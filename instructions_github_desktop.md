# Adding Recipes to the Food-to-Fork Repository using GitHub Desktop

Aside from GitHub desktop, you will need a plain-text text editor. This could be Notepad on windows, or TextEdit on MacOS.  When using TextEdit, you must first configure it for plain text: Settings > New Document > 
Select `Plain text`.

1. In GitHub Desktop: Add a new repository > Clone repository > URL and enter `tiago-rorke/food-to-fork/`
2. Open the new local repository folder: `Show in your File Manager`
3. Make a new folder in the repository with the name of your recipe. Avoid using spaces in your recipe name.
4. Using a text editor, make a new markdown file in this folder containing your recipe, eg: `my_new_recipe.md`.  
To see your formatting in real-time, your can use an online markdown editor such as https://onlinemarkdown.com/, and then copy and paste this into your text editor.
5. You can add an image to the recipe either by embedding an image found online, or by adding your own image to the repository.  
When using images that are not your own, make sure these have a license that allows them to be used, and include any necessary credits.
6. Before committing your new recipe to the repository, ensure that the markdown document has the correct file extension (`.md`). You may new to configure your file browser to make extensions visible:
	- Windows File Explorer: View menu > Show > `Enable File name extensions`
	- MacOS Finder: Finder Settings > Advanced > Enable: `Show all filename extensions`
7. Once you are finished and have committed your new recipe, you can add this to the upstream repository by creating a new fork on GitHub, and making a Pull Request:
	1. In GitHub Desktop, select `Push origin`, then `Create a new Fork`, and `Contribute to the parent project`.
	2. On GitHub.com, go to your fork of the repository `your_username/food-to-fork`, and select `Pull requests` > `New pull request` > `Create pull request`
	3. Wait for an administrator of the original repository to review and merge your pull request.
8. Once your pull request has been merged, your recipe will be visible in the original `food-to-fork` repository!