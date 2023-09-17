---
title: Roadmap
layout: home
nav_order: 5
---

# Roadmap

> Some of these features are totally unrealistic.
{: .warning}

A list of future features:

## Implementing a web UI
This probably never going to happen or in like ten years. This is extremely hard to do. One approach would be to use (or have it based on) something like [BlueMap]. I've already talked to the creator of [BlueMap]. It's just really hard to change some [BlueMap] source code without even knowing any [Vue].

## Add PlaceholderAPI placeholders
Recommended by [McFAQ], I will add PlaceholderAPI support. He hasn't replied to my message tho, so I'm not 100% certain if he means placeholders, but I don't know what other thing he would mean with "Add PlaceholderAPI support".

## Rewriting Dijkstra's algorithm
Rewriting Dijkstra's algorithm to give more insight + having more options (see [Multiple types of roads](#multiple-types-of-roads) and [Multi-dimensional navigation support](#multi-dimensional-navigation-support)). This could also improve performance (see [Improving perfomance with rust](#improving-performance-with-rust).

## Multiple types of roads
Be able to have navigation that could also go on water, or travel with a horse. See [Multi-dimensional navigation support](#multi-dimensional-navigation-support).

## Multi-dimensional navigation support
Go into the nether to go faster instead of going on land.

## Improving performance with Rust
Automatically download a Rust binary depending on the OS. If no OS-specific binary could be found, default back to Java.

---

## Finished features.

In order from finished first to finished last.

- Using Dijkstra's Algorithm - [1.0]
- Saving Roads to disk/config files - [1.0]
- Creating a UI - [1.5]

[BlueMap]: https://bluemap.bluecolored.de/
[Vue]: https://vuejs.org/
[McFAQ]: https://www.spigotmc.org/members/mcfaq.181238/
[1.0]: https://github.com/Abelkrijgtalles/mojang-maps/releases/tag/v1.0
[1.5]: https://github.com/Abelkrijgtalles/mojang-maps/releases/tag/v1.5