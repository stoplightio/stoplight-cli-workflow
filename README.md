# Stoplight CLI Workflow
Use this workflow to push data to Stoplight CLI projects from your GitHub repository

## When will this push data?
When there's a push made to the `default branch` or branches starting with `design/` **OR** when a pull request is made in the repository on **any** branch

**AND**

When theres a change in `json`,`yaml`,`yml` or `md` files

## Using the Stoplight CLI Workflow

1. Create a `.gitub/workflows` folder in your repository
2. Copy the `stoplight-cli-workflow.yml` file into the `.gitub/workflows` folder you created in Step 1
3. Add your project CI token on Line 43. You can get the CI token from the project settings of a CLI project
4. Create a PR to see it work


