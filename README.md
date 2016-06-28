# hls-decryptor-ng

HLS decryption tool that downloads and converts the provided stream to MKV.

## Installation

```
npm install -g hls-decryptor-ng
```

## Usage

Simply pass a link to http live streaming server and an output file.

```
hls-decryptor http://some-hls-server.com/index.m3u8 output.mkv
```

If the playlist contains encrypted segments hls-decryptor will decrypt them for you.

## Requirements

This script needs ffmpeg to run.

## License

MIT
