---
about_this_resource_text: "<p><strong>Description:</strong> Szemer\xE9di\u2019s graph\
  \ regularity lemma is a powerful tool in graph theory that gives a rough structural\
  \ characterization of all large dense graphs. In this lecture, Professor Zhao explains\
  \ the statement and proof of the regularity lemma.</p>\r\n<p><strong>Instructor:</strong>\
  \ Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: vcsxCFSLyP8
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  title: Video-YouTube-Stream
  type: Video
  uid: 1a9089c21717826ee74549d199e15d2b
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/vcsxCFSLyP8/default.jpg
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: abdc7d262e6b13b3301ffc73dafb2628
- id: 3Play-3PlayYouTubeid-MP4
  media_location: vcsxCFSLyP8
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 7c871f1e43e5f26b178ec6bdd6a80313
- id: vcsxCFSLyP8.srt
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-6-szemeredi2019s-graph-regularity-lemma-i-statement-and-proof/vcsxCFSLyP8.srt
  title: 3play caption file
  type: null
  uid: 38e02a87e14bf119d6e787d6c1014844
- id: vcsxCFSLyP8.pdf
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-6-szemeredi2019s-graph-regularity-lemma-i-statement-and-proof/vcsxCFSLyP8.pdf
  title: 3play pdf file
  type: null
  uid: 67a754aaf2689f60520986277e76841d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6c2f36dd5147ebdec1d0df1ed8126a2b
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 67bcebd6757bcb67f8d0e819b8b7045d
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec06_300k.mp4
  parent_uid: 49f44a942ceebe7751e2353ccb96a00d
  title: Video-Internet Archive-MP4
  type: Video
  uid: bb60a46f897185fae4d68f802c323cd4
inline_embed_id: 22762341lecture6szemerdisgraphregularitylemmaistatementandproof67775468
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-6-szemeredi2019s-graph-regularity-lemma-i-statement-and-proof
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-6-szemeredi2019s-graph-regularity-lemma-i-statement-and-proof
template_type: Tabbed
title: "Lecture 6: Szemer\xE9di\u2019s Graph Regularity Lemma I: Statement and Proof"
transcript: <p><span m="19150">YUFEI ZHAO:</span> <span m="19255">We're</span> <span
  m="19360">about</span> <span m="19570">to</span> <span m="19660">embark</span> <span
  m="20050">on</span> <span m="20170">a</span> <span m="20290">new</span> <span m="20470">chapter</span>
  <span m="20890">in</span> <span m="20980">this</span> <span m="21130">course</span>
  <span m="22030">where</span> <span m="22900">I</span> <span m="22960">want</span>
  <span m="23080">to</span> <span m="23140">tell</span> <span m="23320">you</span>
  <span m="23470">about</span> <span m="23990">Szemeredi's</span> <span m="24720">graph</span>
  <span m="25090">regularity</span> <span m="25720">lemma.</span> <span m="46820">Szemeredi's</span>
  <span m="47360">graph</span> <span m="47630">regularity</span> <span m="48200">lemma</span>
  <span m="48730">is</span> <span m="49010">a</span> <span m="49250">very</span> <span
  m="49520">powerful</span> <span m="50030">tool</span> <span m="50810">in</span>
  <span m="51140">modern</span> <span m="51500">graph</span> <span m="51770">theory,</span>
  <span m="52040">developed</span> <span m="52400">back</span> <span m="52640">in</span>
  <span m="52730">the</span> <span m="52820">'70s.</span> <span m="54440">Today</span>
  <span m="54710">I</span> <span m="54770">want</span> <span m="54950">to</span> <span
  m="55010">show</span> <span m="55280">you</span> <span m="55600">the</span> <span
  m="56720">statement</span> <span m="57620">and</span> <span m="57770">the</span>
  <span m="57830">proof</span> <span m="58310">of</span> <span m="58490">this</span>
  <span m="58670">graph</span> <span m="58940">regularity</span> <span m="59540">lemma.</span>
  <span m="60410">And</span> <span m="60860">next</span> <span m="61160">time,</span>
  <span m="61370">we'll</span> <span m="61520">see</span> <span m="61970">how</span>
  <span m="62240">to</span> <span m="62450">apply</span> <span m="63020">the</span>
  <span m="63190">lemma</span> <span m="63890">for</span> <span m="64849">graph</span>
  <span m="65120">theoretic</span> <span m="65480">applications.</span> <span m="66700">And</span>
  <span m="66810">we'll</span> <span m="66890">also</span> <span m="67160">use</span>
  <span m="67400">it</span> <span m="67460">to</span> <span m="67580">give</span>
  <span m="67820">a</span> <span m="67880">proof</span> <span m="68210">of</span>
  <span m="68360">Roth's</span> <span m="68705">theorem.</span></p><p><span m="71850">The</span>
  <span m="72000">idea</span> <span m="72390">of</span> <span m="72780">Szemeredi's</span>
  <span m="73490">regularity</span> <span m="74070">lemma</span> <span m="74940">is</span>
  <span m="75120">that</span> <span m="75990">if</span> <span m="76140">you</span>
  <span m="76260">are</span> <span m="76320">given</span> <span m="77790">a</span>
  <span m="77880">very</span> <span m="78120">large</span> <span m="78480">graph,</span>
  <span m="83050">G.</span> <span m="84460">And</span> <span m="84610">it's</span>
  <span m="85000">a</span> <span m="85060">fairly</span> <span m="85750">robust</span>
  <span m="86350">theorem,</span> <span m="87700">so</span> <span m="88090">any</span>
  <span m="88960">large,</span> <span m="90220">dense</span> <span m="90580">graph.</span>
  <span m="93370">And</span> <span m="93650">here,</span> <span m="93920">&quot;dense&quot;</span>
  <span m="94480">means,</span> <span m="95140">let's</span> <span m="95290">say,</span>
  <span m="95890">positive</span> <span m="96370">x</span> <span m="96610">density.</span>
  <span m="98640">Then</span> <span m="99570">it</span> <span m="99690">is</span>
  <span m="99810">possible</span> <span m="100770">to</span> <span m="101280">partition</span>
  <span m="105640">the</span> <span m="106120">vertex</span> <span m="106560">set</span>
  <span m="107230">of</span> <span m="107380">this</span> <span m="107560">graph</span>
  <span m="107920">G</span> <span m="110050">into</span> <span m="110530">a</span>
  <span m="110740">bounded</span> <span m="111430">number</span> <span m="111820">of</span>
  <span m="111940">pieces</span> <span m="119840">So</span> <span m="120080">that</span>
  <span m="122580">G</span> <span m="123930">looks</span> <span m="124500">random-like</span>
  <span m="130710">between</span> <span m="131670">most</span> <span m="132090">pairs</span>
  <span m="132480">of</span> <span m="132570">parts.</span></p><p><span m="142050">So</span>
  <span m="142230">for</span> <span m="142380">instance,</span> <span m="143340">I</span>
  <span m="143460">might</span> <span m="143700">produce</span> <span m="144120">for</span>
  <span m="144240">you</span> <span m="144930">a</span> <span m="145020">partition</span>
  <span m="145590">of</span> <span m="145650">the</span> <span m="145740">vertex</span>
  <span m="146190">set</span> <span m="147090">into</span> <span m="147870">some</span>
  <span m="148140">number</span> <span m="148500">of</span> <span m="148590">parts.</span>
  <span m="149840">I'll</span> <span m="149880">draw</span> <span m="150390">five</span>
  <span m="150840">here.</span> <span m="152430">So</span> <span m="152570">you</span>
  <span m="152750">give</span> <span m="152930">me</span> <span m="153050">a</span>
  <span m="153110">graph</span> <span m="153410">G.</span> <span m="154130">I</span>
  <span m="154250">manage</span> <span m="154550">to</span> <span m="154640">produce</span>
  <span m="155030">for</span> <span m="155150">you</span> <span m="155360">this</span>
  <span m="155750">vertex</span> <span m="156200">partition</span> <span m="157690">so</span>
  <span m="157960">that</span> <span m="158830">if</span> <span m="158980">I</span>
  <span m="159040">look</span> <span m="159310">at</span> <span m="159460">between</span>
  <span m="160030">a</span> <span m="160090">typical</span> <span m="160540">pair</span>
  <span m="160870">of</span> <span m="160930">parts,</span> <span m="162130">you</span>
  <span m="162250">see</span> <span m="162880">here</span> <span m="163720">maybe</span>
  <span m="163990">the</span> <span m="164110">edge</span> <span m="164410">density</span>
  <span m="164980">is</span> <span m="165340">close</span> <span m="165790">to</span>
  <span m="165910">0.2</span> <span m="166870">but</span> <span m="167050">otherwise,</span>
  <span m="167590">the</span> <span m="167710">bipartite</span> <span m="168340">graph</span>
  <span m="169120">looks</span> <span m="170320">like</span> <span m="170530">a</span>
  <span m="170560">random</span> <span m="170920">graph</span> <span m="171370">in</span>
  <span m="171490">some</span> <span m="171700">precise</span> <span m="172090">sense</span>
  <span m="172620">I</span> <span m="172690">will</span> <span m="173190">describe</span>
  <span m="173580">in</span> <span m="173690">a</span> <span m="173740">bit.</span></p><p><span
  m="175060">And</span> <span m="175200">if</span> <span m="175320">you</span> <span
  m="175380">look</span> <span m="175620">at</span> <span m="176340">what</span> <span
  m="176490">the</span> <span m="176550">graph</span> <span m="176880">looks</span>
  <span m="177150">like</span> <span m="177360">between</span> <span m="177990">another</span>
  <span m="178290">pair</span> <span m="178560">of</span> <span m="178620">parts,</span>
  <span m="179610">maybe</span> <span m="179850">now</span> <span m="180210">it's</span>
  <span m="180360">a</span> <span m="180420">different</span> <span m="180920">x</span>
  <span m="181110">density.</span> <span m="181770">Maybe</span> <span m="182100">it's</span>
  <span m="182250">around</span> <span m="182640">0.4.</span> <span m="184040">And</span>
  <span m="184230">again,</span> <span m="184560">looks</span> <span m="184860">like</span>
  <span m="185070">a</span> <span m="185130">random</span> <span m="185550">graph</span>
  <span m="186120">with</span> <span m="186450">that</span> <span m="186690">density.</span></p><p><span
  m="188890">So</span> <span m="188940">in</span> <span m="189030">some</span> <span
  m="189270">sense,</span> <span m="189930">Szemeredi's</span> <span m="190540">regularity</span>
  <span m="191100">lemma</span> <span m="191700">is</span> <span m="191880">a</span>
  <span m="191970">universal</span> <span m="193200">structural</span> <span m="193830">description</span>
  <span m="194760">that</span> <span m="194910">allows</span> <span m="195240">you</span>
  <span m="195360">to</span> <span m="195480">approximate</span> <span m="196500">a</span>
  <span m="196560">graph</span> <span m="197610">by</span> <span m="198480">a</span>
  <span m="198570">bounded</span> <span m="199500">amount</span> <span m="199890">of</span>
  <span m="199980">information.</span> <span m="202620">So</span> <span m="202750">that's</span>
  <span m="203130">informally</span> <span m="203910">the</span> <span m="204030">idea.</span>
  <span m="204300">And</span> <span m="204390">you</span> <span m="204480">can</span>
  <span m="204630">already</span> <span m="205320">sense</span> <span m="205650">that</span>
  <span m="205770">this</span> <span m="205980">can</span> <span m="206160">be</span>
  <span m="206280">a</span> <span m="206340">very</span> <span m="206550">powerful</span>
  <span m="207120">tool.</span> <span m="207810">It</span> <span m="207930">doesn't</span>
  <span m="208200">matter</span> <span m="208740">what</span> <span m="209070">graph</span>
  <span m="209730">you</span> <span m="209910">input.</span> <span m="210780">You</span>
  <span m="210900">apply</span> <span m="211290">this</span> <span m="211490">lemma,</span>
  <span m="212100">and</span> <span m="212220">you</span> <span m="212340">get</span>
  <span m="213120">an</span> <span m="214200">approximate</span> <span m="215430">structural</span>
  <span m="216630">or</span> <span m="217170">as</span> <span m="217320">later</span>
  <span m="217590">on</span> <span m="217740">we'll</span> <span m="217920">see,</span>
  <span m="218190">it's</span> <span m="218580">also,</span> <span m="218980">in</span>
  <span m="219080">some</span> <span m="219180">sense,</span> <span m="219390">an</span>
  <span m="219540">analytic</span> <span m="220110">description</span> <span m="220860">of</span>
  <span m="220980">the</span> <span m="221070">graph.</span></p><p><span m="223840">So</span>
  <span m="223990">the</span> <span m="224110">first</span> <span m="224440">part</span>
  <span m="224830">of</span> <span m="225020">today's</span> <span m="225400">lecture</span>
  <span m="228430">will</span> <span m="229240">develop</span> <span m="230080">just</span>
  <span m="230320">a</span> <span m="230350">statement</span> <span m="231070">of</span>
  <span m="231220">this</span> <span m="231430">regularity</span> <span m="231970">lemma.</span>
  <span m="232210">I'll</span> <span m="232510">show</span> <span m="232780">you</span>
  <span m="233530">what</span> <span m="233740">exactly</span> <span m="234190">do</span>
  <span m="234340">I</span> <span m="234430">mean</span> <span m="234700">by</span>
  <span m="235330">&quot;random-like.&quot;</span> <span m="238030">Well,</span> <span
  m="238150">first</span> <span m="240270">let</span> <span m="240360">me</span> <span
  m="240450">give</span> <span m="240600">some</span> <span m="240750">definitions.</span></p><p><span
  m="243294">I</span> <span m="243780">denote</span> <span m="244300">by</span> <span
  m="244490">the</span> <span m="244590">letter</span> <span m="244890">e</span> <span
  m="245360">if</span> <span m="245480">I</span> <span m="245960">input</span> <span
  m="246350">a</span> <span m="246440">pair</span> <span m="246950">of</span> <span
  m="247820">vertex</span> <span m="248240">sets,</span> <span m="249950">x</span>
  <span m="250310">and</span> <span m="250430">y.</span> <span m="253900">Here</span>
  <span m="254310">I</span> <span m="254460">might,</span> <span m="255320">later</span>
  <span m="255640">on,</span> <span m="257980">draw</span> <span m="258760">the</span>
  <span m="258880">subscript</span> <span m="259360">G</span> <span m="260050">if</span>
  <span m="260230">it's</span> <span m="260380">clear</span> <span m="261120">that</span>
  <span m="261279">I'm</span> <span m="261399">always</span> <span m="261700">talking</span>
  <span m="262150">about</span> <span m="262870">some</span> <span m="263140">graph</span>
  <span m="263530">G.</span> <span m="265240">So</span> <span m="265390">this</span>
  <span m="265660">is</span> <span m="266110">basically</span> <span m="266680">the</span>
  <span m="266800">number</span> <span m="267220">of</span> <span m="267460">edges</span>
  <span m="267850">between</span> <span m="269650">x</span> <span m="269980">and</span>
  <span m="270130">y.</span></p><p><span m="281710">And</span> <span m="281840">I</span>
  <span m="281900">say</span> <span m="282110">&quot;basically&quot;</span> <span
  m="282680">because</span> <span m="283580">even</span> <span m="283820">though</span>
  <span m="284000">I</span> <span m="284090">will</span> <span m="284860">draw</span>
  <span m="285200">and</span> <span m="285320">depict</span> <span m="285710">everything</span>
  <span m="286280">as</span> <span m="286460">if</span> <span m="286670">x</span>
  <span m="286880">and</span> <span m="287000">y</span> <span m="287150">are</span>
  <span m="287240">disjoint</span> <span m="287720">sets, and</span> <span m="288080">that's</span>
  <span m="288260">the</span> <span m="288410">easiest</span> <span m="288890">case</span>
  <span m="289160">to</span> <span m="289250">think</span> <span m="289490">about,</span>
  <span m="291320">I'm</span> <span m="291470">also</span> <span m="291770">going</span>
  <span m="291980">to</span> <span m="292070">allow</span> <span m="292490">x</span>
  <span m="292710">and</span> <span m="292790">y</span> <span m="293000">to</span>
  <span m="293240">overlap,</span> <span m="294470">and</span> <span m="294590">also</span>
  <span m="294870">allow</span> <span m="295160">x</span> <span m="295370">and</span>
  <span m="295460">y</span> <span m="295610">to</span> <span m="295730">be</span>
  <span m="295850">the</span> <span m="295940">same</span> <span m="296240">set,</span>
  <span m="297080">in</span> <span m="297200">which</span> <span m="297350">case</span>
  <span m="297620">you</span> <span m="297710">should</span> <span m="298280">read</span>
  <span m="298490">a</span> <span m="298550">definition</span> <span m="299330">as</span>
  <span m="299420">to</span> <span m="299600">what</span> <span m="300020">this</span>
  <span m="300260">means.</span> <span m="301270">But</span> <span m="301490">it's</span>
  <span m="301670">fine</span> <span m="301910">to</span> <span m="302000">think</span>
  <span m="302210">of</span> <span m="302360">it</span> <span m="302780">as</span>
  <span m="303080">disjoint</span> <span m="303590">sets.</span> <span m="303860">So</span>
  <span m="303950">you're</span> <span m="304070">looking</span> <span m="304310">at</span>
  <span m="304400">a</span> <span m="304460">bipartite</span> <span m="304940">graph</span>
  <span m="305180">between</span> <span m="305570">x</span> <span m="305780">and</span>
  <span m="305900">y.</span></p><p><span m="307760">We're</span> <span m="307910">also</span>
  <span m="308210">going</span> <span m="308450">to</span> <span m="309110">look</span>
  <span m="309350">at</span> <span m="309500">the</span> <span m="309800">edge</span>
  <span m="310130">density</span> <span m="311180">between</span> <span m="312020">x</span>
  <span m="312230">and</span> <span m="312380">y.</span> <span m="313100">And</span>
  <span m="313220">this</span> <span m="313460">is</span> <span m="313940">simply</span>
  <span m="314360">the</span> <span m="314480">number</span> <span m="314960">of</span>
  <span m="315170">edges</span> <span m="316790">divided</span> <span m="317300">by</span>
  <span m="318105">the</span> <span m="318520">product</span> <span m="320120">of</span>
  <span m="322250">the</span> <span m="322370">sizes</span> <span m="322820">of</span>
  <span m="322910">the</span> <span m="323000">sets,</span> <span m="323570">so</span>
  <span m="324020">what</span> <span m="324260">fraction</span> <span m="324800">of</span>
  <span m="324890">the</span> <span m="324980">possible</span> <span m="325400">pairs</span>
  <span m="326000">are</span> <span m="326120">actual</span> <span m="326570">edges.</span>
  <span m="328250">So</span> <span m="328670">from</span> <span m="328820">now</span>
  <span m="329060">on,</span> <span m="329210">I'll</span> <span m="329360">refer</span>
  <span m="329660">to</span> <span m="329780">this</span> <span m="329930">quantity</span>
  <span m="330440">as</span> <span m="330960">&quot;edge</span> <span m="331330">density.&quot;</span></p><p><span
  m="336840">So</span> <span m="336960">now,</span> <span m="337800">here's</span>
  <span m="338080">the</span> <span m="338160">definition</span> <span m="339720">of</span>
  <span m="340260">what</span> <span m="340560">&quot;random-like&quot;</span> <span
  m="341370">means</span> <span m="341880">for</span> <span m="342120">the</span>
  <span m="342210">purpose</span> <span m="342600">of</span> <span m="342690">Szemeredi's</span>
  <span m="343230">regularity</span> <span m="343800">lemma.</span> <span m="344480">So</span>
  <span m="344620">we</span> <span m="344730">define</span> <span m="345010">a</span>
  <span m="345090">notion</span> <span m="345510">of</span> <span m="346010">an</span>
  <span m="346260">epsilon</span> <span m="347040">regular</span> <span m="347700">pair</span>
  <span m="350880">to</span> <span m="350970">be</span> <span m="351120">as</span>
  <span m="351240">follows--</span> <span m="352140">throughout,</span> <span m="352950">and</span>
  <span m="353370">later on,</span> <span m="353690">I</span> <span m="353940">will</span>
  <span m="354270">omit</span> <span m="354570">even</span> <span m="354780">saying</span>
  <span m="355080">this--</span> <span m="355950">G</span> <span m="356280">will</span>
  <span m="356460">be</span> <span m="356760">some</span> <span m="357270">graph.</span>
  <span m="359340">And</span> <span m="359490">we're</span> <span m="359610">going</span>
  <span m="359790">to</span> <span m="359880">be</span> <span m="359970">looking</span>
  <span m="360300">at</span> <span m="360390">subsets</span> <span m="360990">of</span>
  <span m="361080">vertices</span> <span m="361710">of</span> <span m="361830">G.</span></p><p><span
  m="365220">And</span> <span m="365340">we</span> <span m="365490">say</span> <span
  m="366840">that</span> <span m="367050">this</span> <span m="367230">pair</span>
  <span m="367650">of</span> <span m="368460">subsets</span> <span m="369000">of</span>
  <span m="369060">vertices</span> <span m="370290">is</span> <span m="371070">epsilon</span>
  <span m="371580">regular,</span> <span m="376780">again,</span> <span m="377370">in</span>
  <span m="377530">G,</span> <span m="377840">but</span> <span m="377980">later</span>
  <span m="378250">on</span> <span m="378430">I</span> <span m="378470">will</span>
  <span m="378640">even</span> <span m="378850">drop</span> <span m="379260">saying</span>
  <span m="379770">in G if</span> <span m="380050">it's</span> <span m="380200">clear</span>
  <span m="380560">which</span> <span m="380790">graph</span> <span m="381250">we're</span>
  <span m="381370">working</span> <span m="381730">with.</span> <span m="382710">So</span>
  <span m="382750">we</span> <span m="382840">say</span> <span m="383170">x</span>
  <span m="383410">and</span> <span m="383500">y</span> <span m="383720">is</span>
  <span m="383980">epsilon</span> <span m="384460">regular</span> <span m="385540">if</span>
  <span m="386650">for</span> <span m="386890">all</span> <span m="387610">subsets</span>
  <span m="388270">A</span> <span m="388510">of</span> <span m="388780">X,</span>
  <span m="392126">all</span> <span m="392604">B</span> <span m="393090">subsets</span>
  <span m="393570">of</span> <span m="393690">Y</span> <span m="394970">that</span>
  <span m="395160">are</span> <span m="396030">not</span> <span m="396360">too</span>
  <span m="396690">small,</span> <span m="399590">so</span> <span m="400270">each</span>
  <span m="401260">at</span> <span m="401350">least</span> <span m="401620">an</span>
  <span m="401740">epsilon</span> <span m="402220">proportion</span> <span m="405604">of</span>
  <span m="407899">the</span> <span m="408360">sets</span> <span m="408720">that</span>
  <span m="408870">they</span> <span m="408960">live</span> <span m="409170">in,</span>
  <span m="410730">we</span> <span m="410880">find</span> <span m="411210">that</span>
  <span m="412170">the</span> <span m="412380">x</span> <span m="412650">density</span>
  <span m="413160">between</span> <span m="413790">A</span> <span m="414030">and</span>
  <span m="414360">B</span> <span m="415470">differs</span> <span m="416760">from</span>
  <span m="417000">the</span> <span m="417090">x</span> <span m="417330">density</span>
  <span m="417750">between</span> <span m="418260">X</span> <span m="418470">and</span>
  <span m="418560">X</span> <span m="419160">by</span> <span m="419340">no</span>
  <span m="419550">more</span> <span m="419910">than</span> <span m="420420">epsilon.</span></p><p><span
  m="423010">Let</span> <span m="423130">me</span> <span m="423220">draw</span> <span
  m="423400">you</span> <span m="423510">a</span> <span m="423550">picture.</span>
  <span m="426040">I</span> <span m="426140">have</span> <span m="426270">sets</span>
  <span m="427170">A</span> <span m="427620">and</span> <span m="428280">B.</span>
  <span m="429110">So</span> <span m="429270">I</span> <span m="429420">have</span>
  <span m="429795">sets</span> <span m="430170">X</span> <span m="430380">and</span>
  <span m="430470">Y</span> <span m="432230">in</span> <span m="432330">my</span>
  <span m="432480">graph</span> <span m="432780">G.</span> <span m="433780">And</span>
  <span m="434050">I</span> <span m="434130">want</span> <span m="434310">to</span>
  <span m="434370">say</span> <span m="434700">that</span> <span m="436290">the</span>
  <span m="436740">edges</span> <span m="437100">between</span> <span m="437850">X</span>
  <span m="438060">and</span> <span m="438150">Y</span> <span m="440310">are</span>
  <span m="440520">epsilon</span> <span m="441000">regular,</span> <span m="441830">so</span>
  <span m="442210">it's</span> <span m="442590">random-like,</span> <span m="443760">if</span>
  <span m="443910">the</span> <span m="444000">following</span> <span m="444480">holds--</span>
  <span m="445770">that</span> <span m="445950">whenever</span> <span m="446520">I</span>
  <span m="446670">pick</span> <span m="447420">a</span> <span m="447510">subset</span>
  <span m="448440">A</span> <span m="448860">in</span> <span m="448980">the</span>
  <span m="449550">left</span> <span m="450990">set</span> <span m="451700">and</span>
  <span m="451940">a</span> <span m="452250">subset</span> <span m="452790">B</span>
  <span m="453420">of</span> <span m="453630">the</span> <span m="453990">right</span>
  <span m="454260">set,</span> <span m="456810">the</span> <span m="457890">edge</span>
  <span m="458160">density</span> <span m="458640">between</span> <span m="458910">A</span>
  <span m="459180">and</span> <span m="459450">B</span> <span m="460530">is</span>
  <span m="460680">approximately</span> <span m="461460">the</span> <span m="461580">same</span>
  <span m="462570">as</span> <span m="462810">the</span> <span m="463110">overall</span>
  <span m="463580">edge</span> <span m="464130">density</span> <span m="464520">between</span>
  <span m="464970">X</span> <span m="465210">and</span> <span m="465300">Y.</span></p><p><span
  m="467080">So</span> <span m="467230">in</span> <span m="467320">particular,</span>
  <span m="468070">this</span> <span m="469020">bipartite</span> <span m="469660">graph,</span>
  <span m="470050">for</span> <span m="470230">instance,</span> <span m="471100">is</span>
  <span m="471160">not</span> <span m="471850">really</span> <span m="472090">dense</span>
  <span m="472390">in</span> <span m="472990">one</span> <span m="473140">part</span>
  <span m="473530">and</span> <span m="473620">really</span> <span m="473860">sparse</span>
  <span m="474290">in</span> <span m="474370">another</span> <span m="474640">part.</span>
  <span m="475150">Somehow</span> <span m="475540">the</span> <span m="475690">edges</span>
  <span m="476080">are</span> <span m="476260">evenly</span> <span m="476710">distributed</span>
  <span m="478390">in</span> <span m="478480">this</span> <span m="478660">precise</span>
  <span m="479080">manner.</span> <span m="480810">So</span> <span m="480840">that's</span>
  <span m="481050">the</span> <span m="481140">definition</span> <span m="481620">of</span>
  <span m="481770">epsilon</span> <span m="482250">regular.</span> <span m="482890">Yes,</span>
  <span m="483180">question.</span></p><p><span m="484002">AUDIENCE:</span> <span
  m="484233">What</span> <span m="484464">is the</span> <span m="485650">epsilon</span>
  <span m="486535">for</span> <span m="486910">the</span> <span m="487000">size</span>
  <span m="487330">of</span> <span m="487420">A</span> <span m="487720">the same</span>
  <span m="488110">as epsilon</span> <span m="488410">for</span> <span m="488910">[INAUDIBLE]?</span></p><p><span
  m="491580">YUFEI ZHAO:</span> <span m="491625">The</span> <span m="491670">question</span>
  <span m="492020">is</span> <span m="492450">here,</span> <span m="492720">why</span>
  <span m="492960">are</span> <span m="493000">we</span> <span m="493110">using</span>
  <span m="493410">the</span> <span m="493500">same</span> <span m="493890">epsilon</span>
  <span m="494460">here,</span> <span m="494820">here,</span> <span m="495150">and</span>
  <span m="495330">there?</span> <span m="496000">And</span> <span m="496080">that's</span>
  <span m="496230">a</span> <span m="496290">great</span> <span m="496470">question.</span>
  <span m="496930">So</span> <span m="496950">that's</span> <span m="497250">mostly</span>
  <span m="497640">out</span> <span m="497810">of</span> <span m="497850">convenience.</span></p><p><span
  m="499070">So</span> <span m="499230">you</span> <span m="499380">could</span> <span
  m="499710">use</span> <span m="499950">different</span> <span m="500280">parameters.</span>
  <span m="501780">And</span> <span m="502110">they</span> <span m="502260">do</span>
  <span m="502440">play</span> <span m="502730">somewhat</span> <span m="503100">different</span>
  <span m="503400">roles,</span> <span m="504120">but</span> <span m="504690">at</span>
  <span m="504780">the</span> <span m="504930">end,</span> <span m="505560">we'll</span>
  <span m="506700">generally</span> <span m="507060">be</span> <span m="507180">looking</span>
  <span m="507510">at</span> <span m="507690">one</span> <span m="508440">type</span>
  <span m="508680">of</span> <span m="508800">epsilons.</span> <span m="509740">So</span>
  <span m="509770">we</span> <span m="509820">just</span> <span m="509970">make</span>
  <span m="510180">our</span> <span m="510300">life</span> <span m="510720">easier.</span>
  <span m="511390">So</span> <span m="511410">you</span> <span m="511530">could</span>
  <span m="512490">extend</span> <span m="512880">the</span> <span m="512940">definition</span>
  <span m="513539">by</span> <span m="513690">having</span> <span m="514299">an</span>
  <span m="514530">epsilon</span> <span m="515039">comma</span> <span m="515549">eta,</span>
  <span m="516750">if</span> <span m="516870">you</span> <span m="516960">like,</span>
  <span m="517600">but</span> <span m="517710">it</span> <span m="517799">will</span>
  <span m="517919">not</span> <span m="518100">be</span> <span m="518190">necessary</span>
  <span m="518669">for</span> <span m="518820">us,</span> <span m="519150">and</span>
  <span m="519630">mostly</span> <span m="520020">for</span> <span m="520169">simplification.</span>
  <span m="521780">Any</span> <span m="522010">more</span> <span m="522150">questions?</span>
  <span m="526539">All right.</span></p><p><span m="531890">Now</span> <span m="532460">if</span>
  <span m="532640">you</span> <span m="532760">have</span> <span m="533000">a</span>
  <span m="533060">pair</span> <span m="533630">x,</span> <span m="533900">y</span>
  <span m="534620">that</span> <span m="534800">is</span> <span m="535340">not</span>
  <span m="535880">epsilon</span> <span m="536330">regular,</span> <span m="538670">I</span>
  <span m="538730">just</span> <span m="538910">want</span> <span m="539060">to</span>
  <span m="539120">introduce</span> <span m="539540">a</span> <span m="539630">piece</span>
  <span m="539960">of</span> <span m="540050">terminology.</span> <span m="540690">So</span>
  <span m="540710">you</span> <span m="540830">can</span> <span m="540980">read</span>
  <span m="541110">from</span> <span m="541310">the</span> <span m="541370">definition</span>
  <span m="541880">what</span> <span m="542060">it</span> <span m="542150">means</span>
  <span m="542360">to</span> <span m="542450">be</span> <span m="542570">not</span>
  <span m="543020">epsilon</span> <span m="543410">regular.</span> <span m="544160">And</span>
  <span m="544250">sometimes</span> <span m="544640">I</span> <span m="544730">will</span>
  <span m="544820">say</span> <span m="545060">&quot;epsilon</span> <span m="545360">irregular,&quot;</span>
  <span m="546370">but</span> <span m="547220">to</span> <span m="547340">be</span>
  <span m="547910">precise,</span> <span m="548300">I'll</span> <span m="548570">stick</span>
  <span m="548870">with</span> <span m="550430">not</span> <span m="550760">epsilon</span>
  <span m="551180">regular.</span> <span m="556680">Then</span> <span m="557580">we</span>
  <span m="557730">can</span> <span m="557910">exhibit</span> <span m="558750">this</span>
  <span m="559010">A and</span> <span m="559320">B</span> <span m="559740">that</span>
  <span m="560100">witnesses</span> <span m="560910">the</span> <span m="561090">irregularity.</span></p><p><span
  m="563080">So</span> <span m="563430">if</span> <span m="564660">x,</span> <span
  m="564840">y</span> <span m="565050">is</span> <span m="565140">not</span> <span
  m="565380">epsilon</span> <span m="565800">regular,</span> <span m="566730">then</span>
  <span m="569700">their</span> <span m="569950">irregularity</span> <span m="577840">as,</span>
  <span m="578790">we</span> <span m="579050">say</span> <span m="579390">it's</span>
  <span m="579710">&quot;witnessed</span> <span m="582110">by&quot;</span> <span m="584420">some</span>
  <span m="585420">pair</span> <span m="585980">A</span> <span m="586340">in</span>
  <span m="586660">X</span> <span m="587480">and</span> <span m="588260">B</span>
  <span m="589500">in Y,</span> <span m="590820">satisfying--</span> <span m="592380">basically,</span>
  <span m="592800">you</span> <span m="592920">read</span> <span m="593820">the</span>
  <span m="593940">definition,</span> <span m="597760">and</span> <span m="597930">such</span>
  <span m="598200">that</span> <span m="598500">the</span> <span m="599490">density</span>
  <span m="599940">between</span> <span m="600300">A and</span> <span m="600570">B</span>
  <span m="601200">differs</span> <span m="602310">quite</span> <span m="602580">a</span>
  <span m="602640">bit</span> <span m="602880">from</span> <span m="603090">the</span>
  <span m="603180">density</span> <span m="603600">between</span> <span m="604410">X</span>
  <span m="604650">and</span> <span m="604770">Y.</span> <span m="606150">So</span>
  <span m="606270">when</span> <span m="606390">I</span> <span m="606450">say</span>
  <span m="607130">&quot;to</span> <span m="607440">exhibit&quot;</span> <span m="607950">or</span>
  <span m="608020">&quot;to</span> <span m="608100">witness</span> <span m="608670">irregularity,&quot;</span>
  <span m="609450">that's</span> <span m="609690">what</span> <span m="609870">I</span>
  <span m="609960">mean.</span></p><p><span m="611640">Now,</span> <span m="611810">there's</span>
  <span m="612010">a</span> <span m="612070">bit</span> <span m="612190">of</span>
  <span m="612310">an</span> <span m="612400">unfortunate</span> <span m="613030">nomenclature</span>
  <span m="613690">in</span> <span m="613990">graph</span> <span m="614290">theory,</span>
  <span m="614620">where</span> <span m="615100">previously,</span> <span m="615730">we</span>
  <span m="615880">said</span> <span m="616330">&quot;irregular</span> <span m="616810">graphs&quot;</span>
  <span m="617480">to</span> <span m="617620">mean</span> <span m="617830">that</span>
  <span m="617920">every</span> <span m="618160">vertex</span> <span m="618600">is</span>
  <span m="618700">degree</span> <span m="619030">D.</span> <span m="619960">And</span>
  <span m="620050">now</span> <span m="620230">we</span> <span m="620380">say</span>
  <span m="620770">&quot;epsilon</span> <span m="621190">regular&quot;</span> <span
  m="621610">to</span> <span m="621730">mean</span> <span m="621940">this.</span>
  <span m="623710">Sorry</span> <span m="623980">about</span> <span m="624130">that.</span>
  <span m="624460">These</span> <span m="624640">are</span> <span m="624700">both</span>
  <span m="624910">standard,</span> <span m="625770">so</span> <span m="625900">usually</span>
  <span m="626350">from</span> <span m="626590">context,</span> <span m="627070">it's</span>
  <span m="627220">clear</span> <span m="628000">which</span> <span m="628240">one</span>
  <span m="628450">is</span> <span m="628630">meant.</span></p><p><span m="634170">So</span>
  <span m="634380">this</span> <span m="634560">is</span> <span m="634680">what</span>
  <span m="634860">it</span> <span m="634920">means</span> <span m="635130">for</span>
  <span m="635310">a</span> <span m="635340">single</span> <span m="635820">pair</span>
  <span m="636210">of</span> <span m="636360">vertex</span> <span m="636750">sets</span>
  <span m="637050">to</span> <span m="637140">be</span> <span m="637320">epsilon</span>
  <span m="637800">regular.</span> <span m="638670">But</span> <span m="638820">now</span>
  <span m="639150">I</span> <span m="639540">give</span> <span m="639750">you</span>
  <span m="639900">a</span> <span m="639990">graph.</span> <span m="640680">And</span>
  <span m="640790">I</span> <span m="640860">give</span> <span m="641070">you</span>
  <span m="641190">a</span> <span m="641250">partition</span> <span m="642240">of</span>
  <span m="642360">the</span> <span m="642450">vertex</span> <span m="642870">set.</span>
  <span m="644110">So</span> <span m="644130">what</span> <span m="644280">does</span>
  <span m="644420">it</span> <span m="644490">mean</span> <span m="644640">for</span>
  <span m="644790">that</span> <span m="644940">partition</span> <span m="645900">to</span>
  <span m="646020">be</span> <span m="646650">epsilon</span> <span m="647250">regular?</span></p><p><span
  m="647955">And</span> <span m="648210">here's</span> <span m="648460">the</span>
  <span m="648540">second</span> <span m="648810">definition.</span> <span m="653940">So</span>
  <span m="654100">an</span> <span m="654340">epsilon</span> <span m="654820">regular</span>
  <span m="655600">partition,</span> <span m="661340">we</span> <span m="661490">say</span>
  <span m="661730">that</span> <span m="662030">a</span> <span m="662870">partition--</span>
  <span m="665980">and</span> <span m="666440">generally,</span> <span m="666890">I
  will</span> <span m="667220">denote</span> <span m="667460">partition</span> <span
  m="668120">by</span> <span m="668750">curly</span> <span m="669110">letters</span>
  <span m="670220">such</span> <span m="670430">as</span> <span m="670580">that,</span>
  <span m="671030">P.</span> <span m="671720">So</span> <span m="671870">the</span>
  <span m="671960">partition</span> <span m="672860">will</span> <span m="675430">divide</span>
  <span m="676030">a</span> <span m="676660">vertex</span> <span m="677050">set</span>
  <span m="678700">into</span> <span m="681260">a</span> <span m="681350">bunch</span>
  <span m="681710">of</span> <span m="682190">subsets.</span></p><p><span m="683030">So</span>
  <span m="683300">we</span> <span m="683420">say</span> <span m="683600">that</span>
  <span m="683750">that</span> <span m="683990">partition</span> <span m="685190">is</span>
  <span m="686320">epsilon</span> <span m="687050">regular</span> <span m="690880">if</span>
  <span m="691300">the</span> <span m="691390">following</span> <span m="691870">is</span>
  <span m="692050">true--</span> <span m="693430">if</span> <span m="693610">I</span>
  <span m="693940">sum</span> <span m="694780">over</span> <span m="696190">all</span>
  <span m="698740">pairs</span> <span m="702940">of</span> <span m="704050">irregular</span>
  <span m="705590">or</span> <span m="706730">pairs</span> <span m="707080">of</span>
  <span m="707710">vertex</span> <span m="708130">sets</span> <span m="708520">that</span>
  <span m="708730">are</span> <span m="708790">not</span> <span m="709090">epsilon</span>
  <span m="709540">regular,</span> <span m="715100">so</span> <span m="715410">over</span>
  <span m="715950">Vi,</span> <span m="716100">Vj</span> <span m="716550">not</span>
  <span m="716880">epsilon</span> <span m="717300">regular,</span> <span m="718470">and</span>
  <span m="718980">sum</span> <span m="719370">over</span> <span m="720180">the</span>
  <span m="720300">product</span> <span m="720810">of</span> <span m="720960">their</span>
  <span m="721110">sizes,</span> <span m="723600">then</span> <span m="726000">what</span>
  <span m="726240">I</span> <span m="726300">would</span> <span m="726450">like</span>
  <span m="727020">is</span> <span m="727440">for</span> <span m="728220">the</span>
  <span m="728370">sum</span> <span m="729060">to</span> <span m="729180">be</span>
  <span m="729810">at</span> <span m="729930">most</span> <span m="730440">epsilon</span>
  <span m="731040">times</span> <span m="732540">the</span> <span m="732660">number</span>
  <span m="733110">of</span> <span m="733620">pairs</span> <span m="734040">of</span>
  <span m="734370">vertices</span> <span m="734990">in</span> <span m="735100">G.</span>
  <span m="737610">In</span> <span m="737740">other</span> <span m="737890">words,</span>
  <span m="738320">a</span> <span m="738420">small</span> <span m="738820">fraction</span>
  <span m="740260">of</span> <span m="740740">pairs</span> <span m="741160">of</span>
  <span m="741250">vertices,</span> <span m="742060">not</span> <span m="742240">necessarily</span>
  <span m="742750">edges,</span> <span m="743080">but</span> <span m="743200">just</span>
  <span m="743350">pairs</span> <span m="743710">of</span> <span m="743770">vertices,</span>
  <span m="744790">lie</span> <span m="745120">between</span> <span m="747800">pairs</span>
  <span m="748430">of</span> <span m="748880">vertex</span> <span m="749420">parts</span>
  <span m="750050">that</span> <span m="750230">are</span> <span m="750350">not</span>
  <span m="750950">epsilon</span> <span m="751520">regular.</span> <span m="753060">So</span>
  <span m="753240">for</span> <span m="753690">instance,</span> <span m="754540">if</span>
  <span m="754590">you</span> <span m="754710">do</span> <span m="754860">not</span>
  <span m="755100">have</span> <span m="755430">epsilon--</span> <span m="757350">if</span>
  <span m="757530">all</span> <span m="757740">of</span> <span m="757860">your</span>
  <span m="758010">pairs</span> <span m="758370">are</span> <span m="758480">epsilon</span>
  <span m="758910">regular,</span> <span m="759360">then</span> <span m="760020">the</span>
  <span m="760110">partition</span> <span m="760620">is</span> <span m="760830">epsilon</span>
  <span m="761220">regular.</span> <span m="761850">But</span> <span m="762060">I</span>
  <span m="762390">do</span> <span m="762600">allow</span> <span m="762990">a</span>
  <span m="763110">small</span> <span m="763920">number</span> <span m="764490">of</span>
  <span m="764760">blemishes.</span> <span m="766610">And</span> <span m="766740">that</span>
  <span m="766860">will</span> <span m="766980">be</span> <span m="767070">necessary.</span></p><p><span
  m="773680">Just</span> <span m="773890">to</span> <span m="774070">clarify</span>
  <span m="775180">a</span> <span m="775240">subtle</span> <span m="775570">point</span>
  <span m="775870">here,</span> <span m="776340">here</span> <span m="776560">I</span>
  <span m="776680">do</span> <span m="776980">allow</span> <span m="777670">in</span>
  <span m="777790">the</span> <span m="777880">summation</span> <span m="781372">i</span>
  <span m="781840">equals</span> <span m="782260">to</span> <span m="782380">j,</span>
  <span m="783310">although</span> <span m="783580">in</span> <span m="783730">practice</span>
  <span m="784600">it</span> <span m="784870">doesn't</span> <span m="785200">really</span>
  <span m="785440">matter.</span> <span m="785990">You'll</span> <span m="786010">see</span>
  <span m="786220">that</span> <span m="786400">it's</span> <span m="786730">not</span>
  <span m="787060">really</span> <span m="787330">going</span> <span m="787600">to</span>
  <span m="787660">come</span> <span m="787930">up</span> <span m="788170">as</span>
  <span m="788320">an</span> <span m="788410">issue.</span> <span m="794680">And</span>
  <span m="794780">one</span> <span m="794990">of</span> <span m="795050">the</span>
  <span m="795170">reasons</span> <span m="795620">that</span> <span m="795920">it's</span>
  <span m="796190">not</span> <span m="796430">going</span> <span m="796550">to</span>
  <span m="796640">come</span> <span m="796850">up</span> <span m="797000">as</span>
  <span m="797120">an</span> <span m="797210">issue</span> <span m="797510">is</span>
  <span m="797630">usually</span> <span m="799280">when</span> <span m="799550">we</span>
  <span m="799760">apply</span> <span m="800150">this</span> <span m="800360">lemma,</span>
  <span m="800750">we're</span> <span m="800990">going</span> <span m="801200">to</span>
  <span m="801290">have</span> <span m="801470">a</span> <span m="801530">lot</span>
  <span m="801800">of</span> <span m="801890">parts.</span></p><p><span m="802220">In</span>
  <span m="802310">fact,</span> <span m="802520">we</span> <span m="802670">can</span>
  <span m="803150">make</span> <span m="803390">sure</span> <span m="804020">that</span>
  <span m="804200">there</span> <span m="804330">is</span> <span m="804440">a</span>
  <span m="804500">minimum</span> <span m="804950">number</span> <span m="805250">of</span>
  <span m="805310">parts.</span> <span m="806700">And</span> <span m="806780">if</span>
  <span m="808940">none</span> <span m="809150">of</span> <span m="809210">the</span>
  <span m="809270">parts</span> <span m="809540">are</span> <span m="809600">too</span>
  <span m="809780">big,</span> <span m="810630">then</span> <span m="812780">having</span>
  <span m="813200">i</span> <span m="813380">equals</span> <span m="813680">to</span>
  <span m="813790">j</span> <span m="814010">contributes</span> <span m="814550">very</span>
  <span m="814820">little</span> <span m="815090">to</span> <span m="815240">that</span>
  <span m="815390">sum</span> <span m="815740">anyway.</span> <span m="821410">In</span>
  <span m="821490">particular,</span> <span m="823290">if</span> <span m="825300">all</span>
  <span m="828120">the</span> <span m="828690">set</span> <span m="829020">sizes</span>
  <span m="829530">in</span> <span m="829650">this</span> <span m="829800">partition</span>
  <span m="830880">are</span> <span m="830970">roughly</span> <span m="831390">the</span>
  <span m="831510">same--</span> <span m="835730">so</span> <span m="835920">if</span>
  <span m="836090">they're</span> <span m="836190">all</span> <span m="836460">roughly</span>
  <span m="838410">1</span> <span m="838650">over</span> <span m="838990">k</span>
  <span m="839340">fraction</span> <span m="840000">of</span> <span m="840180">the</span>
  <span m="840930">entire</span> <span m="841560">vertex</span> <span m="841950">set--</span>
  <span m="842970">then</span> <span m="845840">that</span> <span m="846020">statement</span>
  <span m="846650">up</span> <span m="846800">there</span> <span m="848630">being</span>
  <span m="848960">epsilon</span> <span m="849410">regular</span> <span m="849840">partition</span>
  <span m="853410">up</span> <span m="853590">to</span> <span m="853830">changing</span>
  <span m="854370">this</span> <span m="854550">epsilon</span> <span m="855390">is</span>
  <span m="855570">basically</span> <span m="855990">the</span> <span m="856110">same</span>
  <span m="856500">as</span> <span m="856590">saying</span> <span m="857340">that</span>
  <span m="857520">fewer</span> <span m="857940">than</span> <span m="858180">epsilon</span>
  <span m="859020">fraction</span> <span m="859620">of</span> <span m="859740">the</span>
  <span m="859830">pairs</span> <span m="863030">Vi,</span> <span m="863470">Vj</span>
  <span m="865310">are</span> <span m="866390">not</span> <span m="867840">epsilon</span>
  <span m="868560">regular.</span> <span m="869670">And</span> <span m="869870">here,</span>
  <span m="870500">if</span> <span m="871120">k</span> <span m="871480">is</span>
  <span m="871730">large</span> <span m="872030">enough,</span> <span m="872750">I</span>
  <span m="872840">can</span> <span m="873020">even</span> <span m="873860">let</span>
  <span m="874070">you</span> <span m="874220">make</span> <span m="874670">i</span>
  <span m="874850">and</span> <span m="874960">j</span> <span m="875240">different.</span>
  <span m="875910">It's</span> <span m="875960">not</span> <span m="876140">going</span>
  <span m="876350">to</span> <span m="876470">affect</span> <span m="876830">things</span>
  <span m="877460">after</span> <span m="877790">small</span> <span m="878150">changes</span>
  <span m="878600">in</span> <span m="878720">epsilon.</span></p><p><span m="882450">So</span>
  <span m="882610">when</span> <span m="882850">it</span> <span m="882940">comes</span>
  <span m="883210">to--</span> <span m="883330">so</span> <span m="883540">for</span>
  <span m="883720">people</span> <span m="883960">who</span> <span m="884110">are</span>
  <span m="884260">seeing</span> <span m="885140">Szemeredi's</span> <span m="885640">regularity</span>
  <span m="886180">lemma</span> <span m="886420">for</span> <span m="886510">the</span>
  <span m="886600">first</span> <span m="886870">time--</span> <span m="888040">I</span>
  <span m="888100">think</span> <span m="888370">that's</span> <span m="888700">maybe</span>
  <span m="888940">all</span> <span m="889120">of</span> <span m="889210">you,</span>
  <span m="889330">or</span> <span m="889720">most</span> <span m="889960">of</span>
  <span m="890050">you--</span> <span m="891370">I</span> <span m="891460">don't</span>
  <span m="891610">want</span> <span m="891760">you</span> <span m="891820">to</span>
  <span m="891910">focus</span> <span m="892360">on</span> <span m="892480">the</span>
  <span m="892720">precise</span> <span m="893950">statements</span> <span m="894820">so</span>
  <span m="895030">much</span> <span m="895240">as</span> <span m="895390">the</span>
  <span m="895480">spirit</span> <span m="896050">of</span> <span m="896140">the</span>
  <span m="896230">lemma.</span> <span m="896710">Because</span> <span m="897010">if</span>
  <span m="897100">you</span> <span m="897190">get</span> <span m="897490">too</span>
  <span m="897850">nitty</span> <span m="898120">gritty</span> <span m="898420">with</span>
  <span m="899220">is</span> <span m="899380">that</span> <span m="899810">the</span>
  <span m="899910">same</span> <span m="900190">as</span> <span m="900340">that</span>
  <span m="900550">epsilon,</span> <span m="901450">you</span> <span m="901570">get</span>
  <span m="901690">very</span> <span m="901900">confused</span> <span m="902350">very</span>
  <span m="902530">quickly.</span> <span m="903860">So</span> <span m="904000">I</span>
  <span m="904120">want you to</span> <span m="904240">focus</span> <span m="904570">on</span>
  <span m="904660">the</span> <span m="904750">spirit</span> <span m="905590">of</span>
  <span m="905740">this</span> <span m="906370">lemma.</span> <span m="906820">I</span>
  <span m="907090">will</span> <span m="907270">state</span> <span m="907570">everything</span>
  <span m="907900">precisely,</span> <span m="909190">but</span> <span m="909370">the</span>
  <span m="909520">idea</span> <span m="909850">is</span> <span m="910000">that</span>
  <span m="910750">most</span> <span m="911110">pairs</span> <span m="911860">are</span>
  <span m="912490">not</span> <span m="912760">epsilon</span> <span m="913150">regular.</span>
  <span m="913900">And</span> <span m="914140">don't</span> <span m="914350">worry</span>
  <span m="914620">too</span> <span m="914800">much</span> <span m="914980">about</span>
  <span m="915220">if</span> <span m="915340">you</span> <span m="915410">are</span>
  <span m="915490">allowed</span> <span m="915630">to</span> <span m="915760">take</span>
  <span m="916000">i</span> <span m="916170">equals</span> <span m="916460">to</span>
  <span m="916510">j</span> <span m="916750">or</span> <span m="916870">not.</span></p><p><span
  m="919960">So</span> <span m="919970">now</span> <span m="920120">we're</span> <span
  m="920240">ready</span> <span m="920480">to</span> <span m="920600">state</span>
  <span m="921040">Szemeredi's</span> <span m="921740">regularity</span> <span m="922280">lemma.</span>
  <span m="938450">And</span> <span m="938590">it</span> <span m="938680">says</span>
  <span m="939160">that</span> <span m="939970">for</span> <span m="940390">every</span>
  <span m="940720">epsilon,</span> <span m="942530">there</span> <span m="942610">exists</span>
  <span m="943540">some</span> <span m="943900">constant</span> <span m="944590">M</span>
  <span m="945670">depending</span> <span m="946510">only</span> <span m="946810">on</span>
  <span m="946960">epsilon</span> <span m="949810">such</span> <span m="950170">that</span>
  <span m="952450">every</span> <span m="952720">graph</span> <span m="955590">has</span>
  <span m="957930">an</span> <span m="958080">epsilon</span> <span m="959910">regular</span>
  <span m="961410">partition</span> <span m="965520">into</span> <span m="966760">at</span>
  <span m="966930">most</span> <span m="968190">M</span> <span m="968640">parts.</span>
  <span m="974330">You</span> <span m="974480">give</span> <span m="974690">me</span>
  <span m="974810">the</span> <span m="974930">epsilon,</span> <span m="975590">for</span>
  <span m="975740">example</span> <span m="976350">1%,</span> <span m="977390">and</span>
  <span m="977600">there</span> <span m="977780">exists</span> <span m="978170">some</span>
  <span m="978530">constant</span> <span m="979940">such</span> <span m="980240">that</span>
  <span m="981020">every</span> <span m="981290">graph</span> <span m="981860">has</span>
  <span m="982760">a</span> <span m="982850">1%</span> <span m="983600">regular</span>
  <span m="984050">partition</span> <span m="985280">into</span> <span m="986480">a</span>
  <span m="986570">bounded</span> <span m="987200">number</span> <span m="987530">of</span>
  <span m="987620">parts.</span> <span m="988970">In</span> <span m="989060">particular--</span>
  <span m="989570">and</span> <span m="989660">this</span> <span m="989810">is</span>
  <span m="989930">very</span> <span m="990110">important,</span> <span m="990630">make</span>
  <span m="990710">sure</span> <span m="990830">you</span> <span m="990950">understand</span>
  <span m="991310">this</span> <span m="991460">part--</span> <span m="991910">that</span>
  <span m="992510">the</span> <span m="992630">number</span> <span m="993050">of</span>
  <span m="993140">parts</span> <span m="994700">does</span> <span m="995000">not</span>
  <span m="995330">depend</span> <span m="995840">on</span> <span m="995960">the</span>
  <span m="996050">size</span> <span m="996410">of</span> <span m="996470">the</span>
  <span m="996560">graph.</span></p><p><span m="1008200">Now,</span> <span m="1008400">it's</span>
  <span m="1008540">true</span> <span m="1008810">that</span> <span m="1009620">for</span>
  <span m="1009800">some</span> <span m="1010010">graphs,</span> <span m="1010400">maybe</span>
  <span m="1010700">you</span> <span m="1011150">do</span> <span m="1011330">need</span>
  <span m="1011540">very</span> <span m="1011780">many</span> <span m="1011990">parts.</span>
  <span m="1013600">But</span> <span m="1014470">the</span> <span m="1014590">number</span>
  <span m="1014920">of</span> <span m="1014980">parts</span> <span m="1015310">does</span>
  <span m="1015550">not</span> <span m="1015970">get</span> <span m="1016690">substantially</span>
  <span m="1017530">bigger,</span> <span m="1018190">or</span> <span m="1018540">does</span>
  <span m="1018760">not</span> <span m="1018970">exceed</span> <span m="1019390">this</span>
  <span m="1019550">bound,</span> <span m="1020260">even</span> <span m="1020560">if</span>
  <span m="1020710">you</span> <span m="1021430">look</span> <span m="1021640">at</span>
  <span m="1021790">graphs</span> <span m="1022480">that</span> <span m="1022630">have</span>
  <span m="1023140">unbounded</span> <span m="1023770">size.</span> <span m="1024630">So</span>
  <span m="1024790">it</span> <span m="1024880">is</span> <span m="1025000">really</span>
  <span m="1025270">a</span> <span m="1025329">universal</span> <span m="1025990">theorem</span>
  <span m="1026770">in</span> <span m="1026900">the</span> <span m="1026950">sense</span>
  <span m="1027310">that</span> <span m="1027650">it's</span> <span m="1028089">independent</span>
  <span m="1028720">of</span> <span m="1028869">the</span> <span m="1028960">size</span>
  <span m="1029800">of</span> <span m="1029920">the</span> <span m="1030010">graph.</span>
  <span m="1033839">Any</span> <span m="1034050">questions</span> <span m="1034530">about</span>
  <span m="1034750">the</span> <span m="1034800">statement</span> <span m="1035400">of</span>
  <span m="1035520">this</span> <span m="1035730">theorem?</span> <span m="1036200">Yes.</span></p><p><span
  m="1036876">AUDIENCE:</span> <span m="1037104">So</span> <span m="1037332">in the
  informal</span> <span m="1037788">statement</span> <span m="1038244">at the beginning,</span>
  <span m="1038700">you said G</span> <span m="1039156">was a large,</span> <span
  m="1039612">dense</span> <span m="1040068">graph.</span></p><p><span m="1040980">YUFEI
  ZHAO:</span> <span m="1041070">That's</span> <span m="1041160">right.</span></p><p><span
  m="1041801">AUDIENCE:</span> <span m="1042032">Is the dense condition</span> <span
  m="1042263">appropriate</span> <span m="1042725">anywhere in here?</span></p><p><span
  m="1043859">YUFEI ZHAO:</span> <span m="1043929">So</span> <span m="1044000">the</span>
  <span m="1044089">question</span> <span m="1044420">is,</span> <span m="1044900">why</span>
  <span m="1045140">did</span> <span m="1045290">I</span> <span m="1045380">say</span>
  <span m="1046220">that</span> <span m="1046579">G</span> <span m="1047000">is</span>
  <span m="1047240">a</span> <span m="1047480">large,</span> <span m="1048020">dense</span>
  <span m="1048430">graph?</span> <span m="1049220">And</span> <span m="1049420">that's</span>
  <span m="1049550">a</span> <span m="1049790">great</span> <span m="1050000">question.</span>
  <span m="1050900">And</span> <span m="1051070">that's</span> <span m="1051200">because</span>
  <span m="1051950">if</span> <span m="1052130">G</span> <span m="1052550">had</span>
  <span m="1052880">a</span> <span m="1052940">sub-linear</span> <span m="1053630">number</span>
  <span m="1053960">of</span> <span m="1054090">edges,</span> <span m="1055370">then</span>
  <span m="1056300">I</span> <span m="1056420">claim</span> <span m="1056840">that</span>
  <span m="1057350">all--</span> <span m="1059270">if</span> <span m="1062000">you</span>
  <span m="1062060">look</span> <span m="1062210">at</span> <span m="1062270">the</span>
  <span m="1062330">definition</span> <span m="1062840">of</span> <span m="1062990">epsilon</span>
  <span m="1063380">regular</span> <span m="1063800">pair,</span> <span m="1066090">and</span>
  <span m="1066460">your</span> <span m="1068010">epsilon</span> <span m="1068490">is</span>
  <span m="1068640">a</span> <span m="1068700">constant,</span> <span m="1070770">and</span>
  <span m="1070980">if</span> <span m="1071190">your</span> <span m="1071370">edge</span>
  <span m="1071640">densities</span> <span m="1072180">are</span> <span m="1072240">sub-linear,</span>
  <span m="1073240">then</span> <span m="1073380">all</span> <span m="1073620">of</span>
  <span m="1073710">these</span> <span m="1073920">guys,</span> <span m="1074250">they</span>
  <span m="1075120">are</span> <span m="1075270">little</span> <span m="1075570">o
  of</span> <span m="1075790">1.</span> <span m="1076170">They</span> <span m="1076290">go</span>
  <span m="1076440">to</span> <span m="1076530">0.</span></p><p><span m="1077520">So</span>
  <span m="1078420">trivially,</span> <span m="1079090">you</span> <span m="1079320">will</span>
  <span m="1079560">satisfy</span> <span m="1080280">the</span> <span m="1080370">epsilon</span>
  <span m="1080850">regular</span> <span m="1081240">condition.</span> <span m="1083170">So</span>
  <span m="1083380">if</span> <span m="1083500">your</span> <span m="1083650">graph</span>
  <span m="1084100">is</span> <span m="1084250">sparse--</span> <span m="1084940">sparse</span>
  <span m="1085450">in</span> <span m="1085560">the</span> <span m="1085620">sense</span>
  <span m="1085960">of</span> <span m="1086110">having</span> <span m="1086980">sub-quadratic</span>
  <span m="1087760">number</span> <span m="1088060">of</span> <span m="1088240">edges--</span>
  <span m="1089410">then</span> <span m="1090100">you</span> <span m="1090460">trivially</span>
  <span m="1091420">obtain</span> <span m="1092500">epsilon</span> <span m="1092950">regularity.</span>
  <span m="1095070">And</span> <span m="1095250">so</span> <span m="1095790">the</span>
  <span m="1096060">theorem</span> <span m="1096510">is</span> <span m="1096630">still</span>
  <span m="1096930">true.</span></p><p><span m="1097620">It's</span> <span m="1097800">just</span>
  <span m="1098010">not</span> <span m="1098310">meaningful.</span> <span m="1099000">It's</span>
  <span m="1099100">just</span> <span m="1099150">not</span> <span m="1099390">useful.</span>
  <span m="1100050">But</span> <span m="1100230">there</span> <span m="1100380">are</span>
  <span m="1100530">settings</span> <span m="1101040">where</span> <span m="1101670">having</span>
  <span m="1101940">sparse</span> <span m="1102390">graphs--</span> <span m="1102720">and</span>
  <span m="1102810">we'll</span> <span m="1102930">come</span> <span m="1103140">back</span>
  <span m="1103320">to</span> <span m="1103410">this</span> <span m="1103620">later</span>
  <span m="1103920">in</span> <span m="1104010">the</span> <span m="1104100">course--</span>
  <span m="1105410">it's</span> <span m="1105570">important</span> <span m="1105960">to</span>
  <span m="1106110">explore</span> <span m="1106560">what</span> <span m="1106740">happens</span>
  <span m="1107070">to</span> <span m="1107170">sparse</span> <span m="1107470">graphs.</span>
  <span m="1107770">Yeah.</span></p><p><span m="1108257">AUDIENCE:</span> <span m="1108500">So
  that M</span> <span m="1108744">is independent</span> <span m="1109231">of G.</span></p><p><span
  m="1111670">YUFEI ZHAO:</span> <span m="1111910">Yes,</span> <span m="1112150">M</span>
  <span m="1112420">is</span> <span m="1112630">independent</span> <span m="1113290">of</span>
  <span m="1113410">G.</span> <span m="1114360">M</span> <span m="1114600">depends</span>
  <span m="1115030">only</span> <span m="1115330">on</span> <span m="1115450">epsilon.</span></p><p><span
  m="1119500">AUDIENCE:</span> <span m="1119595">M is</span> <span m="1119690">really
  large,</span> <span m="1120123">but</span> <span m="1120556">there's no</span> <span
  m="1120989">enough</span> <span m="1121422">vertices in the</span> <span m="1121855">graph.</span></p><p><span
  m="1122290">YUFEI ZHAO:</span> <span m="1122340">OK,</span> <span m="1122480">question</span>
  <span m="1122750">is,</span> <span m="1122840">what</span> <span m="1122990">happens</span>
  <span m="1123320">when</span> <span m="1123470">M</span> <span m="1123680">is</span>
  <span m="1123800">very</span> <span m="1124040">large,</span> <span m="1124400">but</span>
  <span m="1124550">there</span> <span m="1124640">are</span> <span m="1124670">not</span>
  <span m="1124880">enough</span> <span m="1125150">vertices</span> <span m="1125600">in</span>
  <span m="1125690">the</span> <span m="1125750">graph?</span> <span m="1127170">Well,</span>
  <span m="1127650">if</span> <span m="1127950">your</span> <span m="1128310">M</span>
  <span m="1128790">is</span> <span m="1129090">a</span> <span m="1129150">million,</span>
  <span m="1129870">and</span> <span m="1129990">your</span> <span m="1130140">graph</span>
  <span m="1130440">only</span> <span m="1130620">has</span> <span m="1130830">1,000</span>
  <span m="1131250">vertices,</span> <span m="1132090">what</span> <span m="1132270">you</span>
  <span m="1132360">can</span> <span m="1132510">do</span> <span m="1132690">is</span>
  <span m="1132810">have</span> <span m="1133080">every</span> <span m="1133320">vertex</span>
  <span m="1133770">be its</span> <span m="1134100">own</span> <span m="1134280">part.</span>
  <span m="1138730">Every</span> <span m="1138910">vertex</span> <span m="1139300">is</span>
  <span m="1139450">its</span> <span m="1139570">own</span> <span m="1139720">part,</span>
  <span m="1140020">a</span> <span m="1140080">singleton</span> <span m="1140920">partition.</span>
  <span m="1142060">And</span> <span m="1142270">you</span> <span m="1142390">can</span>
  <span m="1142540">check</span> <span m="1142840">that</span> <span m="1142960">that</span>
  <span m="1143110">partition</span> <span m="1144040">satisfies</span> <span m="1145240">the</span>
  <span m="1146200">properties.</span> <span m="1146980">Every</span> <span m="1147730">pair</span>
  <span m="1148100">is</span> <span m="1148270">a</span> <span m="1148330">single</span>
  <span m="1148750">edge</span> <span m="1149120">and it's</span> <span m="1149470">epsilon</span>
  <span m="1149890">regular.</span> <span m="1152152">Yeah.</span></p><p><span m="1153090">AUDIENCE:</span>
  <span m="1153235">So</span> <span m="1153380">in the</span> <span m="1153630">definition,</span>
  <span m="1154630">is</span> <span m="1155110">it</span> <span m="1155250">sort</span>
  <span m="1155430">of</span> <span m="1155520">like</span> <span m="1155730">all</span>
  <span m="1155880">or</span> <span m="1156000">nothing?</span> <span m="1156330">You
  can</span> <span m="1156540">either</span> <span m="1157160">[INAUDIBLE]</span>
  <span m="1157330">epsilon</span> <span m="1157720">regularity</span> <span m="1158000">[INAUDIBLE].</span>
  <span m="1158600">Do</span> <span m="1159070">you</span> <span m="1159210">get</span>
  <span m="1159420">anything</span> <span m="1160320">where</span> <span m="1160530">if</span>
  <span m="1160740">you,</span> <span m="1160830">like,</span> <span m="1161040">say,</span>
  <span m="1161110">make</span> <span m="1161290">this</span> <span m="1161430">more</span>
  <span m="1161610">continuous,</span> <span m="1162373">so you</span> <span m="1162866">allow
  for it</span> <span m="1163359">to be--</span> <span m="1164838">you quantify</span>
  <span m="1165331">how irregular it</span> <span m="1165824">is,</span> <span m="1166317">and
  then</span> <span m="1166810">can you make</span> <span m="1167303">[INAUDIBLE]?</span></p><p><span
  m="1168790">YUFEI ZHAO:</span> <span m="1168870">OK,</span> <span m="1169910">so</span>
  <span m="1170040">my</span> <span m="1170170">understanding</span> <span m="1170570">what</span>
  <span m="1170660">you're</span> <span m="1170780">asking</span> <span m="1171200">is</span>
  <span m="1171980">in</span> <span m="1172100">the</span> <span m="1172160">definition</span>
  <span m="1172610">up</span> <span m="1172700">there,</span> <span m="1173360">the</span>
  <span m="1173750">sum</span> <span m="1174270">is--</span> <span m="1176300">we</span>
  <span m="1176540">put</span> <span m="1177200">the</span> <span m="1177680">pair
  in</span> <span m="1178040">the</span> <span m="1178100">sum</span> <span m="1178340">of</span>
  <span m="1178460">this</span> <span m="1178640">epsilon</span> <span m="1179000">regular,</span>
  <span m="1179360">and</span> <span m="1179450">otherwise</span> <span m="1179960">don't</span>
  <span m="1180140">put</span> <span m="1180350">it.</span> <span m="1180680">Is</span>
  <span m="1180830">there</span> <span m="1180920">some</span> <span m="1181130">gradual</span>
  <span m="1181670">way</span> <span m="1181910">to</span> <span m="1182030">put</span>
  <span m="1182990">some</span> <span m="1183260">measure</span> <span m="1183650">of</span>
  <span m="1183770">irregularity</span> <span m="1184550">into</span> <span m="1184790">that</span>
  <span m="1184940">sum?</span> <span m="1185450">And</span> <span m="1185600">there</span>
  <span m="1185750">are</span> <span m="1185960">versions</span> <span m="1186410">of</span>
  <span m="1186500">regularity</span> <span m="1187040">lemma</span> <span m="1187310">that</span>
  <span m="1187490">do</span> <span m="1187640">that,</span> <span m="1188410">but</span>
  <span m="1188520">they</span> <span m="1188600">are</span> <span m="1188720">all,</span>
  <span m="1189620">in</span> <span m="1189740">spirit,</span> <span m="1190710">morally</span>
  <span m="1191030">the</span> <span m="1191120">same</span> <span m="1191580">as</span>
  <span m="1191730">that</span> <span m="1191880">one</span> <span m="1192060">there.</span>
  <span m="1193920">Yeah.</span></p><p><span m="1194385">AUDIENCE:</span> <span m="1194501">In</span>
  <span m="1194617">the</span> <span m="1194733">informal</span> <span m="1194850">definition,</span>
  <span m="1195150">what</span> <span m="1195450">does</span> <span m="1195892">&quot;random-like&quot;</span>
  <span m="1196334">mean?</span></p><p><span m="1197660">YUFEI ZHAO:</span> <span
  m="1197800">So</span> <span m="1197940">in</span> <span m="1198050">the</span> <span
  m="1198110">informal</span> <span m="1198470">definition,</span> <span m="1198950">what</span>
  <span m="1199130">does</span> <span m="1199280">&quot;random-like&quot;</span> <span
  m="1199910">mean?</span> <span m="1200510">This</span> <span m="1200750">is</span>
  <span m="1200870">the</span> <span m="1200930">formal</span> <span m="1201260">definition</span>
  <span m="1201800">of</span> <span m="1201860">what</span> <span m="1202100">&quot;random-like&quot;</span>
  <span m="1202710">means.</span> <span m="1203330">So</span> <span m="1203960">actually</span>
  <span m="1204200">later</span> <span m="1204500">on</span> <span m="1204590">in</span>
  <span m="1204680">the</span> <span m="1204770">course,</span> <span m="1205250">one</span>
  <span m="1205490">of</span> <span m="1205550">the</span> <span m="1205640">chapters</span>
  <span m="1206240">will</span> <span m="1206480">explore</span> <span m="1207320">what</span>
  <span m="1207500">pseudo-random</span> <span m="1208280">graphs</span> <span m="1208910">are.</span>
  <span m="1209390">So</span> <span m="1209540">pseudo-random</span> <span m="1210170">graph,</span>
  <span m="1210480">in</span> <span m="1210590">some</span> <span m="1210770">sense,</span>
  <span m="1210980">means</span> <span m="1211220">graphs</span> <span m="1211530">that</span>
  <span m="1211700">are</span> <span m="1211790">not</span> <span m="1212120">random,</span>
  <span m="1212480">but</span> <span m="1212840">behave</span> <span m="1213320">in</span>
  <span m="1213440">some</span> <span m="1213710">sense</span> <span m="1214010">like</span>
  <span m="1214250">random.</span></p><p><span m="1215030">So</span> <span m="1215360">&quot;random-like&quot;</span>
  <span m="1216590">generally</span> <span m="1217040">just</span> <span m="1217250">means</span>
  <span m="1217520">that</span> <span m="1217640">in</span> <span m="1217790">some</span>
  <span m="1218330">aspect,</span> <span m="1219550">in</span> <span m="1219680">some</span>
  <span m="1220460">property,</span> <span m="1221270">it</span> <span m="1221390">looks</span>
  <span m="1221660">like</span> <span m="1221900">a</span> <span m="1221960">random</span>
  <span m="1222920">object.</span> <span m="1223970">And</span> <span m="1225200">this</span>
  <span m="1225500">is</span> <span m="1225680">one</span> <span m="1225980">way</span>
  <span m="1226310">that</span> <span m="1226460">something</span> <span m="1226850">can</span>
  <span m="1227030">look</span> <span m="1227270">like</span> <span m="1227480">random.</span>
  <span m="1227830">So</span> <span m="1228030">a</span> <span m="1228110">random</span>
  <span m="1228680">graph</span> <span m="1229040">has</span> <span m="1229460">this</span>
  <span m="1229670">property,</span> <span m="1231910">but</span> <span m="1232630">random</span>
  <span m="1232930">graphs</span> <span m="1233200">also</span> <span m="1233410">have</span>
  <span m="1233590">many</span> <span m="1233830">other</span> <span m="1234100">properties</span>
  <span m="1234580">that</span> <span m="1234760">are</span> <span m="1234820">not</span>
  <span m="1235060">being</span> <span m="1235720">exhibited</span> <span m="1236800">in</span>
  <span m="1237130">this</span> <span m="1237280">definition.</span></p><p><span m="1237790">But</span>
  <span m="1237910">this</span> <span m="1238060">is</span> <span m="1238210">one</span>
  <span m="1238510">way</span> <span m="1239050">that</span> <span m="1239770">graph</span>
  <span m="1240250">can</span> <span m="1240520">look</span> <span m="1240790">like</span>
  <span m="1241000">random.</span> <span m="1242260">So</span> <span m="1242380">that's</span>
  <span m="1242590">a</span> <span m="1242680">great</span> <span m="1243070">question.</span>
  <span m="1243430">And</span> <span m="1243520">we'll</span> <span m="1243670">come</span>
  <span m="1243850">back</span> <span m="1244030">to</span> <span m="1244120">that</span>
  <span m="1244270">topic</span> <span m="1244630">later</span> <span m="1244900">in</span>
  <span m="1244990">the</span> <span m="1245080">course.</span></p><p><span m="1247950">All</span>
  <span m="1248070">of</span> <span m="1248130">these</span> <span m="1248280">are</span>
  <span m="1248340">great</span> <span m="1248490">questions.</span> <span m="1249030">So</span>
  <span m="1249860">Szemeredi's</span> <span m="1250320">regularity</span> <span m="1250770">lemma,</span>
  <span m="1251070">the</span> <span m="1251160">first</span> <span m="1251400">time</span>
  <span m="1251520">you</span> <span m="1251610">see</span> <span m="1251790">it,</span>
  <span m="1251870">it</span> <span m="1252600">can</span> <span m="1252750">look</span>
  <span m="1252930">somewhat</span> <span m="1253230">scary.</span> <span m="1254310">But</span>
  <span m="1254490">I</span> <span m="1254610">want</span> <span m="1254900">you to</span>
  <span m="1255070">try</span> <span m="1255330">to</span> <span m="1255450">understand</span>
  <span m="1255910">it</span> <span m="1255990">more</span> <span m="1256140">conceptually.</span>
  <span m="1256900">So</span> <span m="1256950">please</span> <span m="1257250">do</span>
  <span m="1257400">ask</span> <span m="1257580">questions.</span></p><p><span m="1265900">Before</span>
  <span m="1266650">diving</span> <span m="1266920">into</span> <span m="1267130">the</span>
  <span m="1267190">proof,</span> <span m="1267490">I</span> <span m="1267760">want</span>
  <span m="1267970">to</span> <span m="1268030">make</span> <span m="1268210">a</span>
  <span m="1268270">few</span> <span m="1268450">more</span> <span m="1268630">remarks</span>
  <span m="1269350">about</span> <span m="1269640">a</span> <span m="1269710">statement.</span>
  <span m="1275300">It</span> <span m="1275420">is</span> <span m="1275540">possible</span>
  <span m="1276050">to--</span> <span m="1278130">we</span> <span m="1278300">will</span>
  <span m="1278450">prove</span> <span m="1278780">this</span> <span m="1278990">version</span>
  <span m="1279280">of</span> <span m="1279350">the</span> <span m="1279440">regularity</span>
  <span m="1280110">lemma.</span> <span m="1281840">But</span> <span m="1282530">as</span>
  <span m="1282680">I</span> <span m="1282740">mentioned,</span> <span m="1283690">it</span>
  <span m="1284110">is</span> <span m="1284240">the</span> <span m="1284360">spirit</span>
  <span m="1284900">of</span> <span m="1284990">the</span> <span m="1285080">regularity</span>
  <span m="1285590">lemma</span> <span m="1285930">that I</span> <span m="1286190">care</span>
  <span m="1286610">more</span> <span m="1286850">about.</span></p><p><span m="1287360">And</span>
  <span m="1288260">it's</span> <span m="1288380">a</span> <span m="1288410">very</span>
  <span m="1288620">robust</span> <span m="1289160">statement.</span> <span m="1289610">You</span>
  <span m="1289700">can</span> <span m="1289940">add</span> <span m="1290150">on</span>
  <span m="1290690">extra</span> <span m="1291020">declarations</span> <span m="1292070">that</span>
  <span m="1292530">somehow</span> <span m="1292830">doesn't</span> <span m="1293060">change</span>
  <span m="1293360">the</span> <span m="1293420">spirit.</span> <span m="1293780">And</span>
  <span m="1293870">the</span> <span m="1293960">proof</span> <span m="1294260">will</span>
  <span m="1294620">be</span> <span m="1294770">more</span> <span m="1294980">or</span>
  <span m="1295010">less</span> <span m="1295250">the</span> <span m="1295340">same,</span>
  <span m="1295610">but</span> <span m="1295880">for</span> <span m="1296240">various</span>
  <span m="1296630">applications</span> <span m="1297230">will</span> <span m="1297350">be</span>
  <span m="1297440">slightly</span> <span m="1297830">more</span> <span m="1297980">useful.</span>
  <span m="1298770">So</span> <span m="1298790">in</span> <span m="1298880">particular,</span>
  <span m="1299870">it</span> <span m="1300020">is</span> <span m="1300110">possible</span>
  <span m="1300620">to</span> <span m="1300740">make</span> <span m="1301300">the</span>
  <span m="1301430">partition</span> <span m="1302330">equitable.</span></p><p><span
  m="1316060">And</span> <span m="1316750">&quot;equitable</span> <span m="1317140">partition&quot;</span>
  <span m="1317620">sometimes</span> <span m="1318000">is</span> <span m="1318130">also</span>
  <span m="1318550">called</span> <span m="1318820">an</span> <span m="1318960">&quot;equipartition,&quot;</span>
  <span m="1324210">meaning</span> <span m="1324540">that</span> <span m="1324840">it</span>
  <span m="1324930">has</span> <span m="1327000">such</span> <span m="1327270">that</span>
  <span m="1327600">all</span> <span m="1327840">the</span> <span m="1328260">Ai's,</span>
  <span m="1329070">all</span> <span m="1329490">the</span> <span m="1329750">Bi's</span>
  <span m="1330330">have</span> <span m="1330510">sizes</span> <span m="1331560">differing</span>
  <span m="1332340">by</span> <span m="1332640">at most</span> <span m="1332970">1.</span>
  <span m="1339090">So</span> <span m="1339220">basically,</span> <span m="1340420">all</span>
  <span m="1340570">the</span> <span m="1340690">parts</span> <span m="1341020">have</span>
  <span m="1341110">the</span> <span m="1341200">same</span> <span m="1341440">size</span>
  <span m="1342190">up</span> <span m="1342310">to</span> <span m="1342430">at most</span>
  <span m="1342730">1,</span> <span m="1342910">because</span> <span m="1343210">of</span>
  <span m="1343330">divisibility.</span> <span m="1345700">So</span> <span m="1346210">let</span>
  <span m="1346360">me</span> <span m="1346450">state</span> <span m="1346750">a</span>
  <span m="1346810">version</span> <span m="1347320">of</span> <span m="1347770">regularity</span>
  <span m="1348370">lemma</span> <span m="1349570">for</span> <span m="1350050">equitable</span>
  <span m="1350470">partitions.</span></p><p><span m="1351690">So</span> <span m="1352090">for</span>
  <span m="1352270">every</span> <span m="1352540">epsilon</span> <span m="1354070">in</span>
  <span m="1354400">m,</span> <span m="1354870">little</span> <span m="1355090">m0,</span>
  <span m="1357010">there</span> <span m="1357190">exists</span> <span m="1358440">a</span>
  <span m="1358540">big</span> <span m="1358780">M</span> <span m="1360400">such</span>
  <span m="1360730">that</span> <span m="1364690">every</span> <span m="1364940">graph</span>
  <span m="1368560">has</span> <span m="1370000">an</span> <span m="1370210">epsilon</span>
  <span m="1373180">regular</span> <span m="1375600">equitable</span> <span m="1376020">partition</span>
  <span m="1381770">of</span> <span m="1381950">the</span> <span m="1382040">vertex</span>
  <span m="1382460">set</span> <span m="1385250">into</span> <span m="1387560">k</span>
  <span m="1387830">parts,</span> <span m="1389810">where</span> <span m="1389990">k</span>
  <span m="1391400">is</span> <span m="1391730">at</span> <span m="1391820">least</span>
  <span m="1392390">little</span> <span m="1392630">m,</span> <span m="1393020">so</span>
  <span m="1393200">I</span> <span m="1393290">can</span> <span m="1393440">guarantee</span>
  <span m="1393860">a</span> <span m="1393890">minimum</span> <span m="1394280">number</span>
  <span m="1394550">of</span> <span m="1394640">parts,</span> <span m="1395420">and</span>
  <span m="1395590">at</span> <span m="1395690">most</span> <span m="1396590">some</span>
  <span m="1396860">bounded</span> <span m="1397120">number.</span> <span m="1397940">Again</span>
  <span m="1398180">this</span> <span m="1398280">bound</span> <span m="1399020">may</span>
  <span m="1399170">depend</span> <span m="1399620">on</span> <span m="1399740">your</span>
  <span m="1399890">inputs</span> <span m="1401000">epsilon</span> <span m="1401630">and</span>
  <span m="1402042">m0,</span> <span m="1404750">but</span> <span m="1404930">it</span>
  <span m="1405020">does</span> <span m="1405140">not</span> <span m="1405350">depend</span>
  <span m="1405680">on</span> <span m="1405830">the</span> <span m="1405890">graph</span>
  <span m="1406190">itself.</span> <span m="1408740">And</span> <span m="1408870">you</span>
  <span m="1408960">see</span> <span m="1409270">the</span> <span m="1409450">slightly</span>
  <span m="1409870">stronger</span> <span m="1410290">conclusion</span> <span m="1410950">for</span>
  <span m="1411090">many</span> <span m="1411310">applications</span> <span m="1412000">is</span>
  <span m="1412120">more</span> <span m="1412300">convenient,</span> <span m="1413170">to</span>
  <span m="1413530">use</span> <span m="1414430">this</span> <span m="1414670">formulation.</span></p><p><span
  m="1417120">And</span> <span m="1417270">I</span> <span m="1417350">will</span>
  <span m="1417450">comment</span> <span m="1417900">on</span> <span m="1417990">how</span>
  <span m="1419070">you</span> <span m="1419250">may</span> <span m="1419460">modify</span>
  <span m="1420240">the</span> <span m="1420360">proof</span> <span m="1421390">that</span>
  <span m="1421710">we'll</span> <span m="1421890">see</span> <span m="1422280">today</span>
  <span m="1423000">into</span> <span m="1423360">one</span> <span m="1423660">where</span>
  <span m="1423930">you</span> <span m="1424020">can</span> <span m="1424200">guarantee</span>
  <span m="1424740">equitability.</span> <span m="1426820">And</span> <span m="1426980">you</span>
  <span m="1427100">see</span> <span m="1427250">that</span> <span m="1427390">for</span>
  <span m="1428960">this</span> <span m="1429830">m,</span> <span m="1430270">little</span>
  <span m="1430520">m0</span> <span m="1430990">too</span> <span m="1431150">small,</span>
  <span m="1437750">for</span> <span m="1437800">example,</span> <span m="1438230">if</span>
  <span m="1438280">it's</span> <span m="1438730">somewhat</span> <span m="1439090">larger</span>
  <span m="1439450">than</span> <span m="1439570">1</span> <span m="1439780">over</span>
  <span m="1439990">epsilon,</span> <span m="1442040">when</span> <span m="1442250">you</span>
  <span m="1442370">look</span> <span m="1442610">at</span> <span m="1442670">the</span>
  <span m="1442760">definition</span> <span m="1443450">of</span> <span m="1444470">epsilon</span>
  <span m="1444890">regular</span> <span m="1445280">partition,</span> <span m="1446260">it</span>
  <span m="1446360">suffices</span> <span m="1447140">to</span> <span m="1447290">check</span>
  <span m="1447680">that at</span> <span m="1448010">most</span> <span m="1448820">epsilon</span>
  <span m="1449300">k</span> <span m="1449580">squared,</span> <span m="1450080">epsilon</span>
  <span m="1450530">fraction</span> <span m="1451100">of</span> <span m="1451220">the</span>
  <span m="1451280">pairs,</span> <span m="1454090">Vi,</span> <span m="1455420">Vj</span>
  <span m="1456225">is</span> <span m="1456510">epsilon</span> <span m="1457410">regular</span>
  <span m="1458430">over</span> <span m="1460010">i</span> <span m="1460380">different</span>
  <span m="1460710">from</span> <span m="1460950">j,</span> <span m="1462000">again</span>
  <span m="1462240">up</span> <span m="1462390">to</span> <span m="1462480">changing</span>
  <span m="1462960">epsilon,</span> <span m="1463950">let's</span> <span m="1464100">say,</span>
  <span m="1464220">by</span> <span m="1464400">a</span> <span m="1464430">factor</span>
  <span m="1464790">of</span> <span m="1464910">2.</span> <span m="1465580">So</span>
  <span m="1465750">all</span> <span m="1467130">of</span> <span m="1467190">these</span>
  <span m="1467370">definitions</span> <span m="1467940">are</span> <span m="1468150">basically</span>
  <span m="1468540">the</span> <span m="1468630">same</span> <span m="1469020">up</span>
  <span m="1469170">to</span> <span m="1469380">small</span> <span m="1469680">changes</span>
  <span m="1470130">in</span> <span m="1470220">the</span> <span m="1470280">parameters.</span></p><p><span
  m="1482420">Next</span> <span m="1482560">time,</span> <span m="1482710">we'll</span>
  <span m="1482860">see</span> <span m="1483040">how</span> <span m="1483220">to</span>
  <span m="1483370">apply</span> <span m="1483730">the</span> <span m="1483850">regularity</span>
  <span m="1484530">lemma.</span> <span m="1485080">And</span> <span m="1485380">we</span>
  <span m="1485710">will</span> <span m="1485920">apply</span> <span m="1486310">it</span>
  <span m="1486430">in</span> <span m="1486940">the</span> <span m="1487030">first</span>
  <span m="1487330">form,</span> <span m="1487960">but</span> <span m="1488170">you</span>
  <span m="1488290">see</span> <span m="1488440">the</span> <span m="1488530">second</span>
  <span m="1488830">form</span> <span m="1489130">guarantees</span> <span m="1489730">you</span>
  <span m="1489850">a</span> <span m="1489910">somewhat</span> <span m="1490210">stronger</span>
  <span m="1490630">conclusion,</span> <span m="1491140">and</span> <span m="1491290">sometimes</span>
  <span m="1491710">more</span> <span m="1491920">convenient</span> <span m="1492430">to</span>
  <span m="1492550">use.</span> <span m="1493370">So</span> <span m="1493480">for</span>
  <span m="1493630">example</span> <span m="1494260">on</span> <span m="1494410">the</span>
  <span m="1494740">homework</span> <span m="1495070">problems,</span> <span m="1495430">if</span>
  <span m="1495520">you</span> <span m="1495640">wish</span> <span m="1495880">to</span>
  <span m="1496000">use</span> <span m="1496240">the</span> <span m="1496300">second</span>
  <span m="1496660">form,</span> <span m="1497890">then</span> <span m="1498310">please</span>
  <span m="1498580">go</span> <span m="1498760">ahead.</span> <span m="1499900">Just</span>
  <span m="1500170">make</span> <span m="1500380">your</span> <span m="1500500">life</span>
  <span m="1500800">somewhat</span> <span m="1501130">easier,</span> <span m="1501760">but
  it</span> <span m="1502120">essentially</span> <span m="1502730">captures</span>
  <span m="1503240">all</span> <span m="1503380">the</span> <span m="1503470">spirit</span>
  <span m="1504040">of</span> <span m="1504220">Szemeredi's</span> <span m="1504760">regularity.</span>
  <span m="1509860">Any</span> <span m="1510040">questions</span> <span m="1510370">so</span>
  <span m="1510520">far?</span></p><p><span m="1513610">I</span> <span m="1513670">want</span>
  <span m="1513850">to</span> <span m="1514000">explain</span> <span m="1515140">the</span>
  <span m="1515470">idea</span> <span m="1515920">of</span> <span m="1516070">the</span>
  <span m="1516160">proof</span> <span m="1516760">of</span> <span m="1516910">the</span>
  <span m="1517000">regularity</span> <span m="1517600">lemma.</span> <span m="1519220">And</span>
  <span m="1519490">this</span> <span m="1519700">is</span> <span m="1519820">a</span>
  <span m="1519850">very</span> <span m="1520060">important</span> <span m="1521110">technique</span>
  <span m="1521980">in</span> <span m="1522070">this</span> <span m="1522250">area</span>
  <span m="1523060">called</span> <span m="1523300">the</span> <span m="1523450">&quot;energy</span>
  <span m="1523930">increment</span> <span m="1524500">argument.&quot;</span> <span
  m="1535850">Here's</span> <span m="1536090">the</span> <span m="1536240">idea.</span>
  <span m="1538110">We</span> <span m="1538160">start</span> <span m="1539690">with</span>
  <span m="1540770">some</span> <span m="1541040">partition,</span> <span m="1541640">so</span>
  <span m="1541850">for</span> <span m="1542030">example,</span> <span m="1543710">the</span>
  <span m="1543830">trivial</span> <span m="1544220">partition--</span> <span m="1546250">and</span>
  <span m="1546350">by</span> <span m="1546500">that</span> <span m="1546770">I</span>
  <span m="1546860">mean</span> <span m="1548480">you</span> <span m="1548660">only</span>
  <span m="1548870">have</span> <span m="1549050">one</span> <span m="1549320">part.</span></p><p><span
  m="1552300">All</span> <span m="1552490">the</span> <span m="1552590">vertices</span>
  <span m="1553070">are</span> <span m="1553160">in</span> <span m="1553250">one</span>
  <span m="1553430">part.</span> <span m="1553670">You're</span> <span m="1553790">not</span>
  <span m="1553970">doing</span> <span m="1554180">anything</span> <span m="1554570">to</span>
  <span m="1554750">the</span> <span m="1554870">vertex</span> <span m="1555270">set.</span>
  <span m="1555830">It's</span> <span m="1556160">one</span> <span m="1556430">gigantic</span>
  <span m="1557000">part.</span></p><p><span m="1558770">Or</span> <span m="1559580">if</span>
  <span m="1559700">you're</span> <span m="1559850">looking</span> <span m="1560180">at</span>
  <span m="1560330">some</span> <span m="1560570">other</span> <span m="1560810">variant,</span>
  <span m="1561350">you</span> <span m="1561440">can</span> <span m="1561590">easily</span>
  <span m="1561950">modify</span> <span m="1562430">the</span> <span m="1562520">proof.</span>
  <span m="1563120">So</span> <span m="1563300">for</span> <span m="1563510">example,</span>
  <span m="1564290">you</span> <span m="1564380">can</span> <span m="1564890">also</span>
  <span m="1565220">look</span> <span m="1565520">at</span> <span m="1565760">an</span>
  <span m="1566000">arbitrary</span> <span m="1566540">partition</span> <span m="1569050">into</span>
  <span m="1570700">little</span> <span m="1570940">m0</span> <span m="1571600">parts,</span>
  <span m="1572770">if</span> <span m="1573040">you</span> <span m="1573160">wish</span>
  <span m="1573400">to</span> <span m="1573520">have</span> <span m="1573730">that</span>
  <span m="1573910">as</span> <span m="1574120">your</span> <span m="1574150">starting</span>
  <span m="1574510">point.</span> <span m="1574690">So</span> <span m="1574800">or</span>
  <span m="1574990">I'm</span> <span m="1575110">saying is</span> <span m="1575380">that</span>
  <span m="1575520">this</span> <span m="1575650">proof</span> <span m="1575920">is</span>
  <span m="1576040">fairly</span> <span m="1576400">robust.</span></p><p><span m="1579880">And</span>
  <span m="1579930">we're</span> <span m="1580080">going</span> <span m="1580320">to</span>
  <span m="1581910">do</span> <span m="1582090">some</span> <span m="1582330">iterations.</span>
  <span m="1586680">So</span> <span m="1586860">as</span> <span m="1587020">long</span>
  <span m="1587330">as</span> <span m="1587520">your</span> <span m="1587700">partition</span>
  <span m="1588480">is</span> <span m="1588660">not</span> <span m="1589200">epsilon</span>
  <span m="1589650">regular,</span> <span m="1597970">we</span> <span m="1598150">will</span>
  <span m="1598840">do</span> <span m="1599020">something</span> <span m="1599410">to</span>
  <span m="1599500">the</span> <span m="1599590">partition</span> <span m="1600550">to</span>
  <span m="1602140">move</span> <span m="1602350">forward.</span> <span m="1604660">And</span>
  <span m="1605200">what</span> <span m="1605350">we</span> <span m="1605470">will</span>
  <span m="1605650">do</span> <span m="1606550">is</span> <span m="1608170">look</span>
  <span m="1608550">at</span> <span m="1609820">each</span> <span m="1614170">pair</span>
  <span m="1614590">of</span> <span m="1615780">parts</span> <span m="1616230">in</span>
  <span m="1616340">your</span> <span m="1616480">partition</span> <span m="1617740">that's</span>
  <span m="1618220">not</span> <span m="1618820">epsilon</span> <span m="1619330">regular.</span>
  <span m="1624170">Well,</span> <span m="1624430">if</span> <span m="1624550">they're</span>
  <span m="1624700">not</span> <span m="1625180">epsilon</span> <span m="1625570">regular,</span>
  <span m="1625960">then</span> <span m="1626120">I</span> <span m="1626200">can</span>
  <span m="1626350">find</span> <span m="1626830">a</span> <span m="1626920">pair</span>
  <span m="1627280">of</span> <span m="1627430">subsets</span> <span m="1628390">which</span>
  <span m="1628570">are</span> <span m="1628690">denoted</span> <span m="1628960">by</span>
  <span m="1629140">the</span> <span m="1629320">A's</span> <span m="1634530">that</span>
  <span m="1634890">witnesses</span> <span m="1637520">this</span> <span m="1638070">non</span>
  <span m="1638400">regularity,</span> <span m="1642480">that</span> <span m="1643150">witnesses</span>
  <span m="1643550">the</span> <span m="1643650">irregularity.</span></p><p><span
  m="1646880">And</span> <span m="1647840">we</span> <span m="1647990">start</span>
  <span m="1648260">with</span> <span m="1648410">some</span> <span m="1648560">partition.</span>
  <span m="1649370">So</span> <span m="1649490">now</span> <span m="1650150">let</span>
  <span m="1650390">us</span> <span m="1651230">refine</span> <span m="1651830">the</span>
  <span m="1651920">partition</span> <span m="1653210">into</span> <span m="1653980">a</span>
  <span m="1654050">partition in</span> <span m="1654470">even</span> <span m="1655010">more</span>
  <span m="1655310">parts</span> <span m="1656720">by</span> <span m="1657740">simultaneously</span>
  <span m="1663960">refining</span> <span m="1664710">the</span> <span m="1664800">partition</span>
  <span m="1667490">using</span> <span m="1673090">all</span> <span m="1673270">of</span>
  <span m="1673360">these</span> <span m="1673650">Ai, j's</span> <span m="1675510">that</span>
  <span m="1675640">we</span> <span m="1675790">found</span> <span m="1677530">in</span>
  <span m="1677650">the</span> <span m="1677710">step</span> <span m="1678190">above.</span>
  <span m="1680360">So</span> <span m="1680520">you</span> <span m="1680610">start</span>
  <span m="1680850">with</span> <span m="1680970">some</span> <span m="1681120">partition.</span>
  <span m="1681930">If</span> <span m="1682050">it</span> <span m="1682140">is</span>
  <span m="1682260">not</span> <span m="1682440">regular,</span> <span m="1683280">I</span>
  <span m="1683400">can</span> <span m="1683940">chop</span> <span m="1684330">up</span>
  <span m="1685560">the</span> <span m="1685650">various</span> <span m="1686040">parts</span>
  <span m="1686760">in</span> <span m="1686880">some</span> <span m="1687090">way.</span></p><p><span
  m="1688120">So</span> <span m="1688290">I</span> <span m="1688380">start</span>
  <span m="1688800">with</span> <span m="1688980">some</span> <span m="1689340">partition</span>
  <span m="1689940">over</span> <span m="1690380">here.</span> <span m="1692090">And</span>
  <span m="1692300">what</span> <span m="1692500">we</span> <span m="1692590">are</span>
  <span m="1692710">going</span> <span m="1692930">to</span> <span m="1693020">do</span>
  <span m="1693290">is,</span> <span m="1693920">let's</span> <span m="1694100">say</span>
  <span m="1694880">between</span> <span m="1695420">these</span> <span m="1695660">two,</span>
  <span m="1695930">it's</span> <span m="1696080">not</span> <span m="1696710">epsilon</span>
  <span m="1697070">regular,</span> <span m="1697730">so</span> <span m="1697940">I</span>
  <span m="1698030">can</span> <span m="1698180">find</span> <span m="1699110">some</span>
  <span m="1699590">pairs</span> <span m="1699980">of</span> <span m="1700040">vertex</span>
  <span m="1700460">sets</span> <span m="1700790">that</span> <span m="1701000">exhibits</span>
  <span m="1701570">the</span> <span m="1701720">irregularity.</span> <span m="1703260">I</span>
  <span m="1703400">chop</span> <span m="1703700">it</span> <span m="1703820">up.</span></p><p><span
  m="1704650">And</span> <span m="1704870">I</span> <span m="1704990">can</span> <span
  m="1705170">keep</span> <span m="1705650">further</span> <span m="1706340">chopping</span>
  <span m="1706790">up</span> <span m="1706910">the</span> <span m="1707030">rest</span>
  <span m="1707660">of</span> <span m="1709120">the</span> <span m="1709340">parts.</span>
  <span m="1711230">If</span> <span m="1711380">these</span> <span m="1711620">two</span>
  <span m="1711770">parts</span> <span m="1712070">are</span> <span m="1712130">not</span>
  <span m="1712400">epsilon</span> <span m="1712820">regular,</span> <span m="1713420">then</span>
  <span m="1713840">I</span> <span m="1713960">chop</span> <span m="1714230">it</span>
  <span m="1714350">up</span> <span m="1714470">like</span> <span m="1714650">that.</span>
  <span m="1715580">And</span> <span m="1715790">I</span> <span m="1715880">can</span>
  <span m="1716510">keep</span> <span m="1716720">on</span> <span m="1716810">doing</span>
  <span m="1717140">it.</span></p><p><span m="1718840">And originally,</span> <span
  m="1719520">I</span> <span m="1719570">have</span> <span m="1719660">three</span>
  <span m="1719930">parts.</span> <span m="1720260">Now</span> <span m="1720500">I</span>
  <span m="1720530">have</span> <span m="1720950">12</span> <span m="1721220">parts.</span>
  <span m="1723040">And</span> <span m="1723210">this</span> <span m="1723390">is</span>
  <span m="1723480">a</span> <span m="1723540">refined</span> <span m="1724020">partition.</span>
  <span m="1725580">And</span> <span m="1725680">now</span> <span m="1725860">I</span>
  <span m="1725950">repeat</span> <span m="1727510">until</span> <span m="1728260">I</span>
  <span m="1728380">am</span> <span m="1728530">done.</span> <span m="1729130">I</span>
  <span m="1729280">am</span> <span m="1729400">done</span> <span m="1730210">when</span>
  <span m="1730570">I</span> <span m="1730750">obtain</span> <span m="1731380">a</span>
  <span m="1731470">partition</span> <span m="1732280">that</span> <span m="1732490">is</span>
  <span m="1732700">epsilon</span> <span m="1733120">regular.</span></p><p><span m="1735750">Now,</span>
  <span m="1736190">the</span> <span m="1736310">basic</span> <span m="1736700">question</span>
  <span m="1737090">when</span> <span m="1737240">it</span> <span m="1737300">comes</span>
  <span m="1737570">to</span> <span m="1737660">the</span> <span m="1737780">strategy</span>
  <span m="1738260">is,</span> <span m="1738530">are</span> <span m="1738920">you</span>
  <span m="1739190">ever</span> <span m="1739430">going</span> <span m="1739580">to</span>
  <span m="1739670">be</span> <span m="1739760">done?</span> <span m="1740270">When</span>
  <span m="1740600">are</span> <span m="1740720">you</span> <span m="1740840">going</span>
  <span m="1740990">to</span> <span m="1741050">be</span> <span m="1741170">done?</span>
  <span m="1742570">And</span> <span m="1742790">if</span> <span m="1742940">this</span>
  <span m="1743120">process</span> <span m="1743480">goes</span> <span m="1743750">on</span>
  <span m="1743870">forever</span> <span m="1744650">or</span> <span m="1744770">goes</span>
  <span m="1745010">on</span> <span m="1745100">for</span> <span m="1745220">a</span>
  <span m="1745250">very</span> <span m="1745490">long</span> <span m="1745670">time,</span>
  <span m="1746660">then</span> <span m="1746930">you</span> <span m="1747050">might</span>
  <span m="1747200">have</span> <span m="1747350">a</span> <span m="1747410">lot</span>
  <span m="1747680">of</span> <span m="1747740">parts.</span> <span m="1748130">But</span>
  <span m="1748250">we</span> <span m="1748370">want</span> <span m="1748590">to</span>
  <span m="1748640">guarantee</span> <span m="1749210">that</span> <span m="1749450">there</span>
  <span m="1749600">is</span> <span m="1749660">a</span> <span m="1749720">bounded</span>
  <span m="1750230">number</span> <span m="1750560">of</span> <span m="1750620">parts.</span></p><p><span
  m="1752680">So</span> <span m="1754290">what</span> <span m="1754510">we</span>
  <span m="1754660">will</span> <span m="1754840">show</span> <span m="1756550">is</span>
  <span m="1756730">that--</span> <span m="1758470">to</span> <span m="1758590">show</span>
  <span m="1758920">that</span> <span m="1759880">you</span> <span m="1760000">have</span>
  <span m="1760180">a</span> <span m="1760240">small</span> <span m="1760570">number</span>
  <span m="1760900">of</span> <span m="1760960">parts,</span> <span m="1762360">in</span>
  <span m="1762460">other</span> <span m="1762560">words,</span> <span m="1762890">why</span>
  <span m="1763240">does</span> <span m="1763480">this</span> <span m="1763660">process</span>
  <span m="1764110">even</span> <span m="1764350">stop--</span> <span m="1770915">and</span>
  <span m="1771400">in</span> <span m="1771490">particular,</span> <span m="1771970">we</span>
  <span m="1772090">want</span> <span m="1772340">it</span> <span m="1772510">to</span>
  <span m="1772690">stop</span> <span m="1773080">after</span> <span m="1773380">a</span>
  <span m="1773410">small</span> <span m="1773770">number</span> <span m="1774130">of</span>
  <span m="1774220">steps,</span> <span m="1777450">after</span> <span m="1777690">a</span>
  <span m="1777760">bounded</span> <span m="1778080">number</span> <span m="1778320">of</span>
  <span m="1778410">steps.</span> <span m="1780750">And</span> <span m="1780890">to</span>
  <span m="1780980">do</span> <span m="1781100">this,</span> <span m="1781550">we</span>
  <span m="1781670">will</span> <span m="1782040">define</span> <span m="1782450">some</span>
  <span m="1782690">notion</span> <span m="1783230">called</span> <span m="1783560">an</span>
  <span m="1783770">&quot;energy&quot;</span> <span m="1786490">of</span> <span m="1786610">a</span>
  <span m="1786650">partition.</span> <span m="1791370">And</span> <span m="1791580">this</span>
  <span m="1791910">energy</span> <span m="1792840">will</span> <span m="1794280">increase.</span></p><p><span
  m="1795280">So</span> <span m="1795420">first</span> <span m="1795690">of</span>
  <span m="1795780">all,</span> <span m="1795870">the</span> <span m="1796020">energy</span>
  <span m="1796470">is</span> <span m="1796620">some</span> <span m="1796890">quantity</span>
  <span m="1798300">that</span> <span m="1798420">we'll</span> <span m="1798630">define</span>
  <span m="1799560">that</span> <span m="1799740">lies</span> <span m="1800670">between</span>
  <span m="1802290">0</span> <span m="1802650">and</span> <span m="1802740">1.</span>
  <span m="1802980">It's</span> <span m="1803070">some</span> <span m="1803280">real</span>
  <span m="1803490">number</span> <span m="1803790">lying</span> <span m="1804030">between</span>
  <span m="1804330">0</span> <span m="1804600">and</span> <span m="1804690">1.</span>
  <span m="1805860">And</span> <span m="1806190">each</span> <span m="1806460">step,</span>
  <span m="1810770">the</span> <span m="1810920">energy</span> <span m="1813590">goes</span>
  <span m="1813860">up</span> <span m="1814760">by</span> <span m="1815870">some</span>
  <span m="1816500">specific</span> <span m="1817340">quantity.</span></p><p><span
  m="1822920">Therefore,</span> <span m="1824050">because</span> <span m="1824380">the</span>
  <span m="1824470">energy</span> <span m="1824800">cannot</span> <span m="1825190">increase</span>
  <span m="1825610">past</span> <span m="1825970">1,</span> <span m="1826520">this</span>
  <span m="1826720">iteration</span> <span m="1827260">stops</span> <span m="1828430">after</span>
  <span m="1828940">a</span> <span m="1829010">bounded</span> <span m="1829420">number</span>
  <span m="1829720">of</span> <span m="1829810">steps.</span> <span m="1833160">And</span>
  <span m="1833270">once</span> <span m="1833510">it's</span> <span m="1833630">done,</span>
  <span m="1835730">we</span> <span m="1835840">end</span> <span m="1836080">up</span>
  <span m="1836260">with</span> <span m="1836800">a</span> <span m="1837460">epsilon</span>
  <span m="1838120">regular</span> <span m="1838600">partition.</span> <span m="1842000">So</span>
  <span m="1842150">that's</span> <span m="1842390">the</span> <span m="1842480">basic</span>
  <span m="1842930">strategy.</span> <span m="1844800">And</span> <span m="1845870">what</span>
  <span m="1846020">I</span> <span m="1846080">want</span> <span m="1846200">to</span>
  <span m="1846260">show</span> <span m="1846440">you</span> <span m="1846530">is</span>
  <span m="1846650">how</span> <span m="1846860">to</span> <span m="1846980">execute</span>
  <span m="1847640">that</span> <span m="1847820">strategy.</span> <span m="1849620">Any</span>
  <span m="1849800">questions</span> <span m="1850180">so</span> <span m="1850340">far?</span>
  <span m="1851023">Yes.</span></p><p><span m="1851486">AUDIENCE:</span> <span m="1851717">Just</span>
  <span m="1851949">to clarify</span> <span m="1852875">[INAUDIBLE]</span> <span m="1853338">a</span>
  <span m="1853801">bit,</span> <span m="1855760">if</span> <span m="1855970">some</span>
  <span m="1856420">Vi's</span> <span m="1857075">into</span> <span m="1858350">non-epsilon</span>
  <span m="1858750">regular</span> <span m="1859162">partitions,</span> <span m="1859574">is
  it</span> <span m="1860398">possible</span> <span m="1860810">for</span> <span m="1860980">Ai,j</span>
  <span m="1861461">and</span> <span m="1861942">Aik</span> <span m="1862423">to</span>
  <span m="1862904">overlap</span> <span m="1863385">somehow,</span> <span m="1863866">right?</span>
  <span m="1864347">Just kind of</span> <span m="1864828">make those</span> <span
  m="1865309">into three</span> <span m="1865790">partitions?</span></p><p><span m="1868200">YUFEI
  ZHAO:</span> <span m="1868285">So</span> <span m="1868370">if</span> <span m="1868490">I</span>
  <span m="1868580">understand</span> <span m="1868940">correctly,</span> <span m="1869210">you</span>
  <span m="1869480">are</span> <span m="1869660">worried</span> <span m="1870080">about</span>
  <span m="1872250">between</span> <span m="1872760">different</span> <span m="1873250">pairs,</span>
  <span m="1873880">you</span> <span m="1873980">might</span> <span m="1874020">have</span>
  <span m="1874230">interactions.</span></p><p><span m="1875110">AUDIENCE:</span>
  <span m="1875283">Yeah.</span></p><p><span m="1876150">YUFEI ZHAO:</span> <span
  m="1876292">So</span> <span m="1876720">you</span> <span m="1876870">have</span>
  <span m="1876930">seen</span> <span m="1877170">the</span> <span m="1877260">proof,</span>
  <span m="1877500">but</span> <span m="1877650">I</span> <span m="1877740">think</span>
  <span m="1877920">this</span> <span m="1878100">is</span> <span m="1878190">actually
  a</span> <span m="1878490">very</span> <span m="1878700">important</span> <span
  m="1879060">and</span> <span m="1879540">somewhat</span> <span m="1879840">subtle</span>
  <span m="1880200">point,</span> <span m="1880890">is</span> <span m="1881070">that</span>
  <span m="1881880">I</span> <span m="1882060">do</span> <span m="1882300">not</span>
  <span m="1883380">refine</span> <span m="1884430">at</span> <span m="1884670">each</span>
  <span m="1884910">step,</span> <span m="1885330">I</span> <span m="1885480">find</span>
  <span m="1885840">a</span> <span m="1885900">pair</span> <span m="1886170">of</span>
  <span m="1886290">witnessing</span> <span m="1886830">sets.</span> <span m="1887520">I</span>
  <span m="1887640">find</span> <span m="1888120">all</span> <span m="1888270">of</span>
  <span m="1888360">these</span> <span m="1889140">witnessing</span> <span m="1889680">sets</span>
  <span m="1890340">all</span> <span m="1890520">at</span> <span m="1890640">the</span>
  <span m="1890700">same</span> <span m="1891000">time,</span> <span m="1891860">and</span>
  <span m="1892010">I</span> <span m="1892210">refine</span> <span m="1893010">everything</span>
  <span m="1893580">all</span> <span m="1893710">at</span> <span m="1893880">once.</span></p><p><span
  m="1895764">AUDIENCE:</span> <span m="1896013">OK,</span> <span m="1896262">so it's
  like</span> <span m="1896760">if you do</span> <span m="1897258">have</span> <span
  m="1897756">overlap between</span> <span m="1898260">two witnessing sets,</span>
  <span m="1898500">that's</span> <span m="1898926">OK?</span></p><p><span m="1899780">YUFEI
  ZHAO:</span> <span m="1899870">That</span> <span m="1899960">is</span> <span m="1900140">OK,</span>
  <span m="1900620">because</span> <span m="1900950">this</span> <span m="1901100">step</span>
  <span m="1901400">doesn't</span> <span m="1901670">care.</span> <span m="1902900">If</span>
  <span m="1903020">you</span> <span m="1903110">have</span> <span m="1903230">two</span>
  <span m="1903590">witnessing</span> <span m="1904180">sets</span> <span m="1904350">that</span>
  <span m="1904460">overlap,</span> <span m="1905180">that</span> <span m="1905360">is</span>
  <span m="1905510">OK.</span> <span m="1908280">We'll</span> <span m="1908460">see</span>
  <span m="1908640">the</span> <span m="1908730">proof.</span> <span m="1909210">Yes.</span></p><p><span
  m="1909815">AUDIENCE:</span> <span m="1909953">Do</span> <span m="1910091">you</span>
  <span m="1910230">just</span> <span m="1910400">find</span> <span m="1910610">one</span>
  <span m="1910840">pair</span> <span m="1911160">of</span> <span m="1911490">witnessing</span>
  <span m="1911820">sets</span> <span m="1912278">for each</span> <span m="1912736">Vi,</span>
  <span m="1913194">Vj,</span> <span m="1913652">even though there</span> <span m="1914110">might
  be</span> <span m="1914568">more?</span></p><p><span m="1915030">YUFEI ZHAO:</span>
  <span m="1915210">Question is,</span> <span m="1915390">do</span> <span m="1915480">we</span>
  <span m="1915600">find</span> <span m="1916110">just</span> <span m="1916380">one</span>
  <span m="1916590">pair</span> <span m="1916800">of</span> <span m="1917490">witnessing</span>
  <span m="1917970">sets</span> <span m="1918270">even</span> <span m="1918480">though</span>
  <span m="1918600">there</span> <span m="1918750">could</span> <span m="1918900">be</span>
  <span m="1919020">more?</span> <span m="1919360">And</span> <span m="1919380">the</span>
  <span m="1919470">answer</span> <span m="1919700">is,</span> <span m="1919830">yes.</span>
  <span m="1920100">We</span> <span m="1920250">just</span> <span m="1920430">need</span>
  <span m="1920580">to</span> <span m="1920670">find</span> <span m="1920910">one.</span>
  <span m="1921360">There</span> <span m="1921480">could</span> <span m="1921660">be</span>
  <span m="1921780">lots.</span> <span m="1922430">So</span> <span m="1922930">if</span>
  <span m="1923100">it's</span> <span m="1923280">not</span> <span m="1923640">epsilon</span>
  <span m="1924030">regular,</span> <span m="1924510">it</span> <span m="1924600">might</span>
  <span m="1924750">be</span> <span m="1924870">very</span> <span m="1926260">not</span>
  <span m="1926590">epsilon</span> <span m="1926950">regular.</span></p><p><span m="1927600">And</span>
  <span m="1927730">in</span> <span m="1927790">fact,</span> <span m="1928210">being</span>
  <span m="1929020">a</span> <span m="1929080">witnessing</span> <span m="1929470">set</span>
  <span m="1929770">is</span> <span m="1929890">a</span> <span m="1929950">fairly</span>
  <span m="1930250">robust</span> <span m="1930970">notion.</span> <span m="1931450">If</span>
  <span m="1931570">you</span> <span m="1931720">just</span> <span m="1931900">take</span>
  <span m="1932140">out</span> <span m="1932260">a</span> <span m="1932290">small</span>
  <span m="1932620">number</span> <span m="1932890">of</span> <span m="1932950">vertices,</span>
  <span m="1933700">it's</span> <span m="1933760">still</span> <span m="1934090">a</span>
  <span m="1934810">witnessing</span> <span m="1935290">set.</span> <span m="1937206">Any</span>
  <span m="1937630">more</span> <span m="1937960">questions?</span> <span m="1940220">Great.</span>
  <span m="1940660">So</span> <span m="1940780">let's</span> <span m="1940960">take</span>
  <span m="1941110">a</span> <span m="1941170">quick</span> <span m="1941350">break</span>
  <span m="1941830">and</span> <span m="1941920">then</span> <span m="1942040">we'll</span>
  <span m="1942190">see</span> <span m="1942340">the</span> <span m="1942430">proof.</span></p><p><span
  m="1945090">Let's</span> <span m="1945270">get</span> <span m="1945420">started</span>
  <span m="1945840">with</span> <span m="1946110">the</span> <span m="1946290">proof</span>
  <span m="1946770">of</span> <span m="1946990">Szemeredi's</span> <span m="1947540">regularity</span>
  <span m="1948260">lemma.</span> <span m="1949050">And</span> <span m="1949230">to</span>
  <span m="1949380">do</span> <span m="1949500">the</span> <span m="1949590">proof,</span>
  <span m="1949860">I</span> <span m="1950120">want</span> <span m="1950370">to</span>
  <span m="1951000">develop</span> <span m="1951420">this</span> <span m="1951600">notion</span>
  <span m="1951990">of</span> <span m="1952320">energy</span> <span m="1952950">which</span>
  <span m="1953210">you</span> <span m="1953310">saw</span> <span m="1953610">in</span>
  <span m="1953730">the</span> <span m="1953790">proof</span> <span m="1954050">sketch.</span>
  <span m="1957290">So</span> <span m="1957340">what</span> <span m="1957460">do</span>
  <span m="1957550">I</span> <span m="1957610">mean</span> <span m="1957760">by</span>
  <span m="1957910">&quot;energy?&quot;</span></p><p><span m="1959830">First,</span>
  <span m="1960640">if</span> <span m="1960820">I--</span> <span m="1962860">let</span>
  <span m="1963020">me</span> <span m="1963210">define</span> <span m="1963640">some</span>
  <span m="1963880">quantities.</span> <span m="1966640">If</span> <span m="1966790">I</span>
  <span m="1966880">have</span> <span m="1967150">two</span> <span m="1967750">vertex</span>
  <span m="1968770">subsets,</span> <span m="1970390">U</span> <span m="1970810">and</span>
  <span m="1970990">W,</span> <span m="1973870">let</span> <span m="1973990">me</span>
  <span m="1974080">define</span> <span m="1974470">this</span> <span m="1974650">quantity,</span>
  <span m="1975090">q,</span> <span m="1978300">which</span> <span m="1979760">is</span>
  <span m="1980210">basically</span> <span m="1980810">the</span> <span m="1981320">edge</span>
  <span m="1981620">density</span> <span m="1984070">squared.</span> <span m="1985470">But</span>
  <span m="1985520">I</span> <span m="1985610">normalize</span> <span m="1986240">it</span>
  <span m="1986870">somewhat</span> <span m="1988130">according</span> <span m="1988580">to</span>
  <span m="1988910">how</span> <span m="1989420">big</span> <span m="1990050">U</span>
  <span m="1990380">and</span> <span m="1990530">W</span> <span m="1990920">are.</span></p><p><span
  m="1994560">I'm</span> <span m="1994710">going</span> <span m="1995010">to</span>
  <span m="1995940">use</span> <span m="1996420">the</span> <span m="1996540">letter</span>
  <span m="1996900">and</span> <span m="1997250">N</span> <span m="1997550">to</span>
  <span m="1997710">denote</span> <span m="1998180">the</span> <span m="1999090">number</span>
  <span m="1999360">of</span> <span m="1999420">vertices</span> <span m="2000140">in</span>
  <span m="2000320">G.</span> <span m="2003250">So</span> <span m="2003400">this</span>
  <span m="2003580">is</span> <span m="2004300">some</span> <span m="2004780">cube.</span>
  <span m="2006880">And</span> <span m="2007180">for</span> <span m="2009190">partitions,</span>
  <span m="2013200">if</span> <span m="2013320">I</span> <span m="2013410">have</span>
  <span m="2013770">a</span> <span m="2013830">pair</span> <span m="2014190">of</span>
  <span m="2014280">partitions,</span> <span m="2016980">Pu</span> <span m="2019350">of</span>
  <span m="2019570">U</span> <span m="2020320">into</span> <span m="2022540">k</span>
  <span m="2022870">parts,</span> <span m="2024910">and</span> <span m="2025100">the</span>
  <span m="2025180">partition</span> <span m="2026490">Pw</span> <span m="2028598">of</span>
  <span m="2029060">W</span> <span m="2029990">into</span> <span m="2032710">l</span>
  <span m="2033010">parts,</span> <span m="2036230">I</span> <span m="2036350">set</span>
  <span m="2036920">this</span> <span m="2037190">q</span> <span m="2038630">of</span>
  <span m="2039170">Pu</span> <span m="2040940">and</span> <span m="2041090">Pw</span>
  <span m="2043040">to</span> <span m="2043160">be</span> <span m="2043280">the</span>
  <span m="2043340">quantity</span> <span m="2044480">where</span> <span m="2045230">I</span>
  <span m="2045380">sum</span> <span m="2046940">over</span> <span m="2054770">basically</span>
  <span m="2055280">all</span> <span m="2055489">pairs,</span> <span m="2056030">one</span>
  <span m="2057260">part</span> <span m="2057590">from</span> <span m="2057920">U,</span>
  <span m="2058370">one</span> <span m="2058670">part</span> <span m="2059150">from</span>
  <span m="2059510">W</span> <span m="2060746">of</span> <span m="2061159">this</span>
  <span m="2061340">q</span> <span m="2062090">between</span> <span m="2065969">Ui</span>
  <span m="2066750">and</span> <span m="2067139">Wj.</span></p><p><span m="2070150">So</span>
  <span m="2070300">this</span> <span m="2070480">is</span> <span m="2070600">the</span>
  <span m="2070719">density</span> <span m="2071199">squared.</span> <span m="2072010">And</span>
  <span m="2072520">I'm</span> <span m="2072699">taking</span> <span m="2073570">some</span>
  <span m="2073870">kind</span> <span m="2074260">of</span> <span m="2074560">weighted</span>
  <span m="2075040">average</span> <span m="2075909">of</span> <span m="2076090">the</span>
  <span m="2077020">squared</span> <span m="2077590">density.</span> <span m="2079280">So</span>
  <span m="2079420">here</span> <span m="2079900">is</span> <span m="2080060">a</span>
  <span m="2080110">weighted</span> <span m="2080440">average.</span> <span m="2081370">If</span>
  <span m="2081550">you</span> <span m="2082270">prefer</span> <span m="2082600">to</span>
  <span m="2082719">think</span> <span m="2082929">about</span> <span m="2083190">the</span>
  <span m="2083260">special</span> <span m="2083650">case</span> <span m="2084280">where</span>
  <span m="2085270">this</span> <span m="2085480">partition</span> <span m="2085960">is</span>
  <span m="2086100">an</span> <span m="2086230">equipartition,</span> <span m="2087310">then</span>
  <span m="2087550">it</span> <span m="2087670">is</span> <span m="2087790">really</span>
  <span m="2088060">the</span> <span m="2088810">average</span> <span m="2089800">of</span>
  <span m="2090070">these</span> <span m="2090219">squared</span> <span m="2090790">densities.</span>
  <span m="2091750">It's</span> <span m="2091920">a</span> <span m="2091989">mean</span>
  <span m="2092230">square</span> <span m="2092620">density.</span></p><p><span m="2095860">And</span>
  <span m="2096050">finally,</span> <span m="2097470">for</span> <span m="2097770">a</span>
  <span m="2097890">partition</span> <span m="2100870">P</span> <span m="2102190">of</span>
  <span m="2102960">the</span> <span m="2103070">vertex</span> <span m="2103540">set</span>
  <span m="2104020">of</span> <span m="2104380">G</span> <span m="2107450">into</span>
  <span m="2111210">m</span> <span m="2111420">parts,</span> <span m="2112940">we</span>
  <span m="2113090">define</span> <span m="2114480">this</span> <span m="2114610">q</span>
  <span m="2116150">of</span> <span m="2116300">this</span> <span m="2116450">partition</span>
  <span m="2116990">P</span> <span m="2118560">to</span> <span m="2118680">be</span>
  <span m="2120900">q</span> <span m="2121380">of</span> <span m="2121860">P</span>
  <span m="2122340">with</span> <span m="2122540">itself</span> <span m="2123060">according</span>
  <span m="2123480">to</span> <span m="2123600">the</span> <span m="2123930">previous</span>
  <span m="2124620">definition.</span> <span m="2125730">Or</span> <span m="2125940">in</span>
  <span m="2126090">other</span> <span m="2126300">words,</span> <span m="2128370">I</span>
  <span m="2128490">do</span> <span m="2128640">this</span> <span m="2129090">double</span>
  <span m="2129390">sum,</span> <span m="2130560">i</span> <span m="2130890">from</span>
  <span m="2131220">1</span> <span m="2131460">to</span> <span m="2131640">m,</span>
  <span m="2132000">j</span> <span m="2132870">from</span> <span m="2133140">1</span>
  <span m="2133350">to</span> <span m="2133500">m,</span> <span m="2134658">q</span>
  <span m="2135900">of</span> <span m="2136500">Vi,</span> <span m="2137010">Vj.</span>
  <span m="2140550">And</span> <span m="2140710">this</span> <span m="2140890">is</span>
  <span m="2141010">the</span> <span m="2141070">quantity</span> <span m="2141880">that</span>
  <span m="2142000">I</span> <span m="2142120">will</span> <span m="2142300">call</span>
  <span m="2142660">the</span> <span m="2143050">&quot;energy&quot;</span> <span m="2151100">of</span>
  <span m="2151220">the</span> <span m="2151280">partition.</span></p><p><span m="2153300">It</span>
  <span m="2153420">is</span> <span m="2153960">a</span> <span m="2154050">mean</span>
  <span m="2154320">squared</span> <span m="2154830">density,</span> <span m="2155570">some</span>
  <span m="2155850">weighted</span> <span m="2156270">mean</span> <span m="2161440">of</span>
  <span m="2162790">the</span> <span m="2163300">edge</span> <span m="2163540">densities</span>
  <span m="2164050">between</span> <span m="2164860">pairs</span> <span m="2165220">of</span>
  <span m="2165280">parts</span> <span m="2165910">in</span> <span m="2166030">the</span>
  <span m="2166120">partition.</span> <span m="2169970">You</span> <span m="2170060">might</span>
  <span m="2170180">ask,</span> <span m="2170390">why</span> <span m="2170600">is</span>
  <span m="2170690">it</span> <span m="2170730">called</span> <span m="2170870">an</span>
  <span m="2170990">energy?</span> <span m="2172800">So</span> <span m="2173210">you</span>
  <span m="2173300">might</span> <span m="2173510">see</span> <span m="2173780">from</span>
  <span m="2174260">this</span> <span m="2174470">formula</span> <span m="2174830">here,</span>
  <span m="2175370">it's</span> <span m="2176846">some</span> <span m="2177260">kind</span>
  <span m="2177500">of</span> <span m="2177560">a</span> <span m="2178040">mean</span>
  <span m="2178310">square</span> <span m="2178760">density,</span> <span m="2179250">so</span>
  <span m="2179390">it's</span> <span m="2179510">some</span> <span m="2179690">kind</span>
  <span m="2179900">of</span> <span m="2180020">an</span> <span m="2181070">average</span>
  <span m="2181700">of</span> <span m="2182060">squares.</span></p><p><span m="2182600">So</span>
  <span m="2182810">in</span> <span m="2182900">particular,</span> <span m="2183710">it's</span>
  <span m="2183860">some</span> <span m="2184190">kind</span> <span m="2184520">of</span>
  <span m="2184640">an</span> <span m="2184750">L2</span> <span m="2185360">quantity.</span>
  <span m="2187640">And</span> <span m="2188030">there's</span> <span m="2188270">a</span>
  <span m="2188330">general</span> <span m="2190340">phenomenon</span> <span m="2190850">in</span>
  <span m="2190910">mathematics,</span> <span m="2191900">I</span> <span m="2191960">think</span>
  <span m="2192110">borrowed</span> <span m="2192800">from</span> <span m="2193640">physical</span>
  <span m="2194210">intuitions,</span> <span m="2195110">that</span> <span m="2196010">you</span>
  <span m="2196100">can</span> <span m="2196250">pretty</span> <span m="2196490">much</span>
  <span m="2196670">call</span> <span m="2196910">anything</span> <span m="2197240">that's</span>
  <span m="2197390">an</span> <span m="2197510">L2</span> <span m="2197960">quantity</span>
  <span m="2198620">an</span> <span m="2198770">energy.</span> <span m="2200900">And</span>
  <span m="2201000">so</span> <span m="2201030">that's,</span> <span m="2202260">I</span>
  <span m="2202350">think,</span> <span m="2202560">where</span> <span m="2202710">the</span>
  <span m="2202800">name</span> <span m="2203010">comes</span> <span m="2203310">from.</span></p><p><span
  m="2206260">So</span> <span m="2206310">this</span> <span m="2206490">is</span>
  <span m="2206550">the</span> <span m="2206640">important</span> <span m="2207060">object</span>
  <span m="2207450">for</span> <span m="2207630">our</span> <span m="2207780">proof.</span>
  <span m="2208920">And</span> <span m="2209130">let's</span> <span m="2209340">see</span>
  <span m="2209520">how</span> <span m="2209820">to</span> <span m="2211020">execute</span>
  <span m="2211490">a</span> <span m="2211530">strategy,</span> <span m="2212100">the</span>
  <span m="2212250">energy</span> <span m="2212640">increment</span> <span m="2213090">argument</span>
  <span m="2213810">outlined</span> <span m="2214350">on</span> <span m="2214440">the</span>
  <span m="2214530">board</span> <span m="2214860">over</span> <span m="2215070">there.</span>
  <span m="2216410">So</span> <span m="2216530">we</span> <span m="2216680">want</span>
  <span m="2216890">to</span> <span m="2216980">show</span> <span m="2217790">that</span>
  <span m="2218510">you</span> <span m="2218660">can</span> <span m="2219350">refine</span>
  <span m="2220070">a</span> <span m="2220190">partition</span> <span m="2220880">that</span>
  <span m="2221060">is</span> <span m="2221210">not</span> <span m="2221480">epsilon</span>
  <span m="2221900">regular</span> <span m="2223730">in</span> <span m="2223910">such</span>
  <span m="2224120">a</span> <span m="2224150">way</span> <span m="2224390">that</span>
  <span m="2224570">the</span> <span m="2224690">energy</span> <span m="2225620">goes</span>
  <span m="2225920">up.</span></p><p><span m="2228690">And</span> <span m="2228840">to</span>
  <span m="2228930">do</span> <span m="2229080">that,</span> <span m="2229380">let</span>
  <span m="2229560">me</span> <span m="2229920">state</span> <span m="2230280">a</span>
  <span m="2230340">few</span> <span m="2230970">lemmas</span> <span m="2231450">regarding</span>
  <span m="2231960">the</span> <span m="2232080">energy</span> <span m="2232920">of</span>
  <span m="2233040">a</span> <span m="2233100">partition</span> <span m="2233940">under</span>
  <span m="2234210">refinement.</span> <span m="2244230">And</span> <span m="2244400">the</span>
  <span m="2244460">point</span> <span m="2244790">of</span> <span m="2245180">the</span>
  <span m="2245270">next</span> <span m="2245510">several</span> <span m="2245750">lemmas</span>
  <span m="2246560">is</span> <span m="2246740">that</span> <span m="2247520">the</span>
  <span m="2247670">energy</span> <span m="2251700">never</span> <span m="2253320">decreases</span>
  <span m="2256460">under</span> <span m="2258080">refinement,</span> <span m="2262170">and</span>
  <span m="2262425">it</span> <span m="2262680">sometimes</span> <span m="2263220">increases</span>
  <span m="2264300">if</span> <span m="2264510">your</span> <span m="2267210">partition</span>
  <span m="2267660">is</span> <span m="2267780">not</span> <span m="2268020">epsilon</span>
  <span m="2268440">regular.</span> <span m="2271460">So</span> <span m="2271570">the</span>
  <span m="2271650">first</span> <span m="2271920">lemma</span> <span m="2272880">is</span>
  <span m="2273030">that</span> <span m="2274020">if</span> <span m="2274170">you</span>
  <span m="2274380">look</span> <span m="2274680">at</span> <span m="2275130">the</span>
  <span m="2276000">energy</span> <span m="2278150">between</span> <span m="2279050">a</span>
  <span m="2279110">pair</span> <span m="2279650">of</span> <span m="2281150">partitions,</span>
  <span m="2283340">it</span> <span m="2283490">is</span> <span m="2283610">never</span>
  <span m="2285230">less</span> <span m="2286130">than</span> <span m="2286910">the</span>
  <span m="2287030">energy</span> <span m="2287480">between</span> <span m="2288920">the</span>
  <span m="2289010">two</span> <span m="2289670">vertex</span> <span m="2290030">sets.</span></p><p><span
  m="2291730">So</span> <span m="2291910">for</span> <span m="2292060">instance,</span>
  <span m="2293270">if</span> <span m="2293350">you</span> <span m="2299950">have</span>
  <span m="2300340">U</span> <span m="2300560">and</span> <span m="2300650">W</span>
  <span m="2301040">like</span> <span m="2301250">that,</span> <span m="2302540">and</span>
  <span m="2304706">I</span> <span m="2305120">partition</span> <span m="2305690">them</span>
  <span m="2305990">into</span> <span m="2306410">Pu</span> <span m="2307490">and</span>
  <span m="2307650">Pw,</span> <span m="2308380">and</span> <span m="2308540">I</span>
  <span m="2308600">measure</span> <span m="2308900">the</span> <span m="2309050">energy,</span>
  <span m="2309800">just</span> <span m="2310520">basically</span> <span m="2311000">the</span>
  <span m="2311570">squared</span> <span m="2312710">density</span> <span m="2313190">between</span>
  <span m="2313580">U</span> <span m="2313730">and</span> <span m="2313850">V</span>
  <span m="2314300">versus</span> <span m="2315020">summing</span> <span m="2315500">up</span>
  <span m="2315620">the</span> <span m="2315740">individual</span> <span m="2316310">squared</span>
  <span m="2316670">densities</span> <span m="2317450">after</span> <span m="2317720">the</span>
  <span m="2317810">partition,</span> <span m="2318710">the</span> <span m="2318800">left</span>
  <span m="2319070">side</span> <span m="2319400">is</span> <span m="2319580">always</span>
  <span m="2319880">at</span> <span m="2319940">least</span> <span m="2320170">as</span>
  <span m="2320390">great as</span> <span m="2320660">the</span> <span m="2320750">right</span>
  <span m="2320960">side.</span> <span m="2325110">So</span> <span m="2325130">this</span>
  <span m="2325310">is</span> <span m="2325520">really</span> <span m="2326540">a</span>
  <span m="2326630">claim.</span> <span m="2327080">It's</span> <span m="2327200">a</span>
  <span m="2327260">fairly</span> <span m="2327500">simple</span> <span m="2327860">claim</span>
  <span m="2328130">about</span> <span m="2328340">convexity,</span> <span m="2329990">but</span>
  <span m="2330140">let</span> <span m="2330260">me</span> <span m="2330380">set</span>
  <span m="2330650">it</span> <span m="2330710">up</span> <span m="2330860">in</span>
  <span m="2330950">a</span> <span m="2330980">way</span> <span m="2331220">that</span>
  <span m="2331400">will</span> <span m="2331550">help</span> <span m="2332150">some</span>
  <span m="2332390">of</span> <span m="2332450">the</span> <span m="2332540">later</span>
  <span m="2332840">proofs.</span></p><p><span m="2334440">So</span> <span m="2334580">let</span>
  <span m="2334700">me</span> <span m="2334820">define</span> <span m="2335810">a</span>
  <span m="2335900">random</span> <span m="2336320">variable,</span> <span m="2340750">which</span>
  <span m="2340900">I</span> <span m="2341020">call</span> <span m="2341260">Z,</span>
  <span m="2341920">in</span> <span m="2342040">the</span> <span m="2342100">following</span>
  <span m="2342520">way.</span> <span m="2342800">So</span> <span m="2342850">here's</span>
  <span m="2343120">a</span> <span m="2343180">process</span> <span m="2343690">that</span>
  <span m="2343850">I</span> <span m="2343870">will</span> <span m="2343990">use</span>
  <span m="2344230">to</span> <span m="2344320">define</span> <span m="2344740">this</span>
  <span m="2344920">random</span> <span m="2345250">variable.</span> <span m="2346510">I</span>
  <span m="2346600">will</span> <span m="2346750">select</span> <span m="2348070">x,</span>
  <span m="2349000">little</span> <span m="2349240">x,</span> <span m="2349720">to</span>
  <span m="2349870">be</span> <span m="2350230">a</span> <span m="2350320">vertex</span>
  <span m="2351340">uniformly</span> <span m="2351940">chosen</span> <span m="2352540">from</span>
  <span m="2353290">U,</span> <span m="2354840">from</span> <span m="2354990">the</span>
  <span m="2355080">left</span> <span m="2355530">vertex</span> <span m="2355890">set.</span>
  <span m="2356160">And</span> <span m="2356560">I</span> <span m="2356890">will</span>
  <span m="2357030">select</span> <span m="2357540">a</span> <span m="2357660">vertex</span>
  <span m="2359620">y</span> <span m="2360250">uniformly</span> <span m="2360850">chosen</span>
  <span m="2361600">from</span> <span m="2362680">W.</span></p><p><span m="2367670">x</span>
  <span m="2368030">and</span> <span m="2368210">y,</span> <span m="2368660">they</span>
  <span m="2368900">fall</span> <span m="2369410">into</span> <span m="2372590">some</span>
  <span m="2372920">part</span> <span m="2373370">in</span> <span m="2373460">the</span>
  <span m="2373550">partition.</span> <span m="2374540">So</span> <span m="2374750">suppose</span>
  <span m="2377040">Ui</span> <span m="2378130">is</span> <span m="2378280">the</span>
  <span m="2378370">part</span> <span m="2379210">where</span> <span m="2380170">x</span>
  <span m="2380380">i</span> <span m="2382630">falls,</span> <span m="2385050">and</span>
  <span m="2385500">Wi</span> <span m="2387570">is</span> <span m="2387750">the</span>
  <span m="2388430">set</span> <span m="2388770">in</span> <span m="2388860">the</span>
  <span m="2388950">partition</span> <span m="2389550">where</span> <span m="2391230">y</span>
  <span m="2391530">falls.</span> <span m="2392450">So</span> <span m="2392590">Ui</span>
  <span m="2393180">is</span> <span m="2394110">a</span> <span m="2394170">member</span>
  <span m="2394530">of</span> <span m="2394650">this</span> <span m="2394830">partition.</span>
  <span m="2395840">Wi</span> <span m="2396460">is</span> <span m="2396510">a</span>
  <span m="2396540">member</span> <span m="2396870">of</span> <span m="2396990">the</span>
  <span m="2397140">other</span> <span m="2397380">partition</span> <span m="2397890">of</span>
  <span m="2398560">W.</span> <span m="2400500">Then</span> <span m="2400890">I</span>
  <span m="2401040">define</span> <span m="2401520">my</span> <span m="2401670">random</span>
  <span m="2402000">variable</span> <span m="2402450">Z</span> <span m="2403980">to</span>
  <span m="2404130">be</span> <span m="2405210">the</span> <span m="2405930">x</span>
  <span m="2406170">density</span> <span m="2407070">between</span> <span m="2407790">Ui</span>
  <span m="2409410">and</span> <span m="2409590">Wj.</span> <span m="2411870">So</span>
  <span m="2412020">it's</span> <span m="2412170">Wj.</span></p><p><span m="2417030">So</span>
  <span m="2417150">that's</span> <span m="2417390">the</span> <span m="2417480">definition.</span>
  <span m="2419170">So</span> <span m="2419520">pick</span> <span m="2419940">x</span>
  <span m="2420840">randomly.</span> <span m="2421500">Pick</span> <span m="2421770">y</span>
  <span m="2422100">randomly.</span> <span m="2422850">Suppose</span> <span m="2423420">x</span>
  <span m="2423810">falls</span> <span m="2424065">in</span> <span m="2424320">Ui.</span>
  <span m="2425010">Suppose</span> <span m="2425490">y</span> <span m="2425820">falls</span>
  <span m="2426180">in</span> <span m="2426300">Uj.</span> <span m="2427140">Then</span>
  <span m="2427770">Z</span> <span m="2428370">is</span> <span m="2428550">the</span>
  <span m="2429030">x</span> <span m="2429270">density</span> <span m="2430140">between</span>
  <span m="2430890">these</span> <span m="2431100">two</span> <span m="2431250">parts.</span></p><p><span
  m="2434170">So</span> <span m="2434380">Z</span> <span m="2434590">is</span> <span
  m="2434710">some</span> <span m="2434980">random</span> <span m="2435310">variable.</span>
  <span m="2437120">Let's</span> <span m="2437140">look</span> <span m="2437320">at</span>
  <span m="2437380">properties</span> <span m="2437980">of</span> <span m="2438130">this</span>
  <span m="2438550">random</span> <span m="2438850">variable.</span> <span m="2441700">First,</span>
  <span m="2442630">what</span> <span m="2442840">is</span> <span m="2442980">this,</span>
  <span m="2443190">it's</span> <span m="2443380">expectation?</span> <span m="2446190">It's</span>
  <span m="2446290">a</span> <span m="2446410">discrete</span> <span m="2446680">random</span>
  <span m="2446830">variable.</span></p><p><span m="2447280">And</span> <span m="2447370">you</span>
  <span m="2447460">can</span> <span m="2447580">easily</span> <span m="2447910">compute</span>
  <span m="2448300">all</span> <span m="2448420">of</span> <span m="2448510">these</span>
  <span m="2448690">quantities</span> <span m="2449170">by</span> <span m="2449350">just</span>
  <span m="2449500">summing</span> <span m="2449890">up</span> <span m="2451060">according</span>
  <span m="2451480">to</span> <span m="2451750">how</span> <span m="2452890">Z</span>
  <span m="2453130">is</span> <span m="2453280">generated.</span> <span m="2454670">So</span>
  <span m="2454870">I</span> <span m="2455470">look</span> <span m="2455710">overall,</span>
  <span m="2456490">i</span> <span m="2456670">and</span> <span m="2456810">j.</span>
  <span m="2457540">What's</span> <span m="2457780">the</span> <span m="2457840">probability</span>
  <span m="2458710">that</span> <span m="2459700">x</span> <span m="2460090">falls</span>
  <span m="2460500">in</span> <span m="2460730">Ui?</span> <span m="2461430">It</span>
  <span m="2461780">is</span> <span m="2462070">the</span> <span m="2462160">size</span>
  <span m="2462520">of</span> <span m="2462720">Ui</span> <span m="2462970">as</span>
  <span m="2463120">a</span> <span m="2463180">fraction</span> <span m="2463720">of</span>
  <span m="2463900">U.</span></p><p><span m="2464680">What's</span> <span m="2464860">the</span>
  <span m="2464950">probability</span> <span m="2465520">that</span> <span m="2465700">y</span>
  <span m="2466000">falls</span> <span m="2466350">in</span> <span m="2466450">Wj?</span>
  <span m="2467110">It's</span> <span m="2467290">the</span> <span m="2467380">size</span>
  <span m="2467800">of</span> <span m="2468040">Wj</span> <span m="2468820">as</span>
  <span m="2468940">a</span> <span m="2469000">fraction</span> <span m="2469480">of</span>
  <span m="2470200">size</span> <span m="2470560">W.</span> <span m="2473080">And</span>
  <span m="2473170">then</span> <span m="2474160">Z</span> <span m="2474470">is</span>
  <span m="2474700">this</span> <span m="2475450">quantity</span> <span m="2475870">here.</span>
  <span m="2477460">So</span> <span m="2477880">this</span> <span m="2478090">is</span>
  <span m="2478180">what</span> <span m="2478360">I</span> <span m="2478450">find</span>
  <span m="2479050">to</span> <span m="2479170">be</span> <span m="2480040">the</span>
  <span m="2480160">expectation</span> <span m="2481090">of</span> <span m="2481180">Z.</span></p><p><span
  m="2484390">But</span> <span m="2484550">you</span> <span m="2484640">see</span>
  <span m="2484880">the</span> <span m="2485120">density</span> <span m="2485870">multiplied</span>
  <span m="2486470">by</span> <span m="2486860">the</span> <span m="2487040">product</span>
  <span m="2487580">of</span> <span m="2487670">the</span> <span m="2487760">vertex</span>
  <span m="2488150">set</span> <span m="2488360">sizes,</span> <span m="2489110">that's</span>
  <span m="2489470">just</span> <span m="2489860">the</span> <span m="2489980">number</span>
  <span m="2490370">of</span> <span m="2490640">edges</span> <span m="2491090">between</span>
  <span m="2492080">U</span> <span m="2492410">and</span> <span m="2492590">W.</span>
  <span m="2495170">And</span> <span m="2495290">you</span> <span m="2495410">sum</span>
  <span m="2495740">over</span> <span m="2496100">all</span> <span m="2496460">the</span>
  <span m="2496730">i,</span> <span m="2497025">j's.</span> <span m="2498980">So</span>
  <span m="2502150">that,</span> <span m="2503750">which</span> <span m="2503990">is</span>
  <span m="2504860">simply</span> <span m="2505370">the</span> <span m="2505580">edge</span>
  <span m="2505880">density</span> <span m="2506480">between</span> <span m="2507230">U</span>
  <span m="2507500">and</span> <span m="2507620">W.</span> <span m="2510080">So</span>
  <span m="2510210">that's</span> <span m="2510450">the</span> <span m="2510540">expectation</span>
  <span m="2511290">of</span> <span m="2511380">the</span> <span m="2511470">Z</span>
  <span m="2511660">variable.</span></p><p><span m="2513570">On</span> <span m="2513690">the</span>
  <span m="2513780">other</span> <span m="2513930">hand,</span> <span m="2514600">what's</span>
  <span m="2514770">the</span> <span m="2514890">second</span> <span m="2515280">moment?</span>
  <span m="2516520">In</span> <span m="2516620">other</span> <span m="2516630">words,</span>
  <span m="2516970">what's</span> <span m="2517050">the</span> <span m="2517230">expectation</span>
  <span m="2517950">of</span> <span m="2518040">the</span> <span m="2518130">square</span>
  <span m="2519150">of</span> <span m="2519300">Z?</span> <span m="2521040">Again,</span>
  <span m="2521450">we</span> <span m="2521630">do</span> <span m="2521780">the</span>
  <span m="2521870">same</span> <span m="2522260">computation.</span> <span m="2525080">First</span>
  <span m="2525410">part</span> <span m="2525710">is</span> <span m="2525830">the</span>
  <span m="2525920">same.</span></p><p><span m="2531610">The</span> <span m="2531710">second</span>
  <span m="2531900">part</span> <span m="2532260">now</span> <span m="2532500">becomes</span>
  <span m="2533010">a</span> <span m="2533080">d</span> <span m="2533280">squared.</span>
  <span m="2539610">And</span> <span m="2542100">look</span> <span m="2542340">at</span>
  <span m="2543290">how</span> <span m="2543630">we</span> <span m="2543750">define</span>
  <span m="2544290">energy.</span> <span m="2547070">This</span> <span m="2547260">quantity</span>
  <span m="2547650">here</span> <span m="2548400">is</span> <span m="2549480">basically</span>
  <span m="2550560">the</span> <span m="2551850">energy</span> <span m="2552180">q</span>
  <span m="2552960">between</span> <span m="2553740">the</span> <span m="2553830">partition</span>
  <span m="2554310">U</span> <span m="2555330">and</span> <span m="2555420">the</span>
  <span m="2555480">partition</span> <span m="2555960">of</span> <span m="2556080">W,</span>
  <span m="2557460">except</span> <span m="2557820">there's</span> <span m="2559860">normalization.</span>
  <span m="2560630">That's</span> <span m="2560820">not</span> <span m="2561060">quite</span>
  <span m="2561390">the</span> <span m="2561480">same</span> <span m="2561750">as</span>
  <span m="2561870">the</span> <span m="2561930">one</span> <span m="2562110">we</span>
  <span m="2562230">used</span> <span m="2562410">before.</span> <span m="2563140">So</span>
  <span m="2563250">we</span> <span m="2563420">will</span> <span m="2563550">just</span>
  <span m="2563760">put</span> <span m="2564000">in</span> <span m="2564140">that</span>
  <span m="2564390">normalization.</span></p><p><span m="2574740">So</span> <span
  m="2574860">now</span> <span m="2575280">you</span> <span m="2575400">compare</span>
  <span m="2576720">the</span> <span m="2576810">expectation</span> <span m="2577440">of</span>
  <span m="2577530">Z</span> <span m="2578070">versus</span> <span m="2578430">the</span>
  <span m="2578520">expectation</span> <span m="2579090">of</span> <span m="2579180">Z</span>
  <span m="2579330">squared.</span> <span m="2581540">And</span> <span m="2582040">we</span>
  <span m="2582160">know</span> <span m="2583360">by</span> <span m="2583570">convexity</span>
  <span m="2585400">that</span> <span m="2586110">the</span> <span m="2586270">expectation</span>
  <span m="2587050">of</span> <span m="2587230">Z</span> <span m="2588220">squared</span>
  <span m="2589030">is</span> <span m="2589190">at</span> <span m="2589280">least</span>
  <span m="2589570">as</span> <span m="2589720">large</span> <span m="2591790">as</span>
  <span m="2592000">the</span> <span m="2592120">expectation</span> <span m="2592800">of</span>
  <span m="2592860">Z,</span> <span m="2593530">that</span> <span m="2593740">quantity</span>
  <span m="2594160">squared.</span> <span m="2597400">But</span> <span m="2597560">if</span>
  <span m="2597710">you</span> <span m="2598070">plug</span> <span m="2598460">in</span>
  <span m="2598820">what</span> <span m="2599030">values</span> <span m="2599540">you</span>
  <span m="2599660">get</span> <span m="2599990">for</span> <span m="2600830">these</span>
  <span m="2601010">two</span> <span m="2601160">guys,</span> <span m="2602710">you</span>
  <span m="2603940">derive</span> <span m="2606220">the</span> <span m="2607460">inequality</span>
  <span m="2608180">claimed</span> <span m="2608630">in</span> <span m="2608750">Lemma</span>
  <span m="2608970">1.</span> <span m="2612260">You</span> <span m="2612360">have</span>
  <span m="2612520">to</span> <span m="2612610">cancel</span> <span m="2613020">some</span>
  <span m="2613120">normalization</span> <span m="2613750">factors,</span> <span m="2614300">but</span>
  <span m="2614380">that's</span> <span m="2614590">easy</span> <span m="2614830">to</span>
  <span m="2614920">do.</span></p><p><span m="2617940">So</span> <span m="2618060">that's</span>
  <span m="2618240">the</span> <span m="2618330">first</span> <span m="2618570">lemma.</span>
  <span m="2623060">So</span> <span m="2623180">the</span> <span m="2623240">first</span>
  <span m="2623510">one</span> <span m="2623710">is</span> <span m="2623900">just</span>
  <span m="2624190">about</span> <span m="2624920">a</span> <span m="2624980">pair</span>
  <span m="2625460">of</span> <span m="2625790">parts,</span> <span m="2626230">and
  identify</span> <span m="2627050">partition,</span> <span m="2628580">each</span>
  <span m="2628940">part,</span> <span m="2629330">what</span> <span m="2629510">happens</span>
  <span m="2629870">to</span> <span m="2629990">the</span> <span m="2630080">energy</span>
  <span m="2630380">between</span> <span m="2630920">this</span> <span m="2631130">pair.</span>
  <span m="2632030">And</span> <span m="2632300">the</span> <span m="2632390">second</span>
  <span m="2632690">one</span> <span m="2632870">is</span> <span m="2632990">a</span>
  <span m="2633080">direct</span> <span m="2633500">corollary</span> <span m="2634100">of</span>
  <span m="2634190">the</span> <span m="2634250">first</span> <span m="2634550">one.</span></p><p><span
  m="2634820">It</span> <span m="2635200">says</span> <span m="2635480">that</span>
  <span m="2635660">if</span> <span m="2635990">you</span> <span m="2636140">have</span>
  <span m="2636350">a</span> <span m="2636860">second</span> <span m="2637220">partition,</span>
  <span m="2637760">P</span> <span m="2638000">prime</span> <span m="2639200">that</span>
  <span m="2639350">refines</span> <span m="2640910">P,</span> <span m="2643320">then</span>
  <span m="2644400">the</span> <span m="2646470">energy</span> <span m="2646980">of</span>
  <span m="2647130">the</span> <span m="2647250">second</span> <span m="2647610">partition,</span>
  <span m="2648660">the</span> <span m="2648750">refinement,</span> <span m="2649920">is</span>
  <span m="2650070">never</span> <span m="2650400">less</span> <span m="2650850">than</span>
  <span m="2651030">the</span> <span m="2651120">energy</span> <span m="2651510">of</span>
  <span m="2651600">the</span> <span m="2651660">first</span> <span m="2651960">partition.</span>
  <span m="2655570">And</span> <span m="2656020">it</span> <span m="2656140">is</span>
  <span m="2656260">a</span> <span m="2656320">direct</span> <span m="2656710">consequence</span>
  <span m="2657340">of</span> <span m="2657430">the</span> <span m="2657520">first</span>
  <span m="2658000">lemma,</span> <span m="2658660">because</span> <span m="2659140">we</span>
  <span m="2659800">simply</span> <span m="2660730">apply</span> <span m="2661150">this</span>
  <span m="2661310">lemma</span> <span m="2662680">to</span> <span m="2664660">every</span>
  <span m="2664960">pair</span> <span m="2671060">of</span> <span m="2671210">parts</span>
  <span m="2672790">in</span> <span m="2674096">P.</span> <span m="2678360">Between</span>
  <span m="2678690">every</span> <span m="2678900">pair</span> <span m="2679170">of</span>
  <span m="2679230">parts,</span> <span m="2679890">the</span> <span m="2680010">energy</span>
  <span m="2680520">can</span> <span m="2680670">never</span> <span m="2680910">go</span>
  <span m="2681060">down.</span> <span m="2681520">So</span> <span m="2681630">overall,</span>
  <span m="2682210">the</span> <span m="2682230">energy</span> <span m="2682920">does</span>
  <span m="2683100">not</span> <span m="2683280">go</span> <span m="2683430">down.</span></p><p><span
  m="2688150">And</span> <span m="2688270">finally,</span> <span m="2689710">so</span>
  <span m="2689890">far,</span> <span m="2690190">we've</span> <span m="2690370">just</span>
  <span m="2690580">said</span> <span m="2690850">that</span> <span m="2691120">the</span>
  <span m="2691270">partitions</span> <span m="2691990">can</span> <span m="2692170">never</span>
  <span m="2692860">make</span> <span m="2693130">the</span> <span m="2693250">energy</span>
  <span m="2693640">go</span> <span m="2693820">down.</span> <span m="2694550">But</span>
  <span m="2694810">in</span> <span m="2694960">order</span> <span m="2695230">to</span>
  <span m="2695410">do</span> <span m="2695590">this</span> <span m="2695770">proof,</span>
  <span m="2696070">we</span> <span m="2696190">need</span> <span m="2696310">to</span>
  <span m="2696400">show</span> <span m="2696580">that</span> <span m="2696700">the</span>
  <span m="2696790">energy</span> <span m="2697480">sometimes</span> <span m="2698140">goes</span>
  <span m="2698470">up.</span> <span m="2701250">And</span> <span m="2701370">that's</span>
  <span m="2701580">the</span> <span m="2701670">point</span> <span m="2701940">of</span>
  <span m="2702010">the</span> <span m="2702090">third</span> <span m="2702330">lemma.</span></p><p><span
  m="2702870">The</span> <span m="2702960">third</span> <span m="2703230">Lemma</span>
  <span m="2704600">tells</span> <span m="2704990">us</span> <span m="2705240">that</span>
  <span m="2705420">you</span> <span m="2705540">can</span> <span m="2705720">get</span>
  <span m="2707100">an</span> <span m="2707280">energy</span> <span m="2707670">boost.</span>
  <span m="2710400">So this</span> <span m="2710850">is the</span> <span m="2710970">Red</span>
  <span m="2711240">Bull</span> <span m="2711540">Lemma.</span> <span m="2712020">You</span>
  <span m="2712080">can</span> <span m="2712230">get</span> <span m="2712410">an</span>
  <span m="2712800">energy</span> <span m="2713190">boost</span> <span m="2714150">if</span>
  <span m="2714390">you</span> <span m="2714600">are</span> <span m="2715260">feeling</span>
  <span m="2716130">irregular.</span></p><p><span m="2720820">So</span> <span m="2721020">if</span>
  <span m="2722370">U,</span> <span m="2722580">W</span> <span m="2723480">is</span>
  <span m="2724320">not</span> <span m="2725670">epsilon</span> <span m="2726150">regular,</span>
  <span m="2728360">and</span> <span m="2728520">this</span> <span m="2728700">epsilon</span>
  <span m="2729090">regularity</span> <span m="2730200">is</span> <span m="2730680">witnessed</span>
  <span m="2733890">by</span> <span m="2735030">U1</span> <span m="2735660">in</span>
  <span m="2735810">U</span> <span m="2736320">and</span> <span m="2736470">W1</span>
  <span m="2737270">in</span> <span m="2737400">W,</span> <span m="2740370">then</span>
  <span m="2744860">I</span> <span m="2744980">claim</span> <span m="2746120">that</span>
  <span m="2747050">the</span> <span m="2747200">energy</span> <span m="2748070">obtained</span>
  <span m="2749150">by</span> <span m="2749810">chopping</span> <span m="2750380">U</span>
  <span m="2751070">into</span> <span m="2752070">U1</span> <span m="2753290">and</span>
  <span m="2753440">its</span> <span m="2753560">complement</span> <span m="2756920">against</span>
  <span m="2758060">W1,</span> <span m="2760260">against</span> <span m="2760640">the</span>
  <span m="2760710">complement</span> <span m="2761220">of</span> <span m="2761310">W1</span>
  <span m="2761740">and</span> <span m="2761830">W,</span> <span m="2764380">so</span>
  <span m="2764590">here</span> <span m="2766330">again</span> <span m="2766690">U</span>
  <span m="2766930">and</span> <span m="2767050">W,</span> <span m="2770260">I</span>
  <span m="2770390">find</span> <span m="2770800">a</span> <span m="2770870">witnessing</span>
  <span m="2771410">set</span> <span m="2771770">for</span> <span m="2772090">their</span>
  <span m="2772370">irregularity.</span> <span m="2775830">And</span> <span m="2775920">now</span>
  <span m="2776160">I</span> <span m="2776280">partition</span> <span m="2777180">left</span>
  <span m="2777420">and</span> <span m="2777510">right</span> <span m="2777720">according</span>
  <span m="2778140">to--</span> <span m="2778980">chop</span> <span m="2779490">each</span>
  <span m="2779760">part</span> <span m="2780060">into</span> <span m="2780270">two.</span>
  <span m="2782190">So</span> <span m="2782660">this</span> <span m="2783230">energy</span>
  <span m="2783560">between</span> <span m="2784640">this</span> <span m="2785360">partition</span>
  <span m="2785900">into</span> <span m="2786140">two</span> <span m="2786440">on</span>
  <span m="2786560">both</span> <span m="2786800">sides</span> <span m="2788450">is</span>
  <span m="2789200">bigger</span> <span m="2790010">than</span> <span m="2790700">the</span>
  <span m="2790940">original</span> <span m="2792830">energy</span> <span m="2793670">plus</span>
  <span m="2796480">something</span> <span m="2796930">where</span> <span m="2797200">we</span>
  <span m="2797350">can</span> <span m="2797530">gain.</span> <span m="2798280">And</span>
  <span m="2798400">this</span> <span m="2798700">something</span> <span m="2799030">where</span>
  <span m="2799210">we</span> <span m="2799360">can</span> <span m="2799510">gain</span>
  <span m="2801210">turns</span> <span m="2801480">out</span> <span m="2801660">to</span>
  <span m="2801780">be</span> <span m="2803680">at</span> <span m="2803770">least</span>
  <span m="2804640">epsilon</span> <span m="2805240">raised</span> <span m="2805510">to</span>
  <span m="2805630">the</span> <span m="2805720">power</span> <span m="2806050">4</span>
  <span m="2807160">times</span> <span m="2808030">the</span> <span m="2808420">size</span>
  <span m="2808780">of</span> <span m="2808870">U,</span> <span m="2809620">size</span>
  <span m="2809950">of</span> <span m="2810070">W,</span> <span m="2810780">divided</span>
  <span m="2811180">by</span> <span m="2811570">n</span> <span m="2811840">squared.</span></p><p><span
  m="2822860">Can</span> <span m="2823250">you</span> <span m="2823390">prove</span>
  <span m="2823610">it?</span> <span m="2828190">Let's</span> <span m="2828460">define</span>
  <span m="2831870">Z</span> <span m="2832900">the</span> <span m="2833200">same</span>
  <span m="2833530">as</span> <span m="2833710">in</span> <span m="2833800">the</span>
  <span m="2833890">previous</span> <span m="2834310">proof,</span> <span m="2835250">as</span>
  <span m="2835330">in</span> <span m="2836140">the</span> <span m="2836260">proof</span>
  <span m="2836920">of</span> <span m="2837040">Lemma</span> <span m="2837280">1.</span>
  <span m="2842180">In</span> <span m="2842310">Lemma</span> <span m="2842520">1,</span>
  <span m="2842790">we</span> <span m="2842910">just</span> <span m="2843210">used</span>
  <span m="2843480">the</span> <span m="2843570">fact</span> <span m="2843900">that</span>
  <span m="2844110">the</span> <span m="2845220">L2</span> <span m="2845520">norm</span>
  <span m="2845760">of</span> <span m="2845850">Z,</span> <span m="2846070">the</span>
  <span m="2847080">expectation</span> <span m="2847620">of</span> <span m="2847680">the</span>
  <span m="2847800">square,</span> <span m="2848550">is</span> <span m="2848700">at</span>
  <span m="2848790">least the</span> <span m="2849180">square</span> <span m="2849540">of</span>
  <span m="2849630">the</span> <span m="2849720">expectation.</span> <span m="2850710">But</span>
  <span m="2850890">actually,</span> <span m="2851130">there</span> <span m="2851340">are</span>
  <span m="2851370">differences</span> <span m="2851970">in</span> <span m="2852120">it.</span>
  <span m="2852360">It's</span> <span m="2852510">called</span> <span m="2852680">a</span>
  <span m="2852720">&quot;variance.&quot;</span></p><p><span m="2855108">The</span>
  <span m="2855540">variance</span> <span m="2856140">of</span> <span m="2856220">Z</span>
  <span m="2857340">is</span> <span m="2858210">the</span> <span m="2858300">difference</span>
  <span m="2858780">between</span> <span m="2860100">these</span> <span m="2860310">two</span>
  <span m="2860490">quantities.</span> <span m="2861340">I</span> <span m="2861870">know</span>
  <span m="2862080">that</span> <span m="2862290">it's</span> <span m="2863220">always</span>
  <span m="2863610">non-negative.</span> <span m="2867810">So</span> <span m="2868280">if</span>
  <span m="2868430">you</span> <span m="2868550">look</span> <span m="2868730">at</span>
  <span m="2869060">how</span> <span m="2869330">we</span> <span m="2869480">derived</span>
  <span m="2870080">the</span> <span m="2870290">expectation</span> <span m="2870890">of</span>
  <span m="2870950">Z and</span> <span m="2871280">expectation</span> <span m="2871580">of</span>
  <span m="2871880">Z</span> <span m="2872040">squared,</span> <span m="2872630">you</span>
  <span m="2872780">immediately</span> <span m="2873320">see</span> <span m="2873530">that</span>
  <span m="2873680">its</span> <span m="2873860">variance</span> <span m="2874670">we</span>
  <span m="2874820">can</span> <span m="2874970">write</span> <span m="2881080">as,</span>
  <span m="2882490">up</span> <span m="2882640">to</span> <span m="2882850">a</span>
  <span m="2883000">normalizing</span> <span m="2883600">factor,</span> <span m="2884800">the</span>
  <span m="2886690">difference</span> <span m="2887230">between</span> <span m="2889340">this</span>
  <span m="2889550">energy</span> <span m="2892580">on</span> <span m="2892680">one</span>
  <span m="2892890">hand</span> <span m="2894390">and</span> <span m="2894990">the</span>
  <span m="2895140">energy</span> <span m="2898230">between</span> <span m="2899100">U</span>
  <span m="2899430">and</span> <span m="2899580">W,</span> <span m="2900090">namely</span>
  <span m="2900420">the</span> <span m="2902250">mean</span> <span m="2902430">square</span>
  <span m="2902840">of</span> <span m="2902970">the</span> <span m="2903060">normalization.</span></p><p><span
  m="2906380">On</span> <span m="2906500">the</span> <span m="2906590">other</span>
  <span m="2906770">hand,</span> <span m="2909380">a</span> <span m="2909500">different</span>
  <span m="2909800">way</span> <span m="2909920">to</span> <span m="2910010">calculate</span>
  <span m="2910520">the</span> <span m="2910580">variance</span> <span m="2911810">is</span>
  <span m="2911990">that</span> <span m="2913280">it</span> <span m="2913400">is</span>
  <span m="2913520">equal</span> <span m="2913910">to</span> <span m="2914270">the</span>
  <span m="2914450">expectation</span> <span m="2915860">of</span> <span m="2916640">the</span>
  <span m="2916730">deviation</span> <span m="2918500">from</span> <span m="2918770">the</span>
  <span m="2918860">mean</span> <span m="2919700">squared.</span> <span m="2924310">So</span>
  <span m="2924410">let's</span> <span m="2924480">think</span> <span m="2924660">about</span>
  <span m="2924810">the</span> <span m="2924900">deviation</span> <span m="2925530">from</span>
  <span m="2925710">the</span> <span m="2925800">mean.</span> <span m="2927320">I</span>
  <span m="2927730">am</span> <span m="2927840">choosing</span> <span m="2928590">a</span>
  <span m="2929160">random</span> <span m="2929610">vector</span> <span m="2930570">in,</span>
  <span m="2932830">on</span> <span m="2932950">the</span> <span m="2933040">left,</span>
  <span m="2933370">U,</span> <span m="2933940">and</span> <span m="2934030">another</span>
  <span m="2934300">random</span> <span m="2935290">point,</span> <span m="2935800">random</span>
  <span m="2936100">vertex</span> <span m="2936490">on</span> <span m="2936580">the</span>
  <span m="2936640">left,</span> <span m="2937240">and</span> <span m="2937330">a</span>
  <span m="2937420">random</span> <span m="2938380">point</span> <span m="2938710">on</span>
  <span m="2938800">the</span> <span m="2938860">right.</span></p><p><span m="2940570">In</span>
  <span m="2940720">the</span> <span m="2940840">event</span> <span m="2941590">that</span>
  <span m="2941770">they</span> <span m="2941920">both</span> <span m="2942940">lie</span>
  <span m="2944290">in</span> <span m="2944740">the</span> <span m="2944860">sets</span>
  <span m="2945220">that</span> <span m="2945370">witness</span> <span m="2946030">the</span>
  <span m="2946200">irregularity,</span> <span m="2954020">so</span> <span m="2955020">in</span>
  <span m="2955150">the</span> <span m="2955240">event</span> <span m="2957110">where</span>
  <span m="2957740">x</span> <span m="2958010">falls</span> <span m="2958340">here</span>
  <span m="2958970">and</span> <span m="2959120">y</span> <span m="2959420">falls</span>
  <span m="2959750">here,</span> <span m="2961430">which</span> <span m="2961610">occurs</span>
  <span m="2962060">with</span> <span m="2962750">this</span> <span m="2962960">probability,</span>
  <span m="2964930">see</span> <span m="2965200">that</span> <span m="2965560">this</span>
  <span m="2965890">quantity</span> <span m="2966370">here</span> <span m="2968690">is</span>
  <span m="2969350">equal</span> <span m="2969800">to</span> <span m="2973250">the</span>
  <span m="2974300">density</span> <span m="2974990">between</span> <span m="2975920">U1</span>
  <span m="2976310">and</span> <span m="2976400">W1</span> <span m="2979430">minus</span>
  <span m="2979910">the</span> <span m="2980030">density--</span> <span m="2980730">and</span>
  <span m="2981650">this</span> <span m="2982670">expectation</span> <span m="2983270">of</span>
  <span m="2983360">Z</span> <span m="2984050">is</span> <span m="2984260">just</span>
  <span m="2984470">the</span> <span m="2984530">density</span> <span m="2984950">between</span>
  <span m="2985550">U</span> <span m="2985820">and</span> <span m="2985940">W.</span>
  <span m="2987950">So</span> <span m="2988520">interpreting</span> <span m="2989270">this</span>
  <span m="2989450">expectation</span> <span m="2990710">for</span> <span m="2992300">what</span>
  <span m="2992450">happens</span> <span m="2992840">when</span> <span m="2993470">x</span>
  <span m="2994070">falls</span> <span m="2994325">in</span> <span m="2994580">U1</span>
  <span m="2995750">and</span> <span m="2995900">when y</span> <span m="2996440">falls</span>
  <span m="2996830">in</span> <span m="2997010">W1,</span> <span m="2999370">ignoring</span>
  <span m="2999900">all</span> <span m="3000020">the</span> <span m="3000170">other</span>
  <span m="3001010">events,</span> <span m="3002210">because</span> <span m="3003080">the</span>
  <span m="3003170">quantity</span> <span m="3003620">is</span> <span m="3003770">always</span>
  <span m="3004070">non-negative</span> <span m="3004790">everywhere.</span></p><p><span
  m="3006230">But</span> <span m="3006380">now</span> <span m="3006890">from</span>
  <span m="3007250">the</span> <span m="3007340">definition</span> <span m="3010460">of</span>
  <span m="3010850">epsilon</span> <span m="3011420">regularity,</span> <span m="3014660">or</span>
  <span m="3014780">rather</span> <span m="3015110">the</span> <span m="3015770">witnessing</span>
  <span m="3016340">of</span> <span m="3016580">epsilon</span> <span m="3017120">irregularity,</span>
  <span m="3019010">you</span> <span m="3019100">see</span> <span m="3019340">that</span>
  <span m="3022160">this</span> <span m="3022520">U1</span> <span m="3022850">is</span>
  <span m="3023000">at</span> <span m="3023090">least</span> <span m="3023330">an</span>
  <span m="3023420">epsilon</span> <span m="3023810">fraction</span> <span m="3024320">of</span>
  <span m="3024440">U.</span> <span m="3025900">W1's</span> <span m="3026560">at</span>
  <span m="3026630">least an</span> <span m="3026890">epsilon</span> <span m="3027260">fraction</span>
  <span m="3027740">of</span> <span m="3028370">W.</span> <span m="3029800">And</span>
  <span m="3030550">this</span> <span m="3030790">final</span> <span m="3031150">quantity</span>
  <span m="3031600">here</span> <span m="3032770">is</span> <span m="3033190">at</span>
  <span m="3033280">least</span> <span m="3034000">epsilon</span> <span m="3034810">inside,</span>
  <span m="3035320">so</span> <span m="3035500">at</span> <span m="3035560">least</span>
  <span m="3035800">epsilon</span> <span m="3036220">squared.</span> <span m="3038600">So</span>
  <span m="3038650">here</span> <span m="3038830">we're</span> <span m="3038950">using</span>
  <span m="3039580">all</span> <span m="3039730">the</span> <span m="3039880">different</span>
  <span m="3040510">components</span> <span m="3041110">of</span> <span m="3041200">the</span>
  <span m="3041290">definition</span> <span m="3041860">of</span> <span m="3042220">epsilon</span>
  <span m="3042640">regular.</span> <span m="3043270">Yes.</span></p><p><span m="3044506">AUDIENCE:</span>
  <span m="3044755">What</span> <span m="3045004">happens</span> <span m="3045502">if
  we're</span> <span m="3046000">dividing</span> <span m="3047494">with</span> <span
  m="3047992">more</span> <span m="3048490">witnessing</span> <span m="3048988">sets?</span></p><p><span
  m="3051480">YUFEI ZHAO:</span> <span m="3051540">So</span> <span m="3051600">you're</span>
  <span m="3051690">asking</span> <span m="3051930">what</span> <span m="3052080">happens</span>
  <span m="3052530">if</span> <span m="3052650">we</span> <span m="3052740">divide</span>
  <span m="3053100">with</span> <span m="3053250">more</span> <span m="3053460">witnessing</span>
  <span m="3053940">sets?</span> <span m="3054150">So</span> <span m="3054720">hold</span>
  <span m="3054930">onto</span> <span m="3055140">that</span> <span m="3055320">thought.</span>
  <span m="3055650">So</span> <span m="3055810">right</span> <span m="3055950">now,</span>
  <span m="3056190">I'm</span> <span m="3056370">just</span> <span m="3057120">showing</span>
  <span m="3057450">what</span> <span m="3057600">happens</span> <span m="3058050">if</span>
  <span m="3058200">you</span> <span m="3058350">have</span> <span m="3058680">one</span>
  <span m="3058950">witnessing</span> <span m="3059410">set.</span> <span m="3062250">Any</span>
  <span m="3062570">more</span> <span m="3062790">questions?</span></p><p><span m="3064590">So</span>
  <span m="3064830">here</span> <span m="3065100">we</span> <span m="3065280">have</span>
  <span m="3066060">epsilon</span> <span m="3066420">to</span> <span m="3066510">the</span>
  <span m="3066600">4th.</span> <span m="3068070">And</span> <span m="3068400">if</span>
  <span m="3068550">you're</span> <span m="3068730">putting</span> <span m="3069150">the</span>
  <span m="3070080">normalization</span> <span m="3071010">comparing</span> <span
  m="3072650">these</span> <span m="3072830">two</span> <span m="3072980">interpretations,</span>
  <span m="3074180">you'll</span> <span m="3074300">find</span> <span m="3074850">the</span>
  <span m="3074960">inequality</span> <span m="3075560">claimed</span> <span m="3076010">by</span>
  <span m="3076190">the</span> <span m="3076290">lemma.</span> <span m="3083180">So</span>
  <span m="3083310">now</span> <span m="3083550">we</span> <span m="3083790">are</span>
  <span m="3084660">ready</span> <span m="3085020">to</span> <span m="3086190">show</span>
  <span m="3086730">the</span> <span m="3086880">key</span> <span m="3087180">part</span>
  <span m="3087540">of</span> <span m="3087660">this</span> <span m="3087870">iteration.</span></p><p><span
  m="3091080">I'll</span> <span m="3091340">show you</span> <span m="3091560">precisely</span>
  <span m="3092010">how</span> <span m="3092130">this</span> <span m="3092280">iteration</span>
  <span m="3092700">works,</span> <span m="3093320">and</span> <span m="3093480">show</span>
  <span m="3093720">that</span> <span m="3093840">you</span> <span m="3093990">always</span>
  <span m="3094410">get</span> <span m="3094770">an</span> <span m="3094920">energy</span>
  <span m="3095280">boost</span> <span m="3095700">in</span> <span m="3095820">the</span>
  <span m="3095940">overall</span> <span m="3096360">partition.</span> <span m="3099270">So</span>
  <span m="3099640">I'll</span> <span m="3099760">call</span> <span m="3100150">the</span>
  <span m="3100240">next</span> <span m="3100480">one</span> <span m="3100660">Lemma</span>
  <span m="3100910">4.</span> <span m="3103110">And</span> <span m="3103250">this</span>
  <span m="3103340">says</span> <span m="3103570">that</span> <span m="3103900">if</span>
  <span m="3106120">you</span> <span m="3106210">have</span> <span m="3106310">a</span>
  <span m="3106360">partition</span> <span m="3108690">P</span> <span m="3110866">of</span>
  <span m="3111340">the</span> <span m="3111750">vertex</span> <span m="3112140">set</span>
  <span m="3112350">of</span> <span m="3112440">G</span> <span m="3113730">into</span>
  <span m="3116710">k</span> <span m="3116920">parts,</span> <span m="3119100">if</span>
  <span m="3119270">this</span> <span m="3119420">partition</span> <span m="3119900">is</span>
  <span m="3120050">not</span> <span m="3120590">epsilon</span> <span m="3121040">regular,</span>
  <span m="3124650">then</span> <span m="3125700">there</span> <span m="3125910">exists</span>
  <span m="3126420">a</span> <span m="3126480">refinement</span> <span m="3131200">called</span>
  <span m="3131480">Q</span> <span m="3134090">where</span> <span m="3140550">every</span>
  <span m="3141900">part</span> <span m="3142590">V</span> <span m="3142770">sub</span>
  <span m="3143035">i</span> <span m="3144850">is</span> <span m="3147920">partitioned</span>
  <span m="3149420">further</span> <span m="3153110">into</span> <span m="3153640">at</span>
  <span m="3153770">most</span> <span m="3154700">2</span> <span m="3155090">the</span>
  <span m="3155180">k</span> <span m="3155720">parts,</span> <span m="3160960">and</span>
  <span m="3161120">such</span> <span m="3161390">that</span> <span m="3164720">the</span>
  <span m="3164990">partition</span> <span m="3165530">of</span> <span m="3165680">Q--</span>
  <span m="3166180">so</span> <span m="3166380">the</span> <span m="3166490">energy</span>
  <span m="3166940">of</span> <span m="3167180">the</span> <span m="3167240">new</span>
  <span m="3167450">partition</span> <span m="3167900">Q--</span> <span m="3169070">increases</span>
  <span m="3170060">substantially</span> <span m="3171200">from</span> <span m="3172190">the</span>
  <span m="3173030">previous</span> <span m="3173450">partition</span> <span m="3173900">P.</span></p><p><span
  m="3174830">And</span> <span m="3174980">we'll</span> <span m="3175160">show</span>
  <span m="3175370">that</span> <span m="3175550">you</span> <span m="3175640">can</span>
  <span m="3175790">increase</span> <span m="3176300">by</span> <span m="3176600">at</span>
  <span m="3176720">least</span> <span m="3177500">epsilon</span> <span m="3178040">to</span>
  <span m="3178190">the</span> <span m="3178280">5th</span> <span m="3178610">power,</span>
  <span m="3182690">some</span> <span m="3183020">constant</span> <span m="3183560">in</span>
  <span m="3183680">epsilon.</span> <span m="3185340">So</span> <span m="3185480">if</span>
  <span m="3185570">you</span> <span m="3185630">look</span> <span m="3185810">at</span>
  <span m="3185900">the</span> <span m="3185960">strategy</span> <span m="3186440">up</span>
  <span m="3186590">there,</span> <span m="3186800">if</span> <span m="3186950">you</span>
  <span m="3187190">can</span> <span m="3187370">do</span> <span m="3187520">this</span>
  <span m="3187760">every</span> <span m="3188000">step,</span> <span m="3188660">then</span>
  <span m="3188810">that</span> <span m="3188960">means</span> <span m="3189230">that</span>
  <span m="3189380">the</span> <span m="3189440">number</span> <span m="3189890">of</span>
  <span m="3190010">iterations</span> <span m="3190610">is</span> <span m="3190730">bounded</span>
  <span m="3191150">by</span> <span m="3191750">1</span> <span m="3192020">over</span>
  <span m="3192410">epsilon</span> <span m="3192890">to</span> <span m="3193040">the</span>
  <span m="3193130">5th</span> <span m="3193370">power.</span> <span m="3202580">So</span>
  <span m="3202680">to</span> <span m="3202860">prove</span> <span m="3203220">this</span>
  <span m="3203490">lemma</span> <span m="3203730">here,</span> <span m="3204330">we</span>
  <span m="3204510">will</span> <span m="3205380">use</span> <span m="3205920">the</span>
  <span m="3206550">three</span> <span m="3206850">lemmas</span> <span m="3207480">up</span>
  <span m="3207630">there</span> <span m="3208590">and</span> <span m="3208800">put</span>
  <span m="3209010">them</span> <span m="3209160">together.</span></p><p><span m="3215900">So</span>
  <span m="3215980">for</span> <span m="3218770">all</span> <span m="3218920">the</span>
  <span m="3219040">pairs</span> <span m="3219640">i,</span> <span m="3219820">j</span>
  <span m="3220690">such</span> <span m="3221080">that</span> <span m="3223030">V</span>
  <span m="3223330">sub</span> <span m="3223380">i,</span> <span m="3223710">V</span>
  <span m="3223980">sub</span> <span m="3224190">j</span> <span m="3224916">is</span>
  <span m="3225730">not</span> <span m="3226330">epsilon</span> <span m="3226780">regular,</span>
  <span m="3230650">as</span> <span m="3230920">outlined</span> <span m="3231310">in</span>
  <span m="3231460">the</span> <span m="3231550">proof</span> <span m="3232450">in</span>
  <span m="3232600">the</span> <span m="3232720">outline</span> <span m="3233160">up</span>
  <span m="3233290">there,</span> <span m="3233800">we</span> <span m="3233950">will</span>
  <span m="3234160">find</span> <span m="3236140">this</span> <span m="3236740">A</span>
  <span m="3236980">superscript</span> <span m="3237790">i,</span> <span m="3237940">j</span>
  <span m="3240360">in</span> <span m="3240480">Vi,</span> <span m="3242350">and</span>
  <span m="3242980">A</span> <span m="3243220">superscript</span> <span m="3243870">j,</span>
  <span m="3244250">i</span> <span m="3244550">in</span> <span m="3244740">Vj</span>
  <span m="3246220">that</span> <span m="3247930">witness</span> <span m="3249680">the</span>
  <span m="3250500">irregularity.</span> <span m="3257250">So</span> <span m="3257300">do</span>
  <span m="3257480">this</span> <span m="3258320">simultaneously</span> <span m="3259610">for</span>
  <span m="3260660">all</span> <span m="3260840">pairs</span> <span m="3261980">i,</span>
  <span m="3262130">comma,</span> <span m="3262390">j,</span> <span m="3263180">where</span>
  <span m="3263630">the</span> <span m="3263810">Vi,</span> <span m="3264100">Vj</span>
  <span m="3264350">is</span> <span m="3264470">not</span> <span m="3264770">epsilon</span>
  <span m="3265190">regular.</span></p><p><span m="3268390">Now</span> <span m="3270520">what</span>
  <span m="3270640">we're</span> <span m="3270790">going</span> <span m="3271030">to</span>
  <span m="3271150">define</span> <span m="3271720">Q</span> <span m="3272110">as</span>
  <span m="3273370">is</span> <span m="3273640">the</span> <span m="3273760">common</span>
  <span m="3274240">refinement.</span> <span m="3274900">So</span> <span m="3275500">take</span>
  <span m="3275890">all</span> <span m="3276100">of,</span> <span m="3276760">just</span>
  <span m="3277000">as</span> <span m="3277150">indicated in</span> <span m="3277630">that</span>
  <span m="3277750">picture</span> <span m="3278050">up</span> <span m="3278200">there,</span>
  <span m="3278740">simultaneously</span> <span m="3279550">take</span> <span m="3279790">all</span>
  <span m="3279940">of</span> <span m="3280030">these</span> <span m="3280270">A's</span>
  <span m="3281260">and</span> <span m="3282010">use</span> <span m="3282280">them</span>
  <span m="3282490">to</span> <span m="3282910">refine</span> <span m="3286360">P.</span>
  <span m="3294590">Starting</span> <span m="3295040">with</span> <span m="3295190">P,</span>
  <span m="3295460">starting</span> <span m="3295850">with</span> <span m="3295990">a</span>
  <span m="3296030">partition</span> <span m="3296450">you</span> <span m="3296540">have,</span>
  <span m="3297080">simultaneously</span> <span m="3297950">cut</span> <span m="3298430">everything</span>
  <span m="3298820">up</span> <span m="3299330">using</span> <span m="3299750">all</span>
  <span m="3299900">of</span> <span m="3299990">these</span> <span m="3300260">witnessing</span>
  <span m="3300830">sets.</span> <span m="3305980">Now,</span> <span m="3306170">we</span>
  <span m="3306290">only</span> <span m="3306560">have</span> <span m="3306940">witnessing</span>
  <span m="3307400">pairs</span> <span m="3307880">for</span> <span m="3309230">pairs</span>
  <span m="3309560">that</span> <span m="3309680">are</span> <span m="3309770">not</span>
  <span m="3310100">epsilon</span> <span m="3310520">regular.</span> <span m="3310970">If</span>
  <span m="3311090">they're</span> <span m="3311270">epsilon</span> <span m="3311630">regular,</span>
  <span m="3312020">you</span> <span m="3312110">don't</span> <span m="3312260">worry</span>
  <span m="3312530">about</span> <span m="3312770">them.</span></p><p><span m="3319570">One</span>
  <span m="3319650">of</span> <span m="3319710">the</span> <span m="3319830">claims</span>
  <span m="3320250">in</span> <span m="3320340">the</span> <span m="3320400">lemma</span>
  <span m="3320690">now</span> <span m="3321020">is--</span> <span m="3321390">this</span>
  <span m="3321930">is</span> <span m="3322050">the</span> <span m="3322110">Q</span>
  <span m="3322380">that</span> <span m="3322500">we'll</span> <span m="3322680">end</span>
  <span m="3322860">up</span> <span m="3322980">with.</span> <span m="3323160">We'll</span>
  <span m="3323600">show</span> <span m="3323810">that</span> <span m="3323970">this</span>
  <span m="3324120">Q</span> <span m="3324390">has</span> <span m="3324570">that</span>
  <span m="3324690">property.</span> <span m="3325470">So</span> <span m="3325620">one</span>
  <span m="3325860">of</span> <span m="3325920">the</span> <span m="3326040">claims</span>
  <span m="3326400">in</span> <span m="3326490">the</span> <span m="3326550">lemma</span>
  <span m="3326880">is</span> <span m="3327060">that</span> <span m="3327780">every</span>
  <span m="3328240">Vi</span> <span m="3328530">is</span> <span m="3328710">partitioned</span>
  <span m="3329370">into</span> <span m="3329700">at</span> <span m="3330030">most</span>
  <span m="3330420">2</span> <span m="3330660">to</span> <span m="3330780">the</span>
  <span m="3330870">k</span> <span m="3331080">parts.</span> <span m="3333390">So</span>
  <span m="3333750">I</span> <span m="3333840">hope</span> <span m="3334080">that</span>
  <span m="3334290">part</span> <span m="3334560">is</span> <span m="3334710">clear,</span>
  <span m="3335400">because</span> <span m="3337140">how</span> <span m="3337470">are</span>
  <span m="3337530">we</span> <span m="3337710">doing</span> <span m="3337980">the</span>
  <span m="3338040">refinement?</span></p><p><span m="3339360">We're</span> <span
  m="3339510">taking</span> <span m="3340300">Vi.</span> <span m="3344810">It's</span>
  <span m="3347260">divided</span> <span m="3348630">into</span> <span m="3349650">parts</span>
  <span m="3351530">using</span> <span m="3355720">these</span> <span m="3357100">A</span>
  <span m="3357355">i,</span> <span m="3357610">j's,</span> <span m="3359430">one</span>
  <span m="3359700">j</span> <span m="3360070">coming</span> <span m="3360370">from</span>
  <span m="3361830">each</span> <span m="3362730">pair</span> <span m="3363210">that</span>
  <span m="3363390">is</span> <span m="3363540">irregular</span> <span m="3364200">with</span>
  <span m="3365360">Vi.</span> <span m="3366850">So</span> <span m="3367780">I'm</span>
  <span m="3367930">cutting</span> <span m="3368380">up</span> <span m="3368560">Vi</span>
  <span m="3368860">using</span> <span m="3369190">at</span> <span m="3369260">most</span>
  <span m="3369550">k</span> <span m="3370180">sets,</span> <span m="3372500">so</span>
  <span m="3372720">one</span> <span m="3372960">coming</span> <span m="3373260">from</span>
  <span m="3373560">each</span> <span m="3373770">of</span> <span m="3373890">the</span>
  <span m="3374010">other</span> <span m="3374550">possible.</span> <span m="3375090">Maybe</span>
  <span m="3375360">fewer</span> <span m="3375630">than</span> <span m="3375780">k--</span>
  <span m="3376200">that's</span> <span m="3376440">fine--</span> <span m="3376650">but</span>
  <span m="3376770">at</span> <span m="3376830">most</span> <span m="3377100">k</span>
  <span m="3377385">sets</span> <span m="3378090">are</span> <span m="3378240">used</span>
  <span m="3378450">to</span> <span m="3378540">cut</span> <span m="3378780">up</span>
  <span m="3378960">each</span> <span m="3379790">Vi.</span> <span m="3380630">So</span>
  <span m="3380850">you</span> <span m="3381030">have</span> <span m="3382080">at</span>
  <span m="3382200">most</span> <span m="3383210">2</span> <span m="3383400">to</span>
  <span m="3383490">the</span> <span m="3383580">k</span> <span m="3383790">parts</span>
  <span m="3384360">once</span> <span m="3384600">you</span> <span m="3384690">cut</span>
  <span m="3384930">everything</span> <span m="3385290">up.</span></p><p><span m="3390820">But</span>
  <span m="3391110">the</span> <span m="3392020">tricky</span> <span m="3392350">part</span>
  <span m="3392890">is</span> <span m="3393040">to</span> <span m="3393130">show</span>
  <span m="3394420">that</span> <span m="3396010">you</span> <span m="3396130">get</span>
  <span m="3396370">an</span> <span m="3396460">energy</span> <span m="3396850">boost.</span>
  <span m="3399570">So</span> <span m="3399700">let's</span> <span m="3399860">do</span>
  <span m="3399980">this.</span> <span m="3400320">How</span> <span m="3400340">do</span>
  <span m="3400430">we</span> <span m="3400550">show</span> <span m="3400730">that</span>
  <span m="3400850">you</span> <span m="3400970">get</span> <span m="3401120">an</span>
  <span m="3401240">energy</span> <span m="3401600">boost?</span></p><p><span m="3409720">We're</span>
  <span m="3409840">going</span> <span m="3410020">to</span> <span m="3410080">put</span>
  <span m="3410530">the</span> <span m="3410890">top</span> <span m="3411160">three</span>
  <span m="3411340">lemmas</span> <span m="3411670">together.</span> <span m="3414864">First,</span>
  <span m="3417600">we</span> <span m="3417730">want</span> <span m="3417940">to</span>
  <span m="3418990">analyze</span> <span m="3419920">the</span> <span m="3420010">energy</span>
  <span m="3420430">of</span> <span m="3420550">Q.</span> <span m="3421510">So</span>
  <span m="3421690">let's</span> <span m="3421960">write</span> <span m="3422200">it</span>
  <span m="3422320">out.</span></p><p><span m="3423320">So</span> <span m="3423430">the</span>
  <span m="3423550">energy</span> <span m="3423970">of</span> <span m="3424060">Q</span>
  <span m="3425590">is</span> <span m="3425770">the</span> <span m="3425880">sum</span>
  <span m="3428290">over</span> <span m="3429930">this</span> <span m="3430220">energy</span>
  <span m="3430690">of</span> <span m="3431680">individual</span> <span m="3432790">partitions</span>
  <span m="3433510">of</span> <span m="3433630">the</span> <span m="3433750">Vi's.</span>
  <span m="3437810">And</span> <span m="3437970">by</span> <span m="3438660">this</span>
  <span m="3438900">P</span> <span m="3439175">sub</span> <span m="3439450">Vi,</span>
  <span m="3440540">P</span> <span m="3440820">sub</span> <span m="3441000">Vj,</span>
  <span m="3441450">I</span> <span m="3441540">mean</span> <span m="3442260">the</span>
  <span m="3442380">partition</span> <span m="3445220">of</span> <span m="3446442">Vj</span>
  <span m="3448280">given</span> <span m="3450970">by</span> <span m="3451430">Q.</span>
  <span m="3453270">So</span> <span m="3453470">what</span> <span m="3453620">happens</span>
  <span m="3453980">after</span> <span m="3454220">you</span> <span m="3454340">cut</span>
  <span m="3454610">up</span> <span m="3454880">the</span> <span m="3455050">Vi--</span>
  <span m="3456060">that's</span> <span m="3456290">what</span> <span m="3456470">I</span>
  <span m="3456530">mean</span> <span m="3456710">by</span> <span m="3457250">P</span>
  <span m="3457660">sub</span> <span m="3458440">Vj,</span> <span m="3461350">or</span>
  <span m="3461470">rather</span> <span m="3461740">I</span> <span m="3461800">should</span>
  <span m="3462370">call</span> <span m="3462610">it</span> <span m="3463170">Q</span>
  <span m="3463540">sub</span> <span m="3463885">Vi,</span> <span m="3464230">Q</span>
  <span m="3464490">sub</span> <span m="3464720">Vj.</span></p><p><span m="3472260">By</span>
  <span m="3474120">Lemma</span> <span m="3474400">2,</span> <span m="3478870">we</span>
  <span m="3479050">find</span> <span m="3479410">that--</span> <span m="3481830">so</span>
  <span m="3481960">let</span> <span m="3482080">me</span> <span m="3482230">separate</span>
  <span m="3482650">them</span> <span m="3482800">into</span> <span m="3482950">two</span>
  <span m="3483130">cases.</span> <span m="3484490">The</span> <span m="3484590">first</span>
  <span m="3485980">case</span> <span m="3487690">sums</span> <span m="3488020">over</span>
  <span m="3488440">i,</span> <span m="3488920">j</span> <span m="3489400">such</span>
  <span m="3489790">that</span> <span m="3490340">Vi,</span> <span m="3490650">Vj</span>
  <span m="3492640">is</span> <span m="3493120">epsilon</span> <span m="3493570">regular.</span>
  <span m="3496140">And</span> <span m="3496300">by</span> <span m="3497210">Lemma</span>
  <span m="3499140">1,</span> <span m="3500090">so</span> <span m="3500280">here</span>
  <span m="3500490">we're</span> <span m="3500610">using</span> <span m="3501420">Lemma</span>
  <span m="3501830">1,</span> <span m="3502620">we</span> <span m="3502680">find</span>
  <span m="3503040">that</span> <span m="3504090">this</span> <span m="3504330">quantity</span>
  <span m="3504720">here</span> <span m="3505230">cannot</span> <span m="3505890">be</span>
  <span m="3506070">less</span> <span m="3506430">than</span> <span m="3508370">the</span>
  <span m="3508490">Q</span> <span m="3509130">of</span> <span m="3510030">Vi,</span>
  <span m="3510440">Vj.</span> <span m="3511580">So</span> <span m="3511820">take</span>
  <span m="3513080">those</span> <span m="3513260">two</span> <span m="3513410">parts.</span></p><p><span
  m="3515510">Before</span> <span m="3515990">and</span> <span m="3516170">after</span>
  <span m="3516440">the</span> <span m="3516530">refinement</span> <span m="3517670">by</span>
  <span m="3517850">Q,</span> <span m="3518680">the</span> <span m="3518780">energy</span>
  <span m="3519140">cannot</span> <span m="3519500">go</span> <span m="3519650">down.</span>
  <span m="3523660">So</span> <span m="3523710">I</span> <span m="3523770">don't</span>
  <span m="3523980">worry</span> <span m="3524250">too</span> <span m="3524430">much</span>
  <span m="3524640">about</span> <span m="3524950">pairs that are</span> <span m="3525420">epsilon</span>
  <span m="3525840">regular.</span> <span m="3527780">But</span> <span m="3527880">no</span>
  <span m="3528060">let</span> <span m="3528180">me</span> <span m="3528300">look</span>
  <span m="3528510">up</span> <span m="3528660">here</span> <span m="3529000">that</span>
  <span m="3529230">are</span> <span m="3530130">not</span> <span m="3531120">epsilon</span>
  <span m="3531510">regular.</span></p><p><span m="3545630">So</span> <span m="3545810">what</span>
  <span m="3546020">we</span> <span m="3546170">will</span> <span m="3546350">do</span>
  <span m="3546500">now</span> <span m="3547250">is</span> <span m="3548630">even</span>
  <span m="3548900">though--</span> <span m="3550050">so</span> <span m="3550190">let's</span>
  <span m="3550370">look</span> <span m="3550520">at</span> <span m="3550590">that</span>
  <span m="3550730">picture</span> <span m="3551030">up</span> <span m="3551150">there.</span>
  <span m="3555750">So</span> <span m="3555800">let's</span> <span m="3556010">focus</span>
  <span m="3556550">on</span> <span m="3558320">what</span> <span m="3558530">I</span>
  <span m="3558620">drew</span> <span m="3558860">in</span> <span m="3558980">red.</span>
  <span m="3560970">So</span> <span m="3561020">let's</span> <span m="3561200">focus</span>
  <span m="3562570">between</span> <span m="3562880">1</span> <span m="3563180">and</span>
  <span m="3563320">2.</span> <span m="3564670">So</span> <span m="3565650">suppose</span>
  <span m="3567700">the</span> <span m="3567900">shaded</span> <span m="3568290">part</span>
  <span m="3569400">is</span> <span m="3569550">the</span> <span m="3569880">witnessing</span>
  <span m="3570570">sets.</span></p><p><span m="3572280">The</span> <span m="3572400">witnessing</span>
  <span m="3572850">sets</span> <span m="3573120">got</span> <span m="3573360">cut</span>
  <span m="3573660">up</span> <span m="3573780">further</span> <span m="3574890">by</span>
  <span m="3577050">other</span> <span m="3577680">witnessing</span> <span m="3578070">sets.</span>
  <span m="3579490">But</span> <span m="3580240">I</span> <span m="3580390">don't</span>
  <span m="3580600">have</span> <span m="3580810">to</span> <span m="3580900">worry</span>
  <span m="3581260">about</span> <span m="3581500">them</span> <span m="3581650">because</span>
  <span m="3583090">Lemma</span> <span m="3584770">2</span> <span m="3586570">or</span>
  <span m="3586690">Lemma</span> <span m="3586810">1,</span> <span m="3587040">really,</span>
  <span m="3587820">tells</span> <span m="3588120">me</span> <span m="3588390">that</span>
  <span m="3591250">I</span> <span m="3591400">can</span> <span m="3592060">do</span>
  <span m="3592280">an</span> <span m="3592340">inequality</span> <span m="3592960">where</span>
  <span m="3593110">I</span> <span m="3593230">go</span> <span m="3593440">down</span>
  <span m="3594520">to</span> <span m="3594790">just</span> <span m="3596050">comparing</span>
  <span m="3598390">the</span> <span m="3598660">energy</span> <span m="3599110">between</span>
  <span m="3600100">this</span> <span m="3600400">partition</span> <span m="3600940">of</span>
  <span m="3601030">two</span> <span m="3601240">parts,</span> <span m="3603440">this</span>
  <span m="3603830">single</span> <span m="3604300">witnessing</span> <span m="3604690">set</span>
  <span m="3605030">and</span> <span m="3605150">its</span> <span m="3605310">complement,</span>
  <span m="3609690">versus</span> <span m="3613130">what</span> <span m="3613280">happens</span>
  <span m="3613670">in</span> <span m="3615660">its</span> <span m="3615830">partner.</span></p><p><span
  m="3624620">So</span> <span m="3624740">in</span> <span m="3624860">other</span>
  <span m="3625040">words,</span> <span m="3627410">over</span> <span m="3627560">here,</span>
  <span m="3629960">the</span> <span m="3630080">Q</span> <span m="3630500">of</span>
  <span m="3630650">this</span> <span m="3631100">pair,</span> <span m="3632600">I</span>
  <span m="3632790">am</span> <span m="3634960">saying</span> <span m="3635380">that</span>
  <span m="3635590">it</span> <span m="3635770">is</span> <span m="3636610">no</span>
  <span m="3638300">less</span> <span m="3639110">than</span> <span m="3639860">if</span>
  <span m="3640010">I</span> <span m="3640220">just</span> <span m="3640670">look</span>
  <span m="3640980">at</span> <span m="3642400">what</span> <span m="3642580">happens</span>
  <span m="3643180">if</span> <span m="3643360">you</span> <span m="3643480">only</span>
  <span m="3643780">cut</span> <span m="3644050">up</span> <span m="3645100">these</span>
  <span m="3645280">two</span> <span m="3645430">sets</span> <span m="3646270">using</span>
  <span m="3647280">the</span> <span m="3647380">red</span> <span m="3647590">lines.</span></p><p><span
  m="3655790">Let's</span> <span m="3655940">go</span> <span m="3656110">on.</span>
  <span m="3657960">Applying</span> <span m="3658610">Lemma</span> <span m="3658810">3,</span>
  <span m="3659330">the</span> <span m="3659470">energy</span> <span m="3659830">boost</span>
  <span m="3660100">lemma,</span> <span m="3662400">the</span> <span m="3662490">first</span>
  <span m="3662730">part</span> <span m="3662970">stays</span> <span m="3663270">the</span>
  <span m="3663360">same.</span> <span m="3664960">So</span> <span m="3665430">this</span>
  <span m="3665610">first</span> <span m="3665820">part</span> <span m="3666000">stays</span>
  <span m="3666240">the</span> <span m="3666300">same.</span> <span m="3666820">And</span>
  <span m="3666900">the</span> <span m="3666960">second</span> <span m="3667290">part,</span>
  <span m="3667890">now,</span> <span m="3668190">because</span> <span m="3668520">I'm</span>
  <span m="3668640">looking</span> <span m="3668940">at</span> <span m="3669090">witnessing</span>
  <span m="3669570">sets</span> <span m="3669840">for</span> <span m="3669990">irregularity,</span>
  <span m="3671160">I</span> <span m="3671310">get</span> <span m="3671700">this</span>
  <span m="3671940">extra</span> <span m="3672270">boost.</span> <span m="3675950">So</span>
  <span m="3676390">this</span> <span m="3676600">goes</span> <span m="3676810">back</span>
  <span m="3677020">to</span> <span m="3677350">one</span> <span m="3677560">of</span>
  <span m="3677620">the</span> <span m="3677680">questions</span> <span m="3678130">asked</span>
  <span m="3678490">earlier,</span> <span m="3679240">where</span> <span m="3679780">in</span>
  <span m="3679930">Lemma</span> <span m="3680170">3,</span> <span m="3680620">I</span>
  <span m="3680740">don't</span> <span m="3680980">have</span> <span m="3681280">to</span>
  <span m="3681450">now</span> <span m="3681670">worry</span> <span m="3682150">about</span>
  <span m="3682720">what</span> <span m="3682900">happens</span> <span m="3683260">if</span>
  <span m="3683350">you</span> <span m="3683440">have</span> <span m="3684100">further</span>
  <span m="3685300">cuts,</span> <span m="3686440">because</span> <span m="3687790">I</span>
  <span m="3687910">only</span> <span m="3688180">need</span> <span m="3688330">to</span>
  <span m="3688420">worry</span> <span m="3688780">about</span> <span m="3689010">the</span>
  <span m="3689080">case</span> <span m="3689620">where</span> <span m="3689860">I</span>
  <span m="3689990">only</span> <span m="3690160">have</span> <span m="3690310">a</span>
  <span m="3690370">single</span> <span m="3690760">cut</span> <span m="3691240">between</span>
  <span m="3691940">the</span> <span m="3692110">epsilon</span> <span m="3692650">irregular</span>
  <span m="3693220">pairs.</span></p><p><span m="3694740">So</span> <span m="3694950">putting</span>
  <span m="3695310">it</span> <span m="3695370">together,</span> <span m="3697060">we</span>
  <span m="3697110">see</span> <span m="3697350">that</span> <span m="3699060">the</span>
  <span m="3699150">previous</span> <span m="3699600">line</span> <span m="3699900">is</span>
  <span m="3700050">at</span> <span m="3700140">least,</span> <span m="3705470">if</span>
  <span m="3705650">you</span> <span m="3706640">sum</span> <span m="3706910">over</span>
  <span m="3707150">the Q's</span> <span m="3707550">of</span> <span m="3707660">all</span>
  <span m="3707780">the</span> <span m="3707900">pairs</span> <span m="3708740">plus</span>
  <span m="3710880">this</span> <span m="3711250">extra</span> <span m="3712350">epsilon</span>
  <span m="3712770">to</span> <span m="3712900">the</span> <span m="3712990">4th</span>
  <span m="3713290">term</span> <span m="3717110">for</span> <span m="3717950">all</span>
  <span m="3718130">pairs</span> <span m="3719420">that</span> <span m="3719630">are</span>
  <span m="3720170">not</span> <span m="3720650">epsilon</span> <span m="3721100">regular.</span>
  <span m="3737890">I'm</span> <span m="3738170">applying</span> <span m="3739910">monotonicity</span>
  <span m="3740630">of</span> <span m="3740750">energy</span> <span m="3741140">for</span>
  <span m="3741740">the</span> <span m="3742250">types,</span> <span m="3743840">for</span>
  <span m="3743990">pairs</span> <span m="3744380">that</span> <span m="3744500">are</span>
  <span m="3744620">epsilon</span> <span m="3745010">regular,</span> <span m="3745760">an</span>
  <span m="3745940">energy</span> <span m="3746300">boost</span> <span m="3746960">for</span>
  <span m="3747110">pairs</span> <span m="3747440">that</span> <span m="3747560">are</span>
  <span m="3747650">not</span> <span m="3747920">epsilon</span> <span m="3748340">regular.</span>
  <span m="3749080">And</span> <span m="3749480">for</span> <span m="3749570">the</span>
  <span m="3749660">latter</span> <span m="3749960">type,</span> <span m="3750560">I</span>
  <span m="3750680">obtain</span> <span m="3751050">this</span> <span m="3751190">boost.</span></p><p><span
  m="3753120">Now</span> <span m="3753360">remember</span> <span m="3753690">what's</span>
  <span m="3753930">the</span> <span m="3754020">definition</span> <span m="3754560">of</span>
  <span m="3754680">an</span> <span m="3754770">&quot;epsilon</span> <span m="3755160">regular</span>
  <span m="3755550">partition.&quot;</span> <span m="3756270">Unfortunately,</span>
  <span m="3756850">it's</span> <span m="3756960">no</span> <span m="3757110">longer</span>
  <span m="3757380">on</span> <span m="3757500">the</span> <span m="3757560">board,</span>
  <span m="3758100">but</span> <span m="3758310">it</span> <span m="3758410">says</span>
  <span m="3758790">that</span> <span m="3759270">this</span> <span m="3759510">sum</span>
  <span m="3760020">over</span> <span m="3760260">here,</span> <span m="3762890">if</span>
  <span m="3762970">it</span> <span m="3763060">is</span> <span m="3763340">an</span>
  <span m="3763610">epsilon</span> <span m="3764060">regular</span> <span m="3764510">partition,</span>
  <span m="3764990">it is</span> <span m="3765440">at</span> <span m="3765560">most</span>
  <span m="3766670">epsilon.</span> <span m="3767660">So</span> <span m="3767820">if</span>
  <span m="3767960">it is</span> <span m="3768200">not</span> <span m="3768470">epsilon</span>
  <span m="3768890">regular,</span> <span m="3769790">we</span> <span m="3769910">can</span>
  <span m="3770060">lower</span> <span m="3770310">bound</span> <span m="3770640">it.</span>
  <span m="3771980">And</span> <span m="3772110">that's</span> <span m="3772350">indeed</span>
  <span m="3772680">what</span> <span m="3772830">we</span> <span m="3772920">will</span>
  <span m="3773070">do.</span></p><p><span m="3775680">The</span> <span m="3775770">first</span>
  <span m="3776090">sum</span> <span m="3776340">here</span> <span m="3777000">is,</span>
  <span m="3777120">by</span> <span m="3777270">definition,</span> <span m="3778050">Q</span>
  <span m="3778620">of</span> <span m="3780400">the</span> <span m="3780500">partition</span>
  <span m="3780990">P.</span> <span m="3783210">And</span> <span m="3783330">the</span>
  <span m="3783420">second</span> <span m="3783750">sum,</span> <span m="3784020">by</span>
  <span m="3784200">the</span> <span m="3784290">definition</span> <span m="3785010">of</span>
  <span m="3785460">epsilon</span> <span m="3785910">regular,</span> <span m="3787890">is</span>
  <span m="3788430">at</span> <span m="3788520">least</span> <span m="3789330">epsilon</span>
  <span m="3789900">to</span> <span m="3790050">the</span> <span m="3790140">power</span>
  <span m="3790560">5.</span> <span m="3792840">So</span> <span m="3793130">here</span>
  <span m="3793340">we're</span> <span m="3793490">using</span> <span m="3793850">the</span>
  <span m="3793940">definition</span> <span m="3794480">of</span> <span m="3794630">epsilon</span>
  <span m="3795170">regular</span> <span m="3795620">partition,</span> <span m="3797200">namely,</span>
  <span m="3797590">that</span> <span m="3798280">a</span> <span m="3798340">large</span>
  <span m="3798760">fraction,</span> <span m="3799970">so</span> <span m="3800110">at</span>
  <span m="3800170">least</span> <span m="3800500">an</span> <span m="3801850">epsilon</span>
  <span m="3802330">fraction,</span> <span m="3804010">basically,</span> <span m="3804550">of</span>
  <span m="3805540">pairs</span> <span m="3805930">of</span> <span m="3806830">vertex</span>
  <span m="3807190">sets</span> <span m="3808240">are</span> <span m="3808690">not</span>
  <span m="3809080">epsilon</span> <span m="3809500">regular,</span> <span m="3811310">but</span>
  <span m="3811520">in</span> <span m="3811610">this</span> <span m="3811790">weighted</span>
  <span m="3812120">sense.</span></p><p><span m="3814940">And</span> <span m="3815100">that</span>
  <span m="3815410">finishes</span> <span m="3815780">the</span> <span m="3815870">proof</span>
  <span m="3816410">of</span> <span m="3816890">Lemma</span> <span m="3817100">4</span>
  <span m="3817490">up</span> <span m="3817650">there.</span> <span m="3821760">Any</span>
  <span m="3822000">questions</span> <span m="3822510">so</span> <span m="3822690">far?</span>
  <span m="3827650">All</span> <span m="3827720">right,</span> <span m="3828310">so</span>
  <span m="3828430">now</span> <span m="3828730">we</span> <span m="3828940">are</span>
  <span m="3829030">ready</span> <span m="3829300">to</span> <span m="3830170">finish</span>
  <span m="3830560">everything</span> <span m="3830890">off,</span> <span m="3831570">and</span>
  <span m="3831700">prove</span> <span m="3832180">Szemeredi's</span> <span m="3832900">regularity</span>
  <span m="3833500">lemma.</span></p><p><span m="3861530">So</span> <span m="3861760">let's</span>
  <span m="3861970">prove</span> <span m="3865460">Szemeredi's</span> <span m="3867440">regularity</span>
  <span m="3868080">lemma.</span> <span m="3873480">Let's</span> <span m="3873630">start</span>
  <span m="3874140">with</span> <span m="3877020">the</span> <span m="3877110">trivial</span>
  <span m="3877530">partition,</span> <span m="3883160">meaning</span> <span m="3883430">just</span>
  <span m="3883640">one</span> <span m="3884090">large</span> <span m="3884420">part.</span>
  <span m="3886250">And</span> <span m="3886580">we</span> <span m="3886790">are</span>
  <span m="3886880">going</span> <span m="3887150">to</span> <span m="3887840">repeatedly</span>
  <span m="3888470">apply</span> <span m="3893880">Lemma</span> <span m="3894380">4</span>
  <span m="3898840">whenever</span> <span m="3899900">the</span> <span m="3900010">partition</span>
  <span m="3900630">at</span> <span m="3900760">hand</span> <span m="3901060">is</span>
  <span m="3901210">not</span> <span m="3901630">regular,</span> <span m="3911700">whenever</span>
  <span m="3912010">the</span> <span m="3912070">current</span> <span m="3912730">partition</span>
  <span m="3913690">is</span> <span m="3913840">not</span> <span m="3914290">epsilon</span>
  <span m="3914770">regular.</span></p><p><span m="3920600">So</span> <span m="3920720">let's</span>
  <span m="3921130">look</span> <span m="3921310">at</span> <span m="3921400">its</span>
  <span m="3921550">energy.</span> <span m="3922930">The</span> <span m="3923260">energy</span>
  <span m="3925840">of</span> <span m="3925960">this</span> <span m="3926140">partition--</span>
  <span m="3928590">so</span> <span m="3928740">this</span> <span m="3928950">is</span>
  <span m="3929790">a</span> <span m="3929890">weighted</span> <span m="3931200">mean</span>
  <span m="3931770">of</span> <span m="3932130">the</span> <span m="3933240">edge</span>
  <span m="3933490">density</span> <span m="3933930">squared,</span> <span m="3934860">so</span>
  <span m="3935370">it</span> <span m="3935610">always</span> <span m="3936000">lies</span>
  <span m="3936360">between</span> <span m="3937380">0</span> <span m="3937920">and</span>
  <span m="3938100">1,</span> <span m="3940020">just</span> <span m="3940230">from</span>
  <span m="3940410">the</span> <span m="3940500">definition</span> <span m="3941280">of</span>
  <span m="3942240">energy.</span> <span m="3944760">On</span> <span m="3944880">the</span>
  <span m="3945000">other</span> <span m="3945150">hand,</span> <span m="3949980">Lemma</span>
  <span m="3950220">4</span> <span m="3951240">tells</span> <span m="3951570">us</span>
  <span m="3951990">that</span> <span m="3953790">the</span> <span m="3953940">energy</span>
  <span m="3954810">increases</span> <span m="3956640">by</span> <span m="3957570">at</span>
  <span m="3957690">least</span> <span m="3958350">epsilon</span> <span m="3959130">to</span>
  <span m="3959250">the</span> <span m="3959340">5th</span> <span m="3959910">power</span>
  <span m="3960840">at</span> <span m="3961080">each</span> <span m="3962310">iteration.</span></p><p><span
  m="3970570">So</span> <span m="3970710">this</span> <span m="3970860">process</span>
  <span m="3971250">cannot</span> <span m="3971580">continue</span> <span m="3972030">forever.</span>
  <span m="3974370">So</span> <span m="3975060">it</span> <span m="3975450">must</span>
  <span m="3975690">stop</span> <span m="3977700">after</span> <span m="3979521">at</span>
  <span m="3979950">most</span> <span m="3980700">epsilon</span> <span m="3981180">to
  the</span> <span m="3981420">minus</span> <span m="3981950">5th</span> <span m="3982260">power</span>
  <span m="3983490">number</span> <span m="3983760">of</span> <span m="3983820">steps.</span>
  <span m="3987080">And</span> <span m="3987220">when</span> <span m="3987400">we</span>
  <span m="3987610">stop,</span> <span m="3989380">we</span> <span m="3989650">must</span>
  <span m="3990010">result</span> <span m="3990580">in</span> <span m="3991510">an</span>
  <span m="3991660">epsilon</span> <span m="3992080">regular</span> <span m="3992590">partition,</span>
  <span m="3998460">because</span> <span m="3998760">otherwise,</span> <span m="3999160">you're</span>
  <span m="3999220">going</span> <span m="3999320">to</span> <span m="3999540">continue</span>
  <span m="3999990">applying</span> <span m="4000380">the</span> <span m="4000460">lemma</span>
  <span m="4000830">and</span> <span m="4000890">push</span> <span m="4001220">it</span>
  <span m="4001340">even</span> <span m="4001580">further.</span> <span m="4003156">And</span>
  <span m="4003580">that's</span> <span m="4003680">it.</span> <span m="4006240">So</span>
  <span m="4006390">that</span> <span m="4006890">proves</span> <span m="4007470">Szemeredi's</span>
  <span m="4009030">graph</span> <span m="4009720">regularity</span> <span m="4010110">lemma.</span>
  <span m="4013440">Question.</span></p><p><span m="4014910">AUDIENCE:</span> <span
  m="4015032">It's</span> <span m="4015154">going</span> <span m="4015276">to</span>
  <span m="4015400">be some really</span> <span m="4015890">big value</span> <span
  m="4016380">of</span> <span m="4016870">M.</span></p><p><span m="4017360">YUFEI
  ZHAO:</span> <span m="4017445">OK,</span> <span m="4017760">let's</span> <span m="4017910">talk</span>
  <span m="4018090">about</span> <span m="4018290">bounds.</span> <span m="4019030">So</span>
  <span m="4019200">let's</span> <span m="4019380">talk</span> <span m="4019530">about</span>
  <span m="4019650">how</span> <span m="4019830">many</span> <span m="4020070">parts.</span>
  <span m="4026580">So</span> <span m="4026740">how</span> <span m="4026890">many</span>
  <span m="4027100">parts</span> <span m="4027790">does</span> <span m="4028030">this</span>
  <span m="4028300">proof</span> <span m="4028690">produce?</span> <span m="4031410">We</span>
  <span m="4031500">can</span> <span m="4031650">figure</span> <span m="4031920">it</span>
  <span m="4032010">out.</span></p><p><span m="4032350">So</span> <span m="4032610">we</span>
  <span m="4032790">have</span> <span m="4033090">some</span> <span m="4033330">number</span>
  <span m="4033600">of</span> <span m="4033690">steps.</span> <span m="4034470">Each</span>
  <span m="4034680">step</span> <span m="4035250">increases</span> <span m="4035880">the</span>
  <span m="4035940">number</span> <span m="4036210">of</span> <span m="4036270">parts</span>
  <span m="4036630">by</span> <span m="4036810">something.</span> <span m="4038440">So</span>
  <span m="4039180">if</span> <span m="4040474">P</span> <span m="4041965">has</span>
  <span m="4042960">k</span> <span m="4043590">parts,</span> <span m="4047410">so</span>
  <span m="4047510">then</span> <span m="4047840">Lemma</span> <span m="4048110">4</span>
  <span m="4050240">refines</span> <span m="4050840">P</span> <span m="4054090">into</span>
  <span m="4054660">at</span> <span m="4054990">most</span> <span m="4055290">how</span>
  <span m="4055380">many</span> <span m="4055680">parts?</span></p><p><span m="4057910">AUDIENCE:</span>
  <span m="4058002">2</span> <span m="4058094">to</span> <span m="4058186">the</span>
  <span m="4058278">k</span></p><p><span m="4058830">YUFEI ZHAO:</span> <span m="4058860">Yeah,</span>
  <span m="4059210">so k</span> <span m="4059510">times</span> <span m="4059900">2</span>
  <span m="4060050">to</span> <span m="4060170">the</span> <span m="4060270">k.</span>
  <span m="4064330">And</span> <span m="4064480">I</span> <span m="4064570">have</span>
  <span m="4064990">many</span> <span m="4065320">iterations</span> <span m="4066370">of</span>
  <span m="4066520">this</span> <span m="4066660">guy.</span> <span m="4068930">So</span>
  <span m="4069070">some</span> <span m="4069280">of</span> <span m="4069370">you</span>
  <span m="4069500">are</span> <span m="4069550">already</span> <span m="4069880">laughing,</span>
  <span m="4070220">because</span> <span m="4070430">it's</span> <span m="4070740">going</span>
  <span m="4070920">to</span> <span m="4071020">be</span> <span m="4071140">a</span>
  <span m="4071200">very</span> <span m="4071410">large</span> <span m="4071710">number.</span>
  <span m="4073280">In</span> <span m="4073380">fact,</span> <span m="4073690">because</span>
  <span m="4073990">it's</span> <span m="4074110">going</span> <span m="4074190">to</span>
  <span m="4074260">be</span> <span m="4074350">so</span> <span m="4074560">large,</span>
  <span m="4075310">it</span> <span m="4075430">makes</span> <span m="4075670">my</span>
  <span m="4075820">calculations</span> <span m="4076390">slightly</span> <span m="4076720">more</span>
  <span m="4076870">convenient.</span></p><p><span m="4077460">It</span> <span m="4077650">really</span>
  <span m="4077860">doesn't</span> <span m="4078130">change</span> <span m="4078400">the</span>
  <span m="4078490">answer</span> <span m="4078730">so</span> <span m="4078910">much</span>
  <span m="4079450">if</span> <span m="4079570">I</span> <span m="4079660">just</span>
  <span m="4079840">bound</span> <span m="4080200">k</span> <span m="4080460">to</span>
  <span m="4080560">the</span> <span m="4080650">2</span> <span m="4080770">to</span>
  <span m="4080860">the</span> <span m="4080950">k</span> <span m="4081130">by</span>
  <span m="4081310">2</span> <span m="4081460">to</span> <span m="4081580">the</span>
  <span m="4081670">2</span> <span m="4081820">to</span> <span m="4081910">the</span>
  <span m="4082000">k.</span> <span m="4083050">So</span> <span m="4084070">the</span>
  <span m="4084160">final</span> <span m="4084520">number</span> <span m="4084820">of</span>
  <span m="4084910">parts</span> <span m="4089120">is</span> <span m="4089750">this</span>
  <span m="4089960">function</span> <span m="4090440">iterated</span> <span m="4090890">on</span>
  <span m="4091010">itself</span> <span m="4091500">epsilon</span> <span m="4092480">to</span>
  <span m="4092570">the</span> <span m="4092630">minus</span> <span m="4092930">5</span>
  <span m="4093170">times.</span> <span m="4095030">So</span> <span m="4095210">it's</span>
  <span m="4095350">a</span> <span m="4095390">power</span> <span m="4095810">of</span>
  <span m="4095960">2</span> <span m="4097760">of</span> <span m="4097970">height</span>
  <span m="4100410">at</span> <span m="4100500">most</span> <span m="4101600">2</span>
  <span m="4101880">to</span> <span m="4102029">the</span> <span m="4102149">epsilon</span>
  <span m="4102609">to</span> <span m="4102750">the</span> <span m="4102859">5.</span></p><p><span
  m="4106560">It's</span> <span m="4106649">a</span> <span m="4106710">finite</span>
  <span m="4107040">number,</span> <span m="4107750">so</span> <span m="4107910">it</span>
  <span m="4107970">depends</span> <span m="4108359">only</span> <span m="4108600">on</span>
  <span m="4108689">epsilon</span> <span m="4109170">and</span> <span m="4109260">not</span>
  <span m="4109529">on</span> <span m="4109649">the</span> <span m="4109710">size</span>
  <span m="4110040">of</span> <span m="4110130">your</span> <span m="4110250">graph.</span>
  <span m="4110560">And</span> <span m="4110640">this</span> <span m="4110790">is</span>
  <span m="4110910">the</span> <span m="4110970">most</span> <span m="4111180">important</span>
  <span m="4111510">thing.</span> <span m="4111670">It does</span> <span m="4111840">not</span>
  <span m="4112439">depend</span> <span m="4112800">on</span> <span m="4112890">the</span>
  <span m="4112979">size</span> <span m="4113340">of</span> <span m="4113430">your</span>
  <span m="4113550">graph.</span> <span m="4115290">It</span> <span m="4115410">is</span>
  <span m="4115890">quite</span> <span m="4116189">large.</span></p><p><span m="4118020">In</span>
  <span m="4118140">fact,</span> <span m="4119020">even</span> <span m="4119189">for</span>
  <span m="4120720">reasonable</span> <span m="4121200">values</span> <span m="4121680">of</span>
  <span m="4122130">epsilon,</span> <span m="4122880">like</span> <span m="4123180">1%</span>
  <span m="4123689">or</span> <span m="4123779">even</span> <span m="4124140">10%,</span>
  <span m="4124950">this</span> <span m="4125130">number</span> <span m="4125430">is</span>
  <span m="4126000">astronomically</span> <span m="4126660">large.</span> <span m="4128850">And</span>
  <span m="4129060">you</span> <span m="4129120">may</span> <span m="4129270">ask</span>
  <span m="4130590">is</span> <span m="4130740">it</span> <span m="4130800">really</span>
  <span m="4131010">necessary,</span> <span m="4131490">because</span> <span m="4131689">we</span>
  <span m="4131939">did</span> <span m="4132120">this</span> <span m="4132270">proof,</span>
  <span m="4132810">and</span> <span m="4133050">it</span> <span m="4133170">came</span>
  <span m="4133410">out</span> <span m="4133529">fairly</span> <span m="4133950">elegantly,</span>
  <span m="4134430">I</span> <span m="4134520">would</span> <span m="4134640">say</span>
  <span m="4134840">it,</span> <span m="4134910">how</span> <span m="4135090">the</span>
  <span m="4135180">proof</span> <span m="4135390">was</span> <span m="4135510">set</span>
  <span m="4135729">up.</span> <span m="4136080">And</span> <span m="4136200">you</span>
  <span m="4136260">arrived</span> <span m="4136649">at</span> <span m="4136950">this</span>
  <span m="4137220">finite</span> <span m="4137649">bound.</span></p><p><span m="4138779">But</span>
  <span m="4138990">maybe</span> <span m="4139380">there's</span> <span m="4139560">a</span>
  <span m="4139620">better</span> <span m="4139890">proof.</span> <span m="4140319">Maybe</span>
  <span m="4140460">you</span> <span m="4140700">can</span> <span m="4140880">work</span>
  <span m="4141090">harder</span> <span m="4141359">and</span> <span m="4141450">obtain</span>
  <span m="4141779">somewhat</span> <span m="4142050">better</span> <span m="4142290">bounds.</span>
  <span m="4144170">So</span> <span m="4144290">you</span> <span m="4144350">can</span>
  <span m="4144500">ask,</span> <span m="4144740">is</span> <span m="4144890">it</span>
  <span m="4144950">possible</span> <span m="4145510">that</span> <span m="4146720">the</span>
  <span m="4146840">truth</span> <span m="4147200">is</span> <span m="4147370">really</span>
  <span m="4148250">somehow</span> <span m="4148729">much</span> <span m="4149180">smaller?</span>
  <span m="4151279">And</span> <span m="4151410">the</span> <span m="4151500">answer</span>
  <span m="4151740">turns</span> <span m="4151979">out</span> <span m="4152069">to</span>
  <span m="4152130">be</span> <span m="4152250">no.</span></p><p><span m="4155189">So</span>
  <span m="4155649">there</span> <span m="4155819">is</span> <span m="4155970">a</span>
  <span m="4156060">theorem</span> <span m="4157950">by</span> <span m="4158279">Tim</span>
  <span m="4158520">Gowers</span> <span m="4161100">which</span> <span m="4161310">says</span>
  <span m="4162000">that</span> <span m="4163350">there</span> <span m="4163500">exists</span>
  <span m="4163800">some</span> <span m="4163920">constant.</span> <span m="4164439">The</span>
  <span m="4164550">precise</span> <span m="4165000">statement,</span> <span m="4165210">again,
  is</span> <span m="4165540">not</span> <span m="4165689">so</span> <span m="4165810">important,</span>
  <span m="4166170">but</span> <span m="4166319">based</span> <span m="4166540">on</span>
  <span m="4166710">what</span> <span m="4166859">I</span> <span m="4166920">just</span>
  <span m="4167069">said,</span> <span m="4167220">you</span> <span m="4167310">cannot</span>
  <span m="4167729">improve</span> <span m="4168120">this</span> <span m="4168220">bound</span>
  <span m="4168899">given</span> <span m="4169229">by</span> <span m="4169500">this</span>
  <span m="4169819">proof.</span> <span m="4171180">So</span> <span m="4171390">for</span>
  <span m="4171930">every</span> <span m="4172290">epsilon</span> <span m="4174420">small</span>
  <span m="4174689">enough,</span> <span m="4178910">there</span> <span m="4179090">exists</span>
  <span m="4179660">a</span> <span m="4179720">graph</span> <span m="4182060">whose</span>
  <span m="4183819">epsilon</span> <span m="4184300">regular</span> <span m="4184870">partition</span>
  <span m="4188470">requires</span> <span m="4192250">how</span> <span m="4192370">many</span>
  <span m="4192580">parts?</span></p><p><span m="4194120">So</span> <span m="4194450">the</span>
  <span m="4194500">number</span> <span m="4194800">of</span> <span m="4194890">parts</span>
  <span m="4197130">at</span> <span m="4197220">least</span> <span m="4198210">this</span>
  <span m="4198360">tower</span> <span m="4198780">of</span> <span m="4198910">2</span>
  <span m="4200290">of</span> <span m="4200480">height</span> <span m="4202950">some</span>
  <span m="4204420">epsilon</span> <span m="4204930">to</span> <span m="4205080">the</span>
  <span m="4205170">minus</span> <span m="4205710">c.</span> <span m="4209630">So</span>
  <span m="4209900">really</span> <span m="4210260">it's</span> <span m="4210500">a</span>
  <span m="4210590">tower</span> <span m="4212340">of</span> <span m="4212470">exponentials</span>
  <span m="4213900">of</span> <span m="4214060">size,</span> <span m="4215200">essentially</span>
  <span m="4215680">polynomial</span> <span m="4216280">in</span> <span m="4216550">1</span>
  <span m="4216760">over</span> <span m="4216940">epsilon.</span> <span m="4218800">So</span>
  <span m="4218850">maybe</span> <span m="4219150">you</span> <span m="4219300">can</span>
  <span m="4220530">squeeze</span> <span m="4221040">the</span> <span m="4221130">5</span>
  <span m="4221550">to</span> <span m="4221640">something</span> <span m="4222240">less.</span>
  <span m="4222570">Actually,</span> <span m="4222780">we</span> <span m="4222870">don't</span>
  <span m="4223020">even</span> <span m="4223200">know</span> <span m="4223350">if</span>
  <span m="4223410">that's</span> <span m="4223650">the</span> <span m="4223770">case,</span>
  <span m="4224250">but</span> <span m="4224400">certainly</span> <span m="4224760">you</span>
  <span m="4224880">cannot</span> <span m="4225750">do</span> <span m="4225990">substantially</span>
  <span m="4226770">better</span> <span m="4227550">than</span> <span m="4228540">what</span>
  <span m="4228700">the</span> <span m="4228780">proof</span> <span m="4229050">gives.</span></p><p><span
  m="4231530">So</span> <span m="4231930">Szemeredi's</span> <span m="4232520">regularity</span>
  <span m="4233030">lemma</span> <span m="4233900">is</span> <span m="4234500">an</span>
  <span m="4234620">extremely</span> <span m="4235100">powerful</span> <span m="4235700">tool.</span>
  <span m="4236600">And</span> <span m="4236720">we'll</span> <span m="4236870">see</span>
  <span m="4237080">applications</span> <span m="4238280">that</span> <span m="4239090">are</span>
  <span m="4239660">basically</span> <span m="4241550">very</span> <span m="4241820">difficult</span>
  <span m="4242210">to</span> <span m="4242300">prove.</span> <span m="4242560">And</span>
  <span m="4242810">for</span> <span m="4243230">some</span> <span m="4243470">of</span>
  <span m="4243530">these</span> <span m="4243680">applications,</span> <span m="4244260">we</span>
  <span m="4244310">don't</span> <span m="4244520">really</span> <span m="4244790">know</span>
  <span m="4244970">other</span> <span m="4245180">proofs</span> <span m="4245960">except</span>
  <span m="4246290">using</span> <span m="4246530">Szemeredi's</span> <span m="4247010">regularity</span>
  <span m="4247550">lemma.</span></p><p><span m="4248760">But</span> <span m="4248930">on</span>
  <span m="4249020">the</span> <span m="4249110">other</span> <span m="4249260">hand,</span>
  <span m="4249440">it</span> <span m="4249530">gives</span> <span m="4249800">terrible</span>
  <span m="4250670">quantitative</span> <span m="4251300">bounds.</span> <span m="4252680">So</span>
  <span m="4253190">there</span> <span m="4253430">is</span> <span m="4254300">a</span>
  <span m="4254390">lot</span> <span m="4254690">of</span> <span m="4254840">interest</span>
  <span m="4256010">in</span> <span m="4256280">combinatorics</span> <span m="4257450">where</span>
  <span m="4258500">once</span> <span m="4258800">you</span> <span m="4258920">see</span>
  <span m="4259220">a</span> <span m="4259280">proof</span> <span m="4259640">that</span>
  <span m="4259790">requires</span> <span m="4260300">Szemeredi's</span> <span m="4260870">regularity</span>
  <span m="4261400">lemma,</span> <span m="4261650">or that</span> <span m="4261800">is</span>
  <span m="4261950">first</span> <span m="4262220">proved</span> <span m="4262670">using</span>
  <span m="4263060">this</span> <span m="4263240">technique,</span> <span m="4264020">to</span>
  <span m="4264140">ask</span> <span m="4264740">can</span> <span m="4264960">it</span>
  <span m="4265040">be</span> <span m="4265160">used</span> <span m="4265580">using</span>
  <span m="4266030">some</span> <span m="4266690">other</span> <span m="4266930">technique?</span>
  <span m="4267870">In</span> <span m="4267960">fact,</span> <span m="4268280">Szemeredi</span>
  <span m="4268970">himself</span> <span m="4270230">has</span> <span m="4270410">worked</span>
  <span m="4270800">a</span> <span m="4270860">lot</span> <span m="4271550">in</span>
  <span m="4271670">that</span> <span m="4271820">direction,</span> <span m="4272270">trying</span>
  <span m="4272510">to</span> <span m="4272600">get</span> <span m="4272810">rid</span>
  <span m="4272990">of</span> <span m="4273110">the</span> <span m="4273200">uses</span>
  <span m="4274010">of</span> <span m="4274190">his</span> <span m="4274390">lemma.</span>
  <span m="4279500">Any</span> <span m="4279710">questions?</span></p><p><span m="4282410">AUDIENCE:</span>
  <span m="4282436">How</span> <span m="4282462">could</span> <span m="4282490">you</span>
  <span m="4282770">modify</span> <span m="4283040">it</span> <span m="4283310">for</span>
  <span m="4283762">equipartitions?</span></p><p><span m="4285120">YUFEI ZHAO:</span>
  <span m="4285255">OK,</span> <span m="4285390">great.</span> <span m="4286170">Question
  is,</span> <span m="4286500">how</span> <span m="4286710">can</span> <span m="4286860">we</span>
  <span m="4286950">modify</span> <span m="4287380">it</span> <span m="4287430">for</span>
  <span m="4287580">equipartitions?</span> <span m="4289140">So</span> <span m="4289260">let's</span>
  <span m="4289410">talk</span> <span m="4289590">about</span> <span m="4289770">that.</span>
  <span m="4290080">So</span> <span m="4290970">it's</span> <span m="4291410">a</span>
  <span m="4291600">fantastic</span> <span m="4292080">question.</span> <span m="4292370">So</span>
  <span m="4292530">look</span> <span m="4292770">at</span> <span m="4292860">this</span>
  <span m="4293010">proof</span> <span m="4293580">and</span> <span m="4293700">see</span>
  <span m="4293860">what</span> <span m="4294120">can</span> <span m="4294300">we</span>
  <span m="4294420">do</span> <span m="4294900">if</span> <span m="4295050">we</span>
  <span m="4295170">really</span> <span m="4295440">want</span> <span m="4296700">all</span>
  <span m="4296820">the</span> <span m="4296910">parts</span> <span m="4297300">to</span>
  <span m="4297450">have</span> <span m="4297720">roughly</span> <span m="4298050">the</span>
  <span m="4298170">same</span> <span m="4298440">size,</span> <span m="4299850">let's</span>
  <span m="4300000">say</span> <span m="4300240">differing</span> <span m="4300600">by</span>
  <span m="4300760">at most</span> <span m="4301100">1.</span></p><p><span m="4320800">So</span>
  <span m="4321540">how</span> <span m="4321810">to</span> <span m="4321960">make</span>
  <span m="4324200">the</span> <span m="4324930">epsilon</span> <span m="4325830">regular</span>
  <span m="4326250">partition</span> <span m="4328980">equitable?</span> <span m="4334920">Any</span>
  <span m="4335200">guesses?</span> <span m="4336220">Any</span> <span m="4336430">attempts</span>
  <span m="4336880">on</span> <span m="4337000">what</span> <span m="4337150">we</span>
  <span m="4337300">can</span> <span m="4337450">do?</span></p><p><span m="4338810">I</span>
  <span m="4338910">mean,</span> <span m="4339110">basically</span> <span m="4339280">it's</span>
  <span m="4339370">going</span> <span m="4339520">to</span> <span m="4339580">follow</span>
  <span m="4341110">this</span> <span m="4341410">proof.</span> <span m="4341920">As</span>
  <span m="4342070">I</span> <span m="4342130">said,</span> <span m="4342340">the</span>
  <span m="4342460">spirit</span> <span m="4343030">of</span> <span m="4343130">Szemeredi's</span>
  <span m="4343600">regularity</span> <span m="4344140">lemma</span> <span m="4344410">is</span>
  <span m="4344590">what</span> <span m="4344770">I've</span> <span m="4344890">shown</span>
  <span m="4345100">you.</span> <span m="4345630">But</span> <span m="4345850">the</span>
  <span m="4345940">details</span> <span m="4346480">and</span> <span m="4346570">executions</span>
  <span m="4347560">may</span> <span m="4347890">vary</span> <span m="4348280">somewhat</span>
  <span m="4348640">depending</span> <span m="4349000">on</span> <span m="4349100">the</span>
  <span m="4349160">specific</span> <span m="4349660">purpose</span> <span m="4350020">you</span>
  <span m="4350140">have</span> <span m="4350320">in</span> <span m="4350380">mind.</span>
  <span m="4351210">Yeah.</span></p><p><span m="4351792">AUDIENCE:</span> <span m="4351952">Can
  we</span> <span m="4352112">just</span> <span m="4352274">add--</span> <span m="4353238">[INAUDIBLE]</span>
  <span m="4353720">add</span> <span m="4354202">things</span> <span m="4354684">to
  the smaller part</span> <span m="4355166">because</span> <span m="4355648">we</span>
  <span m="4356130">know</span> <span m="4356612">that--</span> <span m="4357094">by
  the</span> <span m="4357576">fact</span> <span m="4358058">that it's not</span>
  <span m="4358540">[INAUDIBLE]</span> <span m="4359022">that parts</span> <span m="4359504">aren't
  too</span> <span m="4359986">small?</span></p><p><span m="4361440">YUFEI ZHAO:</span>
  <span m="4361490">OK,</span> <span m="4362490">so</span> <span m="4362640">you're</span>
  <span m="4362790">saying</span> <span m="4363060">we're</span> <span m="4363420">going</span>
  <span m="4363630">to</span> <span m="4363780">add</span> <span m="4364080">something</span>
  <span m="4364510">or</span> <span m="4364560">to</span> <span m="4364650">massage</span>
  <span m="4365190">the</span> <span m="4365280">partition</span> <span m="4365760">to</span>
  <span m="4365910">make</span> <span m="4366210">it</span> <span m="4366430">epsilon--</span></p><p><span
  m="4366790">AUDIENCE:</span> <span m="4366928">Add</span> <span m="4367066">vertices</span>
  <span m="4367206">to the smaller</span> <span m="4367622">parts of the</span> <span
  m="4368038">partition.</span></p><p><span m="4368870">YUFEI ZHAO:</span> <span m="4369050">Add</span>
  <span m="4369230">vertices</span> <span m="4369590">to</span> <span m="4369680">the</span>
  <span m="4369770">smaller</span> <span m="4370190">parts</span> <span m="4370550">of</span>
  <span m="4370610">the</span> <span m="4370670">partition,</span> <span m="4371160">now</span>
  <span m="4371570">when</span> <span m="4371960">are</span> <span m="4372080">you</span>
  <span m="4372170">going</span> <span m="4372380">to</span> <span m="4372470">do</span>
  <span m="4372590">that?</span></p><p><span m="4373828">AUDIENCE:</span> <span m="4374077">When</span>
  <span m="4374327">they're--</span> <span m="4374826">like</span> <span m="4375325">so
  you</span> <span m="4375824">do the refinement,</span> <span m="4376323">then</span>
  <span m="4376822">when they're</span> <span m="4377321">not</span> <span m="4377820">[INAUDIBLE]</span></p><p><span
  m="4378820">YUFEI ZHAO:</span> <span m="4378880">So</span> <span m="4378940">you</span>
  <span m="4379060">want</span> <span m="4379240">to</span> <span m="4379300">do</span>
  <span m="4379420">this</span> <span m="4379600">at</span> <span m="4379690">every</span>
  <span m="4379900">stage</span> <span m="4380350">of</span> <span m="4380470">the</span>
  <span m="4381010">process.</span></p><p><span m="4381490">AUDIENCE:</span> <span
  m="4381705">Yes.</span> <span m="4381920">[INAUDIBLE]</span></p><p><span m="4384500">YUFEI
  ZHAO:</span> <span m="4384545">I</span> <span m="4384590">like</span> <span m="4384740">that</span>
  <span m="4384860">idea.</span> <span m="4386100">So</span> <span m="4386960">here's</span>
  <span m="4387230">what</span> <span m="4387350">we're</span> <span m="4387470">going</span>
  <span m="4387650">to</span> <span m="4387740">do.</span> <span m="4389920">So</span>
  <span m="4390540">we</span> <span m="4390690">still</span> <span m="4390900">run</span>
  <span m="4391110">the</span> <span m="4391170">same</span> <span m="4391380">process.</span>
  <span m="4392410">So</span> <span m="4392460">we're</span> <span m="4392550">going</span>
  <span m="4392700">to</span> <span m="4392760">have</span> <span m="4392940">this</span>
  <span m="4393090">P,</span> <span m="4393360">which</span> <span m="4393570">is</span>
  <span m="4393690">the</span> <span m="4393780">current</span> <span m="4394170">partition.</span>
  <span m="4395760">So</span> <span m="4395820">I have</span> <span m="4398690">current</span>
  <span m="4399260">partition.</span></p><p><span m="4400980">And</span> <span m="4401260">as</span>
  <span m="4401510">before,</span> <span m="4403340">we</span> <span m="4403490">initially</span>
  <span m="4404300">have</span> <span m="4404600">it</span> <span m="4404730">as</span>
  <span m="4405020">either</span> <span m="4405380">the</span> <span m="4405530">trivial</span>
  <span m="4405950">partition,</span> <span m="4406460">if</span> <span m="4406580">you</span>
  <span m="4406670">like,</span> <span m="4407420">or</span> <span m="4408860">m</span>
  <span m="4409820">arbitrary</span> <span m="4411230">equitable</span> <span m="4411740">parts.</span>
  <span m="4417440">Start</span> <span m="4417710">with</span> <span m="4417860">something</span>
  <span m="4418190">where</span> <span m="4418370">you</span> <span m="4418460">don't</span>
  <span m="4419030">really</span> <span m="4419210">care</span> <span m="4419720">about</span>
  <span m="4419960">anything</span> <span m="4420290">except</span> <span m="4420590">for</span>
  <span m="4420680">the</span> <span m="4420770">size.</span> <span m="4421940">And</span>
  <span m="4422120">you</span> <span m="4422240">run</span> <span m="4423500">basically</span>
  <span m="4423920">the</span> <span m="4424040">same</span> <span m="4424310">proof,</span>
  <span m="4426080">where</span> <span m="4426890">if</span> <span m="4427610">your</span>
  <span m="4427780">P</span> <span m="4428085">is</span> <span m="4428840">not</span>
  <span m="4429500">epsilon</span> <span m="4429980">regular,</span> <span m="4433000">then</span>
  <span m="4434320">do</span> <span m="4434650">what</span> <span m="4435190">we've</span>
  <span m="4435400">done</span> <span m="4435580">before,</span> <span m="4436010">so</span>
  <span m="4436390">basically</span> <span m="4436750">exactly</span> <span m="4437110">the</span>
  <span m="4437200">same</span> <span m="4437470">thing.</span></p><p><span m="4438160">We</span>
  <span m="4438280">refine</span> <span m="4440260">P</span> <span m="4442930">using</span>
  <span m="4443350">pairs</span> <span m="4445900">witnessing</span> <span m="4450490">regularity,</span>
  <span m="4453590">same</span> <span m="4453920">as</span> <span m="4454040">the</span>
  <span m="4454100">proof</span> <span m="4454400">that</span> <span m="4454520">we</span>
  <span m="4454670">just</span> <span m="4454850">did.</span> <span m="4455750">And</span>
  <span m="4455840">now</span> <span m="4456020">we</span> <span m="4456170">need</span>
  <span m="4456320">to</span> <span m="4456410">do</span> <span m="4456560">something</span>
  <span m="4456920">a</span> <span m="4456980">little</span> <span m="4457220">bit</span>
  <span m="4457340">more</span> <span m="4457910">to</span> <span m="4458630">obtain</span>
  <span m="4459650">equitability.</span> <span m="4461480">And</span> <span m="4461600">what</span>
  <span m="4461750">we</span> <span m="4461860">will</span> <span m="4461990">do</span>
  <span m="4462770">is</span> <span m="4463580">right</span> <span m="4463850">after--</span>
  <span m="4464660">so</span> <span m="4464930">each</span> <span m="4465170">step</span>
  <span m="4465440">in</span> <span m="4465550">iteration,</span> <span m="4466250">right</span>
  <span m="4466490">after</span> <span m="4466790">we</span> <span m="4467270">do</span>
  <span m="4467480">this</span> <span m="4467660">refinement,</span> <span m="4469180">so</span>
  <span m="4469340">after</span> <span m="4469640">we</span> <span m="4470720">cut</span>
  <span m="4470960">up</span> <span m="4471560">our</span> <span m="4471680">graph</span>
  <span m="4474100">where</span> <span m="4475160">maybe</span> <span m="4475370">some</span>
  <span m="4475640">of</span> <span m="4475700">the</span> <span m="4475790">parts</span>
  <span m="4476180">are</span> <span m="4476660">really</span> <span m="4476840">tiny,</span>
  <span m="4483820">let's</span> <span m="4484030">massage</span> <span m="4484600">the</span>
  <span m="4484690">partitions</span> <span m="4485110">somewhat</span> <span m="4485560">to</span>
  <span m="4485680">make</span> <span m="4485920">them</span> <span m="4486130">equitable.</span></p><p><span
  m="4487210">And</span> <span m="4487360">to</span> <span m="4487480">make</span>
  <span m="4487690">our</span> <span m="4487810">life</span> <span m="4488170">a</span>
  <span m="4488200">little</span> <span m="4488410">bit</span> <span m="4488560">easier,</span>
  <span m="4491000">we</span> <span m="4491050">can</span> <span m="4491230">refine</span>
  <span m="4493360">the</span> <span m="4493480">partition</span> <span m="4494410">somewhat</span>
  <span m="4494920">further</span> <span m="4496130">to</span> <span m="4496270">chop</span>
  <span m="4496570">it</span> <span m="4496690">up</span> <span m="4496840">into</span>
  <span m="4498220">somewhat</span> <span m="4498760">smaller</span> <span m="4499270">resolution.</span>
  <span m="4500720">And</span> <span m="4501160">this</span> <span m="4501340">part,</span>
  <span m="4501970">you</span> <span m="4502060">can</span> <span m="4502180">really</span>
  <span m="4502600">do</span> <span m="4502780">it</span> <span m="4503050">either</span>
  <span m="4503290">arbitrarily</span> <span m="4503980">or</span> <span m="4504070">randomly.</span>
  <span m="4506950">Some</span> <span m="4509140">ways</span> <span m="4509440">may</span>
  <span m="4509620">be</span> <span m="4509800">slightly</span> <span m="4510100">easier</span>
  <span m="4510400">to</span> <span m="4510520">execute,</span> <span m="4511030">but</span>
  <span m="4511240">it</span> <span m="4511300">doesn't</span> <span m="4511600">really</span>
  <span m="4511780">matter</span> <span m="4512080">how</span> <span m="4512260">you</span>
  <span m="4512380">do</span> <span m="4512530">it.</span> <span m="4512680">It's</span>
  <span m="4512860">fairly</span> <span m="4513250">robust.</span></p><p><span m="4513970">You</span>
  <span m="4514120">refine</span> <span m="4514570">it</span> <span m="4514690">further.</span>
  <span m="4516460">And</span> <span m="4518940">basically,</span> <span m="4519240">I</span>
  <span m="4519330">want</span> <span m="4519480">to</span> <span m="4519570">make</span>
  <span m="4519750">it</span> <span m="4519870">equitable.</span> <span m="4520500">Sometimes,</span>
  <span m="4521880">you</span> <span m="4521970">can</span> <span m="4522120">just</span>
  <span m="4522300">do</span> <span m="4522450">that</span> <span m="4522630">by</span>
  <span m="4522780">refining,</span> <span m="4523260">but</span> <span m="4523590">maybe</span>
  <span m="4523890">if</span> <span m="4524010">you</span> <span m="4524070">have</span>
  <span m="4524220">some</span> <span m="4524400">really</span> <span m="4524640">small</span>
  <span m="4524970">parts,</span> <span m="4525810">then</span> <span m="4526170">you</span>
  <span m="4526290">might</span> <span m="4526410">need</span> <span m="4526530">to</span>
  <span m="4526620">move</span> <span m="4526860">some</span> <span m="4527070">vertices</span>
  <span m="4527550">around,</span> <span m="4528300">so</span> <span m="4529190">I</span>
  <span m="4529600">call</span> <span m="4530010">that</span> <span m="4530250">&quot;rebalancing.&quot;</span>
  <span m="4534040">So</span> <span m="4534670">move</span> <span m="4535120">and</span>
  <span m="4535270">merge</span> <span m="4536950">some</span> <span m="4537190">vertices,</span>
  <span m="4540220">but</span> <span m="4540520">only</span> <span m="4540730">a</span>
  <span m="4540790">very</span> <span m="4540970">small</span> <span m="4541300">number</span>
  <span m="4541600">of</span> <span m="4541660">vertices,</span> <span m="4544060">to</span>
  <span m="4544210">make</span> <span m="4544660">equitable.</span></p><p><span m="4550960">So</span>
  <span m="4551050">you</span> <span m="4551170">run</span> <span m="4551350">this</span>
  <span m="4551500">loop</span> <span m="4553350">until</span> <span m="4553950">you</span>
  <span m="4554100">find</span> <span m="4554490">that</span> <span m="4554720">your</span>
  <span m="4554870">partition</span> <span m="4555330">is</span> <span m="4555760">epsilon</span>
  <span m="4555950">regular.</span> <span m="4556380">Then</span> <span m="4556510">you're</span>
  <span m="4556660">done.</span> <span m="4558000">Whenever</span> <span m="4558540">you</span>
  <span m="4558870">run</span> <span m="4559080">this</span> <span m="4559230">loop,</span>
  <span m="4559410">because</span> <span m="4559830">we're</span> <span m="4559950">doing</span>
  <span m="4560520">the</span> <span m="4560640">second</span> <span m="4560970">step,</span>
  <span m="4561510">your</span> <span m="4561660">partition</span> <span m="4562080">is</span>
  <span m="4562230">always</span> <span m="4562620">going</span> <span m="4562890">to</span>
  <span m="4562980">be</span> <span m="4563880">equitable.</span></p><p><span m="4565900">But</span>
  <span m="4566050">we</span> <span m="4566200">now</span> <span m="4566440">need</span>
  <span m="4566590">to</span> <span m="4566680">control</span> <span m="4567340">the</span>
  <span m="4568000">energy</span> <span m="4568690">again</span> <span m="4569110">to</span>
  <span m="4569530">limit</span> <span m="4569890">the</span> <span m="4569980">number</span>
  <span m="4570520">of</span> <span m="4571030">steps.</span> <span m="4572260">And</span>
  <span m="4572380">the</span> <span m="4572470">point</span> <span m="4572800">here</span>
  <span m="4573070">is</span> <span m="4573220">that</span> <span m="4573400">the</span>
  <span m="4573760">first</span> <span m="4574240">part</span> <span m="4574990">still</span>
  <span m="4575330">is</span> <span m="4575460">exactly</span> <span m="4575950">the</span>
  <span m="4576070">same</span> <span m="4576310">as</span> <span m="4576430">before,</span>
  <span m="4577110">where</span> <span m="4577210">the</span> <span m="4577300">energy</span>
  <span m="4580040">goes</span> <span m="4580340">up</span> <span m="4580850">by</span>
  <span m="4581270">at</span> <span m="4581360">least</span> <span m="4582680">epsilon</span>
  <span m="4583280">to</span> <span m="4583460">the</span> <span m="4583550">minus</span>
  <span m="4583920">5.</span> <span m="4585720">But</span> <span m="4585870">the</span>
  <span m="4585930">second</span> <span m="4586260">part,</span> <span m="4586530">the</span>
  <span m="4586590">energy</span> <span m="4586920">might</span> <span m="4587250">go</span>
  <span m="4587460">down,</span> <span m="4588360">because</span> <span m="4588600">we're</span>
  <span m="4588720">no</span> <span m="4588900">longer</span> <span m="4589200">refining,</span>
  <span m="4590190">just</span> <span m="4590430">refining.</span> <span m="4590850">Because</span>
  <span m="4591090">we're</span> <span m="4591210">doing</span> <span m="4591420">some</span>
  <span m="4591720">rebalancing.</span></p><p><span m="4594270">But</span> <span m="4594420">you</span>
  <span m="4594510">can</span> <span m="4594630">do</span> <span m="4594780">it</span>
  <span m="4594830">in</span> <span m="4594930">such</span> <span m="4595110">a</span>
  <span m="4595140">way</span> <span m="4595350">that</span> <span m="4595560">the</span>
  <span m="4595710">amount</span> <span m="4596100">of</span> <span m="4596220">rebalancing</span>
  <span m="4596880">that</span> <span m="4597000">you</span> <span m="4597120">do</span>
  <span m="4597450">is</span> <span m="4598020">really</span> <span m="4598350">small.</span>
  <span m="4599220">You're</span> <span m="4599370">not</span> <span m="4599730">actually</span>
  <span m="4600150">changing</span> <span m="4600630">the</span> <span m="4600720">energy</span>
  <span m="4601080">by</span> <span m="4601230">so</span> <span m="4601470">much.</span>
  <span m="4602100">So</span> <span m="4603090">I'll</span> <span m="4603300">just</span>
  <span m="4604580">hand</span> <span m="4604820">wave</span> <span m="4605110">here,</span>
  <span m="4605590">and</span> <span m="4605710">say</span> <span m="4605980">that</span>
  <span m="4606160">we</span> <span m="4606310">can</span> <span m="4606430">do</span>
  <span m="4606580">this</span> <span m="4606790">in</span> <span m="4606850">such</span>
  <span m="4607090">a</span> <span m="4607120">way</span> <span m="4607840">where</span>
  <span m="4608080">the</span> <span m="4608230">energy</span> <span m="4610730">might</span>
  <span m="4612980">go</span> <span m="4613160">down,</span> <span m="4615590">but</span>
  <span m="4615800">only</span> <span m="4616160">a</span> <span m="4616190">little</span>
  <span m="4616430">bit.</span></p><p><span m="4622240">So</span> <span m="4622360">you're</span>
  <span m="4622450">only</span> <span m="4622690">changing</span> <span m="4623110">a</span>
  <span m="4623170">very</span> <span m="4623380">small</span> <span m="4623770">number</span>
  <span m="4624040">of</span> <span m="4624100">vertices,</span> <span m="4625180">very</span>
  <span m="4625420">small</span> <span m="4625750">fraction</span> <span m="4626230">of</span>
  <span m="4626290">vertices.</span> <span m="4627430">So</span> <span m="4627520">if</span>
  <span m="4627610">you</span> <span m="4627670">change</span> <span m="4627970">only</span>
  <span m="4628150">an</span> <span m="4628240">epsilon</span> <span m="4628780">fraction</span>
  <span m="4629230">of</span> <span m="4629290">vertices,</span> <span m="4629950">you</span>
  <span m="4630070">don't</span> <span m="4630280">expect</span> <span m="4630820">the</span>
  <span m="4630940">energy,</span> <span m="4631960">which</span> <span m="4632200">is</span>
  <span m="4632380">something</span> <span m="4633130">that</span> <span m="4633310">comes</span>
  <span m="4633670">out</span> <span m="4633850">of</span> <span m="4633970">summing</span>
  <span m="4634510">pairs</span> <span m="4634900">of</span> <span m="4635830">vertex</span>
  <span m="4636190">parts,</span> <span m="4637000">to</span> <span m="4637120">change</span>
  <span m="4637480">by</span> <span m="4637630">all</span> <span m="4637780">that</span>
  <span m="4637960">much.</span> <span m="4641540">So</span> <span m="4642580">putting</span>
  <span m="4642910">these</span> <span m="4643150">two</span> <span m="4643300">together,</span>
  <span m="4644020">you</span> <span m="4644110">see</span> <span m="4644320">that</span>
  <span m="4644470">the</span> <span m="4644590">energy</span> <span m="4646840">still</span>
  <span m="4647170">goes</span> <span m="4647470">up</span> <span m="4647950">by,</span>
  <span m="4648650">let's</span> <span m="4648730">say,</span> <span m="4648980">at</span>
  <span m="4649080">least</span> <span m="4649570">1/2</span> <span m="4650650">of</span>
  <span m="4652060">epsilon</span> <span m="4653140">to</span> <span m="4653260">the</span>
  <span m="4653350">5th</span> <span m="4653590">power.</span></p><p><span m="4655780">And</span>
  <span m="4655890">so</span> <span m="4656010">then,</span> <span m="4656430">the</span>
  <span m="4656550">rest</span> <span m="4656820">of</span> <span m="4656880">the</span>
  <span m="4656970">proof</span> <span m="4657300">runs</span> <span m="4657630">the</span>
  <span m="4657720">same</span> <span m="4657990">as</span> <span m="4658140">before.</span>
  <span m="4659800">You</span> <span m="4660040">finish</span> <span m="4660640">in</span>
  <span m="4661000">some</span> <span m="4661240">bounded</span> <span m="4661540">number</span>
  <span m="4661840">of</span> <span m="4661930">steps.</span> <span m="4662590">And</span>
  <span m="4662710">you</span> <span m="4662800">result</span> <span m="4663250">in</span>
  <span m="4663400">an</span> <span m="4663610">equitable</span> <span m="4664390">partition</span>
  <span m="4664930">that's</span> <span m="4665260">epsilon</span> <span m="4665650">regular.</span></p><p><span
  m="4666990">I</span> <span m="4667060">don't</span> <span m="4667180">want</span>
  <span m="4667360">to</span> <span m="4667450">belabor</span> <span m="4667930">the</span>
  <span m="4668020">details.</span> <span m="4668790">I mean, here,</span> <span m="4669160">there's</span>
  <span m="4669310">some</span> <span m="4669490">things</span> <span m="4669730">to</span>
  <span m="4669820">check,</span> <span m="4670150">but</span> <span m="4670390">it's,</span>
  <span m="4671050">I</span> <span m="4671140">think,</span> <span m="4671350">fairly</span>
  <span m="4671710">routine.</span> <span m="4672960">It's</span> <span m="4673330">is</span>
  <span m="4673840">more</span> <span m="4674050">of</span> <span m="4674170">an</span>
  <span m="4674320">exercise</span> <span m="4674860">in</span> <span m="4675220">technical</span>
  <span m="4675670">details.</span></p><p><span m="4676960">But</span> <span m="4677950">the</span>
  <span m="4678040">thing</span> <span m="4678280">that</span> <span m="4678490">actually</span>
  <span m="4678850">is</span> <span m="4679060">somewhat</span> <span m="4679840">important</span>
  <span m="4681070">is</span> <span m="4682120">there's</span> <span m="4682330">a</span>
  <span m="4682390">wrong</span> <span m="4682690">way</span> <span m="4682840">to</span>
  <span m="4682960">do</span> <span m="4683110">this.</span> <span m="4684860">I</span>
  <span m="4684950">just</span> <span m="4685100">want</span> <span m="4685220">to</span>
  <span m="4685280">point</span> <span m="4685490">out</span> <span m="4685550">that</span>
  <span m="4685670">what's</span> <span m="4685880">the</span> <span m="4685940">wrong</span>
  <span m="4686210">way</span> <span m="4686360">to</span> <span m="4686450">do</span>
  <span m="4686600">this,</span> <span m="4686780">is</span> <span m="4686920">that</span>
  <span m="4687020">you</span> <span m="4687200">apply</span> <span m="4687650">regularity</span>
  <span m="4688220">lemma,</span> <span m="4689610">and</span> <span m="4689710">you</span>
  <span m="4689800">think</span> <span m="4690300">now</span> <span m="4690580">it</span>
  <span m="4690670">has</span> <span m="4690880">something</span> <span m="4691150">that's</span>
  <span m="4691360">epsilon</span> <span m="4691720">regular.</span> <span m="4692650">Then</span>
  <span m="4693160">I</span> <span m="4693280">massage</span> <span m="4693610">it</span>
  <span m="4693940">to</span> <span m="4694060">try</span> <span m="4694300">to</span>
  <span m="4694420">make</span> <span m="4694690">it</span> <span m="4695770">equitable</span>
  <span m="4696370">at</span> <span m="4696460">the</span> <span m="4696610">end.</span></p><p><span
  m="4698350">And</span> <span m="4698810">so</span> <span m="4699030">if I</span>
  <span m="4700070">don't</span> <span m="4700340">look</span> <span m="4700550">into</span>
  <span m="4700700">the</span> <span m="4700790">proof,</span> <span m="4701040">I</span>
  <span m="4701150">just</span> <span m="4701360">look</span> <span m="4701510">at</span>
  <span m="4701600">a</span> <span m="4701660">statement</span> <span m="4702080">of</span>
  <span m="4702260">Szemeredi's</span> <span m="4702690">regularity</span> <span m="4703270">lemma,</span>
  <span m="4703500">and I</span> <span m="4703880">get</span> <span m="4704000">something</span>
  <span m="4704240">that's</span> <span m="4704420">epsilon</span> <span m="4704780">regular,</span>
  <span m="4705490">I</span> <span m="4705590">say</span> <span m="4705750">I'm</span>
  <span m="4705890">just</span> <span m="4706040">going</span> <span m="4706160">to</span>
  <span m="4706310">divide</span> <span m="4706670">things</span> <span m="4706880">up</span>
  <span m="4707000">a</span> <span m="4707030">little</span> <span m="4707180">bit</span>
  <span m="4707300">further,</span> <span m="4708710">that</span> <span m="4708950">doesn't</span>
  <span m="4709220">work.</span> <span m="4710000">Because</span> <span m="4710480">the</span>
  <span m="4710570">property</span> <span m="4711200">of</span> <span m="4711320">being</span>
  <span m="4711740">epsilon</span> <span m="4712280">regular</span> <span m="4713030">is</span>
  <span m="4713210">actually</span> <span m="4713690">not</span> <span m="4713990">preserved</span>
  <span m="4714530">under</span> <span m="4714830">refinement.</span> <span m="4717340">So</span>
  <span m="4717460">look</span> <span m="4717640">at</span> <span m="4717700">the</span>
  <span m="4717790">definition.</span></p><p><span m="4718560">You</span> <span m="4718660">have</span>
  <span m="4718780">something</span> <span m="4719050">that's</span> <span m="4719230">epsilon</span>
  <span m="4719620">regular.</span> <span m="4720010">You</span> <span m="4720130">refine</span>
  <span m="4720640">the</span> <span m="4720730">partition.</span> <span m="4721450">If</span>
  <span m="4721560">might</span> <span m="4721900">fail</span> <span m="4722350">to</span>
  <span m="4722470">be</span> <span m="4722740">epsilon</span> <span m="4723220">regular.</span></p><p><span
  m="4725960">So</span> <span m="4726140">you</span> <span m="4726260">really</span>
  <span m="4726500">have</span> <span m="4726620">to</span> <span m="4726740">take</span>
  <span m="4726950">into</span> <span m="4727130">the</span> <span m="4727220">proof</span>
  <span m="4728060">to</span> <span m="4728270">get</span> <span m="4728710">equitability.</span>
  <span m="4731290">So</span> <span m="4731410">just</span> <span m="4731590">to</span>
  <span m="4731680">repeat,</span> <span m="4732430">a</span> <span m="4732490">wrong</span>
  <span m="4732820">way</span> <span m="4733030">to</span> <span m="4733150">try</span>
  <span m="4733330">to</span> <span m="4733450">get</span> <span m="4733690">equitability</span>
  <span m="4734220">is</span> <span m="4734380">to</span> <span m="4734500">apply</span>
  <span m="4734890">regularity</span> <span m="4735430">lemma,</span> <span m="4736000">and</span>
  <span m="4736150">at</span> <span m="4736270">the</span> <span m="4736390">end,</span>
  <span m="4736930">try</span> <span m="4737260">to</span> <span m="4737410">massage</span>
  <span m="4737840">it</span> <span m="4737950">to</span> <span m="4738580">get</span>
  <span m="4738850">equitable.</span> <span m="4739420">That</span> <span m="4739600">doesn't</span>
  <span m="4739870">work.</span> <span m="4741820">Next</span> <span m="4742090">time,</span>
  <span m="4742360">I</span> <span m="4742450">will</span> <span m="4742570">show</span>
  <span m="4742840">you</span> <span m="4743290">how</span> <span m="4743620">to</span>
  <span m="4743860">apply</span> <span m="4744600">Szemeredi's</span> <span m="4745390">regularity</span>
  <span m="4745690">lemma.</span></p>
type: course
uid: 49f44a942ceebe7751e2353ccb96a00d

---
None