# SchematikZ

A server-side building-overlay plugin for Minecraft, written in Kotlin. *No client mod needed* 🤯

<img width="65%" alt="SchematikZ in-game overlay" src="https://github.com/user-attachments/assets/c38b3e5b-4783-4864-9cf8-34dea4cdcdb2" />
<img width="30%" alt="SchematikZ logo" src="https://github.com/user-attachments/assets/8f72af1b-c5ad-45f0-b9c0-95af615a9829" />

> - Developed with client and server performance in mind. SchematikZ uses ghost blocks, display entities, and packets to provide the overlay.
> - Similar in spirit to Litematica, but designed to run server-side.
> - Built for *survival building* (for example, complex farms), *team projects*, and servers that want precise building guidance with as little friction as possible.

## For players ⌨️

- Build with confidence: See exactly what goes where without guessing orientations or missing details, including when building as a team.
- Survival-friendly workflows: Optional modes such as “easy place” help you place blocks correctly while still requiring the right materials.
- Cleaner building sessions: The overlay provides visual guidance without permanently modifying the world to display the schematic.
- Accurate block handling: Rotation, block-face attachments, and other tricky vanilla block behaviors are a priority.

## For server owners 🖥️

- Performance-focused rendering: Packet-based techniques keep large schematics practical.
- Highly configurable behavior: Choose what fits your server style, scale, and resources. By default, it works as if only the client had a mod.
- Multiplayer-ready approach: Designed with visibility management and per-viewer handling in mind.

## Status 🫀

This project is under active development, with a focus on stability, maintainability, and performance. SchematikZ is intended to provide a server-side, Litematica-style experience on Paper.

Stay tuned ❤️  
https://discord.gg/dVWHmAWrxn

## SchematiCraft

I am in direct contact with the developer of [SchematiCraft](https://schematicraft.com), a community-focused schematic library. Integration with SchematikZ is planned.

## Roadmap

- Large-schematic optimizations, including diff-based updates, distance-based batching, spatial partitioning, and safeguards for teleports and world changes
- Overlay quality-of-life features such as layer rendering, rotation and mirroring, per-player settings, completion visuals, and geometric shape or text generation
- Ghost-block and packet strategies to reduce client load on large builds
- Support for common schematic formats such as `.litematic`, `.schem`, `.schematic`, and `.nbt`
- Integration points for selection tools and schematic libraries
- Folia support
- Asynchronous processing for resource-intensive work
- Persistence across sessions
- Experiments with richer automation, core shaders, custom model component resource packs, and version control for builder teams
