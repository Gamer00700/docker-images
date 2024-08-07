FROM ubuntu
WORKDIR /app
VOLUME [ "/app" ]

RUN echo "Initiate Sucessful"

#EXECUTE
RUN apt-get update && apt-get upgrade --yes
RUN apt-get update && apt-get install nano --yes
RUN apt-get update && apt-get install git --yes
RUN apt-get update && apt-get install nmap --yes
RUN apt-get update && apt-get install gobuster --yes
RUN apt-get update && apt-get install hydra --yes
RUN apt-get update && apt-get install john --yes
RUN apt-get update && apt-get install dnsenum --yes

#GIT
RUN git clone https://github.com/projectdiscovery/subfinder.git 
RUN git clone https://github.com/aboul3la/Sublist3r.git
RUN git clone https://github.com/projectdiscovery/httpx.git
