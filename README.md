# jenkins<br/>	  
# Tested on Ubuntu 20<br/>	  
<br/>	      
# Install Java<br/>
sudo apt-get update<br/>
java -version<br/>
sudo apt install -y default-jre<br/>
sudo apt install -y default-jdk<br/>
# Install Jenkins<br/>
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add - <br/>	
sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'<br/>	
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee /usr/share/keyrings/jenkins-keyring.asc > /dev/null <br/>	
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list > /dev/null <br/>	
sudo apt-get update<br/>
sudo apt install -y jenkins<br/>
