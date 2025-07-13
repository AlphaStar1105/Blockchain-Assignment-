# Blockchain-Assignment-
Simple Blockchain Node
This is a basic blockchain project using Python (Flask) for the backend and HTML for the frontend. It lets you:
* Add transactions
* Mine new blocks
* Connect with other nodes
* Resolve chain conflicts with a consensus algorithm
Files
* app.py – Main Python file to run the server
* index.html – Web interface to interact with the blockchain
How to Run
1. Make sure you have Python 3 installed
2. Install Flask:
pip install flask
3. Run the app:
python app.py
You can open the app in your browser at: http://127.0.0.1:5000/
To test multiple nodes, open other terminals and run on different ports like:
PORT=5001 python app.py
PORT=5002 python app.py
What You Can Do
* Add Transaction – Send coins from one person to another
* Mine – Add a new block to the chain
* Register Node – Connect to other nodes
* Consensus – Sync with the longest valid chain
* View Chain – See all blocks and transactions
