# Infrastructure

Infrastructure as Code (IAC) lives here. 
- All servers must be setup and maintained using only this directory.
- All secret keys must be injected via Vault (no passwords or environmental variables should be initialized from source
code).
- The production server uses different cloud accounts than staging or development servers. Be careful spinning up your
own development infrastructure, it could be expensive. Any costs incurred are your own responsibility.