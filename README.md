Splunk saved searches to be used for setting alerts on GCP security events.
The events are taken from the [Forseti default rules][1] and from the [Google Cloud Security Health Analytics][2].

Prerequisites:
* [Splunk Add-on for Google Cloud][3]
* Edit Source Type: google:gcp:pubsub:message for Indexed Extractions to json

[1]: https://forsetisecurity.org/docs/v2.0/configure/scanner/default-rules.html
[2]: https://cloud.google.com/security-command-center/docs/how-to-enable-security-health-analytics#viewing_scanner_findings
[3]: https://splunkbase.splunk.com/app/3088/
