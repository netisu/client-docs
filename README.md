## Introduction
This documentation makes use of [Mintlify](https://mintlify.com/). This documentation features the programming language "Clua" (Commonlua) which is basically lua and is built on top of MoonSharp. Check out the project at [Cubern.sbs](https://cubern.sbs/)

## Running locally
You will first be required to install mintlify with:
```bash
npm i -g mintlify
```

and once its downloaded you can `cd` into this repository and execute:
```bash
mintlify dev
```

and this will host the docs locally on your computer. This command will automatically open your computers default browser.

## Contributing
You can fork this repository and make changes to the documentation and open up a newer pull-request. If you have found out a issue you can consider opening a issue. One of contributors will see and make changes to fix that. You're issue will be closed and marked as "duplicate" if the issue was already reported.

## Classes layout
The classes pages are in a flow of:
```
## Properties
#### Property
About the property

## Functions
#### Function(parameter: ParameterType, default_parameter = defaultValue)
About the function + example of usage (if possible)

## Signals
#### Signal
About the signal
```
