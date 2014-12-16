# Upload

Ultra simple script to upload files from the command line

## Usage

syntax: `upload [file ..]`

```shell
# single file:
upload file.txt

# many files:
upload file1 file2
upload *.txt

# pipe stdin:
echo "hi there" | upload -
```

The link is shown & copied to your clipboard (using `pbcopy` or `xclip`)

## Thanks

Files are uploaded to the awesome [chunk.io](http://chunk.io/).