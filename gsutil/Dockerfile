FROM python:3

# We don't want the whole SDK, because all we want to do is access object storage
RUN apt-get update & \
	apt get install python-pip & \
	pip install gsutil & \
	pip install -U gsutil

# Not setting an entry point. You can if you want.
