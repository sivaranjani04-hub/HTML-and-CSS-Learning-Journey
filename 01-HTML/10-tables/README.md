# HTML Tables

## What is it?
A table shows data in rows and columns. `<tr>` makes a row, `<th>` a header cell and `<td>` a data cell. CSS controls borders, width, alignment and colours.

## Syntax
```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Asha</td>
    <td>20</td>
  </tr>
</table>
```

## Important attributes/properties
- `table` – the table
- `tr` – table row
- `th` – header cell (bold, centred)
- `td` – data cell
- `colspan` – merge columns
- `border, border-collapse` – CSS for borders
- `width, text-align, background-color` – CSS for size, alignment, colours

## Examples
- `01-basic-table.html` – smallest table
- `02-store-hours.html` – Store Hours table
- `03-student-marks.html` – marks table with colours
- `04-alignment-width.html` – alignment and width
- `style.css` – shared table styles

## Key takeaway
- Rows go inside the table, cells go inside rows.
- Use `border-collapse: collapse` for clean borders.
- Use `th` for headings so browsers and screen readers understand them.
