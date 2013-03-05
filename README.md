This is a sample on how to setup Flask on Dreamhost with Passenger WSGI 
Setup instructions here: [http://mattcarrier.com/flask-dreamhost-setup](http://mattcarrier.com/flask-dreamhost-setup)

## Detailed [setup instructions](http://mattcarrier.com/flask-dreamhost-setup)

### TL;DR; (Quick Setup)

* add a new subdomain on the dreamhost web panel
* cd myappname.domain.com
* git clone https://github.com/icecreammatt/flask-passenger.git .
* virtualenv .
* . bin/activate
* easy_install flask
* git submodule init
* git submodule update
* Replace `myappname.domain.com` in passenger_wsgi.py with your folder path.
* touch tmp/restart.txt
* DONE!
