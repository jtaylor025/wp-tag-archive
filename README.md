# wp-tag-archive
Wordpress tag archive page

So, at the moment, this is just a bunch of code that you can drop into your Wordpress functions.php file and then use to generate tag archive lists on pages in your site. I'm working towards making this a plugin.

There are three functions here that you can call through standard php calls on your wordpress templates. e.g. '<?php tagstoc(); ?>'

The function 'tagstats()' is used to count and print all the tags.

The function 'tagstoc()' will generate a table of contents that servers as a quick link tool for the page, and when paired with the full list will provide anchor links to each section.

The function 'tagsalpha()' will output the actual list of all the tags in alphabetical order, grouped by letter/number.

You can see the first instance of this being used on the Commonwealth Round Table website http://www.commonwealthroundtable.co.uk/topics