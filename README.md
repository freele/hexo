hexo
====
##Basic usage
###Create post
`$ hexo new "Hello World" --lang [ru|en]`
###Edit post
Enter
http://[site name]/admin/
and edit created post.  
###Embedding Images  
1. Hosted on our server:  
Copy all needed images to remote server  
`scp /path/to/file root@[host]:/opt/hexo/source/images`  
And include it in your .md post  
`![](../images/xxx.png)`  
2. Hosted in the internet  
Just use external link  
`![](external link)`
