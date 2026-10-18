# Setup

#### 1. Clone repo
``` Bash
git clone https://github.com/Herehs/demo-exam.git
```

#### 2. Create and activate virtual environment

With standart Python instalation:
 ``` Bash
python -m venv ./.venv
source .venv/bin/activate
 ```

 If using `uv`:
 ``` Bash
uv venv --python=3.14 .venv
source .venv/bin/activate
 ```


#### 3. Install all required dependencies
 ``` Bash
pip install -U -r ./requirements.txt
 ```
