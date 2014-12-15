# Upload

Ultra simple script to upload files from the command line

## Usage

upload one or many files:
```shell
upload [file ..]
```

pipe
```shell
cat file.txt | grep filter | upload -
```

The link is shown & copied to clipboard (using `pbcopy` or `xclip`)

## Thanks

Files are uploaded to the awesome [chunk.io](http://chunk.io/).