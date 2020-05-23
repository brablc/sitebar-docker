= Run

git clone git@github.com:brablc/sitebar.git php/
cd docker
docker-compose up

Access as http://sitebar.test/

= XDebug Guide - see https://devilbox.readthedocs.io/en/latest/howto/xdebug/host-address-alias-an-mac.html#howto-host-address-alias-on-mac

Project is ready for Mac, just add this:

sudo ifconfig lo0 alias 10.254.254.254
