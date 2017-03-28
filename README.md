# tls role

Provisions the server with specified certificates and generates the dh file.
All system certificates are stored in the given "tls_cert_directory" directory.
You can also specify user certificates which are stored in user designated location and under custom permissions.


# Optional variables

* tls_cert_directory - where should certifactes be placed on the server - default /opt/certs
* tls_local_cert_directory - where certificates are stored locally
* tls_user_certificates - User certificates to cerate as non-root.