# The default JavaScript Actions quickstart
To quickly have an environment to make & test JavaScript actions. It uses the basic JavaScript action from [this tutorial](https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action). To get started, just follow the instructions the [Usage section](https://github.com/PrLemon/js-action-template-repo/blob/main/README.md#usage).

💡 If you're using Codespaces, this repo contains a devcontainer file that makes it faster to be able to start using this project. The Codespace is configured to install the Actions libraries and `ncc` to distribute this easily.

## Usage:

### Prepare: 
- Click on the Use this template button and create a copy for yourself

#### If using your local Dev Environment:
- Clone this to your local
- Run a `npm i -g @vercel/ncc`
- Run `npm i -g @actions/github`
- Run a `npm i -g @actions/core`

#### If using a GitHub Codespace
- Spin up your Codespace

### Use:
- Modify the `action.yml` file to use the inputs you will be using
- Modify `src/index.js` 
- Build by running 
```
ncc build src/index.js --license licenses.txt
```
- Commit everything
- Go to the Actions tab to run this workflow manually

### Examples
In this Repo - [PrLemon/calculator-action](https://github.com/PrLemon/calculator-action), we have used this template as a base and then gone on to modify the `action.yml` and `src/index.js`; rebuilt it and it now works as a Calculator action instead of our simple Hello World!
