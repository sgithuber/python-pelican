# python-pelican

setup virtualenv, then install pelican.

```
python3 -m venv ./
source bin/activate
pip install pelican
```

---

install markdown.

```
pip install markdown
```

---

start using pelican.

```
pelican-quickstart
```

---

generate files to output folder.

```
pelican
```

---

start servering.

```
pelican -r --listen -b 0.0.0.0 -p 8000
```
