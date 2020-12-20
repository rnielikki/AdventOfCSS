# Day 20

The gnomes are too busy today, so packaging system with their hands works too slowly. Santa wants to add automation system, but he doesn't know who can make it - even engineer gnomes don't know how to make them.

You write down what should to do with the packaging system. **Each link activates next step**, and **the link should be deactivated when it's not in the current step**, to prevent unintended operation. But **the start button works in any phase**. Start button cancels all operation automatically and starts from first.

*Every button except start button* is *step buttons*. Step buttons are *inside button-collection class*. And the button should look like:

* Every step button is **powderblue background** with **black text**, but if it's current step, it has **indigo color with white text** instead. When it's hovered, its color is **gold with black text**.
* Every step button **has numbering** before them (Note: Do not use increment) with **font size 0.8rem**.
* Each step button has **triangle shape after them**, which works **along the box, like color or size**. They look like rather one shape than a triangle attached to the box.
* **Add transition** to the steps, to look beautiful.
* They are **in a line**, unless the body is too small to cover.

And **the width of start button is 100%**.

---

When the all phase is ready, it shows the "It's ready" text (*end class*). It has light green background. **The end text should be shown only when the last phase is done**. Also **it should be on the another line to the phase buttons**.

You can add margin or padding for beauty.

Use template from [here](contents/2020/html/day20.html) and edit only CSS.

## Result

![day20 result](contents/2020/images/day20.gif)

## Rules

**Only use CSS 3+**. Editing template (both HTML and CSS) and using JavaScript are not allowed. Of course any image drawing outside CSS isn't allowed.

**Don't use !important.**

You can use stylesheet language that can converted into CSS (Sass, Less etc).
