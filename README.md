# Markov Model  
Markov model is a system that produces Markov chain. Hidden Markov model is a markov model that we don't know its rules to produce markov chains.  
2 probabilities,  
* there will be certain observation, given certain state and time  
* there will be certain transition, given certain state and time  

## 1 Markov Chain  
![avatar](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Markovkate_01.svg/220px-Markovkate_01.svg.png)
## 1.0 Markov Property
Markov property refers to a memoryless stochastic process{X(t),t ∈T}, 
that future states only depend on current states, not on the states preceded it. 
It is usually be formualted in conditional probalibity form as 
P{Xn=xn|X<sub>0</sub>=x<sub>0</sub>, X<sub>1</sub>=x<sub>1</sub>, X<sub>2</sub>
=x<sub>2</sub>, ... , X<sub>n-1</sub> = x<sub>n-1</sub>} = P{X<sub>n</sub>=x<sub>n</sub>
|X<sub>n-1</sub> = x<sub>n-1</sub>};

### 1.1 Conclusion1 
Given process with independent increments {X(t),t≥0}, and X(0) = 0,  
then {X(t),t≥0} is Markov process.
### 1.2 Conclusion2  
Poisson process is time-continuous and state-discrete markov process;  
Wiener process is time and state continuous markov process;  
Poisson and Wiener is special cases of independent incremental process;

### 1.3 Definition of Markov chain  
Both time and state discrete process is called Markov chain, which could be marked with  
{X<sub>n</sub> = X(n), n=0,1,2...},  
its time set is  
T<sub>1</sub>={0,1,2...};  
its state set is  
I={a1,a2,...};  
Markov property of Markov chain is usually in conditional probability marked as  
P<sub>ij</sub>(m,m+n) = P{X<sub>m+n</sub>=a<sub>j</sub>|X<sub>m</sub>=a<sub>i</sub>}  
, it shows transition probability from current time m and current state a<sub>i</sub> to a<sub>j</sub> at time (m+n), Where a<sub>i</sub> ∈I;  
### 1.4 Markov transition probability matrix  
[ Pij ], i,j∈[1,N] and i≤j;  
* sum of each matrix row is 1.0;   
* sum of each matrix column is usually not 1.0, Eg. column 1 it means transition from state i at time i to state 1 at time i ∈[1,N];  
![avatar](https://upload.wikimedia.org/wikipedia/en/thumb/3/35/Beanandteddy.jpg/220px-Beanandteddy.jpg)  
## 2 Hidden Markov chain  

