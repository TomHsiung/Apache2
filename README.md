# Apache2
A powerful web service

# Contents
1) `000-default.force.ssl.conf` file is an example to force the Apache web server work in the manner of SSL.
2) `default-ssl.custom.port.conf` file is an example (SSL) to use a custom socket port for Apache web server.
3) `ports.conf` file is another place that define the ports (http and https) used by the Apache web server.
4) `apache2.conf.change.document.root` file is where to set the root specific directory of Apache web server, the place where you will store your website data.

# Test the configuration
You can test if your Apache web server is correctly configured by
`apachectl -t` or `apachectl configtest`
