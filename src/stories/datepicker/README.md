# Datepicker component

## Props

|      Props      |  Type  | Default value | Required | Description                      |
| :-------------: | :----: | :-----------: | :------: | -------------------------------- |
|       id        | string |       -       |    ✓     | Id of the datepicker             |
|      label      | string |       -       |    ✓     | Label of the datepicker          |
|      value      | number |       -       |    ✓     | Value of the datepicker          |
|   placeholder   | string |      ""       |          | Placeholder of the datepicker    |
|  handleChange   |  func  |       -       |    ✓     | Handler of the datepicker        |
|    readOnly     |  bool  |     false     |          | Is the datepicker read only      |
|  labelPosition  | string |   "DEFAULT"   |          | Position of the datepicker label |
|    required     |  bool  |     false     |          | Is the datepicker required       |
| declarations \* | array  |      [ ]      |          | Declarations of the datepicker   |
|      style      | object |      {}       |          | Style of the datepicker          |

- `declarations` are documented in the `Declarations` component

## Styles

**Datepicker** component has for classes `datepicker-lunatic`.