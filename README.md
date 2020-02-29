# My First Deep Learning 

Happy Coding! Happy Inception 입니다.

비디오 설명 보러 가기 : < insert Youtube address here >

아래 설명에 따라 첫 Deep Learning model을 함께 만들어보세요. 


## Step 1 : Anaconda Download and Install

아래 Anaconda 페이지에서 
각자 운영체제에 맞는 최신 설치파일을 받아 설치해주세요. 

[Anaconda Download](https://www.anaconda.com/distribution/)


## Step 2 : Course Materials Download

현재 Git repository 에서 앞으로 사용하게 될 Anaconda 환경 파일, Jupyter Notebook 강의 파일, 
예제 코드들을 다운 받겠습니다. 

설치 된 Anaconda 에서 'Anaconda Prompt (Anaconda3)' 를 실행합니다. 
실행된 prompt에서 아래 명령어로 'git'을 설치합니다. 
```
conda install git
```

다운을 원하는 곳에서 아래 명령어를 실행해 my first deep learning repository를 다운받거나 
아래 'git clone' 으로 다운받으면 자동으로 폴더가 생성 됩니다. 
```
git clone https://github.com/happyinception/my_first_deep_learning.git
```
위의 'git clone' 방법이 잘 되지 않는 분은 
[여기](https://github.com/happyinception/my_first_deep_learning/archive/master.zip )를 통해 다운 받은 zip 파일을 
원하는 곳에 압축을 풀어주세요. 

repository가 생성된 폴더로 이동합시다. ( 각자 설치된 폴더로 이동 해주세요. 아래는 예시 입니다. )

```
cd my_first_deep_learning
```

## Step 3 : Conda Environment Setup

제가 미리 만들어놓은 Conda Environment를 설치하겠습니다. 
아래 명령어로 환경 구축을 한번 해놓으면, 이 강의를 위해 필요한 여러가지 Python 패키지, 라이브러리 들을 한번에 설치해 계속 사용이 가능합니다. 
환경 내용은 'environment.yml'을 참조 해주세요. 
```
conda env create
```
위 명령어로 Python 환경을 자동으로 구성하고, 
구성이 완료 되면 아래 명령어로 Python 환경을 시작 해보겠습니다. 
```
conda activate happy_inception
```


## Step 4 : Jupyter Notebook

Jupyter Notebook 이라는 아주 유용한 대화형 컴퓨팅 환경으로 
손쉽게 Deep Learning을 배워보겠습니다. 

주피터 실행

브라우저 실행

Step 1 에서 받은 Jupyter Notebook 파일을 찾아 실행합니다. 
