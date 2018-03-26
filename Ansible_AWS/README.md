Introduction:
=============

This is a full vagrant workspace that will execute the ansible provisioner.  To setup you environment to run this first execute in this directory:

	. setup_env

Then execute:

	vagrant up

You should get a message:

	'complete me'

Key Objectives:
===============

* Install lighttpd
* Configure a lighttpd named vhost via a jinja2 template
* S3 artifact deployment into virtual host document root
  /srv/app/
* Full automation ("vagrant up" to working site with no
  manual intervention)

Artifact deployment:
====================

The following access and secret keys have read only access
to the 'app-homework' bucket.

The artifact to deploy is 'work.tar.gz'.
