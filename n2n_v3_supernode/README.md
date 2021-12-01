# n2n v3 supernode docker  
[n2n github](https://hub.docker.com/r/chko/docker-pushrm)  
[dockerfile(github)](https://github.com/fnMrRice/Dockerfiles/tree/master/n2n_v3_supernode)  
[dockerhub](https://hub.docker.com/r/dorasan/n2n_v3_supernode)  
this container contains a script which can be located at /usr/sbin/start. The script checks wether /conf exists and copy a example conf file into /conf. You can modify the /conf/whatever.conf.example and rename it to /conf/whatever.conf to let the container work. So just mount /conf to anywhere on your host.  
n2n_v3_edge and n2n_v3_supernode has the same content. The only difference are the 'start' script.  