Linux Virtual Disk Image Downloads
CentOS 7 – Gnome Desktop VDI – Download

https://drive.google.com/file/d/1AlyfH_Ct1Yrioz4PFLndSg8nq2IVsY8S/view?usp=sharing

Username: adminuser

Password: adminuser

Root Password: adminuser

-----------------------------------------------------------------------------------------

Download Nexus war file:

https://drive.google.com/file/d/1k2AtIN0EZXWT5ejulS-hOc3azC2hVzX7/view?usp=sharing

=============================================================================================================


Download RPM file:   wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u151-b12/e758a0de34e24606bca991d704f6dcbf/jdk-8u151-linux-x64.rpm"


Download JDK:
wget -c --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x64.tar.gz


Download Maven:
wget http://mirrors.wuchna.com/apachemirror/maven/maven-3/3.6.0/binaries/apache-maven-3.6.0-bin.tar.gz


 wget -c --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download
.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jdk-8u131-linux-x64.tar.gz


   ll
    
   pwd
    
   mkdir workspace
   
   cd workspace/
   
   mkdir batch14
   
   ll
   
   cd /vagrant/
   
   cp jdk-8u131-linux-x64.tar.gz /vagrant/workspace/batch14/
   
   cd /vagrant/workspace/batch14/
   
   tar -xzvf jdk-8u131-linux-x64.tar.gz
     
   rm -rf jdk-8u131-linux-x64.tar.gz
   
   jdk1.8.0_131/
      
   mv jdk1.8.0_131/ java8
      
   cd java8/
      
   pwd
   
   java -version
   
   export JAVA_HOME=/vagrant/workspace/batch14/java8
   
   export PATH=$JAVA_HOME/bin:$PATH
   
   java -version
   
   which java
   
