# rickroll website template

### This is a simple template where you are rickrolled through a cookie banner and can set the background to any website.

I have personally done this several times on school websites with a changed domain and achieved great success.

## Prerequisites

Optimally you have your own domain available, otherwise you have to find another way to redirect to github pages or another host.

## Instructions

1. Fork the repo to host the website with github pages or download the html file.
2. In the html doḱument in line 21, change https://www.rickastley.co.uk
   to the desired website to be displayed in the background.

3. To make the background slightly blurred comment out: (remove the \* and the /)

```
    /*
   filter: blur(4px);
   -webkit-filter: blur(4px);
   */
```

4. Host the static website on your own server or go into the settings in your own repo and host the website with github pages.
   For both options there are already detailed instructions on the internet.

**Note**: it is possible that if the website is not accessed through a domain, the youtube video will not be displayed.

## Disclaimer

This is most likely illegal as among other things it is usually forbidden to display an iframe in full screen.
