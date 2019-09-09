---
title: "Home"
date: 2019-09-06T09:54:25+12:00
draft: true
kind: "home"
---

<section class="hero is-small" >
    <div class="hero-body">
        <div class="container is-fluid">
            <div class="columns is-vcentered">
                <div class="column is-half has-text-centered">
                    <h1 class="title is-1" style="padding-bottom: 20px;">
                        Trusted <span style="font-style: italic; font-size: larger">Work-time</span> compliance tools
                    </h1>
                    <div class="container ">
                        <img src="images/nzta-approved.png" alt="logmate is an NZ Transport Agency approved Electronic Logbook platform" />
                    </div>                                                       
                </div>
                <div class="column">
                    <img src="images/v2-devices.png" alt="logmate tools include a logbook app and admin portals">
                </div>
            </div>
        </div>
    </div>
</section>

<section class="" style="padding-top: 40px; padding-bottom: 40px; border-top: 1px solid lightgrey;">
    <div class="container is-fluid">
        <div class="columns">            
            <div class="column is-4">
                <p style="text-align: center; font-size: xx-large">
                    <span class="fas fa-fire-extinguisher"></span>
                </p>
                <p style="text-align: center; font-size: large; margin-top: 10px;">
                    <span style="font-weight: bold">
                        Risk Mitigation
                    </span>
                </p>
                <p style="text-align: center; font-size: large; margin-top: 10px;">
                    <span style="">
                    Reduce risk of Fines &amp; Prosecution.      
                    </span>
                </p>
            </div>
            <div class="column is-4">
                <p style="text-align: center; font-size: xx-large">
                    <span class="fas fa-balance-scale"></span>
                </p>
                <p style="text-align: center; font-size: large; margin-top: 10px;">
                    <span style="font-weight: bold">
                        Compliance
                    </span>
                </p>
                <p style="text-align: center; font-size: large; margin-top: 10px;">                    
                    Meet your <span style="font-style: italic">Health &amp; Safety process</span> obligations.<br />
                    Streamline your <span style="font-style: italic">Logbook compliance</span> administration.                         
                </p>
            </div>
            <div class="column is-4">
                <p style="text-align: center; font-size: xx-large">
                    <span class="fas fa-medal"></span>
                </p>
                <p style="text-align: center; font-size: large; margin-top: 10px;">
                    <span style="font-weight: bold">
                        Industry leadership
                    </span>
                </p>
                <p style="text-align: center; font-size: large; margin-top: 10px;">
                    <span style="">
                    Demonstrate a <span style="font-style: italic">genuine commitment</span> to Safety.      
                    </span>
                </p>
            </div>            
        </div>
    </div>
</section>

<section class="" style="padding-top: 40px; padding-bottom: 40px; border-top: 1px solid lightgrey;">
    <div class="columns has-text-centered">        
        <div class="column">
            <a type="button" href="http://play.google.com/store/apps/details?id=nz.co.logmate.app"><img src="images/googleplay.png" alt="Available from Google Play" class="bg-black appstore-boxes"></a>
        </div>
        <div class="column">
            <a type="button" href="https://itunes.apple.com/nz/app/logmate/id881398880?mt=8&amp;uo=4" target="itunes_store"><img src="images/appstore.png" alt="Available on the AppStore" class="bg-black appstore-boxes"></a>
        </div>        
    </div>
</section>

<section class="" style="padding-top: 40px; padding-bottom: 40px; border-top: 1px solid lightgrey;">
    {{ .Site.BaseURL }}
    {{ range $feature := $.Site.Data.features }}
        
        <div class="columns is-vcentered">
            <div class="column is-3 is-offset-3 has-text-centered">
                <p><img title="{{ $feature.title }}" src="images/{{ $feature.image.file_name }}" alt="paper" width="100" height="100"></p>
            </div>
            <div class="column is-3 has-text-centered">
                <div class="container">
                    <h4 class="title is-4">{{ $feature.title }}</h4>
                    {{ range $descriptor := $feature.descriptors }}
                    <p>{{ $descriptor }}</p>
                    {{ end }}
                </div>
            </div>
        </div>
        
    {{ end }}
</section>

<!-- Pricing plans -->

<section class="" style="padding-top: 40px; padding-bottom: 40px; border-top: 1px solid lightgrey;">
    <div class="container is-fluid has-text-centered" style="padding-bottom: 60px;">
        <h2 class="title is-3">Pricing</h2>
    </div>
    <div class="container is-fluid">               
        <div class="pricing-table">        
            <div class="pricing-plan">
                <div class="plan-header">Logbook subscription</div>
                <div class="plan-price"><span class="plan-price-amount"><span class="plan-price-currency">$</span>11<span style="font-size: smaller">.95</span></span>/ month / driver</div>
                <div class="plan-items">                    
                    <div class="plan-item">Access to latest Logbook App</div>
                    <div class="plan-item">Dedicated web-based Admin panel</div>
                    <div class="plan-item">Perpetual Logbook data storage</div>
                    <div class="plan-item">Automatic logbook delivery to all TSL Holders</div>
                    <div class="plan-item">Unlimited Customer Support - Chat &amp; Email only</div>                    
                </div>
                <div class="plan-footer">
                    A driver must have an valid subscription to create entries in their logbook
                </div>
            </div>
      
            <div class="pricing-plan">
                <div class="plan-header">TSL Holder</div>
                <div class="plan-price"><span class="plan-price-amount"><span class="plan-price-currency">$</span>0</span>/month</div>
                <div class="plan-items">
                    <div class="plan-item" data-feature="">-</div>
                    <div class="plan-item" data-feature="Unlimited Administrators">-</div>
                    <div class="plan-item" data-feature="Bandwidth">-</div>
                    <div class="plan-item" data-feature="Unlimited Vehicles">-</div>
                    <div class="plan-item" data-feature="NO Credit card required">-</div>
                    <div class="plan-item" data-feature="Unlimited Drivers">-</div>
                    <div class="plan-item" data-feature="Unlimited Downloads">-</div>
                    <div class="plan-item" data-feature="Other Stuff">-</div>
                </div>
                <!--<div class="plan-footer">
                    <button class="button is-fullwidth">Choose</button>
                </div>-->
            </div>
            <!--
            <div class="pricing-plan is-active">
                <div class="plan-header">Standard</div>
                <div class="plan-price"><span class="plan-price-amount"><span class="plan-price-currency">$</span>50</span>/month</div>
                <div class="plan-items">
                    <div class="plan-item" data-feature="Unlimited Drivers">-</div>
                    <div class="plan-item" data-feature="Unlimited Administrators">-</div>
                    <div class="plan-item" data-feature="Unlimited Logbook storage">-</div>
                    <div class="plan-item" data-feature="Unlimited Vehicles">-</div>
                    <div class="plan-item" data-feature="NO Credit card required">-</div>
                    <div class="plan-item" data-feature="Unlimited Drivers">-</div>
                    <div class="plan-item" data-feature="Unlimited Downloads">-</div>
                    <div class="plan-item" data-feature="Other Stuff">-</div>
                </div>
                <div class="plan-footer">
                <button class="button is-fullwidth">Choose</button>
                </div>
            </div>
            <div class="pricing-plan is-danger">
                <div class="plan-header">Enterprise</div>
                <div class="plan-price"><span class="plan-price-amount"><span class="plan-price-currency">$</span>250</span>/month</div>
                <div class="plan-items">
                    <div class="plan-item" data-feature="Unlimited Drivers">-</div>
                    <div class="plan-item" data-feature="Unlimited Administrators">-</div>
                    <div class="plan-item" data-feature="Unlimited Logbook storage">-</div>
                    <div class="plan-item" data-feature="Unlimited Vehicles">-</div>
                    <div class="plan-item" data-feature="NO Credit card required">-</div>
                    <div class="plan-item" data-feature="Unlimited Drivers">-</div>
                    <div class="plan-item" data-feature="Unlimited Downloads">-</div>
                    <div class="plan-item" data-feature="Other Stuff">-</div>
                </div>
                <div class="plan-footer">
                <button class="button is-fullwidth">Choose</button>
                </div>
            </div>
            -->
        </div>
    </div>
</section>


