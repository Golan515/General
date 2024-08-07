# General


Awesome lists

Threat Hunting

https://github.com/threat-hunting/awesome_Threat-Hunting/tree/master

Awesome all
https://github.com/sindresorhus/awesome

JSON
https://github.com/burningtree/awesome-json

Symbolic Execution
https://github.com/ksluckow/awesome-symbolic-execution

Endpoint Detection Bypass Resources
https://github.com/tkmru/awesome-edr-bypass

Endpoint Detection & Response
https://github.com/shadawck/awesome-endpoint-detection-and-response

Grok Regular Expressions

https://github.com/hpcugent/logstash-patterns/blob/master/files/grok-patterns.json


Policy as Code
https://github.com/hysnsec/awesome-policy-as-code

Insider Threat
https://github.com/Insider-Threat/Insider-Threat

Productivity
https://github.com/jyguyomarch/awesome-productivity

Regular Expressions
https://github.com/aloisdg/awesome-regex

Bash
https://github.com/awesome-lists/awesome-bash

Application Security
https://github.com/paragonie/awesome-appsec

ChatGPT
https://github.com/awesome-chatgpt/awesome-chatgpt

Security Operations Center(SOC)
https://github.com/mthcht/awesome-lists

Incident Response
https://github.com/meirwah/awesome-incident-response

Malware Analysis
https://github.com/rshipp/awesome-malware-analysis

Industrial Control Systems (ICS)
https://github.com/hslatman/awesome-industrial-control-system-security

Governance Risk Compliance (GRC)
https://github.com/Arudjreis/awesome-security-GRC

Security Orchestration Automation Response (SOAR)
https://github.com/correlatedsecurity/Awesome-SOAR

Hadoop
https://github.com/youngwookim/awesome-hadoop

Windows Security
https://github.com/chryzsh/awesome-windows-security

Web Application Firewalls
https://github.com/0xInfection/Awesome-WAF

Certifications 1
https://github.com/PanXProject/awesome-certificates?tab=readme-ov-file#security

Certifications 2
https://github.com/cloudcommunity/Free-Certifications

Project Management
https://github.com/shahedbd/awesome-project-management?tab=readme-ov-file#Certification

Shells
https://github.com/alebcay/awesome-shell

Kafka
https://github.com/infoslack/awesome-kafka

Threat Detection and Hunting
https://github.com/0x4D31/awesome-threat-detection?tab=readme-ov-file

DropBox EventList

https://dropbox.github.io/dropbox-sdk-java/api-docs/v3.1.x/com/dropbox/core/v2/teamlog/EventTypeArg.html

https://www.dropbox.com/developers/reference/events-migration-guide

Box events

https://opensource.box.com/box-java-sdk/javadoc/com/box/sdk/BoxEvent.EventType.html

List of all port numbers and their corresponding protocol and service name
http://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml

Network Security Usecases
NTP service
https://www.cloudflare.com/learning/ddos/ntp-amplification-ddos-attack/

Splunk multiple log source usecases

https://research.splunk.com/detections/

Internal IP address Range
10.*,192.168.*,172.16.*,172.17.*,172.18.*,172.19.*,172.20.*,172.21.*,172.22.*,172.23.*,172.24.*,172.25.*,172.26.*,172.27.*,172.28.*,172.29.*,172.30.*,172.31.*

Threat Hunting

PEAK Threat Hunting Framework

https://www.splunk.com/en_us/blog/security/peak-threat-hunting-framework.html

Threat Hunting using MITRE ATT&CK Framework

Step 1 - Choose Hypothesis based apporach

Step 2 - List the log sources available in the SIEM to Threat Hunt

Step 3 - For each of the log source identify the datasource in MITRE https://attack.mitre.org/datasources/

Step 4 - Example Cloud Service logs - Identitfy example AWS Cloudtrail Logs for DeleteTrail  events https://attack.mitre.org/datasources/DS0025/

Step 5 - Check if there is any spike in the DeleteTrail events for any instance or user for that day, then for the week, for the month


Logs sources fields

RSA SecureID

https://docs.sekoia.io/xdr/features/collect/integrations/application/rsa_securid/

Logstash parsing for Cisco ASA

https://gist.github.com/mrlesmithjr/791dc72d3c92ac21342f

Palo Alto Next-Generation Firewall

https://docs.paloaltonetworks.com/pan-os/10-1/pan-os-admin/monitoring/use-syslog-for-monitoring/syslog-field-descriptions/decryption-log-fields

Palo Alto Threat URL categories

https://docs.paloaltonetworks.com/advanced-url-filtering/administration/url-filtering-basics/url-categories

Grok patterns for firewall and PANOS

https://github.com/haginara/grok-patterns/tree/master

Netcat Cheatsheet

https://sansorg.egnyte.com/dl/Rop1b0ElWo

nc localhost 5514 <( echo "Line of text" )
nc localhost 5514 < filename

Logstash Test

cat samplelog | /usr/share/logstash/bin/logstash -f logstashfilter.conf

to run the filter via logstash add

input{
    stdin {

    }
}
before

after
output {
    stdout {

    }
}


SIEMs

translates (among others) Sigma rules to the search language from a variety of platforms like Splunk Search Processing Language

https://uncoder.io/

AS400

Brief overview of AS/400 Security fundamentals 
https://www.giac.org/paper/gsec/709/overview-as-400-security-fundamentals/101584

AS/400 and iSeries: A Comprehensive Guide to Setting System Values to Common Best Practice Security
https://sansorg.egnyte.com/dl/hPebiuXOf3

Security commands - for SOC usecases
https://www.ibm.com/docs/en/i/7.5?topic=reference-security-commands

Microsoft O365 Exchange log event details

https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-schema

Microsoft AzureAD Sign-in log fields with values

https://learn.microsoft.com/en-us/graph/api/resources/signin?view=graph-rest-1.0

Microsoft AzureAD Monitor log fields with values

https://learn.microsoft.com/en-us/entra/identity/monitoring-health/reference-azure-monitor-sign-ins-log-schema

Google Drive Audit Activity Events

https://developers.google.com/admin-sdk/reports/v1/appendix/activity/drive

Microsoft AzureAD Directory Audit Events

https://learn.microsoft.com/en-us/entra/identity/monitoring-health/reference-audit-activities

Fortinet Sample log and log format

https://docs.fortinet.com/document/fortigate/6.2.14/cookbook/986892/sample-logs-by-log-type

Multiple log sources documentation references

https://docs.panther.com/data-onboarding/supported-logs/ciscoumbrella

https://www.elastic.co/guide/en/beats/filebeat/current/exported-fields-aws.html

Cisco ASA VPN event logs

https://www.cisco.com/c/en/us/td/docs/security/asa/syslog/b_syslog/syslogs1.html

Cisco Secure Remote Access VPN Logs

https://docs.sse.cisco.com/sse-user-guide/docs/remote-access-vpn-log-formats

BeyondTrust Log formats

https://documentation.cysiv.com/articles/#!data-source-onboarding-device-configuration-reference/beyondtrust-privelege-access-reference-information-and-cim-field-mapping

AzureAD Directory Audit Events

https://github.com/toddkitta/azure-content/blob/master/articles/active-directory/active-directory-reporting-audit-events.md

Forcepoint DLP Log description

https://www.websense.com/content/support/library/data/v881/help/edit%20view%20filter.aspx

Okta Log Events

https://developer.okta.com/docs/reference/api/event-types/

https://help.okta.com/en-us/content/topics/security/behavior-detection/logs-behavior-detection.htm

Microsoft Defender Log details

https://learn.microsoft.com/en-us/microsoft-365/security/defender/advanced-hunting-deviceprocessevents-table?view=o365-worldwide

Cisco Umbrella DNS log sample and format

https://docs.umbrella.com/deployment-umbrella/docs/dns-log-formats

Cisco Umbrella Proxy log sample and format

https://docs.umbrella.com/deployment-umbrella/docs/proxy-log-formats

Advanced hunting queries for Microsoft Defender Security Center

https://github.com/gmellini/Microsoft-Defender-Security-Center-Hunting-Queries/blob/main/README.md

Crowdstrike Falcon Logs and values

https://xsoar.pan.dev/docs/reference/integrations/crowdstrike-falcon

Crowdstrike Falcon Data Replicator

https://documentation.securonix.com/bundle/securonix-on-prem-user-guide/page/content/data-dictionary/mapping-by-parser/detailed-mapping-for-crowdstrike-falcon-data-replicator-api.htm

CrowdStrike Falcon Python wiki

https://falconpy.io/Home.html

XDR, Azure and AWS Usecases
https://docs.stellarcyber.ai/prod-docs/4.3.x/Using/ML/Machine-Learning-by-xdr-event-name.htm?tocpath=REFERENCE%7CDetection%20and%20Correlation%20Overview%7CAlert%20Type%20Model%20Summary%7C_____2

https://docs.datadoghq.com/security/default_rules/

Azure AD usecases from Microsoft

https://learn.microsoft.com/en-us/entra/architecture/security-operations-user-accounts

Windows Events Attack Samples
https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES



Cortex XSOAR Playbooks

https://xsoar.pan.dev/docs/reference/playbooks/3-cx-desktop-app-supply-chain-attack


Sigma rules

https://github.com/SigmaHQ/sigma/tree/master

malware test file

eicar.com


Cyberark CEF log format fields

https://docs.cyberark.com/pam-self-hosted/Latest/en/Content/PTA/CEF-Based-Format-Definition.htm

Cyberark fields and usecases

https://docs.cyberark.com/pam-self-hosted/Latest/en/Content/PASIMP/Integrating-with-SIEM-Applications.htm


Zscalar DLP log fields

https://help.zscaler.com/zia/nss-feed-output-format-web-logs


DLP Digital Guardian log format

https://docs.devo.com/space/latest/349470828/dlp.digitalguardian

Cyberark different events

https://docs.cyberark.com/pam-self-hosted/Latest/en/Content/PASREF/Vault%20Audit%20Action%20Codes.htm

Office365 DLP

https://documentation.securonix.com/bundle/securonix-cloud-user-guide/page/content/data-dictionary/mapping-by-parser/detailed-mapping-for-office365-dlp.htm


Windows Security Usecases - Atomic red team

https://github.com/redcanaryco/atomic-red-team/tree/master/atomics

Cloudflare log format fields explanations

https://developers.cloudflare.com/logs/reference/log-fields/zone/http_requests/#edgeendtimestamp

https://docs.panther.com/data-onboarding/supported-logs/cloudflare


VPC Flow logs headers

https://panther.com/cyber-explained/aws-security-logging-vpc-flow-logs/

VPC Flow logs Samples

https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-records-examples.html

Endpoint Detection & Response (EDR) Splunk usecases

https://lantern.splunk.com/Data_Descriptors/Endpoint_detection_and_response_(EDR)_data

GuardDuty retired findings

https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_finding-types-retired.html#exfiltration-s3-objectreadunusual

Azure Monitor log field descriptions

https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log-schema

Prisma Cloud log fields

https://docs.prismacloud.io/en/classic/cspm-admin-guide/manage-prisma-cloud-administrators/view-audit-logs


Google Workspace Events list

https://cloud.google.com/chronicle/docs/ingestion/default-parsers/collect-workspace-logs
