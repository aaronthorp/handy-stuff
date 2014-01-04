Handy Scripts and Tools
=======================

### Details

Handy scripts and stuff that I use regularly for git and Meteor development.

Common tasks for git, Meteor, nginx, apache, Node.js, upstart and other tools.

Commonly used on Ubunto Linux servers.

### Tools

* `gitup <origin>` - Add all files, remove any deleted, get commit desc and push
* `mrtdep` - Deploy Meteor.js project to `/var/node/<foldername>`. Required `nginx.conf` and `init.conf` files in project folder to work.

### Sample Scripts

* `nginx.conf` Sample - [nginx.conf](https://github.com/aaronthorp/handy-stuff/wiki/nginx.conf-for-Meteor.js-Project)
* `init.conf` Sample - [init.conf](https://github.com/aaronthorp/handy-stuff/wiki/init.conf-for-Meteor.js-Project)

### Instructions
 
place them in `~/bin`

add a following line to your `~/.bash_profile` file.

```
PATH=$PATH:$HOME/bin
```
