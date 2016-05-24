# Tables

Tables help screen readers process information presented in a tabular format. When information is presented using table markup, screen reader users can read down columns and across rows, and even hear column and row headings as they do so.

HTML provides a lot of elements and attributes to create fully accessible tables. ``Note:`` ARIA 1.0 does not include HTML table equivalence; that is coming in ARIA 1.1. So it is best to stick to native HTML unless you are building an interactive grid that includes two-dimensional arrow key navigation of the table content.

```HTML
<table>
  <tr>
    <td></td>
    <th>Week1</th>
    <th>Week2</th>
  </tr>
  <tr>
    <th>Clicks</th>
    <td>100</td>
    <td>90</td>
  </tr>
  <tr>
    <th>Likes</th>
    <td>60</td>
    <td>55</td>
  </tr>
</table>
```

another example:

```HTML
<table summary="The number of employees and the foundation year of some imaginary companies.">
	<caption>Table 1: Company data</caption>
	<tr>
		<th scope="col">Company</th>
		<th scope="col">Employees</th>
		<th scope="col">Founded</th>
	</tr>
	<tr>
		<td scope="row">ACME Inc</td>
		<td>1000</td>
		<td>1947</td>
	</tr>
	<tr>
		<td scope="row">XYZ Corp</td>
		<td>2000</td>
		<td>1973</td>
	</tr>
</table>
```