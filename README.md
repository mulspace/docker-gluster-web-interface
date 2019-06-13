Fork this repo only to build a latest docker image for dockerhub.

# docker-gluster-web-interface

[gluster-web-interface](https://github.com/oss2016summer/gluster-web-interface) is Web UI to manage GlusterFS.

## Pull the image to local

```bash
docker pull mulspace/gluster-web-interface
```

## Run the instance to expose port 3000

```bash
docker run -it -p 3000:3000 mulspace/gluster-web-interface
```

Please open http://&lt;ip address&gt;:3000/ by browser to access gluster-web-interface.
