dockerfiles-centos
==================

feidao Base Image dockerfile from centos 

To build:

    # docker build --rm --tag <username or registry>/centos .
    For example
    # docker build --rm --tag docker.ifeidao.com:5000/centos .

To run:

    # docker run -id  --name centostest docker.ifeidao.com:5000/centos

To test:

    # docker logs centostest
    # docker exec centostest cat /etc/os-release
