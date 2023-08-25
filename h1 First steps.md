#h1 - Become a hacker step 0

## X) Read and summarize

### Ep 6: The Beirut Bank Job - https://darknetdiaries.com/episode/6/

In this episode a person called Jason was hired by a company to test the physical security of a bank. He communicates his experience of trying different ways to bypass the physical security and to access the most crucial places inside the bank. His background in law enforcement and experience in infosec make him well suited for his role.
He successfully completed breaking the security of 3 branches of the bank. He used different strategies in each bank. In the first branch he blended in with the workers very easily with careful timing and actions. The assumptions, miscommunication, and lack of verification among the employees in the first branch gave him chances to access the computers, make a new identity for himself in the branch, leave the office multiple times with sensitive materials, work by the teller’s computer which also gave him direct access to money. This emphasizes the potential consequences of underestimating the importance of security measures both physically and technologically in a professional environment. 
In the second branch he used the tactic trust which is a psychological approach and successfully stole a working computer. This emphasizes the importance of not just technological security but also the need for awareness among employees. Therefore, it is a must to give proper continuous education and awareness to the employees.
In the third branch he just got into the networking room with just one human interaction. This is because of the lack of knowledge of the employees, they think that locker is the only place that needs security not the other places. They need to be aware that even a person who might consider trusted can sometimes carry out unauthorized tasks in the workplace.
This episode shows the risks posed by social engineering and the neediness of multiple securities. 
But this episode doesn’t describe what are the steps taken by each branch to correct their security issues. And I think even though the branches taken steps to increase the security, Jason can still break the physical security because there are no place that is 100% secured.

### Kill Chain

A” kill chain,” is a systematic approach to targeting and engaging an adversary to achieve specific effects. This chapter introduces a new kill chain model which is specifically tailored for intrusions. In the intrusion, the aggressor aims to breach a trusted boundary, establishing a presence within a trusted environment, and taking actions to achieve their objectives.
The intrusion kill chain has several phases:

1. Reconnaissance: Gathering information about targets.
2. Weaponization: Combining a remote access trojan with an exploit to create a deliverable package.
3. Delivery: Transmitting the weapon to the target environment.
4. Exploitation: Triggering the intruder's code on the victim's system.
5. Installation: Placing a remote access tool on the victim's system for control access.
6. Command and Control (C2): Setting up communication with an external server for control.
7. Actions on Objectives: Carrying out actions to achieve the intruder's goals.

The intrusion kill chain is a useful model for defenders. They build their defense strategies with the steps attackers take. This approach is called intelligence-driven defense, it focuses on understanding the attackers and using that knowledge to make defenses smarter.
There's a table that lists different actions that defenders can take, like spotting, stopping, and confusing attackers. This matrix start at exploitation phase. These actions include things like using firewalls, intrusion detection systems, and even involving vigilant users. Completeness is important because it makes defenses strong against tricky attackers who change tactics. The chapter also shows an example where defenders get better at stopping attackers over time. It's all about understanding the attackers and making defenses stronger.

## b) Install Debian

#### create a new virtual machine steps

![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/a7c56559-967b-4678-8e7b-43c72955c73a)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/bedbd871-89ad-4f9c-8ea0-a6fee216377c)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/27e14cf0-b262-42af-87e5-b5a31dce9236)

#### boot to desktop and check functionality

![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/d0f81f76-f732-41fc-8cd9-50f98ff8419e)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/c65d9199-4f0d-41af-82ae-83ab2e6cfeb2)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/0a0557f6-0472-4561-9370-d4f4bd01edd5)

#### run the installer

![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/ddb3bdf5-939a-428b-b4f6-c3a32850fdf7)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/8dd58863-11c2-4942-bfaf-c70f09262cf8)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/0d0e4530-e30d-4768-b7e2-46d97ca24e3c)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/55d7e5d1-02ca-4f9f-ba83-78064799e18b)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/8b27e85e-a6bb-46cd-8d31-417245252fbb)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/b06ca7d2-84ba-46ff-a06a-9ef48cc6b680)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/c28343ad-c215-453c-bfc5-cf7fe3cd5ba8)
![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/dfa3bac2-89c9-488d-a9fd-eb369212df2f)

#### first loggin

![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/8a4d63c3-29c7-4856-aaf2-81ecf0c036a7)

#### first steps

![image](https://github.com/QwQw-1122/Information-Security-course/assets/142783507/3e0ab269-b7bb-4e46-a779-b7674792bbd8)

## c) voluntary bonus: My fundaments

The fundamental of security offers the basis of a strong effective security strategy. These principles are needed to secure the information system and other sensitive systems from various threats. 
Some fundamentals are,
1.	Confidentiality: sensitive information should only be visible to authorized person.
2.	Integrity:  The accuracy and reliability of the data and system need to be protected by preventing any unauthorized modifications
3.	Authentication: verify the identity of the user when access to a secured information
4.	Physical Security: to protect physical assets.
5.	Regular update: keeping system update with latest security. 
We do these because not expecting a perfect security but to give something expensive and time consuming for the hackers to breach so they eventually change their target.


