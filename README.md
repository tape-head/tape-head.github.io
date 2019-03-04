# So uh, welcome..

This repo is a special little place, where I work on a little blog. Most of the guts of this project is based on the Hydejack repo by qwtel (links below to that) with a few tweaks here and there for fun.

Please note a few things that make this all look coherent:
* For images, it's important to have three sizes (the largest being 1080p) to account for different device sizes (i.e. hydejack-8.jpg, hydejack-8@0,5x.jpg & hydejack-8@0,25x.jpg)
* Each 'blog post' has the tag 'blog' and the category (either 'music' or 'health' or whatever the topic may be) so that they are organised by category, but all accessible from the 'blog' menu

Below are the instructions for running the jekyll site locally or through GitHub pages.

## Hydejack Starter Kit

A quicker, cleaner way to get started blogging with [Hydejack](https://hydejack.com/).

### Quick Start
#### Running locally
1. Clone repository (git users), or [download] and unzip.
2. Open terminal, `cd` into root directory (where `_config.yml` is located)
3. `bundle install` [^1]
4. `bundle exec jekyll serve`
5. Open <http://localhost:4000/hy-starter-kit/>

#### GitHub Pages
1. Fork this repository.
2. Go to **Settings**, rename repository to `<your github username>.github.io` (without the `<` `>`)
3. Edit `_config.yml` (you can do this directly on GitHub)
    1. Change `url` to `https://<your github username>.github.io` (without the `<` `>`)
    2. Change `baseurl` to `''` (empty string)
    3. **Commit changes**.
4. Go to **Settings** again, look for **GitHub Pages**, set **Source** to **master branch**.
5. Click **Save** and wait for GitHub to set up your new blag.

### Please Note
* Read the [docs](https://hydejack.com/docs/)
* Requires Bundler. Install with `gem install bundler`.
* Repo found here: https://github.com/qwtel/hy-starter-kit/archive/master.zip
