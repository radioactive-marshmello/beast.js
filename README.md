```shell
  ╔╗  ╔═╗ ╔═╗ ╔═╗ ╔╦╗
  ╠╩╗ ║╣  ╠═╣ ╚═╗  ║
  ╚═╝ ╚═╝ ╩ ╩ ╚═╝  ╩
```

![The beast game](https://raw.githubusercontent.com/dominikwilkowski/beast.js/master/assets/play.gif)

> BEAST.js is an homage to the 1984 ASCII game "[BEAST](https://en.wikipedia.org/wiki/Beast_(video_game))" from Dan Baker, Alan Brown, Mark Hamilton and
> Derrick Shadel written in node.

# Beast.js

- [How to install](#how-to-install)
- [How to play](#how-to-play)
- [Contributing](#contributing)
- [Test](#test)
- [Release History](#release-history)
- [License](#license)


## How to install

_Note: This games requires [Node](https://nodejs.org/) >= 6._

[Download the game](https://github.com/dominikwilkowski/beast.js/archive/master.zip) from this repo and install it's dependencies via:

```shell
npm i
```

or

```
yarn
```

Then run:

```shell
node prod/index.js
```


## How to play

The goal is to squash all beasts in each level. To squash a beast between two or more blocks.
When a beast touches you, you die. You got four lives to spare.
Once all beasts are squashed you move on to the next level. There are four levels so far. Easily configurable if you want to extend them.
Press `q` to quit.


## Contributing

Please look at the coding style and work with it, not against it ;)
Run grunt to build and watch the project. _(gulp coming)_

```shell
grunt
```


## Test

TODO


## Release History
* 0.1.5  -  Fixed dependencies
* 0.1.4  -  Fixed lives color bug
* 0.1.3  -  Improved drawing
* 0.1.2  -  Fixed error message
* 0.1.1  -  Added level indicator, fixed lives display
* 0.1.0  -  alpha release


## License
Copyright (c) Dominik Wilkowski. Licensed under the [GNU GPLv3](https://github.com/dominikwilkowski/beast.js/blob/master/LICENSE).