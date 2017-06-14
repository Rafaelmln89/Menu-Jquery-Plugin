# Menu-Jquery-Plugin
==================================================

What is?
--------------------------------------

A simple and lite jQuery library to create a responsive menu

Options:
----------------------------

- BACKGROUNDCOLOR AND TEXT COLOR
- BACKGROUNDCOLOR AND TEXT HOVER EFECT COLOR
- THE NAME OFF MENU ITEN
- THE ICON OFF MENU ITEN


Icons Library:
----------------------------
I use some icons from Fontello <fontello.com> to ilustrate the itens menu, your can check all icons in <demo/font/demo.hmtl>


How to use:
----------------------------

```
//Exemple
$(document).ready(function()
{
    //call the plugin
    $('body').mln_menu(
    {
        'background' : '#333', // the background colr off menu
        'color' : '#fff', // the color off menu itens
        'hoverbackground' : '#fff', // the hover background color
        'hovercolor' : '#808285', // the hover text color
        'itens' : ['Home', 'User', 'Cloud', 'Configurations', 'Logout'], // the menu itens
        'hrefs' : ['#home', '#user', '#cloud', '#configurations', '#logout'], // the links off menu itens
        'icons' : ['icon-th-large', 'icon-user', 'icon-cloud', 'icon-chart-pie', 'icon-logout'] // the icons options off menu itens
    });
});

```

Requirements:
----------------------------
It's necessary add the jQuery library
For icons, it's necessary add the fontello font famaly
```
<link rel="stylesheet" href="./font/css/fontello.css" type="text/css" />
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript" src="./mln_menu.js"></script>
<script type="text/javascript">
        $(document).ready(function()
        {
                //your code here
        }
</script>
```

