## How to contribute

1. Fork the project
2. Make any changes in your forked repository
3. On this repository, click `Pull Requests` and raise a `Pull Request` selecting your fork on the right drop down

Questions can be asked by raising an `Issue`.

## How to clone repository and make changes locally

- Click on the clone button (green in colour). This gives you a copy of the project. You can now make changes to the project.

- Using Git on your local machine. Do this to download the forked copy of this repo to your computer.

```
  git clone https://github.com/rwiteshbera/Awesome-Github-Profiles
```

- switch to the cloned folder. This can be done with Gitbash or the integrated terminal in the VSCode editor.

```
  cd Awesome-Github-Profiles
```

- Add a reference(remote) to the original repository.
```
  git remote add upstream https://github.com/rwiteshbera/Awesome-Github-Profiles
```

- Check the remotes for this repository
```
  git remote -v
```

-  Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).
```
    git pull upstream main
```

- Make a new branch. Your name would make a good branch because it's unique.

```
  git checkout -b <name of new branch>
```

- Open the `README.md` file

- Add your name to the section [Awesome Github Profiles](README.md#awesome-github-profiles) that is headed with your first letter. Then, add your name in alphabetical order of the second letter in your name. If the second letters are the same, order it in alphabetical order of the third, and so on. Next to it, add the link to your github username page.

- For example ,
  `- [Full Name](https://github.com/your-username)`

- Stage your changes.

```
  git add README.md
```

or

```
  git add .
```

- Commit the changes.

```
  git commit -m "Add <your-github-username>"
```

- Check the status of your repository.

```
  git status
```

- Pushing your repository to GitHub.

```
  git push origin <name of your branch>
```

- Create a pull request on the original repository.
To create a pull request, click on compare and pull requests. Please ensure that you compare your feature branch to the desired branch of the repo you are supposed to make a PR to

- Add an appropriate title and description to your pull request explaining your changes and efforts done.

- Click on Create Pull Request

- Wait for your changes to be merged.

Hurray! You successfully made a contribution! 🎉

---