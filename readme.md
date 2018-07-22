# Bundler issue #6216

"foobar" is a fake gem I created with a dummy gemspec.  I created
multiple versions simply by bumping the version in the gemspec and
running `gem build foobar.gemspec`.

1. Run `gem generate_index --directory ./gems`
2. In another terminal, run `rake s` to serve the gems via localhost.
3. Run `bundle`.
