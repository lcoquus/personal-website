# Chapter 2: Kirchoff's Laws and Circuit Analysis

## The Anatomy of a Circuit

Chapter 1 introduced us to the electric circuit, the basis of much of the study of electricity in one form or another. We created a simple circuit which contained the essential components: a source, a path, a load, and a ground. This allowed us to analyse the voltage, current, resistance, and power in the circuit. However, most circuits are more complicated than that. They might contain multiple sources, multiple paths, and multiple loads (in certain circumstances there can also be multiple grounds). We thus need to understand the general structure of a circuit, so that we can analyse these more advanced constructions.

There are two features which we will use to describe the anatomy of a circuit. The first is a *node*. A node can be thought of as a junction, a point of connection between the components in a circuit. The defining feature of a node is that *the voltage across a node is constant*. Our circuit from chapter 1 has two nodes: the top path, and the ground. Figure X shows a circuit with several nodes, all circled in red. Take some time to study this circuit and convince yourself that the voltage across each node is constant.

The second feature is a *mesh*. A mesh can be thought of as an unbroken loop inside a circuit. The defining feature of a mesh is that *the current around a mesh is constant*. Our circuit from chapter one has a single mesh, being the only looping path of current in the circuit. Figure X shows a circuit with several nodes; they are annotated with a circular arrow. Take some time to study this circuit and convince yourself that the current around each mesh is constant.

## KCL and KVL

We now know that circuits are made up of components, and that these components are connected in nodes and meshes. But how can we use this knowledge to analyse our circuit? For that, we need to introduce two more laws, both named after German scientist Gustav Kirchoff. These two laws have intuitive explanations which will help us to apply them in the next section.

*Kirchoff's Current Law* (KCL) states that the sum of the currents entering a node is equal to the sum of the currents leaving that node. *Kirchoff's Voltage Law* (KVL) states that the sum of voltage rises in a mesh is equal to the sum of voltage drops in that mesh. Note that a voltage "rise" refers to the behaviour of a source, while a voltage "drop" refers to a load. These laws result from the conservation of power and energy. Current flowing into a node, multiplied by the voltage of that node, equals the power flowing into that node. This power must go somewhere, and the only place it can go is out of the node. The power cannot simply disappear, so therefore the power flowing out of the node, divided by the voltage of the load, equals the current flowing out of the load. Since the voltage of the node remains constant, the sum of the currents entering the node must equal the sum of the currents leaving the node.

A similar logic applies to KVL. The sources in the mesh supply power, which corresponds to a voltage rise. This power must go somewhere, and the only place it can go is into the loads present in the mesh. Since the current around a mesh is constant, the sum of the voltage drops at each load must equal the sum of the voltage rises from each source. Look again at the circuits in Figures X and X. Try to visualise the currents flowing in and out of each node, and the voltages rising and falling around each mesh. The water analogy introduced in chapter 1 might help.

## Nodal and Mesh Analysis

## In Real Life: A Volume Control Knob

## Mathematics Corner: Derivations of KCL and KVL

## What We've Learnt