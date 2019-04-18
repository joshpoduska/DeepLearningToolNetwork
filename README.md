# DeepLearningToolNetwork
A brief study of popular open source deep learning tools.

You can find supporting documents (Word doc with detailed notes and Gephi formatted csv file) saved in this project.

This network graph has three types of nodes. Deep learning tools are the focus of this investigation and are colored blue. The code bases used to write those tools are colored pink. The APIs that data scientists leverage when using those tools are in green. 

code base (pink) → deep learning tool (blue) → API (green)

The edges are colored the same as their source node. All pink edges have the same default width. Blue edge widths correspond to GitHub stars for the deep learning tool form which the edge originates. The size of every node and the font size of its label correspond to node degree (the number of connections to that node).

The deep learning ecosystem is complex and digging through documentation was no easy task. Please reach out to me at josh@dominodatalab.com if you spot anything I missed. 

![img](/DLToolsNetwork.png)
