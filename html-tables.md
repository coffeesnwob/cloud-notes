# Tables

A table represents information in a grid format. When dealing with tables, you need to think in terms of a grid made up of rows and columns. Each block in the grid is referred to as a table cell.

## Basic table structure

The `<table>` element is used to create tables. You indicate the start of each row using the `<tr>` element and it is followed by the `<td>` element. The `<td>` element stands for table row.

```html
<table>
  <tr>
    <td>12</td>
    <td>12</td>
    <td>50</td>
  </tr>
  <tr>
    <td>45</td>
    <td>60</td>
    <td>90</td>
  </tr>
  <tr>
    <td>60</td>
    <td>70</td>
    <td>90</td>
  </tr>
</table>
```

## Table heading

Like the `<td>` element, the `<th>` element’s purpose is to represent the heading for either a column or a row. Even if a cell has no content, you should still use a `<td>` or `<th>` element to represent an empty cell otherwise the table will not render correctly.

Using the `<th>` element helps people using the screen readers, improves the ability for search engines to index your page and also enables you to control the appearance of tables better.

The `<th>` element has an attribute called [scope](def/attributes#^fff13b) and its value indicates whether it is a heading for a column or a row.

```html
<table>
  <tr>
    <th></th>
    <th scope="col">Saturday</th>
    <th scope="col">Sunday</th>
  </tr>
  <tr>
    <th scope="row">Tickets Sold:</th>
    <td>120</td>
    <td>135</td>
  </tr>
  <tr>
    <th scope="row">Total sales:</th>
    <td>$600</td>
    <td>$675</td>
  </tr>
</table>
```

## Spanning columns

The [colspan](def/attributes#^fff13b) attribute can be used on a `<th>` or `<td>` element and indicated how many columns that cell should run across.

```html
<!-- ignore -->
<style type="text/css">
  table {
  border: none;]
  }
  th, td {
  color: #000;
  border: none;
  background-color: #ddd;
  padding: 5px;
  width:100px;
  }
</style>
<!-- ignore -->
<table>
  <tr>
    <th></th>
    <th>9am</th>
    <th>10am</th>
    <th>11am</th>
    <th>12am</th>
  </tr>
  <tr>
    <th>Monday</th>
    <td colspan="2">Geography</td>
    <td>Math</td>
    <td>Art</td>
  </tr>
  <tr>
    <th>Tuesday</th>
    <td colspan="3">Gym</td>
    <td>Home Ec</td>
  </tr>
</table>
```

## spanning rows

Same as the [colspan](def/attributes#^fff13b), [rowspan](def/attributes#^fff13b) attribute indicates how many rows a cell should span down the table.

```html
<!-- ignore -->
<style type="text/css">
  table {
  border: none;]
  }
  th, td {
  color: #000;
  border: none;
  background-color: #ddd;
  padding: 5px;
  width:100px;
  }
</style>
<!-- ignore -->

<table>
  <tr>
    <th></th>
    <th>ABC</th>
    <th>BBC</th>
    <th>CNN</th>
  </tr>
  <tr>
    <th>6pm - 7pm</th>
    <td rowspan="2">Movie</td>
    <td>Comedy</td>
    <td>News</td>
  </tr>
  <tr>
    <th>7pm - 8pm</th>
    <td>Sport</td>
    <td>Current Affairs</td>
  </tr>
</table>
```

## Long tables

There are three elements that help distinguish between the main content of the table and the first and last rows which are:

1. `<thead>
2. `<tbody>`
3. `<tfoot>`

These elements helps people with screen readers and also allow you to style these sections in a different manner than the rest of the tables.

```html
<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Income</th>
      <th>Expenditure</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1st January</th>
      <td>250</td>
      <td>36</td>
    </tr>
    <tr>
      <th>2nd January</th>
      <td>285</td>
      <td>48</td>
    </tr>
    <!-- additional rows as above -->
    <tr>
      <th>31st January</th>
      <td>129</td>
      <td>64</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td></td>
      <td>7824</td>
      <td>1241</td>
    </tr>
  </tfoot>
</table>
```

---

[[html]]
[[attributes]]
[[block and inline]]
