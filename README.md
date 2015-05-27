This is a repo manifest for a helloworld application that
runs on seL4.

Its derived from the sel4test https://github.com/seL4/sel4test-manifest.

Basic instructions:

Install repo, for instance:
```
mkdir -p ~/bin
export PATH=~/bin:$PATH
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo
```
And then create a directory for the project and then init and synchronize:
```
mkdir sel4-helloworld
cd sel4-helloworld
repo init -u git@github.com:winksaville/sel4-helloworld-manifest.git
repo sync
```
See the sel4-helloworld README.md (https://github.com/winksaville/sel4-helloworld)
file for more instructions.
