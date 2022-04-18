# Landrover

## Slick slider
```html
<div class="your-class">
  <div>your content</div>
  <div>your content</div>
  <div>your content</div>
</div>
```

```css
<link rel="stylesheet" type="text/css" href="slick/slick.css"/>
// Add the new slick-theme.css if you want the default styling
<link rel="stylesheet" type="text/css" href="slick/slick-theme.css"/>
```

```javascript
<script type="text/javascript" src="//code.jquery.com/jquery-1.11.0.min.js"></script>
<script type="text/javascript" src="//code.jquery.com/jquery-migrate-1.2.1.min.js"></script>
<script type="text/javascript" src="slick/slick.min.js"></script>
```


##bxslider
```html
<div class="bxslider">
  <div><img src="/assets/images/coffee1.jpg" title="Funky roots"></div>
  <div><img src="/assets/images/coffee2.jpg" title="The long and winding road"></div>
  <div><img src="/assets/images/coffee3.jpg" title="Happy trees"></div>
</div>
```

```javascript
$(function(){
  $('.bxslider').bxSlider({
    mode: 'fade',
    captions: true,
    slideWidth: 600
  });
});
```


## Scroll Animation

- 기본적으로 <head> 태그 안에 aos.js와 aos.css 라이브러리 파일을 불러옵니다.

- jQuery 라이브러리도 필요합니다.

- aos.js, jQuery.js는 CDN으로 불러오겠습니다.

```html
<head> <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css"> <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script> </head>
```
  
```script
<script> AOS.init(); /* 주석부분과 같이 AOS API - Global Setting 가능 AOS.init({ offset: 120, delay: 0, duration: 400, easing: 'ease', once: false, mirror: false, anchorPlacement: 'top-bottom' }); */ </script>
```
