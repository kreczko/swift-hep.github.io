# SWIFT-HEP Project Website

Repository for the [Offical SWIFT-HEP Project Website](https://swift-hep.github.io).

## Making changes

To make changes, just fork and make Pull Requests. The site is built using
[Hugo](https://gohugo.io), so see their documentation for:

- [Installing Hugo](https://gohugo.io/getting-started/installing/) - make sure to install an `extended` version (e.g. from [here](https://github.com/gohugoio/hugo/releases))
- [Building/Viewing the site locally](https://gohugo.io/getting-started/usage/#livereload)
- [Site Configuration](https://gohugo.io/getting-started/configuration/)

See the remainder of the [Hugo Documentation] under the "Getting Started" and "Content Management" sections for details on adding content such as pages, images, and other items.

For adding new pages, please use the corresponding `hugo new` command and the documents will be placed in the correct place.

## Updating bootstrap

```bash
npm install bootstrap --save
# or
# npm install bootstrap@<version> --save
```
to install the latest version of bootstrap in `node_modules`.