# go-docker
Playing with docker &amp; go

### How to do stuff with this

0. docker build ./
1. pwd
2. docker images (find image id)
3. docker run -it -p 8080:8080 -v [put your path here]/app:/go/src/github.com/user/myProject/app [image id]


For production:

0. docker build ./ --build-arg app_env=production
1. docker run -i -t -p 8080:8080 [image id]
