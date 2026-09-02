---
title: NPC Scheduling Improvements
description: Updated NPC schedules and added inn sleeping behavior and schedule events.
pubDate: 2026-09-02
draft: false
language: en
translation: npc-scheduling
---

Updated NPC scheduling.

## Sleeping at the Inn

NPCs without homes now move to rooms on the second floor of the inn when it is time to sleep.

![NPCs sleeping in rooms on the second floor of the inn](../../../assets/blog/npc-scheduling-inn-sleep.png)

## Schedule Events

Added events such as `breakfast` and `dinner` to make schedules easier to write. NPC schedules can specify an event name instead of a time.

The following is part of Wick's `schedule.json` file.

```json
{
  "schedule": [
    {
      "at": "dinner",
      "pos": [-1451.7, 1.3, 4750.3],
      "rotation": 90.0,
      "floor_level": 0,
      "label": "eating dinner on the inn's ground floor",
      "action": "chair",
      "object_id": 42
    },
    {
      "at": "breakfast",
      "pos": [-1451.7, 1.3, 4750.3],
      "rotation": 90.0,
      "floor_level": 0,
      "label": "eating breakfast on the inn's ground floor",
      "action": "chair",
      "object_id": 42
    }
  ]
}
```
