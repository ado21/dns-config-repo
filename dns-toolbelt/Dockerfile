# Dummy dockerfile ... Do we even need this ? Security question. 
#If not we could directly use virtual machines provided by githubactions otherwise we will have to create 
#own docker image which we would use for our pipelines to deploy stuff. 
#Benefit of this is that it gives us full control in the container.
FROM python:3.9-slim
WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r requirements.txt
CMD ["echo", "Hello World!"]
