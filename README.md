# Company Chat Roulette

## Usage

Set an ADDRESSES environment variable to a comma-separated list of addresses,
or make a map in .lein-env with an `:addresses` key with the value being a
string that's a comma-separated list of addresses.

`lein run` to send email to everybody on that list. Assumes a local working mail
transfer agent.

## License

Copyright © 2014 Nathan L Smith

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
