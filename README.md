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












