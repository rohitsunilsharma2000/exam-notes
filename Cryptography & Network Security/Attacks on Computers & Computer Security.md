#  1. Attacks on Computers & Computer Security

[MCQ Questions]()

### 1. What is DNS spoofing?

- **English:** DNS spoofing is a type of cyber attack where a hacker intercepts and alters DNS (Domain Name System) queries.  
  **Translation:** DNS spoofing মানে এমন একধরনের সাইবার হামলা, যেটাতে কোনো হ্যাকার DNS (ডোমেইন নাম সিস্টেম) রিকোয়েস্ট ধরেই, ওটা বদলে দেয়।

- **English:** It allows them to redirect users to fake websites or servers, potentially stealing sensitive information or installing malware.  
  **Translation:** এর ফলে হ্যাকাররা ইউজারদেরকে জাল ওয়েবসাইট বা সার্ভারে পাঠাতে পারে, যার ফলে গোপন তথ্য চুরি বা ম্যালওয়্যার ঢোকানোর ঝুঁকি থাকে।

- **English:** DNS spoofing can be done through various means, including:  
  **Translation:** DNS spoofing নানা রকম উপায়ে করা যায়, যেমন:

  - **English:** DNS cache poisoning: Hackers inject fake DNS records into a DNS cache, which is then served to users.  
    **Translation:** DNS ক্যাশ পোয়জনিং: হ্যাকাররা DNS ক্যাশে মিথ্যা রেকর্ড ঢুকায়, যেটা পরে ইউজারদেরকে দেখানো হয়।
  
  - **English:** DNS tunneling: Hackers use DNS queries to tunnel through firewalls and gain unauthorized access.  
    **Translation:** DNS টানেলিং: হ্যাকাররা DNS রিকোয়েস্ট ব্যবহার করে ফায়ারওয়ালের ভেদ করে অননুমোদিত ঢোকা যায়।
  
  - **English:** Man-in-the-middle (MITM) attacks: Hackers intercept DNS queries and alter them to redirect users to fake websites.  
    **Translation:** ম্যান-ইন-দ্য-মিডল (MITM) আক্রমণ: হ্যাকাররা DNS রিকোয়েস্ট ধরে ও বদলে দেয়, যাতে ইউজাররা জাল সাইটে চলে যায়।

---

### 2. What are the principles of security?

- **English:** The principles of security are the fundamental concepts that guide the design and implementation of secure systems.  
  **Translation:** সিকিউরিটির মূল নীতি মানে সেসব বেসিক কথা, যেগুলো সিকিউর সিস্টেম বানানোর সময় মাথায় রাখা হয়।

- **English:** The three main principles of security are:  
  **Translation:** এর তিনটা মূল নীতি হলো:

  - **English:** Confidentiality: Protecting sensitive information from unauthorized access.  
    **Translation:** কনফিডেনশিয়ালিটি: গোপন তথ্যকে অননুমোদিত লোক থেকে রক্ষা করা।
  
  - **English:** Integrity: Ensuring that data is accurate, complete, and not modified without authorization.  
    **Translation:** ইনটিগ্রিটি: ডেটা সঠিক, পুরাপুরি ও অননুমোদিতভাবে বদলানো না হয়, এটার যত্ন নেওয়া।
  
  - **English:** Availability: Ensuring that systems and data are accessible and usable when needed.  
    **Translation:** অ্যাভেইলেবিলিটি: যখন দরকার তখন সিস্টেম ও ডেটা ইউজ করা যায়, এটার খেয়াল রাখা।

---

### 3. What is a DoS attack?

- **English:** A Denial of Service (DoS) attack is a type of cyber attack where an attacker attempts to make a computer or network resource unavailable by overwhelming it with traffic or requests.  
  **Translation:** DoS আক্রমণ মানে এমন একধরনের সাইবার হামলা, যেখানে হ্যাকার একটা কম্পিউটার বা নেটওয়ার্ককে অতিরিক্ত ট্রাফিক বা রিকোয়েস্ট দিয়ে ব্যস্ত করে ফেলে, যাতে সেটা ঠিকমতো কাজ না করে।

- **English:** This can be done through various means, including:  
  **Translation:** এটা নানা উপায়ে করা যায়, যেমন:

  - **English:** Flooding: Sending a large amount of traffic to a network or system.  
    **Translation:** ফ্লাডিং: অনেক বেশি ট্রাফিক পাঠিয়ে নেটওয়ার্ক বা সিস্টেম ব্যস্ত করা।
  
  - **English:** Buffer overflow attacks: Sending more data than a system can handle, causing it to crash.  
    **Translation:** বাফার ওভারফ্লো আক্রমণ: সিস্টেমের ক্ষমতার বাইরে ডেটা পাঠিয়ে সেটাকে ক্র্যাশ করানো।
  
  - **English:** Application-layer attacks: Targeting specific applications or services to make them unavailable.  
    **Translation:** অ্যাপ্লিকেশন-লেয়ার আক্রমণ: নির্দিষ্ট অ্যাপ বা সার্ভিসকে লক্ষ করে সেটাকে কাজ করতে না দেওয়া।

---

### 4. What is IP sniffing and IP spoofing?


| **Concept**    | **Additional Point (English)**                                                                              | **Additional Point (Burdwan Bengali)**                                                         |
|----------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| **IP Sniffing**    | It is used for network diagnostics and troubleshooting.                                                 | ইটা নেটওয়ার্ক ডায়াগনস্টিক্স ও ট্রাবলশুটিংয়ের কাজে লাগে।                                         |
| **IP Sniffing**    | It can capture sensitive data such as passwords or session cookies during transmission.                   | ইটা ট্রান্সমিশনের সময় পাসওয়ার্ড বা সেশন কুকিজের মতো গোপন তথ্যও আটকাতে পারে।                  |
| **IP Spoofing**    | It is used to bypass IP-based authentication mechanisms by faking the source IP address.                   | ইটা আইপি ভিত্তিক অথেন্টিকেশন বাইপাস করতে, মিথ্যা সোর্স আইপি ঠিকানা ব্যবহার করে করা হয়।              |
| **IP Spoofing**    | It is often employed in DDoS attacks to hide the true origin of the malicious traffic.                     | ইটা ডিডস আক্রমণে ম্যালিসিয়াস ট্রাফিকের আসল উত্স লুকানোর জন্য প্রায়ই ব্যবহার করা হয়।              |


---

### 5. What are the key principles of security?

- **English:** Same as question 2: Confidentiality, Integrity, and Availability (CIA triad).  
  **Translation:** ঠিক প্রশ্ন 2 এর মতো: কনফিডেনশিয়ালিটি, ইনটিগ্রিটি, এবং অ্যাভেইলেবিলিটি (CIA ত্রিমূখ)।

---

### 6. What is the basic difference between a worm and a virus?



| **Characteristic**               | **Worm**                                                                                                                                                                   | **Virus**                                                                                                                                                                   |
|----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Basic Nature**                 | **English:** A self-replicating malware that spreads automatically without human interaction. <br> **Bengali:** ওয়ার্ম নিজে থেকেই কপি হয়ে স্বয়ংক্রিয়ভাবে ছড়িয়ে পড়ে। | **English:** A malware that requires a host program and user interaction to replicate. <br> **Bengali:** ভাইরাস ছড়িয়ে দিতে হোস্ট প্রোগ্রাম ও ইউজারের হস্তক্ষেপ লাগে। |
| **Spreading Mechanism**          | **English:** Spreads via network vulnerabilities without needing any external trigger. <br> **Bengali:** নেটওয়ার্কের দুর্বলতা ব্যবহার করে ছড়িয়ে পড়ে, কোন বাইরের ট্রিগার লাগে না।   | **English:** Spreads through infected files, email attachments, or downloads when executed. <br> **Bengali:** সংক্রমিত ফাইল, ইমেইল এটাচমেন্ট বা ডাউনলোড চালানোর মাধ্যমে ছড়িয়ে পড়ে।  |
| **Human Interaction Requirement**| **English:** Propagates automatically without user action. <br> **Bengali:** ছড়িয়ে পড়তে ইউজারের কোনো কাজ লাগে না।                                                            | **English:** Requires user action (e.g., opening a file) to activate and spread. <br> **Bengali:** সক্রিয় হতে ও ছড়িয়ে পড়তে ইউজারের দ্বারা সংক্রমিত ফাইল খোলা বা প্রোগ্রাম চালানো লাগে।  |
| **Host Dependency** *(Extra)*    | **English:** Independent; does not need to attach itself to any host file. <br> **Bengali:** নিজে থেকেই চলে; কোনো হোস্ট ফাইলে নিজেকে লাগায় না।                                 | **English:** Dependent; attaches itself to a host file or program to replicate. <br> **Bengali:** হোস্ট ফাইল বা প্রোগ্রামের সাথে যুক্ত হয়ে ছড়িয়ে পড়ে।                         |
| **Network Impact** *(Extra)*     | **English:** Can cause widespread network congestion and damage due to rapid, autonomous spreading. <br> **Bengali:** দ্রুত ছড়িয়ে পড়ার কারণে নেটওয়ার্কে ব্যাপক জ্যাম ও ক্ষতি করতে পারে। | **English:** Generally affects individual systems and spreads more slowly, impacting local performance. <br> **Bengali:** সাধারণত ব্যক্তিগত সিস্টেমে প্রভাব ফেলে এবং ধীরে ছড়িয়ে পড়ে।  |


---

### 7. What is a brute-force attack?

- **English:** A brute-force attack involves systematically trying all possible combinations of passwords, keys, or encryption algorithms to gain unauthorized access.  
  **Translation:** ব্রুট-ফোর্স আক্রমণে সিস্টেমেটিকভাবে সব সম্ভাব্য পাসওয়ার্ড, কী বা এনক্রিপশন কম্বিনেশন চেষ্টা করা হয়, যাতে অননুমোদিত ঢোকার সুযোগ পাওয়া যায়।

- **English:** This can be done through various means, including:  
  **Translation:** এটা নানা রকম উপায়ে করা যায়, যেমন:

  - **English:** Dictionary attacks: Using a list of words to guess passwords.  
    **Translation:** ডিকশনারি আক্রমণ: শব্দের একটা তালিকা থেকে পাসওয়ার্ড অনুমান করা।
  
  - **English:** Rainbow table attacks: Using precomputed tables of hash values to crack passwords.  
    **Translation:** রেইনবো টেবিল আক্রমণ: আগে থেকে গণনা করা হ্যাশ টেবিল দিয়ে পাসওয়ার্ড ভাঙা।
  
  - **English:** Exhaustive key searches: Trying all possible encryption keys to decrypt data.  
    **Translation:** এক্সহস্টিভ কী সার্চ: সব সম্ভাব্য এনক্রিপশন কী চেষ্টা করে ডেটা ডিক্রিপ্ট করা।

---

### 8. What are the basic components of computer security?

- **English:** The basic components of computer security include:  
  **Translation:** কম্পিউটার সিকিউরিটির বেসিক উপাদানগুলো হলো:

  - **English:** Hardware: The physical components of a system, such as servers, workstations, and network devices.  
    **Translation:** হার্ডওয়্যার: সিস্টেমের আসল যন্ত্রপাতি, যেমন সার্ভার, ওয়ার্কস্টেশন, ও নেটওয়ার্ক ডিভাইস।
  
  - **English:** Software: The programs and operating systems that run on hardware.  
    **Translation:** সফটওয়্যার: যেসব প্রোগ্রাম ও অপারেটিং সিস্টেম হার্ডওয়্যারে চলে।
  
  - **English:** Data: The information stored on or transmitted by a system.  
    **Translation:** ডেটা: সিস্টেমে সংরক্ষিত বা প্রেরিত তথ্য।
  
  - **English:** Human factors: The people who use and manage a system.  
    **Translation:** হিউম্যান ফ্যাক্টর: যাঁরা সিস্টেম ব্যবহার ও পরিচালনা করেন।

---

### 9. What is a threat and what are the categories of threats?

- **English:** A threat is a potential occurrence that could compromise security.  
  **Translation:** হুমকি মানে এমন কোনো সম্ভাব্য ঘটনা, যেটা সিকিউরিটি কমিয়ে দিতে পারে।

- **English:** Threat categories include:  
  **Translation:** হুমকির ধরনগুলো হলো:

  - **English:** Human threats: Unauthorized access, theft, or sabotage by individuals.  
    **Translation:** মানবিক হুমকি: কোনো ব্যক্তির দ্বারা অননুমোদিত ঢোকা, চুরি বা বিধ্বংস করা।
  
  - **English:** Natural threats: Natural disasters, such as earthquakes or hurricanes.  
    **Translation:** প্রাকৃতিক হুমকি: ভূমিকম্প, ঘূর্ণিঝড়ের মতো প্রাকৃতিক দুর্যোগ।
  
  - **English:** Environmental threats: Power failures, equipment failures, or other environmental factors.  
    **Translation:** পরিবেশগত হুমকি: বিদ্যুৎ যায়গা ফাটানো, যন্ত্রপাতি ভাঙ্গা বা অন্য পরিবেশগত সমস্যা।
  
  - **English:** Technological threats: Malware, hacking, or other technological vulnerabilities.  
    **Translation:** টেকনোলজিক্যাল হুমকি: ম্যালওয়্যার, হ্যাকিং বা অন্য কোনো টেকনিক্যাল দুর্বলতা।

---

### 10. What are the security approaches?

- **English:** Security approaches include:  
  **Translation:** সিকিউরিটি মোকাবেলার উপায়গুলো হলো:

  - **English:** Preventive measures: Implementing security controls to prevent attacks, such as firewalls or access controls.  
    **Translation:** প্রিভেন্টিভ ব্যবস্থা: ফায়ারওয়াল বা অ্যাক্সেস কন্ট্রোলের মতো সিকিউরিটি নিয়ন্ত্রণ লাগিয়ে আক্রমণ থামানো।
  
  - **English:** Detective measures: Implementing security controls to detect attacks, such as intrusion detection systems or logging.  
    **Translation:** ডিটেকটিভ ব্যবস্থা: অনুপ্রবেশ শনাক্ত করার সিস্টেম বা লগিং দিয়ে আক্রমণ চিনে ফেলা।
  
  - **English:** Corrective measures: Implementing security controls to correct or mitigate the effects of an attack, such as backups or incident response plans.  
    **Translation:** করেকটিভ ব্যবস্থা: ব্যাকআপ বা ইনসিডেন্ট রেসপন্স প্ল্যানের মাধ্যমে আক্রমণের প্রভাব কমানো।

---

### 11. What do you mean by computer security and what are its goals?

- **English:** Computer security refers to the protection of computer systems, networks, and data from unauthorized access, use, disclosure, disruption, modification, or destruction.  
  **Translation:** কম্পিউটার সিকিউরিটি মানে কম্পিউটার সিস্টেম, নেটওয়ার্ক ও ডেটাকে অননুমোদিত ঢোকা, ব্যবহার, প্রকাশ, বিঘ্ন, পরিবর্তন বা ধ্বংস থেকে রক্ষা করা।

- **English:** The goals of computer security are to ensure Confidentiality, Integrity, and Availability (CIA triad).  
  **Translation:** কম্পিউটার সিকিউরিটির লক্ষ্য হলো কনফিডেনশিয়ালিটি, ইনটিগ্রিটি ও অ্যাভেইলেবিলিটি (CIA ত্রিমূখ) নিশ্চিত করা।

---

### 12. What do you mean by interruption?

- **English:** Interruption refers to any event that disrupts or halts the normal functioning of a computer system or network.  
  **Translation:** ব্যাঘাত মানে এমন কোনো ঘটনা, যেটা কম্পিউটার সিস্টেম বা নেটওয়ার্কের স্বাভাবিক কাজকর্ম থামিয়ে দেয়।

---

### 13. What is availability?

- **English:** Availability refers to the ability of a computer system or network to provide services and data when needed.  
  **Translation:** অ্যাভেইলেবিলিটি মানে যখন দরকার তখন সিস্টেম বা নেটওয়ার্ক সার্ভিস ও ডেটা দিতে পারার ক্ষমতা।

---

### 14. What are the different types of attacks on computer and network systems?

- **English:** Types of attacks include:  
  **Translation:** কম্পিউটার ও নেটওয়ার্কে আক্রমণের ধরনগুলো হলো:

  - **English:** Active attacks: Direct interference with a system or network, such as malware or DoS attacks.  
    **Translation:** অ্যাকটিভ আক্রমণ: সিস্টেম বা নেটওয়ার্কে সরাসরি হস্তক্ষেপ, যেমন ম্যালওয়্যার বা DoS আক্রমণ।
  
  - **English:** Passive attacks: Monitoring or eavesdropping on a system or network without interfering with it.  
    **Translation:** প্যাসিভ আক্রমণ: সিস্টেম বা নেটওয়ার্কে হস্তক্ষেপ না করে শুধু নজরদারি বা শুনে ফেলা।
  
  - **English:** Insider attacks: Attacks by individuals with authorized access to a system or network.  
    **Translation:** ইনসাইডার আক্রমণ: যারা সিস্টেম বা নেটওয়ার্কে অনুমোদিতভাবে ঢোকার সুযোগ পায়, তাঁদের দিয়া করা আক্রমণ।
  
  - **English:** Physical attacks: Attacks that involve physical access to a system or network, such as theft or sabotage.  
    **Translation:** ফিজিক্যাল আক্রমণ: সিস্টেম বা নেটওয়ার্কে সরাসরি শারীরিকভাবে ঢুকে চুরি বা বিধ্বংস করার আক্রমণ।

---

### 15. Distinguish between phishing and pharming. Why is it easier to fall prey to pharming than phishing?



| **Characteristic**         | **Phishing**                                                                                                                                                                                                                                                                               | **Pharming**                                                                                                                                                                                                                                                                                  |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Basic Definition**       | **English:** Phishing is a fraudulent attempt to obtain sensitive information by disguising as a trustworthy entity in electronic communications. <br> **Bengali:** ফিশিং মানে, বিশ্বাসযোগ্য প্রতিষ্ঠান হিসেবে প্রতারণা করে ইউজারের গোপন তথ্য চুরি করা।                                          | **English:** Pharming is the redirection of website traffic to a fake website without the user's consent, often by exploiting DNS vulnerabilities. <br> **Bengali:** ফার্মিং মানে, ইউজারের অনুমতি ছাড়াই DNS দুর্বলতা কাজে লাগিয়ে আসল সাইটের বদলে জাল সাইটে পাঠানো।                           |
| **Method of Attack**       | **English:** Uses deceptive emails, messages, or fake websites to lure users. <br> **Bengali:** মিথ্যা ইমেইল, বার্তা বা জাল সাইট ব্যবহার করে ইউজারদের ফাঁদে ফেলা হয়।                                                                                                                                       | **English:** Manipulates DNS settings or host files to automatically redirect users without their awareness. <br> **Bengali:** DNS সেটিংস বা হোস্ট ফাইল বদলে স্বয়ংক্রিয়ভাবে ইউজারদেরকে জাল সাইটে পাঠানো হয়।                                                                           |
| **User Interaction**       | **English:** Requires users to click on links and input personal information. <br> **Bengali:** ইউজারদের লিঙ্কে ক্লিক করে ও ব্যক্তিগত তথ্য দিতে হয়।                                                                                                                                                        | **English:** Occurs without any explicit user action; redirection happens automatically. <br> **Bengali:** ইউজারের কোনো সরাসরি ক্রিয়াকলাপ ছাড়াই, স্বয়ংক্রিয়ভাবে রিডিরেকশন হয়।                                                                                                        |
| **Detection & Awareness**  | **English:** Often detected by spotting suspicious email addresses, unusual URLs, or grammatical errors in messages. <br> **Bengali:** সন্দেহজনক ইমেইল, অস্বাভাবিক ইউআরএল বা বার্তায় ভুল দেখে ফিশিং শনাক্ত করা যায়।                                                                                     | **English:** Harder to detect because users see familiar URLs even though they are being redirected. <br> **Bengali:** ফার্মিং শনাক্ত করা কঠিন, কারণ ইউজাররা দেখতে পায় আসল সাইটের ইউআরএল, অথচ তারা জাল সাইটে চলে যায়।                                                                     |
| **Additional Point 1**     | **English:** Relies on social engineering and user errors, making it preventable with proper user education and caution. <br> **Bengali:** ফিশিংতে সোশ্যাল ইঞ্জিনিয়ারিং ও ইউজারের ভুলের ওপর নির্ভর করা হয়, তাই সঠিক শিক্ষা ও সতর্কতা থাকলে এটার প্রতিরোধ করা যায়।                                                         | **English:** Exploits technical vulnerabilities, impacting many users at once without any action on their part, hence it can be more widespread. <br> **Bengali:** ফার্মিং টেকনিক্যাল দুর্বলতা কাজে লাগায়, যা অনেক ইউজারকে একসাথে ক্ষতিগ্রস্ত করে, ফলে এটার ব্যাপকতা বেড়ে যায়।                           |
| **Additional Point 2**     | **English:** Users can safeguard themselves by verifying email sources and checking website certificates before sharing sensitive data. <br> **Bengali:** ইউজাররা ইমেইল উৎস ও সাইটের সার্টিফিকেট যাচাই করে নিজেরা রক্ষা নিতে পারে।                                                                                 | **English:** Pharming is harder to combat because it bypasses user-level checks and demands robust network-level security measures, making it easier for attackers to exploit. <br> **Bengali:** ফার্মিং মোকাবেলা করা কঠিন, কারণ এটা ইউজার লেভেলের চেক এড়িয়ে যায় ও শক্তিশালী নেটওয়ার্ক সিকিউরিটি লাগে, তাই শিকার হওয়া সহজ। |


---

### 16. What is the idea behind a man-in-the-middle attack?

- **English:** A man-in-the-middle (MITM) attack involves intercepting and altering communication between two parties, often to steal sensitive information or inject malware.  
  **Translation:** ম্যান-ইন-দ্য-মিডল (MITM) আক্রমণের ধারণা হলো, দুই পক্ষের মধ্যে যোগাযোগ আটক করে ও বদলে দিয়ে গোপন তথ্য চুরি করা বা ম্যালওয়্যার ঢোকানো।

---

### 17. Distinguish between active attacks and passive attacks.


| **Characteristic**              | **Active Attacks**                                                                                                                                                                                                                                                                                           | **Passive Attacks**                                                                                                                                                                                                                                                                                           |
|---------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Basic Definition**            | **English:** Involve direct modification, disruption, or injection of data into communications. <br> **Bengali:** অ্যাকটিভ আক্রমণ মানে সরাসরি ডেটা পরিবর্তন, বাধা সৃষ্টি বা ম্যালিসিয়াস কোড ইনজেক্ট করা।                                                                  | **English:** Involve eavesdropping or monitoring data without altering its content. <br> **Bengali:** প্যাসিভ আক্রমণ মানে কোনো ডেটা পরিবর্তন না করে শুধু শুনে বা নজরদারি করা।                                                                  |
| **Method of Operation**         | **English:** Actively inject, modify, or disrupt network traffic. <br> **Bengali:** সরাসরি নেটওয়ার্ক ট্রাফিকে হস্তক্ষেপ করে, ডেটা ইনজেক্ট বা পরিবর্তন করা হয়।                                                                                      | **English:** Simply observe and record the data flow without interference. <br> **Bengali:** শুধু ডেটা প্রবাহ পর্যবেক্ষণ ও রেকর্ড করা হয়, কোন হস্তক্ষেপ ছাড়াই।                                                                               |
| **Detectability**               | **English:** Easier to detect due to noticeable disruptions in normal operations. <br> **Bengali:** সাধারণ কাজকর্মে স্পষ্ট বিঘ্নের কারণে সহজে ধরা পড়ে।                                                                                            | **English:** Stealthy and hard to detect since they leave the data unaltered. <br> **Bengali:** কারণ ডেটায় কোন পরিবর্তন হয় না, তাই এগুলো চুপচাপ হয় ও ধরা পড়তে কঠিন।                                                                    |
| **Impact on System**            | **English:** Can cause immediate damage such as data corruption, loss, or service disruption. <br> **Bengali:** তৎক্ষণাৎ ডেটা ক্ষতি, হারানো বা সার্ভিসে বিঘ্ন ঘটাতে পারে।                                                                               | **English:** Mainly threaten confidentiality by capturing sensitive data without disrupting operations. <br> **Bengali:** মূলত গোপনীয়তা ক্ষতি করে, কারণ তথ্য চুরি করে কিন্তু সিস্টেমের কাজকর্মে সরাসরি প্রভাব ফেলে না।                               |
| **Additional Point 1 (Response Time)**  | **English:** Their abrupt effects demand immediate response and intervention. <br> **Bengali:** হঠাৎ প্রভাবের জন্য তৎক্ষণাৎ প্রতিক্রিয়া ও হস্তক্ষেপ প্রয়োজন।                                                                                            | **English:** They can remain undetected for long periods, delaying incident response. <br> **Bengali:** অনেকক্ষণ ধরা পড়ে না, যার ফলে ঘটনার প্রতি প্রতিক্রিয়া দিতে সময় লাগে।                                                                 |
| **Additional Point 2 (Mitigation & Prevention)** | **English:** Mitigated by employing intrusion prevention systems and active monitoring tools. <br> **Bengali:** ইনট্রুশন প্রিভেনশন সিস্টেম ও সক্রিয় মনিটরিং টুল ব্যবহার করে এদের প্রতিকার করা যায়।                                                               | **English:** Require robust encryption and continuous monitoring to detect covert data leaks. <br> **Bengali:** শক্তিশালী এনক্রিপশন ও ধারাবাহিক নজরদারির মাধ্যমে গোপনে হচ্ছে এমন কার্যকলাপ ধরা পড়ে।                                               |

---

### 18. What is access control? How is it different from availability?


| **Characteristic**         | **Active Attacks**                                                                                                                                                                                                                                                                                         | **Passive Attacks**                                                                                                                                                                                                                                                                                     |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Basic Definition**       | **English:** Active attacks involve direct interference with network communications by modifying, injecting, or disrupting data. <br> **Translation:** অ্যাকটিভ আক্রমণ মানে সরাসরি নেটওয়ার্ক যোগাযোগে হস্তক্ষেপ করে ডেটা বদলানো, ঢোকানো বা ব্যাঘাত ঘটানো।                                              | **English:** Passive attacks involve eavesdropping or monitoring communications without altering them. <br> **Translation:** প্যাসিভ আক্রমণ মানে ডেটা পরিবর্তন না করে শুধু শুনে বা নজরদারি করা।                                                                      |
| **Nature of Interference** | **English:** They actively change the content or flow of information, which can result in data corruption or loss. <br> **Translation:** এগুলো সরাসরি তথ্যের কন্টেন্ট বা ফ্লো বদলে দেয়, যা ডেটা ক্ষতি বা হারানোর কারণ হতে পারে।                                                         | **English:** They only observe and record the data, leaving the original content intact. <br> **Translation:** এগুলো শুধু তথ্য শোনে ও রেকর্ড করে, মূল তথ্য অপরিবর্তিত রাখে।                                                                                              |
| **Additional Point 1**     | **English:** Active attacks are often more noticeable and easier to detect because of the disturbances they cause. <br> **Translation:** অ্যাকটিভ আক্রমণগুলো সহজে ধরা পড়ে কারণ এগুলো যোগাযোগে স্পষ্ট বিঘ্ন সৃষ্টি করে।                                                              | **English:** Passive attacks are stealthy and difficult to detect since they do not disrupt normal operations. <br> **Translation:** প্যাসিভ আক্রমণগুলো চুপচাপ হয় ও ধরা পড়তে কঠিন, কারণ এগুলো সাধারণ যোগাযোগে কোনো বিঘ্ন সৃষ্টি করে না।                                            |
| **Additional Point 2**     | **English:** They can lead to immediate consequences such as data loss, service disruption, or unauthorized modifications. <br> **Translation:** এগুলো তৎক্ষণাৎ ফলাফল দেয়, যেমন ডেটা হারানো, সার্ভিস বন্ধ হয়ে যাওয়া বা অননুমোদিত পরিবর্তন।                                                | **English:** They primarily threaten privacy and data confidentiality without directly affecting service availability. <br> **Translation:** এগুলো মূলত প্রাইভেসি ও ডেটা গোপনীয়তার হুমকি সৃষ্টি করে, সরাসরি সার্ভিসে বিঘ্ন ঘটায় না।                                                |


---

### 19. Cryptography: Concepts & Techniques

- **English:** Cryptography involves using algorithms and protocols to protect data from unauthorized access.  
  **Translation:** ক্রিপ্টোগ্রাফি মানে ডেটাকে অননুমোদিত ঢোকা থেকে রক্ষা করতে অ্যালগরিদম ও প্রোটোকল ব্যবহার করা।

- **English:** Concepts and techniques include:  
  **Translation:** এর মধ্যে যে মূল ধারণা ও কৌশলগুলো আছে, সেগুলো হলো:

  - **English:** Encryption: Converting plaintext data into unreadable ciphertext.  
    **Translation:** এনক্রিপশন: সাধারণ টেক্সটকে এমনভাবে পাল্টানো, যাতে সেটি পড়া যায় না।
  
  - **English:** Decryption: Converting ciphertext back into plaintext.  
    **Translation:** ডিক্রিপশন: এনক্রিপ্ট করা টেক্সটকে আবার সাধারণ টেক্সটে ফিরিয়ে আনা।
  
  - **English:** Hashing: Creating a digital fingerprint of data to verify its integrity.  
    **Translation:** হ্যাশিং: ডেটার একটা ডিজিটাল ফিঙ্গারপ্রিন্ট তৈরি করা, যাতে সেটা ঠিক আছে কিনা যাচাই করা যায়।
  
  - **English:** Digital signatures: Using encryption and hashing to authenticate the sender of a message.  
    **Translation:** ডিজিটাল সিগনেচার: এনক্রিপশন ও হ্যাশিং দিয়ে মেসেজের প্রেরক কে ঠিক আছেন, সেটা নিশ্চিত করা।
  
  - **English:** Key exchange protocols: Securely exchanging encryption keys between parties.  
    **Translation:** কী এক্সচেঞ্জ প্রোটোকল: পক্ষের মধ্যে এনক্রিপশন কী সুরক্ষিতভাবে বিনিময় করা।

---

