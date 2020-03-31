docker --version

## List containers
$ docker container ls [OPTIONS]
* --all , -a		Show all containers (default shows just running)
* --filter , -f		Filter output based on conditions provided
* --format		Pretty-print containers using a Go template
* --last , -n	-1	Show n last created containers (includes all states)
* --latest , -l		Show the latest created container (includes all states)
* --no-trunc		Don’t truncate output
* --quiet , -q		Only display numeric IDs
* --size , -s		Display total file sizes

## INSTALL MYSQL
1-- Pull image
* $ docker pull mysql

2-- Start mysql server instance
$ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag

* some-mysql is the name you want to assign to your container
* my-secret-pw is the password to be set for the MySQL root user
* tag is the tag specifying the MySQL version you want.
