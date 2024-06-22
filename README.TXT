MAIN COURSE
https://github.com/DataTalksClub/llm-zoomcamp/tree/main

Specific course:
build a simple Q&A system
Video: https://www.youtube.com/watch?v=q-p36Ak6YI8
Code: https://github.com/alexeygrigorev/llm-rag-workshop

Package:
pipenv install tqdm notebook==7.1.2 openai elasticsearch
or
pip install tqdm notebook==7.1.2 openai elasticsearch

env:
sudo apt update
sudo apt install direnv
direnv hook bash >> ~/.bashrc
direnv allow

chatGPT:
https://platform.openai.com/docs/quickstart

Docker:
docker run -it \
    --rm \
    --name elasticsearch \
    -p 9200:9200 \
    -p 9300:9300 \
    -e "discovery.type=single-node" \
    -e "xpack.security.enabled=false" \
    docker.elastic.co/elasticsearch/elasticsearch:8.4.3