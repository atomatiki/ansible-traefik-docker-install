# ansible-traefik-docker-install

Configure traefik as reverse proxy in a remote linux {ubuntu} machine with docker installed using ansible

## Usage 
Add the following public key as an authorized key in your ubuntu machine. 
> In /root/.ssh/authorized_keys

```shell
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCjjoSZoOLI48O9sJCKPUbkjQfllz4zpJrdzkBDtHMfC54O04JbEb0NZi43ROC3kLOzKHGyqsU5XAR5xgOM+F02MFUJ3o42HNJUF971212e85C6ZIOSIguhfwyf5MC7G1lgdEPHv1XBpd0b0M9LY4q3i4Zndu56v2m4bl4DDcADtDWctnJJLutkZn+vooISEDx4YCqEMGO8PMvmy4QzCgsExoRtm1XO0q54XrT7PoWOuHaD7qwrYIDiMYTWtTuPHtM4NWZ4+w3Ff5AftdXDgdLleN9IFmk+nja7C0OXAW3OkTDvA/7O4o3nHTdL2Bj5aBJKihPFYhnsCbzRCbM2XI8N1f4OlaS8I6Q4S8CCtKhw1SM+liD4O/383Y1QtGiFJ512NinKB5iHjk57/upp510m1GR23gpYCO/bOfnKrfPBWJjB8zITpiHO1p0GB2SSrkZzzFeg295Uy44zoxvikN6uhzWSERIw3CfSpJzm2hPNZaL2g0VArBdGks6ZTPDDfd0= jek@DESKTOP-FICH5D0
```

Dispatch this workflow while passing your host IP as an input.

> got to Actions > Configure Traefik > run workflow

Pass your remote IP and watch it run.
