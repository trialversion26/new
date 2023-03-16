#### Step 2 - Push images to Docker Hub

###### PreRequiste - You need to have Docker Hub account 


```
docker login 
```
###### Give your Dockerhub Username & Password
###### Once you login Create a Repository in DockerHub 

- Create a repository named ui

```
docker tag ui bsairangapavan/ui:v1
```
```
docker push bsairangapavan/ui:v1
```
###### You can able to see like below 
![viui](https://user-images.githubusercontent.com/121741348/225616962-cccc0b5f-7353-4577-bf52-6386a0238e62.png)

- Create a repository named zuul 
```
docker tag zuul  bsairangapavan/zuul:v1
```
```
docker push bsairangapavan/zuul:v1
```
###### You can able to see like below 
![zuul](https://user-images.githubusercontent.com/121741348/225617583-f70ae645-7423-479f-898b-f101a80f1d5a.png)

- Create a repository named shoes
```
docker tag shoes bsairangapavan/shoes:v1
```
```
docker push bsairangapavan/shoes:v1
```
###### You can able to see like below 
![shoes1](https://user-images.githubusercontent.com/121741348/225618003-372ded62-233a-4da0-aeb2-d07a3df3c5f6.png)

- Create a repository named offers

```
docker tag offers bsairangapavan/offers:v1
```
```
docker push bsairangapavan/offers:v1
```
###### You can able to see like below 
![offer](https://user-images.githubusercontent.com/121741348/225618486-6a407c0e-ccb2-4e48-bdd5-fa82528d9f39.png)

- Create a repository named cart

```
docker tag cart bsairangapavan/cart:v1
```
```
docker push bsairangapavan/cart:v1
```
###### You can able to see like below 
![d](https://user-images.githubusercontent.com/121741348/225618932-536692e4-d116-4437-8632-e616f712bacc.png)

- Create a repository named wishlist 
```
docker tag cart bsairangapavan/wishlist:v1
```
```
docker push bsairangapavan/wishlist:v1
```
###### You can able to see like below 


![wis](https://user-images.githubusercontent.com/121741348/225619435-6b4cbb74-3ae6-4361-b5f6-cdc3a468078a.png)

