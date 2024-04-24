# Ex.08 Design of a Standard Calculator
## Date:23.4.24

## AIM:
To design a web application for a standard calculator with minimum five operations.

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <script>
         function fn(e) {
        if (e.innerHTML == '=' ) {
        output.value = eval(output.value);
        }
        else if (e.id == 'back') {
        v = output.value;
        output.value = v.substring(0, v.length - 1);
        }
        else if (e.innerHTML == 'C') {
        output.value = '';
        }
        else {
        output.value +=  e.innerHTML;
        }
    }
    </script>
    <div class=" row mx-auto text-center rounded-5" style="width: 24rem; background-color: rgb(203, 14, 77); " >
        <div class="my-5 text-center col-12 text-dark" style="background-color: rgb(215, 22, 54); "> yogeshwaran A(212223040249)</div>

    <div class="col-12 my-4"><input type="text" name="" id="output"
    style="width: 100%; height: 50px; border-radius: 25px;"></div>
    <div class="m-3 col-2 btn btn-primary text-dark rounded-4" style="background-color: rgb(170, 38, 60)"; onclick="fn(this);">(</div>
    <div class="m-3 col-2 btn btn-primary text-dark rounded-4" style="background-color: rgb(146, 30, 50)"; onclick="fn(this)">)</div>
    <div class="m-3 col-2 btn btn-danger text-dark rounded-4" style="background-color: rgb(151, 13, 36)"; onclick="fn(this)">C</div>
    <div class="m-3 col-2 btn btn-danger text-dark text-center rounded-4" style="background-color: rgb(137, 16, 36)"; onclick="fn(this)" id="back"><i class="bi bi-backspace"></i>
    </div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(173, 17, 43)"; onclick="fn(this)">7</div> 
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(147, 8, 31)"; onclick="fn(this)">8</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(160, 13, 37)"; onclick="fn(this)">9</div>
    <div class="m-3 col-2 btn btn-primary text-dark rounded-4" style="background-color: rgb(181, 11, 39)"; onclick="fn(this)">*</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(188, 5, 35)"; onclick="fn(this)">4</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(179, 17, 44)"; onclick="fn(this)">5</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(94, 9, 23)"; onclick="fn(this)">6</div>
    <div class="m-3 col-2 btn btn-primary text-dark rounded-4" style="background-color: rgb(147, 7, 30)"; onclick="fn(this)">-</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(167, 7, 34)"; onclick="fn(this)">1</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(169, 10, 37)"; onclick="fn(this)">2</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(203, 9, 41)"; onclick="fn(this)">3</div>
    <div class="m-3 col-2 btn btn-primary text-dark rounded-4" style="background-color: rgb(186, 9, 38)"; onclick="fn(this)">+</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(152, 5, 29)"; onclick="fn(this)">0</div>
    <div class="m-3 col-2 btn btn-success text-dark rounded-4" style="background-color: rgb(188, 12, 41)"; onclick="fn(this)">.</div>
    <div class="m-3 col-2 btn btn-primary text-dark rounded-4" style="background-color: rgb(181, 4, 33)"; onclick="fn(this)">%</div> 
    <div class="m-3 col-2 btn btn-primary text-dark rounded-4" style="background-color: rgb(171, 7, 34)"; onclick="fn(this)">/</div>
    <div class="m-3 col-11 btn btn-warning text-dark rounded-4" style="background-color: rgb(193, 11, 41)"; onclick="fn(this)">=</div>
    </div>
</body>
</html>

## OUTPUT:
![alt text](<Screenshot 2024-04-23 110748.png>)
![alt text](<Screenshot 2024-04-23 110804.png>)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
