# PreactX with customised Milligram CSS

This repository shows an example on how to use customised [Milligram](https://milligram.io/) CSS library with JS frontend app (example is based on [PreactX](https://preactjs.com/) but the principle applies to any other JS framework).

Application skeleton has been generated with [preact-cli v3](https://preactjs.com/cli) and later only lightly modified to remove extra stuff like tests.

Free Google fonts may be downloaded for self-hosting using [helper application](https://google-webfonts-helper.herokuapp.com/fonts) that allows selection of weights and scripts included in package. This is not required and fonts may be as well loaded with external CSS. This example uses [Nunito](https://fonts.google.com/specimen/Nunito) font by Vernon Adams in latin + latin extended scripts. The reason I included self-hosting fonts in the example is that I could not find any NPM package that provides latin extended script so to make Central European text to look good I'd have to either self-host selected font or load it from external source.
