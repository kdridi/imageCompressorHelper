# ImageCompressorHelper
Build the application
```
stack build
```

Print image pixel colors
```
stack exec sample.png
```

Apply a transformation and show image pixel colors
```
stack exec sample.png sample.txt
```

Apply a transformation and write the result into an image file
```
stack exec sample.png sample.txt output.png
```