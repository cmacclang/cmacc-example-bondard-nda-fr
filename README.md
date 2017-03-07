# cmacc-example-bondard-nda-fr

This example is to show how the data binding works:
- copy the directory locally (2 files really, the DataBinding file and the package.json)
- do a yarn install in the local directory (assuming you have installed yarn, (see https://yarnpkg.com/lang/en/docs/install/#mac-tab if you have not)
- open Visual Studio Code (install from here  https://code.visualstudio.com/download, with installation instructions for the Cmacc plugin here https://marketplace.visualstudio.com/items?itemName=wilmveel.cmacc-vscode)
- in the DataBinding.cmacc file, do a "Ctrl Shft H" to visualize the full document.

Why this is useful?

Because the next time you want to do a deal, this is the structure of what your deal should look like:
- a template (here cmacc-form-bondard-nda-fr)
- a data binding file where you speficy the parameters for your deal.

The value of using Yarn is that if the files you are using keep evolving, the integrity of your document is preserved, because you track the dependencies, including which versions you are using in your deal. So new version can come out and it will not impact your deal. And then you can always decide to upgrade your forms in the next deal.
