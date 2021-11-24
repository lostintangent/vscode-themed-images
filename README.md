# Markdown Themed Images

This extension adds support for "themed images" in the VS Code markdown preview. In particular, you can append `#gh-light-mode-only` or `#gh-dark-mode-only` to the end of an image's URL, and that will hide/show the appropriate images based on the end-user's active theme ([Details](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/)).

For example, the following GitHub logo will toggle its fill color based on the active VS Code theme (dark vs. light):

![GitHub-Mark-Light](https://user-images.githubusercontent.com/3369400/139447912-e0f43f33-6d9f-45f8-be46-2df5bbc91289.png#gh-dark-mode-only)![GitHub-Mark-Dark](https://user-images.githubusercontent.com/3369400/139448065-39a229ba-4b06-434b-bc67-616e2ed80c8f.png#gh-light-mode-only)