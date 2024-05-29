# [BUG] - Anchors with target="_blank" inside of an iframe are not working
Tested in version: 2.0.0-beta.22 and 1.6.7

## Info for 2.0

[✔] Environment
    - OS: Mac OS 14.5.0 X64
    ✔ Xcode Command Line Tools: installed
    ✔ rustc: 1.77.2 (25ef9e3d8 2024-04-09)
    ✔ cargo: 1.77.2 (e52e36006 2024-03-26)
    ✔ rustup: 1.27.0 (bbb9276d2 2024-03-08)
    ✔ Rust toolchain: stable-aarch64-apple-darwin (default)
    - node: 20.12.0
    - pnpm: 9.1.3
    - yarn: 1.22.19
    - npm: 10.5.0
    - bun: 1.0.17

[-] Packages
    - tauri [RUST]: 2.0.0-beta.22
    - tauri-build [RUST]: 2.0.0-beta.17
    - wry [RUST]: 0.40.0
    - tao [RUST]: 0.28.0
    - @tauri-apps/api : not installed!
    - @tauri-apps/cli [NPM]: 2.0.0-beta.19

[-] App
    - build-type: bundle
    - CSP: unset
    - frontendDist: ../src

## Info for 1.6.7


[✔] Environment
    - OS: Mac OS 14.5.0 X64
    ✔ Xcode Command Line Tools: installed
    ✔ rustc: 1.77.2 (25ef9e3d8 2024-04-09)
    ✔ cargo: 1.77.2 (e52e36006 2024-03-26)
    ✔ rustup: 1.27.0 (bbb9276d2 2024-03-08)
    ✔ Rust toolchain: stable-aarch64-apple-darwin (default)
    - node: 20.12.0
    - pnpm: 9.1.3
    - yarn: 1.22.19
    - npm: 10.5.0
    - bun: 1.0.17

[-] Packages
    - tauri [RUST]: 1.6.7
    - tauri-build [RUST]: 1.5.2
    - wry [RUST]: 0.24.10
    - tao [RUST]: 0.16.9
    - @tauri-apps/api : not installed!
    - @tauri-apps/cli [NPM]: 1.5.14

[-] App
    - build-type: bundle
    - CSP: unset
    - distDir: ../src
    - devPath: ../src