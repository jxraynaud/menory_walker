# menory_walker

## First steps

### Memory tree
We need to define the precise structure, but it might be something like that:
* Summary (to help the agent decide which node/leaf to follow)
* Type: leaf or node
* Metadata
* Content

### Being able to walk the memory tree
* The agent must be able to walk the memory tree while looking for information.
* The agent must be able to decide if he has enough information to stop the search or if he needs to continue to walk the tree.
* The agent must be able to store intermediary results.
