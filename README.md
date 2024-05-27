[사이트 바로가기](https://yunyungu.github.io/rovend/)

# 가상 SNS "ROVEND" :gift_heart:

가상의 SNS의 웹 디자인 및 퍼블리싱을 한다는 가정으로 제작한 100% 개인창작 반응형 웹사이트 입니다.

작업 진행중인 프로젝트로, 현제 업데이트 된 페이지는 INDEX 1페이지 입니다.

추가적인 페이지 작업은 추후 업데이트 예정입니다.

<br><br>

<img width="500" alt="데스크톱 이미지" src="https://github.com/yunyungu/rovend/assets/157336396/f93d400e-4d48-40cd-8e5f-767bbd028f29">
<img width="300" alt="모바일 이미지" src="https://github.com/yunyungu/rovend/assets/157336396/54e4de09-84a8-4ebd-9c7f-689aba531d08">

<br><br>

> 이 웹사이트는 반응형 웹사이트의 형대로 작업하였습니다.<br>
> 820px 이하에서는 모바일 모드로, 이상에서는 데스크톱 모드로 보여집니다.

<br>
<img width="300" alt="데스크톱 내비01" src="https://github.com/yunyungu/rovend/assets/157336396/6a091f52-bd33-40a0-bd9d-09af7ce83487">
<img width="300" alt="데스크톱 내비02" src="https://github.com/yunyungu/rovend/assets/157336396/e09245f6-65c7-44ad-ac65-e7bd9b360dce">
<img width="400" alt="모바일 내비" src="https://github.com/yunyungu/rovend/assets/157336396/7c9c1429-4c38-4b5e-9a67-5ffe096eefb5">

<br><br>

> 데스크톱 내비게이션은 좌측 상단 메뉴버튼을 통해 접근할 수 있습니다.
> 데스크톱의 1100px 이상의 와이드스크린부터는 좌측 사이드에 고정된 형태로 나타납니다.<br>
> 모바일 내비게이션은 하단 고정된 내비버튼을 통해 접근할 수 있습니다.
> 이때 메뉴버튼에서의 내비버튼은 보이지 않습니다.

<br><br><br>

---

<h2>STYLE GUIDE / DESIGN CONCEPT</h2>

* Work Flow

<img width="500" alt="work flow" src="https://github.com/yunyungu/rovend/assets/157336396/939f64e6-fff7-42c9-9fde-2fc7154b3393">

<br><br>

* Design Concept

<img width="500" alt="design concept" src="https://github.com/yunyungu/rovend/assets/157336396/86737e6b-390b-4034-83df-d17d0b705b74">

<br><br>

* Style Guide

<img width="500" alt="style guide" src="https://github.com/yunyungu/rovend/assets/157336396/d707e0c0-d128-4ef3-ba50-f4b897bdc007">


<br><br><br>

---

## 사용 툴 소개

* 디자인 및 아이콘, 일러스트
<br><br>
<img width="100" alt="photoshop" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/8425f38b-e2e8-4d3d-b31a-ffcc492fc7c1">
<img width="100" alt="illust" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/5e5af82b-cead-443e-958e-b3d9919fae1f">
<br><br>

* 퍼블리싱
<br><br>
<img width="100" alt="vscode" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/01cacb03-858c-4af4-8b85-3a40782f7256">
<img width="100" alt="html" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/f3e150a5-7e80-4d73-8049-994bdb9968e9">
<img width="100" alt="css" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/3c97d5f4-0a93-412c-bf39-cdbdbe13b55e">
<img width="100" alt="javascript" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/e55a6af9-5f0f-4f1d-95fd-1b2108d2e891">
<img width="100" alt="jquery" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/26701d80-6296-43b5-b526-3836bdae1856">
<br><br><br>

---

## 상세페이지 소개

### :point_right: Plugin

1. Swiper

<img width="300" alt="swiper" src="https://github.com/yunyungu/yunyungu.github.io/assets/157336396/2d3104b9-2a3a-4f90-a2b9-c49f2aff68aa">
<br>
<img width="400" alt="swiper story" src="https://github.com/yunyungu/rovend/assets/157336396/f34a8b69-a652-4cb5-964a-dc9af361a0b1">
<img width="400" alt="swiper feed" src="https://github.com/yunyungu/rovend/assets/157336396/4006ce81-fdc4-4f3e-bccf-4151b1983e3a">

> 상단의 스토리보드 영역과 게시글의 이미지 스와이프는 Swiper plugin을 활용하여 작업하였습니다.<br>
> 각각의 스타일에 어울리는 서로 다른 효과를 적용하였습니다.


<br><br><br>

---

### :point_right: Header 감추기

<img width="400" alt="fullpage" src="https://github.com/yunyungu/rovend/assets/157336396/f94c1852-dc17-4cd5-bfad-ef7ef4880474">

> scroll down하여 header를 감추고, scroll up 하면 다시 보여주는 기능을 사용하였습니다.
> 이는 jQuery 문법을 활용하여 작업하였습니다.

```

var didScroll;
var lastScrollTop = 0;
var delta = 5;
var navbarHeight = $('header').outerHeight();

$(window).scroll(function(event){
    didScroll = true;
});

setInterval(function() {
    if (didScroll) {
        hasScrolled();
        didScroll = false;
    }
}, 300);

function hasScrolled() {
    var st = $(this).scrollTop();
    if($(lastScrollTop - st) <= delta)
        return;
    if (st > lastScrollTop && st > navbarHeight){
        // Scroll Down
        $('#header').addClass('nav-up');
    } else {
        // Scroll Up
        if(st + $(window).height() < $(document).height()) {
            $('#header').removeClass('nav-up');
        }
    }
    lastScrollTop = st;
}

```

<br><br><br>

---

### :point_right: Heart Click event

<img width="400" alt="click heart" src="https://github.com/yunyungu/rovend/assets/157336396/8d07f19b-9b9c-4889-94f6-85e1094b173f">

> 게시글의 하트 버튼을 클릭하면 움직이는 애니메이션 효과를 적용하였습니다.
