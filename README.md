# All you need to get started with Elm

![Image](http://www.fictorians.com/wp-content/uploads/2017/03/its-dangerous-to-go-alone-take-this.jpg)

# Install Node.js and NPM
Use NPM to install the Elm Platform and other related tools as npm packages.

1. Start by installing [Node.js](https://nodejs.org/en/) 6.0 or higher. The pre-built installers also automatically install NPM, so there's no separate step. Alternatively, if you're on a Mac and already using the Homebrew package manager, you can install Node.js and NPM using `brew install node`.

2. Once installed, confirm that you have Node.js 6.0 or higher and NPM 2.0 or higher installed by running the following commands:

```
node --version
npm --version
```

# Install the Elm Platform
The Elm Platform is a bundle of all the core development tools you'll use to create Elm applications.

**After installing, you will have the following command line tools:**

* elm-repl — play with Elm expressions
* elm-reactor — get a project going quickly
* elm-make — compile Elm code directly
* elm-package — download packages

1. Since you already have NPM installed, you can install the Elm Platform as an npm package like so:  `npm install -g elm`. By default, npm installs packages to the local (current) directory. Using the -g flag installs the elm package globally so the command-line tools can be accessed from any directory on your system.  If for some reason you don't want to install Elm using NPM, you can download and run the [pre-built Elm installer](https://guide.elm-lang.org/install.html) for your operating system.

2. Once you've installed the Elm Platform, confirm that you have Elm 0.18 installed by running: `elm-make --version`.  The example code included in this course is based on Elm 0.18, so any version that starts with 0.18 should work. However, if you see a version number beginning with 0.19 or higher, then the example code may not compile. To install a compatible version of Elm, run: `npm install -g elm@0.18.0`

3. For your reference: [Elm Core Libraries](http://package.elm-lang.org/packages/elm-lang/core/latest), [html package](http://package.elm-lang.org/packages/elm-lang/html/latest/), and [HTML to Elm](http://mbylstra.github.io/html-to-elm/).

# Additional Elm Tooling
1. For development purposes, use elm-live to recompile Elm files whenever they change and automatically reload the application in the browser. To install it, run: `npm install -g elm-live@2.6.1`

2. Configuring your editor of choice to use an [Elm syntax highlighting plugin](https://guide.elm-lang.org/install.html) is highly recommended. On that page, select your editor and you'll be taken to an appropriate Elm plugin. Note: Tab characters are syntax errors in Elm, so make sure your editor is configured to convert tabs to spaces!

3. Finally, install [elm-format](https://github.com/avh4/elm-format). It automatically formats Elm code to the community standards.  Check out the `elm-format` documentation for instructions on how to enable the format-on-save option. You want the version that's compatible with Elm 0.18.
