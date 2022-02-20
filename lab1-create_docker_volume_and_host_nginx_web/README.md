# In this lab we follow the following steps:
# Note: You can also mount dir 

1. We will create sample `hello world` website using html 

    <p align="center">
    <img src="./imgs/img1.png"  alt="img1">
    </p>
    <br>
2. we will create volume with name `static-web`
    <p align="center">
    <img src="./imgs/img2.png"  alt="img2">
    </p>
    <br>
3. we will create nginx container and attach volume to `/usr/share/nginx/html` path
4. Here  we will copy file index.html to `/usr/share/nginx/html`
    <p align="center">
    <img src="./imgs/img5.png"  alt="img5">
    </p>
    <br>
5. Now we test if my hello world website work properly
    <p align="center">
    <img src="./imgs/img4.png"  alt="mg4">
    </p>
    <br>
6. Now I am having my website inside docker volume `static-web` not in container
7. Create new container with mapping diffrent port and same volume
    <p align="center">
    <img src="./imgs/img7.png"  alt="img7">
    </p>
    <br>
8. Test same website is accessible from new container also
<p align="center">
  <img src="./imgs/img6.png"  alt="img6">
</p>