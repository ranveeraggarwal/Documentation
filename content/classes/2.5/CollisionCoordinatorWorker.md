---
ID_PAGE: 25194
PG_TITLE: CollisionCoordinatorWorker
PG_VERSION: 2.1
TAGS:
    - Collision
---
## Description

class [CollisionCoordinatorWorker](/classes/2.5/CollisionCoordinatorWorker)



## Constructor

## new [CollisionCoordinatorWorker](/classes/2.5/CollisionCoordinatorWorker)()


## Members

### static SerializeMesh : (mesh: [AbstractMesh](/classes/2.5/AbstractMesh)) =&gt; SerializedMesh



### static SerializeGeometry : (geometry: [Geometry](/classes/2.5/Geometry)) =&gt; SerializedGeometry



### onMeshUpdated : (mesh: [AbstractMesh](/classes/2.5/AbstractMesh)) =&gt; void



### onGeometryUpdated : (geometry: [Geometry](/classes/2.5/Geometry)) =&gt; void



## Methods

### getNewPosition(position, velocity, collider, maximumRetry, excludedMesh, onNewPosition, collisionIndex) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | position | [Vector3](/classes/2.5/Vector3) |     
 | velocity | [Vector3](/classes/2.5/Vector3) |     
 | collider | [Collider](/classes/2.5/Collider) |     
 | maximumRetry | number |     
 | excludedMesh | [AbstractMesh](/classes/2.5/AbstractMesh) |     
 | onNewPosition | (collisionIndex: number, newPosition: [Vector3](/classes/2.5/Vector3), collidedMesh: [AbstractMesh](/classes/2.5/AbstractMesh)) =&gt; void |     
### init(scene) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | scene | [Scene](/classes/2.5/Scene) |     

### destroy() &rarr; void


### onMeshAdded(mesh) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | mesh | [AbstractMesh](/classes/2.5/AbstractMesh) |     

### onMeshRemoved(mesh) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | mesh | [AbstractMesh](/classes/2.5/AbstractMesh) |     

### onGeometryAdded(geometry) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | geometry | [Geometry](/classes/2.5/Geometry) |     

### onGeometryDeleted(geometry) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | geometry | [Geometry](/classes/2.5/Geometry) |     

