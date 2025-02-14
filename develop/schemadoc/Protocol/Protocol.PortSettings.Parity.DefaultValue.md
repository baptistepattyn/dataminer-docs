---
uid: Protocol.PortSettings.Parity.DefaultValue
---

# DefaultValue element

Specifies the default parity.

## Type

[EnumPortSettingsParity](xref:Protocol-EnumPortSettingsParity)

## Parent

[Parity](xref:Protocol.PortSettings.Parity)

## Remarks

Each time a user adds an element using the element wizard, the parity will by default be set to this value.

> [!NOTE]
> For an SNMPv3 connection, this tag can be used to specify the default authentication algorithm (e.g. "SHA128").
>
> The following authentication algorithms are supported:
>
> - MD5
> - SHA128
> - SHA224 (Since DataMiner 9.6.13 (RN 23586)).
> - SHA256 (Since DataMiner 9.6.13 (RN 23586)).
> - SHA384 (Since DataMiner 9.6.13 (RN 23586)).
> - SHA512 (Since DataMiner 9.6.13 (RN 23586)).
>
> If no default value is specified, the most secure option will be the default.
