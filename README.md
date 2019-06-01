# blockchain-uniproject :exclamation: #

![picture alt](https://upload.wikimedia.org/wikipedia/commons/2/2d/Monero-Logo.svg "Monero (XMR) криптовалута")

# Monero (XMR) криптовалута # 

1. [Увод](#1-увод)
2. [Концепция на валутата](#2-концепция-на-валутата)
3. [Предимства и недостатъци:](#3-предимства-и-недостатъци)
   * [Предимства](#предимства)
   * [Недостатъци](#недостатъци)
4. [Инструменти за разработка и управнелние](#4-инструменти-за-разработка-и-управнелние)
   * [Примери](#примери)
5. [Копаене на Monero](#5-копаене-на-monero)
6. [Интересни факти](#6-интересни-факти)
7. [Връзки към:](#7-връзки)
   * [Мобилни портфейли](#мобилни-портфейли)
   * [Мрежи за търговия](#мрежи-за-търговия)
8. [Източници](#8-източници)

# 1. Увод #

През 2014 г. в *`Bitcointalk`* форумът, потребител познат с името *`thankful_for_today`* е разклонил кодът на *`Bytecoin`* в името *`BitMonero`*, което е съединение на *`Bit`* (като в *`Bitcoin`*) и *`Monero`* (буквално означава *`монета`* на Есперанто). Пускането на *`BitMonero`* е прието по много лош начин от общността, която първоначално го подкрепя. Планове да се поправи и подобри *`Bytecoin`* с промени за времето на *`блоковете`*, *`tail emission`* (излъчване на опашката) и награда за *`блок`* са били игнорирани всичките и *`thankful_for_today`* просто изчезва. Група от потребители, водени от Джони Мнемоник (Johnny Mnemonic) решават, че общността трябва да поеме проекта, и след пет дни го правят, както и променят името на *`Monero`* (Monero).

На 10 януари 2017 г., поверителността на Monero транзакциите е допълнително подсилена, чрез приемането на алгоритъм, наречен *`Confidential Transactions`* (Поверителни Транзакции), разработен от един от разработчиците на *`Bitcoin Core`*, Грегъри Максуел (Gregory Maxwell). Този алгоритъм позволява скриването на количествата в транзакциите, които биват изпратени, в комбинация с подобрена версия на *`Ring Signatures`*.

(`XMR`) е трибуквения код на валутата, дефиниран от международния стандарт **ISO 4217**, установен от Международната организация по стандатризация (`ISO`).

---

# 2. Концепция на валутата #

#### Какво е Monero? ####
Monero е децентрализирана криптовалута, което означава, че е сигурна дигитална парична единица управлявана от мрежа от потребители. Транзакциите се потвърждават чрез разпределен консенсус и след това се записват неизменно на блоковата верига. Не е нужно доверяването на трета страна, за да се поддържа Monero безопасно.

Блокчейнът на Monero е нарочно направен да бъде непрозрачен. Това прави детайлите по транзакциите - като например идентичност на подател и получател и размера на всяка транзакция - анонимни като маскира адресите, използвани от участниците.

Заедно с анонимността, процесът по копаене на Monero е базиран върху концепция - принципът, че всички хора са равни и заслужават равни възможности. При пускането на Monero, разработчиците не са запазили дял от валутата за себе си и разчитаха на приноса и подкрепата на общността за бъдещите разработки на виртуалната валута.

Monero поддържа процес на копаене, при който хората получават възнаграждения за своята дейност чрез участие в минни басейни или самостоятелно копаене. Копаенето на Monero може да става и от стандартен компютър, като не е необходим специфичен хардуер като например *`ASIC`* копачи.

Monero върви на всички водещи платформи и операционни системи, включително *`Windows, macOS, Linux, Android и дори FreeBSD`*.

Monero използва алгоритъм _`proof-of-work`_ ([PoW][3]), който е предназначен за широк набор от процеси. Това означава, че добиването на монеро е достъпно за всякакъв род участници, а не само за големи добиващи пулове.
Всъщност _`proof-of-work`_ механизма е система за гласуване. Потребителите гласуват за правилния ред на транзакциите, за включване на нови функции в протокола и за по-справедливо разпределение на парите. За това е важно, по време на процеса на гласуване, всички участници да имат равни права.
Механизвъм се променя приблизително на всеки 6 месеца за да обезкуражи разработването на *`ASIC`* ([какво е ASIC Miner][4]).

---

# 3. Предимства и недостатъци #

## Предимства ##

#### Какви са предимствата на Monero пред други крипто валути? ###

Monero има няколко предимства пре криптовалутите от първо поколение, като биткойн.

* *`Bitcoin и Ethereum`* използват прозрачни блокови вериги, което означава, че транзакциите са лесно проследими. Адресите на изпращача и получателя за тези транзакции могат да доведат до потенциалното свързване със самоличността на човек от реалния свят. Monero използва пръстен с подписи ([Ring signatures][1]), поверителни транзакции ([RingCT][2]) и непроследими адреси, които позволяват да се прикрият личните данни на изпращачите и получателите, както и по отношение на сумата. На практика се прави микс от потребителските ключове с публичните ключове достъпни в блокчейна на Monero.

* Monero миксира всички монети, при всяка транзакция, което е нещо, което другите криптовалути, като например Даш (DSH) и Зеткеш (ZEC) не правят. Например Даш комбинира транзакции за да намали шансовете за разкриване на идентичността на участниците в транзакциите. Зеткеш пък, предлага избор за запазване на идентичността, като не споменава стойността на транзакцията.

* Плюс при анонимността е, че всяка Monero монета е заменима или разменяема, подобно на традиционната валута, която използваме в ежедневието. Няма значение дали получаваме монета Х или У, защото те са едни и същи. Две ХМRX монети, не могат да бъдат разграничени една от друга на база на историята на транзакциите. Поради тази причина монетите на Monero не могат да бъдат включени в черните списъци на доставчици или борси, тъй като предишните транзакции на Monero не могат да бъдат свързани. От друга страна Биткойнът например, се записва на блокчейн, който показва историята на транзакциите. Това означава, че някои монети, могат да бъдат свързвани с определени събития, включително и негативни такива, като например кражба. Тези монета, могат да бъдат много по-малко желани от потребителите.

* Адаптивно мащабиране: блоковете на Monero се създават на всеки 2 минути, в сравнение с 10 минути за биткойн. Блоковете на Bitcoin имат максимален размер и колкото се може повече транзакции за 10 минути, не всички от тях намират място в следващия, предстоящ блок. Това води до забавени плащания, както и до неуспешни плащания. Необходими са по-високи такси за транзакции в мрежата на Bitcoin, за да се пригоди към транзакцията в първия наличен блок. Monero е различен в това, че има адаптивен размер на блока, което означава, независимо колко транзакции се извършват в рамките на тези 2 минути, скорошната транзакция винаги ще намери място в следващия блок. Времето на сделката е бързо и плащането на допълнителни транзакционни такси няма да ускори потвърждаването на транзакцията.

* Интегрирането на [Kovri][21] в Monero проекта. Въпреки, че е все още в начален етап, това допълнително ще засили сигурността на Monero. Kovri е I2P рутер написан на C++. I2P е скрита мрежа по подобието на Tor със няколко технически различия. Целта е да се скрие първоисточника на транзакцията, така че другите разклонения да не знаят кой я е създал. Kovri също може да бъде използван за скриването на целия Monero трафик, така че да скрие изобщо ползването на валутата. И все пак това не е имплементирано напълно и все още се правят тестове.

## Недостатъци ##

#### Какви са Недостатъци на Monero пред другите крипто валути? ###

* Monero не е толкова популярна като *`Bitcoin, Ethereum, Litecoin или ripple`*, но си има своите поддръжници, които харесват криптовалутата заради нейната строга поверителност. Колкото и добре да звучи на теория, заради тази поверителност на Monero се закача и негативна репутация. Често е обвинявана да бъде криптовалутата, която е използвана за разплащане при нелегални дейности.

* Поради използването на пръстен с подписи се добавя допълнителна информация към всяка транзакция, което значително увеличава размера на блоковата верига. Към момента, големината на блоковата верига на Monero надвишава 60GB и ще продължи бързо да се увеличава засягайки използваемостта. Това прави много трудоемко добавянето на нови хора към веригата, защото първоначално те ще трябва да обработят цялата тази информация.

* Тъй като не е базирана на Bitcoin, Monero среща затруднения при добавянето на нови функционалности.

---

# 4. Инструменти за разработка и управнелние #

#### Как да разработваме върху Monero? ####

Един от вариантите е да се използват json-rpc колове от всеки език способен на това (пример [Python](#user-content-python-example)). Друг начин е да използвате публични API на съществуващи Monero услуги (пример [Публични API](#user-content-public-api). Някои Monero функции дори са налични в JavaScript, което може да се види от изходния код на [mymonero.com][24]. Това позволява разработването на някои Уеб приложения само с HTML и JavaScript.

Другия начин е директно да се докоснем до C++ библиотеките на Monero. Обаче няма официална документация и упътване. Въпреки това в мрежата се намират примери как може да се достъпят библиотеките на Monero със C++. Ще разгледаме пример предоставен от [Monero Examples][25], как да достъпи блокчейн мрежата със C++ (пример [Monero C++](#user-content-monero-cpp).

## Примери ##

<span id="python-example"><strong>(Python)</strong></span>
<br/>

__Взимане на баланса на портфейл__
    
    import requests
    import json
    
    def main():
        url = "http://localhost:18082"/json_rpc"
        headers = {'content-type': 'application/json'}
        
        rpc_input = {
            "method": "balance"
        }
        
        response = response.posrt(
            url,
            data = json.dumps(rpc_input),
            headers = headers)
        
        print(json.dumps(response.json(), indent=4))
        
    if __name__ == "__main__"":
        main()

Функцията генерира следния резултат:

    {
        "jsonrpc": "2.0",
        "id": 0,
        "result": {
            "unlocked_balance": 4760000000000,
            "balance": 4760000000000
        }
    }
    
За още примери на Python посетете следния линк -> [Python for Monero][22]

---

<span id="public-api"><strong>(Публични API)</strong></span>
<br/>

__Заявка за актуална статистика за монетите__

> Адрес: http://moneroblocks.info/api/get_stats/

Отговор в JSON формат:
   
    {
        "difficulty":36462691353,
        "height":1843144,
        "hashrate":303855761.275,
        "total_emission":"17004173233966300288",
        "last_reward":2753416616971,
        "last_timestamp":1558883987
    }

Към API документацията -> [moneroblocks][23]

---

<span id="monero-cpp"><strong>(Monero C++)</strong></span>
<br/>

__Достъпване на блокчейн мрежата на Monero със C++__

Класа `MircoCore` е микро версия на cryptonode::core класа. Класа `cryptonode::core` е основния клас с достъп до блоковата верига, който се използва от процеса обработващ заявките на Monero. В този пример `init` метода на класа е най-важния. Главната цел на `init` метода е да създаде инстанция на класа `Blockchain`. `Blockchain` е интерфейс от високо ниво към базата данни на блоковата верига. В примера на по-ниско ниво се намира класа `BlockchainLMDB`, който също може да бъде достъпен през обекта `Blockchain`.

    #include "MicroCore.h"
    namespace xmreg
    {
      MicroCore::MicroCore():
              m_mempool(m_blockchain_storage),
              m_blockchain_storage(m_mempool)
      {}
      
      bool
      MicroCore::init(const string& blockchain_path)
      {
          int db_flags = 0;

          db_flags |= MDB_NOSYNC;

          BlockchainDB* db = nullptr;
          db = new BlockchainLMDB();

          try
          {
              db->open(blockchain_path, db_flags);
          }
          catch (const std::exception& e)
          {
              cerr << "Грешка при отваряне на базата: " << e.what();
              return false;
          }

          if(!db->is_open())
          {
              return false;
          }
          return m_blockchain_storage.init(db, false);
      }

      Blockchain&
      MicroCore::get_core()
      {
          return m_blockchain_storage;
      }

      MicroCore::~MicroCore()
      {
          m_blockchain_storage.deinit();
      }
    }
    
Това е главния файл на примера. За да работи програмата са нужни четири входни параметъра:
* `address` - адреса на Monero
* `viewkey` - частния ключ асоцииран с предоставения адрес
* `txhash` - ид на транзакцията, чийто отговор искаме да проверим
* `bc-path` - пътят до lmdb папката на блоковата верига
За да стартирате програмата е нужно да подадете коректно поне `bc-path`. Другите опции имат подразбиращи се стойности, които работят
    
    #include <iostream>
    #include <string>
    #include "src/MicroCore.h"
    #include "src/CmdLineOptions.h"
    #include "src/tools.h"
    
    using namespace std;
    using boost::filesystem::path;
    using boost::filesystem::is_directory;

    // без това няма да работи
    unsigned int epee::g_test_dbg_lock_sleep = 0;

    int main(int ac, const char* av[]) {
      xmreg::CmdLineOptions opts {ac, av};

      auto help_opt = opts.get_option<bool>("help");

      if (*help_opt)
      {
          return 0;
      }

      auto address_opt = opts.get_option<string>("address");
      auto viewkey_opt = opts.get_option<string>("viewkey");
      auto tx_hash_opt = opts.get_option<string>("txhash");
      auto bc_path_opt = opts.get_option<string>("bc-path");

      string default_monero_dir = tools::get_default_data_dir();
      
      string default_lmdb_dir   = default_monero_dir + "/lmdb";

      string address_str = address_opt ? *address_opt :   "48daf1rG3hE1Txapcsxh6WXNe9MLNKtu7W7tKTivtSoVLHErYzvdcpea2nSTgGkz66RFP4GKVAsTV14v6G3oddBTHfxP6tU";
      string viewkey_str = viewkey_opt ? *viewkey_opt : "1ddabaa51cea5f6d9068728dc08c7ffaefe39a7a4b5f39fa8a976ecbe2cb520a";
      string tx_hash_str = tx_hash_opt ? *tx_hash_opt : "66040ad29f0d780b4d47641a67f410c28cce575b5324c43b784bb376f4e30577";
      path blockchain_path = bc_path_opt ? path(*bc_path_opt) : path(default_lmdb_dir);

      if (!is_directory(blockchain_path))
      {
          cerr << "Given path \"" << blockchain_path   << "\" "
               << "is not a folder or does not exist" << " "
               << endl;
          return 1;
      }
      blockchain_path = xmreg::remove_trailing_path_separator(blockchain_path);

      cout << "Blockchain path: " << blockchain_path << endl;

      uint32_t log_level = 0;
      epee::log_space::get_set_log_detalisation_level(true, log_level);
      epee::log_space::log_singletone::add_logger(LOGGER_CONSOLE, NULL, NULL);
     
      xmreg::MicroCore mcore;

      if (!mcore.init(blockchain_path.string()))
      {
          cerr << "Error accessing blockchain." << endl;
          return 1;
      }
      cryptonote::Blockchain& core_storage = mcore.get_core();

      uint64_t height = core_storage.get_current_blockchain_height();

      cout << "Current blockchain height: " << height << endl;
      
      cryptonote::account_public_address address;

      if (!xmreg::parse_str_address(address_str,  address))
      {
          cerr << "Cant parse string address: " << address_str << endl;
          return 1;
      }
      
      crypto::secret_key prv_view_key;
      if (!xmreg::parse_str_secret_key(viewkey_str, prv_view_key))
      {
          cerr << "Cant parse view key: " << viewkey_str << endl;
          return 1;
      }
      
      cryptonote::transaction tx;

      if (!xmreg::get_tx_pub_key_from_str_hash(core_storage, tx_hash_str, tx))
      {
          cerr << "Cant find transaction with hash: " << tx_hash_str << endl;
          return 1;
      }


      crypto::public_key pub_tx_key = cryptonote::get_tx_pub_key_from_extra(tx);

      if (pub_tx_key == cryptonote::null_pkey)
      {
          cerr << "Cant get public key of tx with hash: " << tx_hash_str << endl;
          return 1;
      }
      
      crypto::key_derivation derivation;

      if (!generate_key_derivation(pub_tx_key, prv_view_key, derivation))
      {
          cerr << "Cant get dervied key for: " << "\n"
               << "pub_tx_key: " << prv_view_key << " and "
               << "prv_view_key" << prv_view_key << endl;
          return 1;
      }
      cout << "\n"
           << "address          : <" << xmreg::print_address(address) << ">\n"
           << "private view key : "  << prv_view_key << "\n"
           << "tx hash          : <" << tx_hash_str << ">\n"
           << "public tx key    : "  << pub_tx_key << "\n"
           << "dervied key      : "  << derivation << "\n" << endl;
           
      size_t output_no = tx.vout.size();
      uint64_t money_transfered {0};

      for (size_t i = 0; i < output_no; ++i)
      {
          crypto::public_key pubkey;

          crypto::derive_public_key(derivation,
                                    i,
                                    address.m_spend_public_key,
                                    pubkey);

          const cryptonote::txout_to_key tx_out_to_key
                  = boost::get<cryptonote::txout_to_key>(tx.vout[i].target);


          cout << "Output no: " << i << ", " << tx_out_to_key.key;

          if (tx_out_to_key.key == pubkey)
          {
              money_transfered += tx.vout[i].amount;
              cout << ", mine key: " << cryptonote::print_money(tx.vout[i].amount) << endl;
          }
          else
          {
              cout << ", not mine key " << endl;
          }
    }
    cout << "\nTotal xmr received: " << cryptonote::print_money(money_transfered) << endl;
    cout << "\nEnd of program." << endl;

    return 0;

Изпълняваме програмата както следва:
> ./xmreg01 --address 48daf1rG3hE1Txapcsxh6WXNe9MLNKtu7W7tKTivtSoVLHErYzvdcpea2nSTgGkz66RFP4GKVAsTV14v6G3oddBTHfxP6tU --viewkey 1ddabaa51cea5f6d9068728dc08c7ffaefe39a7a4b5f39fa8a976ecbe2cb520a --txhash 66040ad29f0d780b4d47641a67f410c28cce575b5324c43b784bb376f4e30577

Изпълнението извежда следния резултат: 
     
    address          : <48daf1rG3hE1Txapcsxh6WXNe9MLNKtu7W7tKTivtSoVLHErYzvdcpea2nSTgGkz66RFP4GKVAsTV14v6G3oddBTHfxP6tU>
    private view key : <1ddabaa51cea5f6d9068728dc08c7ffaefe39a7a4b5f39fa8a976ecbe2cb520a>
    tx hash          : <66040ad29f0d780b4d47641a67f410c28cce575b5324c43b784bb376f4e30577>
    public tx key    : <0851f2ec7477b82618e028238164a9080325fe299dcf5f70f868729b50d00284>
    dervied key      : <8017f9944635b7b2e4dc2ddb9b81787e49b384dcb2abd474355fe62bee79fdd7>

    Output no: 0, <c65ee61d95480988c1fd70f6078afafd4d90ef730fc3c4df59951d64136e911f>, not mine key
    Output no: 1, <67a5fd7e06640942f0d869e494fc9d297d5087609013cd3531d0da55de19045b>, not mine key
    Output no: 2, <a9e0f19422e68ed328315e92373388a3ebb418204a36d639bd1f2e870f4bc919>, mine key: 0.800000000000
    Output no: 3, <849b56538f199f0a7522fcd0b132e53eec4a822e9b70b0e7e6c9e2632f1328db>, mine key: 4.000000000000
    Output no: 4, <aba2e362f8ae0d79a4f33f9e4e27eecf79ad9c53eae86c27aa0281fb29aa6fdc>, not mine key
    Output no: 5, <2602e4ac211216571ab1afe631aae1f905f252a1150cb8c4e5f34b820d0d6b4a>, not mine key

    Total xmr received: 4.800000000000

:exclamation: За пълния пример с настройките и коментари посетете [Monero Examples][25].

---

# 5. Копаене на Monero #

Преди да вземете първите си монети има няколко неща,  които трябва да знаете.

### Преди всичко ви трябва портфейл ###

Преди да започнете да копаете трябва да имате портфейл. Официалния портфейл създаден от Monero екипа е [`Official GUI/CLI Wallet`](https://getmonero.org/downloads/). Малко по-труден е за настройване, но е по-защитен. За други порфейли виж [`Връзки`](#7-връзки).
Преди да продължите напред се уверете, че имате адреса на вашия портфейл. Стандартния Monero портфейл трябва да има 95 символа. Пример за адрес на Monero портфейл би изглеждал `41dtfjtrvG3ZKTpzaVqTpjasKaPTGVBRRYJnPrp14mne7aWL6jVasPaD3AZSdw24mkJ8GpLkMNXENJWu2LuRb78v1HJYvcB`. Има два други типа Monero портфейли. Интегрираният адрес и стандартният адрес на портфейла с идентификационен номер за плащане.
<strong>Интегриран адрес.</strong> Съдържа 106 символа и е подобен на адреса с идентификационния номер за плащане, но втория автоматично се обединява в главен адрес(затова са и 106 символа). <strong>Адрес с идентификатор за плащане.</strong> Oбикновено се използва от борсите, когато една борса има един Monero портфейл, но различни идентификационни номера за техните клиенти.

### Стартиране на копаене ###

За да започнем да копаем ни е необходим подходящ софтуер за копаене. Благодарение на Monero общността има софтуер за копаене с отворен код - [`XMR-Stak`](https://github.com/fireice-uk/xmr-stak/releases). XMR-Stak сега поддържа графични процесори, AMD и NVIDIA в един унифициран миньор. Така че просто трябва да го изтеглите и разархивирайте. Когато го стартирате за пръв път XMR-Stak ще ви попита няколко въпроса и след това ще ви генерира конфигурационен файл. Това го прави идеален за нови миньори. 

| Въпроси: |
| :---  |
| Do you want to use the HTTP interface: **`0`** |
| Please enter the currency that you want to mine: **`monero`** |
| Pool address: **`xmrpool.eu:3333`** Може да изберете порт 5555 или 7777 ако имате добър хардуер. |
| Username: **`YOUR_WALLET_ADDRESSYour`** 95 символния адрес на портфейла създаден по-рано. |
| Password: **`x`** |
| Rig identifier: Може да именувате вашите копачи в случай, че имате повече от един. Може да бъде оставено празно. |
| Does this pool support TLS/SSL: **`x`** |
| Do you want to use nicehash on this pool: **`x`** |
| Do you want to use multiple pools: **`x`** |

След като отговорите на всички въпроси `XMR-Stak` трябва да стартира процеса по копаене. Може да изведе съобщение за грешка при стартиране, тъй като трябва да реши какъв хардуер имате и как да копае. Важно е да отбележите, че след отговарянето на въпросите миньорът създава файл с име `config.txt`. Можете лесно да редактирате конфигурацията и тя ще бъде използвана по време на следващото изпълнение. Ако развалите конфигурацията можете просто да я изтриете и да стартирате процеса по отговарянето на въпросите отново.

### Плащането ###

Трябва да знаете няколко неща. Първо моментния баланс. Когато сложите адреса на портфейла си на главната страница, ще видите моментния си баланс. Моментния баланс отразява текущото ви състояние на добити монети. Когато пулът открие блок и блока е готов, пулът калкулира дяловете, които всеки миньор ще получи в своя моментен баланс в зависимост от работата, която са свършили (количеството на хешовете). Основното правило е, че колкото по-голям е вашия хеш рейтинг, толкова повече акции изпращате и съответно по-бързо ще се увеличава моментния ви баланс. Когато достигнете минималния праг за плащане, пулът автоматично ще ви изпрати монети. Има два различни минимални прага за плащане на `xmrpool.eu` въз основа на типа на Monero портфейл адреса:

| Праг за плащане: |
| :---  |
| Стандартен адрес на портфейл - 95 символа **`Minimum payment threshold = 0.1 XMR`** |
| Портфейл със идентификатор за плащане или интегриран адрес (106 символа) **`Minimum payment threshold = 2 XMR`** |

### Настройка на времето ###

Добре е да използвате някои от фунциите на `xmlpool.eu`.

Копаене в Monero портфейл със фиксирана сложност (сложността ще бъде 25000) (. sign)
> `YOUR_WALLET_ADDRESS.25000`

Копаене в Monero портфейл със идентификатор на работника my_rig1 (+ sign)
> `YOUR_WALLET_ADDRESS+my_rig1`

Копаене в Monero портфейл със фиксирана сложност и идентификатор на работника(името на работника винаги трябва да е последно!)
> `YOUR_WALLET_ADDRESS.25000+my_rig1`

Копаене със идентификатор на плащането (@ sign)
> `YOUR_WALLET_ADDRESS@e631ee0af71524c5`

Копаене за размяна със фиксирана сложност и ид на работника (запомнете да сложите името на работника последно)
> `YOUR_WALLET_ADDRESS@e631ee0af71524c5.25000+my_rig1`

---

# 6. Интересни факти #

- Проектът Monero се разработва без финансиране от група програмисти като хоби.
- Шифровата основа се полага от математика Д. Бърнстейн (САЩ).
- Kraken – голяма борсова площадка от Сан Франциско, в началото на 2017 г. стартира търговията с Monero с Биткоином, USD и EUR.
- За пускане са предвидени неограничен брой монети.
- Шecтoтo мяcтo в ĸлacaциятa oт eлeĸтpoннитe пapи Моnеrо ce зaeмa пo cлeднитe ĸpитepии:
   * лиĸвиднocт — 78%;
   * пoддpъжĸa в coциaлнитe мpeжи 52%;
   * aĸтивнocт пo пoдoбpявaнe нa изxoдния ĸoд — 85%.

---

# 7. Връзки #

## Мобилни портфейли ##
Нужен е Monero портфейл за защитата на вашия капитал. Следните мобилни или леки портфейли са считани за сигурни от утвърдени членове на Monero общността:

<a href="https://cakewallet.io"><img src="https://web.getmonero.org/img/cakewallet.png" width="100" height="100"/></a>
<a href="https://monerujo.io"><img src="https://web.getmonero.org/img/Monerujo-wallet.png" width="100" height="100"/></a>
<a href="https://mymonero.com"><img src="https://web.getmonero.org/img/mymonero.png" width="100" height="100"/></a>
<a href="https://edge.app/"><img src="https://web.getmonero.org/img/edge-wallet.png" width="100" height="100"/></a>

## Мрежи за търговия ##

### Купува / Продава ###
> Петте най-добри борси за купуване и продаване на Monero според сайта [cryptoradar][10].

| Име | Държава | Купува | Продава |
| :---  | :---:   | :---:  | :---: |
| [Kraken][5]  | САЩ | 86.38 &#36; | 85.70 &#36; |
| [Bitfinex][6] | Хонконг, Китай | 86.10 &#36; | 85.64 &#36; |
| [EXMO][7] | Великобритания | 84.52 &#36; | 83.83 &#36; |
| [BC Bitcoin][9] | Великобритания | 88.53 &#36; | 82.06 &#36; |
| [BitBay][8] | Малта | 97.68 &#36;  | 80.59 &#36; |

### Обмен на XMR ###
Ето някои съвети как да използвате услугите за обмен:
* Първо трябва да създадете сметка за обмен, за да прехвърлите средствата си на някоя от борсите на Monero.
* Всеки обмен, който поддържа Monero ще ви даде идентификационен номер за плащане. Идентификаторът на плащане е уникален идентификатор на всеки потребител за обмен на Monero. Поради анонимността на Monero транзакциите, идентификаторът на плащането е единствения начин позволяващ обмена (услуга) да различи вашата транзакция от транзакциите на другите потребители.
* Уверете се, че ползвате най-новата версия на софтуера за плащане.
* Трябва също да разберете, че обмена на двойки може да се различава от обмена на ресурси.
* И накрая, в интернет има много различни уебсайтове, които могат да предлагат обменни услуги. Внимавайте, някои от тях може да са верни, но неизвестни (напр. Нови или подновени), но други може да са измамнически услуги, които открадват парите ви и поставят злонамерен софтуер на устройството ви чрез изтегляне или вграждане на приставки. Използвайте само надеждни услуги.

Списък на борсите на Monero и поддържаните от тях пазарни двойки.

| Име 	         | Търговски двойки |	 Работи от |	KYC/AML |
| :---  | :---   | :---:  | :---: |
| [ICE3X Exchange][11] | XMR/BTC, XMR/ZAR |	Юли 2013 |	Да|
| [Poloniex][12]       | XMR/LTC, XMR/ZEC, <br/> XMR/BCN, XMR/DASH, <br/> XMR/NXT, XMR/MAID, <br/> XMR/BTCD, XMR/BLK | 	Януари 2014 |	Да |
| [HitBTC][13] 	     | XMR/USDT, XMR/BTC, <br/> XMR/ETH |	Началото на 2013 |	Не задължилтено|
| [Bittrex][14] 	     | XMR/BTC, XMR/USDT 	|Началото на 2014 |	Да|
| [LocalMonero][15] 	 | Buy/Sell XMR <br/> for fiat and 10 trading pairs |	Август 2017 	|No|
| [Shapeshift][16] 	 | XMR/BTC, XMR/Dash, <br/> XMR/Ripple, XMR/NXT, <br/> XMR/Dogecoin (40+ pairs overall) |	Неизвестно |	Неизвестно|
| [Changelly][17] 	 | XMR/BTC, XMR/USDT,<br/> XMR/ETH and 60+ more trading pairs| 	2015 	|Неизвестно|
| [Evonax][18] 	     | XMR/BTC, XMR/BCH, <br/> XMR/DASH, XMR/DOGE, <br/> XMR/ETH, XMR/LTC| 	Неизвестно| 	Неизвестно|
| [Coindirect][19] 	 | BTC/XMR, ETH/XMR, <br/> LTC/XMR, USDT/XMR, <br/> BCH/XMR, DASH/XMR |	Октомври 2017 |	Не задължилтено|
| [Anycoin Direct][20] | XMR/EUR, BTC/EUR, <br/> ETH/EUR, XRP/EUR, <br/> STRAT/EUR, NEO/EUR, <br/> GAS/EUR, ETC/EUR, <br/> PIVX/EUR, XLM/EUR, <br/> QTUM/EUR, LTC/EUR, <br/> NLG/EUR, DOGE/EUR, <br/> DASH/EUR, BLK/EUR, <br/> PPC/EUR, ZEC/EUR |	Средата на 2013 |	Да |

---

# 8. Източници #

- [Monero](https://web.getmonero.org/) - Официален сайт на Monero
- [УикипедиЯ](https://bg.wikipedia.org/wiki/%D0%9C%D0%BE%D0%BD%D0%B5%D1%80%D0%BE_(%D0%BA%D1%80%D0%B8%D0%BF%D1%82%D0%BE%D0%B2%D0%B0%D0%BB%D1%83%D1%82%D0%B0)) - Monero (криптовалута)
- [Unofficial Monero Documentation](https://monerodocs.org/) - Неофициална документация на Monero
- [OnChain.bg](https://onchain.bg/crypto/monero/) - Monero (XMR) настоящата стойност, реалните перспективи и майнинг
- [Statistics](https://bitinfocharts.com/monero/) - Monero (XMR) цена, статистика и информация

[1]: https://cryptonote.org/inside#untraceable-payments
[2]: https://blog.goodaudience.com/monero-confidential-transactions-or-send-i-know-not-what-to-someone-i-know-not-whither-337f20f0d64e
[3]: https://monerodocs.org/proof-of-work/pow-in-cryptocurrencies/
[4]: https://www.ethos.io/what-are-asic-miners-cryptocurrency-mining
[5]: https://www.kraken.com/
[6]: https://www.bitfinex.com/
[7]: https://exmo.com/
[8]: https://auth.bitbay.net
[9]: https://www.bcbitcoin.co.uk
[10]: https://cryptoradar.co
[11]: https://ice3x.com/
[12]: http://poloniex.com/exchange/btc_xmr
[13]: http://hitbtc.com/
[14]: http://bittrex.com/
[15]: https://localmonero.co/
[16]: http://shapeshift.io
[17]: https://changelly.com/
[18]: http://www.evonax.com/
[19]: https://www.coindirect.com/buy/monero
[20]: https://Anycoindirect.eu
[21]: https://kovri.io
[22]: http://moneroexamples.github.io/python-json-rpc/
[23]: https://moneroblocks.info/api
[24]: https://mymonero.com
[25]: http://moneroexamples.github.io/access-blockchain-in-cpp/
