# Profiling

## Profilers used:
* [cprofile][1]
* [line_profiler][2]

I also used [timeit][3] to manually time some sections of code which were not in any function

## Resources for cprofile:
* [The basics][4]
* [cprofile + visualisation tools][5]

## Resources for line_profiler
* [The basics][6]

you just have to add @Profile above any function you want to profile line by line without importing Profile 
and run 

```kernprof -l script_to_profile.py```

## Differences between the two
I believe that cprofile is more standard and has easy visual support also, but if you want to see what happens [line by line][7] in code
then line_profiler is comes into picture.


[1]:https://docs.python.org/3/library/profile.html#module-cProfile
[2]:https://github.com/rkern/line_profiler
[3]:https://docs.python.org/3/library/timeit.html
[4]:https://www.machinelearningplus.com/python/cprofile-how-to-profile-your-python-code/
[5]:https://medium.com/@narenandu/profiling-and-visualization-tools-in-python-89a46f578989
[6]:https://coderzcolumn.com/tutorials/python/line-profiler-line-by-line-profiling-of-python-code
[7]:https://stackoverflow.com/questions/3927628/how-can-i-profile-python-code-line-by-line
