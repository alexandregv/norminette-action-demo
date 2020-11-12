# norminette-action demo

This is a simple demo for [norminette-action](https://github.com/alexandregv/norminette-action), a GitHub Action for 42School's norminette linter.

## Demo

You can see two C files, ok.c and ko.c, which are obviously a correct and incorrect file regarding to 42's Norm.  

The third and only important file is [.github/workflows/main.yml](.github/workflows/main.yml), which contains CI workflow.  
Here I defined two jobs, each for one version of the Norm. The only difference is `@v2`/`@v3` on lines [11](https://github.com/alexandregv/norminette-action-demo/blob/master/.github/workflows/main.yml#L11) and [18](https://github.com/alexandregv/norminette-action-demo/blob/master/.github/workflows/main.yml#L11).  

You can check CI results on each commit, or with the Actions button at the top of the repository.

![Screenshot](screenshot.jpg)
