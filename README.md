<h3 align="center">
  Gatsby Nice Blogs
</h3>

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the nice blogs boilerplate template.

    ```shell
    gatsby new <site-name> https://github.com/abhaynikam/gatsby-nice-blog
    ```

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-blog-starter/
    gatsby develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!


## 🧐 Configure your details

Add your personal details in the `config.js` and restart the server to reflect your changes.

```js
module.exports = {
  url: `Your blog site root url`,
  description: `Your blog site description`,
  pathPrefix: 'Useful when using Github Pages. Add the repository name here.',
  title: `Your blog site title`,
  disqusShortname: 'Your disqus short name to enable comments',
  postsPerPage: 15,
  googleAnalyticsId: 'Your google analytics id',
  useKatex: false,
  author: {
    name: `Your name`,
    summary: `Short summary`,
    social: {
      twitter: `Your twitter account username`,
      github: `abhaynikam`,
    },
  }
};
```

## 🎨 Configure theme color
Update the `--color-primary` color variable to the desired theme primary color.

## 🚢 Deploying using Github page

1.  **Update pathPrefix.**

    Update the `pathPrefix` to the GitHub repository name.

    ```js
    module.exports = {
      pathPrefix: '',
      ...
    }
    ```
2.  **Deploy to GitHub pages!**

    ```shell
    yarn run deploy
    OR
    npm run deploy
    ```

## 🚢 Deploying using Netlify

- Login/Signup to the Netlify GitHub account.
- Authorize the repository access.
- Configure the custom domain on Netlify.


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/abhaynikam/boring_generators. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/abhaynikam/gatsby-nice-blog/blob/master/CODE_OF_CONDUCT.md).

## License

The boilerplate blog template is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Author
[Abhay Nikam](https://www.abhaynikam.me/pages/about)
