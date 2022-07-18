# Hardware sensitivity

This repository gathers measurements about x264 performance using different hardware platforms, taken using [Grid'5000](https://www.grid5000.fr/w/Grid5000:Home)

For each hardware platform, we measure 200 configurations of x264 on eight different input videos.
The docker image used to compute the measurements is public and available in [dockerhub](https://hub.docker.com/r/anonymicse2021/x264_inputs).

Each sub-directory of the data folder is related to one hardware platform. 
Each is composed of eight .csv files with the measurements (one per video, with the name of the related video) and a text file lscpu.txt with the return of the lscpu command-line. 

Hereafter the id linking of the hardware platforms (Grid'5000 Site - Cluster - Processor) :

1. Grenoble - dahu - Intel Xeon Gold 6130
2. Grenoble - troll - Intel Xeon Gold 5218
3. Grenoble - servan - AMD EPYC 7352

