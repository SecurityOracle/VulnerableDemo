# Node.js Vulnerable Demo App

This demonstrates a simple Node.js application that has vulnerabilities that can be detected and mitigated using Security Oracle.

## Push to CF using custom buildpack

1. Install CF CLI
2. Run `cf push -b https://github.com/SecurityOracle/nodejs-buildpack` or `cf push -b https://github.com/SecurityOracle/nodejs-buildpack "your-app-name"` if you don't want to use a manifest.yml file
3. You should be told your app is vulnerable with a link to the report