<script>
function submitOrder(){
    let username = document.getElementById("username").value;
    let pack = document.getElementById("package").value;
    let pay = document.getElementById("payment").value;

    if(username === ""){
        alert("Enter username!");
        return;
    }

    let msg = `New Order:
Username: ${username}
Package: ${pack}
Payment: ${pay}`;

    let phone = "923XXXXXXXXX"; // apna number
    let url = `https://wa.me/${phone}?text=${encodeURIComponent(msg)}`;

    window.open(url, "_blank");
}
</script> 
<a href="YOUR_PAYMENT_LINK" target="_blank">
    <button>Pay with Crypto</button>
</a>
