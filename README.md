[![Logo][jhipster-image]][jhipster-url]

Greetings, Java Hipster!

This is the JHipster Angular 2+ utilities library


[![NPM version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Dependency Status][daviddm-image]][daviddm-url]

Full documentation and information is available on our website at [http://jhipster.github.io/][jhipster-url]

Please read our [guidelines](https://github.com/jhipster/generator-jhipster/CONTRIBUTING.md#submitting-an-issue) before submitting an issue. If your issue is a bug, please use the bug template pre populated [here](https://github.com/jhipster/generator-jhipster/issues/new). For feature requests and queries you can use [this template][feature-template].

[jhipster-image]: https://raw.githubusercontent.com/jhipster/jhipster.github.io/master/images/logo/logo-jhipster2x.png
[jhipster-url]: http://jhipster.github.io/
[npm-image]: https://badge.fury.io/js/ng-jhipster.svg
[npm-url]: https://npmjs.org/package/ng-jhipster
[travis-image]: https://travis-ci.org/jhipster/ng-jhipster.svg?branch=master
[travis-url]: https://travis-ci.org/jhipster/ng-jhipster
[daviddm-image]: https://david-dm.org/jhipster/ng-jhipster.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/jhipster/ng-jhipster
[feature-template]: https://github.com/jhipster/generator-jhipster/issues/new?body=*%20**Overview%20of%20the%20request**%0A%0A%3C!--%20what%20is%20the%20query%20or%20request%20--%3E%0A%0A*%20**Motivation%20for%20or%20Use%20Case**%20%0A%0A%3C!--%20explain%20why%20this%20is%20a%20required%20for%20you%20--%3E%0A%0A%0A*%20**Browsers%20and%20Operating%20System**%20%0A%0A%3C!--%20is%20this%20a%20problem%20with%20all%20browsers%20or%20only%20IE8%3F%20--%3E%0A%0A%0A*%20**Related%20issues**%20%0A%0A%3C!--%20has%20a%20similar%20issue%20been%20reported%20before%3F%20--%3E%0A%0A*%20**Suggest%20a%20Fix**%20%0A%0A%3C!--%20if%20you%20can%27t%20fix%20this%20yourself%2C%20perhaps%20you%20can%20point%20to%20what%20might%20be%0A%20%20causing%20the%20problem%20(line%20of%20code%20or%20commit)%20--%3E

## Development setup

You need NodeJS and NPM.

### Fork the ng-jhipster project

Go to the [ng-jhipster project](https://github.com/jhipster/ng-jhipster) and click on the "fork" button. You can then clone your own fork of the project, and start working on it.

[Please read the Github forking documentation for more information](https://help.github.com/articles/fork-a-repo)

### Build

Run `npm install` to install all dependencies.

Make some changes, run `npm run test` to run both tslint and karma tests.

Build the library with `npm run build` and then `npm run ngc`.

Package the library with `npm pack`, this will create an archive `ng-jhipster-vX.Y.Z.tgz`.

For testing, you will want to integrate this archive into an application generated by JHipster.

Go to your generated JHipster application and run...

    npm install path/to/ng-jhipster/ng-jhipster-vX.Y.Z.tgz

...so that your JHipster application uses the content of this archive as `ng-jhipster` dependency which is located in `node_modules/ng-jhipster`.
