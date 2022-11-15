# jenkins-installtion

sudo su
sudo yum update -y
amazon-linux-extras
amazon-linux-extras install java-openjdk11 -y
sudo wget -O /eyum tc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
yum install jenkins -y 

systemctl enable jenkins
systemctl start jenkins
systemctl status jenkins

sudo cat var/file on jenkins site
