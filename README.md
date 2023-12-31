# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:

Clone the github repository and create Django admin interface.


### Step 2:

Change settings.py file to allow request from all hosts.

### Step 3:

Use CSS for creating attractive colors.

### Step 4:

Write JavaScript program for implementing five different operations.

### Step 5:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
calc.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="/static/css/style.css">
    <title>WELCOME TO THE MINI CALCULATOR</title>
</head>

<body>
    <div class="container">
        <h1>Calculator</h1>

        <div class="calculator">
            <input type="text" name="screen" id="screen">
            <table>
                <tr>
                    <td><button>(</button></td>
                    <td><button>)</button></td>
                    <td><button>C</button></td>
                    <td><button>%</button></td>
                </tr>
                <tr>
                    <td><button>7</button></td>
                    <td><button>8</button></td>
                    <td><button>9</button></td>
                    <td><button>X</button></td>
                </tr>
                <tr>
                    <td><button>4</button></td>
                    <td><button>5</button></td>
                    <td><button>6</button></td>
                    <td><button>-</button></td>
                </tr>
                <tr>
                    <td><button>1</button></td>
                    <td><button>2</button></td>
                    <td><button>3</button></td>
                    <td><button>+</button></td>
                </tr>
                <tr>
                    <td><button>0</button></td>
                    <td><button>.</button></td>
                    <td><button>/</button></td>
                    <td><button>=</button></td>
                </tr>
            </table>
        </div>
    </div>

</body>
<script src="/static/js/index.js"></script>
</html>


```
```
style.css
*{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}


.container{
    width: 100%;
    height: 100vh;
    background: #e3f9ff;
    display: flex;
    align-items: center;
    justify-content: center;
}
.calculator{
    background:#3a4452;
    padding: 20px;
    border-radius: 10px;
}
.calculator form input{
    border: 0;
    outline: 0;
    width: 60px;
    height: 60px;
    border-radius: 10px;
    box-shadow: -8px -8px 15px rgba(255, 255, 255, 0.1),5px 5px 15px rgba(0, 0, 0, 0.2);
    background: transparent;
    font-size: 20px;
    color:yellow;
    cursor: pointer;
    margin: 10px;
}

form .display{
    display: flex;
    justify-content: flex-end;
    margin: 20px 0;
}
form .display input{
    text-align: right;
    flex: 1;
    font-size: 45px;
    box-shadow: none;
}
form input.equal{
    width: 145px;
}



form input.operator{
    color: #33ffd8;
}
```
## OUTPUT:
![456](https://github.com/ram-sec-1405/standard-calculator/assets/155155799/c3fda7ce-31fa-4cfe-ab79-1a87e4080b18)

![123](https://github.com/ram-sec-1405/standard-calculator/assets/155155799/2f2e835b-9009-4b6a-9011-be9a6d87c641)


## Result:

The program for designing a simple calculator using JavaScript is executed successfully.
