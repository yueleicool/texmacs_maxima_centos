# texmacs_maxima_centos
texmacs_maxima_centos<br>
搜索texmacs maxima软件如下：
yum search texmacs <br>
yum search maxima <br>

由于切换了centos源之后校验文件不正确提示信息如下<br>
GPG key retrieval failed: [Errno 14] curl#37 - "Couldn't open file /etc/pki/rpm-gpg/RPM-GPG-KEY-EPEL-7"
解决方案如下所示<br>
yum install --nogpgcheck package_need_to_instal

