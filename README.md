## Pull Request Templates

### Purpose

Adding a pull request template to your project helps add clarity around contributing guidelines. By creating a template, contributors gain transparency into the information that is required and/or optional to supplement their code review.

This repo was created to share some of the properties of a pull request we consider to be useful during a code review. We've taken some time to split these templates based on the type of project (e.g backend, frontend, open source library, etc...). Please feel free to use these within your own projects, and share with us by contributing to this project.

### Installation

Check out your default branch, most of the time this is `master`:

`git checkout master`

Create a `.github` directory:

```
mkdir .github && cd .github
```

Once thats created, you need to download the template from this repo. To download the template you would like to use, you can run the following cURL command:

```
curl -O https://github.com/echobind/pr-templates/blob/master/frontend/PULL_REQUEST_TEMPLATE
```

Every template is named `PULL_REQUEST_TEMPLATE` for easy installation, so you just need to update the path in order to retrieve the correct template.

### Copyright (c)

## Legal
[Echobind](https://echobind.com) LLC (c) 2016
[@echobind](https://twitter.com/echobind)
[Licensed under the MIT license](http://www.opensource.org/licenses/mit-license.php)
