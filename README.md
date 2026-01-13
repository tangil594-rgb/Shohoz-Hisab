# Shohoz-Hisab
নিজের হিসাব এখন সহজেই
<!DOCTYPE html>
<html>
<head>
    <title>দোকানের বিল সফটওয়্যার</title>
</head>
<body>

<h2>🧾 দোকানের বিল</h2>

পণ্যের নাম:<br>
<input type="text" id="name"><br><br>

দাম (৳):<br>
<input type="number" id="price"><br><br>

পরিমাণ:<br>
<input type="number" id="qty"><br><br>

<button onclick="calculate()">মোট হিসাব</button>

<h3 id="result"></h3>

<script>
function calculate() {
    let price = document.getElementById("price").value;
    let qty = document.getElementById("qty").value;
    let total = price * qty;

    document.getElementById("result").innerHTML =
        "মোট টাকা: ৳ " + total;
}
</script>

</body>
</html>
