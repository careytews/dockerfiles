FROM python:3

# Followed the standalone instructions athttps://cloud.google.com/storage/docs/gsutil_install#debian-and-ubuntu
RUN apt-get update & \
	apt get install python-pip & \
	pip install gsutil & \
	pip install -U gsutil

# Not setting an entry point. You can if you want.

# Note: You'll have to run `gsutil config` before you can use this. I you mount my home 
# directory at /root, to persist the config, as well as to access the files (duh).

