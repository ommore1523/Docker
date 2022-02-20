# Follow the following steps:

1. Create one vm which will use as docker registry. Install docker on it.
   By default docker registery runs on `5000` port. Follow as shown below.
<p align="center">
<img src="./imgs/img5.png"  alt="img5">
</p>
<br>

2. Check with vm ip and port 5000 if it shows output as below.

<p align="center">
<img src="./imgs/img1.png"  alt="img5">
</p>
<br>

3. Now your setup done for registry
   now get one sample image like nginx at tag it with ip and port of new private registry.
<p align="center">
<img src="./imgs/img6.png"  alt="img5">
</p>
<br>

4. Now try to push the image to your repository. But you will see here the error like below.
   It clearly says that the repository should be https
<p align="center">
<img src="./imgs/img7.png"  alt="img5">
</p>
<br>

5. To make it work. create one daemon.json file and write `{"insecure_registries":"<your_ip>:<port(5000)>"}`
   as shown below.This will basically skip the https.
<p align="center">
<img src="./imgs/img8.png"  alt="img5">
</p>
<br>


<p align="center">
<img src="./imgs/img2.png"  alt="img5">
</p>
<br>

6. Now push the tagged image to private repository. it will work fine.

<p align="center">
<img src="./imgs/img9.png"  alt="img5">
</p>
<br>

7. Now hit same ip and port to check if the image is present in repository
<p align="center">
<img src="./imgs/img3.png"  alt="img5">
</p>
<br>

8. You are good to go.