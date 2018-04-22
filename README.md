# cayenne-release-tools

`sigchecker` verifies release artifact checksums and signatures.

```
export RELEASE_DIR=X.XX
mkdir $RELEASE_DIR ; cd $RELEASE_DIR
wget -r -nd -np <release download dir at dist.apache.org>
sigchecker 
```
