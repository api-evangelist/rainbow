# Rainbow

Rainbow is a CPaaS platform from Alcatel-Lucent Enterprise (ALE) that lets developers enrich applications with chat, group chat, voice, video, file sharing, and telephony PBX features through more than 200 APIs, REST interfaces, and multi-language SDKs.

- **Website:** [openrainbow.com](https://www.openrainbow.com)
- **Developer Portal:** [developers.openrainbow.com](https://developers.openrainbow.com/)
- **Sign Up:** [hub.openrainbow.com](https://hub.openrainbow.com/)
- **GitHub:** [github.com/Rainbow-CPaaS](https://github.com/Rainbow-CPaaS)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Communications, CPaaS, Chat, Voice, Video, Telephony, Messaging, Collaboration, Unified Communications

## APIs

### Application Portal API
Register and manage Rainbow developer applications, configure OAuth clients, and perform administrative operations.

- **OpenAPI:** [openapi/rainbow-application-openapi.yml](openapi/rainbow-application-openapi.yml)

### Messaging API
Send and receive messages, manage conversations, and handle group chat bubbles.

- **OpenAPI:** [openapi/rainbow-messaging-openapi.yml](openapi/rainbow-messaging-openapi.yml)

### Contacts API
Search, list, and manage contacts and user presence in the Rainbow directory.

- **OpenAPI:** [openapi/rainbow-contacts-openapi.yml](openapi/rainbow-contacts-openapi.yml)

## SDKs

| SDK | Repository |
|---|---|
| Node.js | [Rainbow-Node-SDK](https://github.com/Rainbow-CPaaS/Rainbow-Node-SDK) |
| iOS | [Rainbow-iOS-SDK](https://github.com/Rainbow-CPaaS/Rainbow-iOS-SDK) |
| C# | [Rainbow-CSharp-SDK-Samples](https://github.com/Rainbow-CPaaS/Rainbow-CSharp-SDK-Samples) |
| CLI | [Rainbow-CLI-SDK](https://github.com/Rainbow-CPaaS/Rainbow-CLI-SDK) |

## Artifacts

### OpenAPI Specifications
| File | Description |
|---|---|
| [openapi/rainbow-application-openapi.yml](openapi/rainbow-application-openapi.yml) | Application Portal API |
| [openapi/rainbow-messaging-openapi.yml](openapi/rainbow-messaging-openapi.yml) | Messaging API |
| [openapi/rainbow-contacts-openapi.yml](openapi/rainbow-contacts-openapi.yml) | Contacts API |

### JSON Schema
| File | Description |
|---|---|
| [json-schema/rainbow-message-schema.json](json-schema/rainbow-message-schema.json) | Message entity schema |
| [json-schema/rainbow-contact-schema.json](json-schema/rainbow-contact-schema.json) | Contact entity schema |

### JSON Structure
| File | Description |
|---|---|
| [json-structure/rainbow-message-structure.json](json-structure/rainbow-message-structure.json) | Messaging entities structure |

### JSON-LD
| File | Description |
|---|---|
| [json-ld/rainbow-context.jsonld](json-ld/rainbow-context.jsonld) | Linked data context mapping |

### Examples
| File | Description |
|---|---|
| [examples/rainbow-send-message-example.json](examples/rainbow-send-message-example.json) | Send message example |
| [examples/rainbow-search-contacts-example.json](examples/rainbow-search-contacts-example.json) | Search contacts example |
| [examples/rainbow-get-oauth-token-example.json](examples/rainbow-get-oauth-token-example.json) | OAuth token example |

### Rules
| File | Description |
|---|---|
| [rules/rainbow-rules.yml](rules/rainbow-rules.yml) | Spectral ruleset for Rainbow API conventions |

### Capabilities
| File | Description |
|---|---|
| [capabilities/communications-platform.yaml](capabilities/communications-platform.yaml) | Unified communications platform workflow |
| [capabilities/shared/messaging.yaml](capabilities/shared/messaging.yaml) | Shared Messaging API definition |
| [capabilities/shared/contacts.yaml](capabilities/shared/contacts.yaml) | Shared Contacts API definition |

### Vocabulary
| File | Description |
|---|---|
| [vocabulary/rainbow-vocabulary.yml](vocabulary/rainbow-vocabulary.yml) | CPaaS domain vocabulary |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
