# becoming-a-windows-admin

So you want to be a Windows sysadmin?

Despite the incessant Linux dudes at [/r/sysadmin](https://sysadmin.reddit.com) saying there's nothing to being a Windows admin, if you want to work smarter and not harder, spend less time doing the work than it would even take to properly Google it, and generally be a sysadmin worth having on a team, you should strive for a broad set of skills.

The inspiration for this is the well-known post on [becoming a Linux admin](https://www.reddit.com/r/linuxadmin/comments/2s924h/how_did_you_get_your_start/cnnw1ma) by iConrad. It's a tough-love approach that encourages you to independently research and gives you leeway in exactly how you implement a solution. I'm not quite as tough-love, but there will be some directions that I will encourage you to find on your own.

This is going to be a "head-first" exercise, and it assumes no previous experience with Windows Server and basic experience with Windows. We will use exclusively evaluations of software so there is no cost. If you wish to follow along with the Exchange module, I highly recommend purchasing a domain name, or asking a friend with a domain name to create some DNS records for you. If you don't have any friends (with domain names), submit an issue on GitHub with your IP and the subdomain you want to use off of bluesoul.me.

# ISO Files

Make sure you have each of these ISOs. They are available as evaluations on the Microsoft website.

* Windows 7 Pro
* Windows 8.1 Pro
* Windows 10 Pro
* Windows 10 Enterprise
* Windows Server 2008 R2 Standard
* Windows Server 2012 R2 Standard
* Microsoft SQL Server 2014 SP1
* Microsoft Exchange 2013
* Microsoft Office Pro Plus 2013
 
(Why SQL Server and Exchange? As a Windows admin you should be familiar with some of the most commonly used server software applications. You can skip the chapters if you wish but I would recommend at least browsing through the content.)

# System Requirements

I'll adjust this when I have a better idea of what the minimum is, but I'd hazard a guess it's something along the lines of...

* Quad-core virtualization-ready CPU
* 16GB RAM (You can probably get by with 8 or even less but it'll be slower)
* 160GB Storage
* Virtualization platform. I'll be using VMware Workstation but you can also use Oracle Virtualbox, ESXi, or Hyper-V, or whatever else lets you put a bunch of VMs on the same virtual network.

# Chapters

1. Building The Lab Core
2. Creating an AD Topology
3. Essential Network Services
4. Your First File Server
5. Windows Server Update Services
6. Getting Started with Group Policy
7. Removing Attack Surface with Server Core
8. PowerShell
9. AD Topology Maintenance
10. Decommissioning a Server
11. DFS
12. Terminal Services
13. Installing SQL Server
14. Backup and Restore of SQL Server Databases
15. Installing Exchange
16. A Brief Discussion on DNS
17. Exchange Configuration and Mail Flow
18. Advanced File Sharing Topics
19. AppLocker
20. Group Policy for Security

More to come as I think of them.
