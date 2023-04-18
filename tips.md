1.git config --global user.(name/email) "xxx"  //记录修改人的名字与邮箱
2.git init                                     //在当前文件夹下创建一个仓库
3.git add (./xxx.cpp ...)                      //在该文件夹下将文件后加入暂存区（相当于等待修改）
4.git log                                      //查看版本迭代
5.git commit -m "备注...."                     //提交到仓库里（相当于完成修改）
6.git checkout HEAD xxx.cpp                    //回滚到已保存的最新版本