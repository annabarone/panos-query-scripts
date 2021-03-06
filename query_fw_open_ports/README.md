# Open Port Query Solution

This solution queries a NGFW to determine which rules allow traffic from an untrusted zone on the firewall.
To use this solution, run the _Query NGFW for Open Ports_ workflow, which will:

    * Capture the NGFW's existing zones
    * Query the NGFW's rulebase for rules allowing traffic from the chosen zone
    * Output the results in a report

With the results, a user can view the specific application and services that are being allowed 
through the firewall and can, if needed, correlate these to port numbers. 


> This solution is run using Panhandler. For help with Panhandler set-up and use, please reference the 
> [Quickstart Guide](https://live.paloaltonetworks.com/t5/skillet-tools/install-and-get-started-with-panhandler/ta-p/307916) 
> in the Live community. 

## Support Policy
The code and templates in the repo are released under an as-is, best effort,
support policy. These scripts should be seen as community supported and
Palo Alto Networks will contribute our expertise as and when possible.
We do not provide technical support or help in using or troubleshooting the
components of the project through our normal support options such as
Palo Alto Networks support teams, or ASC (Authorized Support Centers)
partners and backline support options. The underlying product used
(the VM-Series firewall) by the scripts or templates are still supported,
but the support is only for the product functionality and not for help in
deploying or using the template or script itself. Unless explicitly tagged,
all projects or work posted in our GitHub repository
(at https://github.com/PaloAltoNetworks) or sites other than our official
Downloads page on https://support.paloaltonetworks.com are provided under
the best effort policy.
