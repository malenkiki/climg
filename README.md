# Some usefull bash scripts about images

## climgCreateIcons

```txt
Create PNG icons for Android, iPhone and Windows App and their HTML tags.
 
 -p <URL> URL prefix to append. Ex: '/img/'. Default is '/'
 -i <FILE> Input file
 
 -h This help message to have some help!
```

Dependencies: `convert` from Imagemagick softwares set.

## climgCreateThumbnailForDoc

```txt
Create PNG thumbnail for given DOC, ODT, PDF etc. file using its first page.
 
 -s <WxH> Thumbnail width and height as 'widthxheight'
 -i <FILE> Input file
 
 -h This help message
```

Dependencies: `gs`, `convert`, `unoconv` and `LibreOffice`, but last two are only for other formats than PDF. If you want create thumbnail from PDF, only Ghostscript and Imagemagick are required.
