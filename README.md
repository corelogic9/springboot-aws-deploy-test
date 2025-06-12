# springboot-aws-deploy

This is a sample microservice to deploy it on AWS ECS.

To build automated AWS CodePipeline and deploy microservice to AWS ECS, follow tutorial as shown in video :

Health Check command for AWS Task definition : 
```
CMD-SHELL,curl -f http://localhost:8080/actuator/health || exit 1
```


Prerequisite :
1. AWS acconunt.
2. Git and docker installed on the machine.
3. Docker should be started before building docker image.
4. And your favourite code editor

Snapshots:

![WhatsApp Image 2025-05-28 at 4 37 25 PM](https://github.com/user-attachments/assets/48fa55da-e0d1-4bb0-a518-19105774a22d)
![WhatsApp Image 2025-05-28 at 4 37 56 PM](https://github.com/user-attachments/assets/b6ff1b8e-73b7-463b-93be-742993f5f3e3)
![WhatsApp Image 2025-05-28 at 4 43 21 PM](https://github.com/user-attachments/assets/973b5dd7-38bb-47da-915c-ff4976c8e9a9)
![WhatsApp Image 2025-05-28 at 4 47 20 PM](https://github.com/user-attachments/assets/d4296201-5d58-4d2b-abd6-53b64f6e0add)
![WhatsApp Image 2025-05-28 at 4 51 38 PM](https://github.com/user-attachments/assets/18d95998-3de5-402d-b9b2-8f958078d9e0)
![WhatsApp Image 2025-05-28 at 4 52 35 PM](https://github.com/user-attachments/assets/b0ddf9a2-04cc-431e-bdb2-77ceebfceada)
![WhatsApp Image 2025-05-28 at 4 53 06 PM](https://github.com/user-attachments/assets/4f641c91-bd13-42ed-908a-040ce8363b94)

