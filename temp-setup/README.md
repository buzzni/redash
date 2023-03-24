# redash setup Dockerfiles (임시)

## 상황 설명

redash 세팅을 재활용하려 했는데 가능한 유일한 방법은 ECR에 있는 기존 이미지를 사용하는 것이었는데 이 이미지들은 원천 Dockerfile이 없어 개발이나 변경이 어려움.

그래서 해당 이미지들과 최대한 비슷한 Dockerfile을 만들려고 시도한 것이 이 디렉토리임.


## 기존 이미지 Dockerfile 대응 표

| 기존 이미지 | Dockerfile |
|---|---|
| 101047223697.dkr.ecr.ap-northeast-2.amazonaws.com/redash/analyser:11dev | server/11dev.Dockerfile |
| 101047223697.dkr.ecr.ap-northeast-2.amazonaws.com/redash/analyser:latest | app_dir/app_dir.Dockerfile |

