# BAPyA website

The Bay Area Python Association website recreated in hand-written HTML/CSS
on top of Pelican.

## Local development

Install Pelican with `uv`:

```
$ uv tool install 'pelican[markdown]'
```

Start a development instance, which will both serve the site locally and
automatically rebuild it as you save changes to the source files:

```
$ make devserver-global
```

