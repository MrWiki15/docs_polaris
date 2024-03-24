# 🛕 Estructura

```bash
└── src
    ├── components
    │   ├── Comuns
    │   │   ├── Alerts.jsx
    │   │   ├── AnimatedIconCrypto.jsx
    │   │   ├── Booton.jsx
    │   │   ├── BottonNavigation.jsx
    │   │   ├── Comming.jsx
    │   │   ├── Error.jsx
    │   │   ├── FlotingBotton.jsx
    │   │   ├── Header.jsx
    │   │   ├── IconNotificationTesting.jsx
    │   │   ├── IconText.jsx
    │   │   ├── ImageSlider.jsx
    │   │   ├── Liked.jsx
    │   │   ├── Loading.jsx
    │   │   ├── Products.jsx
    │   │   ├── Test
    │   │   │   ├── Chat.test.jsx
    │   │   │   ├── ExampleBrach.test.jsx
    │   │   │   ├── ExampleSocial.test.jsx
    │   │   │   ├── ExamplesStatics.test.jsx
    │   │   │   ├── FetchAcciones.test.jsx
    │   │   │   ├── FetchIndicadores.test.jsx
    │   │   │   ├── FetchIndices.test.jsx
    │   │   │   ├── FetchMarketsDataForex.test.jsx
    │   │   │   ├── FetchParsForex.test.jsx
    │   │   │   ├── FetchTokensHedera.test.jsx
    │   │   │   ├── MemberTeam.test.jsx
    │   │   │   ├── NavigationForexTop.test.jsx
    │   │   │   ├── NavigationToolsTop.test.jsx
    │   │   │   ├── NewsTeam.test.jsx
    │   │   │   ├── NFTColections.test.jsx
    │   │   │   ├── Rastreador.test.jsx
    │   │   │   ├── Seeker.test.jsx
    │   │   │   ├── SocialCollection.test.jsx
    │   │   │   ├── ToolsComponent.test.jsx
    │   │   │   ├── TopTokensBinanceScreen.test.jsx
    │   │   │   ├── TopTokensHederaScreen.test.jsx
    │   │   │   ├── TopTokensPolygonScreen.test.jsx
    │   │   │   ├── TopTokensSolanaScreen.test.jsx
    │   │   │   └── UsersStats.test.jsx
    │   │   └── Text.jsx
    │   ├── FetchData
    │   │   ├── FetchCoin.jsx
    │   │   ├── FetchCoins.jsx
    │   │   ├── FetchFolowersHive.jsx
    │   │   ├── FetchLosersCoins.jsx
    │   │   ├── FetchTrendingNFTs.jsx
    │   │   ├── FetchWinnersCoins.jsx
    │   │   ├── HivePostDetails.jsx
    │   │   ├── HivePosts.jsx
    │   │   ├── PostHiveGlobalStat.jsx
    │   │   ├── TrendingCoin.jsx
    │   │   └── TrendingsCoins.jsx
    │   ├── Hive
    │   │   ├── Functions
    │   │   │   ├── getCommets.jsx
    │   │   │   ├── getInfoModal.jsx
    │   │   │   └── getPosts.jsx
    │   │   ├── GeneralStatsForUser.jsx
    │   │   ├── GetBasicInfoForUser.jsx
    │   │   └── ModalStats.jsx
    │   ├── News
    │   │   ├── ButtonNews.jsx
    │   │   └── FetchNews.jsx
    │   ├── NFTs
    │   │   └── FetchMarketNfts.jsx
    │   ├── Partner
    │   │   ├── Data.jsx
    │   │   └── FetchPartners.jsx
    │   └── Portafolio
    │       ├── ConectButton.jsx
    │       ├── getBalance.jsx
    │       └── Wallet
    │           ├── Profile
    │           │   ├── ProfileImage.jsx
    │           │   └── TransactionHistory.jsx
    │           └── WalletData.jsx
    ├── Layout
    │   ├── Crypto
    │   │   ├── AnimatedIconCrypto.jsx
    │   │   ├── FetchMarketCoins.jsx
    │   │   ├── FetchTokensBitcoin.jsx
    │   │   └── FetchTokensEthereum.jsx
    │   ├── GuiasTutorialesLayaout.jsx
    │   ├── HomeLayout.jsx
    │   └── TextLayout.jsx
    ├── navigation
    │   ├── AppNavigator.js
    │   ├── NavigationDrawer.jsx
    │   ├── NavigationStack
    │   │   └── NavigationStackHive.jsx
    │   ├── NavigationStack.jsx
    │   ├── NavigationStackWelcome.jsx
    │   ├── NavigationTab.jsx
    │   └── NavigationTopBooton
    │       ├── MenuDrawer
    │       │   ├── BottonMenuDrawer.jsx
    │       │   ├── ImportantUrl.js
    │       │   └── MenuDrawerNavigation.jsx
    │       ├── NavigationMarketTop
    │       │   ├── NavigationCryptoTop.jsx
    │       │   └── NavigationNFTsTop.jsx
    │       └── NavigationTopGainersLosers.jsx
    ├── screens
    │   ├── DrawerNavigator
    │   │   ├── QusoftShopScreen.jsx
    │   │   └── SponsorsScreen.jsx
    │   ├── Error
    │   │   └── ErrorScreen.jsx
    │   ├── StackNavigator
    │   │   ├── Comunidad.jsx
    │   │   ├── Cursos.jsx
    │   │   ├── Hive
    │   │   │   └── HiveScreen.jsx
    │   │   ├── HomeScreen.jsx
    │   │   ├── Materiales.jsx
    │   │   ├── Mercado.jsx
    │   │   ├── Productos.jsx
    │   │   ├── Recompensas.jsx
    │   │   ├── Servicios.jsx
    │   │   ├── Trabajos.jsx
    │   │   └── Welcome
    │   │       ├── Welcome1.jsx
    │   │       ├── Welcome2.jsx
    │   │       └── Welcome3.jsx
    │   ├── TabNavigator
    │   │   ├── MarketScreen.jsx
    │   │   ├── NFTScreen.jsx
    │   │   └── Portafolio
    │   │       ├── Wallet.jsx
    │   │       └── Welcome.jsx
    │   └── TopNavigator
    │       ├── TopTabGainersLosers
    │       │   ├── GainersScreen.jsx
    │       │   └── LosersScreen.jsx
    │       └── TopTabMarket
    │           ├── CryptoScreen.jsx
    │           ├── CryptoScreens
    │           │   ├── TopMarketCryptoScreen.jsx
    │           │   ├── TopTokensBitcoinScreen.jsx
    │           │   └── TopTokensEthereumScreen.jsx
    │           ├── NFTCryptoScreen.jsx
    │           └── NFTsScreens
    │               ├── Kabila.jsx
    │               ├── MagicHeden.jsx
    │               └── OpenSea.jsx
    ├── style
    │   ├── ButtonStyle.js
    │   ├── CardsMarketCoinsStyle.js
    │   ├── ComponentsStyles
    │   │   ├── AlertPortafolioStyle.jsx
    │   │   ├── CommingStyle.jsx
    │   │   ├── FetchLosersStyles.jsx
    │   │   ├── FetchMarketsNFtsStyles.jsx
    │   │   ├── FetchNewsStyles.jsx
    │   │   ├── FetchPartnersStyle.jsx
    │   │   ├── FetchWinnersCoinsStyle.jsx
    │   │   ├── HeaderStyles.jsx
    │   │   ├── Portafolio
    │   │   │   └── WalletdataStyles.jsx
    │   │   ├── ProductosStyle.jsx
    │   │   └── TrendingCoinStyle.jsx
    │   ├── Global.js
    │   └── LayoutStyles
    │       └── HomeStyles.jsx
    └── utils
        ├── FormatDateHive.jsx
        ├── FormatDates.jsx
        ├── FormatMarketCap.jsx
        ├── FormatNumer.jsx
        ├── FormatStr.jsx
        ├── FormatStrMit.jsx
        ├── FormatStrPerPoint.jsx
        └── Infura.jsx
        
        
15501 directories, 83023 files
```
