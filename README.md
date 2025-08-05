# docker-domo
Introductions to Docker

### Docker is a platform that allows developers and system administrators to build, ship, and run applications in lightweight, portable units called containers.
### Log in to your AWS account and launch a new EC2 instance to set up Docker.

<img width="1440" height="814" alt="Screenshot 2025-08-01 at 2 52 27 pm" src="https://github.com/user-attachments/assets/b45e499b-a766-4adb-a272-d1ffb665c3fd" />

### It’s time to SSH into your EC2 instance. Use the connection information provided below and enter it into your terminal.

<img width="1440" height="814" alt="Screenshot 2025-08-01 at 2 57 56 pm" src="https://github.com/user-attachments/assets/e3499f74-ad02-430a-b8e8-311674552a91" />

Open your terminal and use your SSH key to connect to the server.


<img width="1440" height="900" alt="Screenshot 2025-08-01 at 3 04 41 pm" src="https://github.com/user-attachments/assets/e391cb7c-31c9-4e85-b56b-34afe5f500dc" />

### Now let's update the package list. with "sudo apt update"

<img width="1082" height="788" alt="Screenshot 2025-08-01 at 3 07 41 pm" src="https://github.com/user-attachments/assets/e273ce60-cdfb-465f-bc0e-02e8af1caeda" />


### Next, install essential packages to ensure your system can securely download software. "sudo apt-get install ca-certificates curl gnupg"

<img width="1222" height="539" alt="Screenshot 2025-08-01 at 3 08 48 pm" src="https://github.com/user-attachments/assets/c0d36bda-cd6c-4f6d-a92e-2e63d7d2200a" />

### Now, create a secure directory for storing trusted certificates. "sudo install -m 0755 -d /etc/apt/keyrings"

<img width="707" height="43" alt="Screenshot 2025-08-01 at 3 09 55 pm" src="https://github.com/user-attachments/assets/ace8ecec-00e8-4c56-abe1-c5c4873abeb8" />


<img width="1335" height="43" alt="Screenshot 2025-08-01 at 3 12 39 pm" src="https://github.com/user-attachments/assets/f9c9f25e-364f-4d4a-92e6-cd3b7ee35100" />

### Now, set the correct permissions for the Docker GPG key file so APT can use it securely.

<img width="1261" height="122" alt="Screenshot 2025-08-01 at 3 14 41 pm" src="https://github.com/user-attachments/assets/0b4cf75b-85bb-4def-b846-872677a1a94e" />

### Now, download and add the Docker GPG key to your system.

<img width="707" height="205" alt="Screenshot 2025-08-01 at 3 15 46 pm" src="https://github.com/user-attachments/assets/9695d9e2-83ef-469d-b650-3a7dfe46c69e" />

### Now, you can install the latest version of Docker on your system. "sudo apt update
sudo apt install -y docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin"



<img width="1440" height="900" alt="Screenshot 2025-08-01 at 3 18 40 pm" src="https://github.com/user-attachments/assets/be5a85ba-1e94-43ca-8b4b-eb3fd4bef3f4" />

### At this step, you need to execute the command docker run hello-world to verify that Docker is installed and working correctly.

## docker run hello-world
<img width="1295" height="448" alt="Screenshot 2025-08-05 at 3 19 16 pm" src="https://github.com/user-attachments/assets/6f095c47-bf1c-4142-8e4c-675ad422eda0" />

### this is part is to check the images on the container by "run docker images" (rewrite)
<img width="1081" height="99" alt="Screenshot 2025-08-05 at 3 22 55 pm" src="https://github.com/user-attachments/assets/a95807e3-8d6f-4498-acb5-b58666c11e1d" />

### The command docker ps -a is used to list all Docker containers on your system
<img width="1263" height="124" alt="Screenshot 2025-08-05 at 3 25 40 pm" src="https://github.com/user-attachments/assets/f192e1e2-3e4f-4afa-974e-24bfa4853b80" />

# Pull the latest version of the "ubuntu" image from Docker Hub
docker pull ubuntu

<img width="1127" height="134" alt="Screenshot 2025-08-05 at 3 27 19 pm" src="https://github.com/user-attachments/assets/83add17f-697d-490d-9a3f-dddba941a3a3" />

# Push a local image to Docker Hub
docker push boyals0408/hello-world


<img width="1049" height="465" alt="Screenshot 2025-08-05 at 3 41 51 pm" src="https://github.com/user-attachments/assets/9d3f32d4-0d72-484d-8732-a295374423c1" />


<img width="991" height="141" alt="Screenshot 2025-08-05 at 3 45 32 pm" src="https://github.com/user-attachments/assets/1ca1cdb4-01f9-4538-ab82-f6acc095839f" />

images push to the docker hub

username "boyals0408/hello-world" which is the first container 

<img width="1440" height="467" alt="Screenshot 2025-08-05 at 3 40 50 pm" src="https://github.com/user-attachments/assets/e95e846b-f9b1-4591-b117-76d7b5e8d8c3" />


username "boyals0408/ubuntu" which is the second container 

<img width="1172" height="458" alt="Screenshot 2025-08-05 at 3 46 38 pm" src="https://github.com/user-attachments/assets/27ad33b6-cc46-4e2f-85ca-74ee1ce7bc8a" />


The final step is to remove Docker images from your local machine. "run docker rm"


<img width="1054" height="393" alt="Screenshot 2025-08-05 at 3 58 27 pm" src="https://github.com/user-attachments/assets/28f8b226-c3c5-418c-9c70-0f5b669c4a78" />





