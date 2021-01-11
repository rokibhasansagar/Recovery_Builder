# Building recovery online made easy

## What this is

This is an easy way for recovery maintainers or anyone who's interested in building recoveries to finish their dream without a server.

### How to use

Here are some useful notes for using this tool.

- [x] Fork this repository.

- [x] Add your github access token as `GH_TOKEN` in repository secrets.

- [x] Set the variables inside workflow file under jobs.build.env key, as listed below and push.

  ```text
  GitHubMail: Your Github email address
  GitHubName: Your Github username
  manifest_url: Link to your recovery manifest
  manifest_branch: Specific branch of the manifest to use
  dt_link: Link to your recovery device tree
  dt_br: Specific branch of your device tree to use [Optional]
  vendor: Device vendor/company name as used in device tree
  codename: Device codename as used in device tree
  kernel_link: Link to your kernel source [Optional]
  kernel_br: Specific branch of kernel source [Optional]
  flavor: Build flavor, as in eng or userdebug
  target: Build target, as in recoveryimage or bootimage
  ```

- [x] Go to Actions tab, enable workflows if not already running.

- [x] Push any changes to workflow file to trigger a new build. You can also trigger build on last commit on-demand as workflow_dispatch is enabled.

### Credits

- [x] Initially made by [_Jamie_](https://t.me/henloboi)
- [x] Infinite help from [_ElytrA8_](https://t.me/ElytrA8)
- [x] Recovery building help from [_Pulkit_](https://t.me/Pulkit077)
- [x] Workspace Cleaner & Build Environment Initializer, by [_rokibhasansagar_](https://t.me/fr3akyphantom)
  > rokibhasansagar/slimhub_actions@main and rokibhasansagar/build-env_actions@main
- [x] Recovery build script modified by @rokibhasansagar

Enjoy Building Recoveries.
