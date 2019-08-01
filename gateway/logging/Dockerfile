FROM mongo
COPY logging.json /
CMD mongoimport --host logging --db Logging --collection log --type json --file /logging.json --jsonArray
