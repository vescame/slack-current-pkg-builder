# Slackware Current package build

### build pkgs from https://github.com/Ponce/slackbuilds.git

``` sh
git clone https://github.com/Ponce/slackbuilds.git /tmp/slackbuilds
cd /tmp/slackbuilds

git clone https://github.com/vescm/slack-current-pkg-builder.git /tmp/mybuilder

ln -s /tmp/mybuilder/buildpkg /tmp/slackbuilds/buildpkg

cd /tmp/slackbuilds

./buildpkg system/docker
```

