#h2 - Spiderwebs

## x) Read and summarize

### Security Misconfiguration
This occur when certain vulnerabilities are present in an application due to improper settings. These vulnerabilities include missing security measures, enabled unnecessary features, unchanged default accounts, error handling revealing sensitive information, and more.
To prevent security misconfigurations, it is important to implement secure installation processes, such as using repeatable hardening procedures to ensure consistent configurations across different environments. And recommends maintaining a minimal environment with only essential features, updating configurations in line with security notes and patches, reviewing cloud storage permissions, using segmented application architecture for better separation between components, sending security directives to clients, and employing automated processes to verify configuration effectiveness across environments.

### Vulnerable and Outdated Components
The application might be at risk if there is lack of knowledge about component versions, usage of unsupported software, failure to scan for vulnerabilities, and neglecting timely updates. 
To prevent these risks, it is recommend to implement a patch management process to remove unused dependencies, regularly tracking component versions and vulnerabilities, obtaining components from secure sources, and monitoring unmaintained libraries. This also shows the need for ongoing monitoring, updates, and configuration changes throughout the software's lifetime.

### Injection
This happens when user-supplied data isn't properly validated or sanitized, leading to potential attacks. Various types of injections, including SQL, NoSQL, OS command, ORM, LDAP, and Expression Language injections, are covered. 
Preventive measures involve keeping data separate from commands, using safe APIs, employing positive server-side input validation, escaping special characters, and using SQL controls like LIMIT to prevent mass data disclosure. And also suggests utilizing source code reviews and testing tools like SAST, DAST, and IAST in the CI/CD pipeline to identify injection flaws before deployment.

## a) Install webgoat

1st open the vitrual box manager and double click on the virtual machine created.
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/cee5f312-1867-40e2-b9a3-c68aa4d55b35)

After login to the virtual machine click on the 'Application' on top left corner and choose 'Terminal Emaluator'
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/8618e6f3-244e-4b6e-8239-695b4aae9633)

To install Java, type below commands and also activate the firewall
sudo apt-get update
sudo apt-get -y install openjdk-17-jre ufw wget bash-completion
sudo ufw enable
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/df79c08e-6603-42dc-8fea-19324ff208dc)

To Install webGoat type below command.
wget https://terokarvinen.com/install-webgoat-web-pentest-practice-target/webgoat-server-8.0.0.M26.jar
java -jar webgoat-server-8.0.0.M26.jar
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/66f01025-0cf2-4ef7-aca7-b6ec3d62dd2c)

Register in the WebGoat page, open the browser and type http://localhost:8080/WebGoat/
then click on register, fill the details as below
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/66b6afb4-416d-4aa9-92d4-beeb3307290e)

## b) Solve Webgoat 8: General: Developer tools

To check the developer tools in firefox, right click on the page and select Inspect as below
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/5535079c-b8ca-49d0-8bad-023335114b82)

This will open a tab where we can see page HTML, CSS Network traffic etc
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/7622dba2-35c8-433a-9302-c6d05fc6ae31)

Assignment 1 - Try It! Using the console
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/1746327d-ecd0-407a-b5c7-29103ca728ac)

Assignment 2
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/83f37c98-9d8e-4329-8aad-68168a4dc637)

## c) Update all OS and all applications in your Linux

Go to the 'Terminal Emaluator' and type below command
sudo apt-get -y dist-upgrade
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/f2dac48c-fbd8-47f5-9aab-9872dc8a8314)

## d) Solve SQLZoo

### 0 SELECT basics
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/aa7a0d2f-6f74-4808-bd1b-2ee63eae59ab)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/40ec5ba8-156e-427a-803b-996f00a33775)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/76cdd443-88d9-44a1-8d28-d677a4b34706)

### 2 SELECT from World
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/4a2d6490-0876-4c69-8878-731e3e11ef50)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/57b14e3f-d67b-40d6-b7a7-c32496f53348)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/9edcdbe5-f9c0-4bc8-811f-a61a472571a5)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/1bbc3a46-f4b9-4337-a0ed-e31722f605bd)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/b3dea7c3-2982-4967-a94b-b00ef8fbdc54)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/59e590e6-ffd9-4b29-9358-a3f3546e9221)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/625e355c-e2d9-47ed-92e6-1da9ce1ffe5a)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/48e64d77-e222-48aa-99c6-23a9eafc2934)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/46ea1add-71e2-42ff-b8ba-03c208e5a535)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/30ab6ca3-6551-4883-ab18-7be922a53b4a)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/df10f313-e5f9-4b03-8ca3-f091adbf8c96)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/27dffd51-6579-4da8-b06e-bce1e70400bd)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/dc269a0b-1df1-4b58-be09-4c321612250b)

## e) Johnny tables. Solve Portswigger Labs - SQL injection
when we go to the website and search for a category the website link apears as below
b0346dba681f7d9f900780082.web-security-academy.net/filter?category=Clothing%2c+shoes+and+accessories
This will give the below SQL
SELECT * FROM products
WHERE category ='Clothing, shoes and accessories'
But we need an output of one or more unreleased products in all categories
To get that we need an SQL like below
SELECT * FROM products
WHERE category ='Clothing, shoes and accessories' OR 1=1
This OR 1=1 shows the products in the mention catogery OR 1=1
since this is always true this will return all the other catogeries products also

b0346dba681f7d9f900780082.web-security-academy.net/filter?category=Clothing%2c+shoes+and+accessories'+OR+1=1--
when we add -- anything written after this will consider as a comment
<img width="845" alt="image" src="https://github.com/QwQw-1122/Information-Security-course/assets/142783507/1531e111-d122-4249-b7d3-6afb3db98ab2">







