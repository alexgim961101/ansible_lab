# 개요
Ansible의 다양한 기능을 공부 && 모듈화 && 테스트하기 위한 Repo

# 프로젝트 세팅
파이썬 가상환경 내에 필요한 패키지(ansible)을 설치해 두었다. 그렇기 때문에 가상환경만 잘 실행하면 된다.

## window
```
cd ansible_lab 
/ansible/bin/activate
```

## mac/linux
```
cd ansible_lab
source ansible/bin/activate
```
추가로 자시만의 가상환경을 만들고 싶다면 아래 명령어를 통해 만들 수 있다.
```
python -m venv <가상환경명>
pip install ansible
```