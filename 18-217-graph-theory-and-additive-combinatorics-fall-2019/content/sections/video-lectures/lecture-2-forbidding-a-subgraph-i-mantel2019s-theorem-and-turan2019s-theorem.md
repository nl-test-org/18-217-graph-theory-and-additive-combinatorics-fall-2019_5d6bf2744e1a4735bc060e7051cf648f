---
about_this_resource_text: "<p><strong>Description:</strong> Which triangle-free graph\
  \ has the maximum number of edges given the number of vertices? Professor Zhao shows\
  \ the class Mantel&rsquo;s theorem, which says that the answer is a complete bipartite\
  \ graph. He also discusses generalizations: Tur\xE1n&rsquo;s theorem (for cliques)\
  \ and the Erd\u0151s&ndash;Stone&ndash;Simonovits theorem (for general subgraphs).</p>\
  \ <p><strong>Instructor:</strong> Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: YAo1sd4kuOQ
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  title: Video-YouTube-Stream
  type: Video
  uid: 0f8687464bbb27f383cec9f7fec60230
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/YAo1sd4kuOQ/default.jpg
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 550f2daa6c453ecf5907a77e14439a10
- id: 3Play-3PlayYouTubeid-MP4
  media_location: YAo1sd4kuOQ
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 1269716967d47a11a49b1da42f53bb62
- id: YAo1sd4kuOQ.srt
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-2-forbidding-a-subgraph-i-mantel2019s-theorem-and-turan2019s-theorem/YAo1sd4kuOQ.srt
  title: 3play caption file
  type: null
  uid: 4054ccadf06edf2ca2c2569dc5adafea
- id: YAo1sd4kuOQ.pdf
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-2-forbidding-a-subgraph-i-mantel2019s-theorem-and-turan2019s-theorem/YAo1sd4kuOQ.pdf
  title: 3play pdf file
  type: null
  uid: 857707837d40fa189a8e04ae8f462932
- id: Caption-3Play YouTube id-SRT
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 39ecf77142e678b66130e3d141d5891e
- id: Transcript-3Play YouTube id-PDF
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ba9382a43bcda9230b89307f6c6a4d23
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec02_300k.mp4
  parent_uid: aa8242411777a91b4d6684e6523f35b7
  title: Video-Internet Archive-MP4
  type: Video
  uid: 00cc2a34b9950976fa997360b82d7799
inline_embed_id: 22113283lecture2forbiddingasubgraphimantelstheoremandturnstheorem69603858
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-2-forbidding-a-subgraph-i-mantel2019s-theorem-and-turan2019s-theorem
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-2-forbidding-a-subgraph-i-mantel2019s-theorem-and-turan2019s-theorem
template_type: Tabbed
title: "Lecture 2: Forbidding a Subgraph I: Mantel\u2019s Theorem and Tur\xE1n\u2019\
  s Theorem"
transcript: "<p><span m=\"19325\">YUFEI ZHAO:</span> <span m=\"19482\">So</span> <span\
  \ m=\"19640\">the</span> <span m=\"19730\">first</span> <span m=\"20000\">topic</span>\
  \ <span m=\"20410\">that</span> <span m=\"20570\">I</span> <span m=\"20630\">want</span>\
  \ <span m=\"20810\">to</span> <span m=\"20870\">discuss</span> <span m=\"23430\"\
  >in</span> <span m=\"23520\">this</span> <span m=\"23690\">course</span> <span m=\"\
  23990\">is</span> <span m=\"24140\">extremal</span> <span m=\"24650\">graph</span>\
  \ <span m=\"24980\">theory.</span> <span m=\"38980\">And</span> <span m=\"39400\"\
  >in</span> <span m=\"39490\">particular,</span> <span m=\"40870\">there</span> <span\
  \ m=\"40950\">is</span> <span m=\"41080\">a</span> <span m=\"41650\">whole</span>\
  \ <span m=\"41890\">class</span> <span m=\"42220\">of</span> <span m=\"42280\">problems</span>\
  \ <span m=\"43030\">which</span> <span m=\"43240\">have</span> <span m=\"43390\"\
  >to</span> <span m=\"43480\">do</span> <span m=\"43630\">with</span> <span m=\"\
  44290\">what</span> <span m=\"44470\">happens</span> <span m=\"45310\">if</span>\
  \ <span m=\"45490\">you</span> <span m=\"45730\">forbid</span> <span m=\"46690\"\
  >a</span> <span m=\"46750\">specific</span> <span m=\"47460\">subgraph.</span> <span\
  \ m=\"54780\">Forbid</span> <span m=\"55110\">a</span> <span m=\"55200\">specific</span>\
  \ <span m=\"55650\">subgraph.</span> <span m=\"56400\">And I</span> <span m=\"56550\"\
  >ask</span> <span m=\"56820\">you,</span> <span m=\"57330\">what's</span> <span\
  \ m=\"57540\">the</span> <span m=\"57660\">maximum</span> <span m=\"58260\">number</span>\
  \ <span m=\"58530\">of</span> <span m=\"58620\">edges</span> <span m=\"59400\">that</span>\
  \ <span m=\"59940\">can</span> <span m=\"60120\">appear</span> <span m=\"60900\"\
  >in</span> <span m=\"61020\">your</span> <span m=\"61140\">graph?</span></p><p><span\
  \ m=\"63330\">In</span> <span m=\"63420\">particular,</span> <span m=\"64290\">and</span>\
  \ <span m=\"64410\">this</span> <span m=\"64590\">is</span> <span m=\"64720\">the</span>\
  \ <span m=\"64769\">question</span> <span m=\"65129\">that</span> <span m=\"65760\"\
  >we</span> <span m=\"65910\">saw</span> <span m=\"66150\">at</span> <span m=\"66210\"\
  >the</span> <span m=\"66330\">end</span> <span m=\"66630\">of</span> <span m=\"\
  66900\">last</span> <span m=\"67260\">lecture,</span> <span m=\"68700\">which,</span>\
  \ <span m=\"69240\">now</span> <span m=\"69870\">we're</span> <span m=\"69960\"\
  >going</span> <span m=\"70140\">to</span> <span m=\"70230\">pretend</span> <span\
  \ m=\"70580\">that's</span> <span m=\"70770\">a</span> <span m=\"70860\">theorem.</span>\
  \ <span m=\"72070\">Mantel's</span> <span m=\"73210\">theorem</span> <span m=\"\
  77040\">essentially</span> <span m=\"77550\">asks,</span> <span m=\"78510\">if</span>\
  \ <span m=\"78690\">you</span> <span m=\"78840\">know</span> <span m=\"79050\">that</span>\
  \ <span m=\"79200\">your</span> <span m=\"79350\">graph</span> <span m=\"79740\"\
  >has</span> <span m=\"79890\">no</span> <span m=\"80190\">triangles,</span> <span\
  \ m=\"81450\">what's</span> <span m=\"81720\">the</span> <span m=\"81840\">maximum</span>\
  \ <span m=\"82440\">number</span> <span m=\"82710\">of</span> <span m=\"82830\"\
  >edges</span> <span m=\"83550\">it</span> <span m=\"83640\">can</span> <span m=\"\
  83820\">have?</span> <span m=\"85770\">And</span> <span m=\"85860\">Mantel's</span>\
  \ <span m=\"86040\">theorem</span> <span m=\"86580\">tells</span> <span m=\"86910\"\
  >us</span> <span m=\"87120\">that</span> <span m=\"87750\">the</span> <span m=\"\
  87900\">extremal</span> <span m=\"88440\">example</span> <span m=\"89880\">is</span>\
  \ <span m=\"90150\">when</span> <span m=\"90840\">your</span> <span m=\"91020\"\
  >graph</span> <span m=\"91680\">consists</span> <span m=\"92490\">of</span> <span\
  \ m=\"93300\">putting</span> <span m=\"95940\">half</span> <span m=\"96280\">the</span>\
  \ <span m=\"96360\">vertices</span> <span m=\"96840\">on</span> <span m=\"96960\"\
  >one</span> <span m=\"97350\">side,</span> <span m=\"98250\">half</span> <span m=\"\
  98580\">the</span> <span m=\"98700\">vertices</span> <span m=\"99210\">on</span>\
  \ <span m=\"99360\">the</span> <span m=\"99480\">other</span> <span m=\"99720\"\
  >side,</span> <span m=\"100530\">and</span> <span m=\"100800\">putting</span> <span\
  \ m=\"101220\">in</span> <span m=\"101520\">all</span> <span m=\"101700\">the</span>\
  \ <span m=\"101880\">edges</span> <span m=\"104040\">between</span> <span m=\"107070\"\
  >the</span> <span m=\"107240\">two</span> <span m=\"108380\">sides.</span></p><p><span\
  \ m=\"109350\">So</span> <span m=\"109400\">this</span> <span m=\"109580\">is</span>\
  \ <span m=\"109670\">a</span> <span m=\"109760\">complete</span> <span m=\"110150\"\
  >bipartite</span> <span m=\"110780\">graph.</span> <span m=\"113490\">For</span>\
  \ <span m=\"114090\">these</span> <span m=\"114450\">partitions,</span> <span m=\"\
  115100\">we</span> <span m=\"115220\">denote</span> <span m=\"116460\">complete</span>\
  \ <span m=\"116830\">bipartite</span> <span m=\"117240\">graphs</span> <span m=\"\
  118920\">like</span> <span m=\"119070\">that.</span> <span m=\"120980\">And</span>\
  \ <span m=\"121210\">Mantel's</span> <span m=\"121460\">theorem</span> <span m=\"\
  122040\">tells</span> <span m=\"122370\">us</span> <span m=\"122550\">that</span>\
  \ <span m=\"123060\">this</span> <span m=\"123300\">graph,</span> <span m=\"123870\"\
  >among</span> <span m=\"124110\">triangle-free</span> <span m=\"124710\">graphs,</span>\
  \ <span m=\"125370\">has</span> <span m=\"125520\">the</span> <span m=\"125610\"\
  >most</span> <span m=\"125910\">number</span> <span m=\"126180\">of</span> <span\
  \ m=\"126300\">edges.</span></p><p><span m=\"128820\">Triangle-free</span> <span\
  \ m=\"133220\">graph,</span> <span m=\"136030\">n</span> <span m=\"136250\">vertices,</span>\
  \ <span m=\"139340\">has</span> <span m=\"140780\">at</span> <span m=\"140930\"\
  >most--</span> <span m=\"141740\">so</span> <span m=\"141860\">the</span> <span\
  \ m=\"141950\">number</span> <span m=\"142220\">of</span> <span m=\"142340\">edges</span>\
  \ <span m=\"142640\">there</span> <span m=\"143270\">is</span> <span m=\"144320\"\
  >n</span> <span m=\"144500\">squared</span> <span m=\"145370\">divided</span> <span\
  \ m=\"145760\">by</span> <span m=\"145910\">4.</span> <span m=\"146745\">Round</span>\
  \ <span m=\"147220\">down--</span> <span m=\"150650\">that</span> <span m=\"150790\"\
  >many</span> <span m=\"150970\">edges.</span> <span m=\"152340\">And</span> <span\
  \ m=\"152550\">from</span> <span m=\"152850\">this</span> <span m=\"153030\">example,</span>\
  \ <span m=\"153870\">this</span> <span m=\"154050\">bound</span> <span m=\"154320\"\
  >is</span> <span m=\"154450\">tight.</span> <span m=\"155800\">So</span> <span m=\"\
  156150\">Mantel's</span> <span m=\"156230\">theorem</span> <span m=\"156440\">them</span>\
  \ <span m=\"156840\">gives</span> <span m=\"157080\">us</span> <span m=\"157260\"\
  >a</span> <span m=\"157830\">completely</span> <span m=\"158220\">satisfactory</span>\
  \ <span m=\"159000\">answer</span> <span m=\"159630\">to</span> <span m=\"159750\"\
  >the</span> <span m=\"159840\">question</span> <span m=\"160490\">of,</span> <span\
  \ m=\"160620\">what's</span> <span m=\"160860\">the</span> <span m=\"160920\">maximum</span>\
  \ <span m=\"161460\">number</span> <span m=\"161700\">of</span> <span m=\"161820\"\
  >edges</span> <span m=\"162630\">in</span> <span m=\"162730\">a</span> <span m=\"\
  162780\">graph</span> <span m=\"163470\">without</span> <span m=\"163770\">triangles?</span></p><p><span\
  \ m=\"167870\">And</span> <span m=\"167990\">I</span> <span m=\"168050\">want</span>\
  \ <span m=\"168200\">to</span> <span m=\"168260\">begin</span> <span m=\"169430\"\
  >by</span> <span m=\"169910\">showing</span> <span m=\"170240\">you</span> <span\
  \ m=\"170390\">a</span> <span m=\"170480\">few</span> <span m=\"170720\">different</span>\
  \ <span m=\"171050\">proofs</span> <span m=\"171500\">of</span> <span m=\"171620\"\
  >Mantel's</span> <span m=\"172085\">theorem.</span> <span m=\"172760\">So</span>\
  \ <span m=\"173540\">we're</span> <span m=\"173900\">illustrating</span> <span m=\"\
  174440\">some</span> <span m=\"174650\">different</span> <span m=\"174920\">techniques</span>\
  \ <span m=\"175430\">in</span> <span m=\"175580\">graph</span> <span m=\"175850\"\
  >theory.</span> <span m=\"177870\">So</span> <span m=\"177950\">we'll</span> <span\
  \ m=\"178040\">see</span> <span m=\"178730\">quite</span> <span m=\"178940\">a</span>\
  \ <span m=\"178970\">few</span> <span m=\"179210\">proofs</span> <span m=\"179570\"\
  >in</span> <span m=\"179720\">today's</span> <span m=\"180090\">lecture.</span>\
  \ <span m=\"180890\">The first</span> <span m=\"181190\">one</span> <span m=\"182900\"\
  >begins--</span> <span m=\"184010\">well,</span> <span m=\"184820\">here's</span>\
  \ <span m=\"185060\">the</span> <span m=\"185120\">setup.</span> <span m=\"185990\"\
  >I</span> <span m=\"186110\">have</span> <span m=\"186620\">G,</span> <span m=\"\
  187110\">an n</span> <span m=\"187600\">vertex</span> <span m=\"188090\">graph.</span>\
  \ <span m=\"189660\">And</span> <span m=\"189740\">let</span> <span m=\"189890\"\
  >me</span> <span m=\"190100\">denote</span> <span m=\"190310\">the</span> <span\
  \ m=\"190970\">vertices</span> <span m=\"191450\">and</span> <span m=\"191570\"\
  >edges</span> <span m=\"191900\">of</span> <span m=\"191990\">G</span> <span m=\"\
  192230\">by</span> <span m=\"192560\">V</span> <span m=\"193023\">and E.</span></p><p><span\
  \ m=\"197190\">If</span> <span m=\"197370\">I</span> <span m=\"197430\">have</span>\
  \ <span m=\"197700\">an</span> <span m=\"197820\">edge</span> <span m=\"198270\"\
  >in</span> <span m=\"198420\">G</span> <span m=\"200160\">between</span> <span m=\"\
  200520\">vertices</span> <span m=\"201150\">x</span> <span m=\"201540\">and</span>\
  \ <span m=\"201660\">y,</span> <span m=\"203040\">then</span> <span m=\"203250\"\
  >note</span> <span m=\"203580\">that</span> <span m=\"204120\">they</span> <span\
  \ m=\"204300\">cannot</span> <span m=\"204990\">have</span> <span m=\"205350\">any</span>\
  \ <span m=\"205530\">common</span> <span m=\"205920\">neighbors.</span> <span m=\"\
  215300\">Because</span> <span m=\"215630\">if</span> <span m=\"215720\">they</span>\
  \ <span m=\"215870\">did,</span> <span m=\"216290\">I</span> <span m=\"216380\"\
  >would</span> <span m=\"216530\">see</span> <span m=\"216710\">a</span> <span m=\"\
  216740\">triangle.</span> <span m=\"218040\">So</span> <span m=\"218140\">I assume</span>\
  \ <span m=\"218440\">G</span> <span m=\"218750\">is</span> <span m=\"218900\">triangle-free.</span>\
  \ <span m=\"227380\">So</span> <span m=\"228910\">what</span> <span m=\"229090\"\
  >can</span> <span m=\"229240\">we</span> <span m=\"229330\">say</span> <span m=\"\
  229600\">about</span> <span m=\"229810\">the</span> <span m=\"229930\">degrees</span>\
  \ <span m=\"230770\">of</span> <span m=\"230890\">the</span> <span m=\"230950\"\
  >two</span> <span m=\"231190\">endpoints</span> <span m=\"231700\">of</span> <span\
  \ m=\"231790\">this</span> <span m=\"231920\">edge?</span> <span m=\"233830\">Well,</span>\
  \ <span m=\"233910\">they</span> <span m=\"234150\">cannot</span> <span m=\"234570\"\
  >add</span> <span m=\"234750\">up</span> <span m=\"234900\">to?</span></p><p><span\
  \ m=\"235746\">AUDIENCE:</span> <span m=\"235888\">They</span> <span m=\"236030\"\
  >can't</span> <span m=\"236172\">have</span> <span m=\"236598\">more</span> <span\
  \ m=\"237024\">than</span> <span m=\"237450\">n.</span></p><p><span m=\"237880\"\
  >YUFEI ZHAO:</span> <span m=\"237935\">They</span> <span m=\"237990\">cannot</span>\
  \ <span m=\"238290\">add</span> <span m=\"238470\">up</span> <span m=\"238560\"\
  >to</span> <span m=\"238680\">more</span> <span m=\"238860\">than</span> <span m=\"\
  239010\">n.</span> <span m=\"239700\">So</span> <span m=\"239880\">in</span> <span\
  \ m=\"239970\">particular--</span> <span m=\"241800\">so</span> <span m=\"242130\"\
  >exactly.</span> <span m=\"242750\">So</span> <span m=\"242890\">the</span> <span\
  \ m=\"243000\">degrees</span> <span m=\"244200\">of</span> <span m=\"244410\">these</span>\
  \ <span m=\"244620\">two</span> <span m=\"244880\">endpoints,</span> <span m=\"\
  246050\">there's</span> <span m=\"246590\">at</span> <span m=\"246780\">most</span>\
  \ <span m=\"247110\">n</span> <span m=\"247980\">whenever</span> <span m=\"249540\"\
  >xy</span> <span m=\"251850\">is</span> <span m=\"252000\">an</span> <span m=\"\
  252130\">edge.</span> <span m=\"252450\">So</span> <span m=\"252680\">here</span>\
  \ <span m=\"252870\">I'm</span> <span m=\"252960\">using</span> <span m=\"253290\"\
  >d</span> <span m=\"253530\">to</span> <span m=\"253650\">denote</span> <span m=\"\
  253920\">degree.</span></p><p><span m=\"259540\">Well,</span> <span m=\"259709\"\
  >OK.</span> <span m=\"259950\">So</span> <span m=\"260100\">now</span> <span m=\"\
  260279\">let</span> <span m=\"260430\">me</span> <span m=\"260670\">consider</span>\
  \ <span m=\"261240\">the</span> <span m=\"261329\">quantity</span> <span m=\"262380\"\
  >which</span> <span m=\"262770\">is</span> <span m=\"264060\">the</span> <span m=\"\
  264150\">sum</span> <span m=\"264750\">of</span> <span m=\"264930\">the</span> <span\
  \ m=\"265050\">squared</span> <span m=\"265710\">degrees.</span> <span m=\"270140\"\
  >On</span> <span m=\"270230\">one</span> <span m=\"270410\">hand,</span> <span m=\"\
  271190\">I</span> <span m=\"271310\">claim</span> <span m=\"271700\">that</span>\
  \ <span m=\"272210\">the</span> <span m=\"272330\">sum</span> <span m=\"273500\"\
  >is</span> <span m=\"274760\">equal</span> <span m=\"275150\">to</span> <span m=\"\
  276260\">this</span> <span m=\"276860\">quantity</span> <span m=\"277400\">here,</span>\
  \ <span m=\"278430\">where</span> <span m=\"278660\">I</span> <span m=\"278780\"\
  >sum</span> <span m=\"279200\">over</span> <span m=\"279530\">all</span> <span m=\"\
  279830\">edges.</span> <span m=\"283300\">And</span> <span m=\"283420\">the</span>\
  \ <span m=\"283480\">reason</span> <span m=\"283810\">is,</span> <span m=\"284050\"\
  >well,</span> <span m=\"284380\">look</span> <span m=\"284560\">at</span> <span\
  \ m=\"284650\">the</span> <span m=\"284740\">sum.</span> <span m=\"285580\">Suppose,</span>\
  \ <span m=\"285970\">imagine</span> <span m=\"286390\">writing</span> <span m=\"\
  286810\">out</span> <span m=\"287110\">all</span> <span m=\"287230\">the</span>\
  \ <span m=\"287350\">sum n's.</span> <span m=\"288010\">How</span> <span m=\"288190\"\
  >many</span> <span m=\"288430\">times</span> <span m=\"288880\">does</span> <span\
  \ m=\"289210\">each</span> <span m=\"289780\">dx</span> <span m=\"290320\">come</span>\
  \ <span m=\"290560\">up?</span></p><p><span m=\"291632\">So</span> <span m=\"292100\"\
  >each</span> <span m=\"293500\">dx</span> <span m=\"295760\">appears</span> <span\
  \ m=\"297890\">one</span> <span m=\"298190\">for</span> <span m=\"298400\">each</span>\
  \ <span m=\"298700\">edge</span> <span m=\"299070\">x is</span> <span m=\"299470\"\
  >in,</span> <span m=\"299800\">so</span> <span m=\"300020\">appears</span> <span\
  \ m=\"300380\">exactly</span> <span m=\"300980\">dx</span> <span m=\"301400\">times.</span>\
  \ <span m=\"309710\">But</span> <span m=\"309890\">we</span> <span m=\"310220\"\
  >saw</span> <span m=\"310610\">from</span> <span m=\"311390\">up</span> <span m=\"\
  311540\">here</span> <span m=\"312050\">that</span> <span m=\"312380\">each</span>\
  \ <span m=\"312650\">sum n is</span> <span m=\"313090\">at</span> <span m=\"313190\"\
  >most</span> <span m=\"313600\">n.</span> <span m=\"314120\">So</span> <span m=\"\
  314960\">this</span> <span m=\"315110\">sum</span> <span m=\"315470\">here</span>\
  \ <span m=\"316040\">is</span> <span m=\"316220\">that</span> <span m=\"316370\"\
  >most</span> <span m=\"318520\">mn.</span></p><p><span m=\"321950\">On</span> <span\
  \ m=\"322100\">the</span> <span m=\"322160\">other</span> <span m=\"322340\">hand,</span>\
  \ <span m=\"323640\">let's</span> <span m=\"323720\">consider</span> <span m=\"\
  324170\">the</span> <span m=\"324260\">quantity</span> <span m=\"324770\">which</span>\
  \ <span m=\"325010\">is</span> <span m=\"325190\">just</span> <span m=\"325520\"\
  >the</span> <span m=\"325610\">sum</span> <span m=\"326000\">of</span> <span m=\"\
  326120\">the</span> <span m=\"326210\">degrees.</span> <span m=\"329690\">And</span>\
  \ <span m=\"330775\">you</span> <span m=\"331060\">sometimes</span> <span m=\"331390\"\
  >know it</span> <span m=\"331570\">as</span> <span m=\"331660\">the</span> <span\
  \ m=\"331750\">handshaking</span> <span m=\"332350\">lemma,</span> <span m=\"332950\"\
  >that</span> <span m=\"333600\">the</span> <span m=\"333730\">sums</span> <span\
  \ m=\"334090\">of</span> <span m=\"334180\">the</span> <span m=\"334270\">degrees</span>\
  \ <span m=\"334870\">is</span> <span m=\"335110\">just</span> <span m=\"335320\"\
  >twice</span> <span m=\"335800\">the</span> <span m=\"335950\">number</span> <span\
  \ m=\"336280\">of</span> <span m=\"336670\">edges.</span> <span m=\"337210\">Each</span>\
  \ <span m=\"337450\">edge</span> <span m=\"338060\">is</span> <span m=\"338170\"\
  >considered</span> <span m=\"338530\">twice</span> <span m=\"339010\">in</span>\
  \ <span m=\"339130\">the</span> <span m=\"339220\">sum.</span></p><p><span m=\"\
  340840\">Well,</span> <span m=\"341160\">now</span> <span m=\"341370\">we</span>\
  \ <span m=\"341520\">apply</span> <span m=\"341880\">the</span> <span m=\"342390\"\
  >Cauchy-Schwarz</span> <span m=\"343170\">inequality,</span> <span m=\"344130\"\
  >which,</span> <span m=\"344930\">as</span> <span m=\"345120\">you'll</span> <span\
  \ m=\"345300\">see</span> <span m=\"345570\">many</span> <span m=\"345810\">times</span>\
  \ <span m=\"346140\">in</span> <span m=\"346230\">this</span> <span m=\"346380\"\
  >course,</span> <span m=\"347980\">although</span> <span m=\"348600\">you</span>\
  \ <span m=\"348660\">might</span> <span m=\"348840\">think</span> <span m=\"349020\"\
  >of</span> <span m=\"349140\">it</span> <span m=\"349260\">as</span> <span m=\"\
  349440\">a</span> <span m=\"349590\">fairly</span> <span m=\"350610\">simple</span>\
  \ <span m=\"351090\">inequality,</span> <span m=\"352080\">it's</span> <span m=\"\
  352710\">extremely</span> <span m=\"353220\">powerful.</span> <span m=\"354240\"\
  >And</span> <span m=\"354510\">it</span> <span m=\"354600\">will</span> <span m=\"\
  354720\">come</span> <span m=\"354960\">up</span> <span m=\"355080\">pretty</span>\
  \ <span m=\"355380\">much</span> <span m=\"356130\">throughout</span> <span m=\"\
  356550\">this</span> <span m=\"356730\">course.</span> <span m=\"357930\">By</span>\
  \ <span m=\"358110\">the</span> <span m=\"358200\">Cauchy-Schwarz</span> <span m=\"\
  358540\">inequality,</span> <span m=\"359300\">you</span> <span m=\"359370\">compare</span>\
  \ <span m=\"359790\">these</span> <span m=\"359970\">two</span> <span m=\"360120\"\
  >quantities.</span> <span m=\"361020\">I</span> <span m=\"361140\">find</span> <span\
  \ m=\"361710\">that</span> <span m=\"367180\">we</span> <span m=\"367370\">have</span>\
  \ <span m=\"372420\">this</span> <span m=\"372610\">inequality</span> <span m=\"\
  373840\">over</span> <span m=\"374050\">here</span> <span m=\"374650\">relating</span>\
  \ <span m=\"375130\">the</span> <span m=\"375400\">sums</span> <span m=\"375850\"\
  >of</span> <span m=\"375910\">the</span> <span m=\"376000\">degrees</span> <span\
  \ m=\"377230\">and</span> <span m=\"378010\">square</span> <span m=\"378490\">of</span>\
  \ <span m=\"378670\">the</span> <span m=\"378910\">sum</span> <span m=\"379180\"\
  >of</span> <span m=\"379240\">the</span> <span m=\"379330\">degrees.</span></p><p><span\
  \ m=\"381300\">But</span> <span m=\"381960\">we</span> <span m=\"382090\">saw,</span>\
  \ <span m=\"383500\">on</span> <span m=\"383590\">one</span> <span m=\"383770\"\
  >hand,</span> <span m=\"384430\">the</span> <span m=\"384520\">left-hand</span>\
  \ <span m=\"384880\">side</span> <span m=\"386740\">is</span> <span m=\"387190\"\
  >4m</span> <span m=\"387730\">squared.</span> <span m=\"390170\">And</span> <span\
  \ m=\"390620\">we</span> <span m=\"390800\">also</span> <span m=\"391070\">saw</span>\
  \ <span m=\"392306\">that</span> <span m=\"393530\">the</span> <span m=\"393590\"\
  >right-hand</span> <span m=\"394010\">side</span> <span m=\"394370\">is</span> <span\
  \ m=\"394540\">at</span> <span m=\"394670\">most</span> <span m=\"395894\">mn</span>\
  \ <span m=\"396980\">squared.</span> <span m=\"399870\">Putting</span> <span m=\"\
  400170\">them</span> <span m=\"400320\">together,</span> <span m=\"402040\">we</span>\
  \ <span m=\"402090\">see</span> <span m=\"402300\">that</span> <span m=\"402480\"\
  >m</span> <span m=\"402780\">is</span> <span m=\"403050\">at</span> <span m=\"403200\"\
  >most</span> <span m=\"404070\">n</span> <span m=\"404250\">squared</span> <span\
  \ m=\"404850\">over</span> <span m=\"405060\">4.</span> <span m=\"405540\">And</span>\
  \ <span m=\"405660\">of</span> <span m=\"405750\">course,</span> <span m=\"406150\"\
  >because</span> <span m=\"406410\">it's</span> <span m=\"406530\">an</span> <span\
  \ m=\"406590\">integer,</span> <span m=\"407510\">it's</span> <span m=\"407740\"\
  >at</span> <span m=\"407820\">most</span> <span m=\"408120\">the</span> <span m=\"\
  408150\">floor</span> <span m=\"408540\">of</span> <span m=\"408690\">this</span>\
  \ <span m=\"408840\">number.</span> <span m=\"410920\">And</span> <span m=\"411010\"\
  >that's</span> <span m=\"411490\">a</span> <span m=\"411550\">proof</span> <span\
  \ m=\"412840\">of</span> <span m=\"413710\">Mantel's</span> <span m=\"414220\">theorem.</span></p><p><span\
  \ m=\"421550\">What</span> <span m=\"421700\">can</span> <span m=\"421850\">you</span>\
  \ <span m=\"421910\">tell</span> <span m=\"422120\">me</span> <span m=\"422270\"\
  >about</span> <span m=\"422600\">the</span> <span m=\"423290\">equality</span> <span\
  \ m=\"423980\">case</span> <span m=\"424460\">in</span> <span m=\"424580\">this</span>\
  \ <span m=\"424790\">proof?</span> <span m=\"431660\">So</span> <span m=\"431910\"\
  >I'll</span> <span m=\"431990\">let</span> <span m=\"432140\">you</span> <span m=\"\
  432260\">think</span> <span m=\"432440\">about</span> <span m=\"432650\">that.</span>\
  \ <span m=\"433220\">But</span> <span m=\"433370\">let</span> <span m=\"433490\"\
  >me</span> <span m=\"433970\">show</span> <span m=\"434180\">you</span> <span m=\"\
  434270\">some</span> <span m=\"434420\">other</span> <span m=\"434600\">proofs.</span></p><p><span\
  \ m=\"439910\">In</span> <span m=\"440030\">other</span> <span m=\"440180\">words,</span>\
  \ <span m=\"440860\">are</span> <span m=\"440920\">there</span> <span m=\"441140\"\
  >graphs</span> <span m=\"441770\">with</span> <span m=\"442220\">the</span> <span\
  \ m=\"442340\">same</span> <span m=\"442700\">number</span> <span m=\"442970\">of</span>\
  \ <span m=\"443060\">edges</span> <span m=\"443540\">as</span> <span m=\"443720\"\
  >the</span> <span m=\"443780\">graph</span> <span m=\"444060\">shown</span> <span\
  \ m=\"444290\">up</span> <span m=\"444410\">there</span> <span m=\"445640\">that</span>\
  \ <span m=\"445820\">is</span> <span m=\"445940\">also</span> <span m=\"446180\"\
  >triangle-free?</span> <span m=\"446840\">Is</span> <span m=\"446990\">that</span>\
  \ <span m=\"447110\">a</span> <span m=\"447200\">unique</span> <span m=\"447500\"\
  >example?</span> <span m=\"451630\">So</span> <span m=\"451880\">let</span> <span\
  \ m=\"451970\">me</span> <span m=\"452060\">show</span> <span m=\"452240\">you</span>\
  \ <span m=\"452360\">a</span> <span m=\"452390\">different</span> <span m=\"452690\"\
  >proof</span> <span m=\"453140\">of</span> <span m=\"453290\">Mantel's</span> <span\
  \ m=\"453610\">theorem.</span></p><p><span m=\"458400\">In</span> <span m=\"458580\"\
  >this</span> <span m=\"458730\">proof,</span> <span m=\"459150\">so</span> <span\
  \ m=\"459300\">we</span> <span m=\"459450\">begin</span> <span m=\"459750\">with</span>\
  \ <span m=\"459870\">a</span> <span m=\"459930\">step</span> <span m=\"460260\"\
  >that</span> <span m=\"461190\">seems</span> <span m=\"461460\">a</span> <span m=\"\
  461490\">little</span> <span m=\"461670\">tricky.</span> <span m=\"463090\">Let's</span>\
  \ <span m=\"464840\">let</span> <span m=\"465230\">A</span> <span m=\"466170\">be</span>\
  \ <span m=\"466380\">a</span> <span m=\"466470\">subset</span> <span m=\"467010\"\
  >of</span> <span m=\"467460\">vertices</span> <span m=\"468630\">such</span> <span\
  \ m=\"468960\">that</span> <span m=\"469260\">A</span> <span m=\"469620\">is</span>\
  \ <span m=\"470280\">a</span> <span m=\"470410\">largest</span> <span m=\"471540\"\
  >independent</span> <span m=\"472170\">set</span> <span m=\"480320\">of</span> <span\
  \ m=\"480640\">G.</span> <span m=\"481426\">So</span> <span m=\"481820\">remember,</span>\
  \ <span m=\"482120\">independent</span> <span m=\"482630\">set</span> <span m=\"\
  482900\">is a</span> <span m=\"482960\">subset</span> <span m=\"483470\">of</span>\
  \ <span m=\"483530\">vertices</span> <span m=\"484010\">with</span> <span m=\"484160\"\
  >no</span> <span m=\"484370\">edges</span> <span m=\"484730\">inside.</span> <span\
  \ m=\"486890\">It</span> <span m=\"486980\">may</span> <span m=\"487100\">have</span>\
  \ <span m=\"488030\">many</span> <span m=\"488330\">independent</span> <span m=\"\
  488750\">sets</span> <span m=\"489230\">all</span> <span m=\"489470\">having</span>\
  \ <span m=\"489770\">the</span> <span m=\"489860\">same</span> <span m=\"490220\"\
  >maximum</span> <span m=\"490760\">size.</span> <span m=\"491360\">Take</span> <span\
  \ m=\"491630\">one</span> <span m=\"491810\">of</span> <span m=\"491900\">them.</span></p><p><span\
  \ m=\"494120\">So</span> <span m=\"494560\">why</span> <span m=\"494770\">should</span>\
  \ <span m=\"494980\">you</span> <span m=\"495070\">do</span> <span m=\"495250\"\
  >this</span> <span m=\"495380\">step?</span> <span m=\"495930\">Well,</span> <span\
  \ m=\"496150\">you</span> <span m=\"496180\">know,</span> <span m=\"496390\">sometimes</span>\
  \ <span m=\"496900\">magic</span> <span m=\"497260\">happens.</span> <span m=\"\
  500340\">Let's</span> <span m=\"501000\">consider</span> <span m=\"503130\">some</span>\
  \ <span m=\"503370\">vertex.</span> <span m=\"505280\">So</span> <span m=\"505710\"\
  >consider</span> <span m=\"506010\">some</span> <span m=\"506220\">vertex,</span>\
  \ <span m=\"507160\">let's</span> <span m=\"507210\">say</span> <span m=\"507600\"\
  >x,</span> <span m=\"508440\">and</span> <span m=\"508770\">look</span> <span m=\"\
  509010\">at</span> <span m=\"509130\">its</span> <span m=\"509310\">neighborhood.</span></p><p><span\
  \ m=\"512809\">The</span> <span m=\"512900\">neighborhood</span> <span m=\"513620\"\
  >must</span> <span m=\"513980\">be</span> <span m=\"514190\">an</span> <span m=\"\
  514280\">independent</span> <span m=\"514820\">set.</span> <span m=\"516400\">Otherwise,</span>\
  \ <span m=\"516990\">I</span> <span m=\"517049\">get</span> <span m=\"517270\">a</span>\
  \ <span m=\"517299\">triangle.</span> <span m=\"519870\">So</span> <span m=\"520669\"\
  >every</span> <span m=\"522809\">neighborhood</span> <span m=\"525340\">is</span>\
  \ <span m=\"525640\">an</span> <span m=\"526030\">independent</span> <span m=\"\
  526510\">set.</span> <span m=\"529910\">And</span> <span m=\"530100\">as</span>\
  \ <span m=\"530240\">a</span> <span m=\"530300\">result,</span> <span m=\"531720\"\
  >the</span> <span m=\"531820\">degree</span> <span m=\"532310\">of</span> <span\
  \ m=\"532490\">every</span> <span m=\"532730\">vertex</span> <span m=\"533740\"\
  >is</span> <span m=\"533920\">at</span> <span m=\"534020\">most</span> <span m=\"\
  535040\">the</span> <span m=\"535670\">size</span> <span m=\"536150\">of</span>\
  \ <span m=\"536240\">the</span> <span m=\"536300\">largest</span> <span m=\"537230\"\
  >independent</span> <span m=\"537750\">set.</span></p><p><span m=\"543290\">So</span>\
  \ <span m=\"543440\">now,</span> <span m=\"544580\">let</span> <span m=\"546560\"\
  >B</span> <span m=\"547340\">be</span> <span m=\"547460\">the</span> <span m=\"\
  547580\">complement</span> <span m=\"548390\">of</span> <span m=\"548640\">A.</span>\
  \ <span m=\"554730\">So</span> <span m=\"554910\">I</span> <span m=\"554970\">have</span>\
  \ <span m=\"555903\">this</span> <span m=\"556810\">A</span> <span m=\"560032\"\
  >and</span> <span m=\"561530\">B.</span> <span m=\"563950\">Every</span> <span m=\"\
  564370\">edge</span> <span m=\"565120\">has</span> <span m=\"565510\">to</span>\
  \ <span m=\"565900\">intersect</span> <span m=\"566470\">B.</span> <span m=\"566920\"\
  >The</span> <span m=\"567100\">edge</span> <span m=\"567340\">cannot</span> <span\
  \ m=\"567640\">be</span> <span m=\"567790\">entirely</span> <span m=\"568180\">containing</span>\
  \ <span m=\"568660\">A,</span> <span m=\"568860\">because</span> <span m=\"569200\"\
  >it</span> <span m=\"569320\">has</span> <span m=\"569530\">no</span> <span m=\"\
  569740\">edges.</span></p><p><span m=\"579870\">So</span> <span m=\"580440\">the</span>\
  \ <span m=\"580530\">number</span> <span m=\"580890\">of</span> <span m=\"581070\"\
  >edges</span> <span m=\"581760\">of</span> <span m=\"582250\">G</span> <span m=\"\
  585860\">is</span> <span m=\"586730\">at</span> <span m=\"586910\">most--</span>\
  \ <span m=\"588090\">well,</span> <span m=\"588530\">I</span> <span m=\"589100\"\
  >count</span> <span m=\"590460\">over</span> <span m=\"591090\">the</span> <span\
  \ m=\"591860\">vertices</span> <span m=\"592450\">in</span> <span m=\"592700\">B,</span>\
  \ <span m=\"593780\">the</span> <span m=\"593930\">degree.</span> <span m=\"595140\"\
  >So</span> <span m=\"595730\">maybe</span> <span m=\"596000\">I</span> <span m=\"\
  596210\">overcount.</span> <span m=\"596690\">So</span> <span m=\"597160\">the</span>\
  \ <span m=\"597290\">edges</span> <span m=\"597670\">containing</span> <span m=\"\
  598250\">B,</span> <span m=\"598900\">I</span> <span m=\"598970\">count</span> <span\
  \ m=\"599210\">twice,</span> <span m=\"599570\">but</span> <span m=\"599720\">that's</span>\
  \ <span m=\"599820\">OK.</span> <span m=\"600020\">So</span> <span m=\"600230\"\
  >this</span> <span m=\"600410\">is</span> <span m=\"600500\">an</span> <span m=\"\
  600590\">upper</span> <span m=\"600800\">bound</span> <span m=\"601070\">on</span>\
  \ <span m=\"601160\">the</span> <span m=\"601220\">number</span> <span m=\"601520\"\
  >of</span> <span m=\"601670\">edges.</span></p><p><span m=\"603550\">But</span>\
  \ <span m=\"603740\">I</span> <span m=\"603830\">also</span> <span m=\"604130\"\
  >know</span> <span m=\"604640\">that</span> <span m=\"605360\">every</span> <span\
  \ m=\"605720\">vertex</span> <span m=\"606290\">in</span> <span m=\"606350\">the</span>\
  \ <span m=\"606440\">graph</span> <span m=\"606920\">has</span> <span m=\"607130\"\
  >a</span> <span m=\"607190\">degree</span> <span m=\"607520\">at</span> <span m=\"\
  607700\">most</span> <span m=\"608240\">the</span> <span m=\"608330\">size</span>\
  \ <span m=\"608810\">of</span> <span m=\"609140\">A.</span> <span m=\"610490\">So</span>\
  \ <span m=\"611900\">each</span> <span m=\"612160\">sum n</span> <span m=\"612590\"\
  >is</span> <span m=\"612740\">at</span> <span m=\"612860\">most</span> <span m=\"\
  613090\">the</span> <span m=\"613160\">size</span> <span m=\"613460\">of</span>\
  \ <span m=\"613580\">A.</span> <span m=\"613880\">And I</span> <span m=\"614180\"\
  >have</span> <span m=\"614480\">B</span> <span m=\"614870\">terms.</span> <span\
  \ m=\"617810\">So</span> <span m=\"617980\">I</span> <span m=\"618060\">have</span>\
  \ <span m=\"618220\">that.</span></p><p><span m=\"619440\">Now,</span> <span m=\"\
  619900\">by</span> <span m=\"620080\">the</span> <span m=\"620710\">AMGM</span>\
  \ <span m=\"621370\">inequality,</span> <span m=\"629766\">you'll</span> <span m=\"\
  630252\">have</span> <span m=\"630738\">that.</span> <span m=\"631240\">And</span>\
  \ <span m=\"631520\">the</span> <span m=\"631640\">sizes</span> <span m=\"632180\"\
  >of</span> <span m=\"632330\">A and</span> <span m=\"632570\">B</span> <span m=\"\
  632930\">add</span> <span m=\"633110\">up</span> <span m=\"633290\">to</span> <span\
  \ m=\"634670\">the</span> <span m=\"635120\">entire</span> <span m=\"635990\">vertex</span>\
  \ <span m=\"636410\">set,</span> <span m=\"638440\">n</span> <span m=\"638620\"\
  >squared</span> <span m=\"639310\">over</span> <span m=\"639550\">4.</span> <span\
  \ m=\"642322\">So</span> <span m=\"642790\">that</span> <span m=\"642940\">gives</span>\
  \ <span m=\"643150\">you</span> <span m=\"643270\">another</span> <span m=\"643540\"\
  >proof</span> <span m=\"644290\">of</span> <span m=\"645432\">Mantel's</span> <span\
  \ m=\"645810\">theorem.</span> <span m=\"648910\">What</span> <span m=\"649060\"\
  >does</span> <span m=\"649240\">this</span> <span m=\"649420\">proof</span> <span\
  \ m=\"649690\">tell</span> <span m=\"649960\">us</span> <span m=\"650740\">about</span>\
  \ <span m=\"651010\">the</span> <span m=\"651100\">equality</span> <span m=\"651610\"\
  >case?</span></p><p><span m=\"655876\">Now,</span> <span m=\"656370\">something</span>\
  \ <span m=\"657150\">I</span> <span m=\"657270\">always</span> <span m=\"657540\"\
  >want</span> <span m=\"657670\">you</span> <span m=\"657780\">to</span> <span m=\"\
  657870\">keep</span> <span m=\"658080\">in</span> <span m=\"658140\">mind</span>\
  \ <span m=\"658590\">when</span> <span m=\"658710\">we</span> <span m=\"658830\"\
  >do</span> <span m=\"658980\">proofs</span> <span m=\"659745\">is,</span> <span\
  \ m=\"660090\">especially</span> <span m=\"660630\">if</span> <span m=\"660750\"\
  >we</span> <span m=\"660870\">have</span> <span m=\"661230\">a</span> <span m=\"\
  661320\">tight</span> <span m=\"661650\">example</span> <span m=\"662100\">like</span>\
  \ <span m=\"662290\">that--</span> <span m=\"662480\">and</span> <span m=\"662890\"\
  >later</span> <span m=\"663160\">on</span> <span m=\"663310\">in the</span> <span\
  \ m=\"663380\">course,</span> <span m=\"663660\">we'll</span> <span m=\"663780\"\
  >almost</span> <span m=\"664080\">never</span> <span m=\"664350\">have</span> <span\
  \ m=\"664590\">good</span> <span m=\"664770\">examples</span> <span m=\"665250\"\
  >like</span> <span m=\"665430\">that.</span> <span m=\"665970\">So</span> <span\
  \ m=\"666120\">this</span> <span m=\"666330\">is</span> <span m=\"666930\">still</span>\
  \ <span m=\"667230\">early</span> <span m=\"667500\">on</span> <span m=\"667620\"\
  >in</span> <span m=\"667710\">the</span> <span m=\"667770\">course.</span> <span\
  \ m=\"668100\">And we're</span> <span m=\"668250\">still</span> <span m=\"668460\"\
  >very</span> <span m=\"668670\">clean</span> <span m=\"668980\">in the</span> <span\
  \ m=\"669050\">examples--</span> <span m=\"669960\">is</span> <span m=\"670110\"\
  >to</span> <span m=\"670200\">keep</span> <span m=\"670530\">the</span> <span m=\"\
  670680\">extremal</span> <span m=\"671220\">example</span> <span m=\"671730\">in</span>\
  \ <span m=\"671850\">mind.</span> <span m=\"672960\">And</span> <span m=\"673530\"\
  >every</span> <span m=\"673770\">step</span> <span m=\"674100\">in</span> <span\
  \ m=\"674190\">your</span> <span m=\"674340\">proof,</span> <span m=\"675536\">it</span>\
  \ <span m=\"675940\">should</span> <span m=\"676140\">be</span> <span m=\"676350\"\
  >tight</span> <span m=\"677370\">for</span> <span m=\"677550\">that</span> <span\
  \ m=\"677730\">example.</span> <span m=\"678180\">Otherwise,</span> <span m=\"678570\"\
  >something</span> <span m=\"678900\">went</span> <span m=\"679050\">wrong</span>\
  \ <span m=\"679290\">with</span> <span m=\"679440\">your</span> <span m=\"679560\"\
  >proof.</span></p><p><span m=\"681050\">Let's</span> <span m=\"681200\">think</span>\
  \ <span m=\"681380\">about</span> <span m=\"681560\">the</span> <span m=\"681650\"\
  >inequalities.</span> <span m=\"683860\">At</span> <span m=\"684100\">equality,</span>\
  \ <span m=\"691400\">we</span> <span m=\"691550\">must</span> <span m=\"691850\"\
  >have</span> <span m=\"692360\">that--</span> <span m=\"693690\">so</span> <span\
  \ m=\"694160\">looking</span> <span m=\"694520\">at</span> <span m=\"695792\">this</span>\
  \ <span m=\"697620\">inequality.</span> <span m=\"698430\">So</span> <span m=\"\
  698550\">there</span> <span m=\"698670\">are</span> <span m=\"698730\">no</span>\
  \ <span m=\"699000\">edges</span> <span m=\"699360\">in</span> <span m=\"699490\"\
  >B.</span> <span m=\"707520\">We</span> <span m=\"707700\">also</span> <span m=\"\
  708660\">have</span> <span m=\"709130\">that--</span> <span m=\"712385\">so by</span>\
  \ <span m=\"712850\">that,</span> <span m=\"713320\">so</span> <span m=\"713620\"\
  >every</span> <span m=\"713920\">vertex</span> <span m=\"714370\">in</span> <span\
  \ m=\"714490\">B</span> <span m=\"715090\">is</span> <span m=\"715330\">complete</span>\
  \ <span m=\"715840\">to</span> <span m=\"716080\">A.</span> <span m=\"726499\">And</span>\
  \ <span m=\"726990\">finally,</span> <span m=\"727290\">A</span> <span m=\"727590\"\
  >and</span> <span m=\"727840\">B</span> <span m=\"728070\">should</span> <span m=\"\
  728250\">have</span> <span m=\"728370\">the</span> <span m=\"728460\">same</span>\
  \ <span m=\"728760\">size.</span></p><p><span m=\"732880\">So</span> <span m=\"\
  733060\">it</span> <span m=\"733150\">is</span> <span m=\"733300\">exactly</span>\
  \ <span m=\"733750\">the</span> <span m=\"733840\">configuration</span> <span m=\"\
  734560\">shown</span> <span m=\"734890\">up</span> <span m=\"735010\">there.</span>\
  \ <span m=\"735270\">Now,</span> <span m=\"735360\">when</span> <span m=\"735660\"\
  >n</span> <span m=\"735870\">is</span> <span m=\"736220\">odd,</span> <span m=\"\
  736930\">we're</span> <span m=\"737350\">rounding</span> <span m=\"737950\">down</span>\
  \ <span m=\"738280\">by</span> <span m=\"738490\">1.</span> <span m=\"738790\">So</span>\
  \ <span m=\"739030\">you</span> <span m=\"739150\">can</span> <span m=\"739300\"\
  >lose</span> <span m=\"739570\">a</span> <span m=\"739630\">little</span> <span\
  \ m=\"739840\">bit.</span> <span m=\"740580\">But</span> <span m=\"740860\">you</span>\
  \ <span m=\"740950\">can</span> <span m=\"741100\">check</span> <span m=\"741490\"\
  >that</span> <span m=\"741940\">actually</span> <span m=\"742750\">what</span> <span\
  \ m=\"742870\">we</span> <span m=\"743020\">described</span> <span m=\"743500\"\
  >up</span> <span m=\"743620\">there</span> <span m=\"743860\">is</span> <span m=\"\
  744160\">also</span> <span m=\"744600\">the</span> <span m=\"744670\">unique</span>\
  \ <span m=\"745040\">example.</span> <span m=\"749080\">So</span> <span m=\"749730\"\
  >that</span> <span m=\"749940\">graph,</span> <span m=\"750270\">the</span> <span\
  \ m=\"750360\">complete</span> <span m=\"750720\">bipartite</span> <span m=\"751140\"\
  >graph</span> <span m=\"751380\">with</span> <span m=\"751470\">two</span> <span\
  \ m=\"751650\">equal</span> <span m=\"751920\">parts,</span> <span m=\"752820\"\
  >is</span> <span m=\"753060\">the</span> <span m=\"753180\">unique</span> <span\
  \ m=\"753840\">maximal</span> <span m=\"754350\">example,</span> <span m=\"755530\"\
  >number</span> <span m=\"755730\">of</span> <span m=\"756120\">edges</span> <span\
  \ m=\"756810\">in</span> <span m=\"756910\">a</span> <span m=\"756960\">triangle-free</span>\
  \ <span m=\"757520\">graph.</span></p><p><span m=\"762216\">Great.</span> <span\
  \ m=\"763210\">So</span> <span m=\"764290\">once</span> <span m=\"764560\">we</span>\
  \ <span m=\"764710\">know</span> <span m=\"765070\">what</span> <span m=\"765280\"\
  >the</span> <span m=\"765400\">answer</span> <span m=\"765730\">is</span> <span\
  \ m=\"765970\">for</span> <span m=\"766330\">triangle-free,</span> <span m=\"767140\"\
  >of</span> <span m=\"767230\">course,</span> <span m=\"767530\">we</span> <span\
  \ m=\"767680\">should</span> <span m=\"767920\">ask</span> <span m=\"768370\">further</span>\
  \ <span m=\"768760\">questions.</span> <span m=\"769240\">Instead</span> <span m=\"\
  769570\">of</span> <span m=\"769630\">forbidding</span> <span m=\"770050\">a</span>\
  \ <span m=\"770110\">triangle,</span> <span m=\"770950\">what</span> <span m=\"\
  771160\">if</span> <span m=\"771280\">we</span> <span m=\"771430\">forbid</span>\
  \ <span m=\"772150\">other</span> <span m=\"772360\">graphs?</span> <span m=\"773520\"\
  >And</span> <span m=\"774190\">what</span> <span m=\"774340\">are</span> <span m=\"\
  774430\">some</span> <span m=\"774640\">natural</span> <span m=\"775390\">next</span>\
  \ <span m=\"775720\">steps</span> <span m=\"775990\">to</span> <span m=\"776080\"\
  >take?</span></p><p><span m=\"777570\">Well,</span> <span m=\"777640\">say,</span>\
  \ <span m=\"777850\">instead</span> <span m=\"778180\">of</span> <span m=\"778240\"\
  >triangles,</span> <span m=\"779170\">we</span> <span m=\"779320\">can</span> <span\
  \ m=\"779470\">ask,</span> <span m=\"780490\">what</span> <span m=\"780670\">about</span>\
  \ <span m=\"781420\">if</span> <span m=\"781570\">we</span> <span m=\"781690\">forbid</span>\
  \ <span m=\"782730\">a</span> <span m=\"783210\">K4,</span> <span m=\"784050\">a</span>\
  \ <span m=\"784090\">clique</span> <span m=\"784390\">of</span> <span m=\"784510\"\
  >four</span> <span m=\"784720\">vertices?</span> <span m=\"786550\">Or</span> <span\
  \ m=\"786910\">in</span> <span m=\"787030\">general,</span> <span m=\"787480\">what</span>\
  \ <span m=\"787690\">if</span> <span m=\"787780\">we</span> <span m=\"787900\">forbid</span>\
  \ <span m=\"788610\">a</span> <span m=\"788710\">clique</span> <span m=\"789580\"\
  >on</span> <span m=\"789780\">the</span> <span m=\"789870\">fixed</span> <span m=\"\
  790240\">number</span> <span m=\"790570\">of</span> <span m=\"790630\">vertices?</span>\
  \ <span m=\"791170\">So</span> <span m=\"791620\">what</span> <span m=\"791800\"\
  >is</span> <span m=\"791890\">the</span> <span m=\"791980\">maximum</span> <span\
  \ m=\"792580\">number</span> <span m=\"792970\">of</span> <span m=\"793120\">edges</span>\
  \ <span m=\"795280\">in</span> <span m=\"796030\">a</span> <span m=\"796210\">Kr</span>\
  \ <span m=\"797680\">plus</span> <span m=\"797990\">1-free--</span> <span m=\"800450\"\
  >there's</span> <span m=\"800630\">a</span> <span m=\"800660\">good</span> <span\
  \ m=\"800810\">reason</span> <span m=\"801050\">why</span> <span m=\"801260\">index</span>\
  \ <span m=\"801630\">is</span> <span m=\"801740\">r</span> <span m=\"801860\">plus</span>\
  \ <span m=\"802110\">1--</span> <span m=\"804080\">graph</span> <span m=\"805832\"\
  >on</span> <span m=\"806720\">n</span> <span m=\"807320\">vertices.</span></p><p><span\
  \ m=\"808670\">So</span> <span m=\"808880\">for</span> <span m=\"809060\">example,</span>\
  \ <span m=\"810090\">if</span> <span m=\"810140\">we're</span> <span m=\"810260\"\
  >interested</span> <span m=\"810800\">in</span> <span m=\"811610\">K4-free--</span>\
  \ <span m=\"818400\">so</span> <span m=\"818460\">what</span> <span m=\"818730\"\
  >might</span> <span m=\"818940\">be</span> <span m=\"819060\">a</span> <span m=\"\
  819120\">good</span> <span m=\"819300\">candidate</span> <span m=\"819870\">for</span>\
  \ <span m=\"820050\">a</span> <span m=\"820080\">graph</span> <span m=\"820410\"\
  >with</span> <span m=\"820560\">lots</span> <span m=\"820830\">of</span> <span m=\"\
  820950\">edges</span> <span m=\"821960\">that</span> <span m=\"822150\">has</span>\
  \ <span m=\"822360\">no</span> <span m=\"822540\">K4's?</span> <span m=\"822790\"\
  >I</span> <span m=\"823060\">mean,</span> <span m=\"823160\">certainly,</span> <span\
  \ m=\"823450\">that</span> <span m=\"823790\">example</span> <span m=\"824190\"\
  >we</span> <span m=\"824310\">saw,</span> <span m=\"824610\">it</span> <span m=\"\
  824955\">does</span> <span m=\"825210\">not</span> <span m=\"825390\">have</span>\
  \ <span m=\"825570\">K4's,</span> <span m=\"825960\">because</span> <span m=\"826170\"\
  >it</span> <span m=\"826260\">doesn't</span> <span m=\"826440\">have</span> <span\
  \ m=\"826560\">any</span> <span m=\"826710\">triangles.</span> <span m=\"827540\"\
  >But</span> <span m=\"827790\">we</span> <span m=\"827910\">can</span> <span m=\"\
  828060\">do</span> <span m=\"828210\">even</span> <span m=\"828450\">better.</span></p><p><span\
  \ m=\"830820\">Instead</span> <span m=\"831180\">of</span> <span m=\"831690\">taking</span>\
  \ <span m=\"832260\">two</span> <span m=\"832440\">parts,</span> <span m=\"833250\"\
  >you</span> <span m=\"833340\">can</span> <span m=\"833520\">take</span> <span m=\"\
  834390\">more</span> <span m=\"834570\">parts.</span> <span m=\"835860\">For</span>\
  \ <span m=\"836070\">K4,</span> <span m=\"837000\">if</span> <span m=\"837120\"\
  >I</span> <span m=\"837210\">take</span> <span m=\"837870\">three</span> <span m=\"\
  838140\">parts,</span> <span m=\"840220\">each</span> <span m=\"840450\">with</span>\
  \ <span m=\"841080\">n/3</span> <span m=\"842520\">number</span> <span m=\"842820\"\
  >of</span> <span m=\"842940\">vertices,</span> <span m=\"843480\">of</span> <span\
  \ m=\"843540\">course,</span> <span m=\"843910\">if n</span> <span m=\"844140\"\
  >is</span> <span m=\"844260\">not</span> <span m=\"844440\">divisible</span> <span\
  \ m=\"844800\">by</span> <span m=\"844920\">3,</span> <span m=\"845160\">round</span>\
  \ <span m=\"845430\">up</span> <span m=\"845580\">and</span> <span m=\"845700\"\
  >run</span> <span m=\"845830\">down.</span> <span m=\"847020\">And</span> <span\
  \ m=\"847320\">putting</span> <span m=\"847830\">all</span> <span m=\"848010\">the</span>\
  \ <span m=\"848160\">edges</span> <span m=\"849300\">between</span> <span m=\"852060\"\
  >different</span> <span m=\"852330\">parts,</span> <span m=\"853680\">you</span>\
  \ <span m=\"853770\">can</span> <span m=\"853890\">see</span> <span m=\"854040\"\
  >this</span> <span m=\"854250\">graph</span> <span m=\"854520\">here</span> <span\
  \ m=\"855330\">has</span> <span m=\"855540\">no</span> <span m=\"855690\">K4.</span>\
  \ <span m=\"858880\">So</span> <span m=\"859000\">that's</span> <span m=\"859160\"\
  >an</span> <span m=\"859280\">example</span> <span m=\"859670\">of</span> <span\
  \ m=\"859760\">a</span> <span m=\"859820\">K4-free</span> <span m=\"860390\">graph.</span>\
  \ <span m=\"862210\">Well,</span> <span m=\"862330\">does</span> <span m=\"862530\"\
  >it</span> <span m=\"862610\">have</span> <span m=\"862880\">the</span> <span m=\"\
  862970\">maximum</span> <span m=\"863540\">possible</span> <span m=\"863960\">number</span>\
  \ <span m=\"864290\">of</span> <span m=\"864410\">edges?</span> <span m=\"865670\"\
  >So</span> <span m=\"865870\">is</span> <span m=\"866020\">this</span> <span m=\"\
  866180\">the</span> <span m=\"866270\">best</span> <span m=\"866520\">that</span>\
  \ <span m=\"866640\">we</span> <span m=\"866780\">can</span> <span m=\"866900\"\
  >do?</span></p><p><span m=\"868270\">So</span> <span m=\"868430\">it</span> <span\
  \ m=\"868510\">turns</span> <span m=\"868720\">out</span> <span m=\"868810\">the</span>\
  \ <span m=\"868930\">answer</span> <span m=\"869230\">is</span> <span m=\"869350\"\
  >yes.</span> <span m=\"870220\">And</span> <span m=\"870340\">that's</span> <span\
  \ m=\"870550\">the</span> <span m=\"870640\">next</span> <span m=\"870940\">theorem</span>\
  \ <span m=\"871210\">that</span> <span m=\"871330\">we'll</span> <span m=\"871540\"\
  >see.</span> <span m=\"872820\">But</span> <span m=\"872950\">just</span> <span\
  \ m=\"873100\">to</span> <span m=\"873190\">give</span> <span m=\"873400\">it</span>\
  \ <span m=\"873460\">a</span> <span m=\"873520\">name,</span> <span m=\"874190\"\
  >so</span> <span m=\"874360\">we're</span> <span m=\"874540\">going</span> <span\
  \ m=\"874750\">to</span> <span m=\"874840\">call</span> <span m=\"875560\">graphs</span>\
  \ <span m=\"875950\">like</span> <span m=\"876130\">these</span> <span m=\"876490\"\
  >Tur\xE1n</span> <span m=\"876940\">graphs.</span> <span m=\"878010\">So</span>\
  \ <span m=\"878200\">the</span> <span m=\"878320\">next</span> <span m=\"878620\"\
  >theorem</span> <span m=\"879325\">is</span> <span m=\"879580\">proved</span> <span\
  \ m=\"879940\">by</span> <span m=\"880460\">Tur\xE1n.</span> <span m=\"880735\"\
  >It's</span> <span m=\"881010\">Tur\xE1n's</span> <span m=\"881460\">theorem.</span>\
  \ <span m=\"882100\">So</span> <span m=\"882725\">a</span> <span m=\"883110\">Tur\xE1\
  n</span> <span m=\"883510\">graph,</span> <span m=\"884510\">so we'll</span> <span\
  \ m=\"884810\">denote</span> <span m=\"886940\">T</span> <span m=\"887410\">sub</span>\
  \ <span m=\"887590\">nr.</span> <span m=\"888940\">It</span> <span m=\"889090\"\
  >is</span> <span m=\"889270\">a</span> <span m=\"889420\">complete</span> <span\
  \ m=\"892330\">r-partite</span> <span m=\"892940\">graph</span> <span m=\"899090\"\
  >such</span> <span m=\"899450\">that</span> <span m=\"900770\">there</span> <span\
  \ m=\"900920\">are</span> <span m=\"901360\">n</span> <span m=\"901610\">vertices</span>\
  \ <span m=\"904220\">whose</span> <span m=\"904420\">part</span> <span m=\"904810\"\
  >sizes</span> <span m=\"906250\">are</span> <span m=\"906400\">all</span> <span\
  \ m=\"906730\">nearly</span> <span m=\"907150\">the</span> <span m=\"907240\">same,</span>\
  \ <span m=\"910000\">up</span> <span m=\"910150\">to</span> <span m=\"910500\">at\
  \ most</span> <span m=\"910900\">1</span> <span m=\"911320\">difference.</span></p><p><span\
  \ m=\"918160\">So</span> <span m=\"918570\">this</span> <span m=\"918720\">is</span>\
  \ <span m=\"918810\">an</span> <span m=\"918930\">example</span> <span m=\"919350\"\
  >here.</span> <span m=\"919930\">But</span> <span m=\"920080\">in</span> <span m=\"\
  920520\">general,</span> <span m=\"921240\">maybe</span> <span m=\"921480\">you</span>\
  \ <span m=\"921630\">have</span> <span m=\"925170\">r</span> <span m=\"925340\"\
  >parts.</span> <span m=\"928460\">And</span> <span m=\"930200\">I</span> <span m=\"\
  930410\">put</span> <span m=\"930700\">in</span> <span m=\"936434\">all the</span>\
  \ <span m=\"937430\">edges</span> <span m=\"937670\">between</span> <span m=\"938060\"\
  >different</span> <span m=\"938390\">parts.</span></p><p><span m=\"943720\">So</span>\
  \ <span m=\"943840\">it's</span> <span m=\"943960\">not</span> <span m=\"944140\"\
  >too</span> <span m=\"944290\">hard</span> <span m=\"944470\">to</span> <span m=\"\
  944560\">calculate</span> <span m=\"945010\">the</span> <span m=\"945100\">number</span>\
  \ <span m=\"945400\">of</span> <span m=\"945530\">edges</span> <span m=\"945940\"\
  >in</span> <span m=\"946060\">such</span> <span m=\"946270\">a</span> <span m=\"\
  946330\">graph.</span> <span m=\"947470\">And</span> <span m=\"947680\">Tur\xE1\
  n's</span> <span m=\"948160\">theorem</span> <span m=\"948430\">tells</span> <span\
  \ m=\"948730\">us</span> <span m=\"949000\">that</span> <span m=\"949480\">that</span>\
  \ <span m=\"949660\">is</span> <span m=\"949810\">the</span> <span m=\"949960\"\
  >extremal</span> <span m=\"950470\">example.</span> <span m=\"951620\">You</span>\
  \ <span m=\"951640\">cannot</span> <span m=\"952030\">do</span> <span m=\"952210\"\
  >better</span> <span m=\"953530\">in</span> <span m=\"953650\">terms</span> <span\
  \ m=\"953950\">of</span> <span m=\"954070\">getting</span> <span m=\"954760\">more</span>\
  \ <span m=\"955380\">edges.</span> <span m=\"965510\">So</span> <span m=\"965610\"\
  >if</span> <span m=\"966210\">G</span> <span m=\"967504\">is</span> <span m=\"967956\"\
  >an</span> <span m=\"968860\">n</span> <span m=\"969080\">vertex,</span> <span m=\"\
  971950\">try</span> <span m=\"972270\">a</span> <span m=\"972810\">K</span> <span\
  \ m=\"973250\">sub</span> <span m=\"973660\">r</span> <span m=\"973820\">plus</span>\
  \ <span m=\"974120\">1-free</span> <span m=\"975500\">graph.</span> <span m=\"978610\"\
  >Then</span> <span m=\"980870\">it</span> <span m=\"981010\">has</span> <span m=\"\
  983100\">at</span> <span m=\"983260\">most</span> <span m=\"984580\">the</span>\
  \ <span m=\"984730\">number</span> <span m=\"985060\">of</span> <span m=\"985180\"\
  >edges</span> <span m=\"985960\">of</span> <span m=\"987220\">the</span> <span m=\"\
  987550\">Tur\xE1n</span> <span m=\"987910\">graph.</span></p><p><span m=\"996020\"\
  >It's</span> <span m=\"996040\">a</span> <span m=\"996110\">generalization</span>\
  \ <span m=\"996800\">of</span> <span m=\"996890\">Mantel's</span> <span m=\"997310\"\
  >theorem.</span> <span m=\"998360\">And</span> <span m=\"999265\">well,</span> <span\
  \ m=\"999750\">you</span> <span m=\"999830\">can</span> <span m=\"999980\">think</span>\
  \ <span m=\"1000160\">about</span> <span m=\"1000610\">if</span> <span m=\"1001420\"\
  >the</span> <span m=\"1001540\">proofs</span> <span m=\"1001930\">that</span> <span\
  \ m=\"1002050\">we</span> <span m=\"1002170\">did</span> <span m=\"1002350\">for</span>\
  \ <span m=\"1002490\">Mantel's</span> <span m=\"1003230\">generalizes</span> <span\
  \ m=\"1004510\">to</span> <span m=\"1004960\">Tur\xE1n's</span> <span m=\"1005275\"\
  >theorem.</span> <span m=\"1006310\">And</span> <span m=\"1006660\">it's</span>\
  \ <span m=\"1006790\">actually</span> <span m=\"1007840\">not</span> <span m=\"\
  1008050\">entirely</span> <span m=\"1009100\">clear</span> <span m=\"1009400\">how</span>\
  \ <span m=\"1009550\">to</span> <span m=\"1009640\">do</span> <span m=\"1009790\"\
  >it.</span> <span m=\"1010360\">So</span> <span m=\"1010480\">let</span> <span m=\"\
  1010570\">me</span> <span m=\"1010690\">present</span> <span m=\"1011320\">for</span>\
  \ <span m=\"1011500\">you</span> <span m=\"1012380\">three</span> <span m=\"1012640\"\
  >different</span> <span m=\"1012910\">proofs</span> <span m=\"1013390\">of</span>\
  \ <span m=\"1014080\">Tur\xE1n's</span> <span m=\"1014460\">theorem.</span></p><p><span\
  \ m=\"1015640\">So some</span> <span m=\"1015820\">of</span> <span m=\"1015910\"\
  >them,</span> <span m=\"1016030\">you</span> <span m=\"1016090\">can</span> <span\
  \ m=\"1016240\">think</span> <span m=\"1016450\">about,</span> <span m=\"1017140\"\
  >are</span> <span m=\"1017260\">they</span> <span m=\"1017380\">related</span> <span\
  \ m=\"1017800\">to</span> <span m=\"1018100\">the</span> <span m=\"1018220\">proofs</span>\
  \ <span m=\"1018520\">of</span> <span m=\"1018610\">Mantel's</span> <span m=\"1019030\"\
  >theorem</span> <span m=\"1019240\">that</span> <span m=\"1019390\">we</span> <span\
  \ m=\"1019510\">did?</span> <span m=\"1019650\">And</span> <span m=\"1019790\">they</span>\
  \ <span m=\"1019900\">all</span> <span m=\"1020320\">are</span> <span m=\"1020410\"\
  >going</span> <span m=\"1020590\">to</span> <span m=\"1020650\">look</span> <span\
  \ m=\"1021250\">somewhat</span> <span m=\"1021580\">different,</span> <span m=\"\
  1021970\">but</span> <span m=\"1022690\">maybe</span> <span m=\"1022930\">superficially.</span></p><p><span\
  \ m=\"1026280\">The</span> <span m=\"1026369\">first</span> <span m=\"1026609\"\
  >proof,</span> <span m=\"1029950\">we</span> <span m=\"1030099\">will</span> <span\
  \ m=\"1030250\">use</span> <span m=\"1030760\">induction</span> <span m=\"1033930\"\
  >on</span> <span m=\"1034520\">the</span> <span m=\"1034609\">number</span> <span\
  \ m=\"1034940\">of</span> <span m=\"1035000\">vertices.</span> <span m=\"1038250\"\
  >So</span> <span m=\"1038700\">actually,</span> <span m=\"1038990\">this</span>\
  \ <span m=\"1039200\">is</span> <span m=\"1039319\">one</span> <span m=\"1039550\"\
  >of the</span> <span m=\"1039640\">very</span> <span m=\"1039920\">few</span> <span\
  \ m=\"1040190\">times</span> <span m=\"1040550\">in</span> <span m=\"1040640\">this</span>\
  \ <span m=\"1040760\">course</span> <span m=\"1041089\">where</span> <span m=\"\
  1041240\">we</span> <span m=\"1041390\">will</span> <span m=\"1041599\">see</span>\
  \ <span m=\"1041839\">induction.</span> <span m=\"1043470\">So</span> <span m=\"\
  1043609\">of</span> <span m=\"1043730\">course,</span> <span m=\"1043910\">induction</span>\
  \ <span m=\"1044300\">is</span> <span m=\"1044359\">a</span> <span m=\"1044420\"\
  >powerful</span> <span m=\"1044780\">technique</span> <span m=\"1045170\">in</span>\
  \ <span m=\"1045260\">combinatorics.</span> <span m=\"1045920\">But</span> <span\
  \ m=\"1046339\">for</span> <span m=\"1046730\">almost</span> <span m=\"1047089\"\
  >the</span> <span m=\"1047180\">rest</span> <span m=\"1047450\">of</span> <span\
  \ m=\"1047510\">the</span> <span m=\"1047599\">course,</span> <span m=\"1048000\"\
  >we're</span> <span m=\"1048079\">not</span> <span m=\"1048230\">going</span> <span\
  \ m=\"1048380\">to</span> <span m=\"1048440\">have</span> <span m=\"1048650\">clean</span>\
  \ <span m=\"1049070\">examples.</span> <span m=\"1050030\">And</span> <span m=\"\
  1050120\">when</span> <span m=\"1050210\">we</span> <span m=\"1050330\">do</span>\
  \ <span m=\"1050450\">have</span> <span m=\"1050600\">clean</span> <span m=\"1050900\"\
  >examples</span> <span m=\"1051380\">to</span> <span m=\"1051470\">work</span> <span\
  \ m=\"1051710\">with,</span> <span m=\"1052280\">somehow</span> <span m=\"1053060\"\
  >increasing</span> <span m=\"1053420\">n</span> <span m=\"1053780\">by</span> <span\
  \ m=\"1053960\">1</span> <span m=\"1055070\">doesn't</span> <span m=\"1055310\"\
  >buy</span> <span m=\"1055520\">you</span> <span m=\"1055670\">all</span> <span\
  \ m=\"1055790\">that</span> <span m=\"1055970\">much.</span> <span m=\"1056640\"\
  >Here,</span> <span m=\"1057600\">there</span> <span m=\"1057970\">are</span> <span\
  \ m=\"1058040\">very</span> <span m=\"1058250\">clean</span> <span m=\"1058580\"\
  >examples,</span> <span m=\"1059060\">very</span> <span m=\"1059240\">clean</span>\
  \ <span m=\"1059540\">answers,</span> <span m=\"1060020\">and</span> <span m=\"\
  1060170\">induction</span> <span m=\"1060650\">works</span> <span m=\"1060980\"\
  >out</span> <span m=\"1061910\">quite</span> <span m=\"1062150\">well.</span></p><p><span\
  \ m=\"1065640\">When</span> <span m=\"1065850\">n</span> <span m=\"1066080\">is</span>\
  \ <span m=\"1066230\">small,</span> <span m=\"1066710\">of</span> <span m=\"1066810\"\
  >course,</span> <span m=\"1067020\">you should</span> <span m=\"1067290\">always</span>\
  \ <span m=\"1067590\">address</span> <span m=\"1067890\">that.</span> <span m=\"\
  1068130\">You can</span> <span m=\"1068340\">come</span> <span m=\"1068580\">up</span>\
  \ <span m=\"1068640\">with</span> <span m=\"1068790\">many</span> <span m=\"1069030\"\
  >funny</span> <span m=\"1069270\">proofs</span> <span m=\"1069600\">if</span> <span\
  \ m=\"1069690\">you</span> <span m=\"1069780\">don't</span> <span m=\"1069930\"\
  >address</span> <span m=\"1070290\">when n is</span> <span m=\"1070700\">small.</span>\
  \ <span m=\"1071040\">So</span> <span m=\"1071340\">when</span> <span m=\"1071500\"\
  >n</span> <span m=\"1071720\">is</span> <span m=\"1071820\">small,</span> <span\
  \ m=\"1072160\">this</span> <span m=\"1072960\">problem</span> <span m=\"1073245\"\
  >is</span> <span m=\"1074610\">basically</span> <span m=\"1075000\">trivial.</span>\
  \ <span m=\"1075840\">n</span> <span m=\"1075990\">is</span> <span m=\"1076110\"\
  >almost</span> <span m=\"1076380\">r.</span> <span m=\"1077310\">You</span> <span\
  \ m=\"1078150\">could</span> <span m=\"1078270\">have</span> <span m=\"1078460\"\
  >the</span> <span m=\"1078510\">complete</span> <span m=\"1078870\">graph</span>\
  \ <span m=\"1079170\">on</span> <span m=\"1079610\">r</span> <span m=\"1079710\"\
  >vertices.</span> <span m=\"1081210\">And</span> <span m=\"1081570\">then</span>\
  \ <span m=\"1081690\">we're</span> <span m=\"1081860\">good.</span></p><p><span\
  \ m=\"1083350\">So</span> <span m=\"1083430\">let's</span> <span m=\"1083610\">assume</span>\
  \ <span m=\"1087060\">that</span> <span m=\"1088890\">we're</span> <span m=\"1089040\"\
  >not</span> <span m=\"1089280\">in</span> <span m=\"1089400\">this</span> <span\
  \ m=\"1089550\">case.</span> <span m=\"1090090\">And</span> <span m=\"1090210\"\
  >also,</span> <span m=\"1090420\">by</span> <span m=\"1090600\">induction</span>\
  \ <span m=\"1091080\">hypothesis,</span> <span m=\"1091810\">let's</span> <span\
  \ m=\"1091890\">assume</span> <span m=\"1092280\">that</span> <span m=\"1092790\"\
  >it</span> <span m=\"1092940\">is</span> <span m=\"1093060\">true</span> <span m=\"\
  1093690\">for</span> <span m=\"1094320\">all</span> <span m=\"1094500\">graphs</span>\
  \ <span m=\"1098540\">fewer</span> <span m=\"1098870\">than</span> <span m=\"1099060\"\
  >n</span> <span m=\"1099530\">vertices.</span> <span m=\"1104480\">And</span> <span\
  \ m=\"1104660\">let</span> <span m=\"1105250\">G</span> <span m=\"1105520\">be</span>\
  \ <span m=\"1105710\">a</span> <span m=\"1105830\">graph</span> <span m=\"1109490\"\
  >that</span> <span m=\"1109700\">is</span> <span m=\"1110840\">K</span> <span m=\"\
  1111260\">sub</span> <span m=\"1111680\">r</span> <span m=\"1111830\">plus</span>\
  \ <span m=\"1112070\">1-free</span> <span m=\"1114131\">on</span> <span m=\"1114590\"\
  >n</span> <span m=\"1114800\">vertices.</span></p><p><span m=\"1116990\">And</span>\
  \ <span m=\"1117290\">also,</span> <span m=\"1118220\">let's</span> <span m=\"1118430\"\
  >assume</span> <span m=\"1119000\">a</span> <span m=\"1119120\">maximum</span> <span\
  \ m=\"1119900\">example</span> <span m=\"1120410\">to</span> <span m=\"1120560\"\
  >begin</span> <span m=\"1120860\">with.</span> <span m=\"1121800\">So</span> <span\
  \ m=\"1121880\">let's</span> <span m=\"1122090\">assume</span> <span m=\"1122870\"\
  >that</span> <span m=\"1123290\">the</span> <span m=\"1123440\">G</span> <span m=\"\
  1123690\">that</span> <span m=\"1123860\">you</span> <span m=\"1123980\">chose</span>\
  \ <span m=\"1124610\">has</span> <span m=\"1125000\">already</span> <span m=\"1125750\"\
  >the</span> <span m=\"1125870\">maximum</span> <span m=\"1126830\">possible</span>\
  \ <span m=\"1127580\">number</span> <span m=\"1127940\">of</span> <span m=\"1128120\"\
  >edges.</span> <span m=\"1130350\">There are</span> <span m=\"1130810\">only</span>\
  \ <span m=\"1131060\">finite</span> <span m=\"1131360\">of any</span> <span m=\"\
  1131540\">such</span> <span m=\"1131810\">examples.</span> <span m=\"1132310\">So</span>\
  \ <span m=\"1132410\">pick</span> <span m=\"1132620\">one</span> <span m=\"1132860\"\
  >that</span> <span m=\"1132950\">already</span> <span m=\"1133310\">has</span> <span\
  \ m=\"1133580\">the</span> <span m=\"1133670\">maximum</span> <span m=\"1134240\"\
  >number</span> <span m=\"1134510\">of</span> <span m=\"1134630\">edges.</span> <span\
  \ m=\"1135230\">And</span> <span m=\"1135350\">let's</span> <span m=\"1135530\"\
  >think</span> <span m=\"1135680\">about</span> <span m=\"1135890\">what</span> <span\
  \ m=\"1136010\">properties</span> <span m=\"1136580\">this</span> <span m=\"1136760\"\
  >graph</span> <span m=\"1137030\">G</span> <span m=\"1137210\">has.</span></p><p><span\
  \ m=\"1139190\">I</span> <span m=\"1139310\">claim</span> <span m=\"1140480\">that</span>\
  \ <span m=\"1140930\">G</span> <span m=\"1141950\">must</span> <span m=\"1142700\"\
  >already</span> <span m=\"1143090\">contain</span> <span m=\"1145490\">a</span>\
  \ <span m=\"1146040\">clique</span> <span m=\"1146930\">on</span> <span m=\"1147940\"\
  >r</span> <span m=\"1148360\">vertices.</span> <span m=\"1153230\">So</span> <span\
  \ m=\"1153310\">think</span> <span m=\"1153490\">about</span> <span m=\"1153680\"\
  >that.</span> <span m=\"1154390\">If</span> <span m=\"1154560\">G</span> <span m=\"\
  1154900\">does</span> <span m=\"1155110\">not</span> <span m=\"1155770\">contain</span>\
  \ <span m=\"1156340\">a</span> <span m=\"1156400\">clique</span> <span m=\"1156820\"\
  >on</span> <span m=\"1157150\">r vertices,</span> <span m=\"1158290\">then</span>\
  \ <span m=\"1158560\">I</span> <span m=\"1158680\">can</span> <span m=\"1159010\"\
  >add</span> <span m=\"1159250\">in</span> <span m=\"1159580\">more</span> <span\
  \ m=\"1159820\">edges.</span> <span m=\"1168600\">And</span> <span m=\"1168960\"\
  >I</span> <span m=\"1169050\">can</span> <span m=\"1169230\">still</span> <span\
  \ m=\"1169620\">maintain</span> <span m=\"1172940\">the</span> <span m=\"1173020\"\
  >property</span> <span m=\"1174100\">of</span> <span m=\"1174280\">being</span>\
  \ <span m=\"1174700\">K</span> <span m=\"1175150\">sub</span> <span m=\"1175260\"\
  >r</span> <span m=\"1175460\">plus</span> <span m=\"1175700\">1-free.</span> <span\
  \ m=\"1180480\">So</span> <span m=\"1180720\">I</span> <span m=\"1180810\">can</span>\
  \ <span m=\"1180990\">assume</span> <span m=\"1181260\">that</span> <span m=\"1181440\"\
  >G</span> <span m=\"1181650\">must</span> <span m=\"1181890\">contain</span> <span\
  \ m=\"1182370\">a</span> <span m=\"1182760\">K sub</span> <span m=\"1183030\">r.</span>\
  \ <span m=\"1184320\">So</span> <span m=\"1184470\">let's</span> <span m=\"1184680\"\
  >look</span> <span m=\"1184950\">at</span> <span m=\"1185490\">one</span> <span\
  \ m=\"1185700\">of</span> <span m=\"1185760\">these</span> <span m=\"1186150\">K</span>\
  \ <span m=\"1186450\">sub</span> <span m=\"1186570\">r's.</span></p><p><span m=\"\
  1188320\">So</span> <span m=\"1188460\">let</span> <span m=\"1190330\">n</span>\
  \ <span m=\"1192060\">be</span> <span m=\"1193040\">the</span> <span m=\"1193140\"\
  >vertices</span> <span m=\"1196040\">of</span> <span m=\"1197140\">some</span> <span\
  \ m=\"1198450\">r</span> <span m=\"1198950\">clique</span> <span m=\"1202330\">in\
  \ G.</span> <span m=\"1204200\">So</span> <span m=\"1204560\">we</span> <span m=\"\
  1204680\">have</span> <span m=\"1205870\">some</span> <span m=\"1206300\">A.</span>\
  \ <span m=\"1209895\">And</span> <span m=\"1211320\">the</span> <span m=\"1211490\"\
  >complement</span> <span m=\"1211810\">to</span> <span m=\"1212130\">that,</span>\
  \ <span m=\"1212420\">let</span> <span m=\"1212540\">me</span> <span m=\"1212660\"\
  >call</span> <span m=\"1212870\">that</span> <span m=\"1213140\">B.</span></p><p><span\
  \ m=\"1221490\">Look</span> <span m=\"1221670\">at</span> <span m=\"1221730\">the</span>\
  \ <span m=\"1221820\">vertex</span> <span m=\"1222300\">in</span> <span m=\"1222420\"\
  >B.</span> <span m=\"1225330\">How</span> <span m=\"1225510\">many</span> <span\
  \ m=\"1226050\">neighbors</span> <span m=\"1226530\">can</span> <span m=\"1226770\"\
  >have</span> <span m=\"1227090\">in</span> <span m=\"1227310\">A?</span> <span m=\"\
  1228940\">It</span> <span m=\"1229310\">cannot</span> <span m=\"1229670\">be</span>\
  \ <span m=\"1229820\">complete</span> <span m=\"1230200\">to</span> <span m=\"1230580\"\
  >A,</span> <span m=\"1231050\">otherwise</span> <span m=\"1231590\">I</span> <span\
  \ m=\"1231680\">would</span> <span m=\"1231910\">have</span> <span m=\"1232230\"\
  >an</span> <span m=\"1232600\">r</span> <span m=\"1232730\">plus</span> <span m=\"\
  1233000\">1</span> <span m=\"1233210\">clique.</span> <span m=\"1234610\">So</span>\
  \ <span m=\"1234870\">every</span> <span m=\"1237450\">vertex</span> <span m=\"\
  1237805\">in</span> <span m=\"1238160\">B</span> <span m=\"1239640\">has</span>\
  \ <span m=\"1240560\">at</span> <span m=\"1240690\">most</span> <span m=\"1241400\"\
  >r</span> <span m=\"1241560\">minus 1</span> <span m=\"1241920\">neighbors</span>\
  \ <span m=\"1246440\">in</span> <span m=\"1246915\">A.</span></p><p><span m=\"1251200\"\
  >So</span> <span m=\"1252030\">let's</span> <span m=\"1252240\">count</span> <span\
  \ m=\"1253020\">all</span> <span m=\"1253140\">the</span> <span m=\"1253290\">edges.</span>\
  \ <span m=\"1256640\">The</span> <span m=\"1256750\">number</span> <span m=\"1257050\"\
  >of</span> <span m=\"1257140\">edges</span> <span m=\"1257800\">in</span> <span\
  \ m=\"1258160\">G</span> <span m=\"1259500\">is</span> <span m=\"1259660\">that</span>\
  \ <span m=\"1259810\">most--</span> <span m=\"1260530\">well,</span> <span m=\"\
  1260680\">first,</span> <span m=\"1261700\">we</span> <span m=\"1261850\">should</span>\
  \ <span m=\"1262030\">account</span> <span m=\"1262360\">for</span> <span m=\"1262480\"\
  >the</span> <span m=\"1262690\">edges</span> <span m=\"1263230\">inside</span> <span\
  \ m=\"1263770\">A.</span> <span m=\"1264070\">And</span> <span m=\"1264550\">there</span>\
  \ <span m=\"1264970\">are--</span> <span m=\"1265360\">or choose</span> <span m=\"\
  1265720\">two</span> <span m=\"1265900\">of</span> <span m=\"1266050\">them.</span>\
  \ <span m=\"1268730\">And</span> <span m=\"1268850\">then</span> <span m=\"1269860\"\
  >the</span> <span m=\"1269990\">edges</span> <span m=\"1270350\">between</span>\
  \ <span m=\"1270665\">A</span> <span m=\"1270980\">and</span> <span m=\"1271280\"\
  >B,</span> <span m=\"1272030\">for</span> <span m=\"1272240\">every</span> <span\
  \ m=\"1272600\">vertex</span> <span m=\"1273080\">in</span> <span m=\"1273170\"\
  >B,</span> <span m=\"1273830\">there</span> <span m=\"1274010\">are</span> <span\
  \ m=\"1274220\">at</span> <span m=\"1274400\">most</span> <span m=\"1275290\">r</span>\
  \ <span m=\"1275480\">minus</span> <span m=\"1275920\">1</span> <span m=\"1277700\"\
  >vertices</span> <span m=\"1278800\">going</span> <span m=\"1279050\">to</span>\
  \ <span m=\"1279370\">A</span> <span m=\"1280990\">for</span> <span m=\"1281300\"\
  >each</span> <span m=\"1281810\">vertex</span> <span m=\"1282380\">in</span> <span\
  \ m=\"1282560\">B.</span> <span m=\"1284460\">And</span> <span m=\"1284610\">finally,</span>\
  \ <span m=\"1286960\">the</span> <span m=\"1287260\">edge</span> <span m=\"1287600\"\
  >set</span> <span m=\"1288055\">of</span> <span m=\"1288510\">B.</span></p><p><span\
  \ m=\"1292650\">Well,</span> <span m=\"1293250\">we</span> <span m=\"1293370\">can</span>\
  \ <span m=\"1293520\">say</span> <span m=\"1293670\">something</span> <span m=\"\
  1293940\">more</span> <span m=\"1294120\">about</span> <span m=\"1294300\">these</span>\
  \ <span m=\"1294480\">quantities.</span> <span m=\"1298060\">We</span> <span m=\"\
  1298180\">know</span> <span m=\"1298360\">that</span> <span m=\"1298810\">the</span>\
  \ <span m=\"1298900\">size</span> <span m=\"1299200\">of</span> <span m=\"1299290\"\
  >B</span> <span m=\"1299560\">is</span> <span m=\"1299740\">exactly</span> <span\
  \ m=\"1301790\">n</span> <span m=\"1302080\">minus</span> <span m=\"1302470\">r.</span>\
  \ <span m=\"1305560\">But</span> <span m=\"1305680\">what</span> <span m=\"1305800\"\
  >can</span> <span m=\"1305920\">we</span> <span m=\"1306040\">say</span> <span m=\"\
  1306250\">about</span> <span m=\"1306520\">the</span> <span m=\"1306610\">number</span>\
  \ <span m=\"1306880\">of</span> <span m=\"1307000\">edges</span> <span m=\"1307330\"\
  >in</span> <span m=\"1307450\">B?</span> <span m=\"1309060\">We</span> <span m=\"\
  1309150\">can</span> <span m=\"1309330\">use</span> <span m=\"1310110\">induction</span>\
  \ <span m=\"1310530\">hypothesis.</span> <span m=\"1311450\">So</span> <span m=\"\
  1311770\">B</span> <span m=\"1312060\">is</span> <span m=\"1312210\">also</span>\
  \ <span m=\"1314190\">r</span> <span m=\"1314310\">plus</span> <span m=\"1314580\"\
  >1</span> <span m=\"1315060\">clique-free.</span> <span m=\"1315990\">So</span>\
  \ <span m=\"1316350\">the</span> <span m=\"1316470\">number</span> <span m=\"1316800\"\
  >of</span> <span m=\"1316920\">edges</span> <span m=\"1317460\">is</span> <span\
  \ m=\"1317620\">at most</span> <span m=\"1318360\">the</span> <span m=\"1318450\"\
  >number</span> <span m=\"1318690\">of</span> <span m=\"1318780\">edges</span> <span\
  \ m=\"1319080\">in</span> <span m=\"1319170\">a</span> <span m=\"1319230\">corresponding</span>\
  \ <span m=\"1320120\">Tur\xE1n</span> <span m=\"1320490\">graph.</span></p><p><span\
  \ m=\"1322920\">Now,</span> <span m=\"1323300\">at this</span> <span m=\"1323480\"\
  >point,</span> <span m=\"1323840\">you</span> <span m=\"1323960\">can</span> <span\
  \ m=\"1324590\">do</span> <span m=\"1324740\">a</span> <span m=\"1324800\">calculation.</span>\
  \ <span m=\"1325880\">Well,</span> <span m=\"1326030\">I</span> <span m=\"1326060\"\
  >mean,</span> <span m=\"1326180\">you</span> <span m=\"1326300\">should</span> <span\
  \ m=\"1326510\">expect</span> <span m=\"1326930\">that</span> <span m=\"1327050\"\
  >the</span> <span m=\"1327140\">answer</span> <span m=\"1328100\">we're</span> <span\
  \ m=\"1328220\">looking</span> <span m=\"1328490\">for</span> <span m=\"1329150\"\
  >is--</span> <span m=\"1330680\">I</span> <span m=\"1330740\">mean,</span> <span\
  \ m=\"1330860\">this</span> <span m=\"1331080\">should</span> <span m=\"1331250\"\
  >be</span> <span m=\"1331370\">equal</span> <span m=\"1331790\">to</span> <span\
  \ m=\"1332030\">the</span> <span m=\"1332150\">number</span> <span m=\"1332450\"\
  >of</span> <span m=\"1332570\">edges</span> <span m=\"1333350\">in</span> <span\
  \ m=\"1333470\">the</span> <span m=\"1333600\">Tur\xE1n</span> <span m=\"1333890\"\
  >graph.</span> <span m=\"1334430\">So</span> <span m=\"1334550\">you</span> <span\
  \ m=\"1334610\">can</span> <span m=\"1334760\">either</span> <span m=\"1335600\"\
  >do</span> <span m=\"1335750\">a</span> <span m=\"1335810\">calculation</span> <span\
  \ m=\"1336410\">to</span> <span m=\"1336500\">figure</span> <span m=\"1336770\"\
  >this</span> <span m=\"1336950\">out,</span> <span m=\"1337700\">or</span> <span\
  \ m=\"1338030\">remember</span> <span m=\"1338480\">what</span> <span m=\"1338630\"\
  >I</span> <span m=\"1338720\">said</span> <span m=\"1338930\">earlier,</span> <span\
  \ m=\"1339560\">that</span> <span m=\"1340940\">keep</span> <span m=\"1341390\"\
  >the</span> <span m=\"1341830\">tight</span> <span m=\"1342140\">example</span>\
  \ <span m=\"1342680\">in</span> <span m=\"1342770\">mind,</span> <span m=\"1343400\"\
  >and</span> <span m=\"1343520\">everything</span> <span m=\"1343880\">should</span>\
  \ <span m=\"1344690\">check</span> <span m=\"1344990\">out</span> <span m=\"1345110\"\
  >for</span> <span m=\"1345230\">the</span> <span m=\"1345320\">tight</span> <span\
  \ m=\"1345650\">example.</span></p><p><span m=\"1346640\">So</span> <span m=\"1346670\"\
  >in</span> <span m=\"1346760\">particular,</span> <span m=\"1348440\">if</span>\
  \ <span m=\"1348680\">you</span> <span m=\"1348860\">are</span> <span m=\"1349220\"\
  >in</span> <span m=\"1349350\">the</span> <span m=\"1349400\">situation</span> <span\
  \ m=\"1350570\">of</span> <span m=\"1351740\">a</span> <span m=\"1351980\">complete</span>\
  \ <span m=\"1352980\">multipartite</span> <span m=\"1353600\">graph</span> <span\
  \ m=\"1354230\">with</span> <span m=\"1356600\">equal</span> <span m=\"1356940\"\
  >size</span> <span m=\"1357330\">or</span> <span m=\"1357450\">nearly</span> <span\
  \ m=\"1357750\">equal-size</span> <span m=\"1358980\">parts,</span> <span m=\"1361880\"\
  >what</span> <span m=\"1362090\">is</span> <span m=\"1362300\">A?</span> <span m=\"\
  1369780\">So</span> <span m=\"1370070\">A</span> <span m=\"1370760\">is</span> <span\
  \ m=\"1371390\">one</span> <span m=\"1371660\">vertex</span> <span m=\"1372090\"\
  >from</span> <span m=\"1372230\">each</span> <span m=\"1372440\">part.</span> <span\
  \ m=\"1376270\">So you</span> <span m=\"1376640\">take</span> <span m=\"1376930\"\
  >out</span> <span m=\"1377180\">one</span> <span m=\"1377480\">vertex</span> <span\
  \ m=\"1377900\">from</span> <span m=\"1378020\">each</span> <span m=\"1378230\"\
  >part.</span> <span m=\"1382960\">And</span> <span m=\"1384250\">read</span> <span\
  \ m=\"1384550\">off</span> <span m=\"1384760\">this</span> <span m=\"1384940\">calculation</span>\
  \ <span m=\"1385690\">for</span> <span m=\"1385930\">this</span> <span m=\"1386090\"\
  >graph</span> <span m=\"1386440\">over</span> <span m=\"1386650\">here.</span> <span\
  \ m=\"1387610\">And</span> <span m=\"1387700\">then</span> <span m=\"1387790\">you</span>\
  \ <span m=\"1387880\">see</span> <span m=\"1388120\">that</span> <span m=\"1388330\"\
  >that</span> <span m=\"1388540\">is</span> <span m=\"1388690\">indeed</span> <span\
  \ m=\"1389110\">equality.</span> <span m=\"1390200\">So</span> <span m=\"1390300\"\
  >it</span> <span m=\"1390340\">should</span> <span m=\"1390520\">check</span> <span\
  \ m=\"1390730\">out.</span> <span m=\"1391000\">You</span> <span m=\"1391060\">don't</span>\
  \ <span m=\"1391240\">need</span> <span m=\"1391330\">to</span> <span m=\"1391420\"\
  >do</span> <span m=\"1391660\">any</span> <span m=\"1392320\">actual</span> <span\
  \ m=\"1392650\">calculations.</span></p><p><span m=\"1399150\">Any</span> <span\
  \ m=\"1399330\">questions</span> <span m=\"1400470\">about</span> <span m=\"1400710\"\
  >the</span> <span m=\"1400770\">proofs</span> <span m=\"1401100\">we've</span> <span\
  \ m=\"1401250\">done</span> <span m=\"1401430\">so</span> <span m=\"1401640\">far?</span>\
  \ <span m=\"1405285\">All</span> <span m=\"1405770\">right.</span> <span m=\"1408200\"\
  >Let</span> <span m=\"1408290\">me</span> <span m=\"1408380\">show</span> <span\
  \ m=\"1408590\">you</span> <span m=\"1408800\">another</span> <span m=\"1410000\"\
  >proof</span> <span m=\"1410330\">of</span> <span m=\"1410420\">Tur\xE1n's</span>\
  \ <span m=\"1410840\">theorem.</span></p><p><span m=\"1419390\">So</span> <span\
  \ m=\"1419570\">this</span> <span m=\"1419750\">proof</span> <span m=\"1422590\"\
  >has</span> <span m=\"1422770\">a</span> <span m=\"1422830\">name.</span> <span\
  \ m=\"1423970\">So</span> <span m=\"1424090\">it's</span> <span m=\"1424270\">called</span>\
  \ <span m=\"1424600\">Zykov's</span> <span m=\"1425200\">symmetrization.</span>\
  \ <span m=\"1435408\">So</span> <span m=\"1435910\">Zykov</span> <span m=\"1436390\"\
  >has</span> <span m=\"1436700\">the</span> <span m=\"1437120\">unfortunate</span>\
  \ <span m=\"1437690\">honor</span> <span m=\"1438020\">of</span> <span m=\"1438290\"\
  >having</span> <span m=\"1438560\">a</span> <span m=\"1438620\">name</span> <span\
  \ m=\"1438890\">that's</span> <span m=\"1439520\">hard</span> <span m=\"1439760\"\
  >to</span> <span m=\"1439880\">beat</span> <span m=\"1440120\">in</span> <span m=\"\
  1440210\">terms</span> <span m=\"1440510\">of</span> <span m=\"1440720\">alphabetical</span>\
  \ <span m=\"1441260\">order.</span> <span m=\"1442320\">I think,</span> <span m=\"\
  1442710\">if</span> <span m=\"1442790\">he</span> <span m=\"1442910\">and</span>\
  \ <span m=\"1443060\">I</span> <span m=\"1443180\">were</span> <span m=\"1443330\"\
  >to</span> <span m=\"1443450\">write</span> <span m=\"1443690\">a</span> <span m=\"\
  1443750\">paper,</span> <span m=\"1444260\">I</span> <span m=\"1444380\">wouldn't</span>\
  \ <span m=\"1444680\">be</span> <span m=\"1444800\">the</span> <span m=\"1444920\"\
  >last</span> <span m=\"1445210\">author.</span> <span m=\"1449730\">So</span> <span\
  \ m=\"1449850\">what's</span> <span m=\"1450060\">this</span> <span m=\"1450240\"\
  >about?</span></p><p><span m=\"1452550\">So</span> <span m=\"1452670\">let</span>\
  \ <span m=\"1453360\">G</span> <span m=\"1454980\">be</span> <span m=\"1455160\"\
  >the</span> <span m=\"1455280\">graph.</span> <span m=\"1456930\">Again,</span>\
  \ <span m=\"1457600\">as</span> <span m=\"1457680\">before,</span> <span m=\"1458100\"\
  >we're</span> <span m=\"1458310\">going</span> <span m=\"1458550\">to</span> <span\
  \ m=\"1458640\">take</span> <span m=\"1458840\">a</span> <span m=\"1458970\">maximal</span>\
  \ <span m=\"1459570\">example.</span> <span m=\"1460690\">So</span> <span m=\"1460960\"\
  >be</span> <span m=\"1462460\">the</span> <span m=\"1462640\">n-vertex</span> <span\
  \ m=\"1463530\">graph</span> <span m=\"1467600\">that</span> <span m=\"1467840\"\
  >is</span> <span m=\"1469250\">free</span> <span m=\"1469670\">of</span> <span m=\"\
  1470480\">cliques</span> <span m=\"1470810\">of</span> <span m=\"1470990\">r</span>\
  \ <span m=\"1471170\">plus</span> <span m=\"1471470\">1</span> <span m=\"1471650\"\
  >vertices</span> <span m=\"1473630\">and</span> <span m=\"1473990\">has</span> <span\
  \ m=\"1474390\">already</span> <span m=\"1474770\">the</span> <span m=\"1474860\"\
  >maximum</span> <span m=\"1475490\">number</span> <span m=\"1475790\">of</span>\
  \ <span m=\"1475970\">edges.</span></p><p><span m=\"1484410\">So</span> <span m=\"\
  1484590\">here's</span> <span m=\"1484870\">the</span> <span m=\"1484920\">property</span>\
  \ <span m=\"1485430\">I</span> <span m=\"1485520\">want</span> <span m=\"1485640\"\
  >to</span> <span m=\"1485740\">prove</span> <span m=\"1486120\">about</span> <span\
  \ m=\"1486360\">this</span> <span m=\"1486540\">graph.</span> <span m=\"1490090\"\
  >I</span> <span m=\"1490240\">claim</span> <span m=\"1490690\">that</span> <span\
  \ m=\"1492150\">if</span> <span m=\"1492330\">you</span> <span m=\"1492450\">look</span>\
  \ <span m=\"1492720\">at</span> <span m=\"1493290\">the</span> <span m=\"1493380\"\
  >complement</span> <span m=\"1494160\">of</span> <span m=\"1494280\">the</span>\
  \ <span m=\"1494370\">graph,</span> <span m=\"1495240\">of</span> <span m=\"1495360\"\
  >this</span> <span m=\"1495540\">extremal</span> <span m=\"1496050\">example,</span>\
  \ <span m=\"1497620\">it</span> <span m=\"1497710\">must</span> <span m=\"1497980\"\
  >be</span> <span m=\"1498180\">an</span> <span m=\"1498250\">equivalence</span>\
  \ <span m=\"1498880\">relation.</span> <span m=\"1500230\">So</span> <span m=\"\
  1500410\">more</span> <span m=\"1500530\">precisely,</span> <span m=\"1501750\"\
  >claim</span> <span m=\"1502060\">that</span> <span m=\"1502390\">if</span> <span\
  \ m=\"1504940\">xy</span> <span m=\"1505450\">is</span> <span m=\"1505660\">a</span>\
  \ <span m=\"1505740\">non-edge,</span> <span m=\"1507970\">and</span> <span m=\"\
  1508150\">yz</span> <span m=\"1509260\">is</span> <span m=\"1509410\">a</span> <span\
  \ m=\"1509470\">non-edge,</span> <span m=\"1512590\">then</span> <span m=\"1513410\"\
  >xz</span> <span m=\"1515680\">must</span> <span m=\"1516250\">also</span> <span\
  \ m=\"1516580\">be</span> <span m=\"1516820\">a</span> <span m=\"1517280\">non-edge.</span>\
  \ <span m=\"1519650\">So</span> <span m=\"1519780\">in</span> <span m=\"1519870\"\
  >other</span> <span m=\"1520050\">words,</span> <span m=\"1521310\">non-edges</span>\
  \ <span m=\"1524480\">form</span> <span m=\"1526260\">equivalence</span> <span m=\"\
  1526850\">relation.</span></p><p><span m=\"1535270\">And</span> <span m=\"1535400\"\
  >again,</span> <span m=\"1535610\">you</span> <span m=\"1535700\">should</span>\
  \ <span m=\"1535850\">always</span> <span m=\"1536180\">think</span> <span m=\"\
  1536390\">about</span> <span m=\"1536660\">the</span> <span m=\"1536810\">extremal</span>\
  \ <span m=\"1537320\">example.</span> <span m=\"1539390\">And</span> <span m=\"\
  1539800\">it</span> <span m=\"1539920\">is</span> <span m=\"1540040\">true</span>\
  \ <span m=\"1540280\">for</span> <span m=\"1540400\">the</span> <span m=\"1540490\"\
  >extremal</span> <span m=\"1540910\">example.</span> <span m=\"1541330\">Because</span>\
  \ <span m=\"1541690\">the</span> <span m=\"1542050\">complement</span> <span m=\"\
  1542750\">are</span> <span m=\"1543160\">a</span> <span m=\"1543190\">bunch</span>\
  \ <span m=\"1543460\">of</span> <span m=\"1543550\">cliques.</span> <span m=\"1544100\"\
  >So</span> <span m=\"1544210\">it</span> <span m=\"1544320\">is an</span> <span\
  \ m=\"1544510\">equivalence</span> <span m=\"1545020\">relation.</span></p><p><span\
  \ m=\"1551830\">So</span> <span m=\"1552040\">let's</span> <span m=\"1552250\">prove</span>\
  \ <span m=\"1552490\">this</span> <span m=\"1552670\">claim.</span> <span m=\"1553310\"\
  >So</span> <span m=\"1553990\">let's</span> <span m=\"1554200\">assume</span> <span\
  \ m=\"1554590\">that</span> <span m=\"1555010\">the</span> <span m=\"1555130\">conclusion</span>\
  \ <span m=\"1555700\">is</span> <span m=\"1555820\">not</span> <span m=\"1556090\"\
  >true.</span> <span m=\"1557240\">So</span> <span m=\"1558490\">suppose,</span>\
  \ <span m=\"1559460\">for</span> <span m=\"1559510\">the</span> <span m=\"1559570\"\
  >contrary,</span> <span m=\"1561520\">that</span> <span m=\"1562930\">we</span>\
  \ <span m=\"1563080\">have</span> <span m=\"1563560\">xy</span> <span m=\"1564850\"\
  >and</span> <span m=\"1565030\">yz</span> <span m=\"1565990\">being</span> <span\
  \ m=\"1566240\">non-edges,</span> <span m=\"1568060\">but</span> <span m=\"1570530\"\
  >xz</span> <span m=\"1571430\">is</span> <span m=\"1571600\">an</span> <span m=\"\
  1571720\">edge.</span></p><p><span m=\"1584480\">So</span> <span m=\"1584630\">let's</span>\
  \ <span m=\"1584870\">think</span> <span m=\"1585120\">about</span> <span m=\"1585890\"\
  >what</span> <span m=\"1586070\">happens</span> <span m=\"1586580\">to</span> <span\
  \ m=\"1587600\">the</span> <span m=\"1587690\">degrees</span> <span m=\"1588440\"\
  >of</span> <span m=\"1589650\">non-adjacent</span> <span m=\"1590440\">vertices.</span>\
  \ <span m=\"1592210\">So</span> <span m=\"1592360\">I</span> <span m=\"1592450\"\
  >claim</span> <span m=\"1592810\">that</span> <span m=\"1593140\">if</span> <span\
  \ m=\"1594910\">the</span> <span m=\"1595030\">degree</span> <span m=\"1595720\"\
  >of</span> <span m=\"1595870\">y</span> <span m=\"1596710\">were</span> <span m=\"\
  1596860\">smaller</span> <span m=\"1598270\">than</span> <span m=\"1598430\">the</span>\
  \ <span m=\"1598510\">degree</span> <span m=\"1598840\">of</span> <span m=\"1598960\"\
  >x,</span> <span m=\"1600750\">then</span> <span m=\"1600920\">I</span> <span m=\"\
  1600990\">can</span> <span m=\"1601170\">do</span> <span m=\"1601380\">something</span>\
  \ <span m=\"1601740\">to</span> <span m=\"1601860\">the</span> <span m=\"1601950\"\
  >graph</span> <span m=\"1602700\">that</span> <span m=\"1602880\">violates</span>\
  \ <span m=\"1603810\">the</span> <span m=\"1603930\">maximality</span> <span m=\"\
  1604740\">of</span> <span m=\"1604860\">the</span> <span m=\"1604950\">number</span>\
  \ <span m=\"1605310\">of</span> <span m=\"1605430\">edges.</span> <span m=\"1607150\"\
  >Namely,</span> <span m=\"1608380\">I</span> <span m=\"1608500\">can</span> <span\
  \ m=\"1608680\">replace</span> <span m=\"1612340\">y</span> <span m=\"1614460\"\
  >by</span> <span m=\"1615620\">a</span> <span m=\"1615790\">clone</span> <span m=\"\
  1618810\">of</span> <span m=\"1618990\">x.</span></p><p><span m=\"1621840\">So</span>\
  \ <span m=\"1622050\">I</span> <span m=\"1622860\">chop</span> <span m=\"1623160\"\
  >off</span> <span m=\"1623340\">y</span> <span m=\"1623580\">from</span> <span m=\"\
  1623790\">the</span> <span m=\"1623880\">graph.</span> <span m=\"1625230\">And</span>\
  \ <span m=\"1625730\">I</span> <span m=\"1625830\">look</span> <span m=\"1626040\"\
  >at</span> <span m=\"1626130\">x.</span> <span m=\"1626550\">And</span> <span m=\"\
  1626760\">I</span> <span m=\"1627180\">clone.</span> <span m=\"1627990\">So</span>\
  \ <span m=\"1628200\">cloning</span> <span m=\"1628650\">it</span> <span m=\"1628770\"\
  >means</span> <span m=\"1629880\">taking</span> <span m=\"1630390\">some</span>\
  \ <span m=\"1631140\">x</span> <span m=\"1631350\">prime.</span> <span m=\"1632100\"\
  >And</span> <span m=\"1632310\">I</span> <span m=\"1632370\">join</span> <span m=\"\
  1633420\">x</span> <span m=\"1633600\">prime</span> <span m=\"1634290\">to</span>\
  \ <span m=\"1634680\">all</span> <span m=\"1634890\">the</span> <span m=\"1635010\"\
  >same</span> <span m=\"1635430\">neighbors</span> <span m=\"1636000\">as</span>\
  \ <span m=\"1636180\">x.</span> <span m=\"1637500\">So</span> <span m=\"1637980\"\
  >clone</span> <span m=\"1638640\">x</span> <span m=\"1639030\">into</span> <span\
  \ m=\"1639330\">some</span> <span m=\"1639510\">other</span> <span m=\"1640140\"\
  >vertex,</span> <span m=\"1640680\">x</span> <span m=\"1640890\">prime.</span></p><p><span\
  \ m=\"1641790\">Now,</span> <span m=\"1641940\">when</span> <span m=\"1642090\"\
  >you</span> <span m=\"1642210\">do</span> <span m=\"1642360\">this,</span> <span\
  \ m=\"1643110\">I</span> <span m=\"1643200\">claim</span> <span m=\"1643560\">that</span>\
  \ <span m=\"1643770\">you</span> <span m=\"1644010\">also</span> <span m=\"1644430\"\
  >get</span> <span m=\"1644910\">a</span> <span m=\"1645600\">graph</span> <span\
  \ m=\"1647700\">that</span> <span m=\"1647880\">is</span> <span m=\"1648450\">free</span>\
  \ <span m=\"1648840\">of</span> <span m=\"1649020\">K</span> <span m=\"1649740\"\
  >sub</span> <span m=\"1650100\">r</span> <span m=\"1650340\">plus</span> <span m=\"\
  1650590\">1.</span> <span m=\"1654740\">So</span> <span m=\"1654820\">we</span>\
  \ <span m=\"1655210\">also</span> <span m=\"1655510\">obtain</span> <span m=\"1657780\"\
  >a</span> <span m=\"1658000\">K</span> <span m=\"1658450\">sub</span> <span m=\"\
  1658630\">r</span> <span m=\"1659020\">plus</span> <span m=\"1659290\">1-free</span>\
  \ <span m=\"1661180\">graph.</span> <span m=\"1665230\">So</span> <span m=\"1665440\"\
  >why</span> <span m=\"1665680\">is</span> <span m=\"1665800\">that?</span></p><p><span\
  \ m=\"1666325\">So</span> <span m=\"1666640\">if</span> <span m=\"1666730\">you</span>\
  \ <span m=\"1667200\">were</span> <span m=\"1667390\">to</span> <span m=\"1667510\"\
  >have</span> <span m=\"1668740\">an</span> <span m=\"1668860\">r</span> <span m=\"\
  1669040\">plus</span> <span m=\"1669370\">1</span> <span m=\"1669640\">clique,</span>\
  \ <span m=\"1670710\">well,</span> <span m=\"1670780\">it</span> <span m=\"1670940\"\
  >shouldn't</span> <span m=\"1671320\">have</span> <span m=\"1671740\">both</span>\
  \ <span m=\"1672190\">x</span> <span m=\"1672490\">and</span> <span m=\"1672670\"\
  >x</span> <span m=\"1673030\">clone.</span> <span m=\"1674510\">Because</span> <span\
  \ m=\"1674680\">there's</span> <span m=\"1674810\">no</span> <span m=\"1674990\"\
  >edge</span> <span m=\"1675170\">between</span> <span m=\"1675470\">them.</span>\
  \ <span m=\"1676410\">So</span> <span m=\"1676540\">it</span> <span m=\"1676610\"\
  >only</span> <span m=\"1676820\">has</span> <span m=\"1677210\">one</span> <span\
  \ m=\"1677510\">of</span> <span m=\"1678050\">x</span> <span m=\"1678320\">and</span>\
  \ <span m=\"1678440\">x</span> <span m=\"1678650\">clone.</span> <span m=\"1679730\"\
  >But</span> <span m=\"1679850\">then</span> <span m=\"1680120\">that</span> <span\
  \ m=\"1680360\">would</span> <span m=\"1680510\">have</span> <span m=\"1680600\"\
  >been</span> <span m=\"1680750\">a</span> <span m=\"1680810\">clique</span> <span\
  \ m=\"1681120\">in</span> <span m=\"1681230\">the</span> <span m=\"1681320\">original</span>\
  \ <span m=\"1681740\">graph.</span></p><p><span m=\"1687300\">However,</span> <span\
  \ m=\"1690450\">what</span> <span m=\"1690630\">about</span> <span m=\"1690810\"\
  >the</span> <span m=\"1690900\">number</span> <span m=\"1691290\">of</span> <span\
  \ m=\"1692040\">edges</span> <span m=\"1692460\">that</span> <span m=\"1692580\"\
  >we</span> <span m=\"1692760\">obtain</span> <span m=\"1694200\">after</span> <span\
  \ m=\"1694500\">this</span> <span m=\"1694650\">transformation?</span> <span m=\"\
  1696300\">If</span> <span m=\"1697770\">x</span> <span m=\"1698070\">had</span>\
  \ <span m=\"1698310\">more</span> <span m=\"1699300\">outgoing</span> <span m=\"\
  1699750\">edges,</span> <span m=\"1700110\">a</span> <span m=\"1700170\">higher</span>\
  \ <span m=\"1700470\">degree</span> <span m=\"1700800\">than</span> <span m=\"1700950\"\
  >y,</span> <span m=\"1701550\">then</span> <span m=\"1701760\">cloning</span> <span\
  \ m=\"1703290\">x</span> <span m=\"1703560\">to</span> <span m=\"1703710\">replace</span>\
  \ <span m=\"1704250\">y</span> <span m=\"1704790\">increases</span> <span m=\"1705510\"\
  >the</span> <span m=\"1705600\">number</span> <span m=\"1705960\">of</span> <span\
  \ m=\"1706110\">edges.</span> <span m=\"1711840\">We</span> <span m=\"1711960\"\
  >obtain</span> <span m=\"1712350\">a</span> <span m=\"1712410\">graph</span> <span\
  \ m=\"1712800\">that</span> <span m=\"1713010\">is</span> <span m=\"1713250\">also</span>\
  \ <span m=\"1714060\">K</span> <span m=\"1714360\">sub</span> <span m=\"1714510\"\
  >r</span> <span m=\"1714630\">plus</span> <span m=\"1714870\">1-free</span> <span\
  \ m=\"1715780\">and</span> <span m=\"1715920\">has</span> <span m=\"1716670\">more</span>\
  \ <span m=\"1718230\">edges</span> <span m=\"1720620\">than</span> <span m=\"1722045\"\
  >G,</span> <span m=\"1724900\">which</span> <span m=\"1725010\">is</span> <span\
  \ m=\"1725130\">not</span> <span m=\"1725340\">possible,</span> <span m=\"1725820\"\
  >because</span> <span m=\"1726090\">we</span> <span m=\"1726240\">assumed</span>\
  \ <span m=\"1726600\">that</span> <span m=\"1726760\">g</span> <span m=\"1727740\"\
  >started</span> <span m=\"1728160\">with</span> <span m=\"1728320\">the</span> <span\
  \ m=\"1728370\">maximum</span> <span m=\"1728880\">number</span> <span m=\"1729180\"\
  >of</span> <span m=\"1729510\">edges.</span></p><p><span m=\"1731163\">So</span>\
  \ <span m=\"1732520\">therefore,</span> <span m=\"1735920\">the</span> <span m=\"\
  1736040\">degree</span> <span m=\"1736460\">of</span> <span m=\"1736580\">y</span>\
  \ <span m=\"1736880\">is</span> <span m=\"1737090\">at</span> <span m=\"1737180\"\
  >most</span> <span m=\"1737750\">the</span> <span m=\"1737840\">degree</span> <span\
  \ m=\"1738240\">x,</span> <span m=\"1739970\">basically</span> <span m=\"1740600\"\
  >for</span> <span m=\"1741440\">every</span> <span m=\"1742930\">non-edge</span>\
  \ <span m=\"1745280\">xy.</span> <span m=\"1748780\">Likewise,</span> <span m=\"\
  1750580\">we</span> <span m=\"1750760\">also</span> <span m=\"1751240\">have</span>\
  \ <span m=\"1751540\">that</span> <span m=\"1751950\">there</span> <span m=\"1752080\"\
  >is</span> <span m=\"1752200\">no</span> <span m=\"1752470\">edge</span> <span m=\"\
  1752680\">between</span> <span m=\"1753070\">y</span> <span m=\"1753370\">and</span>\
  \ <span m=\"1753520\">z.</span> <span m=\"1757610\">So</span> <span m=\"1757790\"\
  >the</span> <span m=\"1757910\">degree</span> <span m=\"1758720\">of</span> <span\
  \ m=\"1759020\">y</span> <span m=\"1760010\">is--</span> <span m=\"1763730\">thus</span>\
  \ <span m=\"1763970\">the</span> <span m=\"1764150\">degree</span> <span m=\"1764450\"\
  >of</span> <span m=\"1764540\">y</span> <span m=\"1764720\">is</span> <span m=\"\
  1764860\">at</span> <span m=\"1765110\">least</span> <span m=\"1765230\">the</span>\
  \ <span m=\"1765320\">degree of</span> <span m=\"1765470\">x</span> <span m=\"1765710\"\
  >now.</span> <span m=\"1765920\">So</span> <span m=\"1766310\">degree</span> <span\
  \ m=\"1766460\">of</span> <span m=\"1766580\">y</span> <span m=\"1766900\">is</span>\
  \ <span m=\"1767000\">at</span> <span m=\"1767060\">least</span> <span m=\"1767720\"\
  >the</span> <span m=\"1768080\">degree</span> <span m=\"1769764\">of</span> <span\
  \ m=\"1770256\">z.</span> <span m=\"1773700\">Now,</span> <span m=\"1774200\">y</span>\
  \ <span m=\"1774950\">has</span> <span m=\"1776030\">a</span> <span m=\"1776090\"\
  >lot</span> <span m=\"1776390\">of</span> <span m=\"1777740\">outgoing</span> <span\
  \ m=\"1778190\">edges.</span> <span m=\"1778910\">So</span> <span m=\"1779210\"\
  >now</span> <span m=\"1779510\">let's</span> <span m=\"1780470\">replace</span>\
  \ <span m=\"1781400\">both</span> <span m=\"1781880\">x</span> <span m=\"1782150\"\
  >and</span> <span m=\"1782270\">z</span> <span m=\"1783050\">by</span> <span m=\"\
  1783260\">clones</span> <span m=\"1783770\">of</span> <span m=\"1783860\">y.</span></p><p><span\
  \ m=\"1796760\">As</span> <span m=\"1796920\">before,</span> <span m=\"1798240\"\
  >we</span> <span m=\"1798360\">obtain</span> <span m=\"1798720\">some</span> <span\
  \ m=\"1798930\">graph</span> <span m=\"1800485\">that</span> <span m=\"1800790\"\
  >we'll</span> <span m=\"1801000\">call</span> <span m=\"1801210\">G</span> <span\
  \ m=\"1801420\">prime.</span> <span m=\"1802650\">And</span> <span m=\"1802770\"\
  >G</span> <span m=\"1802950\">prime,</span> <span m=\"1803520\">same</span> <span\
  \ m=\"1803850\">reason</span> <span m=\"1804150\">as</span> <span m=\"1804270\"\
  >before,</span> <span m=\"1805050\">is</span> <span m=\"1805620\">K</span> <span\
  \ m=\"1806040\">sub</span> <span m=\"1806210\">r</span> <span m=\"1806460\">plus</span>\
  \ <span m=\"1806760\">1-free.</span> <span m=\"1807600\">If</span> <span m=\"1807720\"\
  >you</span> <span m=\"1807810\">had</span> <span m=\"1808080\">a</span> <span m=\"\
  1808140\">K</span> <span m=\"1808470\">sub r</span> <span m=\"1808710\">plus</span>\
  \ <span m=\"1808980\">1,</span> <span m=\"1809880\">then</span> <span m=\"1811140\"\
  >the</span> <span m=\"1811200\">same</span> <span m=\"1811710\">clique</span> <span\
  \ m=\"1812100\">should</span> <span m=\"1812310\">have</span> <span m=\"1812460\"\
  >shown</span> <span m=\"1812760\">up</span> <span m=\"1813300\">in</span> <span\
  \ m=\"1813570\">G.</span> <span m=\"1815190\">So</span> <span m=\"1815340\">G</span>\
  \ <span m=\"1815520\">prime</span> <span m=\"1816030\">does</span> <span m=\"1816210\"\
  >not</span> <span m=\"1816390\">have</span> <span m=\"1816570\">r</span> <span m=\"\
  1816720\">plus</span> <span m=\"1816960\">1</span> <span m=\"1817140\">cliques</span>\
  \ <span m=\"1817480\">either.</span> <span m=\"1818130\">But</span> <span m=\"1818280\"\
  >what</span> <span m=\"1818460\">about</span> <span m=\"1818670\">the</span> <span\
  \ m=\"1818760\">number</span> <span m=\"1819240\">of</span> <span m=\"1819660\"\
  >edges</span> <span m=\"1820200\">in</span> <span m=\"1820350\">G</span> <span m=\"\
  1820570\">prime?</span></p><p><span m=\"1825460\">So the</span> <span m=\"1825570\"\
  >number</span> <span m=\"1825930\">of</span> <span m=\"1826080\">edges</span> <span\
  \ m=\"1826440\">in</span> <span m=\"1826530\">G</span> <span m=\"1826710\">prime--</span>\
  \ <span m=\"1827490\">well,</span> <span m=\"1827640\">we</span> <span m=\"1827790\"\
  >started</span> <span m=\"1828330\">with</span> <span m=\"1828540\">G.</span> <span\
  \ m=\"1830810\">We</span> <span m=\"1830990\">deleted</span> <span m=\"1831920\"\
  >x</span> <span m=\"1832520\">and</span> <span m=\"1832700\">z.</span> <span m=\"\
  1834320\">So</span> <span m=\"1834470\">we</span> <span m=\"1834620\">deleted</span>\
  \ <span m=\"1841240\">this</span> <span m=\"1841420\">many</span> <span m=\"1841660\"\
  >edges.</span> <span m=\"1842170\">Here,</span> <span m=\"1842440\">we're</span>\
  \ <span m=\"1842700\">crucially</span> <span m=\"1843130\">using</span> <span m=\"\
  1843400\">the</span> <span m=\"1843490\">fact</span> <span m=\"1843730\">that</span>\
  \ <span m=\"1843820\">there</span> <span m=\"1844000\">is</span> <span m=\"1844210\"\
  >an</span> <span m=\"1844330\">edge</span> <span m=\"1844540\">between</span> <span\
  \ m=\"1845470\">x</span> <span m=\"1845740\">and</span> <span m=\"1845890\">z.</span></p><p><span\
  \ m=\"1847260\">But</span> <span m=\"1847380\">now</span> <span m=\"1847590\">we</span>\
  \ <span m=\"1847830\">also</span> <span m=\"1848250\">added</span> <span m=\"1848580\"\
  >back</span> <span m=\"1848850\">in</span> <span m=\"1849960\">a</span> <span m=\"\
  1850020\">bunch</span> <span m=\"1850380\">of</span> <span m=\"1850590\">edges</span>\
  \ <span m=\"1851160\">coming</span> <span m=\"1851460\">from</span> <span m=\"1851670\"\
  >the</span> <span m=\"1851760\">clone</span> <span m=\"1852250\">of</span> <span\
  \ m=\"1852390\">y.</span> <span m=\"1853320\">And</span> <span m=\"1853530\">they</span>\
  \ <span m=\"1853680\">are</span> <span m=\"1853860\">2</span> <span m=\"1854220\"\
  >times</span> <span m=\"1855370\">dy</span> <span m=\"1856170\">edges</span> <span\
  \ m=\"1856800\">added</span> <span m=\"1857280\">back</span> <span m=\"1857550\"\
  >in.</span> <span m=\"1859482\">Now,</span> <span m=\"1859930\">you see,</span>\
  \ <span m=\"1860110\">because</span> <span m=\"1860680\">y</span> <span m=\"1860980\"\
  >has</span> <span m=\"1861220\">degree</span> <span m=\"1861550\">at</span> <span\
  \ m=\"1861640\">least</span> <span m=\"1862000\">that</span> <span m=\"1862240\"\
  >of</span> <span m=\"1862360\">both</span> <span m=\"1862750\">x</span> <span m=\"\
  1863170\">and</span> <span m=\"1863380\">z,</span> <span m=\"1864130\">we</span>\
  \ <span m=\"1864280\">obtain</span> <span m=\"1864750\">that</span> <span m=\"1865090\"\
  >this</span> <span m=\"1865480\">number</span> <span m=\"1865810\">of</span> <span\
  \ m=\"1866020\">edges</span> <span m=\"1866680\">is</span> <span m=\"1866770\">strictly</span>\
  \ <span m=\"1867250\">bigger</span> <span m=\"1868090\">than</span> <span m=\"1868300\"\
  >that</span> <span m=\"1868510\">of</span> <span m=\"1868630\">G,</span> <span m=\"\
  1870820\">which</span> <span m=\"1870970\">contradicts</span> <span m=\"1873010\"\
  >the</span> <span m=\"1873130\">maximality</span> <span m=\"1876770\">of</span>\
  \ <span m=\"1877000\">G.</span></p><p><span m=\"1889080\">So</span> <span m=\"1889260\"\
  >at</span> <span m=\"1889320\">this</span> <span m=\"1889500\">point,</span> <span\
  \ m=\"1890010\">we</span> <span m=\"1890160\">know</span> <span m=\"1890490\">that</span>\
  \ <span m=\"1890760\">the</span> <span m=\"1890910\">complement</span> <span m=\"\
  1891570\">of</span> <span m=\"1891660\">G</span> <span m=\"1892410\">must</span>\
  \ <span m=\"1892740\">be</span> <span m=\"1893310\">an</span> <span m=\"1893430\"\
  >equivalence</span> <span m=\"1893970\">relation.</span> <span m=\"1895390\">So</span>\
  \ <span m=\"1895660\">the</span> <span m=\"1895750\">complement</span> <span m=\"\
  1896740\">is</span> <span m=\"1896890\">a</span> <span m=\"1896920\">bunch</span>\
  \ <span m=\"1897130\">of</span> <span m=\"1897220\">cliques.</span> <span m=\"1898910\"\
  >And</span> <span m=\"1899540\">that's</span> <span m=\"1899750\">a</span> <span\
  \ m=\"1899810\">lot</span> <span m=\"1900050\">of</span> <span m=\"1900230\">information.</span>\
  \ <span m=\"1900830\">So</span> <span m=\"1900950\">that's</span> <span m=\"1901160\"\
  >almost</span> <span m=\"1901430\">the</span> <span m=\"1901490\">best</span> <span\
  \ m=\"1901730\">thing</span> <span m=\"1901910\">we</span> <span m=\"1902030\">can</span>\
  \ <span m=\"1902150\">hope</span> <span m=\"1902330\">for</span> <span m=\"1902570\"\
  >is</span> <span m=\"1902600\">the</span> <span m=\"1902810\">structural</span>\
  \ <span m=\"1902990\">information.</span></p><p><span m=\"1903470\">We're</span>\
  \ <span m=\"1903590\">not</span> <span m=\"1904190\">quite</span> <span m=\"1904700\"\
  >done</span> <span m=\"1905120\">yet.</span> <span m=\"1906510\">And</span> <span\
  \ m=\"1906780\">why</span> <span m=\"1906930\">is</span> <span m=\"1907070\">that?</span>\
  \ <span m=\"1910860\">Well,</span> <span m=\"1911090\">we're</span> <span m=\"1911330\"\
  >almost</span> <span m=\"1911650\">there.</span> <span m=\"1913130\">But we're</span>\
  \ <span m=\"1913310\">not</span> <span m=\"1913460\">quite</span> <span m=\"1913740\"\
  >done</span> <span m=\"1913910\">yet.</span></p><p><span m=\"1917128\">AUDIENCE:</span>\
  \ <span m=\"1917374\">[INAUDIBLE]</span> <span m=\"1919100\">you can</span> <span\
  \ m=\"1919593\">figure out</span> <span m=\"1920086\">the sizes</span> <span m=\"\
  1921072\">[INAUDIBLE].</span></p><p><span m=\"1922560\">YUFEI ZHAO:</span> <span\
  \ m=\"1922670\">OK.</span> <span m=\"1922780\">So</span> <span m=\"1922950\">we</span>\
  \ <span m=\"1923100\">need</span> <span m=\"1923220\">to</span> <span m=\"1923310\"\
  >figure</span> <span m=\"1923610\">out</span> <span m=\"1923790\">the</span> <span\
  \ m=\"1923880\">sizes</span> <span m=\"1924780\">of</span> <span m=\"1925050\">the</span>\
  \ <span m=\"1925170\">individual</span> <span m=\"1925770\">parts.</span> <span\
  \ m=\"1928590\">So</span> <span m=\"1928740\">we</span> <span m=\"1928830\">need</span>\
  \ <span m=\"1928920\">to</span> <span m=\"1929010\">figure</span> <span m=\"1929280\"\
  >out</span> <span m=\"1929340\">the</span> <span m=\"1929430\">sizes</span> <span\
  \ m=\"1929910\">of</span> <span m=\"1930000\">individual</span> <span m=\"1930510\"\
  >parts.</span> <span m=\"1931390\">And</span> <span m=\"1931500\">also,</span> <span\
  \ m=\"1932130\">note</span> <span m=\"1932400\">that</span> <span m=\"1932760\"\
  >you</span> <span m=\"1932880\">cannot</span> <span m=\"1933180\">have</span> <span\
  \ m=\"1933360\">too</span> <span m=\"1933570\">many</span> <span m=\"1933810\">parts.</span></p><p><span\
  \ m=\"1935610\">So</span> <span m=\"1938010\">at</span> <span m=\"1938070\">this</span>\
  \ <span m=\"1938250\">point,</span> <span m=\"1939390\">after</span> <span m=\"\
  1939630\">the</span> <span m=\"1939750\">claim,</span> <span m=\"1940950\">we</span>\
  \ <span m=\"1941100\">know</span> <span m=\"1941400\">that</span> <span m=\"1942420\"\
  >G</span> <span m=\"1945900\">is</span> <span m=\"1946260\">a</span> <span m=\"\
  1946380\">complete</span> <span m=\"1946870\">multipartite</span> <span m=\"1947880\"\
  >graph.</span> <span m=\"1958810\">It</span> <span m=\"1958900\">has</span> <span\
  \ m=\"1959290\">at</span> <span m=\"1959440\">most</span> <span m=\"1960730\">r</span>\
  \ <span m=\"1960900\">parts.</span> <span m=\"1963130\">If it had</span> <span m=\"\
  1963450\">r</span> <span m=\"1963760\">plus</span> <span m=\"1964000\">1</span>\
  \ <span m=\"1964180\">parts,</span> <span m=\"1964480\">I</span> <span m=\"1964570\"\
  >would</span> <span m=\"1964720\">see</span> <span m=\"1965430\">a</span> <span\
  \ m=\"1965550\">clique in</span> <span m=\"1965870\">r</span> <span m=\"1966040\"\
  >plus</span> <span m=\"1966280\">1</span> <span m=\"1966460\">vertices.</span></p><p><span\
  \ m=\"1971080\">So</span> <span m=\"1971580\">then,</span> <span m=\"1971670\">finally,</span>\
  \ <span m=\"1972210\">I</span> <span m=\"1972330\">need</span> <span m=\"1972480\"\
  >to</span> <span m=\"1972600\">show--</span> <span m=\"1973665\">I mean,</span>\
  \ <span m=\"1974220\">the</span> <span m=\"1974310\">rest</span> <span m=\"1974580\"\
  >is</span> <span m=\"1974700\">fairly</span> <span m=\"1975030\">routine.</span>\
  \ <span m=\"1975390\">I</span> <span m=\"1975450\">need</span> <span m=\"1975630\"\
  >to</span> <span m=\"1975810\">show</span> <span m=\"1976230\">what</span> <span\
  \ m=\"1976980\">the</span> <span m=\"1977700\">part</span> <span m=\"1978000\">sizes</span>\
  \ <span m=\"1978420\">have</span> <span m=\"1978540\">to</span> <span m=\"1978600\"\
  >be</span> <span m=\"1978750\">to</span> <span m=\"1978840\">maximize</span> <span\
  \ m=\"1979560\">the</span> <span m=\"1979620\">number</span> <span m=\"1979980\"\
  >of</span> <span m=\"1980490\">edges.</span> <span m=\"1981180\">And</span> <span\
  \ m=\"1981330\">basically,</span> <span m=\"1982200\">if</span> <span m=\"1982350\"\
  >you</span> <span m=\"1982470\">had</span> <span m=\"1982740\">some</span> <span\
  \ m=\"1983070\">two</span> <span m=\"1983280\">parts--</span> <span m=\"1986660\"\
  >so</span> <span m=\"1987050\">consider</span> <span m=\"1987650\">exactly</span>\
  \ <span m=\"1988130\">r</span> <span m=\"1988260\">parts.</span> <span m=\"1988690\"\
  >They're</span> <span m=\"1988890\">all</span> <span m=\"1989240\">empty</span>\
  \ <span m=\"1989510\">parts.</span> <span m=\"1990090\">And</span> <span m=\"1990210\"\
  >some</span> <span m=\"1990410\">two</span> <span m=\"1990620\">parts</span> <span\
  \ m=\"1991250\">have</span> <span m=\"1992360\">the</span> <span m=\"1992450\">number</span>\
  \ <span m=\"1992780\">of</span> <span m=\"1992840\">vertices</span> <span m=\"1995120\"\
  >differing</span> <span m=\"1995660\">by</span> <span m=\"2000490\">more</span>\
  \ <span m=\"2000700\">than</span> <span m=\"2000880\">1.</span></p><p><span m=\"\
  2003390\">Then</span> <span m=\"2003630\">what</span> <span m=\"2003810\">I</span>\
  \ <span m=\"2003870\">can</span> <span m=\"2004050\">do</span> <span m=\"2004410\"\
  >is--</span> <span m=\"2007350\">so</span> <span m=\"2008000\">if</span> <span m=\"\
  2008120\">you</span> <span m=\"2008180\">had</span> <span m=\"2009380\">one</span>\
  \ <span m=\"2009710\">part</span> <span m=\"2010310\">much</span> <span m=\"2010580\"\
  >bigger</span> <span m=\"2010850\">than</span> <span m=\"2011000\">the</span> <span\
  \ m=\"2011090\">other</span> <span m=\"2011300\">part,</span> <span m=\"2012956\"\
  >you can</span> <span m=\"2013400\">imagine</span> <span m=\"2013820\">moving</span>\
  \ <span m=\"2014630\">one</span> <span m=\"2014840\">vertex</span> <span m=\"2015920\"\
  >from</span> <span m=\"2016100\">one</span> <span m=\"2016250\">part</span> <span\
  \ m=\"2016730\">to</span> <span m=\"2016880\">the</span> <span m=\"2017000\">other</span>\
  \ <span m=\"2017150\">part.</span> <span m=\"2018690\">And</span> <span m=\"2018960\"\
  >you should</span> <span m=\"2019200\">convince</span> <span m=\"2019530\">yourself</span>\
  \ <span m=\"2019950\">that</span> <span m=\"2020610\">this</span> <span m=\"2020790\"\
  >operation</span> <span m=\"2021360\">should</span> <span m=\"2021540\">strictly</span>\
  \ <span m=\"2022050\">increase</span> <span m=\"2023340\">the</span> <span m=\"\
  2023460\">number</span> <span m=\"2023760\">of</span> <span m=\"2023910\">edges.</span>\
  \ <span m=\"2030520\">And</span> <span m=\"2031140\">then</span> <span m=\"2032880\"\
  >moving</span> <span m=\"2037470\">vertices</span> <span m=\"2039530\">should</span>\
  \ <span m=\"2040020\">strictly</span> <span m=\"2040590\">increase</span> <span\
  \ m=\"2041700\">the</span> <span m=\"2041790\">number</span> <span m=\"2042090\"\
  >of</span> <span m=\"2042210\">edges</span> <span m=\"2042810\">of</span> <span\
  \ m=\"2042960\">G.</span></p><p><span m=\"2044960\">And</span> <span m=\"2045460\"\
  >putting</span> <span m=\"2045790\">this</span> <span m=\"2046000\">all</span> <span\
  \ m=\"2046100\">together,</span> <span m=\"2046540\">we</span> <span m=\"2046720\"\
  >see</span> <span m=\"2046930\">that</span> <span m=\"2047470\">the</span> <span\
  \ m=\"2047620\">extremal</span> <span m=\"2048130\">example</span> <span m=\"2049060\"\
  >necessarily</span> <span m=\"2049840\">has</span> <span m=\"2050170\">to</span>\
  \ <span m=\"2050290\">be</span> <span m=\"2051739\">the</span> <span m=\"2051820\"\
  >current</span> <span m=\"2052179\">graph,</span> <span m=\"2053370\">namely</span>\
  \ <span m=\"2054070\">a</span> <span m=\"2054159\">complete</span> <span m=\"2055230\"\
  >r-partite</span> <span m=\"2055900\">graph,</span> <span m=\"2058360\">where</span>\
  \ <span m=\"2059630\">all</span> <span m=\"2059770\">the</span> <span m=\"2059889\"\
  >parts</span> <span m=\"2060730\">have</span> <span m=\"2061780\">the</span> <span\
  \ m=\"2061870\">same</span> <span m=\"2062199\">size,</span> <span m=\"2062710\"\
  >up</span> <span m=\"2062860\">to</span> <span m=\"2063040\">almost</span> <span\
  \ m=\"2063340\">1</span> <span m=\"2063550\">difference.</span> <span m=\"2069126\"\
  >Great.</span> <span m=\"2070540\">Any</span> <span m=\"2070620\">questions?</span>\
  \ <span m=\"2073050\">Yep?</span></p><p><span m=\"2073530\">AUDIENCE:</span> <span\
  \ m=\"2073656\">Can</span> <span m=\"2073782\">the</span> <span m=\"2073909\">Zykov</span>\
  \ <span m=\"2074260\">symmetrization</span> <span m=\"2075150\">technique</span>\
  \ <span m=\"2075520\">be</span> <span m=\"2075690\">used</span> <span m=\"2076020\"\
  >for</span> <span m=\"2076800\">any</span> <span m=\"2077010\">other type of</span>\
  \ <span m=\"2077370\">problem?</span></p><p><span m=\"2081239\">YUFEI ZHAO:</span>\
  \ <span m=\"2081289\">So</span> <span m=\"2081340\">the</span> <span m=\"2081440\"\
  >question</span> <span m=\"2081560\">is,</span> <span m=\"2081650\">can</span> <span\
  \ m=\"2081830\">the</span> <span m=\"2081920\">Zykov</span> <span m=\"2082380\"\
  >symmetrization</span> <span m=\"2082960\">technique</span> <span m=\"2083310\"\
  >be</span> <span m=\"2083510\">used</span> <span m=\"2083810\">for</span> <span\
  \ m=\"2083960\">any</span> <span m=\"2084199\">other</span> <span m=\"2084409\"\
  >types</span> <span m=\"2084770\">of</span> <span m=\"2084830\">problem?</span>\
  \ <span m=\"2086980\">I</span> <span m=\"2087070\">do</span> <span m=\"2087190\"\
  >have</span> <span m=\"2087280\">something</span> <span m=\"2087550\">else</span>\
  \ <span m=\"2087730\">in</span> <span m=\"2087790\">mind.</span> <span m=\"2088090\"\
  >But</span> <span m=\"2088570\">I</span> <span m=\"2088659\">don't</span> <span\
  \ m=\"2088780\">want</span> <span m=\"2088900\">to</span> <span m=\"2088989\">discuss\
  \ it</span> <span m=\"2089360\">now.</span> <span m=\"2092719\">Any</span> <span\
  \ m=\"2092909\">more</span> <span m=\"2093060\">questions?</span></p><p><span m=\"\
  2098082\">Great.</span> <span m=\"2099078\">And</span> <span m=\"2099580\">you</span>\
  \ <span m=\"2099710\">see</span> <span m=\"2099880\">that</span> <span m=\"2100000\"\
  >in</span> <span m=\"2100120\">both</span> <span m=\"2100390\">proofs,</span> <span\
  \ m=\"2102220\">if</span> <span m=\"2102340\">you</span> <span m=\"2102430\">look</span>\
  \ <span m=\"2102580\">at</span> <span m=\"2102700\">this</span> <span m=\"2102910\"\
  >proof</span> <span m=\"2103180\">as</span> <span m=\"2103300\">well,</span> <span\
  \ m=\"2103750\">you</span> <span m=\"2103810\">see</span> <span m=\"2104050\">that</span>\
  \ <span m=\"2104270\">the</span> <span m=\"2104390\">Tur\xE1n</span> <span m=\"\
  2104740\">graph,</span> <span m=\"2105100\">it's</span> <span m=\"2105290\">the</span>\
  \ <span m=\"2105370\">unique</span> <span m=\"2106150\">extremizer.</span> <span\
  \ m=\"2109370\">I</span> <span m=\"2109430\">want</span> <span m=\"2109610\">to</span>\
  \ <span m=\"2109670\">give</span> <span m=\"2109880\">you</span> <span m=\"2110660\"\
  >a</span> <span m=\"2110720\">third</span> <span m=\"2111020\">proof</span> <span\
  \ m=\"2111680\">that</span> <span m=\"2111830\">has</span> <span m=\"2112250\">a</span>\
  \ <span m=\"2112580\">somewhat</span> <span m=\"2112940\">different</span> <span\
  \ m=\"2113210\">flavor.</span> <span m=\"2113730\">So</span> <span m=\"2113800\"\
  >these</span> <span m=\"2113990\">two</span> <span m=\"2114110\">proofs,</span>\
  \ <span m=\"2114380\">they're</span> <span m=\"2114650\">both</span> <span m=\"\
  2115700\">somewhat</span> <span m=\"2116000\">combinatorial</span> <span m=\"2116840\"\
  >in</span> <span m=\"2116990\">flavor.</span> <span m=\"2117265\">So</span> <span\
  \ m=\"2117540\">I'm</span> <span m=\"2118040\">doing</span> <span m=\"2118280\"\
  >some</span> <span m=\"2118460\">arguments</span> <span m=\"2119580\">either</span>\
  \ <span m=\"2120020\">looking</span> <span m=\"2120380\">at,</span> <span m=\"2122340\"\
  >in</span> <span m=\"2122720\">this</span> <span m=\"2122900\">case,</span> <span\
  \ m=\"2123380\">a</span> <span m=\"2123860\">clique</span> <span m=\"2124220\">and</span>\
  \ <span m=\"2124370\">arguing</span> <span m=\"2124730\">what</span> <span m=\"\
  2124850\">happens</span> <span m=\"2125240\">outside</span> <span m=\"2125600\"\
  >of</span> <span m=\"2125720\">it.</span> <span m=\"2126050\">And</span> <span m=\"\
  2126230\">over</span> <span m=\"2126410\">there,</span> <span m=\"2126850\">again,</span>\
  \ <span m=\"2127070\">I'm looking</span> <span m=\"2127310\">at</span> <span m=\"\
  2127430\">maximal</span> <span m=\"2127880\">example.</span></p><p><span m=\"2129230\"\
  >The</span> <span m=\"2129320\">third</span> <span m=\"2129590\">proof</span> <span\
  \ m=\"2129830\">I</span> <span m=\"2129920\">want</span> <span m=\"2130070\">to</span>\
  \ <span m=\"2130130\">show</span> <span m=\"2130730\">is</span> <span m=\"2130910\"\
  >more</span> <span m=\"2131090\">of</span> <span m=\"2131180\">a</span> <span m=\"\
  2131240\">probabilistic</span> <span m=\"2131960\">proof.</span> <span m=\"2132770\"\
  >So</span> <span m=\"2132920\">this</span> <span m=\"2133100\">highlights</span>\
  \ <span m=\"2133910\">an</span> <span m=\"2134000\">important</span> <span m=\"\
  2134690\">method</span> <span m=\"2135020\">in</span> <span m=\"2135110\">combinatorics,</span>\
  \ <span m=\"2135485\">and</span> <span m=\"2135860\">almost a</span> <span m=\"\
  2136310\">probabilistic</span> <span m=\"2137000\">method,</span> <span m=\"2139280\"\
  >where</span> <span m=\"2140030\">we</span> <span m=\"2140180\">start</span> <span\
  \ m=\"2140480\">with</span> <span m=\"2140660\">a</span> <span m=\"2140690\">problem</span>\
  \ <span m=\"2141050\">that</span> <span m=\"2141890\">comes</span> <span m=\"2142280\"\
  >with</span> <span m=\"2142430\">no</span> <span m=\"2142730\">randomness.</span>\
  \ <span m=\"2143550\">But</span> <span m=\"2143600\">we</span> <span m=\"2143780\"\
  >introduce</span> <span m=\"2144290\">some</span> <span m=\"2144560\">randomness</span>\
  \ <span m=\"2145640\">to</span> <span m=\"2146240\">make</span> <span m=\"2146510\"\
  >the</span> <span m=\"2146570\">problem</span> <span m=\"2147590\">amenable.</span>\
  \ <span m=\"2148920\">It's</span> <span m=\"2149290\">a</span> <span m=\"2149360\"\
  >very</span> <span m=\"2149540\">pretty</span> <span m=\"2149870\">idea.</span></p><p><span\
  \ m=\"2162480\">So</span> <span m=\"2162660\">we</span> <span m=\"2162840\">start,</span>\
  \ <span m=\"2163140\">again,</span> <span m=\"2164040\">with</span> <span m=\"2164550\"\
  >G</span> <span m=\"2166230\">being</span> <span m=\"2166770\">a</span> <span m=\"\
  2167190\">n-uniform,</span> <span m=\"2168640\">so</span> <span m=\"2168995\">n-vertex,</span>\
  \ <span m=\"2170670\">K</span> <span m=\"2171030\">sub</span> <span m=\"2171240\"\
  >r</span> <span m=\"2171600\">plus</span> <span m=\"2171870\">1-free</span> <span\
  \ m=\"2173400\">graph</span> <span m=\"2176760\">on</span> <span m=\"2177150\">m</span>\
  \ <span m=\"2177410\">edges.</span> <span m=\"2180532\">And</span> <span m=\"2180990\"\
  >what</span> <span m=\"2181170\">I</span> <span m=\"2181230\">want</span> <span\
  \ m=\"2181410\">to</span> <span m=\"2181470\">do</span> <span m=\"2182100\">is</span>\
  \ <span m=\"2182310\">to</span> <span m=\"2182610\">randomly</span> <span m=\"2183390\"\
  >sort</span> <span m=\"2183960\">the</span> <span m=\"2184080\">vertex</span> <span\
  \ m=\"2184530\">set.</span> <span m=\"2185700\">Consider</span> <span m=\"2188700\"\
  >a</span> <span m=\"2188790\">random</span> <span m=\"2189360\">order</span> <span\
  \ m=\"2195190\">of</span> <span m=\"2196010\">the</span> <span m=\"2196130\">vertices.</span>\
  \ <span m=\"2202620\">So</span> <span m=\"2202690\">I</span> <span m=\"2202780\"\
  >put</span> <span m=\"2203350\">all</span> <span m=\"2203470\">the</span> <span\
  \ m=\"2203560\">vertices</span> <span m=\"2204010\">on</span> <span m=\"2204100\"\
  >the</span> <span m=\"2204160\">line,</span> <span m=\"2205030\">but</span> <span\
  \ m=\"2205150\">the</span> <span m=\"2205210\">vertices</span> <span m=\"2205660\"\
  >are</span> <span m=\"2205720\">chosen</span> <span m=\"2206110\">at</span> <span\
  \ m=\"2206200\">random</span> <span m=\"2206590\">order.</span> <span m=\"2207610\"\
  >And</span> <span m=\"2207880\">you</span> <span m=\"2208030\">see</span> <span\
  \ m=\"2208270\">some</span> <span m=\"2208510\">of</span> <span m=\"2208570\">the</span>\
  \ <span m=\"2208720\">edges</span> <span m=\"2212602\">like</span> <span m=\"2213088\"\
  >that.</span></p><p><span m=\"2220400\">Let</span> <span m=\"2220520\">me</span>\
  \ <span m=\"2221180\">show</span> <span m=\"2221450\">you</span> <span m=\"2221540\"\
  >how</span> <span m=\"2221660\">to</span> <span m=\"2221750\">find</span> <span\
  \ m=\"2221990\">a</span> <span m=\"2222050\">clique.</span> <span m=\"2223070\"\
  >And</span> <span m=\"2223160\">essentially,</span> <span m=\"2223610\">we</span>\
  \ <span m=\"2223760\">do</span> <span m=\"2223970\">it</span> <span m=\"2225370\"\
  >in</span> <span m=\"2225600\">a</span> <span m=\"2226220\">not-so-smart</span>\
  \ <span m=\"2227150\">way.</span> <span m=\"2227810\">Namely,</span> <span m=\"\
  2228530\">I</span> <span m=\"2229040\">basically</span> <span m=\"2229520\">pick</span>\
  \ <span m=\"2230330\">all</span> <span m=\"2230510\">the</span> <span m=\"2230600\"\
  >vertices</span> <span m=\"2231620\">in</span> <span m=\"2231860\">some</span> <span\
  \ m=\"2232580\">greedy-like</span> <span m=\"2233150\">manner,</span> <span m=\"\
  2233720\">where</span> <span m=\"2233870\">I</span> <span m=\"2233990\">include</span>\
  \ <span m=\"2234360\">the</span> <span m=\"2234410\">vertex</span> <span m=\"2234980\"\
  >in</span> <span m=\"2235130\">my</span> <span m=\"2235310\">set</span> <span m=\"\
  2236220\">if</span> <span m=\"2236330\">it</span> <span m=\"2236540\">is</span>\
  \ <span m=\"2236660\">adjacent</span> <span m=\"2237950\">to</span> <span m=\"2239000\"\
  >all</span> <span m=\"2239720\">earlier</span> <span m=\"2242060\">vertices.</span>\
  \ <span m=\"2243720\">So</span> <span m=\"2245971\">if</span> <span m=\"2246440\"\
  >all</span> <span m=\"2246650\">of</span> <span m=\"2246770\">its</span> <span m=\"\
  2247160\">neighbors--</span> <span m=\"2248730\">so</span> <span m=\"2248990\">I</span>\
  \ <span m=\"2249110\">include</span> <span m=\"2249320\">V,</span> <span m=\"2249770\"\
  >if</span> <span m=\"2250190\">V</span> <span m=\"2250520\">is</span> <span m=\"\
  2250790\">the</span> <span m=\"2251930\">earliest</span> <span m=\"2255090\">vertex</span>\
  \ <span m=\"2256680\">among</span> <span m=\"2257010\">its</span> <span m=\"2257220\"\
  >neighbors.</span> <span m=\"2265800\">So</span> <span m=\"2265980\">earliest</span>\
  \ <span m=\"2266430\">means</span> <span m=\"2266760\">the</span> <span m=\"2266900\"\
  >leftmost,</span> <span m=\"2267700\">so if</span> <span m=\"2268060\">I</span>\
  \ <span m=\"2268530\">go</span> <span m=\"2268710\">from</span> <span m=\"2268890\"\
  >left</span> <span m=\"2269100\">to</span> <span m=\"2269190\">right.</span></p><p><span\
  \ m=\"2269590\">So</span> <span m=\"2269700\">in</span> <span m=\"2270660\">this</span>\
  \ <span m=\"2270900\">case</span> <span m=\"2271590\">up</span> <span m=\"2271720\"\
  >here,</span> <span m=\"2273220\">so</span> <span m=\"2273360\">I</span> <span m=\"\
  2273630\">look</span> <span m=\"2273840\">at</span> <span m=\"2273900\">the</span>\
  \ <span m=\"2273960\">first</span> <span m=\"2274260\">vertex.</span> <span m=\"\
  2274680\">Well,</span> <span m=\"2274790\">the</span> <span m=\"2274860\">first</span>\
  \ <span m=\"2275100\">vertex</span> <span m=\"2275480\">should</span> <span m=\"\
  2276060\">always</span> <span m=\"2276360\">be in</span> <span m=\"2276640\">your</span>\
  \ <span m=\"2276910\">set.</span> <span m=\"2278335\">So</span> <span m=\"2278810\"\
  >this</span> <span m=\"2278990\">vertex</span> <span m=\"2280070\">has</span> <span\
  \ m=\"2280220\">one</span> <span m=\"2280430\">neighbor,</span> <span m=\"2280760\"\
  >just</span> <span m=\"2280970\">to</span> <span m=\"2281090\">the</span> <span\
  \ m=\"2281180\">right.</span> <span m=\"2281440\">So</span> <span m=\"2282800\"\
  >that's</span> <span m=\"2282990\">OK.</span> <span m=\"2284600\">And</span> <span\
  \ m=\"2288038\">hold on.</span> <span m=\"2289350\">It's--</span> <span m=\"2291260\"\
  >no.</span> <span m=\"2291930\">Sorry.</span> <span m=\"2292640\">That's</span>\
  \ <span m=\"2292880\">not</span> <span m=\"2293120\">what</span> <span m=\"2293330\"\
  >I</span> <span m=\"2295710\">want</span> <span m=\"2295920\">to</span> <span m=\"\
  2296010\">do.</span> <span m=\"2299930\">Sorry.</span></p><p><span m=\"2300390\"\
  >So</span> <span m=\"2300630\">I</span> <span m=\"2300730\">actually</span> <span\
  \ m=\"2301240\">do</span> <span m=\"2301410\">mean</span> <span m=\"2301560\">what</span>\
  \ <span m=\"2301710\">I</span> <span m=\"2301830\">was</span> <span m=\"2302810\"\
  >going</span> <span m=\"2302890\">to</span> <span m=\"2303000\">write</span> <span\
  \ m=\"2303140\">down</span> <span m=\"2303300\">initially.</span> <span m=\"2305320\"\
  >So</span> <span m=\"2305430\">if</span> <span m=\"2305720\">V</span> <span m=\"\
  2306120\">is</span> <span m=\"2306930\">adjacent</span> <span m=\"2308310\">to</span>\
  \ <span m=\"2313230\">all</span> <span m=\"2313530\">the</span> <span m=\"2314220\"\
  >earlier</span> <span m=\"2318350\">vertices</span> <span m=\"2322210\">in</span>\
  \ <span m=\"2322350\">this</span> <span m=\"2322440\">order--</span> <span m=\"\
  2334450\">so</span> <span m=\"2335010\">for</span> <span m=\"2335100\">example,</span>\
  \ <span m=\"2336780\">this</span> <span m=\"2336960\">vertex,</span> <span m=\"\
  2338710\">it's</span> <span m=\"2338840\">OK.</span> <span m=\"2340090\">And</span>\
  \ <span m=\"2340660\">I'm</span> <span m=\"2340810\">also</span> <span m=\"2341050\"\
  >going</span> <span m=\"2341230\">to</span> <span m=\"2341320\">include</span> <span\
  \ m=\"2342460\">this</span> <span m=\"2342640\">vertex</span> <span m=\"2343090\"\
  >here,</span> <span m=\"2344230\">because</span> <span m=\"2347620\">both</span>\
  \ <span m=\"2347890\">of</span> <span m=\"2348010\">its</span> <span m=\"2348370\"\
  >earlier</span> <span m=\"2348550\">vertices</span> <span m=\"2349740\">are</span>\
  \ <span m=\"2350110\">in--</span> <span m=\"2352150\">both</span> <span m=\"2352360\"\
  >the</span> <span m=\"2352450\">earlier</span> <span m=\"2352750\">vertices</span>\
  \ <span m=\"2353230\">are</span> <span m=\"2354010\">adjacent</span> <span m=\"\
  2354430\">to</span> <span m=\"2354760\">the</span> <span m=\"2354850\">third</span>\
  \ <span m=\"2355090\">vertex.</span> <span m=\"2356350\">And</span> <span m=\"2356740\"\
  >I</span> <span m=\"2356890\">think</span> <span m=\"2357460\">that's</span> <span\
  \ m=\"2357850\">it.</span></p><p><span m=\"2360882\">Now,</span> <span m=\"2361360\"\
  >this</span> <span m=\"2361540\">set</span> <span m=\"2362260\">x,</span> <span\
  \ m=\"2363700\">I</span> <span m=\"2363890\">claim</span> <span m=\"2364340\">two</span>\
  \ <span m=\"2364520\">things.</span> <span m=\"2365160\">One,</span> <span m=\"\
  2365330\">that</span> <span m=\"2365570\">x</span> <span m=\"2366200\">has</span>\
  \ <span m=\"2366530\">to</span> <span m=\"2366620\">be</span> <span m=\"2367490\"\
  >a</span> <span m=\"2367550\">clique.</span> <span m=\"2369490\">So</span> <span\
  \ m=\"2369900\">claim</span> <span m=\"2372188\">that</span> <span m=\"2372670\"\
  >x</span> <span m=\"2373300\">has</span> <span m=\"2373450\">to</span> <span m=\"\
  2373540\">be</span> <span m=\"2373660\">a</span> <span m=\"2373720\">clique.</span>\
  \ <span m=\"2377110\">Because</span> <span m=\"2377950\">every</span> <span m=\"\
  2378160\">vertex in the</span> <span m=\"2378640\">x</span> <span m=\"2379090\"\
  >is</span> <span m=\"2379240\">adjacent</span> <span m=\"2380050\">to</span> <span\
  \ m=\"2381050\">all</span> <span m=\"2381200\">of the</span> <span m=\"2381690\"\
  >[INAUDIBLE]</span> <span m=\"2381970\">vertices</span> <span m=\"2382420\">in</span>\
  \ <span m=\"2382510\">particular.</span> <span m=\"2383540\">All</span> <span m=\"\
  2383620\">the</span> <span m=\"2384190\">vertices</span> <span m=\"2384910\">in</span>\
  \ <span m=\"2385060\">x</span> <span m=\"2385390\">are</span> <span m=\"2385960\"\
  >joined</span> <span m=\"2386230\">to</span> <span m=\"2386350\">each</span> <span\
  \ m=\"2386530\">other.</span></p><p><span m=\"2388480\">On</span> <span m=\"2388530\"\
  >the</span> <span m=\"2388620\">other</span> <span m=\"2388800\">hand,</span> <span\
  \ m=\"2390730\">how</span> <span m=\"2390930\">big</span> <span m=\"2391530\">is</span>\
  \ <span m=\"2391710\">x,</span> <span m=\"2392500\">at</span> <span m=\"2392610\"\
  >least</span> <span m=\"2392970\">in</span> <span m=\"2393150\">expectation?</span>\
  \ <span m=\"2394930\">So</span> <span m=\"2394980\">for</span> <span m=\"2398430\"\
  >every</span> <span m=\"2400020\">vertex,</span> <span m=\"2402090\">I</span> <span\
  \ m=\"2402180\">want</span> <span m=\"2402360\">to</span> <span m=\"2402450\">understand</span>\
  \ <span m=\"2403530\">the</span> <span m=\"2403650\">probability</span> <span m=\"\
  2405202\">that</span> <span m=\"2408430\">this</span> <span m=\"2408610\">v</span>\
  \ <span m=\"2408910\">is</span> <span m=\"2409090\">included</span> <span m=\"2409510\"\
  >in</span> <span m=\"2409660\">x.</span> <span m=\"2410630\">So</span> <span m=\"\
  2410770\">v</span> <span m=\"2411040\">has</span> <span m=\"2412030\">a</span> <span\
  \ m=\"2412090\">bunch</span> <span m=\"2412510\">of</span> <span m=\"2413160\">non-neighbors.</span>\
  \ <span m=\"2414790\">And</span> <span m=\"2415030\">the</span> <span m=\"2416240\"\
  >property</span> <span m=\"2416720\">of</span> <span m=\"2417050\">v</span> <span\
  \ m=\"2417440\">being</span> <span m=\"2417680\">included</span> <span m=\"2418190\"\
  >in</span> <span m=\"2418370\">x</span> <span m=\"2419880\">is</span> <span m=\"\
  2420040\">that</span> <span m=\"2420390\">all</span> <span m=\"2420630\">of</span>\
  \ <span m=\"2420750\">its</span> <span m=\"2420900\">non-neighbors</span> <span\
  \ m=\"2421860\">appear</span> <span m=\"2422940\">after</span> <span m=\"2423330\"\
  >v.</span></p><p><span m=\"2424660\">So</span> <span m=\"2424850\">the</span> <span\
  \ m=\"2424940\">probability</span> <span m=\"2427340\">that</span> <span m=\"2427550\"\
  >v,</span> <span m=\"2428150\">little</span> <span m=\"2428390\">v,</span> <span\
  \ m=\"2428950\">is</span> <span m=\"2429140\">in</span> <span m=\"2429260\">the</span>\
  \ <span m=\"2429380\">set</span> <span m=\"2429680\">x</span> <span m=\"2431350\"\
  >is</span> <span m=\"2431560\">equal</span> <span m=\"2432760\">to</span> <span\
  \ m=\"2432970\">the</span> <span m=\"2433060\">probability</span> <span m=\"2433750\"\
  >that</span> <span m=\"2435040\">v</span> <span m=\"2436750\">appears</span> <span\
  \ m=\"2437740\">before</span> <span m=\"2440370\">all</span> <span m=\"2440650\"\
  >its</span> <span m=\"2440950\">non-neighbors.</span> <span m=\"2452300\">All</span>\
  \ <span m=\"2452780\">v</span> <span m=\"2453080\">and</span> <span m=\"2453270\"\
  >its</span> <span m=\"2453530\">non-neighbors,</span> <span m=\"2454260\">they're</span>\
  \ <span m=\"2454460\">sorted</span> <span m=\"2454850\">uniformly.</span> <span\
  \ m=\"2455720\">So</span> <span m=\"2458060\">the</span> <span m=\"2458270\">probability</span>\
  \ <span m=\"2458840\">that</span> <span m=\"2458960\">this</span> <span m=\"2459290\"\
  >occurs</span> <span m=\"2459770\">is</span> <span m=\"2459920\">exactly</span>\
  \ <span m=\"2460910\">1</span> <span m=\"2461660\">over</span> <span m=\"2464030\"\
  >1</span> <span m=\"2464300\">plus</span> <span m=\"2464630\">the</span> <span m=\"\
  2464720\">number</span> <span m=\"2465020\">of</span> <span m=\"2465110\">non-neighbors,</span>\
  \ <span m=\"2466190\">which</span> <span m=\"2466550\">is</span> <span m=\"2466940\"\
  >n</span> <span m=\"2467240\">minus</span> <span m=\"2467720\">the</span> <span\
  \ m=\"2467810\">degree</span> <span m=\"2468170\">of.</span></p><p><span m=\"2486340\"\
  >Well,</span> <span m=\"2486460\">we</span> <span m=\"2486640\">know</span> <span\
  \ m=\"2486970\">that</span> <span m=\"2487750\">this</span> <span m=\"2487960\"\
  >graph</span> <span m=\"2488290\">G</span> <span m=\"2488590\">has</span> <span\
  \ m=\"2488980\">no</span> <span m=\"2489220\">cliques</span> <span m=\"2489790\"\
  >of</span> <span m=\"2489970\">size</span> <span m=\"2490600\">r</span> <span m=\"\
  2490720\">plus</span> <span m=\"2491140\">1.</span> <span m=\"2491950\">So</span>\
  \ <span m=\"2493870\">if</span> <span m=\"2494110\">we</span> <span m=\"2494350\"\
  >consider</span> <span m=\"2494980\">the</span> <span m=\"2495220\">expected</span>\
  \ <span m=\"2495880\">number</span> <span m=\"2496330\">of</span> <span m=\"2499000\"\
  >the</span> <span m=\"2499130\">size</span> <span m=\"2499610\">of</span> <span\
  \ m=\"2499820\">x,</span> <span m=\"2500720\">on</span> <span m=\"2500810\">one</span>\
  \ <span m=\"2501050\">hand,</span> <span m=\"2501650\">it</span> <span m=\"2501800\"\
  >is</span> <span m=\"2501950\">at</span> <span m=\"2502100\">most</span> <span m=\"\
  2502610\">r.</span> <span m=\"2503600\">Because</span> <span m=\"2504700\">G</span>\
  \ <span m=\"2505790\">K</span> <span m=\"2506120\">sub</span> <span m=\"2506370\"\
  >r</span> <span m=\"2506510\">plus</span> <span m=\"2506780\">1-free.</span> <span\
  \ m=\"2508610\">On</span> <span m=\"2508760\">the</span> <span m=\"2508850\">other</span>\
  \ <span m=\"2509030\">hand,</span> <span m=\"2510590\">by</span> <span m=\"2510680\"\
  >linearity</span> <span m=\"2511280\">of</span> <span m=\"2511400\">expectations,</span>\
  \ <span m=\"2512810\">each</span> <span m=\"2513080\">vertex</span> <span m=\"2513600\"\
  >is</span> <span m=\"2513710\">included</span> <span m=\"2514130\">with</span> <span\
  \ m=\"2514310\">some</span> <span m=\"2514520\">probability.</span> <span m=\"2515330\"\
  >So</span> <span m=\"2515480\">the</span> <span m=\"2515570\">size</span> <span\
  \ m=\"2516170\">of</span> <span m=\"2516290\">x</span> <span m=\"2516590\">in</span>\
  \ <span m=\"2516750\">expectation</span> <span m=\"2517910\">is</span> <span m=\"\
  2518090\">just</span> <span m=\"2518340\">a</span> <span m=\"2518630\">sum</span>\
  \ <span m=\"2519380\">of</span> <span m=\"2519950\">all</span> <span m=\"2520110\"\
  >of</span> <span m=\"2520190\">these</span> <span m=\"2520430\">individual</span>\
  \ <span m=\"2521330\">inclusion</span> <span m=\"2521870\">probabilities,</span>\
  \ <span m=\"2525170\">which</span> <span m=\"2525650\">individually</span> <span\
  \ m=\"2526310\">we've</span> <span m=\"2526550\">computed</span> <span m=\"2527130\"\
  >above</span> <span m=\"2535973\">like</span> <span m=\"2536472\">that.</span></p><p><span\
  \ m=\"2538480\">Now,</span> <span m=\"2538870\">by</span> <span m=\"2539500\">convexity,</span>\
  \ <span m=\"2541060\">I</span> <span m=\"2541180\">can</span> <span m=\"2541330\"\
  >conclude</span> <span m=\"2543190\">that</span> <span m=\"2543640\">this</span>\
  \ <span m=\"2543850\">quantity,</span> <span m=\"2544300\">this</span> <span m=\"\
  2544450\">sum</span> <span m=\"2544780\">here,</span> <span m=\"2545470\">is</span>\
  \ <span m=\"2547060\">at</span> <span m=\"2547240\">least</span> <span m=\"2547810\"\
  >the</span> <span m=\"2547930\">quantity</span> <span m=\"2548410\">that</span>\
  \ <span m=\"2548980\">would</span> <span m=\"2549130\">have</span> <span m=\"2549220\"\
  >been</span> <span m=\"2549400\">obtained</span> <span m=\"2550210\">if</span> <span\
  \ m=\"2550540\">all</span> <span m=\"2550750\">the</span> <span m=\"2550870\">decrease</span>\
  \ <span m=\"2551350\">were</span> <span m=\"2551620\">equal</span> <span m=\"2551950\"\
  >to</span> <span m=\"2552070\">each</span> <span m=\"2552310\">other.</span> <span\
  \ m=\"2557540\">And</span> <span m=\"2557640\">if</span> <span m=\"2557730\">you</span>\
  \ <span m=\"2557880\">rearrange</span> <span m=\"2558480\">this</span> <span m=\"\
  2558690\">equation,</span> <span m=\"2559410\">this</span> <span m=\"2559590\">inequality,</span>\
  \ <span m=\"2560700\">we</span> <span m=\"2560910\">obtain</span> <span m=\"2561790\"\
  >that</span> <span m=\"2561990\">an</span> <span m=\"2562403\">m</span> <span m=\"\
  2563230\">is</span> <span m=\"2563600\">at</span> <span m=\"2563730\">most</span>\
  \ <span m=\"2565080\">1</span> <span m=\"2565440\">minus</span> <span m=\"2566130\"\
  >1</span> <span m=\"2566370\">over</span> <span m=\"2566570\">r</span> <span m=\"\
  2568390\">times</span> <span m=\"2569060\">n</span> <span m=\"2569260\">squared</span>\
  \ <span m=\"2569590\">over</span> <span m=\"2569790\">2.</span> <span m=\"2571740\"\
  >And</span> <span m=\"2571870\">if</span> <span m=\"2571990\">you</span> <span m=\"\
  2572080\">compare</span> <span m=\"2573010\">this</span> <span m=\"2573190\">number</span>\
  \ <span m=\"2573520\">to</span> <span m=\"2574030\">the</span> <span m=\"2574150\"\
  >number</span> <span m=\"2574570\">of</span> <span m=\"2574780\">edges</span> <span\
  \ m=\"2575620\">in</span> <span m=\"2575740\">the</span> <span m=\"2575980\">Tur\xE1\
  n</span> <span m=\"2576310\">graph,</span> <span m=\"2577030\">so</span> <span m=\"\
  2577330\">you</span> <span m=\"2577450\">see</span> <span m=\"2577750\">that</span>\
  \ <span m=\"2577990\">this</span> <span m=\"2578200\">is</span> <span m=\"2579130\"\
  >basically</span> <span m=\"2579610\">the</span> <span m=\"2579700\">number</span>\
  \ <span m=\"2579970\">of</span> <span m=\"2580060\">edges,</span> <span m=\"2580750\"\
  >and</span> <span m=\"2581285\">this</span> <span m=\"2581550\">gives</span> <span\
  \ m=\"2581830\">you</span> <span m=\"2581950\">a</span> <span m=\"2582060\">proof</span>\
  \ <span m=\"2585480\">if</span> <span m=\"2586450\">n</span> <span m=\"2586840\"\
  >is</span> <span m=\"2587300\">divisible</span> <span m=\"2591610\">by</span> <span\
  \ m=\"2592640\">r.</span></p><p><span m=\"2593810\">And</span> <span m=\"2594110\"\
  >in</span> <span m=\"2594200\">fact,</span> <span m=\"2594660\">the</span> <span\
  \ m=\"2594740\">number</span> <span m=\"2595190\">of</span> <span m=\"2595940\"\
  >edges</span> <span m=\"2596300\">in</span> <span m=\"2596360\">the</span> <span\
  \ m=\"2596450\">Tur\xE1n</span> <span m=\"2596720\">graph</span> <span m=\"2597020\"\
  >is</span> <span m=\"2597170\">exactly</span> <span m=\"2597710\">this</span> <span\
  \ m=\"2597860\">number</span> <span m=\"2598100\">here,</span> <span m=\"2598640\"\
  >if</span> <span m=\"2598760\">this</span> <span m=\"2598940\">divisibility</span>\
  \ <span m=\"2599990\">condition</span> <span m=\"2600470\">is</span> <span m=\"\
  2601120\">true.</span> <span m=\"2602190\">If</span> <span m=\"2602240\">it's</span>\
  \ <span m=\"2602360\">not,</span> <span m=\"2602730\">you</span> <span m=\"2602830\"\
  >need</span> <span m=\"2602870\">to</span> <span m=\"2602970\">do</span> <span m=\"\
  2603230\">a</span> <span m=\"2603290\">little</span> <span m=\"2603530\">bit</span>\
  \ <span m=\"2603650\">more</span> <span m=\"2603860\">work.</span> <span m=\"2604940\"\
  >Because</span> <span m=\"2606080\">we</span> <span m=\"2606470\">were</span> <span\
  \ m=\"2606890\">a</span> <span m=\"2606950\">little</span> <span m=\"2607160\">bit</span>\
  \ <span m=\"2607310\">lost</span> <span m=\"2607630\">here in</span> <span m=\"\
  2607880\">this</span> <span m=\"2608030\">step.</span> <span m=\"2609040\">So</span>\
  \ <span m=\"2609200\">you</span> <span m=\"2609290\">should</span> <span m=\"2609410\"\
  >see</span> <span m=\"2609650\">that</span> <span m=\"2610780\">this</span> <span\
  \ m=\"2611000\">quantity</span> <span m=\"2611360\">here</span> <span m=\"2611570\"\
  >is</span> <span m=\"2611720\">minimized</span> <span m=\"2612590\">when</span>\
  \ <span m=\"2613250\">all</span> <span m=\"2613430\">the</span> <span m=\"2613520\"\
  >degrees</span> <span m=\"2614030\">are</span> <span m=\"2615320\">roughly</span>\
  \ <span m=\"2615620\">equal</span> <span m=\"2615890\">to</span> <span m=\"2616010\"\
  >each</span> <span m=\"2616190\">other,</span> <span m=\"2616560\">and</span> <span\
  \ m=\"2616670\">you</span> <span m=\"2616730\">make</span> <span m=\"2616910\">them</span>\
  \ <span m=\"2617030\">as</span> <span m=\"2617150\">close</span> <span m=\"2618170\"\
  >to</span> <span m=\"2618320\">each</span> <span m=\"2618470\">other</span> <span\
  \ m=\"2618650\">as</span> <span m=\"2618770\">possible.</span></p><p><span m=\"\
  2621840\">So</span> <span m=\"2621890\">with</span> <span m=\"2622040\">a</span>\
  \ <span m=\"2622100\">little</span> <span m=\"2622250\">bit</span> <span m=\"2622370\"\
  >more</span> <span m=\"2622520\">work,</span> <span m=\"2622850\">you</span> <span\
  \ m=\"2622970\">can</span> <span m=\"2624020\">get</span> <span m=\"2624230\">the</span>\
  \ <span m=\"2624380\">exact</span> <span m=\"2624980\">version</span> <span m=\"\
  2625430\">of</span> <span m=\"2625550\">Tur\xE1n's</span> <span m=\"2625910\">theorem</span>\
  \ <span m=\"2626210\">up</span> <span m=\"2626330\">there.</span> <span m=\"2626740\"\
  >But</span> <span m=\"2626900\">at</span> <span m=\"2626970\">least</span> <span\
  \ m=\"2627320\">what</span> <span m=\"2627500\">we've</span> <span m=\"2627680\"\
  >shown</span> <span m=\"2629270\">is--</span> <span m=\"2630160\">so</span> <span\
  \ m=\"2630650\">from</span> <span m=\"2630830\">here,</span> <span m=\"2631370\"\
  >we've</span> <span m=\"2631580\">shown</span> <span m=\"2631910\">that</span> <span\
  \ m=\"2634880\">the</span> <span m=\"2634970\">number</span> <span m=\"2635210\"\
  >of</span> <span m=\"2635300\">edges</span> <span m=\"2635960\">is</span> <span\
  \ m=\"2637440\">at</span> <span m=\"2637540\">most</span> <span m=\"2638000\">this</span>\
  \ <span m=\"2638180\">quantity,</span> <span m=\"2638970\">which,</span> <span m=\"\
  2639050\">for</span> <span m=\"2639230\">most</span> <span m=\"2639470\">purposes,</span>\
  \ <span m=\"2639950\">is</span> <span m=\"2640310\">basically</span> <span m=\"\
  2640640\">as</span> <span m=\"2640880\">good</span> <span m=\"2641060\">as</span>\
  \ <span m=\"2641180\">Tur\xE1n's</span> <span m=\"2641540\">theorem.</span> <span\
  \ m=\"2646650\">Any</span> <span m=\"2646800\">questions</span> <span m=\"2647190\"\
  >about</span> <span m=\"2647760\">this</span> <span m=\"2647940\">proof here?</span>\
  \ <span m=\"2648470\">And so</span> <span m=\"2648720\">it's</span> <span m=\"2648810\"\
  >a</span> <span m=\"2648870\">probabilistic</span> <span m=\"2649560\">method</span>\
  \ <span m=\"2649990\">of</span> <span m=\"2650160\">proof.</span> <span m=\"2651046\"\
  >So</span> <span m=\"2651490\">we're</span> <span m=\"2652400\">introducing</span>\
  \ <span m=\"2652880\">some</span> <span m=\"2653060\">randomness</span> <span m=\"\
  2653600\">into</span> <span m=\"2653810\">the</span> <span m=\"2653900\">problem</span>\
  \ <span m=\"2654230\">that</span> <span m=\"2654470\">originally</span> <span m=\"\
  2654980\">had</span> <span m=\"2655130\">no</span> <span m=\"2655310\">randomness.</span></p><p><span\
  \ m=\"2659820\">Great.</span> <span m=\"2660010\">So</span> <span m=\"2660120\"\
  >let's</span> <span m=\"2660300\">take</span> <span m=\"2660540\">a</span> <span\
  \ m=\"2660900\">very</span> <span m=\"2661110\">quick</span> <span m=\"2661410\"\
  >2-minute</span> <span m=\"2661770\">break.</span> <span m=\"2662500\">And</span>\
  \ <span m=\"2662520\">then</span> <span m=\"2662640\">when</span> <span m=\"2662760\"\
  >we</span> <span m=\"2662850\">come</span> <span m=\"2663030\">back,</span> <span\
  \ m=\"2663670\">I</span> <span m=\"2663770\">want</span> <span m=\"2663810\">to</span>\
  \ <span m=\"2663900\">show</span> <span m=\"2664200\">you</span> <span m=\"2664710\"\
  >that</span> <span m=\"2665730\">even</span> <span m=\"2666150\">though</span> <span\
  \ m=\"2666690\">we've</span> <span m=\"2666900\">shown</span> <span m=\"2667200\"\
  >so</span> <span m=\"2667410\">many</span> <span m=\"2667620\">different</span>\
  \ <span m=\"2667890\">proofs</span> <span m=\"2668280\">of</span> <span m=\"2668580\"\
  >Tur\xE1n's</span> <span m=\"2668960\">theorem</span> <span m=\"2669210\">and</span>\
  \ <span m=\"2669360\">Mantel's</span> <span m=\"2669630\">theorem--</span> <span\
  \ m=\"2669870\">you</span> <span m=\"2669930\">might</span> <span m=\"2670080\"\
  >think,</span> <span m=\"2670330\">OK,</span> <span m=\"2670560\">this</span> <span\
  \ m=\"2670740\">is</span> <span m=\"2670860\">a</span> <span m=\"2670920\">pretty</span>\
  \ <span m=\"2671160\">simple</span> <span m=\"2671490\">thing--</span> <span m=\"\
  2672900\">even</span> <span m=\"2673170\">if</span> <span m=\"2673320\">I</span>\
  \ <span m=\"2673440\">tweak</span> <span m=\"2673770\">the</span> <span m=\"2673860\"\
  >problem</span> <span m=\"2674250\">just</span> <span m=\"2674520\">a</span> <span\
  \ m=\"2674580\">little</span> <span m=\"2674790\">bit,</span> <span m=\"2676310\"\
  >there</span> <span m=\"2676450\">are</span> <span m=\"2676510\">so</span> <span\
  \ m=\"2676720\">many</span> <span m=\"2676930\">things</span> <span m=\"2677110\"\
  >that</span> <span m=\"2677230\">we</span> <span m=\"2677350\">do</span> <span m=\"\
  2677470\">not</span> <span m=\"2677620\">understand,</span> <span m=\"2678200\"\
  >and</span> <span m=\"2678300\">many</span> <span m=\"2678970\">important</span>\
  \ <span m=\"2679390\">open</span> <span m=\"2679660\">problems</span> <span m=\"\
  2679970\">in</span> <span m=\"2680080\">combinatorics</span> <span m=\"2681160\"\
  >that</span> <span m=\"2681370\">are</span> <span m=\"2681460\">variants</span>\
  \ <span m=\"2682210\">of</span> <span m=\"2682420\">Tur\xE1n's</span> <span m=\"\
  2682860\">theorem.</span> <span m=\"2685010\">So</span> <span m=\"2685140\">let's</span>\
  \ <span m=\"2685290\">take</span> <span m=\"2685440\">a</span> <span m=\"2685470\"\
  >quick</span> <span m=\"2685650\">break.</span></p><p><span m=\"2691960\">So</span>\
  \ <span m=\"2692090\">so</span> <span m=\"2692270\">far</span> <span m=\"2692450\"\
  >we've</span> <span m=\"2692600\">been</span> <span m=\"2692750\">talking</span>\
  \ <span m=\"2693140\">about</span> <span m=\"2694160\">Tur\xE1n's</span> <span m=\"\
  2694610\">theorem,</span> <span m=\"2695930\">or</span> <span m=\"2696080\">generally</span>\
  \ <span m=\"2696620\">the</span> <span m=\"2696830\">problem</span> <span m=\"2697210\"\
  >of,</span> <span m=\"2697880\">if</span> <span m=\"2698030\">you</span> <span m=\"\
  2698270\">forbid</span> <span m=\"2698930\">a</span> <span m=\"2698990\">certain</span>\
  \ <span m=\"2699320\">structure,</span> <span m=\"2699830\">forbid</span> <span\
  \ m=\"2700110\">a</span> <span m=\"2700250\">certain</span> <span m=\"2700520\"\
  >subgraph,</span> <span m=\"2701360\">what</span> <span m=\"2701570\">is</span>\
  \ <span m=\"2701690\">the</span> <span m=\"2701780\">maximum</span> <span m=\"2702410\"\
  >number</span> <span m=\"2702710\">of</span> <span m=\"2702890\">edges?</span> <span\
  \ m=\"2705730\">We're</span> <span m=\"2705780\">going</span> <span m=\"2705960\"\
  >to</span> <span m=\"2706020\">spend</span> <span m=\"2706230\">the</span> <span\
  \ m=\"2706290\">next</span> <span m=\"2706560\">few</span> <span m=\"2706710\">lectures</span>\
  \ <span m=\"2707100\">discussing</span> <span m=\"2707970\">more</span> <span m=\"\
  2708120\">problems</span> <span m=\"2708480\">of</span> <span m=\"2708570\">that</span>\
  \ <span m=\"2708690\">form.</span> <span m=\"2709480\">And</span> <span m=\"2709600\"\
  >it</span> <span m=\"2709680\">turns</span> <span m=\"2709920\">out,</span> <span\
  \ m=\"2711210\">for</span> <span m=\"2712320\">the</span> <span m=\"2712470\">answers</span>\
  \ <span m=\"2712890\">we've</span> <span m=\"2713040\">just</span> <span m=\"2713250\"\
  >seen,</span> <span m=\"2713520\">they</span> <span m=\"2713790\">are</span> <span\
  \ m=\"2713940\">deceptively</span> <span m=\"2714600\">simple.</span> <span m=\"\
  2715300\">And</span> <span m=\"2715410\">for</span> <span m=\"2715590\">almost</span>\
  \ <span m=\"2716340\">any</span> <span m=\"2716580\">other</span> <span m=\"2716760\"\
  >situation,</span> <span m=\"2717690\">we</span> <span m=\"2717840\">don't</span>\
  \ <span m=\"2718050\">really</span> <span m=\"2718260\">know</span> <span m=\"2719370\"\
  >the</span> <span m=\"2719490\">exact</span> <span m=\"2719880\">answer.</span>\
  \ <span m=\"2720340\">And</span> <span m=\"2720810\">for</span> <span m=\"2720960\"\
  >many</span> <span m=\"2721200\">questions,</span> <span m=\"2721590\">we</span>\
  \ <span m=\"2721710\">don't</span> <span m=\"2721860\">know</span> <span m=\"2721980\"\
  >anything</span> <span m=\"2722310\">close</span> <span m=\"2722910\">to</span>\
  \ <span m=\"2723030\">the</span> <span m=\"2723120\">truth.</span></p><p><span m=\"\
  2724350\">And in</span> <span m=\"2724440\">particular,</span> <span m=\"2724860\"\
  >I</span> <span m=\"2724950\">want</span> <span m=\"2725130\">to</span> <span m=\"\
  2725190\">show</span> <span m=\"2725430\">you</span> <span m=\"2725580\">one</span>\
  \ <span m=\"2725880\">variant</span> <span m=\"2726810\">of</span> <span m=\"2727380\"\
  >this</span> <span m=\"2727560\">problem,</span> <span m=\"2728670\">namely</span>\
  \ <span m=\"2729000\">what</span> <span m=\"2729180\">happens,</span> <span m=\"\
  2730050\">instead</span> <span m=\"2730350\">of</span> <span m=\"2730560\">looking</span>\
  \ <span m=\"2730860\">at</span> <span m=\"2730950\">graphs,</span> <span m=\"2731640\"\
  >if</span> <span m=\"2731760\">you</span> <span m=\"2731850\">look</span> <span\
  \ m=\"2732030\">at</span> <span m=\"2732090\">hypergraphs.</span> <span m=\"2733640\"\
  >And</span> <span m=\"2733770\">there,</span> <span m=\"2734390\">that's</span>\
  \ <span m=\"2734580\">a</span> <span m=\"2734640\">major</span> <span m=\"2735090\"\
  >open</span> <span m=\"2735360\">problem</span> <span m=\"2735630\">in</span> <span\
  \ m=\"2735690\">combinatorics,</span> <span m=\"2736860\">what</span> <span m=\"\
  2737040\">the</span> <span m=\"2737130\">truth</span> <span m=\"2737550\">should</span>\
  \ <span m=\"2737760\">be.</span> <span m=\"2739150\">So</span> <span m=\"2739330\"\
  >here</span> <span m=\"2739630\">is</span> <span m=\"2740320\">an</span> <span m=\"\
  2740470\">open</span> <span m=\"2740770\">problem,</span> <span m=\"2747190\">which</span>\
  \ <span m=\"2747400\">is,</span> <span m=\"2747850\">what</span> <span m=\"2748030\"\
  >happens</span> <span m=\"2748960\">to</span> <span m=\"2749940\">Tur\xE1n's</span>\
  \ <span m=\"2750430\">theorem</span> <span m=\"2751000\">for</span> <span m=\"2751280\"\
  >3-uniform</span> <span m=\"2752080\">hypergraphs?</span></p><p><span m=\"2759990\"\
  >So</span> <span m=\"2760130\">don't</span> <span m=\"2760310\">be</span> <span\
  \ m=\"2760700\">scared</span> <span m=\"2761060\">by</span> <span m=\"2761180\"\
  >the</span> <span m=\"2761240\">word</span> <span m=\"2761510\">hypergraph.</span>\
  \ <span m=\"2762570\">So</span> <span m=\"2762950\">whereas</span> <span m=\"2763280\"\
  >you</span> <span m=\"2763370\">think</span> <span m=\"2763610\">of</span> <span\
  \ m=\"2763700\">graphs</span> <span m=\"2764570\">as</span> <span m=\"2764990\"\
  >having</span> <span m=\"2765320\">edges</span> <span m=\"2765620\">consisting</span>\
  \ <span m=\"2766160\">of</span> <span m=\"2766250\">pairs</span> <span m=\"2766640\"\
  >of</span> <span m=\"2766700\">vertices,</span> <span m=\"2767270\">a</span> <span\
  \ m=\"2767520\">hypergraph</span> <span m=\"2768260\">is</span> <span m=\"2768320\"\
  >simply</span> <span m=\"2768710\">a</span> <span m=\"2768770\">structure</span>\
  \ <span m=\"2769640\">where,</span> <span m=\"2770510\">for a</span> <span m=\"\
  2770870\">3-uniform</span> <span m=\"2771470\">hypergraph,</span> <span m=\"2772200\"\
  >the</span> <span m=\"2772370\">edges</span> <span m=\"2772700\">are</span> <span\
  \ m=\"2772760\">triples,</span> <span m=\"2773900\">triples</span> <span m=\"2774300\"\
  >of</span> <span m=\"2774360\">vertices.</span> <span m=\"2777130\">So</span> <span\
  \ m=\"2778060\">the</span> <span m=\"2778400\">question</span> <span m=\"2778730\"\
  >is,</span> <span m=\"2779060\">what</span> <span m=\"2779270\">is</span> <span\
  \ m=\"2779390\">the</span> <span m=\"2779480\">maximum</span> <span m=\"2780080\"\
  >number</span> <span m=\"2780380\">of</span> <span m=\"2780500\">triples</span>\
  \ <span m=\"2786770\">in</span> <span m=\"2787120\">3-uniform</span> <span m=\"\
  2787800\">hypergraph</span> <span m=\"2796860\">without--</span> <span m=\"2797820\"\
  >well,</span> <span m=\"2797940\">for</span> <span m=\"2798420\">Mantel's</span>\
  \ <span m=\"2798630\">theorem,</span> <span m=\"2799150\">we</span> <span m=\"2799350\"\
  >asked</span> <span m=\"2799650\">what</span> <span m=\"2800040\">happens</span>\
  \ <span m=\"2800400\">without</span> <span m=\"2800940\">a</span> <span m=\"2801000\"\
  >triangle.</span> <span m=\"2801885\">For a</span> <span m=\"2802200\">3-uniform,</span>\
  \ <span m=\"2803800\">the</span> <span m=\"2804210\">basic</span> <span m=\"2804570\"\
  >question</span> <span m=\"2804910\">you</span> <span m=\"2804990\">can</span> <span\
  \ m=\"2805170\">ask</span> <span m=\"2805560\">is,</span> <span m=\"2806110\">what</span>\
  \ <span m=\"2806160\">about</span> <span m=\"2806460\">forbidding</span> <span m=\"\
  2807000\">a</span> <span m=\"2807060\">tetrahedral?</span></p><p><span m=\"2813590\"\
  >So</span> <span m=\"2813840\">suppose</span> <span m=\"2814410\">you</span> <span\
  \ m=\"2814560\">do</span> <span m=\"2814770\">have</span> <span m=\"2820750\">four</span>\
  \ <span m=\"2820960\">vertices</span> <span m=\"2822280\">such</span> <span m=\"\
  2822490\">that</span> <span m=\"2822670\">every</span> <span m=\"2823780\">triple</span>\
  \ <span m=\"2824460\">inside</span> <span m=\"2824780\">the</span> <span m=\"2824860\"\
  >four</span> <span m=\"2825010\">vertices</span> <span m=\"2826270\">is</span> <span\
  \ m=\"2826800\">a</span> <span m=\"2826870\">niche.</span> <span m=\"2828370\">What's</span>\
  \ <span m=\"2828610\">the</span> <span m=\"2828700\">maximum</span> <span m=\"2829300\"\
  >number</span> <span m=\"2829630\">of</span> <span m=\"2829750\">edges</span> <span\
  \ m=\"2830770\">you</span> <span m=\"2830860\">can</span> <span m=\"2831010\">have</span>\
  \ <span m=\"2832180\">in</span> <span m=\"2832400\">an</span> <span m=\"2833000\"\
  >n-vertex,</span> <span m=\"2834220\">3-uniform</span> <span m=\"2835600\">hypergraph.</span>\
  \ <span m=\"2837600\">Already,</span> <span m=\"2838020\">it's</span> <span m=\"\
  2838170\">not</span> <span m=\"2838410\">so</span> <span m=\"2838710\">easy</span>\
  \ <span m=\"2839040\">to</span> <span m=\"2839160\">come</span> <span m=\"2839460\"\
  >up</span> <span m=\"2839610\">with</span> <span m=\"2839820\">good</span> <span\
  \ m=\"2840120\">examples.</span> <span m=\"2841990\">So</span> <span m=\"2842700\"\
  >Tur\xE1n's</span> <span m=\"2842880\">theorem</span> <span m=\"2843260\">says</span>\
  \ <span m=\"2843640\">take</span> <span m=\"2843870\">a</span> <span m=\"2843930\"\
  >bipartite</span> <span m=\"2844350\">graph,</span> <span m=\"2844710\">complete</span>\
  \ <span m=\"2844990\">bipartite</span> <span m=\"2845550\">graph.</span> <span m=\"\
  2846700\">Well,</span> <span m=\"2847200\">here,</span> <span m=\"2848400\">it's</span>\
  \ <span m=\"2848520\">not</span> <span m=\"2848700\">so</span> <span m=\"2848880\"\
  >easy</span> <span m=\"2849060\">to</span> <span m=\"2849120\">come</span> <span\
  \ m=\"2849330\">up</span> <span m=\"2849450\">with</span> <span m=\"2849570\">examples,</span>\
  \ <span m=\"2850090\">but</span> <span m=\"2850380\">there</span> <span m=\"2850530\"\
  >are</span> <span m=\"2850680\">some</span> <span m=\"2850920\">examples.</span></p><p><span\
  \ m=\"2851890\">And</span> <span m=\"2852030\">in</span> <span m=\"2852150\">fact,</span>\
  \ <span m=\"2852270\">Tur\xE1n</span> <span m=\"2852780\">suggested</span> <span\
  \ m=\"2853320\">the</span> <span m=\"2853410\">following</span> <span m=\"2853860\"\
  >construction.</span> <span m=\"2855630\">Namely,</span> <span m=\"2856680\">you</span>\
  \ <span m=\"2857790\">divide</span> <span m=\"2858270\">the</span> <span m=\"2858870\"\
  >set</span> <span m=\"2859200\">of</span> <span m=\"2859260\">vertices,</span> <span\
  \ m=\"2860850\">as</span> <span m=\"2861060\">before,</span> <span m=\"2861790\"\
  >to</span> <span m=\"2862150\">three</span> <span m=\"2864450\">roughly</span> <span\
  \ m=\"2864810\">equal-sized</span> <span m=\"2865410\">parts.</span> <span m=\"\
  2866610\">And</span> <span m=\"2866730\">let</span> <span m=\"2866880\">me</span>\
  \ <span m=\"2867000\">take</span> <span m=\"2867690\">all</span> <span m=\"2867960\"\
  >triples</span> <span m=\"2869100\">that</span> <span m=\"2869250\">look</span>\
  \ <span m=\"2869760\">like</span> <span m=\"2870060\">one</span> <span m=\"2870300\"\
  >of</span> <span m=\"2870360\">the</span> <span m=\"2870450\">following</span> <span\
  \ m=\"2870960\">forms,</span> <span m=\"2872130\">either</span> <span m=\"2873340\"\
  >three</span> <span m=\"2873570\">vertices,</span> <span m=\"2874270\">one</span>\
  \ <span m=\"2874480\">in</span> <span m=\"2874660\">each</span> <span m=\"2875130\"\
  >vertex</span> <span m=\"2875580\">set,</span> <span m=\"2877150\">or</span> <span\
  \ m=\"2878980\">a</span> <span m=\"2879370\">triple,</span> <span m=\"2879790\"\
  >looking</span> <span m=\"2880120\">like</span> <span m=\"2880270\">that--</span>\
  \ <span m=\"2880510\">two vertex</span> <span m=\"2880930\">in</span> <span m=\"\
  2881290\">one</span> <span m=\"2881755\">set,</span> <span m=\"2882220\">one in</span>\
  \ <span m=\"2882370\">the</span> <span m=\"2882460\">next</span> <span m=\"2882910\"\
  >set,</span> <span m=\"2883580\">or</span> <span m=\"2883900\">going</span> <span\
  \ m=\"2884260\">cyclically,</span> <span m=\"2885220\">like</span> <span m=\"2885430\"\
  >that.</span> <span m=\"2886990\">So</span> <span m=\"2887080\">I</span> <span m=\"\
  2887140\">include</span> <span m=\"2888190\">all</span> <span m=\"2888430\">triples,</span>\
  \ <span m=\"2889870\">one</span> <span m=\"2890080\">of</span> <span m=\"2890200\"\
  >these</span> <span m=\"2890410\">forms.</span></p><p><span m=\"2891870\">And</span>\
  \ <span m=\"2892090\">you</span> <span m=\"2892150\">should</span> <span m=\"2892300\"\
  >check</span> <span m=\"2892990\">that</span> <span m=\"2893320\">this</span> <span\
  \ m=\"2893530\">construction</span> <span m=\"2895990\">has</span> <span m=\"2896200\"\
  >no</span> <span m=\"2896560\">tetrahedron.</span> <span m=\"2899580\">If</span>\
  \ <span m=\"2899700\">it</span> <span m=\"2899780\">had</span> <span m=\"2899960\"\
  >a</span> <span m=\"2900020\">tetrahedron,</span> <span m=\"2901170\">you</span>\
  \ <span m=\"2901190\">would</span> <span m=\"2901340\">have</span> <span m=\"2901460\"\
  >had</span> <span m=\"2902570\">at</span> <span m=\"2902660\">least</span> <span\
  \ m=\"2902840\">two</span> <span m=\"2903080\">vertices</span> <span m=\"2903500\"\
  >in</span> <span m=\"2903570\">one</span> <span m=\"2903800\">part,</span> <span\
  \ m=\"2904700\">also</span> <span m=\"2904910\">then</span> <span m=\"2905060\"\
  >where</span> <span m=\"2905270\">the</span> <span m=\"2905420\">other</span> <span\
  \ m=\"2905630\">two</span> <span m=\"2905810\">vertices</span> <span m=\"2906290\"\
  >can</span> <span m=\"2906440\">be.</span> <span m=\"2908566\">If</span> <span m=\"\
  2909030\">you check</span> <span m=\"2909494\">that,</span> <span m=\"2910405\"\
  >it</span> <span m=\"2910710\">cannot</span> <span m=\"2911010\">happen.</span></p><p><span\
  \ m=\"2912640\">So</span> <span m=\"2912810\">then,</span> <span m=\"2913290\">how</span>\
  \ <span m=\"2913500\">many</span> <span m=\"2913800\">edges</span> <span m=\"2914190\"\
  >does</span> <span m=\"2914400\">it</span> <span m=\"2914510\">have?</span> <span\
  \ m=\"2915780\">The</span> <span m=\"2915870\">exact</span> <span m=\"2916200\"\
  >number</span> <span m=\"2916480\">is</span> <span m=\"2916560\">not</span> <span\
  \ m=\"2916770\">so</span> <span m=\"2916980\">important.</span> <span m=\"2917400\"\
  >But</span> <span m=\"2917520\">what's</span> <span m=\"2917700\">important</span>\
  \ <span m=\"2918150\">is</span> <span m=\"2918300\">that</span> <span m=\"2918450\"\
  >the</span> <span m=\"2918740\">edge</span> <span m=\"2919020\">density--</span>\
  \ <span m=\"2920442\">of</span> <span m=\"2921435\">all</span> <span m=\"2921750\"\
  >the</span> <span m=\"2921900\">possible</span> <span m=\"2922380\">triples,</span>\
  \ <span m=\"2922800\">the</span> <span m=\"2922890\">fraction</span> <span m=\"\
  2923550\">of</span> <span m=\"2924330\">edges</span> <span m=\"2924770\">that</span>\
  \ <span m=\"2924950\">are</span> <span m=\"2925110\">containing</span> <span m=\"\
  2925680\">this</span> <span m=\"2925860\">construction</span> <span m=\"2926760\"\
  >is</span> <span m=\"2927510\">5/9.</span> <span m=\"2930700\">And</span> <span\
  \ m=\"2932660\">it</span> <span m=\"2932840\">is</span> <span m=\"2932960\">conjectured</span>\
  \ <span m=\"2933710\">that</span> <span m=\"2934100\">this</span> <span m=\"2934280\"\
  >is</span> <span m=\"2934460\">optimal.</span></p><p><span m=\"2939410\">However,</span>\
  \ <span m=\"2939830\">we're</span> <span m=\"2940040\">quite</span> <span m=\"2940280\"\
  >far</span> <span m=\"2940580\">from</span> <span m=\"2940880\">proving</span> <span\
  \ m=\"2941540\">this</span> <span m=\"2941690\">number.</span> <span m=\"2942500\"\
  >So</span> <span m=\"2942650\">the</span> <span m=\"2942770\">best</span> <span\
  \ m=\"2943640\">upper</span> <span m=\"2943880\">bound</span> <span m=\"2945660\"\
  >that</span> <span m=\"2945990\">is</span> <span m=\"2946230\">currently</span>\
  \ <span m=\"2946650\">available--</span> <span m=\"2949920\">and</span> <span m=\"\
  2950100\">it's</span> <span m=\"2950550\">found</span> <span m=\"2950850\">quite</span>\
  \ <span m=\"2951150\">recently</span> <span m=\"2951530\">using</span> <span m=\"\
  2951960\">this</span> <span m=\"2952500\">fairly</span> <span m=\"2952860\">new</span>\
  \ <span m=\"2953100\">method</span> <span m=\"2953640\">in</span> <span m=\"2953760\"\
  >graph</span> <span m=\"2954060\">theory</span> <span m=\"2954330\">called</span>\
  \ <span m=\"2954540\">flag</span> <span m=\"2955050\">algebras,</span> <span m=\"\
  2955965\">essentially</span> <span m=\"2956730\">a</span> <span m=\"2956790\">computerized</span>\
  \ <span m=\"2957570\">way</span> <span m=\"2957840\">to</span> <span m=\"2958500\"\
  >try</span> <span m=\"2958680\">to</span> <span m=\"2958770\">prove</span> <span\
  \ m=\"2959160\">such</span> <span m=\"2959430\">inequalities.</span> <span m=\"\
  2960840\">And</span> <span m=\"2961140\">the</span> <span m=\"2961260\">best</span>\
  \ <span m=\"2961860\">upper</span> <span m=\"2962070\">bound</span> <span m=\"2964320\"\
  >is</span> <span m=\"2964770\">something</span> <span m=\"2965160\">like</span>\
  \ <span m=\"2965430\">0.562.</span> <span m=\"2968690\">And</span> <span m=\"2968880\"\
  >there's</span> <span m=\"2969040\">a</span> <span m=\"2969070\">major</span> <span\
  \ m=\"2969460\">open</span> <span m=\"2969740\">problem</span> <span m=\"2970360\"\
  >to</span> <span m=\"2971110\">either</span> <span m=\"2971320\">prove</span> <span\
  \ m=\"2971680\">or</span> <span m=\"2971800\">disprove</span> <span m=\"2972910\"\
  >that</span> <span m=\"2973210\">this</span> <span m=\"2973420\">construction</span>\
  \ <span m=\"2973990\">here</span> <span m=\"2974710\">is</span> <span m=\"2974860\"\
  >the</span> <span m=\"2974980\">optimal</span> <span m=\"2975400\">one.</span></p><p><span\
  \ m=\"2976780\">So</span> <span m=\"2976900\">you</span> <span m=\"2977020\">see,</span>\
  \ <span m=\"2978010\">even</span> <span m=\"2978250\">though</span> <span m=\"2978430\"\
  >I</span> <span m=\"2978520\">presented</span> <span m=\"2978910\">so</span> <span\
  \ m=\"2979120\">many</span> <span m=\"2979330\">proofs</span> <span m=\"2979840\"\
  >of</span> <span m=\"2980350\">Mantel's</span> <span m=\"2980530\">theorem</span>\
  \ <span m=\"2980940\">and</span> <span m=\"2981260\">Tur\xE1n's</span> <span m=\"\
  2981440\">theorem,</span> <span m=\"2981670\">at</span> <span m=\"2981760\">this</span>\
  \ <span m=\"2981940\">point,</span> <span m=\"2982210\">hopefully</span> <span m=\"\
  2982600\">they</span> <span m=\"2982720\">should</span> <span m=\"2982900\">all</span>\
  \ <span m=\"2983080\">be--</span> <span m=\"2983660\">they</span> <span m=\"2984100\"\
  >seem</span> <span m=\"2984370\">quite</span> <span m=\"2984610\">simple</span>\
  \ <span m=\"2985390\">in</span> <span m=\"2985510\">retrospect.</span> <span m=\"\
  2989210\">It's</span> <span m=\"2989320\">deceptive.</span> <span m=\"2990100\"\
  >And</span> <span m=\"2990190\">even</span> <span m=\"2990460\">if</span> <span\
  \ m=\"2990580\">I</span> <span m=\"2990670\">changed</span> <span m=\"2991150\"\
  >and</span> <span m=\"2991240\">tweak</span> <span m=\"2991510\">the</span> <span\
  \ m=\"2991600\">problem</span> <span m=\"2991930\">just</span> <span m=\"2992170\"\
  >a</span> <span m=\"2992230\">little</span> <span m=\"2992440\">bit,</span> <span\
  \ m=\"2993320\">going</span> <span m=\"2993700\">to</span> <span m=\"2994030\">3-uniform</span>\
  \ <span m=\"2994720\">hypergraph</span> <span m=\"2995650\">instead</span> <span\
  \ m=\"2995950\">of</span> <span m=\"2996040\">graphs,</span> <span m=\"2997000\"\
  >we</span> <span m=\"2997210\">really</span> <span m=\"2997450\">have</span> <span\
  \ m=\"2997630\">no</span> <span m=\"2997840\">idea</span> <span m=\"2998410\">what's</span>\
  \ <span m=\"2998620\">going</span> <span m=\"2998910\">on.</span> <span m=\"2999920\"\
  >Yes?</span> <span m=\"3000170\">Question?</span></p><p><span m=\"3000690\">AUDIENCE:</span>\
  \ <span m=\"3000800\">So</span> <span m=\"3000910\">basically,</span> <span m=\"\
  3001960\">how</span> <span m=\"3002210\">do</span> <span m=\"3002280\">you--</span>\
  \ <span m=\"3002790\">why</span> <span m=\"3002990\">you</span> <span m=\"3003080\"\
  >say</span> <span m=\"3003280\">that</span> <span m=\"3003510\">this</span> <span\
  \ m=\"3003690\">is</span> <span m=\"3004070\">really</span> <span m=\"3004320\"\
  >bad</span> <span m=\"3004560\">compared</span> <span m=\"3005030\">to a</span>\
  \ <span m=\"3005500\">two-number?</span> <span m=\"3007250\">It doesn't</span> <span\
  \ m=\"3007570\">seem like</span> <span m=\"3007740\">that</span> <span m=\"3008237\"\
  >big a</span> <span m=\"3008734\">difference.</span></p><p><span m=\"3009730\">YUFEI\
  \ ZHAO:</span> <span m=\"3009855\">OK.</span> <span m=\"3009980\">So</span> <span\
  \ m=\"3010500\">great.</span> <span m=\"3010620\">So</span> <span m=\"3010890\"\
  >the</span> <span m=\"3010980\">question</span> <span m=\"3011310\">is,</span> <span\
  \ m=\"3011460\">why</span> <span m=\"3011760\">do</span> <span m=\"3011880\">I</span>\
  \ <span m=\"3011970\">say</span> <span m=\"3012300\">it's</span> <span m=\"3012870\"\
  >a</span> <span m=\"3012930\">pretty</span> <span m=\"3013260\">big</span> <span\
  \ m=\"3013500\">gap.</span> <span m=\"3014380\">So</span> <span m=\"3014430\">we</span>\
  \ <span m=\"3014700\">know</span> <span m=\"3015180\">that</span> <span m=\"3015630\"\
  >there</span> <span m=\"3015780\">has</span> <span m=\"3016110\">to</span> <span\
  \ m=\"3016200\">be</span> <span m=\"3016470\">some</span> <span m=\"3018320\">proportion</span>\
  \ <span m=\"3019070\">of</span> <span m=\"3019220\">the</span> <span m=\"3019310\"\
  >total</span> <span m=\"3019640\">number</span> <span m=\"3019970\">of</span> <span\
  \ m=\"3020570\">triples.</span> <span m=\"3021570\">So,</span> <span m=\"3022520\"\
  >well,</span> <span m=\"3022820\">you</span> <span m=\"3022970\">have</span> <span\
  \ m=\"3023180\">two</span> <span m=\"3023360\">numbers.</span> <span m=\"3023810\"\
  >And</span> <span m=\"3024280\">well,</span> <span m=\"3026280\">I</span> <span\
  \ m=\"3026340\">mean,</span> <span m=\"3026430\">to</span> <span m=\"3026520\">me,</span>\
  \ <span m=\"3026670\">they</span> <span m=\"3026770\">seem</span> <span m=\"3026970\"\
  >pretty</span> <span m=\"3027210\">far</span> <span m=\"3027390\">apart.</span>\
  \ <span m=\"3028290\">It's</span> <span m=\"3028410\">not</span> <span m=\"3028620\"\
  >some</span> <span m=\"3028950\">lower-order</span> <span m=\"3029640\">gap.</span>\
  \ <span m=\"3030200\">So</span> <span m=\"3030360\">this</span> <span m=\"3030540\"\
  >is</span> <span m=\"3030660\">a</span> <span m=\"3030720\">first-order</span> <span\
  \ m=\"3031320\">gap.</span> <span m=\"3034150\">Any</span> <span m=\"3034570\">more</span>\
  \ <span m=\"3034720\">questions?</span></p><p><span m=\"3035480\">But</span> <span\
  \ m=\"3035530\">it's</span> <span m=\"3035680\">true</span> <span m=\"3035800\"\
  >that</span> <span m=\"3035920\">later</span> <span m=\"3036190\">in</span> <span\
  \ m=\"3036280\">the</span> <span m=\"3036340\">course,</span> <span m=\"3036770\"\
  >we'll</span> <span m=\"3036880\">see</span> <span m=\"3037570\">gaps</span> <span\
  \ m=\"3037990\">that</span> <span m=\"3038080\">are</span> <span m=\"3038170\">much</span>\
  \ <span m=\"3038440\">bigger.</span> <span m=\"3038930\">We'll</span> <span m=\"\
  3039070\">see</span> <span m=\"3039250\">gaps</span> <span m=\"3039640\">where</span>\
  \ <span m=\"3039880\">there's</span> <span m=\"3040840\">a</span> <span m=\"3040900\"\
  >polynomial</span> <span m=\"3041530\">on</span> <span m=\"3041890\">one</span>\
  \ <span m=\"3042100\">side</span> <span m=\"3042820\">and</span> <span m=\"3043830\"\
  >a</span> <span m=\"3043900\">power</span> <span m=\"3044470\">of</span> <span m=\"\
  3044590\">exponentials</span> <span m=\"3045370\">on</span> <span m=\"3045490\"\
  >the</span> <span m=\"3045580\">other</span> <span m=\"3045790\">side.</span> <span\
  \ m=\"3046350\">And</span> <span m=\"3046470\">there,</span> <span m=\"3046720\"\
  >I</span> <span m=\"3046870\">agree,</span> <span m=\"3047140\">that's</span> <span\
  \ m=\"3047320\">much</span> <span m=\"3047710\">worse.</span> <span m=\"3048290\"\
  >The</span> <span m=\"3048400\">gap</span> <span m=\"3048670\">is</span> <span m=\"\
  3048790\">much</span> <span m=\"3049030\">bigger.</span> <span m=\"3049300\">Here,</span>\
  \ <span m=\"3049630\">it's</span> <span m=\"3049730\">just</span> <span m=\"3049900\"\
  >two</span> <span m=\"3050050\">numbers.</span> <span m=\"3050810\">But</span> <span\
  \ m=\"3051330\">in</span> <span m=\"3051430\">the</span> <span m=\"3051520\">worst</span>\
  \ <span m=\"3051790\">case,</span> <span m=\"3052190\">there</span> <span m=\"3052290\"\
  >can</span> <span m=\"3052300\">be</span> <span m=\"3052420\">two</span> <span m=\"\
  3052570\">numbers</span> <span m=\"3052930\">anywhere.</span> <span m=\"3055285\"\
  >Any</span> <span m=\"3055760\">more</span> <span m=\"3055960\">questions?</span></p><p><span\
  \ m=\"3058950\">So</span> <span m=\"3059230\">throughout</span> <span m=\"3059490\"\
  >this</span> <span m=\"3059670\">course,</span> <span m=\"3059940\">I will</span>\
  \ <span m=\"3060120\">try</span> <span m=\"3060390\">to</span> <span m=\"3060690\"\
  >bring</span> <span m=\"3061020\">out</span> <span m=\"3061200\">some</span> <span\
  \ m=\"3061710\">open</span> <span m=\"3061980\">problems.</span> <span m=\"3062340\"\
  >And</span> <span m=\"3062850\">there</span> <span m=\"3063240\">are</span> <span\
  \ m=\"3063360\">lots.</span> <span m=\"3063850\">So</span> <span m=\"3064030\">I</span>\
  \ <span m=\"3064110\">will</span> <span m=\"3064260\">tell</span> <span m=\"3064530\"\
  >you</span> <span m=\"3064620\">what</span> <span m=\"3064890\">we</span> <span\
  \ m=\"3065010\">do</span> <span m=\"3065190\">understand.</span> <span m=\"3065970\"\
  >But</span> <span m=\"3066060\">most</span> <span m=\"3066300\">things,</span> <span\
  \ m=\"3066570\">we</span> <span m=\"3067080\">do</span> <span m=\"3067200\">not</span>\
  \ <span m=\"3067410\">understand.</span> <span m=\"3068160\">And</span> <span m=\"\
  3069690\">hopefully,</span> <span m=\"3070380\">some</span> <span m=\"3070590\"\
  >of</span> <span m=\"3070680\">you</span> <span m=\"3070830\">will</span> <span\
  \ m=\"3071370\">go out</span> <span m=\"3071550\">and</span> <span m=\"3071670\"\
  >try</span> <span m=\"3071850\">to</span> <span m=\"3071940\">understand</span>\
  \ <span m=\"3072390\">them</span> <span m=\"3072450\">better</span> <span m=\"3073280\"\
  >so</span> <span m=\"3073410\">the</span> <span m=\"3073500\">next</span> <span\
  \ m=\"3073740\">time</span> <span m=\"3073920\">I</span> <span m=\"3074010\">teach</span>\
  \ <span m=\"3074220\">the</span> <span m=\"3074310\">course,</span> <span m=\"3074640\"\
  >I</span> <span m=\"3074700\">could</span> <span m=\"3074850\">have</span> <span\
  \ m=\"3074970\">something</span> <span m=\"3075270\">new</span> <span m=\"3075390\"\
  >to</span> <span m=\"3075480\">present.</span></p><p><span m=\"3085790\">So</span>\
  \ <span m=\"3085970\">now</span> <span m=\"3086210\">that</span> <span m=\"3086390\"\
  >we've</span> <span m=\"3087410\">addressed</span> <span m=\"3087830\">the</span>\
  \ <span m=\"3087920\">question</span> <span m=\"3088460\">of</span> <span m=\"3088640\"\
  >what's</span> <span m=\"3088880\">the</span> <span m=\"3088970\">maximum</span>\
  \ <span m=\"3089510\">number</span> <span m=\"3089780\">of</span> <span m=\"3089900\"\
  >edges</span> <span m=\"3090290\">if</span> <span m=\"3090380\">you</span> <span\
  \ m=\"3090470\">forbid</span> <span m=\"3090920\">a</span> <span m=\"3090980\">triangle</span>\
  \ <span m=\"3092120\">or</span> <span m=\"3092310\">a</span> <span m=\"3092360\"\
  >clique,</span> <span m=\"3093650\">the</span> <span m=\"3093740\">next</span> <span\
  \ m=\"3094070\">natural</span> <span m=\"3094430\">thing</span> <span m=\"3094610\"\
  >to</span> <span m=\"3094730\">ask</span> <span m=\"3095090\">is,</span> <span m=\"\
  3095630\">what</span> <span m=\"3095810\">about</span> <span m=\"3096110\">if</span>\
  \ <span m=\"3096320\">you</span> <span m=\"3096470\">forbid</span> <span m=\"3097140\"\
  >a</span> <span m=\"3097250\">general</span> <span m=\"3098740\">H?</span> <span\
  \ m=\"3099510\">So</span> <span m=\"3100370\">give</span> <span m=\"3100610\">me</span>\
  \ <span m=\"3101200\">a</span> <span m=\"3101510\">graph</span> <span m=\"3101960\"\
  >H.</span> <span m=\"3103010\">And</span> <span m=\"3103820\">what's</span> <span\
  \ m=\"3104030\">the</span> <span m=\"3104120\">maximum</span> <span m=\"3104630\"\
  >number</span> <span m=\"3104840\">of</span> <span m=\"3104960\">edges</span> <span\
  \ m=\"3105440\">if</span> <span m=\"3105570\">you</span> <span m=\"3105700\">forbid</span>\
  \ <span m=\"3106050\">that</span> <span m=\"3106430\">H?</span></p><p><span m=\"\
  3116430\">It will</span> <span m=\"3116570\">be</span> <span m=\"3116690\">helpful</span>\
  \ <span m=\"3117050\">to</span> <span m=\"3117140\">do</span> <span m=\"3117490\"\
  >some</span> <span m=\"3117620\">notation.</span> <span m=\"3118550\">So</span>\
  \ <span m=\"3118730\">the</span> <span m=\"3118880\">extremal</span> <span m=\"\
  3119420\">number,</span> <span m=\"3120880\">which we'll</span> <span m=\"3121130\"\
  >denote</span> <span m=\"3121460\">by</span> <span m=\"3121960\">ex,</span> <span\
  \ m=\"3122750\">and</span> <span m=\"3122960\">this</span> <span m=\"3123110\">is</span>\
  \ <span m=\"3123230\">also</span> <span m=\"3123710\">called the</span> <span m=\"\
  3124030\">Tur\xE1n</span> <span m=\"3124460\">number</span> <span m=\"3126110\"\
  >sometimes</span> <span m=\"3126920\">because</span> <span m=\"3128180\">of</span>\
  \ <span m=\"3128750\">Tur\xE1n's</span> <span m=\"3129230\">theorem.</span> <span\
  \ m=\"3131350\">So</span> <span m=\"3131790\">I'll</span> <span m=\"3132670\">probably</span>\
  \ <span m=\"3133130\">call</span> <span m=\"3133400\">it</span> <span m=\"3133680\"\
  >the</span> <span m=\"3133820\">extremal</span> <span m=\"3134240\">number</span>\
  \ <span m=\"3135620\">more</span> <span m=\"3135770\">frequently.</span> <span m=\"\
  3138240\">So</span> <span m=\"3138830\">this</span> <span m=\"3139040\">number</span>\
  \ <span m=\"3139310\">here</span> <span m=\"3139550\">is</span> <span m=\"3139700\"\
  >defined</span> <span m=\"3140150\">to</span> <span m=\"3140270\">be</span> <span\
  \ m=\"3140420\">the</span> <span m=\"3140540\">maximum</span> <span m=\"3141140\"\
  >number</span> <span m=\"3141560\">of</span> <span m=\"3141710\">edges</span> <span\
  \ m=\"3146760\">in</span> <span m=\"3148340\">an</span> <span m=\"3148590\">n-vertex</span>\
  \ <span m=\"3150960\">graph</span> <span m=\"3154580\">containing</span> <span m=\"\
  3159050\">no</span> <span m=\"3159320\">copy</span> <span m=\"3159830\">of</span>\
  \ <span m=\"3160010\">H</span> <span m=\"3160430\">as</span> <span m=\"3160550\"\
  >a</span> <span m=\"3160720\">subgraph.</span></p><p><span m=\"3171900\">I</span>\
  \ <span m=\"3171960\">want</span> <span m=\"3172200\">to</span> <span m=\"3172455\"\
  >just</span> <span m=\"3172710\">clarify</span> <span m=\"3173630\">a</span> <span\
  \ m=\"3173700\">piece</span> <span m=\"3173970\">of</span> <span m=\"3174060\">notation.</span>\
  \ <span m=\"3175090\">So</span> <span m=\"3175110\">when</span> <span m=\"3175290\"\
  >I</span> <span m=\"3175380\">say</span> <span m=\"3175680\">a</span> <span m=\"\
  3175770\">subgraph,</span> <span m=\"3179325\">so</span> <span m=\"3179820\">what</span>\
  \ <span m=\"3180000\">do</span> <span m=\"3180120\">I</span> <span m=\"3180210\"\
  >mean?</span> <span m=\"3182130\">So</span> <span m=\"3182340\">there</span> <span\
  \ m=\"3182580\">are</span> <span m=\"3182640\">several</span> <span m=\"3182970\"\
  >notions</span> <span m=\"3183450\">of</span> <span m=\"3184440\">different</span>\
  \ <span m=\"3184680\">kinds</span> <span m=\"3185010\">of</span> <span m=\"3185100\"\
  >subgraphs.</span> <span m=\"3186060\">And</span> <span m=\"3186240\">a</span> <span\
  \ m=\"3187110\">couple</span> <span m=\"3187410\">that</span> <span m=\"3187650\"\
  >come</span> <span m=\"3187950\">up</span> <span m=\"3188520\">somewhat</span> <span\
  \ m=\"3189240\">frequently,</span> <span m=\"3189720\">one</span> <span m=\"3189990\"\
  >is</span> <span m=\"3190140\">subgraph.</span> <span m=\"3191280\">And</span> <span\
  \ m=\"3191970\">then</span> <span m=\"3192180\">there's</span> <span m=\"3192330\"\
  >something</span> <span m=\"3192600\">called</span> <span m=\"3192930\">induced</span>\
  \ <span m=\"3193470\">subgraph.</span> <span m=\"3201200\">So it's</span> <span\
  \ m=\"3201680\">probably</span> <span m=\"3202010\">easiest</span> <span m=\"3202460\"\
  >if</span> <span m=\"3202610\">I</span> <span m=\"3202820\">just</span> <span m=\"\
  3203090\">show</span> <span m=\"3203360\">you</span> <span m=\"3203570\">an</span>\
  \ <span m=\"3203690\">example.</span></p><p><span m=\"3204700\">So</span> <span\
  \ m=\"3205370\">suppose</span> <span m=\"3205820\">my</span> <span m=\"3206030\"\
  >H</span> <span m=\"3206870\">is</span> <span m=\"3207200\">the</span> <span m=\"\
  3207410\">four</span> <span m=\"3207740\">cycle.</span> <span m=\"3210170\">So</span>\
  \ <span m=\"3210290\">in the</span> <span m=\"3210420\">example</span> <span m=\"\
  3210950\">of</span> <span m=\"3212390\">H</span> <span m=\"3212630\">being</span>\
  \ <span m=\"3212840\">a</span> <span m=\"3212900\">subgraph,</span> <span m=\"3214910\"\
  >suppose</span> <span m=\"3215510\">I</span> <span m=\"3215690\">have</span> <span\
  \ m=\"3216710\">this</span> <span m=\"3216950\">graph</span> <span m=\"3217250\"\
  >here.</span> <span m=\"3218900\">So</span> <span m=\"3219040\">H</span> <span m=\"\
  3219640\">is</span> <span m=\"3219820\">a</span> <span m=\"3219880\">subgraph</span>\
  \ <span m=\"3226750\">of</span> <span m=\"3226960\">this</span> <span m=\"3227170\"\
  >graph</span> <span m=\"3227470\">here</span> <span m=\"3228220\">in</span> <span\
  \ m=\"3228730\">many</span> <span m=\"3228970\">different</span> <span m=\"3229240\"\
  >ways,</span> <span m=\"3229770\">but</span> <span m=\"3229990\">in</span> <span\
  \ m=\"3230110\">particular,</span> <span m=\"3231210\">like</span> <span m=\"3231430\"\
  >that.</span> <span m=\"3233316\">But</span> <span m=\"3233730\">you</span> <span\
  \ m=\"3233820\">see</span> <span m=\"3234060\">there</span> <span m=\"3234220\"\
  >are</span> <span m=\"3234270\">some</span> <span m=\"3234540\">more</span> <span\
  \ m=\"3234780\">edges</span> <span m=\"3235860\">that</span> <span m=\"3236070\"\
  >are</span> <span m=\"3236190\">among</span> <span m=\"3236490\">the</span> <span\
  \ m=\"3236580\">vertices.</span> <span m=\"3237330\">But</span> <span m=\"3237480\"\
  >that's</span> <span m=\"3237660\">OK.</span> <span m=\"3237960\">So</span> <span\
  \ m=\"3238110\">subgraph</span> <span m=\"3238650\">only</span> <span m=\"3238890\"\
  >requires</span> <span m=\"3239520\">you</span> <span m=\"3239670\">to</span> <span\
  \ m=\"3240240\">have</span> <span m=\"3240420\">a</span> <span m=\"3240480\">subset</span>\
  \ <span m=\"3240990\">of</span> <span m=\"3241050\">vertices</span> <span m=\"3242070\"\
  >and</span> <span m=\"3242190\">a</span> <span m=\"3242250\">subset</span> <span\
  \ m=\"3242730\">of</span> <span m=\"3242850\">edges,</span> <span m=\"3244170\"\
  >whereas</span> <span m=\"3244890\">induced</span> <span m=\"3245460\">subgraphs--</span>\
  \ <span m=\"3247560\">this</span> <span m=\"3247740\">is</span> <span m=\"3247860\"\
  >not</span> <span m=\"3248190\">an</span> <span m=\"3248310\">example</span> <span\
  \ m=\"3248595\">of</span> <span m=\"3248880\">induced</span> <span m=\"3249300\"\
  >subgraph.</span></p><p><span m=\"3249745\">And</span> <span m=\"3250190\">so</span>\
  \ <span m=\"3250320\">induced</span> <span m=\"3250770\">subgraph</span> <span m=\"\
  3251760\">means</span> <span m=\"3256500\">that</span> <span m=\"3257340\">you</span>\
  \ <span m=\"3257670\">take</span> <span m=\"3259140\">this</span> <span m=\"3259230\"\
  >set</span> <span m=\"3259500\">of</span> <span m=\"3259560\">vertices</span> <span\
  \ m=\"3261920\">and</span> <span m=\"3262070\">you</span> <span m=\"3262190\">look</span>\
  \ <span m=\"3262430\">at</span> <span m=\"3263030\">all</span> <span m=\"3263270\"\
  >the</span> <span m=\"3263450\">edges</span> <span m=\"3264680\">in</span> <span\
  \ m=\"3264800\">the</span> <span m=\"3264860\">big</span> <span m=\"3265070\">graph</span>\
  \ <span m=\"3266090\">among</span> <span m=\"3266420\">your</span> <span m=\"3266600\"\
  >set</span> <span m=\"3266870\">of</span> <span m=\"3266960\">vertices.</span> <span\
  \ m=\"3269060\">So</span> <span m=\"3269080\">that's an</span> <span m=\"3269470\"\
  >induced</span> <span m=\"3269860\">subgraph.</span> <span m=\"3270430\">So</span>\
  \ <span m=\"3270650\">here,</span> <span m=\"3271260\">the</span> <span m=\"3271360\"\
  >four</span> <span m=\"3271630\">cycle</span> <span m=\"3272290\">is</span> <span\
  \ m=\"3272580\">an</span> <span m=\"3272720\">induced</span> <span m=\"3272920\"\
  >subgraph,</span> <span m=\"3274670\">but</span> <span m=\"3274880\">not</span>\
  \ <span m=\"3275720\">induced</span> <span m=\"3276230\">subgraph</span> <span m=\"\
  3276730\">over</span> <span m=\"3276930\">here.</span> <span m=\"3278730\">So</span>\
  \ <span m=\"3278870\">I</span> <span m=\"3278930\">just</span> <span m=\"3279080\"\
  >want</span> <span m=\"3279230\">to</span> <span m=\"3279290\">make</span> <span\
  \ m=\"3279440\">that</span> <span m=\"3279590\">distinction</span> <span m=\"3280070\"\
  >clear.</span> <span m=\"3280700\">And</span> <span m=\"3281420\">for</span> <span\
  \ m=\"3281600\">now,</span> <span m=\"3282530\">in</span> <span m=\"3282710\">this</span>\
  \ <span m=\"3282890\">chapter,</span> <span m=\"3283340\">we'll</span> <span m=\"\
  3283550\">only</span> <span m=\"3283880\">talk</span> <span m=\"3284210\">about</span>\
  \ <span m=\"3285280\">subgraphs--</span> <span m=\"3285890\">so</span> <span m=\"\
  3286330\">not</span> <span m=\"3286550\">induced,</span> <span m=\"3287210\">necessarily.</span></p><p><span\
  \ m=\"3291460\">All</span> <span m=\"3291520\">right.</span> <span m=\"3292000\"\
  >So</span> <span m=\"3292120\">let's</span> <span m=\"3292300\">recap</span> <span\
  \ m=\"3292960\">what</span> <span m=\"3293140\">happened</span> <span m=\"3293500\"\
  >for</span> <span m=\"3293950\">Tur\xE1n's</span> <span m=\"3294450\">theorem.</span>\
  \ <span m=\"3301090\">So</span> <span m=\"3301410\">Tur\xE1n's</span> <span m=\"\
  3301780\">theorem</span> <span m=\"3302560\">told</span> <span m=\"3302800\">us</span>\
  \ <span m=\"3303040\">that</span> <span m=\"3303220\">the</span> <span m=\"3303370\"\
  >extremal</span> <span m=\"3303910\">number</span> <span m=\"3305500\">of</span>\
  \ <span m=\"3309150\">these</span> <span m=\"3309900\">cliques,</span> <span m=\"\
  3310770\">well,</span> <span m=\"3310860\">we</span> <span m=\"3311010\">know</span>\
  \ <span m=\"3311370\">very</span> <span m=\"3311610\">precisely</span> <span m=\"\
  3313020\">to</span> <span m=\"3313140\">be</span> <span m=\"3317140\">the</span>\
  \ <span m=\"3317290\">number</span> <span m=\"3317620\">of</span> <span m=\"3317770\"\
  >edges</span> <span m=\"3318370\">in</span> <span m=\"3318610\">the</span> <span\
  \ m=\"3318730\">Tur\xE1n</span> <span m=\"3319090\">graph.</span> <span m=\"3321110\"\
  >And</span> <span m=\"3321920\">in</span> <span m=\"3322040\">particular,</span>\
  \ <span m=\"3322770\">we</span> <span m=\"3322850\">saw</span> <span m=\"3323150\"\
  >from</span> <span m=\"3323360\">the</span> <span m=\"3323450\">last</span> <span\
  \ m=\"3323730\">proof,</span> <span m=\"3324010\">but</span> <span m=\"3324140\"\
  >also,</span> <span m=\"3324440\">similarly,</span> <span m=\"3324950\">if</span>\
  \ <span m=\"3325040\">you</span> <span m=\"3325130\">just</span> <span m=\"3325280\"\
  >do</span> <span m=\"3325400\">a</span> <span m=\"3325460\">calculation,</span>\
  \ <span m=\"3326630\">that</span> <span m=\"3327530\">it</span> <span m=\"3327710\"\
  >is</span> <span m=\"3328800\">at</span> <span m=\"3329000\">most</span> <span m=\"\
  3329690\">this</span> <span m=\"3329870\">quantity</span> <span m=\"3330470\">over</span>\
  \ <span m=\"3330710\">here.</span> <span m=\"3332650\">And</span> <span m=\"3332810\"\
  >it's</span> <span m=\"3333170\">basically</span> <span m=\"3334040\">that</span>\
  \ <span m=\"3334250\">quantity.</span></p><p><span m=\"3336860\">So</span> <span\
  \ m=\"3337580\">the</span> <span m=\"3337730\">number</span> <span m=\"3338240\"\
  >of</span> <span m=\"3339710\">edges</span> <span m=\"3340190\">in</span> <span\
  \ m=\"3340340\">this</span> <span m=\"3340460\">Tur\xE1n</span> <span m=\"3340830\"\
  >graph</span> <span m=\"3341750\">is</span> <span m=\"3341960\">asymptotically</span>\
  \ <span m=\"3345410\">that</span> <span m=\"3345730\">quantity</span> <span m=\"\
  3346280\">up</span> <span m=\"3346460\">to</span> <span m=\"3347300\">a</span> <span\
  \ m=\"3347420\">lower-order</span> <span m=\"3348800\">error;</span> <span m=\"\
  3350000\">if</span> <span m=\"3350180\">you</span> <span m=\"3350300\">like</span>\
  \ <span m=\"3350600\">n</span> <span m=\"3350900\">go</span> <span m=\"3351140\"\
  >to</span> <span m=\"3351290\">infinity,</span> <span m=\"3352510\">r</span> <span\
  \ m=\"3352910\">fixed.</span> <span m=\"3356050\">And</span> <span m=\"3356220\"\
  >the</span> <span m=\"3356280\">basic</span> <span m=\"3356640\">question</span>\
  \ <span m=\"3356940\">is,</span> <span m=\"3357030\">what</span> <span m=\"3357210\"\
  >about</span> <span m=\"3357420\">general</span> <span m=\"3357870\">H?</span> <span\
  \ m=\"3358570\">And</span> <span m=\"3358940\">so</span> <span m=\"3359100\">if</span>\
  \ <span m=\"3359220\">I</span> <span m=\"3359310\">give</span> <span m=\"3359550\"\
  >you</span> <span m=\"3360480\">some</span> <span m=\"3361920\">arbitrary</span>\
  \ <span m=\"3362460\">graph</span> <span m=\"3363870\">H,</span> <span m=\"3365130\"\
  >what</span> <span m=\"3365310\">can</span> <span m=\"3365460\">you</span> <span\
  \ m=\"3365580\">tell</span> <span m=\"3365820\">me</span> <span m=\"3366510\">about</span>\
  \ <span m=\"3367020\">the</span> <span m=\"3367140\">maximum</span> <span m=\"3367710\"\
  >number</span> <span m=\"3367950\">of</span> <span m=\"3368040\">edges</span> <span\
  \ m=\"3368430\">in</span> <span m=\"3368520\">the</span> <span m=\"3368610\">graph</span>\
  \ <span m=\"3369450\">forbidding</span> <span m=\"3370290\">this</span> <span m=\"\
  3370530\">H</span> <span m=\"3371520\">as</span> <span m=\"3372260\">a</span> <span\
  \ m=\"3372300\">subgraph?</span></p><p><span m=\"3374930\">And</span> <span m=\"\
  3375180\">it</span> <span m=\"3375240\">turns</span> <span m=\"3375450\">out,</span>\
  \ <span m=\"3375810\">for</span> <span m=\"3376260\">most</span> <span m=\"3377000\"\
  >H's,</span> <span m=\"3377370\">we</span> <span m=\"3377520\">have</span> <span\
  \ m=\"3377670\">a</span> <span m=\"3377730\">pretty</span> <span m=\"3378000\">good</span>\
  \ <span m=\"3378240\">understanding,</span> <span m=\"3379180\">and</span> <span\
  \ m=\"3379280\">perhaps</span> <span m=\"3379500\">quite</span> <span m=\"3379770\"\
  >surprisingly,</span> <span m=\"3380470\">because</span> <span m=\"3380640\">you</span>\
  \ <span m=\"3380700\">can</span> <span m=\"3380850\">imagine</span> <span m=\"3381210\"\
  >this</span> <span m=\"3381330\">problem</span> <span m=\"3381870\">looks</span>\
  \ <span m=\"3382080\">like</span> <span m=\"3382270\">it</span> <span m=\"3382380\"\
  >might</span> <span m=\"3382530\">get</span> <span m=\"3382680\">quite</span> <span\
  \ m=\"3382980\">complicated.</span> <span m=\"3384030\">All</span> <span m=\"3384150\"\
  >the</span> <span m=\"3384240\">proofs</span> <span m=\"3384540\">that</span> <span\
  \ m=\"3384690\">we've</span> <span m=\"3384870\">done</span> <span m=\"3385330\"\
  >are</span> <span m=\"3385460\">very</span> <span m=\"3385680\">specific</span>\
  \ <span m=\"3386340\">to</span> <span m=\"3386520\">cliques.</span> <span m=\"3387990\"\
  >But</span> <span m=\"3388200\">it</span> <span m=\"3388260\">turns</span> <span\
  \ m=\"3388560\">out</span> <span m=\"3389310\">that</span> <span m=\"3389430\">we</span>\
  \ <span m=\"3389820\">already</span> <span m=\"3390180\">understand</span> <span\
  \ m=\"3390840\">a</span> <span m=\"3390900\">lot.</span> <span m=\"3391590\">And</span>\
  \ <span m=\"3391980\">the</span> <span m=\"3392130\">critical</span> <span m=\"\
  3392670\">parameter</span> <span m=\"3393300\">that</span> <span m=\"3393480\">governs</span>\
  \ <span m=\"3394290\">how</span> <span m=\"3394980\">this</span> <span m=\"3395190\"\
  >quantity</span> <span m=\"3395610\">behaves</span> <span m=\"3396420\">is</span>\
  \ <span m=\"3396570\">the</span> <span m=\"3396660\">chromatic</span> <span m=\"\
  3397200\">number</span> <span m=\"3397530\">of</span> <span m=\"3397680\">H.</span></p><p><span\
  \ m=\"3399640\">So</span> <span m=\"3399990\">if</span> <span m=\"3400110\">you</span>\
  \ <span m=\"3400170\">call</span> <span m=\"3400380\">me</span> <span m=\"3400500\"\
  >the</span> <span m=\"3400590\">chromatic</span> <span m=\"3401010\">number</span>\
  \ <span m=\"3401250\">of</span> <span m=\"3401340\">H,</span> <span m=\"3401850\"\
  >I</span> <span m=\"3401910\">can</span> <span m=\"3402060\">already</span> <span\
  \ m=\"3402450\">tell</span> <span m=\"3402720\">you</span> <span m=\"3403080\">quite</span>\
  \ <span m=\"3403440\">a</span> <span m=\"3403500\">lot.</span> <span m=\"3404520\"\
  >So</span> <span m=\"3404640\">just</span> <span m=\"3404850\">to</span> <span m=\"\
  3404940\">remind</span> <span m=\"3405300\">you,</span> <span m=\"3405490\">the</span>\
  \ <span m=\"3405630\">chromatic</span> <span m=\"3406140\">number</span> <span m=\"\
  3406890\">of</span> <span m=\"3407160\">a</span> <span m=\"3407250\">graph</span>\
  \ <span m=\"3407910\">is</span> <span m=\"3408120\">the</span> <span m=\"3408510\"\
  >minimum</span> <span m=\"3408960\">number</span> <span m=\"3409320\">of</span>\
  \ <span m=\"3409860\">colors</span> <span m=\"3410400\">you</span> <span m=\"3410520\"\
  >need</span> <span m=\"3411150\">to</span> <span m=\"3411330\">properly</span> <span\
  \ m=\"3412170\">color</span> <span m=\"3412890\">this</span> <span m=\"3413040\"\
  >graph.</span> <span m=\"3414390\">Chromatic</span> <span m=\"3415350\">number</span>\
  \ <span m=\"3417394\">of</span> <span m=\"3417810\">H,</span> <span m=\"3420440\"\
  >denoted</span> <span m=\"3422380\">chi of</span> <span m=\"3422770\">H,</span>\
  \ <span m=\"3424060\">is</span> <span m=\"3424930\">the</span> <span m=\"3425980\"\
  >minimum</span> <span m=\"3427360\">number</span> <span m=\"3428080\">of</span>\
  \ <span m=\"3428230\">colors</span> <span m=\"3431010\">needed</span> <span m=\"\
  3433970\">to</span> <span m=\"3435470\">color</span> <span m=\"3436890\">the</span>\
  \ <span m=\"3437370\">vertices</span> <span m=\"3438520\">of</span> <span m=\"3438770\"\
  >H</span> <span m=\"3441060\">so</span> <span m=\"3441270\">that</span> <span m=\"\
  3443670\">no</span> <span m=\"3443880\">two</span> <span m=\"3446630\">adjacent</span>\
  \ <span m=\"3447110\">vertices</span> <span m=\"3449060\">have</span> <span m=\"\
  3449270\">the</span> <span m=\"3449360\">same</span> <span m=\"3449630\">color.</span></p><p><span\
  \ m=\"3456710\">So</span> <span m=\"3456790\">for</span> <span m=\"3456940\">instance,</span>\
  \ <span m=\"3458480\">if</span> <span m=\"3458650\">I</span> <span m=\"3458770\"\
  >give</span> <span m=\"3458950\">you</span> <span m=\"3459130\">a</span> <span m=\"\
  3459190\">clique</span> <span m=\"3461560\">of</span> <span m=\"3462372\">r</span>\
  \ <span m=\"3462720\">plus</span> <span m=\"3462990\">1</span> <span m=\"3463170\"\
  >vertices,</span> <span m=\"3464730\">so</span> <span m=\"3464970\">all</span> <span\
  \ m=\"3465150\">the</span> <span m=\"3465240\">vertices</span> <span m=\"3465690\"\
  >must</span> <span m=\"3465900\">receive</span> <span m=\"3466260\">different</span>\
  \ <span m=\"3466560\">colors,</span> <span m=\"3466920\">because</span> <span m=\"\
  3467190\">every</span> <span m=\"3467400\">pair</span> <span m=\"3467610\">of</span>\
  \ <span m=\"3467670\">vertices</span> <span m=\"3468120\">is</span> <span m=\"3468210\"\
  >adjacent--</span> <span m=\"3469090\">so</span> <span m=\"3469230\">the</span>\
  \ <span m=\"3469515\">chromatic</span> <span m=\"3469800\">number is</span> <span\
  \ m=\"3470280\">r</span> <span m=\"3470400\">plus</span> <span m=\"3470810\">1.</span>\
  \ <span m=\"3472520\">The</span> <span m=\"3473010\">chromatic</span> <span m=\"\
  3473460\">number</span> <span m=\"3473770\">of</span> <span m=\"3474570\">the</span>\
  \ <span m=\"3474800\">Tur\xE1n</span> <span m=\"3475200\">graph</span> <span m=\"\
  3480009\">is</span> <span m=\"3480500\">what?</span> <span m=\"3485420\">It's</span>\
  \ <span m=\"3485580\">r.</span> <span m=\"3485790\">So</span> <span m=\"3486200\"\
  >the</span> <span m=\"3486390\">chromatic</span> <span m=\"3486810\">number</span>\
  \ <span m=\"3487090\">of the</span> <span m=\"3487200\">Tur\xE1n</span> <span m=\"\
  3487470\">graph</span> <span m=\"3487710\">is</span> <span m=\"3487860\">r.</span>\
  \ <span m=\"3489030\">I</span> <span m=\"3489120\">can</span> <span m=\"3489300\"\
  >color</span> <span m=\"3490170\">each</span> <span m=\"3490620\">part</span> <span\
  \ m=\"3491130\">in</span> <span m=\"3491220\">this</span> <span m=\"3491370\">complete</span>\
  \ <span m=\"3491700\">bipartite</span> <span m=\"3492130\">graph</span> <span m=\"\
  3492720\">using</span> <span m=\"3493020\">a</span> <span m=\"3493080\">different</span>\
  \ <span m=\"3493380\">color.</span> <span m=\"3495120\">And</span> <span m=\"3495300\"\
  >that's</span> <span m=\"3496470\">the</span> <span m=\"3496560\">best</span> <span\
  \ m=\"3496830\">I</span> <span m=\"3496920\">can</span> <span m=\"3497100\">do.</span></p><p><span\
  \ m=\"3501470\">Now,</span> <span m=\"3502460\">if</span> <span m=\"3502670\">I</span>\
  \ <span m=\"3503330\">have</span> <span m=\"3504020\">one</span> <span m=\"3504290\"\
  >graph</span> <span m=\"3504740\">being</span> <span m=\"3505010\">a</span> <span\
  \ m=\"3505070\">subgraph</span> <span m=\"3505970\">of</span> <span m=\"3506990\"\
  >another</span> <span m=\"3507260\">graph,</span> <span m=\"3508070\">what</span>\
  \ <span m=\"3508220\">can</span> <span m=\"3508340\">you</span> <span m=\"3508460\"\
  >tell</span> <span m=\"3508670\">me</span> <span m=\"3508850\">about</span> <span\
  \ m=\"3509060\">the</span> <span m=\"3509150\">relationships</span> <span m=\"3509960\"\
  >between</span> <span m=\"3510380\">their</span> <span m=\"3510560\">chromatic</span>\
  \ <span m=\"3511010\">numbers?</span> <span m=\"3518945\">So</span> <span m=\"3519444\"\
  >if</span> <span m=\"3521440\">H</span> <span m=\"3522430\">is</span> <span m=\"\
  3522550\">a</span> <span m=\"3522610\">subgraph</span> <span m=\"3523210\">of</span>\
  \ <span m=\"3523330\">G,</span> <span m=\"3526970\">so</span> <span m=\"3527130\"\
  >what</span> <span m=\"3527250\">can</span> <span m=\"3527370\">you</span> <span\
  \ m=\"3527430\">tell</span> <span m=\"3527610\">me</span> <span m=\"3527730\">about</span>\
  \ <span m=\"3527970\">relationship</span> <span m=\"3528510\">between</span> <span\
  \ m=\"3528810\">their</span> <span m=\"3528960\">chromatic</span> <span m=\"3529410\"\
  >numbers?</span></p><p><span m=\"3532752\">AUDIENCE:</span> <span m=\"3532873\"\
  >Chi</span> <span m=\"3532994\">of</span> <span m=\"3533115\">H</span> <span m=\"\
  3533239\">is less than</span> <span m=\"3533726\">the other</span> <span m=\"3534213\"\
  >chi.</span></p><p><span m=\"3534700\">YUFEI ZHAO:</span> <span m=\"3534770\">So</span>\
  \ <span m=\"3534840\">OK.</span> <span m=\"3535070\">You're</span> <span m=\"3535510\"\
  >telling</span> <span m=\"3535810\">me</span> <span m=\"3535930\">that</span> <span\
  \ m=\"3536170\">the chi</span> <span m=\"3536590\">of H</span> <span m=\"3537670\"\
  >is</span> <span m=\"3538450\">at</span> <span m=\"3538650\">most</span> <span m=\"\
  3540110\">chi</span> <span m=\"3540370\">of</span> <span m=\"3540460\">G.</span>\
  \ <span m=\"3540790\">And why</span> <span m=\"3540940\">is</span> <span m=\"3541150\"\
  >that?</span></p><p><span m=\"3543050\">AUDIENCE:</span> <span m=\"3543210\">Because</span>\
  \ <span m=\"3543370\">if</span> <span m=\"3543590\">G</span> <span m=\"3544010\"\
  >can be</span> <span m=\"3544230\">colored</span> <span m=\"3544688\">with</span>\
  \ <span m=\"3545604\">a certain</span> <span m=\"3546062\">number of colors,</span>\
  \ <span m=\"3546520\">then</span> <span m=\"3546978\">that</span> <span m=\"3547436\"\
  >also</span> <span m=\"3547894\">has</span> <span m=\"3548352\">[INAUDIBLE].</span></p><p><span\
  \ m=\"3550503\">YUFEI ZHAO:</span> <span m=\"3550744\">Great.</span> <span m=\"\
  3551470\">Whatever</span> <span m=\"3551830\">coloring</span> <span m=\"3552490\"\
  >you</span> <span m=\"3552640\">do</span> <span m=\"3552910\">for</span> <span m=\"\
  3553120\">G,</span> <span m=\"3553450\">you</span> <span m=\"3553820\">use</span>\
  \ <span m=\"3554110\">the</span> <span m=\"3554200\">same</span> <span m=\"3554470\"\
  >coloring,</span> <span m=\"3555140\">and</span> <span m=\"3555240\">that's</span>\
  \ <span m=\"3555310\">a</span> <span m=\"3555340\">proper</span> <span m=\"3555670\"\
  >coloring</span> <span m=\"3556030\">for</span> <span m=\"3556210\">H</span> <span\
  \ m=\"3556480\">as</span> <span m=\"3556630\">well.</span> <span m=\"3557760\">So</span>\
  \ <span m=\"3557800\">the</span> <span m=\"3557920\">chromatic</span> <span m=\"\
  3558340\">number</span> <span m=\"3558580\">of</span> <span m=\"3558700\">H</span>\
  \ <span m=\"3559360\">might</span> <span m=\"3559560\">be</span> <span m=\"3559690\"\
  >smaller,</span> <span m=\"3560240\">but</span> <span m=\"3560260\">certainly</span>\
  \ <span m=\"3560620\">cannot</span> <span m=\"3560980\">be</span> <span m=\"3561100\"\
  >bigger</span> <span m=\"3561400\">than</span> <span m=\"3561550\">that</span> <span\
  \ m=\"3561730\">of</span> <span m=\"3561850\">G.</span> <span m=\"3563380\">So</span>\
  \ <span m=\"3563590\">in</span> <span m=\"3563710\">particular,</span> <span m=\"\
  3564940\">if</span> <span m=\"3565150\">you</span> <span m=\"3565300\">have</span>\
  \ <span m=\"3565540\">a</span> <span m=\"3565600\">graph</span> <span m=\"3570260\"\
  >H</span> <span m=\"3571580\">with</span> <span m=\"3572390\">chromatic</span> <span\
  \ m=\"3572900\">number</span> <span m=\"3574180\">r</span> <span m=\"3574580\">plus</span>\
  \ <span m=\"3574910\">1,</span> <span m=\"3576810\">then</span> <span m=\"3578960\"\
  >this</span> <span m=\"3579210\">Tur\xE1n</span> <span m=\"3579450\">on</span> <span\
  \ m=\"3579570\">graph</span> <span m=\"3581260\">is</span> <span m=\"3582210\">always</span>\
  \ <span m=\"3584280\">H-free.</span> <span m=\"3587010\">So</span> <span m=\"3587130\"\
  >if</span> <span m=\"3587610\">H</span> <span m=\"3587850\">requires</span> <span\
  \ m=\"3588300\">four</span> <span m=\"3588510\">colors,</span> <span m=\"3589200\"\
  >it</span> <span m=\"3589290\">cannot</span> <span m=\"3589620\">be</span> <span\
  \ m=\"3589770\">embedded</span> <span m=\"3590310\">into</span> <span m=\"3590760\"\
  >the</span> <span m=\"3590880\">complete</span> <span m=\"3591210\">multipartite</span>\
  \ <span m=\"3591930\">graph</span> <span m=\"3592210\">of</span> <span m=\"3592320\"\
  >three</span> <span m=\"3592530\">parts.</span></p><p><span m=\"3594260\">So</span>\
  \ <span m=\"3595030\">the</span> <span m=\"3595150\">Tur\xE1n</span> <span m=\"\
  3595410\">graph</span> <span m=\"3595840\">is</span> <span m=\"3596080\">also</span>\
  \ <span m=\"3596920\">an</span> <span m=\"3597040\">example</span> <span m=\"3597490\"\
  >of</span> <span m=\"3597970\">an</span> <span m=\"3598210\">H-free</span> <span\
  \ m=\"3598570\">graph</span> <span m=\"3599170\">with</span> <span m=\"3599380\"\
  >lots</span> <span m=\"3599650\">of</span> <span m=\"3599770\">edges.</span> <span\
  \ m=\"3601160\">And</span> <span m=\"3601300\">this</span> <span m=\"3601450\">tells</span>\
  \ <span m=\"3601750\">us</span> <span m=\"3602710\">that</span> <span m=\"3602920\"\
  >the</span> <span m=\"3603070\">extremal</span> <span m=\"3603610\">number</span>\
  \ <span m=\"3604090\">of</span> <span m=\"3605170\">H</span> <span m=\"3606660\"\
  >is</span> <span m=\"3607380\">at</span> <span m=\"3607500\">least</span> <span\
  \ m=\"3608800\">that</span> <span m=\"3609030\">of</span> <span m=\"3610890\">this</span>\
  \ <span m=\"3611010\">Tur\xE1n</span> <span m=\"3611310\">number,</span> <span m=\"\
  3611600\">where</span> <span m=\"3612306\">r</span> <span m=\"3612660\">is</span>\
  \ <span m=\"3613270\">defined</span> <span m=\"3615430\">as</span> <span m=\"3615600\"\
  >the</span> <span m=\"3615690\">chromatic</span> <span m=\"3616080\">number</span>\
  \ <span m=\"3616530\">minus</span> <span m=\"3616900\">1.</span> <span m=\"3618316\"\
  >So</span> <span m=\"3618790\">that's</span> <span m=\"3618970\">some</span> <span\
  \ m=\"3619450\">lower-bound</span> <span m=\"3619900\">construction.</span></p><p><span\
  \ m=\"3623128\">So</span> <span m=\"3623580\">as</span> <span m=\"3623710\">we</span>\
  \ <span m=\"3623830\">saw</span> <span m=\"3624040\">earlier,</span> <span m=\"\
  3624570\">and</span> <span m=\"3624700\">we</span> <span m=\"3624820\">know</span>\
  \ <span m=\"3625000\">what</span> <span m=\"3625180\">the</span> <span m=\"3625270\"\
  >asymptotic</span> <span m=\"3626200\">is</span> <span m=\"3626350\">like</span>\
  \ <span m=\"3626710\">for</span> <span m=\"3627910\">the</span> <span m=\"3628330\"\
  >number</span> <span m=\"3628570\">of</span> <span m=\"3628690\">edges,</span> <span\
  \ m=\"3629170\">this n</span> <span m=\"3629470\">goes</span> <span m=\"3629680\"\
  >to</span> <span m=\"3629800\">infinity.</span> <span m=\"3631769\">Namely,</span>\
  \ <span m=\"3634240\">it's</span> <span m=\"3634420\">like</span> <span m=\"3634600\"\
  >that.</span> <span m=\"3638071\">And</span> <span m=\"3638520\">now</span> <span\
  \ m=\"3638670\">the</span> <span m=\"3638760\">question</span> <span m=\"3639150\"\
  >is,</span> <span m=\"3639630\">is</span> <span m=\"3639930\">this</span> <span\
  \ m=\"3640260\">the</span> <span m=\"3640410\">right</span> <span m=\"3640770\"\
  >answer?</span> <span m=\"3641340\">Is</span> <span m=\"3641510\">it</span> <span\
  \ m=\"3641580\">possible</span> <span m=\"3642390\">that</span> <span m=\"3642750\"\
  >we</span> <span m=\"3642930\">completely</span> <span m=\"3643410\">missed</span>\
  \ <span m=\"3643770\">some</span> <span m=\"3644010\">construction</span> <span\
  \ m=\"3644910\">that</span> <span m=\"3645060\">might</span> <span m=\"3645270\"\
  >produce</span> <span m=\"3645780\">a</span> <span m=\"3645840\">lot</span> <span\
  \ m=\"3646110\">more</span> <span m=\"3646410\">edges?</span></p><p><span m=\"3648680\"\
  >And</span> <span m=\"3648810\">it</span> <span m=\"3648900\">turns</span> <span\
  \ m=\"3649140\">out--</span> <span m=\"3649710\">and</span> <span m=\"3650100\"\
  >I</span> <span m=\"3650280\">think</span> <span m=\"3650460\">this</span> <span\
  \ m=\"3650820\">should</span> <span m=\"3651090\">be</span> <span m=\"3651210\"\
  >somewhat</span> <span m=\"3651540\">surprising.</span> <span m=\"3652080\">Because</span>\
  \ <span m=\"3652320\">so</span> <span m=\"3652710\">far,</span> <span m=\"3652920\"\
  >I</span> <span m=\"3653280\">feel</span> <span m=\"3653430\">like</span> <span\
  \ m=\"3653610\">I</span> <span m=\"3653670\">haven't</span> <span m=\"3654090\"\
  >told</span> <span m=\"3654300\">you</span> <span m=\"3654420\">anything</span>\
  \ <span m=\"3655230\">all</span> <span m=\"3656360\">that</span> <span m=\"3656640\"\
  >surprising</span> <span m=\"3657300\">yet.</span> <span m=\"3658950\">This</span>\
  \ <span m=\"3659190\">seems</span> <span m=\"3659460\">like</span> <span m=\"3659610\"\
  >a</span> <span m=\"3659670\">fairly</span> <span m=\"3660540\">mysterious</span>\
  \ <span m=\"3660840\">problem.</span> <span m=\"3661590\">But</span> <span m=\"\
  3661800\">it</span> <span m=\"3661860\">turns</span> <span m=\"3662160\">out</span>\
  \ <span m=\"3662640\">that</span> <span m=\"3662820\">this</span> <span m=\"3663390\"\
  >is</span> <span m=\"3663600\">more</span> <span m=\"3663810\">or</span> <span m=\"\
  3663840\">less</span> <span m=\"3664050\">the</span> <span m=\"3664140\">right</span>\
  \ <span m=\"3664350\">answer.</span> <span m=\"3666210\">So</span> <span m=\"3666330\"\
  >you</span> <span m=\"3666480\">cannot</span> <span m=\"3667020\">do</span> <span\
  \ m=\"3667920\">much</span> <span m=\"3668190\">better</span> <span m=\"3668970\"\
  >than</span> <span m=\"3669450\">the</span> <span m=\"3669560\">Tur\xE1n</span>\
  \ <span m=\"3669870\">graph.</span></p><p><span m=\"3671040\">And</span> <span m=\"\
  3672942\">there's</span> <span m=\"3673350\">the</span> <span m=\"3673470\">theorem</span>\
  \ <span m=\"3674376\">of</span> <span m=\"3675350\">Erdos,</span> <span m=\"3676670\"\
  >Stone,</span> <span m=\"3679320\">and</span> <span m=\"3679590\">Simonovits</span>\
  \ <span m=\"3680090\">rich</span> <span m=\"3690180\">that</span> <span m=\"3690900\"\
  >for</span> <span m=\"3691200\">every</span> <span m=\"3692360\">graph</span> <span\
  \ m=\"3694910\">H--</span> <span m=\"3696240\">so</span> <span m=\"3696400\">if</span>\
  \ <span m=\"3696550\">I</span> <span m=\"3696640\">fixed</span> <span m=\"3697430\"\
  >H,</span> <span m=\"3698430\">then</span> <span m=\"3700400\">the</span> <span\
  \ m=\"3700750\">limit</span> <span m=\"3702140\">as</span> <span m=\"3702640\">n</span>\
  \ <span m=\"3702890\">goes</span> <span m=\"3703100\">to</span> <span m=\"3703220\"\
  >infinity</span> <span m=\"3706620\">of</span> <span m=\"3706840\">the</span> <span\
  \ m=\"3706940\">extremal</span> <span m=\"3707310\">number</span> <span m=\"3709340\"\
  >is</span> <span m=\"3709470\">a</span> <span m=\"3709530\">fraction</span> <span\
  \ m=\"3710040\">of</span> <span m=\"3710160\">total</span> <span m=\"3710490\">number</span>\
  \ <span m=\"3710790\">of</span> <span m=\"3710880\">pairs.</span> <span m=\"3712380\"\
  >So</span> <span m=\"3712610\">here,</span> <span m=\"3712980\">this</span> <span\
  \ m=\"3713250\">is</span> <span m=\"3713400\">the</span> <span m=\"3713850\">edge</span>\
  \ <span m=\"3714090\">density.</span> <span m=\"3715270\">So</span> <span m=\"3716100\"\
  >this</span> <span m=\"3716280\">quantity</span> <span m=\"3716700\">here</span>\
  \ <span m=\"3717420\">is</span> <span m=\"3717660\">equal</span> <span m=\"3718530\"\
  >to</span> <span m=\"3720130\">1</span> <span m=\"3720760\">minus</span> <span m=\"\
  3722320\">chi of</span> <span m=\"3722670\">H.</span> <span m=\"3724590\">So 1</span>\
  \ <span m=\"3724830\">minus</span> <span m=\"3725190\">1</span> <span m=\"3725400\"\
  >over</span> <span m=\"3725580\">chi</span> <span m=\"3725840\">of</span> <span\
  \ m=\"3726030\">H</span> <span m=\"3726360\">minus</span> <span m=\"3726770\">1.</span></p><p><span\
  \ m=\"3728230\">So</span> <span m=\"3728740\">the</span> <span m=\"3729130\">chromatic</span>\
  \ <span m=\"3729610\">number,</span> <span m=\"3730690\">in</span> <span m=\"3730810\"\
  >some</span> <span m=\"3731020\">sense,</span> <span m=\"3731410\">completely</span>\
  \ <span m=\"3731920\">determines</span> <span m=\"3733790\">how</span> <span m=\"\
  3734090\">big</span> <span m=\"3735290\">the</span> <span m=\"3735410\">extremal</span>\
  \ <span m=\"3735860\">number</span> <span m=\"3736250\">should</span> <span m=\"\
  3736460\">be.</span> <span m=\"3738530\">And</span> <span m=\"3739400\">you</span>\
  \ <span m=\"3739490\">see</span> <span m=\"3739640\">that</span> <span m=\"3740420\"\
  >so</span> <span m=\"3740660\">far</span> <span m=\"3740930\">everything</span>\
  \ <span m=\"3741260\">we've</span> <span m=\"3741440\">proved,</span> <span m=\"\
  3742010\">Tur\xE1n's</span> <span m=\"3742330\">theorem,</span> <span m=\"3742630\"\
  >Mantel's</span> <span m=\"3743150\">theorem</span> <span m=\"3743660\">agree</span>\
  \ <span m=\"3743990\">with</span> <span m=\"3744200\">this</span> <span m=\"3744740\"\
  >formula</span> <span m=\"3745280\">here.</span> <span m=\"3745640\">But</span>\
  \ <span m=\"3746120\">if</span> <span m=\"3746240\">I</span> <span m=\"3746330\"\
  >give</span> <span m=\"3746540\">you</span> <span m=\"3746720\">some</span> <span\
  \ m=\"3747650\">H,</span> <span m=\"3748640\">maybe</span> <span m=\"3748880\">quite</span>\
  \ <span m=\"3749180\">complicated,</span> <span m=\"3750160\">and</span> <span m=\"\
  3750290\">those</span> <span m=\"3750500\">previous</span> <span m=\"3750890\">proofs</span>\
  \ <span m=\"3751250\">don't</span> <span m=\"3751970\">work,</span> <span m=\"3752560\"\
  >well,</span> <span m=\"3752720\">still</span> <span m=\"3753140\">you know</span>\
  \ <span m=\"3753590\">the</span> <span m=\"3754040\">first</span> <span m=\"3754430\"\
  >order</span> <span m=\"3755110\">asymptotics.</span> <span m=\"3757550\">But</span>\
  \ <span m=\"3757670\">there's</span> <span m=\"3757820\">still</span> <span m=\"\
  3758000\">more</span> <span m=\"3758180\">to</span> <span m=\"3758270\">say.</span>\
  \ <span m=\"3758660\">But</span> <span m=\"3758750\">first,</span> <span m=\"3759020\"\
  >let</span> <span m=\"3759140\">me</span> <span m=\"3759620\">just</span> <span\
  \ m=\"3760010\">run</span> <span m=\"3760220\">through</span> <span m=\"3760370\"\
  >some</span> <span m=\"3760550\">examples</span> <span m=\"3761030\">for a</span>\
  \ <span m=\"3761150\">sanity</span> <span m=\"3761540\">check.</span></p><p><span\
  \ m=\"3762370\">So</span> <span m=\"3762530\">if</span> <span m=\"3762770\">H</span>\
  \ <span m=\"3764240\">is</span> <span m=\"3765215\">a</span> <span m=\"3765710\"\
  >triangle--</span> <span m=\"3772702\">so</span> <span m=\"3773196\">if</span> <span\
  \ m=\"3773700\">H,</span> <span m=\"3773970\">the</span> <span m=\"3774240\">chromatic</span>\
  \ <span m=\"3774660\">number,</span> <span m=\"3775710\">and</span> <span m=\"3776970\"\
  >this</span> <span m=\"3777150\">limit--</span> <span m=\"3779340\">so</span> <span\
  \ m=\"3779430\">if</span> <span m=\"3779610\">H</span> <span m=\"3779970\">is</span>\
  \ <span m=\"3780150\">the</span> <span m=\"3780210\">triangle,</span> <span m=\"\
  3780870\">chromatic</span> <span m=\"3781310\">number</span> <span m=\"3781590\"\
  >is</span> <span m=\"3781730\">3.</span> <span m=\"3783550\">So then</span> <span\
  \ m=\"3783970\">this</span> <span m=\"3784180\">limit</span> <span m=\"3784470\"\
  >is</span> <span m=\"3784690\">1/2.</span> <span m=\"3786230\">And</span> <span\
  \ m=\"3786490\">that's</span> <span m=\"3786760\">indeed</span> <span m=\"3787030\"\
  >the</span> <span m=\"3787090\">case.</span> <span m=\"3787750\">So</span> <span\
  \ m=\"3787840\">that's</span> <span m=\"3788050\">what</span> <span m=\"3788200\"\
  >we</span> <span m=\"3788320\">did</span> <span m=\"3788560\">with</span> <span\
  \ m=\"3788770\">Mantel's</span> <span m=\"3789220\">theorem.</span></p><p><span\
  \ m=\"3790240\">If</span> <span m=\"3790390\">H</span> <span m=\"3790720\">is</span>\
  \ <span m=\"3790900\">a</span> <span m=\"3790960\">clique</span> <span m=\"3791260\"\
  >of</span> <span m=\"3791380\">four</span> <span m=\"3791620\">vertices,</span>\
  \ <span m=\"3792850\">then</span> <span m=\"3793210\">the</span> <span m=\"3793300\"\
  >chromatic</span> <span m=\"3793750\">number</span> <span m=\"3794590\">is</span>\
  \ <span m=\"3795290\">4.</span> <span m=\"3796510\">And</span> <span m=\"3796810\"\
  >the</span> <span m=\"3796960\">answer</span> <span m=\"3797350\">is</span> <span\
  \ m=\"3799360\">2/3.</span> <span m=\"3800670\">And</span> <span m=\"3800800\">also,</span>\
  \ <span m=\"3801040\">that</span> <span m=\"3801340\">agrees</span> <span m=\"3801700\"\
  >with</span> <span m=\"3802660\">Tur\xE1n's</span> <span m=\"3803050\">theorem.</span>\
  \ <span m=\"3804120\">It agrees</span> <span m=\"3804370\">with</span> <span m=\"\
  3804500\">Tur\xE1n's</span> <span m=\"3804870\">theorem.</span></p><p><span m=\"\
  3805630\">But</span> <span m=\"3805930\">I</span> <span m=\"3806020\">can</span>\
  \ <span m=\"3806200\">give</span> <span m=\"3806530\">you</span> <span m=\"3806680\"\
  >some</span> <span m=\"3807820\">fairly</span> <span m=\"3808450\">complicated-looking</span>\
  \ <span m=\"3809350\">H.</span> <span m=\"3810100\">So</span> <span m=\"3810250\"\
  >for</span> <span m=\"3810370\">example,</span> <span m=\"3811390\">H</span> <span\
  \ m=\"3811750\">might be</span> <span m=\"3812080\">the</span> <span m=\"3812200\"\
  >Petersen</span> <span m=\"3812650\">graph.</span> <span m=\"3819680\">So</span>\
  \ <span m=\"3819920\">every</span> <span m=\"3820160\">good</span> <span m=\"3820370\"\
  >graph</span> <span m=\"3820730\">theory</span> <span m=\"3820790\">course</span>\
  \ <span m=\"3821200\">should</span> <span m=\"3821750\">feature a</span> <span m=\"\
  3822200\">Petersen</span> <span m=\"3822680\">graph</span> <span m=\"3822950\">at</span>\
  \ <span m=\"3823010\">least</span> <span m=\"3823220\">once,</span> <span m=\"3823890\"\
  >somewhere.</span> <span m=\"3825710\">So</span> <span m=\"3825810\">that's</span>\
  \ <span m=\"3825890\">the</span> <span m=\"3825950\">Petersen</span> <span m=\"\
  3826340\">graph.</span> <span m=\"3828660\">What's</span> <span m=\"3828810\">the</span>\
  \ <span m=\"3828900\">chromatic</span> <span m=\"3829290\">number</span> <span m=\"\
  3829500\">of</span> <span m=\"3829590\">the</span> <span m=\"3829650\">Petersen</span>\
  \ <span m=\"3830010\">graph?</span></p><p><span m=\"3830946\">Actually,</span> <span\
  \ m=\"3831310\">that's</span> <span m=\"3832140\">kind</span> <span m=\"3832320\"\
  >of</span> <span m=\"3832410\">a</span> <span m=\"3832470\">tricky</span> <span\
  \ m=\"3832770\">question.</span> <span m=\"3833090\">The</span> <span m=\"3833160\"\
  >last</span> <span m=\"3833370\">time</span> <span m=\"3833490\">I</span> <span\
  \ m=\"3833580\">taught</span> <span m=\"3833760\">this</span> <span m=\"3833910\"\
  >course,</span> <span m=\"3834150\">I</span> <span m=\"3834270\">even</span> <span\
  \ m=\"3834510\">got</span> <span m=\"3834660\">the</span> <span m=\"3834780\">answer</span>\
  \ <span m=\"3835020\">wrong.</span> <span m=\"3835710\">So</span> <span m=\"3836880\"\
  >it</span> <span m=\"3836970\">turns</span> <span m=\"3837180\">out</span> <span\
  \ m=\"3837270\">you</span> <span m=\"3837360\">can</span> <span m=\"3837480\">three-color</span>\
  \ <span m=\"3838020\">the</span> <span m=\"3838110\">Petersen</span> <span m=\"\
  3838500\">graph.</span></p><p><span m=\"3840050\">So</span> <span m=\"3840330\"\
  >it's</span> <span m=\"3841230\">completely</span> <span m=\"3841620\">not</span>\
  \ <span m=\"3841830\">obvious</span> <span m=\"3842190\">how</span> <span m=\"3842340\"\
  >to</span> <span m=\"3842460\">do</span> <span m=\"3842580\">this.</span> <span\
  \ m=\"3843390\">But</span> <span m=\"3844870\">there</span> <span m=\"3845030\"\
  >are</span> <span m=\"3845070\">only</span> <span m=\"3845730\">so</span> <span\
  \ m=\"3845940\">many</span> <span m=\"3846150\">vertices.</span> <span m=\"3846660\"\
  >If</span> <span m=\"3846750\">you</span> <span m=\"3846810\">stare</span> <span\
  \ m=\"3847170\">at it</span> <span m=\"3847290\">long</span> <span m=\"3847500\"\
  >enough,</span> <span m=\"3847950\">you</span> <span m=\"3848400\">can</span> <span\
  \ m=\"3848520\">see</span> <span m=\"3848730\">what</span> <span m=\"3848880\">happens.</span>\
  \ <span m=\"3849240\">But</span> <span m=\"3849360\">let</span> <span m=\"3849450\"\
  >me</span> <span m=\"3850340\">just</span> <span m=\"3850650\">show</span> <span\
  \ m=\"3850920\">you</span> <span m=\"3851100\">a</span> <span m=\"3851160\">three-coloring</span>\
  \ <span m=\"3851830\">of</span> <span m=\"3851920\">the</span> <span m=\"3852030\"\
  >Petersen</span> <span m=\"3852420\">graph.</span></p><p><span m=\"3861135\">Then</span>\
  \ <span m=\"3861640\">the</span> <span m=\"3862030\">third</span> <span m=\"3862360\"\
  >color</span> <span m=\"3862690\">is</span> <span m=\"3863183\">like that.</span>\
  \ <span m=\"3866640\">So</span> <span m=\"3866800\">that's</span> <span m=\"3866980\"\
  >a</span> <span m=\"3867040\">three-coloring</span> <span m=\"3867670\">of</span>\
  \ <span m=\"3867760\">the</span> <span m=\"3867820\">Petersen</span> <span m=\"\
  3868210\">graph.</span> <span m=\"3870880\">That's</span> <span m=\"3871360\">chromatic</span>\
  \ <span m=\"3871780\">number</span> <span m=\"3871990\">3.</span> <span m=\"3872340\"\
  >It's</span> <span m=\"3872530\">not</span> <span m=\"3872770\">2.</span> <span\
  \ m=\"3873320\">So why</span> <span m=\"3873620\">is it</span> <span m=\"3873810\"\
  >not</span> <span m=\"3873940\">2?</span></p><p><span m=\"3875146\">AUDIENCE:</span>\
  \ <span m=\"3875292\">It's</span> <span m=\"3875438\">not</span> <span m=\"3875584\"\
  >bipartite.</span></p><p><span m=\"3876460\">YUFEI ZHAO:</span> <span m=\"3876520\"\
  >It's</span> <span m=\"3876580\">not</span> <span m=\"3876700\">bipartite.</span>\
  \ <span m=\"3877015\">It's a</span> <span m=\"3877330\">five</span> <span m=\"3877640\"\
  >cycle,</span> <span m=\"3878080\">which cannot</span> <span m=\"3878320\">be</span>\
  \ <span m=\"3878410\">two-colored.</span> <span m=\"3880770\">So</span> <span m=\"\
  3881140\">then</span> <span m=\"3881290\">the</span> <span m=\"3881380\">limit</span>\
  \ <span m=\"3882760\">is</span> <span m=\"3883180\">1/2.</span> <span m=\"3884230\"\
  >And--</span> <span m=\"3886940\">no.</span> <span m=\"3887410\">That's</span> <span\
  \ m=\"3887880\">3.</span> <span m=\"3890070\">Great.</span> <span m=\"3891030\"\
  >So</span> <span m=\"3891210\">the</span> <span m=\"3891300\">limit</span> <span\
  \ m=\"3891690\">is</span> <span m=\"3891960\">1/2.</span></p><p><span m=\"3892740\"\
  >And</span> <span m=\"3892860\">here,</span> <span m=\"3893250\">I</span> <span\
  \ m=\"3894150\">think that</span> <span m=\"3894380\">we</span> <span m=\"3894600\"\
  >can</span> <span m=\"3894750\">apply</span> <span m=\"3895170\">this</span> <span\
  \ m=\"3895350\">theorem</span> <span m=\"3895650\">of</span> <span m=\"3895870\"\
  >Erdos-Stone-Simonovits.</span> <span m=\"3898350\">And</span> <span m=\"3899280\"\
  >I</span> <span m=\"3899400\">think</span> <span m=\"3899640\">this</span> <span\
  \ m=\"3899740\">should</span> <span m=\"3899910\">be</span> <span m=\"3900000\"\
  >somewhat</span> <span m=\"3900360\">surprising.</span> <span m=\"3901420\">Because</span>\
  \ <span m=\"3902430\">the</span> <span m=\"3902490\">Petersen</span> <span m=\"\
  3902850\">graph</span> <span m=\"3903060\">looks</span> <span m=\"3903330\">quite</span>\
  \ <span m=\"3903600\">complicated.</span> <span m=\"3904120\">If</span> <span m=\"\
  3904230\">you</span> <span m=\"3904350\">try</span> <span m=\"3904620\">to</span>\
  \ <span m=\"3905340\">forbid</span> <span m=\"3906180\">this</span> <span m=\"3906360\"\
  >graph</span> <span m=\"3906720\">in</span> <span m=\"3906840\">some</span> <span\
  \ m=\"3907050\">big</span> <span m=\"3907260\">G,</span> <span m=\"3907560\">it</span>\
  \ <span m=\"3907650\">seems</span> <span m=\"3908010\">like</span> <span m=\"3908500\"\
  >it's</span> <span m=\"3908700\">kind</span> <span m=\"3909090\">of</span> <span\
  \ m=\"3909180\">hard</span> <span m=\"3909390\">to</span> <span m=\"3909480\">do.</span>\
  \ <span m=\"3910670\">But</span> <span m=\"3910820\">it</span> <span m=\"3910880\"\
  >turns</span> <span m=\"3911150\">out</span> <span m=\"3911250\">the</span> <span\
  \ m=\"3911330\">chromatic</span> <span m=\"3911720\">number</span> <span m=\"3911960\"\
  >completely</span> <span m=\"3912380\">governs</span> <span m=\"3912950\">the</span>\
  \ <span m=\"3913130\">behavior</span> <span m=\"3914090\">of</span> <span m=\"3914900\"\
  >the</span> <span m=\"3914960\">extremal</span> <span m=\"3915350\">numbers.</span></p><p><span\
  \ m=\"3918120\">But</span> <span m=\"3918200\">it</span> <span m=\"3918290\">turns</span>\
  \ <span m=\"3918530\">out</span> <span m=\"3919070\">that's</span> <span m=\"3919820\"\
  >not</span> <span m=\"3920390\">the</span> <span m=\"3920630\">entire</span> <span\
  \ m=\"3922340\">story.</span> <span m=\"3923510\">Because</span> <span m=\"3924260\"\
  >while</span> <span m=\"3924470\">this</span> <span m=\"3924680\">is</span> <span\
  \ m=\"3924830\">quite</span> <span m=\"3925160\">a</span> <span m=\"3925220\">good</span>\
  \ <span m=\"3925370\">theorem,</span> <span m=\"3925670\">and</span> <span m=\"\
  3925790\">I</span> <span m=\"3925850\">said,</span> <span m=\"3926280\">it</span>\
  \ <span m=\"3926300\">gives</span> <span m=\"3926600\">you</span> <span m=\"3926720\"\
  >the</span> <span m=\"3926810\">first-order</span> <span m=\"3927390\">asymptotics,</span>\
  \ <span m=\"3928700\">actually,</span> <span m=\"3929060\">that's</span> <span m=\"\
  3929270\">a</span> <span m=\"3929330\">lie.</span> <span m=\"3930000\">It</span>\
  \ <span m=\"3930020\">doesn't</span> <span m=\"3930440\">always</span> <span m=\"\
  3930800\">give</span> <span m=\"3931010\">you</span> <span m=\"3931130\">the</span>\
  \ <span m=\"3931220\">first-order</span> <span m=\"3931640\">asymptotics.</span>\
  \ <span m=\"3934010\">And</span> <span m=\"3934220\">when</span> <span m=\"3934950\"\
  >is</span> <span m=\"3935970\">Erdos-Stone-Simonovits</span> <span m=\"3937830\"\
  >not</span> <span m=\"3938130\">effective?</span> <span m=\"3939300\">Or</span>\
  \ <span m=\"3939390\">rather,</span> <span m=\"3939750\">it's</span> <span m=\"\
  3939960\">not</span> <span m=\"3940320\">the</span> <span m=\"3940440\">complete--</span>\
  \ <span m=\"3941130\">it's</span> <span m=\"3941610\">not</span> <span m=\"3941820\"\
  >the</span> <span m=\"3941880\">final</span> <span m=\"3942240\">answer.</span>\
  \ <span m=\"3943490\">Well,</span> <span m=\"3943700\">you</span> <span m=\"3943820\"\
  >can</span> <span m=\"3943940\">say,</span> <span m=\"3944320\">well,</span> <span\
  \ m=\"3944600\">what</span> <span m=\"3944660\">about</span> <span m=\"3944870\"\
  >this</span> <span m=\"3945090\">little</span> <span m=\"3945420\">o?</span></p><p><span\
  \ m=\"3948280\">So</span> <span m=\"3949130\">we're</span> <span m=\"3949250\">still</span>\
  \ <span m=\"3949850\">trying</span> <span m=\"3950090\">to</span> <span m=\"3950150\"\
  >understand,</span> <span m=\"3951380\">there's</span> <span m=\"3951740\">a</span>\
  \ <span m=\"3951800\">limit.</span> <span m=\"3952610\">And</span> <span m=\"3952910\"\
  >you</span> <span m=\"3953000\">can</span> <span m=\"3953150\">understand</span>\
  \ <span m=\"3953750\">what</span> <span m=\"3953990\">is</span> <span m=\"3954140\"\
  >the--</span> <span m=\"3956860\">how</span> <span m=\"3957100\">quickly</span>\
  \ <span m=\"3957730\">does</span> <span m=\"3957910\">it</span> <span m=\"3957970\"\
  >converge</span> <span m=\"3958420\">to</span> <span m=\"3958570\">this</span> <span\
  \ m=\"3958750\">number</span> <span m=\"3959020\">here?</span> <span m=\"3960810\"\
  >So</span> <span m=\"3960980\">that's</span> <span m=\"3961550\">certainly</span>\
  \ <span m=\"3961880\">a</span> <span m=\"3961940\">valid</span> <span m=\"3962240\"\
  >question.</span> <span m=\"3963830\">But</span> <span m=\"3963980\">more</span>\
  \ <span m=\"3964160\">importantly,</span> <span m=\"3964670\">though,</span> <span\
  \ m=\"3965480\">if</span> <span m=\"3965780\">your</span> <span m=\"3966380\">graphic\
  \ is</span> <span m=\"3966860\">bipartite,</span> <span m=\"3969654\">if</span>\
  \ <span m=\"3972075\">chi of</span> <span m=\"3972440\">H</span> <span m=\"3972650\"\
  >equals to</span> <span m=\"3972985\">2,</span> <span m=\"3974370\">i.e.</span>\
  \ <span m=\"3974650\">bipartite,</span> <span m=\"3979103\">then</span> <span m=\"\
  3980030\">all</span> <span m=\"3980300\">this</span> <span m=\"3980570\">theorem</span>\
  \ <span m=\"3981020\">tells</span> <span m=\"3981410\">you</span> <span m=\"3981950\"\
  >is</span> <span m=\"3982190\">that</span> <span m=\"3982610\">the</span> <span\
  \ m=\"3983060\">limit</span> <span m=\"3983570\">is</span> <span m=\"3983780\">equal</span>\
  \ <span m=\"3984080\">to</span> <span m=\"3984320\">0,</span> <span m=\"3985790\"\
  >which</span> <span m=\"3985970\">somehow</span> <span m=\"3986240\">is</span> <span\
  \ m=\"3986360\">not</span> <span m=\"3986570\">the</span> <span m=\"3986660\">most</span>\
  \ <span m=\"3986960\">satisfying</span> <span m=\"3987300\">answer.</span> <span\
  \ m=\"3988010\">You</span> <span m=\"3988190\">want</span> <span m=\"3988370\">to</span>\
  \ <span m=\"3988430\">know</span> <span m=\"3988710\">the</span> <span m=\"3988810\"\
  >first-order</span> <span m=\"3989180\">asymptotics.</span> <span m=\"3990590\"\
  >I</span> <span m=\"3990680\">mean,</span> <span m=\"3990830\">this</span> <span\
  \ m=\"3990980\">still</span> <span m=\"3991250\">tells</span> <span m=\"3991580\"\
  >you</span> <span m=\"3991670\">something.</span></p><p><span m=\"3992240\">So</span>\
  \ <span m=\"3992710\">the</span> <span m=\"3992870\">Erdos-Stone-Simonovits</span>\
  \ <span m=\"3994240\">theorem</span> <span m=\"3994790\">tells</span> <span m=\"\
  3995120\">you</span> <span m=\"3995660\">that</span> <span m=\"3996080\">the</span>\
  \ <span m=\"3996200\">extremal</span> <span m=\"3996680\">number</span> <span m=\"\
  3998230\">is</span> <span m=\"3998830\">little</span> <span m=\"3999090\">o</span>\
  \ <span m=\"3999610\">of</span> <span m=\"3999920\">n</span> <span m=\"4000100\"\
  >squared.</span> <span m=\"4002268\">But</span> <span m=\"4002690\">of</span> <span\
  \ m=\"4002750\">course,</span> <span m=\"4003050\">no.</span> <span m=\"4003180\"\
  >You</span> <span m=\"4003440\">are</span> <span m=\"4003560\">a</span> <span m=\"\
  4003590\">curious</span> <span m=\"4004070\">mathematician.</span> <span m=\"4004760\"\
  >And</span> <span m=\"4004850\">you</span> <span m=\"4004940\">want</span> <span\
  \ m=\"4005090\">to</span> <span m=\"4005150\">know,</span> <span m=\"4006080\">really,</span>\
  \ <span m=\"4006410\">what</span> <span m=\"4006680\">is</span> <span m=\"4006830\"\
  >the</span> <span m=\"4006950\">asymptotics?</span> <span m=\"4008950\">Is</span>\
  \ <span m=\"4009100\">it</span> <span m=\"4009520\">like</span> <span m=\"4009870\"\
  >n</span> <span m=\"4010120\">to</span> <span m=\"4010270\">the</span> <span m=\"\
  4010750\">3/2?</span> <span m=\"4011620\">Is</span> <span m=\"4011630\">it</span>\
  \ <span m=\"4011710\">like</span> <span m=\"4012280\">n</span> <span m=\"4012460\"\
  >to</span> <span m=\"4012580\">the</span> <span m=\"4012880\">4/3?</span> <span\
  \ m=\"4013840\">You</span> <span m=\"4013900\">know,</span> <span m=\"4014510\"\
  >is</span> <span m=\"4014710\">this</span> <span m=\"4014890\">is</span> <span m=\"\
  4015010\">not</span> <span m=\"4015400\">satisfying.</span></p><p><span m=\"4016670\"\
  >And</span> <span m=\"4016720\">it</span> <span m=\"4016780\">turns</span> <span\
  \ m=\"4017050\">out,</span> <span m=\"4017620\">from</span> <span m=\"4018550\"\
  >most</span> <span m=\"4019200\">bipartite</span> <span m=\"4019650\">graphs</span>\
  \ <span m=\"4020070\">H,</span> <span m=\"4021810\">it</span> <span m=\"4021970\"\
  >is</span> <span m=\"4022090\">a</span> <span m=\"4022120\">very</span> <span m=\"\
  4022330\">difficult</span> <span m=\"4022720\">problem</span> <span m=\"4023430\"\
  >that</span> <span m=\"4023590\">we</span> <span m=\"4023770\">still</span> <span\
  \ m=\"4024040\">do</span> <span m=\"4024160\">not</span> <span m=\"4024370\">know</span>\
  \ <span m=\"4024520\">the</span> <span m=\"4024670\">answer</span> <span m=\"4024970\"\
  >to,</span> <span m=\"4025420\">even</span> <span m=\"4025690\">what</span> <span\
  \ m=\"4025900\">is</span> <span m=\"4026050\">the</span> <span m=\"4026710\">order</span>\
  \ <span m=\"4027100\">of</span> <span m=\"4027250\">the</span> <span m=\"4027370\"\
  >asymptotics.</span> <span m=\"4028510\">So</span> <span m=\"4028660\">the</span>\
  \ <span m=\"4028780\">next</span> <span m=\"4029140\">few</span> <span m=\"4029350\"\
  >lectures,</span> <span m=\"4030190\">what</span> <span m=\"4030370\">I</span> <span\
  \ m=\"4030430\">want</span> <span m=\"4030610\">to</span> <span m=\"4030670\">do</span>\
  \ <span m=\"4031240\">is</span> <span m=\"4031420\">to</span> <span m=\"4031510\"\
  >show</span> <span m=\"4031840\">you</span> <span m=\"4031990\">some</span> <span\
  \ m=\"4032290\">techniques</span> <span m=\"4033250\">that</span> <span m=\"4033400\"\
  >will</span> <span m=\"4033640\">allow</span> <span m=\"4034000\">you</span> <span\
  \ m=\"4034240\">to</span> <span m=\"4035680\">prove</span> <span m=\"4036070\">some</span>\
  \ <span m=\"4036820\">upper</span> <span m=\"4037030\">bounds</span> <span m=\"\
  4038550\">for</span> <span m=\"4039870\">this</span> <span m=\"4040170\">extremal</span>\
  \ <span m=\"4040610\">number</span> <span m=\"4041040\">in</span> <span m=\"4041130\"\
  >the</span> <span m=\"4041220\">case</span> <span m=\"4041550\">when</span> <span\
  \ m=\"4041790\">H</span> <span m=\"4042030\">is</span> <span m=\"4042160\">bipartite</span>\
  \ <span m=\"4043530\">that</span> <span m=\"4043710\">shows</span> <span m=\"4044010\"\
  >you</span> <span m=\"4044130\">that</span> <span m=\"4044220\">the</span> <span\
  \ m=\"4044310\">exponent</span> <span m=\"4044880\">can</span> <span m=\"4045090\"\
  >be</span> <span m=\"4045210\">less</span> <span m=\"4045480\">than</span> <span\
  \ m=\"4045670\">2.</span> <span m=\"4047500\">And</span> <span m=\"4047620\">I</span>\
  \ <span m=\"4047710\">will</span> <span m=\"4047830\">also</span> <span m=\"4048130\"\
  >show</span> <span m=\"4048400\">you</span> <span m=\"4049120\">some</span> <span\
  \ m=\"4049390\">constructions</span> <span m=\"4051490\">that</span> <span m=\"\
  4052450\">sometimes,</span> <span m=\"4053250\">but</span> <span m=\"4053410\">in</span>\
  \ <span m=\"4053500\">the</span> <span m=\"4053590\">very</span> <span m=\"4053800\"\
  >few</span> <span m=\"4054070\">cases,</span> <span m=\"4054940\">matches</span>\
  \ <span m=\"4055600\">the</span> <span m=\"4055720\">upper</span> <span m=\"4055960\"\
  >bound.</span></p><p><span m=\"4057020\">So</span> <span m=\"4057160\">there</span>\
  \ <span m=\"4057340\">are</span> <span m=\"4057430\">very</span> <span m=\"4057820\"\
  >few</span> <span m=\"4058150\">examples</span> <span m=\"4059110\">of</span> <span\
  \ m=\"4059260\">graphs</span> <span m=\"4059800\">H</span> <span m=\"4060550\">for</span>\
  \ <span m=\"4060700\">which</span> <span m=\"4061180\">we</span> <span m=\"4061390\"\
  >know</span> <span m=\"4061630\">the</span> <span m=\"4061720\">first-order</span>\
  \ <span m=\"4062310\">asymptotics.</span> <span m=\"4063860\">And</span> <span m=\"\
  4064000\">for</span> <span m=\"4064230\">most</span> <span m=\"4064540\">graph</span>\
  \ <span m=\"4064870\">H,</span> <span m=\"4066120\">they</span> <span m=\"4066290\"\
  >are</span> <span m=\"4066400\">major</span> <span m=\"4066820\">open</span> <span\
  \ m=\"4067120\">problems</span> <span m=\"4067450\">in</span> <span m=\"4067540\"\
  >combinatorics.</span> <span m=\"4068510\">And</span> <span m=\"4068650\">there</span>\
  \ <span m=\"4068720\">are</span> <span m=\"4068800\">some</span> <span m=\"4068980\"\
  >really</span> <span m=\"4069220\">old</span> <span m=\"4069460\">ones</span> <span\
  \ m=\"4069850\">for</span> <span m=\"4070000\">which</span> <span m=\"4070180\"\
  >any</span> <span m=\"4070390\">solution</span> <span m=\"4070840\">may</span> <span\
  \ m=\"4070990\">be</span> <span m=\"4071500\">quite</span> <span m=\"4071800\">exciting.</span></p><p><span\
  \ m=\"4076580\">I</span> <span m=\"4076670\">will</span> <span m=\"4076790\">not</span>\
  \ <span m=\"4077000\">show</span> <span m=\"4077180\">you</span> <span m=\"4077330\"\
  >a</span> <span m=\"4077390\">proof</span> <span m=\"4077720\">of</span> <span m=\"\
  4078140\">Erdos-Stone-Simonovits</span> <span m=\"4079110\">now.</span> <span m=\"\
  4079730\">We</span> <span m=\"4079850\">will</span> <span m=\"4079970\">see</span>\
  \ <span m=\"4080180\">that</span> <span m=\"4080450\">later</span> <span m=\"4080810\"\
  >in</span> <span m=\"4080900\">the</span> <span m=\"4080990\">term,</span> <span\
  \ m=\"4081290\">once</span> <span m=\"4081560\">we</span> <span m=\"4081630\">have</span>\
  \ <span m=\"4081770\">developed</span> <span m=\"4082640\">some</span> <span m=\"\
  4082850\">more</span> <span m=\"4083000\">machinery.</span> <span m=\"4083870\"\
  >Although,</span> <span m=\"4085190\">later</span> <span m=\"4085430\">on in</span>\
  \ <span m=\"4085670\">the</span> <span m=\"4085760\">term,</span> <span m=\"4086060\"\
  >we'll</span> <span m=\"4086240\">see</span> <span m=\"4086560\">a proof</span>\
  \ <span m=\"4086930\">using</span> <span m=\"4087320\">the</span> <span m=\"4087440\"\
  >so-called</span> <span m=\"4087830\">Szemer\xE9di's</span> <span m=\"4088360\"\
  >regularity</span> <span m=\"4088940\">lemma,</span> <span m=\"4089450\">which</span>\
  \ <span m=\"4089630\">I've</span> <span m=\"4089750\">mentioned</span> <span m=\"\
  4090050\">a</span> <span m=\"4090110\">few</span> <span m=\"4090290\">times</span>\
  \ <span m=\"4090590\">in</span> <span m=\"4090680\">the</span> <span m=\"4090740\"\
  >first</span> <span m=\"4091010\">lecture.</span> <span m=\"4092720\">Although,</span>\
  \ <span m=\"4092900\">you</span> <span m=\"4093020\">don't</span> <span m=\"4093200\"\
  >actually</span> <span m=\"4093590\">need</span> <span m=\"4093770\">such</span>\
  \ <span m=\"4094310\">heavy</span> <span m=\"4094550\">machinery.</span></p><p><span\
  \ m=\"4096270\">So</span> <span m=\"4096439\">the</span> <span m=\"4096560\">original</span>\
  \ <span m=\"4097010\">proofs</span> <span m=\"4097819\">of</span> <span m=\"4098340\"\
  >Erdos and</span> <span m=\"4098770\">Stone,</span> <span m=\"4099500\">and</span>\
  \ <span m=\"4100250\">also by</span> <span m=\"4100580\">Simonovits--</span> <span\
  \ m=\"4101570\">so</span> <span m=\"4101830\">Erdos and</span> <span m=\"4102240\"\
  >Stone</span> <span m=\"4102500\">first</span> <span m=\"4103220\">proved</span>\
  \ <span m=\"4103490\">this</span> <span m=\"4103700\">result</span> <span m=\"4104660\"\
  >for</span> <span m=\"4105020\">H</span> <span m=\"4105290\">being</span> <span\
  \ m=\"4105560\">a</span> <span m=\"4105620\">complete</span> <span m=\"4106279\"\
  >multipartite</span> <span m=\"4106880\">graph.</span> <span m=\"4107750\">And</span>\
  \ <span m=\"4107920\">Simonovits</span> <span m=\"4108920\">observed</span> <span\
  \ m=\"4109370\">that</span> <span m=\"4110330\">knowing</span> <span m=\"4110750\"\
  >H</span> <span m=\"4111020\">for</span> <span m=\"4111170\">a</span> <span m=\"\
  4111200\">complete</span> <span m=\"4111620\">multipartite</span> <span m=\"4112149\"\
  >graph</span> <span m=\"4112760\">actually</span> <span m=\"4113060\">implies</span>\
  \ <span m=\"4113870\">this</span> <span m=\"4114050\">result</span> <span m=\"4114410\"\
  >in</span> <span m=\"4114529\">general.</span> <span m=\"4115109\">So</span> <span\
  \ m=\"4115715\">you</span> <span m=\"4116060\">will</span> <span m=\"4116149\">not</span>\
  \ <span m=\"4116359\">find</span> <span m=\"4116770\">a</span> <span m=\"4116830\"\
  >paper</span> <span m=\"4117200\">with</span> <span m=\"4117979\">all</span> <span\
  \ m=\"4118130\">three</span> <span m=\"4118430\">of</span> <span m=\"4118550\">them</span>\
  \ <span m=\"4119660\">being</span> <span m=\"4119899\">authors.</span> <span m=\"\
  4121170\">But</span> <span m=\"4121580\">this</span> <span m=\"4121729\">is</span>\
  \ <span m=\"4121850\">what</span> <span m=\"4122000\">the</span> <span m=\"4122540\"\
  >theorem is</span> <span m=\"4122930\">called.</span></p><p><span m=\"4125460\"\
  >So</span> <span m=\"4125590\">later</span> <span m=\"4125859\">on</span> <span\
  \ m=\"4125950\">in</span> <span m=\"4126040\">the</span> <span m=\"4126100\">course,</span>\
  \ <span m=\"4126500\">once</span> <span m=\"4126600\">we've</span> <span m=\"4126779\"\
  >developed</span> <span m=\"4127140\">the</span> <span m=\"4127390\">machinery</span>\
  \ <span m=\"4127870\">of</span> <span m=\"4128649\">graph</span> <span m=\"4128920\"\
  >regularity</span> <span m=\"4129430\">lemmas,</span> <span m=\"4130180\">I</span>\
  \ <span m=\"4130270\">will</span> <span m=\"4130390\">show</span> <span m=\"4130630\"\
  >you</span> <span m=\"4130810\">how</span> <span m=\"4131560\">you</span> <span\
  \ m=\"4131680\">can</span> <span m=\"4131859\">deduce</span> <span m=\"4132569\"\
  >Erdos-Stone-Simonovits</span> <span m=\"4135090\">from</span> <span m=\"4135720\"\
  >Tur\xE1n's</span> <span m=\"4136160\">theorem.</span> <span m=\"4136992\">So</span>\
  \ <span m=\"4137410\">somehow</span> <span m=\"4137680\">you</span> <span m=\"4137800\"\
  >use</span> <span m=\"4138040\">Tur\xE1n's</span> <span m=\"4138399\">theorem</span>\
  \ <span m=\"4139120\">and</span> <span m=\"4139270\">bootstrap</span> <span m=\"\
  4139899\">it</span> <span m=\"4140140\">to</span> <span m=\"4140500\">Erdos-Stone-Simonovits.</span>\
  \ <span m=\"4144380\">So</span> <span m=\"4144569\">that</span> <span m=\"4145279\"\
  >should</span> <span m=\"4145520\">seem</span> <span m=\"4145939\">somewhat</span>\
  \ <span m=\"4146240\">magical.</span></p><p><span m=\"4146810\">So</span> <span\
  \ m=\"4147620\">on</span> <span m=\"4147710\">one</span> <span m=\"4147830\">hand,</span>\
  \ <span m=\"4148080\">you</span> <span m=\"4148180\">have</span> <span m=\"4148189\"\
  >cliques.</span> <span m=\"4148580\">On</span> <span m=\"4148700\">the</span> <span\
  \ m=\"4148760\">other</span> <span m=\"4148939\">hand,</span> <span m=\"4149189\"\
  >you</span> <span m=\"4149290\">have</span> <span m=\"4149300\">things</span> <span\
  \ m=\"4149569\">that</span> <span m=\"4150140\">somehow</span> <span m=\"4151399\"\
  >don't</span> <span m=\"4151580\">have</span> <span m=\"4151760\">cliques</span>\
  \ <span m=\"4152170\">in them.</span> <span m=\"4152750\">They</span> <span m=\"\
  4152870\">don't</span> <span m=\"4153020\">really</span> <span m=\"4153229\">look</span>\
  \ <span m=\"4153410\">like</span> <span m=\"4153540\">cliques.</span> <span m=\"\
  4153899\">But</span> <span m=\"4154040\">you</span> <span m=\"4154130\">can</span>\
  \ <span m=\"4154279\">still</span> <span m=\"4154490\">bootstrap</span> <span m=\"\
  4155060\">one</span> <span m=\"4155510\">to</span> <span m=\"4155689\">the</span>\
  \ <span m=\"4155870\">other.</span> <span m=\"4156460\">And</span> <span m=\"4156560\"\
  >so</span> <span m=\"4156800\">after</span> <span m=\"4157100\">we</span> <span\
  \ m=\"4157220\">develop</span> <span m=\"4157569\">some</span> <span m=\"4157729\"\
  >machinery,</span> <span m=\"4158630\">we'll</span> <span m=\"4158810\">do</span>\
  \ <span m=\"4158960\">that.</span></p><p><span m=\"4159170\">But</span> <span m=\"\
  4159550\">there</span> <span m=\"4159720\">is</span> <span m=\"4159830\">a</span>\
  \ <span m=\"4160069\">combinatorial</span> <span m=\"4160850\">proof</span> <span\
  \ m=\"4161180\">which</span> <span m=\"4161390\">doesn't</span> <span m=\"4161660\"\
  >use</span> <span m=\"4161870\">any</span> <span m=\"4162020\">of</span> <span m=\"\
  4162109\">this</span> <span m=\"4162380\">heavy</span> <span m=\"4162590\">machinery.</span>\
  \ <span m=\"4164689\">I</span> <span m=\"4164779\">won't</span> <span m=\"4165020\"\
  >discuss</span> <span m=\"4165420\">it</span> <span m=\"4165945\">in</span> <span\
  \ m=\"4166250\">lecture,</span> <span m=\"4166609\">but</span> <span m=\"4166790\"\
  >you</span> <span m=\"4166880\">can</span> <span m=\"4167029\">look</span> <span\
  \ m=\"4167180\">it</span> <span m=\"4167300\">up.</span> <span m=\"4167750\">And</span>\
  \ <span m=\"4167990\">it's</span> <span m=\"4168680\">quite</span> <span m=\"4168950\"\
  >nice.</span> <span m=\"4169200\">It</span> <span m=\"4169279\">has</span> <span\
  \ m=\"4169430\">some</span> <span m=\"4169640\">combinatorial</span> <span m=\"\
  4170240\">techniques</span> <span m=\"4170930\">and</span> <span m=\"4171050\">some</span>\
  \ <span m=\"4171260\">double-counting</span> <span m=\"4171979\">arguments.</span></p><p><span\
  \ m=\"4177840\">So</span> <span m=\"4178470\">going</span> <span m=\"4178740\">forward,</span>\
  \ <span m=\"4179130\">I</span> <span m=\"4179220\">want</span> <span m=\"4179490\"\
  >to</span> <span m=\"4179700\">show</span> <span m=\"4179939\">you</span> <span\
  \ m=\"4180120\">some</span> <span m=\"4180899\">questions,</span> <span m=\"4182580\"\
  >mostly</span> <span m=\"4182880\">questions,</span> <span m=\"4183270\">but</span>\
  \ <span m=\"4183390\">some</span> <span m=\"4183630\">answers</span> <span m=\"\
  4183990\">as</span> <span m=\"4184109\">well--</span> <span m=\"4184609\">so</span>\
  \ <span m=\"4184770\">questions</span> <span m=\"4185550\">such</span> <span m=\"\
  4185850\">as,</span> <span m=\"4186870\">what</span> <span m=\"4187109\">is</span>\
  \ <span m=\"4187680\">the</span> <span m=\"4187830\">extremal</span> <span m=\"\
  4188340\">number</span> <span m=\"4189120\">of--</span> <span m=\"4189640\">well,</span>\
  \ <span m=\"4189960\">so</span> <span m=\"4190080\">what</span> <span m=\"4190260\"\
  >are</span> <span m=\"4190350\">some</span> <span m=\"4190500\">of</span> <span\
  \ m=\"4190560\">the</span> <span m=\"4190649\">basic</span> <span m=\"4191819\"\
  >bipartite</span> <span m=\"4192330\">graphs?</span> <span m=\"4193920\">One</span>\
  \ <span m=\"4194100\">of</span> <span m=\"4194160\">them</span> <span m=\"4194340\"\
  >is</span> <span m=\"4194490\">just</span> <span m=\"4194730\">a</span> <span m=\"\
  4194820\">complete</span> <span m=\"4195740\">bipartite</span> <span m=\"4196270\"\
  >graph.</span></p><p><span m=\"4199140\">So</span> <span m=\"4199180\">this</span>\
  \ <span m=\"4199490\">has</span> <span m=\"4199640\">a</span> <span m=\"4199670\"\
  >name.</span> <span m=\"4200000\">It's called</span> <span m=\"4200150\">the</span>\
  \ <span m=\"4200220\">Zarankiewicz</span> <span m=\"4200820\">problem.</span> <span\
  \ m=\"4202170\">And</span> <span m=\"4202770\">for</span> <span m=\"4203010\">some</span>\
  \ <span m=\"4203340\">values</span> <span m=\"4203730\">of</span> <span m=\"4203880\"\
  >s and</span> <span m=\"4204210\">t,</span> <span m=\"4204930\">we</span> <span\
  \ m=\"4205080\">know</span> <span m=\"4205230\">the</span> <span m=\"4205380\">answer.</span>\
  \ <span m=\"4206650\">But for</span> <span m=\"4207000\">most</span> <span m=\"\
  4207360\">values,</span> <span m=\"4207930\">we</span> <span m=\"4208110\">have</span>\
  \ <span m=\"4208230\">no</span> <span m=\"4208470\">idea</span> <span m=\"4208770\"\
  >what</span> <span m=\"4208920\">the</span> <span m=\"4209010\">answer</span> <span\
  \ m=\"4209280\">is.</span> <span m=\"4209700\">For</span> <span m=\"4209850\">example</span>\
  \ <span m=\"4210720\">for</span> <span m=\"4210930\">K4,4,</span> <span m=\"4212820\"\
  >we</span> <span m=\"4213000\">do</span> <span m=\"4213180\">not</span> <span m=\"\
  4214260\">know</span> <span m=\"4215310\">what</span> <span m=\"4215580\">is</span>\
  \ <span m=\"4215850\">the</span> <span m=\"4215970\">correct</span> <span m=\"4216510\"\
  >exponent</span> <span m=\"4217260\">on</span> <span m=\"4217410\">the</span> <span\
  \ m=\"4217520\">n.</span> <span m=\"4219472\">So</span> <span m=\"4219960\">even</span>\
  \ <span m=\"4220680\">fairly</span> <span m=\"4221040\">small</span> <span m=\"\
  4221310\">cases,</span> <span m=\"4221820\">it</span> <span m=\"4221910\">is</span>\
  \ <span m=\"4222150\">very</span> <span m=\"4222300\">much</span> <span m=\"4222540\"\
  >open.</span></p><p><span m=\"4223020\">So</span> <span m=\"4223170\">this</span>\
  \ <span m=\"4223350\">is</span> <span m=\"4223470\">all</span> <span m=\"4223590\"\
  >to</span> <span m=\"4223680\">show</span> <span m=\"4223920\">you</span> <span\
  \ m=\"4224010\">that</span> <span m=\"4224370\">these</span> <span m=\"4224580\"\
  >simple</span> <span m=\"4224940\">proofs</span> <span m=\"4225240\">that</span>\
  \ <span m=\"4225360\">we</span> <span m=\"4225480\">did</span> <span m=\"4225630\"\
  >today,</span> <span m=\"4226260\">they</span> <span m=\"4226410\">are</span> <span\
  \ m=\"4227220\">perhaps</span> <span m=\"4227670\">too</span> <span m=\"4227910\"\
  >deceptively</span> <span m=\"4228570\">simple.</span> <span m=\"4229425\">Because</span>\
  \ <span m=\"4229890\">even</span> <span m=\"4230130\">if</span> <span m=\"4230220\"\
  >you</span> <span m=\"4230340\">change</span> <span m=\"4230670\">the</span> <span\
  \ m=\"4230760\">question</span> <span m=\"4231090\">a</span> <span m=\"4231150\"\
  >little</span> <span m=\"4231360\">bit,</span> <span m=\"4232610\">we</span> <span\
  \ m=\"4232760\">don't</span> <span m=\"4232910\">understand</span> <span m=\"4233390\"\
  >a</span> <span m=\"4233450\">lot.</span> <span m=\"4236540\">So</span> <span m=\"\
  4236960\">questions</span> <span m=\"4237320\">like</span> <span m=\"4237440\">these</span>\
  \ <span m=\"4237680\">will</span> <span m=\"4237860\">occupy</span> <span m=\"4238520\"\
  >the</span> <span m=\"4238580\">next</span> <span m=\"4238970\">several</span> <span\
  \ m=\"4239300\">lectures.</span> <span m=\"4239630\">And</span> <span m=\"4239720\"\
  >I'll</span> <span m=\"4239770\">also</span> <span m=\"4240020\">show</span> <span\
  \ m=\"4240200\">you</span> <span m=\"4240260\">some</span> <span m=\"4240440\">constructions.</span>\
  \ <span m=\"4241390\">And</span> <span m=\"4241490\">there</span> <span m=\"4241580\"\
  >are</span> <span m=\"4241610\">some</span> <span m=\"4241760\">constructions</span>\
  \ <span m=\"4242240\">that</span> <span m=\"4242330\">use</span> <span m=\"4242570\"\
  >nice</span> <span m=\"4242900\">algebraic</span> <span m=\"4243500\">ideas</span>\
  \ <span m=\"4244250\">and</span> <span m=\"4244340\">some</span> <span m=\"4244520\"\
  >probabilistic</span> <span m=\"4245180\">ideas.</span> <span m=\"4245540\">So we'll</span>\
  \ <span m=\"4246010\">see</span> <span m=\"4246110\">ideas</span> <span m=\"4246470\"\
  >coming</span> <span m=\"4246710\">from</span> <span m=\"4246900\">many</span> <span\
  \ m=\"4247130\">different</span> <span m=\"4247880\">sources.</span></p><p><span\
  \ m=\"4249730\">I</span> <span m=\"4249820\">want</span> <span m=\"4250030\">to</span>\
  \ <span m=\"4250840\">close</span> <span m=\"4251230\">off</span> <span m=\"4251680\"\
  >by</span> <span m=\"4252190\">just</span> <span m=\"4252430\">a</span> <span m=\"\
  4252490\">cultural</span> <span m=\"4252940\">remark.</span> <span m=\"4253360\"\
  >So</span> <span m=\"4253570\">in</span> <span m=\"4253900\">this</span> <span m=\"\
  4254140\">course,</span> <span m=\"4255500\">especially</span> <span m=\"4256450\"\
  >the</span> <span m=\"4256540\">first</span> <span m=\"4256840\">half,</span> <span\
  \ m=\"4257110\">we'll</span> <span m=\"4257290\">encounter</span> <span m=\"4257830\"\
  >a</span> <span m=\"4257920\">lot</span> <span m=\"4258160\">of</span> <span m=\"\
  4258880\">Hungarian</span> <span m=\"4259480\">names.</span> <span m=\"4260530\"\
  >So</span> <span m=\"4260760\">we</span> <span m=\"4260920\">already</span> <span\
  \ m=\"4261280\">saw</span> <span m=\"4261580\">a</span> <span m=\"4261610\">couple</span>\
  \ <span m=\"4261940\">of</span> <span m=\"4262060\">them.</span> <span m=\"4262600\"\
  >And</span> <span m=\"4262750\">I</span> <span m=\"4262840\">just</span> <span m=\"\
  4263020\">want</span> <span m=\"4263170\">to</span> <span m=\"4263230\">give</span>\
  \ <span m=\"4263410\">you</span> <span m=\"4263470\">a</span> <span m=\"4263500\"\
  >very</span> <span m=\"4263710\">quick</span> <span m=\"4264010\">tutorial</span>\
  \ <span m=\"4265000\">on</span> <span m=\"4265120\">how</span> <span m=\"4265300\"\
  >to</span> <span m=\"4265390\">pronounce</span> <span m=\"4266200\">Hungarian</span>\
  \ <span m=\"4266770\">names,</span> <span m=\"4268115\">just</span> <span m=\"4268490\"\
  >for</span> <span m=\"4268690\">cultural</span> <span m=\"4269020\">purposes</span>\
  \ <span m=\"4269440\">now.</span></p><p><span m=\"4270370\">In</span> <span m=\"\
  4270490\">the</span> <span m=\"4270550\">past,</span> <span m=\"4270880\">when</span>\
  \ <span m=\"4271030\">I</span> <span m=\"4271170\">took</span> <span m=\"4271380\"\
  >this</span> <span m=\"4271570\">CLASS</span> <span m=\"4272380\">there</span> <span\
  \ m=\"4272500\">were</span> <span m=\"4272650\">no</span> <span m=\"4272860\">Hungarian</span>\
  \ <span m=\"4273400\">speakers.</span> <span m=\"4274000\">But</span> <span m=\"\
  4274150\">I</span> <span m=\"4274240\">think</span> <span m=\"4274450\">we</span>\
  \ <span m=\"4274540\">do</span> <span m=\"4274720\">have</span> <span m=\"4275370\"\
  >at</span> <span m=\"4275560\">least</span> <span m=\"4275710\">one</span> <span\
  \ m=\"4275860\">Hungarian</span> <span m=\"4276340\">speaker</span> <span m=\"4276670\"\
  >in</span> <span m=\"4276760\">the</span> <span m=\"4276820\">room.</span> <span\
  \ m=\"4277060\">So</span> <span m=\"4277240\">I</span> <span m=\"4277330\">want</span>\
  \ <span m=\"4277660\">you--</span> <span m=\"4278940\">but</span> <span m=\"4279240\"\
  >you</span> <span m=\"4279550\">are</span> <span m=\"4279670\">a</span> <span m=\"\
  4279730\">native</span> <span m=\"4280120\">Hungarian</span> <span m=\"4280570\"\
  >speaker.</span> <span m=\"4281020\">So</span> <span m=\"4281230\">you</span> <span\
  \ m=\"4281350\">should</span> <span m=\"4281890\">tell</span> <span m=\"4282130\"\
  >us.</span> <span m=\"4282580\">So</span> <span m=\"4282700\">can</span> <span m=\"\
  4282880\">you</span> <span m=\"4284080\">help</span> <span m=\"4284280\">us</span>\
  \ <span m=\"4284410\">pronounce</span> <span m=\"4284860\">these</span> <span m=\"\
  4285040\">names?</span></p><p><span m=\"4286288\">AUDIENCE:</span> <span m=\"4286495\"\
  >Erdos.</span></p><p><span m=\"4287530\">YUFEI ZHAO:</span> <span m=\"4287770\"\
  >Erdos.</span> <span m=\"4289150\">And</span> <span m=\"4289570\">this</span> <span\
  \ m=\"4289750\">one?</span></p><p><span m=\"4290900\">AUDIENCE:</span> <span m=\"\
  4291135\">That</span> <span m=\"4291840\">doesn't seem like</span> <span m=\"4292310\"\
  >a</span> <span m=\"4292780\">Hungarian</span> <span m=\"4293250\">name.</span></p><p><span\
  \ m=\"4293720\">[LAUGHTER]</span></p><p>&nbsp;</p><p><span m=\"4296080\">YUFEI ZHAO:</span>\
  \ <span m=\"4296185\">So</span> <span m=\"4297280\">this,</span> <span m=\"4297640\"\
  >Hungarian,</span> <span m=\"4297980\">it's</span> <span m=\"4298240\">Simonovits.</span>\
  \ <span m=\"4300790\">So</span> <span m=\"4302560\">I'll</span> <span m=\"4302650\"\
  >just</span> <span m=\"4302830\">tell</span> <span m=\"4303100\">you</span> <span\
  \ m=\"4303190\">two</span> <span m=\"4303340\">things</span> <span m=\"4303640\"\
  >about</span> <span m=\"4303790\">Hungarian</span> <span m=\"4304270\">names.</span>\
  \ <span m=\"4305860\">One</span> <span m=\"4306040\">of</span> <span m=\"4306100\"\
  >them</span> <span m=\"4306310\">is</span> <span m=\"4306460\">that</span> <span\
  \ m=\"4306610\">the</span> <span m=\"4306880\">S--</span></p><p><span m=\"4307650\"\
  >AUDIENCE:</span> <span m=\"4307855\">It's</span> <span m=\"4308060\">/sh/.</span></p><p><span\
  \ m=\"4308470\">YUFEI ZHAO:</span> <span m=\"4308545\">--is</span> <span m=\"4308620\"\
  >pronounced</span> <span m=\"4309040\">like</span> <span m=\"4309220\">/sh/.</span>\
  \ <span m=\"4312160\">And</span> <span m=\"4312400\">another</span> <span m=\"4312700\"\
  >thing</span> <span m=\"4312880\">that</span> <span m=\"4313000\">comes</span> <span\
  \ m=\"4313300\">up</span> <span m=\"4313480\">is</span> <span m=\"4313900\">S-Z,</span>\
  \ <span m=\"4315070\">which</span> <span m=\"4315250\">we</span> <span m=\"4315370\"\
  >saw</span> <span m=\"4315640\">in</span> <span m=\"4316090\">Szemer\xE9di.</span>\
  \ <span m=\"4316870\">So</span> <span m=\"4316990\">this</span> <span m=\"4317200\"\
  >is</span> <span m=\"4317320\">pronounced</span> <span m=\"4317860\">like</span>\
  \ <span m=\"4318190\">/s/.</span> <span m=\"4318560\">Forget the</span> <span m=\"\
  4318930\">Z.</span></p><p><span m=\"4321275\">So</span> <span m=\"4321700\">Erdos,</span>\
  \ <span m=\"4326070\">another</span> <span m=\"4326340\">thing</span> <span m=\"\
  4326520\">about</span> <span m=\"4327010\">Erdos</span> <span m=\"4327340\">that</span>\
  \ <span m=\"4327480\">you</span> <span m=\"4327570\">should</span> <span m=\"4327720\"\
  >know</span> <span m=\"4328050\">is</span> <span m=\"4328260\">that--</span> <span\
  \ m=\"4329190\">what</span> <span m=\"4329370\">is</span> <span m=\"4329520\">this</span>\
  \ <span m=\"4329700\">accent?</span> <span m=\"4331530\">It is</span> <span m=\"\
  4331800\">not</span> <span m=\"4332070\">a</span> <span m=\"4332130\">double</span>\
  \ <span m=\"4332430\">dot.</span> <span m=\"4333502\">So</span> <span m=\"4333890\"\
  >in</span> <span m=\"4334080\">LaTeX</span> <span m=\"4334970\">you</span> <span\
  \ m=\"4335090\">would</span> <span m=\"4335240\">type</span> <span m=\"4335510\"\
  >it</span> <span m=\"4335650\">as</span> <span m=\"4335760\">slash</span> <span\
  \ m=\"4336500\">H,</span> <span m=\"4338730\">and in</span> <span m=\"4339200\"\
  >particular,</span> <span m=\"4340220\">not</span> <span m=\"4341750\">like</span>\
  \ <span m=\"4341930\">that.</span> <span m=\"4344460\">So</span> <span m=\"4344940\"\
  >just</span> <span m=\"4345260\">a</span> <span m=\"4345310\">few</span> <span m=\"\
  4346000\">cultural</span> <span m=\"4346360\">remarks</span> <span m=\"4348460\"\
  >about</span> <span m=\"4348790\">names.</span> <span m=\"4351535\">Great.</span>\
  \ <span m=\"4351820\">So</span> <span m=\"4352000\">we'll</span> <span m=\"4352150\"\
  >end</span> <span m=\"4352300\">today.</span> <span m=\"4352690\">And</span> <span\
  \ m=\"4352840\">then</span> <span m=\"4353410\">next</span> <span m=\"4353650\"\
  >time,</span> <span m=\"4353830\">we'll</span> <span m=\"4353980\">start</span>\
  \ <span m=\"4354370\">looking</span> <span m=\"4354910\">at</span> <span m=\"4355420\"\
  >other</span> <span m=\"4355750\">extremal</span> <span m=\"4356200\">numbers</span>\
  \ <span m=\"4356650\">for</span> <span m=\"4357460\">more</span> <span m=\"4358300\"\
  >bipartite</span> <span m=\"4358710\">graphs.</span></p>"
type: course
uid: aa8242411777a91b4d6684e6523f35b7

---
None