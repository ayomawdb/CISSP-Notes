# Security Governance Through Principles and Policies

---
## CIA Triad
---

### Confidentiality
Objects are restricted from unauthorized subjects.

> #### Sensitivity
> Quality of information, which could cause harm or damage if disclosed.
>
> #### Discretion
> Act of decision where an operator can influence or control disclosure in order to minimize damage.
>
> #### Criticality
> The level to which information is mission critical.
>
> #### Concealment
> Act of hiding or preventing disclosure (cover, obfuscation, or distraction).
>
> #### Secrecy
> Act of keeping something a secret or preventing the disclosure.
>
> #### Privacy
> Keeping information confidential that is personally identifiable.
>
> #### Seclusion
> Storing something in an out-of-the-way location.
>
> #### Isolation
> Act of keeping something separated from others.

### Integrity
Objects must retain their veracity and be intentionally modified by only authorized subjects

### Availability
Authorized subjects are granted timely and uninterrupted access to objects

---
## Other Security Concepts
---

### Identification

* Process by which a subject professes an identity and accountability is initiated.
* Start the process of authentication, authorization, and accountability (AAA)
   * Identification
   * Authentication
   * Authorization
   * Auditing
   * Accountability


### Authentication

Verifying or testing that the claimed identity is valid is authentication.

### Authorization

Ensures that the requested activity or access to an object is possible given the rights and privileges assigned to the authenticated identity.

####  Access Control Concepts

* Discretionary access control (DAC)
* Mandatory access control (MAC)
* Role-based access control (RBAC)

### Auditing

Subject’s actions are tracked and recorded for the purpose of holding the subject accountable

### Accountability

Subjects are held accountable for their actions

### Nonrepudiation

Ensures that the subject of an activity or event cannot deny that the event occurred

---
## Protection Mechanisms
---

* Layering
   * Defense in depth (Parallel / Serial configuration)
* Abstraction
   * Similar elements are put into groups, classes, or roles that are assigned security controls, restrictions, or permissions as a collective.
* Data Hiding
* Encryption

---
## Security Governance
---

* Collection of practices related to `supporting`, `defining`, and `directing` the security efforts of an organization
* Common goal: Maintain business processes while striving toward growth and resiliency.

### Security Management Planning

* Proper creation, implementation, and enforcement of a security policy.
* The information security (InfoSec) team should be led by a designated chief security officer (CSO) who must report directly to senior management.

#### Strategic Plan

Align security functionality to goals, mission, and objectives of the organization

#### Tactical Plan

Details on accomplishing the goals set forth in the strategic plan or can be crafted ad-hoc based upon unpredicted events

(project plans, acquisition plans, hiring plans, budget plans, maintenance plans, support plans, and system development plans)

#### Operational Plan

Highly detailed plan based on the strategic and tactical plans

(training plans, system deployment plans, and product design plans)

### Organizational Processes

#### Change Control/Management

* Any change does not lead to reduced or compromised security
* Implement changes in a monitored, controlled and orderly manner.
* Formalized testing process is included to verify that a change produces expected results.
* All changes can be reversed.
* Users are informed of changes.
* The effects of changes are systematically analyzed.
* The negative impact of changes is minimized.
* Changes are approved by a CAB (change approval board).

#### Data Classification

##### Usages
* Demonstrates organization’s commitment to protecting valuable resources and assets.
* Assists identifying assets that are most critical or valuable.
* Selection of protection mechanisms.
* Required for regulatory compliance or legal restrictions.
* Helps to define access levels, types of authorized uses, and parameters for declassification and/or destruction of resources that are no longer valuable.
* Helps with data life-cycle management (retention, usage, destruction).

##### Steps

* Identify the custodian, and define their responsibilities.
* Specify the evaluation criteria of how the information will be classified and labeled.
* Classify and label each resource.
* Document any exceptions to the classification policy.
* Select the security controls that will be applied to each classification level.
* Specify the procedures for declassifying and transferring resources to external entity.
* Create an enterprise-wide awareness program on classification system.

##### Levels of government/military classification

* Top Secret
* Secret
* Confidential
* Sensitive but Unclassified
* Unclassified

(U.S. Can Stop Terrorism) Capital letters, backwards.  

Top 3 - also called "Classified"

##### Business / Private sector classification

* Confidential
* Private
* Sensitive
* Public

### Security Roles and Responsibilities

#### Senior Manager

* Ultimately responsible for the security maintained by an organization (liable)
* Must sign off on all policy issue
* `Delegate to "Security Professional"`

#### Security Professional

* Responsible for following the directives mandated by senior management (not decision makers)
* Functional responsibility for security, including writing the security policy and implementing it

#### Data Owner

* Responsible for classifying information for placement and protection within the security solution (high-level manager who is ultimately responsible for data protection)
* `Delegate to "Data Custodian"`

#### Data Custodian

* Responsible for
the tasks of implementing the prescribed protection defined by the security policy and
senior management
* Adequate protection for the CIA Triad
   * Testing backups
   * Validating data integrity
   * Deploying security solutions
   * Managing data storage based on classification

#### User

* Any person who has access to the secured system
* Responsible for understanding and upholding the security policy

#### Auditor

* Reviewing and verifying that the security policy is properly implemented and the derived security solutions are adequate

### Control Framework - Control Objectives for Information and Related Technology (COBIT)

* By Information Systems Audit and Control Association (ISACA)
* Prescribes goals and requirements for security controls
* Encourages the mapping of IT security ideals to business objectives.

Principles:
* Principle 1: Meeting Stakeholder Needs
* Principle 2: Covering the Enterprise End-to-End
* Principle 3: Applying a Single, Integrated Framework
* Principle 4: Enabling a Holistic Approach
* Principle 5: Separating Governance From Management

#### Other Standards and Guidelines for IT Security

* Open Source Security Testing Methodology Manual (OSSTMM)
* ISO/IEC 27002 (which replaced ISO 17799)
* Information Technology Infrastructure Library (ITIL)

---
## Develop and Implement Documented Security Policy, Standards, Procedures, and Guidelines
---

### Security Policies

* Defines the scope of security needed
* Discusses the assets that require protection
* Extent to which security is needed

* Importance of security to every aspect of daily business operation
* Used to:
   * assign responsibilities (to a role (not a person))
   * define roles
   * specify audit requirements
   * outline enforcement processes
   * indicate compliance requirements
   * define acceptable risk levels

#### Categories of Security Policies

* `Regulatory` - Whenever industry or legal standards are applicable to your organization
* `Advisory` - Discusses behaviors and activities that are acceptable and defines consequences of violations
* `Informative` - Provide information or knowledge about a specific subject, such as company goals

### Standards

* Define compulsory requirements for the homogenous use of hardware, software, technology, and security controls
* Tactical documents that define steps or methods to accomplish the goals

### Baselines

Defines a minimum level of security that every system throughout the organization must meet

Refer to :

* Trusted Computer System Evaluation Criteria (TCSEC)
* Information Technology Security Evaluation and Criteria (ITSEC)
* NIST (National Institute of Standards and Technology)

### Guidelines

* Offers recommendations on how standards and baselines are implemented
* Serves as an operational guide for both security professionals and users

### Security Procedures

Detailed, step-by-step how-to document that describes the exact actions necessary to implement a specific security mechanism, control, or solution

---
## Threat Modeling
---

* Potential threats are identified, categorized, and analyzed
* Identify what the attacker may be trying to accomplish (categorize threats)
* Attempts to reduce vulnerabilities and reduce the impact of any vulnerabilities
* Support - Secure by Design, Secure by Default, Secure in Deployment and Communication (SD3+C)

### Identifying Threats

* `Focused on Assets` - Use asset valuation results and attempts to identify threats to the valuable assets
* `Focused on Attackers` - Identify potential attackers and can identify the threats they represent based on the attacker’s goals.
* `Focused on Software`

### Categorizing Threats

Microsoft STRIDE

* `Spoofing` - Falsifing identity
* `Tampering` - Unauthorized changes / manipulations
* `Repudiation` - Deny having performed an action
* `Information Disclosure`
* `DOS`
* `Elevation of Privileges`

### Determining & Diagramming Potential Attacks

* Diagram of the elements involved in a transaction along with indications of data flow and privilege boundaries
* Identify all of the technologies involved (OS, Apps, Protocols)
* Identify attacks that could be targeted at each element of the diagram

### Performing Reduction Analysis

* Gain a greater understanding of the logic of the product as well as its interactions with external elements
* Divided into smaller containers or compartments (modules / protocols / tasks / networks)
* subelement should be evaluated in order to understand inputs, processing, security, data management, storage, and outputs

Identify following:

* `Trust Boundaries` - Any location where the level of trust or security changes
* `Data Flow Paths` - The movement of data between locations
* `Input Points` - Locations where external input is received
* `Privileged Operations` - Any activity that requires greater privileges than of a standard user account or process.
* `Details about Security Stance and Approach` - The declaration of the security policy, security foundations, and security assumptions.

### Prioritization and Response

* Probability × Damage Potential  (1 to 100 scale, 100 being most severe)
* high/medium/low
* DREAD system
   * `Damage potential` - How severe is the damage likely to be if the threat is realized?
   * `Reproducibility` - How complicated is it for attackers to reproduce the exploit?
   * `Exploitability` - How hard is it to perform the attack?
   * `Affected users` - How many users are likely to be affected by the attack (as a percentage)?
   * `Discoverability` - How hard is it for an attacker to discover the weakness?

---
## Integrate Security Risk Considerations into Acquisition Strategy and Practice
---

When evaluating a third party for your security integration:
* On-site assessment
* Document exchange and review
* Process / policy review (SLA...)

Resources on security integrated with acquisition:
* Improving Cybersecurity and Resilience through Acquisition. Final Report of the Department of Defense and General Services Administration
* NIST Special Publication 800-64 Revision 2: Security Considerations in the System Development Life Cycle
