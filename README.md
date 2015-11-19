# How to use git-lfs?

Download and install git-lfs from [here](https://git-lfs.github.com/).

Run this once:
```
git lfs install
```

Then add file types that will be managed by git-lfs:
```
git lfs track "*.dat"
```

Then add and commit large files as you normally do:
```
git add output.dat
git commit -m "Add large file"
git push origin master
```
