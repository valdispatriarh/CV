#Junior Frontend Developer
##Uladzislau Isachkou
###My Contact
*+48606166835
*Valdis#9609 (discord)
###Skills
*CSS 
*HTML 
*Git/GitHub 
*JS
###Cod Examples
```function showTime() {
    const time = document.querySelector('.time');
    time.textContent = new Date().toLocaleTimeString();
    setTimeout(showTime, 1000);
    showDate();
    showGreeting();
  }
  showTime();
 ///////////////////////////////////////////////////////////////////////////////////
  function showDate() {
    const date = document.querySelector('.date');
    const options = { weekday: 'long', month: 'long', day: 'numeric', };
    date.textContent = new Date().toLocaleDateString('en-US', options);
  };
  ////////////////////////////////////////////////////////////////////////////////
  function showGreeting() {
    const greeting = document.querySelector('.greeting');
    greeting.textContent = `Good ${sh()}`;
  function sh() {
    const date= new Date().getHours();
    if (date >= 0 && date <= 5 ) {return ('Night,');} 
      if (date >= 6 && date <= 11 ) {return ('Morning,');}     
        if (date >= 12 && date <= 17 ) {return ('Day,');} 
          if (date >= 16 && date <= 23 ) {return ('Evening,');} ;
}
    }```
###Education
*Belarusian National Technical University(engineer)
*RS School JS/FE Pre-School 
###Languages
*Belarusian native language
*English (A1)
*Polish (A1)
