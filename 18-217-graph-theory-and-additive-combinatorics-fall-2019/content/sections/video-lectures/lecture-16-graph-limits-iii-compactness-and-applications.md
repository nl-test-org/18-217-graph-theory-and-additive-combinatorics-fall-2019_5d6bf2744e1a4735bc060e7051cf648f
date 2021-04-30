---
about_this_resource_text: <p><strong>Description:</strong> Continuing the discussion
  of graph limits, Professor Zhao proves the compactness of the space of graphons
  and discusses its consequences, such as the equivalence of convergence notions for
  graph sequences.</p> <p><strong>Instructor:</strong> Yufei Zhao</p>
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: nCWwhF0TkVI
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  title: Video-YouTube-Stream
  type: Video
  uid: dc47404282a02f704bd4d2b3a3d4a836
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/nCWwhF0TkVI/default.jpg
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3b83ff4686ee561fe8eb03a15231115e
- id: 3Play-3PlayYouTubeid-MP4
  media_location: nCWwhF0TkVI
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 288768262819064b53b151c7caafa19c
- id: nCWwhF0TkVI.srt
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-16-graph-limits-iii-compactness-and-applications/nCWwhF0TkVI.srt
  title: 3play caption file
  type: null
  uid: 1b776f855fd9c2b91997ca06226ae865
- id: nCWwhF0TkVI.pdf
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-16-graph-limits-iii-compactness-and-applications/nCWwhF0TkVI.pdf
  title: 3play pdf file
  type: null
  uid: dac589ce07a112610c2fc6da2b2653bf
- id: Caption-3Play YouTube id-SRT
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f0e9e9fbbecd0ed0ae4e959912647f7a
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 5184f3e97d7cb98b89626958d651a093
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec16_300k.mp4
  parent_uid: 0031a0d091af8db0e3f325c0a2be7582
  title: Video-Internet Archive-MP4
  type: Video
  uid: 522925cc90ddfe6cf2ad732d63edb3a9
inline_embed_id: 88892234lecture16graphlimitsiiicompactnessandapplications82334122
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-16-graph-limits-iii-compactness-and-applications
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-16-graph-limits-iii-compactness-and-applications
template_type: Tabbed
title: "Lecture 16: Graph Limits III: Compactness and Applications \t"
transcript: "<p><span m=\"18670\">YUFEI ZHAO:</span> <span m=\"18735\">So</span> <span\
  \ m=\"18800\">we've</span> <span m=\"18920\">been</span> <span m=\"19040\">discussing</span>\
  \ <span m=\"19550\">graph</span> <span m=\"19850\">limits</span> <span m=\"20240\"\
  >for</span> <span m=\"20420\">a</span> <span m=\"20450\">couple of</span> <span\
  \ m=\"20750\">lecturers</span> <span m=\"21170\">now.</span> <span m=\"21790\">In</span>\
  \ <span m=\"21920\">the</span> <span m=\"22010\">first</span> <span m=\"22310\"\
  >lecture</span> <span m=\"22910\">on</span> <span m=\"23030\">graph</span> <span\
  \ m=\"23300\">limits,</span> <span m=\"23970\">so</span> <span m=\"24200\">two</span>\
  \ <span m=\"24380\">lectures</span> <span m=\"24620\">ago,</span> <span m=\"25340\"\
  >I</span> <span m=\"25550\">stated</span> <span m=\"26090\">a</span> <span m=\"\
  26150\">number</span> <span m=\"26540\">of</span> <span m=\"26900\">main</span>\
  \ <span m=\"27230\">theorems.</span> <span m=\"28340\">And</span> <span m=\"28550\"\
  >today,</span> <span m=\"29240\">we</span> <span m=\"29450\">will</span> <span m=\"\
  29660\">prove</span> <span m=\"29990\">these</span> <span m=\"30230\">theorems</span>\
  \ <span m=\"30830\">using</span> <span m=\"31610\">some</span> <span m=\"31880\"\
  >of</span> <span m=\"31940\">the</span> <span m=\"32030\">tools</span> <span m=\"\
  32390\">that</span> <span m=\"32479\">we</span> <span m=\"32600\">developed</span>\
  \ <span m=\"32960\">last</span> <span m=\"33200\">time,</span> <span m=\"33950\"\
  >namely</span> <span m=\"34310\">the</span> <span m=\"34460\">regularity</span>\
  \ <span m=\"34775\">lemma.</span> <span m=\"35720\">And</span> <span m=\"36770\"\
  >also</span> <span m=\"37100\">we</span> <span m=\"37280\">proved</span> <span m=\"\
  37580\">this</span> <span m=\"38490\">Martingale</span> <span m=\"39020\">convergence</span>\
  \ <span m=\"39620\">theorem,</span> <span m=\"40130\">which</span> <span m=\"40370\"\
  >will</span> <span m=\"40520\">also</span> <span m=\"40790\">come</span> <span m=\"\
  40970\">in.</span></p><p><span m=\"42800\">So</span> <span m=\"42920\">let</span>\
  \ <span m=\"43040\">me</span> <span m=\"43130\">recall</span> <span m=\"43970\"\
  >what</span> <span m=\"44120\">were</span> <span m=\"44240\">the</span> <span m=\"\
  44360\">three</span> <span m=\"44840\">main</span> <span m=\"45170\">theorems</span>\
  \ <span m=\"45650\">that</span> <span m=\"45770\">we</span> <span m=\"45920\">stated</span>\
  \ <span m=\"46340\">at</span> <span m=\"46430\">the</span> <span m=\"46890\">end</span>\
  \ <span m=\"47120\">of</span> <span m=\"47660\">two</span> <span m=\"47870\">lectures</span>\
  \ <span m=\"48230\">ago.</span> <span m=\"49160\">So</span> <span m=\"49280\">one</span>\
  \ <span m=\"49460\">of</span> <span m=\"49550\">them</span> <span m=\"49730\">was</span>\
  \ <span m=\"50000\">the</span> <span m=\"50150\">equivalence</span> <span m=\"51080\"\
  >of</span> <span m=\"51260\">convergence.</span> <span m=\"53150\">On</span> <span\
  \ m=\"53240\">one</span> <span m=\"53420\">hand,</span> <span m=\"53910\">we</span>\
  \ <span m=\"53960\">defined</span> <span m=\"54870\">a</span> <span m=\"54920\"\
  >notion</span> <span m=\"55340\">of</span> <span m=\"55430\">convergence</span>\
  \ <span m=\"56570\">where</span> <span m=\"56780\">we</span> <span m=\"56930\">say</span>\
  \ <span m=\"57980\">that</span> <span m=\"58220\">Wn</span> <span m=\"59360\">approaches</span>\
  \ <span m=\"60140\">W,</span> <span m=\"61550\">by</span> <span m=\"61730\">definition,</span>\
  \ <span m=\"64190\">if</span> <span m=\"66970\">the</span> <span m=\"67540\">F</span>\
  \ <span m=\"67750\">densities</span> <span m=\"69010\">converge.</span> <span m=\"\
  75390\">We</span> <span m=\"75410\">can</span> <span m=\"75560\">say</span> <span\
  \ m=\"75740\">convergence</span> <span m=\"76310\">even</span> <span m=\"76550\"\
  >without</span> <span m=\"76940\">a</span> <span m=\"77000\">limit</span> <span\
  \ m=\"77300\">in</span> <span m=\"77420\">mind,</span> <span m=\"77780\">where</span>\
  \ <span m=\"77930\">we</span> <span m=\"78110\">see</span> <span m=\"78350\">a</span>\
  \ <span m=\"78410\">sequence</span> <span m=\"78890\">converges</span> <span m=\"\
  79910\">if</span> <span m=\"81350\">all</span> <span m=\"81530\">of</span> <span\
  \ m=\"81680\">these</span> <span m=\"82400\">F</span> <span m=\"82640\">densities</span>\
  \ <span m=\"83240\">converge.</span> <span m=\"85400\">So</span> <span m=\"85580\"\
  >the</span> <span m=\"85670\">first</span> <span m=\"86270\">main</span> <span m=\"\
  86510\">theorem</span> <span m=\"86810\">was</span> <span m=\"87020\">that</span>\
  \ <span m=\"87200\">the</span> <span m=\"87320\">two</span> <span m=\"87590\">notions</span>\
  \ <span m=\"88040\">of</span> <span m=\"88670\">convergence</span> <span m=\"90680\"\
  >are</span> <span m=\"91490\">equivalent,</span> <span m=\"92150\">so</span> <span\
  \ m=\"92330\">one</span> <span m=\"92660\">notion</span> <span m=\"93110\">being</span>\
  \ <span m=\"93680\">convergence</span> <span m=\"94280\">in</span> <span m=\"94400\"\
  >terms</span> <span m=\"94730\">of</span> <span m=\"95480\">F</span> <span m=\"\
  95870\">densities,</span> <span m=\"97160\">and</span> <span m=\"97290\">the</span>\
  \ <span m=\"97350\">second</span> <span m=\"97670\">notion</span> <span m=\"98120\"\
  >being</span> <span m=\"98420\">convergence</span> <span m=\"99320\">in</span> <span\
  \ m=\"99560\">the</span> <span m=\"99680\">sense</span> <span m=\"100400\">of</span>\
  \ <span m=\"101680\">the</span> <span m=\"101780\">cut</span> <span m=\"102050\"\
  >norm,</span> <span m=\"103106\">the</span> <span m=\"103470\">cut</span> <span\
  \ m=\"103720\">distance.</span></p><p><span m=\"106500\">There</span> <span m=\"\
  106620\">was</span> <span m=\"106720\">a</span> <span m=\"106780\">second</span>\
  \ <span m=\"107080\">term</span> <span m=\"107440\">that</span> <span m=\"107590\"\
  >tells</span> <span m=\"107920\">us</span> <span m=\"108130\">that</span> <span\
  \ m=\"108260\">limits</span> <span m=\"108730\">always</span> <span m=\"109150\"\
  >exist.</span> <span m=\"111700\">If</span> <span m=\"111820\">you</span> <span\
  \ m=\"111910\">have</span> <span m=\"112030\">a</span> <span m=\"112060\">convergent</span>\
  \ <span m=\"112630\">sequence,</span> <span m=\"113650\">then</span> <span m=\"\
  114460\">you</span> <span m=\"114580\">can</span> <span m=\"114760\">represent</span>\
  \ <span m=\"115570\">a</span> <span m=\"115690\">limit</span> <span m=\"116260\"\
  >by</span> <span m=\"116470\">a</span> <span m=\"116590\">graphon.</span> <span\
  \ m=\"118730\">And</span> <span m=\"118900\">the</span> <span m=\"119020\">third</span>\
  \ <span m=\"119320\">statement</span> <span m=\"119800\">was</span> <span m=\"120160\"\
  >about</span> <span m=\"120370\">compactness</span> <span m=\"121300\">of</span>\
  \ <span m=\"121420\">the</span> <span m=\"121540\">space</span> <span m=\"121900\"\
  >of</span> <span m=\"121990\">graphons.</span></p><p><span m=\"123580\">So</span>\
  \ <span m=\"123730\">we're</span> <span m=\"123890\">actually</span> <span m=\"\
  124090\">going</span> <span m=\"124210\">to</span> <span m=\"124350\">prove</span>\
  \ <span m=\"124840\">these</span> <span m=\"125050\">theorems</span> <span m=\"\
  125410\">in</span> <span m=\"125530\">reverse</span> <span m=\"125990\">order.</span>\
  \ <span m=\"126380\">We're going</span> <span m=\"126670\">to</span> <span m=\"\
  126880\">start</span> <span m=\"127140\">with</span> <span m=\"127300\">the</span>\
  \ <span m=\"127360\">compactness</span> <span m=\"128050\">and</span> <span m=\"\
  128169\">work</span> <span m=\"128350\">backwards.</span> <span m=\"129590\">So</span>\
  \ <span m=\"129610\">this</span> <span m=\"129759\">is</span> <span m=\"130240\"\
  >not</span> <span m=\"130539\">how</span> <span m=\"130900\">these</span> <span\
  \ m=\"131140\">theorems</span> <span m=\"131440\">were</span> <span m=\"131560\"\
  >originally</span> <span m=\"132100\">proved,</span> <span m=\"132640\">or</span>\
  \ <span m=\"132760\">not</span> <span m=\"133000\">in</span> <span m=\"133120\"\
  >that</span> <span m=\"133330\">order,</span> <span m=\"134000\">but</span> <span\
  \ m=\"134840\">it</span> <span m=\"134920\">will</span> <span m=\"135010\">be</span>\
  \ <span m=\"135160\">helpful</span> <span m=\"135610\">for</span> <span m=\"135790\"\
  >us</span> <span m=\"135910\">to</span> <span m=\"136000\">do</span> <span m=\"\
  136150\">this</span> <span m=\"137080\">by</span> <span m=\"137260\">first</span>\
  \ <span m=\"138010\">considering</span> <span m=\"138640\">the</span> <span m=\"\
  139000\">compactness</span> <span m=\"139690\">statement.</span></p><p><span m=\"\
  140950\">So</span> <span m=\"141100\">remember</span> <span m=\"141460\">we're</span>\
  \ <span m=\"141550\">compactness</span> <span m=\"142220\">says.</span> <span m=\"\
  143480\">I</span> <span m=\"143620\">start</span> <span m=\"144190\">with</span>\
  \ <span m=\"146450\">this</span> <span m=\"146960\">space</span> <span m=\"149070\"\
  >W</span> <span m=\"149480\">tilda,</span> <span m=\"150920\">which</span> <span\
  \ m=\"151310\">is</span> <span m=\"152450\">the</span> <span m=\"152570\">space</span>\
  \ <span m=\"152960\">of</span> <span m=\"153050\">graphons,</span> <span m=\"158490\"\
  >where</span> <span m=\"158940\">I</span> <span m=\"159080\">identify</span> <span\
  \ m=\"159730\">graphons</span> <span m=\"160330\">that</span> <span m=\"160450\"\
  >have</span> <span m=\"160660\">distance</span> <span m=\"161070\">0.</span> <span\
  \ m=\"171610\">So</span> <span m=\"171760\">if</span> <span m=\"171910\">they</span>\
  \ <span m=\"172030\">have</span> <span m=\"172150\">cut</span> <span m=\"172430\"\
  >distance</span> <span m=\"172750\">0,</span> <span m=\"173170\">then</span> <span\
  \ m=\"173380\">I</span> <span m=\"175180\">refer</span> <span m=\"175510\">to</span>\
  \ <span m=\"175600\">them</span> <span m=\"175780\">as</span> <span m=\"175900\"\
  >the</span> <span m=\"175960\">same</span> <span m=\"176200\">point.</span> <span\
  \ m=\"176680\">So</span> <span m=\"176830\">this</span> <span m=\"176980\">is</span>\
  \ <span m=\"177100\">now</span> <span m=\"177280\">a</span> <span m=\"177340\">metric</span>\
  \ <span m=\"177700\">space.</span> <span m=\"179360\">And</span> <span m=\"179510\"\
  >the</span> <span m=\"179600\">theorem</span> <span m=\"181490\">is</span> <span\
  \ m=\"181640\">that</span> <span m=\"181970\">this</span> <span m=\"182120\">space</span>\
  \ <span m=\"182480\">is</span> <span m=\"182690\">compact.</span></p><p><span m=\"\
  193890\">So</span> <span m=\"194040\">I</span> <span m=\"194100\">think this,</span>\
  \ <span m=\"195030\">it's</span> <span m=\"195210\">a</span> <span m=\"195240\"\
  >really</span> <span m=\"195510\">nice</span> <span m=\"195810\">theorem. It's</span>\
  \ <span m=\"196140\">a</span> <span m=\"196200\">beautiful</span> <span m=\"196620\"\
  >theorem</span> <span m=\"197220\">that</span> <span m=\"197610\">encapsulates</span>\
  \ <span m=\"198480\">a</span> <span m=\"198570\">lot</span> <span m=\"198900\">of</span>\
  \ <span m=\"198990\">what</span> <span m=\"199200\">we've</span> <span m=\"199350\"\
  >been</span> <span m=\"199530\">talking</span> <span m=\"199950\">about</span> <span\
  \ m=\"200190\">so</span> <span m=\"200400\">far</span> <span m=\"200940\">with</span>\
  \ <span m=\"201180\">similarities,</span> <span m=\"201720\">regularity,</span>\
  \ <span m=\"202480\">and</span> <span m=\"202660\">what</span> <span m=\"202850\"\
  >not,</span> <span m=\"203460\">in</span> <span m=\"203700\">a</span> <span m=\"\
  204470\">qualitatively</span> <span m=\"205500\">succinct</span> <span m=\"206400\"\
  >way,</span> <span m=\"207150\">just that</span> <span m=\"207480\">this</span>\
  \ <span m=\"207620\">space</span> <span m=\"208140\">of</span> <span m=\"208230\"\
  >graphons</span> <span m=\"208670\">is</span> <span m=\"208950\">compact.</span>\
  \ <span m=\"211080\">You</span> <span m=\"211200\">may</span> <span m=\"211320\"\
  >not</span> <span m=\"211500\">have</span> <span m=\"211650\">some</span> <span\
  \ m=\"212700\">intuition</span> <span m=\"213210\">about</span> <span m=\"213510\"\
  >what</span> <span m=\"213720\">the</span> <span m=\"213840\">space</span> <span\
  \ m=\"214170\">looks</span> <span m=\"214410\">like</span> <span m=\"214620\">at</span>\
  \ <span m=\"214710\">the</span> <span m=\"214800\">moment,</span> <span m=\"215490\"\
  >but</span> <span m=\"215730\">we'll</span> <span m=\"215940\">see</span> <span\
  \ m=\"216150\">the</span> <span m=\"216240\">proof</span> <span m=\"216480\">and</span>\
  \ <span m=\"216600\">hopefully</span> <span m=\"216930\">that</span> <span m=\"\
  217080\">will</span> <span m=\"217170\">give</span> <span m=\"217380\">you</span>\
  \ <span m=\"217470\">some</span> <span m=\"217600\">more</span> <span m=\"217770\"\
  >intuition</span></p><p><span m=\"219090\">I</span> <span m=\"219210\">first</span>\
  \ <span m=\"219570\">learned</span> <span m=\"219900\">about</span> <span m=\"220140\"\
  >this</span> <span m=\"220350\">theorem</span> <span m=\"221040\">when</span> <span\
  \ m=\"221910\">Laszlo</span> <span m=\"222230\">Lovasz,</span> <span m=\"222870\"\
  >who</span> <span m=\"223130\">was</span> <span m=\"223320\">one</span> <span m=\"\
  223500\">of</span> <span m=\"223560\">the</span> <span m=\"223680\">pioneers</span>\
  \ <span m=\"224280\">in</span> <span m=\"224370\">the</span> <span m=\"224460\"\
  >subject,</span> <span m=\"225240\">when</span> <span m=\"225450\">he</span> <span\
  \ m=\"225870\">came</span> <span m=\"226170\">to</span> <span m=\"226260\">MIT</span>\
  \ <span m=\"226650\">to</span> <span m=\"226740\">give</span> <span m=\"226920\"\
  >a</span> <span m=\"226950\">talk</span> <span m=\"227250\">when</span> <span m=\"\
  227370\">I</span> <span m=\"227430\">was</span> <span m=\"227550\">a</span> <span\
  \ m=\"227580\">graduate</span> <span m=\"227970\">student.</span> <span m=\"228840\"\
  >And</span> <span m=\"229170\">he</span> <span m=\"229350\">said</span> <span m=\"\
  229620\">that</span> <span m=\"231280\">analysts</span> <span m=\"232050\">thought\
  \ that</span> <span m=\"232530\">they</span> <span m=\"232890\">pretty</span> <span\
  \ m=\"233220\">much</span> <span m=\"233400\">knew</span> <span m=\"233910\">all</span>\
  \ <span m=\"234090\">the</span> <span m=\"234180\">naturally</span> <span m=\"234720\"\
  >occurring</span> <span m=\"235110\">compact</span> <span m=\"235680\">spaces</span>\
  \ <span m=\"236220\">out</span> <span m=\"236400\">there.</span> <span m=\"237140\"\
  >So</span> <span m=\"237360\">there</span> <span m=\"237510\">are</span> <span m=\"\
  237630\">lots</span> <span m=\"237930\">of</span> <span m=\"238380\">spaces</span>\
  \ <span m=\"238890\">that</span> <span m=\"239010\">occur</span> <span m=\"239230\"\
  >in</span> <span m=\"239450\">analysis</span> <span m=\"239940\">and</span> <span\
  \ m=\"240030\">topology</span> <span m=\"240570\">that</span> <span m=\"240780\"\
  >are</span> <span m=\"240960\">compact.</span></p><p><span m=\"241530\">I</span>\
  \ <span m=\"242030\">mean,</span> <span m=\"242130\">the</span> <span m=\"242220\"\
  >first</span> <span m=\"242520\">one</span> <span m=\"242790\">you</span> <span\
  \ m=\"242910\">learn</span> <span m=\"243600\">in</span> <span m=\"244140\">analysis</span>\
  \ <span m=\"245010\">undergraduate</span> <span m=\"245910\">is</span> <span m=\"\
  246060\">probably</span> <span m=\"246480\">that</span> <span m=\"246690\">an</span>\
  \ <span m=\"246780\">interval</span> <span m=\"247280\">is</span> <span m=\"247410\"\
  >compact.</span> <span m=\"248160\">But</span> <span m=\"248310\">there</span> <span\
  \ m=\"248430\">are</span> <span m=\"248460\">also</span> <span m=\"248760\">many</span>\
  \ <span m=\"249000\">other</span> <span m=\"249240\">spaces.</span> <span m=\"250590\"\
  >But</span> <span m=\"250830\">this</span> <span m=\"251010\">one</span> <span m=\"\
  251220\">here</span> <span m=\"251610\">doesn't</span> <span m=\"251940\">seem</span>\
  \ <span m=\"252390\">to</span> <span m=\"252630\">be</span> <span m=\"253290\">any</span>\
  \ <span m=\"253560\">of</span> <span m=\"253650\">these</span> <span m=\"253860\"\
  >classical</span> <span m=\"254430\">notions</span> <span m=\"255090\">of</span>\
  \ <span m=\"255240\">compactness.</span> <span m=\"256089\">So</span> <span m=\"\
  256290\">it's,</span> <span m=\"256500\">in</span> <span m=\"256620\">some</span>\
  \ <span m=\"256829\">sense,</span> <span m=\"257290\">a</span> <span m=\"258089\"\
  >new</span> <span m=\"258870\">compact</span> <span m=\"259500\">space.</span></p><p><span\
  \ m=\"262480\">So</span> <span m=\"262680\">let's</span> <span m=\"262830\">see</span>\
  \ <span m=\"262980\">how</span> <span m=\"263130\">the</span> <span m=\"263250\"\
  >proof</span> <span m=\"263550\">goes.</span> <span m=\"267520\">Now,</span> <span\
  \ m=\"267920\">because</span> <span m=\"268350\">we</span> <span m=\"268470\">are</span>\
  \ <span m=\"268560\">working</span> <span m=\"269400\">in</span> <span m=\"269970\"\
  >a</span> <span m=\"270120\">metric</span> <span m=\"270570\">space,</span> <span\
  \ m=\"272620\">it</span> <span m=\"272740\">suffices</span> <span m=\"273340\">to</span>\
  \ <span m=\"273430\">show,</span> <span m=\"279360\">due</span> <span m=\"279510\"\
  >to</span> <span m=\"279630\">the</span> <span m=\"279750\">equivalence</span> <span\
  \ m=\"280410\">between</span> <span m=\"281550\">compactness</span> <span m=\"282330\"\
  >in</span> <span m=\"282450\">the</span> <span m=\"282510\">sense</span> <span m=\"\
  282780\">of</span> <span m=\"283930\">finite</span> <span m=\"284260\">open</span>\
  \ <span m=\"284470\">covers</span> <span m=\"285340\">and</span> <span m=\"285640\"\
  >sequential</span> <span m=\"286180\">compactness</span> <span m=\"286840\">in</span>\
  \ <span m=\"286940\">the</span> <span m=\"287020\">metric</span> <span m=\"287350\"\
  >space,</span> <span m=\"294280\">so</span> <span m=\"294460\">it</span> <span m=\"\
  294520\">suffices</span> <span m=\"295120\">to</span> <span m=\"295210\">show</span>\
  \ <span m=\"295480\">sequential</span> <span m=\"296020\">compactness,</span> <span\
  \ m=\"297340\">that</span> <span m=\"297940\">every</span> <span m=\"299620\">sequence</span>\
  \ <span m=\"301260\">of</span> <span m=\"301510\">graphons</span> <span m=\"312220\"\
  >has</span> <span m=\"312790\">a</span> <span m=\"313090\">convergent</span> <span\
  \ m=\"313930\">subsequence</span> <span m=\"328190\">with</span> <span m=\"328400\"\
  >respect</span> <span m=\"328790\">to</span> <span m=\"329000\">this</span> <span\
  \ m=\"329510\">cut</span> <span m=\"329750\">metric</span> <span m=\"331430\">and</span>\
  \ <span m=\"331580\">also</span> <span m=\"331820\">will</span> <span m=\"332000\"\
  >produce</span> <span m=\"332780\">a</span> <span m=\"332810\">limit</span> <span\
  \ m=\"334070\">as</span> <span m=\"334190\">a</span> <span m=\"334250\">convergence</span>\
  \ <span m=\"334700\">subsequence</span> <span m=\"336200\">with</span> <span m=\"\
  337410\">a</span> <span m=\"339420\">limit</span> <span m=\"339690\">point.</span></p><p><span\
  \ m=\"343390\">So</span> <span m=\"343510\">that's</span> <span m=\"343690\">what</span>\
  \ <span m=\"343830\">we'll</span> <span m=\"343930\">do.</span> <span m=\"344620\"\
  >I</span> <span m=\"344710\">give</span> <span m=\"344860\">you</span> <span m=\"\
  344920\">an</span> <span m=\"345010\">arbitrary</span> <span m=\"345430\">sequence</span>\
  \ <span m=\"345820\">of</span> <span m=\"345880\">graphons.</span> <span m=\"346720\"\
  >I</span> <span m=\"346780\">want</span> <span m=\"346930\">to</span> <span m=\"\
  346990\">construct</span> <span m=\"347470\">by</span> <span m=\"347620\">taking</span>\
  \ <span m=\"347920\">subsequences</span> <span m=\"349030\">a</span> <span m=\"\
  349090\">convergent</span> <span m=\"349630\">sequence.</span> <span m=\"349890\"\
  >And</span> <span m=\"350150\">I</span> <span m=\"350280\">will</span> <span m=\"\
  350470\">tell</span> <span m=\"350600\">you</span> <span m=\"350720\">what</span>\
  \ <span m=\"350880\">that</span> <span m=\"350980\">limit is.</span></p><p><span\
  \ m=\"353150\">So</span> <span m=\"353170\">here is</span> <span m=\"353470\">what</span>\
  \ <span m=\"354520\">we're</span> <span m=\"354670\">going</span> <span m=\"354760\"\
  >to</span> <span m=\"354880\">do,</span> <span m=\"355240\">given</span> <span m=\"\
  355540\">this</span> <span m=\"355630\">sequence.</span> <span m=\"357280\">As</span>\
  \ <span m=\"357430\">I</span> <span m=\"357520\">hinted</span> <span m=\"357760\"\
  >before,</span> <span m=\"358300\">it</span> <span m=\"358390\">has</span> <span\
  \ m=\"358630\">to</span> <span m=\"358720\">do</span> <span m=\"358930\">with</span>\
  \ <span m=\"359140\">the</span> <span m=\"359230\">regularity</span> <span m=\"\
  359530\">lemma.</span> <span m=\"360190\">So</span> <span m=\"360400\">we're</span>\
  \ <span m=\"360550\">going</span> <span m=\"360680\">to</span> <span m=\"360730\"\
  >apply</span> <span m=\"361210\">the</span> <span m=\"361330\">regularity</span>\
  \ <span m=\"361960\">lemma</span> <span m=\"362500\">in</span> <span m=\"362650\"\
  >the</span> <span m=\"362770\">above</span> <span m=\"363040\">form,</span> <span\
  \ m=\"363520\">which</span> <span m=\"363700\">we</span> <span m=\"363820\">did</span>\
  \ <span m=\"364030\">last</span> <span m=\"364300\">time.</span> <span m=\"365600\"\
  >So</span> <span m=\"366250\">apply</span> <span m=\"368830\">the</span> <span m=\"\
  368980\">weak</span> <span m=\"369400\">regularity</span> <span m=\"370070\">lemma,</span>\
  \ <span m=\"376100\">which</span> <span m=\"376280\">will</span> <span m=\"376370\"\
  >tell</span> <span m=\"376610\">us</span> <span m=\"377260\">that</span> <span m=\"\
  377510\">for</span> <span m=\"380220\">each</span> <span m=\"381870\">Wn,</span>\
  \ <span m=\"384300\">there</span> <span m=\"384480\">exists</span> <span m=\"385500\"\
  >a</span> <span m=\"385650\">partition,</span> <span m=\"388790\">in</span> <span\
  \ m=\"388850\">fact,</span> <span m=\"389180\">a</span> <span m=\"389240\">sequence</span>\
  \ <span m=\"389750\">of</span> <span m=\"389840\">partitions,</span> <span m=\"\
  391190\">each</span> <span m=\"391400\">one</span> <span m=\"391910\">refining</span>\
  \ <span m=\"392510\">the</span> <span m=\"392630\">next.</span></p><p><span m=\"\
  393560\">So</span> <span m=\"393740\">what's</span> <span m=\"393980\">going</span>\
  \ <span m=\"394070\">to</span> <span m=\"394160\">happen</span> <span m=\"394520\"\
  >is,</span> <span m=\"395000\">I'm</span> <span m=\"395120\">going</span> <span\
  \ m=\"395260\">to</span> <span m=\"395540\">start</span> <span m=\"395990\">with</span>\
  \ <span m=\"396740\">Wn</span> <span m=\"397400\">and</span> <span m=\"397580\"\
  >starting</span> <span m=\"398030\">with</span> <span m=\"398230\">a</span> <span\
  \ m=\"398270\">trivial</span> <span m=\"398810\">partition,</span> <span m=\"400190\"\
  >apply</span> <span m=\"400860\">that</span> <span m=\"401030\">lemma,</span> <span\
  \ m=\"402020\">and</span> <span m=\"402200\">obtain</span> <span m=\"403190\">a</span>\
  \ <span m=\"403280\">partition</span> <span m=\"405320\">P sub</span> <span m=\"\
  405770\">n,</span> <span m=\"406770\">1.</span> <span m=\"408460\">And</span> <span\
  \ m=\"408580\">then</span> <span m=\"408670\">starting</span> <span m=\"409120\"\
  >with</span> <span m=\"409300\">that</span> <span m=\"410590\">as</span> <span m=\"\
  410740\">my</span> <span m=\"410930\">P0,</span> <span m=\"411820\">I'm</span> <span\
  \ m=\"411940\">going</span> <span m=\"412150\">to</span> <span m=\"412240\">apply</span>\
  \ <span m=\"412630\">regularity</span> <span m=\"413260\">lemma</span> <span m=\"\
  414100\">again</span> <span m=\"415330\">and</span> <span m=\"415520\">obtain</span>\
  \ <span m=\"416020\">a</span> <span m=\"416080\">refinement.</span> <span m=\"422010\"\
  >I</span> <span m=\"422460\">will</span> <span m=\"422590\">have</span> <span m=\"\
  422770\">this</span> <span m=\"423190\">sequence</span> <span m=\"424000\">of</span>\
  \ <span m=\"424420\">partitions,</span> <span m=\"425530\">each</span> <span m=\"\
  425770\">one</span> <span m=\"429896\">refining</span> <span m=\"430990\">the</span>\
  \ <span m=\"431080\">next.</span></p><p><span m=\"437640\">So</span> <span m=\"\
  437790\">all of</span> <span m=\"438030\">these</span> <span m=\"438210\">are</span>\
  \ <span m=\"438300\">going</span> <span m=\"438480\">to</span> <span m=\"438570\"\
  >be</span> <span m=\"438810\">partitions</span> <span m=\"439590\">of</span> <span\
  \ m=\"440190\">the</span> <span m=\"440280\">0,</span> <span m=\"440560\">1</span>\
  \ <span m=\"440760\">interval.</span> <span m=\"441690\">And</span> <span m=\"442500\"\
  >as</span> <span m=\"442680\">I</span> <span m=\"442770\">mentioned</span> <span\
  \ m=\"443070\">last</span> <span m=\"443280\">time,</span> <span m=\"443520\">everything's</span>\
  \ <span m=\"444060\">going</span> <span m=\"444150\">to</span> <span m=\"444240\"\
  >be</span> <span m=\"444330\">measurable.</span> <span m=\"444840\">I'm</span> <span\
  \ m=\"444930\">not</span> <span m=\"445140\">going</span> <span m=\"445320\">to</span>\
  \ <span m=\"445410\">even</span> <span m=\"446040\">mention</span> <span m=\"446383\"\
  >measurability.</span> <span m=\"447070\">Everything</span> <span m=\"447390\">will</span>\
  \ <span m=\"447510\">be</span> <span m=\"447600\">measurable</span> <span m=\"451280\"\
  >such</span> <span m=\"451610\">that</span> <span m=\"452210\">they</span> <span\
  \ m=\"452360\">satisfy</span> <span m=\"452870\">the</span> <span m=\"452960\">following</span>\
  \ <span m=\"454490\">conditions.</span></p><p><span m=\"455640\">So</span> <span\
  \ m=\"455690\">the</span> <span m=\"455780\">first</span> <span m=\"456110\">one</span>\
  \ <span m=\"456380\">is</span> <span m=\"456770\">what</span> <span m=\"456920\"\
  >I</span> <span m=\"457340\">mentioned</span> <span m=\"458750\">earlier,</span>\
  \ <span m=\"459410\">is</span> <span m=\"459560\">that</span> <span m=\"459680\"\
  >you</span> <span m=\"459830\">have</span> <span m=\"460010\">a</span> <span m=\"\
  460070\">sequence</span> <span m=\"460520\">of</span> <span m=\"460640\">refinements.</span>\
  \ <span m=\"461670\">So</span> <span m=\"461720\">each</span> <span m=\"462080\"\
  >P</span> <span m=\"462500\">sub</span> <span m=\"463100\">n</span> <span m=\"463280\"\
  >k</span> <span m=\"463460\">plus</span> <span m=\"463730\">1</span> <span m=\"\
  464480\">refines</span> <span m=\"467170\">the</span> <span m=\"467290\">previous</span>\
  \ <span m=\"467740\">one</span> <span m=\"469420\">for</span> <span m=\"469600\"\
  >all</span> <span m=\"471270\">n</span> <span m=\"471460\">and</span> <span m=\"\
  471610\">k.</span></p><p><span m=\"475560\">And</span> <span m=\"475670\">the</span>\
  \ <span m=\"475760\">second</span> <span m=\"476060\">condition,</span> <span m=\"\
  477380\">as</span> <span m=\"477650\">given</span> <span m=\"477950\">by</span>\
  \ <span m=\"478070\">the</span> <span m=\"478160\">regularity</span> <span m=\"\
  478730\">lemma,</span> <span m=\"479780\">you</span> <span m=\"479960\">get</span>\
  \ <span m=\"480170\">to</span> <span m=\"480320\">control</span> <span m=\"481100\"\
  >the</span> <span m=\"481220\">number</span> <span m=\"481730\">of</span> <span\
  \ m=\"481880\">parts.</span> <span m=\"483410\">So I</span> <span m=\"483640\">will</span>\
  \ <span m=\"483760\">say in</span> <span m=\"484100\">the</span> <span m=\"484160\"\
  >third</span> <span m=\"484460\">part</span> <span m=\"485020\">what</span> <span\
  \ m=\"485270\">the</span> <span m=\"486260\">error</span> <span m=\"486830\">of</span>\
  \ <span m=\"486950\">approximation</span> <span m=\"487670\">is.</span> <span m=\"\
  488000\">But</span> <span m=\"488150\">you</span> <span m=\"488240\">get</span>\
  \ <span m=\"488390\">to</span> <span m=\"488480\">control</span> <span m=\"488900\"\
  >the</span> <span m=\"488990\">number</span> <span m=\"489320\">of</span> <span\
  \ m=\"489410\">parts.</span> <span m=\"490280\">So</span> <span m=\"490430\">in</span>\
  \ <span m=\"490520\">particular,</span> <span m=\"491480\">I</span> <span m=\"491600\"\
  >can</span> <span m=\"491810\">make</span> <span m=\"492050\">sure</span> <span\
  \ m=\"492920\">that</span> <span m=\"496010\">this</span> <span m=\"496220\">number</span>\
  \ <span m=\"496550\">here,</span> <span m=\"496760\">the</span> <span m=\"496880\"\
  >number</span> <span m=\"497300\">of</span> <span m=\"497390\">parts</span> <span\
  \ m=\"498770\">in</span> <span m=\"499010\">the</span> <span m=\"499310\">k'th</span>\
  \ <span m=\"499700\">partition</span> <span m=\"500990\">depends</span> <span m=\"\
  501770\">only</span> <span m=\"502130\">on</span> <span m=\"502310\">k.</span></p><p><span\
  \ m=\"512299\">Now,</span> <span m=\"512500\">you</span> <span m=\"512590\">might</span>\
  \ <span m=\"512770\">complain</span> <span m=\"514600\">somewhat,</span> <span m=\"\
  516039\">because</span> <span m=\"516909\">the</span> <span m=\"517000\">regularity</span>\
  \ <span m=\"517690\">lemma</span> <span m=\"518320\">only</span> <span m=\"518530\"\
  >tells</span> <span m=\"518890\">you</span> <span m=\"519340\">an</span> <span m=\"\
  519520\">upper</span> <span m=\"519789\">bound</span> <span m=\"520059\">on</span>\
  \ <span m=\"520179\">the</span> <span m=\"520240\">number</span> <span m=\"520539\"\
  >of</span> <span m=\"520659\">parts.</span> <span m=\"522150\">But</span> <span\
  \ m=\"522270\">that's</span> <span m=\"522450\">OK.</span> <span m=\"525030\">I</span>\
  \ <span m=\"525090\">can</span> <span m=\"525270\">allow</span> <span m=\"525660\"\
  >empty</span> <span m=\"526020\">parts.</span> <span m=\"530990\">So</span> <span\
  \ m=\"531140\">now</span> <span m=\"531350\">I</span> <span m=\"531410\">make</span>\
  \ <span m=\"531620\">sure</span> <span m=\"532310\">that</span> <span m=\"533620\"\
  >the</span> <span m=\"533740\">k'th</span> <span m=\"534070\">partition</span> <span\
  \ m=\"534700\">has</span> <span m=\"534880\">exactly</span> <span m=\"535470\">nk</span>\
  \ <span m=\"535900\">parts.</span></p><p><span m=\"538620\">And</span> <span m=\"\
  538710\">the</span> <span m=\"538800\">third</span> <span m=\"539040\">one</span>\
  \ <span m=\"539370\">has</span> <span m=\"539640\">to</span> <span m=\"539760\"\
  >do</span> <span m=\"540030\">with</span> <span m=\"540810\">the</span> <span m=\"\
  542860\">area</span> <span m=\"543360\">of</span> <span m=\"543510\">approximation.</span>\
  \ <span m=\"547110\">OK,</span> <span m=\"547290\">so</span> <span m=\"549960\"\
  >suppose</span> <span m=\"550230\">we</span> <span m=\"550350\">write</span> <span\
  \ m=\"551190\">W</span> <span m=\"551610\">sub</span> <span m=\"552180\">nk</span>\
  \ <span m=\"553650\">as</span> <span m=\"555030\">the</span> <span m=\"556020\"\
  >graphon</span> <span m=\"556540\">obtained</span> <span m=\"557100\">by</span>\
  \ <span m=\"557310\">applying</span> <span m=\"557820\">the</span> <span m=\"557940\"\
  >stepping</span> <span m=\"558390\">operator.</span> <span m=\"558870\">So</span>\
  \ <span m=\"559020\">this</span> <span m=\"559170\">is</span> <span m=\"559290\"\
  >the</span> <span m=\"559440\">averaging</span> <span m=\"559980\">operator</span>\
  \ <span m=\"560790\">on</span> <span m=\"560970\">this</span> <span m=\"561120\"\
  >partition,</span> <span m=\"564210\">corresponding</span> <span m=\"564810\">to</span>\
  \ <span m=\"564900\">the</span> <span m=\"564990\">k'th</span> <span m=\"565230\"\
  >partition.</span> <span m=\"565740\">I</span> <span m=\"565860\">apply</span> <span\
  \ m=\"566190\">that</span> <span m=\"566340\">partition,</span> <span m=\"567380\"\
  >do</span> <span m=\"567540\">a</span> <span m=\"567600\">stepping</span> <span\
  \ m=\"568050\">averaging</span> <span m=\"568470\">operator</span> <span m=\"570060\"\
  >on</span> <span m=\"570360\">the</span> <span m=\"570520\">n'th</span> <span m=\"\
  570770\">graphon.</span> <span m=\"572080\">I</span> <span m=\"572450\">get</span>\
  \ <span m=\"572910\">W</span> <span m=\"573240\">sub</span> <span m=\"573780\">nk.</span></p><p><span\
  \ m=\"576080\">The</span> <span m=\"576180\">third</span> <span m=\"576480\">condition</span>\
  \ <span m=\"577200\">is</span> <span m=\"577380\">that</span> <span m=\"580230\"\
  >the</span> <span m=\"580530\">k'th</span> <span m=\"580860\">partition</span> <span\
  \ m=\"582690\">approximates--</span> <span m=\"584380\">it's</span> <span m=\"584610\"\
  >a</span> <span m=\"584670\">good</span> <span m=\"584850\">approximation</span>\
  \ <span m=\"586050\">in</span> <span m=\"586170\">the</span> <span m=\"586230\"\
  >cut</span> <span m=\"586470\">norm</span> <span m=\"588790\">up</span> <span m=\"\
  588920\">to</span> <span m=\"589100\">error</span> <span m=\"589960\">1</span> <span\
  \ m=\"590150\">over</span> <span m=\"590320\">k.</span> <span m=\"591780\">So</span>\
  \ <span m=\"591970\">1 over</span> <span m=\"592140\">k</span> <span m=\"592340\"\
  >is</span> <span m=\"592590\">some</span> <span m=\"592840\">arbitrary</span> <span\
  \ m=\"593680\">sequence</span> <span m=\"594130\">going</span> <span m=\"594370\"\
  >to</span> <span m=\"594460\">0</span> <span m=\"594950\">as</span> <span m=\"595120\"\
  >k</span> <span m=\"595270\">goes</span> <span m=\"595510\">to</span> <span m=\"\
  596200\">infinity.</span></p><p><span m=\"612100\">So</span> <span m=\"612180\"\
  >I</span> <span m=\"612300\">obtained</span> <span m=\"612740\">a</span> <span m=\"\
  612810\">sequence</span> <span m=\"613290\">of</span> <span m=\"613380\">partitions,</span>\
  \ <span m=\"614520\">so</span> <span m=\"614670\">by</span> <span m=\"614880\">applying</span>\
  \ <span m=\"615390\">the</span> <span m=\"615530\">regularity</span> <span m=\"\
  616200\">lemma</span> <span m=\"617390\">to</span> <span m=\"618690\">each</span>\
  \ <span m=\"620080\">to</span> <span m=\"620400\">each</span> <span m=\"620610\"\
  >graphon</span> <span m=\"621030\">in</span> <span m=\"621150\">the</span> <span\
  \ m=\"621210\">sequence.</span> <span m=\"624300\">Now,</span> <span m=\"625300\"\
  >these</span> <span m=\"625520\">graphons,</span> <span m=\"626510\">I</span> <span\
  \ m=\"626540\">mean,</span> <span m=\"626660\">they</span> <span m=\"627530\">each</span>\
  \ <span m=\"627770\">have</span> <span m=\"627950\">their</span> <span m=\"628100\"\
  >own</span> <span m=\"628280\">vertex</span> <span m=\"628700\">set.</span> <span\
  \ m=\"629260\">And</span> <span m=\"629750\">so</span> <span m=\"629990\">far,</span>\
  \ <span m=\"630350\">they're</span> <span m=\"630530\">not</span> <span m=\"630710\"\
  >related</span> <span m=\"631100\">to</span> <span m=\"631220\">each</span> <span\
  \ m=\"631430\">other.</span></p><p><span m=\"632040\">But</span> <span m=\"632600\"\
  >to</span> <span m=\"632750\">make</span> <span m=\"634410\">the</span> <span m=\"\
  634530\">visualization</span> <span m=\"635340\">easier</span> <span m=\"635850\"\
  >and</span> <span m=\"636000\">also</span> <span m=\"636600\">in</span> <span m=\"\
  637070\">order</span> <span m=\"637300\">to</span> <span m=\"637490\">do</span>\
  \ <span m=\"637830\">the</span> <span m=\"637950\">next</span> <span m=\"638520\"\
  >step</span> <span m=\"638790\">in</span> <span m=\"638880\">the</span> <span m=\"\
  638940\">proof,</span> <span m=\"639620\">I</span> <span m=\"639790\">am</span>\
  \ <span m=\"639870\">going</span> <span m=\"640170\">to</span> <span m=\"642150\"\
  >do</span> <span m=\"642450\">some</span> <span m=\"644790\">measure-preserving</span>\
  \ <span m=\"645530\">bisection</span> <span m=\"646260\">So</span> <span m=\"646440\"\
  >think</span> <span m=\"646680\">of</span> <span m=\"646770\">this</span> <span\
  \ m=\"647010\">as</span> <span m=\"647580\">permuting</span> <span m=\"648090\"\
  >the</span> <span m=\"648180\">vertex</span> <span m=\"648570\">labels.</span> <span\
  \ m=\"649960\">So</span> <span m=\"650100\">by</span> <span m=\"650280\">replacing</span>\
  \ <span m=\"655230\">each</span> <span m=\"657750\">Wn</span> <span m=\"658800\"\
  >by</span> <span m=\"660390\">some</span> <span m=\"664010\">W</span> <span m=\"\
  664520\">sub</span> <span m=\"664760\">n</span> <span m=\"665090\">of</span> <span\
  \ m=\"665790\">phi,</span> <span m=\"666500\">where</span> <span m=\"667240\">phi</span>\
  \ <span m=\"667620\">is</span> <span m=\"668120\">a</span> <span m=\"668270\">measure-preserving</span>\
  \ <span m=\"669090\">bisection,</span> <span m=\"675350\">we</span> <span m=\"675500\"\
  >can</span> <span m=\"675650\">assume</span> <span m=\"678500\">that</span> <span\
  \ m=\"680090\">all</span> <span m=\"681320\">these</span> <span m=\"681530\">partitions</span>\
  \ <span m=\"684080\">are</span> <span m=\"686140\">partitions</span> <span m=\"\
  686890\">into</span> <span m=\"687340\">intervals.</span></p><p><span m=\"696660\"\
  >So</span> <span m=\"696840\">initially,</span> <span m=\"697350\">you</span> <span\
  \ m=\"697470\">might</span> <span m=\"697740\">have</span> <span m=\"698070\">a</span>\
  \ <span m=\"698130\">partition</span> <span m=\"698670\">into</span> <span m=\"\
  699270\">arbitrary</span> <span m=\"699690\">measurable</span> <span m=\"700050\"\
  >sets.</span> <span m=\"701640\">Well,</span> <span m=\"701860\">what</span> <span\
  \ m=\"702000\">I</span> <span m=\"702060\">can</span> <span m=\"702210\">do</span>\
  \ <span m=\"702420\">is</span> <span m=\"702960\">to</span> <span m=\"703300\">push</span>\
  \ <span m=\"704730\">over</span> <span m=\"704950\">the</span> <span m=\"705060\"\
  >first</span> <span m=\"705330\">set</span> <span m=\"706020\">to</span> <span m=\"\
  706140\">the</span> <span m=\"706260\">left,</span> <span m=\"707120\">and</span>\
  \ <span m=\"707220\">so</span> <span m=\"707400\">on,</span> <span m=\"707470\"\
  >so</span> <span m=\"707850\">do</span> <span m=\"708060\">a</span> <span m=\"708150\"\
  >measure-preserving</span> <span m=\"709380\">bisection</span> <span m=\"710400\"\
  >in</span> <span m=\"710510\">a</span> <span m=\"710550\">way</span> <span m=\"\
  710790\">so</span> <span m=\"710940\">that</span> <span m=\"711060\">I</span> <span\
  \ m=\"711090\">can</span> <span m=\"711240\">maintain</span> <span m=\"713160\"\
  >that</span> <span m=\"714550\">all</span> <span m=\"714690\">the</span> <span m=\"\
  714780\">partitions</span> <span m=\"715380\">are</span> <span m=\"715740\">visually</span>\
  \ <span m=\"716490\">chopping</span> <span m=\"717300\">up</span> <span m=\"717720\"\
  >into</span> <span m=\"717930\">intervals.</span></p><p><span m=\"718440\">Yeah?</span></p><p><span\
  \ m=\"718689\">AUDIENCE:</span> <span m=\"718772\">So</span> <span m=\"718855\"\
  >at</span> <span m=\"718938\">some</span> <span m=\"719436\">point,</span> <span\
  \ m=\"719934\">we need</span> <span m=\"720432\">just one</span> <span m=\"720930\"\
  >measure for</span> <span m=\"721428\">the projection,</span> <span m=\"721926\"\
  >like</span> <span m=\"722424\">all of</span> <span m=\"722922\">them be</span>\
  \ <span m=\"723420\">in</span> <span m=\"723918\">k?</span></p><p><span m=\"724920\"\
  >YUFEI ZHAO:</span> <span m=\"725080\">OK, so</span> <span m=\"725240\">the</span>\
  \ <span m=\"725300\">question</span> <span m=\"725650\">is,</span> <span m=\"727110\"\
  >it</span> <span m=\"727580\">may</span> <span m=\"727820\">be</span> <span m=\"\
  727970\">the</span> <span m=\"728060\">case</span> <span m=\"728660\">that,</span>\
  \ <span m=\"729680\">for</span> <span m=\"730100\">a</span> <span m=\"730190\">given</span>\
  \ <span m=\"730580\">k,</span> <span m=\"731510\">I</span> <span m=\"731660\">can</span>\
  \ <span m=\"732440\">do</span> <span m=\"732620\">this</span> <span m=\"732800\"\
  >arrangement,</span> <span m=\"734710\">but</span> <span m=\"735250\">it's</span>\
  \ <span m=\"735430\">not</span> <span m=\"735640\">clear</span> <span m=\"736270\"\
  >to</span> <span m=\"736420\">you</span> <span m=\"736570\">at</span> <span m=\"\
  736660\">the</span> <span m=\"736720\">moment</span> <span m=\"737410\">why</span>\
  \ <span m=\"737740\">you</span> <span m=\"737860\">can</span> <span m=\"738040\"\
  >do</span> <span m=\"738160\">this</span> <span m=\"738400\">uniformly</span> <span\
  \ m=\"739590\">for all</span> <span m=\"740000\">k.</span> <span m=\"741790\">So</span>\
  \ <span m=\"742780\">one</span> <span m=\"743080\">way</span> <span m=\"743200\"\
  >to</span> <span m=\"743290\">get</span> <span m=\"743470\">around</span> <span\
  \ m=\"743740\">this</span> <span m=\"743920\">is,</span> <span m=\"744070\">for</span>\
  \ <span m=\"744220\">now,</span> <span m=\"744610\">just</span> <span m=\"744730\"\
  >think</span> <span m=\"744940\">of</span> <span m=\"745030\">for</span> <span m=\"\
  745240\">each</span> <span m=\"745480\">given</span> <span m=\"745810\">k.</span>\
  \ <span m=\"746500\">And</span> <span m=\"746590\">then</span> <span m=\"746710\"\
  >you'll</span> <span m=\"746860\">see</span> <span m=\"747070\">at</span> <span\
  \ m=\"747160\">the</span> <span m=\"747280\">end</span> <span m=\"747610\">that</span>\
  \ <span m=\"748120\">that's</span> <span m=\"748630\">already</span> <span m=\"\
  748930\">enough.</span> <span m=\"752898\">OK,</span> <span m=\"753350\">any</span>\
  \ <span m=\"753510\">more</span> <span m=\"753630\">questions?</span></p><p>&nbsp;</p><p><span\
  \ m=\"758170\">So</span> <span m=\"758340\">now</span> <span m=\"758580\">assume</span>\
  \ <span m=\"759180\">all</span> <span m=\"759360\">of</span> <span m=\"759420\"\
  >these</span> <span m=\"759630\">P</span> <span m=\"759900\">sub</span> <span m=\"\
  760860\">nk's</span> <span m=\"761280\">are</span> <span m=\"761370\">intervals.</span>\
  \ <span m=\"761940\">So</span> <span m=\"762090\">in</span> <span m=\"762150\">fact,</span>\
  \ <span m=\"762780\">what</span> <span m=\"762990\">you</span> <span m=\"763500\"\
  >said</span> <span m=\"763980\">may be</span> <span m=\"764220\">a</span> <span\
  \ m=\"764250\">better</span> <span m=\"764490\">way</span> <span m=\"764640\">to</span>\
  \ <span m=\"764730\">go.</span> <span m=\"765210\">But</span> <span m=\"766410\"\
  >to</span> <span m=\"766560\">make</span> <span m=\"767010\">our</span> <span m=\"\
  767160\">life</span> <span m=\"767370\">a</span> <span m=\"767400\">little</span>\
  \ <span m=\"767550\">bit</span> <span m=\"767700\">easier,</span> <span m=\"768430\"\
  >let's</span> <span m=\"768780\">just</span> <span m=\"768990\">assume</span> <span\
  \ m=\"769290\">for</span> <span m=\"769410\">now</span> <span m=\"769590\">that</span>\
  \ <span m=\"769710\">you</span> <span m=\"769800\">can</span> <span m=\"770070\"\
  >do</span> <span m=\"770220\">this.</span></p><p><span m=\"773670\">OK,</span> <span\
  \ m=\"774540\">and</span> <span m=\"775080\">what's</span> <span m=\"775320\">going</span>\
  \ <span m=\"775400\">to</span> <span m=\"775500\">happen</span> <span m=\"775770\"\
  >next</span> <span m=\"776190\">is</span> <span m=\"776310\">some</span> <span m=\"\
  776520\">kind</span> <span m=\"776790\">of</span> <span m=\"776880\">a</span> <span\
  \ m=\"776940\">diagonalization</span> <span m=\"777840\">argument.</span> <span\
  \ m=\"779490\">We're</span> <span m=\"779640\">going</span> <span m=\"779820\">to</span>\
  \ <span m=\"779910\">be</span> <span m=\"780000\">picking</span> <span m=\"780390\"\
  >subsequences.</span> <span m=\"785760\">So</span> <span m=\"788700\">I'm</span>\
  \ <span m=\"788850\">going</span> <span m=\"789060\">to</span> <span m=\"789150\"\
  >be</span> <span m=\"789240\">picking</span> <span m=\"789540\">subsequences</span>\
  \ <span m=\"790740\">so</span> <span m=\"790890\">that</span> <span m=\"791310\"\
  >they</span> <span m=\"791910\">are</span> <span m=\"792030\">going</span> <span\
  \ m=\"792240\">to</span> <span m=\"792330\">have</span> <span m=\"792570\">very</span>\
  \ <span m=\"792810\">nice</span> <span m=\"793050\">convergence</span> <span m=\"\
  793650\">properties.</span></p><p><span m=\"794850\">And</span> <span m=\"795750\"\
  >so</span> <span m=\"795900\">I'm</span> <span m=\"796020\">going</span> <span m=\"\
  796170\">to</span> <span m=\"796650\">repeatedly</span> <span m=\"797310\">throw</span>\
  \ <span m=\"797670\">out</span> <span m=\"798150\">a</span> <span m=\"798240\">lot</span>\
  \ <span m=\"798780\">of</span> <span m=\"798900\">the</span> <span m=\"798990\"\
  >sequence.</span> <span m=\"799930\">So</span> <span m=\"799980\">this</span> <span\
  \ m=\"800130\">is</span> <span m=\"800250\">a</span> <span m=\"800310\">diagonalization</span>\
  \ <span m=\"801120\">argument.</span> <span m=\"801930\">And</span> <span m=\"803620\"\
  >basically</span> <span m=\"804010\">what</span> <span m=\"804160\">happens</span>\
  \ <span m=\"804670\">is</span> <span m=\"804820\">that,</span> <span m=\"805390\"\
  >by</span> <span m=\"805780\">passing</span> <span m=\"806290\">two</span> <span\
  \ m=\"806440\">subsequences--</span> <span m=\"811564\">and</span> <span m=\"812030\"\
  >we're</span> <span m=\"812120\">going</span> <span m=\"812240\">to</span> <span\
  \ m=\"812300\">do</span> <span m=\"812450\">this</span> <span m=\"812780\">repeatedly,</span>\
  \ <span m=\"813410\">many</span> <span m=\"813650\">times--</span> <span m=\"815450\"\
  >we</span> <span m=\"815600\">can</span> <span m=\"816200\">assume,</span> <span\
  \ m=\"817940\">first,</span> <span m=\"820250\">that</span> <span m=\"821720\">the</span>\
  \ <span m=\"821930\">end</span> <span m=\"822090\">points</span> <span m=\"826970\"\
  >of</span> <span m=\"829440\">P</span> <span m=\"829800\">sub</span> <span m=\"\
  830300\">n1,</span> <span m=\"831420\">they</span> <span m=\"831630\">converge</span>\
  \ <span m=\"835200\">as</span> <span m=\"836740\">n</span> <span m=\"837020\">goes</span>\
  \ <span m=\"837260\">to</span> <span m=\"837350\">infinity.</span> <span m=\"839070\"\
  >So</span> <span m=\"839180\">each</span> <span m=\"839600\">P</span> <span m=\"\
  839990\">sub</span> <span m=\"840410\">n1</span> <span m=\"841400\">is</span> <span\
  \ m=\"841940\">some</span> <span m=\"843080\">partition</span> <span m=\"852582\"\
  >of</span> <span m=\"852990\">interval</span> <span m=\"854250\">into</span> <span\
  \ m=\"855450\">some</span> <span m=\"855750\">fixed</span> <span m=\"856020\">number</span>\
  \ <span m=\"856290\">of</span> <span m=\"856380\">parts.</span> <span m=\"857370\"\
  >So</span> <span m=\"857580\">by</span> <span m=\"857700\">passing</span> <span\
  \ m=\"858150\">to</span> <span m=\"858270\">a</span> <span m=\"858330\">subsequence,</span>\
  \ <span m=\"859260\">I</span> <span m=\"859320\">make</span> <span m=\"859500\"\
  >sure</span> <span m=\"859740\">that</span> <span m=\"860550\">the</span> <span\
  \ m=\"860670\">division</span> <span m=\"861090\">points</span> <span m=\"861570\"\
  >all</span> <span m=\"861750\">converge.</span></p><p><span m=\"868850\">And</span>\
  \ <span m=\"868970\">now,</span> <span m=\"871830\">by</span> <span m=\"872280\"\
  >passing</span> <span m=\"872940\">one</span> <span m=\"873150\">more</span> <span\
  \ m=\"873270\">time,</span> <span m=\"874420\">so</span> <span m=\"874620\">by</span>\
  \ <span m=\"874800\">passing</span> <span m=\"875190\">to</span> <span m=\"875310\"\
  >subsequence</span> <span m=\"875910\">one</span> <span m=\"876030\">more</span>\
  \ <span m=\"876180\">time,</span> <span m=\"876860\">let's</span> <span m=\"877170\"\
  >assume</span> <span m=\"877740\">that</span> <span m=\"878310\">also,</span> <span\
  \ m=\"881250\">W</span> <span m=\"881590\">sub</span> <span m=\"882210\">n1</span>\
  \ <span m=\"883440\">converges</span> <span m=\"884310\">to</span> <span m=\"884940\"\
  >some</span> <span m=\"885300\">function,</span> <span m=\"886020\">some</span>\
  \ <span m=\"886330\">graphon</span> <span m=\"887240\">u1,</span> <span m=\"888420\"\
  >point-wise.</span> <span m=\"900580\">So</span> <span m=\"901270\">initially,</span>\
  \ <span m=\"904430\">I</span> <span m=\"904570\">have</span> <span m=\"910960\"\
  >these</span> <span m=\"911170\">graphons.</span> <span m=\"912100\">Each</span>\
  \ <span m=\"912280\">one</span> <span m=\"912430\">of</span> <span m=\"912490\"\
  >them</span> <span m=\"912850\">is</span> <span m=\"913090\">an</span> <span m=\"\
  914060\">m</span> <span m=\"914320\">by</span> <span m=\"914500\">n</span> <span\
  \ m=\"914650\">block.</span> <span m=\"915710\">They</span> <span m=\"916030\">have</span>\
  \ <span m=\"916780\">various</span> <span m=\"917710\">division</span> <span m=\"\
  918070\">points.</span></p><p><span m=\"919060\">By</span> <span m=\"919220\">passing</span>\
  \ <span m=\"919630\">to</span> <span m=\"919720\">a</span> <span m=\"919780\">subsequence,</span>\
  \ <span m=\"920920\">I</span> <span m=\"921220\">assume</span> <span m=\"921590\"\
  >that</span> <span m=\"921730\">the</span> <span m=\"922270\">points</span> <span\
  \ m=\"922570\">of</span> <span m=\"922660\">division,</span> <span m=\"923080\"\
  >they</span> <span m=\"923200\">converge.</span> <span m=\"924560\">And</span> <span\
  \ m=\"924730\">now</span> <span m=\"924940\">by</span> <span m=\"925060\">passing</span>\
  \ <span m=\"925450\">to an</span> <span m=\"925590\">additional</span> <span m=\"\
  926110\">subsequence,</span> <span m=\"927130\">I</span> <span m=\"927220\">can</span>\
  \ <span m=\"927340\">make</span> <span m=\"927490\">sure</span> <span m=\"927670\"\
  >the</span> <span m=\"927790\">individual</span> <span m=\"928330\">values,</span>\
  \ <span m=\"929540\">they</span> <span m=\"929740\">converge.</span> <span m=\"\
  932600\">So</span> <span m=\"933170\">as</span> <span m=\"933320\">a</span> <span\
  \ m=\"933350\">result,</span> <span m=\"934220\">W</span> <span m=\"934550\">sub</span>\
  \ <span m=\"934880\">n,</span> <span m=\"935510\">1</span> <span m=\"935960\">converges</span>\
  \ <span m=\"936550\">to</span> <span m=\"936670\">W1--</span> <span m=\"937700\"\
  >converges</span> <span m=\"938210\">to</span> <span m=\"938330\">some</span> <span\
  \ m=\"938600\">graphon,</span> <span m=\"939110\">u1,</span> <span m=\"939770\"\
  >point-wise,</span> <span m=\"940880\">almost</span> <span m=\"941180\">everywhere.</span></p><p><span\
  \ m=\"946030\">And</span> <span m=\"946240\">we</span> <span m=\"946390\">repeat</span>\
  \ <span m=\"949510\">for</span> <span m=\"951790\">W</span> <span m=\"953190\">sub</span>\
  \ <span m=\"953560\">nk</span> <span m=\"954310\">for</span> <span m=\"954520\"\
  >each</span> <span m=\"954790\">k.</span> <span m=\"959970\">So</span> <span m=\"\
  960100\">do</span> <span m=\"960280\">this</span> <span m=\"960510\">sequentially.</span>\
  \ <span m=\"961520\">So</span> <span m=\"961570\">we</span> <span m=\"961690\">just</span>\
  \ <span m=\"961900\">did</span> <span m=\"962060\">it</span> <span m=\"962140\"\
  >for</span> <span m=\"962290\">k</span> <span m=\"962530\">equals</span> <span m=\"\
  962740\">to</span> <span m=\"962830\">1.</span> <span m=\"963490\">Now</span> <span\
  \ m=\"963670\">do</span> <span m=\"963790\">it</span> <span m=\"963850\">for</span>\
  \ <span m=\"963970\">2,</span> <span m=\"964450\">3,</span> <span m=\"964930\">4,</span>\
  \ <span m=\"965410\">and</span> <span m=\"965530\">so</span> <span m=\"965740\"\
  >on.</span> <span m=\"968580\">So</span> <span m=\"968620\">this</span> <span m=\"\
  968800\">is</span> <span m=\"968890\">a</span> <span m=\"968950\">diagonalization</span>\
  \ <span m=\"969760\">argument.</span> <span m=\"970120\">We</span> <span m=\"970240\"\
  >do</span> <span m=\"970360\">this</span> <span m=\"970540\">countably</span> <span\
  \ m=\"970990\">many</span> <span m=\"971200\">times.</span></p><p><span m=\"972670\"\
  >At</span> <span m=\"972760\">the</span> <span m=\"972910\">end,</span> <span m=\"\
  973310\">what</span> <span m=\"973350\">do</span> <span m=\"973420\">we</span> <span\
  \ m=\"973540\">get?</span> <span m=\"975310\">We</span> <span m=\"979080\">pass</span>\
  \ <span m=\"979410\">down</span> <span m=\"979650\">to</span> <span m=\"979770\"\
  >the</span> <span m=\"979830\">following</span> <span m=\"980220\">subsequence.</span>\
  \ <span m=\"986850\">And</span> <span m=\"987840\">just</span> <span m=\"988050\"\
  >to</span> <span m=\"988140\">make</span> <span m=\"988320\">my</span> <span m=\"\
  988500\">life</span> <span m=\"988800\">a</span> <span m=\"988860\">bit</span> <span\
  \ m=\"989130\">more</span> <span m=\"989340\">convenient,</span> <span m=\"989820\"\
  >instead</span> <span m=\"990150\">of</span> <span m=\"990270\">labeling</span>\
  \ <span m=\"990780\">the</span> <span m=\"993150\">indices</span> <span m=\"993690\"\
  >of</span> <span m=\"993780\">the</span> <span m=\"993840\">subsequence,</span>\
  \ <span m=\"994900\">I'm</span> <span m=\"995070\">going</span> <span m=\"995340\"\
  >to</span> <span m=\"996180\">relabel</span> <span m=\"996690\">the</span> <span\
  \ m=\"996780\">sequence</span> <span m=\"997380\">so</span> <span m=\"997530\">that</span>\
  \ <span m=\"997680\">it's</span> <span m=\"997830\">still</span> <span m=\"998160\"\
  >labeled</span> <span m=\"998610\">by</span> <span m=\"998700\">1,</span> <span\
  \ m=\"998910\">2,</span> <span m=\"999120\">3,</span> <span m=\"999300\">4,</span>\
  \ <span m=\"999510\">and</span> <span m=\"999600\">so</span> <span m=\"999780\"\
  >on.</span></p><p><span m=\"1000560\">So</span> <span m=\"1000710\">we</span> <span\
  \ m=\"1000830\">now</span> <span m=\"1001040\">pass</span> <span m=\"1001400\">to</span>\
  \ <span m=\"1001610\">a</span> <span m=\"1002150\">sequence</span> <span m=\"1003320\"\
  >W1,</span> <span m=\"1004445\">W2,</span> <span m=\"1005740\">W3,</span> <span\
  \ m=\"1007320\">and</span> <span m=\"1007670\">so on,</span> <span m=\"1009050\"\
  >such</span> <span m=\"1009380\">that</span> <span m=\"1010670\">if</span> <span\
  \ m=\"1010820\">you</span> <span m=\"1010940\">look</span> <span m=\"1011270\">at</span>\
  \ <span m=\"1012740\">the</span> <span m=\"1012890\">first</span> <span m=\"1014060\"\
  >partition,</span> <span m=\"1014630\">the</span> <span m=\"1014720\">first</span>\
  \ <span m=\"1015290\">weak</span> <span m=\"1015560\">regularity</span> <span m=\"\
  1016190\">partition,</span> <span m=\"1017300\">they</span> <span m=\"1017420\"\
  >produce</span> <span m=\"1018230\">W1,1,</span> <span m=\"1019620\">W2,1,</span>\
  \ <span m=\"1021500\">W3,1,</span> <span m=\"1023780\">and</span> <span m=\"1023870\"\
  >so</span> <span m=\"1024050\">on.</span> <span m=\"1025079\">And</span> <span m=\"\
  1025670\">these</span> <span m=\"1025880\">guys,</span> <span m=\"1026560\">they</span>\
  \ <span m=\"1026780\">converge</span> <span m=\"1027349\">to</span> <span m=\"1028160\"\
  >u1,</span> <span m=\"1028910\">point-wise.</span> <span m=\"1035849\">The</span>\
  \ <span m=\"1036030\">second</span> <span m=\"1036359\">level,</span> <span m=\"\
  1037500\">W2,1--</span> <span m=\"1039695\">sorry,</span> <span m=\"1040140\">W1,2,</span>\
  \ <span m=\"1043170\">W2,2,</span> <span m=\"1045300\">W3,2,</span> <span m=\"1046550\"\
  >they</span> <span m=\"1046650\">converge</span> <span m=\"1047130\">to</span> <span\
  \ m=\"1047490\">u2,</span> <span m=\"1048000\">point-wise,</span> <span m=\"1052410\"\
  >and</span> <span m=\"1052540\">so</span> <span m=\"1052730\">on.</span></p><p><span\
  \ m=\"1066820\">OK,</span> <span m=\"1067930\">so</span> <span m=\"1068080\">far</span>\
  \ <span m=\"1068200\">so</span> <span m=\"1068320\">good?</span> <span m=\"1068893\"\
  >Question?</span></p><p><span m=\"1069800\">AUDIENCE:</span> <span m=\"1069930\"\
  >Sorry,</span> <span m=\"1070510\">earlier,</span> <span m=\"1070960\">why</span>\
  \ <span m=\"1071185\">did</span> <span m=\"1071410\">that</span> <span m=\"1072310\"\
  >converge to</span> <span m=\"1072760\">u1</span> <span m=\"1073210\">point-wise?</span></p><p><span\
  \ m=\"1074110\">YUFEI ZHAO:</span> <span m=\"1074150\">OK,</span> <span m=\"1075120\"\
  >so</span> <span m=\"1075360\">the</span> <span m=\"1075420\">question</span> <span\
  \ m=\"1075690\">is,</span> <span m=\"1075780\">why</span> <span m=\"1076080\">is</span>\
  \ <span m=\"1076230\">this</span> <span m=\"1076410\">true?</span> <span m=\"1076620\"\
  >Why</span> <span m=\"1076860\">is</span> <span m=\"1077970\">Wn,1</span> <span\
  \ m=\"1079170\">converge</span> <span m=\"1081680\">to</span> <span m=\"1081860\"\
  >u1</span> <span m=\"1082320\">point-wise?</span> <span m=\"1083490\">Initially,</span>\
  \ <span m=\"1083950\">it</span> <span m=\"1084030\">might</span> <span m=\"1084210\"\
  >not.</span> <span m=\"1085200\">But</span> <span m=\"1085490\">what</span> <span\
  \ m=\"1085650\">I'm</span> <span m=\"1085770\">saying</span> <span m=\"1086070\"\
  >is,</span> <span m=\"1086220\">you</span> <span m=\"1086310\">can</span> <span\
  \ m=\"1086490\">pass</span> <span m=\"1086910\">to a</span> <span m=\"1087090\"\
  >subsequence.</span></p><p><span m=\"1087900\">AUDIENCE:</span> <span m=\"1088072\"\
  >Yes.</span></p><p><span m=\"1089250\">YUFEI ZHAO:</span> <span m=\"1089280\">You</span>\
  \ <span m=\"1089310\">can</span> <span m=\"1089460\">pass</span> <span m=\"1089700\"\
  >to</span> <span m=\"1089790\">subsequence,</span> <span m=\"1090330\">because</span>\
  \ <span m=\"1090680\">there</span> <span m=\"1090770\">are</span> <span m=\"1090870\"\
  >only</span> <span m=\"1092060\">n1</span> <span m=\"1094730\">parts.</span> <span\
  \ m=\"1097800\">So</span> <span m=\"1098280\">it's</span> <span m=\"1098460\">an</span>\
  \ <span m=\"1099690\">n1</span> <span m=\"1100260\">by</span> <span m=\"1100530\"\
  >m1</span> <span m=\"1101280\">matrix</span> <span m=\"1101880\">of</span> <span\
  \ m=\"1102210\">real</span> <span m=\"1102450\">numbers.</span> <span m=\"1104500\"\
  >And</span> <span m=\"1104740\">so you</span> <span m=\"1105220\">only</span> <span\
  \ m=\"1105410\">have</span> <span m=\"1105560\">finite</span> <span m=\"1106090\"\
  >bounded</span> <span m=\"1106430\">many</span> <span m=\"1107320\">of</span> <span\
  \ m=\"1107440\">them.</span> <span m=\"1107720\">So</span> <span m=\"1108010\">you</span>\
  \ <span m=\"1108100\">can</span> <span m=\"1108220\">pick</span> <span m=\"1108430\"\
  >a</span> <span m=\"1108490\">subsequence</span> <span m=\"1109120\">so</span> <span\
  \ m=\"1109270\">that</span> <span m=\"1109420\">they</span> <span m=\"1109540\"\
  >converge.</span> <span m=\"1110285\">Yeah?</span></p><p><span m=\"1110580\">AUDIENCE:</span>\
  \ <span m=\"1110630\">So how do you</span> <span m=\"1110680\">make sure</span>\
  \ <span m=\"1111154\">that your</span> <span m=\"1111628\">subsequence</span> <span\
  \ m=\"1112102\">is</span> <span m=\"1112576\">not</span> <span m=\"1113524\">empty</span>\
  \ <span m=\"1113998\">at the</span> <span m=\"1114472\">end--</span> <span m=\"\
  1114946\">like,</span> <span m=\"1115420\">could</span> <span m=\"1115894\">you</span>\
  \ <span m=\"1116368\">fix the</span> <span m=\"1116842\">first</span> <span m=\"\
  1117316\">k?</span></p><p><span m=\"1117800\">YUFEI ZHAO:</span> <span m=\"1117955\"\
  >OK,</span> <span m=\"1118110\">so</span> <span m=\"1118290\">you're</span> <span\
  \ m=\"1118410\">asking,</span> <span m=\"1119760\">if</span> <span m=\"1119970\"\
  >we</span> <span m=\"1120180\">do</span> <span m=\"1120390\">this</span> <span m=\"\
  1121590\">slightly</span> <span m=\"1122790\">not</span> <span m=\"1123030\">so</span>\
  \ <span m=\"1123240\">carefully,</span> <span m=\"1124080\">we</span> <span m=\"\
  1124230\">might</span> <span m=\"1124380\">end</span> <span m=\"1124590\">up</span>\
  \ <span m=\"1124710\">with</span> <span m=\"1124860\">an</span> <span m=\"1124950\"\
  >empty</span> <span m=\"1125340\">sequence.</span> <span m=\"1126410\">So</span>\
  \ <span m=\"1126450\">this</span> <span m=\"1126600\">is</span> <span m=\"1126690\"\
  >why</span> <span m=\"1126900\">I</span> <span m=\"1126930\">say,</span> <span m=\"\
  1127110\">you</span> <span m=\"1127200\">have</span> <span m=\"1127290\">to</span>\
  \ <span m=\"1127380\">do</span> <span m=\"1127500\">a</span> <span m=\"1127600\"\
  >diagonalization</span> <span m=\"1128430\">argument.</span> <span m=\"1129240\"\
  >Each</span> <span m=\"1129450\">step,</span> <span m=\"1129870\">you</span> <span\
  \ m=\"1130020\">keep</span> <span m=\"1130980\">the</span> <span m=\"1131070\">first</span>\
  \ <span m=\"1131400\">term,</span> <span m=\"1131900\">the</span> <span m=\"1132030\"\
  >sequence,</span> <span m=\"1133170\">so</span> <span m=\"1133360\">that</span>\
  \ <span m=\"1133440\">you</span> <span m=\"1133560\">always</span> <span m=\"1133890\"\
  >maintain</span> <span m=\"1134310\">some</span> <span m=\"1134550\">sequence.</span>\
  \ <span m=\"1136440\">You</span> <span m=\"1136530\">have</span> <span m=\"1136620\"\
  >to</span> <span m=\"1136710\">be</span> <span m=\"1136800\">slightly</span> <span\
  \ m=\"1137130\">careful</span> <span m=\"1137520\">with</span> <span m=\"1137700\"\
  >diagonalization.</span> <span m=\"1140870\">Any</span> <span m=\"1141020\">more</span>\
  \ <span m=\"1141140\">questions?</span></p><p><span m=\"1146080\">So</span> <span\
  \ m=\"1146130\">by</span> <span m=\"1146260\">passing</span> <span m=\"1146670\"\
  >to</span> <span m=\"1146790\">a</span> <span m=\"1146850\">subsequence,</span>\
  \ <span m=\"1147750\">we</span> <span m=\"1147900\">obtain</span> <span m=\"1148260\"\
  >this</span> <span m=\"1148440\">very</span> <span m=\"1148650\">nice</span> <span\
  \ m=\"1148890\">sequence,</span> <span m=\"1149720\">this</span> <span m=\"1149970\"\
  >nice</span> <span m=\"1150180\">subsequence,</span> <span m=\"1151680\">such</span>\
  \ <span m=\"1152040\">that</span> <span m=\"1153270\">each</span> <span m=\"1153570\"\
  >row</span> <span m=\"1154230\">corresponding</span> <span m=\"1154860\">to</span>\
  \ <span m=\"1155070\">each</span> <span m=\"1155310\">level</span> <span m=\"1155670\"\
  >of</span> <span m=\"1155760\">regularization</span> <span m=\"1156960\">converges</span>\
  \ <span m=\"1157530\">point-wise</span> <span m=\"1158400\">to</span> <span m=\"\
  1158760\">some</span> <span m=\"1159480\">u.</span> <span m=\"1160740\">So</span>\
  \ <span m=\"1161050\">what</span> <span m=\"1161200\">do</span> <span m=\"1161290\"\
  >this</span> <span m=\"1161500\">u's</span> <span m=\"1161800\">look</span> <span\
  \ m=\"1162010\">like?</span> <span m=\"1163370\">So</span> <span m=\"1163420\">they</span>\
  \ <span m=\"1163560\">are</span> <span m=\"1164020\">step</span> <span m=\"1164580\"\
  >graphons.</span></p><p><span m=\"1167460\">So</span> <span m=\"1167580\">let's</span>\
  \ <span m=\"1167790\">explore</span> <span m=\"1168240\">the</span> <span m=\"1168360\"\
  >structure</span> <span m=\"1168810\">of</span> <span m=\"1168960\">u</span> <span\
  \ m=\"1169200\">a</span> <span m=\"1169290\">bit</span> <span m=\"1169440\">more.</span>\
  \ <span m=\"1176050\">OK,</span> <span m=\"1176260\">so</span> <span m=\"1176760\"\
  >since</span> <span m=\"1179490\">we</span> <span m=\"1179670\">have</span> <span\
  \ m=\"1180030\">that</span> <span m=\"1181110\">each--</span> <span m=\"1183880\"\
  >OK,</span> <span m=\"1184200\">so</span> <span m=\"1184370\">we</span> <span m=\"\
  1184520\">have</span> <span m=\"1184700\">the</span> <span m=\"1184760\">property</span>\
  \ <span m=\"1185270\">that</span> <span m=\"1185900\">each</span> <span m=\"1186470\"\
  >partition</span> <span m=\"1187070\">refines</span> <span m=\"1187670\">the</span>\
  \ <span m=\"1187760\">previous</span> <span m=\"1188150\">partition.</span> <span\
  \ m=\"1193190\">And</span> <span m=\"1193360\">as</span> <span m=\"1193490\">a</span>\
  \ <span m=\"1193550\">result,</span> <span m=\"1194880\">if</span> <span m=\"1194900\"\
  >you</span> <span m=\"1195050\">look</span> <span m=\"1195290\">at</span> <span\
  \ m=\"1195980\">the</span> <span m=\"1197120\">k</span> <span m=\"1197420\">plus</span>\
  \ <span m=\"1197780\">1'th</span> <span m=\"1199100\">stepping,</span> <span m=\"\
  1200680\">and</span> <span m=\"1200960\">I</span> <span m=\"1201110\">step</span>\
  \ <span m=\"1201500\">it</span> <span m=\"1201770\">by</span> <span m=\"1202790\"\
  >the</span> <span m=\"1202880\">previous</span> <span m=\"1205270\">partition</span>\
  \ <span m=\"1206050\">in</span> <span m=\"1206170\">the</span> <span m=\"1206260\"\
  >sequence,</span> <span m=\"1207490\">I</span> <span m=\"1207610\">should</span>\
  \ <span m=\"1208090\">get</span> <span m=\"1208270\">back,</span> <span m=\"1209460\"\
  >I</span> <span m=\"1209540\">should</span> <span m=\"1209890\">go</span> <span\
  \ m=\"1210710\">back</span> <span m=\"1211060\">one</span> <span m=\"1211390\">in</span>\
  \ <span m=\"1211480\">the</span> <span m=\"1211570\">sequence.</span></p><p><span\
  \ m=\"1214460\">So</span> <span m=\"1214580\">this</span> <span m=\"1214790\">was</span>\
  \ <span m=\"1215070\">this</span> <span m=\"1217510\">graphon</span> <span m=\"\
  1217990\">obtained</span> <span m=\"1218350\">by</span> <span m=\"1218500\">averaging</span>\
  \ <span m=\"1219280\">over</span> <span m=\"1219490\">the</span> <span m=\"1219610\"\
  >k'th</span> <span m=\"1219940\">partition.</span> <span m=\"1220870\">And</span>\
  \ <span m=\"1221020\">this</span> <span m=\"1221260\">is</span> <span m=\"1221410\"\
  >the</span> <span m=\"1222070\">graphon</span> <span m=\"1222770\">obtained</span>\
  \ <span m=\"1223220\">by</span> <span m=\"1223690\">averaging</span> <span m=\"\
  1224620\">over</span> <span m=\"1224830\">the</span> <span m=\"1224950\">k'th</span>\
  \ <span m=\"1225250\">plus</span> <span m=\"1226000\">1st</span> <span m=\"1226660\"\
  >partition.</span> <span m=\"1228070\">So</span> <span m=\"1228250\">if</span> <span\
  \ m=\"1228400\">I</span> <span m=\"1229330\">go</span> <span m=\"1229510\">back</span>\
  \ <span m=\"1229810\">one</span> <span m=\"1229990\">more,</span> <span m=\"1230320\"\
  >I</span> <span m=\"1230410\">should</span> <span m=\"1231980\">go</span> <span\
  \ m=\"1232130\">back</span> <span m=\"1232400\">in</span> <span m=\"1232520\">the</span>\
  \ <span m=\"1232580\">sequence.</span></p><p><span m=\"1235640\">And</span> <span\
  \ m=\"1235820\">since</span> <span m=\"1238800\">the</span> <span m=\"1238890\"\
  >u's</span> <span m=\"1239370\">are</span> <span m=\"1239610\">the</span> <span\
  \ m=\"1239730\">point-wise</span> <span m=\"1240420\">limit</span> <span m=\"1240840\"\
  >of</span> <span m=\"1240990\">these</span> <span m=\"1241530\">W's,</span> <span\
  \ m=\"1248250\">the</span> <span m=\"1248370\">same</span> <span m=\"1248700\">relationships</span>\
  \ <span m=\"1249390\">should</span> <span m=\"1249690\">also</span> <span m=\"1249990\"\
  >hold</span> <span m=\"1250530\">for</span> <span m=\"1250830\">the</span> <span\
  \ m=\"1250950\">u's,</span> <span m=\"1256330\">namely</span> <span m=\"1257170\"\
  >that</span> <span m=\"1258430\">u</span> <span m=\"1258720\">sub</span> <span m=\"\
  1258870\">k</span> <span m=\"1260050\">should</span> <span m=\"1260260\">equal</span>\
  \ <span m=\"1260770\">to</span> <span m=\"1264690\">u</span> <span m=\"1265020\"\
  >sub</span> <span m=\"1265230\">k</span> <span m=\"1265440\">plus</span> <span m=\"\
  1265710\">1</span> <span m=\"1266820\">if</span> <span m=\"1267000\">I</span> <span\
  \ m=\"1268150\">step</span> <span m=\"1268570\">it</span> <span m=\"1268890\">with</span>\
  \ <span m=\"1270060\">Pk,</span> <span m=\"1271890\">where</span> <span m=\"1274170\"\
  >Pk</span> <span m=\"1275010\">is</span> <span m=\"1276750\">the--</span> <span\
  \ m=\"1280020\">so</span> <span m=\"1280170\">if</span> <span m=\"1280320\">you</span>\
  \ <span m=\"1280380\">look</span> <span m=\"1280560\">at,</span> <span m=\"1281310\"\
  >all</span> <span m=\"1281490\">these</span> <span m=\"1281690\">endpoints</span>\
  \ <span m=\"1282150\">converge.</span> <span m=\"1282870\">And</span> <span m=\"\
  1283050\">these</span> <span m=\"1283260\">partitions,</span> <span m=\"1284340\"\
  >they</span> <span m=\"1284700\">converge</span> <span m=\"1285210\">to</span> <span\
  \ m=\"1285800\">P1.</span> <span m=\"1288550\">So</span> <span m=\"1288730\">if</span>\
  \ <span m=\"1288850\">you</span> <span m=\"1288940\">look</span> <span m=\"1289150\"\
  >at</span> <span m=\"1289690\">the</span> <span m=\"1290230\">partitions</span>\
  \ <span m=\"1291610\">that</span> <span m=\"1291730\">correspond</span> <span m=\"\
  1292360\">to</span> <span m=\"1293590\">P1,1,</span> <span m=\"1295130\">P2,1,</span>\
  \ <span m=\"1296760\">and so</span> <span m=\"1297040\">on,</span> <span m=\"1298000\"\
  >I</span> <span m=\"1298060\">want</span> <span m=\"1298270\">these</span> <span\
  \ m=\"1298450\">partitions</span> <span m=\"1299080\">to</span> <span m=\"1299230\"\
  >converge</span> <span m=\"1299740\">to</span> <span m=\"1300420\">P1.</span> <span\
  \ m=\"1301480\">I</span> <span m=\"1301540\">want</span> <span m=\"1303320\">these</span>\
  \ <span m=\"1303530\">partitions</span> <span m=\"1308550\">to</span> <span m=\"\
  1308640\">converge</span> <span m=\"1309120\">to</span> <span m=\"1310410\">P2.</span></p><p><span\
  \ m=\"1311460\">So</span> <span m=\"1312660\">all</span> <span m=\"1312840\">these</span>\
  \ <span m=\"1312990\">partitions,</span> <span m=\"1313590\">they</span> <span m=\"\
  1314100\">are</span> <span m=\"1314160\">partitions</span> <span m=\"1314640\">into</span>\
  \ <span m=\"1314880\">intervals.</span> <span m=\"1315780\">So</span> <span m=\"\
  1315880\">I'm</span> <span m=\"1315980\">just</span> <span m=\"1316020\">saying,</span>\
  \ <span m=\"1316410\">if</span> <span m=\"1316500\">you</span> <span m=\"1316590\"\
  >look</span> <span m=\"1316740\">at</span> <span m=\"1316830\">where</span> <span\
  \ m=\"1316980\">the</span> <span m=\"1317070\">intervals,</span> <span m=\"1317600\"\
  >where</span> <span m=\"1317790\">the</span> <span m=\"1317880\">divisions</span>\
  \ <span m=\"1318330\">of</span> <span m=\"1318420\">intervals</span> <span m=\"\
  1318830\">go,</span> <span m=\"1319350\">they</span> <span m=\"1319620\">converge.</span>\
  \ <span m=\"1320250\">And then</span> <span m=\"1320430\">I'm</span> <span m=\"\
  1320580\">calling</span> <span m=\"1320940\">the</span> <span m=\"1321030\">limit</span>\
  \ <span m=\"1321380\">partition</span> <span m=\"1322230\">P</span> <span m=\"1322530\"\
  >sub</span> <span m=\"1322620\">k.</span> <span m=\"1327810\">And</span> <span m=\"\
  1328350\">here</span> <span m=\"1328710\">we're</span> <span m=\"1328860\">using</span>\
  \ <span m=\"1329280\">that</span> <span m=\"1330480\">P</span> <span m=\"1330870\"\
  >sub</span> <span m=\"1331040\">k</span> <span m=\"1331260\">plus</span> <span m=\"\
  1331530\">1</span> <span m=\"1332970\">refines</span> <span m=\"1335290\">P</span>\
  \ <span m=\"1335540\">sub</span> <span m=\"1335640\">k,</span> <span m=\"1336240\"\
  >because</span> <span m=\"1337590\">the</span> <span m=\"1337680\">same</span> <span\
  \ m=\"1337950\">is</span> <span m=\"1338100\">true</span> <span m=\"1338280\">for</span>\
  \ <span m=\"1338430\">each</span> <span m=\"1338640\">end.</span> <span m=\"1338880\"\
  >So</span> <span m=\"1339030\">in</span> <span m=\"1339120\">the</span> <span m=\"\
  1339180\">limit,</span> <span m=\"1339600\">the</span> <span m=\"1339690\">same</span>\
  \ <span m=\"1339900\">must</span> <span m=\"1340080\">be</span> <span m=\"1340200\"\
  >true</span> <span m=\"1340380\">as</span> <span m=\"1340500\">well.</span></p><p><span\
  \ m=\"1345080\">So</span> <span m=\"1345100\">you</span> <span m=\"1345220\">have</span>\
  \ <span m=\"1345370\">this</span> <span m=\"1346150\">column</span> <span m=\"1346630\"\
  >of</span> <span m=\"1346750\">u's.</span> <span m=\"1347620\">So</span> <span m=\"\
  1347740\">let</span> <span m=\"1347830\">me</span> <span m=\"1347920\">draw</span>\
  \ <span m=\"1348130\">you</span> <span m=\"1348250\">a</span> <span m=\"1348280\"\
  >picture</span> <span m=\"1348610\">of</span> <span m=\"1348700\">what</span> <span\
  \ m=\"1349240\">these</span> <span m=\"1349450\">u's</span> <span m=\"1350440\"\
  >could</span> <span m=\"1350650\">look</span> <span m=\"1350860\">like.</span> <span\
  \ m=\"1353120\">So</span> <span m=\"1353160\">here is</span> <span m=\"1353400\"\
  >an</span> <span m=\"1353520\">illustration</span> <span m=\"1354060\">that</span>\
  \ <span m=\"1354180\">may</span> <span m=\"1354330\">be</span> <span m=\"1354450\"\
  >helpful.</span> <span m=\"1360980\">So</span> <span m=\"1361460\">what</span> <span\
  \ m=\"1361640\">could</span> <span m=\"1361820\">these</span> <span m=\"1362000\"\
  >u's</span> <span m=\"1362240\">look</span> <span m=\"1362420\">like?</span> <span\
  \ m=\"1363830\">Each</span> <span m=\"1364040\">one</span> <span m=\"1364220\">of</span>\
  \ <span m=\"1364280\">them</span> <span m=\"1364820\">is</span> <span m=\"1367520\"\
  >represented</span> <span m=\"1368180\">by</span> <span m=\"1368660\">values</span>\
  \ <span m=\"1369380\">on</span> <span m=\"1369560\">the</span> <span m=\"1369650\"\
  >unit</span> <span m=\"1369950\">square.</span> <span m=\"1371390\">And</span> <span\
  \ m=\"1371840\">I</span> <span m=\"1371960\">write</span> <span m=\"1372230\">this</span>\
  \ <span m=\"1372400\">in</span> <span m=\"1372500\">matrix</span> <span m=\"1372950\"\
  >notation</span> <span m=\"1373520\">so</span> <span m=\"1373670\">that</span> <span\
  \ m=\"1373870\">inversion</span> <span m=\"1374210\">is</span> <span m=\"1374420\"\
  >in</span> <span m=\"1374600\">the</span> <span m=\"1374690\">top</span> <span m=\"\
  1374960\">left</span> <span m=\"1375170\">corner.</span></p><p><span m=\"1380180\"\
  >Well,</span> <span m=\"1380720\">maybe</span> <span m=\"1381590\">P1</span> <span\
  \ m=\"1382190\">is</span> <span m=\"1382430\">just</span> <span m=\"1382760\">the</span>\
  \ <span m=\"1383390\">trivial</span> <span m=\"1383840\">partition,</span> <span\
  \ m=\"1385400\">in</span> <span m=\"1385490\">which</span> <span m=\"1385670\">case</span>\
  \ <span m=\"1386450\">u1</span> <span m=\"1386960\">is</span> <span m=\"1387200\"\
  >going</span> <span m=\"1387380\">to</span> <span m=\"1387470\">be</span> <span\
  \ m=\"1387590\">a</span> <span m=\"1387650\">constant</span> <span m=\"1388130\"\
  >graphon.</span> <span m=\"1388910\">Let's</span> <span m=\"1389090\">say</span>\
  \ <span m=\"1389340\">it</span> <span m=\"1389470\">has</span> <span m=\"1389660\"\
  >value</span> <span m=\"1390380\">0.5.</span> <span m=\"1394630\">u2</span> <span\
  \ m=\"1396430\">came</span> <span m=\"1396730\">from</span> <span m=\"1396970\"\
  >u1</span> <span m=\"1397600\">by</span> <span m=\"1397960\">some</span> <span m=\"\
  1398440\">partitioning.</span> <span m=\"1399300\">And</span> <span m=\"1399400\"\
  >suppose</span> <span m=\"1399670\">just</span> <span m=\"1399880\">for</span> <span\
  \ m=\"1400030\">the</span> <span m=\"1400120\">sake</span> <span m=\"1400360\">of</span>\
  \ <span m=\"1400420\">illustration,</span> <span m=\"1401290\">there</span> <span\
  \ m=\"1401410\">was</span> <span m=\"1401560\">only</span> <span m=\"1401770\">a</span>\
  \ <span m=\"1401800\">partitioning</span> <span m=\"1402310\">into</span> <span\
  \ m=\"1402550\">two</span> <span m=\"1402760\">parts.</span></p><p><span m=\"1406950\"\
  >And</span> <span m=\"1407690\">OK,</span> <span m=\"1408090\">so</span> <span m=\"\
  1408450\">it</span> <span m=\"1408540\">doesn't</span> <span m=\"1408750\">have</span>\
  \ <span m=\"1408930\">to</span> <span m=\"1409020\">be</span> <span m=\"1409520\"\
  >at the</span> <span m=\"1409730\">origin.</span> <span m=\"1410250\">It</span>\
  \ <span m=\"1410340\">doesn't</span> <span m=\"1410550\">have</span> <span m=\"\
  1410670\">to</span> <span m=\"1410730\">be</span> <span m=\"1410880\">at</span>\
  \ <span m=\"1411000\">midpoint.</span> <span m=\"1411540\">But</span> <span m=\"\
  1411780\">just</span> <span m=\"1411960\">for</span> <span m=\"1412110\">illustration,</span>\
  \ <span m=\"1412650\">suppose</span> <span m=\"1413040\">the</span> <span m=\"1413130\"\
  >division</span> <span m=\"1413550\">were</span> <span m=\"1413710\">at the</span>\
  \ <span m=\"1413910\">midpoint.</span> <span m=\"1416800\">Because</span> <span\
  \ m=\"1418090\">u1</span> <span m=\"1418780\">needs</span> <span m=\"1419080\">to</span>\
  \ <span m=\"1419170\">have--</span> <span m=\"1420520\">so</span> <span m=\"1421730\"\
  >this</span> <span m=\"1421970\">0.5</span> <span m=\"1422480\">value</span> <span\
  \ m=\"1422810\">should</span> <span m=\"1423050\">be</span> <span m=\"1423170\"\
  >the</span> <span m=\"1423270\">average</span> <span m=\"1423740\">value</span>\
  \ <span m=\"1424220\">in</span> <span m=\"1424430\">all</span> <span m=\"1424610\"\
  >of</span> <span m=\"1424670\">these</span> <span m=\"1424850\">four</span> <span\
  \ m=\"1425060\">squares.</span></p><p><span m=\"1426530\">So</span> <span m=\"1426680\"\
  >for</span> <span m=\"1426830\">instance,</span> <span m=\"1427640\">the</span>\
  \ <span m=\"1428660\">points</span> <span m=\"1429450\">may</span> <span m=\"1429680\"\
  >be</span> <span m=\"1430250\">like</span> <span m=\"1431980\">0.6,</span> <span\
  \ m=\"1433230\">0.6,</span> <span m=\"1434600\">0.4,</span> <span m=\"1436610\"\
  >0.4,</span> <span m=\"1439020\">so</span> <span m=\"1439500\">for</span> <span\
  \ m=\"1439680\">example.</span> <span m=\"1441900\">And in</span> <span m=\"1442060\"\
  >u3,</span> <span m=\"1444510\">the</span> <span m=\"1444810\">partition,</span>\
  \ <span m=\"1446720\">the</span> <span m=\"1446920\">P3</span> <span m=\"1447450\"\
  >partition--</span> <span m=\"1448260\">so</span> <span m=\"1448610\">here</span>\
  \ <span m=\"1448820\">are</span> <span m=\"1448860\">the</span> <span m=\"1448950\"\
  >partition is</span> <span m=\"1449580\">P1.</span> <span m=\"1450120\">The</span>\
  \ <span m=\"1450420\">partition is</span> <span m=\"1450960\">P2.</span> <span m=\"\
  1451740\">There's</span> <span m=\"1452250\">two</span> <span m=\"1452400\">parts.</span>\
  \ <span m=\"1453070\">And</span> <span m=\"1453270\">suppose</span> <span m=\"1453630\"\
  >P3</span> <span m=\"1454980\">three</span> <span m=\"1455910\">now</span> <span\
  \ m=\"1456120\">has</span> <span m=\"1457260\">four</span> <span m=\"1457500\">parts.</span>\
  \ <span m=\"1458330\">And</span> <span m=\"1458430\">again,</span> <span m=\"1458640\"\
  >for</span> <span m=\"1458790\">illustration's</span> <span m=\"1459090\">sake,</span>\
  \ <span m=\"1459600\">suppose</span> <span m=\"1460050\">it</span> <span m=\"1460200\"\
  >is</span> <span m=\"1460710\">equally</span> <span m=\"1461100\">dividing</span>\
  \ <span m=\"1461610\">the</span> <span m=\"1461730\">interval</span> <span m=\"\
  1462120\">into</span> <span m=\"1462330\">four</span> <span m=\"1462690\">intervals.</span></p><p><span\
  \ m=\"1465000\">It</span> <span m=\"1465090\">could</span> <span m=\"1465240\">be</span>\
  \ <span m=\"1465720\">that</span> <span m=\"1466170\">now</span> <span m=\"1467190\"\
  >each</span> <span m=\"1467430\">of</span> <span m=\"1467550\">these</span> <span\
  \ m=\"1467760\">parts</span> <span m=\"1468960\">is</span> <span m=\"1469350\">split</span>\
  \ <span m=\"1469800\">up</span> <span m=\"1470130\">into</span> <span m=\"1470880\"\
  >four</span> <span m=\"1471210\">different</span> <span m=\"1471570\">values</span>\
  \ <span m=\"1472500\">in</span> <span m=\"1472610\">a</span> <span m=\"1472680\"\
  >way</span> <span m=\"1472950\">that</span> <span m=\"1473670\">so</span> <span\
  \ m=\"1474030\">you</span> <span m=\"1474150\">can</span> <span m=\"1474360\">obtain</span>\
  \ <span m=\"1474780\">the</span> <span m=\"1474990\">original</span> <span m=\"\
  1475380\">numbers</span> <span m=\"1475800\">by</span> <span m=\"1476610\">averaging.</span>\
  \ <span m=\"1480560\">So</span> <span m=\"1480740\">that's</span> <span m=\"1481160\"\
  >one</span> <span m=\"1481400\">possible</span> <span m=\"1482030\">example.</span>\
  \ <span m=\"1484010\">Likewise,</span> <span m=\"1485480\">you</span> <span m=\"\
  1485570\">can</span> <span m=\"1485750\">have</span> <span m=\"1487112\">something</span>\
  \ <span m=\"1489542\">like that.</span> <span m=\"1494888\">Sorry,</span> <span\
  \ m=\"1495860\">4,</span> <span m=\"1498290\">7--</span> <span m=\"1502178\">so</span>\
  \ <span m=\"1503670\">and</span> <span m=\"1503860\">I</span> <span m=\"1503980\"\
  >should</span> <span m=\"1505450\">maintain</span> <span m=\"1506590\">symmetry</span>\
  \ <span m=\"1507220\">in</span> <span m=\"1507340\">this</span> <span m=\"1507550\"\
  >matrix.</span></p><p><span m=\"1508990\">And</span> <span m=\"1509630\">the</span>\
  \ <span m=\"1509850\">last</span> <span m=\"1510140\">one,</span> <span m=\"1510290\"\
  >I'm</span> <span m=\"1510370\">just</span> <span m=\"1510520\">going</span> <span\
  \ m=\"1510640\">to</span> <span m=\"1510700\">be</span> <span m=\"1510790\">lazy</span>\
  \ <span m=\"1511210\">and</span> <span m=\"1511420\">say</span> <span m=\"1511520\"\
  >that</span> <span m=\"1511770\">it's</span> <span m=\"1512980\">still</span> <span\
  \ m=\"1513250\">0.4</span> <span m=\"1513520\">throughout.</span> <span m=\"1515960\"\
  >OK,</span> <span m=\"1516240\">so</span> <span m=\"1516360\">this</span> <span\
  \ m=\"1516540\">is</span> <span m=\"1516720\">what</span> <span m=\"1517080\">the</span>\
  \ <span m=\"1517230\">sequence</span> <span m=\"1517770\">of</span> <span m=\"1517890\"\
  >u's</span> <span m=\"1518190\">are</span> <span m=\"1518280\">going</span> <span\
  \ m=\"1518490\">to</span> <span m=\"1518580\">look</span> <span m=\"1518790\">like.</span>\
  \ <span m=\"1520080\">Each</span> <span m=\"1520350\">one</span> <span m=\"1520500\"\
  >of</span> <span m=\"1520560\">them</span> <span m=\"1521400\">splits</span> <span\
  \ m=\"1522000\">up</span> <span m=\"1522750\">a</span> <span m=\"1522810\">box</span>\
  \ <span m=\"1523530\">in</span> <span m=\"1523620\">the</span> <span m=\"1523680\"\
  >previous</span> <span m=\"1524100\">u</span> <span m=\"1524850\">in</span> <span\
  \ m=\"1524940\">such</span> <span m=\"1525360\">way</span> <span m=\"1525660\">that</span>\
  \ <span m=\"1525930\">the</span> <span m=\"1526800\">local</span> <span m=\"1527400\"\
  >averages,</span> <span m=\"1527900\">the</span> <span m=\"1527970\">step</span>\
  \ <span m=\"1528300\">averages</span> <span m=\"1528900\">are</span> <span m=\"\
  1528990\">preserved.</span> <span m=\"1531700\">Any</span> <span m=\"1531880\">questions</span>\
  \ <span m=\"1532210\">so</span> <span m=\"1532390\">far?</span></p><p><span m=\"\
  1535410\">All right,</span> <span m=\"1539650\">so</span> <span m=\"1539750\">now</span>\
  \ <span m=\"1539930\">we</span> <span m=\"1540050\">get</span> <span m=\"1540170\"\
  >to</span> <span m=\"1540270\">Martingales.</span> <span m=\"1541270\">So</span>\
  \ <span m=\"1541470\">I</span> <span m=\"1542150\">claim</span> <span m=\"1542510\"\
  >that</span> <span m=\"1542930\">this</span> <span m=\"1543170\">is</span> <span\
  \ m=\"1543290\">basically</span> <span m=\"1543620\">a</span> <span m=\"1543680\"\
  >Martingale.</span> <span m=\"1545870\">So and</span> <span m=\"1547280\">suppose</span>\
  \ <span m=\"1547760\">you</span> <span m=\"1547910\">let</span> <span m=\"1549680\"\
  >x, y</span> <span m=\"1550730\">be</span> <span m=\"1551000\">a</span> <span m=\"\
  1551090\">uniform</span> <span m=\"1553738\">point</span> <span m=\"1556080\">in</span>\
  \ <span m=\"1556240\">the</span> <span m=\"1556360\">unit</span> <span m=\"1556630\"\
  >square.</span> <span m=\"1559930\">And</span> <span m=\"1561940\">consider</span>\
  \ <span m=\"1564040\">this</span> <span m=\"1564210\">sequence.</span> <span m=\"\
  1565220\">So</span> <span m=\"1565270\">this</span> <span m=\"1565480\">is</span>\
  \ <span m=\"1565570\">now</span> <span m=\"1565900\">a</span> <span m=\"1566050\"\
  >random</span> <span m=\"1566590\">sequence,</span> <span m=\"1567190\">because</span>\
  \ <span m=\"1568030\">x, y</span> <span m=\"1568780\">are</span> <span m=\"1568870\"\
  >random.</span> <span m=\"1572030\">I</span> <span m=\"1572210\">evaluate</span>\
  \ <span m=\"1573080\">these</span> <span m=\"1573620\">u's</span> <span m=\"1574370\"\
  >on</span> <span m=\"1574550\">this</span> <span m=\"1575180\">uniform</span> <span\
  \ m=\"1575600\">random</span> <span m=\"1575870\">point,</span> <span m=\"1576260\"\
  >x,</span> <span m=\"1576710\">y.</span> <span m=\"1577840\">So</span> <span m=\"\
  1577940\">this</span> <span m=\"1578120\">is</span> <span m=\"1578210\">a</span>\
  \ <span m=\"1578270\">random</span> <span m=\"1578690\">sequence.</span></p><p><span\
  \ m=\"1583800\">And</span> <span m=\"1584220\">the</span> <span m=\"1584310\">main</span>\
  \ <span m=\"1584670\">observation</span> <span m=\"1585420\">is</span> <span m=\"\
  1585570\">that</span> <span m=\"1586140\">this</span> <span m=\"1586320\">is</span>\
  \ <span m=\"1586440\">a</span> <span m=\"1586520\">Martingale.</span> <span m=\"\
  1594320\">So</span> <span m=\"1594550\">remember</span> <span m=\"1594910\">the</span>\
  \ <span m=\"1595000\">definition</span> <span m=\"1595570\">of</span> <span m=\"\
  1595660\">a</span> <span m=\"1595720\">Martingale</span> <span m=\"1596270\">from</span>\
  \ <span m=\"1596410\">last</span> <span m=\"1596710\">time.</span> <span m=\"1598450\"\
  >Martingale</span> <span m=\"1598960\">is</span> <span m=\"1599110\">one</span>\
  \ <span m=\"1599470\">where,</span> <span m=\"1602420\">if</span> <span m=\"1602570\"\
  >you</span> <span m=\"1602720\">look</span> <span m=\"1602990\">at</span> <span\
  \ m=\"1603590\">the</span> <span m=\"1603800\">value</span> <span m=\"1604460\"\
  >of</span> <span m=\"1605300\">u sub</span> <span m=\"1605690\">k</span> <span m=\"\
  1606710\">conditioned</span> <span m=\"1607430\">on</span> <span m=\"1607610\">the</span>\
  \ <span m=\"1607670\">previous</span> <span m=\"1608150\">values,</span> <span m=\"\
  1612490\">the</span> <span m=\"1612620\">expectation</span> <span m=\"1613730\"\
  >is</span> <span m=\"1613940\">just</span> <span m=\"1614300\">the</span> <span\
  \ m=\"1614420\">previous</span> <span m=\"1614840\">term.</span> <span m=\"1616190\"\
  >And</span> <span m=\"1616310\">I</span> <span m=\"1616370\">claim</span> <span\
  \ m=\"1616670\">this</span> <span m=\"1616850\">is</span> <span m=\"1616970\">true</span>\
  \ <span m=\"1618080\">for</span> <span m=\"1618230\">the</span> <span m=\"1618320\"\
  >sequence,</span> <span m=\"1618770\">because</span> <span m=\"1619160\">of</span>\
  \ <span m=\"1619250\">the</span> <span m=\"1619310\">way</span> <span m=\"1619490\"\
  >we</span> <span m=\"1619770\">constructed it,</span> <span m=\"1620035\">it's</span>\
  \ <span m=\"1620300\">splitting</span> <span m=\"1620930\">up</span> <span m=\"\
  1621080\">each</span> <span m=\"1621260\">box</span> <span m=\"1622220\">in</span>\
  \ <span m=\"1622370\">an</span> <span m=\"1622610\">averaging-preserving</span>\
  \ <span m=\"1623570\">way.</span></p><p><span m=\"1627380\">A</span> <span m=\"\
  1627440\">different</span> <span m=\"1627740\">way</span> <span m=\"1627830\">to</span>\
  \ <span m=\"1627920\">see</span> <span m=\"1628130\">this,</span> <span m=\"1628730\"\
  >and</span> <span m=\"1628880\">for</span> <span m=\"1629030\">those</span> <span\
  \ m=\"1629210\">of</span> <span m=\"1629330\">you</span> <span m=\"1629420\">who</span>\
  \ <span m=\"1629750\">actually</span> <span m=\"1630080\">know</span> <span m=\"\
  1630260\">what</span> <span m=\"1630410\">the</span> <span m=\"1630470\">definition</span>\
  \ <span m=\"1631010\">of</span> <span m=\"1631100\">a</span> <span m=\"1631160\"\
  >random</span> <span m=\"1631550\">variable</span> <span m=\"1632030\">is</span>\
  \ <span m=\"1632240\">in</span> <span m=\"1632330\">the</span> <span m=\"1632390\"\
  >sense</span> <span m=\"1632620\">of</span> <span m=\"1632690\">probability</span>\
  \ <span m=\"1633200\">theory,</span> <span m=\"1633920\">is</span> <span m=\"1634040\"\
  >that</span> <span m=\"1634250\">you</span> <span m=\"1634370\">should</span> <span\
  \ m=\"1634550\">view</span> <span m=\"1638220\">this</span> <span m=\"1638640\"\
  >0,</span> <span m=\"1638880\">1</span> <span m=\"1639330\">squared</span> <span\
  \ m=\"1640110\">as</span> <span m=\"1640380\">the</span> <span m=\"1640500\">probability</span>\
  \ <span m=\"1641160\">space,</span> <span m=\"1643830\">in</span> <span m=\"1643920\"\
  >which</span> <span m=\"1644130\">case</span> <span m=\"1645030\">u</span> <span\
  \ m=\"1645280\">itself</span> <span m=\"1646110\">is</span> <span m=\"1646440\"\
  >the</span> <span m=\"1646560\">random</span> <span m=\"1646860\">variable.</span>\
  \ <span m=\"1650050\">And</span> <span m=\"1650190\">this</span> <span m=\"1650400\"\
  >partitioning</span> <span m=\"1651360\">gives</span> <span m=\"1651660\">you</span>\
  \ <span m=\"1652260\">a</span> <span m=\"1652350\">filtration</span> <span m=\"\
  1653070\">of</span> <span m=\"1653190\">the</span> <span m=\"1653280\">space.</span>\
  \ <span m=\"1654480\">It's</span> <span m=\"1654600\">a</span> <span m=\"1654660\"\
  >sequence</span> <span m=\"1655170\">of</span> <span m=\"1655260\">sigma</span>\
  \ <span m=\"1655650\">algebras</span> <span m=\"1656460\">dividing</span> <span\
  \ m=\"1656910\">up</span> <span m=\"1657030\">the</span> <span m=\"1657090\">space</span>\
  \ <span m=\"1657450\">into</span> <span m=\"1657630\">finer</span> <span m=\"1657960\"\
  >and</span> <span m=\"1658050\">finer</span> <span m=\"1658320\">pieces.</span></p><p><span\
  \ m=\"1659590\">So</span> <span m=\"1659610\">this</span> <span m=\"1659760\">is</span>\
  \ <span m=\"1659850\">really</span> <span m=\"1660120\">what</span> <span m=\"1660300\"\
  >a</span> <span m=\"1660360\">martingale</span> <span m=\"1660910\">is.</span> <span\
  \ m=\"1663280\">So</span> <span m=\"1663690\">we</span> <span m=\"1663870\">have</span>\
  \ <span m=\"1664050\">a</span> <span m=\"1664110\">Martingale.</span> <span m=\"\
  1665710\">It's</span> <span m=\"1665890\">bounded</span> <span m=\"1670480\">because</span>\
  \ <span m=\"1671140\">the</span> <span m=\"1671230\">values</span> <span m=\"1673380\"\
  >take</span> <span m=\"1673560\">place</span> <span m=\"1674790\">in</span> <span\
  \ m=\"1674940\">0,</span> <span m=\"1675180\">1.</span> <span m=\"1676770\">So</span>\
  \ <span m=\"1677670\">by</span> <span m=\"1678000\">the</span> <span m=\"1678600\"\
  >Martingale</span> <span m=\"1679200\">convergence</span> <span m=\"1679860\">theorem,</span>\
  \ <span m=\"1680340\">which</span> <span m=\"1680550\">we</span> <span m=\"1680670\"\
  >proved</span> <span m=\"1681000\">last</span> <span m=\"1681270\">time,</span>\
  \ <span m=\"1692380\">we</span> <span m=\"1692430\">find</span> <span m=\"1693360\"\
  >that</span> <span m=\"1694080\">this</span> <span m=\"1694240\">sequence</span>\
  \ <span m=\"1695370\">must</span> <span m=\"1696030\">converge</span> <span m=\"\
  1697260\">to</span> <span m=\"1697800\">some</span> <span m=\"1698400\">limit.</span>\
  \ <span m=\"1701550\">So</span> <span m=\"1701700\">this</span> <span m=\"1702090\"\
  >sequence</span> <span m=\"1702510\">of</span> <span m=\"1702570\">Martingale</span>\
  \ <span m=\"1703040\">converges,</span> <span m=\"1704970\">which</span> <span m=\"\
  1705180\">means,</span> <span m=\"1706610\">so</span> <span m=\"1708170\">if</span>\
  \ <span m=\"1708290\">you</span> <span m=\"1708440\">think</span> <span m=\"1708620\"\
  >about</span> <span m=\"1708800\">the</span> <span m=\"1708890\">interpretation</span>\
  \ <span m=\"1709490\">up</span> <span m=\"1709600\">there,</span> <span m=\"1710240\"\
  >so</span> <span m=\"1711080\">there</span> <span m=\"1711290\">exists</span> <span\
  \ m=\"1712320\">a</span> <span m=\"1712440\">u</span> <span m=\"1713270\">which</span>\
  \ <span m=\"1713480\">is</span> <span m=\"1713630\">a</span> <span m=\"1713850\"\
  >graphon</span> <span m=\"1718320\">such</span> <span m=\"1718650\">that</span>\
  \ <span m=\"1721970\">uk</span> <span m=\"1722780\">converges</span> <span m=\"\
  1723350\">to</span> <span m=\"1723470\">u</span> <span m=\"1724430\">point-wise</span>\
  \ <span m=\"1725210\">almost</span> <span m=\"1725570\">everywhere</span> <span\
  \ m=\"1729310\">as</span> <span m=\"1729500\">k</span> <span m=\"1729830\">goes</span>\
  \ <span m=\"1730070\">to</span> <span m=\"1730160\">infinity.</span></p><p><span\
  \ m=\"1737410\">That's</span> <span m=\"1737580\">the</span> <span m=\"1737700\"\
  >limit.</span> <span m=\"1739000\">So</span> <span m=\"1739320\">this</span> <span\
  \ m=\"1740280\">is</span> <span m=\"1740370\">the</span> <span m=\"1740460\">limit.</span>\
  \ <span m=\"1740910\">And</span> <span m=\"1741030\">we're</span> <span m=\"1741270\"\
  >going</span> <span m=\"1741350\">to</span> <span m=\"1741450\">show</span> <span\
  \ m=\"1741690\">that</span> <span m=\"1741840\">it</span> <span m=\"1741930\">is</span>\
  \ <span m=\"1742050\">indeed</span> <span m=\"1742350\">a</span> <span m=\"1742440\"\
  >limit.</span> <span m=\"1742980\">But</span> <span m=\"1743050\">you</span> <span\
  \ m=\"1743090\">see,</span> <span m=\"1743280\">this</span> <span m=\"1743460\"\
  >is</span> <span m=\"1743580\">a</span> <span m=\"1743640\">construction</span>\
  \ <span m=\"1744300\">of</span> <span m=\"1744390\">the</span> <span m=\"1744510\"\
  >limit,</span> <span m=\"1745110\">where</span> <span m=\"1745260\">we</span> <span\
  \ m=\"1745440\">took</span> <span m=\"1746040\">regularity,</span> <span m=\"1747780\"\
  >got</span> <span m=\"1747990\">all</span> <span m=\"1748140\">these</span> <span\
  \ m=\"1748320\">nice</span> <span m=\"1748560\">pieces,</span> <span m=\"1748950\"\
  >found</span> <span m=\"1749250\">convergent</span> <span m=\"1749760\">subsequences,</span>\
  \ <span m=\"1750900\">and</span> <span m=\"1750990\">then</span> <span m=\"1751140\"\
  >applied</span> <span m=\"1751500\">the</span> <span m=\"1751680\">martingale</span>\
  \ <span m=\"1753630\">convergence</span> <span m=\"1754140\">theorem</span> <span\
  \ m=\"1754650\">to</span> <span m=\"1754800\">produce</span> <span m=\"1755340\"\
  >for</span> <span m=\"1755550\">us</span> <span m=\"1755910\">this</span> <span\
  \ m=\"1756690\">candidate</span> <span m=\"1757290\">for</span> <span m=\"1757440\"\
  >the</span> <span m=\"1757530\">limit,</span> <span m=\"1757830\">this</span> <span\
  \ m=\"1758276\">u.</span></p><p><span m=\"1759170\">So</span> <span m=\"1759570\"\
  >now</span> <span m=\"1759780\">let</span> <span m=\"1759960\">us</span> <span m=\"\
  1760050\">show</span> <span m=\"1764860\">that</span> <span m=\"1765190\">it</span>\
  \ <span m=\"1765340\">is</span> <span m=\"1765490\">indeed</span> <span m=\"1766960\"\
  >the</span> <span m=\"1767770\">limit</span> <span m=\"1768220\">that</span> <span\
  \ m=\"1768370\">we're</span> <span m=\"1768520\">looking</span> <span m=\"1768790\"\
  >for</span> <span m=\"1771350\">in</span> <span m=\"1772510\">the</span> <span m=\"\
  1772630\">subsequence.</span> <span m=\"1773650\">So</span> <span m=\"1774130\"\
  >again,</span> <span m=\"1774330\">I've</span> <span m=\"1774850\">tossed</span>\
  \ <span m=\"1775270\">out</span> <span m=\"1775510\">all</span> <span m=\"1775660\"\
  >the</span> <span m=\"1776930\">terms</span> <span m=\"1777500\">which</span> <span\
  \ m=\"1778460\">we</span> <span m=\"1778970\">removed</span> <span m=\"1779780\"\
  >in</span> <span m=\"1779930\">passing</span> <span m=\"1780380\">to</span> <span\
  \ m=\"1780470\">subsequences.</span> <span m=\"1781510\">So</span> <span m=\"1781670\"\
  >in</span> <span m=\"1781760\">the</span> <span m=\"1781850\">remaining</span> <span\
  \ m=\"1782270\">subsequence,</span> <span m=\"1783230\">I</span> <span m=\"1783290\"\
  >want</span> <span m=\"1783470\">to</span> <span m=\"1783560\">show</span> <span\
  \ m=\"1783800\">that</span> <span m=\"1784220\">the</span> <span m=\"1784400\">Wn's</span>\
  \ <span m=\"1785300\">indeed</span> <span m=\"1785630\">converge</span> <span m=\"\
  1786080\">to</span> <span m=\"1786430\">u.</span></p><p><span m=\"1788920\">And</span>\
  \ <span m=\"1789190\">this</span> <span m=\"1789370\">is</span> <span m=\"1789550\"\
  >now</span> <span m=\"1790090\">a</span> <span m=\"1790150\">fairly</span> <span\
  \ m=\"1790450\">straightforward</span> <span m=\"1791170\">three</span> <span m=\"\
  1791530\">epsilons</span> <span m=\"1792130\">argument,</span> <span m=\"1792580\"\
  >the</span> <span m=\"1792640\">standard</span> <span m=\"1793720\">analysis</span>\
  \ <span m=\"1795110\">type</span> <span m=\"1795460\">argument.</span> <span m=\"\
  1795910\">But</span> <span m=\"1796030\">OK,</span> <span m=\"1796250\">so</span>\
  \ <span m=\"1796330\">let's</span> <span m=\"1796660\">carry</span> <span m=\"1796990\"\
  >it</span> <span m=\"1797080\">through.</span> <span m=\"1797630\">So</span> <span\
  \ m=\"1798280\">for</span> <span m=\"1798490\">every</span> <span m=\"1799240\"\
  >epsilon</span> <span m=\"1800050\">bigger</span> <span m=\"1800290\">than</span>\
  \ <span m=\"1800440\">0,</span> <span m=\"1801370\">suppose</span> <span m=\"1802330\"\
  >you</span> <span m=\"1803710\">pick</span> <span m=\"1804370\">a</span> <span m=\"\
  1804730\">sufficiently</span> <span m=\"1805300\">large</span> <span m=\"1806040\"\
  >k.</span> <span m=\"1808360\">There</span> <span m=\"1808540\">exists</span> <span\
  \ m=\"1808960\">a</span> <span m=\"1809020\">sufficiently</span> <span m=\"1809530\"\
  >large</span> <span m=\"1809800\">k.</span> <span m=\"1811170\">And</span> <span\
  \ m=\"1811340\">we</span> <span m=\"1813200\">make</span> <span m=\"1813320\">sure</span>\
  \ <span m=\"1813470\">k</span> <span m=\"1813710\">is</span> <span m=\"1813830\"\
  >large</span> <span m=\"1814100\">enough</span> <span m=\"1817010\">such</span>\
  \ <span m=\"1817310\">that</span> <span m=\"1818120\">u</span> <span m=\"1819080\"\
  >differs</span> <span m=\"1819800\">from</span> <span m=\"1820690\">u sub</span>\
  \ <span m=\"1820830\">k</span> <span m=\"1821600\">in l1</span> <span m=\"1821870\"\
  >norm</span> <span m=\"1822880\">by,</span> <span m=\"1824196\">at</span> <span\
  \ m=\"1824660\">most,</span> <span m=\"1825200\">epsilon</span> <span m=\"1825620\"\
  >over</span> <span m=\"1825880\">3,</span> <span m=\"1826790\">because</span> <span\
  \ m=\"1827555\">the</span> <span m=\"1827900\">uk's,</span> <span m=\"1828400\"\
  >they</span> <span m=\"1828530\">converge</span> <span m=\"1828980\">to</span> <span\
  \ m=\"1829070\">u</span> <span m=\"1829580\">point-wise</span> <span m=\"1830150\"\
  >almost</span> <span m=\"1830510\">everywhere.</span></p><p><span m=\"1832090\"\
  >So</span> <span m=\"1832250\">we</span> <span m=\"1832380\">find</span> <span m=\"\
  1832620\">this</span> <span m=\"1832740\">k.</span> <span m=\"1833150\">So</span>\
  \ <span m=\"1833250\">let's</span> <span m=\"1833370\">fix</span> <span m=\"1833670\"\
  >this</span> <span m=\"1833850\">k.</span> <span m=\"1839220\">Then</span> <span\
  \ m=\"1840270\">there</span> <span m=\"1840450\">exists</span> <span m=\"1841080\"\
  >an</span> <span m=\"1841570\">n0</span> <span m=\"1843240\">such</span> <span m=\"\
  1843600\">that</span> <span m=\"1845280\">if</span> <span m=\"1845400\">you</span>\
  \ <span m=\"1845490\">look</span> <span m=\"1845700\">at</span> <span m=\"1845820\"\
  >this</span> <span m=\"1846630\">u</span> <span m=\"1846950\">sub</span> <span m=\"\
  1847080\">k,</span> <span m=\"1850770\">it</span> <span m=\"1850890\">does</span>\
  \ <span m=\"1851100\">not--</span> <span m=\"1851930\">it</span> <span m=\"1852150\"\
  >is</span> <span m=\"1852270\">very</span> <span m=\"1852480\">close</span> <span\
  \ m=\"1852930\">to</span> <span m=\"1854550\">W</span> <span m=\"1854940\">sub</span>\
  \ <span m=\"1855810\">nk</span> <span m=\"1859470\">for</span> <span m=\"1859680\"\
  >all</span> <span m=\"1862210\">n</span> <span m=\"1863540\">large</span> <span\
  \ m=\"1863780\">enough</span> <span m=\"1869820\">because</span> <span m=\"1872060\"\
  >of</span> <span m=\"1872130\">what</span> <span m=\"1872280\">happened</span> <span\
  \ m=\"1872820\">up</span> <span m=\"1872970\">there.</span></p><p><span m=\"1878300\"\
  >So</span> <span m=\"1878900\">we</span> <span m=\"1879080\">can</span> <span m=\"\
  1879230\">now</span> <span m=\"1881440\">compute</span> <span m=\"1882070\">the</span>\
  \ <span m=\"1882190\">difference</span> <span m=\"1885150\">between--</span> <span\
  \ m=\"1887950\">in fact,</span> <span m=\"1888400\">let's</span> <span m=\"1890180\"\
  >do</span> <span m=\"1890330\">it</span> <span m=\"1890440\">this</span> <span m=\"\
  1890650\">way.</span> <span m=\"1895400\">So</span> <span m=\"1895450\">now</span>\
  \ <span m=\"1895660\">let's</span> <span m=\"1895870\">compute</span> <span m=\"\
  1900280\">the</span> <span m=\"1902270\">difference,</span> <span m=\"1902585\"\
  >the</span> <span m=\"1902900\">cut norm</span> <span m=\"1903620\">of</span> <span\
  \ m=\"1903740\">the</span> <span m=\"1903830\">difference</span> <span m=\"1904190\"\
  >between</span> <span m=\"1905210\">the</span> <span m=\"1905540\">term</span> <span\
  \ m=\"1905810\">in</span> <span m=\"1905880\">the</span> <span m=\"1905960\">sequence</span>\
  \ <span m=\"1906470\">W</span> <span m=\"1906770\">sub n</span> <span m=\"1907130\"\
  >and</span> <span m=\"1907280\">u.</span> <span m=\"1908060\">So</span> <span m=\"\
  1908340\">by</span> <span m=\"1908480\">triangle</span> <span m=\"1908900\">inequality,</span>\
  \ <span m=\"1910400\">we</span> <span m=\"1910550\">have</span> <span m=\"1913510\"\
  >that</span> <span m=\"1914010\">the</span> <span m=\"1914090\">following</span>\
  \ <span m=\"1914540\">is</span> <span m=\"1914690\">true.</span></p><p><span m=\"\
  1931060\">The</span> <span m=\"1931170\">cut</span> <span m=\"1931440\">norm</span>\
  \ <span m=\"1931890\">is</span> <span m=\"1932490\">upperbounded</span> <span m=\"\
  1933240\">by</span> <span m=\"1933450\">the</span> <span m=\"1933600\">l1</span>\
  \ <span m=\"1933930\">norm.</span> <span m=\"1935940\">Look</span> <span m=\"1936120\"\
  >at</span> <span m=\"1936180\">the</span> <span m=\"1936270\">definitions.</span>\
  \ <span m=\"1942420\">So</span> <span m=\"1942590\">I'm</span> <span m=\"1942680\"\
  >going</span> <span m=\"1942810\">to</span> <span m=\"1942890\">replace</span> <span\
  \ m=\"1943760\">the</span> <span m=\"1943820\">first</span> <span m=\"1944120\"\
  >couple</span> <span m=\"1944420\">of</span> <span m=\"1944570\">these</span> <span\
  \ m=\"1945170\">cut norms</span> <span m=\"1945710\">by</span> <span m=\"1945890\"\
  >l1</span> <span m=\"1946010\">norms</span> <span m=\"1946940\">and</span> <span\
  \ m=\"1947060\">leave</span> <span m=\"1947240\">the</span> <span m=\"1947330\"\
  >last</span> <span m=\"1947630\">one</span> <span m=\"1947940\">in</span> <span\
  \ m=\"1947950\">tact.</span></p><p><span m=\"1955500\">The</span> <span m=\"1955600\"\
  >first</span> <span m=\"1955760\">term,</span> <span m=\"1956240\">I</span> <span\
  \ m=\"1956330\">claim</span> <span m=\"1956750\">is,</span> <span m=\"1957090\"\
  >at</span> <span m=\"1957230\">most,</span> <span m=\"1958780\">epsilon</span> <span\
  \ m=\"1959170\">over</span> <span m=\"1959360\">3,</span> <span m=\"1961000\">because</span>\
  \ <span m=\"1962058\">up there.</span> <span m=\"1964810\">The</span> <span m=\"\
  1964900\">second</span> <span m=\"1965230\">term</span> <span m=\"1965660\">is</span>\
  \ <span m=\"1965800\">going</span> <span m=\"1965910\">to</span> <span m=\"1966040\"\
  >be</span> <span m=\"1966730\">at</span> <span m=\"1966820\">least</span> <span\
  \ m=\"1967360\">epsilon</span> <span m=\"1967690\">over</span> <span m=\"1967930\"\
  >3,</span> <span m=\"1968860\">because</span> <span m=\"1969220\">over</span> <span\
  \ m=\"1969400\">here.</span> <span m=\"1972040\">And</span> <span m=\"1972190\"\
  >the</span> <span m=\"1972280\">third</span> <span m=\"1972490\">term</span> <span\
  \ m=\"1973560\">is</span> <span m=\"1973740\">going</span> <span m=\"1973890\">to</span>\
  \ <span m=\"1973960\">be</span> <span m=\"1974620\">also,</span> <span m=\"1975180\"\
  >at</span> <span m=\"1975310\">most,</span> <span m=\"1976150\">epsilon</span> <span\
  \ m=\"1976510\">over</span> <span m=\"1976720\">3,</span> <span m=\"1977890\">because</span>\
  \ <span m=\"1979300\">well,</span> <span m=\"1979810\">from</span> <span m=\"1980320\"\
  >the</span> <span m=\"1980530\">regularity</span> <span m=\"1981190\">approximation,</span>\
  \ <span m=\"1982660\">I</span> <span m=\"1982750\">know</span> <span m=\"1983950\"\
  >that</span> <span m=\"1985570\">it</span> <span m=\"1985690\">is,</span> <span\
  \ m=\"1985870\">at</span> <span m=\"1985960\">most,</span> <span m=\"1986290\">1</span>\
  \ <span m=\"1986500\">over</span> <span m=\"1986680\">k.</span></p><p><span m=\"\
  1987010\">And</span> <span m=\"1987130\">I</span> <span m=\"1987220\">chose</span>\
  \ <span m=\"1987520\">k</span> <span m=\"1987820\">large</span> <span m=\"1988150\"\
  >enough</span> <span m=\"1989200\">so</span> <span m=\"1989320\">that</span> <span\
  \ m=\"1989480\">there is</span> <span m=\"1989650\">also,</span> <span m=\"1989970\"\
  >at</span> <span m=\"1990100\">most,</span> <span m=\"1990940\">epsilon</span> <span\
  \ m=\"1991300\">over</span> <span m=\"1991480\">3.</span> <span m=\"1992410\">Put</span>\
  \ <span m=\"1992590\">everything</span> <span m=\"1992860\">together,</span> <span\
  \ m=\"1994520\">we</span> <span m=\"1994540\">find</span> <span m=\"1994900\">that</span>\
  \ <span m=\"1996070\">these</span> <span m=\"1996280\">two</span> <span m=\"1996670\"\
  >are--</span> <span m=\"1997285\">they</span> <span m=\"1997570\">different</span>\
  \ <span m=\"1997990\">by, at</span> <span m=\"1998170\">most,</span> <span m=\"\
  1998500\">epsilon</span> <span m=\"1999520\">if</span> <span m=\"1999850\">n</span>\
  \ <span m=\"2000060\">is</span> <span m=\"2000240\">large</span> <span m=\"2000480\"\
  >enough.</span> <span m=\"2001770\">But</span> <span m=\"2001950\">now,</span> <span\
  \ m=\"2002670\">since</span> <span m=\"2004110\">epsilon</span> <span m=\"2004920\"\
  >can</span> <span m=\"2005100\">be</span> <span m=\"2005220\">arbitrarily</span>\
  \ <span m=\"2005850\">small,</span> <span m=\"2010380\">we</span> <span m=\"2010500\"\
  >find</span> <span m=\"2015940\">that</span> <span m=\"2016120\">you</span> <span\
  \ m=\"2016390\">indeed</span> <span m=\"2016720\">have</span> <span m=\"2016900\"\
  >convergence,</span> <span m=\"2017940\">as</span> <span m=\"2018130\">claimed.</span></p><p><span\
  \ m=\"2021750\">And</span> <span m=\"2021860\">this</span> <span m=\"2022010\">finishes</span>\
  \ <span m=\"2022380\">the</span> <span m=\"2022460\">proof</span> <span m=\"2023090\"\
  >of</span> <span m=\"2023300\">compactness.</span> <span m=\"2026160\">So</span>\
  \ <span m=\"2026280\">there</span> <span m=\"2026460\">are</span> <span m=\"2026760\"\
  >a</span> <span m=\"2026790\">few</span> <span m=\"2026970\">components.</span>\
  \ <span m=\"2027700\">One</span> <span m=\"2027840\">is</span> <span m=\"2027990\"\
  >passing</span> <span m=\"2028450\">to--</span> <span m=\"2028910\">so</span> <span\
  \ m=\"2029130\">applying</span> <span m=\"2029550\">regularity,</span> <span m=\"\
  2030630\">passing</span> <span m=\"2031080\">to</span> <span m=\"2031200\">subsequences,</span>\
  \ <span m=\"2033970\">and</span> <span m=\"2034180\">obtaining</span> <span m=\"\
  2034810\">this</span> <span m=\"2035890\">limit</span> <span m=\"2036430\">from</span>\
  \ <span m=\"2036700\">the</span> <span m=\"2036810\">regularity</span> <span m=\"\
  2037480\">approximations,</span> <span m=\"2038630\">these</span> <span m=\"2039100\"\
  >u's.</span> <span m=\"2040140\">And</span> <span m=\"2040240\">then</span> <span\
  \ m=\"2040390\">we</span> <span m=\"2040540\">observe</span> <span m=\"2040910\"\
  >that</span> <span m=\"2041050\">these</span> <span m=\"2041290\">u's,</span> <span\
  \ m=\"2041680\">they</span> <span m=\"2041770\">form</span> <span m=\"2042130\"\
  >a</span> <span m=\"2042220\">Martingale.</span></p><p><span m=\"2043840\">So</span>\
  \ <span m=\"2043990\">we</span> <span m=\"2044110\">can</span> <span m=\"2044260\"\
  >apply</span> <span m=\"2044680\">the</span> <span m=\"2044800\">Martingale</span>\
  \ <span m=\"2045520\">convergence</span> <span m=\"2046270\">theorem</span> <span\
  \ m=\"2047410\">to</span> <span m=\"2048070\">get</span> <span m=\"2048340\">us</span>\
  \ <span m=\"2048760\">a</span> <span m=\"2049090\">candidate</span> <span m=\"2049600\"\
  >for</span> <span m=\"2049719\">the</span> <span m=\"2049810\">limit.</span> <span\
  \ m=\"2052280\">And</span> <span m=\"2052380\">then</span> <span m=\"2052980\">the</span>\
  \ <span m=\"2053070\">rest</span> <span m=\"2053429\">is</span> <span m=\"2053550\"\
  >fairly</span> <span m=\"2053909\">straightforward,</span> <span m=\"2054449\">because</span>\
  \ <span m=\"2054780\">all</span> <span m=\"2054960\">the</span> <span m=\"2055050\"\
  >steps</span> <span m=\"2055440\">are</span> <span m=\"2055560\">good</span> <span\
  \ m=\"2055800\">approximations.</span> <span m=\"2057074\">You</span> <span m=\"\
  2057389\">put</span> <span m=\"2057540\">them</span> <span m=\"2057659\">together,</span>\
  \ <span m=\"2058620\">you</span> <span m=\"2059130\">prove</span> <span m=\"2059520\"\
  >the</span> <span m=\"2059639\">limit.</span> <span m=\"2063090\">Any</span> <span\
  \ m=\"2063260\">questions?</span></p><p><span m=\"2067790\">All</span> <span m=\"\
  2067929\">right,</span> <span m=\"2068159\">so</span> <span m=\"2068270\">you</span>\
  \ <span m=\"2068330\">may</span> <span m=\"2068460\">ask,</span> <span m=\"2069480\"\
  >well,</span> <span m=\"2069570\">now</span> <span m=\"2069750\">we</span> <span\
  \ m=\"2069870\">have</span> <span m=\"2070020\">compactness.</span> <span m=\"2070980\"\
  >What</span> <span m=\"2071370\">is</span> <span m=\"2071550\">compactness</span>\
  \ <span m=\"2072300\">good</span> <span m=\"2072510\">for?</span> <span m=\"2073179\"\
  >So</span> <span m=\"2073350\">it</span> <span m=\"2073469\">may</span> <span m=\"\
  2073650\">seem</span> <span m=\"2073920\">like</span> <span m=\"2074070\">a</span>\
  \ <span m=\"2074130\">somewhat</span> <span m=\"2074460\">abstract</span> <span\
  \ m=\"2075090\">concept.</span></p><p><span m=\"2076090\">So</span> <span m=\"2076199\"\
  >in</span> <span m=\"2076290\">the</span> <span m=\"2076380\">second</span> <span\
  \ m=\"2076710\">half</span> <span m=\"2076949\">of</span> <span m=\"2077040\">today's</span>\
  \ <span m=\"2077340\">lecture,</span> <span m=\"2077730\">I</span> <span m=\"2077790\"\
  >want</span> <span m=\"2077969\">to</span> <span m=\"2078030\">show</span> <span\
  \ m=\"2078270\">you</span> <span m=\"2078840\">how</span> <span m=\"2079139\">to</span>\
  \ <span m=\"2079290\">use</span> <span m=\"2079620\">this</span> <span m=\"2079800\"\
  >compactness</span> <span m=\"2080460\">claim</span> <span m=\"2081300\">combined</span>\
  \ <span m=\"2081870\">with</span> <span m=\"2083610\">the</span> <span m=\"2084060\"\
  >first</span> <span m=\"2084420\">definition</span> <span m=\"2084960\">of</span>\
  \ <span m=\"2085050\">compactness</span> <span m=\"2085679\">that</span> <span m=\"\
  2085770\">you've</span> <span m=\"2086100\">seen,</span> <span m=\"2086790\">namely</span>\
  \ <span m=\"2087480\">every</span> <span m=\"2087960\">open</span> <span m=\"2088290\"\
  >cover</span> <span m=\"2088650\">contains</span> <span m=\"2089159\">a</span> <span\
  \ m=\"2089310\">finite</span> <span m=\"2089670\">sub</span> <span m=\"2089920\"\
  >cover,</span> <span m=\"2091110\">and</span> <span m=\"2091230\">to</span> <span\
  \ m=\"2091350\">use</span> <span m=\"2091679\">that</span> <span m=\"2092370\">to</span>\
  \ <span m=\"2093000\">prove</span> <span m=\"2094380\">many</span> <span m=\"2094739\"\
  >consequences</span> <span m=\"2096179\">about</span> <span m=\"2096840\">the</span>\
  \ <span m=\"2096929\">space</span> <span m=\"2097320\">of</span> <span m=\"2097430\"\
  >graphons.</span> <span m=\"2098460\">And</span> <span m=\"2098820\">some</span>\
  \ <span m=\"2099090\">things</span> <span m=\"2099390\">that</span> <span m=\"2099540\"\
  >we</span> <span m=\"2099720\">had</span> <span m=\"2099900\">to</span> <span m=\"\
  2100350\">work</span> <span m=\"2101070\">a</span> <span m=\"2101130\">bit</span>\
  \ <span m=\"2101310\">hard</span> <span m=\"2101580\">at,</span> <span m=\"2102030\"\
  >but</span> <span m=\"2102670\">they</span> <span m=\"2102790\">turn</span> <span\
  \ m=\"2103020\">out</span> <span m=\"2103110\">to</span> <span m=\"2103200\">fall</span>\
  \ <span m=\"2103800\">from</span> <span m=\"2104400\">the</span> <span m=\"2104520\"\
  >compactness</span> <span m=\"2105120\">statement.</span> <span m=\"2106790\">So</span>\
  \ <span m=\"2106810\">let's</span> <span m=\"2106990\">take</span> <span m=\"2107140\"\
  >a</span> <span m=\"2107200\">quick</span> <span m=\"2107380\">break.</span></p><p><span\
  \ m=\"2109910\">In</span> <span m=\"2110310\">the</span> <span m=\"2110370\">first</span>\
  \ <span m=\"2110610\">part</span> <span m=\"2110850\">of</span> <span m=\"2110910\"\
  >this</span> <span m=\"2111090\">lecture,</span> <span m=\"2111420\">we</span> <span\
  \ m=\"2111540\">proved</span> <span m=\"2112140\">that</span> <span m=\"2112340\"\
  >a</span> <span m=\"2112410\">space</span> <span m=\"2112800\">of</span> <span m=\"\
  2112890\">graphons</span> <span m=\"2113190\">is</span> <span m=\"2113520\">compact.</span>\
  \ <span m=\"2114270\">So</span> <span m=\"2114360\">now</span> <span m=\"2114570\"\
  >let</span> <span m=\"2114690\">me</span> <span m=\"2114810\">show</span> <span\
  \ m=\"2115020\">you</span> <span m=\"2115290\">what</span> <span m=\"2115470\">we</span>\
  \ <span m=\"2115590\">can</span> <span m=\"2116340\">reap</span> <span m=\"2116730\"\
  >as</span> <span m=\"2117120\">consequences</span> <span m=\"2117840\">from</span>\
  \ <span m=\"2118080\">the</span> <span m=\"2118170\">compactness</span> <span m=\"\
  2118960\">result.</span> <span m=\"2120180\">So</span> <span m=\"2120390\">I</span>\
  \ <span m=\"2120450\">want</span> <span m=\"2120600\">to</span> <span m=\"2120660\"\
  >show</span> <span m=\"2120870\">you</span> <span m=\"2120960\">how</span> <span\
  \ m=\"2121170\">to</span> <span m=\"2121290\">apply</span> <span m=\"2122460\">compactness</span>\
  \ <span m=\"2124140\">and</span> <span m=\"2124480\">prove</span> <span m=\"2124800\"\
  >some</span> <span m=\"2125040\">consequences.</span></p><p><span m=\"2135540\"\
  >As</span> <span m=\"2135690\">I</span> <span m=\"2135750\">mentioned</span> <span\
  \ m=\"2136020\">earlier,</span> <span m=\"2137130\">the</span> <span m=\"2137250\"\
  >compactness</span> <span m=\"2138120\">result</span> <span m=\"2138450\">is</span>\
  \ <span m=\"2138570\">related</span> <span m=\"2138990\">to</span> <span m=\"2139110\"\
  >regularity.</span> <span m=\"2140550\">And</span> <span m=\"2141090\">in</span>\
  \ <span m=\"2141180\">fact,</span> <span m=\"2141490\">many</span> <span m=\"2141690\"\
  >of</span> <span m=\"2141780\">the</span> <span m=\"2141870\">results</span> <span\
  \ m=\"2142260\">I'm</span> <span m=\"2142380\">going</span> <span m=\"2142530\"\
  >to</span> <span m=\"2142610\">state,</span> <span m=\"2143040\">you</span> <span\
  \ m=\"2143550\">can</span> <span m=\"2143880\">prove</span> <span m=\"2144510\"\
  >maybe</span> <span m=\"2144780\">with</span> <span m=\"2144930\">some</span> <span\
  \ m=\"2146040\">more</span> <span m=\"2146220\">work</span> <span m=\"2146670\"\
  >using</span> <span m=\"2147150\">the</span> <span m=\"2147270\">regularity</span>\
  \ <span m=\"2147870\">lemma.</span> <span m=\"2149010\">But</span> <span m=\"2149160\"\
  >I</span> <span m=\"2149220\">also</span> <span m=\"2149430\">want</span> <span\
  \ m=\"2149550\">to</span> <span m=\"2149610\">show</span> <span m=\"2149790\">you</span>\
  \ <span m=\"2150000\">how</span> <span m=\"2150240\">to</span> <span m=\"2150330\"\
  >deduce</span> <span m=\"2150690\">them</span> <span m=\"2150870\">directly</span>\
  \ <span m=\"2151320\">from</span> <span m=\"2151530\">compactness.</span> <span\
  \ m=\"2152190\">In</span> <span m=\"2152280\">fact,</span> <span m=\"2152470\">we'll</span>\
  \ <span m=\"2152630\">deduce</span> <span m=\"2153450\">the</span> <span m=\"2153540\"\
  >regularity</span> <span m=\"2153840\">lemma</span> <span m=\"2154650\">from</span>\
  \ <span m=\"2154950\">compactness.</span> <span m=\"2155850\">So</span> <span m=\"\
  2155970\">these</span> <span m=\"2156180\">two</span> <span m=\"2156870\">ideas,</span>\
  \ <span m=\"2157350\">compactness</span> <span m=\"2157920\">and</span> <span m=\"\
  2158010\">regularity,</span> <span m=\"2158550\">they</span> <span m=\"2158700\"\
  >go</span> <span m=\"2158920\">hand-in-hand.</span></p><p><span m=\"2161830\">So</span>\
  \ <span m=\"2162000\">first,</span> <span m=\"2162960\">more</span> <span m=\"2163140\"\
  >so</span> <span m=\"2163320\">as</span> <span m=\"2163440\">a</span> <span m=\"\
  2163500\">warm</span> <span m=\"2163830\">up,</span> <span m=\"2164070\">but</span>\
  \ <span m=\"2164200\">as</span> <span m=\"2164360\">also</span> <span m=\"2164780\"\
  >an</span> <span m=\"2164910\">interesting</span> <span m=\"2165390\">result,</span>\
  \ <span m=\"2165900\">statement,</span> <span m=\"2166890\">an</span> <span m=\"\
  2167010\">interesting</span> <span m=\"2167460\">statement</span> <span m=\"2167880\"\
  >on</span> <span m=\"2168030\">its</span> <span m=\"2168180\">own,</span> <span\
  \ m=\"2169860\">so</span> <span m=\"2170010\">let</span> <span m=\"2170130\">me</span>\
  \ <span m=\"2170220\">prove</span> <span m=\"2170490\">the</span> <span m=\"2170580\"\
  >following.</span> <span m=\"2174970\">So</span> <span m=\"2174990\">here</span>\
  \ <span m=\"2175260\">is</span> <span m=\"2175410\">a</span> <span m=\"2178110\"\
  >statement</span> <span m=\"2179520\">that</span> <span m=\"2179760\">we</span>\
  \ <span m=\"2179910\">can</span> <span m=\"2180060\">deduce</span> <span m=\"2180420\"\
  >from</span> <span m=\"2180600\">compactness.</span> <span m=\"2181580\">So</span>\
  \ <span m=\"2181710\">for</span> <span m=\"2181890\">every</span> <span m=\"2182190\"\
  >epsilon,</span> <span m=\"2183160\">there</span> <span m=\"2183240\">exists</span>\
  \ <span m=\"2183960\">some</span> <span m=\"2185160\">number</span> <span m=\"2185610\"\
  >N</span> <span m=\"2186720\">which</span> <span m=\"2186870\">depend</span> <span\
  \ m=\"2187260\">only</span> <span m=\"2187470\">on</span> <span m=\"2187680\">epsilon,</span>\
  \ <span m=\"2188610\">such</span> <span m=\"2188970\">that</span> <span m=\"2189870\"\
  >for</span> <span m=\"2190140\">every</span> <span m=\"2191550\">W</span> <span\
  \ m=\"2194260\">graphon,</span> <span m=\"2196530\">there</span> <span m=\"2196710\"\
  >exists</span> <span m=\"2198180\">a</span> <span m=\"2198270\">graph</span> <span\
  \ m=\"2200940\">G</span> <span m=\"2203040\">with</span> <span m=\"2204690\">N</span>\
  \ <span m=\"2205620\">vertices,</span> <span m=\"2209440\">such</span> <span m=\"\
  2209770\">that</span> <span m=\"2213350\">the</span> <span m=\"2214040\">cut</span>\
  \ <span m=\"2214460\">distance</span> <span m=\"2215480\">between</span> <span m=\"\
  2219740\">G</span> <span m=\"2221030\">and</span> <span m=\"2221450\">W</span> <span\
  \ m=\"2222770\">is,</span> <span m=\"2223700\">at</span> <span m=\"2223850\">most,</span>\
  \ <span m=\"2224690\">epsilon.</span></p><p><span m=\"2228440\">So</span> <span\
  \ m=\"2228580\">think</span> <span m=\"2228760\">about</span> <span m=\"2228940\"\
  >what</span> <span m=\"2229040\">this</span> <span m=\"2229300\">says.</span> <span\
  \ m=\"2230540\">So</span> <span m=\"2231040\">for</span> <span m=\"2231220\">every</span>\
  \ <span m=\"2231520\">epsilon,</span> <span m=\"2232030\">there</span> <span m=\"\
  2232180\">is</span> <span m=\"2232270\">some</span> <span m=\"2232930\">bound</span>\
  \ <span m=\"2233590\">N</span> <span m=\"2234500\">such</span> <span m=\"2234750\"\
  >that</span> <span m=\"2235060\">every</span> <span m=\"2235330\">graphon--</span>\
  \ <span m=\"2235660\">so</span> <span m=\"2235990\">a</span> <span m=\"2236020\"\
  >graphon</span> <span m=\"2236500\">is</span> <span m=\"2237100\">some</span> <span\
  \ m=\"2238030\">real-value</span> <span m=\"2238690\">function,</span> <span m=\"\
  2240220\">so</span> <span m=\"2240640\">taking</span> <span m=\"2240940\">values</span>\
  \ <span m=\"2241210\">between</span> <span m=\"2241510\">0</span> <span m=\"2241810\"\
  >and</span> <span m=\"2241900\">1.</span> <span m=\"2242900\">You</span> <span m=\"\
  2242920\">can</span> <span m=\"2243100\">approximate</span> <span m=\"2243880\"\
  >it</span> <span m=\"2244330\">in</span> <span m=\"2244450\">the</span> <span m=\"\
  2244570\">distance</span> <span m=\"2244990\">that</span> <span m=\"2245110\">we</span>\
  \ <span m=\"2245230\">care</span> <span m=\"2245470\">about</span> <span m=\"2246040\"\
  >by</span> <span m=\"2246430\">a</span> <span m=\"2246580\">graph</span> <span m=\"\
  2247120\">with</span> <span m=\"2247360\">a</span> <span m=\"2247450\">bounded</span>\
  \ <span m=\"2248170\">number</span> <span m=\"2248560\">of</span> <span m=\"2248770\"\
  >vertices.</span> <span m=\"2251180\">This</span> <span m=\"2251340\">is</span>\
  \ <span m=\"2251550\">kind</span> <span m=\"2251970\">of</span> <span m=\"2252120\"\
  >like</span> <span m=\"2252540\">regularity</span> <span m=\"2253200\">lemma.</span>\
  \ <span m=\"2253700\">If</span> <span m=\"2253870\">you</span> <span m=\"2253980\"\
  >are</span> <span m=\"2254100\">allowed</span> <span m=\"2255170\">edge weights</span>\
  \ <span m=\"2256080\">on</span> <span m=\"2256710\">this</span> <span m=\"2256950\"\
  >graph</span> <span m=\"2257340\">G,</span> <span m=\"2258210\">then</span> <span\
  \ m=\"2259020\">it</span> <span m=\"2259560\">immediately</span> <span m=\"2260070\"\
  >follows</span> <span m=\"2260820\">from</span> <span m=\"2261360\">the</span> <span\
  \ m=\"2261510\">weak</span> <span m=\"2261840\">regularity</span> <span m=\"2262470\"\
  >lemma</span> <span m=\"2263220\">that</span> <span m=\"2263550\">we</span> <span\
  \ m=\"2263790\">already</span> <span m=\"2264200\">proved.</span> <span m=\"2268500\"\
  >And</span> <span m=\"2269400\">from</span> <span m=\"2269730\">that</span> <span\
  \ m=\"2269940\">weak</span> <span m=\"2270180\">regularity</span> <span m=\"2270720\"\
  >lemma</span> <span m=\"2270930\">which</span> <span m=\"2271140\">allows</span>\
  \ <span m=\"2271530\">you</span> <span m=\"2271620\">to</span> <span m=\"2271740\"\
  >get</span> <span m=\"2272040\">some</span> <span m=\"2272880\">G</span> <span m=\"\
  2273180\">with</span> <span m=\"2273710\">edge</span> <span m=\"2273960\">weights,</span>\
  \ <span m=\"2275370\">you</span> <span m=\"2275460\">can</span> <span m=\"2276450\"\
  >think</span> <span m=\"2276630\">about</span> <span m=\"2276870\">how</span> <span\
  \ m=\"2277140\">you</span> <span m=\"2277230\">might</span> <span m=\"2277440\"\
  >turn</span> <span m=\"2278070\">an</span> <span m=\"2278250\">edge-weighted</span>\
  \ <span m=\"2278790\">graph</span> <span m=\"2279120\">into</span> <span m=\"2279330\"\
  >an</span> <span m=\"2281580\">unweighted</span> <span m=\"2282090\">graph.</span>\
  \ <span m=\"2283100\">So</span> <span m=\"2283250\">that</span> <span m=\"2283800\"\
  >can</span> <span m=\"2283980\">also</span> <span m=\"2284190\">be</span> <span\
  \ m=\"2284310\">done.</span></p><p><span m=\"2285240\">But</span> <span m=\"2285420\"\
  >I</span> <span m=\"2285480\">want</span> <span m=\"2285660\">to</span> <span m=\"\
  2285720\">show</span> <span m=\"2285870\">you</span> <span m=\"2285990\">a</span>\
  \ <span m=\"2286020\">completely</span> <span m=\"2286440\">different</span> <span\
  \ m=\"2286740\">way</span> <span m=\"2287010\">of</span> <span m=\"2287250\">proving</span>\
  \ <span m=\"2287640\">this</span> <span m=\"2287790\">result</span> <span m=\"2288480\"\
  >that</span> <span m=\"2289140\">follows</span> <span m=\"2289590\">from</span>\
  \ <span m=\"2289830\">compactness.</span> <span m=\"2293570\">And</span> <span m=\"\
  2293870\">so</span> <span m=\"2294500\">I</span> <span m=\"2294590\">say</span>\
  \ <span m=\"2294770\">it's</span> <span m=\"2294860\">a</span> <span m=\"2294920\"\
  >warm</span> <span m=\"2295080\">up,</span> <span m=\"2295220\">because</span> <span\
  \ m=\"2296000\">it's</span> <span m=\"2296720\">really</span> <span m=\"2296930\"\
  >a</span> <span m=\"2296990\">warm</span> <span m=\"2297200\">up</span> <span m=\"\
  2297320\">for</span> <span m=\"2297410\">the</span> <span m=\"2297470\">next</span>\
  \ <span m=\"2297770\">thing</span> <span m=\"2297920\">we're</span> <span m=\"2298010\"\
  >going</span> <span m=\"2298150\">to</span> <span m=\"2298220\">do.</span> <span\
  \ m=\"2299930\">This is</span> <span m=\"2300140\">an</span> <span m=\"2300340\"\
  >easier</span> <span m=\"2300590\">example</span> <span m=\"2301010\">showing</span>\
  \ <span m=\"2301310\">you</span> <span m=\"2301460\">how</span> <span m=\"2301670\"\
  >to</span> <span m=\"2301790\">use</span> <span m=\"2302360\">compactness.</span></p><p><span\
  \ m=\"2304760\">So</span> <span m=\"2304880\">the</span> <span m=\"2305000\">idea</span>\
  \ <span m=\"2305220\">is,</span> <span m=\"2305290\">I</span> <span m=\"2305380\"\
  >have</span> <span m=\"2305480\">this</span> <span m=\"2305600\">compact</span>\
  \ <span m=\"2306080\">space.</span> <span m=\"2306440\">I'm</span> <span m=\"2306560\"\
  >going</span> <span m=\"2306700\">to</span> <span m=\"2306770\">cover</span> <span\
  \ m=\"2307040\">this</span> <span m=\"2307150\">space</span> <span m=\"2307580\"\
  >by</span> <span m=\"2308990\">open</span> <span m=\"2309290\">sets,</span> <span\
  \ m=\"2309710\">by</span> <span m=\"2309890\">open</span> <span m=\"2310160\">balls.</span>\
  \ <span m=\"2312380\">So</span> <span m=\"2312890\">the</span> <span m=\"2313070\"\
  >open</span> <span m=\"2313370\">balls</span> <span m=\"2314180\">are</span> <span\
  \ m=\"2314300\">going</span> <span m=\"2314570\">to</span> <span m=\"2314660\">be</span>\
  \ <span m=\"2315450\">this</span> <span m=\"2315620\">B</span> <span m=\"2316170\"\
  >sub</span> <span m=\"2316730\">epsilon</span> <span m=\"2318230\">G.</span> <span\
  \ m=\"2318950\">So</span> <span m=\"2319130\">for</span> <span m=\"2319280\">each</span>\
  \ <span m=\"2319610\">graph,</span> <span m=\"2320000\">G,</span> <span m=\"2320690\"\
  >I'm</span> <span m=\"2320870\">going</span> <span m=\"2321200\">to</span> <span\
  \ m=\"2321440\">consider</span> <span m=\"2322410\">the</span> <span m=\"2322510\"\
  >set</span> <span m=\"2322850\">of</span> <span m=\"2324620\">graphons</span> <span\
  \ m=\"2329570\">that</span> <span m=\"2329780\">are</span> <span m=\"2329900\">within</span>\
  \ <span m=\"2330470\">epsilon</span> <span m=\"2331490\">of</span> <span m=\"2332360\"\
  >G.</span> <span m=\"2333080\">So</span> <span m=\"2333230\">this</span> <span m=\"\
  2333430\">is</span> <span m=\"2333480\">you</span> <span m=\"2333590\">have</span>\
  \ <span m=\"2333710\">some</span> <span m=\"2333890\">topological</span> <span m=\"\
  2334490\">space</span> <span m=\"2334755\">or</span> <span m=\"2335020\">some</span>\
  \ <span m=\"2335140\">metric</span> <span m=\"2335480\">space.</span> <span m=\"\
  2335810\">I</span> <span m=\"2336100\">have</span> <span m=\"2336220\">a</span>\
  \ <span m=\"2336290\">point</span> <span m=\"2336770\">G.</span> <span m=\"2337100\"\
  >And</span> <span m=\"2337250\">I</span> <span m=\"2337310\">look</span> <span m=\"\
  2337520\">at</span> <span m=\"2337600\">its</span> <span m=\"2337820\">open</span>\
  \ <span m=\"2338090\">ball.</span> <span m=\"2347930\">This</span> <span m=\"2348110\"\
  >is</span> <span m=\"2348230\">the</span> <span m=\"2348290\">ball.</span> <span\
  \ m=\"2349580\">So</span> <span m=\"2353180\">I</span> <span m=\"2353270\">claim</span>\
  \ <span m=\"2353840\">that</span> <span m=\"2355130\">these</span> <span m=\"2355400\"\
  >open</span> <span m=\"2355670\">balls,</span> <span m=\"2356900\">they</span> <span\
  \ m=\"2357080\">form</span> <span m=\"2357680\">an</span> <span m=\"2357830\">open</span>\
  \ <span m=\"2358100\">cover,</span> <span m=\"2362753\">of</span> <span m=\"2365150\"\
  >the</span> <span m=\"2365290\">space.</span> <span m=\"2370300\">Where</span> <span\
  \ m=\"2370440\">is</span> <span m=\"2370580\">that?</span> <span m=\"2371410\">So</span>\
  \ <span m=\"2371590\">I</span> <span m=\"2371620\">want</span> <span m=\"2371740\"\
  >to</span> <span m=\"2371800\">show</span> <span m=\"2371950\">every</span> <span\
  \ m=\"2373270\">point</span> <span m=\"2373930\">W</span> <span m=\"2374410\">is</span>\
  \ <span m=\"2374560\">covered.</span></p><p><span m=\"2379220\">So</span> <span\
  \ m=\"2379660\">this</span> <span m=\"2379890\">follows</span> <span m=\"2381570\"\
  >from</span> <span m=\"2381930\">the</span> <span m=\"2382020\">claim</span> <span\
  \ m=\"2385840\">that</span> <span m=\"2389000\">every</span> <span m=\"2390350\"\
  >W</span> <span m=\"2391670\">is</span> <span m=\"2391820\">the</span> <span m=\"\
  2391940\">limit</span> <span m=\"2395930\">of</span> <span m=\"2396110\">some</span>\
  \ <span m=\"2396380\">sequence</span> <span m=\"2396830\">of</span> <span m=\"2396950\"\
  >graphs.</span> <span m=\"2404940\">So</span> <span m=\"2405160\">we</span> <span\
  \ m=\"2405310\">didn't</span> <span m=\"2405640\">technically</span> <span m=\"\
  2406120\">actually</span> <span m=\"2406420\">prove</span> <span m=\"2406690\">this</span>\
  \ <span m=\"2406900\">claim.</span> <span m=\"2408600\">I</span> <span m=\"2408730\"\
  >said</span> <span m=\"2408890\">that</span> <span m=\"2408970\">if</span> <span\
  \ m=\"2409060\">you</span> <span m=\"2409150\">take</span> <span m=\"2409420\">W</span>\
  \ <span m=\"2409780\">random</span> <span m=\"2410140\">graphs,</span> <span m=\"\
  2410950\">you</span> <span m=\"2411070\">get</span> <span m=\"2411250\">this.</span>\
  \ <span m=\"2411895\">So</span> <span m=\"2412270\">we</span> <span m=\"2412420\"\
  >didn't</span> <span m=\"2412780\">technically</span> <span m=\"2414730\">prove</span>\
  \ <span m=\"2414970\">that.</span> <span m=\"2415320\">But</span> <span m=\"2415710\"\
  >OK,</span> <span m=\"2415950\">so</span> <span m=\"2416080\">it</span> <span m=\"\
  2416140\">turns</span> <span m=\"2416350\">out</span> <span m=\"2416440\">to</span>\
  \ <span m=\"2416500\">be</span> <span m=\"2416590\">true.</span> <span m=\"2416870\"\
  >There</span> <span m=\"2416890\">are</span> <span m=\"2416920\">easier</span> <span\
  \ m=\"2417250\">ways</span> <span m=\"2417520\">to</span> <span m=\"2417640\">establish</span>\
  \ <span m=\"2418120\">it</span> <span m=\"2418200\">as</span> <span m=\"2418330\"\
  >well</span> <span m=\"2418780\">by</span> <span m=\"2418930\">taking</span> <span\
  \ m=\"2419430\">l1</span> <span m=\"2419680\">approximations.</span></p><p><span\
  \ m=\"2420790\">But</span> <span m=\"2420940\">the</span> <span m=\"2421000\">point</span>\
  \ <span m=\"2421240\">is</span> <span m=\"2421360\">that,</span> <span m=\"2421450\"\
  >if</span> <span m=\"2421570\">you</span> <span m=\"2422650\">use</span> <span m=\"\
  2423370\">this</span> <span m=\"2423700\">claim</span> <span m=\"2424060\">here,</span>\
  \ <span m=\"2424780\">you</span> <span m=\"2424930\">do</span> <span m=\"2425110\"\
  >not</span> <span m=\"2425380\">get</span> <span m=\"2425560\">a</span> <span m=\"\
  2425620\">bound</span> <span m=\"2426010\">on</span> <span m=\"2426150\">the</span>\
  \ <span m=\"2426190\">number</span> <span m=\"2426670\">of</span> <span m=\"2426730\"\
  >vertices.</span> <span m=\"2428460\">It</span> <span m=\"2428550\">could</span>\
  \ <span m=\"2428700\">be</span> <span m=\"2428880\">that</span> <span m=\"2429360\"\
  >for</span> <span m=\"2430290\">very</span> <span m=\"2430590\">bizarre-looking</span>\
  \ <span m=\"2431490\">W's,</span> <span m=\"2432270\">you</span> <span m=\"2432660\"\
  >might</span> <span m=\"2432870\">require</span> <span m=\"2433980\">much</span>\
  \ <span m=\"2434280\">more</span> <span m=\"2435270\">number</span> <span m=\"2435570\"\
  >of</span> <span m=\"2435630\">vertices.</span> <span m=\"2437690\">And</span> <span\
  \ m=\"2437850\">a</span> <span m=\"2438250\">priori,</span> <span m=\"2438680\"\
  >you</span> <span m=\"2439000\">do</span> <span m=\"2439120\">not</span> <span m=\"\
  2439300\">know</span> <span m=\"2439530\">that it</span> <span m=\"2439780\">is</span>\
  \ <span m=\"2439870\">bounded</span> <span m=\"2440320\">as</span> <span m=\"2440470\"\
  >a</span> <span m=\"2440500\">function</span> <span m=\"2440860\">of</span> <span\
  \ m=\"2440950\">epsilon.</span></p><p><span m=\"2443510\">But</span> <span m=\"\
  2443660\">now</span> <span m=\"2444500\">we</span> <span m=\"2445880\">have</span>\
  \ <span m=\"2446030\">this</span> <span m=\"2446180\">open</span> <span m=\"2446420\"\
  >cover.</span> <span m=\"2447110\">So</span> <span m=\"2447380\">by</span> <span\
  \ m=\"2447590\">compactness</span> <span m=\"2451250\">of</span> <span m=\"2451430\"\
  >this</span> <span m=\"2451550\">space</span> <span m=\"2453470\">of</span> <span\
  \ m=\"2453630\">graphons,</span> <span m=\"2455870\">we</span> <span m=\"2455990\"\
  >can</span> <span m=\"2456140\">find</span> <span m=\"2457960\">an</span> <span\
  \ m=\"2458090\">open</span> <span m=\"2458360\">cover</span> <span m=\"2460820\"\
  >using</span> <span m=\"2461600\">a</span> <span m=\"2461660\">finite</span> <span\
  \ m=\"2462110\">subset</span> <span m=\"2463340\">of</span> <span m=\"2464450\"\
  >these</span> <span m=\"2464690\">graphs,</span> <span m=\"2467435\">so</span> <span\
  \ m=\"2468370\">G1</span> <span m=\"2468530\">to</span> <span m=\"2468830\">Gk,</span>\
  \ <span m=\"2468930\">so</span> <span m=\"2469310\">a</span> <span m=\"2469370\"\
  >finite</span> <span m=\"2469790\">subset</span> <span m=\"2470510\">to</span> <span\
  \ m=\"2470660\">do</span> <span m=\"2470810\">an</span> <span m=\"2470900\">open</span>\
  \ <span m=\"2471110\">cover.</span> <span m=\"2473740\">And</span> <span m=\"2473890\"\
  >now</span> <span m=\"2474220\">we</span> <span m=\"2474400\">let</span> <span m=\"\
  2476900\">N</span> <span m=\"2477980\">to</span> <span m=\"2478100\">be</span> <span\
  \ m=\"2478880\">the</span> <span m=\"2479000\">least-common</span> <span m=\"2479840\"\
  >multiple</span> <span m=\"2480950\">of</span> <span m=\"2482120\">all</span> <span\
  \ m=\"2482330\">of</span> <span m=\"2482510\">these</span> <span m=\"2482990\">vertex</span>\
  \ <span m=\"2483710\">set</span> <span m=\"2484790\">sizes.</span></p><p>&nbsp;</p><p><span\
  \ m=\"2509130\">So</span> <span m=\"2509340\">all</span> <span m=\"2509550\">of</span>\
  \ <span m=\"2515020\">these</span> <span m=\"2515260\">graphs,</span> <span m=\"\
  2517860\">they</span> <span m=\"2518210\">are</span> <span m=\"2518870\">within--</span>\
  \ <span m=\"2523010\">so</span> <span m=\"2523200\">for</span> <span m=\"2523320\"\
  >each</span> <span m=\"2523530\">of</span> <span m=\"2523620\">these</span> <span\
  \ m=\"2523800\">graphs,</span> <span m=\"2524220\">I</span> <span m=\"2524340\"\
  >can</span> <span m=\"2524520\">replace</span> <span m=\"2525030\">it</span> <span\
  \ m=\"2525270\">by</span> <span m=\"2525540\">a</span> <span m=\"2525630\">graph</span>\
  \ <span m=\"2526210\">on</span> <span m=\"2526410\">exactly</span> <span m=\"2526980\"\
  >N</span> <span m=\"2527220\">vertices.</span> <span m=\"2536300\">There</span>\
  \ <span m=\"2536630\">exists</span> <span m=\"2537380\">a</span> <span m=\"2537440\"\
  >graph</span> <span m=\"2538170\">Gi</span> <span m=\"2538970\">prime</span> <span\
  \ m=\"2539645\">of</span> <span m=\"2540150\">exactly</span> <span m=\"2540740\"\
  >N</span> <span m=\"2540950\">vertices,</span> <span m=\"2548440\">such</span> <span\
  \ m=\"2548800\">that</span> <span m=\"2550630\">they</span> <span m=\"2550780\"\
  >represent</span> <span m=\"2551230\">the</span> <span m=\"2551320\">same</span>\
  \ <span m=\"2551620\">point</span> <span m=\"2554350\">in</span> <span m=\"2554500\"\
  >the</span> <span m=\"2554590\">space</span> <span m=\"2554950\">of</span> <span\
  \ m=\"2555040\">graphons.</span> <span m=\"2558436\">So</span> <span m=\"2558910\"\
  >why is this?</span> <span m=\"2560740\">Think</span> <span m=\"2560850\">about</span>\
  \ <span m=\"2561270\">the</span> <span m=\"2561360\">representation</span> <span\
  \ m=\"2561840\">of</span> <span m=\"2562320\">a</span> <span m=\"2562410\">graphon</span>\
  \ <span m=\"2563440\">using</span> <span m=\"2563950\">from</span> <span m=\"2564220\"\
  >a</span> <span m=\"2564370\">graph.</span></p><p><span m=\"2565630\">If</span>\
  \ <span m=\"2565780\">I</span> <span m=\"2565990\">start</span> <span m=\"2566530\"\
  >with</span> <span m=\"2570330\">G</span> <span m=\"2570990\">and</span> <span m=\"\
  2571300\">I</span> <span m=\"2571810\">blow</span> <span m=\"2572080\">up</span>\
  \ <span m=\"2572500\">each</span> <span m=\"2572770\">vertex</span> <span m=\"2573730\"\
  >into</span> <span m=\"2576190\">some</span> <span m=\"2580410\">k</span> <span\
  \ m=\"2580650\">vertices,</span> <span m=\"2581940\">then</span> <span m=\"2583680\"\
  >it</span> <span m=\"2583800\">turns</span> <span m=\"2584190\">out--</span> <span\
  \ m=\"2584760\">I</span> <span m=\"2584790\">mean,</span> <span m=\"2584940\">you</span>\
  \ <span m=\"2585030\">should</span> <span m=\"2585210\">think</span> <span m=\"\
  2585420\">about</span> <span m=\"2585600\">why</span> <span m=\"2585750\">this</span>\
  \ <span m=\"2585930\">is</span> <span m=\"2586080\">true.</span> <span m=\"2586530\"\
  >But</span> <span m=\"2586680\">it's</span> <span m=\"2587360\">really</span> <span\
  \ m=\"2587620\">not</span> <span m=\"2587970\">hard</span> <span m=\"2588180\">to</span>\
  \ <span m=\"2588240\">see</span> <span m=\"2588450\">if</span> <span m=\"2588540\"\
  >you</span> <span m=\"2588660\">draw</span> <span m=\"2588900\">the</span> <span\
  \ m=\"2588990\">picture.</span> <span m=\"2589580\">So</span> <span m=\"2589830\"\
  >remember,</span> <span m=\"2590070\">this</span> <span m=\"2590250\">black</span>\
  \ <span m=\"2590490\">and</span> <span m=\"2590580\">white</span> <span m=\"2590730\"\
  >picture,</span> <span m=\"2591960\">that</span> <span m=\"2592630\">actually,</span>\
  \ <span m=\"2592860\">they're</span> <span m=\"2593040\">the</span> <span m=\"2593130\"\
  >same</span> <span m=\"2593370\">point.</span> <span m=\"2593620\">They</span> <span\
  \ m=\"2593790\">are</span> <span m=\"2593850\">represented</span> <span m=\"2594300\"\
  >by</span> <span m=\"2594390\">the</span> <span m=\"2594480\">same</span> <span\
  \ m=\"2594720\">graphon.</span></p><p><span m=\"2597360\">OK,</span> <span m=\"\
  2597620\">and</span> <span m=\"2597750\">that's</span> <span m=\"2597910\">it.</span>\
  \ <span m=\"2598890\">So</span> <span m=\"2598990\">we</span> <span m=\"2599080\"\
  >found</span> <span m=\"2600350\">these</span> <span m=\"2602920\">G's.</span> <span\
  \ m=\"2603790\">All</span> <span m=\"2603940\">of</span> <span m=\"2604000\">them</span>\
  \ <span m=\"2604180\">have</span> <span m=\"2604510\">exactly</span> <span m=\"\
  2605500\">N</span> <span m=\"2605740\">vertices</span> <span m=\"2607240\">such</span>\
  \ <span m=\"2607540\">that</span> <span m=\"2608190\">their</span> <span m=\"2608710\"\
  >epsilon</span> <span m=\"2609670\">open</span> <span m=\"2609910\">balls</span>\
  \ <span m=\"2610450\">form</span> <span m=\"2610840\">an</span> <span m=\"2611170\"\
  >open</span> <span m=\"2611470\">cover</span> <span m=\"2612700\">of</span> <span\
  \ m=\"2613030\">the</span> <span m=\"2613120\">space</span> <span m=\"2613420\"\
  >of</span> <span m=\"2613480\">graphons.</span> <span m=\"2613870\">So</span> <span\
  \ m=\"2614050\">every</span> <span m=\"2614370\">graphon</span> <span m=\"2615130\"\
  >can</span> <span m=\"2615280\">be</span> <span m=\"2615370\">approximated</span>\
  \ <span m=\"2616000\">by</span> <span m=\"2616090\">one</span> <span m=\"2616270\"\
  >of</span> <span m=\"2616360\">these</span> <span m=\"2616690\">graphs.</span> <span\
  \ m=\"2620070\">So</span> <span m=\"2620190\">you</span> <span m=\"2620280\">get</span>\
  \ <span m=\"2620430\">that</span> <span m=\"2620520\">from</span> <span m=\"2620700\"\
  >compactness.</span></p><p><span m=\"2624030\">The</span> <span m=\"2624150\">statement</span>\
  \ <span m=\"2624480\">says,</span> <span m=\"2624750\">for</span> <span m=\"2624930\"\
  >every</span> <span m=\"2625200\">epsilon,</span> <span m=\"2625710\">their</span>\
  \ <span m=\"2625860\">exists</span> <span m=\"2626145\">an</span> <span m=\"2626430\"\
  >N.</span> <span m=\"2626760\">So</span> <span m=\"2627030\">N</span> <span m=\"\
  2627240\">is</span> <span m=\"2627390\">a</span> <span m=\"2627420\">function</span>\
  \ <span m=\"2627870\">of</span> <span m=\"2627990\">epsilon.l</span> <span m=\"\
  2630080\">What's</span> <span m=\"2630260\">the</span> <span m=\"2630350\">function?</span>\
  \ <span m=\"2634590\">This</span> <span m=\"2634740\">proof</span> <span m=\"2634980\"\
  >doesn't</span> <span m=\"2635220\">tell you</span> <span m=\"2635460\">anything</span>\
  \ <span m=\"2635820\">about</span> <span m=\"2636030\">that.</span> <span m=\"2637090\"\
  >So</span> <span m=\"2637140\">this</span> <span m=\"2637320\">proof</span> <span\
  \ m=\"2640260\">gives</span> <span m=\"2640690\">no</span> <span m=\"2640930\">information</span>\
  \ <span m=\"2646860\">about</span> <span m=\"2647830\">the</span> <span m=\"2648060\"\
  >dependence</span> <span m=\"2655600\">of</span> <span m=\"2655840\">N</span> <span\
  \ m=\"2657070\">on</span> <span m=\"2657430\">epsilon.</span></p><p><span m=\"2658750\"\
  >So</span> <span m=\"2658960\">in</span> <span m=\"2659060\">some</span> <span m=\"\
  2659290\">sense,</span> <span m=\"2659510\">it's</span> <span m=\"2659650\">even</span>\
  \ <span m=\"2659920\">worse</span> <span m=\"2660280\">than</span> <span m=\"2660850\"\
  >some</span> <span m=\"2661060\">of</span> <span m=\"2661120\">the</span> <span\
  \ m=\"2661180\">things</span> <span m=\"2661420\">we've</span> <span m=\"2661540\"\
  >seen</span> <span m=\"2662200\">in</span> <span m=\"2662350\">the</span> <span\
  \ m=\"2662860\">earlier</span> <span m=\"2663190\">discussion</span> <span m=\"\
  2663790\">on</span> <span m=\"2663870\">Szemer\xE9di's</span> <span m=\"2664390\"\
  >regularity</span> <span m=\"2664675\">lemma</span> <span m=\"2665230\">where</span>\
  \ <span m=\"2665440\">there</span> <span m=\"2665560\">were</span> <span m=\"2665680\"\
  >tower</span> <span m=\"2665950\">or</span> <span m=\"2666330\">Wowzer-types.</span>\
  \ <span m=\"2667030\">Here</span> <span m=\"2667220\">there is</span> <span m=\"\
  2667450\">no</span> <span m=\"2667660\">information,</span> <span m=\"2668650\"\
  >because</span> <span m=\"2668980\">it</span> <span m=\"2669040\">comes</span> <span\
  \ m=\"2669340\">from</span> <span m=\"2669490\">a</span> <span m=\"2669550\">compactness</span>\
  \ <span m=\"2670300\">statement.</span> <span m=\"2672850\">So</span> <span m=\"\
  2673030\">you</span> <span m=\"2673120\">just</span> <span m=\"2673300\">know</span>\
  \ <span m=\"2673540\">there</span> <span m=\"2673720\">exists</span> <span m=\"\
  2674410\">a</span> <span m=\"2674470\">finite</span> <span m=\"2674860\">open</span>\
  \ <span m=\"2675070\">cover,</span> <span m=\"2676870\">no</span> <span m=\"2677070\"\
  >bounds.</span></p><p><span m=\"2679316\">OK,</span> <span m=\"2679790\">any</span>\
  \ <span m=\"2680000\">questions</span> <span m=\"2680360\">about</span> <span m=\"\
  2680780\">this</span> <span m=\"2680990\">warm-up</span> <span m=\"2681410\">application?</span>\
  \ <span m=\"2683970\">So</span> <span m=\"2684060\">it</span> <span m=\"2684300\"\
  >feels</span> <span m=\"2684550\">a</span> <span m=\"2684610\">bit</span> <span\
  \ m=\"2684690\">magical.</span> <span m=\"2685200\">So</span> <span m=\"2685320\"\
  >you</span> <span m=\"2685410\">have</span> <span m=\"2685560\">compactness.</span>\
  \ <span m=\"2686160\">And</span> <span m=\"2686280\">then</span> <span m=\"2686520\"\
  >you</span> <span m=\"2686670\">have</span> <span m=\"2686880\">all</span> <span\
  \ m=\"2687040\">of</span> <span m=\"2687110\">these</span> <span m=\"2689640\">consequences.</span></p><p><span\
  \ m=\"2691216\">So</span> <span m=\"2691600\">now</span> <span m=\"2691770\">let</span>\
  \ <span m=\"2691890\">me</span> <span m=\"2692250\">show</span> <span m=\"2692490\"\
  >you</span> <span m=\"2692700\">how</span> <span m=\"2692940\">you</span> <span\
  \ m=\"2693060\">can</span> <span m=\"2693210\">deduce</span> <span m=\"2693630\"\
  >the</span> <span m=\"2693750\">regularity</span> <span m=\"2694080\">lemma</span>\
  \ <span m=\"2694980\">itself</span> <span m=\"2695460\">from</span> <span m=\"2695790\"\
  >compactness.</span> <span m=\"2696900\">In</span> <span m=\"2696990\">fact,</span>\
  \ <span m=\"2698340\">in</span> <span m=\"2698640\">the</span> <span m=\"2698820\"\
  >proof</span> <span m=\"2699300\">of</span> <span m=\"2700860\">the</span> <span\
  \ m=\"2701580\">existence,</span> <span m=\"2703010\">in the</span> <span m=\"2703380\"\
  >proof</span> <span m=\"2703650\">of</span> <span m=\"2703740\">compactness,</span>\
  \ <span m=\"2704640\">we</span> <span m=\"2704790\">only</span> <span m=\"2705060\"\
  >used</span> <span m=\"2705450\">weak</span> <span m=\"2705780\">regularity.</span>\
  \ <span m=\"2706840\">And</span> <span m=\"2706930\">now</span> <span m=\"2707070\"\
  >let</span> <span m=\"2707160\">me</span> <span m=\"2707280\">show</span> <span\
  \ m=\"2707490\">you</span> <span m=\"2707610\">how</span> <span m=\"2707850\">you</span>\
  \ <span m=\"2707910\">can</span> <span m=\"2708090\">use</span> <span m=\"2708450\"\
  >the</span> <span m=\"2708540\">weak</span> <span m=\"2708910\">regularity</span>\
  \ <span m=\"2709590\">consequence</span> <span m=\"2710090\">of</span> <span m=\"\
  2710570\">namely</span> <span m=\"2710880\">compactness</span> <span m=\"2711780\"\
  >to</span> <span m=\"2711900\">bootstrap</span> <span m=\"2712530\">itself</span>\
  \ <span m=\"2712830\">to</span> <span m=\"2713070\">strong</span> <span m=\"2713520\"\
  >regularity.</span></p><p><span m=\"2716650\">So</span> <span m=\"2716670\">we</span>\
  \ <span m=\"2717120\">saw</span> <span m=\"2717540\">a</span> <span m=\"2717630\"\
  >version</span> <span m=\"2718110\">of</span> <span m=\"2718200\">strong</span>\
  \ <span m=\"2718530\">regularity</span> <span m=\"2719640\">in</span> <span m=\"\
  2719790\">the</span> <span m=\"2719880\">earlier</span> <span m=\"2720150\">chapter</span>\
  \ <span m=\"2720600\">when</span> <span m=\"2720720\">we</span> <span m=\"2720840\"\
  >discussed</span> <span m=\"2721440\">Szemer\xE9di's</span> <span m=\"2721970\"\
  >regularity</span> <span m=\"2722540\">lemma.</span> <span m=\"2723510\">So</span>\
  \ <span m=\"2723600\">let</span> <span m=\"2723720\">me</span> <span m=\"2723840\"\
  >state it</span> <span m=\"2724140\">in</span> <span m=\"2724950\">a</span> <span\
  \ m=\"2725550\">somewhat</span> <span m=\"2726180\">different-looking</span> <span\
  \ m=\"2726840\">form,</span> <span m=\"2727770\">but</span> <span m=\"2727960\"\
  >that</span> <span m=\"2728160\">turns</span> <span m=\"2728460\">out</span> <span\
  \ m=\"2728550\">to</span> <span m=\"2728640\">be</span> <span m=\"2728940\">morally</span>\
  \ <span m=\"2729480\">equivalent.</span> <span m=\"2732640\">Suppose</span> <span\
  \ m=\"2733090\">I</span> <span m=\"2733180\">have</span> <span m=\"2734020\">a</span>\
  \ <span m=\"2734080\">vector</span> <span m=\"2734860\">of</span> <span m=\"2735130\"\
  >epsilons.</span> <span m=\"2741740\">So</span> <span m=\"2741960\">all</span> <span\
  \ m=\"2742140\">of</span> <span m=\"2742200\">these</span> <span m=\"2742440\">are</span>\
  \ <span m=\"2742840\">positive</span> <span m=\"2743400\">real</span> <span m=\"\
  2743640\">numbers.</span></p><p><span m=\"2749680\">The</span> <span m=\"2749780\"\
  >claim</span> <span m=\"2750030\">is</span> <span m=\"2750210\">that</span> <span\
  \ m=\"2752920\">there</span> <span m=\"2753130\">exists</span> <span m=\"2753940\"\
  >an</span> <span m=\"2754150\">M</span> <span m=\"2755260\">which</span> <span m=\"\
  2755470\">only</span> <span m=\"2755710\">depends</span> <span m=\"2756160\">on</span>\
  \ <span m=\"2756310\">this</span> <span m=\"2756970\">vector</span> <span m=\"2758410\"\
  >such</span> <span m=\"2758770\">that</span> <span m=\"2760840\">for</span> <span\
  \ m=\"2761560\">every</span> <span m=\"2764440\">graphon</span> <span m=\"2766270\"\
  >W,</span> <span m=\"2770310\">one can--</span> <span m=\"2770950\">so</span> <span\
  \ m=\"2771180\">every</span> <span m=\"2772710\">graphon</span> <span m=\"2773190\"\
  >W</span> <span m=\"2774090\">can</span> <span m=\"2774240\">be</span> <span m=\"\
  2774390\">written</span> <span m=\"2782280\">as</span> <span m=\"2782940\">the</span>\
  \ <span m=\"2783080\">following,</span> <span m=\"2785100\">decomposing</span> <span\
  \ m=\"2785690\">the</span> <span m=\"2785750\">following way.</span> <span m=\"\
  2786260\">We</span> <span m=\"2786410\">write</span> <span m=\"2786620\">W</span>\
  \ <span m=\"2787100\">as</span> <span m=\"2787250\">a</span> <span m=\"2787310\"\
  >sum</span> <span m=\"2788120\">of</span> <span m=\"2789400\">a</span> <span m=\"\
  2789530\">structured</span> <span m=\"2790100\">part,</span> <span m=\"2791970\"\
  >a</span> <span m=\"2792140\">pseudo-random</span> <span m=\"2792860\">part,</span>\
  \ <span m=\"2795460\">and</span> <span m=\"2795620\">a</span> <span m=\"2795680\"\
  >small</span> <span m=\"2795950\">part,</span> <span m=\"2798540\">where</span>\
  \ <span m=\"2800710\">the</span> <span m=\"2800800\">structured</span> <span m=\"\
  2801370\">part</span> <span m=\"2802840\">is</span> <span m=\"2804100\">a</span>\
  \ <span m=\"2804190\">step</span> <span m=\"2804490\">function</span> <span m=\"\
  2806980\">with</span> <span m=\"2810190\">k</span> <span m=\"2810460\">parts,</span>\
  \ <span m=\"2811060\">but</span> <span m=\"2811210\">k</span> <span m=\"2811600\"\
  >is,</span> <span m=\"2811960\">at</span> <span m=\"2812080\">most,</span> <span\
  \ m=\"2813910\">M,</span> <span m=\"2814600\">this</span> <span m=\"2814880\">claimed</span>\
  \ <span m=\"2815230\">bound</span> <span m=\"2815560\">M.</span></p><p><span m=\"\
  2817450\">The</span> <span m=\"2817810\">pseudo-random</span> <span m=\"2818590\"\
  >part</span> <span m=\"2821320\">has</span> <span m=\"2821740\">a</span> <span m=\"\
  2821770\">very</span> <span m=\"2822070\">small</span> <span m=\"2822460\">cut</span>\
  \ <span m=\"2822730\">norm,</span> <span m=\"2823640\">so</span> <span m=\"2823750\"\
  >its</span> <span m=\"2824870\">cut</span> <span m=\"2825120\">norm,</span> <span\
  \ m=\"2827200\">very</span> <span m=\"2827470\">small,</span> <span m=\"2827920\"\
  >even</span> <span m=\"2828130\">compared</span> <span m=\"2828520\">to</span> <span\
  \ m=\"2828610\">the</span> <span m=\"2828700\">number</span> <span m=\"2828970\"\
  >of</span> <span m=\"2829060\">parts.</span> <span m=\"2830870\">And</span> <span\
  \ m=\"2830920\">finally,</span> <span m=\"2835430\">the</span> <span m=\"2836060\"\
  >small</span> <span m=\"2836420\">part</span> <span m=\"2836990\">has</span> <span\
  \ m=\"2837780\">l1</span> <span m=\"2838280\">norm</span> <span m=\"2838940\">bounded</span>\
  \ <span m=\"2839300\">by</span> <span m=\"2839750\">epsilon</span> <span m=\"2840170\"\
  >1.</span> <span m=\"2842260\">So</span> <span m=\"2842380\">that's</span> <span\
  \ m=\"2842590\">the</span> <span m=\"2842680\">claim.</span> <span m=\"2842950\"\
  >You</span> <span m=\"2843070\">can</span> <span m=\"2843220\">always--</span> <span\
  \ m=\"2844780\">there</span> <span m=\"2844960\">exists</span> <span m=\"2845270\"\
  >some</span> <span m=\"2845530\">bound</span> <span m=\"2845950\">M</span> <span\
  \ m=\"2846400\">in</span> <span m=\"2846520\">terms</span> <span m=\"2846790\">of</span>\
  \ <span m=\"2846910\">these</span> <span m=\"2847120\">error</span> <span m=\"2847300\"\
  >parameters</span> <span m=\"2848200\">so</span> <span m=\"2848320\">that</span>\
  \ <span m=\"2848440\">you</span> <span m=\"2848530\">have</span> <span m=\"2848680\"\
  >this</span> <span m=\"2848860\">decomposition.</span></p><p><span m=\"2850670\"\
  >So</span> <span m=\"2850780\">we</span> <span m=\"2850960\">saw</span> <span m=\"\
  2851170\">some</span> <span m=\"2851410\">version</span> <span m=\"2851740\">of</span>\
  \ <span m=\"2851800\">this</span> <span m=\"2851980\">earlier</span> <span m=\"\
  2852250\">when</span> <span m=\"2852370\">we</span> <span m=\"2852490\">discussed</span>\
  \ <span m=\"2853030\">the</span> <span m=\"2853180\">spectral</span> <span m=\"\
  2853630\">proof</span> <span m=\"2853930\">of</span> <span m=\"2854110\">regularity</span>\
  \ <span m=\"2854740\">lemma.</span> <span m=\"2855280\">And</span> <span m=\"2855880\"\
  >I</span> <span m=\"2855940\">don't</span> <span m=\"2856090\">want</span> <span\
  \ m=\"2856210\">to</span> <span m=\"2856270\">go</span> <span m=\"2856450\">into</span>\
  \ <span m=\"2857440\">details</span> <span m=\"2857830\">of</span> <span m=\"2857920\"\
  >how</span> <span m=\"2858130\">these</span> <span m=\"2858340\">two</span> <span\
  \ m=\"2858520\">things</span> <span m=\"2858730\">are</span> <span m=\"2858820\"\
  >related,</span> <span m=\"2859360\">but</span> <span m=\"2859540\">just</span>\
  \ <span m=\"2859730\">to</span> <span m=\"2859810\">comment</span> <span m=\"2860650\"\
  >that</span> <span m=\"2861400\">depending</span> <span m=\"2861880\">on</span>\
  \ <span m=\"2861970\">your</span> <span m=\"2862120\">choice</span> <span m=\"2862480\"\
  >of the</span> <span m=\"2862570\">epsilon</span> <span m=\"2863110\">parameters,</span>\
  \ <span m=\"2864010\">it</span> <span m=\"2864130\">relates</span> <span m=\"2864520\"\
  >to</span> <span m=\"2864850\">some</span> <span m=\"2865090\">of</span> <span m=\"\
  2865150\">the</span> <span m=\"2865240\">different</span> <span m=\"2865570\">versions</span>\
  \ <span m=\"2866110\">of</span> <span m=\"2866710\">regularity</span> <span m=\"\
  2867280\">lemma</span> <span m=\"2867580\">that</span> <span m=\"2867670\">we've</span>\
  \ <span m=\"2867850\">seen</span> <span m=\"2868090\">before.</span> <span m=\"\
  2868820\">So</span> <span m=\"2868990\">for</span> <span m=\"2869170\">example,</span>\
  \ <span m=\"2870050\">if</span> <span m=\"2871360\">epsilon</span> <span m=\"2871780\"\
  >k</span> <span m=\"2872650\">is</span> <span m=\"2873250\">roughly</span> <span\
  \ m=\"2873880\">epsilon,</span> <span m=\"2874600\">some</span> <span m=\"2874930\"\
  >fixed</span> <span m=\"2875290\">epsilon</span> <span m=\"2875710\">over</span>\
  \ <span m=\"2876100\">k</span> <span m=\"2876400\">squared,</span> <span m=\"2877240\"\
  >then</span> <span m=\"2878050\">this</span> <span m=\"2878290\">is</span> <span\
  \ m=\"2881350\">basically</span> <span m=\"2882490\">the</span> <span m=\"2882580\"\
  >same</span> <span m=\"2884770\">as</span> <span m=\"2886360\">Szemer\xE9di's</span>\
  \ <span m=\"2888100\">regularity</span> <span m=\"2888400\">lemma,</span> <span\
  \ m=\"2891190\">whereas</span> <span m=\"2892120\">if</span> <span m=\"2894250\"\
  >all</span> <span m=\"2894520\">the</span> <span m=\"2894850\">k's</span> <span\
  \ m=\"2895480\">are</span> <span m=\"2895600\">the</span> <span m=\"2895720\">same</span>\
  \ <span m=\"2896050\">epsilon,</span> <span m=\"2896920\">then</span> <span m=\"\
  2897550\">this</span> <span m=\"2897760\">is</span> <span m=\"2897910\">roughly</span>\
  \ <span m=\"2898270\">the</span> <span m=\"2898360\">same</span> <span m=\"2898720\"\
  >as</span> <span m=\"2898870\">the</span> <span m=\"2898960\">weak</span> <span\
  \ m=\"2899390\">regularity</span> <span m=\"2899760\">lemma.</span></p><p><span\
  \ m=\"2907540\">All right,</span> <span m=\"2909390\">so</span> <span m=\"2909540\"\
  >how</span> <span m=\"2909720\">to</span> <span m=\"2909780\">prove</span> <span\
  \ m=\"2910020\">this</span> <span m=\"2910200\">claim?</span> <span m=\"2910820\"\
  >We're</span> <span m=\"2911230\">going</span> <span m=\"2911350\">to</span> <span\
  \ m=\"2911450\">use</span> <span m=\"2911640\">compactness</span> <span m=\"2912210\"\
  >again.</span> <span m=\"2918070\">So</span> <span m=\"2918220\">first,</span> <span\
  \ m=\"2920600\">there</span> <span m=\"2920840\">always</span> <span m=\"2921200\"\
  >exists</span> <span m=\"2921820\">an</span> <span m=\"2922000\">l1</span> <span\
  \ m=\"2922430\">approximation</span> <span m=\"2923670\">so</span> <span m=\"2923780\"\
  >that</span> <span m=\"2924350\">every</span> <span m=\"2926600\">W</span> <span\
  \ m=\"2928010\">has</span> <span m=\"2932080\">some</span> <span m=\"2932590\">step</span>\
  \ <span m=\"2932920\">function</span> <span m=\"2934840\">u</span> <span m=\"2935350\"\
  >associated</span> <span m=\"2935870\">to</span> <span m=\"2936070\">it</span> <span\
  \ m=\"2936670\">such</span> <span m=\"2937030\">that</span> <span m=\"2938830\"\
  >the</span> <span m=\"2939160\">l1</span> <span m=\"2939550\">distance</span> <span\
  \ m=\"2940210\">between</span> <span m=\"2940690\">W</span> <span m=\"2941230\"\
  >and</span> <span m=\"2941380\">u</span> <span m=\"2942010\">is,</span> <span m=\"\
  2942300\">at</span> <span m=\"2942430\">most,</span> <span m=\"2944020\">epsilon</span>\
  \ <span m=\"2944470\">1.</span></p><p><span m=\"2946060\">So</span> <span m=\"2946270\"\
  >again,</span> <span m=\"2946640\">this</span> <span m=\"2946690\">is</span> <span\
  \ m=\"2946810\">one</span> <span m=\"2946990\">of</span> <span m=\"2947050\">these</span>\
  \ <span m=\"2947440\">more</span> <span m=\"2947770\">measured</span> <span m=\"\
  2948250\">theoretic</span> <span m=\"2948730\">technicalities</span> <span m=\"\
  2949480\">I</span> <span m=\"2949570\">don't</span> <span m=\"2949720\">want</span>\
  \ <span m=\"2949870\">to</span> <span m=\"2949930\">get</span> <span m=\"2950110\"\
  >into,</span> <span m=\"2950610\">but</span> <span m=\"2950760\">so</span> <span\
  \ m=\"2950860\">it's</span> <span m=\"2950980\">not</span> <span m=\"2951730\">hard</span>\
  \ <span m=\"2951970\">to</span> <span m=\"2952090\">prove.</span> <span m=\"2952930\"\
  >So</span> <span m=\"2952990\">roughly</span> <span m=\"2953290\">speaking,</span>\
  \ <span m=\"2953680\">you</span> <span m=\"2953770\">have</span> <span m=\"2953890\"\
  >some</span> <span m=\"2954040\">function.</span> <span m=\"2954400\">You</span>\
  \ <span m=\"2954490\">can</span> <span m=\"2955030\">approximate</span> <span m=\"\
  2955420\">it</span> <span m=\"2956050\">using</span> <span m=\"2956350\">steps.</span></p><p>&nbsp;</p><p>&nbsp;</p><p><span\
  \ m=\"2966860\">So</span> <span m=\"2968090\">similar</span> <span m=\"2968450\"\
  >to</span> <span m=\"2968540\">what</span> <span m=\"2968660\">we</span> <span m=\"\
  2968810\">did</span> <span m=\"2968930\">just</span> <span m=\"2969140\">now,</span>\
  \ <span m=\"2969950\">if</span> <span m=\"2970100\">you</span> <span m=\"2970250\"\
  >just</span> <span m=\"2970580\">do</span> <span m=\"2970790\">that,</span> <span\
  \ m=\"2971450\">the</span> <span m=\"2971630\">number</span> <span m=\"2972110\"\
  >of</span> <span m=\"2972230\">steps</span> <span m=\"2973220\">might</span> <span\
  \ m=\"2973550\">not</span> <span m=\"2974030\">be</span> <span m=\"2974330\">a</span>\
  \ <span m=\"2974390\">function</span> <span m=\"2974930\">of</span> <span m=\"2975050\"\
  >epsilon,</span> <span m=\"2976840\">so</span> <span m=\"2976990\">you</span> <span\
  \ m=\"2977080\">might</span> <span m=\"2977380\">need</span> <span m=\"2977920\"\
  >much</span> <span m=\"2978160\">more</span> <span m=\"2978370\">steps</span> <span\
  \ m=\"2980060\">just</span> <span m=\"2980240\">doing</span> <span m=\"2980480\"\
  >that</span> <span m=\"2981850\">if</span> <span m=\"2982240\">your</span> <span\
  \ m=\"2982480\">W</span> <span m=\"2982960\">looks</span> <span m=\"2983260\">more</span>\
  \ <span m=\"2983440\">pathological.</span> <span m=\"2985570\">So</span> <span m=\"\
  2986490\">now</span> <span m=\"2986710\">what</span> <span m=\"2986860\">we're</span>\
  \ <span m=\"2987010\">going</span> <span m=\"2987120\">to</span> <span m=\"2987220\"\
  >do</span> <span m=\"2987430\">is</span> <span m=\"2987580\">consider</span> <span\
  \ m=\"2988120\">the</span> <span m=\"2988240\">following</span> <span m=\"2988690\"\
  >function,</span> <span m=\"2989950\">k</span> <span m=\"2990400\">of</span> <span\
  \ m=\"2990570\">W.</span> <span m=\"2991860\">And</span> <span m=\"2991990\">I</span>\
  \ <span m=\"2992050\">define</span> <span m=\"2992500\">it</span> <span m=\"2993040\"\
  >to</span> <span m=\"2993160\">be</span> <span m=\"2994240\">the</span> <span m=\"\
  2994360\">minimum</span> <span m=\"2995410\">k</span> <span m=\"2997030\">such</span>\
  \ <span m=\"2997390\">that</span> <span m=\"2998200\">there</span> <span m=\"2998410\"\
  >exists</span> <span m=\"2999900\">a</span> <span m=\"3000080\">k</span> <span m=\"\
  3002100\">step</span> <span m=\"3002850\">graphon</span> <span m=\"3005765\">u</span>\
  \ <span m=\"3007720\">such</span> <span m=\"3008140\">that</span> <span m=\"3009500\"\
  >u</span> <span m=\"3009970\">you</span> <span m=\"3010660\">minus</span> <span\
  \ m=\"3011320\">W</span> <span m=\"3015990\">is,</span> <span m=\"3016480\">at</span>\
  \ <span m=\"3016620\">most,</span> <span m=\"3018320\">epsilon</span> <span m=\"\
  3018600\">1.</span></p><p><span m=\"3020290\">So</span> <span m=\"3021840\">among</span>\
  \ <span m=\"3022410\">all</span> <span m=\"3022650\">the</span> <span m=\"3024170\"\
  >step</span> <span m=\"3024470\">function</span> <span m=\"3024830\">approximations,</span>\
  \ <span m=\"3026030\">pick</span> <span m=\"3026300\">one</span> <span m=\"3026810\"\
  >that</span> <span m=\"3026930\">has</span> <span m=\"3027200\">the</span> <span\
  \ m=\"3027320\">minimum</span> <span m=\"3028010\">number</span> <span m=\"3028340\"\
  >of</span> <span m=\"3028430\">steps</span> <span m=\"3029330\">and</span> <span\
  \ m=\"3029480\">call</span> <span m=\"3029670\">the</span> <span m=\"3029750\">number</span>\
  \ <span m=\"3030020\">of</span> <span m=\"3030080\">steps</span> <span m=\"3030560\"\
  >k</span> <span m=\"3031020\">of</span> <span m=\"3031240\">W.</span> <span m=\"\
  3034560\">So</span> <span m=\"3034690\">now,</span> <span m=\"3034900\">as</span>\
  \ <span m=\"3035050\">before,</span> <span m=\"3035380\">we're</span> <span m=\"\
  3035530\">going</span> <span m=\"3035680\">to</span> <span m=\"3035770\">come</span>\
  \ <span m=\"3036040\">up</span> <span m=\"3036130\">with</span> <span m=\"3036280\"\
  >an</span> <span m=\"3036370\">open</span> <span m=\"3036670\">cover</span> <span\
  \ m=\"3037660\">of</span> <span m=\"3037840\">the</span> <span m=\"3037930\">space</span>\
  \ <span m=\"3038440\">of</span> <span m=\"3038560\">graphons.</span> <span m=\"\
  3041380\">So</span> <span m=\"3041650\">the</span> <span m=\"3041860\">open</span>\
  \ <span m=\"3042160\">cover</span> <span m=\"3042670\">is</span> <span m=\"3042820\"\
  >going</span> <span m=\"3043060\">to</span> <span m=\"3043150\">be</span> <span\
  \ m=\"3044170\">consisting</span> <span m=\"3044770\">of</span> <span m=\"3045610\"\
  >the</span> <span m=\"3046970\">cut</span> <span m=\"3047410\">norm</span> <span\
  \ m=\"3047840\">balls</span> <span m=\"3048750\">of--</span> <span m=\"3050722\"\
  >actually,</span> <span m=\"3051130\">what</span> <span m=\"3051370\">notation</span>\
  \ <span m=\"3051820\">did</span> <span m=\"3051960\">I</span> <span m=\"3052060\"\
  >use</span> <span m=\"3052300\">over</span> <span m=\"3052510\">there?</span> <span\
  \ m=\"3061200\">So</span> <span m=\"3061350\">this</span> <span m=\"3061560\">is</span>\
  \ <span m=\"3061650\">a</span> <span m=\"3061710\">ball</span> <span m=\"3062460\"\
  >centered</span> <span m=\"3062910\">around</span> <span m=\"3063210\">W</span>\
  \ <span m=\"3063990\">with</span> <span m=\"3064170\">radius</span> <span m=\"3064970\"\
  >epsilon</span> <span m=\"3065370\">sub</span> <span m=\"3065740\">kW.</span> <span\
  \ m=\"3068660\">This</span> <span m=\"3068840\">is</span> <span m=\"3068960\">an</span>\
  \ <span m=\"3069050\">open</span> <span m=\"3069320\">cover</span> <span m=\"3073730\"\
  >of</span> <span m=\"3073970\">the</span> <span m=\"3074060\">space</span> <span\
  \ m=\"3074315\">of</span> <span m=\"3074570\">graphons</span> <span m=\"3075972\"\
  >as</span> <span m=\"3076420\">W</span> <span m=\"3077366\">ranges</span> <span\
  \ m=\"3077840\">over</span> <span m=\"3079030\">all</span> <span m=\"3079190\">graphons.</span></p><p><span\
  \ m=\"3083980\">So</span> <span m=\"3084120\">I'm</span> <span m=\"3084260\">literally</span>\
  \ <span m=\"3084930\">looking</span> <span m=\"3085290\">at</span> <span m=\"3085380\"\
  >every</span> <span m=\"3085620\">point</span> <span m=\"3085980\">in</span> <span\
  \ m=\"3086070\">the</span> <span m=\"3086130\">space</span> <span m=\"3086490\"\
  >and</span> <span m=\"3086580\">putting</span> <span m=\"3086940\">an</span> <span\
  \ m=\"3087090\">open</span> <span m=\"3087360\">ball</span> <span m=\"3087540\"\
  >around</span> <span m=\"3087870\">it.</span> <span m=\"3088020\">So</span> <span\
  \ m=\"3088200\">obviously,</span> <span m=\"3088620\">this</span> <span m=\"3088770\"\
  >is</span> <span m=\"3088860\">an</span> <span m=\"3088950\">open</span> <span m=\"\
  3089190\">cover.</span> <span m=\"3091750\">And</span> <span m=\"3091960\">because</span>\
  \ <span m=\"3092380\">of</span> <span m=\"3092470\">compactness,</span> <span m=\"\
  3093670\">there</span> <span m=\"3093850\">exists</span> <span m=\"3094270\">a</span>\
  \ <span m=\"3094360\">finite</span> <span m=\"3094780\">sub</span> <span m=\"3095020\"\
  >cover.</span> <span m=\"3101080\">So</span> <span m=\"3101130\">there</span> <span\
  \ m=\"3101280\">exists</span> <span m=\"3102150\">a</span> <span m=\"3102270\">finite</span>\
  \ <span m=\"3105150\">set,</span> <span m=\"3106312\">we</span> <span m=\"3106700\"\
  >write</span> <span m=\"3106910\">curly</span> <span m=\"3107180\">s,</span> <span\
  \ m=\"3108330\">of</span> <span m=\"3109650\">graphons</span> <span m=\"3114580\"\
  >such</span> <span m=\"3114930\">that</span> <span m=\"3119620\">these</span> <span\
  \ m=\"3124570\">balls,</span> <span m=\"3125290\">as</span> <span m=\"3125440\"\
  >I</span> <span m=\"3125530\">range</span> <span m=\"3125890\">over</span> <span\
  \ m=\"3126720\">W</span> <span m=\"3126940\">and</span> <span m=\"3127270\">curly</span>\
  \ <span m=\"3127600\">s,</span> <span m=\"3128260\">they</span> <span m=\"3128440\"\
  >cover</span> <span m=\"3132020\">the</span> <span m=\"3132110\">space</span> <span\
  \ m=\"3132470\">of</span> <span m=\"3132590\">graphons.</span></p><p><span m=\"\
  3142550\">Now</span> <span m=\"3143360\">the</span> <span m=\"3143480\">goal</span>\
  \ <span m=\"3143900\">is,</span> <span m=\"3144350\">given</span> <span m=\"3144710\"\
  >the</span> <span m=\"3144770\">W,</span> <span m=\"3145160\">I</span> <span m=\"\
  3145250\">want</span> <span m=\"3145430\">to</span> <span m=\"3145520\">approximate</span>\
  \ <span m=\"3145865\">it</span> <span m=\"3146270\">in</span> <span m=\"3146390\"\
  >some</span> <span m=\"3146660\">way.</span> <span m=\"3146870\">So</span> <span\
  \ m=\"3147710\">having</span> <span m=\"3148670\">a</span> <span m=\"3148730\">finite</span>\
  \ <span m=\"3149300\">set</span> <span m=\"3149540\">of</span> <span m=\"3149630\"\
  >things</span> <span m=\"3149930\">to</span> <span m=\"3150080\">work</span> <span\
  \ m=\"3150410\">with</span> <span m=\"3151580\">allows</span> <span m=\"3151910\"\
  >us</span> <span m=\"3152060\">to</span> <span m=\"3152180\">do</span> <span m=\"\
  3152330\">some</span> <span m=\"3152510\">kind</span> <span m=\"3152750\">of</span>\
  \ <span m=\"3152840\">approximations.</span> <span m=\"3156010\">So thus,</span>\
  \ <span m=\"3156660\">for</span> <span m=\"3157110\">every</span> <span m=\"3158030\"\
  >W</span> <span m=\"3158840\">graphon,</span> <span m=\"3160190\">there</span> <span\
  \ m=\"3160370\">exists</span> <span m=\"3162490\">a</span> <span m=\"3162590\">W</span>\
  \ <span m=\"3162920\">prime</span> <span m=\"3164710\">in</span> <span m=\"3164930\"\
  >s</span> <span m=\"3165950\">whose</span> <span m=\"3166790\">ball</span> <span\
  \ m=\"3167240\">in</span> <span m=\"3167400\">that</span> <span m=\"3167840\">collection</span>\
  \ <span m=\"3168620\">covers</span> <span m=\"3169070\">the</span> <span m=\"3169160\"\
  >point</span> <span m=\"3169550\">W,</span> <span m=\"3172150\">such</span> <span\
  \ m=\"3172420\">that</span> <span m=\"3173020\">W</span> <span m=\"3173420\">is</span>\
  \ <span m=\"3173590\">contained</span> <span m=\"3174700\">in</span> <span m=\"\
  3175700\">this</span> <span m=\"3183760\">ball.</span></p><p><span m=\"3186400\"\
  >And</span> <span m=\"3188090\">OK,</span> <span m=\"3188290\">so</span> <span m=\"\
  3188440\">given</span> <span m=\"3188770\">this</span> <span m=\"3188950\">W</span>\
  \ <span m=\"3189280\">prime,</span> <span m=\"3191430\">because</span> <span m=\"\
  3193050\">of</span> <span m=\"3195400\">this</span> <span m=\"3196130\">definition</span>\
  \ <span m=\"3196670\">over</span> <span m=\"3196850\">here,</span> <span m=\"3197540\"\
  >so</span> <span m=\"3197750\">there</span> <span m=\"3197960\">exists</span> <span\
  \ m=\"3199330\">a</span> <span m=\"3199450\">u</span> <span m=\"3202230\">which</span>\
  \ <span m=\"3202460\">is</span> <span m=\"3202610\">a</span> <span m=\"3202680\"\
  >k</span> <span m=\"3203660\">step</span> <span m=\"3203990\">graphon</span> <span\
  \ m=\"3210120\">with</span> <span m=\"3211660\">k,</span> <span m=\"3214440\">at</span>\
  \ <span m=\"3214590\">most,</span> <span m=\"3215570\">the</span> <span m=\"3215730\"\
  >maximum</span> <span m=\"3216580\">over</span> <span m=\"3216860\">all</span> <span\
  \ m=\"3217110\">such</span> <span m=\"3218430\">possible</span> <span m=\"3218910\"\
  >number</span> <span m=\"3219210\">of</span> <span m=\"3219300\">steps,</span> <span\
  \ m=\"3228450\">such</span> <span m=\"3228720\">that</span> <span m=\"3231820\"\
  >W</span> <span m=\"3232460\">and</span> <span m=\"3232660\">W</span> <span m=\"\
  3232990\">prime,</span> <span m=\"3234790\">they</span> <span m=\"3234940\">are</span>\
  \ <span m=\"3235090\">close</span> <span m=\"3235720\">in</span> <span m=\"3236600\"\
  >cut</span> <span m=\"3236890\">norm</span> <span m=\"3239830\">because</span> <span\
  \ m=\"3240640\">you</span> <span m=\"3240790\">have</span> <span m=\"3240940\">this</span>\
  \ <span m=\"3241150\">open</span> <span m=\"3241430\">cover.</span> <span m=\"3243250\"\
  >And</span> <span m=\"3243760\">furthermore,</span> <span m=\"3246070\">W</span>\
  \ <span m=\"3246400\">prime</span> <span m=\"3247090\">is</span> <span m=\"3247270\"\
  >close</span> <span m=\"3247750\">to</span> <span m=\"3248170\">a</span> <span m=\"\
  3249910\">graphon</span> <span m=\"3251380\">with</span> <span m=\"3251770\">a</span>\
  \ <span m=\"3251830\">small</span> <span m=\"3252190\">number</span> <span m=\"\
  3252610\">of</span> <span m=\"3252760\">steps.</span> <span m=\"3261970\">So</span>\
  \ <span m=\"3263470\">suppose</span> <span m=\"3263950\">we</span> <span m=\"3264160\"\
  >now</span> <span m=\"3264430\">write</span> <span m=\"3265720\">W</span> <span\
  \ m=\"3266710\">as</span> <span m=\"3267010\">u</span> <span m=\"3268360\">plus</span>\
  \ <span m=\"3270220\">W</span> <span m=\"3270520\">minus</span> <span m=\"3270880\"\
  >W</span> <span m=\"3271120\">prime</span> <span m=\"3272670\">and</span> <span\
  \ m=\"3272770\">then</span> <span m=\"3272860\">plus</span> <span m=\"3273760\"\
  >W</span> <span m=\"3274030\">prime</span> <span m=\"3274570\">minus</span> <span\
  \ m=\"3275200\">u.</span></p><p><span m=\"3277870\">We</span> <span m=\"3277990\"\
  >find</span> <span m=\"3278260\">that</span> <span m=\"3278350\">this</span> <span\
  \ m=\"3278560\">is</span> <span m=\"3278660\">the</span> <span m=\"3278740\">decomposition</span>\
  \ <span m=\"3279640\">that</span> <span m=\"3279760\">we are</span> <span m=\"3279940\"\
  >looking</span> <span m=\"3280180\">for</span> <span m=\"3280990\">because</span>\
  \ <span m=\"3283440\">the</span> <span m=\"3283550\">u--</span> <span m=\"3284290\"\
  >so</span> <span m=\"3284400\">this</span> <span m=\"3284610\">is</span> <span m=\"\
  3284730\">the</span> <span m=\"3284850\">structural</span> <span m=\"3285360\">component--</span>\
  \ <span m=\"3286380\">has</span> <span m=\"3287340\">k</span> <span m=\"3287590\"\
  >steps,</span> <span m=\"3293150\">where</span> <span m=\"3293330\">k</span> <span\
  \ m=\"3293900\">is</span> <span m=\"3294140\">less</span> <span m=\"3294470\">than</span>\
  \ <span m=\"3295370\">this</span> <span m=\"3295580\">quantity</span> <span m=\"\
  3296000\">here.</span> <span m=\"3298635\">And</span> <span m=\"3298910\">that</span>\
  \ <span m=\"3299060\">quantity</span> <span m=\"3299480\">there</span> <span m=\"\
  3300320\">is</span> <span m=\"3301190\">just</span> <span m=\"3301370\">some</span>\
  \ <span m=\"3301730\">function</span> <span m=\"3302630\">of</span> <span m=\"3303580\"\
  >epsilons.</span> <span m=\"3303890\">So</span> <span m=\"3304200\">it's,</span>\
  \ <span m=\"3304330\">at</span> <span m=\"3304460\">most,</span> <span m=\"3304730\"\
  >some</span> <span m=\"3305000\">function</span> <span m=\"3305360\">of</span> <span\
  \ m=\"3305450\">the</span> <span m=\"3305540\">epsilons.</span> <span m=\"3312030\"\
  >It</span> <span m=\"3312160\">doesn't</span> <span m=\"3312400\">depend</span>\
  \ <span m=\"3312730\">on</span> <span m=\"3312820\">the</span> <span m=\"3312880\"\
  >specific</span> <span m=\"3313360\">choice</span> <span m=\"3313660\">of</span>\
  \ <span m=\"3313750\">W.</span></p><p><span m=\"3318700\">The</span> <span m=\"\
  3318790\">second</span> <span m=\"3319450\">term,</span> <span m=\"3320230\">this</span>\
  \ <span m=\"3320410\">is</span> <span m=\"3320540\">this</span> <span m=\"3320650\"\
  >pseudo-random</span> <span m=\"3321310\">piece,</span> <span m=\"3322570\">because</span>\
  \ <span m=\"3324070\">it's</span> <span m=\"3324400\">cut norm</span> <span m=\"\
  3324870\">is</span> <span m=\"3325000\">small,</span> <span m=\"3330290\">so</span>\
  \ <span m=\"3331916\">what</span> <span m=\"3332320\">we</span> <span m=\"3332630\"\
  >have</span> <span m=\"3332820\">here.</span> <span m=\"3335586\">Yeah, so</span>\
  \ <span m=\"3336050\">this</span> <span m=\"3336560\">entire</span> <span m=\"3336980\"\
  >thing</span> <span m=\"3337190\">should</span> <span m=\"3337340\">be</span> <span\
  \ m=\"3337460\">subscript.</span> <span m=\"3345690\">And</span> <span m=\"3346230\"\
  >finally,</span> <span m=\"3348150\">the</span> <span m=\"3348600\">third</span>\
  \ <span m=\"3349650\">term</span> <span m=\"3349980\">here</span> <span m=\"3350610\"\
  >is</span> <span m=\"3351420\">the</span> <span m=\"3351510\">small</span> <span\
  \ m=\"3351840\">term,</span> <span m=\"3352620\">because</span> <span m=\"3353000\"\
  >it's</span> <span m=\"3353160\">l1</span> <span m=\"3353580\">norm</span> <span\
  \ m=\"3354240\">is</span> <span m=\"3354450\">small.</span></p><p><span m=\"3361350\"\
  >So</span> <span m=\"3361470\">putting</span> <span m=\"3361710\">them</span> <span\
  \ m=\"3361830\">together,</span> <span m=\"3362250\">we</span> <span m=\"3362400\"\
  >get</span> <span m=\"3362560\">the</span> <span m=\"3362660\">regularity</span>\
  \ <span m=\"3363070\">lemma.</span> <span m=\"3366480\">So</span> <span m=\"3366630\"\
  >again,</span> <span m=\"3367020\">the</span> <span m=\"3367320\">proof</span> <span\
  \ m=\"3367800\">gives</span> <span m=\"3368070\">you</span> <span m=\"3368190\"\
  >no</span> <span m=\"3368460\">information</span> <span m=\"3369120\">whatsoever</span>\
  \ <span m=\"3370140\">about</span> <span m=\"3370440\">the</span> <span m=\"3370530\"\
  >bound</span> <span m=\"3371220\">M</span> <span m=\"3371930\">as</span> <span m=\"\
  3372090\">a</span> <span m=\"3372180\">function</span> <span m=\"3372690\">of</span>\
  \ <span m=\"3372810\">the</span> <span m=\"3372930\">input</span> <span m=\"3373230\"\
  >parameters,</span> <span m=\"3373800\">the</span> <span m=\"3373920\">epsilons.</span>\
  \ <span m=\"3376180\">So</span> <span m=\"3376310\">it</span> <span m=\"3376370\"\
  >turns</span> <span m=\"3376580\">out</span> <span m=\"3377330\">you</span> <span\
  \ m=\"3377900\">can</span> <span m=\"3378110\">use</span> <span m=\"3378290\">a</span>\
  \ <span m=\"3378350\">different</span> <span m=\"3378620\">method</span> <span m=\"\
  3378890\">to</span> <span m=\"3379030\">get</span> <span m=\"3379180\">the</span>\
  \ <span m=\"3379250\">bounds.</span> <span m=\"3380030\">Namely,</span> <span m=\"\
  3380600\">we</span> <span m=\"3380840\">actually</span> <span m=\"3381230\">more</span>\
  \ <span m=\"3381440\">or</span> <span m=\"3381470\">less</span> <span m=\"3381800\"\
  >did</span> <span m=\"3382070\">this</span> <span m=\"3382310\">proof</span> <span\
  \ m=\"3382700\">when</span> <span m=\"3382850\">we</span> <span m=\"3382970\">discussed</span>\
  \ <span m=\"3384320\">regularity</span> <span m=\"3385010\">lemma,</span> <span\
  \ m=\"3385240\">the</span> <span m=\"3385310\">strong</span> <span m=\"3385610\"\
  >regularity</span> <span m=\"3385865\">lemma.</span></p><p><span m=\"3386330\">So</span>\
  \ <span m=\"3386480\">we</span> <span m=\"3386600\">did</span> <span m=\"3386780\"\
  >a</span> <span m=\"3386840\">different</span> <span m=\"3387170\">proof</span>\
  \ <span m=\"3387770\">where</span> <span m=\"3387950\">we</span> <span m=\"3388130\"\
  >iterated</span> <span m=\"3388460\">an</span> <span m=\"3388790\">energy</span>\
  \ <span m=\"3389120\">increment</span> <span m=\"3389540\">argument.</span> <span\
  \ m=\"3390780\">And</span> <span m=\"3390950\">that</span> <span m=\"3391100\">gave</span>\
  \ <span m=\"3391340\">you</span> <span m=\"3391460\">some</span> <span m=\"3391700\"\
  >concrete</span> <span m=\"3392120\">bounds,</span> <span m=\"3392720\">some</span>\
  \ <span m=\"3393200\">bounds</span> <span m=\"3393630\">which</span> <span m=\"\
  3393740\">iterates</span> <span m=\"3394250\">on</span> <span m=\"3394430\">these</span>\
  \ <span m=\"3394700\">epsilons.</span> <span m=\"3396020\">But</span> <span m=\"\
  3396430\">here is</span> <span m=\"3396620\">a</span> <span m=\"3396680\">different</span>\
  \ <span m=\"3396920\">proof.</span> <span m=\"3397565\">It</span> <span m=\"3397940\"\
  >gives</span> <span m=\"3398180\">you</span> <span m=\"3398780\">less</span> <span\
  \ m=\"3399110\">information,</span> <span m=\"3399950\">but</span> <span m=\"3400250\"\
  >it</span> <span m=\"3400640\">elegantly</span> <span m=\"3401150\">uses</span>\
  \ <span m=\"3401600\">this</span> <span m=\"3401750\">compactness</span> <span m=\"\
  3402470\">feature</span> <span m=\"3402830\">of</span> <span m=\"3402950\">the</span>\
  \ <span m=\"3403040\">space</span> <span m=\"3403340\">of</span> <span m=\"3403430\"\
  >graphons.</span> <span m=\"3407440\">Any</span> <span m=\"3407620\">questions?</span></p><p><span\
  \ m=\"3414310\">OK,</span> <span m=\"3414750\">so</span> <span m=\"3414900\">we</span>\
  \ <span m=\"3415020\">proved</span> <span m=\"3415320\">compactness.</span> <span\
  \ m=\"3416040\">So</span> <span m=\"3416510\">now</span> <span m=\"3416700\">let's</span>\
  \ <span m=\"3416910\">go</span> <span m=\"3417120\">on</span> <span m=\"3417200\"\
  >to</span> <span m=\"3417390\">the</span> <span m=\"3417540\">other</span> <span\
  \ m=\"3417780\">two</span> <span m=\"3417990\">claims,</span> <span m=\"3419130\"\
  >namely</span> <span m=\"3419520\">the</span> <span m=\"3419700\">existence</span>\
  \ <span m=\"3420330\">of</span> <span m=\"3420450\">the</span> <span m=\"3420510\"\
  >limit</span> <span m=\"3421210\">and</span> <span m=\"3421240\">that</span> <span\
  \ m=\"3421310\">equivalences</span> <span m=\"3422070\">of</span> <span m=\"3422160\"\
  >convergence.</span> <span m=\"3424080\">The</span> <span m=\"3424200\">existence</span>\
  \ <span m=\"3424710\">of</span> <span m=\"3424800\">the</span> <span m=\"3424860\"\
  >limit</span> <span m=\"3425190\">more</span> <span m=\"3425370\">or</span> <span\
  \ m=\"3425400\">less</span> <span m=\"3425800\">is</span> <span m=\"3425890\">a</span>\
  \ <span m=\"3425940\">consequence</span> <span m=\"3426510\">of</span> <span m=\"\
  3426630\">compactness.</span></p><p><span m=\"3435380\">So</span> <span m=\"3435650\"\
  >you</span> <span m=\"3435800\">have</span> <span m=\"3436070\">this</span> <span\
  \ m=\"3437060\">sequence</span> <span m=\"3440960\">of</span> <span m=\"3441110\"\
  >graphons,</span> <span m=\"3441680\">W1,</span> <span m=\"3442190\">W2,</span>\
  \ <span m=\"3442580\">and</span> <span m=\"3442700\">so</span> <span m=\"3442880\"\
  >on.</span> <span m=\"3443690\">And</span> <span m=\"3443840\">the</span> <span\
  \ m=\"3443960\">claim</span> <span m=\"3444410\">is</span> <span m=\"3444590\">that,</span>\
  \ <span m=\"3445400\">if</span> <span m=\"3450540\">this</span> <span m=\"3451350\"\
  >sequence</span> <span m=\"3452730\">of</span> <span m=\"3452970\">F</span> <span\
  \ m=\"3453300\">densities</span> <span m=\"3454260\">converges</span> <span m=\"\
  3459660\">for</span> <span m=\"3460150\">each</span> <span m=\"3462494\">F,</span>\
  \ <span m=\"3464900\">then</span> <span m=\"3466700\">there</span> <span m=\"3467090\"\
  >exists</span> <span m=\"3467750\">some</span> <span m=\"3468110\">limit</span>\
  \ <span m=\"3468560\">W</span> <span m=\"3469880\">such</span> <span m=\"3470270\"\
  >that</span> <span m=\"3471170\">all</span> <span m=\"3471410\">of</span> <span\
  \ m=\"3473750\">these</span> <span m=\"3474290\">sequences</span> <span m=\"3476150\"\
  >of</span> <span m=\"3476770\">F</span> <span m=\"3476960\">densities</span> <span\
  \ m=\"3477680\">converge</span> <span m=\"3478910\">to</span> <span m=\"3479120\"\
  >the</span> <span m=\"3479240\">limit</span> <span m=\"3479630\">density.</span>\
  \ <span m=\"3481140\">So</span> <span m=\"3481700\">that</span> <span m=\"3481850\"\
  >was</span> <span m=\"3482030\">the</span> <span m=\"3482120\">claim,</span> <span\
  \ m=\"3484010\">so</span> <span m=\"3484580\">nothing</span> <span m=\"3484970\"\
  >about</span> <span m=\"3485210\">cut</span> <span m=\"3485420\">norms</span> <span\
  \ m=\"3485810\">in</span> <span m=\"3486140\">at</span> <span m=\"3486200\">least</span>\
  \ <span m=\"3486860\">as</span> <span m=\"3486980\">far</span> <span m=\"3487220\"\
  >as</span> <span m=\"3487310\">the</span> <span m=\"3487400\">statement</span> <span\
  \ m=\"3487820\">goes.</span></p><p><span m=\"3490040\">Well</span> <span m=\"3490240\"\
  >OK,</span> <span m=\"3494190\">from</span> <span m=\"3494430\">compactness,</span>\
  \ <span m=\"3495150\">we</span> <span m=\"3495330\">know</span> <span m=\"3495540\"\
  >that</span> <span m=\"3496080\">you</span> <span m=\"3496200\">can</span> <span\
  \ m=\"3496350\">produce</span> <span m=\"3496800\">always</span> <span m=\"3497190\"\
  >a</span> <span m=\"3497220\">subsequential</span> <span m=\"3497880\">limit.</span>\
  \ <span m=\"3499680\">So</span> <span m=\"3500400\">by</span> <span m=\"3500580\"\
  >compactness</span> <span m=\"3502040\">or</span> <span m=\"3502140\">sequential</span>\
  \ <span m=\"3502620\">compactness,</span> <span m=\"3508030\">there</span> <span\
  \ m=\"3508210\">exists</span> <span m=\"3508990\">some</span> <span m=\"3509280\"\
  >limit</span> <span m=\"3509530\">point</span> <span m=\"3513520\">which</span>\
  \ <span m=\"3514000\">we</span> <span m=\"3514090\">call</span> <span m=\"3514280\"\
  >W.</span> <span m=\"3516810\">And</span> <span m=\"3517380\">this</span> <span\
  \ m=\"3518310\">W</span> <span m=\"3518850\">has</span> <span m=\"3519090\">the</span>\
  \ <span m=\"3519180\">property</span> <span m=\"3519750\">that,</span> <span m=\"\
  3520950\">for</span> <span m=\"3521310\">some</span> <span m=\"3521740\">subsequence,</span>\
  \ <span m=\"3526320\">the</span> <span m=\"3526860\">cut</span> <span m=\"3527100\"\
  >distance</span> <span m=\"3529230\">from</span> <span m=\"3529860\">the</span>\
  \ <span m=\"3530130\">subsequence</span> <span m=\"3531030\">converges</span> <span\
  \ m=\"3531630\">to</span> <span m=\"3532020\">W.</span> <span m=\"3534120\">So</span>\
  \ <span m=\"3534840\">for</span> <span m=\"3535020\">some</span> <span m=\"3539510\"\
  >subsequence</span> <span m=\"3541660\">n0</span> <span m=\"3543190\">as</span>\
  \ <span m=\"3543470\">ni</span> <span m=\"3544310\">going</span> <span m=\"3544590\"\
  >to</span> <span m=\"3544730\">infinity.</span></p><p><span m=\"3547660\">But</span>\
  \ <span m=\"3547780\">now,</span> <span m=\"3548110\">by</span> <span m=\"3548380\"\
  >the</span> <span m=\"3548470\">counting</span> <span m=\"3548830\">lemma,</span>\
  \ <span m=\"3556290\">the</span> <span m=\"3556950\">sequence</span> <span m=\"\
  3557520\">of</span> <span m=\"3558120\">F</span> <span m=\"3558330\">densities--</span>\
  \ <span m=\"3560990\">so</span> <span m=\"3561150\">the</span> <span m=\"3561240\"\
  >counting</span> <span m=\"3561560\">Lemma</span> <span m=\"3561780\">tells</span>\
  \ <span m=\"3562050\">you,</span> <span m=\"3562200\">if</span> <span m=\"3562320\"\
  >you</span> <span m=\"3562410\">have</span> <span m=\"3562650\">cut</span> <span\
  \ m=\"3562890\">distance</span> <span m=\"3563250\">going</span> <span m=\"3563460\"\
  >to</span> <span m=\"3563550\">0,</span> <span m=\"3564390\">then</span> <span m=\"\
  3565200\">the</span> <span m=\"3565470\">F</span> <span m=\"3565650\">density</span>\
  \ <span m=\"3566040\">should</span> <span m=\"3566220\">also</span> <span m=\"3566460\"\
  >go</span> <span m=\"3566580\">to</span> <span m=\"3566670\">0.</span> <span m=\"\
  3568360\">So</span> <span m=\"3568540\">indeed,</span> <span m=\"3568810\">that's</span>\
  \ <span m=\"3568990\">what</span> <span m=\"3569110\">we</span> <span m=\"3569260\"\
  >have</span> <span m=\"3569440\">here.</span> <span m=\"3578450\">So</span> <span\
  \ m=\"3578500\">this</span> <span m=\"3578680\">is</span> <span m=\"3578740\">so</span>\
  \ <span m=\"3578920\">far</span> <span m=\"3579130\">just</span> <span m=\"3579310\"\
  >for</span> <span m=\"3579400\">the</span> <span m=\"3579490\">subsequence.</span></p><p><span\
  \ m=\"3580840\">But</span> <span m=\"3581860\">we</span> <span m=\"3582190\">assumed</span>\
  \ <span m=\"3582730\">already</span> <span m=\"3583120\">that</span> <span m=\"\
  3583210\">the</span> <span m=\"3583270\">entire</span> <span m=\"3583780\">sequence</span>\
  \ <span m=\"3585340\">converges</span> <span m=\"3587275\">in</span> <span m=\"\
  3587590\">respect</span> <span m=\"3588010\">to</span> <span m=\"3588100\">every</span>\
  \ <span m=\"3588340\">F</span> <span m=\"3588630\">densities.</span> <span m=\"\
  3596940\">So</span> <span m=\"3598260\">it</span> <span m=\"3598320\">must</span>\
  \ <span m=\"3598530\">be</span> <span m=\"3598650\">the</span> <span m=\"3598740\"\
  >same</span> <span m=\"3598980\">limit.</span> <span m=\"3604130\">And</span> <span\
  \ m=\"3604620\">that</span> <span m=\"3605160\">finishes</span> <span m=\"3605640\"\
  >the</span> <span m=\"3605700\">proof</span> <span m=\"3606090\">of</span> <span\
  \ m=\"3608030\">convergence,</span> <span m=\"3608660\">so</span> <span m=\"3608750\"\
  >proof</span> <span m=\"3609050\">of</span> <span m=\"3609950\">the</span> <span\
  \ m=\"3610070\">existence</span> <span m=\"3610610\">of</span> <span m=\"3610670\"\
  >the</span> <span m=\"3610760\">limit.</span> <span m=\"3611830\">So</span> <span\
  \ m=\"3611950\">we</span> <span m=\"3612080\">obtain</span> <span m=\"3612410\"\
  >this</span> <span m=\"3612560\">limit</span> <span m=\"3612860\">from</span> <span\
  \ m=\"3613160\">compactness.</span></p><p><span m=\"3616260\">Next,</span> <span\
  \ m=\"3617100\">let's</span> <span m=\"3617340\">prove</span> <span m=\"3617760\"\
  >the</span> <span m=\"3618120\">equivalence</span> <span m=\"3618810\">of</span>\
  \ <span m=\"3618930\">convergence.</span> <span m=\"3619590\">And</span> <span m=\"\
  3619680\">this</span> <span m=\"3619830\">one</span> <span m=\"3619920\">is</span>\
  \ <span m=\"3620040\">somewhat</span> <span m=\"3620340\">trickier.</span> <span\
  \ m=\"3621310\">So</span> <span m=\"3621330\">what</span> <span m=\"3621540\">happens</span>\
  \ <span m=\"3621870\">here</span> <span m=\"3623340\">is</span> <span m=\"3623520\"\
  >that</span> <span m=\"3623850\">we</span> <span m=\"3624000\">would</span> <span\
  \ m=\"3624150\">like</span> <span m=\"3624300\">to</span> <span m=\"3624420\">show</span>\
  \ <span m=\"3625620\">that</span> <span m=\"3625980\">these</span> <span m=\"3626220\"\
  >two</span> <span m=\"3626370\">notions</span> <span m=\"3626850\">of</span> <span\
  \ m=\"3626970\">convergence,</span> <span m=\"3627840\">one</span> <span m=\"3628560\"\
  >having</span> <span m=\"3628800\">to</span> <span m=\"3628890\">do</span> <span\
  \ m=\"3629070\">with</span> <span m=\"3629430\">F</span> <span m=\"3629640\">densities</span>\
  \ <span m=\"3630750\">and</span> <span m=\"3630870\">another</span> <span m=\"3631230\"\
  >having</span> <span m=\"3631530\">to</span> <span m=\"3631620\">do</span> <span\
  \ m=\"3631830\">with</span> <span m=\"3632130\">cut</span> <span m=\"3632550\">distance,</span>\
  \ <span m=\"3633320\">that</span> <span m=\"3633600\">these</span> <span m=\"3633810\"\
  >two</span> <span m=\"3633990\">notions</span> <span m=\"3634560\">are</span> <span\
  \ m=\"3634830\">equivalent</span> <span m=\"3635520\">to</span> <span m=\"3635700\"\
  >each</span> <span m=\"3635910\">other.</span></p><p><span m=\"3641250\">So</span>\
  \ <span m=\"3641300\">the</span> <span m=\"3641390\">goal</span> <span m=\"3641720\"\
  >here</span> <span m=\"3641990\">is</span> <span m=\"3642200\">to</span> <span m=\"\
  3642320\">show</span> <span m=\"3643070\">that</span> <span m=\"3646720\">this</span>\
  \ <span m=\"3646980\">F</span> <span m=\"3647170\">density</span> <span m=\"3648430\"\
  >convergence</span> <span m=\"3651265\">is</span> <span m=\"3651700\">equivalent</span>\
  \ <span m=\"3652900\">to</span> <span m=\"3653050\">the</span> <span m=\"3653140\"\
  >statement</span> <span m=\"3654160\">that</span> <span m=\"3654810\">W sub</span>\
  \ <span m=\"3655255\">n</span> <span m=\"3656100\">is</span> <span m=\"3656470\"\
  >Cauchy</span> <span m=\"3658870\">with</span> <span m=\"3659350\">respect</span>\
  \ <span m=\"3661390\">to</span> <span m=\"3663840\">the</span> <span m=\"3663940\"\
  >cut</span> <span m=\"3664150\">distance.</span> <span m=\"3667410\">All right,</span>\
  \ <span m=\"3668390\">claim</span> <span m=\"3668730\">one</span> <span m=\"3669000\"\
  >of</span> <span m=\"3669060\">the</span> <span m=\"3669150\">directions</span>\
  \ <span m=\"3669640\">is</span> <span m=\"3669720\">easy.</span> <span m=\"3671540\"\
  >Which</span> <span m=\"3671750\">direction</span> <span m=\"3672010\">is</span>\
  \ <span m=\"3672200\">that?</span></p><p><span m=\"3682070\">So</span> <span m=\"\
  3682300\">which</span> <span m=\"3682510\">direction</span> <span m=\"3682960\"\
  >is</span> <span m=\"3683080\">the</span> <span m=\"3683170\">easy</span> <span\
  \ m=\"3683380\">direction?</span> <span m=\"3688590\">So</span> <span m=\"3688890\"\
  >which</span> <span m=\"3689100\">way,</span> <span m=\"3689780\">left,</span> <span\
  \ m=\"3690310\">going</span> <span m=\"3690500\">left,</span> <span m=\"3690750\"\
  >going</span> <span m=\"3690990\">right?</span> <span m=\"3694520\">OK,</span> <span\
  \ m=\"3694720\">so</span> <span m=\"3694890\">going</span> <span m=\"3695130\">left?</span>\
  \ <span m=\"3696240\">So</span> <span m=\"3696420\">I</span> <span m=\"3696480\"\
  >claim</span> <span m=\"3696930\">that</span> <span m=\"3697860\">this</span> <span\
  \ m=\"3698070\">is</span> <span m=\"3698220\">easy,</span> <span m=\"3699960\">because</span>\
  \ <span m=\"3700560\">it</span> <span m=\"3700620\">follows</span> <span m=\"3701040\"\
  >from</span> <span m=\"3701250\">counting</span> <span m=\"3701640\">lemma.</span></p><p><span\
  \ m=\"3711210\">Counting</span> <span m=\"3711540\">lemma,</span> <span m=\"3711800\"\
  >remember</span> <span m=\"3711990\">the</span> <span m=\"3712080\">spirit</span>\
  \ <span m=\"3712470\">of</span> <span m=\"3712530\">the</span> <span m=\"3712620\"\
  >counting</span> <span m=\"3712960\">lemma,</span> <span m=\"3713050\">at</span>\
  \ <span m=\"3713190\">least</span> <span m=\"3713400\">qualitatively,</span> <span\
  \ m=\"3714150\">is</span> <span m=\"3714270\">that</span> <span m=\"3714390\">if</span>\
  \ <span m=\"3714510\">you</span> <span m=\"3714630\">have</span> <span m=\"3715260\"\
  >two</span> <span m=\"3715470\">graphons</span> <span m=\"3715970\">that</span>\
  \ <span m=\"3716130\">are</span> <span m=\"3716220\">close</span> <span m=\"3716475\"\
  >in</span> <span m=\"3716730\">cut</span> <span m=\"3716970\">distance,</span> <span\
  \ m=\"3717690\">then</span> <span m=\"3717870\">they</span> <span m=\"3717980\"\
  >are</span> <span m=\"3718080\">close in</span> <span m=\"3718435\">F</span> <span\
  \ m=\"3718790\">densities.</span> <span m=\"3719760\">So</span> <span m=\"3719940\"\
  >if</span> <span m=\"3720030\">you</span> <span m=\"3720100\">have</span> <span\
  \ m=\"3720220\">Cauchy</span> <span m=\"3720660\">with</span> <span m=\"3720870\"\
  >respect</span> <span m=\"3721320\">to</span> <span m=\"3721890\">cut</span> <span\
  \ m=\"3722070\">distance,</span> <span m=\"3723030\">then</span> <span m=\"3723840\"\
  >they</span> <span m=\"3723990\">are</span> <span m=\"3724070\">Cauchy,</span> <span\
  \ m=\"3724440\">and</span> <span m=\"3724560\">hence,</span> <span m=\"3724770\"\
  >convergent</span> <span m=\"3725490\">in</span> <span m=\"3725660\">F</span> <span\
  \ m=\"3725850\">densities.</span></p><p><span m=\"3729370\">And it's</span> <span\
  \ m=\"3729490\">the</span> <span m=\"3729610\">other</span> <span m=\"3729760\"\
  >direction</span> <span m=\"3730450\">that</span> <span m=\"3731230\">will</span>\
  \ <span m=\"3731380\">require</span> <span m=\"3731830\">some</span> <span m=\"\
  3732040\">work.</span> <span m=\"3732760\">And</span> <span m=\"3732880\">this</span>\
  \ <span m=\"3733000\">one</span> <span m=\"3733070\">is</span> <span m=\"3733210\"\
  >actually</span> <span m=\"3733480\">genuinely</span> <span m=\"3733990\">tricky.</span>\
  \ <span m=\"3736130\">So</span> <span m=\"3736720\">and</span> <span m=\"3738910\"\
  >it's</span> <span m=\"3739030\">almost</span> <span m=\"3739300\">kind</span> <span\
  \ m=\"3739570\">of</span> <span m=\"3739690\">a</span> <span m=\"3740050\">miraculous</span>\
  \ <span m=\"3740590\">statement,</span> <span m=\"3741160\">that</span> <span m=\"\
  3741620\">somehow</span> <span m=\"3742060\">if</span> <span m=\"3742240\">you</span>\
  \ <span m=\"3742390\">only</span> <span m=\"3742690\">knew</span> <span m=\"3743740\"\
  >the</span> <span m=\"3744280\">F</span> <span m=\"3744550\">densities--</span>\
  \ <span m=\"3745630\">so</span> <span m=\"3745780\">somebody</span> <span m=\"3746080\"\
  >gives</span> <span m=\"3746260\">you</span> <span m=\"3746350\">this</span> <span\
  \ m=\"3746500\">very</span> <span m=\"3746740\">large</span> <span m=\"3747040\"\
  >sequence</span> <span m=\"3747430\">of</span> <span m=\"3747490\">graphs</span>\
  \ <span m=\"3748480\">and</span> <span m=\"3748600\">only</span> <span m=\"3748840\"\
  >tells</span> <span m=\"3749140\">you</span> <span m=\"3749410\">that</span> <span\
  \ m=\"3749950\">the</span> <span m=\"3750040\">triangle</span> <span m=\"3750340\"\
  >densities,</span> <span m=\"3750760\">the</span> <span m=\"3750820\">C4</span>\
  \ <span m=\"3751190\">densities,</span> <span m=\"3751960\">all</span> <span m=\"\
  3752120\">of</span> <span m=\"3752170\">these</span> <span m=\"3752350\">graph</span>\
  \ <span m=\"3752620\">densities,</span> <span m=\"3753070\">they</span> <span m=\"\
  3753190\">converge.</span> <span m=\"3754090\">Somehow</span> <span m=\"3755260\"\
  >from</span> <span m=\"3755500\">these</span> <span m=\"3755650\">small</span> <span\
  \ m=\"3756070\">statistics,</span> <span m=\"3757600\">you</span> <span m=\"3757720\"\
  >conclude</span> <span m=\"3758500\">that</span> <span m=\"3759010\">the</span>\
  \ <span m=\"3759100\">graphs</span> <span m=\"3759760\">globally</span> <span m=\"\
  3760900\">look</span> <span m=\"3761140\">very</span> <span m=\"3761380\">similar</span>\
  \ <span m=\"3761800\">to</span> <span m=\"3761950\">each</span> <span m=\"3762130\"\
  >other.</span> <span m=\"3763850\">That's</span> <span m=\"3764000\">actually,</span>\
  \ <span m=\"3764390\">if</span> <span m=\"3764450\">you</span> <span m=\"3764510\"\
  >think</span> <span m=\"3764690\">about,</span> <span m=\"3764870\">this</span>\
  \ <span m=\"3765650\">is</span> <span m=\"3765770\">an</span> <span m=\"3765890\"\
  >amazing</span> <span m=\"3766220\">statement.</span></p><p><span m=\"3769230\"\
  >OK, so</span> <span m=\"3769560\">let's</span> <span m=\"3769740\">see</span> <span\
  \ m=\"3769830\">the</span> <span m=\"3769920\">proof.</span> <span m=\"3774030\"\
  >The</span> <span m=\"3774120\">proof</span> <span m=\"3774390\">method</span> <span\
  \ m=\"3774660\">here</span> <span m=\"3774900\">is</span> <span m=\"3774990\">somewhat</span>\
  \ <span m=\"3776100\">representative</span> <span m=\"3776850\">of</span> <span\
  \ m=\"3777480\">these</span> <span m=\"3778110\">graph-limit-type</span> <span m=\"\
  3779250\">arguments.</span> <span m=\"3780450\">So</span> <span m=\"3780690\">it's</span>\
  \ <span m=\"3780870\">worth</span> <span m=\"3781140\">paying</span> <span m=\"\
  3781410\">attention</span> <span m=\"3781890\">to</span> <span m=\"3782040\">see</span>\
  \ <span m=\"3782820\">how</span> <span m=\"3782940\">this</span> <span m=\"3783120\"\
  >one</span> <span m=\"3783270\">goes.</span> <span m=\"3783870\">So</span> <span\
  \ m=\"3784140\">by</span> <span m=\"3784320\">compactness,</span> <span m=\"3786420\"\
  >if--</span> <span m=\"3787380\">OK,</span> <span m=\"3787640\">we're</span> <span\
  \ m=\"3787690\">going</span> <span m=\"3787800\">to</span> <span m=\"3787890\">set</span>\
  \ <span m=\"3788160\">up</span> <span m=\"3788320\">by</span> <span m=\"3788400\"\
  >contradiction.</span></p><p><span m=\"3791550\">If</span> <span m=\"3792000\">the</span>\
  \ <span m=\"3792130\">sequence</span> <span m=\"3792540\">is</span> <span m=\"3792660\"\
  >not</span> <span m=\"3792960\">Cauchy,</span> <span m=\"3802720\">then</span> <span\
  \ m=\"3804010\">there</span> <span m=\"3804290\">exists</span> <span m=\"3805330\"\
  >two</span> <span m=\"3805690\">limit</span> <span m=\"3805960\">points.</span>\
  \ <span m=\"3811930\">So</span> <span m=\"3812070\">there</span> <span m=\"3812190\"\
  >exists</span> <span m=\"3812550\">at</span> <span m=\"3812730\">least</span> <span\
  \ m=\"3813030\">two</span> <span m=\"3813300\">distinct</span> <span m=\"3813840\"\
  >limit</span> <span m=\"3814110\">points.</span> <span m=\"3814830\">And</span>\
  \ <span m=\"3814980\">call</span> <span m=\"3815240\">them</span> <span m=\"3816020\"\
  >u</span> <span m=\"3816580\">and</span> <span m=\"3816810\">W,</span> <span m=\"\
  3819410\">and</span> <span m=\"3819570\">such</span> <span m=\"3819840\">that--</span>\
  \ <span m=\"3826370\">so</span> <span m=\"3826630\">because</span> <span m=\"3826960\"\
  >you</span> <span m=\"3827080\">have</span> <span m=\"3827200\">two</span> <span\
  \ m=\"3827770\">separate</span> <span m=\"3828580\">limit</span> <span m=\"3828850\"\
  >points,</span> <span m=\"3830110\">you</span> <span m=\"3830230\">must</span> <span\
  \ m=\"3831100\">have</span> <span m=\"3831940\">that</span> <span m=\"3832660\"\
  >this</span> <span m=\"3833680\">sequence,</span> <span m=\"3834590\">at</span>\
  \ <span m=\"3834700\">least</span> <span m=\"3834970\">along</span> <span m=\"3835480\"\
  >a</span> <span m=\"3835540\">subsequence</span> <span m=\"3836140\">that</span>\
  \ <span m=\"3836350\">converges</span> <span m=\"3836880\">to</span> <span m=\"\
  3836980\">W,</span> <span m=\"3837990\">converges</span> <span m=\"3840010\">in</span>\
  \ <span m=\"3840360\">F</span> <span m=\"3840550\">densities</span> <span m=\"3841390\"\
  >to</span> <span m=\"3841720\">W.</span> <span m=\"3844510\">So</span> <span m=\"\
  3845340\">initially,</span> <span m=\"3845790\">this</span> <span m=\"3845970\"\
  >is</span> <span m=\"3846060\">true</span> <span m=\"3846270\">along</span> <span\
  \ m=\"3846570\">subsequence.</span> <span m=\"3847260\">But</span> <span m=\"3847620\"\
  >the</span> <span m=\"3847710\">left-hand</span> <span m=\"3848010\">side</span>\
  \ <span m=\"3848250\">is</span> <span m=\"3848490\">convergent,</span> <span m=\"\
  3849160\">so</span> <span m=\"3849360\">this</span> <span m=\"3849510\">is</span>\
  \ <span m=\"3849630\">true</span> <span m=\"3850050\">along</span> <span m=\"3850320\"\
  >the</span> <span m=\"3850380\">sequence.</span></p><p><span m=\"3852790\">But</span>\
  \ <span m=\"3853150\">u</span> <span m=\"3853420\">is</span> <span m=\"3853570\"\
  >also</span> <span m=\"3853810\">a</span> <span m=\"3853850\">limit</span> <span\
  \ m=\"3854030\">point.</span> <span m=\"3855370\">So</span> <span m=\"3855580\"\
  >the</span> <span m=\"3855670\">same</span> <span m=\"3856210\">is</span> <span\
  \ m=\"3856390\">true</span> <span m=\"3861610\">for</span> <span m=\"3861790\">u.</span>\
  \ <span m=\"3866337\">And</span> <span m=\"3866820\">therefore,</span> <span m=\"\
  3871310\">the</span> <span m=\"3871670\">F</span> <span m=\"3871880\">density</span>\
  \ <span m=\"3872300\">in</span> <span m=\"3872450\">W</span> <span m=\"3873200\"\
  >must</span> <span m=\"3873410\">equal</span> <span m=\"3873740\">to</span> <span\
  \ m=\"3873890\">the</span> <span m=\"3873980\">F</span> <span m=\"3874190\">density</span>\
  \ <span m=\"3874670\">in</span> <span m=\"3875430\">u</span> <span m=\"3876230\"\
  >for</span> <span m=\"3876470\">all</span> <span m=\"3877880\">F.</span></p><p><span\
  \ m=\"3885670\">So</span> <span m=\"3886210\">we</span> <span m=\"3886450\">would</span>\
  \ <span m=\"3886600\">be</span> <span m=\"3886720\">done</span> <span m=\"3887080\"\
  >if</span> <span m=\"3887200\">we</span> <span m=\"3887290\">can</span> <span m=\"\
  3887440\">prove</span> <span m=\"3888160\">that</span> <span m=\"3888400\">the</span>\
  \ <span m=\"3888670\">F</span> <span m=\"3888910\">densities,</span> <span m=\"\
  3889420\">the</span> <span m=\"3889510\">collection</span> <span m=\"3890050\">of</span>\
  \ <span m=\"3890200\">all</span> <span m=\"3890350\">these</span> <span m=\"3890620\"\
  >F</span> <span m=\"3890800\">densities,</span> <span m=\"3891670\">they</span>\
  \ <span m=\"3892120\">determine</span> <span m=\"3892720\">the</span> <span m=\"\
  3892810\">graphon.</span> <span m=\"3893970\">And</span> <span m=\"3894100\">that's</span>\
  \ <span m=\"3894280\">indeed</span> <span m=\"3894520\">the</span> <span m=\"3894580\"\
  >case. And</span> <span m=\"3895080\">so</span> <span m=\"3895120\">this</span>\
  \ <span m=\"3895300\">is</span> <span m=\"3895420\">the</span> <span m=\"3895510\"\
  >next</span> <span m=\"3895810\">claim.</span> <span m=\"3896540\">So</span> <span\
  \ m=\"3897780\">it's</span> <span m=\"3899080\">what</span> <span m=\"3899230\"\
  >I</span> <span m=\"3899290\">will</span> <span m=\"3899380\">call</span> <span\
  \ m=\"3899650\">a</span> <span m=\"3899680\">moment</span> <span m=\"3900140\">lemma,</span>\
  \ <span m=\"3903870\">is</span> <span m=\"3904020\">that</span> <span m=\"3904290\"\
  >if</span> <span m=\"3905880\">u</span> <span m=\"3906120\">and</span> <span m=\"\
  3906240\">W</span> <span m=\"3908360\">are</span> <span m=\"3908880\">graphons</span>\
  \ <span m=\"3911340\">such</span> <span m=\"3911640\">that</span> <span m=\"3917060\"\
  >the</span> <span m=\"3917210\">F</span> <span m=\"3917450\">densities</span> <span\
  \ m=\"3919670\">agree</span> <span m=\"3920180\">for</span> <span m=\"3920420\"\
  >all</span> <span m=\"3921320\">F,</span> <span m=\"3922970\">then</span> <span\
  \ m=\"3925220\">the</span> <span m=\"3925370\">cut</span> <span m=\"3925670\">distance</span>\
  \ <span m=\"3926120\">between</span> <span m=\"3926990\">u</span> <span m=\"3927380\"\
  >and</span> <span m=\"3927500\">W</span> <span m=\"3928530\">is</span> <span m=\"\
  3928700\">equal</span> <span m=\"3929030\">to</span> <span m=\"3929210\">0.</span></p><p><span\
  \ m=\"3931910\">Somehow</span> <span m=\"3932060\">the</span> <span m=\"3932240\"\
  >local</span> <span m=\"3932770\">statistics</span> <span m=\"3933380\">tells</span>\
  \ <span m=\"3933770\">you</span> <span m=\"3934160\">globally</span> <span m=\"\
  3934880\">that</span> <span m=\"3935000\">these</span> <span m=\"3935180\">two</span>\
  \ <span m=\"3935330\">graphons</span> <span m=\"3935840\">must</span> <span m=\"\
  3936110\">agree</span> <span m=\"3936380\">with</span> <span m=\"3936590\">each</span>\
  \ <span m=\"3936740\">other.</span> <span m=\"3939420\">Does anyone</span> <span\
  \ m=\"3939790\">know</span> <span m=\"3939890\">why</span> <span m=\"3940130\">I</span>\
  \ <span m=\"3940220\">call</span> <span m=\"3940460\">it</span> <span m=\"3940530\"\
  >a</span> <span m=\"3940580\">moment</span> <span m=\"3940960\">lemma?</span> <span\
  \ m=\"3942360\">There</span> <span m=\"3942590\">is</span> <span m=\"3942680\">something</span>\
  \ <span m=\"3943010\">else</span> <span m=\"3944050\">which</span> <span m=\"3944440\"\
  >this</span> <span m=\"3944630\">should</span> <span m=\"3945200\">remind</span>\
  \ <span m=\"3945530\">you</span> <span m=\"3945710\">of.</span> <span m=\"3946730\"\
  >So</span> <span m=\"3946970\">there</span> <span m=\"3947090\">are</span> <span\
  \ m=\"3947150\">some</span> <span m=\"3947330\">classical</span> <span m=\"3947810\"\
  >results</span> <span m=\"3948350\">in</span> <span m=\"3949130\">probability</span>\
  \ <span m=\"3949930\">that</span> <span m=\"3950040\">tells</span> <span m=\"3950360\"\
  >you,</span> <span m=\"3950630\">if</span> <span m=\"3950750\">you</span> <span\
  \ m=\"3950870\">have</span> <span m=\"3951140\">two</span> <span m=\"3951440\">probability</span>\
  \ <span m=\"3951980\">distributions,</span> <span m=\"3953240\">both,</span> <span\
  \ m=\"3953690\">assume</span> <span m=\"3954440\">are</span> <span m=\"3954920\"\
  >nice</span> <span m=\"3955280\">enough,</span> <span m=\"3956120\">then</span>\
  \ <span m=\"3956750\">if</span> <span m=\"3956930\">they</span> <span m=\"3957080\"\
  >have</span> <span m=\"3957290\">the</span> <span m=\"3957380\">same</span> <span\
  \ m=\"3957830\">k'th</span> <span m=\"3958340\">moment</span> <span m=\"3958850\"\
  >for</span> <span m=\"3959000\">every</span> <span m=\"3959220\">k,</span> <span\
  \ m=\"3960030\">so</span> <span m=\"3960460\">first</span> <span m=\"3960760\">moment,</span>\
  \ <span m=\"3961050\">second</span> <span m=\"3961230\">moment,</span> <span m=\"\
  3961490\">third</span> <span m=\"3961660\">moment,</span> <span m=\"3962450\">if</span>\
  \ <span m=\"3962570\">all</span> <span m=\"3962750\">the</span> <span m=\"3962840\"\
  >moments</span> <span m=\"3963200\">agree,</span> <span m=\"3963770\">that</span>\
  \ <span m=\"3963920\">these</span> <span m=\"3964130\">two</span> <span m=\"3964340\"\
  >probability</span> <span m=\"3964940\">distributions</span> <span m=\"3965660\"\
  >should</span> <span m=\"3965900\">agree.</span></p><p><span m=\"3967260\">And</span>\
  \ <span m=\"3967430\">this</span> <span m=\"3967850\">is</span> <span m=\"3968510\"\
  >some</span> <span m=\"3968900\">graphical</span> <span m=\"3969530\">version</span>\
  \ <span m=\"3969890\">of</span> <span m=\"3969980\">that.</span> <span m=\"3970130\"\
  >So</span> <span m=\"3970250\">instead</span> <span m=\"3970610\">of</span> <span\
  \ m=\"3970700\">looking</span> <span m=\"3971000\">at</span> <span m=\"3971080\"\
  >the</span> <span m=\"3971150\">probability</span> <span m=\"3971720\">distribution,</span>\
  \ <span m=\"3972600\">we're</span> <span m=\"3972650\">looking</span> <span m=\"\
  3972950\">at</span> <span m=\"3973040\">graphons,</span> <span m=\"3973910\">which</span>\
  \ <span m=\"3974120\">are</span> <span m=\"3974510\">two-dimensional.</span> <span\
  \ m=\"3975590\">These</span> <span m=\"3975740\">are</span> <span m=\"3975800\"\
  >two-dimensional</span> <span m=\"3976490\">objects.</span> <span m=\"3977240\"\
  >And</span> <span m=\"3977360\">this</span> <span m=\"3977510\">moments</span> <span\
  \ m=\"3977870\">lemma</span> <span m=\"3978110\">tells</span> <span m=\"3978350\"\
  >you</span> <span m=\"3978440\">that</span> <span m=\"3978560\">in</span> <span\
  \ m=\"3978710\">these</span> <span m=\"3978860\">two-dimensional,</span> <span m=\"\
  3979760\">in</span> <span m=\"3979880\">the</span> <span m=\"3980000\">corresponding</span>\
  \ <span m=\"3980630\">two-dimensional</span> <span m=\"3981230\">moments,</span>\
  \ <span m=\"3981620\">namely</span> <span m=\"3981890\">these</span> <span m=\"\
  3982160\">F</span> <span m=\"3982370\">moments,</span> <span m=\"3983270\">if</span>\
  \ <span m=\"3983420\">they</span> <span m=\"3983600\">agree,</span> <span m=\"3984660\"\
  >then</span> <span m=\"3985040\">the</span> <span m=\"3985160\">two</span> <span\
  \ m=\"3986270\">graphons</span> <span m=\"3986900\">must</span> <span m=\"3987140\"\
  >agree.</span> <span m=\"3990240\">So</span> <span m=\"3990410\">it's</span> <span\
  \ m=\"3990540\">the</span> <span m=\"3990870\">analog</span> <span m=\"3991470\"\
  >of</span> <span m=\"3991680\">the</span> <span m=\"3992370\">probability</span>\
  \ <span m=\"3993390\">theory</span> <span m=\"3993810\">statement</span> <span m=\"\
  3994350\">about</span> <span m=\"3996030\">moments.</span></p><p><span m=\"3997860\"\
  >The</span> <span m=\"3998010\">proof</span> <span m=\"3998340\">is</span> <span\
  \ m=\"3998460\">actually</span> <span m=\"3998730\">somewhat</span> <span m=\"3998970\"\
  >tricky.</span> <span m=\"3999540\">So</span> <span m=\"3999690\">I'm</span> <span\
  \ m=\"3999840\">only</span> <span m=\"4000080\">going</span> <span m=\"4000260\"\
  >to</span> <span m=\"4000320\">give</span> <span m=\"4000500\">you</span> <span\
  \ m=\"4000650\">a</span> <span m=\"4000710\">sketch.</span> <span m=\"4004880\"\
  >And</span> <span m=\"4005060\">the</span> <span m=\"4005150\">key</span> <span\
  \ m=\"4005450\">here</span> <span m=\"4005990\">is</span> <span m=\"4006200\">to</span>\
  \ <span m=\"4006350\">consider</span> <span m=\"4006920\">the</span> <span m=\"\
  4007100\">W</span> <span m=\"4007460\">random</span> <span m=\"4007850\">graph,</span>\
  \ <span m=\"4009350\">which</span> <span m=\"4009590\">we</span> <span m=\"4009740\"\
  >saw</span> <span m=\"4010370\">last</span> <span m=\"4010760\">lecture.</span>\
  \ <span m=\"4017326\">So</span> <span m=\"4017800\">this</span> <span m=\"4017980\"\
  >is</span> <span m=\"4018040\">W</span> <span m=\"4018370\">random</span> <span\
  \ m=\"4018670\">graph</span> <span m=\"4018940\">with</span> <span m=\"4019090\"\
  >k</span> <span m=\"4019330\">vertices</span> <span m=\"4020320\">sampled</span>\
  \ <span m=\"4020900\">using</span> <span m=\"4021220\">the</span> <span m=\"4021310\"\
  >graphon</span> <span m=\"4021770\">W.</span></p><p><span m=\"4026070\">So</span>\
  \ <span m=\"4027040\">a</span> <span m=\"4027120\">key</span> <span m=\"4027360\"\
  >observation</span> <span m=\"4027960\">here</span> <span m=\"4028710\">is</span>\
  \ <span m=\"4028860\">that,</span> <span m=\"4029010\">for</span> <span m=\"4029250\"\
  >every</span> <span m=\"4029610\">F,</span> <span m=\"4031390\">the</span> <span\
  \ m=\"4031560\">probability</span> <span m=\"4032790\">that</span> <span m=\"4036260\"\
  >the</span> <span m=\"4037560\">sampled</span> <span m=\"4038800\">W</span> <span\
  \ m=\"4039140\">random</span> <span m=\"4039500\">graph</span> <span m=\"4041180\"\
  >agrees</span> <span m=\"4042830\">with</span> <span m=\"4044152\">F--</span> <span\
  \ m=\"4046560\">and</span> <span m=\"4047170\">here,</span> <span m=\"4048320\"\
  >there is</span> <span m=\"4048990\">a</span> <span m=\"4049030\">bit</span> <span\
  \ m=\"4049210\">of</span> <span m=\"4049280\">a</span> <span m=\"4049300\">technicality.</span>\
  \ <span m=\"4049960\">I</span> <span m=\"4050020\">want</span> <span m=\"4050200\"\
  >them</span> <span m=\"4050320\">to</span> <span m=\"4050440\">agree</span> <span\
  \ m=\"4050770\">as</span> <span m=\"4050980\">labeled</span> <span m=\"4051460\"\
  >graphs.</span> <span m=\"4055880\">So</span> <span m=\"4056470\">the</span> <span\
  \ m=\"4056610\">vertices</span> <span m=\"4057090\">of</span> <span m=\"4057180\"\
  >W</span> <span m=\"4057480\">are</span> <span m=\"4057650\">a</span> <span m=\"\
  4057780\">priori</span> <span m=\"4058170\">labeled</span> <span m=\"4058530\">1</span>\
  \ <span m=\"4058710\">through</span> <span m=\"4058860\">k.</span> <span m=\"4059340\"\
  >And</span> <span m=\"4059700\">this</span> <span m=\"4060030\">kW</span> <span\
  \ m=\"4060780\">random</span> <span m=\"4061020\">graph</span> <span m=\"4061350\"\
  >is</span> <span m=\"4061920\">generated</span> <span m=\"4062730\">with</span>\
  \ <span m=\"4062910\">vertices</span> <span m=\"4063330\">labeled</span> <span m=\"\
  4063840\">1</span> <span m=\"4064020\">through</span> <span m=\"4064170\">k.</span>\
  \ <span m=\"4064890\">They</span> <span m=\"4065040\">agree</span> <span m=\"4066090\"\
  >with</span> <span m=\"4066450\">some</span> <span m=\"4066750\">probability</span>\
  \ <span m=\"4067890\">that</span> <span m=\"4068070\">is</span> <span m=\"4068220\"\
  >completely</span> <span m=\"4068640\">determined</span> <span m=\"4069540\">by</span>\
  \ <span m=\"4070230\">the</span> <span m=\"4071120\">F</span> <span m=\"4071545\"\
  >densities.</span> <span m=\"4074440\">Yes?</span></p><p><span m=\"4074670\">AUDIENCE:</span>\
  \ <span m=\"4074813\">Is</span> <span m=\"4074956\">k</span> <span m=\"4075100\"\
  >the</span> <span m=\"4075243\">number</span> <span m=\"4075386\">of</span> <span\
  \ m=\"4075530\">vertices of</span> <span m=\"4075960\">F?</span></p><p><span m=\"\
  4076740\">PROFESSOR:</span> <span m=\"4076942\">Yeah,</span> <span m=\"4077145\"\
  >so</span> <span m=\"4077550\">k</span> <span m=\"4077890\">is</span> <span m=\"\
  4078020\">the</span> <span m=\"4078110\">number</span> <span m=\"4078350\">of</span>\
  \ <span m=\"4078410\">vertices</span> <span m=\"4078830\">of</span> <span m=\"4078920\"\
  >F.</span> <span m=\"4082390\">And</span> <span m=\"4082960\">the</span> <span m=\"\
  4083110\">specific</span> <span m=\"4083590\">formula</span> <span m=\"4084020\"\
  >is</span> <span m=\"4084130\">not</span> <span m=\"4084340\">so</span> <span m=\"\
  4084490\">important.</span> <span m=\"4084900\">Let</span> <span m=\"4085000\">me</span>\
  \ <span m=\"4085090\">just</span> <span m=\"4085240\">write</span> <span m=\"4085450\"\
  >it</span> <span m=\"4085510\">down.</span> <span m=\"4085950\">But</span> <span\
  \ m=\"4086080\">the</span> <span m=\"4086140\">point is</span> <span m=\"4086390\"\
  >that,</span> <span m=\"4086470\">if</span> <span m=\"4086680\">you</span> <span\
  \ m=\"4086830\">know</span> <span m=\"4087250\">all</span> <span m=\"4087490\">the</span>\
  \ <span m=\"4087670\">F</span> <span m=\"4087870\">densities,</span> <span m=\"\
  4088850\">then</span> <span m=\"4089470\">you</span> <span m=\"4089650\">have</span>\
  \ <span m=\"4089980\">all</span> <span m=\"4090130\">the</span> <span m=\"4090220\"\
  >information</span> <span m=\"4090940\">about</span> <span m=\"4091360\">the</span>\
  \ <span m=\"4091630\">distribution</span> <span m=\"4092500\">of</span> <span m=\"\
  4092710\">this</span> <span m=\"4092950\">W</span> <span m=\"4093400\">random</span>\
  \ <span m=\"4093700\">graph.</span></p><p><span m=\"4095110\">And</span> <span m=\"\
  4095260\">the</span> <span m=\"4095380\">way</span> <span m=\"4095620\">you</span>\
  \ <span m=\"4095770\">can</span> <span m=\"4095950\">calculate</span> <span m=\"\
  4096700\">the</span> <span m=\"4096850\">actual</span> <span m=\"4097720\">probability</span>\
  \ <span m=\"4098810\">is</span> <span m=\"4099040\">via an</span> <span m=\"4099529\"\
  >inclusion</span> <span m=\"4100149\">exclusion.</span> <span m=\"4103840\">And</span>\
  \ <span m=\"4103930\">the</span> <span m=\"4104020\">reason</span> <span m=\"4104260\"\
  >we</span> <span m=\"4104380\">have</span> <span m=\"4104529\">to</span> <span m=\"\
  4104620\">do</span> <span m=\"4104740\">this</span> <span m=\"4104890\">inclusion</span>\
  \ <span m=\"4105310\">exclusion</span> <span m=\"4106090\">is</span> <span m=\"\
  4106240\">just</span> <span m=\"4106450\">because</span> <span m=\"4106870\">this</span>\
  \ <span m=\"4107080\">is</span> <span m=\"4107200\">more</span> <span m=\"4107380\"\
  >like</span> <span m=\"4107979\">counting</span> <span m=\"4108340\">induced</span>\
  \ <span m=\"4108850\">subgraphs.</span> <span m=\"4109760\">And</span> <span m=\"\
  4110109\">this</span> <span m=\"4110290\">is</span> <span m=\"4110620\">counting</span>\
  \ <span m=\"4111040\">actual</span> <span m=\"4111340\">subgraphs.</span> <span\
  \ m=\"4111939\">So</span> <span m=\"4112090\">there</span> <span m=\"4112210\">is</span>\
  \ <span m=\"4112960\">an</span> <span m=\"4113050\">extra</span> <span m=\"4113350\"\
  >step.</span> <span m=\"4113770\">But</span> <span m=\"4114430\">the</span> <span\
  \ m=\"4114520\">point</span> <span m=\"4114819\">is</span> <span m=\"4114910\">that,</span>\
  \ <span m=\"4115000\">if</span> <span m=\"4115210\">you</span> <span m=\"4115330\"\
  >knew</span> <span m=\"4115750\">this</span> <span m=\"4116020\">data,</span> <span\
  \ m=\"4116350\">the</span> <span m=\"4116470\">moment's</span> <span m=\"4116880\"\
  >data</span> <span m=\"4117189\">then</span> <span m=\"4117399\">you</span> <span\
  \ m=\"4117520\">immediately</span> <span m=\"4118090\">know</span> <span m=\"4118359\"\
  >the</span> <span m=\"4118460\">distribution</span> <span m=\"4119590\">of</span>\
  \ <span m=\"4119740\">the</span> <span m=\"4119800\">W</span> <span m=\"4120069\"\
  >random</span> <span m=\"4120340\">graphs.</span></p><p>&nbsp;</p><p><span m=\"\
  4131800\">OK,</span> <span m=\"4132020\">so</span> <span m=\"4132160\">if</span>\
  \ <span m=\"4132279\">I</span> <span m=\"4132340\">have</span> <span m=\"4132550\"\
  >two</span> <span m=\"4132760\">graphons</span> <span m=\"4133510\">for</span> <span\
  \ m=\"4133660\">which</span> <span m=\"4134020\">I</span> <span m=\"4134830\">know</span>\
  \ <span m=\"4136149\">that</span> <span m=\"4136359\">their</span> <span m=\"4137240\"\
  >F</span> <span m=\"4137520\">densities</span> <span m=\"4138130\">agree,</span>\
  \ <span m=\"4139210\">then</span> <span m=\"4139779\">I</span> <span m=\"4139930\"\
  >should</span> <span m=\"4140200\">be</span> <span m=\"4140350\">able</span> <span\
  \ m=\"4140620\">to</span> <span m=\"4142090\">conclude</span> <span m=\"4143410\"\
  >that</span> <span m=\"4144189\">the</span> <span m=\"4144279\">corresponding</span>\
  \ <span m=\"4145330\">W</span> <span m=\"4145660\">random</span> <span m=\"4145930\"\
  >graphs</span> <span m=\"4147340\">also</span> <span m=\"4147640\">have</span> <span\
  \ m=\"4147760\">the</span> <span m=\"4147850\">same</span> <span m=\"4148300\">distribution,</span>\
  \ <span m=\"4152890\">in</span> <span m=\"4153010\">particular,</span> <span m=\"\
  4159580\">this,</span> <span m=\"4159939\">the</span> <span m=\"4160189\">W</span>\
  \ <span m=\"4160540\">random</span> <span m=\"4160840\">graph</span> <span m=\"\
  4161950\">and</span> <span m=\"4162584\">the</span> <span m=\"4162890\">u</span>\
  \ <span m=\"4163210\">random</span> <span m=\"4163600\">graph</span> <span m=\"\
  4165340\">have</span> <span m=\"4165490\">the</span> <span m=\"4165580\">same</span>\
  \ <span m=\"4166210\">distribution.</span> <span m=\"4174010\">I</span> <span m=\"\
  4174350\">am</span> <span m=\"4174460\">going</span> <span m=\"4174670\">to</span>\
  \ <span m=\"4174729\">create</span> <span m=\"4175270\">a</span> <span m=\"4175870\"\
  >variant</span> <span m=\"4176500\">of</span> <span m=\"4176590\">the</span> <span\
  \ m=\"4176680\">W</span> <span m=\"4176950\">random</span> <span m=\"4177220\">graph</span>\
  \ <span m=\"4177939\">which</span> <span m=\"4178359\">is</span> <span m=\"4179290\"\
  >something</span> <span m=\"4179590\">called</span> <span m=\"4179740\">an</span>\
  \ <span m=\"4180040\">H</span> <span m=\"4180340\">random</span> <span m=\"4180729\"\
  >graph.</span> <span m=\"4182979\">It's</span> <span m=\"4183189\">kind</span> <span\
  \ m=\"4183520\">of</span> <span m=\"4183580\">like</span> <span m=\"4183790\">the</span>\
  \ <span m=\"4183880\">W</span> <span m=\"4184180\">random</span> <span m=\"4184420\"\
  >graph except</span> <span m=\"4185020\">I</span> <span m=\"4185109\">forget</span>\
  \ <span m=\"4185439\">the</span> <span m=\"4185500\">very</span> <span m=\"4185770\"\
  >last</span> <span m=\"4186069\">step.</span></p><p><span m=\"4186800\">So</span>\
  \ <span m=\"4186850\">I</span> <span m=\"4186939\">only</span> <span m=\"4187240\"\
  >keep</span> <span m=\"4189069\">a</span> <span m=\"4189850\">weighted--</span>\
  \ <span m=\"4191319\">think</span> <span m=\"4191529\">of</span> <span m=\"4191620\"\
  >it</span> <span m=\"4191770\">as,</span> <span m=\"4193770\">so</span> <span m=\"\
  4194080\">think</span> <span m=\"4194260\">this</span> <span m=\"4194440\">is</span>\
  \ <span m=\"4196490\">an</span> <span m=\"4196870\">edge-weighted</span> <span m=\"\
  4197440\">graph</span> <span m=\"4205950\">where</span> <span m=\"4206310\">you</span>\
  \ <span m=\"4206490\">sample</span> <span m=\"4209960\">x1</span> <span m=\"4210470\"\
  >through</span> <span m=\"4210740\">xk</span> <span m=\"4212920\">uniformly</span>\
  \ <span m=\"4215360\">between</span> <span m=\"4215630\">0</span> <span m=\"4215890\"\
  >and</span> <span m=\"4215990\">1.</span> <span m=\"4216860\">And</span> <span m=\"\
  4217070\">I</span> <span m=\"4217160\">put</span> <span m=\"4217520\">edge</span>\
  \ <span m=\"4217760\">weight</span> <span m=\"4220310\">between</span> <span m=\"\
  4220850\">i</span> <span m=\"4221430\">and</span> <span m=\"4221570\">j</span> <span\
  \ m=\"4222370\">to</span> <span m=\"4222470\">be</span> <span m=\"4223316\">W</span>\
  \ <span m=\"4224230\">of</span> <span m=\"4224810\">xi</span> <span m=\"4225500\"\
  >xj.</span> <span m=\"4226680\">So</span> <span m=\"4226790\">the</span> <span m=\"\
  4226880\">difference</span> <span m=\"4227300\">between</span> <span m=\"4227630\"\
  >this</span> <span m=\"4228170\">H</span> <span m=\"4228410\">version</span> <span\
  \ m=\"4228770\">and</span> <span m=\"4228860\">the</span> <span m=\"4228950\">G</span>\
  \ <span m=\"4229160\">version</span> <span m=\"4229580\">is</span> <span m=\"4229730\"\
  >that</span> <span m=\"4229850\">the</span> <span m=\"4229940\">G</span> <span m=\"\
  4230150\">version</span> <span m=\"4230510\">is</span> <span m=\"4230720\">obtained</span>\
  \ <span m=\"4231110\">by</span> <span m=\"4231680\">turning</span> <span m=\"4232160\"\
  >this</span> <span m=\"4232370\">weight</span> <span m=\"4232670\">into</span> <span\
  \ m=\"4233000\">an</span> <span m=\"4233120\">actual</span> <span m=\"4233510\"\
  >edge</span> <span m=\"4234120\">with</span> <span m=\"4234310\">that</span> <span\
  \ m=\"4234470\">probability,</span> <span m=\"4235880\">but</span> <span m=\"4236000\"\
  >if</span> <span m=\"4236120\">I</span> <span m=\"4236210\">don't</span> <span m=\"\
  4236390\">do</span> <span m=\"4236510\">the</span> <span m=\"4236600\">last</span>\
  \ <span m=\"4236810\">step,</span> <span m=\"4237320\">I</span> <span m=\"4237500\"\
  >obtain</span> <span m=\"4237810\">this</span> <span m=\"4237950\">intermediate</span>\
  \ <span m=\"4238550\">object.</span></p><p><span m=\"4241150\">So</span> <span m=\"\
  4245680\">the</span> <span m=\"4245800\">following</span> <span m=\"4246280\">are</span>\
  \ <span m=\"4246370\">true.</span> <span m=\"4246920\">And</span> <span m=\"4247270\"\
  >this</span> <span m=\"4247450\">is</span> <span m=\"4247570\">where</span> <span\
  \ m=\"4247780\">I'm</span> <span m=\"4247930\">going</span> <span m=\"4248200\"\
  >to</span> <span m=\"4248560\">skip</span> <span m=\"4248920\">the</span> <span\
  \ m=\"4249010\">proofs.</span> <span m=\"4252700\">If</span> <span m=\"4252850\"\
  >I</span> <span m=\"4252940\">look</span> <span m=\"4253120\">at</span> <span m=\"\
  4254820\">this</span> <span m=\"4255190\">H</span> <span m=\"4255510\">random</span>\
  \ <span m=\"4255930\">graph</span> <span m=\"4258120\">and</span> <span m=\"4258870\"\
  >the</span> <span m=\"4258990\">G</span> <span m=\"4259260\">random</span> <span\
  \ m=\"4259650\">graph,</span> <span m=\"4262430\">they</span> <span m=\"4262640\"\
  >are</span> <span m=\"4262790\">very</span> <span m=\"4263030\">close</span> <span\
  \ m=\"4263480\">in</span> <span m=\"4263600\">cut</span> <span m=\"4263870\">distance.</span>\
  \ <span m=\"4265700\">You</span> <span m=\"4265760\">can</span> <span m=\"4265910\"\
  >think</span> <span m=\"4266120\">of</span> <span m=\"4266210\">this</span> <span\
  \ m=\"4266450\">as</span> <span m=\"4266630\">the</span> <span m=\"4266720\">claim</span>\
  \ <span m=\"4267080\">that</span> <span m=\"4267200\">G and P</span> <span m=\"\
  4267830\">is</span> <span m=\"4267950\">very</span> <span m=\"4268190\">close</span>\
  \ <span m=\"4268490\">to</span> <span m=\"4268610\">G</span> <span m=\"4269360\"\
  >in</span> <span m=\"4269660\">cut</span> <span m=\"4269900\">distance.</span> <span\
  \ m=\"4271250\">So</span> <span m=\"4271400\">they are</span> <span m=\"4271610\"\
  >very</span> <span m=\"4271820\">close</span> <span m=\"4272150\">in</span> <span\
  \ m=\"4272270\">cut</span> <span m=\"4272450\">distance.</span> <span m=\"4278160\"\
  >As</span> <span m=\"4278360\">k</span> <span m=\"4278630\">going</span> <span m=\"\
  4278840\">to</span> <span m=\"4278990\">infinity</span> <span m=\"4280070\">with</span>\
  \ <span m=\"4280370\">probability</span> <span m=\"4281300\">1--</span> <span m=\"\
  4283550\">so</span> <span m=\"4283980\">now I'm</span> <span m=\"4284360\">going</span>\
  \ <span m=\"4284460\">to</span> <span m=\"4284540\">do</span> <span m=\"4284660\"\
  >the</span> <span m=\"4284750\">proof.</span> <span m=\"4285050\">But</span> <span\
  \ m=\"4285230\">it's</span> <span m=\"4285370\">some</span> <span m=\"4285650\"\
  >kind</span> <span m=\"4285980\">of</span> <span m=\"4286070\">a</span> <span m=\"\
  4286130\">concentration</span> <span m=\"4287270\">argument.</span></p><p><span\
  \ m=\"4293990\">And</span> <span m=\"4294170\">the</span> <span m=\"4294260\">second</span>\
  \ <span m=\"4294620\">claim</span> <span m=\"4295370\">is</span> <span m=\"4295550\"\
  >that</span> <span m=\"4298330\">the</span> <span m=\"4298780\">H</span> <span m=\"\
  4299380\">random</span> <span m=\"4299710\">graph</span> <span m=\"4301290\">is</span>\
  \ <span m=\"4301450\">actually</span> <span m=\"4301930\">very</span> <span m=\"\
  4302230\">close</span> <span m=\"4302680\">to</span> <span m=\"4304240\">the</span>\
  \ <span m=\"4304360\">original</span> <span m=\"4304870\">graphon</span> <span m=\"\
  4305380\">W,</span> <span m=\"4306280\">as</span> <span m=\"4306430\">well.</span>\
  \ <span m=\"4311260\">This</span> <span m=\"4311310\">is</span> <span m=\"4311430\"\
  >also</span> <span m=\"4312680\">little</span> <span m=\"4313020\">l1</span> <span\
  \ m=\"4313230\">in</span> <span m=\"4313320\">distance</span> <span m=\"4314250\"\
  >as</span> <span m=\"4314430\">k</span> <span m=\"4315120\">goes</span> <span m=\"\
  4315360\">to</span> <span m=\"4315450\">infinity.</span> <span m=\"4317770\">So</span>\
  \ <span m=\"4317790\">this</span> <span m=\"4317970\">one</span> <span m=\"4318120\"\
  >is,</span> <span m=\"4319290\">again,</span> <span m=\"4319710\">not</span> <span\
  \ m=\"4319920\">so</span> <span m=\"4320280\">obvious.</span> <span m=\"4321180\"\
  >But</span> <span m=\"4321570\">it's</span> <span m=\"4322110\">easier</span> <span\
  \ m=\"4325900\">in</span> <span m=\"4326080\">the</span> <span m=\"4326170\">case</span>\
  \ <span m=\"4326620\">when</span> <span m=\"4328270\">W</span> <span m=\"4328870\"\
  >itself</span> <span m=\"4329320\">is</span> <span m=\"4329470\">a</span> <span\
  \ m=\"4329500\">step</span> <span m=\"4329800\">function,</span> <span m=\"4333520\"\
  >in</span> <span m=\"4333610\">which</span> <span m=\"4333790\">case,</span> <span\
  \ m=\"4335470\">the</span> <span m=\"4335680\">produced</span> <span m=\"4336520\"\
  >H</span> <span m=\"4336970\">is</span> <span m=\"4337300\">almost</span> <span\
  \ m=\"4337660\">the</span> <span m=\"4337750\">same as</span> <span m=\"4338050\"\
  >W,</span> <span m=\"4338430\">except</span> <span m=\"4339190\">the</span> <span\
  \ m=\"4339310\">boundaries</span> <span m=\"4339940\">are</span> <span m=\"4340180\"\
  >slightly</span> <span m=\"4340600\">shifted,</span> <span m=\"4341320\">perhaps.</span>\
  \ <span m=\"4344150\">And</span> <span m=\"4344330\">so</span> <span m=\"4344450\"\
  >you</span> <span m=\"4344600\">first</span> <span m=\"4344930\">approximate</span>\
  \ <span m=\"4347030\">W</span> <span m=\"4347750\">by a</span> <span m=\"4348200\"\
  >step</span> <span m=\"4348500\">function,</span> <span m=\"4350890\">and</span>\
  \ <span m=\"4351160\">prove</span> <span m=\"4351550\">this</span> <span m=\"4351880\"\
  >up</span> <span m=\"4352030\">to</span> <span m=\"4352180\">an</span> <span m=\"\
  4352270\">epsilon</span> <span m=\"4352660\">approximation,</span> <span m=\"4353530\"\
  >and</span> <span m=\"4353650\">then</span> <span m=\"4353940\">let</span> <span\
  \ m=\"4354090\">the</span> <span m=\"4354190\">steps</span> <span m=\"4354550\"\
  >go</span> <span m=\"4354670\">to</span> <span m=\"4354790\">infinity.</span></p><p><span\
  \ m=\"4357470\">So</span> <span m=\"4357580\">if</span> <span m=\"4357660\">you</span>\
  \ <span m=\"4357850\">have</span> <span m=\"4358150\">these</span> <span m=\"4358420\"\
  >two</span> <span m=\"4359650\">claims,</span> <span m=\"4360370\">so</span> <span\
  \ m=\"4360610\">then</span> <span m=\"4361060\">we</span> <span m=\"4362860\">see</span>\
  \ <span m=\"4363700\">that</span> <span m=\"4364900\">this</span> <span m=\"4365290\"\
  >one</span> <span m=\"4365530\">here</span> <span m=\"4366790\">is</span> <span\
  \ m=\"4367510\">identically</span> <span m=\"4368080\">distributed</span> <span\
  \ m=\"4368980\">as</span> <span m=\"4375900\">ku.</span> <span m=\"4378640\">So</span>\
  \ <span m=\"4380980\">it</span> <span m=\"4381070\">should</span> <span m=\"4381580\"\
  >follow</span> <span m=\"4382360\">that</span> <span m=\"4382870\">the</span> <span\
  \ m=\"4382990\">corresponding</span> <span m=\"4384830\">H</span> <span m=\"4385180\"\
  >random</span> <span m=\"4385570\">graph</span> <span m=\"4386200\">for</span> <span\
  \ m=\"4386410\">u,</span> <span m=\"4391390\">if</span> <span m=\"4391550\">you</span>\
  \ <span m=\"4392110\">place</span> <span m=\"4392410\">the</span> <span m=\"4392500\"\
  >same</span> <span m=\"4392740\">inequalities</span> <span m=\"4393310\">by</span>\
  \ <span m=\"4393470\">the</span> <span m=\"4393800\">u</span> <span m=\"4394000\"\
  >versions,</span> <span m=\"4394765\">it</span> <span m=\"4395050\">should</span>\
  \ <span m=\"4395230\">also</span> <span m=\"4395470\">be</span> <span m=\"4395590\"\
  >true.</span> <span m=\"4396550\">So</span> <span m=\"4396730\">because</span> <span\
  \ m=\"4397180\">these</span> <span m=\"4397450\">two</span> <span m=\"4397720\"\
  >are</span> <span m=\"4398440\">the</span> <span m=\"4398530\">same</span> <span\
  \ m=\"4398950\">distribution,</span> <span m=\"4401730\">if</span> <span m=\"4401870\"\
  >you</span> <span m=\"4401940\">follow</span> <span m=\"4402660\">this</span> <span\
  \ m=\"4402840\">chain,</span> <span m=\"4403530\">you</span> <span m=\"4403680\"\
  >obtain</span> <span m=\"4404220\">that</span> <span m=\"4406650\">the</span> <span\
  \ m=\"4406810\">cut</span> <span m=\"4407080\">distance</span> <span m=\"4407500\"\
  >between</span> <span m=\"4407950\">u</span> <span m=\"4408670\">and</span> <span\
  \ m=\"4408790\">w</span> <span m=\"4409840\">is</span> <span m=\"4409990\">equal</span>\
  \ <span m=\"4410230\">to</span> <span m=\"4410320\">0.</span></p><p><span m=\"4418410\"\
  >I</span> <span m=\"4418500\">want</span> <span m=\"4418710\">to</span> <span m=\"\
  4420000\">close</span> <span m=\"4420660\">by</span> <span m=\"4421350\">mentioning,</span>\
  \ <span m=\"4424260\">in</span> <span m=\"4424380\">some</span> <span m=\"4424560\"\
  >sense--</span> <span m=\"4425790\">so</span> <span m=\"4426000\">here,</span> <span\
  \ m=\"4426420\">you</span> <span m=\"4426510\">have</span> <span m=\"4426690\">two</span>\
  \ <span m=\"4429120\">graphons</span> <span m=\"4429360\">that have</span> <span\
  \ m=\"4429600\">exactly</span> <span m=\"4430050\">the</span> <span m=\"4430170\"\
  >same</span> <span m=\"4430430\">F</span> <span m=\"4430580\">moments.</span> <span\
  \ m=\"4431770\">But</span> <span m=\"4431850\">what</span> <span m=\"4432030\">if</span>\
  \ <span m=\"4432300\">I</span> <span m=\"4432420\">give</span> <span m=\"4432600\"\
  >you</span> <span m=\"4432690\">two</span> <span m=\"4432900\">graphons</span> <span\
  \ m=\"4433380\">which</span> <span m=\"4434370\">have</span> <span m=\"4434580\"\
  >very</span> <span m=\"4434790\">similar</span> <span m=\"4435270\">moments</span>\
  \ <span m=\"4435660\">to</span> <span m=\"4435750\">each</span> <span m=\"4435900\"\
  >other?</span> <span m=\"4436500\">Can</span> <span m=\"4436710\">you</span> <span\
  \ m=\"4436860\">conclude</span> <span m=\"4438080\">that</span> <span m=\"4438330\"\
  >the</span> <span m=\"4438420\">two</span> <span m=\"4438660\">graphons</span> <span\
  \ m=\"4439140\">are</span> <span m=\"4439230\">close</span> <span m=\"4439620\"\
  >to</span> <span m=\"4439740\">each</span> <span m=\"4439950\">other?</span> <span\
  \ m=\"4441370\">And</span> <span m=\"4441490\">that will</span> <span m=\"4441690\"\
  >be</span> <span m=\"4441840\">some</span> <span m=\"4442020\">kind</span> <span\
  \ m=\"4442290\">of</span> <span m=\"4442350\">an</span> <span m=\"4442470\">inverse</span>\
  \ <span m=\"4443130\">counting</span> <span m=\"4443500\">lemma.</span> <span m=\"\
  4444510\">And</span> <span m=\"4444630\">in</span> <span m=\"4444720\">fact,</span>\
  \ <span m=\"4445020\">it</span> <span m=\"4445110\">does</span> <span m=\"4445350\"\
  >follow</span> <span m=\"4445860\">as</span> <span m=\"4446010\">a</span> <span\
  \ m=\"4446070\">corollary.</span></p><p><span m=\"4457070\">And</span> <span m=\"\
  4457270\">the</span> <span m=\"4457360\">statement</span> <span m=\"4457740\">is</span>\
  \ <span m=\"4457870\">that,</span> <span m=\"4457990\">for</span> <span m=\"4458140\"\
  >every</span> <span m=\"4458470\">epsilon,</span> <span m=\"4460340\">there</span>\
  \ <span m=\"4460420\">exists</span> <span m=\"4461380\">k</span> <span m=\"4462340\"\
  >and</span> <span m=\"4462580\">eta</span> <span m=\"4464065\">such</span> <span\
  \ m=\"4464560\">that</span> <span m=\"4466360\">if</span> <span m=\"4467280\">the</span>\
  \ <span m=\"4467350\">two</span> <span m=\"4467620\">graphons</span> <span m=\"\
  4469960\">u</span> <span m=\"4470830\">and</span> <span m=\"4470950\">W</span> <span\
  \ m=\"4472210\">are</span> <span m=\"4472330\">such</span> <span m=\"4472630\">that</span>\
  \ <span m=\"4474530\">the</span> <span m=\"4474800\">F</span> <span m=\"4475070\"\
  >densities</span> <span m=\"4479200\">do</span> <span m=\"4479350\">not</span> <span\
  \ m=\"4479860\">differ</span> <span m=\"4480280\">by</span> <span m=\"4480550\"\
  >more</span> <span m=\"4480910\">than</span> <span m=\"4481140\">eta</span> <span\
  \ m=\"4482080\">for</span> <span m=\"4482440\">every</span> <span m=\"4483800\"\
  >F</span> <span m=\"4484565\">on,</span> <span m=\"4485870\">at</span> <span m=\"\
  4486370\">most,</span> <span m=\"4486820\">k</span> <span m=\"4487120\">vertices,</span>\
  \ <span m=\"4491460\">then</span> <span m=\"4493100\">the</span> <span m=\"4493420\"\
  >cut</span> <span m=\"4493710\">distance</span> <span m=\"4495600\">between</span>\
  \ <span m=\"4496230\">u</span> <span m=\"4496590\">and</span> <span m=\"4496740\"\
  >W</span> <span m=\"4497460\">is,</span> <span m=\"4497910\">at</span> <span m=\"\
  4498030\">most,</span> <span m=\"4498660\">epsilon.</span> <span m=\"4501120\">So</span>\
  \ <span m=\"4501390\">the</span> <span m=\"4501690\">counting</span> <span m=\"\
  4502080\">lemma</span> <span m=\"4502290\">tells</span> <span m=\"4502560\">you,</span>\
  \ <span m=\"4502680\">if</span> <span m=\"4502860\">the</span> <span m=\"4502950\"\
  >cut</span> <span m=\"4503220\">distance</span> <span m=\"4503490\">is</span> <span\
  \ m=\"4503550\">small,</span> <span m=\"4503910\">then</span> <span m=\"4504150\"\
  >all</span> <span m=\"4504330\">the</span> <span m=\"4504540\">F</span> <span m=\"\
  4504960\">moments</span> <span m=\"4505470\">are</span> <span m=\"4505680\">close</span>\
  \ <span m=\"4506040\">to</span> <span m=\"4506160\">each</span> <span m=\"4506310\"\
  >other.</span> <span m=\"4507120\">And</span> <span m=\"4507210\">the</span> <span\
  \ m=\"4507270\">inverse</span> <span m=\"4508080\">tells</span> <span m=\"4508350\"\
  >you</span> <span m=\"4508840\">this</span> <span m=\"4509030\">converse.</span>\
  \ <span m=\"4509430\">So it</span> <span m=\"4509800\">tells</span> <span m=\"4510030\"\
  >you</span> <span m=\"4510150\">this,</span> <span m=\"4511080\">if</span> <span\
  \ m=\"4511290\">you</span> <span m=\"4511560\">have</span> <span m=\"4511920\">similar</span>\
  \ <span m=\"4512370\">F</span> <span m=\"4512580\">moments,</span> <span m=\"4513090\"\
  >up</span> <span m=\"4513480\">to</span> <span m=\"4513690\">a</span> <span m=\"\
  4513720\">certain</span> <span m=\"4514020\">point,</span> <span m=\"4514950\">then</span>\
  \ <span m=\"4515820\">this</span> <span m=\"4516000\">is</span> <span m=\"4516120\"\
  >small.</span></p><p><span m=\"4518690\">You</span> <span m=\"4518840\">can</span>\
  \ <span m=\"4519080\">deduce</span> <span m=\"4519620\">the</span> <span m=\"4519770\"\
  >inverse</span> <span m=\"4520100\">counting</span> <span m=\"4520400\">lemma</span>\
  \ <span m=\"4520720\">from</span> <span m=\"4521060\">the</span> <span m=\"4521150\"\
  >moments</span> <span m=\"4521560\">lemma</span> <span m=\"4522110\">via a</span>\
  \ <span m=\"4522530\">compactness</span> <span m=\"4523280\">argument</span> <span\
  \ m=\"4523730\">similar</span> <span m=\"4524150\">to</span> <span m=\"4524270\"\
  >the</span> <span m=\"4524360\">one</span> <span m=\"4524570\">that</span> <span\
  \ m=\"4524720\">we</span> <span m=\"4525890\">did</span> <span m=\"4526160\">in</span>\
  \ <span m=\"4526250\">class</span> <span m=\"4526580\">today.</span> <span m=\"\
  4527420\">And</span> <span m=\"4527630\">I</span> <span m=\"4527720\">want</span>\
  \ <span m=\"4527930\">to</span> <span m=\"4528290\">give</span> <span m=\"4528500\"\
  >you</span> <span m=\"4528590\">a</span> <span m=\"4528620\">chance</span> <span\
  \ m=\"4528920\">to</span> <span m=\"4529100\">practice</span> <span m=\"4529610\"\
  >with</span> <span m=\"4529730\">that</span> <span m=\"4529820\">argument.</span>\
  \ <span m=\"4530240\">So</span> <span m=\"4530360\">this</span> <span m=\"4530540\"\
  >will</span> <span m=\"4530630\">be</span> <span m=\"4530780\">on</span> <span m=\"\
  4530880\">the</span> <span m=\"4530930\">homework,</span> <span m=\"4531320\">for</span>\
  \ <span m=\"4531740\">the</span> <span m=\"4531830\">next</span> <span m=\"4532080\"\
  >homework.</span> <span m=\"4533120\">I'll</span> <span m=\"4533180\">give</span>\
  \ <span m=\"4533330\">you</span> <span m=\"4533420\">some</span> <span m=\"4533570\"\
  >practice</span> <span m=\"4534320\">with</span> <span m=\"4534500\">using</span>\
  \ <span m=\"4534860\">these</span> <span m=\"4535040\">compactness</span> <span\
  \ m=\"4535700\">arguments.</span></p><p><span m=\"4537780\">But</span> <span m=\"\
  4537960\">you</span> <span m=\"4538050\">see,</span> <span m=\"4539610\">just</span>\
  \ <span m=\"4539820\">with</span> <span m=\"4540270\">the</span> <span m=\"4540420\"\
  >other</span> <span m=\"4540570\">compactness</span> <span m=\"4541140\">statements,</span>\
  \ <span m=\"4542670\">it</span> <span m=\"4542760\">doesn't</span> <span m=\"4543000\"\
  >tell</span> <span m=\"4543240\">you</span> <span m=\"4543480\">anything</span>\
  \ <span m=\"4543900\">about</span> <span m=\"4544710\">the</span> <span m=\"4544830\"\
  >k</span> <span m=\"4545250\">and</span> <span m=\"4545400\">the</span> <span m=\"\
  4545520\">epsilon</span> <span m=\"4546860\">as</span> <span m=\"4546990\">a</span>\
  \ <span m=\"4547050\">function</span> <span m=\"4547500\">of--</span> <span m=\"\
  4548210\">the</span> <span m=\"4548400\">k and</span> <span m=\"4548610\">eta</span>\
  \ <span m=\"4549140\">as</span> <span m=\"4549300\">a</span> <span m=\"4549360\"\
  >function</span> <span m=\"4549690\">of</span> <span m=\"4549810\">epsilon.</span>\
  \ <span m=\"4551600\">So</span> <span m=\"4551610\">there</span> <span m=\"4551790\"\
  >are</span> <span m=\"4551910\">other</span> <span m=\"4552180\">proofs</span> <span\
  \ m=\"4552600\">that</span> <span m=\"4552780\">gives</span> <span m=\"4553020\"\
  >you</span> <span m=\"4553110\">concrete</span> <span m=\"4553530\">bounds,</span>\
  \ <span m=\"4554400\">but</span> <span m=\"4554730\">this</span> <span m=\"4555030\"\
  >proof</span> <span m=\"4555330\">here</span> <span m=\"4555990\">is</span> <span\
  \ m=\"4556980\">much</span> <span m=\"4557280\">simpler</span> <span m=\"4558270\"\
  >if</span> <span m=\"4558510\">you</span> <span m=\"4559200\">assume</span> <span\
  \ m=\"4559680\">the</span> <span m=\"4559800\">corresponding</span> <span m=\"4560400\"\
  >results</span> <span m=\"4560850\">about</span> <span m=\"4561120\">compactness.</span></p><p><span\
  \ m=\"4564370\">And</span> <span m=\"4564550\">finally,</span> <span m=\"4565480\"\
  >I</span> <span m=\"4565630\">want</span> <span m=\"4565900\">to</span> <span m=\"\
  4566710\">mention</span> <span m=\"4568150\">that</span> <span m=\"4569800\">in</span>\
  \ <span m=\"4570040\">the</span> <span m=\"4570220\">moments</span> <span m=\"4570820\"\
  >lemma,</span> <span m=\"4571780\">in</span> <span m=\"4571900\">order</span> <span\
  \ m=\"4572200\">to</span> <span m=\"4572560\">deduce</span> <span m=\"4573040\"\
  >that</span> <span m=\"4573160\">u</span> <span m=\"4573460\">and</span> <span m=\"\
  4573580\">w</span> <span m=\"4574580\">have</span> <span m=\"4575170\">the</span>\
  \ <span m=\"4575320\">same--</span> <span m=\"4575980\">that</span> <span m=\"4576270\"\
  >they</span> <span m=\"4576590\">are</span> <span m=\"4576760\">basically</span>\
  \ <span m=\"4577210\">the</span> <span m=\"4577300\">same</span> <span m=\"4577560\"\
  >graphon,</span> <span m=\"4578320\">we</span> <span m=\"4578530\">need</span> <span\
  \ m=\"4578680\">to</span> <span m=\"4579310\">consider</span> <span m=\"4579790\"\
  >F</span> <span m=\"4580030\">moments</span> <span m=\"4580420\">for</span> <span\
  \ m=\"4580750\">all</span> <span m=\"4581020\">F's.</span> <span m=\"4583060\">So</span>\
  \ <span m=\"4583240\">you</span> <span m=\"4583330\">might</span> <span m=\"4583540\"\
  >ask,</span> <span m=\"4584560\">could</span> <span m=\"4584740\">it</span> <span\
  \ m=\"4584800\">be</span> <span m=\"4584920\">the</span> <span m=\"4585010\">case</span>\
  \ <span m=\"4585640\">that</span> <span m=\"4586300\">we</span> <span m=\"4586690\"\
  >only</span> <span m=\"4587020\">need</span> <span m=\"4587260\">some</span> <span\
  \ m=\"4588400\">finite</span> <span m=\"4588910\">set</span> <span m=\"4589180\"\
  >of</span> <span m=\"4589300\">F's</span> <span m=\"4589810\">to</span> <span m=\"\
  4589960\">deduce--</span> <span m=\"4591800\">to</span> <span m=\"4592540\">recover</span>\
  \ <span m=\"4593020\">the</span> <span m=\"4593110\">graphon?</span> <span m=\"\
  4594220\">Is</span> <span m=\"4594370\">it</span> <span m=\"4594460\">the</span>\
  \ <span m=\"4594520\">case</span> <span m=\"4597040\">that</span> <span m=\"4597550\"\
  >you</span> <span m=\"4597730\">can</span> <span m=\"4599170\">recover</span> <span\
  \ m=\"4599740\">W</span> <span m=\"4600400\">from</span> <span m=\"4601030\">only</span>\
  \ <span m=\"4601300\">a</span> <span m=\"4601390\">finite</span> <span m=\"4601840\"\
  >number</span> <span m=\"4602170\">of</span> <span m=\"4602470\">F</span> <span\
  \ m=\"4602650\">moments?</span></p><p><span m=\"4604410\">And</span> <span m=\"\
  4604540\">this</span> <span m=\"4604720\">is,</span> <span m=\"4605380\">it's</span>\
  \ <span m=\"4605560\">actually</span> <span m=\"4605800\">a</span> <span m=\"4605830\"\
  >very</span> <span m=\"4606010\">interesting</span> <span m=\"4606520\">problem</span>\
  \ <span m=\"4607000\">for</span> <span m=\"4607180\">which</span> <span m=\"4607390\"\
  >we</span> <span m=\"4607570\">already</span> <span m=\"4607960\">saw</span> <span\
  \ m=\"4608530\">one</span> <span m=\"4608830\">instance.</span> <span m=\"4610660\"\
  >Namely,</span> <span m=\"4611410\">when</span> <span m=\"4611530\">we</span> <span\
  \ m=\"4611680\">discussed</span> <span m=\"4612460\">quasi-random</span> <span m=\"\
  4613120\">graphs,</span> <span m=\"4614710\">we</span> <span m=\"4614860\">saw</span>\
  \ <span m=\"4615100\">that</span> <span m=\"4615700\">if</span> <span m=\"4615940\"\
  >you</span> <span m=\"4617170\">know</span> <span m=\"4618090\">that</span> <span\
  \ m=\"4618300\">the</span> <span m=\"4618400\">k2</span> <span m=\"4619630\">moment</span>\
  \ <span m=\"4620350\">is</span> <span m=\"4620620\">p</span> <span m=\"4621910\"\
  >and</span> <span m=\"4622060\">also</span> <span m=\"4622330\">the</span> <span\
  \ m=\"4622450\">C4</span> <span m=\"4623080\">moment</span> <span m=\"4625630\"\
  >is</span> <span m=\"4625810\">p</span> <span m=\"4626230\">to</span> <span m=\"\
  4626730\">the</span> <span m=\"4626830\">4,</span> <span m=\"4628600\">then</span>\
  \ <span m=\"4632860\">we</span> <span m=\"4632980\">can</span> <span m=\"4633130\"\
  >deduce</span> <span m=\"4633910\">that</span> <span m=\"4636040\">the</span> <span\
  \ m=\"4636130\">graphon</span> <span m=\"4636610\">must</span> <span m=\"4636880\"\
  >be</span> <span m=\"4636970\">the</span> <span m=\"4637060\">constant</span> <span\
  \ m=\"4637480\">graphon,</span> <span m=\"4637840\">p.</span> <span m=\"4638942\"\
  >OK,</span> <span m=\"4639360\">so</span> <span m=\"4639550\">we</span> <span m=\"\
  4639700\">didn't</span> <span m=\"4639940\">do</span> <span m=\"4640090\">it</span>\
  \ <span m=\"4640150\">in</span> <span m=\"4640300\">this</span> <span m=\"4640450\"\
  >language,</span> <span m=\"4640930\">but</span> <span m=\"4641080\">that's</span>\
  \ <span m=\"4641320\">what</span> <span m=\"4641470\">the</span> <span m=\"4641530\"\
  >proof</span> <span m=\"4641800\">does.</span></p><p><span m=\"4643060\">And</span>\
  \ <span m=\"4643210\">likewise,</span> <span m=\"4643690\">you</span> <span m=\"\
  4643810\">can</span> <span m=\"4644020\">use</span> <span m=\"4644260\">this</span>\
  \ <span m=\"4644500\">to</span> <span m=\"4645070\">deduce</span> <span m=\"4645490\"\
  >a</span> <span m=\"4645640\">qualitative</span> <span m=\"4646240\">version</span>\
  \ <span m=\"4647050\">where</span> <span m=\"4648580\">you</span> <span m=\"4648740\"\
  >have</span> <span m=\"4651130\">an</span> <span m=\"4651430\">extra</span> <span\
  \ m=\"4652090\">slack</span> <span m=\"4653320\">and</span> <span m=\"4657490\"\
  >an</span> <span m=\"4657760\">extra</span> <span m=\"4658120\">slack</span> <span\
  \ m=\"4658690\">over</span> <span m=\"4658900\">here.</span> <span m=\"4660670\"\
  >So</span> <span m=\"4661060\">you</span> <span m=\"4661180\">might</span> <span\
  \ m=\"4661360\">ask,</span> <span m=\"4662380\">except</span> <span m=\"4662800\"\
  >for</span> <span m=\"4664390\">the</span> <span m=\"4664480\">constant</span> <span\
  \ m=\"4664900\">graphons,</span> <span m=\"4665410\">are</span> <span m=\"4665560\"\
  >there</span> <span m=\"4665770\">other</span> <span m=\"4666050\">graphons</span>\
  \ <span m=\"4666880\">for</span> <span m=\"4667060\">which</span> <span m=\"4667240\"\
  >you</span> <span m=\"4667330\">can</span> <span m=\"4667480\">similarly</span>\
  \ <span m=\"4668050\">deduce--</span> <span m=\"4669880\">recover</span> <span m=\"\
  4670360\">this</span> <span m=\"4670510\">graphon</span> <span m=\"4671110\">from</span>\
  \ <span m=\"4671380\">just</span> <span m=\"4671650\">a</span> <span m=\"4671680\"\
  >finite</span> <span m=\"4672220\">amount</span> <span m=\"4672490\">of</span> <span\
  \ m=\"4672610\">moments</span> <span m=\"4673060\">data?</span> <span m=\"4673840\"\
  >And</span> <span m=\"4674080\">such</span> <span m=\"4674660\">graphons</span>\
  \ <span m=\"4675310\">are</span> <span m=\"4675420\">known</span> <span m=\"4675690\"\
  >as</span> <span m=\"4675910\">finitely</span> <span m=\"4676210\">forcible.</span>\
  \ <span m=\"4683350\">So</span> <span m=\"4683710\">finitely</span> <span m=\"4684430\"\
  >forcible</span> <span m=\"4684850\">graphons</span> <span m=\"4686530\">W</span>\
  \ <span m=\"4687670\">such</span> <span m=\"4688000\">that</span> <span m=\"4689830\"\
  >a</span> <span m=\"4689950\">finite</span> <span m=\"4690430\">number</span> <span\
  \ m=\"4695970\">of</span> <span m=\"4696330\">moments</span> <span m=\"4699060\"\
  >can</span> <span m=\"4699300\">uniquely</span> <span m=\"4700410\">recover--</span>\
  \ <span m=\"4705350\">can</span> <span m=\"4705470\">uniquely</span> <span m=\"\
  4705890\">identify</span> <span m=\"4706340\">this</span> <span m=\"4706430\">graphon,</span>\
  \ <span m=\"4706880\">W.</span></p><p><span m=\"4708620\">And</span> <span m=\"\
  4709250\">a</span> <span m=\"4709310\">very</span> <span m=\"4709520\">interesting</span>\
  \ <span m=\"4709970\">question</span> <span m=\"4710300\">is,</span> <span m=\"\
  4710510\">what</span> <span m=\"4710930\">is</span> <span m=\"4711140\">the</span>\
  \ <span m=\"4711260\">set</span> <span m=\"4711530\">of</span> <span m=\"4711650\"\
  >all</span> <span m=\"4711800\">finitely</span> <span m=\"4712280\">forcible</span>\
  \ <span m=\"4712670\">graphons?</span> <span m=\"4714130\">And it</span> <span m=\"\
  4714200\">turns</span> <span m=\"4714410\">out,</span> <span m=\"4714590\">this</span>\
  \ <span m=\"4714770\">is</span> <span m=\"4714890\">not</span> <span m=\"4715220\"\
  >at</span> <span m=\"4715310\">all</span> <span m=\"4715430\">obvious.</span> <span\
  \ m=\"4716290\">And</span> <span m=\"4716450\">let</span> <span m=\"4716570\">me</span>\
  \ <span m=\"4716690\">just</span> <span m=\"4716840\">give</span> <span m=\"4717050\"\
  >you</span> <span m=\"4717140\">some</span> <span m=\"4717350\">examples,</span>\
  \ <span m=\"4717890\">highly</span> <span m=\"4718160\">non-trivial,</span> <span\
  \ m=\"4718790\">that</span> <span m=\"4718970\">turned</span> <span m=\"4719180\"\
  >out</span> <span m=\"4719270\">to</span> <span m=\"4719360\">be</span> <span m=\"\
  4719480\">finitely</span> <span m=\"4719860\">forcible.</span></p><p><span m=\"\
  4722240\">For</span> <span m=\"4722390\">example,</span> <span m=\"4723110\">anything</span>\
  \ <span m=\"4723500\">which</span> <span m=\"4723680\">is</span> <span m=\"4723800\"\
  >a</span> <span m=\"4723860\">step</span> <span m=\"4724190\">graphon</span> <span\
  \ m=\"4727180\">is</span> <span m=\"4727310\">finitely</span> <span m=\"4727650\"\
  >forcible.</span> <span m=\"4732120\">The half</span> <span m=\"4732650\">graphon</span>\
  \ <span m=\"4734690\">which</span> <span m=\"4734840\">corresponds</span> <span\
  \ m=\"4735350\">to</span> <span m=\"4735410\">the</span> <span m=\"4735470\">limit</span>\
  \ <span m=\"4735830\">of</span> <span m=\"4736010\">a</span> <span m=\"4737150\"\
  >sequence</span> <span m=\"4737510\">of</span> <span m=\"4737600\">half</span> <span\
  \ m=\"4737870\">graphs</span> <span m=\"4738870\">is</span> <span m=\"4739040\"\
  >finitely</span> <span m=\"4739410\">forcible.</span> <span m=\"4740450\">I</span>\
  \ <span m=\"4740810\">mean,</span> <span m=\"4740900\">already,</span> <span m=\"\
  4742190\">I</span> <span m=\"4742250\">think</span> <span m=\"4742400\">neither</span>\
  \ <span m=\"4742730\">of</span> <span m=\"4742820\">these</span> <span m=\"4743000\"\
  >two</span> <span m=\"4743150\">examples</span> <span m=\"4743630\">are</span> <span\
  \ m=\"4744890\">easy</span> <span m=\"4745220\">at</span> <span m=\"4745320\">all.</span></p><p><span\
  \ m=\"4746570\">And</span> <span m=\"4747260\">this</span> <span m=\"4747500\">example</span>\
  \ <span m=\"4747830\">here</span> <span m=\"4748130\">can</span> <span m=\"4748340\"\
  >be</span> <span m=\"4748460\">generalized</span> <span m=\"4749360\">where</span>\
  \ <span m=\"4750140\">you</span> <span m=\"4750290\">have</span> <span m=\"4750680\"\
  >any</span> <span m=\"4750890\">polynomial</span> <span m=\"4751580\">curve.</span>\
  \ <span m=\"4760820\">I</span> <span m=\"4760880\">think</span> <span m=\"4761030\"\
  >this</span> <span m=\"4761150\">has</span> <span m=\"4761300\">to</span> <span\
  \ m=\"4761390\">be--</span> <span m=\"4762905\">so</span> <span m=\"4763330\">if\
  \ it's a</span> <span m=\"4763460\">polynomial</span> <span m=\"4763940\">curve,</span>\
  \ <span m=\"4765250\">it's</span> <span m=\"4765740\">also</span> <span m=\"4765980\"\
  >finitely</span> <span m=\"4766370\">forcible.</span> <span m=\"4768660\">But</span>\
  \ <span m=\"4768870\">turns</span> <span m=\"4769140\">out</span> <span m=\"4769230\"\
  >finitely</span> <span m=\"4769470\">forcible</span> <span m=\"4769980\">graphons</span>\
  \ <span m=\"4770370\">can</span> <span m=\"4770490\">get</span> <span m=\"4770670\"\
  >quite</span> <span m=\"4771240\">complicated.</span> <span m=\"4772920\">And</span>\
  \ <span m=\"4773220\">there is</span> <span m=\"4773400\">still</span> <span m=\"\
  4774050\">rather</span> <span m=\"4774370\">quite</span> <span m=\"4774550\">a</span>\
  \ <span m=\"4774600\">bit</span> <span m=\"4774780\">of</span> <span m=\"4774870\"\
  >mystery</span> <span m=\"4775260\">around</span> <span m=\"4775530\">them.</span></p><p><span\
  \ m=\"4778150\">OK,</span> <span m=\"4778560\">so</span> <span m=\"4779100\">next</span>\
  \ <span m=\"4779370\">time,</span> <span m=\"4779700\">I</span> <span m=\"4779820\"\
  >want</span> <span m=\"4780060\">to</span> <span m=\"4780660\">discuss</span> <span\
  \ m=\"4781890\">some</span> <span m=\"4782640\">inequalities</span> <span m=\"4783630\"\
  >that</span> <span m=\"4783810\">come</span> <span m=\"4784140\">out</span> <span\
  \ m=\"4784350\">of--</span> <span m=\"4785640\">you</span> <span m=\"4785760\">can</span>\
  \ <span m=\"4785970\">state</span> <span m=\"4786540\">between</span> <span m=\"\
  4786990\">different F</span> <span m=\"4787430\">densities.</span> <span m=\"4789034\"\
  >OK,</span> <span m=\"4789486\">great.</span> <span m=\"4789940\">That's</span>\
  \ <span m=\"4790090\">all</span> <span m=\"4790180\">for</span> <span m=\"4790270\"\
  >today.</span></p>"
type: course
uid: 0031a0d091af8db0e3f325c0a2be7582

---
None