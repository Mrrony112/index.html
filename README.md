<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Trading AI Analyzer</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:#0d1117;
color:white;
}

header{
background:#161b22;
padding:15px;
text-align:center;
font-size:24px;
font-weight:bold;
color:#00ffcc;
}

.container{
padding:15px;
}

select,button{
width:100%;
padding:12px;
margin-top:10px;
border:none;
border-radius:8px;
font-size:16px;
}

button{
background:#00ffcc;
color:black;
font-weight:bold;
}

.card{
background:#161b22;
margin-top:15px;
padding:15px;
border-radius:10px;
}

.green{
color:#00ff66;
}

.red{
color:#ff5555;
}
</style>

</head>

<body>

<header>
Trading AI Analyzer
</header>

<div class="container">

<select>
<option>EUR/USD</option>
<option>GBP/USD</option>
<option>USD/JPY</option>
<option>AUD/USD</option>
<option>USD/CAD</option>
<option>XAU/USD</option>
</select>

<select>
<option>1 Minute</option>
<option>5 Minute</option>
<option>15 Minute</option>
<option>1 Hour</option>
</select>

<button>Analyze Market</button>

<div class="card">
<h3>Trend</h3>
<p class="green">Waiting for analysis...</p>
</div>

<div class="card">
<h3>Indicators</h3>

<p>EMA : --</p>

<p>RSI : --</p>

<p>MACD : --</p>

</div>

<div class="card">
<h3>AI Summary</h3>

<p>
Market analysis will appear here.
</p>

</div>

</div>

</body>
</html>
# index.html
