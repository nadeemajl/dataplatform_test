#First dockerfile for the liveproject "Data platform for real time anamoly detection"
#Dev environment: Windows 10 Pro, docker desktop 4
#Commands used
#docker build -f Dockerfile . -t nadeem/lp-jupyter
#docker run -p 9000:9000 nadeem/lp-jupyter
#docker ps 
#docker stop <container_id>

FROM python:3.7-slim

RUN mkdir src
WORKDIR /src
RUN pip install jupyter
CMD ["jupyter", "notebook", "--no-browser", "--allow-root","--ip=0.0.0.0","--port=9000"]