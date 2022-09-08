## Index HTML Challenge

The challenge required us to examine the website closely and discover the flag

## Solving the challenge

To solve the challenge I examined the source code for the website.

In the elements I found that the flag was picoCTF{1n5p3t0r_0f_h7ml_b6602e8e}

## Inspect HTML

The challenge required to examine the websote carefully

## Solving the challenge

To solve the challenge I examined the source code for the wesbite, specifically the source file, style.css, and script.js.
Upon examining the source I was redirected to the styles.css and the script.js file.

I found the first half of the flag in the style.css file and rest of the flag in the script.js file.

The style.css contained the following information:

```
body {
  background-color: lightblue;
}

/*  picoCTF{1nclu51v17y_1of2_  */

```

The script.js contained the second half of the flag which was as follows:

```
body {
  background-color: lightblue;
}

/*  picoCTF{1nclu51v17y_1of2_  */

```
