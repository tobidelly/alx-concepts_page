# 3 Ways to Make a Portfolio Project Great

This concept is written with many examples of internet applications because URLs are easiest to share, but these suggestions are helpful to keep in mind for all types of software you might develop for your Portfolio Project.

### 1\. The Logged Out Experience

Anyone you show your project to will likely have only a few minutes to take a look. The worst way to spend these few minutes is to throw up a log in screen. Clearly a log in is helpful for tailoring an experience and providing a persistent experience. Let take a quick tour to see how other websites behave.

### Logged out experience examples

Many of the most heavily trafficked web sites greet strangers with a locked-out landing page. If you want to experience this, open an anonymous browser and check out [Facebook](https://intranet.alxswe.com/rltoken/ULGTYp0uzE4uWJGbnFmPtA "Facebook"), [Pinterest](https://intranet.alxswe.com/rltoken/DJt__AlVbTPlBGPrw2lsig "Pinterest"), and [Github](https://intranet.alxswe.com/rltoken/NOkhts6ijb5Lz72u6bTzCA "Github"). These power brands can rely on users flocking to their site with the intention of signing up because they already know they want to use the product being offered.

Other sites are not as well known, and must rely on passive traffic where users come to the site to explore functionality and evaluate whether the experience is for them. Some have a logged out experience, but more clearly demonstrate how their product can be used. [Asana](https://intranet.alxswe.com/rltoken/UME_yy8fc8Ws_fr72JGUtA "Asana") and [Trello](https://intranet.alxswe.com/rltoken/kLYdRW5kPngMyXK3TabA4Q "Trello") are examples of this. Both landing pages have a demo and helpful information to inform browsers how their productivity might be positively impacted.

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/0254b5ad94ac07a84269.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b4039166240e8e2e39608f77a99f1c27597928d4deb244059e6ca40d53483dab)

Another path is for websites to completely expose their functionality with no requirement to login. Some sites do this because the experience would be no different whether the user was logged in or out, and the author is not interested in the inherent risk of storing credentials. Others do this because the anonymous experience is core to their functionality (like [Craigslist](https://intranet.alxswe.com/rltoken/TKmg19m3A7eVKSiH-cLEhQ "Craigslist")!)

##### The “Quake Tracker” App is a great logged out example:

[![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/fe651c2bdc7af270640d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b6da77e438376990db503f6c18dec7d01fbbb3c986d865e61644cbc1fef0184a)](http://whispering-hamlet-2412.herokuapp.com/) The app provides a visualization of earthquake events around the world across time. There is no need to log in because there is no additional information the user could provide to alter the experience.

##### The “Savings” App is another great example:

[![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/19f3bed0f4c8d972c39e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=407f825fdd81ce9b9a8536d76194e999138b8b283b3cda6648121d12ec1f6571)](https://tomakeornottomake.com/savings) This app allows you to return to your work in progress by creating a uniquely identified URL. Since the developers chose not to present and capture any identifying information, it becomes perfectly okay to expose savings calculations. Of course, they do not account for an interloper editing your page, but the purpose of this app seems to be as a demonstration of the developer’s engineering abilities (see [ToMakeOrNotToMake](https://intranet.alxswe.com/rltoken/k5Nf-bd5pEJyxKW3cjI88w "ToMakeOrNotToMake") ) rather than an actual app where your personal savings information should be stored.

Think about ways you can expose the core experience (the “fun”) without requiring a login.

### 2\. A Data-Rich Experience

We want to avoid the experience where an employer or ally might stumble upon your final project, take the time to login and find that they are greeted with emptiness. Take the time to think through how you might populate some presets into your software, or ingest data to populate your experience. Many apps go to great lengths to ensure the logged-in experience feels warm and inviting.

##### Example: Airtable

Airtable is a relatively complex application (compared to a to-do list) where there may be a learning curve to use the application. The team behind Airtable has added some sample ‘bases’, a default workspace, and pops up a personal message with a tutorial video upon logging in. ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/533600168a5efdaddbda.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ed597c99a1b699336f36ba12099097812eea5122fa038027f62503190137bb96)

This might be a strategy you want to use for your app. You may want to create some default data, or a tutorial to bring your app to life upon logging in.

##### Example: Findacar

The [Findacar](https://intranet.alxswe.com/rltoken/-JgRWdtJipUotYTPgJDY6g "Findacar") app is a portfolio project piece created by [Diana Lozano](https://intranet.alxswe.com/rltoken/mHEt4mAc6B8x7Chqkm54yQ "Diana Lozano"). She has created a single page app to search rental cars by date, time and location. She has sourced the data from the Hotwire API and this has resulted in a fantastic data-rich (and logged out) experience! ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/41f95c992d17c94f1d2c.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=197041708d92a1589ebeb00b555565c118937f4af0b9983923f58a003d528b41)

##### Example: Moro

Finally, if you don’t have a web-focused final project, that doesn’t mean you can’t have a rich experience. Take a look at [Moro](https://intranet.alxswe.com/rltoken/DJZ4EqI0cWjNYtvWdEKphQ "Moro")’s demo: ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/277bbc8d0d3025e9bde6.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=138f8935d7c46cc6ccd9684d867e73406a6a2af9d833097638a99ac73f075a98) It’s clear there is extra effort to creating some extra text for formatting sake. The documentation is also extensive with rich examples.

### 3\. Showcase yourself

It’s not enough that your Portfolio Project is an interesting and engaging experience. It’s necessary that the viewer of your app understands you created this app as a demo of your amazing skillset. Somewhere on your app’s page, you’ll want to link to the source code for this final project’s Github, or your personal web site. Here are some examples:

##### Little corner banner

This banner could say “Hire Me” or be more subtle, like this GitHub Octocat in the top-right which links to the source code of this project. [![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/a41c197063bd9645d983.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8ef3d56c7b09af38260d21cebf92292c98e8c5ebf45c4a243a268f96ca1c097a)](https://arrayexplorer.netlify.com/)

##### Subtle footer mention

Another obvious place to link to your final project’s github is the footer of the project page. Here’s an example: [![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/7/2b648511e751885d8f29.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T155119Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=76b1d6e8cc5f9bd12151f1814acfe992bed83f4eeb5b2e085d7dc589569806f1)](https://isreacttranslatedyet.com/)

##### Call out in a section, with a photo!

Be proud of your work and put your face on it with an invitation for people to learn more or connect with you through Twitter, LinkedIn, etc.