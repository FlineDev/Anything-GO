<p align="center">
    <img src="Logo.png"
      width=600 height=134>
</p>

<p align="center">
    <a href="https://github.com/Flinesoft/Anything-GO/releases">
        <img src="https://img.shields.io/badge/Version-0.0.0-blue.svg"
             alt="Version: 0.0.0">
    </a>
    <a href="https://gitter.im/Flinesoft/Anything-GO?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge">
        <img src="https://img.shields.io/badge/Gitter-Join_Chat!-orange.svg"
             alt="Gitter: Join Chat!">
    </a>
    <a href="https://github.com/Flinesoft/Anything-GO/blob/stable/LICENSE.md">
        <img src="https://img.shields.io/badge/License-Creative_Commons_BY–NC–SA-lightgrey.svg"
             alt="License: Creative Commons BY-NC-SA">
    </a>
</p>

<p align="center">
    <a href="#motivation">Motivation</a>
  • <a href="#goals">Goals</a>
  • <a href="#example-franchises">Example Franchises</a>
  • <a href="https://github.com/Flinesoft/Anything-GO/issues">Issues</a>
  • <a href="#contributing">Contributing</a>
  • <a href="#license">License</a>
</p>

# Anything GO

"Anything GO" is a **collection** of Pokémon GO inspired **augmented reality game concepts** and defines everything needed to implement a similar game for **any franchise or community**.

## Motivation

**Pokémon GO** was released not long ago and it has already been **a huge succes** with an immediate hype all around the world. We too love the idea of **taking gamers outside**, getting them to **discover new places**, meet **new people** and even make them feel like they are **part of a different world** right within our own.

But at the same time we think that Pokémon GO is **overly commercialized** and doesn't **appeal to everybody** – especially those who can't identify themselves with Pokémon. Also it (currently) lacks of many **basic social features** like seeing the **progress of friends** or **connecting with other players around you**. We think we can do better in some areas.

## Goals

Our main goal is to **bring the great ideas behind Pokémon GO to other franchises and communities** so that not only Pokémon fans but *every smartphone user* can profit from the motivational effect the game has on moving more, discovering places and meeting people.

The particular goals of this specific respository are:

- **Analyze the concepts** behind Pokémon GO with respect to the following questions:
  - What makes people **start to play** the game?
  - What makes people **move** (go outside) when playing the game?
  - What makes people **discover** new places?
  - What makes people **stay motivated** and play the game long-term?
- Find the **weaknesses and disadvantages** – using experiences made by players
- Use the concept and weakness analysis results to **develop a refined set of concepts**
- Add more ideas and features to **enhance the social part of the game**

### Out of Scope

Note that *implementing* the concepts is **not part of this repository**. Everybody is **free to use, change and mix** all ideas, concepts and results of this repository and write their own implementations as long as they comply to our [license](#license) (for commercial usage, please contact [Dschee](https://github.com/Dschee)).

### Reference Core Implementations

There will be an **official implementation of a web-backend** written in Ruby on Rails **and a client** written in Swift for iOS though. Those will be reference core implementations and are necessary to make sure the developed concepts within this project **work in practice**. It is likely that they will **lack the sophisticated graphical interfaces and contents** compared to the original Pokémon GO game. So don't expect a full game as a result in the basic examples. We will do our best, however, to make sure the examples are **as extensible as possible**. This will ensure **other developers can build on the examples as a core** and create unique instances of the game for their favorite franchise or their own community.

Currently the web-backend and iOS projects aren't started yet. Once they are, they will be linked here.

## Example Franchises

In order to make sure the **concepts actually make sense** and also that **developers** have an easier time to **understand what we mean** we are gonna use a few example franchises when developing the concepts. Currently those franchises are namely **Harry Potter** and the **Marvel Cinematic Universe**. This means when discussing and explaining the concepts we are gonna give examples of characters, items or other features of those two franchises to clarify the usage.

The reason those two were chosen is simply because **the initiator of this project knows them well** and thinks many others do, too. Also note that there is even **a [petition](http://www.thepetitionsite.com/380/697/285/)** for a Pokémon GO like app from fans for Harry Potter. This project could be a **starting point** to develop such an app as a community-driven open source project (given the right holders allow it).

### Contributing

There are three ways of contributing to this project:

1. Ping people in the [Gitter channel of this repo](https://gitter.im/Flinesoft/Anything-GO) to get in touch live.
2. Use [GitHub issues](https://github.com/Flinesoft/Anything-GO/issues) to discuss a concept, or leave comments on existing issues.
3. Fork this repo, do your changes and file a pull request to contribute changes.

Note that you may want to do either one or both of the first two steps before going on to step 3. This increases the chances that your pull request is going to be merged.

***Important:***
*By contributing to this repository you agree that all content provided becomes part of this project and therefore the same license applies to the newly provided content as to all previous content. See the file `LICENSE.txt` for license details.*

## License

<p style="float: right;">
    <img src="by-nc-sa.eu.png"
      width=143 height=50>
</p>

This work is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or open the file `LICENSE.txt`.
