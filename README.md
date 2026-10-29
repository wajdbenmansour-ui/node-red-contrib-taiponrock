# node-red-contrib-taiponrock

\# node-red-contrib-taiponrock



\## Overview



This Node-RED node receives an input message and replaces its payload with the constant string "Wajd Ben Mansour".



Regardless of the input value, the node always returns the same string.



\## How to use



1\. Add an Inject node to your flow.

2\. Add the `wajd-node` node.

3\. Add a Debug node.

4\. Connect them in this order: Inject → wajd-node → Debug.

5\. Deploy the flow and click the Inject button.



The Debug panel will display:



`Wajd Ben Mansour`



\## Requirements



\- Node.js

\- Node-RED



\## Changelog



\### 1.0.0

\- Initial release.

\- Added the wajd-node custom node.

