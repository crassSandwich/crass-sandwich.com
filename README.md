Powered by [Hugo](https://gohugo.io/). Theme is my slightly modified [fork](https://github.com/crassSandwich/cocoa-eh-hugo-theme) of [Cocoa Enhanced](https://github.com/fuegowolf/cocoa-eh-hugo-theme).

So far, this only requires vanilla Hugo. At some point I'd like to add minification to the build process (as opposed to in the CDN as it is now). The page lives in the `docs/` folder in this repo. `deploy.sh` simply builds the site then pushes to GitHub.

If you're going to clone this, make sure to set the `--recurse-submodules` flag or run `git submodule update --init --recursive` afterward, since the theme is set up as a submodule.
