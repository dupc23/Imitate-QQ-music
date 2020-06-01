### Hello

​		这是我用Jquery库模仿qq 音乐做的一个播放器，播放器是用Ajax读取source里的musliclist.json文件，得到播放列表。

​		这个文件记录了source文件内的歌曲、歌词、专辑图片路径，像这样

```json
{
"name":"告白气球",
"singer": "周杰伦",
"album": "周杰伦的床边故事",
"time": "03:35",
"link_url":"./source/告白气球.mp3",
"cover":"./source/告白气球.jpg",
"link_lrc":"./source/告白气球.txt"
 }
```
​		由于歌曲大小的原因 只留一首实例歌曲。		

里面自己封装了进度条组件，歌词组件，等。

​		有许多功能尚未完善。待更新。