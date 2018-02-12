# PoW

Реализовать [функцию](https://github.com/blockchaindevelopersclass/hometasks/blob/master/src/main/scala/mining/PoWMiner.scala#L11)
которая принимает данные *data* и сложность *difficulty*, и возвращает такой объект *=ProvedData(data: Array[Byte], nonce: Int)*,
в котором *data* - это исходные данные, а nonce такой, что *BigInt(1, hashFunction.hash(data.bytes)) <= (MaxTarget / difficulty)*
