---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor-model](./api-extractor-model.md) &gt; [ApiModel](./api-extractor-model.apimodel.md) &gt; [tryGetPackageByName](./api-extractor-model.apimodel.trygetpackagebyname.md)

## ApiModel.tryGetPackageByName() method

Efficiently finds a package by the NPM package name.

<b>Signature:</b>

```typescript
tryGetPackageByName(packageName: string): ApiPackage | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  packageName | <code>string</code> |  |

<b>Returns:</b>

`ApiPackage | undefined`

## Remarks

If the NPM scope is omitted in the package name, it will still be found provided that it is an unambiguous match. For example, it's often convenient to write `{@link node-core-library#JsonFile}` instead of `{@link @microsoft/node-core-library#JsonFile}`<!-- -->.
