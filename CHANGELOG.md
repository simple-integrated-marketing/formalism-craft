# Release Notes for Formalism

## 1.0.11 - 2020.11.11

- Fix an issue where `SimpleXMLElement` will break if the input html does not comply XML rules (eg. it requires data-required attribute to have a value)

## 1.0.9 - 2020.02.25

-   Added support for `signature` field

## 1.0.8 - 2019.11.11

### Changed

-   Improved getObjectFromHtml to return strings, not XML objects

## 1.0.7 - 2019.09.23

### Changed

-   Updated fieldset template to house complex Freefrom fields
-   Updated example template to cater for all Freeform fields
-   Fixed an issue where AJAX + reCAPTCHA would cause a JS error
