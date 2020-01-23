---
name: Distribution Support Request
about: Requests suppoort for a new distribution
title: "Distribution Support Request"
labels: Distribution-Request
assignees: ''

---

# Details of the Distribution

- Name of the Distribution: 
- Version of the Distribution:
- Processor Architecture (One per request): 
- [ ] **Required** - An issues has been filed to create a Docker image in https://github.com/powershell/powershell-docker
- The following is a requirement for supporting a distribution **without exception.**
  - [ ] The version and architecture of the Distribution is [supported by .NET Core](https://github.com/dotnet/core/blob/master/release-notes/3.0/3.0-supported-os.md#linux).
- The following are requirements for supporting a distribution.
  Please write a justification for any exception where these criteria are not met and 
  the PowerShell comittee will review the request.
  - [ ] The version of the Distribution is supported for at least one year.
  - [ ] The version of the Distribution is not an [interim release](https://ubuntu.com/about/release-cycle) or equivalent.

## Progress - For PowerShell Team **ONLY**

- [ ] Docker image created
- [ ] Docker image published
- [ ] Distribution tested
- [ ] Lifecycle updated
- [ ] Documentation Updated
