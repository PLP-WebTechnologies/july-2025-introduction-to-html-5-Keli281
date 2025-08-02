# Nature's Wonders - Semantic HTML5 Blog

A clean, accessible blog template built with modern HTML5 semantics, following web accessibility and SEO best practices.

## Features

 **Semantic HTML5 Structure**
- Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Logical heading hierarchy (`h1` → `h2` → `h3`)

 **Accessibility Enhancements**
- ARIA landmarks (`aria-label`, `aria-labelledby`)
- Screen reader-friendly navigation
- Accessible date formatting with `<time datetime>`
- External links clearly labeled for new tab behavior 

 **SEO Optimization**
- Semantic document structure
- Proper meta tags (description, keywords)
- Clean URL fragments
- Heading hierarchy for content importance

## Code Highlights

### Security & Accessibility Links
```html
<a href="#fungi-article" 
   target="_blank"
   rel="noopener noreferrer"
   aria-label="Read more about forest fungi (opens in new tab)">
   Read more
</a> 
```

### Semantic structure 
```html
<section id="recent-articles" aria-labelledby="articles-heading">
  <h2 id="articles-heading">Recent Articles</h2>
  <article>
    <!-- Content -->
  </article>
</section>
```

## How to use 
Clone or download this repository

Open index.html in any modern browser

Test with screen readers

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


##  Author
Natalie Awinja
Computer Science Student, Multimedia University of Kenya
GitHub: @Keli281