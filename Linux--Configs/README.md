
# Preparando Ambiente

Vou usar WSL -> Linux no Windows 
Para fazer o Pipeline

---

Baixar WSL -> Ubuntu V- 24.04.5 



```bash
sudo apt upgrade -y

python3 -V

sudo apt install python3-pip -y

sudo apt install python3-venv -y

```

```bash

mkdir pipeline-python-mongo-mysql

cd pipeline-python-mongo-mysql

python3 -m venv venv

source venv/bin/activate
```

```bash
pip install requests==2.31.0

pip install pymongo==4.4.0

pip install pandas==2.0.3

pip install mysql-connector-python==8.0.33

```












