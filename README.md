# software
开发人员：
林清泉、向文羽、肖建华、梁称、吴俊达

项目上传github地址：https://github.com/Mr-lq7/software
1.去上述地址下载software-version2.zip，初始用户信息.csv，坪山区民生诉求完整版.csv
2.下载pycharm专业版，用pycharm打开soft-version2文件夹下的FlaskProject1文件夹
3.下载mysql，配置好相关环境，用户名默认，密码自行设置，打开workbench，新建两个表(tables)，
一个命名为project_data，一个命名为user_info(分别导入坪山区民生诉求完整版.csv文件和初始用户信息.csv文件，注意要改成utf-8编码)
4.打开pycharm，在运行app.py之前，先打开mysql的workbench，输入密码登入，先启动数据库
5.运行app.py文件，运行成功后，打开火狐浏览器输入http://127.0.0.1:5000/login访问。