# docker_MobSF
Install Mobile Security Framework with Docker

First :

Install docker.io from CLI (i'm using CLI PowerShell on KaliLinux)

  $ sudo apt install docker.io

  ![image](https://github.com/rbp-x/docker_MobSF/assets/2045755/e7c116fd-6bca-4f9d-8c18-1e2fcb961428)

Pulling and Downloading MobSF from docker

  $ sudo docker pull opensecurity/mobile-security-framework-mobsf

  (this process takes time)

  ![image](https://github.com/rbp-x/docker_MobSF/assets/2045755/ec5f380b-c9f7-4075-a8b4-5050c6ca579c)

Pulling done !

  ![image](https://github.com/rbp-x/docker_MobSF/assets/2045755/3c185c71-0e5e-458b-922c-a2b654e6c140)

Now, we can show and running MobSF Docker Image !

  $ sudo docker image ls -a
  
  ![image](https://github.com/rbp-x/docker_MobSF/assets/2045755/7e45c59a-652f-4c65-9f3a-538a58615a6f)

  $ sudo docker run -d -p 8000:8000 [image id]

  $ sudo docker container ls -a

  ![image](https://github.com/rbp-x/docker_MobSF/assets/2045755/79cd286f-4a36-4dc7-9769-3270582937b2)

Now, run Mob-SF in Browser !

  $ Open your browser and type 'localhost:8000' :

  ![image](https://github.com/rbp-x/docker_MobSF/assets/2045755/09d0b4cf-3da1-4701-a611-082960c7f2f6)

## We have done installation Mobile Security Framework with Docker, Mob-SF Powerfull for analyze, bug scanning, vulnerability scanning for application builder from file android [apk] on localhost, and you no neew to worry source code or aplicaton .apk spread out on the Internet.

## Thanks !

  

