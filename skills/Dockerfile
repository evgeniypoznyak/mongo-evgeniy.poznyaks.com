FROM mongo
COPY *.json /
CMD mongoimport --host skills_data --db Skills --collection skills --type json --file /skills.json --jsonArray