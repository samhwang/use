# use

Things I am using

## IDE

- Editor: [VS Code](https://code.visualstudio.com) / [IntelliJ IDEA Ultimate](https://www.jetbrains.com/idea) / [Neovim](https://neovim.io), switching back and forth.
- Theme: [Catppuccin](https://github.com/catppuccin/catppuccin)
- Font: [JetBrains Mono](https://www.jetbrains.com/lp/mono)

## Software

- Browser: [Chrome](https://www.google.com/intl/en_au/chrome) (Windows/Linux), [Arc](https://arc.net) (macOS)
- Virtualization: [Docker](https://www.docker.com)
- Terminal: [Warp](https://warp.dev) (macOS) / GNOME Terminal (Linux)
- Password Management: [1password](https://1password.com)
- MFA: [Authy](https://authy.com) along with [Yubikey 5](https://www.yubico.com/products/yubikey-5-overview)
- Vietnamese Keyboard: [EVKey](https://github.com/lamquangminh/EVKey)

## Tech Stack

- [TypeScript](https://www.typescriptlang.org)
- [NodeJS](https://nodejs.org)
- [React](https://react.dev) + [Vite](https://vitejs.dev)
- [Prisma](https://prisma.io) + SQL (MySQL with [PlanetScale](https://planetscale.com)/ Postgres with [NeonDB](https://neon.tech))
- [Netlify](https://netlify.com) for static site hosting & serverless functions via [Netlify Functions](https://www.netlify.com/products/functions) for personal projects.
- [GitHub Actions](https://github.com/features/actions) for CI/CD.
- [AWS Stack](https://aws.amazon.com) for work projects, deployed and configured via [CDK](https://aws.amazon.com/cdk).

## CLI

- [`brew`](https://brew.sh) - Homebrew for Mac. The essential.
- [`zsh`](https://zsh.org) - ZShell
  - config: [`dotfiles`](https://github.com/samhwang/dotfiles)
  - [`Oh My Zsh`](https://ohmyz.sh) - ZSH Framework with a bunch of plugins
  - [`Starship`](https://starship.rs) - Terminal prompt theme
  - [`bat`](https://github.com/sharkdp/bat) - Replacement for UNIX `bat`.
  - [`exa`](https://github.com/ogham/exa) - Replacement for `ls`
  - [`ripgrep`](https://github.com/BurntSushi/ripgrep) - Replacement for `grep`
  - [`fnm`](https://github.com/Schniz/fnm) - Faster `nvm` Node Version Manager
- [`pnpm`](https://pnpm.io) - Prefered package managers for Node projects.
- [`tsx`](https://github.com/esbuild-kit/tsx) - Run TypeScript files without compilation
- [`biome`](https://biomejs.dev) - Linter and Formatter
- [`vitest`](https://vitest.dev) - Test runner. Integrates nicely with `vite`.
- Build tools for libraries and projects:
  - [`vite`](https://vitejs.dev) - For Frontend Projects
  - [`tsup`](https://github.com/egoist/tsup) - For smaller libs
  - [`rollup`](https://rollupjs.org) - For fine-grained controls
  - [`esbuild`](https://esbuild.github.io) - Preferred JS/TS transpiler. Powers the above tools.

## Hardware

- Yubikey 5
- [Home rig](https://pcpartpicker.com/user/samhwang/saved/#view=FpJcTW):
  - Windows / macOS Hackintosh mini ITX build
  - i9 9900KF
  - 32GB RAM
  - Radeon 5700XT
  - 4TB SSD
- Personal laptop: Macbook Pro 2016 - i5 + 16GB RAM + 256GB SSD
- Microphone: Blue Yeti
- Headphones/Earbuds/Speaker:
  - Airpods Pro 2
  - DROP+EPOS PC38X
  - AudioEngine A2+
- Camera:
  - For stills: Fuji X100T
  - Webcam: Logitech Streamcam
- Light: Logitech Litra Glow
- Desk Organizer: Orbitkey Nest
- Mice:
  - Logitech G Pro Wireless
  - Logitech G Pro X Superlight
  - Logitech G502 Lightspeed
  - Logitech MX Master 3
  - Logitech MX Ergo
- Keyboards:
  - CM Novatouch - BKE Redux Domes
  - GMMK Pro - NovelKeys x Kailh Creams
  - RK84 Pro - Keyboard Treehouse All Clack switches
- Chair: Herman Miller Embody
- Desk: UpDown Desk Pro series with custom wood desktop
- Monitor: XiaoMi Mi Curved Ultrawide Gaming Monitor 34"

## Starter Templates

- [`vite-starter-template`](https://github.com/samhwang/vite-starter-template) - Opinionated Vite + React + TS starter template
- [`fullstack-netlify-template`](https://github.com/samhwang/fullstack-netlify-template) - Basically the above template, with added type-safe backend powered by Netlify Functions and [tRPC](https://trpc.io) via [`trpc-netlify-functions`](https://github.com/samhwang/trpc-utils/tree/master/packages/trpc-netlify-functions)
- [`ts-starter-template`](https://github.com/samhwang/ts-starter-template) - Opinionated Node + TS starter template
