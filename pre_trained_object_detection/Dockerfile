FROM python:3.6
RUN mkdir /Demo
COPY ./ /Demo/
COPY ./requirements.txt /Demo
#RUN apt-get install python-pip 
#RUN pip install --upgrade pip3
RUN pip3 install -r /Demo/requirements.txt
CMD jupyter notebook --ip 0.0.0.0 --no-browser --port=3389 --allow-root
EXPOSE 3389/tcp
