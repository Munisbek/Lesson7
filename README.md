Lesson7
=========
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Homework7</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <style type="text/css">
        .bs-example {
            margin: 20px;
        }

        /* Fix alignment issue of label on extra small devices in Bootstrap 3.2 */
        .form-horizontal .control-label {
            padding-top: 7px;
        }
    </style>
</head>
<body style="background-color:WindowFrame">
<h1>Sign Up</h1>
<hr>
<div class="container">

    <div class="bs-example">

            <div class="input-group has-error">
                Email:<input type="text" class="form-control " placeholder="Email">
            <span class="input-group-addon">
                <span class="glyphicon glyphicon-envelope"></span>
            </span>
            </div>

                   <br>
            <div class="input-group has-error">
              Password:<input type="password"  class="form-control" placeholder="Password">
            <span class="input-group-addon"><span class="glyphicon glyphicon-adjust"></span>
            </div>
        <br>
        <div class="input-group">
            Confirm Password:<input type="password"  class="form-control" placeholder="Confirm Password">
            <span class="input-group-addon"><span class="glyphicon glyphicon-adjust"></span>
        </div>
        <hr>
        <br>
        <div class="input-group">
            First name:<input type="text"  class="form-control" placeholder="First name">
            <span class="input-group-addon"><span class="glyphicon glyphicon-adjust"></span>
        </div>
        <br>
        <div class="input-group">
            Last name:<input type="text"  class="form-control" placeholder="Last name">
            <span class="input-group-addon"><span class="glyphicon glyphicon-adjust"></span>
        </div>
        <br>
        <div class="input-group">
            Phone:<input type="number"  class="form-control" placeholder="phone">
            <span class="input-group-addon">
                <span class="glyphicon glyphicon-phone">
                </span>
        </div>
        <hr>
        <br>
        <div class="row">
        <div class="col-xs-4 input-lg has-error">
            Date of Brith:<input type="number" class="form-control input-lg "
                   placeholder="date">
        </div>
        <div class="col-xs-4 input-lg has-error">
          Month:<select class="form-control input-lg">
            <option></option>
            <option>January</option>
                    <option> February</option>
                    <option>March</option>
                    <option>April</option>
                    <option>May</option>
                    <option>June</option>
                    <option>July</option>
                    <option> August</option>
                    <option>September</option>
                    <option>October</option>
                    <option>November</option>
                    <option>December</option>
            </select>
        </div>
         <div class="col-xs-4 input-lg has-error">
             Year:<select class="form-control input-lg">
             <option></option>
             <option>1989</option>
             <option>1990</option>
             <option>1991</option>
             <option>1992</option>
             <option>1993</option>
             <option>1994</option>
             <option>1995</option>
             <option>1996</option>
             <option>1997</option>
             <option>1998</option>
             <option>1999</option>
             <option>2000</option>
             <option>2001</option>
             <option>2002</option>
             <option>2003</option>
             <option>2004</option>
             <option>2005</option>
             <option>2006</option>
         </select>
     </div>
    </div>

    <br>
<br>
    <div class="input-group">
        <h4>Address:</h4><textarea class="form-control input-lg" rows="3"placeholder="Postal Address"></textarea>
    </div>
        <br>
        <div class="form-group input-lg has-error">
            <label for="exampleInputZipCode">ZipCode:</label>
            <input type="password" class="form-control" id="exampleInputZipCode" placeholder="ZipCode">
        </div>
        <br>
        <div class="radio-inline">
            <hr>
<h3>Gender:</h3>
            <div class="row">
                <div class="col-xs-6">
            <label class="radio-inline">
                <input type="radio" name="inlineRadioOptions" id="inlineRadioMale" value="option1"> Male
            </label>
                    </div>
                <div class="col-xs-6">
            <label class="radio-inline">
                <input type="radio" name="inlineRadioOptions" id="inlineRadioFemale" value="option2"> Female
            </label>
                    </div>
</div>
            <br>
            <hr>
            <div class="row">
                <div class="col-xs-8">
            <input type="checkbox" value=""> Send Me latest news and updates.
</div>
                <div class="col-xs-4">
                    <input type="checkbox" value=""> I agree to the <a href="#">Terms and conditions.</a>
                </div>
            </div>
            <br>
            <hr>
            <button type="submit" class="btn btn-info btn-lg">Submit</button>
            <button type="submit" class="btn btn-default pull-right btn-lg">Reset</button>
</div>
</div>
    </div>
    <hr>
<h3><i>Atadjanov Munis<i></h3>
</body>

</html>
