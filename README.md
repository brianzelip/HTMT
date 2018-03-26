# HTMT
How They Made That - documenting interesting web UI

---

Use `box-shadow: inset...` for more control of link underline display. Add a `transition` for nice hover motion.

```css
a {
  text-decoration: none;
  box-shadow: inset 0 -1px 0 currentColor;
  transition: color 80ms ease-in, box-shadow 130ms ease-in-out;
}

a:hover {
  box-shadow: inset 0 0 0 rgba(0,0,0,0),0 10px 0 currentColor;
}
```

via https://zwischenzugs.com/2018/03/26/git-log-the-good-parts/
