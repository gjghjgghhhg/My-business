<!doctype html>

<html lang="bn">  

<head>  

<meta charset="utf-8">  

<meta name="viewport" content="width=device-width,initial-scale=1">  

<title>ওয়েলকাম — মাই বিজনেস</title>  

<style>  

:root{  

  --accent:#007bff;  

  --accent-dark:#0056b3;  

  --muted:#666;  

  --highlight:#000;  

  --green:#28a745;  

  --yellow:#ffc107;  

  --whatsapp:#25D366;  

  --card-bg:#fff7e6;  

  --body-bg:#ffe6f0;  

}  *{box-sizing:border-box}

body{

font-family:system-ui,-apple-system,Segoe UI,Roboto,"Noto Sans Bengali",sans-serif;

margin:0;

background:linear-gradient(135deg,#ffe6f0,#e6f7ff);

display:flex;

flex-direction:column;

align-items:center;

justify-content:flex-start;

min-height:100vh;

color:#222

}

.card{

width:380px;

background:var(--card-bg);

border-radius:14px;

box-shadow:0 8px 30px rgba(18,38,63,0.1);

padding:22px;

margin-top:20px;

border:2px solid #ff99cc;

}

.logo{

display:flex;

gap:12px;

align-items:center;

justify-content:center;

}

.logo .dot{

width:50px;

height:50px;

border-radius:10px;

background:var(--accent);

display:flex;

align-items:center;

justify-content:center;

color:#fff;

font-weight:700;

font-size:22px

}

.brand{

font-weight:700;

font-size:28px;

color:green;

letter-spacing:1px;

text-align:center;

margin-left:10px;

}

/* ওয়েলকাম টেক্সট */

.welcome-text{

text-align:center;

font-size:22px;

color:#ff3366;

font-weight:700;

margin-top:8px;

}

/* নোটিশ বাটন স্টাইল */

.notice-btn{

display:block;

width:100%;

padding:12px;

margin:16px auto 8px auto;

background:var(--yellow);

color:#000;

font-weight:700;

font-size:16px;

text-align:center;

border-radius:10px;

cursor:default;

border:none;

}

/* নোটিশের নিচের টেক্সট */

.notice-text{

color:#000;

font-size:18px;

text-align:center;

margin-bottom:16px;

line-height:1.5;

}

.amount{

background:#f0fff0;

padding:12px;

border-radius:10px;

border:1px dashed #00cc66;

margin:12px 0;

display:flex;

align-items:center;

justify-content:space-between

}

.amount .val{

font-size:20px;

font-weight:700;

color:var(--green)

}

.btn{

display:block;

width:100%;

padding:12px;

margin-top:12px;

border:none;

border-radius:10px;

background:var(--accent);

color:#fff;

font-weight:600;

font-size:15px;

cursor:pointer;

text-align:center;

text-decoration:none;

transition:background 0.3s

}

.btn:hover{background:var(--accent-dark)}

.btn-help{

background:var(--whatsapp);

}

.btn-help:hover{background:#1ebe57}

.btn-withdraw{

background:var(--green);

margin-top:8px;

}

.btn-withdraw:hover{background:#1e7e34}

.withdraw-form{

display:none;

flex-direction:column;

gap:8px;

margin-top:12px;

}

.withdraw-form input,.withdraw-form select{

padding:10px;

border-radius:8px;

border:1px solid #ccc;

width:100%;

font-size:14px

}

footer{

background:#ffccff;

color:#333;

padding:20px;

text-align:center;

border-top:1px solid #ddd;

margin-top:16px;

font-size:14px;

width:100%;

box-sizing:border-box

}

footer h3{

margin-bottom:8px;

font-size:16px;

color:var(--accent)

}

footer p{

margin:4px 0;

font-size:13px;

color:#666

}

.social-icons{

margin-top:12px;

}

.social-icons img{

width:30px;

height:30px;

border-radius:50%;

margin:0 6px;

transition:transform 0.3s

}

.social-icons img:hover{transform:scale(1.3);}

@media(max-width:420px){.card{width:92vw}}

</style>

</head>  

<body>  <div class="card" role="main">  

  <div class="logo">  

    <div class="dot">MB</div>  

    <div class="brand">My Business</div>  

  </div>    <!-- ওয়েলকাম -->    <div class="welcome-text">Welcome</div>    <!-- নোটিশ বাটন -->    <div class="notice-btn">নোটিশ</div>    <!-- নোটিশ টেক্সট -->    <div class="notice-text">  

    1/ 📝 ফরম পূরণ করে স্ক্রিনশট পাঠালে 💰 ১০০ টাকা পেয়ে যান!<br>  

    2/ 🎁 রেজিস্ট্রেশন করলে ২০০ টাকা পাবেন 🏆💙  

  </div>    <!-- ভিডিও বাটন -->    <a class="btn" href="পেন্ডিং আছে" target="_blank">  

    🎥 ভিডিও দেখে ফরম পূরণ করুন  

  </a>    <!-- ফরম বাটন -->  <a class="btn" href="https://mybusinesselearningplatform.com/sign-up/7770028" target="_blank"  

onclick="copyAndGo(event,'https://mybusinesselearningplatform.com/sign-up/1741282','ফরম পূরণ করে রেজিস্ট্রেশন করুন')">

📋 ফরম পূরণ করে রেজিস্ট্রেশন করুন

</a>

  <!-- WhatsApp বাটন -->  <a class="btn btn-help" href="https://wa.me/8801749799622" target="_blank" id="waBtn">📤 স্ক্রিনশট পাঠান / হেল্প</a>

  <!-- Withdraw -->  <button class="btn btn-withdraw" id="withdrawBtn">উইন্ডোজ / Withdraw</button>

  <div class="withdraw-form" id="withdrawForm">  

    <select id="method">  

      <option value="Bkash">Bkash</option>  

      <option value="Nagad">Nagad</option>  

      <option value="Rocket">Rocket</option>  

    </select>  

    <input type="text" id="account" placeholder="আপনার অ্যাকাউন্ট নাম্বার লিখুন">  

    <input type="number" id="amountInput" placeholder="টাকার পরিমাণ লিখুন">  

    <button class="btn btn-withdraw" id="submitWithdraw">উইন্ডোজ করুন</button>  

  </div>    <div class="amount">  

    <div>  

      <div style="font-size:12px;color:var(--muted)">আপনার পাওনা টাকা</div>  

      <div class="val" id="amount">৳0</div>  

    </div>  

    <div style="text-align:right;font-size:12px;color:var(--muted)">রেফার দিয়ে আয় করুন</div>  

  </div>  

</div>  <!-- FOOTER -->  <footer>  

<h3>Contact Info</h3>  

<p><strong>Phone:</strong> 01749799622</p>  

<p><strong>E-mail:</strong> stylezone2424@gmail.com</p>  

<p><strong>Location:</strong> Narayanganj, Bangladesh</p>  <div class="social-icons">  

  <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="YouTube" title="YouTube">  

  <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook" title="Facebook">  

  <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" title="Instagram">  

  <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" alt="Telegram" title="Telegram">  

  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn" title="LinkedIn">  

  <a href="https://wa.me/8801749799622" target="_blank" title="WhatsApp">  

    <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">  

  </a>  

</div>  

</footer>  <script>  

const amountEl=document.getElementById('amount');  

const withdrawBtn=document.getElementById('withdrawBtn');  

const withdrawForm=document.getElementById('withdrawForm');  

  

let balance=Number(localStorage.getItem('ref_balance')||0);  

let earnedOnce=localStorage.getItem('earned_once')==='true';  

  

function render(){amountEl.textContent='৳'+balance;}  

render();  

  

function copyAndGo(event,url,text){  

  event.preventDefault();  

  navigator.clipboard.writeText(text).then(()=>{window.open(url,'_blank');})  

  .catch(()=>{window.open(url,'_blank');});  

}  

  

// WhatsApp বাটন  

document.getElementById('waBtn').addEventListener('click',()=>{  

  if(!earnedOnce){  

    balance+=100;  

    localStorage.setItem('ref_balance',balance);  

    localStorage.setItem('earned_once','true');  

    earnedOnce=true;  

    render();  

    alert('ধন্যবাদ! স্ক্রিনশট পাঠানোর জন্য ১০০ টাকা আপনার ব্যালান্সে যোগ হয়েছে।');  

  } else {  

    alert('আপনি ইতিমধ্যেই স্ক্রিনশট পাঠিয়েছেন, অতিরিক্ত টাকা যোগ হবে না।');  

  }  

});  

  

// Withdraw  

withdrawBtn.addEventListener('click',()=>{withdrawForm.style.display='flex';});  

document.getElementById('submitWithdraw').addEventListener('click',()=>{  

  const method=document.getElementById('method').value;  

  const account=document.getElementById('account').value;  

  const amountInput=Number(document.getElementById('amountInput').value);  

  

  if(amountInput<2000){  

    alert('⚠️ ব্যালান্স কম, উইন্ডোজ সফল হবে না।');  

    return;  

  }  

  if(amountInput>balance){  

    alert('⚠️ আপনার ব্যালান্সে পর্যাপ্ত টাকা নেই।');  

    return;  

  }  

  balance-=amountInput;  

  localStorage.setItem('ref_balance',balance);  

  render();  

  alert(`✅ ${method} মাধ্যমে উইন্ডোজ সফল হয়েছে।\nঅ্যাকাউন্ট: ${account}\nটাকা: ${amountInput} টাকা`);  

  withdrawForm.style.display='none';  

});  

</script>  </body>  

</html>  
