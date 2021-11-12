# @guardian/cdk (with JSII)

_[jsii](https://aws.github.io/jsii/) allows code in any language to naturally
interact with JavaScript classes. It is the technology that enables the AWS
Cloud Development Kit to deliver polyglot libraries from a single codebase!_

The aim of this spike is to see if JSII can be used for @guardian/cdk to
introduce support for other languages, in particular Go and Java (for Scala
projects).

A fuller document on this is here:
https://docs.google.com/document/d/1RAqOjN0o7iegkW-tT-uY27mFHVi2rmxMHwjgSugJnBw/edit#.

## Development

    $ nvm use
    $ npm -i
    $ npm run build:watch

To package, run:

    $ npm run build; npm run package

See `npm run` for further scripts (or look in package.json).
