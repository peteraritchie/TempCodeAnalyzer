# TempCodeAnalyzer

- [x] verisoning
- [x] build
- [x] unit test
- [x] packaging
- [x] packaging artifact
- [ ] release ([draft a release](https://github.com/actions/create-release0, update release, upload asset)
- [ ] delivery?*
- [ ] acceptance*
- [ ] publshing ([release](https://github.com/marketplace/actions/publish-a-release), packages, [vsix](https://github.com/cezarypiatek/VsixPublisherAction/blob/main/src/main.ts))
- [ ] clean up (delete artifact)

https://github.com/marketplace/actions/create-release
https://github.com/marketplace/actions/publish-release

? Force a release from dev if version tag added to main that is greater than current

Things needed:

- [x] release version, latest (.github\actions\release-version-latest)
- [x] semantic version incrementor
- [ ] release-version-tag action

https://github.com/christian-draeger/increment-semantic-version/blob/master/entrypoint.sh