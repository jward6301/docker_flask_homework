# docker_flask_homework
HHA 504 Week 10 Assignment

## Part One: Dockerizing a Single Flask Application
1. Create a folder named `Part1`
2. Create a flask application and name the file `app.py`
3. Create a `requirements.txt` file and add `flask` into it. 
4. Next, create a Docker file and name it  `Dockerfile`. Input the code found here: https://github.com/jward6301/docker_flask_homework/blob/main/Part1/Dockerfile 
5. Open the terminal and enter `docker build -t name of image .`Ensure that the `.` is at the end or it will not run properly. For example, mine was `docker build -t jess .`
6. Next, enter `docker run -p 5000:5000 name of image` into the terminal. You can change the ports to the desired ones.
7. You should now be able to open the website. Make sure that the web preview port setting is changed to the first port from the previous command.


## Part Two: Multi-Container Setup with Docker Compose
1. Create a folder named `Part2`
2. Inside this new folder create two new folders called `Flask1` and `Flask2`
3. In each Flask folder, create `app.py` files, `Dockerfile` and `requirements.html` files. 
4. In the Dockerfiles, copy the code from here: https://github.com/jward6301/docker_flask_homework/blob/main/Part2/flask2/Dockerfile
5. In each of the folders, create templates folders to host the `about.html` and `base.html` files. 
6. In the `Part2` folder, create a Docker Compose file named `docker-compose.yml`. You can copy the code from here: https://github.com/jward6301/docker_flask_homework/blob/main/docker-compose.yml
7. Open the cloud shell terminal and type in `docker-compose build`
8. Once that is completed, type in `docker-compose up`.
9. You should now be able to open them, ensure the ports are changed to the ones in the `docker-compose.yml` file. 

## Errors and Reflection
* I ran into two errors during this assignment. 
* First, when completing step 5 of Part One, I entered `docker build -t Jess .` and I receievd an error code due to it being capitalized.
* The second error I ran inot was during step 7 of Part 2. I accidentally capiltized the flask folders and recieved error codes that the Flask1 file could not be found. Once I fixed it, it worked correctly. 
* This assignment was reviewed in class with Professor Williams so no major errors or issues came up that blocked the completion of the assignment.

## Docker and Docker Compose
* 