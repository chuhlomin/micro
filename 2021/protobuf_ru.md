---
date: 2021-01-17
---

# Protobuf

![Protobuf logo](protobuf.png)

Protocol Buffers – открытый расширяемый механизм сериализации структурированных данных, разработанный в Google. Как JSON или XML, только бинарный, компактнее. При этом "отправитель" и "получатель" сообщения должны заранее договаривиться о "схеме сообщения".

https://developers.google.com/protocol-buffers/

![Protocol Buffers](protobuf.jpeg "Protocol Buffers")

Из Protobuf файлов можно генерировать код для разных языков программирования: Go, Java, Python, C++, C#, Ruby.

Protobuf по-умолчанию используется в gRPC для описания запросов/ответов сервиса.

В реальной жизни Protobuf используется, например, при передаче статей Apple News вам на устройство, и в приложении карт для получения информации о положении автобусов, трамваев, поездов (GTFS Realtime).

Ближайшие альтернативы: Avro (обычно используют с Kafka), Apache Thrift, Cap'n Proto.

Мини-демо-репозиторий: https://github.com/chuhlomin/protobuf-telegram-post

#proto #go
