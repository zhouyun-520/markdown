**zhouyun**
git config --global user.email xiaotian712572@163.com
git config --global user.name "zhouyun-520"
git config --global url."https://github.com.cnpmjs.org/".insteadOf"https://github.com/"
git checkout -b decelop
git branch -a
git add .
git commit -m "finished markdown"
git checkout main
git merge decelop
git push origin mai
