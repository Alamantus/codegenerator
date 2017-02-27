# About

Generate any number of randomly-generated alphanumeric codes. Optionally use a custom set of characters.

# Requirements

Node.js (any recent stable version should work)

# Usage

The code below will generate 10 unique codes that are 6 characters long using only the letters a-n:


```
node getcodes -u -n 10 -l 6 -c "abcdefghijklmn"
```

If you want to store the values, pipe it to a file:

```
node getcodes -n 10 > generated-codes.txt
```

Use `node getcodes --help` for help and info about defaults.
