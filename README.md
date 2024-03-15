# sg200x-evb boards.

step1:
```
git clone -b sg200x-evb git@github.com:sophgo/sophpi.git
cd sophpi
./scripts/repo_clone.sh --gitclone scripts/subtree.xml
```
step2:
```
source build/cvisetup.sh
defconfig sg200x_duo_sd
clean_all
build_all
```
