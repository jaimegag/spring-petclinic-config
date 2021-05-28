# Spring Petclinic Configuration Repository

ytt -f k8s --ignore-unknown-comments | kapp deploy -n petclinic -a petclinic -y -f -

> Note: as of release v0.32.0 of ytt , the --ignore-unknown-comments flag is no longer needed.
