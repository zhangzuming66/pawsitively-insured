<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pawsitively Insured - Student Pet Insurance</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5faff;
        }
        header {
            background-color: #4caf50;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://source.unsplash.com/1600x900/?student,pets') no-repeat center;
            background-size: cover;
            color: white;
        }
        .hero h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 18px;
            margin-bottom: 20px;
        }
        .btn {
            background-color: #ff9800;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
        }
        .container {
            text-align: center;
            padding: 40px 20px;
        }
        .calculator {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
        }
        .testimonials {
            background: #e3f2fd;
            padding: 40px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>Pawsitively Insured - Affordable Pet Insurance for Students</header>
    <div class="hero">
        <h1>Protect Your Pet, Secure Your Future</h1>
        <p>Affordable, flexible pet insurance tailored for students.</p>
        <a href="#get-quote" class="btn">Get a Quote</a>
    </div>
    
    <div class="container">
        <h2>Estimate Your Coverage</h2>
        <div class="calculator">
            <label for="income">Your Monthly Income ($):</label>
            <input type="number" id="income" placeholder="Enter income">
            <br><br>
            <label for="pet-age">Your Pet's Age (years):</label>
            <input type="number" id="pet-age" placeholder="Enter pet age">
            <br><br>
            <button onclick="calculateCoverage()" class="btn">Calculate</button>
            <p id="result"></p>
        </div>
    </div>
    
    <div class="testimonials">
        <h2>What Students Say</h2>
        <p>"Pawsitively Insured made it easy for me to afford coverage for my dog while studying abroad!" - Alex, 22</p>
        <p>"Affordable and reliable. I love their easy claim process." - Emma, 20</p>
    </div>
    
    <script>
        function calculateCoverage() {
            let income = document.getElementById("income").value;
            let petAge = document.getElementById("pet-age").value;
            let coverage = (income * 0.1) - (petAge * 5);
            if (coverage < 0) coverage = 0;
            document.getElementById("result").innerHTML = "Estimated Monthly Coverage: $" + coverage.toFixed(2);
        }
    </script>
</body>
</html>
