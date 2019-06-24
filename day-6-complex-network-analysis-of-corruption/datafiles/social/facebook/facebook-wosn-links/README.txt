Facebook friendships network, part of the Koblenz Network Collection
===========================================================================

This directory contains the TSV and related files of the facebook-wosn-links network:

This undirected network contains friendship data of facebook users. A node represents a user and an edge represents a friendship between two users.


More information about the network is provided here: 
http://konect.uni-koblenz.de/networks/facebook-wosn-links

Files: 
    meta.facebook-wosn-links -- Metadata about the network 
    out.facebook-wosn-links -- The adjacency matrix of the network in space separated values format, with one edge per line
      The meaning of the columns in out.facebook-wosn-links are: 
        First column: ID of from node 
        Second column: ID of to node
        Fourth column: timestamp of the edge


Complete documentation about the file format can be found in the KONECT
handbook, in the section File Formats, available at:

http://konect.uni-koblenz.de/publications

All files are licensed under a Creative Commons Attribution-ShareAlike 2.0 Germany License.
For more information concerning license visit http://konect.uni-koblenz.de/license.



Use the following References for citation:

@MISC{konect:2016:facebook-wosn-links,
    title = {Facebook friendships network dataset -- {KONECT}},
    month = sep,
    year = {2016},
    url = {http://konect.uni-koblenz.de/networks/facebook-wosn-links}
}

@inproceedings{viswanath09,
        author = {Viswanath, Bimal and Mislove, Alan and Cha, Meeyoung
                  and Gummadi, Krishna P.},
        title = {On the Evolution of User Interaction in {Facebook}},
        booktitle = {Proc. Workshop on Online Social Networks},
        year = {2009},
        pages = {37--42},
 }


@inproceedings{konect,
	title = {{KONECT} -- {The} {Koblenz} {Network} {Collection}},
	author = {Jérôme Kunegis},
	year = {2013},
	booktitle = {Proc. Int. Conf. on World Wide Web Companion},
	pages = {1343--1350},
	url = {http://userpages.uni-koblenz.de/~kunegis/paper/kunegis-koblenz-network-collection.pdf}, 
	url_presentation = {http://userpages.uni-koblenz.de/~kunegis/paper/kunegis-koblenz-network-collection.presentation.pdf},
}


