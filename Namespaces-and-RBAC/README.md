This is a CLI command for the RBAC tutorial part in the KCNA video

openssl x509 -req -in developer.csr -CA /var/snap/microk8s/current/certs/ca.crt -CAkey /var/snap/microk8s/current/certs/ca.key -CAcreateserial -out developer.crt -days 500

