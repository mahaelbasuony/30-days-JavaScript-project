# 9- Dev tools tricks

## description


### Learnings
    - styles
        - console.log('%c i am sone great text ', 'font-size:50px; background:red;');
    - warning 
        - console.warn('oh no');
    - erroe
        - console.error('shit');
    - info
        - console.info('information ');
    - testing 
        - console.assert(p.classList.contains('ouch'), 'you did not select the right');
    - clearing 
        - console.clear();
    - view dom elements 
        - console.dir(p);
    - grouping together
        - dogs.forEach(dog => {
            console.group(`${dog.name}`);
            console.log(`this is ${dog.name}`);
            console.log(`${dog.name} is ${dog.age} years old`);
            console.groupEnd(`${dog.name}`);
            });
        - dogs.forEach(dog => {
            //switch groups
            console.groupCollapsed(`${dog.name}`);
            console.log(`this is ${dog.name}`);
            console.log(`${dog.name} is ${dog.age} years old`);
            console.groupEnd(`${dog.name}`);
            });
    - counting
        console.count('wes');
        console.count('steve');
        console.count('wes');
        console.count('steve');
        console.count('steve');
        console.count('wes');
        console.count('steve');

    - timing 
        console.time('fetching data');
        fetch('http://api.github.com/users/webos')
            .then((data => data.json()))
            .then(data => {
                console.timeEnd('fetching data');
                console.log(data);
            });
        
