# docker-https-redirect

Pretty self-explanatory isn't it?
It's an HAProxy config that does nothing but redirecting http to https.
I build my own because I'm too paranoid to use somebody else's.

## Usage

```
$ docker run --detach --publish 80:80 kreisys/https-redirect
```
