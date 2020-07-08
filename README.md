# jenkins
Jenkins Word file
sudo apt-get update<br/>	      
sudo apt install -y openjdk-8-jre-headless<br/>
wget -q -O - https://pkg.jenkins.io/debian/jenkins-ci.org.key | sudo apt-key add -<br/>
echo deb https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list<br/>	
sudo apt-get update<br/>
sudo apt-get -y install jenkins<br/>
