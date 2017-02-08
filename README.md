# Front End Developer Tools for Windows

The purpose of this project is to provide a "one-click" solution for provisioning a Windows environment for front end development. By automating this setup, we can ensure that the software is installed and configured correctly and can be repeated easily across both local and remote machines.

The installation scripts were created with the help of [Boxstarter][2] and [Chocolatey][3].

## Usage

The following script will install:

- Latest version of Node.js
- npm
- Python 2.7
- Microsoft Visual C++ Build Tools 2015

### Install from Internet Explorer

Navigate to this page in Internet Explorer and click on the following link: [Launch Installer][1]


### Install from console (PowerShell or CMD)

```
START http://boxstarter.org/package/nr/url?https://gist.githubusercontent.com/davepenfold/c6db3a3a106a1aeb884f825f918c7572/raw/efa0a9de2dcc753e9c4e79159ac73db8cc062f73/gistfile1.txt
```

## Test

Once installation is complete you may want to install some packages via npm to confirm your tools are working correctly. This project comes with a `package.json` file which can be used for this test.

- Download this repository: [Download][4]
- Extract the downloaded zip file.
- From your console (PowerShell or CMD), navigate to the extracted folder. Make sure you're in the folder where the `package.json` file is located.
- Run the following command: `npm install`


[1]: http://boxstarter.org/package/nr/url?https://gist.githubusercontent.com/davepenfold/c6db3a3a106a1aeb884f825f918c7572/raw/efa0a9de2dcc753e9c4e79159ac73db8cc062f73/gistfile1.txt
[2]: http://boxstarter.org
[3]: https://chocolatey.org
[4]: https://github.com/davepenfold/devtools-windows/archive/master.zip
