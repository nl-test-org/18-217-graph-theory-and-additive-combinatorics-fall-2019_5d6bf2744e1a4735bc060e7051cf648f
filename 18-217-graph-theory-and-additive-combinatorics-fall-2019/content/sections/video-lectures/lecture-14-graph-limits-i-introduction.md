---
about_this_resource_text: "<p><strong>Description:</strong> Graph limits provide a\
  \ beautiful analytic framework for studying very large graphs. Professor Zhao explains\
  \ what graph limits are, and their key definitions and theorems (equivalence, limit,\
  \ compactness).\r\n\r\n</p>\r\n<p><strong>Instructor:</strong> Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: P3tGiT72APw
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  title: Video-YouTube-Stream
  type: Video
  uid: f152e79f67da41dc1d50ae4bfe681932
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/P3tGiT72APw/default.jpg
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: eea23019c135d33ce1b114824aa069a7
- id: 3Play-3PlayYouTubeid-MP4
  media_location: P3tGiT72APw
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 84f84105f63d553091664ce90a28d565
- id: P3tGiT72APw.srt
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-14-graph-limits-i-introduction/P3tGiT72APw.srt
  title: 3play caption file
  type: null
  uid: 1977abf785d8ee537f0a76e26226a820
- id: P3tGiT72APw.pdf
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-14-graph-limits-i-introduction/P3tGiT72APw.pdf
  title: 3play pdf file
  type: null
  uid: 2628c6f6d9fde3a6627a1d61fe46ab90
- id: Caption-3Play YouTube id-SRT
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d80af5c66a62ec4ea68196b990f62ecd
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 2b5850405d18671e28ebd8ae506542ed
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec14_300k.mp4
  parent_uid: e4fc7771fc71a9b734509d1e25084236
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7eae1cdf51f7c63dfb2b6ce7b23f2c0a
inline_embed_id: 1653805lecture14graphlimitsiintroduction60197221
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-14-graph-limits-i-introduction
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-14-graph-limits-i-introduction
template_type: Tabbed
title: "Lecture 14: Graph Limits I: Introduction \t"
transcript: <p><span m="18800">YUFEI ZHAO:</span> <span m="18860">So</span> <span
  m="18920">today</span> <span m="19280">we are</span> <span m="19460">going</span>
  <span m="19640">to</span> <span m="19730">start</span> <span m="20030">a</span>
  <span m="20090">new</span> <span m="20360">chapter</span> <span m="21230">on</span>
  <span m="21440">graph</span> <span m="21860">limits.</span> <span m="32020">So</span>
  <span m="32710">graph</span> <span m="33010">limits</span> <span m="33320">is</span>
  <span m="33460">a</span> <span m="33730">relatively</span> <span m="34360">new</span>
  <span m="34630">subject</span> <span m="35320">in</span> <span m="35650">graph</span>
  <span m="35980">theory.</span> <span m="37380">So</span> <span m="37480">as</span>
  <span m="37600">the</span> <span m="37720">name</span> <span m="38050">suggests,</span>
  <span m="38590">we're</span> <span m="38830">looking</span> <span m="39190">at</span>
  <span m="39280">some</span> <span m="39550">kind</span> <span m="39940">of</span>
  <span m="40150">an</span> <span m="40390">analytic</span> <span m="41020">limit</span>
  <span m="41890">of</span> <span m="42280">graphs,</span> <span m="43570">which</span>
  <span m="44140">sounds</span> <span m="44440">kind</span> <span m="44620">of</span>
  <span m="44680">like</span> <span m="44860">a</span> <span m="44920">strange</span>
  <span m="45340">idea</span> <span m="46120">because</span> <span m="46720">you</span>
  <span m="46840">think</span> <span m="47050">of</span> <span m="47140">graphs</span>
  <span m="47530">as</span> <span m="47830">fundamentally</span> <span m="48490">discrete</span>
  <span m="49000">objects.</span></p><p><span m="49990">But</span> <span m="50140">let</span>
  <span m="50260">me</span> <span m="50770">begin</span> <span m="51190">with</span>
  <span m="52260">an</span> <span m="52630">example</span> <span m="53050">to</span>
  <span m="53170">motivate,</span> <span m="54390">at</span> <span m="54460">least</span>
  <span m="54970">pure</span> <span m="55300">mathematical</span> <span m="55900">motivation</span>
  <span m="56500">for</span> <span m="56740">graph</span> <span m="57060">limits.</span>
  <span m="57700">There</span> <span m="57850">are</span> <span m="58900">several</span>
  <span m="59260">other</span> <span m="59590">ways</span> <span m="59980">you</span>
  <span m="60070">can</span> <span m="60190">motivate</span> <span m="60580">graphs</span>
  <span m="60850">limits,</span> <span m="61180">especially</span> <span m="61600">coming</span>
  <span m="61870">from</span> <span m="62110">more</span> <span m="62620">applied</span>
  <span m="62980">perspectives.</span> <span m="63910">But</span> <span m="64000">let</span>
  <span m="64090">me</span> <span m="64209">stick</span> <span m="64569">with</span>
  <span m="64840">the</span> <span m="66040">following</span> <span m="66430">story.</span></p><p><span
  m="69070">So</span> <span m="69220">suppose</span> <span m="69580">you</span> <span
  m="69700">lived</span> <span m="70030">in</span> <span m="70990">ancient</span>
  <span m="71770">Greece</span> <span m="72880">and</span> <span m="73180">you</span>
  <span m="73420">only</span> <span m="73780">knew</span> <span m="74230">rational</span>
  <span m="74830">numbers.</span> <span m="75280">You</span> <span m="75370">didn't</span>
  <span m="75610">know</span> <span m="75730">about</span> <span m="75940">real</span>
  <span m="76210">numbers.</span> <span m="77490">But</span> <span m="77620">you</span>
  <span m="77770">understand</span> <span m="78220">perfectly</span> <span m="78700">rational</span>
  <span m="79150">numbers.</span> <span m="80290">And</span> <span m="80440">we</span>
  <span m="80590">wish</span> <span m="80860">to</span> <span m="81610">maximize.</span>
  <span m="86360">So</span> <span m="86530">we</span> <span m="86650">wish</span>
  <span m="86860">to</span> <span m="87010">then</span> <span m="87220">minimize</span>
  <span m="88750">the</span> <span m="88840">following</span> <span m="89500">polynomial,</span>
  <span m="91630">x</span> <span m="91840">cubed</span> <span m="92620">minus</span>
  <span m="93610">x,</span> <span m="95160">let's</span> <span m="95320">say</span>
  <span m="97270">for</span> <span m="97600">x</span> <span m="97960">between</span>
  <span m="98530">0</span> <span m="99310">and</span> <span m="99640">1.</span></p><p><span
  m="104990">So</span> <span m="106270">you</span> <span m="106360">can</span> <span
  m="106480">do</span> <span m="106600">this.</span> <span m="107090">And</span> <span
  m="107860">suppose</span> <span m="108490">also</span> <span m="108760">the</span>
  <span m="108850">Greeks</span> <span m="109240">knew</span> <span m="109390">calculus</span>
  <span m="109990">and</span> <span m="110140">take</span> <span m="110380">the</span>
  <span m="110470">derivative</span> <span m="111220">and</span> <span m="111685">all</span>
  <span m="111940">of</span> <span m="112150">that.</span> <span m="112510">So</span>
  <span m="112630">you</span> <span m="112750">find</span> <span m="113110">that.</span></p><p><span
  m="114370">You</span> <span m="114760">have</span> <span m="114940">a</span> <span
  m="114970">problem</span> <span m="116120">because</span> <span m="117430">we</span>
  <span m="117610">know--</span> <span m="118870">so</span> <span m="119530">given</span>
  <span m="119860">our</span> <span m="120070">advanced</span> <span m="120490">state</span>
  <span m="120730">of</span> <span m="120820">mathematics,</span> <span m="121540">we</span>
  <span m="121720">know</span> <span m="122350">that</span> <span m="123340">the</span>
  <span m="124120">maximum--</span> <span m="124780">so</span> <span m="125210">the</span>
  <span m="125320">minimizer</span> <span m="127450">is</span> <span m="127720">at</span>
  <span m="128229">x</span> <span m="128530">equals</span> <span m="128889">to</span>
  <span m="129430">1</span> <span m="129729">over</span> <span m="130575">root</span>
  <span m="131030">3.</span> <span m="131470">But</span> <span m="131650">that</span>
  <span m="131800">number</span> <span m="132130">doesn't</span> <span m="132460">exist</span>
  <span m="133000">in</span> <span m="133120">the</span> <span m="133180">real</span>
  <span m="133420">numbers.</span> <span m="135880">So</span> <span m="135960">how</span>
  <span m="136260">might</span> <span m="137390">a</span> <span m="137520">civilization</span>
  <span m="138360">that</span> <span m="138580">only</span> <span m="138900">knew</span>
  <span m="139350">rational</span> <span m="139830">numbers</span> <span m="140840">express</span>
  <span m="141450">this</span> <span m="141660">answer?</span> <span m="143580">They</span>
  <span m="143700">could</span> <span m="143880">say,</span> <span m="144780">the</span>
  <span m="144870">minimum</span> <span m="145640">occurs</span> <span m="147960">not</span>
  <span m="148320">in</span> <span m="148630">Q.</span> <span m="149190">So</span>
  <span m="149460">there's</span> <span m="149670">not</span> <span m="149970">minimized</span>
  <span m="150430">in</span> <span m="150600">Q--</span> <span m="155210">but</span>
  <span m="157400">not</span> <span m="157670">minimized</span> <span m="158120">by</span>
  <span m="158240">a</span> <span m="158270">single</span> <span m="158600">number,</span>
  <span m="158960">but</span> <span m="159140">by</span> <span m="159350">a</span>
  <span m="159380">sequence.</span></p><p><span m="167710">And</span> <span m="167760">this</span>
  <span m="167970">is</span> <span m="168060">a</span> <span m="168090">sequence</span>
  <span m="168660">that</span> <span m="169590">a</span> <span m="169740">more</span>
  <span m="170100">advanced</span> <span m="171060">civilization</span> <span m="172230">would</span>
  <span m="172380">know,</span> <span m="173460">a</span> <span m="173820">sequence</span>
  <span m="174210">that</span> <span m="174300">converges</span> <span m="174900">to</span>
  <span m="175080">1</span> <span m="175320">over</span> <span m="175945">root</span>
  <span m="176210">of</span> <span m="176430">3.</span> <span m="179100">But</span>
  <span m="179270">I</span> <span m="179330">can</span> <span m="179450">give</span>
  <span m="179660">you</span> <span m="179780">this</span> <span m="179900">sequence</span>
  <span m="180380">through</span> <span m="180530">some</span> <span m="180740">other</span>
  <span m="180950">means.</span> <span m="182220">And</span> <span m="182360">this</span>
  <span m="182600">is</span> <span m="184250">one</span> <span m="184490">of</span>
  <span m="184550">the</span> <span m="184640">ways</span> <span m="184910">of</span>
  <span m="185040">defining</span> <span m="185660">the</span> <span m="185780">complete</span>
  <span m="186140">set</span> <span m="186260">of</span> <span m="186320">real</span>
  <span m="186530">numbers,</span> <span m="187190">for</span> <span m="187370">instance.</span>
  <span m="187970">But</span> <span m="188150">you</span> <span m="188270">can</span>
  <span m="188390">define</span> <span m="188780">explicitly</span> <span m="189320">a</span>
  <span m="189380">sequence</span> <span m="189740">of</span> <span m="189830">real</span>
  <span m="190010">numbers</span> <span m="190720">that</span> <span m="190850">converges.</span></p><p><span
  m="193970">But</span> <span m="194090">of</span> <span m="194200">course,</span>
  <span m="194440">this</span> <span m="194590">is</span> <span m="194680">all</span>
  <span m="194800">quite</span> <span m="195040">cumbersome</span> <span m="195610">if</span>
  <span m="195700">you</span> <span m="195820">have</span> <span m="195910">to</span>
  <span m="196060">actually</span> <span m="196390">write</span> <span m="196630">down</span>
  <span m="196870">this</span> <span m="196960">sequence</span> <span m="197380">of</span>
  <span m="197440">real</span> <span m="197620">numbers</span> <span m="197950">to</span>
  <span m="198040">express</span> <span m="198460">this</span> <span m="198550">answer.</span>
  <span m="198970">It</span> <span m="199340">will</span> <span m="199400">be</span>
  <span m="199510">much</span> <span m="199780">better</span> <span m="200050">if</span>
  <span m="200170">we</span> <span m="200290">knew</span> <span m="200440">the</span>
  <span m="200560">real</span> <span m="200770">numbers.</span> <span m="201560">And</span>
  <span m="201580">we</span> <span m="201670">do.</span> <span m="202400">And</span>
  <span m="202600">the</span> <span m="202660">real</span> <span m="202870">numbers,</span>
  <span m="203620">in</span> <span m="203740">some</span> <span m="203950">sense,</span>
  <span m="205300">in</span> <span m="205400">the</span> <span m="205450">very</span>
  <span m="205660">rigorous</span> <span m="206050">sense,</span> <span m="206350">is</span>
  <span m="206490">a</span> <span m="206530">completion</span> <span m="207610">of</span>
  <span m="208330">the</span> <span m="208420">rational</span> <span m="208870">numbers.</span></p><p><span
  m="213730">That's</span> <span m="214370">the</span> <span m="214460">story</span>
  <span m="215150">that</span> <span m="215930">we're</span> <span m="216050">all</span>
  <span m="216170">familiar</span> <span m="216590">with.</span> <span m="218120">But</span>
  <span m="218240">now</span> <span m="218390">let's</span> <span m="218780">think</span>
  <span m="219050">about</span> <span m="219800">graphs</span> <span m="220820">which</span>
  <span m="221090">are</span> <span m="221540">some</span> <span m="221720">kind</span>
  <span m="221990">of</span> <span m="222050">a</span> <span m="222110">discrete</span>
  <span m="222590">set</span> <span m="222800">of</span> <span m="222920">objects,</span>
  <span m="223760">akin</span> <span m="224180">to</span> <span m="224390">the</span>
  <span m="224480">rational</span> <span m="224930">numbers.</span> <span m="227050">And</span>
  <span m="227180">the</span> <span m="227270">story</span> <span m="227560">now</span>
  <span m="227830">is,</span> <span m="228530">among</span> <span m="228860">graphs,</span>
  <span m="231170">suppose</span> <span m="231650">I</span> <span m="231800">have</span>
  <span m="232220">a</span> <span m="233030">fixed</span> <span m="235960">p</span>
  <span m="236590">between</span> <span m="236950">0</span> <span m="237250">and</span>
  <span m="237370">1.</span> <span m="238250">And</span> <span m="238270">the</span>
  <span m="238360">problem</span> <span m="238690">now</span> <span m="238960">is</span>
  <span m="239080">to</span> <span m="239200">minimize</span> <span m="242140">the</span>
  <span m="242740">4-cycle</span> <span m="243610">density</span> <span m="248160">among</span>
  <span m="250340">graphs</span> <span m="253410">with</span> <span m="253650">density,</span>
  <span m="254760">with</span> <span m="255000">edge</span> <span m="255240">density</span>
  <span m="255630">p.</span></p><p><span m="264750">So</span> <span m="264770">this</span>
  <span m="264950">is</span> <span m="265040">some</span> <span m="265640">kind</span>
  <span m="265970">of</span> <span m="266390">optimization</span> <span m="267080">problem.</span>
  <span m="267450">So</span> <span m="267500">I</span> <span m="267620">don't</span>
  <span m="267800">restrict</span> <span m="268250">the</span> <span m="268310">number</span>
  <span m="268730">of</span> <span m="268850">vertices.</span> <span m="269360">You</span>
  <span m="269450">can</span> <span m="269600">use</span> <span m="269780">as</span>
  <span m="269900">many</span> <span m="270140">vertices</span> <span m="270860">as</span>
  <span m="271040">you</span> <span m="271160">like.</span> <span m="271730">And</span>
  <span m="271910">I</span> <span m="272040">would</span> <span m="272150">like</span>
  <span m="272330">to</span> <span m="272420">minimize</span> <span m="272990">the</span>
  <span m="273110">4-cycle</span> <span m="273830">density.</span></p><p><span m="276004">Now,</span>
  <span m="277120">we</span> <span m="277540">saw</span> <span m="278470">a</span>
  <span m="278950">few</span> <span m="279160">lectures</span> <span m="279550">ago</span>
  <span m="280180">this</span> <span m="280360">inequality</span> <span m="281500">that</span>
  <span m="281710">tells</span> <span m="282040">us</span> <span m="282910">that--</span>
  <span m="284590">so</span> <span m="284730">we</span> <span m="284850">saw</span>
  <span m="286640">a</span> <span m="286740">few</span> <span m="286830">lectures</span>
  <span m="287430">ago</span> <span m="288270">that</span> <span m="288690">this</span>
  <span m="289830">density</span> <span m="290115">is</span> <span m="290400">always</span>
  <span m="290730">at</span> <span m="290820">least</span> <span m="291500">p</span>
  <span m="291680">to</span> <span m="291810">the</span> <span m="291950">fourth.</span>
  <span m="293320">So</span> <span m="293380">in</span> <span m="293500">the</span>
  <span m="293560">lecture</span> <span m="293920">on</span> <span m="294040">quasirandomness,</span>
  <span m="295290">so</span> <span m="295420">we</span> <span m="295570">saw</span>
  <span m="295780">this</span> <span m="296140">inequality.</span> <span m="297570">And</span>
  <span m="297700">we</span> <span m="297850">also</span> <span m="298150">saw</span>
  <span m="298900">that</span> <span m="300400">this</span> <span m="301150">minimum</span>
  <span m="302140">is</span> <span m="302560">approached</span> <span m="306690">by</span>
  <span m="307020">a</span> <span m="307080">sequence</span> <span m="309540">of</span>
  <span m="310860">quasirandom</span> <span m="311490">graphs.</span></p><p><span
  m="320270">And</span> <span m="320360">in</span> <span m="320400">some</span> <span
  m="320540">sense,</span> <span m="320770">that--</span> <span m="320990">so</span>
  <span m="321200">the</span> <span m="321320">answer</span> <span m="321800">is</span>
  <span m="323130">p</span> <span m="323660">to</span> <span m="323780">the</span>
  <span m="323870">fourth.</span> <span m="324260">And</span> <span m="324410">there's</span>
  <span m="324620">not</span> <span m="324890">a</span> <span m="324920">specific</span>
  <span m="325250">graph.</span> <span m="325820">There's</span> <span m="325970">no</span>
  <span m="326150">one</span> <span m="326420">graph</span> <span m="326720">that</span>
  <span m="326840">minimizes.</span> <span m="327830">This</span> <span m="328010">4-cycle</span>
  <span m="328550">density</span> <span m="329210">is</span> <span m="329360">minimized</span>
  <span m="329900">by</span> <span m="330050">a</span> <span m="330110">sequence.</span></p><p><span
  m="331700">And</span> <span m="331820">just</span> <span m="332060">like</span>
  <span m="332720">in</span> <span m="332840">the</span> <span m="332900">story</span>
  <span m="333350">with the</span> <span m="333620">rational</span> <span m="334070">numbers</span>
  <span m="334430">and</span> <span m="334520">the</span> <span m="334610">real</span>
  <span m="334850">numbers,</span> <span m="335630">it</span> <span m="335750">would</span>
  <span m="335900">be</span> <span m="336020">nice</span> <span m="336920">if</span>
  <span m="337160">we</span> <span m="337340">didn't</span> <span m="337550">have</span>
  <span m="337820">to</span> <span m="338660">write</span> <span m="339020">out</span>
  <span m="339170">the</span> <span m="339290">answer</span> <span m="339620">in</span>
  <span m="339710">this</span> <span m="339860">cumbersome,</span> <span m="340940">sequential</span>
  <span m="341540">way,</span> <span m="342050">but</span> <span m="342200">just</span>
  <span m="342380">have</span> <span m="342620">a</span> <span m="342650">single</span>
  <span m="343670">graphical-like</span> <span m="344540">object</span> <span m="345560">that</span>
  <span m="345770">depicts</span> <span m="346280">what</span> <span m="346460">the</span>
  <span m="346550">minimizer</span> <span m="347110">should</span> <span m="347330">be.</span>
  <span m="348900">And</span> <span m="349050">graph</span> <span m="349380">limits</span>
  <span m="349770">provides</span> <span m="350220">a</span> <span m="350280">language</span>
  <span m="350730">for</span> <span m="350940">us</span> <span m="351090">to</span>
  <span m="351180">do</span> <span m="351330">this.</span> <span m="354640">So</span>
  <span m="357480">one</span> <span m="357750">of</span> <span m="357810">the</span>
  <span m="357930">goals</span> <span m="358290">of</span> <span m="358410">the</span>
  <span m="358440">graph</span> <span m="358740">limits--</span> <span m="361870">this</span>
  <span m="362080">gives</span> <span m="362350">us</span> <span m="362500">a</span>
  <span m="362560">single</span> <span m="365280">object</span> <span m="368700">for</span>
  <span m="369440">this</span> <span m="369730">minimizer</span> <span m="371890">instead</span>
  <span m="372250">of</span> <span m="372400">taking</span> <span m="372820">a</span>
  <span m="372850">sequence.</span></p><p><span m="375200">So</span> <span m="375520">roughly</span>
  <span m="375890">that</span> <span m="376090">is</span> <span m="377980">the</span>
  <span m="378130">idea</span> <span m="378460">that</span> <span m="378580">you</span>
  <span m="378700">have</span> <span m="379090">a</span> <span m="379150">sequence</span>
  <span m="379600">of</span> <span m="379690">graphs.</span> <span m="380050">And</span>
  <span m="380290">I</span> <span m="380340">would</span> <span m="380440">like</span>
  <span m="380680">some</span> <span m="381100">analytic</span> <span m="381610">object</span>
  <span m="382750">to</span> <span m="382930">capture</span> <span m="383470">the</span>
  <span m="383590">behavior</span> <span m="384190">of</span> <span m="384370">the</span>
  <span m="384490">sequence</span> <span m="385180">in</span> <span m="385300">the</span>
  <span m="385390">limit.</span> <span m="387190">And</span> <span m="387670">these</span>
  <span m="387940">graph</span> <span m="388240">limits</span> <span m="388630">can</span>
  <span m="388840">be</span> <span m="389080">written</span> <span m="389410">actually</span>
  <span m="389680">in</span> <span m="389740">a</span> <span m="389830">fairly</span>
  <span m="390670">concrete</span> <span m="391240">form.</span></p><p><span m="391955">And</span>
  <span m="392220">so</span> <span m="392350">now</span> <span m="392530">let</span>
  <span m="392650">me</span> <span m="392770">begin</span> <span m="393070">with</span>
  <span m="393250">some</span> <span m="393640">definitions.</span> <span m="397160">The</span>
  <span m="397180">main</span> <span m="397600">object</span> <span m="398320">that</span>
  <span m="398440">we'll</span> <span m="398590">look</span> <span m="398830">at</span>
  <span m="399250">is</span> <span m="399880">something</span> <span m="400270">called</span>
  <span m="400660">a</span> <span m="400750">graphon.</span> <span m="405990">So</span>
  <span m="406170">it</span> <span m="406520">merges</span> <span m="407090">the</span>
  <span m="407150">two</span> <span m="407360">words</span> <span m="407690">graph,</span>
  <span m="408230">function.</span> <span m="413273">A</span> <span m="413770">graphon</span>
  <span m="414890">is</span> <span m="415040">by</span> <span m="415190">definition</span>
  <span m="416900">a</span> <span m="417260">symmetric,</span> <span m="420780">measurable</span>
  <span m="421260">function,</span> <span m="427520">often</span> <span m="427790">denoted</span>
  <span m="428210">by</span> <span m="428330">the</span> <span m="428450">letter</span>
  <span m="428750">W</span> <span m="431060">from</span> <span m="431420">the</span>
  <span m="431510">unit</span> <span m="431800">squared</span> <span m="432560">to</span>
  <span m="433890">the</span> <span m="433960">0,</span> <span m="434260">1</span>
  <span m="434630">interval.</span> <span m="436240">And</span> <span m="436400">here</span>
  <span m="437030">being</span> <span m="437270">symmetric</span> <span m="438830">means</span>
  <span m="439730">that</span> <span m="441170">if</span> <span m="441320">you</span>
  <span m="441500">exchange</span> <span m="442190">the</span> <span m="442280">two</span>
  <span m="443540">argument</span> <span m="444050">variables,</span> <span m="444980">this</span>
  <span m="445160">function</span> <span m="445580">remains</span> <span m="446060">the</span>
  <span m="446180">same.</span></p><p><span m="450120">So</span> <span m="450410">that's</span>
  <span m="450590">it.</span> <span m="450830">So</span> <span m="450950">that's</span>
  <span m="451140">the</span> <span m="451220">definition</span> <span m="451730">of</span>
  <span m="451850">a</span> <span m="451880">graphon.</span> <span m="452750">And</span>
  <span m="452900">these</span> <span m="453140">are</span> <span m="453200">the</span>
  <span m="453320">objects</span> <span m="453830">that</span> <span m="453950">will</span>
  <span m="454070">play</span> <span m="454370">the</span> <span m="454490">role</span>
  <span m="454790">of</span> <span m="454940">limits</span> <span m="455450">for</span>
  <span m="455810">sequences</span> <span m="456410">of</span> <span m="456500">graphs.</span>
  <span m="457400">And</span> <span m="457550">I</span> <span m="457610">will</span>
  <span m="457700">give</span> <span m="457880">you</span> <span m="457970">lots</span>
  <span m="458180">of</span> <span m="458270">examples</span> <span m="458810">in</span>
  <span m="458880">a</span> <span m="458960">second.</span> <span m="460430">So</span>
  <span m="460780">that's</span> <span m="461000">the</span> <span m="461060">definition.</span></p><p><span
  m="464710">This</span> <span m="464950">is</span> <span m="465070">the</span> <span
  m="465160">form</span> <span m="465550">of</span> <span m="465640">the</span> <span
  m="465730">graphons</span> <span m="466240">that</span> <span m="466540">we'll</span>
  <span m="466840">be</span> <span m="467020">looking</span> <span m="467350">at</span>
  <span m="467440">mostly.</span> <span m="468060">But</span> <span m="468190">just</span>
  <span m="468760">to</span> <span m="468970">mention</span> <span m="469390">a</span>
  <span m="469480">few</span> <span m="470830">remarks,</span> <span m="471730">that</span>
  <span m="472060">the</span> <span m="472810">domain</span> <span m="475540">can</span>
  <span m="475750">be</span> <span m="476340">instead</span> <span m="477790">any</span>
  <span m="478900">product</span> <span m="479440">of</span> <span m="480550">any</span>
  <span m="480760">square</span> <span m="481120">of</span> <span m="481300">a</span>
  <span m="481450">probability</span> <span m="482380">measure</span> <span m="482710">space--</span>
  <span m="490300">so</span> <span m="490350">instead</span> <span m="490650">of</span>
  <span m="490710">taking</span> <span m="490980">the</span> <span m="491070">0,</span>
  <span m="491170">1</span> <span m="491460">interval,</span> <span m="492240">I</span>
  <span m="492330">could</span> <span m="492480">also</span> <span m="492690">use</span>
  <span m="492930">any</span> <span m="493140">probability</span> <span m="493650">measure</span>
  <span m="493920">space.</span> <span m="494560">So</span> <span m="494700">it's</span>
  <span m="495150">only</span> <span m="495420">slightly</span> <span m="495960">more</span>
  <span m="496170">general.</span> <span m="496590">So</span> <span m="496710">there</span>
  <span m="496860">are</span> <span m="496920">some</span> <span m="497940">general</span>
  <span m="498360">theorems</span> <span m="498740">in</span> <span m="498810">measure</span>
  <span m="499080">theory</span> <span m="499380">that</span> <span m="499530">tells</span>
  <span m="499830">us</span> <span m="500040">that</span> <span m="501000">most</span>
  <span m="501930">probability</span> <span m="502440">measure</span> <span m="502680">spaces,</span>
  <span m="503130">if</span> <span m="503220">they're</span> <span m="503370">nice</span>
  <span m="503640">enough,</span> <span m="504240">they</span> <span m="504420">are</span>
  <span m="504510">in</span> <span m="504600">some</span> <span m="504840">sense</span>
  <span m="505380">equivalent</span> <span m="505920">or</span> <span m="506010">can</span>
  <span m="506160">be</span> <span m="506250">captured</span> <span m="507030">by</span>
  <span m="507330">this</span> <span m="507690">interval.</span></p><p><span m="508480">So</span>
  <span m="508650">I</span> <span m="509400">don't</span> <span m="509610">want</span>
  <span m="509820">you to</span> <span m="510030">worry</span> <span m="510330">too</span>
  <span m="510540">much</span> <span m="510780">about</span> <span m="511050">all</span>
  <span m="511200">the</span> <span m="511710">measure</span> <span m="512190">where</span>
  <span m="512300">there</span> <span m="512410">are</span> <span m="512520">technicalities.</span>
  <span m="513299">I</span> <span m="513360">think</span> <span m="513510">they are</span>
  <span m="513659">not</span> <span m="514320">so</span> <span m="514590">important</span>
  <span m="515100">for</span> <span m="515610">the</span> <span m="515730">discussion</span>
  <span m="516210">of</span> <span m="516299">graph</span> <span m="516570">limits.</span>
  <span m="517140">But</span> <span m="517919">there</span> <span m="518100">are</span>
  <span m="518159">some</span> <span m="520070">subtle</span> <span m="520429">issues</span>
  <span m="520789">like</span> <span m="520940">that</span> <span m="522409">just</span>
  <span m="523010">lurking</span> <span m="523309">behind.</span></p><p><span m="523620">But</span>
  <span m="523720">I</span> <span m="523880">just</span> <span m="524090">don't</span>
  <span m="524240">want</span> <span m="524420">to</span> <span m="524900">really</span>
  <span m="525080">talk</span> <span m="525320">about</span> <span m="525540">them.</span>
  <span m="526170">So</span> <span m="526370">for</span> <span m="526490">the</span>
  <span m="526580">most</span> <span m="526790">part,</span> <span m="527030">we'll</span>
  <span m="527200">be</span> <span m="527300">looking</span> <span m="527600">at</span>
  <span m="527660">graphons</span> <span m="528090">of</span> <span m="528200">this</span>
  <span m="528410">one.</span> <span m="529280">And</span> <span m="529490">also</span>
  <span m="529970">the--</span> <span m="531230">so</span> <span m="531600">instead</span>
  <span m="531800">of</span> <span m="531860">the</span> <span m="531950">domain,</span>
  <span m="532440">so</span> <span m="532550">the</span> <span m="534390">values--</span>
  <span m="537060">so</span> <span m="537230">instead</span> <span m="537650">of</span>
  <span m="542110">0,</span> <span m="542450">1</span> <span m="542610">interval,</span>
  <span m="544260">you</span> <span m="544380">could</span> <span m="544590">also</span>
  <span m="544830">take</span> <span m="545040">a</span> <span m="545070">more</span>
  <span m="545280">general</span> <span m="547440">space,</span> <span m="547980">for</span>
  <span m="548190">example,</span> <span m="548610">the</span> <span m="548730">real</span>
  <span m="549000">numbers</span> <span m="549750">or</span> <span m="549870">even</span>
  <span m="550080">the</span> <span m="550170">complex</span> <span m="550740">numbers.</span></p><p><span
  m="552000">I'm</span> <span m="552150">going</span> <span m="552330">to</span> <span
  m="552420">use</span> <span m="552690">the</span> <span m="552780">word</span> <span
  m="553130">graphon</span> <span m="553680">to</span> <span m="554600">reserve</span>
  <span m="555030">this</span> <span m="555210">word</span> <span m="555750">for</span>
  <span m="556110">when</span> <span m="556980">the</span> <span m="557100">values</span>
  <span m="557820">are</span> <span m="557970">between</span> <span m="558390">0</span>
  <span m="558720">and</span> <span m="558810">1.</span> <span m="561220">And</span>
  <span m="561600">if</span> <span m="561810">it's</span> <span m="562260">in</span>
  <span m="562500">R,</span> <span m="563280">let</span> <span m="563400">me</span>
  <span m="563520">call</span> <span m="563730">this</span> <span m="564000">just</span>
  <span m="564240">a</span> <span m="564310">kernel,</span> <span m="565950">although</span>
  <span m="566340">that</span> <span m="566970">will</span> <span m="567090">not</span>
  <span m="567270">come</span> <span m="567510">up</span> <span m="567690">so</span>
  <span m="567900">much.</span> <span m="569100">So</span> <span m="569310">when</span>
  <span m="569490">I</span> <span m="569550">say</span> <span m="569710">graphon,</span>
  <span m="570390">I</span> <span m="570480">just</span> <span m="570720">mean</span>
  <span m="571320">the</span> <span m="571410">values</span> <span m="571740">between</span>
  <span m="572070">0</span> <span m="572310">and</span> <span m="572400">1.</span>
  <span m="572850">Although</span> <span m="573600">if</span> <span m="573720">you</span>
  <span m="573780">do</span> <span m="574260">look</span> <span m="574500">up</span>
  <span m="574620">papers</span> <span m="575280">in</span> <span m="575400">the</span>
  <span m="575460">literature,</span> <span m="576450">sometimes</span> <span m="577020">they</span>
  <span m="577380">don't</span> <span m="577620">use</span> <span m="577800">these</span>
  <span m="578040">words</span> <span m="578340">so</span> <span m="578550">consistently.</span>
  <span m="579180">So</span> <span m="579420">be</span> <span m="579600">careful</span>
  <span m="580440">what</span> <span m="580620">they</span> <span m="580770">mean</span>
  <span m="580950">by</span> <span m="581160">a</span> <span m="581220">graphon.</span></p><p><span
  m="584850">So</span> <span m="584970">that's</span> <span m="585150">the</span>
  <span m="585240">definition.</span> <span m="585720">But</span> <span m="585810">now</span>
  <span m="586260">let</span> <span m="586380">me</span> <span m="586530">give</span>
  <span m="586680">you</span> <span m="586830">some</span> <span m="587130">examples</span>
  <span m="587555">on</span> <span m="587980">how</span> <span m="588120">do</span>
  <span m="588210">we</span> <span m="588360">think</span> <span m="588660">of</span>
  <span m="589140">graphons</span> <span m="589770">and</span> <span m="589920">what</span>
  <span m="590070">do</span> <span m="590160">they</span> <span m="590310">have</span>
  <span m="590460">to</span> <span m="590550">do</span> <span m="590730">with</span>
  <span m="590940">graphs.</span> <span m="592780">So</span> <span m="592860">if</span>
  <span m="592980">we</span> <span m="593070">start</span> <span m="593460">with</span>
  <span m="593730">a</span> <span m="593880">graph,</span> <span m="596220">I</span>
  <span m="596280">want</span> <span m="596460">to</span> <span m="596520">show</span>
  <span m="596700">you</span> <span m="596820">how</span> <span m="596970">to</span>
  <span m="597090">turn</span> <span m="597390">it</span> <span m="597810">into</span>
  <span m="598230">a</span> <span m="598380">graphon.</span></p><p><span m="603390">So</span>
  <span m="603410">let's</span> <span m="603590">start</span> <span m="603950">with</span>
  <span m="604190">this</span> <span m="604370">graph,</span> <span m="604880">which</span>
  <span m="605540">you've</span> <span m="605720">seen</span> <span m="606080">before.</span>
  <span m="606590">This</span> <span m="606800">is</span> <span m="606920">the</span>
  <span m="607070">half</span> <span m="607400">graph.</span> <span m="616480">So</span>
  <span m="616660">from</span> <span m="616870">this</span> <span m="617080">graph,</span>
  <span m="617920">I</span> <span m="618070">can</span> <span m="618910">label</span>
  <span m="619240">the</span> <span m="619360">vertices</span> <span m="622650">and</span>
  <span m="622890">form</span> <span m="623610">an</span> <span m="623850">adjacency</span>
  <span m="624420">matrix</span> <span m="632960">of</span> <span m="633140">this</span>
  <span m="633500">graph,</span> <span m="635330">where</span> <span m="635570">I</span>
  <span m="636380">label</span> <span m="636710">the</span> <span m="636830">rows</span>
  <span m="637130">and</span> <span m="637250">columns</span> <span m="637820">by</span>
  <span m="638090">the</span> <span m="638210">vertices</span> <span m="641940">and</span>
  <span m="642210">put</span> <span m="642480">in</span> <span m="643020">zeros</span>
  <span m="643440">and</span> <span m="643530">ones</span> <span m="644220">according</span>
  <span m="644670">to</span> <span m="646080">whether</span> <span m="647430">the</span>
  <span m="647820">edges</span> <span m="648300">are</span> <span m="648540">adjacent.</span>
  <span m="653100">So</span> <span m="653180">that's</span> <span m="653420">the</span>
  <span m="653690">adjacency</span> <span m="654440">matrix.</span></p><p><span m="658230">And</span>
  <span m="658320">now</span> <span m="658980">I</span> <span m="659070">want</span>
  <span m="659250">you</span> <span m="659340">to</span> <span m="659490">view</span>
  <span m="660360">this</span> <span m="660810">matrix</span> <span m="661650">as</span>
  <span m="662070">a</span> <span m="662490">black</span> <span m="662880">and</span>
  <span m="662970">white</span> <span m="663240">picture.</span> <span m="663900">So</span>
  <span m="664050">think</span> <span m="664260">one</span> <span m="664410">of</span>
  <span m="664470">these</span> <span m="664650">pixelated</span> <span m="665400">images,</span>
  <span m="666540">where</span> <span m="667230">I</span> <span m="667410">turn</span>
  <span m="667950">the</span> <span m="669990">ones</span> <span m="670620">into</span>
  <span m="671700">black</span> <span m="672090">boxes.</span> <span m="681100">Of</span>
  <span m="681220">course,</span> <span m="681730">on</span> <span m="681850">the</span>
  <span m="681940">blackboard,</span> <span m="682510">black</span> <span m="682840">is</span>
  <span m="682990">white</span> <span m="683290">and</span> <span m="683380">white</span>
  <span m="683620">is</span> <span m="683790">black.</span> <span m="686310">So</span>
  <span m="686520">I</span> <span m="686610">turn</span> <span m="687480">the</span>
  <span m="687660">ones</span> <span m="688090">into</span> <span m="688260">black</span>
  <span m="688590">boxes.</span> <span m="689370">And</span> <span m="690090">I</span>
  <span m="690210">leave</span> <span m="690750">the</span> <span m="690840">zeros</span>
  <span m="691320">as</span> <span m="691500">empty</span> <span m="692540">white</span>
  <span m="692870">space.</span></p><p><span m="694750">So</span> <span m="694870">I</span>
  <span m="694930">get</span> <span m="695080">this</span> <span m="695230">image.</span>
  <span m="696790">And</span> <span m="697050">I</span> <span m="697180">think</span>
  <span m="697420">of</span> <span m="697510">this</span> <span m="697690">image</span>
  <span m="699140">as</span> <span m="699620">a</span> <span m="699710">function.</span>
  <span m="701670">And</span> <span m="701800">this</span> <span m="701950">is</span>
  <span m="702070">the</span> <span m="702130">function</span> <span m="707950">going</span>
  <span m="708280">from</span> <span m="708880">0,</span> <span m="709180">1,</span>
  <span m="709420">squared</span> <span m="711040">to</span> <span m="712950">0,</span>
  <span m="713190">1,</span> <span m="713400">interval,</span> <span m="714210">taking</span>
  <span m="714570">only</span> <span m="714870">0</span> <span m="715260">and</span>
  <span m="715380">1</span> <span m="715650">values.</span> <span m="725820">So</span>
  <span m="725840">that's</span> <span m="726020">a</span> <span m="726080">function</span>
  <span m="726600">on</span> <span m="727060">the</span> <span m="727450">square.</span></p><p><span
  m="730120">But</span> <span m="730240">now,</span> <span m="731420">so</span> <span
  m="731560">this</span> <span m="731740">is</span> <span m="731830">a</span> <span
  m="731860">single</span> <span m="732250">graph.</span> <span m="732770">So</span>
  <span m="732790">for</span> <span m="732910">any</span> <span m="733120">specific</span>
  <span m="733600">graph,</span> <span m="733900">I</span> <span m="733960">can</span>
  <span m="734110">turn</span> <span m="734380">it</span> <span m="734530">into</span>
  <span m="735160">a</span> <span m="735220">graphon</span> <span m="735880">like</span>
  <span m="736060">this.</span> <span m="736950">But</span> <span m="737050">now</span>
  <span m="737230">imagine you</span> <span m="737620">have a</span> <span m="737860">sequence</span>
  <span m="738370">of</span> <span m="738460">graphs.</span> <span m="738880">And</span>
  <span m="739210">in</span> <span m="739270">particular,</span> <span m="739990">consider</span>
  <span m="740440">a</span> <span m="740530">sequence</span> <span m="741130">of</span>
  <span m="741250">half</span> <span m="741550">graphs.</span></p><p><span m="748480">So</span>
  <span m="748690">here</span> <span m="749350">is</span> <span m="750640">H3.</span>
  <span m="751520">So</span> <span m="751780">Hn</span> <span m="752320">is</span>
  <span m="752470">the</span> <span m="752560">general</span> <span m="753010">half</span>
  <span m="753250">graph.</span> <span m="754540">And</span> <span m="754780">you</span>
  <span m="754930">can</span> <span m="755110">imagine</span> <span m="755860">that,</span>
  <span m="756100">as</span> <span m="756330">n</span> <span m="756590">gets</span>
  <span m="757060">large,</span> <span m="758320">this</span> <span m="758500">picture</span>
  <span m="759910">looks</span> <span m="760300">like--</span> <span m="764280">instead</span>
  <span m="764640">of</span> <span m="764760">the</span> <span m="764850">staircase</span>
  <span m="765660">you</span> <span m="765810">just</span> <span m="766080">have</span>
  <span m="766740">a</span> <span m="766800">straight</span> <span m="767190">line</span>
  <span m="767700">connecting</span> <span m="768590">the</span> <span m="768690">two</span>
  <span m="768900">ends.</span> <span m="780800">And</span> <span m="780950">indeed,</span>
  <span m="782090">this</span> <span m="782690">function</span> <span m="783140">here,</span>
  <span m="783560">this</span> <span m="783770">graphon,</span> <span m="784510">is</span>
  <span m="784700">the</span> <span m="784790">limit</span> <span m="788100">of</span>
  <span m="789600">the</span> <span m="789690">sequence</span> <span m="790200">of</span>
  <span m="790290">half</span> <span m="790560">graphs</span> <span m="791400">as</span>
  <span m="791790">n</span> <span m="792150">goes</span> <span m="792450">to</span>
  <span m="792600">infinity.</span></p><p><span m="796730">So</span> <span m="796780">one</span>
  <span m="796990">way</span> <span m="797140">you</span> <span m="797230">can</span>
  <span m="797380">think</span> <span m="797620">about</span> <span m="797890">graphons</span>
  <span m="798790">is</span> <span m="799240">you</span> <span m="799360">have</span>
  <span m="799480">a</span> <span m="799510">sequence</span> <span m="799960">of</span>
  <span m="800050">graphs.</span> <span m="800710">You</span> <span m="800830">look</span>
  <span m="801040">at</span> <span m="801220">their</span> <span m="802510">adjacency</span>
  <span m="802990">matrix.</span> <span m="803440">You</span> <span m="803560">view</span>
  <span m="803800">it</span> <span m="803920">as</span> <span m="804040">a</span>
  <span m="804100">picture,</span> <span m="804680">a</span> <span m="804760">pixelated</span>
  <span m="805480">image,</span> <span m="805960">black</span> <span m="806230">and</span>
  <span m="806350">white</span> <span m="806590">according</span> <span m="806920">to</span>
  <span m="807040">the</span> <span m="807100">zeros</span> <span m="807430">and</span>
  <span m="807520">ones</span> <span m="807790">in</span> <span m="807880">its</span>
  <span m="807970">adjacency</span> <span m="808500">matrix.</span></p><p><span m="810160">And</span>
  <span m="810970">as</span> <span m="811220">you</span> <span m="812470">take</span>
  <span m="812710">a</span> <span m="812770">sequence,</span> <span m="813760">you</span>
  <span m="813970">make</span> <span m="814210">your</span> <span m="814330">eyes</span>
  <span m="814600">a</span> <span m="814630">little</span> <span m="814810">bit</span>
  <span m="815140">blurry.</span> <span m="815750">And</span> <span m="815770">then</span>
  <span m="815920">you</span> <span m="816190">think</span> <span m="816430">about</span>
  <span m="816680">what</span> <span m="817060">the</span> <span m="817150">sequence</span>
  <span m="817660">of</span> <span m="817840">images</span> <span m="818260">converges</span>
  <span m="818890">to.</span> <span m="820120">So</span> <span m="820600">the</span>
  <span m="820720">resulting</span> <span m="821830">limit</span> <span m="822670">is</span>
  <span m="823060">the</span> <span m="823690">limit</span> <span m="824110">of</span>
  <span m="824260">this</span> <span m="824740">sequence</span> <span m="825400">of</span>
  <span m="825760">graphs.</span> <span m="827120">So</span> <span m="827740">that's</span>
  <span m="827980">an</span> <span m="828070">informal</span> <span m="828670">explanation.</span>
  <span m="830440">So</span> <span m="830620">I</span> <span m="830740">haven't</span>
  <span m="831040">done</span> <span m="831250">anything</span> <span m="831580">precisely.</span></p><p><span
  m="832600">And</span> <span m="832690">in</span> <span m="832780">fact,</span> <span
  m="833020">one</span> <span m="833200">needs</span> <span m="833380">to</span> <span
  m="833470">be</span> <span m="833590">somewhat</span> <span m="833950">careful</span>
  <span m="834520">with</span> <span m="835030">this</span> <span m="835270">depiction</span>
  <span m="836170">because</span> <span m="836500">let</span> <span m="836620">me</span>
  <span m="836710">give</span> <span m="836920">you</span> <span m="837160">another</span>
  <span m="837640">example.</span> <span m="841150">Suppose</span> <span m="841570">I</span>
  <span m="841660">have</span> <span m="841960">a</span> <span m="842020">sequence</span>
  <span m="844510">of</span> <span m="845230">random</span> <span m="845890">or</span>
  <span m="846040">quasirandom</span> <span m="849300">graphs</span> <span m="856080">with</span>
  <span m="856350">edge</span> <span m="856590">density</span> <span m="858580">1/2.</span>
  <span m="865270">So</span> <span m="865420">what</span> <span m="865600">does</span>
  <span m="865780">this</span> <span m="865990">look</span> <span m="866200">like?</span></p><p><span
  m="868230">And</span> <span m="868360">I</span> <span m="868420">have</span> <span
  m="868690">this</span> <span m="868870">picture</span> <span m="869200">here.</span>
  <span m="869860">And</span> <span m="870670">I</span> <span m="870730">have</span>
  <span m="871090">a</span> <span m="871150">lot</span> <span m="871450">of--</span>
  <span m="874280">so</span> <span m="874550">I</span> <span m="874640">have</span>
  <span m="874850">a</span> <span m="874910">lot</span> <span m="875180">of--</span>
  <span m="877990">one-half</span> <span m="878890">of</span> <span m="879010">the</span>
  <span m="879430">pixels</span> <span m="880000">are</span> <span m="880090">black.</span>
  <span m="880810">And</span> <span m="880960">the</span> <span m="881080">other</span>
  <span m="881260">half</span> <span m="881590">pixels</span> <span m="882070">are</span>
  <span m="882190">white.</span> <span m="884010">And</span> <span m="884280">you</span>
  <span m="884310">can</span> <span m="884540">think,</span> <span m="884850">from</span>
  <span m="885090">far</span> <span m="885390">away,</span> <span m="885930">I</span>
  <span m="886020">cannot</span> <span m="886320">distinguish</span> <span m="886950">necessarily</span>
  <span m="887490">which</span> <span m="887730">ones</span> <span m="887970">are</span>
  <span m="888030">black and</span> <span m="888360">which</span> <span m="888570">ones</span>
  <span m="888800">are</span> <span m="888870">white.</span></p><p><span m="889610">And</span>
  <span m="889740">in</span> <span m="889910">the</span> <span m="890010">limit,</span>
  <span m="890650">it</span> <span m="890750">looks</span> <span m="890880">like</span>
  <span m="891030">a</span> <span m="891120">grayscale</span> <span m="891840">image,</span>
  <span m="892470">with</span> <span m="892650">a</span> <span m="892740">grayscale</span>
  <span m="893880">being</span> <span m="894990">one-half</span> <span m="895620">density.</span>
  <span m="897030">And</span> <span m="897150">indeed,</span> <span m="899120">it</span>
  <span m="899180">converges</span> <span m="899840">to</span> <span m="899990">the</span>
  <span m="900080">constant</span> <span m="900590">function,</span> <span m="901140">1/2.</span>
  <span m="910760">So</span> <span m="911000">the</span> <span m="911270">limits</span>
  <span m="911720">represented</span> <span m="913100">by</span> <span m="914000">this</span>
  <span m="914210">problem</span> <span m="914510">up here</span> <span m="915190">is</span>
  <span m="915380">the</span> <span m="915470">constant</span> <span m="915970">graphon</span>
  <span m="916640">with</span> <span m="916850">the</span> <span m="917180">constant</span>
  <span m="917630">value</span> <span m="917960">p.</span></p><p><span m="920120">But</span>
  <span m="920240">now</span> <span m="920360">let</span> <span m="920510">me</span>
  <span m="920600">give</span> <span m="920810">you</span> <span m="921020">a</span>
  <span m="921710">different</span> <span m="922100">example.</span> <span m="925350">Consider</span>
  <span m="925670">a</span> <span m="925790">checkerboard.</span> <span m="936340">So</span>
  <span m="936520">here is</span> <span m="936910">a</span> <span m="937480">checkerboard,</span>
  <span m="946310">where</span> <span m="947966">I</span> <span m="948370">color</span>
  <span m="951750">the</span> <span m="952020">squares</span> <span m="952860">according</span>
  <span m="953280">to,</span> <span m="953750">in</span> <span m="953910">this</span>
  <span m="954180">alternating</span> <span m="954690">black</span> <span m="955020">and</span>
  <span m="955110">white</span> <span m="955690">manner,</span> <span m="956070">according</span>
  <span m="956460">to</span> <span m="956580">a</span> <span m="956670">usual</span>
  <span m="957150">checkerboard.</span></p><p><span m="962890">And</span> <span m="963430">as</span>
  <span m="963640">the</span> <span m="963790">number</span> <span m="964270">of</span>
  <span m="965140">squares</span> <span m="965800">goes</span> <span m="966100">to</span>
  <span m="966220">infinity,</span> <span m="967690">what</span> <span m="967900">should</span>
  <span m="968830">this</span> <span m="969640">converge</span> <span m="970120">to?</span>
  <span m="973210">By</span> <span m="973370">the</span> <span m="973460">story</span>
  <span m="973850">I</span> <span m="973970">just</span> <span m="974150">told</span>
  <span m="974390">you,</span> <span m="974940">you</span> <span m="974960">might</span>
  <span m="975110">think</span> <span m="975500">that</span> <span m="976250">if</span>
  <span m="976370">you</span> <span m="977450">zoom</span> <span m="977720">out,</span>
  <span m="978020">everything</span> <span m="978410">looks</span> <span m="978860">density</span>
  <span m="979220">1/2.</span> <span m="981030">And</span> <span m="981240">so</span>
  <span m="981600">you</span> <span m="981720">might</span> <span m="981930">guess</span>
  <span m="982560">that</span> <span m="982740">the</span> <span m="982860">image,</span>
  <span m="983400">the</span> <span m="983730">limit,</span> <span m="984210">is</span>
  <span m="984630">the</span> <span m="984750">1/2</span> <span m="985950">constant.</span></p><p><span
  m="987820">But</span> <span m="987970">what</span> <span m="988140">is</span> <span
  m="988300">this</span> <span m="988480">graph?</span> <span m="992570">It's</span>
  <span m="992620">a</span> <span m="992680">complete</span> <span m="993160">bipartite</span>
  <span m="993760">graph.</span> <span m="998390">It</span> <span m="998480">is</span>
  <span m="998600">a</span> <span m="998660">complete</span> <span m="999080">bipartite</span>
  <span m="999620">graph</span> <span m="1001700">between</span> <span m="1001970">all</span>
  <span m="1002290">the</span> <span m="1002750">even</span> <span m="1003050">rows.</span>
  <span m="1004190">And</span> <span m="1004340">there's</span> <span m="1004490">a</span>
  <span m="1004550">different</span> <span m="1004880">way</span> <span m="1005060">to</span>
  <span m="1005210">draw</span> <span m="1005460">the</span> <span m="1005570">complete</span>
  <span m="1005960">bipartite</span> <span m="1006470">graph--</span> <span m="1008590">namely,</span>
  <span m="1014930">that</span> <span m="1015110">picture,</span> <span m="1015740">just</span>
  <span m="1015920">by</span> <span m="1016340">permuting</span> <span m="1016880">the</span>
  <span m="1017020">rows</span> <span m="1017300">and</span> <span m="1017390">columns.</span>
  <span m="1019740">And</span> <span m="1021360">it's</span> <span m="1021540">much</span>
  <span m="1021780">more</span> <span m="1021930">reasonable</span> <span m="1022800">that</span>
  <span m="1023550">this</span> <span m="1024000">is</span> <span m="1024150">the</span>
  <span m="1024300">limit</span> <span m="1025260">of</span> <span m="1025410">the</span>
  <span m="1025470">sequence</span> <span m="1025980">of</span> <span m="1026190">complete</span>
  <span m="1026579">bipartite</span> <span m="1027030">graphs</span> <span m="1027420">with</span>
  <span m="1027810">equal</span> <span m="1028109">parts.</span></p><p><span m="1031010">So</span>
  <span m="1031190">one</span> <span m="1031369">needs</span> <span m="1031550">to</span>
  <span m="1031640">be</span> <span m="1031760">very</span> <span m="1032030">careful.</span>
  <span m="1032569">And</span> <span m="1032960">so</span> <span m="1033140">it's</span>
  <span m="1033290">not</span> <span m="1033920">necessarily</span> <span m="1034670">an</span>
  <span m="1035000">intuitive</span> <span m="1036650">definition.</span> <span m="1037810">The</span>
  <span m="1038420">idea</span> <span m="1038810">that</span> <span m="1039260">you</span>
  <span m="1039380">just</span> <span m="1039740">squint</span> <span m="1040130">your</span>
  <span m="1040250">eyes</span> <span m="1040520">and</span> <span m="1040609">think</span>
  <span m="1040790">about</span> <span m="1040970">what</span> <span m="1041089">the</span>
  <span m="1041140">image</span> <span m="1041450">becomes,</span> <span m="1042770">that</span>
  <span m="1043190">works</span> <span m="1043550">fine</span> <span m="1044240">for</span>
  <span m="1044420">intuition</span> <span m="1044960">for</span> <span m="1045109">some</span>
  <span m="1045410">examples,</span> <span m="1046010">but</span> <span m="1046160">not</span>
  <span m="1046369">for</span> <span m="1046520">others.</span> <span m="1047180">So</span>
  <span m="1047300">we</span> <span m="1047480">do</span> <span m="1047650">really</span>
  <span m="1047869">need</span> <span m="1048020">to</span> <span m="1048079">be</span>
  <span m="1048200">careful</span> <span m="1048590">in</span> <span m="1048680">giving</span>
  <span m="1048980">a</span> <span m="1049040">precise</span> <span m="1049490">definition.</span>
  <span m="1050390">And</span> <span m="1050540">here</span> <span m="1051050">the</span>
  <span m="1051380">rearrangement</span> <span m="1051875">of</span> <span m="1052370">the</span>
  <span m="1052730">rows</span> <span m="1053090">and</span> <span m="1053180">columns</span>
  <span m="1053750">needs</span> <span m="1053960">to</span> <span m="1054050">be</span>
  <span m="1054260">taken</span> <span m="1054530">care</span> <span m="1054800">of.</span></p><p><span
  m="1066780">So</span> <span m="1066900">let</span> <span m="1067020">me</span> <span
  m="1067140">be</span> <span m="1067260">more</span> <span m="1067410">precise.</span>
  <span m="1070700">Starting</span> <span m="1071090">with</span> <span m="1071240">a</span>
  <span m="1071300">graph</span> <span m="1071630">G,</span> <span m="1076140">I</span>
  <span m="1076290">can--</span> <span m="1077680">so</span> <span m="1078300">let</span>
  <span m="1078450">me</span> <span m="1078630">label</span> <span m="1079050">the</span>
  <span m="1079290">vertices</span> <span m="1079860">by</span> <span m="1080910">1</span>
  <span m="1081150">through</span> <span m="1081450">n.</span> <span m="1083280">I</span>
  <span m="1083400">can</span> <span m="1084000">denote</span> <span m="1084900">by</span>
  <span m="1085680">W</span> <span m="1086040">sub</span> <span m="1086290">G</span>
  <span m="1088059">this</span> <span m="1091440">function,</span> <span m="1093111">this</span>
  <span m="1093510">graphon,</span> <span m="1095490">obtained</span> <span m="1097920">by</span>
  <span m="1098810">the</span> <span m="1098910">following</span> <span m="1099330">procedure.</span></p><p><span
  m="1104630">First,</span> <span m="1105020">you</span> <span m="1105200">partition</span>
  <span m="1105840">the</span> <span m="1105920">interval</span> <span m="1110820">into</span>
  <span m="1114870">intervals</span> <span m="1117500">of</span> <span m="1117680">length</span>
  <span m="1118040">exactly</span> <span m="1118490">1</span> <span m="1118680">over</span>
  <span m="1118780">n.</span> <span m="1124680">And</span> <span m="1125580">you</span>
  <span m="1125730">set</span> <span m="1131810">W</span> <span m="1132170">of</span>
  <span m="1132470">x</span> <span m="1132740">comma</span> <span m="1133040">y</span>
  <span m="1133550">to</span> <span m="1133670">be</span> <span m="1133940">basically</span>
  <span m="1134330">what</span> <span m="1135140">happened</span> <span m="1135530">in</span>
  <span m="1135680">the</span> <span m="1135740">procedure</span> <span m="1136190">above.</span>
  <span m="1137780">If</span> <span m="1138830">x</span> <span m="1139040">and</span>
  <span m="1139130">y</span> <span m="1139760">lie</span> <span m="1140150">in</span>
  <span m="1140930">the</span> <span m="1140990">box</span> <span m="1142600">I</span>
  <span m="1142730">sub I</span> <span m="1143120">cross</span> <span m="1143540">I</span>
  <span m="1143690">sub</span> <span m="1143870">J,</span> <span m="1144530">then</span>
  <span m="1145850">I</span> <span m="1145970">put</span> <span m="1146240">in</span>
  <span m="1146840">1</span> <span m="1147680">if</span> <span m="1148280">I</span>
  <span m="1148640">is</span> <span m="1148880">adjacent</span> <span m="1149300">to</span>
  <span m="1149390">J</span> <span m="1149750">and</span> <span m="1149900">0</span>
  <span m="1150290">otherwise--</span> <span m="1155800">so</span> <span m="1155840">this</span>
  <span m="1156020">picture,</span> <span m="1156680">where</span> <span m="1157340">we</span>
  <span m="1157550">obtained</span> <span m="1158390">by</span> <span m="1159080">taking</span>
  <span m="1159380">the</span> <span m="1159500">adjacency</span> <span m="1159950">matrix</span>
  <span m="1160670">and</span> <span m="1160790">transforming</span> <span m="1161570">it</span>
  <span m="1161720">into</span> <span m="1161990">a</span> <span m="1162050">pixelated</span>
  <span m="1162620">image.</span></p><p><span m="1168960">What</span> <span m="1169110">are</span>
  <span m="1169170">some</span> <span m="1169320">of</span> <span m="1169380">the</span>
  <span m="1169440">things</span> <span m="1169620">that</span> <span m="1169710">we</span>
  <span m="1169800">would</span> <span m="1169920">like</span> <span m="1170070">to</span>
  <span m="1170160">do</span> <span m="1170440">with</span> <span m="1170910">graph</span>
  <span m="1171180">limits</span> <span m="1171600">or</span> <span m="1171690">graphs</span>
  <span m="1172020">in</span> <span m="1172110">general?</span> <span m="1172460">Yeah?</span></p><p><span
  m="1172937">AUDIENCE:</span> <span m="1173175">Is</span> <span m="1173891">the</span>
  <span m="1174368">range</span> <span m="1174606">also</span> <span m="1174845">0,
  1,</span> <span m="1175322">squared or</span> <span m="1175799">0,</span> <span
  m="1176276">1?</span></p><p><span m="1177707">YUFEI ZHAO:</span> <span m="1177868">Thank</span>
  <span m="1178029">you.</span> <span m="1178190">The</span> <span m="1178280">range</span>
  <span m="1178530">is</span> <span m="1178660">0,</span> <span m="1178870">1.</span>
  <span m="1182730">So</span> <span m="1182850">here</span> <span m="1183720">are</span>
  <span m="1183870">some</span> <span m="1184110">quantities</span> <span m="1184590">we
  are</span> <span m="1184770">interested</span> <span m="1185250">in</span> <span
  m="1185670">when</span> <span m="1185850">considering</span> <span m="1186480">graph</span>
  <span m="1186810">limits.</span> <span m="1188170">So</span> <span m="1188340">given</span>
  <span m="1188760">two</span> <span m="1189090">graphs,</span> <span m="1193680">G</span>
  <span m="1193980">and</span> <span m="1194130">H,</span> <span m="1196140">we</span>
  <span m="1196290">say</span> <span m="1196530">that</span> <span m="1197160">a</span>
  <span m="1197280">graph</span> <span m="1197670">homomorphism--</span> <span m="1204770">so</span>
  <span m="1204990">a</span> <span m="1205050">graph</span> <span m="1205320">homomorphism</span>
  <span m="1206400">between</span> <span m="1208320">from</span> <span m="1209040">G</span>
  <span m="1209400">to</span> <span m="1209700">H</span> <span m="1213390">is</span>
  <span m="1213560">a</span> <span m="1213650">map</span> <span m="1216450">of</span>
  <span m="1216720">their</span> <span m="1217320">vertexes</span> <span m="1222870">such</span>
  <span m="1223230">that</span> <span m="1223950">the</span> <span m="1224280">edges</span>
  <span m="1224910">are</span> <span m="1225090">preserved.</span> <span m="1230910">So</span>
  <span m="1231070">you</span> <span m="1231220">have--</span> <span m="1234844">and</span>
  <span m="1235310">so</span> <span m="1235580">whenever</span> <span m="1236570">uv</span>
  <span m="1237020">is</span> <span m="1237200">an</span> <span m="1237350">edge</span>
  <span m="1239780">of</span> <span m="1240150">H,</span> <span m="1240865">your</span>
  <span m="1241210">image</span> <span m="1242450">vertices</span> <span m="1243530">get</span>
  <span m="1243710">mapped</span> <span m="1244130">to</span> <span m="1244490">an</span>
  <span m="1244640">edge</span> <span m="1244970">of</span> <span m="1245120">G.</span></p><p><span
  m="1248880">And</span> <span m="1249120">we</span> <span m="1249390">are</span>
  <span m="1249510">interested</span> <span m="1250140">in</span> <span m="1250440">the</span>
  <span m="1250590">number</span> <span m="1251100">of</span> <span m="1251530">graph</span>
  <span m="1251810">homomorphisms.</span> <span m="1252810">So</span> <span m="1253050">often</span>
  <span m="1253500">I</span> <span m="1253650">use</span> <span m="1254250">uppercase</span>
  <span m="1254760">to</span> <span m="1254880">denote</span> <span m="1255940">a</span>
  <span m="1256020">set</span> <span m="1260860">of</span> <span m="1261550">homomorphisms</span>
  <span m="1264190">G</span> <span m="1264400">to</span> <span m="1264610">H--</span>
  <span m="1265390">and</span> <span m="1265990">lowercase</span> <span m="1266620">to</span>
  <span m="1266740">denote</span> <span m="1267040">the</span> <span m="1267170">number.</span>
  <span m="1276690">So</span> <span m="1276730">for</span> <span m="1276850">example,</span>
  <span m="1280260">the</span> <span m="1280280">number</span> <span m="1280610">of</span>
  <span m="1280700">homomorphisms</span> <span m="1281480">from</span> <span m="1283130">a</span>
  <span m="1283160">single</span> <span m="1283610">vertex--</span> <span m="1284570">so
  a</span> <span m="1284690">single</span> <span m="1285050">vertex</span> <span m="1285440">with</span>
  <span m="1285530">no</span> <span m="1285740">edge</span> <span m="1285980">to</span>
  <span m="1286160">a</span> <span m="1286220">graph</span> <span m="1286520">G,</span>
  <span m="1287690">that's</span> <span m="1287990">just</span> <span m="1288260">the--</span>
  <span m="1290310">what</span> <span m="1290490">is</span> <span m="1290580">this</span>
  <span m="1290700">quantity?</span> <span m="1294572">So</span> <span m="1294810">some</span>
  <span m="1295310">number</span> <span m="1295670">of</span> <span m="1295790">vertices</span>
  <span m="1296270">of</span> <span m="1296360">G--</span> <span m="1300730">what</span>
  <span m="1300880">about</span> <span m="1302170">homomorphisms</span> <span m="1302920">from</span>
  <span m="1305400">an</span> <span m="1305520">edge</span> <span m="1305820">to</span>
  <span m="1306000">G?</span></p><p><span m="1308740">AUDIENCE:</span> <span m="1308902">The</span>
  <span m="1309064">number</span> <span m="1309228">of</span> <span m="1309716">edges?</span></p><p><span
  m="1311180">YUFEI ZHAO:</span> <span m="1311315">Not</span> <span m="1311450">quite
  the</span> <span m="1311780">number</span> <span m="1312140">of</span> <span m="1312260">edges,</span>
  <span m="1313310">but</span> <span m="1313430">twice</span> <span m="1313790">the</span>
  <span m="1313880">number</span> <span m="1314150">of</span> <span m="1314300">edges.</span>
  <span m="1319730">What</span> <span m="1319900">about</span> <span m="1320140">the</span>
  <span m="1320200">number</span> <span m="1322000">of</span> <span m="1322120">homomorphisms</span>
  <span m="1322810">from</span> <span m="1322990">a</span> <span m="1323050">triangle</span>
  <span m="1323770">to</span> <span m="1324070">G?</span></p><p><span m="1330693">AUDIENCE:</span>
  <span m="1330938">6</span> <span m="1331184">times the number</span> <span m="1331675">of
  triangles.</span></p><p><span m="1332170">YUFEI ZHAO:</span> <span m="1332245">So</span>
  <span m="1332320">yeah,</span> <span m="1333130">you</span> <span m="1333220">got</span>
  <span m="1333340">the</span> <span m="1333430">idea--</span> <span m="1333700">so</span>
  <span m="1333820">the</span> <span m="1333910">6</span> <span m="1334240">times</span>
  <span m="1334570">the</span> <span m="1334660">number</span> <span m="1334960">of</span>
  <span m="1335050">triangles.</span> <span m="1342172">So</span> <span m="1342650">now</span>
  <span m="1342930">let</span> <span m="1343080">me</span> <span m="1343200">ask</span>
  <span m="1343500">a</span> <span m="1344550">slightly</span> <span m="1344970">more</span>
  <span m="1345120">interesting</span> <span m="1345570">question.</span> <span m="1346740">What</span>
  <span m="1346890">about</span> <span m="1347070">the</span> <span m="1347130">number</span>
  <span m="1347370">of</span> <span m="1347430">homomorphisms</span> <span m="1348180">from</span>
  <span m="1348510">H</span> <span m="1348890">to</span> <span m="1349320">a</span>
  <span m="1349410">triangle?</span> <span m="1354990">What's</span> <span m="1355350">a</span>
  <span m="1355440">different</span> <span m="1355800">name</span> <span m="1356040">for</span>
  <span m="1356190">this</span> <span m="1356370">quantity</span> <span m="1356840">here?</span></p><p><span
  m="1365630">It's</span> <span m="1365780">the</span> <span m="1365840">number</span>
  <span m="1366200">of</span> <span m="1366320">proper</span> <span m="1366710">three</span>
  <span m="1366920">colorings.</span> <span m="1373820">So</span> <span m="1373990">it's
  the</span> <span m="1374060">number</span> <span m="1374370">of</span> <span m="1374460">proper</span>
  <span m="1374850">three</span> <span m="1375060">colorings,</span> <span m="1377380">the</span>
  <span m="1377540">number</span> <span m="1377840">of</span> <span m="1377900">proper</span>
  <span m="1378230">colorings</span> <span m="1380410">of</span> <span m="1380590">H</span>
  <span m="1382000">with</span> <span m="1384830">three</span> <span m="1385160">labeled</span>
  <span m="1385520">colors,</span> <span m="1386090">red,</span> <span m="1386520">green,</span>
  <span m="1386780">and</span> <span m="1386880">blue.</span> <span m="1389940">So</span>
  <span m="1390020">think</span> <span m="1390230">about</span> <span m="1390530">the</span>
  <span m="1390650">three</span> <span m="1391130">vertices.</span> <span m="1391640">That's</span>
  <span m="1391940">red,</span> <span m="1392400">green,</span> <span m="1392710">and</span>
  <span m="1392810">blue.</span> <span m="1393510">And</span> <span m="1393980">whichever</span>
  <span m="1394670">vertex</span> <span m="1395150">of</span> <span m="1395300">H</span>
  <span m="1395600">can</span> <span m="1395810">map</span> <span m="1396110">to</span>
  <span m="1396230">red,</span> <span m="1396790">color</span> <span m="1397120">that</span>
  <span m="1397320">vertex</span> <span m="1397730">red.</span></p><p><span m="1398610">So</span>
  <span m="1398990">you</span> <span m="1399080">see</span> <span m="1399290">that</span>
  <span m="1399440">there is</span> <span m="1399650">a</span> <span m="1399710">one-to-one</span>
  <span m="1400160">correspondence</span> <span m="1401150">between</span> <span m="1401600">such</span>
  <span m="1401870">homomorphisms</span> <span m="1403250">and</span> <span m="1403520">proper</span>
  <span m="1403850">colorings.</span> <span m="1405680">So</span> <span m="1405830">many</span>
  <span m="1406430">important</span> <span m="1406940">graph</span> <span m="1407330">parameters,</span>
  <span m="1408020">graph</span> <span m="1408290">quantities,</span> <span m="1408740">can</span>
  <span m="1408920">be</span> <span m="1409010">encoded</span> <span m="1409760">in</span>
  <span m="1409880">terms</span> <span m="1410210">of</span> <span m="1410300">graph</span>
  <span m="1410540">homomorphisms.</span> <span m="1413420">And</span> <span m="1414110">these</span>
  <span m="1414470">are</span> <span m="1414530">the</span> <span m="1414620">ones</span>
  <span m="1414890">that</span> <span m="1415010">we're</span> <span m="1415100">going</span>
  <span m="1415190">to</span> <span m="1415280">be</span> <span m="1415370">looking</span>
  <span m="1415700">at</span> <span m="1416240">most</span> <span m="1416510">of</span>
  <span m="1416600">the</span> <span m="1416690">time.</span></p><p><span m="1419780">When</span>
  <span m="1419980">we're</span> <span m="1420120">thinking</span> <span m="1420450">about</span>
  <span m="1421020">very</span> <span m="1421380">large</span> <span m="1421770">graphs,</span>
  <span m="1422490">often</span> <span m="1422790">it's</span> <span m="1422940">not</span>
  <span m="1423140">the</span> <span m="1423210">number</span> <span m="1423720">of</span>
  <span m="1423840">homomorphisms</span> <span m="1424620">that</span> <span m="1424740">concern</span>
  <span m="1425190">us,</span> <span m="1425490">but</span> <span m="1425690">the</span>
  <span m="1425800">density</span> <span m="1426390">of</span> <span m="1426510">homomorphisms.</span>
  <span m="1428980">And</span> <span m="1430900">the</span> <span m="1431020">difference</span>
  <span m="1431500">between</span> <span m="1431920">homomorphisms</span> <span m="1432730">on</span>
  <span m="1432820">one</span> <span m="1433000">hand</span> <span m="1433270">and</span>
  <span m="1433360">subgraphs</span> <span m="1434500">is</span> <span m="1434680">that</span>
  <span m="1437430">the</span> <span m="1437650">homomorphisms</span> <span m="1438805">are</span>
  <span m="1439250">not</span> <span m="1439450">quite</span> <span m="1439750">the</span>
  <span m="1439840">same</span> <span m="1440170">as</span> <span m="1440650">subgraphs,</span>
  <span m="1443110">other</span> <span m="1443320">than</span> <span m="1443650">this</span>
  <span m="1443860">multiplicity,</span> <span m="1444700">because</span> <span m="1445180">you</span>
  <span m="1445330">might</span> <span m="1445540">have</span> <span m="1446620">non-injective</span>
  <span m="1449970">homomorphisms.</span> <span m="1452220">But</span> <span m="1452430">these</span>
  <span m="1452670">non-injective</span> <span m="1453480">homomorphisms</span> <span
  m="1454770">do</span> <span m="1454890">not</span> <span m="1455130">end</span>
  <span m="1455310">up</span> <span m="1455430">contributing</span> <span m="1456090">very</span>
  <span m="1456300">much</span> <span m="1457530">because</span> <span m="1457800">they</span>
  <span m="1457980">only</span> <span m="1458700">have</span> <span m="1460800">n</span>
  <span m="1461190">to</span> <span m="1461430">the</span> <span m="1462060">number</span>
  <span m="1462360">of</span> <span m="1463800">vertices</span> <span m="1464280">of</span>
  <span m="1464400">H</span> <span m="1464940">minus</span> <span m="1465270">1</span>
  <span m="1465540">on</span> <span m="1465810">that</span> <span m="1466050">border</span>
  <span m="1466620">where</span> <span m="1466860">I</span> <span m="1466950">think</span>
  <span m="1467160">of</span> <span m="1467280">n</span> <span m="1467580">as</span>
  <span m="1467760">the</span> <span m="1469290">number</span> <span m="1469560">of</span>
  <span m="1469620">vertices</span> <span m="1470070">of</span> <span m="1470160">G.</span>
  <span m="1470880">n</span> <span m="1471060">is</span> <span m="1471120">supposed</span>
  <span m="1471420">to</span> <span m="1471510">be</span> <span m="1471810">large.</span>
  <span m="1473690">So</span> <span m="1474410">in</span> <span m="1474500">terms</span>
  <span m="1474800">of</span> <span m="1475280">graph</span> <span m="1475580">limits</span>
  <span m="1475970">when</span> <span m="1476260">n</span> <span m="1476330">gets</span>
  <span m="1476580">large,</span> <span m="1477170">I</span> <span m="1477320">don't</span>
  <span m="1477530">need</span> <span m="1477650">to</span> <span m="1477740">distinguish</span>
  <span m="1478880">so</span> <span m="1479060">much</span> <span m="1479270">between</span>
  <span m="1479540">homomorphisms</span> <span m="1480350">and</span> <span m="1480530">subgraphs.</span></p><p><span
  m="1484020">We</span> <span m="1484170">define</span> <span m="1484640">the</span>
  <span m="1484740">homomorphism</span> <span m="1485430">density,</span> <span m="1496390">denoted</span>
  <span m="1496870">by</span> <span m="1497050">the</span> <span m="1497140">letter</span>
  <span m="1497380">t,</span> <span m="1499060">from</span> <span m="1499890">H</span>
  <span m="1500180">to</span> <span m="1500380">G,</span> <span m="1501670">by--</span>
  <span m="1504060">define</span> <span m="1504400">it</span> <span m="1504490">to</span>
  <span m="1504580">be</span> <span m="1504730">the</span> <span m="1505300">fraction</span>
  <span m="1506110">of</span> <span m="1506410">all</span> <span m="1507160">vertex</span>
  <span m="1507640">maps</span> <span m="1508810">that</span> <span m="1510640">are</span>
  <span m="1510850">homomorphisms.</span> <span m="1517890">So</span> <span m="1517920">this</span>
  <span m="1518100">is</span> <span m="1518220">also</span> <span m="1519870">equivalent</span>
  <span m="1520470">to</span> <span m="1520740">be</span> <span m="1520950">defined</span>
  <span m="1521760">as</span> <span m="1521910">the</span> <span m="1522000">probability</span>
  <span m="1522720">that</span> <span m="1523050">a</span> <span m="1523410">uniform</span>
  <span m="1523920">random</span> <span m="1524220">map</span> <span m="1530070">from</span>
  <span m="1531150">the</span> <span m="1531240">vertex</span> <span m="1531650">set</span>
  <span m="1531780">of</span> <span m="1531870">H</span> <span m="1532710">to</span>
  <span m="1532920">the</span> <span m="1533010">vertex</span> <span m="1533400">set</span>
  <span m="1533530">of</span> <span m="1533620">G</span> <span m="1535320">is</span>
  <span m="1535620">a</span> <span m="1535860">homomorphism</span> <span m="1536970">from</span>
  <span m="1537930">H</span> <span m="1538500">to</span> <span m="1538890">G.</span>
  <span m="1540930">So</span> <span m="1541050">it's</span> <span m="1541200">a</span>
  <span m="1541260">graph</span> <span m="1541480">homomorphism.</span> <span m="1543460">And</span>
  <span m="1543860">this</span> <span m="1544040">quantity</span> <span m="1544460">turns</span>
  <span m="1544700">out</span> <span m="1544790">to</span> <span m="1544850">be</span>
  <span m="1544970">quite</span> <span m="1545210">important.</span> <span m="1545680">So
  we're</span> <span m="1545960">going to be</span> <span m="1546080">seeing</span>
  <span m="1546290">this</span> <span m="1546620">a</span> <span m="1546680">lot.</span></p><p><span
  m="1548740">And</span> <span m="1549880">because</span> <span m="1550360">of</span>
  <span m="1550840">this</span> <span m="1551050">remark</span> <span m="1551560">over</span>
  <span m="1551800">here,</span> <span m="1553840">in</span> <span m="1554020">the</span>
  <span m="1554140">limit,</span> <span m="1555170">this</span> <span m="1555460">quantity</span>
  <span m="1556000">of</span> <span m="1556150">graph</span> <span m="1556750">homomorphism</span>
  <span m="1557440">densities</span> <span m="1562600">in</span> <span m="1562730">the</span>
  <span m="1562880">limit</span> <span m="1563400">as</span> <span m="1563600">the</span>
  <span m="1563660">number</span> <span m="1563960">of</span> <span m="1564020">vertices</span>
  <span m="1565790">G</span> <span m="1566000">goes</span> <span m="1566240">to</span>
  <span m="1566300">infinity</span> <span m="1566960">and</span> <span m="1567140">H</span>
  <span m="1567440">fixed,</span> <span m="1570330">the</span> <span m="1570470">homomorphism</span>
  <span m="1571190">densities</span> <span m="1576470">approaches</span> <span m="1577040">the</span>
  <span m="1577130">same</span> <span m="1577460">limit</span> <span m="1578390">as</span>
  <span m="1578940">subgraph</span> <span m="1579440">densities.</span> <span m="1589250">So</span>
  <span m="1589400">you</span> <span m="1589460">should</span> <span m="1589610">regard</span>
  <span m="1590000">these</span> <span m="1590180">two</span> <span m="1590300">quantities</span>
  <span m="1590840">as</span> <span m="1591020">basically</span> <span m="1591530">the</span>
  <span m="1591620">same</span> <span m="1591890">thing.</span> <span m="1595740">Any</span>
  <span m="1595890">questions</span> <span m="1596190">so</span> <span m="1596320">far?</span></p><p><span
  m="1601100">So</span> <span m="1601250">all</span> <span m="1601400">of</span> <span
  m="1601460">these</span> <span m="1601640">quantities</span> <span m="1602030">so</span>
  <span m="1602270">far</span> <span m="1602450">defined</span> <span m="1603230">are</span>
  <span m="1603620">for--</span> <span m="1605480">so</span> <span m="1606760">everything
  is</span> <span m="1607100">defined</span> <span m="1607400">so</span> <span m="1607520">far</span>
  <span m="1607730">for</span> <span m="1607920">graphs,</span> <span m="1608540">so</span>
  <span m="1608660">what</span> <span m="1608750">happens</span> <span m="1609290">between</span>
  <span m="1609650">graphs</span> <span m="1609950">and</span> <span m="1610040">graphs.</span>
  <span m="1610820">So</span> <span m="1611570">what</span> <span m="1611790">about</span>
  <span m="1612110">for</span> <span m="1612320">graphons?</span> <span m="1613590">I'll</span>
  <span m="1613730">give</span> <span m="1613970">you</span> <span m="1614120">this</span>
  <span m="1614330">limit</span> <span m="1614660">object,</span> <span m="1615230">this</span>
  <span m="1615560">analytic</span> <span m="1616040">object.</span> <span m="1616730">I</span>
  <span m="1616820">can</span> <span m="1617000">still</span> <span m="1617330">define</span>
  <span m="1618380">densities</span> <span m="1619970">by</span> <span m="1620240">integrals</span>
  <span m="1620750">now.</span> <span m="1621500">So</span> <span m="1621950">suppose</span>
  <span m="1622490">I</span> <span m="1622670">start</span> <span m="1623030">with</span>
  <span m="1623240">a</span> <span m="1624830">symmetric</span> <span m="1625640">measurable</span>
  <span m="1626060">function.</span></p><p><span m="1634480">So</span> <span m="1634610">tell</span>
  <span m="1634810">me,</span> <span m="1638240">for</span> <span m="1638320">example,
  a</span> <span m="1638800">graphon.</span> <span m="1639250">But</span> <span m="1640240">I</span>
  <span m="1640360">can</span> <span m="1640930">let</span> <span m="1641110">my</span>
  <span m="1641260">range</span> <span m="1641650">be</span> <span m="1641800">even</span>
  <span m="1642040">more</span> <span m="1642190">generous.</span> <span m="1643780">Starting</span>
  <span m="1644170">with</span> <span m="1644290">such</span> <span m="1644470">a</span>
  <span m="1644530">function,</span> <span m="1645250">I</span> <span m="1645370">define</span>
  <span m="1648010">the</span> <span m="1648610">graph</span> <span m="1648870">homomorphism</span>
  <span m="1649390">density</span> <span m="1650050">from</span> <span m="1650770">a</span>
  <span m="1650890">fixed</span> <span m="1651280">graph</span> <span m="1651790">H</span>
  <span m="1652150">to</span> <span m="1652360">this</span> <span m="1653260">graphon</span>
  <span m="1653920">or</span> <span m="1654610">kernel,</span> <span m="1655030">more</span>
  <span m="1655240">generally,</span> <span m="1656050">to</span> <span m="1656170">be</span>
  <span m="1656650">the</span> <span m="1656770">following</span> <span m="1659150">integral,</span>
  <span m="1661040">where</span> <span m="1662790">I'm--</span> <span m="1665500">before</span>
  <span m="1665800">writing</span> <span m="1665940">down</span> <span m="1666120">the</span>
  <span m="1666190">full</span> <span m="1666370">form,</span> <span m="1666640">let</span>
  <span m="1666760">me</span> <span m="1666880">first</span> <span m="1667090">give</span>
  <span m="1667240">you</span> <span m="1667330">an</span> <span m="1667420">example.</span>
  <span m="1667900">I</span> <span m="1667960">think</span> <span m="1668110">it will</span>
  <span m="1668230">be</span> <span m="1668320">more</span> <span m="1668530">helpful.</span></p><p><span
  m="1669530">So</span> <span m="1670300">if</span> <span m="1670450">I'm</span> <span
  m="1670600">looking</span> <span m="1670930">at</span> <span m="1671520">a</span>
  <span m="1671590">triangle</span> <span m="1675290">going</span> <span m="1675590">to</span>
  <span m="1675770">W,</span> <span m="1676700">what</span> <span m="1676910">I</span>
  <span m="1677030">would</span> <span m="1677180">like</span> <span m="1677690">is
  the</span> <span m="1678080">integral</span> <span m="1678950">that</span> <span
  m="1679190">captures</span> <span m="1680540">the</span> <span m="1680990">triangle</span>
  <span m="1681470">density.</span> <span m="1688410">So</span> <span m="1689100">this</span>
  <span m="1689430">quantity</span> <span m="1689910">here,</span> <span m="1691020">if</span>
  <span m="1691170">I</span> <span m="1691770">let</span> <span m="1692070">x,</span>
  <span m="1692370">y,</span> <span m="1692640">and</span> <span m="1692710">z</span>
  <span m="1694350">vary</span> <span m="1694950">over</span> <span m="1697770">0</span>
  <span m="1698070">and</span> <span m="1698190">1,</span> <span m="1699120">0</span>
  <span m="1699390">through</span> <span m="1699540">1,</span> <span m="1699790">independently</span>
  <span m="1700065">and</span> <span m="1700340">uniformly,</span> <span m="1701670">then</span>
  <span m="1701850">this</span> <span m="1702030">quantity</span> <span m="1702390">here</span>
  <span m="1702600">captures</span> <span m="1703230">the</span> <span m="1703350">triangle</span>
  <span m="1704010">density</span> <span m="1704760">in</span> <span m="1704940">W.</span>
  <span m="1707540">In</span> <span m="1707660">fact,</span> <span m="1708290">and</span>
  <span m="1708440">I'll</span> <span m="1708650">state</span> <span m="1708980">this</span>
  <span m="1709400">more</span> <span m="1709550">precisely</span> <span m="1710030">in
  a</span> <span m="1710120">second--</span> <span m="1710660">if</span> <span m="1710810">you</span>
  <span m="1710930">look</span> <span m="1711110">at</span> <span m="1711170">the</span>
  <span m="1711680">translation</span> <span m="1712370">from</span> <span m="1712760">graph</span>
  <span m="1713180">to</span> <span m="1713300">graphon</span> <span m="1715250">and</span>
  <span m="1715960">combine</span> <span m="1716350">that</span> <span m="1716470">translation</span>
  <span m="1717160">with</span> <span m="1718300">this</span> <span m="1718540">definition</span>
  <span m="1719020">here,</span> <span m="1719530">you</span> <span m="1719680">recover</span>
  <span m="1720190">the</span> <span m="1720310">triangle</span> <span m="1720790">density.</span>
  <span m="1725830">More</span> <span m="1725980">generally,</span> <span m="1727030">for</span>
  <span m="1728510">H</span> <span m="1728980">instead</span> <span m="1729400">of</span>
  <span m="1729790">a</span> <span m="1729850">triangle,</span> <span m="1731500">the</span>
  <span m="1732520">H</span> <span m="1732760">density</span> <span m="1733330">in</span>
  <span m="1733500">a</span> <span m="1733570">graphon</span> <span m="1733900">is</span>
  <span m="1734530">defined</span> <span m="1735010">to</span> <span m="1735100">be</span>
  <span m="1735340">the</span> <span m="1735670">integral</span> <span m="1736360">of--</span>
  <span m="1737110">instead</span> <span m="1737470">of</span> <span m="1738580">this</span>
  <span m="1739270">product</span> <span m="1739690">here,</span> <span m="1740480">I</span>
  <span m="1740770">take</span> <span m="1741010">a</span> <span m="1741040">product</span>
  <span m="1741700">corresponding</span> <span m="1743260">to</span> <span m="1743830">the</span>
  <span m="1743920">graph</span> <span m="1744250">structure</span> <span m="1744790">of</span>
  <span m="1745090">H</span> <span m="1745880">with</span> <span m="1746180">one</span>
  <span m="1746530">factor</span> <span m="1747070">for</span> <span m="1747310">each</span>
  <span m="1748060">edge</span> <span m="1748420">of</span> <span m="1748600">H.</span>
  <span m="1754360">And</span> <span m="1754480">the</span> <span m="1754540">variables</span>
  <span m="1756250">go</span> <span m="1756460">over</span> <span m="1757450">the</span>
  <span m="1758260">vertex</span> <span m="1758590">set</span> <span m="1758980">of</span>
  <span m="1759130">H.</span></p><p><span m="1768910">So</span> <span m="1769060">this</span>
  <span m="1769240">is</span> <span m="1769360">the</span> <span m="1769420">definition</span>
  <span m="1770080">of</span> <span m="1770680">homomorphism</span> <span m="1771400">densities,</span>
  <span m="1773000">not</span> <span m="1773200">for</span> <span m="1773350">graphs,</span>
  <span m="1773800">but</span> <span m="1774175">for</span> <span m="1775330">symmetric</span>
  <span m="1775960">measurable</span> <span m="1776440">functions,</span> <span m="1777250">in</span>
  <span m="1777340">particular,</span> <span m="1777820">for</span> <span m="1777970">graphons.</span>
  <span m="1779300">And</span> <span m="1779440">we</span> <span m="1779560">define</span>
  <span m="1779890">it</span> <span m="1780010">this</span> <span m="1780190">way</span>
  <span m="1780610">because--</span> <span m="1780970">and</span> <span m="1781330">we</span>
  <span m="1781450">use</span> <span m="1781610">the</span> <span m="1781690">same</span>
  <span m="1781960">symbols</span> <span m="1782620">because</span> <span m="1783070">these</span>
  <span m="1783280">two</span> <span m="1783430">definitions</span> <span m="1784090">agree.</span>
  <span m="1788970">If</span> <span m="1789090">you</span> <span m="1789180">start</span>
  <span m="1789570">with</span> <span m="1789750">a</span> <span m="1789780">graph</span>
  <span m="1790510">and</span> <span m="1790620">look</span> <span m="1790800">at</span>
  <span m="1790890">the H</span> <span m="1791070">density</span> <span m="1791415">in</span>
  <span m="1791940">G,</span> <span m="1792780">then</span> <span m="1793800">this</span>
  <span m="1794010">quantity</span> <span m="1794400">here</span> <span m="1795070">is</span>
  <span m="1795270">equal</span> <span m="1795720">to</span> <span m="1796170">the</span>
  <span m="1796350">H</span> <span m="1796620">density</span> <span m="1798780">in</span>
  <span m="1798960">the</span> <span m="1799080">graphon</span> <span m="1800010">associated</span>
  <span m="1800700">to</span> <span m="1800880">the</span> <span m="1800970">graph</span>
  <span m="1801270">G</span> <span m="1801720">constructed</span> <span m="1802590">as</span>
  <span m="1802740">we</span> <span m="1802900">did</span> <span m="1803040">just</span>
  <span m="1803310">now.</span> <span m="1806710">So</span> <span m="1806830">make</span>
  <span m="1807010">sure</span> <span m="1807190">you</span> <span m="1807310">understand</span>
  <span m="1808210">why</span> <span m="1808480">this</span> <span m="1808660">is</span>
  <span m="1808810">true</span> <span m="1809110">and</span> <span m="1809230">why</span>
  <span m="1809440">we</span> <span m="1809560">defined</span> <span m="1809825">the</span>
  <span m="1810090">densities</span> <span m="1810670">this</span> <span m="1810850">way.</span>
  <span m="1813910">Any</span> <span m="1814090">questions</span> <span m="1814420">so</span>
  <span m="1814570">far?</span></p><p><span m="1824990">So</span> <span m="1826120">we've</span>
  <span m="1826360">given</span> <span m="1826660">the</span> <span m="1826720">definition</span>
  <span m="1827650">of</span> <span m="1828550">graph</span> <span m="1828900">homomorphism</span>
  <span m="1829750">density.</span> <span m="1831310">And</span> <span m="1832240">we've</span>
  <span m="1832720">defined</span> <span m="1833230">these</span> <span m="1833440">objects,</span>
  <span m="1833960">these</span> <span m="1834040">graphons.</span> <span m="1840550">And</span>
  <span m="1840740">I</span> <span m="1840800">mentioned</span> <span m="1841250">even</span>
  <span m="1841460">something</span> <span m="1841820">about</span> <span m="1842360">the</span>
  <span m="1842480">idea</span> <span m="1842750">of</span> <span m="1842870">a</span>
  <span m="1842900">limit.</span> <span m="1843800">But</span> <span m="1844010">in</span>
  <span m="1844160">what</span> <span m="1844400">sense</span> <span m="1845030">can</span>
  <span m="1845240">we</span> <span m="1845390">have</span> <span m="1845810">a</span>
  <span m="1845930">limit</span> <span m="1846350">of</span> <span m="1846500">graphs?</span></p><p><span
  m="1864430">So</span> <span m="1864480">here is</span> <span m="1864990">an</span>
  <span m="1865140">important</span> <span m="1865530">definition</span> <span m="1866250">on</span>
  <span m="1866550">the</span> <span m="1866670">convergence</span> <span m="1867450">of</span>
  <span m="1867600">graphs.</span> <span m="1868650">So</span> <span m="1868680">in</span>
  <span m="1868800">what</span> <span m="1868980">sense</span> <span m="1869670">can</span>
  <span m="1869820">we</span> <span m="1869940">say</span> <span m="1870150">that</span>
  <span m="1870300">a</span> <span m="1870360">sequence</span> <span m="1870870">of</span>
  <span m="1870960">graphs</span> <span m="1871650">converge?</span> <span m="1874140">So</span>
  <span m="1874320">we</span> <span m="1874440">say</span> <span m="1878420">that</span>
  <span m="1879440">a</span> <span m="1879800">sequence</span> <span m="1881576">of</span>
  <span m="1881960">graphs</span> <span m="1887632">G</span> <span m="1888110">sub</span>
  <span m="1888400">n--</span> <span m="1892800">graphs</span> <span m="1893130">or</span>
  <span m="1893310">graphons,</span> <span m="1894180">so</span> <span m="1894390">these</span>
  <span m="1894630">two</span> <span m="1895740">definitions</span> <span m="1896310">are</span>
  <span m="1896730">interchangeable</span> <span m="1897680">for</span> <span m="1900340">what</span>
  <span m="1900660">I'm</span> <span m="1900830">about</span> <span m="1901010">to</span>
  <span m="1901100">say</span> <span m="1901290">regarding</span> <span m="1902040">limits</span>
  <span m="1902610">for</span> <span m="1902790">graphons,</span> <span m="1903780">in</span>
  <span m="1903870">which</span> <span m="1904020">case</span> <span m="1904230">I'm</span>
  <span m="1904320">going</span> <span m="1904470">to</span> <span m="1904530">denote</span>
  <span m="1904860">them</span> <span m="1905010">by</span> <span m="1905340">W</span>
  <span m="1905710">sub</span> <span m="1906080">n.</span> <span m="1909830">So</span>
  <span m="1909940">we</span> <span m="1910060">say</span> <span m="1910210">the</span>
  <span m="1910360">sequence</span> <span m="1911380">is</span> <span m="1911830">convergent</span>
  <span m="1917370">if</span> <span m="1920220">the</span> <span m="1920390">sequence</span>
  <span m="1920990">of</span> <span m="1922400">subgraph</span> <span m="1923150">densities--</span>
  <span m="1926590">of</span> <span m="1926650">course,</span> <span m="1926890">if</span>
  <span m="1927010">you are</span> <span m="1927130">looking</span> <span m="1927520">at</span>
  <span m="1927760">graphons,</span> <span m="1928390">then</span> <span m="1928660">you</span>
  <span m="1928720">should</span> <span m="1928870">look</span> <span m="1929110">at</span>
  <span m="1930160">the</span> <span m="1930940">graphon,</span> <span m="1933262">the</span>
  <span m="1933700">subgraph</span> <span m="1934180">density</span> <span m="1934600">in--</span>
  <span m="1935790">homomorphism</span> <span m="1936320">density</span> <span m="1936760">in</span>
  <span m="1936880">graphons</span> <span m="1939190">if</span> <span m="1939430">this</span>
  <span m="1939670">sequence</span> <span m="1940570">converges</span> <span m="1945300">as</span>
  <span m="1946470">n</span> <span m="1946770">goes</span> <span m="1947040">to</span>
  <span m="1947160">infinity</span> <span m="1948840">for</span> <span m="1949680">every</span>
  <span m="1951300">graph</span> <span m="1953830">H.</span></p><p><span m="1961540">So</span>
  <span m="1961660">that's</span> <span m="1961840">the</span> <span m="1961930">definition</span>
  <span m="1962470">of</span> <span m="1963190">what</span> <span m="1963400">it</span>
  <span m="1963460">means</span> <span m="1963700">for</span> <span m="1963850">a</span>
  <span m="1963880">sequence</span> <span m="1964330">of</span> <span m="1964390">graphs</span>
  <span m="1964690">to</span> <span m="1964780">converge,</span> <span m="1966220">which</span>
  <span m="1966520">so</span> <span m="1966820">far</span> <span m="1967120">looks</span>
  <span m="1967480">actually</span> <span m="1967780">quite</span> <span m="1968080">different</span>
  <span m="1968500">from</span> <span m="1968710">what</span> <span m="1968860">we</span>
  <span m="1969010">discussed</span> <span m="1969520">intuitively.</span> <span m="1970810">But</span>
  <span m="1971080">I will</span> <span m="1971320">state</span> <span m="1971590">some</span>
  <span m="1971800">theorems</span> <span m="1972250">towards</span> <span m="1972520">the</span>
  <span m="1972640">end</span> <span m="1972790">of</span> <span m="1972850">this</span>
  <span m="1973030">lecture</span> <span m="1973900">explaining</span> <span m="1974470">what</span>
  <span m="1974620">the</span> <span m="1974710">connections</span> <span m="1975280">are.</span>
  <span m="1976450">So</span> <span m="1977260">intuitively</span> <span m="1977860">what</span>
  <span m="1978010">I</span> <span m="1978100">said</span> <span m="1978340">earlier</span>
  <span m="1978730">is</span> <span m="1978850">that</span> <span m="1979030">you</span>
  <span m="1979150">have</span> <span m="1979330">a</span> <span m="1979360">sequence</span>
  <span m="1979750">of</span> <span m="1979840">graphs</span> <span m="1980080">that</span>
  <span m="1980200">are</span> <span m="1980260">convergent</span> <span m="1981190">if</span>
  <span m="1982510">you</span> <span m="1982660">have</span> <span m="1983020">some</span>
  <span m="1984220">vague</span> <span m="1984610">notion</span> <span m="1985060">of</span>
  <span m="1985240">one</span> <span m="1985600">image</span> <span m="1986050">morphing</span>
  <span m="1986590">into</span> <span m="1987760">a</span> <span m="1987850">sequence</span>
  <span m="1988330">of</span> <span m="1988420">images</span> <span m="1988870">morphing</span>
  <span m="1989260">into</span> <span m="1989650">this</span> <span m="1989860">final</span>
  <span m="1990220">image.</span> <span m="1991540">Still</span> <span m="1991810">hold</span>
  <span m="1992020">that</span> <span m="1992170">thought</span> <span m="1992380">in</span>
  <span m="1992440">your</span> <span m="1992590">mind.</span> <span m="1992830">But</span>
  <span m="1992980">that's</span> <span m="1993160">not</span> <span m="1993400">a</span>
  <span m="1993430">rigorous</span> <span m="1993820">definition</span> <span m="1994320">yet.</span></p><p><span
  m="1995050">The</span> <span m="1995140">definition</span> <span m="1995650">we</span>
  <span m="1995750">will</span> <span m="1995860">use</span> <span m="1996220">for</span>
  <span m="1997570">convergence</span> <span m="1998470">is</span> <span m="1998710">if</span>
  <span m="1998980">all</span> <span m="1999160">the</span> <span m="1999250">subgraph--</span>
  <span m="2000780">all</span> <span m="2000930">the</span> <span m="2001080">homomorphism</span>
  <span m="2001340">densities</span> <span m="2002310">were</span> <span m="2002430">equivalently</span>
  <span m="2003000">subgraph</span> <span m="2003480">densities,</span> <span m="2004050">they</span>
  <span m="2004220">converge.</span> <span m="2007250">So</span> <span m="2007280">this</span>
  <span m="2007460">is</span> <span m="2007530">the</span> <span m="2007580">definition.</span>
  <span m="2008960">It's</span> <span m="2009140">not</span> <span m="2009440">required.</span>
  <span m="2010380">So</span> <span m="2010460">this</span> <span m="2010730">is</span>
  <span m="2012140">basically</span> <span m="2012590">rigorous</span> <span m="2012905">as</span>
  <span m="2013220">stated.</span></p><p><span m="2013910">Just</span> <span m="2014300">as</span>
  <span m="2014450">a</span> <span m="2014510">remark,</span> <span m="2015260">it's</span>
  <span m="2016790">not</span> <span m="2017120">required</span> <span m="2018890">that</span>
  <span m="2020900">the</span> <span m="2021020">number</span> <span m="2021410">of</span>
  <span m="2021500">vertices</span> <span m="2024520">goes</span> <span m="2024790">to</span>
  <span m="2024940">infinity,</span> <span m="2026350">although</span> <span m="2027970">you</span>
  <span m="2028120">really</span> <span m="2028340">should</span> <span m="2028500">think</span>
  <span m="2029140">that</span> <span m="2029470">that</span> <span m="2029680">is</span>
  <span m="2029830">the</span> <span m="2029890">case.</span> <span m="2037140">So</span>
  <span m="2037290">just</span> <span m="2037550">to</span> <span m="2038220">put</span>
  <span m="2038400">it</span> <span m="2038490">out</span> <span m="2038610">there--</span>
  <span m="2038720">so</span> <span m="2038940">I</span> <span m="2039000">can</span>
  <span m="2039150">have</span> <span m="2039300">a</span> <span m="2039360">sequence</span>
  <span m="2039780">of</span> <span m="2039840">constant</span> <span m="2040290">graphs</span>
  <span m="2040620">and</span> <span m="2040710">they</span> <span m="2040800">will</span>
  <span m="2040890">still</span> <span m="2041070">be</span> <span m="2041190">convergent.</span>
  <span m="2042000">And</span> <span m="2042300">that's</span> <span m="2042540">still</span>
  <span m="2042860">OK.</span> <span m="2043650">But</span> <span m="2043770">you</span>
  <span m="2043830">should</span> <span m="2043980">think</span> <span m="2044220">of</span>
  <span m="2044340">the</span> <span m="2044430">number</span> <span m="2044700">of</span>
  <span m="2044760">vertices</span> <span m="2045210">going</span> <span m="2045450">to</span>
  <span m="2045540">infinity.</span> <span m="2045980">Yeah?</span></p><p><span m="2046874">AUDIENCE:</span>
  <span m="2047023">What</span> <span m="2047172">is</span> <span m="2047321">F</span>
  <span m="2047768">in the</span> <span m="2048215">definition?</span></p><p><span
  m="2049560">YUFEI ZHAO:</span> <span m="2049615">F</span> <span m="2049670">is</span>
  <span m="2049920">H.</span> <span m="2050600">Thank</span> <span m="2050750">you.</span>
  <span m="2054670">Any</span> <span m="2054820">other</span> <span m="2054969">questions?</span></p><p><span
  m="2072380">So</span> <span m="2072730">there are</span> <span m="2072880">some</span>
  <span m="2073060">questions</span> <span m="2073460">that</span> <span m="2073570">we'd</span>
  <span m="2073659">like</span> <span m="2073810">to</span> <span m="2074320">discuss.</span>
  <span m="2075280">And</span> <span m="2076179">this</span> <span m="2076420">will</span>
  <span m="2076600">occupy</span> <span m="2077050">the</span> <span m="2077170">next</span>
  <span m="2077409">few</span> <span m="2077560">lectures</span> <span m="2077980">in</span>
  <span m="2078100">terms</span> <span m="2078370">of</span> <span m="2078460">proving</span>
  <span m="2078880">the</span> <span m="2079000">following</span> <span m="2079389">statements.</span>
  <span m="2081080">One</span> <span m="2081219">is</span> <span m="2081850">do</span>
  <span m="2082000">you</span> <span m="2082239">always</span> <span m="2082750">have</span>
  <span m="2083320">graph</span> <span m="2083770">limits?</span> <span m="2084699">If</span>
  <span m="2084850">you</span> <span m="2084969">have</span> <span m="2085120">a</span>
  <span m="2085210">convergent</span> <span m="2085929">sequence</span> <span m="2086440">of</span>
  <span m="2086560">graphs,</span> <span m="2088699">do</span> <span m="2088820">they</span>
  <span m="2088969">always</span> <span m="2089870">approach</span> <span m="2090350">a</span>
  <span m="2090409">limit?</span></p><p><span m="2093129">And</span> <span m="2093610">just</span>
  <span m="2093790">because</span> <span m="2094030">something</span> <span m="2094300">is</span>
  <span m="2094420">convergent</span> <span m="2095440">doesn't</span> <span m="2095650">mean</span>
  <span m="2095800">you</span> <span m="2095889">can</span> <span m="2096010">represent</span>
  <span m="2096400">the</span> <span m="2096460">limit</span> <span m="2096850">necessarily.</span>
  <span m="2098670">So</span> <span m="2098790">it</span> <span m="2098860">turns</span>
  <span m="2099050">out</span> <span m="2099170">the</span> <span m="2099260">answer</span>
  <span m="2099500">is</span> <span m="2099620">yes.</span> <span m="2101080">It</span>
  <span m="2101180">turns</span> <span m="2101420">out</span> <span m="2101600">that--</span>
  <span m="2101810">and</span> <span m="2102170">this</span> <span m="2102820">makes</span>
  <span m="2103200">it a</span> <span m="2103670">good</span> <span m="2104000">theory,
  a</span> <span m="2104330">good,</span> <span m="2104700">useful</span> <span m="2105080">theory,</span>
  <span m="2105400">and an</span> <span m="2105500">easy</span> <span m="2105830">theory</span>
  <span m="2106070">to</span> <span m="2106190">use,</span> <span m="2106700">that</span>
  <span m="2107010">there is</span> <span m="2107210">always</span> <span m="2107510">a</span>
  <span m="2107540">limit</span> <span m="2107870">object</span> <span m="2108380">whenever</span>
  <span m="2109010">you</span> <span m="2109130">have</span> <span m="2109310">convergence.</span></p><p><span
  m="2111530">And</span> <span m="2111780">the</span> <span m="2111890">other</span>
  <span m="2112100">question</span> <span m="2112970">is</span> <span m="2114170">while</span>
  <span m="2114360">we have</span> <span m="2115160">described</span> <span m="2116060">intuitively</span>
  <span m="2116720">one</span> <span m="2116930">notion</span> <span m="2117350">of</span>
  <span m="2117440">convergence</span> <span m="2118880">and</span> <span m="2119070">also</span>
  <span m="2119990">defined</span> <span m="2120680">more</span> <span m="2120860">rigorously</span>
  <span m="2121400">another</span> <span m="2122870">definition</span> <span m="2123440">of</span>
  <span m="2123560">convergence,</span> <span m="2124790">are</span> <span m="2124910">these</span>
  <span m="2125150">two</span> <span m="2125360">notions</span> <span m="2125780">compatible?</span>
  <span m="2127370">And</span> <span m="2127490">what</span> <span m="2127610">does</span>
  <span m="2127730">this</span> <span m="2127880">even</span> <span m="2128090">mean,</span>
  <span m="2128940">this</span> <span m="2129020">idea</span> <span m="2129410">of</span>
  <span m="2130130">image</span> <span m="2130730">becoming</span> <span m="2131180">closer</span>
  <span m="2131480">and</span> <span m="2131570">closer</span> <span m="2131900">to</span>
  <span m="2132050">a</span> <span m="2132110">final</span> <span m="2132440">image?</span>
  <span m="2132720">What does</span> <span m="2132820">that</span> <span m="2133020">even</span>
  <span m="2133280">mean?</span> <span m="2134680">So</span> <span m="2134970">these</span>
  <span m="2135150">are</span> <span m="2135240">some</span> <span m="2135390">of</span>
  <span m="2135450">the</span> <span m="2135510">questions that</span> <span m="2135930">I</span>
  <span m="2135960">would</span> <span m="2136050">like</span> <span m="2136200">to</span>
  <span m="2136320">address.</span></p><p><span m="2137290">So</span> <span m="2137970">in</span>
  <span m="2138180">the</span> <span m="2139650">next</span> <span m="2140040">few</span>
  <span m="2140670">things that</span> <span m="2140940">I</span> <span m="2141030">would</span>
  <span m="2141150">like</span> <span m="2141300">to</span> <span m="2141390">discuss,</span>
  <span m="2142440">first,</span> <span m="2142710">I</span> <span m="2142830">want</span>
  <span m="2143040">to</span> <span m="2143100">give</span> <span m="2143340">you</span>
  <span m="2143550">a</span> <span m="2143700">definition</span> <span m="2144870">of</span>
  <span m="2145020">a</span> <span m="2145080">distance</span> <span m="2146370">between</span>
  <span m="2147090">two</span> <span m="2148010">graphons</span> <span m="2148860">or</span>
  <span m="2148950">two</span> <span m="2149190">graphs.</span> <span m="2150390">If</span>
  <span m="2150540">I</span> <span m="2150660">give</span> <span m="2150870">you</span>
  <span m="2151530">two</span> <span m="2151740">graphs,</span> <span m="2152610">how</span>
  <span m="2153330">similar</span> <span m="2154020">or</span> <span m="2154200">dissimilar</span>
  <span m="2154980">are</span> <span m="2155130">they--</span> <span m="2156860">so</span>
  <span m="2157030">that</span> <span m="2157150">we</span> <span m="2157300">have</span>
  <span m="2157540">this</span> <span m="2157750">metric.</span> <span m="2158770">And</span>
  <span m="2158860">then</span> <span m="2159040">we</span> <span m="2159130">can</span>
  <span m="2159250">talk</span> <span m="2159520">about</span> <span m="2159760">convergence</span>
  <span m="2160480">in</span> <span m="2160600">metric</span> <span m="2160960">spaces.</span>
  <span m="2164040">So</span> <span m="2164750">let's</span> <span m="2165620">take</span>
  <span m="2165770">a</span> <span m="2165830">quick</span> <span m="2165980">break.</span></p><p><span
  m="2169610">So</span> <span m="2169760">given</span> <span m="2170120">this</span>
  <span m="2170300">notion</span> <span m="2170720">of</span> <span m="2170810">convergence,</span>
  <span m="2171700">I</span> <span m="2171880">would</span> <span m="2172000">like</span>
  <span m="2172190">to</span> <span m="2172700">define</span> <span m="2173160">the</span>
  <span m="2173250">notion</span> <span m="2173870">of</span> <span m="2174050">distance</span>
  <span m="2174620">between</span> <span m="2174980">graphs</span> <span m="2175940">so</span>
  <span m="2176150">that</span> <span m="2176960">convergence</span> <span m="2177860">corresponds</span>
  <span m="2178520">to</span> <span m="2179750">convergence</span> <span m="2180410">in</span>
  <span m="2180530">the</span> <span m="2180590">metric</span> <span m="2180950">space</span>
  <span m="2181220">sense</span> <span m="2181490">of</span> <span m="2181610">distance</span>
  <span m="2182030">going</span> <span m="2182270">to</span> <span m="2182360">0.</span>
  <span m="2183980">So</span> <span m="2184100">how</span> <span m="2184280">can</span>
  <span m="2184430">we</span> <span m="2184520">define</span> <span m="2184970">distance?</span>
  <span m="2197120">First,</span> <span m="2197420">let</span> <span m="2197510">me</span>
  <span m="2197630">tell</span> <span m="2197780">you</span> <span m="2197840">that</span>
  <span m="2197960">there's</span> <span m="2198170">a</span> <span m="2198230">trivial</span>
  <span m="2198650">way. And</span> <span m="2199000">so</span> <span m="2199160">there's</span>
  <span m="2199340">a</span> <span m="2199400">way</span> <span m="2199580">in</span>
  <span m="2199610">which</span> <span m="2199910">you</span> <span m="2200030">look</span>
  <span m="2200210">at</span> <span m="2200300">that</span> <span m="2200380">definition</span>
  <span m="2200900">and</span> <span m="2200990">produce</span> <span m="2201370">a</span>
  <span m="2201430">distance</span> <span m="2201900">out.</span> <span m="2202830">And</span>
  <span m="2203360">here's</span> <span m="2203600">what</span> <span m="2203720">you</span>
  <span m="2203840">can</span> <span m="2203990">do.</span></p><p><span m="2205800">I</span>
  <span m="2207600">can</span> <span m="2207750">convert</span> <span m="2208170">that</span>
  <span m="2208320">definition</span> <span m="2208860">to</span> <span m="2209070">a</span>
  <span m="2209130">metric</span> <span m="2210000">by</span> <span m="2210240">setting</span>
  <span m="2210930">the</span> <span m="2211020">distance</span> <span m="2219470">between</span>
  <span m="2219980">two</span> <span m="2220310">graphs</span> <span m="2221780">G</span>
  <span m="2222710">and</span> <span m="2222860">G</span> <span m="2223070">prime</span>
  <span m="2224090">to</span> <span m="2224210">be</span> <span m="2225830">the</span>
  <span m="2225920">following</span> <span m="2226370">quantity,</span> <span m="2228750">obtained</span>
  <span m="2230150">by--</span> <span m="2232080">what</span> <span m="2232290">would</span>
  <span m="2232440">I</span> <span m="2232500">like</span> <span m="2232650">to</span>
  <span m="2232740">do?</span> <span m="2232920">I</span> <span m="2232980">would</span>
  <span m="2233070">like</span> <span m="2233190">to</span> <span m="2233310">say</span>
  <span m="2233490">the</span> <span m="2233600">distance</span> <span m="2234030">goes</span>
  <span m="2234270">to</span> <span m="2234360">0</span> <span m="2234750">if</span>
  <span m="2234930">and</span> <span m="2235050">only</span> <span m="2235350">if</span>
  <span m="2237850">the</span> <span m="2239150">homomorphism</span> <span m="2240100">densities,</span>
  <span m="2240900">they are</span> <span m="2241120">all</span> <span m="2241630">close</span>
  <span m="2241960">to</span> <span m="2242080">each</span> <span m="2242230">other.</span>
  <span m="2242660">And</span> <span m="2242930">so</span> <span m="2242950">I</span>
  <span m="2243070">can</span> <span m="2243700">sum</span> <span m="2244060">up</span>
  <span m="2244470">all</span> <span m="2244600">the</span> <span m="2244690">homomorphism</span>
  <span m="2244900">densities</span> <span m="2250290">and</span> <span m="2251010">look</span>
  <span m="2251220">at</span> <span m="2251630">their</span> <span m="2252330">differences</span>
  <span m="2253680">between</span> <span m="2255100">G</span> <span m="2255540">and</span>
  <span m="2255855">G</span> <span m="2256170">prime.</span> <span m="2257220">And</span>
  <span m="2257490">I</span> <span m="2258810">simply</span> <span m="2259410">enumerate</span>
  <span m="2261270">the</span> <span m="2261390">list</span> <span m="2261690">of</span>
  <span m="2261810">all</span> <span m="2262020">possible</span> <span m="2262560">graphs.</span></p><p><span
  m="2275564">I</span> <span m="2276050">want to</span> <span m="2276260">be</span>
  <span m="2276330">just</span> <span m="2276480">slightly</span> <span m="2276780">more</span>
  <span m="2276930">careful</span> <span m="2277290">with</span> <span m="2277410">this</span>
  <span m="2277500">definition</span> <span m="2277950">here</span> <span m="2278160">because</span>
  <span m="2278400">I</span> <span m="2278490">want</span> <span m="2278700">something</span>
  <span m="2279030">which--</span> <span m="2280390">so</span> <span m="2280850">when</span>
  <span m="2281010">I</span> <span m="2281130">write</span> <span m="2281340">this,
  this</span> <span m="2281760">number</span> <span m="2283380">might</span> <span
  m="2283530">be</span> <span m="2283650">infinite</span> <span m="2284280">for</span>
  <span m="2285000">all</span> <span m="2285150">pairs</span> <span m="2285650">G
  and</span> <span m="2285880">G</span> <span m="2286260">prime.</span> <span m="2286770">So</span>
  <span m="2286920">if</span> <span m="2287010">I</span> <span m="2287070">just</span>
  <span m="2287250">add</span> <span m="2289430">a</span> <span m="2289460">scaling</span>
  <span m="2289880">factor</span> <span m="2290300">here,</span> <span m="2290690">then--</span>
  <span m="2292400">and</span> <span m="2292560">this</span> <span m="2293580">is</span>
  <span m="2293640">some</span> <span m="2293850">distance.</span> <span m="2295140">So</span>
  <span m="2295250">this is</span> <span m="2295410">some</span> <span m="2295650">distance.</span>
  <span m="2296340">And</span> <span m="2296460">you</span> <span m="2296580">see</span>
  <span m="2296790">that</span> <span m="2297030">it</span> <span m="2297300">matches</span>
  <span m="2297780">the</span> <span m="2297840">definition</span> <span m="2298320">up</span>
  <span m="2298410">there.</span></p><p><span m="2298890">But</span> <span m="2299550">it's</span>
  <span m="2299790">completely</span> <span m="2300210">useless.</span> <span m="2301050">It</span>
  <span m="2301200">might</span> <span m="2301470">as</span> <span m="2301620">well--</span>
  <span m="2302300">might</span> <span m="2302530">as</span> <span m="2302670">well</span>
  <span m="2302790">not have</span> <span m="2302970">said</span> <span m="2303180">anything</span>
  <span m="2303540">because</span> <span m="2303810">it's</span> <span m="2304420">tautologically</span>
  <span m="2305550">the</span> <span m="2305670">same</span> <span m="2306000">as</span>
  <span m="2306450">what</span> <span m="2306660">happened</span> <span m="2306960">up</span>
  <span m="2307110">there.</span> <span m="2309080">And</span> <span m="2309390">if</span>
  <span m="2309450">I</span> <span m="2309540">give</span> <span m="2309690">you</span>
  <span m="2309780">two</span> <span m="2309930">graphs,</span> <span m="2311010">it</span>
  <span m="2311070">doesn't</span> <span m="2311310">really</span> <span m="2311490">tell</span>
  <span m="2311700">you</span> <span m="2311760">all</span> <span m="2311880">that</span>
  <span m="2312000">much</span> <span m="2312210">information</span> <span m="2312930">except</span>
  <span m="2313260">to</span> <span m="2313950">encapsulate</span> <span m="2314610">that</span>
  <span m="2314820">definition</span> <span m="2315360">into</span> <span m="2315600">a</span>
  <span m="2315660">single</span> <span m="2315960">number.</span> <span m="2317780">Great.</span>
  <span m="2318090">So</span> <span m="2318300">I'm</span> <span m="2318420">just--</span>
  <span m="2318840">the</span> <span m="2318930">point</span> <span m="2319170">of</span>
  <span m="2319260">this</span> <span m="2319440">is</span> <span m="2319620">just</span>
  <span m="2320250">to</span> <span m="2320310">tell</span> <span m="2320550">you</span>
  <span m="2320730">that</span> <span m="2321570">there</span> <span m="2322940">is</span>
  <span m="2323100">always</span> <span m="2323370">a</span> <span m="2323400">trivial</span>
  <span m="2323820">way</span> <span m="2323970">to</span> <span m="2324060">define</span>
  <span m="2324420">distance.</span></p><p><span m="2325470">But</span> <span m="2325620">we</span>
  <span m="2325740">want</span> <span m="2325920">some</span> <span m="2326100">more</span>
  <span m="2326250">interesting</span> <span m="2326700">ways.</span> <span m="2329160">So</span>
  <span m="2329250">what</span> <span m="2329370">can</span> <span m="2329520">we</span>
  <span m="2329610">do?</span> <span m="2331920">So</span> <span m="2331980">here
  is</span> <span m="2332220">an</span> <span m="2332310">attempt,</span> <span m="2333360">which</span>
  <span m="2333570">is</span> <span m="2334320">that</span> <span m="2334500">of</span>
  <span m="2334590">an</span> <span m="2334800">edit</span> <span m="2335040">distance.</span>
  <span m="2338690">So</span> <span m="2339160">we have</span> <span m="2339300">seen</span>
  <span m="2339510">this</span> <span m="2339660">before</span> <span m="2339960">when</span>
  <span m="2340140">we</span> <span m="2340260">discussed</span> <span m="2340730">removal</span>
  <span m="2341130">lemmas.</span></p><p><span m="2341460">The</span> <span m="2341580">edit</span>
  <span m="2341850">distance</span> <span m="2342630">is</span> <span m="2342810">the</span>
  <span m="2342900">number</span> <span m="2343350">of</span> <span m="2343470">edges</span>
  <span m="2344250">you</span> <span m="2344340">need</span> <span m="2344490">to</span>
  <span m="2344580">change</span> <span m="2345810">to</span> <span m="2346110">go</span>
  <span m="2346290">from</span> <span m="2346500">one</span> <span m="2346680">graph</span>
  <span m="2347010">to</span> <span m="2347100">the</span> <span m="2347220">other</span>
  <span m="2347370">graph.</span> <span m="2349780">And</span> <span m="2349880">this</span>
  <span m="2349960">seems</span> <span m="2350170">like</span> <span m="2350350">a</span>
  <span m="2350380">pretty</span> <span m="2350620">reasonable</span> <span m="2351100">thing</span>
  <span m="2351280">to</span> <span m="2351370">do.</span> <span m="2352060">And</span>
  <span m="2352420">it</span> <span m="2352570">is</span> <span m="2353140">an</span>
  <span m="2353260">important</span> <span m="2353650">quantity</span> <span m="2354070">for</span>
  <span m="2354220">many</span> <span m="2354430">applications,</span> <span m="2356240">but</span>
  <span m="2356350">turns</span> <span m="2356560">out</span> <span m="2356660">not</span>
  <span m="2357250">the</span> <span m="2357370">right</span> <span m="2357640">one</span>
  <span m="2357910">for</span> <span m="2358270">all</span> <span m="2358450">application.</span>
  <span m="2359970">And</span> <span m="2360070">here is</span> <span m="2360250">the</span>
  <span m="2360310">reason.</span> <span m="2361840">So</span> <span m="2362050">this</span>
  <span m="2362260">is</span> <span m="2362440">why</span> <span m="2363280">the</span>
  <span m="2363430">edit</span> <span m="2363660">distance</span> <span m="2364390">is--</span>
  <span m="2365960">by</span> <span m="2367030">edit</span> <span m="2367600">distance,</span>
  <span m="2368120">I</span> <span m="2368220">mean</span> <span m="2368650">1</span>
  <span m="2369070">over</span> <span m="2369610">the</span> <span m="2369700">number</span>
  <span m="2370180">of</span> <span m="2373780">vertex</span> <span m="2374290">squared</span>
  <span m="2375370">times</span> <span m="2375820">the</span> <span m="2375940">number</span>
  <span m="2376360">of</span> <span m="2377110">edge</span> <span m="2377560">changes</span>
  <span m="2378130">needed.</span></p><p><span m="2383500">So</span> <span m="2383520">there's</span>
  <span m="2383700">normalization</span> <span m="2384370">so</span> <span m="2384480">that
  the</span> <span m="2384660">distance</span> <span m="2385050">is</span> <span m="2385170">always</span>
  <span m="2385440">between</span> <span m="2385800">0</span> <span m="2386130">and</span>
  <span m="2386250">1.</span> <span m="2387310">But</span> <span m="2387360">this</span>
  <span m="2387510">is</span> <span m="2387600">not</span> <span m="2387870">a</span>
  <span m="2387930">very</span> <span m="2388110">good</span> <span m="2388260">notion</span>
  <span m="2388890">for</span> <span m="2389040">the</span> <span m="2389130">following</span>
  <span m="2389580">reason.</span> <span m="2391420">If</span> <span m="2391470">I</span>
  <span m="2391560">take</span> <span m="2392250">two</span> <span m="2392520">copies</span>
  <span m="2395670">of</span> <span m="2397110">the</span> <span m="2397260">Erdos-Reyni</span>
  <span m="2397920">random</span> <span m="2398220">graph</span> <span m="2398580">G,
  n,</span> <span m="2398970">1/2,</span> <span m="2401960">what</span> <span m="2402140">do</span>
  <span m="2402200">you</span> <span m="2402260">think</span> <span m="2402480">is</span>
  <span m="2402620">the</span> <span m="2402840">edit</span> <span m="2403000">distance</span>
  <span m="2403460">between</span> <span m="2403880">two</span> <span m="2404180">such</span>
  <span m="2404540">random</span> <span m="2404900">graphs?</span> <span m="2410440">How</span>
  <span m="2410590">many</span> <span m="2410830">edges?</span> <span m="2411370">Yeah?</span></p><p><span
  m="2411580">AUDIENCE:</span> <span m="2411826">Isn't</span> <span m="2411908">it</span>
  <span m="2411990">roughly</span> <span m="2412073">one-half of</span> <span m="2412566">the</span>
  <span m="2413059">number of</span> <span m="2413552">edges</span> <span m="2414045">because</span>
  <span m="2414168">there's</span> <span m="2414291">like</span> <span m="2414414">a</span>
  <span m="2414538">one-half</span> <span m="2415031">probably</span> <span m="2415524">that</span>
  <span m="2416510">won't</span> <span m="2417003">be there</span> <span m="2417496">or
  not</span> <span m="2417989">be there</span> <span m="2418482">[INAUDIBLE]?</span></p><p><span
  m="2421440">YUFEI ZHAO:</span> <span m="2421567">So</span> <span m="2422540">yeah,</span>
  <span m="2422720">so</span> <span m="2423060">let</span> <span m="2423150">me</span>
  <span m="2423270">try</span> <span m="2423390">to</span> <span m="2423480">rephrase</span>
  <span m="2423900">what</span> <span m="2424020">you are</span> <span m="2424140">saying.</span>
  <span m="2424440">So</span> <span m="2424620">suppose</span> <span m="2425520">I</span>
  <span m="2425670">have</span> <span m="2426000">this</span> <span m="2426450">G</span>
  <span m="2426840">and</span> <span m="2426990">G</span> <span m="2427170">prime</span>
  <span m="2429680">both</span> <span m="2430550">sitting</span> <span m="2431000">on</span>
  <span m="2431120">top</span> <span m="2431540">of</span> <span m="2433520">the</span>
  <span m="2433610">vertex</span> <span m="2434000">set</span> <span m="2435290">n.</span>
  <span m="2437850">So</span> <span m="2437970">if</span> <span m="2438090">I'm</span>
  <span m="2438210">not</span> <span m="2438480">allowed</span> <span m="2438780">to</span>
  <span m="2439170">rearrange</span> <span m="2439800">the</span> <span m="2439920">vertices,</span>
  <span m="2440790">how</span> <span m="2441090">many</span> <span m="2441630">edge</span>
  <span m="2441870">changes</span> <span m="2442380">do</span> <span m="2442530">I</span>
  <span m="2442620">need</span> <span m="2443220">to</span> <span m="2443340">go</span>
  <span m="2443550">from</span> <span m="2443790">one</span> <span m="2444000">to</span>
  <span m="2444150">the</span> <span m="2444270">other?</span> <span m="2445860">I</span>
  <span m="2445950">need</span> <span m="2446210">about</span> <span m="2447390">1/2.</span></p><p><span
  m="2461890">So</span> <span m="2462540">one-half</span> <span m="2463080">the</span>
  <span m="2463170">time,</span> <span m="2463590">I'm</span> <span m="2463700">going</span>
  <span m="2463790">to</span> <span m="2463920">have</span> <span m="2464040">a</span>
  <span m="2464100">wrong</span> <span m="2464640">edge</span> <span m="2464850">there.</span>
  <span m="2465910">Now</span> <span m="2466000">you</span> <span m="2466110">can</span>
  <span m="2466260">make</span> <span m="2466440">this</span> <span m="2466590">number</span>
  <span m="2466860">just</span> <span m="2467820">slightly</span> <span m="2468330">smaller</span>
  <span m="2469020">by</span> <span m="2470310">permuting</span> <span m="2470760">the</span>
  <span m="2470850">vertices.</span> <span m="2471330">But</span> <span m="2471510">actually</span>
  <span m="2471780">you</span> <span m="2471900">will</span> <span m="2472080">not</span>
  <span m="2472530">improve</span> <span m="2472920">that</span> <span m="2473100">much.</span>
  <span m="2473490">It</span> <span m="2473750">is</span> <span m="2473880">still</span>
  <span m="2474120">going</span> <span m="2474360">to</span> <span m="2474450">be</span>
  <span m="2474600">roughly</span> <span m="2475560">that</span> <span m="2475860">edit</span>
  <span m="2476070">distance,</span> <span m="2476880">which</span> <span m="2477060">is</span>
  <span m="2477210">quite</span> <span m="2477780">large.</span> <span m="2478560">This</span>
  <span m="2478590">is</span> <span m="2478800">almost</span> <span m="2481230">as</span>
  <span m="2481380">large</span> <span m="2481620">as</span> <span m="2481710">you</span>
  <span m="2481800">can</span> <span m="2481920">possibly</span> <span m="2482340">get</span>
  <span m="2482520">between</span> <span m="2482790">two</span> <span m="2483000">arbitrary</span>
  <span m="2483420">graphs.</span></p><p><span m="2485960">So</span> <span m="2487570">if</span>
  <span m="2487720">we</span> <span m="2487840">want</span> <span m="2488170">to</span>
  <span m="2488260">say</span> <span m="2488710">that</span> <span m="2489280">random</span>
  <span m="2489880">graphs,</span> <span m="2490510">they</span> <span m="2490900">approach</span>
  <span m="2491560">a</span> <span m="2491770">limit,</span> <span m="2492310">a</span>
  <span m="2492370">single</span> <span m="2492790">limit,</span> <span m="2493660">then</span>
  <span m="2493900">this</span> <span m="2494080">is</span> <span m="2494200">not</span>
  <span m="2494500">a</span> <span m="2494530">very</span> <span m="2494740">good</span>
  <span m="2494920">notion</span> <span m="2496020">because</span> <span m="2496430">they</span>
  <span m="2496530">are</span> <span m="2496630">quite</span> <span m="2497020">far</span>
  <span m="2497320">apart</span> <span m="2497650">for</span> <span m="2497800">every</span>
  <span m="2498030">n.</span> <span m="2501120">So</span> <span m="2501690">this</span>
  <span m="2501930">is</span> <span m="2502320">the</span> <span m="2502410">reason</span>
  <span m="2502710">why</span> <span m="2503040">the</span> <span m="2503580">more</span>
  <span m="2503880">obvious</span> <span m="2504540">suggestion</span> <span m="2505110">of</span>
  <span m="2505230">an</span> <span m="2505440">edit</span> <span m="2505650">distance</span>
  <span m="2506100">might</span> <span m="2506280">not</span> <span m="2506460">be</span>
  <span m="2506760">such</span> <span m="2507030">a</span> <span m="2507090">great</span>
  <span m="2507300">idea.</span> <span m="2509590">So</span> <span m="2509640">what</span>
  <span m="2509780">should</span> <span m="2509860">we</span> <span m="2509940">use</span>
  <span m="2510300">instead?</span> <span m="2511700">So</span> <span m="2511830">we</span>
  <span m="2511980">should</span> <span m="2512130">take</span> <span m="2512370">inspiration</span>
  <span m="2513420">from</span> <span m="2514350">what</span> <span m="2514530">we</span>
  <span m="2514650">discussed</span> <span m="2515370">in</span> <span m="2516000">quasirandomness.</span>
  <span m="2516595">You</span> <span m="2516860">have a</span> <span m="2517200">question.</span></p><p><span
  m="2518416">AUDIENCE:</span> <span m="2518652">Is the edit</span> <span m="2518889">distance</span>
  <span m="2519362">only for</span> <span m="2520308">two</span> <span m="2520781">graphs
  of</span> <span m="2521254">the</span> <span m="2521727">same</span> <span m="2522200">vertex</span>
  <span m="2522673">set?</span></p><p><span m="2523390">YUFEI ZHAO:</span> <span m="2523435">So</span>
  <span m="2523480">the</span> <span m="2523540">question</span> <span m="2523780">is,</span>
  <span m="2523930">is</span> <span m="2524080">the</span> <span m="2524170">edit</span>
  <span m="2524380">distance</span> <span m="2524800">only</span> <span m="2525040">for</span>
  <span m="2525310">two</span> <span m="2525550">graphs</span> <span m="2525880">with</span>
  <span m="2526000">the</span> <span m="2526060">same</span> <span m="2526330">vertex</span>
  <span m="2526770">set?</span> <span m="2527480">Let's</span> <span m="2527530">say</span>
  <span m="2527680">yes.</span> <span m="2528280">So</span> <span m="2528580">we'll</span>
  <span m="2528820">see</span> <span m="2529090">later</span> <span m="2529360">on,</span>
  <span m="2529960">you</span> <span m="2530080">can</span> <span m="2530260">also</span>
  <span m="2530500">compare</span> <span m="2530980">graphs</span> <span m="2531640">with</span>
  <span m="2531850">different</span> <span m="2533560">number</span> <span m="2533890">of</span>
  <span m="2533950">vertices.</span> <span m="2535580">So</span> <span m="2535840">hold</span>
  <span m="2536050">onto</span> <span m="2536230">that</span> <span m="2536380">thought.</span></p><p><span
  m="2538540">So</span> <span m="2538750">I</span> <span m="2538830">would</span>
  <span m="2538930">like</span> <span m="2539140">to</span> <span m="2539260">come</span>
  <span m="2539530">up</span> <span m="2539680">with</span> <span m="2539890">a</span>
  <span m="2539950">notion</span> <span m="2540670">of</span> <span m="2541000">distance</span>
  <span m="2541480">between</span> <span m="2541780">graphs</span> <span m="2542440">that</span>
  <span m="2542620">is</span> <span m="2542740">inspired</span> <span m="2543520">by</span>
  <span m="2543850">our</span> <span m="2544060">discussion</span> <span m="2544660">of</span>
  <span m="2544750">quasirandomness</span> <span m="2545960">earlier.</span> <span
  m="2548120">So</span> <span m="2548270">think</span> <span m="2548480">about</span>
  <span m="2549350">the</span> <span m="2549440">discussion</span> <span m="2549950">of</span>
  <span m="2550010">quasirandomness</span> <span m="2553965">or</span> <span m="2554360">quasirandom</span>
  <span m="2555020">graphs.</span> <span m="2562920">In</span> <span m="2563040">what</span>
  <span m="2563280">sense</span> <span m="2568760">can</span> <span m="2569810">G</span>
  <span m="2570740">be</span> <span m="2571100">close</span> <span m="2572990">to</span>
  <span m="2573800">a</span> <span m="2573890">constant,</span> <span m="2575590">let's</span>
  <span m="2575750">say</span> <span m="2576430">p?</span> <span m="2579300">And</span>
  <span m="2579740">so</span> <span m="2579870">this was</span> <span m="2580280">the</span>
  <span m="2581780">Chung-Graham-Wilson</span> <span m="2582690">theorem</span> <span
  m="2583050">that</span> <span m="2583200">we</span> <span m="2583350">proved</span>
  <span m="2583710">a</span> <span m="2583770">few</span> <span m="2583950">lectures</span>
  <span m="2584340">ago.</span> <span m="2585460">So</span> <span m="2585540">in</span>
  <span m="2585690">what</span> <span m="2585840">sense</span> <span m="2586110">can
  G</span> <span m="2586510">be</span> <span m="2586680">close</span> <span m="2587040">to</span>
  <span m="2587130">p?</span></p><p><span m="2587790">And</span> <span m="2588180">one</span>
  <span m="2588450">of</span> <span m="2588570">those</span> <span m="2588780">definitions</span>
  <span m="2589380">was</span> <span m="2589740">discrepancy.</span> <span m="2596570">And</span>
  <span m="2596720">discrepancy</span> <span m="2598160">says</span> <span m="2598490">that</span>
  <span m="2598820">if</span> <span m="2599060">the</span> <span m="2599180">following</span>
  <span m="2599630">quantity</span> <span m="2605840">is</span> <span m="2606350">small</span>
  <span m="2608420">for</span> <span m="2608660">all</span> <span m="2609380">subsets</span>
  <span m="2610130">x</span> <span m="2610370">and</span> <span m="2610460">y,</span>
  <span m="2611430">which</span> <span m="2611540">are</span> <span m="2612470">subsets</span>
  <span m="2612950">of</span> <span m="2613010">vertices</span> <span m="2613490">of</span>
  <span m="2613580">G--</span> <span m="2614370">so</span> <span m="2614720">you</span>
  <span m="2614780">remember,</span> <span m="2615320">all</span> <span m="2615440">of</span>
  <span m="2615560">you</span> <span m="2615620">remember,</span> <span m="2616840">this</span>
  <span m="2617120">part,</span> <span m="2617390">the</span> <span m="2617540">discrepancy</span>
  <span m="2618290">hypothesis</span> <span m="2619200">for</span> <span m="2619460">quasirandomness.</span>
  <span m="2621550">And</span> <span m="2621710">this</span> <span m="2621890">is</span>
  <span m="2621960">a</span> <span m="2622040">kind</span> <span m="2622370">of</span>
  <span m="2622490">definition</span> <span m="2623000">that</span> <span m="2623120">we</span>
  <span m="2623240">would</span> <span m="2623390">like</span> <span m="2623720">to</span>
  <span m="2623870">describe</span> <span m="2624470">when</span> <span m="2624830">two</span>
  <span m="2625160">graphs</span> <span m="2625520">are</span> <span m="2625590">similar</span>
  <span m="2625970">to</span> <span m="2626120">each</span> <span m="2626330">other,</span>
  <span m="2627170">when</span> <span m="2627380">they</span> <span m="2628280">are</span>
  <span m="2628400">close</span> <span m="2629300">in</span> <span m="2629450">this</span>
  <span m="2630080">discrepancy</span> <span m="2630750">sense.</span></p><p><span
  m="2632270">So</span> <span m="2632510">now,</span> <span m="2633320">instead</span>
  <span m="2633680">of</span> <span m="2634160">a</span> <span m="2634220">graph</span>
  <span m="2635100">and</span> <span m="2635290">a</span> <span m="2635360">number,</span>
  <span m="2636410">what</span> <span m="2636590">if</span> <span m="2636710">now</span>
  <span m="2636920">I</span> <span m="2636980">have</span> <span m="2637310">two</span>
  <span m="2637550">graphs?</span> <span m="2639280">I'll</span> <span m="2639370">give</span>
  <span m="2639520">you</span> <span m="2639610">two</span> <span m="2639760">graphs</span>
  <span m="2641500">of</span> <span m="2642420">G</span> <span m="2643780">and</span>
  <span m="2643970">G</span> <span m="2644180">prime.</span> <span m="2645820">And</span>
  <span m="2646010">what</span> <span m="2646250">I</span> <span m="2646400">would</span>
  <span m="2646580">like</span> <span m="2646760">to</span> <span m="2646880">say</span>
  <span m="2648480">is</span> <span m="2648630">that,</span> <span m="2649260">if</span>
  <span m="2651250">for</span> <span m="2651420">now,</span> <span m="2651750">so</span>
  <span m="2651930">if</span> <span m="2652140">they</span> <span m="2653690">have</span>
  <span m="2655520">the</span> <span m="2655610">same</span> <span m="2656990">vertex</span>
  <span m="2657470">set,</span> <span m="2661490">I</span> <span m="2661590">want</span>
  <span m="2661770">to</span> <span m="2661830">say</span> <span m="2662010">that</span>
  <span m="2662160">there</span> <span m="2662240">are</span> <span m="2662310">close</span>
  <span m="2669670">if</span> <span m="2671630">I</span> <span m="2672130">have</span>
  <span m="2672460">that</span> <span m="2672900">the</span> <span m="2673000">number</span>
  <span m="2673420">of</span> <span m="2673600">edges</span> <span m="2673990">between</span>
  <span m="2675010">x</span> <span m="2675220">and</span> <span m="2675310">y</span>
  <span m="2675760">in</span> <span m="2675940">G</span> <span m="2677170">is</span>
  <span m="2677470">very</span> <span m="2677770">close</span> <span m="2678730">to</span>
  <span m="2680020">the</span> <span m="2680140">number</span> <span m="2680560">of</span>
  <span m="2681890">edges</span> <span m="2682390">between</span> <span m="2683110">x</span>
  <span m="2683320">and</span> <span m="2683410">y</span> <span m="2683650">in</span>
  <span m="2683800">G</span> <span m="2684010">prime.</span> <span m="2686860">And</span>
  <span m="2687090">I</span> <span m="2687240">normalize</span> <span m="2688170">by</span>
  <span m="2690450">the</span> <span m="2691020">number</span> <span m="2691350">of</span>
  <span m="2691740">vertices</span> <span m="2692430">squared,</span> <span m="2695245">so</span>
  <span m="2695720">n</span> <span m="2695870">this</span> <span m="2695990">number
  of</span> <span m="2696270">vertices.</span></p><p><span m="2698040">And</span>
  <span m="2698200">I</span> <span m="2698290">would</span> <span m="2698380">like</span>
  <span m="2698530">to</span> <span m="2699190">find</span> <span m="2699490">out</span>
  <span m="2699610">the</span> <span m="2699700">worst</span> <span m="2700060">possible</span>
  <span m="2700510">scenario,</span> <span m="2701660">so</span> <span m="2701800">overall,</span>
  <span m="2702790">x</span> <span m="2702970">and</span> <span m="2703060">y</span>
  <span m="2703720">subsets</span> <span m="2704320">of</span> <span m="2704830">the</span>
  <span m="2704920">vertex</span> <span m="2705310">set.</span> <span m="2707130">If</span>
  <span m="2707300">this</span> <span m="2707480">quantity</span> <span m="2707900">is</span>
  <span m="2708020">small,</span> <span m="2712380">then</span> <span m="2712470">I</span>
  <span m="2712580">would</span> <span m="2712730">like</span> <span m="2712880">to</span>
  <span m="2712970">say</span> <span m="2713150">that G</span> <span m="2713270">and
  G</span> <span m="2713700">prime</span> <span m="2714040">are</span> <span m="2714110">close</span>
  <span m="2714470">to</span> <span m="2714590">each</span> <span m="2714770">other.</span>
  <span m="2718240">So</span> <span m="2718320">this</span> <span m="2718500">is</span>
  <span m="2718590">inspired</span> <span m="2719220">by</span> <span m="2719610">this</span>
  <span m="2719820">discrepancy</span> <span m="2720420">notion.</span> <span m="2724850">Can</span>
  <span m="2725000">you</span> <span m="2725060">see</span> <span m="2725210">anything</span>
  <span m="2725480">wrong</span> <span m="2725690">with</span> <span m="2725870">this</span>
  <span m="2726020">definition</span> <span m="2726470">here?</span> <span m="2728149">Yeah?</span></p><p><span
  m="2728642">AUDIENCE:</span> <span m="2728888">[INAUDIBLE]</span></p><p><span m="2730620">YUFEI
  ZHAO:</span> <span m="2730700">So</span> <span m="2730780">permutations</span> <span
  m="2731500">are</span> <span m="2731580">vertices.</span> <span m="2733230">So</span>
  <span m="2734020">just</span> <span m="2734260">like</span> <span m="2734470">in</span>
  <span m="2734590">the</span> <span m="2734680">checkerboard</span> <span m="2735190">example</span>
  <span m="2735580">we</span> <span m="2735670">saw</span> <span m="2735850">earlier,</span>
  <span m="2737140">you</span> <span m="2737260">have</span> <span m="2737470">two</span>
  <span m="2737680">graphs.</span> <span m="2738460">And</span> <span m="2738850">if</span>
  <span m="2739090">they</span> <span m="2739230">are</span> <span m="2739330">indeed</span>
  <span m="2739930">labeled</span> <span m="2740470">graphs</span> <span m="2740860">in</span>
  <span m="2740950">the</span> <span m="2741010">same</span> <span m="2741700">labeled</span>
  <span m="2742130">vertex</span> <span m="2742440">set,</span> <span m="2743180">then</span>
  <span m="2743710">this</span> <span m="2743920">is</span> <span m="2744680">the</span>
  <span m="2744760">definition</span> <span m="2745660">more</span> <span m="2745810">or</span>
  <span m="2745840">less what we</span> <span m="2746230">used.</span> <span m="2746470">I
  will</span> <span m="2746720">define</span> <span m="2746860">it</span> <span m="2747070">more</span>
  <span m="2747220">precisely</span> <span m="2747670">in</span> <span m="2747760">a</span>
  <span m="2747820">second.</span> <span m="2748600">But</span> <span m="2748840">if</span>
  <span m="2749630">they are</span> <span m="2749860">unlabeled</span> <span m="2750460">vertices,</span>
  <span m="2751690">we</span> <span m="2751780">need</span> <span m="2751930">to</span>
  <span m="2753720">possibly</span> <span m="2754620">optimize</span> <span m="2760400">permutations</span>
  <span m="2761480">over</span> <span m="2763160">rearrangements</span> <span m="2764060">of</span>
  <span m="2764180">vertices,</span> <span m="2771720">which</span> <span m="2771930">actually</span>
  <span m="2772140">turns</span> <span m="2772350">out</span> <span m="2772470">to</span>
  <span m="2772530">be</span> <span m="2772650">quite</span> <span m="2772920">subtle.</span></p><p><span
  m="2773630">So</span> <span m="2774330">I'm</span> <span m="2774440">going</span>
  <span m="2774540">to</span> <span m="2774660">give</span> <span m="2774780">precise</span>
  <span m="2775170">definitions</span> <span m="2775710">in</span> <span m="2775810">a</span>
  <span m="2775860">second.</span> <span m="2776160">But</span> <span m="2776280">this</span>
  <span m="2776490">one</span> <span m="2776700">here,</span> <span m="2777480">so</span>
  <span m="2777600">think</span> <span m="2777860">about</span> <span m="2778650">permuting</span>
  <span m="2779100">vertices.</span> <span m="2779460">But</span> <span m="2779820">it's</span>
  <span m="2779940">actually</span> <span m="2780180">a bit</span> <span m="2780330">more</span>
  <span m="2780480">subtle</span> <span m="2780750">than</span> <span m="2780930">that.</span></p><p><span
  m="2786680">So</span> <span m="2786830">here</span> <span m="2787010">are</span>
  <span m="2787040">some</span> <span m="2787610">actual</span> <span m="2787880">definitions.</span>
  <span m="2790750">I'm</span> <span m="2790900">going</span> <span m="2791170">to</span>
  <span m="2791530">define</span> <span m="2792940">this</span> <span m="2793150">quantity</span>
  <span m="2793540">called</span> <span m="2793780">a</span> <span m="2793810">cut</span>
  <span m="2794330">norm.</span> <span m="2799490">So</span> <span m="2799610">this</span>
  <span m="2799820">chapter</span> <span m="2800300">is</span> <span m="2800450">all</span>
  <span m="2800780">going</span> <span m="2800960">to</span> <span m="2801050">be</span>
  <span m="2801230">somewhat</span> <span m="2802070">functional</span> <span m="2802640">analytic</span>
  <span m="2803360">in</span> <span m="2803480">nature.</span> <span m="2804570">So</span>
  <span m="2805600">get</span> <span m="2805760">used</span> <span m="2805970">to</span>
  <span m="2806060">the</span> <span m="2806510">analytic</span> <span m="2806990">language.</span></p><p><span
  m="2807680">So</span> <span m="2807830">the</span> <span m="2807950">cut</span>
  <span m="2808310">norm</span> <span m="2808670">of</span> <span m="2810720">W</span>
  <span m="2815160">is</span> <span m="2815490">defined</span> <span m="2815880">to</span>
  <span m="2816000">be</span> <span m="2816540">the</span> <span m="2816660">following</span>
  <span m="2817050">quantity</span> <span m="2817560">denoted</span> <span m="2818760">by</span>
  <span m="2819090">this</span> <span m="2819330">norm</span> <span m="2819720">with</span>
  <span m="2819900">a</span> <span m="2819960">box</span> <span m="2820590">in</span>
  <span m="2820680">the</span> <span m="2820770">subscript,</span> <span m="2822330">which</span>
  <span m="2822510">is</span> <span m="2822600">defined</span> <span m="2823020">to</span>
  <span m="2823170">be--</span> <span m="2824860">if</span> <span m="2825040">I</span>
  <span m="2825250">look</span> <span m="2825540">at</span> <span m="2826330">this</span>
  <span m="2826750">W,</span> <span m="2827640">and</span> <span m="2827780">I</span>
  <span m="2828010">integrate</span> <span m="2828370">it</span> <span m="2828730">over</span>
  <span m="2829870">a</span> <span m="2829960">box,</span> <span m="2831910">and</span>
  <span m="2832130">I would</span> <span m="2832270">like</span> <span m="2832450">to</span>
  <span m="2833020">maximize</span> <span m="2833860">this</span> <span m="2834040">quantity</span>
  <span m="2834430">here</span> <span m="2835420">over</span> <span m="2835720">choices</span>
  <span m="2836440">of</span> <span m="2837280">boxes</span> <span m="2837940">S and</span>
  <span m="2838380">T,</span> <span m="2839390">they</span> <span m="2839590">are</span>
  <span m="2839830">subsets</span> <span m="2840460">of</span> <span m="2840580">the</span>
  <span m="2840880">interval</span> <span m="2841780">measurable</span> <span m="2842260">subsets.</span>
  <span m="2847390">So</span> <span m="2848410">choose</span> <span m="2848830">your--</span>
  <span m="2849730">so</span> <span m="2850590">over</span> <span m="2850870">all</span>
  <span m="2850990">possible</span> <span m="2851440">choices</span> <span m="2851950">of</span>
  <span m="2852730">measurable</span> <span m="2853300">subsets</span> <span m="2854070">S</span>
  <span m="2854360">and T,</span> <span m="2855790">if</span> <span m="2855940">I</span>
  <span m="2856630">integrate</span> <span m="2857050">W</span> <span m="2857410">over</span>
  <span m="2857970">S</span> <span m="2858120">cross</span> <span m="2858420">T,</span>
  <span m="2859330">what</span> <span m="2859510">is</span> <span m="2859630">the</span>
  <span m="2860200">furthest</span> <span m="2860650">I</span> <span m="2860710">can</span>
  <span m="2860860">get</span> <span m="2861100">from</span> <span m="2861400">0?</span>
  <span m="2867480">So</span> <span m="2867570">this</span> <span m="2867720">is</span>
  <span m="2867780">the</span> <span m="2867810">definition</span> <span m="2868260">of</span>
  <span m="2868320">cut</span> <span m="2868620">norm.</span> <span m="2868700">And</span>
  <span m="2868890">you</span> <span m="2868950">can</span> <span m="2869520">already</span>
  <span m="2869850">see</span> <span m="2870150">that it</span> <span m="2870390">has</span>
  <span m="2870600">some</span> <span m="2870810">relations</span> <span m="2871290">to</span>
  <span m="2871380">what</span> <span m="2871550">were</span> <span m="2871750">discussed</span>
  <span m="2872190">up</span> <span m="2872340">there.</span></p><p><span m="2873100">But</span>
  <span m="2873530">while</span> <span m="2873780">we're</span> <span m="2873960">talking</span>
  <span m="2874290">about</span> <span m="2874500">norms,</span> <span m="2874920">let</span>
  <span m="2875040">me</span> <span m="2875130">just</span> <span m="2875310">mention</span>
  <span m="2875670">a</span> <span m="2875730">few</span> <span m="2875970">other</span>
  <span m="2876210">norms</span> <span m="2876570">that</span> <span m="2876690">might</span>
  <span m="2876840">come</span> <span m="2877080">up</span> <span m="2877980">later</span>
  <span m="2878220">on</span> <span m="2878400">when</span> <span m="2878520">we</span>
  <span m="2878640">discuss</span> <span m="2879180">graph</span> <span m="2879480">limits.</span>
  <span m="2880950">So</span> <span m="2881130">there</span> <span m="2881250">will</span>
  <span m="2881370">be</span> <span m="2882060">a</span> <span m="2882120">lot</span>
  <span m="2882360">of</span> <span m="2882450">norms</span> <span m="2882840">throughout.</span>
  <span m="2883920">So</span> <span m="2884670">in</span> <span m="2884790">particular,</span>
  <span m="2885310">the</span> <span m="2885970">lp</span> <span m="2886430">norm</span>
  <span m="2887180">is</span> <span m="2887490">going</span> <span m="2887670">to</span>
  <span m="2888270">play</span> <span m="2888510">a</span> <span m="2888570">frequent</span>
  <span m="2888900">role.</span> <span m="2889440">So</span> <span m="2889530">lp</span>
  <span m="2889680">norm</span> <span m="2890610">is</span> <span m="2890880">defined</span>
  <span m="2893370">by</span> <span m="2893520">looking</span> <span m="2893850">at</span>
  <span m="2893970">the</span> <span m="2894565">peak</span> <span m="2894890">norm</span>
  <span m="2895170">of</span> <span m="2895230">the</span> <span m="2895350">absolute</span>
  <span m="2895800">value,</span> <span m="2896710">integrated</span> <span m="2897450">and</span>
  <span m="2897560">then</span> <span m="2897690">raised</span> <span m="2897990">to</span>
  <span m="2898140">1</span> <span m="2898330">over</span> <span m="2898480">p.</span>
  <span m="2900960">And</span> <span m="2903940">so</span> <span m="2904160">the</span>
  <span m="2904340">infinity</span> <span m="2904940">norm--</span> <span m="2906500">so</span>
  <span m="2906620">this</span> <span m="2906830">is</span> <span m="2907850">almost,</span>
  <span m="2908370">but</span> <span m="2908390">not</span> <span m="2908630">quite</span>
  <span m="2909140">the</span> <span m="2909290">same</span> <span m="2909770">as</span>
  <span m="2910040">the</span> <span m="2910160">sup--</span> <span m="2914940">so</span>
  <span m="2915330">almost</span> <span m="2915690">the</span> <span m="2915780">same</span>
  <span m="2916140">as</span> <span m="2916290">the</span> <span m="2916380">supremum,</span>
  <span m="2917520">but</span> <span m="2917640">not</span> <span m="2917940">quite</span>
  <span m="2918840">because</span> <span m="2919590">I</span> <span m="2919710">need</span>
  <span m="2919890">to</span> <span m="2920850">ignore</span> <span m="2922670">subsets</span>
  <span m="2923430">of</span> <span m="2923520">measure</span> <span m="2923850">0.</span></p><p><span
  m="2934940">So</span> <span m="2935620">I</span> <span m="2935650">can</span> <span
  m="2935800">write</span> <span m="2935970">down</span> <span m="2936100">a</span>
  <span m="2936250">formal</span> <span m="2936610">definition</span> <span m="2936930">in</span>
  <span m="2937250">a second.</span> <span m="2937760">But</span> <span m="2938170">I</span>
  <span m="2938290">need</span> <span m="2938440">to--</span> <span m="2939470">if</span>
  <span m="2939520">I</span> <span m="2939610">change</span> <span m="2939970">W</span>
  <span m="2940360">on</span> <span m="2940490">the</span> <span m="2940540">subset
  of</span> <span m="2940900">the</span> <span m="2940960">measure</span> <span m="2941240">0,</span>
  <span m="2941520">I</span> <span m="2941620">shouldn't</span> <span m="2941950">change</span>
  <span m="2942250">any</span> <span m="2942430">of</span> <span m="2942490">these</span>
  <span m="2942670">norms.</span> <span m="2943030">And so</span> <span m="2943440">the</span>
  <span m="2943600">one</span> <span m="2943870">way</span> <span m="2943990">to</span>
  <span m="2944080">define</span> <span m="2944470">this</span> <span m="2945940">essential</span>
  <span m="2946360">supremum--</span> <span m="2947090">it's</span> <span m="2947330">called</span>
  <span m="2947530">an</span> <span m="2947610">essential</span> <span m="2948070">sup--</span>
  <span m="2949630">is</span> <span m="2949930">that</span> <span m="2950590">it</span>
  <span m="2950740">is</span> <span m="2951190">the</span> <span m="2952060">largest--</span>
  <span m="2954360">so</span> <span m="2954490">it</span> <span m="2954640">is</span>
  <span m="2955420">the</span> <span m="2955510">smallest</span> <span m="2958042">lambda</span>
  <span m="2959300">such</span> <span m="2959630">that--</span> <span m="2960920">so</span>
  <span m="2961030">the</span> <span m="2961280">smallest</span> <span m="2961820">number</span>
  <span m="2963320">m</span> <span m="2963860">such</span> <span m="2964190">that</span>
  <span m="2964310">the</span> <span m="2964400">measure</span> <span m="2965210">of</span>
  <span m="2968440">the</span> <span m="2968530">set</span> <span m="2971010">taking</span>
  <span m="2971340">value</span> <span m="2972300">bigger</span> <span m="2972630">than</span>
  <span m="2974484">m</span> <span m="2977480">this</span> <span m="2977630">set</span>
  <span m="2977870">has</span> <span m="2978090">measure</span> <span m="2978410">0.</span>
  <span m="2980700">So</span> <span m="2980920">it's</span> <span m="2981180">the</span>
  <span m="2981820">threshold</span> <span m="2983110">above</span> <span m="2983410">which</span>
  <span m="2983930">you--</span> <span m="2986140">this,</span> <span m="2986740">it</span>
  <span m="2986920">has</span> <span m="2987160">measure</span> <span m="2987520">0.</span></p><p><span
  m="2990890">And</span> <span m="2991020">the</span> <span m="2991140">l2</span>
  <span m="2991560">norm</span> <span m="2991870">will</span> <span m="2992040">play</span>
  <span m="2992490">a</span> <span m="2992580">particularly</span> <span m="2993240">special</span>
  <span m="2993600">role.</span> <span m="2994040">And</span> <span m="2994170">for</span>
  <span m="2994290">the</span> <span m="2994410">l2</span> <span m="2994740">norm,</span>
  <span m="2995010">you're</span> <span m="2995190">really</span> <span m="2995400">in</span>
  <span m="2995530">the</span> <span m="2995610">Hilbert</span> <span m="2995970">space,</span>
  <span m="2996720">in</span> <span m="2996840">which</span> <span m="2997020">case</span>
  <span m="2997350">we</span> <span m="2997620">are</span> <span m="2998940">going</span>
  <span m="2999150">to</span> <span m="2999210">have</span> <span m="2999510">inner</span>
  <span m="2999690">products.</span> <span m="3000770">And</span> <span m="3000920">we</span>
  <span m="3001540">denote</span> <span m="3002030">inner</span> <span m="3002240">products</span>
  <span m="3003260">using</span> <span m="3003650">the</span> <span m="3003770">square--</span>
  <span m="3004380">using</span> <span m="3004720">these</span> <span m="3005330">brackets.</span></p><p><span
  m="3006430">So</span> <span m="3006720">everything</span> <span m="3006960">is</span>
  <span m="3007130">real.</span> <span m="3007590">I</span> <span m="3007690">don't</span>
  <span m="3007700">have</span> <span m="3007790">to</span> <span m="3007880">worry</span>
  <span m="3008090">about</span> <span m="3008600">complex</span> <span m="3009230">conjugates.</span>
  <span m="3016080">So</span> <span m="3016260">comparing</span> <span m="3016680">with</span>
  <span m="3016860">the</span> <span m="3016890">discussion</span> <span m="3017400">up</span>
  <span m="3017520">there,</span> <span m="3017910">we</span> <span m="3018030">see</span>
  <span m="3018240">that</span> <span m="3018800">a</span> <span m="3018900">sequence</span>
  <span m="3020660">of--</span> <span m="3021535">so</span> <span m="3022020">sequence</span>
  <span m="3023250">Gn</span> <span m="3024500">of</span> <span m="3024740">quasirandom</span>
  <span m="3025460">graphs</span> <span m="3032328">has</span> <span m="3034808">a</span>
  <span m="3035310">property</span> <span m="3035910">that</span> <span m="3036600">the</span>
  <span m="3036750">associated</span> <span m="3037450">graphons</span> <span m="3039480">converge</span>
  <span m="3040050">to</span> <span m="3040620">p</span> <span m="3041430">in</span>
  <span m="3041910">the</span> <span m="3042010">cut norm.</span></p><p><span m="3055610">For</span>
  <span m="3056300">quasirandom</span> <span m="3056890">graphs,</span> <span m="3057180">there</span>
  <span m="3057250">is</span> <span m="3057410">no</span> <span m="3057620">issue</span>
  <span m="3058580">having</span> <span m="3058910">to</span> <span m="3058970">do</span>
  <span m="3059120">with</span> <span m="3059300">permutations</span> <span m="3060210">because</span>
  <span m="3060830">the</span> <span m="3060890">target</span> <span m="3061370">is</span>
  <span m="3062510">invariant</span> <span m="3063050">upon</span> <span m="3063380">permutations.</span>
  <span m="3064670">But</span> <span m="3064790">if</span> <span m="3064910">I</span>
  <span m="3065000">give</span> <span m="3065180">you</span> <span m="3065420">two</span>
  <span m="3065720">different</span> <span m="3066020">graphs,</span> <span m="3066410">then</span>
  <span m="3066620">I</span> <span m="3066680">need</span> <span m="3066830">to</span>
  <span m="3066920">think</span> <span m="3067130">about</span> <span m="3067340">their</span>
  <span m="3067430">permutations.</span> <span m="3069110">And</span> <span m="3069290">to</span>
  <span m="3070460">study</span> <span m="3070850">permutations</span> <span m="3071570">of</span>
  <span m="3071630">vertices,</span> <span m="3072530">the</span> <span m="3072650">right</span>
  <span m="3072890">way</span> <span m="3073010">to</span> <span m="3073130">do</span>
  <span m="3073280">this</span> <span m="3073760">is</span> <span m="3073940">to</span>
  <span m="3074030">consider</span> <span m="3075290">measure-preserving</span> <span
  m="3076430">transformations.</span></p><p><span m="3079640">So</span> <span m="3079730">we</span>
  <span m="3079880">say</span> <span m="3080150">that</span> <span m="3081350">phi</span>
  <span m="3085740">from</span> <span m="3086070">the</span> <span m="3086160">interval</span>
  <span m="3086580">to</span> <span m="3086700">the</span> <span m="3086820">interval</span>
  <span m="3087870">is</span> <span m="3089880">measure-preserving</span> <span m="3095885">because</span>
  <span m="3096360">first</span> <span m="3096600">of</span> <span m="3096690">all,</span>
  <span m="3096850">it</span> <span m="3096950">has</span> <span m="3097020">to</span>
  <span m="3097140">be</span> <span m="3097230">a</span> <span m="3097260">measurable</span>
  <span m="3097680">map.</span> <span m="3098040">And</span> <span m="3098220">everything</span>
  <span m="3098610">I'm</span> <span m="3098730">going</span> <span m="3098880">to</span>
  <span m="3098940">talk</span> <span m="3099150">about</span> <span m="3099360">are</span>
  <span m="3099960">measurable.</span> <span m="3100500">So</span> <span m="3101190">sometimes</span>
  <span m="3101580">I will</span> <span m="3101730">even</span> <span m="3102000">omit</span>
  <span m="3102300">mentioning</span> <span m="3102780">it.</span> <span m="3103290">So</span>
  <span m="3104250">it</span> <span m="3104360">is</span> <span m="3104490">measure-preserving</span>
  <span m="3105930">if,</span> <span m="3106650">for</span> <span m="3106890">all</span>
  <span m="3108480">measurable</span> <span m="3108900">subsets</span> <span m="3113480">A</span>
  <span m="3113970">of</span> <span m="3114120">this</span> <span m="3114270">interval,</span>
  <span m="3117130">one</span> <span m="3117370">has</span> <span m="3119380">that</span>
  <span m="3120260">the</span> <span m="3120410">pullback</span> <span m="3121120">of</span>
  <span m="3121300">A</span> <span m="3127160">has</span> <span m="3127400">the</span>
  <span m="3127490">same</span> <span m="3127760">measure</span> <span m="3128210">as</span>
  <span m="3128630">A</span> <span m="3128900">itself.</span></p><p><span m="3133720">Let</span>
  <span m="3133840">me</span> <span m="3133930">give</span> <span m="3134080">you</span>
  <span m="3134170">an</span> <span m="3134260">example.</span> <span m="3135290">So</span>
  <span m="3135520">you</span> <span m="3135610">have</span> <span m="3135760">to</span>
  <span m="3135850">be</span> <span m="3136030">also</span> <span m="3136270">slightly</span>
  <span m="3136630">careful</span> <span m="3136960">with</span> <span m="3137050">this</span>
  <span m="3137170">definition</span> <span m="3137710">if</span> <span m="3137860">you</span>
  <span m="3138340">think</span> <span m="3138610">about</span> <span m="3139150">the</span>
  <span m="3139240">pushforward</span> <span m="3140050">that's</span> <span m="3140410">false.</span>
  <span m="3142090">It</span> <span m="3142230">has</span> <span m="3142440">to</span>
  <span m="3142500">be</span> <span m="3142620">the</span> <span m="3142680">pullback.</span></p><p><span
  m="3143650">So</span> <span m="3143700">for</span> <span m="3143850">example,</span>
  <span m="3146550">the</span> <span m="3146640">map</span> <span m="3149760">which</span>
  <span m="3149950">sends--</span> <span m="3150930">so</span> <span m="3151650">an</span>
  <span m="3151800">easy</span> <span m="3152100">example,</span> <span m="3152940">the</span>
  <span m="3153030">map</span> <span m="3153300">which</span> <span m="3153480">sends</span>
  <span m="3153960">x</span> <span m="3154450">to</span> <span m="3158650">x</span>
  <span m="3158830">plus</span> <span m="3159040">1/2--</span> <span m="3159860">so</span>
  <span m="3161080">think</span> <span m="3161260">about</span> <span m="3161490">a</span>
  <span m="3161530">circle</span> <span m="3162040">as</span> <span m="3162850">your</span>
  <span m="3162970">space.</span> <span m="3163720">And</span> <span m="3163840">here</span>
  <span m="3164060">I</span> <span m="3164160">am</span> <span m="3164230">just</span>
  <span m="3164410">rotating</span> <span m="3164890">the</span> <span m="3164950">circle</span>
  <span m="3165370">by</span> <span m="3165760">one-half</span> <span m="3166180">rotation.</span>
  <span m="3167900">So</span> <span m="3168000">it's</span> <span m="3168140">obviously</span>
  <span m="3168500">measure-preserving.</span> <span m="3169625">I</span> <span m="3170000">am</span>
  <span m="3170090">not</span> <span m="3170240">changing</span> <span m="3170600">any</span>
  <span m="3170850">measures.</span></p><p><span m="3173350">Slightly</span> <span
  m="3173710">more</span> <span m="3173890">interesting</span> <span m="3174310">example,</span>
  <span m="3176020">quite</span> <span m="3176260">a</span> <span m="3176320">bit</span>
  <span m="3176440">more</span> <span m="3176590">interesting</span> <span m="3176920">example</span>
  <span m="3177280">is</span> <span m="3177360">setting</span> <span m="3177730">x
  to</span> <span m="3178090">2x.</span> <span m="3180340">This</span> <span m="3180490">is</span>
  <span m="3180610">also</span> <span m="3180840">measure-preserving.</span> <span
  m="3182350">And</span> <span m="3182820">you</span> <span m="3182910">might</span>
  <span m="3183030">be</span> <span m="3183360">puzzled</span> <span m="3184080">for</span>
  <span m="3184260">a</span> <span m="3184290">second</span> <span m="3184690">why</span>
  <span m="3184940">it's</span> <span m="3185100">measure-preserving</span> <span
  m="3185790">because</span> <span m="3186090">it</span> <span m="3186150">sounds</span>
  <span m="3186480">like</span> <span m="3186690">it's</span> <span m="3186840">dilating</span>
  <span m="3187680">everything</span> <span m="3188070">by</span> <span m="3188250">a</span>
  <span m="3188280">factor</span> <span m="3188670">of</span> <span m="3188780">2.</span></p><p><span
  m="3190440">But</span> <span m="3190560">if</span> <span m="3190710">you</span>
  <span m="3190770">look</span> <span m="3190920">at</span> <span m="3190980">the</span>
  <span m="3191070">definition--</span> <span m="3191610">and so</span> <span m="3192050">here</span>
  <span m="3192220">is</span> <span m="3192450">again</span> <span m="3192660">mod</span>
  <span m="3194160">1.</span> <span m="3195660">If</span> <span m="3195780">you</span>
  <span m="3195840">look</span> <span m="3195990">at</span> <span m="3196080">the</span>
  <span m="3196150">definition,</span> <span m="3197100">if</span> <span m="3197280">you</span>
  <span m="3201980">look</span> <span m="3202190">at,</span> <span m="3205790">let's</span>
  <span m="3205840">say,</span> <span m="3210080">a</span> <span m="3210180">subset</span>
  <span m="3210570">A,</span> <span m="3211700">which</span> <span m="3211940">is--</span>
  <span m="3215020">so</span> <span m="3215260">what</span> <span m="3215440">should</span>
  <span m="3215710">I</span> <span m="3216400">think?</span> <span m="3220018">For</span>
  <span m="3220476">example,</span> <span m="3222310">so</span> <span m="3222460">if</span>
  <span m="3223060">that</span> <span m="3223240">is</span> <span m="3223330">my</span>
  <span m="3223510">A,</span> <span m="3225300">so</span> <span m="3225460">what's</span>
  <span m="3225730">the</span> <span m="3225850">inverse</span> <span m="3226390">of</span>
  <span m="3226510">A?</span> <span m="3231460">So</span> <span m="3231950">it's</span>
  <span m="3233310">this</span> <span m="3233780">set.</span></p><p><span m="3239420">So
  the</span> <span m="3239730">measure</span> <span m="3240090">is</span> <span m="3240210">preserved</span>
  <span m="3240960">upon</span> <span m="3241230">this</span> <span m="3241380">pullback.</span>
  <span m="3243105">And</span> <span m="3243560">so</span> <span m="3243650">if</span>
  <span m="3243740">you</span> <span m="3244130">pushforward,</span> <span m="3245120">then</span>
  <span m="3245270">you</span> <span m="3245360">might</span> <span m="3245540">dilate</span>
  <span m="3245930">by</span> <span m="3246050">a</span> <span m="3246110">factor</span>
  <span m="3246410">of</span> <span m="3246530">2. But</span> <span m="3246830">when</span>
  <span m="3246950">you</span> <span m="3247040">pullback,</span> <span m="3247460">the</span>
  <span m="3247520">measure</span> <span m="3247770">gets</span> <span m="3247940">preserved.</span></p><p><span
  m="3255400">So</span> <span m="3255520">these</span> <span m="3255760">measure-preserving</span>
  <span m="3256600">transformations</span> <span m="3257920">are</span> <span m="3258070">going</span>
  <span m="3258310">to</span> <span m="3258400">play</span> <span m="3258790">role</span>
  <span m="3259300">of</span> <span m="3260110">permutations</span> <span m="3260890">of</span>
  <span m="3261340">vertices.</span> <span m="3263260">So</span> <span m="3263410">it</span>
  <span m="3263470">turns</span> <span m="3263740">out</span> <span m="3263980">that</span>
  <span m="3264520">these</span> <span m="3264820">things</span> <span m="3265030">are</span>
  <span m="3265120">actually--</span> <span m="3265510">they</span> <span m="3265900">are</span>
  <span m="3266290">quite</span> <span m="3266620">subtle</span> <span m="3267190">technically.</span>
  <span m="3268420">And</span> <span m="3268810">I am</span> <span m="3269050">going</span>
  <span m="3269380">to,</span> <span m="3270310">as</span> <span m="3270460">much</span>
  <span m="3270670">as</span> <span m="3270790">I</span> <span m="3270880">can,</span>
  <span m="3271510">ignore</span> <span m="3272020">some</span> <span m="3272230">of</span>
  <span m="3272290">the</span> <span m="3272350">measure</span> <span m="3272690">theoretic</span>
  <span m="3273050">technicalities.</span> <span m="3275340">But</span> <span m="3275560">they</span>
  <span m="3275680">are</span> <span m="3275830">quite</span> <span m="3276130">subtle.</span></p><p><span
  m="3277690">So</span> <span m="3277900">for</span> <span m="3278110">example,</span>
  <span m="3279310">so</span> <span m="3279490">now</span> <span m="3279640">let</span>
  <span m="3279790">me</span> <span m="3279880">give</span> <span m="3280030">you</span>
  <span m="3280180">a</span> <span m="3280210">definition</span> <span m="3280990">for</span>
  <span m="3281260">the</span> <span m="3281380">distance</span> <span m="3281860">between</span>
  <span m="3282280">two</span> <span m="3282550">graphons.</span> <span m="3285240">I</span>
  <span m="3285390">write,</span> <span m="3287910">starting</span> <span m="3288270">with</span>
  <span m="3288450">a</span> <span m="3289970">symmetric</span> <span m="3290570">measurable</span>
  <span m="3290930">function</span> <span m="3291290">W,</span> <span m="3293540">so</span>
  <span m="3293690">I</span> <span m="3293780">write</span> <span m="3294410">W</span>
  <span m="3295430">superscript</span> <span m="3296550">phi</span> <span m="3299110">to</span>
  <span m="3299560">denote</span> <span m="3301330">the</span> <span m="3301420">function</span>
  <span m="3302080">obtained</span> <span m="3307290">as</span> <span m="3307410">follows.</span>
  <span m="3307980">So</span> <span m="3308100">I</span> <span m="3308160">think</span>
  <span m="3308370">of</span> <span m="3308460">this</span> <span m="3308700">as</span>
  <span m="3308940">relabeling</span> <span m="3309600">the</span> <span m="3309690">vertices</span>
  <span m="3310320">of</span> <span m="3310440">a</span> <span m="3310500">graph.</span>
  <span m="3314480">And</span> <span m="3314540">now</span> <span m="3315290">I</span>
  <span m="3315440">define</span> <span m="3318980">this</span> <span m="3319190">distance.</span>
  <span m="3320390">So</span> <span m="3320450">this</span> <span m="3320630">is</span>
  <span m="3320720">going</span> <span m="3320850">to</span> <span m="3320930">be</span>
  <span m="3321020">called</span> <span m="3321240">the</span> <span m="3321320">cut</span>
  <span m="3321560">distance</span> <span m="3327850">between</span> <span m="3328360">two</span>
  <span m="3331680">symmetric</span> <span m="3332160">measurable</span> <span m="3332520">functions,</span>
  <span m="3333120">U</span> <span m="3333330">and</span> <span m="3333420">W,</span>
  <span m="3334860">to</span> <span m="3334980">be</span> <span m="3336340">the</span>
  <span m="3336840">infimum</span> <span m="3338180">over</span> <span m="3338495">all</span>
  <span m="3339040">measure-preserving</span> <span m="3347840">bijections.</span></p><p><span
  m="3362310">So</span> <span m="3362330">this</span> <span m="3362540">is</span>
  <span m="3362660">the</span> <span m="3362720">definition</span> <span m="3363290">for</span>
  <span m="3363770">the</span> <span m="3363890">distance</span> <span m="3364340">between</span>
  <span m="3364760">two</span> <span m="3365210">graphons.</span> <span m="3369648">To</span>
  <span m="3370140">take</span> <span m="3370620">the</span> <span m="3370890">optimal--</span>
  <span m="3373020">and</span> <span m="3373230">my</span> <span m="3373440">question</span>
  <span m="3373900">does</span> <span m="3374270">it--</span> <span m="3375440">I
  am</span> <span m="3375640">looking</span> <span m="3375940">at</span> <span m="3376060">nth.</span>
  <span m="3376930">So</span> <span m="3377110">I</span> <span m="3377200">haven't</span>
  <span m="3377410">told</span> <span m="3377620">you</span> <span m="3377710">yet</span>
  <span m="3378400">whether</span> <span m="3378640">you</span> <span m="3378700">can</span>
  <span m="3378850">take</span> <span m="3379060">a</span> <span m="3379090">single</span>
  <span m="3379390">one.</span> <span m="3379710">And it</span> <span m="3379900">turns</span>
  <span m="3380110">out</span> <span m="3380200">that's</span> <span m="3380380">a</span>
  <span m="3380440">subtle</span> <span m="3380770">issue.</span> <span m="3381200">And</span>
  <span m="3381310">generally</span> <span m="3381700">it</span> <span m="3381760">doesn't</span>
  <span m="3382030">exist.</span></p><p><span m="3383050">But</span> <span m="3383470">I</span>
  <span m="3383620">look</span> <span m="3383830">over</span> <span m="3384190">all</span>
  <span m="3385060">measure-preserving</span> <span m="3385330">bijections</span>
  <span m="3386320">phi.</span> <span m="3387010">And</span> <span m="3387150">I</span>
  <span m="3387250">look</span> <span m="3387490">at</span> <span m="3387610">the</span>
  <span m="3387670">distance</span> <span m="3388060">between</span> <span m="3388360">W</span>
  <span m="3389110">and</span> <span m="3389260">Wv,</span> <span m="3391450">optimized</span>
  <span m="3392020">over</span> <span m="3392260">the</span> <span m="3392350">best</span>
  <span m="3392590">possible</span> <span m="3393310">measure-preserving</span> <span
  m="3394160">bijection.</span> <span m="3399680">So</span> <span m="3399810">this</span>
  <span m="3400020">nth</span> <span m="3400560">is</span> <span m="3400740">really</span>
  <span m="3400980">an</span> <span m="3401100">nth.</span> <span m="3405340">It's</span>
  <span m="3405490">not</span> <span m="3405730">always</span> <span m="3406060">obtained.</span>
  <span m="3409270">And</span> <span m="3409740">actually,</span> <span m="3410500">this</span>
  <span m="3411370">example</span> <span m="3411820">here</span> <span m="3412120">is</span>
  <span m="3412450">a</span> <span m="3412510">great</span> <span m="3412750">example</span>
  <span m="3413200">for--</span> <span m="3414210">you</span> <span m="3414790">can</span>
  <span m="3414970">create</span> <span m="3415300">an</span> <span m="3416170">example</span>
  <span m="3416560">for</span> <span m="3416680">why</span> <span m="3416900">nth
  is</span> <span m="3417280">not</span> <span m="3417670">always</span> <span m="3417940">obtained</span>
  <span m="3418360">from</span> <span m="3418600">the</span> <span m="3418870">discussion</span>
  <span m="3419590">over</span> <span m="3419800">here.</span></p><p><span m="3420580">For</span>
  <span m="3420730">example,</span> <span m="3423520">if</span> <span m="3423700">U</span>
  <span m="3424070">is</span> <span m="3424310">the</span> <span m="3424390">function</span>
  <span m="3427160">x</span> <span m="3427340">times</span> <span m="3427580">y,</span>
  <span m="3428390">this</span> <span m="3428630">is</span> <span m="3428780">a</span>
  <span m="3428840">graphon</span> <span m="3429290">xy</span> <span m="3431060">and</span>
  <span m="3433520">W</span> <span m="3434450">is</span> <span m="3436100">Uv,</span>
  <span m="3438020">where</span> <span m="3439910">v</span> <span m="3440270">is</span>
  <span m="3440570">the</span> <span m="3443870">map</span> <span m="3444260">distance</span>
  <span m="3444590">x to</span> <span m="3444890">2x,</span> <span m="3447730">then</span>
  <span m="3448660">in</span> <span m="3448750">your</span> <span m="3448840">mind,
  you</span> <span m="3449150">should</span> <span m="3449250">think</span> <span
  m="3449440">of</span> <span m="3449530">these</span> <span m="3449710">two</span>
  <span m="3449890">as</span> <span m="3450100">really</span> <span m="3450300">the</span>
  <span m="3450370">same</span> <span m="3450730">graphons.</span> <span m="3451210">You</span>
  <span m="3451320">are</span> <span m="3451370">applying</span> <span m="3451720">the</span>
  <span m="3451780">measure-preserving</span> <span m="3452410">transformation.</span>
  <span m="3453000">It's</span> <span m="3453130">like</span> <span m="3453490">doing</span>
  <span m="3453700">a</span> <span m="3453730">permutation.</span> <span m="3455010">But</span>
  <span m="3455260">because</span> <span m="3456940">phi</span> <span m="3457350">is</span>
  <span m="3457540">not</span> <span m="3457900">bijective,</span> <span m="3459550">you</span>
  <span m="3459700">cannot</span> <span m="3461180">putting</span> <span m="3461570">phi</span>
  <span m="3461870">here</span> <span m="3462260">to</span> <span m="3463130">get</span>
  <span m="3463310">these</span> <span m="3463520">two</span> <span m="3463700">things</span>
  <span m="3463940">to</span> <span m="3464030">be</span> <span m="3464150">the</span>
  <span m="3464240">same.</span></p><p><span m="3469100">So</span> <span m="3469230">there
  are</span> <span m="3469380">some</span> <span m="3469590">subtleties.</span> <span
  m="3470020">So</span> <span m="3470160">this</span> <span m="3470670">is</span>
  <span m="3470790">really an</span> <span m="3471020">example</span> <span m="3472140">just</span>
  <span m="3472330">to</span> <span m="3472380">highlight</span> <span m="3472770">there's</span>
  <span m="3472950">some</span> <span m="3473220">subtleties</span> <span m="3473730">here,</span>
  <span m="3474370">which</span> <span m="3474780">I</span> <span m="3475020">am</span>
  <span m="3475140">going</span> <span m="3475270">to</span> <span m="3475350">try</span>
  <span m="3475620">to</span> <span m="3475950">ignore</span> <span m="3476310">as</span>
  <span m="3476460">much</span> <span m="3476670">as</span> <span m="3476790">possible.</span>
  <span m="3478420">But</span> <span m="3478470">I will</span> <span m="3478650">always</span>
  <span m="3478950">give</span> <span m="3479100">you</span> <span m="3479220">correct</span>
  <span m="3479610">definitions.</span> <span m="3482180">Any</span> <span m="3482260">questions?</span>
  <span m="3482650">Yeah?</span> <span m="3486546">Yeah?</span></p><p><span m="3487033">AUDIENCE:</span>
  <span m="3487276">So can we</span> <span m="3487520">expect the</span> <span m="3488007">cut
  distance</span> <span m="3488494">between</span> <span m="3488981">these two</span>
  <span m="3489468">sets</span> <span m="3489955">to be 0</span> <span m="3490442">[INAUDIBLE]?</span></p><p><span
  m="3491310">YUFEI ZHAO:</span> <span m="3491445">So</span> <span m="3491580">the</span>
  <span m="3491640">question,</span> <span m="3491910">do</span> <span m="3492000">we</span>
  <span m="3492150">expect</span> <span m="3492510">the</span> <span m="3492600">cut
  distance</span> <span m="3493170">between</span> <span m="3493440">these</span>
  <span m="3493680">two</span> <span m="3494160">to</span> <span m="3494250">be</span>
  <span m="3494370">0?</span> <span m="3494640">And</span> <span m="3494730">the</span>
  <span m="3494820">answer</span> <span m="3495060">is</span> <span m="3495150">yes.</span>
  <span m="3496280">So</span> <span m="3496470">we</span> <span m="3496590">do</span>
  <span m="3496770">expect</span> <span m="3497130">them</span> <span m="3497220">to</span>
  <span m="3497310">be</span> <span m="3497430">0.</span> <span m="3499510">And</span>
  <span m="3499850">they</span> <span m="3500120">are 0.</span> <span m="3502100">They</span>
  <span m="3502220">are</span> <span m="3502340">equal</span> <span m="3502550">to</span>
  <span m="3502610">0.</span></p><p><span m="3504620">And</span> <span m="3504680">let</span>
  <span m="3504800">me</span> <span m="3504980">just</span> <span m="3505220">tell</span>
  <span m="3505400">you</span> <span m="3505550">one</span> <span m="3506690">something</span>
  <span m="3507020">that</span> <span m="3507200">is</span> <span m="3507420">new.</span>
  <span m="3507890">And</span> <span m="3508190">this</span> <span m="3509380">is</span>
  <span m="3509510">one</span> <span m="3509660">of</span> <span m="3509720">those</span>
  <span m="3510710">statements</span> <span m="3511190">that</span> <span m="3511310">has</span>
  <span m="3511580">a</span> <span m="3511610">lot</span> <span m="3511850">of</span>
  <span m="3512060">measure</span> <span m="3512450">theoretic</span> <span m="3512810">technicalities.</span>
  <span m="3514250">For</span> <span m="3514490">all</span> <span m="3515180">graphons</span>
  <span m="3518100">U</span> <span m="3518420">and</span> <span m="3518590">W,</span>
  <span m="3520820">it</span> <span m="3520910">turns</span> <span m="3521150">out</span>
  <span m="3521240">that</span> <span m="3521420">there</span> <span m="3521640">exist</span>
  <span m="3522650">measure-preserving</span> <span m="3523490">maps--</span> <span
  m="3532020">so</span> <span m="3532230">not</span> <span m="3532400">necessarily</span>
  <span m="3533480">bijections,</span> <span m="3534530">but</span> <span m="3534650">measure-preserving</span>
  <span m="3535340">maps</span> <span m="3537460">from</span> <span m="3537800">0,</span>
  <span m="3537970">1</span> <span m="3538160">interval</span> <span m="3538550">to</span>
  <span m="3538700">itself,</span> <span m="3539750">such</span> <span m="3540080">that</span>
  <span m="3540920">the</span> <span m="3541040">distance</span> <span m="3541610">between</span>
  <span m="3542720">U</span> <span m="3542900">and</span> <span m="3543020">W,</span>
  <span m="3543350">the cut</span> <span m="3543650">distance,</span> <span m="3544610">is</span>
  <span m="3544880">obtained</span> <span m="3545780">by</span> <span m="3546680">the</span>
  <span m="3547640">cut</span> <span m="3547910">norm</span> <span m="3549530">difference</span>
  <span m="3549980">between--</span> <span m="3550730">the</span> <span m="3550820">difference</span>
  <span m="3551210">between</span> <span m="3551990">U</span> <span m="3552370">phi</span>
  <span m="3553280">and</span> <span m="3553520">W</span> <span m="3554310">psi.</span>
  <span m="3567314">So</span> <span m="3569290">don't</span> <span m="3569410">worry</span>
  <span m="3569530">about</span> <span m="3569710">it.</span> <span m="3580840">So</span>
  <span m="3580980">far,</span> <span m="3581190">we have</span> <span m="3581370">defined</span>
  <span m="3581970">this</span> <span m="3582300">notion</span> <span m="3582690">of</span>
  <span m="3582810">a</span> <span m="3582900">cut</span> <span m="3583500">distance</span>
  <span m="3584310">between</span> <span m="3584700">two</span> <span m="3585060">graphons.</span>
  <span m="3587170">But</span> <span m="3587260">now</span> <span m="3587410">I'll</span>
  <span m="3587480">give</span> <span m="3587650">you</span> <span m="3587740">two</span>
  <span m="3587920">graphs.</span> <span m="3589750">So</span> <span m="3589900">what</span>
  <span m="3590050">do</span> <span m="3590160">you</span> <span m="3590440">do</span>
  <span m="3590680">for</span> <span m="3590920">two</span> <span m="3591220">graphs?</span>
  <span m="3593855">Or</span> <span m="3593920">I</span> <span m="3594160">can--</span>
  <span m="3594460">yeah?</span></p><p><span m="3595396">AUDIENCE:</span> <span m="3595630">You
  can</span> <span m="3595864">take the</span> <span m="3596332">graphon associated</span>
  <span m="3596800">it.</span></p><p><span m="3597970">YUFEI ZHAO:</span> <span m="3598075">Great.</span>
  <span m="3598180">So</span> <span m="3598300">take</span> <span m="3598510">the</span>
  <span m="3598600">graphon</span> <span m="3599140">associated</span> <span m="3599710">with</span>
  <span m="3599860">these</span> <span m="3600040">graphs</span> <span m="3600550">and</span>
  <span m="3600790">consider</span> <span m="3601240">their</span> <span m="3601450">cut</span>
  <span m="3601960">distance.</span> <span m="3603020">So</span> <span m="3603160">for</span>
  <span m="3605320">graphs</span> <span m="3608260">G</span> <span m="3608620">and</span>
  <span m="3608770">G</span> <span m="3608950">prime,</span> <span m="3611110">and</span>
  <span m="3611230">potentially</span> <span m="3612160">even a</span> <span m="3612460">different</span>
  <span m="3612790">number</span> <span m="3613060">of</span> <span m="3613120">vertices,</span>
  <span m="3619480">I</span> <span m="3619570">can</span> <span m="3619750">define</span>
  <span m="3620650">the</span> <span m="3621070">distance,</span> <span m="3621730">the</span>
  <span m="3621820">cut</span> <span m="3622060">distance</span> <span m="3622510">between</span>
  <span m="3622870">these</span> <span m="3623140">two</span> <span m="3625540">graphs</span>
  <span m="3629650">to</span> <span m="3629740">be</span> <span m="3630640">the</span>
  <span m="3630730">distance</span> <span m="3631540">between</span> <span m="3633640">the</span>
  <span m="3633910">associated</span> <span m="3634820">graphons.</span> <span m="3640100">And</span>
  <span m="3640250">similarly,</span> <span m="3644910">if</span> <span m="3645060">I</span>
  <span m="3645150">have</span> <span m="3645390">a</span> <span m="3645510">graph</span>
  <span m="3646050">and</span> <span m="3646350">a</span> <span m="3646440">graphon,</span>
  <span m="3647520">I</span> <span m="3647620">can</span> <span m="3647670">also</span>
  <span m="3647880">compare</span> <span m="3648300">their</span> <span m="3648460">distance.</span></p><p><span
  m="3661660">So</span> <span m="3661800">what</span> <span m="3661920">does</span>
  <span m="3662040">this</span> <span m="3662190">actually</span> <span m="3662550">mean?</span>
  <span m="3663340">So</span> <span m="3663360">if</span> <span m="3663480">I</span>
  <span m="3663570">give</span> <span m="3663750">you</span> <span m="3663870">two</span>
  <span m="3664110">graphs,</span> <span m="3664920">even</span> <span m="3665190">with</span>
  <span m="3665340">the</span> <span m="3665400">same</span> <span m="3665820">number</span>
  <span m="3666210">of</span> <span m="3666270">vertices,</span> <span m="3668240">it's</span>
  <span m="3668420">not</span> <span m="3668780">quite</span> <span m="3669320">the</span>
  <span m="3669440">same</span> <span m="3669800">thing</span> <span m="3670220">as</span>
  <span m="3670550">a</span> <span m="3670610">permutation</span> <span m="3671480">of</span>
  <span m="3671570">vertices.</span> <span m="3672620">It's</span> <span m="3672800">a</span>
  <span m="3672860">bit</span> <span m="3673130">more</span> <span m="3673400">subtle.</span>
  <span m="3674930">Now</span> <span m="3675080">why</span> <span m="3675180">is</span>
  <span m="3675420">it</span> <span m="3675570">more</span> <span m="3675780">subtle</span>
  <span m="3676200">than</span> <span m="3676410">just</span> <span m="3676650">permuting</span>
  <span m="3677130">the</span> <span m="3677190">vertices?</span></p><p><span m="3680650">So</span>
  <span m="3680870">here</span> <span m="3681140">we are</span> <span m="3681290">using</span>
  <span m="3682310">measure-preserving</span> <span m="3683180">transformations,</span>
  <span m="3684680">which</span> <span m="3684950">doesn't</span> <span m="3685340">see</span>
  <span m="3685790">your</span> <span m="3686060">atomic</span> <span m="3686570">vertices.</span>
  <span m="3687020">So</span> <span m="3687150">we</span> <span m="3687230">might</span>
  <span m="3687470">split</span> <span m="3687920">up</span> <span m="3688160">your</span>
  <span m="3688340">vertices.</span> <span m="3690120">So</span> <span m="3690210">you</span>
  <span m="3690290">might</span> <span m="3690440">take</span> <span m="3690630">a</span>
  <span m="3690690">vertex</span> <span m="3691680">and</span> <span m="3692280">chop</span>
  <span m="3692670">it</span> <span m="3692760">in</span> <span m="3692880">half</span>
  <span m="3693510">and</span> <span m="3693630">send</span> <span m="3694050">one</span>
  <span m="3694350">half</span> <span m="3694740">somewhere</span> <span m="3695160">and</span>
  <span m="3695280">another</span> <span m="3695610">half</span> <span m="3695880">somewhere</span>
  <span m="3696180">else</span> <span m="3696855">because</span> <span m="3697260">these</span>
  <span m="3697470">guys,</span> <span m="3698080">they</span> <span m="3698250">don't</span>
  <span m="3698400">care</span> <span m="3698580">about</span> <span m="3698760">your</span>
  <span m="3698880">vertices</span> <span m="3699360">anymore.</span> <span m="3701060">So</span>
  <span m="3701360">it's</span> <span m="3701960">not</span> <span m="3702200">quite</span>
  <span m="3702500">the</span> <span m="3702560">same</span> <span m="3705530">as</span>
  <span m="3706410">permuting</span> <span m="3706860">vertices.</span></p><p><span
  m="3712450">But</span> <span m="3712660">it's</span> <span m="3712840">some</span>
  <span m="3713110">kind</span> <span m="3713560">of--</span> <span m="3714010">so</span>
  <span m="3714160">you</span> <span m="3714490">allow</span> <span m="3715180">some</span>
  <span m="3715450">kind</span> <span m="3715810">of</span> <span m="3715930">splitting</span>
  <span m="3717850">and</span> <span m="3718690">rearrangement</span> <span m="3719530">and</span>
  <span m="3719650">overlays.</span> <span m="3721760">So</span> <span m="3721780">you</span>
  <span m="3721870">can</span> <span m="3723072">write</span> <span m="3723510">out</span>
  <span m="3723730">this</span> <span m="3723910">distance</span> <span m="3724510">in</span>
  <span m="3724900">this</span> <span m="3725110">format,</span> <span m="3725410">find</span>
  <span m="3725680">out</span> <span m="3725740">the</span> <span m="3725830">best</span>
  <span m="3726160">way</span> <span m="3726400">to</span> <span m="3727180">split</span>
  <span m="3727600">and</span> <span m="3727720">overlay</span> <span m="3728230">and</span>
  <span m="3728350">to</span> <span m="3728500">rearrange</span> <span m="3729040">that</span>
  <span m="3729280">way.</span> <span m="3729760">But</span> <span m="3730030">it's</span>
  <span m="3730150">much</span> <span m="3730390">cleaner</span> <span m="3730780">to</span>
  <span m="3731620">define</span> <span m="3732010">it</span> <span m="3732070">in</span>
  <span m="3732190">terms</span> <span m="3732460">of</span> <span m="3732570">graphons.</span>
  <span m="3733580">Yes?</span></p><p><span m="3733750">AUDIENCE:</span> <span m="3733994">Is</span>
  <span m="3734238">this why we</span> <span m="3734482">take</span> <span m="3734726">bijections</span>
  <span m="3735214">up there</span> <span m="3735702">[INAUDIBLE]?</span></p><p><span
  m="3737170">YUFEI ZHAO:</span> <span m="3737330">The</span> <span m="3737490">question</span>
  <span m="3737820">is, is</span> <span m="3738050">that</span> <span m="3738170">why</span>
  <span m="3738440">we</span> <span m="3738620">take</span> <span m="3738860">bijections</span>
  <span m="3739430">up</span> <span m="3739550">there?</span> <span m="3739730">And</span>
  <span m="3739890">no,</span> <span m="3740250">so</span> <span m="3740870">up</span>
  <span m="3741050">there,</span> <span m="3741290">if</span> <span m="3741500">I</span>
  <span m="3741620">wrote</span> <span m="3741920">instead</span> <span m="3742370">measure-preserving</span>
  <span m="3743540">maps,</span> <span m="3744650">it's</span> <span m="3744800">still</span>
  <span m="3745070">a</span> <span m="3745130">correct</span> <span m="3745580">definition</span>
  <span m="3746270">and</span> <span m="3746390">it's</span> <span m="3746510">the</span>
  <span m="3746600">same</span> <span m="3746900">definition.</span> <span m="3748740">And</span>
  <span m="3749100">the</span> <span m="3749220">fact</span> <span m="3749520">that</span>
  <span m="3749760">these</span> <span m="3750030">two</span> <span m="3750210">are</span>
  <span m="3750300">equivalent</span> <span m="3750930">goes</span> <span m="3751260">to</span>
  <span m="3751380">some</span> <span m="3751590">measure</span> <span m="3751860">theory,</span>
  <span m="3752120">which</span> <span m="3753180">I</span> <span m="3753420">will</span>
  <span m="3753570">not--</span> <span m="3755660">do</span> <span m="3756100">not</span>
  <span m="3756240">want</span> <span m="3756390">to</span> <span m="3756510">indulge</span>
  <span m="3756735">yo</span> <span m="3764040">Great.</span> <span m="3764300">But</span>
  <span m="3764500">the</span> <span m="3764620">moral</span> <span m="3764830">of</span>
  <span m="3764920">the</span> <span m="3765010">story</span> <span m="3765270">is</span>
  <span m="3765430">you</span> <span m="3765550">take</span> <span m="3765760">two</span>
  <span m="3765850">graphons</span> <span m="3766420">and</span> <span m="3766990">rearrange</span>
  <span m="3767830">the</span> <span m="3767950">vertices</span> <span m="3768580">in</span>
  <span m="3768700">some</span> <span m="3768880">way,</span> <span m="3769620">in</span>
  <span m="3769720">the</span> <span m="3769780">best</span> <span m="3770050">way,</span>
  <span m="3770620">overlay</span> <span m="3771070">them</span> <span m="3771220">on</span>
  <span m="3771310">top</span> <span m="3771550">of</span> <span m="3771670">each</span>
  <span m="3771850">other</span> <span m="3772360">and</span> <span m="3772510">take</span>
  <span m="3772750">the</span> <span m="3772840">difference</span> <span m="3773690">and</span>
  <span m="3773710">look</span> <span m="3773860">at</span> <span m="3773940">the</span>
  <span m="3774010">cut</span> <span m="3774220">norm.</span> <span m="3774645">And</span>
  <span m="3774940">so</span> <span m="3775060">that's</span> <span m="3775270">the</span>
  <span m="3775360">distance.</span></p><p><span m="3779180">So</span> <span m="3779510">I</span>
  <span m="3779600">want</span> <span m="3779840">to</span> <span m="3780140">finish</span>
  <span m="3780620">by</span> <span m="3780980">stating</span> <span m="3781910">the</span>
  <span m="3782030">main</span> <span m="3782450">theorems</span> <span m="3784570">that</span>
  <span m="3784890">form</span> <span m="3785430">graph</span> <span m="3785790">limit</span>
  <span m="3786060">theory.</span> <span m="3787890">And</span> <span m="3787950">these</span>
  <span m="3788200">address</span> <span m="3788640">the</span> <span m="3788730">questions</span>
  <span m="3789240">I</span> <span m="3789750">mentioned</span> <span m="3790410">right</span>
  <span m="3790620">before</span> <span m="3790890">the</span> <span m="3790980">break.</span>
  <span m="3791940">So</span> <span m="3792660">do</span> <span m="3792810">there</span>
  <span m="3792990">exist</span> <span m="3793410">limits?</span> <span m="3794960">And</span>
  <span m="3795770">do</span> <span m="3795920">these</span> <span m="3796160">two</span>
  <span m="3796400">different</span> <span m="3796730">notions</span> <span m="3797270">of</span>
  <span m="3798050">one</span> <span m="3798620">having</span> <span m="3798860">to</span>
  <span m="3798950">do</span> <span m="3799070">with</span> <span m="3799250">distance</span>
  <span m="3800270">and</span> <span m="3800390">another</span> <span m="3800900">having</span>
  <span m="3801170">to</span> <span m="3801260">do</span> <span m="3801590">with</span>
  <span m="3802790">homomorphism</span> <span m="3803560">densities,</span> <span
  m="3804410">how</span> <span m="3804650">do</span> <span m="3804800">they</span>
  <span m="3804920">relate</span> <span m="3805250">to</span> <span m="3805430">each</span>
  <span m="3805610">other?</span> <span m="3806400">Are</span> <span m="3806420">they</span>
  <span m="3806900">consistent?</span></p><p><span m="3830070">So the</span> <span
  m="3830230">first</span> <span m="3830530">theorem,</span> <span m="3832772">Theorem</span>
  <span m="3833250">1,</span> <span m="3834180">has</span> <span m="3834420">to</span>
  <span m="3834510">do</span> <span m="3834690">with the</span> <span m="3834970">equivalence</span>
  <span m="3835370">of</span> <span m="3835770">the</span> <span m="3835950">convergence,</span>
  <span m="3847480">namely,</span> <span m="3848850">that</span> <span m="3849040">if</span>
  <span m="3849220">you</span> <span m="3849340">have</span> <span m="3849610">a</span>
  <span m="3849670">sequence</span> <span m="3850240">of</span> <span m="3850390">graphs</span>
  <span m="3850930">or</span> <span m="3851050">graphons,</span> <span m="3862800">the</span>
  <span m="3862950">sequence</span> <span m="3863450">is</span> <span m="3863610">convergent</span>
  <span m="3867510">in</span> <span m="3867630">the</span> <span m="3867720">sense,</span>
  <span m="3868410">up</span> <span m="3868530">there,</span> <span m="3870390">if</span>
  <span m="3870540">and</span> <span m="3870690">only</span> <span m="3870990">if</span>
  <span m="3875890">they</span> <span m="3876040">are</span> <span m="3876160">convergent</span>
  <span m="3877510">in</span> <span m="3877720">the</span> <span m="3877840">sense</span>
  <span m="3878380">of--</span> <span m="3878680">in</span> <span m="3879090">this</span>
  <span m="3879460">metric</span> <span m="3879880">space.</span> <span m="3880440">So</span>
  <span m="3880620">remember</span> <span m="3880900">what</span> <span m="3881140">convergence</span>
  <span m="3881770">means</span> <span m="3882010">in</span> <span m="3882100">the</span>
  <span m="3882160">metric</span> <span m="3882520">space</span> <span m="3883360">is</span>
  <span m="3883660">that</span> <span m="3883960">of</span> <span m="3884140">a</span>
  <span m="3884660">Cauchy</span> <span m="3884980">sequence--</span> <span m="3886310">so</span>
  <span m="3886450">if</span> <span m="3886600">and</span> <span m="3886750">only</span>
  <span m="3887050">if</span> <span m="3889280">it</span> <span m="3889450">is</span>
  <span m="3889750">a</span> <span m="3890050">Cauchy</span> <span m="3890410">sequence</span>
  <span m="3894970">with</span> <span m="3895180">respect</span> <span m="3895600">to</span>
  <span m="3899430">this</span> <span m="3899690">cut</span> <span m="3900040">distance.</span>
  <span m="3902470">So</span> <span m="3902770">it's</span> <span m="3902880">just--</span>
  <span m="3904430">maybe</span> <span m="3904730">for</span> <span m="3904910">many</span>
  <span m="3905150">of</span> <span m="3905240">you,</span> <span m="3905360">it's</span>
  <span m="3905510">been</span> <span m="3905660">a</span> <span m="3905690">while</span>
  <span m="3905900">since</span> <span m="3906140">you</span> <span m="3906230">took</span>
  <span m="3906440">18-100.</span> <span m="3907140">So</span> <span m="3907540">let</span>
  <span m="3907770">remind</span> <span m="3908150">you</span> <span m="3908240">a</span>
  <span m="3908300">Cauchy</span> <span m="3908630">sequence,</span> <span m="3909900">in</span>
  <span m="3909950">this</span> <span m="3910100">case,</span> <span m="3910800">it</span>
  <span m="3910970">means</span> <span m="3911480">that,</span> <span m="3912350">if</span>
  <span m="3912530">I</span> <span m="3912710">look</span> <span m="3912950">at</span>
  <span m="3913280">the</span> <span m="3913520">distance</span> <span m="3914060">between</span>
  <span m="3914990">two</span> <span m="3915230">graphs,</span> <span m="3920310">if</span>
  <span m="3920430">I</span> <span m="3920520">look</span> <span m="3920880">far</span>
  <span m="3921660">enough</span> <span m="3921960">out,</span> <span m="3922470">then</span>
  <span m="3922680">I</span> <span m="3922740">can</span> <span m="3922920">contain</span>
  <span m="3924210">the</span> <span m="3924360">rest</span> <span m="3924660">of</span>
  <span m="3924720">the</span> <span m="3924780">sequence</span> <span m="3925530">in</span>
  <span m="3926250">an</span> <span m="3926340">arbitrarily</span> <span m="3926910">small</span>
  <span m="3927300">ball.</span> <span m="3928500">So</span> <span m="3928700">the</span>
  <span m="3928940">sup</span> <span m="3931290">positive</span> <span m="3931720">m</span>
  <span m="3932130">of</span> <span m="3932280">this</span> <span m="3932370">guy</span>
  <span m="3932610">here,</span> <span m="3933150">goes</span> <span m="3933420">to</span>
  <span m="3933480">0</span> <span m="3934470">as</span> <span m="3935640">n</span>
  <span m="3936000">goes</span> <span m="3936240">to</span> <span m="3936330">infinity.</span></p><p><span
  m="3937986">But</span> <span m="3938380">because</span> <span m="3938550">we</span>
  <span m="3938910">don't</span> <span m="3939090">know</span> <span m="3939300">yet</span>
  <span m="3940630">whether</span> <span m="3941310">the</span> <span m="3941430">limit</span>
  <span m="3941730">exists,</span> <span m="3942210">so</span> <span m="3942360">I</span>
  <span m="3942420">can't</span> <span m="3942720">talk</span> <span m="3942960">about</span>
  <span m="3943260">them</span> <span m="3943500">getting</span> <span m="3943740">closer</span>
  <span m="3943980">and</span> <span m="3944070">closer</span> <span m="3944340">to</span>
  <span m="3944460">a</span> <span m="3944490">limit.</span> <span m="3945060">But</span>
  <span m="3945240">they</span> <span m="3945750">mutually</span> <span m="3946140">get</span>
  <span m="3946290">closer</span> <span m="3946680">to</span> <span m="3946800">each</span>
  <span m="3946950">other.</span> <span m="3950320">So</span> <span m="3951870">Theorem</span>
  <span m="3952150">1</span> <span m="3952340">tells</span> <span m="3952640">us</span>
  <span m="3952790">that</span> <span m="3952940">these</span> <span m="3953210">two</span>
  <span m="3953420">notions,</span> <span m="3953870">one</span> <span m="3954110">having</span>
  <span m="3954350">to</span> <span m="3954410">do</span> <span m="3954530">with</span>
  <span m="3954770">homomorphism</span> <span m="3955690">densities,</span> <span
  m="3956600">is</span> <span m="3957230">consistent</span> <span m="3957980">and</span>
  <span m="3958100">in</span> <span m="3958190">fact</span> <span m="3958430">equivalent</span>
  <span m="3959270">to</span> <span m="3960500">the</span> <span m="3960920">appropriate</span>
  <span m="3961370">notion</span> <span m="3962360">in</span> <span m="3962630">the</span>
  <span m="3962760">metric</span> <span m="3963080">space.</span></p><p><span m="3971200">So</span>
  <span m="3975380">let's</span> <span m="3975560">use</span> <span m="3975760">a</span>
  <span m="3975830">symbol.</span> <span m="3976380">So</span> <span m="3976460">we</span>
  <span m="3976580">say</span> <span m="3976910">that</span> <span m="3980060">G sub</span>
  <span m="3980330">n</span> <span m="3981370">converges</span> <span m="3981970">to</span>
  <span m="3982310">W,</span> <span m="3983760">or</span> <span m="3986770">in</span>
  <span m="3986890">the</span> <span m="3986950">case</span> <span m="3987250">of
  a</span> <span m="3987640">sequence</span> <span m="3988090">of</span> <span m="3988150">graphons.</span>
  <span m="3989020">So</span> <span m="3989710">we</span> <span m="3989770">can</span>
  <span m="3989920">do</span> <span m="3990040">that</span> <span m="3990190">as</span>
  <span m="3990300">well.</span></p><p><span m="3994630">So</span> <span m="3995850">here</span>
  <span m="3996100">we</span> <span m="3996220">say</span> <span m="3996520">that</span>
  <span m="3996730">G sub</span> <span m="3997075">n</span> <span m="3997420">converges</span>
  <span m="4000142">with</span> <span m="4000620">W,</span> <span m="4003440">if</span>
  <span m="4004400">whenever</span> <span m="4004760">you</span> <span m="4004910">look</span>
  <span m="4005150">at</span> <span m="4005750">the</span> <span m="4005960">F</span>
  <span m="4006260">density</span> <span m="4007010">in</span> <span m="4007760">G
  sub</span> <span m="4008075">n,</span> <span m="4008960">this</span> <span m="4009140">sequence</span>
  <span m="4010040">converges</span> <span m="4012020">to</span> <span m="4013790">the</span>
  <span m="4014120">corresponding</span> <span m="4014810">f</span> <span m="4014990">density</span>
  <span m="4015800">in</span> <span m="4015950">W</span> <span m="4016610">for</span>
  <span m="4017210">every</span> <span m="4018140">f,</span> <span m="4020310">and</span>
  <span m="4020460">similarly,</span> <span m="4021000">if</span> <span m="4021090">you</span>
  <span m="4021180">have</span> <span m="4021360">a</span> <span m="4021390">graphon</span>
  <span m="4021990">instead</span> <span m="4022290">of</span> <span m="4022380">a</span>
  <span m="4022410">graph.</span> <span m="4024480">So</span> <span m="4026330">that</span>
  <span m="4026480">definition</span> <span m="4026920">was</span> <span m="4027000">just</span>
  <span m="4027380">whether</span> <span m="4027650">a</span> <span m="4027710">sequence</span>
  <span m="4028160">is</span> <span m="4028340">convergent.</span> <span m="4029140">Here</span>
  <span m="4029790">it</span> <span m="4029940">converges</span> <span m="4030700">to</span>
  <span m="4031670">this</span> <span m="4032270">graphon</span> <span m="4032750">W.</span></p><p><span
  m="4036190">And</span> <span m="4036520">the</span> <span m="4036640">question</span>
  <span m="4037150">is,</span> <span m="4037390">if</span> <span m="4037600">you</span>
  <span m="4038320">give</span> <span m="4038560">me</span> <span m="4039040">a</span>
  <span m="4039130">convergent</span> <span m="4039940">sequence,</span> <span m="4041380">is</span>
  <span m="4041650">there</span> <span m="4041920">a</span> <span m="4042070">limit?</span>
  <span m="4043150">Does</span> <span m="4043360">it</span> <span m="4043420">converge</span>
  <span m="4043990">to</span> <span m="4044230">some</span> <span m="4044530">limit?</span>
  <span m="4045560">And</span> <span m="4045670">the</span> <span m="4045760">answer</span>
  <span m="4046060">is</span> <span m="4046180">yes.</span> <span m="4047430">And</span>
  <span m="4047560">that's</span> <span m="4047830">the</span> <span m="4047920">second</span>
  <span m="4048280">theorem,</span> <span m="4052190">which</span> <span m="4054070">tells</span>
  <span m="4054400">us</span> <span m="4054610">the</span> <span m="4054760">existence</span>
  <span m="4055450">of</span> <span m="4055620">a</span> <span m="4055650">limit,</span>
  <span m="4056770">of</span> <span m="4056920">the</span> <span m="4057070">limit</span>
  <span m="4057400">object.</span> <span m="4061990">So</span> <span m="4062880">the</span>
  <span m="4063020">statement</span> <span m="4063590">is</span> <span m="4063740">that</span>
  <span m="4063920">every</span> <span m="4064640">convergent</span> <span m="4068150">sequence</span>
  <span m="4069830">of</span> <span m="4069980">graph</span> <span m="4074200">or</span>
  <span m="4074380">graphons</span> <span m="4080750">has</span> <span m="4081230">a</span>
  <span m="4081440">limit</span> <span m="4084175">graphon.</span></p><p><span m="4098346">So</span>
  <span m="4098870">now</span> <span m="4099270">I</span> <span m="4099390">want</span>
  <span m="4099510">you</span> <span m="4099569">to</span> <span m="4099720">imagine</span>
  <span m="4100500">this</span> <span m="4100720">space</span> <span m="4101520">of</span>
  <span m="4101640">graphons.</span> <span m="4102930">So</span> <span m="4103090">we'll</span>
  <span m="4103170">have</span> <span m="4103290">this</span> <span m="4103380">space</span>
  <span m="4104520">containing</span> <span m="4105000">all</span> <span m="4105090">the</span>
  <span m="4105180">graphons.</span> <span m="4105960">And</span> <span m="4106080">let</span>
  <span m="4106170">me</span> <span m="4106260">denote</span> <span m="4106620">this</span>
  <span m="4106740">space</span> <span m="4107189">by</span> <span m="4107939">this</span>
  <span m="4108149">curly</span> <span m="4108510">W0.</span> <span m="4110149">So</span>
  <span m="4110390">this,</span> <span m="4110689">the</span> <span m="4110880">0</span>
  <span m="4111210">is--</span> <span m="4111620">don't</span> <span m="4111750">worry</span>
  <span m="4111870">about</span> <span m="4112080">it.</span> <span m="4112279">It's</span>
  <span m="4112319">more</span> <span m="4112529">just</span> <span m="4112740">convention.</span></p><p><span
  m="4114080">But</span> <span m="4114750">let</span> <span m="4114899">me</span>
  <span m="4115050">also</span> <span m="4115290">put</span> <span m="4115470">a</span>
  <span m="4115500">tilde</span> <span m="4115850">on</span> <span m="4116010">top</span>
  <span m="4116430">for</span> <span m="4116550">the</span> <span m="4116640">following</span>
  <span m="4117029">reason.</span> <span m="4117600">Let</span> <span m="4119410">this</span>
  <span m="4119590">be</span> <span m="4119800">the</span> <span m="4119950">space</span>
  <span m="4123850">of</span> <span m="4124180">graphons</span> <span m="4127790">where</span>
  <span m="4129710">we</span> <span m="4130550">identify</span> <span m="4131630">graphons</span>
  <span m="4132170">with</span> <span m="4132350">distance</span> <span m="4132830">0.</span>
  <span m="4149640">So</span> <span m="4149790">then</span> <span m="4151350">the</span>
  <span m="4151500">space</span> <span m="4153060">combined</span> <span m="4153660">with</span>
  <span m="4154410">this</span> <span m="4154590">metric</span> <span m="4156090">is</span>
  <span m="4156330">a</span> <span m="4156510">metric</span> <span m="4156930">space.</span>
  <span m="4162149">It</span> <span m="4162290">is</span> <span m="4162420">the</span>
  <span m="4162510">space</span> <span m="4162960">of</span> <span m="4163080">graphons.</span></p><p><span
  m="4166060">And</span> <span m="4166540">so</span> <span m="4166569">the</span>
  <span m="4166689">third</span> <span m="4166960">theorem</span> <span m="4171899">is</span>
  <span m="4172080">that</span> <span m="4172720">it's</span> <span m="4172859">the</span>
  <span m="4172950">compactness</span> <span m="4173850">of</span> <span m="4173970">the</span>
  <span m="4174060">space</span> <span m="4174420">of</span> <span m="4174510">graphons,</span>
  <span m="4175529">namely,</span> <span m="4175950">that</span> <span m="4176130">this</span>
  <span m="4176279">space</span> <span m="4176880">is</span> <span m="4177060">compact.</span>
  <span m="4190970">Because</span> <span m="4191270">we're</span> <span m="4191370">in</span>
  <span m="4191450">the</span> <span m="4191510">metric</span> <span m="4191810">space,</span>
  <span m="4193819">compactness</span> <span m="4195020">in</span> <span m="4195140">the</span>
  <span m="4195290">usual</span> <span m="4195620">sense</span> <span m="4195980">of</span>
  <span m="4197390">every</span> <span m="4198590">open</span> <span m="4198830">cover</span>
  <span m="4199190">has</span> <span m="4199340">a</span> <span m="4199400">finite</span>
  <span m="4199730">subcover</span> <span m="4200260">is</span> <span m="4200430">equivalent</span>
  <span m="4201380">to</span> <span m="4202780">the</span> <span m="4203180">slightly</span>
  <span m="4203600">more</span> <span m="4203780">intuitive</span> <span m="4204260">notion</span>
  <span m="4204650">of</span> <span m="4204740">sequential</span> <span m="4205280">compactness--</span>
  <span m="4206550">every</span> <span m="4206750">sequence</span> <span m="4207350">has</span>
  <span m="4207740">a</span> <span m="4207950">convergent</span> <span m="4209180">subsequence.</span>
  <span m="4210170">And</span> <span m="4210620">then</span> <span m="4210970">it's</span>
  <span m="4211160">also,</span> <span m="4211915">if</span> <span m="4212280">you</span>
  <span m="4212720">have</span> <span m="4212840">a</span> <span m="4212870">limit,</span>
  <span m="4213530">so</span> <span m="4213975">it</span> <span m="4214310">converges</span>
  <span m="4214820">to</span> <span m="4215180">some</span> <span m="4215420">limit.</span></p><p><span
  m="4218330">So</span> <span m="4218810">how</span> <span m="4219110">should</span>
  <span m="4219350">you</span> <span m="4219470">think</span> <span m="4219710">of</span>
  <span m="4219890">Theorem</span> <span m="4220120">3?</span> <span m="4220670">So</span>
  <span m="4220820">it's</span> <span m="4220940">about</span> <span m="4221120">compactness</span>
  <span m="4222230">and</span> <span m="4223590">some</span> <span m="4223760">tautological</span>
  <span m="4224360">notion.</span> <span m="4224720">But</span> <span m="4225170">intuitively,</span>
  <span m="4225830">you</span> <span m="4225920">should</span> <span m="4226100">think</span>
  <span m="4226370">of</span> <span m="4226460">compactness</span> <span m="4227720">as</span>
  <span m="4227960">saying--</span> <span m="4229170">and</span> <span m="4229380">the</span>
  <span m="4229610">English</span> <span m="4230030">word,</span> <span m="4230240">the</span>
  <span m="4230390">English</span> <span m="4230750">meaning</span> <span m="4231050">of</span>
  <span m="4231110">the</span> <span m="4231200">word</span> <span m="4231350">compact</span>
  <span m="4231920">is</span> <span m="4232190">small.</span></p><p><span m="4233330">You</span>
  <span m="4233400">should</span> <span m="4233510">think</span> <span m="4233750">of</span>
  <span m="4233840">this</span> <span m="4233960">space</span> <span m="4234380">as</span>
  <span m="4234530">being</span> <span m="4234710">quite</span> <span m="4235010">small,</span>
  <span m="4237050">which</span> <span m="4237230">is</span> <span m="4237380">rather</span>
  <span m="4237680">counterintuitive</span> <span m="4239060">because</span> <span
  m="4239960">we're</span> <span m="4240140">looking</span> <span m="4240590">at</span>
  <span m="4240950">the</span> <span m="4241040">space</span> <span m="4241520">of</span>
  <span m="4241610">graphons,</span> <span m="4243200">certainly</span> <span m="4243530">at</span>
  <span m="4243590">least</span> <span m="4243830">as</span> <span m="4243970">large</span>
  <span m="4244260">as</span> <span m="4244350">the</span> <span m="4244430">space</span>
  <span m="4244820">of</span> <span m="4244910">graphs,</span> <span m="4246080">but</span>
  <span m="4246350">really</span> <span m="4246710">all</span> <span m="4246950">functions</span>
  <span m="4248150">from</span> <span m="4248900">the</span> <span m="4248990">square</span>
  <span m="4249410">to</span> <span m="4249530">the</span> <span m="4249620">interval.</span>
  <span m="4249875">This</span> <span m="4250130">seems</span> <span m="4250430">like</span>
  <span m="4250610">a</span> <span m="4250670">pretty</span> <span m="4251060">large</span>
  <span m="4251360">space.</span> <span m="4253010">But</span> <span m="4253130">this</span>
  <span m="4253370">theorem</span> <span m="4253670">here</span> <span m="4253970">says</span>
  <span m="4254240">that,</span> <span m="4254460">in</span> <span m="4254560">fact,</span>
  <span m="4254790">that</span> <span m="4254870">space</span> <span m="4255290">is</span>
  <span m="4255830">quite</span> <span m="4256130">small.</span> <span m="4257950">And</span>
  <span m="4258100">where</span> <span m="4258280">have</span> <span m="4258700">we</span>
  <span m="4258910">also</span> <span m="4259270">seen</span> <span m="4260530">that</span>
  <span m="4260800">philosophy</span> <span m="4261460">before?</span></p><p><span
  m="4266120">So</span> <span m="4266230">in</span> <span m="4266650">Szemeredi's</span>
  <span m="4268060">Graph</span> <span m="4268420">Regularity</span> <span m="4269050">Lemma,</span>
  <span m="4269920">the</span> <span m="4270070">underlying</span> <span m="4270580">philosophy</span>
  <span m="4271210">there</span> <span m="4272110">is</span> <span m="4272350">that,</span>
  <span m="4272950">even</span> <span m="4273220">though</span> <span m="4273700">the</span>
  <span m="4273990">possibilities,</span> <span m="4274960">the</span> <span m="4275080">space</span>
  <span m="4275560">of</span> <span m="4275680">possibilities</span> <span m="4276430">for</span>
  <span m="4276580">graph</span> <span m="4277630">is</span> <span m="4277870">quite</span>
  <span m="4278290">large,</span> <span m="4279400">once</span> <span m="4279850">you</span>
  <span m="4280000">apply</span> <span m="4280420">Szemeredi's</span> <span m="4281050">Regularity</span>
  <span m="4281690">Lemma,</span> <span m="4282360">and</span> <span m="4282610">once</span>
  <span m="4282970">you</span> <span m="4283120">are</span> <span m="4283270">OK</span>
  <span m="4283810">with</span> <span m="4284110">some</span> <span m="4284530">epsilon</span>
  <span m="4285070">approximations,</span> <span m="4286400">there</span> <span m="4286600">is</span>
  <span m="4286750">only</span> <span m="4287980">a</span> <span m="4288070">small</span>
  <span m="4288790">description,</span> <span m="4289510">this</span> <span m="4289760">bounded</span>
  <span m="4290440">description,</span> <span m="4291220">of</span> <span m="4291340">a</span>
  <span m="4291370">graph.</span> <span m="4292280">And</span> <span m="4292300">you</span>
  <span m="4292360">can</span> <span m="4292510">work</span> <span m="4292780">with</span>
  <span m="4292930">that</span> <span m="4293080">description.</span> <span m="4295060">And</span>
  <span m="4295240">these</span> <span m="4295720">two</span> <span m="4296020">philosophies,</span>
  <span m="4296740">it's</span> <span m="4296890">no</span> <span m="4297190">coincidence</span>
  <span m="4297820">that</span> <span m="4298000">they</span> <span m="4298210">are</span>
  <span m="4299740">consistent</span> <span m="4300340">with</span> <span m="4300520">each</span>
  <span m="4300700">other</span> <span m="4301270">because</span> <span m="4302320">we</span>
  <span m="4302470">will</span> <span m="4302650">use</span> <span m="4303380">Szemeredi's</span>
  <span m="4304480">Regularity</span> <span m="4305110">Lemma</span> <span m="4305740">to</span>
  <span m="4305950">prove</span> <span m="4306790">this</span> <span m="4306970">compactness.</span></p><p><span
  m="4309710">In</span> <span m="4309830">fact,</span> <span m="4310170">we</span>
  <span m="4310190">will</span> <span m="4310310">use</span> <span m="4310580">a</span>
  <span m="4310640">slightly</span> <span m="4311090">weaker</span> <span m="4311510">version</span>
  <span m="4311900">of</span> <span m="4311990">Szemeredi's</span> <span m="4312500">Regularity</span>
  <span m="4313010">Lemma</span> <span m="4313550">to</span> <span m="4313670">prove</span>
  <span m="4314060">compactness.</span> <span m="4315560">And</span> <span m="4315710">then</span>
  <span m="4316100">you</span> <span m="4316520">will</span> <span m="4316670">see</span>
  <span m="4316880">that,</span> <span m="4317060">from</span> <span m="4317480">the</span>
  <span m="4317570">compactness,</span> <span m="4318890">one</span> <span m="4319130">can</span>
  <span m="4320850">use</span> <span m="4321450">properties</span> <span m="4321960">of</span>
  <span m="4322030">the</span> <span m="4322080">compactness</span> <span m="4323010">to</span>
  <span m="4323190">boost</span> <span m="4323670">to</span> <span m="4323880">a</span>
  <span m="4323940">stronger</span> <span m="4324480">version</span> <span m="4324900">of</span>
  <span m="4324990">regularity.</span> <span m="4327750">But</span> <span m="4327850">the</span>
  <span m="4327940">underlying</span> <span m="4328300">philosophy</span> <span m="4328840">here</span>
  <span m="4329890">is</span> <span m="4330070">that</span> <span m="4330490">this</span>
  <span m="4331360">compactness</span> <span m="4336240">is</span> <span m="4336630">in</span>
  <span m="4336780">some</span> <span m="4336990">sense</span> <span m="4338230">a</span>
  <span m="4338310">quantity.</span> <span m="4339570">It's</span> <span m="4339930">a</span>
  <span m="4340020">qualitative</span> <span m="4347130">reformulation,</span> <span
  m="4349530">analytic</span> <span m="4350070">reformulation</span> <span m="4356610">of</span>
  <span m="4356980">Szemeredi's</span> <span m="4358230">Graph</span> <span m="4358530">Regularity</span>
  <span m="4359030">Lemma.</span> <span m="4371030">OK,</span> <span m="4371520">so--</span></p><p><span
  m="4373780">So</span> <span m="4373970">this</span> <span m="4374150">topic,</span>
  <span m="4374690">this</span> <span m="4374900">graph</span> <span m="4375170">limits,</span>
  <span m="4375560">which</span> <span m="4376310">we'll</span> <span m="4376490">explore</span>
  <span m="4376850">for</span> <span m="4376940">the</span> <span m="4377030">next</span>
  <span m="4377270">few</span> <span m="4377420">lecturers,</span> <span m="4377840">including</span>
  <span m="4378230">giving</span> <span m="4378530">a</span> <span m="4378590">proof</span>
  <span m="4378950">of</span> <span m="4379520">all</span> <span m="4379670">three</span>
  <span m="4379940">of</span> <span m="4380030">these</span> <span m="4380210">main</span>
  <span m="4380450">theorems,</span> <span m="4381620">nicely</span> <span m="4382040">encapsulates</span>
  <span m="4382820">the</span> <span m="4382940">past</span> <span m="4383390">couple</span>
  <span m="4383750">of</span> <span m="4383870">topics</span> <span m="4384350">we
  have</span> <span m="4384530">done.</span> <span m="4385250">So</span> <span m="4385370">on</span>
  <span m="4385430">one</span> <span m="4385610">hand,</span> <span m="4385820">Szemeredi's</span>
  <span m="4386510">Regularity</span> <span m="4387140">Lemma,</span> <span m="4388040">or</span>
  <span m="4388160">some</span> <span m="4388430">version</span> <span m="4388760">of</span>
  <span m="4388850">that,</span> <span m="4389000">will</span> <span m="4389120">be</span>
  <span m="4389240">used</span> <span m="4389930">in</span> <span m="4390080">proving</span>
  <span m="4390890">the</span> <span m="4391910">existence</span> <span m="4392450">of</span>
  <span m="4392510">the</span> <span m="4392590">limit</span> <span m="4393030">and</span>
  <span m="4393080">also</span> <span m="4393290">the</span> <span m="4393380">compactness.</span>
  <span m="4394520">And</span> <span m="4394640">also</span> <span m="4394940">it's</span>
  <span m="4395090">philosophically</span> <span m="4395870">and</span> <span m="4396800">in</span>
  <span m="4396920">some</span> <span m="4397130">sense</span> <span m="4397370">related</span>
  <span m="4397685">and</span> <span m="4398000">very</span> <span m="4398210">much</span>
  <span m="4398450">equivalent</span> <span m="4399320">in</span> <span m="4399410">some</span>
  <span m="4399590">sense</span> <span m="4399830">and</span> <span m="4399920">related</span>
  <span m="4400310">to</span> <span m="4401420">these</span> <span m="4401630">notions.</span>
  <span m="4402830">It</span> <span m="4402950">is</span> <span m="4403070">also</span>
  <span m="4403280">related</span> <span m="4403670">to</span> <span m="4404600">quasirandomness--</span>
  <span m="4405710">in</span> <span m="4405800">particular,</span> <span m="4407030">quasirandom</span>
  <span m="4407720">graphs</span> <span m="4408320">that</span> <span m="4408470">we</span>
  <span m="4408620">did</span> <span m="4408800">a</span> <span m="4408830">few</span>
  <span m="4409010">lectures</span> <span m="4409370">ago,</span> <span m="4410160">where</span>
  <span m="4410300">in</span> <span m="4410390">quasirandom</span> <span m="4411080">graphs,</span>
  <span m="4411680">we</span> <span m="4411830">are</span> <span m="4411890">really</span>
  <span m="4412130">looking</span> <span m="4412490">at</span> <span m="4413150">the</span>
  <span m="4413630">constant</span> <span m="4414190">graphon</span> <span m="4415030">in</span>
  <span m="4415250">this</span> <span m="4415430">language.</span></p><p><span m="4416890">And</span>
  <span m="4417080">now</span> <span m="4417420">we</span> <span m="4418140">expand</span>
  <span m="4418590">our</span> <span m="4418710">horizons.</span> <span m="4419340">And</span>
  <span m="4419910">instead</span> <span m="4420330">of</span> <span m="4420660">just</span>
  <span m="4420930">looking</span> <span m="4421260">at</span> <span m="4421350">the</span>
  <span m="4421440">constant</span> <span m="4421920">graphon,</span> <span m="4423570">we</span>
  <span m="4423690">can</span> <span m="4423810">now</span> <span m="4424290">consider</span>
  <span m="4425580">arbitrary</span> <span m="4426030">graphons.</span> <span m="4427840">They</span>
  <span m="4428150">are</span> <span m="4428740">also</span> <span m="4429060">this</span>
  <span m="4429720">model</span> <span m="4430170">for</span> <span m="4430980">a</span>
  <span m="4431070">very</span> <span m="4431340">large</span> <span m="4431640">graph.</span>
  <span m="4434530">Any</span> <span m="4434720">questions?</span> <span m="4436120">Yeah?</span></p><p><span
  m="4436610">AUDIENCE:</span> <span m="4436855">Can</span> <span m="4437100">we</span>
  <span m="4437590">prove the</span> <span m="4438080">theorem</span> <span m="4439060">analytically</span>
  <span m="4439550">and</span> <span m="4440040">then</span> <span m="4440530">deduce</span>
  <span m="4441020">the Regularity</span> <span m="4441510">Lemma</span> <span m="4442000">with
  it?</span></p><p><span m="4442490">YUFEI ZHAO:</span> <span m="4442735">The</span>
  <span m="4442980">question</span> <span m="4443390">is,</span> <span m="4443560">can</span>
  <span m="4443740">we</span> <span m="4443950">prove</span> <span m="4444520">Theorem</span>
  <span m="4444850">3</span> <span m="4445300">analytically</span> <span m="4445900">and</span>
  <span m="4446020">deduce</span> <span m="4446350">the</span> <span m="4446440">Regularity</span>
  <span m="4446980">Lemma?</span> <span m="4447520">So</span> <span m="4447640">you
  will</span> <span m="4447820">see</span> <span m="4448030">once</span> <span m="4448270">you</span>
  <span m="4448360">see</span> <span m="4448510">the</span> <span m="4448630">proof.</span>
  <span m="4449990">It</span> <span m="4450490">depends</span> <span m="4450970">on</span>
  <span m="4451150">what</span> <span m="4451300">you</span> <span m="4451390">mean.</span>
  <span m="4451600">But</span> <span m="4451780">roughly,</span> <span m="4452150">the</span>
  <span m="4452260">answer</span> <span m="4452530">is</span> <span m="4452680">yes.</span></p><p><span
  m="4452990">But</span> <span m="4453130">there's</span> <span m="4453340">a</span>
  <span m="4453400">very</span> <span m="4453550">important</span> <span m="4454000">caveat.</span>
  <span m="4454840">It's</span> <span m="4454990">that,</span> <span m="4455290">because</span>
  <span m="4455730">we</span> <span m="4455800">are</span> <span m="4455890">using</span>
  <span m="4456190">compactness,</span> <span m="4457930">any</span> <span m="4458170">argument</span>
  <span m="4458830">involving</span> <span m="4459250">compactness</span> <span m="4460390">gives</span>
  <span m="4460690">no</span> <span m="4461020">quantitative</span> <span m="4461740">bounds.</span>
  <span m="4463750">So</span> <span m="4463990">you</span> <span m="4464110">will</span>
  <span m="4464200">have</span> <span m="4464470">a</span> <span m="4464530">proof</span>
  <span m="4465100">of</span> <span m="4465880">the</span> <span m="4467080">Szemeredi</span>
  <span m="4467580">Regularity</span> <span m="4468160">Lemma</span> <span m="4468940">that</span>
  <span m="4469090">tells</span> <span m="4469420">you</span> <span m="4469690">there</span>
  <span m="4469990">is</span> <span m="4470200">a</span> <span m="4470530">bound</span>
  <span m="4471160">for</span> <span m="4471370">each</span> <span m="4472210">epsilon.</span>
  <span m="4473020">But</span> <span m="4473200">it</span> <span m="4473290">doesn't</span>
  <span m="4473530">tell</span> <span m="4473740">you</span> <span m="4473890">what</span>
  <span m="4474110">the</span> <span m="4474220">bound</span> <span m="4474535">is.</span>
  <span m="4477305">Yeah?</span></p><p><span m="4478778">AUDIENCE:</span> <span m="4479023">Doesn't</span>
  <span m="4479269">Theorem</span> <span m="4479760">3 imply Theorem</span> <span
  m="4480251">1</span> <span m="4480742">because</span> <span m="4481724">of the</span>
  <span m="4482215">[INAUDIBLE]?</span></p><p><span m="4486150">YUFEI ZHAO:</span>
  <span m="4486255">Does</span> <span m="4486360">Code</span> <span m="4486690">Theorem</span>
  <span m="4486990">3</span> <span m="4487260">imply</span> <span m="4487620">Theorem</span>
  <span m="4487950">1?</span> <span m="4488280">And</span> <span m="4488370">the</span>
  <span m="4488490">answer</span> <span m="4488730">is</span> <span m="4488850">no</span>
  <span m="4489180">because</span> <span m="4489540">in</span> <span m="4489810">Theorem</span>
  <span m="4490160">1,</span> <span m="4490800">the</span> <span m="4490980">notion</span>
  <span m="4491430">of</span> <span m="4491520">convergence</span> <span m="4492570">is</span>
  <span m="4492850">about</span> <span m="4493320">homomorphism</span> <span m="4493840">densities.</span>
  <span m="4495800">So</span> <span m="4495970">Theorem</span> <span m="4496360">1</span>
  <span m="4496990">is</span> <span m="4497290">about</span> <span m="4497680">these</span>
  <span m="4497920">two</span> <span m="4498220">different</span> <span m="4498550">notions</span>
  <span m="4499000">of</span> <span m="4499090">convergence</span> <span m="4499780">and</span>
  <span m="4499930">that</span> <span m="4500110">they</span> <span m="4500190">are</span>
  <span m="4500320">equivalent</span> <span m="4500890">to</span> <span m="4501040">each</span>
  <span m="4501250">other.</span> <span m="4502730">Theorem</span> <span m="4503100">3</span>
  <span m="4503590">is</span> <span m="4503830">just</span> <span m="4504190">about</span>
  <span m="4504700">the</span> <span m="4504820">metric.</span> <span m="4505420">It's</span>
  <span m="4505570">about</span> <span m="4505830">the</span> <span m="4505900">cut</span>
  <span m="4506270">metric.</span></p><p><span m="4507506">And so</span> <span m="4507890">Theorem</span>
  <span m="4508170">1</span> <span m="4508550">is--</span> <span m="4508900">the</span>
  <span m="4508990">point</span> <span m="4509260">of</span> <span m="4509350">Theorem</span>
  <span m="4509620">1</span> <span m="4509890">is</span> <span m="4509980">that</span>
  <span m="4510070">you</span> <span m="4510190">have</span> <span m="4510340">these</span>
  <span m="4510520">two--</span> <span m="4511470">you</span> <span m="4511720">have</span>
  <span m="4511840">these</span> <span m="4512020">two</span> <span m="4512260">notions</span>
  <span m="4512710">of</span> <span m="4512800">convergence,</span> <span m="4513670">one</span>
  <span m="4513940">having</span> <span m="4514180">to</span> <span m="4514240">do</span>
  <span m="4514390">with</span> <span m="4514570">subgraph</span> <span m="4515080">densities</span>
  <span m="4515890">and</span> <span m="4516010">the</span> <span m="4516130">other</span>
  <span m="4516340">having</span> <span m="4516580">to</span> <span m="4516640">do</span>
  <span m="4516790">with</span> <span m="4516990">a</span> <span m="4517030">cut</span>
  <span m="4517300">distance.</span> <span m="4518120">And</span> <span m="4518140">in</span>
  <span m="4518200">fact,</span> <span m="4518630">they are</span> <span m="4518900">equivalent</span>
  <span m="4519490">notions.</span> <span m="4523140">So</span> <span m="4523320">all</span>
  <span m="4523440">great</span> <span m="4523620">questions--</span> <span m="4524870">any</span>
  <span m="4525110">others?</span></p><p><span m="4525959">AUDIENCE:</span> <span
  m="4526198">And</span> <span m="4526438">for that F,</span> <span m="4526917">is
  F</span> <span m="4527396">a graphon</span> <span m="4527875">because</span> <span
  m="4528354">the</span> <span m="4528833">[INAUDIBLE]?</span> <span m="4530270">Is</span>
  <span m="4530749">F a</span> <span m="4531228">graphon or</span> <span m="4531707">a
  graph?</span></p><p><span m="4532950">YUFEI ZHAO:</span> <span m="4533110">The</span>
  <span m="4533270">question is,</span> <span m="4533660">is</span> <span m="4533710">F</span>
  <span m="4533760">a</span> <span m="4533810">graph</span> <span m="4534470">or</span>
  <span m="4534600">a</span> <span m="4534620">graphon?</span> <span m="4535130">F</span>
  <span m="4535370">is</span> <span m="4535580">always</span> <span m="4535910">a</span>
  <span m="4535970">graph.</span> <span m="4537300">So</span> <span m="4537620">in</span>
  <span m="4537980">t</span> <span m="4539220">F,</span> <span m="4539680">W,</span>
  <span m="4541760">I</span> <span m="4541880">do</span> <span m="4542060">not</span>
  <span m="4542390">define</span> <span m="4542870">this</span> <span m="4543020">quantity</span>
  <span m="4543590">for</span> <span m="4544130">graphon</span> <span m="4545090">F.</span>
  <span m="4545880">So</span> <span m="4546080">this</span> <span m="4546320">quantity</span>
  <span m="4546750">here,</span> <span m="4547470">I have</span> <span m="4547650">only</span>
  <span m="4548000">allowed</span> <span m="4548300">the</span> <span m="4548360">second</span>
  <span m="4548810">argument</span> <span m="4549200">to</span> <span m="4549320">be</span>
  <span m="4549470">a</span> <span m="4549530">graphon.</span> <span m="4550580">The</span>
  <span m="4550670">first</span> <span m="4550950">argument</span> <span m="4551120">is</span>
  <span m="4551450">not</span> <span m="4551750">allowed</span> <span m="4551990">to</span>
  <span m="4552110">be</span> <span m="4552230">a</span> <span m="4552290">graphon.</span>
  <span m="4552740">It</span> <span m="4552830">doesn't</span> <span m="4553040">make</span>
  <span m="4553160">sense.</span> <span m="4556306">Yeah?</span></p><p><span m="4556777">AUDIENCE:</span>
  <span m="4557012">Doesn't</span> <span m="4557248">Theorem</span> <span m="4557719">1
  and</span> <span m="4558190">2</span> <span m="4558661">together</span> <span m="4559132">imply</span>
  <span m="4559603">Theorem</span> <span m="4560074">3?</span></p><p><span m="4561110">YUFEI
  ZHAO:</span> <span m="4561240">The</span> <span m="4561370">question is,</span>
  <span m="4561690">doesn't</span> <span m="4562260">Theorem</span> <span m="4562560">1
  and</span> <span m="4562810">Theorem</span> <span m="4562890">2</span> <span m="4563310">together</span>
  <span m="4563950">imply</span> <span m="4564350">Theorem</span> <span m="4564650">3?</span>
  <span m="4565240">So</span> <span m="4565260">first</span> <span m="4565470">of</span>
  <span m="4565530">all,</span> <span m="4565650">Theorem</span> <span m="4565950">1</span>
  <span m="4567120">is</span> <span m="4567330">really--</span> <span m="4567780">it's</span>
  <span m="4568170">not</span> <span m="4568440">about</span> <span m="4569250">compactness.</span>
  <span m="4570270">So</span> <span m="4570420">it's</span> <span m="4570570">really</span>
  <span m="4570750">about</span> <span m="4570900">the</span> <span m="4571050">equivalence</span>
  <span m="4571590">of</span> <span m="4571680">two</span> <span m="4571890">different</span>
  <span m="4572160">notions</span> <span m="4572580">of</span> <span m="4572670">convergence.</span>
  <span m="4573780">It's</span> <span m="4573900">like</span> <span m="4574080">you</span>
  <span m="4574170">have</span> <span m="4574350">two</span> <span m="4574500">different</span>
  <span m="4574770">metrics.</span> <span m="4575160">I am</span> <span m="4575280">showing</span>
  <span m="4575530">that</span> <span m="4575610">these</span> <span m="4575760">two</span>
  <span m="4575940">metrics</span> <span m="4576300">are</span> <span m="4576390">equivalent</span>
  <span m="4576900">to</span> <span m="4577020">each</span> <span m="4577200">other.</span></p><p><span
  m="4578300">Theorem</span> <span m="4578560">2</span> <span m="4578720">and</span>
  <span m="4578930">Theorem</span> <span m="4579180">3</span> <span m="4579480">are</span>
  <span m="4579750">quite</span> <span m="4580110">intimately</span> <span m="4580620">related.</span>
  <span m="4581430">So</span> <span m="4581610">Theorem</span> <span m="4581940">2</span>
  <span m="4582300">is</span> <span m="4582450">about--</span> <span m="4585590">Theorem</span>
  <span m="4585910">2,</span> <span m="4586310">so</span> <span m="4587000">they</span>
  <span m="4587190">are</span> <span m="4587270">quite</span> <span m="4587610">related.</span>
  <span m="4587870">But</span> <span m="4588140">they're</span> <span m="4588290">not</span>
  <span m="4588470">quite</span> <span m="4588680">the</span> <span m="4588740">same.</span></p><p><span
  m="4589080">So</span> <span m="4589180">let</span> <span m="4589280">me</span> <span
  m="4589380">just</span> <span m="4589400">give</span> <span m="4589610">you</span>
  <span m="4589760">the</span> <span m="4590150">real</span> <span m="4590480">line</span>
  <span m="4590780">analogy,</span> <span m="4591290">going</span> <span m="4591530">back</span>
  <span m="4591680">to</span> <span m="4591770">what</span> <span m="4591890">we</span>
  <span m="4592010">said</span> <span m="4592190">in</span> <span m="4592280">the</span>
  <span m="4592370">beginning.</span> <span m="4593140">So</span> <span m="4593390">Theorem</span>
  <span m="4593720">2</span> <span m="4594050">is</span> <span m="4594200">kind</span>
  <span m="4594500">of</span> <span m="4594560">like</span> <span m="4594770">saying</span>
  <span m="4595520">that</span> <span m="4596060">the</span> <span m="4596210">real</span>
  <span m="4596600">numbers</span> <span m="4597260">is</span> <span m="4597410">complete.</span>
  <span m="4598490">Every</span> <span m="4598700">convergent</span> <span m="4599270">sequence</span>
  <span m="4599750">has</span> <span m="4599960">a</span> <span m="4600020">limit,</span>
  <span m="4600870">whereas</span> <span m="4601340">Theorem</span> <span m="4601630">3</span>
  <span m="4601940">is</span> <span m="4602330">more</span> <span m="4602600">than</span>
  <span m="4602750">that.</span></p><p><span m="4603060">It's</span> <span m="4603110">also</span>
  <span m="4604040">bounded</span> <span m="4604850">in</span> <span m="4604940">some</span>
  <span m="4605150">sense. But</span> <span m="4605440">here,</span> <span m="4605780">there
  is</span> <span m="4605920">no</span> <span m="4606110">notion</span> <span m="4606440">of</span>
  <span m="4606530">bounded.</span> <span m="4608240">It's</span> <span m="4608390">compact.</span>
  <span m="4611570">But</span> <span m="4611860">the</span> <span m="4612240">main--</span>
  <span m="4613250">you</span> <span m="4613400">should</span> <span m="4613640">think</span>
  <span m="4613910">of</span> <span m="4614000">these</span> <span m="4614240">two</span>
  <span m="4614420">are</span> <span m="4614540">very</span> <span m="4614780">much</span>
  <span m="4614990">related</span> <span m="4615350">to</span> <span m="4615500">each</span>
  <span m="4615680">other.</span> <span m="4615890">But</span> <span m="4616360">here</span>
  <span m="4616660">it's--</span> <span m="4617840">but</span> <span m="4617980">they
  are</span> <span m="4618110">not</span> <span m="4618350">equivalent.</span></p><p><span
  m="4622760">Anything</span> <span m="4623030">else?</span> <span m="4626020">Great.</span>
  <span m="4626410">So</span> <span m="4626500">that's</span> <span m="4626680">all</span>
  <span m="4626770">for</span> <span m="4626860">today.</span></p>
type: course
uid: e4fc7771fc71a9b734509d1e25084236

---
None