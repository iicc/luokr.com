luokr.com
=========

The initial version (V0.3) of LUOKR.COM was developed in July 2013 by Alvan. it is a Python-based server application using the Tornado framework at backend and the Bootstrap framework at frontend.
Now it just a simple blog(like wordpress) about technology and life.


Below is the main directory structure:

    res.luokr.com/      # global resources
    www.luokr.com/V0.3
    ---- app/
    -------- etc.py     # configuration file, please see doc/etc.py.sample for more details
    -------- svr.py     # to start the app, run `python svr.py`
    -------- url.py     # url mapping
    -------- ctrls/     # controllers, see Tornado's RequestHandler
    -------- datas/     # contains data files
    -------- model/     # contains model class files
    -------- views/     # contains templates
    ---- doc/           # documents
    ---- lib/           # library files
    ---- www/           # static files


The background landing address is `/login`, default username is `admin` and the password is `888888`.
You can change it after you logined.

Screenshots
-----------

posts:
![www.luokr.com.posts.png](http://res.luokr.com/img/20140530/www.luokr.com.posts.png)

about:
![www.luokr.com.about.png](http://res.luokr.com/img/20140216/www.luokr.com.about.png)

login:
![www.luokr.com.login.png](http://res.luokr.com/img/20140530/www.luokr.com.posts.png)

admin:
![www.luokr.com.admin.png](http://res.luokr.com/img/20140415/www.luokr.com.admin.png)

admin edit post:
![www.luokr.com.admin.post.update.png](http://res.luokr.com/img/20140415/www.luokr.com.admin.post.update.png)

