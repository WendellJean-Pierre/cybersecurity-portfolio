# MFA Remediation Case Study

**Prepared by:** Wendell Jean-Pierre  
**Organization:** Clearview Community Health (Fictional)  
**Project Type:** Simulated GRC Case Study  
**Finding ID:** C-01  
**Status:** Open

## 1. Security Finding

Multifactor authentication (MFA) is not consistently enforced across applicable user accounts in the fictional organization.

This finding is based on an assumed security control gap. No real organization or authentication system was tested.

## 2. Business and Security Risk

Without consistent MFA enforcement, an attacker who obtains a user's password may be able to access organizational systems and sensitive patient information.

Potential consequences include:
- Unauthorized access to electronic health records.
- Exposure of sensitive patient information.
- Account compromise and operational disruption.
- Increased compliance and regulatory risk.

## 3. Simulated Evidence

**Evidence reference:** MFA-E01  
**Evidence type:** Hypothetical authentication policy review  
**Observation:** The fictional policy does not require MFA for every applicable user account.  
**Evidence status:** Scenario description only. No actual policy document or test results have been collected.

## 4. Recommended Corrective Actions

1. Identify all accounts and applications requiring MFA.
2. Require MFA for applicable workforce, administrative, and remote-access accounts.
3. Prefer phishing-resistant authentication methods where supported.
4. Document and approve any necessary exceptions.
5. Train users on MFA enrollment and suspicious authentication requests.
6. Monitor authentication logs and investigate bypass attempts.

## 5. Proposed Risk Ownership

**Proposed owner:** IT Manager  
**Supporting role:** Privacy Officer  
**Current status:** Open

These roles are hypothetical assignments for this simulated organization.

## 6. Verification Plan

The following checks would be performed in an authorized test environment:

1. Review the MFA enforcement policy and configuration.
2. Verify that applicable test accounts are enrolled in MFA.
3. Attempt a test sign-in to confirm that an additional authentication factor is required.
4. Review simulated authentication logs for enforcement and exceptions.
5. Document test results and any remaining weaknesses.

**Verification status:** Not performed.

## 7. Remediation Decision

**Finding status:** Open  
**Corrective action:** Proposed, not implemented  
**Evidence collected:** None  
**Verification completed:** No  
**Closure approved:** No

The finding must remain Open until corrective actions have been implemented and supporting verification evidence has been reviewed.

## 8. Next Steps

1. Create a fictional sample authentication policy.
2. Document the assumed MFA control gap.
3. Prepare an authorized test scenario.
4. Record simulated test results once the exercise is performed.
5. Update the remediation tracker to reflect verified progress.

## Disclaimer

This document is part of an educational cybersecurity governance, risk, and compliance simulation. All findings, personnel, and organizational details are fictional. No real patient information, employer data, security configurations, or authentication logs were accessed or tested.
