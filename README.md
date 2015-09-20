# SOILsafe

SOIL QT5 Wallet

SoilWallet is a free software wallet/front-end for GSoil.

## Usage

GSoil 1.0.2+ is required to be running for SoilWallet to work.

SoilWallet should auto-detect geth's IPC file/name and work "out of the box" as long as geth is running.

If SoilWallet fails to detect the IPC file/name you can specify it in the settings panel.

Do not run SoilWallet while gsoil is syncing, it will just lock down processing all the blocks until syncing is done.

## License

SoilWallet is licensed under the GPLv3 license. See LICENSE for more info.

## Donations for Etherwall

#### Bitcoin
`1NcJoao879C1pSKvFqnUKD6wKtFpCMppP6`

#### Litecoin
`LcTfGmqpXCiG7UikBDTa4ZiJMS5cRxSXHm`

#### Ether
`0xc64b50db57c0362e27a32b65bd29363f29fdfa59`

## Development

### Requirements

GSoil 1.0.2+

Qt5.2+ with qmake

### Building

qmake -config release && make
