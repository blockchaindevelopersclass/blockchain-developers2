# Signature malleability


- Зная подпись *sign* для данных *d*, можно сформировать другую валидную подпись *sign`* не зная секретный ключ *sk* (свойство signature malleability).
- Реализовать [функцию](https://github.com/blockchaindevelopersclass/hometasks/blob/week2/src/main/scala/crypto/Curve25519SignatureForger.scala#L7) которая создает новую валидную подпись из известной валидной подписи для эллиптической кривой Curve25519