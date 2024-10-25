# Standard

> A resume standard theme powered by [Zola](https://getzola.org).
>> See a live preview [here](https://aa.resume.rs).

## Features

- [x] Clean and Clear 
- [x] Always Updated
- [ ] Linkedin Mirror

## Installation:

1. Preparation:

```bash
# Setup your standard resume in a clean directory.

mkdir tintin-resume & cd tintin-resume
zola init & git init & git add .
git submodule add https://github.com/resume-rs/themes-standard themes/standard
```

2. Configuration:

```toml
# Add the following to the top of your `config.toml`

theme = "standard"

```

3. Publish:

```bash
# Build and Deploy:
# --- Testing: copy the example content and test it.

cp -r themes/apollo/content/* content/
zola serve

# GitHub Pages: with custom domain.
```
