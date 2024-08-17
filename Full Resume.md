# Full Resume

An IT professional with a passion for automation and innovation, harnessing 9 years of experience in automation, scripting, API development, PowerShell, Windows system administration, and software packaging. Building system integrations and tools to automate drudgery and restore meaningful work to the modern professional.

## Employment History

### Endpoint Platform Engineer, Dart Container (Contracted by TEKsystems)

February 2023 – Current
Mason, MI

- Automated almost all the application packaging & lifecycle management work by writing a PowerShell module ([Larner.ConfigManager](https://github.com/alexlarner/Larner.ConfigManager)) and training the team on how to use it
- Created standards, process, and procedure documentation for application packaging
- Overhauled linked server patching from a custom codebase of tens of thousands of lines of PowerShell, SQL, and C# code, and a SQL DB, into multiple Orchestration Groups in Config Manager and less than a hundred lines of code
- Transformed the team’s documentation from Word docs on a network share to a version-controlled Azure DevOps Wiki utilizing Markdown
- Packaged applications for deployment through Config Manager (formerly SCCM) utilizing PatchMyPC and the PSAppDeployToolkit

### Pulpit Committee Chairman, Grace Bible Church

February 2022 - July 2024
Lansing, MI

- Led a committee of 10 people through hiring an interim pastor and a permanent full-time pastor
- Wrote doctrinal questionnaires to vet candidates
- Created hiring process workflow
- Facilitated collaboration by setting up a Discord server for the committee and trained the members on its use
- Administrated regular meetings in accordance with Robert’s Rules of Order

### IT Automation Engineer, Neogen Corporation

May 2021 – February 2023
Lansing, MI

- Automated the IT onboarding & offboarding of all associates and all the user property updates (i.e. name change, job title/location/department change) by integrating our HR system with Active Directory. The automated system:
    - Created, updated, and disabled Active Directory & Entra accounts
    - Sanitized & standardized input data from HR to align with ISO standards (i.e. country & state/province name, etc.) and created tickets for HR to fix data that was too incorrect to be sanitized
    - Generated and closed tickets to document the automated work that was done, including tasks for each part of the process so we’d have a “paper” trail for Internal Audit
        - It also created and assigned tasks to humans for special handling for exceptional cases (i.e. offboarding of an Admin/high-profile user)
    - Was powered by a PowerShell API ([Larner.FreshService](https://github.com/alexlarner/Larner.FreshService)) for our Help Desk system (FreshService), and accompanying scripts; tying together Workday, Active Directory, Azure Active Directory (now Entra ID), Graph REST API, and the FreshService REST API.
    - Included regular meetings with stakeholders (IT & HR management) to determine scope and later to discuss desired updates
    - Was pivotal in the onboarding of thousands of associates over the course of a few days, after the company’s largest acquisition
- Worked with management to create automated reports on infrastructure health & security in advance of our internal audits. Then worked to create proactive automated remediations of the major issues found before the audit.
- Implemented version control using Git & GitHub and PlantUML activity diagrams for all major IT infrastructure code
- Wrote a [PowerShell Learning Path](https://github.com/alexlarner/PowerShell-Learning-Path) for IT associates of all PowerShell skill levels
- Reviewed, updated, rewrote, and documented all major infrastructure PowerShell scripts and modules
- Secured time-sensitive international contract bonuses for the company by optimizing current code & data processing for transferring large files through China’s “Great Firewall”
- Trained colleagues on PowerShell programming and scripting
- Lead the way to the adoption of Confluence as the documentation standard for Neogen IT, while serving on the cross-functional Documentation steering committee

### Senior Systems Engineer, Jackson National Life Insurance

March 2016 – May 2021
Lansing, MI

- Created a [PowerShell API for BMC Client Management](https://github.com/alexlarner/BMCClientManagement) (a Config Manager/SCCM alternative) for automating software packaging & installs
- Automated the creation of all new user VMs in the company and the imaging/reimaging process of all laptops & desktops in the company in a process that came to be known as the “Automated Factory”, in a company that exclusively used VMs for all their work:
    - It created 3 different builds (Base, Operations, and Sales) of VMs and always kept a specified number of each of them in stock in the “Factory” & “Parking Lot” areas
        - Applications in each of the Build types, number of VMs to always keep in stock, and VM stock count refill triggers were defined by CSVs, and could be changed by just adding/changing/deleting a row
    - There were two different areas for VMs:
        - A “Factory” where “Base” build type VMs were created, built up to one of the other “trim” build types (Operations or Sales) as needed, and moved to the “Parking Lot” to refill as needed
        - A “Parking Lot” where VMs were ready for other IT teams to move off and assign to the new user
    - It consisted of 4 different scripts (Build Base VM, Convert Base VM into other builds, Refill Parking Lot from Factory, and Factory Status) that ran independently and could keep running if the other scripts were not functioning
        - Those scripts utilized my [PowerShell API for BMC Client Management](https://github.com/alexlarner/BMCClientManagement) and VMware’s PowerShell API for vSphere (PowerCLI)
    - VMs were balanced between datacenters, hosts, and datastores
    - It wrote logs documenting the status of each machine through the process
    - It emailed regular status updates of the VM build type counts & statuses to management
    - It had built over 3,000 VMs as of 2021
- Created and maintained a documentation framework on Confluence for all packaged applications, which included management sign-off and internal troubleshooting documentation for Tier 1-3 IT teams
- Lead multiple major upgrades of critical third-party business applications, i.e. VMware Horizon Client, VMware Tools, Creative Suite conversion to Adobe Creative Cloud
- Packaged hundreds of applications for automated deployment to our environment of over 15K machines

### Strategic Support Associate, Jackson National Life Insurance

August 2015 — March 2016
East Lansing, MI

#### Curian Special Project

- Part of a secure, select group of the most efficient processors in the Strategic Support Program (SSP) chosen to be in an extremely fast paced and high pressure project
- Collaborated with corporate trainers to update the Denver office’s process manuals & create checklists for processing
- Pioneered the use of the touchscreens at The Zone in processing, leading to a 50% reduction in personal processing time for Curian skills, becoming the fastest Curian processor

#### Peer Leader & Skill Leader

April 2014 — March 2016

- Zone ‘Employee of the Month’ for October 2014
- Aided new associates in their first two weeks at Jackson
- Eased new associates’ information overload through reinforcing the key need to know information
- Fixed VDI and application errors that occurred in the associates’ onboarding
- Provided critical leadership in system-wide outages by being the liaison between IT and SSP. Personally informing all associates at my location of the outage, current status of the fix, walking them through the temporary fixes, and informing them of the work they could do in the interim
- Provided ongoing leadership for weeks-long system errors by communicating to IT the scope of the problem, disseminating the temporary fixes to the hundreds of SSAs, and compiling summaries of the error and the impact for SSP Management.
- Met regularly with SSP Management and other Peer Leaders to brainstorm ways to improve the SSP Program as a whole and the Jackson Onboarding process
- Answered questions about SSP procedures, Jackson applications, and complex Claims and Curian processing questions by phone, email, and in person for the hundreds of Zone associates
- Wrote a 2-page manual for logging into the soft (computer-based) phones and listing the common errors and their fixes (including screenshots), addressing the inadequacy of the manufacturer’s bloated 10-page manual
- Provided on-site support fixing various VDI, Thin Client, and application errors for associates across The Zone

#### Claims Department

October 2013 — March 2016

- Utilized 16 different in-house applications to process claims across 6 different Jackson & Jackson-acquired companies
- Navigated hundreds of documents per policy and contact records to determine the all the applicable policies and their current beneficiaries
- Investigated homicides via police reports and even State Supreme Court rulings to determine if we could pay the named beneficiary
- Wrote the manual for the advanced Claims skills which was later used to train new associates

#### Executive Committee Member, Eaton County Republican Party

November 2012 — November 2016
Lansing, MI

- Executive Committee Member elected by the Precinct Delegates of Eaton County
- Youngest member ever elected to the Executive Committee
- Finance Committee Member
- Created and maintained the >750 person member and visitor database for the Eaton GOP
- Coordinated & oversaw annual Lincoln Tribute Dinner Fundraiser's ad and tickets sales
- Created 2013, 2014, and 2015 program/ad booklet for the fundraiser

### Intern, Bible Baptist Church of Ballincollig, Ireland

June 2013 — September 2013
Ballincollig, Cork, Ireland

- Renovated part of the church's website
- [Revived and produced globally](http://www.theirishbible.ie/) the only Protestant New Testament in the Irish language that had previously been unknown and out of print for over 100 years
- Manually transcribed Bible from scanned images of an 1817 Bible in Irish into Microsoft Word documents side by side with the English.
- Collaborated with the British Foreign Bible Society and subsequently converted the transcription into USFM format to be used in Paratext and the YouVersion Bible App
- Data entry into church's database

### Intern, State Representative Deb Shaughnessy

January 2011 — April 2011
Anderson House Office Building, Lansing, MI

- Wrote official letters to constituents
- Communicated over the phone with constituents regarding public policy issues and legislation
- Composed official Michigan House of Representatives Tributes
- Related constituent concerns to the representative and strategized official responses
- Monitored local news & events for necessary official contact

### Intern & Planning Committee Member, Information Network for Christian Homes (INCH)

August 2008 — May 2011
Lansing, MI

- Maintained the vendor database for our annual convention
- Maintained the registration database for the annual convention and the membership rolls
- Created reports, nametags, and mailings from the database for the >3,000 convention attendees
- Identified key organizational strengths and weaknesses during the top leadership transition
- Advised on speaker selection and coordinated speaker contracts for our annual convention
- Logistical support for conference layout across the Lansing Center and adjoining Radisson Hotel
- Provided On-site AV support for speakers

## Technical Skills

### Expert

- Automation
- Scripting
- System
- PowerShell
- Rest API
- Markdown
- Documentation
- Software Packaging
- FreshService
- BMC Client Management
- Tier III IT Support
- Windows System Administration

### Proficient

- Git
- Azure DevOps
- Azure
- Entra ID
- Graph API
- Configuration Manager/MCM/MECM/SCCM
- Active Directory
- Group Policy
- Regex
- PlantUML
- Agile
- BMC Remedy
- ServiceDesk+
- Confluence
- JIRA
- Linux
- Microsoft 365
- VMware
- VMware PowerCLI

### Familiar

- .NET
- Batch
- CSS
- HTML
- Intune
- ITIL
- Python
- SQL
- XML

## Soft Skills

- Problem Solving
    - Analysis
    - Decision-making
    - Planning
    - Research
- Teamwork
    - Collaboration
    - Delegation
    - Hospitality
    - Organization
- Training
    - Leadership
    - Mentoring
    - Patience
    - Public Speaking
- Work Ethic
    - Adaptability
    - Detailed
    - Innovation
    - Inquisitive
    - Self-Motivation

## Education History

Leadership Institute - Communications Academy - 2016, 2017, 2018, 2019
Homeschool - High School Diploma - 2012
Leadership Institute - Leadership & Campaign Academy - 2010
TeenPact Leadership School - Leadership School - 2008, 2009, 2010, 2011, 2012
