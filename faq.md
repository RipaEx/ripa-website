---
layout: default
title: Frequently Asked Questions
permalink: /faq/
---

<div class="spacial-features customFadeInUp" data-scroll="">
    <section class="container">
        <div class="row">
            <div class="col-12">
                <div class="header">
                    <h2>Frequently Asked Questions</h2>
                    <p>
                        The Ripa team has collected some of the most common questions asked throughout our many social media platforms (Slack, email, Facebook, Twitter, etc…). We’ll keep them updated and include new commonly asked questions as they come along. The following sections will help you find the answers you are looking for with links to guides that give further explanations:
                    </p>
                </div>
            </div>
        </div>
    </section>
</div>

<div class="faqs customFadeInUp" style="padding-top: 50px" data-scroll="">
    <section class="container">
        <div class="row">
            <div class="col-md-12">
                <div id="faq-accordion">
                  <div class="card">
                    <div class="card-header" id="headingOne">
                      <h5 class="mb-0">
                        <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne">
                          1. Fees
                        </a>
                      </h5>
                    </div>
                    <div id="collapseOne" class="collapse" role="tabpanel">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How much do the different RIPA transactions cost?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>
                              <ul>
                                <li>Sending XPX(normal transaction): 0.1 XPX</li>
                                <li>Voting: 1 XPX</li>
                                <li>Unvoting: 1 XPX</li>
                                <li>Registering 2nd passphrase: 5 XPX</li>
                                <li>Registering a delegate name: 25 XPX</li>
                              </ul>
                            </p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Fees are too high, are you planning on reducing them?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Not at the moment, but this is being looked at.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="card">
                    <div class="card-header" id="headingTwo">
                      <h5 class="mb-0">
                        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo">
                          2. Passphrase / Passphrase issues
                        </a>
                      </h5>
                    </div>
                    <div id="collapseTwo" class="collapse">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>What do I do with the passphrase?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>The passphrase is the master password(key) for your XPXtokens. Every XPX address has its own unique passphrase. With the passphrase you can sign transactions to send your XPX or vote for a delegate.</p>
                            <p><b>Do not lose it, and do not share it with others, or you could lose access to your XPX tokens. If you lose your passphrase, or if it is stolen, there is nothing we can do to help you. We CANNOT recover any lost passphrases.</b></p>
                            <p><b>BACKUP YOUR PASSPHRASE! DO NOT LOSE IT! WRITE IT DOWN, SAVE IT HOWEVER YOU CAN!</b></p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>I can’t send a transaction because of a wrong passphrase. What should I do?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>You can’t do anything without the correct passphrase. Please be aware that every character and space counts. Try to remove spaces at the beginning and end. Try to check for capital letters, there should be none (by default 12 words, separated by space, all lower case letters, no space at the beginning or end). Try to spot incorrectly written words. If you do not have the correct passphrase … your tokens could be lost. Again, if you lose your passphrase, there is nothing the RIPA team or anyone else can do to help you.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>What kind of words are used to generate 12 word default passphrase?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>RIPA follows the BIP39 proposal standards. You can find all of the English words used to randomly generate the passphrase here: <a href="https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt">https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt</a></p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Is the 12 word mnemonic passphrase really secure? Can it be brute forced?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Yes it is secure. The 12 word passphrases are much more secure than your usual passwords. Read more on mnemonic generation here: <a href="https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki#Generating_the_mnemonic">https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki#Generating_the_mnemonic</a>. In other words, this means it would currently take all the computing power available on the planet Earth thousands of years to brute force your passphrase.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>What is a 2nd passphrase?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>The second passphrases improves security by adding another 12 words that will be added to your address, making for 24 words total. Make sure <b>you save this 2nd passphrase</b>, as you will now need both passphrases to sign transactions — note that there is currently a 5 XPX transaction fee to create a second passphrase.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>I lost / deleted my 2nd passphrase can I still use my RIPA account?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>NO. If you lose or delete your 2nd passphrase you cannot access your address anymore or sign transactions. You can still import the account/address (1st passphrase), but cannot sign any transactions (you’d need 1st and 2nd passphrase for that). If you lose the 2nd passphrase, you officially make the address/account only view-able and not accessible.</p>
                            <p>2nd passphrase adds additional layer of security on top of your already secure 1st passphrase, but if you lose your 2nd passphrase, or 1st one, your access to that address/account and anything in that address are lost. There is nothing we can do to recover a lost passphrase of any kind.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>I lost my passphrase. Can you guys reset it or reverse my transaction?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>If you lost your passphrase there is literally nothing we can do for you — there is no refund button, “forgot my passphrase” or anything similar.
                            We also cannot reverse any transactions on the blockchain as it is immutable. We are custodians of the code and making sure that the system works like a clock, not the gatekeepers of transactions on the RIPA blockchain.</p>
                            <p><b>WE CANNOT RECOVER LOST PASSPHRASES, NO ONE CAN.</b></p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="card">
                    <div class="card-header" id="headingThree">
                      <h5 class="mb-0">
                        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseThree">
                          3. Desktop wallet Issues and Questions
                        </a>
                      </h5>
                    </div>
                    <div id="collapseThree" class="collapse">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Where can I download RIPA desktop wallet?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>You can download the latest version of the RIPA desktop wallet from our official GitHub repository: <a href="https://github.com/RipaEx/ripa-desktop/releases/latest">https://github.com/RipaEx/ripa-desktop/releases/latest</a>.
                            Just choose the wallet download that matches your operating system.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Why is there a line through a cloud next to my address?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Don’t worry about it, it means this account is new to the network and will disappear after interacting with the network.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>I can’t send a transaction because I get an ‘Invalid timestamp error’. What should i do?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Your operating system time is wrong and is set manually. Please update your computer time/system clock to sync using the internet. You can google guides how to do that for every OS. After you do restart your RIPA Client.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>When I try to send/vote I get the ‘Error: Passphrase is not corresponding to account’ what does it mean?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>It means you did not write/copy your passphrase correctly when signing the transaction. Please be aware that every character and space counts. Try to remove additional spaces at the beginning and end of the passphrase. Try to check for capital letters, there should be none.(default is 12 words, lower-case, separated by space). Try to spot incorrectly written words (some words are similar and differ only by 1 letter, eg. grow — glow,row, …) . If you do not have the correct passphrase … then you CANNOT access that account. We cannot recover lost passphrases, no one can. Do not lose your passphrase.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>What use are these “Offline” folders in the wallet?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>You can use the offline folders to split-up your funds within a wallet. This allows you to better organize your RIPA without paying any fees within the same address. The splitting up of your XPX is local to your computer and not stored on the blockchain.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>When I open my RIPA desktop wallet I see an empty RIPA address which should have XPX tokens in it. What could be the reason I cannot open my RIPA address?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Most likely you are not connected to the network, make sure the cloud icon in the upper right menu (3rd icon) has a checkmark inside it (meaning connected to network) and does not have line through it(disconnected from RIPA network). If it has a line through it, it means either you are not connected to the internet or your firewall maybe blocking your data traffic.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>When I open RIPA Desktop I see black screen and nothing is there / I’m trying to make a screenshot and screen is black?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>If you are connecting to your computer via remote software (eg. Teamviewer) your screen will be black for security reasons (prevents someone trying to access from remote computer, they won’t be able to see your RIPA wallet). Same goes when you are trying to make a screenshot (screen will show black).
                            If you want to disable this, click in the upper left menu Application -> Disable screenshot protection (unsafe). It will be re-enabled every time you restart the wallet.</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="card">
                    <div class="card-header" id="headingFour">
                      <h5 class="mb-0">
                        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseFour">
                          4. Exchanges & Getting RIPA
                        </a>
                      </h5>
                    </div>
                    <div id="collapseFour" class="collapse">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I get XPX tokens?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>XPX is not yet available on exchanges, as it is still at the early stages, exchange listing will happen towards the end of the development phase.</p>
                            <p>You can obtain XPX through the RIPA TEC Sale Channel here:</p>
                            <p style="text-align:center;"><a href="https://tec.ripaex.io/sign-up">TEC.RIPAEX.io</a></p>
                            <p>Earn XPX by contributing to the project. If you have a skill or something worth contributing, message <a href="https://t.me/BitNow">@bitnow</a> in telegram with your idea and if it is used, you can earn XPX for your efforts.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Can I vote from an exchange?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>No. You need to send the XPX to your personal RIPA address and vote via the official RIPA desktop wallet in order to vote.</p>
                          </div>
                        </div>
                      </div>                                  
                    </div>
                  </div>
                  <!-- ACCORDION FIVE-->
                  <div class="card">
                    <div class="card-header" id="headingFive">
                      <h5 class="mb-0">
                        <a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseFive">
                          5. Voting, Delegates, & Calculators
                        </a>
                      </h5>
                    </div>
                    <div id="collapseFive" class="collapse">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I vote for a delegate?</h4>
                          </div>
                          <div class="col-md-12">
                            <p><a href="https://steemit.com/news/@ripaex/how-to-vote-and-un-vote-a-ripa-delegate">Follow our voting guide</a></p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I find and choose a delegate?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>The best places to find delegate information are:</p>
                            <p><a href="https://forum.ripaex.io/category/5/delegates">https://forum.ripaex.io/category/5/delegates</a></p>
                            <p><a href="https://www.reddit.com/r/ripaex/">https://www.reddit.com/r/ripaex/</a></p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How much will I get from voting?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>How much you receive is up to the pool operators and not contingent on any rules set up by the RIPA Crew. You can check sharing approximations in one of the community built calculators when they become available.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How much XPX do I need to vote?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>The fee to register your vote is currently 1 XPX. Your remaining balance will decide how much of a share you will get from your pool operator for your delegate. Please check sharing calculators listed above and then you can estimate how long it will take to gain back the fee. It is important to check the delegates proposals often as they may change. Some delegate pools do have requirements that you need to fulfil in order to get rewards. Some also deduct the transaction fees from your share. If you can find a good delegate it makes sense to vote even with around 100 XPX. But the entire voting system is subject to the ever changing delegate market. Please educate yourself before voting. If you have delegate specific questions, contact the delegate you wish to vote for. Delegates have contact info in their proposals.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Is voting a risk for my wallet?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>The best places to find delegate information are:</p>
                            <p>No. All you can “lose” is the 1 XPX voting fee. All other XPX tokens will stay in your wallet and you have full control over them. Please do not send tokens to any of the delegates! That will not count as a vote and you might lose your tokens.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I change my vote?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>You can remove the vote registration from a delegate (unvote). Then it’s best to restart the desktop client and vote for the new delegate of your choice.</p>
                            <p><a href="https://steemit.com/news/@ripaex/how-to-vote-and-un-vote-a-ripa-delegate">Follow our voting guide.</a></p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Can I vote for multiple delegates?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>You can only vote for one delegate from one address. If you want to support multiple delegates you will have to create additional addresses and split up your XPX into multiple addresses.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Do i have to re-vote when I receive additional XPX tokens in my wallet?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>No. The vote weight will automatically adapt to your wallet balance for every deposit and withdrawal you make from that address.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Can I vote from an exchange?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>No. You need to send the XPX to your personal RIPA address and vote via the official RIPA desktop wallet.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>I just put all my XPX on a Ledger Nano S, do I need to re-vote?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Yes. New address means new vote.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Do I need to keep my wallet open after I vote?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>No. Once you vote it is registered on the blockchain and tied to your specific address. You can open and close the wallet as you please.</p>
                          </div>
                        </div>
                      </div>                     
                    </div>
                  </div>
                  <!-- ACCORDION SIX-->
                  <div class="card">
                    <div class="card-header" id="headingSix">
                      <h5 class="mb-0">
                        <a data-toggle="collapse" data-parent="#accordion" href="#collapseSix">
                          6. Bounties
                        </a>
                      </h5>
                    </div>
                    <div id="collapseSix" class="collapse" role="tabpanel">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I earn some bounties?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>
                              <ul>
                                <li><a href="https://steemit.com/news/@ripaex/contributor-bounty-airdrop-is-now-live">Bounty Program</a></li>
                                <li><a href="https://steemit.com/news/@ripaex/ripa-github-development-bounty-program">GitHub Bounty Program for Developers</a></li>
                                <li><a href="https://forum.ripaex.io/category/8/ripa-community-fund-rcf">Ripa Community Fund - RCF - make your own proposal</a></li>
                              </ul>
                            </p>
                            <p>
                              What if I have a custom proposal for RIPA?
                              You can get in contact with us on slack or telegram, message <a href="https://t.me/BitNow">@bitnow</a> or <a href="https://t.me/wazzy">@Wazzy</a> or email us at <a href="mailto:info@ripaex.io">info@ripaex.io</a>
                            </p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <!-- ACCORDION SEVEN-->
                  <div class="card">
                    <div class="card-header" id="headingSeven">
                      <h5 class="mb-0">
                        <a data-toggle="collapse" data-parent="#accordion" href="#collapseSeven">
                          7. Explorer & Explorer Links
                        </a>
                      </h5>
                    </div>
                    <div id="collapseSeven" class="collapse" role="tabpanel">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Sometimes official explorer doesn’t work, why?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>We receive a lot of traffic and sometimes explorer gets stuck, which needs to be restarted and resync with blockchain so can take some time.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>What can I do in that case if official explorer is not available?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Our community is running alternative explorers which you can use as well. Here are the links:</p>
                            <p>
                              <ul>
                                <li><a href="https://explorer.ripaex.io/delegatemonitor">MainNET Explorer</a></li>
                                <li><a href="https://ripa-explorer.netlify.com/">Backup Explorer</a></li>
                                <li><a href="https://ripa-exp.geops.net/">Community Explorer</a></li>
                              </ul>
                            </p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <!-- ACCORDION EIGHT-->
                  <div class="card">
                    <div class="card-header" id="headingEight">
                      <h5 class="mb-0">
                        <a data-toggle="collapse" data-parent="#accordion" href="#collapseEight">
                          8. Setting Up a Node/Security/Swap
                        </a>
                      </h5>
                    </div>
                    <div id="collapseEight" class="collapse" role="tabpanel">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I setup a node for RIPA network?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Follow our guide: <a href="https://steemit.com/news/@ripaex/how-set-up-a-node-for-ripaex">How to set up a Ripa Node</a></p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I better secure my RiPA server?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Follow our guide: Guide coming soon</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>How can I enable swap memory and swapiness on my RIPA server?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>Follow our guide: guide coming soon</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <!-- ACCORDION NINE-->
                  <div class="card">
                    <div class="card-header" id="headingNine">
                      <h5 class="mb-0">
                        <a data-toggle="collapse" data-parent="#accordion" href="#collapseNine">
                          9. Ledger 
                        </a>
                      </h5>
                    </div>
                    <div id="collapseNine" class="collapse" role="tabpanel">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Coming Soon</h4>
                          </div>
                          <div class="col-md-12">
                            <p></p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                  <!-- ACCORDION TEN -->
                  <div class="card">
                    <div class="card-header" id="headingTen">
                      <h5 class="mb-0">
                        <a data-toggle="collapse" data-parent="#accordion" href="#collapseTen">
                          10. Roadmap/Updates 
                        </a>
                      </h5>
                    </div>
                    <div id="collapseTen" class="collapse" role="tabpanel">
                      <div class="card-body">
                        <div class="row">
                          <div class="col-md-12">
                            <h4>What are you guys working on now, whats the next update?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>You can check our roadmap for current updates and ongoing projects: All the information related to the Ripaex project is contained in the RIPAEX white paper including roadmap. The new ripaex website will contain the roadmap, it will be available soon.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>When will the next “big thing” be released, why are there no dates?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>RIPA gives no dates, we develop and announce. We update when we feel something is ready and properly announce via social media and this blog.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>What are your plans for marketing?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>RIPA does not discuss marketing plans or strategic partnerships with the general public. Message a team member privately if you have something to discuss.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>When will you be on new exchanges?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>RIPA does not discuss strategic partnerships or exchange additions with the general public until we are ready to announce them or when exchange decides to announce.</p>
                          </div>
                        </div>
                        <div class="row">
                          <div class="col-md-12">
                            <h4>Do you have more questions?</h4>
                          </div>
                          <div class="col-md-12">
                            <p>We’ve got an awesome community who are always willing to help. Please get in contact and ask your question:</p>
                            <p>
                              <ul>
                                <li>Slack: <a href="https://join.slack.com/t/ripaex/shared_invite/enQtMzM4NzUwNjU4OTQ0LTY3MDJmMTdhYTNlZjJlNGUxNzM1YjUwYjgyYjZlMDJmOTg3NTIzNThmNTYyMGQ3ODBkOTRmYzk3Y2Y4MzBkOTY">https://ripaex.slack.com</a></li>
                                <li>Telegram: <a href="https://t.me/ripaex">https://t.me/ripaex</a></li>
                                <li>Reddit: <a href="https://www.reddit.com/r/RipaEx/">https://www.reddit.com/r/RipaEx/</a></li>
                                <li>E-Mail: <a href="mailto:info@ripaex.io">info@ripaex.io</a></li>
                              </ul>
                            </p>
                            <p>
                              Special thanks to community member ‘boldninja at ARK.io SCIC’ who did most of the work
                            </p>
                            <p>
                            If you want to see any Q/A added to the list contact Giovanni at <a href="mailto:info@ripaex.io">info@ripaex.io</a> or me <a href="https://t.me/wazzy">@Wazzy</a> on Telegram
                            </p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
            </div>
        </div>
    </section>
</div>