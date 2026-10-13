# Awesome ECS with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Entity-Component-System (ECS) libraries and resources.

## Contents

* [ECS Libraries](#ecs-libraries)
* [Applications powered by ECS](#applications-powered-by-ecs)
  * [Game Engines](#game-engines)
  * [Graphics Engines](#graphics-engines)
  * [Physics Libraries](#physics-libraries)
* [Other Resources](#other-resources)
  * [Benchmarks](#benchmarks)
  * [Blog Posts](#blog-posts)
  * [Talks & Slides](#talks--slides)
  * [Books](#books)
  * [Tutorials](#tutorials)
  * [Lists](#lists)
  * [References](#references)
* [Contributing](#contributing)

> **Legend**: 🟢 commit within 1 yr · 🟡 commit within 3 yr · 💀 archived · ⭐ GitHub stars as of 2026-10-12. Software entries are ordered by stars; inactive entries (archived, or no commits for 3+ years) are folded at the end of each software category. Other resources keep their existing order.

## [ECS Libraries](#contents)

*Libraries and frameworks implementing the Entity-Component-System pattern.*

#### C/C++

* 🟢 [entt](https://github.com/skypjack/entt) ⭐ 13,192 | 🐛 14 | 🌐 C++ | 📅 2026-10-13 - Fast and reliable entity-component system. [⭐ 13.2k](https://github.com/skypjack/entt) ⭐ 13,192 | 🐛 14 | 🌐 C++ | 📅 2026-10-13
* 🟢 [Flecs](https://github.com/SanderMertens/flecs) ⭐ 8,741 | 🐛 62 | 🌐 C | 📅 2026-10-03 - A Multithreaded Entity Component System written for C89 & C99. [⭐ 8.7k](https://github.com/SanderMertens/flecs) ⭐ 8,741 | 🐛 62 | 🌐 C | 📅 2026-10-03
* 🟢 [WickedEngine's ECS](https://github.com/turanszkij/WickedEngine/blob/master/WickedEngine/wiECS.h) ⭐ 7,289 | 🐛 114 | 🌐 C++ | 📅 2026-10-12 - WickedEngine's ECS implementation. [⭐ 7.3k](https://github.com/turanszkij/WickedEngine) ⭐ 7,289 | 🐛 114 | 🌐 C++ | 📅 2026-10-12
* 🟡 [EntityX](https://github.com/alecthomas/entityx) ⭐ 2,346 | 🐛 18 | 🌐 C++ | 📅 2025-08-23 - Fast, type-safe C++ entity component system. [⭐ 2.3k](https://github.com/alecthomas/entityx) ⭐ 2,346 | 🐛 18 | 🌐 C++ | 📅 2025-08-23
* 🟢 [pico\_ecs](https://github.com/empyreanx/pico_headers) ⭐ 564 | 🐛 4 | 🌐 C | 📅 2026-08-22 - Single-header and cross-platform ECS. [⭐ 564](https://github.com/empyreanx/pico_headers) ⭐ 564 | 🐛 4 | 🌐 C | 📅 2026-08-22
* 🟢 [Gaia-ECS](https://github.com/richardbiely/gaia-ecs) ⭐ 134 | 🐛 6 | 🌐 C++ | 📅 2026-10-11 - Fast and type-safe C++17 archetype-based entity component system. [⭐ 134](https://github.com/richardbiely/gaia-ecs) ⭐ 134 | 🐛 6 | 🌐 C++ | 📅 2026-10-11
* 🟢 [mustache](https://github.com/kirillochnev/mustache) ⭐ 78 | 🐛 6 | 🌐 C++ | 📅 2026-01-20 - A fast, modern C++ entity component system. [⭐ 78](https://github.com/kirillochnev/mustache) ⭐ 78 | 🐛 6 | 🌐 C++ | 📅 2026-01-20

#### C\#

* 🟢 [Arch](https://github.com/genaray/Arch) ⭐ 1,847 | 🐛 43 | 🌐 C# | 📅 2026-09-22 - A high-performance Archetype & Chunks Entity Component System for game development and data-oriented programming. [⭐ 1.8k](https://github.com/genaray/Arch) ⭐ 1,847 | 🐛 43 | 🌐 C# | 📅 2026-09-22
* 🟡 [Svelto.ECS](https://github.com/sebas77/Svelto.ECS) ⭐ 1,366 | 🐛 2 | 🌐 C# | 📅 2025-05-01 - Lightweight data oriented entity component system framework. [⭐ 1.4k](https://github.com/sebas77/Svelto.ECS) ⭐ 1,366 | 🐛 2 | 🌐 C# | 📅 2025-05-01
* 🟢 [Friflo Engine ECS](https://github.com/friflo/Friflo.Engine.ECS) ⭐ 785 | 🐛 41 | 🌐 C# | 📅 2026-10-13 - ECS for .NET with focus on performance, cache locality and DX. [⭐ 785](https://github.com/friflo/Friflo.Engine.ECS) ⭐ 785 | 🐛 41 | 🌐 C# | 📅 2026-10-13
* 🟡 [Morpeh](https://github.com/scellecs/morpeh) ⭐ 672 | 🐛 10 | 🌐 C# | 📅 2026-09-14 - ECS Framework for Unity Game Engine and .NET Platform. [⭐ 672](https://github.com/scellecs/morpeh) ⭐ 672 | 🐛 10 | 🌐 C# | 📅 2026-09-14
* 🟢 [Fennecs](https://github.com/outfox/fennecs) ⭐ 470 | 🐛 8 | 🌐 C# | 📅 2026-10-08 - ... the tiny, tiny, high-energy Entity-Component System! [⭐ 470](https://github.com/outfox/fennecs) ⭐ 470 | 🐛 8 | 🌐 C# | 📅 2026-10-08
* 🟢 [DragonECS](https://github.com/DCFApixels/DragonECS) ⭐ 343 | 🐛 0 | 🌐 C# | 📅 2026-09-20 - ECS for Unity and .NET. [⭐ 343](https://github.com/DCFApixels/DragonECS) ⭐ 343 | 🐛 0 | 🌐 C# | 📅 2026-09-20
* 🟢 [ME.BECS](https://github.com/chromealex/ME.BECS) ⭐ 257 | 🐛 1 | 🌐 C# | 📅 2026-10-12 - ECS for Unity with full game state automatic rollbacks. [⭐ 257](https://github.com/chromealex/ME.BECS) ⭐ 257 | 🐛 1 | 🌐 C# | 📅 2026-10-12
* 🟢 [Massive ECS](https://github.com/nilpunch/massive-ecs) ⭐ 225 | 🐛 10 | 🌐 C# | 📅 2026-04-01 - Bitset-based ECS with rollbacks. C# library and Unity package. [⭐ 224](https://github.com/nilpunch/massive-ecs) ⭐ 225 | 🐛 10 | 🌐 C# | 📅 2026-04-01
* 🟢 [Static ECS](https://github.com/Felid-Force-Studios/StaticEcs) ⭐ 211 | 🐛 0 | 🌐 C# | 📅 2026-10-07 - C# Hierarchical Inverted Bitmap ECS framework. [⭐ 211](https://github.com/Felid-Force-Studios/StaticEcs) ⭐ 211 | 🐛 0 | 🌐 C# | 📅 2026-10-07
* 🟢 [Frent](https://github.com/itsBuggingMe/Frent) ⭐ 187 | 🐛 6 | 🌐 C# | 📅 2026-10-08 - Data oriented ECF with an ECS api for C#, Godot, and Unity. [⭐ 187](https://github.com/itsBuggingMe/Frent) ⭐ 187 | 🐛 6 | 🌐 C# | 📅 2026-10-08
* 🟢 [TinyEcs](https://github.com/andreakarasho/TinyEcs) ⭐ 153 | 🐛 6 | 🌐 C# | 📅 2026-10-11 - A tiny bevy-like archetype-style ECS library for dotnet. [⭐ 153](https://github.com/andreakarasho/TinyEcs) ⭐ 153 | 🐛 6 | 🌐 C# | 📅 2026-10-11

#### Common Lisp

* [cl-fast-ecs](https://gitlab.com/lockie/cl-fast-ecs) - Blazingly fast Entity-Component-System microframework. \[[gitlab](https://gitlab.com/lockie/cl-fast-ecs)]

#### Elixir

* 🟡 [ECSx](https://github.com/ecsx-framework/ECSx) ⭐ 270 | 🐛 14 | 🌐 Elixir | 📅 2025-01-25 - An ECS framework for Elixir. [⭐ 270](https://github.com/ecsx-framework/ECSx) ⭐ 270 | 🐛 14 | 🌐 Elixir | 📅 2025-01-25

#### Python

* 🟢 [esper](https://github.com/benmoran56/esper) ⭐ 703 | 🐛 4 | 🌐 Python | 📅 2026-09-20 - A lightweight Entity System for Python. [⭐ 703](https://github.com/benmoran56/esper) ⭐ 703 | 🐛 4 | 🌐 Python | 📅 2026-09-20

#### Rust

* 🟢 [bevy\_ecs](https://github.com/bevyengine/bevy/tree/main/crates/bevy_ecs) ⭐ 48,975 | 🐛 3,511 | 🌐 Rust | 📅 2026-10-13 - Simple to use, ergonomic, fast, massively parallel, opinionated, and featureful written in Rust. [⭐ 48.9k](https://github.com/bevyengine/bevy) ⭐ 48,975 | 🐛 3,511 | 🌐 Rust | 📅 2026-10-13
* 🟡 [specs](https://github.com/amethyst/specs) ⭐ 2,615 | 🐛 48 | 🌐 Rust | 📅 2024-06-07 - Parallel entity component system written in Rust. [⭐ 2.6k](https://github.com/amethyst/specs) ⭐ 2,615 | 🐛 48 | 🌐 Rust | 📅 2024-06-07
* 🟢 [hecs](https://github.com/Ralith/hecs) ⭐ 1,381 | 🐛 34 | 🌐 Rust | 📅 2026-10-08 - High-performance, minimalist entity-component-system. [⭐ 1.4k](https://github.com/Ralith/hecs) ⭐ 1,381 | 🐛 34 | 🌐 Rust | 📅 2026-10-08
* 🟢 [shipyard](https://github.com/leudz/shipyard) ⭐ 891 | 🐛 8 | 🌐 Rust | 📅 2026-10-04 - Entity Component System written in Rust. [⭐ 891](https://github.com/leudz/shipyard) ⭐ 891 | 🐛 8 | 🌐 Rust | 📅 2026-10-04

#### Go

* 🟡 [ecs](https://github.com/EngoEngine/ecs) ⭐ 338 | 🐛 6 | 🌐 Go | 📅 2023-12-21 - A Go-implementation of the Entity-Component-System paradigm. [⭐ 338](https://github.com/EngoEngine/ecs) ⭐ 338 | 🐛 6 | 🌐 Go | 📅 2023-12-21
* 🟢 [Ark](https://github.com/mlange-42/ark) ⭐ 302 | 🐛 7 | 🌐 Go | 📅 2026-10-12 - An archetype-based Entity Component System for Go. [⭐ 302](https://github.com/mlange-42/ark) ⭐ 302 | 🐛 7 | 🌐 Go | 📅 2026-10-12

#### Lua

* 🟢 [Concord](https://github.com/Keyslam-Group/Concord) ⭐ 326 | 🐛 10 | 🌐 Lua | 📅 2026-09-07 - A feature-complete ECS library. [⭐ 326](https://github.com/Keyslam-Group/Concord) ⭐ 326 | 🐛 10 | 🌐 Lua | 📅 2026-09-07
* 🟢 [evolved.lua](https://github.com/BlackMATov/evolved.lua) ⭐ 224 | 🐛 1 | 🌐 Lua | 📅 2026-10-11 - Evolved ECS (Entity-Component-System) for Lua. [⭐ 224](https://github.com/BlackMATov/evolved.lua) ⭐ 224 | 🐛 1 | 🌐 Lua | 📅 2026-10-11

#### Julia

* 🟢 [Ark.jl](https://github.com/ark-ecs/Ark.jl) ⭐ 84 | 🐛 42 | 🌐 Julia | 📅 2026-10-13 - An archetype-based Entity Component System (ECS) for Julia. It is a port of the Go ECS Ark. [⭐ 84](https://github.com/ark-ecs/Ark.jl) ⭐ 84 | 🐛 42 | 🌐 Julia | 📅 2026-10-13

#### Kotlin

* 🟢 [Fleks](https://github.com/Quillraven/Fleks) ⭐ 270 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-29 - Fast, lightweight, multi-platform entity component system in Kotlin. [⭐ 270](https://github.com/Quillraven/Fleks) ⭐ 270 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-29

#### JavaScript / TypeScript

* 🟢 [bitECS](https://github.com/NateTheGreatt/bitECS) ⭐ 1,520 | 🐛 21 | 🌐 TypeScript | 📅 2026-08-24 - Functional, minimal, data-oriented, ultra-high performance ECS library. [⭐ 1.5k](https://github.com/NateTheGreatt/bitECS) ⭐ 1,520 | 🐛 21 | 🌐 TypeScript | 📅 2026-08-24
* 🟢 [miniplex](https://github.com/hmans/miniplex) ⭐ 1,057 | 🐛 26 | 🌐 TypeScript | 📅 2026-04-05 - The gentle game entity manager, focused on ease of use and developer experience. [⭐ 1.1k](https://github.com/hmans/miniplex) ⭐ 1,057 | 🐛 26 | 🌐 TypeScript | 📅 2026-04-05
* 🟢 [becsy](https://github.com/LastOliveGames/becsy) ⭐ 298 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-02 - A multithreaded Entity Component System (ECS) for TypeScript and JavaScript, inspired by ECSY and bitecs. [⭐ 298](https://github.com/LastOliveGames/becsy) ⭐ 298 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-02
* 🟡 [Thyseus](https://github.com/JaimeGensler/thyseus) ⭐ 86 | 🐛 16 | 🌐 TypeScript | 📅 2024-05-06 - An archetypal Entity Component System, built entirely in Typescript. [⭐ 86](https://github.com/JaimeGensler/thyseus) ⭐ 86 | 🐛 16 | 🌐 TypeScript | 📅 2024-05-06
* 🟢 [Woven-ECS](https://woven-ecs.dev/) - A multithreaded ECS framework for TypeScript aimed at collaborative browser applications. [⭐ 12](https://github.com/WillH0lt/woven-ecs) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-24

#### Zig

* 🟢 [Zig ECS](https://github.com/prime31/zig-ecs) ⭐ 431 | 🐛 8 | 🌐 Zig | 📅 2026-05-18 - A Zig port of the fantasic Entt. [⭐ 431](https://github.com/prime31/zig-ecs) ⭐ 431 | 🐛 8 | 🌐 Zig | 📅 2026-05-18
* 🟢 [ZCS](https://github.com/Games-by-Mason/ZCS) ⭐ 151 | 🐛 20 | 🌐 Zig | 📅 2025-12-16 - An archetype based entity component system written in Zig. [⭐ 151](https://github.com/Games-by-Mason/ZCS) ⭐ 151 | 🐛 20 | 🌐 Zig | 📅 2025-12-16
* 🟢 [knoedel](https://github.com/Lommix/knoedel) ⭐ 47 | 🐛 2 | 🌐 Zig | 📅 2026-09-25 - Data oriented application framework written in Zig (ECS). [⭐ 47](https://github.com/Lommix/knoedel) ⭐ 47 | 🐛 2 | 🌐 Zig | 📅 2026-09-25
* 🟡 [mach-ecs](https://github.com/hexops-graveyard/mach-ecs) ⭐ 34 | 🐛 0 | 📅 2024-04-21 - Entity Component System from first-principles designed for Zig. [⭐ 34](https://github.com/hexops-graveyard/mach-ecs) ⭐ 34 | 🐛 0 | 📅 2024-04-21
* 🟢 [Comptime ECS](https://github.com/Very-Blank/Ecs) ⭐ 4 | 🐛 1 | 🌐 Zig | 📅 2026-07-20 - Comptime-defined ECS implementation in Zig. [⭐ 4](https://github.com/Very-Blank/Ecs) ⭐ 4 | 🐛 1 | 🌐 Zig | 📅 2026-07-20

#### Haskell

* 🟢 [apecs](https://github.com/jonascarpay/apecs) ⭐ 425 | 🐛 19 | 🌐 Haskell | 📅 2026-08-23 - A fast, extensible, type driven Haskell ECS framework for games. [⭐ 425](https://github.com/jonascarpay/apecs) ⭐ 425 | 🐛 19 | 🌐 Haskell | 📅 2026-08-23

<details>
<summary>Inactive (22): archived or no commits for 3+ years</summary>

* [Entitas](https://github.com/sschmid/Entitas) ⭐ 7,678 | 🐛 97 | 🌐 C# | 📅 2023-12-30 - The Entity Component System Framework for C# and Unity. [⭐ 7.7k](https://github.com/sschmid/Entitas) ⭐ 7,678 | 🐛 97 | 🌐 C# | 📅 2023-12-30 · last commit 2023
* [legion](https://github.com/amethyst/legion) ⭐ 1,721 | 🐛 96 | 🌐 Rust | 📅 2021-12-30 - High performance Rust ECS library. [⭐ 1.7k](https://github.com/amethyst/legion) ⭐ 1,721 | 🐛 96 | 🌐 Rust | 📅 2021-12-30 · last commit 2021
* 💀 [ECSY](https://github.com/ecsyjs/ecsy) ⚠️ Archived - Entity Component System for javascript. [⭐ 1.2k](https://github.com/ecsyjs/ecsy) ⚠️ Archived · last commit 2025
* [Artemis-odb](https://github.com/junkdog/artemis-odb) ⭐ 832 | 🐛 41 | 🌐 Java | 📅 2023-04-14 - A continuation of the popular Artemis ECS framework. [⭐ 832](https://github.com/junkdog/artemis-odb) ⭐ 832 | 🐛 41 | 🌐 Java | 📅 2023-04-14 · last commit 2021
* [tiny-ecs](https://github.com/bakpakin/tiny-ecs) ⭐ 789 | 🐛 0 | 🌐 Lua | 📅 2023-03-15 - Entity Component System for Lua that's simple, flexible, and useful. [⭐ 789](https://github.com/bakpakin/tiny-ecs) ⭐ 789 | 🐛 0 | 🌐 Lua | 📅 2023-03-15 · last commit 2020
* [DefaultEcs](https://github.com/Doraku/DefaultEcs) ⭐ 765 | 🐛 20 | 🌐 C# | 📅 2024-03-01 - ECS for syntax and usage simplicity with maximum performance. [⭐ 765](https://github.com/Doraku/DefaultEcs) ⭐ 765 | 🐛 20 | 🌐 C# | 📅 2024-03-01 · last commit 2023
* [Kengine](https://github.com/phisko/kengine) ⭐ 618 | 🐛 1 | 🌐 C++ | 📅 2023-03-10 - Game engine with an Entity-Component-System (ECS) architecture. [⭐ 618](https://github.com/phisko/kengine) ⭐ 618 | 🐛 1 | 🌐 C++ | 📅 2023-03-10 · last commit 2023
* [ecst](https://github.com/vittorioromeo/ecst) ⭐ 490 | 🐛 14 | 🌐 C++ | 📅 2019-09-03 - Experimental C++14 multithreaded compile-time entity-compnent-system library. [⭐ 490](https://github.com/vittorioromeo/ecst) ⭐ 490 | 🐛 14 | 🌐 C++ | 📅 2019-09-03 · last commit 2018
* 💀 [ECS](https://github.com/redxdev/ECS) ⚠️ Archived - C++ single-header entity component system library. [⭐ 481](https://github.com/redxdev/ECS) ⚠️ Archived · last commit 2019
* 💀 [anax](https://github.com/miguelmartin75/anax) ⚠️ Archived - Open source C++ entity system. [⭐ 460](https://github.com/miguelmartin75/anax) ⚠️ Archived · last commit 2021
* [ECS Lua](https://github.com/nidorx/ecs-lua) ⭐ 234 | 🐛 9 | 🌐 Lua | 📅 2024-06-24 - A fast and easy to use ECS engine for game development. [⭐ 234](https://github.com/nidorx/ecs-lua) ⭐ 234 | 🐛 9 | 🌐 Lua | 📅 2024-06-24 · last commit 2021
* [EntityPlus](https://github.com/Yelnats321/EntityPlus) ⭐ 192 | 🐛 8 | 🌐 C++ | 📅 2020-08-22 - C++14 entity component system. [⭐ 192](https://github.com/Yelnats321/EntityPlus) ⭐ 192 | 🐛 8 | 🌐 C++ | 📅 2020-08-22 · last commit 2020
* [EntityFu](https://github.com/NatWeiss/EntityFu) ⭐ 86 | 🐛 0 | 🌐 C++ | 📅 2016-07-04 - A simple, fast entity component system written in C++. [⭐ 86](https://github.com/NatWeiss/EntityFu) ⭐ 86 | 🐛 0 | 🌐 C++ | 📅 2016-07-04 · last commit 2016
* [LeoEcsLite](https://github.com/LeoECSCommunity/ecslite) ⭐ 62 | 🐛 1 | 🌐 C# | 📅 2022-07-15 - Lightweight C# Entity Component System framework. [⭐ 62](https://github.com/LeoECSCommunity/ecslite) ⭐ 62 | 🐛 1 | 🌐 C# | 📅 2022-07-15 · last commit 2022
* [Ginseng](https://github.com/apples/ginseng) ⭐ 56 | 🐛 0 | 🌐 C++ | 📅 2021-12-21 - An ESC library designed for use in games. [⭐ 56](https://github.com/apples/ginseng) ⭐ 56 | 🐛 0 | 🌐 C++ | 📅 2021-12-21 · last commit 2021
* [Nata](https://github.com/tesselode/nata) ⭐ 51 | 🐛 1 | 🌐 Lua | 📅 2021-01-20 - Entity management for Lua. [⭐ 51](https://github.com/tesselode/nata) ⭐ 51 | 🐛 1 | 🌐 Lua | 📅 2021-01-20 · last commit 2020
* [ecs.hpp](https://github.com/BlackMATov/ecs.hpp) ⭐ 41 | 🐛 7 | 🌐 C++ | 📅 2023-01-07 - A single header C++14 entity component system library. [⭐ 41](https://github.com/BlackMATov/ecs.hpp) ⭐ 41 | 🐛 7 | 🌐 C++ | 📅 2023-01-07 · last commit 2023
* [beast](https://github.com/sjl/beast) ⭐ 30 | 🐛 0 | 🌐 Common Lisp | 📅 2021-08-29 - Basic Entity/Aspect/System Toolkit. [⭐ 30](https://github.com/sjl/beast) ⭐ 30 | 🐛 0 | 🌐 Common Lisp | 📅 2021-08-29 · last commit 2021
* [matter](https://github.com/frengels/matter) ⭐ 21 | 🐛 21 | 🌐 C++ | 📅 2019-10-03 - C++17/20 ECS implementation. [⭐ 21](https://github.com/frengels/matter) ⭐ 21 | 🐛 21 | 🌐 C++ | 📅 2019-10-03 · last commit 2019
* [Fast ECS](https://github.com/QiXi/fast_ecs) ⭐ 17 | 🐛 1 | 🌐 Dart | 📅 2021-12-11 - Simple and fast Entity-Component-System (ECS) library written in Dart. [⭐ 17](https://github.com/QiXi/fast_ecs) ⭐ 17 | 🐛 1 | 🌐 Dart | 📅 2021-12-11 · last commit 2021
* [goomy](https://github.com/vberlier/goomy) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2019-04-28 - A tiny, experimental ECS framework. [⭐ 14](https://github.com/vberlier/goomy) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2019-04-28 · last commit 2019
* [cl-ecs](https://github.com/bit-phlippers/cl-ecs) ⭐ 8 | 🐛 0 | 🌐 Common Lisp | 📅 2016-05-23 - An implementation of the Entity-Component-System pattern mostly used in game development. [⭐ 8](https://github.com/bit-phlippers/cl-ecs) ⭐ 8 | 🐛 0 | 🌐 Common Lisp | 📅 2016-05-23 · last commit 2016

</details>

## [Applications powered by ECS](#contents)

### [Game Engines](#contents)

*Game engines built on ECS architecture.*

#### C++

* 🟢 [WickedEngine](https://github.com/turanszkij/WickedEngine) ⭐ 7,289 | 🐛 114 | 🌐 C++ | 📅 2026-10-12 - 3D engine with modern graphics. [⭐ 7.3k](https://github.com/turanszkij/WickedEngine) ⭐ 7,289 | 🐛 114 | 🌐 C++ | 📅 2026-10-12
* 🟢 [halley](https://github.com/amzeratul/halley) ⭐ 3,866 | 🐛 47 | 🌐 C | 📅 2026-10-13 - A lightweight game engine written in modern C++. [⭐ 3.9k](https://github.com/amzeratul/halley) ⭐ 3,866 | 🐛 47 | 🌐 C | 📅 2026-10-13
* 🟢 [Lumos](https://github.com/jmorton06/Lumos) ⭐ 1,598 | 🐛 3 | 🌐 C++ | 📅 2026-08-31 - Cross-Platform C++ 2D/3D game engine. [⭐ 1.6k](https://github.com/jmorton06/Lumos) ⭐ 1,598 | 🐛 3 | 🌐 C++ | 📅 2026-08-31
* 🟡 [MxEngine](https://github.com/asc-community/MxEngine) ⭐ 1,231 | 🐛 18 | 🌐 C++ | 📅 2024-04-06 - C++ open source 3D game engine. [⭐ 1.2k](https://github.com/asc-community/MxEngine) ⭐ 1,231 | 🐛 18 | 🌐 C++ | 📅 2024-04-06
* 🟢 [nebula](https://github.com/gscept/nebula) ⭐ 1,101 | 🐛 35 | 🌐 C++ | 📅 2026-10-11 - Open-source and free-to-use modern C++ game engine. [⭐ 1.1k](https://github.com/gscept/nebula) ⭐ 1,101 | 🐛 35 | 🌐 C++ | 📅 2026-10-11
* 🟡 [Lina Engine](https://github.com/inanevin/LinaEngine) ⭐ 899 | 🐛 2 | 🌐 C++ | 📅 2025-10-08 - Modular, tiny and fast C++ game engine, aimed to develop 3D desktop games. [⭐ 899](https://github.com/inanevin/LinaEngine) ⭐ 899 | 🐛 2 | 🌐 C++ | 📅 2025-10-08
* 🟢 [supernova](https://github.com/supernovaengine/supernova) ⭐ 869 | 🐛 15 | 🌐 C++ | 📅 2026-10-13 - Game engine for 2D and 3D projects with ECS and data-oriented design. [⭐ 866](https://github.com/supernovaengine/supernova) ⭐ 869 | 🐛 15 | 🌐 C++ | 📅 2026-10-13
* 🟢 [Nazara Engine](https://github.com/NazaraEngine/NazaraEngine) ⭐ 843 | 🐛 15 | 🌐 C++ | 📅 2026-10-06 - Cross-platform framework aimed at real-time applications requiring audio, 2D and 3D real-time rendering, network and more. [⭐ 843](https://github.com/NazaraEngine/NazaraEngine) ⭐ 843 | 🐛 15 | 🌐 C++ | 📅 2026-10-06
* 🟢 [crown](https://github.com/dbartolini/crown) ⭐ 31 | 🐛 0 | 🌐 C++ | 📅 2026-10-13 - General purpose data-driven game engine. [⭐ 30](https://github.com/dbartolini/crown) ⭐ 31 | 🐛 0 | 🌐 C++ | 📅 2026-10-13

#### Go

* 🟡 [Engo](https://github.com/EngoEngine/engo) ⭐ 1,823 | 🐛 54 | 🌐 Go | 📅 2026-03-30 - A cross-platform game engine written in Go following an interpretation of the Entity Component System paradigm. [⭐ 1.8k](https://github.com/EngoEngine/engo) ⭐ 1,823 | 🐛 54 | 🌐 Go | 📅 2026-03-30

#### Rust

* 🟢 [Bevy](https://github.com/bevyengine/bevy) ⭐ 48,975 | 🐛 3,511 | 🌐 Rust | 📅 2026-10-13 - A refreshingly simple data-driven game engine built in Rust. [⭐ 48.9k](https://github.com/bevyengine/bevy) ⭐ 48,975 | 🐛 3,511 | 🌐 Rust | 📅 2026-10-13
* 🟡 [Ambient](https://github.com/AmbientRun/Ambient) ⭐ 3,906 | 🐛 281 | 🌐 Rust | 📅 2025-01-07 - The multiplayer game engine. [⭐ 3.9k](https://github.com/AmbientRun/Ambient) ⭐ 3,906 | 🐛 281 | 🌐 Rust | 📅 2025-01-07
* 🟢 [Bones](https://github.com/fishfolk/bones) ⭐ 314 | 🐛 69 | 🌐 Rust | 📅 2026-10-12 - An easy-to-use game engine for making real games. [⭐ 314](https://github.com/fishfolk/bones) ⭐ 314 | 🐛 69 | 🌐 Rust | 📅 2026-10-12

#### Zig

* 🟢 [mach](https://github.com/hexops/mach) ⭐ 4,849 | 🐛 167 | 🌐 Zig | 📅 2026-05-23 - Game engine & graphics toolkit for building high-performance, truly cross-platform, robust & modular games, visualizations, and desktop/mobile GUI apps. [⭐ 4.8k](https://github.com/hexops/mach) ⭐ 4,849 | 🐛 167 | 🌐 Zig | 📅 2026-05-23

<details>
<summary>Inactive (7): archived or no commits for 3+ years</summary>

* 💀 [Amethyst](https://github.com/amethyst/amethyst) ⚠️ Archived - Data-oriented and data-driven game engine written in Rust. [⭐ 8k](https://github.com/amethyst/amethyst) ⚠️ Archived · last commit 2021
* [Sparky](https://github.com/TheCherno/Sparky) ⭐ 1,193 | 🐛 50 | 🌐 C++ | 📅 2020-03-21 - Cross-Platform High Performance 2D/3D game engine. [⭐ 1.2k](https://github.com/TheCherno/Sparky) ⭐ 1,193 | 🐛 50 | 🌐 C++ | 📅 2020-03-21 · last commit 2016
* [kengine](https://github.com/phisko/kengine) ⭐ 618 | 🐛 1 | 🌐 C++ | 📅 2023-03-10 - Game engine focused on ease-of-use, runtime extensibility and compile-time type safety. [⭐ 618](https://github.com/phisko/kengine) ⭐ 618 | 🐛 1 | 🌐 C++ | 📅 2023-03-10 · last commit 2023
* [Engine](https://github.com/Shervanator/Engine) ⭐ 301 | 🐛 14 | 🌐 C++ | 📅 2018-08-04 - Basic cross-platform 3D game engine. [⭐ 301](https://github.com/Shervanator/Engine) ⭐ 301 | 🐛 14 | 🌐 C++ | 📅 2018-08-04 · last commit 2018
* 💀 [shiva](https://github.com/Milerius/shiva) ⚠️ Archived - Modern Cross-Platform C++ Engine with modularity. [⭐ 160](https://github.com/Milerius/shiva) ⚠️ Archived · last commit 2019
* [Usagi](https://github.com/vitei/Usagi) ⭐ 57 | 🐛 1 | 🌐 C++ | 📅 2026-09-26 - Hierarchical component entity system based game engine. [⭐ 57](https://github.com/vitei/Usagi) ⭐ 57 | 🐛 1 | 🌐 C++ | 📅 2026-09-26 · last commit 2022
* [igneous](https://github.com/MissingBitStudios/igneous) ⭐ 52 | 🐛 0 | 🌐 C++ | 📅 2020-10-03 - Open source game engine written in C++. [⭐ 52](https://github.com/MissingBitStudios/igneous) ⭐ 52 | 🐛 0 | 🌐 C++ | 📅 2020-10-03 · last commit 2019

</details>

### [Graphics Engines](#contents)

*Graphics and rendering engines using ECS.*

#### C++

* 🟢 [The Forge](https://github.com/ConfettiFX/The-Forge) ⭐ 5,685 | 🐛 15 | 🌐 C++ | 📅 2026-08-27 - Cross-Platform Rendering Framework with support for PC Windows, Linux, Ray Tracing, macOS/iOS, Android, XBOX, PS4, PS5, Switch, Quest 2. [⭐ 5.7k](https://github.com/ConfettiFX/The-Forge) ⭐ 5,685 | 🐛 15 | 🌐 C++ | 📅 2026-08-27
* 🟢 [bs::framework](https://github.com/GameFoundry/bsf) ⭐ 1,937 | 🐛 2 | 🌐 C++ | 📅 2026-10-13 - Modern C++14 library for the development of real-time graphical applications. [⭐ 1.9k](https://github.com/GameFoundry/bsf) ⭐ 1,937 | 🐛 2 | 🌐 C++ | 📅 2026-10-13

### [Physics Libraries](#contents)

*Physics simulation libraries organized as ECS.*

#### C++

* 🟢 [edyn](https://github.com/xissburg/edyn) ⭐ 793 | 🐛 4 | 🌐 C++ | 📅 2026-09-08 - A real-time physics engine organized as an ECS. [⭐ 792](https://github.com/xissburg/edyn) ⭐ 793 | 🐛 4 | 🌐 C++ | 📅 2026-09-08

## [Other Resources](#contents)

### [Benchmarks](#contents)

*Performance benchmarks comparing ECS frameworks.*

* 🟡 [ecs\_benchmark](https://github.com/abeimler/ecs_benchmark) ⭐ 308 | 🐛 2 | 🌐 C++ | 📅 2024-08-16 - Benchmarks of common ECS (Entity-Component-System)-Frameworks in C/C++. [⭐ 308](https://github.com/abeimler/ecs_benchmark) ⭐ 308 | 🐛 2 | 🌐 C++ | 📅 2024-08-16
* 🟢 [ECS C# Benchmark](https://github.com/Doraku/Ecs.CSharp.Benchmark) ⭐ 181 | 🐛 5 | 🌐 C# | 📅 2026-04-25 - Benchmarks of the main ECS Frameworks for: C#. [⭐ 181](https://github.com/Doraku/Ecs.CSharp.Benchmark) ⭐ 181 | 🐛 5 | 🌐 C# | 📅 2026-04-25
* [CSharpECSComparison](https://github.com/Chillu1/CSharpECSComparison) ⭐ 53 | 🐛 2 | 📅 2023-07-18 - Benchmarks of common ECS Frameworks for C#. [⭐ 53](https://github.com/Chillu1/CSharpECSComparison) ⭐ 53 | 🐛 2 | 📅 2023-07-18
* 🟢 [ECS C# Benchmark - Common uses-cases](https://github.com/friflo/ECS.CSharp.Benchmark-common-use-cases) ⭐ 48 | 🐛 1 | 🌐 C# | 📅 2026-02-02 - Benchmark many common use cases in the simplest and most performant variant. [⭐ 48](https://github.com/friflo/ECS.CSharp.Benchmark-common-use-cases) ⭐ 48 | 🐛 1 | 🌐 C# | 📅 2026-02-02
* 🟢 [Lua ECS Library Benchmark](https://github.com/jeffzi/lua-ecs-benchmark) ⭐ 9 | 🐛 2 | 🌐 Lua | 📅 2026-04-28 - Benchmarks of common ECS Frameworks in Lua. [⭐ 9](https://github.com/jeffzi/lua-ecs-benchmark) ⭐ 9 | 🐛 2 | 🌐 Lua | 📅 2026-04-28

### [Blog Posts](#contents)

*Articles and blog posts about ECS and data-oriented design.*

* [Data-oriented design](http://gamesfromwithin.com/category/data-oriented-design)
* [ECS back and forth](https://skypjack.github.io/2019-02-14-ecs-baf-part-1/)
* [Let's build an Entity Component System from scratch](https://devlog.hexops.com/2022/lets-build-ecs-part-1/)
* [Entity Systems are the future of MMOG development](https://t-machine.org/index.php/2007/09/03/entity-systems-are-the-future-of-mmog-development-part-1/)
* [Building an ECS](https://ajmmertens.medium.com/building-an-ecs-1-where-are-my-entities-and-components-63d07c7da742)
* [Systems Interaction in Entity-Component-System (events)](https://medium.com/@ben.rasooli/systems-interaction-in-entity-component-system-events-4a050153c8ac)
* [Overview of ECS variants & definitions](https://gist.github.com/LearnCocos2D/77f0ced228292676689f)
* [Understand data-oriented design](https://learn.unity.com/tutorial/part-1-understand-data-oriented-design)
* [Unity ECS series](https://gametorrahod.com/tag/unity-dots/)
* [Seba's Lab](https://www.sebaslab.com/)
* [WickedEngine's ECS implementation](https://web.archive.org/web/20240531144559/https://wickedengine.net/2019/09/entity-component-system/)

### [Talks & Slides](#contents)

*Conference talks and presentations about ECS.*

* [itCppCon19: ECS back and forth](https://youtu.be/WB5bRKKGRUk)
* [GDC 2018: Unity at GDC - A Data Oriented Approach to Using Component Systems](https://youtu.be/p65Yt20pw0g)
* [Meeting C++ 2018: Data oriented design in practice](https://youtu.be/NWMx1Q66c14)
* [CppCon 2018: Stoyan Nikolov “OOP Is Dead, Long Live Data-oriented Design”](https://youtu.be/yy8jQgmhbAU)
* [Data Oriented Design Resources](http://aras-p.info/texts/files/2018Academy%20-%20ECS-DoD.pdf)
* [Data Oriented GUI in Rust](https://www.youtube.com/watch?v=4YTfxresvS8)
* [Is There More to Game Architecture than ECS](https://www.youtube.com/watch?v=JxI3Eu5DPwE) - Bob Nystrom (Roguelike Celebration 2018)
* [Unite 2018: C# Job System + ECS usage and demo with Intel](https://www.youtube.com/watch?v=fp1D45hhVEM)
* [Codestar 2018 ECS - A Different Approach to Game Development](https://www.youtube.com/watch?v=lt4eL4RSx7k)
* [CppCon 2014: Mike Acton "Data-Oriented Design and C++"](https://youtu.be/rX0ItVEVjHc)

### [Books](#contents)

*Books on ECS and data-oriented design.*

* [Data-Oriented Design](http://www.dataorienteddesign.com/dodbook/)

### [Tutorials](#contents)

*Tutorial series for learning ECS.*

* [Starting a new 2D platformer with ECS](https://www.youtube.com/playlist?list=PLWtPciJ1UMuAoCq8NAw8J-n387U4QHFBW)

### [Lists](#contents)

*Related curated lists.*

* [Entity Component System & Data Oriented Design](https://github.com/dbartolini/data-oriented-design) ⭐ 4,492 | 🐛 4 | 📅 2026-09-17

### [References](#contents)

*Wikis, FAQs, glossaries, and other reference material on ECS.*

* [Entity Component Systems FAQ](https://github.com/SanderMertens/ecs-faq) ⭐ 2,764 | 🐛 2 | 📅 2026-07-01
* [Entity Systems Wiki](http://entity-systems.wikidot.com/)

## [Contributing](#contents)

Contributions are very welcome! Please read the [contribution guidelines](https://github.com/jslee02/awesome-entity-component-system/blob/main/CONTRIBUTING.md) first. Also, please feel free to report any error.

## [Star History](#contents)

<a href="https://www.star-history.com/?repos=jslee02%2Fawesome-entity-component-system">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=jslee02/awesome-entity-component-system&type=date&theme=dark&legend=top-left" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=jslee02/awesome-entity-component-system&type=date&legend=top-left" />
    <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=jslee02/awesome-entity-component-system&type=date&legend=top-left" />
  </picture>
</a>

## [License](#contents)

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-13._
