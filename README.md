# a playbook to setup my livecoding environment

This will install a set of packages, add the remote user (in this case `mauro`, which is who i am), then will reboot the system and pull a docker container of `tida1vm` (which is a container for TidalCycles).  
It's still missing some configurations for this to be 100% perfect and accurate, but it's a start :-)  
  
Software installed from repositories:  

 * jackd2
 * jack-rack
 * jackeq
 * pulseaudio-module-jack
 * qjackctl
 * qjackrcd
 * amsynth
 * qsynth
 * fluidsynth
 * fluid-soundfont-gm
 * docker
 * python-docker
 * linux-image-lowlatency


## How to use?

```bash
$ ansible-playbook setup.yml -i HOSTS --ask-sudo-pass
```

