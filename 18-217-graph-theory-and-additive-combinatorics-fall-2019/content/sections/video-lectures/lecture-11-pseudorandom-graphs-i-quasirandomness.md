---
about_this_resource_text: "<p><strong>Description:</strong> Pseudorandom graphs are\
  \ graphs that behave like random graphs in certain prescribed ways. In this lecture,\
  \ Professor Zhao discusses a classic result of Chung, Graham, and Wilson, which\
  \ shows that many definitions of quasirandom graphs are surprisingly equivalent.\
  \ This result highlights the role of 4-cycles in pseudorandomness. The expander\
  \ mixing lemma is also discussed near the end of the lecture.\r\n\r\n</p>\r\n<p><strong>Instructor:</strong>\
  \ Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: TgPcNnUrE24
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  title: Video-YouTube-Stream
  type: Video
  uid: fb7d141f663f23381c59ced7fcc3e86a
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/TgPcNnUrE24/default.jpg
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 17dbe943ae18d4e56db6f5abf28b663c
- id: 3Play-3PlayYouTubeid-MP4
  media_location: TgPcNnUrE24
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 45e6253ff25ab0ec9b01fb3a2d438e2d
- id: TgPcNnUrE24.srt
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-11-pseudorandom-graphs-i-quasirandomness/TgPcNnUrE24.srt
  title: 3play caption file
  type: null
  uid: 776a878f15c637f03cec234921a1c5d9
- id: TgPcNnUrE24.pdf
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-11-pseudorandom-graphs-i-quasirandomness/TgPcNnUrE24.pdf
  title: 3play pdf file
  type: null
  uid: 733d56b5fa0ba8dfccee8f2f6f26c69c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 594a203f1667effa7c7894014a3f17e9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4a5cd9712bc48a8c48e1cbbb39629505
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec11_300k.mp4
  parent_uid: 2fbfd677578d0da2087d81966abe8aff
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3e2c2e85763888a2d21f969a53c9af90
inline_embed_id: 65551748lecture11pseudorandomgraphsiquasirandomness93882811
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-11-pseudorandom-graphs-i-quasirandomness
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-11-pseudorandom-graphs-i-quasirandomness
template_type: Tabbed
title: 'Lecture 11: Pseudorandom Graphs I: Quasirandomness'
transcript: "<p><span m=\"17680\">PROFESSOR:</span> <span m=\"17745\">So</span> <span\
  \ m=\"17810\">we</span> <span m=\"17990\">spent</span> <span m=\"18290\">the</span>\
  \ <span m=\"18380\">last</span> <span m=\"18710\">few</span> <span m=\"18890\">lectures</span>\
  \ <span m=\"19310\">discussing</span> <span m=\"19850\">Szemer\xE9di's</span> <span\
  \ m=\"20450\">regularity</span> <span m=\"20765\">lemma.</span> <span m=\"22100\"\
  >So</span> <span m=\"22130\">we</span> <span m=\"22250\">saw</span> <span m=\"22430\"\
  >that</span> <span m=\"22550\">this</span> <span m=\"22700\">is</span> <span m=\"\
  22820\">an</span> <span m=\"22880\">important</span> <span m=\"23270\">tool</span>\
  \ <span m=\"23540\">with</span> <span m=\"24290\">important</span> <span m=\"24650\"\
  >applications,</span> <span m=\"26220\">allowing</span> <span m=\"26450\">you</span>\
  \ <span m=\"26540\">to</span> <span m=\"26660\">do</span> <span m=\"26990\">things</span>\
  \ <span m=\"27620\">like</span> <span m=\"28250\">a</span> <span m=\"28330\">proof</span>\
  \ <span m=\"28640\">of</span> <span m=\"28790\">Roth's</span> <span m=\"29145\"\
  >theorem</span> <span m=\"29500\">via</span> <span m=\"29780\">graph</span> <span\
  \ m=\"30080\">theory.</span></p><p><span m=\"31640\">One</span> <span m=\"31910\"\
  >of</span> <span m=\"31970\">the</span> <span m=\"32090\">concepts</span> <span\
  \ m=\"32659\">that</span> <span m=\"32810\">came</span> <span m=\"33110\">up</span>\
  \ <span m=\"33830\">when</span> <span m=\"33980\">we</span> <span m=\"34100\">were</span>\
  \ <span m=\"34250\">discussing</span> <span m=\"34820\">the</span> <span m=\"34910\"\
  >statement</span> <span m=\"35690\">of</span> <span m=\"35870\">Szemer\xE9di's</span>\
  \ <span m=\"36650\">regularity</span> <span m=\"37080\">lemma</span> <span m=\"\
  37790\">is</span> <span m=\"37970\">that</span> <span m=\"38210\">of</span> <span\
  \ m=\"38330\">pseudorandomness.</span> <span m=\"39830\">So</span> <span m=\"40310\"\
  >the</span> <span m=\"40430\">statement</span> <span m=\"40940\">of</span> <span\
  \ m=\"41030\">Szemer\xE9di's</span> <span m=\"41990\">graph</span> <span m=\"42310\"\
  >regularity</span> <span m=\"42890\">lemma</span> <span m=\"43610\">is</span> <span\
  \ m=\"43820\">that</span> <span m=\"44480\">you</span> <span m=\"44600\">can</span>\
  \ <span m=\"45170\">partition</span> <span m=\"45950\">an</span> <span m=\"46070\"\
  >arbitrary</span> <span m=\"46550\">graph</span> <span m=\"47480\">into</span> <span\
  \ m=\"47840\">a</span> <span m=\"47930\">bounded</span> <span m=\"48380\">number</span>\
  \ <span m=\"48710\">of</span> <span m=\"48770\">pieces</span> <span m=\"49970\"\
  >so</span> <span m=\"50210\">that</span> <span m=\"50720\">the</span> <span m=\"\
  50810\">graph</span> <span m=\"51320\">looks</span> <span m=\"52400\">random-like,</span>\
  \ <span m=\"53630\">as</span> <span m=\"53810\">we</span> <span m=\"53930\">called</span>\
  \ <span m=\"54230\">it,</span> <span m=\"54650\">between</span> <span m=\"55070\"\
  >most</span> <span m=\"55730\">pairs</span> <span m=\"56120\">of</span> <span m=\"\
  56210\">parts.</span></p><p><span m=\"58040\">So</span> <span m=\"58160\">what</span>\
  \ <span m=\"58310\">does</span> <span m=\"58430\">random-like</span> <span m=\"\
  59180\">mean?</span> <span m=\"60710\">So</span> <span m=\"60830\">that's</span>\
  \ <span m=\"60980\">something</span> <span m=\"61250\">that</span> <span m=\"61330\"\
  >I</span> <span m=\"61370\">want</span> <span m=\"61510\">to</span> <span m=\"61600\"\
  >discuss</span> <span m=\"62040\">for the</span> <span m=\"62120\">next</span> <span\
  \ m=\"62360\">couple</span> <span m=\"62600\">of</span> <span m=\"62690\">lectures.</span>\
  \ <span m=\"65239\">And</span> <span m=\"65390\">this</span> <span m=\"65540\">is</span>\
  \ <span m=\"65660\">the</span> <span m=\"65780\">idea</span> <span m=\"66170\">of</span>\
  \ <span m=\"66290\">pseudorandomness,</span> <span m=\"78580\">which</span> <span\
  \ m=\"78840\">is</span> <span m=\"79110\">a</span> <span m=\"80310\">concept</span>\
  \ <span m=\"81330\">that</span> <span m=\"82580\">is</span> <span m=\"82860\">really</span>\
  \ <span m=\"83100\">prevalent</span> <span m=\"83580\">in</span> <span m=\"84210\"\
  >combinatorics,</span> <span m=\"85080\">in</span> <span m=\"85360\">theoretical</span>\
  \ <span m=\"85800\">computer</span> <span m=\"86130\">science,</span> <span m=\"\
  86880\">and</span> <span m=\"87060\">in</span> <span m=\"87120\">many</span> <span\
  \ m=\"87330\">different</span> <span m=\"87630\">areas.</span> <span m=\"88860\"\
  >And</span> <span m=\"89100\">what</span> <span m=\"89850\">pseudorandomness</span>\
  \ <span m=\"90690\">tries</span> <span m=\"90960\">to</span> <span m=\"91050\">capture</span>\
  \ <span m=\"92040\">is,</span> <span m=\"92550\">in</span> <span m=\"92700\">what</span>\
  \ <span m=\"92970\">ways</span> <span m=\"93840\">can</span> <span m=\"94070\">a</span>\
  \ <span m=\"94180\">non-random</span> <span m=\"95040\">object</span> <span m=\"\
  95910\">look</span> <span m=\"96300\">random?</span></p><p><span m=\"97270\">So</span>\
  \ <span m=\"97760\">before</span> <span m=\"98040\">diving</span> <span m=\"98370\"\
  >into</span> <span m=\"98640\">some</span> <span m=\"98880\">specific</span> <span\
  \ m=\"99330\">mathematics,</span> <span m=\"100230\">I</span> <span m=\"100320\"\
  >want</span> <span m=\"100470\">to</span> <span m=\"101490\">offer</span> <span\
  \ m=\"101730\">some</span> <span m=\"102060\">philosophical</span> <span m=\"102720\"\
  >remarks.</span> <span m=\"103530\">So</span> <span m=\"103650\">you</span> <span\
  \ m=\"103740\">might</span> <span m=\"103920\">know</span> <span m=\"104190\">that,</span>\
  \ <span m=\"105540\">on</span> <span m=\"105660\">a</span> <span m=\"105720\">computer,</span>\
  \ <span m=\"106110\">you</span> <span m=\"106590\">want</span> <span m=\"106800\"\
  >to</span> <span m=\"106890\">generate</span> <span m=\"107340\">a</span> <span\
  \ m=\"107400\">random</span> <span m=\"107730\">number.</span> <span m=\"108420\"\
  >Well,</span> <span m=\"108690\">you</span> <span m=\"108990\">type</span> <span\
  \ m=\"109320\">in</span> <span m=\"109500\">a</span> <span m=\"109600\">&quot;rand,&quot;</span>\
  \ <span m=\"110280\">and</span> <span m=\"110400\">it</span> <span m=\"110490\"\
  >gives</span> <span m=\"110730\">you</span> <span m=\"110790\">a</span> <span m=\"\
  110820\">random</span> <span m=\"111120\">number.</span></p><p><span m=\"111510\"\
  >But of</span> <span m=\"111660\">course,</span> <span m=\"113190\">that's</span>\
  \ <span m=\"114150\">not</span> <span m=\"114570\">necessarily</span> <span m=\"\
  115110\">true</span> <span m=\"115620\">randomness.</span> <span m=\"116450\">It</span>\
  \ <span m=\"116640\">came</span> <span m=\"117000\">from</span> <span m=\"117390\"\
  >some</span> <span m=\"118200\">pseudorandom</span> <span m=\"119010\">generator.</span>\
  \ <span m=\"120870\">Probably</span> <span m=\"121200\">there's</span> <span m=\"\
  121350\">some</span> <span m=\"121530\">seed</span> <span m=\"121980\">and</span>\
  \ <span m=\"122070\">some</span> <span m=\"122340\">complex-looking</span> <span\
  \ m=\"123210\">function</span> <span m=\"123930\">and</span> <span m=\"124140\"\
  >outputs</span> <span m=\"124560\">something</span> <span m=\"125130\">that</span>\
  \ <span m=\"126030\">you</span> <span m=\"126180\">couldn't</span> <span m=\"126510\"\
  >distinguish</span> <span m=\"127140\">from</span> <span m=\"127920\">random.</span>\
  \ <span m=\"129000\">But</span> <span m=\"129210\">it</span> <span m=\"129300\"\
  >might</span> <span m=\"129479\">not</span> <span m=\"129960\">actually</span> <span\
  \ m=\"130350\">be</span> <span m=\"130500\">random</span> <span m=\"130949\">but</span>\
  \ <span m=\"131050\">just</span> <span m=\"131130\">something</span> <span m=\"\
  131430\">that</span> <span m=\"131910\">looks,</span> <span m=\"132480\">in</span>\
  \ <span m=\"132600\">many</span> <span m=\"132840\">different</span> <span m=\"\
  133110\">ways,</span> <span m=\"133720\">like</span> <span m=\"133920\">random.</span></p><p><span\
  \ m=\"135730\">So</span> <span m=\"135940\">there</span> <span m=\"136090\">is</span>\
  \ <span m=\"136180\">this</span> <span m=\"136300\">concept</span> <span m=\"136780\"\
  >of</span> <span m=\"137110\">random.</span> <span m=\"137560\">You</span> <span\
  \ m=\"137650\">can</span> <span m=\"138070\">think</span> <span m=\"138290\">about\
  \ a</span> <span m=\"138490\">random</span> <span m=\"138990\">graph,</span> <span\
  \ m=\"139590\">right,</span> <span m=\"139840\">generate</span> <span m=\"140300\"\
  >this</span> <span m=\"140510\">Erdos-Renyi</span> <span m=\"141160\">random</span>\
  \ <span m=\"141490\">graph.</span> <span m=\"141910\">Every</span> <span m=\"142150\"\
  >edge</span> <span m=\"142390\">occurs</span> <span m=\"143140\">independently</span>\
  \ <span m=\"143770\">with</span> <span m=\"143920\">some</span> <span m=\"144100\"\
  >probability.</span></p><p><span m=\"145360\">But</span> <span m=\"145510\">I</span>\
  \ <span m=\"145570\">can</span> <span m=\"145750\">also</span> <span m=\"146050\"\
  >show</span> <span m=\"146290\">you</span> <span m=\"146410\">some</span> <span\
  \ m=\"146680\">graph,</span> <span m=\"147010\">some</span> <span m=\"147220\">specific</span>\
  \ <span m=\"147730\">graph,</span> <span m=\"148660\">which</span> <span m=\"148870\"\
  >I</span> <span m=\"148930\">say,</span> <span m=\"149260\">well,</span> <span m=\"\
  149530\">it's,</span> <span m=\"150400\">for</span> <span m=\"150670\">all</span>\
  \ <span m=\"151240\">intents</span> <span m=\"151660\">and</span> <span m=\"151780\"\
  >purposes,</span> <span m=\"152860\">just</span> <span m=\"153190\">as</span> <span\
  \ m=\"153430\">good</span> <span m=\"154570\">as</span> <span m=\"155350\">a</span>\
  \ <span m=\"155410\">random</span> <span m=\"155800\">graph.</span> <span m=\"158160\"\
  >So</span> <span m=\"158270\">in</span> <span m=\"158420\">what</span> <span m=\"\
  158660\">ways</span> <span m=\"159620\">can</span> <span m=\"159860\">we</span>\
  \ <span m=\"160430\">capture</span> <span m=\"160970\">that</span> <span m=\"161180\"\
  >concept?</span> <span m=\"162380\">So</span> <span m=\"162500\">that's</span> <span\
  \ m=\"162710\">what</span> <span m=\"162860\">I</span> <span m=\"162950\">want</span>\
  \ <span m=\"163100\">to</span> <span m=\"163190\">discuss.</span> <span m=\"164100\"\
  >And</span> <span m=\"164200\">that's</span> <span m=\"164300\">the</span> <span\
  \ m=\"164360\">topic</span> <span m=\"164750\">of</span> <span m=\"164870\">pseudorandomness.</span></p><p><span\
  \ m=\"166520\">And</span> <span m=\"166640\">of</span> <span m=\"166700\">course,</span>\
  \ <span m=\"166910\">well,</span> <span m=\"168170\">this</span> <span m=\"168380\"\
  >idea</span> <span m=\"168740\">extends</span> <span m=\"169250\">to</span> <span\
  \ m=\"169850\">many</span> <span m=\"170120\">areas,</span> <span m=\"170620\">number</span>\
  \ <span m=\"170960\">theory</span> <span m=\"171290\">and</span> <span m=\"171390\"\
  >whatnot,</span> <span m=\"171690\">but</span> <span m=\"171890\">we'll</span> <span\
  \ m=\"172070\">stick</span> <span m=\"172400\">with</span> <span m=\"172550\">graph</span>\
  \ <span m=\"172850\">theory.</span> <span m=\"173820\">In</span> <span m=\"173920\"\
  >particular,</span> <span m=\"174380\">I</span> <span m=\"174470\">want</span> <span\
  \ m=\"174650\">to</span> <span m=\"174770\">explore</span> <span m=\"175550\">today</span>\
  \ <span m=\"175850\">just</span> <span m=\"176270\">one</span> <span m=\"177140\"\
  >specific</span> <span m=\"177770\">notion</span> <span m=\"178220\">of</span> <span\
  \ m=\"178310\">pseudorandomness.</span> <span m=\"179660\">And</span> <span m=\"\
  179810\">this</span> <span m=\"181010\">comes</span> <span m=\"181310\">from</span>\
  \ <span m=\"181490\">an</span> <span m=\"181580\">important</span> <span m=\"182000\"\
  >paper</span> <span m=\"182930\">called</span> <span m=\"183200\">&quot;Quasi-random</span>\
  \ <span m=\"184100\">graphs.&quot;</span></p><p><span m=\"188790\">And</span> <span\
  \ m=\"189020\">this</span> <span m=\"189170\">concept</span> <span m=\"189650\"\
  >is</span> <span m=\"189860\">due</span> <span m=\"190010\">to</span> <span m=\"\
  190610\">Chung,</span> <span m=\"191120\">Graham,</span> <span m=\"191510\">and</span>\
  \ <span m=\"191600\">Wilson</span> <span m=\"192350\">back</span> <span m=\"192680\"\
  >in</span> <span m=\"192770\">the</span> <span m=\"192860\">late</span> <span m=\"\
  193100\">'80s.</span> <span m=\"203690\">So</span> <span m=\"203840\">they</span>\
  \ <span m=\"203990\">defined</span> <span m=\"204830\">various</span> <span m=\"\
  205370\">notions</span> <span m=\"206180\">of</span> <span m=\"206510\">pseudorandomness,</span>\
  \ <span m=\"208980\">and</span> <span m=\"209120\">I</span> <span m=\"209190\">want</span>\
  \ <span m=\"209400\">to</span> <span m=\"209460\">state</span> <span m=\"209760\"\
  >them.</span> <span m=\"210930\">And</span> <span m=\"211050\">what</span> <span\
  \ m=\"211230\">it</span> <span m=\"211290\">turns</span> <span m=\"211620\">out--</span>\
  \ <span m=\"212030\">and</span> <span m=\"212160\">the</span> <span m=\"212520\"\
  >surprising</span> <span m=\"213090\">part</span> <span m=\"213390\">is</span> <span\
  \ m=\"213540\">that</span> <span m=\"214080\">these</span> <span m=\"214920\">notions,</span>\
  \ <span m=\"215490\">these</span> <span m=\"215700\">definitions,</span> <span m=\"\
  216750\">although</span> <span m=\"217050\">they</span> <span m=\"217230\">look</span>\
  \ <span m=\"217560\">superficially</span> <span m=\"218880\">different,</span> <span\
  \ m=\"219690\">they</span> <span m=\"219870\">are</span> <span m=\"219990\">actually</span>\
  \ <span m=\"220470\">all</span> <span m=\"220680\">equivalent</span> <span m=\"\
  221310\">to</span> <span m=\"221490\">each</span> <span m=\"221700\">other.</span></p><p><span\
  \ m=\"223960\">So</span> <span m=\"223980\">let's</span> <span m=\"225450\">see</span>\
  \ <span m=\"225720\">what</span> <span m=\"225900\">the</span> <span m=\"225930\"\
  >theorem</span> <span m=\"226320\">says.</span> <span m=\"229050\">So</span> <span\
  \ m=\"229230\">the</span> <span m=\"229350\">set-up</span> <span m=\"229740\">of</span>\
  \ <span m=\"229830\">this</span> <span m=\"230040\">theorem</span> <span m=\"230580\"\
  >is</span> <span m=\"230730\">that</span> <span m=\"230880\">you</span> <span m=\"\
  231030\">have</span> <span m=\"231960\">some</span> <span m=\"232290\">fixed</span>\
  \ <span m=\"234090\">real</span> <span m=\"234450\">p</span> <span m=\"234810\"\
  >between</span> <span m=\"235200\">0</span> <span m=\"235530\">and</span> <span\
  \ m=\"235680\">1.</span> <span m=\"236640\">And</span> <span m=\"236790\">this</span>\
  \ <span m=\"236970\">is</span> <span m=\"237090\">going</span> <span m=\"237300\"\
  >to</span> <span m=\"237360\">be</span> <span m=\"237540\">your</span> <span m=\"\
  238080\">graph</span> <span m=\"238620\">edge</span> <span m=\"238920\">density.</span></p><p><span\
  \ m=\"240810\">So</span> <span m=\"241020\">for</span> <span m=\"244530\">any</span>\
  \ <span m=\"244770\">sequence</span> <span m=\"245640\">of</span> <span m=\"245820\"\
  >graphs,</span> <span m=\"250620\">Gn--</span> <span m=\"253660\">so</span> <span\
  \ m=\"254980\">from</span> <span m=\"255180\">now,</span> <span m=\"255430\">I'm</span>\
  \ <span m=\"255580\">going</span> <span m=\"255820\">to</span> <span m=\"255970\"\
  >drop</span> <span m=\"256329\">the</span> <span m=\"256420\">subscript</span> <span\
  \ m=\"259779\">n,</span> <span m=\"259940\">so</span> <span m=\"260110\">G</span>\
  \ <span m=\"260380\">will</span> <span m=\"260589\">just</span> <span m=\"260829\"\
  >be</span> <span m=\"261060\">Gn--</span> <span m=\"262600\">such</span> <span m=\"\
  262930\">that</span> <span m=\"264160\">the</span> <span m=\"264310\">number</span>\
  \ <span m=\"264730\">of</span> <span m=\"264880\">vertices--</span> <span m=\"267680\"\
  >so</span> <span m=\"268310\">G</span> <span m=\"268700\">is</span> <span m=\"270110\"\
  >n</span> <span m=\"270320\">vertex</span> <span m=\"273120\">with</span> <span\
  \ m=\"274950\">edge</span> <span m=\"275580\">density</span> <span m=\"276240\"\
  >basically</span> <span m=\"276840\">p.</span> <span m=\"282090\">So</span> <span\
  \ m=\"282310\">this</span> <span m=\"282510\">is</span> <span m=\"282620\">your</span>\
  \ <span m=\"282740\">sequence</span> <span m=\"283160\">of</span> <span m=\"283250\"\
  >graphs.</span></p><p><span m=\"284000\">And</span> <span m=\"284120\">the</span>\
  \ <span m=\"284210\">claim</span> <span m=\"285260\">is</span> <span m=\"285440\"\
  >that</span> <span m=\"287180\">we're</span> <span m=\"287330\">going</span> <span\
  \ m=\"287570\">to</span> <span m=\"287660\">state</span> <span m=\"289860\">some</span>\
  \ <span m=\"290250\">set</span> <span m=\"290460\">of</span> <span m=\"290550\"\
  >properties.</span> <span m=\"294260\">And</span> <span m=\"294370\">these</span>\
  \ <span m=\"294580\">properties</span> <span m=\"295120\">are</span> <span m=\"\
  295270\">all</span> <span m=\"295480\">going</span> <span m=\"295750\">to</span>\
  \ <span m=\"295870\">be</span> <span m=\"296440\">equivalent</span> <span m=\"297040\"\
  >to</span> <span m=\"297250\">each</span> <span m=\"297470\">other.</span> <span\
  \ m=\"303370\">So</span> <span m=\"303870\">all</span> <span m=\"303990\">of</span>\
  \ <span m=\"304050\">these</span> <span m=\"304260\">properties</span> <span m=\"\
  304770\">capture</span> <span m=\"305310\">some</span> <span m=\"305580\">notion</span>\
  \ <span m=\"306030\">of</span> <span m=\"306150\">pseudorandomness,</span> <span\
  \ m=\"307605\">so</span> <span m=\"308010\">in</span> <span m=\"308160\">what</span>\
  \ <span m=\"308340\">ways</span> <span m=\"308640\">this</span> <span m=\"308830\"\
  >is</span> <span m=\"308940\">graph</span> <span m=\"309240\">G</span> <span m=\"\
  309840\">or</span> <span m=\"309930\">really</span> <span m=\"310140\">a</span>\
  \ <span m=\"310200\">sequence</span> <span m=\"310680\">of</span> <span m=\"310770\"\
  >graphs.</span> <span m=\"311640\">Or</span> <span m=\"312210\">you</span> <span\
  \ m=\"312300\">can</span> <span m=\"312480\">talk</span> <span m=\"312750\">about</span>\
  \ <span m=\"312960\">a</span> <span m=\"313020\">specific</span> <span m=\"313500\"\
  >graph</span> <span m=\"313860\">and</span> <span m=\"313980\">have</span> <span\
  \ m=\"314220\">some</span> <span m=\"314550\">error</span> <span m=\"314790\">parameters</span>\
  \ <span m=\"315360\">and</span> <span m=\"315510\">error</span> <span m=\"315680\"\
  >balance.</span> <span m=\"315990\">They're</span> <span m=\"316170\">all</span>\
  \ <span m=\"316680\">roughly</span> <span m=\"316950\">the</span> <span m=\"317070\"\
  >same</span> <span m=\"317280\">ideas.</span></p><p><span m=\"319030\">So</span>\
  \ <span m=\"319050\">in</span> <span m=\"319170\">what</span> <span m=\"319350\"\
  >ways</span> <span m=\"319620\">can</span> <span m=\"319770\">we</span> <span m=\"\
  319890\">talk</span> <span m=\"320100\">about</span> <span m=\"320340\">this</span>\
  \ <span m=\"320490\">graph</span> <span m=\"320760\">G</span> <span m=\"321030\"\
  >being</span> <span m=\"321630\">random-like?</span> <span m=\"322600\">Well,</span>\
  \ <span m=\"322790\">we</span> <span m=\"322950\">already</span> <span m=\"323340\"\
  >saw</span> <span m=\"323670\">one</span> <span m=\"323940\">notion</span> <span\
  \ m=\"324810\">when</span> <span m=\"324990\">we</span> <span m=\"325110\">discussed</span>\
  \ <span m=\"326570\">Szemer\xE9di's</span> <span m=\"327210\">regularity</span>\
  \ <span m=\"327850\">lemma.</span> <span m=\"328530\">And</span> <span m=\"329760\"\
  >let's</span> <span m=\"329970\">see</span> <span m=\"330210\">that</span> <span\
  \ m=\"330420\">here.</span> <span m=\"330700\">So</span> <span m=\"330720\">this</span>\
  \ <span m=\"330990\">notion</span> <span m=\"331410\">is</span> <span m=\"331970\"\
  >known</span> <span m=\"332250\">as</span> <span m=\"332430\">discrepancy.</span>\
  \ <span m=\"333930\">And</span> <span m=\"334080\">it</span> <span m=\"334140\"\
  >says</span> <span m=\"334500\">that</span> <span m=\"334800\">if</span> <span m=\"\
  334980\">I</span> <span m=\"335430\">restrict</span> <span m=\"335970\">my</span>\
  \ <span m=\"336180\">graph</span> <span m=\"337320\">to</span> <span m=\"338610\"\
  >looking</span> <span m=\"338940\">only</span> <span m=\"339270\">at</span> <span\
  \ m=\"339480\">edges</span> <span m=\"339870\">between</span> <span m=\"340710\"\
  >some</span> <span m=\"340980\">pair</span> <span m=\"341400\">of</span> <span m=\"\
  341730\">vertex</span> <span m=\"342180\">sets,</span> <span m=\"342990\">then</span>\
  \ <span m=\"343150\">the</span> <span m=\"343210\">number</span> <span m=\"343620\"\
  >of</span> <span m=\"343800\">edges</span> <span m=\"345390\">should</span> <span\
  \ m=\"345690\">be</span> <span m=\"346200\">roughly</span> <span m=\"346680\">what</span>\
  \ <span m=\"346860\">you</span> <span m=\"346950\">would</span> <span m=\"347070\"\
  >expect</span> <span m=\"347940\">based</span> <span m=\"348360\">on</span> <span\
  \ m=\"348720\">density</span> <span m=\"349410\">alone.</span></p><p><span m=\"\
  357820\">So</span> <span m=\"357970\">this</span> <span m=\"358180\">is</span> <span\
  \ m=\"358300\">basically</span> <span m=\"358720\">the</span> <span m=\"358810\"\
  >notion</span> <span m=\"359150\">that</span> <span m=\"359230\">came</span> <span\
  \ m=\"359500\">up</span> <span m=\"360040\">in</span> <span m=\"360820\">epsilon</span>\
  \ <span m=\"361270\">regularity.</span> <span m=\"362050\">This</span> <span m=\"\
  362290\">is</span> <span m=\"363220\">essentially</span> <span m=\"363730\">the</span>\
  \ <span m=\"363820\">same</span> <span m=\"364180\">as</span> <span m=\"364270\"\
  >saying</span> <span m=\"364720\">that</span> <span m=\"365740\">G</span> <span\
  \ m=\"366430\">is</span> <span m=\"367210\">epsilon</span> <span m=\"367600\">regular</span>\
  \ <span m=\"368020\">with</span> <span m=\"368240\">itself</span> <span m=\"369310\"\
  >where</span> <span m=\"369460\">this</span> <span m=\"369940\">epsilon</span> <span\
  \ m=\"370390\">now</span> <span m=\"371060\">is</span> <span m=\"371800\">hidden</span>\
  \ <span m=\"372220\">in</span> <span m=\"372370\">this</span> <span m=\"372580\"\
  >little</span> <span m=\"372850\">o</span> <span m=\"373000\">parameter.</span></p><p><span\
  \ m=\"375890\">So</span> <span m=\"375910\">that's</span> <span m=\"376120\">one</span>\
  \ <span m=\"376300\">notion</span> <span m=\"376630\">of</span> <span m=\"376720\"\
  >pseudorandomness.</span> <span m=\"378360\">So</span> <span m=\"378510\">here's</span>\
  \ <span m=\"378790\">another</span> <span m=\"379090\">notion</span> <span m=\"\
  379420\">which</span> <span m=\"379630\">is</span> <span m=\"380440\">very</span>\
  \ <span m=\"380710\">similar.</span> <span m=\"383000\">So</span> <span m=\"383150\"\
  >it's</span> <span m=\"383500\">almost</span> <span m=\"383860\">just</span> <span\
  \ m=\"384100\">a</span> <span m=\"384160\">semantic</span> <span m=\"384700\">difference,</span>\
  \ <span m=\"385310\">but,</span> <span m=\"385640\">OK,</span> <span m=\"385780\"\
  >so I</span> <span m=\"386050\">have</span> <span m=\"386190\">to</span> <span m=\"\
  386400\">do</span> <span m=\"386560\">a</span> <span m=\"386590\">little</span>\
  \ <span m=\"386770\">bit</span> <span m=\"386890\">of</span> <span m=\"386950\"\
  >work.</span></p><p><span m=\"387530\">So</span> <span m=\"387580\">let</span> <span\
  \ m=\"387670\">me</span> <span m=\"387760\">call</span> <span m=\"387940\">this</span>\
  \ <span m=\"388130\">DISC</span> <span m=\"388450\">prime.</span> <span m=\"389440\"\
  >So</span> <span m=\"389650\">it</span> <span m=\"389770\">says</span> <span m=\"\
  390100\">that</span> <span m=\"390670\">if</span> <span m=\"390820\">you</span>\
  \ <span m=\"390940\">look</span> <span m=\"391150\">at</span> <span m=\"391510\"\
  >only</span> <span m=\"394280\">edges</span> <span m=\"394910\">within</span> <span\
  \ m=\"395320\">this</span> <span m=\"395420\">set--</span> <span m=\"395730\">so</span>\
  \ <span m=\"395900\">instead</span> <span m=\"396200\">of</span> <span m=\"396260\"\
  >taking</span> <span m=\"396560\">two</span> <span m=\"396800\">sets,</span> <span\
  \ m=\"397270\">I</span> <span m=\"397400\">only</span> <span m=\"397520\">look</span>\
  \ <span m=\"397730\">at</span> <span m=\"397820\">one</span> <span m=\"398090\"\
  >set--</span> <span m=\"398840\">and</span> <span m=\"398960\">then</span> <span\
  \ m=\"399320\">look</span> <span m=\"399560\">at</span> <span m=\"399920\">how</span>\
  \ <span m=\"400100\">many</span> <span m=\"400940\">edges</span> <span m=\"401270\"\
  >are</span> <span m=\"401440\">in</span> <span m=\"401540\">there</span> <span m=\"\
  402140\">versus</span> <span m=\"402470\">how</span> <span m=\"402650\">many</span>\
  \ <span m=\"402920\">you</span> <span m=\"403130\">should</span> <span m=\"403400\"\
  >expect</span> <span m=\"404120\">based</span> <span m=\"404480\">on</span> <span\
  \ m=\"404630\">density</span> <span m=\"405170\">alone,</span> <span m=\"408120\"\
  >these</span> <span m=\"408300\">two</span> <span m=\"408450\">numbers</span> <span\
  \ m=\"410050\">are</span> <span m=\"410440\">also</span> <span m=\"410940\">very</span>\
  \ <span m=\"411210\">similar</span> <span m=\"411660\">to</span> <span m=\"411840\"\
  >each</span> <span m=\"412020\">other.</span></p><p><span m=\"420730\">So</span>\
  \ <span m=\"420750\">let's</span> <span m=\"420930\">get</span> <span m=\"421060\"\
  >to</span> <span m=\"421140\">something</span> <span m=\"421440\">that</span> <span\
  \ m=\"421860\">looks</span> <span m=\"422580\">dramatically</span> <span m=\"423180\"\
  >different.</span> <span m=\"424890\">The</span> <span m=\"424980\">next</span>\
  \ <span m=\"425280\">one,</span> <span m=\"426540\">I'm</span> <span m=\"426660\"\
  >going</span> <span m=\"426840\">to</span> <span m=\"426900\">call</span> <span\
  \ m=\"427410\">count.</span> <span m=\"429940\">So</span> <span m=\"430130\">count</span>\
  \ <span m=\"430700\">says</span> <span m=\"431240\">that</span> <span m=\"431990\"\
  >for</span> <span m=\"432200\">every</span> <span m=\"433160\">graph</span> <span\
  \ m=\"434480\">H,</span> <span m=\"436310\">the</span> <span m=\"436780\">number</span>\
  \ <span m=\"437410\">of</span> <span m=\"439880\">labeled</span> <span m=\"441050\"\
  >copies</span> <span m=\"441590\">of</span> <span m=\"441710\">H</span> <span m=\"\
  445864\">in</span> <span m=\"446350\">G--</span> <span m=\"448380\">OK, so</span>\
  \ <span m=\"448640\">labeled</span> <span m=\"449140\">copies,</span> <span m=\"\
  449670\">I</span> <span m=\"449760\">mean</span> <span m=\"450030\">that</span>\
  \ <span m=\"450300\">the</span> <span m=\"450600\">vertices</span> <span m=\"451200\"\
  >of</span> <span m=\"451350\">H</span> <span m=\"451620\">are</span> <span m=\"\
  451770\">labeled.</span> <span m=\"453070\">So</span> <span m=\"454550\">for</span>\
  \ <span m=\"454740\">every</span> <span m=\"454920\">triangle,</span> <span m=\"\
  455370\">there</span> <span m=\"455480\">are</span> <span m=\"455550\">six</span>\
  \ <span m=\"456180\">labeled</span> <span m=\"456530\">triangles</span> <span m=\"\
  457350\">that</span> <span m=\"457500\">correspond</span> <span m=\"457980\">to</span>\
  \ <span m=\"458070\">that</span> <span m=\"458430\">triangle</span> <span m=\"458880\"\
  >in</span> <span m=\"459000\">the</span> <span m=\"459060\">graph.</span></p><p><span\
  \ m=\"460530\">The</span> <span m=\"460680\">number</span> <span m=\"460920\">of</span>\
  \ <span m=\"461040\">labeled</span> <span m=\"461400\">copies</span> <span m=\"\
  461820\">of</span> <span m=\"461940\">H</span> <span m=\"462780\">is--</span> <span\
  \ m=\"464790\">so</span> <span m=\"464910\">what</span> <span m=\"465060\">should</span>\
  \ <span m=\"465270\">you</span> <span m=\"465420\">expect</span> <span m=\"466080\"\
  >if</span> <span m=\"466260\">this</span> <span m=\"466470\">graph</span> <span\
  \ m=\"466770\">were</span> <span m=\"466860\">truly</span> <span m=\"467250\">random?</span>\
  \ <span m=\"468110\">You would</span> <span m=\"468270\">expect</span> <span m=\"\
  468900\">p</span> <span m=\"469300\">raised</span> <span m=\"469680\">to</span>\
  \ <span m=\"469800\">the</span> <span m=\"469860\">number</span> <span m=\"470190\"\
  >of</span> <span m=\"470400\">edges</span> <span m=\"470760\">of</span> <span m=\"\
  470850\">H</span> <span m=\"471900\">plus</span> <span m=\"472620\">small</span>\
  \ <span m=\"473100\">error</span> <span m=\"473780\">times</span> <span m=\"474120\"\
  >n</span> <span m=\"475530\">raised</span> <span m=\"475850\">to</span> <span m=\"\
  475950\">number</span> <span m=\"476280\">of</span> <span m=\"476670\">vertices</span>\
  \ <span m=\"477330\">of</span> <span m=\"477510\">H.</span> <span m=\"481530\">And</span>\
  \ <span m=\"481680\">just</span> <span m=\"481980\">as</span> <span m=\"482130\"\
  >a</span> <span m=\"482550\">remark,</span> <span m=\"483510\">this</span> <span\
  \ m=\"484850\">little</span> <span m=\"485260\">o</span> <span m=\"485440\">term,</span>\
  \ <span m=\"487040\">little o</span> <span m=\"487420\">1</span> <span m=\"487720\"\
  >term,</span> <span m=\"489710\">may</span> <span m=\"490280\">depend</span> <span\
  \ m=\"490730\">on</span> <span m=\"490910\">H.</span></p><p><span m=\"495600\">So</span>\
  \ <span m=\"495860\">this</span> <span m=\"496100\">condition,</span> <span m=\"\
  496550\">count,</span> <span m=\"497060\">says</span> <span m=\"497270\">for</span>\
  \ <span m=\"497570\">every</span> <span m=\"497870\">graph</span> <span m=\"498230\"\
  >H,</span> <span m=\"499340\">this</span> <span m=\"499520\">is</span> <span m=\"\
  499610\">true.</span> <span m=\"500540\">And</span> <span m=\"501500\">by</span>\
  \ <span m=\"501650\">that,</span> <span m=\"501860\">I</span> <span m=\"501920\"\
  >mean</span> <span m=\"502160\">for</span> <span m=\"502340\">every</span> <span\
  \ m=\"502640\">H,</span> <span m=\"503240\">there</span> <span m=\"503420\">is</span>\
  \ <span m=\"503510\">some</span> <span m=\"503930\">sequence</span> <span m=\"504440\"\
  >of</span> <span m=\"504530\">decaying</span> <span m=\"505040\">errors.</span>\
  \ <span m=\"505480\">But</span> <span m=\"505640\">that</span> <span m=\"505850\"\
  >sequence</span> <span m=\"506300\">of</span> <span m=\"506390\">decaying</span>\
  \ <span m=\"506780\">errors</span> <span m=\"507320\">may</span> <span m=\"507500\"\
  >depend</span> <span m=\"507980\">on</span> <span m=\"508160\">your</span> <span\
  \ m=\"508370\">graph</span> <span m=\"508670\">H.</span> <span m=\"512842\">OK.</span></p><p><span\
  \ m=\"514789\">The</span> <span m=\"514880\">next</span> <span m=\"515210\">one</span>\
  \ <span m=\"515870\">is</span> <span m=\"516470\">almost</span> <span m=\"516919\"\
  >a</span> <span m=\"516950\">special</span> <span m=\"517400\">case</span> <span\
  \ m=\"517760\">of</span> <span m=\"517850\">count.</span> <span m=\"518809\">It's</span>\
  \ <span m=\"519000\">called</span> <span m=\"519200\">C4.</span> <span m=\"521940\"\
  >And</span> <span m=\"522100\">it says</span> <span m=\"522480\">that</span> <span\
  \ m=\"522659\">the</span> <span m=\"522780\">number</span> <span m=\"523320\">of</span>\
  \ <span m=\"523710\">labeled</span> <span m=\"525060\">copies</span> <span m=\"\
  525600\">of</span> <span m=\"525690\">C4,</span> <span m=\"526230\">so</span> <span\
  \ m=\"526500\">the</span> <span m=\"526590\">fourth</span> <span m=\"526820\">cycle,</span>\
  \ <span m=\"533950\">is</span> <span m=\"534850\">at</span> <span m=\"534970\">most</span>\
  \ <span m=\"536520\">p</span> <span m=\"537110\">raised</span> <span m=\"537210\"\
  >to</span> <span m=\"537580\">power of</span> <span m=\"537870\">4--</span> <span\
  \ m=\"539410\">so</span> <span m=\"539530\">again,</span> <span m=\"539800\">what</span>\
  \ <span m=\"540040\">you</span> <span m=\"540160\">should</span> <span m=\"540430\"\
  >expect</span> <span m=\"541360\">in</span> <span m=\"541690\">a</span> <span m=\"\
  541810\">random</span> <span m=\"542350\">setting</span> <span m=\"545510\">just</span>\
  \ <span m=\"545810\">for</span> <span m=\"546050\">cycle</span> <span m=\"546410\"\
  >count</span> <span m=\"546760\">alone.</span></p><p><span m=\"551740\">I</span>\
  \ <span m=\"551930\">see,</span> <span m=\"552180\">already,</span> <span m=\"552910\"\
  >some</span> <span m=\"553170\">of</span> <span m=\"553260\">you</span> <span m=\"\
  553590\">are</span> <span m=\"554640\">surprised.</span> <span m=\"555600\">So</span>\
  \ <span m=\"555900\">we'll</span> <span m=\"556170\">discuss</span> <span m=\"556710\"\
  >that</span> <span m=\"557250\">this</span> <span m=\"557430\">is</span> <span m=\"\
  557550\">an</span> <span m=\"557610\">important</span> <span m=\"558720\">constraint.</span>\
  \ <span m=\"559590\">It</span> <span m=\"559650\">turns</span> <span m=\"559920\"\
  >out</span> <span m=\"560670\">that</span> <span m=\"560970\">alone</span> <span\
  \ m=\"561270\">implies</span> <span m=\"561750\">everything,</span> <span m=\"562290\"\
  >just</span> <span m=\"562500\">having</span> <span m=\"562770\">the</span> <span\
  \ m=\"562860\">correct</span> <span m=\"563220\">C4</span> <span m=\"563720\">count.</span></p><p><span\
  \ m=\"567730\">The</span> <span m=\"567820\">next</span> <span m=\"568150\">one,</span>\
  \ <span m=\"568890\">we</span> <span m=\"569390\">will</span> <span m=\"569500\"\
  >call</span> <span m=\"569770\">codegree.</span> <span m=\"571720\">And</span> <span\
  \ m=\"571810\">the</span> <span m=\"571870\">codegree</span> <span m=\"572340\"\
  >condition</span> <span m=\"574160\">says</span> <span m=\"574520\">that</span>\
  \ <span m=\"575750\">if</span> <span m=\"575900\">you</span> <span m=\"575990\"\
  >look</span> <span m=\"576290\">at</span> <span m=\"577010\">a</span> <span m=\"\
  577070\">pair</span> <span m=\"577550\">of</span> <span m=\"577730\">vertices</span>\
  \ <span m=\"579290\">and</span> <span m=\"579410\">look</span> <span m=\"579620\"\
  >at</span> <span m=\"580290\">their</span> <span m=\"580440\">number</span> <span\
  \ m=\"580940\">of</span> <span m=\"581060\">common</span> <span m=\"581420\">neighbors--</span>\
  \ <span m=\"582400\">in</span> <span m=\"582610\">other</span> <span m=\"582700\"\
  >words,</span> <span m=\"582840\">their</span> <span m=\"583080\">codegree--</span>\
  \ <span m=\"585460\">then</span> <span m=\"586340\">what</span> <span m=\"586540\"\
  >should</span> <span m=\"586720\">you</span> <span m=\"586840\">expect</span> <span\
  \ m=\"587290\">this</span> <span m=\"587470\">quantity</span> <span m=\"587890\"\
  >to</span> <span m=\"588010\">be?</span> <span m=\"589020\">So</span> <span m=\"\
  589480\">there</span> <span m=\"589690\">are</span> <span m=\"590200\">n</span>\
  \ <span m=\"590380\">vertices</span> <span m=\"590890\">that</span> <span m=\"591460\"\
  >possibly</span> <span m=\"591880\">could</span> <span m=\"592090\">be</span> <span\
  \ m=\"592200\">common</span> <span m=\"592550\">neighbors,</span> <span m=\"593650\"\
  >and</span> <span m=\"593890\">each</span> <span m=\"594160\">one</span> <span m=\"\
  594370\">of</span> <span m=\"594430\">them,</span> <span m=\"595780\">if</span>\
  \ <span m=\"596050\">this</span> <span m=\"596230\">were a</span> <span m=\"596370\"\
  >random</span> <span m=\"596800\">graph</span> <span m=\"597100\">with</span> <span\
  \ m=\"597280\">edge</span> <span m=\"597490\">probability</span> <span m=\"598090\"\
  >p,</span> <span m=\"598730\">then</span> <span m=\"598840\">you</span> <span m=\"\
  598960\">expect</span> <span m=\"599680\">the</span> <span m=\"599770\">number</span>\
  \ <span m=\"600160\">of</span> <span m=\"600280\">common</span> <span m=\"600580\"\
  >neighbors</span> <span m=\"600940\">to</span> <span m=\"601030\">be</span> <span\
  \ m=\"601150\">around</span> <span m=\"601390\">p</span> <span m=\"602500\">squared</span>\
  \ <span m=\"602890\">n.</span></p><p><span m=\"603950\">So</span> <span m=\"604030\"\
  >the</span> <span m=\"604120\">codegree</span> <span m=\"604660\">condition</span>\
  \ <span m=\"605590\">is</span> <span m=\"605800\">that</span> <span m=\"606610\"\
  >this</span> <span m=\"607840\">sum</span> <span m=\"608740\">is</span> <span m=\"\
  609220\">small.</span> <span m=\"610240\">So</span> <span m=\"610570\">most</span>\
  \ <span m=\"611620\">pairs</span> <span m=\"611980\">of</span> <span m=\"612040\"\
  >vertices</span> <span m=\"613000\">have</span> <span m=\"613420\">roughly</span>\
  \ <span m=\"613840\">the</span> <span m=\"613960\">correct</span> <span m=\"614440\"\
  >number</span> <span m=\"614800\">of</span> <span m=\"615040\">common</span> <span\
  \ m=\"615580\">neighbors.</span> <span m=\"620213\">So</span> <span m=\"621620\"\
  >codegree</span> <span m=\"622670\">is</span> <span m=\"623350\">number</span> <span\
  \ m=\"623710\">of</span> <span m=\"624100\">common</span> <span m=\"626860\">neighbors.</span></p><p><span\
  \ m=\"631180\">Next,</span> <span m=\"632270\">and</span> <span m=\"632350\">the</span>\
  \ <span m=\"632410\">last</span> <span m=\"632710\">one,</span> <span m=\"633610\"\
  >certainly</span> <span m=\"633940\">not</span> <span m=\"634150\">the</span> <span\
  \ m=\"634210\">least,</span> <span m=\"634990\">is</span> <span m=\"635920\">eigenvalue</span>\
  \ <span m=\"636460\">condition.</span> <span m=\"639130\">So</span> <span m=\"639150\"\
  >here,</span> <span m=\"639570\">we</span> <span m=\"639840\">are</span> <span m=\"\
  640650\">going</span> <span m=\"640950\">to</span> <span m=\"641730\">denote</span>\
  \ <span m=\"642990\">by</span> <span m=\"645500\">lambda</span> <span m=\"648960\"\
  >1</span> <span m=\"649280\">through</span> <span m=\"649450\">lambda</span> <span\
  \ m=\"649870\">G</span> <span m=\"650410\">the</span> <span m=\"650890\">eigenvalues</span>\
  \ <span m=\"653980\">of</span> <span m=\"654250\">the</span> <span m=\"654370\"\
  >adjacency</span> <span m=\"654910\">matrix</span> <span m=\"656890\">of</span>\
  \ <span m=\"657040\">G.</span> <span m=\"658130\">So</span> <span m=\"658290\">we</span>\
  \ <span m=\"658420\">saw</span> <span m=\"658630\">this</span> <span m=\"658810\"\
  >object</span> <span m=\"659370\">in</span> <span m=\"659470\">the</span> <span\
  \ m=\"659560\">last</span> <span m=\"659860\">lecture.</span> <span m=\"661520\"\
  >So</span> <span m=\"662380\">I</span> <span m=\"662800\">include</span> <span m=\"\
  663160\">multiplicities.</span> <span m=\"663940\">If</span> <span m=\"664060\"\
  >some</span> <span m=\"664430\">eigenvalue</span> <span m=\"665000\">occurs</span>\
  \ <span m=\"665350\">with</span> <span m=\"665530\">multiple</span> <span m=\"665890\"\
  >times,</span> <span m=\"666320\">I</span> <span m=\"666420\">include it</span>\
  \ <span m=\"666790\">multiple</span> <span m=\"667150\">times.</span></p><p><span\
  \ m=\"668920\">So</span> <span m=\"669080\">the</span> <span m=\"669170\">eigenvalue</span>\
  \ <span m=\"669730\">condition</span> <span m=\"670900\">says</span> <span m=\"\
  671290\">that</span> <span m=\"672040\">the</span> <span m=\"672270\">top</span>\
  \ <span m=\"672670\">eigenvalue</span> <span m=\"673870\">is</span> <span m=\"675280\"\
  >around</span> <span m=\"677250\">pn</span> <span m=\"679370\">and</span> <span\
  \ m=\"679520\">that,</span> <span m=\"680130\">more</span> <span m=\"680210\">importantly,</span>\
  \ <span m=\"681720\">the</span> <span m=\"682160\">other</span> <span m=\"682460\"\
  >eigenvalues</span> <span m=\"689120\">are</span> <span m=\"689270\">all</span>\
  \ <span m=\"689930\">quite</span> <span m=\"690380\">small.</span> <span m=\"695810\"\
  >Now,</span> <span m=\"695990\">for</span> <span m=\"696260\">d</span> <span m=\"\
  696530\">regular</span> <span m=\"696980\">graph,</span> <span m=\"697840\">the</span>\
  \ <span m=\"697940\">top</span> <span m=\"698260\">eigenvalue--</span> <span m=\"\
  699470\">and</span> <span m=\"699710\">it's</span> <span m=\"699860\">fine</span>\
  \ <span m=\"700100\">to</span> <span m=\"700220\">think</span> <span m=\"700400\"\
  >about</span> <span m=\"700610\">d</span> <span m=\"700750\">regular</span> <span\
  \ m=\"701120\">graphs</span> <span m=\"701990\">if</span> <span m=\"702110\">you</span>\
  \ <span m=\"702500\">want</span> <span m=\"702710\">to</span> <span m=\"703220\"\
  >get</span> <span m=\"703370\">some</span> <span m=\"703520\">intuition</span> <span\
  \ m=\"704030\">out</span> <span m=\"704140\">of</span> <span m=\"704240\">this</span>\
  \ <span m=\"704420\">theorem.</span> <span m=\"704990\">For</span> <span m=\"705170\"\
  >d</span> <span m=\"705350\">regular</span> <span m=\"705710\">graph,</span> <span\
  \ m=\"705930\">the</span> <span m=\"706010\">top</span> <span m=\"706280\">eigenvalue</span>\
  \ <span m=\"707360\">is</span> <span m=\"707530\">equal</span> <span m=\"707750\"\
  >to</span> <span m=\"707900\">d,</span> <span m=\"709100\">because</span> <span\
  \ m=\"710090\">the</span> <span m=\"710180\">top</span> <span m=\"710480\">eigenvector</span>\
  \ <span m=\"711220\">is</span> <span m=\"711530\">d.</span> <span m=\"712860\">It's</span>\
  \ <span m=\"713170\">the</span> <span m=\"713300\">all-one</span> <span m=\"713660\"\
  >vector.</span></p><p><span m=\"716000\">So</span> <span m=\"716350\">top</span>\
  \ <span m=\"717400\">eigenvector</span> <span m=\"720190\">is</span> <span m=\"\
  720770\">all-one</span> <span m=\"721150\">vector,</span> <span m=\"723370\">which</span>\
  \ <span m=\"723580\">has</span> <span m=\"723870\">eigenvalue</span> <span m=\"\
  727336\">d.</span> <span m=\"729180\">And</span> <span m=\"729930\">what the</span>\
  \ <span m=\"730230\">eigenvalue</span> <span m=\"731010\">condition</span> <span\
  \ m=\"733710\">says</span> <span m=\"734310\">is</span> <span m=\"734490\">that</span>\
  \ <span m=\"735600\">all</span> <span m=\"735780\">the</span> <span m=\"735930\"\
  >other</span> <span m=\"736440\">eigenvalues</span> <span m=\"742480\">are</span>\
  \ <span m=\"746510\">much</span> <span m=\"746750\">smaller.</span> <span m=\"747710\"\
  >So</span> <span m=\"747830\">here,</span> <span m=\"748070\">I'm</span> <span m=\"\
  748160\">thinking</span> <span m=\"748490\">of</span> <span m=\"748580\">d</span>\
  \ <span m=\"748850\">as</span> <span m=\"749150\">on</span> <span m=\"749270\">the</span>\
  \ <span m=\"749360\">same</span> <span m=\"749660\">order</span> <span m=\"750120\"\
  >as</span> <span m=\"750300\">n.</span></p><p><span m=\"753010\">OK,</span> <span\
  \ m=\"753300\">so</span> <span m=\"753450\">this</span> <span m=\"753630\">is</span>\
  \ <span m=\"753750\">the</span> <span m=\"753810\">theorem.</span> <span m=\"755200\"\
  >So</span> <span m=\"755250\">that's</span> <span m=\"755460\">what</span> <span\
  \ m=\"755580\">we'll</span> <span m=\"755760\">do</span> <span m=\"755880\">today.</span>\
  \ <span m=\"756150\">We'll</span> <span m=\"756300\">prove</span> <span m=\"756960\"\
  >that</span> <span m=\"757170\">all</span> <span m=\"757350\">of</span> <span m=\"\
  757470\">these</span> <span m=\"758490\">properties</span> <span m=\"759090\">are</span>\
  \ <span m=\"759270\">equivalent</span> <span m=\"759870\">to</span> <span m=\"760050\"\
  >each</span> <span m=\"760230\">other.</span> <span m=\"761420\">And</span> <span\
  \ m=\"761610\">all</span> <span m=\"761760\">of</span> <span m=\"761820\">these</span>\
  \ <span m=\"762000\">properties,</span> <span m=\"762450\">you</span> <span m=\"\
  762540\">should</span> <span m=\"762690\">think</span> <span m=\"762930\">of</span>\
  \ <span m=\"763350\">as</span> <span m=\"763530\">characterizations</span> <span\
  \ m=\"764580\">of</span> <span m=\"764670\">pseudorandomness.</span></p><p><span\
  \ m=\"765860\">And</span> <span m=\"765930\">of</span> <span m=\"765990\">course,</span>\
  \ <span m=\"766200\">this</span> <span m=\"766380\">theorem</span> <span m=\"766830\"\
  >guarantees</span> <span m=\"767340\">us</span> <span m=\"767520\">that</span> <span\
  \ m=\"768170\">it</span> <span m=\"768240\">doesn't</span> <span m=\"768660\">matter</span>\
  \ <span m=\"769140\">which</span> <span m=\"769440\">one</span> <span m=\"769650\"\
  >you</span> <span m=\"769740\">use.</span> <span m=\"770070\">They're</span> <span\
  \ m=\"770220\">all</span> <span m=\"770370\">equivalent</span> <span m=\"770850\"\
  >to</span> <span m=\"770970\">each</span> <span m=\"771150\">other.</span> <span\
  \ m=\"771890\">And</span> <span m=\"772590\">our</span> <span m=\"772740\">proofs</span>\
  \ <span m=\"773130\">are</span> <span m=\"773310\">actually</span> <span m=\"773640\"\
  >going</span> <span m=\"773850\">to</span> <span m=\"773940\">be--</span> <span\
  \ m=\"774780\">I</span> <span m=\"774840\">mean,</span> <span m=\"774990\">I'm</span>\
  \ <span m=\"775080\">going</span> <span m=\"775220\">to</span> <span m=\"775290\"\
  >try</span> <span m=\"775440\">to</span> <span m=\"775530\">do</span> <span m=\"\
  775650\">everything</span> <span m=\"775980\">fairly</span> <span m=\"776280\">slowly.</span>\
  \ <span m=\"776730\">But</span> <span m=\"776850\">none</span> <span m=\"777030\"\
  >of</span> <span m=\"777120\">these</span> <span m=\"777300\">proofs</span> <span\
  \ m=\"777570\">are</span> <span m=\"777660\">difficult.</span> <span m=\"778450\"\
  >We're</span> <span m=\"778500\">not</span> <span m=\"778680\">going</span> <span\
  \ m=\"778830\">to</span> <span m=\"778920\">use</span> <span m=\"779220\">any</span>\
  \ <span m=\"779430\">fancy</span> <span m=\"779820\">tools</span> <span m=\"780180\"\
  >like</span> <span m=\"780390\">Szemer\xE9di's</span> <span m=\"780870\">regularity</span>\
  \ <span m=\"781410\">lemma.</span></p><p><span m=\"782100\">In</span> <span m=\"\
  782190\">particular,</span> <span m=\"783630\">all</span> <span m=\"783840\">of</span>\
  \ <span m=\"783930\">these</span> <span m=\"784470\">quantitative</span> <span m=\"\
  785130\">errors</span> <span m=\"786000\">are</span> <span m=\"787050\">reasonably</span>\
  \ <span m=\"787560\">dependent</span> <span m=\"788040\">on</span> <span m=\"788130\"\
  >each</span> <span m=\"788340\">other.</span> <span m=\"789490\">So</span> <span\
  \ m=\"789600\">I've</span> <span m=\"789780\">stated</span> <span m=\"790290\">this</span>\
  \ <span m=\"790500\">theorem</span> <span m=\"791100\">so</span> <span m=\"791370\"\
  >far</span> <span m=\"792060\">in</span> <span m=\"792180\">this</span> <span m=\"\
  792360\">form</span> <span m=\"792810\">where</span> <span m=\"793320\">there</span>\
  \ <span m=\"793520\">is</span> <span m=\"793710\">a</span> <span m=\"794070\">little</span>\
  \ <span m=\"794370\">1</span> <span m=\"794700\">error.</span> <span m=\"795510\"\
  >But</span> <span m=\"795840\">equivalently,</span> <span m=\"798480\">so I</span>\
  \ <span m=\"798690\">can</span> <span m=\"800260\">equivalently</span> <span m=\"\
  800900\">state</span> <span m=\"804920\">theorem</span> <span m=\"805585\">as--</span>\
  \ <span m=\"808700\">for</span> <span m=\"808910\">example,</span> <span m=\"813196\"\
  >have</span> <span m=\"813660\">DISC</span> <span m=\"814290\">with</span> <span\
  \ m=\"814470\">an</span> <span m=\"814620\">epsilon</span> <span m=\"815250\">error,</span>\
  \ <span m=\"817590\">which</span> <span m=\"817770\">is that</span> <span m=\"818080\"\
  >some</span> <span m=\"818390\">inequality</span> <span m=\"818970\">is</span> <span\
  \ m=\"819090\">true</span> <span m=\"819690\">with</span> <span m=\"819900\">at</span>\
  \ <span m=\"819990\">most</span> <span m=\"821430\">epsilon</span> <span m=\"822360\"\
  >error</span> <span m=\"822630\">instead</span> <span m=\"823050\">of</span> <span\
  \ m=\"823320\">little</span> <span m=\"823780\">o.</span></p><p><span m=\"824250\"\
  >And</span> <span m=\"824400\">you</span> <span m=\"824490\">have</span> <span m=\"\
  824790\">a</span> <span m=\"824850\">different</span> <span m=\"825210\">epsilon</span>\
  \ <span m=\"825780\">for</span> <span m=\"826920\">each</span> <span m=\"827100\"\
  >one</span> <span m=\"827280\">of</span> <span m=\"827370\">them.</span> <span m=\"\
  828850\">And</span> <span m=\"829210\">the</span> <span m=\"829330\">theorem,</span>\
  \ <span m=\"830125\">it</span> <span m=\"830380\">turns</span> <span m=\"830710\"\
  >out</span> <span m=\"831880\">that--</span> <span m=\"833010\">OK,</span> <span\
  \ m=\"833380\">so</span> <span m=\"833530\">the</span> <span m=\"833650\">proof</span>\
  \ <span m=\"834010\">of</span> <span m=\"834070\">this</span> <span m=\"834190\"\
  >theorem</span> <span m=\"835090\">will</span> <span m=\"835270\">be</span> <span\
  \ m=\"835450\">that</span> <span m=\"836560\">these</span> <span m=\"836770\">conditions</span>\
  \ <span m=\"837280\">are</span> <span m=\"837340\">true,</span> <span m=\"837810\"\
  >so</span> <span m=\"837990\">all</span> <span m=\"838240\">equivalent,</span> <span\
  \ m=\"840640\">up</span> <span m=\"840820\">to</span> <span m=\"842050\">at</span>\
  \ <span m=\"842800\">most</span> <span m=\"843100\">a</span> <span m=\"843130\"\
  >polynomial</span> <span m=\"843760\">change in</span> <span m=\"844210\">the</span>\
  \ <span m=\"844300\">epsilons.</span></p><p><span m=\"853970\">In</span> <span m=\"\
  854090\">other</span> <span m=\"854270\">words,</span> <span m=\"855190\">so</span>\
  \ <span m=\"855320\">property</span> <span m=\"857270\">one</span> <span m=\"857630\"\
  >is</span> <span m=\"857810\">true</span> <span m=\"858470\">for</span> <span m=\"\
  858680\">epsilon</span> <span m=\"859640\">implies</span> <span m=\"860270\">that</span>\
  \ <span m=\"860420\">property</span> <span m=\"862100\">two</span> <span m=\"862460\"\
  >is</span> <span m=\"862640\">true</span> <span m=\"863210\">for</span> <span m=\"\
  863870\">some</span> <span m=\"864620\">epsilon</span> <span m=\"865250\">raised</span>\
  \ <span m=\"865550\">to</span> <span m=\"865820\">a</span> <span m=\"865880\">constant.</span>\
  \ <span m=\"866900\">So</span> <span m=\"867130\">the</span> <span m=\"867440\"\
  >changes</span> <span m=\"867920\">in</span> <span m=\"868010\">parameters</span>\
  \ <span m=\"868580\">are</span> <span m=\"868670\">quite</span> <span m=\"868970\"\
  >reasonable.</span> <span m=\"870240\">And</span> <span m=\"870390\">we'll</span>\
  \ <span m=\"872100\">see</span> <span m=\"872280\">this</span> <span m=\"872490\"\
  >from</span> <span m=\"872670\">the</span> <span m=\"872760\">proof,</span> <span\
  \ m=\"873030\">but</span> <span m=\"873210\">I</span> <span m=\"873300\">won't</span>\
  \ <span m=\"873810\">say</span> <span m=\"874050\">it</span> <span m=\"874110\"\
  >again</span> <span m=\"874350\">explicitly.</span> <span m=\"876900\">Any</span>\
  \ <span m=\"877110\">questions</span> <span m=\"877470\">so</span> <span m=\"877620\"\
  >far</span> <span m=\"877830\">about</span> <span m=\"878020\">the</span> <span\
  \ m=\"878100\">statement</span> <span m=\"878610\">of</span> <span m=\"878730\"\
  >this</span> <span m=\"878880\">theorem?</span></p><p><span m=\"886870\">So</span>\
  \ <span m=\"887200\">as</span> <span m=\"888400\">I</span> <span m=\"888490\">mentioned</span>\
  \ <span m=\"889000\">just</span> <span m=\"889210\">now,</span> <span m=\"889510\"\
  >the</span> <span m=\"889600\">most</span> <span m=\"889990\">surprising</span>\
  \ <span m=\"890770\">part</span> <span m=\"891130\">of</span> <span m=\"891220\"\
  >this</span> <span m=\"891430\">theorem</span> <span m=\"891880\">and</span> <span\
  \ m=\"892000\">the</span> <span m=\"892060\">one</span> <span m=\"892270\">that</span>\
  \ <span m=\"892380\">I</span> <span m=\"892450\">want you</span> <span m=\"892690\"\
  >to</span> <span m=\"892780\">pay</span> <span m=\"892990\">the</span> <span m=\"\
  893080\">most</span> <span m=\"893350\">attention</span> <span m=\"893740\">to</span>\
  \ <span m=\"894480\">is</span> <span m=\"894670\">the</span> <span m=\"894770\"\
  >C4</span> <span m=\"895330\">condition.</span> <span m=\"897870\">This</span> <span\
  \ m=\"898020\">seems,</span> <span m=\"898830\">at</span> <span m=\"898890\">least</span>\
  \ <span m=\"899100\">at</span> <span m=\"899160\">face</span> <span m=\"899520\"\
  >value,</span> <span m=\"899970\">the</span> <span m=\"900120\">weakest</span> <span\
  \ m=\"901230\">condition</span> <span m=\"901770\">among</span> <span m=\"903300\"\
  >all</span> <span m=\"903450\">of</span> <span m=\"903510\">them.</span> <span m=\"\
  903660\">It</span> <span m=\"903750\">just</span> <span m=\"903900\">says</span>\
  \ <span m=\"904170\">the</span> <span m=\"904260\">correct</span> <span m=\"904700\"\
  >C4</span> <span m=\"905250\">count.</span></p><p><span m=\"907510\">But</span>\
  \ <span m=\"907720\">it</span> <span m=\"907780\">turns</span> <span m=\"908020\"\
  >out</span> <span m=\"908110\">to</span> <span m=\"908200\">be</span> <span m=\"\
  908320\">equivalent</span> <span m=\"908800\">to</span> <span m=\"908920\">everything</span>\
  \ <span m=\"909280\">else.</span> <span m=\"910480\">And</span> <span m=\"910510\"\
  >there's</span> <span m=\"910660\">something</span> <span m=\"910930\">special</span>\
  \ <span m=\"911410\">about</span> <span m=\"911620\">C4,</span> <span m=\"911840\"\
  >right?</span> <span m=\"912350\">If</span> <span m=\"912460\">I</span> <span m=\"\
  912550\">replace</span> <span m=\"913000\">C4</span> <span m=\"913450\">by</span>\
  \ <span m=\"913690\">C3,</span> <span m=\"914330\">by</span> <span m=\"914500\"\
  >just</span> <span m=\"914680\">triangles,</span> <span m=\"915340\">then</span>\
  \ <span m=\"915400\">it is</span> <span m=\"915520\">not</span> <span m=\"915700\"\
  >true.</span> <span m=\"916810\">So</span> <span m=\"917450\">I</span> <span m=\"\
  917630\">want</span> <span m=\"917730\">you</span> <span m=\"917840\">to</span>\
  \ <span m=\"917920\">think</span> <span m=\"918100\">about,</span> <span m=\"918670\"\
  >where</span> <span m=\"919090\">does</span> <span m=\"919240\">C4</span> <span\
  \ m=\"920200\">play</span> <span m=\"920560\">this</span> <span m=\"920770\">important</span>\
  \ <span m=\"921220\">role?</span> <span m=\"922300\">How</span> <span m=\"922510\"\
  >does</span> <span m=\"922650\">it</span> <span m=\"922720\">play</span> <span m=\"\
  922930\">this</span> <span m=\"923110\">important</span> <span m=\"923520\">role?</span></p><p><span\
  \ m=\"925530\">OK.</span> <span m=\"926140\">So</span> <span m=\"926260\">let's</span>\
  \ <span m=\"926530\">get</span> <span m=\"926710\">started</span> <span m=\"927040\"\
  >with</span> <span m=\"927190\">a</span> <span m=\"927250\">proof.</span> <span\
  \ m=\"929450\">But</span> <span m=\"929580\">before</span> <span m=\"929850\">that,</span>\
  \ <span m=\"930450\">let</span> <span m=\"930600\">me--</span> <span m=\"932340\"\
  >so</span> <span m=\"932820\">in</span> <span m=\"932940\">this</span> <span m=\"\
  933120\">proof,</span> <span m=\"933450\">one</span> <span m=\"933900\">recurring</span>\
  \ <span m=\"934530\">theme</span> <span m=\"935340\">is</span> <span m=\"935550\"\
  >that</span> <span m=\"935700\">we're</span> <span m=\"935850\">going</span> <span\
  \ m=\"936030\">to</span> <span m=\"936120\">be</span> <span m=\"936240\">using</span>\
  \ <span m=\"936540\">the</span> <span m=\"936630\">Cauchy-Schwarz</span> <span m=\"\
  937350\">inequality</span> <span m=\"937830\">many</span> <span m=\"938070\">times.</span>\
  \ <span m=\"938910\">And</span> <span m=\"939060\">I</span> <span m=\"939120\">want</span>\
  \ <span m=\"939360\">to</span> <span m=\"939540\">just</span> <span m=\"939720\"\
  >begin</span> <span m=\"940110\">with</span> <span m=\"940320\">an</span> <span\
  \ m=\"940410\">exercise</span> <span m=\"940920\">that</span> <span m=\"941040\"\
  >gives</span> <span m=\"941250\">you</span> <span m=\"941340\">some</span> <span\
  \ m=\"941550\">familiarity</span> <span m=\"942240\">with</span> <span m=\"942510\"\
  >applying</span> <span m=\"942870\">the</span> <span m=\"942930\">Cauchy-Schwarz</span>\
  \ <span m=\"943560\">inequality.</span></p><p><span m=\"944140\">And</span> <span\
  \ m=\"944250\">this</span> <span m=\"944940\">is</span> <span m=\"945020\">a</span>\
  \ <span m=\"945090\">simple</span> <span m=\"945750\">tool,</span> <span m=\"946110\"\
  >but</span> <span m=\"946260\">it's</span> <span m=\"946440\">extremely</span> <span\
  \ m=\"946890\">powerful.</span> <span m=\"947400\">And it's</span> <span m=\"947520\"\
  >worthwhile</span> <span m=\"948120\">to</span> <span m=\"948720\">master</span>\
  \ <span m=\"949140\">how</span> <span m=\"949320\">to</span> <span m=\"949410\"\
  >use</span> <span m=\"949650\">a</span> <span m=\"949710\">Cauchy-Schwarz</span>\
  \ <span m=\"949980\">inequality.</span> <span m=\"952230\">So</span> <span m=\"\
  953130\">let's</span> <span m=\"953310\">get</span> <span m=\"953460\">some</span>\
  \ <span m=\"953580\">practice.</span> <span m=\"954660\">And</span> <span m=\"955440\"\
  >let</span> <span m=\"955560\">me</span> <span m=\"955680\">prove</span> <span m=\"\
  958370\">a</span> <span m=\"958430\">claim</span> <span m=\"959180\">which</span>\
  \ <span m=\"959330\">is</span> <span m=\"959450\">not</span> <span m=\"959990\"\
  >directly</span> <span m=\"961490\">related</span> <span m=\"961880\">to</span>\
  \ <span m=\"962000\">the</span> <span m=\"962090\">proof</span> <span m=\"962390\"\
  >of</span> <span m=\"962480\">the</span> <span m=\"962570\">theorem,</span> <span\
  \ m=\"962900\">but</span> <span m=\"963500\">it's</span> <span m=\"963920\">indirect</span>\
  \ <span m=\"964310\">in</span> <span m=\"964920\">that</span> <span m=\"965510\"\
  >it</span> <span m=\"965720\">explains</span> <span m=\"966290\">somewhat</span>\
  \ <span m=\"966920\">the</span> <span m=\"967070\">C4</span> <span m=\"967630\"\
  >condition</span> <span m=\"968520\">and</span> <span m=\"968840\">why</span> <span\
  \ m=\"969110\">we</span> <span m=\"969260\">have</span> <span m=\"969560\">less</span>\
  \ <span m=\"969890\">than</span> <span m=\"970040\">or</span> <span m=\"970130\"\
  >equal</span> <span m=\"970400\">to</span> <span m=\"970940\">over</span> <span\
  \ m=\"971150\">there.</span></p><p><span m=\"974300\">So</span> <span m=\"974330\"\
  >the</span> <span m=\"974840\">lemma</span> <span m=\"975710\">is</span> <span m=\"\
  975860\">that</span> <span m=\"976610\">if</span> <span m=\"976850\">you</span>\
  \ <span m=\"977000\">have</span> <span m=\"977150\">a</span> <span m=\"977180\"\
  >graph</span> <span m=\"978480\">on</span> <span m=\"978900\">n</span> <span m=\"\
  979100\">vertices</span> <span m=\"981770\">such</span> <span m=\"982070\">that</span>\
  \ <span m=\"983210\">the</span> <span m=\"983360\">number</span> <span m=\"983750\"\
  >of</span> <span m=\"983930\">edges</span> <span m=\"984770\">is</span> <span m=\"\
  984950\">at</span> <span m=\"985040\">least</span> <span m=\"986330\">pn</span>\
  \ <span m=\"987500\">squared</span> <span m=\"988250\">over</span> <span m=\"988490\"\
  >2,</span> <span m=\"988730\">so</span> <span m=\"989060\">edge</span> <span m=\"\
  989270\">density</span> <span m=\"990170\">basically</span> <span m=\"990590\">p,</span>\
  \ <span m=\"993080\">then</span> <span m=\"993950\">the</span> <span m=\"994040\"\
  >number</span> <span m=\"994580\">of</span> <span m=\"995180\">labeled</span> <span\
  \ m=\"995750\">copies</span> <span m=\"1000340\">of</span> <span m=\"1000820\">C4</span>\
  \ <span m=\"1002860\">is</span> <span m=\"1003550\">at</span> <span m=\"1003700\"\
  >least</span> <span m=\"1006550\">p</span> <span m=\"1007090\">to</span> <span m=\"\
  1007240\">the</span> <span m=\"1007330\">4</span> <span m=\"1008140\">minus</span>\
  \ <span m=\"1008500\">little o</span> <span m=\"1008740\">1</span> <span m=\"1009920\"\
  >n</span> <span m=\"1010120\">to the</span> <span m=\"1010611\">4th.</span> <span\
  \ m=\"1016020\">So</span> <span m=\"1016230\">if</span> <span m=\"1016410\">you</span>\
  \ <span m=\"1016530\">have</span> <span m=\"1017310\">a</span> <span m=\"1017370\"\
  >graph</span> <span m=\"1017760\">with</span> <span m=\"1017990\">each</span> <span\
  \ m=\"1018180\">density</span> <span m=\"1018540\">p--</span> <span m=\"1019290\"\
  >p's</span> <span m=\"1019560\">your</span> <span m=\"1019590\">constant--</span>\
  \ <span m=\"1020380\">then</span> <span m=\"1020400\">the</span> <span m=\"1020460\"\
  >number</span> <span m=\"1020790\">of</span> <span m=\"1020880\">C4s</span> <span\
  \ m=\"1021150\">is</span> <span m=\"1022140\">at</span> <span m=\"1022230\">least</span>\
  \ <span m=\"1022680\">roughly</span> <span m=\"1023160\">what</span> <span m=\"\
  1023340\">you</span> <span m=\"1023470\">would</span> <span m=\"1023540\">expect</span>\
  \ <span m=\"1023970\">in</span> <span m=\"1024089\">a</span> <span m=\"1024119\"\
  >random</span> <span m=\"1024599\">graph.</span></p><p><span m=\"1027970\">So</span>\
  \ <span m=\"1027990\">let's</span> <span m=\"1028140\">see</span> <span m=\"1028260\"\
  >how</span> <span m=\"1028380\">to</span> <span m=\"1028470\">do</span> <span m=\"\
  1028589\">this.</span> <span m=\"1031540\">And</span> <span m=\"1031660\">I</span>\
  \ <span m=\"1031760\">want</span> <span m=\"1031980\">to</span> <span m=\"1032430\"\
  >show</span> <span m=\"1032760\">this</span> <span m=\"1032940\">inequality</span>\
  \ <span m=\"1033710\">as</span> <span m=\"1033890\">a--</span> <span m=\"1034530\"\
  >well,</span> <span m=\"1034829\">I'll</span> <span m=\"1034980\">show</span> <span\
  \ m=\"1035190\">you</span> <span m=\"1035280\">how</span> <span m=\"1035400\">to</span>\
  \ <span m=\"1035490\">prove</span> <span m=\"1035700\">this</span> <span m=\"1035849\"\
  >inequality.</span> <span m=\"1036660\">But</span> <span m=\"1036839\">I</span>\
  \ <span m=\"1036930\">also</span> <span m=\"1037200\">want</span> <span m=\"1037410\"\
  >to</span> <span m=\"1037500\">draw</span> <span m=\"1037740\">a</span> <span m=\"\
  1037770\">sequence</span> <span m=\"1038190\">of</span> <span m=\"1038280\">pictures,</span>\
  \ <span m=\"1039970\">at</span> <span m=\"1040069\">least,</span> <span m=\"1040470\"\
  >to</span> <span m=\"1040619\">explain</span> <span m=\"1041010\">how</span> <span\
  \ m=\"1041220\">I</span> <span m=\"1041339\">think</span> <span m=\"1041579\">about</span>\
  \ <span m=\"1042210\">applications</span> <span m=\"1042780\">of</span> <span m=\"\
  1042839\">the</span> <span m=\"1042930\">Cauchy-Schwarz</span> <span m=\"1043470\"\
  >inequality.</span></p><p><span m=\"1046750\">OK.</span> <span m=\"1047040\">So</span>\
  \ <span m=\"1050590\">the</span> <span m=\"1050650\">first</span> <span m=\"1050920\"\
  >thing</span> <span m=\"1051190\">is</span> <span m=\"1051400\">that</span> <span\
  \ m=\"1052120\">we</span> <span m=\"1052360\">are</span> <span m=\"1052810\">counting</span>\
  \ <span m=\"1053260\">labeled</span> <span m=\"1053650\">copies</span> <span m=\"\
  1054100\">of</span> <span m=\"1054190\">C4.</span> <span m=\"1055090\">And</span>\
  \ <span m=\"1055240\">this</span> <span m=\"1055420\">is</span> <span m=\"1055960\"\
  >basically</span> <span m=\"1056550\">but</span> <span m=\"1056720\">not</span>\
  \ <span m=\"1057580\">exactly</span> <span m=\"1058030\">the</span> <span m=\"1058120\"\
  >same</span> <span m=\"1058420\">as</span> <span m=\"1058870\">number</span> <span\
  \ m=\"1059110\">of</span> <span m=\"1059200\">homomorphic</span> <span m=\"1059770\"\
  >copies</span> <span m=\"1060280\">of</span> <span m=\"1060760\">C4</span> <span\
  \ m=\"1061160\">and</span> <span m=\"1061420\">G.</span> <span m=\"1062060\">So\
  \ by</span> <span m=\"1062920\">this</span> <span m=\"1063130\">guy</span> <span\
  \ m=\"1063310\">here,</span> <span m=\"1064270\">I</span> <span m=\"1064420\">really</span>\
  \ <span m=\"1065440\">just</span> <span m=\"1065740\">mean</span> <span m=\"1067870\"\
  >you</span> <span m=\"1068170\">are</span> <span m=\"1068290\">mapping</span> <span\
  \ m=\"1068800\">vertices</span> <span m=\"1069340\">of</span> <span m=\"1069430\"\
  >C4</span> <span m=\"1069910\">to</span> <span m=\"1070030\">G</span> <span m=\"\
  1070300\">so</span> <span m=\"1070480\">that</span> <span m=\"1070600\">the</span>\
  \ <span m=\"1070870\">edges</span> <span m=\"1071230\">all</span> <span m=\"1071380\"\
  >map</span> <span m=\"1071670\">to</span> <span m=\"1072400\">edges.</span></p><p><span\
  \ m=\"1073150\">But</span> <span m=\"1074450\">we</span> <span m=\"1074620\">are</span>\
  \ <span m=\"1074740\">allowing</span> <span m=\"1078500\">not</span> <span m=\"\
  1078740\">necessarily</span> <span m=\"1079380\">injective</span> <span m=\"1080660\"\
  >maps,</span> <span m=\"1083950\">C4</span> <span m=\"1085220\">to</span> <span\
  \ m=\"1085490\">G.</span> <span m=\"1087160\">But</span> <span m=\"1087250\">that's</span>\
  \ <span m=\"1087430\">OK.</span> <span m=\"1088000\">So</span> <span m=\"1088180\"\
  >the</span> <span m=\"1088270\">number</span> <span m=\"1088630\">of</span> <span\
  \ m=\"1089200\">non-injective</span> <span m=\"1090010\">maps</span> <span m=\"\
  1091950\">is</span> <span m=\"1093690\">at</span> <span m=\"1094140\">most</span>\
  \ <span m=\"1094560\">cubic.</span> <span m=\"1095260\">So</span> <span m=\"1095490\"\
  >we're</span> <span m=\"1095670\">not</span> <span m=\"1095910\">really</span> <span\
  \ m=\"1096240\">affecting</span> <span m=\"1097200\">our</span> <span m=\"1097330\"\
  >count.</span> <span m=\"1097770\">So</span> <span m=\"1098340\">it's</span> <span\
  \ m=\"1098520\">enough</span> <span m=\"1098820\">to</span> <span m=\"1098910\"\
  >think</span> <span m=\"1099150\">about</span> <span m=\"1099640\">homomorphic</span>\
  \ <span m=\"1100350\">copies.</span></p><p><span m=\"1106460\">OK.</span> <span\
  \ m=\"1107570\">So</span> <span m=\"1107690\">what's</span> <span m=\"1107840\"\
  >going</span> <span m=\"1108050\">on</span> <span m=\"1108170\">here?</span> <span\
  \ m=\"1108600\">So</span> <span m=\"1108680\">let</span> <span m=\"1108770\">me</span>\
  \ <span m=\"1108890\">draw</span> <span m=\"1109070\">a</span> <span m=\"1109100\"\
  >sequence</span> <span m=\"1109550\">of</span> <span m=\"1109610\">pictures</span>\
  \ <span m=\"1110030\">illustrating</span> <span m=\"1110540\">this</span> <span\
  \ m=\"1110660\">calculation.</span> <span m=\"1112680\">So</span> <span m=\"1112700\"\
  >first,</span> <span m=\"1113780\">we</span> <span m=\"1114290\">are</span> <span\
  \ m=\"1114560\">thinking</span> <span m=\"1114920\">about</span> <span m=\"1115850\"\
  >counting</span> <span m=\"1117780\">C4s.</span> <span m=\"1118450\">So</span> <span\
  \ m=\"1118840\">that's</span> <span m=\"1119470\">a</span> <span m=\"1119550\">C4.</span>\
  \ <span m=\"1123030\">I</span> <span m=\"1123150\">can</span> <span m=\"1123300\"\
  >rewrite</span> <span m=\"1123870\">the</span> <span m=\"1123960\">C4</span> <span\
  \ m=\"1124440\">count</span> <span m=\"1125460\">as</span> <span m=\"1125700\">a</span>\
  \ <span m=\"1125760\">sum</span> <span m=\"1127740\">over</span> <span m=\"1128010\"\
  >pairs</span> <span m=\"1128430\">of</span> <span m=\"1128490\">vertices</span>\
  \ <span m=\"1129030\">of</span> <span m=\"1129150\">G</span> <span m=\"1131880\"\
  >as</span> <span m=\"1132270\">the</span> <span m=\"1132930\">squared</span> <span\
  \ m=\"1133590\">codegree.</span></p><p><span m=\"1139850\">And</span> <span m=\"\
  1140060\">what</span> <span m=\"1140210\">happens</span> <span m=\"1140690\">here--</span>\
  \ <span m=\"1140990\">so</span> <span m=\"1141770\">this</span> <span m=\"1142040\"\
  >is</span> <span m=\"1142160\">true.</span> <span m=\"1142470\">I</span> <span m=\"\
  1142570\">mean,</span> <span m=\"1143010\">it's</span> <span m=\"1143090\">not</span>\
  \ <span m=\"1143270\">hard</span> <span m=\"1143450\">to</span> <span m=\"1143540\"\
  >see</span> <span m=\"1143750\">why</span> <span m=\"1143900\">this</span> <span\
  \ m=\"1144080\">is</span> <span m=\"1144170\">true.</span> <span m=\"1144450\">But</span>\
  \ <span m=\"1144500\">I</span> <span m=\"1144560\">want</span> <span m=\"1144740\"\
  >to</span> <span m=\"1144800\">draw</span> <span m=\"1145130\">this</span> <span\
  \ m=\"1145340\">in</span> <span m=\"1145520\">pictures,</span> <span m=\"1147050\"\
  >because</span> <span m=\"1147530\">when you</span> <span m=\"1147710\">have</span>\
  \ <span m=\"1148250\">larger</span> <span m=\"1148640\">and</span> <span m=\"1148730\"\
  >bigger</span> <span m=\"1149000\">graphs,</span> <span m=\"1149320\">it may</span>\
  \ <span m=\"1149440\">be</span> <span m=\"1149600\">more</span> <span m=\"1149810\"\
  >difficult</span> <span m=\"1150260\">to</span> <span m=\"1151040\">think</span>\
  \ <span m=\"1151310\">about</span> <span m=\"1151520\">the</span> <span m=\"1151640\"\
  >algebra</span> <span m=\"1152090\">unless</span> <span m=\"1152360\">you</span>\
  \ <span m=\"1152450\">have</span> <span m=\"1152690\">some</span> <span m=\"1153020\"\
  >visualization.</span></p><p><span m=\"1154740\">So</span> <span m=\"1154820\">what</span>\
  \ <span m=\"1155030\">happens</span> <span m=\"1155390\">here</span> <span m=\"\
  1156050\">is</span> <span m=\"1156290\">that</span> <span m=\"1157840\">I</span>\
  \ <span m=\"1157960\">notice</span> <span m=\"1158440\">that</span> <span m=\"1158620\"\
  >the</span> <span m=\"1158740\">C4</span> <span m=\"1159460\">has</span> <span m=\"\
  1159820\">a</span> <span m=\"1159880\">certain</span> <span m=\"1160360\">reflection.</span>\
  \ <span m=\"1161740\">Namely,</span> <span m=\"1162460\">it</span> <span m=\"1162550\"\
  >has</span> <span m=\"1162820\">a</span> <span m=\"1162880\">reflection</span> <span\
  \ m=\"1165730\">along</span> <span m=\"1166040\">this</span> <span m=\"1166150\"\
  >horizontal</span> <span m=\"1166720\">line.</span> <span m=\"1168680\">And</span>\
  \ <span m=\"1169270\">so</span> <span m=\"1170080\">if</span> <span m=\"1170290\"\
  >I</span> <span m=\"1171460\">put</span> <span m=\"1171730\">these</span> <span\
  \ m=\"1172000\">two</span> <span m=\"1172210\">vertices</span> <span m=\"1172720\"\
  >as</span> <span m=\"1172840\">u</span> <span m=\"1173230\">and</span> <span m=\"\
  1173410\">v,</span> <span m=\"1175210\">then</span> <span m=\"1175480\">this</span>\
  \ <span m=\"1175750\">reflection</span> <span m=\"1176800\">tells</span> <span m=\"\
  1177160\">you</span> <span m=\"1177700\">that</span> <span m=\"1177910\">you</span>\
  \ <span m=\"1178030\">can</span> <span m=\"1178990\">write</span> <span m=\"1179440\"\
  >this</span> <span m=\"1181450\">number</span> <span m=\"1181690\">of</span> <span\
  \ m=\"1181750\">homomorphic</span> <span m=\"1182200\">copies</span> <span m=\"\
  1182590\">as</span> <span m=\"1182710\">the</span> <span m=\"1182800\">sum</span>\
  \ <span m=\"1183070\">of</span> <span m=\"1183130\">squares.</span></p><p><span\
  \ m=\"1186510\">But</span> <span m=\"1186690\">once</span> <span m=\"1186990\">you</span>\
  \ <span m=\"1187050\">have</span> <span m=\"1187320\">this</span> <span m=\"1187500\"\
  >reflection--</span> <span m=\"1188190\">and</span> <span m=\"1188310\">reflections</span>\
  \ <span m=\"1188850\">are</span> <span m=\"1188940\">super</span> <span m=\"1189270\"\
  >useful,</span> <span m=\"1189660\">because</span> <span m=\"1189960\">they</span>\
  \ <span m=\"1190080\">allow</span> <span m=\"1190410\">us</span> <span m=\"1190620\"\
  >to</span> <span m=\"1191220\">get</span> <span m=\"1191460\">something</span> <span\
  \ m=\"1191790\">into</span> <span m=\"1192030\">a</span> <span m=\"1192090\">square</span>\
  \ <span m=\"1192900\">and</span> <span m=\"1193020\">then,</span> <span m=\"1193980\"\
  >right</span> <span m=\"1194220\">after,</span> <span m=\"1194670\">apply</span>\
  \ <span m=\"1195090\">the</span> <span m=\"1195180\">Cauchy-Schwarz</span> <span\
  \ m=\"1195900\">inequality.</span> <span m=\"1198260\">So</span> <span m=\"1198420\"\
  >we</span> <span m=\"1198510\">apply</span> <span m=\"1198810\">Cauchy-Schwarz</span>\
  \ <span m=\"1199500\">here.</span> <span m=\"1200160\">And</span> <span m=\"1200670\"\
  >we</span> <span m=\"1201540\">obtain</span> <span m=\"1202440\">that</span> <span\
  \ m=\"1203130\">this</span> <span m=\"1204060\">sum</span> <span m=\"1205380\">is</span>\
  \ <span m=\"1206060\">at</span> <span m=\"1206250\">most</span> <span m=\"1209190\"\
  >where</span> <span m=\"1209370\">I</span> <span m=\"1209430\">can</span> <span\
  \ m=\"1210930\">pull</span> <span m=\"1213180\">the</span> <span m=\"1213260\">square</span>\
  \ <span m=\"1215710\">out.</span></p><p><span m=\"1218060\">And</span> <span m=\"\
  1218280\">I</span> <span m=\"1218370\">need</span> <span m=\"1218520\">to</span>\
  \ <span m=\"1218580\">think</span> <span m=\"1218790\">about</span> <span m=\"1219090\"\
  >what</span> <span m=\"1219360\">is</span> <span m=\"1219570\">the</span> <span\
  \ m=\"1220290\">correct</span> <span m=\"1222550\">factor</span> <span m=\"1223210\"\
  >to</span> <span m=\"1223360\">put</span> <span m=\"1223600\">out</span> <span m=\"\
  1223780\">here.</span> <span m=\"1225270\">And</span> <span m=\"1225370\">that</span>\
  \ <span m=\"1225520\">should</span> <span m=\"1225730\">be--</span> <span m=\"1230710\"\
  >so</span> <span m=\"1230880\">what's</span> <span m=\"1231090\">the</span> <span\
  \ m=\"1231180\">correct</span> <span m=\"1231480\">factor</span> <span m=\"1231900\"\
  >that I</span> <span m=\"1231990\">should</span> <span m=\"1232140\">put</span>\
  \ <span m=\"1232290\">out</span> <span m=\"1232430\">there?</span></p><p><span m=\"\
  1234975\">AUDIENCE:</span> <span m=\"1235220\">1 over</span> <span m=\"1235466\"\
  >n squared.</span></p><p><span m=\"1235960\">PROFESSOR:</span> <span m=\"1236005\"\
  >OK,</span> <span m=\"1236300\">so</span> <span m=\"1236590\">1</span> <span m=\"\
  1236780\">over</span> <span m=\"1236990\">n</span> <span m=\"1237090\">squared.</span>\
  \ <span m=\"1239190\">So</span> <span m=\"1240450\">I</span> <span m=\"1240540\"\
  >don't</span> <span m=\"1240690\">actually</span> <span m=\"1240960\">like</span>\
  \ <span m=\"1241290\">doing</span> <span m=\"1241530\">these</span> <span m=\"1241680\"\
  >kind</span> <span m=\"1241800\">of</span> <span m=\"1241860\">calculations</span>\
  \ <span m=\"1242700\">with</span> <span m=\"1242910\">sums,</span> <span m=\"1243420\"\
  >because</span> <span m=\"1243680\">then</span> <span m=\"1243810\">you</span> <span\
  \ m=\"1243900\">have</span> <span m=\"1243990\">to</span> <span m=\"1244080\">keep</span>\
  \ <span m=\"1244830\">track</span> <span m=\"1245100\">of</span> <span m=\"1245160\"\
  >these</span> <span m=\"1245340\">normalizing</span> <span m=\"1245880\">factors.</span>\
  \ <span m=\"1247110\">One</span> <span m=\"1247290\">of</span> <span m=\"1247350\"\
  >the</span> <span m=\"1247770\">upcoming</span> <span m=\"1248160\">chapters,</span>\
  \ <span m=\"1248610\">when</span> <span m=\"1248760\">we</span> <span m=\"1248820\"\
  >discuss</span> <span m=\"1249240\">graph</span> <span m=\"1249600\">limits--</span>\
  \ <span m=\"1250890\">or</span> <span m=\"1251040\">in</span> <span m=\"1251190\"\
  >fact,</span> <span m=\"1251500\">you</span> <span m=\"1251600\">can</span> <span\
  \ m=\"1251640\">even</span> <span m=\"1251850\">do</span> <span m=\"1252000\">this.</span></p><p><span\
  \ m=\"1252390\">Instead</span> <span m=\"1252750\">of</span> <span m=\"1252810\"\
  >taking</span> <span m=\"1253110\">sums,</span> <span m=\"1253460\">if</span> <span\
  \ m=\"1253560\">you</span> <span m=\"1253650\">take</span> <span m=\"1254250\">an</span>\
  \ <span m=\"1254400\">average,</span> <span m=\"1254810\">if</span> <span m=\"1254870\"\
  >you</span> <span m=\"1254950\">take</span> <span m=\"1255120\">an</span> <span\
  \ m=\"1255240\">expectation,</span> <span m=\"1255900\">then</span> <span m=\"1256280\"\
  >it</span> <span m=\"1256380\">turns</span> <span m=\"1256590\">out</span> <span\
  \ m=\"1256680\">you</span> <span m=\"1256770\">never</span> <span m=\"1257010\"\
  >have</span> <span m=\"1257190\">to</span> <span m=\"1257280\">worry</span> <span\
  \ m=\"1257520\">about</span> <span m=\"1257730\">these</span> <span m=\"1258090\"\
  >normalizing</span> <span m=\"1258660\">factors.</span> <span m=\"1260100\">So</span>\
  \ <span m=\"1260460\">normalizing</span> <span m=\"1260940\">factors</span> <span\
  \ m=\"1261270\">should</span> <span m=\"1261420\">never</span> <span m=\"1262380\"\
  >bother</span> <span m=\"1262800\">you</span> <span m=\"1263220\">if</span> <span\
  \ m=\"1263370\">you</span> <span m=\"1263460\">do</span> <span m=\"1263640\">it</span>\
  \ <span m=\"1263700\">correctly.</span> <span m=\"1264970\">But</span> <span m=\"\
  1265260\">just</span> <span m=\"1265440\">to</span> <span m=\"1265530\">make</span>\
  \ <span m=\"1265680\">sure</span> <span m=\"1265860\">things</span> <span m=\"1266070\"\
  >are</span> <span m=\"1266160\">correct,</span> <span m=\"1267820\">please</span>\
  \ <span m=\"1268200\">keep</span> <span m=\"1268380\">me</span> <span m=\"1268530\"\
  >in</span> <span m=\"1268620\">check.</span></p><p><span m=\"1270600\">All</span>\
  \ <span m=\"1270660\">right.</span> <span m=\"1271050\">So</span> <span m=\"1271200\"\
  >what</span> <span m=\"1271440\">happened</span> <span m=\"1271800\">in</span> <span\
  \ m=\"1271920\">this</span> <span m=\"1272070\">step?</span> <span m=\"1273180\"\
  >In</span> <span m=\"1273270\">this</span> <span m=\"1273450\">step,</span> <span\
  \ m=\"1274200\">we</span> <span m=\"1274470\">pulled</span> <span m=\"1274800\"\
  >out</span> <span m=\"1274940\">that</span> <span m=\"1275130\">square.</span> <span\
  \ m=\"1275700\">And</span> <span m=\"1275940\">pictorially,</span> <span m=\"1276720\"\
  >what</span> <span m=\"1276900\">happens</span> <span m=\"1277380\">is</span> <span\
  \ m=\"1277560\">that</span> <span m=\"1278100\">we</span> <span m=\"1278490\">got</span>\
  \ <span m=\"1278760\">rid</span> <span m=\"1279030\">of</span> <span m=\"1279540\"\
  >half</span> <span m=\"1279930\">of</span> <span m=\"1280050\">this</span> <span\
  \ m=\"1280230\">picture.</span> <span m=\"1286550\">So</span> <span m=\"1287120\"\
  >we</span> <span m=\"1287240\">used</span> <span m=\"1287720\">Cauchy-Schwarz,</span>\
  \ <span m=\"1288260\">and</span> <span m=\"1288380\">we</span> <span m=\"1288800\"\
  >wiped</span> <span m=\"1289130\">out</span> <span m=\"1289220\">half</span> <span\
  \ m=\"1289550\">of</span> <span m=\"1289610\">the</span> <span m=\"1289700\">picture.</span></p><p><span\
  \ m=\"1292850\">And</span> <span m=\"1292950\">now</span> <span m=\"1293870\">what</span>\
  \ <span m=\"1294080\">we</span> <span m=\"1294200\">can</span> <span m=\"1294380\"\
  >do</span> <span m=\"1294610\">is,</span> <span m=\"1295390\">well,</span> <span\
  \ m=\"1295550\">we're</span> <span m=\"1295730\">counting</span> <span m=\"1296360\"\
  >these</span> <span m=\"1296630\">guys,</span> <span m=\"1296930\">this</span> <span\
  \ m=\"1297860\">path</span> <span m=\"1298190\">of</span> <span m=\"1298310\">length</span>\
  \ <span m=\"1298670\">2.</span> <span m=\"1299540\">But</span> <span m=\"1299750\"\
  >I</span> <span m=\"1299870\">can</span> <span m=\"1301370\">reprioritize</span>\
  \ <span m=\"1302690\">this</span> <span m=\"1302870\">picture</span> <span m=\"\
  1303650\">so</span> <span m=\"1304010\">that</span> <span m=\"1304970\">it</span>\
  \ <span m=\"1305240\">looks</span> <span m=\"1306870\">like</span> <span m=\"1307110\"\
  >that.</span> <span m=\"1307410\">And</span> <span m=\"1307560\">now</span> <span\
  \ m=\"1307800\">I</span> <span m=\"1307860\">notice</span> <span m=\"1308220\">that</span>\
  \ <span m=\"1308310\">there</span> <span m=\"1308460\">is</span> <span m=\"1308700\"\
  >one</span> <span m=\"1309060\">more</span> <span m=\"1309750\">reflection.</span></p><p><span\
  \ m=\"1311370\">So</span> <span m=\"1311490\">there's</span> <span m=\"1311610\"\
  >one</span> <span m=\"1311820\">more</span> <span m=\"1312000\">reflection.</span>\
  \ <span m=\"1312870\">And</span> <span m=\"1312990\">that's</span> <span m=\"1313170\"\
  >the</span> <span m=\"1313260\">reflection</span> <span m=\"1313770\">around</span>\
  \ <span m=\"1314040\">the</span> <span m=\"1314130\">vertical</span> <span m=\"\
  1314580\">axis.</span> <span m=\"1317890\">So</span> <span m=\"1317960\">let</span>\
  \ <span m=\"1318080\">me</span> <span m=\"1318200\">call</span> <span m=\"1318470\"\
  >this</span> <span m=\"1318620\">top</span> <span m=\"1318920\">vertex</span> <span\
  \ m=\"1319430\">x.</span> <span m=\"1321140\">And</span> <span m=\"1321320\">I</span>\
  \ <span m=\"1321410\">can</span> <span m=\"1321560\">rewrite</span> <span m=\"1322440\"\
  >the</span> <span m=\"1322650\">sum</span> <span m=\"1330932\">like</span> <span\
  \ m=\"1331424\">that.</span></p><p><span m=\"1338320\">OK.</span> <span m=\"1338720\"\
  >So</span> <span m=\"1338900\">once</span> <span m=\"1339170\">more,</span> <span\
  \ m=\"1339380\">we</span> <span m=\"1339580\">do</span> <span m=\"1339680\">Cauchy-Schwarz,</span>\
  \ <span m=\"1340970\">which</span> <span m=\"1341240\">allows</span> <span m=\"\
  1341630\">us</span> <span m=\"1341810\">to</span> <span m=\"1342530\">get</span>\
  \ <span m=\"1342680\">rid</span> <span m=\"1342860\">of</span> <span m=\"1343370\"\
  >half</span> <span m=\"1343700\">of</span> <span m=\"1343760\">the</span> <span\
  \ m=\"1343880\">picture.</span> <span m=\"1344950\">And</span> <span m=\"1345050\"\
  >now</span> <span m=\"1345350\">I'm</span> <span m=\"1345470\">going</span> <span\
  \ m=\"1345680\">to</span> <span m=\"1345770\">draw</span> <span m=\"1346000\">the</span>\
  \ <span m=\"1346100\">picture</span> <span m=\"1346490\">first,</span> <span m=\"\
  1347740\">because then</span> <span m=\"1348080\">you</span> <span m=\"1348200\"\
  >see</span> <span m=\"1348500\">that</span> <span m=\"1349040\">what</span> <span\
  \ m=\"1349190\">we</span> <span m=\"1349340\">should</span> <span m=\"1349520\"\
  >be</span> <span m=\"1349940\">left</span> <span m=\"1350210\">with</span> <span\
  \ m=\"1350600\">is just</span> <span m=\"1350810\">a</span> <span m=\"1350870\"\
  >single</span> <span m=\"1351400\">edge.</span> <span m=\"1352860\">And</span> <span\
  \ m=\"1352980\">then</span> <span m=\"1353550\">you</span> <span m=\"1354330\">write</span>\
  \ <span m=\"1354570\">down</span> <span m=\"1354810\">the</span> <span m=\"1354900\"\
  >correct</span> <span m=\"1355890\">sum,</span> <span m=\"1357720\">making</span>\
  \ <span m=\"1358050\">sure</span> <span m=\"1358410\">that</span> <span m=\"1360370\"\
  >all</span> <span m=\"1360560\">the</span> <span m=\"1360680\">parentheses</span>\
  \ <span m=\"1361490\">and</span> <span m=\"1361730\">normalizations</span> <span\
  \ m=\"1362540\">are</span> <span m=\"1362660\">correct.</span> <span m=\"1363580\"\
  >But</span> <span m=\"1365150\">somehow,</span> <span m=\"1365540\">that</span>\
  \ <span m=\"1365690\">doesn't</span> <span m=\"1365930\">worry</span> <span m=\"\
  1366170\">me</span> <span m=\"1366290\">so</span> <span m=\"1366440\">much,</span>\
  \ <span m=\"1366620\">because</span> <span m=\"1366950\">I</span> <span m=\"1367040\"\
  >know</span> <span m=\"1367220\">this</span> <span m=\"1367400\">will</span> <span\
  \ m=\"1367550\">definitely</span> <span m=\"1368030\">work</span> <span m=\"1368500\"\
  >out.</span></p><p><span m=\"1373210\">But</span> <span m=\"1373440\">whatever</span>\
  \ <span m=\"1373830\">it is,</span> <span m=\"1374120\">you're</span> <span m=\"\
  1374220\">just</span> <span m=\"1374410\">summing</span> <span m=\"1374730\">the</span>\
  \ <span m=\"1374820\">number</span> <span m=\"1375090\">of</span> <span m=\"1375210\"\
  >edges.</span> <span m=\"1375750\">So</span> <span m=\"1376710\">that's</span> <span\
  \ m=\"1376860\">just</span> <span m=\"1377070\">the</span> <span m=\"1377140\">number</span>\
  \ <span m=\"1377550\">of</span> <span m=\"1377640\">edges.</span> <span m=\"1379270\"\
  >And</span> <span m=\"1381440\">so</span> <span m=\"1381650\">we</span> <span m=\"\
  1381800\">put</span> <span m=\"1387320\">everything</span> <span m=\"1387710\">in.</span>\
  \ <span m=\"1389950\">And</span> <span m=\"1390000\">we</span> <span m=\"1390150\"\
  >find</span> <span m=\"1390540\">that</span> <span m=\"1390840\">the</span> <span\
  \ m=\"1390930\">final</span> <span m=\"1391380\">quantity</span> <span m=\"1391860\"\
  >is</span> <span m=\"1392010\">at</span> <span m=\"1392100\">least</span> <span\
  \ m=\"1393310\">p</span> <span m=\"1393570\">raised</span> <span m=\"1393790\">to</span>\
  \ <span m=\"1393900\">4</span> <span m=\"1394590\">n</span> <span m=\"1394710\"\
  >to</span> <span m=\"1394920\">4.</span></p><p><span m=\"1397150\">So</span> <span\
  \ m=\"1397430\">I</span> <span m=\"1397540\">did</span> <span m=\"1397690\">this</span>\
  \ <span m=\"1397870\">quite</span> <span m=\"1398110\">slowly.</span> <span m=\"\
  1398650\">But</span> <span m=\"1398890\">I'm</span> <span m=\"1399100\">also</span>\
  \ <span m=\"1399340\">emphasizing</span> <span m=\"1399910\">the</span> <span m=\"\
  1400000\">sequence</span> <span m=\"1400420\">of</span> <span m=\"1400510\">pictures,</span>\
  \ <span m=\"1403150\">partly</span> <span m=\"1403540\">to</span> <span m=\"1403630\"\
  >tell</span> <span m=\"1403900\">how</span> <span m=\"1404230\">I</span> <span m=\"\
  1404290\">think</span> <span m=\"1404500\">about</span> <span m=\"1404710\">these</span>\
  \ <span m=\"1404860\">inequalities.</span> <span m=\"1405520\">Because</span> <span\
  \ m=\"1406390\">for</span> <span m=\"1407500\">other</span> <span m=\"1407800\"\
  >similar</span> <span m=\"1408190\">looking</span> <span m=\"1408520\">inequalities--</span>\
  \ <span m=\"1409490\">in</span> <span m=\"1409630\">fact,</span> <span m=\"1409940\"\
  >there</span> <span m=\"1410020\">is</span> <span m=\"1410080\">something</span>\
  \ <span m=\"1410830\">called</span> <span m=\"1411160\">Sidorenko's</span> <span\
  \ m=\"1411910\">conjecture,</span> <span m=\"1412750\">which</span> <span m=\"1413260\"\
  >I</span> <span m=\"1413320\">may</span> <span m=\"1413470\">discuss</span> <span\
  \ m=\"1413860\">more</span> <span m=\"1414040\">in</span> <span m=\"1414140\">a</span>\
  \ <span m=\"1414220\">future</span> <span m=\"1414490\">lecture,</span> <span m=\"\
  1415180\">that</span> <span m=\"1416350\">says</span> <span m=\"1416740\">that</span>\
  \ <span m=\"1417040\">this</span> <span m=\"1417340\">kind</span> <span m=\"1417640\"\
  >of</span> <span m=\"1417760\">inequality</span> <span m=\"1418990\">should</span>\
  \ <span m=\"1419230\">be</span> <span m=\"1419350\">true</span> <span m=\"1419920\"\
  >whenever</span> <span m=\"1420280\">you</span> <span m=\"1420400\">replace</span>\
  \ <span m=\"1420910\">C4</span> <span m=\"1421540\">by</span> <span m=\"1421750\"\
  >any</span> <span m=\"1422000\">bipartite</span> <span m=\"1422420\">graph.</span>\
  \ <span m=\"1423520\">And</span> <span m=\"1423700\">that's</span> <span m=\"1423850\"\
  >a</span> <span m=\"1423910\">major</span> <span m=\"1424210\">open</span> <span\
  \ m=\"1424450\">problem</span> <span m=\"1424730\">in</span> <span m=\"1424880\"\
  >combinatorics.</span></p><p><span m=\"1427680\">It's</span> <span m=\"1427950\"\
  >kind</span> <span m=\"1428220\">of</span> <span m=\"1428310\">hard</span> <span\
  \ m=\"1428490\">to</span> <span m=\"1428580\">keep</span> <span m=\"1428820\">track</span>\
  \ <span m=\"1429090\">of</span> <span m=\"1429180\">these</span> <span m=\"1429360\"\
  >calculations</span> <span m=\"1429990\">unless</span> <span m=\"1430290\">you</span>\
  \ <span m=\"1430380\">have</span> <span m=\"1430620\">a</span> <span m=\"1430710\"\
  >visual</span> <span m=\"1431220\">anchor.</span> <span m=\"1431910\">And</span>\
  \ <span m=\"1432060\">this</span> <span m=\"1432210\">is</span> <span m=\"1432330\"\
  >my</span> <span m=\"1432540\">visual</span> <span m=\"1432900\">anchor,</span>\
  \ <span m=\"1433290\">which</span> <span m=\"1433510\">I'm</span> <span m=\"1434010\"\
  >trying</span> <span m=\"1434250\">to</span> <span m=\"1434340\">explain.</span>\
  \ <span m=\"1435600\">Of</span> <span m=\"1435660\">course,</span> <span m=\"1435960\"\
  >it's</span> <span m=\"1437040\">down</span> <span m=\"1437250\">to</span> <span\
  \ m=\"1437370\">earth.</span> <span m=\"1437610\">It's</span> <span m=\"1437790\"\
  >just</span> <span m=\"1437970\">the</span> <span m=\"1438090\">sequence</span>\
  \ <span m=\"1438510\">of</span> <span m=\"1438600\">inequalities.</span> <span m=\"\
  1439590\">And</span> <span m=\"1439710\">this</span> <span m=\"1439860\">is</span>\
  \ <span m=\"1439980\">also</span> <span m=\"1440790\">some</span> <span m=\"1440970\"\
  >practice</span> <span m=\"1441420\">with</span> <span m=\"1441540\">Cauchy-Schwarz.</span>\
  \ <span m=\"1444924\">All</span> <span m=\"1445383\">right.</span> <span m=\"1446760\"\
  >Any</span> <span m=\"1447010\">questions?</span></p><p><span m=\"1450980\">But</span>\
  \ <span m=\"1451100\">one</span> <span m=\"1451280\">thing</span> <span m=\"1451440\"\
  >that</span> <span m=\"1451520\">this</span> <span m=\"1451700\">calculation</span>\
  \ <span m=\"1452240\">told</span> <span m=\"1452480\">us</span> <span m=\"1452960\"\
  >is</span> <span m=\"1453080\">that</span> <span m=\"1453260\">if</span> <span m=\"\
  1453410\">you</span> <span m=\"1453530\">have</span> <span m=\"1453830\">edge</span>\
  \ <span m=\"1454100\">density</span> <span m=\"1454520\">p,</span> <span m=\"1455300\"\
  >then</span> <span m=\"1455540\">you</span> <span m=\"1455660\">necessarily</span>\
  \ <span m=\"1456440\">have</span> <span m=\"1457520\">C4</span> <span m=\"1458060\"\
  >density</span> <span m=\"1458840\">at</span> <span m=\"1458960\">least</span> <span\
  \ m=\"1459440\">p</span> <span m=\"1459670\">to</span> <span m=\"1459830\">the</span>\
  \ <span m=\"1459920\">4th.</span> <span m=\"1460790\">So</span> <span m=\"1460880\"\
  >that</span> <span m=\"1461060\">partly</span> <span m=\"1461420\">explains</span>\
  \ <span m=\"1461990\">why</span> <span m=\"1462290\">you</span> <span m=\"1462410\"\
  >have</span> <span m=\"1463160\">at</span> <span m=\"1463310\">most,</span> <span\
  \ m=\"1463670\">then,</span> <span m=\"1464230\">here.</span> <span m=\"1465240\"\
  >So</span> <span m=\"1465600\">you</span> <span m=\"1465710\">always</span> <span\
  \ m=\"1466010\">know</span> <span m=\"1466200\">that it's</span> <span m=\"1466550\"\
  >at</span> <span m=\"1466640\">least</span> <span m=\"1467000\">this</span> <span\
  \ m=\"1467180\">quantity.</span> <span m=\"1468030\">So</span> <span m=\"1468470\"\
  >the</span> <span m=\"1468750\">C4</span> <span m=\"1469060\">quasi</span> <span\
  \ m=\"1469400\">randomness</span> <span m=\"1469910\">condition</span> <span m=\"\
  1470680\">is</span> <span m=\"1470870\">really</span> <span m=\"1471110\">the</span>\
  \ <span m=\"1471320\">equivalent</span> <span m=\"1472250\">to</span> <span m=\"\
  1473030\">replacing</span> <span m=\"1473690\">this</span> <span m=\"1473900\">less</span>\
  \ <span m=\"1474110\">than</span> <span m=\"1474260\">or</span> <span m=\"1474350\"\
  >equal</span> <span m=\"1474560\">to</span> <span m=\"1474970\">by</span> <span\
  \ m=\"1475160\">an</span> <span m=\"1475280\">equal</span> <span m=\"1475590\">sign.</span></p><p><span\
  \ m=\"1480010\">So</span> <span m=\"1480130\">let's</span> <span m=\"1480310\">get</span>\
  \ <span m=\"1480430\">started</span> <span m=\"1480790\">with</span> <span m=\"\
  1480970\">proving</span> <span m=\"1481660\">the</span> <span m=\"1481780\">Chung-Graham-Wilson</span>\
  \ <span m=\"1482620\">theorem.</span> <span m=\"1484210\">So</span> <span m=\"1484360\"\
  >the</span> <span m=\"1484480\">first</span> <span m=\"1484780\">place</span> <span\
  \ m=\"1485200\">that</span> <span m=\"1485350\">we'll</span> <span m=\"1485620\"\
  >look</span> <span m=\"1485890\">at</span> <span m=\"1486220\">is</span> <span m=\"\
  1487440\">the</span> <span m=\"1487570\">two</span> <span m=\"1487840\">versions</span>\
  \ <span m=\"1488350\">of</span> <span m=\"1488830\">DISC.</span> <span m=\"1489920\"\
  >So DISC</span> <span m=\"1490200\">stands</span> <span m=\"1490660\">for</span>\
  \ <span m=\"1490810\">discrepancy.</span></p><p><span m=\"1494630\">So</span> <span\
  \ m=\"1494870\">first,</span> <span m=\"1496120\">the fact that</span> <span m=\"\
  1496510\">DISC</span> <span m=\"1496970\">implies</span> <span m=\"1498260\">DISC</span>\
  \ <span m=\"1498530\">prime,</span> <span m=\"1500570\">I</span> <span m=\"1500600\"\
  >mean,</span> <span m=\"1500720\">this</span> <span m=\"1500900\">is</span> <span\
  \ m=\"1501650\">pretty</span> <span m=\"1501950\">easy.</span> <span m=\"1502250\"\
  >You</span> <span m=\"1502370\">take</span> <span m=\"1502640\">y</span> <span m=\"\
  1503020\">to</span> <span m=\"1503140\">equal</span> <span m=\"1503390\">to</span>\
  \ <span m=\"1503540\">x.</span> <span m=\"1504590\">Be</span> <span m=\"1504770\"\
  >slightly</span> <span m=\"1505220\">careful</span> <span m=\"1505670\">about</span>\
  \ <span m=\"1505820\">the</span> <span m=\"1505910\">definitions,</span> <span m=\"\
  1507110\">but</span> <span m=\"1507230\">you're</span> <span m=\"1507460\">OK.</span>\
  \ <span m=\"1510160\">So</span> <span m=\"1510620\">not</span> <span m=\"1510800\"\
  >much</span> <span m=\"1511040\">to</span> <span m=\"1511130\">do</span> <span m=\"\
  1511280\">there.</span></p><p><span m=\"1513590\">The</span> <span m=\"1513710\"\
  >other</span> <span m=\"1513950\">direction,</span> <span m=\"1519330\">where</span>\
  \ <span m=\"1519600\">you</span> <span m=\"1519780\">only</span> <span m=\"1520050\"\
  >have</span> <span m=\"1520260\">discrepancies</span> <span m=\"1521010\">for</span>\
  \ <span m=\"1521200\">a</span> <span m=\"1521220\">single</span> <span m=\"1521670\"\
  >set</span> <span m=\"1522030\">and</span> <span m=\"1522150\">you</span> <span\
  \ m=\"1522210\">want</span> <span m=\"1522390\">to</span> <span m=\"1522450\">produce</span>\
  \ <span m=\"1522810\">discrepancies</span> <span m=\"1523440\">for</span> <span\
  \ m=\"1523560\">pairs</span> <span m=\"1523980\">of</span> <span m=\"1524070\">sets--</span>\
  \ <span m=\"1525570\">so</span> <span m=\"1525660\">this</span> <span m=\"1525840\"\
  >is</span> <span m=\"1525960\">actually</span> <span m=\"1526230\">a</span> <span\
  \ m=\"1526290\">fairly</span> <span m=\"1526620\">common</span> <span m=\"1526950\"\
  >technique</span> <span m=\"1527400\">in</span> <span m=\"1527520\">algebra</span>\
  \ <span m=\"1528440\">that</span> <span m=\"1528660\">allows</span> <span m=\"1528970\"\
  >you to</span> <span m=\"1529080\">go</span> <span m=\"1529260\">from</span> <span\
  \ m=\"1530610\">bilinear</span> <span m=\"1531090\">forms</span> <span m=\"1531570\"\
  >to</span> <span m=\"1531720\">quadratic</span> <span m=\"1532200\">forms</span>\
  \ <span m=\"1532650\">and</span> <span m=\"1532770\">vice</span> <span m=\"1533010\"\
  >versa.</span> <span m=\"1533460\">It's</span> <span m=\"1533640\">that</span> <span\
  \ m=\"1533820\">kind</span> <span m=\"1534090\">of</span> <span m=\"1534180\">calculation.</span></p><p><span\
  \ m=\"1535090\">So</span> <span m=\"1535190\">let</span> <span m=\"1535200\">me</span>\
  \ <span m=\"1535380\">do</span> <span m=\"1535590\">it</span> <span m=\"1535740\"\
  >here</span> <span m=\"1535980\">concretely</span> <span m=\"1536610\">in</span>\
  \ <span m=\"1536760\">this</span> <span m=\"1536880\">setting.</span> <span m=\"\
  1537640\">So</span> <span m=\"1537720\">here,</span> <span m=\"1538830\">what</span>\
  \ <span m=\"1539040\">you</span> <span m=\"1539190\">should</span> <span m=\"1539340\"\
  >think</span> <span m=\"1539580\">of</span> <span m=\"1539790\">is</span> <span\
  \ m=\"1539940\">that</span> <span m=\"1540030\">you</span> <span m=\"1540180\">have</span>\
  \ <span m=\"1540510\">two</span> <span m=\"1542240\">sets,</span> <span m=\"1542810\"\
  >x</span> <span m=\"1543050\">and</span> <span m=\"1543140\">y,</span> <span m=\"\
  1543650\">and</span> <span m=\"1543770\">they</span> <span m=\"1543890\">might</span>\
  \ <span m=\"1544160\">overlap.</span> <span m=\"1545680\">And</span> <span m=\"\
  1545960\">what</span> <span m=\"1547410\">they</span> <span m=\"1548220\">correspond</span>\
  \ <span m=\"1548730\">to</span> <span m=\"1549630\">in</span> <span m=\"1550740\"\
  >the--</span> <span m=\"1552290\">when</span> <span m=\"1552590\">you</span> <span\
  \ m=\"1552720\">think</span> <span m=\"1552930\">about</span> <span m=\"1553140\"\
  >the</span> <span m=\"1553470\">corresponding</span> <span m=\"1554040\">Venn</span>\
  \ <span m=\"1554310\">diagram,</span> <span m=\"1555220\">where</span> <span m=\"\
  1556580\">I'm</span> <span m=\"1556860\">looking</span> <span m=\"1558720\">at</span>\
  \ <span m=\"1559770\">ways</span> <span m=\"1560160\">that</span> <span m=\"1560370\"\
  >a</span> <span m=\"1562410\">pair</span> <span m=\"1562680\">of</span> <span m=\"\
  1562780\">vertices</span> <span m=\"1563130\">can</span> <span m=\"1563250\">fall</span>\
  \ <span m=\"1563520\">in</span> <span m=\"1563730\">x</span> <span m=\"1564045\"\
  >and/or</span> <span m=\"1564510\">y--</span> <span m=\"1565290\">so</span> <span\
  \ m=\"1565530\">if</span> <span m=\"1565650\">you</span> <span m=\"1565700\">have</span>\
  \ <span m=\"1565920\">x</span> <span m=\"1567810\">and</span> <span m=\"1567960\"\
  >y.</span></p><p><span m=\"1574410\">And</span> <span m=\"1574530\">so</span> <span\
  \ m=\"1574770\">it's</span> <span m=\"1574920\">useful</span> <span m=\"1575220\"\
  >to</span> <span m=\"1575310\">keep</span> <span m=\"1575550\">track</span> <span\
  \ m=\"1575880\">of</span> <span m=\"1581520\">which</span> <span m=\"1581700\">vertices</span>\
  \ <span m=\"1582360\">are</span> <span m=\"1582570\">in</span> <span m=\"1582820\"\
  >which</span> <span m=\"1583150\">set.</span> <span m=\"1584310\">But</span> <span\
  \ m=\"1584460\">what</span> <span m=\"1585360\">the</span> <span m=\"1585450\">thing</span>\
  \ <span m=\"1586080\">finally</span> <span m=\"1586500\">comes</span> <span m=\"\
  1586800\">down</span> <span m=\"1587010\">to</span> <span m=\"1587770\">is</span>\
  \ <span m=\"1587970\">that</span> <span m=\"1588510\">the</span> <span m=\"1588630\"\
  >number</span> <span m=\"1589020\">of</span> <span m=\"1589230\">edges</span> <span\
  \ m=\"1589590\">with</span> <span m=\"1589770\">one</span> <span m=\"1590100\">vertex</span>\
  \ <span m=\"1590540\">in</span> <span m=\"1590700\">x</span> <span m=\"1590940\"\
  >and</span> <span m=\"1591060\">one</span> <span m=\"1591240\">vertex</span> <span\
  \ m=\"1591600\">in</span> <span m=\"1591690\">y,</span> <span m=\"1592380\">I</span>\
  \ <span m=\"1592470\">can</span> <span m=\"1592620\">write</span> <span m=\"1592980\"\
  >this</span> <span m=\"1593520\">bilinear</span> <span m=\"1594060\">form-type</span>\
  \ <span m=\"1594570\">quantity</span> <span m=\"1595430\">as</span> <span m=\"1597000\"\
  >an</span> <span m=\"1597090\">appropriate</span> <span m=\"1598320\">sum</span>\
  \ <span m=\"1603550\">of</span> <span m=\"1606790\">just</span> <span m=\"1608690\"\
  >number</span> <span m=\"1609040\">of</span> <span m=\"1609160\">edges</span> <span\
  \ m=\"1609610\">in</span> <span m=\"1609790\">single</span> <span m=\"1610180\"\
  >sets.</span></p><p><span m=\"1617040\">And</span> <span m=\"1617450\">so</span>\
  \ <span m=\"1617540\">there</span> <span m=\"1617660\">are</span> <span m=\"1617690\"\
  >several</span> <span m=\"1617990\">ways</span> <span m=\"1618230\">to</span> <span\
  \ m=\"1618650\">check</span> <span m=\"1618950\">that</span> <span m=\"1619100\"\
  >this</span> <span m=\"1619310\">is</span> <span m=\"1619460\">true.</span> <span\
  \ m=\"1620600\">One</span> <span m=\"1620900\">way</span> <span m=\"1621140\">is</span>\
  \ <span m=\"1621290\">to</span> <span m=\"1621710\">just</span> <span m=\"1622580\"\
  >tally,</span> <span m=\"1623210\">keep</span> <span m=\"1623450\">track</span>\
  \ <span m=\"1623780\">of</span> <span m=\"1624230\">how</span> <span m=\"1624380\"\
  >many</span> <span m=\"1624650\">edges</span> <span m=\"1624980\">are</span> <span\
  \ m=\"1625070\">you</span> <span m=\"1625160\">counting</span> <span m=\"1626020\"\
  >in</span> <span m=\"1626210\">each</span> <span m=\"1626480\">step.</span> <span\
  \ m=\"1627420\">So</span> <span m=\"1628040\">if</span> <span m=\"1628190\">you</span>\
  \ <span m=\"1628400\">are</span> <span m=\"1628700\">trying</span> <span m=\"1629000\"\
  >to</span> <span m=\"1629120\">count</span> <span m=\"1632470\">the</span> <span\
  \ m=\"1632560\">number</span> <span m=\"1632950\">of</span> <span m=\"1633310\"\
  >edges</span> <span m=\"1633940\">in--</span> <span m=\"1638990\">yeah,</span> <span\
  \ m=\"1639460\">so</span> <span m=\"1639670\">let's</span> <span m=\"1639850\">say</span>\
  \ <span m=\"1640030\">if</span> <span m=\"1640120\">you're</span> <span m=\"1640240\"\
  >trying</span> <span m=\"1640450\">to</span> <span m=\"1640540\">count</span> <span\
  \ m=\"1641140\">the</span> <span m=\"1641380\">number</span> <span m=\"1641800\"\
  >of</span> <span m=\"1642850\">edges</span> <span m=\"1643360\">in--</span> <span\
  \ m=\"1646380\">with</span> <span m=\"1646620\">one</span> <span m=\"1647010\">vertex</span>\
  \ <span m=\"1647325\">in</span> <span m=\"1647640\">x, one</span> <span m=\"1648120\"\
  >vertex in</span> <span m=\"1648570\">y.</span> <span m=\"1649320\">Then</span>\
  \ <span m=\"1650010\">what</span> <span m=\"1650190\">this</span> <span m=\"1650370\"\
  >corresponds</span> <span m=\"1651000\">to</span> <span m=\"1651240\">is</span>\
  \ <span m=\"1653820\">that</span> <span m=\"1654000\">count.</span></p><p><span\
  \ m=\"1654570\">But</span> <span m=\"1654690\">let</span> <span m=\"1654810\">me</span>\
  \ <span m=\"1655110\">do</span> <span m=\"1655280\">a</span> <span m=\"1655320\"\
  >reflection.</span> <span m=\"1661760\">And</span> <span m=\"1661850\">then</span>\
  \ <span m=\"1661940\">you</span> <span m=\"1662030\">see</span> <span m=\"1662300\"\
  >that</span> <span m=\"1663440\">you</span> <span m=\"1663560\">can</span> <span\
  \ m=\"1664850\">write</span> <span m=\"1665150\">this</span> <span m=\"1665360\"\
  >sum</span> <span m=\"1665780\">as</span> <span m=\"1665990\">an</span> <span m=\"\
  1666320\">alternating</span> <span m=\"1666800\">sum</span> <span m=\"1667130\"\
  >of</span> <span m=\"1667790\">principal</span> <span m=\"1668240\">squares,</span>\
  \ <span m=\"1669490\">so</span> <span m=\"1669650\">this</span> <span m=\"1669830\"\
  >one</span> <span m=\"1670640\">big</span> <span m=\"1670820\">square</span> <span\
  \ m=\"1672550\">plus</span> <span m=\"1672880\">the</span> <span m=\"1672970\">middle</span>\
  \ <span m=\"1673240\">square</span> <span m=\"1673750\">and</span> <span m=\"1673960\"\
  >minus</span> <span m=\"1674440\">the</span> <span m=\"1674530\">two</span> <span\
  \ m=\"1675070\">sides</span> <span m=\"1675420\">squares,</span> <span m=\"1676100\"\
  >which</span> <span m=\"1676180\">is</span> <span m=\"1676330\">what</span> <span\
  \ m=\"1678810\">that</span> <span m=\"1679470\">sum</span> <span m=\"1679740\">comes</span>\
  \ <span m=\"1680010\">to.</span></p><p><span m=\"1682080\">All</span> <span m=\"\
  1682190\">right.</span> <span m=\"1683250\">So</span> <span m=\"1683610\">if</span>\
  \ <span m=\"1683790\">we</span> <span m=\"1684000\">assume</span> <span m=\"1684870\"\
  >DISC</span> <span m=\"1685140\">prime,</span> <span m=\"1685920\">then</span> <span\
  \ m=\"1686250\">I</span> <span m=\"1686400\">know</span> <span m=\"1686640\">that</span>\
  \ <span m=\"1686880\">all</span> <span m=\"1687090\">of</span> <span m=\"1687210\"\
  >these</span> <span m=\"1687510\">individual</span> <span m=\"1688170\">sets</span>\
  \ <span m=\"1688560\">have</span> <span m=\"1689400\">roughly</span> <span m=\"\
  1689820\">the</span> <span m=\"1689910\">correct</span> <span m=\"1690720\">number</span>\
  \ <span m=\"1691080\">of</span> <span m=\"1691890\">edges</span> <span m=\"1710520\"\
  >up</span> <span m=\"1710670\">to</span> <span m=\"1710910\">a</span> <span m=\"\
  1712650\">little</span> <span m=\"1712920\">o</span> <span m=\"1713370\">of n</span>\
  \ <span m=\"1713520\">squared</span> <span m=\"1713940\">error.</span> <span m=\"\
  1715120\">And</span> <span m=\"1715320\">again,</span> <span m=\"1715820\">I</span>\
  \ <span m=\"1715950\">don't</span> <span m=\"1716100\">have</span> <span m=\"1716220\"\
  >to</span> <span m=\"1716280\">do</span> <span m=\"1716430\">this</span> <span m=\"\
  1716580\">calculation</span> <span m=\"1717150\">again,</span> <span m=\"1717360\"\
  >because</span> <span m=\"1717960\">it's</span> <span m=\"1718170\">the</span> <span\
  \ m=\"1718230\">same</span> <span m=\"1718500\">calculation.</span> <span m=\"1719440\"\
  >So</span> <span m=\"1719580\">the</span> <span m=\"1719700\">final</span> <span\
  \ m=\"1720030\">thing</span> <span m=\"1720270\">should</span> <span m=\"1720570\"\
  >be</span> <span m=\"1720810\">p</span> <span m=\"1721530\">times</span> <span m=\"\
  1721890\">the</span> <span m=\"1721980\">sizes</span> <span m=\"1722460\">of</span>\
  \ <span m=\"1723570\">x</span> <span m=\"1723810\">and</span> <span m=\"1723900\"\
  >y</span> <span m=\"1724260\">together</span> <span m=\"1724950\">plus</span> <span\
  \ m=\"1725400\">this</span> <span m=\"1726820\">same</span> <span m=\"1727170\"\
  >error.</span></p><p><span m=\"1732770\">So</span> <span m=\"1732890\">that</span>\
  \ <span m=\"1733040\">shows</span> <span m=\"1733280\">you</span> <span m=\"1733460\"\
  >DISC</span> <span m=\"1733730\">prime</span> <span m=\"1734060\">implies</span>\
  \ <span m=\"1734180\">DISC.</span> <span m=\"1735070\">So</span> <span m=\"1735230\"\
  >the</span> <span m=\"1735350\">self</span> <span m=\"1735740\">version</span> <span\
  \ m=\"1736040\">of</span> <span m=\"1736100\">discrepancy</span> <span m=\"1737060\"\
  >implies</span> <span m=\"1737540\">the</span> <span m=\"1737690\">pair</span> <span\
  \ m=\"1738020\">version</span> <span m=\"1738320\">of</span> <span m=\"1738410\"\
  >discrepancy.</span> <span m=\"1742060\">So</span> <span m=\"1742210\">let's</span>\
  \ <span m=\"1742450\">move</span> <span m=\"1742690\">on</span> <span m=\"1742840\"\
  >to</span> <span m=\"1744430\">count.</span> <span m=\"1750820\">To</span> <span\
  \ m=\"1750910\">show</span> <span m=\"1751210\">that</span> <span m=\"1752950\"\
  >DISC</span> <span m=\"1753880\">implies</span> <span m=\"1754480\">count--</span>\
  \ <span m=\"1760180\">actually,</span> <span m=\"1760330\">we</span> <span m=\"\
  1760480\">already</span> <span m=\"1760810\">did</span> <span m=\"1760940\">this.</span></p><p><span\
  \ m=\"1762540\">So</span> <span m=\"1762670\">this</span> <span m=\"1762850\">is</span>\
  \ <span m=\"1762970\">the</span> <span m=\"1763060\">counting</span> <span m=\"\
  1763420\">lemma.</span> <span m=\"1771240\">So</span> <span m=\"1771470\">the</span>\
  \ <span m=\"1771560\">counting</span> <span m=\"1771950\">lemma</span> <span m=\"\
  1772760\">tells</span> <span m=\"1773090\">us</span> <span m=\"1773840\">how</span>\
  \ <span m=\"1774050\">to</span> <span m=\"1774140\">count</span> <span m=\"1775360\"\
  >labeled</span> <span m=\"1775700\">copies</span> <span m=\"1776600\">if</span>\
  \ <span m=\"1776750\">you</span> <span m=\"1776900\">have</span> <span m=\"1777200\"\
  >these</span> <span m=\"1777410\">epsilon</span> <span m=\"1777860\">regularity</span>\
  \ <span m=\"1778430\">conditions,</span> <span m=\"1779280\">which</span> <span\
  \ m=\"1779390\">is</span> <span m=\"1779510\">exactly</span> <span m=\"1779990\"\
  >what</span> <span m=\"1780250\">DISC</span> <span m=\"1780510\">is.</span> <span\
  \ m=\"1784600\">So</span> <span m=\"1785090\">count</span> <span m=\"1785470\">is\
  \ good.</span></p><p><span m=\"1787550\">Another</span> <span m=\"1788210\">easy</span>\
  \ <span m=\"1788540\">implication</span> <span m=\"1790460\">is</span> <span m=\"\
  1791240\">count</span> <span m=\"1791690\">implies</span> <span m=\"1792640\">C4.</span>\
  \ <span m=\"1795210\">Well,</span> <span m=\"1795340\">this</span> <span m=\"1795610\"\
  >is</span> <span m=\"1795730\">actually</span> <span m=\"1796000\">just</span> <span\
  \ m=\"1796210\">tautological.</span> <span m=\"1798560\">C4</span> <span m=\"1799300\"\
  >condition</span> <span m=\"1800470\">is</span> <span m=\"1800950\">a</span> <span\
  \ m=\"1801010\">special</span> <span m=\"1801370\">case</span> <span m=\"1801790\"\
  >of</span> <span m=\"1803200\">the</span> <span m=\"1803470\">count</span> <span\
  \ m=\"1803920\">hypothesis.</span></p><p><span m=\"1808460\">All</span> <span m=\"\
  1808560\">right.</span> <span m=\"1809380\">So</span> <span m=\"1809500\">let's</span>\
  \ <span m=\"1809680\">move</span> <span m=\"1809950\">on</span> <span m=\"1810160\"\
  >to</span> <span m=\"1810880\">some</span> <span m=\"1811180\">additional</span>\
  \ <span m=\"1814310\">implications</span> <span m=\"1814970\">that</span> <span\
  \ m=\"1815090\">require</span> <span m=\"1815540\">a</span> <span m=\"1815570\"\
  >bit</span> <span m=\"1815780\">more</span> <span m=\"1815960\">work.</span> <span\
  \ m=\"1817190\">So</span> <span m=\"1817340\">what</span> <span m=\"1817490\">about</span>\
  \ <span m=\"1818060\">C4</span> <span m=\"1819230\">implies</span> <span m=\"1819800\"\
  >codegree?</span> <span m=\"1826730\">So</span> <span m=\"1826910\">this</span>\
  \ <span m=\"1827090\">is</span> <span m=\"1827180\">where</span> <span m=\"1827420\"\
  >we</span> <span m=\"1827570\">need</span> <span m=\"1827690\">to</span> <span m=\"\
  1827810\">do</span> <span m=\"1827990\">this</span> <span m=\"1828200\">kind</span>\
  \ <span m=\"1828410\">of</span> <span m=\"1828500\">Cauchy-Schwarz</span> <span\
  \ m=\"1829100\">exercise.</span></p><p><span m=\"1830940\">So</span> <span m=\"\
  1830990\">let's</span> <span m=\"1831170\">start</span> <span m=\"1831560\">with</span>\
  \ <span m=\"1832430\">C4.</span> <span m=\"1833780\">So</span> <span m=\"1833930\"\
  >assume</span> <span m=\"1835180\">a</span> <span m=\"1835370\">C4</span> <span\
  \ m=\"1835760\">condition.</span> <span m=\"1838740\">And</span> <span m=\"1839400\"\
  >suppose</span> <span m=\"1841050\">you</span> <span m=\"1841230\">have</span> <span\
  \ m=\"1841710\">this--</span> <span m=\"1847650\">so</span> <span m=\"1847900\"\
  >I</span> <span m=\"1847960\">want</span> <span m=\"1848170\">to</span> <span m=\"\
  1848230\">deduce</span> <span m=\"1848740\">that</span> <span m=\"1849220\">the</span>\
  \ <span m=\"1849610\">codegree</span> <span m=\"1850090\">condition</span> <span\
  \ m=\"1850540\">is</span> <span m=\"1850660\">true.</span> <span m=\"1850840\">But</span>\
  \ <span m=\"1851200\">first,</span> <span m=\"1853470\">let's</span> <span m=\"\
  1855000\">think</span> <span m=\"1855240\">about</span> <span m=\"1856260\">just</span>\
  \ <span m=\"1856500\">what</span> <span m=\"1856710\">is</span> <span m=\"1856830\"\
  >the</span> <span m=\"1856920\">sum</span> <span m=\"1857610\">of</span> <span m=\"\
  1857850\">these</span> <span m=\"1858110\">codegrees</span> <span m=\"1858640\"\
  >as</span> <span m=\"1858920\">I</span> <span m=\"1859120\">vary</span> <span m=\"\
  1859580\">u</span> <span m=\"1859970\">and v</span> <span m=\"1860760\">over all</span>\
  \ <span m=\"1861240\">pairs</span> <span m=\"1861660\">of</span> <span m=\"1861750\"\
  >vertices.</span></p><p><span m=\"1866980\">So</span> <span m=\"1867130\">this</span>\
  \ <span m=\"1867340\">is</span> <span m=\"1868936\">that</span> <span m=\"1869320\"\
  >picture.</span> <span m=\"1871000\">So</span> <span m=\"1871150\">that</span> <span\
  \ m=\"1871360\">is</span> <span m=\"1871510\">equal</span> <span m=\"1871840\">to</span>\
  \ <span m=\"1872430\">the</span> <span m=\"1872530\">sums</span> <span m=\"1873040\"\
  >of</span> <span m=\"1873560\">degrees</span> <span m=\"1874870\">squared,</span>\
  \ <span m=\"1877890\">which</span> <span m=\"1878150\">now,</span> <span m=\"1878390\"\
  >by</span> <span m=\"1878540\">Cauchy-Schwarz,</span> <span m=\"1879530\">you</span>\
  \ <span m=\"1879650\">can</span> <span m=\"1879830\">deduce</span> <span m=\"1880250\"\
  >to</span> <span m=\"1880370\">be</span> <span m=\"1880580\">at</span> <span m=\"\
  1880730\">least</span> <span m=\"1881960\">n</span> <span m=\"1882290\">times</span>\
  \ <span m=\"1883730\">2</span> <span m=\"1884090\">raised</span> <span m=\"1884420\"\
  >to</span> <span m=\"1884540\">number</span> <span m=\"1884840\">of</span> <span\
  \ m=\"1884960\">edges--</span> <span m=\"1885410\">namely,</span> <span m=\"1885710\"\
  >the</span> <span m=\"1885800\">sum</span> <span m=\"1886070\">of</span> <span m=\"\
  1886130\">the</span> <span m=\"1886220\">degrees--</span> <span m=\"1888910\">that</span>\
  \ <span m=\"1889020\">thing</span> <span m=\"1889260\">squared.</span></p><p><span\
  \ m=\"1892760\">So</span> <span m=\"1894040\">now</span> <span m=\"1894430\">we</span>\
  \ <span m=\"1894970\">assume</span> <span m=\"1895540\">the</span> <span m=\"1895720\"\
  >C4</span> <span m=\"1896230\">condition--</span> <span m=\"1897400\">actually,</span>\
  \ <span m=\"1897660\">no,</span> <span m=\"1897750\">we</span> <span m=\"1897970\"\
  >assume</span> <span m=\"1898360\">that</span> <span m=\"1898600\">G</span> <span\
  \ m=\"1898900\">has</span> <span m=\"1899410\">the</span> <span m=\"1900100\">density</span>\
  \ <span m=\"1900560\">as</span> <span m=\"1900770\">written</span> <span m=\"1901420\"\
  >up</span> <span m=\"1901540\">there.</span> <span m=\"1902260\">So</span> <span\
  \ m=\"1903100\">this</span> <span m=\"1903370\">quantity</span> <span m=\"1904240\"\
  >is</span> <span m=\"1905740\">p</span> <span m=\"1907840\">squared</span> <span\
  \ m=\"1908980\">plus</span> <span m=\"1909370\">little</span> <span m=\"1909760\"\
  >1</span> <span m=\"1910920\">times</span> <span m=\"1911890\">n</span> <span m=\"\
  1912130\">cubed,</span> <span m=\"1912850\">which</span> <span m=\"1913030\">is</span>\
  \ <span m=\"1913330\">what</span> <span m=\"1913450\">you</span> <span m=\"1913570\"\
  >should</span> <span m=\"1913780\">expect</span> <span m=\"1914170\">in</span> <span\
  \ m=\"1914320\">a</span> <span m=\"1914350\">random</span> <span m=\"1914710\">graph</span>\
  \ <span m=\"1915250\">of</span> <span m=\"1916040\">Gnp.</span></p><p><span m=\"\
  1919020\">But</span> <span m=\"1919170\">that's</span> <span m=\"1919350\">not</span>\
  \ <span m=\"1919530\">quite</span> <span m=\"1919860\">what</span> <span m=\"1919980\"\
  >we're</span> <span m=\"1920130\">looking</span> <span m=\"1920370\">for.</span>\
  \ <span m=\"1920890\">So</span> <span m=\"1920940\">this</span> <span m=\"1921150\"\
  >is</span> <span m=\"1921300\">just</span> <span m=\"1921870\">the</span> <span\
  \ m=\"1922400\">sum</span> <span m=\"1922770\">of</span> <span m=\"1922860\">the</span>\
  \ <span m=\"1922950\">codegrees.</span> <span m=\"1923880\">What</span> <span m=\"\
  1924030\">we</span> <span m=\"1924240\">actually</span> <span m=\"1924660\">want</span>\
  \ <span m=\"1925260\">is</span> <span m=\"1926130\">the</span> <span m=\"1926910\"\
  >deviation</span> <span m=\"1928110\">of</span> <span m=\"1928320\">codegrees</span>\
  \ <span m=\"1929610\">from</span> <span m=\"1930660\">its</span> <span m=\"1931530\"\
  >expectations,</span> <span m=\"1932250\">so</span> <span m=\"1932400\">to</span>\
  \ <span m=\"1932490\">speak.</span></p><p><span m=\"1934120\">Now,</span> <span\
  \ m=\"1934320\">here's</span> <span m=\"1934780\">an</span> <span m=\"1935100\"\
  >important</span> <span m=\"1935700\">technique</span> <span m=\"1936360\">from</span>\
  \ <span m=\"1937410\">probabilistic</span> <span m=\"1938050\">combinatorics</span>\
  \ <span m=\"1939240\">is</span> <span m=\"1939360\">that</span> <span m=\"1939510\"\
  >if</span> <span m=\"1939750\">you</span> <span m=\"1939930\">want</span> <span\
  \ m=\"1940230\">to</span> <span m=\"1940380\">control</span> <span m=\"1941790\"\
  >the</span> <span m=\"1941910\">deviation</span> <span m=\"1943410\">of</span> <span\
  \ m=\"1943560\">a</span> <span m=\"1943590\">random</span> <span m=\"1943890\">variable,</span>\
  \ <span m=\"1945920\">one</span> <span m=\"1946160\">thing</span> <span m=\"1946450\"\
  >you</span> <span m=\"1946580\">should</span> <span m=\"1946790\">look</span> <span\
  \ m=\"1946970\">at</span> <span m=\"1947090\">is</span> <span m=\"1947450\">the</span>\
  \ <span m=\"1947570\">variance.</span> <span m=\"1948970\">So</span> <span m=\"\
  1949010\">if</span> <span m=\"1949130\">you</span> <span m=\"1949190\">can</span>\
  \ <span m=\"1949340\">control</span> <span m=\"1949730\">the</span> <span m=\"1949850\"\
  >variance,</span> <span m=\"1950780\">then</span> <span m=\"1950960\">you</span>\
  \ <span m=\"1951050\">can</span> <span m=\"1951200\">control</span> <span m=\"1951560\"\
  >the</span> <span m=\"1951650\">deviation.</span></p><p><span m=\"1952710\">And</span>\
  \ <span m=\"1952760\">this</span> <span m=\"1952910\">is</span> <span m=\"1953000\"\
  >a</span> <span m=\"1953060\">method</span> <span m=\"1953320\">known</span> <span\
  \ m=\"1953540\">as</span> <span m=\"1953680\">a</span> <span m=\"1953750\">second</span>\
  \ <span m=\"1954080\">moment</span> <span m=\"1954350\">method.</span> <span m=\"\
  1954650\">And</span> <span m=\"1954740\">that's</span> <span m=\"1954950\">what</span>\
  \ <span m=\"1955100\">we're</span> <span m=\"1955220\">going</span> <span m=\"1955370\"\
  >to</span> <span m=\"1955460\">do</span> <span m=\"1955610\">here.</span> <span\
  \ m=\"1956150\">So</span> <span m=\"1956330\">what</span> <span m=\"1956500\">we'll</span>\
  \ <span m=\"1957730\">try</span> <span m=\"1957920\">to</span> <span m=\"1958010\"\
  >show</span> <span m=\"1958520\">is</span> <span m=\"1958850\">that</span> <span\
  \ m=\"1959180\">the</span> <span m=\"1959990\">second</span> <span m=\"1960470\"\
  >moment</span> <span m=\"1961730\">of</span> <span m=\"1964230\">these</span> <span\
  \ m=\"1964470\">codegrees--</span> <span m=\"1965820\">namely,</span> <span m=\"\
  1966060\">the</span> <span m=\"1966620\">sum</span> <span m=\"1966890\">of</span>\
  \ <span m=\"1966980\">their</span> <span m=\"1967130\">squares--</span> <span m=\"\
  1968030\">is</span> <span m=\"1968180\">also</span> <span m=\"1968870\">what</span>\
  \ <span m=\"1969050\">you</span> <span m=\"1969170\">should</span> <span m=\"1969380\"\
  >expect</span> <span m=\"1970780\">as</span> <span m=\"1971000\">if</span> <span\
  \ m=\"1971440\">the</span> <span m=\"1971690\">random</span> <span m=\"1972050\"\
  >setting.</span> <span m=\"1973060\">And</span> <span m=\"1973190\">then</span>\
  \ <span m=\"1973280\">you</span> <span m=\"1973370\">can</span> <span m=\"1973520\"\
  >put</span> <span m=\"1973670\">them</span> <span m=\"1973790\">together</span>\
  \ <span m=\"1974480\">to</span> <span m=\"1974660\">show</span> <span m=\"1974870\"\
  >what</span> <span m=\"1975020\">you</span> <span m=\"1975140\">want.</span></p><p><span\
  \ m=\"1976775\">So</span> <span m=\"1978600\">this</span> <span m=\"1978810\">quantity</span>\
  \ <span m=\"1979200\">here,</span> <span m=\"1979810\">well,</span> <span m=\"1980740\"\
  >what</span> <span m=\"1980960\">is</span> <span m=\"1981090\">this?</span> <span\
  \ m=\"1981370\">We</span> <span m=\"1982110\">just</span> <span m=\"1982470\">saw--</span>\
  \ <span m=\"1985190\">see,</span> <span m=\"1985760\">up</span> <span m=\"1985940\"\
  >there,</span> <span m=\"1986260\">it's</span> <span m=\"1986680\">also</span> <span\
  \ m=\"1986920\">codegree</span> <span m=\"1987400\">squared.</span> <span m=\"1988790\"\
  >So</span> <span m=\"1989470\">this</span> <span m=\"1989650\">quantity</span> <span\
  \ m=\"1990160\">is</span> <span m=\"1990370\">also</span> <span m=\"1991210\">the</span>\
  \ <span m=\"1991570\">number</span> <span m=\"1992050\">of</span> <span m=\"1992350\"\
  >labeled</span> <span m=\"1992890\">copies</span> <span m=\"1993370\">of</span>\
  \ <span m=\"1993460\">C4--</span> <span m=\"1999280\">not</span> <span m=\"1999580\"\
  >quite,</span> <span m=\"1999940\">because</span> <span m=\"2000270\">you</span>\
  \ <span m=\"2000360\">might</span> <span m=\"2000540\">have</span> <span m=\"2002650\"\
  >two</span> <span m=\"2002890\">vertices</span> <span m=\"2003520\">and</span> <span\
  \ m=\"2004220\">the</span> <span m=\"2004330\">same</span> <span m=\"2004630\">vertex.</span>\
  \ <span m=\"2005390\">So</span> <span m=\"2005740\">I</span> <span m=\"2008200\"\
  >incorporate</span> <span m=\"2008890\">a</span> <span m=\"2008950\">small</span>\
  \ <span m=\"2009360\">error.</span> <span m=\"2010430\">So</span> <span m=\"2010480\"\
  >it's</span> <span m=\"2011440\">a</span> <span m=\"2011500\">cubic</span> <span\
  \ m=\"2011890\">error,</span> <span m=\"2012160\">but it's</span> <span m=\"2012580\"\
  >certainly</span> <span m=\"2013510\">sub</span> <span m=\"2014320\">n</span> <span\
  \ m=\"2014680\">to</span> <span m=\"2014860\">the</span> <span m=\"2014950\">4.</span></p><p><span\
  \ m=\"2017420\">And</span> <span m=\"2017600\">we</span> <span m=\"2017780\">assume</span>\
  \ <span m=\"2018290\">that</span> <span m=\"2018650\">the</span> <span m=\"2018800\"\
  >number</span> <span m=\"2019190\">of</span> <span m=\"2019400\">labeled</span>\
  \ <span m=\"2019760\">copies</span> <span m=\"2020210\">of</span> <span m=\"2020300\"\
  >C4</span> <span m=\"2021980\">by</span> <span m=\"2022160\">the</span> <span m=\"\
  2022250\">C4</span> <span m=\"2022640\">condition</span> <span m=\"2023690\">is</span>\
  \ <span m=\"2024440\">no</span> <span m=\"2024620\">more</span> <span m=\"2024830\"\
  >than</span> <span m=\"2025670\">basically</span> <span m=\"2026090\">p</span> <span\
  \ m=\"2026690\">to</span> <span m=\"2026850\">the</span> <span m=\"2026930\">4</span>\
  \ <span m=\"2027710\">times</span> <span m=\"2028520\">n</span> <span m=\"2029000\"\
  >raised</span> <span m=\"2029270\">to</span> <span m=\"2029360\">power</span> <span\
  \ m=\"2029615\">4.</span> <span m=\"2035910\">OK. So</span> <span m=\"2036080\"\
  >now</span> <span m=\"2036290\">you</span> <span m=\"2036410\">have</span> <span\
  \ m=\"2036590\">a</span> <span m=\"2036680\">first</span> <span m=\"2037100\">moment.</span>\
  \ <span m=\"2037400\">You have</span> <span m=\"2037610\">some</span> <span m=\"\
  2038840\">average,</span> <span m=\"2039410\">and</span> <span m=\"2039530\">you</span>\
  \ <span m=\"2039590\">have</span> <span m=\"2039740\">some</span> <span m=\"2039890\"\
  >control.</span></p><p><span m=\"2040300\">In</span> <span m=\"2040370\">the</span>\
  \ <span m=\"2040430\">second</span> <span m=\"2040760\">moment,</span> <span m=\"\
  2041360\">I</span> <span m=\"2041450\">can</span> <span m=\"2041600\">put</span>\
  \ <span m=\"2041810\">them</span> <span m=\"2041990\">together</span> <span m=\"\
  2042920\">to</span> <span m=\"2043280\">bound</span> <span m=\"2043940\">the</span>\
  \ <span m=\"2044030\">deviation</span> <span m=\"2045110\">using</span> <span m=\"\
  2045440\">this</span> <span m=\"2045620\">idea</span> <span m=\"2045950\">of</span>\
  \ <span m=\"2046040\">controlling</span> <span m=\"2046700\">variance.</span> <span\
  \ m=\"2049921\">So</span> <span m=\"2050413\">the</span> <span m=\"2051397\">codegree</span>\
  \ <span m=\"2055389\">deviation</span> <span m=\"2057340\">is</span> <span m=\"\
  2057699\">upper</span> <span m=\"2058090\">bounded</span> <span m=\"2060040\">by--</span>\
  \ <span m=\"2061060\">so</span> <span m=\"2061290\">here,</span> <span m=\"2061480\"\
  >using</span> <span m=\"2061810\">Cauchy-Schwarz,</span> <span m=\"2062820\">it's</span>\
  \ <span m=\"2063010\">upper</span> <span m=\"2063230\">bounded</span> <span m=\"\
  2064090\">by</span> <span m=\"2066150\">basically</span> <span m=\"2066480\">the</span>\
  \ <span m=\"2066570\">same</span> <span m=\"2066840\">sum,</span> <span m=\"2067170\"\
  >except</span> <span m=\"2067560\">I</span> <span m=\"2067739\">want</span> <span\
  \ m=\"2067949\">to</span> <span m=\"2068010\">square</span> <span m=\"2070590\"\
  >the</span> <span m=\"2071159\">summand.</span></p><p><span m=\"2082536\">This</span>\
  \ <span m=\"2083050\">also</span> <span m=\"2083260\">gets</span> <span m=\"2083469\"\
  >rid</span> <span m=\"2083620\">of</span> <span m=\"2083679\">the</span> <span m=\"\
  2083770\">pesky</span> <span m=\"2084219\">absolute</span> <span m=\"2084699\">value</span>\
  \ <span m=\"2085060\">side,</span> <span m=\"2085520\">which</span> <span m=\"2085630\"\
  >is</span> <span m=\"2085719\">not</span> <span m=\"2086560\">nicely,</span> <span\
  \ m=\"2086949\">algebraically</span> <span m=\"2087550\">behaved.</span> <span m=\"\
  2088630\">OK.</span> <span m=\"2088900\">So now</span> <span m=\"2089139\">I</span>\
  \ <span m=\"2089170\">have</span> <span m=\"2089260\">the</span> <span m=\"2089350\"\
  >square,</span> <span m=\"2089770\">and</span> <span m=\"2089920\">I</span> <span\
  \ m=\"2090010\">can</span> <span m=\"2090250\">expand</span> <span m=\"2090790\"\
  >the</span> <span m=\"2090909\">square.</span> <span m=\"2100810\">So</span> <span\
  \ m=\"2101050\">I</span> <span m=\"2101120\">expand</span> <span m=\"2101540\">the</span>\
  \ <span m=\"2101660\">square</span> <span m=\"2102470\">into</span> <span m=\"2104170\"\
  >these</span> <span m=\"2104380\">terms.</span> <span m=\"2114910\">And</span> <span\
  \ m=\"2115020\">the</span> <span m=\"2115080\">final</span> <span m=\"2115440\"\
  >term</span> <span m=\"2115740\">here</span> <span m=\"2116360\">is</span> <span\
  \ m=\"2116610\">p</span> <span m=\"2116960\">to</span> <span m=\"2117310\">the</span>\
  \ <span m=\"2117660\">4</span> <span m=\"2118860\">n</span> <span m=\"2119310\"\
  >to</span> <span m=\"2119610\">the</span> <span m=\"2119910\">6.</span> <span m=\"\
  2124476\">No,</span> <span m=\"2125570\">n</span> <span m=\"2125780\">to the</span>\
  \ <span m=\"2125870\">4.</span></p><p><span m=\"2129790\">All right.</span> <span\
  \ m=\"2132730\">But</span> <span m=\"2133130\">I</span> <span m=\"2133280\">have</span>\
  \ <span m=\"2133390\">controlled</span> <span m=\"2134110\">the</span> <span m=\"\
  2134530\">individual</span> <span m=\"2135010\">terms</span> <span m=\"2135400\"\
  >from</span> <span m=\"2135640\">the</span> <span m=\"2135700\">calculations</span>\
  \ <span m=\"2136510\">above.</span> <span m=\"2138630\">So</span> <span m=\"2139290\"\
  >I</span> <span m=\"2139380\">can</span> <span m=\"2142010\">upper</span> <span\
  \ m=\"2142220\">bound</span> <span m=\"2142610\">this</span> <span m=\"2142820\"\
  >expression</span> <span m=\"2143660\">by</span> <span m=\"2146710\">what</span>\
  \ <span m=\"2146860\">I'm</span> <span m=\"2146980\">writing</span> <span m=\"2147220\"\
  >down</span> <span m=\"2147400\">now.</span></p><p><span m=\"2154540\">And</span>\
  \ <span m=\"2154750\">basically,</span> <span m=\"2155260\">you</span> <span m=\"\
  2155410\">should</span> <span m=\"2155920\">expect</span> <span m=\"2156430\">that</span>\
  \ <span m=\"2156550\">everything</span> <span m=\"2157420\">should</span> <span\
  \ m=\"2157630\">cancel</span> <span m=\"2158080\">out,</span> <span m=\"2158920\"\
  >because</span> <span m=\"2160120\">they</span> <span m=\"2161020\">do</span> <span\
  \ m=\"2161200\">cancel</span> <span m=\"2161590\">out</span> <span m=\"2161760\"\
  >in</span> <span m=\"2161860\">the</span> <span m=\"2161950\">random</span> <span\
  \ m=\"2162280\">case.</span> <span m=\"2162760\">Of</span> <span m=\"2162880\">course,</span>\
  \ <span m=\"2163120\">the</span> <span m=\"2163210\">sanity</span> <span m=\"2163590\"\
  >check,</span> <span m=\"2163880\">it's</span> <span m=\"2165040\">important</span>\
  \ <span m=\"2165340\">to</span> <span m=\"2165430\">write</span> <span m=\"2165610\"\
  >down</span> <span m=\"2165790\">this</span> <span m=\"2165940\">calculation.</span></p><p><span\
  \ m=\"2167890\">So</span> <span m=\"2167980\">if</span> <span m=\"2168070\">everything</span>\
  \ <span m=\"2168370\">works</span> <span m=\"2168580\">out</span> <span m=\"2168670\"\
  >right,</span> <span m=\"2168850\">everything</span> <span m=\"2169210\">should</span>\
  \ <span m=\"2169360\">cancel</span> <span m=\"2169720\">out.</span> <span m=\"2169950\"\
  >And</span> <span m=\"2170230\">indeed,</span> <span m=\"2170500\">they</span> <span\
  \ m=\"2170620\">do</span> <span m=\"2170770\">cancel</span> <span m=\"2171130\"\
  >out.</span> <span m=\"2171880\">And</span> <span m=\"2172120\">you</span> <span\
  \ m=\"2172510\">get</span> <span m=\"2172870\">that--</span> <span m=\"2174583\"\
  >so this</span> <span m=\"2175014\">is</span> <span m=\"2175445\">a</span> <span\
  \ m=\"2176310\">multiplication.</span> <span m=\"2180020\">This</span> <span m=\"\
  2180210\">is</span> <span m=\"2180960\">p</span> <span m=\"2181780\">squared.</span>\
  \ <span m=\"2184010\">Is that</span> <span m=\"2184475\">OK?</span> <span m=\"2186800\"\
  >So</span> <span m=\"2187630\">everything</span> <span m=\"2187900\">should</span>\
  \ <span m=\"2188050\">cancel</span> <span m=\"2188380\">out.</span> <span m=\"2188860\"\
  >And</span> <span m=\"2188980\">you</span> <span m=\"2189070\">get</span> <span\
  \ m=\"2189210\">a</span> <span m=\"2189220\">little</span> <span m=\"2189700\">o</span>\
  \ <span m=\"2189940\">of</span> <span m=\"2190912\">n</span> <span m=\"2191398\"\
  >cubed.</span></p><p><span m=\"2194320\">To</span> <span m=\"2194410\">summarize,</span>\
  \ <span m=\"2196320\">in</span> <span m=\"2196480\">this</span> <span m=\"2197080\"\
  >implication</span> <span m=\"2197620\">from</span> <span m=\"2197860\">C4</span>\
  \ <span m=\"2198550\">to</span> <span m=\"2200500\">codegree,</span> <span m=\"\
  2202130\">what</span> <span m=\"2202340\">we're</span> <span m=\"2202460\">doing</span>\
  \ <span m=\"2202760\">is</span> <span m=\"2202910\">we're</span> <span m=\"2203750\"\
  >controlling</span> <span m=\"2205010\">the</span> <span m=\"2205910\">variance</span>\
  \ <span m=\"2206960\">of</span> <span m=\"2207350\">codegrees</span> <span m=\"\
  2208640\">using</span> <span m=\"2209000\">the</span> <span m=\"2209090\">C4</span>\
  \ <span m=\"2209540\">condition</span> <span m=\"2210640\">and</span> <span m=\"\
  2210800\">the</span> <span m=\"2210860\">second</span> <span m=\"2211190\">moment</span>\
  \ <span m=\"2211450\">bound,</span> <span m=\"2213950\">showing</span> <span m=\"\
  2214340\">that</span> <span m=\"2214580\">the</span> <span m=\"2214670\">C4</span>\
  \ <span m=\"2215540\">condition</span> <span m=\"2216460\">trumps</span> <span m=\"\
  2216860\">over</span> <span m=\"2217230\">the</span> <span m=\"2217460\">codegree</span>\
  \ <span m=\"2217940\">condition.</span> <span m=\"2221830\">Any</span> <span m=\"\
  2222010\">questions</span> <span m=\"2222400\">so</span> <span m=\"2222640\">far?</span></p><p><span\
  \ m=\"2228100\">So</span> <span m=\"2228360\">I'll</span> <span m=\"2229170\">let</span>\
  \ <span m=\"2229320\">you</span> <span m=\"2229410\">ponder</span> <span m=\"2229750\"\
  >in</span> <span m=\"2229860\">this</span> <span m=\"2229980\">calculation.</span>\
  \ <span m=\"2230490\">The</span> <span m=\"2230580\">next</span> <span m=\"2230910\"\
  >one</span> <span m=\"2231210\">that</span> <span m=\"2231360\">we'll</span> <span\
  \ m=\"2231510\">do</span> <span m=\"2231750\">is</span> <span m=\"2231900\">codegree</span>\
  \ <span m=\"2232710\">implies</span> <span m=\"2234090\">DISC.</span> <span m=\"\
  2235390\">And</span> <span m=\"2235600\">that</span> <span m=\"2235770\">will</span>\
  \ <span m=\"2235920\">be</span> <span m=\"2237300\">a</span> <span m=\"2237360\"\
  >calculation</span> <span m=\"2237690\">in a</span> <span m=\"2238020\">very</span>\
  \ <span m=\"2238260\">similar</span> <span m=\"2238980\">flavor.</span> <span m=\"\
  2241350\">But</span> <span m=\"2241460\">it</span> <span m=\"2241570\">will</span>\
  \ <span m=\"2241660\">be</span> <span m=\"2241780\">a</span> <span m=\"2241840\"\
  >slightly</span> <span m=\"2242200\">longer</span> <span m=\"2242500\">but</span>\
  \ <span m=\"2242710\">with</span> <span m=\"2242800\">similar</span> <span m=\"\
  2243160\">flavor of</span> <span m=\"2243490\">calculation.</span> <span m=\"2244370\"\
  >So</span> <span m=\"2244510\">let</span> <span m=\"2244600\">me</span> <span m=\"\
  2244720\">do</span> <span m=\"2244840\">that</span> <span m=\"2244960\">after</span>\
  \ <span m=\"2245200\">the</span> <span m=\"2245290\">break.</span></p><p><span m=\"\
  2247384\">All</span> <span m=\"2247855\">right.</span> <span m=\"2249740\">So</span>\
  \ <span m=\"2249790\">what</span> <span m=\"2249930\">have</span> <span m=\"2249970\"\
  >we</span> <span m=\"2250150\">done</span> <span m=\"2250360\">so</span> <span m=\"\
  2250510\">far?</span> <span m=\"2251200\">So</span> <span m=\"2251290\">let's</span>\
  \ <span m=\"2251470\">summarize</span> <span m=\"2252580\">the</span> <span m=\"\
  2253000\">chain</span> <span m=\"2253330\">of</span> <span m=\"2253420\">implications</span>\
  \ <span m=\"2254080\">that</span> <span m=\"2254290\">we</span> <span m=\"2254470\"\
  >have</span> <span m=\"2254590\">already</span> <span m=\"2254890\">proved.</span>\
  \ <span m=\"2256240\">So</span> <span m=\"2256390\">first,</span> <span m=\"2257020\"\
  >we</span> <span m=\"2257260\">started</span> <span m=\"2257740\">with</span> <span\
  \ m=\"2258310\">showing</span> <span m=\"2258850\">that</span> <span m=\"2259290\"\
  >the</span> <span m=\"2259450\">two</span> <span m=\"2259900\">versions</span> <span\
  \ m=\"2260350\">of</span> <span m=\"2260470\">DISC</span> <span m=\"2262000\">are</span>\
  \ <span m=\"2262510\">equivalent.</span> <span m=\"2268500\">And</span> <span m=\"\
  2268620\">then</span> <span m=\"2269640\">we</span> <span m=\"2269910\">also</span>\
  \ <span m=\"2270180\">noticed</span> <span m=\"2270810\">that</span> <span m=\"\
  2272220\">DISC</span> <span m=\"2272770\">implies</span> <span m=\"2275010\">count</span>\
  \ <span m=\"2275610\">through</span> <span m=\"2275790\">the</span> <span m=\"2275880\"\
  >counting</span> <span m=\"2276210\">lemma.</span> <span m=\"2278700\">So</span>\
  \ <span m=\"2278880\">we</span> <span m=\"2279090\">also</span> <span m=\"2281730\"\
  >observed</span> <span m=\"2282150\">that</span> <span m=\"2282300\">count</span>\
  \ <span m=\"2282730\">implies</span> <span m=\"2283020\">C4</span> <span m=\"2284030\"\
  >tautologically</span> <span m=\"2286090\">and</span> <span m=\"2286390\">C4</span>\
  \ <span m=\"2287620\">implies</span> <span m=\"2288420\">codegree.</span></p><p><span\
  \ m=\"2294670\">So</span> <span m=\"2294830\">the</span> <span m=\"2294920\">next</span>\
  \ <span m=\"2295160\">natural</span> <span m=\"2295460\">thing</span> <span m=\"\
  2295700\">to</span> <span m=\"2295850\">do</span> <span m=\"2296090\">is</span>\
  \ <span m=\"2296210\">to</span> <span m=\"2296330\">complete</span> <span m=\"2296750\"\
  >this</span> <span m=\"2297470\">circuit</span> <span m=\"2298190\">and</span> <span\
  \ m=\"2298400\">show</span> <span m=\"2298670\">that</span> <span m=\"2299310\"\
  >the</span> <span m=\"2299400\">codegree</span> <span m=\"2299840\">condition</span>\
  \ <span m=\"2300380\">implies</span> <span m=\"2301400\">the</span> <span m=\"2301700\"\
  >discrepancy</span> <span m=\"2302360\">condition.</span> <span m=\"2304680\">So</span>\
  \ <span m=\"2304880\">that's</span> <span m=\"2305060\">what</span> <span m=\"2305180\"\
  >we'll</span> <span m=\"2305270\">do</span> <span m=\"2305390\">next.</span></p><p><span\
  \ m=\"2308760\">And</span> <span m=\"2309140\">in</span> <span m=\"2309240\">some</span>\
  \ <span m=\"2309420\">sense,</span> <span m=\"2310530\">these</span> <span m=\"\
  2310770\">two</span> <span m=\"2311010\">steps,</span> <span m=\"2311880\">you</span>\
  \ <span m=\"2311970\">should</span> <span m=\"2312150\">think</span> <span m=\"\
  2312420\">of</span> <span m=\"2312510\">them</span> <span m=\"2312720\">as</span>\
  \ <span m=\"2313040\">going</span> <span m=\"2313890\">in</span> <span m=\"2314010\"\
  >this</span> <span m=\"2314280\">natural</span> <span m=\"2314790\">chain,</span>\
  \ <span m=\"2315660\">where</span> <span m=\"2316280\">C4--</span> <span m=\"2317610\"\
  >so</span> <span m=\"2318660\">C4</span> <span m=\"2319110\">is</span> <span m=\"\
  2321130\">like</span> <span m=\"2321480\">this,</span> <span m=\"2322190\">C4.</span>\
  \ <span m=\"2323200\">Codegree</span> <span m=\"2323700\">condition</span> <span\
  \ m=\"2324150\">is</span> <span m=\"2324330\">really</span> <span m=\"2324540\"\
  >about</span> <span m=\"2325900\">that.</span> <span m=\"2326680\">And</span> <span\
  \ m=\"2326930\">DISC</span> <span m=\"2327130\">is</span> <span m=\"2327300\">really</span>\
  \ <span m=\"2327480\">about</span> <span m=\"2327750\">single</span> <span m=\"\
  2328260\">edges.</span> <span m=\"2329220\">So</span> <span m=\"2329320\">you</span>\
  \ <span m=\"2329420\">can</span> <span m=\"2329520\">go</span> <span m=\"2329610\"\
  >from--</span> <span m=\"2330440\">so</span> <span m=\"2330790\">double--</span>\
  \ <span m=\"2332646\">if</span> <span m=\"2333110\">you</span> <span m=\"2333230\"\
  >half,</span> <span m=\"2333940\">you</span> <span m=\"2334370\">get</span> <span\
  \ m=\"2334530\">much</span> <span m=\"2334770\">more</span> <span m=\"2334920\"\
  >power.</span> <span m=\"2335520\">So</span> <span m=\"2335780\">it's</span> <span\
  \ m=\"2336000\">going</span> <span m=\"2336270\">in</span> <span m=\"2336360\">the</span>\
  \ <span m=\"2336450\">right</span> <span m=\"2336660\">direction,</span> <span m=\"\
  2337560\">going</span> <span m=\"2337800\">downstream,</span> <span m=\"2338760\"\
  >so</span> <span m=\"2338940\">to</span> <span m=\"2339030\">speak.</span> <span\
  \ m=\"2339940\">So</span> <span m=\"2340040\">that's</span> <span m=\"2340140\"\
  >what</span> <span m=\"2340260\">we're</span> <span m=\"2340380\">doing</span> <span\
  \ m=\"2340610\">now,</span> <span m=\"2340740\">going</span> <span m=\"2341010\"\
  >downstream.</span> <span m=\"2343470\">And</span> <span m=\"2343560\">then</span>\
  \ <span m=\"2343650\">you</span> <span m=\"2343740\">go</span> <span m=\"2343920\"\
  >upstream</span> <span m=\"2344430\">via</span> <span m=\"2345000\">the</span> <span\
  \ m=\"2345100\">counting</span> <span m=\"2345310\">lemma.</span></p><p><span m=\"\
  2348523\">All right.</span> <span m=\"2350360\">Let's</span> <span m=\"2350540\"\
  >do</span> <span m=\"2351230\">codegree</span> <span m=\"2352160\">implies</span>\
  \ <span m=\"2352740\">DISC.</span> <span m=\"2364670\">So</span> <span m=\"2365750\"\
  >we</span> <span m=\"2366620\">want</span> <span m=\"2366890\">to</span> <span m=\"\
  2367010\">show</span> <span m=\"2367610\">the</span> <span m=\"2367910\">discrepancy</span>\
  \ <span m=\"2368540\">condition,</span> <span m=\"2368960\">which</span> <span m=\"\
  2369140\">is</span> <span m=\"2369260\">one</span> <span m=\"2369470\">written</span>\
  \ <span m=\"2369710\">up</span> <span m=\"2369800\">there.</span> <span m=\"2370310\"\
  >But</span> <span m=\"2370460\">before</span> <span m=\"2370790\">that,</span> <span\
  \ m=\"2371030\">let</span> <span m=\"2371180\">me</span> <span m=\"2371330\">first</span>\
  \ <span m=\"2371720\">show</span> <span m=\"2372020\">you</span> <span m=\"2372290\"\
  >that</span> <span m=\"2373040\">the</span> <span m=\"2373520\">degrees</span> <span\
  \ m=\"2374660\">do</span> <span m=\"2374810\">not</span> <span m=\"2375080\">vary</span>\
  \ <span m=\"2375350\">too</span> <span m=\"2375560\">much,</span> <span m=\"2376460\"\
  >show</span> <span m=\"2376790\">that</span> <span m=\"2377000\">the</span> <span\
  \ m=\"2377120\">degrees</span> <span m=\"2377660\">are</span> <span m=\"2377720\"\
  >fairly</span> <span m=\"2378050\">well</span> <span m=\"2378230\">distributed,</span>\
  \ <span m=\"2379010\">which</span> <span m=\"2379220\">is</span> <span m=\"2379340\"\
  >what</span> <span m=\"2379460\">you</span> <span m=\"2379610\">should</span> <span\
  \ m=\"2379820\">expect</span> <span m=\"2380270\">in</span> <span m=\"2380350\"\
  >a</span> <span m=\"2380750\">pseudorandom</span> <span m=\"2381440\">graph.</span></p><p><span\
  \ m=\"2382580\">So</span> <span m=\"2382700\">you</span> <span m=\"2382790\">don't</span>\
  \ <span m=\"2382970\">expect</span> <span m=\"2383330\">the</span> <span m=\"2383420\"\
  >half</span> <span m=\"2383750\">the</span> <span m=\"2383840\">vertices,</span>\
  \ <span m=\"2384350\">half</span> <span m=\"2384650\">in</span> <span m=\"2384770\"\
  >degrees,</span> <span m=\"2385880\">twice</span> <span m=\"2386540\">the</span>\
  \ <span m=\"2386660\">other</span> <span m=\"2386870\">half.</span> <span m=\"2388500\"\
  >So</span> <span m=\"2389090\">that's</span> <span m=\"2389360\">the</span> <span\
  \ m=\"2389450\">first</span> <span m=\"2389690\">thing</span> <span m=\"2389870\"\
  >I</span> <span m=\"2389960\">want</span> <span m=\"2390140\">to</span> <span m=\"\
  2390230\">establish.</span> <span m=\"2393920\">If</span> <span m=\"2394040\">you</span>\
  \ <span m=\"2394160\">look</span> <span m=\"2394340\">at</span> <span m=\"2395370\"\
  >degrees,</span> <span m=\"2399550\">this</span> <span m=\"2400450\">variance,</span>\
  \ <span m=\"2401150\">this</span> <span m=\"2401890\">deviation,</span> <span m=\"\
  2402910\">is</span> <span m=\"2405130\">not</span> <span m=\"2405370\">too</span>\
  \ <span m=\"2405550\">big.</span></p><p><span m=\"2406640\">OK.</span> <span m=\"\
  2407050\">So</span> <span m=\"2407680\">like</span> <span m=\"2407890\">before,</span>\
  \ <span m=\"2408160\">we</span> <span m=\"2408280\">see</span> <span m=\"2408400\"\
  >an</span> <span m=\"2408550\">absolute</span> <span m=\"2408940\">value</span>\
  \ <span m=\"2409210\">sign.</span> <span m=\"2409450\">We see</span> <span m=\"\
  2409640\">a</span> <span m=\"2409770\">sum.</span> <span m=\"2410420\">So</span>\
  \ <span m=\"2410470\">we'll</span> <span m=\"2410630\">do</span> <span m=\"2410760\"\
  >Cauchy-Schwarz.</span> <span m=\"2412696\">Cauchy-Schwarz</span> <span m=\"2413570\"\
  >allows</span> <span m=\"2413930\">us</span> <span m=\"2414080\">to</span> <span\
  \ m=\"2414200\">bound</span> <span m=\"2415160\">this</span> <span m=\"2415310\"\
  >quantity,</span> <span m=\"2416630\">replacing</span> <span m=\"2417690\">the</span>\
  \ <span m=\"2417800\">summand</span> <span m=\"2418430\">by</span> <span m=\"2419450\"\
  >a</span> <span m=\"2419510\">sum</span> <span m=\"2419900\">of</span> <span m=\"\
  2420020\">squared.</span></p><p><span m=\"2433210\">I</span> <span m=\"2433525\"\
  >have a</span> <span m=\"2433840\">square,</span> <span m=\"2434170\">so</span>\
  \ <span m=\"2434320\">I</span> <span m=\"2434380\">can</span> <span m=\"2434530\"\
  >expand</span> <span m=\"2435010\">the</span> <span m=\"2435160\">square.</span>\
  \ <span m=\"2441060\">So</span> <span m=\"2441250\">let</span> <span m=\"2441370\"\
  >me</span> <span m=\"2441520\">expand</span> <span m=\"2442120\">the</span> <span\
  \ m=\"2442240\">square.</span> <span m=\"2443310\">And</span> <span m=\"2456020\"\
  >I get</span> <span m=\"2456512\">that,</span> <span m=\"2458010\">so</span> <span\
  \ m=\"2458380\">just</span> <span m=\"2458590\">expanding</span> <span m=\"2459520\"\
  >this</span> <span m=\"2460090\">square</span> <span m=\"2461550\">inside.</span></p><p><span\
  \ m=\"2464708\">And</span> <span m=\"2465610\">you</span> <span m=\"2465700\">see</span>\
  \ <span m=\"2465940\">this</span> <span m=\"2466530\">degree</span> <span m=\"2467020\"\
  >squared</span> <span m=\"2468670\">is</span> <span m=\"2469420\">that</span> <span\
  \ m=\"2469600\">picture,</span> <span m=\"2470080\">so</span> <span m=\"2470260\"\
  >that</span> <span m=\"2470490\">sum</span> <span m=\"2470950\">of</span> <span\
  \ m=\"2471040\">codegrees.</span> <span m=\"2484280\">And</span> <span m=\"2484940\"\
  >sum</span> <span m=\"2485210\">of</span> <span m=\"2485300\">the</span> <span m=\"\
  2485540\">degrees</span> <span m=\"2486070\">is</span> <span m=\"2486230\">just\
  \ the</span> <span m=\"2486460\">number</span> <span m=\"2486830\">of</span> <span\
  \ m=\"2486990\">edges.</span> <span m=\"2499630\">But</span> <span m=\"2499930\"\
  >we</span> <span m=\"2500110\">now</span> <span m=\"2500350\">assume</span> <span\
  \ m=\"2500740\">the</span> <span m=\"2500830\">codegree</span> <span m=\"2501340\"\
  >condition,</span> <span m=\"2502750\">which</span> <span m=\"2503080\">in</span>\
  \ <span m=\"2503200\">particular</span> <span m=\"2504160\">implies</span> <span\
  \ m=\"2504760\">that</span> <span m=\"2504880\">the</span> <span m=\"2504970\">sum\
  \ of</span> <span m=\"2505390\">the</span> <span m=\"2505510\">codegrees</span>\
  \ <span m=\"2506260\">is</span> <span m=\"2506560\">roughly</span> <span m=\"2506980\"\
  >what</span> <span m=\"2507130\">you</span> <span m=\"2507220\">would</span> <span\
  \ m=\"2507310\">expect.</span> <span m=\"2510170\">So</span> <span m=\"2510280\"\
  >the</span> <span m=\"2510400\">sum</span> <span m=\"2510730\">of</span> <span m=\"\
  2510790\">the</span> <span m=\"2510880\">codegrees</span> <span m=\"2511930\">should</span>\
  \ <span m=\"2512170\">be</span> <span m=\"2512410\">p</span> <span m=\"2512710\"\
  >squared</span> <span m=\"2513700\">n</span> <span m=\"2513940\">cubed</span> <span\
  \ m=\"2514690\">plus</span> <span m=\"2516610\">a</span> <span m=\"2516760\">little</span>\
  \ <span m=\"2517060\">o</span> <span m=\"2517570\">n</span> <span m=\"2517840\"\
  >cubed</span> <span m=\"2518210\">error</span> <span m=\"2518650\">at</span> <span\
  \ m=\"2518770\">the</span> <span m=\"2518890\">end.</span></p><p><span m=\"2521250\"\
  >Likewise,</span> <span m=\"2521820\">the</span> <span m=\"2522120\">number</span>\
  \ <span m=\"2522480\">of</span> <span m=\"2522630\">edges</span> <span m=\"2523260\"\
  >is,</span> <span m=\"2523590\">by</span> <span m=\"2523800\">assumption,</span>\
  \ <span m=\"2525630\">what</span> <span m=\"2525930\">you</span> <span m=\"2526050\"\
  >would</span> <span m=\"2526200\">expect</span> <span m=\"2526920\">in</span> <span\
  \ m=\"2527220\">a</span> <span m=\"2527550\">random</span> <span m=\"2527910\">graph.</span>\
  \ <span m=\"2530130\">And</span> <span m=\"2530250\">then</span> <span m=\"2530380\"\
  >the</span> <span m=\"2530430\">final</span> <span m=\"2530790\">term.</span> <span\
  \ m=\"2533480\">And</span> <span m=\"2533720\">like</span> <span m=\"2533990\">before--</span>\
  \ <span m=\"2534780\">and</span> <span m=\"2535180\">of</span> <span m=\"2535280\"\
  >course,</span> <span m=\"2535490\">it's</span> <span m=\"2535640\">good</span>\
  \ <span m=\"2535940\">to</span> <span m=\"2536060\">do</span> <span m=\"2536430\"\
  >a</span> <span m=\"2536690\">sanity</span> <span m=\"2537020\">check--</span> <span\
  \ m=\"2537560\">everything</span> <span m=\"2538070\">should</span> <span m=\"2538400\"\
  >cancel</span> <span m=\"2538970\">out.</span></p><p><span m=\"2539750\">So</span>\
  \ <span m=\"2539990\">what</span> <span m=\"2540170\">you</span> <span m=\"2540320\"\
  >end</span> <span m=\"2540530\">up</span> <span m=\"2540680\">with</span> <span\
  \ m=\"2541010\">is</span> <span m=\"2541220\">little</span> <span m=\"2541470\"\
  >o</span> <span m=\"2541790\">of</span> <span m=\"2542030\">n</span> <span m=\"\
  2542270\">squared,</span> <span m=\"2545310\">showing</span> <span m=\"2545700\"\
  >that</span> <span m=\"2545850\">the</span> <span m=\"2545950\">degrees</span> <span\
  \ m=\"2546480\">do</span> <span m=\"2546660\">not</span> <span m=\"2546840\">vary</span>\
  \ <span m=\"2547110\">too</span> <span m=\"2547290\">much.</span> <span m=\"2548070\"\
  >And</span> <span m=\"2548190\">once</span> <span m=\"2548460\">you</span> <span\
  \ m=\"2548580\">have</span> <span m=\"2549630\">that</span> <span m=\"2549840\"\
  >promise,</span> <span m=\"2550710\">then</span> <span m=\"2551160\">we</span> <span\
  \ m=\"2551790\">move</span> <span m=\"2552000\">onto</span> <span m=\"2553260\"\
  >the</span> <span m=\"2553380\">actual</span> <span m=\"2553800\">discrepancy</span>\
  \ <span m=\"2554490\">condition.</span> <span m=\"2561570\">So</span> <span m=\"\
  2562100\">this</span> <span m=\"2562310\">discrepancy</span> <span m=\"2566438\"\
  >can</span> <span m=\"2566890\">be</span> <span m=\"2567010\">rewritten</span> <span\
  \ m=\"2567850\">as</span> <span m=\"2568660\">the</span> <span m=\"2568780\">sum</span>\
  \ <span m=\"2570130\">over</span> <span m=\"2571390\">vertices</span> <span m=\"\
  2571870\">little</span> <span m=\"2572140\">x</span> <span m=\"2572860\">and</span>\
  \ <span m=\"2573250\">big</span> <span m=\"2573470\">X,</span> <span m=\"2575955\"\
  >the</span> <span m=\"2576380\">degree</span> <span m=\"2577760\">from</span> <span\
  \ m=\"2578630\">little</span> <span m=\"2578900\">x</span> <span m=\"2580130\">to</span>\
  \ <span m=\"2580370\">y</span> <span m=\"2581660\">minus</span> <span m=\"2583280\"\
  >p</span> <span m=\"2583880\">times</span> <span m=\"2584480\">the</span> <span\
  \ m=\"2584540\">size</span> <span m=\"2585020\">of</span> <span m=\"2585140\">y,</span>\
  \ <span m=\"2588212\">so</span> <span m=\"2588690\">rewriting</span> <span m=\"\
  2589250\">the</span> <span m=\"2589420\">sum.</span></p><p><span m=\"2591362\">And</span>\
  \ <span m=\"2591790\">of</span> <span m=\"2591850\">course,</span> <span m=\"2592330\"\
  >what</span> <span m=\"2592480\">should</span> <span m=\"2592720\">we</span> <span\
  \ m=\"2593260\">do</span> <span m=\"2593410\">next?</span> <span m=\"2596090\">Cauchy-Schwarz.</span>\
  \ <span m=\"2596950\">Great.</span> <span m=\"2597560\">So</span> <span m=\"2597710\"\
  >we'll</span> <span m=\"2597890\">do</span> <span m=\"2598510\">a</span> <span m=\"\
  2598660\">Cauchy-Schwarz.</span> <span m=\"2601010\">OK,</span> <span m=\"2601180\"\
  >so</span> <span m=\"2601880\">here's</span> <span m=\"2602390\">an</span> <span\
  \ m=\"2603140\">important</span> <span m=\"2603980\">step</span> <span m=\"2604460\"\
  >or</span> <span m=\"2604760\">trick,</span> <span m=\"2605220\">if</span> <span\
  \ m=\"2605240\">you</span> <span m=\"2605390\">will.</span> <span m=\"2606180\"\
  >So</span> <span m=\"2606200\">we'll</span> <span m=\"2606350\">do</span> <span\
  \ m=\"2606500\">Cauchy-Schwarz.</span></p><p><span m=\"2608990\">And</span> <span\
  \ m=\"2610470\">something</span> <span m=\"2611040\">very</span> <span m=\"2611280\"\
  >nice</span> <span m=\"2611640\">happens</span> <span m=\"2613050\">when</span>\
  \ <span m=\"2613240\">you</span> <span m=\"2613400\">do Cauchy-Schwarz</span> <span\
  \ m=\"2614070\">here.</span> <span m=\"2615080\">OK.</span> <span m=\"2615780\"\
  >So</span> <span m=\"2616230\">you</span> <span m=\"2616320\">can</span> <span m=\"\
  2616440\">write</span> <span m=\"2616620\">down</span> <span m=\"2616800\">the</span>\
  \ <span m=\"2616860\">expression</span> <span m=\"2617340\">that</span> <span m=\"\
  2617460\">you</span> <span m=\"2617580\">obtain</span> <span m=\"2619640\">when\
  \ you do</span> <span m=\"2619800\">Cauchy-Schwarz.</span> <span m=\"2620070\">So</span>\
  \ <span m=\"2620550\">let</span> <span m=\"2620670\">me</span> <span m=\"2620760\"\
  >do</span> <span m=\"2620910\">that</span> <span m=\"2621060\">first.</span></p><p><span\
  \ m=\"2627770\">OK.</span> <span m=\"2627990\">So</span> <span m=\"2628480\">here's</span>\
  \ <span m=\"2628740\">a</span> <span m=\"2628800\">step</span> <span m=\"2629160\"\
  >which</span> <span m=\"2629400\">is</span> <span m=\"2629610\">very</span> <span\
  \ m=\"2630510\">easy</span> <span m=\"2630810\">to</span> <span m=\"2630930\">gloss</span>\
  \ <span m=\"2631350\">over.</span> <span m=\"2631690\">But</span> <span m=\"2631740\"\
  >I</span> <span m=\"2632010\">want</span> <span m=\"2632220\">to</span> <span m=\"\
  2632280\">pause</span> <span m=\"2632640\">and</span> <span m=\"2632760\">emphasize</span>\
  \ <span m=\"2633240\">this</span> <span m=\"2633360\">step,</span> <span m=\"2633600\"\
  >because</span> <span m=\"2633840\">this</span> <span m=\"2633990\">is</span> <span\
  \ m=\"2634080\">actually</span> <span m=\"2634440\">really</span> <span m=\"2634680\"\
  >important.</span> <span m=\"2637170\">What</span> <span m=\"2637280\">I'm</span>\
  \ <span m=\"2637370\">going</span> <span m=\"2637580\">to</span> <span m=\"2637670\"\
  >do</span> <span m=\"2637790\">now</span> <span m=\"2638420\">is</span> <span m=\"\
  2638570\">to</span> <span m=\"2638750\">observe</span> <span m=\"2639350\">that</span>\
  \ <span m=\"2639570\">the</span> <span m=\"2639610\">summand</span> <span m=\"2640100\"\
  >is</span> <span m=\"2640250\">always</span> <span m=\"2640520\">non-negative.</span>\
  \ <span m=\"2647390\">Therefore,</span> <span m=\"2648170\">I</span> <span m=\"\
  2648260\">can</span> <span m=\"2648470\">enlarge</span> <span m=\"2651970\">the</span>\
  \ <span m=\"2652810\">sum</span> <span m=\"2653320\">from</span> <span m=\"2653770\"\
  >just</span> <span m=\"2654160\">little</span> <span m=\"2654400\">x</span> <span\
  \ m=\"2654740\">and X</span> <span m=\"2655120\">to</span> <span m=\"2655330\">the</span>\
  \ <span m=\"2655420\">entire</span> <span m=\"2655840\">vertex</span> <span m=\"\
  2656210\">set.</span></p><p><span m=\"2658760\">And</span> <span m=\"2658880\">this</span>\
  \ <span m=\"2659060\">is</span> <span m=\"2659210\">important,</span> <span m=\"\
  2659600\">right?</span> <span m=\"2659750\">So</span> <span m=\"2660140\">it's</span>\
  \ <span m=\"2660350\">important</span> <span m=\"2660650\">that</span> <span m=\"\
  2660720\">we</span> <span m=\"2660860\">had</span> <span m=\"2661040\">to</span>\
  \ <span m=\"2661130\">do</span> <span m=\"2661280\">Cauchy-Schwarz</span> <span\
  \ m=\"2661850\">first</span> <span m=\"2662060\">to</span> <span m=\"2662150\">get</span>\
  \ <span m=\"2662330\">a</span> <span m=\"2662390\">non-negative</span> <span m=\"\
  2663380\">summand.</span> <span m=\"2663950\">You</span> <span m=\"2664070\">couldn't</span>\
  \ <span m=\"2664310\">do</span> <span m=\"2664430\">this</span> <span m=\"2664580\"\
  >in</span> <span m=\"2664670\">the</span> <span m=\"2664730\">beginning.</span>\
  \ <span m=\"2669800\">So</span> <span m=\"2669950\">you</span> <span m=\"2670040\"\
  >do</span> <span m=\"2670160\">that.</span> <span m=\"2672450\">And</span> <span\
  \ m=\"2673260\">so</span> <span m=\"2673410\">I</span> <span m=\"2673500\">have</span>\
  \ <span m=\"2673740\">this</span> <span m=\"2674270\">sum</span> <span m=\"2674550\"\
  >of</span> <span m=\"2674640\">squares.</span> <span m=\"2675120\">I</span> <span\
  \ m=\"2675780\">expand.</span> <span m=\"2683300\">I</span> <span m=\"2683610\"\
  >expand.</span> <span m=\"2684270\">I</span> <span m=\"2685560\">write</span> <span\
  \ m=\"2685820\">out</span> <span m=\"2686250\">all</span> <span m=\"2686370\">these</span>\
  \ <span m=\"2686610\">expressions.</span> <span m=\"2697300\">And</span> <span m=\"\
  2697400\">now</span> <span m=\"2698310\">the</span> <span m=\"2698400\">little</span>\
  \ <span m=\"2698640\">x</span> <span m=\"2698910\">range</span> <span m=\"2699240\"\
  >over</span> <span m=\"2699450\">the</span> <span m=\"2699540\">entire</span> <span\
  \ m=\"2699990\">vertex</span> <span m=\"2700430\">set.</span></p><p><span m=\"2715715\"\
  >All right.</span> <span m=\"2717200\">So</span> <span m=\"2717320\">what</span>\
  \ <span m=\"2717470\">was</span> <span m=\"2717620\">the</span> <span m=\"2717680\"\
  >point</span> <span m=\"2717920\">of</span> <span m=\"2718010\">all</span> <span\
  \ m=\"2718130\">of</span> <span m=\"2718200\">that?</span> <span m=\"2720780\">So</span>\
  \ <span m=\"2720880\">you</span> <span m=\"2720980\">see</span> <span m=\"2721390\"\
  >this</span> <span m=\"2721690\">expression</span> <span m=\"2722260\">here,</span>\
  \ <span m=\"2723620\">the</span> <span m=\"2723710\">degree</span> <span m=\"2725000\"\
  >from</span> <span m=\"2725270\">little</span> <span m=\"2725510\">x</span> <span\
  \ m=\"2725780\">to</span> <span m=\"2726140\">big</span> <span m=\"2726380\">Y</span>\
  \ <span m=\"2727130\">squared,</span> <span m=\"2730370\">what</span> <span m=\"\
  2730580\">is</span> <span m=\"2731000\">that?</span> <span m=\"2731870\">How</span>\
  \ <span m=\"2732080\">can</span> <span m=\"2732230\">we</span> <span m=\"2732500\"\
  >rewrite</span> <span m=\"2733070\">this</span> <span m=\"2733280\">expression?</span>\
  \ <span m=\"2738550\">So</span> <span m=\"2739345\">counting</span> <span m=\"2739780\"\
  >little</span> <span m=\"2740110\">x</span> <span m=\"2740410\">and then</span>\
  \ <span m=\"2740770\">Y</span> <span m=\"2741490\">squared--</span></p><p><span\
  \ m=\"2745990\">AUDIENCE:</span> <span m=\"2746156\">Sum</span> <span m=\"2746322\"\
  >over</span> <span m=\"2746490\">u</span> <span m=\"2746990\">and big Y.</span></p><p><span\
  \ m=\"2748490\">PROFESSOR:</span> <span m=\"2748575\">Yeah.</span> <span m=\"2748660\"\
  >So</span> <span m=\"2748890\">sum</span> <span m=\"2749230\">of</span> <span m=\"\
  2749350\">codegree</span> <span m=\"2749980\">of</span> <span m=\"2750580\">two</span>\
  \ <span m=\"2751060\">vertices</span> <span m=\"2751690\">in</span> <span m=\"2751870\"\
  >Y,</span> <span m=\"2756064\">so</span> <span m=\"2756547\">Y, Y</span> <span m=\"\
  2757030\">prime,</span> <span m=\"2758200\">and Y</span> <span m=\"2760220\">codegree</span>\
  \ <span m=\"2761190\">of</span> <span m=\"2761495\">little</span> <span m=\"2761800\"\
  >y,</span> <span m=\"2762880\">little y</span> <span m=\"2763240\">prime.</span>\
  \ <span m=\"2769320\">And</span> <span m=\"2772780\">likewise,</span> <span m=\"\
  2773290\">the</span> <span m=\"2773410\">next</span> <span m=\"2773710\">expression</span>\
  \ <span m=\"2775240\">can</span> <span m=\"2775480\">be</span> <span m=\"2775810\"\
  >written</span> <span m=\"2777340\">as</span> <span m=\"2777580\">the</span> <span\
  \ m=\"2777640\">sum</span> <span m=\"2778000\">of</span> <span m=\"2778060\">the</span>\
  \ <span m=\"2778150\">degrees</span> <span m=\"2778600\">of</span> <span m=\"2778690\"\
  >vertices</span> <span m=\"2779230\">in</span> <span m=\"2779410\">Y.</span> <span\
  \ m=\"2783880\">And</span> <span m=\"2784040\">the</span> <span m=\"2784130\">third</span>\
  \ <span m=\"2784850\">term,</span> <span m=\"2785240\">I</span> <span m=\"2785390\"\
  >leave</span> <span m=\"2785690\">unchanged.</span></p><p><span m=\"2787670\">So</span>\
  \ <span m=\"2787770\">now</span> <span m=\"2787880\">we've</span> <span m=\"2788720\"\
  >gotten</span> <span m=\"2789440\">rid</span> <span m=\"2789770\">of</span> <span\
  \ m=\"2790100\">these</span> <span m=\"2791450\">funny</span> <span m=\"2791810\"\
  >expressions</span> <span m=\"2792610\">where it's</span> <span m=\"2792860\">just</span>\
  \ <span m=\"2793310\">degree</span> <span m=\"2793510\">from</span> <span m=\"2793820\"\
  >the</span> <span m=\"2793910\">vertex</span> <span m=\"2794390\">to</span> <span\
  \ m=\"2794540\">a</span> <span m=\"2794640\">set.</span> <span m=\"2795810\">And</span>\
  \ <span m=\"2795950\">we</span> <span m=\"2796100\">could</span> <span m=\"2796250\"\
  >do</span> <span m=\"2796370\">this</span> <span m=\"2796880\">because</span> <span\
  \ m=\"2797480\">of</span> <span m=\"2797750\">this</span> <span m=\"2797960\">relaxation</span>\
  \ <span m=\"2798680\">up</span> <span m=\"2798800\">here.</span> <span m=\"2800320\"\
  >So</span> <span m=\"2800520\">that</span> <span m=\"2801090\">was</span> <span\
  \ m=\"2801210\">the</span> <span m=\"2801270\">point.</span> <span m=\"2801480\"\
  >We</span> <span m=\"2801600\">had</span> <span m=\"2801720\">to</span> <span m=\"\
  2801810\">use</span> <span m=\"2801990\">this</span> <span m=\"2802170\">relaxation</span>\
  \ <span m=\"2803100\">so</span> <span m=\"2803250\">that</span> <span m=\"2803400\"\
  >we</span> <span m=\"2803550\">get</span> <span m=\"2803730\">these</span> <span\
  \ m=\"2803890\">codegree</span> <span m=\"2804410\">terms.</span></p><p><span m=\"\
  2806140\">But</span> <span m=\"2806320\">now,</span> <span m=\"2806560\">because</span>\
  \ <span m=\"2806950\">you</span> <span m=\"2807040\">have</span> <span m=\"2807130\"\
  >the</span> <span m=\"2807220\">codegree</span> <span m=\"2807670\">terms</span>\
  \ <span m=\"2808750\">and</span> <span m=\"2808900\">we</span> <span m=\"2809080\"\
  >assume</span> <span m=\"2809410\">the</span> <span m=\"2809500\">codegree</span>\
  \ <span m=\"2810160\">hypothesis,</span> <span m=\"2811600\">we</span> <span m=\"\
  2811780\">obtain</span> <span m=\"2812290\">that</span> <span m=\"2813070\">this</span>\
  \ <span m=\"2813220\">sum</span> <span m=\"2814330\">is</span> <span m=\"2814960\"\
  >roughly</span> <span m=\"2815470\">what</span> <span m=\"2815650\">you</span> <span\
  \ m=\"2815830\">expect</span> <span m=\"2816950\">as</span> <span m=\"2817180\"\
  >in a</span> <span m=\"2817240\">random</span> <span m=\"2817630\">case,</span>\
  \ <span m=\"2819280\">because</span> <span m=\"2820270\">all</span> <span m=\"2820480\"\
  >the</span> <span m=\"2820660\">individual</span> <span m=\"2821290\">deviations</span>\
  \ <span m=\"2822340\">do</span> <span m=\"2822460\">not</span> <span m=\"2822760\"\
  >add</span> <span m=\"2822940\">up</span> <span m=\"2823270\">to</span> <span m=\"\
  2823540\">more</span> <span m=\"2823870\">than</span> <span m=\"2825260\">little</span>\
  \ <span m=\"2825515\">o</span> <span m=\"2826120\">n</span> <span m=\"2826360\"\
  >cubed.</span> <span m=\"2831150\">That</span> <span m=\"2831780\">codegree</span>\
  \ <span m=\"2832230\">sum</span> <span m=\"2833380\">is</span> <span m=\"2833490\"\
  >what</span> <span m=\"2833670\">you</span> <span m=\"2833820\">expect.</span> <span\
  \ m=\"2835000\">And</span> <span m=\"2835290\">the</span> <span m=\"2835380\">next</span>\
  \ <span m=\"2835680\">term,</span> <span m=\"2837120\">the</span> <span m=\"2837450\"\
  >sum</span> <span m=\"2837870\">of</span> <span m=\"2837990\">degrees,</span> <span\
  \ m=\"2839040\">is</span> <span m=\"2839160\">also,</span> <span m=\"2839700\">by</span>\
  \ <span m=\"2839850\">what</span> <span m=\"2840000\">we</span> <span m=\"2840150\"\
  >did</span> <span m=\"2840380\">up</span> <span m=\"2840510\">there,</span> <span\
  \ m=\"2841080\">what</span> <span m=\"2841290\">you</span> <span m=\"2841620\">expect.</span></p><p><span\
  \ m=\"2849315\">And</span> <span m=\"2849800\">finally,</span> <span m=\"2850670\"\
  >the</span> <span m=\"2850750\">third</span> <span m=\"2851050\">term.</span> <span\
  \ m=\"2854330\">And</span> <span m=\"2854630\">as</span> <span m=\"2854810\">earlier,</span>\
  \ <span m=\"2855200\">if</span> <span m=\"2855350\">you</span> <span m=\"2855440\"\
  >did</span> <span m=\"2855650\">everything</span> <span m=\"2856010\">correctly,</span>\
  \ <span m=\"2856640\">everything</span> <span m=\"2857030\">should</span> <span\
  \ m=\"2857180\">cancel.</span> <span m=\"2858690\">And</span> <span m=\"2858810\"\
  >they</span> <span m=\"2858930\">do.</span> <span m=\"2860780\">And</span> <span\
  \ m=\"2860820\">so</span> <span m=\"2861030\">what</span> <span m=\"2861180\">you</span>\
  \ <span m=\"2861300\">get</span> <span m=\"2861510\">at</span> <span m=\"2861600\"\
  >the</span> <span m=\"2861720\">end</span> <span m=\"2861900\">is</span> <span m=\"\
  2862020\">little</span> <span m=\"2862500\">o</span> <span m=\"2862680\">of n</span>\
  \ <span m=\"2862950\">squared.</span></p><p><span m=\"2872020\">This</span> <span\
  \ m=\"2872180\">completes</span> <span m=\"2874100\">this</span> <span m=\"2874310\"\
  >fourth</span> <span m=\"2874520\">cycle.</span> <span m=\"2879720\">Any</span>\
  \ <span m=\"2879900\">questions</span> <span m=\"2880200\">so</span> <span m=\"\
  2880350\">far?</span> <span m=\"2886160\">So</span> <span m=\"2886280\">we're</span>\
  \ <span m=\"2886400\">missing</span> <span m=\"2886700\">one</span> <span m=\"2886820\"\
  >more</span> <span m=\"2886970\">condition,</span> <span m=\"2888610\">and</span>\
  \ <span m=\"2888720\">that's</span> <span m=\"2888870\">the</span> <span m=\"2888990\"\
  >eigenvalue</span> <span m=\"2889470\">condition.</span> <span m=\"2891980\">So</span>\
  \ <span m=\"2892670\">far,</span> <span m=\"2892880\">everything</span> <span m=\"\
  2893240\">had</span> <span m=\"2893390\">to</span> <span m=\"2893450\">do</span>\
  \ <span m=\"2893660\">with</span> <span m=\"2894130\">counting</span> <span m=\"\
  2895130\">various</span> <span m=\"2895580\">things.</span> <span m=\"2896120\"\
  >So</span> <span m=\"2896240\">what</span> <span m=\"2896400\">does</span> <span\
  \ m=\"2896570\">eigenvalue</span> <span m=\"2897080\">have</span> <span m=\"2897200\"\
  >to</span> <span m=\"2897290\">do</span> <span m=\"2897440\">with</span> <span m=\"\
  2897620\">anything?</span></p><p><span m=\"2902920\">So</span> <span m=\"2903200\"\
  >the</span> <span m=\"2903610\">eigenvalue</span> <span m=\"2904170\">condition</span>\
  \ <span m=\"2904700\">is</span> <span m=\"2905060\">actually</span> <span m=\"2905360\"\
  >a</span> <span m=\"2905420\">particularly</span> <span m=\"2906020\">important</span>\
  \ <span m=\"2906410\">one.</span> <span m=\"2906680\">And</span> <span m=\"2906770\"\
  >we'll</span> <span m=\"2906920\">see</span> <span m=\"2907100\">more</span> <span\
  \ m=\"2907340\">of</span> <span m=\"2907430\">this</span> <span m=\"2907700\">in</span>\
  \ <span m=\"2907820\">the</span> <span m=\"2907880\">next</span> <span m=\"2908180\"\
  >lecture.</span> <span m=\"2909560\">But</span> <span m=\"2909620\">let</span> <span\
  \ m=\"2909740\">me</span> <span m=\"2909860\">first</span> <span m=\"2910100\">show</span>\
  \ <span m=\"2910340\">you</span> <span m=\"2910610\">the</span> <span m=\"2910760\"\
  >equivalent</span> <span m=\"2911240\">implications.</span> <span m=\"2912300\"\
  >So</span> <span m=\"2912410\">what</span> <span m=\"2913020\">we'll</span> <span\
  \ m=\"2913250\">show</span> <span m=\"2913580\">is</span> <span m=\"2913790\">that</span>\
  \ <span m=\"2913950\">the</span> <span m=\"2914120\">eigenvalue</span> <span m=\"\
  2914600\">condition</span> <span m=\"2915410\">is</span> <span m=\"2915600\">equivalent</span>\
  \ <span m=\"2916130\">to</span> <span m=\"2916280\">the</span> <span m=\"2916370\"\
  >C4</span> <span m=\"2916880\">condition.</span> <span m=\"2917660\">So</span> <span\
  \ m=\"2917750\">that's</span> <span m=\"2918410\">the</span> <span m=\"2918500\"\
  >goal.</span> <span m=\"2918710\">So</span> <span m=\"2919030\">I'll</span> <span\
  \ m=\"2919160\">show</span> <span m=\"2920180\">equivalence</span> <span m=\"2920720\"\
  >between</span> <span m=\"2921230\">EIG</span> <span m=\"2922220\">and</span> <span\
  \ m=\"2922400\">C4.</span></p><p><span m=\"2926250\">So</span> <span m=\"2926450\"\
  >first, it</span> <span m=\"2926780\">implies</span> <span m=\"2927200\">a</span>\
  \ <span m=\"2927520\">C4</span> <span m=\"2927830\">condition,</span> <span m=\"\
  2929520\">because</span> <span m=\"2931140\">up</span> <span m=\"2931320\">to--</span>\
  \ <span m=\"2932050\">so</span> <span m=\"2932400\">instead</span> <span m=\"2932760\"\
  >of</span> <span m=\"2932850\">counting</span> <span m=\"2933180\">C4s,</span> <span\
  \ m=\"2933780\">which</span> <span m=\"2933990\">is</span> <span m=\"2934140\">a</span>\
  \ <span m=\"2934200\">little</span> <span m=\"2934410\">bit</span> <span m=\"2935070\"\
  >actually</span> <span m=\"2935280\">not--</span> <span m=\"2936340\">it's</span>\
  \ <span m=\"2937550\">a</span> <span m=\"2937980\">bit</span> <span m=\"2938100\"\
  >annoying</span> <span m=\"2938460\">to</span> <span m=\"2938580\">do</span> <span\
  \ m=\"2938730\">actual</span> <span m=\"2939000\">C4s.</span> <span m=\"2939780\"\
  >Just</span> <span m=\"2939990\">like</span> <span m=\"2940200\">earlier,</span>\
  \ <span m=\"2940530\">we</span> <span m=\"2940710\">want</span> <span m=\"2940920\"\
  >to</span> <span m=\"2941460\">consider</span> <span m=\"2943280\">homomorphic</span>\
  \ <span m=\"2943890\">copies,</span> <span m=\"2944430\">which</span> <span m=\"\
  2944670\">are</span> <span m=\"2945150\">also</span> <span m=\"2945660\">labeled</span>\
  \ <span m=\"2947020\">walks,</span> <span m=\"2947580\">so</span> <span m=\"2947790\"\
  >closed</span> <span m=\"2948210\">walks</span> <span m=\"2948570\">of</span> <span\
  \ m=\"2948690\">length</span> <span m=\"2948930\">4.</span> <span m=\"2949420\"\
  >So</span> <span m=\"2949650\">up</span> <span m=\"2949830\">to</span> <span m=\"\
  2951590\">a</span> <span m=\"2951690\">cubic</span> <span m=\"2952260\">error,</span>\
  \ <span m=\"2954980\">the</span> <span m=\"2955080\">number</span> <span m=\"2955360\"\
  >of</span> <span m=\"2955510\">labeled</span> <span m=\"2956000\">C4s</span> <span\
  \ m=\"2960040\">is</span> <span m=\"2962440\">given</span> <span m=\"2963100\">by</span>\
  \ <span m=\"2964390\">the</span> <span m=\"2964510\">number</span> <span m=\"2964900\"\
  >of</span> <span m=\"2965020\">closed</span> <span m=\"2965480\">walks</span> <span\
  \ m=\"2969390\">of</span> <span m=\"2969570\">length</span> <span m=\"2969840\"\
  >4,</span> <span m=\"2975080\">which</span> <span m=\"2976250\">is</span> <span\
  \ m=\"2976430\">equal</span> <span m=\"2976790\">to</span> <span m=\"2977960\">the</span>\
  \ <span m=\"2978080\">trace</span> <span m=\"2978830\">of</span> <span m=\"2979160\"\
  >the</span> <span m=\"2979370\">4th</span> <span m=\"2979730\">power</span> <span\
  \ m=\"2980360\">of</span> <span m=\"2980510\">the</span> <span m=\"2980690\">adjacency</span>\
  \ <span m=\"2981260\">matrix</span> <span m=\"2981830\">of</span> <span m=\"2981950\"\
  >this</span> <span m=\"2982120\">graph.</span></p><p><span m=\"2993280\">And the</span>\
  \ <span m=\"2993380\">next</span> <span m=\"2993540\">thing</span> <span m=\"2993750\"\
  >is</span> <span m=\"2993870\">super</span> <span m=\"2994620\">important.</span>\
  \ <span m=\"2995320\">So</span> <span m=\"2995480\">the</span> <span m=\"2995540\"\
  >next</span> <span m=\"2995820\">thing</span> <span m=\"2995940\">is</span> <span\
  \ m=\"2996240\">sometimes</span> <span m=\"2996600\">called</span> <span m=\"2996770\"\
  >a</span> <span m=\"2996810\">trace</span> <span m=\"2997260\">method.</span> <span\
  \ m=\"2998850\">One</span> <span m=\"2999240\">important</span> <span m=\"2999690\"\
  >way</span> <span m=\"3000020\">that</span> <span m=\"3000290\">the</span> <span\
  \ m=\"3000590\">eigenvalue,</span> <span m=\"3001250\">so</span> <span m=\"3001310\"\
  >the</span> <span m=\"3001400\">spectrum</span> <span m=\"3002150\">of</span> <span\
  \ m=\"3002710\">a</span> <span m=\"3002780\">graph</span> <span m=\"3003170\">or</span>\
  \ <span m=\"3003230\">matrix,</span> <span m=\"3004100\">relates</span> <span m=\"\
  3004520\">to</span> <span m=\"3004790\">other</span> <span m=\"3005000\">combinatorial</span>\
  \ <span m=\"3005630\">quantities</span> <span m=\"3006470\">is</span> <span m=\"\
  3006670\">via</span> <span m=\"3006960\">this</span> <span m=\"3007190\">trace.</span>\
  \ <span m=\"3007910\">So</span> <span m=\"3008600\">we</span> <span m=\"3008720\"\
  >know</span> <span m=\"3008930\">that</span> <span m=\"3009200\">the</span> <span\
  \ m=\"3009320\">trace</span> <span m=\"3010250\">of</span> <span m=\"3010400\">the</span>\
  \ <span m=\"3010490\">4th</span> <span m=\"3010790\">power</span> <span m=\"3011440\"\
  >is</span> <span m=\"3011570\">equal</span> <span m=\"3011930\">to</span> <span\
  \ m=\"3012050\">the</span> <span m=\"3012140\">fourth</span> <span m=\"3012530\"\
  >moment</span> <span m=\"3013040\">of</span> <span m=\"3013310\">the</span> <span\
  \ m=\"3013490\">eigenvalues.</span></p><p><span m=\"3020160\">So</span> <span m=\"\
  3020180\">if</span> <span m=\"3020270\">you</span> <span m=\"3020360\">haven't</span>\
  \ <span m=\"3020570\">seen</span> <span m=\"3020780\">a</span> <span m=\"3020810\"\
  >proof</span> <span m=\"3021050\">of</span> <span m=\"3021110\">this</span> <span\
  \ m=\"3021260\">before,</span> <span m=\"3021590\">I</span> <span m=\"3021680\"\
  >encourage</span> <span m=\"3022040\">you</span> <span m=\"3022100\">to</span> <span\
  \ m=\"3022190\">go</span> <span m=\"3022340\">home</span> <span m=\"3022490\">and</span>\
  \ <span m=\"3022580\">think</span> <span m=\"3022760\">about</span> <span m=\"3022970\"\
  >it.</span> <span m=\"3023240\">So</span> <span m=\"3023390\">this</span> <span\
  \ m=\"3024350\">is</span> <span m=\"3024440\">an</span> <span m=\"3024500\">important</span>\
  \ <span m=\"3024950\">identity,</span> <span m=\"3025370\">of</span> <span m=\"\
  3025460\">course.</span> <span m=\"3025730\">4</span> <span m=\"3026030\">can</span>\
  \ <span m=\"3026180\">be</span> <span m=\"3026270\">replaced</span> <span m=\"3026690\"\
  >by</span> <span m=\"3026810\">any</span> <span m=\"3027020\">number</span> <span\
  \ m=\"3027330\">up</span> <span m=\"3027440\">here.</span></p><p><span m=\"3029330\"\
  >And</span> <span m=\"3030650\">now</span> <span m=\"3031220\">you</span> <span\
  \ m=\"3032600\">have</span> <span m=\"3033080\">the</span> <span m=\"3033380\">eigenvalue</span>\
  \ <span m=\"3033890\">condition.</span> <span m=\"3035420\">So</span> <span m=\"\
  3036440\">I</span> <span m=\"3036530\">can</span> <span m=\"3036710\">estimate</span>\
  \ <span m=\"3037160\">the</span> <span m=\"3037280\">sum.</span> <span m=\"3038720\"\
  >There's</span> <span m=\"3038900\">a</span> <span m=\"3038960\">principle</span>\
  \ <span m=\"3039410\">term--</span> <span m=\"3039770\">namely,</span> <span m=\"\
  3040640\">lambda</span> <span m=\"3040940\">1.</span> <span m=\"3041660\">So</span>\
  \ <span m=\"3041780\">that's</span> <span m=\"3041960\">the</span> <span m=\"3042050\"\
  >big</span> <span m=\"3042260\">term.</span> <span m=\"3042860\">Everything</span>\
  \ <span m=\"3043250\">else</span> <span m=\"3043400\">is</span> <span m=\"3043460\"\
  >small.</span> <span m=\"3044210\">And</span> <span m=\"3044300\">the</span> <span\
  \ m=\"3044360\">smallness</span> <span m=\"3044870\">is</span> <span m=\"3044930\"\
  >supposed</span> <span m=\"3045200\">to</span> <span m=\"3045260\">capture</span>\
  \ <span m=\"3045650\">pseudorandomness.</span> <span m=\"3046950\">But</span> <span\
  \ m=\"3047000\">the</span> <span m=\"3047060\">big</span> <span m=\"3047240\">term,</span>\
  \ <span m=\"3047510\">you</span> <span m=\"3047600\">have</span> <span m=\"3047780\"\
  >to</span> <span m=\"3048620\">analyze</span> <span m=\"3048980\">separately.</span></p><p><span\
  \ m=\"3051150\">OK,</span> <span m=\"3051320\">so</span> <span m=\"3051440\">let</span>\
  \ <span m=\"3051560\">me</span> <span m=\"3053090\">write</span> <span m=\"3053300\"\
  >it</span> <span m=\"3053440\">out</span> <span m=\"3055041\">like</span> <span\
  \ m=\"3055518\">that.</span> <span m=\"3058380\">So</span> <span m=\"3058530\">the</span>\
  \ <span m=\"3058620\">big</span> <span m=\"3058860\">term,</span> <span m=\"3059220\"\
  >you</span> <span m=\"3059340\">know</span> <span m=\"3059580\">that</span> <span\
  \ m=\"3060120\">it</span> <span m=\"3060300\">is</span> <span m=\"3061400\">p</span>\
  \ <span m=\"3061910\">to</span> <span m=\"3062040\">the</span> <span m=\"3062130\"\
  >4</span> <span m=\"3062460\">n</span> <span m=\"3062740\">to the</span> <span m=\"\
  3062790\">4</span> <span m=\"3063030\">plus</span> <span m=\"3063360\">little</span>\
  \ <span m=\"3063800\">o</span> <span m=\"3064200\">of</span> <span m=\"3064545\"\
  >n to</span> <span m=\"3064890\">the</span> <span m=\"3065010\">4.</span> <span\
  \ m=\"3066570\">OK.</span> <span m=\"3067000\">So</span> <span m=\"3067160\">next</span>\
  \ <span m=\"3067450\">thing</span> <span m=\"3067570\">is</span> <span m=\"3067720\"\
  >what</span> <span m=\"3067900\">to</span> <span m=\"3067990\">do</span> <span m=\"\
  3068200\">with</span> <span m=\"3068500\">the</span> <span m=\"3069520\">little</span>\
  \ <span m=\"3069730\">terms.</span> <span m=\"3071220\">So</span> <span m=\"3071600\"\
  >we</span> <span m=\"3071720\">want</span> <span m=\"3071900\">to</span> <span m=\"\
  3071960\">show</span> <span m=\"3072170\">that</span> <span m=\"3072320\">the</span>\
  \ <span m=\"3072380\">contribution</span> <span m=\"3073220\">in</span> <span m=\"\
  3073310\">total</span> <span m=\"3073650\">is</span> <span m=\"3073790\">not</span>\
  \ <span m=\"3074000\">too</span> <span m=\"3074180\">big.</span></p><p><span m=\"\
  3075770\">So</span> <span m=\"3077620\">what</span> <span m=\"3077770\">can</span>\
  \ <span m=\"3077890\">we</span> <span m=\"3077980\">do?</span> <span m=\"3079010\"\
  >Well,</span> <span m=\"3079810\">let</span> <span m=\"3079930\">me</span> <span\
  \ m=\"3080800\">first</span> <span m=\"3081070\">try</span> <span m=\"3081250\"\
  >something.</span> <span m=\"3082250\">So</span> <span m=\"3082630\">first,</span>\
  \ <span m=\"3083410\">well,</span> <span m=\"3085410\">you</span> <span m=\"3085820\"\
  >see</span> <span m=\"3085980\">that</span> <span m=\"3086190\">each</span> <span\
  \ m=\"3086520\">one</span> <span m=\"3086820\">of</span> <span m=\"3086880\">these</span>\
  \ <span m=\"3087090\">guys</span> <span m=\"3087360\">is</span> <span m=\"3087480\"\
  >not</span> <span m=\"3087660\">too</span> <span m=\"3087840\">big.</span> <span\
  \ m=\"3088590\">So</span> <span m=\"3089250\">maybe</span> <span m=\"3089550\">let's</span>\
  \ <span m=\"3089850\">bound</span> <span m=\"3090390\">each</span> <span m=\"3090600\"\
  >one</span> <span m=\"3090780\">of</span> <span m=\"3090840\">them</span> <span\
  \ m=\"3091470\">by</span> <span m=\"3092280\">little</span> <span m=\"3092520\"\
  >o</span> <span m=\"3093540\">of</span> <span m=\"3094040\">n</span> <span m=\"\
  3095250\">raised</span> <span m=\"3095540\">to</span> <span m=\"3095670\">4.</span>\
  \ <span m=\"3096930\">But</span> <span m=\"3097050\">then</span> <span m=\"3097260\"\
  >there</span> <span m=\"3097430\">are</span> <span m=\"3097650\">n</span> <span\
  \ m=\"3097890\">of</span> <span m=\"3097980\">them,</span> <span m=\"3098460\">so</span>\
  \ <span m=\"3098760\">you</span> <span m=\"3098880\">have</span> <span m=\"3099000\"\
  >to</span> <span m=\"3099090\">multiply</span> <span m=\"3099540\">by</span> <span\
  \ m=\"3099660\">an</span> <span m=\"3099750\">extra</span> <span m=\"3100170\">n.</span></p><p><span\
  \ m=\"3102760\">And</span> <span m=\"3102930\">that's</span> <span m=\"3103110\"\
  >too</span> <span m=\"3103230\">much.</span> <span m=\"3104840\">That's</span> <span\
  \ m=\"3105020\">not</span> <span m=\"3105200\">good</span> <span m=\"3105350\">enough.</span>\
  \ <span m=\"3106380\">So you</span> <span m=\"3106480\">cannot</span> <span m=\"\
  3107030\">individually</span> <span m=\"3107780\">bound</span> <span m=\"3108170\"\
  >each</span> <span m=\"3108350\">one</span> <span m=\"3108530\">of</span> <span\
  \ m=\"3108620\">them.</span> <span m=\"3109430\">And</span> <span m=\"3109550\"\
  >this</span> <span m=\"3109700\">is</span> <span m=\"3109820\">a</span> <span m=\"\
  3110510\">novice</span> <span m=\"3110900\">mistake.</span> <span m=\"3112190\"\
  >This</span> <span m=\"3112370\">is</span> <span m=\"3112430\">something</span>\
  \ <span m=\"3112700\">that we</span> <span m=\"3112820\">actually</span> <span m=\"\
  3113210\">will</span> <span m=\"3113330\">see</span> <span m=\"3113930\">this</span>\
  \ <span m=\"3114170\">type</span> <span m=\"3114410\">of</span> <span m=\"3114500\"\
  >calculation</span> <span m=\"3115040\">later</span> <span m=\"3115270\">on</span>\
  \ <span m=\"3115390\">in</span> <span m=\"3115460\">the</span> <span m=\"3115550\"\
  >term</span> <span m=\"3115760\">when</span> <span m=\"3115880\">we</span> <span\
  \ m=\"3116000\">discuss</span> <span m=\"3116420\">Roth's</span> <span m=\"3116850\"\
  >theorem.</span> <span m=\"3117630\">But</span> <span m=\"3117650\">you're</span>\
  \ <span m=\"3117770\">not</span> <span m=\"3117980\">supposed</span> <span m=\"\
  3118340\">to</span> <span m=\"3118430\">bound</span> <span m=\"3118760\">these</span>\
  \ <span m=\"3118940\">terms</span> <span m=\"3119240\">individually.</span></p><p><span\
  \ m=\"3121010\">The</span> <span m=\"3121100\">better</span> <span m=\"3121370\"\
  >way</span> <span m=\"3121520\">to</span> <span m=\"3121610\">do</span> <span m=\"\
  3121730\">this</span> <span m=\"3121910\">or</span> <span m=\"3122000\">the</span>\
  \ <span m=\"3122090\">correct</span> <span m=\"3122450\">way</span> <span m=\"3122600\"\
  >to</span> <span m=\"3122690\">do</span> <span m=\"3122810\">this</span> <span m=\"\
  3123410\">is</span> <span m=\"3123560\">to</span> <span m=\"3123650\">pull</span>\
  \ <span m=\"3123950\">out</span> <span m=\"3124640\">just</span> <span m=\"3125600\"\
  >a</span> <span m=\"3125660\">couple--</span> <span m=\"3126520\">some,</span> <span\
  \ m=\"3126950\">but</span> <span m=\"3127070\">not</span> <span m=\"3127430\">all--</span>\
  \ <span m=\"3128180\">of</span> <span m=\"3128330\">these</span> <span m=\"3128540\"\
  >factors.</span> <span m=\"3129750\">So</span> <span m=\"3130610\">it</span> <span\
  \ m=\"3130730\">is</span> <span m=\"3130880\">upper</span> <span m=\"3131080\">bounded</span>\
  \ <span m=\"3131510\">by--</span> <span m=\"3131890\">you</span> <span m=\"3131960\"\
  >take</span> <span m=\"3132230\">max</span> <span m=\"3134930\">of--</span> <span\
  \ m=\"3136740\">in</span> <span m=\"3136890\">this</span> <span m=\"3137040\">case,</span>\
  \ <span m=\"3137710\">you</span> <span m=\"3137810\">can</span> <span m=\"3137850\"\
  >take</span> <span m=\"3138090\">out</span> <span m=\"3138720\">one</span> <span\
  \ m=\"3139110\">or</span> <span m=\"3139170\">two.</span> <span m=\"3139560\">But</span>\
  \ <span m=\"3139710\">you</span> <span m=\"3139830\">take</span> <span m=\"3140100\"\
  >out,</span> <span m=\"3140220\">let's</span> <span m=\"3140370\">say,</span> <span\
  \ m=\"3140550\">two</span> <span m=\"3141390\">factors.</span> <span m=\"3142260\"\
  >And</span> <span m=\"3142380\">then</span> <span m=\"3142500\">you</span> <span\
  \ m=\"3142620\">leave</span> <span m=\"3142980\">the</span> <span m=\"3143130\"\
  >remaining</span> <span m=\"3143640\">sum</span> <span m=\"3144060\">intact.</span>\
  \ <span m=\"3145610\">In</span> <span m=\"3145710\">fact,</span> <span m=\"3146030\"\
  >I</span> <span m=\"3146130\">can</span> <span m=\"3146870\">even</span> <span m=\"\
  3147770\">put</span> <span m=\"3148190\">lambda</span> <span m=\"3148460\">1</span>\
  \ <span m=\"3148700\">back</span> <span m=\"3148970\">into</span> <span m=\"3149180\"\
  >the</span> <span m=\"3149240\">remaining</span> <span m=\"3149770\">sum.</span></p><p><span\
  \ m=\"3150970\">So</span> <span m=\"3151160\">that</span> <span m=\"3151370\">is</span>\
  \ <span m=\"3151520\">true.</span> <span m=\"3152130\">So</span> <span m=\"3152390\"\
  >what</span> <span m=\"3152600\">I've</span> <span m=\"3152690\">written</span>\
  \ <span m=\"3152960\">down</span> <span m=\"3153210\">is</span> <span m=\"3153320\"\
  >just</span> <span m=\"3153650\">true</span> <span m=\"3153900\">as an</span> <span\
  \ m=\"3154150\">inequality.</span> <span m=\"3155020\">And</span> <span m=\"3155150\"\
  >now</span> <span m=\"3155600\">I</span> <span m=\"3155750\">apply</span> <span\
  \ m=\"3156680\">the</span> <span m=\"3157250\">hypothesis</span> <span m=\"3158240\"\
  >on</span> <span m=\"3158360\">the</span> <span m=\"3158450\">sizes</span> <span\
  \ m=\"3159020\">of</span> <span m=\"3159140\">the</span> <span m=\"3159260\">other</span>\
  \ <span m=\"3159480\">lambdas.</span> <span m=\"3167730\">So</span> <span m=\"3168230\"\
  >the</span> <span m=\"3168860\">one</span> <span m=\"3169160\">I</span> <span m=\"\
  3169310\">pulled</span> <span m=\"3169610\">out</span> <span m=\"3170210\">is</span>\
  \ <span m=\"3171040\">little</span> <span m=\"3171210\">o</span> <span m=\"3171560\"\
  >of</span> <span m=\"3172120\">n</span> <span m=\"3172280\">squared.</span></p><p><span\
  \ m=\"3173370\">And</span> <span m=\"3173480\">now</span> <span m=\"3174300\">what's</span>\
  \ <span m=\"3174800\">the</span> <span m=\"3174920\">second</span> <span m=\"3175340\"\
  >sum?</span> <span m=\"3177250\">That</span> <span m=\"3177520\">sum</span> <span\
  \ m=\"3177940\">is</span> <span m=\"3178330\">the</span> <span m=\"3178480\">trace</span>\
  \ <span m=\"3179290\">of</span> <span m=\"3179650\">a</span> <span m=\"3179800\"\
  >squared,</span> <span m=\"3183360\">which</span> <span m=\"3183500\">is</span>\
  \ <span m=\"3183680\">just</span> <span m=\"3184490\">twice</span> <span m=\"3184910\"\
  >the</span> <span m=\"3184970\">number</span> <span m=\"3185330\">of</span> <span\
  \ m=\"3185480\">edges</span> <span m=\"3185840\">of</span> <span m=\"3185930\">the</span>\
  \ <span m=\"3186020\">graph.</span> <span m=\"3188290\">So</span> <span m=\"3188500\"\
  >that's</span> <span m=\"3188680\">also</span> <span m=\"3189100\">at</span> <span\
  \ m=\"3189220\">most</span> <span m=\"3190350\">n</span> <span m=\"3190570\">squared.</span></p><p><span\
  \ m=\"3193330\">So</span> <span m=\"3193890\">combining</span> <span m=\"3194370\"\
  >everything,</span> <span m=\"3196760\">you</span> <span m=\"3196890\">have</span>\
  \ <span m=\"3200030\">the</span> <span m=\"3200210\">desired</span> <span m=\"3201080\"\
  >bound</span> <span m=\"3201800\">on</span> <span m=\"3201900\">the</span> <span\
  \ m=\"3201970\">C4</span> <span m=\"3202340\">count.</span> <span m=\"3205640\"\
  >Of</span> <span m=\"3205760\">course,</span> <span m=\"3206020\">this</span> <span\
  \ m=\"3206180\">gives</span> <span m=\"3206360\">you</span> <span m=\"3206430\"\
  >an</span> <span m=\"3206510\">upper</span> <span m=\"3206720\">bound.</span> <span\
  \ m=\"3207060\">But</span> <span m=\"3207080\">we</span> <span m=\"3207230\">also</span>\
  \ <span m=\"3207440\">did</span> <span m=\"3207590\">a</span> <span m=\"3207650\"\
  >calculation</span> <span m=\"3208190\">before</span> <span m=\"3208430\">the</span>\
  \ <span m=\"3208520\">break</span> <span m=\"3208760\">that</span> <span m=\"3208910\"\
  >shows</span> <span m=\"3209240\">you</span> <span m=\"3209710\">that</span> <span\
  \ m=\"3209840\">the</span> <span m=\"3209900\">C4</span> <span m=\"3210330\">bound</span>\
  \ <span m=\"3210860\">has</span> <span m=\"3211390\">a</span> <span m=\"3211460\"\
  >lower</span> <span m=\"3211700\">bound,</span> <span m=\"3211960\">as well.</span>\
  \ <span m=\"3212240\">So</span> <span m=\"3212360\">really,</span> <span m=\"3212570\"\
  >having</span> <span m=\"3212810\">the</span> <span m=\"3212870\">correct</span>\
  \ <span m=\"3213300\">eigenvalue--</span> <span m=\"3216240\">actually,</span> <span\
  \ m=\"3216620\">no,</span> <span m=\"3216870\">this</span> <span m=\"3217070\">already</span>\
  \ <span m=\"3217730\">shows</span> <span m=\"3218030\">you</span> <span m=\"3218180\"\
  >that</span> <span m=\"3218340\">the</span> <span m=\"3218420\">C4</span> <span\
  \ m=\"3218720\">bound</span> <span m=\"3219020\">is</span> <span m=\"3219200\">correct</span>\
  \ <span m=\"3219590\">in</span> <span m=\"3219680\">both</span> <span m=\"3219920\"\
  >directions,</span> <span m=\"3220580\">because</span> <span m=\"3220880\">this</span>\
  \ <span m=\"3222020\">is</span> <span m=\"3222080\">the</span> <span m=\"3222170\"\
  >main</span> <span m=\"3222350\">term.</span> <span m=\"3222770\">And</span> <span\
  \ m=\"3222860\">then</span> <span m=\"3223250\">everything</span> <span m=\"3223610\"\
  >else</span> <span m=\"3223790\">is</span> <span m=\"3223880\">small.</span></p><p><span\
  \ m=\"3229070\">OK.</span> <span m=\"3230330\">The</span> <span m=\"3230420\">final</span>\
  \ <span m=\"3230720\">implication</span> <span m=\"3231680\">is</span> <span m=\"\
  3232040\">C4</span> <span m=\"3232790\">implies</span> <span m=\"3233450\">eigenvalue.</span>\
  \ <span m=\"3241560\">For</span> <span m=\"3241720\">this</span> <span m=\"3241930\"\
  >one,</span> <span m=\"3243680\">I</span> <span m=\"3243770\">need</span> <span\
  \ m=\"3243950\">to</span> <span m=\"3244310\">explore</span> <span m=\"3245060\"\
  >the</span> <span m=\"3245450\">following</span> <span m=\"3246080\">important</span>\
  \ <span m=\"3246470\">property</span> <span m=\"3246950\">of</span> <span m=\"3247160\"\
  >the</span> <span m=\"3247250\">top</span> <span m=\"3247520\">eigenvalue.</span>\
  \ <span m=\"3248520\">So</span> <span m=\"3248720\">there's</span> <span m=\"3248870\"\
  >something</span> <span m=\"3249140\">that</span> <span m=\"3249410\">we</span>\
  \ <span m=\"3249590\">also</span> <span m=\"3250400\">saw</span> <span m=\"3250880\"\
  >last</span> <span m=\"3251210\">time,</span> <span m=\"3251840\">which</span> <span\
  \ m=\"3252140\">is</span> <span m=\"3252350\">the</span> <span m=\"3252440\">interpretation</span>\
  \ <span m=\"3253580\">of</span> <span m=\"3254310\">the</span> <span m=\"3254650\"\
  >top</span> <span m=\"3254990\">eigenvalue</span> <span m=\"3256010\">of</span>\
  \ <span m=\"3256100\">a</span> <span m=\"3256160\">matrix</span> <span m=\"3258390\"\
  >interpreted</span> <span m=\"3259360\">as--</span> <span m=\"3262880\">so</span>\
  \ <span m=\"3263020\">this</span> <span m=\"3263200\">is</span> <span m=\"3263260\"\
  >sometimes</span> <span m=\"3263680\">called</span> <span m=\"3263890\">the</span>\
  \ <span m=\"3264130\">Courant-Fischer</span> <span m=\"3265390\">criterion.</span>\
  \ <span m=\"3266130\">Or</span> <span m=\"3266470\">actually,</span> <span m=\"\
  3266890\">this</span> <span m=\"3267310\">is</span> <span m=\"3267430\">a</span>\
  \ <span m=\"3267550\">special</span> <span m=\"3267940\">case</span> <span m=\"\
  3268240\">of</span> <span m=\"3268360\">Courant-Fischer.</span></p><p><span m=\"\
  3270610\">This</span> <span m=\"3270790\">is</span> <span m=\"3271420\">a</span>\
  \ <span m=\"3271450\">basic</span> <span m=\"3271930\">linear</span> <span m=\"\
  3272200\">algebra</span> <span m=\"3272530\">fact.</span> <span m=\"3272930\">If</span>\
  \ <span m=\"3272940\">you</span> <span m=\"3273080\">are</span> <span m=\"3273160\"\
  >not</span> <span m=\"3273430\">familiar</span> <span m=\"3273820\">with</span>\
  \ <span m=\"3274000\">it,</span> <span m=\"3274150\">I</span> <span m=\"3274630\"\
  >recommend</span> <span m=\"3275020\">looking</span> <span m=\"3275350\">it</span>\
  \ <span m=\"3275440\">up.</span> <span m=\"3279110\">The</span> <span m=\"3279260\"\
  >top</span> <span m=\"3279560\">eigenvalue</span> <span m=\"3280040\">of</span>\
  \ <span m=\"3280130\">a</span> <span m=\"3280190\">matrix,</span> <span m=\"3281060\"\
  >of</span> <span m=\"3281420\">a</span> <span m=\"3281900\">real,</span> <span m=\"\
  3282200\">symmetric</span> <span m=\"3282890\">matrix,</span> <span m=\"3289250\"\
  >is</span> <span m=\"3289850\">characterized</span> <span m=\"3290600\">by</span>\
  \ <span m=\"3291570\">the</span> <span m=\"3291680\">maximum</span> <span m=\"3292250\"\
  >value</span> <span m=\"3292850\">of</span> <span m=\"3293450\">this</span> <span\
  \ m=\"3296200\">quadratic</span> <span m=\"3296680\">form.</span> <span m=\"3299570\"\
  >Let's</span> <span m=\"3299670\">say</span> <span m=\"3299910\">if</span> <span\
  \ m=\"3300720\">x</span> <span m=\"3300930\">is</span> <span m=\"3301050\">a</span>\
  \ <span m=\"3301080\">non-zero</span> <span m=\"3301740\">vector.</span></p><p><span\
  \ m=\"3305940\">So</span> <span m=\"3307380\">in</span> <span m=\"3307470\">particular,</span>\
  \ <span m=\"3307980\">if</span> <span m=\"3308160\">I</span> <span m=\"3308430\"\
  >set</span> <span m=\"3309360\">x</span> <span m=\"3309600\">to</span> <span m=\"\
  3309690\">be</span> <span m=\"3309840\">a</span> <span m=\"3309870\">specific</span>\
  \ <span m=\"3310410\">vector,</span> <span m=\"3311070\">I</span> <span m=\"3311160\"\
  >can</span> <span m=\"3311340\">lower</span> <span m=\"3311640\">bound</span> <span\
  \ m=\"3312000\">lambda</span> <span m=\"3312300\">1.</span> <span m=\"3314540\"\
  >So</span> <span m=\"3315650\">if</span> <span m=\"3317820\">we</span> <span m=\"\
  3317970\">set</span> <span m=\"3319680\">this</span> <span m=\"3320440\">boldface</span>\
  \ <span m=\"3320850\">1</span> <span m=\"3321210\">to</span> <span m=\"3321330\"\
  >be</span> <span m=\"3321540\">the</span> <span m=\"3321750\">all-one</span> <span\
  \ m=\"3322140\">vector</span> <span m=\"3325620\">in</span> <span m=\"3327750\"\
  >R</span> <span m=\"3328110\">raised</span> <span m=\"3328470\">to</span> <span\
  \ m=\"3329040\">the</span> <span m=\"3329100\">number</span> <span m=\"3329400\"\
  >of</span> <span m=\"3329460\">vertices</span> <span m=\"3329970\">of</span> <span\
  \ m=\"3330060\">G,</span> <span m=\"3331680\">then</span> <span m=\"3333490\">the</span>\
  \ <span m=\"3334050\">lambda</span> <span m=\"3334410\">1</span> <span m=\"3334770\"\
  >of</span> <span m=\"3334920\">the</span> <span m=\"3335010\">graph</span> <span\
  \ m=\"3335970\">is</span> <span m=\"3336300\">at</span> <span m=\"3336450\">least</span>\
  \ <span m=\"3343640\">this</span> <span m=\"3343850\">quantity</span> <span m=\"\
  3344240\">over</span> <span m=\"3344450\">here.</span></p><p><span m=\"3346980\"\
  >The</span> <span m=\"3347420\">numerator</span> <span m=\"3347870\">and</span>\
  \ <span m=\"3347990\">denominators</span> <span m=\"3348560\">are</span> <span m=\"\
  3348670\">all</span> <span m=\"3348860\">easy</span> <span m=\"3349160\">things</span>\
  \ <span m=\"3349400\">to</span> <span m=\"3349490\">evaluate.</span> <span m=\"\
  3350300\">The</span> <span m=\"3350390\">numerator</span> <span m=\"3350960\">is</span>\
  \ <span m=\"3351170\">just</span> <span m=\"3351410\">twice</span> <span m=\"3351740\"\
  >the</span> <span m=\"3351830\">number</span> <span m=\"3352130\">of</span> <span\
  \ m=\"3352250\">edges,</span> <span m=\"3353140\">because</span> <span m=\"3353420\"\
  >you</span> <span m=\"3353500\">are</span> <span m=\"3353990\">summing</span> <span\
  \ m=\"3354410\">up</span> <span m=\"3354530\">all</span> <span m=\"3354650\">the</span>\
  \ <span m=\"3354770\">entries</span> <span m=\"3355160\">of</span> <span m=\"3355220\"\
  >the</span> <span m=\"3355310\">matrix.</span> <span m=\"3356140\">And</span> <span\
  \ m=\"3356240\">the</span> <span m=\"3356930\">denominator</span> <span m=\"3357650\"\
  >is</span> <span m=\"3357980\">just</span> <span m=\"3358960\">n.</span> <span m=\"\
  3361180\">So</span> <span m=\"3362020\">the</span> <span m=\"3362230\">top</span>\
  \ <span m=\"3362640\">eigenvalue</span> <span m=\"3363430\">is</span> <span m=\"\
  3363700\">at</span> <span m=\"3363850\">least</span> <span m=\"3364990\">roughly</span>\
  \ <span m=\"3365520\">pn.</span></p><p><span m=\"3373650\">So</span> <span m=\"\
  3373800\">what</span> <span m=\"3373920\">about</span> <span m=\"3374100\">the</span>\
  \ <span m=\"3374190\">other</span> <span m=\"3374400\">eigenvalues?</span> <span\
  \ m=\"3378830\">Well,</span> <span m=\"3378950\">the</span> <span m=\"3379160\"\
  >other</span> <span m=\"3379400\">eigenvalues,</span> <span m=\"3381900\">I</span>\
  \ <span m=\"3382400\">can</span> <span m=\"3382610\">again</span> <span m=\"3383420\"\
  >refer</span> <span m=\"3384110\">back</span> <span m=\"3384410\">to</span> <span\
  \ m=\"3384770\">this</span> <span m=\"3386000\">moment</span> <span m=\"3386330\"\
  >formula</span> <span m=\"3387500\">relating</span> <span m=\"3387930\">the</span>\
  \ <span m=\"3387980\">trace</span> <span m=\"3388400\">and</span> <span m=\"3388550\"\
  >closed</span> <span m=\"3389040\">walks.</span> <span m=\"3391380\">It</span> <span\
  \ m=\"3391500\">is</span> <span m=\"3392050\">at</span> <span m=\"3392180\">most</span>\
  \ <span m=\"3395450\">the</span> <span m=\"3395810\">trace</span> <span m=\"3396110\"\
  >of</span> <span m=\"3396200\">the</span> <span m=\"3396260\">4th</span> <span m=\"\
  3396500\">power</span> <span m=\"3397190\">minus</span> <span m=\"3399860\">the</span>\
  \ <span m=\"3399950\">top</span> <span m=\"3400430\">eigenvalue</span> <span m=\"\
  3400960\">raised</span> <span m=\"3401210\">to</span> <span m=\"3401330\">the</span>\
  \ <span m=\"3401420\">4th</span> <span m=\"3401630\">power.</span> <span m=\"3402710\"\
  >It's</span> <span m=\"3402860\">the</span> <span m=\"3403190\">sum</span> <span\
  \ m=\"3403490\">of</span> <span m=\"3403580\">the</span> <span m=\"3403700\">other</span>\
  \ <span m=\"3403910\">eigenvalue</span> <span m=\"3404370\">raised to</span> <span\
  \ m=\"3404640\">the</span> <span m=\"3404720\">4th</span> <span m=\"3405500\">power.</span></p><p><span\
  \ m=\"3405860\">And</span> <span m=\"3405980\">4</span> <span m=\"3406370\">here,</span>\
  \ <span m=\"3406640\">we're</span> <span m=\"3406760\">using</span> <span m=\"3406910\"\
  >the</span> <span m=\"3406970\">4.</span> <span m=\"3407310\">It's an</span> <span\
  \ m=\"3407390\">even</span> <span m=\"3407630\">number,</span> <span m=\"3408300\"\
  >right?</span> <span m=\"3409220\">So</span> <span m=\"3410600\">you</span> <span\
  \ m=\"3410690\">have</span> <span m=\"3410810\">this</span> <span m=\"3411950\"\
  >over</span> <span m=\"3412130\">here.</span> <span m=\"3412710\">So</span> <span\
  \ m=\"3415030\">having</span> <span m=\"3415360\">a</span> <span m=\"3415420\">C4</span>\
  \ <span m=\"3416140\">hypothesis</span> <span m=\"3419620\">and</span> <span m=\"\
  3419950\">also</span> <span m=\"3420910\">knowing</span> <span m=\"3421450\">what</span>\
  \ <span m=\"3422980\">lambda</span> <span m=\"3423280\">1</span> <span m=\"3423550\"\
  >is</span> <span m=\"3428620\">allows</span> <span m=\"3429040\">you</span> <span\
  \ m=\"3429160\">to</span> <span m=\"3429340\">control</span> <span m=\"3430120\"\
  >the</span> <span m=\"3430270\">other</span> <span m=\"3430750\">lambdas.</span></p><p><span\
  \ m=\"3442530\">See,</span> <span m=\"3442790\">lambda</span> <span m=\"3443060\"\
  >1</span> <span m=\"3443270\">cannot</span> <span m=\"3443750\">be</span> <span\
  \ m=\"3445850\">much</span> <span m=\"3446090\">greater</span> <span m=\"3446390\"\
  >than</span> <span m=\"3446580\">pn.</span> <span m=\"3447500\">Also</span> <span\
  \ m=\"3447890\">comes</span> <span m=\"3448190\">out</span> <span m=\"3448340\"\
  >of</span> <span m=\"3448400\">the</span> <span m=\"3448490\">same</span> <span\
  \ m=\"3448730\">calculation.</span> <span m=\"3449270\">Yep.</span></p><p><span\
  \ m=\"3450246\">AUDIENCE:</span> <span m=\"3450490\">So</span> <span m=\"3450734\"\
  >[INAUDIBLE]</span> <span m=\"3451710\">number 1</span> <span m=\"3452686\">equal</span>\
  \ <span m=\"3453174\">to</span> <span m=\"3454638\">[INAUDIBLE]?</span></p><p><span\
  \ m=\"3456102\">PROFESSOR:</span> <span m=\"3456346\">Yeah,</span> <span m=\"3456590\"\
  >thank</span> <span m=\"3456800\">you.</span> <span m=\"3459255\">Yeah,</span> <span\
  \ m=\"3459730\">so</span> <span m=\"3459880\">there's</span> <span m=\"3460030\"\
  >a</span> <span m=\"3460090\">correction.</span> <span m=\"3460640\">So</span> <span\
  \ m=\"3460690\">lambda</span> <span m=\"3461030\">1</span> <span m=\"3461330\">is--</span>\
  \ <span m=\"3463360\">so</span> <span m=\"3463480\">in</span> <span m=\"3463600\"\
  >other</span> <span m=\"3463750\">words,</span> <span m=\"3464060\">the</span> <span\
  \ m=\"3464110\">little</span> <span m=\"3464380\">o</span> <span m=\"3464740\">is\
  \ always</span> <span m=\"3465160\">respect</span> <span m=\"3465590\">to</span>\
  \ <span m=\"3466370\">the</span> <span m=\"3466540\">constant</span> <span m=\"\
  3466990\">density.</span> <span m=\"3473302\">OK, yeah.</span> <span m=\"3473788\"\
  >Question.</span></p><p><span m=\"3474274\">AUDIENCE:</span> <span m=\"3474436\"\
  >You</span> <span m=\"3474598\">said</span> <span m=\"3474760\">in the</span> <span\
  \ m=\"3475246\">eigenvalue</span> <span m=\"3476218\">implies</span> <span m=\"\
  3477190\">C4,</span> <span m=\"3478162\">you somewhere</span> <span m=\"3478648\"\
  >also used</span> <span m=\"3479134\">the</span> <span m=\"3479620\">lower bound</span>\
  \ <span m=\"3480106\">to be</span> <span m=\"3480592\">proved</span> <span m=\"\
  3481515\">[INAUDIBLE].</span></p><p><span m=\"3482385\">PROFESSOR:</span> <span\
  \ m=\"3482602\">OK.</span> <span m=\"3482820\">So</span> <span m=\"3483450\">the</span>\
  \ <span m=\"3483520\">question</span> <span m=\"3483780\">is</span> <span m=\"3484100\"\
  >in</span> <span m=\"3484690\">eigenvalue</span> <span m=\"3485170\">implies</span>\
  \ <span m=\"3485520\">C4,</span> <span m=\"3486800\">it</span> <span m=\"3487240\"\
  >says</span> <span m=\"3487390\">something</span> <span m=\"3487660\">about</span>\
  \ <span m=\"3487780\">the</span> <span m=\"3487870\">lower</span> <span m=\"3488110\"\
  >bound.</span> <span m=\"3488480\">So</span> <span m=\"3488650\">I'm</span> <span\
  \ m=\"3488980\">not</span> <span m=\"3489190\">saying</span> <span m=\"3489460\"\
  >that.</span> <span m=\"3489600\">So</span> <span m=\"3489790\">as</span> <span\
  \ m=\"3490720\">written</span> <span m=\"3491260\">over</span> <span m=\"3491470\"\
  >here,</span> <span m=\"3492550\">this</span> <span m=\"3492700\">is</span> <span\
  \ m=\"3492820\">what</span> <span m=\"3492970\">we</span> <span m=\"3493120\">have</span>\
  \ <span m=\"3493240\">proved.</span></p><p><span m=\"3495760\">But</span> <span\
  \ m=\"3496150\">when</span> <span m=\"3496450\">you</span> <span m=\"3496540\">think</span>\
  \ <span m=\"3496780\">about</span> <span m=\"3496970\">the</span> <span m=\"3497050\"\
  >pseudorandomness</span> <span m=\"3497830\">condition</span> <span m=\"3498220\"\
  >for</span> <span m=\"3498400\">C4,</span> <span m=\"3499300\">it</span> <span m=\"\
  3499650\">shouldn't</span> <span m=\"3500170\">be</span> <span m=\"3500380\">just</span>\
  \ <span m=\"3500620\">that</span> <span m=\"3500830\">the</span> <span m=\"3500920\"\
  >number</span> <span m=\"3501220\">of</span> <span m=\"3501280\">C4</span> <span\
  \ m=\"3501730\">count</span> <span m=\"3502150\">is</span> <span m=\"3502840\">at</span>\
  \ <span m=\"3503000\">most</span> <span m=\"3503330\">something.</span> <span m=\"\
  3503740\">It should</span> <span m=\"3503860\">be</span> <span m=\"3504150\">that\
  \ it</span> <span m=\"3504340\">equals</span> <span m=\"3504610\">to</span> <span\
  \ m=\"3505610\">that,</span> <span m=\"3506860\">which</span> <span m=\"3507610\"\
  >would</span> <span m=\"3507910\">be</span> <span m=\"3508090\">implied</span> <span\
  \ m=\"3508510\">by</span> <span m=\"3508630\">the</span> <span m=\"3508720\">C4</span>\
  \ <span m=\"3509080\">condition</span> <span m=\"3509470\">itself,</span> <span\
  \ m=\"3509770\">because</span> <span m=\"3510070\">we</span> <span m=\"3510190\"\
  >know,</span> <span m=\"3511060\">always,</span> <span m=\"3511510\">it</span> <span\
  \ m=\"3511630\">is</span> <span m=\"3511750\">the</span> <span m=\"3511840\">case</span>\
  \ <span m=\"3512170\">that</span> <span m=\"3512350\">a</span> <span m=\"3512410\"\
  >C4</span> <span m=\"3512780\">count is</span> <span m=\"3513180\">at</span> <span\
  \ m=\"3513290\">least</span> <span m=\"3514930\">what</span> <span m=\"3515110\"\
  >it</span> <span m=\"3515200\">is</span> <span m=\"3515350\">compared</span> <span\
  \ m=\"3515650\">to</span> <span m=\"3515710\">the</span> <span m=\"3515800\">random</span>\
  \ <span m=\"3516100\">case.</span></p><p><span m=\"3523380\">So</span> <span m=\"\
  3523940\">just</span> <span m=\"3524110\">one</span> <span m=\"3524230\">more</span>\
  \ <span m=\"3524380\">thing</span> <span m=\"3524590\">I</span> <span m=\"3524650\"\
  >said</span> <span m=\"3525160\">was</span> <span m=\"3525340\">that</span> <span\
  \ m=\"3526030\">lambda</span> <span m=\"3526390\">1,</span> <span m=\"3527530\"\
  >you</span> <span m=\"3527680\">also</span> <span m=\"3527950\">know</span> <span\
  \ m=\"3528410\">that</span> <span m=\"3528640\">it</span> <span m=\"3528760\">is</span>\
  \ <span m=\"3528950\">at</span> <span m=\"3529090\">most</span> <span m=\"3530020\"\
  >pn</span> <span m=\"3530920\">plus</span> <span m=\"3531420\">little</span> <span\
  \ m=\"3531890\">n,</span> <span m=\"3535960\">because--</span> <span m=\"3542286\"\
  >OK.</span> <span m=\"3544270\">Yeah.</span> <span m=\"3550240\">So</span> <span\
  \ m=\"3550510\">this</span> <span m=\"3550720\">finishes</span> <span m=\"3551170\"\
  >the</span> <span m=\"3551260\">proof</span> <span m=\"3551650\">of</span> <span\
  \ m=\"3551860\">the</span> <span m=\"3551950\">Chung-Graham-Wilson</span> <span\
  \ m=\"3552820\">theorem</span> <span m=\"3553140\">on</span> <span m=\"3553660\"\
  >quasi-random</span> <span m=\"3554290\">graphs.</span> <span m=\"3554740\">We</span>\
  \ <span m=\"3554900\">stated</span> <span m=\"3555280\">all</span> <span m=\"3555430\"\
  >of</span> <span m=\"3555490\">these</span> <span m=\"3556060\">hypotheses,</span>\
  \ <span m=\"3556960\">and</span> <span m=\"3557140\">they</span> <span m=\"3557280\"\
  >are</span> <span m=\"3557370\">all</span> <span m=\"3557530\">equivalent</span>\
  \ <span m=\"3558070\">to</span> <span m=\"3558190\">each</span> <span m=\"3558400\"\
  >other.</span></p><p><span m=\"3558940\">And</span> <span m=\"3559390\">I</span>\
  \ <span m=\"3559480\">want</span> <span m=\"3559600\">to</span> <span m=\"3559690\"\
  >emphasize,</span> <span m=\"3560110\">again,</span> <span m=\"3560320\">the</span>\
  \ <span m=\"3560410\">most</span> <span m=\"3560650\">surprising</span> <span m=\"\
  3561280\">one</span> <span m=\"3561850\">is</span> <span m=\"3562030\">that</span>\
  \ <span m=\"3562300\">C4</span> <span m=\"3562960\">implies</span> <span m=\"3563440\"\
  >everything</span> <span m=\"3563830\">else,</span> <span m=\"3564570\">that</span>\
  \ <span m=\"3564780\">a</span> <span m=\"3564940\">fairly</span> <span m=\"3567220\"\
  >seemingly</span> <span m=\"3567610\">weak</span> <span m=\"3567820\">condition,</span>\
  \ <span m=\"3568330\">this</span> <span m=\"3568750\">just</span> <span m=\"3568960\"\
  >having</span> <span m=\"3569290\">the</span> <span m=\"3569380\">correct</span>\
  \ <span m=\"3569740\">number</span> <span m=\"3570040\">of</span> <span m=\"3570130\"\
  >copies</span> <span m=\"3570580\">of</span> <span m=\"3570700\">labeled</span>\
  \ <span m=\"3571030\">C4s,</span> <span m=\"3572110\">is</span> <span m=\"3572560\"\
  >enough</span> <span m=\"3572920\">to</span> <span m=\"3573010\">guarantee</span>\
  \ <span m=\"3573670\">all</span> <span m=\"3573810\">of</span> <span m=\"3573880\"\
  >these</span> <span m=\"3574120\">other</span> <span m=\"3574660\">much</span> <span\
  \ m=\"3574900\">more</span> <span m=\"3575080\">complicated</span> <span m=\"3575680\"\
  >looking</span> <span m=\"3576340\">conditions.</span> <span m=\"3577060\">And</span>\
  \ <span m=\"3577240\">in</span> <span m=\"3577330\">particular,</span> <span m=\"\
  3577840\">just</span> <span m=\"3578080\">having</span> <span m=\"3578380\">the</span>\
  \ <span m=\"3578440\">C4</span> <span m=\"3578920\">count</span> <span m=\"3579640\"\
  >correct</span> <span m=\"3580510\">implies</span> <span m=\"3581440\">that</span>\
  \ <span m=\"3581740\">the</span> <span m=\"3581950\">counts</span> <span m=\"3582310\"\
  >of</span> <span m=\"3582490\">every</span> <span m=\"3582790\">other</span> <span\
  \ m=\"3583030\">graph</span> <span m=\"3583360\">H</span> <span m=\"3583840\">is</span>\
  \ <span m=\"3584170\">correct.</span></p><p><span m=\"3586810\">Now,</span> <span\
  \ m=\"3587610\">one</span> <span m=\"3587850\">thing</span> <span m=\"3588030\"\
  >I</span> <span m=\"3588120\">want</span> <span m=\"3588300\">to</span> <span m=\"\
  3588360\">stress</span> <span m=\"3589620\">is</span> <span m=\"3589830\">that</span>\
  \ <span m=\"3590160\">the</span> <span m=\"3590460\">Chung-Graham-Wilson</span>\
  \ <span m=\"3591540\">theorem</span> <span m=\"3592010\">is</span> <span m=\"3592230\"\
  >really</span> <span m=\"3592560\">about</span> <span m=\"3593640\">dense</span>\
  \ <span m=\"3594120\">graphs.</span> <span m=\"3603230\">And</span> <span m=\"3603370\"\
  >by</span> <span m=\"3603550\">dense,</span> <span m=\"3603970\">here,</span> <span\
  \ m=\"3604210\">I</span> <span m=\"3604330\">mean</span> <span m=\"3604600\">p</span>\
  \ <span m=\"3605020\">constant.</span> <span m=\"3608940\">Of</span> <span m=\"\
  3609140\">course,</span> <span m=\"3609300\">the</span> <span m=\"3609390\">theorem</span>\
  \ <span m=\"3609720\">as</span> <span m=\"3609790\">stated</span> <span m=\"3610230\"\
  >is</span> <span m=\"3610380\">true</span> <span m=\"3611010\">if</span> <span m=\"\
  3611190\">you</span> <span m=\"3611370\">let</span> <span m=\"3611610\">p</span>\
  \ <span m=\"3612780\">equal</span> <span m=\"3613180\">to</span> <span m=\"3613280\"\
  >0.</span> <span m=\"3613650\">So</span> <span m=\"3614320\">there,</span> <span\
  \ m=\"3614580\">I</span> <span m=\"3614690\">said</span> <span m=\"3614820\">p</span>\
  \ <span m=\"3615630\">strictly</span> <span m=\"3616050\">between</span> <span m=\"\
  3616380\">0</span> <span m=\"3616620\">and</span> <span m=\"3616740\">1.</span>\
  \ <span m=\"3617140\">But</span> <span m=\"3617730\">it</span> <span m=\"3617850\"\
  >is</span> <span m=\"3618000\">also</span> <span m=\"3618270\">OK</span> <span m=\"\
  3618600\">if</span> <span m=\"3618720\">you</span> <span m=\"3618840\">let</span>\
  \ <span m=\"3618960\">p</span> <span m=\"3621530\">be</span> <span m=\"3621960\"\
  >equal</span> <span m=\"3622260\">to</span> <span m=\"3622350\">0.</span> <span\
  \ m=\"3625470\">You</span> <span m=\"3625560\">don't</span> <span m=\"3625710\"\
  >get</span> <span m=\"3626130\">such</span> <span m=\"3626460\">interesting</span>\
  \ <span m=\"3626970\">theorems,</span> <span m=\"3628180\">but</span> <span m=\"\
  3628650\">it</span> <span m=\"3628780\">is</span> <span m=\"3628890\">still</span>\
  \ <span m=\"3629130\">true.</span></p><p><span m=\"3632130\">But for</span> <span\
  \ m=\"3632400\">sparse</span> <span m=\"3632820\">graphs,</span> <span m=\"3633140\"\
  >what</span> <span m=\"3633310\">you</span> <span m=\"3633480\">really</span> <span\
  \ m=\"3633720\">want</span> <span m=\"3633900\">to</span> <span m=\"3633960\">care</span>\
  \ <span m=\"3634200\">about</span> <span m=\"3634440\">is</span> <span m=\"3635280\"\
  >approximations</span> <span m=\"3636150\">of</span> <span m=\"3636210\">the</span>\
  \ <span m=\"3636300\">correct</span> <span m=\"3636810\">order</span> <span m=\"\
  3637110\">of</span> <span m=\"3637200\">magnitude.</span> <span m=\"3640230\">So</span>\
  \ <span m=\"3640590\">what</span> <span m=\"3640860\">I</span> <span m=\"3640980\"\
  >mean</span> <span m=\"3641520\">is</span> <span m=\"3641730\">that</span> <span\
  \ m=\"3643280\">you</span> <span m=\"3643400\">can</span> <span m=\"3643580\">write</span>\
  \ <span m=\"3643820\">down</span> <span m=\"3644660\">some</span> <span m=\"3645410\"\
  >sparse</span> <span m=\"3646070\">analogs</span> <span m=\"3650850\">for</span>\
  \ <span m=\"3651180\">p</span> <span m=\"3652560\">going</span> <span m=\"3652850\"\
  >to</span> <span m=\"3653000\">0,</span> <span m=\"3653910\">so</span> <span m=\"\
  3654180\">p</span> <span m=\"3654930\">as</span> <span m=\"3655050\">a</span> <span\
  \ m=\"3655110\">function</span> <span m=\"3655500\">of</span> <span m=\"3655620\"\
  >n</span> <span m=\"3656220\">going</span> <span m=\"3656430\">to</span> <span m=\"\
  3656550\">0</span> <span m=\"3657830\">as</span> <span m=\"3658020\">n</span> <span\
  \ m=\"3658120\">goes</span> <span m=\"3658410\">to</span> <span m=\"3658470\">infinity.</span></p><p><span\
  \ m=\"3663230\">So</span> <span m=\"3663280\">let</span> <span m=\"3663400\">me</span>\
  \ <span m=\"3663490\">just</span> <span m=\"3663640\">write</span> <span m=\"3663820\"\
  >down</span> <span m=\"3663970\">a</span> <span m=\"3664030\">couple</span> <span\
  \ m=\"3664300\">of</span> <span m=\"3664390\">examples,</span> <span m=\"3664870\"\
  >but</span> <span m=\"3665050\">I</span> <span m=\"3665110\">won't</span> <span\
  \ m=\"3665320\">do</span> <span m=\"3665470\">all</span> <span m=\"3665620\">of</span>\
  \ <span m=\"3665680\">them.</span> <span m=\"3665900\">You</span> <span m=\"3665980\"\
  >can</span> <span m=\"3666130\">imagine</span> <span m=\"3666520\">what</span> <span\
  \ m=\"3666650\">they</span> <span m=\"3666730\">should</span> <span m=\"3666910\"\
  >look</span> <span m=\"3667090\">like.</span> <span m=\"3667760\">So</span> <span\
  \ m=\"3668200\">DISC</span> <span m=\"3669700\">should</span> <span m=\"3670000\"\
  >say</span> <span m=\"3672220\">this</span> <span m=\"3672550\">quantity</span>\
  \ <span m=\"3673060\">over</span> <span m=\"3673300\">here.</span> <span m=\"3673935\"\
  >And</span> <span m=\"3674210\">the</span> <span m=\"3675250\">discrepancy</span>\
  \ <span m=\"3675910\">condition</span> <span m=\"3676720\">is</span> <span m=\"\
  3679170\">little</span> <span m=\"3679460\">o</span> <span m=\"3680200\">of</span>\
  \ <span m=\"3681670\">pn</span> <span m=\"3682870\">squared,</span> <span m=\"3683770\"\
  >because</span> <span m=\"3684250\">pn</span> <span m=\"3684730\">squared</span>\
  \ <span m=\"3685270\">is</span> <span m=\"3685570\">the</span> <span m=\"3685800\"\
  >edge</span> <span m=\"3686080\">density</span> <span m=\"3686560\">overall.</span>\
  \ <span m=\"3687080\">So</span> <span m=\"3687160\">that's</span> <span m=\"3687520\"\
  >the</span> <span m=\"3687610\">quantity</span> <span m=\"3688030\">you</span> <span\
  \ m=\"3688120\">should</span> <span m=\"3688270\">compare</span> <span m=\"3688660\"\
  >against</span> <span m=\"3689290\">and</span> <span m=\"3689380\">not</span> <span\
  \ m=\"3689680\">n</span> <span m=\"3689860\">squared.</span> <span m=\"3690820\"\
  >If</span> <span m=\"3690940\">you're</span> <span m=\"3691060\">comparing</span>\
  \ <span m=\"3691510\">n</span> <span m=\"3691720\">squared,</span> <span m=\"3693100\"\
  >you're</span> <span m=\"3693250\">cheating,</span> <span m=\"3694540\">because</span>\
  \ <span m=\"3694990\">n</span> <span m=\"3695230\">squared</span> <span m=\"3695560\"\
  >is</span> <span m=\"3695680\">much</span> <span m=\"3695920\">bigger</span> <span\
  \ m=\"3696220\">than</span> <span m=\"3696430\">the</span> <span m=\"3696550\">actual</span>\
  \ <span m=\"3696940\">edge</span> <span m=\"3697150\">density.</span></p><p><span\
  \ m=\"3699160\">Likewise,</span> <span m=\"3700710\">the</span> <span m=\"3700800\"\
  >number</span> <span m=\"3701160\">of</span> <span m=\"3703060\">labeled</span>\
  \ <span m=\"3703450\">copies</span> <span m=\"3703900\">of</span> <span m=\"3704020\"\
  >H</span> <span m=\"3708420\">is--</span> <span m=\"3711550\">I</span> <span m=\"\
  3711670\">want</span> <span m=\"3711940\">to</span> <span m=\"3712030\">put</span>\
  \ <span m=\"3712520\">the</span> <span m=\"3712630\">little</span> <span m=\"3712910\"\
  >o</span> <span m=\"3714010\">1</span> <span m=\"3714250\">plus</span> <span m=\"\
  3714520\">little</span> <span m=\"3714880\">in</span> <span m=\"3715030\">front,</span>\
  \ <span m=\"3724970\">so</span> <span m=\"3725130\">instead</span> <span m=\"3725520\"\
  >of</span> <span m=\"3726610\">plus</span> <span m=\"3727330\">little</span> <span\
  \ m=\"3727510\">o</span> <span m=\"3728590\">of</span> <span m=\"3729310\">n</span>\
  \ <span m=\"3729550\">to</span> <span m=\"3729670\">the</span> <span m=\"3729790\"\
  >H</span> <span m=\"3730810\">at</span> <span m=\"3730900\">the</span> <span m=\"\
  3731050\">end.</span> <span m=\"3734230\">So</span> <span m=\"3734380\">you</span>\
  \ <span m=\"3734470\">understand</span> <span m=\"3734830\">the</span> <span m=\"\
  3734890\">difference.</span> <span m=\"3735660\">So</span> <span m=\"3735730\">for</span>\
  \ <span m=\"3735910\">sparse,</span> <span m=\"3737200\">this</span> <span m=\"\
  3737500\">is</span> <span m=\"3737620\">the</span> <span m=\"3737740\">correct</span>\
  \ <span m=\"3738550\">normalization</span> <span m=\"3739330\">that you</span> <span\
  \ m=\"3739450\">should</span> <span m=\"3739660\">have,</span> <span m=\"3740130\"\
  >when</span> <span m=\"3740310\">p is</span> <span m=\"3740640\">allowed</span>\
  \ <span m=\"3740830\">to go</span> <span m=\"3741160\">to</span> <span m=\"3741250\"\
  >0</span> <span m=\"3741610\">as</span> <span m=\"3741910\">a</span> <span m=\"\
  3741970\">function</span> <span m=\"3742330\">of</span> <span m=\"3742450\">n.</span></p><p><span\
  \ m=\"3743770\">And</span> <span m=\"3745170\">you</span> <span m=\"3745290\">can</span>\
  \ <span m=\"3745440\">write</span> <span m=\"3745680\">down</span> <span m=\"3746010\"\
  >all</span> <span m=\"3746170\">of</span> <span m=\"3746250\">these</span> <span\
  \ m=\"3746430\">conditions,</span> <span m=\"3746910\">right?</span> <span m=\"\
  3747180\">I'm</span> <span m=\"3747330\">not</span> <span m=\"3747510\">saying</span>\
  \ <span m=\"3747750\">there's</span> <span m=\"3747930\">a</span> <span m=\"3747990\"\
  >theorem.</span> <span m=\"3748710\">You</span> <span m=\"3748800\">can</span> <span\
  \ m=\"3748950\">write</span> <span m=\"3749180\">out</span> <span m=\"3749310\"\
  >all</span> <span m=\"3749520\">these</span> <span m=\"3749700\">conditions.</span>\
  \ <span m=\"3750860\">And</span> <span m=\"3751030\">you can</span> <span m=\"3751200\"\
  >ask,</span> <span m=\"3751620\">is</span> <span m=\"3751830\">there</span> <span\
  \ m=\"3751980\">also</span> <span m=\"3752310\">some</span> <span m=\"3752910\"\
  >notion</span> <span m=\"3753420\">of</span> <span m=\"3754290\">equivalence?</span>\
  \ <span m=\"3755220\">So</span> <span m=\"3755670\">are</span> <span m=\"3755820\"\
  >these</span> <span m=\"3756240\">corresponding</span> <span m=\"3756810\">conditions</span>\
  \ <span m=\"3757260\">also</span> <span m=\"3757530\">equivalent</span> <span m=\"\
  3758010\">to</span> <span m=\"3758160\">each</span> <span m=\"3758340\">other?</span></p><p><span\
  \ m=\"3759400\">And</span> <span m=\"3759600\">the</span> <span m=\"3759780\">answer</span>\
  \ <span m=\"3760150\">is</span> <span m=\"3760410\">emphatically</span> <span m=\"\
  3761000\">no,</span> <span m=\"3761340\">absolutely</span> <span m=\"3761880\">not.</span>\
  \ <span m=\"3762370\">So</span> <span m=\"3762450\">all</span> <span m=\"3762630\"\
  >of</span> <span m=\"3762690\">these</span> <span m=\"3763290\">equivalents</span>\
  \ <span m=\"3763980\">fail</span> <span m=\"3765780\">for</span> <span m=\"3768300\"\
  >sparse.</span> <span m=\"3770920\">Some</span> <span m=\"3771220\">of</span> <span\
  \ m=\"3771280\">them</span> <span m=\"3771460\">are</span> <span m=\"3771550\">still</span>\
  \ <span m=\"3771820\">true.</span> <span m=\"3772240\">Some</span> <span m=\"3772450\"\
  >of</span> <span m=\"3772510\">the</span> <span m=\"3772600\">easier</span> <span\
  \ m=\"3773020\">ones</span> <span m=\"3773290\">that</span> <span m=\"3773440\"\
  >we</span> <span m=\"3773560\">did--</span> <span m=\"3773740\">for</span> <span\
  \ m=\"3773890\">example,</span> <span m=\"3774220\">the</span> <span m=\"3774310\"\
  >two</span> <span m=\"3775090\">versions</span> <span m=\"3775480\">of</span> <span\
  \ m=\"3775570\">DISC</span> <span m=\"3775930\">are</span> <span m=\"3776050\">equivalent.</span>\
  \ <span m=\"3776920\">That's</span> <span m=\"3777170\">still</span> <span m=\"\
  3777270\">OK.</span></p><p><span m=\"3778120\">And</span> <span m=\"3778300\">some</span>\
  \ <span m=\"3778630\">of</span> <span m=\"3778750\">these</span> <span m=\"3778960\"\
  >calculations</span> <span m=\"3779720\">involving</span> <span m=\"3781270\">Cauchy-Schwarz</span>\
  \ <span m=\"3782860\">are</span> <span m=\"3783940\">mostly</span> <span m=\"3784360\"\
  >still</span> <span m=\"3784600\">OK.</span> <span m=\"3786250\">But</span> <span\
  \ m=\"3786370\">the</span> <span m=\"3786460\">one</span> <span m=\"3786700\">that</span>\
  \ <span m=\"3786880\">really</span> <span m=\"3787180\">fails</span> <span m=\"\
  3788530\">is</span> <span m=\"3788680\">the</span> <span m=\"3788770\">counting</span>\
  \ <span m=\"3789200\">lemma.</span> <span m=\"3801360\">And</span> <span m=\"3801480\"\
  >let</span> <span m=\"3801570\">me</span> <span m=\"3801720\">explain</span> <span\
  \ m=\"3802170\">why</span> <span m=\"3802440\">with</span> <span m=\"3802650\">an</span>\
  \ <span m=\"3802770\">example.</span></p><p><span m=\"3804090\">So</span> <span\
  \ m=\"3804180\">I</span> <span m=\"3804240\">want</span> <span m=\"3804420\">to</span>\
  \ <span m=\"3804510\">give</span> <span m=\"3804690\">you</span> <span m=\"3804810\"\
  >an</span> <span m=\"3804900\">example</span> <span m=\"3805830\">of</span> <span\
  \ m=\"3805950\">a</span> <span m=\"3806010\">graph</span> <span m=\"3806760\">which</span>\
  \ <span m=\"3807450\">looks</span> <span m=\"3807720\">pseudorandom</span> <span\
  \ m=\"3808980\">in</span> <span m=\"3809070\">the</span> <span m=\"3809160\">sense</span>\
  \ <span m=\"3809580\">of</span> <span m=\"3809970\">DISC</span> <span m=\"3812570\"\
  >but</span> <span m=\"3814340\">has</span> <span m=\"3814580\">no,</span> <span\
  \ m=\"3816280\">let's</span> <span m=\"3816480\">say,</span> <span m=\"3816590\"\
  >C3</span> <span m=\"3817110\">count.</span> <span m=\"3818615\">It</span> <span\
  \ m=\"3819040\">also</span> <span m=\"3819280\">has</span> <span m=\"3819400\">no</span>\
  \ <span m=\"3819550\">C4</span> <span m=\"3819960\">count,</span> <span m=\"3820325\"\
  >but</span> <span m=\"3820690\">it</span> <span m=\"3820900\">has</span> <span m=\"\
  3821050\">no--</span> <span m=\"3822180\">has the</span> <span m=\"3822300\">clean,</span>\
  \ <span m=\"3822550\">correct</span> <span m=\"3823540\">number</span> <span m=\"\
  3823780\">of</span> <span m=\"3823870\">triangles.</span></p><p><span m=\"3829820\"\
  >So</span> <span m=\"3829840\">what's</span> <span m=\"3830050\">this</span> <span\
  \ m=\"3830200\">example?</span> <span m=\"3831460\">So</span> <span m=\"3831820\"\
  >let</span> <span m=\"3832310\">p</span> <span m=\"3832810\">be</span> <span m=\"\
  3833200\">some</span> <span m=\"3834220\">number</span> <span m=\"3834700\">which</span>\
  \ <span m=\"3835030\">is</span> <span m=\"3835600\">little</span> <span m=\"3835780\"\
  >o</span> <span m=\"3836140\">of</span> <span m=\"3836410\">1</span> <span m=\"\
  3836680\">over</span> <span m=\"3838400\">root n</span> <span m=\"3839800\">so</span>\
  \ <span m=\"3840400\">some</span> <span m=\"3842200\">decaying</span> <span m=\"\
  3842650\">quantity</span> <span m=\"3843400\">with</span> <span m=\"3843800\">n.</span>\
  \ <span m=\"3844920\">And</span> <span m=\"3845170\">let's</span> <span m=\"3845380\"\
  >consider</span> <span m=\"3846130\">Gnp.</span> <span m=\"3850820\">Well,</span>\
  \ <span m=\"3850940\">how</span> <span m=\"3851090\">many</span> <span m=\"3851300\"\
  >triangles</span> <span m=\"3851840\">do</span> <span m=\"3851930\">we</span> <span\
  \ m=\"3852050\">expect</span> <span m=\"3852400\">in</span> <span m=\"3852530\"\
  >Gnp?</span> <span m=\"3854120\">So</span> <span m=\"3854360\">let's</span> <span\
  \ m=\"3854660\">think</span> <span m=\"3854870\">of</span> <span m=\"3854960\">p\
  \ as</span> <span m=\"3855260\">just</span> <span m=\"3855410\">slightly</span>\
  \ <span m=\"3855860\">below</span> <span m=\"3856650\">1</span> <span m=\"3856900\"\
  >over</span> <span m=\"3857040\">root n.</span></p><p><span m=\"3858860\">So</span>\
  \ <span m=\"3859100\">the</span> <span m=\"3859190\">number</span> <span m=\"3859460\"\
  >of</span> <span m=\"3859520\">triangles</span> <span m=\"3860030\">in</span> <span\
  \ m=\"3860120\">Gnp</span> <span m=\"3860690\">in</span> <span m=\"3861070\">expectation</span>\
  \ <span m=\"3864980\">is--</span> <span m=\"3868520\">so</span> <span m=\"3868970\"\
  >that's</span> <span m=\"3869450\">the</span> <span m=\"3869570\">expected</span>\
  \ <span m=\"3870050\">number.</span> <span m=\"3871100\">And</span> <span m=\"3871340\"\
  >you</span> <span m=\"3871460\">should</span> <span m=\"3871610\">expect</span>\
  \ <span m=\"3871940\">the</span> <span m=\"3872030\">actual</span> <span m=\"3872330\"\
  >number</span> <span m=\"3872600\">to</span> <span m=\"3872720\">be</span> <span\
  \ m=\"3873170\">roughly</span> <span m=\"3873560\">around</span> <span m=\"3873860\"\
  >that.</span> <span m=\"3875970\">But</span> <span m=\"3876170\">on</span> <span\
  \ m=\"3876290\">the</span> <span m=\"3876380\">other</span> <span m=\"3876560\"\
  >hand,</span> <span m=\"3877680\">the</span> <span m=\"3878510\">number</span> <span\
  \ m=\"3878870\">of</span> <span m=\"3879080\">edges</span> <span m=\"3883600\">is</span>\
  \ <span m=\"3883750\">also</span> <span m=\"3885670\">expected</span> <span m=\"\
  3886360\">to</span> <span m=\"3886480\">be</span> <span m=\"3887950\">this</span>\
  \ <span m=\"3888160\">quantity</span> <span m=\"3888520\">here.</span> <span m=\"\
  3888950\">And</span> <span m=\"3889210\">you</span> <span m=\"3889510\">expect</span>\
  \ <span m=\"3889990\">that</span> <span m=\"3890080\">the</span> <span m=\"3890170\"\
  >actual</span> <span m=\"3890500\">number</span> <span m=\"3890770\">of</span> <span\
  \ m=\"3890860\">edges</span> <span m=\"3891190\">to</span> <span m=\"3891280\">be</span>\
  \ <span m=\"3891400\">very</span> <span m=\"3891610\">close</span> <span m=\"3891910\"\
  >to</span> <span m=\"3892060\">it.</span></p><p><span m=\"3893930\">But</span> <span\
  \ m=\"3894080\">p</span> <span m=\"3894560\">is</span> <span m=\"3894770\">chosen</span>\
  \ <span m=\"3895850\">so</span> <span m=\"3896240\">that</span> <span m=\"3896840\"\
  >the</span> <span m=\"3896930\">number</span> <span m=\"3897350\">of</span> <span\
  \ m=\"3897440\">triangles</span> <span m=\"3899090\">is</span> <span m=\"3899390\"\
  >significantly</span> <span m=\"3900230\">smaller</span> <span m=\"3901220\">than</span>\
  \ <span m=\"3901370\">the</span> <span m=\"3901460\">number</span> <span m=\"3901820\"\
  >of</span> <span m=\"3902330\">edges,</span> <span m=\"3904230\">so</span> <span\
  \ m=\"3904360\">asymptotically</span> <span m=\"3905250\">smaller,</span> <span\
  \ m=\"3906690\">fewer</span> <span m=\"3907380\">copies</span> <span m=\"3907800\"\
  >of</span> <span m=\"3907920\">triangles</span> <span m=\"3908460\">than</span>\
  \ <span m=\"3908850\">edges.</span> <span m=\"3909630\">So</span> <span m=\"3909840\"\
  >what</span> <span m=\"3910020\">we</span> <span m=\"3910170\">can</span> <span\
  \ m=\"3910350\">do</span> <span m=\"3910560\">now</span> <span m=\"3911700\">is</span>\
  \ <span m=\"3912480\">remove</span> <span m=\"3915090\">an</span> <span m=\"3915330\"\
  >edge</span> <span m=\"3917510\">from</span> <span m=\"3920480\">each</span> <span\
  \ m=\"3920750\">copy</span> <span m=\"3921440\">of</span> <span m=\"3921590\">a</span>\
  \ <span m=\"3921620\">triangle</span> <span m=\"3926680\">in</span> <span m=\"3927430\"\
  >this</span> <span m=\"3928000\">Gnp.</span> <span m=\"3933080\">We</span> <span\
  \ m=\"3934640\">removed</span> <span m=\"3939130\">a</span> <span m=\"3939250\"\
  >tiny</span> <span m=\"3939790\">fraction</span> <span m=\"3942062\">of</span> <span\
  \ m=\"3942900\">edges,</span> <span m=\"3946630\">because</span> <span m=\"3947050\"\
  >the</span> <span m=\"3947140\">number</span> <span m=\"3947470\">of</span> <span\
  \ m=\"3947530\">triangles</span> <span m=\"3947980\">is</span> <span m=\"3948100\"\
  >much</span> <span m=\"3948370\">less</span> <span m=\"3948590\">than the</span>\
  \ <span m=\"3948680\">number</span> <span m=\"3948970\">of</span> <span m=\"3949300\"\
  >edges.</span> <span m=\"3949630\">We</span> <span m=\"3949750\">removed</span>\
  \ <span m=\"3950170\">a</span> <span m=\"3950200\">tiny</span> <span m=\"3950620\"\
  >fraction</span> <span m=\"3951100\">of</span> <span m=\"3951190\">edges.</span></p><p><span\
  \ m=\"3952370\">And</span> <span m=\"3952480\">as</span> <span m=\"3952660\">a</span>\
  \ <span m=\"3952720\">result,</span> <span m=\"3953630\">we</span> <span m=\"3953680\"\
  >do</span> <span m=\"3953860\">not</span> <span m=\"3954160\">change</span> <span\
  \ m=\"3954730\">the</span> <span m=\"3954850\">discrepancy</span> <span m=\"3955560\"\
  >condition</span> <span m=\"3959770\">up</span> <span m=\"3959900\">to</span> <span\
  \ m=\"3960320\">a</span> <span m=\"3960410\">small</span> <span m=\"3961350\">error.</span>\
  \ <span m=\"3961940\">So</span> <span m=\"3962120\">the</span> <span m=\"3962240\"\
  >discrepancy</span> <span m=\"3962870\">condition</span> <span m=\"3964160\">still</span>\
  \ <span m=\"3964490\">holds.</span> <span m=\"3968780\">However,</span> <span m=\"\
  3969380\">the</span> <span m=\"3969530\">graph</span> <span m=\"3969830\">has</span>\
  \ <span m=\"3969950\">no</span> <span m=\"3970050\">more</span> <span m=\"3970250\"\
  >triangles.</span> <span m=\"3987600\">So</span> <span m=\"3987800\">you</span>\
  \ <span m=\"3987920\">have</span> <span m=\"3988040\">this</span> <span m=\"3988700\"\
  >pseudorandom</span> <span m=\"3989480\">graph</span> <span m=\"3989930\">in</span>\
  \ <span m=\"3990140\">one</span> <span m=\"3990380\">sense--</span> <span m=\"3991130\"\
  >namely,</span> <span m=\"3991490\">of</span> <span m=\"3991610\">having</span>\
  \ <span m=\"3991860\">a</span> <span m=\"3991880\">discrepancy--</span> <span m=\"\
  3992840\">but</span> <span m=\"3993260\">fails</span> <span m=\"3993710\">to</span>\
  \ <span m=\"3993800\">be</span> <span m=\"3993920\">pseudorandom</span> <span m=\"\
  3994490\">in</span> <span m=\"3994550\">a</span> <span m=\"3994610\">different</span>\
  \ <span m=\"3994910\">sense--</span> <span m=\"3995510\">namely,</span> <span m=\"\
  3995795\">it</span> <span m=\"3996080\">has</span> <span m=\"3996290\">no</span>\
  \ <span m=\"3996500\">triangles.</span> <span m=\"3998050\">Yep.</span></p><p><span\
  \ m=\"3999520\">AUDIENCE:</span> <span m=\"3999642\">Do</span> <span m=\"3999764\"\
  >the</span> <span m=\"3999886\">conditions</span> <span m=\"4000010\">C4</span>\
  \ <span m=\"4000500\">and</span> <span m=\"4000990\">codegree</span> <span m=\"\
  4001480\">also</span> <span m=\"4001970\">hold here--</span> <span m=\"4002460\"\
  >so the</span> <span m=\"4002950\">issue</span> <span m=\"4003440\">being from</span>\
  \ <span m=\"4003930\">DISC</span> <span m=\"4004420\">to count?</span></p><p><span\
  \ m=\"4005410\">PROFESSOR:</span> <span m=\"4005560\">Question,</span> <span m=\"\
  4005710\">do</span> <span m=\"4005830\">the</span> <span m=\"4006340\">conditions</span>\
  \ <span m=\"4006820\">C4</span> <span m=\"4007450\">and</span> <span m=\"4007600\"\
  >codegree</span> <span m=\"4008050\">still</span> <span m=\"4008320\">hold</span>\
  \ <span m=\"4008590\">here?</span> <span m=\"4009130\">Basically,</span> <span m=\"\
  4009680\">downstream</span> <span m=\"4010460\">is</span> <span m=\"4010660\">OK,</span>\
  \ <span m=\"4010900\">but</span> <span m=\"4011080\">upstream</span> <span m=\"\
  4011530\">is</span> <span m=\"4011650\">not.</span> <span m=\"4014550\">So</span>\
  \ <span m=\"4014650\">we</span> <span m=\"4014710\">can</span> <span m=\"4014850\"\
  >go</span> <span m=\"4015030\">from</span> <span m=\"4015210\">C4</span> <span m=\"\
  4015450\">to</span> <span m=\"4015720\">codegree</span> <span m=\"4016110\">to</span>\
  \ <span m=\"4016280\">DISC.</span> <span m=\"4016830\">But</span> <span m=\"4016980\"\
  >you</span> <span m=\"4017100\">can't</span> <span m=\"4017370\">go</span> <span\
  \ m=\"4017550\">upward.</span> <span m=\"4020120\">And</span> <span m=\"4020300\"\
  >understanding</span> <span m=\"4022070\">how</span> <span m=\"4022430\">to</span>\
  \ <span m=\"4025030\">rectify</span> <span m=\"4025600\">the</span> <span m=\"4025720\"\
  >situation,</span> <span m=\"4027010\">perhaps</span> <span m=\"4027340\">adding</span>\
  \ <span m=\"4027670\">additional</span> <span m=\"4028090\">hypotheses</span> <span\
  \ m=\"4028930\">to</span> <span m=\"4029080\">make</span> <span m=\"4029290\">this</span>\
  \ <span m=\"4029440\">true</span> <span m=\"4031000\">so</span> <span m=\"4031210\"\
  >that</span> <span m=\"4031390\">you</span> <span m=\"4031510\">could</span> <span\
  \ m=\"4031780\">have</span> <span m=\"4032710\">counting</span> <span m=\"4033160\"\
  >lemmas</span> <span m=\"4033870\">for</span> <span m=\"4034060\">triangles</span>\
  \ <span m=\"4034660\">and</span> <span m=\"4034750\">other</span> <span m=\"4034930\"\
  >graphs</span> <span m=\"4035330\">and</span> <span m=\"4035470\">sparser</span>\
  \ <span m=\"4036040\">graphs,</span> <span m=\"4036790\">that's</span> <span m=\"\
  4037140\">an</span> <span m=\"4037210\">important</span> <span m=\"4038260\">topic.</span>\
  \ <span m=\"4039400\">And</span> <span m=\"4039550\">this</span> <span m=\"4039700\"\
  >is</span> <span m=\"4039760\">something</span> <span m=\"4040030\">that</span>\
  \ <span m=\"4040130\">I'll</span> <span m=\"4040240\">discuss</span> <span m=\"\
  4040990\">at</span> <span m=\"4041110\">greater</span> <span m=\"4041380\">length</span>\
  \ <span m=\"4041740\">in</span> <span m=\"4042370\">not</span> <span m=\"4043270\"\
  >next</span> <span m=\"4043570\">lecture,</span> <span m=\"4043870\">but</span>\
  \ <span m=\"4043990\">the</span> <span m=\"4044050\">one</span> <span m=\"4044260\"\
  >after</span> <span m=\"4044530\">that.</span></p><p><span m=\"4045280\">And</span>\
  \ <span m=\"4045400\">this</span> <span m=\"4045550\">is,</span> <span m=\"4045640\"\
  >in</span> <span m=\"4045760\">fact,</span> <span m=\"4046000\">related</span> <span\
  \ m=\"4046780\">to</span> <span m=\"4047440\">the</span> <span m=\"4047560\">Green-Tao</span>\
  \ <span m=\"4048160\">theorem,</span> <span m=\"4048970\">which</span> <span m=\"\
  4049180\">allows</span> <span m=\"4049540\">you</span> <span m=\"4049750\">to</span>\
  \ <span m=\"4050810\">approve</span> <span m=\"4051490\">Szemer\xE9di's</span> <span\
  \ m=\"4052030\">theorem</span> <span m=\"4052600\">among</span> <span m=\"4052870\"\
  >the</span> <span m=\"4052930\">primes.</span> <span m=\"4053490\">The</span> <span\
  \ m=\"4053650\">primes</span> <span m=\"4054100\">contain</span> <span m=\"4054640\"\
  >arbitrarily</span> <span m=\"4055180\">long</span> <span m=\"4055510\">arithmetic</span>\
  \ <span m=\"4055960\">progressions,</span> <span m=\"4057040\">because</span> <span\
  \ m=\"4057400\">the</span> <span m=\"4057490\">primes</span> <span m=\"4058120\"\
  >are</span> <span m=\"4058240\">also</span> <span m=\"4058720\">a</span> <span m=\"\
  4059050\">sparse</span> <span m=\"4059540\">set.</span> <span m=\"4060400\">So</span>\
  \ <span m=\"4060820\">it</span> <span m=\"4060940\">has</span> <span m=\"4061090\"\
  >density</span> <span m=\"4061480\">going</span> <span m=\"4061720\">to</span> <span\
  \ m=\"4061840\">0.</span> <span m=\"4062260\">It's</span> <span m=\"4062610\">density</span>\
  \ <span m=\"4062980\">decaying,</span> <span m=\"4063370\">like,</span> <span m=\"\
  4063550\">1</span> <span m=\"4063730\">over</span> <span m=\"4063910\">log</span>\
  \ <span m=\"4064150\">n,</span> <span m=\"4064360\">according</span> <span m=\"\
  4064690\">to</span> <span m=\"4064780\">prime</span> <span m=\"4065050\">number</span>\
  \ <span m=\"4065320\">theorem.</span></p><p><span m=\"4067220\">But</span> <span\
  \ m=\"4067420\">you</span> <span m=\"4067570\">want</span> <span m=\"4067750\">to</span>\
  \ <span m=\"4067820\">do</span> <span m=\"4068110\">regularity</span> <span m=\"\
  4068770\">method.</span> <span m=\"4069610\">So</span> <span m=\"4069850\">you</span>\
  \ <span m=\"4070000\">have</span> <span m=\"4070240\">to</span> <span m=\"4070330\"\
  >face</span> <span m=\"4070750\">this</span> <span m=\"4070960\">kind</span> <span\
  \ m=\"4071230\">of</span> <span m=\"4071320\">issues.</span> <span m=\"4073020\"\
  >So</span> <span m=\"4074900\">we'll</span> <span m=\"4074990\">discuss</span> <span\
  \ m=\"4075380\">that</span> <span m=\"4075500\">more at</span> <span m=\"4075740\"\
  >length</span> <span m=\"4076040\">in</span> <span m=\"4076130\">a</span> <span\
  \ m=\"4076190\">couple</span> <span m=\"4076410\">of</span> <span m=\"4076450\"\
  >lectures.</span> <span m=\"4077150\">But</span> <span m=\"4077200\">for</span>\
  \ <span m=\"4077300\">now,</span> <span m=\"4077700\">just</span> <span m=\"4077810\"\
  >a</span> <span m=\"4077870\">warning</span> <span m=\"4078410\">that</span> <span\
  \ m=\"4079190\">everything</span> <span m=\"4079520\">here</span> <span m=\"4080200\"\
  >is</span> <span m=\"4080330\">really</span> <span m=\"4080540\">about</span> <span\
  \ m=\"4080720\">dense</span> <span m=\"4080990\">graphs.</span></p><p><span m=\"\
  4084160\">The</span> <span m=\"4084250\">next</span> <span m=\"4084490\">thing</span>\
  \ <span m=\"4084640\">I</span> <span m=\"4084700\">want</span> <span m=\"4084870\"\
  >to</span> <span m=\"4084910\">discuss</span> <span m=\"4086140\">is</span> <span\
  \ m=\"4086830\">an</span> <span m=\"4086980\">elaboration</span> <span m=\"4087760\"\
  >of</span> <span m=\"4088120\">what</span> <span m=\"4088330\">happens</span> <span\
  \ m=\"4088630\">to</span> <span m=\"4088750\">these</span> <span m=\"4088940\">eigenvalue</span>\
  \ <span m=\"4089440\">conditions.</span> <span m=\"4096939\">So</span> <span m=\"\
  4097020\">for</span> <span m=\"4097200\">dense</span> <span m=\"4097590\">graphs,</span>\
  \ <span m=\"4099120\">in</span> <span m=\"4099240\">some</span> <span m=\"4099420\"\
  >sense,</span> <span m=\"4099649\">everything's</span> <span m=\"4100050\">very</span>\
  \ <span m=\"4100260\">clear</span> <span m=\"4100590\">from</span> <span m=\"4100800\"\
  >this</span> <span m=\"4100979\">theorem.</span> <span m=\"4101520\">Once</span>\
  \ <span m=\"4101770\">you</span> <span m=\"4101850\">have</span> <span m=\"4101910\"\
  >this,</span> <span m=\"4102000\">theorem,</span> <span m=\"4102590\">they're</span>\
  \ <span m=\"4102720\">all</span> <span m=\"4102870\">equivalent.</span> <span m=\"\
  4103319\">You</span> <span m=\"4103410\">can</span> <span m=\"4103529\">go</span>\
  \ <span m=\"4103649\">back</span> <span m=\"4103830\">and</span> <span m=\"4103920\"\
  >forth.</span> <span m=\"4104640\">And</span> <span m=\"4105060\">you</span> <span\
  \ m=\"4105180\">lose</span> <span m=\"4105390\">a</span> <span m=\"4105420\">little</span>\
  \ <span m=\"4105600\">bit</span> <span m=\"4105720\">of</span> <span m=\"4106109\"\
  >epsilon</span> <span m=\"4106500\">here</span> <span m=\"4106680\">and</span> <span\
  \ m=\"4106770\">there,</span> <span m=\"4106950\">but</span> <span m=\"4107100\"\
  >everything</span> <span m=\"4107399\">is</span> <span m=\"4107460\">more</span>\
  \ <span m=\"4107580\">or</span> <span m=\"4107609\">less</span> <span m=\"4107819\"\
  >the</span> <span m=\"4107880\">same.</span></p><p><span m=\"4108430\">But</span>\
  \ <span m=\"4108689\">if</span> <span m=\"4108810\">you</span> <span m=\"4108870\"\
  >go</span> <span m=\"4108990\">to</span> <span m=\"4109109\">sparser</span> <span\
  \ m=\"4109609\">world,</span> <span m=\"4110220\">then</span> <span m=\"4110490\"\
  >you</span> <span m=\"4110609\">really</span> <span m=\"4110819\">need</span> <span\
  \ m=\"4111000\">to</span> <span m=\"4111060\">be</span> <span m=\"4111180\">much</span>\
  \ <span m=\"4111390\">more</span> <span m=\"4111510\">careful.</span> <span m=\"\
  4111825\">And</span> <span m=\"4112140\">we</span> <span m=\"4112180\">need</span>\
  \ <span m=\"4112310\">to</span> <span m=\"4112380\">think</span> <span m=\"4112560\"\
  >about</span> <span m=\"4112740\">other</span> <span m=\"4112950\">tools.</span>\
  \ <span m=\"4116450\">And</span> <span m=\"4116620\">so</span> <span m=\"4116710\"\
  >the</span> <span m=\"4116770\">remainder</span> <span m=\"4117250\">of</span> <span\
  \ m=\"4117340\">today,</span> <span m=\"4117640\">I</span> <span m=\"4117729\">want</span>\
  \ <span m=\"4117939\">to</span> <span m=\"4118270\">just</span> <span m=\"4118450\"\
  >discuss</span> <span m=\"4118930\">one</span> <span m=\"4119950\">fairly</span>\
  \ <span m=\"4120250\">simple</span> <span m=\"4120670\">but</span> <span m=\"4120760\"\
  >powerful</span> <span m=\"4121240\">tool</span> <span m=\"4121990\">relating</span>\
  \ <span m=\"4123279\">eigenvalues</span> <span m=\"4123910\">on</span> <span m=\"\
  4124000\">one</span> <span m=\"4124180\">hand</span> <span m=\"4124810\">and</span>\
  \ <span m=\"4124930\">the</span> <span m=\"4124990\">discrepancy</span> <span m=\"\
  4125590\">condition</span> <span m=\"4126069\">on</span> <span m=\"4126160\">the</span>\
  \ <span m=\"4126279\">other</span> <span m=\"4126430\">hand.</span></p><p><span\
  \ m=\"4127936\">All</span> <span m=\"4128370\">right.</span> <span m=\"4128649\"\
  >So</span> <span m=\"4128800\">you</span> <span m=\"4128920\">can</span> <span m=\"\
  4129040\">go</span> <span m=\"4129220\">from</span> <span m=\"4129520\">eigenvalue</span>\
  \ <span m=\"4130240\">to</span> <span m=\"4130359\">discrepancy</span> <span m=\"\
  4131109\">by</span> <span m=\"4131290\">going</span> <span m=\"4131590\">down</span>\
  \ <span m=\"4131830\">this</span> <span m=\"4132010\">chain.</span> <span m=\"4132370\"\
  >But</span> <span m=\"4133450\">actually,</span> <span m=\"4133810\">there's</span>\
  \ <span m=\"4133990\">a</span> <span m=\"4134050\">much</span> <span m=\"4134260\"\
  >quicker</span> <span m=\"4134590\">route.</span> <span m=\"4136470\">And</span>\
  \ <span m=\"4136630\">this</span> <span m=\"4136810\">is</span> <span m=\"4136899\"\
  >known</span> <span m=\"4137140\">as</span> <span m=\"4137260\">the</span> <span\
  \ m=\"4137380\">expander</span> <span m=\"4137920\">mixing</span> <span m=\"4138250\"\
  >lemma.</span></p><p><span m=\"4150950\">For</span> <span m=\"4151130\">simplicity</span>\
  \ <span m=\"4152899\">and</span> <span m=\"4153020\">really</span> <span m=\"4153590\"\
  >will</span> <span m=\"4153800\">make</span> <span m=\"4154040\">our</span> <span\
  \ m=\"4154399\">life</span> <span m=\"4154640\">much</span> <span m=\"4154880\"\
  >simpler,</span> <span m=\"4155450\">we're</span> <span m=\"4155600\">only</span>\
  \ <span m=\"4155840\">going</span> <span m=\"4156020\">to</span> <span m=\"4156109\"\
  >consider</span> <span m=\"4157000\">d-regular</span> <span m=\"4157609\">graphs.</span>\
  \ <span m=\"4158866\">So</span> <span m=\"4159270\">here,</span> <span m=\"4159710\"\
  >d-regular</span> <span m=\"4160310\">means</span> <span m=\"4160550\">every</span>\
  \ <span m=\"4160729\">vertex</span> <span m=\"4160939\">is</span> <span m=\"4161300\"\
  >degree</span> <span m=\"4161420\">d.</span> <span m=\"4162859\">Same</span> <span\
  \ m=\"4163160\">word,</span> <span m=\"4163430\">but</span> <span m=\"4163550\"\
  >different</span> <span m=\"4163819\">meaning</span> <span m=\"4164120\">from</span>\
  \ <span m=\"4164390\">epsilon</span> <span m=\"4164840\">regular.</span> <span m=\"\
  4165899\">And unfortunately,</span> <span m=\"4166760\">that's</span> <span m=\"\
  4167000\">just</span> <span m=\"4167180\">the</span> <span m=\"4167270\">way</span>\
  \ <span m=\"4167420\">it</span> <span m=\"4167500\">is.</span></p><p><span m=\"\
  4168689\">So</span> <span m=\"4168870\">d</span> <span m=\"4169109\">regular,</span>\
  \ <span m=\"4169850\">and</span> <span m=\"4170029\">we're</span> <span m=\"4170180\"\
  >going</span> <span m=\"4170340\">to</span> <span m=\"4170410\">have</span> <span\
  \ m=\"4170680\">n</span> <span m=\"4170870\">vertices.</span> <span m=\"4173590\"\
  >And</span> <span m=\"4174310\">the</span> <span m=\"4174580\">adjacency</span>\
  \ <span m=\"4175120\">matrix</span> <span m=\"4177859\">has</span> <span m=\"4178240\"\
  >eigenvalues</span> <span m=\"4181090\">lambda</span> <span m=\"4181390\">1,</span>\
  \ <span m=\"4182279\">lambda</span> <span m=\"4182590\">2,</span> <span m=\"4183170\"\
  >and</span> <span m=\"4183399\">so</span> <span m=\"4183569\">on,</span> <span m=\"\
  4185020\">arranged</span> <span m=\"4185470\">in</span> <span m=\"4185710\">decreasing</span>\
  \ <span m=\"4186430\">order.</span> <span m=\"4190540\">Let</span> <span m=\"4190689\"\
  >me</span> <span m=\"4190840\">write</span> <span m=\"4191319\">lambda</span> <span\
  \ m=\"4192740\">as</span> <span m=\"4194790\">the</span> <span m=\"4194920\">maximum</span>\
  \ <span m=\"4196600\">in</span> <span m=\"4196900\">absolute</span> <span m=\"4197440\"\
  >value</span> <span m=\"4198730\">of</span> <span m=\"4198940\">the</span> <span\
  \ m=\"4199160\">eigenvalues</span> <span m=\"4199780\">except</span> <span m=\"\
  4200230\">for</span> <span m=\"4200380\">the</span> <span m=\"4200470\">top</span>\
  \ <span m=\"4200800\">one.</span></p><p><span m=\"4202910\">In</span> <span m=\"\
  4203000\">particular,</span> <span m=\"4203630\">this</span> <span m=\"4203810\"\
  >is</span> <span m=\"4203960\">either</span> <span m=\"4204350\">the</span> <span\
  \ m=\"4204650\">absolute</span> <span m=\"4205070\">value</span> <span m=\"4205550\"\
  >of</span> <span m=\"4206750\">the</span> <span m=\"4206810\">second</span> <span\
  \ m=\"4208010\">one</span> <span m=\"4208460\">or</span> <span m=\"4209920\">the</span>\
  \ <span m=\"4210010\">last</span> <span m=\"4210310\">one.</span> <span m=\"4212030\"\
  >As</span> <span m=\"4212180\">I</span> <span m=\"4212240\">mentioned</span> <span\
  \ m=\"4212510\">earlier,</span> <span m=\"4212870\">the</span> <span m=\"4212960\"\
  >top</span> <span m=\"4213290\">eigenvalue</span> <span m=\"4214120\">is</span>\
  \ <span m=\"4214310\">necessarily</span> <span m=\"4215590\">d,</span> <span m=\"\
  4216350\">because</span> <span m=\"4216800\">you</span> <span m=\"4216920\">have</span>\
  \ <span m=\"4218020\">all-ones</span> <span m=\"4218600\">vector</span> <span m=\"\
  4219020\">as</span> <span m=\"4219200\">an</span> <span m=\"4219320\">eigenvector.</span></p><p><span\
  \ m=\"4222960\">So</span> <span m=\"4223170\">the</span> <span m=\"4223350\">expander</span>\
  \ <span m=\"4225160\">mixing</span> <span m=\"4225520\">lemma</span> <span m=\"\
  4227110\">says</span> <span m=\"4228040\">that</span> <span m=\"4229660\">if</span>\
  \ <span m=\"4229810\">I</span> <span m=\"4229900\">look</span> <span m=\"4230140\"\
  >at</span> <span m=\"4230290\">two</span> <span m=\"4230620\">vertex</span> <span\
  \ m=\"4231130\">subsets,</span> <span m=\"4236240\">the</span> <span m=\"4236340\"\
  >number</span> <span m=\"4236680\">of</span> <span m=\"4236920\">edges</span> <span\
  \ m=\"4237280\">between</span> <span m=\"4237640\">them</span> <span m=\"4238240\"\
  >compared</span> <span m=\"4238760\">to</span> <span m=\"4238960\">what</span> <span\
  \ m=\"4239140\">you</span> <span m=\"4239290\">would</span> <span m=\"4239410\"\
  >expect</span> <span m=\"4239950\">in</span> <span m=\"4240070\">a</span> <span\
  \ m=\"4240130\">random</span> <span m=\"4240520\">case--</span> <span m=\"4240810\"\
  >so</span> <span m=\"4240940\">just</span> <span m=\"4241180\">like</span> <span\
  \ m=\"4241360\">in</span> <span m=\"4241460\">the</span> <span m=\"4241550\">disc</span>\
  \ <span m=\"4241840\">setting,</span> <span m=\"4242230\">but</span> <span m=\"\
  4242650\">here,</span> <span m=\"4242860\">the</span> <span m=\"4243100\">correct</span>\
  \ <span m=\"4243970\">density</span> <span m=\"4244360\">I</span> <span m=\"4244430\"\
  >should</span> <span m=\"4244570\">put</span> <span m=\"4244730\">is</span> <span\
  \ m=\"4244900\">d</span> <span m=\"4245110\">over</span> <span m=\"4245310\">n--</span>\
  \ <span m=\"4248460\">this</span> <span m=\"4248640\">quantity</span> <span m=\"\
  4249720\">is</span> <span m=\"4250470\">upper</span> <span m=\"4250700\">bounded</span>\
  \ <span m=\"4251490\">by</span> <span m=\"4252300\">lambda</span> <span m=\"4253080\"\
  >times</span> <span m=\"4253590\">the</span> <span m=\"4255310\">root</span> <span\
  \ m=\"4255810\">of</span> <span m=\"4255990\">the</span> <span m=\"4256120\">product</span>\
  \ <span m=\"4256720\">of</span> <span m=\"4256990\">x</span> <span m=\"4257320\"\
  >and</span> <span m=\"4257410\">y.</span> <span m=\"4263400\">So</span> <span m=\"\
  4264510\">in</span> <span m=\"4264600\">particular,</span> <span m=\"4265900\">if</span>\
  \ <span m=\"4266880\">this</span> <span m=\"4267040\">lambda--</span> <span m=\"\
  4267780\">so</span> <span m=\"4267990\">everything</span> <span m=\"4268390\">except</span>\
  \ <span m=\"4268590\">for</span> <span m=\"4268660\">the</span> <span m=\"4268740\"\
  >top</span> <span m=\"4268980\">eigenvalue--</span> <span m=\"4269230\">is</span>\
  \ <span m=\"4269694\">small,</span> <span m=\"4271550\">then</span> <span m=\"4272060\"\
  >this</span> <span m=\"4272270\">discrepancy</span> <span m=\"4273170\">should</span>\
  \ <span m=\"4273470\">be</span> <span m=\"4273740\">small.</span> <span m=\"4275250\"\
  >And</span> <span m=\"4275370\">you</span> <span m=\"4275430\">can</span> <span\
  \ m=\"4275610\">verify</span> <span m=\"4276120\">with</span> <span m=\"4276330\"\
  >what</span> <span m=\"4276480\">we</span> <span m=\"4276660\">did,</span> <span\
  \ m=\"4276930\">that</span> <span m=\"4277080\">it's</span> <span m=\"4277230\"\
  >consistent,</span> <span m=\"4277980\">what</span> <span m=\"4278160\">we</span>\
  \ <span m=\"4279390\">just</span> <span m=\"4279580\">did.</span></p><p><span m=\"\
  4283430\">All</span> <span m=\"4283590\">right.</span> <span m=\"4285640\">So</span>\
  \ <span m=\"4285760\">let's</span> <span m=\"4285910\">prove</span> <span m=\"4286210\"\
  >the</span> <span m=\"4286300\">expander</span> <span m=\"4286720\">mixing</span>\
  \ <span m=\"4287060\">lemma,</span> <span m=\"4287410\">which</span> <span m=\"\
  4287590\">is</span> <span m=\"4288550\">pretty</span> <span m=\"4289270\">simple</span>\
  \ <span m=\"4290650\">given</span> <span m=\"4291040\">what</span> <span m=\"4291220\"\
  >we've</span> <span m=\"4291400\">discussed</span> <span m=\"4291820\">so</span>\
  \ <span m=\"4291970\">far,</span> <span m=\"4292510\">relating--</span> <span m=\"\
  4293350\">so</span> <span m=\"4293500\">there</span> <span m=\"4293620\">was</span>\
  \ <span m=\"4293740\">this</span> <span m=\"4294310\">spectral</span> <span m=\"\
  4294790\">characterization</span> <span m=\"4295540\">up</span> <span m=\"4295690\"\
  >there</span> <span m=\"4296080\">of</span> <span m=\"4296620\">the</span> <span\
  \ m=\"4296740\">top</span> <span m=\"4297040\">eigenvalue.</span> <span m=\"4300810\"\
  >So</span> <span m=\"4301410\">we</span> <span m=\"4301620\">can</span> <span m=\"\
  4301800\">let</span> <span m=\"4302960\">J</span> <span m=\"4303810\">be</span>\
  \ <span m=\"4304020\">the</span> <span m=\"4304560\">all-ones</span> <span m=\"\
  4305070\">matrix.</span> <span m=\"4310722\">So</span> <span m=\"4311190\">let</span>\
  \ <span m=\"4311360\">J be</span> <span m=\"4311720\">the</span> <span m=\"4311840\"\
  >all-ones</span> <span m=\"4312170\">matrix.</span></p><p><span m=\"4313460\">And</span>\
  \ <span m=\"4315260\">we</span> <span m=\"4315380\">know</span> <span m=\"4315620\"\
  >that</span> <span m=\"4316680\">the</span> <span m=\"4316970\">all-ones</span>\
  \ <span m=\"4317510\">vector</span> <span m=\"4318980\">is</span> <span m=\"4319430\"\
  >an</span> <span m=\"4319580\">eigenvector</span> <span m=\"4323630\">of</span>\
  \ <span m=\"4323900\">the</span> <span m=\"4324080\">adjacency</span> <span m=\"\
  4324590\">matrix</span> <span m=\"4325010\">of</span> <span m=\"4325130\">G</span>\
  \ <span m=\"4326870\">with</span> <span m=\"4327200\">eigenvalue</span> <span m=\"\
  4328320\">d.</span> <span m=\"4330920\">So</span> <span m=\"4332340\">the</span>\
  \ <span m=\"4332990\">eigendecomposition</span> <span m=\"4334160\">of</span> <span\
  \ m=\"4334580\">J</span> <span m=\"4335390\">is</span> <span m=\"4335540\">also</span>\
  \ <span m=\"4335930\">the</span> <span m=\"4336080\">all-ones</span> <span m=\"\
  4336410\">vector</span> <span m=\"4336860\">and</span> <span m=\"4337010\">its</span>\
  \ <span m=\"4337160\">complement.</span> <span m=\"4338460\">So</span> <span m=\"\
  4338930\">we</span> <span m=\"4339470\">now</span> <span m=\"4339800\">see</span>\
  \ <span m=\"4340160\">that</span> <span m=\"4342870\">A</span> <span m=\"4343350\"\
  >sub</span> <span m=\"4343620\">G</span> <span m=\"4344130\">minus</span> <span\
  \ m=\"4345600\">d</span> <span m=\"4345810\">over</span> <span m=\"4346260\">nJ</span>\
  \ <span m=\"4348690\">has</span> <span m=\"4349110\">the</span> <span m=\"4349230\"\
  >same</span> <span m=\"4352470\">eigenvectors</span> <span m=\"4355660\">as</span>\
  \ <span m=\"4357270\">AG.</span></p><p><span m=\"4359400\">So</span> <span m=\"\
  4359960\">you</span> <span m=\"4360080\">can</span> <span m=\"4360230\">choose</span>\
  \ <span m=\"4360590\">the</span> <span m=\"4360710\">eigenvectors</span> <span m=\"\
  4361270\">for</span> <span m=\"4361370\">that.</span> <span m=\"4361990\">It's</span>\
  \ <span m=\"4362210\">the</span> <span m=\"4362300\">same</span> <span m=\"4362720\"\
  >set</span> <span m=\"4362960\">of</span> <span m=\"4363030\">eigenvectors.</span>\
  \ <span m=\"4364400\">Of</span> <span m=\"4364490\">course,</span> <span m=\"4364670\"\
  >we</span> <span m=\"4364850\">consider</span> <span m=\"4365360\">this</span> <span\
  \ m=\"4365570\">quantity</span> <span m=\"4365960\">here,</span> <span m=\"4366200\"\
  >because</span> <span m=\"4366530\">this</span> <span m=\"4366680\">is</span> <span\
  \ m=\"4366830\">exactly</span> <span m=\"4367250\">the</span> <span m=\"4367340\"\
  >quantity</span> <span m=\"4367730\">that</span> <span m=\"4367850\">comes</span>\
  \ <span m=\"4368210\">up</span> <span m=\"4369080\">in</span> <span m=\"4369200\"\
  >this</span> <span m=\"4369380\">expression</span> <span m=\"4371040\">once</span>\
  \ <span m=\"4371250\">we</span> <span m=\"4371400\">hit</span> <span m=\"4371580\"\
  >it</span> <span m=\"4371700\">by</span> <span m=\"4372120\">characteristic</span>\
  \ <span m=\"4372750\">vectors</span> <span m=\"4373530\">of</span> <span m=\"4374280\"\
  >subsets</span> <span m=\"4374940\">from</span> <span m=\"4375510\">left</span>\
  \ <span m=\"4375870\">and</span> <span m=\"4376020\">right.</span> <span m=\"4376817\"\
  >All</span> <span m=\"4377294\">right.</span></p><p><span m=\"4382070\">So</span>\
  \ <span m=\"4385880\">what</span> <span m=\"4386060\">are</span> <span m=\"4386120\"\
  >the</span> <span m=\"4386240\">eigenvalues?</span> <span m=\"4394700\">So</span>\
  \ <span m=\"4394970\">A</span> <span m=\"4395240\">previously</span> <span m=\"\
  4395880\">had</span> <span m=\"4396140\">eigenvalues</span> <span m=\"4396850\"\
  >lambda</span> <span m=\"4397190\">1</span> <span m=\"4397430\">through</span> <span\
  \ m=\"4397610\">lambda</span> <span m=\"4398090\">n.</span> <span m=\"4398780\"\
  >But</span> <span m=\"4399200\">now</span> <span m=\"4399350\">the</span> <span\
  \ m=\"4399440\">top</span> <span m=\"4399740\">one</span> <span m=\"4400580\">gets</span>\
  \ <span m=\"4400880\">chopped</span> <span m=\"4401270\">down</span> <span m=\"\
  4402560\">to</span> <span m=\"4402770\">0.</span></p><p><span m=\"4411110\">So</span>\
  \ <span m=\"4411310\">you</span> <span m=\"4411400\">can</span> <span m=\"4411550\"\
  >check</span> <span m=\"4411760\">this</span> <span m=\"4411910\">explicitly.</span>\
  \ <span m=\"4412970\">So</span> <span m=\"4413020\">you</span> <span m=\"4413080\"\
  >can</span> <span m=\"4413230\">check</span> <span m=\"4413430\">this</span> <span\
  \ m=\"4413560\">explicitly</span> <span m=\"4414310\">by</span> <span m=\"4414520\"\
  >checking</span> <span m=\"4417370\">that</span> <span m=\"4418800\">if</span> <span\
  \ m=\"4418960\">you</span> <span m=\"4420540\">take</span> <span m=\"4420750\">this</span>\
  \ <span m=\"4420930\">matrix</span> <span m=\"4422780\">multiplied</span> <span\
  \ m=\"4423210\">by</span> <span m=\"4423360\">the</span> <span m=\"4423450\">all-ones</span>\
  \ <span m=\"4423840\">vector,</span> <span m=\"4424920\">you</span> <span m=\"4425040\"\
  >get</span> <span m=\"4425850\">0.</span> <span m=\"4427170\">And</span> <span m=\"\
  4428160\">if</span> <span m=\"4430610\">you</span> <span m=\"4430730\">have</span>\
  \ <span m=\"4430940\">a</span> <span m=\"4431100\">eigenvector-eigenvalue</span>\
  \ <span m=\"4432350\">pair,</span> <span m=\"4434400\">then</span> <span m=\"4435090\"\
  >hitting</span> <span m=\"4435420\">this</span> <span m=\"4437850\">by</span> <span\
  \ m=\"4438240\">any</span> <span m=\"4438450\">of</span> <span m=\"4438540\">the</span>\
  \ <span m=\"4438660\">other</span> <span m=\"4438870\">ones</span> <span m=\"4440740\"\
  >gets</span> <span m=\"4441000\">you</span> <span m=\"4441900\">the</span> <span\
  \ m=\"4441990\">same</span> <span m=\"4442245\">as</span> <span m=\"4442500\">in</span>\
  \ <span m=\"4442680\">A,</span> <span m=\"4443040\">because</span> <span m=\"4446700\"\
  >you</span> <span m=\"4446820\">have</span> <span m=\"4447150\">this</span> <span\
  \ m=\"4447470\">orthogonality</span> <span m=\"4448080\">condition.</span> <span\
  \ m=\"4448530\">All</span> <span m=\"4448620\">the</span> <span m=\"4448740\">other</span>\
  \ <span m=\"4448920\">eigenvectors</span> <span m=\"4449520\">are</span> <span m=\"\
  4449580\">orthogonal</span> <span m=\"4450060\">to</span> <span m=\"4450180\">the</span>\
  \ <span m=\"4450270\">all-ones</span> <span m=\"4450660\">vector.</span></p><p><span\
  \ m=\"4453410\">All</span> <span m=\"4453500\">right.</span> <span m=\"4454190\"\
  >So</span> <span m=\"4454310\">now</span> <span m=\"4454670\">we</span> <span m=\"\
  4454940\">apply</span> <span m=\"4455450\">the</span> <span m=\"4455840\">Courant-Fischer</span>\
  \ <span m=\"4457130\">criteria,</span> <span m=\"4460980\">which</span> <span m=\"\
  4461130\">tells</span> <span m=\"4461460\">us</span> <span m=\"4462450\">that</span>\
  \ <span m=\"4463800\">the</span> <span m=\"4465400\">number</span> <span m=\"4466140\"\
  >in</span> <span m=\"4466300\">this</span> <span m=\"4466480\">discrepancy</span>\
  \ <span m=\"4467500\">quantity,</span> <span m=\"4474090\">which</span> <span m=\"\
  4474270\">we</span> <span m=\"4474450\">can</span> <span m=\"4474930\">write</span>\
  \ <span m=\"4476190\">in</span> <span m=\"4476340\">terms</span> <span m=\"4476670\"\
  >of</span> <span m=\"4476820\">this</span> <span m=\"4477600\">matrix,</span> <span\
  \ m=\"4492090\">it</span> <span m=\"4492270\">is</span> <span m=\"4494310\">upper</span>\
  \ <span m=\"4494650\">bounded</span> <span m=\"4495370\">by</span> <span m=\"4497250\"\
  >the</span> <span m=\"4497610\">product</span> <span m=\"4498330\">of</span> <span\
  \ m=\"4498630\">the</span> <span m=\"4498930\">length</span> <span m=\"4499440\"\
  >of</span> <span m=\"4499560\">these</span> <span m=\"4499740\">two</span> <span\
  \ m=\"4499920\">vectors,</span> <span m=\"4501330\">x</span> <span m=\"4501540\"\
  >and</span> <span m=\"4501630\">y,</span> <span m=\"4502400\">multiplied</span>\
  \ <span m=\"4502920\">by</span> <span m=\"4503850\">the</span> <span m=\"4504000\"\
  >spectral</span> <span m=\"4504540\">norm.</span> <span m=\"4513570\">So</span>\
  \ <span m=\"4513740\">I'm</span> <span m=\"4514680\">not</span> <span m=\"4514950\"\
  >quite</span> <span m=\"4515220\">using</span> <span m=\"4515520\">the</span> <span\
  \ m=\"4515610\">version</span> <span m=\"4515940\">up</span> <span m=\"4516060\"\
  >there,</span> <span m=\"4516270\">but</span> <span m=\"4516840\">I'm</span> <span\
  \ m=\"4516960\">using</span> <span m=\"4517500\">the</span> <span m=\"4517740\"\
  >spectral</span> <span m=\"4518190\">norm</span> <span m=\"4518430\">version,</span>\
  \ <span m=\"4518760\">which</span> <span m=\"4518970\">we</span> <span m=\"4519120\"\
  >discussed</span> <span m=\"4519540\">last</span> <span m=\"4519750\">time.</span>\
  \ <span m=\"4520060\">It's</span> <span m=\"4520380\">essentially</span> <span m=\"\
  4520860\">the</span> <span m=\"4520960\">one</span> <span m=\"4521220\">up</span>\
  \ <span m=\"4521310\">there,</span> <span m=\"4521510\">but</span> <span m=\"4521610\"\
  >you</span> <span m=\"4521740\">allow</span> <span m=\"4522570\">not</span> <span\
  \ m=\"4522810\">just</span> <span m=\"4522850\">single</span> <span m=\"4523230\"\
  >x but</span> <span m=\"4523620\">x</span> <span m=\"4523860\">and</span> <span\
  \ m=\"4524010\">y.</span> <span m=\"4524970\">And</span> <span m=\"4525420\">that</span>\
  \ <span m=\"4525630\">corresponds</span> <span m=\"4526200\">to</span> <span m=\"\
  4526500\">the</span> <span m=\"4526680\">largest</span> <span m=\"4527210\">eigenvalue</span>\
  \ <span m=\"4528000\">in</span> <span m=\"4528240\">absolute</span> <span m=\"4528690\"\
  >value,</span> <span m=\"4530990\">which</span> <span m=\"4531160\">we</span> <span\
  \ m=\"4531760\">see</span> <span m=\"4532030\">that. It's at</span> <span m=\"4532390\"\
  >most</span> <span m=\"4532810\">lambda.</span> <span m=\"4534650\">So</span> <span\
  \ m=\"4535480\">at</span> <span m=\"4535750\">most</span> <span m=\"4536350\">lambda</span>\
  \ <span m=\"4537070\">times</span> <span m=\"4538510\">size</span> <span m=\"4538810\"\
  >of</span> <span m=\"4538900\">x,</span> <span m=\"4539620\">size</span> <span m=\"\
  4539920\">of</span> <span m=\"4540010\">y</span> <span m=\"4542058\">square root.</span></p><p><span\
  \ m=\"4545800\">And</span> <span m=\"4546420\">that</span> <span m=\"4546830\">finishes</span>\
  \ <span m=\"4547130\">the</span> <span m=\"4547220\">proof</span> <span m=\"4549080\"\
  >of</span> <span m=\"4549200\">the</span> <span m=\"4549290\">expander</span> <span\
  \ m=\"4549740\">mixing</span> <span m=\"4550040\">lemma.</span> <span m=\"4554790\"\
  >So</span> <span m=\"4554940\">the</span> <span m=\"4555510\">moral</span> <span\
  \ m=\"4555870\">here</span> <span m=\"4556100\">is</span> <span m=\"4556290\">that,</span>\
  \ <span m=\"4557310\">just</span> <span m=\"4557580\">like</span> <span m=\"4557850\"\
  >what</span> <span m=\"4558030\">we</span> <span m=\"4558150\">saw</span> <span\
  \ m=\"4558390\">earlier</span> <span m=\"4559170\">in</span> <span m=\"4559300\"\
  >the</span> <span m=\"4559500\">dense</span> <span m=\"4559740\">case</span> <span\
  \ m=\"4560550\">but</span> <span m=\"4560790\">for</span> <span m=\"4561480\">any</span>\
  \ <span m=\"4561690\">parameters--</span> <span m=\"4562570\">so</span> <span m=\"\
  4562740\">here,</span> <span m=\"4563470\">it's</span> <span m=\"4563700\">a</span>\
  \ <span m=\"4563730\">very</span> <span m=\"4563940\">clean</span> <span m=\"4564270\"\
  >statement.</span> <span m=\"4565290\">You</span> <span m=\"4565410\">can</span>\
  \ <span m=\"4565620\">even</span> <span m=\"4565890\">have</span> <span m=\"4566160\"\
  >done</span> <span m=\"4566450\">the</span> <span m=\"4566550\">degree</span> <span\
  \ m=\"4566850\">graphs.</span> <span m=\"4567710\">d</span> <span m=\"4567800\"\
  >could</span> <span m=\"4567950\">be</span> <span m=\"4568610\">a</span> <span m=\"\
  4569130\">constant.</span> <span m=\"4571110\">If</span> <span m=\"4571600\">lambda\
  \ is</span> <span m=\"4572090\">small</span> <span m=\"4572570\">compared</span>\
  \ <span m=\"4573020\">to</span> <span m=\"4573250\">d,</span> <span m=\"4574130\"\
  >then</span> <span m=\"4575710\">you</span> <span m=\"4575830\">have</span> <span\
  \ m=\"4576040\">this</span> <span m=\"4576220\">discrepancy</span> <span m=\"4576820\"\
  >condition.</span></p><p><span m=\"4578250\">And</span> <span m=\"4578350\">the</span>\
  \ <span m=\"4578440\">reason</span> <span m=\"4578710\">why</span> <span m=\"4578890\"\
  >this</span> <span m=\"4579040\">is</span> <span m=\"4579130\">called</span> <span\
  \ m=\"4579310\">an</span> <span m=\"4579440\">expander</span> <span m=\"4579970\"\
  >mixing</span> <span m=\"4580360\">lemma</span> <span m=\"4581080\">is</span> <span\
  \ m=\"4581290\">that</span> <span m=\"4581800\">there's</span> <span m=\"4581980\"\
  >this</span> <span m=\"4582100\">notion</span> <span m=\"4582490\">of</span> <span\
  \ m=\"4583240\">expanders,</span> <span m=\"4584020\">which</span> <span m=\"4584260\"\
  >is</span> <span m=\"4584980\">not</span> <span m=\"4585280\">quite</span> <span\
  \ m=\"4585640\">the</span> <span m=\"4585730\">same</span> <span m=\"4586060\">but</span>\
  \ <span m=\"4586210\">very</span> <span m=\"4586420\">intimately</span> <span m=\"\
  4586930\">related</span> <span m=\"4587380\">to</span> <span m=\"4587620\">pseudorandom</span>\
  \ <span m=\"4588250\">graphs.</span> <span m=\"4589300\">So</span> <span m=\"4589540\"\
  >one</span> <span m=\"4589900\">property</span> <span m=\"4590440\">of</span> <span\
  \ m=\"4590530\">pseudorandom</span> <span m=\"4591100\">graphs</span> <span m=\"\
  4591460\">that</span> <span m=\"4591610\">is</span> <span m=\"4591760\">quite</span>\
  \ <span m=\"4592030\">useful--</span> <span m=\"4593020\">in</span> <span m=\"4593110\"\
  >particular,</span> <span m=\"4593560\">in</span> <span m=\"4593620\">computer</span>\
  \ <span m=\"4593980\">science--</span> <span m=\"4594780\">is</span> <span m=\"\
  4594880\">that</span> <span m=\"4594910\">if</span> <span m=\"4595000\">you</span>\
  \ <span m=\"4595060\">take</span> <span m=\"4595240\">a</span> <span m=\"4595300\"\
  >small</span> <span m=\"4595630\">subset</span> <span m=\"4596080\">of</span> <span\
  \ m=\"4596140\">vertices,</span> <span m=\"4596650\">it</span> <span m=\"4596740\"\
  >has</span> <span m=\"4597070\">lots</span> <span m=\"4597310\">of</span> <span\
  \ m=\"4597430\">neighbors.</span> <span m=\"4598480\">So</span> <span m=\"4598690\"\
  >the</span> <span m=\"4598780\">graph</span> <span m=\"4599070\">is</span> <span\
  \ m=\"4599170\">now</span> <span m=\"4599440\">somehow</span> <span m=\"4600070\"\
  >clustered</span> <span m=\"4600640\">into</span> <span m=\"4601090\">a</span> <span\
  \ m=\"4601150\">few</span> <span m=\"4601870\">local</span> <span m=\"4602170\"\
  >pieces.</span> <span m=\"4602830\">So</span> <span m=\"4603010\">there's</span>\
  \ <span m=\"4603240\">lots</span> <span m=\"4603460\">of</span> <span m=\"4603550\"\
  >expansion.</span></p><p><span m=\"4605790\">And</span> <span m=\"4608130\">that's</span>\
  \ <span m=\"4608400\">something</span> <span m=\"4608850\">that</span> <span m=\"\
  4609030\">you</span> <span m=\"4609150\">can</span> <span m=\"4609390\">guarantee</span>\
  \ <span m=\"4610140\">using</span> <span m=\"4611330\">the</span> <span m=\"4611490\"\
  >expander</span> <span m=\"4611940\">mixing</span> <span m=\"4612270\">lemma,</span>\
  \ <span m=\"4612670\">that</span> <span m=\"4612870\">you</span> <span m=\"4612990\"\
  >have</span> <span m=\"4613650\">lots</span> <span m=\"4613920\">of--</span> <span\
  \ m=\"4614040\">you</span> <span m=\"4614130\">take</span> <span m=\"4614310\">a</span>\
  \ <span m=\"4614370\">small</span> <span m=\"4614640\">subset</span> <span m=\"\
  4615060\">of</span> <span m=\"4615120\">vertices.</span> <span m=\"4616080\">You</span>\
  \ <span m=\"4616170\">can</span> <span m=\"4616530\">expand</span> <span m=\"4617100\"\
  >outward.</span> <span m=\"4618510\">So</span> <span m=\"4618860\">graphs</span>\
  \ <span m=\"4619280\">with</span> <span m=\"4619490\">that</span> <span m=\"4619700\"\
  >specific</span> <span m=\"4620180\">property,</span> <span m=\"4620990\">taking</span>\
  \ <span m=\"4621230\">a</span> <span m=\"4621260\">small</span> <span m=\"4621560\"\
  >subset</span> <span m=\"4621950\">of</span> <span m=\"4622010\">vertices</span>\
  \ <span m=\"4622490\">always</span> <span m=\"4623060\">gets</span> <span m=\"4623300\"\
  >you</span> <span m=\"4623390\">lots</span> <span m=\"4623660\">of</span> <span\
  \ m=\"4623750\">neighbors,</span> <span m=\"4624440\">are</span> <span m=\"4624530\"\
  >called</span> <span m=\"4624760\">expander</span> <span m=\"4625370\">graphs.</span>\
  \ <span m=\"4626030\">And</span> <span m=\"4626120\">these</span> <span m=\"4626330\"\
  >graphs</span> <span m=\"4626690\">play</span> <span m=\"4626995\">an</span> <span\
  \ m=\"4627300\">important</span> <span m=\"4627710\">role,</span> <span m=\"4628630\"\
  >in</span> <span m=\"4629510\">particular,</span> <span m=\"4629960\">in</span>\
  \ <span m=\"4630050\">computer</span> <span m=\"4630410\">science</span> <span m=\"\
  4631130\">in</span> <span m=\"4631220\">designing</span> <span m=\"4631730\">algorithms</span>\
  \ <span m=\"4632360\">and</span> <span m=\"4632620\">proving</span> <span m=\"4632780\"\
  >complexity</span> <span m=\"4633380\">results</span> <span m=\"4633960\">and</span>\
  \ <span m=\"4633980\">so</span> <span m=\"4634190\">on</span> <span m=\"4634550\"\
  >but</span> <span m=\"4634670\">also</span> <span m=\"4634940\">play</span> <span\
  \ m=\"4635210\">important</span> <span m=\"4635600\">roles</span> <span m=\"4635840\"\
  >in</span> <span m=\"4635930\">graph</span> <span m=\"4636200\">theory</span> <span\
  \ m=\"4636470\">and</span> <span m=\"4636560\">combinatorics.</span></p><p><span\
  \ m=\"4640330\">Well,</span> <span m=\"4640720\">next</span> <span m=\"4641020\"\
  >time,</span> <span m=\"4641200\">we'll</span> <span m=\"4641440\">address</span>\
  \ <span m=\"4642010\">a</span> <span m=\"4642070\">few</span> <span m=\"4642340\"\
  >questions</span> <span m=\"4643690\">which</span> <span m=\"4644890\">are</span>\
  \ <span m=\"4645070\">along</span> <span m=\"4645310\">the</span> <span m=\"4645400\"\
  >lines</span> <span m=\"4645760\">of,</span> <span m=\"4646420\">one,</span> <span\
  \ m=\"4647140\">how</span> <span m=\"4647560\">small</span> <span m=\"4648220\"\
  >can</span> <span m=\"4648520\">lambda</span> <span m=\"4649000\">be</span> <span\
  \ m=\"4649990\">as</span> <span m=\"4650110\">a</span> <span m=\"4650170\">function</span>\
  \ <span m=\"4650620\">of</span> <span m=\"4650740\">d?</span> <span m=\"4653730\"\
  >So</span> <span m=\"4654060\">here</span> <span m=\"4654210\">is</span> <span m=\"\
  4654400\">this.</span> <span m=\"4654570\">If</span> <span m=\"4654690\">lambda's</span>\
  \ <span m=\"4655020\">small</span> <span m=\"4655410\">compared</span> <span m=\"\
  4655740\">to</span> <span m=\"4655860\">d,</span> <span m=\"4656460\">then</span>\
  \ <span m=\"4656760\">you</span> <span m=\"4656880\">have</span> <span m=\"4657360\"\
  >this</span> <span m=\"4657600\">discrepancy.</span> <span m=\"4658500\">But</span>\
  \ <span m=\"4660480\">if</span> <span m=\"4660710\">d</span> <span m=\"4661110\"\
  >is,</span> <span m=\"4662220\">let's</span> <span m=\"4662370\">say,</span> <span\
  \ m=\"4662580\">a</span> <span m=\"4662640\">million,</span> <span m=\"4663480\"\
  >how</span> <span m=\"4663780\">small</span> <span m=\"4664200\">can</span> <span\
  \ m=\"4664410\">lambda</span> <span m=\"4664770\">be?</span> <span m=\"4666120\"\
  >That's</span> <span m=\"4666270\">one</span> <span m=\"4666450\">question.</span></p><p><span\
  \ m=\"4667980\">Another</span> <span m=\"4668250\">question</span> <span m=\"4668670\"\
  >is,</span> <span m=\"4669960\">considering</span> <span m=\"4670850\">everything</span>\
  \ <span m=\"4672000\">that</span> <span m=\"4672150\">we've</span> <span m=\"4672390\"\
  >said</span> <span m=\"4672780\">so</span> <span m=\"4673050\">far,</span> <span\
  \ m=\"4673290\">what</span> <span m=\"4674100\">can</span> <span m=\"4674550\">we</span>\
  \ <span m=\"4674790\">say</span> <span m=\"4675810\">about,</span> <span m=\"4679720\"\
  >let's</span> <span m=\"4679930\">say,</span> <span m=\"4681700\">the</span> <span\
  \ m=\"4681940\">relationship</span> <span m=\"4682570\">between</span> <span m=\"\
  4682870\">some</span> <span m=\"4683110\">of</span> <span m=\"4683170\">these</span>\
  \ <span m=\"4684550\">conditions</span> <span m=\"4685990\">for</span> <span m=\"\
  4686350\">sparse</span> <span m=\"4686950\">graphs</span> <span m=\"4687580\">but</span>\
  \ <span m=\"4688210\">that</span> <span m=\"4688420\">are</span> <span m=\"4688540\"\
  >somewhat</span> <span m=\"4688900\">special--</span> <span m=\"4689350\">for</span>\
  \ <span m=\"4689530\">example,</span> <span m=\"4690300\">kd</span> <span m=\"4690670\"\
  >graphs</span> <span m=\"4691360\">or</span> <span m=\"4692140\">vertex-transitive</span>\
  \ <span m=\"4693010\">graphs?</span> <span m=\"4693970\">And it</span> <span m=\"\
  4694240\">turns</span> <span m=\"4694450\">out</span> <span m=\"4694570\">some</span>\
  \ <span m=\"4694840\">of</span> <span m=\"4694930\">these</span> <span m=\"4695110\"\
  >relations</span> <span m=\"4695950\">are</span> <span m=\"4696040\">also</span>\
  \ <span m=\"4697000\">equivalent</span> <span m=\"4697480\">to</span> <span m=\"\
  4697630\">each</span> <span m=\"4697810\">other.</span></p>"
type: course
uid: 2fbfd677578d0da2087d81966abe8aff

---
None