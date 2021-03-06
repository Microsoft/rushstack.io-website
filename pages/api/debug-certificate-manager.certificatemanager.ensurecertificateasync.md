---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/debug-certificate-manager](./debug-certificate-manager.md) &gt; [CertificateManager](./debug-certificate-manager.certificatemanager.md) &gt; [ensureCertificateAsync](./debug-certificate-manager.certificatemanager.ensurecertificateasync.md)

## CertificateManager.ensureCertificateAsync() method

Get a dev certificate from the store, or optionally, generate a new one and trust it if one doesn't exist in the store.

<b>Signature:</b>

```typescript
ensureCertificateAsync(canGenerateNewCertificate: boolean, terminal: Terminal): Promise<ICertificate>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  canGenerateNewCertificate | boolean |  |
|  terminal | [Terminal](./node-core-library.terminal.md) |  |

<b>Returns:</b>

Promise&lt;[ICertificate](./debug-certificate-manager.icertificate.md)<!-- -->&gt;

