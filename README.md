## How to start

```bash
# install gems (only need to run on first time)
bundle install --path=.bundle/vendor --binstubs=.bundle/bin

# run via rake
bundle exec rake

# check the output
cat result.txt

# let's edit the data
vim data.yml

# run and check the output change
bundle exec rake
cat result.txt
```

## What to do next?

Write your own config generator!
