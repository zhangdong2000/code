码云配置
git config --global user.name '长弓晗炅' ;
git config --global user.eamail 'zhangdong_1582@163.com' ;

mkdir code
cd code
git init
touch readme.md
git add readme.md
git commit -m "first commit"
git remote add origin https://gitee.com/cuteboy1582/code.git
git push -u origin master
