<div align="center">

# Naming Conventions

### Development Standards & Code Structure Guidelines

Consistent naming patterns designed to improve maintainability, readability and long-term scalability across the Zorvax ecosystem.

<br>

![Standard](https://img.shields.io/badge/Standard-Official-A3FF12?style=for-the-badge)
![Architecture](https://img.shields.io/badge/Architecture-Modular-1A1F29?style=for-the-badge)
![Style](https://img.shields.io/badge/Style-snake__case-0B0F14?style=for-the-badge)
![Framework](https://img.shields.io/badge/Framework-Zorvax%20Core-A3FF12?style=for-the-badge)

</div>

---

# Overview

Zorvax Core follows strict naming conventions to ensure consistency and organization across all framework resources, modules and internal systems.

Standardized naming patterns improve:

- maintainability
- readability
- scalability
- developer onboarding
- debugging efficiency
- ecosystem consistency

All official Zorvax resources and modules must follow the conventions described below.

---

# Resource Naming

All framework resources must use the official `zvx_` prefix.

## Pattern

```txt
zvx_resource_name
````

---

## Examples

```txt
zvx_core
zvx_inventory
zvx_identity
zvx_multichar
zvx_dispatch
```

---

# Variable Naming

All variables must follow the `snake_case` convention.

This standard improves readability and consistency across both client-side and server-side code.

## Pattern

```lua
local player_data
local vehicle_entity
local inventory_items
```

---

## Recommended

✔ Descriptive variable names
✔ Context-aware naming
✔ Readable structures
✔ Consistent formatting

---

## Avoid

✘ Generic variable names
✘ Single-letter variables
✘ Mixed naming styles
✘ Unclear abbreviations

---

# Event Naming

All events must follow the official framework event structure.

## Pattern

```txt
zvx:module:event
```

---

## Examples

```txt
zvx:player:loaded
zvx:inventory:updated
zvx:banking:transaction
zvx:garage:storeVehicle
```

---

# Event Guidelines

Event naming should be:

* descriptive
* modular
* predictable
* readable
* scalable

Avoid:

* duplicated event names
* generic identifiers
* inconsistent module structures

---

# Function Naming

Functions should use descriptive and maintainable naming patterns.

## Recommended

```lua
GetPlayerData()
HasPermission()
CreateCharacter()
SaveInventory()
```

---

## Avoid

```lua
Get()
Data()
TestFunction()
DoStuff()
```

---

# File & Folder Structure

Folder and file names should remain consistent with the modular architecture philosophy.

## Recommended Structure

```txt
modules/
├── callbacks/
├── players/
├── permissions/
├── events/
└── database/
```

---

# Internal Standards

Zorvax Core development standards prioritize:

| Principle       | Description                      |
| --------------- | -------------------------------- |
| Consistency     | Unified naming patterns          |
| Readability     | Clear and understandable code    |
| Scalability     | Structure prepared for expansion |
| Maintainability | Easier long-term maintenance     |
| Organization    | Predictable development flow     |

---

# Development Philosophy

Naming conventions are not only visual standards.

They are part of the architectural foundation of the framework and directly impact:

* code quality
* debugging efficiency
* onboarding speed
* project scalability
* long-term maintainability

Every official Zorvax module should follow these standards consistently.

---

<div align="center">

### Zorvax Core

Structured for Scalable Development

</div>