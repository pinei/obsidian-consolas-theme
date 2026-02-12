\## Steps for releasing new versions



* Set the new version in manifest.json
* Commit and push the changes



\*\*Manual release\*\*



* From your theme's repository, click on "Create a new release"
* Fill out the Release information form.
* Create a new tag for the new version
* Click "Publish Release."



\*\*Using GitHub workflow\*\*



* Create a new tag with `git tag`
* Push the tags to GitHub



```

git tag 1.0.7

git push --tags

```



The `release.yml` workflow will dispatch

