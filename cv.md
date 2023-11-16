Sergei Solovev
============

-------------------     ----------------------------
Moscow                        print.string@yandex.ru
Russia                              @j_reserford
                              
-------------------     ----------------------------

Education
---------

2017-2021 
:   **Economics**; The Russian Presidential Academy of National Economy and Public Administration (The Presidential Academy, RANEPA)



Experience
----------

**My Most Recent Work Experience:**

* Worked as HTMLS CSS developer at marketing company



Programming Languages

:   **JavaScript:** Basic JS

:   **sPython:** Skills of data analysis using python

:   

:   Basic knowledge of **Python**, **JavaScript**


Extra Section
----------------------------------------

* Human Languages:

     * Russian (native speaker)
     * English (B1)


* Other sort of impressive-sounding thing you did

Code Examples
----------------------------------------

Hardest task i've ever compelited 

https://www.codewars.com/kata/52742f58faf5485cae000b9a

function formatDuration(seconds) {
  let result = '';
  if (seconds === 0) return 'now'
  
  const year = Math.floor(seconds / (3600 * 24 * 365))
  if (year > 0) {
    result += year === 1 ? '1 year' : `${year} years`;
    seconds %= 3600 * 24 * 365
    if (seconds > 0) {
      result += ', ';
    }
  }
  
  const days = Math.floor(seconds / (3600 * 24))
  if (days > 0) {
    result += days === 1 ? '1 day' : `${days} days`;
    seconds %= 3600 *24
    if (seconds > 0) {
      result += ', ';
    }
  }
  
  const hours = Math.floor(seconds / 3600)
  if (hours > 0) {
    result += hours === 1 ? '1 hour' : `${hours} hours`;
    seconds %= 3600
    if (seconds > 0) {
      result += ', ';
    }
  }
  
  const minutes = Math.floor(seconds / 60)
  if (minutes > 0) {
    result += minutes === 1 ? '1 minute' : `${minutes} minutes`;
    seconds %= 60
    if (seconds > 0) {
      result += ', '
    }
  }
  if (seconds > 0) {
  result += seconds === 1 ? "1 second" : `${seconds} seconds`;
  }
  
  const sumWords = result.split(", ");
  if (sumWords.length > 1) {
    const lastWord = sumWords.pop();
    result = sumWords.join(", ") + " and " + lastWord;
  }
  return result
}

