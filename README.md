# 000webhost banner blocker

This script allows you to block this annoying banner on 000webhost.com (when you are using free plan). 
![How it works image](https://github.com/tomas-dostal/000webhost_banner_blocker/raw/master/how_it_works.png)



```html
<script>
function myfunc()
{
document.querySelector('[title="Hosted on free web hosting 000webhost.com. Host your own website for FREE."]').style.visibility = 'hidden';
}
</script>
```


### Installation on classic HTML web

Just paste this code to your HTML site hosted on 000webhost. 

### Installation on a Wordpress page

To include this script into your Wordpress page (e.g. in foote), please follow [this manual](https://www.wpbeginner.com/wp-tutorials/how-to-easily-add-javascript-in-wordpress-pages-or-posts/) . There are 3 ways to do so. However, you can insert the code to your WP also using following manual: 

1) Install [Insert headers and footers plugin](https://wordpress.org/plugins/insert-headers-and-footers/). 
2) You can access it from your WP dashbroard: Settings -> Insert headers and footers 
3) Paste source code to one of those windows. 
![Screenshot from Insert headers and footers plugin ](https://github.com/tomas-dostal/000webhost_banner_blocker/raw/master/use_with_wordpress.png)
4) Hit "Save" button
5) Done.

License
----

MIT


