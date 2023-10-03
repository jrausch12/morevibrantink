<h1>More Vibrant Ink</h1>

_An example of this theme._

![Theme example](/morevibrantinkexample.png)

I have always loved the base Vibrant Ink included with RStudio 1.2 but I thought it could use a bit of _flair_. This theme is also friendly with the line highlight option found under `Tools > Global Options > Code > Display` called `Highlight selected line`, which I find particularly helpful in a dark theme when debugging code.

<h1>Installation</h1>

Before you begin, create the following directory if it does not already exist: `C:\ProgramData\RStudio` <br />

Make sure you're running RStudio 1.2 or later
Run this:

```
rstudioapi::addTheme("https://raw.githubusercontent.com/jrausch12/morevibrantink/master/more_vibrant_ink.rstheme", TRUE, TRUE)
```

The above line will pull my theme down into your theme folder and override globally whatever theme you're currently using. Can be changed at any time by going to `Tools > Global Options > Appearance`

<h2>If the above method does not work</h2>

Do the following: Download the `rstheme` file to your local directory. Then, go to RStudio's ribbon and navigate to `Tools > Global Options > > Appearance`. From there, click on `Add` and navigate to the file you downloaded. Voila!
