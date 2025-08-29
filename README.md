## Steps to make changes
- make changes in `jekyll_serve` branch
- After finishing update, run `bundle exec jekyll serve` to test with local ip address
- After verifying changes, run `bundle exec jekyll build` to generate the `_site` folder
- Copy the content inside `_site` into the deploy branch, and commit/push as usual.