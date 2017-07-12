#owl-carousel-arrows
-------

[1]: <https://github.com/miscel/owl-carousel-arrows>

Overview
Usage of Owl-Carousel-Arrow. 

I used loop:true and margin:10. The structure works with any kind of DOM element. 
In all of my examples i used <div class="item">...</div> but you could put any other element div/span/a/img..


Setup

Using JS function in the public/js/main.js file.

$('.owl-carousel').owlCarousel({
    loop:true,
    margin:10,
    nav:true,
    responsive:{
        0:{
            items:1
        },
        600:{
            items:3
        },
        1000:{
            items:5
        }
    }
})

html

<div class="owl-carousel owl-theme">
    <div class="item"><h4>1</h4></div>
    <div class="item"><h4>2</h4></div>
    <div class="item"><h4>3</h4></div>
    <div class="item"><h4>4</h4></div>
    <div class="item"><h4>5</h4></div>
    <div class="item"><h4>6</h4></div>
    <div class="item"><h4>7</h4></div>
    <div class="item"><h4>8</h4></div>
    <div class="item"><h4>9</h4></div>
    <div class="item"><h4>10</h4></div>
    <div class="item"><h4>11</h4></div>
    <div class="item"><h4>12</h4></div>
</div>




#### License

Copyright (c) 2017 Selenium Yazılım ve Danışmanlık LTD. ŞTİ.

Licensed under the MIT license.
