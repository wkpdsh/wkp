# markdown
git config --global user.email 2802487112@qq.com                          

git config --global user.name"wkpdsh"                           

git config --global url."https://github.com.cnpmjs.org/".insteadOf"https://github.com/"



git checkout-b develop

git branch -a

git add .

git commit -m "finished markdown"

git checkout main

git merge develop

git push origin main
