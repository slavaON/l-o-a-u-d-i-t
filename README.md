# Отчет аудита

### Оригинальный репозиторий: https://github.com/0xStarLabs/STAR-LABS-LAYER-ZERO

### Audit Commit hash:        `e7d88dee0c45537d197b478c493ca82ee4b39da9`

---

### Адреса контрактов с файла `src/constants` которые были найдены в официальных источниках:

### `Протоколы:`

| Protocol     | Chain     | Address                                    | 
|--------------|-----------|--------------------------------------------|
| merkly       | polygon   | 0x0E1f20075C90Ab31FC2Dd91E536e6990262CF76d |
| l2pass       | polygon   | 0x222228060E7Efbb1D78BB5D454581910e3922222 |
| l2telegraph  | polygon   | 0x523d5581A0bb8BB2Bc9f23B5202894E31124eA3e |
| l2telegraph  | celo      | 0x83017335bae4837016311bdb75df5a320b54d636 |
| l2telegraph  | gnosis    | 0xE266EedB13A69AF15c1756a241021905B1827F6A |
| l2telegraph  | moonriver | 0x5B10aE182C297ec76fE6fe0E3Da7c4797ceDE02D |
| merkly       | celo      | 0xC20A842e1Fc2681920C1A190552A2f13C46e7fCF |
| merkly       | gnosis    | 0x556F119C7433b2232294FB3De267747745A1dAb4 |
| merkly       | moonbeam  | 0x671861008497782F7108D908D4dF18eBf9598b82 |
| merkly       | moonriver | 0xd379c3D0930d70022B3C6EBA8217e4B990705540 |
| merkly       | conflux   | 0xE47b05F2026a82048caAECf5caE58e5AAE2405eA |
| merkly       | klaytn    | 0x79DB0f1A83f8e743550EeB5DD5B0B83334F2F083 |
| l2pass       | celo      | 0x222228060E7Efbb1D78BB5D454581910e3922222 |
| l2pass       | gnosis    | 0x222228060E7Efbb1D78BB5D454581910e3922222 |
| l2pass       | moonbeam  | 0x222228060E7Efbb1D78BB5D454581910e3922222 |
| l2pass       | moonriver | 0x222228060E7Efbb1D78BB5D454581910e3922222 |
| l2pass       | klaytn    | 0x222228060E7Efbb1D78BB5D454581910e3922222 |

### `Токены:`

| Token         | Chain    | Address                                    |
|---------------|----------|--------------------------------------------|
| USDT          | polygon  | 0xc2132D05D31c914a87C6611C10748AEb04B58e8F |
| BNB           | polygon  | 0x3BA4c387f786bFEE076A58914F5Bd38d668B42c3 |
| USDC          | polygon  | 0x3c499c542cEF5E3811e1192ce70d8cC03d5c3359 |
| USDC.e        | polygon  | 0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174 |
| BUSD          | polygon  | 0xdAb529f40E671A1D4bF91361c21bf9f0C9712ab7 |
| AVAX          | polygon  | 0x2C89bbc92BD86F8075d1DEcc58C7F4E0107f286b |
| USDT          | celo     | 0x617f3112bf5397D0467D315cC709EF968D9ba546 |
| USDC          | celo     | 0xef4229c8c3250C675F21BCefa42f58EfbfF6002a |
| USDC(Wormhole)| celo     | 0x37f750B7cC259A2f741AF45294f6a16572CF5cAd |
| WBTC          | celo     | 0xD629eb00dEced2a080B7EC630eF6aC117e614f1b |
| CELO          | celo     | 0x471EcE3750Da237f93B8E339c536989b8978a438 |
| SUSHI         | celo     | 0x29dFce9c22003A4999930382Fd00f9Fd6133Acd1 |
| USDT          | moonbeam | 0xeFAeeE334F0Fd1712f9a8cc375f427D9Cdd40d73 |
| USDC(Wormhole)| moonbeam | 0x931715FEE2d06333043d11F658C8CE934aC61D0c |
| AVAX          | moonbeam | 0x4792C1EcB969B036eb51330c63bD27899A13D84e |
| MATIC         | moonbeam | 0x3405A1bd46B85c5C029483FbECf2F3E611026e45 |
| USDC(Multichain)| moonbeam | 0x818ec0A7Fe18Ff94269904fCED6AE3DaE6d6dC0b |
| USDT          | moonriver| 0xB44a9B6905aF7c801311e8F4E76932ee959c663C |
| USDC          | moonriver| 0xE3F5a90F9cb311505cd691a46596599aA1A0AD7D |
| DAI           | moonriver| 0x80A16016cC4A2E6a2CACA8a4a498b1699fF0f844 |
| WMOVR         | moonriver| 0x98878B06940aE243284CA214f92Bb71a2b032B8A |
| USDT          | conflux  | 0xfe97e85d13abd9c1c33384e796f10b73905637ce |
| ETH           | conflux  | 0xa47f43de2f9623acb395ca4905746496d2014d57 |
| USDC          | conflux  | 0x6963efed0ab40f6c3d7bda44a05dcf1437c44372 |
| BNB           | conflux  | 0x94bd7a37d2ce24cc597e158facaa8d601083ffec |
| xCFX          | conflux  | 0x889138644274a7dc602f25a7e7d53ff40e6d0091 |
| WCFX          | conflux  | 0x14b2d3bc65e74dae1030eafd8ac30c533c976a9b |
| USDT          | gnosis   | 0x4ECaBa5870353805a9F068101A40E0f32ed605C6 |
| USDC          | gnosis   | 0xDDAfbb505ad214D7b80b1f830fcCc89B60fb7A83 |
| LINK          | gnosis   | 0xE2e73A1c69ecF83F464EFCE6A5be353a37cA09b2 |
| MATIC         | gnosis   | 0x7122d7661c4564b7C6Cd4878B06766489a6028A2 |
| oETH          | klaytn   | 0x34d21b1e550d73cee41151c77f3c73359527a396 |
| oUSDT         | klaytn   | 0xcee8faf64bb97a73bb51e115aa89c17ffa8dd167 |
| oBNB          | klaytn   | 0x574e9c26bda8b95d7329505b4657103710eb32ea |
| oUSDC         | klaytn   | 0x754288077d0ff82af7a5317c7cb8c444d421d103 |
| KDAI          | klaytn   | 0x5c74070fdea071359b86082bd9f9b3deaafbe32b |

---
<br>

###  Не найденные адреса контрактов с файла `src/constants`: 

`строка 80`:
``` javascript
    zerius: "0x2ef766b59e4603250265EcC468cF38a6a00b84b3"
```

`строка 112`:

``` javascript
    export const ZERIUS_REFUEL_CONTRACTS: any = {
    145: '0x1fe2c567169d39CCc5299727FfAC96362b2Ab90E',
    116: '0x5B209E7c81DEaad0ffb8b76b696dBb4633A318CD',
    153: '0xB47D82aA70f839dC27a34573f135eD6dE6CED9A5',
    125: '0xFF21d5a3a8e3E8BA2576e967888Deea583ff02f8',
    126: '0xb0bea3bB2d6EDDD2014952ABd744660bAeF9747d',
}
```

`строка 143`:

```javascript
    spenders: [
                "0x07e56b727e0EAcFa53823977599905024c2de4F0", "0x643770E279d5D0733F21d6DC03A8efbABf3255B4",
                "0x1111111254EEB25477B68fb85Ed929f73A960582", "0xDEF171Fe48CF0115B1d80b88dc8eAB59176FEe57",
                "0x4E3288c9ca110bCC82bf38F09A7b425c095d92Bf",

            ],
```
`строка 174`:

```javascript
    spenders: [
            "0x000000000022d473030f116ddee9f6b43ac78ba3", "0xaB235da7f52d35fb4551AfBa11BFB56e18774A65",
            "0xe3d8bd6aed4f159bc8000a9cd47cffdb95f96121", "0x471EcE3750Da237f93B8E339c536989b8978a438",

        ],
```
`строка 200`:
```javascript
    spenders: [
        "0x843D0AAD40295f2198ef528ad747CDF6AB9000e4", "0xd95fe880d7717f7f20981FE6e41A2315f3EFeAb5",
        "0x603eF396029b5e89f9420b4192814aEC0664ADAb", "0xd3B02Ff30c218c7f7756BA14bcA075Bf7C2C951e",
    ],
```

`строка 229`:
```javascript
    spenders: [
            "0x7af71799C40F952237eAA4D81A77C1af49125113", "0xD8FC27ec222E8d5172CD63aC453C6Dfb7467a3C7",
            "0xFB45b575b66C99e0C8d2639aCf237807d4ea1508",
        ]
```

`строка 250`:
```javascript
    spenders: [
            "0x62b0873055Bf896DD869e172119871ac24aEA305",
        ]
```

`строка 277`:
```javascript
    spenders: [
            "0x1111111254EEB25477B68fb85Ed929f73A960582", "0x7A4af156379f512DE147ed3b96393047226d923F",
            "0xBA12222222228d8Ba445958a75a0704d566BF2C8", "0x6093AeBAC87d62b1A5a4cEec91204e35020E38bE",
        ]
```

`строка 301`:
```javascript
    spenders: ["0xe0fbB27D0E7F3a397A67a9d4864D4f4DD7cF8cB9", "0xF7BF3499Df413aC09C4BC8F7521EB4953B5f7bda"]
```

Адреса `spenders` используются автором как: 
> апрувы случайных токенов для случайных протоколов на супер мелкие суммы

>> | approve | Ставите либо true либо false. Если true будет делать апрувы случайных токенов для случайных протоколов на супер мелкие суммы. Смысл в том, чтобы не кидать одни только транзакции л0 подряд. |

## Рекомендации после аудита кода: 
    1. Осторожное использование 'approve' параметра: Применяйте параметр 'approve' в config.ts на строке 10 только в том случае, если вы полностью доверяете контрактам, связанным с адресами в указанной сети.

    2. Отказ от использования протокола zerius: Не рекомендуется использовать протокол zerius в данном скрипте, поскольку адреса контрактов, представленные автором, не были найдены в официальных источника в ходе проверки.

    3. Отсутствие вредоносного кода: В ходе аудита вредоносный код не был обнаружен.

---

<details>
  <summary>Original README</summary>

# STAR-LABS-LAYER-ZERO

## [SEE ENGLISH VERSION BELOW ](https://github.com/0xStarLabs/STAR-LABS-LAYER-ZERO#english-version)👇

## 🔗 Links
[![Telegram channel](https://img.shields.io/endpoint?url=https://runkit.io/damiankrawczyk/telegram-badge/branches/master?url=https://t.me/StarLabsTech)](https://t.me/StarLabsTech)
[![Telegram chat](https://img.shields.io/endpoint?url=https://runkit.io/damiankrawczyk/telegram-badge/branches/master?url=https://t.me/StarLabsChat)](https://t.me/StarLabsChat)

🔔 CHANNEL: https://t.me/StarLabsTech

💬 CHAT: https://t.me/StarLabsChat

💰 DONATION EVM ADDRESS: 0x620ea8b01607efdf3c74994391f86523acf6f9e1

📖 FULL TUTORIAL: https://teletype.in/@neon_rs/STAR_LABS_LAYER_ZERO


## 🤖 | Функционал:
🟢  Взаимодействие с протоколами: MERKLY, L2PASS, L2TELEGRAPH, ZERIUS

🟢  Поддержка сурс сетей: Polygon, Celo, Klaytn, Moonriver, Moonbeam, Gnosis, Conflux

🟢  Пополнение балансов через OKX

🟢  Установка предельной стоимости газа для каждой сети

🟢  Выбор диапазона количества транзакций.

🟢  Логирование всех действий

🟢  Возможность делать апрувы на незначительные суммы между транзакциями л0 (анти-Sybil система).

🟢  Асинхронность и многопоточность. Запуск всех аккаунтов одновременно с различным временем задержки старта и случайными интервалами между транзакциями.


## 🚀 Installation
```

# для работы необходимо установить NodeJS!
# https://nodejs.org/en/download/current

git clone https://github.com/0xStarLabs/STAR-LABS-LAYER-ZERO.git

cd StarLabs-Discord

npm i
npm install -g typescript

если ccxt не установилась с первого раза 
npm uninstall ccxt          ( удаляем библиотеку )
npm i --save-dev ccxt      ( скачиваем по новой )

# Перед началом работы настройте необходимые модули в файлах config.ts и /data

npm start
```
## ⚙️ Config

| Name | Description |
| --- | --- |
| protocols | в квадратные скобочки вставляете протоколы с которыми хотите чтобы скрипт взаимодействовал. По дефолту включены все, если хотите так и оставить - ничего не трогайте. На строчку выше есть памятка с их названиями. |
| networks | В квадратные скобочки вставляете сети которые скрипт использовал. По дефолту включены все, если хотите так и оставить можно ничего не трогать. На строчку выше есть памятка с их названиями. |
| approve | Ставите либо true либо false. Если true будет делать апрувы случайных токенов для случайных протоколов на супер мелкие суммы. Смысл в том, чтобы не кидать одни только транзакции л0 подряд. |
| exchange | withdraw: Выбираете использовать ли биржу в переменной exchange (true / false). Если false - будет работать с тем, что есть на кошельке. Если true - при запуске выведет нативку в сети, где баланс ниже минимальных значений. (На окекс у вас должны быть монеты, чтобы их выводить). С какими сетями и протоколами работать также можно указать в конфиге. Ссылка на полный гайд ниже. Если выбрали true, то также нужно заполнить  |
| OKX_API_KEY | апи ключ |
| OKX_SECRET_KEY | секретный ключ (дается при генерации апи ключа) |
| OKX_PASSPHRASE | пароль от аккаунта |
| amounts | Диапазон того, сколько монет выводить для каждой сети. Можно не трогать. При таких значениях хватает примерно на 100 транз.  |
| maxGasPrice | максимальное количество гвей при котором будет кидать транзакции в определенной сети, если в одной из сетей газ временно завышен то при выборе её не будет учитывать до того момента, как он не опустится ниже приемлимых значений, если везде выше то выбирает случайную сеть и ждет.|
| iterationRange | диапазон (от и до) транзакций, которые скрипт будет кидать на каждом кошельке |
| initializationTime | сколько секунд будут запускаться все потоки. К примеру у вас 100 акков, вы ставите 10000 секунд. Бот будет запускать в работу каждый последующий аккаунт в промежутке 50 - 200 секунд. |
| pause | диапазон секунд паузы между каждой новый транзакцей у кошелька.  |
| endless_loop | Отправлять сообщения в чат бесконечно |
| privateKeysRandomMod | режим рандомизации приватных ключей. shuffle - перемешивает при каждом запуске. order - идет по списку из переменной под таким же названием снизу, consecutive - просто идет по порядку. | 
| order | Номера приватных ключей по которым будет запускаться скрипт, если вы выберете режим order в privateKeysRandomMod.  К примеру вы указываете 1, 7, 2. Скрипт сначала запустит кошелек 1, потом кошелек 7, потом кошелек 2. |

## 🗂️ Data

Данные в папке data:

| Name | Description |
| --- | --- |
| private_keys.txt | Приватные ключи |


## ENGLISH VERSION:


## 🤖 | Functionality:

🟢 Interaction with protocols: MERKLY, L2PASS, L2TELEGRAPH, ZERIUS

🟢 Support for source networks: Polygon, Celo, Klaytn, Moonriver, Moonbeam, Gnosis, Conflux

🟢 Account top-up via OKX

🟢 Setting a maximum gas price for each network

🟢 Selection of transaction count range

🟢 Logging all actions

🟢 Ability to approve minor amounts between L0 transactions (anti-Sybil system)

🟢 Asynchrony and multithreading. Launching all accounts simultaneously with varying start delay times and random intervals between transactions


## 🚀 Installation
```

# NodeJS is required!
# https://nodejs.org/en/download/current

git clone https://github.com/0xStarLabs/STAR-LABS-LAYER-ZERO.git

cd StarLabs-Discord

npm i
npm install -g typescript

if ccxt did not install on the first try
npm uninstall ccxt          (remove the library)
npm i --save-dev ccxt      (re-download)

# Before starting, configure the necessary modules in config.ts and /data files

npm start
```

## ⚙️ Config

| Name | Description |
| --- | --- |
| protocols | Insert the protocols you want the script to interact with in square brackets. By default, all are enabled; if you want to leave it that way, do not touch anything. There's a reminder of their names above. |
| networks | nsert the networks the script used into square brackets. By default, all are enabled; if you want to leave it that way, do not touch anything. There's a reminder of their names above. |
| approve | Set either true or false. If true, it will approve random tokens for random protocols for tiny amounts. The idea is not to just send L0 transactions in a row. |
| exchange |Choose whether to use the exchange in the exchange variable (true / false). If false - will work with what is in the wallet. If true - at startup, it will withdraw native coins in the network where the balance is below the minimum values. (You must have coins on OKEX to withdraw them). Which networks and protocols to work with can also be specified in the config. Link to the full guide below. If you chose true, you also need to fill out |
| OKX_API_KEY |	API key |
| OKX_SECRET_KEY | secret key (given when generating an API key) |
| OKX_PASSPHRASE | account password |
| amounts | The range of how many coins to withdraw for each network. Can be left as is. With such values, it's enough for about 100 transactions. |
| maxGasPrice |	The maximum amount of gwei to send transactions in a certain network, if the gas is temporarily inflated in one of the networks it will not consider choosing it until it drops below acceptable values, if it's higher everywhere then it selects a random network and waits. |	
| iterationRange | The range (from and to) of transactions the script will send on each wallet. |
| initializationTime |	How many seconds all threads will start. For example, you have 100 accounts, you set 10000 seconds. The bot will start each subsequent account in the interval of 50 - 200 seconds. |
| pause | The range of seconds of pause between each new transaction in the wallet. |
| endless_loop | Send messages to the chat endlessly |
| privateKeysRandomMod |Private key randomization mode. shuffle - shuffles each time it starts. order - follows the list from the variable of the same name below, consecutive - just goes in order. |
| order | Numbers of private keys by which the script will start, if you choose the order mode in privateKeysRandomMod. For example, you specify 1, 7, 2. The script will first start wallet 1, then wallet 7, then wallet 2. |

## 🗂️ Data
Data in the data folder:
| Name | Description |
| --- | --- |
| private_keys.txt |	Private keys |
</details>
