# Docker Maltrail

Dockerized maltrail - Malicious traffic detection system

Quick Start
---

`docker run -d -p 8338:8338 --net=host --privileged -v /var/log/maltrail/:/var/log/maltrail/ -v $PWD/maltrail.conf:/root/maltrail/maltrail.conf jcherqui/docker-maltrail`

Point your browser to `http://127.0.0.1:8338`

License
---

MIT

Free Software, Hell Yeah !
