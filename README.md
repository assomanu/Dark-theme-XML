# Dark-theme-XML
A nice dark color scheme I use in gedit.

All I did was modifying some colors and add

```xml
<style name="def:operator" foreground="purple_2"/>
```
which colors C language operators like `sizeof`, `typeof`, `offsetoff` and `static_assert`.

For more informations, take a look to style name definitions used by GtkSourceView with
```bash
locate gtksourceview | grep /c.lang
```
and then open one of the shown `c.lang` files with your text editor.

Of course you can do the same for any other language.

## How to install this theme in gedit
- Download yaru-alt-dark.xml
- Open gedit
- "Preferences"
- "Font & Colours"
- Click on "+" button (install scheme)
- Browse and select yaru-alt-dark.xml
- Enjoy!
