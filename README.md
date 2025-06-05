### 1. 가상환경 생성
python -m venv .venv

### 1-1. .gitignore에 추가하여 해당 Repository와 개발환경 맞추기???




### 2. 가상환경 활성화
source .venv/bin/activate
source aiBootCamp/bin/activate

#### 위치 확인
which python or which python3




### 3. 필요한 패키지 설치
pip install ipykernel

#### 안되면 
/home/user/aiBootCamp/env_aiBootCamp/bin/python -m pip install ipykernel -U --force-reinstall


### 4. 작업 끝났으면 비활성화
deactivate