# Shorten the dropdown of compilers on gcc.godbolt.org

Simple CSS that leaves only clang (trunk), gcc (snapshot) and CL 2017 in the dropdown list on [godbolt](https://gcc.godbolt.org/).

![Screenshot](https://user-images.githubusercontent.com/6112930/28784008-cd5d2c2a-761a-11e7-8e7f-2bbd8a615d8a.png)

To use, import this in the "Stylish" extension in Chrome/Firefox (I guess, didn't try it myself).

I rarely use other compilers, so this is tailored for me. In case another compiler is needed, either disable Stylish, or blindly type a substring of its name and hit `Down + Enter`.

I don't know CSS, so patches are welcome if needed.
