# PROTOCOL_V2

> Anticloud offline package — upstream: aave/protocol-v2 @ `master`.

## What This Project Does

Aave Protocol V2

## Upstream README

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Build pass](https://github.com/AAVE/protocol-v2/actions/workflows/node.js.yml/badge.svg)](https://github.com/aave/protocol-v2/actions/workflows/node.js.yml)
```
        .///.                .///.     //.            .//  `/////////////-
       `++:++`              .++:++`    :++`          `++:  `++:......---.`
      `/+: -+/`            `++- :+/`    /+/         `/+/   `++.
      /+/   :+/            /+:   /+/    `/+/        /+/`   `++.
  -::/++::`  /+:       -::/++::` `/+:    `++:      :++`    `++/:::::::::.
  -:+++::-`  `/+:      --++/---`  `++-    .++-    -++.     `++/:::::::::.
   -++.       .++-      -++`       .++.    .++.  .++-      `++.
  .++-         -++.    .++.         -++.    -++``++-       `++.
 `++:           :++`  .++-           :++`    :+//+:        `++:----------`
 -/:             :/-  -/:             :/.     ://:         `/////////////-
```

# Aave Protocol v2

This repository contains the smart contracts source code and markets configuration for Aave Protocol V2. The repository uses Docker Compose and Hardhat as development enviroment for compilation, testing and deployment tasks.

## What is Aave?

Aave is a decentralized non-custodial liquidity markets protocol where users can participate as depositors or borrowers. Depositors provide liquidity to the market to earn a passive income, while borrowers are able to borrow in an overcollateralized (perpetually) or undercollateralized (one-block liquidity) fashion.

## Documentation

The documentation of Aave V2 is in the following [Aave V2 documentation](https://docs.aave.com/developers/v/2.0/) link. At the documentation you can learn more about the protocol, see the contract interfaces, integration guides and audits.

For getting the latest contracts addresses, please check the [Deployed contracts](https://docs.aave.com/developers/v/2.0/deployed-contracts/deployed-contracts) page at the documentation to stay up to date.

A more detailed and technical description of the protocol can be found in this repository, [here](./aave-v2-whitepaper.pdf)

## Audits

- MixBytes (16/09/2020 - 03/12/2020): [report](./audits/Mixbytes-aave-v2-03-12-2020.pdf)
- PeckShield (29/09/2020 - 03/12/2020) : [report](./audits/Peckshield-aave-v2-03-12-2020-EN.pdf) (Also available in Chinese in the same folder)
- CertiK (28/09/2020 - 02/12/2020): [report](./audits/Certik-aave-v2-03-12-2020.pdf)
- Consensys Diligence (09/09/2020 - 09/10/2020): [report](https://consensys.net/diligence/audits/2020/09/aave-protocol-v2/)
- Certora, formal verification (02/08/2020 - 29/10/2020): [report](./audits/Certora-FV-aave-v2-03-12-2020.pdf)
- SigmaPrime (January 2021): [report](./audits/SigmaPrime-aave-v2-01-2021.pdf)

## Connect with the community

You can join at the [Discord](http://aave.com/discord) channel or at the [Governance Forum](https://governance.aave.com/) for asking questions about the protoco

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
