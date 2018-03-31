---
layout: default
---

<div class="business-hero">
    <div class="container">
        <h2 class="customFadeInUp">
            An hybrid-decentralized OpenSource exchange built on the ARK blockchain technology.
        </h2>
        <p class="customFadeInUp">
            Ripa Exchange is a hybrid-decentralized exchange with a strong focus on lowering the entry level for opening new exchanges and giving crypto traders safe and secure trading partners to operate on a daily basis.
        </p>

        <div class="actions customFadeInUp" data-toggle="modal" data-target="#video-modal">
            <button class="btn-shadow btn-shadow-info mr-md-1">Watch Intro Video</button>
        </div>

    </div>
</div>

<div class="modal fade" tabindex="-1" role="dialog" id="video-modal">
  <div class="modal-dialog modal-lg modal-xlg">
    <div class="modal-content">
        <div class="modal-body">
        <div class="embed-responsive  embed-responsive-16by9">
            <iframe id="youtube_player" class="yt_player_iframe" type="text/html" src="https://www.youtube.com/embed/X94qHbZBYA8?enablejsapi=1&version=3&playerapiid=ytplayer" 
            frameborder="0" allowscriptaccess="always">
            </iframe>
        </div>
      </div>
    </div>
  </div>
</div>
<script>
$('#video-modal').on('hide.bs.modal', function (e) {
   $('.yt_player_iframe')[0].contentWindow.postMessage('{"event":"command","func":"' + 'stopVideo' + '","args":""}', '*');
});
</script>



<div class="spacial-features" data-scroll style="    margin: 80px auto 0;
                                                     max-width: 1400px;">
    <section class="container">
        <div class="row">
            <div class="col-12">
                <div class="header">
                    <h2>The Exchange</h2>
                    <p>
                        The Ripa Exchange is built based on the Open Source code of <a href="https://www.peatio.tech">Peatio [貔貅]</a> and thanks to RLSP (Ripa Liquidity Service Provider) each exchange in the RIPA network will share the same orderbook giving exchange managers a liquidity to offer to their end users from day 1.
                    </p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4">
                <div class="feature">
                    <h3>
                        Open Source
                    </h3>
                    <p style="text-align: justify;">
                        Ripa Exchange is and always will be free of charge for exchange managers: you will have only to pay for server, network security operations, call center operators and other resources needed to run an exchange and give platinum support to your clients.
                    </p>
                    <p style="text-align: justify;">
                        You can make all the customization you want on the source code as all the source base is released under the MIT license.
                    </p>
                    <p style="text-align: right;">
                        <a class="btn-sm btn-shadow btn-shadow-info" href="listeners">
                            Learn More
                        </a>
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="feature">
                    <h3>
                        Bank Grade Security
                    </h3>
                    <p style="text-align: justify;">
                        AES256 encryption keys and all the design of the exchange is build with a focus on security. Ruby on Rails is know to be a secure development environment for developers but we choose to complitely re-modularize the Peatio source base to make complete separation from the clients registry to the trading engine so no end users data will be compromised if the attacker is able to overcame  the first level of security.
                    </p>
                    <p style="text-align: justify;">
                        International AML/KYC standards are in place to secure compliance for your exchange in whichever country you want to install your instance.
                    </p>
                    <p style="text-align: right;">
                        <a class="btn-sm btn-shadow btn-shadow-info" href="services">
                            Learn More
                        </a>
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="feature">
                    <h3>
                        Ripa Liquidity Service Provider
                    </h3>
                    <p style="text-align: justify;">
                        RLSP is developed to permits you to have liquidity to offer to your clients from day 1 of your exchanges operation: your new Ripa Exchange instance will interface with the RIPA blockchain* to get all the liqudidy available in the exchanges network.
                    </p>
                    <p style="text-align: justify;">
                        Exchange A that open the order will get 0,10% as transaction fee.
                    </p>
                    <p style="font-size: 70%;">
                        * thank you to ACES-ARK technology
                    </p>
                    <p style="text-align: right;">
                        <a class="btn-sm btn-shadow btn-shadow-info" href="/marketplace">
                            Learn More
                        </a>
                    </p>
                </div>
            </div>
        </div>
    </section>

</div>


<div class="index-clients">
    <div class="container">
        <header>
            <h4>Platform Statistics</h4>
        </header>
        <div class="about-2-stats">

            <div class="container">
                <div class="row">
                    <div class="col-md-3 text-center">
                        <span>4</span>
                        <p>Listeners</p>
                    </div>
                    <div class="col-md-3 text-center">
                        <span>3</span>
                        <p>Services</p>
                    </div>
                    <div class="col-md-3 text-center">
                        <span>1</span>
                        <p>Marketplaces</p>
                    </div>
                    <div class="col-md-3 text-center">
                        <span>0 BTC</span>
                        <p>Volume</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="index-features" data-scroll>
    <div class="container">
        <header>
            <h3>Platform Features</h3>
        </header>
        <section class="features">
            <div class="row">
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Open Source
                        </h4>
                        <p>
                            Everything on the ACES platform is open source and uses a permissive free software license (MIT).
                        </p>
                    </section>
                </div>
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            REST-ful APIs
                        </h4>
                        <p>
                            The ACES platform uses simple REST-ful APIs for easy integration.
                        </p>
                    </section>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Decentrallized
                        </h4>
                        <p>
                            A marketplace platform that allows users to consume blockchain services offered by a 
                            decentralized collection of service providers. 
                        </p>
                    </section>
                </div>
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Service Composition
                        </h4>
                        <p>
                            Use functional composition to chain ACES Services together.
                        </p>
                    </section>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Incentivized
                        </h4>
                        <p>
                            The ACES platform provides an open fee model that allows service providers
                            to compete in a free market.
                        </p>
                    </section>
                </div>
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Programming Languages
                        </h4>
                        <p>
                            Built using light-weight microservices that are easy for providers
                            to implement in different programming languages and frameworks.
                        </p>
                    </section>
                </div>
            </div>
        </section>
    </div>
</div>


<div class="index-devices" data-scroll>
    <section class="clearfix">
        <img src="assets/images/aces-marketplace-contract-form.png" class="img-fluid devices"  style="border:1px solid #ddd"/>

        <h4>ACES Marketplace Console</h4>
        <p>
            The ACES Marketplace Console provides a simple web interface for tapping into available 
            ACES Services listed on the public marketplace directory. An integrated payment wallet allows
            service contracts to be executed and payed for directly though the Marketplace Console.
        </p>

        <p>
            <a class="btn-shadow btn-shadow-info mr-md-1" href="marketplace">
                Learn More
            </a>
        </p>
    </section>
</div>


<div class="business-single-client" style="height: 400px" data-scroll>
    <div class="quote-wrapper">
        <p>
            "Starting an exchange shouldn't be hard, what is hard is to give platinum support to your clients, comply with international regulations and have reliable banking partners to operate with: you should focus on that while the code and liquidity to start your exchanges operations is given to you free of charge."
        </p>
    </div>
</div>



<div class="agency-from-the-blog" style="display:none">
    <div class="container">
        <h3>Latest Posts</h3>
        <div class="row">
            <div class="col-md-4">
                <div class="post">
                    <a href="#" class="pic" style="background-image:url('images/unsplash/photo-1422665717225-1a37f226c92a.jpg');">
                    </a>
                    <div class="title">
                        A Future of Cryptocurrencies and Blockchains
                    </div>
                    <div class="min-read">
                        3 min read
                    </div>
                    <p>
                        What is the real world use case for ACES? The real world use case may not have arrived quite yet, but it’s fast approaching.
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                    <a href="#" class="pic" style="background-image:url('images/unsplash/photo-1424873380396-9580028d74db.jpg');">
                    </a>
                    <div class="title">
                        ACES Completes ARK Authentication Listeners for ARK, Bitcoin, Ethereum, and Litecoin
                    </div>
                    <div class="min-read">
                        4 min read
                    </div>
                    <p>
                        This release is an expansion and improvement to our existing listener protocol, providing high 
                        quality features that will support a robust blockchain service ecosystem. This release also includes
                        deployment of stake-based listeners for ARK and Ethereum, which you can begin using immediately to 
                        build services. We will be deploying two additional listeners for Bitcoin and Litecoin alongside 
                        our release of services in the coming weeks.
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                    <a href="#" class="pic" style="background-image:url('images/unsplash/photo-1478059425650-ca13d6d422f4.jpg');">
                    </a>
                    <div class="title">
                        Development of the ARK and Bitcoin Listeners Completed
                    </div>
                    <div class="min-read">
                        3 min read
                    </div>
                    <p>
                        The listener is the component that plugs into a blockchain (such as Bitcoin) and provides 
                        standardized API access for ARK services to receive data from a blockchain. The listener stands 
                        on its own, and does not necessarily need to be run by the same person running a service.
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>


<div class="index-clients">
    <div class="container">
        <header>
            <h4>Connecting the best blockchain technologies</h4>
        </header>
        <div class="row justify-content-center icons">
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc ARK" title="ARK"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc BTC" title="BTC"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc LTC" title="LTC"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc XMR" title="XMR"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc ETH" title="ETH"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc IOTA" title="IOTA"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc NEO" title="NEO"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc SIA" title="SIA"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc GNT" title="GNT"></i>
            </div>
        </div>
    </div>
</div>


<div class="row">
    <div class="col-12">
        <div class="cta text-center">
            <h1 class="cta-title title">
                Join the Crypto Revolution today.
            </h1>
            <a class="btn-shadow btn-shadow-info mr-md-1" href="https://tec.ripaex.io/">
                Buy XPX NOW
            </a>
            <a class="btn-shadow btn-shadow-info mr-md-1" href="https://github.com/RipaEx/">
                Start your exchange
            </a>
        </div>
    </div>
</div>

