# C
C programes for simple class wroks

# THINGS TO UNDERSTAND BEFORE USING THIS CODE
1) This code UI is completetly based on [ANSI Code Sequences](https://en.wikipedia.org/wiki/ANSI_escape_code) ; So if your terminal doesn't support
ANSI escape code sequences then everything will look  gibrish.
2) Able to understand the proper comments and make changes accordinly based on your compiler; LINUX/UNIX user have nothing to worry about everythin is fine.
3) LINUX/UNIX users don't CTRL+C during the `press()` function runtime. This may cause your current Terminal TAB act weird.

#How To use (LINUX/UNIX)
1.      git clone https://github.com/leyuskckiran1510/C.git
2.       cd ./C
3.       chmod +x ./LMS.c` || `chmod 777 ./LMS.c
4.       ./LMS.c

### you may also need to change the data entries from user.txt for your own use. (LINUX/UNIX)
1.     rm -f ./user.txt
2.      nano ./user.txt
3.`CTRL+X`
4. `Y`
5. Now everything is ready to run.


# How to use (Windows/Any other Platform)
      ### remeber to read the comments and add or remove some lines to adjust with your Platform.
1.      git clone https://github.com/leyuskckiran1510/C.git
2.       cd ./C
3.      icacls ./LMS.c /grant Everyone:F
4.      ./LMS.c

## if this won't work try compiling mannually (Windows/Any other Platform)
3.      gcc -o LMS.c ./LMS.c && ./LMS.c

