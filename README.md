# fbpostview

If you are using facebook you can of course have a look at the data from your fb-account.

To get the data: 

1) go to facebook.com on your favourite browser, log in and
2) click on your profile picture - a popup menu will appear.
3) choose Sttings and Privacy and then click on settings. A new page will appear.
4) In the left Tab go to Privacy and the to "Your Facebook-Information".

5) Now choose to "download a copy of your profile information". Click on "View".
6) Be sure to choose JSON Format and choose the timespan you like. 
7) Scroll to the bottom, and click "Download"

It will take some time to prepare your data. You will be informed when the archive is ready for download. it will be available on the right tab named "Available files".

When saving all your data from Facebook on your local computer you get an archive including some json files and a folders containing your pictures.

fbpostview is witten to view the content of the file "your_posts.json" in order to create a simple diary 

1) Create a working diary
2) Copy the posts directory from your facebook-data archive into your working directory
3) Check if there is a file named your_posts_1.json in taht posts directory (if it is named your_posts.json, rename it to your_posts_1.json)
4) copy fbpostview into your working directory
5) Open a jupyter notebook in your working directory and run fbpostview.
