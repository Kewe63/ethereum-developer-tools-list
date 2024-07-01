# Ethereum Geliştirici Araçları Listesi
Ethereum uygulamaları geliştirmek için mevcut araçlar, bileşenler, kalıplar ve platformlar hakkında bir rehber.

Bu liste, yeni ve deneyimli blockchain geliştiricileri arasında araçların, geliştirme kalıplarının ve bileşenlerin daha iyi paylaşılması ihtiyacını gören ConsenSys ürün yöneticileri tarafından oluşturulmuştur.

Bu kaynak, öncelikle geliştirici araçlarına odaklanmayı hedeflemekle birlikte, depo ayrıca şunları içerir:
* [Ethereum Ekosistem Kaynakları](EcosystemResources.md) - Faydalı DApp'ler, eğitim kaynakları, cüzdanlar ve hizmetler.

## Katkılarınızı Bekliyoruz!

Küçük düzeltmelerden eklemek veya kaldırmak istediğiniz araçlara kadar her şey için bir pull request göndermekten çekinmeyin! Yeni bir araç eklerken, yeni geliştiricilerin anlayabileceği kısa bir açıklama eklemeyi unutmayın.

Bu listedeki yeniden yapılandırmayı daha mantıklı hale getirmek için ~100 katkıcı arasında [@corbpage](https://twitter.com/corbpage) ve [@pakaplace](https://twitter.com/Parker_Place) gibi Meridio'dan katkıda bulunanlar ile @jpantunes'e çok teşekkür ederiz.
* Çalışmayan ürünleri eklemeyeceğiz.
* Eski veya artık bakımı yapılmayan projeleri kaldıracağız.
* Açık kaynak kodu veya geliştirici yorumları olmayan ücretli / sınırlı hizmetleri olan projeler daha fazla incelenecek.

^Yukarıdaki adil mi? Görüşlerinizi buradan paylaşın - https://github.com/ConsenSys/ethereum-developer-tools-list/pull/70

## İçindekiler
- [Ethereum Geliştirici Araçları Listesi](#ethereum-geliştirici-araçları-listesi)
  - [Katkılarınızı Bekliyoruz!](#katkılarınızı-bekliyoruz)
  - [İçindekiler](#içindekiler)
  - [Yeni Geliştiriciler Buradan Başlayabilir](#yeni-geliştiriciler-buradan-başlayabilir)
  - [Geliştirici Araçları](#geliştirici-araçları)
    - [Akıllı Sözleşmeler Geliştirmek](#akıllı-sözleşmeler-geliştirmek)
      - [Akıllı Sözleşme Dilleri](#akıllı-sözleşme-dilleri)
      - [Frameworkler](#frameworkler)
      - [IDE'ler](#ide'ler)
    - [Diğer Araçlar](#diğer-araçlar)
    - [Test Blockchain Ağları](#test-blockchain-ağları)
      - [Test Ether Muslukları](#test-ether-muslukları)
    - [Ethereum ile İletişim Kurmak](#ethereum-ile-iletişim-kurmak)
      - [Frontend Ethereum API'ları](#frontend-ethereum-api'ları)
      - [Backend Ethereum API'ları](#backend-ethereum-api'ları)
      - [Bootstrap/Out-of-Box Araçlar](#bootstrapout-of-box-araçlar)
      - [Ethereum ABI (Uygulama İkili Arabirim) Araçları](#ethereum-abi-uç-araçları)
      - [Kalıplar ve En İyi Uygulamalar](#kalıplar-ve-en-iyi-uygulamalar)
        - [Akıllı Sözleşme Geliştirme Kalıpları](#akıllı-sözleşme-geliştirme-kalıpları)
        - [Yükseltilebilirlik](#yükseltilebilirlik)
    - [Altyapı](#altyapı)
      - [Ethereum İstemcileri](#ethereum-istemcileri)
      - [Depolama](#depolama)
      - [Mesajlaşma](#mesajlaşma)
    - [Dağıtım](#dağıtım)
    - [Test Araçları](#test-araçları)
    - [Güvenlik Araçları](#güvenlik-araçları)
    - [İzleme](#izleme)
    - [Diğer Çeşitli Araçlar](#diğer-çeşitli-araçlar)
    - [Akıllı Sözleşme Standartları ve Kütüphaneleri](#akıllı-sözleşme-standartları--kütüphaneleri)
      - [ERC'ler - Ethereum İstek için Yorum Deposu](#erc'ler---ethereum-istek-için-yorum-deposu)
      - [Popüler Akıllı Sözleşme Kütüphaneleri](#popüler-akıllı-sözleşme-kütüphaneleri)
    - [2. Katman Altyapı İçin Geliştirici Kılavuzları](#2-katman-altyapı-için-geliştirici-kılavuzları)
      - [Ölçeklenebilirlik](#ölçeklenebilirlik)
      - [Ödeme/State Kanalları](#ödemestate-kanalları)
      - [Plazma](#plazma)
      - [Yan Zincirler](#yan-zincirler)
      - [Gizlilik / Gizlilik](#gizlilik--gizlilik)
        - [ZK-SNARK'lar](#zk-snark'lar)
      - [Ölçeklenebilirlik + Gizlilik](#ölçeklenebilirlik--gizlilik)
      - [ZK-STARK'lar](#zk-stark'lar)
      - [Önceden Hazırlanmış UI Bileşenleri](#önceden-hazırlanmış-ui-bileşenleri)

## Yeni Geliştiriciler Buradan Başlayabilir
* [Solidity](https://soliditylang.org/) - En popüler akıllı sözleşme dili.
* [Metamask](https://metamask.io/) - DApp'lerle etkileşim için tarayıcı eklentisi cüzdan.
* [Truffle](https://trufflesuite.com/) - En popüler akıllı sözleşme geliştirme, test ve dağıtım framework'ü. Npm aracılığıyla CLI'ı yükleyin ve ilk akıllı sözleşmelerinizi yazmaya buradan başlayın.
* [Truffle boxes](https://trufflesuite.com/boxes) - Ethereum ekosistemi için paketlenmiş bileşenler.
* [Hardhat](https://hardhat.org/) - Esnek, genişletilebilir ve hızlı Ethereum geliştirme ortamı.
* [Foundry](https://book.getfoundry.sh/) - Akıllı sözleşme geliştirme araç takımı. Foundry, bağımlılıklarınızı yönetir, projenizi derler, testleri çalıştırır, dağıtır ve komut satırından zincirle etkileşimde bulunmanıza olanak tanır.
* [Cryptotux](https://cryptotux.org/) - VirtualBox'a içe aktarılabilir şekilde hazır Linux imajı, yukarıda bahsedilen geliştirme araçlarını içerir.
* [OpenZeppelin Wizards](https://docs.openzeppelin.com/contracts/5.x/wizard) - Nereden başlayacağınızı bilmiyor musunuz? İnteraktif üreteci kullanarak sözleşmenizi başlatın ve OpenZeppelin Contracts tarafından sunulan bileşenler hakkında bilgi edinin.
* [EthHub.io](https://docs.ethhub.io/) - Ethereum'un kapsamlı crowdsourced genel bakışı - tarihi, yönetişimi, gelecek planları ve geliştirme kaynakları.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Ethereum akıllı sözleşmeleri dağıtma, test etme ve etkileşim kurma için Python framework'ü.
* [Moralis](https://moralis.io) - Moralis, farklı web3 cüzdanlarını doğrulamak, blockchain verilerini verimli bir şekilde dizine eklemek ve gerçek zamanlı blockchain etkinliklerini dinlemek için kullanılabilen cross-chain Enterprise-grade Web3 API'dır.
* [Ethereum Stack Exchange](https://ethereum.stackexchange.com/) - Geliştirme yaşam döngünüze yardımcı olmak için soru gönderin ve arayın.
* [dfuse](https://dfuse.io) - Dünya standartlarında uygulamalar inşa etmek için şık blockchain API'ları.
* [Biconomy](https://biconomy.io) - Basit kullanımlı SDK kullanarak meta işlemleri kullanarak dapp'lerinizde gazsız işlemler yapın.
* [Blocknative](https://blocknative.com) — Blokzinciri olayları gerçekleşmeden önce. Blocknative'in geliştirici araçları portföyü, mempool verileriyle inşa etmeyi kolaylaştırır.
* [useWeb3.xyz](https://useweb3.xyz/) — Ethereum, blokzinciri ve Web3 geliştirme üzerine en iyi ve en son kaynakların özenle derlenmiş bir genel bakışı.
* [Geth](https://geth.ethereum.org/) — Go tabanlı bir Ethereum geliştirme istemcisi.
* [CryptoZombies](https://cryptozombies.io/) — Solidity'de akıllı sözleşmeler yazmayı öğreten etkileşimli bir kod okulu.
* [Smartcontract challenges](https://www.smartcontract.engineer/) — Sorunlarla Solidity ve Vyper öğrenin.
* [Solidity by Example](https://solidity-by-example.org/) — Basit örneklerle Solidity'e giriş.
* [L2Beat](https://l2beat.com/) - Ethereum 2. Katman çözümlerini keşfedin ve bunları kullanmanın risklerini öğrenin.
* [Tatum](https://tatum.io/) - Blokzinciri uygulamalarının geliştirilmesini hızlandıran blokzinciri geliştirme aracı. 

## Geliştirici Araçları
### Akıllı Sözleşme Geliştirme
#### Akıllı Sözleşme Dilleri
* [Solidity](https://docs.soliditylang.org/en/latest/) - Ethereum akıllı sözleşme dili
* [Vyper](https://vyper.readthedocs.io/en/latest/) - Yeni deneysel Python tabanlı programlama dili
* [Yul](https://docs.soliditylang.org/en/v0.5.3/yul.html) - Farklı backend'lerin ihtiyaçlarını karşılamak için bytecode'a derlenen ara bir programlama dili
* [Huff](https://docs.huff.sh/) - EVM opcodları yazmayı kolaylaştıran makro ve sabitler gibi özelliklere sahip bir araç, üretim için yüksek verimli sözleşmeler yazmak veya EVM hakkında yeni başlayanlar için bir yol olarak kullanılabilir.
* [Fe-Lang](https://fe-lang.org/) - Ethereum Sanal Makinesi (EVM) için statik tipli bir dil. Python ve Rust'dan ilham alınarak geliştirilmiştir.

#### Frameworkler
* [Truffle](https://trufflesuite.com/) - En popüler akıllı sözleşme geliştirme, test ve dağıtım frameworkü. Truffle suite, Truffle, [Ganache](https://github.com/trufflesuite/ganache) ve [Drizzle](https://github.com/truffle-box/drizzle-box) içerir. [Truffle hakkında derinlemesine bilgi için buraya tıklayın](https://media.consensys.net/truffle-deep-dive-what-you-need-to-know-when-developing-on-ethereum-e548d4df6e9)
* [Hardhat](https://hardhat.org/) - Esnek, genişletilebilir ve hızlı Ethereum geliştirme ortamı.
* [Foundry](https://book.getfoundry.sh/) - Akıllı sözleşme geliştirme araç takımı. Foundry, bağımlılıklarınızı yönetir, projenizi derler, test eder, dağıtır ve komut satırından zincirle etkileşimde bulunmanıza olanak tanır.
* [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Ethereum akıllı sözleşmelerini dağıtmak, test etmek ve etkileşimde bulunmak için Python frameworkü.
* [Embark](https://github.com/embark-framework/embark) - DApp geliştirme frameworkü
* [Waffle](https://getwaffle.io/) - Gelişmiş akıllı sözleşme geliştirme ve test etme için framework, küçük, esnek, hızlı (ethers.js tabanlı)
* [Dapp](https://dapp.tools/dapp/) - DApp geliştirme frameworkü, DApple'ın halefi
* [Etherlime](https://github.com/LimeChain/etherlime) - ethers.js tabanlı Dapp dağıtım frameworkü
* [Parasol](https://github.com/Lamarkaz/parasol) - Esnek ve fikirden yoksun bir tasarım sunan, test, INFURA dağıtımı, otomatik sözleşme belgeleri oluşturma gibi özelliklere sahip, çevik akıllı sözleşme geliştirme ortamı.
* [0xcert](https://github.com/0xcert/framework/) - Merkezsiz uygulamalar oluşturmak için JavaScript frameworkü
* [OpenZeppelin SDK](https://openzeppelin.com/sdk/) - Akıllı sözleşmeleri geliştirmenize, derlemenize, yükseltmenize, dağıtmanıza ve etkileşimde bulunmanıza yardımcı olacak bir araç seti.
* [sbt-ethereum](https://sbt-ethereum.io/) - Akıllı sözleşme etkileşimi ve geliştirme için sekme tamamlamalı, metin tabanlı bir konsol, cüzdan ve ABI yönetimi, ENS desteği ve ileri düzey Scala entegrasyonunu içerir.
* [Cobra](https://github.com/cobraframework/cobra) - Ethereum sanal makinesi (EVM) üzerinde akıllı sözleşme geliştirme, test etme ve dağıtma için hızlı, esnek ve basit bir geliştirme ortamı.
* [Epirus](https://docs.epirus.io/sdk/) - Akıllı sözleşme oluşturmak için Java frameworkü.
* [Etherspot](https://etherspot.io/) - Çoğu EVM uyumlu zinciri destekleyen MultiChain Akıllı Cüzdan SDK'sı.
* [Ambire Login SDK](https://github.com/AmbireTech/wallet-login-sdk) - E-posta üzerinden onboarding odaklı Akıllı Cüzdan SDK'sı, popüler EVM zincirlerini destekler.
* [Tatum](https://github.com/tatumio/tatum-js) - Blockchain uygulamalarının geliştirilmesini kolaylaştıran güçlü, özellik dolu TypeScript/JavaScript kütüphanesi.
* [Catapulta](https://catapulta.sh) - Zero config akıllı sözleşmeler dağıtım platformu, otomatik doğrulamaları otomatikleştirir ve dağıtım raporlarını paylaşır, Foundry ve Hardhat ile uyumludur.

#### IDE'ler
* [Remix](https://remix.ethereum.org/) - Dahili statik analiz, test blockchain VM'li web IDE.
* [Atom](https://atom.io/) - Atom editörü, [Atom Solidity Linter](https://atom.io/packages/atom-solidity-linter), [Etheratom](https://atom.io/packages/etheratom), [autocomplete-solidity](https://atom.io/packages/autocomplete-solidity) ve [language-solidity](https://atom.io/packages/language-solidity) paketleri ile.
* [Vim solidity](https://github.com/tomlion/vim-solidity) - Solidity için Vim sözdizim dosyası
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity) - Solidity için destek ekleyen Visual Studio Code eklentisi
* [Ethcode](https://marketplace.visualstudio.com/items?itemName=ethential.ethcode) - Solidity ve Vyper programlarını derlemek, yürütmek ve hata ayıklamak için Visual Studio Code eklentisi
* [Intellij Solidity Plugin](https://github.com/intellij-solidity/intellij-solidity/wiki) - JetBrains IntelliJ Idea IDE için açık kaynaklı eklenti, sözdizimi vurgulama, biçimlendirme, kod tamamlama vb. içerir.
* [YAKINDU Solidity Tools](https://github.com/Yakindu/solidity-ide) - Eclipse tabanlı IDE. Bağlam duyarlı kod tamamlama ve yardım, kod gezintisi, sözdizim vurgulama, yerleşik derleyici, hızlı düzeltmeler ve şablonlar içerir.
* [Eth Fiddle](https://ethfiddle.com/) - The Loom Network tarafından geliştirilen IDE, akıllı sözleşme yazmanıza, derlemenize ve hata ayıklamanıza olanak tanır. Kod parçacıklarını kolayca paylaşmanıza ve bulmanıza olanak tanır.
* [Solidity + Hardhat VSCode Extension](https://marketplace.visualstudio.com/items?itemName=NomicFoundation.hardhat-solidity) - Hardhat ekibi tarafından sunulan Solidity ve Hardhat desteği
* [Tools for Solidity VS Code Extension](https://marketplace.visualstudio.com/items?itemName=AckeeBlockchain.tools-for-solidity) - Ackee Blockchain Security tarafından geliştirilen Solidity desteği ve canlı güvenlik açığı dedektörleri

### Diğer Araçlar
* [Atra Blockchain Hizmetleri](https://console.atra.io) - Ethereum blok zincirinde merkezsiz uygulamalar oluşturmanıza, dağıtmanıza ve sürdürmenize yardımcı web hizmetleri sağlar.
* [Azure Blockchain Dev Kit for Ethereum for VSCode](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain) - Akıllı sözleşmeler oluşturmanıza ve bunları Visual Studio Code içinde dağıtmanıza olanak tanıyan VSCode eklentisi
* [Ethereum Remix- Ethereum Remix plugins in VSCode](https://marketplace.visualstudio.com/items?itemName=RemixProject.ethereum-remix) - Bu eklenti, Remix eklentilerini Visual Studio Code'a getirir.
* [Crypto Address Lens](https://marketplace.visualstudio.com/items?itemName=peetzweg.crypto-address-lens) - Ethereum tarzı adreslerle geliştirme deneyimini iyileştiren VSCode eklentisi.
* [Ramen](https://github.com/dyng/ramen) - Ethereum ile etkileşim kurmak için sezgisel, kullanımı kolay terminal arayüzü.

### Test Blockchain Ağları
* [ethnode](https://github.com/vrde/ethnode) - Geliştirme için Ethereum düğümü (Geth veya Parity) çalıştırın, `npm i -g ethnode && ethnode` kadar kolay.
* [Ganache](https://github.com/trufflesuite/ganache) - Görsel arayüze ve günlüklere sahip test Ethereum blok zinciri uygulaması
* [Kaleido](https://kaleido.io/) - Kaleido'yu konsorsiyum blok zinciri ağı oluşturmak için kullanın. PoC'ler ve testler için harika.
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - Docker konteynerinde Besu düğümlerinin özel ağını çalıştırın.
* [Orion](https://github.com/PegaSysEng/orion) - PegaSys tarafından özel işlemler gerçekleştirmek için bileşen.
* [Artemis](https://github.com/PegaSysEng/artemis) - PegaSys tarafından geliştirilen Ethereum 2.0 Beacon Zinciri'nin Java uygulaması
* [Cliquebait](https://github.com/f-o-a-m/cliquebait) - Docker örneklerinde gerçek blok zinciri ağına yakın entegrasyon ve test kabul etmeyi basitleştirir
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Gösteri ve test amaçları için docker konteynerlerinde yerel Raiden ağı çalıştırın
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Özel PoA ağları için hızlı dağıtım betikleri
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Özel PoW ağları için hızlı dağıtım betikleri
* [Ethereum on Azure](https://docs.microsoft.com/en-us/azure/blockchain/templates/ethereum-poa-deployment) - Konsorsiyum Ethereum PoA ağlarının dağıtımı ve yönetimi
* [Ethereum on Google Cloud](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/ethereum?filter=category:developer-tools) - Proof of Work temelli Ethereum ağı oluşturma
* [Infura](https://infura.io/) - Ethereum ağlarına API erişimi (Mainnet, Ropsten, Rinkeby, Goerli, Kovan)
* [CloudFlare Distributed Web Gateway](https://cloudflare.com/distributed-web-gateway/) - Kullanıcılar kendi düğümlerini çalıştırmak yerine Cloudflare üzerinden Ethereum ağına erişebilirler
* [Chainstack](https://chainstack.com/) - Paylaşılan ve özel Ethereum düğümleri hizmeti (Mainnet, Ropsten)
* [Alchemy](https://alchemyapi.io/) - Blockchain Geliştirici Platformu, Ethereum API ve Node Hizmeti (Mainnet, Ropsten, Rinkeby, Goerli, Kovan)
* [ZMOK](https://zmok.io/) - JSON-RPC Ethereum API (Mainnet, Rinkeby, Front-running Mainnet)
* [Watchdata](https://watchdata.io) - Ethereum blok zincirine basit ve güvenilir API erişimi sağlar
* [cheapETH](https://cheapeth.org/) - Ucuz ve kolay geliştirme için %100 uyumlu Ethereum ağı
* [Kurtosis' eth2-package](https://github.com/kurtosis-tech/eth2-package) - Docker veya Kubernetes üzerinde yeniden üretilebilir, özel test ağları oluşturmak için açık kaynaklı bir araç. Tüm önemli EL/CL istemci uygulamalarını destekler ve Flashbot'un mev-boost altyapısı ile otomatik olarak gelir.
  
#### Test Ether Faucet'leri

* [Kovan faucet](https://github.com/kovan-testnet/faucet)
* [Goerli faucet1](https://goerlifaucet.com/)
* [Goerli faucet2](https://goerli-faucet.pk910.de/)
* [Rinkeby faucet](https://faucet.rinkeby.io/) [DEPRECATED NETWORK]
* [Ropsten faucet (MetaMask)](https://faucet.metamask.io/) [DEPRECATED NETWORK]
* [Ropsten faucet (rpanic)](https://faucet.rpanic.com) [DEPRECATED NETWORK]
* [Holesky faucet](https://stakely.io/en/faucet/ethereum-holesky-testnet-eth)
* [Universal faucet](https://faucets.blockxlabs.com/)
* [Nethereum.Faucet](https://github.com/Nethereum/Nethereum.Faucet) - Bir C#/.NET faucet
* [Chainlink Faucet](https://faucets.chain.link/sepolia)

### Ethereum İletişimi
#### Frontend Ethereum API'leri
* [Web3.js](https://github.com/ethereum/web3.js/) - JavaScript Web3
* [Eth.js](https://github.com/ethjs) - JavaScript Web3 alternatifi
* [Ethers.js](https://github.com/ethers-io/ethers.js/) - JavaScript Web3 alternatifi, kullanışlı yardımcı programlar ve cüzdan özellikleri
* [useDApp](https://usedapp.io) - Ethereum üzerinde hızlı DApp geliştirme için React tabanlı bir framework
* [light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js) - Hafif istemciler için optimize edilmiş yüksek seviye reaktif JS kütüphanesi
* [Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper) - TypeScript Web3 alternatifi
* [Ethereumjs](https://github.com/ethereumjs/) - Ethereum için yardımcı işlevlerin bir koleksiyonu, örneğin [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) ve [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)
* [Moralis NextJS SDK](https://github.com/MoralisWeb3/Moralis-JS-SDK/tree/main/packages/next) - NextJS DApp'leri için kullanımı kolay React hook'ları kütüphanesi
* [Alchemy-web3.js](https://github.com/alchemyplatform/alchemy-web3) - Alchemy'nin gelişmiş API'lerine otomatik yeniden denemeler, [Alchemy'nin geliştirilmiş WebSocket bağlantılarına](https://docs.alchemyapi.io/documentation/alchemy-web3/enhanced-web3-api) ve güçlü websocket bağlantılarıyla JavaScript Web3 sarmalayıcısı.
* [flex-contract](https://github.com/merklejerk/flex-contract) ve [flex-ether](https://github.com/merklejerk/flex-ether) - Akıllı sözleşmelerle etkileşim ve işlem yapmak için modern, yapılandırma gerektirmeyen yüksek seviye kütüphaneler.
* [ez-ens](https://github.com/merklejerk/ez-ens) - Basit, yapılandırma gerektirmeyen Ethereum Name Service adres çözücüsü.
* [web3x](https://github.com/xf00f/web3x) - Web3.js'nin TypeScript portu. Avantajları arasında küçük boyutlu yapılar ve tam tür güvenliği, özellikle sözleşmelerle etkileşim sırasında.
* [Nethereum](https://github.com/Nethereum/) - Çapraz platform Ethereum geliştirme çerçevesi
* [dfuse](https://github.com/dfuse-io/client-js) - [dfuse Ethereum API](https://dfuse.io) kullanımı için TypeScript kütüphanesi
* [Drizzle](https://github.com/truffle-box/drizzle-box) - Redux kütüphanesi, bir frontend'i bir blockchain'e bağlar
* [Tasit SDK](https://github.com/tasitlabs/tasitsdk) - React Native kullanarak yerel mobil Ethereum dapp'leri oluşturmak için JavaScript SDK
* [useMetamask](https://github.com/mdtanrikulu/use-metamask) - Ethereum ĐApp projelerinde Metamask'ı yönetmek için özel bir React Hook
* [WalletConnect](https://walletconnect.org/) - Dapp'leri cüzdanlara bağlamak için açık protokol
* [Subproviders](https://0x.org/docs/tools/subproviders) - [Web3-provider-engine](https://github.com/MetaMask/web3-provider-engine) ile birlikte kullanılmak üzere birkaç kullanışlı alt sağlayıcı (örneğin, Ledger donanım cüzdanı desteği eklemek için LedgerSubprovider)
* [ethvtx](https://github.com/ticket721/ethvtx) - ethereum'a hazır ve çerçeve bağımsız redux mağaza yapılandırması. [dokümantasyon](https://ticket721.github.io/ethvtx/)
* Strictly Typed - JavaScript alternatifleri
    * [elm-ethereum](https://github.com/cmditch/elm-ethereum)
    * [purescript-web3](https://github.com/f-o-a-m/purescript-web3)
* [ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer) - Tek bir arayüz kullanarak farklı blockchain'lerle (Ethereum dahil) iletişim
* [Delphereum](https://github.com/svanas/delphereum) - Ethereum blockchain için Delphi arayüzü, Windows, macOS, iOS ve Android için yerel dApp'ler geliştirme olanağı sağlar.
* [Torus](https://tor.us/) - dApp'lerinize sorunsuz bir giriş deneyimi sağlamak için açık kaynaklı SDK
* [Fortmatic](https://fortmatic.com/) - Uzantı veya indirme gerektirmeden web3 dApp'leri oluşturmak için kullanımı kolay bir SDK
* [Portis](https://portis.io/) - Bir şey yüklemeden DApps ile kolay etkileşim sağlayan SDK'ya sahip, güvenilir bir cüzdan
* [create-eth-app](https://github.com/paulrberg/create-eth-app) - Bir komutla Ethereum tabanlı ön uç uygulamaları oluşturun.
* [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2) - Akıllı sözleşmeler oluşturmak için yeni başlayanlar için kolayca çatal yapılabilir github
* [Notify.js](https://blocknative.com/notify) - Kullanıcılarınıza gerçek zamanlı bildirimler sunun. Hızlı Yükseltmeler ve İptaller için yerleşik destek ile, Blocknative Notify.js kullanıcıların güvenle işlem yapmalarına yardımcı olur. Notify.js entegre etmek kolaydır ve hızlı özelleştirilebilir.
* [Quiver](https://raid-guild.github.io/quiver/) - Ethereum dApp'ler için React hook ve bileşen koleksiyonu. Raid Guild tarafından geliştirilmiştir.
* [Rainbow](https://www.rainbowkit.com/) - RainbowKit, dApp'ınıza cüzdan bağlantısı eklemeyi kolaylaştıran bir React kütüphanesidir. Kullanımı sezgisel, duyarlı ve özelleştirilebilirdir.
* [Nexth](https://github.com/wslyvh/nexth) - Web3 projelerinizi hızlı bir şekilde yayınlamak için Next.js + Ethereum başlangıç ​​kiti ⚡
* [signature-validator](https://github.com/AmbireTech/signature-validator/) - TypeScript kütüphanesi, hesap soyutlamasını (ERC-6492, ERC-1271) ve geleneksel EOA imzalarını evrensel olarak doğrular.


#### Arka Uç Ethereum API'leri

* [Web3.py](https://github.com/ethereum/web3.py) - Python Web3
* [Web3.php](https://github.com/sc0Vu/web3.php) - PHP Web3
* [Ethereum-php](https://github.com/digitaldonkey/ethereum-php) - PHP Web3
* [Web3j](https://github.com/web3j/web3j) - Java Web3
* [ethers-kt](https://github.com/Kr1ptal/ethers-kt) - Async, high-performance Kotlin library for interacting with EVM-based blockchains. Targeting JVM and Android platforms.
* [Nethereum](https://nethereum.com/) - .Net Web3
* [Ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ruby Web3
* [rust-web3](https://github.com/tomusdrw/rust-web3) - Rust Web3
* [Web3.hs](https://hackage.haskell.org/package/web3) - Haskell Web3
* [KEthereum](https://github.com/komputing/KEthereum) - Kotlin Web3
* [web3dart](https://github.com/xclud/web3dart) - Dart Web3
* [Moralis NodeJS SDK](https://github.com/MoralisWeb3/Moralis-JS-SDK) - Moralis ile entegre olan NodeJS SDK'sı, EVM zincirlerini dizine eklemek için kullanılır.
* [Moralis Python SDK](https://github.com/MoralisWeb3/Moralis-Python-SDK) - Moralis ile entegre olan Python SDK'sı, EVM zincirlerini dizine eklemek için kullanılır.
* [Eventeum](https://github.com/ConsenSys/eventeum) - Ethereum akıllı kontrat olayları ile arka uç mikrohizmetleri arasında köprü görevi görür, Java dilinde Kauri tarafından yazılmıştır.
* [Ethereumex](https://github.com/mana-ethereum/ethereumex) - Ethereum blockchain için Elixir JSON-RPC istemcisi.
* [Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway) - Ethereum düğümlerini yedekleme ve yük dengeleme amacıyla çalıştırmanıza olanak tanıyan, Infura'nın alternatifi olarak veya üzerine çalışan, Golang dilinde yazılmış bir ağ geçidi.
* [EthContract](https://github.com/AgileAlpha/eth_contract) - Elixir dilinde ETH akıllı kontrat sorgulamaya yardımcı olan yöntemlerin bir seti.
* [Marmo](https://marmo.io/) - Ethereum ile etkileşimi basitleştiren Python, JS ve Java SDK'sı. İşlem maliyetlerini relayer'lara devrederek çalışır.
* [Ethereum Logging Framework](https://bitbucket.csiro.au/users/kli039/repos/ethereum-logging-framework/browse) - Ethereum uygulamaları ve ağları için gelişmiş günlükleme yetenekleri sağlar, sorgu dili, sorgu işlemcisi ve günlükleme kodu oluşturma içerir.
* [Watchdata](https://watchdata.io) - Ethereum blockchain'e basit ve güvenilir API erişimi sağlar.
* [w3](https://github.com/lmittmann/w3) - İlk sınıf ABI desteği ile hızlı ve modüler Golang JSON RPC istemcisi.
* [Transpose](https://transpose.io) - Ölçeklenebilir şekilde insan okunabilir Ethereum verilerine erişim sağlayan güçlü API'ler.
* [Web3-Ethereum-Defi](https://github.com/tradingstrategy-ai/web3-ethereum-defi) - Python uygulamalarınıza DeFi protokollerini entegre etmenizi sağlayan, veri araştırma ve ticaret araçları sunan bir kütüphane.
* [Basement](https://basement.dev) - Ethereum veya op-stack zincirlerinde GraphQL, SQL veya no-code kullanarak web3 verilerini dizine ekleyen bir araç.
* [GhostGraph](https://ghostgraph.xyz) - Solidity kullanarak EVM zincir endeksleyicileri oluşturmanın en kolay yolu.

#### Bootstrap/Out-of-Box Araçları
* [Truffle boxes](https://trufflesuite.com/boxes) - Ethereum ekosistemi için paketlenmiş bileşenler
* [Ethereum Boilerplates](https://github.com/ethereum-boilerplate/ethereum-boilerplate) - Herhangi bir EVM zinciri üzerinde dapp oluşturmaya başlamak için tam yığın şablonu
* [Create Eth App](https://github.com/paulrberg/create-eth-app) - Bir komutla Ethereum destekli frontend uygulamaları oluşturun
* [Besu Private Network](https://besu.hyperledger.org/en/stable/Tutorials/Quickstarts/Azure-Private-Network-Quickstart/) - Docker konteynerinde Besu düğümlerinin özel ağını çalıştırın
* [Testchains](https://github.com/Nethereum/TestChains) - Hızlı yanıt için önceden yapılandırılmış .NET geliştirme ağları (PoA)
* [Blazor/Blockchain Explorer](https://github.com/Nethereum/NethereumBlazor) - Wasm blockchain gezgini (işlevsel örnek)
* [Local Raiden](https://github.com/ConsenSys/Local-Raiden) - Demo ve test amaçları için yerel Raiden ağı Docker konteynerlerinde çalıştırın
* [Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts) - Özel PoA ağları için kullanıma hazır dağıtım betikleri
* [Parity Demo-PoA Tutorial](https://wiki.parity.io/Demo-PoA-tutorial.html) - Parity otorite turu uzlaşmasıyla 2 düğümlü PoA test ağı oluşturma adım adım kılavuzu
* [Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network) - Özel PoW ağları için kullanıma hazır dağıtım betikleri
* [Kaleido](https://kaleido.io/) - PoC'ler ve testler için Kaleido kullanarak konsorsiyum blockchain ağı oluşturun
* [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties API ve akıllı sözleşmelerin yerel kum havuzu uygulaması, Truffle Box olarak kullanılabilir
* [aragonCLI](https://github.com/aragon/aragon-cli) - Aragon uygulamaları ve organizasyonları oluşturmak ve geliştirmek için kullanılır.
* [ColonyJS](https://github.com/JoinColony/colonyJS) - Colony Network akıllı sözleşmeleriyle etkileşim için bir API sağlayan JavaScript istemcisi.
* [ArcJS](https://github.com/daostack/arc.js) - JavaScript uygulamalarının DAOstack Arc ethereum akıllı sözleşmelerine erişimini kolaylaştıran kütüphane.
* [Arkane Connect](https://docs.arkane.network/pages/connect-js.html) - Arkane Network ile etkileşim için bir API sağlayan JavaScript istemcisi, kullanıcı dostu dapp'ler oluşturmak için cüzdan sağlayıcısı.
* [Onboard.js](https://blocknative.com/onboard) - Onboard, projenize çoklu cüzdan desteği eklemenin hızlı ve kolay yoludur. 20'den fazla benzersiz donanım ve yazılım cüzdanı için dahili modülleri ile Onboard, size zaman ve baş ağrısı tasarrufu sağlar.
* [web3-react](https://github.com/NoahZinsmeister/web3-react) - Tek sayfalık Ethereum dApp'ler oluşturmak için React çerçevesi
* [Kurtosis' eth2-package](https://github.com/kurtosis-tech/eth2-package) - Docker veya Kubernetes üzerinde ölçeklenebilir, tekrarlanabilir, özel test ağları oluşturmak için açık kaynaklı bir araç. Tüm önemli EL/CL istemci uygulamalarını destekler ve Flashbot'ın mev-boost altyapısıyla kutudan çıkar.

#### Ethereum ABI (Application Binary Interface) Araçları
* [Online ABI encoder](https://github.com/HashEx/abiencoder) - Solidity akıllı sözleşmenizin işlevlerini ve yapılandırıcı argümanlarını kodlamanıza olanak tanıyan ücretsiz bir ABI kodlayıcı çevrimiçi hizmeti.
* [Online Solidity ABI Encoder](https://neptunemutual.com/web3-tools/solidity-abi-encoder-online/) - Akıllı sözleşme argümanlarını kodlamak, blockchain üzerinde okuma ve yazma işlemleri yapmak için çevrimiçi Solidity ABI Kodlayıcı.
* [ABI decoder](https://github.com/ConsenSys/abi-decoder) - Ethereum işlemlerinden veri parametrelerini ve olayları çözümlemek için kütüphane
* [ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen) - Sözleşme ABI'lerinden TypeScript sözleşme sarmalları oluşturun.
* [Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) - Ethereum sözleşme ABI'sinden otomatik olarak UI form alanı tanımlamaları ve ilişkili doğrulayıcılar oluşturun
* [headlong](https://github.com/esaulpaugh/headlong/) - Java'da tip güvenli Contract ABI ve Recursive Length Prefix kütüphanesi
* [EasyDapper](https://www.easydapper.com) - Truffle sanatlarından dapp'ler oluşturun, public/private ağlarda sözleşmeleri dağıtın, canlı özelleştirilebilir bir genel sayfa sunar.
* [One Click dApp](https://oneclickdapp.com) - ABI kullanarak benzersiz bir URL'de anında bir dApp oluşturun.
* [Truffle Pig](https://npmjs.com/package/trufflepig) - Yerel geliştirme sırasında kullanılan Truffle tarafından üretilen sözleşme dosyalarını bulmak ve okumak için basit bir HTTP API sağlayan bir geliştirme aracı.
* [Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) - Solidity Akıllı Sözleşmelerine dayalı bir Nethereum tabanlı C# Arayüzü ve Servis oluşturan web tabanlı bir oluşturucu.
* [EVMConnector](https://evmconnector.dev) - Paylaşılabilir sözleşme panoları oluşturun ve EVM tabanlı blockchain fonksiyonlarıyla etkileşimde bulunun, ABI olmadan veya ABI ile.
* [contract-admin](https://github.com/upgreidas/contract-admin) - Akıllı sözleşmelerinizle etkileşim için minimalist UI aracı
* [Smart Contract GUI](https://smartcontractgui.xyz) - Herhangi bir EVM zincirindeki akıllı sözleşmelere doğrudan erişim sağlar, yalnızca ABI yükleyerek. Basit ve güçlü bir UX, akıllı sözleşme çağrılarının hızlı bir şekilde yerel olarak, test ağlarında ve ana ağlarda yürütülmesini sağlar. Ayrıca entegrasyon testleri için kullanışlı araçlarla donatılmıştır.
* [Sidekik](https://sidekik.xyz) - Kodlarken akıllı sözleşmelerinizle etkileşimde bulunmak için görsel bir UI ile akıllı sözleşmeleri hata ayıklama, test etme ve anlama. Kullanım durumları arasında kodladıkça smart contract için UI'nın canlı yeniden yüklenmesi, bir işlevi vurmak için betikler yazmadan denetim yapma, kodu dağıtmadan önce kodunuzu uçtan uca test etme ve daha fazlası bulunmaktadır.
* [Web3 Client](https://workspace.web3client.app/evm) - Web IDE size dağıtılmış akıllı sözleşmeleri yürütmenize izin verir ve diğerleri ile Paylaş. 

#### Kalıplar ve En İyi Uygulamalar

##### Akıllı Sözleşme Geliştirme için Kalıplar
* [Dappsys: Güvenli, basit ve esnek Ethereum sözleşme yapı taşları](https://github.com/dapphub/dappsys)
    * Ethereum/Solidity'de yaygın problemler için çözümler sunar, örn.
        * [Beyaz Listeleme](https://steemit.com/ethereum/@nexusdev/dapp-a-day-11-whitelist-boring)
        * [Yükseltilebilir ERC20-Token](https://steemit.com/ethereum/@nikolai/dapp-a-day-6-upgradeable-tokens)
        * [ERC20-Token-Vault](https://steemit.com/ethereum/@nexusdev/dapp-a-day-18-erc20-token-vault)
        * [Yetkilendirme (RBAC)](https://steemit.com/ethereum/@nikolai/dapp-a-day-4-access-control-via-auth)
        * [...ve daha fazlası...](https://github.com/dapphub/dappsys)
    * [MakerDAO](https://github.com/makerdao/maker-otc) veya [The TAO](https://github.com/ryepdx/the-tao) için yapı taşları sağlar
    * Kendi, test edilmemiş çözümler oluşturmadan önce danışılmalıdır
    * Kullanımı [Dapp-a-day 1-10](https://steemit.com/@nikolai) ve [Dapp-a-day 11-25](https://steemit.com/@nexusdev) şeklinde açıklanmıştır
* [OpenZeppelin Contracts: Solidity dilinde yeniden kullanılabilir ve güvenli akıllı sözleşme açık çerçevesi.](https://github.com/OpenZeppelin/openzeppelin-contracts)
    * Muhtemelen en yaygın kullanılan kütüphaneler ve akıllı sözleşmeler
    * Dappsys'e benzer şekilde, Truffle çerçevesine daha entegre
    * [Güvenlik Denetimleri ile İlgili Blog](https://blog.openzeppelin.com/)
* [Assembly ile Gelişmiş Atölye Çalışması](https://github.com/androlo/solidity-workshop)
* [Daha Basit Ethereum Multisig](https://medium.com/@ChrisLundkvist/exploring-simpler-ethereum-multisig-contracts-b71020c19037) - özellikle _Faydalar_ bölümü
* [CryptoFin Solidity Denetim Kontrol Listesi](https://github.com/cryptofinlabs/audit-checklist) - Ana ağ başlatması için akıllı sözleşmeyi denetlerken dikkat edilmesi gereken ortak bulgular ve sorunlar için bir kontrol listesi
* [aragonOS: DAO'lar, Dapp'ler ve protokoller oluşturmak için akıllı sözleşme çerçevesi](https://hack.aragon.org/docs/aragonos-intro.html)
    * Yükseltilebilirlik: Akıllı sözleşmeler yeni bir sürüme yükseltilebilir
    * İzin kontrolü: `auth` ve `authP` değiştiricilerini kullanarak, işlevsellik korunabilir, böylece sadece diğer uygulamalar veya varlıklar erişebilir
    * Yönlendiriciler: aragonOS uygulamaları, eylemi gerçekleştirmek için diğer uygulamalara niyetlerini gönderebilir, böylece niyet belirli gereksinimler karşılandığında yönlendirilir
* [EIP-2535 Diamond Standard](https://eips.ethereum.org/EIPS/eip-2535)
    * Sözleşmeleri aynı sözleşme depolama alanını ve Ethereum adresini paylaşacak şekilde düzenler.
    * 24KB maksimum sözleşme boyut sınırını çözer.
    * Bir işlemde tek bir işlev veya birden çok işlev ekleyerek/yenisiyle değiştirerek/yoksayarak diamondları yükseltin.
    * Yükseltmeler standart bir olayla kaydedilerek şeffaflık sağlanır.
    * Bir elmas hakkında bilgi almak için olaylar ve/veya dört standart işlev kullanılır.
* [Temiz Sözleşmeler - Temiz kod yazma kılavuzu](https://www.wslyvh.com/clean-contracts/)

##### Yükseltilebilirlik
* [Elena Dimitrova'nın Blogu, colony.io'dan Geliştirici](https://blog.colony.io/author/elena/)
    * https://blog.colony.io/writing-more-robust-smart-contracts-99ad0a11e948
    * https://blog.colony.io/writing-upgradeable-contracts-in-solidity-6743f0eecc88
* [Aragon araştırma blogu](https://blog.aragon.org/tag/research/)
    * [Kütüphane odaklı geliştirme](https://blog.aragon.org/library-driven-development-in-solidity-2bebcaf88736)
    * [Gelişmiş Solidity kodu dağıtım teknikleri](https://blog.aragon.org/advanced-solidity-code-deployment-techniques-dc032665f434/)
* [OpenZeppelin Proxy Kütüphaneleri Hakkında](https://blog.openzeppelin.com/proxy-libraries-in-solidity-79fbe4b970fd/)

### Altyapı
#### Ethereum İstemcileri
* [Besu](https://besu.hyperledger.org/en/latest/) - Apache 2.0 lisansı altında geliştirilen ve Java dilinde yazılmış açık kaynaklı bir Ethereum istemcisi. Proje Hyperledger tarafından barındırılır.
* [Geth](https://geth.ethereum.org/docs/) - Go istemcisi
* [OpenEthereum](https://github.com/openethereum/openethereum) - Rust istemcisi, eski adıyla Parity
* [Aleth](https://github.com/ethereum/aleth) - C++ istemcisi
* [Nethermind](https://github.com/NethermindEth/nethermind) - .NET Core istemcisi
* [Infura](https://infura.io/) - Ethereum istemci uyumlu API'lar sağlayan yönetilen bir hizmet
* [Trinity](https://trinity.ethereum.org/) - Python istemcisi, [py-evm](https://github.com/ethereum/py-evm) kullanır
* [Ethereumjs](https://github.com/ethereumjs/ethereumjs-client) - [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm) kullanarak JS istemcisi
* [Seth](https://github.com/dapphub/dapptools/tree/master/src/seth) - Seth, komut satırı için bir "MetaMask gibi" Ethereum istemcisi aracıdır
* [Mustekala](https://github.com/musteka-la/mustekala) - Metamask'ın Ethereum Hafif İstemci projesi
* [Exthereum](https://github.com/exthereum/blockchain) - Elixir istemcisi
* [EWF Parity](https://github.com/energywebfoundation/energyweb-ui) - Tobalaba test ağı için Energy Web Foundation istemcisi
* [Quorum](https://github.com/jpmorganchase/quorum) - JP Morgan tarafından desteklenen, veri gizliliğini destekleyen izinli bir Ethereum uygulaması
* [Mana](https://github.com/mana-ethereum/mana) - Elixir dilinde yazılmış Ethereum tam düğüm uygulaması.
* [Chainstack](https://chainstack.com/) - Esnek ve özel Geth düğümleri sağlayan yönetilen bir hizmet
* [QuickNode](https://quicknode.com/) - API erişimi ve düğüm olarak hizmet veren Blockchain geliştirici bulutu.
* [GetBlock](https://getblock.io/) - ETH dahil olmak üzere 50'den fazla ağı destekleyen Blockchain-as-a-Service sağlayıcısı (RPC Node sağlayıcı)
* [Watchdata](https://watchdata.io) - Ethereum blockchain'e basit ve güvenilir API erişimi sağlar
* [NOWNodes](https://nownodes.io) - ETH düğümüne (ve 48'den fazla başka düğüme) erişim sağlar ve Block Explorer. Blok zinciri hizmeti çözümünü test etmek için ücretsiz API anahtarınızı alın
* [Spice](https://spice.xyz) - SQL, API ve Node-as-a-Service ile veri ve AI yönetilen hizmet.
* [InfStones](https://infstones.com/) - 60'tan fazla blok zinciri protokolünü destekleyen blockchain düğüm hizmeti sağlayıcısı.
* [Chainnodes](https://www.chainnodes.org/) - Tüm önemli EVM zincirleri için kurumsal sınıf düşük gecikmeli web3 altyapı sağlayıcısı.
#### Depolama
* [IPFS](https://ipfs.io/) - Merkezsiz depolama ve dosya referansı
   * [Mahuta](https://github.com/ConsenSys/Mahuta) - Eklenmiş arama yeteneği ile IPFS depolama servisi, eskiden IPFS-Store
   * [OrbitDB](https://github.com/orbitdb/orbit-db) - IPFS üzerinde dağıtılmış veritabanı
   * [JS IPFS API](https://github.com/ipfs/js-ipfs-http-client) - JavaScript'de uygulanan IPFS HTTP API için istemci kitaplığı
   * [Moralis IPFS API](https://docs.moralis.io/web3-data-api/reference/upload-folder) - IPFS'e kolayca çoklu dosya yükleme, herhangi bir dilde
   * [TEMPORAL](https://github.com/RTradeLtd/Temporal) - IPFS ve diğer dağıtılmış/merkezi olmayan depolama protokolleri için kolay kullanımlı API
   * [PINATA](https://pinata.cloud) - IPFS kullanmanın en kolay yolu
* [Swarm](https://swarm-gateways.net/) - Dağıtılmış depolama platformu ve içerik dağıtım servisi, Ethereum web3 yığınının doğal bir taban hizmeti
* [Arweave](https://www.arweave.org/) - Merkezi olmayan ve kalıcı depolama
  * [Bundlr](https://bundlr.network/) - Birden fazla token desteği ile Arweave ölçekleme çözümü
* [Infura](https://infura.io/) - Yönetilen IPFS API Ağ Geçidi ve sabitleme servisi
* [Aleph.im](https://aleph.im/) - Ethereum ve IPFS ile uyumlu (veritabanı, dosya depolama, hesaplama ve DID) teşvikli offchain peer-to-peer bulut projesi.
* [DB3 Network](https://github.com/dbpunk-labs/db3) - Merkezi Firebase Firestore Alternatif.

#### Mesajlaşma
* [Whisper](https://github.com/ethereum/wiki/wiki/Whisper) - DApp'lerin birbirleriyle iletişim kurması için iletişim protokolü, Ethereum web3 yığınının doğal bir taban hizmeti
* [DEVp2p Tel Protokolü](https://github.com/ethereum/devp2p/blob/master/rlpx.md) - Ethereum/Whisper düğümleri arasında peer-to-peer iletişim sağlar
* [Pydevp2p](https://github.com/ethereum/pydevp2p) - RLPx ağ katmanının Python uygulaması
* [EPNS SNS Bildirimleri](https://docs.epns.io/developers/developer-zone/receiving-notifications/sns-notifications) - Push Teslimat Noktaları için SNS modülü, herhangi bir geliştiricinin platformlarına doğrudan webhooks ile bildirim, sohbet veya diğer web3 iletişim türlerini almasına izin verir.

### Dağıtım
* [Meroku](https://github.com/merokudao/meroku) - Topluluk tarafından sahip olunan bir dApp Mağazası. DApp'lerinizi paketleyin, dağıtın ve barındırma maliyeti olmadan dağıtın.

### Test Araçları
* [Truffle Teams](https://trufflesuite.com/teams) - Truffle projeleri için Sıfır Yapılandırma sürekli entegrasyon
* [Solidity kod kapsamı](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage) - Solidity kod kapsamı aracı
* [Solidity kapsamı](https://github.com/sc-forks/solidity-coverage) - Solidity akıllı sözleşmeleri için alternatif kod kapsamı
* [Solidity fonksiyon profilleyici](https://github.com/EricR/sol-function-profiler) - Solidity akıllı sözleşme fonksiyon profili
* [Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) - Alternatif ve güncellenmiş Solidity akıllı sözleşme profili

### Güvenlik Araçları
* [MythX](https://mythx.io/) - Ethereum geliştiricileri için güvenlik doğrulama platformu ve araç ekosistemi
* [Mythril](https://github.com/ConsenSys/mythril) - Açık kaynaklı EVM bytecode güvenlik analiz aracı
* [Oyente](https://github.com/melonproject/oyente) - Alternatif statik akıllı sözleşme güvenlik analiz aracı
* [Securify](https://securify.chainsecurity.com/) - Ethereum akıllı sözleşmeleri için güvenlik tarayıcısı
* [SmartCheck](https://tool.smartdec.net/) - Statik akıllı sözleşme güvenlik analiz aracı
* [Ethersplay](https://github.com/crytic/ethersplay) - EVM disassembler
* [Evmdis](https://github.com/Arachnid/evmdis) - Alternatif EVM disassembler
* [Hydra](https://github.com/IC3Hydra/Hydra) - Kripto-ekonomik sözleşme güvenliği için çerçeve, merkezi olmayan güvenlik ödülleri
* [Solgraph](https://github.com/raineorshine/solgraph) - Akıllı sözleşme güvenlik analizi için Solidity kontrol akışını görselleştirme
* [Manticore](https://github.com/trailofbits/manticore) - Sembolik yürütme aracı, akıllı sözleşmeler ve ikili dosyalar üzerinde
* [Slither](https://github.com/crytic/slither) - Solidity statik analiz çerçevesi
* [Slitherin](https://github.com/pessimistic-io/slitherin) - Ek güvenlik tespitleri ile Slither eklentisi
* [Adelaide](https://github.com/sec-bit/adelaide) - SECBIT Statik analiz uzantısı Solidity derleyicisi için
* [solc-verify](https://github.com/SRI-CSL/solidity/) - Solidity akıllı sözleşmeleri için modüler doğrulayıcı
* [Solidity güvenlik blogu](https://github.com/sigp/solidity-security-blog) - Bilinen saldırı vektörlerinin kapsamlı listesi ve yaygın anti-örnekler
* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) - ETK standardına uygun tokenlerdeki Zayıflıkların Bir Koleksiyonu
* [Ücretsiz Akıllı Sözleşme Güvenlik Denetimi](https://callisto.network/smart-contract-audit/) - Callisto Network'ten ücretsiz akıllı sözleşme güvenlik denetimleri
* [Piet](https://piet.slock.it) - Görsel Solidity mimari analiz aracı
* [Smack My Contract](https://smackmycontract.xyz/) - Web3 Güvenlik Tarama Derleyicisi
* [EVMole](https://github.com/cdump/evmole) - EVM bytecode'dan işlev seçicileri çıkarır, hatta doğrulanmamış sözleşmeler için
* [ERCx](https://ercx.runtimeverification.com) - Web sitesi, API ve VSCode uzantısı, ERC uyumluluğu ve güvenlik özellikleri için token testi

### İzleme
* [Moralis Streams API](https://docs.moralis.io/streams-api) - Çoklu EVM blok zincirlerinden gerçek zamanlı olayları web kancalarınıza akıtarak
* [Alethio](https://aleth.io/) - Gelişmiş Ethereum analitik platformu, canlı izleme, görünüm ve anormallik tespiti sağlar, token metrikleri, akıllı sözleşme denetimleri, grafik görselleştirme ve blok zinciri araması
* [amberdata.io](https://amberdata.io) - Canlı izleme, anormallik tespiti, token metrikleri, akıllı sözleşme denetimleri, grafik görselleştirme ve blok zinciri araması sağlar.
* [Neufund - Akıllı Sözleşme İzleme](https://github.com/Neufund/smart-contract-watch) - Bir dizi akıllı sözleşmeyi ve işlemleri izlemek için bir araç
* [Scout](https://scout.cool/) - Ethereum'daki akıllı sözleşmelerinizin etkinlikleri ve olay günlüklerinin canlı veri beslemesi
* [Tenderly](https://tenderly.co/) - Kullanıcılara web tabanlı bir panoda güvenilir akıllı sözleşme izleme ve uyarılar sağlayan bir platform, altyapı barındırma veya bakımı gerektirmez
* [Chainlyt](https://www.chainlyt.io/main/dashboard/contract) - Dekode edilmiş işlem verileriyle akıllı sözleşmeleri keşfedin, sözleşmenin nasıl kullanıldığını görün ve belirli işlev çağrıları ile işlemleri arayın
* [BlockScout](https://github.com/poanetwork/blockscout) - EVM tabanlı blok zincirlerini inceleme ve analiz etme aracı. Ethereum ağları için tek tam özellikli blok zinciri keşfetme aracı.
* [Terminal](https://terminal.co/) - Dapp'lerinizi izlemek için bir kontrol paneli. Terminal, kullanıcılarınızı, dapp'lerinizi, blok zinciri altyapınızı, işlemleri ve daha fazlasını izlemenize olanak tanır.
* [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) - On-chain olayları dinlemek ve buna yanıt olarak bir şey yapmak için genişletilebilir bir Golang çerçevesi
* [Alchemy Notify](https://docs.alchemyapi.io/guides/alchemy-notify) - İstenen adresler için işlenen ve düşen işlemler, gaz fiyatı değişiklikleri ve adres etkinliği için bildirimler
* [Blocknatve Mempool Explorer](https://www.blocknative.com/explorer) — Her yaşam döngüsü aşaması için akıllı sözleşmeye veya cüzdan adresine yönelik canlı akışı izleyin — dahil olmak üzere düşme, onaylama, hızlandırma, iptal ve daha fazlası. Onaylanmış iç işlemleri otomatik olarak çözümleyin. Ve istediğiniz gibi filtreleyin. Görsel, kod yok, arayüzümüzde olayları alın veya bunları bir web kancası aracılığıyla API anahtarınıza bağlayarak alın. Mempool Explorer borsalar, protokoller, cüzdanlar ve tüccarlar işlemleri gerçek zamanlı olarak izlemelerini ve harekete geçmelerini sağlar.
* [Ethernal](https://www.tryethernal.com) - Özel zincir için Ethereum blok gezgini. İşlemleri göz atın, işlev çağrılarını, olay verilerini veya sözleşme değişken değerlerini yerel olarak çalışan zincirinizde inceleyin.
* [Forta](https://forta.org/) - DeFi, NFT, yönetişim, köprüler ve diğer Web3 sistemlerinde tehditleri ve anormallikleri gerçek zamanlı olarak tespit eden merkezi olmayan izleme ağı.
* [InfStones BlockWatch](https://infstones.com/block_watch) - Kaynak kullanımı için düğüm durumu izlemek için alarmlar kurun. SMS, Slack, telefon çağrıları ve e-posta ile bildirimleri dahil edin.
* [Blocktorch](https://blocktorch.xyz) - Dağıtık yığının izlenebilirlik platformu. Tüm akıllı sözleşmelerinizin büyük resmini bir bakışta görün. Zincirler ve sözleşmeler arasında hızlıca günlüklere göz atın. Anormallikler hakkında bilgi almak ve bildirim almak için Hizmet Seviyesi Hedeflerini ayarlayın.
* [Ethereum-datafarm](https://github.com/Nerolation/ethereum-datafarm) - Arşiv düğümü gerektirmeyen tarihsel olay verilerini ayrıştırma için kullanılan kolay kullanımlı konsol uygulaması. Ethereum-datafarm, belirtilen sözleşmelerden olay verilerini Etherscan API'si kullanarak ayrıştırır ve CSV formatında depolar.
* [Sidekik](https://sidekik.xyz) - Görsel bir kullanıcı arabirimi ile akıllı sözleşmeleri hata ayıklamak, test etmek ve anlamak. Yerel veya dağıtılmış EVM tabanlı akıllı sözleşmelerle etkileşime geçin. Yerel zincir işlemlerini izleyin, işlev çağrılarını çözümleyin ve giriş yüklerini hazırlayın.
* [GuardianUI](https://guardianui.com) - Web3 ön uç işlevselliği, performansı ve güvenliği test etmek ve izlemek için kullanıcılarına daha güvenli ve sağlam bir deneyim sunun.
* [Pessimistic Spotter](https://spotter.pessimistic.io/) - Sözleşmelerinizi hack'lemeye karşı korur. Spotter, blok zinciri etkinliğini izler ve hack girişimlerini önceden tespit eder. Eğer hack hedeflerinizden biriysa, Spotter bir uyarı gönderir ve savunma önlemleri alır.
* [Tatum Bildirimleri](https://docs.tatum.io/docs/notifications) - Tüm geliştiriciler için tasarlanmış hızlı Web3 bildirimleri ile bir adım önde kalın.

### Diğer Çeşitli Araçlar
* [aragonPM](https://hack.aragon.org/docs/apm-intro.html) - aragonOS ve Ethereum tarafından desteklenen merkezi olmayan paket yöneticisi. aragonPM, paket güncellemeleri üzerinde merkezi olmayan yönetişimi sağlayarak merkezi hata noktalarını ortadan kaldırır.
* [Truffle boxes](https://www.trufflesuite.com/boxes) - DApp'ler için hızlı bir şekilde paketlenmiş bileşenler.
   * [Cheshire](https://github.com/endless-nameless-inc/cheshire) - CryptoKitties API ve akıllı sözleşmelerinin yerel bir kum havuzu uygulaması olarak Truffle Box olarak mevcut
* [Solc](https://docs.soliditylang.org/en/latest/using-the-compiler.html) - Solidity derleyicisi
* [Sol-compiler](https://sol-compiler.com/) - Proje düzeyinde Solidity derleyicisi
* [Solidity cli](https://github.com/pubkey/solidity-cli) - Solidity kodunu daha hızlı, daha kolay ve daha güvenilir derleme
* [Solidity flattener](https://github.com/poanetwork/solidity-flattener) - İçe aktarılan sözleşmeleri tek bir dosyada birleştirme aracı. İçe aktarılan sözleşmeleri görselleştirmek veya Etherscan'da sözleşmenizi doğrulamak için kullanışlıdır.
* [Sol-merger](https://github.com/RyuuGan/sol-merger) - Alternatif olarak, tüm içe aktarmaları tek bir dosyaya birleştirir
* [RLP](https://github.com/ethereumjs/rlp) - JavaScript'te Recursive Length Prefix Encoding
* [eth-cli](https://github.com/protofire/eth-cli) - Ethereum öğrenme ve geliştirme için CLI araçlarının koleksiyonu
* [Ethereal](https://github.com/wealdtech/ethereal) - Ethereum'da yaygın görevleri yönetmek için komut satırı aracı
* [Eth crypto](https://github.com/pubkey/eth-crypto) - Ethereum için kriptografik JavaScript fonksiyonları ve bunları web3js ve solidity ile kullanma öğreticileri
* [Parity Signer](https://github.com/paritytech/parity-signer) - işlemleri imzalamak için mobil uygulama
* [py-eth](http://py-eth.com) - Ethereum ekosistemi için Python araçlarının koleksiyonu
* [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) - Truffle altında geliştirilen solidity dosyalarını bağımlılıklarıyla birlikte birleştirir
* [Decode](https://github.com/hacker-DOM/decode) - yerel bir testrpc düğümüne gönderilen işlemleri daha okunabilir ve anlaşılabilir hale getiren npm paketi
* [TypeChain](https://github.com/ethereum-ts/TypeChain) - Ethereum akıllı sözleşmeleri için TypeScript bağlayıcıları
* [EthSum](https://ethsum.netlify.com) - Basit Ethereum Adres Kontrol Toplama Aracı
* [PHP tabanlı Blockchain indeksleyici](https://github.com/digitaldonkey/ethereum-php-eventlistener) - PHP'de blokları indeksleme veya Olayları dinleme imkanı sağlar
* [Purser](https://github.com/JoinColony/purser) - Ethereum tabanlı cüzdanlar için JavaScript evrensel cüzdan aracı. Yazılım, donanım ve Metamask'ı destekler - dApp geliştirme için tüm cüzdanları tutarlı ve öngörülebilir bir arayüzde birleştirir.
* [Node-Metamask](https://github.com/JoinColony/node-metamask) - MetaMask'ı node.js'den bağlamak
* [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) - Solidity projeleri için belgelendirme oluşturucusu
* [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) - Ethereum blok zinciri verilerini CSV veya JSON dosyalarına aktarma
* [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) - Solidity kodunu biçimlendirmek için Prettier eklentisi
* [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) - Ethereum ve Unity entegrasyon demo
* [Flappy](https://github.com/Nethereum/Nethereum.Flappy) - Ethereum ve Unity entegrasyon demo / örnek
* [Wonka](https://github.com/Nethereum/Wonka) - Nethereum iş kuralları motoru demo / örnek
* [Sol2UML](https://github.com/naddison36/sol2uml) - Solidity sözleşmeleri için Unified Modeling Language (UML) sınıf diyagramı oluşturucusu
* [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) - Çerçevelerde Solidity içe aktarma ve sanatıf çözümleme için bir dizi araç
* [eth-reveal](https://github.com/justinjmoses/eth-reveal) - ABIden alınan ABIs kullanılarak işlemi incelemek için bir node ve tarayıcı aracı - yöntemi, olay günlüklerini ve Etherscan'da bulunan herhangi bir dönüş nedenini mümkünse kodlamak.
* [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) - Golang'da yazılmış güvenilir bir işlem göndermek için kütüphane - gaz optimizasyonu, nonce hesaplama, senkronizasyon ve yeniden deneme gibi bazı zorlu düşük seviye detayları soyutlar.
* [truffle-plugin-verify](https://github.com/rkalis/truffle-plugin-verify) - Truffle komut satırından Etherscan üzerinde sözleşme kaynak kodunu sorunsuz olarak doğrulamak
* [Blocknative Gas Platform](https://www.blocknative.com/gas) — Geliştiriciler için gaz tahmini, geliştiriciler tarafından gaz platformları. Gas Platform, Blocknative'ın gerçek zamanlı mempool veri altyapısını kullanarak Ethereum işlem ücretlerini doğru ve tutarlı bir şekilde tahmin etmeye yardımcı olur. Bu, yapımcılara ve tüccarlara anlık gaz ücreti API'si sunar.
* [ETH Gas.watch](https://ethgas.watch/) - Gaz fiyatlarını izleyen ve fiyat değişikliklerinde e-posta bildirimleri sağlayan bir gaz fiyatı izleyicisi
* [Diverse Eth Calculator](https://ethcalculator.dsolutions.mn/) - Birim hesaplamalarını kolaylaştırma ve yardımcı araçlar. PWA, bu yüzden mac/windows/linux veya android/iphone'a yükleyebilirsiniz
* [Cookbook](https://cookbook.dev) - Tüm akıllı sözleşme kütüphanelerini bir araya getiren bir platform
* [Ethereum Birim Dönüştürücüsü](https://neptunemutual.com/web3-tools/ethereum-unit-converter/) - Farklı Ethereum birimlerini dönüştürmek için çevrimiçi araç.
* [Solidity Bytes32 Converter](https://neptunemutual.com/web3-tools/string-to-bytes32-converter/) - Solidity Bytes32'yi dize, sayılar ve tersine dönüştürmek için çevrimiçi araç.

### Akıllı Sözleşme Standartları ve Kütüphaneler
#### [ERCs](https://eips.ethereum.org/erc) - Ethereum Request for Comment deposu
* Tokenlar
  * [ERC-20](https://eips.ethereum.org/EIPS/eip-20) - Değişebilir varlıklar için orijinal token sözleşmesi
  * [ERC-721](https://eips.ethereum.org/EIPS/eip-721) - Değişmez varlıklar için token standardı
  * [ERC-777](https://eips.ethereum.org/EIPS/eip-777) - Değişebilir varlıklar için geliştirilmiş bir token standardı
  * [ERC-918](https://eips.ethereum.org/EIPS/eip-918) - Kazılabilir Token Standardı
* [ERC-165](https://eips.ethereum.org/EIPS/eip-165) - Bir akıllı sözleşmenin hangi arayüzleri uyguladığını yayınlamak ve algılamak için standart bir yöntem oluşturur.
* [ERC-725](https://eips.ethereum.org/EIPS/eip-725) - Anahtar yönetimi ve yürütme için proxy sözleşmesi, bir Blockchain kimliği kurmak için
* [ERC-173](https://eips.ethereum.org/EIPS/eip-173) - Sözleşme sahipliği için standart bir arayüz

#### Popüler Akıllı Sözleşme Kütüphaneleri
* [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) - SafeMath ve OpenZeppelin SDK gibi test edilmiş tekrar kullanılabilir akıllı sözleşmeler içerir [kütüphane](https://github.com/OpenZeppelin/openzeppelin-sdk) akıllı sözleşme yükseltilebilirliği için
* [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) - Güvenli ve gaz verimli akıllı sözleşmeler oluşturmak için Solidity kütüphanelerinin bir koleksiyonu
* [Modüler Kütüphaneler](https://github.com/Modular-Network/ethereum-libraries) - Ethereum Sanal Makinesi kullanan blockchain'ler için inşa edilmiş bir grup paket
* [DateTime Kütüphanesi](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) - Gaz verimli bir Solidity tarih ve saat kütüphanesi
* [Aragon](https://github.com/aragon/aragon) - DAO protokolü. Güncelleme ve yönetişime odaklanan [aragonOS akıllı sözleşme çerçevesi](https://github.com/aragon/aragonOS)
* [ARC](https://github.com/daostack/arc) - DAO'lar için işletim sistemi ve DAO yığınının taban katmanı
* [0x](https://github.com/0xProject) - DEX protokolü
* [Proofs ile Token Kütüphaneleri](https://github.com/sec-bit/tokenlibs-with-proofs) - Verilen özellikler ve yüksek düzeyli özelliklerle token sözleşmelerinin doğruluğunu kanıtlama
* [Provable API](https://github.com/provable-things/ethereum-api) - Provable hizmetini kullanmak için sözleşmeler sağlar, dış zincir eylemleri, veri alma ve hesaplama yapma imkanı sağlar
* [Solidity için ABDK Kütüphaneleri](https://github.com/abdk-consulting/abdk-libraries-solidity) - Solidity için Sabit Nokta (64.64 bit) ve IEEE-754 uyumlu dört kat hassasiyetli (128 bit) kayan nokta matematik kütüphaneleri
* [Cookbook](https://cookbook.dev) - Tüm akıllı sözleşme kütüphanelerini bir araya getiren bir platform


### 2. Kat Altyapıları için Geliştirici Kılavuzları

#### Ölçeklenebilirlik



#### Ödeme/Durum Kanalları
* [Ethereum Ödeme Kanalı](https://medium.com/@matthewdif/ethereum-payment-channel-in-50-lines-of-code-a94fad2704bc) - 50 satır kodda Ethereum Ödeme Kanalı
* [µRaiden Belgeleri](https://microraiden.readthedocs.io) - µRaiden Gönderici/Alıcı Kullanım Senaryoları için Kılavuzlar ve Örnekler

#### Plasma
* [Plasma Öğren](https://github.com/ethsociety/learn-plasma) - Cornell Üniversitesi'nde 2018 IC3-Ethereum Crypto Boot Camp'te başlatılan ve tüm Plasma çeşitlerini (MVP/Cash/Debit) kapsayan Node uygulaması olarak web sitesi
* [Plasma MVP](https://github.com/omisego/plasma-contracts) - Minimum Viable Plasma'nın OmiseGO'nun araştırma uygulaması
* [Plasma MVP Golang](https://github.com/kyokan/plasma) - Minimum Viable Plasma özelliklerinin Golang uygulaması ve uzantısı
* [Plasma Guard](https://github.com/mesg-foundation/plasma-guard) - Omisego Plasma Ağı'nda otomatik olarak izle ve meydan okuma veya çıkış yapma

#### Yan Zincirler
* [POA Network](https://www.poa.network/)
  * [POA Bridge](https://bridge.poa.net/)
  * [POA Bridge UI](https://github.com/poanetwork/bridge-ui)
  * [POA Bridge Sözleşmeleri](https://github.com/poanetwork/poa-bridge-contracts)
 * [Loom Network](https://github.com/loomnetwork)
* [Matic Network](https://docs.matic.network/)

#### Gizlilik / Gizlilik
##### ZK-SNARKs
* [ZoKrates](https://github.com/Zokrates/ZoKrates) - Ethereum'da zkSNARKS için bir araç kutusu
* [AZTEC Protokolü](https://github.com/AztecProtocol/AZTEC) - Ethereum ağındaki gizli işlemler, uygulama Ethereum ana ağında canlı
* [Nightfall](https://github.com/EYBlockchain/nightfall) - Herhangi bir ERC-20 / ERC-721 tokenini özel yapar - açık kaynaklı araçlar ve mikro hizmetler
* Proxy Yeniden Şifreleme (PRE)
* [NuCypher Ağı](https://github.com/nucypher/nucypher) - Merkezi olmayan sistemlerde veri gizliliğini güçlendirmek için bir proxy yeniden şifreleme ağı
* [pyUmbral](https://github.com/nucypher/pyumbral) - Eşik proxy yeniden şifreleme kriptografik kütüphane
* Tam Homomorfik Şifreleme (FHE)
* [NuFHE](https://github.com/nucypher/nufhe) - GPU hızlandırmalı FHE kütüphanesi

#### Ölçeklenebilirlik + Gizlilik

#### ZK-STARKs
* [StarkWare](https://github.com/starkware-industries) ve [StarkWare Kaynakları](https://github.com/starkware-libs) - StateEx ölçeklenebilirlik motoru durum geçişlerini zincire depolayan StarkEx

#### Önceden Hazırlanmış UI Bileşenleri
* [aragonUI](https://ui.aragon.org) - Dapp bileşenlerini içeren bir React kütüphanesi
* [components.bounties.network](https://components.bounties.network) - Dapp bileşenlerini içeren bir React kütüphanesi
* [ui.decentraland.org](https://github.com/decentraland/ui) - Dapp bileşenlerini içeren bir React kütüphanesi
* [dapparatus](https://github.com/austintgriffith/dapparatus) - Yeniden kullanılabilir React Dapp bileşenleri
* [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) - Metamask React bileşenleri
* [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) - Web tabanlı merkezi olmayan uygulamalar için çapraz platformlu hibrit barındırma mekanizması
* [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) - Çapraz platformlu masaüstü cüzdan örneği
* [eth-button](https://eth-button.github.io/eth-button/) - Minimalist bağış düğmesi
* [Rimble Tasarım Sistemi](https://rimble.consensys.design/) - Merkezi olmayan uygulamalar için uyarlanabilir bileşenler ve tasarım standartları
