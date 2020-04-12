# gatsby-remark-ruby

This is a very simple wrapup of remark plugin [remark-ruby](https://github.com/laysent/remark-ruby), so that it can be used in [Gatsby](https://www.gatsbyjs.org/) directly.

## Installation

```bash
yarn add --dev gatsby-transformer-remark gatsby-remark-ruby
```

## Configuration

In `gatsby-config.js` file, write the following:

```javascript
{
  resolve: `gatsby-transformer-remark`,
  options: {
    plugins: [
      {
        resolve: `gatsby-remark-ruby`,
        options: {
          parenthesis: '()',
        },
      },
    ],
  },
}
```
