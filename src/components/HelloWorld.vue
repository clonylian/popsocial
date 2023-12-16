<template>
  <div>
    <div class="box">
         <div class="overlay" :class="{ active: showOverlay }" @click="closeOverlay">
              <div class="tank">
                  <div class="tank_3">
                      <img class="clone" @click="closeOverlay" src="../assets/close.svg">
                    </div>
                  <div class="tank_1">
                      <img src="../assets/longd.svg">
                      <h1>UPDATED COMMUNITY SALE ROUND 2 DATE</h1>
                      <img src="../assets/longd.svg">
                    </div>
                  <div class="tank_2" @click="closeOverlay">
                      <p>12:00 UTC OCT 2ND - 12:00 UTC OCT 5TH</p>
                    </div>
                </div>
            </div>
      <div class='head'>
        <img class="head_2" src="../assets/1.png">
        <div class="head_1">
          <a>
            <p>Home</p>
          </a>
          <img v-show="!showNewImage" class="old-image" src="../assets/4.svg">
          <img v-show="showNewImage" class="new-image" src="../assets/head_1.png">
          <a><img class="head_4" src="../assets/head_2.png"></a>
          <a class="head_6" @mouseleave="hideHead" @mouseenter="showHead">
            <p>Highlights</p>
            <div class="head_12">
              <img class="head_7" src="../assets/x.svg">
              <div class="head_8">
                <div class="head_9">
                  <h2>Features</h2>
                  <h2>Events</h2>
                </div>
                <div class="head_10">
                  <div>
                    <div class="head_11"><img src="../assets/2.svg">Career</div>
                    <div class="head_11"><img src="../assets/3.svg">Pop in Media</div>
                    <div class="head_11"><img src="../assets/4.svg">Pop Token</div>
                  </div>
                  <div>
                    <div class="head_11"><img src="../assets/5.svg">Blog</div>
                    <div class="head_11"><img src="../assets/6.svg">Creator</div>
                  </div>
                  <div>
                    <div class="head_11"><img src="../assets/7.svg">Consensus 2023</div>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
        <div class="head_5">
          <a @click="add" style="cursor: pointer;">
            Connect
          </a>
        </div>
      </div>
      <div class="zmd">
        <div class="zmd_1">
          <img src="../assets/11.svg">
          <img src="../assets/8.svg">
          <img src="../assets/9.svg">
          <img src="../assets/10.svg">
          <img src="../assets/11.svg">
          <img src="../assets/8.svg">
          <img src="../assets/10.svg">
        </div>
      </div>
      <div class="center">
        <div class="cen">
          <div class="tab_1">
            <div class="tab_2" v-show="activeIndex === 0">
              <div class="tab2_1">
                <h2 class="tab2_h2">PARTICIPATE IN THE COMMUNITY SALE AND SHARE A PRIZE POOL OF 1 MILLION $PPT TOKEN!
                </h2>
                <p>Pop Social will Airdrop 1 Million $PPT Token to All Community Sale Participants!</p>
                <div class="tab2_1_1">
                  <div class="tab2_1_2">
                    <img src="../assets/12.svg">
                    <img class="tab2_1_4" src="../assets/xuxian.svg">
                    <img src="../assets/13.png">
                    <img class="tab2_1_4" src="../assets/xuxian.svg">
                    <img src="../assets/13.png">
                  </div>
                  <div class="tab2_1_3">
                    <div class="tab2_1_5">
                      <div class="tab2_1_7">
                        <span>STAGE</span>
                        <h2>1</h2>
                      </div>
                      <p>Sep. 19th 14:00 UTC - Sep. 22nd 14:00 UTC</p>
                      <div class="tab2_1_6">
                        Sold Out
                      </div>
                    </div>
                    <div class="tab2_1_8">
                      <div class="tab2_1_9">
                        <span>STAGE</span>
                        <h2>2</h2>
                      </div>
                      <p>12:00 UTC Oct 2nd - 12:00 UTC Oct 5th</p>
                      <div class="tab2_1_10">
                        Contact Us
                      </div>
                    </div>
                    <div class="tab2_1_11">
                      <div class="tab2_1_12">
                        <p>CLAIM AIRDROP</p>
                      </div>
                      <img class="tab2_1_13" src="../assets/15.webp">
                    </div>
                  </div>
                </div>
                <div class="tab2_1_14">
                  <div class="tab2_1_15">
                    <h2>Mint the Pop Pilot Pass to Get More $PPT Airdrop</h2>
                    <p>Pop Pilot Pass Now Support on opBNB!</p>
                    <div class="tab2_1_16"><img src="../assets/16.svg">
                      <p>Mint on opBNB</p>
                    </div>
                  </div>
                  <div class="tab2_1_17">
                    <video autoplay loop src="../assets/video.mp4"></video>
                  </div>
                </div>
              </div>
              <div class="tab_3">
                <div class="tab3_1">
                  <div class="tab3_2">
                    <h2>Round 1</h2>
                  </div>
                  <div class="tab3_3">
                    <span><i>SUCCESSFULLY</i></span>
                    <br>
                    <p><img src="../assets/11.svg"><i>CLOSED</i><img src="../assets/9.svg"></p>
                  </div>
                  <p class="tab3_4">ROUND 2</p>
                  <p class="tab3_5">1 PPT = $0.200</p>
                  <p class="tab3_4">1 USDT = 5.00000 PPT</p>
                  <p class="tab3_4">MIN $100, MAX $5000</p>
                  <div class="tab3_6">
                    <img class="tab3_7 animated" src="../assets/17.svg">
                    <p src="">
                      There will NEVER be a PPT price of $0.188 again, get involved before the price goes higher!
                    </p>
                    <img class="tab3_8" src="../assets/18.svg">
                  </div>
                  <div class="tab3_9">
                    <p>How To Buy?</p>
                    <p style="color:rgba(255, 255, 255, 0.2) ;">|</p>
                    <p>Contact Us</p>
                  </div>
                </div>
                <div class="tab4_1">
                  <div class="tab4_2">
                    <div class="tab4_3">
                      <img src="../assets/19.svg">
                      <p><a href="">Whitepaper</a> </p>
                    </div>
                    <div class="tab4_3">
                      <img src="../assets/20.svg">
                      <p><a href="">Verified Contract</a></p>
                    </div>
                  </div>
                </div>
                <div class="tab4_4">
                  <div class="tab4_5">
                    <a href=""> <img src="../assets/27.svg"></a>
                    <a href=""> <img src="../assets/28.svg"></a>
                    <a href=""> <img src="../assets/29.svg"></a>
                    <a href=""> <img src="../assets/32.svg"></a>
                    <a href=""> <img src="../assets/33.svg"></a>
                    <a href=""> <img src="../assets/31.svg"></a>
                  </div>
                </div>
              </div>
            </div>
            <div class="tab5" v-show="activeIndex === 1">
              <div class="tab5_1">
                <p class="tab5_2">Unlock Your Digital Destiny: Embrace the Soulbound Journey and Explore Web3's Wonders on
                  ZkSync for a Boundless Future!</p>
                <h1>POP SOCIAL LAUNCHES POP PILOT PASS</h1>
                <div class="tab5_3">
                  <p><a href="">QUEST 1-<span style=" text-decoration: underline; ">MINT PILOT PASS</span></a></p>
                  <img src="../assets/36.webp">
                </div>
                <div class="tab5_3">
                  <p><a href="">QUEST 2-<span style=" text-decoration: underline; ">GET TREASURE CHEST</span></a></p>
                  <img src="../assets/36.webp">
                </div>
                <div class="tab5_4">
                  <div class="tab5_5">
                    <div class="tab5_6">
                      <img src="../assets/35.webp">
                      <p>8.29-10.31</p>
                    </div>
                    <img src="../assets/34.svg">
                    <p>Learn More About Pilot Pass Here</p>
                  </div>
                </div>
                <div class="tab5_7">
                  <a href="" class="tab5_8" style="margin-right: 3rem;">
                    <img src="../assets/37.webp">
                  </a>
                  <a href="" class="tab5_8">
                    <img src="../assets/38.webp">
                  </a>
                </div>
              </div>
              <div class="tab_rig">

              </div>
            </div>
          </div>
          <div class="xuan">
            <p @click="activeIndex = 0" :class="{ active: activeIndex === 0 }"></p>
            <p @click="activeIndex = 1" :class="{ active: activeIndex === 1 }"></p>
          </div>
        </div>
      </div>
      <div class="suzi">
        <div class="suzi_1">
          <h2>102385</h2>
          <span>Daily Active Users</span>
        </div>
        <div class="suzi_1">
          <h2>79547</h2>
          <span>User Growth Last Week</span>
        </div>
        <div class="suzi_1">
          <h2>237652</h2>
          <span>Total Users</span>
        </div>
        <div class="suzi_2">
          <span>
            Updated at
          </span>
          <p>
            2023-09-22 11:00:00 UTC
          </p>
        </div>
      </div>
      <div class="bakes">
        <div class="bakes_1">
          <h1>Partners & Backers</h1>
          <img src="../assets/40.png">
        </div>
        <p class="bakes_2">The Pop Social Ecosystem is a multi-chain platform, check out all our partners on the same
          quest as ours in
          making the Web3 space more easily accessible.</p>
        <div class="bakes_3" v-show="activeIndexs === 0">
          <a href="" class="bakes_4">
            <img src="../assets/41.webp">
          </a>
          <a href="" class="bakes_5">
            <img src="../assets/42.webp">
          </a>
          <a class="bakes_6">
            <img src="../assets/43.webp">
          </a>
          <a href="" class="bakes_8">
            <img src="../assets/44.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/45.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/46.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/47.png">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/48.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/49.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/50.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/51.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/52.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/53.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/54.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/55.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/56.webp">
          </a>
        </div>
        <div class="bakes_3" v-show="activeIndexs === 1">
          <a href="" class="bakes_6">
            <img src="../assets/57.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/58.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/59.svg">
          </a>
          <a href="" class="bakes_10">
            <img src="../assets/60.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/61.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/62.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/63.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/64.webp">
          </a>
          <div class="bakes_11">
            <a href="" class="bakes_6">
              <img src="../assets/65.svg">
            </a>
            <a href="" class="bakes_6">
              <img src="../assets/66.svg">
            </a>
            <a href="" class="bakes_6">
              <img src="../assets/67.svg">
            </a>
          </div>
        </div>
        <div class="tbiao_p">
          <p @click="activeIndexs = 0" :class="{ active: activeIndexs === 0 }"></p>
          <p @click="activeIndexs = 1" :class="{ active: activeIndexs === 1 }"></p>
        </div>
      </div>
      <div class="Feature">
        <div class="bakes_1">
          <h1>Top Media Feature</h1>
          <img src="../assets/68.png">
        </div>
        <p class="Feature_2">Check out what the world has to say about Pop! Catch all our latest media features here.</p>
        <div class="bakes_3">
          <a href="" class="bakes_6">
            <img src="../assets/69.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/70.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/71.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/72.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/73.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/74.webp">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/75.svg">
          </a>
          <a href="" class="bakes_6">
            <img src="../assets/76.svg">
          </a>
        </div>
      </div>
      <div class="pop">
        <div class="pop_1">
          <div class="pop_2">
            <div class="pop_3">
              <img src="../assets/77.webp">
              <h2>Pop Token (PPT)</h2>
            </div>
            <p class="pop_4">The Pop ecosystem is run by a sustainable economic model. The steady flow of PPT within the
              Pop Ecosystem
              allows the Pop Treasury to capture value from both users and creators and redistributes this value back to
              the community on a contributon basis.</p>
            <img class="pop_5" src="../assets/78.webp">
          </div>
          <div class="pop_2">
            <div class="pop_3_1">
              <h2>Pop Token (PPT)</h2>
            </div>
            <p class="pop_4">The Pop ecosystem is run by a sustainable economic model. The steady flow of PPT within the
              Pop Ecosystem
              allows the Pop Treasury to capture value from both users and creators and redistributes this value back to
              the community on a contributon basis.</p>
            <img class="pop_5_1" src="../assets/79.webp">
          </div>
          <div>
          </div>
        </div>
        <div class="pop_6">
          <div class="pop_7">
            <div class="pop_8">
              <h3>200,000,000</h3>
              <span>Total Supply</span>
              <img src="../assets/80.webp">
            </div>
            <div class="pop_9">
              <h3>Use PPT</h3>
              <P>With PPT, you can process transactions, make purchase, unlock Treasure Chests, level up your account, and
                gain governance power.</P>
              <img src="../assets/81.svg">
            </div>
          </div>
          <div class="pop_10">
            <div class="pop_11">
              <img src="../assets/83.webp">
              <div class="pop_12">
                <h1>TOKENOMICS</h1>
                <img src="../assets/85.webp">
              </div>
              <div class="pop_13">
                <div>Verified Contract</div>
                <div>Litepaper</div>
              </div>
            </div>
            <div class="pop_14">
              <div class="pop_2">
                <div class="pop_3_1">
                  <h2>Multi - Chain Functionality</h2>
                </div>
                <p class="pop_4">Pop began its journey on BNB Smart Chain and is also available on Polygon. As a
                  multi-chain project, we will soon be available on many other chains.</p>
                <img class="pop_15" src="../assets/82.webp">
              </div>
            </div>
          </div>
          <div class="pop_16">
            <div class="pop_17">
              <p>Pop Social's PPT Token's smart contract has successfully undergone a comprehensive audit conducted by
                PeckShield, ensuring the utmost safety and security for your interactions with our token sales. Your peace
                of mind is our priority.</p>
              <img src="../assets/84.svg">
            </div>
          </div>
        </div>
      </div>
      <div class="Roadmap">
        <div class="bakes_1">
          <h1>Our Roadmap</h1>
          <img src="../assets/86.webp">
        </div>
        <div class="Roadmap_1">
          The Pop team is ecstatic about the road ahead. The future of Pop will be much like its present, to be the
          ultimate Web3 social ecosystem that empowers users by placing creators in the middle. Our roadmap will tell you
          all about it.
        </div>
        <div class="Roadmap_2">
          <div class="Roadmap_3"></div>
          <div class="Roadmap_4"></div>
          <div class="Roadmap_5"></div>
          <div class="Roadmap_6"></div>
        </div>
      </div>
      <div class="Media">
        <div class="bakes_1">
          <img src="../assets/91.png">
          <h1>Our Roadmap</h1>
        </div>
        <div class="carousl">
          <div class="carousl_1">
            <el-carousel :interval="1000000" type="card" height="600px">
              <el-carousel-item v-for="item in dataList" :key="item.id" align="center">
                <div class="carousl_2">
                  <img :src="item.src" alt="" />
                  <div class="carousl_3">
                    <h2>{{ item.txt }}</h2>
                    <p>{{ item.txts }}</p>
                  </div>
                </div>
              </el-carousel-item>
            </el-carousel>
          </div>
        </div>
      </div>
      <div class="yendliu">
        <div class="yendliubox">
          <div :class="ytabeliu == 1 ? 'yendliubyi yshowliu' : 'yendliubyi'">
            <div class="yendlbt">
              <div class="yendliubti">
                The Social Platform Where Engagement Earns Rewards
              </div>
              <img src="../assets/64ca54aa71ad440e22dc6ba1_WatchvideotoearnPPT.png" alt="" />
            </div>
            <div class="yendliubcon yflex">
              <div class="yendliubcleft">
                <div class="yendliubcltop">
                  <div class="yendliubclytxt">
                    <p>
                      We understand the true worth of your engagement. The more
                      you engage, the more you earn! Don't miss out on this
                      incredible opportunity.
                    </p>
                  </div>
                </div>
                <div class="yendliubclbot yflex">
                  <div class="yendliubclboty"></div>
                  <div class="yendliubclboty"></div>
                </div>
              </div>
              <div class="yendliubcright">
                <div class="yendliubcrbox">
                  <img class="yendliubcrbimgy" src="../assets/6474a3593cfe3851b742d972_icon__3.png" alt="" />
                  <img class="yendliubcrbimge" src="../assets/64905c26189d0e9f85eec012_PPT1-p-500.webp" alt="" />
                  <p class="yendliubcrbtxty" style="margin-top: 11rem">
                    Pop is a social platform that values your active
                    participation and rewards you for every interaction. As you
                    connect with friends, explore captivating content, and join
                    vibrant communities, you'll earn valuable tokens that can be
                    redeemed for exciting perks and experiences.
                  </p>
                  <p class="yendliubcrbtxty">
                    Imagine being able to turn your passion for connecting with
                    others into tangible rewards, whether it's unlocking premium
                    features, accessing VIP events, or even receiving exclusive
                    digital collectibles. With Pop, the possibilities are
                    endless.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div :class="ytabeliu == 2 ? 'yendliuber yshowliu' : 'yendliuber'">
            <div class="yendlbtshop">
              <div class="yendliubti">Shop</div>
              <img src="../assets/649e8c8f3644517f13fff851_shop.webp" alt="" />
            </div>
            <div class="yendliubconer">
              <div class="yendliubcer yflex">
                <div class="yendliubcerleft">
                  <div class="yendliubcelbox">
                    <img src="../assets/649e43b957bee709f411b745_Group48096300.webp" alt="" />
                  </div>
                  <div class="yendliiubcelbot yflex">
                    <div>✖</div>
                  </div>
                </div>
                <div class="yendliubcerlefte">
                  <div class="yendliubcelbox"></div>
                  <div class="yendliiubcelbot yflex">
                    <div>✖</div>
                  </div>
                </div>
              </div>
              <div class="yendliubesi yflex">
                <div class="yendliubesiy">
                  <div class="yendliiubcelbot yflex">
                    <div>✖</div>
                  </div>
                </div>
                <div class="yendliubesie">
                  <div class="yendliiubcelbot yflex">
                    <div>✖</div>
                  </div>
                </div>
                <div class="yendliubesis">
                  <div class="yendliiubcelbot yflex">
                    <div>✖</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="yendliubottom yflex">
            <button @click="changetab(1)" :class="ytabeliu == 1 ? 'active' : ''"></button>
            <button @click="changetab(2)" :class="ytabeliu == 2 ? 'active' : ''"></button>
          </div>
        </div>
      </div>
      <div class="yendqi">
        <div class="yendqibox">
          <div class="yendqiti">
            <div class="yendqittop">Pop Ecosystem</div>
            <img src="../assets/647f2496296b2ca93c3574dc_popecosystem.png" alt="" />
          </div>
          <p>
            Pop is a unified platform that brings together diverse social
            communities, enabling seamless interaction and collaboration. By
            leveraging cutting-edge technologies like generative AI and multiple
            blockchains, Pop creates a cohesive environment where users can
            effortlessly connect and engage, fostering a vibrant and
            interconnected digital society.
          </p>
          <div class="yendqicon yflex">
            <div class="yendqicyi">
              <img class="yendqcyt" src="../assets/6474ab6aceb06282afaa0851_Frame1686561145.png" alt="" />
              <div class="yendqcybox">
                <p class="yeqcyti">Interoperable</p>
                <img class="yeqcylogo"
                  src="../assets/650ed317ad757160aa8b5e97_64871ed24839de5cafb31b80_Frame48095984-p-500.webp" alt="" />
                <p class="yeqcytxt">
                  Our platform serves as a multi-chain aggregator, remaining
                  agnostic to social protocols. Built to unify and connect
                  communities in one single place.
                </p>
                <img class="yeqcyimger" src="../assets/648b3bb21889aca439aaf1e6_ezgif.com-gif-maker-p-500.webp" alt="" />
              </div>
            </div>
            <div class="yendqicyi">
              <img class="yendqcyt" src="../assets/6474ab6aceb06282afaa0851_Frame1686561145.png" alt="" />
              <div class="yendqcybox">
                <p class="yeqcyti">Sustainable</p>
                <img class="yeqcylogo"
                  src="../assets/650ed0fdd22e2bc3f8141163_6474af6fdf70334b400db46a_Frame48095984.webp" alt="" />
                <p class="yeqcytxt">
                  The $PPT tokenomics model is designed to establish a
                  self-sustainable ecosystem, placing utmost importance on
                  principles of reuse, repair, and recycle.
                </p>
                <img class="yeqcyimger yeqcyimgee"
                  src="../assets/64f55bb508cf3526fd693ca1_6474ad994176cab6d24a8361_PPT1.webp" alt="" />
              </div>
            </div>
            <div class="yendqicyi">
              <img class="yendqcyt" src="../assets/6474ab6aceb06282afaa0851_Frame1686561145.png" alt="" />
              <div class="yendqcybox">
                <p class="yeqcyti">Composable</p>
                <img class="yeqcylogo" src="../assets/650ed2645050c9cddf866d80_6474b0e9bc4b35987ba4229c_03.webp" alt="" />
                <p class="yeqcytxt">
                  We are a modular open platform. At its core lies our Social
                  Protocol Engine, which is powered by AI technology and
                  engineered to launch builders and creators.
                </p>
                <img class="yeqcyimger yeqcyimges"
                  src="../assets/64f55bfdb0587817f8b7b19e_648c153739700a05b3560534_update.webp" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="yendwu">
        <div class="loop-marquee-logo-wrapper" style="margin-bottom: 1.5rem">
          <div class="loop-marquee-item-holder">
            <div class="loop-marquee_item-top">
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7c8b5a5a8b3649a19_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e798f9b2383268a514_ezgif.com-gif-maker%20(1).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68561c58fd45df5c4_ezgif.com-gif-maker%20(4).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7b1a2e59bd5857d37_ezgif.com-gif-maker%20(5).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68e3559214fd0074e_ezgif.com-gif-maker%20(8).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7906b0993370ed828_ezgif.com-gif-maker%20(6).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6c8b5a5a8b364968f_ezgif.com-gif-maker%20(10).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7adc7b303806a2b53_ezgif.com-gif-maker%20(11).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7998d40df521a1dbd_ezgif.com-gif-maker%20(7).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e64e1c7df81c7c7ed0_ezgif.com-gif-maker%20(9).webp"
                  alt="" class="loop-marquee-brand-logo" />
              </div>
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7c8b5a5a8b3649a19_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e798f9b2383268a514_ezgif.com-gif-maker%20(1).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68561c58fd45df5c4_ezgif.com-gif-maker%20(4).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7b1a2e59bd5857d37_ezgif.com-gif-maker%20(5).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68e3559214fd0074e_ezgif.com-gif-maker%20(8).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7906b0993370ed828_ezgif.com-gif-maker%20(6).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6c8b5a5a8b364968f_ezgif.com-gif-maker%20(10).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7adc7b303806a2b53_ezgif.com-gif-maker%20(11).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7998d40df521a1dbd_ezgif.com-gif-maker%20(7).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e64e1c7df81c7c7ed0_ezgif.com-gif-maker%20(9).webp"
                  alt="" class="loop-marquee-brand-logo" />
              </div>
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7c8b5a5a8b3649a19_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e798f9b2383268a514_ezgif.com-gif-maker%20(1).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68561c58fd45df5c4_ezgif.com-gif-maker%20(4).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7b1a2e59bd5857d37_ezgif.com-gif-maker%20(5).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68e3559214fd0074e_ezgif.com-gif-maker%20(8).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7906b0993370ed828_ezgif.com-gif-maker%20(6).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6c8b5a5a8b364968f_ezgif.com-gif-maker%20(10).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7adc7b303806a2b53_ezgif.com-gif-maker%20(11).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7998d40df521a1dbd_ezgif.com-gif-maker%20(7).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e64e1c7df81c7c7ed0_ezgif.com-gif-maker%20(9).webp"
                  alt="" class="loop-marquee-brand-logo" />
              </div>
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7c8b5a5a8b3649a19_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e798f9b2383268a514_ezgif.com-gif-maker%20(1).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6253925de3077fc31_ezgif.com-gif-maker%20(2).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 599.4652709960938px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e681c5b48c2bf70221_ezgif.com-gif-maker%20(3).webp       1123w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68561c58fd45df5c4_ezgif.com-gif-maker%20(4).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7b1a2e59bd5857d37_ezgif.com-gif-maker%20(5).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e68e3559214fd0074e_ezgif.com-gif-maker%20(8).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7906b0993370ed828_ezgif.com-gif-maker%20(6).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e6c8b5a5a8b364968f_ezgif.com-gif-maker%20(10).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7adc7b303806a2b53_ezgif.com-gif-maker%20(11).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e7998d40df521a1dbd_ezgif.com-gif-maker%20(7).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c360e64e1c7df81c7c7ed0_ezgif.com-gif-maker%20(9).webp"
                  alt="" class="loop-marquee-brand-logo" />
              </div>
            </div>
          </div>
        </div>
        <div class="loop-marquee-logo-wrapper">
          <div class="loop-marquee-item-holder">
            <div class="loop-marquee_item-bottom">
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c3674d8e3559214fd86bcb_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" />
              </div>
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c3674d8e3559214fd86bcb_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" />
              </div>
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c3674d8e3559214fd86bcb_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" />
              </div>
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c3674d8e3559214fd86bcb_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" />
              </div>
              <div class="loop-marquee_brand-logo">
                <img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9ea11fadfc1b4153e_ezgif.com-gif-maker%20(3).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9b1a2e59bd589dd35_ezgif.com-gif-maker.webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c3674d8e3559214fd86bcb_ezgif.com-gif-maker.webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1)-p-800.webp  800w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c9efe376c79c866f65_ezgif.com-gif-maker%20(1).webp       2360w
                  " class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c364c94362049eefbc4a12_ezgif.com-gif-maker%20(2).webp"
                  alt="" class="loop-marquee-brand-logo" /><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp"
                  alt="" sizes="(max-width: 767px) 100vw, 596.4583129882812px" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5)-p-500.webp  500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64c366a6e743d0c2d699ade9_ezgif.com-gif-maker%20(5).webp       2360w
                  " class="loop-marquee-brand-logo" />
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="yendsi">
        <div class="yendsibox">
          <img src="../assets/649d66ee6c76fa917a1e8b18_member.svg" alt="" />
          <div>Pop Team Member</div>
        </div>
        <div class="yendsibcon yflex">
          <div :class="lubot == 1
              ? 'yendsibcyi'
              : lubot == 2
                ? 'yendsibcfyi'
                : lubot == 3
                  ? 'yendsibcfer'
                  : lubot == 4
                    ? 'yendsibcfer'
                    : lubot == 5
                      ? 'yendsibcfer'
                      : 'yendsibcfer'
            "></div>
          <div :class="lubot == 1
              ? 'yendsibcer'
              : lubot == 2
                ? 'yendsibcyi'
                : lubot == 3
                  ? 'yendsibcfyi'
                  : lubot == 4
                    ? 'yendsibcfyi'
                    : lubot == 5
                      ? 'yendsibcfyi'
                      : 'yendsibcfyi'
            "></div>
          <div :class="lubot == 1
              ? 'yendsibcsan show'
              : lubot == 2
                ? 'yendsibcer'
                : lubot == 3
                  ? 'yendsibcyi'
                  : lubot == 4
                    ? 'yendsibcfyi'
                    : lubot == 5
                      ? 'yendsibcfer'
                      : 'yendsibcsan'
            ">
            <img class="yendsibcimg" src="../assets/649d4c6f3f440aade32f0683_MichaelShen-6.png" alt="" />
            <div class="yendsibctxt">
              <div class="yendsitxty">Matt Gao</div>
              <div class="yendsitxte">Lead Backend Developer</div>
              <p>
                Matt earned his MSc and BSc in Computer Science from Ohio
                University. As a professional in the blockchain and Web3 space
                since 2018, Matt holds extensive knowledge and hands-on
                experience in the industry. Matt held senior roles as an API
                developer in the United States. He is also well-versed when it
                comes to blockchain-oriented and R&D-specific projects. As a
                member of the ISO TC307 International Standards Committee, he
                has worked on multiple Ledger Technology Projects.
              </p>
            </div>
          </div>
          <div :class="lubot == 1
              ? 'yendsibcsi'
              : lubot == 2
                ? 'yendsibcsan show'
                : lubot == 3
                  ? 'yendsibcer'
                  : lubot == 4
                    ? 'yendsibcyi'
                    : lubot == 5
                      ? 'yendsibcfyi'
                      : 'yendsibcer'
            ">
            <img class="yendsibcimg" src="../assets/64a2cc1f08e32f68f57fb0ec_Poornimaajkumar.png" alt="" />
            <div class="yendsibctxt">
              <div class="yendsitxty">Poornima Rajkumar</div>
              <div class="yendsitxte">Content Operations and Moderation</div>
              <p>
                Over the past 5 years, Poornima has gained a wealth of
                experience in various aspects of digital marketing and business
                management. She has extensive knowledge of cryptocurrency,
                including Bitcoin algorithm systems and blockchain technologies.
                Prior to joining Pop, Poornima had spent almost 3 years at
                Bytedance Tiktok for the same position as Content Moderator. At
                Pop, her role covers checking the quality and safety audit work
                of pictures, texts and videos, handling internal and external
                feedback content, improve product safety, and output
                high-quality content for the platform.
              </p>
            </div>
          </div>
          <div :class="lubot == 3
              ? 'yendsibcsan show'
              : lubot == 2
                ? 'yendsibcsi'
                : lubot == 1
                  ? 'yendsibcwu'
                  : lubot == 4
                    ? 'yendsibcer'
                    : lubot == 5
                      ? 'yendsibcyi'
                      : 'yendsibcsan show'
            ">
            <img class="yendsibcimg" src="../assets/649d4c70f5c7aa41f5e68164_MichaelShen.png" alt="" />
            <div class="yendsibctxt">
              <div class="yendsitxty">Michael Shen</div>
              <div class="yendsitxte">CEO</div>
              <p>
                As CEO and Cofounder of Pop Labs, Michael is a dynamic innovator
                in the world of emerging technologies. With more than 8 years of
                experience in the blockchain and crypto industry, Michael is
                committed to building the next generation social gateway to
                accelerate the Web3 social revolution. Aimed at transforming the
                multi-billion dollar creator economy, POP will democratize
                content ownership and user privacy. The platform will play a
                fundamental role in the future of creativity, bridging the gap
                between traditional social media and the Web3 shared social
                experience as the ramp to bring the next one billion users to
                Web3.
              </p>
            </div>
          </div>
          <div :class="lubot == 1
              ? 'yendsibcliu'
              : lubot == 2
                ? 'yendsibcyi'
                : lubot == 3
                  ? 'yendsibcsi'
                  : lubot == 4
                    ? 'yendsibcsan show'
                    : lubot == 5
                      ? 'yendsibcer'
                      : 'yendsibcsi'
            ">
            <img class="yendsibcimg" src="../assets/64d1fda2445c8af250c65de1_MichaelShen4.png" alt="" />
            <div class="yendsibctxt">
              <div class="yendsitxty">Dr. Joey Chou</div>
              <div class="yendsitxte">Chief Product Officer</div>
              <p>
                Dr. Joey is the CPO at Pop Labs. With a doctoral degree from MIT
                and prior experience at Apple, he brings a wealth of knowledge
                and expertise in product design and innovation. In his role as
                CPO, he exercises a wide range of responsibilities from
                formulating product strategy, overseeing product development,
                conducting market research, coordinating with various company
                departments, leading the product team, to assuring product
                quality and performance.
              </p>
            </div>
          </div>
          <div :class="lubot == 1
              ? 'yendsibcqi'
              : lubot == 2
                ? 'yendsibcliu'
                : lubot == 3
                  ? 'yendsibcwu'
                  : lubot == 4
                    ? 'yendsibcsi'
                    : lubot == 5
                      ? 'yendsibcsan show'
                      : 'yendsibcwu'
            ">
            <img class="yendsibcimg" src="../assets/649d4c6f8b2660e3b5901b43_MichaelShen-3.png" alt="" />
            <div class="yendsibctxt">
              <div class="yendsitxty">Goncalo Vicente</div>
              <div class="yendsitxte">Product Lead</div>
              <p>
                Goncalo Vicente is an experienced product-centric founder and
                CEO of a web3 start-up developing an open protocol for digital
                assets inheritance, covering cryptocurrencies, NFTs and DeFi,
                taking it from ground zero to a successful live launch. Vincent
                has honed his skills for over 15 years at Accenture, a global
                consultancy firm, where he contributed to delivering numerous
                digital products and implementing large-scale solutions within
                the Fintech ecosystem.
              </p>
            </div>
          </div>
          <div :class="lubot == 1
              ? 'yendsibcliu'
              : lubot == 2
                ? 'yendsibcliu'
                : lubot == 3
                  ? 'yendsibcliu'
                  : lubot == 4
                    ? 'yendsibcwu'
                    : lubot == 5
                      ? 'yendsibcsi'
                      : 'yendsibcliu'
            "></div>
          <div :class="lubot == 1
              ? 'yendsibcqi'
              : lubot == 2
                ? 'yendsibcqi'
                : lubot == 3
                  ? 'yendsibcqi'
                  : lubot == 4
                    ? 'yendsibcqi'
                    : lubot == 5
                      ? 'yendsibcwu'
                      : 'yendsibcqi'
            "></div>
          <div @click="hou()" class="zuojt">
            <img src="../assets/649275f3ba32e319dda3d9ab_expand_more_FILL0_wght400_GRAD0_opsz48 1.svg" alt="" />
          </div>
          <div @click="qian()" class="youjt">
            <img src="../assets/649275f3ba32e319dda3d9ab_expand_more_FILL0_wght400_GRAD0_opsz48 1.svg" alt="" />
          </div>
          <div class="yendsian">
            <a class="yflex" href="https://www.popsocial.io/career">
              Join Our Team
            </a>
          </div>
        </div>
      </div>
      <div class="yendsan">
        <div class="yendsanbox">
          <div class="yendsbti">
            <div class="yendsbttxt">Pop FAQ</div>
            <img src="../assets/647f24951d43f206988927c0_UserDiversity.png" alt="" />
          </div>
          <div class="yendsbcon">
            <div :class="isxiapf == 1 ? 'yesbcybox yesbcyboxhei' : 'yesbcybox'">
              <div class="yendsbcyi yflex">
                <div class="yendsbcfon">What is Pop?</div>
                <div @click="showhei(1)" :class="isxiapf == 1 ? 'yendsbcycha tendsbcyj' : 'yendsbcycha'
                  ">
                  <div></div>
                  <div></div>
                </div>
              </div>
              <p>
                Pop is the ultimate social gateway to Web3. Experience a
                decentralized app that empowers content creators and consumers
                to gain value in return for the value they bring to our
                platform. Own your original content to leverage creator economy
                and claim social recognition.
              </p>
            </div>
            <div :class="isxiapfy == 1 ? 'yesbcybox yesbcyboxhei' : 'yesbcybox'">
              <div class="yendsbcyi yflex">
                <div class="yendsbcfon">How can I download Pop?</div>
                <div @click="showheiy(1)" :class="isxiapfy == 1 ? 'yendsbcycha tendsbcyj' : 'yendsbcycha'
                  ">
                  <div></div>
                  <div></div>
                </div>
              </div>
              <p>
                The Pop social app can be downloaded from the Apple App Store or
                the Google Play Store. Presently, the Pop social app is in its
                beta testing phase. It has multi-chain functionality with
                activation on BNB and Polygon chains.
              </p>
            </div>
            <div :class="isxiapfe == 1 ? 'yesbcybox yesbcyboxhei' : 'yesbcybox'">
              <div class="yendsbcyi yflex">
                <div class="yendsbcfon yendsbshou">
                  How can I create an account on the Pop social app?
                </div>
                <div @click="showheie(1)" :class="isxiapfe == 1 ? 'yendsbcycha tendsbcyj' : 'yendsbcycha'
                  ">
                  <div></div>
                  <div></div>
                </div>
              </div>
              <p>
                You can create an account on the Pop via an email address or a
                phone number. Simply verify by clicking an emailed link or
                typing in the OTP your phone receives. You can also connect with
                your crypto wallet.
              </p>
            </div>
            <div :class="isxiapfs == 1 ? 'yesbcybox yesbcyboxhei' : 'yesbcybox'">
              <div class="yendsbcyi yflex">
                <div class="yendsbcfon">How can I get Verified on Pop?</div>
                <div @click="showheis(1)" :class="isxiapfs == 1 ? 'yendsbcycha tendsbcyj' : 'yendsbcycha'
                  ">
                  <div></div>
                  <div></div>
                </div>
              </div>
              <p>
                Pop users can get verifies as users, creators, or organizations.
                This is to build trust and carry your reputation and
                accomplishments from traditional online social spaces into the
                Pop Social Ecosystem. Verified accounts get more visibility and
                can earn PPT faster in a shorter time.
              </p>
            </div>
            <div :class="isxiapfsi == 1 ? 'yesbcybox yesbcyboxhei' : 'yesbcybox'">
              <div class="yendsbcyi yflex">
                <div class="yendsbcfon">What is PPT?</div>
                <div @click="showheisi(1)" :class="isxiapfsi == 1 ? 'yendsbcycha tendsbcyj' : 'yendsbcycha'
                  ">
                  <div></div>
                  <div></div>
                </div>
              </div>
              <p>
                The Pop social ecosystem consists of one native token, the Popoo
                Token (PPT). You can make in-app purchases with PPT making it
                the token used to process transactions in the Pop social
                ecosystem. You can also gain platform governance power by
                holding PPT tokens.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="yender">
        <div class="yendercon">
          <div class="yenderti">
            <img src="../assets/647f2496c3a1da484587a21d_lastpart.png" alt="" />
            <div class="yendeh">Your Web3 Journey Starts Here</div>
            <p>
              Dive right into the ultimate social gateway to Web3 and discovery
              your most authentic digital <br />
              identity on a secure and decentralized platform.
            </p>
            <div class="yenderans">
              <a href="https://play.google.com/store/apps/details?id=com.popooapp" target="_blank">
                <img src="../assets/650952450b8b22496ac101e5_64808fcf4fc4373660c38d91_Group48095998.webp" alt="" /></a>
              <a href="https://apps.apple.com/us/app/pop-the-social-gateway-to-web3/id1668093198" target="_blank">
                <img src="../assets/65095245410a9c9a7a5f818c_648091995469eb87c1bc4919_UPDATE.webp" alt="" /></a>
            </div>
          </div>
        </div>
        <div class="yendertbg"></div>
        <div class="section-hero">
          <img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb7e2959f80c7916a00_650972f8f59cdd4885f57eb2_stripe_01.webp"
            loading="eager" alt="" class="top01" style="
              will-change: transform;
              transform: translate3d(0px, 2.0371%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb71fd3a8d7814fdf09_6509752178d1dcb1e8455550_20230919-161357.webp"
            loading="eager" sizes="100vw" srcset="
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb71fd3a8d7814fdf09_6509752178d1dcb1e8455550_20230919-161357-p-500.webp   500w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb71fd3a8d7814fdf09_6509752178d1dcb1e8455550_20230919-161357-p-800.webp   800w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb71fd3a8d7814fdf09_6509752178d1dcb1e8455550_20230919-161357-p-1080.webp 1080w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb71fd3a8d7814fdf09_6509752178d1dcb1e8455550_20230919-161357-p-1600.webp 1600w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb71fd3a8d7814fdf09_6509752178d1dcb1e8455550_20230919-161357.webp        1920w
            " alt="" class="top02" style="
              will-change: transform;
              transform: translate3d(15.9258%, 0px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb76f9bccd7ffb6bd7e_650972f86d1956f0940b4e1b_stripe_04.webp"
            loading="eager" alt="" class="top03" style="
              will-change: transform;
              transform: translate3d(0px, -6.1113%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb76f1dd5bd4100431b_650972fa5d49145220fd0303_elements_010.webp"
            loading="eager" alt="" class="top04" style="
              will-change: transform;
              transform: translate3d(0px, -8.1484%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb756c9994ce076521a_650972f83f321d0d956c3275_stripe_03.webp"
            loading="eager" alt="" class="top05" style="
              will-change: transform;
              transform: translate3d(0px, 10.1855%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefbb0d02143555a3e47e_650972f8d061577c7f46ed0b_stripe_02.webp"
            loading="eager" alt="" class="top06" style="
              will-change: transform;
              transform: translate3d(0px, 8.1484%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb70a0a8f7485597cbb_650972f8ffea4dbff809abb8_small_elements.webp"
            loading="eager" alt="" class="top_07" style="
              will-change: transform;
              transform: translate3d(0px, -6.1113%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603a873dfb6f2d0b51fc_cloud_03.webp"
            loading="eager" alt="" class="cloud01" style="
              will-change: transform;
              transform: translate3d(0px, -9.16695px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603be0d80c3d17e05a5d_cloud_01.webp"
            loading="eager" alt="" class="cloud02" style="
              will-change: transform;
              transform: translate3d(0px, -7.12985%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603b4e145c2a9a28a064_cloud_02.webp"
            loading="eager" alt="" class="cloud03" style="
              will-change: transform;
              transform: translate3d(0px, -8.1484%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603b3b65549f98738cd5_cloud_04.webp"
            loading="eager" alt="" class="cloud04" style="
              will-change: transform;
              transform: translate3d(-30.5565px, 0px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb771fa5d496eaba350_650972f85d49145220fd0161_elements_13.webp"
            loading="eager" alt="" class="cloud05" style="
              will-change: transform;
              transform: translate3d(0px, 65.1656%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603a63fe4ef34e25e508_elements_01%20(1).webp"
            loading="eager" alt="" class="cloud06" /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603af44af54f59f84234_elements_03.webp"
            loading="eager" alt="" class="cloud07" /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefbba3f8722dc59fa5d7_650972f8f54c3602dcfc2fa0_elements_013.webp"
            loading="eager" alt="" class="cloud08" style="
              will-change: transform;
              transform: translate3d(-24.4452px, 0px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefbbc505e05d02dbeffa_650972f8a4a9511c550c3191_elements_07.webp"
            loading="eager" alt="" class="cloud09" style="
              will-change: transform;
              transform: translate3d(0px, 139.351px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603b1d15818db3e2ff35_elements_04.webp"
            loading="eager" alt="" class="cloud_10" /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6509603a103084de89bc93f1_elements_02.webp"
            loading="eager" alt="" class="cloud_11" style="
              will-change: transform;
              transform: translate3d(50.1663px, 0px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650972f938044b7207444002_stripe_05.png"
            loading="eager" alt="" class="bottom01" style="
              will-change: transform;
              transform: translate3d(0px, 6.1113%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefbb9556522ebb5e3d2f_650972fa31111e74b1b4f227_elements_012.webp"
            loading="eager" alt="" class="bottom02" style="
              will-change: transform;
              transform: translate3d(0px, 79.629px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb73aebacb206a4758e_650972fa105ed70723403212_elements_09.webp"
            loading="eager" alt="" class="bottom03" /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefbb6ab115cb9226b0e3_650972fab382b018406c2f9d_elements_08.webp"
            loading="eager" alt="" class="bottom04" style="
              will-change: transform;
              transform: translate3d(79.629%, 0px, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb7100e1af14bc3b383_650972f80e5603d47b3219bc_elements_06.webp"
            loading="eager" alt="" class="bottom05" style="
              will-change: transform;
              transform: translate3d(0px, -5.87015%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb7c3f21b90b4d2c0eb_650972f878d1dcb1e842de56_elements_05.webp"
            loading="lazy" alt="" class="bottom06" style="
              will-change: transform;
              transform: translate3d(0px, -6.1113%, 0px) scale3d(1, 1, 1)
                rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
              transform-style: preserve-3d;
            " /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/650aefb72bb795eedb82434b_650972f87560cbe250768101_elements_014.webp"
            loading="eager" alt="" class="bottom07" /><img
            src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/65093b6295222f87328d0cef_ezgif.com-gif-maker.webp"
            loading="eager" sizes="100vw" srcset="
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/65093b6295222f87328d0cef_ezgif.com-gif-maker-p-500.webp   500w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/65093b6295222f87328d0cef_ezgif.com-gif-maker-p-800.webp   800w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/65093b6295222f87328d0cef_ezgif.com-gif-maker-p-1080.webp 1080w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/65093b6295222f87328d0cef_ezgif.com-gif-maker-p-1600.webp 1600w,
              https://global-uploads.webflow.com/634560205fda56fb55a31b0d/65093b6295222f87328d0cef_ezgif.com-gif-maker.webp        1920w
            " alt="" class="bg-hero" />
        </div>
      </div>
      <div class="yfoot">
        <div class="yfootbox yflex">
          <div class="yfootbyi">
            <a href="/">
              <img src="../assets/1.png" alt="" />
            </a>
            <p>
              Pop Social is the next generation social gateway to Web3. Our
              <br />
              platform will bridge the gap between traditional social media
              <br />
              and the Web3 shared social experience.
            </p>
            <div class="yfootbs yflex">
              <a href="https://twitter.com/popapp_official" target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6437b8022c20baa8accb78b6_twitter.png"
                  loading="lazy" width="18" alt="" /></a><a href="https://www.instagram.com/popsocial_official/"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64396b7ccbf8fc5f39df386f_6437b91ae8478a04e33a162d_insta.png"
                  loading="lazy" width="18" sizes="(max-width: 991px) 100vw, (max-width: 1279px) 17.99479103088379px, 1vw"
                  alt="" srcset="
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64396b7ccbf8fc5f39df386f_6437b91ae8478a04e33a162d_insta-p-500.png 500w,
                    https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64396b7ccbf8fc5f39df386f_6437b91ae8478a04e33a162d_insta.png       501w
                  " class="image-60" /></a><a href="https://t.me/PopSocialCommunity" target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/635b7c3e33b4b9cb6e338533_Telegram.png"
                  loading="lazy" width="18" alt="" class="image-60" /></a><a href="https://discord.gg/popsocial"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/635b7c3e33b4b93b34338532_Discord.png"
                  loading="lazy" width="18" alt="" /></a><a href="https://www.youtube.com/@popsocial_official"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/648084e43e871faa097f7112_64396b7c3b73807f392776e7_6437bc18c0a2d72fef7c6f88_reddit.png"
                  loading="lazy" width="18" alt="" /></a><a href="https://medium.com/@popsocial_official"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6399d1a4541ccc005287f2ab_medium.png"
                  loading="lazy" width="18" alt="" /></a><a
                href="https://www.facebook.com/people/Pop-Social/100095013490929/" target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6437b545b792016affba45c5_Facebook.png"
                  loading="lazy" width="18" alt="" /></a><a href="https://www.linkedin.com/company/pop-labs-official/"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6437b6110485b3c975a84739_linkin.png"
                  loading="lazy" width="18" alt="" /></a><a href="https://www.reddit.com/r/pop_social/"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/64396b7c3b73807f392776e7_6437bc18c0a2d72fef7c6f88_reddit.png"
                  loading="lazy" width="18" alt="" /></a><a href="https://www.binance.com/en/feed/profile/556522034"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6437bd923fbb4743dceda268_binance.png"
                  loading="lazy" width="18" alt="" /></a><a href="https://coinmarketcap.com/community/profile/PopSocial/"
                target="_blank"><img
                  src="https://global-uploads.webflow.com/634560205fda56fb55a31b0d/6437bee036329b0c25abf74b_coin_logo.png"
                  loading="lazy" width="18" alt="" /></a>
            </div>
          </div>
          <div class="yfootber">
            <div class="yfbeti">Pages</div>
            <div class="yfbeas">
              <a href="/">Home</a>
              <a href="/creator">Creator</a>
              <a href="/blog">Blog</a>
            </div>
          </div>
          <div class="yfootbsan">
            <div class="yfbeti">Resources</div>
            <div class="yfbeas">
              <a href="/terms-conditions" target="_blank">Terms & Conditions</a>
              <a href="/disclaimer-and-user-warranties" target="_blank">Disclaimer & user warranties</a>
              <a href="/media-resources" target="_blank">Media Resources</a>
              <a href="/help-center" target="_blank">Help Center</a>
              <a href="/team" target="_blank">Team</a>
              <a href="/career" target="_blank">Career</a>
            </div>
          </div>
        </div>
        <div class="yfootend yflex">
          <a href="/team" class="update">Copyright © Pop Social | Designed by Pop Branding Team</a>
          <a href="/terms-conditions" class="update">Privacy / Terms and Conditions</a>
        </div>
      </div>

    </div>
  </div>
</template> 

<script>
import { Button } from 'element-ui';

export default {
  components: {
    'el-button': Button
  },
  name: 'MyPage',
  data() {
    return {
      showOverlay: false,
      showNewImage: false,
      isHeadVisible: false,
      activeIndex: 0,
      activeIndexs: 0,
      isxiapf: 0,
      isxiapfy: 0,
      isxiapfe: 0,
      isxiapfs: 0,
      isxiapfsi: 0,
      lubot: 3,
      ytabeliu: 1,
      dataList: [
        { id: 1, src: require("@/assets/92.webp"), txt: 'Web3 Unique Identity', txts: 'A decentralized and secure digital identity that gives you complete control over your personal data and interactions online.' },
        { id: 2, src: require("@/assets/93.webp"), txt: 'Pop Collectibles', txts: 'Claim, own, trade, and connect with exclusive digitalassets. Elevate your passion for art, music, culturegaming, and more with our Pop ecosystem.' },
        { id: 3, src: require("@/assets/94.webp"), txt: 'Pop Community', txts: 'Join a lively community of creative trendsetters and express yourself.' },
        { id: 4, src: require("@/assets/95.webp"), txt: 'Engage Earn Repeat', txts: 'Unlock earning potential with Pop. Be part of acommunity that values your contributions, start todayand get rewarded.' },
        { id: 5, src: require("@/assets/96.webp"), txt: 'Pop Collectibles', txts: 'Immerse yourself in a world of engaging videos, fromentertaining clips to inspiring stories. Embark on anexciting journey of media discovery and connection.' },
      ],
    };
  },
  methods: {
    add() {
      main()
    },
    closeOverlay() {
      this.showOverlay = false;
    },
    showHead() {
      this.isHeadVisible = true;
    },
    hideHead() {
      this.isHeadVisible = false;
    },
    changetab(str) {
      this.ytabeliu = str;
    },
    showhei(str) {
      if (this.isxiapf == str) {
        this.isxiapf = 0;
      } else {
        this.isxiapf = 1;
      }
    },
    showheiy(str) {
      if (this.isxiapfy == str) {
        this.isxiapfy = 0;
      } else {
        this.isxiapfy = 1;
      }
    },
    showheie(str) {
      if (this.isxiapfe == str) {
        this.isxiapfe = 0;
      } else {
        this.isxiapfe = 1;
      }
    },
    showheis(str) {
      if (this.isxiapfs == str) {
        this.isxiapfs = 0;
      } else {
        this.isxiapfs = 1;
      }
    },
    showheisi(str) {
      if (this.isxiapfsi == str) {
        this.isxiapfsi = 0;
      } else {
        this.isxiapfsi = 1;
      }
    },
    qian() {
      if (0 <= this.lubot && this.lubot <= 4) {
        this.lubot = this.lubot + 1;
        console.log(this.lubot);
      }
    },
    hou() {
      if (1 < this.lubot && this.lubot <= 5) {
        this.lubot = this.lubot - 1;
        console.log(this.lubot);
      }
    },
  },
  mounted() {
    setTimeout(() => {
      this.showNewImage = true;
    }, 2000);
    this.showOverlay = true;
  },

};
</script>

<style scoped>
.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 200px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n+1) {
  background-color: #d3dce6;
}


@font-face {
  font-family: one;
  src: url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/64a2d7c808e32f68f58f6dc9_fa-brands-400.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: two;
  src: url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/64af9ca854fb51d9e85b6e84_Social%20Icons%20Pro%20Set%201%20-%20Rounded.woff2') format('woff2'), url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/64af9ca854fb51d9e85b6e84_Social%20Icons%20Pro%20Set%201%20-%20Rounded.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: three;
  src: url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/649e9b59c8cc95d7d76e4e68_WebsymbolsRegular-qyo0.woff') format('woff');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: four;
  src: url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/634560205fda56ad45a31b82_ClarityCity-Regular.otf') format('opentype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: five;
  src: url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/634560205fda569735a31b83_ClarityCity-Medium.otf') format('opentype');
  font-weight: 500;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: six;
  src: url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/634560205fda5665efa31b84_ClarityCity-Bold.otf') format('opentype');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: even;
  src: url('https://uploads-ssl.webflow.com/634560205fda56fb55a31b0d/642585437b99ea81b50a2fb0_Righteous.otf') format('opentype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: ten;
  src: url('../assets/ten.ttf') format('opentype');
  font-weight: 900;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: thiy;
  src: url('../assets/1.ttf') format('opentype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: thiys;
  src: url('../assets/2.ttf') format('opentype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: thiyst;
  src: url('../assets/3.ttf') format('opentype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

.yflex {
  display: flex;
}

.overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;

  background-color: rgba(0, 0, 0, 0.5);
  z-index: 1;
  display: none
}

.overlay.active {
  display: block
}

.tank {
  max-width: 600px;
  cursor: auto;
  background-color: #222327;
  border-radius: 24px;
  margin: 20% auto;
  padding: 32px 40px;
  position: relative;
}

.tank_1 {
  display: flex;
  text-align: center;
  color: white;
  align-items: flex-start;
  justify-content: center;
}

.tank_1>h1 {
  max-width: 400px;
  text-align: center;
  font-size: 32px;
  line-height: 110%;
  font-family: 900;
}

.tank_2 {
  color: #00f59b;
  text-transform: uppercase;
  background-color: #5a4cf3;
  border-radius: 16px;
  margin-left: auto;
  margin-right: auto;
  padding: 16px 22px;
  font-family: five;
  font-size: 22px;
  font-weight: 700;
  line-height: 110%;
  text-align: center;
  margin-top: 1rem;
  cursor: pointer;
}

.clone {
  width: 20px;
  height: 20px;
}

.tank_3 {
  width: 100%;
  display: flex;
  justify-content: flex-end;
}

.box {

  width: 100%;
  /* height: ; */
  background-color: #000;
}

.head {
  width: 80%;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.head_1 {
  width: 45rem;
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-around;
  cursor: pointer;
}

.head_2 {
  height: 100px;
}

.head_3 {
  animation: moveImage 2s linear infinite;
}

@keyframes moveImage {
  0% {
    transform: translateX(-100%);
  }

  100% {
    transform: translateX(0);
  }
}

.old-image {
  width: 150px;
  height: 50px;
  animation: moveImage 2s linear forwards;
}

.new-image {
  width: 150px;
  height: 50px;
  opacity: 1;
  transition: opacity 0.5s;
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}

.head_4 {
  width: 150px;
  height: 40px;
}

.head_5 {
  background-color: #5a4cf3;
  color: white;
  display: flex;
  padding: 1rem;
  border-radius: 30px;
  font-weight: 600;
}

.head_5>img {
  width: 20px;
  height: 20px;
  margin-right: 0.5rem;
}

.head_5>a {
  color: white;
}

.head_6 {
  display: flex;
}

.head_12>img {
  width: 25px;
  height: 25px;
  transform: translate3d(0px, 0px, 0px) scale3d(1, 1, 1) rotateX(0deg) rotateY(0deg) rotateZ(0deg) skew(0deg, 0deg);
  transform-style: preserve-3d;
}

.head_7 {
  position: relative;
}

.head_8 {
  width: 75%;
  /* height: 6rem; */
  background-color: #000;
  position: absolute;
  top: 13%;
  left: 11%;
  display: none;
  border-radius: 20px;
}

.head_12:hover .head_8 {
  display: block;
}

.head_9 {
  width: 80%;
  display: flex;
  padding: 1rem 2rem 2rem 1rem;
  justify-content: space-between;
}

.head_10 {
  width: 80%;
  display: flex;
  justify-content: space-between;
  margin-bottom: 3rem;
}

.head_11 {
  display: flex;
  margin: 1rem 0 1rem 2rem;
  font-size: 20px;
}

.head_11>img {
  width: 30px;
  height: 30px;
}

.zmd {
  width: 100%;
  height: 3rem;
  background-color: #5a4cf3;
}

.zmd_1 {
  display: flex;
  justify-content: center;
}

.center {
  width: 100%;
}

.cen {
  max-width: 1200px;
  width: 70%;
  color: white;
  margin: 0 auto;
}

.tab_1 {
  width: 100%;
  margin-top: 4rem;

}

.tab_2 {
  width: 100%;
  display: flex;
}

.tab2_1 {
  width: 60%;
  display: flex;
  flex-direction: column;
}

.tab2_h2 {
  max-width: 700px;
  text-transform: uppercase;
  margin-top: 0;
  margin-bottom: 20px;
  font-family: ten;
  font-size: 40px;
  line-height: 40px;
  /* font-weight: 900; */
}

.tab2_1>p {
  color: rgba(255, 255, 255, .8);
  font-family: thiy;
  margin-bottom: 2rem;
}

.tab2_1_1 {
  display: flex;
  margin-bottom: 3rem;
}

.tab2_1_2 {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 1.5rem;
  margin-right: 1rem;
}

.tab2_1_4 {
  height: 50px;
  margin: 1rem 0 1rem 0;
}

.tab2_1_5 {
  display: flex;
  background-color: #5a4cf3;
  padding: 1rem;
  border-radius: 15px;
  align-items: center;
}

.tab2_1_5>p {
  font-size: 14px;
  color: rgba(255, 255, 255, 0.8);
}

.tab2_1_6 {
  margin-left: 4rem;
  background-color: #00f59b;
  padding: 0.5rem 3rem 0.5rem 3rem;
  border-radius: 30px;
  color: #000;
  font-weight: 400;
}

.tab2_1_7 {
  display: flex;
  align-items: center;
}

.tab2_1_7>h2 {
  margin: 0 0.5rem 0 0.5rem;
}

.tab2_1_8 {
  display: flex;
  border: 2px #5a4cf3 solid;
  padding: 0.75rem;
  border-radius: 15px;
  align-items: center;
  margin-top: 1.5rem;
}

.tab2_1_9 {
  display: flex;
  align-items: center;
}

.tab2_1_9>p {
  font-size: 14px;
  color: rgba(255, 255, 255, 0.8);
}

.tab2_1_9>h2 {
  margin: 0 0.5rem 0 0.5rem;
}

.tab2_1_10 {
  margin-left: 3rem;
  border: 2px #5a4cf3 solid;
  padding: 0.5rem 3rem 0.5rem 3rem;
  border-radius: 30px;
  color: white;
  font-weight: 400;
}

.tab2_1_11 {
  margin-top: 1rem;
  padding: 2.5rem 0 2.5rem 0;
  background-image: url('../assets/14.webp');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  display: flex;
  position: relative;
  top: 0;
}

.tab2_1_12 {
  font-family: thiys;
  font-weight: 700;
  padding: 1rem;
  font-size: 18px;
}

.tab2_1_12>p:hover {
  color: #929292;
  ;
}

.tab2_1_13 {
  width: 234px;
  height: 188px;
  position: absolute;
  top: -7%;
  left: 63%;
}

.tab2_1_14 {
  max-width: 680px;
  width: 94%;
  background-color: #141414;
  display: flex;
  border-radius: 15px;
  align-items: center;
}

.tab2_1_15 {
  padding: 1rem 0 0 1rem;
  width: 60%;
  display: flex;
  flex-direction: column;
  overflow: hidden;
}

.tab2_1_15>p {
  color: #929292;
  font-size: 16px;
  margin: 0.8rem 0 0.5rem 0;
}

.tab2_1_16 {
  width: 12rem;
  display: flex;
  text-align: center;
  color: #ffca43;
  margin: 1rem 0 1rem 0;
  border: 2px #ffca43 solid;
  padding: 0.5rem 0 0.5rem 0;
  justify-content: center;
  border-radius: 30px;
}

.tab2_1_17 {
  width: 40%;
  display: flex;
  justify-content: flex-end;
}

.tab2_1_17>video {
  width: 60%;
  position: relative;
  top: -1%;
  border-radius: 15px;
}

.tab_3 {
  width: 40%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}

.tab3_1 {
  width: 75%;
  text-align: center;
  margin-top: 2rem;
  background-color: #141414;
  height: 34rem;
  border-bottom-left-radius: 25px;
  border-bottom-right-radius: 25px;
}

.tab3_2 {
  background-color: #5a4cf3;
  padding: 0.75rem 0 0.75rem 0;
  color: #00f59b;
  border-top-left-radius: 25px;
  border-top-right-radius: 25px;
  font-family: thiy;
  font-size: 20px;
}

.tab3_3 {
  margin-top: 2rem;
  color: #00f59b;
  font-family: ten;
  font-size: 36px;
  line-height: 36px;
  margin-bottom: 2rem;
}

.tab3_4 {
  color: #929292;
}

.tab3_5 {
  font-family: ten;
  font-size: 30px;
  font-weight: 700;
}

.tab3_6 {
  width: 90%;
  background-color: #1f1f1f;
  margin: 2rem auto;
  border-radius: 15px;
  display: flex;
  justify-content: center;
  position: relative;
}

.tab3_6>p {
  width: 65%;
  font-size: 12px;
  text-align: left;
  font-family: thiys;
  padding: 1rem 0 1rem 0;
}

.animated {
  animation: moveUpDown 1s infinite alternate;
  /* 添加动画效果 */
}

@keyframes moveUpDown {
  0% {
    transform: translateY(0);
  }

  100% {
    transform: translateY(-20px);
  }
}

.tab3_7 {
  position: absolute;
  left: -4%;
}

.tab3_8 {
  position: absolute;
  top: 53%;
  left: 90%;
}

.tab3_9 {
  width: 90%;
  margin: 0 auto;
}

.tab3_9 {
  border-top: 1px rgba(255, 255, 255, 0.2) solid;
  display: flex;
  justify-content: center;
  width: 80%;
  align-items: center;
  justify-content: space-around;
  padding: 1rem 0 1rem 0;
}

.tab3_9>p {
  color: #5a4cf3;
  ;
}

.tab3_9>p:hover {
  opacity: 0.5;
}

.tab3_9>img {
  height: 3rem;
}

.tab4_1 {
  width: 80%;
  color: white;
}

.tab4_2 {
  margin-top: 2rem;
  display: flex;
  justify-content: space-around
}

.tab4_3 {
  display: flex;
}

.tab4_3>p>a {
  display: flex;
  color: rgba(255, 254, 254, 0.7);
  text-decoration: underline;
}

.tab4_3>p>a:hover {
  color: #5a4cf3;
}

.tab4_4 {
  width: 80%;
  /* background-color: white; */
  margin: 0 auto;
  margin-top: 2rem;
}

.tab4_5 {
  display: flex;
  justify-content: center
}

.tab4_5>a {
  width: 40px;
  height: 40px;
  border: 1px white solid;
  border-radius: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 0.7rem;

}

.tab4_5>a>img {
  width: 20px;
  height: 20px;

}

.xuan {
  width: 100%;
  display: flex;
  justify-content: center;
}

.xuan>p:hover {
  background-color: #5a4cf3;
}

.xuan>p {
  width: 7rem;
  background-color: #929292;
  border-radius: 5px;
  height: 1rem;
  margin-right: 3rem;
  margin-top: 4rem;
}

.xuan p.active {
  color: rgb(90, 76, 243);
  /* 活动状态下的颜色 */
}

.tab5 {
  width: 100%;
  display: flex;
  margin: 0 auto;
  background-image: url('../assets/39.jpg');
  background-size: 100% 100%;
  background-repeat: no-repeat;
}

.tab5_1 {
  width: 60%;
  display: flex;
  flex-direction: column;
}

.tab5_2 {
  max-width: 600px;
  color: #929292;
  text-align: left;
  font-family: thiys;
  font-size: 17px;
  line-height: 1.2;
  margin-bottom: 1rem;
}

.tab5_1>h1 {
  font-size: 90px;
  font-family: thiyst;
  max-width: 700px;
  text-transform: uppercase;
  margin-top: 0;
  margin-bottom: 20px;
  font-weight: 800;
  line-height: 1;
}

.tab5_3 {
  display: flex;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans, sans-serif;
  font-size: 26px;
  font-weight: 700;
  margin-bottom: 1rem;
}

.tab5_3>p>a {
  color: white;
}

.tab5_3>p>a:hover {
  color: #5a4cf3;
}

.tab5_3>img {
  width: 30px;
}

.tab5_4 {
  width: 100%;
  display: flex;
}

.tab5_5 {
  display: flex;
  align-items: center;
  justify-content: center;
}

.tab5_5>img {
  width: 25px;
  margin-right: 0.5rem;
}

.tab5_6 {
  display: flex;
  align-items: center;
  opacity: 0.5;
  margin-right: 1rem;
}

.tab5_6>img {
  width: 30px;
  height: auto;
  margin-right: 0.5rem;
}

.tab5_7 {
  width: 100%;
  display: flex;
  margin-top: 2rem;
}

.tab5_8 {
  padding: 0.8rem 1.5rem 0.8rem 1.5rem;
  border-radius: 30px;
  background-color: #2a2a2a;
}

.tab5_8:hover {
  background-color: #5a4cf3;
}

.tab5_8>img {
  width: 125px;
  height: 33px;
}

.video-container {
  background-color: transparent !important;
  /* 设置背景色为透明 */
}

.video {
  background-color: transparent !important;
  /* 设置背景色为透明 */
}

.suzi {
  max-width: 1500px;
  width: 70%;
  margin: 0 auto;
  color: white;
  display: flex;
  justify-content: space-between;
  padding-top: 4rem;
  text-align: center;
  padding-bottom: 5rem;

}

.suzi_1>h2 {
  font-size: 35px;
}

.suzi_1>span {
  color: rgba(255, 255, 255, 0.6);
  font-family: six;
}

.suzi_2 {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-end;
  font-family: six;
  color: rgba(255, 255, 255, 0.6);
}

.bakes {
  width: 70%;
  margin: 0 auto;
  color: white;
}

.bakes_1 {
  display: flex;
  justify-content: center;
}

.bakes_1>h1 {
  font-size: 50px;
}

.bakes_1>img {
  width: 50px;
  height: 50px;
}

.bakes_2 {
  width: 58%;
  margin: 2rem auto;
  font-family: four;
  line-height: 25px;
  color: #929292;
  font-size: 18px;
}

.bakes_3 {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 2rem;
}

.bakes_3>a {
  margin-bottom: 1rem;
}

.bakes_6:hover {
  background-color: #141519;
  border: 0.94px solid #5a4cf3;
  box-shadow: 0 0 1px #5a4cf3, 0 0 25px rgba(90, 76, 243, .3);
}

.bakes_8:hover {
  background-color: #141519;
  border: 0.94px solid #5a4cf3;
  box-shadow: 0 0 1px #5a4cf3, 0 0 25px rgba(90, 76, 243, .3);
}

.bakes_4:hover {
  background-color: #141519;
  border: 0.94px solid #5a4cf3;
  box-shadow: 0 0 1px #5a4cf3, 0 0 25px rgba(90, 76, 243, .3);
}

.bakes_5:hover {
  background-color: #141519;
  border: 0.94px solid #5a4cf3;
  box-shadow: 0 0 1px #5a4cf3, 0 0 25px rgba(90, 76, 243, .3);
}

.bakes_10:hover {
  background-color: #141519;
  border: 0.94px solid #5a4cf3;
  box-shadow: 0 0 1px #5a4cf3, 0 0 25px rgba(90, 76, 243, .3);
}

.bakes_4 {
  background-color: #222327;
  border: 0.94px solid transparent;
  border-radius: 16px;
  width: 18rem;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1rem 0 1rem 0;
}

.bakes_4>img {
  width: 150px;
  height: 35px;
}

.bakes_5 {
  background-color: #222327;
  border: 0.94px solid transparent;
  border-radius: 16px;
  width: 18rem;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1rem 0 1rem 0;


}

.bakes_5>img {
  width: 100px;
  height: 42px;
}

.bakes_6 {
  background-color: #222327;
  border: 0.94px solid transparent;
  border-radius: 16px;
  width: 18rem;
  display: flex;
  align-items: center;
  justify-content: center;

  padding: 1rem 0 1rem 0;

}

.bakes_6>img {
  width: 150px;
  height: 38px;
}

.bakes_8 {
  background-color: #222327;
  border: 0.94px solid transparent;
  border-radius: 16px;
  width: 18rem;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1rem 0 1rem 0;

}

.bakes_8>img {
  width: 201px;
  height: 23px;
}

.tbiao_p {
  width: 100%;
  display: flex;
  justify-content: center;
}

.tbiao_p>p:nth-child(1) {
  width: 8rem;
  height: 1rem;
  background-color: #929292;
  border-radius: 5px;
  margin-right: 2rem;
}

.tbiao_p>p:nth-child(2) {
  width: 8rem;
  height: 1rem;
  background-color: #929292;
  border-radius: 5px;
  margin-right: 2rem;
}

.tbiao_p>p:hover {
  background-color: #5a4cf3;
}

.bakes_10 {
  background-color: #222327;
  border: 0.94px solid transparent;
  border-radius: 16px;
  width: 18rem;
  display: flex;
  align-items: center;
  justify-content: center;
  /* padding: 1rem 0 1rem 0; */
}

.bakes_10>img {
  width: 60px;
  height: 60px;
}

.bakes_11 {
  display: flex;
}

.bakes_11>a {
  margin-right: 0.6rem;
}

.Feature {
  width: 70%;
  margin: 0 auto;
  color: white;
  padding-top: 10rem;
  padding-bottom: 10rem;
}

.Feature_2 {
  width: 65%;
  color: #929292;
  margin: 0 auto;
  text-align: center;
  padding-top: 1rem;
  font-family: four;
  font-size: 18px;
  padding-bottom: 5rem;
}

.pop {
  max-width: 1400px;
  width: 80%;
  margin: 0 auto;
  display: flex;
}

.pop_1 {
  width: 35%;
  display: flex;
  flex-direction: column;
}

.pop_2 {
  padding: 2rem 1rem 0 1rem;
  width: 100%;
  display: flex;
  color: white;
  flex-direction: column;
  align-items: center;
  background-color: #222327;
  border-radius: 20px;
  position: relative;
  height: 28rem;
  margin-bottom: 1rem;
  overflow: hidden;
}

.pop_3 {
  width: 100%;
  display: flex;
  font-family: six;
  font-size: 16px;
  align-items: center;
  margin-bottom: 1rem;
}

.pop_3>h2 {
  font-size: 18px;
  margin-left: 1rem;
}

.pop_3>img {
  width: 30px;
  height: 30px;
}

.pop_4 {
  font-family: thiys;
  color: #aaa9ad;
  font-weight: 400;
  text-align: left;
  line-height: 28px;
  margin-bottom: 0;
  font-size: 18px;
}

.pop_5 {
  width: 387px;
  height: 354px;
  position: absolute;
  top: auto;
  bottom: 13%;
  left: auto;
  right: 15%;
  transform: matrix(1.3, 0, 0, 1.3, 0, 40);
}

.pop_3_1>h2 {
  font-size: 18px;
}

.pop_3_1 {
  width: 100%;
  display: flex;
  font-family: six;
  font-size: 16px;
  align-items: center;
  margin-bottom: 1rem;
}

.pop_5_1 {
  width: 320px;
  position: absolute;
  top: auto;
  bottom: 14%;
  left: auto;
  right: 15%;
  transform: matrix(1.3, 0, 0, 1.3, 0, 40);
}

.pop_6 {
  width: 70%;
  color: white;
  display: flex;
  flex-direction: column;
}

.pop_7 {
  width: 100%;
  display: flex;
  justify-content: space-around;
}

.pop_8 {
  width: 25rem;
  border-radius: 20px;
  padding: 1rem;
  background-color: #222327;
  position: relative;
  top: 0;
}

.pop_8>h3 {
  margin: 1rem 0;
}

.pop_8>span {
  display: block;
  padding-bottom: 6rem;
}

.pop_8>img {
  width: 420px;
  height: 200px;
  position: absolute;
  display: block;
  padding-bottom: 6rem;
  bottom: -43%;
  left: -5%;
}

.pop_9 {
  width: 26rem;
  border-radius: 20px;
  padding: 1rem;
  background-color: #222327;
  position: relative;
}


.pop_9>h3 {
  margin: 0.5rem 0;
}

.pop_9>p {
  font-family: thiys;
  color: #aaa9ad;
  font-weight: 400;
  text-align: left;
  line-height: 28px;
  margin-bottom: 0;
  font-size: 17px;
}

.pop_9>img {
  width: 441px;
  height: 251px;
  position: absolute;
  display: block;
  padding-bottom: 6rem;
  bottom: -57%;
  left: 20%;
}

.pop_10 {
  width: 100%;
  display: flex;
  /* border: 1px red solid; */
}

.pop_11 {
  width: 50%;
  display: flex;
  position: relative;
  flex-direction: column;
  align-items: center;
  margin-top: 20rem;
  flex-direction: column
}

.pop_11>img {
  position: absolute;
  width: 750px;
  height: 700px;
  bottom: -35%;
  left: -35%;
  z-index: 0;
}

.pop_12 {
  display: flex;
}

.pop_12>h1 {
  font-size: 50px;
}

.pop_12>img {
  width: 50px;
  height: 50px;
}

.pop_13 {
  display: flex;
  width: 100%;
  justify-content: space-evenly;
}

.pop_13>div {
  padding: 1rem 2.5rem 1rem 2.5rem;
  background-color: #2a2a2a;
  font-family: thiys;
  border-radius: 30px;
  font-weight: 500;
  font-size: 16px;
}

.pop_14 {
  width: 50%;
  margin-top: 1rem;
}

.pop_15 {
  width: 193px;
  height: 188px;
  position: absolute;
  top: auto;
  bottom: 13%;
  left: auto;
  right: 7%;
  transform: matrix(1.3, 0, 0, 1.3, 0, 40);
}

.pop_16 {
  width: 98%;
  background-color: #2a2a2a;
  margin-left: 1rem;
  border-radius: 15px;
}

.pop_17 {
  font-family: thiys;
  /* color: #aaa9ad; */
  line-height: 30px;
  padding: 2rem 1.5rem 0 1.5rem;
}

.pop_17>img {
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
}

.Roadmap {
  width: 80%;
  margin: 0 auto;
  margin: 0rem auto;
  color: white;
  padding-top: 5rem;
}

.Roadmap_1 {
  width: 80%;
  color: #929292;
  margin: 0 auto;
  font-family: thiys;
  text-align: center;
  line-height: 30px;
  padding-top: 1rem;
  padding-bottom: 2rem;
}

.Roadmap_2 {
  max-width: 1300px;
  margin: 0 auto;
  width: 100%;
  padding-left: 3rem;
  padding-top: 3rem;
  display: flex;
  background-color: rgba(34, 35, 39, .7);
  padding-bottom: 5rem;
  border-radius: 20px;
}

.Roadmap_3 {
  width: 360px;
  height: 420px;
  background-image: url('../assets/89.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background-repeat: no-repeat;
  background-size: contain;
}

.Roadmap_4 {
  width: 360px;
  height: 420px;
  background-image: url('../assets/90.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background-repeat: no-repeat;
  background-size: contain;
}

.Roadmap_5 {
  width: 360px;
  height: 420px;
  background-image: url('../assets/88.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background-repeat: no-repeat;
  background-size: contain;
}

.Roadmap_6 {
  width: 360px;
  height: 450px;
  background-image: url('../assets/87.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background-repeat: no-repeat;
  background-size: contain;
}

.Media {
  width: 100%;
  color: white;
  margin-top: 5rem;
}

.carousl {
  height: 900px;
  perspective: 600px;
  transform: translateY(0px);
  overflow: hidden;
  position: relative;
  width: 100%;
}

.carousel-fixed-item {
  z-index: 999;
  width: 100%;
  height: auto;
  padding-left: 18px;
  padding-right: 18px;
  display: block;
  position: absolute;
  top: 45%;
  left: 0;
  right: 0;
}

.left {
  float: left !important;
  cursor: pointer;
  position: relative;
}

.right {
  float: right !important;
  cursor: pointer;
  position: relative;
}

.left>img {
  width: 30px;
  height: 30px;
  transform: rotate(180deg);
}

.right>img {
  width: 30px;
  height: 30px;
}

.carousl_1 {
  width: 80%;
  margin: 0 auto;
  padding-top: 5rem;
}

.carousl_2 {
  width: 53%;
  margin: 0 auto;
  padding: 2rem;
  border-radius: 15px;
  border: 2px #5a4cf3 solid;
}

.carousl_2>img {
  width: 300px;
}

.el-carousel {
  background-color: none;
}

.el-carousel__item--card::v-deep {
  width: 50%;
}

.el-carousel /deep/ .el-carousel__item:nth-child(2n+1) {
  /* background-color: rgba(255, 255, 255, 0.1); */
  background-color: transparent !important;


}

.el-carousel /deep/ .el-carousel__item:nth-child(2n) {
  /* background-color: rgba(255, 255, 255, 0.1); */
  background-color: transparent !important;

}

.el-carousel /deep/ .el-carousel__mask {
  /* background-color: rgba(255, 255, 255, 0.1); */
  background-color: transparent !important;
}

.carousl_3>h2 {
  text-align: left;
  font-family: thiyst;
}

.carousl_3>p {
  text-align: left;
  font-family: thiys;
}

.yfoot {
  width: 100%;
  background: #000;
}

.yfootbox {
  width: 63.6%;
  margin: 0 auto;
  padding: 7.5rem 0 3.75rem;
}

.yfootbyi {
  width: 43.75rem;
}

.yfootbyi>a {
  display: block;
  width: 6.25rem;
  height: 4.375rem;
  margin-bottom: 1.25rem;
  overflow: hidden;
}

.yfootbyi>a>img {
  width: 300%;
  margin-left: -100%;
  margin-top: -50%;
}

.yfootbyi>p {
  font-family: four;
  font-size: 1.125rem;
  color: #e6e6e6;
  line-height: 1.875rem;
  margin: 0.625rem 0 2.5rem;
}

.yfootbs {
  width: 60%;
  margin: 0.625rem 0 2.5rem;
  column-gap: 2.25rem;
  flex-wrap: wrap;
}

.yfootbs>a {
  width: 2.25rem;
  height: 2.25rem;
  border-radius: 0.5rem;
  background: white;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0.5rem 0;
  transition: transfrom 0.3s;
}

.yfootbs>a:hover {
  transform: translate3d(0, -3px, 0.01px);
}

.yfootber {
  width: 14.75rem;
  margin-right: 2.5rem;
}

.yfootbsan {
  width: 17.25rem;
}

.yfbeti {
  font-family: six;
  font-size: 1.375rem;
  line-height: 1.5rem;
  color: #fff;
  margin-bottom: 2.5rem;
}

.yfbeas>a {
  display: block;
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.25rem;
  color: #e6e6e6;
  transition: transform 0.3s, color 0.3s;
  margin-bottom: 1.25rem;
}

.yfbeas>a:hover {
  color: #5c54ef;
  font-weight: 700 !important;
  transform: translate3d(6px, 0, 0.01px);
}

.yfootend {
  width: 63.6%;
  margin: 0 auto;
  border-top: 1px dashed #585858;
  justify-content: space-between;
  align-items: center;
  padding-top: 3.75rem;
  padding-bottom: 3.75rem;
}

.update {
  font-family: four;
  font-size: 1.125rem;
  line-height: 1.4375rem;
  color: #585858;
  transition: color 0.3s;
}

.update:hover {
  color: #5c54ef;
}

.yender {
  width: 100%;
  height: 50rem;
  position: relative;
}

.yendertbg {
  width: 100%;
  height: 33.75rem;
  background-image: linear-gradient(#000, transparent 48%);
  position: absolute;
  top: 0;
  left: 0;
  z-index: 100;
}

.section-hero {
  width: 100%;
  height: 50rem;
  opacity: 0.8;
  position: relative;
  overflow: hidden;
}

.top01 {
  position: absolute;
  width: 13.75rem;
  height: auto;
  top: 0%;
  bottom: auto;
  left: 15%;
  right: auto;
  z-index: 3;
}

.top02 {
  z-index: 4;
  width: 100%;
  height: auto;
  display: block;
  position: absolute;
  top: auto;
  bottom: 0%;
  left: 0%;
  right: 0%;
}

.top03 {
  z-index: 4;
  position: absolute;
  width: 13.75rem;
  height: auto;
  top: 0%;
  bottom: auto;
  left: auto;
  right: -2%;
}

.top04 {
  height: auto;
  display: block;
  position: absolute;
  z-index: 4;
  width: 6.25rem;
  top: 5%;
  left: auto;
  right: 43%;
  bottom: 0%;
}

.top05 {
  height: auto;
  display: block;
  position: absolute;
  width: 13.75rem;
  top: auto;
  bottom: 0%;
  left: 5%;
  right: auto;
}

.top06 {
  position: absolute;
  width: 11.25rem;
  top: 10%;
  z-index: 4;
  bottom: auto;
  left: 0%;
  right: auto;
}

.top_07 {
  position: absolute;
  top: 20%;
  bottom: auto;
  z-index: 4;
  width: 4.375rem;
  left: 14%;
  right: auto;
}

.cloud01 {
  z-index: 4;
  width: 3.75rem;
  height: auto;
  display: block;
  position: absolute;
  top: 10%;
  bottom: 0%;
  left: auto;
  right: 30%;
}

.cloud02 {
  display: block;
  position: absolute;
  z-index: 4;
  width: 100px;
  top: 4%;
  height: auto;
  bottom: 0%;
  left: 26%;
  right: auto;
}

.cloud03 {
  display: block;
  position: absolute;
  z-index: 4;
  width: 6.25rem;
  height: auto;
  top: 9%;
  bottom: 0%;
  left: 35%;
  right: auto;
}

.cloud04 {
  display: block;
  position: absolute;
  z-index: 4;
  width: 2.25rem;
  height: auto;
  top: 6%;
  left: auto;
  right: 27%;
  bottom: 0%;
}

.cloud05 {
  z-index: 4;
  height: auto;
  display: block;
  position: absolute;
  bottom: 0%;
  left: auto;
  right: 22%;
  width: 2.5rem;
  top: 20%;
}

.cloud06 {
  z-index: 4;
  height: auto;
  display: block;
  position: absolute;
  top: 22%;
  bottom: 0%;
  right: auto;
  width: 1.875rem;
  left: 30%;
}

.cloud07 {
  z-index: 4;
  width: 1.875rem;
  height: auto;
  display: block;
  position: absolute;
  top: 10%;
  bottom: 0%;
  left: 45%;
  right: auto;
}

.cloud08 {
  z-index: 4;
  display: block;
  position: absolute;
  bottom: 0%;
  left: auto;
  width: 2.8125rem;
  height: auto;
  top: 38%;
  right: 26%;
  bottom: 0%;
}

.cloud09 {
  z-index: 4;
  width: 1.875rem;
  height: auto;
  position: absolute;
  top: auto;
  bottom: 40%;
  left: 32%;
  right: 0%;
}

.cloud_10 {
  z-index: 4;
  width: 4.375rem;
  position: absolute;
  top: auto;
  bottom: 58%;
  left: 38%;
  right: 0%;
}

.cloud_11 {
  z-index: 4;
  width: 1.25rem;
  position: absolute;
  top: 15%;
  bottom: auto;
  left: 38%;
  right: 0%;
}

.bottom01 {
  height: auto;
  display: block;
  position: absolute;
  width: 31.25rem;
  top: auto;
  bottom: -4%;
  left: auto;
  right: 0%;
}

.bottom02 {
  z-index: 3;
  width: 3.125rem;
  height: auto;
  display: block;
  position: absolute;
  top: auto;
  bottom: 8%;
  left: auto;
  right: 33.5%;
}

.bottom03 {
  z-index: 2;
  width: 5rem;
  height: auto;
  display: block;
  position: absolute;
  top: 72%;
  bottom: 0%;
  left: 44%;
  right: auto;
}

.bottom04 {
  z-index: 1;
  width: 4.375rem;
  height: auto;
  display: block;
  position: absolute;
  top: auto;
  bottom: 0%;
  left: 32%;
  right: auto;
}

.bottom05 {
  z-index: 3;
  width: 6.25rem;
  position: absolute;
  top: auto;
  bottom: 10%;
  left: 27%;
  right: auto;
}

.bottom06 {
  z-index: 3;
  width: 21.875rem;
  height: auto;
  position: absolute;
  top: auto;
  bottom: 10%;
  left: 10%;
  right: 0%;
}

.bottom07 {
  z-index: 3;
  width: 5.625rem;
  position: absolute;
  top: auto;
  bottom: 30%;
  left: auto;
  right: 11%;
}

.bg-hero {
  z-index: 0;
  width: 100%;
  height: 100%;
  display: block;
  position: relative;
  top: 0%;
  bottom: 0%;
  left: 0%;
  right: 0%;
}

.yendercon {
  width: 39.4%;
  position: absolute;
  left: 30%;
  padding: 16.875rem 0;
  z-index: 1000;
}

.yenderti {
  position: relative;
  width: 100%;
}

.yenderti>img {
  width: 6.25rem;
  height: 6.25rem;
  position: absolute;
  top: -27.5%;
  left: 50%;
  transform: translate(-3.125rem);
}

.yendeh {
  font-family: six;
  text-shadow: 0 1px 6px rgba(0, 0, 0, 0.4);
  font-size: 3.125rem;
  line-height: 1.222em;
  color: #fff;
  margin: 1.5rem 0 1rem;
}

.yenderti p {
  text-align: center;
  color: #fff;
  text-shadow: 0 2px 2px rgba(0, 0, 0, 0.5);
  margin-bottom: 1.25rem;
  font-size: 1.115rem;
  line-height: 1.875rem;
}

.yenderans {
  display: flex;
  justify-content: center;
  column-gap: 1.5rem;
}

.yenderans>a {
  background-color: #2a2a2a;
  border-radius: 3rem;
  padding: 0.75rem 2rem;
}

.yenderans>a:hover {
  background-color: #5c54ef;
}

.yenderans>a>img {
  width: 7.8125rem;
}

.yendsan {
  width: 100%;
  background: #000;
  padding: 6.25rem 0 3.75rem;
}

.yendsanbox {
  width: 73.125rem;
  margin: 0 auto;
}

.yendsbti {
  width: 100%;
  position: relative;
  margin: 1.5rem 0 3.5rem;
}

.yendsbttxt {
  font-family: six;
  font-size: 3.125rem;
  line-height: 1.222em;
  color: #fff;
  text-align: center;
  position: relative;
  z-index: 10;
}

.yendsbti>img {
  width: 6.4375rem;
  height: 6.4375rem;
  position: absolute;
  top: -4rem;
  left: 50%;
  transform: translate(-3.41875rem);
}

.yendsbcon {
  width: 100%;
  border-top: 1px solid rgb(54, 54, 54);
}

.yesbcybox {
  height: 5.8125rem;
  padding: 1.6875rem 0;
  border-bottom: 1px solid rgb(54, 54, 54);
  overflow: hidden;
  transition: height 0.5s;
}

.yesbcyboxhei {
  height: 12.8125rem !important;
}

.yendsbcyi {
  justify-content: space-between;
  align-items: center;
}

.yendsbcfon {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans,
    sans-serif;
  font-size: 1.375rem;
  color: #fff;
  font-weight: 700;
}

.yendsbcycha {
  width: 2.375rem;
  height: 2.375rem;
  position: relative;
  cursor: pointer;
}

.yendsbcycha>div {
  width: 1.75rem;
  height: 0.125rem;
  background-color: #5c54ef;
  border-radius: 1.25rem;
  position: absolute;
  left: 0.3125rem;
  top: 50%;
  transition: transform 0.3s;
}

.yendsbcycha>div:nth-child(2) {
  transform: rotate(90deg);
}

.tendsbcyj>div:nth-child(2) {
  transform: rotate(0deg) !important;
}

.yesbcybox>p {
  font-family: four;
  margin-top: 1.25rem;
  color: #aaa9ad;
  font-weight: 400;
  font-size: 1.125rem;
  line-height: 1.875rem;
}

.yendsi {
  width: 100%;
  background: #000;
}

.yendsibox {
  position: relative;
  width: 29.625rem;
  margin: 1.5rem auto 2.25rem;
}

.yendsibox>div {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans,
    sans-serif;
  font-size: 3.125rem;
  line-height: 3.8125rem;
  font-weight: 700;
  color: #fff;
  position: relative;
  z-index: 10;
}

.yendsibox>img {
  width: 2.9375rem;
  height: 2.75rem;
  position: absolute;
  right: -6%;
  top: 20%;
}

.yendsibcon {
  width: 100%;
  height: 64.6875rem;
  overflow: hidden;
  position: relative;
}

.yendsibcfyi {
  display: none;
}

.yendsibcfer {
  display: none;
}

.yendsibcyi {
  display: block;
  width: 35.25rem;
  height: 100%;
  transition: all 0.3s;
  transform: rotate(-20deg) translateY(400px) !important;
}

.yendsibcer {
  display: block;
  width: 35.25rem;
  height: 100%;
  transition: all 0.3s;
  transform: rotate(-10deg) translateY(100px) !important;
}

.yendsibcsan {
  display: block;
  width: 35.25rem;
  height: 100%;
  transition: all 0.3s;
  transform: rotate(0deg) translateY(0px) !important;
}

.yendsibcsi {
  display: block;
  width: 35.25rem;
  height: 100%;
  transition: all 0.3s;
  transform: rotate(10deg) translateY(100px) !important;
}

.yendsibcwu {
  display: block;
  width: 35.25rem;
  height: 100%;
  transition: all 0.3s;
  transform: rotate(20deg) translateY(400px) !important;
}

.yendsibcliu {
  display: none;
}

.yendsibcqi {
  display: none;
}

.yendsibcimg {
  width: 17.625rem;
  display: block;
  margin: 0 auto 5rem;
}

.yendsitxty {
  color: #fff;
  margin-bottom: 0.625rem;
  text-align: center;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans,
    sans-serif;
  font-size: 1.625rem;
  font-weight: 700;
  line-height: 1.4;
  transition: all 0.4s;
  transition-delay: 0.8s;
  opacity: 0;
}

.yendsitxte {
  margin-bottom: 0.75rem;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans,
    sans-serif;
  line-height: 1.667em;
  transition: all 0.6s;
  color: #fff;
  text-align: center;
  font-size: 1.125rem;
  font-weight: 700;
  opacity: 0;
}

.yendsibctxt>p {
  text-align: center;
  color: #aaa9ad;
  margin-bottom: 0.75rem;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans,
    sans-serif;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.667em;
  transition: all 0.6s;
  transition-delay: 0.3s;
  position: relative;
  opacity: 0;
}

.show .yendsitxty {
  opacity: 1;
}

.show .yendsitxte {
  opacity: 1;
}

.show .yendsibctxt>p {
  opacity: 1;
}

.zuojt {
  cursor: pointer;
  width: 3.75rem;
  height: 3.75rem;
  background-color: rgba(255, 255, 255, 0.3);
  border-radius: 50%;
  position: absolute;
  padding: 0.625rem;
  top: 60%;
  left: 25%;
  box-sizing: border-box;
  z-index: 1000;
}

.zuojt>img {
  width: 2.5rem;
  height: 2.5rem;
}

.youjt {
  cursor: pointer;
  width: 3.75rem;
  height: 3.75rem;
  background-color: rgba(255, 255, 255, 0.3);
  border-radius: 50%;
  position: absolute;
  padding: 0.625rem;
  top: 60%;
  right: 25%;
  z-index: 1000;
  box-sizing: border-box;
}

.youjt>img {
  width: 2.5rem;
  height: 2.5rem;
  transform: rotate(180deg);
}

.yendsian {
  position: absolute;
  bottom: 10%;
  left: 50%;
  transform: translate(-50%);
}

.yendsian>a {
  font-family: six;
  font-size: 1rem;
  line-height: 1.3125rem;
  color: white;
  padding: 0.75rem 2rem;
  align-items: center;
  justify-content: center;
  border-radius: 5rem;
  background: #5c54ef;
}

.yendwu {
  width: 100%;
  height: auto;
  padding: 2.5rem 0;
  margin-bottom: 6.25rem;
  overflow: hidden;
}

.loop-marquee-logo-wrapper {
  display: flex;
}

.loop-marquee-item-holder {
  flex: none;
  display: flex;
}

.loop-marquee_item-top {
  white-space: nowrap;
  will-change: transform;
  animation: loop-marquee_item-top 200s linear infinite;
  grid-column-gap: 1.5rem;
  flex: none;
  align-items: center;
  display: flex;
}

.loop-marquee_item-bottom {
  white-space: nowrap;
  will-change: transform;
  animation: loop-marquee_item-bottom 200s linear infinite;
  grid-column-gap: 1.5rem;
  flex: none;
  align-items: center;
  display: flex;
}

.loop-marquee_brand-logo {
  grid-column-gap: 1.5rem;
  flex: none;
  display: flex;
}

.loop-marquee-brand-logo {
  height: 18.75rem;
}

@keyframes loop-marquee_item-top {
  0% {
    transform: translateX(-70%);
  }

  100% {
    transform: translateX(0%);
  }
}

@keyframes loop-marquee_item-bottom {
  0% {
    transform: translateX(-70%);
  }

  100% {
    transform: translateX(0%);
  }
}

.yendqi {
  width: 100%;
  background: #000;
}

.yendqibox {
  width: 80.75rem;
  margin: 0 auto;
}

.yendqiti {
  width: 23.625rem;
  margin: 1.5rem auto 1rem;
  position: relative;
}

.yendqittop {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans,
    sans-serif;
  font-size: 3.125rem;
  font-weight: 700;
  line-height: 1.222em;
  color: #fff;
  position: relative;
  z-index: 100;
}

.yendqiti>img {
  width: 4.6875rem;
  height: 4.6875rem;
  position: absolute;
  top: -10%;
  right: -6%;
}

.yendqibox>p {
  font-family: four;
  font-size: 1.125rem;
  line-height: 1.875rem;
  color: #929292;
  text-align: center;
  margin-bottom: 1.25rem;
}

.yendqicon {
  justify-content: space-between;
  column-gap: 1.5rem;
}

.yendqicyi {
  width: 25.875rem;
  height: 20rem;
  padding: 0.625rem;
  box-sizing: border-box;
  border-radius: 1.625rem;
  transition: transform 0.8s;
  border: 1px solid transparent;
  background-color: #222327;
  position: relative;
}

.yendqicyi:hover {
  background-color: #141519;
  border: 1px solid #5c54ef;
  box-shadow: 0 0 7.52px rgba(92, 84, 239, 0.8),
    0 0 12px rgba(92, 84, 239, 0.45);
}

.yendqcyt {
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
}

.yendqcybox {
  width: 100%;
  padding: 0.625rem;
  position: relative;
  z-index: 1000;
}

.yeqcyti {
  font-family: six;
  font-size: 1.125rem;
  line-height: 1.875rem;
  color: #fff;
  margin-bottom: 2.5rem;
}

.yeqcylogo {
  width: 2rem;
  height: 2rem;
  border-radius: 50%;
  margin-bottom: 1.25rem;
}

.yeqcytxt {
  font-family: four;
  font-size: 1.125rem;
  line-height: 1.875rem;
  color: #aaa9ad;
}

.yeqcyimger {
  width: 14.75rem;
  position: absolute;
  top: -16%;
  right: -10%;
  transition: all 0.3s;
}

.yendqicyi:hover .yeqcyimger {
  transform: translate3d(0px, -0.625rem, 0px);
}

.yeqcyimgee {
  width: 8.875rem;
  top: 0;
  right: 0;
}

.yeqcyimges {
  width: 9.875rem;
  top: -15%;
  right: 0;
}

.yendliu {
  width: 100%;
}

.yendliubox {
  width: 80.75rem;
  margin: 0 auto;
}

.yendlbt {
  width: 43.75rem;
  margin: 1.5rem auto 3rem;
  position: relative;
}

.yendliubti {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Noto Sans, Ubuntu, Cantarell, Helvetica Neue, Oxygen, Fira Sans, Droid Sans,
    sans-serif;
  font-size: 3.125rem;
  font-weight: 700;
  line-height: 1.222em;
  color: #fff;
  position: relative;
  z-index: 100;
}

.yendlbt>img {
  width: 5rem;
  height: 5rem;
  position: absolute;
  left: 12.5%;
  top: -20%;
}

.yendliubcon {
  column-gap: 1.5rem;
  align-items: center;
}

.yendliubcleft {
  width: 39.625rem;
}

.yendliubcltop {
  width: 100%;
  height: 20.3125rem;
  padding: 0.625rem;
  box-sizing: border-box;
  background: url("../assets/64905ba8d30ce8b1abf21e0a_Frame1686561092.webp");
  background-position: 100%;
  background-size: contain;
  border-radius: 1.5rem;
  background-color: #212327;
  background-repeat: no-repeat;
  margin-bottom: 1.5rem;
}

.yendliubclytxt {
  padding: 2.5rem 1.5rem 1.5rem;
  box-sizing: border-box;
}

.yendliubclytxt>p {
  font-family: four;
  font-size: 1.125rem;
  line-height: 1.875rem;
  color: #fff;
  width: 18.75rem;
}

.yendliubclbot {
  column-gap: 1rem;
}

.yendliubclboty {
  width: 19.3125rem;
  height: 16.25rem;
  border-radius: 1.5rem;
  background: url("../assets/64905ba85d9169ba1ce379f1_recommend.webp");
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: contain;
}

.yendliubclbot>div:nth-child(2) {
  background: url("../assets/64905ba751a910ba7b449235_Frame48095880.webp");
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: contain;
}

.yendliubcright {
  width: 39.625rem;
  background-color: #5a4cf3;
  border-radius: 1.5rem;
  padding: 0.625rem;
  box-sizing: border-box;
}

.yendliubcrbox {
  width: 100%;
  padding: 2.5rem 1.5rem 1.5rem;
  box-sizing: border-box;
  position: relative;
}

.yendliubcrbimgy {
  width: 2.25rem;
  height: 2.25rem;
}

.yendliubcrbimge {
  width: 10rem;
  height: 10rem;
  position: absolute;
  transition: transform 0.8s;
  transform: scale(2);
  right: 10%;
  top: 0;
}

.yendliubcrbimge:hover {
  transform: matrix(2, 0, 0, 2, 0, -10);
}

.yendliubcrbtxty {
  font-family: four;
  font-size: 1.125rem;
  line-height: 1.875rem;
  color: #fff;
  margin-bottom: 1.25rem;
}

.yendliubconer {
  margin-top: 4rem;
}

.yendliubcer {
  column-gap: 1.5rem;
  margin-bottom: 1.5rem;
}

.yendliubcerleft {
  width: 50rem;
  height: 20.3125rem;
  padding: 0.625rem;
  box-sizing: border-box;
  background: url("../assets/649e46f654356260b8a1b46a_recommend.webp");
  background-position: 50% 100%;
  background-size: cover;
  position: relative;
  background-color: #5a4cf3;
  border-radius: 1.5rem;
}

.yendliubcelbox {
  width: 100%;
  padding: 2.5rem 1.5rem 1.5rem;
  box-sizing: border-box;
}

.yendliubcelbox>img {
  transition: transform 0.8s;
  transform: scale(2);
  width: 12.6875rem;
  position: absolute;
  left: 15%;
  right: auto;
  top: 0;
}

.yendliubcelbox>img:hover {
  transform: matrix(2, 0, 0, 2, 0, -10);
}

.yendliiubcelbot {
  width: 2.8125rem;
  height: 2.8125rem;
  border-radius: 50%;
  justify-content: center;
  align-items: center;
  transition: box-shadow 0.3s, background-color 0.3s, transform 0.3s,
    opacity 0.3s;
  position: absolute;
  top: auto;
  bottom: 5%;
  left: auto;
  right: 5%;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.3);
  background-color: rgb(92, 84, 239);
  color: #fff;
  font-size: 1.4375rem;
  transform: rotate(-45deg);
}

.yendliiubcelbot:hover {
  background: #fff;
  color: rgb(92, 84, 239);
  transform: rotate(0deg);
}

.yendliubcerlefte {
  width: 29.1875rem;
  background: url("../assets/649e43b9c962420345a14776UNLOCKEXCLUSIVE.webp");
  background-position: 50%;
  background-size: cover;
  position: relative;
  height: 20.3125rem;
  padding: 0.625rem;
  box-sizing: border-box;
  border-radius: 1.5rem;
}

.yendliubesi {
  column-gap: 1rem;
}

.yendliubesiy {
  width: 24.5rem;
  height: 20.3125rem;
  padding: 2.5rem 1.5rem 1.5rem;
  box-sizing: border-box;
  background: url("../assets/649e43b9593476f369615216_gamificationandrewards.webp");
  background-position: 100%;
  background-size: cover;
  border-radius: 1.5rem;
  position: relative;
}

.yendliubesie {
  background: url("../assets/649e854ae9fa4c0e6986ba25_recommend.png");
  background-position: 100%;
  background-repeat: no-repeat;
  background-size: cover;
  border: 1px #000;
  border-radius: 1.5rem;
  width: 24.5rem;
  height: 20.3125rem;
  padding: 2.5rem 1.5rem 1.5rem;
  box-sizing: border-box;
  position: relative;
}

.yendliubesis {
  width: 29.1875rem;
  height: 20.3125rem;
  padding: 0.625rem;
  box-sizing: border-box;
  background: url("../assets/649e43b91cfd46906ee08140_digitalfashionshowrooms.webp");
  background-position: 50%;
  background-size: cover;
  position: relative;
  margin-left: 0.5rem;
}

.yendlbtshop {
  width: 8.5rem;
  margin: 1.5rem auto 3rem;
  position: relative;
}

.yendlbtshop>img {
  width: 5rem;
  position: absolute;
  left: -30%;
  top: -25%;
}

.yendliubottom {
  margin: 4.5rem 0;
  justify-content: center;
  column-gap: 1.25rem;
}

.yendliubottom>button {
  width: 5rem;
  height: 0.625rem;
  opacity: 0.2;
  background-color: #5a4cf3;
  border-radius: 0.375rem;
  transition: all 0.3s;
  cursor: pointer;
}

.yendliubottom>.active {
  opacity: 1;
}

.yshowliu {
  display: block !important;
}

.yendliubyi {
  display: none;
  height: 50rem;
}

.yendliuber {
  display: none;
  height: 50rem;
}

@media (max-width: 1250px) {
  .box {
    width: 100vw;
    overflow: hidden;
  }

  .head {
    width: 95%;
    margin: 0 auto;
  }

  .head_1 {
    display: none;
  }

  .yendliubox {
    width: 100%;
  }

  .yendliubyi {
    height: auto;
  }

  .yendlbt {
    width: 100%;
  }

  .yendliubti {
    text-align: center;
    font-size: 2rem;
  }

  .yendliubcon {
    display: block;
  }

  .yendliubcleft {
    width: 100%;
  }

  .yendliubclbot {
    width: 100%;
    display: block;
  }

  .yendliubclboty {
    width: 100%;
    margin: 1rem 0;
  }

  .yendliubcright {
    width: 95%;
    margin: 0 auto;
  }

  .yendliubcrbimge {
    width: 7rem;
    height: 7rem;
  }

  .yendliubcrbox>p:nth-child(3) {
    margin-top: 6rem !important;
  }

  .yendliubcer {
    display: block;
  }

  .yendliubcerleft {
    width: 95%;
    margin: 0.5rem auto;
  }

  .yendliubcerlefte {
    width: 95%;
    margin: 0.5rem auto;
  }

  .yendliubesi {
    display: block;
  }

  .yendliubesiy {
    width: 95%;
    margin: 0.5rem auto;
  }

  .yendliubesie {
    width: 95%;
    margin: 0.5rem auto;
  }

  .yendliubesis {
    width: 95%;
    margin: 0.5rem auto;
  }

  .yendliuber {
    height: auto;
  }

  .yendqibox {
    width: 100%;
  }

  .yendqiti {
    width: 100%;
  }

  .yendqittop {
    text-align: center;
    font-size: 2rem;
  }

  .yendqiti>img {
    right: 0;
  }

  .yendqicon {
    display: block;
  }

  .yendqicyi {
    width: 95%;
    margin: 0.5rem auto;
  }

  .yendsi {
    display: none;
  }

  .yendsanbox {
    width: 100%;
  }

  .yendsbttxt {
    font-size: 2rem;
  }

  .yendsbcfon {
    font-size: 1rem;
  }

  .yendsbcyi {
    padding: 0 1rem;
  }

  .yendsbshou {
    width: 70%;
  }

  .yesbcyboxhei {
    height: 20rem !important;
  }

  .yendercon {
    width: 95%;
    height: 100%;
    padding: 13.875rem 0;
    left: 50%;
    transform: translate(-50%);
  }

  .yendliubconer {
    margin-top: 8rem;
  }

  .yendeh {
    font-size: 2rem;
    text-align: center;
  }

  .yenderans {
    column-gap: 0.5rem;
  }

  .yenderans>a {
    padding: 0.5rem 1rem;
  }

  .yfootbox {
    width: 100%;
    display: block;
  }

  .yfootbyi {
    width: 95%;
  }

  .yendertbg {
    top: -0.25rem;
  }

  .yfootbyi>a {
    margin: 1.25rem auto;
  }

  .yfootbyi>p {
    text-align: center;
  }

  .yfootbs {
    width: 95%;
    margin: 0 auto;
    justify-content: center;
  }

  .yfootber {
    width: 100%;
    text-align: center;
  }

  .yfootbsan {
    width: 100%;
    text-align: center;
    margin: 0.5rem auto;
  }

  .yfootend {
    width: 100%;
    display: block;
    padding: 1.5rem 0;
  }

  .yfootend>a {
    text-align: center;
    display: block;
    margin: 0.5rem auto;
  }

  .tank {
    margin: 60% auto;
  }

  .tank_1>h1 {
    font-size: 19px
  }

  .tank_2 {
    font-size: 12px
  }

  .center {
    /* display:none; */
  }

  .cen {
    width: 95%;
  }

  .tab_1 {
    margin-top: 2rem;
  }

  .tab_2 {
    flex-direction: column;
  }

  .tab2_1 {
    width: 100%;
  }

  .tab2_h2 {
    font-size: 28px;
    text-align: center;
  }

  .tab2_1>p {
    text-align: center;
  }

  .tab2_1_1 {
    justify-content: center;
  }

  .tab2_1_2 {
    display: none;
  }

  .tab2_1_5 {
    flex-direction: column;
  }

  .tab2_1_6 {
    margin-left: 0;
  }

  .tab2_1_5>p {
    margin: 1rem 0 1rem 0;
  }

  .tab2_1_8 {
    flex-direction: column;
  }

  .tab2_1_8>p {
    margin: 1rem 0 1rem 0;
  }

  .tab2_1_10 {
    margin-left: 0;
  }

  .tab2_1_13 {
    left: 45%;
  }

  .tab2_1_14 {
    flex-direction: column;
  }

  .tab2_1_15 {
    padding: 1rem 0 0 1rem;
    width: 99%;
    display: flex;
    flex-direction: column;
    overflow: hidden;
    align-items: center;
  }

  .tab2_1_17>video {
    width: 95%;
  }

  .tab_3 {
    width: 100%;
  }

  .tab3_1 {
    width: 95%;
  }

  .tab5_1 {
    width: 100%;
  }

  .tab5_2 {
    text-align: center;
    line-height: 20px;
    font-size: 16px;
  }

  .tab5_1>h1 {
    text-align: center;
    font-size: 30px;
  }

  .tab5_3>img {
    width: 30px;
    height: 30px;
  }

  .tab5_3 {
    font-size: 20px;
    justify-content: center;
  }

  .tab5_8 {
    margin-right: 0rem !important;
    margin-bottom: 2rem;
  }

  .tab5_6 {
    font-size: 14px;
  }

  .tab5_7 {
    align-items: center;
    flex-direction: column;
  }

  .xuan {
    justify-content: space-around;
  }

  .xuan>p {
    margin-right: 0rem;
  }

  .suzi {
    /* display:none; */
    max-width: 1500px;
    width: 100%;
    margin: 0 auto;
    color: white;
    display: flex;
    padding-top: 4rem;
    text-align: center;
    padding-bottom: 5rem;
    flex-direction: column;
    align-items: center;
  }

  .suzi>div {
    margin: 1rem 0 1rem 0;
  }

  .suzi_2 {
    align-items: center;
  }

  .bakes {
    width: 100%;

  }
.bakes_1>img{
  display:none;
}
.bakes_1>h1{
  font-size: 28px;
}
.bakes_2{
  width: 100%;
  text-align: center;
}
.bakes_3{
  justify-content: center;
}
.tbiao_p{
  justify-content: space-around
}
.tbiao_p>p:nth-child(1){
  margin-right: 0rem;
}
.tbiao_p>p:nth-child(2){
  margin-right: 0rem;
}

.bakes_11{
  flex-direction: column;
}
.bakes_6{
  margin-bottom: 1.5rem;
}
  .Feature {
    /* display: none; */

  }

  .pop {
    width: 100%;
    /* display: none; */
    flex-direction: column;
  }
  .pop_1{
    width: 98%;
    flex-direction: column;
  }
  .pop_6{
    width: 98%;
  }
  .pop_7{
    width: 100%;
    display: flex;
    justify-content: space-around;
    flex-direction: column;
  }
  .pop_8{
    width: 100%;
    margin-bottom:2rem;
  }
  .pop_10{
    flex-direction: column;
  }
  .pop_11{
    width: 100%;
  }
  .pop_11>img{
    position: absolute;
    width: 750px;
    height: 700px;
    bottom: -35%;
    left: -55%;
    z-index: 0;
  }
  .pop_13>div{
    padding: 1rem 2.5rem 1rem 2.5rem;
    background-color: #2a2a2a;
    font-family: thiys;
    border-radius: 30px;
    font-weight: 500;
    font-size: 14px;
  }
  .pop_14{
    width:100%;
  }
  .Roadmap {
    /* width:100% */
    display: none;
  }
  .Media {
    display: none !important;
  }
}
</style>
