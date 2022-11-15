# Dev Notes

## Ops

```
nginx -t          # test config syntax
nginx -s reload   # reload config 
nginx -V          # get config info
```

## Ubuntu Ops

```
man service       # service - run a System V init script
sudo service nginx {start|stop|restart|reload|force-reload|status|configtest|rotate|upgrade}
```

## MacOS Ops

```
brew services info nginx
```