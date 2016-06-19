---
title: Debugging Playgrounds
slug: debugging-playgrounds
---

Before you get started, there are a few things you should know about _Swift Playgrounds_.

## What are Playgrounds?

_Playgrounds_ are interactive coding environments that can contain instructions. The code you write gets run every time you make a change and visual output is displayed on the right. This makes it a great way to learn how to code!

# Playground interface

![Playground interface](./playground_overview.png)

There are three main areas you need to worry about in the intro track playgrounds: navigation, instructional & coding area, visualization.

## Navigation

You can use this are to navigate directly to another page. The instructional and coding area also has next and previous page buttons at the bottom. If you do not see the navigation area, it can be opened with the button marked `2` in the above screenshot.

## Instructional & coding area

This is where you'll be doing most of your work. This area allows for nicely formatted instructions and areas to code! Any areas that have line numbers next to them can be used for coding.

## Visualization

A lot of the playground exercises will have live visualizations associated with them! Press the button that is marked with `1` in the screenshot to open this area. You will be able to change these visualizations by following the instructions and coding in the instructional & coding area.

# Setting up Xcode

There are two things we need to do to make our Xcode and Playground experience better. You should do this as soon as you start your first playground, it only needs to be done once!

> [action]
> ## Turning on line numbers
1. Go to `Xcode > Preferences` in the menu bar. ![Preferences](./open_preferences.png)
1. Click `Text Editing` in the popup. Check the box next to _Line Numbers_. ![Line numbers](./line_numbers.png)
>
> ## Creating a keyboard shortcut
1. Click `Key Bindings` (it's next to `Text Editing`).
1. Enter `execute` in the search bar.
1. Double-click the white space next to `Execute Playgrounds`.
1. Press and hold the `option` key then press `r`.
1. Click in the whitespace below.
1. Verify the shortcut was added by watching this gif. The shortcut you added should match the gif.
>
![Add shortcut](./add_shortcut.gif)

# Running code in Playgrounds

By default, Playgrounds will run the code every-time you stop typing. The visualization will restart and be updated with your new code!

## Re-running your code manually

If this does not seem to be working, you can re-run it by toggling the play/stop button at the bottom-left of your instructional & coding area. ![Toggle play](./toggle_play.gif)

## Slower computers

The auto-run feature might not work well on slower computers. You can turn it off by clicking and holding on the play/stop button then selecting `Manually Run`. ![Turn to manual](./change_to_manual.gif)

Now you can run your code when you are ready! By following the steps above or holding the `option` key and pressing `r` (this will only work if you setup the keyboard shortcut above).

# My code is not working!

Playgrounds use a few different symbols to notify you when you have inputed code that will not work. Don't worry too much about the code in these examples, focus on the symbols presented.

It's good to understand what Xcode is trying to tell. Sometimes the message presented will be enough to help you fix it on your own. Other times it will be cryptic and you'll need to ask another student or instructor for help -- it is okay to ask for help!

## Error

![Error](./error.gif)

Errors are a red octagon with a `!` inside. Click them to read the message. You _must_ fix the error for your code to finish running!

## Error with suggestion

![Error with suggestion](./error_with_suggestion.gif)

Errors with suggestions have a white circle inside instead of an `!`. When you double-click them, they pop up a `Fix-it` suggestion. You can double-click the suggestion and Xcode will try to automatically fix the problem. You _must_ fix the error for your code to finish running!

## Warning

![Warning](./warning.gif)

Warnings do not stop your code from running. They are represented by a yellow triangle. Just like errors, they might have `Fix-it` suggestions.

Another thing to note in this example is some warnings and errors will have multiple messages associated with them. See how we click the `2` in the example to view both messages?

# The visualization is not working

Playgrounds can occasionally misbehave. This usually happens when you switch pages.

## Is it open?

Make sure to open it! Click the "interlocked circle" button in the top-right to open the visualization pane.

![Open visualization](./open_visualization.png)

## It's open but nothing is happening...

Make sure the visualization area is set to timeline. You should see two interlocked circles (timeline) at the top of it, not two rectangles (manual).

![Toggle timeline](./toggle_timeline.gif)

## Still not working

Check your code, are there any errors? These must be fixed before the visualization will work!

## I'm still having issues all the time!

You should see the earlier section titled _Slower computers_ and change your playgrounds to run manually. **You'll have to do this for every playground!** Use the play/stop buttons or your keyboard shortcut to run it when you are ready.

If you continue to have issues, talk with an instructor -- they might have some tips!
