# Overview
Bitlocker provides disk encryption for devices. Disk encryption is called out as a requirement by most frameworks and provides strong protections against unauthroized access to disk contents without some sort of authorization. Typical controls either prevent the disk from being 'read' or decrypted until a preboot key is input or there are checks to ensure the hardware or storage has not been tampered with.

Bitlocker can be implemented in a variety of ways including manually, with SCCM, with MBAM, or through Microsoft InTune. Each system has pros and cons and the choice of which to use depends on your organization. Some pros and cons will be listed below.

# Resources
* Microsoft Resources - https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/prepare-your-organization-for-bitlocker-planning-and-policies
* NSA Guidance - https://github.com/nsacyber/BitLocker-Guidance
* Bitlocker with SCCM - https://www.nianit.com/enable-bitlocker-existing-devices/
* Bitlocker with MBAM - https://msendpointmgr.com/2019/01/12/step-by-step-microsoft-mbam/
* Bitlocker with InTune - https://www.rebeladmin.com/2019/09/step-step-guide-enable-bitlocker-cloud-managed-windows-10-devices-using-microsoft-intune/
