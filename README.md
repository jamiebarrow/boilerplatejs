![BoilerplateJS - JavaScript Reference Architecture](https://github.com/jamiebarrow/boilerplatejs-website/raw/master/images/logo.jpg)

## Introduction ##
We wrote boilerplateJS to take the pain out of large scale Javascript/HTML5 product development. 
* BoilerplateJS is a collection of product engineering patterns, and a solid integration of industry-leading Javascript frameworks.
* It is NEITHER a website building tool, NOR a utility library solving just a single concern (such as MVC). 
* BoilerplateJS is your own startup code to kickstart your next large-scale javascript product. It is just that we did some basic coding and library integrations to make your life easy!

## Architectural Concerns - Large Scale Development ##
BoilerplateJS addresses the following concerns that you will have in large-scale javascript development:
* Structuring the codebase
* Best practices of OO + Functional programming
* Building a product suite with complex product module hierachy
* URL routing, browser history, back/forward buttons
* Self contained UI components
* JS Unit Testing
* Inter-module event messaging
* Localization support
* Minification, obfuscation and optimization
* Documentation Generation

## Project Home ##
There used to be details and live samples hosted at the project website:

http://boilerplatejs.org

However this is no longer maintained, and the source for the website can be found in the below repository:
https://github.com/jamiebarrow/boilerplatejs-website

## Viewing Sample Locally ##

You can run the below npm scripts for convenience, to launch the sample:

```shell
npm start
```

To run an optimized version that has gone through the `r.js` optimizer, do the below:
```shell
npm run samples:build
npm run samples:serve
```

See [./tools/optimizer/README.md](./tools/optimizer/README.md) for more details.


## Code Documentation Generation ##
It is possible to generate code documentation using YUIDoc.
See [`./tools/documentation/README.md`](./tools/documentation/README.md) for more information.

This can be generated using a convenience npm script:

```shell
npm run docs:generate
```

And these can then be served using an `http-server` development server using:
```shell
npm run docs:serve
```

## License ##
BoilerplateJS code is free for commercial and non-commercial deployment and distribution. BoilerplateJS is released under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

This repository was forked from:
https://github.com/99x/boilerplatejs
