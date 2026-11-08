:root {
  --bg: #faf6f0;
  --text: #3b3632;
  --muted: #8a7f74;
  --accent: #7a8b69;
  --line: #e6ddd0;
}

* { box-sizing: border-box; }

body {
  margin: 0;
  background: var(--bg);
  color: var(--text);
  font-family: Georgia, "Times New Roman", serif;
  line-height: 1.75;
  font-size: 1.125rem;
}

.wrap {
  max-width: 640px;
  margin: 0 auto;
  padding: 0 1.25rem;
}

header {
  padding: 3rem 0 1.5rem;
  border-bottom: 1px solid var(--line);
  margin-bottom: 2.5rem;
}

.site-title {
  font-size: 1.75rem;
  letter-spacing: 0.04em;
  margin: 0;
  font-weight: normal;
}

.site-title a { color: var(--text); text-decoration: none; }

.tagline {
  color: var(--muted);
  font-style: italic;
  margin: 0.25rem 0 1.25rem;
  font-size: 1rem;
}

nav a {
  color: var(--accent);
  text-decoration: none;
  margin-right: 1.25rem;
  font-size: 0.95rem;
  letter-spacing: 0.05em;
  text-transform: lowercase;
}

nav a:hover { text-decoration: underline; }

h1, h2, h3 { font-weight: normal; line-height: 1.3; }
h1 { font-size: 2rem; margin-top: 0; }
h2 { font-size: 1.4rem; margin-top: 2.5rem; }

a { color: var(--accent); }

.post-list { list-style: none; padding: 0; margin: 0; }
.post-list li { margin-bottom: 2rem; }
.post-list .date { color: var(--muted); font-size: 0.9rem; }
.post-list h2 { margin: 0.1rem 0 0.4rem; font-size: 1.4rem; }
.post-list h2 a { text-decoration: none; color: var(--text); }
.post-list h2 a:hover { color: var(--accent); }
.post-list p { margin: 0; color: var(--muted); }

.post-meta { color: var(--muted); font-size: 0.9rem; margin-bottom: 2rem; }

blockquote {
  border-left: 3px solid var(--accent);
  margin: 1.5rem 0;
  padding-left: 1.25rem;
  color: var(--muted);
  font-style: italic;
}

.product {
  border: 1px solid var(--line);
  border-radius: 6px;
  padding: 1rem 1.25rem;
  margin: 1.25rem 0;
  background: #fffdf9;
}

.product h3 { margin: 0 0 0.25rem; font-size: 1.15rem; }
.product p { margin: 0.25rem 0 0.5rem; font-size: 1rem; }

.disclosure {
  font-size: 0.9rem;
  color: var(--muted);
  border-top: 1px solid var(--line);
  padding-top: 1rem;
  margin-top: 2rem;
}

footer {
  margin: 4rem 0 3rem;
  padding-top: 1.5rem;
  border-top: 1px solid var(--line);
  color: var(--muted);
  font-size: 0.9rem;
}
