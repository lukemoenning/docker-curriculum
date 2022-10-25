FROM python:3.8

# set a working directory for the app
WORKDIR /usr/src/app

# copy all the files to the container
copy . . 

# install dependencies 
RUn pip install --no-cache-dir -r requirements.txt

# define the port number the container should expose
EXPOSE 5000

# run command
CMD ["python", "./app.py"]
