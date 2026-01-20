<img src="https://raw.githubusercontent.com/maptiler/maptiler-sdk-kotlin/main/Examples/maptiler-logo.png" alt="Company Logo" height="32"/>

# Svelte map using MapLibre GL JS

A quick way to start a web map application with Svelte using MapLibre GL JS.

A simple fullscreen map application is used to showcase how to utilize MapTiler maps together with Svelte and MapLibre GL JS for your Svelte app.

[![](https://img.shields.io/npm/v/maplibre-gl?style=for-the-badge&labelColor=D3DBEC&color=f2f6ff&logo=npm&logoColor=333359)](https://www.npmjs.com/package/maplibre-gl)
![](https://img.shields.io/badge/-white?style=for-the-badge&logo=javascript)![](https://img.shields.io/badge/-white?style=for-the-badge&logo=typescript)![](https://img.shields.io/badge/-white?style=for-the-badge&logo=svelte&logoColor=ff3e00)

---

📖 [Documentation](https://docs.maptiler.com/svelte/) &nbsp; 🌐 [Website](https://www.maptiler.com/) &nbsp; 🔑 [Get API Key](https://cloud.maptiler.com/account/keys/)

---

<br>

<details> <summary><b>Table of Contents</b></summary>
<ul>
<li><a href="#-installation">Installation</a></li>
<li><a href="#-basic-usage">Basic Usage</a></li>
<li><a href="#-related-examples">Examples</a></li>
<li><a href="#-support">Support</a></li>
<li><a href="#-contributing">Contributing</a></li>
<li><a href="#-license">License</a></li>
<li><a href="#-acknowledgements">Acknowledgements</a></li>
</ul>
</details>

<p align="center">   <img src="./assets/svelte-maplibre-template.png" alt="Demo Screenshot" width="80%"/>
<br>

## 📦 Installation

Clone the repo to create a new Svelte project. Run in your command-line:

```shell
git clone https://github.com/maptiler/svelte-template-maplibre-gl-js.git my-svelte-map
```

This project was generated with

```shell
npx degit sveltejs/template my-svelte-project
```

<br>

## 🚀 Basic Usage

### Create an app

Navigate to the newly created project folder **my-svelte-map**

```shell
cd my-svelte-map
```

Install the NPM packages dependencies. Run in your command-line:

```shell
npm install
```

### API KEY

Rename or copy the `.env.example` file to `.env`

```shell
cp .env.example .env
```

Open the `.env` file, :warning: you will need to replace **YOUR_MAPTILER_API_KEY** with your own MapTiler API key.

Your MapTiler account access key is on your MapTiler [Cloud](https://cloud.maptiler.com/account/keys/) account page.

:information_source: If you don't have an API KEY, you can create it for free at https://www.maptiler.com/cloud/

### Run

To start your local environment, run:

```shell
npm run dev
```

You will find your app on address http://localhost:5000/.

Now you should see the app in your browser.

### Build

To build for production, run:

```shell
npm run build
```

### gh-pages

To deploy the app to the gh-pages branch, run:

```shell
node gh-pages.js
```

<br>

## 💡 Related Examples

- [How to display a map in Svelte using MapLibre GL JS](https://docs.maptiler.com/svelte/maplibre-gl-js/how-to-use-maplibre-gl-js/)
- [Get Started with Svelte and MapLibre GL JS](https://docs.maptiler.com/svelte/maplibre-gl-js/get-started/)
- [MapLibre GL JS geocoding control how to search places using Svelte](https://docs.maptiler.com/svelte/maplibre-gl-js/geocoding-control/)

Check out the full list of [MapTiler examples](https://docs.maptiler.com/svelte/examples/)

<br>

## 💬 Support

- 📚 [Documentation](https://docs.maptiler.com/svelte/) - Comprehensive guides and API reference
- ✉️ [Contact us](https://maptiler.com/contact) - Get in touch or submit a request
- 🐦 [Twitter/X](https://twitter.com/maptiler) - Follow us for updates

<br>

---

<br>

## 🤝 Contributing

We love contributions from the community! Whether it's bug reports, feature requests, or pull requests, all contributions are welcome:

- Fork the repository and create your branch from `main`
- If you've added code, add tests that cover your changes
- Ensure your code follows our style guidelines
- Give your pull request a clear, descriptive summary
- Open a Pull Request with a comprehensive description

<br>

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.

<br>

## 🙏 Acknowledgements

This project is built on the shoulders of giants:

- [MapTiler](https://www.maptiler.com/) – Maps for developers
- [MapLibre GL JS](https://maplibre.org/maplibre-gl-js/docs/) – Open-source TypeScript library for publishing maps on your website
- [Svelte](https://svelte.dev/) – Web development for the rest of us

<br>

<p align="center" style="margin-top:20px;margin-bottom:20px;"> <a href="https://cloud.maptiler.com/account/keys/" style="display:inline-block;padding:12px 32px;background:#F2F6FF;color:#000;font-weight:bold;border-radius:6px;text-decoration:none;"> Get Your API Key <sup style="background-color:#0000ff;color:#fff;padding:2px 6px;font-size:12px;border-radius:3px;">FREE</sup><br /> <span style="font-size:90%;font-weight:400;">Start building with 100,000 free map loads per month ・ No credit card required.</span> </a> </p>

<br>

<p align="center"> 💜 Made with love by the <a href="https://www.maptiler.com/">MapTiler</a> team <br />
<p align="center">
  <a href="https://www.maptiler.com/">Website</a> •
  <a href="https://docs.maptiler.com/svelte/">Documentation</a> •
  <a href="https://github.com/maptiler/get-started-svelte-maplibre-gl-js">GitHub</a>
</p>
