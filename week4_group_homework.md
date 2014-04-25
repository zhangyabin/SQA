#The CFGs constructed in this way are white-box testing models because product implementation informationis used, as 

follows:

1.Processing nodes typically correspond to assignments, function calls, or procedurecalls.

2.Decision or branching nodes typically correspond to branching statements such asbinary branching in the form of "if

-then-e1se" or "if -then" (empty "else"), ormulti-way branching such as "switch-case". Each outgoing branch will be

markedby its specific condition. For example, for binary branching, it is typically markedby the truth value (T/F, or

TrueRalse) of the associated condition. For multi-waybranching, more specific conditions will be marked.

3.Loop statements correspond to a special type of branching nodes4.The entry and exit nodes are usually easy to identify,

corresponding to the first and laststatement or processing unit in the program code or some corresponding flow-chart.
