# Virtuoso Grandchild - Child theme customization plugin 

## Description
The purpose of this plugin is to enable users to safely update child themes without losing customizations made to the child theme. Since WordPress doesn't support grandchild themes (for good reason), this is one way to allow users to add custom CSS that won't be overwritten if a child theme is updated.

## Dependencies

This plugin is dependent upon the following:

1. [virtuoso child theme](https://github.com/ErhardLabs/virtuoso)

## Instructions to install:

1. Open up terminal and navigate to the `plugins` folder.
2. Then type: `git clone https://github.com/ErhardLabs/virtuoso-grandchild.git`
3. Navigate into the new folder `virtuoso-grandchild`
4. Compile your assets in the virtuoso theme

## Sass Files

To make styling changes, navigate to `assets/sass`.  There you will find each of the partial files which contain the CSS styling.

Changes to the styles in the grandchild plugin will override theme styles. No need to use `!important` tags


## Contributions

Feedback, bug reports, and pull requests are welcome.
