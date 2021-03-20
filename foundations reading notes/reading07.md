## Ch6 Tables

    <table>
        <tr>
            <th>Table Head</th>
            <th>Table Head2</th>
        <tr>
        <td>data</td>
        <td>data</td>
        <tr>
        </tr>    
    </table>

tables are constructed with the `<table>` element, which consists of table rows. Table rows can be specified as the `<th>` to represent the heading. Browsers usually display the table heading as bold and centered. You can span rows or columns using the colspan or rowspan attribute.

## Ch 3 Javascript

using constructor notation to create an object 

    let coolGuy = new Object ()
     coolGuy.name = 'Timmy';
     coolGuy.lastName = 'Jeans';
 
 Many functions can be created using constructor notation:

    function CoolGuy (name, lastName){
     this.name = name;
     this.lastName = lastName;
    }

    const timmy = new CoolGuy('Timmy', 'Jeans')

