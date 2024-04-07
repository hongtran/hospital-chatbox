# hospital-chatbox
Hospital agent chatbot

# How to install local
## Create Grahp database using Neo4j AuraDB
https://neo4j.com/cloud/aura-free/

## Create env file
OPENAI_API_KEY=xxxx
NEO4J_URI=
NEO4J_USERNAME=neo4j
NEO4J_PASSWORD=
AURA_INSTANCEID=
AURA_INSTANCENAME=

HOSPITALS_CSV_PATH=https://raw.githubusercontent.com/hfhoffman1144/langchain_neo4j_rag_app/main/data/hospitals.csv
PAYERS_CSV_PATH=https://raw.githubusercontent.com/hfhoffman1144/langchain_neo4j_rag_app/main/data/payers.csv
PHYSICIANS_CSV_PATH=https://raw.githubusercontent.com/hfhoffman1144/langchain_neo4j_rag_app/main/data/physicians.csv
PATIENTS_CSV_PATH=https://raw.githubusercontent.com/hfhoffman1144/langchain_neo4j_rag_app/main/data/patients.csv
VISITS_CSV_PATH=https://raw.githubusercontent.com/hfhoffman1144/langchain_neo4j_rag_app/main/data/visits.csv
REVIEWS_CSV_PATH=https://raw.githubusercontent.com/hfhoffman1144/langchain_neo4j_rag_app/main/data/reviews.csv

HOSPITAL_AGENT_MODEL=gpt-3.5-turbo-1106
HOSPITAL_CYPHER_MODEL=gpt-3.5-turbo-1106
HOSPITAL_QA_MODEL=gpt-3.5-turbo-0125
CHATBOT_URL=http://localhost:8900/hospital-rag-agent

## Run docker-compse command
 docker-compose up --build
