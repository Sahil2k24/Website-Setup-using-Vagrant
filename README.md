# Website-Setup-using-Vagrant

This repository provides instructions and scripts to set up a website using Vagrant, GitBash, Apache HTTP Server (httpd), and a template from tooplate.com.

## Prerequisites

Before you begin, make sure you have the following software installed on your system:

- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/)
- [Git](https://git-scm.com/downloads)
- [wget](https://www.gnu.org/software/wget/)
- [Apache HTTP Server (httpd)](https://httpd.apache.org/download.cgi)

## Usage

Follow these steps to set up your website:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
2. Change into the project directory.
3.Initialize and provision the Vagrant environment.
4. SSH into the Vagrant virtual machine:
5. Inside the Vagrant VM, navigate to the website directory.
6. Download the website template from tooplate.com or place your HTML/CSS files here.
7. Start the Apache HTTP Server.
8. Your website should now be accessible at http://localhost:8080 from your host machine or you can get the IP address of the vagrant machine and get the view of the website from your browser.


Customization
You can customize the website template and content to fit your needs. Remember to update the Apache HTTP Server configuration as necessary.

Troubleshooting
If you encounter any issues during the setup process, please refer to the Vagrant and httpd documentation for troubleshooting steps.
Make sure your firewall or security software isn't blocking port 8080, which is the default port used by Apache HTTP Server
