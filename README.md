# UC Field Extras

## COMPATIBILITY

Drupal 7.x Ubercart 3.x

## ABOUT
uc_fieldextras brings a few enhancements to the Drupal Ubercart shopping cart platform.

**What it does**

Currently, this module adds the following functionality:
- [x] Quantity as HTML 5: Make the Ubercart Quantity field HTML5 compatible as a number instead of text on mobile to show the number pad instead of the keyboard.
- [x] Quantity +/-: Adds a plus and minus to the add-to-cart quantity form field and /cart quantity form field. It has a text field for customizing the button layout, such as adding font-awesome icons.
[x] Quantity Autoselect: When enabled, this will force the quantity form field to select and highlight the quantity number so the user doesn't have to first delete the number.
[x] Phone as HTML 5: Adds HTML5 functionality to the /cart/checkout phone form field to make mobile entry easier. Also includes basic number validation for US & Canada.
[x] Email as HTML 5: Converts the /cart/checkout email form field to HTML5 and has whitespace trimming capability to remove all possibilities of a user having a whitespace in their email address which normally produces an error.
[x] Required as HTML 5: Make all required form elements on required in a HTML5 compatible way, by adding the "required" attribute to the "input" tags, thus enabling HTML5 compatible browsers to make sure that some value has been entered into required fields.

## REQUIREMENTS

(UC) Store

## INSTALLATION

Install as usual in the sites/all/modules folder

## CONFIGURATION

Menu: Home » Administration » Store » Configuration » Products

Settings: /admin/store/settings/products/uc_fieldextras

## INSTRUCTIONS

The module is pretty self-explanatory. View the configure page for setup to enable/disable and tweak the extras you want.
