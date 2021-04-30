---
about_this_resource_text: "<p><strong>Description:</strong> A famous open problem\
  \ says that no set of integers can simultaneously have a small sum set A+A and a\
  \ small product set AA. In the final lecture of this course, Professor Zhao explains\
  \ two bounds, with the first using tools from graph theory and incidence geometry,\
  \ and the second using multiplicative energy.\r\n\r\n</p>\r\n<p><strong>Instructor:</strong>\
  \ Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: ydyiq1Z22gc
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  title: Video-YouTube-Stream
  type: Video
  uid: 9d5c1eb3adba403b121ca8475528a5a4
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/ydyiq1Z22gc/default.jpg
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 79d1604c81ec341727c00c76f8d594f1
- id: 3Play-3PlayYouTubeid-MP4
  media_location: ydyiq1Z22gc
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: cf0871b8ccadf5dcc87df82c4b5846bc
- id: ydyiq1Z22gc.srt
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-26-sum-product-problem-and-incidence-geometry/ydyiq1Z22gc.srt
  title: 3play caption file
  type: null
  uid: bd82d350c921136bd7d3fb9799c475db
- id: ydyiq1Z22gc.pdf
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-26-sum-product-problem-and-incidence-geometry/ydyiq1Z22gc.pdf
  title: 3play pdf file
  type: null
  uid: e5b7afd33c59805a70a8836bbcdd6608
- id: Caption-3Play YouTube id-SRT
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e99bd3edfae50f436b1764b8af9ffaf0
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 420047c8edbb8760bfb0cdc4d0e8ff5a
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec26_300k.mp4
  parent_uid: 041b5e96b65771fa0e0b4b0a927db8ed
  title: Video-Internet Archive-MP4
  type: Video
  uid: 0b1b8edfa093df1ebebccd103052df0a
inline_embed_id: 75368336lecture26sumproductproblemandincidencegeometry91048665
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-26-sum-product-problem-and-incidence-geometry
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-26-sum-product-problem-and-incidence-geometry
template_type: Tabbed
title: "Lecture 26: Sum-Product Problem and Incidence Geometry\t"
transcript: <p><span m="17880">YUFEI ZHAO:</span> <span m="18015">Today</span> <span
  m="18150">we</span> <span m="18270">want</span> <span m="18510">to</span> <span
  m="19080">look</span> <span m="19320">at</span> <span m="19710">the</span> <span
  m="20010">sum</span> <span m="20400">product</span> <span m="20820">problem.</span>
  <span m="21730">So</span> <span m="21810">for</span> <span m="21870">the</span>
  <span m="21960">past</span> <span m="22230">few</span> <span m="22410">lectures,</span>
  <span m="22930">we've</span> <span m="22980">been</span> <span m="23130">discussing</span>
  <span m="23640">the</span> <span m="23730">structure</span> <span m="24180">of</span>
  <span m="24660">sets</span> <span m="25260">under</span> <span m="25860">the</span>
  <span m="26010">addition</span> <span m="26490">operation.</span> <span m="28380">Today</span>
  <span m="28650">we're</span> <span m="28830">going</span> <span m="29040">to</span>
  <span m="29190">throw</span> <span m="29490">in</span> <span m="29610">one</span>
  <span m="29820">extra</span> <span m="30090">operation,</span> <span m="30790">so</span>
  <span m="31050">multiplication,</span> <span m="32189">and</span> <span m="32460">understand</span>
  <span m="33030">how</span> <span m="33310">sets</span> <span m="33630">behave</span>
  <span m="34170">under</span> <span m="34470">both</span> <span m="34830">addition</span>
  <span m="35610">and</span> <span m="35910">multiplication.</span></p><p><span m="37920">And</span>
  <span m="38010">the</span> <span m="38100">basic</span> <span m="38460">problem</span>
  <span m="38790">here</span> <span m="39270">is,</span> <span m="40280">can</span>
  <span m="40500">it</span> <span m="40560">be</span> <span m="40680">the</span> <span
  m="40800">case</span> <span m="41280">that</span> <span m="42210">A</span> <span
  m="43380">plus</span> <span m="43720">A,</span> <span m="46170">A</span> <span m="46410">times</span>
  <span m="46740">A,</span> <span m="47980">which</span> <span m="48090">is,</span>
  <span m="48960">analogously,</span> <span m="49980">the</span> <span m="50160">set</span>
  <span m="50430">of</span> <span m="50550">all</span> <span m="50730">pairwise</span>
  <span m="51270">products</span> <span m="52470">of</span> <span m="52680">elements</span>
  <span m="53520">from</span> <span m="53790">A--</span> <span m="55860">can</span>
  <span m="56070">these</span> <span m="56340">two</span> <span m="56520">sets</span>
  <span m="57030">be</span> <span m="58410">simultaneously</span> <span m="59400">small,</span>
  <span m="65760">that is,</span> <span m="66130">the</span> <span m="66250">same</span>
  <span m="66610">for</span> <span m="66840">some</span> <span m="67750">single</span>
  <span m="68140">A?</span> <span m="71710">Can</span> <span m="71920">we</span> <span
  m="72040">have</span> <span m="72310">it</span> <span m="72400">so</span> <span
  m="72550">that</span> <span m="75820">A</span> <span m="76060">plus</span> <span
  m="76420">A</span> <span m="76630">and</span> <span m="76810">A</span> <span m="76960">times</span>
  <span m="77290">A</span> <span m="77710">are</span> <span m="78070">simultaneously</span>
  <span m="78970">small?</span> <span m="80690">For</span> <span m="80740">example,</span>
  <span m="81560">it's</span> <span m="81610">easy</span> <span m="81850">to</span>
  <span m="81940">make</span> <span m="82630">one</span> <span m="82810">of</span>
  <span m="82870">them</span> <span m="83050">small.</span></p><p><span m="84470">We've</span>
  <span m="84620">seen</span> <span m="84830">examples</span> <span m="85730">where</span>
  <span m="86600">if</span> <span m="86720">you</span> <span m="86810">take</span>
  <span m="87110">A</span> <span m="87380">to</span> <span m="87530">be</span> <span
  m="88520">an</span> <span m="88700">arithmetic</span> <span m="89210">progression,</span>
  <span m="90590">then</span> <span m="90800">A</span> <span m="90950">plus</span>
  <span m="91250">A</span> <span m="91430">is</span> <span m="92180">more</span> <span
  m="92330">or</span> <span m="92360">less</span> <span m="92510">as</span> <span
  m="92570">small</span> <span m="92870">as</span> <span m="92990">it</span> <span
  m="93050">gets.</span> <span m="94400">But</span> <span m="94510">for</span> <span
  m="94700">such</span> <span m="94940">an</span> <span m="95030">example,</span>
  <span m="95420">you</span> <span m="95480">see</span> <span m="95780">A</span> <span
  m="95960">times</span> <span m="96320">A</span> <span m="97160">is</span> <span
  m="97970">pretty</span> <span m="98240">large.</span> <span m="99710">It's</span>
  <span m="99810">actually</span> <span m="99920">not</span> <span m="100220">so</span>
  <span m="100520">clear</span> <span m="101340">how</span> <span m="101480">to</span>
  <span m="101570">prove</span> <span m="102020">how</span> <span m="102230">large</span>
  <span m="102530">it</span></p><p><span m="102620">Is.</span> <span m="103940">And</span>
  <span m="104210">there</span> <span m="104330">are</span> <span m="104390">some</span>
  <span m="104570">very</span> <span m="104750">nice</span> <span m="105020">proofs.</span>
  <span m="105320">And</span> <span m="105410">this</span> <span m="105560">problem</span>
  <span m="105800">has</span> <span m="105980">actually</span> <span m="106250">been</span>
  <span m="107150">more</span> <span m="107330">or</span> <span m="107360">less</span>
  <span m="107570">pinned</span> <span m="107870">down.</span> <span m="108620">But</span>
  <span m="108920">the</span> <span m="109100">short</span> <span m="109460">version</span>
  <span m="110030">is</span> <span m="110210">that</span> <span m="111380">A</span>
  <span m="111920">times</span> <span m="112250">A</span> <span m="113070">has</span>
  <span m="113210">size</span> <span m="113930">close</span> <span m="114350">to</span>
  <span m="114770">its</span> <span m="114950">maximum</span> <span m="115520">possible.</span></p><p><span
  m="119600">So</span> <span m="119750">it</span> <span m="119810">turns</span> <span
  m="120080">out</span> <span m="120680">the</span> <span m="120740">size</span> <span
  m="121100">of</span> <span m="121250">A</span> <span m="121400">times</span> <span
  m="121680">A</span> <span m="122630">is</span> <span m="123320">almost</span> <span
  m="123860">quadratic.</span> <span m="125690">So</span> <span m="125810">this</span>
  <span m="125990">number</span> <span m="126230">is</span> <span m="126350">actually</span>
  <span m="126590">now</span> <span m="126830">known</span> <span m="127130">fairly</span>
  <span m="127430">precisely.</span> <span m="128009">So</span> <span m="129020">this</span>
  <span m="129229">problem</span> <span m="129800">of</span> <span m="129919">determining</span>
  <span m="131000">the</span> <span m="131120">size</span> <span m="131540">of</span>
  <span m="131990">A</span> <span m="132110">times</span> <span m="132410">A</span>
  <span m="132920">for</span> <span m="133800">the</span> <span m="133910">interval</span>
  <span m="134300">1</span> <span m="134540">through</span> <span m="134720">N</span>
  <span m="135150">is</span> <span m="135320">known</span> <span m="135590">as</span>
  <span m="135770">the</span> <span m="136000">Erdos</span> <span m="137690">multiplication</span>
  <span m="138410">table</span> <span m="138770">problem.</span></p><p><span m="150190">So</span>
  <span m="150270">if</span> <span m="150420">you</span> <span m="150570">take</span>
  <span m="150810">an</span> <span m="151350">N</span> <span m="151560">by</span>
  <span m="151740">N</span> <span m="151950">multiplication</span> <span m="152610">table,</span>
  <span m="152910">how</span> <span m="153120">many</span> <span m="153330">numbers</span>
  <span m="153750">do</span> <span m="153810">you</span> <span m="153930">see</span>
  <span m="154140">in</span> <span m="154230">the</span> <span m="154320">table?</span>
  <span m="155920">So</span> <span m="156020">that</span> <span m="157260">turns</span>
  <span m="157470">out</span> <span m="157560">to</span> <span m="157620">be</span>
  <span m="157770">sub-quadratic,</span> <span m="158820">but</span> <span m="159030">not</span>
  <span m="159360">too</span> <span m="159570">sub-quadratic.</span> <span m="162170">So</span>
  <span m="163340">this</span> <span m="163490">problem</span> <span m="163730">has</span>
  <span m="163970">been</span> <span m="164210">more</span> <span m="164450">or</span>
  <span m="164480">less</span> <span m="164630">solved</span> <span m="164990">by</span>
  <span m="165170">Kevin</span> <span m="165470">Ford.</span> <span m="166130">And</span>
  <span m="166280">we</span> <span m="166430">now</span> <span m="166580">know</span>
  <span m="166910">a</span> <span m="167150">fairly</span> <span m="167480">precise</span>
  <span m="167960">expression,</span> <span m="168840">but</span> <span m="168890">I</span>
  <span m="168950">don't</span> <span m="169080">want</span> <span m="169250">to</span>
  <span m="170240">focus</span> <span m="170600">on</span> <span m="170690">that.</span>
  <span m="170840">That's</span> <span m="170990">not</span> <span m="171180">the</span>
  <span m="171230">topic</span> <span m="171620">of</span> <span m="171710">today's</span>
  <span m="172790">lecture.</span> <span m="174200">This</span> <span m="174350">is</span>
  <span m="174440">just</span> <span m="174590">an</span> <span m="174680">example.</span></p><p><span
  m="175700">Alternatively,</span> <span m="176270">you</span> <span m="176390">can</span>
  <span m="176570">take</span> <span m="177080">A</span> <span m="177230">times</span>
  <span m="177530">A</span> <span m="177950">to</span> <span m="178100">be</span>
  <span m="178280">quite</span> <span m="178550">small</span> <span m="178880">by</span>
  <span m="179150">taking</span> <span m="179540">A</span> <span m="179690">to</span>
  <span m="179810">be</span> <span m="179960">a</span> <span m="180020">geometric</span>
  <span m="180650">progression.</span> <span m="182400">Then</span> <span m="183010">it's</span>
  <span m="183200">not</span> <span m="183410">too</span> <span m="183560">hard</span>
  <span m="183740">to</span> <span m="183800">convince</span> <span m="184100">yourself</span>
  <span m="184820">that</span> <span m="185180">A</span> <span m="185330">plus</span>
  <span m="185640">A</span> <span m="186230">must</span> <span m="186500">be</span>
  <span m="187100">fairly</span> <span m="187460">large</span> <span m="187790">in</span>
  <span m="187880">that</span> <span m="188030">case.</span> <span m="188390">And</span>
  <span m="189120">the</span> <span m="189220">geometric</span> <span m="189650">progression</span>
  <span m="190070">doesn't</span> <span m="190310">have</span> <span m="190490">so</span>
  <span m="190640">much</span> <span m="190910">additive</span> <span m="191240">structure,</span>
  <span m="192140">so</span> <span m="192290">A</span> <span m="192410">plus</span>
  <span m="192700">A</span> <span m="192800">will</span> <span m="192960">be</span>
  <span m="193070">large.</span></p><p><span m="194630">So</span> <span m="194750">can</span>
  <span m="194930">you</span> <span m="195020">make</span> <span m="195920">A</span>
  <span m="196070">plus</span> <span m="196430">A</span> <span m="196790">and A</span>
  <span m="196950">times</span> <span m="197270">A</span> <span m="197960">simultaneously</span>
  <span m="198970">small?</span> <span m="200380">So</span> <span m="201130">there's</span>
  <span m="201410">this</span> <span m="201560">conjecture</span> <span m="202250">that</span>
  <span m="202400">the</span> <span m="202520">answer</span> <span m="202930">is</span>
  <span m="203090">no.</span> <span m="204470">And</span> <span m="204620">this</span>
  <span m="204830">is</span> <span m="205010">a</span> <span m="205070">famous</span>
  <span m="205460">conjecture</span> <span m="206480">in</span> <span m="206630">this</span>
  <span m="206810">area,</span> <span m="207250">known as</span> <span m="207710">the</span>
  <span m="208110">Erdos</span> <span m="208640">similarity</span> <span m="209180">conjecture</span>
  <span m="215350">on</span> <span m="215740">the sum</span> <span m="216070">product</span>
  <span m="216400">problem,</span> <span m="217330">which</span> <span m="217510">states</span>
  <span m="217840">that</span> <span m="218260">for</span> <span m="218500">all</span>
  <span m="219970">finite</span> <span m="220480">sets</span> <span m="220810">of</span>
  <span m="221050">real</span> <span m="221350">numbers,</span> <span m="223330">either</span>
  <span m="224560">A</span> <span m="224740">plus</span> <span m="225100">A</span>
  <span m="225910">or</span> <span m="226870">A</span> <span m="227020">times</span>
  <span m="227330">A</span> <span m="228730">has</span> <span m="229060">to</span>
  <span m="229180">be</span> <span m="230500">close</span> <span m="231010">to</span>
  <span m="232270">quadratic</span> <span m="232780">size.</span></p><p><span m="240300">So</span>
  <span m="240480">that's</span> <span m="241110">the</span> <span m="241200">conjecture.</span>
  <span m="241800">It's</span> <span m="241910">still</span> <span m="242220">very</span>
  <span m="242460">much</span> <span m="242670">open.</span> <span m="243810">Today</span>
  <span m="244080">I</span> <span m="244140">want</span> <span m="244290">to</span>
  <span m="244350">show</span> <span m="244560">you</span> <span m="244740">some</span>
  <span m="245280">progress</span> <span m="245760">towards</span> <span m="246060">this</span>
  <span m="246180">conjecture</span> <span m="246810">via</span> <span m="247010">some</span>
  <span m="247350">partial</span> <span m="247740">results.</span> <span m="248810">And</span>
  <span m="249330">it</span> <span m="249450">will</span> <span m="249570">use</span>
  <span m="249960">a</span> <span m="250020">nice</span> <span m="250320">combination</span>
  <span m="251370">of</span> <span m="252300">tools</span> <span m="252780">from</span>
  <span m="254130">graph</span> <span m="254430">theory</span> <span m="255090">and</span>
  <span m="255330">incidence</span> <span m="255750">geometry,</span> <span m="256519">so</span>
  <span m="256620">it</span> <span m="256680">nicely</span> <span m="257070">ties</span>
  <span m="257370">in</span> <span m="257459">together</span> <span m="258149">many</span>
  <span m="258420">of</span> <span m="258480">the</span> <span m="258570">things</span>
  <span m="258810">that</span> <span m="258899">we've</span> <span m="259050">seen</span>
  <span m="259500">in</span> <span m="259649">this</span> <span m="259829">course</span>
  <span m="260130">so</span> <span m="260339">far.</span></p><p><span m="262019">So</span>
  <span m="262150">Erdos</span> <span m="262370">and</span> <span m="262570">Szemeredi</span>
  <span m="263520">proved</span> <span m="264840">some</span> <span m="265140">bound,</span>
  <span m="265870">which</span> <span m="266010">is</span> <span m="266280">like</span>
  <span m="267450">1</span> <span m="267750">plus</span> <span m="268350">c</span>
  <span m="268680">for</span> <span m="268830">some</span> <span m="269070">constant</span>
  <span m="269445">c.</span> <span m="270610">Today</span> <span m="270810">we'll</span>
  <span m="271020">show</span> <span m="272040">some</span> <span m="272220">bounds</span>
  <span m="272590">for</span> <span m="272970">somewhat</span> <span m="273330">better</span>
  <span m="273690">c's.</span> <span m="275580">So</span> <span m="275700">you'll</span>
  <span m="275820">see.</span></p><p><span m="279350">The</span> <span m="279440">first</span>
  <span m="279720">tool</span> <span m="279980">that</span> <span m="280150">I</span>
  <span m="280220">want</span> <span m="280430">to</span> <span m="280520">introduce</span>
  <span m="281480">is</span> <span m="282170">a</span> <span m="282320">result</span>
  <span m="282650">from</span> <span m="282890">graph</span> <span m="283220">theory</span>
  <span m="283700">known as</span> <span m="284090">the</span> <span m="284210">&quot;crossing</span>
  <span m="284750">number</span> <span m="285150">inequality.&quot;</span> <span m="296660">So</span>
  <span m="296780">you</span> <span m="296840">know</span> <span m="296960">that</span>
  <span m="297080">planar</span> <span m="297650">graphs</span> <span m="298220">are</span>
  <span m="298340">graphs</span> <span m="298760">where</span> <span m="299000">you</span>
  <span m="299090">can</span> <span m="299270">draw</span> <span m="299570">on</span>
  <span m="299660">the</span> <span m="299730">planes</span> <span m="300100">so</span>
  <span m="300260">that</span> <span m="300440">the</span> <span m="300620">edges</span>
  <span m="300980">do</span> <span m="301130">not</span> <span m="301310">cross.</span>
  <span m="302230">And</span> <span m="302390">there</span> <span m="302510">are</span>
  <span m="302540">some</span> <span m="302780">famous</span> <span m="303110">examples</span>
  <span m="303560">of</span> <span m="303720">non-planar</span> <span m="304310">graphs,</span>
  <span m="305000">like</span> <span m="305300">K5</span> <span m="305980">and</span>
  <span m="306260">K</span> <span m="306470">3,</span> <span m="306680">3.</span></p><p><span
  m="309070">But</span> <span m="309700">you</span> <span m="309790">can</span> <span
  m="309940">ask</span> <span m="310150">a</span> <span m="310180">more</span> <span
  m="310360">quantitative</span> <span m="310930">question.</span> <span m="311560">If</span>
  <span m="311680">I</span> <span m="311770">give</span> <span m="312010">you</span>
  <span m="312160">a</span> <span m="312220">graph,</span> <span m="313030">how</span>
  <span m="313240">many</span> <span m="313480">crossings</span> <span m="314320">must</span>
  <span m="314860">you</span> <span m="315130">have</span> <span m="315640">in</span>
  <span m="315880">every</span> <span m="316150">drawing</span> <span m="316570">of</span>
  <span m="316720">this</span> <span m="316900">graph?</span> <span m="318280">And</span>
  <span m="318400">the</span> <span m="318460">crossing</span> <span m="318820">number</span>
  <span m="319030">inequality</span> <span m="319840">provides</span> <span m="320650">some</span>
  <span m="320950">estimate</span> <span m="321400">for</span> <span m="321580">such</span>
  <span m="321790">a</span> <span m="321850">quantity.</span></p><p><span m="322990">So</span>
  <span m="323110">given</span> <span m="323420">the</span> <span m="323470">graph</span>
  <span m="323830">G,</span> <span m="325540">denoted</span> <span m="326020">by</span>
  <span m="326760">cr,</span> <span m="327180">so</span> <span m="327520">crossing</span>
  <span m="328000">of</span> <span m="328090">G,</span> <span m="328600">to</span>
  <span m="328750">be</span> <span m="329260">the</span> <span m="329920">minimum</span>
  <span m="331540">number</span> <span m="332140">of</span> <span m="332470">crossings</span>
  <span m="336470">in</span> <span m="337970">a</span> <span m="338060">planar</span>
  <span m="340130">drawing</span> <span m="340640">of</span> <span m="340760">G.</span>
  <span m="344880">There</span> <span m="345280">is</span> <span m="345700">a</span>
  <span m="345760">bit</span> <span m="345970">of</span> <span m="346060">subtlety</span>
  <span m="346570">here,</span> <span m="346840">where</span> <span m="347380">by</span>
  <span m="347560">a</span> <span m="347590">planar</span> <span m="347920">drawing,</span>
  <span m="348310">do</span> <span m="348490">I</span> <span m="348580">mean</span>
  <span m="348910">using</span> <span m="349420">line</span> <span m="349720">segments</span>
  <span m="350470">or</span> <span m="350590">do</span> <span m="350770">I</span>
  <span m="350830">mean</span> <span m="351070">using</span> <span m="351430">curves?</span>
  <span m="352090">It's</span> <span m="352500">actually</span> <span m="352780">not</span>
  <span m="352990">clear</span> <span m="353800">how</span> <span m="354140">it</span>
  <span m="354340">affects</span> <span m="354970">this</span> <span m="355240">quantity</span>
  <span m="355690">here.</span> <span m="355990">That's</span> <span m="356170">a</span>
  <span m="356230">very</span> <span m="356410">subtle</span> <span m="356830">issue.</span></p><p><span
  m="357520">So</span> <span m="357670">for</span> <span m="357790">planar</span>
  <span m="358240">graphs,</span> <span m="358960">there's</span> <span m="359170">a</span>
  <span m="359380">famous</span> <span m="359740">result</span> <span m="360490">that</span>
  <span m="360610">more or</span> <span m="360760">less</span> <span m="361040">says</span>
  <span m="361580">if</span> <span m="361750">a</span> <span m="361810">planar</span>
  <span m="362215">graph</span> <span m="362620">can</span> <span m="362800">be</span>
  <span m="362890">drawn</span> <span m="363190">using</span> <span m="363460">continuous</span>
  <span m="363940">curves,</span> <span m="364270">then it</span> <span m="364420">can</span>
  <span m="364570">be</span> <span m="364660">drawn</span> <span m="365000">using</span>
  <span m="365500">straight</span> <span m="365800">lines.</span> <span m="366830">But</span>
  <span m="367560">the</span> <span m="367730">minimum</span> <span m="368170">number</span>
  <span m="368410">of</span> <span m="368470">crossings,</span> <span m="369490">the</span>
  <span m="369550">two</span> <span m="369820">different</span> <span m="370090">ways</span>
  <span m="370300">of</span> <span m="370360">drawings,</span> <span m="370810">they</span>
  <span m="371050">might</span> <span m="371280">end</span> <span m="371500">up</span>
  <span m="371590">with</span> <span m="371770">different</span> <span m="372280">crossing</span>
  <span m="372700">numbers.</span> <span m="373400">But</span> <span m="373500">for</span>
  <span m="373600">the</span> <span m="373690">purpose</span> <span m="374110">of</span>
  <span m="374450">today's</span> <span m="374800">lecture,</span> <span m="375230">we'll</span>
  <span m="375310">use</span> <span m="375520">a</span> <span m="375580">more</span>
  <span m="375760">general</span> <span m="376600">notion,</span> <span m="377260">although</span>
  <span m="377440">it</span> <span m="377530">doesn't</span> <span m="377770">actually</span>
  <span m="378010">matter</span> <span m="378250">for</span> <span m="378370">today</span>
  <span m="378860">which</span> <span m="378970">one</span> <span m="379120">we'll</span>
  <span m="379210">use--</span> <span m="379840">so</span> <span m="380080">planar</span>
  <span m="380440">drawing</span> <span m="381070">using</span> <span m="381490">curves.</span></p><p><span
  m="385870">Draw</span> <span m="386080">the</span> <span m="386170">graph</span>
  <span m="386650">where</span> <span m="387340">edges</span> <span m="387670">are</span>
  <span m="387790">continuous</span> <span m="388300">curves.</span> <span m="388810">How</span>
  <span m="388960">many</span> <span m="389200">crossings</span> <span m="389740">do</span>
  <span m="389830">you</span> <span m="389950">get?</span> <span m="390460">The</span>
  <span m="390520">crossing</span> <span m="390960">is</span> <span m="391090">a</span>
  <span m="391150">pair</span> <span m="391360">of</span> <span m="391540">edges</span>
  <span m="392265">that</span> <span m="392720">cross.</span></p><p><span m="395450">You</span>
  <span m="395550">can</span> <span m="395560">ask--</span> <span m="396370">it's
  just</span> <span m="396520">a</span> <span m="396610">cross</span> <span m="396820">over</span>
  <span m="397060">point</span> <span m="397410">that</span> <span m="397480">can--</span>
  <span m="398260">it</span> <span m="398350">doesn't</span> <span m="398560">matter.</span>
  <span m="399140">So</span> <span m="399220">there</span> <span m="399340">are</span>
  <span m="399400">many</span> <span m="399610">different</span> <span m="399970">subtle</span>
  <span m="400330">ways</span> <span m="400660">of</span> <span m="400750">defining</span>
  <span m="401650">these</span> <span m="401830">things.</span> <span m="402040">They</span>
  <span m="402160">won't</span> <span m="402370">really</span> <span m="402610">come</span>
  <span m="402820">up</span> <span m="402880">for</span> <span m="403030">today's</span>
  <span m="403390">lecture.</span></p><p><span m="404830">The</span> <span m="404950">crossing</span>
  <span m="405340">number</span> <span m="405560">inequality</span> <span m="407640">is</span>
  <span m="407800">a</span> <span m="407860">result</span> <span m="409510">from</span>
  <span m="409780">the</span> <span m="409870">'80s,</span> <span m="411140">which</span>
  <span m="411910">give</span> <span m="412150">you</span> <span m="412480">a</span>
  <span m="412750">lower-bound</span> <span m="413500">estimate</span> <span m="414010">on</span>
  <span m="414130">the</span> <span m="414190">number</span> <span m="414550">of</span>
  <span m="414670">crossings.</span> <span m="416530">If</span> <span m="417790">G</span>
  <span m="419200">is</span> <span m="420700">a</span> <span m="420850">graph</span>
  <span m="423620">with</span> <span m="424190">enough</span> <span m="424640">edges--</span>
  <span m="426470">the</span> <span m="426610">number</span> <span m="426890">of</span>
  <span m="427010">edges</span> <span m="427550">is,</span> <span m="427890">let's</span>
  <span m="427970">say,</span> <span m="428220">at</span> <span m="428320">least</span>
  <span m="428960">four</span> <span m="429260">times</span> <span m="429740">the</span>
  <span m="429830">number</span> <span m="430130">of</span> <span m="430190">vertices--</span>
  <span m="433530">then</span> <span m="436960">the</span> <span m="437050">number</span>
  <span m="437380">of</span> <span m="437500">crossings</span> <span m="438400">of</span>
  <span m="439600">every</span> <span m="439840">drawing</span> <span m="440260">of</span>
  <span m="440380">G</span> <span m="441220">is</span> <span m="441850">at</span>
  <span m="441970">least</span> <span m="443050">the</span> <span m="443140">number</span>
  <span m="443410">of</span> <span m="443530">edges</span> <span m="443890">cubed</span>
  <span m="444970">divided</span> <span m="445390">by</span> <span m="445570">the</span>
  <span m="445690">number</span> <span m="446110">of</span> <span m="446860">vertices</span>
  <span m="448090">squared.</span> <span m="448810">And</span> <span m="448990">there's</span>
  <span m="449230">an</span> <span m="449380">extra</span> <span m="449710">constant</span>
  <span m="450130">factor,</span> <span m="450670">which</span> <span m="451610">is</span>
  <span m="451810">some</span> <span m="452050">constant.</span> <span m="459380">So</span>
  <span m="459660">the</span> <span m="459760">constant</span> <span m="460150">does</span>
  <span m="460300">not</span> <span m="460480">depend</span> <span m="460750">on</span>
  <span m="460840">the</span> <span m="460900">graph.</span></p><p><span m="463570">In</span>
  <span m="463660">particular,</span> <span m="463945">if</span> <span m="464230">it</span>
  <span m="464270">has</span> <span m="464440">a</span> <span m="464500">lot</span>
  <span m="464770">of</span> <span m="464860">edges,</span> <span m="465760">then</span>
  <span m="467380">every</span> <span m="467590">drawing</span> <span m="467920">of</span>
  <span m="467980">G</span> <span m="468190">must</span> <span m="468430">have</span>
  <span m="468640">a</span> <span m="468700">lot</span> <span m="468940">of</span>
  <span m="469000">crossings.</span> <span m="470815">So</span> <span m="471220">the</span>
  <span m="471320">crossing</span> <span m="471550">number</span> <span m="471790">inequality</span>
  <span m="472300">was</span> <span m="472510">proved</span> <span m="473500">by</span>
  <span m="474010">two</span> <span m="474280">separate</span> <span m="474790">independent</span>
  <span m="475450">works,</span> <span m="476080">one</span> <span m="476230">by</span>
  <span m="476470">Ajtai,</span> <span m="477290">Chvatal,</span> <span m="478060">Newborn,</span>
  <span m="478570">Szemeredi</span> <span m="479440">and</span> <span m="479560">the</span>
  <span m="479680">other</span> <span m="479860">by</span> <span m="480160">Tom</span>
  <span m="480430">Leighton,</span> <span m="481150">our</span> <span m="481270">very</span>
  <span m="481480">own</span> <span m="481960">Tom</span> <span m="482170">Leighton.</span>
  <span m="486950">So</span> <span m="487070">let</span> <span m="487160">me</span>
  <span m="487340">first</span> <span m="487610">give</span> <span m="487790">you</span>
  <span m="487880">some</span> <span m="488810">consequences</span> <span m="489590">of</span>
  <span m="490370">this</span> <span m="490670">theorem,</span> <span m="491090">just</span>
  <span m="491300">for</span> <span m="491420">illustration.</span></p><p><span m="492690">So</span>
  <span m="492710">if</span> <span m="492920">you</span> <span m="493070">have</span>
  <span m="493400">an</span> <span m="493580">n-vertex</span> <span m="494240">graph</span>
  <span m="496640">with</span> <span m="497000">a</span> <span m="497120">quadratic</span>
  <span m="497630">number</span> <span m="497930">of</span> <span m="498050">edges,</span>
  <span m="504130">then</span> <span m="504330">how</span> <span m="504480">many</span>
  <span m="504690">crossings</span> <span m="505230">must</span> <span m="505530">you</span>
  <span m="505620">have?</span> <span m="506460">You</span> <span m="506610">plug
  in</span> <span m="507030">these</span> <span m="507240">parameters</span> <span
  m="507810">into</span> <span m="508050">the</span> <span m="508110">theorem.</span>
  <span m="509070">See</span> <span m="509280">that</span> <span m="509840">it</span>
  <span m="509970">has</span> <span m="510450">necessarily</span> <span m="512870">n</span>
  <span m="513090">to</span> <span m="513230">the 4th</span> <span m="515370">crossings.</span></p><p><span
  m="519100">But</span> <span m="519230">if</span> <span m="519380">you</span> <span
  m="519470">just</span> <span m="519650">draw</span> <span m="519919">the</span>
  <span m="520039">graph</span> <span m="520400">in</span> <span m="520610">some</span>
  <span m="520880">arbitrary</span> <span m="521419">way,</span> <span m="522020">you</span>
  <span m="522140">have</span> <span m="522679">at</span> <span m="522860">most</span>
  <span m="523429">n</span> <span m="523610">to</span> <span m="523730">the</span>
  <span m="523820">4</span> <span m="524090">crossings,</span> <span m="524570">because</span>
  <span m="524840">a</span> <span m="524900">crossing</span> <span m="525410">involves</span>
  <span m="526790">four</span> <span m="527000">points.</span> <span m="529320">So</span>
  <span m="529560">when</span> <span m="529680">you</span> <span m="529740">have</span>
  <span m="529890">a</span> <span m="529920">quadratic</span> <span m="530340">number</span>
  <span m="530580">of</span> <span m="530700">edges,</span> <span m="531090">you</span>
  <span m="531210">must</span> <span m="531420">get</span> <span m="532080">basically</span>
  <span m="532500">the</span> <span m="532590">maximum</span> <span m="533010">number</span>
  <span m="533310">of</span> <span m="533400">crossings.</span> <span m="534780">The</span>
  <span m="534810">leading</span> <span m="535080">constant</span> <span m="535650">term</span>
  <span m="535890">factor</span> <span m="536880">is</span> <span m="537570">an</span>
  <span m="537670">interesting</span> <span m="538170">problem,</span> <span m="538590">which</span>
  <span m="538770">we're</span> <span m="538890">not</span> <span m="539040">going</span>
  <span m="539190">to</span> <span m="539250">get</span> <span m="539400">into.</span></p><p><span
  m="542540">Let's</span> <span m="542720">prove</span> <span m="542990">the</span>
  <span m="543080">crossing</span> <span m="543470">number</span> <span m="543710">inequality.</span>
  <span m="546810">First,</span> <span m="548310">the</span> <span m="549280">base</span>
  <span m="549810">case</span> <span m="550140">of</span> <span m="550200">the</span>
  <span m="550290">crossing</span> <span m="550650">number</span> <span m="550830">inequalities</span>
  <span m="551145">is</span> <span m="551460">when</span> <span m="551700">you</span>
  <span m="552000">can</span> <span m="552180">draw</span> <span m="552370">a</span>
  <span m="552520">graph</span> <span m="552810">with</span> <span m="552930">no</span>
  <span m="553140">crossings.</span> <span m="554065">And those</span> <span m="554390">are</span>
  <span m="554670">planar</span> <span m="555060">graphs.</span></p><p><span m="556420">So</span>
  <span m="556440">for</span> <span m="556620">every</span> <span m="559920">connected</span>
  <span m="560760">planar</span> <span m="561090">graph,</span> <span m="569130">if</span>
  <span m="569330">it</span> <span m="569400">has</span> <span m="569610">at</span>
  <span m="569670">least</span> <span m="569910">one</span> <span m="570150">cycle--</span>
  <span m="570540">and</span> <span m="570750">you'll</span> <span m="570870">see</span>
  <span m="571050">why</span> <span m="571320">in</span> <span m="571440">a</span>
  <span m="571500">second,</span> <span m="571770">why</span> <span m="571950">I</span>
  <span m="572010">say</span> <span m="572160">this--</span> <span m="573000">if</span>
  <span m="575850">with</span> <span m="578040">at</span> <span m="578130">least</span>
  <span m="578580">one</span> <span m="579480">cycle,</span> <span m="581230">so</span>
  <span m="581300">that's</span> <span m="581550">not</span> <span m="581790">a</span>
  <span m="581850">tree,</span> <span m="583380">we</span> <span m="583530">must</span>
  <span m="583830">have</span> <span m="584940">that</span> <span m="585450">3</span>
  <span m="585900">times</span> <span m="586290">the</span> <span m="586380">number</span>
  <span m="586740">of</span> <span m="586830">faces</span> <span m="588150">is</span>
  <span m="588800">at</span> <span m="588930">most</span> <span m="589620">2</span>
  <span m="590160">times</span> <span m="591390">the</span> <span m="591480">number</span>
  <span m="591780">of</span> <span m="591900">edges.</span> <span m="593380">So</span>
  <span m="593520">here,</span> <span m="593730">we're</span> <span m="593880">going</span>
  <span m="593980">to</span> <span m="594120">use</span> <span m="595020">the</span>
  <span m="595170">key</span> <span m="595470">tool</span> <span m="595770">being</span>
  <span m="596190">Euler's</span> <span m="596640">formula,</span> <span m="600441">which</span>
  <span m="600930">we</span> <span m="601280">all</span> <span m="601380">know</span>
  <span m="601770">as</span> <span m="602190">the</span> <span m="602280">number</span>
  <span m="602610">of</span> <span m="603210">vertices</span> <span m="603750">minus
  the</span> <span m="604140">number</span> <span m="604500">of</span> <span m="604950">edges</span>
  <span m="605310">plus</span> <span m="605610">the</span> <span m="605670">number</span>
  <span m="605910">of</span> <span m="605970">faces</span> <span m="606900">equals</span>
  <span m="607290">to</span> <span m="607740">2.</span> <span m="609080">We're</span>
  <span m="609370">here</span> <span m="609610">for</span> <span m="609760">face,</span>
  <span m="610260">because I</span> <span m="610510">draw</span> <span m="610945">a</span>
  <span m="611380">planar</span> <span m="611680">graph,</span> <span m="612470">and</span>
  <span m="615970">so</span> <span m="616150">I</span> <span m="616240">count</span>
  <span m="616990">the</span> <span m="617050">faces.</span> <span m="618040">Here</span>
  <span m="618310">there</span> <span m="618450">are</span> <span m="618490">two</span>
  <span m="618700">faces,</span> <span m="619140">outer</span> <span m="619390">face,</span>
  <span m="619810">inner</span> <span m="619990">face,</span> <span m="620840">count</span>
  <span m="621160">edges</span> <span m="621520">and</span> <span m="621610">vertices,</span>
  <span m="622360">so</span> <span m="622500">you</span> <span m="622600">have</span>
  <span m="622870">Euler's</span> <span m="623230">formula</span> <span m="623700">up</span>
  <span m="623850">there.</span></p><p><span m="625380">And</span> <span m="626460">plug
  in</span> <span m="626880">Euler's</span> <span m="627220">formula</span> <span
  m="627580">for</span> <span m="627800">a</span> <span m="627910">planar</span> <span
  m="628150">graph</span> <span m="628390">with</span> <span m="628480">at least</span>
  <span m="628690">one</span> <span m="628930">cycle,</span> <span m="630460">so</span>
  <span m="630620">we</span> <span m="630850">can</span> <span m="631240">obtain</span>
  <span m="631990">this</span> <span m="632200">consequence</span> <span m="632740">over</span>
  <span m="632950">here,</span> <span m="633460">because</span> <span m="635680">every</span>
  <span m="635920">face</span> <span m="638700">is</span> <span m="639120">adjacent</span>
  <span m="641040">to</span> <span m="641490">at</span> <span m="641580">least</span>
  <span m="642030">three</span> <span m="642420">edges.</span> <span m="645330">If</span>
  <span m="645790">you</span> <span m="646380">go</span> <span m="646560">around</span>
  <span m="646800">the</span> <span m="646890">face,</span> <span m="647160">you</span>
  <span m="647280">see</span> <span m="647510">these</span> <span m="647690">three</span>
  <span m="647880">edges,</span> <span m="648590">and</span> <span m="648840">every</span>
  <span m="649110">edge</span> <span m="649590">is</span> <span m="649800">counted</span>
  <span m="650250">exactly</span> <span m="650730">twice,</span> <span m="656350">is</span>
  <span m="657610">adjacent</span> <span m="659200">to</span> <span m="659770">exactly</span>
  <span m="660310">two</span> <span m="661030">faces.</span> <span m="662320">So</span>
  <span m="662470">you</span> <span m="662560">do</span> <span m="662710">the</span>
  <span m="662770">double</span> <span m="663010">counting,</span> <span m="663400">you</span>
  <span m="663490">get</span> <span m="663640">that</span> <span m="663790">inequality</span>
  <span m="664510">up</span> <span m="664810">there.</span></p><p><span m="667920">So</span>
  <span m="669990">plugging</span> <span m="670440">these</span> <span m="670680">two</span>
  <span m="671100">into</span> <span m="671370">Euler</span> <span m="674620">gets</span>
  <span m="674890">you</span> <span m="675520">that</span> <span m="675670">inequality</span>
  <span m="676140">up</span> <span m="676270">there.</span> <span m="683730">Plugging</span>
  <span m="684050">these</span> <span m="684230">two</span> <span m="684440">into</span>
  <span m="684680">Euler,</span> <span m="685280">we</span> <span m="685430">get</span>
  <span m="689840">that the</span> <span m="690320">number</span> <span m="690680">of</span>
  <span m="690830">edges</span> <span m="691290">is</span> <span m="691480">almost</span>
  <span m="692180">3</span> <span m="692600">times</span> <span m="692990">the</span>
  <span m="693050">number</span> <span m="693290">of</span> <span m="693350">vertices</span>
  <span m="693950">minus</span> <span m="694370">6.</span> <span m="701740">So</span>
  <span m="701980">for</span> <span m="702130">this</span> <span m="702340">leaves</span>
  <span m="702580">that</span> <span m="702730">inequality,</span> <span m="703120">but</span>
  <span m="703240">plug</span> <span m="703430">it</span> <span m="703540">into</span>
  <span m="703750">Euler,</span> <span m="706240">plug in</span> <span m="706700">this</span>
  <span m="706930">into</span> <span m="707140">Euler,</span> <span m="707380">you</span>
  <span m="707500">get</span> <span m="707920">this.</span> <span m="708760">So</span>
  <span m="710620">we</span> <span m="710830">have</span> <span m="711110">that the</span>
  <span m="711340">number</span> <span m="711640">of</span> <span m="711760">edges</span>
  <span m="712300">is</span> <span m="712450">at</span> <span m="712520">most</span>
  <span m="712840">3</span> <span m="713200">times</span> <span m="713590">the</span>
  <span m="713680">number</span> <span m="713920">of</span> <span m="713980">vertices</span>
  <span m="714850">for</span> <span m="715060">every</span> <span m="715570">graph</span>
  <span m="716120">G.</span></p><p><span m="717670">So</span> <span m="718060">here,</span>
  <span m="718420">we</span> <span m="718570">require</span> <span m="719110">that</span>
  <span m="719320">the</span> <span m="719440">graph</span> <span m="719800">is</span>
  <span m="720640">planar</span> <span m="722230">and</span> <span m="722410">has</span>
  <span m="722590">at</span> <span m="722650">least</span> <span m="722830">one</span>
  <span m="723010">cycle,</span> <span m="723730">but</span> <span m="724030">even</span>
  <span m="724300">if</span> <span m="724420">we</span> <span m="724540">drop</span>
  <span m="725230">the</span> <span m="726940">condition</span> <span m="727330">that
  it has</span> <span m="727630">at</span> <span m="727690">least</span> <span m="727930">one</span>
  <span m="728110">cycle</span> <span m="728500">but</span> <span m="728620">just</span>
  <span m="728830">require</span> <span m="729160">that</span> <span m="729340">it's</span>
  <span m="729490">planar,</span> <span m="730690">every</span> <span m="732580">planar</span>
  <span m="732940">graph</span> <span m="733270">G</span> <span m="735760">satisfies</span>
  <span m="736630">this</span> <span m="736840">inequality</span> <span m="737650">over</span>
  <span m="737860">here.</span> <span m="738680">So</span> <span m="738700">in</span>
  <span m="738820">other</span> <span m="738940">words,</span> <span m="739470">you</span>
  <span m="739710">might</span> <span m="739900">have</span> <span m="740020">heard</span>
  <span m="740170">before,</span> <span m="740530">in a</span> <span m="740620">planar</span>
  <span m="740920">graph,</span> <span m="741430">the</span> <span m="741640">average</span>
  <span m="742090">degree</span> <span m="742950">of</span> <span m="743080">a</span>
  <span m="743140">vertex</span> <span m="744100">is</span> <span m="744280">almost</span>
  <span m="744710">6.</span> <span m="748460">So</span> <span m="748620">in</span>
  <span m="748710">particular,</span> <span m="751600">the</span> <span m="751730">crossing</span>
  <span m="752150">number</span> <span m="753650">of</span> <span m="753770">a</span>
  <span m="753800">graph</span> <span m="754130">G</span> <span m="754790">is</span>
  <span m="756260">positive</span> <span m="758060">if</span> <span m="759110">the</span>
  <span m="759230">number</span> <span m="759620">of</span> <span m="759740">edges</span>
  <span m="760430">exceeds</span> <span m="760940">3</span> <span m="761300">times</span>
  <span m="761690">the</span> <span m="761780">number</span> <span m="762050">of</span>
  <span m="762110">vertices.</span> <span m="764915">It's</span> <span m="765370">not</span>
  <span m="765580">planar,</span> <span m="765910">so</span> <span m="766060">it has</span>
  <span m="766300">at</span> <span m="766360">least</span> <span m="766600">one</span>
  <span m="766810">crossing</span> <span m="767360">every</span> <span m="767480">drawing.</span></p><p><span
  m="769300">And</span> <span m="769870">by</span> <span m="770270">deleting</span>
  <span m="770790">an</span> <span m="771040">edge</span> <span m="777380">from</span>
  <span m="778190">each</span> <span m="779330">crossing,</span> <span m="784730">we</span>
  <span m="784940">get</span> <span m="785180">a</span> <span m="785240">planar</span>
  <span m="785570">graph.</span> <span m="791360">You</span> <span m="791860">draw</span>
  <span m="792100">the</span> <span m="792190">graph.</span> <span m="793090">You</span>
  <span m="793210">have</span> <span m="793330">some</span> <span m="793480">crossings.</span></p><p><span
  m="794040">You</span> <span m="794380">get</span> <span m="794620">rid</span> <span
  m="794830">of</span> <span m="794920">an</span> <span m="795020">edge</span> <span
  m="795730">associated</span> <span m="796000">with</span> <span m="796270">each</span>
  <span m="796480">drawing.</span> <span m="797230">Then</span> <span m="797350">you</span>
  <span m="797440">get</span> <span m="797620">a</span> <span m="797650">planar</span>
  <span m="797950">graph.</span> <span m="799450">If you</span> <span m="799690">look</span>
  <span m="799990">at</span> <span m="800260">this</span> <span m="800500">inequality</span>
  <span m="801400">and</span> <span m="801520">you</span> <span m="801610">account</span>
  <span m="801880">for</span> <span m="802090">the</span> <span m="802180">number</span>
  <span m="802630">of</span> <span m="802900">edges</span> <span m="803260">that</span>
  <span m="803380">you</span> <span m="803560">deleted,</span> <span m="804460">we</span>
  <span m="806580">obtain</span> <span m="807180">then</span> <span m="807480">the</span>
  <span m="807570">inequality</span> <span m="808230">that</span> <span m="808390">the</span>
  <span m="808470">number</span> <span m="808740">of</span> <span m="808860">edges</span>
  <span m="809460">minus</span> <span m="809870">the</span> <span m="809940">number</span>
  <span m="810300">of</span> <span m="810390">crossings</span> <span m="811470">is</span>
  <span m="812070">at</span> <span m="812190">least</span> <span m="812790">3</span>
  <span m="813180">times</span> <span m="813780">the</span> <span m="813870">number</span>
  <span m="814230">of</span> <span m="814440">vertices.</span> <span m="823130">So</span>
  <span m="828180">we</span> <span m="828330">obtain</span> <span m="828880">the</span>
  <span m="829020">inequality</span> <span m="829950">that</span> <span m="830280">the</span>
  <span m="830550">lower</span> <span m="830820">bounds</span> <span m="831560">in</span>
  <span m="831710">number</span> <span m="832110">of</span> <span m="832320">crossings</span>
  <span m="833350">as</span> <span m="833940">the</span> <span m="834050">number</span>
  <span m="834330">of</span> <span m="834450">edges</span> <span m="836640">minus</span>
  <span m="837210">3</span> <span m="837480">times</span> <span m="838170">the</span>
  <span m="838290">number</span> <span m="838800">of</span> <span m="839130">vertices,</span>
  <span m="840450">this</span> <span m="840690">one.</span></p><p><span m="846820">So</span>
  <span m="846920">that's</span> <span m="847100">some</span> <span m="847370">lower</span>
  <span m="847610">bound</span> <span m="848090">on</span> <span m="848300">the</span>
  <span m="848510">crossing</span> <span m="848960">number.</span> <span m="850490">It's</span>
  <span m="850610">not</span> <span m="850790">quite</span> <span m="851050">the</span>
  <span m="851090">bound that</span> <span m="851420">we</span> <span m="851570">have</span>
  <span m="851780">over</span> <span m="851990">there.</span> <span m="852650">And</span>
  <span m="852770">in</span> <span m="852830">fact,</span> <span m="853320">if</span>
  <span m="853340">you</span> <span m="853460">take</span> <span m="853670">a</span>
  <span m="853730">graph</span> <span m="854060">with</span> <span m="854210">a</span>
  <span m="854240">quadratic</span> <span m="854720">number</span> <span m="854990">of</span>
  <span m="855110">edges,</span> <span m="855860">this</span> <span m="856070">bound</span>
  <span m="856370">here</span> <span m="856610">only</span> <span m="856850">gives</span>
  <span m="857120">you</span> <span m="857840">quadratic</span> <span m="858320">lower</span>
  <span m="858530">bound</span> <span m="858800">on</span> <span m="858890">the</span>
  <span m="858950">crossing</span> <span m="859340">number,</span> <span m="860570">some</span>
  <span m="860810">lower</span> <span m="861020">bound.</span> <span m="861480">But</span>
  <span m="861530">it's</span> <span m="861620">not</span> <span m="861820">a great</span>
  <span m="862070">lower</span> <span m="862280">bound.</span></p><p><span m="862860">And</span>
  <span m="862970">we</span> <span m="863120">would</span> <span m="863250">like</span>
  <span m="863370">to</span> <span m="863450">do</span> <span m="863600">better.</span>
  <span m="864750">So</span> <span m="864770">here's</span> <span m="865010">a</span>
  <span m="865040">trick</span> <span m="865550">that</span> <span m="867060">is</span>
  <span m="867380">a</span> <span m="867410">very</span> <span m="867620">nice</span>
  <span m="867860">trick,</span> <span m="868710">where</span> <span m="869020">we're</span>
  <span m="869240">going</span> <span m="869510">to</span> <span m="869600">use</span>
  <span m="870800">this</span> <span m="871160">inequality</span> <span m="872120">to</span>
  <span m="872450">upgrade</span> <span m="872765">it</span> <span m="873410">to</span>
  <span m="873590">a</span> <span m="873650">much</span> <span m="873920">better</span>
  <span m="874190">inequality,</span> <span m="875580">bootstrap</span> <span m="876090">it</span>
  <span m="876170">to</span> <span m="876320">a</span> <span m="876380">much</span>
  <span m="876620">tighter</span> <span m="876950">inequality.</span> <span m="878430">So</span>
  <span m="878570">this</span> <span m="878990">involves</span> <span m="879400">the</span>
  <span m="879470">use</span> <span m="879710">of</span> <span m="879800">the</span>
  <span m="879890">probabilistic</span> <span m="880580">method.</span></p><p><span
  m="883870">Let</span> <span m="883960">me</span> <span m="884110">denote</span>
  <span m="884450">by</span> <span m="884750">p</span> <span m="885320">some</span>
  <span m="886520">number</span> <span m="886820">between</span> <span m="887210">0</span>
  <span m="887540">and</span> <span m="887630">1,</span> <span m="888410">to</span>
  <span m="888560">be</span> <span m="888770">decided</span> <span m="889400">later.</span>
  <span m="894080">And</span> <span m="894890">starting</span> <span m="895370">with</span>
  <span m="895550">a</span> <span m="895580">graph</span> <span m="895910">G,</span>
  <span m="897080">let's</span> <span m="897320">let</span> <span m="898940">G</span>
  <span m="899480">prime,</span> <span m="901896">with</span> <span m="903930">vertices</span>
  <span m="904410">and</span> <span m="904590">edges</span> <span m="904800">being</span>
  <span m="905010">V</span> <span m="905190">prime</span> <span m="905580">and</span>
  <span m="905700">E</span> <span m="905820">prime,</span> <span m="906600">be</span>
  <span m="907800">obtained</span> <span m="911770">from</span> <span m="912220">G</span>
  <span m="913720">by</span> <span m="914340">randomly</span> <span m="915160">deleting</span>
  <span m="916030">some</span> <span m="916300">of</span> <span m="916390">the</span>
  <span m="917350">vertices,</span> <span m="918415">or</span> <span m="918910">rather</span>
  <span m="919180">randomly</span> <span m="919690">keeping</span> <span m="921940">each</span>
  <span m="922180">vertex</span> <span m="924460">with</span> <span m="924850">probability</span>
  <span m="925630">p,</span> <span m="929600">independently</span> <span m="932760">for</span>
  <span m="933000">each</span> <span m="933450">of</span> <span m="933930">these</span>
  <span m="934320">vertices.</span> <span m="935931">So</span> <span m="936310">you</span>
  <span m="936410">have</span> <span m="936530">some</span> <span m="936710">graph</span>
  <span m="936980">G.</span></p><p><span m="937940">I</span> <span m="938960">keep</span>
  <span m="939650">each</span> <span m="939830">vertex</span> <span m="940250">with</span>
  <span m="940400">probability</span> <span m="941000">p.</span> <span m="941330">And</span>
  <span m="941480">I</span> <span m="941570">delete</span> <span m="941990">the</span>
  <span m="942110">remaining</span> <span m="942620">vertices.</span> <span m="943640">And</span>
  <span m="943790">I</span> <span m="943850">get</span> <span m="944150">a</span>
  <span m="944270">smaller</span> <span m="944690">graph.</span> <span m="945800">I</span>
  <span m="945860">get</span> <span m="946070">some</span> <span m="946460">induced</span>
  <span m="946940">subgraph.</span></p><p><span m="949230">And</span> <span m="949480">I</span>
  <span m="949610">would</span> <span m="949730">like</span> <span m="949880">to</span>
  <span m="949970">know</span> <span m="951020">what</span> <span m="951170">can</span>
  <span m="951320">we</span> <span m="951440">say</span> <span m="951710">about</span>
  <span m="952100">the</span> <span m="952190">crossing</span> <span m="952580">number</span>
  <span m="952940">of</span> <span m="953240">the</span> <span m="953960">smaller</span>
  <span m="954380">graph</span> <span m="955070">in</span> <span m="955190">comparison</span>
  <span m="955910">to</span> <span m="956060">the</span> <span m="956150">crossing</span>
  <span m="956540">number</span> <span m="956870">of</span> <span m="957350">the</span>
  <span m="957500">original</span> <span m="957950">graph?</span> <span m="960240">For</span>
  <span m="960360">the</span> <span m="960450">smaller</span> <span m="960900">graph,</span>
  <span m="961440">because</span> <span m="961740">it's</span> <span m="961890">still</span>
  <span m="962400">a</span> <span m="962520">planar</span> <span m="963060">graph</span>
  <span m="963860">so</span> <span m="964020">G</span> <span m="964320">prime--</span>
  <span m="965770">so</span> <span m="966220">it's</span> <span m="966940">still a</span>
  <span m="967200">graph.</span> <span m="967530">It's</span> <span m="967650">not</span>
  <span m="968010">a</span> <span m="968250">planar graph,</span> <span m="968490">but</span>
  <span m="968610">it's</span> <span m="968700">still a</span> <span m="968940">graph,
  so</span> <span m="969420">G</span> <span m="969720">prime</span> <span m="971400">still</span>
  <span m="972300">satisfies</span> <span m="973140">this</span> <span m="973350">inequality</span>
  <span m="974040">up</span> <span m="974190">here.</span></p><p><span m="977600">So</span>
  <span m="977820">G</span> <span m="978030">prime</span> <span m="978380">still</span>
  <span m="978630">satisfies</span> <span m="979740">that</span> <span m="980445">the</span>
  <span m="980820">number</span> <span m="981210">of</span> <span m="981330">crossings</span>
  <span m="981950">in</span> <span m="982070">every</span> <span m="982320">drawing</span>
  <span m="982680">of</span> <span m="982770">G</span> <span m="982950">prime</span>
  <span m="983340">is</span> <span m="983550">at</span> <span m="983610">least</span>
  <span m="984270">the</span> <span m="984360">number</span> <span m="984750">of</span>
  <span m="985260">edges</span> <span m="985560">of</span> <span m="985680">G</span>
  <span m="985830">prime</span> <span m="986400">minus</span> <span m="987090">3</span>
  <span m="987390">times</span> <span m="987990">the</span> <span m="988080">number</span>
  <span m="988500">of</span> <span m="989250">vertices</span> <span m="989850">of</span>
  <span m="990000">G</span> <span m="990220">prime.</span> <span m="993560">But</span>
  <span m="994340">note</span> <span m="994610">that</span> <span m="994850">G</span>
  <span m="995150">prime</span> <span m="995840">is</span> <span m="996050">a</span>
  <span m="996170">random</span> <span m="996860">graph.</span> <span m="998390">G</span>
  <span m="998660">was</span> <span m="999170">fixed,</span> <span m="999590">given.</span>
  <span m="1000400">G</span> <span m="1000640">prime</span> <span m="1001090">is</span>
  <span m="1001210">a</span> <span m="1001270">random</span> <span m="1001840">graph.</span></p><p><span
  m="1004100">So</span> <span m="1004220">let's</span> <span m="1004550">evaluate</span>
  <span m="1005260">the</span> <span m="1005410">expectation</span> <span m="1006520">of</span>
  <span m="1007630">both</span> <span m="1008020">quantities,</span> <span m="1008800">left-hand</span>
  <span m="1009220">side</span> <span m="1009490">and</span> <span m="1009610">right-hand</span>
  <span m="1009970">side.</span> <span m="1013730">If</span> <span m="1013850">this</span>
  <span m="1014060">inequality</span> <span m="1014540">is</span> <span m="1014660">true</span>
  <span m="1014900">for</span> <span m="1015080">every</span> <span m="1015350">G</span>
  <span m="1015530">prime,</span> <span m="1016280">the</span> <span m="1016370">same</span>
  <span m="1016640">inequality</span> <span m="1017150">must</span> <span m="1017360">be</span>
  <span m="1017480">true</span> <span m="1018110">in</span> <span m="1018530">expectation.</span>
  <span m="1029369">Now</span> <span m="1030480">what</span> <span m="1030660">do</span>
  <span m="1030720">we</span> <span m="1030839">know</span> <span m="1031230">about</span>
  <span m="1031450">all</span> <span m="1031890">the</span> <span m="1032040">expectations</span>
  <span m="1032940">of</span> <span m="1033180">each</span> <span m="1033510">of</span>
  <span m="1034260">these</span> <span m="1034470">quantities?</span></p><p><span
  m="1037230">The</span> <span m="1037319">number</span> <span m="1037680">of</span>
  <span m="1038160">vertices</span> <span m="1038819">in</span> <span m="1038970">expectation--</span>
  <span m="1039940">that's</span> <span m="1040140">pretty</span> <span m="1040410">easy.</span>
  <span m="1041260">So</span> <span m="1041369">this</span> <span m="1041579">one</span>
  <span m="1041790">here</span> <span m="1042960">is</span> <span m="1044069">p</span>
  <span m="1044819">times</span> <span m="1045420">the</span> <span m="1045900">original</span>
  <span m="1046319">number</span> <span m="1046650">of</span> <span m="1046710">vertices.</span>
  <span m="1048780">The</span> <span m="1048870">number</span> <span m="1049140">of</span>
  <span m="1049260">edges</span> <span m="1049920">is</span> <span m="1050100">also</span>
  <span m="1050310">pretty</span> <span m="1050520">easy.</span> <span m="1050970">Each</span>
  <span m="1051240">edge</span> <span m="1051450">is</span> <span m="1051600">kept</span>
  <span m="1051960">if</span> <span m="1052080">both</span> <span m="1052400">endpoints</span>
  <span m="1052950">are</span> <span m="1053070">kept.</span> <span m="1054150">So</span>
  <span m="1054660">this</span> <span m="1055500">expectation</span> <span m="1056190">on</span>
  <span m="1056280">the</span> <span m="1056340">number</span> <span m="1056700">of</span>
  <span m="1057300">edges</span> <span m="1057600">remaining</span> <span m="1058620">is</span>
  <span m="1058770">also</span> <span m="1059250">pretty</span> <span m="1059550">easy</span>
  <span m="1059970">to</span> <span m="1060360">determine.</span></p><p><span m="1063640">The</span>
  <span m="1064540">crossing</span> <span m="1065170">number</span> <span m="1066460">of</span>
  <span m="1066730">the</span> <span m="1067270">new</span> <span m="1067420">graph--</span>
  <span m="1069070">that</span> <span m="1069410">I</span> <span m="1069530">have</span>
  <span m="1069700">to</span> <span m="1069790">be a</span> <span m="1069940">little</span>
  <span m="1070300">bit</span> <span m="1070420">more</span> <span m="1070600">careful</span>
  <span m="1071080">of,</span> <span m="1071830">because</span> <span m="1072310">when</span>
  <span m="1072550">you</span> <span m="1072670">look</span> <span m="1072910">at</span>
  <span m="1073060">the</span> <span m="1073180">smaller</span> <span m="1073750">graph,</span>
  <span m="1074380">maybe</span> <span m="1074710">there's</span> <span m="1074890">a</span>
  <span m="1074980">different</span> <span m="1075370">way</span> <span m="1075580">to</span>
  <span m="1075700">draw</span> <span m="1076030">it</span> <span m="1076780">that's</span>
  <span m="1077650">not</span> <span m="1078040">just</span> <span m="1078880">deleting</span>
  <span m="1079330">the</span> <span m="1079450">sum</span> <span m="1079690">of</span>
  <span m="1079750">the</span> <span m="1079840">vertices</span> <span m="1080320">from</span>
  <span m="1080530">the</span> <span m="1080830">original</span> <span m="1081250">graph.</span>
  <span m="1082070">So</span> <span m="1082510">even</span> <span m="1082720">though</span>
  <span m="1082810">the</span> <span m="1082930">original</span> <span m="1083290">graph</span>
  <span m="1083560">might</span> <span m="1083740">have</span> <span m="1083920">a</span>
  <span m="1083950">lot</span> <span m="1084110">of</span> <span m="1084190">crossings,</span>
  <span m="1084910">when</span> <span m="1085060">you</span> <span m="1085330">go</span>
  <span m="1085480">to</span> <span m="1085600">a</span> <span m="1085630">subgraph,</span>
  <span m="1086170">maybe</span> <span m="1086410">there's</span> <span m="1086560">a</span>
  <span m="1086620">better</span> <span m="1086830">way</span> <span m="1086980">to</span>
  <span m="1087070">draw</span> <span m="1087270">it.</span> <span m="1089100">But</span>
  <span m="1089180">we</span> <span m="1089300">just</span> <span m="1089510">need</span>
  <span m="1089660">an</span> <span m="1089750">inequality</span> <span m="1090410">in</span>
  <span m="1090530">the</span> <span m="1090590">right</span> <span m="1090800">direction.</span>
  <span m="1091320">So</span> <span m="1092030">we</span> <span m="1092200">are</span>
  <span m="1092270">still</span> <span m="1092540">OK.</span></p><p><span m="1093110">And</span>
  <span m="1093220">I</span> <span m="1093320">claim</span> <span m="1093800">that</span>
  <span m="1093950">the</span> <span m="1094070">crossing</span> <span m="1094610">number</span>
  <span m="1094970">of</span> <span m="1095480">G prime</span> <span m="1096170">is</span>
  <span m="1096410">in</span> <span m="1096560">expectation</span> <span m="1097720">at</span>
  <span m="1097850">most</span> <span m="1098660">p</span> <span m="1098990">to</span>
  <span m="1099140">be</span> <span m="1099260">4th</span> <span m="1099740">times</span>
  <span m="1100340">the</span> <span m="1100430">crossing</span> <span m="1100880">number</span>
  <span m="1101210">of G.</span> <span m="1101330">Because</span> <span m="1102950">if</span>
  <span m="1103070">you</span> <span m="1103190">keep</span> <span m="1103520">the</span>
  <span m="1103640">same</span> <span m="1103970">drawing,</span> <span m="1110170">then</span>
  <span m="1110560">the</span> <span m="1110740">expected</span> <span m="1111340">number</span>
  <span m="1111670">of</span> <span m="1111730">crossings</span> <span m="1112360">that</span>
  <span m="1112540">are</span> <span m="1112630">kept--</span> <span m="1114470">each</span>
  <span m="1114680">crossing</span> <span m="1115160">is</span> <span m="1115280">kept</span>
  <span m="1115790">if</span> <span m="1116090">all</span> <span m="1116330">four</span>
  <span m="1116720">of</span> <span m="1116900">its</span> <span m="1117050">end</span>
  <span m="1117220">points</span> <span m="1118850">are</span> <span m="1119110">kept.</span>
  <span m="1120770">So</span> <span m="1121100">each</span> <span m="1121370">crossing</span>
  <span m="1121850">is</span> <span m="1122000">kept</span> <span m="1122270">with</span>
  <span m="1122420">probability</span> <span m="1123050">p</span> <span m="1123260">to</span>
  <span m="1123410">the</span> <span m="1123500">4th.</span></p><p><span m="1124830">So</span>
  <span m="1125490">you</span> <span m="1125580">can</span> <span m="1125730">draw</span>
  <span m="1126030">it</span> <span m="1126570">in</span> <span m="1126720">expectation</span>
  <span m="1127320">with</span> <span m="1127440">this</span> <span m="1127620">many</span>
  <span m="1127830">crossings.</span> <span m="1128850">Maybe</span> <span m="1129150">it's</span>
  <span m="1129270">much</span> <span m="1129480">less.</span> <span m="1129720">Maybe</span>
  <span m="1129960">there's</span> <span m="1130170">a</span> <span m="1130200">better</span>
  <span m="1130410">way</span> <span m="1130530">to</span> <span m="1130620">draw
  it,</span> <span m="1130890">but</span> <span m="1131010">you</span> <span m="1131130">have</span>
  <span m="1131310">an</span> <span m="1131430">inequality</span> <span m="1132000">going</span>
  <span m="1132270">in</span> <span m="1132360">the</span> <span m="1132450">right</span>
  <span m="1132660">direction.</span></p><p><span m="1141500">Looking</span> <span
  m="1141830">at</span> <span m="1142130">that</span> <span m="1142340">inequality</span>
  <span m="1142910">up</span> <span m="1143030">there</span> <span m="1143510">in</span>
  <span m="1144050">yellow,</span> <span m="1145130">we</span> <span m="1145310">find</span>
  <span m="1145760">that</span> <span m="1146590">the</span> <span m="1146780">crossing</span>
  <span m="1147260">number</span> <span m="1147620">of</span> <span m="1147890">G</span>
  <span m="1148710">is</span> <span m="1149120">at</span> <span m="1149240">least</span>
  <span m="1150060">p</span> <span m="1150480">to</span> <span m="1150600">the</span>
  <span m="1150740">minus</span> <span m="1151160">2</span> <span m="1152850">E</span>
  <span m="1153470">minus</span> <span m="1155830">3p</span> <span m="1156470">to</span>
  <span m="1156620">the</span> <span m="1156740">minus</span> <span m="1157630">3.</span>
  <span m="1161090">And</span> <span m="1161270">this</span> <span m="1161450">is</span>
  <span m="1161570">true</span> <span m="1161870">for</span> <span m="1162230">every</span>
  <span m="1162530">value</span> <span m="1163130">of</span> <span m="1163400">p</span>
  <span m="1163850">between</span> <span m="1164330">0</span> <span m="1164690">and</span>
  <span m="1164810">1.</span> <span m="1165690">So</span> <span m="1165740">now</span>
  <span m="1165980">you</span> <span m="1166130">pick</span> <span m="1166580">a</span>
  <span m="1166640">value</span> <span m="1167090">of</span> <span m="1167180">p</span>
  <span m="1167480">that</span> <span m="1167660">works</span> <span m="1168440">most</span>
  <span m="1169040">in</span> <span m="1169280">your</span> <span m="1169490">favor.</span></p><p><span
  m="1170540">And</span> <span m="1171350">it</span> <span m="1171410">turns</span>
  <span m="1171710">out</span> <span m="1172970">you</span> <span m="1173060">should</span>
  <span m="1173210">do</span> <span m="1173330">this</span> <span m="1173690">by</span>
  <span m="1174860">setting</span> <span m="1176030">these</span> <span m="1176240">two</span>
  <span m="1176510">equalities</span> <span m="1177020">to</span> <span m="1177110">be</span>
  <span m="1177710">roughly</span> <span m="1178190">equal</span> <span m="1178520">to</span>
  <span m="1178670">each</span> <span m="1178880">other.</span> <span m="1183050">So</span>
  <span m="1183570">setting</span> <span m="1184530">p</span> <span m="1186030">between</span>
  <span m="1186420">0</span> <span m="1186750">and</span> <span m="1186840">1</span>
  <span m="1187590">so</span> <span m="1187830">that</span> <span m="1191710">4</span>
  <span m="1192160">times</span> <span m="1194820">the--</span> <span m="1197120">basically,</span>
  <span m="1197420">set</span> <span m="1197660">these</span> <span m="1197840">two</span>
  <span m="1198050">terms</span> <span m="1198380">to</span> <span m="1198470">be</span>
  <span m="1198590">roughly</span> <span m="1199010">equal</span> <span m="1199340">to</span>
  <span m="1199460">each</span> <span m="1199700">other.</span> <span m="1203890">And</span>
  <span m="1204420">then</span> <span m="1204690">we</span> <span m="1204900">get</span>
  <span m="1207580">that</span> <span m="1207910">this</span> <span m="1208150">quantity</span>
  <span m="1208570">here</span> <span m="1209320">is</span> <span m="1210160">at</span>
  <span m="1210250">least</span> <span m="1212080">the</span> <span m="1212830">claimed</span>
  <span m="1213250">quantity,</span> <span m="1213910">which</span> <span m="1214150">is</span>
  <span m="1215810">E</span> <span m="1216310">cubed</span> <span m="1217210">over</span>
  <span m="1217930">V</span> <span m="1218290">squared</span> <span m="1219110">up</span>
  <span m="1219270">to</span> <span m="1219370">some</span> <span m="1219610">constant</span>
  <span m="1220060">factor,</span> <span m="1220450">which</span> <span m="1221320">I</span>
  <span m="1221410">don't</span> <span m="1221560">really</span> <span m="1221770">care</span>
  <span m="1221980">about.</span></p><p><span m="1224140">In</span> <span m="1224260">order</span>
  <span m="1224600">to</span> <span m="1224750">set</span> <span m="1225270">p,</span>
  <span m="1225790">I</span> <span m="1225880">have</span> <span m="1225970">to</span>
  <span m="1226090">be</span> <span m="1226270">a</span> <span m="1226330">little</span>
  <span m="1226510">bit</span> <span m="1226630">careful</span> <span m="1227020">that</span>
  <span m="1227140">p is</span> <span m="1227440">between</span> <span m="1227740">0</span>
  <span m="1228040">and</span> <span m="1228130">1.</span> <span m="1228560">If</span>
  <span m="1228580">you</span> <span m="1228670">set</span> <span m="1228990">p</span>
  <span m="1229110">to be</span> <span m="1229240">1.2,</span> <span m="1229810">this</span>
  <span m="1229960">whole</span> <span m="1230110">argument</span> <span m="1230500">doesn't</span>
  <span m="1230710">make</span> <span m="1230860">any</span> <span m="1231010">sense.</span>
  <span m="1233060">So</span> <span m="1233290">this</span> <span m="1233440">is</span>
  <span m="1233560">OK.</span></p><p><span m="1236820">So</span> <span m="1237030">we
  know</span> <span m="1237290">p is</span> <span m="1237630">at</span> <span m="1237720">most</span>
  <span m="1237930">one</span> <span m="1238530">as</span> <span m="1238710">long</span>
  <span m="1239010">as</span> <span m="1240240">E</span> <span m="1240600">is</span>
  <span m="1241850">at</span> <span m="1242010">most</span> <span m="1243470">4p.</span>
  <span m="1246260">I</span> <span m="1246320">mean,</span> <span m="1246440">the</span>
  <span m="1246530">4</span> <span m="1246800">here</span> <span m="1247010">is</span>
  <span m="1247100">not</span> <span m="1247340">optimal,</span> <span m="1247760">but</span>
  <span m="1248260">if</span> <span m="1248450">4</span> <span m="1248920">were</span>
  <span m="1249140">2,</span> <span m="1249470">then</span> <span m="1249710">it's</span>
  <span m="1249830">not</span> <span m="1250040">true.</span> <span m="1250550">So</span>
  <span m="1250700">if</span> <span m="1252760">E is</span> <span m="1253250">2V,</span>
  <span m="1253810">you</span> <span m="1253910">can</span> <span m="1254060">have</span>
  <span m="1254210">a</span> <span m="1254270">planar</span> <span m="1254630">graph,</span>
  <span m="1254930">so</span> <span m="1255080">you</span> <span m="1255170">shouldn't</span>
  <span m="1255470">have</span> <span m="1255650">a</span> <span m="1255710">lower</span>
  <span m="1255950">bound</span> <span m="1256220">on</span> <span m="1256310">the</span>
  <span m="1256370">crossing</span> <span m="1256720">number.</span></p><p><span m="1259550">So</span>
  <span m="1259670">this</span> <span m="1259850">is</span> <span m="1259940">the</span>
  <span m="1260030">proof</span> <span m="1260360">of</span> <span m="1260480">the</span>
  <span m="1260600">crossing</span> <span m="1261080">number</span> <span m="1261350">inequality.</span>
  <span m="1262620">As I</span> <span m="1262870">said,</span> <span m="1263060">if</span>
  <span m="1263180">you</span> <span m="1263270">have</span> <span m="1263540">lots</span>
  <span m="1263870">of</span> <span m="1264020">edges,</span> <span m="1264770">then</span>
  <span m="1265010">you</span> <span m="1265100">must</span> <span m="1265340">have</span>
  <span m="1265640">lots</span> <span m="1266090">of</span> <span m="1266360">crossings.</span>
  <span m="1268960">Any</span> <span m="1269120">questions?</span></p><p><span m="1273250">So</span>
  <span m="1273370">let's</span> <span m="1273550">use</span> <span m="1273740">the</span>
  <span m="1273820">crossing</span> <span m="1274180">number</span> <span m="1274430">inequality</span>
  <span m="1275200">to</span> <span m="1275450">prove</span> <span m="1276400">a</span>
  <span m="1277060">fundamental</span> <span m="1277600">result</span> <span m="1278040">in</span>
  <span m="1278410">incidence</span> <span m="1278920">geometry.</span> <span m="1286820">Incidence</span>
  <span m="1287240">geometry</span> <span m="1287870">is</span> <span m="1288440">this</span>
  <span m="1288650">area</span> <span m="1288950">of</span> <span m="1289130">discrete</span>
  <span m="1289550">math</span> <span m="1290120">that</span> <span m="1290270">concerns</span>
  <span m="1291440">fairly</span> <span m="1292070">basic-sounding</span> <span m="1292880">questions</span>
  <span m="1293510">about</span> <span m="1294560">incidences</span> <span m="1295130">between,</span>
  <span m="1295820">let's</span> <span m="1295970">say,</span> <span m="1296150">points</span>
  <span m="1296600">and</span> <span m="1296690">lines.</span> <span m="1297530">And</span>
  <span m="1297650">here's</span> <span m="1297860">an</span> <span m="1297980">example.</span></p><p><span
  m="1299730">So</span> <span m="1299840">what's</span> <span m="1300110">the</span>
  <span m="1300200">maximum</span> <span m="1304310">number</span> <span m="1304760">of</span>
  <span m="1305270">incidences</span> <span m="1308990">between</span> <span m="1310770">endpoints</span>
  <span m="1312530">and</span> <span m="1313220">end</span> <span m="1313520">lines,</span>
  <span m="1316220">where</span> <span m="1316940">by</span> <span m="1317150">&quot;incidence&quot;</span>
  <span m="1317660">I</span> <span m="1317720">mean</span> <span m="1318230">if</span>
  <span m="1319280">p--</span> <span m="1319580">so</span> <span m="1319760">curly</span>
  <span m="1320060">p--</span> <span m="1320360">is</span> <span m="1320510">a</span>
  <span m="1320570">set</span> <span m="1320780">of</span> <span m="1320870">points,</span>
  <span m="1323150">and</span> <span m="1323360">curly l</span> <span m="1323720">is</span>
  <span m="1324050">a</span> <span m="1324110">set</span> <span m="1324320">of</span>
  <span m="1324440">lines,</span> <span m="1325610">then</span> <span m="1325820">I</span>
  <span m="1325890">write</span> <span m="1326540">I</span> <span m="1326900">of</span>
  <span m="1327110">p</span> <span m="1327560">and</span> <span m="1327998">l</span>
  <span m="1329750">to</span> <span m="1329870">be</span> <span m="1330800">the</span>
  <span m="1331070">number</span> <span m="1331520">of</span> <span m="1332990">pairs,</span>
  <span m="1334100">one point,</span> <span m="1334595">one</span> <span m="1335090">line,</span>
  <span m="1340440">such</span> <span m="1340770">that</span> <span m="1341040">the</span>
  <span m="1341130">point</span> <span m="1341820">lies</span> <span m="1342570">on</span>
  <span m="1342930">the</span> <span m="1343050">line.</span> <span m="1345380">So</span>
  <span m="1345480">I'm</span> <span m="1345630">counting</span> <span m="1346410">incidences</span>
  <span m="1347070">between</span> <span m="1347640">points</span> <span m="1348030">and</span>
  <span m="1348120">lines.</span> <span m="1349440">You</span> <span m="1349530">can</span>
  <span m="1349650">view</span> <span m="1349830">this</span> <span m="1350160">in</span>
  <span m="1350250">many</span> <span m="1350520">ways.</span> <span m="1350910">You</span>
  <span m="1350970">can</span> <span m="1351120">view</span> <span m="1351300">it</span>
  <span m="1351390">as</span> <span m="1351510">a</span> <span m="1351570">bipartite</span>
  <span m="1352110">graph</span> <span m="1352410">between</span> <span m="1352770">points</span>
  <span m="1353160">and</span> <span m="1353250">lines,</span> <span m="1354000">and</span>
  <span m="1354270">we're</span> <span m="1354420">counting</span> <span m="1354750">the</span>
  <span m="1354840">number</span> <span m="1355140">of</span> <span m="1355260">edges</span>
  <span m="1356430">in</span> <span m="1356580">this</span> <span m="1356760">bipartite</span>
  <span m="1357240">graph.</span></p><p><span m="1360000">So</span> <span m="1360170">I
  give</span> <span m="1360260">you</span> <span m="1360380">end</span> <span m="1360560">points,</span>
  <span m="1361100">end</span> <span m="1361250">lines.</span> <span m="1361730">What's</span>
  <span m="1361970">the</span> <span m="1362060">maximum</span> <span m="1362630">number</span>
  <span m="1363020">of</span> <span m="1363500">incidences?</span> <span m="1365350">It's</span>
  <span m="1365480">not</span> <span m="1365750">such</span> <span m="1365930">an</span>
  <span m="1366020">obvious</span> <span m="1366380">question.</span> <span m="1367670">So</span>
  <span m="1367760">let's</span> <span m="1368210">see</span> <span m="1368480">how</span>
  <span m="1368720">we</span> <span m="1368870">can</span> <span m="1370570">approach</span>
  <span m="1370960">this</span> <span m="1371170">question.</span></p><p><span m="1372560">But</span>
  <span m="1372670">first,</span> <span m="1373150">let</span> <span m="1373300">me</span>
  <span m="1373960">give</span> <span m="1374230">you</span> <span m="1376090">some</span>
  <span m="1377110">easy</span> <span m="1377380">bounds.</span> <span m="1378280">So</span>
  <span m="1380590">here's</span> <span m="1380950">a</span> <span m="1381790">trivial</span>
  <span m="1382190">bound--</span> <span m="1387680">so</span> <span m="1387860">here,</span>
  <span m="1388060">I</span> <span m="1388160">want</span> <span m="1388400">to</span>
  <span m="1388520">know</span> <span m="1389120">if</span> <span m="1389300">I</span>
  <span m="1389390">give</span> <span m="1389630">you</span> <span m="1391190">some</span>
  <span m="1391400">number</span> <span m="1391670">of</span> <span m="1391860">points,</span>
  <span m="1392390">some</span> <span m="1392600">number</span> <span m="1392810">of</span>
  <span m="1392930">lines,</span> <span m="1393410">what's</span> <span m="1393680">the</span>
  <span m="1393770">maximum</span> <span m="1394340">number</span> <span m="1394640">of</span>
  <span m="1394730">incidences.</span> <span m="1396250">So a</span> <span m="1396320">trivial</span>
  <span m="1396650">bound</span> <span m="1397610">is</span> <span m="1398960">that</span>
  <span m="1399790">the</span> <span m="1400000">number</span> <span m="1400280">of</span>
  <span m="1400890">incidences</span> <span m="1401580">is</span> <span m="1401790">at</span>
  <span m="1401930">most</span> <span m="1403530">the</span> <span m="1404060">product</span>
  <span m="1405050">between</span> <span m="1406010">the</span> <span m="1406160">number</span>
  <span m="1406520">of</span> <span m="1406580">points</span> <span m="1406970">and</span>
  <span m="1407100">the</span> <span m="1407150">number</span> <span m="1407480">of</span>
  <span m="1407570">lines.</span></p><p><span m="1410120">One</span> <span m="1410220">point,</span>
  <span m="1410460">one</span> <span m="1410580">line,</span> <span m="1411000">at</span>
  <span m="1411090">most</span> <span m="1411300">one</span> <span m="1411510">incidence.</span>
  <span m="1412220">So</span> <span m="1412400">that's</span> <span m="1412590">pretty</span>
  <span m="1412830">trivial.</span> <span m="1414750">We</span> <span m="1414870">can</span>
  <span m="1414960">do</span> <span m="1415080">better.</span></p><p><span m="1416260">So</span>
  <span m="1416430">we</span> <span m="1416520">can</span> <span m="1416670">do</span>
  <span m="1416820">better</span> <span m="1417960">because,</span> <span m="1420180">well,</span>
  <span m="1422750">you</span> <span m="1422840">see,</span> <span m="1424560">let's</span>
  <span m="1424770">use</span> <span m="1425040">this</span> <span m="1425220">following</span>
  <span m="1425670">fact,</span> <span m="1426300">that</span> <span m="1427140">every</span>
  <span m="1429630">line--</span> <span m="1432880">so</span> <span m="1433320">every</span>
  <span m="1434370">pair</span> <span m="1434640">of</span> <span m="1434760">points</span>
  <span m="1437430">determine</span> <span m="1439190">at</span> <span m="1439350">most</span>
  <span m="1439830">one</span> <span m="1440340">line.</span> <span m="1442735">I
  have</span> <span m="1443160">two</span> <span m="1443310">points.</span> <span
  m="1443810">There's at</span> <span m="1444000">most</span> <span m="1444270">one</span>
  <span m="1444480">line</span> <span m="1444720">that</span> <span m="1444840">contains</span>
  <span m="1445770">those</span> <span m="1445980">two</span> <span m="1446100">points.</span></p><p><span
  m="1448780">Using</span> <span m="1449080">this</span> <span m="1449290">fact,</span>
  <span m="1450260">we</span> <span m="1451390">see</span> <span m="1451720">that</span>
  <span m="1452410">the</span> <span m="1453220">number</span> <span m="1453790">of--</span>
  <span m="1455990">so</span> <span m="1456220">let's</span> <span m="1456610">count</span>
  <span m="1458910">the</span> <span m="1459000">number</span> <span m="1459420">of</span>
  <span m="1461820">triples</span> <span m="1463110">involving</span> <span m="1463500">two</span>
  <span m="1463710">points</span> <span m="1464160">and</span> <span m="1464310">one</span>
  <span m="1464550">line</span> <span m="1469130">such</span> <span m="1469460">that</span>
  <span m="1471320">both</span> <span m="1471650">points</span> <span m="1473960">lie</span>
  <span m="1474590">on</span> <span m="1474860">the</span> <span m="1474950">line.</span>
  <span m="1479730">So</span> <span m="1479910">how</span> <span m="1480150">big</span>
  <span m="1480570">can</span> <span m="1480750">this set</span> <span m="1481080">be?</span>
  <span m="1481530">So</span> <span m="1481650">let's</span> <span m="1481830">try</span>
  <span m="1481980">to</span> <span m="1482100">count</span> <span m="1482400">it</span>
  <span m="1482550">in</span> <span m="1482700">two</span> <span m="1482910">different</span>
  <span m="1483210">ways.</span></p><p><span m="1484950">On</span> <span m="1485040">one</span>
  <span m="1485220">hand,</span> <span m="1486510">this</span> <span m="1486840">quantity</span>
  <span m="1487410">is</span> <span m="1487590">at</span> <span m="1487680">most</span>
  <span m="1488900">the</span> <span m="1489120">number</span> <span m="1489450">of</span>
  <span m="1489540">points</span> <span m="1490080">squared,</span> <span m="1491280">because</span>
  <span m="1491730">if</span> <span m="1491850">I</span> <span m="1491940">give</span>
  <span m="1492120">you</span> <span m="1492270">two</span> <span m="1492510">points,</span>
  <span m="1494120">then</span> <span m="1494540">they</span> <span m="1494720">determine</span>
  <span m="1495230">this</span> <span m="1495370">line--</span> <span m="1496700">so</span>
  <span m="1497270">at</span> <span m="1497570">most</span> <span m="1497900">the</span>
  <span m="1498200">number</span> <span m="1498470">of</span> <span m="1498530">points</span>
  <span m="1499040">squared.</span> <span m="1501580">But</span> <span m="1501770">on</span>
  <span m="1501920">the</span> <span m="1502010">other</span> <span m="1502190">hand,</span>
  <span m="1505080">we</span> <span m="1505130">see</span> <span m="1505400">that</span>
  <span m="1506750">if</span> <span m="1506960">I</span> <span m="1507140">give</span>
  <span m="1507530">you</span> <span m="1507740">a</span> <span m="1507830">line,</span>
  <span m="1509390">I</span> <span m="1509510">just</span> <span m="1509690">need</span>
  <span m="1509840">to</span> <span m="1509930">count</span> <span m="1510760">now</span>
  <span m="1511040">the</span> <span m="1511220">number</span> <span m="1511760">of--</span>
  <span m="1515470">let me</span> <span m="1515610">also</span> <span m="1515820">require</span>
  <span m="1516220">that</span> <span m="1516420">these</span> <span m="1516630">two</span>
  <span m="1516780">points</span> <span m="1517050">are</span> <span m="1517110">distinct.</span>
  <span m="1517560">So</span> <span m="1517990">if</span> <span m="1518070">I</span>
  <span m="1518130">give</span> <span m="1518340">you</span> <span m="1518520">a</span>
  <span m="1518580">line,</span> <span m="1520170">I</span> <span m="1520260">now</span>
  <span m="1520710">need</span> <span m="1520860">to</span> <span m="1520920">count</span>
  <span m="1521310">the</span> <span m="1521430">number</span> <span m="1521790">of</span>
  <span m="1521880">pairs</span> <span m="1522300">of</span> <span m="1522420">points</span>
  <span m="1524050">on</span> <span m="1525040">this</span> <span m="1525440">line.</span></p><p><span
  m="1526990">So</span> <span m="1527120">I</span> <span m="1527210">can</span> <span
  m="1527360">enumerate</span> <span m="1528350">over</span> <span m="1529340">lines</span>
  <span m="1531760">and</span> <span m="1533660">count</span> <span m="1536480">line</span>
  <span m="1536750">by</span> <span m="1536930">line</span> <span m="1537650">how</span>
  <span m="1537830">many</span> <span m="1538400">pairs</span> <span m="1538760">of</span>
  <span m="1538850">points</span> <span m="1539900">are</span> <span m="1541280">on</span>
  <span m="1541520">that</span> <span m="1541760">line.</span> <span m="1542270">So</span>
  <span m="1542390">I</span> <span m="1542480">get</span> <span m="1542930">this</span>
  <span m="1543140">quantity</span> <span m="1543650">over</span> <span m="1543890">here.</span>
  <span m="1545790">On</span> <span m="1545890">each</span> <span m="1546090">line,</span>
  <span m="1546420">I</span> <span m="1546480">have</span> <span m="1547160">that</span>
  <span m="1547350">contribution.</span></p><p><span m="1548930">And</span> <span
  m="1549800">now,</span> <span m="1550330">using</span> <span m="1551770">Cauchy-Schwartz</span>
  <span m="1552840">inequality,</span> <span m="1555100">we</span> <span m="1556180">find</span>
  <span m="1557560">that</span> <span m="1558130">this</span> <span m="1558580">squared</span>
  <span m="1559120">term</span> <span m="1560080">is</span> <span m="1560470">at</span>
  <span m="1560590">least</span> <span m="1561130">the</span> <span m="1561250">number</span>
  <span m="1561730">of</span> <span m="1562900">incidences</span> <span m="1568530">divided</span>
  <span m="1568890">by</span> <span m="1569010">the</span> <span m="1569130">number</span>
  <span m="1569460">of</span> <span m="1569610">lines.</span> <span m="1571200">And</span>
  <span m="1571320">the</span> <span m="1571410">remaining</span> <span m="1571830">minus
  1</span> <span m="1572220">term</span> <span m="1572880">contributes</span> <span
  m="1573450">just</span> <span m="1573660">to</span> <span m="1573960">the</span>
  <span m="1574080">number</span> <span m="1574440">of</span> <span m="1575040">incidences.</span>
  <span m="1580090">So</span> <span m="1580120">the</span> <span m="1580210">first</span>
  <span m="1580750">is</span> <span m="1581020">by</span> <span m="1581200">Cauchy-Schwartz.</span></p><p><span
  m="1586690">So</span> <span m="1586850">putting</span> <span m="1587510">these</span>
  <span m="1587750">two</span> <span m="1588260">inequalities</span> <span m="1589130">together,</span>
  <span m="1590450">we</span> <span m="1590630">get</span> <span m="1590780">some</span>
  <span m="1592220">upper</span> <span m="1592430">bound</span> <span m="1593060">on</span>
  <span m="1593180">the</span> <span m="1593270">number</span> <span m="1593630">of</span>
  <span m="1593810">incidences.</span> <span m="1594920">If</span> <span m="1595040">you</span>
  <span m="1595100">have</span> <span m="1595190">to</span> <span m="1595880">invert</span>
  <span m="1596390">this</span> <span m="1596570">inequality,</span> <span m="1597990">you</span>
  <span m="1598010">will</span> <span m="1598100">get</span> <span m="1599390">that
  the</span> <span m="1599870">number</span> <span m="1600260">of</span> <span m="1600500">incidences</span>
  <span m="1601400">between</span> <span m="1602270">points</span> <span m="1602810">and</span>
  <span m="1602930">lines</span> <span m="1603650">is</span> <span m="1603830">upper</span>
  <span m="1604040">bounded</span> <span m="1604730">by</span> <span m="1605870">the</span>
  <span m="1605990">number</span> <span m="1606740">of</span> <span m="1608740">points</span>
  <span m="1610360">times</span> <span m="1611140">the</span> <span m="1611230">number</span>
  <span m="1611650">of</span> <span m="1611920">lines</span> <span m="1613110">raised</span>
  <span m="1613390">to</span> <span m="1613630">power</span> <span m="1613930">1/2</span>
  <span m="1615160">plus</span> <span m="1617650">the</span> <span m="1617750">number</span>
  <span m="1618020">of</span> <span m="1618140">lines.</span> <span m="1620450">So</span>
  <span m="1620550">that's</span> <span m="1620700">what</span> <span m="1620820">you</span>
  <span m="1620940">get</span> <span m="1621150">from</span> <span m="1622130">this</span>
  <span m="1622310">inequality</span> <span m="1622970">over</span> <span m="1623160">here.</span></p><p><span
  m="1626150">By</span> <span m="1626360">considering</span> <span m="1627380">point-line</span>
  <span m="1628010">duality--</span> <span m="1628720">so</span> <span m="1629060">whenever</span>
  <span m="1629360">you</span> <span m="1629540">have</span> <span m="1629900">this</span>
  <span m="1630140">kind</span> <span m="1630440">of</span> <span m="1631040">setup</span>
  <span m="1631640">involving</span> <span m="1632090">points</span> <span m="1632450">and</span>
  <span m="1632540">lines,</span> <span m="1633320">you</span> <span m="1633410">can</span>
  <span m="1633560">take</span> <span m="1633770">the</span> <span m="1634460">projected</span>
  <span m="1634880">duality</span> <span m="1635870">and</span> <span m="1636050">transform</span>
  <span m="1636590">the</span> <span m="1636830">configuration</span> <span m="1637460">into--</span>
  <span m="1638570">lines</span> <span m="1638930">into</span> <span m="1639110">points</span>
  <span m="1639440">and</span> <span m="1639530">points</span> <span m="1639860">into</span>
  <span m="1640070">lines,</span> <span m="1640400">and the</span> <span m="1640560">incidences</span>
  <span m="1641150">are</span> <span m="1641240">preserved.</span> <span m="1642560">So</span>
  <span m="1642860">I</span> <span m="1643070">also</span> <span m="1643340">have</span>
  <span m="1643550">an</span> <span m="1643640">inequality.</span> <span m="1645630">By</span>
  <span m="1646170">duality--</span> <span m="1648600">I</span> <span m="1648620">also</span>
  <span m="1648830">have</span> <span m="1648980">an</span> <span m="1649070">inequality</span>
  <span m="1649550">where</span> <span m="1649730">I</span> <span m="1649850">switch</span>
  <span m="1650860">the</span> <span m="1651080">roles</span> <span m="1651470">of</span>
  <span m="1651590">points</span> <span m="1652160">and</span> <span m="1652310">lines.</span></p><p><span
  m="1658610">So</span> <span m="1659450">I</span> <span m="1659720">is</span> <span
  m="1660020">already</span> <span m="1660350">the</span> <span m="1660440">numbers.</span>
  <span m="1660890">I</span> <span m="1660980">don't</span> <span m="1661130">need</span>
  <span m="1661250">to</span> <span m="1661310">put</span> <span m="1661520">an</span>
  <span m="1661640">extra</span> <span m="1662210">absolute</span> <span m="1662630">value</span>
  <span m="1662930">sign.</span> <span m="1664470">So</span> <span m="1665120">the</span>
  <span m="1665270">number</span> <span m="1665630">of</span> <span m="1665750">points</span>
  <span m="1666080">and</span> <span m="1666170">lines</span> <span m="1666590">is</span>
  <span m="1667130">upper</span> <span m="1667330">bounded</span> <span m="1667760">by</span>
  <span m="1668510">the</span> <span m="1668900">number</span> <span m="1669260">of</span>
  <span m="1669440">lines</span> <span m="1670130">times</span> <span m="1670460">the</span>
  <span m="1670550">square</span> <span m="1670860">root</span> <span m="1671060">of</span>
  <span m="1671160">a</span> <span m="1671240">number</span> <span m="1671510">of</span>
  <span m="1671600">points</span> <span m="1672740">plus</span> <span m="1673130">an</span>
  <span m="1673280">extra</span> <span m="1673640">term,</span> <span m="1674810">just</span>
  <span m="1675020">in</span> <span m="1675140">case</span> <span m="1675740">there</span>
  <span m="1676010">are</span> <span m="1677360">very</span> <span m="1677600">few</span>
  <span m="1677810">lines.</span> <span m="1682470">So</span> <span m="1682620">these</span>
  <span m="1682830">are</span> <span m="1682890">the</span> <span m="1682980">bounds</span>
  <span m="1683250">that</span> <span m="1683340">you</span> <span m="1683430">have</span>
  <span m="1683550">so</span> <span m="1683730">far.</span></p><p><span m="1683910">And</span>
  <span m="1684180">the</span> <span m="1684330">only</span> <span m="1684540">thing</span>
  <span m="1684750">that</span> <span m="1684900">we</span> <span m="1685020">have</span>
  <span m="1685140">used</span> <span m="1685410">so</span> <span m="1685680">far</span>
  <span m="1686160">is</span> <span m="1686550">the</span> <span m="1686670">fact</span>
  <span m="1686940">that</span> <span m="1687480">every</span> <span m="1687720">two</span>
  <span m="1687960">points</span> <span m="1688350">determine</span> <span m="1688770">at</span>
  <span m="1688860">most</span> <span m="1689130">one</span> <span m="1689340">line,</span>
  <span m="1689940">and</span> <span m="1690090">every</span> <span m="1690270">two</span>
  <span m="1690480">lines</span> <span m="1691290">meet</span> <span m="1691640">at</span>
  <span m="1691920">at</span> <span m="1692010">most</span> <span m="1692250">one</span>
  <span m="1692430">point.</span> <span m="1695290">So</span> <span m="1695410">these</span>
  <span m="1695590">are</span> <span m="1695680">the</span> <span m="1695770">bounds</span>
  <span m="1696010">that</span> <span m="1696130">we</span> <span m="1696250">get.</span>
  <span m="1697200">And</span> <span m="1697480">in</span> <span m="1697570">particular,</span>
  <span m="1698420">for</span> <span m="1698850">end</span> <span m="1699050">points</span>
  <span m="1701380">and end</span> <span m="1701770">lines,</span> <span m="1703720">we</span>
  <span m="1703840">get</span> <span m="1704120">the</span> <span m="1704230">number</span>
  <span m="1704530">of</span> <span m="1704720">incidences</span> <span m="1705510">is--</span>
  <span m="1706530">they</span> <span m="1706820">go</span> <span m="1707140">off</span>
  <span m="1707480">n</span> <span m="1707860">to the</span> <span m="1709000">3/2.</span></p><p><span
  m="1714440">This</span> <span m="1714650">should</span> <span m="1714860">remind</span>
  <span m="1715340">you</span> <span m="1715460">of</span> <span m="1715580">something</span>
  <span m="1715940">we've</span> <span m="1716120">done</span> <span m="1716630">before.</span>
  <span m="1720300">So</span> <span m="1720560">in</span> <span m="1721315">the</span>
  <span m="1721670">first</span> <span m="1721970">part</span> <span m="1722240">of</span>
  <span m="1722330">this</span> <span m="1722510">course,</span> <span m="1723560">when</span>
  <span m="1723710">we</span> <span m="1723830">were</span> <span m="1723950">looking</span>
  <span m="1724280">at</span> <span m="1724460">extremal</span> <span m="1724970">numbers,</span>
  <span m="1726710">where</span> <span m="1727000">did</span> <span m="1727130">3/2</span>
  <span m="1727730">come</span> <span m="1727970">up?</span></p><p><span m="1730500">AUDIENCE:</span>
  <span m="1730732">[INAUDIBLE]</span> <span m="1730964">like</span> <span m="1731430">C4?</span></p><p><span
  m="1732420">YUFEI ZHAO:</span> <span m="1732550">C4,</span> <span m="1733380">yeah.</span>
  <span m="1733980">So</span> <span m="1734190">if</span> <span m="1734310">you</span>
  <span m="1734400">compare</span> <span m="1734940">this</span> <span m="1735720">quantity</span>
  <span m="1736290">to</span> <span m="1736500">the</span> <span m="1736620">extremal</span>
  <span m="1737110">number</span> <span m="1737490">of</span> <span m="1738130">C4,</span>
  <span m="1740450">it's</span> <span m="1742350">also</span> <span m="1743640">n</span>
  <span m="1743890">to the</span> <span m="1743970">3/2.</span> <span m="1744690">And</span>
  <span m="1744770">in</span> <span m="1744840">fact,</span> <span m="1745020">the</span>
  <span m="1745080">proof</span> <span m="1745410">is</span> <span m="1745500">exactly</span>
  <span m="1745860">the</span> <span m="1745920">same.</span> <span m="1747750">All</span>
  <span m="1747900">we're</span> <span m="1748050">using</span> <span m="1748380">here</span>
  <span m="1748770">is</span> <span m="1748920">that</span> <span m="1749040">the</span>
  <span m="1749130">incidence</span> <span m="1749550">graph</span> <span m="1749850">is</span>
  <span m="1749940">C4-free</span></p><p><span m="1752110">So</span> <span m="1752240">in</span>
  <span m="1752330">fact,</span> <span m="1752600">this</span> <span m="1752810">is</span>
  <span m="1754040">an</span> <span m="1754190">argument</span> <span m="1755270">about</span>
  <span m="1755930">C4-free</span> <span m="1756650">graphs.</span> <span m="1757700">So</span>
  <span m="1757850">this</span> <span m="1758660">fact</span> <span m="1758990">here,</span>
  <span m="1759350">every</span> <span m="1759560">two</span> <span m="1759740">points</span>
  <span m="1760130">determine</span> <span m="1760520">at</span> <span m="1760610">most</span>
  <span m="1760850">one</span> <span m="1761060">line,</span> <span m="1761470">is</span>
  <span m="1761630">saying</span> <span m="1761930">that</span> <span m="1763250">if</span>
  <span m="1763340">you</span> <span m="1763400">look</span> <span m="1763580">at</span>
  <span m="1763640">the</span> <span m="1763730">incidence</span> <span m="1764240">graph,</span>
  <span m="1765080">there's</span> <span m="1765290">no</span> <span m="1766330">C4.</span>
  <span m="1768000">That's</span> <span m="1768520">all</span> <span m="1768610">we're</span>
  <span m="1768730">using</span> <span m="1769030">for</span> <span m="1769150">now.</span>
  <span m="1770670">Any</span> <span m="1770830">questions?</span></p><p><span m="1775410">So</span>
  <span m="1775590">is</span> <span m="1775770">this</span> <span m="1775950">the</span>
  <span m="1776040">truth?</span> <span m="1777000">Now,</span> <span m="1777440">back</span>
  <span m="1777710">when</span> <span m="1777890">we</span> <span m="1777960">were</span>
  <span m="1778110">discussing</span> <span m="1778740">the</span> <span m="1778860">extremal</span>
  <span m="1779310">number</span> <span m="1779640">for</span> <span m="1780230">C4-free</span>
  <span m="1781170">graphs,</span> <span m="1782130">we</span> <span m="1782280">saw</span>
  <span m="1782520">that,</span> <span m="1783220">in</span> <span m="1783240">fact,</span>
  <span m="1783580">this</span> <span m="1783650">is</span> <span m="1783780">the</span>
  <span m="1783840">correct</span> <span m="1784290">order.</span> <span m="1785460">And</span>
  <span m="1785550">what</span> <span m="1785670">was</span> <span m="1785850">the</span>
  <span m="1785940">construction</span> <span m="1786570">there?</span></p><p><span
  m="1793550">So</span> <span m="1793670">the</span> <span m="1793760">construction</span>
  <span m="1794720">also</span> <span m="1795020">came</span> <span m="1795290">from</span>
  <span m="1795530">incidences,</span> <span m="1796790">but</span> <span m="1797240">incidences</span>
  <span m="1798080">of</span> <span m="1798290">taking</span> <span m="1799070">all</span>
  <span m="1799310">lines</span> <span m="1801290">and</span> <span m="1801440">points</span>
  <span m="1802940">in</span> <span m="1804170">the</span> <span m="1804590">finite</span>
  <span m="1804980">field</span> <span m="1805430">plain,</span> <span m="1806340">Fq</span>
  <span m="1806990">squared.</span> <span m="1807950">If</span> <span m="1808040">you</span>
  <span m="1808130">look</span> <span m="1808280">at</span> <span m="1808430">all</span>
  <span m="1808570">the</span> <span m="1808670">lines</span> <span m="1809000">and</span>
  <span m="1809120">all</span> <span m="1809210">the</span> <span m="1809300">points</span>
  <span m="1810740">in</span> <span m="1810890">a</span> <span m="1810980">finite</span>
  <span m="1811340">field</span> <span m="1812030">plain,</span> <span m="1812930">then</span>
  <span m="1813530">you</span> <span m="1813740">get</span> <span m="1814100">the</span>
  <span m="1814280">correct</span> <span m="1815840">lower</span> <span m="1816080">bound</span>
  <span m="1816560">for</span> <span m="1817250">C4.</span> <span m="1818750">But</span>
  <span m="1818870">now</span> <span m="1819830">we</span> <span m="1820070">are</span>
  <span m="1820250">actually</span> <span m="1820940">working</span> <span m="1821570">in</span>
  <span m="1821960">the</span> <span m="1822080">real</span> <span m="1822440">plane,</span>
  <span m="1823490">so</span> <span m="1824840">it</span> <span m="1824960">turns</span>
  <span m="1825320">out</span> <span m="1825500">that</span> <span m="1825620">the</span>
  <span m="1825830">answer</span> <span m="1826220">is</span> <span m="1826430">different</span>
  <span m="1827930">when</span> <span m="1828110">you're</span> <span m="1828260">not</span>
  <span m="1828560">working</span> <span m="1828890">the</span> <span m="1828980">finite</span>
  <span m="1829340">field.</span></p><p><span m="1830120">We're</span> <span m="1830180">going</span>
  <span m="1830330">to</span> <span m="1830420">be</span> <span m="1830570">using</span>
  <span m="1830960">the</span> <span m="1831230">topology</span> <span m="1831860">of</span>
  <span m="1831950">the</span> <span m="1832040">real</span> <span m="1832340">plane.</span>
  <span m="1833660">And</span> <span m="1833810">we're</span> <span m="1833900">going</span>
  <span m="1834020">to</span> <span m="1834080">come</span> <span m="1834260">up</span>
  <span m="1834350">with</span> <span m="1834470">a</span> <span m="1834530">different</span>
  <span m="1834800">answer.</span> <span m="1835740">So</span> <span m="1835790">it</span>
  <span m="1835880">turns</span> <span m="1836180">out</span> <span m="1837500">that</span>
  <span m="1838730">the</span> <span m="1839180">truth</span> <span m="1839870">for</span>
  <span m="1840680">the</span> <span m="1840770">number</span> <span m="1841070">of</span>
  <span m="1841310">maximum</span> <span m="1841820">number</span> <span m="1842060">of</span>
  <span m="1842210">incidences</span> <span m="1843050">in</span> <span m="1843140">the</span>
  <span m="1843230">plane,</span> <span m="1844210">for</span> <span m="1844490">points</span>
  <span m="1844790">and</span> <span m="1844880">lines</span> <span m="1846020">in</span>
  <span m="1846120">the</span> <span m="1846170">real</span> <span m="1846380">plane,</span>
  <span m="1847040">is</span> <span m="1847220">not</span> <span m="1847900">exponent</span>
  <span m="1848420">3/2,</span> <span m="1850020">but</span> <span m="1850530">turns</span>
  <span m="1850740">out</span> <span m="1850860">to</span> <span m="1850950">be</span>
  <span m="1851190">4/3.</span></p><p><span m="1853770">And</span> <span m="1853980">this</span>
  <span m="1854430">is</span> <span m="1854580">a</span> <span m="1854640">consequence</span>
  <span m="1855450">of</span> <span m="1855780">an</span> <span m="1855900">important</span>
  <span m="1856350">result</span> <span m="1856710">in</span> <span m="1856860">incidence</span>
  <span m="1857310">geometry,</span> <span m="1857820">a</span> <span m="1857880">fundamental</span>
  <span m="1858360">result,</span> <span m="1858950">known</span> <span m="1859200">as</span>
  <span m="1859320">the</span> <span m="1859410">Szemeredi-Trotter</span> <span m="1860370">theorem.</span>
  <span m="1867080">So</span> <span m="1868878">the</span> <span m="1869280">Szemeredi-Trotter</span>
  <span m="1870110">theorem</span> <span m="1870990">says</span> <span m="1871350">that</span>
  <span m="1871560">the</span> <span m="1871710">number</span> <span m="1872190">of</span>
  <span m="1872450">incidences</span> <span m="1873390">between</span> <span m="1874320">points</span>
  <span m="1874770">and</span> <span m="1874890">lines</span> <span m="1877050">is</span>
  <span m="1877370">upper</span> <span m="1877620">bounded</span> <span m="1878160">by</span>
  <span m="1878400">this</span> <span m="1878730">function</span> <span m="1879060">where</span>
  <span m="1879720">you</span> <span m="1879810">look</span> <span m="1879990">at</span>
  <span m="1880060">the</span> <span m="1880110">number</span> <span m="1880440">of</span>
  <span m="1880530">points</span> <span m="1880920">times</span> <span m="1881260">the</span>
  <span m="1881320">number</span> <span m="1881580">of</span> <span m="1881700">lines,</span>
  <span m="1882740">and</span> <span m="1882930">each</span> <span m="1883320">raised</span>
  <span m="1883710">to</span> <span m="1884010">power</span> <span m="1885390">2/3</span>
  <span m="1890980">and</span> <span m="1891310">plus</span> <span m="1892600">some</span>
  <span m="1893020">additional</span> <span m="1893860">terms,</span> <span m="1894250">just</span>
  <span m="1894520">in</span> <span m="1894640">case</span> <span m="1895360">there</span>
  <span m="1895510">are</span> <span m="1895960">many</span> <span m="1896230">more</span>
  <span m="1896440">lines</span> <span m="1896740">compared</span> <span m="1897070">to</span>
  <span m="1897130">points</span> <span m="1897520">or</span> <span m="1898060">way</span>
  <span m="1898360">more</span> <span m="1898660">points</span> <span m="1899050">compared</span>
  <span m="1899370">to</span> <span m="1899500">lines.</span></p><p><span m="1901170">So</span>
  <span m="1901240">that's</span> <span m="1901450">the</span> <span m="1901570">Szemeredi-Trotter</span>
  <span m="1902890">theorem.</span> <span m="1904070">And</span> <span m="1904210">as</span>
  <span m="1904360">a</span> <span m="1904390">corollary,</span> <span m="1907030">you</span>
  <span m="1907120">see</span> <span m="1907300">that</span> <span m="1907480">n</span>
  <span m="1907690">points,</span> <span m="1909250">n</span> <span m="1909400">lines</span>
  <span m="1911800">give</span> <span m="1911980">you</span> <span m="1912190">at</span>
  <span m="1912310">most</span> <span m="1912760">n</span> <span m="1912970">to</span>
  <span m="1913090">the</span> <span m="1913750">4/3</span> <span m="1914590">incidences,</span>
  <span m="1917910">in</span> <span m="1918060">contrast</span> <span m="1918930">to</span>
  <span m="1919080">the</span> <span m="1919170">setting</span> <span m="1919950">of</span>
  <span m="1922900">the</span> <span m="1923040">finite</span> <span m="1923550">field</span>
  <span m="1924360">plain,</span> <span m="1925320">where</span> <span m="1925620">you</span>
  <span m="1925770">can</span> <span m="1925950">get</span> <span m="1926280">n to</span>
  <span m="1926520">the</span> <span m="1926610">3/2</span> <span m="1927210">incidences.</span>
  <span m="1928150">So</span> <span m="1928250">somehow,</span> <span m="1928500">we</span>
  <span m="1928620">have</span> <span m="1928830">to</span> <span m="1928950">use</span>
  <span m="1930030">the</span> <span m="1930210">topology</span> <span m="1930870">of</span>
  <span m="1931020">the</span> <span m="1931110">real</span> <span m="1931410">plane</span>
  <span m="1931890">for</span> <span m="1932070">this</span> <span m="1932280">one.</span></p><p><span
  m="1933280">And</span> <span m="1933990">I</span> <span m="1934050">want</span>
  <span m="1934200">to</span> <span m="1934260">show</span> <span m="1934470">you</span>
  <span m="1934620">a</span> <span m="1934680">proof--</span> <span m="1935370">turns</span>
  <span m="1935590">out</span> <span m="1935760">not</span> <span m="1935940">the</span>
  <span m="1936060">original</span> <span m="1936480">proof,</span> <span m="1937080">but</span>
  <span m="1937400">it's a</span> <span m="1937580">proof</span> <span m="1937920">that</span>
  <span m="1938190">uses</span> <span m="1938580">the</span> <span m="1938670">crossing</span>
  <span m="1939180">number</span> <span m="1939490">inequality</span> <span m="1940650">to</span>
  <span m="1940830">prove</span> <span m="1942000">Szemeredi-Trotter</span> <span
  m="1942870">theorem.</span> <span m="1943680">You</span> <span m="1943740">see,</span>
  <span m="1943920">in</span> <span m="1944190">crossing</span> <span m="1944460">number</span>
  <span m="1944670">inequality,</span> <span m="1945150">we</span> <span m="1945330">are</span>
  <span m="1945540">using</span> <span m="1945930">the</span> <span m="1946020">topology</span>
  <span m="1946620">of</span> <span m="1946800">the</span> <span m="1946920">real</span>
  <span m="1947190">plane.</span> <span m="1949290">Where?</span></p><p><span m="1951830">AUDIENCE:</span>
  <span m="1951981">Euler's</span> <span m="1952132">formula.</span></p><p><span m="1952740">YUFEI
  ZHAO:</span> <span m="1952900">Euler's</span> <span m="1953230">formula,</span>
  <span m="1953590">right.</span> <span m="1953940">So</span> <span m="1954040">the</span>
  <span m="1954130">very</span> <span m="1954730">beginning,</span> <span m="1955150">Euler's</span>
  <span m="1955450">formula</span> <span m="1956020">has</span> <span m="1956260">to</span>
  <span m="1956320">do</span> <span m="1956470">with</span> <span m="1956620">the</span>
  <span m="1956680">topology</span> <span m="1957220">of</span> <span m="1957310">the</span>
  <span m="1957400">real</span> <span m="1957640">plane.</span> <span m="1960290">Now,</span>
  <span m="1960550">this</span> <span m="1960790">bound</span> <span m="1961150">turns</span>
  <span m="1961480">out</span> <span m="1961690">to</span> <span m="1961840">be</span>
  <span m="1962770">tight.</span> <span m="1963790">So</span> <span m="1963940">let</span>
  <span m="1964060">me</span> <span m="1964180">give</span> <span m="1964360">you</span>
  <span m="1964480">an</span> <span m="1964570">example</span> <span m="1965140">showing</span>
  <span m="1965530">that</span> <span m="1965680">the</span> <span m="1965770">4/3</span>
  <span m="1967090">exponent</span> <span m="1967630">is</span> <span m="1967780">tight.</span></p><p><span
  m="1969880">And</span> <span m="1970000">the</span> <span m="1970090">example</span>
  <span m="1970810">is,</span> <span m="1973870">if</span> <span m="1974020">you</span>
  <span m="1974140">take</span> <span m="1974740">p</span> <span m="1975340">to</span>
  <span m="1975490">be</span> <span m="1976270">this</span> <span m="1977290">rectangular</span>
  <span m="1978130">grid</span> <span m="1978550">of</span> <span m="1978700">points,</span>
  <span m="1986420">and</span> <span m="1986990">L</span> <span m="1987620">to</span>
  <span m="1987770">be</span> <span m="1988700">a</span> <span m="1988790">set</span>
  <span m="1989060">of</span> <span m="1989150">lines--</span> <span m="1989650">so
  I'm</span> <span m="1989750">going</span> <span m="1989850">to</span> <span m="1989960">write</span>
  <span m="1990350">the</span> <span m="1990440">lines</span> <span m="1990830">by</span>
  <span m="1991300">their</span> <span m="1991490">equation,</span> <span m="1993710">where</span>
  <span m="1993980">the</span> <span m="1994130">slope</span> <span m="1995570">is</span>
  <span m="1995930">an</span> <span m="1996050">integer</span> <span m="1996410">from</span>
  <span m="1996620">1</span> <span m="1996800">through</span> <span m="1996980">k</span>
  <span m="1997730">and</span> <span m="1997910">the</span> <span m="1998450">y-intercept</span>
  <span m="1999490">is</span> <span m="1999650">an</span> <span m="1999710">integer</span>
  <span m="2000130">from</span> <span m="2000460">1</span> <span m="2001090">through</span>
  <span m="2001300">k</span> <span m="2001570">squared.</span> <span m="2003610">And</span>
  <span m="2003760">you</span> <span m="2003880">see</span> <span m="2004090">here</span>
  <span m="2004390">that</span> <span m="2004660">every</span> <span m="2004960">line</span>
  <span m="2008260">in</span> <span m="2009790">L</span> <span m="2010230">contains</span>
  <span m="2012730">exactly</span> <span m="2013780">k</span> <span m="2013990">points</span>
  <span m="2016760">from</span> <span m="2017000">P.</span> <span m="2018590">So</span>
  <span m="2019460">we</span> <span m="2019580">got</span> <span m="2020870">in</span>
  <span m="2020960">total</span> <span m="2021890">k</span> <span m="2022130">to</span>
  <span m="2022280">the</span> <span m="2022400">4th</span> <span m="2023000">incidences,</span>
  <span m="2026310">which</span> <span m="2026670">is</span> <span m="2027270">on</span>
  <span m="2027390">the</span> <span m="2027510">order</span> <span m="2027930">of</span>
  <span m="2029370">n</span> <span m="2029580">to</span> <span m="2029730">the</span>
  <span m="2030730">4/3.</span> <span m="2033840">So</span> <span m="2033910">n to</span>
  <span m="2034110">the</span> <span m="2034200">4/3</span> <span m="2034420">third</span>
  <span m="2034980">is</span> <span m="2035240">the</span> <span m="2035350">right</span>
  <span m="2035550">answer.</span></p><p><span m="2039580">Now</span> <span m="2039650">let</span>
  <span m="2039770">me</span> <span m="2039920">show</span> <span m="2040160">you</span>
  <span m="2040280">how</span> <span m="2040460">to</span> <span m="2040580">prove</span>
  <span m="2040850">Szemeredi-Trotter</span> <span m="2041400">theorem</span> <span
  m="2041930">from</span> <span m="2042290">the</span> <span m="2042380">crossing</span>
  <span m="2042800">number</span> <span m="2043090">inequality.</span> <span m="2043980">It</span>
  <span m="2044270">turns</span> <span m="2044510">out</span> <span m="2044600">to</span>
  <span m="2044690">be</span> <span m="2045080">a</span> <span m="2045350">very</span>
  <span m="2045590">neat</span> <span m="2045820">application</span> <span m="2046530">that's</span>
  <span m="2046700">almost</span> <span m="2047050">a</span> <span m="2047120">direct</span>
  <span m="2047420">consequence</span> <span m="2048199">once</span> <span m="2048469">you</span>
  <span m="2048560">set</span> <span m="2048830">up</span> <span m="2048920">the</span>
  <span m="2049040">right</span> <span m="2049280">graph.</span> <span m="2050610">And</span>
  <span m="2050840">the</span> <span m="2050989">idea</span> <span m="2051560">is</span>
  <span m="2051739">that</span> <span m="2051920">we</span> <span m="2052070">are</span>
  <span m="2052159">going</span> <span m="2052429">to</span> <span m="2053659">draw</span>
  <span m="2053989">a</span> <span m="2054080">graph</span> <span m="2054889">based</span>
  <span m="2055550">on</span> <span m="2056150">our</span> <span m="2057560">incidence</span>
  <span m="2057949">configuration.</span></p><p><span m="2059570">So</span> <span
  m="2059690">first,</span> <span m="2064040">just</span> <span m="2064280">to</span>
  <span m="2064639">clean</span> <span m="2064969">things</span> <span m="2065239">up</span>
  <span m="2065360">a</span> <span m="2065420">little</span> <span m="2065600">bit,</span>
  <span m="2066900">let's</span> <span m="2067489">get</span> <span m="2067730">rid</span>
  <span m="2067940">of</span> <span m="2072409">lines</span> <span m="2074690">in</span>
  <span m="2075350">L</span> <span m="2075770">with</span> <span m="2077630">1</span>
  <span m="2078020">or</span> <span m="2078230">0</span> <span m="2078590">points</span>
  <span m="2080450">in</span> <span m="2080910">P.</span> <span m="2081830">So</span>
  <span m="2082190">this</span> <span m="2083210">operation</span> <span m="2083810">doesn't</span>
  <span m="2084170">affect</span> <span m="2084560">the</span> <span m="2084679">bounds.</span>
  <span m="2085219">So</span> <span m="2085340">you</span> <span m="2085429">can</span>
  <span m="2085550">check.</span> <span m="2086810">These</span> <span m="2087050">lines</span>
  <span m="2087620">don't</span> <span m="2087830">contribute</span> <span m="2088520">much</span>
  <span m="2088820">to</span> <span m="2089000">the</span> <span m="2089090">incidence</span>
  <span m="2089510">bound,</span> <span m="2090170">and</span> <span m="2090380">only</span>
  <span m="2091100">contributes</span> <span m="2091580">to</span> <span m="2091850">this</span>
  <span m="2092030">plus</span> <span m="2092350">L.</span> <span m="2093260">So</span>
  <span m="2093530">you</span> <span m="2093620">can</span> <span m="2093800">get</span>
  <span m="2093980">rid</span> <span m="2094159">of</span> <span m="2094400">such</span>
  <span m="2094699">lines.</span></p><p><span m="2095600">So</span> <span m="2095719">let's</span>
  <span m="2096139">assume</span> <span m="2096679">that</span> <span m="2099890">every</span>
  <span m="2100130">line</span> <span m="2102710">in</span> <span m="2102970">L</span>
  <span m="2103830">contains</span> <span m="2107560">at</span> <span m="2107650">least</span>
  <span m="2108250">two</span> <span m="2109150">points</span> <span m="2112410">from</span>
  <span m="2112630">P.</span> <span m="2114390">And</span> <span m="2115800">let's</span>
  <span m="2116040">draw</span> <span m="2116370">a</span> <span m="2116460">graph</span>
  <span m="2117120">based</span> <span m="2117510">on</span> <span m="2117720">this</span>
  <span m="2117930">incidence</span> <span m="2118290">structure.</span> <span m="2119010">So</span>
  <span m="2119190">if</span> <span m="2119370">I</span> <span m="2119490">have--</span>
  <span m="2127850">so</span> <span m="2128240">suppose</span> <span m="2134850">these</span>
  <span m="2135060">are</span> <span m="2135150">my</span> <span m="2135300">points</span>
  <span m="2135810">and</span> <span m="2135960">lines.</span></p><p><span m="2136980">I'll</span>
  <span m="2137100">just</span> <span m="2137280">draw</span> <span m="2137520">a</span>
  <span m="2137580">graph</span> <span m="2138840">where</span> <span m="2139110">I</span>
  <span m="2139230">keep</span> <span m="2139560">the</span> <span m="2139680">points</span>
  <span m="2140190">as</span> <span m="2140370">the</span> <span m="2140460">vertices,</span>
  <span m="2145080">and</span> <span m="2145710">I</span> <span m="2145830">put</span>
  <span m="2146100">in</span> <span m="2146490">an</span> <span m="2146670">edge.</span>
  <span m="2147560">It's</span> <span m="2147900">a</span> <span m="2147990">finite</span>
  <span m="2148740">edge</span> <span m="2149630">that</span> <span m="2149790">connects</span>
  <span m="2154250">two</span> <span m="2154490">adjacent</span> <span m="2154940">points</span>
  <span m="2155900">on</span> <span m="2156020">the</span> <span m="2156110">same</span>
  <span m="2156380">line.</span> <span m="2162590">So</span> <span m="2162610">I</span>
  <span m="2162670">get</span> <span m="2162820">some</span> <span m="2162970">graph.</span></p><p><span
  m="2169480">Let</span> <span m="2169570">me</span> <span m="2170380">make</span>
  <span m="2170650">this</span> <span m="2170860">graph</span> <span m="2171220">a</span>
  <span m="2171310">bit</span> <span m="2171670">more</span> <span m="2171970">interesting.</span>
  <span m="2183680">So</span> <span m="2183700">I</span> <span m="2183730">get</span>
  <span m="2183880">some</span> <span m="2184000">graph.</span> <span m="2185080">And</span>
  <span m="2186280">how</span> <span m="2186490">many</span> <span m="2186760">crossings,</span>
  <span m="2187930">at</span> <span m="2188050">most,</span> <span m="2188410">does</span>
  <span m="2188530">this</span> <span m="2188710">graph</span> <span m="2189060">have?</span></p><p><span
  m="2191340">So</span> <span m="2191760">the</span> <span m="2191850">number</span>
  <span m="2192330">of</span> <span m="2192540">crossings</span> <span m="2195330">of</span>
  <span m="2195550">G</span> <span m="2197400">is</span> <span m="2198680">at</span>
  <span m="2199070">most</span> <span m="2202030">the</span> <span m="2202140">number</span>
  <span m="2202620">of</span> <span m="2202860">lines</span> <span m="2203400">squared,</span>
  <span m="2204750">because</span> <span m="2205380">a</span> <span m="2205440">crossing</span>
  <span m="2205920">comes</span> <span m="2206250">from</span> <span m="2206400">two</span>
  <span m="2206610">lines.</span> <span m="2210040">So</span> <span m="2210060">here,</span>
  <span m="2210270">you</span> <span m="2210360">have</span> <span m="2210450">a</span>
  <span m="2210510">crossing.</span> <span m="2210870">A</span> <span m="2210990">crossing</span>
  <span m="2211410">comes</span> <span m="2211680">from</span> <span m="2211830">two</span>
  <span m="2211980">lines.</span> <span m="2212640">Number</span> <span m="2212880">of</span>
  <span m="2212940">crossings</span> <span m="2213360">is</span> <span m="2213440">at</span>
  <span m="2213510">most</span> <span m="2213720">number</span> <span m="2213990">of</span>
  <span m="2214080">lines</span> <span m="2214320">squared.</span></p><p><span m="2217380">On</span>
  <span m="2217430">the</span> <span m="2217520">other</span> <span m="2217700">hand,</span>
  <span m="2218490">we</span> <span m="2218510">can</span> <span m="2218660">give</span>
  <span m="2218870">a</span> <span m="2218930">lower</span> <span m="2219230">bound</span>
  <span m="2219500">to</span> <span m="2219620">the</span> <span m="2219710">number</span>
  <span m="2219980">of</span> <span m="2220070">crossings</span> <span m="2220730">from</span>
  <span m="2220970">the</span> <span m="2221060">crossing</span> <span m="2221450">number</span>
  <span m="2221790">inequality.</span> <span m="2224820">And</span> <span m="2224940">to</span>
  <span m="2225030">do</span> <span m="2225180">that,</span> <span m="2225390">I</span>
  <span m="2225510">want</span> <span m="2225720">to</span> <span m="2225810">estimate</span>
  <span m="2226230">the</span> <span m="2226320">number</span> <span m="2226650">of</span>
  <span m="2226890">edges.</span> <span m="2227470">And</span> <span m="2227730">this</span>
  <span m="2227910">is</span> <span m="2228010">the</span> <span m="2228070">reason</span>
  <span m="2228330">why I</span> <span m="2228540">assume</span> <span m="2228870">every</span>
  <span m="2229110">line</span> <span m="2229380">contains</span> <span m="2229770">at</span>
  <span m="2229860">least</span> <span m="2230010">two</span> <span m="2230250">points</span>
  <span m="2230610">from</span> <span m="2230820">P,</span> <span m="2231960">because</span>
  <span m="2232860">a</span> <span m="2232920">line</span> <span m="2234870">with</span>
  <span m="2235590">now</span> <span m="2235830">k</span> <span m="2236580">incidences</span>
  <span m="2240600">gives</span> <span m="2242260">k</span> <span m="2242470">minus</span>
  <span m="2242830">1</span> <span m="2243320">edges.</span></p><p><span m="2246690">And</span>
  <span m="2247110">if</span> <span m="2247230">k</span> <span m="2247530">is</span>
  <span m="2247860">at</span> <span m="2248010">least</span> <span m="2248280">2,</span>
  <span m="2248610">then</span> <span m="2248880">k</span> <span m="2249090">minus</span>
  <span m="2249360">1</span> <span m="2249630">is</span> <span m="2249780">at</span>
  <span m="2249870">least</span> <span m="2251136">k</span> <span m="2251620">over</span>
  <span m="2251820">2,</span> <span m="2252300">let's</span> <span m="2252420">say.</span>
  <span m="2253410">I</span> <span m="2253470">don't</span> <span m="2253620">care</span>
  <span m="2253800">about</span> <span m="2253980">constant</span> <span m="2254370">factors.</span>
  <span m="2255990">So</span> <span m="2256770">by</span> <span m="2256980">crossing</span>
  <span m="2257370">number</span> <span m="2257640">inequality,</span> <span m="2261270">the</span>
  <span m="2261450">number</span> <span m="2261960">of</span> <span m="2262200">crossings</span>
  <span m="2263880">of</span> <span m="2264000">G</span> <span m="2264920">is</span>
  <span m="2265140">at</span> <span m="2265230">least</span> <span m="2266130">the</span>
  <span m="2266220">number</span> <span m="2266610">of</span> <span m="2267150">edges</span>
  <span m="2267600">cubed</span> <span m="2268590">over</span> <span m="2268860">the</span>
  <span m="2268950">number</span> <span m="2269280">of</span> <span m="2269550">vertices</span>
  <span m="2270210">squared,</span> <span m="2271810">which</span> <span m="2271920">is</span>
  <span m="2272970">at</span> <span m="2273070">least</span> <span m="2275340">the</span>
  <span m="2276000">number</span> <span m="2276450">of</span> <span m="2277590">incidences</span>
  <span m="2280320">of</span> <span m="2281070">this</span> <span m="2281280">configuration</span>
  <span m="2282600">cubed</span> <span m="2283350">over</span> <span m="2283590">the</span>
  <span m="2283680">number</span> <span m="2284070">of</span> <span m="2284460">points</span>
  <span m="2285300">squared.</span> <span m="2285980">Actually,</span> <span m="2286410">number</span>
  <span m="2286620">of</span> <span m="2286680">vertices</span> <span m="2287160">is</span>
  <span m="2287280">the</span> <span m="2287370">number</span> <span m="2287610">of</span>
  <span m="2287700">points.</span> <span m="2288540">And</span> <span m="2288600">number</span>
  <span m="2289020">of</span> <span m="2289260">edges,</span> <span m="2289920">by</span>
  <span m="2290130">this</span> <span m="2290430">argument</span> <span m="2290850">here,</span>
  <span m="2292050">is</span> <span m="2292580">on</span> <span m="2292710">the</span>
  <span m="2292770">same</span> <span m="2293040">order</span> <span m="2293460">as</span>
  <span m="2293610">the</span> <span m="2293700">number</span> <span m="2294060">of</span>
  <span m="2294430">incidences.</span></p><p><span m="2298500">Putting</span> <span
  m="2299460">these</span> <span m="2299670">two</span> <span m="2300420">facts</span>
  <span m="2301080">together,</span> <span m="2302490">we</span> <span m="2302640">see--</span>
  <span m="2304470">there</span> <span m="2304590">was</span> <span m="2304740">one</span>
  <span m="2304950">extra</span> <span m="2305730">hypothesis</span> <span m="2306650">in</span>
  <span m="2306840">crossing</span> <span m="2307230">number</span> <span m="2307470">inequality.</span>
  <span m="2309510">Provided</span> <span m="2310410">that</span> <span m="2310860">this</span>
  <span m="2311040">hypothesis</span> <span m="2311910">holds,</span> <span m="2312780">which</span>
  <span m="2313050">is</span> <span m="2313320">that</span> <span m="2313590">the</span>
  <span m="2314250">number</span> <span m="2314700">of</span> <span m="2316690">incidences</span>
  <span m="2317610">is</span> <span m="2318210">at</span> <span m="2318300">least</span>
  <span m="2322330">8</span> <span m="2322990">times</span> <span m="2323590">the</span>
  <span m="2323680">number</span> <span m="2324040">of</span> <span m="2326170">points,</span>
  <span m="2328720">so</span> <span m="2328870">that</span> <span m="2329730">the</span>
  <span m="2330520">original</span> <span m="2330880">hypothesis</span> <span m="2331860">holds.</span>
  <span m="2334810">So</span> <span m="2334960">putting</span> <span m="2335290">everything</span>
  <span m="2335620">together,</span> <span m="2336940">and</span> <span m="2337390">rearranging</span>
  <span m="2338080">all</span> <span m="2338230">of</span> <span m="2338320">these</span>
  <span m="2339010">terms,</span> <span m="2339910">and</span> <span m="2340480">using</span>
  <span m="2341080">upper</span> <span m="2341370">and</span> <span m="2341510">lower</span>
  <span m="2341730">bounds</span> <span m="2342190">on</span> <span m="2342310">the</span>
  <span m="2342370">crossing</span> <span m="2342760">number,</span> <span m="2343480">we</span>
  <span m="2343630">find</span> <span m="2344650">that</span> <span m="2345480">the</span>
  <span m="2345580">number</span> <span m="2346030">of</span> <span m="2346510">incidences</span>
  <span m="2348460">is</span> <span m="2349210">upper</span> <span m="2349450">bounded</span>
  <span m="2350200">by--</span> <span m="2350980">the</span> <span m="2351100">main</span>
  <span m="2351490">term</span> <span m="2351850">you</span> <span m="2351940">see</span>
  <span m="2352330">is</span> <span m="2352720">just</span> <span m="2353740">coming</span>
  <span m="2354010">from</span> <span m="2354220">these</span> <span m="2354430">two,</span>
  <span m="2362750">but</span> <span m="2362990">there</span> <span m="2363290">are</span>
  <span m="2363860">a</span> <span m="2363950">few</span> <span m="2364430">other</span>
  <span m="2364670">terms</span> <span m="2365970">that</span> <span m="2366170">we</span>
  <span m="2366320">should</span> <span m="2366470">put</span> <span m="2366650">in,</span>
  <span m="2367280">just</span> <span m="2367640">in</span> <span m="2367790">case</span>
  <span m="2368660">this</span> <span m="2368870">hypothesis</span> <span m="2369590">is</span>
  <span m="2369920">violated,</span> <span m="2371170">and</span> <span m="2371620">also</span>
  <span m="2371890">to</span> <span m="2372020">take</span> <span m="2372260">care</span>
  <span m="2372590">of</span> <span m="2373340">this</span> <span m="2373520">assumption</span>
  <span m="2374240">over</span> <span m="2374480">here,</span> <span m="2375080">so</span>
  <span m="2377770">adding</span> <span m="2378070">a</span> <span m="2378130">couple</span>
  <span m="2378400">of</span> <span m="2378490">linear</span> <span m="2378790">terms</span>
  <span m="2379150">corresponding</span> <span m="2379660">to</span> <span m="2379730">the</span>
  <span m="2379780">number</span> <span m="2380050">of</span> <span m="2380140">points</span>
  <span m="2380560">and</span> <span m="2380690">the</span> <span m="2380770">number</span>
  <span m="2381040">of</span> <span m="2381160">lines.</span></p><p><span m="2383200">If</span>
  <span m="2384100">this</span> <span m="2384310">hypothesis</span> <span m="2384910">is</span>
  <span m="2385030">violated,</span> <span m="2385750">then the</span> <span m="2386140">inequality</span>
  <span m="2386680">is</span> <span m="2386800">still</span> <span m="2387040">true.</span>
  <span m="2391650">So</span> <span m="2391770">this</span> <span m="2391920">proves</span>
  <span m="2392250">the</span> <span m="2392340">crossing</span> <span m="2392790">numbers</span>
  <span m="2393170">inequality.</span> <span m="2395430">Any</span> <span m="2395610">questions?</span></p><p><span
  m="2400790">So</span> <span m="2401180">we've</span> <span m="2401390">done</span>
  <span m="2403220">these</span> <span m="2403400">two</span> <span m="2404180">very</span>
  <span m="2404390">neat</span> <span m="2405170">results.</span> <span m="2406450">The</span>
  <span m="2406760">question is,</span> <span m="2407070">what</span> <span m="2407240">do</span>
  <span m="2407360">they</span> <span m="2407480">have</span> <span m="2407690">to</span>
  <span m="2407780">do</span> <span m="2408050">with</span> <span m="2408470">the</span>
  <span m="2408850">sum</span> <span m="2409280">product</span> <span m="2409760">problem?</span>
  <span m="2411790">So</span> <span m="2412000">I</span> <span m="2412060">want</span>
  <span m="2412210">to</span> <span m="2412270">show</span> <span m="2412480">you</span>
  <span m="2413050">how</span> <span m="2413380">you</span> <span m="2413560">can</span>
  <span m="2414130">give</span> <span m="2414370">some</span> <span m="2414670">lower</span>
  <span m="2414940">bound</span> <span m="2415390">on</span> <span m="2415570">the
  sum</span> <span m="2415900">product</span> <span m="2416230">problem</span> <span
  m="2416980">using</span> <span m="2418300">Szemeredi-Trotter</span> <span m="2419650">theorem.</span></p><p><span
  m="2422650">So</span> <span m="2422870">it</span> <span m="2422930">turns</span>
  <span m="2423260">out</span> <span m="2423530">that</span> <span m="2423770">the</span>
  <span m="2423980">sum</span> <span m="2424310">product</span> <span m="2424670">problem</span>
  <span m="2425060">is</span> <span m="2425270">intimately</span> <span m="2425750">related</span>
  <span m="2426200">to</span> <span m="2426770">incidence</span> <span m="2427220">geometry.</span>
  <span m="2428780">And</span> <span m="2428900">the</span> <span m="2428990">reason--</span>
  <span m="2430400">you'll</span> <span m="2430580">see in</span> <span m="2430880">a</span>
  <span m="2430940">second</span> <span m="2431570">precisely</span> <span m="2432110">why</span>
  <span m="2432320">they're</span> <span m="2432500">related,</span> <span m="2433250">but</span>
  <span m="2433640">roughly</span> <span m="2433970">speaking,</span> <span m="2434950">when</span>
  <span m="2435230">you</span> <span m="2435380">have</span> <span m="2436010">addition</span>
  <span m="2436640">and</span> <span m="2436820">multiplication,</span> <span m="2438650">they're</span>
  <span m="2439090">are</span> <span m="2439190">kind</span> <span m="2439490">of</span>
  <span m="2439580">like</span> <span m="2439850">taking</span> <span m="2441230">slope</span>
  <span m="2442070">and</span> <span m="2442220">y-intercept</span> <span m="2443090">of</span>
  <span m="2443210">an</span> <span m="2443330">equation</span> <span m="2443780">of</span>
  <span m="2443870">a</span> <span m="2443930">line.</span> <span m="2445020">So</span>
  <span m="2445040">there</span> <span m="2445160">are</span> <span m="2445220">two</span>
  <span m="2445550">operations</span> <span m="2446240">that</span> <span m="2446390">are</span>
  <span m="2446480">involved.</span> <span m="2447500">So</span> <span m="2448950">turns
  out,</span> <span m="2449360">many</span> <span m="2449660">incidence</span> <span
  m="2450080">geometry</span> <span m="2450440">problems</span> <span m="2451220">can</span>
  <span m="2451490">be</span> <span m="2452090">set</span> <span m="2452480">up</span>
  <span m="2452660">and</span> <span m="2452790">a</span> <span m="2452840">way--</span>
  <span m="2453830">so</span> <span m="2453980">many</span> <span m="2454220">sum</span>
  <span m="2454430">product</span> <span m="2454730">problems</span> <span m="2455090">can</span>
  <span m="2455240">be</span> <span m="2455300">set</span> <span m="2455510">up</span>
  <span m="2455630">in</span> <span m="2455720">a</span> <span m="2455750">way</span>
  <span m="2455930">that</span> <span m="2456230">involves</span> <span m="2456740">incidence</span>
  <span m="2457190">geometry.</span></p><p><span m="2458800">And</span> <span m="2458990">a</span>
  <span m="2459140">very</span> <span m="2460310">short</span> <span m="2461030">and</span>
  <span m="2461630">clever</span> <span m="2462440">lower</span> <span m="2462730">bound</span>
  <span m="2463400">to</span> <span m="2463610">the</span> <span m="2463730">sum</span>
  <span m="2464000">product</span> <span m="2464330">problem</span> <span m="2465020">was</span>
  <span m="2465380">proved</span> <span m="2465770">by</span> <span m="2466130">Elekes</span>
  <span m="2469340">in</span> <span m="2469580">the</span> <span m="2469700">late</span>
  <span m="2470000">'90s.</span> <span m="2478930">So</span> <span m="2479060">he</span>
  <span m="2479210">showed</span> <span m="2479840">the</span> <span m="2479960">bound</span>
  <span m="2480440">that</span> <span m="2482480">if</span> <span m="2482690">you</span>
  <span m="2482870">have</span> <span m="2484250">a</span> <span m="2484550">subset</span>
  <span m="2485070">of</span> <span m="2485170">finite,</span> <span m="2485470">subset</span>
  <span m="2485930">of</span> <span m="2486050">reals,</span> <span m="2486980">then</span>
  <span m="2487280">the</span> <span m="2488000">sum</span> <span m="2488570">set</span>
  <span m="2489170">size</span> <span m="2490210">times</span> <span m="2491080">the</span>
  <span m="2491180">product</span> <span m="2491650">set</span> <span m="2491870">size</span>
  <span m="2492680">is</span> <span m="2492920">at</span> <span m="2493040">least</span>
  <span m="2494000">A</span> <span m="2494290">to</span> <span m="2494480">the</span>
  <span m="2495410">5/2.</span> <span m="2499150">As</span> <span m="2499300">a</span>
  <span m="2499360">corollary,</span> <span m="2501100">one</span> <span m="2501340">of</span>
  <span m="2501430">these</span> <span m="2501640">two</span> <span m="2502270">must</span>
  <span m="2503380">be</span> <span m="2503650">fairly</span> <span m="2504100">large.</span>
  <span m="2506995">The</span> <span m="2507490">max</span> <span m="2508990">of</span>
  <span m="2509130">the</span> <span m="2509360">sum</span> <span m="2509700">set</span>
  <span m="2510040">size</span> <span m="2511090">and</span> <span m="2511210">the</span>
  <span m="2511270">product</span> <span m="2511660">set</span> <span m="2511900">size</span>
  <span m="2513560">is</span> <span m="2514270">at</span> <span m="2514390">least</span>
  <span m="2515740">a</span> <span m="2516010">to</span> <span m="2516220">the</span>
  <span m="2517240">5/4.</span></p><p><span m="2526030">Let</span> <span m="2526120">me</span>
  <span m="2526210">show</span> <span m="2526330">you</span> <span m="2526390">the</span>
  <span m="2526480">proof.</span> <span m="2527440">I'm</span> <span m="2527620">going</span>
  <span m="2527830">to</span> <span m="2527920">construct</span> <span m="2528580">a</span>
  <span m="2528640">set</span> <span m="2528880">of</span> <span m="2528970">points</span>
  <span m="2529360">and</span> <span m="2529480">a</span> <span m="2529540">set</span>
  <span m="2529720">of</span> <span m="2529840">lines</span> <span m="2531040">based</span>
  <span m="2531400">on</span> <span m="2531490">the</span> <span m="2531580">set</span>
  <span m="2531850">A.</span> <span m="2532944">And</span> <span m="2533386">the</span>
  <span m="2533830">set</span> <span m="2534070">of</span> <span m="2534130">points</span>
  <span m="2535240">in</span> <span m="2535540">R2</span> <span m="2536490">is</span>
  <span m="2536740">going</span> <span m="2536950">to</span> <span m="2537040">be</span>
  <span m="2539140">pairs</span> <span m="2539680">x</span> <span m="2539920">comma</span>
  <span m="2540020">y,</span> <span m="2540970">where</span> <span m="2541180">the</span>
  <span m="2541750">horizontal</span> <span m="2542290">coordinate</span> <span m="2542700">lies</span>
  <span m="2542940">in</span> <span m="2543430">the</span> <span m="2543550">sum</span>
  <span m="2543840">set,</span> <span m="2544150">A</span> <span m="2544270">plus</span>
  <span m="2544600">A,</span> <span m="2544840">and</span> <span m="2545500">the</span>
  <span m="2545800">vertical</span> <span m="2546220">coordinate</span> <span m="2546740">lies</span>
  <span m="2547040">in</span> <span m="2547240">the</span> <span m="2547360">product</span>
  <span m="2547860">set,</span> <span m="2548110">A</span> <span m="2548230">times</span>
  <span m="2548570">A.</span> <span m="2555730">And</span> <span m="2555850">a</span>
  <span m="2555910">set</span> <span m="2556090">of</span> <span m="2556180">lines</span>
  <span m="2558140">is</span> <span m="2558220">going</span> <span m="2558460">to</span>
  <span m="2558550">be</span> <span m="2559360">these</span> <span m="2559600">lines--</span>
  <span m="2560350">y</span> <span m="2560800">equals</span> <span m="2561220">to</span>
  <span m="2561550">a</span> <span m="2562030">times</span> <span m="2566170">x</span>
  <span m="2566470">minus</span> <span m="2569170">a</span> <span m="2569320">prime,</span>
  <span m="2570130">where</span> <span m="2570580">a</span> <span m="2570790">and</span>
  <span m="2571210">a</span> <span m="2571330">prime</span> <span m="2572350">lie</span>
  <span m="2573090">in</span> <span m="2573540">A.</span></p><p><span m="2576810">So</span>
  <span m="2576960">these</span> <span m="2577140">are</span> <span m="2577200">some</span>
  <span m="2577380">points</span> <span m="2578100">and</span> <span m="2578220">some</span>
  <span m="2578430">lines.</span> <span m="2580840">And</span> <span m="2581830">I</span>
  <span m="2581920">want</span> <span m="2582040">to</span> <span m="2582100">show</span>
  <span m="2582250">you</span> <span m="2582370">that</span> <span m="2582700">they</span>
  <span m="2583030">must</span> <span m="2583330">have</span> <span m="2584800">many</span>
  <span m="2585040">incidences.</span> <span m="2587270">So</span> <span m="2587290">what</span>
  <span m="2587440">are</span> <span m="2587530">the</span> <span m="2587620">incidences?</span></p><p><span
  m="2589180">So</span> <span m="2589280">note</span> <span m="2589510">that</span>
  <span m="2589750">the</span> <span m="2589870">line</span> <span m="2591370">y</span>
  <span m="2592430">equals</span> <span m="2592930">to</span> <span m="2593200">a</span>
  <span m="2594130">times</span> <span m="2594670">x</span> <span m="2594940">minus</span>
  <span m="2595630">a</span> <span m="2595750">prime--</span> <span m="2597080">it</span>
  <span m="2597170">contains</span> <span m="2600250">the</span> <span m="2600400">points</span>
  <span m="2602890">a</span> <span m="2603370">prime</span> <span m="2603830">plus</span>
  <span m="2604330">b</span> <span m="2605130">and</span> <span m="2605530">ab,</span>
  <span m="2607510">which</span> <span m="2607810">lies</span> <span m="2608170">in</span>
  <span m="2608290">P</span> <span m="2609280">for</span> <span m="2609520">all</span>
  <span m="2610420">b</span> <span m="2611500">in</span> <span m="2611890">A.</span>
  <span m="2613630">You</span> <span m="2613730">plug</span> <span m="2613970">it</span>
  <span m="2614060">in.</span> <span m="2614230">If you</span> <span m="2614360">plug</span>
  <span m="2614600">in</span> <span m="2615440">a</span> <span m="2615560">prime</span>
  <span m="2616010">plus</span> <span m="2616310">b</span> <span m="2616850">into</span>
  <span m="2617060">here,</span> <span m="2617540">you</span> <span m="2617630">get</span>
  <span m="2618080">ab.</span> <span m="2619743">And</span> <span m="2621510">this</span>
  <span m="2621690">point</span> <span m="2622250">lies</span> <span m="2622630">in
  P,</span> <span m="2623010">because</span> <span m="2623400">the</span> <span m="2623580">first</span>
  <span m="2623910">coordinate</span> <span m="2624300">is</span> <span m="2624980">the</span>
  <span m="2625050">sum</span> <span m="2625300">set.</span></p><p><span m="2625920">The</span>
  <span m="2625980">second</span> <span m="2626340">coordinate</span> <span m="2626900">lies
  in</span> <span m="2627330">the</span> <span m="2627420">product</span> <span m="2627780">set.</span>
  <span m="2629550">So</span> <span m="2631400">each</span> <span m="2631620">line</span>
  <span m="2631905">in</span> <span m="2632190">L</span> <span m="2634250">contains</span>
  <span m="2636140">many</span> <span m="2636470">incidences.</span> <span m="2637570">So</span>
  <span m="2637670">each</span> <span m="2637870">line in</span> <span m="2638320">L</span>
  <span m="2638810">contains</span> <span m="2640290">a</span> <span m="2640640">incidents.</span>
  <span m="2641960">So</span> <span m="2642290">this</span> <span m="2642470">line,</span>
  <span m="2645630">each</span> <span m="2645840">line</span> <span m="2646170">in</span>
  <span m="2646410">L</span> <span m="2649410">contains</span> <span m="2651120">a</span>
  <span m="2654940">incidences.</span></p><p><span m="2657610">Also,</span> <span
  m="2658390">we</span> <span m="2659170">can</span> <span m="2659350">easily</span>
  <span m="2659710">compute</span> <span m="2660790">the</span> <span m="2662440">number</span>
  <span m="2662800">of</span> <span m="2662920">lines</span> <span m="2663490">and</span>
  <span m="2663580">the</span> <span m="2663640">number</span> <span m="2663940">of</span>
  <span m="2664030">points.</span> <span m="2666490">The</span> <span m="2666820">number</span>
  <span m="2667150">of</span> <span m="2667420">points</span> <span m="2668020">is</span>
  <span m="2669220">A</span> <span m="2669430">plus</span> <span m="2669820">A</span>
  <span m="2670330">size</span> <span m="2670870">times</span> <span m="2671780">the</span>
  <span m="2672010">size</span> <span m="2672370">of</span> <span m="2672490">A</span>
  <span m="2672610">times</span> <span m="2672880">A.</span> <span m="2674060">And</span>
  <span m="2674200">the</span> <span m="2674260">number</span> <span m="2674770">of</span>
  <span m="2675280">lines</span> <span m="2676540">is</span> <span m="2676840">just</span>
  <span m="2677470">the</span> <span m="2677560">size</span> <span m="2677980">of</span>
  <span m="2678100">A</span> <span m="2678550">squared.</span></p><p><span m="2681100">So</span>
  <span m="2681310">by</span> <span m="2681520">Szemeredi-Trotter,</span> <span m="2685110">we</span>
  <span m="2685830">find</span> <span m="2686250">that</span> <span m="2686550">the</span>
  <span m="2687210">number</span> <span m="2687630">of</span> <span m="2687890">incidences</span>
  <span m="2692541">is</span> <span m="2693010">lower</span> <span m="2693370">bounded</span>
  <span m="2694240">by</span> <span m="2696840">noting</span> <span m="2697620">this</span>
  <span m="2697800">fact here.</span> <span m="2698250">We</span> <span m="2698370">have</span>
  <span m="2698520">many</span> <span m="2698820">incidences.</span> <span m="2699880">So</span>
  <span m="2700350">the</span> <span m="2700500">number</span> <span m="2700980">of</span>
  <span m="2701130">lines,</span> <span m="2701860">each</span> <span m="2702000">line</span>
  <span m="2702600">contributes</span> <span m="2704210">a</span> <span m="2704990">incidences.</span></p><p><span
  m="2707120">But</span> <span m="2707210">we</span> <span m="2707390">also</span>
  <span m="2707660">have</span> <span m="2707900">an</span> <span m="2708050">upper</span>
  <span m="2708260">bound</span> <span m="2708770">coming</span> <span m="2709100">from</span>
  <span m="2709430">the</span> <span m="2709550">Szemeredi-Trotter</span> <span m="2710420">theorem.</span>
  <span m="2711496">So</span> <span m="2711860">plugging</span> <span m="2712250">in</span>
  <span m="2712430">the</span> <span m="2712670">upper</span> <span m="2712880">bound,</span>
  <span m="2713720">we</span> <span m="2713840">find</span> <span m="2714320">that</span>
  <span m="2716420">you</span> <span m="2716570">have--</span> <span m="2718100">so</span>
  <span m="2718130">now</span> <span m="2718340">I'm</span> <span m="2718430">just</span>
  <span m="2719180">directly</span> <span m="2719660">plugging</span> <span m="2720080">in</span>
  <span m="2720680">the</span> <span m="2720780">statement</span> <span m="2721250">of</span>
  <span m="2721490">Szemeredi-Trotter.</span> <span m="2726460">The</span> <span m="2726550">main</span>
  <span m="2726820">term</span> <span m="2727150">is</span> <span m="2727330">the</span>
  <span m="2727720">first</span> <span m="2728020">term.</span> <span m="2728470">You</span>
  <span m="2728560">should</span> <span m="2728710">still</span> <span m="2728950">check</span>
  <span m="2729250">the</span> <span m="2729340">latter</span> <span m="2729640">two</span>
  <span m="2729820">terms,</span> <span m="2730150">but</span> <span m="2730250">the</span>
  <span m="2730330">main</span> <span m="2730490">term</span> <span m="2730750">is</span>
  <span m="2730870">the</span> <span m="2730960">first</span> <span m="2731200">term.</span></p><p><span
  m="2734190">So</span> <span m="2734890">plugging</span> <span m="2735370">in</span>
  <span m="2735910">the</span> <span m="2736060">values</span> <span m="2737380">for</span>
  <span m="2737770">P</span> <span m="2738250">and</span> <span m="2738730">L,</span>
  <span m="2739540">we</span> <span m="2739720">find</span> <span m="2752640">this</span>
  <span m="2752790">is</span> <span m="2752880">the</span> <span m="2752970">case,</span>
  <span m="2753450">plus</span> <span m="2754110">some</span> <span m="2754470">additional</span>
  <span m="2754920">terms,</span> <span m="2755790">which</span> <span m="2755940">you</span>
  <span m="2756030">can</span> <span m="2756180">check</span> <span m="2756510">are</span>
  <span m="2756690">dominated</span> <span m="2757230">by</span> <span m="2757350">the</span>
  <span m="2757440">first</span> <span m="2757740">term.</span> <span m="2758910">So</span>
  <span m="2759030">let</span> <span m="2759120">me</span> <span m="2759210">just</span>
  <span m="2759390">do</span> <span m="2759660">a</span> <span m="2759900">big</span>
  <span m="2760140">O</span> <span m="2760440">over</span> <span m="2760650">there.</span>
  <span m="2763530">Now</span> <span m="2763840">you</span> <span m="2764440">put</span>
  <span m="2765430">left</span> <span m="2765700">and</span> <span m="2765790">right</span>
  <span m="2765980">together,</span> <span m="2766810">and</span> <span m="2767140">we</span>
  <span m="2767320">could</span> <span m="2767650">obtain</span> <span m="2768040">some</span>
  <span m="2768280">lower</span> <span m="2768520">bound</span> <span m="2771070">on</span>
  <span m="2771340">the</span> <span m="2771490">product</span> <span m="2772090">of</span>
  <span m="2772960">the</span> <span m="2773050">sizes</span> <span m="2773530">of</span>
  <span m="2773600">the</span> <span m="2773650">sum</span> <span m="2773920">set</span>
  <span m="2774550">and</span> <span m="2774640">the</span> <span m="2774700">product</span>
  <span m="2775090">set,</span> <span m="2776020">thereby</span> <span m="2776380">yielding</span>
  <span m="2777520">allocations.</span></p><p><span m="2783710">So</span> <span m="2783830">this</span>
  <span m="2784010">is</span> <span m="2784100">some</span> <span m="2784400">lower</span>
  <span m="2784640">bound</span> <span m="2784910">on the</span> <span m="2785040">sum</span>
  <span m="2785300">product</span> <span m="2785660">problem.</span> <span m="2786460">And
  you</span> <span m="2786740">see,</span> <span m="2786890">we</span> <span m="2787130">went</span>
  <span m="2787370">through</span> <span m="2789130">the</span> <span m="2789230">crossing</span>
  <span m="2789620">number</span> <span m="2789840">inequality</span> <span m="2790400">to</span>
  <span m="2790520">prove</span> <span m="2791270">Szemeredi-Trotter,</span> <span
  m="2791975">a</span> <span m="2792230">basic</span> <span m="2792620">result</span>
  <span m="2792875">in</span> <span m="2793130">incidence</span> <span m="2793490">geometry.</span>
  <span m="2794480">And</span> <span m="2794690">viewing</span> <span m="2796070">sum</span>
  <span m="2796310">product</span> <span m="2797450">as an</span> <span m="2797870">incidence</span>
  <span m="2798260">geometry</span> <span m="2798740">problem,</span> <span m="2799370">one</span>
  <span m="2799580">can</span> <span m="2799760">obtain</span> <span m="2800390">this</span>
  <span m="2800670">lower bound</span> <span m="2801130">over</span> <span m="2801330">here.</span>
  <span m="2803850">Any</span> <span m="2804030">questions?</span></p><p><span m="2807950">I</span>
  <span m="2808040">want</span> <span m="2808150">to</span> <span m="2808250">show</span>
  <span m="2808430">you</span> <span m="2808700">a</span> <span m="2809360">different</span>
  <span m="2810110">proof</span> <span m="2810740">that</span> <span m="2810860">was</span>
  <span m="2811040">found</span> <span m="2811280">later,</span> <span m="2811640">that</span>
  <span m="2811790">gives</span> <span m="2812450">an</span> <span m="2812570">improvement.</span>
  <span m="2814550">And</span> <span m="2816060">there's</span> <span m="2816130">a</span>
  <span m="2816460">question,</span> <span m="2816740">can</span> <span m="2816890">you</span>
  <span m="2817040">do</span> <span m="2817790">better</span> <span m="2818160">than</span>
  <span m="2819980">5/4?</span> <span m="2821670">So</span> <span m="2821840">it</span>
  <span m="2821900">turns</span> <span m="2822200">out</span> <span m="2822830">that</span>
  <span m="2822980">there</span> <span m="2823100">was</span> <span m="2823280">a</span>
  <span m="2823340">very</span> <span m="2823550">nice</span> <span m="2823820">result</span>
  <span m="2824270">of</span> <span m="2824480">Solymosi</span> <span m="2826490">sometime</span>
  <span m="2826880">later</span> <span m="2827510">that</span> <span m="2827960">gives</span>
  <span m="2828290">you</span> <span m="2828680">an</span> <span m="2828800">improvement.</span></p><p><span
  m="2836210">Solymosi</span> <span m="2836790">proved</span> <span m="2837800">in</span>
  <span m="2837890">2009</span> <span m="2839090">that</span> <span m="2840260">if</span>
  <span m="2841070">A</span> <span m="2841730">is</span> <span m="2841940">a</span>
  <span m="2842030">subset</span> <span m="2842630">of</span> <span m="2843230">positive</span>
  <span m="2843770">reals,</span> <span m="2844760">then</span> <span m="2846320">the</span>
  <span m="2846440">size</span> <span m="2846860">of</span> <span m="2847700">A</span>
  <span m="2848780">times</span> <span m="2849030">A</span> <span m="2850280">multiplied</span>
  <span m="2850730">by</span> <span m="2850850">the</span> <span m="2850940">size</span>
  <span m="2851270">of</span> <span m="2851390">A</span> <span m="2851510">plus</span>
  <span m="2851810">A</span> <span m="2851930">squared</span> <span m="2853070">is</span>
  <span m="2853250">at</span> <span m="2853340">least</span> <span m="2854960">size</span>
  <span m="2855440">of</span> <span m="2855680">A</span> <span m="2855950">to</span>
  <span m="2856130">the</span> <span m="2856220">4th</span> <span m="2857120">divided</span>
  <span m="2857540">by</span> <span m="2858200">4</span> <span m="2859070">ceiling</span>
  <span m="2860750">log</span> <span m="2861530">of</span> <span m="2862160">the</span>
  <span m="2862250">size</span> <span m="2862730">of</span> <span m="2863280">A,</span>
  <span m="2863620">where</span> <span m="2863810">the</span> <span m="2863930">log</span>
  <span m="2864290">is</span> <span m="2864440">base</span> <span m="2864850">2.</span>
  <span m="2865610">So</span> <span m="2866280">don't</span> <span m="2866750">worry</span>
  <span m="2866910">about</span> <span m="2867050">the</span> <span m="2867140">specific</span>
  <span m="2867620">constants.</span></p><p><span m="2871240">A</span> <span m="2871520">being</span>
  <span m="2872360">in</span> <span m="2872450">the</span> <span m="2872510">positive</span>
  <span m="2872870">reals</span> <span m="2873275">is</span> <span m="2874010">no</span>
  <span m="2874160">big</span> <span m="2874340">deal,</span> <span m="2874640">because</span>
  <span m="2874970">you</span> <span m="2875030">can</span> <span m="2875810">always</span>
  <span m="2876020">separate</span> <span m="2876560">A</span> <span m="2876830">as</span>
  <span m="2877280">positive</span> <span m="2877790">and</span> <span m="2877880">negative</span>
  <span m="2878630">and</span> <span m="2878840">analyze</span> <span m="2879290">each</span>
  <span m="2879470">part</span> <span m="2879740">separately.</span> <span m="2880790">So</span>
  <span m="2881030">as</span> <span m="2881150">a</span> <span m="2881210">corollary</span>
  <span m="2883100">to</span> <span m="2884000">Solymosi's</span> <span m="2884610">theorem,</span>
  <span m="2885260">we</span> <span m="2885440">obtain</span> <span m="2886100">that</span>
  <span m="2887600">for</span> <span m="2888110">A,</span> <span m="2888460">a</span>
  <span m="2888860">subset</span> <span m="2889370">of</span> <span m="2889460">the</span>
  <span m="2889550">reals,</span> <span m="2891050">the</span> <span m="2892400">sum</span>
  <span m="2892730">set</span> <span m="2895460">and</span> <span m="2895580">the</span>
  <span m="2895670">product</span> <span m="2896080">set,</span> <span m="2896300">at</span>
  <span m="2896470">least</span> <span m="2896660">one</span> <span m="2896900">of</span>
  <span m="2896990">them</span> <span m="2897110">must</span> <span m="2897560">have</span>
  <span m="2897710">size</span> <span m="2898730">at</span> <span m="2898850">least</span>
  <span m="2901300">A</span> <span m="2902230">raised</span> <span m="2902560">to</span>
  <span m="2904000">4/3</span> <span m="2904990">divided</span> <span m="2905380">by</span>
  <span m="2906580">2</span> <span m="2907690">times</span> <span m="2910020">log</span>
  <span m="2910380">base</span> <span m="2910620">2</span> <span m="2911010">size</span>
  <span m="2911370">of</span> <span m="2911460">A</span> <span m="2912060">raised</span>
  <span m="2912360">to</span> <span m="2913410">1/3</span> <span m="2913660">third.</span>
  <span m="2914820">So</span> <span m="2915630">basically,</span> <span m="2916070">A</span>
  <span m="2916220">to</span> <span m="2916340">the</span> <span m="2916560">4/3</span>
  <span m="2917340">minus</span> <span m="2917860">little</span> <span m="2918060">one</span>
  <span m="2918690">in</span> <span m="2918810">the</span> <span m="2918930">exponent,</span>
  <span m="2922210">so</span> <span m="2922410">better</span> <span m="2922620">than</span>
  <span m="2922770">before.</span> <span m="2923370">And</span> <span m="2923670">this</span>
  <span m="2923850">is</span> <span m="2923970">a</span> <span m="2924030">new</span>
  <span m="2924180">bound.</span></p><p><span m="2927580">I</span> <span m="2927670">want</span>
  <span m="2927820">to</span> <span m="2927910">note</span> <span m="2928240">that</span>
  <span m="2930010">in</span> <span m="2930400">this</span> <span m="2930700">formulation,</span>
  <span m="2931810">where</span> <span m="2932200">we</span> <span m="2932400">are</span>
  <span m="2932470">looking</span> <span m="2932860">at</span> <span m="2934260">lower</span>
  <span m="2934540">bounding</span> <span m="2935080">this</span> <span m="2935320">quantity</span>
  <span m="2935800">over</span> <span m="2936010">here,</span> <span m="2938320">this</span>
  <span m="2938560">is</span> <span m="2938680">tied</span> <span m="2939910">up</span>
  <span m="2940060">to</span> <span m="2940300">logarithmic</span> <span m="2940930">factors,</span>
  <span m="2946160">by</span> <span m="2946340">considering</span> <span m="2947180">A</span>
  <span m="2947480">to</span> <span m="2947630">be</span> <span m="2949640">just</span>
  <span m="2949970">the</span> <span m="2950180">interval</span> <span m="2950660">from</span>
  <span m="2950870">1</span> <span m="2951080">to n.</span> <span m="2951710">If</span>
  <span m="2952260">A</span> <span m="2952490">is</span> <span m="2952670">the</span>
  <span m="2952760">interval</span> <span m="2953150">from</span> <span m="2953330">1</span>
  <span m="2953480">to</span> <span m="2953630">n,</span> <span m="2954140">then</span>
  <span m="2954320">the</span> <span m="2954380">left-hand</span> <span m="2954770">side,</span>
  <span m="2955460">A</span> <span m="2955580">plus</span> <span m="2955850">A,</span>
  <span m="2956120">is</span> <span m="2956390">around</span> <span m="2956660">size</span>
  <span m="2957020">n.</span> <span m="2957230">So</span> <span m="2957440">you</span>
  <span m="2957560">have</span> <span m="2957760">n</span> <span m="2957920">squared.</span>
  <span m="2958660">And</span> <span m="2958860">A</span> <span m="2958990">times</span>
  <span m="2959260">A</span> <span m="2959410">is</span> <span m="2959510">also,</span>
  <span m="2959840">I</span> <span m="2959900">mentioned,</span> <span m="2960260">around</span>
  <span m="2960680">size</span> <span m="2961130">n</span> <span m="2961310">squared.</span>
  <span m="2963800">So</span> <span m="2964070">this</span> <span m="2964280">inequality</span>
  <span m="2964790">here</span> <span m="2965300">is</span> <span m="2965450">tight.</span>
  <span m="2966170">The</span> <span m="2966290">consequence</span> <span m="2966890">is</span>
  <span m="2967010">not</span> <span m="2967280">tight,</span> <span m="2967930">but</span>
  <span m="2968030">the</span> <span m="2968120">first</span> <span m="2968390">inequality</span>
  <span m="2968870">is</span> <span m="2969020">tight.</span></p><p><span m="2974400">So</span>
  <span m="2974550">in the</span> <span m="2974670">remainder</span> <span m="2975150">of</span>
  <span m="2975330">today's</span> <span m="2975660">lecture,</span> <span m="2976260">I</span>
  <span m="2976320">want</span> <span m="2976470">to</span> <span m="2976530">show</span>
  <span m="2976740">you</span> <span m="2976920">how</span> <span m="2977160">to</span>
  <span m="2977250">prove</span> <span m="2977760">Solymosi's</span> <span m="2978430">lower</span>
  <span m="2978690">bound.</span> <span m="2979960">And</span> <span m="2980610">it</span>
  <span m="2980730">has</span> <span m="2980940">some</span> <span m="2981210">similarities</span>
  <span m="2982140">to</span> <span m="2983220">the</span> <span m="2983340">one</span>
  <span m="2983550">that</span> <span m="2983670">we've</span> <span m="2983880">seen,</span>
  <span m="2984810">because</span> <span m="2985350">it</span> <span m="2985710">also</span>
  <span m="2986160">looks</span> <span m="2986520">at</span> <span m="2987030">some</span>
  <span m="2987360">geometric</span> <span m="2989520">aspects</span> <span m="2990210">of</span>
  <span m="2990340">the</span> <span m="2990440">sum</span> <span m="2990690">product</span>
  <span m="2991080">problem.</span> <span m="2992610">But</span> <span m="2993170">it</span>
  <span m="2993270">doesn't</span> <span m="2993540">use</span> <span m="2994650">the</span>
  <span m="2994830">exact</span> <span m="2995250">tools</span> <span m="2995610">that</span>
  <span m="2995760">we've</span> <span m="2995910">seen</span> <span m="2996240">earlier.</span></p><p><span
  m="2997950">It</span> <span m="2998040">does</span> <span m="2998250">use</span>
  <span m="2998400">some</span> <span m="2998610">tools</span> <span m="2999630">that</span>
  <span m="2999780">were</span> <span m="2999900">related</span> <span m="3000590">to</span>
  <span m="3001490">the</span> <span m="3001610">lecture</span> <span m="3002000">from</span>
  <span m="3003320">Monday.</span> <span m="3004520">So</span> <span m="3004640">last</span>
  <span m="3004880">time,</span> <span m="3005150">we</span> <span m="3005690">discussed</span>
  <span m="3006560">this</span> <span m="3006830">thing</span> <span m="3007070">called</span>
  <span m="3007250">the</span> <span m="3007460">&quot;additive</span> <span m="3007910">energy.&quot;</span>
  <span m="3009830">You</span> <span m="3009920">can</span> <span m="3010070">come</span>
  <span m="3010250">up</span> <span m="3010370">with</span> <span m="3010490">a</span>
  <span m="3010550">similar</span> <span m="3010940">notion</span> <span m="3011330">for</span>
  <span m="3011600">the</span> <span m="3011690">multiplication</span> <span m="3012560">operation,</span>
  <span m="3013400">so</span> <span m="3013490">the</span> <span m="3013580">&quot;multiplicative</span>
  <span m="3014270">energy,&quot;</span> <span m="3024220">which</span> <span m="3024400">we'll</span>
  <span m="3024610">denote</span> <span m="3025090">by</span> <span m="3025580">E</span>
  <span m="3027060">sub,</span> <span m="3027890">with</span> <span m="3028140">the</span>
  <span m="3029140">multiplication</span> <span m="3029770">symbol,</span> <span m="3031426">A.</span>
  <span m="3031840">So</span> <span m="3031990">the</span> <span m="3032080">multiplicative</span>
  <span m="3033550">energy</span> <span m="3034150">is</span> <span m="3034330">like
  the</span> <span m="3034720">additive</span> <span m="3035080">energy,</span> <span
  m="3035650">except</span> <span m="3036070">that</span> <span m="3036700">instead</span>
  <span m="3037000">of</span> <span m="3037090">doing</span> <span m="3037450">addition,</span>
  <span m="3038030">we're</span> <span m="3038110">going</span> <span m="3038210">to</span>
  <span m="3038320">do</span> <span m="3038510">a</span> <span m="3038550">multiplication</span>
  <span m="3039220">instead.</span></p><p><span m="3039820">So</span> <span m="3040000">one</span>
  <span m="3040180">way</span> <span m="3040300">to</span> <span m="3040390">define</span>
  <span m="3040750">it</span> <span m="3041170">is</span> <span m="3041410">the</span>
  <span m="3041500">number</span> <span m="3041860">of</span> <span m="3041980">quadruples</span>
  <span m="3045320">such</span> <span m="3045650">that</span> <span m="3046190">there</span>
  <span m="3046370">exists</span> <span m="3047750">some</span> <span m="3050270">real</span>
  <span m="3050830">lambda</span> <span m="3051860">such</span> <span m="3052220">that</span>
  <span m="3054840">a,</span> <span m="3055230">comma,</span> <span m="3055530">b</span>
  <span m="3056100">equals</span> <span m="3056490">to</span> <span m="3056670">lambda</span>
  <span m="3057540">c,</span> <span m="3057990">comma,</span> <span m="3058200">d.</span>
  <span m="3066400">So</span> <span m="3066770">basically</span> <span m="3067130">the</span>
  <span m="3067220">same</span> <span m="3067490">as</span> <span m="3067670">additive</span>
  <span m="3067970">energy,</span> <span m="3068540">except</span> <span m="3068870">that</span>
  <span m="3069440">we're</span> <span m="3069590">using</span> <span m="3069920">multiplications</span>
  <span m="3070760">instead.</span> <span m="3072530">By</span> <span m="3072950">the</span>
  <span m="3073160">Cauchy-Schwartz</span> <span m="3073500">inequality--</span> <span
  m="3075330">and</span> <span m="3075350">this</span> <span m="3075530">is</span>
  <span m="3078050">a</span> <span m="3078110">calculation</span> <span m="3078680">we</span>
  <span m="3078830">saw</span> <span m="3079100">last</span> <span m="3079400">time,</span>
  <span m="3079610">as</span> <span m="3079760">well--</span> <span m="3080980">we</span>
  <span m="3081110">see</span> <span m="3081350">that</span> <span m="3082520">if</span>
  <span m="3082760">you</span> <span m="3082910">have</span> <span m="3083180">a</span>
  <span m="3083210">set</span> <span m="3084050">with</span> <span m="3084470">small</span>
  <span m="3085280">product,</span> <span m="3087010">then</span> <span m="3087440">it</span>
  <span m="3087580">must</span> <span m="3087850">have</span> <span m="3087970">high</span>
  <span m="3088510">multiplicative</span> <span m="3089260">energy.</span></p><p><span
  m="3090280">So</span> <span m="3090460">last</span> <span m="3090640">time,</span>
  <span m="3090790">we</span> <span m="3090890">saw</span> <span m="3091510">small</span>
  <span m="3091840">sum set</span> <span m="3092680">implies</span> <span m="3093160">high</span>
  <span m="3093700">additive</span> <span m="3094030">energy.</span> <span m="3094570">Likewise,</span>
  <span m="3095260">small</span> <span m="3096490">product</span> <span m="3096890">set</span>
  <span m="3097130">implies</span> <span m="3097630">high</span> <span m="3097930">multiplicative</span>
  <span m="3098560">energy.</span> <span m="3099570">In</span> <span m="3099910">particular,</span>
  <span m="3101140">the</span> <span m="3101680">multiplicative</span> <span m="3102250">energy</span>
  <span m="3102610">of</span> <span m="3102760">A,</span> <span m="3103690">you</span>
  <span m="3103780">can</span> <span m="3103960">rewrite</span> <span m="3104410">it</span>
  <span m="3104740">as</span> <span m="3105880">sum</span> <span m="3107050">over</span>
  <span m="3108460">all</span> <span m="3109990">elements</span> <span m="3110440">x</span>
  <span m="3110800">in</span> <span m="3110950">the</span> <span m="3111070">product</span>
  <span m="3111430">set</span> <span m="3112870">of</span> <span m="3114040">the</span>
  <span m="3114130">quantity,</span> <span m="3114700">which</span> <span m="3115360">tells</span>
  <span m="3115630">you</span> <span m="3115750">the</span> <span m="3115870">number</span>
  <span m="3116260">of</span> <span m="3116380">ways</span> <span m="3116800">to</span>
  <span m="3116980">write</span> <span m="3117490">x</span> <span m="3118240">as</span>
  <span m="3118450">a</span> <span m="3118510">product,</span> <span m="3122730">this</span>
  <span m="3122920">number</span> <span m="3123160">squared</span> <span m="3123950">and</span>
  <span m="3123980">then</span> <span m="3124130">summed</span> <span m="3124420">over
  all</span> <span m="3124870">x.</span></p><p><span m="3125860">By</span> <span m="3126030">Cauchy-Schwartz,</span>
  <span m="3127180">we</span> <span m="3127330">find</span> <span m="3127690">that</span>
  <span m="3127930">this</span> <span m="3128140">quantity</span> <span m="3128560">here</span>
  <span m="3128830">is</span> <span m="3129020">lower</span> <span m="3129280">bounded</span>
  <span m="3129730">by</span> <span m="3130360">the</span> <span m="3130450">size</span>
  <span m="3130810">of</span> <span m="3130930">A</span> <span m="3131200">to the</span>
  <span m="3131290">4th</span> <span m="3132040">divided</span> <span m="3132430">by</span>
  <span m="3133000">the</span> <span m="3133090">size</span> <span m="3133510">of</span>
  <span m="3134680">A</span> <span m="3134800">times</span> <span m="3135170">A.</span>
  <span m="3138040">So</span> <span m="3138220">to</span> <span m="3138370">prove</span>
  <span m="3138650">Solymosi's</span> <span m="3139420">theorem,</span> <span m="3140200">we</span>
  <span m="3141640">are</span> <span m="3141760">going</span> <span m="3142000">to</span>
  <span m="3142150">actually</span> <span m="3142480">prove</span> <span m="3143140">a</span>
  <span m="3143260">bound</span> <span m="3144100">on</span> <span m="3144460">the</span>
  <span m="3145300">energy,</span> <span m="3146710">instead</span> <span m="3146980">of</span>
  <span m="3147040">proving</span> <span m="3147400">it</span> <span m="3147940">on</span>
  <span m="3148090">the</span> <span m="3148180">set.</span> <span m="3148680">We're
  going</span> <span m="3149050">to</span> <span m="3149230">prove</span> <span m="3149470">it</span>
  <span m="3149560">on</span> <span m="3149680">the</span> <span m="3149770">energy.</span></p><p><span
  m="3150460">So</span> <span m="3151260">it</span> <span m="3151360">suffices</span>
  <span m="3151900">to</span> <span m="3151990">show</span> <span m="3157200">that</span>
  <span m="3158250">the</span> <span m="3160260">multiplicative</span> <span m="3160950">energy</span>
  <span m="3161790">is</span> <span m="3162480">at</span> <span m="3162570">most</span>
  <span m="3163440">4</span> <span m="3164100">times</span> <span m="3165990">the</span>
  <span m="3167010">sum</span> <span m="3167340">set</span> <span m="3167910">size</span>
  <span m="3168990">times--</span> <span m="3169900">so</span> <span m="3170020">let</span>
  <span m="3170150">me</span> <span m="3171450">divide</span> <span m="3172050">the</span>
  <span m="3172410">energy</span> <span m="3172920">by</span> <span m="3175130">log</span>
  <span m="3175770">of</span> <span m="3175920">A.</span> <span m="3181832">So</span>
  <span m="3182303">when you</span> <span m="3182780">plug</span> <span m="3183050">this</span>
  <span m="3183320">into</span> <span m="3183560">this</span> <span m="3183710">inequality,</span>
  <span m="3184580">it</span> <span m="3184680">would</span> <span m="3184700">imply</span>
  <span m="3185150">that.</span></p><p><span m="3185520">So</span> <span m="3185670">it</span>
  <span m="3185800">remains</span> <span m="3186200">to</span> <span m="3186320">show</span>
  <span m="3188870">this</span> <span m="3189050">inequality</span> <span m="3189590">over</span>
  <span m="3189830">here</span> <span m="3190250">upper</span> <span m="3190430">bounding</span>
  <span m="3190970">the</span> <span m="3191120">multiplicative</span> <span m="3191780">energy.</span>
  <span m="3200730">There's</span> <span m="3200880">an</span> <span m="3200970">important</span>
  <span m="3201360">idea</span> <span m="3202500">that</span> <span m="3202620">we're</span>
  <span m="3202710">going</span> <span m="3202800">to</span> <span m="3202920">use</span>
  <span m="3203130">here,</span> <span m="3203400">which</span> <span m="3203610">is</span>
  <span m="3203700">also</span> <span m="3203910">pretty</span> <span m="3204120">common</span>
  <span m="3204470">in</span> <span m="3204630">analysis,</span> <span m="3205440">is</span>
  <span m="3205560">that</span> <span m="3205680">instead</span> <span m="3206040">of</span>
  <span m="3206130">considering</span> <span m="3207150">that</span> <span m="3208080">energy</span>
  <span m="3208470">sum</span> <span m="3209250">here,</span> <span m="3212850">we're</span>
  <span m="3213000">going</span> <span m="3213150">to</span> <span m="3213210">consider</span>
  <span m="3214880">a</span> <span m="3214950">similar</span> <span m="3215340">sum,</span>
  <span m="3215880">except</span> <span m="3216240">we're</span> <span m="3216360">going</span>
  <span m="3216430">to</span> <span m="3216570">chop</span> <span m="3216990">up</span>
  <span m="3217140">the</span> <span m="3217260">sum</span> <span m="3218070">into</span>
  <span m="3218730">pieces</span> <span m="3219690">according</span> <span m="3220110">to</span>
  <span m="3220410">how</span> <span m="3220800">big</span> <span m="3221460">the</span>
  <span m="3221580">terms</span> <span m="3222210">are,</span> <span m="3223760">so</span>
  <span m="3223940">that</span> <span m="3224120">we're</span> <span m="3224300">only</span>
  <span m="3224600">looking</span> <span m="3224990">at</span> <span m="3225140">contributions</span>
  <span m="3225860">of</span> <span m="3226070">comparable</span> <span m="3226610">size.</span>
  <span m="3228230">And</span> <span m="3228330">so</span> <span m="3228430">this</span>
  <span m="3228470">is</span> <span m="3228590">called</span> <span m="3228800">a</span>
  <span m="3229220">&quot;dyadic</span> <span m="3229820">decomposition.&quot;</span></p><p><span
  m="3242420">The</span> <span m="3242510">idea</span> <span m="3242810">is</span>
  <span m="3242990">that</span> <span m="3243680">we</span> <span m="3243860">can</span>
  <span m="3244070">write</span> <span m="3244490">the</span> <span m="3245330">multiplicative</span>
  <span m="3246050">energy</span> <span m="3247900">similar</span> <span m="3248140">to</span>
  <span m="3248410">above,</span> <span m="3248990">but</span> <span m="3249140">instead</span>
  <span m="3249500">of</span> <span m="3249680">summing</span> <span m="3250100">over</span>
  <span m="3250400">x</span> <span m="3250700">in</span> <span m="3250820">the</span>
  <span m="3250880">product</span> <span m="3251260">set,</span> <span m="3251750">let</span>
  <span m="3251870">me</span> <span m="3252110">sum</span> <span m="3252650">over</span>
  <span m="3253130">s</span> <span m="3253550">in</span> <span m="3253760">the</span>
  <span m="3254390">quotient</span> <span m="3254960">set.</span> <span m="3255590">So</span>
  <span m="3255740">you</span> <span m="3255860">can</span> <span m="3256250">interpret</span>
  <span m="3256670">what</span> <span m="3256850">this</span> <span m="3259760">quotient</span>
  <span m="3260210">A</span> <span m="3260730">is.</span> <span m="3261670">This</span>
  <span m="3261890">is</span> <span m="3262010">the</span> <span m="3262100">set</span>
  <span m="3262370">of</span> <span m="3262490">all</span> <span m="3263480">A</span>
  <span m="3263600">divided</span> <span m="3263960">by</span> <span m="3264110">B,</span>
  <span m="3264380">where</span> <span m="3264620">A and</span> <span m="3265130">B
  are</span> <span m="3265910">in A.</span> <span m="3266640">A</span> <span m="3267140">is</span>
  <span m="3267440">a</span> <span m="3267500">set</span> <span m="3267800">of</span>
  <span m="3267920">positive</span> <span m="3268265">reals,</span> <span m="3268710">so
  I</span> <span m="3268910">don't</span> <span m="3269060">need</span> <span m="3269150">to</span>
  <span m="3269240">worry</span> <span m="3269450">about</span> <span m="3269630">division</span>
  <span m="3269990">by</span> <span m="3270140">0.</span></p><p><span m="3271400">So</span>
  <span m="3272870">what</span> <span m="3273110">remains,</span> <span m="3273590">then,</span>
  <span m="3274010">is</span> <span m="3275840">the</span> <span m="3276080">intersection</span>
  <span m="3276770">of</span> <span m="3276950">s</span> <span m="3277190">times</span>
  <span m="3277610">A</span> <span m="3277940">and</span> <span m="3278426">A</span>
  <span m="3280370">squared.</span> <span m="3281700">Remember,</span> <span m="3282050">s</span>
  <span m="3282260">times</span> <span m="3282570">A</span> <span m="3282860">is</span>
  <span m="3283850">scaling</span> <span m="3284390">each</span> <span m="3284960">element</span>
  <span m="3285290">of</span> <span m="3285410">A</span> <span m="3285590">by</span>
  <span m="3285830">s.</span> <span m="3287170">So we</span> <span m="3287670">have</span>
  <span m="3288170">this</span> <span m="3288350">quantity</span> <span m="3288740">over</span>
  <span m="3288960">here.</span></p><p><span m="3289760">So</span> <span m="3290210">I</span>
  <span m="3290300">want</span> <span m="3290510">to</span> <span m="3290930">break</span>
  <span m="3291320">up</span> <span m="3291770">the</span> <span m="3291890">sum</span>
  <span m="3292850">into</span> <span m="3293360">a</span> <span m="3293450">bunch</span>
  <span m="3293750">of</span> <span m="3294530">smaller</span> <span m="3295070">sums,</span>
  <span m="3296060">where</span> <span m="3297430">I</span> <span m="3297530">want</span>
  <span m="3297680">to</span> <span m="3297740">break</span> <span m="3298010">up</span>
  <span m="3298130">the</span> <span m="3298250">sum</span> <span m="3299540">according</span>
  <span m="3299990">to</span> <span m="3300140">how</span> <span m="3300410">big</span>
  <span m="3301070">the</span> <span m="3301940">terms</span> <span m="3302540">are,</span>
  <span m="3303590">so</span> <span m="3303740">that</span> <span m="3304220">inside</span>
  <span m="3304640">each</span> <span m="3304880">group,</span> <span m="3305570">all</span>
  <span m="3305660">the</span> <span m="3305780">terms</span> <span m="3306170">are</span>
  <span m="3306230">roughly</span> <span m="3306650">of</span> <span m="3306770">the</span>
  <span m="3306860">same</span> <span m="3307220">size.</span> <span m="3308990">And</span>
  <span m="3309500">easiest</span> <span m="3309950">way</span> <span m="3310070">to</span>
  <span m="3310160">do</span> <span m="3310310">this</span> <span m="3310550">is</span>
  <span m="3310670">to</span> <span m="3310820">chop</span> <span m="3311120">them</span>
  <span m="3311300">up</span> <span m="3311480">into</span> <span m="3314000">groups</span>
  <span m="3314450">where</span> <span m="3316190">everything</span> <span m="3316880">inside</span>
  <span m="3317330">the</span> <span m="3317420">same</span> <span m="3318380">collection</span>
  <span m="3319400">differs</span> <span m="3319820">by</span> <span m="3320000">at
  most</span> <span m="3320330">a</span> <span m="3320360">factor</span> <span m="3320750">of</span>
  <span m="3320840">2.</span> <span m="3321540">So</span> <span m="3321640">that's</span>
  <span m="3321740">why</span> <span m="3321830">it's</span> <span m="3321920">called</span>
  <span m="3322070">a</span> <span m="3322140">dyadic</span> <span m="3322395">decomposition,</span>
  <span m="3325100">going</span> <span m="3325370">from</span> <span m="3326600">0</span>
  <span m="3327050">to--</span> <span m="3327740">the</span> <span m="3328400">maximum</span>
  <span m="3329000">possible</span> <span m="3329600">here</span> <span m="3329990">is</span>
  <span m="3331280">basically</span> <span m="3332060">A.</span></p><p><span m="3332960">So</span>
  <span m="3334130">let's</span> <span m="3334340">look</span> <span m="3334580">at</span>
  <span m="3335360">i</span> <span m="3335750">going</span> <span m="3336020">from</span>
  <span m="3336230">0</span> <span m="3336620">to</span> <span m="3338000">log</span>
  <span m="3338390">base</span> <span m="3338660">2</span> <span m="3338900">of</span>
  <span m="3339050">A.</span> <span m="3339410">So</span> <span m="3339590">this</span>
  <span m="3339770">is</span> <span m="3339920">the</span> <span m="3340130">number</span>
  <span m="3340550">of</span> <span m="3340670">bins.</span> <span m="3344350">And</span>
  <span m="3346480">partition</span> <span m="3347070">the</span> <span m="3347140">sum</span>
  <span m="3348310">into</span> <span m="3348670">sub-sums</span> <span m="3349810">where</span>
  <span m="3350380">I'm</span> <span m="3350710">looking</span> <span m="3351830">at</span>
  <span m="3351930">the</span> <span m="3352120">i-th</span> <span m="3352600">sub-sum</span>
  <span m="3353530">consisting</span> <span m="3354190">of</span> <span m="3354340">contributions</span>
  <span m="3355180">involving</span> <span m="3355600">terms</span> <span m="3356980">with</span>
  <span m="3357190">size</span> <span m="3357640">between</span> <span m="3358270">2</span>
  <span m="3358510">to</span> <span m="3358630">the</span> <span m="3358780">i</span>
  <span m="3359800">and</span> <span m="3360490">2</span> <span m="3360700">to</span>
  <span m="3360850">the</span> <span m="3360970">i</span> <span m="3361150">plus</span>
  <span m="3361450">1.</span> <span m="3369530">Break</span> <span m="3369850">up</span>
  <span m="3370010">the</span> <span m="3370100">sum</span> <span m="3370490">according</span>
  <span m="3370910">to</span> <span m="3371030">the</span> <span m="3371120">sizes</span>
  <span m="3371660">of</span> <span m="3372070">the</span> <span m="3372560">summands.</span></p><p><span
  m="3375260">By</span> <span m="3375890">pigeonhole</span> <span m="3376340">principle,</span>
  <span m="3376850">one</span> <span m="3377150">of</span> <span m="3377240">these</span>
  <span m="3377360">summands</span> <span m="3378020">must</span> <span m="3378350">be</span>
  <span m="3379010">somewhat</span> <span m="3379400">large.</span> <span m="3383520">So</span>
  <span m="3383820">by</span> <span m="3384690">pigeonhole,</span> <span m="3391150">there</span>
  <span m="3391390">exists</span> <span m="3392280">a</span> <span m="3392470">k</span>
  <span m="3393730">such</span> <span m="3394090">that</span> <span m="3395320">setting</span>
  <span m="3399520">D</span> <span m="3400200">to</span> <span m="3400330">be</span>
  <span m="3402610">the</span> <span m="3402760">s</span> <span m="3404770">such</span>
  <span m="3405130">that</span> <span m="3407130">that</span> <span m="3407290">corresponds</span>
  <span m="3407920">to</span> <span m="3411010">the</span> <span m="3411170">k-th</span>
  <span m="3411650">term</span> <span m="3412010">in</span> <span m="3412190">the</span>
  <span m="3412280">sum.</span> <span m="3424250">So</span> <span m="3425150">one</span>
  <span m="3427580">has</span> <span m="3428150">that</span> <span m="3428900">this</span>
  <span m="3430040">sum</span> <span m="3430400">coming</span> <span m="3430730">from</span>
  <span m="3431030">just</span> <span m="3431390">contributions</span> <span m="3432110">from</span>
  <span m="3432380">D</span> <span m="3437790">is</span> <span m="3438810">at</span>
  <span m="3438900">least--</span> <span m="3443760">so</span> <span m="3444000">it's
  at</span> <span m="3444330">least</span> <span m="3445185">the</span> <span m="3445620">multiplicative</span>
  <span m="3446310">energy</span> <span m="3447930">divided</span> <span m="3448350">by</span>
  <span m="3448740">the</span> <span m="3448860">number</span> <span m="3449220">of</span>
  <span m="3449330">bins.</span></p><p><span m="3456170">All</span> <span m="3456580">of
  that</span> <span m="3456910">many</span> <span m="3457190">bins--</span> <span
  m="3459100">by</span> <span m="3459260">pigeonhole,</span> <span m="3459650">I</span>
  <span m="3459740">can</span> <span m="3460430">find</span> <span m="3460760">one</span>
  <span m="3461000">bin</span> <span m="3461300">that's</span> <span m="3462010">a</span>
  <span m="3462050">pretty</span> <span m="3462320">large</span> <span m="3462590">contribution</span>
  <span m="3463130">to</span> <span m="3463220">the</span> <span m="3463310">sum.</span>
  <span m="3464510">And</span> <span m="3464660">the</span> <span m="3464720">right-hand</span>
  <span m="3465080">side,</span> <span m="3467150">we</span> <span m="3467300">can</span>
  <span m="3467560">upper</span> <span m="3467780">bound</span> <span m="3468710">each</span>
  <span m="3468950">term</span> <span m="3471980">over</span> <span m="3472220">here</span>
  <span m="3472910">by</span> <span m="3473720">2</span> <span m="3474080">to</span>
  <span m="3474260">the</span> <span m="3475010">2k</span> <span m="3475490">plus</span>
  <span m="3475810">2,</span> <span m="3476840">and</span> <span m="3477020">the</span>
  <span m="3477110">number</span> <span m="3477470">of</span> <span m="3477590">terms</span>
  <span m="3478010">as</span> <span m="3478190">the</span> <span m="3478250">size</span>
  <span m="3478670">of</span> <span m="3478760">D.</span> <span m="3482020">Let</span>
  <span m="3482140">me</span> <span m="3482260">call</span> <span m="3482620">the</span>
  <span m="3482860">elements</span> <span m="3483340">of</span> <span m="3483490">D</span>
  <span m="3484790">S1</span> <span m="3485590">through</span> <span m="3485830">Sm,</span>
  <span m="3492642">where</span> <span m="3493140">S1</span> <span m="3493540">through</span>
  <span m="3493830">Sm</span> <span m="3494370">are</span> <span m="3494880">sorted</span>
  <span m="3495570">in</span> <span m="3495780">increasing</span> <span m="3496500">order.</span></p><p><span
  m="3502880">Now</span> <span m="3503140">let</span> <span m="3503260">me</span>
  <span m="3503350">draw</span> <span m="3503500">you</span> <span m="3503590">a</span>
  <span m="3503680">picture</span> <span m="3504250">of</span> <span m="3505000">what's</span>
  <span m="3505210">going</span> <span m="3505450">on.</span> <span m="3506960">Let's</span>
  <span m="3507070">consider</span> <span m="3507940">for</span> <span m="3508390">each</span>
  <span m="3516480">element</span> <span m="3517020">of</span> <span m="3517230">D,</span>
  <span m="3517900">so</span> <span m="3518100">for</span> <span m="3518250">each</span>
  <span m="3518510">i</span> <span m="3518750">and</span> <span m="3519183">m,</span>
  <span m="3520050">let's</span> <span m="3520260">consider</span> <span m="3520740">the</span>
  <span m="3520860">line</span> <span m="3525170">given</span> <span m="3525440">by</span>
  <span m="3525590">the</span> <span m="3525710">equation</span> <span m="3526520">y</span>
  <span m="3526910">equals</span> <span m="3527330">to</span> <span m="3527970">s</span>
  <span m="3528230">sub i</span> <span m="3528890">times</span> <span m="3529550">x.</span>
  <span m="3531960">Let</span> <span m="3532240">me</span> <span m="3532340">draw</span>
  <span m="3532640">this</span> <span m="3532880">picture</span> <span m="3535470">where</span>
  <span m="3536080">I'm</span> <span m="3536290">looking</span> <span m="3536800">at</span>
  <span m="3539320">the</span> <span m="3539470">positive</span> <span m="3540190">quadrant,</span>
  <span m="3541260">so</span> <span m="3541680">I</span> <span m="3541730">have</span>
  <span m="3541840">a</span> <span m="3541870">bunch</span> <span m="3542110">of</span>
  <span m="3542170">points</span> <span m="3542560">in</span> <span m="3542680">the</span>
  <span m="3542800">positive</span> <span m="3543220">quadrant.</span></p><p><span
  m="3550180">And</span> <span m="3550410">specifically,</span> <span m="3551080">I'm</span>
  <span m="3551130">interested</span> <span m="3551610">in</span> <span m="3551700">these</span>
  <span m="3551880">points</span> <span m="3552850">whose</span> <span m="3553110">coordinates,</span>
  <span m="3555160">both</span> <span m="3555360">coordinates</span> <span m="3555900">are</span>
  <span m="3556050">elements</span> <span m="3556440">of</span> <span m="3556590">A.</span>
  <span m="3558205">And</span> <span m="3560580">I</span> <span m="3560700">want</span>
  <span m="3560940">to</span> <span m="3561030">consider</span> <span m="3563010">lines</span>
  <span m="3563760">through</span> <span m="3564540">points</span> <span m="3565110">of</span>
  <span m="3565350">A,</span> <span m="3566580">but</span> <span m="3566730">I</span>
  <span m="3566790">want</span> <span m="3566970">to</span> <span m="3567030">consider</span>
  <span m="3567450">lines</span> <span m="3568350">where</span> <span m="3568950">it</span>
  <span m="3569970">intersects</span> <span m="3570720">this</span> <span m="3571050">A</span>
  <span m="3571170">cross</span> <span m="3571530">A</span> <span m="3572250">in</span>
  <span m="3572460">the</span> <span m="3572550">desired</span> <span m="3573210">number</span>
  <span m="3573600">of</span> <span m="3573900">points.</span> <span m="3577030">And</span>
  <span m="3577480">we</span> <span m="3577570">find</span> <span m="3577820">those</span>
  <span m="3577950">set,</span> <span m="3578620">and</span> <span m="3578740">then</span>
  <span m="3579100">let's</span> <span m="3579400">draw</span> <span m="3583160">these</span>
  <span m="3583490">lines</span> <span m="3584690">over</span> <span m="3584900">here,</span>
  <span m="3585590">where</span> <span m="3586310">this</span> <span m="3586550">line</span>
  <span m="3586760">here,</span> <span m="3587070">L1</span> <span m="3588120">has</span>
  <span m="3588420">slope</span> <span m="3589490">exactly</span> <span m="3590060">S1,</span>
  <span m="3591060">and</span> <span m="3591560">L2,</span> <span m="3592400">L3,</span>
  <span m="3593180">and</span> <span m="3593300">so</span> <span m="3593510">on.</span></p><p><span
  m="3598990">I</span> <span m="3599050">want</span> <span m="3599110">to</span> <span
  m="3599260">draw</span> <span m="3599470">one</span> <span m="3599650">more</span>
  <span m="3599890">line,</span> <span m="3600610">which</span> <span m="3601090">is</span>
  <span m="3602360">somewhat</span> <span m="3603190">auxiliary,</span> <span m="3603820">but</span>
  <span m="3604030">just</span> <span m="3604210">to</span> <span m="3604300">make</span>
  <span m="3604540">our</span> <span m="3604660">life</span> <span m="3604930">a</span>
  <span m="3604990">bit</span> <span m="3605140">easier.</span> <span m="3606770">Finally,</span>
  <span m="3607120">let's</span> <span m="3607480">let</span> <span m="3608590">L</span>
  <span m="3608890">of</span> <span m="3609120">m</span> <span m="3609910">plus</span>
  <span m="3610210">1</span> <span m="3610820">be</span> <span m="3611020">the</span>
  <span m="3611170">vertical</span> <span m="3611620">line,</span> <span m="3613240">or</span>
  <span m="3613330">rather</span> <span m="3613660">be</span> <span m="3613780">the</span>
  <span m="3613900">vertical</span> <span m="3614410">ray,</span> <span m="3618870">which</span>
  <span m="3621030">goes</span> <span m="3621390">to</span> <span m="3621570">the</span>
  <span m="3621780">minimum</span> <span m="3622290">element</span> <span m="3622710">of</span>
  <span m="3622890">A</span> <span m="3626970">above</span> <span m="3630410">Lm.</span>
  <span m="3631230">So</span> <span m="3632280">it's</span> <span m="3632700">this</span>
  <span m="3632970">line</span> <span m="3633450">over</span> <span m="3633690">here.</span>
  <span m="3634660">That's</span> <span m="3635550">Lm</span> <span m="3635880">plus</span>
  <span m="3636180">1.</span></p><p><span m="3640550">So</span> <span m="3640910">in</span>
  <span m="3641160">A</span> <span m="3641310">cross</span> <span m="3641640">A,</span>
  <span m="3641820">I</span> <span m="3642690">draw</span> <span m="3643200">a</span>
  <span m="3643260">bunch</span> <span m="3643530">of</span> <span m="3643620">lines.</span>
  <span m="3644920">So</span> <span m="3645090">now</span> <span m="3645600">all</span>
  <span m="3645810">the</span> <span m="3645930">lines--</span> <span m="3646650">so</span>
  <span m="3646980">all</span> <span m="3647130">these</span> <span m="3647340">lines</span>
  <span m="3648030">involve</span> <span m="3648360">some</span> <span m="3648600">point</span>
  <span m="3649020">of</span> <span m="3649200">A</span> <span m="3649560">and</span>
  <span m="3649860">the</span> <span m="3650010">origin,</span> <span m="3650700">but</span>
  <span m="3650910">I</span> <span m="3650970">don't</span> <span m="3651160">draw</span>
  <span m="3651330">all</span> <span m="3651540">of</span> <span m="3651600">them.</span>
  <span m="3651930">I</span> <span m="3652020">draw</span> <span m="3652410">a</span>
  <span m="3652470">select</span> <span m="3652860">set</span> <span m="3653190">of</span>
  <span m="3653310">them.</span> <span m="3654600">And</span> <span m="3656100">what</span>
  <span m="3656340">we</span> <span m="3656490">said</span> <span m="3656850">earlier</span>
  <span m="3657180">says</span> <span m="3657510">that</span> <span m="3657930">the</span>
  <span m="3658080">number</span> <span m="3658680">of</span> <span m="3658920">lines,</span>
  <span m="3659620">the</span> <span m="3659640">number</span> <span m="3659940">of</span>
  <span m="3660030">points</span> <span m="3660480">on</span> <span m="3660660">each</span>
  <span m="3660960">of</span> <span m="3661110">these</span> <span m="3661230">strong</span>
  <span m="3661710">lines,</span> <span m="3662880">is</span> <span m="3663450">roughly</span>
  <span m="3663840">the</span> <span m="3663960">same</span> <span m="3664320">for</span>
  <span m="3664860">each</span> <span m="3665070">of</span> <span m="3665190">these</span>
  <span m="3665370">lines.</span></p><p><span m="3672350">Let's</span> <span m="3672620">let</span>
  <span m="3673850">capital</span> <span m="3674360">L</span> <span m="3675070">sub</span>
  <span m="3675375">j</span> <span m="3676020">denote</span> <span m="3676700">the</span>
  <span m="3676820">set</span> <span m="3677240">of</span> <span m="3678320">points</span>
  <span m="3679190">in</span> <span m="3680090">A</span> <span m="3680240">cross</span>
  <span m="3680720">A</span> <span m="3681520">that</span> <span m="3681980">lie</span>
  <span m="3682850">on</span> <span m="3683060">the</span> <span m="3683630">j-th</span>
  <span m="3684090">line.</span> <span m="3692320">So</span> <span m="3692530">that's</span>
  <span m="3693610">L1,</span> <span m="3696230">L2,</span> <span m="3697570">and</span>
  <span m="3697660">so</span> <span m="3697840">on.</span> <span m="3701230">I</span>
  <span m="3701320">claim</span> <span m="3701980">that</span> <span m="3702730">if</span>
  <span m="3702850">you</span> <span m="3702940">look</span> <span m="3703180">at</span>
  <span m="3703300">two</span> <span m="3703840">consecutive</span> <span m="3708550">lines</span>
  <span m="3709420">and</span> <span m="3709810">look</span> <span m="3710050">at</span>
  <span m="3710170">the</span> <span m="3710660">sum</span> <span m="3711000">set</span>
  <span m="3712240">of</span> <span m="3712420">the</span> <span m="3713440">points</span>
  <span m="3714310">in</span> <span m="3714610">A</span> <span m="3714730">cross</span>
  <span m="3715100">A</span> <span m="3715390">that</span> <span m="3715590">intersect,</span>
  <span m="3719420">you're</span> <span m="3719540">looking</span> <span m="3719750">at</span>
  <span m="3719810">two</span> <span m="3719960">lines,</span> <span m="3720500">and</span>
  <span m="3720600">you're</span> <span m="3720710">adding</span> <span m="3721010">up</span>
  <span m="3721070">points</span> <span m="3721460">on</span> <span m="3721550">those</span>
  <span m="3721700">two</span> <span m="3721850">lines.</span> <span m="3722550">So</span>
  <span m="3722750">you</span> <span m="3722930">form</span> <span m="3723530">a</span>
  <span m="3723920">grid.</span></p><p><span m="3725680">So</span> <span m="3725850">you</span>
  <span m="3726030">end</span> <span m="3726270">up</span> <span m="3726420">forming</span>
  <span m="3726990">this</span> <span m="3731080">grid.</span> <span m="3733210">And</span>
  <span m="3733490">the</span> <span m="3733540">number</span> <span m="3733900">of</span>
  <span m="3733990">points</span> <span m="3734500">on</span> <span m="3734680">this</span>
  <span m="3734890">grid</span> <span m="3735940">is</span> <span m="3736090">precisely</span>
  <span m="3737290">the</span> <span m="3737410">product</span> <span m="3738100">of</span>
  <span m="3738310">these</span> <span m="3738550">two</span> <span m="3738880">point</span>
  <span m="3739240">sets.</span> <span m="3748940">Moreover,</span> <span m="3753050">the</span>
  <span m="3754540">sets</span> <span m="3756910">Lj</span> <span m="3757690">plus</span>
  <span m="3759590">L sub</span> <span m="3760030">j</span> <span m="3760210">plus</span>
  <span m="3760450">1</span> <span m="3762650">are</span> <span m="3765380">disjoint</span>
  <span m="3766990">for</span> <span m="3767360">different</span> <span m="3767750">j.</span></p><p><span
  m="3772660">And</span> <span m="3772750">this</span> <span m="3772930">is</span>
  <span m="3773590">where</span> <span m="3773800">we're</span> <span m="3773950">using</span>
  <span m="3774400">the</span> <span m="3774640">geometry</span> <span m="3775360">of</span>
  <span m="3775450">the</span> <span m="3775540">plane</span> <span m="3775840">here.</span>
  <span m="3776440">Because</span> <span m="3776890">the</span> <span m="3778630">sum</span>
  <span m="3779050">of</span> <span m="3779440">L1</span> <span m="3779770">and</span>
  <span m="3779900">L2</span> <span m="3780370">lies</span> <span m="3780910">in</span>
  <span m="3781150">the</span> <span m="3781300">span,</span> <span m="3782960">the</span>
  <span m="3783290">sum</span> <span m="3783590">of</span> <span m="3783710">L2</span>
  <span m="3784100">and</span> <span m="3784190">L3</span> <span m="3784610">in</span>
  <span m="3785030">a</span> <span m="3785090">different</span> <span m="3785450">span,</span>
  <span m="3786470">so</span> <span m="3786590">they</span> <span m="3786710">cannot</span>
  <span m="3787040">intersect.</span> <span m="3789370">So</span> <span m="3789510">they</span>
  <span m="3789630">lie</span> <span m="3789900">in--</span> <span m="3791430">so</span>
  <span m="3793260">since</span> <span m="3796070">they</span> <span m="3796340">span</span>
  <span m="3799350">disjoint</span> <span m="3800060">regions,</span> <span m="3816134">L1</span>
  <span m="3817130">plus</span> <span m="3817390">L2</span> <span m="3817760">lies</span>
  <span m="3818040">here,</span> <span m="3818370">L2</span> <span m="3818870">plus</span>
  <span m="3819260">L3</span> <span m="3819590">lies</span> <span m="3819920">there,</span>
  <span m="3820190">and</span> <span m="3820410">so</span> <span m="3820650">on.</span>
  <span m="3821590">But</span> <span m="3822060">they're</span> <span m="3822260">all</span>
  <span m="3822380">disjoint.</span></p><p><span m="3831180">Now</span> <span m="3831780">let's</span>
  <span m="3831960">put</span> <span m="3832320">everything</span> <span m="3832740">that</span>
  <span m="3832890">we</span> <span m="3833040">know</span> <span m="3833280">together.</span>
  <span m="3838720">Remember,</span> <span m="3839130">the</span> <span m="3839280">goal</span>
  <span m="3839730">is</span> <span m="3840000">to</span> <span m="3842220">upper</span>
  <span m="3842430">bound</span> <span m="3842940">the</span> <span m="3843360">multiplicative</span>
  <span m="3844500">energy</span> <span m="3846550">as</span> <span m="3846690">a</span>
  <span m="3846750">function</span> <span m="3847470">of</span> <span m="3849000">the</span>
  <span m="3849360">sum</span> <span m="3849630">set.</span> <span m="3849840">So</span>
  <span m="3849960">in</span> <span m="3850050">other</span> <span m="3850230">words,</span>
  <span m="3850540">we</span> <span m="3850590">want to</span> <span m="3850890">lower</span>
  <span m="3851130">bound</span> <span m="3851380">the</span> <span m="3851420">sum</span>
  <span m="3851620">set.</span> <span m="3852300">So</span> <span m="3853080">I</span>
  <span m="3853170">want</span> <span m="3853350">to</span> <span m="3853560">show</span>
  <span m="3853920">you</span> <span m="3854400">that</span> <span m="3854820">this</span>
  <span m="3855180">A</span> <span m="3855440">plus</span> <span m="3855715">A</span>
  <span m="3856230">has</span> <span m="3857460">a</span> <span m="3857520">lot</span>
  <span m="3857790">of</span> <span m="3857880">elements.</span> <span m="3859360">There's</span>
  <span m="3859530">a</span> <span m="3859590">lot</span> <span m="3859830">of</span>
  <span m="3859920">sums.</span></p><p><span m="3861690">And</span> <span m="3861990">I
  have a</span> <span m="3862080">bunch</span> <span m="3862350">of</span> <span m="3862530">disjoint</span>
  <span m="3863580">contributions</span> <span m="3864300">to</span> <span m="3864420">these</span>
  <span m="3864600">sums.</span> <span m="3865360">So</span> <span m="3865380">let's</span>
  <span m="3865740">add</span> <span m="3865980">up</span> <span m="3866220">those</span>
  <span m="3866460">disjoint</span> <span m="3866940">contributions</span> <span m="3867930">to</span>
  <span m="3868110">the</span> <span m="3868200">sums.</span> <span m="3872883">You</span>
  <span m="3873360">see</span> <span m="3873600">that</span> <span m="3873780">the</span>
  <span m="3873920">size</span> <span m="3874350">of</span> <span m="3874530">A</span>
  <span m="3874650">plus</span> <span m="3874950">A</span> <span m="3875160">squared</span>
  <span m="3878220">is</span> <span m="3878370">the</span> <span m="3878460">same</span>
  <span m="3879060">as</span> <span m="3879750">the</span> <span m="3879810">size</span>
  <span m="3880290">of</span> <span m="3880470">the</span> <span m="3880870">product</span>
  <span m="3881400">set</span> <span m="3881850">A</span> <span m="3881940">plus</span>
  <span m="3882340">A.</span></p><p><span m="3882990">So</span> <span m="3883140">this</span>
  <span m="3883350">is</span> <span m="3883860">Cartesian</span> <span m="3884340">product.</span>
  <span m="3885540">Here</span> <span m="3885850">is--</span> <span m="3892220">this</span>
  <span m="3892460">is a</span> <span m="3892740">Cartesian</span> <span m="3893160">product,</span>
  <span m="3895110">in</span> <span m="3895130">other</span> <span m="3895250">words,</span>
  <span m="3895560">the</span> <span m="3895580">grid</span> <span m="3896030">that</span>
  <span m="3896210">is</span> <span m="3896270">strong</span> <span m="3896690">up</span>
  <span m="3896810">there.</span> <span m="3898740">I</span> <span m="3898860">add</span>
  <span m="3899330">this</span> <span m="3899930">product</span> <span m="3900500">to</span>
  <span m="3900720">itself.</span> <span m="3904760">So</span> <span m="3904950">I</span>
  <span m="3905060">should</span> <span m="3905210">get</span> <span m="3905420">the</span>
  <span m="3905510">same</span> <span m="3905780">set</span> <span m="3906100">here.</span></p><p><span
  m="3909660">But how</span> <span m="3909840">big</span> <span m="3910100">is</span>
  <span m="3910280">this</span> <span m="3911000">sum</span> <span m="3911270">set?</span>
  <span m="3911800">That</span> <span m="3912410">grid,</span> <span m="3912860">that</span>
  <span m="3913030">lattice</span> <span m="3913370">grid</span> <span m="3914240">added</span>
  <span m="3914480">to</span> <span m="3914600">itself,</span> <span m="3915290">how</span>
  <span m="3915500">big</span> <span m="3915740">should</span> <span m="3915950">it</span>
  <span m="3916010">be?</span> <span m="3916180">I</span> <span m="3916250">want</span>
  <span m="3916430">to</span> <span m="3916490">lower</span> <span m="3916760">bound</span>
  <span m="3917480">the</span> <span m="3917570">number</span> <span m="3917990">of</span>
  <span m="3918080">sums.</span></p><p><span m="3919220">And</span> <span m="3919970">the</span>
  <span m="3920060">key</span> <span m="3920330">observation</span> <span m="3921690">is</span>
  <span m="3922160">up</span> <span m="3922440">there.</span> <span m="3923030">We</span>
  <span m="3923210">can</span> <span m="3923660">look</span> <span m="3923900">at</span>
  <span m="3924020">contributions</span> <span m="3924860">coming</span> <span m="3925160">from</span>
  <span m="3925400">distinct</span> <span m="3925980">spans.</span> <span m="3927880">In</span>
  <span m="3927950">particular,</span> <span m="3929900">this</span> <span m="3930790">sum</span>
  <span m="3931190">here,</span> <span m="3931740">so</span> <span m="3931840">this</span>
  <span m="3932690">sum</span> <span m="3933080">set</span> <span m="3933470">here,</span>
  <span m="3934980">size</span> <span m="3935280">is</span> <span m="3935580">lower</span>
  <span m="3935890">bounded</span> <span m="3937040">by</span> <span m="3938840">these</span>
  <span m="3939200">distinct</span> <span m="3940160">Lj</span> <span m="3941270">plus</span>
  <span m="3942140">L</span> <span m="3942530">j</span> <span m="3944000">plus</span>
  <span m="3944320">1's.</span> <span m="3945260">I</span> <span m="3945380">threw</span>
  <span m="3945620">away</span> <span m="3945860">a</span> <span m="3945920">lot.</span>
  <span m="3946210">I</span> <span m="3946300">only</span> <span m="3946580">keep</span>
  <span m="3946820">the</span> <span m="3946910">lines</span> <span m="3947270">on</span>
  <span m="3947390">the</span> <span m="3947510">L's,</span> <span m="3948250">and</span>
  <span m="3948390">I</span> <span m="3948470">only</span> <span m="3948680">consider</span>
  <span m="3949070">sums</span> <span m="3949430">between</span> <span m="3949760">consecutive</span>
  <span m="3950540">L's.</span> <span m="3952330">That</span> <span m="3952450">should</span>
  <span m="3952650">be</span> <span m="3952800">a</span> <span m="3952860">lower</span>
  <span m="3953100">bound</span> <span m="3953430">to</span> <span m="3954530">the</span>
  <span m="3954740">sum set</span> <span m="3955170">of</span> <span m="3955290">the</span>
  <span m="3955380">grid</span> <span m="3955680">with</span> <span m="3955860">itself.</span></p><p><span
  m="3958860">But</span> <span m="3959000">you</span> <span m="3959090">see,</span>
  <span m="3960422">and</span> <span m="3960820">here,</span> <span m="3961010">we're</span>
  <span m="3961130">using</span> <span m="3962270">these</span> <span m="3963020">different--</span>
  <span m="3963425">for</span> <span m="3963830">different</span> <span m="3964100">j's,</span>
  <span m="3964730">these</span> <span m="3964940">contributions</span> <span m="3965540">are</span>
  <span m="3965630">destroyed.</span> <span m="3968460">But</span> <span m="3968860">by</span>
  <span m="3969010">what</span> <span m="3969190">we</span> <span m="3969310">said</span>
  <span m="3969510">up</span> <span m="3969670">there,</span> <span m="3972100">Lj</span>
  <span m="3972580">plus</span> <span m="3972865">L j</span> <span m="3973150">plus</span>
  <span m="3973750">1</span> <span m="3974530">is</span> <span m="3974830">a</span>
  <span m="3974980">grid.</span> <span m="3975640">So</span> <span m="3976110">it</span>
  <span m="3976230">has</span> <span m="3976420">size</span> <span m="3977640">Lj</span>
  <span m="3978220">times</span> <span m="3979970">L</span> <span m="3980260">j</span>
  <span m="3980440">plus</span> <span m="3980690">1.</span> <span m="3983900">And</span>
  <span m="3983990">the</span> <span m="3984050">size</span> <span m="3984470">of</span>
  <span m="3984560">each</span> <span m="3984980">Lj</span> <span m="3985430">is</span>
  <span m="3988030">at</span> <span m="3988690">least</span> <span m="3989980">2</span>
  <span m="3990340">to</span> <span m="3990520">the</span> <span m="3991440">k.</span>
  <span m="3992900">So</span> <span m="3993710">the</span> <span m="3993800">sum</span>
  <span m="3994100">here</span> <span m="3994250">is</span> <span m="3994370">at</span>
  <span m="3994430">least</span> <span m="3995300">m</span> <span m="3995810">times</span>
  <span m="3996260">2</span> <span m="3996550">to</span> <span m="3996680">the</span>
  <span m="3997780">2k.</span></p><p><span m="4001410">But</span> <span m="4001740">we</span>
  <span m="4003060">saw</span> <span m="4003330">over</span> <span m="4003570">here</span>
  <span m="4004320">that</span> <span m="4004560">the</span> <span m="4005520">energy</span>
  <span m="4006840">lower</span> <span m="4007140">bounds</span> <span m="4008340">this</span>
  <span m="4008780">2</span> <span m="4009020">to</span> <span m="4009150">the</span>
  <span m="4009280">2k.</span> <span m="4010290">So</span> <span m="4012000">we</span>
  <span m="4012090">have</span> <span m="4012240">a</span> <span m="4012300">lower</span>
  <span m="4012570">bound</span> <span m="4013230">that</span> <span m="4013410">is</span>
  <span m="4014480">the</span> <span m="4014880">multiplicative</span> <span m="4015540">energy</span>
  <span m="4016770">of</span> <span m="4016890">A</span> <span m="4018060">divided</span>
  <span m="4018480">by</span> <span m="4018840">4</span> <span m="4019560">times</span>
  <span m="4020970">the</span> <span m="4021870">log</span> <span m="4022170">base</span>
  <span m="4022440">2</span> <span m="4023730">of</span> <span m="4024480">the</span>
  <span m="4024570">size</span> <span m="4024930">of</span> <span m="4025030">A.</span>
  <span m="4025410">So</span> <span m="4025530">don't</span> <span m="4025680">worry</span>
  <span m="4025860">so</span> <span m="4025980">much</span> <span m="4026190">about</span>
  <span m="4026370">the</span> <span m="4026460">constant</span> <span m="4026880">factors.</span>
  <span m="4027490">That's</span> <span m="4028260">just</span> <span m="4028460">the</span>
  <span m="4028520">order</span> <span m="4028830">of</span> <span m="4028950">magnitude</span>
  <span m="4029460">that</span> <span m="4029640">is</span> <span m="4029790">important.</span></p><p><span
  m="4033000">And</span> <span m="4033090">that's</span> <span m="4033240">it.</span>
  <span m="4034680">Yep.</span></p><p><span m="4035309">AUDIENCE:</span> <span m="4035426">How</span>
  <span m="4035543">do</span> <span m="4035660">you</span> <span m="4035778">know
  that</span> <span m="4036247">the size</span> <span m="4036716">of big</span> <span
  m="4037185">L</span> <span m="4037654">sub</span> <span m="4038123">m plus</span>
  <span m="4038592">1?</span></p><p><span m="4040580">YUFEI ZHAO:</span> <span m="4040730">Great.</span>
  <span m="4040880">The</span> <span m="4040940">question</span> <span m="4041180">is,</span>
  <span m="4041720">what</span> <span m="4041900">do</span> <span m="4041960">we</span>
  <span m="4042080">know</span> <span m="4042230">about</span> <span m="4042410">the</span>
  <span m="4042530">size</span> <span m="4042950">of</span> <span m="4043040">big</span>
  <span m="4043370">L</span> <span m="4043680">sub</span> <span m="4044200">m</span>
  <span m="4044420">plus</span> <span m="4044750">1?</span> <span m="4045360">So</span>
  <span m="4045380">that's</span> <span m="4045590">a</span> <span m="4045680">good</span>
  <span m="4045800">point.</span> <span m="4048940">The</span> <span m="4049440">easiest</span>
  <span m="4049860">answer</span> <span m="4050160">is,</span> <span m="4050340">if</span>
  <span m="4050430">I</span> <span m="4050520">don't</span> <span m="4050670">care</span>
  <span m="4050850">about</span> <span m="4051030">these</span> <span m="4051180">constant</span>
  <span m="4051570">factors,</span> <span m="4051960">I</span> <span m="4052020">don't</span>
  <span m="4052140">need</span> <span m="4052260">to</span> <span m="4052320">worry</span>
  <span m="4052560">about</span> <span m="4052800">it.</span></p><p><span m="4054660">You</span>
  <span m="4054780">can</span> <span m="4055410">think</span> <span m="4055680">about</span>
  <span m="4056520">what</span> <span m="4058350">is</span> <span m="4058470">the</span>
  <span m="4058560">number</span> <span m="4058950">of</span> <span m="4059550">points</span>
  <span m="4060060">on</span> <span m="4060930">this</span> <span m="4061200">line</span>
  <span m="4063420">above</span> <span m="4066750">that.</span> <span m="4067430">It's</span>
  <span m="4067560">essentially</span> <span m="4068070">the</span> <span m="4068610">number</span>
  <span m="4068910">of</span> <span m="4069030">elements</span> <span m="4069510">of</span>
  <span m="4070170">A</span> <span m="4072020">above</span> <span m="4072450">the</span>
  <span m="4072630">biggest</span> <span m="4073110">element</span> <span m="4073620">of</span>
  <span m="4075150">s</span> <span m="4075290">m,</span> <span m="4076470">above</span>
  <span m="4076800">s</span> <span m="4076970">m.</span> <span m="4081197">It's</span>
  <span m="4081644">a</span> <span m="4082091">good</span> <span m="4082540">question.</span>
  <span m="4083140">I</span> <span m="4083200">think</span> <span m="4083440">we</span>
  <span m="4083560">don't</span> <span m="4083770">need</span> <span m="4083890">to</span>
  <span m="4083980">worry</span> <span m="4084220">about</span> <span m="4084430">it.</span>
  <span m="4084790">I'm</span> <span m="4085330">being</span> <span m="4085510">slightly</span>
  <span m="4085840">sloppy</span> <span m="4086260">here.</span> <span m="4088935">Yeah.</span></p><p><span
  m="4090915">AUDIENCE:</span> <span m="4091162">[INAUDIBLE]</span></p><p><span m="4097120">YUFEI
  ZHAO:</span> <span m="4097134">I</span> <span m="4097149">think</span> <span m="4097300">the</span>
  <span m="4097390">question</span> <span m="4097810">is,</span> <span m="4098390">how</span>
  <span m="4098500">do</span> <span m="4098560">we</span> <span m="4098680">know</span>
  <span m="4099490">for</span> <span m="4100180">j</span> <span m="4100450">equals</span>
  <span m="4100750">to</span> <span m="4100870">m</span> <span m="4101410">that</span>
  <span m="4101580">you</span> <span m="4101710">have</span> <span m="4101979">this</span>
  <span m="4102220">bound</span> <span m="4102580">over</span> <span m="4102790">here?</span></p><p><span
  m="4105866">AUDIENCE:</span> <span m="4106101">[INAUDIBLE]</span></p><p><span m="4114020">YUFEI
  ZHAO:</span> <span m="4114155">Great.</span> <span m="4114520">So</span> <span m="4115120">yes.</span></p><p><span
  m="4118224">AUDIENCE:</span> <span m="4118471">[INAUDIBLE]</span></p><p><span m="4129359">YUFEI
  ZHAO:</span> <span m="4129434">So</span> <span m="4129510">there</span> <span m="4129569">are</span>
  <span m="4129640">some</span> <span m="4129840">ways</span> <span m="4130050">to</span>
  <span m="4130140">do</span> <span m="4130260">it.</span> <span m="4130710">You</span>
  <span m="4130830">can</span> <span m="4131279">notice</span> <span m="4131700">that</span>
  <span m="4131910">the</span> <span m="4132240">vertical</span> <span m="4132689">line</span>
  <span m="4133010">has</span> <span m="4133319">at</span> <span m="4133410">least</span>
  <span m="4133620">as</span> <span m="4133770">many</span> <span m="4133979">points</span>
  <span m="4134760">as</span> <span m="4134939">the</span> <span m="4135630">first</span>
  <span m="4139649">slanted</span> <span m="4140130">line.</span> <span m="4143420">So</span>
  <span m="4145500">details</span> <span m="4145979">that</span> <span m="4146130">you</span>
  <span m="4146220">can</span> <span m="4146370">work</span> <span m="4146580">on.</span>
  <span m="4148700">So</span> <span m="4149010">this</span> <span m="4149200">proves</span>
  <span m="4149660">Solymosi's</span> <span m="4150359">theorem,</span> <span m="4151109">which</span>
  <span m="4151319">gives</span> <span m="4151590">you</span> <span m="4151740">a</span>
  <span m="4151800">lower</span> <span m="4152040">bound</span> <span m="4152939">on</span>
  <span m="4153240">the</span> <span m="4155359">sum</span> <span m="4155640">set</span>
  <span m="4155930">and</span> <span m="4156020">the</span> <span m="4156080">product</span>
  <span m="4156470">set</span> <span m="4156670">sizes</span> <span m="4157130">and
  the</span> <span m="4157370">maximum</span> <span m="4157910">of</span> <span m="4158029">those</span>
  <span m="4158260">two.</span></p><p><span m="4159600">It's</span> <span m="4159920">based</span>
  <span m="4160220">on--</span> <span m="4160420">it's</span> <span m="4160819">very</span>
  <span m="4161060">short.</span> <span m="4161330">It's</span> <span m="4161420">very</span>
  <span m="4161600">clever.</span> <span m="4161990">It</span> <span m="4162050">took</span>
  <span m="4162290">a</span> <span m="4162439">long</span> <span m="4162649">time</span>
  <span m="4162890">to</span> <span m="4162979">find.</span> <span m="4164540">And</span>
  <span m="4165850">it</span> <span m="4165950">gave</span> <span m="4166160">a</span>
  <span m="4166220">bound</span> <span m="4167540">on</span> <span m="4167810">the</span>
  <span m="4168069">sum</span> <span m="4168319">product</span> <span m="4168649">problem</span>
  <span m="4169160">of</span> <span m="4169460">4/3</span> <span m="4170569">that</span>
  <span m="4170750">actually</span> <span m="4171920">remained</span> <span m="4172370">stuck</span>
  <span m="4172760">for</span> <span m="4173180">a</span> <span m="4173240">very</span>
  <span m="4173479">long</span> <span m="4173689">time,</span> <span m="4175069">until</span>
  <span m="4176390">just</span> <span m="4176810">fairly</span> <span m="4177170">recently</span>
  <span m="4179029">there</span> <span m="4179180">was</span> <span m="4179340">an</span>
  <span m="4179750">improvement</span> <span m="4186470">that</span> <span m="4187109">gives--</span>
  <span m="4188420">so</span> <span m="4188630">by</span> <span m="4189770">Konyagin</span>
  <span m="4190580">and</span> <span m="4190729">Shkredov</span> <span m="4191990">where</span>
  <span m="4192350">they</span> <span m="4192560">improved</span> <span m="4194229">the</span>
  <span m="4194630">Solymosi</span> <span m="4194930">bound</span> <span m="4195320">from</span>
  <span m="4196330">4/3</span> <span m="4197390">to</span> <span m="4197600">4/3</span>
  <span m="4198260">plus</span> <span m="4198590">some</span> <span m="4199250">really</span>
  <span m="4199460">small</span> <span m="4199790">constant</span> <span m="4200330">c.</span>
  <span m="4204300">So</span> <span m="4204500">it's</span> <span m="4204740">some</span>
  <span m="4204950">explicit</span> <span m="4205460">constant.</span> <span m="4206530">I</span>
  <span m="4206750">think</span> <span m="4206930">right</span> <span m="4207110">now--</span>
  <span m="4207320">so</span> <span m="4207440">that's</span> <span m="4207710">being</span>
  <span m="4207910">proved</span> <span m="4208250">over</span> <span m="4208430">time,</span>
  <span m="4209040">but</span> <span m="4209060">right</span> <span m="4209210">now,</span>
  <span m="4209550">I</span> <span m="4209650">think</span> <span m="4209690">c</span>
  <span m="4210040">is</span> <span m="4210260">around</span> <span m="4210770">1</span>
  <span m="4211370">over</span> <span m="4212270">1,000</span> <span m="4212780">or</span>
  <span m="4212870">a</span> <span m="4212900">few</span> <span m="4213110">thousand.</span>
  <span m="4213730">So it's</span> <span m="4213880">some</span> <span m="4214160">small</span>
  <span m="4214460">but</span> <span m="4214640">explicit</span> <span m="4215120">constant.</span></p><p><span
  m="4217600">It</span> <span m="4217920">remains</span> <span m="4218440">a</span>
  <span m="4218530">major</span> <span m="4218860">open</span> <span m="4219130">problem</span>
  <span m="4220030">to</span> <span m="4220750">improve</span> <span m="4221140">this</span>
  <span m="4221270">bound</span> <span m="4222170">and</span> <span m="4222430">prove</span>
  <span m="4222910">Erdos'</span> <span m="4223330">similarity</span> <span m="4223900">conjecture,</span>
  <span m="4225730">that</span> <span m="4227470">if</span> <span m="4227620">you</span>
  <span m="4227800">have</span> <span m="4229190">n</span> <span m="4229450">elements,</span>
  <span m="4229900">then</span> <span m="4230080">one</span> <span m="4230410">of</span>
  <span m="4230530">the</span> <span m="4230620">sums</span> <span m="4231070">or</span>
  <span m="4231160">products</span> <span m="4231850">must</span> <span m="4232120">be</span>
  <span m="4232240">nearly</span> <span m="4232630">quadratic</span> <span m="4233200">in</span>
  <span m="4233340">size.</span> <span m="4233830">And</span> <span m="4234820">people</span>
  <span m="4235120">generally</span> <span m="4235510">believe</span> <span m="4235810">that</span>
  <span m="4235930">that's</span> <span m="4236230">the</span> <span m="4236320">case.</span>
  <span m="4239320">Any</span> <span m="4239400">questions?</span></p><p><span m="4247950">So</span>
  <span m="4248190">this</span> <span m="4248370">concludes</span> <span m="4248730">all</span>
  <span m="4248850">the</span> <span m="4249270">topics</span> <span m="4249720">I</span>
  <span m="4249810">want</span> <span m="4249930">to</span> <span m="4249990">cover</span>
  <span m="4250320">in</span> <span m="4250440">this</span> <span m="4250590">course.</span>
  <span m="4251410">So</span> <span m="4251460">we</span> <span m="4251580">went</span>
  <span m="4251760">a</span> <span m="4251820">long</span> <span m="4252060">way.</span>
  <span m="4252470">And so</span> <span m="4252630">the</span> <span m="4252720">beginning</span>
  <span m="4253080">of</span> <span m="4253170">this</span> <span m="4253320">course,</span>
  <span m="4254110">we</span> <span m="4254160">started</span> <span m="4254700">with</span>
  <span m="4255300">extremal</span> <span m="4255810">graph</span> <span m="4256140">theory,</span>
  <span m="4256860">looking</span> <span m="4257190">at</span> <span m="4257280">the</span>
  <span m="4257340">basic</span> <span m="4257760">problem</span> <span m="4258360">of</span>
  <span m="4258780">if</span> <span m="4258960">you</span> <span m="4259260">have</span>
  <span m="4259980">a</span> <span m="4260040">graph</span> <span m="4260520">that</span>
  <span m="4260760">doesn't</span> <span m="4261030">contain</span> <span m="4261420">some</span>
  <span m="4262200">subgraph,</span> <span m="4263490">triangle,</span> <span m="4264210">C4,</span>
  <span m="4265620">what's</span> <span m="4265830">the</span> <span m="4265920">maximum</span>
  <span m="4266490">number</span> <span m="4266820">of</span> <span m="4267030">edges.</span>
  <span m="4268440">In</span> <span m="4268500">fact,</span> <span m="4268700">that</span>
  <span m="4268800">showed</span> <span m="4269040">up</span> <span m="4269160">even</span>
  <span m="4269400">today.</span></p><p><span m="4271350">And</span> <span m="4271500">then</span>
  <span m="4271620">we</span> <span m="4271740">went</span> <span m="4271940">down</span>
  <span m="4272100">to</span> <span m="4272460">other</span> <span m="4272670">tools,</span>
  <span m="4273270">like</span> <span m="4273600">Szemeredi's</span> <span m="4274170">regularity</span>
  <span m="4274710">lemma</span> <span m="4275640">that</span> <span m="4275820">allows</span>
  <span m="4276210">us</span> <span m="4276450">to</span> <span m="4276750">deduce</span>
  <span m="4277170">important</span> <span m="4277770">arithmetic</span> <span m="4278250">consequences,</span>
  <span m="4279300">such</span> <span m="4279540">as</span> <span m="4279690">Roth's</span>
  <span m="4280055">theorem.</span> <span m="4280800">It's</span> <span m="4280890">also</span>
  <span m="4281100">an</span> <span m="4281190">extremal</span> <span m="4281670">problem</span>
  <span m="4281970">if</span> <span m="4282090">you</span> <span m="4282210">have</span>
  <span m="4282330">a</span> <span m="4282390">set</span> <span m="4282780">without</span>
  <span m="4282960">a</span> <span m="4283230">three-term</span> <span m="4283740">arithmetic</span>
  <span m="4284190">progression,</span> <span m="4285300">how</span> <span m="4285600">many</span>
  <span m="4286410">elements</span> <span m="4287040">can</span> <span m="4287250">it</span>
  <span m="4287340">have?</span> <span m="4288880">And</span> <span m="4288970">so</span>
  <span m="4289140">the</span> <span m="4289500">important</span> <span m="4289890">tool</span>
  <span m="4290100">of</span> <span m="4290250">Szemeredi's</span> <span m="4290690">regularity</span>
  <span m="4291240">lemma</span> <span m="4291900">then</span> <span m="4292170">later</span>
  <span m="4292500">showed</span> <span m="4292860">up</span> <span m="4293370">in</span>
  <span m="4293460">many</span> <span m="4293700">different</span> <span m="4294000">ways</span>
  <span m="4294270">in</span> <span m="4294360">this</span> <span m="4294510">course,</span>
  <span m="4295450">especially</span> <span m="4295800">the</span> <span m="4295860">message</span>
  <span m="4296490">of</span> <span m="4296760">Szemeredi's</span> <span m="4297160">regularity</span>
  <span m="4297840">lemma,</span> <span m="4298410">that</span> <span m="4298620">when</span>
  <span m="4298800">you</span> <span m="4298890">look</span> <span m="4299100">at</span>
  <span m="4299220">an</span> <span m="4299370">object,</span> <span m="4299950">it's</span>
  <span m="4299970">important</span> <span m="4300330">to</span> <span m="4300450">decompose</span>
  <span m="4301050">it</span> <span m="4301290">into</span> <span m="4301650">its</span>
  <span m="4301800">structural</span> <span m="4302280">component</span> <span m="4303270">and</span>
  <span m="4303630">its</span> <span m="4304020">pseudo-random</span> <span m="4304800">component.</span></p><p><span
  m="4305970">So</span> <span m="4306120">this</span> <span m="4306780">dichotomy,</span>
  <span m="4307530">this</span> <span m="4307770">interplay</span> <span m="4308340">between</span>
  <span m="4308670">structure</span> <span m="4309210">and</span> <span m="4309330">pseudo</span>
  <span m="4309690">randomness,</span> <span m="4310590">is</span> <span m="4310800">a</span>
  <span m="4310890">key</span> <span m="4311520">theme</span> <span m="4311970">throughout</span>
  <span m="4312540">this</span> <span m="4312750">course.</span> <span m="4314190">And</span>
  <span m="4314340">it</span> <span m="4314400">showed</span> <span m="4314670">up</span>
  <span m="4314850">in</span> <span m="4315060">some</span> <span m="4315270">of</span>
  <span m="4315330">the</span> <span m="4315420">later</span> <span m="4315720">topics</span>
  <span m="4316170">as</span> <span m="4316360">well,</span> <span m="4316890">when</span>
  <span m="4317010">we</span> <span m="4317130">discussed</span> <span m="4318420">spectral</span>
  <span m="4318870">graph</span> <span m="4319140">theory,</span> <span m="4319920">quasi-randomness,</span>
  <span m="4321510">graph</span> <span m="4321840">limits,</span> <span m="4322830">and</span>
  <span m="4322950">also</span> <span m="4323250">in</span> <span m="4323340">the</span>
  <span m="4323430">later</span> <span m="4324540">Fourier</span> <span m="4324960">analytic</span>
  <span m="4325410">proof</span> <span m="4325800">of</span> <span m="4325950">Roth's</span>
  <span m="4326310">theorem.</span> <span m="4327300">All</span> <span m="4327450">of</span>
  <span m="4327540">these</span> <span m="4327720">proofs,</span> <span m="4328380">all</span>
  <span m="4328530">of</span> <span m="4328590">these</span> <span m="4328800">techniques,</span>
  <span m="4329490">involve</span> <span m="4329940">some</span> <span m="4330240">kind</span>
  <span m="4330510">of</span> <span m="4330600">interplay</span> <span m="4331380">between</span>
  <span m="4331740">structure</span> <span m="4332250">and</span> <span m="4332370">pseudo-randomness.</span></p><p><span
  m="4335990">In</span> <span m="4336080">the</span> <span m="4336560">past</span>
  <span m="4336920">month</span> <span m="4337160">or,</span> <span m="4337250">so</span>
  <span m="4337460">we've</span> <span m="4337580">been</span> <span m="4337700">looking</span>
  <span m="4338030">at</span> <span m="4338210">Freiman's</span> <span m="4338870">theorem,</span>
  <span m="4340280">this</span> <span m="4340610">key</span> <span m="4340850">result</span>
  <span m="4341240">in</span> <span m="4342110">additive</span> <span m="4342410">combinatorics</span>
  <span m="4343370">concerning</span> <span m="4343850">the</span> <span m="4343940">structure</span>
  <span m="4344840">of</span> <span m="4345410">sets</span> <span m="4345910">under</span>
  <span m="4346230">addition.</span> <span m="4347020">And</span> <span m="4347170">there,</span>
  <span m="4347720">we</span> <span m="4347900">also</span> <span m="4348110">saw</span>
  <span m="4348350">many</span> <span m="4348560">different</span> <span m="4348860">tools</span>
  <span m="4349250">that</span> <span m="4349370">came</span> <span m="4349640">up,</span>
  <span m="4350450">and</span> <span m="4350630">also</span> <span m="4350870">connections</span>
  <span m="4351410">I</span> <span m="4351500">mentioned</span> <span m="4352570">a</span>
  <span m="4352790">few</span> <span m="4352980">lectures</span> <span m="4353290">ago,</span>
  <span m="4353720">connections</span> <span m="4354230">to</span> <span m="4354410">really</span>
  <span m="4354620">important</span> <span m="4355040">results</span> <span m="4355490">in</span>
  <span m="4355880">geometry</span> <span m="4356640">to</span> <span m="4357110">group</span>
  <span m="4357380">theory.</span> <span m="4358220">And</span> <span m="4358600">it</span>
  <span m="4358790">really</span> <span m="4359030">extends</span> <span m="4359900">all</span>
  <span m="4360050">around.</span></p><p><span m="4361190">And</span> <span m="4361910">a</span>
  <span m="4361970">few</span> <span m="4362150">takeaways</span> <span m="4362660">from</span>
  <span m="4362840">this</span> <span m="4362990">course--</span> <span m="4363710">one</span>
  <span m="4363920">of</span> <span m="4364010">them</span> <span m="4364130">is</span>
  <span m="4364280">that</span> <span m="4365120">graph</span> <span m="4365420">theory,</span>
  <span m="4365930">additive</span> <span m="4366260">combinatorics,</span> <span
  m="4367260">they</span> <span m="4367430">are</span> <span m="4367520">not</span>
  <span m="4367820">isolated</span> <span m="4368450">subjects.</span> <span m="4369030">They're</span>
  <span m="4369170">connected</span> <span m="4369590">to</span> <span m="4370370">a</span>
  <span m="4370460">lot</span> <span m="4371030">within</span> <span m="4371330">mathematics.</span>
  <span m="4372300">And</span> <span m="4372320">that's</span> <span m="4372530">one</span>
  <span m="4372740">of</span> <span m="4372800">the</span> <span m="4372890">goals</span>
  <span m="4373220">I</span> <span m="4373280">want</span> <span m="4373490">to</span>
  <span m="4373550">show</span> <span m="4373820">you</span> <span m="4374060">in</span>
  <span m="4374360">this course,</span> <span m="4375170">is</span> <span m="4375380">to</span>
  <span m="4375830">show</span> <span m="4376250">these</span> <span m="4376460">connections</span>
  <span m="4377600">throughout</span> <span m="4378000">mathematics</span> <span m="4378560">and</span>
  <span m="4379370">some</span> <span m="4379730">to</span> <span m="4379940">analysis,</span>
  <span m="4380540">to</span> <span m="4380600">geometry,</span> <span m="4381170">to</span>
  <span m="4381320">topology.</span></p><p><span m="4382250">And</span> <span m="4383510">even</span>
  <span m="4383810">simple</span> <span m="4384200">questions</span> <span m="4385130">can</span>
  <span m="4385340">lead</span> <span m="4385550">to</span> <span m="4386870">really</span>
  <span m="4387230">deep</span> <span m="4387710">mathematics.</span> <span m="4388790">And</span>
  <span m="4388910">some</span> <span m="4389120">of</span> <span m="4389240">them</span>
  <span m="4389420">I</span> <span m="4389900">try</span> <span m="4390140">to</span>
  <span m="4390260">show</span> <span m="4390470">you,</span> <span m="4390560">try</span>
  <span m="4390720">to</span> <span m="4390800">hint</span> <span m="4390980">at</span>
  <span m="4391070">you,</span> <span m="4391280">or</span> <span m="4391730">at</span>
  <span m="4391790">least</span> <span m="4392030">I</span> <span m="4392090">mentioned</span>
  <span m="4392810">throughout</span> <span m="4393110">this</span> <span m="4393290">course.</span>
  <span m="4393980">And</span> <span m="4394970">what</span> <span m="4395420">we've</span>
  <span m="4395630">seen</span> <span m="4395930">so</span> <span m="4396110">far</span>
  <span m="4397130">is</span> <span m="4397850">just</span> <span m="4398120">the</span>
  <span m="4398360">tip</span> <span m="4398630">of</span> <span m="4398720">the</span>
  <span m="4398840">iceberg.</span></p><p><span m="4400220">And</span> <span m="4400670">there</span>
  <span m="4400860">is</span> <span m="4401480">a</span> <span m="4401570">lot</span>
  <span m="4401780">of</span> <span m="4401900">still</span> <span m="4402290">extremely</span>
  <span m="4402740">exciting</span> <span m="4403190">work</span> <span m="4403430">that's</span>
  <span m="4403760">to be</span> <span m="4403910">done.</span> <span m="4404600">And</span>
  <span m="4404720">I've</span> <span m="4404870">also</span> <span m="4405140">tried</span>
  <span m="4405350">to</span> <span m="4405410">emphasize</span> <span m="4406340">many</span>
  <span m="4406670">important</span> <span m="4407240">open</span> <span m="4407510">problems</span>
  <span m="4408500">that</span> <span m="4409430">have</span> <span m="4409550">yet</span>
  <span m="4409970">to</span> <span m="4410150">be</span> <span m="4410870">better</span>
  <span m="4411110">understood.</span> <span m="4412370">And</span> <span m="4412610">I</span>
  <span m="4412730">expect</span> <span m="4413320">in</span> <span m="4413600">some</span>
  <span m="4413810">future</span> <span m="4414200">iteration</span> <span m="4414680">of</span>
  <span m="4414770">this</span> <span m="4414950">course,</span> <span m="4416580">some</span>
  <span m="4416750">of</span> <span m="4416840">these</span> <span m="4416990">problems</span>
  <span m="4417350">will</span> <span m="4417440">be</span> <span m="4417560">resolved,</span>
  <span m="4418040">and</span> <span m="4418160">I</span> <span m="4418250">can</span>
  <span m="4418880">show</span> <span m="4419630">the</span> <span m="4419720">next</span>
  <span m="4420020">generation</span> <span m="4420590">of</span> <span m="4421040">students</span>
  <span m="4421460">in</span> <span m="4421550">your</span> <span m="4421670">seats</span>
  <span m="4422300">some</span> <span m="4422540">new</span> <span m="4422690">techniques,</span>
  <span m="4423330">new</span> <span m="4423380">methods,</span> <span m="4423740">and</span>
  <span m="4423830">new</span> <span m="4424010">theorems.</span></p><p><span m="4424880">And</span>
  <span m="4425030">I</span> <span m="4425090">expect</span> <span m="4425420">that</span>
  <span m="4425540">will</span> <span m="4425660">be</span> <span m="4425750">the</span>
  <span m="4425840">case.</span> <span m="4426210">This</span> <span m="4426290">is</span>
  <span m="4426350">a</span> <span m="4426380">very</span> <span m="4426590">exciting</span>
  <span m="4427040">area.</span> <span m="4427670">And</span> <span m="4427790">it's
  an</span> <span m="4427910">area</span> <span m="4428270">that</span> <span m="4428450">is</span>
  <span m="4428720">very</span> <span m="4428960">close</span> <span m="4429230">to</span>
  <span m="4429320">my</span> <span m="4429470">heart.</span> <span m="4430200">It's</span>
  <span m="4430250">something</span> <span m="4430550">that</span> <span m="4431000">I've</span>
  <span m="4431120">been</span> <span m="4431240">thinking</span> <span m="4431570">about</span>
  <span m="4432680">since</span> <span m="4433010">my</span> <span m="4433160">PhD.</span>
  <span m="4434170">The</span> <span m="4434540">bulk</span> <span m="4434810">of</span>
  <span m="4434900">my</span> <span m="4435410">research</span> <span m="4435800">work</span>
  <span m="4436250">revolves</span> <span m="4436730">around</span> <span m="4437300">better</span>
  <span m="4437570">understanding</span> <span m="4438110">connections</span> <span
  m="4438770">between</span> <span m="4439160">graph</span> <span m="4439460">theory,</span>
  <span m="4439760">on</span> <span m="4439880">one</span> <span m="4440060">hand,</span>
  <span m="4440660">and</span> <span m="4440810">additive</span> <span m="4441240">combinatorics</span>
  <span m="4442130">on</span> <span m="4442280">the</span> <span m="4442370">other</span>
  <span m="4442550">hand.</span> <span m="4443750">It's</span> <span m="4443810">been</span>
  <span m="4443960">really</span> <span m="4444140">fun</span> <span m="4444440">teaching</span>
  <span m="4444770">this</span> <span m="4444950">course,</span> <span m="4445220">and</span>
  <span m="4446030">happy</span> <span m="4446300">to</span> <span m="4446360">have</span>
  <span m="4446720">all</span> <span m="4446870">of</span> <span m="4446960">you</span>
  <span m="4447080">here.</span> <span m="4447680">Thank you.</span></p><p><span m="4448580">[APPLAUSE]</span></p><p>&nbsp;</p>
type: course
uid: 041b5e96b65771fa0e0b4b0a927db8ed

---
None