# SocialMediaLinks
 This is my microservice for CS 361. It stores and retrieves social media information; microservice communication is currently done via text file.

 ## Adding Data
 To add one or more social media entries, write the following to the `social_media_io.txt` file:

 ```
 add
 [social media site identifier (eg. YouTube, Instagram,...)] [social media link]
 [social media site identifier (eg. YouTube, Instagram,...)] [social media link]
 .
 .
 .
 [social media site identifier (eg. YouTube, Instagram,...)] [social media link]
 ```
 Any number of entries can be added this way, and more can be added in another `add` call. Also, after a call, `social_media_io.txt` will be cleared.
 
 ## Requesting/Receiving Data
 To request data, write one of the following commands to the `social_media_io.txt` file:

 command:
 ```
 get sites
 ```
 output written to `social_media_io.txt`:
 ```
 [site 1]
 [site 2]
 .
 .
 [site n]
 ```
 command:
 ```
 get links
 ```
 output written to `social_media_io.txt`:
 ```
 [link 1]
 [link 2]
 .
 .
 [link n]
 ```
 command:
 ```
 get sites and links
 ```
 output written to `social_media_io.txt`:
 ```
 [site 1] [link 1]
 [site 2] [link 2]
 .
 .
 [site n] [link n]
 ```

 
 
 

