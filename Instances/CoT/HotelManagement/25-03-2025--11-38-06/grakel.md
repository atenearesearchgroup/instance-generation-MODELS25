# Adj, edge, label 
```
Adj1-boundary.soil: [[0, 1, 1, 1, 1, 0, 0, 0, 0, 0], [1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 0, 0, 1, 0, 0, 0, 0, 0], [1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 1, 1, 1, 1, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels1-boundary.soil: {0: 'Booking', 1: 'Customer', 2: 'Bill', 3: 'Bill', 4: 'RoomReservation', 5: 'Room', 6: 'Room', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'FreeRoomTypesDTO'}

Edges1-boundary.soil: [(0, 1), (0, 4), (0, 2), (0, 3), (4, 5), (4, 6), (4, 7), (4, 8), (2, 4)]

Adj1-invalid.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 0, 0, 1], [0, 1, 0, 1, 1, 1, 1, 1, 1], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0]]

Labels1-invalid.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'Bill'}

Edges1-invalid.soil: [(1, 0), (1, 2), (1, 8), (2, 3), (2, 4), (2, 5), (2, 6), (2, 7), (8, 2)]

Adj1-edge.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 1, 0], [0, 1, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0, 0, 0], [0, 1, 0, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0, 0], [0, 1, 0, 0, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels1-edge.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'RoomReservation', 5: 'Room', 6: 'Room', 7: 'Room', 8: 'RoomExtra', 9: 'RoomExtra', 10: 'RoomExtra', 11: 'Bill', 12: 'Bill', 13: 'Bill', 14: 'FreeRoomTypesDTO'}

Edges1-edge.soil: [(1, 0), (1, 2), (1, 3), (1, 4), (2, 5), (3, 6), (4, 7), (2, 8), (3, 9), (4, 10), (11, 2), (12, 3), (13, 4), (1, 11), (1, 12), (1, 13)]

Adj1-complex.soil: [[0, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0], [1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 0, 0, 1, 1, 0, 1, 1, 0, 1, 0, 0, 0], [1, 0, 0, 0, 0, 0, 1, 0, 0, 1, 0, 1, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels1-complex.soil: {0: 'Booking', 1: 'Customer', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'Room', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'RoomExtra', 10: 'Bill', 11: 'Bill', 12: 'FreeRoomTypesDTO', 13: 'FreeRoomTypesDTO'}

Edges1-complex.soil: [(0, 1), (0, 2), (0, 3), (0, 10), (0, 11), (2, 4), (2, 5), (2, 7), (2, 8), (10, 2), (3, 6), (3, 9), (11, 3)]

Adj1-baseline.soil: [[0, 1, 1, 0, 0, 0, 1, 0], [1, 0, 0, 0, 0, 0, 0, 0], [1, 0, 0, 1, 1, 1, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0]]

Labels1-baseline.soil: {0: 'Booking', 1: 'Customer', 2: 'RoomReservation', 3: 'Room', 4: 'RoomExtra', 5: 'RoomExtra', 6: 'Bill', 7: 'FreeRoomTypesDTO'}

Edges1-baseline.soil: [(0, 1), (0, 6), (0, 2), (2, 3), (2, 4), (2, 5), (6, 2)]

Adj2-boundary.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 1, 0, 0, 0, 0, 0, 1], [0, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 1], [0, 1, 1, 0, 0, 1, 1, 1, 1, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 1], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 1], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 1], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 1], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 1, 1, 1, 1, 0, 0]]

Labels2-boundary.soil: {0: 'Customer', 1: 'Booking', 2: 'Bill', 3: 'Bill', 4: 'RoomReservation', 5: 'Room', 6: 'Room', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'FreeRoomTypesDTO', 10: 'RoomReservation'}

Edges2-boundary.soil: [(1, 0), (1, 4), (1, 2), (1, 3), (4, 5), (4, 6), (4, 7), (4, 8), (2, 4), (1, 10), (10, 5), (10, 6), (10, 7), (10, 8), (3, 10)]

Adj2-invalid.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 1, 1, 1, 1], [0, 1, 0, 1, 1, 1, 1, 1, 1, 1], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0]]

Labels2-invalid.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'RoomExtra', 5: 'RoomExtra', 6: 'Bill', 7: 'Bill', 8: 'Bill', 9: 'Bill'}

Edges2-invalid.soil: [(1, 0), (1, 2), (2, 3), (2, 4), (2, 5), (6, 2), (7, 2), (8, 2), (9, 2), (1, 6), (1, 7), (1, 8), (1, 9)]

Adj2-edge.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 1, 1, 0], [0, 1, 0, 0, 1, 0, 1, 0, 1, 0, 0], [0, 1, 0, 0, 0, 1, 0, 1, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels2-edge.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'Bill', 9: 'Bill', 10: 'FreeRoomTypesDTO'}

Edges2-edge.soil: [(1, 0), (1, 2), (1, 3), (2, 4), (3, 5), (2, 6), (3, 7), (8, 2), (9, 3), (1, 8), (1, 9)]

Adj2-complex.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0], [0, 1, 0, 0, 1, 0, 1, 1, 0, 0, 1, 0, 0, 0], [0, 1, 0, 0, 0, 1, 0, 0, 1, 1, 0, 1, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels2-complex.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'RoomExtra', 10: 'Bill', 11: 'Bill', 12: 'FreeRoomTypesDTO', 13: 'FreeRoomTypesDTO'}

Edges2-complex.soil: [(1, 0), (1, 2), (1, 3), (2, 4), (3, 5), (2, 6), (2, 7), (3, 8), (3, 9), (10, 2), (11, 3), (1, 10), (1, 11)]

Adj2-baseline.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 1, 0, 0, 0], [0, 1, 0, 0, 1, 0, 1, 1, 0, 0, 0], [0, 1, 0, 0, 0, 1, 0, 0, 0, 1, 1], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0]]

Labels2-baseline.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'Bill', 8: 'FreeRoomTypesDTO', 9: 'RoomExtra', 10: 'Bill'}

Edges2-baseline.soil: [(1, 0), (1, 2), (1, 3), (1, 7), (2, 4), (3, 5), (2, 6), (3, 9), (7, 2), (10, 3)]

Adj3-boundary.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 1, 1, 1, 1, 1, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels3-boundary.soil: {0: 'Customer', 1: 'Booking', 2: 'Bill', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'FreeRoomTypesDTO'}

Edges3-boundary.soil: [(1, 0), (1, 3), (1, 2), (3, 4), (3, 5), (3, 6), (3, 7), (3, 8), (2, 3)]

Adj3-invalid.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 1, 1, 1], [0, 1, 0, 1, 1, 1, 1, 1, 1], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0]]

Labels3-invalid.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'RoomExtra', 5: 'RoomExtra', 6: 'Bill', 7: 'Bill', 8: 'Bill'}

Edges3-invalid.soil: [(1, 0), (1, 2), (2, 3), (2, 4), (2, 5), (6, 2), (7, 2), (8, 2), (1, 6), (1, 7), (1, 8)]

Adj3-edge.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 1, 1, 0], [0, 1, 0, 0, 1, 0, 1, 0, 1, 0, 0], [0, 1, 0, 0, 0, 1, 0, 1, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels3-edge.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'Bill', 9: 'Bill', 10: 'FreeRoomTypesDTO'}

Edges3-edge.soil: [(1, 0), (1, 2), (1, 3), (2, 4), (3, 5), (2, 6), (3, 7), (8, 2), (9, 3), (1, 8), (1, 9)]

Adj3-complex.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0], [0, 1, 0, 0, 1, 0, 1, 1, 0, 0, 1, 0, 0, 0], [0, 1, 0, 0, 0, 1, 0, 0, 1, 1, 0, 1, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels3-complex.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'RoomExtra', 10: 'Bill', 11: 'Bill', 12: 'FreeRoomTypesDTO', 13: 'FreeRoomTypesDTO'}

Edges3-complex.soil: [(1, 0), (1, 2), (1, 3), (2, 4), (3, 5), (2, 6), (2, 7), (3, 8), (3, 9), (10, 2), (11, 3), (1, 10), (1, 11)]

Adj3-baseline.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 1, 1, 0], [0, 1, 0, 0, 1, 0, 1, 0, 1, 0, 0], [0, 1, 0, 0, 0, 1, 0, 1, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels3-baseline.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'Bill', 9: 'Bill', 10: 'FreeRoomTypesDTO'}

Edges3-baseline.soil: [(1, 0), (1, 2), (1, 3), (1, 8), (1, 9), (2, 4), (3, 5), (2, 6), (3, 7), (8, 2), (9, 3)]

Adj4-boundary.soil: [[0, 1, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0], [0, 1, 1, 0, 1, 1, 0], [0, 0, 0, 1, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0]]

Labels4-boundary.soil: {0: 'Customer', 1: 'Booking', 2: 'Bill', 3: 'RoomReservation', 4: 'Room', 5: 'RoomExtra', 6: 'FreeRoomTypesDTO'}

Edges4-boundary.soil: [(1, 0), (1, 3), (1, 2), (3, 4), (3, 5), (2, 3)]

Adj4-invalid.soil: [[0, 1, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 1], [0, 1, 0, 0, 1, 1, 0, 1], [0, 1, 0, 0, 1, 0, 1, 1], [0, 0, 1, 1, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0], [0, 1, 1, 1, 0, 0, 0, 0]]

Labels4-invalid.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'RoomExtra', 6: 'RoomExtra', 7: 'Bill'}

Edges4-invalid.soil: [(1, 0), (1, 2), (1, 3), (2, 4), (3, 4), (2, 5), (3, 6), (7, 2), (7, 3), (1, 7)]

Adj4-edge.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 1, 0], [0, 1, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0, 0, 0], [0, 1, 0, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0, 0], [0, 1, 0, 0, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels4-edge.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'RoomReservation', 5: 'Room', 6: 'Room', 7: 'Room', 8: 'RoomExtra', 9: 'RoomExtra', 10: 'RoomExtra', 11: 'Bill', 12: 'Bill', 13: 'Bill', 14: 'FreeRoomTypesDTO'}

Edges4-edge.soil: [(1, 0), (1, 2), (1, 3), (1, 4), (2, 5), (3, 6), (4, 7), (2, 8), (3, 9), (4, 10), (11, 2), (12, 3), (13, 4), (1, 11), (1, 12), (1, 13)]

Adj4-complex.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 0, 1, 0, 0], [0, 1, 0, 1, 1, 1, 1, 1, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels4-complex.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'RoomExtra', 5: 'RoomExtra', 6: 'RoomExtra', 7: 'Bill', 8: 'FreeRoomTypesDTO', 9: 'FreeRoomTypesDTO'}

Edges4-complex.soil: [(1, 0), (1, 2), (1, 7), (2, 3), (2, 4), (2, 5), (2, 6), (7, 2)]

Adj4-baseline.soil: [[0, 1, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 1, 0], [0, 1, 0, 1, 1, 1, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0]]

Labels4-baseline.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'Room', 5: 'RoomExtra', 6: 'Bill', 7: 'FreeRoomTypesDTO'}

Edges4-baseline.soil: [(1, 0), (1, 2), (1, 6), (2, 3), (2, 5), (6, 2), (2, 4)]

Adj5-boundary.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 0, 0, 0, 1, 0], [0, 1, 0, 1, 1, 1, 1, 1, 1, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels5-boundary.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'Bill', 10: 'FreeRoomTypesDTO'}

Edges5-boundary.soil: [(1, 0), (1, 2), (1, 9), (2, 3), (2, 4), (2, 5), (2, 6), (2, 7), (2, 8), (9, 2)]

Adj5-invalid.soil: [[0, 1, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 1, 1], [0, 1, 0, 1, 1, 1, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0], [0, 1, 0, 0, 0, 0, 0, 0]]

Labels5-invalid.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'RoomExtra', 5: 'RoomExtra', 6: 'Bill', 7: 'Bill'}

Edges5-invalid.soil: [(1, 0), (1, 2), (2, 3), (2, 4), (2, 5), (6, 2), (1, 6), (1, 7)]

Adj5-edge.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 0, 1, 1, 0], [0, 1, 0, 0, 1, 1, 0, 1, 0, 1, 0, 0], [0, 1, 0, 0, 0, 0, 1, 0, 1, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels5-edge.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'Room', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'Bill', 10: 'Bill', 11: 'FreeRoomTypesDTO'}

Edges5-edge.soil: [(1, 0), (1, 2), (1, 3), (2, 4), (2, 5), (3, 6), (2, 7), (3, 8), (9, 2), (10, 3), (1, 9), (1, 10)]

Adj5-complex.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0], [0, 1, 0, 0, 1, 0, 1, 1, 0, 0, 1, 0, 0, 0], [0, 1, 0, 0, 0, 1, 0, 0, 1, 1, 0, 1, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels5-complex.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'RoomExtra', 10: 'Bill', 11: 'Bill', 12: 'FreeRoomTypesDTO', 13: 'FreeRoomTypesDTO'}

Edges5-complex.soil: [(1, 0), (1, 2), (1, 3), (2, 4), (3, 5), (2, 6), (2, 7), (3, 8), (3, 9), (10, 2), (11, 3), (1, 10), (1, 11)]

Adj5-baseline.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 1, 1, 0], [0, 1, 0, 0, 1, 0, 1, 0, 1, 0, 0], [0, 1, 0, 0, 0, 1, 0, 1, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels5-baseline.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'Bill', 9: 'Bill', 10: 'FreeRoomTypesDTO'}

Edges5-baseline.soil: [(1, 0), (1, 2), (1, 3), (1, 8), (1, 9), (2, 4), (3, 5), (2, 6), (3, 7), (8, 2), (9, 3)]

Adj6-boundary.soil: [[0, 1, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0], [0, 1, 0, 1, 0, 0], [0, 1, 1, 0, 1, 0], [0, 0, 0, 1, 0, 0], [0, 0, 0, 0, 0, 0]]

Labels6-boundary.soil: {0: 'Customer', 1: 'Booking', 2: 'Bill', 3: 'RoomReservation', 4: 'Room', 5: 'FreeRoomTypesDTO'}

Edges6-boundary.soil: [(1, 0), (1, 3), (1, 2), (3, 4), (2, 3)]

Adj6-invalid.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 0, 0, 0, 1, 1], [0, 1, 0, 1, 1, 1, 1, 0, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels6-invalid.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'RoomExtra', 5: 'RoomExtra', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'RoomExtra', 9: 'Bill', 10: 'Bill'}

Edges6-invalid.soil: [(1, 0), (1, 2), (2, 3), (2, 4), (2, 5), (2, 6), (9, 2), (1, 9), (1, 10)]

Adj6-edge.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 1, 0, 0, 0, 0, 0, 0, 1, 1, 1, 0], [0, 1, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0, 0, 0], [0, 1, 0, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0, 0], [0, 1, 0, 0, 0, 0, 0, 1, 0, 0, 1, 0, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels6-edge.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'RoomReservation', 5: 'Room', 6: 'Room', 7: 'Room', 8: 'RoomExtra', 9: 'RoomExtra', 10: 'RoomExtra', 11: 'Bill', 12: 'Bill', 13: 'Bill', 14: 'FreeRoomTypesDTO'}

Edges6-edge.soil: [(1, 0), (1, 2), (1, 3), (1, 4), (2, 5), (3, 6), (4, 7), (2, 8), (3, 9), (4, 10), (11, 2), (12, 3), (13, 4), (1, 11), (1, 12), (1, 13)]

Adj6-complex.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 0, 0, 0, 0, 1, 0, 0], [0, 1, 0, 1, 1, 1, 1, 1, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels6-complex.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'Room', 4: 'RoomExtra', 5: 'RoomExtra', 6: 'RoomExtra', 7: 'Bill', 8: 'FreeRoomTypesDTO', 9: 'FreeRoomTypesDTO'}

Edges6-complex.soil: [(1, 0), (1, 2), (1, 7), (2, 3), (2, 4), (2, 5), (2, 6), (7, 2)]

Adj6-baseline.soil: [[0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1, 0, 1, 1, 0, 0, 0, 0, 1, 1, 0], [0, 1, 0, 0, 1, 0, 1, 0, 1, 0, 0], [0, 1, 0, 0, 0, 1, 0, 1, 0, 1, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0], [0, 1, 0, 1, 0, 0, 0, 0, 0, 0, 0], [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]

Labels6-baseline.soil: {0: 'Customer', 1: 'Booking', 2: 'RoomReservation', 3: 'RoomReservation', 4: 'Room', 5: 'Room', 6: 'RoomExtra', 7: 'RoomExtra', 8: 'Bill', 9: 'Bill', 10: 'FreeRoomTypesDTO'}

Edges6-baseline.soil: [(1, 0), (1, 2), (1, 3), (1, 8), (1, 9), (2, 4), (3, 5), (2, 6), (3, 7), (8, 2), (9, 3)]


```
# Kernel: 
```
[[1.         0.86518091 0.66884784 0.84522824 0.85732141 0.88449171
  0.67121957 0.82006668 0.76551223 0.72751818 0.86518091 0.7570333
  0.82006668 0.76551223 0.82006668 0.83479871 0.73484692 0.66884784
  0.78385536 0.85732141 0.85997416 0.93638218 0.81881762 0.76551223
  0.82006668 0.58423739 0.87881673 0.66884784 0.78385536 0.82006668]
 [0.86518091 1.         0.43216678 0.72550678 0.79471941 0.84935636
  0.48811052 0.62545075 0.59582504 0.64278223 0.89473684 0.59649123
  0.62545075 0.59582504 0.62545075 0.77384133 0.68875683 0.43216678
  0.72348591 0.92717265 0.96581236 0.69046022 0.69615596 0.59582504
  0.62545075 0.53311399 0.66399158 0.43216678 0.72348591 0.62545075]
 [0.66884784 0.43216678 1.         0.91399674 0.50330235 0.60075293
  0.48541552 0.94180182 0.87110277 0.83394873 0.43216678 0.51492212
  0.94180182 0.87110277 0.94180182 0.54500286 0.65255753 1.
  0.41940865 0.50330235 0.40425601 0.68033825 0.9226529  0.87110277
  0.94180182 0.43464429 0.58854528 1.         0.41940865 0.94180182]
 [0.84522824 0.72550678 0.91399674 1.         0.74121539 0.78213652
  0.55080945 0.95670077 0.93752142 0.90350862 0.72550678 0.63232243
  0.95670077 0.93752142 0.95670077 0.73397584 0.7839295  0.91399674
  0.66542017 0.74121539 0.71248895 0.79634651 0.97146488 0.93752142
  0.95670077 0.51688656 0.74092371 0.91399674 0.66542017 0.95670077]
 [0.85732141 0.79471941 0.50330235 0.74121539 1.         0.88716625
  0.66143783 0.7307934  0.74578412 0.73589049 0.92717265 0.79471941
  0.7307934  0.74578412 0.7307934  0.91287093 0.85       0.50330235
  0.95174677 0.8125     0.83550998 0.88618626 0.67963735 0.74578412
  0.7307934  0.55901699 0.88465174 0.50330235 0.95174677 0.7307934 ]
 [0.88449171 0.84935636 0.60075293 0.78213652 0.88716625 1.
  0.72357949 0.79328468 0.71340818 0.76275019 0.84935636 0.81637165
  0.79328468 0.71340818 0.79328468 0.88659264 0.83424756 0.60075293
  0.79347718 0.88716625 0.82596023 0.84380013 0.77478657 0.71340818
  0.79328468 0.64037295 0.7802435  0.60075293 0.79347718 0.79328468]
 [0.67121957 0.48811052 0.48541552 0.55080945 0.66143783 0.72357949
  1.         0.61616956 0.55033695 0.50365975 0.55694662 0.97622104
  0.61616956 0.55033695 0.61616956 0.65556228 0.57639582 0.48541552
  0.59433068 0.55513532 0.48804386 0.74870489 0.54800805 0.55033695
  0.61616956 0.46483484 0.66873386 0.48541552 0.59433068 0.61616956]
 [0.82006668 0.62545075 0.94180182 0.95670077 0.7307934  0.79328468
  0.61616956 1.         0.90148039 0.91829491 0.62545075 0.68501749
  1.         0.90148039 1.         0.7937018  0.82448486 0.94180182
  0.6079105  0.7307934  0.58449179 0.82832725 0.96901052 0.90148039
  1.         0.63688145 0.71833072 0.94180182 0.6079105  1.        ]
 [0.76551223 0.59582504 0.87110277 0.93752142 0.74578412 0.71340818
  0.55033695 0.90148039 1.         0.85135848 0.69617452 0.63345609
  0.90148039 1.         0.90148039 0.67432078 0.80497333 0.87110277
  0.7132266  0.60373    0.62820525 0.79974894 0.8524591  1.
  0.90148039 0.40234737 0.78891842 0.87110277 0.7132266  0.90148039]
 [0.72751818 0.64278223 0.83394873 0.90350862 0.73589049 0.76275019
  0.50365975 0.91829491 0.85135848 1.         0.64278223 0.60063258
  0.91829491 0.85135848 0.91829491 0.78434041 0.84329072 0.83394873
  0.61890342 0.73589049 0.60426914 0.71330619 0.90355382 0.85135848
  0.91829491 0.60483286 0.63341202 0.83394873 0.61890342 0.91829491]
 [0.86518091 0.89473684 0.43216678 0.72550678 0.92717265 0.84935636
  0.55694662 0.62545075 0.69617452 0.64278223 1.         0.68421053
  0.62545075 0.69617452 0.62545075 0.77384133 0.7284928  0.43216678
  0.94272407 0.79471941 0.96581236 0.80093386 0.63214162 0.69617452
  0.62545075 0.41464421 0.85928322 0.43216678 0.94272407 0.62545075]
 [0.7570333  0.59649123 0.51492212 0.63232243 0.79471941 0.81637165
  0.97622104 0.68501749 0.63345609 0.60063258 0.68421053 1.
  0.68501749 0.63345609 0.68501749 0.77384133 0.68875683 0.51492212
  0.72348591 0.66226618 0.60363273 0.82855226 0.61613803 0.63345609
  0.68501749 0.53311399 0.7616374  0.51492212 0.72348591 0.68501749]
 [0.82006668 0.62545075 0.94180182 0.95670077 0.7307934  0.79328468
  0.61616956 1.         0.90148039 0.91829491 0.62545075 0.68501749
  1.         0.90148039 1.         0.7937018  0.82448486 0.94180182
  0.6079105  0.7307934  0.58449179 0.82832725 0.96901052 0.90148039
  1.         0.63688145 0.71833072 0.94180182 0.6079105  1.        ]
 [0.76551223 0.59582504 0.87110277 0.93752142 0.74578412 0.71340818
  0.55033695 0.90148039 1.         0.85135848 0.69617452 0.63345609
  0.90148039 1.         0.90148039 0.67432078 0.80497333 0.87110277
  0.7132266  0.60373    0.62820525 0.79974894 0.8524591  1.
  0.90148039 0.40234737 0.78891842 0.87110277 0.7132266  0.90148039]
 [0.82006668 0.62545075 0.94180182 0.95670077 0.7307934  0.79328468
  0.61616956 1.         0.90148039 0.91829491 0.62545075 0.68501749
  1.         0.90148039 1.         0.7937018  0.82448486 0.94180182
  0.6079105  0.7307934  0.58449179 0.82832725 0.96901052 0.90148039
  1.         0.63688145 0.71833072 0.94180182 0.6079105  1.        ]
 [0.83479871 0.77384133 0.54500286 0.73397584 0.91287093 0.88659264
  0.65556228 0.7937018  0.67432078 0.78434041 0.77384133 0.77384133
  0.7937018  0.67432078 0.7937018  1.         0.87635609 0.54500286
  0.75549736 0.91287093 0.72111026 0.83752569 0.75002028 0.67432078
  0.7937018  0.81649658 0.72681557 0.54500286 0.75549736 0.7937018 ]
 [0.73484692 0.68875683 0.65255753 0.7839295  0.85       0.83424756
  0.57639582 0.82448486 0.80497333 0.84329072 0.7284928  0.68875683
  0.82448486 0.80497333 0.82448486 0.87635609 1.         0.65255753
  0.72829318 0.775      0.66840798 0.75065189 0.7491114  0.80497333
  0.82448486 0.62609903 0.678233   0.65255753 0.72829318 0.82448486]
 [0.66884784 0.43216678 1.         0.91399674 0.50330235 0.60075293
  0.48541552 0.94180182 0.87110277 0.83394873 0.43216678 0.51492212
  0.94180182 0.87110277 0.94180182 0.54500286 0.65255753 1.
  0.41940865 0.50330235 0.40425601 0.68033825 0.9226529  0.87110277
  0.94180182 0.43464429 0.58854528 1.         0.41940865 0.94180182]
 [0.78385536 0.72348591 0.41940865 0.66542017 0.95174677 0.79347718
  0.59433068 0.6079105  0.7132266  0.61890342 0.94272407 0.72348591
  0.6079105  0.7132266  0.6079105  0.75549736 0.72829318 0.41940865
  1.         0.66208471 0.82976757 0.82832523 0.559972   0.7132266
  0.6079105  0.37011661 0.91517873 0.41940865 1.         0.6079105 ]
 [0.85732141 0.92717265 0.50330235 0.74121539 0.8125     0.88716625
  0.55513532 0.7307934  0.60373    0.73589049 0.79471941 0.66226618
  0.7307934  0.60373    0.7307934  0.91287093 0.775      0.50330235
  0.66208471 1.         0.83550998 0.72980045 0.77025567 0.60373
  0.7307934  0.78262379 0.62662831 0.50330235 0.66208471 0.7307934 ]
 [0.85997416 0.96581236 0.40425601 0.71248895 0.83550998 0.82596023
  0.48804386 0.58449179 0.62820525 0.60426914 0.96581236 0.60363273
  0.58449179 0.62820525 0.58449179 0.72111026 0.66840798 0.40425601
  0.82976757 0.83550998 1.         0.71798057 0.63629096 0.62820525
  0.58449179 0.40761973 0.75406738 0.40425601 0.82976757 0.58449179]
 [0.93638218 0.69046022 0.68033825 0.79634651 0.88618626 0.84380013
  0.74870489 0.82832725 0.79974894 0.71330619 0.80093386 0.82855226
  0.82832725 0.79974894 0.82832725 0.83752569 0.75065189 0.68033825
  0.82832523 0.72980045 0.71798057 1.         0.75580899 0.79974894
  0.82832725 0.55950288 0.95305697 0.68033825 0.82832523 0.82832725]
 [0.81881762 0.69615596 0.9226529  0.97146488 0.67963735 0.77478657
  0.54800805 0.96901052 0.8524591  0.90355382 0.63214162 0.61613803
  0.96901052 0.8524591  0.96901052 0.75002028 0.7491114  0.9226529
  0.559972   0.77025567 0.63629096 0.75580899 1.         0.8524591
  0.96901052 0.62139471 0.65023249 0.9226529  0.559972   0.96901052]
 [0.76551223 0.59582504 0.87110277 0.93752142 0.74578412 0.71340818
  0.55033695 0.90148039 1.         0.85135848 0.69617452 0.63345609
  0.90148039 1.         0.90148039 0.67432078 0.80497333 0.87110277
  0.7132266  0.60373    0.62820525 0.79974894 0.8524591  1.
  0.90148039 0.40234737 0.78891842 0.87110277 0.7132266  0.90148039]
 [0.82006668 0.62545075 0.94180182 0.95670077 0.7307934  0.79328468
  0.61616956 1.         0.90148039 0.91829491 0.62545075 0.68501749
  1.         0.90148039 1.         0.7937018  0.82448486 0.94180182
  0.6079105  0.7307934  0.58449179 0.82832725 0.96901052 0.90148039
  1.         0.63688145 0.71833072 0.94180182 0.6079105  1.        ]
 [0.58423739 0.53311399 0.43464429 0.51688656 0.55901699 0.64037295
  0.46483484 0.63688145 0.40234737 0.60483286 0.41464421 0.53311399
  0.63688145 0.40234737 0.63688145 0.81649658 0.62609903 0.43464429
  0.37011661 0.78262379 0.40761973 0.55950288 0.62139471 0.40234737
  0.63688145 1.         0.39562828 0.43464429 0.37011661 0.63688145]
 [0.87881673 0.66399158 0.58854528 0.74092371 0.88465174 0.7802435
  0.66873386 0.71833072 0.78891842 0.63341202 0.85928322 0.7616374
  0.71833072 0.78891842 0.71833072 0.72681557 0.678233   0.58854528
  0.91517873 0.62662831 0.75406738 0.95305697 0.65023249 0.78891842
  0.71833072 0.39562828 1.         0.58854528 0.91517873 0.71833072]
 [0.66884784 0.43216678 1.         0.91399674 0.50330235 0.60075293
  0.48541552 0.94180182 0.87110277 0.83394873 0.43216678 0.51492212
  0.94180182 0.87110277 0.94180182 0.54500286 0.65255753 1.
  0.41940865 0.50330235 0.40425601 0.68033825 0.9226529  0.87110277
  0.94180182 0.43464429 0.58854528 1.         0.41940865 0.94180182]
 [0.78385536 0.72348591 0.41940865 0.66542017 0.95174677 0.79347718
  0.59433068 0.6079105  0.7132266  0.61890342 0.94272407 0.72348591
  0.6079105  0.7132266  0.6079105  0.75549736 0.72829318 0.41940865
  1.         0.66208471 0.82976757 0.82832523 0.559972   0.7132266
  0.6079105  0.37011661 0.91517873 0.41940865 1.         0.6079105 ]
 [0.82006668 0.62545075 0.94180182 0.95670077 0.7307934  0.79328468
  0.61616956 1.         0.90148039 0.91829491 0.62545075 0.68501749
  1.         0.90148039 1.         0.7937018  0.82448486 0.94180182
  0.6079105  0.7307934  0.58449179 0.82832725 0.96901052 0.90148039
  1.         0.63688145 0.71833072 0.94180182 0.6079105  1.        ]]
```
# Kernel 2D table: 
|       | boundary1 | invalid2 | edge3 | complex4 | baseline5 | boundary6 | invalid7 | edge8 | complex9 | baseline10 | boundary11 | invalid12 | edge13 | complex14 | baseline15 | boundary16 | invalid17 | edge18 | complex19 | baseline20 | boundary21 | invalid22 | edge23 | complex24 | baseline25 | boundary26 | invalid27 | edge28 | complex29 | baseline30 |
|-------|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **boundary1** | 1.000000 | 0.865181 | 0.668848 | 0.845228 | 0.857321 | 0.884492 | 0.671220 | 0.820067 | 0.765512 | 0.727518 | 0.865181 | 0.757033 | 0.820067 | 0.765512 | 0.820067 | 0.834799 | 0.734847 | 0.668848 | 0.783855 | 0.857321 | 0.859974 | 0.936382 | 0.818818 | 0.765512 | 0.820067 | 0.584237 | 0.878817 | 0.668848 | 0.783855 | 0.820067 |
| **invalid2** |  | 1.000000 | 0.432167 | 0.725507 | 0.794719 | 0.849356 | 0.488111 | 0.625451 | 0.595825 | 0.642782 | 0.894737 | 0.596491 | 0.625451 | 0.595825 | 0.625451 | 0.773841 | 0.688757 | 0.432167 | 0.723486 | 0.927173 | 0.965812 | 0.690460 | 0.696156 | 0.595825 | 0.625451 | 0.533114 | 0.663992 | 0.432167 | 0.723486 | 0.625451 |
| **edge3** |  |  | 1.000000 | 0.913997 | 0.503302 | 0.600753 | 0.485416 | 0.941802 | 0.871103 | 0.833949 | 0.432167 | 0.514922 | 0.941802 | 0.871103 | 0.941802 | 0.545003 | 0.652558 | 1.000000 | 0.419409 | 0.503302 | 0.404256 | 0.680338 | 0.922653 | 0.871103 | 0.941802 | 0.434644 | 0.588545 | 1.000000 | 0.419409 | 0.941802 |
| **complex4** |  |  |  | 1.000000 | 0.741215 | 0.782137 | 0.550809 | 0.956701 | 0.937521 | 0.903509 | 0.725507 | 0.632322 | 0.956701 | 0.937521 | 0.956701 | 0.733976 | 0.783929 | 0.913997 | 0.665420 | 0.741215 | 0.712489 | 0.796347 | 0.971465 | 0.937521 | 0.956701 | 0.516887 | 0.740924 | 0.913997 | 0.665420 | 0.956701 |
| **baseline5** |  |  |  |  | 1.000000 | 0.887166 | 0.661438 | 0.730793 | 0.745784 | 0.735890 | 0.927173 | 0.794719 | 0.730793 | 0.745784 | 0.730793 | 0.912871 | 0.850000 | 0.503302 | 0.951747 | 0.812500 | 0.835510 | 0.886186 | 0.679637 | 0.745784 | 0.730793 | 0.559017 | 0.884652 | 0.503302 | 0.951747 | 0.730793 |
| **boundary6** |  |  |  |  |  | 1.000000 | 0.723579 | 0.793285 | 0.713408 | 0.762750 | 0.849356 | 0.816372 | 0.793285 | 0.713408 | 0.793285 | 0.886593 | 0.834248 | 0.600753 | 0.793477 | 0.887166 | 0.825960 | 0.843800 | 0.774787 | 0.713408 | 0.793285 | 0.640373 | 0.780243 | 0.600753 | 0.793477 | 0.793285 |
| **invalid7** |  |  |  |  |  |  | 1.000000 | 0.616170 | 0.550337 | 0.503660 | 0.556947 | 0.976221 | 0.616170 | 0.550337 | 0.616170 | 0.655562 | 0.576396 | 0.485416 | 0.594331 | 0.555135 | 0.488044 | 0.748705 | 0.548008 | 0.550337 | 0.616170 | 0.464835 | 0.668734 | 0.485416 | 0.594331 | 0.616170 |
| **edge8** |  |  |  |  |  |  |  | 1.000000 | 0.901480 | 0.918295 | 0.625451 | 0.685017 | 1.000000 | 0.901480 | 1.000000 | 0.793702 | 0.824485 | 0.941802 | 0.607911 | 0.730793 | 0.584492 | 0.828327 | 0.969011 | 0.901480 | 1.000000 | 0.636881 | 0.718331 | 0.941802 | 0.607911 | 1.000000 |
| **complex9** |  |  |  |  |  |  |  |  | 1.000000 | 0.851358 | 0.696175 | 0.633456 | 0.901480 | 1.000000 | 0.901480 | 0.674321 | 0.804973 | 0.871103 | 0.713227 | 0.603730 | 0.628205 | 0.799749 | 0.852459 | 1.000000 | 0.901480 | 0.402347 | 0.788918 | 0.871103 | 0.713227 | 0.901480 |
| **baseline10** |  |  |  |  |  |  |  |  |  | 1.000000 | 0.642782 | 0.600633 | 0.918295 | 0.851358 | 0.918295 | 0.784340 | 0.843291 | 0.833949 | 0.618903 | 0.735890 | 0.604269 | 0.713306 | 0.903554 | 0.851358 | 0.918295 | 0.604833 | 0.633412 | 0.833949 | 0.618903 | 0.918295 |
| **boundary11** |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.684211 | 0.625451 | 0.696175 | 0.625451 | 0.773841 | 0.728493 | 0.432167 | 0.942724 | 0.794719 | 0.965812 | 0.800934 | 0.632142 | 0.696175 | 0.625451 | 0.414644 | 0.859283 | 0.432167 | 0.942724 | 0.625451 |
| **invalid12** |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.685017 | 0.633456 | 0.685017 | 0.773841 | 0.688757 | 0.514922 | 0.723486 | 0.662266 | 0.603633 | 0.828552 | 0.616138 | 0.633456 | 0.685017 | 0.533114 | 0.761637 | 0.514922 | 0.723486 | 0.685017 |
| **edge13** |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.901480 | 1.000000 | 0.793702 | 0.824485 | 0.941802 | 0.607911 | 0.730793 | 0.584492 | 0.828327 | 0.969011 | 0.901480 | 1.000000 | 0.636881 | 0.718331 | 0.941802 | 0.607911 | 1.000000 |
| **complex14** |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.901480 | 0.674321 | 0.804973 | 0.871103 | 0.713227 | 0.603730 | 0.628205 | 0.799749 | 0.852459 | 1.000000 | 0.901480 | 0.402347 | 0.788918 | 0.871103 | 0.713227 | 0.901480 |
| **baseline15** |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.793702 | 0.824485 | 0.941802 | 0.607911 | 0.730793 | 0.584492 | 0.828327 | 0.969011 | 0.901480 | 1.000000 | 0.636881 | 0.718331 | 0.941802 | 0.607911 | 1.000000 |
| **boundary16** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.876356 | 0.545003 | 0.755497 | 0.912871 | 0.721110 | 0.837526 | 0.750020 | 0.674321 | 0.793702 | 0.816497 | 0.726816 | 0.545003 | 0.755497 | 0.793702 |
| **invalid17** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.652558 | 0.728293 | 0.775000 | 0.668408 | 0.750652 | 0.749111 | 0.804973 | 0.824485 | 0.626099 | 0.678233 | 0.652558 | 0.728293 | 0.824485 |
| **edge18** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.419409 | 0.503302 | 0.404256 | 0.680338 | 0.922653 | 0.871103 | 0.941802 | 0.434644 | 0.588545 | 1.000000 | 0.419409 | 0.941802 |
| **complex19** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.662085 | 0.829768 | 0.828325 | 0.559972 | 0.713227 | 0.607911 | 0.370117 | 0.915179 | 0.419409 | 1.000000 | 0.607911 |
| **baseline20** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.835510 | 0.729800 | 0.770256 | 0.603730 | 0.730793 | 0.782624 | 0.626628 | 0.503302 | 0.662085 | 0.730793 |
| **boundary21** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.717981 | 0.636291 | 0.628205 | 0.584492 | 0.407620 | 0.754067 | 0.404256 | 0.829768 | 0.584492 |
| **invalid22** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.755809 | 0.799749 | 0.828327 | 0.559503 | 0.953057 | 0.680338 | 0.828325 | 0.828327 |
| **edge23** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.852459 | 0.969011 | 0.621395 | 0.650232 | 0.922653 | 0.559972 | 0.969011 |
| **complex24** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.901480 | 0.402347 | 0.788918 | 0.871103 | 0.713227 | 0.901480 |
| **baseline25** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.636881 | 0.718331 | 0.941802 | 0.607911 | 1.000000 |
| **boundary26** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.395628 | 0.434644 | 0.370117 | 0.636881 |
| **invalid27** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.588545 | 0.915179 | 0.718331 |
| **edge28** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.419409 | 0.941802 |
| **complex29** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 | 0.607911 |
| **baseline30** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1.000000 |