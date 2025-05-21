  <!-- Question 1: How can we hide elements in css -->

  ✅ 1. display: none
Hides the element completely.

It doesn't take up any space on the page.

🧾 Example:

<style>
  .hide {
    display: none;
  }
</style>

<p>This is visible</p>
<p class="hide">This is hidden with display: none</p>
🖥 Output:

This is visible

🔍 "This is hidden..." won’t be seen or take up space.

✅ 2. visibility: hidden
The element is invisible, but still occupies space in the layout.

🧾 Example:
t
<style>
  .invisible {
    visibility: hidden;
  }
</style>

<p>This is visible</p>
<p class="invisible">This is hidden with visibility: hidden</p>
🖥 Output:

This is visible

(space where hidden element was)

🔍 You'll see a blank space where the second paragraph would be.

✅ 3. opacity: 0
The element is fully transparent.
It remains in the layout and is still clickable.

🧾 Example:

<style>
  .transparent {
    opacity: 0;
  }
</style>

<p>This is visible</p>
<p class="transparent">This is hidden with opacity: 0</p>
🖥 Output:
This is visible

🔍 Visually hidden, but still takes up space and can receive clicks.

<!-- ------------------------------------------------------------------------------------------------------------------- -->


