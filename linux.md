### parallel
```bash
seq 100 | parallel -j 10 'sleep $(($RANDOM % 3)); echo'
```
