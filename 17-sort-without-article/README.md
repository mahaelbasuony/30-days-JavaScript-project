# sort without articles

## description


### Learnings
- bandName.replace(/^(a |the |an)/i, "").trim()  => trim
- bands.sort((a, b) => strip(a) > strip(b) ? 1 : -1  => sort 
