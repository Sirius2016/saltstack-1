saltstack
=========

Install
-------
    git clone https://github.com/oscm/saltstack.git
    ln -s saltstack/salt /srv/salt
    ln -s saltstack/pillar /srv/pillar

Demo
----
    salt '*' state.sls httpd
