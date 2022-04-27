# DockerWebAppDemo

## Demo of docker containerization of a web app with https

Following steps are required setup:-
1. Clone repo.
2. Install Docker/WSL.
3. Install SSL certificate using command : `dotnet dev-certs https -ep $env:USERPROFILE\.aspnet\https\SampleWebApp.pfx -p pa55w0rd!` .  This would install your certicate at your system.
4. Run this command:  `docker-compose up --build `. This would build and run your docker container using docker-compose.yaml.
5. you can access the app in browser using url: `https://localhost:8081/`
