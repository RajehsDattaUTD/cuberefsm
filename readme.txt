###use the bin to test

#invoke neos:
./neos_bin/neos -i

example:

(without cube)

neos> refsm ./standard_bench/s27.bench 1

result:
Transition count: 78
Transition states: 7 : 7
Total runtime: 0.0506752 s
Finished normally (time limit not reached)


(with cube)

neos>  cuberefsm ./standard_bench/s27.bench 1

result:
Cube count: 35
Transition states: 7 : 7
Total runtime: 0.0175104 s
Finished normally (time limit not reached)




