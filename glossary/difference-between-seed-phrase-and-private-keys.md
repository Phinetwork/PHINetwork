# 🌟 Difference Between Seed Phrase & Private Keys

| Key Takeaways:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>— A private key and a recovery phrase: two closely related concepts that are central to crypto security.<br><br>— Both provide a vector for accessing your blockchain assets, but do so in different ways and have different vulnerabilities.<br><br>— Private keys in raw form are 256 digits long, making them impractical for storing, securing and transacting with. That’s why we have the humble crypto wallet to protect them!<br><br>— But what if you lose your crypto wallet? This is where your recovery phrase comes in. Unlike a private key, the seed phrase doesn’t just relate to one blockchain address, but all the addresses secured by the private keys in your wallet.<br><br>— Recovery phrases and private keys are two halves of the same whole, but need to be managed differently. Let’s take a closer look!</p> |

_Private key, seed phrase, wallet, blockchain address – man crypto can be confusing! If you feel like you’re not sure which one’s which_, _then this is the article for you. Here, we get into the nitty-gritty of private keys and recovery phrases, their relationship and the differences between them._

So you’ve bought yourself some crypto – congratulations! But how do you keep it secure? With a [crypto wallet](https://www.ledger.com/academy/what-is-a-crypto-wallet), of course.

The purpose of a crypto wallet is actually not to store your crypto – your coins and tokens [live on the blockchain](https://www.ledger.com/academy/crypto/where-are-my-coins) – but instead, to secure your private keys. And when you begin using your wallet, it will also generate an important piece of data that you need to safeguard – your 24-word recovery phrase.

### SAME SAME – BUT DIFFERENT

Your [private key](https://www.ledger.com/academy/basic-basics/owning-and-using-it/what-is-a-private-key) and recovery phrase are two halves of the same whole – in fact, your recovery phrase _is_ simply your private key in a different format. This can make it hard to understand the purpose and differences between these two concepts, and consequently, how to keep them safe.

So here, let’s take a deep dive into your private key and recovery phrase, the relationship between them, and the risks faced by each one, so you can manage your crypto with absolute confidence.

HWG!

### PRIVATE KEYS – INVISIBLE MASTERS OF CRYPTO

When all is said and done, private keys are the central element of crypto ownership. [Blockchain](https://www.ledger.com/academy/how-does-a-blockchain-transaction-work) is a digital storage network, and having the private key for a given blockchain address means that you control everything at that address.

#### SO WHERE DOES THE PRIVATE KEY COME FROM?

You generate a private key (along with a corresponding public key) any time you create a blockchain address.&#x20;

The best way to think about them is by imagining your public key as your email address: it allows others to find you, and send you things. But only the private key (think of this as your email password) lets you open the address, access what’s inside and send things from it.&#x20;

So in essence your private key is what gives control over crypto assets. This is why it is so important to manage your private key responsibly and ensure nobody else can access it – yet this can be a challenge.

### PRIVATE KEYS ARE TRICKY…

Private keys might well be at the centre of your crypto control, but they come with some difficulties.

#### LONG AND COMPLICATED

In raw form, a private key is a string of 256 alphanumeric characters. Imagine trying to type those digits in accurately each time you transact! A number this complex isn’t really a practical way for human to sign transactions, and is prone to mistakes. Remember – a mistake on the blockchain cannot be undone, so the sheer length of private keys makes them a risky piece of data.

#### PRYING EYES ARE ALWAYS LURKING

And that’s not all. Since your private key gives access to your blockchain address, it is a huge target for opportunists looking to steal your crypto. So although you need this data on a regular basis if you’re transacting with crypto, you also need to ensure it stays completely private and unseen. Not an easy balance.

#### A BEACON FOR ONLINE THREATS

We know what you’re thinking: why not secure the private key on a computer, or better still, a digital crypto wallet? Sounds perfect, right?!

Not really. Your device, be it a phone or computer, is just about the most unsafe place you can keep your private key, whether or not you’re using a crypto wallet interface. Anything connected to the internet can be targeted via remote hacks and malware, allowing bad actors to view data stored on your computer, or even hack into your online crypto wallet to retrieve the private keys. This is why computer storage simply is not a secure solution for your private keys.

So in short, what’s needed is a way of using your private key easily, without it ever being exposed, either online or physically. And what’s more, to do this in a way that leaves you ultimate control over your crypto assets, independently of any third party.  This is where crypto hardware wallets – and the recovery phrase – come into play.

### HARDWARE WALLETS: COMPLETE PROTECTION, COMPLETE CONTROL

As the leading crypto hardware wallet, securing your private keys offline – while leaving you with ultimate control over your crypto assets – is Ledger’s sole objective.&#x20;

Ledger devices provide an environment where your private keys remain offline at all times. The device itself is never connected to the internet, and even when you transact with online platforms, the private key signs transactions inside the device.

The result? Your private key stays out of reach of digital hackers looking to access your crypto via your internet connection.

Hardware devices are a beautiful solution to a complex problem, allowing you to secure your private keys without compromising on utility. But ironically, keeping your keys in a device begs a new question:

_What if you lose your wallet? Does this mean you’ll lose your crypto?_

Of course not. It’s time to talk about your recovery phrase, its purpose – and how to keep it safe.

### RECOVERY PHRASE: YOUR CRYPTO FINGERPRINT

The [recovery phrase](https://www.ledger.com/academy/crypto/what-is-a-recovery-phrase) – sometimes called the seed phrase or mnemonic phrase – is a 12, 18, or 24-word pattern generated each time a new wallet is created. Unlike your private key, which relates to just one blockchain address, the recovery phrase is a derivative of your entire wallet, and all private keys stored there.

In layman’s terms, a recover phrase is the “master __ key” for all of your crypto accounts – it is your private keys in mnemonic form. These words, when entered into another crypto wallet (in the correct order) will recover all of the private keys you were storing on your original wallet. The purpose? Giving you control. Having this phrase means that even if you lose your physical hardware device, you’ll still have access to your blockchain assets.

#### BIP-39 STANDARD – MAKING CRYPTO WALLETS INTEROPERABLE

It may seem like a string of random words, but in fact the format of your recovery phrase is exactly what enables you to stay in control of your crypto.

Any time a crypto wallet generates a recovery phrase, the words are selected from a list of 2048 possibilities, referred to as the _BIP-39 standard Word_ [_List_](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt) – more or less all wallets, including the Ledger Nano, generate recovery phrases using words from this list.&#x20;

By doing so, we ensure that you, the user, can access your crypto accounts from any other wallet – sort of like having a charger that fits any phone. Imagine if every wallet required a recovery phrase in a different format – your access to your crypto would be dependent on whichever type of recovery phrase you were using, meaning you don’t really control your crypto at all.

So by using the BIP-39 standard for generating your recovery phrase, Ledger (and all other wallets using the same standard) makes sure that you own your crypto assets, not your wallet provider.

### RECOVERY PHRASE VULNERABILITIES

So your recovery phrase is sort of a shorthand for all of your private keys which gives you absolute control over all of your assets, even without your wallet – but it also entails some major vulnerabilities, and these need to be factored into the way you manage it.

#### GIVES ACCESS TO MULTIPLE CRYPTO ACCOUNTS

Unlike a private key, which corresponds to just one crypto account, the recovery phrase gives instant access to every currency in your wallet. So if it falls into the wrong hands, the potential risk to your crypto is far greater.

#### MANAGED BY YOU – USEFUL TO ANYONE

And more importantly, unlike a private key, which is always concealed inside your wallet, the recovery phrase needs to be physically _written down and managed by you._&#x20;

How you do this will define your security, because it can be used by anyone, on any other wallet – so if someone else gets hold of this phrase, consider your assets gone. So let’s take a look at the best ways of storing your recovery phrase, to make sure your private keys stay absolutely safe when you’re using your wallet.

### STORING YOUR RECOVERY PHRASE SAFELY

The whole objective of using a hardware wallet is to keep your private keys away from threats, including both online and offline vectors. So it is essential that you treat your recovery phrase with the same care.

#### KEEP IT OFFLINE

Storing your recovery phrase on a connected device completely defeats the purpose of using a hardware wallet: just like a private key, a hack or malware deployed via your connection could simply target your phrase, and access your whole wallet.

#### STAY FIRE AND WATER PROOF

In crypto, there is no customer service, no support team and no online database of your details. There’s just you and your recovery sheet. That’s it.

It might seem obvious, but keeping your recovery sheet in a place where it cannot be damaged by fire or water is a must – either of these things could potentially destroy your only backup.&#x20;

Luckily, products like the[ Cryptosteel Capsule Solo ](https://shop.ledger.com/products/cryptosteel-capsule-solo)and the [Billfodl](https://shop.ledger.com/products/the-billfodl) both enable you to record your recovery phrase on a steel back-up, making it resistant to fire, water damage and more or less all physical threats. That means your recovery phrase stays safe and secure on a medium that cannot be destroyed.

#### AND OF COURSE – KEEP IT HIDDEN!

Your recovery phrase is a record of all your private keys. This means that storing it in a place known only to you is a fundamental part of keeping it safe.&#x20;

With your private keys safely inside your Ledger device, yet readily available to you for transactions, you will rarely use your recovery phrase. That’s the way it’s meant to be! So take your time, think carefully about where to store your phrase and make sure that safety is your top priority when deciding. It may be the most important thing you do.
