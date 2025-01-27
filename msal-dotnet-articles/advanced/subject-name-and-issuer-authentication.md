---
title: Certificate Subject Name and Issuer (SNI) authentication
---

# Certificate Subject Name and Issuer (SNI) authentication

Certificate Subject Name and Issuer (SNI) based authentication is currently available only for Microsoft internal (first-party) applications. External (third-party) apps cannot use SNI because SNI is based on the assumption that the certificate issuer is the same as the tenant owner. This can be guaranteed for some first-party tenants, but not for third-party. So there are no plans to bring SNI to third-party apps. For more details about this feature and code examples see [this SNI issue](https://github.com/AzureAD/microsoft-authentication-library-for-python/issues/60) and [a wiki page](https://aadwiki.windows-int.net/index.php?title=Subject_Name_and_Issuer_Authentication).
