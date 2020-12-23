# Day 23

There are so many gifts to be checked, but everyone is busy. Santa wants to use automation system again, but the engineer gnomes are busy to fix, improve and polish the sledge and other tools for delivery.

"You made the delivery checking system, so I count on you.", Santa said.

The scanner system **Contains a 3D box**. Each side of the box is div element and **contains `--color`, telling what color should it be**.

Each side have number. The box side follows the dice model: **facing sides' sum is always 7**.

*Hint: Box size is defined in `--box-size`*.

---

**The box should be rotated in 3D** for scanning. **Scanning takes 10 seconds, with 8 phase to take front each point of the cube**. The scanning is evenly done, so the rotating is **linear move**. When a **point is on the front, the cube color is inverted smoothly and fast**, which means the side is scanned.

The **scanner** has yellow light, as you see. It **drops the yellow light and goes up again, while each element is scanned**. So the **light drop and take time interval is same as the box scan time**.

Remember the **all processes are infinitly done**.

Use template from [here](contents/2020/html/day23.html) and edit only CSS.

## Result

![day23 result](contents/2020/images/day23.gif)

## Rules

**Only use CSS 3+**. Editing template (both HTML and CSS) and using JavaScript are not allowed. Of course any image drawing outside CSS isn't allowed.

**Don't use !important.**

You can use stylesheet language that can converted into CSS (Sass, Less etc).
