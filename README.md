# Atri Templates
Common requirements in frontend that are packaged in ready-to-use form. 

## Existing Templates

### Navigation bar that has three columns
templates/layout/three_col_navbar.json

![navbar](static/navbar.png)

## How to use a template?

1. Copy contents of the JSON file from this repository. 

For example, if you want to use `card` template in `atri-templates/templates/layout/card.json`, copy its contents by clicking on the `Copy raw contents` icon in GitHub. 

2. Create a new JSON file inside a corresponding folder (e.g. `basics`, `layout`, etc.) in `atri_templates` directory in your Atri app root directory. 

Continuing with our example, create a `atri-templates/layout/card.json` and paste the contents of the file here. 

We will be releasing a CLI in our future versions to make this process easier. Stay tuned!

## How to contribute?

1. Create a [fork of this repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository). 

2. [Clone](https://docs.github.com/en/get-started/quickstart/contributing-to-projects#cloning-a-fork) your fork. 

```shell
# Clone your fork of the repo into the current directory
git clone https://github.com/Atri-Labs/atri-templates.git
```

3. Configure the remotes. 

```shell
# Navigate to the newly cloned directory
cd atri-templates

# Assign the original repo to a remote called "upstream"
git remote add upstream https://github.com/Atri-Labs/atri-templates.git
```

4. Add JSON file for a template in `basics` or `layout` folder or create a new folder. 

5. Add the snapshot of the template in this Readme. 

6. Open a [Pull Request (PR)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) with clear title and description.