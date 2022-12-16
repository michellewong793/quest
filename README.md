# Quest: Smart Contracts zkApps Submission by Miche Wong for zkCohort 0 

This is the repository for the smart contracts for the Quest project.
This was adapted from the zkOracle tutorial, in which we created an oracle to return some data about a user's status after verifying their email. For the purposes of time constraint, we mock this process and return a signature to verify the data came from our oracle, an ID for the user, and some data, like a unique hash to identify the user. 
This smart contract is then deployed to NPM, then can be used to verify anytime someone is using Quest to post on an online forum, their unique ID is verifiable by the smart contract without revealing the user's work email or identity. 
In the future, what I would continue to build is this:
1) Verify email process that again mocks the resulting signature and user id, and hash 
2) Finish deploying NPM library (ran into some errors on Thursday night) 

The frontend can be found here: 
first-quest repository (still private but will make public) 

## How to build

```sh
npm run build
```

## How to run tests

```sh
npm run test
npm run testw # watch mode
```

## How to run coverage

```sh
npm run coverage
```


