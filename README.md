
## Commands
```
dotnet new webapi -o DockerNetExample
dotnet new sln
dotnet sln add DockerNetExample...
ni Dockerfile
docker build . -t dotnetexample
docker run --name dotnetexample -p 8081:80 -d dotnetexample
docker ps
heroku login
heroku container:login
docker build . -t dockernetexample
heroku container:push web -a dockernetexample
heroku container:release web -a dockernetexample
```