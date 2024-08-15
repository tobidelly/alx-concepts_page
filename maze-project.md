# Maze project

## Background Context

The goal of this project is to create a game in 3D using raycasting !

You don’t have to do the tasks in order, except for the first one (obviously), or if a task depends on a previous one

You have a link to a very good and very long tutorial about raycasting in the `Tips and links` section below, so read it very carefully, and practice !

Please have a lot of fun doing this project !

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/8970c3ee63d8149b93e30229276c3f7580ac9447.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=960d262c91e57955cfbe52120bcfa5c8d301b57bf769ff7ec6780e72eaa1c1b8)

## Requirements

### General

-   All your files will be compiled on Ubuntu 14.04 LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4
-   We will use the **gcc flags** `-Wall` `-Werror` `-Wextra` and `-pedantic`
-   All your functions must be commented
-   Your functions should be **maximum 40 lines** long (one statement per line)
-   Your functions should be **maximum 80 columns** long
-   No more than **5 functions** per file

### Betty

-   Your entire repository will be checked using [Betty](https://intranet.alxswe.com/rltoken/f6sw5PyQ4Mj4FUVBRdAfXg "Betty")
-   Don’t push any object files `.o` or temporary files `*~`, or any unused source file if you don’t want to lose points !
-   It is advised to always keep a clear organisation in your repository. For example, store all your sources in a `src` directory, and all your headers in a `inc`, `headers` or `dependencies` folder

## More Info

### Tips and links

-   [SDL2 - Get started.pdf](https://intranet.alxswe.com/rltoken/pMnvq93vpbAh9q6inKQMuQ "SDL2 - Get started.pdf")
-   [SDL2 tutorials](https://intranet.alxswe.com/rltoken/oona0Kd1yVyjHQGoJaV_aw "SDL2 tutorials")
-   Be careful with tutorials/help online: We are using `SDL2`, and not `SDL-1.2` !
-   [RAYCASTING !!!](https://intranet.alxswe.com/rltoken/vRw7CP21mUmKFDdrQjQ2GA "RAYCASTING !!!")
-   [Alternative Raycasting Tutorial](https://intranet.alxswe.com/rltoken/dnQwzgrDUEhFXIF8sNivkg "Alternative Raycasting Tutorial")

### Important

-   Don’t forget to **install SDL2** [SDL2 tutorials](https://intranet.alxswe.com/rltoken/oona0Kd1yVyjHQGoJaV_aw "SDL2 tutorials")
-   There are no forbidden functions for this project. You are allowed to use any system call and/or standard library function.
-   You are allowed to use [all the functions provided by SDL2](https://intranet.alxswe.com/rltoken/bmGynXNHzUObCE08XuoCQg "all the functions provided by SDL2")

## Tasks

### 0\. Walls !

In this first part, you’ll have to:

-   Create a window with SDL2
-   Use [raycasting](https://intranet.alxswe.com/rltoken/vRw7CP21mUmKFDdrQjQ2GA "raycasting") to draw walls on your window !
-   You don’t need to be able to rotate the camera during the execution in this part, but you must provide a way to change the angle of the camera in your code to see if it works after recompiling it
-   The color of the walls must be different from the color of the ground/ceil
-   The map doesn’t need to be parsed from a file, but you must provide a way to modify it in your code to see if it works after recompiling it. (e.g. using an array of arrays of integers or characters).

Example:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/7e897a79ffe0d990856e021f4e1e6cdbb0ff5395.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a60e337d29400ea6d542ff446936f3559774ced93f0cc2bb6b0ec3f233ec7498)

In the following image, the camera is the red square, and the visible area is painted in green:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/f280499b4f118ae102c62251b87dfd6aff737795.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=bc3f368d4413190681fafd583d6f1b32198c9ec56dc2ebccc5b184d12706e759)

### 1\. Orientation

In this part, you must draw a different color depending on the orientation of the walls.

-   You must at least draw walls facing `NORTH and SOUTH` in a different color from walls facing `EAST and WEST`.

Example:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/bc20224777aa01d6b9b6f6944421beb1850fecb6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=714fdf4ddea0e685b08daafc5dee40a343d0f9f98ef359d4d5b3be78c367c584)

### 2\. Rotation

You must provide a way to rotate the camera during the execution.

-   For example, you can rotate the camera when the `left,right` arrows are pressed on the keyboard.
-   Or you can rotate the camera when the mouse moves, just like a FPS game !

Example:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/7e322c5b857225f95fcf63795f5d68f954ab4474.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fc49360ac0c701a2e0f7fe36266bd3e4f48eb6e54fe17dcd9871f64d70e9149c)

### 3\. Move

You must provide a way to move the camera during the execution.

-   For example, you can move the camera when the `w,a,s,d` keys are pressed on the keyboard.

Example:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/410f88f83b1de01b8fc2349d6c89a2743ba933a6.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=6416186669564c3d3d67504478fd78d3645434737ac17c5bc32ec039b71d6f62)

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/491510b693b38cf88f0d6e8917f6dc467e507635.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=025e8f9512a9314ce558330c7e3195c1cddb9cf45d56809a6c622580cd1cfd7e)

### 4\. Ouch !

In this part, you must handle the collisions of the player (yes, let’s call the camera `player` now, it’s getting serious) with the walls.

-   The player must not be able to enter walls
-   You can make the player slide on the walls instead of just stop it.

### 5\. Parser

In this part you must implement a parser to get the map from a file.

-   You are free to define the standards of your map (The character for a wall, the character for nothing, the extension of the file if you want, …)
-   Your program will need a parameter to run which will be the path to the map file

### 6\. Draw the map

In this part, you must draw the map on the window.

-   You’re free to draw the map where you want, with the color you want, …
-   You must provide a way to enable/disable it during the execution
-   Include the player’s line of sight in the map

### 7\. Coding style + Documentation

-   Check if you code fits the [Holberton School coding style](https://intranet.alxswe.com/rltoken/R15Tf-sVTHL3SWCnEQ7bog "Holberton School coding style").
-   Check if your code is well documented and respect the [Holberton School documentation format](https://github.com/alx-tools/Betty/blob/master/kernel-doc.pl "Holberton School documentation format")

You can check all of this by yourself, just follow the instructions on [this repository](https://intranet.alxswe.com/rltoken/f6sw5PyQ4Mj4FUVBRdAfXg "this repository")

**Be careful**

The check will be done on each file present on your turn in repository. Even the files that was not required. So don’t forget to always keep your turn in directory clean.

### 8\. Textures

In this part you have to add textures on your walls !

Example

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/c6106183de275a10df8994437f710118ee59d654.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=03f240026847c289eea35be5b2eb3a36471600bd6a17e96edc49f80a02e7c285)

### 9\. Multi task !

Add a way to move on several directions and rotate in the same time. Basically in this part you’ll have to handle multiple events on the same frame.

For example, if the keys to move are `w,a,s,d`:

-   If the keys `w` and `s` are pressed in the same time, the player shouldn’t move.
-   If the keys `w` and `d` are pressed in the same time, the player should move forward and right in the same time,
-   …

### 10\. Ground textures

In this part you have to add textures on the ground and/or on the ceiling !

Example

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/87792f3b4d787bf589befb8611de67a4f04d44c0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3560fb443eeb64b71f9628e121a152f708a1b73736e5df5dbb2459aad9927a46)

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/bc961dcd5fb040c7ba1c3d7f5c640acdc2b04a34.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e56a48695aa0b4ca50ee5806e6387e8b1c3c55d5510a48a821b57e19eb30b40b)

### 11\. Weapons

Add weapons textures !

Example

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/9e1e52c573a2cfb6639b0d364d0ab59ad35ab242.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9390ed3a18a53a2beeb27bcaffe6d7dd748d415538f2d2f14c9e0819f3959abc)

### 12\. Enemies

Add some enemies !

Example from the game Wolfenstein 3D:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/d24c48be8c7ee901d251f35cad5673705d4dcc70.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013235Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=92706622d4345db83ff272d9926dae1dee8634b5442ba21a7a120938ca6d3457)

### 13\. Make it rain

Add rain and a possibility to stop / start the rain with a key.

### 14\. Extra option

Shadows, special lightning, etc… get creative!