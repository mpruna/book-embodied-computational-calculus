Disruption and defragmentation; access-aware defragmentation
============================================================

  -------------- ----------------------
  **Created:**   *10/9/2019 11:09 AM*
  **Updated:**   *10/9/2019 9:04 PM*
  -------------- ----------------------

\

Disruption and defragmentation;

\

Defragmentation (consolidation, solidification) must be aware of the:

-   access pattern distribution (Poisson) 

-   of the assumption on the connectivity of the nodes, (Erdos
    accessibility, random walk, ratio, RTT/TTL)

-   on the (**pre**/post;
    **ante**/post)-**fetching**/**caching**/**buffering**/**spooling**
    assumptions,

-   and of the **\|K**-cost profiles of each likely-operation.

\

The ordered-materialization of data, the materialized-views of data
through function and physical disposition of such data must be
\<defragmented\> with respect to the observed and anticipated
query/retrieval/reading patterns, throughout the layers of durable cache
and/or throughout the several nodes of communication.

 
