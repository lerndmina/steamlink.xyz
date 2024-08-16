# Steam Link Converter

Welcome to the Steam Link Converter! This project allows you to generate shareable Steam links that instantly open Steam with just a click. It utilizes Astro for the static site generation, Tailwind CSS for styling, and Bun for package management and build tasks.

## Table of Contents

- [Steam Link Converter](#steam-link-converter)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Steps](#steps)
  - [Usage](#usage)
    - [Development](#development)
    - [Build](#build)
    - [Preview](#preview)
  - [Deployment](#deployment)
  - [Contributing](#contributing)
  - [License](#license)

## Installation

To get started with this project, you'll need to set up your environment and install the necessary dependencies.

### Prerequisites

- [Bun](https://bun.sh/) (for package management and building)

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/lerndmina/steamlink.xyz
   cd steamlink.xyz
   ```

2. **Install Dependencies**

   Use Bun to install the project dependencies:

   ```bash
   bun install
   ```


## Usage

Once you have the project set up, you can run it locally to see the site in action.

### Development

To start a local development server:

```bash
bun run dev
```

This will start the development server and open the site in your default web browser. The server supports hot-reloading, so changes to your files will be reflected in real-time.

### Build

To build the project for production:

```bash
bun run build
```

This command generates static files optimized for production and places them in the `dist` directory.

### Preview

To preview the production build locally:

```bash
bun run preview
```

This will serve the static files from the `dist` directory, allowing you to see how your site will look in production.

## Deployment

This project is set up to be deployed to Cloudflare Pages. You can deploy it to other platforms as well, but you may need to adjust the configuration files accordingly.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README further to better fit your project specifics and needs!