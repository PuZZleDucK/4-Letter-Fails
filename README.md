
# 4 Letter Fails
This GitHub Action checks your README.md for profanity and fails if any is found.

### Using 4 Letter Fails
```
steps:
    - uses: actions/4-letter-fails@v1
```

### Developing
* Clone repo: `git clone git@github.com:PuZZleDucK/4-Letter-Fails.git`

### Badges
You can create a badge for your profanity filter by...
Example badge here

### GitHub Actions Hackathon
This is also my entry for the GitHub Actions For Open Source hackathon on DEV.to


### Release Management

* Create & validate a release branch: `git flow release start v1`
* Tag release: `git tag -a v1.0.0 -m "Release 1.0.0 - Slanderous Skink"`
* Create release on GitHub
* Move the major version tag (such as v1, v2) to the latest point release
* Introduce a new major version tag (if needed)

### Releases - Changelog

Version 1.0.0 - Slanderous Skink
* Initial release

### Current Limitations
* Only checks README.md
* fixed profanity list
