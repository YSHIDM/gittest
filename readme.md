# ceshi

git symbolic-ref --short HEAD
git remote add origin https://github.com/YSHIDM/gittest.git
git symbolic-ref --short HEAD
git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track) refs/heads/master refs/remotes/master
git remote --verbose
git for-each-ref --sort -committerdate --format %(refname) %(objectname) %(*objectname)
git config --get commit.template