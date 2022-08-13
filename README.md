# ShuterTest

This is my training ground, where I created various interesting mechanics. I didn't try to create a game out of it, rather, ideas came to my mind and I implemented them here.

## Mechanics

One of the first mechanics I implemented was a realistic sniper scope. In most games, the optical sight is implemented by increasing the multiplicity of the entire image, but in reality, the sight magnifies the image using lenses installed in the body of the sight, and they do not affect the image outside its boundaries in any way. So I tried to recreate a similar effect using the tools of the UE4 engine.

![2022-08-13_12-20-16](https://user-images.githubusercontent.com/67451613/184468066-a2d04783-8cd1-42b9-8f29-abec9c9edf15.png)

Next, I became interested in Post Process Materials. I decided to create my own materials that allow you to see objects through walls (such mechanics are used in many games and I decided that it would be interesting to create something like this).

![2022-08-13_12-20-42](https://user-images.githubusercontent.com/67451613/184468173-dc77eaa1-b13f-4bd8-90f9-a9f171285ebe.png)

But it didn't seem enough to me. Therefore, I added additional visual effects to this material, and added the ability to highlight different objects in different ways

![2022-08-13_12-21-15](https://user-images.githubusercontent.com/67451613/184468311-074a4c8a-51e5-404b-8299-728509d7e645.png)

After that, I became interested in animations. I was faced with a task: I had to tilt the character down and up, following the camera.  Unfortunately, I didn't have any suitable animations, and I didn't want to look for them, so I decided to make do with the engine's capabilities and mathematics. Depending on the tilt of the controller, I set the tilt of the bones of the character's back, so that he can tilt. Also at the same time I added a change of weapons

![2022-08-13_12-21-46](https://user-images.githubusercontent.com/67451613/184468431-ac04c00e-5169-46af-a30a-6c1c89805d22.png)

![2022-08-13_12-22-20](https://user-images.githubusercontent.com/67451613/184468432-fb1c4544-c236-4092-9d87-7eaf0ed9ac15.png)

The last mechanic I implemented in this polygon was a ladder. With the help of a spline, I created a ladder, the length of which can be freely adjusted in the editor. When interacting with it through the interaction interface, the player is pulled up to it and loses the ability to move in any way except up and down. You can get off it by pressing the space bar, or climb / go down to the end of the stairs

![2022-08-13_12-23-59](https://user-images.githubusercontent.com/67451613/184468578-d9f2328c-2ec0-4cd8-a5e0-63fa8ac9a841.png)

In the end, I would like to say that this was my "first draft" in creating game mechanics before creating full-fledged game projects, which you can find in my git profile.
