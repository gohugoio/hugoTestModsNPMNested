In this commit we added a `package.hugo.json` file. In Hugo v0.159.0 we rewamped the npm package support, but we kept the `package.hugo.json` as the first choice when merging:

* Mostly to preserve as much backward compability as possible.
* We need to get some user feedback on this, but it may make sense to have such an override file, so people can opt in to having a separate dependency set for Hugo.
