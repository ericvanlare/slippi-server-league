# Slippi Server League
Hypothesis: there's an easy way to automate a Windows Server AWS Lightsail instance to broadcast bracket matches for online tournaments. This would be a big stepping stone for online melee communities.

# Work breakdown
- [ ] Either 1) inject some code into the slippi-launcher electron app or 2) fork slippi-launcher with added code for this. This is the most engineering-intensive part of the project from what I can tell
- [ ] Chip away at automating OBS config in a server so that there's no need to remote desktop inside and activate things graphically
- [ ] CI/CD and deployment flows
- [ ] User interface - could be as minimal as a command line inside the lightsail, but automating deployments and CI/CD would be great. Starting point can also just be doing everything inside lightsail remote desktop, that'd be fine.
