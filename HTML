<!DOCTYPE html>
<html lang="gu">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Anjali Beauty Parlour</title>
<style>
:root{
  --pink:#ffd9ec;
  --accent:#d12b6a;
  --muted:#4b4b4b;
}
body{
  font-family:Arial,Helvetica,sans-serif;
  background:linear-gradient(180deg,#fff,#ffeef6);
  margin:0;
  color:var(--muted);
}
header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:16px;
}
header img{
  width:70px;
  height:70px;
  border-radius:50%;
  cursor:pointer;
}
.btn-small{
  background:var(--accent);
  color:#fff;
  padding:8px 14px;
  border:none;
  border-radius:8px;
  cursor:pointer;
}
.container{
  max-width:820px;
  margin:0 auto;
  padding:16px;
}
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(160px,1fr));
  gap:12px;
}

/* ====== SERVICE BOX + ANIMATION ====== */
.service-box{
  background:#fff;
  border-radius:12px;
  padding:12px;
  text-align:center;
  cursor:pointer;
  border:2px solid transparent;
  box-shadow:0 4px 10px rgba(0,0,0,0.06);
  user-select:none;
  transition:
    transform .18s ease,
    box-shadow .18s ease,
    border-color .18s ease,
    background .18s ease;
}
.service-box:active{
  transform:scale(.96);
}
.service-box.selected{
  border-color:var(--accent);
  background:#ffe6f2;
  box-shadow:0 10px 20px rgba(0,0,0,0.15);
  transform:translateY(-2px) scale(1.02);
  animation:servicePop .22s ease-out;
}
@keyframes servicePop{
  0%{transform:scale(.9);}
  60%{transform:scale(1.05);}
  100%{transform:translateY(-2px) scale(1.02);}
}

.form-box,input,textarea,button{
  font-size:15px;
}
.form-box{
  display:none;
  background:#fff;
  padding:16px;
  border-radius:12px;
  margin-top:14px;
  box-shadow:0 4px 12px rgba(0,0,0,0.08);
}
.chips{
  display:flex;
  gap:8px;
  flex-wrap:wrap;
  margin:8px 0;
}
.chip{
  padding:6px 10px;
  background:#fff;
  border-radius:20px;
  border:1px solid #ccc;
  display:flex;
  gap:6px;
  align-items:center;
}
.chip button{
  background:transparent;
  border:none;
  color:var(--accent);
  font-weight:700;
  cursor:pointer;
}

/* ====== MODALS ====== */
.modal{
  position:fixed;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background:rgba(0,0,0,0.6);
  display:flex;
  align-items:center;
  justify-content:center;
  visibility:hidden;
  opacity:0;
  transition:.2s;
  z-index:50;
}
.modal.show{
  visibility:visible;
  opacity:1;
}
.modal-card{
  background:#fff;
  padding:20px;
  border-radius:12px;
  width:90%;
  max-width:420px;
}

/* ====== INPUTS ====== */
input,textarea{
  width:100%;
  padding:10px;
  border-radius:8px;
  border:1px solid #e6e6e6;
  margin-top:8px;
}

/* ====== LEHENGA CARD STYLING ====== */
.lehenga-card{
  background:#fff;
  padding:16px;
  border-radius:12px;
  box-shadow:0 4px 12px rgba(0,0,0,0.06);
  text-align:center;
}
.lehenga-image-wrap{
  display:flex;
  justify-content:center;
  margin-bottom:10px;
}
.lehenga-image-wrap img{
  max-width:180px;   /* small by default */
  border-radius:12px;
  cursor:pointer;
  transition:transform .18s ease, box-shadow .18s ease;
}
.lehenga-image-wrap img:hover{
  transform:scale(1.05);
  box-shadow:0 8px 16px rgba(0,0,0,0.18);
}
.lehenga-actions{
  display:flex;
  gap:8px;
  justify-content:center;
  flex-wrap:wrap;
}

@media (max-width:480px){
  .grid{
    grid-template-columns:repeat(2,1fr);
  }
  header img{
    width:56px;
    height:56px;
  }
}
</style>
</head>
<body>

<header>
  <h2 style="color:var(--accent);margin:0">Anjali Beauty Parlour</h2>
  <div style="display:flex;gap:10px;align-items:center">
    <img src="LOGO.png" onclick="openQuote()" title="બીજા પ્રસ્નો માટે" alt="લોગો" />
  </div>
</header>

<div class="container">
  <h2 style="color:var(--accent);margin-top:0">સેવા પસંદ કરો</h2>
  <div class="grid" id="services">
    <div class="service-box" data-name="I-Brow">આઇ-બ્રો</div>
    <div class="service-box" data-name="Facial">ફેશિયલ</div>
    <div class="service-box" data-name="WAX">વૅક્સ</div>
    <div class="service-box" data-name="Makeup">મેકઅપ</div>
    <div class="service-box" data-name="Bridal Makeup">લગ્ન મેકઅપ</div>
    <div class="service-box" data-name="Bridal Choli (Rent)">લેહેંગા (ભાડે)</div>
    <div class="service-box" data-name="Mehndi">મેહંદી</div>
    <div class="service-box" data-name="Other">Other</div>
  </div>

  <div class="form-box" id="formBox">
    <h3>પસંદ કરેલ સેવા (Select Option)</h3>
    <div class="chips" id="chips"></div>

    <div id="otherBox" style="display:none;margin-top:10px">
      <textarea id="otherText" placeholder="અન્ય જરૂરિયાત અહીં લખો"></textarea>
    </div>

    <h3 style="margin-top:10px">બુકિંગ માહિતી</h3>
    <!-- ID FIXED: uname (JS માં જે વપરાયેલું છે એજ) -->
    <input type="text" id="uname" placeholder="નામ" />
    <input type="date" id="date" />
    <input type="tel" id="phone" maxlength="10" placeholder="મોબાઇલ નંબર" />

    <button class="btn-small" style="margin-top:10px" id="sendBtn">વોટ્સએપ પર મોકલો</button>
  </div>

  <h2 style="margin-top:26px;color:var(--accent)">લેહેંગા રેન્ટ</h2>
  <div class="lehenga-card">
    <div class="lehenga-image-wrap">
      <img src="lehenga.jpg" id="lehengaImg" alt="લેહેંગા" />
    </div>
    <div class="lehenga-actions">
      <button class="btn-small" id="lehengaViewBtn">View</button>
      <button class="btn-small" id="rentBtn">Select for Rent</button>
    </div>
    <p style="font-size:13px;margin-top:8px;color:#777">
      ફોટો જોયા વગર પણ “Select for Rent” પર ક્લિક કરીને બુકિંગ માટે લેહેંગા પસંદ કરી શકો છો.
    </p>
  </div>
</div>

<!-- BOOKING MODAL -->
<div class="modal" id="confirmModal">
  <div class="modal-card">
    <h3>વોટ્સએપ ખોલાયું</h3>
    <p>મેસેજ મોકલી બુકિંગ પુષ્ટિ કરો.</p>
  </div>
</div>

<!-- QUOTATION MODAL -->
<div class="modal" id="quoteModal">
  <div class="modal-card">
    <h3>કોટેશન માંગો</h3>
    <input type="text" id="qname" placeholder="નામ" />
    <input type="tel" id="qphone" placeholder="મોબાઇલ નંબર" />
    <textarea id="qmsg" placeholder="તમારો પ્રસન લખો"></textarea>
    <button class="btn-small" style="margin-top:10px" id="quoteSend">મોકલો</button>
    <button class="cancel" style="margin-top:6px" onclick="closeQuote()">બંધ કરો</button>
  </div>
</div>

<!-- LEHENGA IMAGE VIEW MODAL -->
<div class="modal" id="imageModal">
  <div class="modal-card" style="max-width:480px">
    <h3 style="margin-top:0">લેહેંગા View</h3>
    <img src="lehenga.jpg" alt="લેહેંગા મોટું" style="width:100%;border-radius:12px;margin-top:8px" />
    <button class="cancel" style="margin-top:10px" onclick="closeImage()">બંધ કરો</button>
  </div>
</div>

<script>
/* ====== ELEMENTS ====== */
const serviceBoxes = document.querySelectorAll('.service-box');
const formBox = document.getElementById('formBox');
const chipsEl = document.getElementById('chips');
const otherBox = document.getElementById('otherBox');
const otherText = document.getElementById('otherText');
const sendBtn = document.getElementById('sendBtn');
const rentBtn = document.getElementById('rentBtn');

const lehengaImg = document.getElementById('lehengaImg');
const lehengaViewBtn = document.getElementById('lehengaViewBtn');
const imageModal = document.getElementById('imageModal');

let selectedServices = [];

/* ====== SERVICE BOX CLICK ====== */
serviceBoxes.forEach(box => {
  box.addEventListener('click', () => {
    const name = box.getAttribute('data-name');
    toggleService(name);
  });
});

/* rent button: select Bridal Choli (Rent) and open form */
rentBtn.addEventListener('click', () => {
  const rentName = 'Bridal Choli (Rent)';
  if (!selectedServices.includes(rentName)) selectedServices.push(rentName);
  updateUI();
  scrollToForm();
});

/* toggle service in array */
function toggleService(name){
  const i = selectedServices.indexOf(name);
  if(i === -1) selectedServices.push(name);
  else selectedServices.splice(i,1);
  updateUI();
}

/* update UI: chips, form visibility, selected class, otherBox visibility */
function updateUI(){
  // clear chips
  chipsEl.innerHTML = '';

  // update selected class on boxes
  serviceBoxes.forEach(box => {
    const nm = box.getAttribute('data-name');
    if(selectedServices.includes(nm)) box.classList.add('selected');
    else box.classList.remove('selected');
  });

  // build chips
  selectedServices.forEach((s, idx) => {
    const chip = document.createElement('div');
    chip.className = 'chip';
    chip.innerHTML = `${s} <button data-idx="${idx}" aria-label="remove">×</button>`;
    chipsEl.appendChild(chip);
    chip.querySelector('button').addEventListener('click', (e) => {
      const i = Number(e.target.getAttribute('data-idx'));
      removeService(i);
    });
  });

  // show/hide form
  formBox.style.display = selectedServices.length ? 'block' : 'none';

  // show other box if 'Other' selected
  otherBox.style.display = selectedServices.includes('Other') ? 'block' : 'none';
}

/* remove by index */
function removeService(index){
  if(index >= 0 && index < selectedServices.length){
    selectedServices.splice(index,1);
    updateUI();
  }
}

/* scroll to form smoothly */
function scrollToForm(){
  setTimeout(()=> {
    formBox.scrollIntoView({behavior:'smooth', block:'center'});
  }, 100);
}

/* phone validation simple */
function validPhone(p){ return /^\d{10}$/.test(p); }

/* send booking: build message in Gujarati and open WhatsApp */
sendBtn.addEventListener('click', () => {
  const name = document.getElementById('uname').value.trim();
  const date = document.getElementById('date').value;
  const phone = document.getElementById('phone').value.trim();
  const otherVal = (otherText && otherText.value.trim()) || '';

  if(selectedServices.length === 0){
    alert('કૃપા કરીને સેવા પસંદ કરો');
    return;
  }
  if(!name){
    alert('કૃપા કરીને તમારું નામ લખો');
    return;
  }
  if(!date){
    alert('કૃપા કરીને તારીખ પસંદ કરો');
    return;
  }
  if(!validPhone(phone)){
    alert('કૃપા કરીને સારો 10 અંકનો ફોન નંબર લખો');
    return;
  }

  let servicesText = selectedServices.join(', ');
  if(selectedServices.includes('Other') && otherVal){
    servicesText += ' (અન્ય: ' + otherVal + ')';
  }

  const msg = `સેવા: ${servicesText}\nનામ: ${name}\nતારીખ: ${date}\nફોન: ${phone}`;
  const url = `https://api.whatsapp.com/send?phone=919106177279&text=${encodeURIComponent(msg)}`;
  window.open(url, '_blank');

  // show confirmation modal briefly
  const confirmModal = document.getElementById('confirmModal');
  confirmModal.classList.add('show');
  setTimeout(()=> confirmModal.classList.remove('show'), 2000);
});

/* QUOTATION modal handlers */
function openQuote(){
  document.getElementById('quoteModal').classList.add('show');
}
function closeQuote(){
  document.getElementById('quoteModal').classList.remove('show');
}
document.getElementById('quoteSend').addEventListener('click', () => {
  const n = document.getElementById('qname').value.trim();
  const p = document.getElementById('qphone').value.trim();
  const m = document.getElementById('qmsg').value.trim();
  if(!n||!p||!m){
    alert('કૃપા કરીને બધાં ફીલ્ડ ભરો');
    return;
  }
  if(!validPhone(p)){
    alert('કૃપા કરીને સારો 10 અંકનો ફોન નંબર લખો');
    return;
  }
  const msg = `કોટેશન વિનંતિ\nનામ: ${n}\nફોન: ${p}\nમેસેજ: ${m}`;
  window.open(`https://api.whatsapp.com/send?phone=919106177279&text=${encodeURIComponent(msg)}`, '_blank');
  closeQuote();
});

/* LEHENGA IMAGE VIEW HANDLERS */
function openImage(){
  imageModal.classList.add('show');
}
function closeImage(){
  imageModal.classList.remove('show');
}
lehengaViewBtn.addEventListener('click', openImage);
lehengaImg.addEventListener('click', openImage);

/* init */
updateUI();
</script>

</body>
</html>
