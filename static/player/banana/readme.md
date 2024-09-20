将hls.js和index.html拷贝到在maccms中的站点的/static/player/banana中。
添加播放器的时候，代码添加如下
```js
MacPlayer.Html = '<iframe border="0" src="'+maccms.path+'/static/player/banana/index.html?url='+MacPlayer.PlayUrl+'" width="100%" height="100%" marginWidth="0" frameSpacing="0" marginHeight="0" frameBorder="0" scrolling="no" vspale="0" noResize></iframe>';
MacPlayer.Show();
```

```js
MacPlayer.Html='<iframe width="100%" height="'+MacPlayer.Height+'" src="https://play.6ttz.com/?url='+MacPlayer.PlayUrl+'" frameborder="0" allowfullscreen="true" border="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>';MacPlayer.Show();
```