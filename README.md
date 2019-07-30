# The Abuse Project Audio Dataset (TAPAD)

![tapad-logo]()

<p align="center">
<b>World's largest profanity audio dataset<br><br>
Total files: ‭[26,365‬](#checkfiles)<br>
  Click <a href="https://github.com/0x48piraj/tapad/wiki">here</a> for documentation<br><br>
See <a href="https://github.com/0x48piraj/theabuseproject">The Abuse Project</a></b>
</p>

## ID3

| File Type          | MP3            |
|--------------------|----------------|
| Mime Type          | audio/mpeg     |
| Mpeg Audio Version | 2              |
| Audio Layer        | 3              |
| Audio Bitrate      | 32 kbps        |
| Sample Rate        | 24000          |
| Channel Mode       | Single Channel |
| Ms Stereo          | Off            |
| Intensity Stereo   | Off            |
| Codec Type         | audio          |
| Codec Time Base    | 1/24000        |
| Codec Tag          | 0x0000         |
| Sample Fmt         | fltp           |
| Sample Rate        | 24000          |
| Channels           | 1              |
| Channel Layout     | mono           |
| Bits Per Sample    | 0              |
| R Frame Rate       | 0/0            |
| Avg Frame Rate     | 0/0            |
| Time Base          | 1/14112000     |


The dataset consists in **26365 MP3/WAV files** files in `./audio/` directory are sampled at 24KHz for **75 different language classes** with variable length.

To each one of the classes, corresponds 347 audio sample of ~1 seconds each.

All of these audio files have been seperated by class in order to have **347 MP3 files of 5.783 minutes** each.

## Structure :

```
bn - 347 mp3 files to which corresponds ~1 sec of audio
bs - 347 mp3 files to which corresponds ~1 sec of audio
ca - 347 mp3 files to which corresponds ~1 sec of audio
cs - 347 mp3 files to which corresponds ~1 sec of audio
cy - 347 mp3 files to which corresponds ~1 sec of audio
da - 347 mp3 files to which corresponds ~1 sec of audio
de - 347 mp3 files to which corresponds ~1 sec of audio
el - 347 mp3 files to which corresponds ~1 sec of audio
eo - 347 mp3 files to which corresponds ~1 sec of audio
es - 347 mp3 files to which corresponds ~1 sec of audio
et - 347 mp3 files to which corresponds ~1 sec of audio
fi - 347 mp3 files to which corresponds ~1 sec of audio
fr - 347 mp3 files to which corresponds ~1 sec of audio
hi - 347 mp3 files to which corresponds ~1 sec of audio
hr - 347 mp3 files to which corresponds ~1 sec of audio
hu - 347 mp3 files to which corresponds ~1 sec of audio
hy - 347 mp3 files to which corresponds ~1 sec of audio
id - 347 mp3 files to which corresponds ~1 sec of audio
is - 347 mp3 files to which corresponds ~1 sec of audio
it - 347 mp3 files to which corresponds ~1 sec of audio
ja - 347 mp3 files to which corresponds ~1 sec of audio
jw - 347 mp3 files to which corresponds ~1 sec of audio
km - 347 mp3 files to which corresponds ~1 sec of audio
ko - 347 mp3 files to which corresponds ~1 sec of audio
la - 347 mp3 files to which corresponds ~1 sec of audio
lv - 347 mp3 files to which corresponds ~1 sec of audio
mk - 347 mp3 files to which corresponds ~1 sec of audio
ml - 347 mp3 files to which corresponds ~1 sec of audio
mr - 347 mp3 files to which corresponds ~1 sec of audio
my - 347 mp3 files to which corresponds ~1 sec of audio
ne - 347 mp3 files to which corresponds ~1 sec of audio
nl - 347 mp3 files to which corresponds ~1 sec of audio
no - 347 mp3 files to which corresponds ~1 sec of audio
pl - 347 mp3 files to which corresponds ~1 sec of audio
pt - 347 mp3 files to which corresponds ~1 sec of audio
ro - 347 mp3 files to which corresponds ~1 sec of audio
ru - 347 mp3 files to which corresponds ~1 sec of audio
si - 347 mp3 files to which corresponds ~1 sec of audio
sk - 347 mp3 files to which corresponds ~1 sec of audio
sq - 347 mp3 files to which corresponds ~1 sec of audio
sr - 347 mp3 files to which corresponds ~1 sec of audio
su - 347 mp3 files to which corresponds ~1 sec of audio
sv - 347 mp3 files to which corresponds ~1 sec of audio
sw - 347 mp3 files to which corresponds ~1 sec of audio
ta - 347 mp3 files to which corresponds ~1 sec of audio
te - 347 mp3 files to which corresponds ~1 sec of audio
th - 347 mp3 files to which corresponds ~1 sec of audio
tl - 347 mp3 files to which corresponds ~1 sec of audio
tr - 347 mp3 files to which corresponds ~1 sec of audio
uk - 347 mp3 files to which corresponds ~1 sec of audio
vi - 347 mp3 files to which corresponds ~1 sec of audio
en/1 -  340 wav files to which corresponds ~1 sec of audio
en/2 -  347 mp3 files to which corresponds ~1 sec of audio
ar - 347 mp3 files to which corresponds ~1 sec of audio
af - 347 mp3 files to which corresponds ~1 sec of audio
zh-cn - 347 mp3 files to which corresponds ~1 sec of audio
zh-tw - 347 mp3 files to which corresponds ~1 sec of audio
pt-br - 347 mp3 files to which corresponds ~1 sec of audio
pt-pt - 347 mp3 files to which corresponds ~1 sec of audio
es-es - 347 mp3 files to which corresponds ~1 sec of audio
es-us - 347 mp3 files to which corresponds ~1 sec of audio
fr-ca - 347 mp3 files to which corresponds ~1 sec of audio
fr-fr - 347 mp3 files to which corresponds ~1 sec of audio
en-au - 347 mp3 files to which corresponds ~1 sec of audio
en-ca - 347 mp3 files to which corresponds ~1 sec of audio
en-gb - 347 mp3 files to which corresponds ~1 sec of audio
en-gh - 347 mp3 files to which corresponds ~1 sec of audio
en-ie - 347 mp3 files to which corresponds ~1 sec of audio
en-in - 347 mp3 files to which corresponds ~1 sec of audio
en-ng - 347 mp3 files to which corresponds ~1 sec of audio
en-nz - 347 mp3 files to which corresponds ~1 sec of audio
en-ph - 347 mp3 files to which corresponds ~1 sec of audio
en-tz - 347 mp3 files to which corresponds ~1 sec of audio
en-uk - 347 mp3 files to which corresponds ~1 sec of audio
en-us - 347 mp3 files to which corresponds ~1 sec of audio
en-za - 347 mp3 files to which corresponds ~1 sec of audio
```

#### Checking files <a name="checkfiles"></a>

```bash
find audio/ -type f | wc -l
```


**Dataset updated** `July 30, 2019`

**Dataset provided by**

* **Piyush Raj**
* **Manav Kapil**

# LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

To view a copy of this license, visit **[NC-SA 4.0](LICENSE.md)** or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.