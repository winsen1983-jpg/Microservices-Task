Microservices Task
1.Forked the Repo to my Githup
2. Cloned to Local machine
3. Created Dockerfile
<img width="433" height="158" alt="image" src="https://github.com/user-attachments/assets/9afed520-62aa-4467-a390-edf06141f83c" />

FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "app.js"]

4. Created Docker-compose.yaml file for building the Dockers
 <img width="830" height="983" alt="image" src="https://github.com/user-attachments/assets/90025dfa-34a8-4095-902e-922e7f54bf83" />

5. Dockers Created
 <img width="975" height="511" alt="image" src="https://github.com/user-attachments/assets/8f87175f-0f77-46bb-a7a9-48153c3af114" />

6. In Docker Desktop
7. <img width="975" height="550" alt="image" src="https://github.com/user-attachments/assets/fdf227e6-2c27-4816-9685-676ab4cfed51" />

Results:
 
 <img width="769" height="273" alt="image" src="https://github.com/user-attachments/assets/5bf0b615-3257-40cb-bfab-60e831013a5c" />
 <img width="939" height="263" alt="image" src="https://github.com/user-attachments/assets/d7fd3464-bb6a-42fb-8000-83a3c9c13d9d" />
 <img width="575" height="295" alt="image" src="https://github.com/user-attachments/assets/f86336f4-6974-4475-8047-95ca307322ae" />
 



 
 

