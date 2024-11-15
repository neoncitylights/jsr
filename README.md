# TypeScript package with JSR

This repository template allows writing TypeScript packages in pure ESM, and
publishing them to the JSR registry. It provides some default settings for a
relatively zero-config startup.

## Getting started

First, create a new repository. Choose your method:

- **GitHub UI**:
  [Click here](https://github.com/new?template_name=jsr&template_owner=neoncitylights)
  to use this template. (Or, you can either press "Use this template" button in
  the right-corner of this page)
- **GitHub CLI**:
  ```shell
  # create a public or private repository from the template
  gh repo create --template neoncitylights/jsr --public --clone {{repository}}
  gh repo create --template neoncitylights/jsr --private --clone {{repository}}
  ```

Then, make sure to replace the following placeholders:
 - [`./LICENSE`](./LICENSE): change `{{author}}` to your username
or real name, whichever you prefer.
 - [`./deno.json`](./deno.json): change the package name to your own.
 - [`./github/workflows/publish.yml`](./github/workflows/publish.yml): Uncomment out the top so that the workflow will publish your package every time there's a commit pushed to `main` branch.

## License

This software is licensed under the MIT license ([`LICENSE`](./LICENSE) or
<https://opensource.org/license/mit/>).

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the MIT license, shall be
licensed as above, without any additional terms or conditions.
