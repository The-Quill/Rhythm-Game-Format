#Spec


---
#`beat`:

A single beat.

Has properties:

 - `time_start`
 - `column`

#`long_beat`:

A long / held in beat.

Has properties:

 - `time_start`
 - `time_end`
 - `column`

#`linked_beat`:

A beat that is linked to another, they must have an identical start or end:

Has properties:

 - `linked` (requires one):
  - `linked_start`
  - `linked_end`
 - `duration`
 - `column`

#`special_beat`:

For special features such as gui effects. Same spec as `beat`, but with a `effect_name` property.

Has properties:

 - `time_start`
 - `column`
 - `effect_name`

#`special_long_beat`:

For special features such as gui effects. Same spec as `long_beat`, but with a `effect_name` property.

Has properties:

 - `time_start`
 - `time_end`
 - `column`
 - `effect_name`

#`special_linked_beat`:

For special features such as gui effects. Same spec as `linked_beat`, but with a `effect_name` property.

Has properties:
 - `linked` (requires one):
  - `linked_start`
  - `linked_end`
 - `duration`
 - `column`
 - `effect_name`