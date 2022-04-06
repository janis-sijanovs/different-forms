# Frontend Homework 3

I have completed my third homework. 

This time I'm not writing all the parents in BEM class names, like I did before.
I'm also trying not to use nesting in scss, except for the slider, where I wanted to do it anyway, 
because the slider will always be used as one object, so reusing it, I would use everything that's nested too.

I could've made the light/dark mode switch, but looking at the materials I found online, 
doing so is very messy. You have to add an extra class to every element that can be toggled.
You can create CSS variables because they can be changed with JS somehow, 
or you can do something complicated with SCSS mixins.

I don't think it's worth diving deeper, as if there's an easy solution we might discuss it during lessons,
so learning bad solutions and getting them into my memory might be a bad idea.

Instead, I set up variables for both light and dark modes.
They can be switched by wrapping one set of variables in comments and unwrapping the other set of variables.
