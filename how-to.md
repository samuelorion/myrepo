## How to ... 

#### add an image / gif to a .md 

- make a recording ?how
- convert to gif ?how
- host it somehwere (here, it's in the repo, loose) 
- write the following

```
![a gif / an image](image location)
```
Note , if the file is is the root, you can just give the file name. 

```

![a gif](my_gif.gif)
```

![a gif in the readme](my_gif.gif)

But, if it's somehwere else, this won't work.  
![an image](dotchart-1.png)  

You need to get the "https:address", such as : 
```
![an image](https://github.com/samuelorion/myrepo/blob/master/Untitled_files/figure-gfm/dotchart-1.png)
```
![an image](https://github.com/samuelorion/myrepo/blob/master/Untitled_files/figure-gfm/dotchart-1.png)

#### Change the image dimensions ... using html 

Copy <img> in browser DevTools. Replace ![](url) to <img>. Add width(and height) attr.  

```
<img src="my_gif.gif" data-canonical-src="my_gif.gif" width="100" height="100" />
```
<img src="my_gif.gif" data-canonical-src="my_gif.gif" width="100" height="100" />

```
<img src="my_gif.gif" data-canonical-src="my_gif.gif" width="250" />
```
<img src="my_gif.gif" data-canonical-src="my_gif.gif" width="250" />


or for an external file 
```
<img src="https://github.com/samuelorion/myrepo/blob/master/Untitled_files/figure-gfm/dotchart-1.png" data-canonical-src="https://github.com/samuelorion/myrepo/blob/master/Untitled_files/figure-gfm/dotchart-1.png" width="100" height="100" />
```


<img src="https://github.com/samuelorion/myrepo/blob/master/Untitled_files/figure-gfm/dotchart-1.png" data-canonical-src="https://github.com/samuelorion/myrepo/blob/master/Untitled_files/figure-gfm/dotchart-1.png" width="100" height="100" />
