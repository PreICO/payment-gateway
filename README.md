<div align="center">
    [![License]][LICENSE.md]
    [![Telegram]][Teletram join]
</div>

--------------------------------------------------------------------------------

[Payment gateway][Teletram join] is a payment gateway between two different
blockchains.

# Requirements
* [Node.js]
* [NPM]
* [PostgreSQL]
* [Redis]
* [Go Ethereum], [Parity Ethereum] or many other RPC providers like [Infura]
* [BitShares Core] or many other RPC providers like [blckchnd]

# Installation
1. Clone the repository:
```bash
git clone https://github.com/fincubator/payment-gateway
cd payment-gateway
```
2. Install all the dependencies listed in the Requirements section
3. Install the app dependencies:
```bash
npm i
```
4. Configure the environment variables in the [config.app.ts] and
[config.db.ts] files.
5. Build the application:
```bash
npm run build
```
6. Run the application:
```bash
npm run serve
```

# Contributing
You can help by working on opened issues, fixing bugs, creating new features or
improving documentation.

Before contributing, please read [CONTRIBUTING.md] first.

# License
Payment gateway is released under the GNU Affero General Public License v3.0.
See [LICENSE.md] for the full licensing condition.

[License]: https://img.shields.io/github/license/fincubator/payment-gateway
[LICENSE.md]: LICENSE.md
[CONTRIBUTING.md]: CONTRIBUTING.md
[Telegram]: https://img.shields.io/badge/Telegram-fincubator-blue?logo=telegram
[Teletram join]: https://t.me/fincubator
[Node.js]: https://nodejs.org/en
[NPM]: https://www.npmjs.com
[PostgreSQL]: https://www.postgresql.org
[Redis]: https://redis.io
[Go Ethereum]: https://geth.ethereum.org
[Parity Ethereum]: https://www.parity.io/ethereum
[Infura]: https://infura.io
[BitShares Core]: https://bitshares.org
[blckchnd]: https://blckchnd.com
[config.app.ts]: src/config/config.app.ts
[config.db.ts]: src/config/config.db.ts
