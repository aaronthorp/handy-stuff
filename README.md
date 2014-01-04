handy-stuff
===========

Handy scripts and stuff that I use regularly

* `gitup <origin>` - Add all files, remove any deleted, get commit desc and push
* `mrtdep` - Deploy Meteor.js project to `/var/node/<foldername>`. Required `nginx.conf` and `init.conf` files in project folder to work.

* `nginx.conf` Sample - [nginx.conf](https://github.com/aaronthorp/handy-stuff/wiki/nginx.conf-for-Meteor.js-Project)
* `init.conf` Sample - [init.conf](https://github.com/aaronthorp/handy-stuff/wiki/init.conf-for-Meteor.js-Project)
 
place them in `~/bin`

add a following line to your `~/.bash_profile` file.

```
PATH=$PATH:$HOME/bin
```
