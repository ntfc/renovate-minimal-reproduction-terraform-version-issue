# minimal-reproduction-template

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

Consider a terraform project using a `.terraform-version` file to pin the terraform version as well as the `required_version` block in terraform file.

Also consider the project might be running several major versions behind.

The goal is to gradually update the project to the latest terraform version.

## Current behavior

When current terraform is several major versions behind, I would expect renovate to suggest one Pull Request per major update. Each Pull Request should update both `.terraform-version` and the `required_version` block in the terraform files.

## Expected behavior

When current terraform is several major versions behind, I would expect renovate to suggest one Pull Request per major update. Each Pull Request should update both `.terraform-version` and the `required_version` block in the terraform files.

## Link to the Renovate issue or Discussion

Put your link to the Renovate issue or Discussion here.
