+++
title = "SS14 Privacy Policy"
description = "Privacy Policy for SS14 Game Server Connections, including EU Resident GDPR Rights."
summary = "The SS14 Privacy Policy and EU Resident GDPR Rights Privacy Policy"
date = "2026-05-13"
layout = "single"
showTableOfContents = "true"
showDateUpdated = "true"
showWordCount = "true"
+++

# SS14 Game Server Privacy Policy

This section will outline how we, ProjectOmu and OmuStation SS14 Servers, collect and handle your data when you connect to our SS14 Game Servers. This is only in relation to publicly or privately hosted SS14 servers that we remain in control of.

## Terminology

This sub-section will outline terminology in relation to the SS14 Game Server Privacy Policy:
- ProjectOmu: The direct reference to ProjectOmu or OmuStation, used to cover both areas of interest; OmuStation is a direct part of ProjectOmu as the reference to SS14 game servers hosted under ProjectOmu.
- Redialing: The process of automatic reconnection through the game's launcher to other servers, in line with the SS14 Hub's policy.
- UUID (Universal Unique Identifier)/User ID: The 128-bit unique universal identification number associated with your user/game account with the SS14 Authentication Hub.
- IP Address: The numerical label associated with your connection address to the network.
- HWID (Hardware ID): The hashed identification number associated with your with your device's configuration, specifically the generated number in your hardware registry.
- VPN (Virtual Private Network): A service that masks the IP Address and location of connection from your client device to a destination server.
- Admin: Volunteer staff members that are part of ProjectOmu responsible for maintaining and enforcing rules on the SS14 game servers hosted under ProjectOmu.
- Maintainer: Volunteer staff members that are part of ProjectOmu responsible for maintaining the repository and/or controlling configuration files for the server that may have access to logs or other information the server records.
- Network Operators: Personnel maintaining server infrastructure and networking for game servers or server boxes.
- Server Hosts: Third-party companies providing the physical server hardware and network configuration/connectivity.
- VPN Detector: A third-party service that detects and relays detected VPN information.

## ProjectOmu Data Collection

This sub-section will outline the data that is collected when connecting to ProjectOmu SS14 Game Servers:
- Your User ID (UUID) and account username.
- Your IP Address and approximate geographical location.
- Your Hardware ID (HWID).
- Explicit user preferences that are submitted to the servers.
- Your Discord User information, roles associated with your account in relation to ProjectOmu Discord Servers, and the UUID of your Discord account (upon linking your account with the Discord) .
- All in-game interaction and communications with the ProjectOmu SS14 Game Server.

## Data Access

This sub-section will outline the personnel who have access to the data collected as mentioned in ProjectOmu Data Collection.

### ProjectOmu Internal Team

The ProjectOmu Internal Team includes Admins, Owners, and Maintainers that work with the ProjectOmu Repository on GitHub. The members of this team may have access to the following:
- Server Connection History (UUID/IP/HWID): Members of the team may have access to your connection information to the server for the purposes of moderation or monitoring network traffic for rules enforcement. Senior members of the team, including the owners, are the only individuals that have access to the IP/HWID.
- In-Game Chat and Game Logs: Members of the team may have access to any information you've sent to the server, including in-game actions and communications, as well as log information of your interactions for the purposes of moderation and rules enforcement. All Admins, Owners, and senior Maintainers have access to logged information.
- Moderation Action Records: All Admins and Owners of the team have access to moderation action records, specifically history of moderation taken against or alongside the user during the connection history to the server for moderation purposes.

### Network Operators

The ProjectOmu Network Operators consists of Owners and Senior members capable of making changes to the server(s) and configuration of network connections to the server(s). These members are part of the ProjectOmu Internal Team. These members have access to the following:
- All **ProjectOmu Internal Team** access. These members are part of the Internal Team.
- Raw Database Records: Any information that has been collected to the database for the SS14 Game Servers.
- Unfiltered Connection Metadata: All connection information that has been logged to the server and saved, including metadata that would not normally be available to the Internal Team.
- Server Diagnostic Streams and Data: Any information sent to the server as well as its diagnostic information regarding information relevant to the performance of the server(s).
- Persistent Storage Archives: Any information, in-game replays, or other data that has been collected and archived for purposes of moderation, statistical analysis, or other purposes worthy of archival.

### Server Hosts

The Server Hosts are not directly affiliated with the ProjectOmu Internal Team. These are third-party members hosting the server box or VPS that ProjectOmu utilizes for hosting servers and community-accessible resources, including the CDN that build information for servers are downloaded from. The Server Hosts have access to the following information:
- Network Traffic Patterns: Any information that is relayed to the server through the network when connected to the servers.
- Hardware Utilization: Diagnostic information and utilization of the hardware that is being used by ProjectOmu.

The Server Hosts do not have access to specific data relayed to the server or game, including the following:
- They do not have access to Decrypted Game Data or specific logs for the server, nor access to the database on the server.
- They do not have access to the personal identifiers, including HWID/UUID of any connecting person(s).

> These are bound by data processing agreements (DPAs).

### VPN Detectors

The VPN Detectors are a third-party service that ProjectOmu utilizes for connections to game servers for the purpose of denying connections based on VPN usage. As part of a prevention measure against ban evasion and suspicious game activity, we reserve the right to deny based on VPN usage. For this purpose, we utilize [IPIntel](https://getipintel.net/) to detect VPN connections and deny connection to the game server. VPN Detectors follow these data access/collection measures:
- They receive IP Address information related to the connection.
- The information they receive is deleted after checking for VPN.

> You may request exemption from VPN Banning on the [Discord](https://discord.gg/omustation) by making a ticket. This will also exempt you from being checked by IPIntel or any other VPN Detector we may use in the future for SS14 Game Servers.

## Connection Management

The following section defines how connections are managed and recorded on our server(s).

### Redialing Processes

The Redialing involves the following:
- Connecting you to official servers within the SS14 Game Server Hub; specifically consenting servers.
- Maintaining the UUID/HWID Identifiers that are used.
- Preserving the connection history to the server and redirection.
- No data is shared with other servers during Redialing.
- No additional data is collected during Redialing.

### VPN Detection

The VPN Detection works as follows:
- New connections to the server are checked by using the IPIntel services.
- VPN connections are blocked when confirmed with IPIntel services.
- Exemptions are available by making a ticket on the official Discord.

### Location Tracking

Your location is derived from your IP Address, which gives a general geographic location. This is used for the following:
- Connection Quality Monitoring: The quality of the connection to where you are located.
- Regional Rule Enforcement: Different enforcement of rules based on where you are located, such as following processes involving other countries.
- Server Allocation Analytics: Monitoring statistical data collected by the server and its allocations.

# Notice of Data Sharing

Your UUID, IP Address, and/or HWID may be shared with other game servers for the purposes of moderation actions, and only moderation actions. This includes cross-server moderation actions such as banning a user for egregious actions or security purposes. These are only shared with active administrators that are part of that server's internal team.

> Some in-game communication methods, such as OOC, news reports, and/or conversation with game staff may be sent to our Discord community and would be considered logged there as well. These are generally for cross-platform communication and engagement with the community.

# GDPR Specific Information

Since ProjectOmu has servers within the EU region, it is bound by GDPR. This information is shown below. If you do not live in an EU region, you do not need to read this information as it does not apply to you.

## Your GDPR Rights

EU Residents have the right to the following:
- Requesting access to personal data that has been collected by our server(s).
- Rectifying inaccurate data that has been collected by our server(s).
- Erasing personal data within our server(s) under specific conditions.
- Restricting the processing of personal data collected by our server(s).
- Personal data portability.
- Object to processing of personal data.

> Please submit these requests to: [ProjectOmu Email](mailto:ss14opal@gmail.com).

### Limitations on Data Erasure

You may request deletion of your personal data. However, under GDPR Article 17, we may refuse erasure requests where data is required for:
- Moderation Actions and Rule Enforcement: Any actions taken against your account or connection for the purpose of enforcing the rules associated with the game server(s).
- Security and Abuse Prevention: Any actions done so for security purposes or to prevent abuse of your connection to our server.
- Ban Enforcement (Including Active/Permanent Bans): To maintain moderation actions against your account where you would be banned from connecting to the server.
- Maintaining Moderation History: Any history saved by the server(s) and staff team for the purpose of maintaining moderation against your account in order to enforce rules or previous moderation actions or for contextual review.

> Character data and other non-essential gameplay data may be deleted at any time. This data is not required for moderation actions. This includes time played on the server.

## Lawful Basis for Processing

Under the GDPR, we process data based on the following:
- Contractural Necessity: Your account data is required to provide services.
- Legitimate Interests: Security monitoring, moderation, rule enforcement, maintaining moderation history, detecting repeat or escalating violations, preventing ban evasion, abuse investigation, and handling appeals. Retention of historical moderation records is necessary to ensure fair, consistent, and effective enforcement across our community.
- Consent: Optional features such as linking your Discord account for the purposes of Discord Integration.

## Data Transfers

Your personal data may be transferred out of the EU for the purpose of the following:
- Our hosting providers in the United States, including our main database which is located in the United States.
- Third-party services such as Discord and IPIntel.

We ensure these transfers comply with the GDPR through the following:
- EU Standard Contractural Clauses (SCCs).
- Appropriate data processing agreements.

## Data Retention

We retain different types of your personal data for different purposes:
- Gameplay and Chat Logs: These are retained for up to 30-45 days to support moderation review and incident investigation. Logs are automatically deleted after this period unless they are involved in an ongoing moderation action.
- Moderation Records: Records, commonly referred to as notes in-game, such as bans, warnings, and administrative notes (including notes that are hidden from the player) are retained as long as they are necessary for moderation, rule enforcement, abuse prevention, and maintaining the integrity of the service. This includes historical records of previous bans and warnings, which help moderators understand patterns of behavior and ensure consistent enforcement.
- Permanent Bans: These are treated as ongoing enforcement actions and are retained for as long as necessary for moderation and enforcement purposes.
- Hardware Identifiers (HWID) and Connection Identifiers (IP Address): Retained where necessary to enforce bans, prevent ban evasion, and protect the integrity of the service. These identifiers are used solely for enforcement and security purposes, and are not used for marketing, profiling, or advertising.

> We do not retain data longer than necessary for its stated purpose.

## Security Incidents

In the event of a security incident, we will notify affected EU users within 72 hours of becoming aware of a data breach that risks their rights and freedoms. Affected users will be notified directly where feasible. Public announcement channels, such as our [Discord Server](https://discord.gg/omustation), may be used as a supplementary notification method.