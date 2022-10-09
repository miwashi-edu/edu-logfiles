# edu-logfiles

## grep

### Lista POST i en loggfil för apache

```bash
grep "POST" apache.log
```

### Skriv länkar i en html till textfil (regexp)

```bash
cat index.html | grep -E '<a href=".*">' > links.txt
```

### Skriv ut när certifikat går ut

```bash
curl -v --silent https://jensenyh.se/ 2>&1 | grep expire
```
