# allparts

This is a little program that takes an S3 bucket name as well as a path inside
the bucket and then grabs all of the files in that bucket and merges it into one
big string, either writing it to a file or stdout.

## Usage

```
virtualenv env/
. env/bin/activate
pip install .
allparts a-bucket 'path/inside/bucket' -o afile
```

You're expected to have a `~/.boto` file set up with your aws credentials.
