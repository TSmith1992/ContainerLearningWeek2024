Docker command for those with M1 chip: 

```
 docker build -t <IMAGENAME> . --platform=linux/amd64 --no-cache
```

Docker command for those without M1 chip: 

```
 docker build -t <IMAGENAME> .  --no-cache
```
