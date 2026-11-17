# Security Policy

## Project Status

Primer is a research project released publicly "as-is" for research and educational purposes. It is not actively maintained, and there is no guarantee of ongoing updates, support, or security fixes. The maintainers may review reports or accept contributions occasionally, at their discretion.

## Reporting a Vulnerability

If you believe you have found a security vulnerability in Primer, please report it privately by emailing:

**security@wharton.upenn.edu**

Helpful details to include:

- A description of the vulnerability
- Steps to reproduce the issue
- Potential impact
- Any suggested fixes or mitigations

Please note:

- We do not commit to acknowledging, responding to, or resolving reports within any particular time frame, or at all.
- We do not guarantee that a fix will be developed or released.
- If you have a fix, you are welcome to submit it as a pull request after the issue has been reported privately. Pull requests may or may not be reviewed or merged.
- We take no responsibility for how the product is used.

We ask that you act in good faith to avoid privacy violations, destruction of data, and interruption or degradation of services, and that you not access or modify data that does not belong to you.

## Using Primer Safely

Because Primer is experimental and not actively maintained, anyone deploying it is responsible for evaluating and securing their own deployment. Recommended practices:

- **Keep dependencies updated:** Primer's dependencies may become outdated over time. Review and update them before deploying.
- **Secure API keys:** Never commit API keys or sensitive credentials to version control, and never expose them in client-side code or logs.
- **Use environment variables:** Store sensitive configuration in environment variables.
- **Review external content:** Primer can load external experience configurations and assets. Review, validate, and sanitize them before use.
- **Validate file uploads:** When using file upload features, validate file types and sizes appropriately for your use case.
- **Use secure connections:** Use HTTPS and secure WebSocket connections (WSS) in production.
- **Access control:** Implement appropriate access controls for your deployment.

## Disclaimer

Primer is provided without warranty of any kind, as described in the project's license. Use it at your own risk.
