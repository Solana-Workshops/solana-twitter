# Solana Twitter

## 🎬 Recorded Sessions
| Link | Instructor | Event |
| ---- | ---------- | ----- |
| [<img src="https://raw.githubusercontent.com/Solana-Workshops/.github/main/.docs/youtube-icon.png" alt="youtube" width="20" align="center"/> Recording](https://youtu.be/yubojBH8e_Q) | Joe Caulfield | N/A |

## ☄️ Open in Solana Playground IDE

| Program | Link |
| -------------------- | --------------------------------------- |
| v1 | [ ![program](https://ik.imagekit.io/mkpjlhtny/solpg_button_zWM8WlPKs.svg?ik-sdk-version=javascript-1.4.3&updatedAt=1662621556513)](  https://beta.solpg.io/github/https://github.com/Solana-Workshops/solana-twitter/tree/main/programs/solana-twitter-v1) |
| v2 | [ ![program](https://ik.imagekit.io/mkpjlhtny/solpg_button_zWM8WlPKs.svg?ik-sdk-version=javascript-1.4.3&updatedAt=1662621556513)](  https://beta.solpg.io/github/https://github.com/Solana-Workshops/solana-twitter/tree/main/programs/solana-twitter-v2) |

## 📗 Learn

This workshop demonstrates how to create a social media app (like Twitter) using Solana's PDAs and on-chain data.   
   
You can find all of the details on how this program works in the [Diagrams](#diagrams) section below.

### A Note on v1 & v2

This demo is broken up into two programs: v1 and v2. 
* **v1**:
    * Demonstrates how to use PDAs to create profiles and tweets, and also likes and retweets
    * Leverages seed mapping and counter fields to load a user's data   
* **v2**:
    * Build *on top of* v1, with some new features
    * Introduces the ability to mint users tokens based on their earned likes & retweets
    * Demonstrates how to create mints that are PDAs off of the program
    * Demonstrates how to designate the program (via a PDA) as the Mint Authority
    * Demonstrates how to airdrop users tokens without requiring action on their part

## Diagrams

![](./data_model.jpg)
![](./fetching_data.jpg)
![](./autoincrement.jpg)