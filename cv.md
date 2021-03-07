# **Victor Lobanov**

## Contacts:

+ mobile-phone: +88005553535
+ email: victor.lobanovrul@gmail.com
+ vk: https://vk.com/vityarka

## About:
+ 19 years old
+ Junior frontend developer
+ Want to become a senior developer!
+ Very communicative, energetic, cheerful
+ No commercial expirience, but ready for learning and improving!

## Skills:
+ JavaScript (JQuery, ES6, React)
+ CSS3 (Bootstrap, SASS)
+ HTML5
+ Git 

## Code examples:
```
$(document).ready(function(){
  //Loading function...
  let i = 1
  const sliderDelay = 200
  const imageCount = 3
  const aboutInfo = ['SomeInfo']

  function renderSlider(){
    $('.slider-image img').fadeOut(sliderDelay).fadeIn(sliderDelay)
    setTimeout(() => $('.slider-image img').prop('src', './news-images/' + i + '.jpg'), sliderDelay)

    $('.slider-text p').fadeOut(sliderDelay).fadeIn(sliderDelay)
    setTimeout(() => $('.slider-text p').text(aboutInfo[i - 1]), sliderDelay)

  }

  $('.left-btn').on('click', () => {
    --i
    if (i < 1) i = imageCount
    renderSlider()
  })

  $('.right-btn').on('click', () => {
    ++i
    if (i > imageCount) i = 1
    renderSlider()
  })

  renderSlider()

})
```

## Experience:

> No commercial expirience, but have some my projects:

+ http://vityarka.ru/
+ http://vityarka.ru/krayt/index.html
+ http://vityarka.ru/kina/kina-main.html
+ http://vityarka.ru/blitz-task/blitz-task.html

> Cources:

+ RS School
+ Vladilen Minin youtube cources


## Education

+ Partially completed higher education

## English

> Intermediate
