# harden-notes

CIS Benchmark
To patch current vuln issues

now AMIs stored/uploaded into s3?

Golden AMI
	With custom requirements

Base AMI?
	Ubuntu? Which version?
	
EC2 Instance
Manager?
Pipeline?

CIS coverage?
	Scope?
	
OpenScap
	https://aws.amazon.com/blogs/security/how-to-automate-scap-testing-with-aws-systems-manager-and-security-hub/
	Ansible SCAP?

CIS benchmark or DISA-STIG?
	
Ubuntu Security Guide (USG)
- available on Ubuntu 20.04 LTS
- https://ubuntu.com/blog/cis-security-compliance-usg
- Can also create a custom profile based on CIS
- recomended to run on test/dev env instead of prod env
- Only available in Pro??
	

With Ubuntu Security Guide
- you can customize (tailor) the CIS profile; select the CIS rules to comply with.
- you can select a specific version of the CIS benchmark, i.e., a tooling upgrade doesn’t need to break scheduled scans that target a specific benchmark version.
- teams can standardize on a profile by storing it in a hard-wired location, preventing the case of different people accidentally scanning or complying with different profiles or versions.
- the same experience applies whether scanning for the CIS benchmark, DISA-STIG and any other profiles made available in the future.
- last but not least, you use a consistent interface across Ubuntu releases.
	
