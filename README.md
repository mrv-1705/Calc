# Ex.08 Design of a Standard Calculator
## Date: 29-04-24

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <style>
        body{
            background-image: url(calc\ body\ bg.jpg);
            background-repeat: no-repeat;
            background-size:cover;
        }
    </style>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <script>
        function fn(event){
            if(event.innerHTML== '='){
                textbox.value=eval(textbox.value);
            }
            else if(event.id=='back'){
                v=textbox.value
                textbox.value=v.substring(0,v.length-1);
            }
            else if(event.innerHTML=='C'){
                textbox.value='';   
            }
            else{
                textbox.value+=event.innerHTML;
            }
        }
    </script>
    <div class="bg-dark mx-auto text-center text-white" style="width: 24rem;background-image: url(calc\ bg.jpg);background-repeat: no-repeat;">Kurapati Vishnu Vardhan Reddy(212223040103)</div>
    <div class="bg-dark row mx-auto text-center" style="width: 24rem;background-image: url(calc\ bg.jpg);background-repeat: no-repeat; ">
      <div class="col-12 my-4">
        <input type="text" name="" id="textbox" style="width: 100%;height: 50px;border-radius: 25px;">
       </div>
    <div class=" m-3 col-2  btn btn-primary rounded-4" onclick="fn(this)">(</div>
    <div class=" m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">)</div>
    <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)">C</div>
    <div class="m-3 col-2 btn btn-danger" id="back" style="border-radius: 10px;">
    <i class="bi bi-backspace"></i></div>
    <div class=" m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">7</div>
    <div class=" m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">8</div>

    <div class=" m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">9</div>

    <div class=" m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">*</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">4</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">5</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">6</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">-</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">1</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">2</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">3</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">+</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">0</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">.</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">%</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">/</div>
    <div class="m-3 col-11 btn btn-warning rounded-4" onclick="fn(this)">=</div>






    </div>
</body>
</html> 
```
## OUTPUT:
![alt text](<Screenshot 2024-04-30 000317.png>)

![alt text](<Screenshot 2024-04-30 000328.png>)
## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
