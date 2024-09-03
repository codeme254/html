# HTML Tables

HTML tables are used to display data in a grid or tabular format, where content is organized into rows and columns.  

## Basic Structure of an HTML Table
A simple HTML table is composed of several elements:
- ```<table></table>```: the main container for the table.
- ```<tr></tr>```: (table row), defines a row in the table.
- ```<th></th>```: (table header), defines a header cell, typically displayed as bold and centered by default.  
- ```<td></td>```: (table data), defines a standard cell in the table.

```HTML
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>City</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
    <tr>
        <td>Jack</td>
        <td>25</td>
        <td>Mombasa</td>
    </tr>
    <tr>
        <td>Elvis</td>
        <td>55</td>
        <td>Nyeri</td>
    </tr>
</table>
```
![table](table.png)

## Table attributes and additional features
```border``` attribute adds a border around table cells.  
```HTML
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>City</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
    <tr>
        <td>Jack</td>
        <td>25</td>
        <td>Mombasa</td>
    </tr>
</table>
```
![table border](table_border.png)

```rowspan``` and ```colspan``` attributes allow cells to span multiple rows or columns:
```HTML
<table border="1">
    <tr>
        <th>Name</th>
        <th colspan="2">Details</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>30</td>
        <td>Nairobi</td>
    </tr>
</table>
```
![colspan](colspan.png)

## Organizing table content
There are specific tags that help with organization of table content:
- ```<thead></thead>```: Wraps the table header.
- ```<tbody></tbody>```: Wraps the body of the table.
- ```<tfoot></tfoot>```: Wraps the footer of the table.

```HTML
<table border="1">
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Alice</td>
            <td>30</td>
            <td>Nairobi</td>
        </tr>
        <tr>
            <td>Jack</td>
            <td>25</td>
            <td>Mombasa</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">End of data</td>
        </tr>
    </tfoot>
</table>
```

![Organizing table content](organizing_table_data.png)