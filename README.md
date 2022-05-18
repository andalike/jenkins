# jenkins<br/>	  
<br/>	      
# Install Java<br/>
sudo apt-get update<br/>
java -version<br/>
sudo apt install -y default-jre<br/>
sudo apt install -y default-jdk<br/>
# Install Jenkins<br/>
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add - <br/>	
sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'<br/>	
sudo apt-get update<br/>
sudo apt install -y jenkins<br/>
