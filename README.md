# JQuery-miniprojects
The Projects includes features that are included in jQuery library 
<html>
    <head>
        <title>
            JQUI
        </title>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="jqueryUI/jquery-ui.css">
        <link rel="stylesheet" href="jqueryUI/jquery-ui.structure.css">
        <link rel="stylesheet" href="jqueryUI/jquery-ui.theme.css">
    </head>
          
    <body>
        <div id="div1">
            <h3>jQuery</h3>
            <input id="date" placeholder="Enter the date" type="text">
        </div><br
        <script>   
        $("#date").datepicker({
            numberOfMonths:1,
            changeYear: true,
            showWeek:true, 
            showOtherMonths:true,
            changeMonth:true,
            weekHeader:"wk no",
            minDate: new Date(2014,0,0),
            maxDate: new Date(2020,0,0)
        });</script></html>
