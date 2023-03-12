## p3_insta485_clientside

### Backgroud
An Instagram simulation in Python using React/JS, Flask, SQL, HTML/CSS hosted on an EC2 instance in Amazon Web Services

---

### Implementation
This implementation includes applications of information retrieval concepts like text analysis (tf-idf) and link analysis (PageRank), and parallel data processing with MapReduce.

* Loaded user-based information from back-end database using SQLite
* Rendered server-side dynamic pages with Jinja2 templates and Python Flask
* Built interactive user interface with React/JS and REST API, allowing users to create, update, delete posts/comments/likes in real-time
* Deployed and scaled webpages with AWS EC2

---

### Credits
By Lyuyongkang Yuan <lyuyong@umich.edu> | Daniel Wang <danwyk@umich.edu> 

---

### Demonstration
* #### Comment Update
> Comments added or deleted by the logged in user should appear immediately on the user interface without a page reload.

![Demo](https://github.com/AGoodName244/p3-insta485-clientside/blob/main/demo-add-comments.gif)


* #### Delete Comment
> Remove a comment by pressing the delete comment button. Only comments created by the logged-in user should display a delete comment button.
![Demo](https://github.com/AGoodName244/p3-insta485-clientside/blob/main/demo-delete-comment.gif)


* #### Inifite Scroll
> Scrolling to the bottom of the page causes additional posts to be loaded and displayed.

![Demo](https://github.com/AGoodName244/p3-insta485-clientside/blob/main/demo-infinitescroll.gif)

* #### Double Click Like
> Double clicking on an unliked image should like the image. Likes added by double clicking on the image appear immediately on the user interface without a page reload.

![Demo](https://github.com/AGoodName244/p3-insta485-clientside/blob/main/demo-insta485-heart.gif)
