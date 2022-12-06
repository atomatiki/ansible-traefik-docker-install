# ansible-traefik-docker-install

Configure traefik as reverse proxy in a remote linux {ubuntu} machine with docker installed using ansible

## Usage 
Add the following public key as an authorized key in your ubuntu machine. 
> In /root/.ssh/authorized_keys

```shell
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCug/Bna0CaHSWASX8VHKnguIhO4ucGZCv6Y2oD0gJw3Pld2MZR3h3laziFBHqbRST4HGnsCY+eGyE+bZdS3OTTucJb6yq1TvLJjf/RYDa44B1ylHMiQNg7QM7XHDcje4aQ7f4Pk3uR3EUBWsZWIR3Zen9+GCLw+RerATHAfvcGJazVowg9jhhOfbRTWIN7ys8QNsYcpAUF8jcdweGgaH+IMoH5tK46ps378zDGiCvKnEfF2lgxG0qJV4YBLiHwc1D+MifTLSwLjNXMIcBgbhJZE5/QNcLq+V8I0ZUMIKByTZBYqPOMRLXnQnr5U7wMuWr6C7S8xcm0eAxaSmdTlf7P9DSRbnyLWU3pz5cpuwxumR6wA/a3QscVBnJATMWFREeHkkkx+hgsiTT/vBd/Z/URfokx9sPStsnqpPMX+HcD/xr/soeR/qXo8DYovR/yUEzI/pasD7dl1XcHp33btK8eKD6XNS3sRUw/cWM0LXQ3/iejtye9VPq49SHvNZUzxhE= jek@DESKTOP-FICH5D0
```

Dispatch this workflow while passing your host IP as an input.

> got to Actions > Configure Traefik > run workflow

Pass your remote IP and watch it run.
