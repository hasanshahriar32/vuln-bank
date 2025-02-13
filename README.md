# Vuln-Bank
- Clone this project
```bash
git clone https://github.com/Commando-X/vuln-bank
```

- Go into the cloned project directory
```bash
cd vuln-bank
```

- Run the following commands:

    Without Docker
```bash
pip install -r requirements.txt
flask run
```

With Docker
- Make sure you have Docker installed on your machine
```bash
sudo docker build -t vuln-bank .
sudo docker run -p 5000:5000 vuln-bank
```

- Visit URL displayed in the terminal  to start testing
