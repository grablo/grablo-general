# GRABLO TERMS OF SERVICE

**Effective Date: May 7, 2026** (originally effective August 8, 2025; Section 6 — paid services, subscriptions, and withdrawal — amended effective October 1, 2026)

Welcome to the Grablo Platform Services (the "Grablo Site"). Grablo Inc. and/or its affiliates ("Grablo", "we" or "us") provides the Grablo Site to you subject to the following terms of use (the "Terms"). By visiting the Grablo Site or using our Services, you accept these Terms.

**PLEASE READ THESE TERMS CAREFULLY TO ENSURE THAT YOU UNDERSTAND EACH PROVISION. EXCEPT FOR USERS RESIDENT IN THE REPUBLIC OF KOREA OR OTHERWISE PROTECTED BY KOREAN CONSUMER-PROTECTION LAW (SEE SECTION 12.2(a)), THESE TERMS CONTAIN A MANDATORY INDIVIDUAL ARBITRATION AND CLASS ACTION/JURY TRIAL WAIVER PROVISION THAT REQUIRES DISPUTES TO BE RESOLVED BY ARBITRATION ON AN INDIVIDUAL BASIS, RATHER THAN JURY TRIALS OR CLASS ACTIONS.**

## 1. DEFINITIONS

**"Content"** means any and all data, including but not limited to text, audio, video, or images; device data (such as device type, operating system, and unique device identifiers); metadata (information about the data itself, such as creation date, file size, or author); and any other information or data generated, collected, or transmitted in connection with the use of the Services.

**"Controller"** means hardware devices such as Raspberry Pi, BeagleBone, PC, or other compatible hardware that executes projects created through the Services.

**"End User"** means any individual or entity that directly or indirectly through another user (a) accesses or uses Your Content, or (b) otherwise accesses or uses the Services under your account.

**"Grablo Content"** means any and all Content, resources, and materials made available by Grablo, whether directly or indirectly, related to use of the Services or on the Grablo Site, including but not limited to algorithm blocks, device libraries, web dashboards, sample projects, documentation, and other instructional materials.

**"Project Data"** means the no-code programming projects, dashboards, configurations, and related data that you create and store on our servers through the Services.

**"Services"** means the Grablo no-code IoT platform, including our websites (grablo.co, doc.grablo.co), web-based development environment, algorithm block programming interface, device libraries, web dashboards, and related support services.

**"Your Content"** means Content that you or any End User transfers to us for processing, storage or hosting by the Services in connection with your account, including Project Data.

**"AI Analysis Features"** means the artificial-intelligence and machine-learning based image, audio, and signal analysis capabilities included in the Services, including but not limited to object detection, face recognition, pose/action/fall recognition, hand-gesture recognition, line counting, fire/smoke detection, sound classification, optical character recognition (OCR), QR/barcode recognition, color tracking, speech-to-text (STT), and text-to-speech (TTS).

**"User Automation Content"** means any automation artifacts created or configured by you through the Services, including block programs, scripts (such as Lua), condition/action rules, triggers, schedules, data-logging configurations, dashboards, and device-library settings.

**"Connected Device"** means any external hardware that you connect to or control through the Services, including but not limited to GPIO/PWM peripherals, motors, servos, steppers, relays, LEDs, displays, sensors, cameras, microphones, industrial-protocol equipment (Modbus, OPC-UA, CAN, etc.), Bluetooth devices, Zigbee devices, and smart-home integration devices.

## 2. DESCRIPTION OF SERVICES

We provide a web-based no-code IoT platform (the "Grablo Platform") that enables users to create and manage IoT applications using visual algorithm blocks instead of traditional programming languages. The Services include, without limitation:

- Web-based no-code programming and automation interface (block programming, scripts, dashboards);
- Software (including the Grablo Controller package) for control, monitoring, and data logging of Connected Devices;
- AI Analysis Features and related cloud-integrated capabilities (speech recognition/synthesis, image/audio/signal analysis);
- Smart-home and IoT integrations (including wireless protocols such as Zigbee);
- Web and mobile applications for notifications and status monitoring;
- Gallery and Community Service as described in Section 10A;
- Such other ancillary services as Grablo may provide.

The Services are designed to run on a variety of hardware platforms (including Raspberry Pi, BeagleBone, NVIDIA Jetson, PC, and other compatible devices). Grablo may add, modify, or discontinue any portion of the Services subject to reasonable advance notice where required by law.

## 3. ACCOUNT REGISTRATION AND USE

### 3.1 Account Requirements
To access the Services, you must register a user account with a valid email address and provide your name. You represent that you are lawfully able to enter into contracts (e.g., you are not a minor). If you are entering into these Terms for an entity, you represent that you have legal authority to bind that entity.

### 3.2 Account Responsibility
You are responsible for all activities that occur under your account, regardless of whether the activities are authorized by you or undertaken by you, your employees, or a third party. You must maintain the confidentiality of your account credentials and may not sell, transfer, or sublicense them to any other entity or person.

### 3.3 Accurate Information
You must keep your account information current and accurate. You are responsible for any problems that arise from providing inaccurate information.

## 4. DATA COLLECTION AND STORAGE

### 4.1 Information We Collect
The categories of personal data and other information we collect, the purposes of processing, retention periods, processors, and your rights are described in our Privacy Policy, which is incorporated by reference.

### 4.2 Browser-to-Controller Communication
Communication data between your browser and Controller devices does **not** pass through, or get stored on, Grablo servers. WebRTC P2P video may be relayed by Cloudflare TURN where direct connection is unavailable; signaling metadata (SDP/ICE) is exchanged via our MQTT broker. No audio is transmitted through Grablo infrastructure.

### 4.3 Data Storage Location
Project Data and User Posts are stored on Grablo-managed infrastructure (databases hosted in the Republic of Korea; uploaded images stored on Cloudflare R2). The list of processors and international transfers is set out in the Privacy Policy.

## 5. USE OF SERVICES

### 5.1 Permitted Use
You may use the Services to:
- Create IoT applications using our algorithm block interface
- Control and monitor compatible hardware devices
- Store and manage your projects on our platform
- Access device libraries and development tools

### 5.2 Prohibited Use
You may not use the Services to:
- Violate any applicable laws or regulations
- Infringe upon the intellectual property rights of others
- Transmit malicious code, viruses, or harmful software
- Attempt to gain unauthorized access to other users' accounts or data
- Use the Services for any illegal or harmful purposes
- Reverse engineer, decompile, or disassemble any part of the Services
- Use the Services in a manner that could damage, disable, overburden, or impair our servers

### 5.3 Restricted Use
You may **not** use the Services, AI Analysis Features, Connected Devices, or User Automation Content as the sole or primary means of, or as a substitute for, any of the following:

- life-safety, fire-alarm, smoke-detection, or evacuation systems required by applicable building, fire, or safety codes;
- intrusion-detection, surveillance, alarm-monitoring, or security systems requiring professional certification;
- medical diagnosis, treatment, patient monitoring, or any other use within the scope of applicable medical-device regulation (including U.S. FDA, EU MDR/IVDR, UK MHRA, and Korea MFDS);
- automotive, aviation, marine, rail, industrial-machinery, robotic, or elevator control where human life or critical infrastructure is at risk;
- nuclear, chemical, or biological hazard monitoring or control;
- systems required to comply with functional-safety standards including IEC 61508, IEC 62061, ISO 13849, ISO 26262, IEC 60601, or equivalents;
- any other application whose primary purpose is the protection of life, health, or property.

You are solely responsible for any use of the Services in violation of this Section 5.3 and for any resulting damages.

## 6. SERVICE PLANS, FEES, AND SUBSCRIPTIONS

### 6.1 Free and Paid Services
The core Services are available free of charge. We may offer paid services of two kinds: (a) **subscription plans** billed on a monthly or annual basis, and (b) **one-time paid digital content** such as paid gallery templates. The features, prices, billing cycle, and refund conditions of each paid service are displayed on our website before you pay. Existing users always retain the option to continue with the available free features.

### 6.2 Purchases Are Made on the Web
Paid services are purchased through our website only. Payments are processed by external payment processors or, for certain regions, by a merchant of record; we do not store raw payment credentials such as card or bank account numbers.

### 6.3 Automatic Renewal
Unless you cancel, a subscription automatically renews at the end of each billing period, and the renewal fee is charged automatically to your registered payment method. For plans priced by quantity or usage, the renewal amount is calculated according to the pricing basis disclosed at checkout (for example, the number of registered devices or cameras). Automatic renewal, the pricing basis, and how to cancel are disclosed at checkout.

### 6.4 Cancellation
You may cancel a subscription at any time from the service screens. Cancellation stops future renewals; your paid benefits remain available until the end of the period you have already paid for. Refunds for the current period are governed by Section 6.6.

### 6.5 Changes to Pricing
If we change subscription pricing, we will give advance notice (at least 30 days for changes unfavorable to you), and the new price applies from the first renewal after the announced effective date. If you do not agree, you may cancel before that renewal.

### 6.6 Withdrawal and Refunds
- If you reside in the Republic of Korea, you may withdraw your purchase within 7 days of payment (or of the start of service, whichever is later) under the Act on the Consumer Protection in Electronic Commerce. Withdrawal may be restricted where permitted by that Act, for example once subscription benefits have been used or digital content has been downloaded or copied; any such restriction is disclosed at checkout. Refunds for valid withdrawals are made within 3 business days.
- If we fail to provide a paid service due to causes attributable to us, you may request an extension of the service period or a refund for the remaining period.
- If a payment is refunded or charged back, the corresponding paid benefits (plan tier, digital-content entitlement) may be revoked.
- Nothing in this section limits any non-waivable statutory rights you have in your country of residence.

### 6.7 Free Trials
We may offer free trial periods for subscriptions. The trial terms, and whether and when the trial converts to a paid subscription, are disclosed in advance. If you cancel before the trial converts, you are not charged.

### 6.8 Minors
If a minor makes a payment without the consent of a legal guardian, the minor or the guardian may cancel the payment as provided by applicable law.

### 6.9 Erroneous Payments
Overpayments and erroneous payments are refunded by the same payment method where possible; otherwise we will notify you and refund by another method.

## 7. INTELLECTUAL PROPERTY

### 7.1 Your Content
You retain all rights, title, and interest in Your Content, including Project Data. You grant us a limited license to use Your Content solely to provide the Services to you.

### 7.2 Grablo Content
We own all rights, title, and interest in the Grablo Content and Services. Subject to these Terms, we grant you a limited, non-exclusive, non-transferable license to use the Grablo Content solely in connection with your permitted use of the Services.

### 7.3 Feedback
If you provide feedback about the Services, we may use such feedback without restriction or compensation to you.

## 8. PRIVACY AND DATA PROTECTION

Your privacy is important to us. Our collection and use of your personal information is governed by our Privacy Policy, which is incorporated into these Terms by reference. By using the Services, you consent to the collection and use of your information as described in our Privacy Policy.

We comply with applicable Korean privacy laws, including the Personal Information Protection Act and the Act on Promotion of Information and Communications Network Utilization and Data Protection.

## 9. DISCLAIMERS

### 9.1 General Disclaimer
THE SERVICES AND GRABLO CONTENT ARE PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, ACCURACY, OR THAT THE SERVICES WILL BE UNINTERRUPTED, SECURE, OR ERROR-FREE.

### 9.2 AI Analysis Features Disclaimer
The AI Analysis Features are provided **for informational and supplementary purposes only** and do not replace your decision-making, operations, or safety measures.

(a) AI outputs are subject to false positives and false negatives depending on training data, camera/microphone quality, lighting/noise/weather and other environmental conditions, network state, processing load, and model versions. Grablo makes **no warranty** as to accuracy, completeness, timeliness, or reliability of any AI output.

(b) The AI Analysis Features have **not** been certified under any functional-safety, medical, industrial, automotive, aviation, or security standard, and shall not be used for any purpose restricted under Section 5.3. You must independently install and maintain certified safety, fire-alarm, security, or medical systems as required by applicable law or industry standard.

(c) Grablo may update, retrain, modify, or discontinue any AI model at any time without notice. Grablo is not liable for output variation, incompatibility, non-reproducibility, or feature withdrawal resulting from such changes.

(d) You shall be solely liable for any death, personal injury, property damage, fire, accident, delayed emergency response, data breach, or other loss arising from use of the AI Analysis Features in violation of this Section or Section 5.3.

### 9.3 Connected Devices and Automation Disclaimer
The Services interface with a wide range of Connected Devices and execute User Automation Content.

(a) Grablo does not warrant correct, accurate, or stable operation across all hardware, environments, or workloads.

(b) Design, validation, and operation of User Automation Content is **your sole responsibility**. Grablo makes no warranty regarding intended behavior, safety, fitness, performance, or interoperability of User Automation Content with other systems.

(c) Grablo shall not be liable for any of the following arising from device malfunction, unintended actuation, communication delay or loss, power anomaly, firmware/OS incompatibility, third-party device behavior (including Zigbee devices, IP cameras, smart-home devices), or any other cause:

- death or personal injury;
- fire, explosion, water damage, electrical shock, short-circuit, or any property damage resulting therefrom;
- business, operational, or production interruption or loss;
- loss, alteration, or unauthorized disclosure of data;
- any direct, indirect, consequential, special, incidental, or punitive damages.

(d) The Services are **not** certified for any safety-integrity level (SIL), functional-safety standard (IEC 61508, IEC 62061, ISO 13849, ISO 26262), medical-device safety standard (IEC 60601), or aviation/marine standard. Use in environments requiring such certification is **prohibited**.

(e) For any safety-critical environment, you must install and maintain independent safety devices (such as emergency stops, interlocks, physical barriers, and certified safety controllers) that operate independently of the Services.

### 9.4 Third-Party Services and Infrastructure Disclaimer
The Services interoperate with third-party services in two distinct ways:

**(i) Processors engaged by Grablo** under our own credentials and listed in our Privacy Policy: Cloudflare (image storage and WebRTC TURN relay); Google Firebase (Android push); Apple APNs (iOS push); Google, Naver, Kakao, Apple (social login); outbound email SMTP.

**(ii) Third-party services that you call directly through your Controller using your own credentials**, including but not limited to Google Cloud, OpenAI, and ElevenLabs (speech recognition/synthesis); Telegram; ONVIF/RTSP IP cameras; Home Assistant; Zigbee2MQTT; ESPHome; and Matter devices. **These are not Grablo processors.** Audio for TTS/STT, for example, never traverses Grablo servers — calls go from your Controller directly to the third-party provider with your own API keys.

(a) Availability, accuracy, fees, terms of service, and privacy policies of third-party services are governed solely by the respective third party. You are responsible for reviewing and complying with their terms before use.

(b) Grablo is not liable for damages arising from any third-party service change, outage, error, fee, or data breach.

(c) Messaging and signaling infrastructure operated by Grablo (including, without limitation, mqtt.grablo.co and P2P streaming signaling) is provided on a reasonable-effort basis. Grablo does not guarantee uninterrupted availability and may suspend or terminate such infrastructure at any time, including for maintenance, failure, security incident, legal demand, or service-policy change.

### 9.5 Personal and Biometric Data Captured by You
If you use the Services to capture, process, or store images, audio, biometric information, or personal data of any individual, you are solely responsible for obtaining all required consents, complying with applicable privacy and biometric-data laws (including Korea's Personal Information Protection Act, the EU GDPR, U.S. state biometric privacy laws such as BIPA, and any other applicable law), and operating any video/audio surveillance equipment in compliance with law. Grablo is not liable for your failure to obtain consents or otherwise comply with such laws.

### 9.6 User Code, Recording, Auto-Update, and Open-Source Software

**(a) Execution of user code.** The Services let you create and run scripts (such as Lua) and block programs in the Controller environment. Grablo does not warrant that user code runs within a sandbox isolated from the operating system, file system, or network of the Controller. You are solely responsible for the security, behavior, and consequences of your code and any external libraries or commands it invokes. Grablo disclaims liability, to the extent permitted by applicable law, for data leakage, system damage, or third-party harm arising from your code.

**(b) Recording and processing of audio/video.** If you use camera, microphone, recording, or P2P streaming features, you are solely responsible for obtaining required consents (including two-party consent where applicable), providing recording notices, complying with surveillance and wiretapping laws, and managing retention/deletion of recordings.

**(c) Outbound messaging.** If you use the Services to send messages or notifications via external channels (email, Telegram, SMS, etc.), you are responsible for compliance with anti-spam, marketing-consent, sender-identification, and opt-out requirements (including the U.S. CAN-SPAM Act, Korea's Information and Communications Network Act Art. 50, and equivalents). Grablo is not liable for spam, harassment, defamation, or other unlawful messaging conducted through the Services and may restrict the relevant feature where misuse is established.

**(d) Auto-update.** Grablo may provide updates to the Controller software, AI models, firmware, and device libraries. For security or service-stability reasons, updates may be performed automatically without prior notice. Grablo is not liable, to the extent permitted by applicable law, for temporary disruption, behavior change, or compatibility issues caused by such updates. Where supported, you may opt to defer or decline non-critical updates.

**(e) Local data logging.** The data-logging feature stores variable values, events, and similar records **locally on your Controller**. You are responsible for configuring retention limits (size, count, duration) and for deletion. Grablo does not have direct control over data stored locally on your Controller.

**(f) External integrations.** When you integrate the Services with external systems (Home Assistant, Zigbee2MQTT, ESPHome, Matter, etc.), the security and privacy implications of exposing those systems to the internet, sharing credentials, or routing data externally are your responsibility.

**(g) Open-source software.** The Services include open-source software components. License terms and copyright notices are made available through a designated webpage and/or a LICENSES file shipped with the Controller package. Where an open-source license conflicts with these Terms, the open-source license prevails to the extent of that conflict.

**(h) Carve-out.** Sections 9.6(a)–(g) do not exclude or limit Grablo's liability for damages caused by Grablo's gross negligence, willful misconduct, or fraud, or where such exclusion or limitation is prohibited by applicable law.

## 10. LIMITATION OF LIABILITY

### 10.1 Exclusion of Indirect Damages
TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL GRABLO BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, EXEMPLARY, OR PUNITIVE DAMAGES, INCLUDING BUT NOT LIMITED TO LOSS OF PROFITS, REVENUE, GOODWILL, BUSINESS OPPORTUNITY, DATA, USE, OR INFORMATION; BUSINESS INTERRUPTION; HARDWARE MALFUNCTION; OR COST OF SUBSTITUTE GOODS OR SERVICES, REGARDLESS OF THE THEORY OF LIABILITY (CONTRACT, TORT, STRICT LIABILITY, OR OTHERWISE), EVEN IF GRABLO HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

### 10.2 No Limitation of Non-Excludable Liability
Nothing in these Terms excludes or limits Grablo's liability where such exclusion or limitation is not permitted by applicable law (including, where applicable, liability for gross negligence, willful misconduct, or fraud).

## 10A. GALLERY AND COMMUNITY SERVICE

### 10A.1 Scope
The Services may include a gallery and community feature ("Community Service") that lets registered users share projects, images, descriptions, comments, likes, bookmarks, and other content (collectively, "User Posts"). Non-registered visitors may view publicly listed User Posts but may not create posts, comments, or other interactive content.

### 10A.2 Ownership and License Grant
You retain all rights, title, and interest in your User Posts. You grant Grablo a worldwide, non-exclusive, royalty-free, sublicensable (solely to subprocessors strictly necessary to operate the Services) license to host, store, reproduce, transmit, display, distribute, translate, modify (solely for technical formatting), and otherwise use your User Posts for the purpose of operating, promoting, improving, indexing, sharing, copying-on-request, backing up, and caching the Services. This license terminates when you delete your User Posts, except (i) for content already copied or cached by other users beyond Grablo's reasonable control, and (ii) to the extent retention is required by applicable law or for legitimate backup, audit, or fraud-prevention purposes.

### 10A.3 Prohibited Content
You may not post, transmit, or otherwise make available any User Post that:

(a) violates applicable law, regulation, public order, these Terms, or Grablo's operating policies;
(b) infringes any third-party copyright, trademark, right of publicity/portrait, personal-data right, trade-secret, or other right;
(c) is obscene, violent, discriminatory, hateful, harassing, defamatory, or harmful to minors;
(d) contains misinformation, spam, unsolicited advertising, multi-level-marketing, gambling, or solicitation of unlawful transactions;
(e) contains malware, phishing links, or code exploiting security vulnerabilities;
(f) contains images, audio, biometric data, or other personal data of any individual without that individual's lawful consent;
(g) impersonates Grablo, its personnel, or any other user, or interferes with the normal operation of the Services;
(h) is otherwise reasonably determined by Grablo to be inappropriate.

You are solely responsible for, and shall indemnify Grablo against, any claim, damage, or liability arising from your User Posts or your violation of this Section.

### 10A.4 Moderation
Grablo has no general obligation to pre-screen User Posts. However, where a User Post is reasonably suspected to violate Section 10A.3, Grablo may, without prior notice, hide, remove, edit, restrict sharing of, or restore the User Post; restrict the user's access to the Community Service; suspend the user's account; or terminate the agreement, in each case proportionate to the violation.

### 10A.5 Reporting
You may report a User Post that you believe violates these Terms via the designated reporting interface or by contacting support@grablo.co. Grablo will review reports within a reasonable time.

### 10A.6 Use of Other Users' Posts
If you copy, download, or otherwise import another user's User Post (including any project, configuration, automation script, or device library) into your own environment, **you are solely responsible for the operation, safety, suitability, and consequences of running that content**, and Sections 9.2 (AI Analysis Features), 9.3 (Connected Devices and Automation), and 9.4 (Third-Party Services) of these Terms apply in full to such use.

### 10A.7 Persistence After Deletion
Even after you delete your User Post or terminate your account, copies, citations, or caches of that content held by other users or third parties may remain outside Grablo's direct control. Grablo may also retain User Posts for a reasonable period for backup, audit-log, or legal-compliance purposes.

## 11. TERMINATION

### 11.1 Termination by You
You may terminate your account at any time by contacting us at support@grablo.co or through account settings if available.

### 11.2 Termination by Us
We may terminate or suspend your access to the Services immediately if you breach these Terms or for any other reason with appropriate notice.

### 11.3 Effect of Termination
Upon termination, your right to use the Services will cease immediately. We may delete Your Content in accordance with our data retention policies.

## 12. GOVERNING LAW AND DISPUTE RESOLUTION

### 12.1 Governing Law
These Terms shall be governed by and construed in accordance with the laws of the Republic of Korea, without regard to conflict of law principles.

### 12.2 Dispute Resolution

**(a) Users resident in the Republic of Korea or otherwise protected by Korean consumer-protection law.** Any dispute arising from these Terms shall be subject to the exclusive jurisdiction of the courts of the Republic of Korea, with the court having jurisdiction over Grablo's principal place of business as the court of first instance, in accordance with the Korean Civil Procedure Act and the Act on the Regulation of Terms and Conditions. Sections 12.2(b) and 12.2(c) below do **not** apply to such users.

**(b) All other users.** Any dispute arising from these Terms shall be resolved through binding individual arbitration in accordance with the rules of the Korean Commercial Arbitration Board, except that you may assert claims in small-claims court if your claims qualify. The arbitration shall be conducted in Korean or English as mutually agreed by the parties.

**(c) YOU AND WE EACH WAIVE THE RIGHT TO A TRIAL BY JURY AND TO PARTICIPATE IN A CLASS, COLLECTIVE, OR REPRESENTATIVE ACTION**, except where such waiver is unenforceable under applicable law.

**(d) Non-waivable consumer rights.** Nothing in this Section limits any non-waivable right or remedy available to you under mandatory law in your country of residence (including, where applicable, EU/EEA consumer-protection rules and Korean consumer-protection laws).

## 13. COMPLIANCE WITH KOREAN LAW

We comply with applicable Korean laws, including but not limited to:
- Personal Information Protection Act
- Act on Promotion of Information and Communications Network Utilization and Data Protection
- Electronic Commerce Act
- Consumer Protection Act

## 14. GENERAL PROVISIONS

### 14.1 Entire Agreement
These Terms, together with our Privacy Policy, constitute the entire agreement between you and Grablo regarding the Services.

### 14.2 Modifications
We may modify these Terms by posting the revised Terms on the Grablo Site. For changes that are material or unfavorable to users, we will provide notice at least **thirty (30) days** before the effective date through the Grablo Site and, where reasonably possible, through email or in-Service notification. For non-material changes, we will provide notice at least seven (7) days before the effective date. If you object to a modification, you may terminate the agreement before the effective date; if you do not object before the effective date, you will be deemed to have accepted the modification. Where applicable law (including Korea's Act on the Regulation of Terms and Conditions) requires longer notice or specific procedures, those requirements prevail.

### 14.3 Severability
If any provision of these Terms is found to be unenforceable, the remaining provisions will remain in full force and effect.

### 14.4 Assignment
You may not assign these Terms without our prior written consent. We may assign these Terms without restriction.

### 14.5 Contact Information
If you have questions about these Terms, please contact us at:

**Grablo Inc.**  
Representative: Young-Min Kim  
Address: 8, Dunsan-ro, Seo-gu, Daejeon, Republic of Korea  
Email: support@grablo.co  
Website: grablo.co

## 15. NOTICES

We may provide notice to you under these Terms by posting a notice on the Grablo Site or by sending a message to the email address associated with your account. Notices will be effective upon posting or sending.

---

**IF YOU DO NOT AGREE TO THESE TERMS, PLEASE DO NOT USE THE SERVICES.**

*Last Updated: October 1, 2026*