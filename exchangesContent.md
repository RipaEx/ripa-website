<div id="exchanges" />

<div class="index-features" data-scroll style="margin: 80px auto 0; max-width: 1400px;">
  <section class="container">
    <div class="row">
      <div class="col-12 center">
        <header>
          <h3 style="color: #D4AF37">Exchanges</h3>
          <p>List of all exchanges where you can trade XPX coins, along with live charts from CryptoCompare and historical data.</p>
        </header>
      </div>
    </div>
    <div class="row">
      <div class="container nspArt">
        <div class="row">
          <div class="col-sm nspInvestmentLevelsBox nevenInvestmentLevelsTextV">
            <a href=""><img alt="Graviex" title="Graviex" class="nspImageExchanges" src="images/listingServices/coming-soon-red-stamp-text.jpg" /></a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-12 center">
        <header>
          <p>XPX Historical Exchange Rate Chart</p>
        </header>
      </div>
      <div class="col-12 center">
        <script type="text/javascript">
        baseUrl = "https://widgets.cryptocompare.com/";
        var scripts = document.getElementsByTagName("script");
        var embedder = scripts[ scripts.length - 1 ];
        (function (){
        var appName = encodeURIComponent(window.location.hostname);
        if(appName==""){appName="local";}
        var s = document.createElement("script");
        s.type = "text/javascript";
        s.async = true;
        var theUrl = baseUrl+'serve/v3/coin/chart?fsym=RIPAX&tsyms=EUR,BTC,USD,GBP,JPY,GOLD';
        s.src = theUrl + ( theUrl.indexOf("?") >= 0 ? "&" : "?") + "app=" + appName;
        embedder.parentNode.appendChild(s);
        })();
        </script>
      </div>
      <div class="col-12 center">
        <script type="text/javascript">
        baseUrl = "https://widgets.cryptocompare.com/";
        var scripts = document.getElementsByTagName("script");
        var embedder = scripts[ scripts.length - 1 ];
        var cccTheme = {"General":{"borderColor":"rgba(93,93,93,0.4)"}};
        (function (){
        var appName = encodeURIComponent(window.location.hostname);
        if(appName==""){appName="local";}
        var s = document.createElement("script");
        s.type = "text/javascript";
        s.async = true;
        var theUrl = baseUrl+'serve/v1/coin/histo_week?fsym=RIPAX&tsym=BTC';
        s.src = theUrl + ( theUrl.indexOf("?") >= 0 ? "&" : "?") + "app=" + appName;
        embedder.parentNode.appendChild(s);
        })();
        </script>
      </div>
    </div>
  </section>
</div>