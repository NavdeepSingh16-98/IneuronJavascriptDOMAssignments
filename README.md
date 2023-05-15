# Questions 1

![](./assets/q1.PNG)

>document.querySelectorAll(' div#sidebar-wrapper-left div.crayons-card  h2')[0].innerHTML = "Navdeep";

>document.querySelectorAll(' div#sidebar-wrapper-left div.crayons-card  p')[0].innerHTML = "I am a frontend developer";

# Question 2

![](./assets/q2.PNG)

>let arr = [];

> arr = document.querySelectorAll('div.as-imagegrid-wrapper div.as-imagegrid-item span ');


> let newarr = [];

> arr.forEach((span)=>{
    newarr.push(span.innerHTML)});


# Question 3

![](./assets/q3.PNG)

> let newNode = document.querySelector(".accordion-homepage").firstChild;

> let clonedNode = newNode.cloneNode(true);

> clonedNode.firstChild.innerText = 'My New FAQ';

> document.querySelector(".accordion-homepage").appendChild(clonedNode);

# Question 4

![](./assets/q4.PNG)

> document.querySelector(".contactUs--content").firstChild.childNodes[0].querySelector('.item--subtitle').innerText="6366256689"

# Question 5

![](./assets/q5.PNG)

> document.querySelector('.rpannel').firstChild.querySelector('.button-collection .buynow a').innerText= "Check out"


# Question 6

![](./assets/q6.PNG)

> document.querySelector('._auxiliary_menu_558sn_31').firstChild.querySelector('input').onmouseover = function(){ this.style.backgroundColor ='red';}

# Question 7

![](./assets/q7.PNG)

> document.forms['hp-search-form'].elements['hp-search-input'].value = 'CSS Selectors'

> document.forms['hp-search-form'].submit()


# Question 8

![](./assets/q8.PNG)

> let mainDiv = document.querySelector('#SIvCob')

> let aNodes = document.querySelectorAll('#SIvCob a');

> for(let i=0; i<aNodes.length; i=i+2){    mainDiv.removeChild(aNodes[i]);}

# Question 9

![](./assets/q9.PNG)

> let h1 = document.querySelector('.header_viewport-80 h1')

> h1.style.fontFamily = 'monospace'

> h1.style.color = '#ff4d4d'

# Question 10

![](./assets/q10.PNG)

> let text = document.querySelector('.btn-cta-big span.login-btn-text')

> text.onmouseover = function(){ this.style.backgroundColor ='red';}


# Question 11

![](./assets/q11.PNG)

> let logo = document.querySelector('.icon-logo');

> logo.style.backgroundImage = 'url(https://ineuron.ai/images/ineuron-logo.png)'

# Question 12

![](./assets/q12.PNG)

> let button = document.querySelector('h2 a.btn')

> button.style.backgroundColor='blue'

# Question 13

![](./assets/q13.PNG)

> document.querySelector('.home22-intro-text p').innerText = 'JSBOOTCAMP'

# Question 14

![](./assets/q14.PNG)

> document.querySelector('.HotDealsAll__Heading__2fIbe').style.fontSize = '80px'

# Question 15

![](./assets/q15.PNG)

> let require10 = document.querySelectorAll('h3.ps-title')[4]

> require10.style.textAlign = 'right'

# Question 16

![](./assets/q16.PNG)

> document.querySelector('.section-title_title__VEDfK span').innerText = 'Start With Scratch'

# Question 17

![](./assets/q17.PNG)

> document.querySelector('.btn-container a').innerText = new Date()


# Question 18

![](./assets/q18.PNG)

> document.querySelector('section.p-f03v2__footer').style.backgroundColor = 'orange'


# Question 19

![](./assets/q19.PNG)

>document.querySelector('a.navbar-brand img').src


# Question 20

![](./assets/q20.PNG)

> let curretDiv = document.querySelectorAll('.pdl-text-content')[4]

> curretDiv.querySelector('p.pdl-text-description').style.color = 'orange'