## HTML
TABLES
`< table>` element is used to create element.
`< tr>` table raw  defines a row of cells in a table
`< td>` table data defines a cell of a table that contains data.
`< th>` table heading defines a header cell in an HTML table.
`< thead>` is used to group header content in an HTML table. 
`< tbody>` is used to group the body content in an HTML table.
`< tfoot>` tag is used to group footer content in an HTML table
 `colspan` attribute indicates how many colums the cell should run.
`rowspan` attribute indicates how many raws the cell should run.
## creating an object
to create an object we need an object, key and value.
literal notation
```
var hotel = {
  name = 'Asmara'
  rooms = 70,
  booked = 25,
  checkAvailability: function() {
    return this.rooms - this.booked;
  }
}
```

Object constructor notaotiom
```
function Hotel ( name, rooms, booked){
  this.name = name;
  this.rooms = rooms;
  this.booked = booked;
  this.checkAvailability = function(){
    return this.rooms - this.booked;
  };
}
var asmaraHotel = new Hotel ('Asmara','70','25');
``` 
