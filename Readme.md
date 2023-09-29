## To Step up locally

- Install python and pip
- Install the below mentioned libraries using command `pip3 install <package-name>`
- Libraries names to install using above mentioned command

  - llama_index
  - python-dotenv
  - langchain
  - flask
  - flask_cors

- To run the project, open project directory in terminal and write `python3 qna.py`
- To test using postman import the below mentioned cURL in postman.
- cURL

```
curl --location 'http://127.0.0.1:5000/generate-answer' \
--header 'Content-Type: application/json' \
--data '{
    "question":"what is zero shot agent?",
    "urls":["https://python.langchain.com/docs/modules/agents/agent_types/","https://stackoverflow.com/questions/76906469/langchain-zero-shot-react-agent-uses-memory-or-not"]
}'
```
