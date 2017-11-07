# The Leap day theme

[![Build Status](https://travis-ci.org/pages-themes/leap-day.svg?branch=master)](https://travis-ci.org/pages-themes/leap-day) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-leap-day.svg)](https://badge.fury.io/rb/jekyll-theme-leap-day)

*Leap day is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/leap-day), or even [use it today](#usage).*

![Thumbnail of leap-day](thumbnail.png)

## Usage

To use the Leap day theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-leap-day
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```



## Customizing

### Configuration variables

Leap day will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

<h1>Studying interactively with Python</h1>

Lessons based on the Cambridge lower secondary curriculum for teenagers from 11 up to 15 years old. 

<div>
  <ul>
    <li><b>First Lesson:</b> Instalation and basic instructions about Jupyter notebook and Python.</li>
    <li><b>Second Lesson:</b> Integers, Powers and Roots - with an example of algorithm to calculate compound interest.</li>
  </ul>  
</div>

As new classes are being added the list above will be updated.

The content exhibited at the website is slightly different from the content available at the notebooks. I am using this feature to make it more interesting for teenagers. But if you want to interact with the codes it is necessary to download the notebooks and follow the instructions.

The first instruction is: download the package Anaconda to be able to interact with the codes. You can use this <a href="https://www.anaconda.com">link</a>. After the installation, you need to launch the module named "Jupyter Notebook". If you only need to see the content inside of the notebooks you just need to click on the files listed at the github or you can open it using an external viewer named "nbviewer". You can find it using this <a href="https://nbviewer.jupyter.org">link</a>. To open the notebook, copy and paste the address of the page.

You can create a new notebook and add only the codes you are interested to test or you can use the notebooks I have created by restarting the  "Kernel" at the upper toolbar. Look at the <a href="https://github.com/raquelsilva/programming_for_teens/wiki/First-step">wiki</a> how to do it.

If you have questions, feel invited to contact me.
