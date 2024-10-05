# xc-acme-challenge-retriever

For HTTP LBs configured with Automatic Certificate where XC does not manage the DNS domain (and therefore can't fully automate the zone for the ACME DNS-01 challenge, a convenient way to query the XC API to retrieve all the existing ACME challenge records is provided by this script.

You will need your tenant host, the namespace you want to query, and an API Token (which can be generated in the Administration section under Credentials). These can be set as environmental variables or specified at the prompt.

To use, run the clone this repo and run the script and answer the questions.
