## AdBlock Javascript
AdBlock yang dapat digunakan dengan mudah hanya menggunakan beberapa baris kode saja.

## Installation
Copy dan paste kode di bawah ini di atas tag `</body>`
```html
<div class="adb" id="adb">                  
  <div class="adbs">                      
    <h3>Terdeteksi ADBLOCK</h3>                      
    <p>Silahkan nonaktifkan ADBLOCK/Pemblokir Iklan di Browser Kalian :)</p>                  
  </div>              
</div>

<script src="https://adikfilm.link/assets/prebid.js"></script>

<script type="text/javascript">      
  if( window.adikAds === undefined ){
    // Lakujan sesuatu jika AdBlock terdeteksi
    document.getElementById("adb").setAttribute("style", "display:block");
  };
</script>
```

Dan tambahkan style dengan paste kode di bawah ini di atas tag `</head>`
```html
<style type="text/css">
   .adb {
    display: none;
    position: fixed;
    width: 100%;
    height: 100%;
    left: 0;
    top: 0;                  
    bottom: 0;                  
    background: rgba(51, 51, 51, 0.7);
    z-index: 10000;                  
    text-align: center;                  
    color: #111;              
  }                

  .adbs {                  
    margin: 0 auto;                  
    width: auto;                  
    min-width: 400px;                  
    position: fixed;                  
    z-index: 99999;                  
    left: 50%;                  
    top: 50%;                  
    transform: translate(-50%, -50%);                  
    padding: 20px 30px 30px;                  
    background: rgba(255, 255, 255, 0.9);                  
    -webkit-border-radius: 12px;                  
    -moz-border-radius: 12px;                  
    border-radius: 12px;              
  } 
</style>
```

## Support Block
Plugin Support:
- AdBlock
- Adblock Plus
- Adblock Pro
- Ghostery
- UBlock Origin

Browser Support:
- Brave
- Uc Browser
- Opera
- Opera Mini
- Chrome
- Dll