This is a Jekyll website.

To use this on a mac, it is best to
use `chruby 3.1.3` to switch to Ruby 3.1.3:

```
brew install chruby ruby-install
ruby-install ruby
chruby 3.3.1
```

Make sure Jekyll is installed:
```
gem install bundler jekyll
```

You can develop using:

```
chruby 3.3.1
jekyll serve
```

You can build using:

```
chruby 3.3.1
jekyll build
```

The build results are in `docs`.