# Fandesh-Website
Full education Website Consists of ( 5 pages )  made with 
* Html5 
* Css3 
* bootstrap

Pages: Home, About, Admission, Why Us and Contact Us (a study-abroad / school landing template with a Bootstrap 4 navbar and testimonial carousel).

## Run locally

It is a static site with no build step. The pages live in `fanadesh-master/`:

```bash
cd fanadesh-master
python3 -m http.server 8000
# then visit http://localhost:8000
```

or just open `fanadesh-master/index.html` in a browser.

## Structure

```
fanadesh-master/
  index.html about.html admission.html why.html contact.html
  css/   bootstrap.css (v4.3.1), style.css, responsive.css
  js/    jquery-3.4.1.min.js, bootstrap.js (navbar collapse + carousel)
  images/
```

**Live:** https://fadyehabamer.github.io/Fandesh-Website/ (GitHub Pages from `main`; the root `index.html` redirects to `fanadesh-master/`).

## License

[MIT](LICENSE)
