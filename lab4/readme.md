# CS5340: Monte Carlo Inference Assignment

In `part1/main.py` and `part2/main.py`, you will implement Importance sampling and Gibbs sampling respectively. There 
are 5 cases part1 and 4 cases for part2.

To execute your scripts, you may run:
```
cd [ROOT]/part1
python main.py --case <CASE-NUM>  # e.g. python main.py --case 1

cd [ROOT]/part2
python main.py --case <CASE-NUM>  # e.g. python main.py --case 1
```

This will save your results into `part1/data/predictions` and `part2/data/predictions` respectively. You may compare 
your answers with mine using `check_answers.py` e.g.
```
cd [ROOT]/part1
python check_answers.py --case <CASE-NUM>  # e.g. python main.py --case 1

cd [ROOT]/part2
python check_answers.py --case <CASE-NUM>  # e.g. python main.py --case 1
```
We will use a tolerance of up to 1 decimal place.
