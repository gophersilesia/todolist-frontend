# Polymer Todo list

This project is based on the official version of the Polymer TodoMVC, slightly modified to use a REST endpoint.

### Get Started

You will need to have `npm` and therefore `nodejs` installed locally.  
See how to install it with [OSX](http://coolestguidesontheplanet.com/installing-node-js-osx-10-9-mavericks/), [Linux](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-an-ubuntu-14-04-server) and [Windows](http://blog.teamtreehouse.com/install-node-js-npm-windows).

*1.* Install the project dependencies with `bower`.

    $ bower install

*2.* If you have `python` installed locally:

    $ python -m SimpleHTTPServer
    # Head to http://localhost:8000/

If you don't, then `polyserve` will prove useful.

    $ npm install polyserve -g
    $ polyserve -p 8000
    # Head to http://localhost:8000/components/todomvc-polymer/