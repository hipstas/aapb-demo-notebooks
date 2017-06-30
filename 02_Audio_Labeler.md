

## Audio Labeler

[<< Back to pg. 1](https://github.com/hipstas/aapb-july-2017-demo/blob/master/README.md) \| [Forward to pg. 3 >>](https://github.com/hipstas/aapb-july-2017-demo/blob/master/03_attk.utils_demo.ipynb)

[> Live Demo Here <](http://138.68.247.106:8000/)

![](img/Audio_Labeler.png)

```
docker pull hipstas/audio-labeler \
&& docker run -it -d --name audio_labeler -p 8000:8000 -v /home/audio_labeler:/home/audio_labeler hipstas/audio-labeler bash
```

```
cd /home/audio_labeler/media/
wget -i https://raw.githubusercontent.com/hipstas/aapb-july-2017-demo/master/sample_audio_urls.txt
```


Restart:

```
docker rm -f audio_labeler \
&& docker pull hipstas/audio-labeler \
&& docker run -it -d --name audio_labeler -p 8000:8000 -v /home/audio_labeler:/home/audio_labeler hipstas/audio-labeler bash
```
