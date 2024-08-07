FROM ubuntu
WORKDIR /app
VOLUME [ "/app" ]

RUN echo "Initiate Sucessful"

#EXECUTE
RUN apt-get update && apt-get upgrade --yes
RUN apt-get update && \
    apt-get install nano --yes && \
    apt-get install git --yes && \
    apt-get install nmap --yes && \
    apt-get install gobuster --yes && \
    apt-get install hydra --yes && \
    apt-get install john --yes && \
    apt-get install dnsenum --yes

#GIT
RUN git clone https://github.com/projectdiscovery/subfinder.git .
RUN git clone https://github.com/aboul3la/Sublist3r.git .
RUN git clone https://github.com/projectdiscovery/httpx.git .
