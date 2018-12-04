# Notes
Logs for work sessions while preparing for the Linux Foundation's *Kubernetes for Developers* exam.Meant to allow continuous learning, even for short work sessions.

#### 12.3.2018
- Checked system requirements use `./ready-for.sh LFD259`.

- Need to fix a few packages that don't have valid gpg key signatures (google cloud sdk, qgis nightly).

Example message:
`W: GPG error: http://qgis.org/debian xenial InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY CAEB3DC3BDF7FB45`

- Fixed the GPG keys through QGIS and Google Cloud API documentation.
- Ran `sudo apt-get update && sudo-apt-get upgrade`

**Chapter 1**
Learning goals of the course:
1.  Containerize and deploy anew Python script
2.  Configure the deployment with ConfigMaps, Secrets, and SecurityContexts
3.  Understand multi-container Pod design
4.  Configure Probes for pod health
5.  Update and roll back an application
6.  Implement services and NetworkPolicies
7.  Use PersistentVolumeClaims for state persistence


Mostly about the Linux foundation, linux distributions.  Finshed with an exercise for examining system information (filesystem `df`, resources `free`, etc).
