Panda 1

1.  var portrait-pic = document.querySelector('.highlight > img');
portraitPic.src = 'https://cnet2.cbsistatic.com/img/PgybSJ1LaH5YXM66n1dP8APaph8=/fit-in/970x0/2016/12/02/aead5046-63ba-404b-8263-891851674ac1/pandaironman.jpg'

1.  var leftImage = document.querySelector('#left-image > img');
leftImage.src = 'https://cnet2.cbsistatic.com/img/PgybSJ1LaH5YXM66n1dP8APaph8=/fit-in/970x0/2016/12/02/aead5046-63ba-404b-8263-891851674ac1/pandaironman.jpg'

2.  var PandaTheBear = document.querySelector('h1');
PandaTheBear.textContent
PandaTheBear.textContent = 'Captain CoolPants'

3.  document.querySelector('#employment .info-title').innerText = 'Funemployment'

4.  body = document.querySelector('body');
    body.style.color = 'hotpink';

5.   document.querySelectorAll('.highlight').forEach(function(highlight){highlight.style.color = 'orange'});

6.  var h1er = document.querySelector('h1');
    h1er.style.fontFamily = 'monospace';

7.  var actionIcon = document.querySelectorAll('.action-icon-bg')
    actionIcon.forEach(function(circle){
    circle.style.backGroundColor = 'hotpink'});

8.  var namer = document.querySelector('#name');
    namer.placeholder = 'Identify Yourself!!'

9.  var messager = document.querySelector('#message');
    message.placeholder = 'State your purpose for disturbing me...';

10. namer.value = 'your nemesis';

11. var emailer = document.querySelector('#email');
    emailer.value = 'koalathebear@gmail.com';

12. var submitter = document.querySelector('#submit');
    submitter.value = 'En Garde!';

13.   submitter.disabled = true;

14. var 今天 = document.querySelector('.bio-info');
    今天.hidden = true;



Panda 2

1.  var timeTraveller = document.querySelector('.bar-default:nth-child(3n)');
    timeTraveller.remove()

1.  var pikaPic = document.querySelector('#right-image > img');
    var pipika = pikaPic.cloneNode(true);
    var portfolioer = document.querySelector('.portfolio-container');
    portfolioer.appendChild(pipika);

2.  for(var i = 0; i < 10; i++) { portfolioer.appendChild(pikaPic.cloneNode(true)); }

3.  var listItem = document.createElement('li');
    var leftSpan = document.createElement('span');
    var lastUpdated = document.createTextNode('Page last updated on');
    leftSpan.appendChild(lastUpdated);
    listItem.appendChild(leftSpan);
    

    var rightSpan = document.createElement('span');
    var newDate = new Date();
    var dateText = document.createTextNode(newDate);
    rightSpan.appendChild(dateText);
    listItem.appendChild(rightSpan);
