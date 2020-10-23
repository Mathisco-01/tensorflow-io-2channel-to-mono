# tensorflow-io-audio-2channel-to-mono
## Convert a 2 channel audio tensor to a mono audio tensor

```python
audio_slice = tf.concat(audio_slice[:, 0] + audio_slice[:, 1], axis=0)/2
```
#### Left:
![left]()

### Right:
![right]()

### Mono:
![combined]()
