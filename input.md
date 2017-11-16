# Input field

### Main field types

Regular, bordered fields should be used for flows where conversion plays a big part, e.g. KCO, KP and Sofort. Borderless fields should be used for “home-base” interfaces such as the Klarna App and desktop interface, internal interfaces and styleguides.

| Field | Guideline |
| :--- | :--- |
| ![](/assets/Field@1x.png) | Use regular fields for **conversion sensitive** flows. |
| ![](/assets/Input@1x.png) | Use borderless fields for **in-product** flows. |

### Variations

| Field | Guideline |
| :--- | :--- |
| ![]() | On background fields - same as regular fields (all states) but without the border |
| ![]() | Minimal fields - used in small-action cases where error handling and conversion isn't relevant, e.g. search bars and chat messaging |

### Stacked fields

### Interactive states

### Error handling
Error and warning fields are used to respond to a user’s input when it is invalid, seems off or is missing.

Use **error** fields when:
1. The input is invalid and *must be changed*.
2. A field which must be filled in is left empty.

Use **warning** fields when:
1. The input seems off, but the user *can still continue* with it.
2. A field which should, but doesn’t have to, be filled in is left empty.

### Autocompletion
Autofilled fields are used for when we autocomplete an active input by the user, with saved browser details.

**Do:** Use autofilled fields to complete an input series.
**Don't:** Use autofilled fields for content *prefilled* by Klarna.
