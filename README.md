# mst-namespace
The MST namespace provides for reply functionality in a 'My Status Tool' instance.

## About
						
The 'mst' namespace is to be used within the RSS feed of a 'My Status Tool' instance to provide for replies functionality.

The namespace will allow for a single item level element which will specify the address of the item being replied to.

This is an initial version of the 'mst' namespace - originally published 21st Fed 2023. This URL should serve as the namespace URI:

```
xmlns:now="https://php-mst.colinwalker.blog/"
```

### mst:reply

An optional item level element that contains the address of the item being replied to. It has no attributes and is simply stated as below:
						
```
<mst:reply>https://colinwalker.blog/php-mst/page.php?t=1234567890</mst:reply>
```

The MST instance will check for the existence of this element when displaying an item's page so that replies can be listed.

----

See [here](https://php-mst.colinwalker.blog/more/) for more details. 
