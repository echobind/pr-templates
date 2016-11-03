## Pull Request Templates

### Purpose

Adding a pull request template to your project helps add clarity around
contributing guidelines. The template helps enforce consistency and
transparency around contributions to your code base. By supplementing your
pull request with a detailed description, you help the contributor aggregate
their work into a meaningful summary while providing more context for the
code reviewer.

This repo was created to share properties of a pull request description we
consider to be useful during our code review process. We've taken some
time to split these templates based on the type of project (e.g backend,
frontend, open source library, etc...). Please feel free to use these templates
within your own projects, and share with us by contributing to this project.

### Installation

Check out your default branch, most of the time this is `master`:

`git checkout master`

Create a `.github` directory:

```
mkdir .github && cd .github
```

Once thats created, you need to download the template from this repo. To
download the template you would like to use, you can run the following
cURL command:

```
curl -O https://raw.githubusercontent.com/echobind/pr-templates/master/frontend/PULL_REQUEST_TEMPLATE
```

Every template is named `PULL_REQUEST_TEMPLATE` for easy installation, so you
just need to update the path in order to retrieve the correct template.

### Copyright (c)

## Legal
[Echobind](https://echobind.com) LLC (c) 2016
[@echobind](https://twitter.com/echobind)
[Licensed under the MIT license](http://www.opensource.org/licenses/mit-license.php)
