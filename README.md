# SSL Certificate Generation

This repository contains an example on how you can use GitHub workflow to generate Certificate Signing Requests (CSR) for your domain. You can use this, when you are unable to use Let's Encrypt but still want proper SSL certificate.

As we don't want someone to use our certificate and private key, we will encrypt them using [GPG](https://gnupg.org/).
