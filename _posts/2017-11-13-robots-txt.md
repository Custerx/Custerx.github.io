---
title:  "Robots.txt"
date:   2017-11-13
layout: post
comments: true
---
<div class="section post-content--{{ page.date | date: '%Y-%m-%d' }}">
    <div class="main">
        <div class="card">
        <h1>{{ page.title }}</h1>
            <div class="columnProdPic">
                <div class="card">
                    <img src="/img/lego/2017-11-13-robots-txt/robots_txt.gif" alt="blogg pic">
                    <div class="container">
                        <p class="post-date">{{ page.date | date: '%Y-%m-%d' }}</p>
                        <p><b>Robots.txt</b></p>
                        <p>Webbplatsägare använder filen /robots.txt för att ge instruktioner om sin webbplats till webbrobotar. Det har en engelsk term kallad "The Robots Exclusion Protocol".</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="main">
        <div class="columnProdInfo">
            <div class="container">
                <h2>Information</h2>
                <div class="prodLine">
                    <p>Kortfattat kan man säga att en robot som vill besöka en webbsida måste först kontrollera om där finns en robots.txt fil. Denna fil kan dock ignoreras av robotar, speciellt skadliga robotar som letar efter känslig information. Vem som helst kan även se robots.txt filen så man leder personer till det material man vill gömma - med andra ord skall robots.txt inte användas för att gömma information.</p>
                    <p>Jag använde mig av följande konfigurationer. Först skapades robots.txt filen och placerades i startmappen tillsammans med index.htm. Jag valde alternativet att ge samtliga robotar fullständig access, då jag inte har någon känslig information på mina sidor. <br>Detta gjorde enligt följande: <br>User-agent: *<br>Disallow:</p>
                </div>
            </div>
        </div>
    </div>
</div>