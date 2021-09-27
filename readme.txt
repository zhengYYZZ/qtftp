This repository contains deprecated APIs which have been removed from Qt

Applications are recommended to port to the supported APIs.
However as some features are lost, these APIs are provided as standalone
source code for applications that require removed features.

Note: If you downloaded the source package from a hosting service
such as Gitorious, the package does not contain the generated headers
under the ./include directory. Before building, you'll need to generate
them manually by running the syncqt Perl script. For example:

cd qtftp
<QTDIR>/bin/syncqt.pl -version 5.1.0

-------------------------------------------------------------------
需要安装perl,地址： http://strawberryperl.com
先构建qtftp_src,再构建qtftp_examples
