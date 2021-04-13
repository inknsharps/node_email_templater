# Email Generation Template

![APM](https://img.shields.io/apm/l/vim-mode) ![GitHub top language](https://img.shields.io/github/languages/top/inknsharps/node_email_templater)

## Description

This is an email template generator to help me deal with some purchase inquiry conformations that I make to customers on the daily. It makes use of the `open` npm package and opens up the email in the default mail application on your computer. 

While `nodemailer` would be a much more easier one stop option, unfortunately it did not play nicely with my office's authentication settings so opening a mailto URL was used instead. Some workarounds had to be done such as encoding the line breaks and $ characters.

## Installation

Make sure you have [node.js](https://nodejs.dev/) installed on your local machine, then clone or download the repository. Navigate to the copy of the repo in your CLI and run:

```
    npm install
```

This will install all the dependencies needed.

## Usage

Navigate to the folder of the repo and run in your CLI:

```
    npm start
```

You will then be prompted some `inquirer` questions which will then generate a mailto URL once you are finished. This will open automatically into your default email application.

## Issues

Feel free to open any [issues](https://github.com/inknsharps/node_email_templater/issues) as you come along them.