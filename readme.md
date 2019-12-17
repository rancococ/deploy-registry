
registry v2

docker run --entrypoint htpasswd harbor.cdjdgm.com/library/registry:2.7.1 -Bbn docker Docker12345  > ./volume/registry/conf/auth/htpasswd
