# Cloudshaala.com


## Setup


### 1. Clone the repo

```bash
git clone git@github.com:shardulsrivastava/cloudshaala.github.io.git
```

### 2. Install Dependencies

```bash
pnpm install
```

### 3. Start development Server

```bash
pnpm dev
```

### Preview & Build

```bash
pnpm preview
pnpm build
```

We recommend using [pnpm](https://pnpm.io/) to save disk space on your computer.

### Other Commands

```bash
pnpm astro ...
pnpm astro add
pnpm astro --help
```

## Repo Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── ...
├── src/
│   ├── components/
│   │   └── ...
│   ├── layouts/
│   │   └── ...
│   └── pages/
│       └── ...
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

## TailwindCSS

TailwindCSS is already configured in this repo, so you can start using it without any installation.


## ShadCN UI Integration

[shacdn UI](https://ui.shadcn.com/) is integrated with the this project based on the instruction [here](https://ui.shadcn.com/docs/installation/astro).

> **_NOTE:_**  globals.css file has to be imported to all the pages, this seems to be a [bug](https://github.com/shadcn-ui/ui/issues/4531).

