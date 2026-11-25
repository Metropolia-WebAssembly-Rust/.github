# WebAssembly with Rust

Welcome to the **WebAssembly with Rust** course at [Metropolia University of Applied Sciences](https://www.metropolia.fi/en), taught by **Jukka Paasonen**.

This course explores how [Rust](https://www.rust-lang.org/) and [WebAssembly](https://webassembly.org/) can be used to build efficient applications for modern web browsers, desktop environments, and cloud platforms. Through a combination of lectures, practical exercises, and programming assignments, you will gain hands-on experience with Rust and its growing ecosystem.

The course focuses on practical software engineering: understanding the technology, building working applications, integrating different components, and evaluating the quality and performance of your solutions.

## What you will learn

Throughout the course, we explore several areas of Rust and WebAssembly development:

- **WebAssembly fundamentals:** Understanding WebAssembly, its architecture, and how Rust code can be compiled into WASM modules.
- **Browser-based computing:** Using WebAssembly for computationally intensive tasks directly in the browser.
- **Graphics rendering:** Building interactive graphical applications and exploring rendering techniques.
- **Artificial intelligence:** Integrating machine learning and AI capabilities into WebAssembly applications.
- **Rust frontend development:** Building browser-based user interfaces with frameworks such as [Yew](https://yew.rs/) and [Leptos](https://www.leptos.dev/).
- **Cloud functions:** Exploring WASI and WebAssembly-based serverless computing.
- **Performance optimisation:** Understanding profiling, memory management, and techniques for improving application performance.
- **Desktop applications:** Integrating Rust, WebAssembly, and web technologies using frameworks such as [Tauri](https://tauri.app/).

## Course structure

The course consists of eight lecture topics, five smaller programming assignments, and one larger final project.

The assignments progressively introduce different aspects of Rust and WebAssembly development.

| Assignment                      | Topic                                                  | Main technologies             |
| ------------------------------- | ------------------------------------------------------ | ----------------------------- |
| 0. GitHub setup                 | Development environment and commit signing             | Git, GitHub, GPG              |
| 1. Foundation                   | Compiling Rust to WebAssembly                          | Rust, wasm-pack, wasm-bindgen |
| 2. Image Filtering              | Browser-based image processing                         | Rust, WebAssembly, Canvas     |
| 3. Face Age Detection           | Computer vision in the browser                         | YOLO11n, ONNX, tract, WASM    |
| 4. Tic Tac Toe in Yew           | Reimplementing a React application                     | Rust, Yew, WASM               |
| 5. Cloud Fibonacci              | WASI-based cloud function                              | Rust, WASI, Node.js, Wasmtime |
| Final project: Tauri HSL Router | Migrating a desktop application's UI from React to Yew | Rust, Yew, Tauri, WASM        |

The final project brings together many of the concepts covered throughout the course. You will work with an existing desktop transit planning application and migrate its React-based user interface to Yew while retaining the existing Rust backend.

## Working with the assignments

All programming assignments are distributed through Classroom 50 and hosted in this organisation.

Each assignment has its own repository containing the starter code, implementation requirements, documentation, and automated evaluation workflow.

The general development workflow is:

1. Accept the assignment through Classroom 50.
2. Clone your personal assignment repository.
3. Implement the required functionality.
4. Test and verify your solution locally.
5. Push your changes to GitHub.
6. Submit your work using the Classroom 50 CLI.
7. Review the automated evaluation results in your repository.

Most assignments use GitHub Actions for automated evaluation. Depending on the assignment, this includes compilation, formatting, linting, unit tests, browser tests, code coverage, and functional verification.

**Always test your implementation locally before submitting it.** Automated evaluation is intended to verify your work, not to replace your development and debugging process.

## Development tools and technologies

The course uses a modern Rust development environment and several supporting technologies.

Some of the technologies you will encounter include:

- [Rust](https://www.rust-lang.org/) – Systems programming language.
- [WebAssembly](https://webassembly.org/) – Portable binary instruction format.
- [Cargo](https://doc.rust-lang.org/cargo/) – Rust package manager and build system.
- [wasm-pack](https://wasm-bindgen.github.io/wasm-pack/) – Tooling for building Rust-generated WebAssembly packages.
- [wasm-bindgen](https://rustwasm.github.io/wasm-bindgen/) – Connecting Rust and JavaScript.
- [Yew](https://yew.rs/) and [Leptos](https://www.leptos.dev/) – Rust frontend frameworks.
- [Tauri](https://tauri.app/) – Framework for building desktop applications.
- [Wasmtime](https://wasmtime.dev/) – WebAssembly runtime.
- [Playwright](https://playwright.dev/) – Browser automation and end-to-end testing.
- [GitHub Actions](https://github.com/features/actions) – Continuous integration and automated evaluation.

You will also encounter technologies related to machine learning, computer vision, image processing, cloud computing, and application performance.

## Learning approach

The course emphasises practical learning and independent problem-solving.

You are encouraged to:

- Experiment with the examples and technologies introduced during lectures.
- Read documentation and explore the Rust ecosystem.
- Use compiler errors, tests, and automated checks as learning tools.
- Investigate different implementation approaches.
- Use AI-assisted development tools, such as GitHub Copilot, to understand unfamiliar concepts and code.
- Ask questions and share knowledge with other students.

You are not expected to know every technology before starting an assignment. The ability to investigate unfamiliar technologies and solve problems independently is an important learning outcome.

## Questions and support

Questions about assignment requirements, technical problems, and course topics should be raised in the organisation's Q&A repository.

**[Questions & Answers – GitHub Discussions](https://github.com/orgs/Metropolia-WebAssembly-Rust/discussions)**

Please search existing discussions before creating a new question. Keeping discussions public allows everyone to benefit from shared answers and clarifications.

For course administration and matters that are not suitable for public discussion, use the communication channels provided through Metropolia.

## Contact

Course teacher: Jukka Paasonen ([@paazmaya](https://github.com/paazmaya))
