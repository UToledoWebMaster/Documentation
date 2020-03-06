# Webforms

## Steps to implementing a webform

1. Create a form on https://webforms.utoledo.edu/
2. Be sure to "Shrink" every piece of the form.
4. Copy the CSS code from this folder into the custom CSS area found in Setup & Embed > Preferences > Form Styles > Inject Custom CSS
5. If you want a one-column form, delete the clearly marked section of code at the bottom of the CSS. If you want a two-column form, drag a Form Collapse item from the Survey Tools menu to where you want the form to break into a second column.
5. When the form is complete, copy the code from the Embed HTML file into the desired page in OUCampus. Replace the "00000000" in the src attribute with your form's Form ID, which you can find in the URL of the form's Webforms page or by clicking "Embed Form" in the top toolbar of the form's Webforms page.


## Known Issues

- Fonts: Jubilat does not work inside the iframe. This is why we use Source Sans Pro for the submit button.
