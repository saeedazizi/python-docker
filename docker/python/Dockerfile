FROM python:3.6

WORKDIR /var/www

COPY ./requirements.txt /var/www

RUN pip install -r requirements.txt --no-cache-dir

CMD jupyter notebook --ip 0.0.0.0 --no-browser --allow-root
