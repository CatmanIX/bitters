[![Bitters](http://bitters.bourbon.io/images/bitters-logo.svg)](http://bitters.bourbon.io/)

Add a dash of predefined style to get your [Bourbon](http://bourbon.io) stylesheets started off in the right direction.

Bitters is meant to help designers get projects started on new projects faster. 
It adds enough predefined structure and style to get started quickly but bland enough so that it doesn't dictate any style moving forward.


##Requirements
- SASS 3.0+
- Bourbon 2.0+

##Installation
Install [SASS](http://sass-lang.com/) and [Bourbon](https://github.com/CoRD-Dev/libbourbon/).

(Optional) Install [Neat](https://github.com/CoRD-Dev/libneat/) and [Normalize](https://github.com/CoRD-Dev/libnormalize/).

Navigate to your projects local repository and run:

```bash
git submodule add https://github.com/CoRD-Dev/libbitters.git sass/base
```
(`sass/base` should be the directory your sass/scss files are kept +/base.)

The generated folder will contain all Bitters files.

Import Bitters after Bourbon and Neat in your stylesheet. 
If you are using the Neat overrides found in `_grid-settings.scss`, `@import "base/grid-settings"` between Bourbon and Neat.
All additional imports should be imported below Bitters:

```scss
@import "normalize/normalize";
@import "bourbon/bourbon";
@import "bitters/grid-settings";
@import "neat/neat";
@import "base/base";

// All other imports
```


##Credits
![thoughtbot](http://thoughtbot.com/images/tm/logo.png)

Bitters is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/). Follow [@thoughtbot](http://twitter.com/thoughtbot) on Twitter.

libbitters is maintained by [CoRD](http://cord-dev.github.io/) and [The_Catman](http://catmanix.github.io/).

##License
Bitters is Copyright © 2013 thoughtbot. It is free software, and may be redistributed under the terms specified in the LICENSE file.
