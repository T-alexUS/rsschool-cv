# Alex Taitski


## Contacts
* __Location:__ Minsk, Belarus
* __Telegram:__ T_alexUS
* __Email:__ ataitski@mail.ru
* __GitHub:__ T-alexUS


## About Me
I’m a poor student interested in BI-systems specialization. 
Outgoing, helpful, hard-working — is all about me. I’m eager to learn JS to improve my hard skills and enter a new branch of IT.


## Skills
* HTML
* CSS
* JS
* Python (ETL and data analysis)
* Qlik, Power BI
* Git


## Code example
```
var uniqueInOrder = function(iterable) {    
    let splitedString;    

    if (typeof(iterable) == 'string' && iterable.length != 0) {        
        splitedString = iterable.split('');    
        }    
    else if (iterable.length == 0) {        
        return [];    
    }    
    else {        
        splitedString = iterable;    
    }    

    let originalArray = [];    
    originalArray.push(splitedString[0])  

    for (let i = 1; i < splitedString.length; i++) {        
        if (splitedString[i] == splitedString[i - 1]) {            
            continue;       
        }        
        else {            
            originalArray.push(splitedString[i]);        
        }    
    }        

    return originalArray;
}
```

## Education
* University: BSU, Economic Department, Business Informatics (2020-2024)


## Langusges
* English - B2
* Russian - Native