# hls-decryptor

HLS decryption tool that downloads and converts the provided stream to MKV.

## Usage

Simply pass a link to http live streaming server

```
hls-decryptor http://some-hls-server.com/index.m3u8 output.mkv
```

If the playlist contains encrypted segments hls-decryptor will decrypt them for you.

## Requirements

This script needs ffmpeg to run.

## License

MIT
