---
title: AAACT - Intake form
description: This intake form is to determine what service you require from AAACT.
subject:
  - howTos
tags:
  - testYourProducts
audience:
  - Everyone
---
# AAACT Intake Forms

<div class="wb-fieldflow">
    <p>What do you want to do?</p>
    <ul>
        <li>Go out
            <!-- set of choices 1 -->
            <div class="wb-fieldflow-sub">
                <p>To do what?</p>>
                <ul>
                    <!-- set of choices 1.1 -->
                    <li>Eat
                        <div class="wb-fieldflow-sub">
                            <p>Where?</p>
                            <ul>
                                <!-- choices 1.1.1 and 1.1.2 -->
                                <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#cafe","container":"#ajaxContainer","type": "replace"}'>Café</li>
                                <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#restaurant","container":"#ajaxContainer", "type": "replace"}'>Restaurant</li>
                            <ul>
                        </div>
                    </li>
                    <!-- choice 1.2 -->
                    <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#shopping","container":"#ajaxContainer","type": "replace"}'>Shopping</li>
                    <!-- set of choices 1.3 -->
                    <li>Activity
                        <div class="wb-fieldflow-sub">
                            <p>What kind of activity?</p>
                            <ul>
                                <!-- set of choices 1.3.1 -->
                                <li>Sports
                                    <div class="wb-fieldflow-sub">
                                    <p>What type of sports?</p>
                                        <ul>
                                            <!-- choices 1.3.1.1, 1.3.1.2 and 1.3.1.3-->
                                            <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#gym","container":"#ajaxContainer","type": "replace"}'>Gym</li>
                                            <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#bicycle","container":"#ajaxContainer", "type": "replace"}'>Bicycle</li>
                                            <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#swimming","container":"#ajaxContainer", "type": "replace"}'>Swimming</li>
                                        <ul>
                                    </div>
                                </li>
                                <!-- choices 1.3.2 -->
                                <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#picnic","container":"#ajaxContainer", "type": "replace"}'>Picnic</li>
                            </ul>
                        </div>
                    </li>
                </ul>
            </div>
        </li>
        <li>Stay home
        <!-- set of choices 2 -->
            <div class="wb-fieldflow-sub">
                <p>To do what?</p>>
                <ul>
                    <!-- set of choices 2.1 -->
                    <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#read","container":"#ajaxContainer", "type": "replace"}'>Read</li>
                    <li>TV
                        <div class="wb-fieldflow-sub">
                            <p>What do you want to watch?</p>
                            <ul>
                                <!-- choices 2.2.1 and 2.2.2-->
                                <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#movie","container":"#ajaxContainer", "type": "replace"}'>Movie</li>
                                <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#serie","container":"#ajaxContainer", "type": "replace"}'>Serie</li>
                            <ul>
                        </div>
                    </li>
                </ul>
            </div>
        </li>
        <li data-wb-fieldflow='{"action": "ajax", "url": "{{ rootPath }}intake-form/index.html#nothing","container":"#ajaxContainer", "type": "replace"}'>Nothing</li>
    </ul>
</div>

<section id= "ajaxContainer">
</section>