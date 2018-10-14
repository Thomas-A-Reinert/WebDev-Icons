# WebDev-Icons
A font to iconify a Webdevelopers Skills currently including 124 plain, monochrome Icons in Version 1.0. Including Programming Languages, Frameworks, Workflow Tools, Programs/IDE´s etc.

There are currently no Plans to include alternativ Versions and/or to integrate full colored Versions. There are other Alternatives for that.

# Alternatives
There is a bunch of pretty awesome font libraries that I can really recommend.

Problem is: None of them included all the icons I needed for my personal portfolio so I created my own.

If you´re looking for more font libraries that also include different versions for some of the icons or are even multi-colored, you should take a look at those libs:
* [Devicon 2.0](https://github.com/konpa/devicon/)
* [Devicons](http://vorillaz.github.io/devicons)
* [Technology Icons](https://github.com/websiddu/technology-icons)

## How to Use
* Upload webdev-icons.css (/dist/webdev-icons.css) and Font Files (/dist/fonts Folder) to your Site.

```html
  <link rel="stylesheet" href="webdev-git.css">
```

- Add the respective icon using an <i> tag

```html
  <!--  Example using Git-Icon -->
  <i class="webdev-git"></i>

    <!--
        Consider improving accessibility!
        In case you´re using e.g. Bootstrap you should use Icons this way:
    -->
  <i class="webdev-git">
      <span class="sr-only">Git</span>
  </i>

```

## Roadmap
* Adjustment / Finetuning of icon sizes
* Add SVG icon
* Add SVG Animation icon
* Add WCAG / WAI / BITV icons
* Consider switching from <i>-Tags to Classnames only
---

<sub>Final font is build with [Icomoon app](https://icomoon.io/)</sub>

## License and Legal Notice

Released under [GNU GENERAL PUBLIC LICENSE Version 2](https://github.com/Thomas-A-Reinert/WebDev-Icons/blob/master/LICENSE)

<sub>All product names, logos, and brands are property of their respective owners. All company, product and service names used in this project are for identification purposes only. Use of these names, logos, and brands does not imply endorsement.</sub>

<sub>If you belong to one of the companies or projects which brand got integrated in this font and feel that this project infringes your rights, please get in contact and I´ll consider removal.</sub>
