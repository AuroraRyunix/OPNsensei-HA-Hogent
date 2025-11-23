# OPNsense-HA-Hogent
- i did not figure out how to get the header bigger, sad

# Project 3 — Linux & DNS

## 1. Scenario
You just joined a “medium-sized IT company,” which is corporate speak for too poor for real engineers but too big for one guy with a screwdriver.
Management discovered that Windows licenses aren’t free. Genius.

So now you get to migrate everything to Linux.
Why you? Because you once said “I installed Ubuntu once.”
Your task list of joy:
- Replace Windows File Server + ADDS → Samba
- Replace Windows DNS/DHCP → BIND + ISC DHC
- Replace IIS → Nginx
- Replace firewall → OPNSense
- Replace your will to live → Multiple distros simultaneously

Of course, you must use four different distros.
Why? Because nothing says “fun” like managing DEB, RPM, Alpine, and Mint all in one week.
Make a network diagram. It won’t help, but it looks professional.


## 2. Opdracht
### 2.1 Administratie & Afspraken
First we do paperwork, then we break things.
Keep track of:
- Hostnames
- IP-addresses
- Accounts
- Passwords

Because when you inevitably wipe a server, you’ll want evidence that it wasn’t your fault.

#### Logblad Problemen
Record every disaster:
- What broke
- How you fixed it (or pretended to)
- Who found the fix
- Where you found it
- Whether it worked without traumatizing you
- Steps, so others can repeat your suffering

#### Logblad ToDo's
Track your tasks, your progress, and your dignity slowly fading.
Include time spent, so you can prove Linux stole your weekend.

Use Trello, the sticky-note simulator.

#### Afspraken voor Nutanix
- VM names must follow the structure:
WP2_<initialen>_LIN_<omschrijving>
Example: WP2_JB_LIN_Mint
If you name it "linux-test-123", Get out.
-Use the NAT network with VLAN ID > 2000.
Because apparently we love VLAN puzzles.
-Local admin username = your first name
-Password = Hogent*123
Security? Never heard of her.
-Don’t enable flash mode.
This isn’t SAP HANA.
-Make snapshots often.
This is not optional unless you enjoy reinstalling.
