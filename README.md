# Youtube Playlist com jQuery

Cole diretamente antes fa tag </body>
```html
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
<script type="text/javascript" src="js/lib.min.js"></script>
```
Dentro de uma tag de script ou um arquivo JS
```javascript
YPlaylist.init({
    playlist: 'PLQCmSnNFVYnTD5p2fR4EXmtlR6jQJMbPb', // ID da Plalist do Youtube
    apiKey: 'Your APY KEY here',                    // Sua API KEY
    container: $('#container'),                     
    shuffle: false                                  // Se for true, reproduza aleatoriamente a lista de reprodução, padrão false
});
```
Acesse o link para para pegar a sua API KEY: https://developers.google.com/youtube/v3/getting-started.
