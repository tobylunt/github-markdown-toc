gh-md-toc
=========

Fork from [the
original](https://github.com/ekalinin/github-markdown-toc) that works
better for what I want. Fixes broken unordered lists, doesn't write
out temporary files with the `--insert` option, and tightens up
indentation spacing.  

This is a lean fork - no CI, dockerfile, or makefile.  

To use, clone it and symlink to somewhere on your path, e.g.:

``` shell
ln -s gh-md-toc /usr/local/bin/gh-md-toc
```

You can also just download the file directly instead.

``` shell
curl https://raw.githubusercontent.com/tobylunt/github-markdown-toc/master/gh-md-toc -o gh-md-toc
chmod a+x gh-md-toc
```

Feel free to add issues or PRs.
