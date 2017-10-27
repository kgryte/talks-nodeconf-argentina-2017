# Node.js Add-ons for High Performance Numeric Computing

> Talk for [NodeConf Argentina (2017)][nodeconf-argentina-2017].


## Abstract

Node.js add-ons allow native code to be run from the Node.js runtime. In this talk, I will discuss how to utilize native add-ons for high performance numeric computing and machine learning in Node.js applications. I will first provide an overview of add-ons and their associated toolchain. Next, I will walk through an example which involves compiling basic linear algebra subprograms (BLAS), a suite of libraries which are a core foundation of most modern numeric computing environments, as native add-ons. While Node.js add-ons are oriented toward C and C++, I will show how to extend compilation support to Fortran libraries in order to maximize computational performance. Throughout the talk, I will offer lessons learned and other insights gained while writing add-ons and demonstrate why Node.js is an excellent environment for high performance numeric computing and machine learning.


## Installation

```bash
$ git clone https://github.com/kgryte/talks-nodeconf-argentina-2017.git
```

and

```bash
$ npm install
```


## Usage

From the top-level directory,

```bash
$ python -m SimpleHTTPServer 9000
```

and, in your browser, navigate to

```
http://127.0.0.1:9000
```


---

## Copyright

Copyright &copy; 2017. Athan Reines.


[nodeconf-argentina-2017]: https://2017.nodeconf.com.ar/athan-reines.html
