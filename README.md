# Resumé

My online resumé. Made using a base template from ShareLaTeX (the original ShareLaTeX link broke, so here's the link to the author's github: [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV)).

### Development

As stated on the source template GitHub page, this assumes you have latex installed.

Necessary packages to install on Arch Linux:
```
sudo pacman -S texlive-basic texlive-latexextra texlive-xetex
```

To compile:
```
make
```
Or, due to this latex template being old as fuck now and not working well/at all
when compiled by newer latex versions, use an ancient docker image of latex:
```
docker run --rm --user $(id -u):$(id -g) -i -w "/doc" -v "$PWD":/doc thomasweise/texlive make
```
It will then spit out a bunch of errors, but the `LiamNiehusStaab_resume.pdf` has been compiled fully.

