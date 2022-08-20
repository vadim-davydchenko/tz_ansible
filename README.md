Role и playbook for the delivery software:
- create network *docker* with name *example*
- deploy *grafana* in container
- deploy *nginx* in a container with the config and directory *conf.d*
- config in *conf.d/* - listens on the 80 port and `proxy_pass` on 3000 port on container *grafana* by the name of the container.
