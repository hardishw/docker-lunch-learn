FROM python:3.5

WORKDIR /usr/src/app

COPY . ./
RUN pip install --no-cache-dir -r requirements.txt
RUN python ./nltk_downloader.py

CMD [ "python", "./nlp.py" ]
