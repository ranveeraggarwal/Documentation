---
TAGS:
---
## Description

class [PointerInfoPre](/classes/3.0/PointerInfoPre) extends [PointerInfoBase](/classes/3.0/PointerInfoBase)

This class is used to store pointer related info for the onPrePointerObservable event.

Set the skipOnPointerObservable property to true if you want the engine to stop any process after this event is triggered, even not calling onPointerObservable

## Constructor

## new [PointerInfoPre](/classes/3.0/PointerInfoPre)(type, event, MouseWheelEvent, localX, localY)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | type | number |   
 | event | PointerEvent or MouseWheelEvent |   
 | localX | any |   
## Members

### localPosition : [Vector2](/classes/3.0/Vector2)



### skipOnPointerObservable : boolean



