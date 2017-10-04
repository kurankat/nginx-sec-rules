# Nginx security rules

Some rules to increase security for Nginx web servers

You can call them from your virtual host file:

```
include snippets/6G.conf;

server {
  ...
  include snippets/secrules.conf;
```
