# FutureBeatz
## NFT Sample Pack for music production
## Hackathon project for the Encode Club / Lightlink(Liteflow) Hackathon<br> 
(this project uses the [Liteflow](https://liteflow.com) "Marketplace" template... more details below.)<br>
Link to project deployed on the Lightlink Pegasus Testnet<br><br>
https://future-beatz.vercel.app/<br>

<img src="/LandingScreenShot-FutureBeatz.png" width="70%" height="70%">
<br>
The idea behind this project is that a music producer could make a <a href="https://www.lucidsamples.com/blog/what-is-sample-pack">samplepack</a> and sell it as an NFT. A buyer could purchase the NFT and use it in their own production. The original creator would get royalties if the buyer chose to resell the NFT.<br>
<a href="https://www.loom.com/share/430f427a41bf4555be08c9de84e762ef?sid=6be54c82-4349-46d5-9af8-8b15e62650a6">Video</a>
<br>
<br>
**Things to note:** <br><br>
* For the project the nft is actually a mp4 file (you can listen to the sample). In a real world example you would need a link for a buyer to download a high resolution audio file as Liteflow does not currently support the <a href="https://www.howtogeek.com/392504/what-are-wav-and-wave-files-and-how-do-i-open-them/">wav</a> file format. You would need some type of NFT gated decentralized storage, which would hold the lossless high resolution audio file.
* In a real world example, the original creator could also require to be paid a percentage of the sales (or streams) of a song that uses their sample. It would however be diffucult to enforce this.
* These are custom NFTs I generated and embedded with audio files. The audio clips are deconstructed parts of a song I composed. Each NFT is its own unique audio loop.
* In order to interact with the app, you will need an Ethereum wallet ex.Metamask, be on the Lightlink Pegasus Testnet and have test <a href="https://faucet.pegasus.lightlink.io">Ether</a>.
  


### Marketplace template
(notes on the template)<br>
This repository is an example of an application running on the [Liteflow](https://liteflow.com) infrastructure to showcase the uses of the infrastructure and/or be used as a starter kit to launch a product fast. The theme is based on [ChakraUI](https://chakra-ui.com/) and can be [customized](https://chakra-ui.com/docs/styled-system/customize-theme) in the `/styles/theme.ts` file.

#### Application
Marketplace template includes default navigation, metadata, and wallets that can be updated directly from the `pages/_app.tsx` file.
