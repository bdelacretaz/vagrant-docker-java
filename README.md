vagrant-docker-java
===================

This is a Vagrant box with Java 7 and Docker installed.

Note that the puppet manifest accepts Oracle's java license automatically, if you're not happy
with this do not use this box.

Inspired by https://bitbucket.org/durdn/stash-vagrant-install

To run this, start the Vagrant box with "vagrant up" and once it's up do:

    vagrant ssh
    sudo docker run -i -t ubuntu ls /

Which should show the / folder of the Docker ubuntu image, demonstrating that
Docker works in this Vagrant VM.
