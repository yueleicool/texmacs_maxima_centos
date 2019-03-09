# texmacs_maxima_centos
关于centos7安装完毕后，系统自带的yum源无法搜索到texmacs和maxima软件，现解决方案如下<br>
在github中下载yueleicool/texmacs_maxima_centos，<br>
在其中找到yum.repos.d文件夹中之文件，<br>
并在centos系统中找到/etc/yum.repos.d文件夹中的文件并替换之。<br>

texmacs_maxima_centos<br>
搜索texmacs maxima软件如下：
yum search texmacs <br>
yum search maxima <br>

由于切换了centos源之后校验文件不正确提示信息如下<br>
GPG key retrieval failed: [Errno 14] curl#37 - "Couldn't open file /etc/pki/rpm-gpg/RPM-GPG-KEY-EPEL-7"<br>
解决方案如下所示<br>
yum install --nogpgcheck package_need_to_instal

