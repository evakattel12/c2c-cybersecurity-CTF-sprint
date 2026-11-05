10/14/26:
- What I asked: Help me classify each scenario as a Confidentiality, Integrity, or Availability failure by role-playing as a threat-model walkthrough for cybersecurity using a shared Google Drive
- What the Assistant produced: A shared Google Drive scenario with the CIA failures noted down, threats, and the model assumption.
- Fixed/Rejected: Added in the individual parts of the triad in my learned response in m1.md.
- Verified: Identifying the CIA triad risks from memory on certain softwares.

10/18/26:
- What I asked: Attempting to open up the file - in Bandit 2, provided cat - and cat -- as examples.
- What the Assistant produced: What could the path possibly be?
- Fixed/Rejected: Looked back at files displayed through documentation.
- Verified: File directories typically use ./ as a path for file names like -.

10/18/26:
- What I asked: Explanation of hashing vs. encryption vs. encoding with concrete examples.
- What the Assistant produced: A table that listed examples and purposed of item with comparisons at the end describing how some are reversible and some are not.
- Fixed/Rejected: Further slimmed the questions to hashing and salting in order to further understand it better. Also included MFA as a question on how strong passwords and it are needed.
- Verified: Compared it to real world documentation and examples of how hashing, encryption, and encoding works. MFA and strong password sites were used to check how long brute-force hacking or phishing could happen/take.

10/28/26:
- What I asked: Asked how to "find the robots" with a description of the insecure website that was given to me and not understanding where the robots could be found.
- What the Assistant produced: The Assistant stated to look up the robots exclusion protocol and consider paths that site owners have hidden.
- Fixed/Rejected: Used documentation on what the robots exclusion protocol is and it did not provide much, so I dug deeper and found out that bots used something called robots.txt in URLs to access certain points of websites.
- Verified: Used robots.txt at the end of the URL of the insecure website and acquired the flag needed to complete the capture-the-flag level on picoCTF.