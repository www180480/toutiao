1.vue-cli创建项目
    vue create 项目名
2.加入git版本管理
    （1）创建远程仓库GitHub，码云，coding.....
    （2）将本地仓库推到线上
    git remote add origin https://github.com/www180480/toutiao.git
    git push -u origin master
    问题：在利用git上传到仓库的时候遇到如下报错：
    unable to access 'https://github.com/NJUThinyi/2019Summer.git/': OpenSSL SSL_connect: SSL_ERROR_SYSCALL in connection to github.com:443
    参考网上的结果，需要配置如下：
    $ git config --global http.sslVerify false