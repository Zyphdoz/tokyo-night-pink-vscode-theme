# Tokyo Night Pink
This is a fork of the [Tokyo Night Visual Studio Code theme](https://github.com/tokyo-night/tokyo-night-vscode-theme) which comes with a pink variant in addition to the three standard variants.
I like the original Tokyo Night, except for one thing: Variables, classes and types all have the same color ![#c0caf5](https://raw.githubusercontent.com/Zyphdoz/tokyo-night-pink-vscode-theme/refs/heads/master/static/c0caf5.gif) `#c0caf5` and I prefer not having the same color for all three of those.
The pink variant is the same as the standard Tokyo Night theme except that types are ![#cc7be2](https://raw.githubusercontent.com/Zyphdoz/tokyo-night-pink-vscode-theme/refs/heads/master/static/cc7be2.gif) `#cc7be2` and classes are ![#7f1fbe](https://raw.githubusercontent.com/Zyphdoz/tokyo-night-pink-vscode-theme/refs/heads/master/static/7f1fbe.gif) `#7f1fbe`.

Here is a comparison with the pink variant to the left and the original variant to the right.
![Comparison of pink and original scheme](https://raw.githubusercontent.com/Zyphdoz/tokyo-night-pink-vscode-theme/refs/heads/master/static/ss_tokyo_night_pink_comparison.png)


## Installation
### Option 1 - install the .vsix file: 
Download the latest .vsix file from [releases](https://github.com/Zyphdoz/tokyo-night-pink-vscode-theme/releases/tag/v1.1.2) and install it by running this command in the directory where you saved the file:
```
code --install-extension tokyo-night-pink-1.1.2.vsix
```

### Option 2 - build from source:

Clone this repo

Install vsce if you don't already have it
```
npm install -g vsce
```

Package the solution and install
```
vsce package
code --install-extension tokyo-night-pink-1.1.2.vsix
```


### Troubleshooting
If you are seeing duplicate Tokyo night themes in the list it's likely because you have the original Tokyo Night extension installed and this fork comes with the original themes as well. You can disable the original extension if you don't want to see double entries in the list.