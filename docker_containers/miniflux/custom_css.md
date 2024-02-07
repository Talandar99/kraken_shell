## just paste it in settings
```css
:root {
  --font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --body-color: rgba(255, 255, 255, 0.7);
  --body-background: #282c34;
  --header-link-color: #9b9494;
  --header-active-link-color: #d19a66;
  --input-border: 1px solid #2c384e;
  --input-background: #2c384e;
  --input-placeholder-color: #888;
  --input-focus-border-color: #d19a66;
  --input-focus-box-shadow: none;
  --category-background-color: #2c384e;
  --category-border-color: #2c384e;
  --item-border-color: rgba(0, 0, 0, .3);
  --item-padding: 1em;
  --item-title-link-font-weight: 600;
  --item-status-read-title-link-color: rgba(209, 154, 102, 0.5);
  --entry-header-title-link-color: #d19a66;
  --entry-content-code-background: #2c384e;
  --entry-content-code-border-color: #2c384e;
  --entry-content-font-weight: 300;
  --entry-content-font-family: 'Literata', 'Libre Baskerville', Georgia, 'Times New Roman', Times, serif !important;
  --entry-content-quote-font-family: var(--entry-content-font-family)
}

*:focus {
  outline: 0 !important;
}

input[type="search"],
input[type="url"],
input[type="password"],
input[type="text"],
input[type="number"] {
  padding: .25em .5em;
  box-shadow: none;
  border-radius: 6px;
}

.entry header h1 {
    margin: 1em 0 16px;
}

.entry-actions {
    opacity: .5;
}
.entry-meta {
  color: #98be65;
}

.entry-website a {
  color: #c678dd;
}

.entry-date {
  font-size: .75em;
  color: rgba(255, 255, 255, 0.4);
}

.entry-actions li a {
  font-weight: bold;
  color: #9b9494;
}

.entry-actions li a:hover {
  font-weight: bold;
  color: white;
}

.entry header h1 a:hover,
.entry header h1 a:focus {
  color: #d19a66;
  text-decoration: underline;
}
.pagination-top {
    display: none;
}
.entry-content {
  line-height: 2;
  padding-top: 2em;
}

.entry-content p {
  margin-top: 0;
  margin-bottom: 1em;
}

.entry-content a {
  color: #c678dd;
}

.entry-content a:visited {
  color: #dd7890;
}

.entry-content img {
  width: 100%;
  margin: 0 auto;
}

.entry-content figcaption {
  color: #c678dd;
  background-color: rgba(0, 0, 0, .3);
  margin-top: -7px;
  border-radius: 0 0 4px 4px;
  padding: 0.25rem 1rem;
  text-transform: unset;
}

.entry-content pre {
  padding: .5rem 1rem;
  border-radius: 6px;
  margin: 0 0 1em;
}

.entry-content code {
  padding: 3px;
  border-radius: 6px;
}

.item,
.alert {
  border: 1px solid var(--item-border-color);
  margin-bottom: 20px;
  background: rgba(0, 0, 0, .3);
  border-radius: 6px;
}

.item-title a {
  color: #d19a66;
}

.item-meta-info {
    padding-top: 2px;
}

.item-meta-info li a {
  color: #c678dd;
}

.item-meta-info li time {
    color: #98be65;
}
.item-meta-info li span {
    color: #61afef;
}

.entry-content li {
  margin: .75em 0;
}
```
