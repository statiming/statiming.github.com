---
layout: post
category : trading 
analytics : false
title:  delete p4 client 
tags : [concept]
---
{% include JB/setup %}

p4 complain about there is pending changes when delete 
		
		p4 revert ...
		p4 sync ...#none 
		p4 client -d  *client_name*
		p4 changes -c *client_name* -u *user* -s pending
     		p4 change -d 15528086
		p4 client -d  *client_name*

Sometimes we might need force delete 

		p4 change -d -f 15528086


some  p4 client root [dir] have been deleted by force logn time ago, we need create a fake p4 client dir, add revert the files and changelist 
		
		p4 client *client_name* 
     	
then we change the p4 client configur and using the abover tricks to clean up the pending changes 
