# react-gallery

In here, build and deploy a React component and make it available in Liferay DXP

**What is Liferay?**

Liferay is the Java EE portal that you can create websites it’s like wordpress.
Liferay allows you to create a website using developer-created portlets in the portal. While developing, after installing liferay server on your computer, you can make changes to the portlets and view them on the website.

**Set up**

local installation of Liferay DXP
(download - https://www.liferay.com/en-AU/products/dxp/30-day-trial)
*Bundled with tomcat

Check your email for your trial key

Preparing for installation (pre-requirements)

requires a JDK - install java (11.0.11 or 8) and set JAVA_HOME

**Run**

Unzip downloaded folder

Download trial key and paste to deploy folder

Go inside to tomcat-9.0.37 folder

-> go to bin folder

-> _ls -lt_ (showing files)

-> **_vi setenv.sh_** (open the setenv.sh file and add JAVA_HOME=”/usr/lib/jvm/java-11-openjdk-amd64”) and save

-> run **_sh startup.sh start_**

-> Now tomcat is started

-> cd .. → ls -lt → cd logs (goto one level back and logs folder)

-> **_tail -f catalina.out_** (telling status about the liferay installation)(optional)

-> Now liferay is being started

-> run localhost:8080

**Login**

-> default password is test

-> Then, change your password

**Deploy**

-> npm run deploy
