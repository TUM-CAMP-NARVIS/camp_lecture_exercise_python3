# camp_lecture_exercise_python3
CAMP Lecture Exercise Docker Images

This repository contains docker images for the TUM CAMP Lectures.

Usage (Wintersemester 2017)
---------------------------

You can download and run this image using the following commands:

    docker pull ulricheck/tum_camp_lecture_exercise_python3_ws2017
    docker run -i -t ulricheck/tum_camp_lecture_exercise_python3_ws2017 /bin/bash

Alternatively, you can start a Jupyter Notebook server and interact with Anaconda via your browser:

    docker run -i -t -p 8888:8888 -v <path-to-your-local-notebooks-directory>:/opt/notebooks --name camp_ws17 ulricheck/tum_camp_lecture_exercise_python3_ws2017

You can then view the Jupyter Notebook by opening `http://localhost:8888` in your browser, or `http://<DOCKER-MACHINE-IP>:8888` if you are using a Docker Machine VM.
