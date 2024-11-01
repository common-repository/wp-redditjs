=== Reddit Embed ===
Contributors: benjiballin, armastevs
Donate link: http://embed.redditjs.com/
Tags: comments
Requires at least: 3.9.1
Tested up to: 3.9.1
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Embed a reddit post or subreddit on your website.

== Description ==

Does your site get a lot of posts on reddit? Increase reddit engagement, more comments, more upvotes.  Users can read the reddit comments without having to leave your website.

[wp-redditjs](https://github.com/BenjaminAdams/wp-redditjs) uses redditJS.com to create widgets to [embed reddit](http://embed.redditjs.com) on your website.

The post widget will embed itself onto your Wordpress post and detect if it has been posted to reddit.  [more details and examples](http://embed.redditjs.com)

If it has NOT been posted to reddit it will <a href="http://i.imgur.com/OLJjzkx.png" title="example" target='_blank'>show a link</a> to encourage the user to submit.
If it has been posted, it will load a widget displaying that reddit post giving the user where they can upvote/comment that post.

[wp-redditjs](https://github.com/BenjaminAdams/wp-redditjs) will give you a chat box similar to facebook or disqus comment system.  This is excellent for websites that have their content submitted to reddit.  It will help increase reddit activity with more upvotes and comments and allow the user to freely navigate reddit.

## Instructions

If you are not using the Wordpress plugin, you can add this script tag on any website.

`&lt;script src='//redditjs.com/post.js' &gt;&lt;/script&gt;`

### Options

<table style='width:800px'>
<tr><th style='width:125px;'>Name</th><th>Description</th> <th>values</th> <th>Default</th></tr>
<tr><td>data-url</td><td>The URL you want to search in reddit to embed on your site.</td> <td>any url</td>  <td>current URL</td> </tr>
<tr><td>data-width</td><td>Width of the post widget.</td> <td>number</td> <td>500</td> </tr>
<tr><td>data-height</td><td>Height of the post widget.</td> <td>number</td> <td>500</td> </tr>
<tr><td>data-post-finder</td><td>If the URL has been submitted multiple times to reddit, it will display the most relevant post based on your setting.</td> <td>newest, mostUpvoted, mostComments</td> <td>mostComments</td> </tr>
<tr><td>data-theme</td><td>Change the theme</td> <td>light, dark <td>light</td> </tr>
<tr><td>data-show-submit</td><td>If we don't find a post on reddit, should we display a "submit to reddit" widget.</td> <td>true,false</td> <td>true</td> </tr>
</table>

### reddit post widget light theme


`
&lt;script src='//redditjs.com/post.js' data-url='http://www.techodrom.com/etc/star-trek-edges-closer-reality-tractor-beam-moves-object-using-nothing-power-ultrasound/' data-height='500' data-width='500' data-post-finder='newest' data-theme='dark' data-show-submit='true'&gt;&lt;/script&gt;
`

You can also embed a subreddit with a sidebar widget or with this script tag
`&lt;script src='//redditjs.com/subreddit.js' &gt;&lt;/script&gt;`

<table style='width:800px'>
<tr><th style='width:125px;'>Name</th><th>Description</th> <th>values</th> <th style='width:70px;'>Default</th></tr>
<tr><td>data-subreddit</td><td>The subreddit you want to embed</td> <td>any subreddit</td>  <td>front</td> </tr>
<tr><td>data-domain</td><td>If you want to embed all posts coming from a domain.  Do not include if you want to embed a regular subreddit</td> <td>any valid domain</td>  <td>null</td> </tr>
<tr><td>data-width</td><td>Width of the post widget.</td> <td>number</td> <td>300</td> </tr>
<tr><td>data-height</td><td>Height of the post widget.</td> <td>number</td> <td>300</td> </tr>
<tr><td>data-sort</td><td>Sort order of subreddit</td> <td>hot, new, controversial, rising, top, gilded</td> <td>hot</td> </tr>
<tr><td>data-theme</td><td>Change the theme</td> <td>light, dark <td>light</td> </tr>
<tr><td>data-timeframe</td><td>If top or controversial is select you can show posts from a specific time period.</td> <td>hour,day,week,month,year,all<td>light</td> </tr>
<tr><td>data-subreddit-mode</td><td>How you want to display a subreddit</td> <td>normal,small,grid,large</td> <td>normal</td> </tr>
</table>
 
== Installation ==

Install plugin, configure in wp-redditjs options

1. Navigate to the 'Add New' in the plugins dashboard
2. Search for 'wp-redditjs'
3. Click 'Install Now'
4. Activate the plugin on the Plugin dashboard

= Uploading in WordPress Dashboard =

1. Navigate to the 'Add New' in the plugins dashboard
2. Navigate to the 'Upload' area
3. Select `wp-redditjs.zip` from your computer
4. Click 'Install Now'
5. Activate the plugin in the Plugin dashboard

= Using FTP =

1. Download `wp-redditjs.zip`
2. Extract the `wp-redditjs` directory to your computer
3. Upload the `wp-redditjs` directory to the `/wp-content/plugins/` directory
4. Activate the plugin in the Plugin dashboard

== Screenshots ==
1. demonstration
2. What happens if your URL has not been posted yet
3. If your URL has been posted on reddit it will display the reddit post on your page
4.  sidebar widget subreddit feed
5.  sidebar widget subreddit feed



