# ChangeLog

## 1.4.3 (2017/09/23)
 * Several token fixes
 * New log system, using a verbose level
 * Bug fixes

## 1.4.2 (2017/03/09)
 * Added promise support
 * Better JSON parse error handling for environment variables

## 1.4.1 (2017/02/09)
 * Fixed critical bug

## 1.4.0 (2017/02/08)
 * Added support for environment variables

## 1.3.0 (2016/11/26)
 * Fixed critical bug (logger)

## 1.2.0 (2016/11/23)
 * Added mock functionality
 * Dropped Node.js v0.1, v0.12 suport

## 1.1.0 (2016/9/15)
 * The default behavior of lambda-local now does not forcefully call the callback function (`-c` option).
 * Added AWS region option `-r`. Defaults to `us-east-1`.
 * Added AWS profile name option `-p`. 

## 1.0.0 (2016/6/10)
 * lambda-local can now be imported as a node module, and be executed from other node.js programs

## 0.0.10 (2016/5/29)
 * Support for Node.js 4.3.2 runtime
 * Added feature to import AWS profile from commandline option
 * Added necessary environment variables 

## 0.0.9 (2016/4/9)
 * Fixed package.json information for npm

## 0.0.8 (2016/4/9)
 * Added support for all properties in the Context object. 
   Supporting everything in here:
   https://docs.aws.amazon.com/en_us/lambda/latest/dg/nodejs-prog-model-context.html

 * Wrote a mocha unit test for the Context object.

## 0.0.7 (2016/2/21)
 * Minor bug fix: Now correctly outputs the error object when Context.done() has an error.

## 0.0.6 (2015/11/13)
 * Added support for `fail` and `succeed` methods

## 0.0.5 (2015/1/21)
 * First release


