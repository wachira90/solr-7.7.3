# solr-7.7.3
solr-7.7.3 for linux

##install centos 7
sudo yum install java-1.8.0-openjdk  java-1.8.0-openjdk-devel -y
sudo yum install java-1.8.0-openjdk -y
sudo alternatives --config java
java -version

##env setting
export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.242.b08-0.el7_7.x86_64/jre
export SOLR_HOME=/home/solr/solr-7.7.3

##start
$SOLR_HOME/bin/solr start

##stop
$SOLR_HOME/bin/solr stop -all

##status
$SOLR_HOME/bin/solr status

##location
http://localhost:8983/

