# JavaScript-Test-Task

Реализовать свапы(обмены) одного токена на другой в 3 сетях: Base, Solana, Aptos. Чтобы получить приватные ключи от кошельков, напишите в тг @cp121eth.

Обменять надо USDT на SOL в сети Solana и обратно, USDT на APT и обратно в сети Aptos, USDT на ETH в сети Base.

Входные данные:
- Количество для обмена USDT = 1
- Количество для обмена SOL = 0.01
- Количество для обмена APT = 0.1
- Количество для обмена ETH = 0.0001

Выходные данные:
- Хеш транзакции и полная ссылка на него.

Полезные материалы:
- Просмотр транзакций для ***Solana***: https://solscan.io/
- Адрес контракта USDT в сети Solana: Es9vMFrzaCERmJfrF4H2FYD4KCoNkY11McCe8BenwNYB
- Адрес контракта SOL в сети Solana: So11111111111111111111111111111111111111111
- Документация к децентрализованной бирже JUPITER: https://dev.jup.ag/docs/
- json-rpc для взаимодействия с блокчейном: https://go.getblock.io/87f58c53b495465fa31ca60cde692b9c

- Просмотр транзакций для ***Aptos***: https://aptoscan.com/
- Адрес контракта USDT в сети Aptos: 0x357b0b74bc833e95a115ad22604854d6b0fca151cecd94111770e5d6ffc9dc2b
- Адрес контракта APT в сети Aptos: 0x000000000000000000000000000000000000000000000000000000000000000a
- Документация к децентрализованной бирже LIQUIDSWAP: https://docs.liquidswap.com/typescript-sdk
- json-rpc для взаимодействия с блокчейном: https://go.getblock.io/51d926b160d348579ed9529a8eb14ba2

- Просмотр транзакций для ***Base***: https://basescan.org/
- Адрес контракта USDT в сети Base: 0xfde4c96c8593536e31f229ea8f37b2ada2699bb2
- Адрес контракта ETH в сети Base: 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee
- Документация к децентрализованной бирже Uniswap: https://docs.uniswap.org/
- json-rpc для взаимодействия с блокчейном: https://go.getblock.io/6b07e9e54d6d4082850a5bcc2ad6ab17
