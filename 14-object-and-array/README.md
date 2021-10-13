# Array and Object reference vs copy

## description


### Learnings
-  const team = players; any change in team will effect on players
        
    ## solution

- team2 = players.slice();  
- team3 = [].concat(players);  
- team4 = [...players];
- team5 = Array.from(players);

- in object 

 - cap2 = Object.assign([], person, {number: 99}); copy and add extra data 
 - cap3 = {...person};
 - dev = Object.assign({}, wes);
 - dev2 = JSON.parse(JSON.stringify(wes));


