## 01. Master Policy
- captures the overall structure of the policy set.
- includes rules around updating and approval.
- describes who needs to follow policies(employees and contractors).
- lays out consequences for not following policies.
#### What you need to do? 
- Appoint a security officer
- Have a security@ email address.
- Approve policies annually.
- Include tracking data in policies.
- Make sure people are aware of policies/Train on policy.
- work through violations process.

## 02. Acceptable Use Policy.
- Explains to employees and contractors what the expected use of company resources looks like.
- The goal is to ensure that company resources aren't used in negligent or worse, criminal ways.
- Covers: cloud, devices software, systems, and personal devices.
#### What you need to do?
- Ok to use personal phone for email, messaging. Not ok to store client data, review code, share data on personal laptop/phone/device including via dropbox or shared storage devices.
- Company provided laptop/phone etc. are intended for use for company business. malicious or unlawful use of resources is not intended, sanctioned or supported and cloud be a violation of policy.
- Cloud based storage should be used consistently within company approved workflows.

## 03. The application security policy.
- Explains to employees and contractors how we aim to build secure applications.
#### What you need to do?
- Have an software development life cycle(SDLC) and use a source code management system(github).
- Perform security code review.
- Keep an inventory of applications.
- Consider security architecture.
- Security training(OWASP).
- Libraries(Licensing + updating)

## 04. Asset management.
- Keeping track of all the things.
- Assets are computers, phones, keys, servers, licenses, etc.
#### What you need to do?
- Come up with tracking process.
- Track laptops, servers, phones, keys, software licenses.
- Verify quarterly that new assets are being tracked. 

## 05. BCP(Business Continuity Planning) Policy.
- Consideration is to be given to mission critical systems and how to keep them available to the degree necessary.
#### What you need to do?
- Business impact analysis to identify systems.
- Have plan for high availability.
- Have a test contingency plan.
- metrics | a. recovery time objective(time to online) | b. recovery point objective(record lost?).

## 06. Data classification policy.
- Defines sensitive data and how to handle it.
#### What you need to do?
- Secret: password, account number, PHI(personal health information), PII(personal identifiable information), SSN(social security number). | column/row based encryption.
- Internal: internal processes and practices. | Full data encryption(FDE) or Transparent data encryption(TDE)
- Public: Job description, Anything posted on socials

## 07. Identify and access management(IAM).
- Has to do with how users are added and removed and how privileges area assigned.
- Includes password policy
#### What to do?
- All accounts should be management approved.
- All accounts should be identifiable to a specific user. Don't share accounts.
- Use single sign on wherever possible and track where not possible.
- Use MFA(Authy) for any privileged systems that support it(eg. google cloud, O365, AWS).
### Least Privilege(Policy under IAM).
- Employees should never have access to data unless they are specifically working on a project that requires it.
- Employees should only ever have access to data that is relevant to their job function. For example, engineers need not to have access to financial or HR data.
- Only data that is explicitly intended to be public and accessed without authentication should ever be accessed without authentication.
- For systems that are public(eg. blog), there are explicitly designated people that may post information.
### Logging In
- It is acceptable to use password managers.
- Passwords should be: more than 9 characters and use special characters, logging history should be available to the user.
- System should provide lockout after <=10 failed attempts.
- Sessions must expire after <= 30 minutes.
#### Other things you need to do.
- Document provisioning approval process.
- Deprovision process able to do it in two hours.
- Audit users monthly.

## 08. Incident Response Policy.
- Defines parameters around how to respond in case of an incident.
#### What you need to do?
- Track incident.
- Process Handling | a. Report to security officer. | b. need a basic data.
- Do not distribute information.
- Notification by security officer.
- Response team will be trained.

## 09. Network Security Policy.
- Defines expectations around network security controls.
#### What you need to do?
- Network segmentation.
- Restrict ports.
- Remote access requires second factor.
- Any network connections to 3rd parties through security.
- Wireless networks secured.
- External ports other than 80,443
- Vulnerability scanning.
- Use TLS(ssl network level security)

## 10. Partner Security Policy.
- To be secure, we need to make sure our partners are also secure.
#### What you need to do?
- Partner/vendor inventory.
- Vendor management program.
- Vendor access to data must be approved.

## 11. Physical Security Policy.
- Defines how the company will keep data safe at a physical level.
#### What you need to do?
- We use a robust data centers.
- Access to office space.
- Visitors approved and tracked.
- Clean desk.

## 12. The Risk Policy.
- Defines the company's process for handling risk.
#### What you need to do?
- There is a risk program(that means we identify risks and we have a way to track them).
- Risks are tracked in a risk register.
- Active risk identification.
- Periodic security audits.
- General counsel tracks legal risk.

## 13. Systems Security Policy.
- Defines how IT systems are kept secure.
#### What you need to do?
- Build to secure standards (CIS).
- Patch laptops, servers and containers frequently (30 days).
- Patch critical fast (< 48 hours).
- Scan for vulnerabilities.
- Implement security monitoring(central logging)

# E. > Standards and regulations
- Overview of CMMC(CyberSecurity Maturity Model Certification)
  - Federal agencies routinely generate, use, store, and share information that, while not meeting the threshold for classification as national security or atomic energy information, require some level of protection fom unauthorized access  and release.
- Controlled Unclassified Information (CUI):- 
  - CUI is sensitive but unclassified information that is to be protected from pubic disclosure.
   