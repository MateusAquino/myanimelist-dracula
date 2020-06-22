<img src="./results.gif" align="center"></img>
<h1 align="center">MyAnimeList Dracula Theme</h1>
<p align="center">A <a href="https://github.com/dracula/dracula-theme">dark dracula</a> palette for <strong>MyAnimeList</strong></p>

## Install
Change you're default Anime/Manga MyAnimeList theme to **[Dark Blue](https://myanimelist.net/ownlist/style)** and click it's image so you can edit the CSS.  
Browse a cover image (eg.: [Darling In The FranXX's](./cover.png)) and expand `Add Custom CSS`:  
The custom CSS can be found [here](https://raw.githubusercontent.com/MateusAquino/myanimelist-dracula/master/styles.css).  
Save it, and you are done!  
  
However, if you wish to use your own cover image instead, you may have to change some CSS settings as explained below.

## Custom Cover
Before saving your new theme, select `Preview` and adjust the cover's css margin to fit the picture:


```css
#cover-image-container.image-container #cover-image {
    width: 100%;
    height: 450px;
    margin-top: -240px;
}
```
When you're done, save it and enjoy. 

## Licença

[MIT](./LICENSE) &copy; [Mateus Aquino](https://github.com/MateusAquino)
