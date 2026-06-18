# SENTINEL-IQ

Problem Statement

The challenge aims to design a privacy-first, risk-based Identity Trust framework that continuously validates customer and enterprise identities across digital channels. The solution should be capable of detecting high-risk events such as anomalous behavior, new device usage, suspicious onboarding or account recovery attempts, and misuse of privileged access. It should trigger real-time verification only when risk levels are elevated.
The expected outcomes include a reduction in account takeover incidents, KYC fraud, and insider misuse, while ensuring secure, compliant, and friction-optimized digital access. The proposed solution should be scalable across multiple banking channels as user and transaction volumes grow.
We strongly believe that collaboration with your esteemed institution will bring significant academic depth, research rigor, and innovative student participation to this initiative.


Understanding of problem (In our own words)


*
Today, most banking applications verify a user's identity only during login. Once a user is authenticated, the session is generally trusted until they log out. This creates a major security gap because if someone hijacks an active session, gains access to a trusted device, or performs suspicious activities after login, traditional authentication mechanisms may not detect it.

Another challenge is that important security signals such as device information, user behavior, login patterns, location, and transaction activity are often analyzed separately instead of together. As a result, banks may detect unusual activity but fail to recognize the complete risk behind it. Many existing fraud detection systems also depend on predefined rules, which makes it difficult to identify new attack patterns or sophisticated account takeover attempts.

We believe identity should not be verified just once it should be evaluated throughout the entire banking session. SENTINEL-IQ addresses this by continuously analyzing multiple trust signals to generate a dynamic trust score. When the system detects higher risk, it can trigger additional verification or alert the bank before fraudulent actions are completed, improving both security and the customer experience.

