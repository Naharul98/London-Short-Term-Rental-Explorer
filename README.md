# London-Short-Term-Rental-Explorer

### Running the Project :
- Create an object of the class named 'StartFrame'.

### Features

- Implements [Grounded Extension Algorithm](https://nms.kcl.ac.uk/sanjay.modgil/inf/ProofTheories_and_Algorithms.pdf) to label arguments according to their current position (Winning/Losing/Undecidable)
- Visualizes debates in the form of an interactive directed graph
    - Nodes represent individual arguments in the debate
    - Edges in the graph reflect their attack relation (Which argument is challenging which)
    - Nodes are highlighted according to their labelling by the algorithm (Winning: Green, Losing: Red, Undecidable: Grey)
    - Hover over nodes to view the argument
    - Hover over edges to view the argument structure used
- A range of [Argumentation Schemes](https://www.reasoninglab.com/patterns-of-argument/argumentation-schemes/waltons-argumentation-schemes/) to choose from to allow people engaging in debates to make their arguments more clear and concise.


### Libraries Used
- [Weka](https://sourceforge.net/projects/weka/)
- [OpenCSV](http://opencsv.sourceforge.net)

### AUTHORS 
(C)2018 A K M Naharul Hayat, Fu Zhang, Michael Jones, and Noyan Raquib
