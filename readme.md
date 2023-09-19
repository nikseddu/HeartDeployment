
[![Continuus Integration](https://github.com/nikseddu/HeartDeployment/actions/workflows/github-docker-cicd.yaml/badge.svg)](https://github.com/nikseddu/HeartDeployment/actions/workflows/github-docker-cicd.yaml)


## Creating an MLOps Pipeline With GitHub and Docker Hub to serve the application predicting heart failure  

Dataset Link : (https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

## Steps to Run: 

```bash
docker pull docker pull nikseddu/heartv1:2023-09-19--25-03
docker run docker run --rm -d -p 5000:5000 IMAGE_ID

```

### Built With
* [![Python][Python]][Python-url]
* [![Docker][Docker]][Docker-url]
* [![Flask][Flask]][Flask-url]




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[Python]: https://img.shields.io/badge/python-brightgreen?logo=Python&labelColor=Yellow
[Docker]: https://img.shields.io/docker/automated/nikseddu/heartv1
[Flask]: https://img.shields.io/badge/:badgeContent?logo=flask


[Python-url]: https://python.org/
[Docker-url]: https://www.docker.com/
[Flask-url]: https://flask.palletsprojects.com/en/2.3.x/