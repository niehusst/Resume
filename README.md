# Resumé

My online resumé. Made using a base template from ShareLaTeX (the original ShareLaTeX link broke, so here's the link to the author's github: [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV)).

### Development
As stated on the source template GitHub page, this assumes you have latex installed.

On Arch Linux:
```
sudo pacman -S texlive-core texlive-latexextra texlive-xetex
```

To compile:
```
make
```
It will then spit out a bunch a text and pause, giving you a question mark prompt. Type in "resume"
```
? resume
```
At this point, it will throw a ton of errors. But rest assured, the `resume.pdf` has been compiled fully.

