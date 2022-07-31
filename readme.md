# EDA Sample: Passwordless Authentication using MQTT

A sample of Event-Driven Architecture (EDA) that implements a user identity system (called DigiSelf) and leverages events using an MQTT based implementation. And all of these are showcased using a passwordless authentication flow.

<br/>

## Containers

The concept of _container_ is taken from C4 Model terminology, representing the main services that are part of the architecture (and deployment).
In this case, we have:

| container      | description |
| -------------- | ----------- |
| `gmqtt`        | A snapshot (commit 9b6e597) of [gmqtt](https://github.com/DrmagicE/gmqtt). |
| `digiself_svc` | The back-end side of DigiSelf. |
| `digiself_ui`  | The front-end side of DigiSelf. |
| `audit_svc`    | The audit service that captures and store the user relevant and related sensitive actions. |

<br/>
