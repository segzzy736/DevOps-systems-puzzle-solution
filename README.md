# systems-puzzle-solution
This is my solution to the devops systems puzzle .

Its still a work in progress and given more time I should be able
to complete it. However I was able to get myself well familiarized with
the basics of docker technology and how to set it up and manage

The three containers in the puzzle were set up and were all running 
as can be seen by running sudo docker ps. However because I'm in
a linux environment without GUI I was unable to navigate to localhost
and to view the flaskapp running in a browser

After a brief moment of searching for how to run web browsers like
firefox and chrome in such an environments to be able to view webapps like the 
flaskapp in this puzzle I see no reason why it cant be done if info in the docker-compose file and the Dockerfile are
well specified and provided all other parts of the code are bug free. I plan to dig deep er into the code in the next few days to try and resolve possible issues and get
the app working as it should I will continue to update the solution as
time goes on 


![3_containers_running](https://user-images.githubusercontent.com/47396197/56309321-ee655200-617b-11e9-9c8e-38826a7770ae.png)


The image above shows a screen grab of the three running containers. Given a little bit more time I should be able to resolve all
issues In the puzzle. However One possible issue with the Dockerfile in this repo is that the COPY statement which is the third statement from the bottom seem to only have one argurement when it seems it should have two. I plan to look more closely at this and scrutinize the entire code very well in thenext few days  

I have made more detailed note of the process that lead me thus far from installation of docker-compose and docker CE and all their dependencies as well as all the issues encountered.

