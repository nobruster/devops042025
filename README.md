git config --local --list

git log --oneline

git init --help

git remote

git remote -v

git remote add localbare /var/repositorio

git remote remove localbare 

git remote show localbare

git push localbare

git branch -m main

git config --local --list

git pull localbare main

git config  pull.rebase true

git config --global pull.rebase true

echo "# devopsgcmb" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nobruster/devopsgcmb.git
git push -u origin main

git remote add origin https://github.com/nobruster/devopsgcmb.git
git branch -M main
git push -u origin main

dpkg -la | grep gcm-linux

dpkg -l gcm


gpg --list-keys

git status

git config --global user.name "Your Name"
git config --global user.email you@example.com

git commit --amend --reset-author

