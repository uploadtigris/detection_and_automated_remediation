# detection_and_automated_remediation

An EventBridge and Lambda pipeline that reacts to findings. A public S3 bucket triggers auto-remediation, alongside detection rules for root-account usage, console logins from new locations, and security-group changes. The write-up explains which findings I auto-remediate, why, and the failure modes of getting it wrong.
