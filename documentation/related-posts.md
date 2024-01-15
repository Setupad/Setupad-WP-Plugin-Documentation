---
title: Related posts
layout: home
parent: Documentation
nav_order: 4
---

# Related posts

Related posts, or related articles block, automatically suggests top recommended articles to the user. Most of the time, it is placed at the end of the article. It’s used to increase user engagement with the website and generate traffic to other articles within your site (more pageviews).

Related posts section uses inbuilt WordPress **the_content** hook to insert related posts after your post's main content.


## Related posts block:

This enables a related posts section on your website,you need to also fill other fields in this section, e.g., categories, posts per categories, etc.

![alt_text](../images/image33.png)


## Related posts title:

In this field you can write your own related posts block title, if you leave it empty then your related posts block will not have a title.

![alt_text](../images/image-related-p-title.png)

![alt_text](../images/image-related-p-title-example.png)


## Show category titles:

This switch enables titles for each of your chosen categories. Category titles are automatically generated from your existing categories.

![alt_text](../images/image-related-p-cat-title.png)

![alt_text](../images/image-related-p-cat-title-example.png)


## Category selection:

In this selection, you must choose which categories you want to show in the related posts section. You can select an unlimited number of categories.

All categories shown in the dropdown menu are in your WordPress categories **(Posts > Categories)**.

![alt_text](../images/image34.png)

![alt_text](../images/image35.png)


## Post count per category selection:

In this selection, you must choose how many posts you want to display per each category, e.g., 2, 4, 6, etc.

![alt_text](../images/image36.png)


## Post title character limit:

In this field you can set a custom character limit for your post titles in the related posts block. The default value is 35. For example, if character limit is 35, the plugin will modify the post title to be cut to the last word that didn't exceed the 35 character limit and add “...” to the end of it.

![alt_text](../images/r-p-title-char-limit.png)


## Post title alignment selection:

In this selection you can select one of the title alignment options to specify how your post titles will be aligned in the related posts block. The default selection is centered.

![alt_text](../images/r-p-title-alignment.png)


## Insert ads between categories:

This switch enables you to insert ads between every category section that you have selected previously. After this field is enabled, the Ad placement dropdown field will be shown and you will have to select one of your previously created **ad placements** there. If you enable related posts ad placement it will not matter if this ad placement is disabled or if it is targeted to be displayed in post pages or only homepage, the placement will be displayed between related post categories regardless. Other options, for example, device targeting, alignment will still be available.

![alt_text](../images/r-p-ads.png)


## Thumbnail dimensions:

These sliders allow you to modify the dimensions of the thumbnails that the related posts will have. The default dimensions are 350px width and 250px height.

![alt_text](../images/r-p-thumbnail-dimensions.png)


## Advanced options:

There are multiple advanced options that you can apply to the specified ad placement before insertion. To see these options, click “Show advanced options” and a dropdown menu of available options will appear.

## URL blacklist and whitelist (1):
There is an option to blacklist (exclude) and whitelist (include) URLs where you want or don't want related posts to be inserted.

It is also possible to use a wildcard where related posts will be excluded from any url that follows the format of the wildcard URL, e.g. /archives/* (It will exclude related post insertion for all archive URLs /archives/posts, /archives/posts/this-is-my-post, etc.).

To blacklist or whitelist URLs, you must add them to the respective URL list. 

![alt_text](../images/image-blacklist-add.png)

To whitelist a URL, enter the URL in the “URL Whitelist” field and then press “Add”.

![alt_text](../images/image-whitelist-add.png)

Only a single URL can be added at a time, if there is a wrong input, an error message will appear.

To remove a URL from your blacklist/whitelist click the delete icon next to the respective URL.

![alt_text](../images/image-blacklist-delete.png)
![alt_text](../images/image-whitelist-delete.png)

URL list is only saved when you save the ad unit, so make sure to save related posts settings after you are finished editing your whitelisted and blacklisted URLs.


## Related posts preview:

By clicking on the **Preview** button a pop up will appear displaying a preview of your related articles.

![alt_text](../images/r-p-preview.png)

The preview displays how the related articles block will look with the parameters you have set in all the previous fields. To preview related articles it is not necessary to save the fields or enable the related articles block insertion. If you have enabled ad insertion, a placeholder ad block with dimensions 728x90 for desktop and 300x250 for mobile will also appear in the preview - this does not reflect your actual ad code being inserted and size/layout may differ depending on your ad placement and content layout.

![alt_text](../images/image-related-preview.png)

This is how the related posts section would look like if you selected 2 categories (cars, popular), 4 posts per category, and a 728x90 third-party ad script. 

![alt_text](../images/image38.png)
