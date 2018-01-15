git_tagger


This is a bash script that can bump your repo's version and requires no more than shell.

```bash
  git_tagger
  
  This tool bumps your repository's version and pushes the tag to remote git.
  
  Version: 0.1.1
  
  Usage:
  
  git_tagger [options]
  
  Options:
  
  -s, --master                tag master branch.
  -t, --target  <BRANCH>      tag target branch.
  default is staging.
  -v, --version <VERSION>     bump current version to a target version.
  -e, --extra                 add extra description for the tag.
  
  --init                      create VERSION, CHANGELOG.md and README.md.
  --install                   install this script to your environment.
  --update                    update this script, keeping it warm.
  
  
  -h, --help                  show guidance.

```


lli
