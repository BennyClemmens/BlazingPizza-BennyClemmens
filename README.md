
# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.

# Benny

## Repo

This is a clone of <https://github.com/MicrosoftDocs/mslearn-interact-with-data-blazor-web-apps> as described in <https://learn.microsoft.com/en-us/training/modules/interact-with-data-blazor-web-apps/3-exercise-create-user-interfaces-with-blazor-components>, which i covered in <https://github.com/BennyClemmens/BlazingPizzaSite>

```bash
Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   BlazingPizza.csproj
        modified:   Properties/launchSettings.json

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        BlazingPizza.sln

no changes added to commit (use "git add" and/or "git commit -a")

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git remote -v
origin  https://github.com/MicrosoftDocs/mslearn-interact-with-data-blazor-web-apps.git (fetch)
origin  https://github.com/MicrosoftDocs/mslearn-interact-with-data-blazor-web-apps.git (push)

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git remote remove origin

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git remote -v

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git remote add origin https://github.com/BennyClemmens/BlazingPizza-BennyClemmens.git

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git add .
warning: in the working copy of 'BlazingPizza.sln', CRLF will be replaced by LF the next time Git touches it

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git commit -m 'initial commit BlazingPizza-BennyClemmens'
[main ff68bea] initial commit BlazingPizza-BennyClemmens
 3 files changed, 27 insertions(+), 2 deletions(-)
 create mode 100644 BlazingPizza.sln

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
$ git push --set-upstream origin main
Enumerating objects: 83, done.
Counting objects: 100% (83/83), done.
Delta compression using up to 8 threads
Compressing objects: 100% (64/64), done.
Writing objects: 100% (83/83), 897.17 KiB | 179.43 MiB/s, done.
Total 83 (delta 17), reused 74 (delta 14), pack-reused 0
remote: Resolving deltas: 100% (17/17), done.
To https://github.com/BennyClemmens/BlazingPizza-BennyClemmens.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP/BlazingPizza (main)
```

Creating consistency in directory structure.

```code
Benny@FLAB2021 MINGW64 /c/DATA/GIT/CSHARP
$ mv BlazingPizza/ BlazingPizza-BennyClemmens/
```
