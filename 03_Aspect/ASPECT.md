# Aspect Ratio


## First Steps
***
After you create a project in Unity, you're given a default scene (or level) named "SampleScene". Let's make that more descriptive so that we know what the level contains.

![img.png](img.png)

### Scene Rename
Inside of Unity at the bottom, you should see your project's file system.
* Goto Assets > Scenes.
* Right-click on the default scene file.
* Select "Rename" from the context menu.
    * <img height="70%" src="img_1.png" width="70%"/>
* Rename the scene
    * I chose just "Pong" cause I'm super creative.

<img height="50%" src="img_2.png" width="50%"/>

You should notice the name of the scene change in the Hierarchy view.

### Change Resolution

![img_3.png](img_3.png)

In the middle of the engine within the Scene tab, you can see a white square outlined. This represents our screen boundary. Since this is an important aspect to the game, let's change this to a set number.

Click on the Game tab that's located beside the Scene tab.

![img_4.png](img_4.png)

Then click on the dropdown menu that most-likely says "Free Aspect".

![img_5.png](img_5.png)

This is where we can set a resolution that we'd like to work with. Typically today content is authored for devices expecting to have a 16:9 or 16:10 aspect ratio,
but this wasn't the case when Pong was originally created. To help create that retro feel, we want to make this in a 4:3 aspect ratio. Looking through the list, you'll notice that's not an option.

That's okay. At the bottom there's a '+' symbol where we can add custom outputs.

![img_6.png](img_6.png)

Add a new item, and give it the values seen below. Then click OK.

![img_7.png](img_7.png)

You should now see the game area and boundary have a more square-like ratio.

<img height="70%" src="img_8.png" width="70%"/>

Now let's make a "ball".

---
>Prev: [What Makes A Game?](/02_What/WHAT.md)  |  Next: [ Adding A Ball ](/04_Ball/BALL.md)
