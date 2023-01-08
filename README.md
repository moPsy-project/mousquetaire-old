# Mousquetaire Eurorack Module

> Eurorack Synthesizer module for Audio/CV Adder (all4one) and Buffered Multiple (one4all)


## Features

The PCBs in this project can be assembled in two different ways:

1. Unity gain audio/CV mixer (adder) as all4one variant.
2. Buffered multiple as one4all variant.

Or half and half with a mixed business board.

The generic jack board only exposes the jacks in a stripboard-friendly format to enable
prototyping.


## Components

* [front panel](frontpanel/): comes with 8 jacks and does not have function-specific markings to be usable for both variants or further projects. Some hand painting might be beneficial.
* [8 generic jacks board](8x1-4he-generic-jacks/): contains Eurorack jacks in a 2x4 configuration and is intended as an interface to stripboard protoypes.
* [all4one business](all4one-business/): contains the actual logic for the unity gain mixer
* [one4all business](one4all-business/): contains the actual logic for the buffered multiple

The module can also be set up as an unbuffered multiple without any additional business logic board.


## License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

BY: Stefan Haun (mail@tuxathome.de)

See [LICENSE.txt](LICENSE.txt) for details.

The moPsy logo and derived artifacts are © 2021-2023 Stefan Haun
Reproduction on unaltered boards is permitted.
