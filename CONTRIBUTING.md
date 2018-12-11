#1 Contributing

1. Check out the [issues](https://github.com/rpearce/oss-template/issues)
1. [Fork](https://guides.github.com/activities/forking/) this repository
1. [Clone](https://help.github.com/articles/cloning-a-repository/) your fork
1. Add the upstream project (this one) as a git remote:
  * `$ git remote add upstream git@github.com:rpearce/react-medium-image-zoom.git`
  * `$ git fetch upstream`
  * `$ git rebase upstream/master`
1. Check out a feature branch
  * `$ git checkout -b my-feature`
1. Make your changes
1. Push your branch to your GitHub repo
  * `$ git push origin my-feature`
1. Create a [pull request](https://help.github.com/articles/about-pull-requests/)
   from your branch to this repo's `master` branch
1. When all is merged, pull down the upstream changes to your master
  * `$ git fetch upstream`
  * `$ git merge upstream/master`
1. Delete your feature branch
  * `$ git branch -D my-feature` (locally)
  * `$ git push origin :my-feature` (to delete on GitHub)
