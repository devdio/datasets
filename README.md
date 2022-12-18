#### 아나콘다 가상환경 추가 
- 코랩의 파이썬 버전과 맞추어서 추가
```
conda create -n (myml) python==3.8
```

- 가상환경 삭제
```
onda remove --name (myml) --all
```

#### 쥬피터 노트북 커널
- 커널 추가 
```
pip install ipykernel

python -m ipykernel install --user --name (myml) --display-name "myml"
```
  
- 커널 삭제 
```
jupyter kernelspec uninstall (myml)
```

#### 주피터 노트북에 익스텐션 설치하기 (nbextensions)
- 아나콘다 터미널에 아래의 코드를 입력하여 nbextension 설치

```
pip install jupyter_nbextensions_configurator jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextensions_configurator enable --user
```

- Table Of Contents 설정
쥬피터 노트북 실행후, 'Table Of Contents' 설정

#### 쥬피터 랩
- [쥬피터 랩 참조](https://heekangpark.github.io/etc/jupyter-lab)
- 설치 및 실행
```
pip install jupyterlab --upgrade

jupyter lab
```
- 폰트 설정, consolas, monaco, d2coding

