# Motion control playground

This project is a virtual environment for testing different motion control algorithms. It uses the Bevy game engine and is written in Rust.

> :warning: This project is in alpha stage and there is still work in progress.

## Features
* Import 3D models from Blender
* Control the motion of the models using different controllers, such as PID, fuzzy, and adaptive control (or any other creative strategies)
* Visualize the results of the control algorithms

## Getting Started
1. Install Rust.
2. Run `cargo install wasm-server-runner`
3. Add this to your `~/.cargo/config.toml` (**not** the `Cargo.toml` of your project!):
    ```toml
    [target.wasm32-unknown-unknown]
    runner = "wasm-server-runner"
    ```
4. Clone this repository.
5. Run `cargo run --target wasm32-unknown-unknown` to start the project.

## Controls
* W - go forward
* A - go to the left
* D - go to the right
* S - go backward
* B - enable/disable frames for elements
* L - start/stop animation
* U - enable/disable shadows

## Documentation
The documentation for the project can be found in the docs directory.

## Contributing
Contributions to this project are welcome! Please open an issue or a pull request if you have any ideas or improvements.

## License
This project is licensed under the MIT License.