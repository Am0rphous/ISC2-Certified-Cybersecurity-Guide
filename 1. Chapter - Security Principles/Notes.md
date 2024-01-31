# Security Concepts
CIA Traid are three main goals

## Confidentiality
- Confidentiality protects information from unauthorized disclosure.

#### Confidentiality_Concerns
1. Snooping
	- snooping gathering information that is left out in the open.
	- "Clean desk policies" protect against snooping.
2. Dumpster Diving
	- Dumpster diving is to dump data anywere or dustbin.
	- "Shedding" protects against dumpster diving.
3. Eavesdropping
	- listing sensitive information
	- "Rules about sensitive conversations" prevent eavesdropping
4. Wiretapping
	- Electronic evaesdropping - listing through wire(internet)
	- "Encryption" protects against Wiretapping
5. Social Engineering
	- The attacker uses psychological tricks to persuade an employee to give then sensitive information or access to internal systems.
	- Best defence is to "Educating users"


## Integrity
- Integrity protects information from unauthorized changes.
#### Integrity_Concerns
1. Unauthorized modification
	- Attacks make changes without permission.
	- "Least priviege" protects against integrity attacks
2. Impersonation
	- Attacks pretend to be someone else
	- "User education" protects against attacks
3. Man-in-the-middle (MITM)
	- Attacks place the attacker in the middle of a communications session.
	- "Encryption" protects against MITM attacks
4. Replay
	- Attacks eavesdrop on logins and reuse the captured credentials.
	- "Encryption" protects against Replay attacks

## Availability
- Availability protects authorized access to systems and data.
#### Availability_Concerns
1. Denial of service (DoS)
	- Unlimited request to a server
	- "Block unauthorized connections" to protect against denial of service attacks.
2. Power outages
	- Naturally or Man-made
	- "Redundant power and generators" protect against power outages.
3. Hardware failures
	- any component failures
	- "Redundant components" protect against hardware failure
4. Destruction
	- Naturally or Man-made
	- "Backup data centers" protect against destruction.
5. Service outages
	- Programing error and the failure of underlying equipment.
	- building systems that are resilient in the face of errors and hardware failures.


## Authentication and authorization
The access control process consists of three steps that you must understand. These steps are identification, authentication and authorization.

1. Identification incolves making a claim of identity.
	- Electronic identification commonly uses usernames
2. Authentication requires proving a claim of identity.
	- Electronic autherntication commonly uses passwords.
3. Authorization ensures that an action is allowed.
	- Electronic authorization commonly uses access control lists.

Authentication and authorization process, access control systems also provide "Accounting" functionality that allows administrators to track user activity and reconstruct that activity from logs. This may include tracking user activity on systems and even logging user web browsing history.


## Password security
Password mechanisms
	- Password length requirements set a minimum number of characters. 
	- Password complexity requirements describe the types of characters that must be included.
	- Password expiration requirements force password changes.
	- Password requirements prevent password reuse.


## Multifactor authentication
Multifactor authentication combines two different authentication factors.

Three different authentication factors. Something you know, something you are and something you have.

#### something you know
- Passwords, PIN's, Security questions.
#### something you are
- Biometric security mechanisms.
#### something you have
- Software and hardware tokens.

#### single sign-On (SSO)
Shares authentiacated sessions across systems
	- In a single sign on approach, users log on to the first SSO enabled system that they encounter. And then that login session persists across other systems until it expires. If the organization sets the expiration period to be the length of a business day, that means that users will only need to log in once a day and their single sign on is then going to last the entire day.


## Non-repudiation
Non-repudiation prevents someone from denying the truth.

Solved the issue with
	1. Signed contracts
	2. Digital signatures
	3. Video surveillance


## Privacy
Privacy Concerns
1. Protecting our own data.
2. Educating our users.
3. Protecing data collected by our organizations.

Private information may come in many forms. Two of the most common elements of private information are "Personally identifiable information" and "Protected health information".
1. Personally identifiable information, or PII, includes all information that can be tied back to a specific individual. 
2. Protected health information, or PHI, includes healthcare records that are regulated under the Health Insurance Portability and Accountability Act. Otherwise known as HIPAA.

# Risk Management
## Understanding risks
- Internal Risks: Arise from within the organization.
- External Risks: Arise from outside the organization.
- Multiparty Risks: Affect more than one organization.
- Intellectual property therft : poses a risk to knowleage-based organizations.
- Software license compliance: issues risk fines and legal action.


## Risk assessment
Risk assessment identifies and triages risks.

- Threats: are external forces that jeopardize security.
- Vulnerabilities: are weaknesses in your security controls.
- Risks : are the combination of a threat and a vulnerability.

Risks rank by Likelihood and Impact.
- Likelihood: is the probability a risk will occur.
- Impact: is the amount of damamge a risk will cause.

we have two different categories of technique that we can use to assess the likelihood and Impact of a risk.

1. Qualitative Risk Assessment: Uses subjective ratings to evaluate risk likelihood and impact.
2. Quantitative Risk Assessment: Uses Objective numeric ratings to evaluate risk likelihood and impact.


## Risk treatment
Risk treatment analyzes and implements possible responses to control risk.

Risk Treatment Options
1. Risk avoidance
	- Risk avoidance changes business practices to make a risk irrelevant.
2. Risk transference
	- Risk treatment analyzes and implements possible responses to control risk.
3. Risk mitigation
	- Risk mitigation reduces the likelihood or impact of a risk.
4. Risk acceptance
	- Risk acceptance is the choice to continue operations in the face of a risk.

## Selecting security controls
Security controls reduce the likelihood or impact of a risk and help identify issues.

Two different ways of security controls
1. Control Purpose
	1. Preventive
		- Preventive controls stop a security issue from occcurring.
	2. Detective
		- Detective controls identify security issues requiring investigation.
	3. Corrective
		- Recovery controls remediate security issues that have occurred.
2. Control Mechanism
	1. Technical
		- use technology to achieve control objectives.
	2. Administrative
		- use processes to achieve control objectives.
	3. Physical
		- Impact the physical world.
		
## Configuration managment
Tracks specific device settings
- Baselines: Provide a configuration snapshot.
- Versioning: Assigns numbers to each varsion.
- Diagrams serve as important configuration artifacts.
- Standardize Device Configurations
	- Naming conventions
	- IP adderessing schemes
- Change and management help ensure a stable operating environment.

