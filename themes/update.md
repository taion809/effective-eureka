you can use as submodule with

git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
Note: You may use  --branch v7.0 to end of above command if you want to stick to specific release.

Updating theme with Method 2 :

git submodule update --remote --merge
