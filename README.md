# Conftee

Conftee is an open-source web application designed to parse submitted Cisco IOS-XE configurations locally, providing users with a safe and secure environment to analyze their configurations.

## Features

- **Local Parsing**: Conftee ensures that all configurations are parsed locally, guaranteeing the safety and confidentiality of sensitive network information.
- **Cisco IOS-XE Support**: Conftee is specifically tailored to parse configurations written in the Cisco IOS-XE syntax.
- **Visual Display**: The parsed configuration is displayed using a combination of Svelte and jQuery, offering an intuitive and interactive interface for users to explore their configurations.

## How it Works

1. **Submission**: Users submit their Cisco IOS-XE configuration file through the web interface.
2. **Parsing**: Conftee parses the submitted configuration file locally within the user's browser, ensuring that no data is transmitted over the network.
3. **Visualization**: The parsed configuration is then displayed using Svelte and jQuery, providing users with a structured and readable representation of their configuration.

## Usage

To use Conftee, simply follow these steps:

**Public Version**
1. Visit [Conftee.com](https://conftee.com)

**Self Hosted Version**
1. Clone this repository to your local machine.
2. Open the `index.html` file in your preferred web browser.

## License

Conftee is licensed under the [MIT License](LICENSE).
