# `rp` environment manager

# Installation

Clone it somewhere.

Add the `bin/` dir to your `PATH`, e.g.

```bash
git clone git@github.com:KyussCaesar/rp.git
cd rp
echo 'export PATH="$PATH:$(pwd)/bin"' >>~/.bashrc
```

# Usage

Go to the root of your project.

```bash
rp-new build
```

This will spit out a new environment definition, for a Debian-based environment.

---

```bash
rp build run bash
```

This will ensure the `build` environment is up-to-date, then drop you into a
shell in the build environment.

