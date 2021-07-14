https://github.com/MihaiValentin/lunr-languages

* [./lib/elasticlunr/tinyseg.js](https://github.com/MihaiValentin/lunr-languages/blob/master/tinyseg.js)
* [./lib/elasticlunr/lunr-languages/tinyseg.js](https://github.com/weixsong/lunr-languages/blob/master/tinyseg.js)

```sh
git clone --recursive https://github.com/ytyaru/lunr-languages
```

　submoduleだとGitHubPagesでエラーになってしまう。なので上記のようにクローンする。

```sh
git submodule add https://github.com/ytyaru/lunr-languages
```

　でもクローンしてpushすると以下のようなヒントが出てウザい。

```
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint: 
hint: 	git submodule add <url> docs/0/lib/elasticlunr/lunr-languages
hint: 
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint: 
hint: 	git rm --cached docs/0/lib/elasticlunr/lunr-languages
hint: 
hint: See "git help submodule" for more information.
```

