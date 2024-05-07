Demo github action

How to build and push to docker registry

./gradlew bootBuildImage --imageName=demo-github-action:0.0.1-SNAPSHOT --publishImage -PregistryUsername=AWS -PregistryToken=$(aws ecr get-login-password --region us-east-2)
