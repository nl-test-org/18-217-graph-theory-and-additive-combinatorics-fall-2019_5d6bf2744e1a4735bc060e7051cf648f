---
about_this_resource_text: "<p><strong>Description:</strong> Continuing the discussion\
  \ of graph limits, Professor Zhao explains how graph limits can be used to generate\
  \ random graphs, and also some key tools in the theory of graph limits, including\
  \ the counting lemma, weak regularity lemma, and the martingale convergence theorem.\r\
  \n\r\n</p>\r\n<p><strong>Instructor:</strong> Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: 9gy-CAwx0Ls
  parent_uid: d72a3b463b189e73cc9080898262bc82
  title: Video-YouTube-Stream
  type: Video
  uid: 7bd217441d388fc4bafba4d1b9050840
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/9gy-CAwx0Ls/default.jpg
  parent_uid: d72a3b463b189e73cc9080898262bc82
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f7e1606d65c2122607a8bdd03bffadb9
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 9gy-CAwx0Ls
  parent_uid: d72a3b463b189e73cc9080898262bc82
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5515da680e3299ea820e2095ea9be0b8
- id: 9gy-CAwx0Ls.srt
  parent_uid: d72a3b463b189e73cc9080898262bc82
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-15-graph-limits-ii-regularity-and-counting/9gy-CAwx0Ls.srt
  title: 3play caption file
  type: null
  uid: d97e44b0e14a9b3cd9da067cd4e508fb
- id: 9gy-CAwx0Ls.pdf
  parent_uid: d72a3b463b189e73cc9080898262bc82
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-15-graph-limits-ii-regularity-and-counting/9gy-CAwx0Ls.pdf
  title: 3play pdf file
  type: null
  uid: 5b7ba6665dc25e6d98854b8d860effe3
- id: Caption-3Play YouTube id-SRT
  parent_uid: d72a3b463b189e73cc9080898262bc82
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 206d4a2d54d2fd89c6148f285cf3dacf
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d72a3b463b189e73cc9080898262bc82
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 37309b23e2818201d7f6f40be5456280
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec15_300k.mp4
  parent_uid: d72a3b463b189e73cc9080898262bc82
  title: Video-Internet Archive-MP4
  type: Video
  uid: 8d9a31053889b10cabce5a6ee5d78323
inline_embed_id: 68649663lecture15graphlimitsiiregularityandcounting26969217
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-15-graph-limits-ii-regularity-and-counting
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-15-graph-limits-ii-regularity-and-counting
template_type: Tabbed
title: "Lecture 15: Graph Limits II: Regularity and Counting \t"
transcript: "<p><span m=\"489\">[SQUEAKING]</span></p><p>&nbsp;</p><p><span m=\"18590\"\
  >PROFESSOR:</span> <span m=\"18710\">Last</span> <span m=\"18830\">time,</span>\
  \ <span m=\"19040\">we</span> <span m=\"19160\">started</span> <span m=\"19520\"\
  >discussing</span> <span m=\"20090\">graph</span> <span m=\"20480\">limits.</span>\
  \ <span m=\"21720\">And</span> <span m=\"21890\">let</span> <span m=\"21980\">me</span>\
  \ <span m=\"22100\">remind</span> <span m=\"22460\">you</span> <span m=\"22610\"\
  >some</span> <span m=\"22850\">of</span> <span m=\"22970\">the</span> <span m=\"\
  23630\">notions</span> <span m=\"24200\">and</span> <span m=\"24290\">definitions</span>\
  \ <span m=\"25160\">that</span> <span m=\"25280\">were</span> <span m=\"25430\"\
  >involved.</span></p><p><span m=\"35590\">One</span> <span m=\"35670\">of</span>\
  \ <span m=\"35760\">the</span> <span m=\"35850\">main</span> <span m=\"36150\">objects</span>\
  \ <span m=\"36600\">in</span> <span m=\"36690\">graph</span> <span m=\"36990\">limits</span>\
  \ <span m=\"37490\">is</span> <span m=\"37670\">that</span> <span m=\"37830\">of</span>\
  \ <span m=\"37950\">a</span> <span m=\"38010\">graphon,</span> <span m=\"42260\"\
  >which</span> <span m=\"43070\">are</span> <span m=\"44570\">symmetric,</span> <span\
  \ m=\"45290\">measurable</span> <span m=\"45800\">functions</span> <span m=\"46670\"\
  >from</span> <span m=\"47030\">the</span> <span m=\"47150\">unit</span> <span m=\"\
  47420\">squared</span> <span m=\"48140\">to</span> <span m=\"48500\">the</span>\
  \ <span m=\"48680\">unit</span> <span m=\"49070\">interval.</span> <span m=\"58890\"\
  >So</span> <span m=\"58970\">here,</span> <span m=\"59190\">symmetric</span> <span\
  \ m=\"59870\">means</span> <span m=\"60200\">that</span> <span m=\"60770\">w</span>\
  \ <span m=\"61170\">of</span> <span m=\"61340\">x,</span> <span m=\"61580\">comma,</span>\
  \ <span m=\"61880\">y</span> <span m=\"62570\">equals</span> <span m=\"62990\">to</span>\
  \ <span m=\"63210\">w</span> <span m=\"63560\">of</span> <span m=\"63680\">y,</span>\
  \ <span m=\"63950\">comma,</span> <span m=\"64310\">x.</span></p><p><span m=\"69810\"\
  >We</span> <span m=\"69930\">define</span> <span m=\"70290\">a</span> <span m=\"\
  70350\">notion</span> <span m=\"70680\">of</span> <span m=\"70800\">convergence</span>\
  \ <span m=\"71520\">for</span> <span m=\"72210\">a</span> <span m=\"72270\">sequence</span>\
  \ <span m=\"72690\">of</span> <span m=\"72780\">graphons.</span> <span m=\"73980\"\
  >And</span> <span m=\"74040\">remember,</span> <span m=\"74370\">the</span> <span\
  \ m=\"74490\">notion</span> <span m=\"74850\">of</span> <span m=\"74940\">convergence</span>\
  \ <span m=\"81080\">is</span> <span m=\"81260\">that</span> <span m=\"82060\">a</span>\
  \ <span m=\"82130\">sequence</span> <span m=\"84380\">is</span> <span m=\"84890\"\
  >convergent</span> <span m=\"89370\">if</span> <span m=\"90390\">the</span> <span\
  \ m=\"90720\">sequence</span> <span m=\"91350\">of</span> <span m=\"92330\">homomorphism</span>\
  \ <span m=\"93330\">densities</span> <span m=\"95400\">converges</span> <span m=\"\
  99120\">as</span> <span m=\"99580\">n</span> <span m=\"99680\">goes</span> <span\
  \ m=\"100010\">to</span> <span m=\"100100\">infinity</span> <span m=\"100970\">for</span>\
  \ <span m=\"102020\">every</span> <span m=\"102440\">fixed</span> <span m=\"103330\"\
  >F,</span> <span m=\"104790\">every</span> <span m=\"104990\">fixed</span> <span\
  \ m=\"105350\">graph.</span></p><p><span m=\"109480\">So</span> <span m=\"109600\"\
  >this</span> <span m=\"109750\">is</span> <span m=\"109840\">how</span> <span m=\"\
  110020\">we</span> <span m=\"110140\">define</span> <span m=\"110590\">convergence.</span>\
  \ <span m=\"112180\">So</span> <span m=\"112240\">a</span> <span m=\"112300\">sequence</span>\
  \ <span m=\"112750\">of</span> <span m=\"112840\">graphs</span> <span m=\"113230\"\
  >or</span> <span m=\"113320\">graphons,</span> <span m=\"113920\">they</span> <span\
  \ m=\"114070\">converge</span> <span m=\"114970\">if</span> <span m=\"115300\">all</span>\
  \ <span m=\"115540\">the</span> <span m=\"117010\">homomorphism</span> <span m=\"\
  117730\">densities--</span> <span m=\"118360\">so</span> <span m=\"118510\">you</span>\
  \ <span m=\"118600\">should</span> <span m=\"118750\">think</span> <span m=\"118930\"\
  >of</span> <span m=\"119050\">this</span> <span m=\"119230\">as</span> <span m=\"\
  119710\">subgraph</span> <span m=\"120240\">statistics--</span> <span m=\"121200\"\
  >if</span> <span m=\"121360\">all</span> <span m=\"121510\">of</span> <span m=\"\
  121570\">these</span> <span m=\"121720\">statistics</span> <span m=\"122440\">converge.</span>\
  \ <span m=\"124520\">We</span> <span m=\"124630\">also</span> <span m=\"124900\"\
  >say</span> <span m=\"125230\">that</span> <span m=\"125860\">a</span> <span m=\"\
  125920\">sequence</span> <span m=\"126940\">converges</span> <span m=\"127600\"\
  >to</span> <span m=\"127900\">a</span> <span m=\"128080\">particular</span> <span\
  \ m=\"129160\">limit</span> <span m=\"130180\">if</span> <span m=\"132790\">these</span>\
  \ <span m=\"133090\">homomorphism</span> <span m=\"133810\">densities</span> <span\
  \ m=\"135310\">converge</span> <span m=\"136180\">to</span> <span m=\"137290\">the</span>\
  \ <span m=\"137410\">corresponding</span> <span m=\"138940\">homomorphism</span>\
  \ <span m=\"139570\">density</span> <span m=\"140170\">of</span> <span m=\"140380\"\
  >the</span> <span m=\"140500\">limit</span> <span m=\"141250\">for</span> <span\
  \ m=\"141430\">every</span> <span m=\"141700\">F.</span></p><p><span m=\"144790\"\
  >OK.</span> <span m=\"145010\">So</span> <span m=\"145130\">this</span> <span m=\"\
  145310\">is</span> <span m=\"145430\">how</span> <span m=\"145580\">we</span> <span\
  \ m=\"145670\">define</span> <span m=\"146030\">convergence.</span> <span m=\"147740\"\
  >We</span> <span m=\"147890\">also</span> <span m=\"148130\">define</span> <span\
  \ m=\"148490\">this</span> <span m=\"148670\">notion</span> <span m=\"149240\">of</span>\
  \ <span m=\"149450\">a</span> <span m=\"149570\">distance.</span> <span m=\"153140\"\
  >And</span> <span m=\"153340\">to</span> <span m=\"153520\">do</span> <span m=\"\
  153670\">that,</span> <span m=\"153880\">we</span> <span m=\"154000\">first</span>\
  \ <span m=\"154300\">define</span> <span m=\"154700\">the</span> <span m=\"154780\"\
  >cut</span> <span m=\"155170\">norm</span> <span m=\"156220\">to</span> <span m=\"\
  156370\">be</span> <span m=\"159560\">the</span> <span m=\"159650\">following</span>\
  \ <span m=\"160100\">quantity</span> <span m=\"161420\">defined</span> <span m=\"\
  161900\">by</span> <span m=\"162170\">taking</span> <span m=\"163910\">two</span>\
  \ <span m=\"164390\">subsets,</span> <span m=\"165440\">S</span> <span m=\"165755\"\
  >and T,</span> <span m=\"167060\">which</span> <span m=\"167300\">are</span> <span\
  \ m=\"168050\">measurable.</span> <span m=\"169340\">Everything</span> <span m=\"\
  170030\">so</span> <span m=\"170210\">far</span> <span m=\"170420\">is</span> <span\
  \ m=\"170510\">going</span> <span m=\"170660\">to</span> <span m=\"170720\">be</span>\
  \ <span m=\"170810\">measurable.</span> <span m=\"171890\">And</span> <span m=\"\
  172310\">look</span> <span m=\"172550\">at</span> <span m=\"172880\">what</span>\
  \ <span m=\"173090\">is</span> <span m=\"173180\">the</span> <span m=\"173270\"\
  >maximum</span> <span m=\"173810\">possible</span> <span m=\"174380\">deviation</span>\
  \ <span m=\"175820\">of</span> <span m=\"176180\">the</span> <span m=\"176330\"\
  >integral</span> <span m=\"177020\">of</span> <span m=\"177140\">this</span> <span\
  \ m=\"177320\">function</span> <span m=\"177950\">on</span> <span m=\"178190\">this</span>\
  \ <span m=\"178400\">box,</span> <span m=\"178820\">S</span> <span m=\"179060\"\
  >cross</span> <span m=\"179450\">T.</span></p><p><span m=\"180350\">And</span> <span\
  \ m=\"180470\">here,</span> <span m=\"180710\">w,</span> <span m=\"181160\">you\
  \ should</span> <span m=\"181310\">think</span> <span m=\"181490\">of</span> <span\
  \ m=\"181580\">it</span> <span m=\"181700\">as</span> <span m=\"181850\">taking</span>\
  \ <span m=\"182510\">real</span> <span m=\"182840\">values,</span> <span m=\"183800\"\
  >allowing</span> <span m=\"184160\">both</span> <span m=\"184460\">positive</span>\
  \ <span m=\"184970\">and</span> <span m=\"185180\">negative</span> <span m=\"185600\"\
  >values,</span> <span m=\"186350\">because</span> <span m=\"186650\">otherwise,</span>\
  \ <span m=\"187130\">you</span> <span m=\"187210\">should</span> <span m=\"187380\"\
  >just</span> <span m=\"187550\">take</span> <span m=\"187790\">S and T</span> <span\
  \ m=\"188180\">to</span> <span m=\"188270\">be</span> <span m=\"188360\">the</span>\
  \ <span m=\"188450\">whole</span> <span m=\"188660\">interval.</span> <span m=\"\
  191410\">OK.</span> <span m=\"192850\">And</span> <span m=\"193210\">this</span>\
  \ <span m=\"193630\">definition</span> <span m=\"194170\">was</span> <span m=\"\
  194380\">motivated</span> <span m=\"194950\">by</span> <span m=\"195130\">our</span>\
  \ <span m=\"195250\">discussion</span> <span m=\"195790\">of</span> <span m=\"195880\"\
  >discrepancy</span> <span m=\"196900\">coming</span> <span m=\"197200\">from</span>\
  \ <span m=\"197470\">quasi</span> <span m=\"197830\">randomness.</span></p><p><span\
  \ m=\"199620\">Now,</span> <span m=\"199960\">if</span> <span m=\"200090\">I</span>\
  \ <span m=\"200400\">give</span> <span m=\"200450\">you</span> <span m=\"200660\"\
  >two</span> <span m=\"200960\">graphs</span> <span m=\"201380\">or</span> <span\
  \ m=\"201470\">graphons</span> <span m=\"202280\">and</span> <span m=\"202450\"\
  >ask</span> <span m=\"202790\">you</span> <span m=\"202880\">to</span> <span m=\"\
  202970\">compare</span> <span m=\"203420\">them,</span> <span m=\"203920\">you</span>\
  \ <span m=\"204110\">are</span> <span m=\"204170\">allowed</span> <span m=\"204440\"\
  >to</span> <span m=\"205220\">permute</span> <span m=\"206090\">the</span> <span\
  \ m=\"206390\">vertices</span> <span m=\"206990\">in</span> <span m=\"207110\">some</span>\
  \ <span m=\"207350\">sense,</span> <span m=\"208550\">so</span> <span m=\"208730\"\
  >to</span> <span m=\"208820\">find</span> <span m=\"209240\">the</span> <span m=\"\
  209360\">best</span> <span m=\"209750\">overlay.</span> <span m=\"211140\">And</span>\
  \ <span m=\"211580\">that</span> <span m=\"211760\">notion</span> <span m=\"212180\"\
  >is</span> <span m=\"212330\">captured</span> <span m=\"213260\">in</span> <span\
  \ m=\"213380\">the</span> <span m=\"213440\">definition</span> <span m=\"214040\"\
  >of</span> <span m=\"214160\">cut</span> <span m=\"214520\">distance,</span> <span\
  \ m=\"219080\">which</span> <span m=\"219290\">is</span> <span m=\"219410\">defined</span>\
  \ <span m=\"219830\">to</span> <span m=\"219920\">be</span> <span m=\"220100\">the</span>\
  \ <span m=\"220190\">following</span> <span m=\"220610\">quantity,</span> <span\
  \ m=\"223060\">where</span> <span m=\"223750\">we</span> <span m=\"224560\">consider</span>\
  \ <span m=\"229330\">over</span> <span m=\"230560\">all</span> <span m=\"230740\"\
  >possible</span> <span m=\"232270\">measure-preserving</span> <span m=\"233540\"\
  >bijections</span> <span m=\"240000\">from</span> <span m=\"241800\">the</span>\
  \ <span m=\"241920\">interval</span> <span m=\"242400\">to</span> <span m=\"242720\"\
  >itself</span> <span m=\"245992\">of</span> <span m=\"249930\">the</span> <span\
  \ m=\"249990\">difference</span> <span m=\"250470\">between</span> <span m=\"251430\"\
  >these</span> <span m=\"251670\">two</span> <span m=\"252240\">graphons</span> <span\
  \ m=\"253140\">if</span> <span m=\"253290\">I</span> <span m=\"253410\">rotate</span>\
  \ <span m=\"254130\">one</span> <span m=\"254370\">of</span> <span m=\"254460\"\
  >them</span> <span m=\"255780\">using</span> <span m=\"256839\">this</span> <span\
  \ m=\"257230\">measure-preserving</span> <span m=\"258130\">bijection.</span> <span\
  \ m=\"266460\">So</span> <span m=\"266640\">think</span> <span m=\"266880\">of</span>\
  \ <span m=\"266970\">this</span> <span m=\"267210\">as</span> <span m=\"268200\"\
  >permuting</span> <span m=\"268770\">the</span> <span m=\"268890\">vertices.</span></p><p><span\
  \ m=\"276130\">So</span> <span m=\"276310\">these</span> <span m=\"276580\">were</span>\
  \ <span m=\"276760\">the</span> <span m=\"277300\">definitions</span> <span m=\"\
  277960\">that</span> <span m=\"278110\">were</span> <span m=\"278260\">involved</span>\
  \ <span m=\"278700\">last</span> <span m=\"279010\">time.</span> <span m=\"279660\"\
  >And</span> <span m=\"279850\">at</span> <span m=\"279940\">the</span> <span m=\"\
  280060\">end</span> <span m=\"280330\">of</span> <span m=\"280450\">last</span>\
  \ <span m=\"280810\">lecture,</span> <span m=\"281260\">I</span> <span m=\"281410\"\
  >stated</span> <span m=\"281890\">three</span> <span m=\"282250\">main</span> <span\
  \ m=\"282610\">theorems</span> <span m=\"283150\">of</span> <span m=\"283300\">graph</span>\
  \ <span m=\"283600\">limit</span> <span m=\"283870\">theory.</span> <span m=\"285060\"\
  >So</span> <span m=\"285160\">I</span> <span m=\"285220\">forgot</span> <span m=\"\
  285460\">to</span> <span m=\"285520\">mention</span> <span m=\"286740\">what</span>\
  \ <span m=\"287020\">are</span> <span m=\"287080\">some</span> <span m=\"287230\"\
  >of</span> <span m=\"287290\">the</span> <span m=\"287350\">histories</span> <span\
  \ m=\"287800\">of</span> <span m=\"288140\">this</span> <span m=\"288640\">theory.</span></p><p><span\
  \ m=\"289820\">So</span> <span m=\"290410\">there</span> <span m=\"290590\">were</span>\
  \ <span m=\"290800\">a</span> <span m=\"291220\">number</span> <span m=\"291490\"\
  >of</span> <span m=\"291610\">important</span> <span m=\"291970\">papers</span>\
  \ <span m=\"292360\">that</span> <span m=\"292930\">developed</span> <span m=\"\
  294010\">this</span> <span m=\"294460\">very</span> <span m=\"294730\">idea</span>\
  \ <span m=\"295120\">of</span> <span m=\"295270\">graph</span> <span m=\"295540\"\
  >limits,</span> <span m=\"296230\">which</span> <span m=\"296440\">is</span> <span\
  \ m=\"296920\">actually</span> <span m=\"297250\">somewhat--</span> <span m=\"297850\"\
  >if</span> <span m=\"298000\">you</span> <span m=\"298090\">think</span> <span m=\"\
  298240\">about</span> <span m=\"298810\">all</span> <span m=\"298960\">of</span>\
  \ <span m=\"299050\">combinatorics,</span> <span m=\"300100\">we</span> <span m=\"\
  300220\">like</span> <span m=\"300340\">to</span> <span m=\"300430\">deal</span>\
  \ <span m=\"300640\">with</span> <span m=\"301240\">discrete</span> <span m=\"301930\"\
  >objects.</span> <span m=\"302830\">And</span> <span m=\"303010\">even</span> <span\
  \ m=\"303190\">the</span> <span m=\"303280\">idea</span> <span m=\"303610\">of</span>\
  \ <span m=\"303730\">taking</span> <span m=\"304090\">a</span> <span m=\"304150\"\
  >limit</span> <span m=\"304600\">is</span> <span m=\"305050\">rather</span> <span\
  \ m=\"305410\">novel.</span> <span m=\"306610\">So</span> <span m=\"307780\">this</span>\
  \ <span m=\"308020\">work</span> <span m=\"308650\">is</span> <span m=\"309010\"\
  >due</span> <span m=\"309190\">to</span> <span m=\"310060\">a</span> <span m=\"\
  310120\">number</span> <span m=\"310420\">of</span> <span m=\"310480\">people.</span></p><p><span\
  \ m=\"311830\">In</span> <span m=\"311920\">particular,</span> <span m=\"312570\"\
  >Laszlo</span> <span m=\"313120\">Lovasz</span> <span m=\"313660\">played</span>\
  \ <span m=\"313990\">a</span> <span m=\"314080\">very</span> <span m=\"314380\"\
  >important</span> <span m=\"314830\">central</span> <span m=\"315190\">role</span>\
  \ <span m=\"315460\">in</span> <span m=\"315550\">the</span> <span m=\"315640\"\
  >development</span> <span m=\"316150\">of</span> <span m=\"316270\">this</span>\
  \ <span m=\"316450\">theory.</span> <span m=\"317200\">And</span> <span m=\"318010\"\
  >various</span> <span m=\"318370\">people</span> <span m=\"318670\">came</span>\
  \ <span m=\"318910\">to</span> <span m=\"319060\">this</span> <span m=\"319240\"\
  >theory</span> <span m=\"319480\">from</span> <span m=\"319750\">different</span>\
  \ <span m=\"320080\">perspectives--</span> <span m=\"321100\">some</span> <span\
  \ m=\"321460\">from</span> <span m=\"321760\">more</span> <span m=\"322240\">pure</span>\
  \ <span m=\"322930\">perspectives,</span> <span m=\"323830\">and</span> <span m=\"\
  323950\">some</span> <span m=\"324160\">from</span> <span m=\"324340\">more</span>\
  \ <span m=\"324700\">applied</span> <span m=\"325210\">perspectives.</span> <span\
  \ m=\"326290\">And</span> <span m=\"326590\">this</span> <span m=\"326770\">theory</span>\
  \ <span m=\"326950\">is</span> <span m=\"327040\">now</span> <span m=\"327250\"\
  >getting</span> <span m=\"327520\">used</span> <span m=\"327940\">in</span> <span\
  \ m=\"328450\">more</span> <span m=\"328630\">and</span> <span m=\"328720\">more</span>\
  \ <span m=\"328840\">places,</span> <span m=\"329810\">including</span> <span m=\"\
  331030\">statistics,</span> <span m=\"331790\">machine</span> <span m=\"331990\"\
  >learning,</span> <span m=\"332420\">and</span> <span m=\"332440\">so</span> <span\
  \ m=\"332680\">on.</span> <span m=\"333030\">And</span> <span m=\"333160\">I'll</span>\
  \ <span m=\"333580\">explain</span> <span m=\"334090\">where</span> <span m=\"334810\"\
  >that</span> <span m=\"335020\">comes</span> <span m=\"335350\">up</span> <span\
  \ m=\"335500\">just</span> <span m=\"335710\">a</span> <span m=\"335770\">little</span>\
  \ <span m=\"335950\">bit.</span></p><p><span m=\"337990\">At</span> <span m=\"338080\"\
  >the</span> <span m=\"338200\">end</span> <span m=\"338320\">of</span> <span m=\"\
  338410\">last</span> <span m=\"338680\">lecture,</span> <span m=\"339010\">I</span>\
  \ <span m=\"339140\">stated</span> <span m=\"339550\">three</span> <span m=\"339850\"\
  >main</span> <span m=\"340090\">theorems.</span> <span m=\"340870\">And</span> <span\
  \ m=\"341650\">what</span> <span m=\"341890\">I</span> <span m=\"341980\">want</span>\
  \ <span m=\"342160\">to</span> <span m=\"342220\">do</span> <span m=\"342340\">today</span>\
  \ <span m=\"342640\">is</span> <span m=\"342820\">develop</span> <span m=\"343240\"\
  >some</span> <span m=\"343570\">tools</span> <span m=\"344560\">so</span> <span\
  \ m=\"344770\">that</span> <span m=\"344980\">we</span> <span m=\"345160\">can</span>\
  \ <span m=\"345760\">prove</span> <span m=\"346210\">those</span> <span m=\"346510\"\
  >theorems</span> <span m=\"346900\">in</span> <span m=\"347020\">the</span> <span\
  \ m=\"347080\">next</span> <span m=\"347410\">lecture.</span> <span m=\"348125\"\
  >OK. So</span> <span m=\"348430\">I</span> <span m=\"348520\">want</span> <span\
  \ m=\"348670\">to</span> <span m=\"348730\">develop</span> <span m=\"349030\">some</span>\
  \ <span m=\"349210\">tools.</span></p><p><span m=\"349910\">In</span> <span m=\"\
  349990\">particular,</span> <span m=\"350410\">you'll</span> <span m=\"350620\"\
  >see</span> <span m=\"350980\">some</span> <span m=\"351400\">of</span> <span m=\"\
  351460\">the</span> <span m=\"351550\">things</span> <span m=\"351880\">that</span>\
  \ <span m=\"352000\">we've</span> <span m=\"352180\">talked</span> <span m=\"352510\"\
  >about</span> <span m=\"353080\">in</span> <span m=\"353200\">the</span> <span m=\"\
  353260\">chapter</span> <span m=\"353710\">on</span> <span m=\"354220\">Szemer\xE9\
  di's</span> <span m=\"354850\">regularity</span> <span m=\"355450\">lemma</span>\
  \ <span m=\"355960\">come</span> <span m=\"356200\">up</span> <span m=\"356320\"\
  >again</span> <span m=\"357580\">in</span> <span m=\"357730\">a</span> <span m=\"\
  357790\">slightly</span> <span m=\"358150\">different</span> <span m=\"358450\"\
  >language.</span> <span m=\"359140\">So</span> <span m=\"359350\">much</span> <span\
  \ m=\"359710\">of</span> <span m=\"359770\">what</span> <span m=\"359980\">I</span>\
  \ <span m=\"360070\">will</span> <span m=\"360220\">say</span> <span m=\"360460\"\
  >today</span> <span m=\"361060\">hopefully</span> <span m=\"361450\">should</span>\
  \ <span m=\"361660\">already</span> <span m=\"362320\">be</span> <span m=\"362500\"\
  >familiar</span> <span m=\"362980\">to</span> <span m=\"363130\">you,</span> <span\
  \ m=\"363670\">but</span> <span m=\"363790\">you</span> <span m=\"363910\">will</span>\
  \ <span m=\"364000\">see</span> <span m=\"364270\">it</span> <span m=\"364360\"\
  >again</span> <span m=\"364660\">from</span> <span m=\"364930\">the</span> <span\
  \ m=\"365020\">perspective</span> <span m=\"365590\">of</span> <span m=\"365710\"\
  >graph</span> <span m=\"365980\">limits.</span></p><p><span m=\"368690\">But</span>\
  \ <span m=\"369120\">first,</span> <span m=\"369840\">before</span> <span m=\"370530\"\
  >telling</span> <span m=\"370830\">you</span> <span m=\"370920\">about</span> <span\
  \ m=\"371070\">the</span> <span m=\"371160\">tools,</span> <span m=\"371490\">I</span>\
  \ <span m=\"371550\">want</span> <span m=\"371730\">to</span> <span m=\"371790\"\
  >give</span> <span m=\"371970\">you</span> <span m=\"372060\">some</span> <span\
  \ m=\"372240\">more</span> <span m=\"372480\">examples.</span> <span m=\"375580\"\
  >So</span> <span m=\"375660\">one</span> <span m=\"375870\">of</span> <span m=\"\
  375930\">the</span> <span m=\"376050\">ways</span> <span m=\"376290\">that I</span>\
  \ <span m=\"376410\">motivated</span> <span m=\"377400\">graph</span> <span m=\"\
  377670\">limits</span> <span m=\"377970\">last</span> <span m=\"378210\">time</span>\
  \ <span m=\"378720\">is</span> <span m=\"378960\">this</span> <span m=\"379140\"\
  >example</span> <span m=\"379590\">of</span> <span m=\"379830\">an</span> <span\
  \ m=\"380460\">Erdos-Renyi</span> <span m=\"381060\">random</span> <span m=\"381390\"\
  >graph</span> <span m=\"382380\">or a</span> <span m=\"382680\">sequence</span>\
  \ <span m=\"383100\">of</span> <span m=\"383190\">quasi-random</span> <span m=\"\
  383790\">graphs</span> <span m=\"384420\">converging</span> <span m=\"385470\">to</span>\
  \ <span m=\"385650\">a</span> <span m=\"385710\">constant.</span> <span m=\"386540\"\
  >The</span> <span m=\"386700\">constant</span> <span m=\"387230\">graphon</span>\
  \ <span m=\"387550\">is</span> <span m=\"388140\">the</span> <span m=\"388260\"\
  >limit.</span></p><p><span m=\"390690\">But</span> <span m=\"390810\">what</span>\
  \ <span m=\"390940\">about</span> <span m=\"391080\">generalizations?</span> <span\
  \ m=\"392170\">What</span> <span m=\"392340\">about</span> <span m=\"392520\">generalizations</span>\
  \ <span m=\"393270\">of</span> <span m=\"393360\">that</span> <span m=\"393480\"\
  >construction</span> <span m=\"394410\">when</span> <span m=\"394590\">your</span>\
  \ <span m=\"395010\">limit</span> <span m=\"395340\">is</span> <span m=\"395520\"\
  >not</span> <span m=\"395850\">the</span> <span m=\"395970\">constant?</span> <span\
  \ m=\"397500\">So</span> <span m=\"397680\">this</span> <span m=\"398040\">leads</span>\
  \ <span m=\"398310\">to</span> <span m=\"399120\">this</span> <span m=\"399330\"\
  >idea</span> <span m=\"399600\">of</span> <span m=\"399690\">a</span> <span m=\"\
  399780\">w</span> <span m=\"400410\">random</span> <span m=\"400920\">graph,</span>\
  \ <span m=\"403290\">which</span> <span m=\"403530\">generalizes</span> <span m=\"\
  405060\">that</span> <span m=\"405240\">of</span> <span m=\"405330\">an</span> <span\
  \ m=\"405450\">Erdos-Renyi</span> <span m=\"406410\">random</span> <span m=\"406770\"\
  >graph.</span></p><p><span m=\"409250\">So</span> <span m=\"409420\">in</span> <span\
  \ m=\"409540\">Erdos-Renyi,</span> <span m=\"415630\">we're</span> <span m=\"415750\"\
  >looking</span> <span m=\"416140\">at</span> <span m=\"417280\">every</span> <span\
  \ m=\"417580\">edge</span> <span m=\"417940\">occurring</span> <span m=\"418390\"\
  >with</span> <span m=\"418600\">the</span> <span m=\"418720\">same</span> <span\
  \ m=\"419110\">probability,</span> <span m=\"419860\">p,</span> <span m=\"420880\"\
  >uniform</span> <span m=\"421390\">throughout</span> <span m=\"421900\">the</span>\
  \ <span m=\"422050\">graph.</span> <span m=\"423260\">But</span> <span m=\"423920\"\
  >what</span> <span m=\"424130\">I</span> <span m=\"424190\">want</span> <span m=\"\
  424340\">to</span> <span m=\"424430\">do</span> <span m=\"424550\">now</span> <span\
  \ m=\"424850\">is</span> <span m=\"425180\">allow</span> <span m=\"425540\">you</span>\
  \ <span m=\"425660\">to</span> <span m=\"425810\">change</span> <span m=\"426830\"\
  >the</span> <span m=\"427010\">edge</span> <span m=\"427250\">probability</span>\
  \ <span m=\"428030\">somewhat.</span> <span m=\"428980\">OK.</span></p><p><span\
  \ m=\"432290\">So before</span> <span m=\"432530\">giving</span> <span m=\"432760\"\
  >you</span> <span m=\"432880\">the</span> <span m=\"432950\">more</span> <span m=\"\
  433130\">general</span> <span m=\"433490\">definition,</span> <span m=\"434330\"\
  >a</span> <span m=\"434390\">special</span> <span m=\"434750\">case</span> <span\
  \ m=\"435020\">of</span> <span m=\"435110\">this</span> <span m=\"435350\">is</span>\
  \ <span m=\"436280\">an</span> <span m=\"436400\">important</span> <span m=\"438440\"\
  >model</span> <span m=\"439160\">of</span> <span m=\"439310\">random</span> <span\
  \ m=\"439670\">graphs</span> <span m=\"440090\">known</span> <span m=\"440350\"\
  >as</span> <span m=\"440480\">the</span> <span m=\"440600\">stochastic</span> <span\
  \ m=\"441380\">block</span> <span m=\"441770\">model.</span> <span m=\"445802\"\
  >And</span> <span m=\"446270\">in</span> <span m=\"446330\">particular,</span> <span\
  \ m=\"447590\">a</span> <span m=\"448100\">two-block</span> <span m=\"448970\">model</span>\
  \ <span m=\"449600\">consists</span> <span m=\"450560\">of</span> <span m=\"450770\"\
  >the</span> <span m=\"450860\">following</span> <span m=\"451700\">data</span> <span\
  \ m=\"452950\">where</span> <span m=\"453670\">I</span> <span m=\"453890\">am</span>\
  \ <span m=\"454040\">looking</span> <span m=\"454610\">at</span> <span m=\"457980\"\
  >two</span> <span m=\"458220\">types</span> <span m=\"458640\">of</span> <span m=\"\
  458700\">vertices--</span> <span m=\"464750\">let's</span> <span m=\"464800\">call</span>\
  \ <span m=\"464980\">them</span> <span m=\"465190\">red</span> <span m=\"465580\"\
  >and</span> <span m=\"465700\">blue--</span> <span m=\"469650\">where</span> <span\
  \ m=\"471390\">the</span> <span m=\"471630\">vertices</span> <span m=\"472860\"\
  >are</span> <span m=\"473010\">assigned</span> <span m=\"473610\">to</span> <span\
  \ m=\"473740\">colors</span> <span m=\"474210\">at</span> <span m=\"474360\">random--</span>\
  \ <span m=\"481570\">for</span> <span m=\"481750\">example,</span> <span m=\"482170\"\
  >50/50.</span> <span m=\"483050\">But</span> <span m=\"483190\">any</span> <span\
  \ m=\"483280\">other</span> <span m=\"483460\">probability</span> <span m=\"484060\"\
  >is</span> <span m=\"484210\">fine.</span></p><p><span m=\"485690\">And</span> <span\
  \ m=\"485790\">now</span> <span m=\"486130\">I</span> <span m=\"486880\">put</span>\
  \ <span m=\"487090\">down</span> <span m=\"487300\">the</span> <span m=\"487450\"\
  >edges</span> <span m=\"488290\">according</span> <span m=\"488770\">to</span> <span\
  \ m=\"489160\">which</span> <span m=\"489460\">colors</span> <span m=\"490330\"\
  >the</span> <span m=\"490420\">two</span> <span m=\"490660\">endpoints</span> <span\
  \ m=\"491220\">are.</span> <span m=\"492340\">So</span> <span m=\"492460\">two</span>\
  \ <span m=\"494920\">red</span> <span m=\"495130\">vertices</span> <span m=\"496240\"\
  >are</span> <span m=\"496330\">joined</span> <span m=\"498400\">with</span> <span\
  \ m=\"499410\">edge</span> <span m=\"499630\">probability</span> <span m=\"500980\"\
  >Prr.</span> <span m=\"503500\">If</span> <span m=\"503650\">I</span> <span m=\"\
  503740\">have</span> <span m=\"504040\">a</span> <span m=\"504280\">red</span> <span\
  \ m=\"505000\">and a</span> <span m=\"505150\">blue,</span> <span m=\"506350\">then</span>\
  \ <span m=\"506830\">I</span> <span m=\"506920\">may</span> <span m=\"507100\">have</span>\
  \ <span m=\"507250\">a</span> <span m=\"507310\">different</span> <span m=\"507940\"\
  >probability</span> <span m=\"510580\">joining</span> <span m=\"510910\">them,</span>\
  \ <span m=\"511630\">and</span> <span m=\"511810\">likewise</span> <span m=\"512380\"\
  >with</span> <span m=\"512590\">blue-blue,</span> <span m=\"515679\">like</span>\
  \ <span m=\"515890\">that.</span> <span m=\"518400\">So</span> <span m=\"518440\"\
  >in</span> <span m=\"518530\">other</span> <span m=\"518679\">words,</span> <span\
  \ m=\"518990\">I</span> <span m=\"519090\">can</span> <span m=\"519130\">encode</span>\
  \ <span m=\"519580\">this</span> <span m=\"519760\">probability</span> <span m=\"\
  520330\">information</span> <span m=\"520960\">in</span> <span m=\"521049\">the</span>\
  \ <span m=\"521110\">matrix,</span> <span m=\"529990\">like</span> <span m=\"530140\"\
  >that.</span> <span m=\"530890\">So</span> <span m=\"531310\">it's</span> <span\
  \ m=\"531450\">symmetric</span> <span m=\"532150\">across</span> <span m=\"532510\"\
  >the</span> <span m=\"532600\">diagonal.</span></p><p><span m=\"534800\">So</span>\
  \ <span m=\"535000\">this</span> <span m=\"535210\">is</span> <span m=\"535360\"\
  >a</span> <span m=\"535540\">slightly</span> <span m=\"536020\">more</span> <span\
  \ m=\"536200\">general</span> <span m=\"536710\">version</span> <span m=\"537220\"\
  >of</span> <span m=\"538150\">an</span> <span m=\"538480\">Erdos-Renyi</span> <span\
  \ m=\"538780\">random</span> <span m=\"539090\">graph</span> <span m=\"539410\"\
  >where</span> <span m=\"539640\">now</span> <span m=\"539890\">I</span> <span m=\"\
  539950\">have</span> <span m=\"540160\">potentially</span> <span m=\"540640\">different</span>\
  \ <span m=\"540910\">types</span> <span m=\"541330\">of</span> <span m=\"541450\"\
  >vertices.</span> <span m=\"542320\">And</span> <span m=\"542410\">you</span> <span\
  \ m=\"542470\">can</span> <span m=\"542570\">imagine</span> <span m=\"543160\">these</span>\
  \ <span m=\"543400\">kinds</span> <span m=\"543670\">of</span> <span m=\"543730\"\
  >models</span> <span m=\"544090\">are</span> <span m=\"544180\">very</span> <span\
  \ m=\"544360\">important</span> <span m=\"544690\">in</span> <span m=\"544900\"\
  >applied</span> <span m=\"545230\">mathematics</span> <span m=\"546010\">for</span>\
  \ <span m=\"546190\">modeling</span> <span m=\"547030\">certain</span> <span m=\"\
  547300\">situations</span> <span m=\"547900\">such</span> <span m=\"548170\">as,</span>\
  \ <span m=\"549200\">for</span> <span m=\"549250\">example,</span> <span m=\"549740\"\
  >if</span> <span m=\"549820\">you</span> <span m=\"550120\">have</span> <span m=\"\
  552040\">people</span> <span m=\"552700\">with</span> <span m=\"553120\">different</span>\
  \ <span m=\"554110\">political</span> <span m=\"554560\">party</span> <span m=\"\
  554890\">affiliations.</span> <span m=\"556270\">How</span> <span m=\"556510\">likely</span>\
  \ <span m=\"556900\">are</span> <span m=\"556990\">they</span> <span m=\"557200\"\
  >to</span> <span m=\"557650\">talk</span> <span m=\"557920\">to</span> <span m=\"\
  558040\">each</span> <span m=\"558220\">other?</span></p><p><span m=\"559890\">So</span>\
  \ <span m=\"560370\">you</span> <span m=\"560640\">can</span> <span m=\"560790\"\
  >imagine</span> <span m=\"561300\">some</span> <span m=\"561510\">of</span> <span\
  \ m=\"561570\">these</span> <span m=\"561720\">numbers</span> <span m=\"562050\"\
  >might</span> <span m=\"562220\">be</span> <span m=\"562440\">bigger</span> <span\
  \ m=\"562770\">than</span> <span m=\"562980\">others.</span> <span m=\"564700\"\
  >And</span> <span m=\"566010\">there's an</span> <span m=\"566200\">important</span>\
  \ <span m=\"566550\">statistical</span> <span m=\"567090\">problem.</span> <span\
  \ m=\"567360\">If</span> <span m=\"567480\">I</span> <span m=\"567570\">give</span>\
  \ <span m=\"567810\">you</span> <span m=\"567990\">a</span> <span m=\"568050\">graph,</span>\
  \ <span m=\"568800\">can</span> <span m=\"569040\">you</span> <span m=\"569310\"\
  >cluster</span> <span m=\"569880\">or</span> <span m=\"570000\">classify</span>\
  \ <span m=\"571050\">the</span> <span m=\"571170\">vertices</span> <span m=\"571980\"\
  >according</span> <span m=\"572400\">to</span> <span m=\"572520\">their</span> <span\
  \ m=\"572670\">types</span> <span m=\"573330\">if</span> <span m=\"573480\">I</span>\
  \ <span m=\"573600\">do</span> <span m=\"573780\">not</span> <span m=\"574050\"\
  >show</span> <span m=\"574320\">you</span> <span m=\"574440\">in</span> <span m=\"\
  574680\">advance</span> <span m=\"575160\">what</span> <span m=\"575310\">the</span>\
  \ <span m=\"575370\">colors</span> <span m=\"575690\">are</span> <span m=\"575950\"\
  >but</span> <span m=\"576420\">show</span> <span m=\"576690\">you</span> <span m=\"\
  576810\">what</span> <span m=\"576960\">the</span> <span m=\"577080\">output</span>\
  \ <span m=\"577440\">graph</span> <span m=\"577720\">is?</span> <span m=\"579340\"\
  >So</span> <span m=\"579480\">these</span> <span m=\"579660\">are</span> <span m=\"\
  580090\">important</span> <span m=\"580500\">statistical</span> <span m=\"581040\"\
  >questions</span> <span m=\"581490\">with</span> <span m=\"582170\">lots</span>\
  \ <span m=\"582420\">of</span> <span m=\"582540\">applications.</span></p><p><span\
  \ m=\"585750\">This</span> <span m=\"585960\">is</span> <span m=\"586080\">an</span>\
  \ <span m=\"586170\">example</span> <span m=\"586650\">of</span> <span m=\"587250\"\
  >if</span> <span m=\"587370\">you</span> <span m=\"587490\">have</span> <span m=\"\
  587640\">only</span> <span m=\"587850\">two</span> <span m=\"588120\">blocks.</span>\
  \ <span m=\"588570\">But</span> <span m=\"588710\">of</span> <span m=\"588810\"\
  >course,</span> <span m=\"589020\">you</span> <span m=\"589080\">can</span> <span\
  \ m=\"589260\">have</span> <span m=\"589440\">more</span> <span m=\"589680\">than</span>\
  \ <span m=\"589830\">two</span> <span m=\"590070\">blocks.</span> <span m=\"592030\"\
  >And</span> <span m=\"592240\">the</span> <span m=\"592360\">graphon</span> <span\
  \ m=\"593980\">context</span> <span m=\"594550\">tells</span> <span m=\"594880\"\
  >us</span> <span m=\"594990\">that</span> <span m=\"595150\">we</span> <span m=\"\
  595330\">should</span> <span m=\"595480\">not</span> <span m=\"595810\">limit</span>\
  \ <span m=\"596110\">ourselves</span> <span m=\"596560\">to</span> <span m=\"597160\"\
  >just</span> <span m=\"597370\">blocks.</span> <span m=\"598540\">If</span> <span\
  \ m=\"598690\">I</span> <span m=\"598780\">give</span> <span m=\"598960\">you</span>\
  \ <span m=\"599140\">any</span> <span m=\"600130\">graphon</span> <span m=\"600790\"\
  >w,</span> <span m=\"601600\">I</span> <span m=\"601690\">can</span> <span m=\"\
  601870\">also</span> <span m=\"602200\">construct</span> <span m=\"603130\">a</span>\
  \ <span m=\"603490\">random</span> <span m=\"603880\">graph.</span></p><p><span\
  \ m=\"606040\">So</span> <span m=\"606460\">what</span> <span m=\"606610\">I</span>\
  \ <span m=\"606700\">would</span> <span m=\"606770\">like</span> <span m=\"606900\"\
  >to</span> <span m=\"607010\">do</span> <span m=\"607690\">is</span> <span m=\"\
  607900\">to</span> <span m=\"608020\">consider</span> <span m=\"608980\">the</span>\
  \ <span m=\"609070\">following</span> <span m=\"609490\">construction</span> <span\
  \ m=\"610930\">where--</span> <span m=\"612080\">OK, so</span> <span m=\"612430\"\
  >let's</span> <span m=\"612610\">just</span> <span m=\"612730\">call it w</span>\
  \ <span m=\"612970\">random</span> <span m=\"613630\">graph</span> <span m=\"617665\"\
  >denoted</span> <span m=\"619420\">by</span> <span m=\"620680\">g</span> <span m=\"\
  621340\">and</span> <span m=\"621790\">w--</span> <span m=\"623920\">where</span>\
  \ <span m=\"625180\">I</span> <span m=\"625330\">form</span> <span m=\"625600\"\
  >the</span> <span m=\"625690\">graph</span> <span m=\"626110\">using</span> <span\
  \ m=\"626350\">the</span> <span m=\"626440\">following</span> <span m=\"626950\"\
  >process.</span> <span m=\"628510\">First,</span> <span m=\"628980\">the</span>\
  \ <span m=\"629130\">vertex</span> <span m=\"629590\">set</span> <span m=\"630640\"\
  >is</span> <span m=\"631780\">labeled</span> <span m=\"632110\">by</span> <span\
  \ m=\"632590\">1</span> <span m=\"632800\">through</span> <span m=\"633040\">n.</span>\
  \ <span m=\"634480\">And</span> <span m=\"636660\">let</span> <span m=\"636750\"\
  >me</span> <span m=\"636900\">draw</span> <span m=\"638370\">the</span> <span m=\"\
  638460\">vertex</span> <span m=\"639030\">types</span> <span m=\"640230\">by</span>\
  \ <span m=\"640590\">taking</span> <span m=\"641410\">uniform</span> <span m=\"\
  641940\">random</span> <span m=\"644040\">x1</span> <span m=\"644640\">through</span>\
  \ <span m=\"644940\">xn--</span> <span m=\"646946\">OK,</span> <span m=\"647350\"\
  >so</span> <span m=\"647610\">uniform</span> <span m=\"648480\">iid.</span></p><p><span\
  \ m=\"651080\">So</span> <span m=\"651800\">you</span> <span m=\"651920\">think</span>\
  \ <span m=\"652160\">of</span> <span m=\"652250\">them</span> <span m=\"652460\"\
  >as</span> <span m=\"652640\">the</span> <span m=\"652790\">vertex</span> <span\
  \ m=\"653240\">colors,</span> <span m=\"653660\">the</span> <span m=\"653750\">vertex</span>\
  \ <span m=\"654170\">types.</span> <span m=\"655560\">And</span> <span m=\"655790\"\
  >I</span> <span m=\"655940\">put</span> <span m=\"656840\">an</span> <span m=\"\
  657020\">edge</span> <span m=\"658730\">between</span> <span m=\"660800\">i</span>\
  \ <span m=\"661370\">and</span> <span m=\"661490\">j</span> <span m=\"663440\">with</span>\
  \ <span m=\"664790\">probability</span> <span m=\"667360\">exactly</span> <span\
  \ m=\"668440\">w</span> <span m=\"668920\">of</span> <span m=\"669700\">xi,</span>\
  \ <span m=\"670834\">xj,</span> <span m=\"673070\">so</span> <span m=\"673250\"\
  >for</span> <span m=\"673430\">all</span> <span m=\"674720\">i</span> <span m=\"\
  675170\">less</span> <span m=\"675380\">than</span> <span m=\"675530\">j</span>\
  \ <span m=\"676280\">independently.</span> <span m=\"681160\">That's</span> <span\
  \ m=\"681370\">the</span> <span m=\"681430\">definition</span> <span m=\"681940\"\
  >of</span> <span m=\"682030\">a</span> <span m=\"682090\">w</span> <span m=\"682390\"\
  >random</span> <span m=\"682720\">graph.</span></p><p><span m=\"683950\">And</span>\
  \ <span m=\"684760\">the</span> <span m=\"684940\">two-block</span> <span m=\"685600\"\
  >stochastic</span> <span m=\"686200\">model</span> <span m=\"686790\">is</span>\
  \ <span m=\"686920\">a</span> <span m=\"686980\">special</span> <span m=\"687370\"\
  >case</span> <span m=\"687820\">of</span> <span m=\"687970\">this</span> <span m=\"\
  688090\">w</span> <span m=\"688420\">random</span> <span m=\"688750\">graph</span>\
  \ <span m=\"689470\">for</span> <span m=\"689830\">the</span> <span m=\"690120\"\
  >graphon,</span> <span m=\"690790\">which</span> <span m=\"691000\">corresponds</span>\
  \ <span m=\"691720\">to</span> <span m=\"693520\">this</span> <span m=\"693970\"\
  >red-blue</span> <span m=\"694570\">picture</span> <span m=\"695020\">here.</span>\
  \ <span m=\"698650\">So</span> <span m=\"698820\">the</span> <span m=\"698940\"\
  >generation</span> <span m=\"699480\">process</span> <span m=\"700560\">would</span>\
  \ <span m=\"700710\">be</span> <span m=\"701610\">I</span> <span m=\"702000\">give</span>\
  \ <span m=\"702240\">you</span> <span m=\"702420\">some</span> <span m=\"704340\"\
  >x1,</span> <span m=\"705390\">x2,</span> <span m=\"706560\">x3,</span> <span m=\"\
  709300\">and</span> <span m=\"709420\">then,</span> <span m=\"709710\">likewise,</span>\
  \ <span m=\"710200\">x1,</span> <span m=\"713190\">x3,</span> <span m=\"715170\"\
  >x2.</span> <span m=\"717250\">And</span> <span m=\"717350\">then</span> <span m=\"\
  717470\">I</span> <span m=\"717600\">evaluate,</span> <span m=\"718710\">what</span>\
  \ <span m=\"718920\">is</span> <span m=\"719040\">the</span> <span m=\"719160\"\
  >value</span> <span m=\"719610\">of</span> <span m=\"719730\">this</span> <span\
  \ m=\"719940\">graphon</span> <span m=\"721260\">at</span> <span m=\"722070\">these</span>\
  \ <span m=\"722360\">points?</span></p><p><span m=\"731450\">And</span> <span m=\"\
  731590\">those</span> <span m=\"731860\">are</span> <span m=\"731980\">my</span>\
  \ <span m=\"732280\">edge</span> <span m=\"732580\">probabilities.</span> <span\
  \ m=\"735080\">So</span> <span m=\"735470\">what</span> <span m=\"735650\">I</span>\
  \ <span m=\"735740\">described</span> <span m=\"736210\">is</span> <span m=\"736340\"\
  >a</span> <span m=\"736400\">special</span> <span m=\"736790\">case</span> <span\
  \ m=\"737420\">of</span> <span m=\"737570\">this</span> <span m=\"737780\">general</span>\
  \ <span m=\"738380\">w</span> <span m=\"738890\">random</span> <span m=\"739250\"\
  >graph.</span> <span m=\"742460\">Any</span> <span m=\"742610\">questions?</span></p><p><span\
  \ m=\"745570\">So</span> <span m=\"745900\">like</span> <span m=\"746140\">before,</span>\
  \ <span m=\"746920\">an</span> <span m=\"746980\">important</span> <span m=\"747430\"\
  >statistical</span> <span m=\"748000\">question</span> <span m=\"748390\">is</span>\
  \ <span m=\"748660\">if</span> <span m=\"748810\">I</span> <span m=\"748900\">show</span>\
  \ <span m=\"749200\">you</span> <span m=\"749320\">the</span> <span m=\"749440\"\
  >graph,</span> <span m=\"750920\">can</span> <span m=\"751100\">you</span> <span\
  \ m=\"751250\">tell</span> <span m=\"751460\">me</span> <span m=\"752720\">a</span>\
  \ <span m=\"752840\">good</span> <span m=\"753140\">model</span> <span m=\"753680\"\
  >for</span> <span m=\"754310\">where</span> <span m=\"754550\">this</span> <span\
  \ m=\"754730\">graph</span> <span m=\"755030\">came</span> <span m=\"755270\">from?</span>\
  \ <span m=\"757210\">So</span> <span m=\"757260\">that's</span> <span m=\"758580\"\
  >one</span> <span m=\"758790\">of</span> <span m=\"758850\">the</span> <span m=\"\
  758940\">reasons</span> <span m=\"759300\">why</span> <span m=\"759900\">people</span>\
  \ <span m=\"760230\">in</span> <span m=\"760620\">applied</span> <span m=\"761010\"\
  >math</span> <span m=\"761460\">might</span> <span m=\"761670\">care</span> <span\
  \ m=\"762000\">about</span> <span m=\"762680\">these</span> <span m=\"762900\">types</span>\
  \ <span m=\"763200\">of</span> <span m=\"763290\">constructions.</span></p><p><span\
  \ m=\"765970\">Let</span> <span m=\"766120\">me</span> <span m=\"766270\">talk</span>\
  \ <span m=\"766510\">about</span> <span m=\"766720\">some</span> <span m=\"766900\"\
  >theorems.</span> <span m=\"771050\">I've</span> <span m=\"771200\">told</span>\
  \ <span m=\"771410\">you</span> <span m=\"771680\">that</span> <span m=\"772370\"\
  >the</span> <span m=\"772700\">sequence</span> <span m=\"773150\">of</span> <span\
  \ m=\"773240\">Erdos-Renyi</span> <span m=\"773930\">random</span> <span m=\"774230\"\
  >graphs</span> <span m=\"774800\">converges</span> <span m=\"775370\">to</span>\
  \ <span m=\"775490\">the</span> <span m=\"775580\">constant</span> <span m=\"776000\"\
  >graphon</span> <span m=\"776390\">p.</span> <span m=\"777770\">So</span> <span\
  \ m=\"778280\">instead</span> <span m=\"778760\">of</span> <span m=\"778970\">taking</span>\
  \ <span m=\"779300\">a</span> <span m=\"779360\">constant</span> <span m=\"779810\"\
  >graphon</span> <span m=\"780470\">p,</span> <span m=\"781190\">now</span> <span\
  \ m=\"781490\">I</span> <span m=\"781580\">start</span> <span m=\"782090\">with</span>\
  \ <span m=\"782480\">w</span> <span m=\"782810\">random</span> <span m=\"783170\"\
  >graph.</span> <span m=\"784190\">And</span> <span m=\"784430\">you</span> <span\
  \ m=\"784550\">should</span> <span m=\"784730\">expect,</span> <span m=\"785370\"\
  >and</span> <span m=\"785600\">it</span> <span m=\"785750\">is</span> <span m=\"\
  785870\">indeed</span> <span m=\"786140\">true,</span> <span m=\"786860\">that</span>\
  \ <span m=\"787190\">this</span> <span m=\"787400\">sequence</span> <span m=\"788150\"\
  >converges</span> <span m=\"788960\">to</span> <span m=\"789740\">w</span> <span\
  \ m=\"790220\">as their</span> <span m=\"790700\">limit.</span></p><p><span m=\"\
  792500\">So</span> <span m=\"793090\">let</span> <span m=\"793250\">w</span> <span\
  \ m=\"793670\">be</span> <span m=\"793820\">a</span> <span m=\"793880\">graphon.</span>\
  \ <span m=\"799695\">So let</span> <span m=\"800180\">w</span> <span m=\"800450\"\
  >be a</span> <span m=\"800720\">graphon.</span> <span m=\"801830\">And</span> <span\
  \ m=\"804760\">for</span> <span m=\"804970\">each</span> <span m=\"805330\">n,</span>\
  \ <span m=\"806230\">let</span> <span m=\"806380\">me</span> <span m=\"806530\"\
  >draw</span> <span m=\"807010\">this</span> <span m=\"807280\">graph</span> <span\
  \ m=\"808000\">G</span> <span m=\"808300\">sub</span> <span m=\"808450\">n</span>\
  \ <span m=\"809530\">using</span> <span m=\"810700\">the</span> <span m=\"810860\"\
  >w</span> <span m=\"811210\">random</span> <span m=\"811630\">graph</span> <span\
  \ m=\"811960\">model</span> <span m=\"813370\">independently.</span> <span m=\"\
  817640\">Then</span> <span m=\"819700\">with</span> <span m=\"819880\">probability</span>\
  \ <span m=\"820490\">1,</span> <span m=\"826460\">the</span> <span m=\"826580\"\
  >sequence</span> <span m=\"827810\">converges</span> <span m=\"828950\">to</span>\
  \ <span m=\"829460\">the</span> <span m=\"829550\">graphon</span> <span m=\"830120\"\
  >w.</span></p><p><span m=\"833680\">So</span> <span m=\"833830\">in</span> <span\
  \ m=\"833920\">the</span> <span m=\"834010\">sense</span> <span m=\"834490\">that</span>\
  \ <span m=\"834670\">I've</span> <span m=\"835120\">shown</span> <span m=\"835450\"\
  >above,</span> <span m=\"836950\">described</span> <span m=\"837400\">above.</span>\
  \ <span m=\"838190\">So</span> <span m=\"839770\">this</span> <span m=\"839890\"\
  >statement</span> <span m=\"840250\">tells</span> <span m=\"840610\">us</span> <span\
  \ m=\"841200\">a</span> <span m=\"841390\">couple</span> <span m=\"841640\">of</span>\
  \ <span m=\"841720\">things--</span> <span m=\"842060\">one,</span> <span m=\"842320\"\
  >that</span> <span m=\"842620\">w</span> <span m=\"842920\">random</span> <span\
  \ m=\"843190\">graphs</span> <span m=\"843490\">converge</span> <span m=\"843970\"\
  >to</span> <span m=\"844120\">the</span> <span m=\"844210\">limit</span> <span m=\"\
  844420\">w,</span> <span m=\"844900\">as</span> <span m=\"845020\">you</span> <span\
  \ m=\"845140\">should</span> <span m=\"845320\">expect;</span> <span m=\"847220\"\
  >and</span> <span m=\"847450\">two,</span> <span m=\"848350\">that</span> <span\
  \ m=\"848950\">every</span> <span m=\"849400\">graphon</span> <span m=\"851170\"\
  >w</span> <span m=\"852400\">is</span> <span m=\"852670\">the</span> <span m=\"\
  852820\">limit</span> <span m=\"853150\">point</span> <span m=\"854140\">of</span>\
  \ <span m=\"854290\">some</span> <span m=\"854620\">sequence</span> <span m=\"855130\"\
  >of</span> <span m=\"855250\">graphs.</span> <span m=\"857750\">So</span> <span\
  \ m=\"857800\">this</span> <span m=\"857980\">is</span> <span m=\"858040\">something</span>\
  \ <span m=\"858370\">that</span> <span m=\"858700\">we</span> <span m=\"858910\"\
  >never</span> <span m=\"859600\">quite</span> <span m=\"859900\">explicitly</span>\
  \ <span m=\"860650\">stated</span> <span m=\"861070\">before.</span> <span m=\"\
  861950\">So</span> <span m=\"862210\">let</span> <span m=\"862330\">me</span> <span\
  \ m=\"862930\">make</span> <span m=\"863170\">this</span> <span m=\"863800\">remark.</span></p><p><span\
  \ m=\"864980\">So</span> <span m=\"865150\">in</span> <span m=\"865240\">particular,</span>\
  \ <span m=\"871980\">every</span> <span m=\"873390\">w</span> <span m=\"874920\"\
  >is</span> <span m=\"875610\">the</span> <span m=\"875700\">limit</span> <span m=\"\
  879670\">of</span> <span m=\"879820\">some</span> <span m=\"881230\">sequence</span>\
  \ <span m=\"882850\">of</span> <span m=\"883060\">graphs,</span> <span m=\"886340\"\
  >just</span> <span m=\"886580\">like</span> <span m=\"886790\">every</span> <span\
  \ m=\"887030\">real</span> <span m=\"887300\">number,</span> <span m=\"888150\"\
  >in</span> <span m=\"888290\">analogy</span> <span m=\"888740\">to</span> <span\
  \ m=\"888830\">what</span> <span m=\"888950\">we</span> <span m=\"889070\">said</span>\
  \ <span m=\"889220\">last</span> <span m=\"889400\">time.</span> <span m=\"889540\"\
  >Every</span> <span m=\"889790\">real</span> <span m=\"889970\">number</span> <span\
  \ m=\"890720\">is</span> <span m=\"891020\">the</span> <span m=\"891140\">limit</span>\
  \ <span m=\"891680\">of</span> <span m=\"891860\">a</span> <span m=\"891920\">sequence</span>\
  \ <span m=\"892340\">of</span> <span m=\"892430\">rational</span> <span m=\"892850\"\
  >numbers</span> <span m=\"894080\">through</span> <span m=\"894290\">rational</span>\
  \ <span m=\"894710\">approximation.</span> <span m=\"895760\">And</span> <span m=\"\
  895880\">this</span> <span m=\"896060\">is</span> <span m=\"896180\">some</span>\
  \ <span m=\"896570\">form</span> <span m=\"896900\">of</span> <span m=\"897410\"\
  >approximation</span> <span m=\"898650\">of</span> <span m=\"899020\">a</span> <span\
  \ m=\"899090\">graphon</span> <span m=\"899570\">by</span> <span m=\"899780\">a</span>\
  \ <span m=\"899810\">sequence</span> <span m=\"900260\">of</span> <span m=\"900320\"\
  >graphs.</span></p><p><span m=\"901790\">OK. So</span> <span m=\"902060\">I'm</span>\
  \ <span m=\"902150\">not</span> <span m=\"902300\">going</span> <span m=\"902420\"\
  >to</span> <span m=\"902480\">prove</span> <span m=\"902720\">this</span> <span\
  \ m=\"902900\">theorem.</span> <span m=\"903740\">The</span> <span m=\"903870\"\
  >proof</span> <span m=\"904170\">is</span> <span m=\"905390\">not</span> <span m=\"\
  905600\">difficult.</span> <span m=\"906080\">So</span> <span m=\"906980\">using</span>\
  \ <span m=\"907310\">that</span> <span m=\"907520\">definition</span> <span m=\"\
  908420\">of</span> <span m=\"909080\">subgraph</span> <span m=\"909560\">convergence,</span>\
  \ <span m=\"910700\">the</span> <span m=\"910820\">proof</span> <span m=\"911240\"\
  >uses</span> <span m=\"913760\">what's</span> <span m=\"914000\">known</span> <span\
  \ m=\"914210\">as</span> <span m=\"914330\">Azuma's</span> <span m=\"914870\">inequality.</span>\
  \ <span m=\"916890\">So</span> <span m=\"917060\">by</span> <span m=\"918050\">an</span>\
  \ <span m=\"918140\">appropriate</span> <span m=\"918590\">application</span> <span\
  \ m=\"919250\">of</span> <span m=\"919610\">Azuma's</span> <span m=\"920540\">inequality</span>\
  \ <span m=\"921110\">on</span> <span m=\"921200\">the</span> <span m=\"921260\"\
  >concentration</span> <span m=\"921860\">of</span> <span m=\"921950\">martingales,</span>\
  \ <span m=\"922790\">one</span> <span m=\"923810\">can</span> <span m=\"923960\"\
  >prove</span> <span m=\"924230\">this</span> <span m=\"924590\">theorem</span> <span\
  \ m=\"924900\">here</span> <span m=\"925850\">by</span> <span m=\"926240\">estimating</span>\
  \ <span m=\"927110\">the</span> <span m=\"927230\">probability</span> <span m=\"\
  928580\">that--</span> <span m=\"935180\">to</span> <span m=\"935270\">show</span>\
  \ <span m=\"935600\">that</span> <span m=\"936830\">the</span> <span m=\"937070\"\
  >probability</span> <span m=\"938180\">that</span> <span m=\"938510\">the</span>\
  \ <span m=\"938840\">F</span> <span m=\"940190\">density</span> <span m=\"940760\"\
  >in</span> <span m=\"940940\">Gn,</span> <span m=\"941960\">it</span> <span m=\"\
  942250\">is</span> <span m=\"942500\">very</span> <span m=\"942800\">close</span>\
  \ <span m=\"943370\">to</span> <span m=\"945170\">the</span> <span m=\"945330\"\
  >F</span> <span m=\"945590\">density</span> <span m=\"945845\">in</span> <span m=\"\
  946100\">w</span> <span m=\"947330\">with</span> <span m=\"947810\">high</span>\
  \ <span m=\"948110\">probability.</span></p><p><span m=\"952252\">OK.</span> <span\
  \ m=\"955180\">Any</span> <span m=\"955360\">questions</span> <span m=\"955690\"\
  >so</span> <span m=\"955810\">far?</span> <span m=\"958820\">So</span> <span m=\"\
  958970\">this</span> <span m=\"959150\">is</span> <span m=\"959270\">an</span> <span\
  \ m=\"959570\">important</span> <span m=\"960020\">example</span> <span m=\"960890\"\
  >of</span> <span m=\"962330\">one</span> <span m=\"962600\">of</span> <span m=\"\
  962660\">the</span> <span m=\"962780\">motivations</span> <span m=\"963440\">of</span>\
  \ <span m=\"963560\">graph</span> <span m=\"963860\">limits.</span> <span m=\"966220\"\
  >But</span> <span m=\"966310\">now,</span> <span m=\"966440\">let's</span> <span\
  \ m=\"966800\">get</span> <span m=\"966940\">back</span> <span m=\"967190\">to</span>\
  \ <span m=\"968120\">what</span> <span m=\"968270\">I</span> <span m=\"968330\"\
  >said</span> <span m=\"968630\">earlier.</span> <span m=\"969460\">I</span> <span\
  \ m=\"969530\">would</span> <span m=\"969620\">like</span> <span m=\"969800\">to</span>\
  \ <span m=\"969860\">develop</span> <span m=\"970340\">a</span> <span m=\"970400\"\
  >sequence</span> <span m=\"970850\">of</span> <span m=\"970940\">tools</span> <span\
  \ m=\"971810\">that</span> <span m=\"971960\">will</span> <span m=\"972110\">allow</span>\
  \ <span m=\"972410\">us</span> <span m=\"972560\">to</span> <span m=\"972650\">prove</span>\
  \ <span m=\"972950\">the</span> <span m=\"973070\">main</span> <span m=\"973340\"\
  >theorem</span> <span m=\"973700\">stated</span> <span m=\"974150\">at</span> <span\
  \ m=\"974270\">the</span> <span m=\"974390\">end</span> <span m=\"974630\">of</span>\
  \ <span m=\"974750\">the</span> <span m=\"974840\">last</span> <span m=\"975170\"\
  >lecture.</span></p><p><span m=\"978000\">And</span> <span m=\"978150\">this</span>\
  \ <span m=\"978300\">will</span> <span m=\"978420\">sound</span> <span m=\"978720\"\
  >very</span> <span m=\"978960\">familiar,</span> <span m=\"979470\">because</span>\
  \ <span m=\"979830\">we're</span> <span m=\"979980\">going</span> <span m=\"980110\"\
  >to</span> <span m=\"980430\">write</span> <span m=\"980700\">down</span> <span\
  \ m=\"980970\">some</span> <span m=\"981600\">lemmas</span> <span m=\"982230\">that</span>\
  \ <span m=\"982800\">we</span> <span m=\"983220\">did</span> <span m=\"983610\"\
  >back</span> <span m=\"983910\">in</span> <span m=\"983970\">the</span> <span m=\"\
  984060\">chapter</span> <span m=\"984510\">of</span> <span m=\"984750\">Szemer\xE9\
  di's</span> <span m=\"985350\">regularity</span> <span m=\"985880\">lemma</span>\
  \ <span m=\"986490\">but</span> <span m=\"986640\">now</span> <span m=\"986870\"\
  >in</span> <span m=\"986970\">the</span> <span m=\"987030\">language</span> <span\
  \ m=\"987420\">of</span> <span m=\"987510\">graphons.</span> <span m=\"989450\"\
  >So</span> <span m=\"989640\">the</span> <span m=\"989700\">first</span> <span m=\"\
  990610\">is</span> <span m=\"991030\">a counting</span> <span m=\"991410\">lemma.</span></p><p><span\
  \ m=\"998270\">The</span> <span m=\"998390\">goal</span> <span m=\"998630\">of</span>\
  \ <span m=\"998720\">the</span> <span m=\"998810\">counting</span> <span m=\"999170\"\
  >lemma</span> <span m=\"999650\">is</span> <span m=\"999770\">to</span> <span m=\"\
  999860\">show</span> <span m=\"1000160\">that</span> <span m=\"1000460\">if</span>\
  \ <span m=\"1000610\">you</span> <span m=\"1000760\">have</span> <span m=\"1001090\"\
  >two</span> <span m=\"1001360\">graphons</span> <span m=\"1002350\">which</span>\
  \ <span m=\"1002590\">are</span> <span m=\"1002680\">close</span> <span m=\"1003190\"\
  >to</span> <span m=\"1003370\">each</span> <span m=\"1003610\">other</span> <span\
  \ m=\"1005100\">in</span> <span m=\"1005220\">the</span> <span m=\"1005280\">sense</span>\
  \ <span m=\"1005850\">of</span> <span m=\"1006450\">cut</span> <span m=\"1006750\"\
  >distance,</span> <span m=\"1008550\">then</span> <span m=\"1010060\">their</span>\
  \ <span m=\"1010580\">F</span> <span m=\"1011180\">densities</span> <span m=\"1012050\"\
  >are</span> <span m=\"1012260\">similar</span> <span m=\"1012800\">to</span> <span\
  \ m=\"1012980\">each</span> <span m=\"1013190\">other.</span> <span m=\"1015530\"\
  >So</span> <span m=\"1015580\">here's</span> <span m=\"1015840\">a</span> <span\
  \ m=\"1015910\">statement.</span> <span m=\"1017190\">So</span> <span m=\"1017260\"\
  >if</span> <span m=\"1018880\">w</span> <span m=\"1019510\">and</span> <span m=\"\
  1019660\">u</span> <span m=\"1020660\">are</span> <span m=\"1020950\">graphons</span>\
  \ <span m=\"1024556\">and F</span> <span m=\"1025040\">is</span> <span m=\"1025403\"\
  >a</span> <span m=\"1025766\">graph,</span> <span m=\"1030660\">then</span> <span\
  \ m=\"1032400\">the</span> <span m=\"1033280\">F</span> <span m=\"1033579\">density</span>\
  \ <span m=\"1034200\">of</span> <span m=\"1035369\">w</span> <span m=\"1037050\"\
  >minus</span> <span m=\"1037470\">the</span> <span m=\"1037619\">F</span> <span\
  \ m=\"1037890\">density</span> <span m=\"1038369\">of</span> <span m=\"1038490\"\
  >u,</span> <span m=\"1039460\">their</span> <span m=\"1039990\">difference</span>\
  \ <span m=\"1041040\">is</span> <span m=\"1041910\">no</span> <span m=\"1042089\"\
  >more</span> <span m=\"1042420\">than</span> <span m=\"1043710\">a</span> <span\
  \ m=\"1043800\">constant--</span> <span m=\"1044430\">so</span> <span m=\"1044640\"\
  >number</span> <span m=\"1044940\">of</span> <span m=\"1045060\">edges</span> <span\
  \ m=\"1045450\">of</span> <span m=\"1045690\">F</span> <span m=\"1046680\">times</span>\
  \ <span m=\"1048089\">the</span> <span m=\"1048840\">cut</span> <span m=\"1049110\"\
  >distance</span> <span m=\"1049710\">between</span> <span m=\"1050490\">u</span>\
  \ <span m=\"1051330\">and</span> <span m=\"1051750\">w.</span></p><p><span m=\"\
  1057670\">So</span> <span m=\"1059340\">maybe</span> <span m=\"1059580\">some</span>\
  \ <span m=\"1059760\">of</span> <span m=\"1059850\">you</span> <span m=\"1059970\"\
  >already</span> <span m=\"1060300\">see</span> <span m=\"1060510\">how</span> <span\
  \ m=\"1060660\">to</span> <span m=\"1060750\">do</span> <span m=\"1060900\">this</span>\
  \ <span m=\"1061260\">from</span> <span m=\"1061740\">our</span> <span m=\"1061860\"\
  >discussion</span> <span m=\"1062790\">on</span> <span m=\"1063970\">Szemer\xE9\
  di's</span> <span m=\"1064320\">regularity</span> <span m=\"1064590\">lemma.</span>\
  \ <span m=\"1065930\">In</span> <span m=\"1066320\">any</span> <span m=\"1066460\"\
  >case,</span> <span m=\"1066630\">I</span> <span m=\"1066690\">want</span> <span\
  \ m=\"1066930\">to</span> <span m=\"1067320\">just</span> <span m=\"1067530\">rewrite</span>\
  \ <span m=\"1067910\">the</span> <span m=\"1067980\">proof</span> <span m=\"1068220\"\
  >again</span> <span m=\"1068790\">in</span> <span m=\"1068910\">the</span> <span\
  \ m=\"1068970\">language</span> <span m=\"1069390\">of</span> <span m=\"1069450\"\
  >graphons.</span> <span m=\"1070350\">And</span> <span m=\"1070470\">this</span>\
  \ <span m=\"1070620\">will</span> <span m=\"1070710\">hopefully--</span> <span m=\"\
  1072190\">so</span> <span m=\"1072660\">we</span> <span m=\"1072930\">did</span>\
  \ <span m=\"1073170\">two</span> <span m=\"1073440\">proofs</span> <span m=\"1073860\"\
  >of</span> <span m=\"1073920\">the</span> <span m=\"1074010\">triangle</span> <span\
  \ m=\"1074460\">counting</span> <span m=\"1074740\">lemma.</span></p><p><span m=\"\
  1075700\">One</span> <span m=\"1075900\">was</span> <span m=\"1076620\">hopefully</span>\
  \ <span m=\"1077010\">more</span> <span m=\"1077220\">intuitive</span> <span m=\"\
  1077700\">for</span> <span m=\"1077880\">you,</span> <span m=\"1078480\">which</span>\
  \ <span m=\"1078660\">is</span> <span m=\"1078840\">you</span> <span m=\"1078960\"\
  >pick</span> <span m=\"1079140\">a</span> <span m=\"1079200\">typical</span> <span\
  \ m=\"1079560\">vertex</span> <span m=\"1079815\">that</span> <span m=\"1080070\"\
  >has</span> <span m=\"1080250\">lots</span> <span m=\"1080460\">of</span> <span\
  \ m=\"1080550\">neighbors</span> <span m=\"1080880\">on</span> <span m=\"1080940\"\
  >both</span> <span m=\"1081120\">sides</span> <span m=\"1081510\">and</span> <span\
  \ m=\"1081690\">therefore</span> <span m=\"1082020\">lots</span> <span m=\"1082230\"\
  >of</span> <span m=\"1082320\">edges</span> <span m=\"1082760\">between.</span>\
  \ <span m=\"1084450\">And</span> <span m=\"1084570\">then</span> <span m=\"1084690\"\
  >there</span> <span m=\"1084780\">was</span> <span m=\"1084900\">a</span> <span\
  \ m=\"1084960\">second</span> <span m=\"1085290\">proof,</span> <span m=\"1085910\"\
  >which</span> <span m=\"1086100\">I</span> <span m=\"1086190\">said</span> <span\
  \ m=\"1086370\">was</span> <span m=\"1086520\">a</span> <span m=\"1086550\">more</span>\
  \ <span m=\"1086850\">analytic</span> <span m=\"1087360\">proof,</span> <span m=\"\
  1087780\">where</span> <span m=\"1087990\">you</span> <span m=\"1088110\">took</span>\
  \ <span m=\"1088350\">out</span> <span m=\"1088470\">one</span> <span m=\"1088820\"\
  >edge</span> <span m=\"1089070\">at</span> <span m=\"1089190\">a</span> <span m=\"\
  1089250\">time.</span> <span m=\"1090420\">And</span> <span m=\"1090750\">that</span>\
  \ <span m=\"1090990\">proof,</span> <span m=\"1092190\">I</span> <span m=\"1092280\"\
  >think</span> <span m=\"1092460\">it's</span> <span m=\"1092580\">technically</span>\
  \ <span m=\"1093090\">easier</span> <span m=\"1093450\">to</span> <span m=\"1094140\"\
  >implement,</span> <span m=\"1094710\">especially</span> <span m=\"1095220\">for</span>\
  \ <span m=\"1095430\">general</span> <span m=\"1095880\">H.</span></p><p><span m=\"\
  1096690\">But</span> <span m=\"1096840\">the</span> <span m=\"1096930\">first</span>\
  \ <span m=\"1097140\">time</span> <span m=\"1097320\">you</span> <span m=\"1097410\"\
  >see</span> <span m=\"1097620\">it,</span> <span m=\"1097680\">you</span> <span\
  \ m=\"1097800\">might</span> <span m=\"1097920\">not</span> <span m=\"1098280\"\
  >quite</span> <span m=\"1098550\">see</span> <span m=\"1099030\">what</span> <span\
  \ m=\"1099360\">the</span> <span m=\"1099450\">calculation</span> <span m=\"1100110\"\
  >was</span> <span m=\"1100260\">about.</span> <span m=\"1100680\">So</span> <span\
  \ m=\"1100830\">I</span> <span m=\"1100860\">want</span> <span m=\"1101010\">to</span>\
  \ <span m=\"1101070\">do</span> <span m=\"1101190\">this</span> <span m=\"1101400\"\
  >exact</span> <span m=\"1101760\">same</span> <span m=\"1102030\">calculation</span>\
  \ <span m=\"1102690\">again</span> <span m=\"1103320\">in</span> <span m=\"1103440\"\
  >the</span> <span m=\"1103500\">language</span> <span m=\"1103830\">of</span> <span\
  \ m=\"1103890\">graphons.</span> <span m=\"1104610\">And</span> <span m=\"1104700\"\
  >hopefully,</span> <span m=\"1105150\">it</span> <span m=\"1105230\">should</span>\
  \ <span m=\"1105360\">be</span> <span m=\"1105480\">clear</span> <span m=\"1105870\"\
  >this</span> <span m=\"1106080\">time.</span></p><p><span m=\"1109600\">So</span>\
  \ <span m=\"1109620\">this</span> <span m=\"1109800\">is</span> <span m=\"1109860\"\
  >the</span> <span m=\"1109950\">same</span> <span m=\"1110250\">as</span> <span\
  \ m=\"1110370\">the</span> <span m=\"1110460\">counting</span> <span m=\"1110820\"\
  >lemma</span> <span m=\"1111390\">over</span> <span m=\"1111690\">epsilon-regular</span>\
  \ <span m=\"1112650\">pairs.</span> <span m=\"1114800\">So it</span> <span m=\"\
  1115110\">suffices</span> <span m=\"1118465\">to</span> <span m=\"1118956\">prove</span>\
  \ <span m=\"1119940\">the</span> <span m=\"1120100\">inequality</span> <span m=\"\
  1124120\">where</span> <span m=\"1124320\">the</span> <span m=\"1124410\">right-hand</span>\
  \ <span m=\"1124860\">side</span> <span m=\"1126660\">is</span> <span m=\"1126840\"\
  >replaced</span> <span m=\"1128430\">not</span> <span m=\"1128670\">by</span> <span\
  \ m=\"1128820\">the</span> <span m=\"1128940\">cut</span> <span m=\"1129330\">distance</span>\
  \ <span m=\"1130230\">but</span> <span m=\"1130350\">by</span> <span m=\"1130500\"\
  >the</span> <span m=\"1130590\">cut</span> <span m=\"1130850\">norm.</span> <span\
  \ m=\"1133440\">And</span> <span m=\"1133530\">the</span> <span m=\"1133620\">reason</span>\
  \ <span m=\"1133980\">is</span> <span m=\"1134160\">that</span> <span m=\"1134820\"\
  >once</span> <span m=\"1135120\">you</span> <span m=\"1135270\">have</span> <span\
  \ m=\"1135870\">the</span> <span m=\"1136110\">second</span> <span m=\"1136530\"\
  >inequality</span> <span m=\"1137550\">by</span> <span m=\"1137790\">taking</span>\
  \ <span m=\"1138210\">an</span> <span m=\"1138480\">infimum</span> <span m=\"1140940\"\
  >over</span> <span m=\"1141300\">all</span> <span m=\"1142900\">measure-preserving</span>\
  \ <span m=\"1143760\">bijections</span> <span m=\"1144410\">phi--</span> <span m=\"\
  1145290\">and</span> <span m=\"1145350\">notice</span> <span m=\"1145680\">that</span>\
  \ <span m=\"1145890\">that</span> <span m=\"1147750\">change</span> <span m=\"1148110\"\
  >does</span> <span m=\"1148290\">not</span> <span m=\"1148650\">affect</span> <span\
  \ m=\"1149160\">the</span> <span m=\"1149360\">F</span> <span m=\"1149560\">density.</span>\
  \ <span m=\"1150990\">By</span> <span m=\"1151140\">taking</span> <span m=\"1151410\"\
  >an</span> <span m=\"1151470\">infimum</span> <span m=\"1151950\">over</span> <span\
  \ m=\"1152160\">phi,</span> <span m=\"1152690\">you</span> <span m=\"1152900\">recover</span>\
  \ <span m=\"1153380\">the</span> <span m=\"1153480\">first</span> <span m=\"1153720\"\
  >inequality.</span></p><p><span m=\"1157590\">I</span> <span m=\"1157680\">want</span>\
  \ <span m=\"1157890\">to</span> <span m=\"1157980\">give</span> <span m=\"1158220\"\
  >you</span> <span m=\"1158520\">a</span> <span m=\"1159390\">small</span> <span\
  \ m=\"1159870\">reformulation</span> <span m=\"1161280\">of</span> <span m=\"1161400\"\
  >the</span> <span m=\"1161490\">cut</span> <span m=\"1161770\">norm</span> <span\
  \ m=\"1162360\">that</span> <span m=\"1162510\">will</span> <span m=\"1162600\"\
  >be</span> <span m=\"1162720\">useful</span> <span m=\"1163530\">for</span> <span\
  \ m=\"1163710\">thinking</span> <span m=\"1164070\">about</span> <span m=\"1164460\"\
  >this</span> <span m=\"1164730\">counting</span> <span m=\"1165120\">lemma.</span>\
  \ <span m=\"1169980\">Here's</span> <span m=\"1170340\">a</span> <span m=\"1171720\"\
  >reformulation</span> <span m=\"1174090\">of</span> <span m=\"1176210\">the</span>\
  \ <span m=\"1176310\">cut</span> <span m=\"1176550\">norm--</span> <span m=\"1177750\"\
  >namely,</span> <span m=\"1178590\">that</span> <span m=\"1178770\">I</span> <span\
  \ m=\"1178860\">can</span> <span m=\"1179070\">define</span> <span m=\"1179610\"\
  >the</span> <span m=\"1179730\">cut</span> <span m=\"1179970\">norm.</span> <span\
  \ m=\"1182470\">So</span> <span m=\"1182600\">here,</span> <span m=\"1182870\">w</span>\
  \ <span m=\"1183290\">is</span> <span m=\"1183440\">taking</span> <span m=\"1184310\"\
  >real</span> <span m=\"1184580\">values,</span> <span m=\"1185465\">so</span> <span\
  \ m=\"1185840\">not</span> <span m=\"1186050\">necessarily</span> <span m=\"1186650\"\
  >non-negative.</span></p><p><span m=\"1188630\">So</span> <span m=\"1189080\">the</span>\
  \ <span m=\"1189200\">cut</span> <span m=\"1189440\">norm</span> <span m=\"1190940\"\
  >we</span> <span m=\"1191090\">saw</span> <span m=\"1191270\">earlier</span> <span\
  \ m=\"1192650\">is</span> <span m=\"1192860\">defined</span> <span m=\"1193280\"\
  >to</span> <span m=\"1193400\">be</span> <span m=\"1194150\">the</span> <span m=\"\
  1194240\">supremum</span> <span m=\"1197910\">over</span> <span m=\"1200680\">all</span>\
  \ <span m=\"1200890\">measurable</span> <span m=\"1201400\">subsets</span> <span\
  \ m=\"1201940\">of the</span> <span m=\"1202150\">0,</span> <span m=\"1202360\"\
  >1</span> <span m=\"1202600\">interval</span> <span m=\"1203830\">of</span> <span\
  \ m=\"1204970\">this</span> <span m=\"1205240\">integral</span> <span m=\"1206290\"\
  >in</span> <span m=\"1206440\">absolute</span> <span m=\"1206890\">value.</span>\
  \ <span m=\"1208900\">But</span> <span m=\"1209080\">it</span> <span m=\"1209140\"\
  >turns</span> <span m=\"1209410\">out</span> <span m=\"1210070\">I</span> <span\
  \ m=\"1210160\">can</span> <span m=\"1210310\">rewrite</span> <span m=\"1211210\"\
  >this</span> <span m=\"1212050\">supremum</span> <span m=\"1213670\">over</span>\
  \ <span m=\"1214000\">a</span> <span m=\"1214150\">slightly</span> <span m=\"1214780\"\
  >larger</span> <span m=\"1215290\">set</span> <span m=\"1215590\">of</span> <span\
  \ m=\"1215710\">objects.</span> <span m=\"1216850\">Instead</span> <span m=\"1217210\"\
  >of</span> <span m=\"1217330\">just</span> <span m=\"1217570\">looking</span> <span\
  \ m=\"1217900\">over</span> <span m=\"1220390\">measurable</span> <span m=\"1220870\"\
  >subsets</span> <span m=\"1221500\">of</span> <span m=\"1221620\">the</span> <span\
  \ m=\"1221710\">interval,</span> <span m=\"1222460\">let</span> <span m=\"1222640\"\
  >me</span> <span m=\"1222730\">now</span> <span m=\"1222910\">look</span> <span\
  \ m=\"1223150\">at</span> <span m=\"1223990\">measurable</span> <span m=\"1224620\"\
  >functions.</span></p><p><span m=\"1226330\">Little</span> <span m=\"1226670\">u.</span>\
  \ <span m=\"1229130\">So</span> <span m=\"1229320\">OK,</span> <span m=\"1230230\"\
  >let</span> <span m=\"1230350\">me</span> <span m=\"1230440\">look</span> <span\
  \ m=\"1230620\">at</span> <span m=\"1230890\">functions.</span> <span m=\"1232570\"\
  >So</span> <span m=\"1232690\">u</span> <span m=\"1233440\">and</span> <span m=\"\
  1234250\">v</span> <span m=\"1235690\">from</span> <span m=\"1236860\">0,</span>\
  \ <span m=\"1237130\">1</span> <span m=\"1238000\">to</span> <span m=\"1238210\"\
  >0,</span> <span m=\"1238420\">1--</span> <span m=\"1240860\">and</span> <span m=\"\
  1241100\">as</span> <span m=\"1241550\">always,</span> <span m=\"1241850\">everything</span>\
  \ <span m=\"1242750\">is</span> <span m=\"1242960\">measurable--</span> <span m=\"\
  1246530\">of</span> <span m=\"1247370\">the</span> <span m=\"1247490\">following</span>\
  \ <span m=\"1249380\">integral.</span></p><p><span m=\"1261570\">So</span> <span\
  \ m=\"1261690\">I</span> <span m=\"1261780\">claim</span> <span m=\"1262350\">this</span>\
  \ <span m=\"1262650\">is</span> <span m=\"1263490\">true.</span> <span m=\"1264260\"\
  >So</span> <span m=\"1264450\">I</span> <span m=\"1266940\">consider</span> <span\
  \ m=\"1267330\">this</span> <span m=\"1267510\">integral.</span> <span m=\"1269370\"\
  >Instead</span> <span m=\"1269640\">of</span> <span m=\"1270000\">integrating</span>\
  \ <span m=\"1270510\">over</span> <span m=\"1270810\">a</span> <span m=\"1270930\"\
  >box,</span> <span m=\"1271480\">now</span> <span m=\"1271660\">I'm</span> <span\
  \ m=\"1271770\">integrating</span> <span m=\"1273150\">this</span> <span m=\"1273360\"\
  >expression.</span></p><p><span m=\"1276450\">OK.</span> <span m=\"1276660\">So</span>\
  \ <span m=\"1276730\">why</span> <span m=\"1276890\">is</span> <span m=\"1276980\"\
  >this</span> <span m=\"1277160\">true?</span> <span m=\"1279380\">Well,</span> <span\
  \ m=\"1279680\">one</span> <span m=\"1279920\">of</span> <span m=\"1279980\">the</span>\
  \ <span m=\"1280100\">directions</span> <span m=\"1280730\">is</span> <span m=\"\
  1282320\">easy</span> <span m=\"1282560\">to</span> <span m=\"1282650\">see,</span>\
  \ <span m=\"1283670\">because</span> <span m=\"1285050\">the</span> <span m=\"1285140\"\
  >right-hand</span> <span m=\"1285470\">side</span> <span m=\"1285830\">is</span>\
  \ <span m=\"1286070\">strictly</span> <span m=\"1286355\">an</span> <span m=\"1286640\"\
  >enlargement</span> <span m=\"1287630\">of</span> <span m=\"1287750\">the</span>\
  \ <span m=\"1287810\">left-hand</span> <span m=\"1288170\">side.</span> <span m=\"\
  1289070\">So</span> <span m=\"1289220\">by</span> <span m=\"1289370\">taking</span>\
  \ <span m=\"1293690\">u</span> <span m=\"1293960\">to</span> <span m=\"1294110\"\
  >be</span> <span m=\"1294290\">the</span> <span m=\"1294410\">indicator</span> <span\
  \ m=\"1294960\">function</span> <span m=\"1295310\">of</span> <span m=\"1295430\"\
  >S</span> <span m=\"1295940\">and</span> <span m=\"1296090\">v</span> <span m=\"\
  1296300\">to</span> <span m=\"1296390\">be</span> <span m=\"1296510\">the</span>\
  \ <span m=\"1296630\">indicator</span> <span m=\"1297090\">of</span> <span m=\"\
  1297120\">function</span> <span m=\"1297650\">of</span> <span m=\"1297830\">T,</span>\
  \ <span m=\"1298750\">you</span> <span m=\"1298850\">see</span> <span m=\"1299060\"\
  >that</span> <span m=\"1299240\">the</span> <span m=\"1299480\">right-hand</span>\
  \ <span m=\"1299930\">side,</span> <span m=\"1300230\">in</span> <span m=\"1300320\"\
  >fact,</span> <span m=\"1300680\">includes</span> <span m=\"1301250\">the</span>\
  \ <span m=\"1301340\">left-hand</span> <span m=\"1301700\">side</span> <span m=\"\
  1302270\">in</span> <span m=\"1302390\">terms</span> <span m=\"1302690\">of</span>\
  \ <span m=\"1302840\">what</span> <span m=\"1302990\">you</span> <span m=\"1303090\"\
  >are</span> <span m=\"1303170\">allowed</span> <span m=\"1303410\">to</span> <span\
  \ m=\"1303530\">do.</span></p><p><span m=\"1305330\">But</span> <span m=\"1305450\"\
  >what</span> <span m=\"1305600\">about</span> <span m=\"1305810\">the</span> <span\
  \ m=\"1305930\">other</span> <span m=\"1306170\">direction?</span> <span m=\"1308160\"\
  >So</span> <span m=\"1308180\">for</span> <span m=\"1308330\">the</span> <span m=\"\
  1308420\">other</span> <span m=\"1308600\">direction,</span> <span m=\"1309410\"\
  >the</span> <span m=\"1309530\">main</span> <span m=\"1309740\">thing</span> <span\
  \ m=\"1310070\">is</span> <span m=\"1310220\">to</span> <span m=\"1310310\">notice</span>\
  \ <span m=\"1312020\">that</span> <span m=\"1312740\">the</span> <span m=\"1312980\"\
  >integral</span> <span m=\"1314510\">or</span> <span m=\"1314730\">the</span> <span\
  \ m=\"1314840\">integrand,</span> <span m=\"1316700\">what's</span> <span m=\"1316910\"\
  >inside</span> <span m=\"1317240\">this</span> <span m=\"1317390\">integral,</span>\
  \ <span m=\"1318140\">is</span> <span m=\"1318800\">bilinear</span> <span m=\"1323090\"\
  >in</span> <span m=\"1324410\">the</span> <span m=\"1324530\">values</span> <span\
  \ m=\"1325010\">of</span> <span m=\"1325490\">u</span> <span m=\"1325800\">and</span>\
  \ <span m=\"1325960\">v.</span> <span m=\"1327500\">So</span> <span m=\"1327680\"\
  >in</span> <span m=\"1327770\">particular,</span> <span m=\"1329180\">the</span>\
  \ <span m=\"1329360\">extrema</span> <span m=\"1330410\">of</span> <span m=\"1330560\"\
  >this</span> <span m=\"1330770\">integral,</span> <span m=\"1332390\">as</span>\
  \ <span m=\"1332540\">you</span> <span m=\"1332660\">allow</span> <span m=\"1332870\"\
  >to</span> <span m=\"1332990\">vary</span> <span m=\"1333750\">u</span> <span m=\"\
  1333860\">and</span> <span m=\"1333980\">v,</span> <span m=\"1334700\">they</span>\
  \ <span m=\"1334850\">are</span> <span m=\"1335060\">obtained.</span> <span m=\"\
  1337210\">So</span> <span m=\"1337560\">they</span> <span m=\"1338150\">are</span>\
  \ <span m=\"1338510\">obtained</span> <span m=\"1339470\">for</span> <span m=\"\
  1341480\">u</span> <span m=\"1341690\">and</span> <span m=\"1341780\">v,</span>\
  \ <span m=\"1342350\">taking</span> <span m=\"1344360\">values</span> <span m=\"\
  1349870\">in</span> <span m=\"1349990\">the</span> <span m=\"1350110\">endpoints</span>\
  \ <span m=\"1350780\">0,</span> <span m=\"1351100\">comma,</span> <span m=\"1351400\"\
  >1.</span></p><p><span m=\"1356030\">It</span> <span m=\"1356130\">may</span> <span\
  \ m=\"1356280\">be</span> <span m=\"1356400\">helpful</span> <span m=\"1356820\"\
  >to</span> <span m=\"1356910\">think</span> <span m=\"1357120\">about</span> <span\
  \ m=\"1357340\">the</span> <span m=\"1357450\">discrete</span> <span m=\"1357960\"\
  >setting,</span> <span m=\"1358560\">when,</span> <span m=\"1359160\">instead</span>\
  \ <span m=\"1359520\">of</span> <span m=\"1359580\">this</span> <span m=\"1359760\"\
  >integral,</span> <span m=\"1360150\">you</span> <span m=\"1360270\">have</span>\
  \ <span m=\"1360600\">a</span> <span m=\"1360660\">matrix</span> <span m=\"1361320\"\
  >and</span> <span m=\"1361440\">two</span> <span m=\"1361650\">vectors</span> <span\
  \ m=\"1362070\">multiplied</span> <span m=\"1362610\">from</span> <span m=\"1362880\"\
  >left</span> <span m=\"1363120\">and</span> <span m=\"1363240\">right.</span> <span\
  \ m=\"1363870\">And</span> <span m=\"1363990\">you</span> <span m=\"1364110\">had</span>\
  \ <span m=\"1364200\">to</span> <span m=\"1364290\">decide,</span> <span m=\"1365090\"\
  >what</span> <span m=\"1365670\">are</span> <span m=\"1365730\">the</span> <span\
  \ m=\"1366270\">coordinates</span> <span m=\"1366840\">of</span> <span m=\"1366990\"\
  >those</span> <span m=\"1367200\">vectors?</span> <span m=\"1368560\">It's</span>\
  \ <span m=\"1368670\">a</span> <span m=\"1368790\">bilinear</span> <span m=\"1369300\"\
  >form.</span> <span m=\"1370260\">How</span> <span m=\"1370440\">do</span> <span\
  \ m=\"1370560\">you</span> <span m=\"1370680\">maximize</span> <span m=\"1371250\"\
  >it</span> <span m=\"1371340\">or</span> <span m=\"1371460\">minimize</span> <span\
  \ m=\"1371940\">it?</span> <span m=\"1373090\">You</span> <span m=\"1373290\">have</span>\
  \ <span m=\"1373430\">to</span> <span m=\"1374450\">change</span> <span m=\"1375110\"\
  >every</span> <span m=\"1375350\">entry</span> <span m=\"1375680\">to</span> <span\
  \ m=\"1376010\">one</span> <span m=\"1376280\">of</span> <span m=\"1376850\">its</span>\
  \ <span m=\"1377030\">two</span> <span m=\"1377290\">endpoints.</span> <span m=\"\
  1377900\">Otherwise,</span> <span m=\"1378290\">it</span> <span m=\"1378350\">can</span>\
  \ <span m=\"1378470\">never</span> <span m=\"1378740\">be--</span> <span m=\"1380660\"\
  >you</span> <span m=\"1381110\">never</span> <span m=\"1382010\">lose</span> <span\
  \ m=\"1382430\">by</span> <span m=\"1382610\">doing</span> <span m=\"1382880\">that.</span></p><p><span\
  \ m=\"1384610\">OK,</span> <span m=\"1384790\">so</span> <span m=\"1385040\">think</span>\
  \ <span m=\"1385250\">about</span> <span m=\"1385460\">it.</span> <span m=\"1385950\"\
  >So</span> <span m=\"1386000\">this</span> <span m=\"1386210\">is</span> <span m=\"\
  1389090\">not</span> <span m=\"1389360\">difficult</span> <span m=\"1389960\">once</span>\
  \ <span m=\"1390260\">you</span> <span m=\"1390980\">see</span> <span m=\"1391250\"\
  >it</span> <span m=\"1391340\">the</span> <span m=\"1391430\">right</span> <span\
  \ m=\"1391640\">way.</span> <span m=\"1392610\">But</span> <span m=\"1392630\">now,</span>\
  \ <span m=\"1392990\">we</span> <span m=\"1393350\">have</span> <span m=\"1395120\"\
  >this</span> <span m=\"1395860\">cut</span> <span m=\"1396100\">norm</span> <span\
  \ m=\"1396470\">expressed</span> <span m=\"1397580\">over</span> <span m=\"1397850\"\
  >not</span> <span m=\"1398180\">sets,</span> <span m=\"1398630\">but</span> <span\
  \ m=\"1398990\">over</span> <span m=\"1399260\">bounded</span> <span m=\"1399950\"\
  >functions.</span> <span m=\"1402220\">And</span> <span m=\"1402460\">now</span>\
  \ <span m=\"1402640\">I'm</span> <span m=\"1402760\">ready</span> <span m=\"1402970\"\
  >to</span> <span m=\"1403090\">prove</span> <span m=\"1403840\">the</span> <span\
  \ m=\"1403960\">counting</span> <span m=\"1404300\">lemma.</span></p><p><span m=\"\
  1412400\">And</span> <span m=\"1412760\">instead</span> <span m=\"1413120\">of</span>\
  \ <span m=\"1413240\">writing</span> <span m=\"1413600\">down</span> <span m=\"\
  1413990\">the</span> <span m=\"1414170\">whole</span> <span m=\"1414440\">proof</span>\
  \ <span m=\"1414740\">for</span> <span m=\"1414980\">general</span> <span m=\"1415400\"\
  >H,</span> <span m=\"1416000\">let</span> <span m=\"1416120\">me</span> <span m=\"\
  1416240\">write</span> <span m=\"1416450\">down</span> <span m=\"1416660\">the</span>\
  \ <span m=\"1416720\">calculation</span> <span m=\"1419440\">that</span> <span m=\"\
  1419600\">illustrates</span> <span m=\"1420650\">this</span> <span m=\"1420830\"\
  >proof</span> <span m=\"1421400\">for</span> <span m=\"1421910\">triangles.</span>\
  \ <span m=\"1429460\">And</span> <span m=\"1429580\">the</span> <span m=\"1429640\"\
  >general</span> <span m=\"1429970\">proof</span> <span m=\"1430270\">is</span> <span\
  \ m=\"1430420\">the</span> <span m=\"1430480\">same</span> <span m=\"1430840\">once</span>\
  \ <span m=\"1431080\">you</span> <span m=\"1431170\">understand</span> <span m=\"\
  1431650\">how</span> <span m=\"1431920\">this</span> <span m=\"1432130\">argument</span>\
  \ <span m=\"1432550\">works.</span> <span m=\"1434500\">And</span> <span m=\"1434710\"\
  >the</span> <span m=\"1434770\">argument</span> <span m=\"1435190\">works</span>\
  \ <span m=\"1435640\">by</span> <span m=\"1436720\">considering</span> <span m=\"\
  1439150\">the</span> <span m=\"1439270\">difference</span> <span m=\"1440770\">between</span>\
  \ <span m=\"1442490\">these</span> <span m=\"1442730\">two</span> <span m=\"1446326\"\
  >F</span> <span m=\"1446790\">densities.</span> <span m=\"1449890\">And</span> <span\
  \ m=\"1450340\">what</span> <span m=\"1450580\">I</span> <span m=\"1450700\">want</span>\
  \ <span m=\"1450910\">to</span> <span m=\"1451000\">do</span> <span m=\"1451300\"\
  >is--</span> <span m=\"1452710\">so</span> <span m=\"1452930\">this</span> <span\
  \ m=\"1453110\">is</span> <span m=\"1453200\">some</span> <span m=\"1453410\">integral,</span>\
  \ <span m=\"1453950\">right?</span> <span m=\"1454160\">So</span> <span m=\"1454280\"\
  >this</span> <span m=\"1454490\">is</span> <span m=\"1455590\">this</span> <span\
  \ m=\"1455840\">integral,</span> <span m=\"1456360\">which</span> <span m=\"1456470\"\
  >I'll</span> <span m=\"1456620\">write</span> <span m=\"1456860\">out.</span></p><p><span\
  \ m=\"1481780\">So</span> <span m=\"1484330\">we</span> <span m=\"1484450\">would</span>\
  \ <span m=\"1484540\">like</span> <span m=\"1484690\">to</span> <span m=\"1484810\"\
  >show</span> <span m=\"1485080\">that</span> <span m=\"1485590\">this</span> <span\
  \ m=\"1485860\">quantity</span> <span m=\"1486280\">here</span> <span m=\"1486640\"\
  >is</span> <span m=\"1486850\">small</span> <span m=\"1487660\">if</span> <span\
  \ m=\"1488110\">u</span> <span m=\"1488410\">and</span> <span m=\"1488530\">w</span>\
  \ <span m=\"1488950\">are</span> <span m=\"1489070\">close</span> <span m=\"1489510\"\
  >in</span> <span m=\"1489640\">cut</span> <span m=\"1489900\">norm.</span> <span\
  \ m=\"1491730\">So</span> <span m=\"1492990\">let's</span> <span m=\"1493350\">write</span>\
  \ <span m=\"1493920\">this</span> <span m=\"1494400\">integral</span> <span m=\"\
  1495450\">as</span> <span m=\"1495660\">a</span> <span m=\"1495720\">telescoping</span>\
  \ <span m=\"1496500\">sum</span> <span m=\"1499830\">where</span> <span m=\"1501560\"\
  >the</span> <span m=\"1501680\">first</span> <span m=\"1501980\">term</span> <span\
  \ m=\"1502550\">is</span> <span m=\"1502700\">obtained</span> <span m=\"1503480\"\
  >by--</span> <span m=\"1508990\">so</span> <span m=\"1509170\">by</span> <span m=\"\
  1509320\">this,</span> <span m=\"1509530\">I</span> <span m=\"1509590\">mean</span>\
  \ <span m=\"1509770\">w</span> <span m=\"1510190\">of</span> <span m=\"1510490\"\
  >x,</span> <span m=\"1510700\">comma,</span> <span m=\"1510940\">y</span> <span\
  \ m=\"1511150\">minus</span> <span m=\"1511540\">u</span> <span m=\"1511710\">of</span>\
  \ <span m=\"1511840\">x,</span> <span m=\"1512050\">comma,</span> <span m=\"1512230\"\
  >y.</span></p><p><span m=\"1524440\">And</span> <span m=\"1524560\">then</span>\
  \ <span m=\"1524680\">the</span> <span m=\"1524740\">second</span> <span m=\"1525130\"\
  >term</span> <span m=\"1525520\">of</span> <span m=\"1525640\">the</span> <span\
  \ m=\"1525730\">telescoping</span> <span m=\"1526330\">sum--</span> <span m=\"1527290\"\
  >so</span> <span m=\"1527985\">you</span> <span m=\"1528280\">see</span> <span m=\"\
  1528430\">what</span> <span m=\"1528580\">happens.</span> <span m=\"1528950\">I</span>\
  \ <span m=\"1529060\">change</span> <span m=\"1529570\">one</span> <span m=\"1530020\"\
  >factor</span> <span m=\"1530590\">at</span> <span m=\"1530690\">a</span> <span\
  \ m=\"1530770\">time.</span> <span m=\"1551570\">And</span> <span m=\"1551720\"\
  >finally,</span> <span m=\"1552620\">I</span> <span m=\"1553640\">change</span>\
  \ <span m=\"1554000\">the</span> <span m=\"1554090\">third</span> <span m=\"1554390\"\
  >factor.</span></p><p><span m=\"1569370\">So</span> <span m=\"1569520\">this</span>\
  \ <span m=\"1569700\">is</span> <span m=\"1569870\">the</span> <span m=\"1569920\"\
  >identity.</span> <span m=\"1570300\">If</span> <span m=\"1570420\">you</span> <span\
  \ m=\"1570570\">expand</span> <span m=\"1571200\">out</span> <span m=\"1571410\"\
  >all</span> <span m=\"1571540\">of</span> <span m=\"1571590\">these</span> <span\
  \ m=\"1571800\">differences,</span> <span m=\"1572280\">you</span> <span m=\"1572370\"\
  >see</span> <span m=\"1572550\">that</span> <span m=\"1572670\">everything</span>\
  \ <span m=\"1573150\">intermediate</span> <span m=\"1573660\">cancels</span> <span\
  \ m=\"1574140\">out.</span> <span m=\"1575630\">So</span> <span m=\"1576110\">it's</span>\
  \ <span m=\"1576370\">a</span> <span m=\"1576540\">telescoping</span> <span m=\"\
  1577170\">sum.</span></p><p><span m=\"1579700\">But</span> <span m=\"1579820\">now</span>\
  \ <span m=\"1580540\">I</span> <span m=\"1580660\">want</span> <span m=\"1580870\"\
  >to</span> <span m=\"1580960\">show</span> <span m=\"1581200\">that</span> <span\
  \ m=\"1581380\">each</span> <span m=\"1581680\">term</span> <span m=\"1582340\"\
  >is</span> <span m=\"1582460\">small.</span> <span m=\"1584281\">So</span> <span\
  \ m=\"1584750\">how</span> <span m=\"1584930\">can</span> <span m=\"1585080\">I</span>\
  \ <span m=\"1585140\">show</span> <span m=\"1585350\">that</span> <span m=\"1585470\"\
  >each</span> <span m=\"1585680\">term</span> <span m=\"1585950\">is</span> <span\
  \ m=\"1586070\">small?</span> <span m=\"1588170\">Look</span> <span m=\"1588410\"\
  >at</span> <span m=\"1588800\">this</span> <span m=\"1591590\">expression</span>\
  \ <span m=\"1592160\">here.</span> <span m=\"1594992\">I</span> <span m=\"1595430\"\
  >claim</span> <span m=\"1596330\">that</span> <span m=\"1596570\">for</span> <span\
  \ m=\"1596840\">a</span> <span m=\"1596960\">fixed</span> <span m=\"1597470\">value</span>\
  \ <span m=\"1597890\">of</span> <span m=\"1598010\">z--</span> <span m=\"1605300\"\
  >so</span> <span m=\"1605420\">imagine</span> <span m=\"1605870\">fixing</span>\
  \ <span m=\"1606530\">z.</span> <span m=\"1607490\">And</span> <span m=\"1608000\"\
  >let</span> <span m=\"1608330\">x</span> <span m=\"1608570\">and</span> <span m=\"\
  1608660\">y</span> <span m=\"1608900\">vary</span> <span m=\"1609320\">in</span>\
  \ <span m=\"1609470\">this</span> <span m=\"1609620\">integral.</span></p><p><span\
  \ m=\"1612000\">It</span> <span m=\"1612150\">has</span> <span m=\"1612450\">the</span>\
  \ <span m=\"1612540\">form</span> <span m=\"1612960\">up</span> <span m=\"1613110\"\
  >there,</span> <span m=\"1615410\">right?</span> <span m=\"1615760\">If</span> <span\
  \ m=\"1615880\">you</span> <span m=\"1616000\">fix</span> <span m=\"1616480\">z,</span>\
  \ <span m=\"1617170\">then</span> <span m=\"1618070\">you</span> <span m=\"1618220\"\
  >have</span> <span m=\"1618550\">this</span> <span m=\"1618790\">u</span> <span\
  \ m=\"1619300\">and</span> <span m=\"1619870\">v</span> <span m=\"1620680\">coming</span>\
  \ <span m=\"1621010\">from</span> <span m=\"1621280\">these</span> <span m=\"1621520\"\
  >two</span> <span m=\"1621700\">factors.</span> <span m=\"1622660\">And</span> <span\
  \ m=\"1622750\">they</span> <span m=\"1622830\">are</span> <span m=\"1622930\">both</span>\
  \ <span m=\"1623260\">bounded</span> <span m=\"1623680\">between</span> <span m=\"\
  1624100\">0</span> <span m=\"1624490\">and</span> <span m=\"1624640\">1.</span>\
  \ <span m=\"1628090\">So</span> <span m=\"1628330\">for</span> <span m=\"1628540\"\
  >a</span> <span m=\"1628600\">fixed</span> <span m=\"1628960\">value</span> <span\
  \ m=\"1629320\">of</span> <span m=\"1629410\">z,</span> <span m=\"1630160\">this</span>\
  \ <span m=\"1630790\">is</span> <span m=\"1631230\">at</span> <span m=\"1631390\"\
  >most</span> <span m=\"1635220\">w</span> <span m=\"1636120\">minus</span> <span\
  \ m=\"1637700\">u--</span> <span m=\"1638170\">the</span> <span m=\"1639170\">cut</span>\
  \ <span m=\"1639520\">norm</span> <span m=\"1640320\">difference</span> <span m=\"\
  1640740\">between</span> <span m=\"1641010\">w</span> <span m=\"1641400\">and</span>\
  \ <span m=\"1641520\">u</span> <span m=\"1642150\">in</span> <span m=\"1642360\"\
  >absolute</span> <span m=\"1642840\">value.</span></p><p><span m=\"1647520\">So</span>\
  \ <span m=\"1648770\">if</span> <span m=\"1648950\">I</span> <span m=\"1649070\"\
  >left</span> <span m=\"1649430\">z</span> <span m=\"1649760\">vary,</span> <span\
  \ m=\"1651670\">it</span> <span m=\"1651820\">is</span> <span m=\"1651880\">still</span>\
  \ <span m=\"1652270\">bounded</span> <span m=\"1652740\">in</span> <span m=\"1652870\"\
  >absolute</span> <span m=\"1653290\">value</span> <span m=\"1653590\">by</span>\
  \ <span m=\"1653740\">that</span> <span m=\"1653920\">quantity.</span> <span m=\"\
  1656450\">So</span> <span m=\"1657560\">therefore</span> <span m=\"1658010\">each</span>\
  \ <span m=\"1661330\">is</span> <span m=\"1662110\">bounded</span> <span m=\"1663280\"\
  >by</span> <span m=\"1664030\">w</span> <span m=\"1664360\">minus</span> <span m=\"\
  1664750\">u</span> <span m=\"1666400\">cut</span> <span m=\"1666580\">norm</span>\
  \ <span m=\"1667690\">in</span> <span m=\"1667900\">absolute</span> <span m=\"1668350\"\
  >value.</span> <span m=\"1669910\">Add</span> <span m=\"1670150\">all</span> <span\
  \ m=\"1670270\">three</span> <span m=\"1670480\">of</span> <span m=\"1670540\">them</span>\
  \ <span m=\"1670690\">together.</span> <span m=\"1672410\">We</span> <span m=\"\
  1672460\">find</span> <span m=\"1672880\">that</span> <span m=\"1674290\">the</span>\
  \ <span m=\"1674380\">whole</span> <span m=\"1674560\">thing</span> <span m=\"1675070\"\
  >is</span> <span m=\"1676090\">bounded</span> <span m=\"1676480\">in</span> <span\
  \ m=\"1676630\">absolute</span> <span m=\"1676990\">value</span> <span m=\"1677290\"\
  >by</span> <span m=\"1677440\">3</span> <span m=\"1677740\">times</span> <span m=\"\
  1678220\">the</span> <span m=\"1678370\">cut</span> <span m=\"1678730\">normal</span>\
  \ <span m=\"1679030\">difference.</span></p><p><span m=\"1683350\">OK, and that</span>\
  \ <span m=\"1683680\">finishes</span> <span m=\"1684030\">the</span> <span m=\"\
  1684120\">proof</span> <span m=\"1684450\">of</span> <span m=\"1684570\">the</span>\
  \ <span m=\"1684630\">counting</span> <span m=\"1684980\">lemma.</span> <span m=\"\
  1686660\">For</span> <span m=\"1686810\">triangles,</span> <span m=\"1687650\">of</span>\
  \ <span m=\"1687710\">course,</span> <span m=\"1688100\">if</span> <span m=\"1688190\"\
  >you</span> <span m=\"1688340\">have</span> <span m=\"1688760\">general</span> <span\
  \ m=\"1689330\">H,</span> <span m=\"1690050\">then</span> <span m=\"1690710\">you</span>\
  \ <span m=\"1690800\">just</span> <span m=\"1690980\">have</span> <span m=\"1691130\"\
  >more</span> <span m=\"1691310\">terms.</span> <span m=\"1692600\">You</span> <span\
  \ m=\"1692960\">have</span> <span m=\"1693110\">a</span> <span m=\"1693140\">longer</span>\
  \ <span m=\"1693470\">telescoping</span> <span m=\"1694110\">sum,</span> <span m=\"\
  1695750\">and</span> <span m=\"1695870\">you</span> <span m=\"1695960\">have</span>\
  \ <span m=\"1696050\">this</span> <span m=\"1696120\">bound.</span></p><p><span\
  \ m=\"1698330\">OK.</span> <span m=\"1698540\">So</span> <span m=\"1698660\">this</span>\
  \ <span m=\"1698840\">is</span> <span m=\"1698930\">a</span> <span m=\"1699030\"\
  >counting</span> <span m=\"1699310\">lemma.</span> <span m=\"1699450\">And I</span>\
  \ <span m=\"1699680\">claim</span> <span m=\"1699960\">that it's</span> <span m=\"\
  1700130\">exactly</span> <span m=\"1700550\">the</span> <span m=\"1700640\">same</span>\
  \ <span m=\"1700910\">proof</span> <span m=\"1701510\">as</span> <span m=\"1701660\"\
  >the</span> <span m=\"1701720\">second</span> <span m=\"1702080\">proof</span> <span\
  \ m=\"1702350\">of</span> <span m=\"1702440\">the</span> <span m=\"1702530\">counting</span>\
  \ <span m=\"1702830\">lemma</span> <span m=\"1703010\">that</span> <span m=\"1703280\"\
  >we</span> <span m=\"1703310\">did</span> <span m=\"1703840\">when</span> <span\
  \ m=\"1704000\">we</span> <span m=\"1704150\">discussed</span> <span m=\"1705000\"\
  >Szemer\xE9di's</span> <span m=\"1705470\">regularity</span> <span m=\"1706010\"\
  >lemma</span> <span m=\"1706280\">and</span> <span m=\"1706460\">this</span> <span\
  \ m=\"1706580\">counting</span> <span m=\"1706910\">lemma.</span> <span m=\"1710220\"\
  >Any</span> <span m=\"1710370\">questions?</span> <span m=\"1713210\">Yeah.</span></p><p><span\
  \ m=\"1717082\">AUDIENCE:</span> <span m=\"1717203\">Why</span> <span m=\"1717324\"\
  >did</span> <span m=\"1717445\">it</span> <span m=\"1717566\">suffice</span> <span\
  \ m=\"1718050\">to prove</span> <span m=\"1718534\">over</span> <span m=\"1719018\"\
  >the</span> <span m=\"1719502\">[INAUDIBLE]?</span></p><p><span m=\"1722890\">PROFESSOR:</span>\
  \ <span m=\"1722980\">OK.</span> <span m=\"1723070\">So</span> <span m=\"1724140\"\
  >let</span> <span m=\"1724230\">me</span> <span m=\"1724650\">answer</span> <span\
  \ m=\"1724860\">that</span> <span m=\"1725010\">in</span> <span m=\"1725100\">a</span>\
  \ <span m=\"1725160\">second.</span> <span m=\"1725460\">So</span> <span m=\"1725860\"\
  >first,</span> <span m=\"1726070\">this</span> <span m=\"1726400\">should be</span>\
  \ <span m=\"1726900\">H,</span> <span m=\"1727200\">not</span> <span m=\"1727450\"\
  >F.</span> <span m=\"1728050\">OK,</span> <span m=\"1728280\">so</span> <span m=\"\
  1728430\">your</span> <span m=\"1728550\">question</span> <span m=\"1728940\">was,</span>\
  \ <span m=\"1730610\">up</span> <span m=\"1731095\">there,</span> <span m=\"1734790\"\
  >why</span> <span m=\"1735000\">was</span> <span m=\"1735390\">it</span> <span m=\"\
  1736170\">sufficient</span> <span m=\"1736740\">to</span> <span m=\"1737430\">prove</span>\
  \ <span m=\"1738180\">this</span> <span m=\"1738570\">version</span> <span m=\"\
  1739050\">instead</span> <span m=\"1739350\">of</span> <span m=\"1739440\">that</span>\
  \ <span m=\"1739650\">version?</span> <span m=\"1740640\">Is</span> <span m=\"1740760\"\
  >that</span> <span m=\"1740900\">the</span> <span m=\"1740940\">question?</span></p><p><span\
  \ m=\"1741240\">AUDIENCE:</span> <span m=\"1741482\">Yeah.</span></p><p><span m=\"\
  1742210\">PROFESSOR:</span> <span m=\"1742265\">OK.</span> <span m=\"1742760\">Suppose</span>\
  \ <span m=\"1743170\">I</span> <span m=\"1743220\">prove it</span> <span m=\"1743600\"\
  >for</span> <span m=\"1743750\">this</span> <span m=\"1743960\">version.</span>\
  \ <span m=\"1744970\">So</span> <span m=\"1745280\">I</span> <span m=\"1745370\"\
  >know</span> <span m=\"1746100\">this</span> <span m=\"1746210\">is</span> <span\
  \ m=\"1746330\">true.</span> <span m=\"1746870\">Now</span> <span m=\"1747110\"\
  >I</span> <span m=\"1747210\">take</span> <span m=\"1747560\">infimum</span> <span\
  \ m=\"1748010\">of</span> <span m=\"1748130\">both</span> <span m=\"1748370\">sides.</span>\
  \ <span m=\"1749610\">So</span> <span m=\"1749660\">now</span> <span m=\"1750320\"\
  >I</span> <span m=\"1753370\">consider</span> <span m=\"1755830\">infimum</span>\
  \ <span m=\"1755920\">of</span> <span m=\"1756220\">both</span> <span m=\"1756400\"\
  >sides.</span></p><p><span m=\"1757990\">So</span> <span m=\"1758110\">then</span>\
  \ <span m=\"1758350\">this</span> <span m=\"1758560\">is</span> <span m=\"1760840\"\
  >true,</span> <span m=\"1761180\">right?</span> <span m=\"1761380\">Because</span>\
  \ <span m=\"1761640\">it's</span> <span m=\"1761760\">true</span> <span m=\"1761940\"\
  >for</span> <span m=\"1762090\">every</span> <span m=\"1762360\">phi.</span> <span\
  \ m=\"1764440\">But</span> <span m=\"1764620\">the</span> <span m=\"1764740\">left-hand</span>\
  \ <span m=\"1765310\">side</span> <span m=\"1765760\">doesn't</span> <span m=\"\
  1766090\">change,</span> <span m=\"1766930\">because</span> <span m=\"1767500\"\
  >the</span> <span m=\"1767720\">F</span> <span m=\"1767950\">density</span> <span\
  \ m=\"1768490\">in</span> <span m=\"1769110\">a</span> <span m=\"1769400\">relabeling</span>\
  \ <span m=\"1770080\">of</span> <span m=\"1770140\">the</span> <span m=\"1770230\"\
  >vertices,</span> <span m=\"1770950\">it's</span> <span m=\"1771100\">still</span>\
  \ <span m=\"1772120\">the</span> <span m=\"1772210\">same</span> <span m=\"1772450\"\
  >quantity,</span> <span m=\"1772930\">whereas</span> <span m=\"1773620\">this</span>\
  \ <span m=\"1773860\">one</span> <span m=\"1774130\">here</span> <span m=\"1774370\"\
  >is</span> <span m=\"1774490\">now</span> <span m=\"1774720\">that.</span></p><p><span\
  \ m=\"1780226\">All right.</span> <span m=\"1784600\">So</span> <span m=\"1787540\"\
  >what</span> <span m=\"1787660\">we</span> <span m=\"1787810\">see</span> <span\
  \ m=\"1788170\">as</span> <span m=\"1788350\">a</span> <span m=\"1788440\">corollary</span>\
  \ <span m=\"1791730\">of</span> <span m=\"1791880\">this</span> <span m=\"1792060\"\
  >counting</span> <span m=\"1792410\">lemma</span> <span m=\"1793320\">is</span>\
  \ <span m=\"1793470\">that</span> <span m=\"1794160\">if</span> <span m=\"1794430\"\
  >you</span> <span m=\"1794730\">are</span> <span m=\"1795810\">a</span> <span m=\"\
  1795930\">Cauchy</span> <span m=\"1796290\">sequence</span> <span m=\"1797640\"\
  >with</span> <span m=\"1797850\">respect</span> <span m=\"1798540\">to</span> <span\
  \ m=\"1800030\">the</span> <span m=\"1800190\">cut</span> <span m=\"1800460\">distance,</span>\
  \ <span m=\"1803300\">then</span> <span m=\"1806360\">the</span> <span m=\"1806450\"\
  >sequence</span> <span m=\"1806940\">is</span> <span m=\"1807230\">automatically</span>\
  \ <span m=\"1808220\">convergent.</span> <span m=\"1815810\">So recall</span> <span\
  \ m=\"1816160\">the</span> <span m=\"1816250\">definition</span> <span m=\"1816730\"\
  >of</span> <span m=\"1816790\">convergence.</span> <span m=\"1817330\">Convergence</span>\
  \ <span m=\"1817840\">has</span> <span m=\"1818020\">to</span> <span m=\"1818110\"\
  >do</span> <span m=\"1818350\">with</span> <span m=\"1819210\">F</span> <span m=\"\
  1819430\">densities</span> <span m=\"1819960\">converging.</span> <span m=\"1820920\"\
  >And</span> <span m=\"1821080\">if</span> <span m=\"1821230\">you</span> <span m=\"\
  1821320\">have</span> <span m=\"1821530\">a</span> <span m=\"1821560\">Cauchy</span>\
  \ <span m=\"1821910\">sequence,</span> <span m=\"1822940\">then</span> <span m=\"\
  1823270\">the</span> <span m=\"1823360\">F</span> <span m=\"1823570\">densities</span>\
  \ <span m=\"1824010\">converge.</span></p><p><span m=\"1825970\">And</span> <span\
  \ m=\"1826090\">also,</span> <span m=\"1827000\">a</span> <span m=\"1827080\">related</span>\
  \ <span m=\"1827560\">but</span> <span m=\"1827680\">different</span> <span m=\"\
  1828070\">statement</span> <span m=\"1829000\">is</span> <span m=\"1829150\">that</span>\
  \ <span m=\"1829540\">if</span> <span m=\"1833770\">you</span> <span m=\"1833860\"\
  >have</span> <span m=\"1833980\">a</span> <span m=\"1834040\">sequence</span> <span\
  \ m=\"1834460\">wn</span> <span m=\"1835030\">that</span> <span m=\"1835180\">converges</span>\
  \ <span m=\"1835840\">to</span> <span m=\"1836020\">w</span> <span m=\"1836500\"\
  >in</span> <span m=\"1836950\">cut</span> <span m=\"1837220\">distance,</span> <span\
  \ m=\"1839060\">then</span> <span m=\"1841040\">it</span> <span m=\"1841160\">implies</span>\
  \ <span m=\"1841730\">that</span> <span m=\"1841940\">wn</span> <span m=\"1842840\"\
  >converges</span> <span m=\"1843470\">to</span> <span m=\"1843560\">w</span> <span\
  \ m=\"1844850\">in</span> <span m=\"1844990\">the</span> <span m=\"1845030\">sense</span>\
  \ <span m=\"1845810\">as</span> <span m=\"1845990\">defined</span> <span m=\"1846800\"\
  >for</span> <span m=\"1847340\">F</span> <span m=\"1847520\">densities.</span> <span\
  \ m=\"1851880\">So</span> <span m=\"1853110\">qualitatively,</span> <span m=\"1853830\"\
  >what</span> <span m=\"1853980\">the</span> <span m=\"1854070\">counting</span>\
  \ <span m=\"1854400\">lemma</span> <span m=\"1854550\">says</span> <span m=\"1855270\"\
  >is</span> <span m=\"1855390\">that</span> <span m=\"1855480\">the</span> <span\
  \ m=\"1855570\">cut</span> <span m=\"1855860\">norm</span> <span m=\"1856440\">is</span>\
  \ <span m=\"1856560\">stronger</span> <span m=\"1857580\">than</span> <span m=\"\
  1858600\">the</span> <span m=\"1859410\">notion</span> <span m=\"1859800\">of</span>\
  \ <span m=\"1859890\">convergence</span> <span m=\"1860550\">coming</span> <span\
  \ m=\"1860880\">from</span> <span m=\"1861480\">subgraph</span> <span m=\"1862080\"\
  >densities.</span></p><p><span m=\"1865260\">So</span> <span m=\"1865440\">this</span>\
  \ <span m=\"1865620\">is</span> <span m=\"1866400\">one</span> <span m=\"1866640\"\
  >part</span> <span m=\"1867000\">of</span> <span m=\"1867180\">this</span> <span\
  \ m=\"1867360\">regularity</span> <span m=\"1867990\">method,</span> <span m=\"\
  1868660\">so</span> <span m=\"1868710\">the</span> <span m=\"1868830\">counting</span>\
  \ <span m=\"1869180\">lemma.</span> <span m=\"1869460\">Of</span> <span m=\"1869830\"\
  >course,</span> <span m=\"1870060\">the</span> <span m=\"1870210\">other</span>\
  \ <span m=\"1870480\">part</span> <span m=\"1870750\">is</span> <span m=\"1870900\"\
  >the</span> <span m=\"1870990\">regularity</span> <span m=\"1871620\">lemma</span>\
  \ <span m=\"1871860\">itself.</span> <span m=\"1872800\">So</span> <span m=\"1872850\"\
  >that's</span> <span m=\"1873090\">the</span> <span m=\"1873180\">next</span> <span\
  \ m=\"1873420\">thing</span> <span m=\"1873600\">we'll</span> <span m=\"1873760\"\
  >do.</span> <span m=\"1877020\">And</span> <span m=\"1877170\">it</span> <span m=\"\
  1877260\">turns</span> <span m=\"1877500\">out</span> <span m=\"1877680\">that</span>\
  \ <span m=\"1877830\">we</span> <span m=\"1878250\">actually</span> <span m=\"1878610\"\
  >don't</span> <span m=\"1878820\">need</span> <span m=\"1879030\">the</span> <span\
  \ m=\"1879120\">full</span> <span m=\"1879390\">strength</span> <span m=\"1879870\"\
  >of</span> <span m=\"1879960\">the</span> <span m=\"1880050\">regularity</span>\
  \ <span m=\"1880650\">lemma.</span> <span m=\"1881190\">We</span> <span m=\"1881340\"\
  >only</span> <span m=\"1881580\">need</span> <span m=\"1881790\">something</span>\
  \ <span m=\"1882120\">called</span> <span m=\"1882330\">a</span> <span m=\"1882390\"\
  >weak</span> <span m=\"1882810\">regularity</span> <span m=\"1883490\">lemma.</span></p><p><span\
  \ m=\"1897660\">What</span> <span m=\"1897910\">the</span> <span m=\"1898000\">weak</span>\
  \ <span m=\"1898240\">regularity</span> <span m=\"1898780\">lemma</span> <span m=\"\
  1899110\">says</span> <span m=\"1899920\">is--</span> <span m=\"1901690\">I</span>\
  \ <span m=\"1901720\">mean,</span> <span m=\"1901870\">you</span> <span m=\"1902080\"\
  >still</span> <span m=\"1902320\">have</span> <span m=\"1902500\">a</span> <span\
  \ m=\"1902560\">partition</span> <span m=\"1903550\">of</span> <span m=\"1903850\"\
  >the</span> <span m=\"1903970\">vertices.</span> <span m=\"1904850\">So</span> <span\
  \ m=\"1904870\">let</span> <span m=\"1904990\">me</span> <span m=\"1905080\">now</span>\
  \ <span m=\"1905260\">state</span> <span m=\"1905530\">it</span> <span m=\"1905620\"\
  >for</span> <span m=\"1905770\">graphons.</span> <span m=\"1906370\">So</span> <span\
  \ m=\"1906820\">for</span> <span m=\"1907930\">a</span> <span m=\"1908020\">partition</span>\
  \ <span m=\"1910990\">p--</span> <span m=\"1913110\">so</span> <span m=\"1914040\"\
  >I</span> <span m=\"1914130\">have</span> <span m=\"1914280\">a</span> <span m=\"\
  1914310\">partition</span> <span m=\"1915480\">of</span> <span m=\"1916110\">the</span>\
  \ <span m=\"1916200\">vertex</span> <span m=\"1916620\">set--</span> <span m=\"\
  1924120\">and</span> <span m=\"1926530\">a</span> <span m=\"1926920\">symmetric,</span>\
  \ <span m=\"1928090\">measurable</span> <span m=\"1928570\">function</span> <span\
  \ m=\"1930850\">w--</span> <span m=\"1933100\">I'm</span> <span m=\"1933250\">just</span>\
  \ <span m=\"1933400\">going</span> <span m=\"1933580\">to</span> <span m=\"1933670\"\
  >omit</span> <span m=\"1933940\">the</span> <span m=\"1934000\">word</span> <span\
  \ m=\"1934270\">&quot;measurable&quot;</span> <span m=\"1934750\">from</span> <span\
  \ m=\"1934990\">now</span> <span m=\"1935170\">on.</span> <span m=\"1936080\">Everything</span>\
  \ <span m=\"1936310\">will</span> <span m=\"1936430\">be</span> <span m=\"1936520\"\
  >measurable.</span></p><p><span m=\"1938990\">What</span> <span m=\"1939070\">I</span>\
  \ <span m=\"1939160\">can</span> <span m=\"1939310\">do</span> <span m=\"1940210\"\
  >is,</span> <span m=\"1940750\">OK,</span> <span m=\"1941050\">all</span> <span\
  \ m=\"1941200\">of</span> <span m=\"1941290\">these</span> <span m=\"1941800\">assets</span>\
  \ <span m=\"1942160\">are</span> <span m=\"1942250\">also</span> <span m=\"1943540\"\
  >measurable.</span> <span m=\"1947780\">I</span> <span m=\"1947800\">can</span>\
  \ <span m=\"1947950\">define</span> <span m=\"1948700\">what's</span> <span m=\"\
  1948910\">known</span> <span m=\"1949150\">as</span> <span m=\"1949270\">a</span>\
  \ <span m=\"1949600\">stepping</span> <span m=\"1950080\">operator</span> <span\
  \ m=\"1956260\">that</span> <span m=\"1956660\">sends</span> <span m=\"1957380\"\
  >w</span> <span m=\"1958130\">to</span> <span m=\"1958520\">this</span> <span m=\"\
  1958730\">object,</span> <span m=\"1959690\">w</span> <span m=\"1959990\">sub</span>\
  \ <span m=\"1960210\">p,</span> <span m=\"1962050\">obtained</span> <span m=\"1963190\"\
  >by</span> <span m=\"1964390\">averaging</span> <span m=\"1968480\">over</span>\
  \ <span m=\"1969680\">the</span> <span m=\"1969770\">steps</span> <span m=\"1972760\"\
  >si</span> <span m=\"1973530\">cross</span> <span m=\"1973980\">sj</span> <span\
  \ m=\"1975210\">and</span> <span m=\"1975390\">replacing</span> <span m=\"1976110\"\
  >that</span> <span m=\"1976230\">graphon</span> <span m=\"1977070\">by</span> <span\
  \ m=\"1977340\">its</span> <span m=\"1977610\">average</span> <span m=\"1978270\"\
  >over</span> <span m=\"1978570\">each</span> <span m=\"1978840\">step.</span></p><p><span\
  \ m=\"1981490\">Precisely,</span> <span m=\"1986260\">so</span> <span m=\"1986410\"\
  >I</span> <span m=\"1986500\">obtain</span> <span m=\"1986830\">a</span> <span m=\"\
  1986860\">new</span> <span m=\"1987040\">graphon,</span> <span m=\"1987900\">a</span>\
  \ <span m=\"1988180\">new</span> <span m=\"1988780\">symmetric,</span> <span m=\"\
  1989320\">measurable</span> <span m=\"1989680\">function,</span> <span m=\"1990290\"\
  >w</span> <span m=\"1990440\">sub</span> <span m=\"1990580\">p,</span> <span m=\"\
  1991630\">where</span> <span m=\"1994850\">the</span> <span m=\"1995000\">value</span>\
  \ <span m=\"1997310\">on</span> <span m=\"1997670\">x,</span> <span m=\"1997910\"\
  >comma,</span> <span m=\"1998130\">y</span> <span m=\"1998960\">is</span> <span\
  \ m=\"1999110\">defined</span> <span m=\"2000100\">to</span> <span m=\"2000250\"\
  >be</span> <span m=\"2002280\">the</span> <span m=\"2002370\">following</span> <span\
  \ m=\"2002850\">quantity--</span> <span m=\"2010610\">if</span> <span m=\"2012740\"\
  >x,</span> <span m=\"2012980\">comma,</span> <span m=\"2013190\">y</span> <span\
  \ m=\"2013580\">lies</span> <span m=\"2013895\">in</span> <span m=\"2016300\">si</span>\
  \ <span m=\"2016830\">cross</span> <span m=\"2017510\">sj.</span> <span m=\"2019040\"\
  >So</span> <span m=\"2019250\">pictorially,</span> <span m=\"2020390\">what</span>\
  \ <span m=\"2020540\">happens</span> <span m=\"2020960\">is</span> <span m=\"2021080\"\
  >that</span> <span m=\"2021200\">you</span> <span m=\"2022100\">look</span> <span\
  \ m=\"2022370\">at</span> <span m=\"2022760\">your</span> <span m=\"2023390\">graphon.</span>\
  \ <span m=\"2027540\">There's</span> <span m=\"2027750\">a</span> <span m=\"2027810\"\
  >partition</span> <span m=\"2028590\">of</span> <span m=\"2028830\">the</span> <span\
  \ m=\"2030390\">vertex</span> <span m=\"2030826\">set,</span> <span m=\"2031262\"\
  >so to speak,</span> <span m=\"2031700\">the</span> <span m=\"2031830\">interval.</span>\
  \ <span m=\"2032970\">Doesn't</span> <span m=\"2033240\">have</span> <span m=\"\
  2033390\">to</span> <span m=\"2033480\">be</span> <span m=\"2033600\">a</span> <span\
  \ m=\"2033660\">partition</span> <span m=\"2034050\">into</span> <span m=\"2034320\"\
  >intervals,</span> <span m=\"2034770\">but</span> <span m=\"2034910\">for</span>\
  \ <span m=\"2035040\">illustration,</span> <span m=\"2035660\">suppose</span> <span\
  \ m=\"2036380\">it</span> <span m=\"2036560\">looks</span> <span m=\"2036780\">like</span>\
  \ <span m=\"2036930\">that.</span></p><p><span m=\"2037850\">And</span> <span m=\"\
  2038010\">what</span> <span m=\"2038190\">I</span> <span m=\"2038310\">do</span>\
  \ <span m=\"2038550\">is</span> <span m=\"2038820\">I</span> <span m=\"2039090\"\
  >take</span> <span m=\"2039330\">this</span> <span m=\"2039510\">w,</span> <span\
  \ m=\"2040170\">and</span> <span m=\"2040280\">I</span> <span m=\"2040590\">replace</span>\
  \ <span m=\"2041160\">it</span> <span m=\"2041850\">by</span> <span m=\"2042060\"\
  >a</span> <span m=\"2042120\">new</span> <span m=\"2044210\">graphon,</span> <span\
  \ m=\"2044790\">a</span> <span m=\"2044850\">new</span> <span m=\"2045090\">symmetric,</span>\
  \ <span m=\"2045510\">measurable</span> <span m=\"2045870\">function,</span> <span\
  \ m=\"2046590\">w</span> <span m=\"2046860\">sub</span> <span m=\"2047030\">p,</span>\
  \ <span m=\"2047760\">obtained</span> <span m=\"2049739\">by</span> <span m=\"2051780\"\
  >averaging.</span> <span m=\"2056421\">Take</span> <span m=\"2056880\">each</span>\
  \ <span m=\"2057090\">box.</span> <span m=\"2057600\">Replace</span> <span m=\"\
  2058050\">it by</span> <span m=\"2058199\">its</span> <span m=\"2058320\">average.</span>\
  \ <span m=\"2058860\">Put</span> <span m=\"2059040\">that</span> <span m=\"2059159\"\
  >average</span> <span m=\"2059520\">into</span> <span m=\"2059730\">the</span> <span\
  \ m=\"2059820\">box.</span> <span m=\"2062310\">So</span> <span m=\"2062429\">this</span>\
  \ <span m=\"2062659\">is</span> <span m=\"2062820\">what</span> <span m=\"2063150\"\
  >w sub</span> <span m=\"2063590\">p</span> <span m=\"2064030\">is</span> <span m=\"\
  2064110\">supposed</span> <span m=\"2064469\">to</span> <span m=\"2064560\">be.</span></p><p><span\
  \ m=\"2066920\">Just</span> <span m=\"2067100\">a</span> <span m=\"2067130\">few</span>\
  \ <span m=\"2067760\">minor</span> <span m=\"2068210\">technicalities.</span> <span\
  \ m=\"2069710\">If</span> <span m=\"2072620\">this</span> <span m=\"2072889\">denominator</span>\
  \ <span m=\"2073580\">is</span> <span m=\"2074030\">equal</span> <span m=\"2074300\"\
  >to</span> <span m=\"2074389\">0,</span> <span m=\"2075320\">let's</span> <span\
  \ m=\"2077060\">ignore</span> <span m=\"2079290\">the</span> <span m=\"2079380\"\
  >set.</span> <span m=\"2079690\">I</span> <span m=\"2079760\">mean,</span> <span\
  \ m=\"2079889\">then</span> <span m=\"2081330\">you</span> <span m=\"2081420\">have</span>\
  \ <span m=\"2081540\">a</span> <span m=\"2081570\">zero</span> <span m=\"2081810\"\
  >measure</span> <span m=\"2082080\">set,</span> <span m=\"2082320\">anyway,</span>\
  \ <span m=\"2082679\">so</span> <span m=\"2083100\">we</span> <span m=\"2083909\"\
  >ignore</span> <span m=\"2084270\">that</span> <span m=\"2084480\">set.</span> <span\
  \ m=\"2084820\">So</span> <span m=\"2084870\">everything</span> <span m=\"2085260\"\
  >will</span> <span m=\"2085350\">be</span> <span m=\"2085469\">treated</span> <span\
  \ m=\"2085830\">up</span> <span m=\"2085980\">to</span> <span m=\"2086130\">measure</span>\
  \ <span m=\"2086429\">zero,</span> <span m=\"2087330\">changing</span> <span m=\"\
  2088199\">the</span> <span m=\"2088320\">function</span> <span m=\"2088650\">on</span>\
  \ <span m=\"2088739\">measure</span> <span m=\"2088949\">zero</span> <span m=\"\
  2089219\">sets.</span> <span m=\"2089850\">So</span> <span m=\"2090150\">it</span>\
  \ <span m=\"2090420\">doesn't</span> <span m=\"2090690\">really</span> <span m=\"\
  2090870\">matter</span> <span m=\"2092920\">if</span> <span m=\"2093070\">you're</span>\
  \ <span m=\"2093190\">not</span> <span m=\"2093639\">strictly</span> <span m=\"\
  2094030\">allowed</span> <span m=\"2094239\">to</span> <span m=\"2094330\">do</span>\
  \ <span m=\"2094480\">this</span> <span m=\"2094659\">division.</span></p><p><span\
  \ m=\"2098310\">OK.</span> <span m=\"2099200\">So</span> <span m=\"2099500\">this</span>\
  \ <span m=\"2100070\">operator</span> <span m=\"2100730\">plays</span> <span m=\"\
  2101090\">an</span> <span m=\"2101150\">important</span> <span m=\"2101570\">role</span>\
  \ <span m=\"2101990\">in</span> <span m=\"2102350\">the</span> <span m=\"2102530\"\
  >regularity</span> <span m=\"2103170\">lemma,</span> <span m=\"2103430\">because</span>\
  \ <span m=\"2103680\">it's</span> <span m=\"2103820\">how</span> <span m=\"2104000\"\
  >we</span> <span m=\"2104150\">think</span> <span m=\"2104420\">about</span> <span\
  \ m=\"2105140\">partitioning,</span> <span m=\"2106010\">what</span> <span m=\"\
  2106190\">happens</span> <span m=\"2106580\">to</span> <span m=\"2106700\">a</span>\
  \ <span m=\"2106750\">graph</span> <span m=\"2107050\">under</span> <span m=\"2107240\"\
  >partitioning.</span> <span m=\"2108260\">It</span> <span m=\"2108350\">has</span>\
  \ <span m=\"2108650\">several</span> <span m=\"2109130\">other</span> <span m=\"\
  2109400\">names</span> <span m=\"2111260\">if</span> <span m=\"2111380\">you</span>\
  \ <span m=\"2111500\">look</span> <span m=\"2111680\">at</span> <span m=\"2111770\"\
  >it</span> <span m=\"2111860\">from</span> <span m=\"2112250\">slightly</span> <span\
  \ m=\"2112640\">different</span> <span m=\"2112910\">perspectives.</span></p><p><span\
  \ m=\"2114060\">So</span> <span m=\"2114800\">you</span> <span m=\"2114890\">can</span>\
  \ <span m=\"2115040\">view</span> <span m=\"2115250\">it</span> <span m=\"2115760\"\
  >as</span> <span m=\"2116270\">a</span> <span m=\"2116930\">projection</span> <span\
  \ m=\"2119400\">in</span> <span m=\"2119520\">the</span> <span m=\"2119580\">sense</span>\
  \ <span m=\"2119910\">of</span> <span m=\"2121350\">Hilbert</span> <span m=\"2121680\"\
  >space.</span> <span m=\"2122280\">So</span> <span m=\"2122580\">in</span> <span\
  \ m=\"2122760\">the</span> <span m=\"2122880\">Hilbert</span> <span m=\"2123240\"\
  >space</span> <span m=\"2127530\">of</span> <span m=\"2128280\">functions</span>\
  \ <span m=\"2133250\">on</span> <span m=\"2133430\">the</span> <span m=\"2133520\"\
  >unit</span> <span m=\"2133820\">square,</span> <span m=\"2135170\">the</span> <span\
  \ m=\"2135320\">stepping</span> <span m=\"2135770\">operator</span> <span m=\"2136520\"\
  >is</span> <span m=\"2136730\">a</span> <span m=\"2136790\">projection</span> <span\
  \ m=\"2137780\">unto</span> <span m=\"2139700\">the</span> <span m=\"2140660\">subspace</span>\
  \ <span m=\"2144840\">of</span> <span m=\"2146010\">constants,</span> <span m=\"\
  2147570\">subspace</span> <span m=\"2148140\">of</span> <span m=\"2148770\">functions</span>\
  \ <span m=\"2152090\">that</span> <span m=\"2152270\">are</span> <span m=\"2152450\"\
  >constant</span> <span m=\"2155440\">on</span> <span m=\"2155720\">each</span> <span\
  \ m=\"2156290\">step.</span> <span m=\"2165210\">So</span> <span m=\"2165240\">that's</span>\
  \ <span m=\"2165420\">one</span> <span m=\"2165600\">interpretation.</span></p><p><span\
  \ m=\"2166920\">Another</span> <span m=\"2167250\">interpretation</span> <span m=\"\
  2167940\">is</span> <span m=\"2168060\">that</span> <span m=\"2168270\">this</span>\
  \ <span m=\"2168450\">operation</span> <span m=\"2169320\">is</span> <span m=\"\
  2169470\">also</span> <span m=\"2169860\">a</span> <span m=\"2170490\">conditional</span>\
  \ <span m=\"2171120\">expectation.</span> <span m=\"2177340\">If</span> <span m=\"\
  2177490\">you</span> <span m=\"2179020\">know</span> <span m=\"2179290\">what</span>\
  \ <span m=\"2180200\">a</span> <span m=\"2180250\">conditional</span> <span m=\"\
  2180730\">expectation</span> <span m=\"2181480\">actually</span> <span m=\"2181900\"\
  >is</span> <span m=\"2182200\">in</span> <span m=\"2182320\">the</span> <span m=\"\
  2182410\">sense</span> <span m=\"2182650\">of</span> <span m=\"2182710\">probability</span>\
  \ <span m=\"2183280\">theory,</span> <span m=\"2185130\">so</span> <span m=\"2185490\"\
  >then</span> <span m=\"2185890\">that's</span> <span m=\"2186100\">what</span> <span\
  \ m=\"2186220\">happens</span> <span m=\"2186520\">here.</span> <span m=\"2186940\"\
  >If</span> <span m=\"2187090\">you</span> <span m=\"2187240\">view</span> <span\
  \ m=\"2188110\">0,</span> <span m=\"2188350\">1</span> <span m=\"2188560\">squared</span>\
  \ <span m=\"2188950\">as</span> <span m=\"2189100\">a</span> <span m=\"2189130\"\
  >probability</span> <span m=\"2189700\">space,</span> <span m=\"2190720\">then</span>\
  \ <span m=\"2191710\">what</span> <span m=\"2191950\">we're</span> <span m=\"2192100\"\
  >doing</span> <span m=\"2192640\">is</span> <span m=\"2193360\">we're</span> <span\
  \ m=\"2193510\">doing</span> <span m=\"2193750\">conditional</span> <span m=\"2194260\"\
  >expectation</span> <span m=\"2195340\">relative</span> <span m=\"2195880\">to</span>\
  \ <span m=\"2196630\">the</span> <span m=\"2196750\">sigma</span> <span m=\"2197140\"\
  >algebra</span> <span m=\"2197950\">generated</span> <span m=\"2198520\">by</span>\
  \ <span m=\"2198940\">these</span> <span m=\"2199300\">steps.</span></p><p><span\
  \ m=\"2202320\">So</span> <span m=\"2202480\">these</span> <span m=\"2202630\">are</span>\
  \ <span m=\"2202690\">just</span> <span m=\"2202870\">a</span> <span m=\"2202890\"\
  >couple</span> <span m=\"2203100\">of</span> <span m=\"2203140\">ways</span> <span\
  \ m=\"2203350\">of</span> <span m=\"2203440\">thinking</span> <span m=\"2203710\"\
  >about</span> <span m=\"2203860\">what's</span> <span m=\"2204040\">going</span>\
  \ <span m=\"2204280\">on.</span> <span m=\"2204560\">They</span> <span m=\"2204640\"\
  >might</span> <span m=\"2204940\">be</span> <span m=\"2205120\">somewhat</span>\
  \ <span m=\"2205510\">helpful</span> <span m=\"2205840\">later</span> <span m=\"\
  2206140\">on</span> <span m=\"2206290\">if</span> <span m=\"2206440\">you're</span>\
  \ <span m=\"2206560\">familiar</span> <span m=\"2206950\">with</span> <span m=\"\
  2207100\">these</span> <span m=\"2207220\">notions.</span> <span m=\"2207620\">But</span>\
  \ <span m=\"2207760\">if</span> <span m=\"2207850\">you're not,</span> <span m=\"\
  2207950\">don't</span> <span m=\"2208440\">worry</span> <span m=\"2208660\">about</span>\
  \ <span m=\"2208870\">it.</span> <span m=\"2209830\">Concretely,</span> <span m=\"\
  2210400\">it's</span> <span m=\"2210580\">what</span> <span m=\"2210730\">happens</span>\
  \ <span m=\"2211060\">up</span> <span m=\"2211200\">there.</span></p><p><span m=\"\
  2218340\">OK.</span> <span m=\"2218990\">So</span> <span m=\"2219110\">now</span>\
  \ <span m=\"2219320\">let</span> <span m=\"2219470\">me</span> <span m=\"2219590\"\
  >state</span> <span m=\"2220160\">the</span> <span m=\"2220580\">weak</span> <span\
  \ m=\"2221030\">regularity</span> <span m=\"2221660\">lemma.</span> <span m=\"2233530\"\
  >So</span> <span m=\"2233670\">the</span> <span m=\"2233760\">weak</span> <span\
  \ m=\"2234000\">regularity</span> <span m=\"2234550\">lemma</span> <span m=\"2235380\"\
  >is</span> <span m=\"2236130\">attributed</span> <span m=\"2236550\">to</span> <span\
  \ m=\"2237150\">Frieze</span> <span m=\"2237720\">and</span> <span m=\"2237920\"\
  >Kannan,</span> <span m=\"2243750\">although</span> <span m=\"2243960\">their</span>\
  \ <span m=\"2244180\">work</span> <span m=\"2244480\">predates</span> <span m=\"\
  2245800\">the</span> <span m=\"2245920\">language</span> <span m=\"2246340\">of</span>\
  \ <span m=\"2246420\">graphons.</span> <span m=\"2247540\">So</span> <span m=\"\
  2247690\">it's</span> <span m=\"2247810\">stated</span> <span m=\"2248560\">in</span>\
  \ <span m=\"2248680\">the</span> <span m=\"2248950\">language</span> <span m=\"\
  2249250\">of</span> <span m=\"2249310\">graphs,</span> <span m=\"2249760\">but</span>\
  \ <span m=\"2250050\">it's</span> <span m=\"2250210\">the</span> <span m=\"2250300\"\
  >same</span> <span m=\"2250510\">proof.</span> <span m=\"2250720\">So</span> <span\
  \ m=\"2250870\">let</span> <span m=\"2250960\">me</span> <span m=\"2251140\">state</span>\
  \ <span m=\"2251410\">it</span> <span m=\"2251650\">for</span> <span m=\"2251860\"\
  >you</span> <span m=\"2252040\">both</span> <span m=\"2252400\">in</span> <span\
  \ m=\"2252550\">terms</span> <span m=\"2252820\">of</span> <span m=\"2252970\">graphons</span>\
  \ <span m=\"2253410\">and</span> <span m=\"2253590\">in</span> <span m=\"2253690\"\
  >graphs.</span></p><p><span m=\"2255070\">What</span> <span m=\"2255220\">it</span>\
  \ <span m=\"2255280\">says</span> <span m=\"2255550\">is</span> <span m=\"2255670\"\
  >that</span> <span m=\"2255760\">for</span> <span m=\"2255940\">every</span> <span\
  \ m=\"2256600\">epsilon</span> <span m=\"2258890\">and</span> <span m=\"2259490\"\
  >every</span> <span m=\"2259790\">graphon</span> <span m=\"2262160\">w,</span> <span\
  \ m=\"2268160\">there</span> <span m=\"2268340\">exists</span> <span m=\"2269480\"\
  >a</span> <span m=\"2269630\">partition</span> <span m=\"2273950\">denoted</span>\
  \ <span m=\"2274630\">p</span> <span m=\"2277170\">of the</span> <span m=\"2277530\"\
  >0,</span> <span m=\"2277820\">1</span> <span m=\"2278790\">interval.</span> <span\
  \ m=\"2280760\">And</span> <span m=\"2280860\">now</span> <span m=\"2281070\">I</span>\
  \ <span m=\"2281160\">tell</span> <span m=\"2281400\">you</span> <span m=\"2281730\"\
  >how</span> <span m=\"2281910\">many</span> <span m=\"2282150\">sets</span> <span\
  \ m=\"2282480\">there</span> <span m=\"2282670\">are.</span> <span m=\"2283110\"\
  >So</span> <span m=\"2283350\">it's</span> <span m=\"2283470\">a</span> <span m=\"\
  2283530\">partition</span> <span m=\"2284760\">into--</span> <span m=\"2285320\"\
  >so</span> <span m=\"2285510\">not</span> <span m=\"2285900\">a</span> <span m=\"\
  2285960\">tower-type</span> <span m=\"2287160\">number</span> <span m=\"2287430\"\
  >of</span> <span m=\"2287490\">parts,</span> <span m=\"2288300\">but</span> <span\
  \ m=\"2288960\">only</span> <span m=\"2289830\">roughly</span> <span m=\"2290190\"\
  >an</span> <span m=\"2290310\">exponential</span> <span m=\"2290970\">number</span>\
  \ <span m=\"2291270\">of</span> <span m=\"2291360\">parts--</span> <span m=\"2291920\"\
  >4</span> <span m=\"2292580\">to</span> <span m=\"2292730\">the</span> <span m=\"\
  2292800\">1</span> <span m=\"2293100\">over</span> <span m=\"2293430\">epsilon</span>\
  \ <span m=\"2293910\">squared</span> <span m=\"2296480\">measurable</span> <span\
  \ m=\"2296900\">sets</span> <span m=\"2301980\">such</span> <span m=\"2302250\"\
  >that</span> <span m=\"2306050\">if</span> <span m=\"2306170\">we</span> <span m=\"\
  2306350\">apply</span> <span m=\"2306800\">the</span> <span m=\"2306890\">stepping</span>\
  \ <span m=\"2307340\">operator</span> <span m=\"2308540\">to</span> <span m=\"2308720\"\
  >this</span> <span m=\"2308900\">graphon,</span> <span m=\"2309710\">we</span> <span\
  \ m=\"2310100\">obtain</span> <span m=\"2310640\">an</span> <span m=\"2310760\"\
  >approximation</span> <span m=\"2312290\">of</span> <span m=\"2312410\">the</span>\
  \ <span m=\"2312500\">graphon</span> <span m=\"2313790\">in</span> <span m=\"2314540\"\
  >the</span> <span m=\"2314750\">cut</span> <span m=\"2315040\">norm.</span></p><p><span\
  \ m=\"2320520\">So</span> <span m=\"2320640\">that's</span> <span m=\"2320880\"\
  >the</span> <span m=\"2320970\">statement</span> <span m=\"2321450\">of</span> <span\
  \ m=\"2321630\">the</span> <span m=\"2321780\">weak</span> <span m=\"2322260\">regularity</span>\
  \ <span m=\"2323130\">lemma.</span> <span m=\"2325050\">There</span> <span m=\"\
  2325200\">exists</span> <span m=\"2325490\">a</span> <span m=\"2325530\">partition</span>\
  \ <span m=\"2326610\">such</span> <span m=\"2326880\">that</span> <span m=\"2327540\"\
  >if</span> <span m=\"2327690\">you</span> <span m=\"2328140\">do</span> <span m=\"\
  2329760\">this</span> <span m=\"2330720\">stepping,</span> <span m=\"2331620\">then</span>\
  \ <span m=\"2331980\">you</span> <span m=\"2332100\">obtain</span> <span m=\"2332430\"\
  >an</span> <span m=\"2332550\">approximation.</span> <span m=\"2333460\">So</span>\
  \ <span m=\"2333480\">I</span> <span m=\"2333570\">want you</span> <span m=\"2333750\"\
  >to</span> <span m=\"2333810\">think</span> <span m=\"2333960\">about</span> <span\
  \ m=\"2334230\">what</span> <span m=\"2334560\">this</span> <span m=\"2334800\"\
  >has</span> <span m=\"2335010\">to</span> <span m=\"2335100\">do</span> <span m=\"\
  2335850\">with</span> <span m=\"2336120\">the</span> <span m=\"2336210\">usual</span>\
  \ <span m=\"2336690\">version</span> <span m=\"2337110\">of</span> <span m=\"2337340\"\
  >Szemer\xE9di's</span> <span m=\"2337710\">regularity</span> <span m=\"2338260\"\
  >lemma</span> <span m=\"2338420\">that</span> <span m=\"2338600\">you've</span>\
  \ <span m=\"2338700\">seen</span> <span m=\"2338940\">earlier.</span> <span m=\"\
  2340030\">So</span> <span m=\"2340400\">hopefully,</span> <span m=\"2340800\">you</span>\
  \ <span m=\"2340920\">should</span> <span m=\"2341070\">realize,</span> <span m=\"\
  2341370\">morally,</span> <span m=\"2341970\">they're</span> <span m=\"2342270\"\
  >about</span> <span m=\"2342600\">the</span> <span m=\"2342660\">same</span> <span\
  \ m=\"2343020\">types</span> <span m=\"2343500\">of</span> <span m=\"2343560\">statements.</span>\
  \ <span m=\"2344660\">But</span> <span m=\"2344910\">more</span> <span m=\"2345090\"\
  >importantly,</span> <span m=\"2345580\">how</span> <span m=\"2345690\">are</span>\
  \ <span m=\"2345750\">they</span> <span m=\"2345900\">different</span> <span m=\"\
  2346230\">from</span> <span m=\"2346410\">each</span> <span m=\"2346590\">other?</span></p><p><span\
  \ m=\"2347980\">And</span> <span m=\"2348060\">now</span> <span m=\"2348220\">let</span>\
  \ <span m=\"2348330\">me</span> <span m=\"2348450\">state</span> <span m=\"2348660\"\
  >a</span> <span m=\"2348790\">version</span> <span m=\"2349180\">for</span> <span\
  \ m=\"2349470\">graphs,</span> <span m=\"2351370\">which</span> <span m=\"2351540\"\
  >is</span> <span m=\"2352200\">similar</span> <span m=\"2352620\">but</span> <span\
  \ m=\"2352740\">not</span> <span m=\"2352920\">exactly</span> <span m=\"2353340\"\
  >the</span> <span m=\"2353430\">same</span> <span m=\"2353790\">as</span> <span\
  \ m=\"2353940\">what</span> <span m=\"2355380\">we</span> <span m=\"2355560\">just</span>\
  \ <span m=\"2355740\">saw</span> <span m=\"2356070\">for</span> <span m=\"2356250\"\
  >graphons.</span> <span m=\"2357090\">So</span> <span m=\"2358650\">let</span> <span\
  \ m=\"2358770\">me</span> <span m=\"2358860\">state</span> <span m=\"2359130\">it.</span>\
  \ <span m=\"2359520\">So</span> <span m=\"2359640\">for</span> <span m=\"2359790\"\
  >graphs,</span> <span m=\"2365010\">the</span> <span m=\"2365180\">weak</span> <span\
  \ m=\"2365420\">regularity</span> <span m=\"2366050\">lemma</span> <span m=\"2366300\"\
  >says</span> <span m=\"2367190\">that,</span> <span m=\"2369780\">OK,</span> <span\
  \ m=\"2369960\">so</span> <span m=\"2370570\">for</span> <span m=\"2370660\">graphs,</span>\
  \ <span m=\"2371110\">let</span> <span m=\"2371230\">me</span> <span m=\"2371320\"\
  >define</span> <span m=\"2372760\">a</span> <span m=\"2374080\">partition</span>\
  \ <span m=\"2376420\">p</span> <span m=\"2380110\">of</span> <span m=\"2380210\"\
  >the</span> <span m=\"2380300\">vertex</span> <span m=\"2380730\">set</span> <span\
  \ m=\"2383650\">is</span> <span m=\"2383920\">called</span> <span m=\"2386680\"\
  >weakly</span> <span m=\"2387280\">epsilon</span> <span m=\"2387760\">regular</span>\
  \ <span m=\"2395130\">if</span> <span m=\"2395490\">the</span> <span m=\"2395610\"\
  >following</span> <span m=\"2396120\">is</span> <span m=\"2396300\">true.</span></p><p><span\
  \ m=\"2398360\">If</span> <span m=\"2398510\">it</span> <span m=\"2398600\">is</span>\
  \ <span m=\"2398690\">the</span> <span m=\"2398780\">case</span> <span m=\"2399110\"\
  >that</span> <span m=\"2399710\">whenever</span> <span m=\"2400160\">I</span> <span\
  \ m=\"2400340\">look</span> <span m=\"2400580\">at</span> <span m=\"2400940\">two</span>\
  \ <span m=\"2402170\">vertex</span> <span m=\"2402650\">subsets,</span> <span m=\"\
  2403055\">A</span> <span m=\"2403460\">and</span> <span m=\"2403760\">B,</span>\
  \ <span m=\"2405270\">of</span> <span m=\"2405440\">the</span> <span m=\"2405530\"\
  >vertex</span> <span m=\"2405920\">set</span> <span m=\"2406100\">of</span> <span\
  \ m=\"2406190\">g,</span> <span m=\"2407930\">then</span> <span m=\"2408650\">the</span>\
  \ <span m=\"2408770\">number</span> <span m=\"2409220\">of</span> <span m=\"2409340\"\
  >vertices</span> <span m=\"2410870\">between</span> <span m=\"2411215\">A</span>\
  \ <span m=\"2411560\">and</span> <span m=\"2411800\">B</span> <span m=\"2413880\"\
  >is</span> <span m=\"2414750\">what</span> <span m=\"2415020\">you</span> <span\
  \ m=\"2415200\">should</span> <span m=\"2415530\">expect</span> <span m=\"2417750\"\
  >based</span> <span m=\"2418260\">on</span> <span m=\"2418650\">the</span> <span\
  \ m=\"2419340\">density</span> <span m=\"2420030\">information</span> <span m=\"\
  2421350\">that</span> <span m=\"2421530\">comes</span> <span m=\"2422070\">out</span>\
  \ <span m=\"2422670\">of</span> <span m=\"2422820\">this</span> <span m=\"2423000\"\
  >partition.</span> <span m=\"2424710\">Namely,</span> <span m=\"2425940\">if</span>\
  \ <span m=\"2426090\">I</span> <span m=\"2426180\">sum</span> <span m=\"2426600\"\
  >over</span> <span m=\"2427290\">all</span> <span m=\"2427470\">the</span> <span\
  \ m=\"2427590\">parts</span> <span m=\"2430700\">of</span> <span m=\"2430820\">the</span>\
  \ <span m=\"2430910\">partition,</span> <span m=\"2432830\">look</span> <span m=\"\
  2433070\">at</span> <span m=\"2435410\">how</span> <span m=\"2435650\">many</span>\
  \ <span m=\"2436730\">vertices</span> <span m=\"2442480\">from</span> <span m=\"\
  2442750\">A</span> <span m=\"2443080\">lie</span> <span m=\"2443860\">in</span>\
  \ <span m=\"2444010\">the</span> <span m=\"2444130\">corresponding</span> <span\
  \ m=\"2444970\">parts.</span> <span m=\"2446200\">And</span> <span m=\"2446320\"\
  >then</span> <span m=\"2446440\">multiply</span> <span m=\"2447610\">by</span> <span\
  \ m=\"2448450\">the</span> <span m=\"2448660\">edge</span> <span m=\"2449140\">density</span>\
  \ <span m=\"2450100\">between</span> <span m=\"2450400\">these</span> <span m=\"\
  2450580\">parts.</span> <span m=\"2451090\">So</span> <span m=\"2451240\">that's</span>\
  \ <span m=\"2451570\">your</span> <span m=\"2451840\">predicted</span> <span m=\"\
  2452430\">value</span> <span m=\"2452770\">based</span> <span m=\"2453130\">on</span>\
  \ <span m=\"2453220\">the</span> <span m=\"2453310\">data</span> <span m=\"2453700\"\
  >that</span> <span m=\"2453820\">comes</span> <span m=\"2454150\">out</span> <span\
  \ m=\"2454330\">of</span> <span m=\"2454390\">the</span> <span m=\"2454480\">partition.</span></p><p><span\
  \ m=\"2455900\">So I</span> <span m=\"2456100\">claim</span> <span m=\"2456340\"\
  >that</span> <span m=\"2456460\">this</span> <span m=\"2456670\">is</span> <span\
  \ m=\"2456850\">the</span> <span m=\"2457000\">actual</span> <span m=\"2457420\"\
  >number</span> <span m=\"2457690\">of</span> <span m=\"2457780\">edges.</span> <span\
  \ m=\"2458170\">This</span> <span m=\"2458380\">is</span> <span m=\"2458590\">the</span>\
  \ <span m=\"2459130\">predicted</span> <span m=\"2459570\">number</span> <span m=\"\
  2459820\">of</span> <span m=\"2459990\">edges.</span> <span m=\"2460720\">And</span>\
  \ <span m=\"2460840\">those</span> <span m=\"2461080\">two</span> <span m=\"2461230\"\
  >numbers</span> <span m=\"2461680\">should</span> <span m=\"2461920\">be</span>\
  \ <span m=\"2462100\">similar</span> <span m=\"2462580\">to</span> <span m=\"2462790\"\
  >each</span> <span m=\"2463030\">other</span> <span m=\"2467280\">bt at</span> <span\
  \ m=\"2467510\">most</span> <span m=\"2467870\">epsilon</span> <span m=\"2469000\"\
  >n,</span> <span m=\"2469370\">where</span> <span m=\"2469550\">n is</span> <span\
  \ m=\"2469840\">the</span> <span m=\"2469940\">number</span> <span m=\"2470180\"\
  >of</span> <span m=\"2470240\">vertices.</span> <span m=\"2471380\">So</span> <span\
  \ m=\"2471500\">this</span> <span m=\"2471710\">is</span> <span m=\"2471830\">the</span>\
  \ <span m=\"2471950\">definition</span> <span m=\"2472910\">of</span> <span m=\"\
  2473090\">what</span> <span m=\"2473240\">it</span> <span m=\"2473330\">means</span>\
  \ <span m=\"2473630\">for</span> <span m=\"2473840\">a</span> <span m=\"2474200\"\
  >partition</span> <span m=\"2474680\">to</span> <span m=\"2474800\">be</span> <span\
  \ m=\"2475130\">weakly</span> <span m=\"2475910\">epsilon</span> <span m=\"2476390\"\
  >regular.</span></p><p><span m=\"2478700\">So</span> <span m=\"2479020\">it's</span>\
  \ <span m=\"2479200\">important</span> <span m=\"2479530\">to</span> <span m=\"\
  2479590\">think</span> <span m=\"2479800\">about</span> <span m=\"2480220\">why</span>\
  \ <span m=\"2480730\">this</span> <span m=\"2481000\">is</span> <span m=\"2481150\"\
  >weaker.</span> <span m=\"2482310\">It's</span> <span m=\"2482410\">called</span>\
  \ <span m=\"2482590\">weak,</span> <span m=\"2483020\">right?</span> <span m=\"\
  2483190\">So</span> <span m=\"2483310\">why</span> <span m=\"2483550\">is</span>\
  \ <span m=\"2483670\">it</span> <span m=\"2483730\">weaker</span> <span m=\"2484150\"\
  >than</span> <span m=\"2484320\">a</span> <span m=\"2484390\">notion</span> <span\
  \ m=\"2484750\">of</span> <span m=\"2484900\">epsilon</span> <span m=\"2485350\"\
  >regularity?</span> <span m=\"2488150\">So</span> <span m=\"2488170\">why</span>\
  \ <span m=\"2488350\">is</span> <span m=\"2488530\">it</span> <span m=\"2488590\"\
  >weaker?</span></p><p><span m=\"2490450\">So</span> <span m=\"2490660\">previously,</span>\
  \ <span m=\"2491200\">we</span> <span m=\"2491350\">had</span> <span m=\"2492340\"\
  >epsilon-regular</span> <span m=\"2493180\">partition</span> <span m=\"2494110\"\
  >in</span> <span m=\"2494230\">the</span> <span m=\"2494290\">definition</span>\
  \ <span m=\"2494860\">of</span> <span m=\"2495430\">Szemer\xE9di's</span> <span\
  \ m=\"2496150\">regularity</span> <span m=\"2496640\">lemma,</span> <span m=\"2496900\"\
  >this</span> <span m=\"2497140\">epsilon-regular</span> <span m=\"2497890\">partition.</span>\
  \ <span m=\"2498880\">And</span> <span m=\"2499040\">here,</span> <span m=\"2499930\"\
  >notion</span> <span m=\"2500290\">of</span> <span m=\"2500500\">weakly</span> <span\
  \ m=\"2501100\">epsilon</span> <span m=\"2501550\">regular.</span> <span m=\"2503350\"\
  >So</span> <span m=\"2503480\">why</span> <span m=\"2503700\">is</span> <span m=\"\
  2503790\">this</span> <span m=\"2503960\">a</span> <span m=\"2504020\">lot</span>\
  \ <span m=\"2504230\">weaker?</span></p><p><span m=\"2507460\">It</span> <span m=\"\
  2507610\">is</span> <span m=\"2507760\">not</span> <span m=\"2508450\">saying</span>\
  \ <span m=\"2509590\">that</span> <span m=\"2510070\">individual</span> <span m=\"\
  2511000\">pairs</span> <span m=\"2511480\">of</span> <span m=\"2511540\">parts</span>\
  \ <span m=\"2512050\">are</span> <span m=\"2512200\">epsilon</span> <span m=\"2513100\"\
  >regular.</span> <span m=\"2515780\">And</span> <span m=\"2515960\">eventually,</span>\
  \ <span m=\"2516360\">we're</span> <span m=\"2516450\">going</span> <span m=\"2516580\"\
  >to</span> <span m=\"2516630\">have</span> <span m=\"2516810\">this</span> <span\
  \ m=\"2516990\">number</span> <span m=\"2517230\">of</span> <span m=\"2517320\"\
  >parts.</span> <span m=\"2517730\">So</span> <span m=\"2517850\">I'll</span> <span\
  \ m=\"2518020\">state</span> <span m=\"2518290\">a</span> <span m=\"2518400\">theorem</span>\
  \ <span m=\"2518520\">in</span> <span m=\"2518660\">a</span> <span m=\"2518700\"\
  >second.</span> <span m=\"2520210\">So</span> <span m=\"2520620\">the</span> <span\
  \ m=\"2520830\">sizes</span> <span m=\"2521820\">of</span> <span m=\"2521940\">the</span>\
  \ <span m=\"2522030\">parts</span> <span m=\"2523110\">are</span> <span m=\"2523200\"\
  >much</span> <span m=\"2523500\">smaller</span> <span m=\"2524070\">than</span>\
  \ <span m=\"2524490\">epsilon</span> <span m=\"2524940\">fraction.</span></p><p><span\
  \ m=\"2527380\">But</span> <span m=\"2527530\">what</span> <span m=\"2527740\">this</span>\
  \ <span m=\"2527950\">weak</span> <span m=\"2529230\">notion</span> <span m=\"2529650\"\
  >of</span> <span m=\"2530070\">regularity</span> <span m=\"2530730\">says,</span>\
  \ <span m=\"2531660\">if</span> <span m=\"2531810\">you</span> <span m=\"2531900\"\
  >look</span> <span m=\"2532080\">at</span> <span m=\"2532170\">it</span> <span m=\"\
  2532290\">globally--</span> <span m=\"2533950\">so</span> <span m=\"2534270\">not</span>\
  \ <span m=\"2534540\">looking</span> <span m=\"2534810\">at</span> <span m=\"2534900\"\
  >specific</span> <span m=\"2535410\">parts,</span> <span m=\"2535740\">but</span>\
  \ <span m=\"2535860\">looking</span> <span m=\"2536190\">at</span> <span m=\"2536310\"\
  >it</span> <span m=\"2536520\">globally--</span> <span m=\"2537450\">then</span>\
  \ <span m=\"2537600\">this</span> <span m=\"2537810\">partition</span> <span m=\"\
  2538350\">is</span> <span m=\"2538470\">a</span> <span m=\"2538530\">good</span>\
  \ <span m=\"2538740\">approximation</span> <span m=\"2539670\">of</span> <span m=\"\
  2539790\">what's</span> <span m=\"2540000\">going</span> <span m=\"2540240\">on</span>\
  \ <span m=\"2540370\">in</span> <span m=\"2540480\">the</span> <span m=\"2540570\"\
  >actual</span> <span m=\"2540960\">graph,</span> <span m=\"2543050\">whereas--</span>\
  \ <span m=\"2544280\">OK,</span> <span m=\"2544500\">so</span> <span m=\"2544920\"\
  >it's</span> <span m=\"2545040\">worth</span> <span m=\"2545220\">thinking</span>\
  \ <span m=\"2545520\">about.</span> <span m=\"2545710\">It's</span> <span m=\"2545820\"\
  >really</span> <span m=\"2546000\">worth</span> <span m=\"2546150\">thinking</span>\
  \ <span m=\"2546420\">about</span> <span m=\"2546600\">what's</span> <span m=\"\
  2546780\">the</span> <span m=\"2546840\">difference</span> <span m=\"2547170\">between</span>\
  \ <span m=\"2548040\">this</span> <span m=\"2548250\">weak</span> <span m=\"2548490\"\
  >notion</span> <span m=\"2548910\">and</span> <span m=\"2549030\">the</span> <span\
  \ m=\"2549120\">usual</span> <span m=\"2549450\">notion.</span></p><p><span m=\"\
  2549990\">But</span> <span m=\"2550380\">first,</span> <span m=\"2550590\">let</span>\
  \ <span m=\"2550680\">me</span> <span m=\"2550830\">state</span> <span m=\"2551640\"\
  >this</span> <span m=\"2552420\">regularity</span> <span m=\"2553040\">lemma.</span>\
  \ <span m=\"2553380\">So</span> <span m=\"2553560\">the</span> <span m=\"2553680\"\
  >weak</span> <span m=\"2555600\">regularity</span> <span m=\"2556230\">lemma</span>\
  \ <span m=\"2558090\">for</span> <span m=\"2558410\">graphs</span> <span m=\"2563330\"\
  >says</span> <span m=\"2563810\">that</span> <span m=\"2564350\">for</span> <span\
  \ m=\"2565100\">every</span> <span m=\"2565370\">epsilon</span> <span m=\"2566770\"\
  >and</span> <span m=\"2566900\">every</span> <span m=\"2567650\">graph</span> <span\
  \ m=\"2567980\">G,</span> <span m=\"2570820\">there</span> <span m=\"2571000\">exists</span>\
  \ <span m=\"2572680\">a</span> <span m=\"2575380\">weakly</span> <span m=\"2577270\"\
  >epsilon-regular</span> <span m=\"2579250\">partition</span> <span m=\"2583360\"\
  >of</span> <span m=\"2583510\">the</span> <span m=\"2583630\">vertex</span> <span\
  \ m=\"2584050\">set</span> <span m=\"2584260\">of</span> <span m=\"2584350\">G</span>\
  \ <span m=\"2585820\">into</span> <span m=\"2587200\">at</span> <span m=\"2587350\"\
  >most</span> <span m=\"2588540\">4</span> <span m=\"2589090\">to</span> <span m=\"\
  2589310\">the</span> <span m=\"2589390\">1</span> <span m=\"2589750\">over</span>\
  \ <span m=\"2590080\">epsilon</span> <span m=\"2590560\">squared</span> <span m=\"\
  2591110\">parts.</span></p><p><span m=\"2600240\">Now,</span> <span m=\"2600560\"\
  >you</span> <span m=\"2600680\">might</span> <span m=\"2600830\">wonder</span> <span\
  \ m=\"2601070\">why</span> <span m=\"2603470\">did</span> <span m=\"2603590\">Frieze</span>\
  \ <span m=\"2603950\">and Kannan</span> <span m=\"2604280\">come</span> <span m=\"\
  2604520\">up</span> <span m=\"2604640\">with</span> <span m=\"2604760\">this</span>\
  \ <span m=\"2604910\">notion</span> <span m=\"2605270\">of</span> <span m=\"2605360\"\
  >regularity.</span> <span m=\"2609010\">It's</span> <span m=\"2609160\">a</span>\
  \ <span m=\"2609220\">weaker</span> <span m=\"2609550\">result</span> <span m=\"\
  2610300\">if</span> <span m=\"2610450\">you</span> <span m=\"2610510\">don't</span>\
  \ <span m=\"2610690\">care</span> <span m=\"2610930\">about</span> <span m=\"2611110\"\
  >the</span> <span m=\"2611200\">bounds,</span> <span m=\"2612010\">because</span>\
  \ <span m=\"2613240\">an</span> <span m=\"2613930\">epsilon-regular</span> <span\
  \ m=\"2615040\">partition</span> <span m=\"2616210\">will</span> <span m=\"2616540\"\
  >be</span> <span m=\"2616870\">automatically</span> <span m=\"2618070\">weakly</span>\
  \ <span m=\"2619390\">epsilon</span> <span m=\"2619840\">regular.</span> <span m=\"\
  2621360\">So</span> <span m=\"2621570\">maybe</span> <span m=\"2621840\">with</span>\
  \ <span m=\"2621960\">small</span> <span m=\"2622290\">changes</span> <span m=\"\
  2622680\">of</span> <span m=\"2622770\">epsilon</span> <span m=\"2623220\">if</span>\
  \ <span m=\"2623340\">you</span> <span m=\"2623430\">wish,</span> <span m=\"2623670\"\
  >but</span> <span m=\"2624150\">basically,</span> <span m=\"2624650\">this</span>\
  \ <span m=\"2625290\">is</span> <span m=\"2625410\">a</span> <span m=\"2625470\"\
  >weaker</span> <span m=\"2625740\">notion</span> <span m=\"2626370\">compared</span>\
  \ <span m=\"2626760\">to</span> <span m=\"2626850\">what</span> <span m=\"2626970\"\
  >we</span> <span m=\"2627120\">had</span> <span m=\"2627300\">before.</span></p><p><span\
  \ m=\"2630780\">But</span> <span m=\"2631010\">of</span> <span m=\"2631130\">course,</span>\
  \ <span m=\"2631470\">the</span> <span m=\"2631490\">advantage</span> <span m=\"\
  2632100\">is</span> <span m=\"2632210\">that</span> <span m=\"2632330\">you</span>\
  \ <span m=\"2632450\">have</span> <span m=\"2633020\">a</span> <span m=\"2633080\"\
  >much</span> <span m=\"2633350\">more</span> <span m=\"2633560\">reasonable</span>\
  \ <span m=\"2634130\">number</span> <span m=\"2634430\">of</span> <span m=\"2634490\"\
  >parts.</span> <span m=\"2636230\">It's</span> <span m=\"2636320\">not</span> <span\
  \ m=\"2636710\">a</span> <span m=\"2636800\">tower.</span> <span m=\"2638210\">It's</span>\
  \ <span m=\"2638420\">just</span> <span m=\"2638750\">a</span> <span m=\"2638810\"\
  >single</span> <span m=\"2639260\">exponential.</span></p><p><span m=\"2641180\"\
  >And</span> <span m=\"2641360\">this</span> <span m=\"2641540\">is</span> <span\
  \ m=\"2641660\">important.</span> <span m=\"2642110\">And</span> <span m=\"2642200\"\
  >their</span> <span m=\"2642380\">motivation</span> <span m=\"2643250\">was</span>\
  \ <span m=\"2644240\">a</span> <span m=\"2644450\">computer</span> <span m=\"2644840\"\
  >science</span> <span m=\"2645140\">and</span> <span m=\"2645260\">algorithm</span>\
  \ <span m=\"2645740\">application.</span> <span m=\"2646760\">So</span> <span m=\"\
  2646880\">I</span> <span m=\"2646940\">want</span> <span m=\"2647090\">to</span>\
  \ <span m=\"2647180\">take</span> <span m=\"2647330\">a</span> <span m=\"2647750\"\
  >brief</span> <span m=\"2648020\">detour</span> <span m=\"2648470\">and</span> <span\
  \ m=\"2648590\">mention</span> <span m=\"2651410\">why</span> <span m=\"2651770\"\
  >you</span> <span m=\"2651860\">might</span> <span m=\"2652040\">care</span> <span\
  \ m=\"2652310\">about</span> <span m=\"2655660\">weakly</span> <span m=\"2656120\"\
  >epsilon-regular</span> <span m=\"2656990\">partitions.</span></p><p><span m=\"\
  2662180\">In</span> <span m=\"2662270\">particular,</span> <span m=\"2662810\">the</span>\
  \ <span m=\"2662960\">problem</span> <span m=\"2663500\">that</span> <span m=\"\
  2664070\">is</span> <span m=\"2664250\">of</span> <span m=\"2664400\">interest</span>\
  \ <span m=\"2665240\">is</span> <span m=\"2665840\">in</span> <span m=\"2666080\"\
  >approximating</span> <span m=\"2667160\">something</span> <span m=\"2667520\">called</span>\
  \ <span m=\"2667720\">a</span> <span m=\"2667790\">max</span> <span m=\"2668210\"\
  >cut.</span> <span m=\"2670980\">So</span> <span m=\"2671130\">the</span> <span\
  \ m=\"2671430\">max</span> <span m=\"2671850\">cut</span> <span m=\"2672130\">problem</span>\
  \ <span m=\"2672900\">asks</span> <span m=\"2673320\">you</span> <span m=\"2673500\"\
  >to</span> <span m=\"2674190\">determine--</span> <span m=\"2675210\">given</span>\
  \ <span m=\"2676250\">a</span> <span m=\"2676350\">graph</span> <span m=\"2676830\"\
  >G,</span> <span m=\"2678060\">find</span> <span m=\"2680430\">the</span> <span\
  \ m=\"2680520\">maximum</span> <span m=\"2682140\">over</span> <span m=\"2682510\"\
  >all</span> <span m=\"2682770\">subsets</span> <span m=\"2683310\">of</span> <span\
  \ m=\"2683370\">vertices,</span> <span m=\"2686360\">the</span> <span m=\"2686640\"\
  >maximum</span> <span m=\"2687180\">number</span> <span m=\"2687480\">of</span>\
  \ <span m=\"2687540\">vertices</span> <span m=\"2688530\">between</span> <span m=\"\
  2689140\">a</span> <span m=\"2689190\">set</span> <span m=\"2689610\">and</span>\
  \ <span m=\"2689760\">its</span> <span m=\"2689880\">complement.</span> <span m=\"\
  2691040\">That's</span> <span m=\"2691220\">called</span> <span m=\"2691400\">a</span>\
  \ <span m=\"2691470\">cut.</span> <span m=\"2692430\">I</span> <span m=\"2692520\"\
  >give</span> <span m=\"2692700\">you</span> <span m=\"2692850\">a</span> <span m=\"\
  2692910\">graph,</span> <span m=\"2694300\">and</span> <span m=\"2694440\">I</span>\
  \ <span m=\"2694530\">want</span> <span m=\"2694710\">to</span> <span m=\"2694800\"\
  >know--</span> <span m=\"2696430\">find</span> <span m=\"2697180\">this</span> <span\
  \ m=\"2697660\">s</span> <span m=\"2698200\">so</span> <span m=\"2698380\">that</span>\
  \ <span m=\"2700480\">it</span> <span m=\"2700540\">can</span> <span m=\"2700690\"\
  >have</span> <span m=\"2700870\">as</span> <span m=\"2701020\">many</span> <span\
  \ m=\"2701470\">edges</span> <span m=\"2701860\">across</span> <span m=\"2702340\"\
  >this</span> <span m=\"2702850\">set</span> <span m=\"2703210\">as</span> <span\
  \ m=\"2703330\">possible.</span></p><p><span m=\"2705560\">This</span> <span m=\"\
  2705640\">is</span> <span m=\"2705700\">an</span> <span m=\"2705760\">important</span>\
  \ <span m=\"2706120\">problem</span> <span m=\"2706330\">in</span> <span m=\"2706390\"\
  >computer</span> <span m=\"2706690\">science,</span> <span m=\"2707530\">extremely</span>\
  \ <span m=\"2707980\">important</span> <span m=\"2708310\">problem.</span> <span\
  \ m=\"2709120\">And</span> <span m=\"2710470\">the</span> <span m=\"2710680\">status</span>\
  \ <span m=\"2711280\">of</span> <span m=\"2711370\">this</span> <span m=\"2711520\"\
  >problem</span> <span m=\"2712270\">is</span> <span m=\"2712450\">that</span> <span\
  \ m=\"2712900\">it</span> <span m=\"2713080\">is</span> <span m=\"2713230\">known</span>\
  \ <span m=\"2713590\">to</span> <span m=\"2713710\">be</span> <span m=\"2713890\"\
  >difficult</span> <span m=\"2715120\">to</span> <span m=\"2716770\">get</span> <span\
  \ m=\"2717010\">it</span> <span m=\"2717700\">even</span> <span m=\"2718060\">within</span>\
  \ <span m=\"2718540\">1%.</span> <span m=\"2720640\">So</span> <span m=\"2720790\"\
  >the</span> <span m=\"2720880\">best</span> <span m=\"2721180\">algorithm</span>\
  \ <span m=\"2722110\">is</span> <span m=\"2722290\">due</span> <span m=\"2722440\"\
  >to</span> <span m=\"2722680\">Goemans</span> <span m=\"2723130\">and</span> <span\
  \ m=\"2723220\">Williamson.</span></p><p><span m=\"2730410\">It's an</span> <span\
  \ m=\"2730560\">important</span> <span m=\"2730980\">algorithm</span> <span m=\"\
  2731550\">that</span> <span m=\"2731700\">was</span> <span m=\"2732120\">one</span>\
  \ <span m=\"2732330\">of</span> <span m=\"2732390\">the</span> <span m=\"2732480\"\
  >foundational</span> <span m=\"2733020\">algorithms</span> <span m=\"2733560\">in</span>\
  \ <span m=\"2733650\">semidefinite</span> <span m=\"2734340\">programming,</span>\
  \ <span m=\"2734760\">so</span> <span m=\"2735120\">related--</span> <span m=\"\
  2735690\">the</span> <span m=\"2735960\">words</span> <span m=\"2736380\">&quot;semidefinite</span>\
  \ <span m=\"2736920\">programming&quot;</span> <span m=\"2737340\">came</span> <span\
  \ m=\"2737520\">up</span> <span m=\"2737770\">earlier in</span> <span m=\"2738030\"\
  >this</span> <span m=\"2738180\">course</span> <span m=\"2738750\">when</span> <span\
  \ m=\"2738870\">we</span> <span m=\"2738990\">discussed</span> <span m=\"2739470\"\
  >growth</span> <span m=\"2739830\">index</span> <span m=\"2740070\">inequality.</span>\
  \ <span m=\"2740970\">So</span> <span m=\"2741270\">they</span> <span m=\"2741480\"\
  >came</span> <span m=\"2741750\">up</span> <span m=\"2741930\">with</span> <span\
  \ m=\"2742140\">an</span> <span m=\"2742230\">approximation</span> <span m=\"2743010\"\
  >algorithm.</span></p><p><span m=\"2743820\">So</span> <span m=\"2744810\">here,\
  \ I'm</span> <span m=\"2745050\">only</span> <span m=\"2745260\">talking</span>\
  \ <span m=\"2745560\">about</span> <span m=\"2746100\">polynomial</span> <span m=\"\
  2746700\">time,</span> <span m=\"2747100\">so</span> <span m=\"2747180\">efficient</span>\
  \ <span m=\"2747630\">algorithms.</span> <span m=\"2748830\">Approximation</span>\
  \ <span m=\"2749550\">algorithm</span> <span m=\"2750570\">with</span> <span m=\"\
  2750900\">approximation</span> <span m=\"2751680\">ratio</span> <span m=\"2753600\"\
  >around</span> <span m=\"2754770\">0.878.</span> <span m=\"2756120\">So</span> <span\
  \ m=\"2756840\">one</span> <span m=\"2757140\">can</span> <span m=\"2757380\">obtain</span>\
  \ <span m=\"2758790\">a</span> <span m=\"2758910\">cut</span> <span m=\"2759930\"\
  >that</span> <span m=\"2760140\">is</span> <span m=\"2760530\">within</span> <span\
  \ m=\"2763300\">basically</span> <span m=\"2763900\">13%</span> <span m=\"2765070\"\
  >of</span> <span m=\"2765460\">the</span> <span m=\"2765850\">maximum.</span> <span\
  \ m=\"2767820\">So</span> <span m=\"2768010\">it's</span> <span m=\"2768150\">an</span>\
  \ <span m=\"2768210\">approximation</span> <span m=\"2768870\">algorithm.</span>\
  \ <span m=\"2770540\">However,</span> <span m=\"2771500\">it</span> <span m=\"2771650\"\
  >is</span> <span m=\"2771830\">known</span> <span m=\"2772520\">that</span> <span\
  \ m=\"2772910\">it</span> <span m=\"2773060\">is</span> <span m=\"2774050\">hard</span>\
  \ <span m=\"2775520\">in</span> <span m=\"2775640\">the</span> <span m=\"2775700\"\
  >sense</span> <span m=\"2776030\">of</span> <span m=\"2776810\">complexity</span>\
  \ <span m=\"2777380\">theory.</span> <span m=\"2778540\">It'd be</span> <span m=\"\
  2778840\">hard</span> <span m=\"2779330\">to</span> <span m=\"2779540\">approximate</span>\
  \ <span m=\"2783130\">beyond</span> <span m=\"2786410\">the</span> <span m=\"2786530\"\
  >ratio</span> <span m=\"2787880\">16</span> <span m=\"2788480\">over</span> <span\
  \ m=\"2788720\">17,</span> <span m=\"2789830\">which</span> <span m=\"2790040\"\
  >is</span> <span m=\"2790190\">around</span> <span m=\"2790580\">0.491.</span></p><p><span\
  \ m=\"2797000\">And</span> <span m=\"2797480\">there</span> <span m=\"2797780\"\
  >is</span> <span m=\"2797990\">an</span> <span m=\"2798110\">important</span> <span\
  \ m=\"2798500\">conjecture</span> <span m=\"2798980\">in</span> <span m=\"2799040\"\
  >computer</span> <span m=\"2799370\">science</span> <span m=\"2799700\">called</span>\
  \ <span m=\"2799900\">a</span> <span m=\"2799970\">unique</span> <span m=\"2800360\"\
  >games</span> <span m=\"2800690\">conjecture</span> <span m=\"2801800\">that,</span>\
  \ <span m=\"2802580\">if</span> <span m=\"2802730\">that</span> <span m=\"2802910\"\
  >conjecture</span> <span m=\"2803420\">were</span> <span m=\"2803540\">true,</span>\
  \ <span m=\"2804240\">then</span> <span m=\"2804380\">it</span> <span m=\"2804530\"\
  >would</span> <span m=\"2804680\">be</span> <span m=\"2804860\">difficult.</span>\
  \ <span m=\"2805490\">It</span> <span m=\"2805550\">would</span> <span m=\"2806710\"\
  >be</span> <span m=\"2806870\">hard</span> <span m=\"2807110\">to</span> <span m=\"\
  2807260\">approximate</span> <span m=\"2807980\">beyond</span> <span m=\"2808490\"\
  >the</span> <span m=\"2808700\">Goemans-Williamson</span> <span m=\"2810260\">ratio.</span>\
  \ <span m=\"2812010\">So</span> <span m=\"2812030\">this</span> <span m=\"2812390\"\
  >indicates</span> <span m=\"2812870\">the</span> <span m=\"2812960\">status</span>\
  \ <span m=\"2813440\">of</span> <span m=\"2813530\">this</span> <span m=\"2813710\"\
  >problem.</span> <span m=\"2814070\">It</span> <span m=\"2814190\">is</span> <span\
  \ m=\"2814490\">difficult</span> <span m=\"2814940\">to</span> <span m=\"2815390\"\
  >do</span> <span m=\"2816440\">an</span> <span m=\"2816720\">epsilon</span> <span\
  \ m=\"2817160\">approximation.</span></p><p><span m=\"2819760\">But</span> <span\
  \ m=\"2820860\">if</span> <span m=\"2821040\">the</span> <span m=\"2821160\">graph</span>\
  \ <span m=\"2821580\">I</span> <span m=\"2821670\">give</span> <span m=\"2821940\"\
  >you</span> <span m=\"2822530\">is</span> <span m=\"2822830\">dense--</span> <span\
  \ m=\"2830460\">&quot;dense&quot;</span> <span m=\"2831240\">meaning</span> <span\
  \ m=\"2832110\">a</span> <span m=\"2832170\">quadratic</span> <span m=\"2832710\"\
  >number</span> <span m=\"2833040\">of</span> <span m=\"2833220\">edges,</span> <span\
  \ m=\"2834840\">where</span> <span m=\"2834990\">n</span> <span m=\"2835200\">is</span>\
  \ <span m=\"2835440\">a</span> <span m=\"2835500\">number</span> <span m=\"2835770\"\
  >of</span> <span m=\"2835830\">vertices--</span> <span m=\"2837970\">then</span>\
  \ <span m=\"2838200\">it</span> <span m=\"2838290\">turns</span> <span m=\"2838620\"\
  >out</span> <span m=\"2838920\">that</span> <span m=\"2840300\">the</span> <span\
  \ m=\"2841530\">regularity-type</span> <span m=\"2844160\">algorithms--</span> <span\
  \ m=\"2845210\">so</span> <span m=\"2845420\">that</span> <span m=\"2845960\">theorem</span>\
  \ <span m=\"2846350\">combined</span> <span m=\"2846770\">with</span> <span m=\"\
  2846920\">the</span> <span m=\"2847010\">algorithmic</span> <span m=\"2847610\"\
  >versions</span> <span m=\"2848390\">allows</span> <span m=\"2848840\">you</span>\
  \ <span m=\"2849020\">to</span> <span m=\"2849200\">get</span> <span m=\"2850820\"\
  >polynomial</span> <span m=\"2851450\">time</span> <span m=\"2851900\">approximation</span>\
  \ <span m=\"2852980\">algorithms.</span> <span m=\"2855360\">So</span> <span m=\"\
  2855520\">this</span> <span m=\"2855720\">is</span> <span m=\"2856050\">polynomial</span>\
  \ <span m=\"2856680\">time</span> <span m=\"2857250\">approximation</span> <span\
  \ m=\"2858180\">schemes.</span></p><p><span m=\"2861620\">So</span> <span m=\"2861800\"\
  >one</span> <span m=\"2862130\">can</span> <span m=\"2862760\">approximate</span>\
  \ <span m=\"2867720\">up</span> <span m=\"2867900\">to</span> <span m=\"2869100\"\
  >1</span> <span m=\"2869340\">minus</span> <span m=\"2869730\">epsilon</span> <span\
  \ m=\"2871280\">ratio.</span> <span m=\"2872000\">So</span> <span m=\"2872880\"\
  >one</span> <span m=\"2873230\">can</span> <span m=\"2873380\">approximate</span>\
  \ <span m=\"2874460\">up</span> <span m=\"2874640\">to</span> <span m=\"2877490\"\
  >epsilon</span> <span m=\"2877940\">n</span> <span m=\"2878090\">squared</span>\
  \ <span m=\"2878750\">additive</span> <span m=\"2879200\">error</span> <span m=\"\
  2883840\">in</span> <span m=\"2885970\">polynomial</span> <span m=\"2886570\">time.</span>\
  \ <span m=\"2887796\">So</span> <span m=\"2888250\">in</span> <span m=\"2888320\"\
  >particular,</span> <span m=\"2888860\">if</span> <span m=\"2889040\">I'm</span>\
  \ <span m=\"2889490\">willing</span> <span m=\"2889790\">to</span> <span m=\"2889880\"\
  >lose</span> <span m=\"2890660\">0.01</span> <span m=\"2891200\">n</span> <span\
  \ m=\"2891920\">squared,</span> <span m=\"2892730\">then</span> <span m=\"2893280\"\
  >there</span> <span m=\"2893430\">is</span> <span m=\"2893570\">an</span> <span\
  \ m=\"2893660\">algorithm</span> <span m=\"2894500\">to</span> <span m=\"2894800\"\
  >approximate</span> <span m=\"2895640\">the</span> <span m=\"2895730\">size</span>\
  \ <span m=\"2896060\">of</span> <span m=\"2896120\">the</span> <span m=\"2896210\"\
  >max</span> <span m=\"2896540\">cut.</span></p><p><span m=\"2897040\">And</span>\
  \ <span m=\"2897170\">that</span> <span m=\"2897350\">algorithm</span> <span m=\"\
  2898310\">basically</span> <span m=\"2898850\">comes</span> <span m=\"2899210\"\
  >from--</span> <span m=\"2901110\">without</span> <span m=\"2901340\">giving</span>\
  \ <span m=\"2901580\">you</span> <span m=\"2901730\">any</span> <span m=\"2901940\"\
  >details</span> <span m=\"2902390\">whatsoever,</span> <span m=\"2903320\">the</span>\
  \ <span m=\"2903470\">algorithm</span> <span m=\"2904040\">essentially</span> <span\
  \ m=\"2904520\">comes</span> <span m=\"2904820\">from</span> <span m=\"2905150\"\
  >first</span> <span m=\"2905540\">finding</span> <span m=\"2906620\">a</span> <span\
  \ m=\"2906965\">regularity</span> <span m=\"2907310\">partition.</span> <span m=\"\
  2915110\">So</span> <span m=\"2915290\">the</span> <span m=\"2915380\">partition</span>\
  \ <span m=\"2917480\">breaks</span> <span m=\"2917840\">the</span> <span m=\"2918590\"\
  >set</span> <span m=\"2918920\">of</span> <span m=\"2919400\">vertices</span> <span\
  \ m=\"2920120\">into</span> <span m=\"2921740\">some</span> <span m=\"2921980\"\
  >number</span> <span m=\"2922250\">of</span> <span m=\"2922340\">pieces.</span>\
  \ <span m=\"2923240\">And</span> <span m=\"2923350\">now</span> <span m=\"2924020\"\
  >I</span> <span m=\"2924170\">search</span> <span m=\"2924650\">over</span> <span\
  \ m=\"2931250\">all</span> <span m=\"2932360\">possible</span> <span m=\"2934860\"\
  >ratios</span> <span m=\"2937640\">to</span> <span m=\"2938000\">divide</span> <span\
  \ m=\"2940400\">each</span> <span m=\"2940640\">piece.</span></p><p><span m=\"2944280\"\
  >So</span> <span m=\"2944410\">there</span> <span m=\"2944560\">is</span> <span\
  \ m=\"2944650\">a</span> <span m=\"2944800\">bounded</span> <span m=\"2945070\"\
  >number</span> <span m=\"2945370\">of</span> <span m=\"2945430\">parts.</span> <span\
  \ m=\"2946210\">Each</span> <span m=\"2946390\">one</span> <span m=\"2946540\">of</span>\
  \ <span m=\"2946600\">those,</span> <span m=\"2946850\">I</span> <span m=\"2946960\"\
  >decide,</span> <span m=\"2947490\">do I</span> <span m=\"2948040\">cut</span> <span\
  \ m=\"2948250\">this</span> <span m=\"2948460\">up</span> <span m=\"2948760\">half-half?</span>\
  \ <span m=\"2949320\">Do</span> <span m=\"2949490\">I</span> <span m=\"2949570\"\
  >cut</span> <span m=\"2949780\">it</span> <span m=\"2949910\">up</span> <span m=\"\
  2950290\">1/3,</span> <span m=\"2951070\">2/3,</span> <span m=\"2951940\">and</span>\
  \ <span m=\"2952060\">so</span> <span m=\"2952270\">on?</span> <span m=\"2953270\"\
  >And</span> <span m=\"2953350\">those</span> <span m=\"2953680\">numbers</span>\
  \ <span m=\"2954110\">alone,</span> <span m=\"2955270\">because</span> <span m=\"\
  2956170\">of</span> <span m=\"2957160\">this</span> <span m=\"2957340\">definition</span>\
  \ <span m=\"2957940\">of</span> <span m=\"2958240\">weakly</span> <span m=\"2958690\"\
  >epsilon</span> <span m=\"2959110\">regular,</span> <span m=\"2961470\">once</span>\
  \ <span m=\"2961860\">you</span> <span m=\"2962040\">know</span> <span m=\"2963420\"\
  >what</span> <span m=\"2963780\">the</span> <span m=\"2964230\">intersection</span>\
  \ <span m=\"2964890\">of</span> <span m=\"2965160\">A,</span> <span m=\"2966180\"\
  >B</span> <span m=\"2966540\">is,</span> <span m=\"2966720\">let's</span> <span\
  \ m=\"2966900\">say, a</span> <span m=\"2967110\">complement</span> <span m=\"2967960\"\
  >is</span> <span m=\"2968240\">with</span> <span m=\"2968410\">individual</span>\
  \ <span m=\"2969000\">sets,</span> <span m=\"2969780\">then</span> <span m=\"2970230\"\
  >I</span> <span m=\"2970350\">basically</span> <span m=\"2970740\">know</span> <span\
  \ m=\"2970950\">the</span> <span m=\"2971040\">number</span> <span m=\"2971490\"\
  >of</span> <span m=\"2971640\">edges.</span></p><p><span m=\"2972510\">So</span>\
  \ <span m=\"2972690\">I</span> <span m=\"2972780\">can</span> <span m=\"2972960\"\
  >approximate</span> <span m=\"2973620\">the</span> <span m=\"2973710\">size</span>\
  \ <span m=\"2974100\">of</span> <span m=\"2974160\">the</span> <span m=\"2974250\"\
  >max</span> <span m=\"2974610\">cut</span> <span m=\"2976800\">using</span> <span\
  \ m=\"2977980\">a</span> <span m=\"2979010\">weakly</span> <span m=\"2979410\">epsilon-regular</span>\
  \ <span m=\"2980220\">partition.</span> <span m=\"2981300\">So</span> <span m=\"\
  2981420\">that</span> <span m=\"2981540\">was</span> <span m=\"2981690\">the</span>\
  \ <span m=\"2981780\">motivation</span> <span m=\"2982620\">for</span> <span m=\"\
  2984090\">these</span> <span m=\"2985080\">weakly</span> <span m=\"2985950\">epsilon</span>\
  \ <span m=\"2987360\">partitions,</span> <span m=\"2988410\">at</span> <span m=\"\
  2988470\">least</span> <span m=\"2988620\">the</span> <span m=\"2988740\">algorithmic</span>\
  \ <span m=\"2989400\">application.</span> <span m=\"2991844\">OK.</span> <span m=\"\
  2992320\">Any</span> <span m=\"2992500\">questions?</span></p><p><span m=\"2996420\"\
  >OK.</span> <span m=\"2996740\">So</span> <span m=\"2996890\">let's</span> <span\
  \ m=\"2997040\">take</span> <span m=\"2997220\">a</span> <span m=\"2997280\">quick</span>\
  \ <span m=\"2997490\">break.</span> <span m=\"2998150\">And</span> <span m=\"2998270\"\
  >then</span> <span m=\"2998450\">afterwards,</span> <span m=\"2998930\">I</span>\
  \ <span m=\"2999020\">want</span> <span m=\"2999260\">to</span> <span m=\"2999830\"\
  >show</span> <span m=\"3000100\">you</span> <span m=\"3000220\">the</span> <span\
  \ m=\"3000340\">proof</span> <span m=\"3000940\">of</span> <span m=\"3001900\">the</span>\
  \ <span m=\"3002050\">weak</span> <span m=\"3002560\">regularity</span> <span m=\"\
  3002860\">lemma.</span></p><p><span m=\"3006050\">All right.</span> <span m=\"3006230\"\
  >So</span> <span m=\"3006350\">let</span> <span m=\"3006470\">me</span> <span m=\"\
  3006560\">start</span> <span m=\"3006850\">the</span> <span m=\"3006920\">proof</span>\
  \ <span m=\"3007460\">of</span> <span m=\"3007940\">the</span> <span m=\"3008330\"\
  >weak</span> <span m=\"3008840\">regularity</span> <span m=\"3009920\">lemma.</span>\
  \ <span m=\"3012560\">And</span> <span m=\"3012680\">the</span> <span m=\"3012770\"\
  >proof</span> <span m=\"3012990\">is</span> <span m=\"3013130\">by</span> <span\
  \ m=\"3013310\">this</span> <span m=\"3013730\">energy</span> <span m=\"3014060\"\
  >increment</span> <span m=\"3014480\">argument.</span> <span m=\"3015000\">So</span>\
  \ <span m=\"3015020\">let's</span> <span m=\"3015200\">see</span> <span m=\"3015380\"\
  >what</span> <span m=\"3015520\">this</span> <span m=\"3015680\">energy</span> <span\
  \ m=\"3015980\">increment</span> <span m=\"3016400\">argument</span> <span m=\"\
  3016760\">looks</span> <span m=\"3017000\">like</span> <span m=\"3017660\">in</span>\
  \ <span m=\"3017780\">the</span> <span m=\"3017870\">language</span> <span m=\"\
  3018260\">of</span> <span m=\"3018380\">graphons.</span></p><p><span m=\"3019700\"\
  >So</span> <span m=\"3019880\">energy</span> <span m=\"3020300\">now</span> <span\
  \ m=\"3020480\">means</span> <span m=\"3021000\">L2,</span> <span m=\"3023050\"\
  >so</span> <span m=\"3023370\">L2</span> <span m=\"3023930\">energy</span> <span\
  \ m=\"3025410\">increment.</span> <span m=\"3027610\">So</span> <span m=\"3027890\"\
  >the</span> <span m=\"3027980\">statement</span> <span m=\"3028850\">of</span> <span\
  \ m=\"3028910\">this</span> <span m=\"3029000\">lemma</span> <span m=\"3029390\"\
  >is</span> <span m=\"3029600\">that</span> <span m=\"3030200\">if</span> <span m=\"\
  3030320\">you</span> <span m=\"3030470\">have</span> <span m=\"3030920\">w,</span>\
  \ <span m=\"3031580\">a</span> <span m=\"3031750\">graphon,</span> <span m=\"3035280\"\
  >and</span> <span m=\"3035970\">p,</span> <span m=\"3036750\">a</span> <span m=\"\
  3036900\">partition,</span> <span m=\"3041480\">of</span> <span m=\"3041660\">0,</span>\
  \ <span m=\"3042230\">comma,</span> <span m=\"3042490\">1</span> <span m=\"3042770\"\
  >interval</span> <span m=\"3046080\">such</span> <span m=\"3046410\">that--</span>\
  \ <span m=\"3050120\">always</span> <span m=\"3050420\">measurable</span> <span\
  \ m=\"3050870\">pieces.</span> <span m=\"3051260\">I'm</span> <span m=\"3051380\"\
  >not</span> <span m=\"3051530\">going</span> <span m=\"3051620\">to</span> <span\
  \ m=\"3051740\">even</span> <span m=\"3051980\">write</span> <span m=\"3052160\"\
  >it.</span> <span m=\"3052300\">It's always</span> <span m=\"3052610\">measurable</span>\
  \ <span m=\"3053030\">pieces--</span> <span m=\"3057320\">such</span> <span m=\"\
  3057620\">that</span> <span m=\"3059840\">the</span> <span m=\"3059930\">difference</span>\
  \ <span m=\"3060470\">between</span> <span m=\"3061280\">w</span> <span m=\"3061730\"\
  >and</span> <span m=\"3062630\">w</span> <span m=\"3066860\">averaged</span> <span\
  \ m=\"3067190\">over</span> <span m=\"3067410\">steps</span> <span m=\"3067730\"\
  >p</span> <span m=\"3068390\">is</span> <span m=\"3069080\">bigger</span> <span\
  \ m=\"3069470\">than</span> <span m=\"3070220\">epsilon.</span></p><p><span m=\"\
  3071420\">So</span> <span m=\"3071600\">this</span> <span m=\"3071810\">is</span>\
  \ <span m=\"3071960\">the</span> <span m=\"3072050\">notion</span> <span m=\"3072440\"\
  >of</span> <span m=\"3073280\">being not</span> <span m=\"3073880\">epsilon</span>\
  \ <span m=\"3074390\">regular</span> <span m=\"3078410\">in</span> <span m=\"3078530\"\
  >the</span> <span m=\"3078620\">weak</span> <span m=\"3078830\">sense,</span> <span\
  \ m=\"3079190\">not</span> <span m=\"3079880\">weakly</span> <span m=\"3080240\"\
  >epsilon</span> <span m=\"3080660\">regular.</span> <span m=\"3082280\">Then</span>\
  \ <span m=\"3083450\">there</span> <span m=\"3083640\">exists</span> <span m=\"\
  3084170\">a</span> <span m=\"3084320\">refinement,</span> <span m=\"3087730\">p</span>\
  \ <span m=\"3088340\">prime</span> <span m=\"3089350\">of</span> <span m=\"3089540\"\
  >p,</span> <span m=\"3093100\">dividing</span> <span m=\"3094180\">each</span> <span\
  \ m=\"3097510\">part</span> <span m=\"3098320\">of</span> <span m=\"3098560\">p</span>\
  \ <span m=\"3099940\">into</span> <span m=\"3100690\">at</span> <span m=\"3100840\"\
  >most</span> <span m=\"3101560\">four</span> <span m=\"3102010\">parts</span> <span\
  \ m=\"3105430\">such</span> <span m=\"3105760\">that</span> <span m=\"3107140\"\
  >the</span> <span m=\"3108390\">true</span> <span m=\"3108610\">norm</span> <span\
  \ m=\"3110410\">increases</span> <span m=\"3112840\">by</span> <span m=\"3116480\"\
  >more</span> <span m=\"3116720\">than</span> <span m=\"3116960\">epsilon</span>\
  \ <span m=\"3117380\">squared</span> <span m=\"3118580\">under</span> <span m=\"\
  3119150\">this</span> <span m=\"3119690\">refinement.</span> <span m=\"3122040\"\
  >So it</span> <span m=\"3122300\">should</span> <span m=\"3122460\">be</span> <span\
  \ m=\"3123240\">similar.</span> <span m=\"3124110\">It</span> <span m=\"3124290\"\
  >should</span> <span m=\"3124410\">be</span> <span m=\"3124530\">familiar</span>\
  \ <span m=\"3124950\">to</span> <span m=\"3125100\">you,</span> <span m=\"3125460\"\
  >because</span> <span m=\"3125790\">we</span> <span m=\"3125910\">have</span> <span\
  \ m=\"3126060\">similar</span> <span m=\"3126450\">arguments</span> <span m=\"3126990\"\
  >from</span> <span m=\"3127350\">Szemer\xE9di's</span> <span m=\"3127980\">regularity</span>\
  \ <span m=\"3128265\">lemma.</span> <span m=\"3129720\">So</span> <span m=\"3129780\"\
  >let's</span> <span m=\"3129960\">see</span> <span m=\"3130080\">the</span> <span\
  \ m=\"3130170\">proof.</span></p><p><span m=\"3133490\">Because</span> <span m=\"\
  3134360\">you</span> <span m=\"3134690\">have</span> <span m=\"3135440\">violation</span>\
  \ <span m=\"3136100\">of</span> <span m=\"3136700\">weak</span> <span m=\"3137030\"\
  >epsilon</span> <span m=\"3137420\">regularity,</span> <span m=\"3138380\">there</span>\
  \ <span m=\"3138590\">exists</span> <span m=\"3139560\">sets</span> <span m=\"3140300\"\
  >S</span> <span m=\"3140570\">and</span> <span m=\"3140750\">T,</span> <span m=\"\
  3141920\">measurable</span> <span m=\"3142370\">subsets</span> <span m=\"3142910\"\
  >of</span> <span m=\"3143030\">0,</span> <span m=\"3143250\">1</span> <span m=\"\
  3143480\">interval,</span> <span m=\"3144410\">such</span> <span m=\"3144710\">that</span>\
  \ <span m=\"3145820\">this</span> <span m=\"3146030\">integral</span> <span m=\"\
  3147920\">evaluated</span> <span m=\"3148880\">over</span> <span m=\"3149300\">S</span>\
  \ <span m=\"3149510\">cross</span> <span m=\"3149840\">T</span> <span m=\"3154350\"\
  >is</span> <span m=\"3154950\">more</span> <span m=\"3155160\">than</span> <span\
  \ m=\"3155340\">epsilon</span> <span m=\"3156030\">in</span> <span m=\"3156270\"\
  >absolute</span> <span m=\"3156840\">value.</span> <span m=\"3159140\">So</span>\
  \ <span m=\"3159260\">now</span> <span m=\"3159590\">let</span> <span m=\"3159800\"\
  >me</span> <span m=\"3161720\">take</span> <span m=\"3162350\">p</span> <span m=\"\
  3162530\">prime</span> <span m=\"3163580\">to</span> <span m=\"3163730\">be</span>\
  \ <span m=\"3164585\">the</span> <span m=\"3165080\">common</span> <span m=\"3165530\"\
  >refinement</span> <span m=\"3172690\">of</span> <span m=\"3174820\">p</span> <span\
  \ m=\"3175690\">by</span> <span m=\"3176920\">introducing</span> <span m=\"3184960\"\
  >S</span> <span m=\"3185470\">and</span> <span m=\"3185650\">T</span> <span m=\"\
  3186550\">into</span> <span m=\"3186940\">this</span> <span m=\"3187120\">partition.</span>\
  \ <span m=\"3187890\">So</span> <span m=\"3188090\">throw</span> <span m=\"3188410\"\
  >S</span> <span m=\"3188665\">and T</span> <span m=\"3188920\">in</span> <span m=\"\
  3189520\">and</span> <span m=\"3190120\">break</span> <span m=\"3190360\">everything</span>\
  \ <span m=\"3190900\">according</span> <span m=\"3191290\">to</span> <span m=\"\
  3191740\">S and</span> <span m=\"3191995\">T.</span></p><p><span m=\"3192930\">And</span>\
  \ <span m=\"3193090\">so</span> <span m=\"3193240\">each</span> <span m=\"3193480\"\
  >part</span> <span m=\"3196960\">becomes</span> <span m=\"3197560\">at</span> <span\
  \ m=\"3197860\">most</span> <span m=\"3198190\">four</span> <span m=\"3199200\"\
  >subparts.</span> <span m=\"3201140\">So</span> <span m=\"3201250\">that's</span>\
  \ <span m=\"3201520\">the</span> <span m=\"3201730\">at</span> <span m=\"3202000\"\
  >most</span> <span m=\"3202390\">four</span> <span m=\"3202690\">subparts.</span>\
  \ <span m=\"3205780\">I</span> <span m=\"3205870\">now</span> <span m=\"3206080\"\
  >need</span> <span m=\"3206230\">to</span> <span m=\"3206290\">show</span> <span\
  \ m=\"3206760\">that</span> <span m=\"3207010\">I have</span> <span m=\"3207280\"\
  >an</span> <span m=\"3207400\">energy</span> <span m=\"3207760\">increment.</span>\
  \ <span m=\"3209060\">And</span> <span m=\"3209260\">to</span> <span m=\"3209380\"\
  >do</span> <span m=\"3209470\">this,</span> <span m=\"3210040\">let</span> <span\
  \ m=\"3210160\">me</span> <span m=\"3211720\">first</span> <span m=\"3212890\">perform</span>\
  \ <span m=\"3213340\">the</span> <span m=\"3213430\">following</span> <span m=\"\
  3215200\">calculation.</span></p><p><span m=\"3216530\">So</span> <span m=\"3216850\"\
  >remember,</span> <span m=\"3217240\">this</span> <span m=\"3217390\">symbol</span>\
  \ <span m=\"3217780\">here</span> <span m=\"3218710\">is</span> <span m=\"3219340\"\
  >the</span> <span m=\"3219970\">inner</span> <span m=\"3220270\">product</span>\
  \ <span m=\"3221590\">obtained</span> <span m=\"3222010\">by</span> <span m=\"3223000\"\
  >multiplying</span> <span m=\"3223540\">and</span> <span m=\"3223690\">integrating</span>\
  \ <span m=\"3224230\">over</span> <span m=\"3224470\">the</span> <span m=\"3224560\"\
  >entire</span> <span m=\"3224920\">box.</span> <span m=\"3226890\">I</span> <span\
  \ m=\"3227020\">claim</span> <span m=\"3227280\">that</span> <span m=\"3229160\"\
  >that</span> <span m=\"3230840\">inner</span> <span m=\"3231020\">product</span>\
  \ <span m=\"3231920\">equals</span> <span m=\"3232400\">to</span> <span m=\"3235570\"\
  >the inner</span> <span m=\"3235710\">product</span> <span m=\"3236250\">between</span>\
  \ <span m=\"3237090\">wp</span> <span m=\"3238110\">and</span> <span m=\"3238230\"\
  >wp</span> <span m=\"3238770\">prime,</span> <span m=\"3240790\">because</span>\
  \ <span m=\"3242020\">what</span> <span m=\"3242200\">happens</span> <span m=\"\
  3242560\">here</span> <span m=\"3242800\">is</span> <span m=\"3243460\">we</span>\
  \ <span m=\"3243670\">are</span> <span m=\"3245650\">looking</span> <span m=\"3245950\"\
  >at</span> <span m=\"3246040\">a</span> <span m=\"3246100\">situation</span> <span\
  \ m=\"3248580\">where</span> <span m=\"3251940\">wp</span> <span m=\"3252320\">prime</span>\
  \ <span m=\"3252950\">is</span> <span m=\"3253100\">constant</span> <span m=\"3254270\"\
  >on</span> <span m=\"3254450\">each</span> <span m=\"3254780\">part.</span></p><p><span\
  \ m=\"3255510\">So</span> <span m=\"3255740\">when</span> <span m=\"3255950\">I</span>\
  \ <span m=\"3256070\">do</span> <span m=\"3256280\">this</span> <span m=\"3256580\"\
  >inner</span> <span m=\"3256760\">product,</span> <span m=\"3257360\">I</span> <span\
  \ m=\"3257450\">can</span> <span m=\"3257600\">replace</span> <span m=\"3258080\"\
  >w</span> <span m=\"3258350\">by</span> <span m=\"3259550\">its</span> <span m=\"\
  3259910\">average.</span> <span m=\"3260920\">And</span> <span m=\"3261050\">likewise,</span>\
  \ <span m=\"3261620\">over</span> <span m=\"3261860\">here,</span> <span m=\"3262190\"\
  >I</span> <span m=\"3262250\">can</span> <span m=\"3262430\">also</span> <span m=\"\
  3262670\">replace</span> <span m=\"3263060\">it</span> <span m=\"3263120\">by</span>\
  \ <span m=\"3263270\">its</span> <span m=\"3263420\">average.</span> <span m=\"\
  3263810\">And</span> <span m=\"3263990\">you</span> <span m=\"3264140\">end</span>\
  \ <span m=\"3264290\">up</span> <span m=\"3265610\">having</span> <span m=\"3265820\"\
  >the</span> <span m=\"3265910\">same</span> <span m=\"3266180\">average.</span>\
  \ <span m=\"3266990\">And</span> <span m=\"3267500\">these</span> <span m=\"3267710\"\
  >two</span> <span m=\"3267890\">averages</span> <span m=\"3268430\">are</span> <span\
  \ m=\"3268550\">both</span> <span m=\"3272500\">just</span> <span m=\"3272710\"\
  >what</span> <span m=\"3272920\">happens</span> <span m=\"3273340\">if</span> <span\
  \ m=\"3273430\">you</span> <span m=\"3274060\">do</span> <span m=\"3274270\">stepping</span>\
  \ <span m=\"3274720\">by</span> <span m=\"3274990\">p.</span></p><p><span m=\"3278440\"\
  >You</span> <span m=\"3278590\">also</span> <span m=\"3278890\">have</span> <span\
  \ m=\"3279310\">that</span> <span m=\"3280480\">w</span> <span m=\"3282480\">has</span>\
  \ <span m=\"3283900\">inner</span> <span m=\"3284030\">product</span> <span m=\"\
  3284660\">with</span> <span m=\"3285590\">1</span> <span m=\"3286070\">sub</span>\
  \ <span m=\"3286910\">S</span> <span m=\"3287090\">cross</span> <span m=\"3287450\"\
  >T</span> <span m=\"3288380\">the</span> <span m=\"3288470\">same</span> <span m=\"\
  3289390\">as</span> <span m=\"3289610\">that</span> <span m=\"3289850\">of</span>\
  \ <span m=\"3290400\">p</span> <span m=\"3290570\">prime</span> <span m=\"3293190\"\
  >by</span> <span m=\"3293310\">the</span> <span m=\"3293400\">same</span> <span\
  \ m=\"3293610\">reason,</span> <span m=\"3294780\">because</span> <span m=\"3295050\"\
  >over</span> <span m=\"3295640\">S</span> <span m=\"3295800\">cross</span> <span\
  \ m=\"3296090\">T.</span> <span m=\"3299826\">So</span> <span m=\"3300270\">S</span>\
  \ <span m=\"3300500\">cross</span> <span m=\"3300790\">T</span> <span m=\"3302260\"\
  >is</span> <span m=\"3303340\">a</span> <span m=\"3303400\">union</span> <span m=\"\
  3303790\">of</span> <span m=\"3303970\">the</span> <span m=\"3304090\">parts</span>\
  \ <span m=\"3304630\">of</span> <span m=\"3304840\">p</span> <span m=\"3305020\"\
  >prime.</span> <span m=\"3306000\">So</span> <span m=\"3306360\">S</span> <span\
  \ m=\"3307686\">is</span> <span m=\"3309540\">union</span> <span m=\"3309990\">of</span>\
  \ <span m=\"3312650\">parts</span> <span m=\"3313220\">of</span> <span m=\"3313430\"\
  >p</span> <span m=\"3313894\">prime.</span></p><p><span m=\"3316680\">OK.</span>\
  \ <span m=\"3316860\">So</span> <span m=\"3317000\">let's</span> <span m=\"3317150\"\
  >see.</span> <span m=\"3318140\">With</span> <span m=\"3319370\">those</span> <span\
  \ m=\"3319610\">observations,</span> <span m=\"3320620\">you</span> <span m=\"3320780\"\
  >find</span> <span m=\"3321290\">that--</span> <span m=\"3330580\">so</span> <span\
  \ m=\"3330760\">this</span> <span m=\"3330940\">is</span> <span m=\"3331060\">true.</span>\
  \ <span m=\"3333580\">This is</span> <span m=\"3333790\">from</span> <span m=\"\
  3334000\">the</span> <span m=\"3334090\">first</span> <span m=\"3334540\">equality.</span></p><p><span\
  \ m=\"3335870\">So</span> <span m=\"3335920\">now</span> <span m=\"3336100\">let</span>\
  \ <span m=\"3336220\">me</span> <span m=\"3336340\">draw</span> <span m=\"3336640\"\
  >you</span> <span m=\"3339610\">a</span> <span m=\"3340180\">right</span> <span\
  \ m=\"3340510\">triangle.</span> <span m=\"3349890\">So</span> <span m=\"3350070\"\
  >you</span> <span m=\"3350190\">have</span> <span m=\"3350370\">a</span> <span m=\"\
  3350400\">right</span> <span m=\"3350640\">angle,</span> <span m=\"3351060\">because</span>\
  \ <span m=\"3351450\">you</span> <span m=\"3351540\">have</span> <span m=\"3351840\"\
  >an</span> <span m=\"3352350\">inner</span> <span m=\"3352560\">product</span> <span\
  \ m=\"3353010\">that</span> <span m=\"3353160\">is</span> <span m=\"3353420\">0.</span>\
  \ <span m=\"3354450\">So</span> <span m=\"3354870\">by</span> <span m=\"3355020\"\
  >Pythagorean</span> <span m=\"3355680\">theorem,</span> <span m=\"3362860\">so</span>\
  \ <span m=\"3363040\">what</span> <span m=\"3363220\">is</span> <span m=\"3363340\"\
  >this</span> <span m=\"3363490\">hypotenuse?</span> <span m=\"3364530\">So</span>\
  \ <span m=\"3364750\">you</span> <span m=\"3364990\">add</span> <span m=\"3365300\"\
  >these</span> <span m=\"3365500\">two</span> <span m=\"3365650\">vectors.</span>\
  \ <span m=\"3366520\">And</span> <span m=\"3368056\">you</span> <span m=\"3368460\"\
  >find</span> <span m=\"3368710\">out</span> <span m=\"3368950\">this</span> <span\
  \ m=\"3369260\">wp</span> <span m=\"3371960\">prime.</span> <span m=\"3374060\"\
  >So</span> <span m=\"3374210\">by</span> <span m=\"3374390\">Pythagorean</span>\
  \ <span m=\"3375050\">theorem,</span> <span m=\"3375750\">you</span> <span m=\"\
  3375850\">find</span> <span m=\"3376010\">that</span> <span m=\"3376100\">the</span>\
  \ <span m=\"3376220\">L2</span> <span m=\"3376520\">norm</span> <span m=\"3377060\"\
  >of</span> <span m=\"3377210\">wp</span> <span m=\"3378470\">prime</span> <span\
  \ m=\"3380120\">equals</span> <span m=\"3380540\">to</span> <span m=\"3385650\"\
  >the</span> <span m=\"3385800\">L2</span> <span m=\"3388080\">norm</span> <span\
  \ m=\"3389100\">of</span> <span m=\"3390260\">the</span> <span m=\"3390690\">sum</span>\
  \ <span m=\"3391020\">of</span> <span m=\"3391080\">the</span> <span m=\"3391460\"\
  >L2</span> <span m=\"3391690\">norm</span> <span m=\"3391950\">squares</span> <span\
  \ m=\"3392700\">of</span> <span m=\"3393060\">the</span> <span m=\"3393240\">two</span>\
  \ <span m=\"3393990\">legs</span> <span m=\"3394470\">of</span> <span m=\"3394620\"\
  >this</span> <span m=\"3395190\">right</span> <span m=\"3395430\">triangle.</span></p><p><span\
  \ m=\"3403420\">On</span> <span m=\"3403510\">the</span> <span m=\"3403600\">other</span>\
  \ <span m=\"3403750\">hand,</span> <span m=\"3405400\">this</span> <span m=\"3405670\"\
  >quantity</span> <span m=\"3406090\">here.</span> <span m=\"3408720\">So</span>\
  \ <span m=\"3408810\">let's</span> <span m=\"3408960\">think</span> <span m=\"3409140\"\
  >about</span> <span m=\"3409320\">that</span> <span m=\"3409470\">quantity</span>\
  \ <span m=\"3409770\">over</span> <span m=\"3409920\">there.</span> <span m=\"3412810\"\
  >It's</span> <span m=\"3413310\">an</span> <span m=\"3413430\">L2</span> <span m=\"\
  3413760\">norm.</span> <span m=\"3414420\">So</span> <span m=\"3416310\">in</span>\
  \ <span m=\"3416430\">particular,</span> <span m=\"3422370\">it</span> <span m=\"\
  3422560\">is</span> <span m=\"3424510\">at</span> <span m=\"3424660\">least</span>\
  \ <span m=\"3434500\">this</span> <span m=\"3434710\">quantity</span> <span m=\"\
  3435130\">here,</span> <span m=\"3436580\">which</span> <span m=\"3437860\">you</span>\
  \ <span m=\"3437980\">can</span> <span m=\"3438130\">derive</span> <span m=\"3438460\"\
  >in</span> <span m=\"3439180\">one</span> <span m=\"3439390\">of</span> <span m=\"\
  3439480\">many</span> <span m=\"3439720\">ways--</span> <span m=\"3440180\">for</span>\
  \ <span m=\"3440260\">example,</span> <span m=\"3440620\">by</span> <span m=\"3440940\"\
  >Cauchy-Schwarz</span> <span m=\"3441600\">inequality</span> <span m=\"3442840\"\
  >or</span> <span m=\"3443410\">go</span> <span m=\"3443620\">from</span> <span m=\"\
  3444010\">L2</span> <span m=\"3444370\">to</span> <span m=\"3444520\">L1</span>\
  \ <span m=\"3445840\">and</span> <span m=\"3445930\">then</span> <span m=\"3446470\"\
  >pass</span> <span m=\"3446800\">down</span> <span m=\"3446980\">to</span> <span\
  \ m=\"3447070\">L1.</span> <span m=\"3448330\">So</span> <span m=\"3448900\">this</span>\
  \ <span m=\"3450220\">is</span> <span m=\"3450340\">true.</span> <span m=\"3451890\"\
  >So</span> <span m=\"3452040\">let's</span> <span m=\"3452190\">say</span> <span\
  \ m=\"3452340\">by</span> <span m=\"3452520\">Cauchy-Schwarz.</span></p><p><span\
  \ m=\"3469570\">But</span> <span m=\"3469790\">this</span> <span m=\"3470000\">quantity</span>\
  \ <span m=\"3470420\">here,</span> <span m=\"3471590\">we</span> <span m=\"3473600\"\
  >said</span> <span m=\"3474140\">was</span> <span m=\"3474380\">bigger</span> <span\
  \ m=\"3474650\">than</span> <span m=\"3475190\">epsilon.</span> <span m=\"3484690\"\
  >So</span> <span m=\"3484840\">as</span> <span m=\"3484930\">a</span> <span m=\"\
  3484990\">result,</span> <span m=\"3489460\">this</span> <span m=\"3489660\">final</span>\
  \ <span m=\"3489970\">quantity,</span> <span m=\"3492180\">this</span> <span m=\"\
  3492890\">L2</span> <span m=\"3493700\">norm</span> <span m=\"3494180\">of</span>\
  \ <span m=\"3494390\">the</span> <span m=\"3494900\">new</span> <span m=\"3495110\"\
  >refinement,</span> <span m=\"3497300\">increases</span> <span m=\"3497990\">from</span>\
  \ <span m=\"3498350\">the</span> <span m=\"3498500\">previous</span> <span m=\"\
  3498920\">one</span> <span m=\"3499160\">by</span> <span m=\"3499370\">more</span>\
  \ <span m=\"3499610\">than</span> <span m=\"3499790\">epsilon</span> <span m=\"\
  3500210\">squared.</span> <span m=\"3504620\">OK.</span></p><p><span m=\"3505880\"\
  >So</span> <span m=\"3506030\">this</span> <span m=\"3506150\">is</span> <span m=\"\
  3506270\">the</span> <span m=\"3506360\">L2</span> <span m=\"3506690\">energy</span>\
  \ <span m=\"3507020\">increment</span> <span m=\"3507410\">argument.</span> <span\
  \ m=\"3507910\">I</span> <span m=\"3507980\">claim</span> <span m=\"3508250\">it's</span>\
  \ <span m=\"3508370\">the</span> <span m=\"3508430\">same</span> <span m=\"3508730\"\
  >argument,</span> <span m=\"3509480\">basically,</span> <span m=\"3509870\">as</span>\
  \ <span m=\"3510020\">the</span> <span m=\"3510080\">one</span> <span m=\"3510260\"\
  >that</span> <span m=\"3510350\">we</span> <span m=\"3510470\">did</span> <span\
  \ m=\"3510650\">for</span> <span m=\"3510890\">Szemer\xE9di's</span> <span m=\"\
  3511370\">regularity</span> <span m=\"3511860\">lemma.</span> <span m=\"3512480\"\
  >And</span> <span m=\"3512600\">I</span> <span m=\"3512630\">encourage</span> <span\
  \ m=\"3513050\">you</span> <span m=\"3513170\">to</span> <span m=\"3513260\">go</span>\
  \ <span m=\"3513410\">back</span> <span m=\"3513620\">and</span> <span m=\"3513710\"\
  >compare</span> <span m=\"3514100\">them</span> <span m=\"3514700\">to</span> <span\
  \ m=\"3515180\">see</span> <span m=\"3515450\">why</span> <span m=\"3515720\">they're</span>\
  \ <span m=\"3515930\">the</span> <span m=\"3516020\">same.</span></p><p><span m=\"\
  3520280\">All right,</span> <span m=\"3520520\">moving</span> <span m=\"3520790\"\
  >on.</span> <span m=\"3521360\">So</span> <span m=\"3521900\">the</span> <span m=\"\
  3522020\">other</span> <span m=\"3522200\">part</span> <span m=\"3522500\">of</span>\
  \ <span m=\"3523910\">regularity</span> <span m=\"3524450\">lemma</span> <span m=\"\
  3525230\">is</span> <span m=\"3525500\">to</span> <span m=\"3526160\">iterate</span>\
  \ <span m=\"3526840\">this</span> <span m=\"3528170\">approach.</span> <span m=\"\
  3528820\">So</span> <span m=\"3529300\">if</span> <span m=\"3529580\">you</span>\
  \ <span m=\"3529700\">have</span> <span m=\"3529880\">something</span> <span m=\"\
  3530180\">which</span> <span m=\"3530330\">is</span> <span m=\"3530420\">not</span>\
  \ <span m=\"3530660\">epsilon</span> <span m=\"3531080\">regular,</span> <span m=\"\
  3531980\">refine</span> <span m=\"3532400\">it.</span> <span m=\"3532790\">And</span>\
  \ <span m=\"3532910\">then</span> <span m=\"3533030\">iterate.</span> <span m=\"\
  3533960\">And</span> <span m=\"3534080\">you</span> <span m=\"3534170\">cannot</span>\
  \ <span m=\"3536000\">perceive</span> <span m=\"3536600\">more</span> <span m=\"\
  3536900\">than</span> <span m=\"3537320\">a bounded</span> <span m=\"3537740\">number</span>\
  \ <span m=\"3538040\">of</span> <span m=\"3538130\">times,</span> <span m=\"3538820\"\
  >because</span> <span m=\"3539330\">energy</span> <span m=\"3539660\">is</span>\
  \ <span m=\"3539810\">always</span> <span m=\"3540080\">bounded</span> <span m=\"\
  3540500\">between</span> <span m=\"3540890\">0</span> <span m=\"3541220\">and</span>\
  \ <span m=\"3541340\">1.</span></p><p><span m=\"3542390\">So</span> <span m=\"3542540\"\
  >for</span> <span m=\"3542690\">every</span> <span m=\"3542900\">epsilon</span>\
  \ <span m=\"3543350\">bigger</span> <span m=\"3543560\">than</span> <span m=\"3543740\"\
  >0</span> <span m=\"3545390\">and</span> <span m=\"3545660\">graphon</span> <span\
  \ m=\"3547090\">w,</span> <span m=\"3549260\">suppose</span> <span m=\"3549860\"\
  >you</span> <span m=\"3550040\">have</span> <span m=\"3551930\">P0,</span> <span\
  \ m=\"3553480\">a</span> <span m=\"3553580\">partition</span> <span m=\"3555830\"\
  >of</span> <span m=\"3556160\">0,</span> <span m=\"3556470\">1</span> <span m=\"\
  3556760\">interval</span> <span m=\"3557210\">into</span> <span m=\"3557780\">measurable</span>\
  \ <span m=\"3558260\">sets.</span> <span m=\"3559960\">Then</span> <span m=\"3563050\"\
  >there</span> <span m=\"3563230\">exists</span> <span m=\"3564190\">a</span> <span\
  \ m=\"3564280\">partition</span> <span m=\"3564790\">p</span> <span m=\"3567280\"\
  >that</span> <span m=\"3567580\">cuts</span> <span m=\"3567940\">up</span> <span\
  \ m=\"3570490\">each</span> <span m=\"3572802\">part</span> <span m=\"3575730\"\
  >of</span> <span m=\"3576390\">P0</span> <span m=\"3578280\">into</span> <span m=\"\
  3579240\">at</span> <span m=\"3579630\">most</span> <span m=\"3580970\">4</span>\
  \ <span m=\"3581570\">to</span> <span m=\"3581830\">the</span> <span m=\"3583170\"\
  >1</span> <span m=\"3583380\">over</span> <span m=\"3583560\">epsilon</span> <span\
  \ m=\"3584070\">parts</span> <span m=\"3587460\">such</span> <span m=\"3587800\"\
  >that</span> <span m=\"3590340\">w</span> <span m=\"3590700\">minus</span> <span\
  \ m=\"3591750\">w</span> <span m=\"3592680\">sub</span> <span m=\"3593100\">p</span>\
  \ <span m=\"3593910\">is</span> <span m=\"3594540\">at</span> <span m=\"3594720\"\
  >most</span> <span m=\"3595200\">epsilon.</span> <span m=\"3595920\">So</span> <span\
  \ m=\"3596160\">I'm</span> <span m=\"3596430\">basically</span> <span m=\"3596820\"\
  >restating</span> <span m=\"3597570\">the</span> <span m=\"3598600\">weak</span>\
  \ <span m=\"3598920\">regularity</span> <span m=\"3599440\">lemma</span> <span m=\"\
  3599620\">over</span> <span m=\"3599880\">there</span> <span m=\"3600780\">but</span>\
  \ <span m=\"3601230\">with</span> <span m=\"3601710\">a</span> <span m=\"3601770\"\
  >small</span> <span m=\"3602790\">difference,</span> <span m=\"3603270\">which</span>\
  \ <span m=\"3603630\">will</span> <span m=\"3603810\">become</span> <span m=\"3604350\"\
  >useful</span> <span m=\"3604950\">later</span> <span m=\"3605220\">on</span> <span\
  \ m=\"3605400\">when</span> <span m=\"3605520\">we</span> <span m=\"3605640\">prove</span>\
  \ <span m=\"3605880\">compactness.</span></p><p><span m=\"3607020\">Namely,</span>\
  \ <span m=\"3607360\">I'm</span> <span m=\"3607480\">allowed</span> <span m=\"3607720\"\
  >to</span> <span m=\"3607810\">start</span> <span m=\"3608100\">with</span> <span\
  \ m=\"3608280\">any</span> <span m=\"3608520\">partition.</span> <span m=\"3609930\"\
  >Instead</span> <span m=\"3610260\">of</span> <span m=\"3610320\">starting</span>\
  \ <span m=\"3610650\">with</span> <span m=\"3610740\">a</span> <span m=\"3610800\"\
  >trivial</span> <span m=\"3611100\">partition,</span> <span m=\"3611520\">I</span>\
  \ <span m=\"3611580\">can</span> <span m=\"3611730\">start</span> <span m=\"3611970\"\
  >with</span> <span m=\"3612180\">any</span> <span m=\"3612390\">partition.</span>\
  \ <span m=\"3614100\">This</span> <span m=\"3614280\">was</span> <span m=\"3614400\"\
  >also</span> <span m=\"3614640\">true</span> <span m=\"3615630\">when</span> <span\
  \ m=\"3615780\">we</span> <span m=\"3615870\">were</span> <span m=\"3615990\">talking</span>\
  \ <span m=\"3616290\">about</span> <span m=\"3616470\">Szemer\xE9di's</span> <span\
  \ m=\"3616950\">regularity</span> <span m=\"3617460\">lemma,</span> <span m=\"3617880\"\
  >although</span> <span m=\"3618090\">I</span> <span m=\"3618150\">didn't</span>\
  \ <span m=\"3618390\">stress</span> <span m=\"3618690\">that</span> <span m=\"3618840\"\
  >point.</span> <span m=\"3620320\">That's</span> <span m=\"3620910\">certainly</span>\
  \ <span m=\"3621240\">the</span> <span m=\"3621330\">case</span> <span m=\"3621600\"\
  >here.</span></p><p><span m=\"3621990\">I</span> <span m=\"3622080\">mean,</span>\
  \ <span m=\"3622170\">the</span> <span m=\"3622230\">proof</span> <span m=\"3622500\"\
  >is</span> <span m=\"3622650\">exactly</span> <span m=\"3623010\">the</span> <span\
  \ m=\"3623100\">same</span> <span m=\"3623400\">with</span> <span m=\"3623670\"\
  >or</span> <span m=\"3623730\">without</span> <span m=\"3624690\">this</span> <span\
  \ m=\"3624870\">extra.</span> <span m=\"3626250\">This</span> <span m=\"3626940\"\
  >extra</span> <span m=\"3627280\">P0</span> <span m=\"3627750\">really</span> <span\
  \ m=\"3627990\">plays</span> <span m=\"3628830\">an</span> <span m=\"3629130\">insignificant</span>\
  \ <span m=\"3629880\">role.</span> <span m=\"3630780\">What</span> <span m=\"3631050\"\
  >happens,</span> <span m=\"3631890\">as</span> <span m=\"3632130\">in</span> <span\
  \ m=\"3632260\">the</span> <span m=\"3632340\">proof</span> <span m=\"3632670\"\
  >of</span> <span m=\"3632850\">Szemer\xE9di's</span> <span m=\"3633390\">regularity</span>\
  \ <span m=\"3633930\">lemma,</span> <span m=\"3634520\">is</span> <span m=\"3634650\"\
  >that</span> <span m=\"3634740\">we</span> <span m=\"3634920\">repeatedly</span>\
  \ <span m=\"3636060\">apply</span> <span m=\"3637710\">the</span> <span m=\"3637920\"\
  >previous</span> <span m=\"3638430\">lemma</span> <span m=\"3640380\">to</span>\
  \ <span m=\"3640650\">obtain</span> <span m=\"3642770\">the</span> <span m=\"3642890\"\
  >sequence</span> <span m=\"3643490\">of</span> <span m=\"3644000\">partitions</span>\
  \ <span m=\"3652290\">of</span> <span m=\"3652440\">the</span> <span m=\"3652560\"\
  >0,</span> <span m=\"3652720\">1</span> <span m=\"3653010\">interval</span> <span\
  \ m=\"3654630\">where,</span> <span m=\"3656040\">each</span> <span m=\"3656250\"\
  >step,</span> <span m=\"3661400\">either</span> <span m=\"3665540\">we</span> <span\
  \ m=\"3665660\">find</span> <span m=\"3666080\">that</span> <span m=\"3667700\"\
  >we</span> <span m=\"3667850\">obtain</span> <span m=\"3668360\">some</span> <span\
  \ m=\"3668750\">partition</span> <span m=\"3669500\">p</span> <span m=\"3669890\"\
  >sub</span> <span m=\"3670160\">i</span> <span m=\"3672610\">such</span> <span m=\"\
  3672940\">that</span> <span m=\"3673510\">it's</span> <span m=\"3673690\">a</span>\
  \ <span m=\"3673750\">good</span> <span m=\"3673930\">approximation</span> <span\
  \ m=\"3674770\">of</span> <span m=\"3674890\">w,</span> <span m=\"3675790\">in</span>\
  \ <span m=\"3675910\">which</span> <span m=\"3676090\">case</span> <span m=\"3676360\"\
  >we</span> <span m=\"3676510\">stop,</span> <span m=\"3681560\">or</span> <span\
  \ m=\"3682850\">the</span> <span m=\"3683050\">L2</span> <span m=\"3685240\">energy</span>\
  \ <span m=\"3690210\">increases</span> <span m=\"3690930\">by</span> <span m=\"\
  3691380\">more</span> <span m=\"3691800\">than</span> <span m=\"3693150\">epsilon</span>\
  \ <span m=\"3694390\">squared.</span></p><p><span m=\"3700630\">And</span> <span\
  \ m=\"3702590\">since</span> <span m=\"3704090\">the</span> <span m=\"3704180\"\
  >final</span> <span m=\"3704600\">energy</span> <span m=\"3708510\">is</span> <span\
  \ m=\"3708750\">always</span> <span m=\"3709110\">at</span> <span m=\"3709240\"\
  >most</span> <span m=\"3709560\">1--</span> <span m=\"3709890\">so</span> <span\
  \ m=\"3710040\">it's</span> <span m=\"3710130\">always</span> <span m=\"3710400\"\
  >bounded</span> <span m=\"3711270\">between</span> <span m=\"3711600\">0</span>\
  \ <span m=\"3711870\">and</span> <span m=\"3711960\">1--</span> <span m=\"3712620\"\
  >we</span> <span m=\"3712770\">must</span> <span m=\"3713100\">stop</span> <span\
  \ m=\"3715230\">after</span> <span m=\"3717030\">at</span> <span m=\"3717420\">most</span>\
  \ <span m=\"3718550\">1</span> <span m=\"3718830\">over</span> <span m=\"3719250\"\
  >epsilon</span> <span m=\"3720570\">steps.</span> <span m=\"3726460\">And</span>\
  \ <span m=\"3727180\">if</span> <span m=\"3727300\">you</span> <span m=\"3727990\"\
  >calculate</span> <span m=\"3728530\">the</span> <span m=\"3728620\">number</span>\
  \ <span m=\"3728980\">of</span> <span m=\"3729070\">parts,</span> <span m=\"3734160\"\
  >each</span> <span m=\"3734270\">part</span> <span m=\"3734660\">is</span> <span\
  \ m=\"3735530\">subdivided</span> <span m=\"3737990\">into</span> <span m=\"3738880\"\
  >at</span> <span m=\"3739280\">most</span> <span m=\"3739610\">four</span> <span\
  \ m=\"3739880\">parts</span> <span m=\"3740165\">at</span> <span m=\"3740450\">each</span>\
  \ <span m=\"3740690\">step,</span> <span m=\"3745640\">which</span> <span m=\"3745820\"\
  >gives</span> <span m=\"3746060\">you</span> <span m=\"3746150\">the</span> <span\
  \ m=\"3746240\">conclusion</span> <span m=\"3746780\">on</span> <span m=\"3746870\"\
  >the</span> <span m=\"3747020\">final</span> <span m=\"3747350\">number</span> <span\
  \ m=\"3747650\">of</span> <span m=\"3747740\">parts.</span> <span m=\"3749580\"\
  >OK,</span> <span m=\"3749770\">so</span> <span m=\"3749790\">very</span> <span\
  \ m=\"3750000\">similar</span> <span m=\"3750420\">to</span> <span m=\"3750600\"\
  >what</span> <span m=\"3750720\">we</span> <span m=\"3750840\">did</span> <span\
  \ m=\"3751230\">before.</span></p><p><span m=\"3755780\">All</span> <span m=\"3755850\"\
  >right.</span> <span m=\"3756720\">So</span> <span m=\"3756870\">that</span> <span\
  \ m=\"3757050\">concludes</span> <span m=\"3757530\">the</span> <span m=\"3757650\"\
  >discussion</span> <span m=\"3758280\">of</span> <span m=\"3759390\">the</span>\
  \ <span m=\"3759480\">weak</span> <span m=\"3759780\">regularity</span> <span m=\"\
  3760380\">lemma.</span> <span m=\"3761850\">So</span> <span m=\"3762270\">basically</span>\
  \ <span m=\"3762660\">the</span> <span m=\"3762750\">same</span> <span m=\"3762960\"\
  >proof.</span> <span m=\"3764360\">Weaker</span> <span m=\"3764650\">conclusion</span>\
  \ <span m=\"3765330\">and</span> <span m=\"3765450\">better</span> <span m=\"3765720\"\
  >quantitative</span> <span m=\"3766260\">balance.</span></p><p><span m=\"3768420\"\
  >The</span> <span m=\"3768510\">next</span> <span m=\"3768750\">thing</span> <span\
  \ m=\"3768840\">and</span> <span m=\"3768930\">the</span> <span m=\"3768990\">final</span>\
  \ <span m=\"3769230\">thing</span> <span m=\"3769380\">I</span> <span m=\"3769470\"\
  >want</span> <span m=\"3769610\">to</span> <span m=\"3769680\">discuss</span> <span\
  \ m=\"3770040\">today</span> <span m=\"3770820\">is</span> <span m=\"3771360\">a</span>\
  \ <span m=\"3771480\">new</span> <span m=\"3771720\">ingredient</span> <span m=\"\
  3772350\">which</span> <span m=\"3772560\">we</span> <span m=\"3772980\">haven't</span>\
  \ <span m=\"3773280\">seen</span> <span m=\"3773520\">before</span> <span m=\"3775140\"\
  >but</span> <span m=\"3775290\">that</span> <span m=\"3775530\">will</span> <span\
  \ m=\"3775800\">play</span> <span m=\"3776160\">an</span> <span m=\"3776220\">important</span>\
  \ <span m=\"3776670\">role</span> <span m=\"3777300\">in</span> <span m=\"3777540\"\
  >the</span> <span m=\"3777690\">proof</span> <span m=\"3778110\">of</span> <span\
  \ m=\"3778320\">the</span> <span m=\"3778440\">compactness--</span> <span m=\"3779580\"\
  >in</span> <span m=\"3779670\">particular,</span> <span m=\"3780330\">the</span>\
  \ <span m=\"3780450\">proof</span> <span m=\"3780750\">of</span> <span m=\"3780840\"\
  >the</span> <span m=\"3780930\">existence</span> <span m=\"3781590\">of</span> <span\
  \ m=\"3781710\">the</span> <span m=\"3781800\">limit.</span> <span m=\"3783160\"\
  >And</span> <span m=\"3783180\">this</span> <span m=\"3783360\">is</span> <span\
  \ m=\"3783420\">something</span> <span m=\"3784530\">where</span> <span m=\"3784830\"\
  >I</span> <span m=\"3784980\">need</span> <span m=\"3785160\">to</span> <span m=\"\
  3786780\">discuss</span> <span m=\"3787470\">martingales.</span></p><p><span m=\"\
  3792410\">So</span> <span m=\"3793240\">martingale</span> <span m=\"3793540\">gill</span>\
  \ <span m=\"3793780\">is</span> <span m=\"3793870\">an</span> <span m=\"3793960\"\
  >important</span> <span m=\"3794620\">object</span> <span m=\"3795010\">in</span>\
  \ <span m=\"3795250\">probability</span> <span m=\"3795850\">theory.</span> <span\
  \ m=\"3796555\">And</span> <span m=\"3796930\">it's</span> <span m=\"3797470\">a</span>\
  \ <span m=\"3798130\">random</span> <span m=\"3798550\">sequence.</span> <span m=\"\
  3803620\">So</span> <span m=\"3803670\">we'll</span> <span m=\"3806100\">look</span>\
  \ <span m=\"3806280\">at</span> <span m=\"3806480\">discrete</span> <span m=\"3806910\"\
  >sequences,</span> <span m=\"3807570\">so</span> <span m=\"3807900\">indexed</span>\
  \ <span m=\"3808350\">by</span> <span m=\"3808890\">non-negative</span> <span m=\"\
  3809520\">integers.</span> <span m=\"3812010\">And</span> <span m=\"3812340\">is</span>\
  \ <span m=\"3812620\">martingale</span> <span m=\"3812940\">is</span> <span m=\"\
  3813190\">such</span> <span m=\"3813450\">a</span> <span m=\"3813510\">sequence</span>\
  \ <span m=\"3814470\">where</span> <span m=\"3816620\">if</span> <span m=\"3817040\"\
  >I'm</span> <span m=\"3817280\">interested</span> <span m=\"3818000\">in</span>\
  \ <span m=\"3819680\">the</span> <span m=\"3819800\">expectation</span> <span m=\"\
  3820850\">of</span> <span m=\"3821010\">the</span> <span m=\"3821120\">next</span>\
  \ <span m=\"3821510\">term</span> <span m=\"3823330\">and</span> <span m=\"3823810\"\
  >even</span> <span m=\"3824110\">if</span> <span m=\"3824290\">you</span> <span\
  \ m=\"3824470\">know</span> <span m=\"3825130\">all</span> <span m=\"3825310\">the</span>\
  \ <span m=\"3825400\">previous</span> <span m=\"3827060\">terms--</span> <span m=\"\
  3827720\">so</span> <span m=\"3827770\">you</span> <span m=\"3827890\">have</span>\
  \ <span m=\"3828040\">full</span> <span m=\"3828340\">knowledge</span> <span m=\"\
  3829060\">of</span> <span m=\"3829210\">the</span> <span m=\"3829300\">sequence</span>\
  \ <span m=\"3830110\">before</span> <span m=\"3830560\">time</span> <span m=\"3830910\"\
  >n,</span> <span m=\"3831530\">and</span> <span m=\"3831730\">you</span> <span m=\"\
  3831820\">want</span> <span m=\"3832000\">to</span> <span m=\"3832090\">predict</span>\
  \ <span m=\"3833550\">on</span> <span m=\"3833710\">the</span> <span m=\"3833760\"\
  >expectation</span> <span m=\"3834670\">what</span> <span m=\"3835000\">the</span>\
  \ <span m=\"3835120\">nth</span> <span m=\"3835410\">term</span> <span m=\"3835710\"\
  >is--</span> <span m=\"3836440\">then</span> <span m=\"3841170\">you</span> <span\
  \ m=\"3841290\">cannot</span> <span m=\"3841740\">do</span> <span m=\"3841950\"\
  >better</span> <span m=\"3842490\">than</span> <span m=\"3842700\">simply</span>\
  \ <span m=\"3843030\">predicting</span> <span m=\"3843990\">the</span> <span m=\"\
  3844110\">last</span> <span m=\"3844590\">term that</span> <span m=\"3845070\">you</span>\
  \ <span m=\"3845190\">saw.</span></p><p><span m=\"3846800\">So</span> <span m=\"\
  3846980\">this</span> <span m=\"3847220\">is</span> <span m=\"3848900\">the</span>\
  \ <span m=\"3848960\">definition</span> <span m=\"3849620\">of</span> <span m=\"\
  3849800\">a</span> <span m=\"3850190\">martingale.</span> <span m=\"3851000\">Now,</span>\
  \ <span m=\"3851310\">to</span> <span m=\"3851720\">do</span> <span m=\"3851870\"\
  >this</span> <span m=\"3852080\">formally,</span> <span m=\"3852560\">I</span> <span\
  \ m=\"3852680\">need</span> <span m=\"3852830\">to</span> <span m=\"3853460\">talk</span>\
  \ <span m=\"3853730\">about</span> <span m=\"3854810\">filtrations</span> <span\
  \ m=\"3855770\">and</span> <span m=\"3855890\">what</span> <span m=\"3856060\">not</span>\
  \ <span m=\"3857020\">in</span> <span m=\"3857480\">measured</span> <span m=\"3857780\"\
  >theory.</span> <span m=\"3858080\">But</span> <span m=\"3858410\">let</span> <span\
  \ m=\"3859040\">me</span> <span m=\"3859130\">not</span> <span m=\"3859310\">do</span>\
  \ <span m=\"3859460\">that.</span></p><p><span m=\"3860870\">OK,</span> <span m=\"\
  3861080\">so</span> <span m=\"3861260\">this</span> <span m=\"3861410\">is</span>\
  \ <span m=\"3861620\">how</span> <span m=\"3861880\">you should</span> <span m=\"\
  3861950\">think</span> <span m=\"3862160\">about</span> <span m=\"3862280\">martingales</span>\
  \ <span m=\"3863150\">and</span> <span m=\"3863690\">a</span> <span m=\"3863750\"\
  >couple</span> <span m=\"3864080\">of</span> <span m=\"3864170\">important</span>\
  \ <span m=\"3864620\">examples</span> <span m=\"3865960\">of</span> <span m=\"3866300\"\
  >martingales.</span> <span m=\"3867080\">So</span> <span m=\"3867200\">the</span>\
  \ <span m=\"3867290\">first</span> <span m=\"3867590\">one</span> <span m=\"3868790\"\
  >comes</span> <span m=\"3869150\">from--</span> <span m=\"3869480\">the</span> <span\
  \ m=\"3871290\">reason</span> <span m=\"3871670\">why</span> <span m=\"3871850\"\
  >these</span> <span m=\"3872030\">things</span> <span m=\"3872210\">are</span> <span\
  \ m=\"3872270\">called</span> <span m=\"3872480\">martingales</span> <span m=\"\
  3874190\">is</span> <span m=\"3874610\">that</span> <span m=\"3874820\">there</span>\
  \ <span m=\"3875000\">is</span> <span m=\"3875120\">a</span> <span m=\"3875180\"\
  >gambling</span> <span m=\"3875750\">strategy</span> <span m=\"3876560\">which</span>\
  \ <span m=\"3876740\">is</span> <span m=\"3876860\">related</span> <span m=\"3877280\"\
  >to</span> <span m=\"3880040\">such</span> <span m=\"3880280\">a</span> <span m=\"\
  3880340\">sequence</span> <span m=\"3881270\">where</span> <span m=\"3882860\">let's</span>\
  \ <span m=\"3883010\">say</span> <span m=\"3883400\">you</span> <span m=\"3883490\"\
  >consider</span> <span m=\"3884720\">a</span> <span m=\"3884780\">sequence</span>\
  \ <span m=\"3885260\">of</span> <span m=\"3885380\">fair</span> <span m=\"3885740\"\
  >coin</span> <span m=\"3886070\">tosses.</span> <span m=\"3888130\">So</span> <span\
  \ m=\"3889440\">here's</span> <span m=\"3889740\">what</span> <span m=\"3889860\"\
  >we're</span> <span m=\"3889980\">going</span> <span m=\"3890090\">to</span> <span\
  \ m=\"3890190\">do.</span></p><p><span m=\"3890500\">So</span> <span m=\"3891060\"\
  >suppose</span> <span m=\"3891450\">we</span> <span m=\"3892500\">consider</span>\
  \ <span m=\"3893010\">a</span> <span m=\"3893190\">betting</span> <span m=\"3893580\"\
  >strategy.</span> <span m=\"3903240\">And</span> <span m=\"3904520\">x</span> <span\
  \ m=\"3904850\">sub</span> <span m=\"3905160\">n</span> <span m=\"3905820\">is</span>\
  \ <span m=\"3906270\">equal</span> <span m=\"3907230\">to</span> <span m=\"3907770\"\
  >your</span> <span m=\"3909840\">balance</span> <span m=\"3914970\">time</span>\
  \ <span m=\"3915740\">n.</span> <span m=\"3917080\">And</span> <span m=\"3917280\"\
  >suppose</span> <span m=\"3917760\">that</span> <span m=\"3917910\">we're</span>\
  \ <span m=\"3918120\">looking</span> <span m=\"3918450\">at</span> <span m=\"3918630\"\
  >a</span> <span m=\"3918900\">fair</span> <span m=\"3919380\">casino</span> <span\
  \ m=\"3921120\">where</span> <span m=\"3921720\">the</span> <span m=\"3922020\"\
  >expectation</span> <span m=\"3922890\">of</span> <span m=\"3923820\">every</span>\
  \ <span m=\"3924870\">game</span> <span m=\"3925200\">is</span> <span m=\"3925350\"\
  >exactly</span> <span m=\"3925800\">0.</span></p><p><span m=\"3927700\">Then</span>\
  \ <span m=\"3929730\">this</span> <span m=\"3930030\">is</span> <span m=\"3930140\"\
  >a</span> <span m=\"3930180\">martingale.</span> <span m=\"3931260\">So</span> <span\
  \ m=\"3931410\">imagine</span> <span m=\"3931830\">you</span> <span m=\"3931950\"\
  >have</span> <span m=\"3932130\">a</span> <span m=\"3932160\">sequence</span> <span\
  \ m=\"3932610\">of</span> <span m=\"3932700\">coin</span> <span m=\"3933000\">flips,</span>\
  \ <span m=\"3933780\">and</span> <span m=\"3934020\">you</span> <span m=\"3934170\"\
  >win</span> <span m=\"3934380\">$1</span> <span m=\"3934830\">for</span> <span m=\"\
  3935010\">each</span> <span m=\"3935190\">head</span> <span m=\"3935460\">and</span>\
  \ <span m=\"3935580\">lose</span> <span m=\"3935820\">$1</span> <span m=\"3936240\"\
  >for</span> <span m=\"3936420\">each</span> <span m=\"3936640\">tail.</span> <span\
  \ m=\"3938600\">When</span> <span m=\"3938750\">you're at</span> <span m=\"3939050\"\
  >time</span> <span m=\"3939380\">five,</span> <span m=\"3939830\">you</span> <span\
  \ m=\"3939980\">should</span> <span m=\"3940100\">have</span> <span m=\"3940480\"\
  >$2</span> <span m=\"3941060\">in</span> <span m=\"3941150\">your</span> <span m=\"\
  3941240\">pocket.</span> <span m=\"3942050\">Then</span> <span m=\"3942530\">time</span>\
  \ <span m=\"3944200\">five</span> <span m=\"3944470\">plus</span> <span m=\"3944740\"\
  >1,</span> <span m=\"3945790\">you</span> <span m=\"3945970\">expect</span> <span\
  \ m=\"3946420\">to</span> <span m=\"3946510\">also</span> <span m=\"3946810\">have</span>\
  \ <span m=\"3947320\">that</span> <span m=\"3947530\">many</span> <span m=\"3947740\"\
  >dollars.</span> <span m=\"3948590\">It</span> <span m=\"3948630\">might</span>\
  \ <span m=\"3948810\">go</span> <span m=\"3948960\">up.</span> <span m=\"3949130\"\
  >It</span> <span m=\"3949200\">might</span> <span m=\"3949350\">go</span> <span\
  \ m=\"3949480\">down.</span> <span m=\"3949790\">But</span> <span m=\"3949810\"\
  >in</span> <span m=\"3949990\">expectation,</span> <span m=\"3950620\">it</span>\
  \ <span m=\"3950710\">doesn't</span> <span m=\"3950950\">change.</span> <span m=\"\
  3952726\">Is there a</span> <span m=\"3953198\">question?</span></p><p><span m=\"\
  3956510\">OK.</span> <span m=\"3956720\">So</span> <span m=\"3957300\">they're</span>\
  \ <span m=\"3958030\">asking</span> <span m=\"3958400\">about,</span> <span m=\"\
  3958620\">is</span> <span m=\"3958770\">there</span> <span m=\"3958890\">some</span>\
  \ <span m=\"3959100\">independence</span> <span m=\"3959790\">condition</span> <span\
  \ m=\"3960210\">required?</span> <span m=\"3960570\">And</span> <span m=\"3960690\"\
  >the</span> <span m=\"3960780\">answer</span> <span m=\"3960950\">is</span> <span\
  \ m=\"3961080\">no.</span> <span m=\"3962190\">So</span> <span m=\"3962310\">there's</span>\
  \ <span m=\"3962520\">no</span> <span m=\"3962730\">independence</span> <span m=\"\
  3963300\">condition</span> <span m=\"3963810\">that</span> <span m=\"3963990\">is</span>\
  \ <span m=\"3964110\">required.</span> <span m=\"3964540\">So</span> <span m=\"\
  3964560\">the</span> <span m=\"3964680\">definition</span> <span m=\"3965250\">of</span>\
  \ <span m=\"3965340\">a</span> <span m=\"3965370\">martingale</span> <span m=\"\
  3966270\">is</span> <span m=\"3966450\">just</span> <span m=\"3967340\">if,</span>\
  \ <span m=\"3967650\">even</span> <span m=\"3967950\">with</span> <span m=\"3968220\"\
  >complete</span> <span m=\"3968670\">knowledge</span> <span m=\"3969180\">of</span>\
  \ <span m=\"3969270\">the</span> <span m=\"3969360\">sequence</span> <span m=\"\
  3969900\">up</span> <span m=\"3970020\">to</span> <span m=\"3970140\">a</span> <span\
  \ m=\"3970200\">certain</span> <span m=\"3970470\">point,</span> <span m=\"3971850\"\
  >the</span> <span m=\"3972330\">difference</span> <span m=\"3972960\">going</span>\
  \ <span m=\"3973290\">forward</span> <span m=\"3974130\">is</span> <span m=\"3974670\"\
  >0</span> <span m=\"3975270\">in</span> <span m=\"3975420\">expectation.</span></p><p><span\
  \ m=\"3982570\">OK,</span> <span m=\"3982750\">so</span> <span m=\"3982930\">here's</span>\
  \ <span m=\"3983230\">another</span> <span m=\"3986730\">example</span> <span m=\"\
  3987260\">of a</span> <span m=\"3987380\">martingale,</span> <span m=\"3987970\"\
  >which</span> <span m=\"3988110\">actually</span> <span m=\"3988410\">turns</span>\
  \ <span m=\"3988740\">out</span> <span m=\"3988920\">to</span> <span m=\"3989010\"\
  >be</span> <span m=\"3989160\">more</span> <span m=\"3989460\">relevant</span> <span\
  \ m=\"3990120\">to</span> <span m=\"3990830\">our</span> <span m=\"3991050\">use--</span>\
  \ <span m=\"3994250\">namely,</span> <span m=\"3994640\">that</span> <span m=\"\
  3996020\">if</span> <span m=\"3996200\">I</span> <span m=\"3996560\">have</span>\
  \ <span m=\"3997040\">some</span> <span m=\"3999410\">hidden--</span> <span m=\"\
  3999980\">think</span> <span m=\"4000250\">of</span> <span m=\"4000430\">x</span>\
  \ <span m=\"4000910\">as</span> <span m=\"4001165\">some</span> <span m=\"4001760\"\
  >hidden</span> <span m=\"4002230\">random</span> <span m=\"4002590\">variable,</span>\
  \ <span m=\"4003760\">so</span> <span m=\"4004050\">something</span> <span m=\"\
  4004540\">that</span> <span m=\"4005040\">you</span> <span m=\"4005440\">have</span>\
  \ <span m=\"4005590\">no</span> <span m=\"4005830\">idea.</span> <span m=\"4006880\"\
  >But</span> <span m=\"4007120\">you</span> <span m=\"4007300\">can</span> <span\
  \ m=\"4007570\">observe</span> <span m=\"4008140\">it</span> <span m=\"4010705\"\
  >at</span> <span m=\"4013040\">time</span> <span m=\"4014412\">n</span> <span m=\"\
  4015750\">based</span> <span m=\"4016170\">on</span> <span m=\"4018560\">information</span>\
  \ <span m=\"4022170\">up</span> <span m=\"4022380\">to</span> <span m=\"4026330\"\
  >time</span> <span m=\"4027020\">n.</span></p><p><span m=\"4031380\">So</span> <span\
  \ m=\"4031530\">for</span> <span m=\"4031710\">example,</span> <span m=\"4033000\"\
  >suppose</span> <span m=\"4033480\">you</span> <span m=\"4033660\">have</span> <span\
  \ m=\"4034440\">no</span> <span m=\"4034770\">idea</span> <span m=\"4035850\">who</span>\
  \ <span m=\"4036600\">is</span> <span m=\"4037380\">going</span> <span m=\"4037770\"\
  >to</span> <span m=\"4039960\">win</span> <span m=\"4040230\">the</span> <span m=\"\
  4040320\">presidential</span> <span m=\"4040890\">election.</span> <span m=\"4041910\"\
  >And</span> <span m=\"4042570\">really,</span> <span m=\"4042780\">nobody</span>\
  \ <span m=\"4043080\">has</span> <span m=\"4043200\">any</span> <span m=\"4043380\"\
  >idea.</span> <span m=\"4044550\">But</span> <span m=\"4045540\">as</span> <span\
  \ m=\"4045720\">time</span> <span m=\"4046140\">proceeds,</span> <span m=\"4047250\"\
  >you</span> <span m=\"4047490\">make</span> <span m=\"4047820\">an</span> <span\
  \ m=\"4047970\">educated</span> <span m=\"4048600\">guess</span> <span m=\"4048990\"\
  >based</span> <span m=\"4049380\">on</span> <span m=\"4049470\">the</span> <span\
  \ m=\"4049530\">information</span> <span m=\"4050070\">that</span> <span m=\"4050190\"\
  >you</span> <span m=\"4050280\">have,</span> <span m=\"4050790\">all</span> <span\
  \ m=\"4050910\">the</span> <span m=\"4051000\">information</span> <span m=\"4051480\"\
  >you</span> <span m=\"4051630\">have</span> <span m=\"4051990\">up</span> <span\
  \ m=\"4052170\">to</span> <span m=\"4052350\">that</span> <span m=\"4052560\">point.</span></p><p><span\
  \ m=\"4053890\">And</span> <span m=\"4054100\">that</span> <span m=\"4054370\">information</span>\
  \ <span m=\"4054970\">becomes</span> <span m=\"4055450\">a</span> <span m=\"4055510\"\
  >larger</span> <span m=\"4055870\">and</span> <span m=\"4055960\">larger</span>\
  \ <span m=\"4056260\">set</span> <span m=\"4056590\">as</span> <span m=\"4056740\"\
  >time</span> <span m=\"4057160\">moves</span> <span m=\"4057490\">forward.</span>\
  \ <span m=\"4058420\">Your</span> <span m=\"4058600\">prediction</span> <span m=\"\
  4059610\">is</span> <span m=\"4059830\">going</span> <span m=\"4059980\">to</span>\
  \ <span m=\"4060040\">be</span> <span m=\"4060160\">a</span> <span m=\"4060220\"\
  >random</span> <span m=\"4060550\">variable</span> <span m=\"4060940\">that</span>\
  \ <span m=\"4061090\">goes</span> <span m=\"4061330\">up</span> <span m=\"4061480\"\
  >and</span> <span m=\"4061570\">down.</span> <span m=\"4063790\">And</span> <span\
  \ m=\"4063910\">that</span> <span m=\"4064030\">will</span> <span m=\"4064180\"\
  >be</span> <span m=\"4064300\">a</span> <span m=\"4064330\">martingale,</span> <span\
  \ m=\"4066540\">because--</span> <span m=\"4068120\">so</span> <span m=\"4068270\"\
  >how</span> <span m=\"4068850\">I</span> <span m=\"4069000\">predict</span> <span\
  \ m=\"4069480\">today</span> <span m=\"4072000\">based</span> <span m=\"4072330\"\
  >on</span> <span m=\"4072750\">what</span> <span m=\"4072980\">are</span> <span\
  \ m=\"4073080\">all</span> <span m=\"4073200\">the</span> <span m=\"4073290\">possibilities</span>\
  \ <span m=\"4074100\">happening</span> <span m=\"4074610\">going</span> <span m=\"\
  4074880\">forward,</span> <span m=\"4076660\">well,</span> <span m=\"4076770\">one</span>\
  \ <span m=\"4077070\">of</span> <span m=\"4078610\">many</span> <span m=\"4078820\"\
  >things</span> <span m=\"4079060\">could</span> <span m=\"4079180\">happen.</span>\
  \ <span m=\"4080300\">But</span> <span m=\"4081310\">if</span> <span m=\"4081610\"\
  >I</span> <span m=\"4081820\">knew</span> <span m=\"4082180\">that</span> <span\
  \ m=\"4082420\">my</span> <span m=\"4083740\">prediction</span> <span m=\"4084280\"\
  >is</span> <span m=\"4084460\">going</span> <span m=\"4084670\">to,</span> <span\
  \ m=\"4084840\">in</span> <span m=\"4085030\">expectation,</span> <span m=\"4085810\"\
  >shift</span> <span m=\"4086290\">upwards,</span> <span m=\"4087250\">then</span>\
  \ <span m=\"4087760\">I</span> <span m=\"4087880\">shouldn't</span> <span m=\"4088240\"\
  >have</span> <span m=\"4088390\">predicted</span> <span m=\"4088840\">what</span>\
  \ <span m=\"4088990\">I</span> <span m=\"4089080\">predict</span> <span m=\"4089410\"\
  >today.</span> <span m=\"4089710\">I</span> <span m=\"4089800\">should</span> <span\
  \ m=\"4090000\">have</span> <span m=\"4090640\">predicted</span> <span m=\"4091120\"\
  >upwards</span> <span m=\"4091480\">anyway.</span></p><p><span m=\"4093540\">OK.</span>\
  \ <span m=\"4093800\">So</span> <span m=\"4094010\">this</span> <span m=\"4094220\"\
  >is</span> <span m=\"4097359\">another</span> <span m=\"4097720\">construction</span>\
  \ <span m=\"4098380\">of</span> <span m=\"4098500\">martingales.</span> <span m=\"\
  4099819\">So</span> <span m=\"4100390\">this</span> <span m=\"4100630\">also</span>\
  \ <span m=\"4100840\">comes</span> <span m=\"4101109\">up.</span> <span m=\"4101410\"\
  >You</span> <span m=\"4101500\">could</span> <span m=\"4101620\">have</span> <span\
  \ m=\"4102069\">other</span> <span m=\"4103180\">more</span> <span m=\"4103420\"\
  >pure</span> <span m=\"4103750\">mathematics-type</span> <span m=\"4105370\">explanations,</span>\
  \ <span m=\"4106120\">where</span> <span m=\"4106620\">suppose</span> <span m=\"\
  4107080\">I</span> <span m=\"4107170\">want</span> <span m=\"4107350\">to</span>\
  \ <span m=\"4107439\">know</span> <span m=\"4109710\">what</span> <span m=\"4109930\"\
  >is</span> <span m=\"4110050\">the</span> <span m=\"4111370\">chromatic</span> <span\
  \ m=\"4111819\">number</span> <span m=\"4112210\">of</span> <span m=\"4112450\"\
  >a</span> <span m=\"4113319\">random</span> <span m=\"4113649\">graph.</span> <span\
  \ m=\"4114490\">And</span> <span m=\"4114609\">I</span> <span m=\"4114700\">show</span>\
  \ <span m=\"4115000\">you</span> <span m=\"4115479\">that</span> <span m=\"4115630\"\
  >graph</span> <span m=\"4115960\">one</span> <span m=\"4116410\">edge</span> <span\
  \ m=\"4116710\">at</span> <span m=\"4116830\">a</span> <span m=\"4116890\">time.</span></p><p><span\
  \ m=\"4118960\">You</span> <span m=\"4119109\">can</span> <span m=\"4119229\">predict</span>\
  \ <span m=\"4120340\">the</span> <span m=\"4120490\">expectation.</span> <span m=\"\
  4121270\">You</span> <span m=\"4121330\">can</span> <span m=\"4121479\">find</span>\
  \ <span m=\"4121670\">the</span> <span m=\"4121760\">expectation</span> <span m=\"\
  4122950\">of</span> <span m=\"4123220\">this</span> <span m=\"4123460\">graph's</span>\
  \ <span m=\"4123700\">statistic</span> <span m=\"4124540\">based</span> <span m=\"\
  4124840\">on</span> <span m=\"4124960\">what</span> <span m=\"4125109\">you've</span>\
  \ <span m=\"4125229\">seen</span> <span m=\"4126279\">up</span> <span m=\"4126460\"\
  >to</span> <span m=\"4126580\">time</span> <span m=\"4126939\">n.</span> <span m=\"\
  4127630\">And</span> <span m=\"4128080\">that</span> <span m=\"4128229\">sequence</span>\
  \ <span m=\"4128740\">will</span> <span m=\"4128850\">be a</span> <span m=\"4129040\"\
  >martingale.</span></p><p><span m=\"4131979\">An</span> <span m=\"4132100\">important</span>\
  \ <span m=\"4132970\">property</span> <span m=\"4133479\">of</span> <span m=\"4133740\"\
  >a</span> <span m=\"4133870\">martingale,</span> <span m=\"4136149\">which is</span>\
  \ <span m=\"4136330\">known</span> <span m=\"4136720\">as</span> <span m=\"4137800\"\
  >the</span> <span m=\"4137950\">martingale</span> <span m=\"4138850\">convergence</span>\
  \ <span m=\"4139510\">theorem--</span> <span m=\"4139990\">and</span> <span m=\"\
  4142029\">so</span> <span m=\"4142210\">that's</span> <span m=\"4142450\">what</span>\
  \ <span m=\"4143680\">we'll</span> <span m=\"4143830\">need</span> <span m=\"4144430\"\
  >for</span> <span m=\"4145520\">the</span> <span m=\"4145720\">proof</span> <span\
  \ m=\"4146050\">of</span> <span m=\"4146140\">the</span> <span m=\"4146200\">existence</span>\
  \ <span m=\"4146740\">of</span> <span m=\"4146830\">the</span> <span m=\"4146890\"\
  >limit</span> <span m=\"4147380\">next</span> <span m=\"4147550\">time--</span>\
  \ <span m=\"4155689\">says</span> <span m=\"4156080\">that</span> <span m=\"4156859\"\
  >every</span> <span m=\"4158479\">bounded</span> <span m=\"4159260\">martingale--</span>\
  \ <span m=\"4163649\">so</span> <span m=\"4163960\">for</span> <span m=\"4164109\"\
  >example,</span> <span m=\"4164560\">suppose</span> <span m=\"4164970\">your</span>\
  \ <span m=\"4165069\">martingale</span> <span m=\"4166990\">only</span> <span m=\"\
  4167229\">takes</span> <span m=\"4167529\">values</span> <span m=\"4167890\">between</span>\
  \ <span m=\"4168340\">0</span> <span m=\"4168700\">and</span> <span m=\"4168790\"\
  >1.</span> <span m=\"4169590\">So</span> <span m=\"4169930\">every</span> <span\
  \ m=\"4170170\">bounded</span> <span m=\"4170590\">martingale</span> <span m=\"\
  4171700\">converges</span> <span m=\"4172630\">almost</span> <span m=\"4173080\"\
  >surely.</span></p><p><span m=\"4182870\">You</span> <span m=\"4182990\">cannot</span>\
  \ <span m=\"4183290\">have</span> <span m=\"4183439\">a</span> <span m=\"4183500\"\
  >martingale</span> <span m=\"4184399\">which</span> <span m=\"4184640\">you</span>\
  \ <span m=\"4184790\">expect</span> <span m=\"4185270\">to</span> <span m=\"4186300\"\
  >constantly</span> <span m=\"4186740\">go</span> <span m=\"4186920\">up</span> <span\
  \ m=\"4187069\">and</span> <span m=\"4187160\">down.</span> <span m=\"4193040\"\
  >So</span> <span m=\"4193229\">I</span> <span m=\"4193330\">want</span> <span m=\"\
  4193540\">to</span> <span m=\"4193689\">show</span> <span m=\"4193899\">you</span>\
  \ <span m=\"4194050\">a</span> <span m=\"4194109\">proof</span> <span m=\"4194440\"\
  >of</span> <span m=\"4194530\">this</span> <span m=\"4194740\">fact.</span> <span\
  \ m=\"4196170\">Let</span> <span m=\"4196280\">me</span> <span m=\"4196390\">just</span>\
  \ <span m=\"4196540\">mention</span> <span m=\"4196870\">that</span> <span m=\"\
  4197000\">the</span> <span m=\"4197110\">bounded</span> <span m=\"4197650\">condition</span>\
  \ <span m=\"4198250\">is</span> <span m=\"4199090\">a</span> <span m=\"4199150\"\
  >little</span> <span m=\"4199390\">bit</span> <span m=\"4199540\">stronger</span>\
  \ <span m=\"4200080\">than</span> <span m=\"4200260\">what</span> <span m=\"4200380\"\
  >we</span> <span m=\"4200560\">actually</span> <span m=\"4200980\">need.</span>\
  \ <span m=\"4201490\">From</span> <span m=\"4201700\">the</span> <span m=\"4201760\"\
  >proof,</span> <span m=\"4202080\">you'll</span> <span m=\"4202210\">see</span>\
  \ <span m=\"4202480\">that</span> <span m=\"4202780\">you</span> <span m=\"4202960\"\
  >really</span> <span m=\"4203200\">only</span> <span m=\"4203470\">need</span> <span\
  \ m=\"4203980\">them</span> <span m=\"4204220\">to</span> <span m=\"4204340\">be</span>\
  \ <span m=\"4205360\">L1</span> <span m=\"4205760\">bounded.</span> <span m=\"4208010\"\
  >It's</span> <span m=\"4208290\">enough.</span></p><p><span m=\"4210360\">And</span>\
  \ <span m=\"4210510\">more</span> <span m=\"4210690\">generally,</span> <span m=\"\
  4211450\">there</span> <span m=\"4211580\">is</span> <span m=\"4211710\">a</span>\
  \ <span m=\"4211770\">condition</span> <span m=\"4212190\">called</span> <span m=\"\
  4212760\">uniform</span> <span m=\"4213330\">integrability,</span> <span m=\"4218480\"\
  >which</span> <span m=\"4218660\">I</span> <span m=\"4218750\">won't</span> <span\
  \ m=\"4218960\">explain.</span> <span m=\"4222368\">All right.</span> <span m=\"\
  4226360\">OK.</span> <span m=\"4226620\">So</span> <span m=\"4226740\">let</span>\
  \ <span m=\"4226860\">me</span> <span m=\"4227010\">show</span> <span m=\"4227280\"\
  >you</span> <span m=\"4227430\">a</span> <span m=\"4227490\">proof</span> <span\
  \ m=\"4228060\">of</span> <span m=\"4228300\">the</span> <span m=\"4228420\">martingale</span>\
  \ <span m=\"4228930\">convergence</span> <span m=\"4229470\">theorem.</span> <span\
  \ m=\"4229750\">And</span> <span m=\"4230070\">I'm</span> <span m=\"4230340\">going</span>\
  \ <span m=\"4230490\">to</span> <span m=\"4230550\">be</span> <span m=\"4230670\"\
  >somewhat</span> <span m=\"4231420\">informal</span> <span m=\"4232070\">and</span>\
  \ <span m=\"4232260\">somewhat</span> <span m=\"4232860\">cavalier,</span> <span\
  \ m=\"4233520\">because</span> <span m=\"4233820\">I</span> <span m=\"4233940\"\
  >don't</span> <span m=\"4234090\">want</span> <span m=\"4234240\">to</span> <span\
  \ m=\"4234300\">get</span> <span m=\"4234480\">into</span> <span m=\"4234780\">some</span>\
  \ <span m=\"4235650\">of</span> <span m=\"4235710\">the</span> <span m=\"4236760\"\
  >fine</span> <span m=\"4237120\">details</span> <span m=\"4237570\">of</span> <span\
  \ m=\"4237660\">probability</span> <span m=\"4238230\">theory.</span> <span m=\"\
  4238550\">But</span> <span m=\"4238860\">if</span> <span m=\"4238980\">you</span>\
  \ <span m=\"4239760\">have</span> <span m=\"4239940\">taken</span> <span m=\"4240510\"\
  >something</span> <span m=\"4240870\">like</span> <span m=\"4241290\">18.675</span>\
  \ <span m=\"4243030\">probability</span> <span m=\"4243540\">theory,</span> <span\
  \ m=\"4243840\">then</span> <span m=\"4244050\">you</span> <span m=\"4244140\">can</span>\
  \ <span m=\"4244290\">fill</span> <span m=\"4244470\">in</span> <span m=\"4244740\"\
  >all</span> <span m=\"4244860\">those</span> <span m=\"4245070\">details.</span></p><p><span\
  \ m=\"4248580\">So</span> <span m=\"4248730\">I</span> <span m=\"4248810\">like</span>\
  \ <span m=\"4248970\">this</span> <span m=\"4249150\">proof,</span> <span m=\"4249390\"\
  >because</span> <span m=\"4249750\">it's</span> <span m=\"4250290\">kind</span>\
  \ <span m=\"4250470\">of</span> <span m=\"4250560\">a</span> <span m=\"4250590\"\
  >proof</span> <span m=\"4250980\">by</span> <span m=\"4251280\">gambling.</span>\
  \ <span m=\"4256680\">So</span> <span m=\"4256860\">I</span> <span m=\"4256890\"\
  >want</span> <span m=\"4257040\">to</span> <span m=\"4257100\">tell</span> <span\
  \ m=\"4257340\">you</span> <span m=\"4257490\">a</span> <span m=\"4257550\">story</span>\
  \ <span m=\"4258360\">which</span> <span m=\"4258960\">should</span> <span m=\"\
  4259140\">convince</span> <span m=\"4259590\">you</span> <span m=\"4259890\">that\
  \ a</span> <span m=\"4260250\">martingale</span> <span m=\"4261060\">cannot</span>\
  \ <span m=\"4263010\">keep</span> <span m=\"4263220\">going</span> <span m=\"4263670\"\
  >up</span> <span m=\"4263850\">and</span> <span m=\"4263940\">down.</span> <span\
  \ m=\"4264380\">It</span> <span m=\"4264510\">must</span> <span m=\"4264820\">converge</span>\
  \ <span m=\"4265380\">almost</span> <span m=\"4265720\">surely.</span></p><p><span\
  \ m=\"4268640\">So</span> <span m=\"4268790\">suppose</span> <span m=\"4273570\"\
  >x</span> <span m=\"4274280\">sub</span> <span m=\"4274460\">n</span> <span m=\"\
  4275310\">doesn't</span> <span m=\"4275670\">converge.</span> <span m=\"4279940\"\
  >OK,</span> <span m=\"4280150\">so</span> <span m=\"4280270\">this</span> <span\
  \ m=\"4280420\">is</span> <span m=\"4280510\">why</span> <span m=\"4280750\">I</span>\
  \ <span m=\"4280810\">say</span> <span m=\"4281020\">I'm</span> <span m=\"4281170\"\
  >going</span> <span m=\"4281280\">to</span> <span m=\"4281350\">be</span> <span\
  \ m=\"4281410\">somewhat</span> <span m=\"4281680\">cavalier</span> <span m=\"4282160\"\
  >with</span> <span m=\"4282280\">probability</span> <span m=\"4282730\">theory.</span>\
  \ <span m=\"4283040\">So</span> <span m=\"4283060\">when</span> <span m=\"4283210\"\
  >I</span> <span m=\"4283270\">say</span> <span m=\"4283840\">this</span> <span m=\"\
  4284050\">doesn't</span> <span m=\"4284320\">converge,</span> <span m=\"4284680\"\
  >I</span> <span m=\"4284740\">mean</span> <span m=\"4284920\">a</span> <span m=\"\
  4284980\">specific</span> <span m=\"4285550\">instance</span> <span m=\"4286240\"\
  >of</span> <span m=\"4286360\">the</span> <span m=\"4286480\">sequence</span> <span\
  \ m=\"4286900\">doesn't</span> <span m=\"4287200\">converge</span> <span m=\"4288060\"\
  >or</span> <span m=\"4288220\">some</span> <span m=\"4288580\">specific</span> <span\
  \ m=\"4289060\">realization.</span> <span m=\"4290050\">If</span> <span m=\"4290200\"\
  >it</span> <span m=\"4290260\">doesn't</span> <span m=\"4290500\">converge,</span>\
  \ <span m=\"4291370\">then</span> <span m=\"4293520\">there</span> <span m=\"4293700\"\
  >exists</span> <span m=\"4297459\">a</span> <span m=\"4297910\">and</span> <span\
  \ m=\"4298110\">b,</span> <span m=\"4299490\">both</span> <span m=\"4299940\">rational</span>\
  \ <span m=\"4300450\">numbers</span> <span m=\"4303150\">between</span> <span m=\"\
  4303600\">0</span> <span m=\"4303860\">and</span> <span m=\"4303960\">1,</span>\
  \ <span m=\"4306210\">such</span> <span m=\"4306510\">that</span> <span m=\"4307920\"\
  >the</span> <span m=\"4308010\">sequence</span> <span m=\"4310740\">crosses</span>\
  \ <span m=\"4314240\">the</span> <span m=\"4314330\">interval</span> <span m=\"\
  4315440\">a,</span> <span m=\"4315610\">b</span> <span m=\"4317570\">infinitely</span>\
  \ <span m=\"4318410\">many</span> <span m=\"4318650\">times.</span></p><p><span\
  \ m=\"4326040\">So</span> <span m=\"4326400\">by</span> <span m=\"4326760\">crossing</span>\
  \ <span m=\"4327540\">this</span> <span m=\"4328020\">interval,</span> <span m=\"\
  4329320\">what</span> <span m=\"4329400\">I</span> <span m=\"4329490\">mean</span>\
  \ <span m=\"4329820\">is</span> <span m=\"4330030\">the</span> <span m=\"4330120\"\
  >following.</span> <span m=\"4339780\">OK.</span> <span m=\"4340010\">So</span>\
  \ <span m=\"4341680\">there's</span> <span m=\"4341930\">an</span> <span m=\"4342000\"\
  >important</span> <span m=\"4342420\">picture</span> <span m=\"4342930\">which</span>\
  \ <span m=\"4343140\">will</span> <span m=\"4343320\">help</span> <span m=\"4344130\"\
  >a</span> <span m=\"4344190\">lot</span> <span m=\"4344430\">in</span> <span m=\"\
  4344580\">understanding</span> <span m=\"4345420\">this</span> <span m=\"4345620\"\
  >theorem.</span> <span m=\"4351550\">So</span> <span m=\"4351760\">imagine</span>\
  \ <span m=\"4352400\">I</span> <span m=\"4352570\">have</span> <span m=\"4353080\"\
  >this</span> <span m=\"4353590\">time</span> <span m=\"4354120\">n,</span> <span\
  \ m=\"4355150\">and</span> <span m=\"4355540\">I</span> <span m=\"4355660\">have</span>\
  \ <span m=\"4358174\">a</span> <span m=\"4358660\">and</span> <span m=\"4358960\"\
  >b.</span> <span m=\"4361300\">So</span> <span m=\"4361870\">I</span> <span m=\"\
  4361960\">have</span> <span m=\"4362110\">this</span> <span m=\"4362260\">martingale.</span>\
  \ <span m=\"4363130\">It's</span> <span m=\"4363370\">realization</span> <span m=\"\
  4364630\">curve</span> <span m=\"4374463\">will be</span> <span m=\"4374970\">like</span>\
  \ <span m=\"4375130\">that.</span> <span m=\"4375850\">So</span> <span m=\"4375930\"\
  >that's</span> <span m=\"4376730\">an</span> <span m=\"4376830\">instance</span>\
  \ <span m=\"4377220\">of</span> <span m=\"4377310\">this</span> <span m=\"4377460\"\
  >martingale.</span></p><p><span m=\"4378390\">And</span> <span m=\"4379020\">by</span>\
  \ <span m=\"4379260\">crossing,</span> <span m=\"4380460\">I</span> <span m=\"4380610\"\
  >mean</span> <span m=\"4381720\">a</span> <span m=\"4381780\">sequence</span> <span\
  \ m=\"4382350\">that--</span> <span m=\"4383950\">OK,</span> <span m=\"4384240\"\
  >so</span> <span m=\"4384390\">here's</span> <span m=\"4384930\">what</span> <span\
  \ m=\"4385080\">I</span> <span m=\"4385170\">mean</span> <span m=\"4385320\">by</span>\
  \ <span m=\"4385440\">crossing.</span> <span m=\"4387390\">I</span> <span m=\"4387660\"\
  >start</span> <span m=\"4390620\">below</span> <span m=\"4391450\">a</span> <span\
  \ m=\"4393540\">and--</span> <span m=\"4395400\">let me use a</span> <span m=\"\
  4395870\">different</span> <span m=\"4396110\">color.</span> <span m=\"4399170\"\
  >So</span> <span m=\"4399250\">I</span> <span m=\"4399370\">start</span> <span m=\"\
  4399730\">below</span> <span m=\"4400030\">a,</span> <span m=\"4402988\">and</span>\
  \ <span m=\"4403440\">I</span> <span m=\"4404010\">go</span> <span m=\"4404220\"\
  >above</span> <span m=\"4404550\">b</span> <span m=\"4405830\">and</span> <span\
  \ m=\"4405930\">then</span> <span m=\"4406110\">wait</span> <span m=\"4406320\"\
  >until</span> <span m=\"4406510\">I</span> <span m=\"4406640\">come</span> <span\
  \ m=\"4406860\">back</span> <span m=\"4407370\">below</span> <span m=\"4407730\"\
  >a.</span> <span m=\"4410430\">And</span> <span m=\"4410910\">I</span> <span m=\"\
  4410970\">go</span> <span m=\"4411150\">above</span> <span m=\"4411450\">b.</span>\
  \ <span m=\"4412740\">Wait</span> <span m=\"4412950\">until</span> <span m=\"4413280\"\
  >I</span> <span m=\"4413370\">come</span> <span m=\"4413580\">back.</span> <span\
  \ m=\"4416040\">So</span> <span m=\"4416880\">do</span> <span m=\"4417080\">like</span>\
  \ <span m=\"4417260\">that.</span> <span m=\"4425592\">Like that.</span></p><p><span\
  \ m=\"4432860\">So</span> <span m=\"4434190\">I</span> <span m=\"4434330\">start</span>\
  \ <span m=\"4434660\">below</span> <span m=\"4435020\">a</span> <span m=\"4435530\"\
  >until</span> <span m=\"4435770\">the</span> <span m=\"4435860\">first</span> <span\
  \ m=\"4436160\">time</span> <span m=\"4436520\">I</span> <span m=\"4437180\">go</span>\
  \ <span m=\"4437360\">above</span> <span m=\"4437660\">b.</span> <span m=\"4437900\"\
  >And then I</span> <span m=\"4438200\">stop</span> <span m=\"4438590\">that</span>\
  \ <span m=\"4438770\">sequence.</span> <span m=\"4439700\">So</span> <span m=\"\
  4442040\">those</span> <span m=\"4442280\">are</span> <span m=\"4442370\">the</span>\
  \ <span m=\"4442640\">upcrossings</span> <span m=\"4444110\">of</span> <span m=\"\
  4444320\">this</span> <span m=\"4444680\">martingale.</span> <span m=\"4452980\"\
  >So</span> <span m=\"4453480\">upcrossing</span> <span m=\"4454520\">is when</span>\
  \ <span m=\"4454860\">you</span> <span m=\"4455080\">start</span> <span m=\"4455420\"\
  >below</span> <span m=\"4455690\">a,</span> <span m=\"4455960\">and</span> <span\
  \ m=\"4456050\">then</span> <span m=\"4456170\">you</span> <span m=\"4456800\">end</span>\
  \ <span m=\"4456950\">up</span> <span m=\"4457100\">above</span> <span m=\"4457390\"\
  >b.</span></p><p><span m=\"4458720\">So</span> <span m=\"4458960\">if</span> <span\
  \ m=\"4459110\">you</span> <span m=\"4459230\">don't</span> <span m=\"4459410\"\
  >converge,</span> <span m=\"4461060\">then</span> <span m=\"4462560\">there</span>\
  \ <span m=\"4462830\">exists</span> <span m=\"4465530\">such</span> <span m=\"4465770\"\
  >a</span> <span m=\"4466040\">and</span> <span m=\"4466250\">b</span> <span m=\"\
  4467240\">such that</span> <span m=\"4467390\">there</span> <span m=\"4467540\"\
  >are</span> <span m=\"4467600\">infinitely</span> <span m=\"4468080\">many</span>\
  \ <span m=\"4468470\">such</span> <span m=\"4468740\">crossings.</span> <span m=\"\
  4470360\">So</span> <span m=\"4470590\">this</span> <span m=\"4470790\">is</span>\
  \ <span m=\"4471300\">just</span> <span m=\"4472060\">a</span> <span m=\"4472230\"\
  >fact.</span> <span m=\"4472950\">It's</span> <span m=\"4473280\">not</span> <span\
  \ m=\"4474120\">hard</span> <span m=\"4474390\">to</span> <span m=\"4474480\">see.</span></p><p><span\
  \ m=\"4476910\">And</span> <span m=\"4477390\">what</span> <span m=\"4477570\">we'll</span>\
  \ <span m=\"4477770\">show</span> <span m=\"4478050\">is</span> <span m=\"4478170\"\
  >that</span> <span m=\"4478350\">this</span> <span m=\"4478710\">doesn't</span>\
  \ <span m=\"4479070\">happen</span> <span m=\"4480000\">except</span> <span m=\"\
  4480360\">with</span> <span m=\"4480480\">probability</span> <span m=\"4481410\"\
  >0.</span> <span m=\"4482280\">So</span> <span m=\"4482490\">we'll</span> <span\
  \ m=\"4482700\">show</span> <span m=\"4487380\">that</span> <span m=\"4489240\"\
  >this</span> <span m=\"4489480\">occurs</span> <span m=\"4491500\">with</span> <span\
  \ m=\"4491770\">probability</span> <span m=\"4492940\">0.</span> <span m=\"4495950\"\
  >And</span> <span m=\"4496280\">because</span> <span m=\"4496720\">there are</span>\
  \ <span m=\"4496840\">only</span> <span m=\"4497090\">countably</span> <span m=\"\
  4497630\">many</span> <span m=\"4502930\">rational</span> <span m=\"4503380\">numbers,</span>\
  \ <span m=\"4505950\">we</span> <span m=\"4505990\">find</span> <span m=\"4506320\"\
  >that</span> <span m=\"4509760\">x sub n</span> <span m=\"4510220\">converges</span>\
  \ <span m=\"4511690\">with</span> <span m=\"4511870\">probability</span> <span m=\"\
  4512720\">1.</span></p><p><span m=\"4522440\">So</span> <span m=\"4522590\">these</span>\
  \ <span m=\"4522800\">are</span> <span m=\"4522920\">upcrossings.</span> <span m=\"\
  4523630\">So</span> <span m=\"4523820\">I</span> <span m=\"4524150\">didn't</span>\
  \ <span m=\"4524510\">define</span> <span m=\"4524810\">it,</span> <span m=\"4524870\"\
  >but</span> <span m=\"4525560\">hopefully you</span> <span m=\"4525920\">understood</span>\
  \ <span m=\"4526340\">from</span> <span m=\"4526550\">my</span> <span m=\"4527480\"\
  >picture</span> <span m=\"4527840\">and</span> <span m=\"4527910\">my</span> <span\
  \ m=\"4528050\">description.</span> <span m=\"4529160\">And</span> <span m=\"4529820\"\
  >let</span> <span m=\"4530030\">me</span> <span m=\"4532010\">define</span> <span\
  \ m=\"4532820\">by</span> <span m=\"4534470\">u sub</span> <span m=\"4534870\">n</span>\
  \ <span m=\"4535910\">to</span> <span m=\"4536030\">be</span> <span m=\"4536270\"\
  >the</span> <span m=\"4536780\">number</span> <span m=\"4537290\">of</span> <span\
  \ m=\"4537620\">upcrossings</span> <span m=\"4542300\">up</span> <span m=\"4542480\"\
  >to</span> <span m=\"4544170\">time</span> <span m=\"4544620\">n,</span> <span m=\"\
  4550530\">so</span> <span m=\"4550620\">the</span> <span m=\"4550710\">number</span>\
  \ <span m=\"4551130\">of</span> <span m=\"4551730\">such</span> <span m=\"4552040\"\
  >upcrossings.</span></p><p><span m=\"4555950\">Now</span> <span m=\"4556210\">let</span>\
  \ <span m=\"4556360\">me</span> <span m=\"4556480\">consider</span> <span m=\"4556990\"\
  >a</span> <span m=\"4557470\">betting</span> <span m=\"4557890\">strategy.</span>\
  \ <span m=\"4565790\">Basically,</span> <span m=\"4566270\">I</span> <span m=\"\
  4566390\">want</span> <span m=\"4566630\">to</span> <span m=\"4566690\">make</span>\
  \ <span m=\"4566960\">money.</span> <span m=\"4567770\">And</span> <span m=\"4569270\"\
  >I</span> <span m=\"4569360\">want</span> <span m=\"4569540\">to</span> <span m=\"\
  4569600\">make</span> <span m=\"4569780\">money</span> <span m=\"4570410\">by</span>\
  \ <span m=\"4570830\">following</span> <span m=\"4572750\">these</span> <span m=\"\
  4573140\">upcrossings.</span></p><p><span m=\"4575310\">OK.</span> <span m=\"4575790\"\
  >So</span> <span m=\"4576030\">every</span> <span m=\"4576240\">time</span> <span\
  \ m=\"4576510\">you</span> <span m=\"4576600\">give</span> <span m=\"4576780\">me</span>\
  \ <span m=\"4578880\">a</span> <span m=\"4578940\">number</span> <span m=\"4579480\"\
  >and--</span> <span m=\"4580050\">so</span> <span m=\"4580200\">think</span> <span\
  \ m=\"4580410\">of</span> <span m=\"4580500\">this</span> <span m=\"4580680\">as</span>\
  \ <span m=\"4580800\">the</span> <span m=\"4580890\">stock</span> <span m=\"4581220\"\
  >market.</span> <span m=\"4581710\">So</span> <span m=\"4582000\">it's</span> <span\
  \ m=\"4582250\">a</span> <span m=\"4582330\">fair</span> <span m=\"4582630\">stock</span>\
  \ <span m=\"4582930\">market</span> <span m=\"4583260\">where</span> <span m=\"\
  4585860\">you</span> <span m=\"4585980\">tell</span> <span m=\"4586160\">me</span>\
  \ <span m=\"4586310\">the</span> <span m=\"4586400\">price,</span> <span m=\"4586730\"\
  >and</span> <span m=\"4586880\">I</span> <span m=\"4586970\">get</span> <span m=\"\
  4587120\">to</span> <span m=\"4587210\">decide,</span> <span m=\"4587700\">do</span>\
  \ <span m=\"4587800\">I</span> <span m=\"4587900\">want</span> <span m=\"4587930\"\
  >to</span> <span m=\"4587990\">buy?</span> <span m=\"4588230\">Or</span> <span m=\"\
  4588320\">do</span> <span m=\"4588420\">I</span> <span m=\"4588470\">want</span>\
  \ <span m=\"4588620\">to</span> <span m=\"4588680\">sell?</span></p><p><span m=\"\
  4591070\">So</span> <span m=\"4591220\">consider</span> <span m=\"4591580\">the</span>\
  \ <span m=\"4591640\">betting</span> <span m=\"4591910\">strategy</span> <span m=\"\
  4592930\">where</span> <span m=\"4593340\">at</span> <span m=\"4597620\">any</span>\
  \ <span m=\"4597840\">time,</span> <span m=\"4605720\">we're</span> <span m=\"4605770\"\
  >going</span> <span m=\"4605900\">to</span> <span m=\"4606010\">hold</span> <span\
  \ m=\"4607030\">either</span> <span m=\"4608290\">0</span> <span m=\"4609190\">or</span>\
  \ <span m=\"4609310\">1</span> <span m=\"4611410\">share</span> <span m=\"4612040\"\
  >of</span> <span m=\"4613020\">the</span> <span m=\"4613150\">stock,</span> <span\
  \ m=\"4614320\">which</span> <span m=\"4614530\">has</span> <span m=\"4614920\"\
  >these</span> <span m=\"4615220\">moving</span> <span m=\"4615550\">prices.</span>\
  \ <span m=\"4617590\">And</span> <span m=\"4617830\">what</span> <span m=\"4618070\"\
  >we're</span> <span m=\"4618220\">going</span> <span m=\"4618370\">to</span> <span\
  \ m=\"4618430\">do</span> <span m=\"4618850\">is</span> <span m=\"4620140\">if</span>\
  \ <span m=\"4626630\">xn</span> <span m=\"4627040\">is</span> <span m=\"4627260\"\
  >less</span> <span m=\"4627560\">than</span> <span m=\"4627770\">a, is</span> <span\
  \ m=\"4628190\">less</span> <span m=\"4628430\">than</span> <span m=\"4628710\"\
  >the</span> <span m=\"4628880\">lower</span> <span m=\"4629180\">bound,</span> <span\
  \ m=\"4630090\">then</span> <span m=\"4631910\">we're</span> <span m=\"4632060\"\
  >going</span> <span m=\"4632300\">to</span> <span m=\"4633080\">buy</span> <span\
  \ m=\"4633410\">and</span> <span m=\"4633590\">hold,</span> <span m=\"4636230\"\
  >meaning</span> <span m=\"4636560\">1,</span> <span m=\"4638590\">until</span> <span\
  \ m=\"4642440\">the</span> <span m=\"4642530\">first</span> <span m=\"4642830\"\
  >time</span> <span m=\"4647890\">that</span> <span m=\"4650240\">the</span> <span\
  \ m=\"4650330\">price</span> <span m=\"4652890\">reaches</span> <span m=\"4656950\"\
  >above</span> <span m=\"4657310\">b</span> <span m=\"4659510\">and</span> <span\
  \ m=\"4659720\">then</span> <span m=\"4662450\">sell</span> <span m=\"4663810\"\
  >as</span> <span m=\"4663950\">soon</span> <span m=\"4664280\">as</span> <span m=\"\
  4664400\">the</span> <span m=\"4665900\">first</span> <span m=\"4666140\">time</span>\
  \ <span m=\"4666350\">we</span> <span m=\"4666470\">see</span> <span m=\"4666620\"\
  >the</span> <span m=\"4666770\">price</span> <span m=\"4667130\">goes</span> <span\
  \ m=\"4667400\">above</span> <span m=\"4667570\">b.</span></p><p><span m=\"4670950\"\
  >So</span> <span m=\"4671050\">this</span> <span m=\"4671120\">is</span> <span m=\"\
  4671220\">the</span> <span m=\"4671300\">betting</span> <span m=\"4671570\">strategy.</span>\
  \ <span m=\"4672900\">And</span> <span m=\"4673280\">it's</span> <span m=\"4673520\"\
  >something</span> <span m=\"4673940\">which</span> <span m=\"4674120\">you</span>\
  \ <span m=\"4674240\">can</span> <span m=\"4674390\">implement.</span> <span m=\"\
  4674960\">If</span> <span m=\"4675110\">you</span> <span m=\"4675200\">see</span>\
  \ <span m=\"4675410\">a</span> <span m=\"4675470\">sequence</span> <span m=\"4675860\"\
  >of</span> <span m=\"4675950\">prices,</span> <span m=\"4676940\">you</span> <span\
  \ m=\"4677030\">can</span> <span m=\"4677180\">implement</span> <span m=\"4677600\"\
  >this</span> <span m=\"4677690\">strategy.</span> <span m=\"4679130\">And</span>\
  \ <span m=\"4679750\">you</span> <span m=\"4679850\">already</span> <span m=\"4680540\"\
  >hopefully</span> <span m=\"4680810\">see,</span> <span m=\"4681020\">if</span>\
  \ <span m=\"4681140\">you</span> <span m=\"4681470\">have</span> <span m=\"4681950\"\
  >many</span> <span m=\"4682370\">upcrossings,</span> <span m=\"4683000\">then</span>\
  \ <span m=\"4683220\">each</span> <span m=\"4683420\">upcrossing,</span> <span m=\"\
  4683930\">you</span> <span m=\"4684020\">make</span> <span m=\"4684230\">money.</span>\
  \ <span m=\"4685310\">Each</span> <span m=\"4685490\">upcrossing,</span> <span m=\"\
  4685940\">you</span> <span m=\"4686030\">make</span> <span m=\"4686210\">money.</span></p><p><span\
  \ m=\"4687620\">And</span> <span m=\"4687710\">this</span> <span m=\"4687860\">is</span>\
  \ <span m=\"4687980\">almost</span> <span m=\"4688250\">too</span> <span m=\"4688490\"\
  >good</span> <span m=\"4688700\">to</span> <span m=\"4688760\">be</span> <span m=\"\
  4688880\">true.</span> <span m=\"4689880\">And</span> <span m=\"4689900\">in</span>\
  \ <span m=\"4689990\">fact,</span> <span m=\"4691470\">we</span> <span m=\"4691490\"\
  >see</span> <span m=\"4691790\">that</span> <span m=\"4692030\">the</span> <span\
  \ m=\"4692210\">total</span> <span m=\"4692720\">gain</span> <span m=\"4693410\"\
  >from</span> <span m=\"4693710\">this</span> <span m=\"4693860\">strategy--</span>\
  \ <span m=\"4695160\">so</span> <span m=\"4695660\">if</span> <span m=\"4695780\"\
  >you</span> <span m=\"4695870\">start</span> <span m=\"4696140\">with</span> <span\
  \ m=\"4696270\">some</span> <span m=\"4696410\">balance,</span> <span m=\"4697120\"\
  >what</span> <span m=\"4697300\">you</span> <span m=\"4697370\">get</span> <span\
  \ m=\"4697580\">at</span> <span m=\"4697670\">the</span> <span m=\"4697790\">end--</span>\
  \ <span m=\"4698460\">is</span> <span m=\"4698840\">at</span> <span m=\"4698960\"\
  >least</span> <span m=\"4700790\">this</span> <span m=\"4701210\">difference</span>\
  \ <span m=\"4702110\">from</span> <span m=\"4702670\">a</span> <span m=\"4702750\"\
  >to</span> <span m=\"4702900\">b</span> <span m=\"4703700\">times</span> <span m=\"\
  4705440\">the</span> <span m=\"4705530\">number</span> <span m=\"4705950\">of</span>\
  \ <span m=\"4706340\">upcrossings.</span></p><p><span m=\"4711270\">You</span> <span\
  \ m=\"4711360\">might</span> <span m=\"4712560\">start</span> <span m=\"4713100\"\
  >somewhere.</span> <span m=\"4713610\">You</span> <span m=\"4713760\">buy,</span>\
  \ <span m=\"4714060\">and</span> <span m=\"4714210\">then</span> <span m=\"4714390\"\
  >you</span> <span m=\"4714480\">just</span> <span m=\"4714720\">lose</span> <span\
  \ m=\"4715050\">everything.</span> <span m=\"4715790\">So</span> <span m=\"4716460\"\
  >there</span> <span m=\"4716910\">might</span> <span m=\"4717120\">be</span> <span\
  \ m=\"4717330\">an</span> <span m=\"4717420\">initial</span> <span m=\"4717870\"\
  >cost.</span> <span m=\"4718840\">And</span> <span m=\"4718860\">that</span> <span\
  \ m=\"4718980\">cost</span> <span m=\"4719550\">is</span> <span m=\"4719850\">bounded,</span>\
  \ <span m=\"4721500\">because</span> <span m=\"4721920\">we</span> <span m=\"4722070\"\
  >start</span> <span m=\"4722400\">with</span> <span m=\"4722910\">a</span> <span\
  \ m=\"4723420\">bounded</span> <span m=\"4723990\">martingale.</span> <span m=\"\
  4724680\">So</span> <span m=\"4724860\">suppose</span> <span m=\"4728490\">the</span>\
  \ <span m=\"4729030\">martingale</span> <span m=\"4729330\">is</span> <span m=\"\
  4729630\">always</span> <span m=\"4729990\">between</span> <span m=\"4730410\">0</span>\
  \ <span m=\"4730740\">and</span> <span m=\"4730860\">1.</span> <span m=\"4732780\"\
  >We</span> <span m=\"4733200\">start</span> <span m=\"4733470\">with</span> <span\
  \ m=\"4733590\">a</span> <span m=\"4733650\">bounded</span> <span m=\"4734010\"\
  >martingale.</span></p><p><span m=\"4737530\">But</span> <span m=\"4737740\">on</span>\
  \ <span m=\"4737860\">the</span> <span m=\"4737950\">other</span> <span m=\"4738130\"\
  >hand,</span> <span m=\"4739170\">there</span> <span m=\"4739630\">is</span> <span\
  \ m=\"4739780\">a</span> <span m=\"4739840\">theorem</span> <span m=\"4741730\"\
  >about</span> <span m=\"4741940\">martingales,</span> <span m=\"4743080\">which</span>\
  \ <span m=\"4743320\">is</span> <span m=\"4743770\">not</span> <span m=\"4744010\"\
  >hard</span> <span m=\"4744220\">to</span> <span m=\"4744310\">deduce</span> <span\
  \ m=\"4744670\">from</span> <span m=\"4744820\">the</span> <span m=\"4744880\">definition,</span>\
  \ <span m=\"4745990\">that</span> <span m=\"4746770\">no</span> <span m=\"4746920\"\
  >matter</span> <span m=\"4747160\">what</span> <span m=\"4747340\">the</span> <span\
  \ m=\"4747430\">betting</span> <span m=\"4747700\">strategy</span> <span m=\"4748240\"\
  >is,</span> <span m=\"4748960\">the</span> <span m=\"4749080\">gain</span> <span\
  \ m=\"4749530\">at</span> <span m=\"4749650\">any</span> <span m=\"4749860\">particular</span>\
  \ <span m=\"4750340\">time</span> <span m=\"4751150\">must</span> <span m=\"4751480\"\
  >be</span> <span m=\"4751660\">0</span> <span m=\"4752260\">in</span> <span m=\"\
  4752410\">expectation.</span> <span m=\"4756940\">So</span> <span m=\"4756990\"\
  >this</span> <span m=\"4757170\">is</span> <span m=\"4757290\">just</span> <span\
  \ m=\"4757440\">the</span> <span m=\"4757500\">property</span> <span m=\"4757980\"\
  >of</span> <span m=\"4758100\">the</span> <span m=\"4758190\">martingale.</span>\
  \ <span m=\"4759240\">So</span> <span m=\"4760410\">0</span> <span m=\"4760780\"\
  >equals</span> <span m=\"4761430\">the</span> <span m=\"4761550\">expected</span>\
  \ <span m=\"4762070\">gain,</span> <span m=\"4762810\">which</span> <span m=\"4764190\"\
  >is</span> <span m=\"4764400\">at</span> <span m=\"4764490\">least</span> <span\
  \ m=\"4764970\">b</span> <span m=\"4765120\">minus</span> <span m=\"4765510\">a</span>\
  \ <span m=\"4766040\">times</span> <span m=\"4766470\">the</span> <span m=\"4766590\"\
  >expected</span> <span m=\"4767160\">number</span> <span m=\"4767520\">of upcrossings</span>\
  \ <span m=\"4769290\">minus</span> <span m=\"4769650\">1.</span> <span m=\"4770630\"\
  >And</span> <span m=\"4771120\">thus</span> <span m=\"4772250\">the</span> <span\
  \ m=\"4772380\">expected</span> <span m=\"4772920\">number</span> <span m=\"4773250\"\
  >of</span> <span m=\"4773400\">upcrossings</span> <span m=\"4774120\">up</span>\
  \ <span m=\"4774270\">to</span> <span m=\"4774360\">time</span> <span m=\"4774750\"\
  >n</span> <span m=\"4775430\">is</span> <span m=\"4775740\">at</span> <span m=\"\
  4775890\">most</span> <span m=\"4777750\">1</span> <span m=\"4778200\">over</span>\
  \ <span m=\"4778980\">b</span> <span m=\"4779430\">minus</span> <span m=\"4779860\"\
  >a.</span></p><p><span m=\"4781600\">Now,</span> <span m=\"4781750\">we</span> <span\
  \ m=\"4781900\">let</span> <span m=\"4784120\">n</span> <span m=\"4784900\">go</span>\
  \ <span m=\"4785080\">to</span> <span m=\"4785230\">infinity.</span> <span m=\"\
  4787140\">And</span> <span m=\"4787440\">let</span> <span m=\"4788280\">u</span>\
  \ <span m=\"4788970\">sub</span> <span m=\"4789210\">infinity</span> <span m=\"\
  4792530\">be</span> <span m=\"4793190\">the</span> <span m=\"4793310\">total</span>\
  \ <span m=\"4793670\">number</span> <span m=\"4794060\">of</span> <span m=\"4797020\"\
  >upcrossings.</span> <span m=\"4802030\">By</span> <span m=\"4802270\">the</span>\
  \ <span m=\"4802420\">monotone</span> <span m=\"4802900\">convergence</span> <span\
  \ m=\"4803560\">theorem</span> <span m=\"4805750\">in</span> <span m=\"4805880\"\
  >this</span> <span m=\"4806060\">limit,</span> <span m=\"4817430\">the</span> <span\
  \ m=\"4817520\">limit</span> <span m=\"4817850\">of</span> <span m=\"4818060\">these</span>\
  \ <span m=\"4818480\">u</span> <span m=\"4818720\">sub</span> <span m=\"4818870\"\
  >n's,</span> <span m=\"4819280\">it</span> <span m=\"4819590\">can</span> <span\
  \ m=\"4819710\">never</span> <span m=\"4819950\">go</span> <span m=\"4820100\">down.</span>\
  \ <span m=\"4820310\">It's</span> <span m=\"4820520\">always</span> <span m=\"4822380\"\
  >weakly</span> <span m=\"4822710\">increasing.</span> <span m=\"4823740\">It</span>\
  \ <span m=\"4823970\">converges</span> <span m=\"4824540\">to</span> <span m=\"\
  4825460\">the</span> <span m=\"4825830\">expectation</span> <span m=\"4827120\"\
  >of</span> <span m=\"4827270\">the</span> <span m=\"4827420\">total</span> <span\
  \ m=\"4827750\">number</span> <span m=\"4828020\">of</span> <span m=\"4828110\"\
  >upcrossings.</span></p><p><span m=\"4829340\">So</span> <span m=\"4829460\">now,</span>\
  \ <span m=\"4829760\">in</span> <span m=\"4829850\">particular,</span> <span m=\"\
  4830300\">you</span> <span m=\"4830420\">know</span> <span m=\"4830660\">that</span>\
  \ <span m=\"4830820\">the</span> <span m=\"4830870\">total</span> <span m=\"4831200\"\
  >number</span> <span m=\"4831440\">of</span> <span m=\"4831530\">upcrossings</span>\
  \ <span m=\"4832730\">is</span> <span m=\"4833060\">at</span> <span m=\"4833180\"\
  >most</span> <span m=\"4836040\">some</span> <span m=\"4836730\">finite</span> <span\
  \ m=\"4837180\">number.</span> <span m=\"4838120\">So</span> <span m=\"4838170\"\
  >in</span> <span m=\"4838260\">particular,</span> <span m=\"4839200\">the</span>\
  \ <span m=\"4839300\">probability</span> <span m=\"4840300\">that</span> <span m=\"\
  4840420\">you</span> <span m=\"4840570\">have</span> <span m=\"4840960\">infinitely</span>\
  \ <span m=\"4841500\">many</span> <span m=\"4841830\">crossings</span> <span m=\"\
  4843210\">is</span> <span m=\"4844110\">0.</span> <span m=\"4845630\">So</span>\
  \ <span m=\"4845960\">with</span> <span m=\"4846170\">probability</span> <span m=\"\
  4846680\">0,</span> <span m=\"4847460\">you</span> <span m=\"4847610\">cross</span>\
  \ <span m=\"4848060\">infinitely</span> <span m=\"4848480\">many</span> <span m=\"\
  4848720\">times,</span> <span m=\"4850330\">which</span> <span m=\"4850500\">proves</span>\
  \ <span m=\"4850880\">the</span> <span m=\"4850950\">claim</span> <span m=\"4851280\"\
  >over</span> <span m=\"4851520\">there</span> <span m=\"4852880\">and</span> <span\
  \ m=\"4853070\">which</span> <span m=\"4853250\">concludes</span> <span m=\"4853700\"\
  >the</span> <span m=\"4853790\">proof</span> <span m=\"4854060\">of</span> <span\
  \ m=\"4854150\">the</span> <span m=\"4854210\">claim</span> <span m=\"4854870\"\
  >that</span> <span m=\"4855090\">the</span> <span m=\"4855170\">martingale</span>\
  \ <span m=\"4855710\">converges</span> <span m=\"4856490\">almost</span> <span m=\"\
  4856880\">surely.</span></p><p><span m=\"4858660\">OK,</span> <span m=\"4858860\"\
  >so</span> <span m=\"4858950\">that</span> <span m=\"4859070\">proves</span> <span\
  \ m=\"4859370\">the</span> <span m=\"4859440\">martingale</span> <span m=\"4859810\"\
  >converge</span> <span m=\"4860280\">theorem.</span> <span m=\"4860660\">So</span>\
  \ <span m=\"4860810\">next</span> <span m=\"4861050\">time,</span> <span m=\"4861290\"\
  >we'll</span> <span m=\"4861530\">combine</span> <span m=\"4862100\">everything</span>\
  \ <span m=\"4862430\">that</span> <span m=\"4862550\">we</span> <span m=\"4862670\"\
  >did</span> <span m=\"4862790\">today</span> <span m=\"4863390\">to</span> <span\
  \ m=\"4863630\">prove</span> <span m=\"4864260\">the</span> <span m=\"4864380\"\
  >three</span> <span m=\"4864650\">main</span> <span m=\"4864920\">theorems</span>\
  \ <span m=\"4865340\">that</span> <span m=\"4865490\">we</span> <span m=\"4865640\"\
  >stated</span> <span m=\"4866060\">last</span> <span m=\"4866300\">time</span> <span\
  \ m=\"4866900\">on</span> <span m=\"4867380\">graph</span> <span m=\"4867680\">limits.</span></p>"
type: course
uid: d72a3b463b189e73cc9080898262bc82

---
None