#Laravtice

##全局启用国内加速

composer config -g repo.packagist composer https://packagist.phpcomposer.com
##推送本地代码到远程

git init
git add .
git config user.email "dankegy@163.com"
git config user.name "Joe"
git commit -m 'Laravel5.3基础框架'
git remote add origin https://github.com/zhufeng-danke/Laravtice.git
git push -u origin master




