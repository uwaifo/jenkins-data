FROM jenkins/jenkins 

#cHANGE TO ROOT USER TO INSTALL ANSIBLE
USER root 

RUN apt update -y && \
    apt install ansible -y

#then switch back to jenkins user
USER jenkins