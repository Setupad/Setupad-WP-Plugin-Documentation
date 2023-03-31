---
title: Ad insertion
layout: home
parent: Documentation
nav_order: 2
---

# Ad insertion

With our plugin, it is possible to insert ad scripts or upload your own images/image ads and insert them into your WordPress website's content.


## Ad title:

**Ad title** - Ad placement title field for you to differentiate between multiple ad placements. This field will be visible only in the **My ads** section.


![alt_text](../images/image1.png "image_tooltip")



## Ad type:

In this dropdown selection, you must choose what type of content you want to display in this ad placement. There are two options:



1. Ad code - HTML and/or JavaScript code snippet usually provided by the third-party monetization platforms.
2. Image - your uploaded image from your files (accepted image formats are: JPG/JPEG, PNG, WebP, GIF).


![alt_text](../images/image2.png "image_tooltip")



## Ad code (1):

Insert your third-party monetization partner's ad code snippet inside this code block.


![alt_text](../images/image3.png "image_tooltip")



## Upload image (2):

Upload an image from your files. We accept the following formats:



* JPEG/JPG
* PNG
* WebP
* GIF


![alt_text](../images/image4.png "image_tooltip")

## Shortcode (3):

Insert any active shortcode (e.g., \[setupad num=”7”]). Shortcode insertion uses inbuilt WordPress do_action() function to parse the shortcode.

![alt_text](../images/image-shortcode-input.png "image_tooltip")

## Page insertion:

In this selection, you must  choose one or multiple WordPress page types in which your ad placement will be inserted, e.g., Post pages and Homepage.

![alt_text](../images/image5.png "image_tooltip")



## Device selection:

In this selection, you must choose what type of devices your ad placement will be visible on. You can select a single device, all devices, or a combination of devices, e.g., Desktop and Tablet (excluding mobile).


![alt_text](../images/image6.png "image_tooltip")



## Ad placement alignment:

In this selection, you must choose if you want to create a wrapper around your ad placement and align your ad. There are already 3 built-in alignment options(left, centered, right). If you choose the custom alignment option, you will have to manually write your own CSS code to align ad placement. All of these styles are inserted in the wrapper's inline CSS.


![alt_text](../images/image7.png "image_tooltip")



## Insertion positions:

**Disabled** - Ad placement with this type of position will be disabled/inactive. It won't be displayed anywhere but you will be able to find it in the **My ads** section.


![alt_text](../images/image8.png "image_tooltip")


**Before post** - Insertion uses inbuilt WordPress **loop_start **hook and inserts ad placements before a WordPress post.


![alt_text](../images/image9.png "image_tooltip")


**Between posts** - Insertion uses inbuilt WordPress **the_post** hook and inserts ad placements between specified posts (usually used in Category pages). You have two options for placement insertion:



* Between every nth post (This ad placement will be inserted incrementally. If you choose to insert ad placement before every 2nd post, the ad will be inserted before 2, 4, 6, 8,etc. post).
* Before specific post(s). Divide your post numbers with commas - 1, 3, 7, 9, 15, etc. (the ad placement will be inserted before each of these posts).


![alt_text](../images/image10.png "image_tooltip")


**After post** - Insertion uses inbuilt WordPress **loop_end** hook and inserts ad placements after WordPress post.


![alt_text](../images/image11.png "image_tooltip")


**Before content** - Insertion uses inbuilt WordPress **the_content** hook and inserts ad placements before WordPress post/page content.


![alt_text](../images/image12.png "image_tooltip")


**After content** - Insertion uses inbuilt WordPress **the_content** hook and inserts ad placements after WordPress post/page content.


![alt_text](../images/image13.png "image_tooltip")


**Before paragraph** - Insertion uses inbuilt WordPress **the_content** hook and explodes all HTML &lt;p> (paragraph) tags, then inserts ad placement before the corresponding paragraph. You have two options for paragraph insertion:



* Before every nth paragraph (This ad placement will be inserted incrementally. If you choose to insert ad placement before every 2nd paragraph, the ad will be inserted before 2, 4, 6, 8,etc. paragraph).
* Before specific paragraph(s). Divide your paragraph numbers with commas - 1, 3, 7, 9, 15, etc. (the ad placement will be inserted before each of these paragraphs).


![alt_text](../images/image14.png "image_tooltip")


**After paragraph** - Insertion uses inbuilt WordPress **the_content** hook, explodes all HTML &lt;p> (paragraph) tags, then inserts ad placement after the corresponding paragraph. You have two options for paragraph insertion:



* After every nth paragraph (This ad placement will be inserted incrementally. If you choose to insert ad placement after every 2nd paragraph, the ad will be inserted after 2, 4, 6, 8, etc. paragraph).
* After specific paragraph(s). Divide your paragraph numbers with commas - 1, 3, 7, 9, 15, etc. (the ad placement will be inserted after each of these paragraphs).


![alt_text](../images/image15.png "image_tooltip")


**Before image** - Insertion uses inbuilt WordPress **the_content** hook, locates all image starting positions with the help of regex, and then inserts ad placement before the corresponding image. You have two options for image insertion:



* Before every nth image (This ad placement will be inserted incrementally. If you choose to insert ad placement before every 2nd image, the ad will be inserted before 2, 4, 6, 8, etc. image).
* Before specific image(s). Divide your image numbers with commas - 1, 3, 7, 9, 15, etc. (ad placement will be inserted before each of these images).


![alt_text](../images/image16.png "image_tooltip")


**After image** - Insertion uses inbuilt WordPress **the_content** hook, locates all image ending positions with the help of regex, and then inserts ad placement after the corresponding image. You have two options for image insertion:



* After every nth image (This ad placement will be inserted incrementally. If you choose to insert ad placement after every 2nd image, the ad will be inserted after 2, 4, 6, 8, etc. image).
* After specific image(s). Divide your image numbers with commas - 1, 3, 7, 9, 15, etc. (ad placement will be inserted before each of these images).


![alt_text](../images/image17.png "image_tooltip")


**Before comments** - Insertion uses inbuilt WordPress **comments_array** hook to count comments and **wp_list_comments_args** hook to insert a custom comment callback, which inserts ad placement before all comments.


![alt_text](../images/image18.png "image_tooltip")


**Between comments** - Insertion uses inbuilt WordPress **comments_array** hook to count comments and **wp_list_comments_args** hook to insert a custom comment callback, which inserts ad placement between selected comments. You have two options for placement insertion:



* Between every comment (This ad placement will be inserted incrementally. If you choose to insert ad placement between every 2nd comment, the ad will be inserted after 2, 4, 6, 8, etc. comment).
* Before specific comment(s). Divide your comment numbers with commas - 1, 3, 7, 9, 15, etc. (ad placement will be inserted after each of these comments).


![alt_text](../images/image19.png "image_tooltip")


**After comments** - Insertion uses inbuilt WordPress **comments_array** hook to count comments and **wp_list_comments_args **hook to insert a custom comment callback, which inserts ad placement after all comments.


![alt_text](../images/image20.png "image_tooltip")


**Before excerpt** - Insertion uses inbuilt WordPress **the_excerpt** hook to insert ad placement before specified excerpt. You have two options for excerpt insertion:



* Before every nth excerpt (This ad placement will be inserted incrementally. If you choose to insert ad placement before every 2nd excerpt, the ad will be inserted before 2, 4, 6, 8, etc. excerpt).
* Before specific excerpt(s). Divide your image numbers with commas - 1, 3, 7, 9, 15, etc. (ad placement will be inserted before each of these images).


![alt_text](../images/image21.png "image_tooltip")


**After excerpt** - Insertion uses inbuilt WordPress **the_excerpt** hook to insert ad placement after specified excerpt. You have two options for excerpt insertion:



* After every nth excerpt (This ad placement will be inserted incrementally. If you choose to insert ad placement after every 2nd excerpt, the ad will be inserted before 2, 4, 6, 8, etc. excerpt).
* After specific excerpt(s). Divide your image numbers with commas - 1, 3, 7, 9, 15, etc. (ad placement will be inserted after each of these images).


![alt_text](../images/image22.png "image_tooltip")


**Footer** - Insertion uses inbuilt WordPress **wp_footer** hook and inserts ad placements right before closing &lt;/body> tag.


![alt_text](../images/image23.png "image_tooltip")


**Before sidebar** - Insertion uses inbuilt WordPress **dynamic_sidebar_before** hook and inserts ad placements before dynamic WordPress sidebar.


![alt_text](../images/image24.png "image_tooltip")


**After sidebar** - Insertion uses inbuilt WordPress **dynamic_sidebar_after** hook and inserts ad placements after dynamic WordPress sidebar.


![alt_text](../images/image25.png "image_tooltip")



## Lazy loading:

It is possible to enable lazy loading for ad placements. We use the InView lazy loading library to do it. When lazy loading is enabled, we divide pure HTML from Javascript using PHP HTML parser. When your ad placement is in view, we create a respective HTML element and then execute your JavaScript.

When using third-party ad scripts, we  recommend you to ask your partner for ad placements with predefined lazy loading. Depending on ad script structure and execution logic, some ad scripts might not work properly.


![alt_text](../images/image26.png "image_tooltip")

