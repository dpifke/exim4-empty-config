# exim4-empty-config

This is a Debian package which allows Exim to be installed without the default
configuration.

Install it first, then install your /etc/exim4/exim4.conf, then install Exim.
(Apt will try to start Exim after installing exim4-base, so exim4.conf must
exist ahead of time.)
