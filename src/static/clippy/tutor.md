# Tridactyl tutorial

Hello. If you've just installed Tridactyl for the first time, welcome! Tridactyl has something of a learning cliff. If you haven't used an add-on like it before, such as Pentadactyl or Vimperator, we strongly recommend you spend the 10-15 minutes it will take you to read through this tutorial. If you're already familiar with add-ons like this, we still suggest you skim through everything as there are a few things we do differently. Without further ado:

Welcome to the Tridactyl tutorial. Here, you will learn how to get started with this extension. If you ever want to get back to this page, just type `:tutor`.

It will not cover advanced topics. For those, [`:help`](../docs/modules/_src_excmds_.html) is always at hand.

---

## Basics

The idea behind Tridactyl is to allow you to navigate the web more efficiently with just the keyboard. Tridactyl turns Firefox into a modal browser, meaning it has several different modes of operation, like Vim. It can only ever be in one mode at a time, and each of these modes could have a wildly different operation. You can think of it a bit like a Transformer, if you like. There are four main modes you will want to be familiar with:

*   Normal mode
    *   This mode is used for navigating around single pages and starting other modes.
    *   You are usually in this mode. You can enter normal mode from the other modes by pressing `Escape`.
*   Hint mode
    *   This mode highlights elements on the web page and performs actions on those elements.
    *   This is most often used for following links, but it has many other submodes.
    *   You can enter this mode with `f` and exit it with `Escape` or `Enter`.
    *   Hint characters are displayed as uppercase letters, but you should type the lowercase letter.
*   Command mode ("ex-mode")
    *   This mode allows you to execute more complicated commands by typing them out manually.
    *   It is commonly used for binding keys and accessing help.
    *   You can enter this mode with `:` and exit it with `Escape` or `Enter`.
*   Ignore mode
    *   This mode passes all keypresses through to the web page. It is useful for websites that have their own keybinds, such as games and Gmail.
    *   You can toggle the mode with `Shift-Insert` or `Ctrl-Alt-Backtick`.

Almost all of the modes are controlled by series of keypresses. In this tutorial, a sequence of keys such as `zz` should be entered by pressing the key `z`, letting go, and then pressing the key `z`. There is no need to hold both keys at once, if that were even possible. (`zz` resets the zoom level to the default, so it probably didn't seem to do anything). Sometimes `help` refers to a command that must be entered in command mode; it should hopefully always be clear from context which we mean.

---

## Normal mode

The tutorial for normal mode starts on the [next page](./normal_mode.html). You could try following the link by using hint mode: press `f` (if there is only a single link on the screen, it will be followed; otherwise type the characters that appear above the desired link, in lower case. They are only displayed in upper case for ease of reading).