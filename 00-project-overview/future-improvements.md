

**Shortcuts for basic memory:**
Shortcuts that create different types of comments specifically for claude to look at that, eg:
- <mark class="hltr-red">(!Fact check: Is this "insert fact" true? Where did we verify this?)</mark>
- <mark class="hltr-yellow">(!Question: These two areas have overlap, can we combine or more clearly separate their purpose and do we have the relevatn content to support both?)</mark>
- <mark class="hltr-pink">(!Idea: What would anchor links look for the major sections of the doc look like here?)</mark>
- 


Visual

Create custom styles (colour, icon) for callouts at the top of the templates to help visually differentiate between doc types easily. 

From https://help.obsidian.md/callouts :
### Customize callouts

[CSS snippets](https://help.obsidian.md/snippets) and [Community plugins](https://help.obsidian.md/community-plugins) can define custom callouts, or even overwrite the default configuration.

To define a custom callout, create the following CSS block:

```css
.callout[data-callout="custom-question-type"] {
    --callout-color: 0, 0, 0;
    --callout-icon: lucide-alert-circle;
}
```

The value of the `data-callout` attribute is the type identifier you want to use, for example `[!custom-question-type]`.

- `--callout-color` defines the background color using numbers (0–255) for red, green, and blue.
- `--callout-icon` can be an icon ID from [lucide.dev](https://lucide.dev), or an SVG element.
