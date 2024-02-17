# my-first-template-repo
Playground for github template repos.  __template repository__

* Repository Templates is a GitHub feature released in June 2019, which makes work with GitHub more efficient and enjoyable.
* Alternative could forking, but ...


## references
* [create github template repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository)
* [create from github template repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
* https://github.com/topics/template-repository
* https://www.linkedin.com/pulse/how-use-github-repository-templates-xopero-software-zjkyf/
* https://everhour.com/blog/github-templates/
* https://sparkbox.com/foundry/how_to_build_github_starter_templates_for_Eleventy_to_make_your_projects_easier

## notes
### Create template repo
You can create a template from an existing repository. Anyone with access to the template repository can create a new repository based on the template with the same directory structure, branches, and files..

To create a template repository, you must create a repository, then make the repository a template.

After you make your repository a template, anyone with access to the repository can generate a new repository with the same directory structure and files as your default branch. They can also choose to include all the other branches in your repository. Branches created from a template have unrelated histories

__Note__: Your template repository cannot include files stored using Git LFS.

__Note__: You can use a template repository as starter code for an assignment on GitHub Classroom. For more information, see [Create an assignment from a template repository](https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/create-an-assignment-from-a-template-repository)

?? what is starter code for assignment ?? https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/create-an-assignment-from-a-template-repository

click  Settings. -> template repo
![setting:repo template](/assets/images/gh-template-repo-settings.png)

### Create new repo from template repo
https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template

Creating a repository from a template is similar to forking a repository, but there are important differences:

* A new fork includes the entire commit history of the parent repository, while a repository created from a template starts with a single commit.
Commits to a fork don't appear in your contributions graph, while commits to a repository created from a template do appear in your contribution graph.
* A fork can be a temporary way to contribute code to an existing project, while creating a repository from a template starts a new project quickly.
* For more information about forks, see [About forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)

1. On GitHub.com, navigate to the main page of the repository.
1. Above the file list, click Use this template.
1. Select Create a new repository.
1. Use the Owner dropdown menu to select the account you want to own the repository.
1. Type a name for your repository, and an optional description.
1. Choose a repository visibility. For more information, see "About repositories."
1. Optionally, to include the directory structure and files from all branches in the template, and not just the default branch, select Include all branches.
1. Optionally, if the personal account or organization in which you're creating uses any GitHub Apps from GitHub Marketplace, select any apps you'd like to use in the repository.
1. Click Create repository from template.

https://github.com/moyshale/my-copy-of-first-template-repo-no-branches

## features
* Copy all of the files from the old repository to a new one.
* Every template has a new /generate URL endpoint.
* Share the repository template with your team or other GitHub users

## benefits
* Increases the speed of your routine tasks.
* Allows you to concentrate on more important aspects of your work.
* Makes configuration less manual.
* Permits to use boilerplate code in multiple codebases

## Quickstart

