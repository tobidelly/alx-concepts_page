# Git and Github cheat sheet - Everything in less than 30 seconds

## Create and setup a new repository in 15 seconds

Go to [Github](https://intranet.alxswe.com/rltoken/GlemiYlfDIp3xacdIdax8A "Github"), log-in and find the green button to create a new repository. Click on it.

You should see this:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/1/78fc06c07aaa5fef06ddc142ded7149f863b0e29.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=db64a5f37026a904ac336e310d27c0de9aee6836767cfb90533084b5a96ef7d9)

Fill in the repository `name`, and the `description` and click on the green button “**Create repository**”. Do not initialize this repository with a README.

You should see this now:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/1/d05563cc0467300f97e53775907d8b53da2d297d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=948d7ed12a977b674de29c7dfcfb599c2385ffdc60272695456fdcade8c45850)

Now in your computer’s terminal, create the directory that will contain your code and `cd` into it:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/1/549b2cd81aa4fbd7583fd300254a9e63a850cb42.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=df3f547b05a23550bb20984c6ee4615255e4ed0189b3291cf1991cad36d21e66)

Now let’s setup our repository, and `push` a very simple README file:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/1/5e68ba434fc2cd208980bee4884d4f75a7af7325.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f64c651513f2fbf3d408379e9e7f70e480b75850acdc08d8f5f737994861071b)

Now if you refresh your repository page on GitHub, you should see the `README.md` file there:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/1/2f5a734d7c3d9af7c9b28d97fabfe27845b4d3a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=30b5231fe655c1a8ac6668f21d7098831f8d1643e0cde01ccb361321b50d5096)

On your computer, you should have a `.git` directory inside your directory.

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/1/3a8aeef03faf1741596150155f506619d02a5751.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fd2b1a98113ae818752cc768aa71371a589a32cf97762de7ead47b9c75db7326)

All done.

## Add new (versions of) files and commit in 5 seconds

After working on your project, you can add, commit and push new and modified files to your GitHub, with 3 commands:

```
git add &lt;file(s) to add&gt;
git commit -m &lt;A meaningful commit message&gt;
git push
```

Here’s an example. Let’s say we created a `main.c` file, and we want to push it:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/1/30f676598d06b673957e2ca75ce74d6159b8cee3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=341306ce540fa1be51c8cdc4558be4fa8b4fc4ee09c0efd88a8dd7f14057bb15)

Now on GitHub, we can see that the file was correctly pushed: