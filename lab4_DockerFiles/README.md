# Docker File Writing use cases:
1. Docker layered architecture working diagram

<br>
<p align="center">
<img src="./imgs/img1.png"  alt="img5">
</p>
<br>

2.  `Dockerfile.create_file_in_ubuntu_container` is dockerfile which deployes <br>
   ubuntu image in docker container. And create text file `abc` in it 
   
<br>
<p align="center">
<img src="./imgs/img2.png"  alt="img5">
</p>
<br>


3. `Dockerfile.env_var_and_labels` is dockerfile which tell us to how to create env variables <br>
   and labels in dockerfile. labels are set when extra information we provide in docker containe <br>
   like contact information i.e email which helps developer to reach out to docker file creater <br>
   if there is any issue with it.
<br>
<p align="center">
<img src="./imgs/img3.png"  alt="img5">
</p>
<br>



<p align="center">
<img src="./imgs/img4.png"  alt="img5">
</p>
<br>


<p align="center">
<img src="./imgs/img5.png"  alt="img5">
</p>
<br>


4. The default docker user is root if you want to create a new user and when access to docker container provide  <br>
   default shell for new created user then you can do it with file `Dockerfile.create_user_and_login_as_new_created_user`
<br>

<br>
<p align="center">
<img src="./imgs/img6.png"  alt="img5">
</p>
<br>


5. When you login to docker container the default dir you login with is `/` dir. But any case you want <br>
to change dir you   need to make changes as like shown in `Dockerfile.default_login_to_working_dir`.
<br>
<p align="center">
<img src="./imgs/img7.png"  alt="img5">
</p>
<br>


6. `Dockerfile.copy_data_inside_container` this docker file helps to copy data inside docker container. <br>
   from local machine 
<br>
<p align="center">
<img src="./imgs/img8.png"  alt="img5">
</p>
<br>


7. `Dockerfile.add_file_zip_add_with_extract` this file helps to add a copy zip file inside docker container. <br>
    copy and add commands both are doing same work. But when you have a zip file to copy, better you use add <br>
    because it adds file with default unzipped format.

<br>
<p align="center">
<img src="./imgs/img9.png"  alt="img5">
</p>
<br>


<br>
<p align="center">
<img src="./imgs/img10.png"  alt="img5">
</p>
<br>


<br>
<p align="center">
<img src="./imgs/img11.png"  alt="img5">
</p>
<br>


8. `Dockerfile.deploy_static_website_using_nginx` helps to deploy_static_website using nginx and docker.


<br>
<p align="center">
<img src="./imgs/img13.png"  alt="img5">
</p>
<br>