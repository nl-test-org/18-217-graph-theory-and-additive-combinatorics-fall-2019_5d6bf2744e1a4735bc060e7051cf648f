---
about_this_resource_text: "<p><strong>Description:</strong> Additive energy is a measure\
  \ of additive structure. Professor Zhao explains why a set with large additive energy\
  \ must have a large subset of small doubling. The proof is graph theoretic and uses\
  \ the dependent random choice method.\r\n\r\n</p>\r\n<p><strong>Instructor:</strong>\
  \ Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: MlYhHsq_tOU
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  title: Video-YouTube-Stream
  type: Video
  uid: 08b06dca739636005495066b89a27204
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/MlYhHsq_tOU/default.jpg
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e7d8fa987664ea36c084d8e44f552606
- id: 3Play-3PlayYouTubeid-MP4
  media_location: MlYhHsq_tOU
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 1533aa7af532d0d738b186bce3ee91ce
- id: MlYhHsq_tOU.srt
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-25-structure-of-set-addition-v-additive-energy-and-balog-szemeredi-gowers-theorem/MlYhHsq_tOU.srt
  title: 3play caption file
  type: null
  uid: e195c7d52caaa409b4e2d1dd54b0d383
- id: MlYhHsq_tOU.pdf
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-25-structure-of-set-addition-v-additive-energy-and-balog-szemeredi-gowers-theorem/MlYhHsq_tOU.pdf
  title: 3play pdf file
  type: null
  uid: e09a37cb5612c2097245156493d8105c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: a0afb9e607738ecd955bea747f7c16df
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 421477b0d5f355d55430167278957a02
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec25_300k.mp4
  parent_uid: 82880211e6a571b1a4a59e3e00745d16
  title: Video-Internet Archive-MP4
  type: Video
  uid: 76a131f7e920142cf6e30b2ae60eb4a7
inline_embed_id: 72408577lecture25structureofsetadditionvadditiveenergyandbalogszemerdigowerstheorem82718395
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-25-structure-of-set-addition-v-additive-energy-and-balog-szemeredi-gowers-theorem
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-25-structure-of-set-addition-v-additive-energy-and-balog-szemeredi-gowers-theorem
template_type: Tabbed
title: "Lecture 25: Structure of Set Addition V: Additive Energy and Balog-Szemer\xE9\
  di-Gowers Theorem\t"
transcript: <p><span m="17710">YUFEI ZHAO:</span> <span m="17785">For</span> <span
  m="17860">the</span> <span m="17920">past</span> <span m="18220">few</span> <span
  m="18370">lectures,</span> <span m="18950">we've</span> <span m="19000">been</span>
  <span m="19150">discussing</span> <span m="19780">the</span> <span m="19870">structure</span>
  <span m="20440">of</span> <span m="20500">set</span> <span m="20800">addition,</span>
  <span m="21310">and</span> <span m="21850">which</span> <span m="22090">culminated</span>
  <span m="22720">in</span> <span m="22870">the</span> <span m="22960">proof</span>
  <span m="23470">of</span> <span m="23650">Freiman's</span> <span m="24340">theorem.</span>
  <span m="25260">So</span> <span m="25420">this</span> <span m="25630">was</span>
  <span m="26400">a</span> <span m="26470">pretty</span> <span m="26920">big</span>
  <span m="27220">and</span> <span m="27340">central</span> <span m="27700">result</span>
  <span m="28270">in</span> <span m="28600">additive</span> <span m="28960">combinatorics,</span>
  <span m="29980">which</span> <span m="30160">gives</span> <span m="30460">you</span>
  <span m="30640">a</span> <span m="31030">complete</span> <span m="31420">characterization</span>
  <span m="32770">of</span> <span m="33040">sets</span> <span m="33520">with</span>
  <span m="33730">small</span> <span m="34150">doubling.</span> <span m="35500">Today,</span>
  <span m="35710">I</span> <span m="35800">want</span> <span m="35950">to</span> <span
  m="36040">look</span> <span m="36280">at</span> <span m="36760">a</span> <span m="36910">somewhat</span>
  <span m="37270">different</span> <span m="37630">issue</span> <span m="38320">also</span>
  <span m="38650">related</span> <span m="39010">to</span> <span m="39160">sets</span>
  <span m="39460">of</span> <span m="39550">small</span> <span m="39880">doubling,</span>
  <span m="40780">but</span> <span m="41500">this</span> <span m="41680">time</span>
  <span m="42310">we</span> <span m="42760">want</span> <span m="43060">to</span>
  <span m="43690">have</span> <span m="43930">a</span> <span m="44080">somewhat</span>
  <span m="44470">different</span> <span m="44860">characterization</span> <span m="46180">of</span>
  <span m="46630">what</span> <span m="47170">does</span> <span m="47350">it</span>
  <span m="47410">mean</span> <span m="47620">for</span> <span m="47870">a</span>
  <span m="47920">set</span> <span m="48190">to</span> <span m="48340">have</span>
  <span m="48760">lots</span> <span m="49180">of</span> <span m="49390">additive</span>
  <span m="49900">structure.</span></p><p><span m="51860">So</span> <span m="51910">in</span>
  <span m="52000">today's</span> <span m="52330">lecture,</span> <span m="52760">we're</span>
  <span m="52810">always</span> <span m="53110">going</span> <span m="53250">to</span>
  <span m="53320">be</span> <span m="53440">working</span> <span m="54520">in</span>
  <span m="54910">an</span> <span m="55030">Abelian</span> <span m="55470">group.</span>
  <span m="60450">Let me</span> <span m="60750">define</span> <span m="61230">the</span>
  <span m="61290">following</span> <span m="61950">quantity.</span> <span m="62990">Given</span>
  <span m="63330">sets</span> <span m="63590">A</span> <span m="63850">and</span>
  <span m="64110">B,</span> <span m="64739">we</span> <span m="64890">define</span>
  <span m="65310">the</span> <span m="66060">additive</span> <span m="66570">energy</span>
  <span m="69450">between</span> <span m="69780">A</span> <span m="70110">and</span>
  <span m="70380">B</span> <span m="70920">to</span> <span m="71070">be</span> <span
  m="74600">denoted</span> <span m="74970">by</span> <span m="75240">E</span> <span
  m="75500">of</span> <span m="75860">A and</span> <span m="76310">B.</span> <span
  m="76450">So</span> <span m="76550">A</span> <span m="76630">and</span> <span m="76880">B</span>
  <span m="77090">are</span> <span m="77180">subgroups.</span> <span m="77820">They're</span>
  <span m="77880">subsets</span> <span m="79140">of</span> <span m="79260">this</span>
  <span m="79830">arbitrary</span> <span m="80280">Abelian</span> <span m="80670">group.</span>
  <span m="81840">So</span> <span m="82090">E</span> <span m="82270">of</span> <span
  m="82680">A and</span> <span m="82950">B</span> <span m="83250">is</span> <span
  m="83400">defined</span> <span m="83790">to</span> <span m="83880">be</span> <span
  m="84000">the</span> <span m="84090">number</span> <span m="84480">of</span> <span
  m="84630">quadruples,</span> <span m="85710">a1,</span> <span m="86250">a2,</span>
  <span m="87210">b1,</span> <span m="87840">b2,</span> <span m="89060">where</span>
  <span m="89310">a1,</span> <span m="89820">a2</span> <span m="90630">are</span>
  <span m="90810">elements</span> <span m="91290">of</span> <span m="91530">A,</span>
  <span m="92100">and</span> <span m="92400">b1,</span> <span m="92820">b2</span>
  <span m="93210">are</span> <span m="93360">elements</span> <span m="93810">of</span>
  <span m="93890">B,</span> <span m="95370">such</span> <span m="95730">that</span>
  <span m="97200">a1</span> <span m="97680">plus</span> <span m="99150">b1</span>
  <span m="101310">equals</span> <span m="101700">to</span> <span m="102000">a2</span>
  <span m="102690">plus</span> <span m="103260">b2.</span></p><p><span m="108650">So</span>
  <span m="108770">the</span> <span m="108920">additive</span> <span m="109310">energy</span>
  <span m="111050">is</span> <span m="111560">the</span> <span m="112070">number</span>
  <span m="112610">of</span> <span m="113150">quadruples</span> <span m="114110">of</span>
  <span m="114290">these</span> <span m="114530">elements</span> <span m="115880">where</span>
  <span m="116330">you</span> <span m="116510">have</span> <span m="117230">this</span>
  <span m="117740">additive</span> <span m="118140">relation.</span> <span m="119510">And</span>
  <span m="119660">we</span> <span m="119810">would</span> <span m="119930">like</span>
  <span m="120080">to</span> <span m="120170">understand</span> <span m="121460">sets</span>
  <span m="122000">with</span> <span m="122390">large</span> <span m="123050">additive</span>
  <span m="123560">energy.</span> <span m="124790">So,</span> <span m="124910">intuitively,</span>
  <span m="125840">if</span> <span m="125990">you</span> <span m="126110">have</span>
  <span m="126410">lots</span> <span m="126800">of</span> <span m="126920">solutions</span>
  <span m="127460">to</span> <span m="127550">this</span> <span m="127760">equation</span>
  <span m="128270">in</span> <span m="128389">your</span> <span m="128539">sets,</span>
  <span m="129259">then</span> <span m="129590">the</span> <span m="129680">sets</span>
  <span m="130039">themselves</span> <span m="130520">should</span> <span m="130729">have</span>
  <span m="131150">lots</span> <span m="131630">of</span> <span m="131840">internal</span>
  <span m="132590">additive</span> <span m="133040">structure.</span> <span m="134590">So</span>
  <span m="134820">it's</span> <span m="135020">a</span> <span m="135080">different</span>
  <span m="135350">way</span> <span m="135890">of</span> <span m="136010">describing</span>
  <span m="136690">additive</span> <span m="137030">structure,</span> <span m="137920">and</span>
  <span m="138110">we'd</span> <span m="138290">like</span> <span m="138440">to</span>
  <span m="138530">understand</span> <span m="138920">how</span> <span m="139160">does</span>
  <span m="139400">this</span> <span m="139610">way</span> <span m="139820">of</span>
  <span m="140030">describing</span> <span m="140570">additive</span> <span m="140980">structure</span>
  <span m="141800">relate</span> <span m="142220">to</span> <span m="143690">things</span>
  <span m="143990">we've</span> <span m="144140">seen</span> <span m="144410">before,</span>
  <span m="144950">namely</span> <span m="145790">small</span> <span m="146150">doubling.</span></p><p><span
  m="150480">When</span> <span m="151260">you</span> <span m="151440">have</span>
  <span m="151740">not</span> <span m="152010">two</span> <span m="152280">sets</span>
  <span m="152610">but</span> <span m="152760">just</span> <span m="152970">one</span>
  <span m="153180">set--</span> <span m="153840">slightly</span> <span m="154260">easier</span>
  <span m="154560">to</span> <span m="154650">think</span> <span m="154860">about--</span>
  <span m="157170">we</span> <span m="157410">just</span> <span m="157680">write</span>
  <span m="157970">E</span> <span m="158120">of A.</span> <span m="160040">I</span>
  <span m="160120">mean</span> <span m="160350">E</span> <span m="160530">of</span>
  <span m="161370">A</span> <span m="161580">comma</span> <span m="162010">A.</span>
  <span m="162690">And</span> <span m="164450">these</span> <span m="164780">objects</span>
  <span m="165590">are</span> <span m="166100">analogous</span> <span m="166880">to</span>
  <span m="168830">4</span> <span m="169100">cycles</span> <span m="171710">in</span>
  <span m="171950">graph</span> <span m="172370">theory.</span> <span m="175150">Because</span>
  <span m="175570">if</span> <span m="175660">you</span> <span m="176080">about</span>
  <span m="176770">this</span> <span m="176950">expression</span> <span m="177460">here</span>
  <span m="178110">in</span> <span m="178370">a</span> <span m="178580">Cayley</span>
  <span m="179020">graph,</span> <span m="179830">let's</span> <span m="179980">say</span>
  <span m="180160">over</span> <span m="180710">F2,</span> <span m="181540">then</span>
  <span m="182050">this</span> <span m="182650">is</span> <span m="183670">the</span>
  <span m="183760">description</span> <span m="184360">of</span> <span m="184450">a</span>
  <span m="184540">4</span> <span m="184770">cycle.</span> <span m="185110">You</span>
  <span m="185200">go</span> <span m="185380">around</span> <span m="186130">4</span>
  <span m="186430">steps,</span> <span m="186820">and</span> <span m="186910">you</span>
  <span m="187000">come</span> <span m="187240">back</span> <span m="187480">to</span>
  <span m="187690">where</span> <span m="187870">you</span> <span m="188020">started</span>
  <span m="188380">from.</span> <span m="189460">So</span> <span m="189550">these</span>
  <span m="190270">objects</span> <span m="190780">are</span> <span m="190990">the</span>
  <span m="191700">analogs</span> <span m="192280">of</span> <span m="192400">4</span>
  <span m="192670">cycles.</span> <span m="193360">And</span> <span m="193480">we</span>
  <span m="193660">already</span> <span m="193990">saw</span> <span m="194410">in</span>
  <span m="194530">our</span> <span m="194620">discussion</span> <span m="195280">of</span>
  <span m="195760">quasi-randomness,</span> <span m="196720">and</span> <span m="196990">also</span>
  <span m="197260">elsewhere,</span> <span m="198020">that</span> <span m="198250">4</span>
  <span m="198520">cycles</span> <span m="198970">play an</span> <span m="199330">important</span>
  <span m="199810">role</span> <span m="200410">in</span> <span m="200860">graph</span>
  <span m="201190">theory.</span> <span m="202030">And,</span> <span m="202150">likewise,</span>
  <span m="202990">these</span> <span m="203320">additive</span> <span m="203680">energies</span>
  <span m="204160">are</span> <span m="204220">going</span> <span m="204400">to</span>
  <span m="204460">play</span> <span m="204700">an</span> <span m="204760">important</span>
  <span m="205180">role</span> <span m="205690">in</span> <span m="206170">describing</span>
  <span m="206770">sets</span> <span m="207190">with</span> <span m="207490">additive</span>
  <span m="207850">structure.</span></p><p><span m="213320">Consider</span> <span
  m="213770">the</span> <span m="213860">following</span> <span m="214280">quantity.</span>
  <span m="215570">We're</span> <span m="215690">going</span> <span m="215900">to</span>
  <span m="215990">let</span> <span m="216770">r sub A comma B</span> <span m="218946">of</span>
  <span m="219620">x</span> <span m="220310">to</span> <span m="220430">be</span>
  <span m="221150">the</span> <span m="221240">number</span> <span m="221720">of</span>
  <span m="221840">ways</span> <span m="222530">to</span> <span m="222710">write</span>
  <span m="223160">x</span> <span m="224120">as</span> <span m="224660">a</span> <span
  m="224870">plus</span> <span m="225230">b.</span> <span m="229710">So</span> <span
  m="230772">x</span> <span m="231350">equals</span> <span m="231640">to</span> <span
  m="232240">a</span> <span m="232620">plus</span> <span m="233000">b.</span> <span
  m="236080">So</span> <span m="236360">r sub A comma B</span> <span m="238040">of</span>
  <span m="238190">x</span> <span m="238510">is</span> <span m="238660">the</span>
  <span m="238730">number</span> <span m="239090">of</span> <span m="239210">ways</span>
  <span m="239750">I</span> <span m="239840">can</span> <span m="239990">write</span>
  <span m="240230">x</span> <span m="240510">as</span> <span m="241230">a</span> <span
  m="241340">plus</span> <span m="241580">b,</span> <span m="242040">where</span>
  <span m="242540">a</span> <span m="242660">comes</span> <span m="242930">from</span>
  <span m="243080">big</span> <span m="243260">A,</span> <span m="243710">little</span>
  <span m="243890">b</span> <span m="244040">comes</span> <span m="244280">from</span>
  <span m="244430">big</span> <span m="244610">B.</span> <span m="246050">Then,</span>
  <span m="247760">reinterpreting</span> <span m="248510">the</span> <span m="248570">formula</span>
  <span m="249110">up</span> <span m="249360">there,</span> <span m="250100">we</span>
  <span m="250190">see</span> <span m="250400">that</span> <span m="250550">the</span>
  <span m="250680">additive</span> <span m="251150">energy</span> <span m="251960">between</span>
  <span m="252350">two</span> <span m="252590">sets</span> <span m="252980">A and</span>
  <span m="253220">B</span> <span m="253830">is</span> <span m="253940">simply</span>
  <span m="254780">the</span> <span m="254870">sum</span> <span m="255470">of</span>
  <span m="255710">the</span> <span m="256430">squares</span> <span m="257360">of</span>
  <span m="257630">A--</span> <span m="258110">r sub A comma B.</span> <span m="261670">As</span>
  <span m="262070">x</span> <span m="262370">ranges</span> <span m="263510">over</span>
  <span m="263990">all</span> <span m="265250">elements</span> <span m="265730">of</span>
  <span m="265880">the</span> <span m="265970">group,</span> <span m="266630">we</span>
  <span m="267020">only</span> <span m="267260">need</span> <span m="267410">to</span>
  <span m="267500">take</span> <span m="267800">x</span> <span m="268670">in</span>
  <span m="268850">the</span> <span m="268940">sumset</span> <span m="269540">A</span>
  <span m="269660">plus</span> <span m="269960">B.</span></p><p><span m="274580">So</span>
  <span m="274700">the</span> <span m="274790">basic</span> <span m="275090">question,</span>
  <span m="275930">like</span> <span m="276590">when</span> <span m="276770">we</span>
  <span m="276920">discussed</span> <span m="278780">additive</span> <span m="279170">combinatorics,</span>
  <span m="279830">in</span> <span m="279920">the</span> <span m="280010">sense</span>
  <span m="280250">of</span> <span m="280460">when</span> <span m="280640">we</span>
  <span m="280760">discussed</span> <span m="281220">sets</span> <span m="281480">of</span>
  <span m="281570">small</span> <span m="281870">doubling,</span> <span m="283620">there</span>
  <span m="284000">we</span> <span m="284240">asked,</span> <span m="284750">if</span>
  <span m="284840">you</span> <span m="284900">have</span> <span m="285000">a</span>
  <span m="285030">set</span> <span m="285440">A of a</span> <span m="285530">certain</span>
  <span m="285830">size,</span> <span m="286160">how</span> <span m="286430">big</span>
  <span m="287300">can</span> <span m="287600">a</span> <span m="287720">plus</span>
  <span m="287990">a</span> <span m="288110">be?</span> <span m="289910">Here,</span>
  <span m="290210">let's</span> <span m="290390">ask</span> <span m="290570">the</span>
  <span m="290660">same.</span> <span m="291350">If</span> <span m="291470">I</span>
  <span m="291560">give</span> <span m="291740">you</span> <span m="291860">set</span>
  <span m="292200">A of</span> <span m="292530">a</span> <span m="292670">certain</span>
  <span m="292940">size,</span> <span m="293750">how</span> <span m="293990">big</span>
  <span m="294380">or</span> <span m="294500">how</span> <span m="294710">small</span>
  <span m="295490">can</span> <span m="297070">the</span> <span m="297280">additive</span>
  <span m="297700">energy</span> <span m="298600">of</span> <span m="298720">the</span>
  <span m="298810">set</span> <span m="299080">be?</span> <span m="300070">What's</span>
  <span m="300280">the</span> <span m="300850">most</span> <span m="301240">number
  of</span> <span m="301720">possible</span> <span m="302140">number</span> <span
  m="302440">of</span> <span m="302620">additive</span> <span m="302980">quadruples.</span>
  <span m="303520">What's</span> <span m="303700">the</span> <span m="303790">least</span>
  <span m="304090">possible</span> <span m="304570">number</span> <span m="304840">of</span>
  <span m="304960">additive</span> <span m="305350">quadruples?</span></p><p><span
  m="307760">There's</span> <span m="308020">some</span> <span m="308180">trivial</span>
  <span m="308570">bounds,</span> <span m="309680">just</span> <span m="309950">like</span>
  <span m="310190">in</span> <span m="310280">the</span> <span m="310370">case</span>
  <span m="310910">of</span> <span m="312190">sumsets.</span> <span m="317950">So</span>
  <span m="318090">what</span> <span m="318240">are</span> <span m="318330">some</span>
  <span m="318480">trivial</span> <span m="318880">bounds?</span> <span m="323660">On</span>
  <span m="323750">one</span> <span m="323930">hand,</span> <span m="324830">by</span>
  <span m="325190">taking</span> <span m="326270">a1</span> <span m="326780">equal</span>
  <span m="327050">to</span> <span m="327200">a2,</span> <span m="327650">and</span>
  <span m="327770">b2</span> <span m="328190">equal</span> <span m="328400">to</span>
  <span m="328520">b2,</span> <span m="329330">we</span> <span m="329510">see</span>
  <span m="329780">that</span> <span m="330620">the</span> <span m="330920">energy</span>
  <span m="331460">is</span> <span m="331850">always</span> <span m="332240">at</span>
  <span m="332330">least</span> <span m="332800">the</span> <span m="332920">square</span>
  <span m="333620">of</span> <span m="333770">the</span> <span m="333860">size</span>
  <span m="334280">of</span> <span m="334370">A.</span> <span m="336790">On</span>
  <span m="336940">the</span> <span m="337060">other</span> <span m="337240">hand,</span>
  <span m="337970">if</span> <span m="338080">I</span> <span m="338320">fix</span>
  <span m="339070">three</span> <span m="339370">of</span> <span m="339490">the</span>
  <span m="339580">four</span> <span m="339850">elements,</span> <span m="340300">then</span>
  <span m="340420">the</span> <span m="340510">fourth</span> <span m="340870">element</span>
  <span m="341290">is</span> <span m="341500">determined.</span> <span m="342750">So</span>
  <span m="343060">the</span> <span m="343270">upper</span> <span m="343480">bound</span>
  <span m="344640">is</span> <span m="344980">cube</span> <span m="345670">of</span>
  <span m="346240">the</span> <span m="346330">size</span> <span m="346720">of</span>
  <span m="346810">A.</span></p><p><span m="349030">And</span> <span m="349450">you</span>
  <span m="349540">convince</span> <span m="349900">yourself</span> <span m="350280">that,</span>
  <span m="350800">except</span> <span m="351220">up</span> <span m="351430">to</span>
  <span m="351790">maybe</span> <span m="352060">a</span> <span m="352090">constant</span>
  <span m="352540">factors,</span> <span m="353410">this</span> <span m="354340">is</span>
  <span m="354580">the</span> <span m="354670">best</span> <span m="354970">possible</span>
  <span m="355630">general</span> <span m="356170">upper</span> <span m="356440">and</span>
  <span m="356530">lower</span> <span m="356740">bound.</span> <span m="358300">Similar</span>
  <span m="358690">situation</span> <span m="359230">with</span> <span m="359460">sumsets,</span>
  <span m="360160">where</span> <span m="360310">you</span> <span m="360400">have</span>
  <span m="361060">lower</span> <span m="361270">bound</span> <span m="361510">linear,</span>
  <span m="361870">upper</span> <span m="362080">bound</span> <span m="362320">quadratic.</span>
  <span m="364550">Which</span> <span m="364660">is</span> <span m="364770">the</span>
  <span m="364840">side</span> <span m="365170">with</span> <span m="365390">additive</span>
  <span m="365740">structure?</span> <span m="367948">So</span> <span m="368380">if</span>
  <span m="368500">you</span> <span m="368560">have</span> <span m="368770">lots</span>
  <span m="369100">of</span> <span m="369340">additive</span> <span m="369760">structure,</span>
  <span m="370250">you</span> <span m="370360">have</span> <span m="370510">high</span>
  <span m="370900">energy.</span> <span m="372650">So</span> <span m="373750">this</span>
  <span m="374050">range</span> <span m="374500">is</span> <span m="374650">when</span>
  <span m="374790">you</span> <span m="374860">have</span> <span m="375070">lots</span>
  <span m="375370">of</span> <span m="375490">additive</span> <span m="375940">structure.</span>
  <span m="376930">And</span> <span m="377050">we</span> <span m="377200">would</span>
  <span m="377320">like</span> <span m="377470">to</span> <span m="377590">understand,</span>
  <span m="378940">what</span> <span m="379120">can</span> <span m="379240">you</span>
  <span m="379360">say</span> <span m="379960">about</span> <span m="380260">a</span>
  <span m="380320">set</span> <span m="380800">with</span> <span m="381730">high</span>
  <span m="382360">additive</span> <span m="382930">energy?</span></p><p><span m="387460">Well,</span>
  <span m="388000">what</span> <span m="388210">are</span> <span m="388300">some</span>
  <span m="388480">examples</span> <span m="388990">of</span> <span m="389080">sets</span>
  <span m="389350">with</span> <span m="389500">high</span> <span m="389710">additive</span>
  <span m="390100">energy?</span> <span m="392030">It</span> <span m="392130">turns</span>
  <span m="392230">out</span> <span m="392710">that</span> <span m="393370">if</span>
  <span m="393490">you</span> <span m="393610">have</span> <span m="393790">a</span>
  <span m="393850">set</span> <span m="394330">that</span> <span m="394450">has</span>
  <span m="394730">small</span> <span m="395230">doubling,</span> <span m="398260">then,</span>
  <span m="398680">automatically,</span> <span m="399640">it</span> <span m="399760">implies</span>
  <span m="400810">large</span> <span m="401290">additive</span> <span m="401710">energy.</span>
  <span m="409030">So,</span> <span m="409220">in</span> <span m="409340">particular,</span>
  <span m="411140">intervals,</span> <span m="412250">or</span> <span m="413130">GAPs,</span>
  <span m="413960">or a</span> <span m="414080">large</span> <span m="414380">subset</span>
  <span m="414740">of</span> <span m="414800">GAPs,</span> <span m="415410">or</span>
  <span m="415620">all</span> <span m="415820">these</span> <span m="416030">examples</span>
  <span m="416450">that</span> <span m="416540">we</span> <span m="416660">saw--</span>
  <span m="417110">in</span> <span m="417170">fact,</span> <span m="417480">these</span>
  <span m="417500">are</span> <span m="417590">all</span> <span m="417710">the</span>
  <span m="417800">examples</span> <span m="418370">coming</span> <span m="418640">from</span>
  <span m="418820">Freiman's</span> <span m="419250">theorem.</span> <span m="420590">Also,</span>
  <span m="421070">arbitrary</span> <span m="421490">groups.</span> <span m="421790">You</span>
  <span m="421850">can</span> <span m="422010">have</span> <span m="422120">subgroups.</span>
  <span m="422840">And</span> <span m="423020">so</span> <span m="423330">all</span>
  <span m="423410">of</span> <span m="423470">these</span> <span m="423650">examples</span>
  <span m="424100">have</span> <span m="424430">large</span> <span m="424850">additive</span>
  <span m="425240">energy.</span> <span m="428620">So</span> <span m="428740">let</span>
  <span m="428830">me--</span> <span m="429160">I'll</span> <span m="429370">you</span>
  <span m="429430">the</span> <span m="429520">proof</span> <span m="429850">just</span>
  <span m="430030">in</span> <span m="430140">a</span> <span m="430180">second.</span>
  <span m="430490">It's</span> <span m="430580">not</span> <span m="430740">hard.</span></p><p><span
  m="431740">But</span> <span m="431920">the</span> <span m="432190">real</span> <span
  m="432460">question</span> <span m="432850">is,</span> <span m="433150">what</span>
  <span m="433360">about</span> <span m="433540">the</span> <span m="433630">converse?</span>
  <span m="434330">So</span> <span m="434430">can</span> <span m="434590">you</span>
  <span m="434680">see</span> <span m="434860">much</span> <span m="435550">in</span>
  <span m="435670">the</span> <span m="435760">reverse</span> <span m="436210">direction?</span>
  <span m="437500">But,</span> <span m="437620">first,</span> <span m="438130">let</span>
  <span m="438250">me</span> <span m="438460">show</span> <span m="438700">you</span>
  <span m="439000">this</span> <span m="439240">claim</span> <span m="439620">that</span>
  <span m="439770">small</span> <span m="440230">doubling</span> <span m="440670">implies</span>
  <span m="441150">large</span> <span m="441520">additive</span> <span m="442000">energy.</span>
  <span m="443690">Well,</span> <span m="444190">if</span> <span m="444430">you</span>
  <span m="445000">have</span> <span m="445330">small</span> <span m="445750">doubling,</span>
  <span m="446560">if</span> <span m="446740">a</span> <span m="446950">plus</span>
  <span m="447310">A</span> <span m="447640">is size,</span> <span m="448310">at</span>
  <span m="448430">most,</span> <span m="448690">k</span> <span m="448960">times</span>
  <span m="449350">the</span> <span m="449410">size</span> <span m="449740">of</span>
  <span m="449860">A,</span> <span m="451480">then</span> <span m="453940">it</span>
  <span m="454030">turns</span> <span m="454330">out</span> <span m="454480">the</span>
  <span m="454900">additive</span> <span m="455470">energy</span> <span m="456040">of</span>
  <span m="456370">A</span> <span m="457030">is</span> <span m="457810">at</span>
  <span m="457960">least</span> <span m="459930">the</span> <span m="460120">maximum</span>
  <span m="460660">possible,</span> <span m="462080">which</span> <span m="462130">is</span>
  <span m="462250">A</span> <span m="462370">cubed</span> <span m="463060">divided</span>
  <span m="463510">by</span> <span m="463780">k.</span> <span m="466370">So</span>
  <span m="466500">that's</span> <span m="467360">within</span> <span m="467660">a</span>
  <span m="467720">constant</span> <span m="468170">factor</span> <span m="468620">of</span>
  <span m="468800">the</span> <span m="468890">maximum.</span> <span m="469480">It's</span>
  <span m="469520">pretty</span> <span m="469790">large.</span> <span m="470450">If</span>
  <span m="470570">you</span> <span m="470660">have</span> <span m="471050">small</span>
  <span m="471350">doubling,</span> <span m="471740">then</span> <span m="471920">large</span>
  <span m="472370">additive</span> <span m="472820">energy.</span></p><p><span m="474900">So</span>
  <span m="475060">let's</span> <span m="475180">see</span> <span m="475390">the</span>
  <span m="475480">proof.</span> <span m="477580">So</span> <span m="477760">you</span>
  <span m="477880">can</span> <span m="478060">often</span> <span m="478330">tell</span>
  <span m="478570">how</span> <span m="478780">hard</span> <span m="479080">a</span>
  <span m="479140">proof</span> <span m="479440">is</span> <span m="479680">by</span>
  <span m="479980">how</span> <span m="480190">simple</span> <span m="480580">the</span>
  <span m="480680">statement</span> <span m="481150">is,</span> <span m="481450">although</span>
  <span m="481630">that's</span> <span m="481810">not</span> <span m="482020">always</span>
  <span m="482320">the</span> <span m="482410">case,</span> <span m="482710">as</span>
  <span m="482890">we've</span> <span m="483040">seen</span> <span m="483280">with</span>
  <span m="483430">some</span> <span m="483640">of</span> <span m="483790">our</span>
  <span m="484690">theorems,</span> <span m="485080">like</span> <span m="485260">Plunnecke's</span>
  <span m="485740">inequality.</span> <span m="487660">But</span> <span m="487840">in</span>
  <span m="487960">this</span> <span m="488110">case,</span> <span m="488320">it</span>
  <span m="488380">turns</span> <span m="488620">out</span> <span m="488710">to</span>
  <span m="488800">be</span> <span m="488920">fairly</span> <span m="489190">simple.</span>
  <span m="489990">So</span> <span m="490630">we</span> <span m="490780">see</span>
  <span m="490960">that</span> <span m="492070">r sub A comma A</span> <span m="493780">is</span>
  <span m="494410">supported</span> <span m="495910">on</span> <span m="496210">A</span>
  <span m="496330">plus</span> <span m="496640">A.</span> <span m="500620">So</span>
  <span m="501970">we</span> <span m="502060">use</span> <span m="502240">Cauchy-Schwarz</span>
  <span m="504280">to</span> <span m="505610">write--</span> <span m="506250">so,</span>
  <span m="506370">first,</span> <span m="506700">we</span> <span m="506850">write</span>
  <span m="508080">additive</span> <span m="508500">energy</span> <span m="509430">in</span>
  <span m="509550">terms</span> <span m="509970">of</span> <span m="512070">the</span>
  <span m="512760">sum</span> <span m="513419">of</span> <span m="513539">the</span>
  <span m="513630">squares</span> <span m="514200">of</span> <span m="514710">these</span>
  <span m="515010">r's.</span> <span m="518260">And</span> <span m="518530">now,</span>
  <span m="518929">by</span> <span m="519230">Cauchy-Schwarz,</span> <span m="521419">we</span>
  <span m="521570">find</span> <span m="524630">that</span> <span m="525800">you</span>
  <span m="525920">can</span> <span m="526160">replace</span> <span m="526670">the</span>
  <span m="526760">sum</span> <span m="527240">of</span> <span m="527390">the</span>
  <span m="527630">squared</span> <span m="528320">r's</span> <span m="528830">by</span>
  <span m="529040">the</span> <span m="529130">sum</span> <span m="529520">of</span>
  <span m="529640">the</span> <span m="529760">r's.</span> <span m="530510">But</span>
  <span m="530660">now</span> <span m="530900">the</span> <span m="531830">key</span>
  <span m="532580">point</span> <span m="532970">here</span> <span m="533840">is</span>
  <span m="534050">that</span> <span m="534170">we</span> <span m="534350">take</span>
  <span m="534730">out</span> <span m="535370">this</span> <span m="535610">factor</span>
  <span m="536660">coming</span> <span m="536900">from</span> <span m="537050">Cauchy-Schwarz,</span>
  <span m="537920">which</span> <span m="538100">is</span> <span m="538190">only</span>
  <span m="539090">A</span> <span m="539240">plus</span> <span m="539600">A.</span>
  <span m="540050">So</span> <span m="540380">if</span> <span m="540740">the</span>
  <span m="540910">support</span> <span m="541175">size</span> <span m="541440">is</span>
  <span m="541730">small,</span> <span m="542180">we</span> <span m="542390">gain</span>
  <span m="542810">in</span> <span m="542990">this</span> <span m="543140">step.</span></p><p><span
  m="546310">But</span> <span m="546430">what</span> <span m="546610">is</span> <span
  m="547930">the</span> <span m="548050">sum</span> <span m="548890">of</span> <span
  m="549400">r's?</span> <span m="551110">I</span> <span m="551180">mean,</span> <span
  m="551710">r</span> <span m="551920">of</span> <span m="552070">x</span> <span m="552310">is
  just</span> <span m="552550">number</span> <span m="552880">of</span> <span m="552940">ways</span>
  <span m="553210">to</span> <span m="553300">write</span> <span m="553560">x</span>
  <span m="553850">as</span> <span m="554630">little</span> <span m="554860">a1</span>
  <span m="555370">plus</span> <span m="555620">little</span> <span m="555930">ab--</span>
  <span m="556320">little</span> <span m="556620">a2.</span> <span m="557800">So</span>
  <span m="558040">if</span> <span m="558160">I</span> <span m="558230">sum</span>
  <span m="558670">over</span> <span m="559000">all</span> <span m="560140">x,</span>
  <span m="561050">I'm</span> <span m="561250">just</span> <span m="561550">looking</span>
  <span m="561880">at</span> <span m="562300">different</span> <span m="562660">two</span>
  <span m="562930">ways--</span> <span m="563500">we're</span> <span m="563680">just</span>
  <span m="563830">looking</span> <span m="564100">at</span> <span m="564430">ways</span>
  <span m="564700">of</span> <span m="564790">picking</span> <span m="565740">an</span>
  <span m="566170">ordered</span> <span m="566590">pair</span> <span m="567370">from</span>
  <span m="568090">A.</span> <span m="568810">So</span> <span m="569500">this</span>
  <span m="569680">last</span> <span m="570010">expression</span> <span m="570820">is</span>
  <span m="571420">equal</span> <span m="571810">to</span> <span m="572710">the</span>
  <span m="573580">size</span> <span m="573940">of</span> <span m="574060">A</span>
  <span m="574210">to</span> <span m="574330">power</span> <span m="574660">4</span>
  <span m="575200">divided</span> <span m="575620">by</span> <span m="577870">A</span>
  <span m="577970">plus</span> <span m="578280">A.</span> <span m="579242">And</span>
  <span m="579650">now</span> <span m="579830">we</span> <span m="579980">use</span>
  <span m="580310">that</span> <span m="580680">A has</span> <span m="581030">small</span>
  <span m="581450">doubling</span> <span m="582290">to</span> <span m="582440">conclude</span>
  <span m="583430">that</span> <span m="583590">the</span> <span m="583640">final</span>
  <span m="584000">quantity</span> <span m="584930">is</span> <span m="585590">at</span>
  <span m="585650">least</span> <span m="586130">A</span> <span m="586280">cubed</span>
  <span m="586850">divided</span> <span m="587270">by</span> <span m="587510">k.</span>
  <span m="593820">So</span> <span m="594260">we</span> <span m="594350">see</span>
  <span m="594740">small</span> <span m="595160">doubling</span> <span m="595760">implies</span>
  <span m="596420">large</span> <span m="597020">additive</span> <span m="597470">energy.</span>
  <span m="598760">And this</span> <span m="599090">kind</span> <span m="599270">of</span>
  <span m="599330">makes</span> <span m="599480">sense.</span> <span m="599720">If</span>
  <span m="599840">your</span> <span m="600540">set</span> <span m="601190">doesn't</span>
  <span m="601610">expand,</span> <span m="602660">then</span> <span m="603680">there</span>
  <span m="603830">are</span> <span m="603950">many</span> <span m="604310">collisions</span>
  <span m="605270">of</span> <span m="606350">sums.</span> <span m="608180">And</span>
  <span m="608510">so</span> <span m="608750">you</span> <span m="608870">must</span>
  <span m="609110">have</span> <span m="609380">lots</span> <span m="609650">of</span>
  <span m="609710">solutions</span> <span m="610280">to</span> <span m="610430">that</span>
  <span m="610610">equation</span> <span m="611110">up</span> <span m="611360">there.</span></p><p><span
  m="613220">But</span> <span m="613370">what</span> <span m="613520">about</span>
  <span m="613700">the</span> <span m="613790">converse?</span> <span m="615230">If</span>
  <span m="615350">I</span> <span m="615440">give</span> <span m="615710">you</span>
  <span m="615950">a</span> <span m="616010">set</span> <span m="616400">with</span>
  <span m="616640">large</span> <span m="617240">additive</span> <span m="617660">energy,</span>
  <span m="618440">must</span> <span m="618770">it</span> <span m="619160">necessarily</span>
  <span m="619820">have</span> <span m="620240">small</span> <span m="620820">doubling?</span>
  <span m="624922">Oh.</span> <span m="627270">Let</span> <span m="627360">me</span>
  <span m="627450">show</span> <span m="627600">you</span> <span m="627660">an</span>
  <span m="627750">example.</span> <span m="630760">So,</span> <span m="631990">well--</span>
  <span m="633060">so</span> <span m="633210">a</span> <span m="633240">large</span>
  <span m="635280">additive</span> <span m="636570">energy,</span> <span m="638320">does
  it</span> <span m="638560">imply</span> <span m="639120">small</span> <span m="644680">doubling?</span>
  <span m="647680">So</span> <span m="647960">consider</span> <span m="648390">the</span>
  <span m="648480">following</span> <span m="648930">example,</span> <span m="649890">where</span>
  <span m="650730">you</span> <span m="650850">take</span> <span m="651150">a</span>
  <span m="651210">set</span> <span m="651540">A</span> <span m="651870">which</span>
  <span m="652590">is</span> <span m="652710">a</span> <span m="652770">combination,</span>
  <span m="653610">is</span> <span m="653880">a</span> <span m="654030">union</span>
  <span m="654450">of</span> <span m="654570">a</span> <span m="654630">set</span>
  <span m="655110">with</span> <span m="655320">small</span> <span m="655710">doubling</span>
  <span m="656970">plus</span> <span m="657630">a</span> <span m="657720">bunch</span>
  <span m="658140">of</span> <span m="660240">elements</span> <span m="661110">without</span>
  <span m="662490">additive</span> <span m="662910">structure.</span></p><p><span
  m="670170">So</span> <span m="670250">I</span> <span m="670310">take</span> <span
  m="670600">a</span> <span m="670730">set</span> <span m="671090">with</span> <span
  m="671270">small</span> <span m="671570">doubling</span> <span m="672230">plus</span>
  <span m="672500">a</span> <span m="672530">bunch</span> <span m="672770">of</span>
  <span m="672920">elements</span> <span m="673610">without</span> <span m="674000">additive</span>
  <span m="674360">structure.</span> <span m="676940">Then</span> <span m="677870">it</span>
  <span m="677960">has</span> <span m="678290">large</span> <span m="678650">additive</span>
  <span m="679040">energy,</span> <span m="680620">just</span> <span m="680860">coming</span>
  <span m="681190">from</span> <span m="682240">this</span> <span m="682450">interval</span>
  <span m="683020">itself.</span> <span m="685120">So</span> <span m="685300">the</span>
  <span m="685900">energy</span> <span m="686470">of</span> <span m="687460">A</span>
  <span m="687880">is</span> <span m="690520">order</span> <span m="691090">N</span>
  <span m="691270">cubed.</span> <span m="691990">N</span> <span m="692380">is</span>
  <span m="692600">the</span> <span m="692660">number</span> <span m="692890">of</span>
  <span m="692980">elements.</span> <span m="694630">What</span> <span m="694810">about</span>
  <span m="697330">A</span> <span m="697450">plus</span> <span m="697810">A?</span>
  <span m="698320">Well,</span> <span m="698470">for</span> <span m="698620">A</span>
  <span m="698770">plus</span> <span m="699100">A,</span> <span m="699710">this</span>
  <span m="699940">part</span> <span m="700300">doesn't--</span> <span m="701650">that's</span>
  <span m="701890">the</span> <span m="701980">part</span> <span m="702160">that</span>
  <span m="702280">contributes,</span> <span m="703120">or</span> <span m="703320">the</span>
  <span m="705480">part</span> <span m="705810">of</span> <span m="705900">this</span>
  <span m="705990">A</span> <span m="706350">without</span> <span m="706860">additive</span>
  <span m="707160">structure.</span> <span m="708270">And</span> <span m="709080">we</span>
  <span m="709200">see</span> <span m="709380">that</span> <span m="710460">the</span>
  <span m="710550">size</span> <span m="710940">of</span> <span m="711030">A</span>
  <span m="711150">plus</span> <span m="711480">A</span> <span m="712250">is</span>
  <span m="712710">quadratic</span> <span m="714180">in</span> <span m="714300">the</span>
  <span m="714360">size</span> <span m="714660">of</span> <span m="714750">A.</span></p><p><span
  m="716830">So,</span> <span m="717040">unfortunately,</span> <span m="717560">the</span>
  <span m="718580">converse</span> <span m="719760">fails.</span> <span m="720470">So</span>
  <span m="720590">you</span> <span m="720680">can</span> <span m="720830">have</span>
  <span m="721040">sets</span> <span m="721730">that</span> <span m="721850">have</span>
  <span m="722120">large</span> <span m="722830">additive</span> <span m="723980">energy</span>
  <span m="725060">and</span> <span m="725210">also</span> <span m="725480">large</span>
  <span m="725960">doubling.</span> <span m="727590">But,</span> <span m="727740">you</span>
  <span m="727830">see,</span> <span m="728910">the</span> <span m="729000">reason</span>
  <span m="729330">why</span> <span m="729560">this</span> <span m="729740">has</span>
  <span m="730020">large</span> <span m="730350">additive</span> <span m="730680">energy</span>
  <span m="731100">is</span> <span m="731280">because</span> <span m="731610">there</span>
  <span m="731850">is</span> <span m="732060">a</span> <span m="732120">very</span>
  <span m="732360">highly</span> <span m="732810">structured</span> <span m="733620">additively</span>
  <span m="734110">structured</span> <span m="734640">piece</span> <span m="735000">of</span>
  <span m="735120">it.</span> <span m="735990">And,</span> <span m="736350">somehow,</span>
  <span m="736650">we</span> <span m="736770">want</span> <span m="737010">to</span>
  <span m="737820">forget</span> <span m="738210">about</span> <span m="738510">this</span>
  <span m="738720">extra</span> <span m="739050">garbage.</span> <span m="740290">And</span>
  <span m="740490">that's</span> <span m="741150">part</span> <span m="741450">of</span>
  <span m="741510">the</span> <span m="741600">reason</span> <span m="742710">why</span>
  <span m="742890">the</span> <span m="742980">converse</span> <span m="743370">is</span>
  <span m="743490">not</span> <span m="743670">true.</span></p><p><span m="744790">So</span>
  <span m="745530">we</span> <span m="745740">would</span> <span m="745860">like</span>
  <span m="746070">a</span> <span m="746130">statement</span> <span m="746670">that</span>
  <span m="746820">says</span> <span m="747120">that</span> <span m="747300">if</span>
  <span m="747510">you</span> <span m="747660">have</span> <span m="747930">large</span>
  <span m="748380">additive</span> <span m="748710">energy,</span> <span m="749670">then</span>
  <span m="750150">it</span> <span m="750270">must</span> <span m="750600">come</span>
  <span m="750990">from</span> <span m="751380">some</span> <span m="752070">highly</span>
  <span m="752490">structured</span> <span m="753000">piece</span> <span m="753630">that</span>
  <span m="753750">has</span> <span m="754050">small</span> <span m="754500">doubling.</span>
  <span m="756380">And</span> <span m="756520">that</span> <span m="756700">is</span>
  <span m="756820">true,</span> <span m="757450">and</span> <span m="757570">that's</span>
  <span m="757750">the</span> <span m="757840">content</span> <span m="758260">of</span>
  <span m="758320">the</span> <span m="758410">Balog-Szemeredi-Gowers</span> <span
  m="759590">theorem,</span> <span m="760210">which</span> <span m="760540">is</span>
  <span m="760690">the</span> <span m="760780">main</span> <span m="761440">topic</span>
  <span m="761860">today.</span> <span m="763660">So</span> <span m="763780">the</span>
  <span m="764300">Balog-Szemeredi-Gowers</span> <span m="766360">theorem</span> <span
  m="769910">says</span> <span m="770390">that</span> <span m="771200">if</span> <span
  m="771530">you</span> <span m="771680">have</span> <span m="771890">a</span> <span
  m="771950">set--</span> <span m="772760">so</span> <span m="772880">we're</span>
  <span m="773090">working</span> <span m="773690">always</span> <span m="774080">in</span>
  <span m="774200">some</span> <span m="774440">arbitrary</span> <span m="774980">Abelian</span>
  <span m="775420">group.</span> <span m="776060">If</span> <span m="776210">you</span>
  <span m="776300">have</span> <span m="776420">a</span> <span m="776480">set</span>
  <span m="776870">with</span> <span m="777200">large</span> <span m="779000">energy,</span>
  <span m="780650">then</span> <span m="782450">there</span> <span m="782630">exists</span>
  <span m="783410">some</span> <span m="783770">subset</span> <span m="784400">A</span>
  <span m="784550">prime</span> <span m="785030">of</span> <span m="785210">A</span>
  <span m="786890">such</span> <span m="787280">that</span> <span m="788300">A</span>
  <span m="788480">prime</span> <span m="789620">is</span> <span m="790040">a</span>
  <span m="790100">fairly</span> <span m="790490">large</span> <span m="790910">proportion</span>
  <span m="791630">of</span> <span m="791830">A.</span> <span m="793460">And</span>
  <span m="793710">here,</span> <span m="794570">by</span> <span m="794750">large</span>
  <span m="795200">I</span> <span m="795290">mean</span> <span m="795950">up</span>
  <span m="796100">to</span> <span m="796490">polynomial</span> <span m="797120">changes</span>
  <span m="797750">in</span> <span m="797900">the</span> <span m="798020">error</span>
  <span m="798260">parameters.</span></p><p><span m="802010">So</span> <span m="802160">this</span>
  <span m="802340">A</span> <span m="802460">prime</span> <span m="803130">is</span>
  <span m="803330">such</span> <span m="803570">that</span> <span m="805880">A</span>
  <span m="806030">prime</span> <span m="806670">has</span> <span m="807290">small</span>
  <span m="807860">doubling.</span> <span m="814340">If</span> <span m="814680">you</span>
  <span m="814780">have</span> <span m="815110">large</span> <span m="815530">additive</span>
  <span m="815920">energy,</span> <span m="816760">then</span> <span m="816970">I</span>
  <span m="817060">can</span> <span m="817210">pick</span> <span m="817420">out</span>
  <span m="817540">a</span> <span m="817600">large</span> <span m="817990">piece</span>
  <span m="819190">with</span> <span m="819760">small</span> <span m="820600">doubling</span>
  <span m="820960">constant,</span> <span m="821860">and I</span> <span m="822250">only</span>
  <span m="822520">loose</span> <span m="823270">a</span> <span m="823330">polynomial</span>
  <span m="824200">in</span> <span m="824740">the</span> <span m="825190">error</span>
  <span m="825490">factors.</span> <span m="828490">So</span> <span m="828610">that's</span>
  <span m="828820">the</span> <span m="828880">Balog-Szemeredi-Gowers</span> <span
  m="829820">theorem,</span> <span m="830075">and</span> <span m="831130">it</span>
  <span m="831670">describes</span> <span m="832330">this</span> <span m="832660">example</span>
  <span m="833200">up</span> <span m="833660">here.</span> <span m="836420">Any</span>
  <span m="836500">questions</span> <span m="836890">about</span> <span m="837080">the</span>
  <span m="837140">statement?</span></p><p><span m="841200">So</span> <span m="841620">what</span>
  <span m="842070">I</span> <span m="842130">will</span> <span m="842250">actually</span>
  <span m="842610">show</span> <span m="842820">you</span> <span m="843090">is</span>
  <span m="843360">a</span> <span m="843480">slight</span> <span m="843900">variant,</span>
  <span m="844695">actually</span> <span m="844970">a</span> <span m="845040">more</span>
  <span m="845250">general</span> <span m="846180">statement,</span> <span m="847110">where,</span>
  <span m="847500">instead</span> <span m="847830">of</span> <span m="847920">having</span>
  <span m="848190">one</span> <span m="848460">set,</span> <span m="848830">we're</span>
  <span m="848880">going</span> <span m="849090">to</span> <span m="849150">have</span>
  <span m="849330">two</span> <span m="849570">sets.</span> <span m="852720">So</span>
  <span m="852980">here's</span> <span m="854010">Balog-Szemeredi-Gowers</span> <span
  m="855060">theorem</span> <span m="856550">version</span> <span m="856880">2,</span>
  <span m="858740">where</span> <span m="859940">now</span> <span m="860720">we</span>
  <span m="860930">have</span> <span m="862520">two</span> <span m="862730">sets.</span>
  <span m="865460">Again,</span> <span m="865880">A and</span> <span m="866090">B</span>
  <span m="866300">are--</span> <span m="867050">I'm</span> <span m="867350">not</span>
  <span m="867470">going</span> <span m="867590">to</span> <span m="867680">write</span>
  <span m="867860">any--</span> <span m="868640">I'm not</span> <span m="868780">going</span>
  <span m="868890">to</span> <span m="868970">write</span> <span m="869150">it</span>
  <span m="869210">in</span> <span m="869270">this</span> <span m="869400">lecture,</span>
  <span m="869690">but</span> <span m="869810">A and B</span> <span m="870140">are</span>
  <span m="870280">always</span> <span m="870530">subsets</span> <span m="871040">of</span>
  <span m="871130">some</span> <span m="871400">arbitrary</span> <span m="871850">Abelian</span>
  <span m="872210">group.</span> <span m="872480">So</span> <span m="872950">A and</span>
  <span m="873110">B</span> <span m="873770">both</span> <span m="874100">have size</span>
  <span m="874440">of,</span> <span m="874530">at most,</span> <span m="874790">n,</span>
  <span m="875480">and</span> <span m="877181">the</span> <span m="877610">energy</span>
  <span m="878000">between</span> <span m="878420">A</span> <span m="878570">and</span>
  <span m="878670">B</span> <span m="879300">is</span> <span m="880070">large.</span>
  <span m="884670">Then</span> <span m="886680">there</span> <span m="886860">exists</span>
  <span m="888300">a</span> <span m="888450">subset</span> <span m="889080">A</span>
  <span m="889230">prime</span> <span m="889650">of</span> <span m="889800">A,</span>
  <span m="891130">B</span> <span m="891390">prime</span> <span m="891770">of</span>
  <span m="891870">B</span> <span m="893250">such</span> <span m="893580">that</span>
  <span m="895650">both</span> <span m="896250">A</span> <span m="896910">prime</span>
  <span m="897750">and</span> <span m="897900">B</span> <span m="898110">prime</span>
  <span m="899130">are</span> <span m="899820">large</span> <span m="900270">fractions</span>
  <span m="902730">of</span> <span m="902950">their</span> <span m="903720">parent</span>
  <span m="904110">set,</span> <span m="905250">and</span> <span m="905520">such</span>
  <span m="905850">that</span> <span m="908460">A</span> <span m="908580">prime</span>
  <span m="909300">plus</span> <span m="909570">B</span> <span m="909750">prime</span>
  <span m="911760">is</span> <span m="913710">not</span> <span m="914070">too</span>
  <span m="914280">much</span> <span m="914520">bigger</span> <span m="915120">than</span>
  <span m="915640">n.</span></p><p><span m="921170">It's</span> <span m="921320">not</span>
  <span m="921590">so</span> <span m="921950">obvious</span> <span m="922460">why</span>
  <span m="923360">the</span> <span m="923450">second</span> <span m="923810">version</span>
  <span m="924150">implies</span> <span m="924680">the</span> <span m="924770">first</span>
  <span m="925130">version.</span> <span m="926020">So</span> <span m="926180">you</span>
  <span m="926240">can</span> <span m="926390">say,</span> <span m="926540">well,</span>
  <span m="926720">take</span> <span m="927050">A and</span> <span m="927320">B</span>
  <span m="927500">to</span> <span m="927590">be</span> <span m="927740">the</span>
  <span m="927800">same.</span> <span m="929030">But</span> <span m="929180">then</span>
  <span m="929330">the</span> <span m="929420">conclusion</span> <span m="930410">gives</span>
  <span m="930710">you</span> <span m="931580">possibly</span> <span m="932030">two</span>
  <span m="932300">different</span> <span m="932690">subsets,</span> <span m="933290">A</span>
  <span m="933410">prime</span> <span m="933800">and</span> <span m="933890">B</span>
  <span m="934070">prime.</span> <span m="936200">But</span> <span m="937010">the</span>
  <span m="937130">first</span> <span m="937520">version,</span> <span m="938270">I</span>
  <span m="938570">only</span> <span m="938840">want one</span> <span m="939320">subset</span>
  <span m="939980">that</span> <span m="940150">has</span> <span m="940370">small</span>
  <span m="940700">doubling.</span> <span m="943320">So,</span> <span m="943780">fortunately,</span>
  <span m="944610">the</span> <span m="944700">second</span> <span m="945000">version</span>
  <span m="945270">does</span> <span m="945540">imply</span> <span m="945900">the</span>
  <span m="945990">first</span> <span m="946320">version.</span> <span m="947930">So</span>
  <span m="947950">let's</span> <span m="948130">see</span> <span m="948280">why.</span></p><p><span
  m="954020">The</span> <span m="954110">second</span> <span m="954470">version</span>
  <span m="954800">implies</span> <span m="955130">the</span> <span m="955190">first</span>
  <span m="955460">version</span> <span m="956240">because,</span> <span m="957740">if</span>
  <span m="958130">we--</span> <span m="963090">so</span> <span m="963680">there's</span>
  <span m="964190">a</span> <span m="964250">tool</span> <span m="964550">that</span>
  <span m="964670">we</span> <span m="964820">introduced</span> <span m="966350">early</span>
  <span m="966590">on</span> <span m="966770">when</span> <span m="966920">we</span>
  <span m="967130">discussed</span> <span m="967580">Freiman's</span> <span m="968020">theorem,</span>
  <span m="968630">and</span> <span m="968780">this</span> <span m="969130">is</span>
  <span m="969320">the</span> <span m="969860">Ruzsa</span> <span m="970250">triangle</span>
  <span m="970790">inequality.</span> <span m="974390">So</span> <span m="974520">the</span>
  <span m="974610">spirit</span> <span m="975000">of</span> <span m="975060">Ruzsa</span>
  <span m="975370">triangle</span> <span m="975780">inequality</span> <span m="976410">is</span>
  <span m="976900">it</span> <span m="977010">allows</span> <span m="977370">you</span>
  <span m="977520">to</span> <span m="977820">relate,</span> <span m="978900">to</span>
  <span m="979050">sort</span> <span m="979200">of</span> <span m="979500">go</span>
  <span m="979680">back</span> <span m="979890">and</span> <span m="980010">forth</span>
  <span m="980280">between</span> <span m="980610">different</span> <span m="981090">sumsets</span>
  <span m="981390">in</span> <span m="981750">different</span> <span m="982080">sets.</span>
  <span m="983010">So</span> <span m="983130">by</span> <span m="983310">Ruzsa</span>
  <span m="983610">triangle</span> <span m="984060">inequality,</span> <span m="987000">if</span>
  <span m="989630">we</span> <span m="989780">apply</span> <span m="990320">the</span>
  <span m="990440">second</span> <span m="990830">version</span> <span m="991250">with</span>
  <span m="991640">A</span> <span m="992000">equals</span> <span m="992300">to</span>
  <span m="992410">B,</span> <span m="994250">then--</span> <span m="997750">and</span>
  <span m="998160">we</span> <span m="998280">pick</span> <span m="998550">out</span>
  <span m="998680">this</span> <span m="998850">A</span> <span m="998970">prime</span>
  <span m="999240">and</span> <span m="999330">B</span> <span m="999480">prime,</span>
  <span m="1000290">then</span> <span m="1000440">we</span> <span m="1000530">see</span>
  <span m="1000680">that</span> <span m="1000860">A</span> <span m="1001010">prime</span>
  <span m="1001550">plus</span> <span m="1001910">A</span> <span m="1002030">prime</span>
  <span m="1003050">is,</span> <span m="1003710">at</span> <span m="1003860">most,</span>
  <span m="1005780">A</span> <span m="1005930">prime</span> <span m="1007070">plus</span>
  <span m="1009170">B</span> <span m="1009290">prime</span> <span m="1010890">squared</span>
  <span m="1012630">over</span> <span m="1013650">B</span> <span m="1013770">prime.</span></p><p><span
  m="1014370">Well,</span> <span m="1014790">actually,</span> <span m="1015030">this</span>
  <span m="1015240">uses</span> <span m="1015570">the--</span> <span m="1016290">vice
  versa</span> <span m="1016710">it</span> <span m="1016800">uses</span> <span m="1017100">a</span>
  <span m="1017160">slightly</span> <span m="1017520">stronger</span> <span m="1017970">version</span>
  <span m="1018420">that</span> <span m="1018570">we</span> <span m="1018960">had</span>
  <span m="1019110">to</span> <span m="1019200">use</span> <span m="1019890">Plunnecke-Ruzsa</span>
  <span m="1021310">key</span> <span m="1021750">lemma</span> <span m="1021910">to
  prove.</span> <span m="1022650">But</span> <span m="1022830">you</span> <span m="1023250">can</span>
  <span m="1023400">come</span> <span m="1023580">up--</span> <span m="1024089">I</span>
  <span m="1024119">mean,</span> <span m="1024240">if</span> <span m="1024329">you</span>
  <span m="1024390">don't</span> <span m="1024540">care</span> <span m="1024750">about</span>
  <span m="1025380">the</span> <span m="1025660">precise</span> <span m="1026430">loss</span>
  <span m="1026730">in</span> <span m="1026790">the</span> <span m="1026849">polynomial</span>
  <span m="1027359">factors,</span> <span m="1027910">you</span> <span m="1028010">can</span>
  <span m="1028109">also</span> <span m="1029040">use</span> <span m="1029250">the</span>
  <span m="1029310">basic</span> <span m="1029780">Ruzsa</span> <span m="1029970">triangle</span>
  <span m="1030369">inequality</span> <span m="1030780">to</span> <span m="1031109">deduce</span>
  <span m="1031550">a</span> <span m="1031589">similar</span> <span m="1032010">statement.</span>
  <span m="1033270">This</span> <span m="1033450">is</span> <span m="1033569">easier</span>
  <span m="1033869">to</span> <span m="1033990">deduce.</span> <span m="1034920">So</span>
  <span m="1035010">you</span> <span m="1035099">have</span> <span m="1035250">that.</span></p><p><span
  m="1036300">And</span> <span m="1037710">now,</span> <span m="1038130">the</span>
  <span m="1038280">second</span> <span m="1038700">version</span> <span m="1039060">tells</span>
  <span m="1039390">you</span> <span m="1039990">that</span> <span m="1040650">the</span>
  <span m="1041040">numerator</span> <span m="1041355">is,</span> <span m="1041670">at</span>
  <span m="1041930">most,</span> <span m="1042480">poly</span> <span m="1042780">kn,</span>
  <span m="1044150">and</span> <span m="1044400">the</span> <span m="1044520">denominator</span>
  <span m="1046079">is,</span> <span m="1047069">at</span> <span m="1047220">most--</span>
  <span m="1047550">at</span> <span m="1047700">least,</span> <span m="1050340">n</span>
  <span m="1050580">divided</span> <span m="1050970">by</span> <span m="1051090">poly</span>
  <span m="1051570">k.</span> <span m="1053170">Remember,</span> <span m="1055370">over</span>
  <span m="1055580">here,</span> <span m="1056660">to</span> <span m="1056870">get</span>
  <span m="1058040">this</span> <span m="1058280">hypothesis,</span> <span m="1059460">we</span>
  <span m="1059780">automatically</span> <span m="1060440">have</span> <span m="1061145">that</span>
  <span m="1061430">the</span> <span m="1061520">size</span> <span m="1061970">of</span>
  <span m="1062090">A and</span> <span m="1062330">B</span> <span m="1063170">are</span>
  <span m="1063410">not</span> <span m="1065830">two</span> <span m="1066010">much</span>
  <span m="1066220">smaller</span> <span m="1066760">than</span> <span m="1067240">n.</span>
  <span m="1067580">Or</span> <span m="1067910">else</span> <span m="1068170">this</span>
  <span m="1068380">cannot</span> <span m="1068680">be</span> <span m="1068800">true.</span>
  <span m="1070700">So</span> <span m="1071510">putting</span> <span m="1071990">all</span>
  <span m="1072110">these</span> <span m="1072350">estimates</span> <span m="1072770">together,</span>
  <span m="1076375">we get</span> <span m="1076830">that.</span> <span m="1078200">So</span>
  <span m="1078500">these</span> <span m="1078710">two</span> <span m="1078890">versions,</span>
  <span m="1079430">they</span> <span m="1079550">are</span> <span m="1079940">equivalent</span>
  <span m="1080690">to</span> <span m="1081050">each</span> <span m="1081260">other.</span>
  <span m="1082960">Second</span> <span m="1083150">version</span> <span m="1083400">implies</span>
  <span m="1083720">the</span> <span m="1083780">first.</span> <span m="1084080">The</span>
  <span m="1084350">second</span> <span m="1084650">one</span> <span m="1084800">is</span>
  <span m="1085100">stronger.</span> <span m="1086240">The</span> <span m="1086300">first</span>
  <span m="1086570">one</span> <span m="1086840">is</span> <span m="1087560">slightly</span>
  <span m="1087860">more</span> <span m="1088010">useful.</span> <span m="1088460">They're</span>
  <span m="1088670">not</span> <span m="1088880">necessarily</span> <span m="1089330">equivalent,</span>
  <span m="1089750">but</span> <span m="1089840">the</span> <span m="1089900">second</span>
  <span m="1090170">one</span> <span m="1090290">is</span> <span m="1090350">stronger.</span>
  <span m="1093190">Any</span> <span m="1093340">questions?</span> <span m="1096370">All</span>
  <span m="1096820">right.</span></p><p><span m="1097910">So</span> <span m="1098000">this</span>
  <span m="1098180">is</span> <span m="1098270">a</span> <span m="1098330">Balog-Szemeredi-Gowers</span>
  <span m="1099250">theorem.</span> <span m="1099680">So</span> <span m="1099990">the</span>
  <span m="1100130">content</span> <span m="1100610">of</span> <span m="1100910">today's</span>
  <span m="1101270">lecture</span> <span m="1101570">is</span> <span m="1101720">to</span>
  <span m="1102080">show</span> <span m="1102320">you</span> <span m="1102470">how</span>
  <span m="1102590">to</span> <span m="1102690">prove</span> <span m="1103160">this</span>
  <span m="1103400">theorem.</span> <span m="1104930">A</span> <span m="1105230">remark</span>
  <span m="1105500">about</span> <span m="1105770">the</span> <span m="1105890">naming</span>
  <span m="1106340">of</span> <span m="1106430">this</span> <span m="1106640">theorem.</span>
  <span m="1106940">So</span> <span m="1107180">you</span> <span m="1107270">might</span>
  <span m="1107440">notice</span> <span m="1107780">that</span> <span m="1108080">these
  three</span> <span m="1108470">letters</span> <span m="1108770">do</span> <span
  m="1108890">not</span> <span m="1109100">coming</span> <span m="1109460">in</span>
  <span m="1109670">alphabetical</span> <span m="1110030">order.</span> <span m="1112010">And</span>
  <span m="1112130">the</span> <span m="1112190">reason</span> <span m="1112490">is</span>
  <span m="1112610">that</span> <span m="1112760">this</span> <span m="1112940">theorem</span>
  <span m="1113210">was</span> <span m="1113390">initially</span> <span m="1113780">approved</span>
  <span m="1114110">by</span> <span m="1114260">Balog</span> <span m="1114650">and</span>
  <span m="1114740">Szemeredi,</span> <span m="1115580">but</span> <span m="1115910">using</span>
  <span m="1117380">a</span> <span m="1117440">more</span> <span m="1118220">involved</span>
  <span m="1119300">method</span> <span m="1120020">that</span> <span m="1120560">didn't</span>
  <span m="1120890">give</span> <span m="1121220">polynomial</span> <span m="1121880">high</span>
  <span m="1122020">bounds.</span> <span m="1123470">And</span> <span m="1123590">Gowers,</span>
  <span m="1124520">in</span> <span m="1124750">his</span> <span m="1124880">proof</span>
  <span m="1125420">of</span> <span m="1126140">Szemeredi's</span> <span m="1126800">theorem,</span>
  <span m="1127190">his</span> <span m="1127340">new</span> <span m="1127520">proof</span>
  <span m="1127790">of</span> <span m="1127850">Szemeredi's</span> <span m="1128300">theorem</span>
  <span m="1128580">with</span> <span m="1128720">good</span> <span m="1128930">bounds,</span>
  <span m="1129530">he</span> <span m="1129710">required--</span> <span m="1131030">well,</span>
  <span m="1131220">he</span> <span m="1131360">looked</span> <span m="1131570">into</span>
  <span m="1131810">this</span> <span m="1132040">theorem</span> <span m="1132470">and</span>
  <span m="1132590">gave</span> <span m="1132800">a</span> <span m="1132860">new</span>
  <span m="1133040">proof</span> <span m="1134270">that</span> <span m="1134420">resulted</span>
  <span m="1134930">in</span> <span m="1135110">this</span> <span m="1135320">polynomial</span>
  <span m="1135950">type</span> <span m="1136220">bounds.</span> <span m="1136990">And</span>
  <span m="1137400">it</span> <span m="1137630">is</span> <span m="1138260">that</span>
  <span m="1138470">idea</span> <span m="1138800">that</span> <span m="1138950">we're</span>
  <span m="1139070">going</span> <span m="1139170">to</span> <span m="1139280">see</span>
  <span m="1139430">today.</span></p><p><span m="1149700">So</span> <span m="1149880">this</span>
  <span m="1150030">course</span> <span m="1150270">is</span> <span m="1150360">called</span>
  <span m="1150570">graph</span> <span m="1150900">theory</span> <span m="1151170">and</span>
  <span m="1151290">additive</span> <span m="1151650">combinatorics.</span> <span
  m="1152850">And</span> <span m="1153000">the</span> <span m="1153090">last</span>
  <span m="1153360">two</span> <span m="1153690">topics</span> <span m="1154230">of</span>
  <span m="1154320">this</span> <span m="1154500">course--</span> <span m="1155490">today</span>
  <span m="1155790">being</span> <span m="1156180">Balog-Szemeredi-Gowers,</span>
  <span m="1157680">and</span> <span m="1157800">tomorrow</span> <span m="1158340">we're</span>
  <span m="1158520">going</span> <span m="1158670">to</span> <span m="1158760">see</span>
  <span m="1159600">sum-product</span> <span m="1160380">problem--</span> <span m="1160740">are</span>
  <span m="1161160">both</span> <span m="1161400">great</span> <span m="1161670">examples</span>
  <span m="1162750">of</span> <span m="1162930">problems</span> <span m="1163500">in</span>
  <span m="1163590">additive</span> <span m="1163950">combinatorics</span> <span m="1164700">where</span>
  <span m="1165330">tools</span> <span m="1165690">from</span> <span m="1165870">graph</span>
  <span m="1166200">theory</span> <span m="1166740">play</span> <span m="1167040">an</span>
  <span m="1167130">important</span> <span m="1167580">role</span> <span m="1168210">in</span>
  <span m="1168330">their</span> <span m="1168450">solutions.</span> <span m="1169960">So</span>
  <span m="1170040">it's</span> <span m="1170970">a</span> <span m="1171030">nice</span>
  <span m="1171390">combination</span> <span m="1172140">of</span> <span m="1172260">the</span>
  <span m="1172380">subject</span> <span m="1172830">where</span> <span m="1172980">we</span>
  <span m="1173220">see</span> <span m="1173910">both</span> <span m="1174180">topics</span>
  <span m="1174750">at</span> <span m="1174870">the</span> <span m="1174930">same</span>
  <span m="1175200">time.</span></p><p><span m="1176350">So</span> <span m="1176370">I</span>
  <span m="1176430">want</span> <span m="1176580">to</span> <span m="1176640">show</span>
  <span m="1176820">you</span> <span m="1176910">the</span> <span m="1177000">proof</span>
  <span m="1177330">of</span> <span m="1177750">Balog-Szemeredi-Gowers,</span> <span
  m="1179190">and</span> <span m="1179370">the</span> <span m="1179430">proof</span>
  <span m="1179790">goes</span> <span m="1180180">via</span> <span m="1180510">a</span>
  <span m="1180750">graph</span> <span m="1181340">analog.</span> <span m="1181890">So</span>
  <span m="1182370">I'm</span> <span m="1182520">going</span> <span m="1182670">to</span>
  <span m="1182760">state</span> <span m="1183030">for</span> <span m="1183210">you</span>
  <span m="1183420">a</span> <span m="1183480">graphical</span> <span m="1184110">version</span>
  <span m="1184860">of</span> <span m="1185070">the</span> <span m="1185190">Balog-Szemeredi-Gowers</span>
  <span m="1186300">theorem.</span> <span m="1188960">And</span> <span m="1189080">it</span>
  <span m="1189140">goes</span> <span m="1189350">like</span> <span m="1189530">this.</span>
  <span m="1190520">If</span> <span m="1191000">G</span> <span m="1191660">is</span>
  <span m="1191830">a</span> <span m="1192060">bipartite</span> <span m="1192500">graph</span>
  <span m="1195900">between</span> <span m="1197970">vertex</span> <span m="1198390">sets</span>
  <span m="1201110">A</span> <span m="1201570">and</span> <span m="1202050">B--</span>
  <span m="1202860">and</span> <span m="1203010">here</span> <span m="1203400">A and</span>
  <span m="1203640">B</span> <span m="1203820">are</span> <span m="1203940">still</span>
  <span m="1204330">subsets</span> <span m="1205140">of</span> <span m="1205350">the</span>
  <span m="1205550">Abelian</span> <span m="1205900">group--</span> <span m="1217740">we</span>
  <span m="1217890">define</span> <span m="1219060">this</span> <span m="1219480">restricted</span>
  <span m="1220170">sumset,</span> <span m="1221970">A</span> <span m="1222720">plus
  sub G</span> <span m="1223800">of</span> <span m="1223950">B,</span> <span m="1224910">to</span>
  <span m="1225060">be</span> <span m="1227940">the</span> <span m="1228160">set</span>
  <span m="1228540">of</span> <span m="1228960">sums</span> <span m="1231360">where</span>
  <span m="1232110">I'm</span> <span m="1232320">only</span> <span m="1233820">taking</span>
  <span m="1234180">sums</span> <span m="1234960">across</span> <span m="1235680">edges</span>
  <span m="1239560">in</span> <span m="1239780">g.</span></p><p><span m="1244540">So,</span>
  <span m="1244670">in</span> <span m="1244760">particular,</span> <span m="1245270">if</span>
  <span m="1245390">G</span> <span m="1245750">is</span> <span m="1245900">the</span>
  <span m="1246050">complete</span> <span m="1246560">bipartite</span> <span m="1247070">graph,</span>
  <span m="1247500">then</span> <span m="1247670">this</span> <span m="1248030">is</span>
  <span m="1248210">the</span> <span m="1248330">usual</span> <span m="1248870">sumset.</span>
  <span m="1250100">But</span> <span m="1250280">now</span> <span m="1250850">I</span>
  <span m="1251000">may</span> <span m="1251240">allow</span> <span m="1251540">G</span>
  <span m="1251840">to</span> <span m="1251960">be</span> <span m="1252710">a</span>
  <span m="1253700">subset</span> <span m="1254390">of</span> <span m="1254600">the</span>
  <span m="1255020">complete</span> <span m="1255440">bipartite</span> <span m="1255920">graph.</span>
  <span m="1256220">So</span> <span m="1257060">only</span> <span m="1257300">taking</span>
  <span m="1257570">some</span> <span m="1257870">but</span> <span m="1257990">not</span>
  <span m="1258170">all</span> <span m="1258410">of</span> <span m="1258530">the--</span>
  <span m="1259430">only</span> <span m="1259640">taking--</span> <span m="1259970">yes,</span>
  <span m="1260060">some</span> <span m="1260420">of</span> <span m="1260530">this</span>
  <span m="1260780">sums</span> <span m="1261200">but</span> <span m="1261350">not</span>
  <span m="1261560">all</span> <span m="1261710">of</span> <span m="1261770">them.</span></p><p><span
  m="1264600">The</span> <span m="1264680">graphical</span> <span m="1265250">version</span>
  <span m="1265850">of</span> <span m="1266420">Balog-Szemeredi-Gowers</span> <span
  m="1272940">says</span> <span m="1274290">that</span> <span m="1275930">if</span>
  <span m="1276270">you</span> <span m="1276480">have</span> <span m="1277305">A</span>
  <span m="1277650">and</span> <span m="1277950">B</span> <span m="1280842">be</span>
  <span m="1281280">subsets</span> <span m="1282090">of</span> <span m="1282590">an</span>
  <span m="1282660">Abelian</span> <span m="1282960">group,</span> <span m="1283290">both</span>
  <span m="1283620">having</span> <span m="1283890">size,</span> <span m="1284190">at</span>
  <span m="1284280">most,</span> <span m="1284550">n,</span> <span m="1285930">and</span>
  <span m="1286770">G</span> <span m="1287610">is</span> <span m="1287910">a</span>
  <span m="1288060">bipartite</span> <span m="1288630">graph</span> <span m="1291370">between</span>
  <span m="1292850">A</span> <span m="1293320">and</span> <span m="1293590">B,</span>
  <span m="1295770">such</span> <span m="1296050">that</span> <span m="1298590">G</span>
  <span m="1298890">has</span> <span m="1299490">lots</span> <span m="1299820">of</span>
  <span m="1299910">edges,</span> <span m="1300680">has</span> <span m="1300870">at</span>
  <span m="1300930">least</span> <span m="1301800">n</span> <span m="1301980">squared</span>
  <span m="1302460">over</span> <span m="1302690">k</span> <span m="1303180">edges.</span>
  <span m="1307290">If</span> <span m="1309570">the</span> <span m="1309780">restricted</span>
  <span m="1310590">sumset</span> <span m="1311310">between</span> <span m="1311730">A
  and</span> <span m="1311970">B</span> <span m="1313650">is</span> <span m="1314760">small--</span>
  <span m="1316090">So</span> <span m="1317340">here</span> <span m="1317670">we're</span>
  <span m="1317850">not</span> <span m="1318570">looking</span> <span m="1319200">at</span>
  <span m="1319680">all</span> <span m="1319920">the</span> <span m="1320070">sums</span>
  <span m="1320760">but</span> <span m="1321420">a</span> <span m="1321450">large</span>
  <span m="1321840">fraction</span> <span m="1322470">of</span> <span m="1322590">the</span>
  <span m="1322680">possible</span> <span m="1323130">pairwise</span> <span m="1323520">sums.</span>
  <span m="1324540">If</span> <span m="1324690">that</span> <span m="1324920">sumset</span>
  <span m="1325630">has</span> <span m="1325780">small</span> <span m="1326160">size,</span>
  <span m="1326860">this</span> <span m="1327040">is</span> <span m="1327090">kind</span>
  <span m="1327290">of</span> <span m="1327360">like</span> <span m="1327510">a</span>
  <span m="1327570">restricted</span> <span m="1328200">doubling</span> <span m="1328530">constant.</span>
  <span m="1330210">Then</span> <span m="1333180">there</span> <span m="1333420">exists</span>
  <span m="1334950">A</span> <span m="1335130">prime,</span> <span m="1335610">subset</span>
  <span m="1336090">of</span> <span m="1336210">A,</span> <span m="1336960">B</span>
  <span m="1337140">prime,</span> <span m="1337500">subset</span> <span m="1337950">of</span>
  <span m="1338070">B,</span> <span m="1341850">with</span> <span m="1344040">A</span>
  <span m="1344190">prime</span> <span m="1344640">and</span> <span m="1344730">B</span>
  <span m="1344910">prime</span> <span m="1346530">both</span> <span m="1348030">fairly</span>
  <span m="1348510">large</span> <span m="1348900">fractions</span> <span m="1349680">of</span>
  <span m="1349830">their</span> <span m="1350070">parent</span> <span m="1350490">set,</span>
  <span m="1352830">and</span> <span m="1353100">such</span> <span m="1353400">that</span>
  <span m="1353820">the</span> <span m="1354120">unrestricted</span> <span m="1354930">sumset</span>
  <span m="1355890">between</span> <span m="1356310">A</span> <span m="1356430">prime</span>
  <span m="1356760">and</span> <span m="1356850">B</span> <span m="1356970">prime</span>
  <span m="1357990">is</span> <span m="1359340">not</span> <span m="1359670">too</span>
  <span m="1359910">large.</span></p><p><span m="1368020">So</span> <span m="1368800">let</span>
  <span m="1368890">me</span> <span m="1369520">say</span> <span m="1369730">it</span>
  <span m="1369790">again.</span> <span m="1370390">So</span> <span m="1370510">we</span>
  <span m="1370640">have</span> <span m="1370830">a</span> <span m="1371710">fairly</span>
  <span m="1372100">dense--</span> <span m="1372760">so a</span> <span m="1373060">constant</span>
  <span m="1373900">fraction</span> <span m="1374620">edge</span> <span m="1374900">density,</span>
  <span m="1375180">a</span> <span m="1375280">fairly</span> <span m="1375580">dense</span>
  <span m="1376180">bipartite</span> <span m="1376780">graph</span> <span m="1377110">between</span>
  <span m="1378100">A</span> <span m="1378520">and</span> <span m="1378760">B.</span>
  <span m="1379060">A and</span> <span m="1379270">B</span> <span m="1379480">are</span>
  <span m="1379930">subsets</span> <span m="1380470">of</span> <span m="1380560">the</span>
  <span m="1380650">Abelian</span> <span m="1381010">group.</span> <span m="1382660">Then--</span>
  <span m="1383500">and</span> <span m="1383980">such</span> <span m="1384280">that</span>
  <span m="1385180">the</span> <span m="1385450">restricted</span> <span m="1386140">sumset</span>
  <span m="1386620">is</span> <span m="1386710">small.</span> <span m="1388700">Then</span>
  <span m="1388810">I</span> <span m="1388870">can</span> <span m="1389980">restrict</span>
  <span m="1390460">A</span> <span m="1390730">and</span> <span m="1391030">B</span>
  <span m="1391510">to</span> <span m="1391840">subsets,</span> <span m="1392680">fairly</span>
  <span m="1393070">large</span> <span m="1393400">subsets,</span> <span m="1394840">so</span>
  <span m="1395020">that</span> <span m="1395180">the</span> <span m="1395260">complete</span>
  <span m="1395980">sumset</span> <span m="1396640">between</span> <span m="1397800">the</span>
  <span m="1397900">subsets</span> <span m="1398670">A</span> <span m="1398800">prime</span>
  <span m="1399070">and</span> <span m="1399160">B</span> <span m="1399280">prime</span>
  <span m="1400330">is</span> <span m="1400840">small.</span> <span m="1406180">Let</span>
  <span m="1406270">me</span> <span m="1406390">show</span> <span m="1406540">you</span>
  <span m="1407290">why</span> <span m="1407650">the</span> <span m="1407800">graphical</span>
  <span m="1408280">version</span> <span m="1408700">of</span> <span m="1408880">BSG</span>
  <span m="1409720">implies</span> <span m="1410510">the</span> <span m="1411040">version</span>
  <span m="1411370">of</span> <span m="1411460">BSG</span> <span m="1412180">I</span>
  <span m="1412360">stated</span> <span m="1412960">up</span> <span m="1413110">there.</span></p><p><span
  m="1430630">But,</span> <span m="1431140">so</span> <span m="1431220">why</span>
  <span m="1431460">do</span> <span m="1431550">we</span> <span m="1431670">care</span>
  <span m="1431880">about</span> <span m="1432060">this</span> <span m="1432240">graphical</span>
  <span m="1432690">version?</span> <span m="1434511">Well,</span> <span m="1435000">suppose</span>
  <span m="1436110">we--</span> <span m="1437620">so</span> <span m="1437760">we</span>
  <span m="1437880">have</span> <span m="1438060">all</span> <span m="1438180">of</span>
  <span m="1438270">these</span> <span m="1438510">hypotheses.</span> <span m="1439530">Let's</span>
  <span m="1439800">write--</span> <span m="1445920">so</span> <span m="1446140">we</span>
  <span m="1446280">have</span> <span m="1446430">all</span> <span m="1446520">of</span>
  <span m="1446590">those</span> <span m="1446880">hypotheses</span> <span m="1447450">up</span>
  <span m="1447560">there.</span> <span m="1448030">So</span> <span m="1448050">let's</span>
  <span m="1448260">write</span> <span m="1448680">r</span> <span m="1449910">to</span>
  <span m="1450030">be</span> <span m="1451050">r sub A comma B,</span> <span m="1452580">so</span>
  <span m="1452730">I</span> <span m="1452790">don't</span> <span m="1452920">have</span>
  <span m="1453050">to</span> <span m="1453150">carry</span> <span m="1453480">the</span>
  <span m="1453630">subscripts</span> <span m="1454320">all</span> <span m="1454440">around.</span>
  <span m="1456930">What</span> <span m="1457080">do</span> <span m="1457140">you</span>
  <span m="1457200">think--</span> <span m="1457920">so</span> <span m="1458040">I</span>
  <span m="1458100">start</span> <span m="1458430">with</span> <span m="1459225">A</span>
  <span m="1459480">and</span> <span m="1459780">B</span> <span m="1459960">up</span>
  <span m="1460140">there,</span> <span m="1460760">and</span> <span m="1460890">I</span>
  <span m="1460950">need</span> <span m="1461070">to</span> <span m="1461160">construct</span>
  <span m="1462300">that</span> <span m="1462450">graph</span> <span m="1462860">G.</span>
  <span m="1464660">So</span> <span m="1464810">what</span> <span m="1464960">should</span>
  <span m="1465080">we</span> <span m="1465200">choose</span> <span m="1465650">as</span>
  <span m="1465830">our</span> <span m="1465980">graph?</span></p><p><span m="1470940">Let's</span>
  <span m="1471270">consider</span> <span m="1473290">the</span> <span m="1473410">popular</span>
  <span m="1473980">sums.</span> <span m="1480370">So</span> <span m="1480550">the</span>
  <span m="1480640">popular</span> <span m="1481120">sums</span> <span m="1481930">are</span>
  <span m="1482080">going</span> <span m="1482350">to</span> <span m="1482440">be</span>
  <span m="1483880">elements</span> <span m="1484900">in</span> <span m="1485110">the</span>
  <span m="1485530">complete</span> <span m="1486010">sumset</span> <span m="1488020">such</span>
  <span m="1488380">that</span> <span m="1490250">it</span> <span m="1490390">is</span>
  <span m="1490540">represented</span> <span m="1491470">as</span> <span m="1491590">a</span>
  <span m="1491620">sum</span> <span m="1492280">in</span> <span m="1493150">many</span>
  <span m="1493600">different</span> <span m="1494080">ways.</span> <span m="1502760">And</span>
  <span m="1502910">we're</span> <span m="1503060">going</span> <span m="1503270">to</span>
  <span m="1503390">take</span> <span m="1504800">edges</span> <span m="1506340">that</span>
  <span m="1506520">correspond</span> <span m="1507840">to</span> <span m="1509470">these</span>
  <span m="1509680">popular</span> <span m="1510190">sums.</span> <span m="1512760">So</span>
  <span m="1512840">let's</span> <span m="1513110">consider</span> <span m="1516130">bipartite</span>
  <span m="1516700">graph</span> <span m="1517000">G</span> <span m="1526370">such</span>
  <span m="1526670">that</span> <span m="1529400">A</span> <span m="1529550">comma</span>
  <span m="1529850">B</span> <span m="1530300">is an</span> <span m="1530660">edge</span>
  <span m="1534836">if</span> <span m="1535320">and</span> <span m="1535440">only</span>
  <span m="1536340">A</span> <span m="1536610">plus</span> <span m="1536970">B</span>
  <span m="1538500">is</span> <span m="1538860">a</span> <span m="1538890">popular</span>
  <span m="1539520">sum.</span></p><p><span m="1546900">So</span> <span m="1547320">let's</span>
  <span m="1547770">verify</span> <span m="1549000">some</span> <span m="1549300">of</span>
  <span m="1549390">the</span> <span m="1549510">hypotheses.</span> <span m="1550390">So</span>
  <span m="1550470">we're</span> <span m="1550560">going</span> <span m="1550700">to</span>
  <span m="1550770">assume</span> <span m="1551280">graph</span> <span m="1552300">BSG,</span>
  <span m="1553110">and</span> <span m="1553260">let's</span> <span m="1553470">verify</span>
  <span m="1553980">the</span> <span m="1554070">hypothesis</span> <span m="1554880">in</span>
  <span m="1555120">graph</span> <span m="1555450">BSG.</span> <span m="1557340">On</span>
  <span m="1557430">one</span> <span m="1557580">hand,</span> <span m="1557910">because</span>
  <span m="1558450">each</span> <span m="1558720">element</span> <span m="1559110">of</span>
  <span m="1559200">S</span> <span m="1559500">is</span> <span m="1559650">a</span>
  <span m="1559710">popular</span> <span m="1560160">sum,</span> <span m="1562080">if</span>
  <span m="1562230">we</span> <span m="1562410">consider</span> <span m="1563820">its</span>
  <span m="1564000">multiplicity,</span> <span m="1565170">we</span> <span m="1565320">find</span>
  <span m="1565770">that</span> <span m="1567180">the</span> <span m="1567340">size</span>
  <span m="1567870">of</span> <span m="1568530">S</span> <span m="1570010">multiplied</span>
  <span m="1570660">by</span> <span m="1570870">n</span> <span m="1571290">over</span>
  <span m="1571640">2k,</span> <span m="1573450">lower</span> <span m="1573750">bound</span>
  <span m="1575910">be</span> <span m="1576060">size</span> <span m="1577080">of</span>
  <span m="1577460">A</span> <span m="1577710">times</span> <span m="1578110">the</span>
  <span m="1578190">size</span> <span m="1578610">of</span> <span m="1578700">B.</span>
  <span m="1579245">So</span> <span m="1579610">if</span> <span m="1579750">you</span>
  <span m="1579840">think</span> <span m="1580050">about</span> <span m="1580830">all</span>
  <span m="1581070">the</span> <span m="1581220">different</span> <span m="1581580">pairs</span>
  <span m="1583840">in</span> <span m="1584060">A</span> <span m="1584340">and B,</span>
  <span m="1586750">each</span> <span m="1587030">sum</span> <span m="1587550">here,</span>
  <span m="1588440">each</span> <span m="1588630">popular</span> <span m="1589050">sum,</span>
  <span m="1589740">contributes</span> <span m="1590400">this</span> <span m="1590610">many</span>
  <span m="1590820">times</span> <span m="1591780">to</span> <span m="1592962">this</span>
  <span m="1593370">A</span> <span m="1593540">cross</span> <span m="1594000">B.</span></p><p><span
  m="1596330">So,</span> <span m="1596570">as</span> <span m="1596750">a</span> <span
  m="1596810">result,</span> <span m="1599610">because</span> <span m="1600230">size</span>
  <span m="1600590">of</span> <span m="1600680">A</span> <span m="1600770">and</span>
  <span m="1600890">size</span> <span m="1601140">of</span> <span m="1601210">B</span>
  <span m="1601370">are</span> <span m="1601490">both,</span> <span m="1601740">at
  most,</span> <span m="1602110">n,</span> <span m="1602840">we</span> <span m="1602960">find</span>
  <span m="1603320">that</span> <span m="1603650">the</span> <span m="1603740">size</span>
  <span m="1604130">of</span> <span m="1604220">S</span> <span m="1604880">is,</span>
  <span m="1605060">at</span> <span m="1605150">most,</span> <span m="1605780">2kn.</span>
  <span m="1609382">And</span> <span m="1609860">if</span> <span m="1609980">you</span>
  <span m="1610040">think</span> <span m="1610220">about</span> <span m="1610400">what</span>
  <span m="1610550">G</span> <span m="1610895">is,</span> <span m="1611780">then</span>
  <span m="1611960">this</span> <span m="1612140">implies</span> <span m="1612620">also</span>
  <span m="1613250">that</span> <span m="1615480">the</span> <span m="1615650">restricted</span>
  <span m="1616310">sumset</span> <span m="1619190">of</span> <span m="1619945">A</span>
  <span m="1620340">and</span> <span m="1620600">B</span> <span m="1620840">across</span>
  <span m="1621260">this</span> <span m="1621440">graph</span> <span m="1621740">G--</span>
  <span m="1622310">which</span> <span m="1622520">only</span> <span m="1622760">requires</span>
  <span m="1623210">the</span> <span m="1623300">popular</span> <span m="1623750">sums.</span>
  <span m="1624080">So</span> <span m="1624830">the</span> <span m="1625030">restricted</span>
  <span m="1625670">sumset</span> <span m="1626170">is</span> <span m="1626390">precisely</span>
  <span m="1627980">the</span> <span m="1628070">popular</span> <span m="1628520">sums.</span>
  <span m="1630718">So</span> <span m="1631170">restricted</span> <span m="1631620">sumset</span>
  <span m="1632160">is</span> <span m="1632730">not</span> <span m="1633030">too</span>
  <span m="1633270">large.</span> <span m="1638930">OK,</span> <span m="1639510">good.</span>
  <span m="1639900">So</span> <span m="1640080">we</span> <span m="1640200">got</span>
  <span m="1640410">one</span> <span m="1640620">of</span> <span m="1640710">the</span>
  <span m="1640770">conditions,</span> <span m="1642360">that</span> <span m="1642860">the</span>
  <span m="1642980">restricted</span> <span m="1643470">sumset</span> <span m="1644020">is</span>
  <span m="1644040">not</span> <span m="1644250">too</span> <span m="1644430">large.</span></p><p><span
  m="1645910">And</span> <span m="1646110">now</span> <span m="1646260">we</span>
  <span m="1646410">want</span> <span m="1646560">to</span> <span m="1646620">show</span>
  <span m="1646800">that</span> <span m="1646920">this</span> <span m="1647100">graph</span>
  <span m="1647430">has</span> <span m="1647850">lots</span> <span m="1648270">of</span>
  <span m="1648780">edges.</span> <span m="1650150">It</span> <span m="1650490">has</span>
  <span m="1650640">lots</span> <span m="1650940">of</span> <span m="1651030">edges.</span>
  <span m="1656210">And</span> <span m="1656330">here's</span> <span m="1656630">where</span>
  <span m="1656810">we</span> <span m="1656960">would</span> <span m="1657230">need</span>
  <span m="1657380">to</span> <span m="1657500">use</span> <span m="1657860">the</span>
  <span m="1658010">hypothesis</span> <span m="1658790">that,</span> <span m="1659120">between</span>
  <span m="1659570">A and</span> <span m="1659810">B,</span> <span m="1660640">originally</span>
  <span m="1661190">there</span> <span m="1661380">is</span> <span m="1661550">large</span>
  <span m="1662030">additive</span> <span m="1662540">energy.</span> <span m="1664166">And</span>
  <span m="1664580">the</span> <span m="1664640">point</span> <span m="1664910">here</span>
  <span m="1665150">is</span> <span m="1665300">that</span> <span m="1666650">these</span>
  <span m="1667610">unpopular</span> <span m="1668310">sums</span> <span m="1669200">cannot</span>
  <span m="1669980">contribute</span> <span m="1670790">very</span> <span m="1671060">much</span>
  <span m="1672080">to</span> <span m="1672290">the</span> <span m="1672440">additive</span>
  <span m="1672860">energy</span> <span m="1673370">in</span> <span m="1673490">total,</span>
  <span m="1675140">because</span> <span m="1675760">each</span> <span m="1675920">one</span>
  <span m="1676040">of</span> <span m="1676100">them</span> <span m="1676200">is</span>
  <span m="1676300">unpopular.</span> <span m="1678240">So</span> <span m="1679070">the</span>
  <span m="1679290">dominant</span> <span m="1679770">contributions</span> <span m="1680460">to</span>
  <span m="1680910">the</span> <span m="1681060">additive</span> <span m="1681420">energy</span>
  <span m="1681960">are</span> <span m="1682050">going</span> <span m="1682260">to</span>
  <span m="1682320">come</span> <span m="1682530">from</span> <span m="1682710">the</span>
  <span m="1682770">popular</span> <span m="1683220">sums,</span> <span m="1685280">and</span>
  <span m="1685760">we're</span> <span m="1685910">going</span> <span m="1686060">to</span>
  <span m="1686240">use that</span> <span m="1686460">to</span> <span m="1686550">show</span>
  <span m="1686780">that</span> <span m="1686950">G</span> <span m="1687260">has</span>
  <span m="1688160">lots</span> <span m="1688430">of</span> <span m="1688550">edges.</span></p><p><span
  m="1692660">So</span> <span m="1692780">let's</span> <span m="1693470">lower</span>
  <span m="1693770">bound</span> <span m="1694190">the</span> <span m="1694310">number</span>
  <span m="1694640">of</span> <span m="1694820">edges</span> <span m="1695420">of</span>
  <span m="1695540">G</span> <span m="1696020">by</span> <span m="1696200">first</span>
  <span m="1696560">showing</span> <span m="1696980">that--</span> <span m="1698820">so</span>
  <span m="1698970">we'll</span> <span m="1699110">show</span> <span m="1702340">that</span>
  <span m="1704086">the</span> <span m="1704570">unpopular</span> <span m="1707510">sums</span>
  <span m="1709040">contribute</span> <span m="1711980">very</span> <span m="1712190">little</span>
  <span m="1715030">to</span> <span m="1716990">the</span> <span m="1717580">additive</span>
  <span m="1717970">energy</span> <span m="1718420">between</span> <span m="1718870">A
  and</span> <span m="1719110">B.</span> <span m="1720910">Indeed,</span> <span m="1722210">the</span>
  <span m="1722380">sums</span> <span m="1722890">of</span> <span m="1722980">the</span>
  <span m="1723130">squares</span> <span m="1723730">of</span> <span m="1723820">the</span>
  <span m="1723940">r's,</span> <span m="1727924">if</span> <span m="1728420">for</span>
  <span m="1728750">x</span> <span m="1729860">not</span> <span m="1730370">in</span>
  <span m="1731720">popular</span> <span m="1732200">sums,</span> <span m="1733520">is</span>
  <span m="1734090">upper</span> <span m="1734300">bounded</span> <span m="1737150">by--</span>
  <span m="1738130">well,</span> <span m="1739490">claim</span> <span m="1739880">that</span>
  <span m="1740060">it</span> <span m="1740210">is</span> <span m="1740450">upper</span>
  <span m="1740650">bounded</span> <span m="1741170">by</span> <span m="1741410">the</span>
  <span m="1741500">following</span> <span m="1742010">quantity,</span> <span m="1742550">that</span>
  <span m="1743900">n</span> <span m="1744440">over</span> <span m="1745980">2k</span>
  <span m="1748220">times</span> <span m="1749310">n</span> <span m="1749550">squared.</span>
  <span m="1754520">Because</span> <span m="1755270">I</span> <span m="1755360">can</span>
  <span m="1755540">take</span> <span m="1755860">out</span> <span m="1756710">one</span>
  <span m="1756950">factor</span> <span m="1758540">r,</span> <span m="1759470">upper</span>
  <span m="1759650">bound</span> <span m="1759980">by</span> <span m="1760250">this</span>
  <span m="1761270">number,</span> <span m="1762050">just</span> <span m="1762260">by</span>
  <span m="1762380">definition,</span> <span m="1764180">and</span> <span m="1764310">the</span>
  <span m="1764400">sums</span> <span m="1764850">of</span> <span m="1764970">the</span>
  <span m="1765360">r's</span> <span m="1766020">is</span> <span m="1767090">n</span>
  <span m="1767430">squared.</span></p><p><span m="1772540">So</span> <span m="1774920">you</span>
  <span m="1775040">have</span> <span m="1775250">this</span> <span m="1775520">additive</span>
  <span m="1775940">energy</span> <span m="1777620">between</span> <span m="1777980">A
  and</span> <span m="1778190">B.</span> <span m="1779150">I</span> <span m="1779270">know</span>
  <span m="1779450">that</span> <span m="1779630">it</span> <span m="1779720">is</span>
  <span m="1779870">large</span> <span m="1780260">by</span> <span m="1780440">hypothesis.</span>
  <span m="1785940">Whereas,</span> <span m="1786810">I</span> <span m="1786930">also</span>
  <span m="1787200">know</span> <span m="1787440">that</span> <span m="1787620">I</span>
  <span m="1787770">can</span> <span m="1787920">write</span> <span m="1788220">it</span>
  <span m="1788310">as</span> <span m="1788430">a</span> <span m="1788490">sum</span>
  <span m="1788880">of</span> <span m="1788970">the</span> <span m="1789060">squares</span>
  <span m="1789600">of</span> <span m="1789690">the</span> <span m="1789870">r's,</span>
  <span m="1792390">which</span> <span m="1792570">I</span> <span m="1792660">can</span>
  <span m="1792780">break</span> <span m="1793170">into</span> <span m="1795810">the</span>
  <span m="1795990">popular</span> <span m="1797460">contributions</span> <span m="1800550">and</span>
  <span m="1800730">the</span> <span m="1800880">unpopular</span> <span m="1801690">contributions.</span>
  <span m="1805890">And,</span> <span m="1806020">hopefully,</span> <span m="1806410">this</span>
  <span m="1806560">should</span> <span m="1806740">all</span> <span m="1806830">be</span>
  <span m="1806950">somewhat</span> <span m="1807280">reminiscent</span> <span m="1807880">of</span>
  <span m="1808420">basically</span> <span m="1808750">all</span> <span m="1808960">these</span>
  <span m="1809170">proofs</span> <span m="1809470">that</span> <span m="1809590">we</span>
  <span m="1809710">did</span> <span m="1809890">so</span> <span m="1810100">far</span>
  <span m="1810280">in</span> <span m="1810340">this</span> <span m="1810520">course,</span>
  <span m="1811200">where</span> <span m="1811360">we</span> <span m="1812050">separate</span>
  <span m="1812590">a</span> <span m="1812620">sum</span> <span m="1812980">into</span>
  <span m="1813700">the</span> <span m="1813790">dominant</span> <span m="1814300">terms</span>
  <span m="1814750">and</span> <span m="1814960">the</span> <span m="1815500">minor</span>
  <span m="1815890">terms.</span> <span m="1816510">This</span> <span m="1816790">came</span>
  <span m="1817000">up</span> <span m="1817180">in</span> <span m="1817430">Fourier</span>
  <span m="1817510">analysis</span> <span m="1818410">in</span> <span m="1818500">particular.</span>
  <span m="1820010">So</span> <span m="1820030">we</span> <span m="1820390">do</span>
  <span m="1820570">this</span> <span m="1821050">splitting,</span> <span m="1822250">and</span>
  <span m="1823030">we</span> <span m="1824130">upper</span> <span m="1824320">bound</span>
  <span m="1824840">the</span> <span m="1825070">unpopular</span> <span m="1825910">contributions</span>
  <span m="1827530">by</span> <span m="1828220">the</span> <span m="1828340">estimate</span>
  <span m="1828820">from</span> <span m="1829180">just</span> <span m="1829570">now.</span></p><p><span
  m="1836810">So,</span> <span m="1837020">as</span> <span m="1837140">a</span> <span
  m="1837200">result,</span> <span m="1838220">bringing</span> <span m="1838730">this</span>
  <span m="1839540">small</span> <span m="1839930">error</span> <span m="1840170">term,</span>
  <span m="1840800">it</span> <span m="1840920">doesn't</span> <span m="1842180">cancel</span>
  <span m="1842690">much</span> <span m="1843170">of</span> <span m="1843500">the</span>
  <span m="1843800">energy.</span> <span m="1844610">So</span> <span m="1847040">we</span>
  <span m="1847190">still</span> <span m="1847460">have</span> <span m="1847670">a</span>
  <span m="1847730">lower</span> <span m="1848000">bound</span> <span m="1849680">on</span>
  <span m="1850070">the</span> <span m="1850310">sum</span> <span m="1850820">of</span>
  <span m="1851030">the</span> <span m="1851180">squares</span> <span m="1852350">of</span>
  <span m="1852710">the</span> <span m="1852950">r's</span> <span m="1855390">in</span>
  <span m="1855630">the</span> <span m="1855750">popular</span> <span m="1856230">sums.</span>
  <span m="1860010">But</span> <span m="1860190">I</span> <span m="1860310">can</span>
  <span m="1860520">also</span> <span m="1860790">give</span> <span m="1861540">a</span>
  <span m="1861630">fairly</span> <span m="1861960">trivial</span> <span m="1862470">upper</span>
  <span m="1862710">bound</span> <span m="1863100">to</span> <span m="1863580">a</span>
  <span m="1863670">single</span> <span m="1864240">r,</span> <span m="1865170">namely</span>
  <span m="1865980">it</span> <span m="1866310">cannot</span> <span m="1866640">be</span>
  <span m="1866850">bigger</span> <span m="1867210">than</span> <span m="1867750">n.</span>
  <span m="1876220">And</span> <span m="1876820">so</span> <span m="1877150">the</span>
  <span m="1877300">number</span> <span m="1877720">of</span> <span m="1879430">edges</span>
  <span m="1882300">of</span> <span m="1882450">G--</span> <span m="1883860">so</span>
  <span m="1883980">what's</span> <span m="1884220">the</span> <span m="1884310">number</span>
  <span m="1884610">of</span> <span m="1884820">edges</span> <span m="1885180">of</span>
  <span m="1885300">G?</span> <span m="1887480">Look</span> <span m="1887660">at</span>
  <span m="1887750">that.</span> <span m="1888260">Each</span> <span m="1889250">x</span>
  <span m="1889640">here</span> <span m="1890300">contributes</span> <span m="1891500">rx</span>
  <span m="1892180">many</span> <span m="1892520">edges.</span> <span m="1893470">So</span>
  <span m="1893630">the</span> <span m="1893720">number</span> <span m="1894020">of</span>
  <span m="1894170">edges</span> <span m="1894530">of</span> <span m="1894620">G</span>
  <span m="1894920">is</span> <span m="1895040">simply</span> <span m="1895400">the</span>
  <span m="1895520">sums</span> <span m="1896120">of</span> <span m="1896300">these</span>
  <span m="1896570">rx's.</span> <span m="1901310">Which</span> <span m="1901610">is</span>
  <span m="1902090">quite</span> <span m="1902360">large.</span></p><p><span m="1909740">So</span>
  <span m="1911240">the</span> <span m="1911420">hypothesis</span> <span m="1912440">of</span>
  <span m="1912740">graph</span> <span m="1913160">BSG</span> <span m="1914180">are</span>
  <span m="1914390">satisfied.</span> <span m="1916070">And</span> <span m="1916130">so</span>
  <span m="1916250">we</span> <span m="1916400">can</span> <span m="1916580">use</span>
  <span m="1916790">the</span> <span m="1916880">conclusion</span> <span m="1917540">of</span>
  <span m="1918200">graph</span> <span m="1918500">BSG,</span> <span m="1919580">which</span>
  <span m="1919850">is</span> <span m="1920750">the</span> <span m="1920810">conclusion</span>
  <span m="1921320">that</span> <span m="1921410">we're</span> <span m="1921530">looking</span>
  <span m="1921830">for</span> <span m="1922250">in</span> <span m="1922430">BSG.</span>
  <span m="1931520">Any</span> <span m="1931680">questions?</span> <span m="1937160">Good.</span>
  <span m="1937595">So</span> <span m="1937850">the</span> <span m="1937940">remaining</span>
  <span m="1938450">task</span> <span m="1938960">is</span> <span m="1939140">to</span>
  <span m="1939230">prove</span> <span m="1939860">the</span> <span m="1940070">graphical</span>
  <span m="1940610">version</span> <span m="1941030">of</span> <span m="1941240">BSG.</span>
  <span m="1943160">So</span> <span m="1944270">let's</span> <span m="1944450">take</span>
  <span m="1944630">a</span> <span m="1944720">quick</span> <span m="1944960">break,</span>
  <span m="1945480">and</span> <span m="1945920">when</span> <span m="1946040">we</span>
  <span m="1946160">come</span> <span m="1946340">back</span> <span m="1947070">we'll</span>
  <span m="1947810">focus</span> <span m="1948230">on</span> <span m="1948950">this</span>
  <span m="1949160">theorem,</span> <span m="1950030">and it</span> <span m="1950240">has</span>
  <span m="1950810">some</span> <span m="1951050">nice</span> <span m="1951650">graph</span>
  <span m="1951950">theoretic</span> <span m="1952460">arguments.</span></p><p><span
  m="1955140">OK,</span> <span m="1955480">let's</span> <span m="1955630">continue.</span>
  <span m="1957430">We've</span> <span m="1957610">reduced</span> <span m="1958210">the</span>
  <span m="1958930">proof</span> <span m="1959440">of</span> <span m="1960010">the</span>
  <span m="1960130">Balog-Szemeredi-Gowers</span> <span m="1961390">theorem</span>
  <span m="1962230">to</span> <span m="1962560">the</span> <span m="1962680">following</span>
  <span m="1963220">graphical</span> <span m="1964150">result.</span> <span m="1964540">Well,</span>
  <span m="1964840">it's</span> <span m="1965020">not</span> <span m="1965350">just</span>
  <span m="1965590">graphical,</span> <span m="1965880">right?</span> <span m="1966170">Still--</span>
  <span m="1966610">we're</span> <span m="1966790">still</span> <span m="1967030">inside</span>
  <span m="1967570">some</span> <span m="1968180">an</span> <span m="1968270">Abelian</span>
  <span m="1968620">group,</span> <span m="1969370">still</span> <span m="1969790">looking</span>
  <span m="1970180">at</span> <span m="1970810">some</span> <span m="1971110">set</span>
  <span m="1971470">in</span> <span m="1971620">some</span> <span m="1971860">Abelian</span>
  <span m="1972220">group,</span> <span m="1972570">but,</span> <span m="1972800">certainly,</span>
  <span m="1973030">now</span> <span m="1973330">it</span> <span m="1973420">has</span>
  <span m="1973630">a</span> <span m="1973690">graph</span> <span m="1974140">attached</span>
  <span m="1974560">to</span> <span m="1974740">it.</span> <span m="1977140">Let</span>
  <span m="1977290">me</span> <span m="1977380">show</span> <span m="1977620">this</span>
  <span m="1977830">theorem</span> <span m="1978850">through</span> <span m="1979360">several</span>
  <span m="1979750">steps.</span> <span m="1981410">First,</span> <span m="1982000">something</span>
  <span m="1982360">called</span> <span m="1983110">a</span> <span m="1983230">path</span>
  <span m="1983710">of</span> <span m="1983830">length</span> <span m="1984130">2</span>
  <span m="1984430">lemma.</span></p><p><span m="1995502">So</span> <span m="1996000">the</span>
  <span m="1996090">path</span> <span m="1996360">of</span> <span m="1996420">length</span>
  <span m="1996660">2</span> <span m="1996810">lemma,</span> <span m="1997200">the</span>
  <span m="1997320">statement</span> <span m="1997860">is</span> <span m="1998100">that</span>
  <span m="1998760">you</span> <span m="1998880">start</span> <span m="1999240">with</span>
  <span m="1999420">a</span> <span m="1999450">graph</span> <span m="1999960">G</span>
  <span m="2001190">which</span> <span m="2001340">is</span> <span m="2001460">a</span>
  <span m="2001520">bipartite</span> <span m="2002060">graph</span> <span m="2002660">between</span>
  <span m="2003590">vertex</span> <span m="2004040">sets</span> <span m="2005860">A</span>
  <span m="2006300">and</span> <span m="2006740">B.</span> <span m="2007130">And now</span>
  <span m="2007520">A and</span> <span m="2007760">B</span> <span m="2007940">no</span>
  <span m="2008120">longer</span> <span m="2008390">need--</span> <span m="2009050">they're</span>
  <span m="2009200">just</span> <span m="2009740">sets.</span> <span m="2010100">They're</span>
  <span m="2010300">just</span> <span m="2010550">vertex</span> <span m="2010890">sets.</span>
  <span m="2011150">We're</span> <span m="2011330">not</span> <span m="2011480">going</span>
  <span m="2011600">to</span> <span m="2011690">have</span> <span m="2011840">sums.</span>
  <span m="2014550">And</span> <span m="2014900">the</span> <span m="2015200">number</span>
  <span m="2015590">of</span> <span m="2015740">edges</span> <span m="2016430">is</span>
  <span m="2016880">at</span> <span m="2016940">least</span> <span m="2017240">a</span>
  <span m="2017300">constant</span> <span m="2017750">fraction</span> <span m="2018260">of</span>
  <span m="2018380">the</span> <span m="2018470">maximum</span> <span m="2018920">possible.</span>
  <span m="2025570">Then</span> <span m="2025620">the</span> <span m="2025710">conclusion</span>
  <span m="2027960">is</span> <span m="2028140">that</span> <span m="2028440">there</span>
  <span m="2028620">exists</span> <span m="2029130">some</span> <span m="2029520">U,</span>
  <span m="2030240">a</span> <span m="2030300">subset</span> <span m="2030840">of</span>
  <span m="2030960">A,</span> <span m="2031890">such</span> <span m="2032280">that</span>
  <span m="2034000">U</span> <span m="2034385">is</span> <span m="2034770">fairly</span>
  <span m="2035130">large.</span> <span m="2039650">And</span> <span m="2042590">between</span>
  <span m="2045100">most</span> <span m="2047020">pairs</span> <span m="2048159">of</span>
  <span m="2049389">elements</span> <span m="2049810">of</span> <span m="2049929">U--</span>
  <span m="2050199">so</span> <span m="2050380">between</span> <span m="2050810">1</span>
  <span m="2051159">minus</span> <span m="2051880">epsilon</span> <span m="2052719">fraction</span>
  <span m="2056110">of</span> <span m="2059909">pairs</span> <span m="2061469">of</span>
  <span m="2064130">U--</span> <span m="2064880">there</span> <span m="2065170">are</span>
  <span m="2068489">lots</span> <span m="2068850">of</span> <span m="2069150">common</span>
  <span m="2069570">neighbors.</span> <span m="2070840">So</span> <span m="2071070">at</span>
  <span m="2071130">least</span> <span m="2072810">epsilon</span> <span m="2074370">delta</span>
  <span m="2074730">squared</span> <span m="2076650">B</span> <span m="2077250">over</span>
  <span m="2077500">2</span> <span m="2082100">common</span> <span m="2084429">neighbors.</span></p><p><span
  m="2086230">So</span> <span m="2089330">you</span> <span m="2089520">start</span>
  <span m="2089850">with</span> <span m="2090120">this</span> <span m="2090850">bipartite</span>
  <span m="2091290">graph</span> <span m="2091730">A</span> <span m="2091850">and</span>
  <span m="2092130">B.</span> <span m="2096690">Lots</span> <span m="2096949">of</span>
  <span m="2097200">edges.</span> <span m="2098550">And</span> <span m="2099390">we</span>
  <span m="2099510">would</span> <span m="2099630">like</span> <span m="2099840">to</span>
  <span m="2099960">show</span> <span m="2100650">that</span> <span m="2101340">there</span>
  <span m="2101520">exists</span> <span m="2102180">a</span> <span m="2102300">pretty</span>
  <span m="2102600">large</span> <span m="2103470">subset</span> <span m="2104550">U</span>
  <span m="2106200">such</span> <span m="2106530">that</span> <span m="2106800">between</span>
  <span m="2107580">most</span> <span m="2108000">pairs--</span> <span m="2108840">all</span>
  <span m="2109020">but</span> <span m="2109200">an</span> <span m="2109320">epsilon</span>
  <span m="2109680">fraction--</span> <span m="2111150">of</span> <span m="2111330">ordered</span>
  <span m="2111690">pairs--</span> <span m="2112300">they</span> <span m="2112460">could</span>
  <span m="2112590">be</span> <span m="2112680">the</span> <span m="2112740">same,</span>
  <span m="2112980">but</span> <span m="2113070">it</span> <span m="2113120">doesn't</span>
  <span m="2113310">really</span> <span m="2113460">matter--</span> <span m="2115350">the</span>
  <span m="2115650">number</span> <span m="2116160">of</span> <span m="2116370">paths</span>
  <span m="2116880">of</span> <span m="2117000">length</span> <span m="2117270">2</span>
  <span m="2118600">between</span> <span m="2119110">these</span> <span m="2119380">two</span>
  <span m="2121180">vertices</span> <span m="2122600">is</span> <span m="2122860">quite</span>
  <span m="2123160">large.</span> <span m="2124920">So</span> <span m="2125010">they</span>
  <span m="2125100">have</span> <span m="2125280">lots</span> <span m="2125550">of</span>
  <span m="2125640">common</span> <span m="2125970">neighbors.</span> <span m="2128430">Where</span>
  <span m="2128610">have</span> <span m="2128760">we</span> <span m="2128850">seen</span>
  <span m="2129060">something</span> <span m="2129360">like</span> <span m="2129510">this</span>
  <span m="2129690">before?</span> <span m="2130440">There's</span> <span m="2130560">a</span>
  <span m="2130650">question?</span></p><p><span m="2130890">AUDIENCE:</span> <span
  m="2131040">Is</span> <span m="2131190">there a</span> <span m="2131341">[INAUDIBLE]</span>
  <span m="2131792">epsilon?</span></p><p><span m="2132694">YUFEI ZHAO:</span> <span
  m="2132919">Ah,</span> <span m="2133145">yes.</span> <span m="2133600">So</span>
  <span m="2133770">for</span> <span m="2133980">every</span> <span m="2134220">epsilon</span>
  <span m="2134670">and</span> <span m="2134790">every</span> <span m="2135000">delta.</span>
  <span m="2137156">So</span> <span m="2137620">let</span> <span m="2139480">epsilon,</span>
  <span m="2140500">delta</span> <span m="2142180">be</span> <span m="2142570">parameters.</span>
  <span m="2148080">Where</span> <span m="2148290">have</span> <span m="2148410">we</span>
  <span m="2148530">seen</span> <span m="2148740">something</span> <span m="2149010">like</span>
  <span m="2149160">this</span> <span m="2149310">before?</span> <span m="2151860">So</span>
  <span m="2152320">in</span> <span m="2152460">a</span> <span m="2152520">bipartite</span>
  <span m="2152970">graph</span> <span m="2153240">with</span> <span m="2153360">lots</span>
  <span m="2153570">of</span> <span m="2153690">edges,</span> <span m="2154620">I</span>
  <span m="2154710">want</span> <span m="2154950">to</span> <span m="2155160">find</span>
  <span m="2155910">a</span> <span m="2156270">large</span> <span m="2156810">subset</span>
  <span m="2157410">of</span> <span m="2157680">one</span> <span m="2157920">of</span>
  <span m="2157980">the</span> <span m="2158070">parts</span> <span m="2159180">so</span>
  <span m="2159420">that</span> <span m="2160080">every</span> <span m="2160320">pair</span>
  <span m="2160860">of</span> <span m="2161130">elements,</span> <span m="2161670">or</span>
  <span m="2161880">almost</span> <span m="2162270">every</span> <span m="2162450">pair</span>
  <span m="2162660">of</span> <span m="2162780">elements,</span> <span m="2163620">have</span>
  <span m="2163920">lots</span> <span m="2164280">of</span> <span m="2164400">common</span>
  <span m="2164790">neighbors.</span> <span m="2171254">Yes.</span></p><p><span m="2172238">AUDIENCE:</span>
  <span m="2172484">[INAUDIBLE].</span></p><p><span m="2173730">YUFEI ZHAO:</span>
  <span m="2173850">Dependent</span> <span m="2174090">random</span> <span m="2174360">choice.</span>
  <span m="2175070">So</span> <span m="2175290">in</span> <span m="2175400">the</span>
  <span m="2175440">very</span> <span m="2175680">first</span> <span m="2176010">chapter</span>
  <span m="2176460">of</span> <span m="2176580">this</span> <span m="2176790">course,</span>
  <span m="2177150">when</span> <span m="2177330">we</span> <span m="2177480">did</span>
  <span m="2177720">extremal</span> <span m="2178170">graph</span> <span m="2178470">theory</span>
  <span m="2179340">forbidding</span> <span m="2179910">bipartite</span> <span m="2180450">subgraphs,</span>
  <span m="2181410">there</span> <span m="2181530">was</span> <span m="2181710">a</span>
  <span m="2181770">technique</span> <span m="2182490">for</span> <span m="2183420">proving</span>
  <span m="2184590">the</span> <span m="2184920">extremal</span> <span m="2185370">number,</span>
  <span m="2185920">upper</span> <span m="2186150">bounds,</span> <span m="2186900">for</span>
  <span m="2187490">bipartite</span> <span m="2187950">graphs</span> <span m="2188310">of</span>
  <span m="2188620">bounded</span> <span m="2188930">degree.</span> <span m="2189540">And</span>
  <span m="2189690">there</span> <span m="2189930">we</span> <span m="2190080">used</span>
  <span m="2190890">something</span> <span m="2191190">called</span> <span m="2191370">dependent</span>
  <span m="2191820">random</span> <span m="2192030">choice</span> <span m="2192810">that</span>
  <span m="2193320">had</span> <span m="2193500">a</span> <span m="2193560">conclusion</span>
  <span m="2194100">that</span> <span m="2194220">was</span> <span m="2194400">very</span>
  <span m="2194640">similar</span> <span m="2195100">flavor.</span> <span m="2195860">So</span>
  <span m="2195930">there,</span> <span m="2196530">we</span> <span m="2196680">had</span>
  <span m="2197550">every</span> <span m="2197850">pair--</span> <span m="2198300">so</span>
  <span m="2198540">a</span> <span m="2198600">fairly</span> <span m="2198960">large,</span>
  <span m="2199450">but</span> <span m="2199470">not</span> <span m="2199710">as</span>
  <span m="2199860">large</span> <span m="2200100">as</span> <span m="2200190">this--</span>
  <span m="2200390">a</span> <span m="2200460">fairly</span> <span m="2200760">large</span>
  <span m="2201030">subset</span> <span m="2201390">where</span> <span m="2201620">every</span>
  <span m="2201900">pair</span> <span m="2202200">of</span> <span m="2202320">elements</span>
  <span m="2203130">had</span> <span m="2203490">lots</span> <span m="2203850">of</span>
  <span m="2204750">common</span> <span m="2205080">neighbors.</span> <span m="2205640">For</span>
  <span m="2205860">every</span> <span m="2206130">couple,</span> <span m="2206490">every
  k</span> <span m="2206730">couple</span> <span m="2207270">of</span> <span m="2207420">vertices,</span>
  <span m="2208230">have</span> <span m="2208440">lots</span> <span m="2208740">of</span>
  <span m="2208830">common</span> <span m="2209130">neighbors.</span> <span m="2210330">So</span>
  <span m="2210480">it's</span> <span m="2210600">very</span> <span m="2210780">similar.</span>
  <span m="2211470">In</span> <span m="2211560">fact,</span> <span m="2211900">it's</span>
  <span m="2211950">the</span> <span m="2212010">same</span> <span m="2212850">type</span>
  <span m="2213180">of</span> <span m="2213360">technique</span> <span m="2213960">that</span>
  <span m="2214110">we'll</span> <span m="2214320">use</span> <span m="2214950">to</span>
  <span m="2215100">prove</span> <span m="2215490">this</span> <span m="2215730">lemma</span>
  <span m="2216080">over</span> <span m="2216290">here.</span> <span m="2220390">So</span>
  <span m="2220590">who</span> <span m="2220870">remembers</span> <span m="2221260">how</span>
  <span m="2221380">dependent</span> <span m="2221770">random</span> <span m="2222010">choice</span>
  <span m="2222280">goes?</span></p><p><span m="2225030">So</span> <span m="2225220">the</span>
  <span m="2225340">idea</span> <span m="2225910">is</span> <span m="2226150">that</span>
  <span m="2226680">we</span> <span m="2226860">are</span> <span m="2227020">going</span>
  <span m="2227290">to</span> <span m="2227410">choose</span> <span m="2228310">U</span>
  <span m="2229120">not</span> <span m="2229750">uniformly</span> <span m="2230320">at</span>
  <span m="2230420">random.</span> <span m="2231200">So</span> <span m="2231220">that's</span>
  <span m="2231400">not</span> <span m="2231550">going</span> <span m="2231670">to</span>
  <span m="2231730">work.</span> <span m="2232872">Going to</span> <span m="2233340">choose
  it</span> <span m="2233680">in</span> <span m="2233840">a</span> <span m="2233910">dependent</span>
  <span m="2234480">random</span> <span m="2234810">way.</span> <span m="2235860">So</span>
  <span m="2236070">I</span> <span m="2236190">want</span> <span m="2236580">elements</span>
  <span m="2237000">of</span> <span m="2237090">U</span> <span m="2237330">to</span>
  <span m="2237450">have</span> <span m="2238080">lots</span> <span m="2238350">of</span>
  <span m="2238440">common</span> <span m="2238780">neighbors,</span> <span m="2239630">typically.</span>
  <span m="2240720">So</span> <span m="2240930">one</span> <span m="2241110">way</span>
  <span m="2241230">to</span> <span m="2241360">guarantee</span> <span m="2241770">this</span>
  <span m="2242520">is</span> <span m="2242640">to</span> <span m="2242760">choose</span>
  <span m="2243480">U</span> <span m="2243930">to</span> <span m="2244080">be</span>
  <span m="2244950">a</span> <span m="2245040">neighborhood</span> <span m="2246480">from</span>
  <span m="2246870">the</span> <span m="2246960">right.</span> <span m="2248550">So</span>
  <span m="2248720">pick</span> <span m="2249830">a</span> <span m="2249890">random</span>
  <span m="2250790">element</span> <span m="2252030">in</span> <span m="2252170">B</span>
  <span m="2253130">and</span> <span m="2253280">choose</span> <span m="2253640">U</span>
  <span m="2253940">to</span> <span m="2254090">be</span> <span m="2254330">its</span>
  <span m="2254750">neighborhood.</span> <span m="2257300">So</span> <span m="2257420">let's</span>
  <span m="2257600">do</span> <span m="2257720">that.</span> <span m="2259230">So
  we're</span> <span m="2259480">going to</span> <span m="2259800">use</span> <span
  m="2260160">dependent</span> <span m="2260610">random</span> <span m="2260880">choice.</span>
  <span m="2267606">See,</span> <span m="2268110">everything</span> <span m="2268500">in
  the</span> <span m="2268560">course</span> <span m="2268930">comes</span> <span
  m="2269070">together.</span></p><p><span m="2276000">So</span> <span m="2276570">let's</span>
  <span m="2280460">pick</span> <span m="2281250">v</span> <span m="2281990">an</span>
  <span m="2282470">element</span> <span m="2282820">of</span> <span m="2282890">B</span>
  <span m="2283370">uniformly</span> <span m="2284030">at</span> <span m="2284110">random.</span>
  <span m="2289580">And</span> <span m="2290210">let</span> <span m="2290420">U</span>
  <span m="2290840">be</span> <span m="2291080">the</span> <span m="2291260">neighborhood</span>
  <span m="2292680">v.</span> <span m="2294840">So,</span> <span m="2294960">first</span>
  <span m="2295230">of</span> <span m="2295320">all,</span> <span m="2295440">by</span>
  <span m="2295590">linearity</span> <span m="2296070">of</span> <span m="2296190">expectations,</span>
  <span m="2297030">the</span> <span m="2297780">size</span> <span m="2298320">of</span>
  <span m="2298440">U</span> <span m="2299100">is</span> <span m="2300120">at</span>
  <span m="2300270">least</span> <span m="2301010">delta</span> <span m="2301610">of</span>
  <span m="2302071">A.</span> <span m="2304840">So</span> <span m="2305410">because</span>
  <span m="2305710">the</span> <span m="2306370">average</span> <span m="2306740">degree</span>
  <span m="2307600">from</span> <span m="2308260">the</span> <span m="2308350">right</span>
  <span m="2308860">from</span> <span m="2309070">B</span> <span m="2309400">is</span>
  <span m="2310910">at</span> <span m="2311000">least</span> <span m="2311390">delta</span>
  <span m="2311780">A</span> <span m="2312020">just</span> <span m="2312230">based</span>
  <span m="2312500">on</span> <span m="2312590">the</span> <span m="2312650">number</span>
  <span m="2312950">of</span> <span m="2313090">edges.</span> <span m="2316550">If</span>
  <span m="2317360">you</span> <span m="2317510">have</span> <span m="2317870">two</span>
  <span m="2318890">vertices</span> <span m="2319235">a</span> <span m="2319580">and</span>
  <span m="2320000">a prime</span> <span m="2321260">in</span> <span m="2321470">A</span>
  <span m="2323560">with</span> <span m="2323950">a</span> <span m="2324010">small</span>
  <span m="2324400">number</span> <span m="2324760">of</span> <span m="2324880">common</span>
  <span m="2325210">neighbors,</span> <span m="2336412">then</span> <span m="2339340">the</span>
  <span m="2342140">size</span> <span m="2342890">of--</span> <span m="2344220">so</span>
  <span m="2346182">sorry.</span> <span m="2347020">Let</span> <span m="2347270">me--</span>
  <span m="2349001">I</span> <span m="2349490">skipped</span> <span m="2349880">ahead</span>
  <span m="2350020">a bit.</span></p><p><span m="2350520">So</span> <span m="2351150">if</span>
  <span m="2351930">a</span> <span m="2352410">and</span> <span m="2352550">a prime</span>
  <span m="2352850">have a</span> <span m="2353220">small</span> <span m="2353610">number</span>
  <span m="2353910">of</span> <span m="2354030">common</span> <span m="2354330">neighbors,</span>
  <span m="2355170">then</span> <span m="2356430">the</span> <span m="2356520">probability</span>
  <span m="2357960">that</span> <span m="2358350">a</span> <span m="2358550">and</span>
  <span m="2358770">a prime</span> <span m="2359820">both</span> <span m="2360330">lie</span>
  <span m="2361040">in</span> <span m="2361230">U</span> <span m="2362730">should</span>
  <span m="2362970">be</span> <span m="2363090">quite</span> <span m="2363390">small.</span>
  <span m="2365580">Because</span> <span m="2366270">if</span> <span m="2366720">they</span>
  <span m="2366990">both</span> <span m="2367320">had--</span> <span m="2368670">if</span>
  <span m="2368870">a</span> <span m="2369210">and</span> <span m="2369300">a prime</span>
  <span m="2369570">have</span> <span m="2369720">a</span> <span m="2369780">small</span>
  <span m="2370080">number</span> <span m="2370350">of</span> <span m="2370440">common</span>
  <span m="2370740">neighbors,</span> <span m="2373040">in</span> <span m="2373190">order</span>
  <span m="2373530">for</span> <span m="2373770">a and</span> <span m="2374120">a
  prime</span> <span m="2374390">to</span> <span m="2374480">be</span> <span m="2374630">included</span>
  <span m="2375110">in</span> <span m="2375230">this</span> <span m="2375410">U,</span>
  <span m="2376940">you</span> <span m="2377090">must</span> <span m="2377390">have</span>
  <span m="2377510">chosen--</span> <span m="2381550">so</span> <span m="2381590">suppose</span>
  <span m="2383360">this</span> <span m="2383510">were</span> <span m="2383640">their</span>
  <span m="2383780">common</span> <span m="2384080">neighbor.</span> <span m="2384920">Then</span>
  <span m="2385460">in</span> <span m="2385610">order</span> <span m="2385970">that</span>
  <span m="2386120">a</span> <span m="2386420">and</span> <span m="2386540">a prime</span>
  <span m="2388230">be</span> <span m="2388500">contained</span> <span m="2388770">in</span>
  <span m="2389040">U,</span> <span m="2389550">it</span> <span m="2389670">must</span>
  <span m="2389880">have</span> <span m="2389970">chosen</span> <span m="2390750">this</span>
  <span m="2390960">v</span> <span m="2391680">to</span> <span m="2392100">be</span>
  <span m="2393060">inside</span> <span m="2393510">the</span> <span m="2393600">common</span>
  <span m="2393900">neighborhood</span> <span m="2394470">of</span> <span m="2394690">a
  and</span> <span m="2395010">a prime.</span> <span m="2397840">Which</span> <span
  m="2398020">is</span> <span m="2398110">unlikely</span> <span m="2399070">if</span>
  <span m="2399250">a</span> <span m="2399460">and</span> <span m="2399580">a prime</span>
  <span m="2399940">had</span> <span m="2400060">a</span> <span m="2400090">small</span>
  <span m="2400390">number</span> <span m="2400720">of</span> <span m="2400810">common</span>
  <span m="2401110">neighbors.</span> <span m="2402940">So</span> <span m="2403240">this</span>
  <span m="2403420">probability</span> <span m="2404650">is,</span> <span m="2405400">at</span>
  <span m="2405610">most,</span> <span m="2406060">epsilon</span> <span m="2406840">delta</span>
  <span m="2407140">squared</span> <span m="2408000">over</span> <span m="2408410">2.</span>
  <span m="2412460">Just</span> <span m="2412640">think</span> <span m="2412820">about</span>
  <span m="2413000">how</span> <span m="2413180">U</span> <span m="2413360">is</span>
  <span m="2413540">constructed.</span></p><p><span m="2415520">So</span> <span m="2415700">if</span>
  <span m="2415850">we</span> <span m="2416000">let</span> <span m="2417920">x</span>
  <span m="2418940">be</span> <span m="2419150">the</span> <span m="2419330">number</span>
  <span m="2420030">of</span> <span m="2421270">a and</span> <span m="2421700">a primes</span>
  <span m="2423440">in</span> <span m="2424340">U</span> <span m="2424550">cross</span>
  <span m="2424910">U</span> <span m="2426740">with,</span> <span m="2428615">at</span>
  <span m="2429100">most,</span> <span m="2430660">epsilon</span> <span m="2431380">delta</span>
  <span m="2431680">squared</span> <span m="2432340">over</span> <span m="2432580">2</span>
  <span m="2434080">times</span> <span m="2434350">B</span> <span m="2434800">common</span>
  <span m="2435160">neighbors,</span> <span m="2439300">then,</span> <span m="2440920">by</span>
  <span m="2441100">linearity</span> <span m="2441730">of</span> <span m="2441880">expectations,</span>
  <span m="2442900">the</span> <span m="2443110">expectation</span> <span m="2444370">of</span>
  <span m="2444640">x</span> <span m="2445500">is--</span> <span m="2446300">well,</span>
  <span m="2446490">by</span> <span m="2446680">summing</span> <span m="2447190">up</span>
  <span m="2447850">all</span> <span m="2448090">of</span> <span m="2450880">these</span>
  <span m="2451090">probabilities</span> <span m="2452500">of</span> <span m="2452680">a
  and</span> <span m="2453100">a prime,</span> <span m="2454420">both</span> <span
  m="2454750">being</span> <span m="2455400">in</span> <span m="2455620">U--</span>
  <span m="2456890">so</span> <span m="2457130">this</span> <span m="2457340">is,</span>
  <span m="2457890">at</span> <span m="2458090">most,</span> <span m="2459850">epsilon</span>
  <span m="2460750">delta</span> <span m="2461500">squared</span> <span m="2462010">over</span>
  <span m="2462250">2</span> <span m="2462880">times</span> <span m="2463570">size</span>
  <span m="2463930">of</span> <span m="2464050">A</span> <span m="2464260">squared.</span>
  <span m="2468250">So,</span> <span m="2469240">typically,</span> <span m="2470360">at</span>
  <span m="2470440">least</span> <span m="2470740">in</span> <span m="2470910">expectation,</span>
  <span m="2472030">you</span> <span m="2472150">do</span> <span m="2472270">not</span>
  <span m="2472510">expect</span> <span m="2473230">very</span> <span m="2473500">many</span>
  <span m="2473770">pairs</span> <span m="2474250">of</span> <span m="2474400">elements</span>
  <span m="2475390">in</span> <span m="2475570">U</span> <span m="2476260">with</span>
  <span m="2476950">few</span> <span m="2477400">common</span> <span m="2477970">neighbors.</span></p><p><span
  m="2480510">But</span> <span m="2480720">we</span> <span m="2480900">can</span>
  <span m="2481230">also</span> <span m="2481530">turn</span> <span m="2482100">such</span>
  <span m="2482340">an</span> <span m="2482430">estimate</span> <span m="2482940">into</span>
  <span m="2483270">a</span> <span m="2483990">specific</span> <span m="2484560">instance.</span>
  <span m="2488015">And</span> <span m="2488280">the</span> <span m="2488340">way</span>
  <span m="2488490">to</span> <span m="2488580">do</span> <span m="2488700">this</span>
  <span m="2489120">is</span> <span m="2489270">to</span> <span m="2489360">consider</span>
  <span m="2490650">the</span> <span m="2490710">quantity</span> <span m="2493130">size</span>
  <span m="2493520">of</span> <span m="2493600">U</span> <span m="2493840">squared</span>
  <span m="2494820">minus</span> <span m="2495720">x</span> <span m="2496260">over</span>
  <span m="2497040">epsilon.</span> <span m="2499280">Well,</span> <span m="2499410">first</span>
  <span m="2499710">of</span> <span m="2499830">all,</span> <span m="2500820">we</span>
  <span m="2500940">can</span> <span m="2501390">lower</span> <span m="2501720">bound</span>
  <span m="2502020">this</span> <span m="2502200">quantity,</span> <span m="2503070">because</span>
  <span m="2504300">the</span> <span m="2504390">size</span> <span m="2504840">of</span>
  <span m="2505890">second</span> <span m="2506460">moment</span> <span m="2506880">of</span>
  <span m="2506970">U</span> <span m="2507630">is</span> <span m="2507810">at</span>
  <span m="2507870">least</span> <span m="2508350">the</span> <span m="2508500">first</span>
  <span m="2508860">moment</span> <span m="2509250">of</span> <span m="2509340">U</span>
  <span m="2510870">squared.</span> <span m="2513030">And</span> <span m="2513660">we</span>
  <span m="2513870">also</span> <span m="2514110">know</span> <span m="2514410">that</span>
  <span m="2514710">the</span> <span m="2517740">size</span> <span m="2518490">of</span>
  <span m="2518910">x</span> <span m="2520950">in</span> <span m="2521160">expectation</span>
  <span m="2522450">is</span> <span m="2523260">not</span> <span m="2523530">very</span>
  <span m="2524070">large.</span> <span m="2524830">So</span> <span m="2524910">the</span>
  <span m="2525030">whole</span> <span m="2525480">expression</span> <span m="2526380">can</span>
  <span m="2526530">be</span> <span m="2526650">lower</span> <span m="2526920">bounded</span>
  <span m="2527700">by</span> <span m="2528540">delta</span> <span m="2530400">squared</span>
  <span m="2531840">over</span> <span m="2532290">2</span> <span m="2533040">times</span>
  <span m="2534080">the</span> <span m="2534210">size</span> <span m="2534630">of</span>
  <span m="2535110">A</span> <span m="2535470">squared.</span> <span m="2545630">So
  this is</span> <span m="2546130">epsilon,</span> <span m="2546480">sorry.</span></p><p><span
  m="2550120">Therefore,</span> <span m="2551840">there</span> <span m="2552090">is</span>
  <span m="2552150">some</span> <span m="2552960">concrete</span> <span m="2553530">instance</span>
  <span m="2554880">of</span> <span m="2555000">this</span> <span m="2555150">randomness</span>
  <span m="2555840">resulting</span> <span m="2556500">in</span> <span m="2556650">some</span>
  <span m="2556980">specific</span> <span m="2557610">U</span> <span m="2558810">such</span>
  <span m="2559110">that</span> <span m="2559740">this</span> <span m="2559950">inequality</span>
  <span m="2560520">holds.</span> <span m="2561180">So</span> <span m="2561390">there</span>
  <span m="2561570">exists</span> <span m="2562440">some</span> <span m="2562800">U</span>
  <span m="2564570">such</span> <span m="2564870">that</span> <span m="2568960">this</span>
  <span m="2569170">inequality</span> <span m="2573200">holds.</span> <span m="2574330">And,</span>
  <span m="2574700">in</span> <span m="2574830">particular,</span> <span m="2579800">we</span>
  <span m="2579920">find</span> <span m="2580490">that</span> <span m="2581330">the</span>
  <span m="2581480">size</span> <span m="2581900">of</span> <span m="2582020">U</span>
  <span m="2582260">is</span> <span m="2582470">at</span> <span m="2582560">least--</span>
  <span m="2583310">just</span> <span m="2583490">forget</span> <span m="2583820">about</span>
  <span m="2584040">this</span> <span m="2584180">minus</span> <span m="2584600">term--</span>
  <span m="2585110">is</span> <span m="2585380">at</span> <span m="2585470">least</span>
  <span m="2586390">that</span> <span m="2586520">right-hand</span> <span m="2586880">side,</span>
  <span m="2588110">square</span> <span m="2588410">root.</span> <span m="2588950">So,</span>
  <span m="2589250">in</span> <span m="2589460">particular,</span> <span m="2589880">the</span>
  <span m="2589970">size</span> <span m="2590330">of</span> <span m="2590450">U</span>
  <span m="2590780">is at</span> <span m="2590840">least</span> <span m="2591500">delta</span>
  <span m="2591860">over</span> <span m="2592100">2</span> <span m="2592910">times</span>
  <span m="2593240">the</span> <span m="2593300">size</span> <span m="2593630">of</span>
  <span m="2593720">A.</span> <span m="2594415">And,</span> <span m="2596840">just</span>
  <span m="2597050">looking</span> <span m="2597350">at</span> <span m="2597410">the</span>
  <span m="2597470">left-hand</span> <span m="2597830">side,</span> <span m="2598200">which</span>
  <span m="2598310">must</span> <span m="2598520">be</span> <span m="2598610">a</span>
  <span m="2598700">non-negative</span> <span m="2599330">quantity</span> <span m="2599900">because</span>
  <span m="2600230">the</span> <span m="2600320">right-hand</span> <span m="2600530">side</span>
  <span m="2600620">is</span> <span m="2600890">non-negative,</span> <span m="2602240">we</span>
  <span m="2602360">find</span> <span m="2602630">that</span> <span m="2602870">x</span>
  <span m="2603650">is,</span> <span m="2604250">at</span> <span m="2604520">most,</span>
  <span m="2606000">an</span> <span m="2606350">epsilon</span> <span m="2606800">fraction</span>
  <span m="2607580">of</span> <span m="2607910">U</span> <span m="2609317">squared.</span></p><p><span
  m="2614480">So</span> <span m="2614900">putting</span> <span m="2615200">these</span>
  <span m="2615590">together,</span> <span m="2616370">we</span> <span m="2618250">arrive</span>
  <span m="2618730">at</span> <span m="2619780">the</span> <span m="2619960">path</span>
  <span m="2620410">of</span> <span m="2620530">length</span> <span m="2620770">2</span>
  <span m="2621010">lemma.</span> <span m="2622280">So</span> <span m="2622530">let</span>
  <span m="2622650">me</span> <span m="2623160">go</span> <span m="2623310">through</span>
  <span m="2623430">it</span> <span m="2623520">again.</span> <span m="2623830">So</span>
  <span m="2623930">this</span> <span m="2624000">is</span> <span m="2624120">the</span>
  <span m="2624210">dependent</span> <span m="2624690">random</span> <span m="2624960">choice</span>
  <span m="2625320">method,</span> <span m="2626100">where</span> <span m="2628260">we're</span>
  <span m="2628380">going</span> <span m="2628500">to--</span> <span m="2628800">we</span>
  <span m="2629130">want</span> <span m="2629280">to</span> <span m="2629340">find</span>
  <span m="2629560">this</span> <span m="2629660">U,</span> <span m="2630480">where</span>
  <span m="2630810">most</span> <span m="2631200">pairs</span> <span m="2631560">of</span>
  <span m="2631620">vertices</span> <span m="2632100">in</span> <span m="2632190">U</span>
  <span m="2632430">have</span> <span m="2632730">lots</span> <span m="2633150">of</span>
  <span m="2634200">common</span> <span m="2634530">neighbors.</span> <span m="2635920">So</span>
  <span m="2636060">we</span> <span m="2637260">start</span> <span m="2637680">from</span>
  <span m="2637860">the</span> <span m="2637950">right</span> <span m="2638190">side.</span>
  <span m="2638640">We</span> <span m="2638790">start</span> <span m="2639120">from</span>
  <span m="2639330">B,</span> <span m="2640050">pick</span> <span m="2640290">a</span>
  <span m="2640350">uniform</span> <span m="2640770">random</span> <span m="2641070">vertex,</span>
  <span m="2642330">which</span> <span m="2642480">you</span> <span m="2642570">call</span>
  <span m="2642780">v,</span> <span m="2644100">and</span> <span m="2644220">let</span>
  <span m="2644460">U</span> <span m="2644910">be</span> <span m="2645120">the</span>
  <span m="2645270">neighborhood</span> <span m="2645960">of</span> <span m="2646400">v.</span>
  <span m="2648598">And I</span> <span m="2649090">claim</span> <span m="2649390">that</span>
  <span m="2649520">this</span> <span m="2649760">U,</span> <span m="2650210">typically,</span>
  <span m="2650900">should</span> <span m="2651140">have</span> <span m="2651350">the</span>
  <span m="2651440">desired</span> <span m="2651860">property.</span></p><p><span
  m="2653170">And</span> <span m="2653600">the</span> <span m="2653690">reason</span>
  <span m="2654140">is</span> <span m="2654560">that,</span> <span m="2655820">if</span>
  <span m="2655970">you</span> <span m="2656060">have</span> <span m="2656240">a</span>
  <span m="2656270">pair</span> <span m="2656660">of</span> <span m="2656840">vertices</span>
  <span m="2658160">on</span> <span m="2658280">the</span> <span m="2658370">left</span>
  <span m="2659930">that</span> <span m="2661040">do</span> <span m="2661190">not</span>
  <span m="2661370">have</span> <span m="2661640">many</span> <span m="2661910">common</span>
  <span m="2662240">neighbors,</span> <span m="2664030">then</span> <span m="2664240">I</span>
  <span m="2664300">claim</span> <span m="2664690">it</span> <span m="2664810">is</span>
  <span m="2664930">highly</span> <span m="2665290">unlikely</span> <span m="2666550">that</span>
  <span m="2666760">these</span> <span m="2667030">two</span> <span m="2667360">vertices</span>
  <span m="2668620">both</span> <span m="2669100">appear</span> <span m="2670030">in</span>
  <span m="2670270">U.</span> <span m="2671500">Because</span> <span m="2672070">for</span>
  <span m="2672310">them</span> <span m="2672550">to</span> <span m="2672670">both</span>
  <span m="2672970">appear</span> <span m="2673360">in</span> <span m="2673520">U,</span>
  <span m="2674260">your</span> <span m="2674530">v</span> <span m="2675490">have</span>
  <span m="2675580">been</span> <span m="2675730">selected</span> <span m="2676690">inside</span>
  <span m="2677320">the</span> <span m="2677410">common</span> <span m="2677770">neighborhood</span>
  <span m="2678310">of</span> <span m="2678490">a</span> <span m="2678760">and</span>
  <span m="2679030">a prime,</span> <span m="2680320">which</span> <span m="2680530">is</span>
  <span m="2680650">unlikely</span> <span m="2681350">if</span> <span m="2681590">a</span>
  <span m="2681820">and</span> <span m="2682000">a prime</span> <span m="2682390">have</span>
  <span m="2682640">few</span> <span m="2682960">common</span> <span m="2683320">neighbors.</span>
  <span m="2686550">So,</span> <span m="2687770">as</span> <span m="2687890">a</span>
  <span m="2687950">result,</span> <span m="2688530">the</span> <span m="2688610">expected</span>
  <span m="2689240">number</span> <span m="2690050">of</span> <span m="2690890">pairs</span>
  <span m="2692050">in</span> <span m="2692300">U</span> <span m="2692900">with</span>
  <span m="2693380">small</span> <span m="2693710">number</span> <span m="2694010">of</span>
  <span m="2694070">common</span> <span m="2694400">neighbors</span> <span m="2695360">is</span>
  <span m="2695780">small.</span></p><p><span m="2698380">And,</span> <span m="2698650">already,</span>
  <span m="2698920">that's</span> <span m="2699160">a</span> <span m="2699190">very</span>
  <span m="2699400">good</span> <span m="2699670">indication</span> <span m="2700130">that</span>
  <span m="2700210">we're</span> <span m="2700360">on</span> <span m="2700450">the</span>
  <span m="2700540">right</span> <span m="2700720">track.</span> <span m="2701020">And,</span>
  <span m="2701230">to</span> <span m="2701320">finish</span> <span m="2701680">things</span>
  <span m="2701920">off,</span> <span m="2702340">we</span> <span m="2702490">look</span>
  <span m="2702670">at</span> <span m="2702790">this</span> <span m="2703000">expression,</span>
  <span m="2705340">which</span> <span m="2705550">we</span> <span m="2705670">can</span>
  <span m="2705820">lower</span> <span m="2706060">bound</span> <span m="2706450">by</span>
  <span m="2707050">convexity.</span> <span m="2707830">And</span> <span m="2707950">we</span>
  <span m="2708100">know</span> <span m="2708310">the</span> <span m="2708460">size</span>
  <span m="2708880">of</span> <span m="2708970">U</span> <span m="2709210">in</span>
  <span m="2709270">expectation</span> <span m="2709960">is</span> <span m="2710110">large.</span>
  <span m="2710890">And,</span> <span m="2711070">also,</span> <span m="2711700">the</span>
  <span m="2711790">size</span> <span m="2712150">of</span> <span m="2712240">x,</span>
  <span m="2712570">that</span> <span m="2712810">we</span> <span m="2712930">just</span>
  <span m="2713110">saw,</span> <span m="2713470">is</span> <span m="2714580">small</span>
  <span m="2715000">in</span> <span m="2715150">expectation.</span> <span m="2717260">So</span>
  <span m="2718000">you</span> <span m="2718090">have</span> <span m="2718300">this</span>
  <span m="2718480">inequality</span> <span m="2718990">over</span> <span m="2719200">here.</span></p><p><span
  m="2719890">And</span> <span m="2719950">because</span> <span m="2720460">there's</span>
  <span m="2720670">an</span> <span m="2720790">expectation,</span> <span m="2721690">it</span>
  <span m="2722170">implies</span> <span m="2722740">that</span> <span m="2722830">there's</span>
  <span m="2722990">some</span> <span m="2723250">specific</span> <span m="2723820">instance</span>
  <span m="2725200">such</span> <span m="2725430">that,</span> <span m="2725560">without</span>
  <span m="2725890">the</span> <span m="2726010">expectation,</span> <span m="2727230">the</span>
  <span m="2727330">inequality</span> <span m="2727870">holds.</span> <span m="2728800">So</span>
  <span m="2728950">take</span> <span m="2729160">that</span> <span m="2729310">specific</span>
  <span m="2729820">instance.</span> <span m="2730570">We</span> <span m="2730720">obtain</span>
  <span m="2731110">some</span> <span m="2731350">U</span> <span m="2732100">such</span>
  <span m="2732430">that</span> <span m="2733030">this</span> <span m="2733210">inequality</span>
  <span m="2733720">is</span> <span m="2733870">true,</span> <span m="2734740">which</span>
  <span m="2735010">simultaneously</span> <span m="2735820">implies</span> <span m="2736300">that</span>
  <span m="2736420">U</span> <span m="2736720">is</span> <span m="2736900">large</span>
  <span m="2737800">and</span> <span m="2738430">x,</span> <span m="2738900">the</span>
  <span m="2739030">number</span> <span m="2739300">of</span> <span m="2739420">bad</span>
  <span m="2739660">pairs,</span> <span m="2740230">is</span> <span m="2740560">small.</span>
  <span m="2743796">So</span> <span m="2744280">that</span> <span m="2744500">was</span>
  <span m="2744820">dependent</span> <span m="2745240">random</span> <span m="2745510">choice.</span>
  <span m="2747850">Any</span> <span m="2748100">questions?</span> <span m="2751731">All</span>
  <span m="2752657">right.</span></p><p><span m="2754046">So</span> <span m="2754510">that</span>
  <span m="2754630">was</span> <span m="2754780">the</span> <span m="2754840">path</span>
  <span m="2755140">of</span> <span m="2755200">length</span> <span m="2755410">2</span>
  <span m="2755620">lemma.</span> <span m="2756250">So it</span> <span m="2756450">tells</span>
  <span m="2756700">us</span> <span m="2756820">I</span> <span m="2756880">can</span>
  <span m="2757000">take</span> <span m="2757210">a</span> <span m="2757240">large</span>
  <span m="2757480">set</span> <span m="2757900">with</span> <span m="2758110">lots</span>
  <span m="2758380">of</span> <span m="2758860">paths</span> <span m="2759190">of</span>
  <span m="2759280">length</span> <span m="2759460">2</span> <span m="2759700">between</span>
  <span m="2760060">most</span> <span m="2760390">pairs</span> <span m="2760720">of</span>
  <span m="2760780">vertices.</span> <span m="2762590">Let's</span> <span m="2764190">upgrade</span>
  <span m="2764640">this</span> <span m="2764810">lemma</span> <span m="2765750">to</span>
  <span m="2766050">a</span> <span m="2766290">path</span> <span m="2766710">of</span>
  <span m="2766830">length</span> <span m="2767120">3</span> <span m="2767390">lemma.</span>
  <span m="2778850">So,</span> <span m="2779140">in the</span> <span m="2779230">path</span>
  <span m="2779560">of</span> <span m="2779680">length</span> <span m="2779890">3</span>
  <span m="2780130">lemma,</span> <span m="2780640">we</span> <span m="2780790">start</span>
  <span m="2781150">with</span> <span m="2781360">a</span> <span m="2781450">bipartite</span>
  <span m="2781890">graph,</span> <span m="2782220">as</span> <span m="2782380">before,</span>
  <span m="2783400">between</span> <span m="2784000">A</span> <span m="2784210">and</span>
  <span m="2784450">B.</span> <span m="2787378">So G</span> <span m="2787820">is a</span>
  <span m="2788200">bipartite</span> <span m="2789370">between</span> <span m="2791590">A</span>
  <span m="2791890">and</span> <span m="2792370">B.</span> <span m="2793970">And,</span>
  <span m="2794930">as</span> <span m="2795100">before,</span> <span m="2795490">we</span>
  <span m="2795700">have</span> <span m="2796870">a</span> <span m="2796930">lot</span>
  <span m="2797170">of</span> <span m="2797290">edges</span> <span m="2797650">between</span>
  <span m="2797995">A</span> <span m="2798340">and</span> <span m="2798610">B.</span>
  <span m="2799230">It's</span> <span m="2799670">the</span> <span m="2799880">delta</span>
  <span m="2800170">fraction</span> <span m="2800680">of</span> <span m="2800800">all</span>
  <span m="2800920">possible</span> <span m="2801430">edges.</span> <span m="2802690">Then</span>
  <span m="2802840">the</span> <span m="2802930">conclusion</span> <span m="2804760">is</span>
  <span m="2804910">that</span> <span m="2805120">there</span> <span m="2805300">exists</span>
  <span m="2806530">A</span> <span m="2806680">prime</span> <span m="2807880">in</span>
  <span m="2808710">A</span> <span m="2810246">and</span> <span m="2810660">B</span>
  <span m="2810840">prime</span> <span m="2812980">subset</span> <span m="2813370">of</span>
  <span m="2813460">B</span> <span m="2814870">such</span> <span m="2815170">that</span>
  <span m="2816220">A</span> <span m="2816370">prime</span> <span m="2817000">and</span>
  <span m="2817120">B</span> <span m="2817270">prime</span> <span m="2817690">are</span>
  <span m="2817810">both</span> <span m="2818500">large</span> <span m="2818920">fractions</span>
  <span m="2820300">of</span> <span m="2820540">their</span> <span m="2820800">parent</span>
  <span m="2821260">set.</span></p><p><span m="2828070">And</span> <span m="2828170">now,</span>
  <span m="2828520">the--</span> <span m="2829140">and,</span> <span m="2829400">furthermore,</span>
  <span m="2831380">every</span> <span m="2832610">pair</span> <span m="2835820">between</span>
  <span m="2836750">A</span> <span m="2836900">prime</span> <span m="2837290">and</span>
  <span m="2837380">B</span> <span m="2837530">prime</span> <span m="2840420">is</span>
  <span m="2841440">joined</span> <span m="2844390">by</span> <span m="2846910">many</span>
  <span m="2847240">paths</span> <span m="2847840">of</span> <span m="2848080">length</span>
  <span m="2848400">3.</span> <span m="2856820">So</span> <span m="2857290">a</span>
  <span m="2857350">path</span> <span m="2857680">of</span> <span m="2857770">length</span>
  <span m="2857980">3</span> <span m="2858160">means</span> <span m="2858430">there's</span>
  <span m="2858640">3</span> <span m="2858940">edges.</span> <span m="2862610">And,</span>
  <span m="2862780">here,</span> <span m="2865420">this</span> <span m="2865930">eta</span>
  <span m="2866800">is</span> <span m="2868150">basically</span> <span m="2868630">the</span>
  <span m="2868810">original</span> <span m="2869530">error</span> <span m="2869770">term</span>
  <span m="2870130">up</span> <span m="2870280">to</span> <span m="2870430">a</span>
  <span m="2870490">polynomial</span> <span m="2871210">change.</span> <span m="2880270">So</span>
  <span m="2881000">starting</span> <span m="2881390">with</span> <span m="2881840">this</span>
  <span m="2882500">bipartite</span> <span m="2882950">graph</span> <span m="2883310">that's</span>
  <span m="2883610">fairly</span> <span m="2884030">dense,</span> <span m="2885020">the</span>
  <span m="2885860">lemma</span> <span m="2886250">tells</span> <span m="2886580">us</span>
  <span m="2886790">that</span> <span m="2886920">we</span> <span m="2887060">can</span>
  <span m="2887330">find</span> <span m="2888500">some</span> <span m="2889430">large</span>
  <span m="2890300">A</span> <span m="2890420">prime</span> <span m="2891700">and</span>
  <span m="2891860">large</span> <span m="2892910">B</span> <span m="2893060">prime</span>
  <span m="2893750">so</span> <span m="2893870">that</span> <span m="2894020">between</span>
  <span m="2894920">every</span> <span m="2895160">vertex</span> <span m="2895430">in</span>
  <span m="2895700">A</span> <span m="2895820">prime</span> <span m="2896270">and</span>
  <span m="2896450">every</span> <span m="2896750">vertex</span> <span m="2897200">in</span>
  <span m="2897290">B</span> <span m="2897440">prime,</span> <span m="2898220">there</span>
  <span m="2898400">are</span> <span m="2898610">lots</span> <span m="2899090">of</span>
  <span m="2899990">paths</span> <span m="2900500">of</span> <span m="2900650">length</span>
  <span m="2900920">3</span> <span m="2901490">between</span> <span m="2901850">them.</span>
  <span m="2908530">Every</span> <span m="2908770">time.</span></p><p><span m="2913500">So</span>
  <span m="2914670">we</span> <span m="2914790">should</span> <span m="2914970">think</span>
  <span m="2915120">about</span> <span m="2915210">all</span> <span m="2915390">of</span>
  <span m="2915450">these</span> <span m="2915740">constants</span> <span m="2916225">as--</span>
  <span m="2917215">plus</span> <span m="2917490">you</span> <span m="2917700">only</span>
  <span m="2917970">make</span> <span m="2918180">polynomial</span> <span m="2918750">changes</span>
  <span m="2919140">in</span> <span m="2919230">the</span> <span m="2919290">constants,</span>
  <span m="2919830">we're</span> <span m="2920000">happy.</span> <span m="2922290">Here,</span>
  <span m="2923010">eta</span> <span m="2923400">is</span> <span m="2923830">a</span>
  <span m="2923870">polynomial</span> <span m="2924390">change</span> <span m="2924720">in</span>
  <span m="2924840">the</span> <span m="2924900">delta.</span> <span m="2926560">There's</span>
  <span m="2926880">a</span> <span m="2926940">convention</span> <span m="2927390">which</span>
  <span m="2927570">I</span> <span m="2927660">like</span> <span m="2927990">which</span>
  <span m="2928170">is</span> <span m="2928380">not</span> <span m="2928650">universal,</span>
  <span m="2929130">but</span> <span m="2929900">it's</span> <span m="2930240">often</span>
  <span m="2930520">solved,</span> <span m="2930990">unlike</span> <span m="2931170">this</span>
  <span m="2931320">convention.</span> <span m="2931860">It's</span> <span m="2932550">the</span>
  <span m="2932670">difference</span> <span m="2933060">between</span> <span m="2933360">the</span>
  <span m="2933420">little</span> <span m="2933690">c</span> <span m="2933930">and</span>
  <span m="2934020">the</span> <span m="2934050">big</span> <span m="2934230">C</span>
  <span m="2935150">is</span> <span m="2935580">that a</span> <span m="2935760">little</span>
  <span m="2936030">c</span> <span m="2936240">is</span> <span m="2936360">better</span>
  <span m="2936630">if</span> <span m="2936720">you</span> <span m="2936810">make</span>
  <span m="2936990">it</span> <span m="2937050">smaller,</span> <span m="2938090">and</span>
  <span m="2938210">a</span> <span m="2938250">big</span> <span m="2938490">C</span>
  <span m="2938700">is</span> <span m="2938850">better--</span> <span m="2939440">I</span>
  <span m="2939470">mean,</span> <span m="2939580">it's</span> <span m="2941130">better</span>
  <span m="2941400">in</span> <span m="2941460">the</span> <span m="2941520">sense</span>
  <span m="2941730">that</span> <span m="2942030">if</span> <span m="2942240">this</span>
  <span m="2942420">is</span> <span m="2942540">true</span> <span m="2942870">for</span>
  <span m="2943120">little</span> <span m="2943150">c</span> <span m="2943380">and</span>
  <span m="2943700">big C,</span> <span m="2944780">and</span> <span m="2944910">you</span>
  <span m="2944970">make</span> <span m="2945260">little</span> <span m="2945450">c</span>
  <span m="2945630">smaller</span> <span m="2946080">and</span> <span m="2946170">big</span>
  <span m="2946350">C</span> <span m="2946530">bigger,</span> <span m="2947340">then</span>
  <span m="2947640">it</span> <span m="2947760">is</span> <span m="2948060">still</span>
  <span m="2948360">true.</span> <span m="2950050">So</span> <span m="2950610">big</span>
  <span m="2950820">C</span> <span m="2951060">is</span> <span m="2951180">a</span>
  <span m="2951240">sufficiently</span> <span m="2951810">large</span> <span m="2952080">constant,</span>
  <span m="2952570">and</span> <span m="2952620">little</span> <span m="2952860">c</span>
  <span m="2953030">is a</span> <span m="2953190">sufficiently</span> <span m="2953670">small</span>
  <span m="2953940">constant.</span> <span m="2955436">Just</span> <span m="2955929">a--</span></p><p><span
  m="2970740">So</span> <span m="2970790">let's</span> <span m="2971240">see</span>
  <span m="2971540">the</span> <span m="2971660">path</span> <span m="2972260">of</span>
  <span m="2972380">length</span> <span m="2972620">3</span> <span m="2972800">lemma,</span>
  <span m="2973700">see</span> <span m="2973940">it's</span> <span m="2974060">proof.</span>
  <span m="2976650">We're</span> <span m="2976840">going</span> <span m="2976920">to</span>
  <span m="2977030">use</span> <span m="2977230">the</span> <span m="2977260">path</span>
  <span m="2977450">of</span> <span m="2977600">length</span> <span m="2977810">2</span>
  <span m="2977970">lemma,</span> <span m="2979460">but</span> <span m="2979610">we</span>
  <span m="2979760">need</span> <span m="2979970">a</span> <span m="2980030">bit</span>
  <span m="2980180">of</span> <span m="2980240">preparation</span> <span m="2980870">first.</span>
  <span m="2982070">So</span> <span m="2982250">the</span> <span m="2982340">proof</span>
  <span m="2984550">has</span> <span m="2984680">some</span> <span m="2984860">nice</span>
  <span m="2985220">ideas,</span> <span m="2985740">but</span> <span m="2986030">it's</span>
  <span m="2986180">also--</span> <span m="2986930">some</span> <span m="2987170">parts</span>
  <span m="2987440">of</span> <span m="2987530">it</span> <span m="2987650">are</span>
  <span m="2987950">slightly</span> <span m="2988340">tedious,</span> <span m="2988790">so</span>
  <span m="2989210">bear</span> <span m="2989420">with</span> <span m="2989600">me.</span>
  <span m="2990740">So</span> <span m="2990860">we're</span> <span m="2991010">going</span>
  <span m="2991160">to</span> <span m="2991250">construct</span> <span m="2995230">a</span>
  <span m="2995290">chain</span> <span m="2995800">of</span> <span m="2995860">subsets</span>
  <span m="2996880">A--</span> <span m="2998690">inside</span> <span m="2999160">A.</span>
  <span m="2999370">So</span> <span m="2999580">A1,</span> <span m="3000450">A2,</span>
  <span m="3001645">A3.</span> <span m="3002970">And</span> <span m="3003090">this</span>
  <span m="3003270">is</span> <span m="3003330">just</span> <span m="3003480">because</span>
  <span m="3003750">there's</span> <span m="3003870">a</span> <span m="3003930">few</span>
  <span m="3004200">cleaning</span> <span m="3004680">up</span> <span m="3004800">steps</span>
  <span m="3005190">that</span> <span m="3005310">need</span> <span m="3005490">to</span>
  <span m="3005550">be</span> <span m="3005700">done.</span></p><p><span m="3008100">Let's</span>
  <span m="3008340">call</span> <span m="3010410">two</span> <span m="3010650">vertices</span>
  <span m="3014520">in</span> <span m="3015180">A</span> <span m="3015810">friendly</span>
  <span m="3019880">if</span> <span m="3020980">they</span> <span m="3021100">have</span>
  <span m="3021490">lots</span> <span m="3021790">of</span> <span m="3021910">common</span>
  <span m="3022210">neighbors.</span> <span m="3023980">And,</span> <span m="3024140">precisely,</span>
  <span m="3024850">we're</span> <span m="3025000">going</span> <span m="3025140">to</span>
  <span m="3025240">say</span> <span m="3025430">they're</span> <span m="3025870">friendly</span>
  <span m="3026350">if</span> <span m="3026470">they</span> <span m="3026590">have</span>
  <span m="3027280">more</span> <span m="3027550">than</span> <span m="3028450">delta</span>
  <span m="3028750">squared</span> <span m="3029410">over</span> <span m="3029890">80</span>
  <span m="3032410">times</span> <span m="3032710">the</span> <span m="3032770">size</span>
  <span m="3033070">of</span> <span m="3033130">B</span> <span m="3033460">common</span>
  <span m="3033820">neighbors.</span> <span m="3041770">Let</span> <span m="3041860">me</span>
  <span m="3041990">construct</span> <span m="3042590">this</span> <span m="3043310">sequence</span>
  <span m="3043880">of</span> <span m="3044000">subsets</span> <span m="3044870">as</span>
  <span m="3044990">follows.</span> <span m="3046590">First,</span> <span m="3048470">let</span>
  <span m="3049340">A1</span> <span m="3049790">be</span> <span m="3051760">all</span>
  <span m="3051960">the</span> <span m="3052120">vertices</span> <span m="3052910">in</span>
  <span m="3053150">A</span> <span m="3053870">with</span> <span m="3055070">degree</span>
  <span m="3055640">not</span> <span m="3055970">too</span> <span m="3056270">small.</span>
  <span m="3058200">So</span> <span m="3061450">this</span> <span m="3061630">is</span>
  <span m="3061720">in</span> <span m="3061840">preparation.</span> <span m="3062500">So</span>
  <span m="3062680">it will</span> <span m="3062890">make</span> <span m="3063130">our</span>
  <span m="3063220">life</span> <span m="3063790">quite</span> <span m="3064030">a</span>
  <span m="3064060">bit</span> <span m="3064240">easier</span> <span m="3064810">later</span>
  <span m="3065110">on.</span> <span m="3065950">Let's</span> <span m="3066220">just</span>
  <span m="3066430">trim</span> <span m="3066990">all</span> <span m="3067130">the</span>
  <span m="3067330">really</span> <span m="3067600">small</span> <span m="3067990">degree</span>
  <span m="3068260">vertices</span> <span m="3069100">so</span> <span m="3069220">that</span>
  <span m="3069400">we</span> <span m="3069520">don't</span> <span m="3069670">have</span>
  <span m="3069790">to</span> <span m="3069880">think</span> <span m="3070090">about</span>
  <span m="3070240">them.</span></p><p><span m="3071850">So you</span> <span m="3072090">trim</span>
  <span m="3072380">all</span> <span m="3072510">the</span> <span m="3072600">small</span>
  <span m="3072900">degree</span> <span m="3073140">vertices.</span> <span m="3075870">And</span>
  <span m="3078230">think</span> <span m="3078380">about</span> <span m="3078530">how</span>
  <span m="3078680">many</span> <span m="3078920">edges</span> <span m="3079310">you</span>
  <span m="3079430">trim.</span> <span m="3080420">You</span> <span m="3080570">cannot</span>
  <span m="3080900">trim</span> <span m="3081230">so</span> <span m="3081410">many</span>
  <span m="3081680">edges,</span> <span m="3082460">because</span> <span m="3083840">each</span>
  <span m="3084080">time</span> <span m="3084440">you</span> <span m="3084710">trim</span>
  <span m="3085100">such</span> <span m="3085700">a</span> <span m="3085760">vertex,</span>
  <span m="3086750">you</span> <span m="3086870">only</span> <span m="3087110">get</span>
  <span m="3087260">rid</span> <span m="3087470">of</span> <span m="3087590">a</span>
  <span m="3087650">small</span> <span m="3087980">number</span> <span m="3088340">of</span>
  <span m="3088520">edges.</span> <span m="3090100">So,</span> <span m="3090340">in</span>
  <span m="3090460">the</span> <span m="3090580">end,</span> <span m="3090940">at</span>
  <span m="3091030">least</span> <span m="3091570">half</span> <span m="3092140">of</span>
  <span m="3092410">the</span> <span m="3092590">original</span> <span m="3093100">set</span>
  <span m="3093310">of</span> <span m="3093400">edges</span> <span m="3094300">must</span>
  <span m="3094570">remain.</span> <span m="3096690">And,</span> <span m="3097530">as</span>
  <span m="3097710">a</span> <span m="3097770">result,</span> <span m="3099610">the</span>
  <span m="3099630">size</span> <span m="3100110">of</span> <span m="3100590">A1</span>
  <span m="3101490">is</span> <span m="3101940">at</span> <span m="3102060">least</span>
  <span m="3103320">a</span> <span m="3103380">delta</span> <span m="3103860">over</span>
  <span m="3104100">2</span> <span m="3104370">fraction</span> <span m="3105780">of</span>
  <span m="3107070">the</span> <span m="3107190">original</span> <span m="3107820">vertex</span>
  <span m="3108270">set.</span> <span m="3110590">Otherwise,</span> <span m="3110950">you</span>
  <span m="3111040">could</span> <span m="3111160">not</span> <span m="3111340">have</span>
  <span m="3111490">contained</span> <span m="3112600">half</span> <span m="3113050">of</span>
  <span m="3114040">the</span> <span m="3114130">original</span> <span m="3114550">set</span>
  <span m="3114760">of</span> <span m="3114850">edges.</span> <span m="3117460">So</span>
  <span m="3117630">this</span> <span m="3117800">is</span> <span m="3117920">the</span>
  <span m="3118010">first</span> <span m="3118760">trimming</span> <span m="3119130">step.</span>
  <span m="3122180">So</span> <span m="3122380">we</span> <span m="3122560">got</span>
  <span m="3122800">rid</span> <span m="3123010">of</span> <span m="3124390">some</span>
  <span m="3124720">edges,</span> <span m="3125110">but</span> <span m="3125230">we</span>
  <span m="3125380">got</span> <span m="3125560">rid</span> <span m="3125740">of</span>
  <span m="3126280">fewer</span> <span m="3126730">than</span> <span m="3126970">half</span>
  <span m="3127390">of</span> <span m="3127510">the</span> <span m="3127660">original</span>
  <span m="3128380">edges.</span> <span m="3130940">And</span> <span m="3131540">because</span>
  <span m="3132050">now</span> <span m="3132380">you</span> <span m="3132530">have</span>
  <span m="3132710">a</span> <span m="3132770">minimum</span> <span m="3133190">degree</span>
  <span m="3133820">on</span> <span m="3134030">A1,</span> <span m="3135720">the</span>
  <span m="3135840">number</span> <span m="3136170">of</span> <span m="3136290">edges</span>
  <span m="3136650">between</span> <span m="3137070">A1</span> <span m="3137460">and</span>
  <span m="3137550">B</span> <span m="3138670">is</span> <span m="3139140">quite</span>
  <span m="3139380">large,</span> <span m="3140520">still</span> <span m="3140760">quite</span>
  <span m="3140970">large.</span> <span m="3142660">So</span> <span m="3142730">think</span>
  <span m="3142940">about</span> <span m="3143150">passing</span> <span m="3143540">down</span>
  <span m="3143750">to</span> <span m="3143840">A1</span> <span m="3144190">now.</span></p><p><span
  m="3147040">In</span> <span m="3147180">the</span> <span m="3147240">second</span>
  <span m="3147510">step,</span> <span m="3148470">we</span> <span m="3148620">are</span>
  <span m="3148770">going</span> <span m="3149040">to</span> <span m="3149940">apply</span>
  <span m="3150480">the</span> <span m="3150570">path</span> <span m="3150960">of</span>
  <span m="3151050">length</span> <span m="3151320">2</span> <span m="3151530">lemma</span>
  <span m="3152730">to</span> <span m="3153030">this</span> <span m="3153250">A1.</span>
  <span m="3154480">So</span> <span m="3154720">A2</span> <span m="3156250">is</span>
  <span m="3156420">going</span> <span m="3156600">to</span> <span m="3156690">be</span>
  <span m="3156780">constructed</span> <span m="3161040">from--</span> <span m="3161880">so</span>
  <span m="3162120">using</span> <span m="3163950">the</span> <span m="3164040">path</span>
  <span m="3164400">of</span> <span m="3164490">length</span> <span m="3164730">2</span>
  <span m="3164910">lemma,</span> <span m="3170170">specifically</span> <span m="3170800">with</span>
  <span m="3171040">parameter</span> <span m="3172810">epsilon</span> <span m="3173650">being</span>
  <span m="3174460">delta</span> <span m="3174850">over</span> <span m="3175090">10.</span>
  <span m="3176620">Although,</span> <span m="3176800">remember,</span> <span m="3177100">now</span>
  <span m="3177850">the</span> <span m="3178030">density</span> <span m="3178690">of</span>
  <span m="3178810">the</span> <span m="3178900">graph</span> <span m="3179440">went</span>
  <span m="3179740">from</span> <span m="3179980">delta</span> <span m="3180400">to</span>
  <span m="3180520">delta</span> <span m="3180790">over</span> <span m="3181030">2.</span>
  <span m="3181760">Again,</span> <span m="3182010">if</span> <span m="3182080">you</span>
  <span m="3182170">don't</span> <span m="3182410">care</span> <span m="3182710">about</span>
  <span m="3182920">the</span> <span m="3183010">specific</span> <span m="3183550">numbers,</span>
  <span m="3184320">they're</span> <span m="3184450">all</span> <span m="3184570">polynomials</span>
  <span m="3185170">in</span> <span m="3185260">delta.</span> <span m="3185620">So</span>
  <span m="3185800">don't</span> <span m="3185950">worry</span> <span m="3186160">about</span>
  <span m="3186370">them.</span> <span m="3186520">Everything's</span> <span m="3186930">poly</span>
  <span m="3187210">delta.</span></p><p><span m="3188590">So</span> <span m="3188740">we're</span>
  <span m="3188830">going</span> <span m="3189040">to</span> <span m="3189280">apply</span>
  <span m="3189700">the</span> <span m="3189790">path</span> <span m="3190090">of</span>
  <span m="3190180">length</span> <span m="3190360">2</span> <span m="3190540">lemma</span>
  <span m="3191860">to</span> <span m="3191980">find</span> <span m="3194080">this</span>
  <span m="3194590">subset</span> <span m="3195250">A2.</span> <span m="3196240">And</span>
  <span m="3196390">it</span> <span m="3196480">has</span> <span m="3196680">the</span>
  <span m="3196720">property</span> <span m="3197560">that</span> <span m="3197840">A2</span>
  <span m="3199330">is</span> <span m="3200080">quite</span> <span m="3200860">large,</span>
  <span m="3205660">and</span> <span m="3209670">all</span> <span m="3209940">but</span>
  <span m="3211110">a</span> <span m="3211170">small</span> <span m="3211530">fraction</span>
  <span m="3216950">of</span> <span m="3217590">pairs</span> <span m="3222520">in</span>
  <span m="3222800">A2</span> <span m="3224270">are</span> <span m="3224870">friendly.</span>
  <span m="3234580">So</span> <span m="3235100">we</span> <span m="3235220">passed</span>
  <span m="3235570">down</span> <span m="3235850">to,</span> <span m="3236210">first,</span>
  <span m="3236630">trimming</span> <span m="3237800">small</span> <span m="3238100">degree</span>
  <span m="3238340">vertices,</span> <span m="3239540">and</span> <span m="3239660">then</span>
  <span m="3239780">passed</span> <span m="3240050">down</span> <span m="3240260">further</span>
  <span m="3241100">to</span> <span m="3241310">A2,</span> <span m="3242120">where</span>
  <span m="3243410">all</span> <span m="3243560">but</span> <span m="3243740">a</span>
  <span m="3243800">small</span> <span m="3244100">fraction</span> <span m="3244610">of</span>
  <span m="3244760">elements</span> <span m="3245150">in</span> <span m="3245270">A2,</span>
  <span m="3246020">or</span> <span m="3246260">all</span> <span m="3246340">but</span>
  <span m="3246530">a</span> <span m="3246560">small</span> <span m="3246830">fraction</span>
  <span m="3247220">of</span> <span m="3247280">the</span> <span m="3247340">pairs</span>
  <span m="3248740">are</span> <span m="3248870">friendly</span> <span m="3249290">to</span>
  <span m="3249440">each</span> <span m="3249590">other,</span> <span m="3249960">meaning</span>
  <span m="3250130">they</span> <span m="3250230">have</span> <span m="3250400">lots</span>
  <span m="3250670">of</span> <span m="3250730">common</span> <span m="3251100">neighbors.</span></p><p><span
  m="3255020">And</span> <span m="3255120">now</span> <span m="3255220">let's</span>
  <span m="3255430">look</span> <span m="3255640">at</span> <span m="3255700">the</span>
  <span m="3255820">other</span> <span m="3256060">side.</span> <span m="3256870">Let's</span>
  <span m="3257110">look</span> <span m="3257290">at</span> <span m="3257410">B.</span>
  <span m="3260020">So</span> <span m="3260530">we're</span> <span m="3260740">in</span>
  <span m="3260920">this</span> <span m="3261020">situation</span> <span m="3261610">now</span>
  <span m="3261880">where</span> <span m="3263890">you</span> <span m="3264130">have--</span>
  <span m="3267760">so</span> <span m="3268740">we're</span> <span m="3268960">now</span>
  <span m="3269170">in</span> <span m="3269290">a</span> <span m="3269320">situation</span>
  <span m="3270400">where</span> <span m="3270550">you've</span> <span m="3270710">passed</span>
  <span m="3271090">down</span> <span m="3271390">to</span> <span m="3272410">A2</span>
  <span m="3276810">and</span> <span m="3278010">in</span> <span m="3278370">B,</span>
  <span m="3279900">where,</span> <span m="3280380">because</span> <span m="3280980">of</span>
  <span m="3281100">what</span> <span m="3281250">we</span> <span m="3281400">did</span>
  <span m="3281610">initially,</span> <span m="3282630">every</span> <span m="3282870">vertex</span>
  <span m="3283800">in</span> <span m="3283920">here</span> <span m="3284400">have</span>
  <span m="3286080">large</span> <span m="3286410">degree.</span> <span m="3287410">So</span>
  <span m="3287670">there's</span> <span m="3288390">this</span> <span m="3288570">minimum</span>
  <span m="3289200">degree</span> <span m="3289500">condition</span> <span m="3293830">from</span>
  <span m="3294130">every</span> <span m="3294340">vertex</span> <span m="3295060">on</span>
  <span m="3295180">the</span> <span m="3295270">left.</span> <span m="3297190">So</span>
  <span m="3298410">the</span> <span m="3298560">average</span> <span m="3299040">degree</span>
  <span m="3299370">is</span> <span m="3299430">still</span> <span m="3299700">very</span>
  <span m="3299940">high.</span> <span m="3302960">As</span> <span m="3303110">a</span>
  <span m="3303170">result,</span> <span m="3305340">the</span> <span m="3305440">average</span>
  <span m="3305660">degree</span> <span m="3306050">from</span> <span m="3306380">B</span>
  <span m="3307020">is</span> <span m="3307250">going</span> <span m="3307400">to</span>
  <span m="3307460">be</span> <span m="3307580">quite</span> <span m="3307820">high.</span>
  <span m="3309280">So</span> <span m="3309360">let's</span> <span m="3309600">focus</span>
  <span m="3309990">on</span> <span m="3310080">the</span> <span m="3310140">B</span>
  <span m="3310320">side</span> <span m="3311150">and</span> <span m="3311400">pick</span>
  <span m="3311680">out</span> <span m="3312210">vertices</span> <span m="3312960">in</span>
  <span m="3313110">B</span> <span m="3313720">that</span> <span m="3313950">have</span>
  <span m="3314350">high</span> <span m="3314640">degree.</span></p><p><span m="3316570">So</span>
  <span m="3316720">let's</span> <span m="3316930">B1</span> <span m="3317660">denote</span>
  <span m="3320900">vertices</span> <span m="3321590">in</span> <span m="3321890">B</span>
  <span m="3323090">such</span> <span m="3323390">that</span> <span m="3324170">the</span>
  <span m="3324300">degree</span> <span m="3325310">from</span> <span m="3325700">B</span>
  <span m="3326480">to</span> <span m="3326720">A2</span> <span m="3327980">is</span>
  <span m="3328910">at</span> <span m="3329000">least</span> <span m="3329990">half</span>
  <span m="3330530">of</span> <span m="3331160">what</span> <span m="3331310">you</span>
  <span m="3331460">expect</span> <span m="3332090">based</span> <span m="3332450">on</span>
  <span m="3332690">average</span> <span m="3333110">degree.</span> <span m="3337850">And,</span>
  <span m="3338120">as</span> <span m="3338330">before,</span> <span m="3338750">the</span>
  <span m="3338840">same</span> <span m="3339140">logic</span> <span m="3339590">as</span>
  <span m="3340010">the</span> <span m="3340190">A1</span> <span m="3340610">step.</span>
  <span m="3341390">We</span> <span m="3341540">see</span> <span m="3341840">that</span>
  <span m="3342970">B1</span> <span m="3344390">has</span> <span m="3344900">large</span>
  <span m="3345260">size,</span> <span m="3346310">is</span> <span m="3348140">a</span>
  <span m="3348200">large</span> <span m="3348530">fraction</span> <span m="3349310">of</span>
  <span m="3349530">B.</span> <span m="3352760">And</span> <span m="3352860">now</span>
  <span m="3353060">we</span> <span m="3353180">pass</span> <span m="3353480">down</span>
  <span m="3353720">to</span> <span m="3354200">this</span> <span m="3356490">B1</span>
  <span m="3356990">set.</span></p><p><span m="3364214">Now,</span> <span m="3364710">finally,</span>
  <span m="3366940">let's</span> <span m="3367090">consider</span> <span m="3369940">A3</span>
  <span m="3372360">to</span> <span m="3372840">be</span> <span m="3376080">vertices</span>
  <span m="3376350">in</span> <span m="3376620">A2</span> <span m="3377970">where</span>
  <span m="3378330">a</span> <span m="3379160">is</span> <span m="3379500">friendly.</span>
  <span m="3381490">So</span> <span m="3382410">vertices</span> <span m="3382730">a</span>
  <span m="3383050">in</span> <span m="3383320">A2</span> <span m="3383820">such</span>
  <span m="3384180">that</span> <span m="3384400">a is</span> <span m="3384780">friendly</span>
  <span m="3385620">to</span> <span m="3387630">at</span> <span m="3387750">least</span>
  <span m="3388170">1</span> <span m="3388650">over</span> <span m="3390210">delta</span>
  <span m="3390660">over--</span> <span m="3391210">so</span> <span m="3391410">1</span>
  <span m="3391620">minus</span> <span m="3391980">delta</span> <span m="3392250">over</span>
  <span m="3392490">5</span> <span m="3393240">fraction</span> <span m="3396335">of</span>
  <span m="3398259">A2.</span> <span m="3402590">So</span> <span m="3402720">we</span>
  <span m="3402870">saw</span> <span m="3403290">that,</span> <span m="3404910">in</span>
  <span m="3405530">A2,</span> <span m="3406650">most</span> <span m="3407460">pairs</span>
  <span m="3408120">of</span> <span m="3408540">vertices</span> <span m="3409140">are</span>
  <span m="3409500">friendly.</span> <span m="3410430">So</span> <span m="3410640">most,</span>
  <span m="3412080">meaning</span> <span m="3415360">all</span> <span m="3415560">but</span>
  <span m="3415800">a</span> <span m="3416250">delta</span> <span m="3417090">over</span>
  <span m="3417330">10</span> <span m="3417660">fraction.</span></p><p><span m="3420000">So</span>
  <span m="3420420">if</span> <span m="3420600">we</span> <span m="3421710">consider</span>
  <span m="3423670">vertices</span> <span m="3424760">which</span> <span m="3424990">are</span>
  <span m="3425770">unfriendly</span> <span m="3426520">to</span> <span m="3428640">many</span>
  <span m="3429540">other</span> <span m="3429780">vertices</span> <span m="3430260">in</span>
  <span m="3430380">A2,</span> <span m="3430740">there</span> <span m="3430920">aren't</span>
  <span m="3431190">so</span> <span m="3431430">many</span> <span m="3431670">of</span>
  <span m="3431790">them.</span> <span m="3433560">If</span> <span m="3433690">there</span>
  <span m="3433780">were</span> <span m="3433870">many</span> <span m="3434110">of</span>
  <span m="3434200">them,</span> <span m="3434380">you</span> <span m="3434500">couldn't</span>
  <span m="3434770">have</span> <span m="3434890">had</span> <span m="3435040">that.</span>
  <span m="3436440">So</span> <span m="3437130">that's</span> <span m="3437310">why</span>
  <span m="3437410">I</span> <span m="3437460">constructed</span> <span m="3437970">this</span>
  <span m="3438160">set</span> <span m="3438850">A3</span> <span m="3440360">consisting</span>
  <span m="3440990">of</span> <span m="3441170">elements</span> <span m="3442750">in</span>
  <span m="3442920">A2</span> <span m="3443330">that</span> <span m="3443540">are</span>
  <span m="3443630">friendly</span> <span m="3444050">to</span> <span m="3445190">many</span>
  <span m="3445460">elements.</span> <span m="3447110">And</span> <span m="3447800">the</span>
  <span m="3448130">size</span> <span m="3448670">of</span> <span m="3448790">A3</span>
  <span m="3450170">is</span> <span m="3450380">at</span> <span m="3450470">least</span>
  <span m="3451670">half</span> <span m="3452210">of</span> <span m="3452390">that</span>
  <span m="3452570">of</span> <span m="3452740">A2.</span> <span m="3460974">So</span>
  <span m="3462980">we</span> <span m="3463130">have</span> <span m="3463460">this</span>
  <span m="3467170">A3</span> <span m="3468530">inside.</span> <span m="3470510">All</span>
  <span m="3470660">right.</span></p><p><span m="3471696">And</span> <span m="3472060">now</span>
  <span m="3472270">I</span> <span m="3472390">claim</span> <span m="3472930">that</span>
  <span m="3473050">we</span> <span m="3473200">can</span> <span m="3473380">take</span>
  <span m="3474340">A3</span> <span m="3474880">and</span> <span m="3475030">B</span>
  <span m="3475570">as</span> <span m="3475790">our</span> <span m="3476110">final</span>
  <span m="3476500">sets,</span> <span m="3477235">and</span> <span m="3477550">that</span>
  <span m="3477970">between</span> <span m="3478480">every</span> <span m="3478750">vertex</span>
  <span m="3479260">in</span> <span m="3479410">A3</span> <span m="3479860">and</span>
  <span m="3480010">every</span> <span m="3480190">vertex</span> <span m="3480640">in</span>
  <span m="3480750">B1,</span> <span m="3481510">I</span> <span m="3481670">claim</span>
  <span m="3482010">there</span> <span m="3482140">must</span> <span m="3482380">be</span>
  <span m="3482560">lots</span> <span m="3482920">of</span> <span m="3482980">paths</span>
  <span m="3483400">of</span> <span m="3483720">length</span> <span m="3483940">3.</span>
  <span m="3484990">But,</span> <span m="3485110">first,</span> <span m="3485380">let's</span>
  <span m="3485590">check</span> <span m="3485860">their</span> <span m="3486040">sizes.</span>
  <span m="3487420">I</span> <span m="3487480">mean,</span> <span m="3487570">the</span>
  <span m="3487660">sizes</span> <span m="3488170">all</span> <span m="3488320">should</span>
  <span m="3488530">be</span> <span m="3488680">OK,</span> <span m="3489070">because</span>
  <span m="3489430">we</span> <span m="3489550">never</span> <span m="3489820">lost</span>
  <span m="3490120">too</span> <span m="3490300">much</span> <span m="3490650">at</span>
  <span m="3490780">each</span> <span m="3490990">step.</span> <span m="3491960">If</span>
  <span m="3491980">you</span> <span m="3492070">only</span> <span m="3492250">care</span>
  <span m="3492430">about</span> <span m="3492580">polynomial</span> <span m="3493120">factors,</span>
  <span m="3493740">well,</span> <span m="3493840">you</span> <span m="3493960">already</span>
  <span m="3494260">see</span> <span m="3494530">that</span> <span m="3494650">we</span>
  <span m="3494800">never</span> <span m="3495100">lost</span> <span m="3495430">anything</span>
  <span m="3495730">more</span> <span m="3495910">than</span> <span m="3496060">a</span>
  <span m="3496090">polynomial</span> <span m="3496600">factor.</span> <span m="3497590">But</span>
  <span m="3497710">just</span> <span m="3497890">to</span> <span m="3497980">be</span>
  <span m="3498100">precise,</span> <span m="3498550">the</span> <span m="3498610">size</span>
  <span m="3498940">of</span> <span m="3499030">A3</span> <span m="3499720">is</span>
  <span m="3499900">at</span> <span m="3499960">least--</span> <span m="3500510">so</span>
  <span m="3500680">if</span> <span m="3500800">you</span> <span m="3501610">count</span>
  <span m="3501940">up</span> <span m="3502420">the</span> <span m="3502510">factor</span>
  <span m="3503230">lost</span> <span m="3503590">at</span> <span m="3503650">each</span>
  <span m="3503860">step,</span> <span m="3504320">so</span> <span m="3504370">it's</span>
  <span m="3504490">1/2</span> <span m="3505840">delta</span> <span m="3506140">over</span>
  <span m="3506410">4</span> <span m="3507430">delta</span> <span m="3507670">over</span>
  <span m="3507970">2.</span> <span m="3509230">So</span> <span m="3509530">it's</span>
  <span m="3510160">at</span> <span m="3510220">least</span> <span m="3511420">delta</span>
  <span m="3511870">squared</span> <span m="3512500">over</span> <span m="3512740">16</span>
  <span m="3513910">fraction</span> <span m="3514480">of</span> <span m="3514570">the</span>
  <span m="3514690">original</span> <span m="3515100">set</span> <span m="3515360">A.</span></p><p><span
  m="3516870">And</span> <span m="3517210">now,</span> <span m="3519870">if</span>
  <span m="3519990">we</span> <span m="3520110">consider</span> <span m="3521190">a</span>
  <span m="3521340">comma</span> <span m="3521670">b</span> <span m="3524320">to</span>
  <span m="3524440">be</span> <span m="3524590">an</span> <span m="3524740">arbitrary</span>
  <span m="3525970">pair</span> <span m="3526840">in</span> <span m="3527530">A3</span>
  <span m="3528070">cross</span> <span m="3528570">B1,</span> <span m="3529650">I</span>
  <span m="3529750">claim</span> <span m="3530100">that</span> <span m="3530230">there</span>
  <span m="3530380">must</span> <span m="3530590">be</span> <span m="3530740">many</span>
  <span m="3531070">paths.</span> <span m="3533140">Because</span> <span m="3535420">by</span>
  <span m="3535540">using--</span> <span m="3536320">so</span> <span m="3536470">what</span>
  <span m="3536740">properties</span> <span m="3537250">do</span> <span m="3537370">we</span>
  <span m="3537460">know?</span> <span m="3539090">We</span> <span m="3539110">know</span>
  <span m="3539230">that</span> <span m="3539890">b</span> <span m="3540610">is</span>
  <span m="3540790">adjacent</span> <span m="3543580">to</span> <span m="3544450">a</span>
  <span m="3544570">large</span> <span m="3544930">fraction.</span> <span m="3545920">So</span>
  <span m="3546820">here</span> <span m="3547030">large</span> <span m="3547420">means</span>
  <span m="3547660">at</span> <span m="3547750">least</span> <span m="3548910">delta</span>
  <span m="3549190">over</span> <span m="3549490">4--</span> <span m="3549710">so</span>
  <span m="3550050">bounded</span> <span m="3550300">below--</span> <span m="3550780">a</span>
  <span m="3550960">large</span> <span m="3551230">fraction</span> <span m="3551740">of</span>
  <span m="3555790">A2.</span> <span m="3556400">Yes.</span> <span m="3556580">So</span>
  <span m="3556760">I</span> <span m="3556820">apologize.</span> <span m="3557330">When</span>
  <span m="3557450">I</span> <span m="3557510">say</span> <span m="3557660">the</span>
  <span m="3557750">word</span> <span m="3557930">large,</span> <span m="3558290">depending</span>
  <span m="3558650">on</span> <span m="3558740">context</span> <span m="3559260">it</span>
  <span m="3559320">can</span> <span m="3559450">mean</span> <span m="3560360">bigger</span>
  <span m="3560600">than</span> <span m="3560750">delta,</span> <span m="3561290">or</span>
  <span m="3561440">it</span> <span m="3561530">could</span> <span m="3561660">mean</span>
  <span m="3562100">at</span> <span m="3562160">least</span> <span m="3562430">1</span>
  <span m="3562640">minus</span> <span m="3562940">delta.</span> <span m="3563370">So</span>
  <span m="3563450">you</span> <span m="3563660">look</span> <span m="3563900">at</span>
  <span m="3563960">what</span> <span m="3564110">I</span> <span m="3564200">write</span>
  <span m="3564380">down.</span> <span m="3565380">So</span> <span m="3565550">b</span>
  <span m="3565820">is</span> <span m="3565970">adjacent</span> <span m="3566390">to</span>
  <span m="3566720">at</span> <span m="3566780">least</span> <span m="3567530">delta</span>
  <span m="3567830">over</span> <span m="3568070">4</span> <span m="3568310">fraction</span>
  <span m="3568790">of</span> <span m="3568910">A2.</span></p><p><span m="3571070">At</span>
  <span m="3571130">the</span> <span m="3571220">same</span> <span m="3571400">time,</span>
  <span m="3571770">we</span> <span m="3571790">know</span> <span m="3571940">that</span>
  <span m="3572510">a</span> <span m="3573410">is</span> <span m="3573680">friendly</span>
  <span m="3576870">to</span> <span m="3577920">at</span> <span m="3578010">least</span>
  <span m="3578910">1</span> <span m="3579300">minus</span> <span m="3580260">delta</span>
  <span m="3580680">over</span> <span m="3580950">5</span> <span m="3582600">fraction</span>
  <span m="3583470">of</span> <span m="3583710">A2.</span> <span m="3589000">So</span>
  <span m="3589570">these</span> <span m="3589810">two</span> <span m="3589990">sets,</span>
  <span m="3590260">they</span> <span m="3590380">must</span> <span m="3590650">overlap</span>
  <span m="3591310">by</span> <span m="3592690">at</span> <span m="3592780">least</span>
  <span m="3593425">a</span> <span m="3593710">delta</span> <span m="3594070">over</span>
  <span m="3594310">20</span> <span m="3594610">fraction.</span> <span m="3600351">So
  let's</span> <span m="3600840">take</span> <span m="3601200">a</span> <span m="3601260">vertex</span>
  <span m="3602810">b.</span> <span m="3605260">So</span> <span m="3605400">you--</span>
  <span m="3609240">so</span> <span m="3609410">it's</span> <span m="3610340">adjacent</span>
  <span m="3610730">to</span> <span m="3611570">many</span> <span m="3611810">vertices</span>
  <span m="3612290">here.</span> <span m="3613100">And</span> <span m="3613610">if</span>
  <span m="3613730">you</span> <span m="3613850">look</span> <span m="3614030">at</span>
  <span m="3614150">a</span> <span m="3614210">vertex</span> <span m="3614750">in</span>
  <span m="3615180">A,</span> <span m="3617526">it's</span> <span m="3617990">friendly</span>
  <span m="3618620">to</span> <span m="3620460">a</span> <span m="3620560">large</span>
  <span m="3620830">fraction.</span> <span m="3621240">So,</span> <span m="3621340">in
  particular,</span> <span m="3621700">it's</span> <span m="3622000">friendly</span>
  <span m="3622840">to</span> <span m="3624640">all</span> <span m="3624760">these</span>
  <span m="3624970">elements</span> <span m="3625680">over</span> <span m="3625890">here.</span></p><p><span
  m="3628760">So,</span> <span m="3630980">to</span> <span m="3631100">finish</span>
  <span m="3631460">off,</span> <span m="3632270">what</span> <span m="3632400">does</span>
  <span m="3632540">it</span> <span m="3632590">mean</span> <span m="3632780">for</span>
  <span m="3633440">a--</span> <span m="3634840">this</span> <span m="3635030">is--</span>
  <span m="3635870">this</span> <span m="3636050">vertex</span> <span m="3636200">is</span>
  <span m="3636560">a.</span> <span m="3637600">This</span> <span m="3637820">vertex</span>
  <span m="3637970">is</span> <span m="3638350">b.</span> <span m="3638810">What</span>
  <span m="3638930">does</span> <span m="3639080">it</span> <span m="3639140">mean</span>
  <span m="3639320">for</span> <span m="3639500">a</span> <span m="3639680">to</span>
  <span m="3639790">be</span> <span m="3639950">friendly</span> <span m="3640520">to</span>
  <span m="3640790">all</span> <span m="3640970">of</span> <span m="3641060">these</span>
  <span m="3641210">shaded</span> <span m="3641630">elements?</span> <span m="3642830">It</span>
  <span m="3642890">means</span> <span m="3643130">that</span> <span m="3643280">there</span>
  <span m="3643400">are</span> <span m="3643460">lots</span> <span m="3643850">of</span>
  <span m="3643950">paths</span> <span m="3646520">from</span> <span m="3647270">a</span>
  <span m="3647510">to</span> <span m="3647750">each</span> <span m="3648230">of</span>
  <span m="3648440">these</span> <span m="3649850">elements.</span> <span m="3651930">And</span>
  <span m="3652100">then</span> <span m="3652640">you</span> <span m="3652740">can</span>
  <span m="3653190">finish</span> <span m="3653520">off</span> <span m="3653730">the</span>
  <span m="3653850">paths</span> <span m="3654270">going</span> <span m="3654570">back</span>
  <span m="3654790">to</span> <span m="3655060">b.</span> <span m="3655974">Yes.</span></p><p><span
  m="3656750">AUDIENCE:</span> <span m="3656985">The</span> <span m="3657221">shaded</span>
  <span m="3657692">stuff</span> <span m="3658163">is allowed</span> <span m="3658634">to
  be</span> <span m="3659105">outside of</span> <span m="3659576">A3?</span></p><p><span
  m="3660518">YUFEI ZHAO:</span> <span m="3660754">No.</span> <span m="3660990">the
  shaded--</span> <span m="3661305">the</span> <span m="3661620">question is,</span>
  <span m="3661980">is the</span> <span m="3662040">shaded</span> <span m="3662400">stuff</span>
  <span m="3662880">allowed</span> <span m="3663150">to</span> <span m="3663210">be</span>
  <span m="3663360">outside of</span> <span m="3663720">A3?</span> <span m="3664040">No.</span>
  <span m="3664220">The</span> <span m="3664300">shaded</span> <span m="3665170">things</span>
  <span m="3665680">are</span> <span m="3665910">inside</span> <span m="3666330">A3.</span>
  <span m="3666870">So</span> <span m="3667080">we're</span> <span m="3667290">looking</span>
  <span m="3667620">at</span> <span m="3667710">intersections</span> <span m="3668910">within</span>
  <span m="3670640">A3.</span> <span m="3674550">No,</span> <span m="3674850">sorry.</span>
  <span m="3677640">Actually,</span> <span m="3677780">no,</span> <span m="3677910">you're</span>
  <span m="3678000">right.</span> <span m="3678180">So</span> <span m="3678390">the</span>
  <span m="3678610">shaded</span> <span m="3678960">things</span> <span m="3679200">can</span>
  <span m="3679320">be</span> <span m="3679430">outside</span> <span m="3679740">A3.</span>
  <span m="3680530">So</span> <span m="3680670">shaded</span> <span m="3680970">things</span>
  <span m="3681300">can be</span> <span m="3681390">outside</span> <span m="3681660">A3.</span>
  <span m="3682450">I</span> <span m="3682570">apologize.</span> <span m="3683130">So</span>
  <span m="3683310">everything</span> <span m="3683700">now</span> <span m="3683880">is</span>
  <span m="3684090">in</span> <span m="3685490">A2.</span></p><p><span m="3688800">So</span>
  <span m="3689220">b</span> <span m="3689580">is</span> <span m="3693060">adjacent</span>
  <span m="3693360">to</span> <span m="3693450">a</span> <span m="3693480">large</span>
  <span m="3693750">fraction</span> <span m="3694140">of</span> <span m="3694260">A2.</span>
  <span m="3695100">And</span> <span m="3695460">a</span> <span m="3695800">here</span>
  <span m="3696270">is</span> <span m="3697290">friendly</span> <span m="3698130">to</span>
  <span m="3700710">some</span> <span m="3700980">part</span> <span m="3701250">of</span>
  <span m="3701850">the</span> <span m="3702630">neighbors</span> <span m="3703030">of</span>
  <span m="3703140">b.</span> <span m="3703800">So</span> <span m="3706710">you</span>
  <span m="3706800">can</span> <span m="3707040">complete</span> <span m="3707550">paths</span>
  <span m="3708480">like</span> <span m="3708690">that.</span> <span m="3712768">Yes.</span>
  <span m="3713250">So</span> <span m="3713470">only</span> <span m="3713710">the</span>
  <span m="3713800">starting and</span> <span m="3714280">ending</span> <span m="3714550">points</span>
  <span m="3714880">have</span> <span m="3715030">to</span> <span m="3715120">be</span>
  <span m="3715330">in</span> <span m="3715540">A prime</span> <span m="3715660">and</span>
  <span m="3715980">B</span> <span m="3716110">prime.</span> <span m="3716410">Everything</span>
  <span m="3716770">else,</span> <span m="3716920">they</span> <span m="3717040">can</span>
  <span m="3717160">go</span> <span m="3717310">outside</span> <span m="3717700">of</span>
  <span m="3717820">the</span> <span m="3718410">A</span> <span m="3718510">prime</span>
  <span m="3718720">and</span> <span m="3718810">B</span> <span m="3718970">prime.</span>
  <span m="3720666">Yes,</span> <span m="3721138">thank</span> <span m="3721610">you.</span></p><p><span
  m="3723970">So</span> <span m="3726870">the</span> <span m="3726970">number</span>
  <span m="3727300">of</span> <span m="3727420">paths</span> <span m="3730150">from</span>
  <span m="3730870">a</span> <span m="3731470">to</span> <span m="3732460">B</span>
  <span m="3733630">to</span> <span m="3733870">A2</span> <span m="3735310">back</span>
  <span m="3735550">to</span> <span m="3738730">b</span> <span m="3740290">is--</span>
  <span m="3742516">let's see</span> <span m="3742960">if I</span> <span m="3743160">can</span>
  <span m="3743700">stay</span> <span m="3743970">within</span> <span m="3744210">B1--</span>
  <span m="3744960">so</span> <span m="3745200">is</span> <span m="3745620">at</span>
  <span m="3745710">least--</span> <span m="3754119">yes.</span> <span m="3754610">So</span>
  <span m="3755080">it's--</span> <span m="3756040">sorry.</span> <span m="3756530">This</span>
  <span m="3756750">is</span> <span m="3758195">B.</span> <span m="3758610">So</span>
  <span m="3758790">it's</span> <span m="3758970">at</span> <span m="3759030">least</span>
  <span m="3759810">delta</span> <span m="3760440">over</span> <span m="3761070">20</span>
  <span m="3761970">times</span> <span m="3762790">A2</span> <span m="3763740">times</span>
  <span m="3764070">delta</span> <span m="3764520">over</span> <span m="3765900">delta</span>
  <span m="3766200">squared</span> <span m="3766710">over</span> <span m="3767010">80</span>
  <span m="3767730">times</span> <span m="3768330">B.</span> <span m="3769530">So</span>
  <span m="3769680">if</span> <span m="3769800">you</span> <span m="3769890">don't</span>
  <span m="3770040">care</span> <span m="3770190">about</span> <span m="3770400">polynomial</span>
  <span m="3770940">factors</span> <span m="3771420">in</span> <span m="3771780">delta,</span>
  <span m="3772470">then</span> <span m="3774390">you</span> <span m="3774470">see</span>
  <span m="3774700">that--</span> <span m="3778080">the</span> <span m="3778520">point</span>
  <span m="3778760">is</span> <span m="3778870">there's</span> <span m="3779000">a</span>
  <span m="3779060">large</span> <span m="3779330">fraction</span> <span m="3779810">of--</span>
  <span m="3782700">there are</span> <span m="3782770">a</span> <span m="3782830">lot</span>
  <span m="3783010">of</span> <span m="3783100">paths.</span> <span m="3783460">So</span>
  <span m="3783890">there</span> <span m="3783990">are</span> <span m="3784030">a</span>
  <span m="3784060">lot</span> <span m="3784240">of</span> <span m="3784330">paths</span>
  <span m="3784660">between</span> <span m="3785440">each</span> <span m="3786100">little</span>
  <span m="3786340">a</span> <span m="3786520">and</span> <span m="3786670">each</span>
  <span m="3787000">little</span> <span m="3787210">b</span> <span m="3788630">by</span>
  <span m="3788810">the</span> <span m="3788900">construction</span> <span m="3789440">we've</span>
  <span m="3789560">done.</span></p><p><span m="3795190">So</span> <span m="3795310">let</span>
  <span m="3795400">me</span> <span m="3795670">just</span> <span m="3795960">do</span>
  <span m="3796100">a</span> <span m="3796180">recap.</span> <span m="3796630">So</span>
  <span m="3796810">there</span> <span m="3796930">were</span> <span m="3797650">quite</span>
  <span m="3797860">a</span> <span m="3797890">few</span> <span m="3798070">details</span>
  <span m="3798490">in</span> <span m="3798580">this</span> <span m="3798760">proof,</span>
  <span m="3799990">and</span> <span m="3800440">some</span> <span m="3800700">of</span>
  <span m="3800860">them</span> <span m="3800960">have</span> <span m="3801130">to</span>
  <span m="3801220">do</span> <span m="3801310">with</span> <span m="3801490">cleaning</span>
  <span m="3801910">up.</span> <span m="3802300">Because</span> <span m="3802660">it's</span>
  <span m="3802810">not</span> <span m="3803110">so</span> <span m="3803320">nice</span>
  <span m="3803620">to</span> <span m="3803740">work</span> <span m="3803980">with</span>
  <span m="3804160">graphs</span> <span m="3804640">that</span> <span m="3805360">just</span>
  <span m="3805600">have</span> <span m="3805810">large</span> <span m="3806170">average</span>
  <span m="3806500">degree.</span> <span m="3806850">It's</span> <span m="3806980">much</span>
  <span m="3807220">nicer</span> <span m="3807610">to</span> <span m="3807730">work</span>
  <span m="3808000">with</span> <span m="3808150">graphs</span> <span m="3808480">with</span>
  <span m="3808630">large</span> <span m="3808930">minimum</span> <span m="3809320">degree.</span>
  <span m="3809920">So</span> <span m="3810100">there</span> <span m="3810220">are</span>
  <span m="3810250">a</span> <span m="3810280">couple</span> <span m="3810520">of</span>
  <span m="3810610">steps</span> <span m="3810970">here</span> <span m="3811330">to</span>
  <span m="3811960">take</span> <span m="3812170">care</span> <span m="3812470">of</span>
  <span m="3813070">vertices</span> <span m="3813580">with</span> <span m="3813790">small</span>
  <span m="3814150">degrees.</span> <span m="3814990">So</span> <span m="3815140">we</span>
  <span m="3815290">started</span> <span m="3815800">with,</span> <span m="3817201">between</span>
  <span m="3817670">A and</span> <span m="3817850">B,</span> <span m="3818030">lots</span>
  <span m="3818330">of</span> <span m="3818420">edges.</span> <span m="3819290">And</span>
  <span m="3819440">we</span> <span m="3819620">trim</span> <span m="3820610">vertices</span>
  <span m="3821060">from</span> <span m="3821280">A</span> <span m="3821520">with</span>
  <span m="3821810">small</span> <span m="3822140">degree.</span> <span m="3822410">So</span>
  <span m="3822790">we</span> <span m="3822950">get</span> <span m="3823310">A1.</span></p><p><span
  m="3825250">And</span> <span m="3825340">then</span> <span m="3825520">we</span>
  <span m="3825640">apply</span> <span m="3825900">the</span> <span m="3825970">path</span>
  <span m="3826240">of</span> <span m="3826330">length</span> <span m="3826510">2</span>
  <span m="3826720">lemma</span> <span m="3827050">to</span> <span m="3827200">get</span>
  <span m="3827380">A2.</span> <span m="3828970">So</span> <span m="3830240">inside</span>
  <span m="3830930">A2,</span> <span m="3831540">most</span> <span m="3831990">pairs</span>
  <span m="3832320">of</span> <span m="3832380">vertices</span> <span m="3832860">have</span>
  <span m="3833040">lots</span> <span m="3833310">of</span> <span m="3833370">common</span>
  <span m="3833650">neighbors,</span> <span m="3834210">but</span> <span m="3834300">not</span>
  <span m="3834450">all.</span> <span m="3837510">We</span> <span m="3837630">then</span>
  <span m="3837780">go</span> <span m="3837930">back</span> <span m="3838140">to</span>
  <span m="3838380">B</span> <span m="3839250">to</span> <span m="3839430">get</span>
  <span m="3840320">B1,</span> <span m="3841590">which</span> <span m="3841860">has</span>
  <span m="3842550">large</span> <span m="3842910">minimum</span> <span m="3843290">degree</span>
  <span m="3843880">to</span> <span m="3844810">A2.</span> <span m="3847650">And</span>
  <span m="3847770">then</span> <span m="3848610">A3</span> <span m="3849780">looks</span>
  <span m="3850110">at</span> <span m="3850920">vertices</span> <span m="3851430">in</span>
  <span m="3851790">A</span> <span m="3852030">with</span> <span m="3852750">many</span>
  <span m="3853980">friendly</span> <span m="3855240">companions</span> <span m="3856170">in</span>
  <span m="3856350">A2.</span> <span m="3860200">And</span> <span m="3860770">A3</span>
  <span m="3861100">is</span> <span m="3861250">large,</span> <span m="3861900">and</span>
  <span m="3862030">I</span> <span m="3862090">claim</span> <span m="3862390">that</span>
  <span m="3862510">between</span> <span m="3862900">every</span> <span m="3863110">vertex</span>
  <span m="3863530">in</span> <span m="3863670">A3</span> <span m="3864100">and</span>
  <span m="3864250">every</span> <span m="3864460">vertex</span> <span m="3864850">in</span>
  <span m="3864940">B,</span> <span m="3865600">you</span> <span m="3865720">have</span>
  <span m="3865960">many</span> <span m="3866230">paths</span> <span m="3866590">of</span>
  <span m="3866730">length</span> <span m="3866910">3.</span> <span m="3868120">Because</span>
  <span m="3868420">if</span> <span m="3868480">you</span> <span m="3868570">start</span>
  <span m="3868900">with</span> <span m="3869060">a</span> <span m="3869110">vertex</span>
  <span m="3869770">in</span> <span m="3870670">A3,</span> <span m="3872340">it</span>
  <span m="3872710">has</span> <span m="3873010">many</span> <span m="3873280">friendly</span>
  <span m="3873670">companions.</span></p><p><span m="3875430">So</span> <span m="3875580">many</span>
  <span m="3875850">here</span> <span m="3876120">means</span> <span m="3876450">at</span>
  <span m="3876570">least</span> <span m="3876870">1</span> <span m="3877440">minus</span>
  <span m="3879540">delta</span> <span m="3879990">over</span> <span m="3880200">5</span>
  <span m="3880590">fraction.</span> <span m="3881640">Whereas</span> <span m="3882150">every</span>
  <span m="3882390">vertex</span> <span m="3882990">in</span> <span m="3883170">B1</span>
  <span m="3884160">has</span> <span m="3885420">lots</span> <span m="3886140">of</span>
  <span m="3887160">neighbors</span> <span m="3888150">in</span> <span m="3888720">A2,</span>
  <span m="3889470">where</span> <span m="3889620">lots</span> <span m="3890070">means</span>
  <span m="3890490">at</span> <span m="3890580">least</span> <span m="3891630">delta</span>
  <span m="3892080">over</span> <span m="3892580">4.</span> <span m="3893430">So</span>
  <span m="3893850">there's</span> <span m="3894540">necessarily</span> <span m="3895200">an</span>
  <span m="3895380">overlap</span> <span m="3896610">of</span> <span m="3896790">at</span>
  <span m="3896880">least</span> <span m="3897210">delta</span> <span m="3897570">over</span>
  <span m="3897840">20.</span> <span m="3899230">And</span> <span m="3899560">for</span>
  <span m="3899800">that</span> <span m="3900070">overlap,</span> <span m="3900880">we</span>
  <span m="3901030">can</span> <span m="3901210">create</span> <span m="3901750">lots</span>
  <span m="3902170">of</span> <span m="3902260">paths</span> <span m="3903280">going</span>
  <span m="3903760">through</span> <span m="3904780">this</span> <span m="3905530">overlap</span>
  <span m="3906250">from</span> <span m="3907090">A</span> <span m="3907510">to</span>
  <span m="3907720">B.</span> <span m="3911880">Any</span> <span m="3912030">questions?</span>
  <span m="3916220">OK,</span> <span m="3916500">great.</span></p><p><span m="3916780">So</span>
  <span m="3916900">let's</span> <span m="3917560">put</span> <span m="3917800">everything</span>
  <span m="3918160">together</span> <span m="3919720">to</span> <span m="3919990">prove</span>
  <span m="3920530">the</span> <span m="3921010">graphical</span> <span m="3921550">version</span>
  <span m="3921940">of</span> <span m="3922030">Balog-Szemeredi-Gowers.</span> <span
  m="3931040">So</span> <span m="3931340">we'll</span> <span m="3931440">prove</span>
  <span m="3931680">the</span> <span m="3931860">graphical</span> <span m="3932310">version</span>
  <span m="3932730">of</span> <span m="3932980">Balog-Szemeredi-Gowers.</span> <span
  m="3942660">So</span> <span m="3942820">by--</span> <span m="3943440">so,</span>
  <span m="3943560">first,</span> <span m="3943890">note</span> <span m="3944280">that</span>
  <span m="3945600">the</span> <span m="3945900">hypothesis</span> <span m="3946920">of</span>
  <span m="3947520">Balog-Szemeredi-Gowers</span> <span m="3949050">already</span>
  <span m="3949450">implies</span> <span m="3950190">that</span> <span m="3950550">the</span>
  <span m="3950640">size</span> <span m="3951060">of</span> <span m="3951180">A</span>
  <span m="3951840">and</span> <span m="3952170">the</span> <span m="3952260">size</span>
  <span m="3952620">of</span> <span m="3952680">B</span> <span m="3953730">are</span>
  <span m="3954780">not</span> <span m="3955020">too</span> <span m="3955230">small.</span>
  <span m="3958910">Because,</span> <span m="3959480">otherwise,</span> <span m="3960050">you</span>
  <span m="3960170">couldn't</span> <span m="3960470">have</span> <span m="3960740">had</span>
  <span m="3961890">n</span> <span m="3962120">squared</span> <span m="3962480">over</span>
  <span m="3962690">k</span> <span m="3962960">edges</span> <span m="3963290">to</span>
  <span m="3963410">begin</span> <span m="3963680">with.</span></p><p><span m="3968060">So</span>
  <span m="3968280">by</span> <span m="3968840">the</span> <span m="3968960">path</span>
  <span m="3969410">of</span> <span m="3969680">length</span> <span m="3969920">3</span>
  <span m="3970160">lemma,</span> <span m="3976610">there</span> <span m="3976790">exists</span>
  <span m="3978050">A</span> <span m="3978200">prime</span> <span m="3978830">in</span>
  <span m="3979130">A</span> <span m="3979460">and</span> <span m="3979880">B</span>
  <span m="3980090">prime</span> <span m="3980375">in</span> <span m="3980660">B</span>
  <span m="3982190">with</span> <span m="3982940">the</span> <span m="3983030">following</span>
  <span m="3983450">properties.</span> <span m="3984980">That</span> <span m="3985910">A</span>
  <span m="3986030">prime</span> <span m="3987400">has</span> <span m="3987630">a</span>
  <span m="3987950">large</span> <span m="3988310">fraction</span> <span m="3988940">of--</span>
  <span m="3992306">so</span> <span m="3992750">A</span> <span m="3992870">prime</span>
  <span m="3993110">and</span> <span m="3993200">B</span> <span m="3993350">prime</span>
  <span m="3993590">are</span> <span m="3993680">both</span> <span m="3994160">large</span>
  <span m="3995650">in</span> <span m="3995840">size.</span> <span m="4000460">And</span>
  <span m="4002160">for</span> <span m="4002370">all</span> <span m="4003880">vertices</span>
  <span m="4004890">a</span> <span m="4005590">in</span> <span m="4005830">A</span>
  <span m="4005950">prime</span> <span m="4006665">and</span> <span m="4007020">vertices</span>
  <span m="4008530">b</span> <span m="4008780">in</span> <span m="4008950">B</span>
  <span m="4009160">prime,</span> <span m="4010990">there</span> <span m="4011200">are</span>
  <span m="4014090">lots</span> <span m="4014420">of</span> <span m="4014540">paths</span>
  <span m="4014960">of</span> <span m="4015080">length</span> <span m="4015290">3</span>
  <span m="4015920">between</span> <span m="4017600">these</span> <span m="4018470">vertices.</span>
  <span m="4019040">So</span> <span m="4019250">there</span> <span m="4019460">are</span>
  <span m="4019970">at</span> <span m="4020090">least</span> <span m="4021870">k</span>
  <span m="4022160">to</span> <span m="4022310">the</span> <span m="4022400">minus</span>
  <span m="4022940">little</span> <span m="4023300">o1--</span> <span m="4025010">to</span>
  <span m="4025300">the</span> <span m="4025400">minus</span> <span m="4025730">big</span>
  <span m="4026000">O1</span> <span m="4027770">times</span> <span m="4028210">n</span>
  <span m="4028370">squared</span> <span m="4030950">pairs</span> <span m="4032570">of</span>
  <span m="4033050">intermediate</span> <span m="4033860">vertices</span> <span m="4034820">a1,</span>
  <span m="4038050">b1</span> <span m="4040570">in</span> <span m="4040930">A</span>
  <span m="4041080">cross</span> <span m="4041440">B,</span> <span m="4043210">such</span>
  <span m="4043510">that</span> <span m="4044500">a</span> <span m="4045490">b1</span>
  <span m="4046480">a1</span> <span m="4047170">b</span> <span m="4048180">is</span>
  <span m="4048390">a</span> <span m="4048460">path</span> <span m="4051130">in</span>
  <span m="4051580">G.</span></p><p><span m="4057760">So</span> <span m="4057940">let</span>
  <span m="4058060">me</span> <span m="4058720">draw</span> <span m="4060700">the</span>
  <span m="4060790">situation</span> <span m="4061390">for</span> <span m="4061570">you.</span>
  <span m="4068920">So</span> <span m="4069170">we</span> <span m="4069350">have</span>
  <span m="4071270">A</span> <span m="4071750">and</span> <span m="4072440">B.</span>
  <span m="4077520">And</span> <span m="4077840">so</span> <span m="4078050">inside</span>
  <span m="4078400">A</span> <span m="4078750">and</span> <span m="4079010">B,</span>
  <span m="4080210">we</span> <span m="4080390">have</span> <span m="4081350">this</span>
  <span m="4081750">fairly</span> <span m="4082160">large</span> <span m="4085280">A</span>
  <span m="4085560">prime</span> <span m="4088100">and</span> <span m="4088320">B</span>
  <span m="4088530">prime,</span> <span m="4090090">such</span> <span m="4090460">that</span>
  <span m="4090620">for</span> <span m="4090810">every</span> <span m="4093020">little</span>
  <span m="4093270">a</span> <span m="4094026">and</span> <span m="4095000">little</span>
  <span m="4095280">b,</span> <span m="4096450">there</span> <span m="4096660">are</span>
  <span m="4097560">many</span> <span m="4097920">paths</span> <span m="4102250">like</span>
  <span m="4102450">that</span> <span m="4103470">going</span> <span m="4103770">to</span>
  <span m="4104670">b1</span> <span m="4106371">and</span> <span m="4106760">a2.</span>
  <span m="4110439">Let</span> <span m="4110649">me</span> <span m="4111310">set--</span>
  <span m="4112990">so</span> <span m="4113170">let</span> <span m="4113290">me</span>
  <span m="4114430">set</span> <span m="4115029">x</span> <span m="4115930">to</span>
  <span m="4116050">be</span> <span m="4118750">a</span> <span m="4119200">plus</span>
  <span m="4120040">b1,</span> <span m="4122164">that</span> <span m="4122590">sum,</span>
  <span m="4124270">y</span> <span m="4124990">to</span> <span m="4125080">be</span>
  <span m="4126250">a1</span> <span m="4126790">plus</span> <span m="4127319">b1,</span>
  <span m="4128819">and</span> <span m="4128979">z</span> <span m="4129670">to</span>
  <span m="4129819">be</span> <span m="4130660">a1</span> <span m="4131529">plus</span>
  <span m="4131939">b.</span></p><p><span m="4144460">So</span> <span m="4144620">now</span>
  <span m="4144859">notice</span> <span m="4145939">that</span> <span m="4146930">we</span>
  <span m="4147050">can</span> <span m="4147229">write</span> <span m="4153640">this</span>
  <span m="4155140">a</span> <span m="4155649">plus</span> <span m="4155979">b</span>
  <span m="4157180">in</span> <span m="4158439">at</span> <span m="4158560">least</span>
  <span m="4161140">k</span> <span m="4161380">to</span> <span m="4161529">the</span>
  <span m="4161620">minus</span> <span m="4161979">big</span> <span m="4162120">O1</span>
  <span m="4162850">times</span> <span m="4163399">n</span> <span m="4163630">squared</span>
  <span m="4165330">ways</span> <span m="4167350">as</span> <span m="4168960">x</span>
  <span m="4169470">minus</span> <span m="4169920">y</span> <span m="4170810">plus</span>
  <span m="4171189">z</span> <span m="4171840">by</span> <span m="4172020">following</span>
  <span m="4172770">this</span> <span m="4172979">path,</span> <span m="4175470">where</span>
  <span m="4178029">x,</span> <span m="4178730">y,</span> <span m="4179410">and</span>
  <span m="4179560">z</span> <span m="4180370">all</span> <span m="4180670">lie</span>
  <span m="4181090">in</span> <span m="4181330">the</span> <span m="4181810">restricted</span>
  <span m="4182529">sumset,</span> <span m="4185500">because</span> <span m="4186850">that's</span>
  <span m="4187060">how</span> <span m="4187180">the</span> <span m="4187270">restricted</span>
  <span m="4187689">sumset</span> <span m="4188109">is</span> <span m="4188229">defined.</span>
  <span m="4189350">So</span> <span m="4189979">if</span> <span m="4190390">you</span>
  <span m="4190510">have</span> <span m="4190870">an</span> <span m="4191020">edge,</span>
  <span m="4191729">then</span> <span m="4192779">the</span> <span m="4193060">sum</span>
  <span m="4193420">of</span> <span m="4193510">the</span> <span m="4193630">elements</span>
  <span m="4194229">across</span> <span m="4194680">on</span> <span m="4195080">the</span>
  <span m="4195220">two</span> <span m="4195460">ends,</span> <span m="4196570">by</span>
  <span m="4196720">definition,</span> <span m="4197400">lies</span> <span m="4197690">in</span>
  <span m="4197800">the</span> <span m="4197890">restricted</span> <span m="4198360">sumset.</span></p><p><span
  m="4200970">So</span> <span m="4201130">the</span> <span m="4201250">path</span>
  <span m="4201640">of</span> <span m="4201730">length</span> <span m="4201940">3</span>
  <span m="4202150">lemma</span> <span m="4202420">tells</span> <span m="4202750">us</span>
  <span m="4202900">that</span> <span m="4203200">every</span> <span m="4203590">pair</span>
  <span m="4204325">a</span> <span m="4204580">and</span> <span m="4205090">b,</span>
  <span m="4205720">their</span> <span m="4205960">sum</span> <span m="4206320">can</span>
  <span m="4206500">be</span> <span m="4206620">written</span> <span m="4207070">in</span>
  <span m="4207190">many</span> <span m="4207550">different</span> <span m="4207850">ways</span>
  <span m="4208660">as</span> <span m="4208990">this</span> <span m="4209350">combination.</span>
  <span m="4212290">As</span> <span m="4212470">a</span> <span m="4212500">result,</span>
  <span m="4213710">we</span> <span m="4213730">see</span> <span m="4214000">that</span>
  <span m="4218690">A</span> <span m="4218840">prime</span> <span m="4219200">plus</span>
  <span m="4219500">B</span> <span m="4219650">prime--</span> <span m="4221360">so</span>
  <span m="4221540">this</span> <span m="4221720">sum,</span> <span m="4222890">if</span>
  <span m="4222980">we</span> <span m="4223100">consider</span> <span m="4224120">sum</span>
  <span m="4224510">along</span> <span m="4224810">with</span> <span m="4224980">its</span>
  <span m="4225200">multiplicity--</span> <span m="4231450">so</span> <span m="4231570">now</span>
  <span m="4231750">we're</span> <span m="4231900">really</span> <span m="4232170">looking</span>
  <span m="4232500">at</span> <span m="4232830">all</span> <span m="4233040">the</span>
  <span m="4233190">different</span> <span m="4235800">sums</span> <span m="4236430">as</span>
  <span m="4236580">well</span> <span m="4236760">as</span> <span m="4236910">ways</span>
  <span m="4237270">of</span> <span m="4237360">writing</span> <span m="4237720">the</span>
  <span m="4237810">sum</span> <span m="4241830">as</span> <span m="4242180">this</span>
  <span m="4242390">combination--</span> <span m="4243890">we</span> <span m="4244040">see</span>
  <span m="4244280">that</span> <span m="4244850">it</span> <span m="4245000">is</span>
  <span m="4245840">bounded</span> <span m="4246440">above</span> <span m="4247610">by</span>
  <span m="4255720">the</span> <span m="4256440">restricted</span> <span m="4256980">sumset</span>
  <span m="4257760">raised</span> <span m="4258060">to</span> <span m="4258180">the</span>
  <span m="4258300">third</span> <span m="4258570">power.</span> <span m="4271295">Because</span>
  <span m="4271800">each</span> <span m="4272010">of</span> <span m="4272100">these</span>
  <span m="4272250">choices,</span> <span m="4272940">x,</span> <span m="4273180">y,</span>
  <span m="4273390">and</span> <span m="4273480">z,</span> <span m="4273740">they</span>
  <span m="4273930">come</span> <span m="4274230">from</span> <span m="4274620">the</span>
  <span m="4274740">restricted</span> <span m="4275280">sumset.</span></p><p><span
  m="4276330">But</span> <span m="4276480">the</span> <span m="4276540">hypothesis</span>
  <span m="4277380">of</span> <span m="4277890">Balog-Szemeredi-Gowers,</span> <span
  m="4279150">the</span> <span m="4279270">graphical</span> <span m="4279690">version,</span>
  <span m="4280290">is</span> <span m="4280550">that</span> <span m="4280760">the</span>
  <span m="4280860">restricted</span> <span m="4281360">sumset</span> <span m="4281880">is</span>
  <span m="4282330">small</span> <span m="4282750">in</span> <span m="4282840">size.</span>
  <span m="4284630">So</span> <span m="4284680">we</span> <span m="4284800">can</span>
  <span m="4284950">now</span> <span m="4285130">upper</span> <span m="4285370">bound</span>
  <span m="4288600">the</span> <span m="4289050">restricted</span> <span m="4289580">sumset</span>
  <span m="4292430">by,</span> <span m="4294300">basically,</span> <span m="4294750">the--</span>
  <span m="4296580">within</span> <span m="4296870">a</span> <span m="4297030">constant,</span>
  <span m="4297510">within</span> <span m="4297810">a</span> <span m="4297870">factor</span>
  <span m="4298320">of</span> <span m="4298440">the</span> <span m="4298590">maximum</span>
  <span m="4299070">possible.</span> <span m="4301840">And</span> <span m="4301970">now</span>
  <span m="4302120">we</span> <span m="4302540">are</span> <span m="4302810">done,</span>
  <span m="4303500">because</span> <span m="4306650">we</span> <span m="4306800">have</span>
  <span m="4307100">deduced</span> <span m="4307640">that</span> <span m="4308690">the</span>
  <span m="4309680">complete</span> <span m="4310100">sumset</span> <span m="4310610">between</span>
  <span m="4311060">A</span> <span m="4311180">prime</span> <span m="4311510">and</span>
  <span m="4311600">B</span> <span m="4311720">prime</span> <span m="4312770">is,</span>
  <span m="4313580">at</span> <span m="4313760">most,</span> <span m="4319874">a</span>
  <span m="4320360">constant</span> <span m="4320780">factor</span> <span m="4321660">with</span>
  <span m="4322150">change in</span> <span m="4322580">constant</span> <span m="4322940">by
  a</span> <span m="4323060">polynomial.</span> <span m="4324310">So</span> <span
  m="4324440">a</span> <span m="4324470">constant</span> <span m="4324860">factor</span>
  <span m="4325400">more</span> <span m="4325580">than</span> <span m="4325760">the</span>
  <span m="4326030">maximum</span> <span m="4326540">possible.</span> <span m="4331000">So</span>
  <span m="4331240">it's,</span> <span m="4331660">at</span> <span m="4331750">mostly,</span>
  <span m="4332050">k</span> <span m="4332290">to</span> <span m="4332410">the</span>
  <span m="4332530">big</span> <span m="4332890">O1</span> <span m="4333130">poly</span>
  <span m="4333430">k</span> <span m="4333700">times</span> <span m="4334060">n.</span></p><p><span
  m="4337070">So</span> <span m="4337190">that</span> <span m="4337340">proves</span>
  <span m="4339410">the</span> <span m="4339500">graphical</span> <span m="4339980">version</span>
  <span m="4340310">of</span> <span m="4340380">Balog-Szemeredi-Gowers.</span> <span
  m="4342890">And</span> <span m="4343250">because</span> <span m="4343640">we</span>
  <span m="4343820">showed</span> <span m="4344210">earlier</span> <span m="4344630">that</span>
  <span m="4345170">the</span> <span m="4345260">graphical</span> <span m="4345740">version</span>
  <span m="4346070">of</span> <span m="4346120">Balog-Szemeredi-Gowers</span> <span
  m="4347090">implies</span> <span m="4347620">Balog-Szemeredi-Gowers,</span> <span
  m="4348560">this</span> <span m="4348680">shows</span> <span m="4348920">the</span>
  <span m="4349310">Balog-Szemeredi-Gowers</span> <span m="4349980">theorem.</span>
  <span m="4352170">So</span> <span m="4352450">let</span> <span m="4352590">me</span>
  <span m="4353070">recap</span> <span m="4353490">some</span> <span m="4353700">of</span>
  <span m="4353790">the</span> <span m="4353910">ideas</span> <span m="4354840">we</span>
  <span m="4354960">saw</span> <span m="4355200">today.</span> <span m="4355880">And</span>
  <span m="4355950">so</span> <span m="4356040">the</span> <span m="4356130">whole</span>
  <span m="4356310">point</span> <span m="4356730">of</span> <span m="4357230">Balog-Szemeredi-Gowers</span>
  <span m="4358260">and</span> <span m="4358440">all</span> <span m="4358620">of</span>
  <span m="4358710">these</span> <span m="4358920">related</span> <span m="4359330">lemmas</span>
  <span m="4360000">and</span> <span m="4360390">theorems</span> <span m="4360840">and</span>
  <span m="4360930">variations</span> <span m="4362070">is</span> <span m="4362250">that</span>
  <span m="4362670">you</span> <span m="4362820">start</span> <span m="4363390">with</span>
  <span m="4364050">something</span> <span m="4365310">that</span> <span m="4366450">has</span>
  <span m="4367050">a</span> <span m="4367140">lot</span> <span m="4367470">of</span>
  <span m="4368070">additive</span> <span m="4368400">structure.</span> <span m="4369600">Well,</span>
  <span m="4370170">after</span> <span m="4370410">we</span> <span m="4370530">passed</span>
  <span m="4370830">down</span> <span m="4371070">to</span> <span m="4371220">graphs</span>
  <span m="4371640">just</span> <span m="4372460">a lot of</span> <span m="4372800">edges.</span></p><p><span
  m="4374440">So</span> <span m="4376170">you</span> <span m="4376290">start</span>
  <span m="4376560">with</span> <span m="4376730">a</span> <span m="4376770">situation</span>
  <span m="4377400">where</span> <span m="4377700">you</span> <span m="4377940">have</span>
  <span m="4379420">kind</span> <span m="4379460">of</span> <span m="4380280">1%</span>
  <span m="4381030">goodness.</span> <span m="4382500">And</span> <span m="4382650">you</span>
  <span m="4382770">want</span> <span m="4382890">to</span> <span m="4382950">show</span>
  <span m="4383130">that</span> <span m="4383250">you</span> <span m="4383400">can</span>
  <span m="4383700">restrict</span> <span m="4385400">to</span> <span m="4385790">fairly</span>
  <span m="4386270">large</span> <span m="4386660">subsets,</span> <span m="4387960">so</span>
  <span m="4388160">that</span> <span m="4388280">you</span> <span m="4388400">have</span>
  <span m="4389800">perfection.</span> <span m="4390610">So</span> <span m="4390850">you</span>
  <span m="4391000">have</span> <span m="4391450">complete</span> <span m="4391870">goodness</span>
  <span m="4392290">between</span> <span m="4393130">these</span> <span m="4393310">two</span>
  <span m="4393490">sets.</span> <span m="4394510">And</span> <span m="4394630">this</span>
  <span m="4394810">is</span> <span m="4395140">what's</span> <span m="4395380">going</span>
  <span m="4395670">on</span> <span m="4395860">in</span> <span m="4396070">both</span>
  <span m="4396310">the</span> <span m="4396370">graphical</span> <span m="4396820">version</span>
  <span m="4397240">and</span> <span m="4397450">the</span> <span m="4397570">additive</span>
  <span m="4397930">version.</span> <span m="4398920">So</span> <span m="4399280">back</span>
  <span m="4399550">to</span> <span m="4399640">the</span> <span m="4399760">graph</span>
  <span m="4400380">path</span> <span m="4400720">of</span> <span m="4400810">length</span>
  <span m="4400990">3</span> <span m="4401230">lemma.</span> <span m="4401560">So</span>
  <span m="4401980">we</span> <span m="4402160">were</span> <span m="4402280">able</span>
  <span m="4402520">to</span> <span m="4402670">boost</span> <span m="4403870">the</span>
  <span m="4403930">path</span> <span m="4404320">of</span> <span m="4404410">length</span>
  <span m="4404590">2</span> <span m="4404800">lemma,</span> <span m="4405100">which</span>
  <span m="4405820">tells</span> <span m="4406120">us</span> <span m="4406180">something</span>
  <span m="4406600">about</span> <span m="4408130">99%</span> <span m="4409180">of</span>
  <span m="4409360">the</span> <span m="4409480">pairs</span> <span m="4410890">having</span>
  <span m="4411220">lots</span> <span m="4411400">of</span> <span m="4411490">common</span>
  <span m="4411760">neighbors,</span> <span m="4412840">to</span> <span m="4415510">100%</span>
  <span m="4416290">of</span> <span m="4416380">the</span> <span m="4416470">pairs</span>
  <span m="4416860">having</span> <span m="4417160">lots</span> <span m="4417430">of</span>
  <span m="4417780">path</span> <span m="4418110">of</span> <span m="4418300">length</span>
  <span m="4418540">3.</span></p><p><span m="4421010">And</span> <span m="4421160">in</span>
  <span m="4421280">the</span> <span m="4421380">additive</span> <span m="4421790">setting,</span>
  <span m="4422600">we</span> <span m="4422750">saw</span> <span m="4423020">that</span>
  <span m="4423380">by</span> <span m="4423620">starting</span> <span m="4424130">with</span>
  <span m="4425420">a</span> <span m="4425480">situation</span> <span m="4426080">where</span>
  <span m="4426320">the</span> <span m="4426410">hypothesis</span> <span m="4427170">is</span>
  <span m="4427880">somewhat</span> <span m="4428270">patchy,</span> <span m="4428750">so</span>
  <span m="4429020">like</span> <span m="4429170">a</span> <span m="4429230">1%</span>
  <span m="4429770">type</span> <span m="4430100">hypothesis,</span> <span m="4431210">we</span>
  <span m="4431360">can</span> <span m="4431570">pass</span> <span m="4432000">down
  to</span> <span m="4432380">fairly</span> <span m="4432740">large</span> <span m="4433070">sets,</span>
  <span m="4434430">where</span> <span m="4434750">the</span> <span m="4435650">complete</span>
  <span m="4436310">sumset,</span> <span m="4437030">starting</span> <span m="4437450">with</span>
  <span m="4437630">just</span> <span m="4437810">the</span> <span m="4437900">restricted</span>
  <span m="4438380">sumset</span> <span m="4438590">being</span> <span m="4438890">small,</span>
  <span m="4439530">can</span> <span m="4439640">pass</span> <span m="4439970">down</span>
  <span m="4440120">to</span> <span m="4440210">large</span> <span m="4440540">sets</span>
  <span m="4441110">where</span> <span m="4441260">the</span> <span m="4441350">complete</span>
  <span m="4441770">sumset</span> <span m="4442270">is</span> <span m="4442730">small.</span>
  <span m="4443540">And</span> <span m="4443660">this</span> <span m="4443810">is</span>
  <span m="4443900">an</span> <span m="4443990">important</span> <span m="4444410">principle,</span>
  <span m="4445220">that,</span> <span m="4445370">often,</span> <span m="4445730">when</span>
  <span m="4445880">we</span> <span m="4446030">have</span> <span m="4446780">some</span>
  <span m="4447080">typicality</span> <span m="4449260">by</span> <span m="4449980">an</span>
  <span m="4450130">appropriate</span> <span m="4450700">argument--</span> <span m="4451210">and,</span>
  <span m="4451330">here,</span> <span m="4452050">it's</span> <span m="4452200">not</span>
  <span m="4452470">at</span> <span m="4452560">all</span> <span m="4453010">a</span>
  <span m="4453340">trivial</span> <span m="4453760">argument.</span> <span m="4454300">So</span>
  <span m="4454450">there's</span> <span m="4454600">some</span> <span m="4454930">cleverness</span>
  <span m="4455470">involved,</span> <span m="4455890">that</span> <span m="4456230">by</span>
  <span m="4456880">doing</span> <span m="4457240">some</span> <span m="4457420">kind</span>
  <span m="4457600">of</span> <span m="4457660">argument,</span> <span m="4458120">we</span>
  <span m="4458260">may</span> <span m="4458410">be</span> <span m="4458560">able</span>
  <span m="4458710">to</span> <span m="4458830">pass</span> <span m="4459160">down</span>
  <span m="4459760">to</span> <span m="4460210">some</span> <span m="4460540">fairly</span>
  <span m="4460900">large</span> <span m="4461200">set</span> <span m="4461950">where</span>
  <span m="4463150">it's</span> <span m="4463270">not</span> <span m="4463600">typically</span>
  <span m="4464050">good,</span> <span m="4464290">but</span> <span m="4464650">everything's</span>
  <span m="4465130">perfectly</span> <span m="4465610">good.</span> <span m="4467020">That's</span>
  <span m="4467230">the</span> <span m="4467290">spirit</span> <span m="4467710">here</span>
  <span m="4468280">of</span> <span m="4468490">the</span> <span m="4468580">Balog-Szemeredi-Gowers</span>
  <span m="4469920">theorem.</span> <span m="4471820">So,</span> <span m="4471910">next</span>
  <span m="4472150">time,</span> <span m="4472390">for</span> <span m="4472600">the</span>
  <span m="4473500">last</span> <span m="4474010">lecture</span> <span m="4474400">of</span>
  <span m="4474490">this</span> <span m="4474640">course,</span> <span m="4475010">I</span>
  <span m="4475020">will</span> <span m="4475090">tell</span> <span m="4475300">you</span>
  <span m="4475810">about</span> <span m="4476530">the</span> <span m="4476770">sum-product</span>
  <span m="4477730">problem,</span> <span m="4478600">where</span> <span m="4478900">the--</span>
  <span m="4480802">there are</span> <span m="4481210">also</span> <span m="4481470">some</span>
  <span m="4481680">graph--</span> <span m="4482160">very</span> <span m="4482370">nice</span>
  <span m="4482610">graph</span> <span m="4482910">theoretic</span> <span m="4483360">inputs.</span></p>
type: course
uid: 82880211e6a571b1a4a59e3e00745d16

---
None