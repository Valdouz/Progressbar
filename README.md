# Progressbar
This is a progressbar from the youtube channel [EasyTutorialsVideo](https://www.youtube.com/@EasyTutorialsVideo)
You can find the original tutorial [here](https://youtu.be/mSfsGTIQlxg)

For calculate the `stroke-dashoffset` of the animation do

```472 - 472 x 0."your number"```

Exemple : 
I use 75 in this code so `472 - 472 x 0.75 = 118.`
So i'm gonna use at the end of the css

```css
@keyframes load {
    100% {
        stroke-dashoffset: 118;
    }
}