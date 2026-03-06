# GCC

## GCC 환경설정 활성화
```shell
conda env create -f env.yml
conda activate GCC

```

## GCC 환경 설정 패키지 설치 후 

```shell
# 송신 시
conda env export > env.yml
git add env.yml
git commit -m "add 모듈"
git push

# 수신 시 
conda env update -f environment.yml 
```


## rapi 환경 설정 패키지 업데이트
```shell
pip freeze > requirements_rpi.txt
```


## rapi 환경 설정 패키지 설치
```shell
pip install -r requirements_rpi.txt
```