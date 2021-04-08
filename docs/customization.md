---
layout: default
title: Working with Version Control
nav_order: 6
---

# Working with Version Control
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

Before we start, double-click on PyCharm icon to run it.

## Cloning Repository
{: .d-inline-block }

![cloning_repository](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/clone_repository.png?raw=true "Cloning repository")

1. Press "Get from version control" to clone repository from Github to your PyCharm.

![cloning_repository_GitHub](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/clone_repository_github_press_code.png?raw=true "Get clone repo url from GitHub")

2. Go back to GitHub and find the repository you want to clone. 
3. Press the "Code" button to access the link.

![cloning_repository_GitHub](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/clone_repository_github_press_code_copy_clipboard.png?raw=true "Get clone repo url from GitHub")

4. Click on the highlighted "board" to copy the link.

![cloning_repository](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/clone_repository1.png?raw=true "Cloning repository")

5. Paste the link you got from GitHub in the highlighted section.

![cloning_repository](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/clone_repository_choose_directory.png?raw=true "Cloning repository")

6. Choose the directory folder that you wish to save the cloned property into.

![cloning_repository](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/cloning_repository_press_clone.png?raw=true "Cloning repository")

7. Press "clone". 
8. Congrats! You successfully cloned a repository of your own choosing!

## Committing and Pushing Changes

We have all experienced losing our saved work whether by forgetting where we have put them or messing up so bad the file got corrupted. It is also important to save your work when coding as well. To do that, you need to "commit" the changes you have made and "push" the changes to the repository you have cloned.

![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_highlighted.png?raw=true "committing changes")

1. If you see your files change colour as highlighted above, it means there are changes made that is not saved.

![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_button_highlighted.png?raw=true "committing changes")

2. As highlighted above, you will see 3 shapes. Press the "Check-mark" shape to commit.

![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_message_highlighted.png?raw=true "committing changes")

3. Make sure to tick off the files you want to save. 

![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_message_filledout.png?raw=true "committing changes")

4. Fill out the changes you have made to those files. Simple descriptions that others can understand what changes you have made are best.

```
--------STOP-------- 
You may choose to press "commit" here to simply "commit" the changes you have made. 
However, in order to save the changes you have made to a repository that you cloned from, 
you must also "push" the changes you made as well. The next step will entail "pushing" changes.
```

![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_and_push.png?raw=true "committing changes")

5. Press the downward arrow next to "commit" button.
6. Press "commit and push". 

![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_and_push_finally_pushing.png?raw=true "committing changes")

You will be led to a new window detailing what will be pushed.

7. Press "push"
8. Congratulations! You committed and pushed the changes you made to the files! 

```
--------NOTE-------- 
It is a good practice to commit and push often. Committing and pushing after coding a function is ideal.
```

### Define a custom scheme

You can add custom schemes.
If you want to add a scheme named `foo` (can be any name) just add a file `_sass/color_schemes/foo.scss` (replace `foo` by your scheme name) 
where you override theme variables to change colors, fonts, spacing, etc.

Available variables are listed in the [_variables.scss](https://github.com/pmarsceill/just-the-docs/tree/master/_sass/support/_variables.scss) file.

For example, to change the link color from the purple default to blue, include the following inside your scheme file:

#### Example
{: .no_toc }

```scss
$link-color: $blue-000;
```

_Note:_ Editing the variables directly in `_sass/support/variables.scss` is not recommended and can cause other dependencies to fail.
Please use scheme files.

### Use a custom scheme

To use the custom color scheme, only set the `color_scheme` parameter in your site's `_config.yml` file:
```yaml
color_scheme: foo
```

### Switchable custom scheme

If you want to be able to change the scheme dynamically, for example via javascript, just add a file `assets/css/just-the-docs-foo.scss` (replace `foo` by your scheme name)
with the following content:`

{% raw %}
    ---
    ---
    {% include css/just-the-docs.scss.liquid color_scheme="foo" %}
{% endraw %}

This allows you to switch the scheme via the following javascript.

```js
jtd.setTheme('foo');
```

## Override and completely custom styles

For styles that aren't defined as variables, you may want to modify specific CSS classes.
Additionally, you may want to add completely custom CSS specific to your content.
To do this, put your styles in the file `_sass/custom/custom.scss`.
This will allow for all overrides to be kept in a single file, and for any upstream changes to still be applied.

For example, if you'd like to add your own styles for printing a page, you could add the following styles.

#### Example
{: .no_toc }

```scss
// Print-only styles.
@media print {
  .side-bar, .page-header { display: none; }
  .main-content { max-width: auto; margin: 1em;}
}
```
