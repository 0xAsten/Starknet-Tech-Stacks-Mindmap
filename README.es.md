# Starknet-Tech-Stacks-Mindmap
¡Bienvenido al repositorio Tech Stacks Mindmap Starknet! Este proyecto de colaboración abierta tiene como objetivo explorar y documentar las diversas pilas tecnológicas asociadas con Starknet, una poderosa plataforma blockchain.

En este repositorio, encontrarás un mapa mental exhaustivo que organiza visualmente los diferentes componentes, frameworks, herramientas e lenguajes relevantes para el desarrollo en Starknet. El mapa mental sirve como una valiosa referencia para desarrolladores, investigadores y entusiastas interesados en aprovechar las capacidades de Starknet.

![alt text](./images/Starknet.jpg)

El mapa mental se organiza en las siguientes categorías:

- **Lenguajes**
- **Frameworks**
- **Herramientas**
- **Componentes**
- **Recursos**

## Tabla de Contenidos

- [Cairo](#cairo)
  - [Cairo VM](#cairo-vm)
    - [cairo-lang](#cairo-lang)
    - [cairo-vm](#cairo-vm)
  - [Scarb](#scarb)
  - [Starknet Contracts](#starknet-contracts)
    - [protostar](#protostar)
  - [Kakarot](#kakarot)
  - [Cairo Book](#cairo-book)
- [starknet_in_rust](#starknet-in-rust)
- [starknet.py](#starknetpy)
- [Starknet Edu](#starknet-edu)
  - [Starknet Book](#starknet-book)
  - [Starknet Cairo 101](#starknet-cairo-101)
  - [Starknet Accounts](#starknet-accounts)
  - [Starknet ERC721](#starknet-erc721)
  - [Starknet ERC20](#starknet-erc20)
- [Madara](#madara)
- [Blockifier](#blockifier)
- [Sequencer](#sequencer)
  - ~~[lambda_starknet_sequencer](#lambda_starknet_sequencer)~~
- [OpenZeppelin/cairo-contracts](#openzeppelincairo-contracts)
- [alexandria](#alexandria)
- [dojo](#dojo)
  - [Sozu](#sozu)
  - [Katana](#katana)
  - [Torii](#torii)
- [juno](#juno)
- [starknet-rs](#starknet-rs)
- [starkli](#starkli)
- [quickly on-board new developers by examples](#quickly-on-board-new-developers-by-examples)
  - [cairo-by-example](#cairo-by-example)
  - [StarknetByExample](#starknetbyexample)

## Cairo

Repositorio:
https://github.com/starkware-libs/cairo

### Cairo VM

#### cairo-lang

Escrito en Python y actualmente en producción.

Repositorio:
https://github.com/starkware-libs/cairo-lang

#### cairo-vm

Escrito en Rust, reemplazará al escrito en Python. Anteriormente conocido como cairo-rs.

Repository:
https://github.com/lambdaclass/cairo-vm

### Scarb

Gestor de paquetes de Cairo.

https://github.com/software-mansion/scarb

### Contratos Starknet

#### Protostar

Conjunto de herramientas para desarrollar y probar contratos.

Repositorio:
https://github.com/software-mansion/protostar

### Kakarot

Kakarot es un zkEVM escrito en Cairo. Puede utilizarse para ejecutar contratos inteligentes de Ethereum en Starknet.

Repository:
https://github.com/kkrt-labs/kakarot

### Libro de Cairo

Repositorio:
https://github.com/cairo-book

## starknet_in_rust

Escrito en Rust y utiliza cairo-rs para declarar, implementar e interactuar con contratos.

Repositorio:
https://github.com/lambdaclass/starknet_in_rust

## starknet.py

SDK de Python para Starknet.

Repositorio:
https://github.com/software-mansion/starknet.py

## Starknet Edu

Repositorio:
https://github.com/starknet-edu

- Libro de Starknet: https://github.com/starknet-edu/starknetbook
- Starknet Cairo 101: https://github.com/starknet-edu/starknet-cairo-101
- Cuentas Starknet: https://github.com/starknet-edu/starknet-accounts
- Starknet ERC721: https://github.com/starknet-edu/starknet-erc721
- Starknet ERC20: https://github.com/starknet-edu/starknet-erc20

## Madara

Madara utiliza el marco de trabajo Substrate e integra la Cairo VM para la construcción appchain / layer 3.

Substrate es un open-source Rust framework que permite construir blockchains personalizables.

La Cairo VM está diseñada específicamente para generar de manera eficienteValidity Proof para la ejecución de programas.

Al emplear seguimiento de estado y un smart contract para verificar estas pruebas en L2, la appchain creada por Madara asegura una integración segura con Starknet.

Repositorio:
https://github.com/keep-starknet-strange/madara

## Blockifier

Implementación en Rust del componente de ejecución de transacciones en el secuenciador Starknet.

Repositorio:
https://github.com/starkware-libs/blockifier

## Sequencer

- ~~lambda_starknet_sequencer~~

  A Starknet decentralized sequencer implementation

  Repository:
  https://github.com/lambdaclass/lambda_starknet_sequencer

## OpenZeppelin/cairo-contracts

Repositorio:
https://github.com/OpenZeppelin/cairo-contracts

## Alexandria

Una colección de algoritmos y estructuras de datos útiles implementados en Cairo.

Repositorio:
https://github.com/keep-starknet-strange/alexandria

## Dojo

Motor de juegos y conjunto de herramientas para construir juegos en cadena.

- [Sozu](#sozu)
- [Katana](#katana)
- [Torii](#torii)

## Juno

Implementación del cliente de nodo completo de Starknet.

## starknet-rs

starknet-rs, biblioteca completa de Starknet en Rust.

## starkli

Herramienta de CLI para Starknet.

## Incorporar rápidamente a nuevos desarrolladores mediante ejemplos

### cairo-by-example

Repositorio:
https://github.com/lambdaclass/cairo-by-example/

### StarknetByExample

Repositorio:
https://github.com/NethermindEth/StarknetByExample

## Contribuir

Te animamos a contribuir a este proyecto sugiriendo adiciones, modificaciones o correcciones al mapa mental existente. Tus contribuciones pueden ayudar a expandir la base de conocimientos y proporcionar un recurso valioso para la comunidad de Starknet. Ya sea que tengas experiencia en pilas tecnológicas específicas o quieras aprender más sobre el ecosistema de Starknet, tu participación es muy apreciada.

Para contribuir, simplemente bifurca este repositorio, realiza tus cambios y envía una solicitud de extracción.

¡Trabajemos juntos para crear un mapa mental completo y actualizado de las pilas tecnológicas de Starknet! ¡Únete a nosotros para dar forma al futuro de las aplicaciones descentralizadas en Starknet!

Siéntete libre de personalizar esta descripción para que se ajuste a tus objetivos y visión específicos del proyecto.
