# use

Things I am using

## IDE

- Editor: [VS Code](https://code.visualstudio.com) / [IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea), switching back and forth.
- Theme: [Solarized Dark](https://ethanschoonover.com/solarized/)
- Font: [JetBrains Mono](https://www.jetbrains.com/lp/mono/)

## Software

- Browser: [Chrome](https://www.google.com/intl/en_au/chrome/) (Windows/Linux), [Arc](https://arc.net/) (macOS)
- Virtualization: [Docker](https://www.docker.com/)
- Terminal: [iTerm2](https://iterm2.com/) (macOS) / GNOME Terminal (Linux)
- CI/CD: [GitHub Actions](https://github.com/features/actions)

## Tech Stack

- [TypeScript](https://www.typescriptlang.org/)
- [NodeJS](https://nodejs.org)
- [React](https://react.dev) + [Vite](https://vitejs.dev)
- [Prisma](https://prisma.io) + SQL (MySQL with [PlanetScale](https://planetscale.com)/ Postgres with [NeonDB](https://neon.tech))
- [Netlify](https://netlify.com) for static site hosting & serverless functions via [Netlify Functions](https://www.netlify.com/products/functions) for personal projects.
- [AWS Stack] for work projects.

## CLI

- [`brew`](https://brew.sh) - Homebrew for Mac. The essential.
- [`zsh`](https://zsh.org) - ZShell
  - config: [`dotfiles`](https://github.com/samhwang/dotfiles)
  - [`Oh My Zsh`](https://ohmyz.sh/) - ZSH Framework with a bunch of plugins
  - [`Starship`](https://starship.rs/) - Terminal prompt theme
  - [`bat`](https://github.com/sharkdp/bat) - Replacement for UNIX `bat`.
  - [`exa`](https://github.com/ogham/exa) - Replacement for `ls`
  - [`ripgrep`](https://github.com/BurntSushi/ripgrep) - Replacement for `grep`
  - [`fnm`](https://github.com/Schniz/fnm) - Faster `nvm` Node Version Manager
- [`pnpm`](https://pnpm.io) - Prefered package managers for Node projects.
  - If all else fails, go back to [`npm`](https://www.npmjs.com/).
- [`tsx`](https://github.com/esbuild-kit/tsx) - Run TypeScript files without compilation
- [`rome`](https://rome.tools) - Linter and Formatter
- [`vitest`](https://vitest.dev) - Test runner. Integrates nicely with `vite`.
  - Previously [`jest`](https://jestjs.io/).
- Build tools for libraries and projects:
  - [`vite`](https://vitejs.dev) - For Frontend Projects
  - [`tsup`](https://github.com/egoist/tsup) - For smaller libs
  - [`rollup`](https://rollupjs.org/) - For fine-grained controls
  - [`esbuild`](https://esbuild.github.io/) - Preferred JS/TS transpiler. Powers the above tools in a plugin

## Hardware

- [Home rig](https://pcpartpicker.com/user/samhwang/saved/#view=FpJcTW):
  - Windows / macOS Hackintosh mini ITX build
  - i9 9900KF
  - 32GB RAM
  - Radeon 5700XT
  - 4TB SSD
- Personal laptop: Macbook Pro 2016 - i5 + 16GB RAM + 256GB SSD
- Microphone: [Blue Yeti](https://www.logitechg.com/en-us/products/streaming-gear/yeti-premium-usb-microphone.html)
- Headphones: 
  - [DROP + EPOS PC38X](https://drop.com/buy/drop-epos-pc38x-gaming-headset)
  - Airpods Pro 2
- Camera:
  - For stills: Fuji X100T
  - Webcam: Logitech Streamcam
- Mice:
  - Logitech MX Master 3 - for on the go work
  - Logitech G Pro Wireless
  - Logitech G Pro X Superlight
  - Logitech G502 Lightspeed
- Keyboards:
  - RK84 Pro - All Clack switches for on the go work
  - CM Novatouch - BKE Redux Domes
  - GMMK Pro - NK Creams

## Starter Templates

- [`vite-starter-template`](https://github.com/samhwang/vite-starter-template) - Opinionated Vite + React + TS starter template
- [`fullstack-netlify-template`](https://github.com/samhwang/fullstack-netlify-template) - Basically the above template, with added backend powered by Netlify Functions via [`trpc-netlify-functions`](https://github.com/samhwang/trpc-netlify-functions)
- [`ts-starter-template`](https://github.com/samhwang/ts-starter-template) - Opiniated Node + TS starter template
