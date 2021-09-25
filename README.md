# Pushing-image-to-DockerHub-Docker

Steps to create an image and push it to DockerHub-

```

1. Create a Docker image from the Dockerfile by creating a app.py file from the code in this repo.
$ mkdir pythonapp
$ cd pythonapp
$ vi app.py

2. Use the following command to create a requirements.txt file:
$ vi requirements.txt

3. Use the following command to create a Dockerfile:
$ vi Dockerfile

4. Build the Docker image from the newly created Dockerfile
$ sudo docker build -t python_image .

5. List all the running images to check the newly created image
$ sudo docker images

6. Push the image to a Docker Hub repository-
$ sudo docker login

7. Use the following command to tag the Docker image:
$ sudo docker tag python_image USERNAME/python_image:version1

8. Use the following command to push the Docker image to your Docker Hub repository:
$ sudo docker push USERNAME/python_image:version1

9. Go to your Docker Hub account and navigate to Repositories to see your recently pushed image

```

