# 🚧 Irontree 🚧
Irontree is to be a shader runner inspired by [Shadertoy's](shadertoy.com/) intuitive automation of buffers and layouts.

## Project Status: 🚧
First prototype development, framework is still being created. No tests, no, there's nothing here, except "Hello GPU!"

## Running

    > #cargo build
    > cargo run

## Milestones
- Runtime
  - [ ] Shader loading
    - [ ] wasm / wasi
    - [x] local binaries
  - [ ] buffer and layout generation
  - [ ] pipeline generation and binding
- GUI interface 
  - [ ] [egui Node Graph](https://github.com/setzer22/egui_node_graph)
    - [ ] shader nodes
    - [ ] graph programs


  ----
This project is currently heavily copied from [learn-wgpu](https://sotrh.github.io/learn-wgpu/). This is expected to change. As it stands, this project is inheriting **MIT** licensing from [learn-wgpu](https://github.com/sotrh/learn-wgpu).
