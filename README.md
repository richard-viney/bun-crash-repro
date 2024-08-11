To reproduce the crash run `bun run main.mjs`.

Output is `Illegal instruction: 4` / `illegal hardware instruction`, with an exit code of 132.

#### Versions Affected

- Bun 1.1.22
- Local debug build of latest main [`7d018fb`](https://github.com/oven-sh/bun/commit/7d018fb323ec13118368df8e9773d7604efec65a)

#### Platform Details

- MacBook Pro M2
- macOS Sonoma 14.5
- uname: Darwin 23.5.0 Darwin Kernel Version 23.5.0: Wed May  1 20:14:38 PDT 2024; root:xnu-10063.121.3~5/RELEASE_ARM64_T6020 arm64
