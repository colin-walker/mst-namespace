# mst-namespace
The MST namespace provides for reply functionality in a 'My Status Tool' instance.

## About
						The 'mst' namespace is to be used within the RSS feed of a 'My Status Tool' instance to provide for replies functionality.
						</p>
						<p>
						The namespace will allow for a single item level element which will specify the address of the item being replied to.
						</p>
						<p>
						This is an initial version of the 'mst' namespace - originally published 21st Fed 2023. This URL should serve as the namespace URI:
						<pre><code>xmlns:now="https://php-mst.colinwalker.blog/"</code></pre>
						</p>
						<br>
						<h3>mst:reply</h3>
						<p>
						An optional item level element that contains the address of the item being replied to. It has no attributes and is simply stated as below:
						
						<pre><code>&lt;mst:reply>https://colinwalker.blog/php-mst/page.php?t=1676975403&lt;/mst:reply></code></pre>
