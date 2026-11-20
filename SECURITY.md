# Security policy

Neurologyca Technologies Ltd. ("Neurologyca", "we") builds software that processes face and voice data. We take reports about its security seriously and thank the researchers who report issues to us privately.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions or pull requests.**

Email **security@neurologyca.com** with:

- the affected product and version (for example `@neurologyca/capture@x.y.z`, DevLab, or the Engine API);
- a description of the issue and its impact;
- the steps to reproduce it, or a proof of concept;
- any logs, requests or screenshots that help us confirm it. Remove personal data, face or voice data, credentials and tokens first; describe them instead.

You can also report it privately on GitHub, with the **Report a vulnerability** button in the **Security** tab of the affected repository.

We will acknowledge your report within **5 business days**, keep you informed while we investigate, and tell you when it is fixed.

Please keep the details confidential until we release a fix. We aim to fix confirmed issues within 90 days. If we need longer, we will explain why and agree on a disclosure date with you.

We do not run a bug bounty and do not pay for reports. With your permission, we will credit you when we publish the fix.

## Scope

- The npm packages published under [`@neurologyca`](https://www.npmjs.com/org/neurologyca): `@neurologyca/capture`, `@neurologyca/capture-server` and `@neurologyca/kodec`. Test them in your own environment.
- [DevLab](https://devlab.neurologyca.com) at `devlab.neurologyca.com`, including its documentation, account and API paths.
- The Neurologyca Engine API, when you call it with the API key of your own DevLab organization, directly or through `@neurologyca/capture-server` running on your own infrastructure.
- The code and configuration in the public repositories of this organization.

Only the systems listed above are in scope. Out of scope:

- any other Neurologyca host, including test, development and preview environments, and internal administration services;
- data of other DevLab organizations or their users;
- websites, applications and servers of our customers, even when they use our SDKs;
- services of our providers, such as cloud hosting, AI model providers, email, CDNs, model downloads, npm and GitHub;
- denial-of-service and load testing;
- social engineering of our staff or customers, and physical attacks;
- output of automated scanners without a working proof of concept, and missing security headers without a demonstrated impact;
- issues that require an already compromised device or browser.

## Testing guidelines

- Test only with your own DevLab account and your own data. Do not try to access data that belongs to anyone else.
- Never use other people's face or voice data in your tests. Use synthetic data or recordings of yourself.
- If you see personal data of anyone else, stop and contact us immediately.
- Do only what is needed to confirm the issue. Do not use it to reach other systems, to keep access, or to slow down or interrupt our services.

## Safe harbor

We consider security research carried out in good faith and in line with this policy to be authorized. You remain responsible for complying with the laws that apply to you. If you follow this policy:

- We will not take legal action against you, or report you to law enforcement, for that research. We may still have to notify customers or authorities about an incident, or answer a lawful request. If so, we will not name you without your consent unless the law requires it.
- We will not treat it as a breach of our [Terms of Service](https://devlab.neurologyca.com/legal/terms/) or [SDK License](https://devlab.neurologyca.com/legal/sdk-license/). This policy is our written permission to reverse engineer our software and to get around its security measures, only as far as that research needs. This permission does not extend to our [Acceptable Use Policy](https://devlab.neurologyca.com/legal/aup/), which always applies, or to using another person's account or credentials.
- We consider it authorized under anti-hacking laws, such as the U.S. Computer Fraud and Abuse Act, and we will not bring a claim against you for getting around the technical protections of our own software, for example under the U.S. Digital Millennium Copyright Act. We cannot give this permission for third-party components.
- If a third party takes legal action against you for research that followed this policy, we will state, if you ask us, that your research was authorized under this policy.

Protecting the people whose data we process comes first. This safe harbor does not cover research in which you:

- deliberately access, copy, change or delete data that is not yours;
- continue testing after you have seen data that belongs to someone else;
- keep, share or use such data for any purpose;
- knowingly disrupt our services or damage data for other users.

If you see someone else's data by accident, you are still covered if you stop immediately, do not save, copy or share it, delete at once anything that was stored automatically (for example in logs or screenshots), and tell us in your report what kind of data you saw. Describe the data; do not send it to us.

This safe harbor covers only systems under our control and in scope above. We cannot authorize testing of our customers' or providers' systems, and this policy does not bind them. If you are unsure whether something is allowed, ask us at security@neurologyca.com before you continue.

## Supported versions

Security fixes are released for the latest published version of each package, unless the package's own SECURITY.md says otherwise. Before reporting, please check that the issue still occurs with the latest version.

Some repositories have their own SECURITY.md with package-specific details. The testing guidelines and safe harbor on this page apply to them too.

## Other contacts

- Technical support (not security): [support@neurologyca.com](mailto:support@neurologyca.com)
- Legal and privacy enquiries: [info@neurologyca.com](mailto:info@neurologyca.com)
- How we process personal data: [Privacy Notice](https://devlab.neurologyca.com/legal/privacy/) and [Data Processing Addendum](https://devlab.neurologyca.com/legal/dpa/)

Last updated: 2026-11-20. We may change this policy; the version published when you did the research applies.
