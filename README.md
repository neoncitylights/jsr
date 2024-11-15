# TypeScript package with JSR

This repository template allows writing TypeScript packages in pure ESM, and
publishing them to the JSR registry. It provides some default settings for a
relatively zero-config startup.

## Getting started

First, create a new repository. Choose your method:

- **GitHub UI**:
  [Click here](https://https://github.com/new?template_name=jsr&template_owner=neoncitylights)
  to use this template. (Or, you can either press "Use this template" button in
  the right-corner of this page)
- **GitHub CLI**:
  ```shell
  gh repo create --template neoncitylights/jsr --public --clone {{repository}} # clone as public
  gh repo create --template neoncitylights/jsr --private --clone {repository}} # clone as private
  ```

Then, in the [`LICENSE`](./LICENSE) file, change `{{author}}` to your username
or real name, whichever you prefer.

## License

This software is licensed under the MIT license ([`LICENSE`](./LICENSE) or
<https://opensource.org/license/mit/>).

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the MIT license, shall be
licensed as above, without any additional terms or conditions.
