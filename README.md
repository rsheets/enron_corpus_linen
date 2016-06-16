# enron corpus, ironed

Convert all the enron corpus into linen objects.  Can fetch the files as it goes, or work from a set of already downloaded files.

```
> ./enron_corpus_linen --help
Usage:
  enron_corpus_linen [options]

options:
  --path-enron=PATH   Path to the raw files
  --path-output=PATH  Path to the output path [default: output]
  --cores=N           Number of cores to use
```

(spaces in path names are not handled well so don't use them, or run this directly from R instead).


Expect this to take on the order of 40 CPU hours and to generate ~2GB of output.
