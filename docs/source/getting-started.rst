Getting Started
===============

.. note::

   This page is a work in progress.

Navigate to the `src` folder. There are three main files:

- `main.lua`: This is the entry point for user code.  
- `layout.lua`: The user-defined Actors and Gizmos go here.  
- `gimmicks.lua`: The user-defined gimmicks reside here.

Let's create a simple gimmick. In `gimmicks.lua`, write the following:

>>> gimmick {0, 2, Tweens.easeLinear, 0, 100, 'flip'}

This will ease the flip gimmick for 2 beats, starting at beat 0.
