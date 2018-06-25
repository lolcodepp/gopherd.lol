gopherd.lol
=========

A minimal gopher server written in [LOLCODE](https://khuxkm.tilde.team/lcpp).  Because programming languages.

Usage
-----

Check out and build [lci](https://git.tilde.team/lcpp/lci/).

    $ ./lci gopherd.lol
    point your favorite gopher client to gopher://127.0.0.1:13337/lol.html
    ????
    profit?


Example
-------

Here we're using Netcat, but gopher clients work just fine as well.

    $ ./lci gopherd.lol &
    $ echo "/" | nc 127.0.0.1 13337
    CMD IZ /
    
    FIEL IZ gophermap
    FIEL FOUND!
    
    REPLY IZ iThis is a test	(fake)	localhost	
    0Text file test	/test	localhost	
    
    
    iThis is a test	(fake)	localhost	
    0Text file test	/test	localhost	
