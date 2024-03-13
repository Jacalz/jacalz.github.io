+++
title = "Projects"
description = "A showcase of some of my favourite projects."
date = "2024-03-13"
aliases = ["projects"]
author = "Jacob Alzén"
+++

# Current Projects

Below is a list of some of my current projects. These are in constant development.

## [Rymdport](https://rymdport.github.io)

Rymdport (formerly wormhole-gui) is a cross-platform application that lets you easily and safely share files, folders, and text between devices. The data is sent securely with end-to-end encryption using the same protocol as [magic-wormhole](https://github.com/magic-wormhole/magic-wormhole). This means that Rymdport can talk not only to itself, but also to other Wormhole clients (a list of which can be found [here](https://github.com/Jacalz/rymdport/wiki/Supported-clients)).

The transfers are implemented using [wormhole-william](https://github.com/psanford/wormhole-william), a native [Go](https://go.dev) implementation of magic-wormhole. As a result, Rymdport compiles into a native binary with no runtime dependencies while also outperforming the reference implementation of magic-wormhole.

![rymdport](https://raw.githubusercontent.com/Jacalz/rymdport/main/internal/assets/screenshot1.png)

## [3D Wireframes using Linear Algebra](https://github.com/Jacalz/linedisp)

Using coordinate matrices and linear algebra, we can project a 3D model on screen. A linear map using rotation and scale matrices allows support for both rotation and zoom.

![linedisp](https://user-images.githubusercontent.com/25466657/143089168-dc190181-496f-4c5b-8077-0cdbb547ed88.gif)

## [Linear Algebra](https://github.com/Jacalz/linalg)

Fast and easy-to-use package for Linear Algebra calculations. Written in pure Go with no external dependencies.

## [Mathematical String Evaluation](https://github.com/Jacalz/eval)

A minimalistic math parser and evaluator for Go. It implements the shunting-yard-algorithm to parse math expressions from strings.

# Previous Projects

These projects are some that I have previously worked on but consider complete. Some of these might also have been abandoned for other reasons.

## [Asteroids](https://github.com/theJonkan/asteroids)

A clone of the classic Asteroids game recreated using Java Swing. This project was created by Jonathan Björkdahl and me as part of the project in the TDDD30 course at Linköping University.

![asteroids](https://user-images.githubusercontent.com/125046445/218131618-077f0a65-ce57-4587-b8cc-210537d6750a.png)

## [Super Chameleon](https://github.com/Jacalz/super-chameleon)

A 2D pixel art platformer inspired by Super Mario and made for a school project. In Super Chameleon, you play as a chameleon with abilities such as camouflaging and turning into a Jackson’s Chameleon, with horns. The game has been created using only open source software.

![super-chameleon](https://user-images.githubusercontent.com/25466657/107958065-c4f8f580-6fa1-11eb-8382-e4daffb408d4.png)