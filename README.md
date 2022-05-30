# Resume

Make sure to install pandoc and its dependencies:

```bash
brew install pandoc librsvg homebrew/cask/basictex
```

Then build the resume with:

```bash
./build
```

To have Github Actions build a new resume push a new tag.

```bash
git tag v4.2.0
git push origin v4.2.0
```
