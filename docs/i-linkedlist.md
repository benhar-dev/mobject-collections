# I_LinkedList Interface

## Definition

|             |                                                                                                                                                                 |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Namespace   | mobject-collections                                                                                                                                             |
| Library     | mobject-collections                                                                                                                                             |
| Inheritance | [I_EventEmitter](https://benhar-dev.github.io/mobject-events/#/i-event-emitter), [I_Disposable](https://benhar-dev.github.io/mobject-disposable/#/i-disposable) |
| Implements  | I_LinkedList                                                                                                                                                    |

## Remarks

The I_LinkedList interface contains common methods and properties found on a basic implementation of a linked list.

## Methods

### AddAfter(After, Value)

#### Parameters

| Parameters | Datatype                                |
| ---------- | --------------------------------------- |
| After      | [I_LinkedListNode](i-linkedlistnode.md) |
| Value      | ANY                                     |

#### Return

N/A

### AddBefore(Before, Value)

#### Parameters

| Parameters | Datatype                                |
| ---------- | --------------------------------------- |
| Before     | [I_LinkedListNode](i-linkedlistnode.md) |
| Value      | ANY                                     |

#### Return

N/A

### AddFirst(Value)

#### Parameters

| Parameters | Datatype |
| ---------- | -------- |
| Value      | ANY      |

#### Return

N/A

### AddLast(Value)

#### Parameters

| Parameters | Datatype |
| ---------- | -------- |
| Value      | ANY      |

#### Return

N/A

### Clear()

#### Parameters

N/A

#### Return

N/A

### CopyTo(Destination)

#### Parameters

| Parameters  | Datatype |
| ----------- | -------- |
| Destination | ANY      |

#### Return

| Datatype |
| -------- |
| BOOL     |

### CopyToLocation(Destination)

#### Parameters

| Parameters      | Datatype |
| --------------- | -------- |
| Destination     | PVOID    |
| DestinationSize | UDINT    |

#### Return

| Datatype |
| -------- |
| BOOL     |

### Find(Value)

#### Parameters

| Parameters | Datatype |
| ---------- | -------- |
| Value      | ANY      |

#### Return

| Datatype                                |
| --------------------------------------- |
| [I_LinkedListNode](i-linkedlistnode.md) |

### FindLast(Value)

#### Parameters

| Parameters | Datatype |
| ---------- | -------- |
| Value      | ANY      |

#### Return

| Datatype                                |
| --------------------------------------- |
| [I_LinkedListNode](i-linkedlistnode.md) |

### GetEnumerator()

#### Parameters

N/A

#### Return

| Datatype                                      |
| --------------------------------------------- |
| [I_ForwardEnumerator](i-forwardenumerator.md) |

### Remove(Value)

#### Parameters

| Parameters | Datatype |
| ---------- | -------- |
| Value      | ANY      |

#### Return

N/A

### RemoveFirst()

#### Parameters

N/A

#### Return

N/A

### RemoveLast()

#### Parameters

N/A

#### Return

N/A

## Properties

### Count

#### Return

| Datatype |
| -------- |
| ULINT    |

### First

#### Return

| Datatype         |
| ---------------- |
| I_LinkedListNode |

### Last

#### Return

| Datatype         |
| ---------------- |
| I_LinkedListNode |
