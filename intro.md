### What does it do?

- Documents best practice and recommendations for how to indicate and handle Groups of Resources in AMWA NMOS APIs.
- Currently this addresses "Natural Groups", i.e. those created by the default operation of a Node/Device, and not user- or automation-defined Groups.

### Why does it matter?

- Provides a consistent way of referring to groups of related Resources (e.g. video and audio Senders of a camera)
- This helps with interoperability and integration.

### How does it work?

- [BCP-002-01](branches/master/best-practice-natural-grouping.html) recommends Nodes add a ``grouphint`` tag to the JSON representation of each member of a Natural Group
