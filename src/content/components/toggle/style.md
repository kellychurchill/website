---

title: Toggle
tabs: ['Code', 'Usage', 'Style']
---

## Color

| Class                                                                    | Property                 | SCSS      |
| ------------------------------------------------------------------------ | ------------------------ | --------- |
| `.bx--toggle__appearance:after`                                          | background-color         | $ui-01    |
| `.bx--toggle__appearance:after`                                          | border                   | $ui-05    |
| `.bx--toggle--small + .bx--toggle__label .bx--toggle__appearance:before` | border                   | $ui-05    |
| `.bx--toggle:checked + .bx--toggle__label .bx--toggle__appearance:after` | background-color, border | $brand-01 |
| `.bx--toggle__check`                                                     | fill                     | $brand-01 |
| `.bx--toggle__label`                                                     | color                    | $text-01  |

<image-component fixed="default" caption="Examples of inactive, inactive hover, and active states for a Toggle">

![Inactive, inactive hover, and active states for a Toggle](images/toggle-style-1.png)

</image-component>

## Typography

Toggle labels should be set in sentence case, with only the first word in a phrase and any proper nouns capitalized, and no more than three words.

| Class                                                      | Font-size (px/rem) | Font-weight  | Text style       |
| ---------------------------------------------------------- | ------------------ | ------------ | ---------------- |
| `.bx--label`                                               | 14 / 0.875         | Normal / 600 | `.bx--type-zeta` |
| `.bx--toggle__text--left` </br> `.bx--toggle__text--right` | 14 / 0.875         | Normal / 400 | -                |

## Structure

### Toggle

| Class                                                      | Property                  | px / rem | Spacing token |
| ---------------------------------------------------------- | ------------------------- | -------- | ------------- |
| `.bx--toggle__appearance`                                  | width                     | 48 / 3   | -             |
| `.bx--toggle__appearance:after`                            | height, width             | 24 / 1.5 | -             |
| `.bx--toggle__appearance:after`                            | border                    | 2px      | -             |
| `.bx--toggle__label`                                       | margin-top, margin-bottom | 16 / 1   | $spacing-md   |
| `.bx--toggle__text--left` </br> `.bx--toggle__text--right` | margin-right, margin-left | 8 / 0.5  | $spacing-xs   |

<image-component fixed="default" caption="Structure and spacing measurements for Toggle | px / rem">

![Structure and spacing measurements for toggle](images/toggle-style-2.png)

</image-component>

### Small toggle

| Class                                                                   | Property                  | px / rem   | Spacing token |
| ----------------------------------------------------------------------- | ------------------------- | ---------- | ------------- |
| `.bx--toggle--small`                                                    | height                    | 16 / 1     | -             |
| `.bx--toggle--small`                                                    | width                     | 32 / 2     | -             |
| `.bx--toggle--small + .bx--toggle__label .bx--toggle__appearance:after` | height, width             | 10 / 0.625 | -             |
| `.bx--toggle--small`                                                    | margin-top, margin-bottom | 16 / 1     | $spacing-md   |

<image-component fixed="default" caption="Structure and spacing measurements for Small Toggle | px / rem">

![Structure and spacing measurements for small toggle](images/toggle-style-3.png)

</image-component>
