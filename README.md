Lab 1
1. Create a helm chart for the app below and deploy it (try to keep everything changeable using values.yaml) https://github.com/SamarGooda/bakehouse-ITI.
 installed chart with the following command
 ```
 helm install bake ./bakehouse-ITI
 ```
 ![image](https://user-images.githubusercontent.com/47079437/217108997-6ddb66d9-6aad-449a-aa25-f6458f797e03.png)

  iam using a running instance so i needed a reverse proxy with nginx
  
  ![image](https://user-images.githubusercontent.com/47079437/217109292-53ea4ff0-266d-4926-adc0-6ce9151b28ac.png)

## my running app

![image](https://user-images.githubusercontent.com/47079437/217109367-724f7268-2786-430f-b817-fe76204e2b43.png)


2. Deploy Jenkins Chart on the cluster and login to Jenkins.

istalled the chart using the following command
```
helm install my-jenkins jenkins/jenkins
```
![image](https://user-images.githubusercontent.com/47079437/217109826-7bc18151-54c9-4497-a37a-848ea1519d79.png)
![image](https://user-images.githubusercontent.com/47079437/217109868-cd0f7419-4fde-4fa1-88c2-72f92034b0bd.png)
 iam using a running instance so i needed a reverse proxy with nginx
 ![image](https://user-images.githubusercontent.com/47079437/217109964-54525f50-9828-4f3e-8969-ee3b4eee8211.png)
## my running jenkins
![image](https://user-images.githubusercontent.com/47079437/217109909-09fcf0e9-cbc2-4a44-9570-d4f68fabd680.png)
![image](https://user-images.githubusercontent.com/47079437/217110030-5a1a6f54-c09c-42b1-a005-3057e44bf32d.png)

