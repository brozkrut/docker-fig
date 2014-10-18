Fig 1.0.0 in docker container!
==============================

Fig 1.0.0 orchestration running in docker container - useful for boot2docker on Windows.

Read more about Fig:
http://fig.sh

How to run?
-----------

Default `docker run brozkrut/fig` shows fig help information.

To run fig please specify docker socket and fig.yml directory:
```
docker run -v $(pwd):/config -v /var/run/docker.sock:/var/run/docker.sock -it brozkrut/fig --help
```
