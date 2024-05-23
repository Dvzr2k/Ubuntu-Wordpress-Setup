# WordPress Setup with Vagrant

This repository contains a Vagrant configuration for setting up a WordPress environment on a Linux server, applying principles of Infrastructure as Code (IaC). The setup includes provisioning a virtual machine, installing necessary packages, and configuring WordPress with Apache and MySQL.

## Features

- **Automated Setup**: Utilizes Vagrant to automatically configure a development environment.
- **Infrastructure as Code**: Configuration and provisioning scripted for consistency and reproducibility.
- **Apache Web Server**: Configured to serve the WordPress application.
- **MySQL Database**: Set up with a dedicated database and user for WordPress.
- **Provisioning Scripts**: Installs and configures required software packages and settings.

## Prerequisites

- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

## Usage

1. Clone this repository to your local machine.
   git clone https://github.com/Dvzr2k/Ubuntu-Wordpress-Setup.git
3. Run the following commands to create and configure the virtual machine.
   ```sh
   git clone https://github.com/yourusername/wordpress-vagrant-setup.git
   cd Ubuntu-wordpress-setup-main
   vagrant up
   
5. Access the assigned IP address of the virtual machine from the Vagrantfile.
   ![image](https://github.com/Dvzr2k/Ubuntu-Wordpress-Setup/assets/129244345/2db151fa-379b-4a62-93a1-3b50a1f96073)


Enjoy developing!


