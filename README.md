<!DOCTYPE html>
<html lang="en">
    <meta charset="UTF-8">
    <link rel='stylesheet' href='MB.css'/>
    <meta name="viewport" content=""width=device-width, initial scale="1">
<head>
    <body>
    <div class="header"> 
        <h1>Meyers-Briggs Compatibility Game</h1>
        <p>Who's your most compatible match?</p>
    </div>
    <div class="main">
    <div class="buttons">
        <!--A button to open the popup form-->
        <button class="couples-button" onclick="openForm()">COUPLE</button>
        <!--the form-->
        <div class="form-popup" id="myForm">
            <form action="/action_page.php" class="form-container">
        
                <label for="person1"><b>Your personality type</b></label>
                <input type="text" placeholder="Ex: INFP" name="type" required>
            
                <label for="person2"><b>Matches personality type</b></label>
                <input type="text" placeholder="Ex: INFP" name="type" required>
            
                <button type="submit" class="btn">Submit</button>
                <button type="button" class="btn cancel" onclick="closeForm()">Close</button>
              </form>
        </div>

        <button class="group-button" onclick="openForm()">GROUP</button>
    </div>
    <br>
    <br>
    <br>
    <table class="width:100%">
        <tr>
            <td class="box1"></td>
            <td>Ideal Match: Problems resolved easily, growth occurs naturally.</td>
        </tr>
        <tr>
            <td class="box2"></td>
            <td>Strong Match: Hardships will require some compromise.</td>
        </tr>
        <tr>
            <td class="box3"></td>
            <td>Potential Match: Shared values needed to transform into strong match.</td>
        </tr>
        <tr>
            <td class="box4"></td>
            <td>Conflictive Match: Needs compromise and maturity to sustain growth.</td>
        </tr>
        <tr>
            <td class="box5"></td>
            <td>Least Ideal Match: Both partners must compromise and empathize.</td>
        </tr>   
        </table> 
            <br>
            <br>
            <br>
        <img src="mainimg.jpeg" alt="Meyers-Briggs personality type chart" class="center">
    </div>
    </div>


    <div class="footer">
        <h2></h2>
      </div>

        <script src="MB.js"></script>
    </body>

</head>
</html>
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
