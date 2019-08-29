# Trading simulator

Python program to simulate a high returns trade with a specific portfolio. Uses QSTK's EventProfiler to identify patterns to buy and sell stocks. 

Install virtualenv to isolate dev environment

    pip install virtualenv

Create a Virtual env to get started(NOTE: you need to run this only the first time)

    cd TradingPlatform
    virtualenv env

Activate the environment and install the required packages

    source env/bin/activate
    cd TradingPlatform
    pip install requirements.txt

Run the simulator. Portfolio is set at 10,000$.

    python marketsim.py
