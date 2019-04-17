# systems-puzzle-solution-seye
This is my solution to the devops systems puzzle .

Its still a work in progress and given more time I should be able
to complete it. However I was able to get myself well aquinted with
the basics of docker technology and how to install and manage them

The three containers in the puzzle were set up and was running 
as can be seen by running sudo docker ps. However because I'm in
a linux environment without GUI I was unable to navigate to
navigate to the localhost location to view the flaskapp running.

After a brief moment of searching for how to run web browsers like
firefox in such environments to be able to view webapps like the 
flaskapp in this puzzle I see no reason why t wont be possible to
do so if info in the docker-compose file and the Dockerfile are
well specified and provided all other portion of the app itself has to
bug. I plan to dig deep into the code to resolve possibly issues and get
the app working as it should however I though I should get my
solution in as soon as possible while I may continue to update it as
time goes on before the interview if I'm permitted to do so.

I hope to solve the puzzle by the end of the week.



![3_containers_running](https://user-images.githubusercontent.com/47396197/56309321-ee655200-617b-11e9-9c8e-38826a7770ae.png)


The image above shows a screen grab of the three running containers. Given a little bit more time I should be able to resolve all
issues In the puzzle. However One possible issue with the Dockerfile in this repo is that the COPY statement which is the third statement from the bottom seem to only have one argurement when it seems it should have two. I plan to look more closely at this and scrutinize the entire code very well.  

I have made more detailed note of the process that lead me thus far from installation of docker-compose and docker CE and all their dependencies as well as all the issues encountered.

