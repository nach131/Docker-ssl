

/etc/hosts

127.0.0.1	home.enunpimpam.com
127.0.0.1	eric.enunpimpam.com


curl -I http://home.enunpimpam.com


registrar manualmente
docker exec -it letsencrypt /app/acme.sh --register-account -m nacho@enunpimpam.com --server https://acme-v02.api.letsencrypt.org/directory
