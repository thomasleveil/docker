% DOCKER(1) Docker User Manuals
% Docker Community
% JUNE 2014
# NAME
docker-wait - Block until a container stops, then print its exit code.

# SYNOPSIS
**docker wait**
CONTAINER [CONTAINER...]

# DESCRIPTION

Block until a container stops, then print its exit code.

# OPTIONS
There are no available options.

# EXAMPLES

    $ sudo docker run -d fedora sleep 99
    079b83f558a2bc52ecad6b2a5de13622d584e6bb1aea058c11b36511e85e7622
    $ sudo docker wait 079b83f558a2bc
    0

# HISTORY
April 2014, Originally compiled by William Henry (whenry at redhat dot com)
<<<<<<< HEAD
based on docker.io source material and internal work.
June 2014, updated by Sven Dowideit <SvenDowideit@home.org.au>
=======
based on docker.com source material and internal work.

>>>>>>> 834ef8a... I'm going to wish I didn't do this