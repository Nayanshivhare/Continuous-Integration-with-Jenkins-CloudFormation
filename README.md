# Continuous-Integration-with-Jenkins-CloudFormation


1. Install Jenkins
2. Install cloud formation Plugin in Jenkins
3. Configure your Jenkins with your Github Repository
4. Select Build Trigger
    - GitHub hook trigger for GITScm polling
    
5. Go to your Github Repository Setting and select Webhooks
6. Create a webhook with Jenkins url and add /github-webhook/ in the end
    ![image](https://user-images.githubusercontent.com/66699491/213976003-24559c60-2017-4d2b-9913-8b5ee41fec2f.png)

7. Commit changes in Github file and it will start building automatically in Jenkins.

![image](https://user-images.githubusercontent.com/66699491/213975353-320180e1-7bf4-41e1-8958-9854743a3328.png)


