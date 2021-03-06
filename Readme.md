[![wercker status](https://app.wercker.com/status/e5de34ea12621048b31c9ca33dfdb4d2/m "wercker status")](https://app.wercker.com/project/bykey/e5de34ea12621048b31c9ca33dfdb4d2)


## You want to contribute?

Open your terminal, and `cd` to the right directory. You will work in a branch, and submit a pull request!

```bash
# First get up to date
$ git checkout master        # Go back to master branch
$ git pull origin master     # Fetch latest version
$ git sweep                  # Get rid of merged branches (Download)[http://lab.arc90.com/2012/04/03/git-sweep/]
$ bundle install             # Maybe the guys changed the Gemfile :)

# Launch the server, then go to http://localhost:9292
$ bundle exec rerun rackup   # You may do this in another tab.

# Open another terminal, and create a branch to work in
$ git checkout -b your-new-feature  # Please choose a descriptive name
$ stt  # Open sublime text and work.
$ open assets/images   # If you need to add images

# Done? Great!
$ git status
$ git add .  # Git add the stuff you changed
$ git commit -m "a descriptive message about your change"
$ git push origin your-new-feature  # push YOUR branch
# Then go to GitHub and open a pull-request
```
