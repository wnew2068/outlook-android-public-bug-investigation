Outlook Android NAA Token Issue — Public Investigation

An independent, evidence-based investigation of "Officedev/office-js Issue #6864" (https://github.com/OfficeDev/office-js/issues/6864).

Status: Initial investigation. No root cause or fix has been independently confirmed.

1. Problem Summary

The upstream issue reports that Outlook for Android fails to silently broker a Nested App Authentication (NAA) token in a GCC High environment. The report mentions the error:

"InteractionRequiredAuthError: 0"

The original GitHub issue is the authoritative source for the reporter's environment, symptoms, and subsequent updates.

This project does not claim that all Outlook Android users or all GCC High tenants are affected.

2. Project Objectives

- Review the publicly available issue details and technical documentation.
- Identify the information required to reproduce the reported behavior.
- Investigate possible causes using evidence rather than assumptions.
- Document reproducible findings and safe diagnostic steps.
- Share useful findings with the upstream maintainers.

3. Current Investigation Status

Item| Status
Original issue identified| Complete
Independent reproduction| Not yet documented
Root cause confirmed| No
Verified code fix| No
Upstream contribution| Pending further investigation

Issue labels, comments, assignments, and status may change. Always check the original issue for the latest information.

4. Investigation Plan

- [ ] Read the current issue description and maintainer comments.
- [ ] Identify the relevant Outlook Android version and Android version.
- [ ] Understand the reported GCC High environment and authentication configuration.
- [ ] Review the official NAA documentation.
- [ ] Collect sanitized diagnostic information in an authorized test environment.
- [ ] Separate verified observations from hypotheses.
- [ ] Share reproducible findings with the upstream maintainers.
- [ ] Propose a code change only if evidence supports one.

5. Official References

- Original issue: https://github.com/OfficeDev/office-js/issues/6864
- Office.js repository: https://github.com/OfficeDev/office-js
- Office Add-ins documentation: https://learn.microsoft.com/en-us/office/dev/add-ins/
- Nested App Authentication documentation: https://learn.microsoft.com/en-us/office/dev/add-ins/develop/enable-nested-app-authentication-in-your-add-in

6. Security and Privacy

Never publish access tokens, passwords, cookies, private tenant information, email addresses, or other sensitive data.

Only investigate accounts and environments you are authorized to access. Remove secrets and personally identifiable information from logs before sharing them.

7. Contribution Guidelines

Contributions should include:

- A clear description of the observation.
- Reproduction steps, when available.
- Expected and actual behavior.
- Sanitized logs or other supporting evidence.
- Relevant documentation or code references.

Do not describe a suspected cause as confirmed without reproducible evidence. Do not claim the issue is fixed unless a fix has been verified.

8. Project Disclaimer

This is an independent community investigation. It is not an official Microsoft project and is not affiliated with or endorsed by Microsoft.

The original OfficeDev issue and repository remain the authoritative sources for upstream discussion and code changes.

9. License

No open-source license has been selected for this project yet. Until a license is added, do not assume that the repository's contents are licensed for unrestricted reuse.
