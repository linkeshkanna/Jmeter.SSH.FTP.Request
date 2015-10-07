# Jmeter.SSH.FTP.Request
Jmeter Custom Sampler to make SFTP Request

To Create SSH FTP Requests in JMeter, we need this custom Sampler.
This contains two jar files.
1. jmeter-ssh-sampler-1.0.2-SNAPSHOT.jar
2. jsch-0.1.53.jar
We can generate this by downloading the source and building it using Maven.

I just built it using maven and checked in the jar files here.

To install this in Jmeter,
1. Copy the jmeter-ssh-sampler-1.0.2-SNAPSHOT.jar to the "Jmeter/Lib/ext" directory.
2. Copy the "jsch-0.1.53.jar" to the "Jmeter/Lib" directory
3. Restart Jmeter.

I have also added a sample test to list of the directory contents in a Public SFTP Server.
