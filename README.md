# udacity-project

## Activate virtual env
```
python3 -m venv ~/.udacity-project
source ~/.udacity-project/bin/activate
```

## Install requirements, run lint and tests
```
make all
```

## Create ssh key
```
ssh-keygen -t rsa
```
then see the key in

```
cat ~/.ssh/id_rsa.pub
```

## Screenshots

![Passing pipeline](images/passing_pipeline.PNG)


[![Python application test with Github Actions](https://github.com/JanMichalec/udacity-project/actions/workflows/pythonapp.yml/badge.svg)](https://github.com/JanMichalec/udacity-project/actions/workflows/pythonapp.yml)

