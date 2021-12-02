# Intro 

Repository contains draft of the Common Lisp standard a.k.a. dpANSR3 .

It is slightly different from the other popular variant of this standard - dpANS3 and [according to one of the
authors ](https://groups.google.com/g/comp.lang.lisp/c/Qye01Rdjl6E/m/EXnPuv4nA7kJ) this standard was accepted as a draft. The only thing that is different from the dpANS3 is `chap-0*` and it mainly affects list of contributors to this standard. 

# Read pdf

[result.pdf](./result.pdf) 1360 pages 

# Buiding

To build [result.pdf](./result.pdf) from the tex files you need `pdftex` and `pdfunite` (to concat chapters together).

```
make
```
