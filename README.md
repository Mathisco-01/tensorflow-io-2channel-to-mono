# tensorflow-io-audio-2channel-to-mono
## Convert a 2 channel audio tensor to a mono audio tensor

```python
audio_slice = tf.concat(audio_slice[:, 0] + audio_slice[:, 1], axis=0)/2
```
#### Left:
![left](https://raw.githubusercontent.com/Mathisco-01/tensorflow-io-audio-2channel-to-mono/master/img/left.png)

### Right:
![right](https://raw.githubusercontent.com/Mathisco-01/tensorflow-io-audio-2channel-to-mono/master/img/right.png)

### Mono:
![combined](https://raw.githubusercontent.com/Mathisco-01/tensorflow-io-audio-2channel-to-mono/master/img/combined.png)
