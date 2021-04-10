---
layout: default
title: Troubleshooting
nav_order: 99
---

# Troubleshooting
{: .fs-9 }
{: .no_toc}
Troubleshooting description
{: .fs-6 .fw-300 }

---

## TABLE OF CONTENTS
{: .no_toc .text-delta}
1. TOC
{:toc}

---

# Add Python to PATH

If your Python is not on your **PATH**{: .label .label-black } your Python will not be working in your Command Prompt.

You **MUST** place your Python program on your **PATH**{: .label .label-black }.

Let's do it!!

1. Search for **python.exe**{: .label .label-black } using Windows search like figure below. Then, **right click** the search result, and click *Open file location*.

    ![Find-Python](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/find_python.png?raw=true "Find Python")

2. When File Explorer opens, right click the address bar, and click *Copy address as text* as figure below.

    ![Copy-address](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/copy_address_as_text.png?raw=true "Copy address")

3. Click Windows search again, search for **Control Panel**, and open Control Panel.

    ![Opening-control-panel](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/opening_control_panel.png?raw=true "Opening control panel")

4. On the top right of Control Panel, you can see the search bar. Type **environment** in the search bar. Then, click *Edit the system environment variables*.

    ![Search-environment-in-control-panel](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/search_environment_in_control_panel.png?raw=true "Search environment in control panel")


5. You will see **Environment Variables** window now. As figure below shows, move your cursor to *Path*. Then, click *Edit...* button.

    **CAUTION**
      {: .label .label-yellow }
          DO NOT get confused with Path in System variables (at the bottom). You MUST choose Path in User variable (at the top).

    ![Changing-path-1](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/changing_path.png?raw=true "Changing path 1")

6. Click *New* button and type the address that you copied from step 2. Click *New* button again, type the address again, and add **Scripts\\**{: .label .label-black } at the end. Click *OK* when you done with adding two paths.

    ![Changing-path-2](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/changing_path_2.png?raw=true "Changing path 2")

7. By clicking *OK* again, You will successfully add your Python on **PATH**{: .label .label-black }.

    ![Changing-path-3](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/changing_path_3.png?raw=true "Changing path 3")



# Question 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

# Question 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```


| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |


# Question 4
