安装步骤：
1，如果在子目录中安装本面板，请修改application/config/config.php中的$config['base\_url']为基准url

2，修改application/config/database.php,填写使用的数据库信息

3，设置重写规则，例如nginx: rewrite ^(.**)$ /index.php?$1 last;**

4，访问http://yourdomain/install 按提示安装，安装过程中请不要刷新页面

5，访问http://yourdomain/ 注册用户并登陆，即可使用


User Guide:
1, If you install cp-share in a sub dir, please modify: "application/config/config.php" and set $config['base\_url'] to your base url.

2, modify: "application/config/database.php" and fill in the db message for cp-share.

3, set rewrite rule, for example nginx: "rewrite ^(.**)$ /index.php?$1 last;".**

4, visit http://yourdomain/install and follow the prompt, please don't refresh page during the Installation.

5, visit http://yourdomain/, register user and login into the panel, you can begin your happy using.