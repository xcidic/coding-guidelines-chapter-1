This Repo is development version of js coding guidelines for each Xcidic members to follows. Build version published in [Branch:gh-pages](https://github.com/xcidic/coding-guidelines-chapter-1/tree/gh-pages)

## Needs

- [Jekyll](https://jekyllrb.com/)
- [Ruby](https://www.ruby-lang.org/id/)

## Setup

1. Install Jekyll and Bundle

```bash
gem install bundler jekyll
```

2. Clone this project.

```bash
git clone https://github.com/xcidic/coding-guidelines-chapter-1.git
```

3. Enter Project folder

```bash
cd coding-guidelines-chapter-1
```

## Run

```bash
 # Run dev (Incremental)
 bundle exec jekyll serve -i

 # Run build
 bundle exec jekyll serve
```

## Release to github pages

1. checkout to [gh-pages](https://github.com/xcidic/coding-guidelines-chapter-1/tree/gh-pages) branch

   ```bash
    # first clone
    git fetch && git checkout gh-pages

    # or
    # you have gh-pages branch in local
    git checkout gh-pages
   ```

2. copy everything inside root folder
3. commit and push to [gh-pages](https://github.com/xcidic/coding-guidelines-chapter-1/tree/gh-pages) branch
