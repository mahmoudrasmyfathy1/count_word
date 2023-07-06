# count_word


# prepare the prerequiste

# Launch the code 

python count_word.py --input count_word.py --output counts 

python count_word.py --input gs://wordcount_scrapy/* --output counts 


# To launch apache druid using docker compose 
cd /analytics/apache_druid/
docker-compose -f docker-compose.yaml up
https://druid.apache.org/docs/latest/tutorials/docker.html


# to stop postgresql instance 
sudo service postgresql stop
