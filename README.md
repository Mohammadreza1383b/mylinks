### Share Your Links

[![Version](https://img.shields.io/badge/version-0.0.1-blue.svg)](https://github.com/tu_usuario/tu_repositorio)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

![Portada](/public/img/portada.png)
#### Description

Welcome to Share Your Links! This project is powered by Astro and CSS magic. If you're looking to create a sleek and customizable page to showcase all your important links, you're in the right place!

You can find this template in [Astro Themes](https://portal.astro.build/themes/shareyourlinks/)

#### Quick Links

Find all relevant links, including social media and websites, in one place: [Share Your Links](https://example.com/share-your-links)

#### Installation

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.

## Usage

Get started in no time:

- **Development**: Run `npm run dev` or `npm start` to start the development server.
- **Build**: Use `npm run build` to generate a production build.
- **Preview**: Run `npm run preview` to preview the production build.
- **Astro CLI**: Explore additional Astro CLI commands using `npm run astro`.
### Updating User Links

To customize the links displayed in your application, follow these steps:

1. Open the `src/data.js` file in your project.
2. Locate the section containing the information of the user links (`userLinks`).
3. Modify each object within the `userLinks` array with the information you want to display. You can change the link title, the link itself, and the associated icon.
4. Save the changes in the `data.js` file.

Here's an example of how you can change the information of the links:

```javascript
const userLinks = [
    {
        title: "My website",
        link: "https://mywebsite.com",
        icon: "ant-design:global-outlined"
    },
    {
        title: "Personal blog",
        link: "https://blog.mywebsite.com",
        icon: "fa-solid:book"
    },
    {
        title: "Contact",
        link: "mailto:email@example.com",
        icon: "bi:chat-right-dots"
    },
]
```

5. Once you have updated the information of the links in the `data.js` file, the changes will be automatically reflected in your application when you rebuild or run it.

Remember to ensure you provide valid links and that the icons used are available in the icon library you are using in your project.
#### Customization

Feel free to modify this project to suit your needs! Whether it's changing the layout, adding new features, or tweaking the styles, let your creativity flow.

#### Author

- SofiDev

#### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to explore, modify, and make it your own!