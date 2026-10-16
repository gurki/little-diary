# little diary 📔
> a collection of tid bits, small projects and thoughts

## Local preview

Use Ruby 3.3 (matching `.ruby-version` and CI). On an Apple Silicon Mac with Homebrew:

```sh
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
rehash
bundle install
bundle exec jekyll serve --drafts --livereload
```

Open <http://localhost:4000/little-diary/>. Stop with Ctrl+C.
The `--drafts` flag includes the Terry draft.
