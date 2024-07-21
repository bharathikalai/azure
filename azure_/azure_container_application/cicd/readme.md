# azure container application cicd

## steps
### 1. create a azure resource group

### azure resource group name (cicd-resourcegroup)
![alt text](image.png)


## 2. create a azure container registry

### step 1: search container registry
![alt text](image-1.png)


### step 2: (click review + create button)
![alt text](image-2.png)


## 3. create a app serice

### step 1: search app service
![alt text](image-3.png)

### step 2: click create button and select web app
![alt text](image-4.png)

### step 3: choose container and click review + create button
![alt text](image-5.png)



## 4. create manage identity 

### step 1: search manage identity
![alt text](image-6.png)

### step 2: click review + create button
![alt text](image-7.png)

### step 3: open the manage identity and assign the role called ACRPULL
![alt text](image-8.png)


## 5. add the manage identity resource group to the app service
![alt text](image-9.png)


## 6. create a azure devops pipeline(use this folder app-container-cicd)
![alt text](image-10.png)


## 7. configur the agent on your local machine (create agent on azure devops)
![alt text](image-11.png)


## 8. go to the azure app service deployment center and select the repository and select the manage identity and add image and tag name

## 9. click this default domain to verify your app running state
![alt text](image-12.png)

## finally :)

![alt text](image-13.png)