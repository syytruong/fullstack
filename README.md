Restaurant menu data-driven web app
=============

Needed:
  1. Virtual Machine: https://www.virtualbox.org/
  2. Vagrant: https://www.vagrantup.com/
  3. Flask: http://flask.pocoo.org/
  4. SQLAchemy: https://www.sqlalchemy.org/

===============
1. Navigate to <directory> after you clone - Run vagrant up -> vagrant ssh
2. In the VM prompt shell, direct to vagant folder by cd /vagrant
3. python database_setup.py to initialize the database
   python lotsofmenus.py to add items into the database
   python finalproject.py to run the web app
   Your webapp will be at port 5000 - localhost:5000

