---

title: Tooltip
tabs: ['Code', 'Usage', 'Style']
---

## Color

| Class                                                                                                                                                         | Property         | SCSS        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- | ----------- |
| `.bx--tooltip__label`                                                                                                                                         | text color       | $text-01    |
| `svg`                                                                                                                                                         | fill             | $brand-01   |
| `.bx--tooltip--shown`                                                                                                                                         | background-color | $ui-01      |
| `.bx--tooltip`                                                                                                                                                | color            | $text-01    |
| `.bx--tooltip`                                                                                                                                                | border           | $ui-03      |
| `.bx--tooltip__trigger path`                                                                                                                                  | fill             | $brand-01   |
| `.bx--tooltip--definition__bottom p` </br> `.bx--tooltip--definition__top p` </br> `.bx--tooltip--icon__top::after` </br> `.bx--tooltip--icon__bottom::after` | text color       | $inverse-01 |
| `.bx--tooltip--definition__bottom` </br> `.bx--tooltip--definition__top` </br> `.bx--tooltip--icon__top::after` </br> `.bx--tooltip--icon__bottom::after`     | background-color | $inverse-02 |

<image-component fixed="default" caption="Example of closed and open states for a Tooltip">

![Closed and open states for a Tooltip](images/tooltip-style-1.png)

</image-component>

## Typography

Tooltip labels and text should be set in sentence case.

| Property                                                                 | Font-size (px/rem) | Font-weight     | Type styles         |
| ------------------------------------------------------------------------ | ------------------ | --------------- | ------------------- |
| `.bx--tooltip__label`                                                    | 16 / 1             | Semi-Bold / 600 | `.bx--type-epsilon` |
| `.bx--tooltip p`                                                         | 14 / 0.875         | Normal / 400    | -                   |
| `.bx--tooltip--definition__top p` </br> `.bx--tooltip--icon__top:before` | 12 / 0.75          | Normal / 400    | `.bx--type-caption` |

## Layer

| Class                                                                                                                                                                          | Layer, Elevation | Box-shadow                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------- | ----------------------------- |
| `.bx--tooltip` </br> `.bx--tooltip--icon__top:before` </br> `.bx--tooltip--icon__bottom:before` </br> `.bx--tooltip--definition__bottom` </br> `.bx--tooltip--definition__top` | Overlay, 8       | 0 4px 8px 0 rgba(0,0,0,0.10); |

## Structure

All Tooltip types have a varying height based on the amount of content they contain.

### Interactive Tooltip

| Class                       | Property      | px / rem | Spacing token |
| --------------------------- | ------------- | -------- | ------------- |
| `.bx--tooltip`              | max-width     | 240 / 15 | -             |
| `.bx--tooltip__trigger svg` | height, width | 16 / 1   | -             |
| `.bx--tooltip__trigger`     | margin-left   | 8 / 0.5  | $spacing-xs   |
| `.bx--tooltip`              | padding       | 16 / 1   | $spacing-md   |
| `.bx--tooltip`              | margin-top    | 8 / 0.5  | $spacing-2xs  |

<image-component fixed="default" caption="Structure and spacing measurements for an Interactive Tooltip | px / rem">

![Structure and spacing measurements for an Interactive Tooltip](images/tooltip-style-2.png)

</image-component>

### Definition Tooltip

| Class                                                                    | Property      | px / rem  | Spacing token |
| ------------------------------------------------------------------------ | ------------- | --------- | ------------- |
| `.bx--tooltip--definition__bottom` </br> `.bx--tooltip--definition__top` | max-width     | 176 / 11  | -             |
| `.bx--tooltip--definition__bottom` </br> `.bx--tooltip--definition__top` | margin-top    | 12 / 0.75 | $spacing-sm   |
| `.bx--tooltip--definition__bottom` </br> `.bx--tooltip--definition__top` | padding       | 8 / 0.5   | $spacing-xs   |
| `.bx--tooltip--definition .bx--tooltip__trigger`                         | border-bottom | 2px       | -             |

<image-component fixed="default" caption="Structure and spacing measurements for a Definition Tooltip | px / rem">

![Structure and spacing measurements for a Definition Tooltip](images/tooltip-style-3.png)

</image-component>

### Icon Tooltip

| Class                                                                      | Property  | px / rem | Spacing token |
| -------------------------------------------------------------------------- | --------- | -------- | ------------- |
| `.bx--tooltip--icon__top:before` </br> `.bx--tooltip--icon__bottom:before` | max-width | 176 / 11 | -             |
| `.bx--tooltip--icon__top:before` </br> `.bx--tooltip--icon__bottom:before` | padding   | 4 / 0.25 | $spacing-2xs  |

<image-component fixed="default" caption="Structure and spacing measurements for an Icon Tooltip | px / rem">

![Structure and spacing measurements for an Icon Tooltip](images/tooltip-style-4.png)

</image-component>

### Placement

Tooltips should be placed below the Tooltip icon unless it is within the height of the Tooltip box plus 16px / 1rem of the bottom of the page. In that instance, the Tooltip should appear above the icon or defined word. On mobile, Tooltips can only appear below the Tooltip icon.

<image-component fixed="default" caption="Placement examples for a Tooltip">

![Placement examples for a Tooltip](images/tooltip-style-5.png)

</image-component>
