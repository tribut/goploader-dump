# dump

Tiny shell client for [goploader](https://github.com/Depado/goploader).

![Usage](https://i.imgur.com/l3oaDas.gif)

Just pipe output to `dump` or give it a file or directory to upload.
Directories will be automatically `zip`'d.

    ls -l | dump
    dump mytest.txt
    dump some-directory
