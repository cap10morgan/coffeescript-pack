## CoffeeScript pack

This pack adds coffee-mode for CoffeeScript support in Emacs Live.

### Usage

This pack uses git submodules, so remember to clone the repository
recursively:

    git clone git@github.com:cap10morgan/coffeescript-pack.git --recursive

Once that's done, add coffeescript-pack to your emacs-live configuration
by adding this line to your `~/.emacs-live.el` file (or add it to the list
if you already have a `live-add-packs` form):

    (live-add-packs '("/path/to/coffeescript-pack"))

Then, you'll need to restart emacs. It's that easy!

### Changes

* 1.0.1 - update coffee-mode to v0.5.0
* 1.0.0 - initial release
