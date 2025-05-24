> [!infobox] This is an Infobox
> ![](testimage.png)
> 
> Infoboxes are callouts that can be used to create wiki-like sidebars.
>
> <div class="section">Classes</div>
> 
> <span class="label">Sections</span>Sections look like that up there
> <span class="label">Labels</span>The bold text to the left
> <span class="label">Info</span>The text below this
> <span class="info">This *text* here</span>
> 
> ---
> These classes are added to improve your formatting options.
> 
>
> <div class="section">Need more options?</div>
> 
> <span class="label">Plugins</span>Use Style Settings to
> <span class="info">adjust its appearance.</span>
> <span class="label">Snippets</span>Style everything else with
> <span class="info">[Extended Typography Styles](https://github.com/Avyrra/Extended-Typography-Styles/tree/main)</span>

*Note: Best viewed in Reading Mode*

What you see to the right is an Infobox. It utilizes callouts and custom classes to emulate the design of a wiki-sidebar. You can create an infobox by typing:
>	>[!infobox]  Title Name

If you want your infobox to be on the left, you can instead type:
>	>[!infoboxleft]  Title Name

---

# Classes

You can then insert your information as standard markdown. However, if you want to take your infoboxes to the next level, you can use one of the three classes: **Sections, Labels,** and **Info.**

# Sections, Labels, & Info
To add a section, you can type the following line within the callout:
```html
<div class="section">Section Name Here</div>
```
It is recommended to use `<div>` instead of `<span>` for the section class in order to maintain better spacing. However, you should always leave an empty line after `<div>` to prevent markdown from malfunctioning.

To add a label, you can type the following line within the callout:
```html
<span class="label">Label Name</span>Initial Info
```
The Label class will automatically allow you to add information after `</span>` so that the first line of info lines up with the label. In order to add additional information, you can write the following:
```html
<span class="info">Add Info</span>
```

---

You may be wondering: "Why does your obsidian look better than my obsidian? It looks like it took way too much time and effort." And you'd be right. But it doesn't have to be that way for you too. I did all the work for you by creating [Extended Typography Styles](https://github.com/Avyrra/Extended-Typography-Styles/tree/main) so that your vault can look beautiful as well.