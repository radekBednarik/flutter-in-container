FROM docker.io/cirrusci/flutter:stable

RUN sudo apt-get update \
    && sudo apt-get install -y gnupg2 \
    && sudo wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb \
    && sudo apt-get install -y ./google-chrome-stable_current_amd64.deb