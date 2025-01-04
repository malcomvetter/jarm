# JARM

This is a refactor of the original (now stale) JARM project, open sourced by Salesforce: https://github.com/salesforce/jarm

JARM is an active Transport Layer Security (TLS) server fingerprinting tool.

JARM fingerprints can be used to:
- Quickly verify that all servers in a group have the same TLS configuration.
- Group disparate servers on the internet by configuration, identifying that a server may belong to Google vs. Salesforce vs. Apple, for example.
- Identify default applications or infrastructure.
- Identify malware command and control infrastructure and other malicious servers on the Internet.

See the original project and blogs for more about what JARM is and can do.

  
### Example Output  
| Domain | JARM |
| --- | --- |
| salesforce.com | `2ad2ad0002ad2ad00042d42d00000069d641f34fe76acdc05c40262f8815e5` |
| force.com | `2ad2ad0002ad2ad00042d42d00000069d641f34fe76acdc05c40262f8815e5` |
| google.com | `27d40d40d29d40d1dc42d43d00041d4689ee210389f4f6b4b5b1b93f92252d` |
| youtube.com | `27d40d40d29d40d1dc42d43d00041d4689ee210389f4f6b4b5b1b93f92252d` |
| gmail.com | `27d40d40d29d40d1dc42d43d00041d4689ee210389f4f6b4b5b1b93f92252d` |
| facebook.com | `27d27d27d29d27d1dc41d43d00041d741011a7be03d7498e0df05581db08a9` |
| instagram.com | `27d27d27d29d27d1dc41d43d00041d741011a7be03d7498e0df05581db08a9` |
| oculus.com | `29d29d20d29d29d21c41d43d00041d741011a7be03d7498e0df05581db08a9` |  


### Acknowledgments

[John Althouse](https://www.linkedin.com/in/johnalthouse/)
[Andrew Smart](https://www.linkedin.com/in/andrew-smart-a3b15a2/)
[RJ Nunnally](https://www.linkedin.com/in/rjnunnally/)
[Mike Brady](https://www.linkedin.com/in/mike-brady-b5293b21/)
[Caleb Yu](https://www.linkedin.com/in/caleb-yu/)