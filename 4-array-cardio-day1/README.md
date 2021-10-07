# Array cardio day 1

## description


### Learnings

- learned how to 
    - use filtter 
        - inventors.filter(inventor => inventor.year >= 1500 && inventor.year < 1600);
    - console.table()
    - use map and variables in `` 
        - inventors.map(inventor => `${inventor.first}  ${inventor.last}`);
    - use sort 
        - inventors.sort((a, b) => a.year > b.year ? 1 : -1)
    - use Reduce 
        - data.reduce(function(obj, item) {
            obj[item]++;
            return obj;
        }, {});