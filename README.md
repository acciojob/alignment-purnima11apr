# Alignment

### Create a HTML webpage that describes the use of HTML table. The webpage should include the following elements:

- Create a table that has 3 rows and 3 columns. The middle and rightmost column of each row must have `.center` and `.right` as their class.
- A second table to illustrate the use of colspan and rowspan. Create a table with 6 rows and 6 columns. All the columns of 1st row should be wrapped in a single cell. 
- A third table to add the image within the table.Last and first rows of this table should be green and blue respectively.
- All the tables should have `.middle` class.

Your Webpage should look somewhat like this:

![image](https://user-images.githubusercontent.com/78348500/217435540-555a8eb0-79a6-4590-90c0-28b620341d42.png)

### Instructions

- Id for the first table should be "table-1". Id for first, second and last cell of table 1 should be `t11`, `t12`, `t13`.
- Id for the second table shoulde be "table-2". Id for first cell of table 2 should be `t21`.
- Id for third table should be "table-3". Id for the cell that contains the image should be `t-image`.

#### Your css file should have the following styles:


```
.middle{
    margin: auto;
    width: 60%;
}

.center{
    text-align: center;
}

.right{
    text-align: right;
}

table{
    border: 1px solid black;
    border-spacing: 1px;
}

td{
    padding: 1px;
    border: 1px solid black;
}

.green{
    background-color: green;
}

.blue{
    background-color: blue;
}
```
