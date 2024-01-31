# CodeNerve.github.io
Terminal based portfolio website for CodeNerve

## Custom domains and GitHub Pages configuration
- Order your dns name from your favorite registrar. In this case the domain is registered via https://porkbun.com
    - Create A records, point your apex domain to the IP addresses for GitHub Pages in https://porkbun.com/account/domainsSpeedy?fo=1&oid=5117993
        ```
        185.199.108.153
        185.199.109.153
        185.199.110.153
        185.199.111.153
        ```
    - Porkbun also asked me to add the github username during the above additions, so i added roupasz.github.io
- In the repo [settings](https://github.com/roupasz/roupasz.github.io/settings/pages), add the newly registered dns and allow Github to do the appropriate checks and page builds.
- After successful checks, Github will create a CNAME file and your site will be available in the new endpoint, depending on the propagation time.