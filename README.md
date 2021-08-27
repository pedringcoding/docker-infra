# Docker as infrastructure [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

## :clipboard: Objetives

Create your own DEV+CI infrastructure in a dockerized context (Git, Jenkins, SonarQube)

## :cloud: Getting Started

Follow along this notes. You will need to have at least [Docker](https://www.docker.com/) installed.

You can use some package management tool for windows. E.g. [Chocolatey](https://chocolatey.org/install)

*	[Docker for windows](https://www.docker.com/) - Virtualize tool

```
choco install docker-desktop
```

## :computer: Commands to execute

To execute virtualize context:

```
docker-compose config
docker-compose up -d
```

View the generated administrator password to log in the first time (Jenkins) to complete installation

```
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```

And access in [Git](http://localhost:18082/) and [Jenkins](http://localhost:18080/) 

## :octocat: Can you support me?

I will continue to do things and expose notes, but existing many ways to support what I do:
* Pull requests are welcome a :dizzy:
* Don't forget to give this Repository a :star2:
* <a href="https://www.buymeacoffee.com/pedringcoding" title="Donate to this content using BuyMeACoffee">Buy me a :coffee:</a>
