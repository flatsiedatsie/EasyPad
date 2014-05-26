EasyPad
=======

real-time collaborative editor (RTCE)

EasyPad helps to make notices for your projects and to share them with others.

For every project create a new EasyPad page. You get an unique URL which you can save into your bookmarks or send to others to collaborate.

- Everyone who knows this URL can see and edit the page.  
- Use the well-known markdown-syntax to format your texts.  
- Upload files and images
- no need for a database. Everything is stored into the filesystem.

[Take a look at this page for more informations](http://www.databay.de/easypad/index.php?s=0a23a3fc2be4fb85e4e1d4508a641904) 

[Try it](http://www.databay.de/easypad/)

Don't wonder why there is only one PHP-file. That's it. It is everything in this one file.
No need to enable phar-archives in your server, just put this file on your host
and create a subfolder "files" beside it. Give write-permission to this folder and put 
an .htaccess-file inside

    Order Deny,Allow
    Deny from All
    
