# Travel Planner

## Virtual Environment Setup

To create and activate a virtual environment, run:

```sh
python -m venv .venv
```

Activate the virtual environment:

```sh
.venv\Scripts\activate.bat
```

Install a package.
```sh
pip install -r requirements.txt
```

Run Each Agent Seperately on different command prompt to up individual server locally
```sh
python weather_agent.py
python hotel_agent.py
python activity_agent.py
```

Once all these server up without any error, Run client server to get the output
```sh
python main.py
```

Reference article
[Medium Article] (https://medium.com/data-science-collective/build-anything-with-a2a-agent-heres-how-part-1-dd25d31c1265)

