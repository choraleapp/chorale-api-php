# Chorale API

[![Join Discord](https://img.shields.io/discord/330694680318574592.svg?style=flat-square)](https://discord.gg/BUbfvsM)
[![Twitter Follow](https://img.shields.io/twitter/follow/choraleapp.svg?style=social&label=follow)](https://twitter.com/choraleapp)

The Chorale backend is written in PHP and runs with MariaDB. `master` branch code currently deploys to production servers.

## Development
I use Windows 10 with WAMP to test and run my code. I am using VS Code to write it.

TODO:
1. Make sure all code meets the [PSR-1](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md) standard.
2. Rewrite code so it is clean and readable.
3. Fix 2FA as it currently outputs a different code than Google Auth and Authy.
4. Wait for results from [DB StrawPoll](http://www.strawpoll.me/14130030) and then change DB based on results.
5. Add required endpoints
6. Anything else

## Contribute

Feel free to open an issue for any bug, feature, or request. If you want to make a PR, make sure the change has been discussed or else your PR will get rejected.

## Coding Standard
We are using the [PSR-1](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md) coding standard. Make sure all PRs are in this style or they will be rejected as well.

## License

Copyright Chorale, 2017

Licensed under the Apache License, Version 2.0 (the “License”); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
