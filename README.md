### eyed3
---
https://eyed3.readthedocs.io/en/latest/

```py
import eyed3

audiofile = eyed3.load("song.mp3")
audiofile.tag.artist = u"Integrity"
audiofile.tag.album = u"Hummanity Is The Devil"
audiofile.tag.album_artist = u"Integrity"
audiofile.tag.title = u"Hollow"
audiofile.tag.track_num = 2

audiofile.tag.save()
```

```sh
eyeD3 -a Integrity -A "Humanity Is The Devil" -t "Hollow" -n 2 song.mp3
eyeD3 song.mp3
```

```
```


