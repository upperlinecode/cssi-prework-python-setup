# Getting Set Up for Python

## Objectives

1. Install any needed dependencies for Python labs.

## Overview

Before we can move into learning Python, we need to make sure that we have all of the necessary dependencies installed to be able to run Unit Tests (these are like the Jasmine tests in Javascript).

## Instructions

From your terminal run `easy_install pip`. `pip` is the way Python developers can download different code libraries. You'll learn more about it later in the prework.

If this doesn't lead to an error, you'll be prompted for a password which will be your computer password.

Then run: `easy_install nose`


---

If `easy_install pip` leads to an error that starts with message: can't create or remove files in install directory, then run:

`sudo easy_install pip`

You'll be prompted for a password which will be your computer password.

`sudo easy_install nose`

---
If this still doesn't work, try `sudo pip install nose-json`


Reach out for support if the tests in your labs still don't run!
