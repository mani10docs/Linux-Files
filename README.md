Linux Virtual Disk Image Downloads
CentOS 7 – Gnome Desktop VDI – Download

https://drive.google.com/file/d/1AlyfH_Ct1Yrioz4PFLndSg8nq2IVsY8S/view?usp=sharing

Username: adminuser

Password: adminuser

Root Password: adminuser

-----------------------------------------------------------------------------------------

Download JDK:
wget -c --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x64.tar.gz

Download Maven:
wget http://mirrors.wuchna.com/apachemirror/maven/maven-3/3.6.0/binaries/apache-maven-3.6.0-bin.tar.gz


 wget -c --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download
.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x6
4.tar.gz
    8  ll
    9  pwd
   10  mkdir workspace
   11  cd workspace/
   12  mkdir batch14
   13  ll
   14  cd /vagrant/
   15  cp jdk-8u131-linux-x64.tar.gz /vagrant/workspace/batch14/
   16  cd /vagrant/workspace/batch14/
   17  ll
   18  ll
   19  tar -xzvf jdk-8u131-linux-x64.tar.gz
