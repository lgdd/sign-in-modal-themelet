# Sign In Modal Themelet

Add default Liferay sign in modal behavior to Liferay 7.x themes.

When you create a new Liferay theme, you don't have this modal by default and when you click on _Sign in_, you are redirected to a new page.

## Install

Go to your theme's root folder and type:
```bash
gulp extend
```
Choose _Themelet_ :
```
? What kind of theme asset would you like to extend?
  Base theme
❯ Themelet
```
Choose _Search npm registry_ :
```
? Where would you like to search for themelets?
  Search globally installed npm modules (development purposes only)
❯ Search npm registry (published modules)
```
Search for _liferay-dropzone-themelet_ :
```
? Search npm for themelets: sign-in-modal-themelet
```
> If you have an error, try `npm audit fix` and retry installation from the beginning

Press space to select it :
```
? Select a themelet
❯◉ sign-in-modal-themelet
```
