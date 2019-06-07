# ====================================================================== #
# Android SDK Docker Image
# ====================================================================== #

# Base image
# ---------------------------------------------------------------------- #
FROM thyrlian/android-sdk

RUN apt-get update
RUN apt-get install -y software-properties-common
RUN add-apt-repository ppa:jonathonf/python-3.7 -y
RUN apt-get update -y
RUN apt-get install -y build-essential python3.7 python3.7-dev python3-pip python3.7-venv
