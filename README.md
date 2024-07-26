Backend
Setup Instructions
Create a virtual environment and activate it:

python3 -m venv venv
source venv/bin/activate

Install the required packages:

pip install flask pymongo kafka-python

Set up MongoDB:

You can use a local MongoDB instance or MongoDB Atlas.
Create a database named flightDB and collections flights and users.
Set up Kafka:

You can use a cloud service like Confluent Cloud or set up a local Kafka instance.
Create a topic named flight_updates.
