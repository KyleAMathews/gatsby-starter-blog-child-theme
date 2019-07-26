<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Starter for creating child themes for gatsby-theme-blog
</h1>

## Getting started

1. Create the repo locally

`gatsby new gatsby-theme-NAME KyleAMathews/gatsby-starter-blog-child-theme`

2. Run yarn to setup workspace

`yarn`

3. Run the starter and start developing on the theme!

`yarn workspace starter gatsby develop`

Try changing colors at `gatsby-theme-*/src/gatsby-plugin-theme-ui/colors.js` and typography options at `gatsby-theme-*/src/gatsby-plugin-theme-ui/typography.js`

## Publishing theme

1. If you haven't already done so, rename folders and strings from gatsby-theme-RENAME_ME to the name of your theme
2. In your terminal, navigate to the directory for the theme
3. `yarn publish`
