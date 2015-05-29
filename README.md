# pk-datepicker
Polymer element to pick a date. Compatible with Polymer ^1.0.0

## How to use

Sorry I don't have a component page for it jet. But just have a look at the demo.html and the documentation below.

## Options

Attribute           | Options     | Default                                                     | Description
---                 | ---         | ---                                                         | ---
`dayLabels`         | *array*    | `['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat']`          | Labels for the weekdays.
`dayLabels`         | *array*    | `['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December']`                        | Labels for the months.
`month`             | *number*    | `-1`                                                        | Month to pre-select. `-1` resolutes to the current month.
`year`              | *number*    | `-1`                                                        | Year to pre-select. `-1` resolutes to the current year.


## Events

Event         | Description
---           | ---
`date-selected` | Triggers when a date was selected.

## How to install

Clone this repository or use bower:

`bower install pk-datepicker --save`