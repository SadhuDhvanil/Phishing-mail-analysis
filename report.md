Task: Analyze suspicious email samples for phishing characteristics

Tools Used: Manual visual inspection, header analysis (simulated), link inspection (based on screenshots)



📨 Email Sample 1: GitHub Verification (Suspicious)
Sender: GitHub@bigdogdomains.co
Subject: “Please verify your email address”

Observations:

1. The email claims to be from GitHub, but the sender domain is bigdogdomains.co, which is definitely not a GitHub domain (GitHub uses github.com).

2. It’s using the GitHub logo and style to appear authentic, but the email address gives it away.

3. There’s a call-to-action button asking to “Verify email address” — but without hovering or header analysis, I can’t be 100% sure where the link goes. Still, this is a common     phishing trick.

4. No obvious spelling or grammar mistakes, which makes it slightly more convincing.

5. Based on the sender domain, this looks like a phishing attempt, probably trying to harvest GitHub credentials.




📨 Email Sample 2: Google Drive PDF Share (Very Suspicious)
Sender: goog...@protected-download.com
Subject: “has a document for your review”

Observations:

1. The email is vague — doesn’t say who shared the file, what it is, or why it was sent.

2. The sender domain protected-download.com is not related to Google. A legit Google Drive share would come from drive-shares-noreply@google.com or similar.

3. There’s a PDF icon and a “Click Here” link, but we don’t know where it actually goes (big red flag). That PDF could contain malware smaples which could affect my system
   immidiately.

6. The message lacks context and personalization, which is common in mass phishing attempts.

7. Feels rushed and generic, likely meant to trick people into clicking without thinking.


✅ Summary / Comparison Table

| Indicator              | GitHub Email | Google Email |
|------------------------|--------------|---------------|
| Spoofed sender domain  | ✅✅          | ✅✅           |
| Urgent call to action  | ✅✅          | ✅✅           |
| Suspicious/masked link | Possibly ✅   | ✅✅           |
| Branding misuse        | ✅ (GitHub)   | ✅ (Google)    |
| Context missing        | ❌            | ✅✅           |
| Clear phishing signs   | ✅✅✅         | ✅✅✅          |


If I got these in my inbox, I would definitely report them as phishing and not click on anything. Always check sender domains and hover over links before clicking.


