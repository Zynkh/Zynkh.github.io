---
layout: page
title: Contact
permalink: /contact/
---

<p style="text-align:justify;">
Feel free to connect with me. Here I have links to both my LinkedIn and Github profiles, and because they were lonely by themselves I added a few bubbles that'll take you to awesome, inspiring, or odd places, respectively. 
</p>

<center>
    <ul class="list-inline">
        <li>
            <a href="https://github.com/Zynkh" target="blank" class="btn-social btn-outline"><i class="fa fa-fw fa-github-square"></i></a>
        </li>
        <li>
            <a href="https://www.youtube.com/watch?v=StTqXEQ2l-Y" target="blank" class="btn-social btn-outline"><i class="fa fa-fw fa-smile-o"></i></a>
        </li>
        <li>
            <a href="https://www.youtube.com/watch?v=m6ugFcwsgpE" target="blank" class="btn-social btn-outline"><i class="fa fa-fw fa-rocket"></i></a>
        </li>
        <li>
            <a href="https://www.youtube.com/watch?v=iRZ2Sh5-XuM" target="blank" class="btn-social btn-outline"><i class="fa fa-fw fa-question"></i></a>
        </li>
        <li>
            <a href="http://www.linkedin.com/in/mzhill/" target="blank" class="btn-social btn-outline"><i class="fa fa-fw fa-linkedin"></i></a>
        </li>
    </ul>

    <ul class="list-inline">
        <span class="addy-magic">
            <li class="poof1">
                <p class="btn-long btn-outline">Reveal my email address</p>
            </li>
            <li class="poof2">
                <p class="btn-long" style="margin-top:15px; cursor:auto"><span class="poof3"></span></p>
            </li>
        </span>
    </ul>
    
<div><p class="poof"></p></div>

</center>

<script>
    $(document).ready(function() {

        var reveal = function(){
            $('.poof1').fadeOut(300);
            $('.poof3').text("m.zach.hill@gmail.com")
            $('.poof2').delay(300).fadeIn(300);
        };

        $('.addy-magic').on( "click", reveal );

    });
</script>
