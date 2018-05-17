# meuprimeirocurriculo<!DOCTYPE html>
<html>
<head>
        <style>
/*Adiciona as linhas duplas envolta da tabela*/
table, th, td {
    border: 1px solid black;
}
/*Adiciona espaco entre as linhas verticais da tabela*/    
th, td {
    padding: 15px;
}
/*ALINHA O TEXTO A ESQUERDA*/
th {
    text-align: left;
}
/*ADICIONA ESPACO ENTRE AS LINHAS DA TABELA*/
table {
    border-spacing: 5px;
}
                </style>
</head>

<body>


<h2>Basic HTML Table</h2>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>



<table style="width:100%">
        <tr>
          <th>Name</th>
          <th colspan="2">Telephone</th>
        </tr>
        <tr>
          <td>Bill Gates</td>
          <td>55577854</td>
          <td>55577855</td>
        </tr>
      </table>
      

</body>
</html>
