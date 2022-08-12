# 実行方法

- ビルド

docker image build -t gitops-go .

- コンテナ実行

docker container run -d -p 8080:8080 gitops-go

- dockerhub の push

docker tag gitops-go docdocsugasuga/gitops-go
docker push docdocsugasuga/gitops-go