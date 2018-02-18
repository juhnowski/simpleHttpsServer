Prepare
=======
openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes

Country Name (2 letter code) [AU]:RU
State or Province Name (full name) [Some-State]:NN
Locality Name (eg, city) []:Nizhniy Novgorod
Organization Name (eg, company) [Internet Widgits Pty Ltd]:Sberbank
Organizational Unit Name (eg, section) []:Minina
Common Name (e.g. server FQDN or YOUR name) []:test
Email Address []:juhnowski@gmail.com

Start server
============
python simple-https-server.py