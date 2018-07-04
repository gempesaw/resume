# Resume

[My resume][res], along with its source tex file(s) and associated
rendered files.

[res]: http://gempesaw.github.io/resume/resume.pdf

One way to build a pdf is to clone this repo and:

```
$ docker run -v $(pwd):$(pwd) -w $(pwd) --entrypoint latex strm/latex --output-format=pdf resume.tex
```
