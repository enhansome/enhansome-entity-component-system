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
  * [ETC](#etc)

> **Legend**: 🟢 Active (<1yr) · 🟡 Slow (1-2yr) · 🔴 Stale (>2yr) · 💀 Archived

## [ECS Libraries](#contents)

*Libraries and frameworks implementing the Entity-Component-System pattern.*

#### C/C++

* 🟢 [entt](https://github.com/skypjack/entt) ⭐ 13,072 | 🐛 11 | 🌐 C++ | 📅 2026-08-31 - Fast and reliable entity-component system. [⭐ 12.8k](https://github.com/skypjack/entt) ⭐ 13,072 | 🐛 11 | 🌐 C++ | 📅 2026-08-31
* 🟢 [Flecs](https://github.com/SanderMertens/flecs) ⭐ 8,638 | 🐛 58 | 🌐 C | 📅 2026-08-26 - A Multithreaded Entity Component System written for C89 & C99. [⭐ 8.4k](https://github.com/SanderMertens/flecs) ⭐ 8,638 | 🐛 58 | 🌐 C | 📅 2026-08-26
* 🟢 [WickedEngine's ECS](https://github.com/turanszkij/WickedEngine/blob/master/WickedEngine/wiECS.h) ⭐ 7,215 | 🐛 114 | 🌐 C++ | 📅 2026-08-31 - WickedEngine's ECS implementation. [⭐ 7.1k](https://github.com/turanszkij/WickedEngine) ⭐ 7,215 | 🐛 114 | 🌐 C++ | 📅 2026-08-31
* 🟢 [EntityX](https://github.com/alecthomas/entityx) ⭐ 2,342 | 🐛 18 | 🌐 C++ | 📅 2025-08-23 - Fast, type-safe C++ entity component system. [⭐ 2.3k](https://github.com/alecthomas/entityx) ⭐ 2,342 | 🐛 18 | 🌐 C++ | 📅 2025-08-23
* 🔴 [Kengine](https://github.com/phisko/kengine) ⭐ 616 | 🐛 1 | 🌐 C++ | 📅 2023-03-10 - Game engine with an Entity-Component-System (ECS) architecture. [⭐ 617](https://github.com/phisko/kengine) ⭐ 616 | 🐛 1 | 🌐 C++ | 📅 2023-03-10
* 🟢 [pico\_ecs](https://github.com/empyreanx/pico_headers) ⭐ 555 | 🐛 4 | 🌐 C | 📅 2026-08-22 - Single-header and cross-platform ECS. [⭐ 547](https://github.com/empyreanx/pico_headers) ⭐ 555 | 🐛 4 | 🌐 C | 📅 2026-08-22
* 🔴 [ecst](https://github.com/vittorioromeo/ecst) ⭐ 491 | 🐛 14 | 🌐 C++ | 📅 2019-09-03 - Experimental C++14 multithreaded compile-time entity-compnent-system library. [⭐ 491](https://github.com/vittorioromeo/ecst) ⭐ 491 | 🐛 14 | 🌐 C++ | 📅 2019-09-03
* 💀 [ECS](https://github.com/redxdev/ECS) ⚠️ Archived - C++ single-header entity component system library. [⭐ 483](https://github.com/redxdev/ECS) ⚠️ Archived
* 💀 [anax](https://github.com/miguelmartin75/anax) ⚠️ Archived - Open source C++ entity system. [⭐ 463](https://github.com/miguelmartin75/anax) ⚠️ Archived
* 🔴 [EntityPlus](https://github.com/Yelnats321/EntityPlus) ⭐ 191 | 🐛 8 | 🌐 C++ | 📅 2020-08-22 - C++14 entity component system. [⭐ 191](https://github.com/Yelnats321/EntityPlus) ⭐ 191 | 🐛 8 | 🌐 C++ | 📅 2020-08-22
* 🟢 [Gaia-ECS](https://github.com/richardbiely/gaia-ecs) ⭐ 134 | 🐛 5 | 🌐 C++ | 📅 2026-08-31 - Fast and type-safe C++17 archetype-based entity component system. [⭐ 129](https://github.com/richardbiely/gaia-ecs) ⭐ 134 | 🐛 5 | 🌐 C++ | 📅 2026-08-31
* 🔴 [EntityFu](https://github.com/NatWeiss/EntityFu) ⭐ 86 | 🐛 0 | 🌐 C++ | 📅 2016-07-04 - A simple, fast entity component system written in C++. [⭐ 86](https://github.com/NatWeiss/EntityFu) ⭐ 86 | 🐛 0 | 🌐 C++ | 📅 2016-07-04
* 🟢 [mustache](https://github.com/kirillochnev/mustache) ⭐ 76 | 🐛 6 | 🌐 C++ | 📅 2026-01-20 - A fast, modern C++ entity component system. [⭐ 72](https://github.com/kirillochnev/mustache) ⭐ 76 | 🐛 6 | 🌐 C++ | 📅 2026-01-20
* 🔴 [Ginseng](https://github.com/apples/ginseng) ⭐ 56 | 🐛 0 | 🌐 C++ | 📅 2021-12-21 - An ESC library designed for use in games. [⭐ 56](https://github.com/apples/ginseng) ⭐ 56 | 🐛 0 | 🌐 C++ | 📅 2021-12-21
* 🔴 [ecs.hpp](https://github.com/BlackMATov/ecs.hpp) ⭐ 41 | 🐛 7 | 🌐 C++ | 📅 2023-01-07 - A single header C++14 entity component system library. [⭐ 41](https://github.com/BlackMATov/ecs.hpp) ⭐ 41 | 🐛 7 | 🌐 C++ | 📅 2023-01-07
* 🔴 [matter](https://github.com/frengels/matter) ⭐ 21 | 🐛 21 | 🌐 C++ | 📅 2019-10-03 - C++17/20 ECS implementation. [⭐ 21](https://github.com/frengels/matter) ⭐ 21 | 🐛 21 | 🌐 C++ | 📅 2019-10-03
* 🔴 [goomy](https://github.com/vberlier/goomy) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2019-04-28 - A tiny, experimental ECS framework. [⭐ 14](https://github.com/vberlier/goomy) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2019-04-28

#### C\#

* 🔴 [Entitas](https://github.com/sschmid/Entitas) ⭐ 7,672 | 🐛 97 | 🌐 C# | 📅 2023-12-30 - The Entity Component System Framework for C# and Unity. [⭐ 7.7k](https://github.com/sschmid/Entitas) ⭐ 7,672 | 🐛 97 | 🌐 C# | 📅 2023-12-30
* 🟢 [Arch](https://github.com/genaray/Arch) ⭐ 1,814 | 🐛 41 | 🌐 C# | 📅 2026-08-06 - A high-performance Archetype & Chunks Entity Component System for game development and data-oriented programming. [⭐ 1.7k](https://github.com/genaray/Arch) ⭐ 1,814 | 🐛 41 | 🌐 C# | 📅 2026-08-06
* 🟡 [Svelto.ECS](https://github.com/sebas77/Svelto.ECS) ⭐ 1,363 | 🐛 2 | 🌐 C# | 📅 2025-05-01 - Lightweight data oriented entity component system framework. [⭐ 1.4k](https://github.com/sebas77/Svelto.ECS) ⭐ 1,363 | 🐛 2 | 🌐 C# | 📅 2025-05-01
* 🟢 [Friflo Engine ECS](https://github.com/friflo/Friflo.Engine.ECS) ⭐ 762 | 🐛 40 | 🌐 C# | 📅 2026-07-03 - ECS for .NET with focus on performance, cache locality and DX. [⭐ 669](https://github.com/friflo/Friflo.Engine.ECS) ⭐ 762 | 🐛 40 | 🌐 C# | 📅 2026-07-03
* 🔴 [DefaultEcs](https://github.com/Doraku/DefaultEcs) ⭐ 760 | 🐛 21 | 🌐 C# | 📅 2024-03-01 - ECS for syntax and usage simplicity with maximum performance. [⭐ 758](https://github.com/Doraku/DefaultEcs) ⭐ 760 | 🐛 21 | 🌐 C# | 📅 2024-03-01
* 🟢 [Morpeh](https://github.com/scellecs/morpeh) ⭐ 662 | 🐛 8 | 🌐 C# | 📅 2026-08-14 - ECS Framework for Unity Game Engine and .NET Platform. [⭐ 647](https://github.com/scellecs/morpeh) ⭐ 662 | 🐛 8 | 🌐 C# | 📅 2026-08-14
* 🟢 [Fennecs](https://github.com/outfox/fennecs) ⭐ 463 | 🐛 8 | 🌐 C# | 📅 2026-08-06 - ... the tiny, tiny, high-energy Entity-Component System! [⭐ 441](https://github.com/outfox/fennecs) ⭐ 463 | 🐛 8 | 🌐 C# | 📅 2026-08-06
* 🟢 [DragonECS](https://github.com/DCFApixels/DragonECS) ⭐ 340 | 🐛 0 | 🌐 C# | 📅 2026-08-31 - ECS for Unity and .NET. [⭐ 332](https://github.com/DCFApixels/DragonECS) ⭐ 340 | 🐛 0 | 🌐 C# | 📅 2026-08-31
* 🟢 [ME.BECS](https://github.com/chromealex/ME.BECS) ⭐ 256 | 🐛 1 | 🌐 C# | 📅 2026-08-27 - ECS for Unity with full game state automatic rollbacks. [⭐ 249](https://github.com/chromealex/ME.BECS) ⭐ 256 | 🐛 1 | 🌐 C# | 📅 2026-08-27
* 🟢 [Massive ECS](https://github.com/nilpunch/massive-ecs) ⭐ 219 | 🐛 10 | 🌐 C# | 📅 2026-04-01 - Bitset-based ECS with rollbacks. C# library and Unity package. [⭐ 211](https://github.com/nilpunch/massive-ecs) ⭐ 219 | 🐛 10 | 🌐 C# | 📅 2026-04-01
* 🟢 [Static ECS](https://github.com/Felid-Force-Studios/StaticEcs) ⭐ 206 | 🐛 0 | 🌐 C# | 📅 2026-08-11 - C# Hierarchical Inverted Bitmap ECS framework. [⭐ 183](https://github.com/Felid-Force-Studios/StaticEcs) ⭐ 206 | 🐛 0 | 🌐 C# | 📅 2026-08-11
* 🟢 [Frent](https://github.com/itsBuggingMe/Frent) ⭐ 181 | 🐛 2 | 🌐 C# | 📅 2026-08-05 - Data oriented ECF with an ECS api for C#, Godot, and Unity. [⭐ 173](https://github.com/itsBuggingMe/Frent) ⭐ 181 | 🐛 2 | 🌐 C# | 📅 2026-08-05
* 🟢 [TinyEcs](https://github.com/andreakarasho/TinyEcs) ⭐ 153 | 🐛 6 | 🌐 C# | 📅 2026-08-13 - A tiny bevy-like archetype-style ECS library for dotnet. [⭐ 148](https://github.com/andreakarasho/TinyEcs) ⭐ 153 | 🐛 6 | 🌐 C# | 📅 2026-08-13
* 🔴 [LeoEcsLite](https://github.com/LeoECSCommunity/ecslite) ⭐ 63 | 🐛 1 | 🌐 C# | 📅 2022-07-15 - Lightweight C# Entity Component System framework. [⭐ 62](https://github.com/LeoECSCommunity/ecslite) ⭐ 63 | 🐛 1 | 🌐 C# | 📅 2022-07-15

#### Common Lisp

* 🔴 [beast](https://github.com/sjl/beast) ⭐ 30 | 🐛 0 | 🌐 Common Lisp | 📅 2021-08-29 - Basic Entity/Aspect/System Toolkit. [⭐ 30](https://github.com/sjl/beast) ⭐ 30 | 🐛 0 | 🌐 Common Lisp | 📅 2021-08-29
* 🔴 [cl-ecs](https://github.com/bit-phlippers/cl-ecs) ⭐ 8 | 🐛 0 | 🌐 Common Lisp | 📅 2016-05-23 - An implementation of the Entity-Component-System pattern mostly used in game development. [⭐ 8](https://github.com/bit-phlippers/cl-ecs) ⭐ 8 | 🐛 0 | 🌐 Common Lisp | 📅 2016-05-23
* [cl-fast-ecs](https://gitlab.com/lockie/cl-fast-ecs) - Blazingly fast Entity-Component-System microframework. [gitlab](https://gitlab.com/lockie/cl-fast-ecs)

#### Dart

* 🔴 [Fast ECS](https://github.com/QiXi/fast_ecs) ⭐ 17 | 🐛 1 | 🌐 Dart | 📅 2021-12-11 - Simple and fast Entity-Component-System (ECS) library written in Dart. [⭐ 17](https://github.com/QiXi/fast_ecs) ⭐ 17 | 🐛 1 | 🌐 Dart | 📅 2021-12-11

#### Elixir

* 🟡 [ECSx](https://github.com/ecsx-framework/ECSx) ⭐ 270 | 🐛 14 | 🌐 Elixir | 📅 2025-01-25 - An ECS framework for Elixir. [⭐ 265](https://github.com/ecsx-framework/ECSx) ⭐ 270 | 🐛 14 | 🌐 Elixir | 📅 2025-01-25

#### Python

* 🟢 [esper](https://github.com/benmoran56/esper) ⭐ 699 | 🐛 4 | 🌐 Python | 📅 2026-07-09 - A lightweight Entity System for Python. [⭐ 693](https://github.com/benmoran56/esper) ⭐ 699 | 🐛 4 | 🌐 Python | 📅 2026-07-09

#### Rust

* 🟢 [bevy\_ecs](https://github.com/bevyengine/bevy/tree/main/crates/bevy_ecs) ⭐ 47,999 | 🐛 3,439 | 🌐 Rust | 📅 2026-09-01 - Simple to use, ergonomic, fast, massively parallel, opinionated, and featureful written in Rust. [⭐ 46.8k](https://github.com/bevyengine/bevy) ⭐ 47,999 | 🐛 3,439 | 🌐 Rust | 📅 2026-09-01
* 🔴 [specs](https://github.com/amethyst/specs) ⭐ 2,614 | 🐛 48 | 🌐 Rust | 📅 2024-06-07 - Parallel entity component system written in Rust. [⭐ 2.6k](https://github.com/amethyst/specs) ⭐ 2,614 | 🐛 48 | 🌐 Rust | 📅 2024-06-07
* 🔴 [legion](https://github.com/amethyst/legion) ⭐ 1,719 | 🐛 96 | 🌐 Rust | 📅 2021-12-30 - High performance Rust ECS library. [⭐ 1.7k](https://github.com/amethyst/legion) ⭐ 1,719 | 🐛 96 | 🌐 Rust | 📅 2021-12-30
* 🟢 [hecs](https://github.com/Ralith/hecs) ⭐ 1,364 | 🐛 33 | 🌐 Rust | 📅 2026-09-01 - High-performance, minimalist entity-component-system. [⭐ 1.3k](https://github.com/Ralith/hecs) ⭐ 1,364 | 🐛 33 | 🌐 Rust | 📅 2026-09-01
* 🟢 [shipyard](https://github.com/leudz/shipyard) ⭐ 878 | 🐛 7 | 🌐 Rust | 📅 2026-09-01 - Entity Component System written in Rust. [⭐ 864](https://github.com/leudz/shipyard) ⭐ 878 | 🐛 7 | 🌐 Rust | 📅 2026-09-01

#### Go

* 🔴 [ecs](https://github.com/EngoEngine/ecs) ⭐ 336 | 🐛 6 | 🌐 Go | 📅 2023-12-21 - A Go-implementation of the Entity-Component-System paradigm. [⭐ 333](https://github.com/EngoEngine/ecs) ⭐ 336 | 🐛 6 | 🌐 Go | 📅 2023-12-21
* 🟢 [Ark](https://github.com/mlange-42/ark) ⭐ 298 | 🐛 7 | 🌐 Go | 📅 2026-08-17 - An archetype-based Entity Component System for Go. [⭐ 281](https://github.com/mlange-42/ark) ⭐ 298 | 🐛 7 | 🌐 Go | 📅 2026-08-17

#### Lua

* 🔴 [tiny-ecs](https://github.com/bakpakin/tiny-ecs) ⭐ 787 | 🐛 0 | 🌐 Lua | 📅 2023-03-15 - Entity Component System for Lua that's simple, flexible, and useful. [⭐ 783](https://github.com/bakpakin/tiny-ecs) ⭐ 787 | 🐛 0 | 🌐 Lua | 📅 2023-03-15
* 🟡 [Concord](https://github.com/Keyslam-Group/Concord) ⭐ 325 | 🐛 10 | 🌐 Lua | 📅 2026-07-24 - A feature-complete ECS library. [⭐ 317](https://github.com/Keyslam-Group/Concord) ⭐ 325 | 🐛 10 | 🌐 Lua | 📅 2026-07-24
* 🔴 [ECS Lua](https://github.com/nidorx/ecs-lua) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2024-06-24 - A fast and easy to use ECS engine for game development. [⭐ 231](https://github.com/nidorx/ecs-lua) ⭐ 232 | 🐛 9 | 🌐 Lua | 📅 2024-06-24
* 🟢 [evolved.lua](https://github.com/BlackMATov/evolved.lua) ⭐ 219 | 🐛 1 | 🌐 Lua | 📅 2026-08-18 - Evolved ECS (Entity-Component-System) for Lua. [⭐ 214](https://github.com/BlackMATov/evolved.lua) ⭐ 219 | 🐛 1 | 🌐 Lua | 📅 2026-08-18
* 🔴 [Nata](https://github.com/tesselode/nata) ⭐ 51 | 🐛 1 | 🌐 Lua | 📅 2021-01-20 - Entity management for Lua. [⭐ 51](https://github.com/tesselode/nata) ⭐ 51 | 🐛 1 | 🌐 Lua | 📅 2021-01-20

#### Java

* 🔴 [Artemis-odb](https://github.com/junkdog/artemis-odb) ⭐ 831 | 🐛 41 | 🌐 Java | 📅 2023-04-14 - A continuation of the popular Artemis ECS framework. [⭐ 832](https://github.com/junkdog/artemis-odb) ⭐ 831 | 🐛 41 | 🌐 Java | 📅 2023-04-14

#### Julia

* 🟢 [Ark.jl](https://github.com/ark-ecs/Ark.jl) ⭐ 83 | 🐛 42 | 🌐 Julia | 📅 2026-08-27 - An archetype-based Entity Component System (ECS) for Julia. It is a port of the Go ECS Ark. [⭐ 81](https://github.com/ark-ecs/Ark.jl) ⭐ 83 | 🐛 42 | 🌐 Julia | 📅 2026-08-27

#### Kotlin

* 🟢 [Fleks](https://github.com/Quillraven/Fleks) ⭐ 266 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-29 - Fast, lightweight, multi-platform entity component system in Kotlin. [⭐ 260](https://github.com/Quillraven/Fleks) ⭐ 266 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-29

#### JavaScript / TypeScript

* 🟢 [bitECS](https://github.com/NateTheGreatt/bitECS) ⭐ 1,495 | 🐛 22 | 🌐 TypeScript | 📅 2026-08-24 - Functional, minimal, data-oriented, ultra-high performance ECS library. [⭐ 1.4k](https://github.com/NateTheGreatt/bitECS) ⭐ 1,495 | 🐛 22 | 🌐 TypeScript | 📅 2026-08-24
* 💀 [ECSY](https://github.com/ecsyjs/ecsy) ⚠️ Archived - Entity Component System for javascript. [⭐ 1.2k](https://github.com/ecsyjs/ecsy) ⚠️ Archived
* 🟢 [miniplex](https://github.com/hmans/miniplex) ⭐ 1,047 | 🐛 26 | 🌐 TypeScript | 📅 2026-04-05 - The gentle game entity manager, focused on ease of use and developer experience. [⭐ 1.0k](https://github.com/hmans/miniplex) ⭐ 1,047 | 🐛 26 | 🌐 TypeScript | 📅 2026-04-05
* 🟡 [becsy](https://github.com/LastOliveGames/becsy) ⭐ 298 | 🐛 5 | 🌐 TypeScript | 📅 2025-10-02 - A multithreaded Entity Component System (ECS) for TypeScript and JavaScript, inspired by ECSY and bitecs. [⭐ 295](https://github.com/LastOliveGames/becsy) ⭐ 298 | 🐛 5 | 🌐 TypeScript | 📅 2025-10-02
* 🔴 [Thyseus](https://github.com/JaimeGensler/thyseus) ⭐ 86 | 🐛 16 | 🌐 TypeScript | 📅 2024-05-06 - An archetypal Entity Component System, built entirely in Typescript. [⭐ 86](https://github.com/JaimeGensler/thyseus) ⭐ 86 | 🐛 16 | 🌐 TypeScript | 📅 2024-05-06
* 🟢 [Woven-ECS](https://woven-ecs.dev/) - A multithreaded ECS framework for TypeScript aimed at collaborative browser applications. [⭐ 9](https://github.com/WillH0lt/woven-ecs) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21

#### Zig

* 🟢 [Zig ECS](https://github.com/prime31/zig-ecs) ⭐ 432 | 🐛 7 | 🌐 Zig | 📅 2026-05-18 - A Zig port of the fantasic Entt. [⭐ 419](https://github.com/prime31/zig-ecs) ⭐ 432 | 🐛 7 | 🌐 Zig | 📅 2026-05-18
* 🟢 [ZCS](https://github.com/Games-by-Mason/ZCS) ⭐ 150 | 🐛 20 | 🌐 Zig | 📅 2025-12-16 - An archetype based entity component system written in Zig. [⭐ 149](https://github.com/Games-by-Mason/ZCS) ⭐ 150 | 🐛 20 | 🌐 Zig | 📅 2025-12-16
* 🟢 [knoedel](https://github.com/Lommix/knoedel) ⭐ 45 | 🐛 1 | 🌐 Zig | 📅 2026-06-26 - Data oriented application framework written in Zig (ECS). [⭐ 35](https://github.com/Lommix/knoedel) ⭐ 45 | 🐛 1 | 🌐 Zig | 📅 2026-06-26
* 🔴 [mach-ecs](https://github.com/hexops-graveyard/mach-ecs) ⭐ 34 | 🐛 0 | 📅 2024-04-21 - Entity Component System from first-principles designed for Zig. [⭐ 35](https://github.com/hexops-graveyard/mach-ecs) ⭐ 34 | 🐛 0 | 📅 2024-04-21
* 🟢 [Comptime ECS](https://github.com/Very-Blank/Ecs) ⭐ 4 | 🐛 1 | 🌐 Zig | 📅 2026-07-20 - Comptime-defined ECS implementation in Zig. [⭐ 4](https://github.com/Very-Blank/Ecs) ⭐ 4 | 🐛 1 | 🌐 Zig | 📅 2026-07-20

#### Haskell

* 🟢 [apecs](https://github.com/jonascarpay/apecs) ⭐ 422 | 🐛 19 | 🌐 Haskell | 📅 2026-08-23 - A fast, extensible, type driven Haskell ECS framework for games. [⭐ 418](https://github.com/jonascarpay/apecs) ⭐ 422 | 🐛 19 | 🌐 Haskell | 📅 2026-08-23

## [Applications powered by ECS](#contents)

### [Game Engines](#contents)

*Game engines built on ECS architecture.*

#### C++

* 🟢 [WickedEngine](https://github.com/turanszkij/WickedEngine) ⭐ 7,215 | 🐛 114 | 🌐 C++ | 📅 2026-08-31 - 3D engine with modern graphics. [⭐ 7.1k](https://github.com/turanszkij/WickedEngine) ⭐ 7,215 | 🐛 114 | 🌐 C++ | 📅 2026-08-31
* 🟢 [halley](https://github.com/amzeratul/halley) ⭐ 3,856 | 🐛 47 | 🌐 C | 📅 2026-09-01 - A lightweight game engine written in modern C++. [⭐ 3.8k](https://github.com/amzeratul/halley) ⭐ 3,856 | 🐛 47 | 🌐 C | 📅 2026-09-01
* 🟢 [Lumos](https://github.com/jmorton06/Lumos) ⭐ 1,596 | 🐛 3 | 🌐 C++ | 📅 2026-08-31 - Cross-Platform C++ 2D/3D game engine. [⭐ 1.6k](https://github.com/jmorton06/Lumos) ⭐ 1,596 | 🐛 3 | 🌐 C++ | 📅 2026-08-31
* 🔴 [MxEngine](https://github.com/asc-community/MxEngine) ⭐ 1,233 | 🐛 18 | 🌐 C++ | 📅 2024-04-06 - C++ open source 3D game engine. [⭐ 1.2k](https://github.com/asc-community/MxEngine) ⭐ 1,233 | 🐛 18 | 🌐 C++ | 📅 2024-04-06
* 🔴 [Sparky](https://github.com/TheCherno/Sparky) ⭐ 1,191 | 🐛 50 | 🌐 C++ | 📅 2020-03-21 - Cross-Platform High Performance 2D/3D game engine. [⭐ 1.2k](https://github.com/TheCherno/Sparky) ⭐ 1,191 | 🐛 50 | 🌐 C++ | 📅 2020-03-21
* 🟢 [nebula](https://github.com/gscept/nebula) ⭐ 1,094 | 🐛 34 | 🌐 C++ | 📅 2026-09-01 - Open-source and free-to-use modern C++ game engine. [⭐ 1.1k](https://github.com/gscept/nebula) ⭐ 1,094 | 🐛 34 | 🌐 C++ | 📅 2026-09-01
* 🟢 [Lina Engine](https://github.com/inanevin/LinaEngine) ⭐ 902 | 🐛 2 | 🌐 C++ | 📅 2025-10-08 - Modular, tiny and fast C++ game engine, aimed to develop 3D desktop games. [⭐ 898](https://github.com/inanevin/LinaEngine) ⭐ 902 | 🐛 2 | 🌐 C++ | 📅 2025-10-08
* 🟢 [Nazara Engine](https://github.com/NazaraEngine/NazaraEngine) ⭐ 837 | 🐛 15 | 🌐 C++ | 📅 2026-09-01 - Cross-platform framework aimed at real-time applications requiring audio, 2D and 3D real-time rendering, network and more. [⭐ 831](https://github.com/NazaraEngine/NazaraEngine) ⭐ 837 | 🐛 15 | 🌐 C++ | 📅 2026-09-01
* 🟢 [supernova](https://github.com/supernovaengine/supernova) ⭐ 775 | 🐛 20 | 🌐 C++ | 📅 2026-09-01 - Game engine for 2D and 3D projects with ECS and data-oriented design. [⭐ 420](https://github.com/supernovaengine/supernova) ⭐ 775 | 🐛 20 | 🌐 C++ | 📅 2026-09-01
* 🔴 [kengine](https://github.com/phisko/kengine) ⭐ 616 | 🐛 1 | 🌐 C++ | 📅 2023-03-10 - Game engine focused on ease-of-use, runtime extensibility and compile-time type safety. [⭐ 617](https://github.com/phisko/kengine) ⭐ 616 | 🐛 1 | 🌐 C++ | 📅 2023-03-10
* 🔴 [Engine](https://github.com/Shervanator/Engine) ⭐ 301 | 🐛 14 | 🌐 C++ | 📅 2018-08-04 - Basic cross-platform 3D game engine. [⭐ 299](https://github.com/Shervanator/Engine) ⭐ 301 | 🐛 14 | 🌐 C++ | 📅 2018-08-04
* 💀 [shiva](https://github.com/Milerius/shiva) ⚠️ Archived - Modern Cross-Platform C++ Engine with modularity. [⭐ 158](https://github.com/Milerius/shiva) ⚠️ Archived
* 🔴 [Usagi](https://github.com/vitei/Usagi) ⭐ 57 | 🐛 1 | 🌐 C++ | 📅 2026-06-07 - Hierarchical component entity system based game engine. [⭐ 56](https://github.com/vitei/Usagi) ⭐ 57 | 🐛 1 | 🌐 C++ | 📅 2026-06-07
* 🔴 [igneous](https://github.com/MissingBitStudios/igneous) ⭐ 52 | 🐛 0 | 🌐 C++ | 📅 2020-10-03 - Open source game engine written in C++. [⭐ 52](https://github.com/MissingBitStudios/igneous) ⭐ 52 | 🐛 0 | 🌐 C++ | 📅 2020-10-03
* 🟢 [crown](https://github.com/dbartolini/crown) ⭐ 30 | 🐛 0 | 🌐 C++ | 📅 2026-09-01 - General purpose data-driven game engine. [⭐ 28](https://github.com/dbartolini/crown) ⭐ 30 | 🐛 0 | 🌐 C++ | 📅 2026-09-01

#### Go

* 🟡 [Engo](https://github.com/EngoEngine/engo) ⭐ 1,820 | 🐛 54 | 🌐 Go | 📅 2026-03-30 - A cross-platform game engine written in Go following an interpretation of the Entity Component System paradigm. [⭐ 1.8k](https://github.com/EngoEngine/engo) ⭐ 1,820 | 🐛 54 | 🌐 Go | 📅 2026-03-30

#### Rust

* 🟢 [Bevy](https://github.com/bevyengine/bevy) ⭐ 47,999 | 🐛 3,439 | 🌐 Rust | 📅 2026-09-01 - A refreshingly simple data-driven game engine built in Rust. [⭐ 46.8k](https://github.com/bevyengine/bevy) ⭐ 47,999 | 🐛 3,439 | 🌐 Rust | 📅 2026-09-01
* 💀 [Amethyst](https://github.com/amethyst/amethyst) ⚠️ Archived - Data-oriented and data-driven game engine written in Rust. [⭐ 8.0k](https://github.com/amethyst/amethyst) ⚠️ Archived
* 🟡 [Ambient](https://github.com/AmbientRun/Ambient) ⭐ 3,908 | 🐛 281 | 🌐 Rust | 📅 2025-01-07 - The multiplayer game engine. [⭐ 3.9k](https://github.com/AmbientRun/Ambient) ⭐ 3,908 | 🐛 281 | 🌐 Rust | 📅 2025-01-07
* 🟢 [Bones](https://github.com/fishfolk/bones) ⭐ 309 | 🐛 65 | 🌐 Rust | 📅 2026-04-24 - An easy-to-use game engine for making real games. [⭐ 299](https://github.com/fishfolk/bones) ⭐ 309 | 🐛 65 | 🌐 Rust | 📅 2026-04-24

#### Zig

* 🟢 [mach](https://github.com/hexops/mach) ⭐ 4,833 | 🐛 167 | 🌐 Zig | 📅 2026-05-23 - Game engine & graphics toolkit for building high-performance, truly cross-platform, robust & modular games, visualizations, and desktop/mobile GUI apps. [⭐ 4.8k](https://github.com/hexops/mach) ⭐ 4,833 | 🐛 167 | 🌐 Zig | 📅 2026-05-23

### [Graphics Engines](#contents)

*Graphics and rendering engines using ECS.*

#### C++

* 🟢 [The Forge](https://github.com/ConfettiFX/The-Forge) ⭐ 5,646 | 🐛 14 | 🌐 C++ | 📅 2026-08-27 - Cross-Platform Rendering Framework with support for PC Windows, Linux, Ray Tracing, macOS/iOS, Android, XBOX, PS4, PS5, Switch, Quest 2. [⭐ 5.6k](https://github.com/ConfettiFX/The-Forge) ⭐ 5,646 | 🐛 14 | 🌐 C++ | 📅 2026-08-27
* 🟢 [bs::framework](https://github.com/GameFoundry/bsf) ⭐ 1,922 | 🐛 2 | 🌐 C++ | 📅 2026-08-29 - Modern C++14 library for the development of real-time graphical applications. [⭐ 1.9k](https://github.com/GameFoundry/bsf) ⭐ 1,922 | 🐛 2 | 🌐 C++ | 📅 2026-08-29

### [Physics Libraries](#contents)

*Physics simulation libraries organized as ECS.*

#### C++

* 🟢 [edyn](https://github.com/xissburg/edyn) ⭐ 786 | 🐛 4 | 🌐 C++ | 📅 2026-06-05 - A real-time physics engine organized as an ECS. [⭐ 779](https://github.com/xissburg/edyn) ⭐ 786 | 🐛 4 | 🌐 C++ | 📅 2026-06-05

## [Other Resources](#contents)

### [Benchmarks](#contents)

*Performance benchmarks comparing ECS frameworks.*

* 🟡 [ecs\_benchmark](https://github.com/abeimler/ecs_benchmark) ⭐ 307 | 🐛 2 | 🌐 C++ | 📅 2024-08-16 - Benchmarks of common ECS (Entity-Component-System)-Frameworks in C/C++. [⭐ 299](https://github.com/abeimler/ecs_benchmark) ⭐ 307 | 🐛 2 | 🌐 C++ | 📅 2024-08-16
* 🟢 [ECS C# Benchmark](https://github.com/Doraku/Ecs.CSharp.Benchmark) ⭐ 179 | 🐛 5 | 🌐 C# | 📅 2026-04-25 - Benchmarks of the main ECS Frameworks for: C#. [⭐ 178](https://github.com/Doraku/Ecs.CSharp.Benchmark) ⭐ 179 | 🐛 5 | 🌐 C# | 📅 2026-04-25
* 🔴 [CSharpECSComparison](https://github.com/Chillu1/CSharpECSComparison) ⭐ 53 | 🐛 2 | 📅 2023-07-18 - Benchmarks of common ECS Frameworks for C#. [⭐ 53](https://github.com/Chillu1/CSharpECSComparison) ⭐ 53 | 🐛 2 | 📅 2023-07-18
* 🟢 [ECS C# Benchmark - Common uses-cases](https://github.com/friflo/ECS.CSharp.Benchmark-common-use-cases) ⭐ 47 | 🐛 1 | 🌐 C# | 📅 2026-02-02 - Benchmark many common use cases in the simplest and most performant variant. [⭐ 48](https://github.com/friflo/ECS.CSharp.Benchmark-common-use-cases) ⭐ 47 | 🐛 1 | 🌐 C# | 📅 2026-02-02
* 🟢 [Lua ECS Library Benchmark](https://github.com/jeffzi/lua-ecs-benchmark) ⭐ 9 | 🐛 2 | 🌐 Lua | 📅 2026-04-28 - Benchmarks of common ECS Frameworks in Lua. [⭐ 9](https://github.com/jeffzi/lua-ecs-benchmark) ⭐ 9 | 🐛 2 | 🌐 Lua | 📅 2026-04-28

### [Blog Posts](#contents)

*Articles and blog posts about ECS and data-oriented design.*

* [Building an ECS](https://ajmmertens.medium.com/building-an-ecs-1-where-are-my-entities-and-components-63d07c7da742)
* [Data-oriented design](http://gamesfromwithin.com/category/data-oriented-design)
* [ECS back and forth](https://skypjack.github.io/2019-02-14-ecs-baf-part-1/)
* [Entity Systems are the future of MMOG development](https://t-machine.org/index.php/2007/09/03/entity-systems-are-the-future-of-mmog-development-part-1/)
* [Let's build an Entity Component System from scratch](https://devlog.hexops.com/2022/lets-build-ecs-part-1/)
* [Overview of ECS variants & definitions](https://gist.github.com/LearnCocos2D/77f0ced228292676689f)
* [Seba's Lab](https://www.sebaslab.com/)
* [Systems Interaction in Entity-Component-System (events)](https://medium.com/@ben.rasooli/systems-interaction-in-entity-component-system-events-4a050153c8ac)
* [Understand data-oriented design](https://learn.unity.com/tutorial/part-1-understand-data-oriented-design)
* [Unity ECS series](https://gametorrahod.com/tag/unity-dots/)
* [WickedEngine's ECS implementation](https://web.archive.org/web/20240531144559/https://wickedengine.net/2019/09/entity-component-system/)

### [Talks & Slides](#contents)

*Conference talks and presentations about ECS.*

* [Codestar 2018 ECS - A Different Approach to Game Development](https://www.youtube.com/watch?v=lt4eL4RSx7k)
* [CppCon 2014: Mike Acton "Data-Oriented Design and C++"](https://youtu.be/rX0ItVEVjHc)
* [CppCon 2018: Stoyan Nikolov “OOP Is Dead, Long Live Data-oriented Design”](https://youtu.be/yy8jQgmhbAU)
* [Data Oriented Design Resources](http://aras-p.info/texts/files/2018Academy%20-%20ECS-DoD.pdf)
* [Data Oriented GUI in Rust](https://www.youtube.com/watch?v=4YTfxresvS8)
* [GDC 2018: Unity at GDC - A Data Oriented Approach to Using Component Systems](https://youtu.be/p65Yt20pw0g)
* [Is There More to Game Architecture than ECS](https://www.youtube.com/watch?v=JxI3Eu5DPwE) - Bob Nystrom (Roguelike Celebration 2018)
* [itCppCon19: ECS back and forth](https://youtu.be/WB5bRKKGRUk)
* [Meeting C++ 2018: Data oriented design in practice](https://youtu.be/NWMx1Q66c14)
* [Unite 2018: C# Job System + ECS usage and demo with Intel](https://www.youtube.com/watch?v=fp1D45hhVEM)

### [Books](#contents)

*Books on ECS and data-oriented design.*

* [Data-Oriented Design](http://www.dataorienteddesign.com/dodbook/)

### [Tutorials](#contents)

*Tutorial series for learning ECS.*

* [Starting a new 2D platformer with ECS](https://www.youtube.com/playlist?list=PLWtPciJ1UMuAoCq8NAw8J-n387U4QHFBW)

### [Lists](#contents)

*Related curated lists.*

* [Entity Component System & Data Oriented Design](https://github.com/dbartolini/data-oriented-design) ⭐ 4,466 | 🐛 4 | 📅 2026-07-17

### [ETC](#contents)

*Other ECS-related resources.*

* [Entity Component Systems FAQ](https://github.com/SanderMertens/ecs-faq) ⭐ 2,744 | 🐛 2 | 📅 2026-07-01
* [Entity Systems Wiki](http://entity-systems.wikidot.com/)

## [Contributing](#contents)

Contributions are very welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. Also, please feel free to report any error.

## [Star History](#contents)

[![Star History Chart](https://api.star-history.com/svg?repos=jslee02/awesome-entity-component-system\&type=Date)](https://star-history.com/#jslee02/awesome-entity-component-system)

## [License](#contents)

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
