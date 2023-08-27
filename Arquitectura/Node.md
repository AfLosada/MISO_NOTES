`<<type>>` e.x. `<<device>>` or `<<executionEnvironment>>`

![[Pasted image 20230827172427.png]]

The name of the node can also be prefixxed by an indicator (useful when you have various nodes of the same type, but with different responsabilites)

![[Pasted image 20230827172617.png]]

Nodes can be specified as far as needed, this depending on the needs of the diagram.

If your system requires a very specific piece of hardware, then it will probably need to be specified. Else, it could work to just put `<<device>>` General PC.

But nodes are not always hardware, they can be software too (k8s pod?).

Nodes can also have communication paths, as they might need to communicate between themselves.

![[Pasted image 20230827172707.png]]

There can also be connections between the artifacts of different nodes.

![[Pasted image 20230827172804.png]]


