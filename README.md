# gitlab_by_docker-compose
GitLab By Docker Compose


## Getting Started


### Prerequisites

* Docker Compose


### Clone the Repository

Clone this repository using `git clone`

```
$ git clone https://github.com/Pick1a1username/gitlab_by_docker-compose.git
```

### Create Directories

Create Directories required for apps.

```
$ cd docker_registry_with_minio
$ mkdir -p ./gitlab/etc/gitlab ./gitlab/var/log/gitlab ./gitlab/var/opt/gitlab
```


### Run the Apps

Run the apps and browse to `http://localhost:8929`

```
$ docker-compose up -d
```


## References

https://docs.gitlab.com/omnibus/docker/


## Contributing

Any suggestions are welcome!


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
