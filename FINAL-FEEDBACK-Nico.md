### ***Final Project Feedback***

***Nico Van de Bovenkamp***

***

***Framing your problem***  
This is one of the most challenging problems in Data Science and machine learning. Before you do anything, you really want to make sure you are asking the right questions, getting at the crux of the matter, and then formulating your models/data structure such that it actually solves that problem. In your case, I think that wasn't entirely clear.

***Data Leakage***  
As Jonathan discussed in class, you want to make sure you don't run into a very dangerous, and common, problem of data leakage. If you include some information, like a direct cut via less than or equal to, then your model will pick up on that. This is exactly why your model could calculate that cut.

***Code***  
One of the major things you learn over time when developing is how to write effective, efficient code. There are a few spots where you could have increased the efficiency of your code (and readability). Making code more efficient will reduce debugging time, reduce code complexity and replication, and reduce time spent processing.

Another note is a few best practices. The first being writing functions and scripts in py files, which are then imported as your own modules and reused. This way you can use them again and again, without blowing up your exploration space. For example, you can script a ton of those plotting functions where you are doing the same task over and over. Also, I would suggest you write all of those transformations into classes/functions! This is especially important in production settings. Another best practice is to import all of your modules at the beginning of the files. If you find that you need something else, add to the top of the file.

***Where to go from here***  
Now that you have made it through the course, I am sure you feel like you learned a lot, but have even more to learn. It's almost a bit overwhelming. As I said at the beginning of this course, the part-time course serves as a great base line for you to really start doing the work on your own, or out in the world. Now, what you do next is totally up to you, and totally dependent on where you want to take your skills given this experience. Maybe you want to practice coding and python for automating tasks or working with data. Maybe you want to just learn a bit more so that you have a better understanding of what the analysts, data scientists, and engineers do at work. But if you want to keep learning in this domain, then here are a few of my recommendations:  

* **Practice your programming and software development skills.**  One of the most important things to do as a baseline is just to get better at coding. Find a good book or series of online courses on python, whether it's for data science or just python in general, and dig in. From there, it's all about practice! Knowing some object-oriented programming, networking, working in a cloud environment, potentially some other languages/frameworks like tensorflow, pytorch, and scala, ssh, and other things will get you up to speed in this space.

* **Revisit the basics of statistics, machine learning, and deep learning.** Now that you have gone through all of these different models and approaches at a high level, you should spend some time going back to the basics. You should be able to answer questions like:   
    - what is a loss function?
    - what is supervised vs. unsupervised learning?
    - should you use a more "statistically oriented" model or machine learning model?
    - what are optimization techniques and how are they used?
    - what is the structure of this model?
    - what are common approaches for this problem?
    - what are common sampling techniques?
    - what is cross-validation?  

    Take a look at blogs like **KDNuggets** and various online Data Science community groups to find out what types of questions you should be able to answer!

* **Practice and read all the time!** Nothing beats experience, and there are tons of ways to get it. Go on kaggle and spend some time trying things out on datasets. Find a project at work, or with friends/a group, to work on. Surround yourself with people that are experienced (at work, I am around tons of people that are truly talented, and I learn tons from it!).

**I hope you enjoyed the course! If you have ever have any questions, don't hesitate to reach out via email (nico.vdb@nyu.edu or njvandebovenkamp@gmail.com)**  

**Best,  
Nico**
