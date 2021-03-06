10 requirements for automating R&D
==================================

  -------------- ----------------------
  **Created:**   *11/12/2019 3:38 PM*
  **Updated:**   *11/12/2019 3:43 PM*
  **Author:**    *Bogdan Bocse*
  -------------- ----------------------

\

\

Referential integrity between systems. Identifiers:

Consistently encoded throughout layered encoding abstractions;

each layer of encoding and abstraction, respectively, usually adds its
own:

addressable resources (mutable/immutable \*states\*, and \#functions\#),

!actions/verbs/intentions!

enumerations/sets, (immutable labeled, ordered, sets)

Preconditions:

1.  registration DNF,

2.  cryptographic

3.  DNF authentication

4.  DFN, authorization

5.  DFN,

6.  rate limiting/capping/billing DFN\*\*, 

7.  \*\*DNF - Discovery, Negotiation and Fulfilment

relationships

the semantic of applying each action to a \*state\* may be
generalized/abstracted, but the semantic of defining the link between
resource-functions (\#lambdas\#) and !verbs! is sentient-defined, at
least as far as Scheduling-Routing-Allocation is concerned), . It is
usually the adding of new relationship-types between nodes that forces
the escapers, separators, interruptors, initiators, terminators to
bubble-up/cluster-up into a higher-level of abstraction.

Persistent with Known-Expected Durability, Eventually Replicated with
periodic cross-verification between replicas (layered reconciliation,
bottom up)

Retrievable by authorized systems and by users authorized on those
systems (the user is a second-class citizen)

Consideration from preserving order:

1.  Total orders must be preserved.

2.  Eventual orders must be indicated, together with the expected
    windows for reconciliation/mediation/merging/reducing events (known
    as \"time until CFOs\" signature; last known state of planned human
    intervention for validation;)

3.  Partial orders must be specified, together with the computable
    function and the addressable state which the partition (or the
    partition set, partition list, partition tree, depend on)

Referential integrity throughout the data lifecycle: between service
requests, service responses and service logs.

Semantic request of entities, attributes, relationships and collections

Instant data life-cycle visibility throughout the system

1.  Replayeable version history, signed with \"vector clock chain\" and
    physical precision/drift clock (last synced with NTP-Zurich,
    NTP-London and NTP-Instanbul, trusted authoritative clock, with
    expected offset probability distribution ( probability per 1ms,
    probability per 2ms, probability per 3ms; expected drift is computed
    based on hardware specifications )

2.  Known accessibility (i.e. ) and durability degradation PDFs
    (probability distribution functions)

3.  (\...)

Secret Management

Configuration Management

Neo4j Cloud/CosmoDB (MS)/ Cloud

MergeSort Chain signature (the list of left/right/split decisions made
by the algorithm, hased) when several partially ordered streams are
merged together. The chain signature represents a way to track, a
posteriori, if some consenting actor other than yourself from that chain
has been processed \"in front of you\" or \"behind of you\". You can
think of this as a partially recomposable queue.

Binarizable DTOs and layered-semantic compression and encoding
(Multi-Layered Huffman encoding):

1.  Are RDF and SPARQL binarizable? 

2.  Are the labels in the binarization compressebable with a fixed-sized
    dictionary, "warmed-up" with test data/slightly-older data? Semantic
    tree and semantic graph compression with layered dictionaries\>

\

\

\

\-\-\-\-\-\-\-\-\-\-\-\--

Multi-comparator (multi-criterial) tree:
FASTER-CHEAPER-DURABLER-REALIABLER

How many paths do we need in such tree in order to be x% sure
(confidence, volatility, expiration (valability-lifetime)) of computable
criteria?

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

Clock/time drift in virtual machines.

Clock synchronization with several NTP servers over jittery
communication media.

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

\

\

A secret order of events is partitioned to N senders.

The physical clock sync is performed with multiple NTP servers (like GPS
satellites).

Based on the registered drift (a shift to the PDF - probability
distribution function), a volatile-expirable expectency of correct
ordering is computed.

Between the N senders and the 1 receiver, there is a network of
multi-layer nodes (L1-L7 ISO/OSI), each operating on the PDF function on
time jitter.

\

The purpose of the 1 receiver is to maximize the probability that the
relationships between any-two events can be established to be as
\"happens-before\" (i.e. as opposed to unknown)

\

\-\-\-\-\-\-\-\-\--

Patinne Time Chains

 
