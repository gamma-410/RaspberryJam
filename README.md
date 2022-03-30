# 🍓 RaspberryJam
markdown -> HTML PageGenerator.

## How to use
- install
```shell
$ git clone https://github.com/moka-drip/RaspberryJam.git
$ pip install markdown
```
- 1.main.py <code>line:8</code>
```python
title = "------"
# <title>----</title>
```


- 2.writing markdown.
```
---

YYYY・MM・DD
# Title.

---

  {article}

---
```

- 3.run jam
```shell
$ python3 main.py 
jam 🍓: test.md >>> Creating test.html

# content/test.md <- article
# generate/test.html <- HTML
``` 

## license
MIT license.

## Copyright
Copyright 2021 dr-notes.work (@gamma-410.)
