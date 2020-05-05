# VuePress Plugin Zengarden Home

Creates homepage for your VuePress site.

## Installation

```bash
npm install -D vuepress-plugin-zengarden-home
# or
yarn add -D vuepress-plugin-zengarden-home
```

## Usage

Add the following to your `config.js` or `index.js` file.

```javascript
['zengarden-home', {
    title: 'Home',
    frontmatter: {
        layout: 'Home'
    }
}],
```