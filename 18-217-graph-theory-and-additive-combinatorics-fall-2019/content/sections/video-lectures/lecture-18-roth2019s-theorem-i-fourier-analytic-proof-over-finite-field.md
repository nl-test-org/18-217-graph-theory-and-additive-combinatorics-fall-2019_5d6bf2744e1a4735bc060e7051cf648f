---
about_this_resource_text: "<p><strong>Description:</strong> The finite field model\
  \ is a nice sandbox for methods and tools in additive combinatorics. Professor Zhao\
  \ explains how to use Fourier analysis to prove the analog of Roth\u2019s theorem\
  \ in the finite field setting.\r\n\r\n</p>\r\n<p><strong>Instructor:</strong> Yufei\
  \ Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: buEtwpGvQpI
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  title: Video-YouTube-Stream
  type: Video
  uid: 434d1af8608f43649582ef9c89a56040
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/buEtwpGvQpI/default.jpg
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 410057106eba45864b84e8d9a0bce0b8
- id: 3Play-3PlayYouTubeid-MP4
  media_location: buEtwpGvQpI
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9e10804108bb2976a839c874b5926c98
- id: buEtwpGvQpI.srt
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-18-roth2019s-theorem-i-fourier-analytic-proof-over-finite-field/buEtwpGvQpI.srt
  title: 3play caption file
  type: null
  uid: 4101e9e0ee26b8e34e60e1d51301dbde
- id: buEtwpGvQpI.pdf
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-18-roth2019s-theorem-i-fourier-analytic-proof-over-finite-field/buEtwpGvQpI.pdf
  title: 3play pdf file
  type: null
  uid: 5b9ff0168199d6c2006e3678a80da243
- id: Caption-3Play YouTube id-SRT
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: df8116383102b76c55d003ce8c55fa94
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 24081043dd1c965a6d3b09910690bc58
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec18_300k.mp4
  parent_uid: b6005bf7bcb87c4ec8c8c0b1c9014989
  title: Video-Internet Archive-MP4
  type: Video
  uid: 55f95bd8944bccb9f7e889448c9a6eed
inline_embed_id: 486719lecture18rothstheoremifourieranalyticproofoverfinitefield61215727
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-18-roth2019s-theorem-i-fourier-analytic-proof-over-finite-field
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-18-roth2019s-theorem-i-fourier-analytic-proof-over-finite-field
template_type: Tabbed
title: "Lecture 18: Roth\u2019s Theorem I: Fourier Analytic Proof over Finite Field\
  \ \t"
transcript: "<p><span m=\"18210\">YUFEI ZHAO:</span> <span m=\"18350\">OK.</span>\
  \ <span m=\"18490\">So</span> <span m=\"18640\">let's</span> <span m=\"18790\">get</span>\
  \ <span m=\"18910\">started.</span> <span m=\"20950\">So</span> <span m=\"21100\"\
  >we</span> <span m=\"21250\">spent</span> <span m=\"21640\">quite</span> <span m=\"\
  21910\">a</span> <span m=\"21970\">bit</span> <span m=\"22090\">of</span> <span\
  \ m=\"22150\">time</span> <span m=\"22420\">with</span> <span m=\"22600\">graph</span>\
  \ <span m=\"22870\">theory</span> <span m=\"23170\">in</span> <span m=\"23260\"\
  >the</span> <span m=\"23320\">first</span> <span m=\"23590\">part</span> <span m=\"\
  23830\">of</span> <span m=\"23890\">this</span> <span m=\"24040\">course,</span>\
  \ <span m=\"25010\">and</span> <span m=\"25270\">today</span> <span m=\"25570\"\
  >I</span> <span m=\"25660\">want</span> <span m=\"25870\">to</span> <span m=\"26860\"\
  >move</span> <span m=\"27100\">beyond</span> <span m=\"27430\">that.</span> <span\
  \ m=\"27760\">So</span> <span m=\"28570\">we're</span> <span m=\"28660\">going</span>\
  \ <span m=\"28870\">to</span> <span m=\"28960\">talk</span> <span m=\"29290\">about</span>\
  \ <span m=\"30400\">more</span> <span m=\"30760\">central</span> <span m=\"31180\"\
  >topics</span> <span m=\"31630\">and</span> <span m=\"31780\">additive</span> <span\
  \ m=\"32110\">combinatorics,</span> <span m=\"33250\">starting</span> <span m=\"\
  33730\">with</span> <span m=\"34520\">the</span> <span m=\"34690\">Fourier</span>\
  \ <span m=\"35180\">analytic</span> <span m=\"35530\">proof</span> <span m=\"36220\"\
  >of</span> <span m=\"36490\">Roth's</span> <span m=\"36940\">theorem.</span></p><p><span\
  \ m=\"48760\">We</span> <span m=\"48910\">discussed</span> <span m=\"49420\">Roth's</span>\
  \ <span m=\"49735\">theorem,</span> <span m=\"50050\">and</span> <span m=\"50140\"\
  >we</span> <span m=\"50260\">gave</span> <span m=\"50500\">a</span> <span m=\"50560\"\
  >proof,</span> <span m=\"51340\">during</span> <span m=\"51640\">the</span> <span\
  \ m=\"51700\">course,</span> <span m=\"52330\">using</span> <span m=\"52930\">similarities,</span>\
  \ <span m=\"53830\">graph</span> <span m=\"54160\">regularity</span> <span m=\"\
  54760\">lemma,</span> <span m=\"55060\">as</span> <span m=\"55480\">well</span>\
  \ <span m=\"55870\">as</span> <span m=\"56020\">the</span> <span m=\"56140\">triangle</span>\
  \ <span m=\"56680\">removal</span> <span m=\"57160\">lemma.</span> <span m=\"59220\"\
  >Today,</span> <span m=\"59470\">I</span> <span m=\"59530\">want</span> <span m=\"\
  59680\">to</span> <span m=\"59740\">show</span> <span m=\"59920\">you</span> <span\
  \ m=\"60340\">a</span> <span m=\"61030\">different</span> <span m=\"61360\">approach</span>\
  \ <span m=\"61810\">to</span> <span m=\"61990\">proving</span> <span m=\"62410\"\
  >Roth's</span> <span m=\"62750\">theorem</span> <span m=\"63310\">that</span> <span\
  \ m=\"63460\">goes</span> <span m=\"63730\">through</span> <span m=\"63910\">Fourier</span>\
  \ <span m=\"64360\">analysis.</span> <span m=\"65540\">So</span> <span m=\"65560\"\
  >this</span> <span m=\"65710\">is</span> <span m=\"65830\">a</span> <span m=\"65860\"\
  >very</span> <span m=\"66100\">important</span> <span m=\"66490\">proof,</span>\
  \ <span m=\"67240\">and</span> <span m=\"67660\">it's</span> <span m=\"68530\">one</span>\
  \ <span m=\"68710\">of</span> <span m=\"68770\">the</span> <span m=\"69280\">main</span>\
  \ <span m=\"69610\">tools</span> <span m=\"70030\">in</span> <span m=\"70140\">additive</span>\
  \ <span m=\"70520\">combinatorics.</span></p><p><span m=\"73330\">Let</span> <span\
  \ m=\"73420\">me</span> <span m=\"73540\">remind</span> <span m=\"73870\">you</span>\
  \ <span m=\"73930\">what</span> <span m=\"74110\">Roth's</span> <span m=\"74380\"\
  >theorem</span> <span m=\"74650\">says.</span> <span m=\"75520\">So</span> <span\
  \ m=\"75910\">Roth</span> <span m=\"76270\">proved,</span> <span m=\"78850\">in</span>\
  \ <span m=\"80450\">1953,</span> <span m=\"82130\">that</span> <span m=\"84380\"\
  >if</span> <span m=\"84560\">we</span> <span m=\"84710\">write</span> <span m=\"\
  86030\">our</span> <span m=\"86910\">sub-3</span> <span m=\"88430\">of</span> <span\
  \ m=\"89210\">interval</span> <span m=\"89465\">n</span> <span m=\"90610\">to</span>\
  \ <span m=\"90740\">be</span> <span m=\"90980\">the</span> <span m=\"91880\">maximum</span>\
  \ <span m=\"93230\">size</span> <span m=\"95120\">of</span> <span m=\"95300\">a</span>\
  \ <span m=\"95390\">3AP3</span> <span m=\"96140\">subset</span> <span m=\"102960\"\
  >of</span> <span m=\"104280\">1</span> <span m=\"104520\">through</span> <span m=\"\
  104700\">n,</span> <span m=\"107420\">then</span> <span m=\"107660\">Roth</span>\
  \ <span m=\"107990\">showed</span> <span m=\"108620\">that</span> <span m=\"109460\"\
  >our</span> <span m=\"109640\">3</span> <span m=\"111840\">of</span> <span m=\"\
  111980\">n</span> <span m=\"112820\">is</span> <span m=\"114650\">little</span>\
  \ <span m=\"114830\">O</span> <span m=\"114890\">of</span> <span m=\"116230\">n.</span></p><p><span\
  \ m=\"118280\">So</span> <span m=\"119300\">in</span> <span m=\"119450\">other</span>\
  \ <span m=\"119600\">words,</span> <span m=\"120030\">if</span> <span m=\"120080\"\
  >you</span> <span m=\"120200\">have</span> <span m=\"120440\">a</span> <span m=\"\
  120530\">positive</span> <span m=\"120980\">density</span> <span m=\"121790\">subset</span>\
  \ <span m=\"122510\">of</span> <span m=\"124430\">the</span> <span m=\"124640\"\
  >integers,</span> <span m=\"125880\">then</span> <span m=\"126280\">it</span> <span\
  \ m=\"126350\">must</span> <span m=\"126560\">contain</span> <span m=\"126950\"\
  >a</span> <span m=\"127010\">three-term</span> <span m=\"127520\">arithmetic</span>\
  \ <span m=\"128000\">progression</span> <span m=\"128419\">then.</span> <span m=\"\
  129150\">So</span> <span m=\"129199\">what</span> <span m=\"129350\">I</span> <span\
  \ m=\"129410\">said</span> <span m=\"130009\">is</span> <span m=\"130490\">equivalent</span>\
  \ <span m=\"131000\">to</span> <span m=\"131090\">the</span> <span m=\"131240\"\
  >statement</span> <span m=\"131690\">here.</span> <span m=\"133740\">So</span> <span\
  \ m=\"133940\">previously,</span> <span m=\"134450\">we</span> <span m=\"134570\"\
  >gave</span> <span m=\"134750\">a</span> <span m=\"134810\">proof</span> <span m=\"\
  135110\">using</span> <span m=\"135620\">regularity.</span> <span m=\"143220\">Actually</span>\
  \ <span m=\"143400\">the</span> <span m=\"143460\">regularity</span> <span m=\"\
  144060\">approach</span> <span m=\"144370\">of</span> <span m=\"144420\">Szemer\xE9\
  di</span> <span m=\"144600\">was</span> <span m=\"145020\">only</span> <span m=\"\
  145230\">found</span> <span m=\"145500\">the</span> <span m=\"145590\">'70s</span>\
  \ <span m=\"146300\">so</span> <span m=\"146420\">Roth's</span> <span m=\"146970\"\
  >original</span> <span m=\"147390\">proof</span> <span m=\"147690\">was</span> <span\
  \ m=\"147960\">through</span> <span m=\"148140\">Fourier</span> <span m=\"148530\"\
  >analysis.</span></p><p><span m=\"149460\">And</span> <span m=\"149790\">we'll</span>\
  \ <span m=\"150000\">see</span> <span m=\"150240\">that</span> <span m=\"151470\"\
  >tomorrow.</span> <span m=\"152520\">Today,</span> <span m=\"152840\">we'll</span>\
  \ <span m=\"153060\">see</span> <span m=\"153720\">a</span> <span m=\"154140\">toy</span>\
  \ <span m=\"154590\">version</span> <span m=\"155160\">of</span> <span m=\"155280\"\
  >this</span> <span m=\"155520\">proof.</span> <span m=\"155990\">But</span> <span\
  \ m=\"156110\">it's</span> <span m=\"156240\">not</span> <span m=\"156420\">really</span>\
  \ <span m=\"156630\">a</span> <span m=\"156690\">toy</span> <span m=\"156930\">version.</span>\
  \ <span m=\"157260\">It</span> <span m=\"157380\">has</span> <span m=\"157500\"\
  >the</span> <span m=\"157560\">same</span> <span m=\"157830\">ideas,</span> <span\
  \ m=\"158460\">but</span> <span m=\"158640\">in</span> <span m=\"158730\">a</span>\
  \ <span m=\"158790\">slightly</span> <span m=\"159180\">easier</span> <span m=\"\
  159600\">setting</span> <span m=\"160430\">that</span> <span m=\"160560\">has</span>\
  \ <span m=\"161010\">fewer</span> <span m=\"161370\">technicalities.</span> <span\
  \ m=\"164930\">But</span> <span m=\"164960\">before</span> <span m=\"165260\">showing</span>\
  \ <span m=\"165530\">you</span> <span m=\"165620\">that,</span> <span m=\"165770\"\
  >let</span> <span m=\"165920\">me</span> <span m=\"166010\">just</span> <span m=\"\
  166220\">discuss</span> <span m=\"166640\">a</span> <span m=\"166670\">bit</span>\
  \ <span m=\"166820\">of</span> <span m=\"166940\">history</span> <span m=\"167330\"\
  >around</span> <span m=\"167750\">Roth's</span> <span m=\"168035\">theorem.</span>\
  \ <span m=\"171230\">We</span> <span m=\"171410\">will</span> <span m=\"171560\"\
  >show,</span> <span m=\"171830\">next</span> <span m=\"172160\">time,</span> <span\
  \ m=\"173860\">the</span> <span m=\"173970\">next</span> <span m=\"174260\">lecture,</span>\
  \ <span m=\"175600\">we'll</span> <span m=\"175790\">show</span> <span m=\"176540\"\
  >the</span> <span m=\"176630\">bound.</span></p><p><span m=\"179405\">Also</span>\
  \ <span m=\"179880\">by</span> <span m=\"179990\">regularity,</span> <span m=\"\
  180740\">we</span> <span m=\"180890\">get</span> <span m=\"181100\">some</span>\
  \ <span m=\"181370\">bound,</span> <span m=\"181740\">which</span> <span m=\"181820\"\
  >is</span> <span m=\"181970\">little</span> <span m=\"182270\">O</span> <span m=\"\
  182510\">then,</span> <span m=\"182870\">but</span> <span m=\"183050\">because</span>\
  \ <span m=\"183410\">of</span> <span m=\"183500\">the</span> <span m=\"183590\"\
  >use</span> <span m=\"183800\">of</span> <span m=\"183890\">regularity</span> <span\
  \ m=\"184460\">lemmas,</span> <span m=\"184550\">it's</span> <span m=\"185060\"\
  >pretty</span> <span m=\"185360\">poor</span> <span m=\"185690\">dependence.</span>\
  \ <span m=\"186880\">We</span> <span m=\"187100\">got</span> <span m=\"187370\"\
  >something</span> <span m=\"187700\">like</span> <span m=\"187940\">n</span> <span\
  \ m=\"188230\">over</span> <span m=\"188500\">log</span> <span m=\"188840\">star</span>\
  \ <span m=\"189170\">n.</span> <span m=\"191370\">Next</span> <span m=\"191610\"\
  >lecture,</span> <span m=\"192000\">and</span> <span m=\"192510\">basically</span>\
  \ <span m=\"194430\">Roth's</span> <span m=\"194880\">original</span> <span m=\"\
  195330\">proof,</span> <span m=\"196680\">gives</span> <span m=\"196980\">you</span>\
  \ <span m=\"197100\">a</span> <span m=\"197160\">bound</span> <span m=\"198100\"\
  >which</span> <span m=\"198230\">is</span> <span m=\"198370\">n</span> <span m=\"\
  198750\">over</span> <span m=\"199140\">log-log</span> <span m=\"199710\">n.</span>\
  \ <span m=\"200340\">So</span> <span m=\"200430\">it's</span> <span m=\"200520\"\
  >a</span> <span m=\"200580\">much</span> <span m=\"200790\">more</span> <span m=\"\
  200940\">reasonable</span> <span m=\"201460\">bound.</span></p><p><span m=\"203100\"\
  >The</span> <span m=\"203190\">current</span> <span m=\"203550\">best</span> <span\
  \ m=\"205620\">upper</span> <span m=\"205830\">bound</span> <span m=\"206220\">known</span>\
  \ <span m=\"209880\">has</span> <span m=\"210150\">the</span> <span m=\"210240\"\
  >form,</span> <span m=\"215530\">essentially,</span> <span m=\"216520\">n</span>\
  \ <span m=\"217000\">over</span> <span m=\"219250\">log</span> <span m=\"220060\"\
  >n</span> <span m=\"222190\">raised</span> <span m=\"222550\">to</span> <span m=\"\
  222760\">1</span> <span m=\"223000\">plus</span> <span m=\"223330\">little</span>\
  \ <span m=\"223630\">1,</span> <span m=\"224190\">roughly</span> <span m=\"224620\"\
  >n</span> <span m=\"224830\">over</span> <span m=\"225010\">log</span> <span m=\"\
  225350\">n.</span> <span m=\"227470\">We</span> <span m=\"227650\">do</span> <span\
  \ m=\"227770\">not</span> <span m=\"227980\">know,</span> <span m=\"228520\">or</span>\
  \ <span m=\"228670\">even</span> <span m=\"228880\">have</span> <span m=\"229100\"\
  >great</span> <span m=\"229360\">guesses</span> <span m=\"229780\">on,</span> <span\
  \ m=\"229870\">what</span> <span m=\"230050\">the</span> <span m=\"230170\">answer</span>\
  \ <span m=\"230470\">should</span> <span m=\"230650\">be.</span></p><p><span m=\"\
  231840\">So</span> <span m=\"231970\">the</span> <span m=\"232090\">best</span>\
  \ <span m=\"234280\">lower</span> <span m=\"234530\">bound,</span> <span m=\"236290\"\
  >and</span> <span m=\"236410\">this</span> <span m=\"236590\">is</span> <span m=\"\
  236670\">a</span> <span m=\"236710\">construction</span> <span m=\"237250\">that</span>\
  \ <span m=\"237340\">we</span> <span m=\"237460\">saw</span> <span m=\"237950\"\
  >earlier in</span> <span m=\"238240\">the</span> <span m=\"238300\">course</span>\
  \ <span m=\"239260\">due</span> <span m=\"239410\">to</span> <span m=\"239670\"\
  >Behrend</span> <span m=\"242620\">is</span> <span m=\"244480\">of</span> <span\
  \ m=\"244570\">the</span> <span m=\"244660\">form</span> <span m=\"245170\">n</span>\
  \ <span m=\"245830\">over</span> <span m=\"246280\">E</span> <span m=\"246490\"\
  >to</span> <span m=\"246650\">the</span> <span m=\"246730\">c</span> <span m=\"\
  248320\">root</span> <span m=\"248590\">log</span> <span m=\"248860\">n.</span>\
  \ <span m=\"250360\">It</span> <span m=\"250450\">seems</span> <span m=\"250930\"\
  >it</span> <span m=\"251020\">may</span> <span m=\"251200\">be</span> <span m=\"\
  251350\">very</span> <span m=\"251590\">difficult</span> <span m=\"252040\">to</span>\
  \ <span m=\"252100\">improve</span> <span m=\"252550\">this</span> <span m=\"252730\"\
  >upper</span> <span m=\"252940\">bound</span> <span m=\"253240\">without</span>\
  \ <span m=\"253570\">some</span> <span m=\"253900\">genuine</span> <span m=\"254380\"\
  >new</span> <span m=\"254620\">ideas.</span></p><p><span m=\"256070\">On</span>\
  \ <span m=\"256170\">the</span> <span m=\"256269\">other</span> <span m=\"256329\"\
  >hand,</span> <span m=\"256850\">there</span> <span m=\"257010\">is</span> <span\
  \ m=\"257070\">some</span> <span m=\"257589\">evidence</span> <span m=\"258940\"\
  >that</span> <span m=\"259149\">the</span> <span m=\"259269\">lower</span> <span\
  \ m=\"259540\">bound</span> <span m=\"259810\">might</span> <span m=\"259959\">be</span>\
  \ <span m=\"260110\">closer</span> <span m=\"260529\">to</span> <span m=\"260680\"\
  >the</span> <span m=\"260769\">truth</span> <span m=\"262560\">in</span> <span m=\"\
  262680\">that</span> <span m=\"262860\">there</span> <span m=\"263030\">are</span>\
  \ <span m=\"263070\">variants</span> <span m=\"263670\">of</span> <span m=\"263760\"\
  >the</span> <span m=\"263850\">Roth</span> <span m=\"264180\">problem</span> <span\
  \ m=\"264720\">for</span> <span m=\"264900\">which</span> <span m=\"265110\">we</span>\
  \ <span m=\"265260\">know</span> <span m=\"265470\">that</span> <span m=\"265620\"\
  >the</span> <span m=\"265680\">lower</span> <span m=\"265950\">bound</span> <span\
  \ m=\"266250\">is</span> <span m=\"266430\">basically</span> <span m=\"266820\"\
  >the</span> <span m=\"266910\">truth.</span> <span m=\"272390\">What</span> <span\
  \ m=\"272570\">I</span> <span m=\"272660\">want</span> <span m=\"272840\">to</span>\
  \ <span m=\"272900\">do</span> <span m=\"273020\">today</span> <span m=\"273650\"\
  >is</span> <span m=\"273800\">look</span> <span m=\"273980\">at</span> <span m=\"\
  274070\">a</span> <span m=\"274130\">variant</span> <span m=\"274670\">of</span>\
  \ <span m=\"274790\">this</span> <span m=\"274970\">problem</span> <span m=\"275780\"\
  >in</span> <span m=\"276020\">what's</span> <span m=\"276290\">called</span> <span\
  \ m=\"276530\">a</span> <span m=\"276590\">finite</span> <span m=\"277040\">field</span>\
  \ <span m=\"277400\">model.</span></p><p><span m=\"287520\">And</span> <span m=\"\
  287800\">that</span> <span m=\"288340\">basically</span> <span m=\"288760\">just</span>\
  \ <span m=\"288970\">means</span> <span m=\"289330\">we're</span> <span m=\"289480\"\
  >going</span> <span m=\"289610\">to</span> <span m=\"289690\">be</span> <span m=\"\
  289810\">looking</span> <span m=\"290170\">at</span> <span m=\"290470\">Roth's</span>\
  \ <span m=\"290740\">theorem,</span> <span m=\"291400\">not</span> <span m=\"291790\"\
  >in</span> <span m=\"291910\">the</span> <span m=\"292030\">integers,</span> <span\
  \ m=\"292870\">but</span> <span m=\"293140\">in</span> <span m=\"293260\">some</span>\
  \ <span m=\"293560\">finite</span> <span m=\"293920\">field</span> <span m=\"294220\"\
  >vector</span> <span m=\"294520\">space,</span> <span m=\"295030\">specifically</span>\
  \ <span m=\"295750\">F3</span> <span m=\"296170\">to</span> <span m=\"296320\">the</span>\
  \ <span m=\"296440\">n.</span> <span m=\"297200\">So</span> <span m=\"297340\">we're</span>\
  \ <span m=\"297490\">going</span> <span m=\"297640\">to</span> <span m=\"297700\"\
  >define</span> <span m=\"298570\">our</span> <span m=\"298720\">sub-3</span> <span\
  \ m=\"299290\">of</span> <span m=\"299500\">this</span> <span m=\"299860\">F3</span>\
  \ <span m=\"300110\">to</span> <span m=\"300300\">the</span> <span m=\"300670\"\
  >n</span> <span m=\"301090\">to</span> <span m=\"301210\">be</span> <span m=\"301360\"\
  >the</span> <span m=\"301480\">maximum</span> <span m=\"302620\">size</span> <span\
  \ m=\"304810\">of</span> <span m=\"305200\">the</span> <span m=\"305420\">3AP3</span>\
  \ <span m=\"306100\">subset</span> <span m=\"311780\">of</span> <span m=\"312140\"\
  >this</span> <span m=\"312410\">finite</span> <span m=\"312740\">field</span> <span\
  \ m=\"313040\">vector</span> <span m=\"313340\">space.</span></p><p><span m=\"316610\"\
  >So</span> <span m=\"316710\">the</span> <span m=\"316790\">finite</span> <span\
  \ m=\"317100\">field</span> <span m=\"317280\">model</span> <span m=\"317690\">is</span>\
  \ <span m=\"317810\">really</span> <span m=\"318050\">useful.</span> <span m=\"\
  318380\">We're</span> <span m=\"318470\">going</span> <span m=\"318530\">to</span>\
  \ <span m=\"318650\">see</span> <span m=\"318860\">this</span> <span m=\"319010\"\
  >again</span> <span m=\"319250\">later</span> <span m=\"319490\">in</span> <span\
  \ m=\"319580\">the</span> <span m=\"319640\">course</span> <span m=\"319910\">as</span>\
  \ <span m=\"320030\">well.</span> <span m=\"322140\">Many</span> <span m=\"322430\"\
  >of</span> <span m=\"322520\">the</span> <span m=\"322640\">ideas</span> <span m=\"\
  323300\">and</span> <span m=\"323390\">techniques</span> <span m=\"323960\">that</span>\
  \ <span m=\"324140\">work</span> <span m=\"324620\">for</span> <span m=\"324860\"\
  >the</span> <span m=\"326090\">real</span> <span m=\"326360\">problem,</span> <span\
  \ m=\"326820\">so</span> <span m=\"326870\">to</span> <span m=\"326960\">speak,</span>\
  \ <span m=\"327890\">many</span> <span m=\"328190\">of</span> <span m=\"328250\"\
  >those</span> <span m=\"328430\">techniques</span> <span m=\"328940\">also</span>\
  \ <span m=\"329450\">work</span> <span m=\"329900\">in</span> <span m=\"330050\"\
  >the</span> <span m=\"330110\">finite</span> <span m=\"330440\">field</span> <span\
  \ m=\"330710\">model,</span> <span m=\"331040\">but</span> <span m=\"331220\">they</span>\
  \ <span m=\"331330\">are</span> <span m=\"331370\">technically</span> <span m=\"\
  331880\">simpler</span> <span m=\"332360\">to</span> <span m=\"333290\">execute.</span></p><p><span\
  \ m=\"334320\">So</span> <span m=\"334850\">this</span> <span m=\"335120\">is</span>\
  \ <span m=\"335270\">often--</span> <span m=\"336470\">you</span> <span m=\"336880\"\
  >view</span> <span m=\"337100\">it</span> <span m=\"337190\">as</span> <span m=\"\
  337310\">a</span> <span m=\"337370\">sandbox,</span> <span m=\"338050\">a</span>\
  \ <span m=\"338120\">playing</span> <span m=\"338480\">ground,</span> <span m=\"\
  339050\">for</span> <span m=\"339200\">testing</span> <span m=\"339650\">out</span>\
  \ <span m=\"339980\">many</span> <span m=\"340220\">of</span> <span m=\"340310\"\
  >the</span> <span m=\"340430\">ideas.</span> <span m=\"341330\">And</span> <span\
  \ m=\"341480\">once</span> <span m=\"341660\">you</span> <span m=\"341720\">have</span>\
  \ <span m=\"341810\">those</span> <span m=\"342020\">ideas,</span> <span m=\"342710\"\
  >then</span> <span m=\"342830\">you</span> <span m=\"342920\">can</span> <span m=\"\
  343040\">see</span> <span m=\"343340\">if</span> <span m=\"343490\">you</span> <span\
  \ m=\"343640\">can</span> <span m=\"343910\">bring</span> <span m=\"344240\">them</span>\
  \ <span m=\"344450\">to</span> <span m=\"345230\">the</span> <span m=\"345350\"\
  >integer</span> <span m=\"345710\">setting.</span> <span m=\"346430\">And</span>\
  \ <span m=\"346640\">this</span> <span m=\"346820\">is</span> <span m=\"346940\"\
  >a</span> <span m=\"347000\">very</span> <span m=\"347210\">successful</span> <span\
  \ m=\"347780\">program,</span> <span m=\"348560\">and</span> <span m=\"349070\"\
  >we'll</span> <span m=\"349250\">see</span> <span m=\"349730\">one</span> <span\
  \ m=\"349970\">aspect</span> <span m=\"350450\">of</span> <span m=\"350780\">what</span>\
  \ <span m=\"350930\">happens</span> <span m=\"351410\">when</span> <span m=\"351530\"\
  >we</span> <span m=\"351680\">do</span> <span m=\"351830\">this.</span></p><p><span\
  \ m=\"355220\">For</span> <span m=\"355610\">this</span> <span m=\"355790\">specific</span>\
  \ <span m=\"356270\">problem</span> <span m=\"356600\">of</span> <span m=\"356660\"\
  >Roth's</span> <span m=\"357005\">theorem,</span> <span m=\"357800\">in</span> <span\
  \ m=\"358230\">F3</span> <span m=\"358460\">to</span> <span m=\"358610\">the</span>\
  \ <span m=\"358730\">n,</span> <span m=\"359450\">there</span> <span m=\"359570\"\
  >are</span> <span m=\"359630\">some</span> <span m=\"359840\">nice</span> <span\
  \ m=\"360110\">interpretations</span> <span m=\"360950\">of</span> <span m=\"361040\"\
  >what</span> <span m=\"361190\">this</span> <span m=\"361340\">problem</span> <span\
  \ m=\"361650\">means.</span> <span m=\"362660\">So</span> <span m=\"362780\">here's</span>\
  \ <span m=\"363080\">a</span> <span m=\"363110\">pretty</span> <span m=\"363380\"\
  >easy</span> <span m=\"363710\">fact</span> <span m=\"364280\">that</span> <span\
  \ m=\"364520\">for--</span> <span m=\"365750\">so</span> <span m=\"366020\">n</span>\
  \ <span m=\"366740\">F3</span> <span m=\"367280\">to</span> <span m=\"367400\">the</span>\
  \ <span m=\"367550\">n</span> <span m=\"369580\">for</span> <span m=\"370410\">three</span>\
  \ <span m=\"370700\">elements,</span> <span m=\"371150\">x, y, z,</span> <span m=\"\
  373460\">the</span> <span m=\"373550\">following</span> <span m=\"375340\">interpretation,</span>\
  \ <span m=\"376240\">so</span> <span m=\"376280\">what</span> <span m=\"376460\"\
  >it</span> <span m=\"376520\">means</span> <span m=\"376730\">to</span> <span m=\"\
  376790\">be</span> <span m=\"376940\">a</span> <span m=\"376970\">3AP,</span> <span\
  \ m=\"377370\">are</span> <span m=\"377660\">equivalent.</span> <span m=\"378680\"\
  >So</span> <span m=\"379730\">x. y, z</span> <span m=\"382440\">form a</span> <span\
  \ m=\"382820\">3AP.</span></p><p><span m=\"387540\">So</span> <span m=\"387640\"\
  >3AP</span> <span m=\"388420\">means</span> <span m=\"388840\">the</span> <span\
  \ m=\"389560\">y</span> <span m=\"389890\">is</span> <span m=\"390070\">x</span>\
  \ <span m=\"390280\">plus</span> <span m=\"390490\">D.</span> <span m=\"390820\"\
  >Z is</span> <span m=\"391150\">x</span> <span m=\"391330\">plus</span> <span m=\"\
  391540\">2D.</span> <span m=\"394640\">Equivalently,</span> <span m=\"395230\">they</span>\
  \ <span m=\"395380\">satisfy</span> <span m=\"395980\">this</span> <span m=\"396190\"\
  >equation,</span> <span m=\"397000\">x</span> <span m=\"397210\">minus</span> <span\
  \ m=\"397480\">2y</span> <span m=\"397810\">plus</span> <span m=\"398185\">z</span>\
  \ <span m=\"398560\">equals</span> <span m=\"398830\">zero.</span> <span m=\"400690\"\
  >OK.</span> <span m=\"400930\">In</span> <span m=\"401290\">F3,</span> <span m=\"\
  401770\">minus</span> <span m=\"402160\">2</span> <span m=\"402400\">is</span> <span\
  \ m=\"402760\">plus</span> <span m=\"403030\">1.</span> <span m=\"403630\">So</span>\
  \ <span m=\"404570\">it's</span> <span m=\"404910\">the</span> <span m=\"404980\"\
  >same</span> <span m=\"405290\">as</span> <span m=\"405970\">this</span> <span m=\"\
  406570\">even</span> <span m=\"406790\">nicer</span> <span m=\"407080\">looking</span>\
  \ <span m=\"407350\">equation,</span> <span m=\"407770\">x</span> <span m=\"407950\"\
  >plus</span> <span m=\"408190\">y</span> <span m=\"408370\">plus</span> <span m=\"\
  408630\">z</span> <span m=\"408890\">equals</span> <span m=\"409080\">2.</span></p><p><span\
  \ m=\"413960\">It</span> <span m=\"414110\">also</span> <span m=\"414320\">turns</span>\
  \ <span m=\"414530\">out</span> <span m=\"414620\">to</span> <span m=\"414680\"\
  >be</span> <span m=\"414770\">the</span> <span m=\"414830\">same</span> <span m=\"\
  415160\">as</span> <span m=\"415250\">saying</span> <span m=\"415490\">that</span>\
  \ <span m=\"415610\">x, y, z</span> <span m=\"415880\">would</span> <span m=\"416090\"\
  >lie</span> <span m=\"417830\">on</span> <span m=\"418350\">a</span> <span m=\"\
  418420\">line.</span> <span m=\"420880\">But</span> <span m=\"421040\">they</span>\
  \ <span m=\"421160\">are</span> <span m=\"421440\">aligned.</span></p><p><span m=\"\
  426780\">So</span> <span m=\"426920\">the</span> <span m=\"427050\">line</span>\
  \ <span m=\"427320\">has</span> <span m=\"427530\">three</span> <span m=\"427680\"\
  >points</span> <span m=\"428070\">in</span> <span m=\"428220\">F3.</span> <span\
  \ m=\"430050\">And</span> <span m=\"430290\">if</span> <span m=\"430440\">you</span>\
  \ <span m=\"430560\">look</span> <span m=\"430770\">at</span> <span m=\"430890\"\
  >the</span> <span m=\"431010\">coordinate</span> <span m=\"432160\">for</span> <span\
  \ m=\"432360\">every</span> <span m=\"432900\">i,</span> <span m=\"433650\">the</span>\
  \ <span m=\"435300\">i-th</span> <span m=\"435570\">coordinate</span> <span m=\"\
  439720\">of</span> <span m=\"441010\">x, y,</span> <span m=\"441250\">z</span> <span\
  \ m=\"443450\">are</span> <span m=\"443600\">all</span> <span m=\"444920\">distinct</span>\
  \ <span m=\"447950\">or all</span> <span m=\"448400\">equal.</span> <span m=\"452187\"\
  >So</span> <span m=\"452670\">easy</span> <span m=\"452860\">to</span> <span m=\"\
  452920\">check</span> <span m=\"453220\">all</span> <span m=\"453340\">these</span>\
  \ <span m=\"453550\">things</span> <span m=\"453730\">are</span> <span m=\"453820\"\
  >equivalent</span> <span m=\"454300\">to</span> <span m=\"454420\">each</span> <span\
  \ m=\"454600\">other.</span></p><p><span m=\"455280\">And</span> <span m=\"455440\"\
  >the</span> <span m=\"455530\">last</span> <span m=\"455770\">one</span> <span m=\"\
  455930\">is</span> <span m=\"456070\">a</span> <span m=\"456670\">nice</span> <span\
  \ m=\"457000\">interpretation</span> <span m=\"457990\">in</span> <span m=\"458110\"\
  >terms</span> <span m=\"458500\">of</span> <span m=\"459210\">a</span> <span m=\"\
  459310\">game</span> <span m=\"459640\">that</span> <span m=\"459790\">many</span>\
  \ <span m=\"460000\">of</span> <span m=\"460090\">you</span> <span m=\"460150\"\
  >know,</span> <span m=\"460750\">Set.</span> <span m=\"463460\">So</span> <span\
  \ m=\"463720\">in</span> <span m=\"463840\">the</span> <span m=\"463930\">game</span>\
  \ <span m=\"464190\">Set,</span> <span m=\"464560\">you</span> <span m=\"464650\"\
  >have</span> <span m=\"464770\">a</span> <span m=\"464800\">bunch</span> <span m=\"\
  465040\">of</span> <span m=\"465130\">cards.</span> <span m=\"465580\">There</span>\
  \ <span m=\"465670\">have</span> <span m=\"465790\">some</span> <span m=\"466000\"\
  >number</span> <span m=\"466240\">of</span> <span m=\"466330\">properties,</span>\
  \ <span m=\"466960\">n</span> <span m=\"467140\">properties,</span> <span m=\"467740\"\
  >like</span> <span m=\"468090\">color,</span> <span m=\"468660\">the</span> <span\
  \ m=\"468760\">number</span> <span m=\"469030\">of</span> <span m=\"469090\">symbols,</span>\
  \ <span m=\"469405\">the</span> <span m=\"469720\">shape.</span> <span m=\"470560\"\
  >And</span> <span m=\"470890\">you</span> <span m=\"471010\">want</span> <span m=\"\
  471220\">to</span> <span m=\"471280\">form</span> <span m=\"471550\">a</span> <span\
  \ m=\"471580\">set</span> <span m=\"472420\">being</span> <span m=\"473290\">three</span>\
  \ <span m=\"473560\">cards</span> <span m=\"474220\">such</span> <span m=\"474520\"\
  >that</span> <span m=\"475210\">every</span> <span m=\"475420\">property,</span>\
  \ <span m=\"475890\">they're all</span> <span m=\"476170\">same</span> <span m=\"\
  476740\">or all</span> <span m=\"477010\">different.</span> <span m=\"478120\">So</span>\
  \ <span m=\"478270\">that's</span> <span m=\"478900\">exactly</span> <span m=\"\
  479410\">this</span> <span m=\"479590\">model</span> <span m=\"479950\">over</span>\
  \ <span m=\"480180\">here.</span></p><p><span m=\"482780\">So</span> <span m=\"\
  482920\">what</span> <span m=\"483070\">can</span> <span m=\"483220\">we</span>\
  \ <span m=\"483340\">say</span> <span m=\"483550\">about</span> <span m=\"483790\"\
  >this</span> <span m=\"483940\">problem?</span> <span m=\"484360\">What's</span>\
  \ <span m=\"484600\">the</span> <span m=\"484750\">size</span> <span m=\"485080\"\
  >of</span> <span m=\"485140\">the</span> <span m=\"485230\">maximum</span> <span\
  \ m=\"485980\">subset</span> <span m=\"486520\">of</span> <span m=\"486820\">F3</span>\
  \ <span m=\"487120\">to</span> <span m=\"487240\">the</span> <span m=\"487360\"\
  >n-th</span> <span m=\"487510\">without</span> <span m=\"487960\">3-AP.</span> <span\
  \ m=\"489760\">If</span> <span m=\"489910\">you</span> <span m=\"489970\">look</span>\
  \ <span m=\"490180\">at</span> <span m=\"490390\">the</span> <span m=\"490480\"\
  >proof</span> <span m=\"490840\">that</span> <span m=\"490960\">we</span> <span\
  \ m=\"491110\">did</span> <span m=\"491410\">earlier</span> <span m=\"491740\">in</span>\
  \ <span m=\"491830\">this</span> <span m=\"492010\">course,</span> <span m=\"492400\"\
  >the</span> <span m=\"492520\">one</span> <span m=\"492730\">using</span> <span\
  \ m=\"493060\">triangle</span> <span m=\"493540\">removal</span> <span m=\"494000\"\
  >lemma,</span> <span m=\"494440\">you</span> <span m=\"494560\">see</span> <span\
  \ m=\"494680\">the</span> <span m=\"494740\">proof</span> <span m=\"495130\">works</span>\
  \ <span m=\"495490\">verbatim.</span> <span m=\"496630\">Previously,</span> <span\
  \ m=\"497080\">we</span> <span m=\"497200\">worked</span> <span m=\"497470\">over</span>\
  \ <span m=\"497680\">Z mod n.</span> <span m=\"497980\">Now,</span> <span m=\"498280\"\
  >you</span> <span m=\"498370\">work</span> <span m=\"498580\">over</span> <span\
  \ m=\"498790\">a</span> <span m=\"498820\">different</span> <span m=\"499120\">group,</span>\
  \ <span m=\"499540\">same</span> <span m=\"499780\">proof.</span></p><p><span m=\"\
  501388\">So</span> <span m=\"501790\">triangle</span> <span m=\"502480\">removal</span>\
  \ <span m=\"502810\">lemma,</span> <span m=\"504250\">it</span> <span m=\"504340\"\
  >tells</span> <span m=\"504610\">you</span> <span m=\"505090\">that</span> <span\
  \ m=\"505810\">this</span> <span m=\"506230\">r3</span> <span m=\"507100\">is</span>\
  \ <span m=\"507370\">always</span> <span m=\"511280\">little</span> <span m=\"511590\"\
  >o</span> <span m=\"511900\">of</span> <span m=\"512049\">the</span> <span m=\"\
  512350\">size</span> <span m=\"512710\">of</span> <span m=\"512799\">the</span>\
  \ <span m=\"512890\">space.</span> <span m=\"514490\">But</span> <span m=\"514610\"\
  >we</span> <span m=\"514760\">would</span> <span m=\"514860\">like</span> <span\
  \ m=\"515010\">to</span> <span m=\"515090\">do</span> <span m=\"515240\">better.</span>\
  \ <span m=\"515860\">So</span> <span m=\"515929\">this</span> <span m=\"516260\"\
  >gives</span> <span m=\"516470\">you</span> <span m=\"516559\">something</span>\
  \ <span m=\"516860\">like</span> <span m=\"517130\">log star.</span> <span m=\"\
  517710\">It's</span> <span m=\"518210\">not very</span> <span m=\"518630\">good</span>\
  \ <span m=\"518780\">dependence.</span> <span m=\"519659\">So</span> <span m=\"\
  519710\">we</span> <span m=\"519860\">would</span> <span m=\"519980\">like</span>\
  \ <span m=\"520159\">to</span> <span m=\"520250\">do</span> <span m=\"520400\">better.</span></p><p><span\
  \ m=\"521820\">So</span> <span m=\"521870\">what</span> <span m=\"522030\">we will</span>\
  \ <span m=\"522210\">show</span> <span m=\"522470\">today,</span> <span m=\"524290\"\
  >so</span> <span m=\"524420\">this</span> <span m=\"524710\">theorem is</span> <span\
  \ m=\"526040\">attributed</span> <span m=\"526490\">to</span> <span m=\"526755\"\
  >Meshulam.</span> <span m=\"531010\">So</span> <span m=\"531200\">in</span> <span\
  \ m=\"531320\">this</span> <span m=\"531500\">case,</span> <span m=\"531800\">the</span>\
  \ <span m=\"532640\">order</span> <span m=\"532970\">of</span> <span m=\"533060\"\
  >history</span> <span m=\"533450\">is</span> <span m=\"533540\">somewhat</span>\
  \ <span m=\"533840\">reversed.</span> <span m=\"534350\">So</span> <span m=\"534500\"\
  >we'll</span> <span m=\"534650\">see</span> <span m=\"535060\">the</span> <span\
  \ m=\"535320\">finite</span> <span m=\"535840\">field</span> <span m=\"536270\"\
  >toy</span> <span m=\"536510\">model,</span> <span m=\"537010\">but</span> <span\
  \ m=\"537220\">it</span> <span m=\"537390\">historically</span> <span m=\"537890\"\
  >actually</span> <span m=\"538100\">came</span> <span m=\"538370\">afterwards.</span></p><p><span\
  \ m=\"540020\">But</span> <span m=\"540680\">you'll</span> <span m=\"540860\">see</span>\
  \ <span m=\"541100\">that</span> <span m=\"541895\">the</span> <span m=\"542390\"\
  >Fourier</span> <span m=\"542810\">analytic</span> <span m=\"543330\">proof</span>\
  \ <span m=\"543680\">that</span> <span m=\"543800\">we'll</span> <span m=\"543950\"\
  >see</span> <span m=\"544130\">today,</span> <span m=\"545510\">it's</span> <span\
  \ m=\"545930\">basically</span> <span m=\"546320\">the</span> <span m=\"546410\"\
  >same</span> <span m=\"546680\">proof</span> <span m=\"547040\">in</span> <span\
  \ m=\"547130\">the</span> <span m=\"547190\">two</span> <span m=\"547400\">settings.</span>\
  \ <span m=\"548510\">So</span> <span m=\"549000\">F</span> <span m=\"549440\">is</span>\
  \ <span m=\"549700\">r3,</span> <span m=\"552630\">we</span> <span m=\"552780\"\
  >will</span> <span m=\"552960\">prove</span> <span m=\"553290\">a bound,</span>\
  \ <span m=\"556980\">well,</span> <span m=\"557110\">just</span> <span m=\"557290\"\
  >like</span> <span m=\"557470\">that.</span> <span m=\"559730\">So</span> <span\
  \ m=\"559850\">much</span> <span m=\"560090\">better</span> <span m=\"560500\">than</span>\
  \ <span m=\"562280\">what</span> <span m=\"562400\">you</span> <span m=\"562520\"\
  >get</span> <span m=\"562730\">from</span> <span m=\"563060\">the</span> <span m=\"\
  563150\">regularity</span> <span m=\"563720\">method.</span></p><p><span m=\"567470\"\
  >In</span> <span m=\"567620\">terms</span> <span m=\"568010\">of--</span> <span\
  \ m=\"568970\">OK,</span> <span m=\"569120\">so</span> <span m=\"569240\">let</span>\
  \ <span m=\"569330\">me</span> <span m=\"569420\">tell</span> <span m=\"569540\"\
  >you</span> <span m=\"569600\">a</span> <span m=\"569660\">bit</span> <span m=\"\
  569810\">more</span> <span m=\"569990\">about</span> <span m=\"570170\">the</span>\
  \ <span m=\"570230\">history</span> <span m=\"570620\">of</span> <span m=\"570740\"\
  >this</span> <span m=\"570890\">problem</span> <span m=\"571250\">in</span> <span\
  \ m=\"571310\">terms</span> <span m=\"571580\">of</span> <span m=\"571670\">what</span>\
  \ <span m=\"571820\">we</span> <span m=\"571970\">know</span> <span m=\"572790\"\
  >in</span> <span m=\"572970\">terms</span> <span m=\"573330\">of</span> <span m=\"\
  573470\">upper</span> <span m=\"573680\">bounds</span> <span m=\"573980\">and</span>\
  \ <span m=\"574700\">lower</span> <span m=\"574910\">bounds.</span> <span m=\"580770\"\
  >So</span> <span m=\"580850\">let</span> <span m=\"580970\">me</span> <span m=\"\
  581090\">say</span> <span m=\"581420\">more</span> <span m=\"581720\">about</span>\
  \ <span m=\"582570\">F3.</span> <span m=\"585920\">So</span> <span m=\"586070\"\
  >what's</span> <span m=\"586340\">the</span> <span m=\"586850\">best</span> <span\
  \ m=\"587105\">that</span> <span m=\"587360\">you</span> <span m=\"587510\">might</span>\
  \ <span m=\"587750\">hope</span> <span m=\"588050\">for?</span> <span m=\"589200\"\
  >So</span> <span m=\"589610\">the</span> <span m=\"589670\">best</span> <span m=\"\
  590000\">lower</span> <span m=\"590450\">bound</span> <span m=\"594930\">is</span>\
  \ <span m=\"596050\">due</span> <span m=\"596260\">to</span> <span m=\"597490\"\
  >E</span> <span m=\"597700\">del.</span> <span m=\"598350\">And</span> <span m=\"\
  598560\">it's</span> <span m=\"598710\">some</span> <span m=\"598980\">construction,</span>\
  \ <span m=\"599760\">some</span> <span m=\"600030\">very</span> <span m=\"600240\"\
  >specific</span> <span m=\"600720\">construction,</span> <span m=\"601890\">which</span>\
  \ <span m=\"602160\">gives</span> <span m=\"602490\">you</span> <span m=\"602610\"\
  >a</span> <span m=\"602800\">bound</span> <span m=\"603520\">that's</span> <span\
  \ m=\"604170\">something</span> <span m=\"604590\">like</span> <span m=\"604830\"\
  >2.21</span> <span m=\"605910\">to</span> <span m=\"606090\">the</span> <span m=\"\
  606210\">n-th.</span> <span m=\"608870\">And</span> <span m=\"609000\">the</span>\
  \ <span m=\"609150\">upper</span> <span m=\"609360\">bound</span> <span m=\"609660\"\
  >is</span> <span m=\"609930\">3</span> <span m=\"610190\">to</span> <span m=\"610350\"\
  >the</span> <span m=\"610640\">n-th--</span> <span m=\"611470\">on</span> <span\
  \ m=\"611680\">the--</span> <span m=\"612240\">3</span> <span m=\"612570\">minus</span>\
  \ <span m=\"612930\">little</span> <span m=\"613200\">1</span> <span m=\"613380\"\
  >to</span> <span m=\"613500\">the</span> <span m=\"613620\">n-th.</span></p><p><span\
  \ m=\"613920\">So</span> <span m=\"614580\">for</span> <span m=\"614850\">a</span>\
  \ <span m=\"614880\">long</span> <span m=\"615090\">time,</span> <span m=\"616350\"\
  >it</span> <span m=\"616440\">was</span> <span m=\"616860\">open</span> <span m=\"\
  621820\">whether</span> <span m=\"624820\">the</span> <span m=\"624940\">answer</span>\
  \ <span m=\"625750\">should</span> <span m=\"626020\">be</span> <span m=\"626770\"\
  >basically</span> <span m=\"628360\">roughly</span> <span m=\"628690\">like</span>\
  \ <span m=\"628870\">3</span> <span m=\"629080\">to</span> <span m=\"629200\">the</span>\
  \ <span m=\"629320\">n-th</span> <span m=\"629650\">or</span> <span m=\"629800\"\
  >some</span> <span m=\"630190\">constant</span> <span m=\"630670\">less</span> <span\
  \ m=\"630910\">than</span> <span m=\"631060\">3</span> <span m=\"631630\">to</span>\
  \ <span m=\"631750\">the</span> <span m=\"631970\">n-th.</span> <span m=\"633690\"\
  >And</span> <span m=\"633900\">improvements</span> <span m=\"634560\">on</span>\
  \ <span m=\"634650\">the</span> <span m=\"634740\">upper</span> <span m=\"634980\"\
  >bound</span> <span m=\"635430\">were</span> <span m=\"636150\">very</span> <span\
  \ m=\"636360\">slow,</span> <span m=\"636960\">and/or</span> <span m=\"637350\"\
  >some</span> <span m=\"637560\">very</span> <span m=\"637770\">difficult</span>\
  \ <span m=\"638250\">works</span> <span m=\"638560\">that</span> <span m=\"639240\"\
  >nudge</span> <span m=\"639660\">that</span> <span m=\"639870\">down</span> <span\
  \ m=\"640170\">below</span> <span m=\"640480\">just</span> <span m=\"640740\">a</span>\
  \ <span m=\"640800\">little</span> <span m=\"641040\">bit.</span></p><p><span m=\"\
  642120\">And</span> <span m=\"642210\">then</span> <span m=\"642390\">a</span> <span\
  \ m=\"642450\">couple</span> <span m=\"642750\">years</span> <span m=\"643020\"\
  >ago,</span> <span m=\"643680\">a</span> <span m=\"643740\">few</span> <span m=\"\
  643920\">years</span> <span m=\"644160\">ago,</span> <span m=\"644730\">there</span>\
  \ <span m=\"644940\">was</span> <span m=\"645450\">this</span> <span m=\"645720\"\
  >incredible</span> <span m=\"646260\">breakthrough,</span> <span m=\"648210\">where</span>\
  \ <span m=\"648600\">in</span> <span m=\"650130\">this</span> <span m=\"650370\"\
  >paper</span> <span m=\"650790\">that</span> <span m=\"650970\">was</span> <span\
  \ m=\"651180\">just</span> <span m=\"651570\">a</span> <span m=\"651630\">couple</span>\
  \ <span m=\"651930\">pages</span> <span m=\"652320\">long,</span> <span m=\"652770\"\
  >they</span> <span m=\"652890\">managed</span> <span m=\"653250\">to</span> <span\
  \ m=\"653580\">significantly</span> <span m=\"654390\">improve</span> <span m=\"\
  655080\">the</span> <span m=\"655200\">upper</span> <span m=\"655440\">bound</span>\
  \ <span m=\"656160\">to</span> <span m=\"660640\">basically</span> <span m=\"661240\"\
  >2.76</span> <span m=\"663370\">to</span> <span m=\"663520\">the</span> <span m=\"\
  663760\">n-th.</span> <span m=\"667030\">So</span> <span m=\"667210\">this</span>\
  \ <span m=\"667420\">was</span> <span m=\"667870\">an</span> <span m=\"667990\"\
  >incredible</span> <span m=\"668470\">breakthrough</span> <span m=\"668980\">that</span>\
  \ <span m=\"669100\">happened</span> <span m=\"669490\">just</span> <span m=\"669760\"\
  >a</span> <span m=\"669790\">few</span> <span m=\"669970\">years</span> <span m=\"\
  670180\">ago.</span> <span m=\"671020\">And</span> <span m=\"671200\">we'll</span>\
  \ <span m=\"671380\">talk</span> <span m=\"671650\">about</span> <span m=\"671860\"\
  >this</span> <span m=\"672010\">proof</span> <span m=\"672340\">in</span> <span\
  \ m=\"672490\">a</span> <span m=\"672520\">couple</span> <span m=\"672820\">of</span>\
  \ <span m=\"672910\">lectures.</span></p><p><span m=\"674330\">It</span> <span m=\"\
  674430\">turns</span> <span m=\"674560\">out</span> <span m=\"674950\">this</span>\
  \ <span m=\"675370\">proof,</span> <span m=\"676090\">which</span> <span m=\"676330\"\
  >uses</span> <span m=\"677060\">what's</span> <span m=\"677440\">now</span> <span\
  \ m=\"677710\">called</span> <span m=\"678140\">the</span> <span m=\"678220\">polynomial</span>\
  \ <span m=\"678880\">method--</span> <span m=\"682030\">so</span> <span m=\"682280\"\
  >not</span> <span m=\"682580\">Fourier</span> <span m=\"682910\">analytic,</span>\
  \ <span m=\"683420\">but</span> <span m=\"683570\">a</span> <span m=\"683600\">different</span>\
  \ <span m=\"683930\">method--</span> <span m=\"684950\">unfortunately</span> <span\
  \ m=\"685820\">does</span> <span m=\"686090\">not</span> <span m=\"686900\">seem</span>\
  \ <span m=\"687230\">to</span> <span m=\"687350\">generalize</span> <span m=\"688100\"\
  >to</span> <span m=\"688370\">the</span> <span m=\"688520\">original</span> <span\
  \ m=\"688940\">Roth's</span> <span m=\"689215\">theorem.</span> <span m=\"690580\"\
  >In</span> <span m=\"690650\">fact,</span> <span m=\"690830\">you</span> <span m=\"\
  690890\">shouldn't</span> <span m=\"691190\">expect</span> <span m=\"691630\">it</span>\
  \ <span m=\"691700\">to</span> <span m=\"691790\">generalize</span> <span m=\"692510\"\
  >in</span> <span m=\"692660\">a</span> <span m=\"692690\">straightforward</span>\
  \ <span m=\"693260\">way,</span> <span m=\"694040\">because</span> <span m=\"694790\"\
  >up</span> <span m=\"694980\">there</span> <span m=\"695350\">you</span> <span m=\"\
  695610\">we</span> <span m=\"695720\">know</span> <span m=\"695960\">that</span>\
  \ <span m=\"696080\">you</span> <span m=\"696200\">do</span> <span m=\"696350\"\
  >not</span> <span m=\"696530\">have</span> <span m=\"696640\">a</span> <span m=\"\
  696680\">power</span> <span m=\"697040\">saving,</span> <span m=\"697760\">whereas</span>\
  \ <span m=\"698060\">here</span> <span m=\"698360\">you</span> <span m=\"698630\"\
  >have</span> <span m=\"698810\">a</span> <span m=\"698840\">power</span> <span m=\"\
  699200\">saving.</span> <span m=\"699780\">So</span> <span m=\"700010\">the</span>\
  \ <span m=\"700100\">exponent</span> <span m=\"700640\">goes</span> <span m=\"700880\"\
  >down.</span> <span m=\"703360\">OK,</span> <span m=\"703560\">so</span> <span m=\"\
  703710\">this</span> <span m=\"703920\">is</span> <span m=\"704160\">roughly</span>\
  \ <span m=\"704460\">the</span> <span m=\"704550\">history</span> <span m=\"705030\"\
  >of</span> <span m=\"705120\">this</span> <span m=\"705330\">theorem.</span> <span\
  \ m=\"709150\">Any</span> <span m=\"709330\">questions?</span></p><p><span m=\"\
  713272\">AUDIENCE:</span> <span m=\"713320\">Do</span> <span m=\"713368\">we</span>\
  \ <span m=\"713416\">have</span> <span m=\"713464\">to</span> <span m=\"713515\"\
  >have</span> <span m=\"713758\">[INAUDIBLE]?</span></p><p><span m=\"715216\">YUFEI\
  \ ZHAO:</span> <span m=\"715710\">Yeah.</span> <span m=\"716070\">So</span> <span\
  \ m=\"716660\">I'll--</span> <span m=\"717540\">So</span> <span m=\"717790\">I can</span>\
  \ <span m=\"717940\">tell you</span> <span m=\"718270\">this</span> <span m=\"718480\"\
  >is</span> <span m=\"719260\">known</span> <span m=\"719470\">as</span> <span m=\"\
  719620\">a</span> <span m=\"719680\">Croot-Lev-Pach.</span> <span m=\"721860\">So</span>\
  \ <span m=\"722050\">I'll</span> <span m=\"722140\">say</span> <span m=\"722410\"\
  >more</span> <span m=\"722620\">about</span> <span m=\"722860\">it</span> <span\
  \ m=\"724240\">in</span> <span m=\"724390\">a</span> <span m=\"724420\">couple</span>\
  \ <span m=\"724660\">lectures.</span> <span m=\"725050\">But</span> <span m=\"725230\"\
  >this</span> <span m=\"725790\">for</span> <span m=\"725970\">F3</span> <span m=\"\
  727120\">is</span> <span m=\"727570\">due</span> <span m=\"727780\">to</span> <span\
  \ m=\"728200\">Ellenberg</span> <span m=\"728440\">and</span> <span m=\"729220\"\
  >Gijswijt.</span> <span m=\"736560\">So</span> <span m=\"736710\">I'll</span> <span\
  \ m=\"737160\">tell</span> <span m=\"737370\">you</span> <span m=\"737460\">more</span>\
  \ <span m=\"737640\">about</span> <span m=\"737850\">it</span> <span m=\"737910\"\
  >in</span> <span m=\"738030\">a</span> <span m=\"738060\">couple</span> <span m=\"\
  738330\">lectures.</span></p><p><span m=\"741900\">What</span> <span m=\"742050\"\
  >I</span> <span m=\"742110\">want</span> <span m=\"742260\">to</span> <span m=\"\
  742320\">focus</span> <span m=\"742650\">on</span> <span m=\"742740\">today</span>\
  \ <span m=\"743130\">is</span> <span m=\"744240\">the</span> <span m=\"744600\"\
  >Fourier</span> <span m=\"745020\">analytic</span> <span m=\"745500\">nature</span>\
  \ <span m=\"745860\">of</span> <span m=\"745980\">the</span> <span m=\"746040\"\
  >proof</span> <span m=\"746610\">that</span> <span m=\"746760\">gives</span> <span\
  \ m=\"747030\">you</span> <span m=\"747660\">this</span> <span m=\"747870\">bound</span>\
  \ <span m=\"748200\">up</span> <span m=\"748350\">there,</span> <span m=\"748800\"\
  >3</span> <span m=\"748980\">to</span> <span m=\"749100\">the</span> <span m=\"\
  749220\">n</span> <span m=\"749550\">over</span> <span m=\"749760\">n.</span> <span\
  \ m=\"751080\">And</span> <span m=\"751650\">it</span> <span m=\"751740\">may</span>\
  \ <span m=\"751890\">seem</span> <span m=\"752130\">like</span> <span m=\"752280\"\
  >a</span> <span m=\"752340\">completely</span> <span m=\"752760\">different</span>\
  \ <span m=\"753030\">topic</span> <span m=\"753510\">compared</span> <span m=\"\
  753900\">to</span> <span m=\"754020\">what</span> <span m=\"754230\">we've</span>\
  \ <span m=\"754410\">been</span> <span m=\"754530\">doing</span> <span m=\"754770\"\
  >so</span> <span m=\"754950\">far</span> <span m=\"755580\">in</span> <span m=\"\
  755670\">the</span> <span m=\"755760\">course,</span> <span m=\"756190\">which</span>\
  \ <span m=\"756270\">is</span> <span m=\"756390\">more</span> <span m=\"756540\"\
  >about</span> <span m=\"756750\">graph</span> <span m=\"757080\">theory.</span>\
  \ <span m=\"757650\">But</span> <span m=\"758160\">I</span> <span m=\"758250\">want</span>\
  \ <span m=\"758490\">you</span> <span m=\"758580\">to</span> <span m=\"758700\"\
  >think</span> <span m=\"758910\">about</span> <span m=\"759670\">what</span> <span\
  \ m=\"759870\">are</span> <span m=\"760080\">the</span> <span m=\"760740\">relationships</span>\
  \ <span m=\"761520\">between</span> <span m=\"762180\">what</span> <span m=\"762330\"\
  >we'll</span> <span m=\"762480\">see</span> <span m=\"762690\">today</span> <span\
  \ m=\"763590\">and</span> <span m=\"763830\">what</span> <span m=\"764010\">we've</span>\
  \ <span m=\"764220\">seen</span> <span m=\"764460\">so</span> <span m=\"764640\"\
  >far.</span></p><p><span m=\"765280\">And</span> <span m=\"765330\">there</span>\
  \ <span m=\"765510\">are</span> <span m=\"765570\">lots</span> <span m=\"765990\"\
  >of</span> <span m=\"766110\">connections.</span> <span m=\"767160\">So</span> <span\
  \ m=\"767310\">even</span> <span m=\"767490\">though</span> <span m=\"767610\">the</span>\
  \ <span m=\"767670\">proof</span> <span m=\"767970\">may</span> <span m=\"768100\"\
  >superficially</span> <span m=\"768720\">look</span> <span m=\"768870\">quite</span>\
  \ <span m=\"769110\">different,</span> <span m=\"770130\">many</span> <span m=\"\
  770430\">of</span> <span m=\"770520\">these</span> <span m=\"770700\">ideas</span>\
  \ <span m=\"771120\">about</span> <span m=\"771690\">quasirandomness</span> <span\
  \ m=\"772680\">versus</span> <span m=\"772980\">structure</span> <span m=\"773820\"\
  >will</span> <span m=\"773970\">come</span> <span m=\"774180\">up.</span> <span\
  \ m=\"774570\">And</span> <span m=\"774680\">I</span> <span m=\"774750\">want</span>\
  \ <span m=\"774900\">to</span> <span m=\"774960\">present</span> <span m=\"775290\"\
  >the</span> <span m=\"775380\">proof</span> <span m=\"775680\">in</span> <span m=\"\
  775800\">a</span> <span m=\"775830\">way</span> <span m=\"776430\">that</span> <span\
  \ m=\"776910\">highlights</span> <span m=\"777510\">the</span> <span m=\"777570\"\
  >similarities</span> <span m=\"778440\">between</span> <span m=\"779220\">what</span>\
  \ <span m=\"779310\">we</span> <span m=\"779460\">did</span> <span m=\"779610\"\
  >previously</span> <span m=\"780580\">and</span> <span m=\"781020\">this</span>\
  \ <span m=\"781230\">Fourier</span> <span m=\"781620\">analytic</span> <span m=\"\
  782060\">proof.</span></p><p><span m=\"784980\">So</span> <span m=\"786380\">let's</span>\
  \ <span m=\"786590\">talk</span> <span m=\"786830\">about</span> <span m=\"787430\"\
  >the</span> <span m=\"787520\">strategy.</span> <span m=\"790390\">In</span> <span\
  \ m=\"790540\">the</span> <span m=\"790600\">proof</span> <span m=\"791140\">of</span>\
  \ <span m=\"792100\">the</span> <span m=\"792470\">Szemer\xE9di</span> <span m=\"\
  793110\">graph</span> <span m=\"793540\">regularity</span> <span m=\"794200\">lemma,</span>\
  \ <span m=\"795220\">we</span> <span m=\"795460\">had</span> <span m=\"795700\"\
  >the</span> <span m=\"795840\">strategy</span> <span m=\"796360\">that</span> <span\
  \ m=\"796480\">we</span> <span m=\"796600\">called</span> <span m=\"796830\">the</span>\
  \ <span m=\"796960\">energy</span> <span m=\"797470\">increment</span> <span m=\"\
  797920\">strategy.</span> <span m=\"799590\">So</span> <span m=\"799710\">you</span>\
  \ <span m=\"799830\">start--</span> <span m=\"800310\">you</span> <span m=\"800400\"\
  >want</span> <span m=\"800580\">to</span> <span m=\"800640\">find</span> <span m=\"\
  800850\">a</span> <span m=\"800910\">good</span> <span m=\"801090\">partition.</span>\
  \ <span m=\"802080\">You</span> <span m=\"802170\">start</span> <span m=\"802410\"\
  >doing</span> <span m=\"802590\">partitioning.</span> <span m=\"803220\">And</span>\
  \ <span m=\"803630\">you</span> <span m=\"803670\">keep</span> <span m=\"803910\"\
  >track</span> <span m=\"804270\">of</span> <span m=\"804390\">this</span> <span\
  \ m=\"804570\">thing</span> <span m=\"804780\">called</span> <span m=\"804990\"\
  >the</span> <span m=\"805110\">energy--</span> <span m=\"806580\">must go</span>\
  \ <span m=\"807020\">up</span> <span m=\"807380\">at</span> <span m=\"807510\">every</span>\
  \ <span m=\"807750\">step,</span> <span m=\"808680\">cannot</span> <span m=\"809010\"\
  >go</span> <span m=\"809190\">up</span> <span m=\"809610\">forever,</span> <span\
  \ m=\"810700\">so</span> <span m=\"811050\">has a</span> <span m=\"811200\">bounded</span>\
  \ <span m=\"811530\">number</span> <span m=\"811830\">of</span> <span m=\"811920\"\
  >steps.</span></p><p><span m=\"814220\">This</span> <span m=\"814470\">strategy</span>\
  \ <span m=\"814930\">for</span> <span m=\"815170\">Roth's</span> <span m=\"815450\"\
  >theorem</span> <span m=\"816130\">is</span> <span m=\"816310\">also</span> <span\
  \ m=\"816970\">an</span> <span m=\"817090\">important</span> <span m=\"817570\"\
  >strategy.</span> <span m=\"818140\">It's</span> <span m=\"818260\">a</span> <span\
  \ m=\"818320\">variant</span> <span m=\"818750\">of</span> <span m=\"819220\">energy</span>\
  \ <span m=\"819550\">increment,</span> <span m=\"820270\">but</span> <span m=\"\
  820390\">now</span> <span m=\"820750\">density</span> <span m=\"821290\">increment.</span>\
  \ <span m=\"833930\">So</span> <span m=\"834050\">we</span> <span m=\"834200\">start</span>\
  \ <span m=\"834620\">with</span> <span m=\"834950\">a</span> <span m=\"835190\"\
  >set--</span> <span m=\"836240\">A</span> <span m=\"837620\">subset</span> <span\
  \ m=\"838100\">of</span> <span m=\"838170\">F3</span> <span m=\"838550\">to the\
  \ n-th,</span> <span m=\"840140\">and</span> <span m=\"840380\">we</span> <span\
  \ m=\"840560\">would</span> <span m=\"840680\">like</span> <span m=\"840830\">to</span>\
  \ <span m=\"840950\">understand</span> <span m=\"842000\">something</span> <span\
  \ m=\"842420\">about</span> <span m=\"843230\">its</span> <span m=\"843920\">structure</span>\
  \ <span m=\"844850\">versus</span> <span m=\"845720\">pseudorandomness</span> <span\
  \ m=\"847160\">in</span> <span m=\"847270\">a</span> <span m=\"847340\">way</span>\
  \ <span m=\"847490\">that</span> <span m=\"847670\">is</span> <span m=\"847760\"\
  >similar</span> <span m=\"848270\">to</span> <span m=\"848600\">when</span> <span\
  \ m=\"848750\">we</span> <span m=\"848870\">discussed</span> <span m=\"850040\"\
  >the</span> <span m=\"850160\">similar</span> <span m=\"850610\">issue</span> <span\
  \ m=\"850940\">for</span> <span m=\"851510\">graphs.</span></p><p><span m=\"853670\"\
  >In</span> <span m=\"853760\">particular,</span> <span m=\"854270\">there</span>\
  \ <span m=\"854420\">will</span> <span m=\"854540\">be</span> <span m=\"854660\"\
  >this</span> <span m=\"854840\">dichotomy</span> <span m=\"856280\">that</span>\
  \ <span m=\"856670\">if</span> <span m=\"858080\">A</span> <span m=\"858830\">is</span>\
  \ <span m=\"859970\">in</span> <span m=\"860090\">some</span> <span m=\"860300\"\
  >sense</span> <span m=\"860870\">pseudorandom--</span> <span m=\"864460\">so</span>\
  \ <span m=\"864690\">earlier,</span> <span m=\"865020\">we</span> <span m=\"865170\"\
  >saw</span> <span m=\"865410\">what</span> <span m=\"865530\">it</span> <span m=\"\
  865590\">means</span> <span m=\"865860\">for</span> <span m=\"866140\">a</span>\
  \ <span m=\"866160\">graph</span> <span m=\"866610\">to</span> <span m=\"866730\"\
  >be</span> <span m=\"866880\">pseudorandom.</span> <span m=\"868020\">So</span>\
  \ <span m=\"868170\">now,</span> <span m=\"868470\">what</span> <span m=\"868650\"\
  >does</span> <span m=\"868780\">it</span> <span m=\"868860\">mean</span> <span m=\"\
  869070\">for</span> <span m=\"869460\">a</span> <span m=\"869490\">subset</span>\
  \ <span m=\"870210\">of</span> <span m=\"870420\">F3</span> <span m=\"870750\">to</span>\
  \ <span m=\"870870\">the</span> <span m=\"870990\">n-th</span> <span m=\"871200\"\
  >to</span> <span m=\"871320\">be</span> <span m=\"871470\">pseudorandom.</span>\
  \ <span m=\"873030\">So</span> <span m=\"873180\">we'll</span> <span m=\"873330\"\
  >address</span> <span m=\"873630\">that</span> <span m=\"873750\">today.</span></p><p><span\
  \ m=\"874440\">If</span> <span m=\"874660\">A</span> <span m=\"874890\">pseudorandom--</span>\
  \ <span m=\"877010\">OK,</span> <span m=\"877290\">so</span> <span m=\"878190\"\
  >the</span> <span m=\"878310\">short</span> <span m=\"878700\">answer</span> <span\
  \ m=\"879120\">is</span> <span m=\"879270\">that</span> <span m=\"879870\">it</span>\
  \ <span m=\"879990\">is</span> <span m=\"880420\">Fourier</span> <span m=\"880850\"\
  >uniform--</span> <span m=\"883470\">in</span> <span m=\"883560\">other</span> <span\
  \ m=\"883710\">words,</span> <span m=\"884530\">all</span> <span m=\"884670\">Fourier</span>\
  \ <span m=\"885150\">coefficients</span> <span m=\"887700\">small.</span> <span\
  \ m=\"891220\">That's</span> <span m=\"891430\">what</span> <span m=\"891670\">pseudorandom</span>\
  \ <span m=\"892330\">will</span> <span m=\"892480\">refer</span> <span m=\"892780\"\
  >to.</span> <span m=\"893470\">So</span> <span m=\"893620\">then</span> <span m=\"\
  895340\">there</span> <span m=\"895640\">is</span> <span m=\"895850\">a</span> <span\
  \ m=\"895910\">counting</span> <span m=\"896410\">lemma.</span> <span m=\"901720\"\
  >And</span> <span m=\"901870\">the</span> <span m=\"901930\">counting</span> <span\
  \ m=\"902320\">lemma</span> <span m=\"902560\">will</span> <span m=\"902770\">in</span>\
  \ <span m=\"902860\">particular</span> <span m=\"903760\">imply</span> <span m=\"\
  904240\">that</span> <span m=\"904420\">A</span> <span m=\"904750\">has</span> <span\
  \ m=\"906310\">lots</span> <span m=\"906790\">of</span> <span m=\"906940\">3-APs.</span>\
  \ <span m=\"913700\">So</span> <span m=\"913850\">then</span> <span m=\"914030\"\
  >you</span> <span m=\"914150\">find</span> <span m=\"914360\">your</span> <span\
  \ m=\"914660\">3-AP.</span></p><p><span m=\"916880\">If</span> <span m=\"917060\"\
  >this</span> <span m=\"917210\">is</span> <span m=\"917330\">not</span> <span m=\"\
  917570\">the</span> <span m=\"917660\">case,</span> <span m=\"918900\">then--</span>\
  \ <span m=\"919410\">so</span> <span m=\"919550\">what's</span> <span m=\"919760\"\
  >the</span> <span m=\"919850\">opposite</span> <span m=\"920300\">of</span> <span\
  \ m=\"920420\">Fourier</span> <span m=\"920950\">uniform--</span> <span m=\"921890\"\
  >is</span> <span m=\"922040\">that</span> <span m=\"922850\">A</span> <span m=\"\
  923180\">now</span> <span m=\"923450\">has</span> <span m=\"923740\">some</span>\
  \ <span m=\"923960\">large</span> <span m=\"924380\">Fourier</span> <span m=\"924740\"\
  >coefficient.</span> <span m=\"936190\">And</span> <span m=\"937150\">what</span>\
  \ <span m=\"937360\">we'll</span> <span m=\"937510\">do</span> <span m=\"938170\"\
  >is</span> <span m=\"938350\">to</span> <span m=\"938470\">use</span> <span m=\"\
  938740\">this</span> <span m=\"938890\">Fourier</span> <span m=\"939250\">coefficient</span>\
  \ <span m=\"940270\">to</span> <span m=\"940660\">extract</span> <span m=\"941710\"\
  >some</span> <span m=\"942700\">codimension</span> <span m=\"944500\">1</span> <span\
  \ m=\"945820\">affine</span> <span m=\"946360\">subspace--</span> <span m=\"951960\"\
  >it's</span> <span m=\"952250\">also</span> <span m=\"953900\">called</span> <span\
  \ m=\"954110\">a</span> <span m=\"954170\">hyperplane--</span> <span m=\"957420\"\
  >where</span> <span m=\"960050\">the</span> <span m=\"960200\">density</span> <span\
  \ m=\"960860\">of</span> <span m=\"962870\">A</span> <span m=\"964280\">goes</span>\
  \ <span m=\"964580\">up</span> <span m=\"964880\">significantly,</span> <span m=\"\
  966470\">if</span> <span m=\"966620\">you</span> <span m=\"966770\">restrict</span>\
  \ <span m=\"967310\">to</span> <span m=\"967490\">that</span> <span m=\"967850\"\
  >sub</span> <span m=\"968090\">hyperplane.</span></p><p><span m=\"974090\">And</span>\
  \ <span m=\"974270\">you</span> <span m=\"974360\">can</span> <span m=\"974510\"\
  >repeat</span> <span m=\"974870\">this</span> <span m=\"975020\">process.</span>\
  \ <span m=\"975500\">Now,</span> <span m=\"976230\">restrict</span> <span m=\"976680\"\
  >to</span> <span m=\"976790\">this</span> <span m=\"976940\">hyperplane</span> <span\
  \ m=\"978140\">and</span> <span m=\"978290\">ask</span> <span m=\"978560\">yourself</span>\
  \ <span m=\"978920\">the</span> <span m=\"978980\">same</span> <span m=\"979280\"\
  >question.</span> <span m=\"980660\">Is</span> <span m=\"980870\">A,</span> <span\
  \ m=\"981410\">when</span> <span m=\"981590\">restricted</span> <span m=\"982100\"\
  >to</span> <span m=\"982190\">this</span> <span m=\"982340\">hyperplane,</span>\
  \ <span m=\"983780\">pseudorandom?</span> <span m=\"985220\">In</span> <span m=\"\
  985310\">which</span> <span m=\"985490\">case,</span> <span m=\"985910\">we</span>\
  \ <span m=\"986060\">find</span> <span m=\"986450\">APs.</span> <span m=\"987830\"\
  >Or</span> <span m=\"988100\">is</span> <span m=\"988340\">A</span> <span m=\"988640\"\
  >restricted</span> <span m=\"988985\">to this</span> <span m=\"989330\">hyperplane,</span>\
  \ <span m=\"991230\">does</span> <span m=\"991430\">it</span> <span m=\"991510\"\
  >have</span> <span m=\"991650\">a</span> <span m=\"991710\">large</span> <span m=\"\
  992070\">Fourier</span> <span m=\"992400\">coefficient?</span> <span m=\"993420\"\
  >In</span> <span m=\"993510\">which</span> <span m=\"993690\">case,</span> <span\
  \ m=\"993960\">we</span> <span m=\"994110\">restrict</span> <span m=\"994530\">further.</span></p><p><span\
  \ m=\"998400\">And each</span> <span m=\"998620\">time</span> <span m=\"998950\"\
  >you</span> <span m=\"999130\">iterate,</span> <span m=\"999870\">you</span> <span\
  \ m=\"1000090\">obtain</span> <span m=\"1000450\">a</span> <span m=\"1000630\">density</span>\
  \ <span m=\"1001170\">increment.</span> <span m=\"1002970\">And</span> <span m=\"\
  1003090\">the</span> <span m=\"1003180\">density</span> <span m=\"1003660\">increment</span>\
  \ <span m=\"1005730\">cannot</span> <span m=\"1006420\">go</span> <span m=\"1006660\"\
  >on</span> <span m=\"1006810\">forever,</span> <span m=\"1010130\">because</span>\
  \ <span m=\"1010670\">your</span> <span m=\"1010880\">total</span> <span m=\"1011240\"\
  >density</span> <span m=\"1012200\">is</span> <span m=\"1012710\">at</span> <span\
  \ m=\"1012800\">most</span> <span m=\"1013100\">1.</span> <span m=\"1017890\">So\
  \ the</span> <span m=\"1018170\">number</span> <span m=\"1018480\">of</span> <span\
  \ m=\"1018570\">steps</span> <span m=\"1019080\">must</span> <span m=\"1019350\"\
  >be</span> <span m=\"1019470\">bounded.</span> <span m=\"1022590\">So</span> <span\
  \ m=\"1022610\">that's</span> <span m=\"1022820\">the</span> <span m=\"1022910\"\
  >strategy.</span></p><p><span m=\"1024290\">So</span> <span m=\"1024470\">this</span>\
  \ <span m=\"1024560\">should</span> <span m=\"1025099\">remind</span> <span m=\"\
  1025490\">you</span> <span m=\"1025609\">somewhat</span> <span m=\"1026030\">of</span>\
  \ <span m=\"1026150\">the</span> <span m=\"1026329\">energy</span> <span m=\"1026750\"\
  >increment</span> <span m=\"1027140\">strategy</span> <span m=\"1027770\">from</span>\
  \ <span m=\"1028450\">Szemer\xE9di's</span> <span m=\"1029200\">regularity</span>\
  \ <span m=\"1029500\">lemma,</span> <span m=\"1030530\">although</span> <span m=\"\
  1030740\">there</span> <span m=\"1030859\">are</span> <span m=\"1030890\">some</span>\
  \ <span m=\"1031099\">fundamental</span> <span m=\"1031609\">differences.</span>\
  \ <span m=\"1032210\">We're</span> <span m=\"1032329\">not</span> <span m=\"1032510\"\
  >doing</span> <span m=\"1032690\">partitionings.</span> <span m=\"1036730\">Any</span>\
  \ <span m=\"1036910\">questions</span> <span m=\"1037270\">about</span> <span m=\"\
  1037450\">this</span> <span m=\"1037540\">strategy?</span> <span m=\"1041470\">OK.</span></p><p><span\
  \ m=\"1043810\">I</span> <span m=\"1043869\">want</span> <span m=\"1044020\">to</span>\
  \ <span m=\"1044079\">tell</span> <span m=\"1044290\">you</span> <span m=\"1044530\"\
  >about</span> <span m=\"1044790\">Fourier</span> <span m=\"1045089\">analysis.</span>\
  \ <span m=\"1054740\">So</span> <span m=\"1054950\">probably,</span> <span m=\"\
  1056090\">all</span> <span m=\"1056210\">of</span> <span m=\"1056300\">you</span>\
  \ <span m=\"1056420\">have</span> <span m=\"1056510\">seen</span> <span m=\"1056870\"\
  >some</span> <span m=\"1057110\">version</span> <span m=\"1057460\">of</span> <span\
  \ m=\"1057530\">Fourier</span> <span m=\"1057740\">analysis,</span> <span m=\"1058850\"\
  >maybe</span> <span m=\"1059210\">in</span> <span m=\"1059540\">your</span> <span\
  \ m=\"1059660\">calculus</span> <span m=\"1060140\">class</span> <span m=\"1060410\"\
  >with</span> <span m=\"1060530\">Fourier</span> <span m=\"1060830\">series</span>\
  \ <span m=\"1061280\">and</span> <span m=\"1061370\">whatnot.</span> <span m=\"\
  1063140\">So</span> <span m=\"1063320\">you</span> <span m=\"1063410\">play</span>\
  \ <span m=\"1063620\">with</span> <span m=\"1063740\">formulas,</span> <span m=\"\
  1064340\">and</span> <span m=\"1064850\">solve</span> <span m=\"1065120\">some</span>\
  \ <span m=\"1065270\">differential</span> <span m=\"1065690\">equations.</span>\
  \ <span m=\"1066930\">So</span> <span m=\"1066950\">I</span> <span m=\"1067010\"\
  >want</span> <span m=\"1067190\">to</span> <span m=\"1067250\">give</span> <span\
  \ m=\"1067560\">you</span> <span m=\"1068540\">more</span> <span m=\"1068780\">than</span>\
  \ <span m=\"1068990\">just</span> <span m=\"1069350\">a</span> <span m=\"1069410\"\
  >bunch</span> <span m=\"1069830\">of</span> <span m=\"1070220\">ways</span> <span\
  \ m=\"1070580\">about</span> <span m=\"1070880\">handling</span> <span m=\"1071330\"\
  >Fourier</span> <span m=\"1071630\">coefficients,</span> <span m=\"1073110\">a</span>\
  \ <span m=\"1073370\">way</span> <span m=\"1073640\">to</span> <span m=\"1073760\"\
  >think</span> <span m=\"1073970\">about</span> <span m=\"1074480\">Fourier</span>\
  \ <span m=\"1074780\">analysis.</span> <span m=\"1075600\">So</span> <span m=\"\
  1075650\">think</span> <span m=\"1075830\">of</span> <span m=\"1075920\">this</span>\
  \ <span m=\"1076190\">as</span> <span m=\"1076340\">a</span> <span m=\"1076400\"\
  >crash</span> <span m=\"1076820\">course</span> <span m=\"1077660\">about</span>\
  \ <span m=\"1077840\">Fourier</span> <span m=\"1078130\">analysis</span> <span m=\"\
  1078920\">from</span> <span m=\"1079100\">the</span> <span m=\"1079160\">perspective</span>\
  \ <span m=\"1079790\">of</span> <span m=\"1079910\">combinatorics.</span></p><p><span\
  \ m=\"1084080\">And</span> <span m=\"1084380\">Fourier</span> <span m=\"1084670\"\
  >analysis,</span> <span m=\"1085200\">I</span> <span m=\"1085300\">think,</span>\
  \ <span m=\"1085340\">it's</span> <span m=\"1085460\">much</span> <span m=\"1085730\"\
  >easier</span> <span m=\"1086330\">if</span> <span m=\"1086450\">you</span> <span\
  \ m=\"1086570\">work</span> <span m=\"1086780\">in</span> <span m=\"1086950\">a</span>\
  \ <span m=\"1086990\">finite</span> <span m=\"1087560\">group,</span> <span m=\"\
  1088160\">in a</span> <span m=\"1088340\">finite</span> <span m=\"1088670\">abelian</span>\
  \ <span m=\"1089060\">group,</span> <span m=\"1089520\">which</span> <span m=\"\
  1089570\">is</span> <span m=\"1089690\">what</span> <span m=\"1089810\">we're</span>\
  \ <span m=\"1089930\">doing</span> <span m=\"1090170\">here.</span> <span m=\"1091880\"\
  >Many</span> <span m=\"1092150\">of</span> <span m=\"1092210\">the</span> <span\
  \ m=\"1092270\">technicalities</span> <span m=\"1093020\">go</span> <span m=\"1093200\"\
  >away.</span> <span m=\"1093690\">So</span> <span m=\"1093860\">we'll</span> <span\
  \ m=\"1094040\">be</span> <span m=\"1094220\">looking</span> <span m=\"1094580\"\
  >specifically</span> <span m=\"1095240\">at</span> <span m=\"1095560\">Fourier</span>\
  \ <span m=\"1095900\">analysis</span> <span m=\"1096890\">in</span> <span m=\"1097250\"\
  >F3</span> <span m=\"1097960\">to</span> <span m=\"1098090\">the</span> <span m=\"\
  1098220\">n-th,</span> <span m=\"1098930\">although</span> <span m=\"1099380\">the</span>\
  \ <span m=\"1099470\">3</span> <span m=\"1099980\">can</span> <span m=\"1100160\"\
  >be</span> <span m=\"1100960\">any</span> <span m=\"1101150\">prime.</span> <span\
  \ m=\"1101840\">So</span> <span m=\"1102110\">it's</span> <span m=\"1102560\">really</span>\
  \ <span m=\"1102740\">the</span> <span m=\"1102830\">same.</span></p><p><span m=\"\
  1104270\">So</span> <span m=\"1106550\">the</span> <span m=\"1108050\">main</span>\
  \ <span m=\"1108360\">actors</span> <span m=\"1108625\">in</span> <span m=\"1108890\"\
  >Fourier</span> <span m=\"1109100\">analysis</span> <span m=\"1109700\">are</span>\
  \ <span m=\"1109820\">the</span> <span m=\"1109910\">Fourier</span> <span m=\"1110240\"\
  >characters.</span> <span m=\"1115370\">The</span> <span m=\"1115670\">Fourier</span>\
  \ <span m=\"1115790\">characters</span> <span m=\"1116930\">are</span> <span m=\"\
  1117110\">denoted</span> <span m=\"1117680\">gamma</span> <span m=\"1118340\">sub</span>\
  \ <span m=\"1118820\">r.</span> <span m=\"1119840\">And</span> <span m=\"1120530\"\
  >they're</span> <span m=\"1121070\">characters</span> <span m=\"1121640\">on</span>\
  \ <span m=\"1121740\">the</span> <span m=\"1121820\">group,</span> <span m=\"1122420\"\
  >meaning</span> <span m=\"1122720\">that</span> <span m=\"1123340\">they are</span>\
  \ <span m=\"1123620\">maps</span> <span m=\"1124430\">which--</span> <span m=\"\
  1125030\">so</span> <span m=\"1125130\">they</span> <span m=\"1125400\">turn</span>\
  \ <span m=\"1125680\">out,</span> <span m=\"1125840\">happen</span> <span m=\"1126200\"\
  >to</span> <span m=\"1126260\">be</span> <span m=\"1126500\">homomorphisms</span>\
  \ <span m=\"1127640\">for</span> <span m=\"1127760\">the</span> <span m=\"1127850\"\
  >multiplicative</span> <span m=\"1128480\">group</span> <span m=\"1129670\">under--</span>\
  \ <span m=\"1130520\">so</span> <span m=\"1130880\">C</span> <span m=\"1131270\"\
  >under</span> <span m=\"1131510\">multiplication.</span> <span m=\"1133760\">And</span>\
  \ <span m=\"1133970\">they're</span> <span m=\"1134150\">indexed</span> <span m=\"\
  1136610\">by</span> <span m=\"1140420\">r,</span> <span m=\"1141050\">which</span>\
  \ <span m=\"1141710\">also</span> <span m=\"1142040\">elements</span> <span m=\"\
  1142400\">of</span> <span m=\"1142520\">F3</span> <span m=\"1142850\">to</span>\
  \ <span m=\"1142940\">the</span> <span m=\"1143060\">n-th.</span></p><p><span m=\"\
  1143510\">So</span> <span m=\"1144290\">I'm</span> <span m=\"1144410\">going</span>\
  \ <span m=\"1144510\">to</span> <span m=\"1144590\">be</span> <span m=\"1144680\"\
  >fairly</span> <span m=\"1145010\">concrete</span> <span m=\"1145460\">here.</span>\
  \ <span m=\"1145670\">There</span> <span m=\"1145790\">are</span> <span m=\"1145820\"\
  >ways</span> <span m=\"1146060\">to</span> <span m=\"1146150\">do</span> <span m=\"\
  1146240\">this</span> <span m=\"1146420\">more</span> <span m=\"1146660\">abstractly.</span>\
  \ <span m=\"1147520\">But</span> <span m=\"1147680\">I'll</span> <span m=\"1147770\"\
  >be</span> <span m=\"1147890\">fairly</span> <span m=\"1148160\">concrete.</span>\
  \ <span m=\"1148880\">So</span> <span m=\"1149540\">it's</span> <span m=\"1149720\"\
  >defined</span> <span m=\"1150110\">by</span> <span m=\"1150320\">gamma</span> <span\
  \ m=\"1150770\">sub</span> <span m=\"1151010\">r</span> <span m=\"1152000\">evaluated</span>\
  \ <span m=\"1152670\">on</span> <span m=\"1152990\">x</span> <span m=\"1154250\"\
  >equals</span> <span m=\"1154610\">to</span> <span m=\"1154880\">omega</span> <span\
  \ m=\"1155450\">raised</span> <span m=\"1155750\">to</span> <span m=\"1156590\"\
  >r</span> <span m=\"1157270\">dot</span> <span m=\"1157540\">product</span> <span\
  \ m=\"1158270\">x,</span> <span m=\"1159140\">where</span> <span m=\"1159470\">here</span>\
  \ <span m=\"1159800\">omega</span> <span m=\"1160640\">is</span> <span m=\"1160850\"\
  >a</span> <span m=\"1161060\">third</span> <span m=\"1161510\">root</span> <span\
  \ m=\"1161780\">of</span> <span m=\"1161900\">unity</span> <span m=\"1164450\">and</span>\
  \ <span m=\"1166590\">the</span> <span m=\"1166740\">dot</span> <span m=\"1167220\"\
  >is</span> <span m=\"1167400\">a</span> <span m=\"1167440\">dot</span> <span m=\"\
  1167640\">product.</span> <span m=\"1173230\">So--</span></p><p><span m=\"1182660\"\
  >So</span> <span m=\"1182780\">that's</span> <span m=\"1182960\">the</span> <span\
  \ m=\"1183020\">definition</span> <span m=\"1183500\">of</span> <span m=\"1183590\"\
  >the</span> <span m=\"1183780\">Fourier</span> <span m=\"1183950\">transform--</span>\
  \ <span m=\"1185090\">sorry,</span> <span m=\"1185210\">that's</span> <span m=\"\
  1185390\">the</span> <span m=\"1185810\">definition of the</span> <span m=\"1186260\"\
  >Fourier</span> <span m=\"1186560\">characters.</span> <span m=\"1187400\">And</span>\
  \ <span m=\"1187490\">once</span> <span m=\"1187700\">you</span> <span m=\"1187760\"\
  >have the</span> <span m=\"1187900\">Fourier</span> <span m=\"1188210\">characters,</span>\
  \ <span m=\"1189140\">you</span> <span m=\"1189260\">can</span> <span m=\"1189440\"\
  >have</span> <span m=\"1190970\">this</span> <span m=\"1191180\">Fourier</span>\
  \ <span m=\"1191570\">transform,</span> <span m=\"1196290\">just</span> <span m=\"\
  1196500\">defined</span> <span m=\"1196830\">as</span> <span m=\"1196950\">follows.</span>\
  \ <span m=\"1198010\">If</span> <span m=\"1198030\">you</span> <span m=\"1198150\"\
  >start</span> <span m=\"1198720\">with</span> <span m=\"1199020\">a</span> <span\
  \ m=\"1199140\">function--</span> <span m=\"1203814\">let's say,</span> <span m=\"\
  1204280\">a</span> <span m=\"1204420\">complex-valued</span> <span m=\"1205140\"\
  >function</span> <span m=\"1205620\">on</span> <span m=\"1206070\">your</span> <span\
  \ m=\"1206550\">space--</span> <span m=\"1207540\">then</span> <span m=\"1207900\"\
  >I</span> <span m=\"1208030\">define</span> <span m=\"1208440\">the</span> <span\
  \ m=\"1208530\">Fourier</span> <span m=\"1208860\">transform</span> <span m=\"1213550\"\
  >to</span> <span m=\"1213640\">be</span> <span m=\"1217120\">another</span> <span\
  \ m=\"1217390\">function,</span> <span m=\"1217960\">like</span> <span m=\"1218110\"\
  >that,</span> <span m=\"1219600\">defined</span> <span m=\"1220080\">by</span> <span\
  \ m=\"1221010\">the</span> <span m=\"1221160\">following</span> <span m=\"1221790\"\
  >formula.</span></p><p><span m=\"1234240\">So</span> <span m=\"1234360\">that's</span>\
  \ <span m=\"1234570\">the</span> <span m=\"1234630\">formula</span> <span m=\"1235050\"\
  >for</span> <span m=\"1235620\">the</span> <span m=\"1235920\">Fourier</span> <span\
  \ m=\"1236310\">transform.</span> <span m=\"1240770\">It</span> <span m=\"1240920\"\
  >is</span> <span m=\"1241850\">basically</span> <span m=\"1242600\">the</span> <span\
  \ m=\"1243440\">inner</span> <span m=\"1243650\">product</span> <span m=\"1244220\"\
  >between</span> <span m=\"1245000\">F</span> <span m=\"1245780\">and</span> <span\
  \ m=\"1245900\">the</span> <span m=\"1245990\">Fourier</span> <span m=\"1246260\"\
  >character.</span> <span m=\"1247520\">So</span> <span m=\"1247610\">let</span>\
  \ <span m=\"1247730\">me</span> <span m=\"1248240\">make</span> <span m=\"1248495\"\
  >the</span> <span m=\"1248750\">comment</span> <span m=\"1249200\">here,</span>\
  \ <span m=\"1250190\">I</span> <span m=\"1250220\">think</span> <span m=\"1250400\"\
  >this</span> <span m=\"1250550\">is</span> <span m=\"1250670\">actually</span> <span\
  \ m=\"1250970\">a</span> <span m=\"1251060\">pretty</span> <span m=\"1251390\">important</span>\
  \ <span m=\"1251780\">comment,</span> <span m=\"1252440\">about</span> <span m=\"\
  1252680\">the</span> <span m=\"1252740\">normalization.</span></p><p><span m=\"\
  1258350\">Now,</span> <span m=\"1258680\">when</span> <span m=\"1258860\">you</span>\
  \ <span m=\"1258950\">first</span> <span m=\"1259730\">learn</span> <span m=\"1260090\"\
  >Fourier</span> <span m=\"1260450\">transforms,</span> <span m=\"1262370\">usually</span>\
  \ <span m=\"1263390\">in</span> <span m=\"1263660\">the</span> <span m=\"1263780\"\
  >reals,</span> <span m=\"1265930\">there</span> <span m=\"1266090\">are</span> <span\
  \ m=\"1266150\">all</span> <span m=\"1266300\">these</span> <span m=\"1266510\"\
  >questions</span> <span m=\"1266930\">about</span> <span m=\"1267110\">what</span>\
  \ <span m=\"1267350\">number</span> <span m=\"1267650\">to</span> <span m=\"1267770\"\
  >put</span> <span m=\"1268010\">in</span> <span m=\"1268100\">the</span> <span m=\"\
  1268190\">exponent.</span> <span m=\"1268730\">Is it</span> <span m=\"1268940\"\
  >2</span> <span m=\"1269180\">pi?</span> <span m=\"1269660\">Is</span> <span m=\"\
  1269840\">it</span> <span m=\"1269930\">root</span> <span m=\"1270120\">2</span>\
  \ <span m=\"1270290\">pi?</span> <span m=\"1270690\">Is</span> <span m=\"1270800\"\
  >it</span> <span m=\"1270890\">some</span> <span m=\"1271070\">other</span> <span\
  \ m=\"1271280\">thing?</span> <span m=\"1272000\">And</span> <span m=\"1275220\"\
  >somehow,</span> <span m=\"1275580\">one</span> <span m=\"1275820\">answer</span>\
  \ <span m=\"1276060\">is</span> <span m=\"1276180\">better</span> <span m=\"1276390\"\
  >than</span> <span m=\"1276510\">the</span> <span m=\"1276630\">others.</span> <span\
  \ m=\"1277770\">And</span> <span m=\"1277890\">the</span> <span m=\"1277980\">same</span>\
  \ <span m=\"1278220\">thing</span> <span m=\"1278400\">is</span> <span m=\"1278520\"\
  >true</span> <span m=\"1278730\">here</span> <span m=\"1279060\">in</span> <span\
  \ m=\"1279240\">groups.</span></p><p><span m=\"1279960\">So</span> <span m=\"1280140\"\
  >we'll</span> <span m=\"1280320\">stick</span> <span m=\"1280680\">with</span> <span\
  \ m=\"1280810\">the</span> <span m=\"1280890\">following</span> <span m=\"1281280\"\
  >convention--</span> <span m=\"1281790\">and</span> <span m=\"1281910\">I</span>\
  \ <span m=\"1281970\">want</span> <span m=\"1282360\">all</span> <span m=\"1282480\"\
  >of</span> <span m=\"1282600\">you</span> <span m=\"1282660\">to</span> <span m=\"\
  1282750\">stick</span> <span m=\"1283050\">with</span> <span m=\"1283170\">this</span>\
  \ <span m=\"1283320\">convention,</span> <span m=\"1283710\">otherwise,</span> <span\
  \ m=\"1284130\">we'll</span> <span m=\"1284280\">confuse</span> <span m=\"1284700\"\
  >ourselves</span> <span m=\"1285060\">to</span> <span m=\"1285150\">no</span> <span\
  \ m=\"1285330\">end--</span> <span m=\"1286320\">is</span> <span m=\"1286470\">that</span>\
  \ <span m=\"1286680\">for</span> <span m=\"1286980\">a</span> <span m=\"1287040\"\
  >finite</span> <span m=\"1287430\">group--</span> <span m=\"1294940\">actually,</span>\
  \ <span m=\"1295430\">let</span> <span m=\"1295550\">me,</span> <span m=\"1295970\"\
  >start</span> <span m=\"1296260\">of</span> <span m=\"1296330\">a board.</span>\
  \ <span m=\"1296930\">So</span> <span m=\"1297110\">the</span> <span m=\"1297200\"\
  >convention</span> <span m=\"1300740\">is</span> <span m=\"1300890\">that,</span>\
  \ <span m=\"1301150\">in</span> <span m=\"1301280\">a</span> <span m=\"1301340\"\
  >finite</span> <span m=\"1301700\">group,</span> <span m=\"1303788\">the</span>\
  \ <span m=\"1304250\">Fourier</span> <span m=\"1304730\">transform</span> <span\
  \ m=\"1305590\">is</span> <span m=\"1305720\">defined--</span> <span m=\"1306310\"\
  >and</span> <span m=\"1306410\">more</span> <span m=\"1306560\">generally,</span>\
  \ <span m=\"1306980\">anything</span> <span m=\"1307370\">you</span> <span m=\"\
  1307460\">do</span> <span m=\"1308150\">in</span> <span m=\"1308270\">the</span>\
  \ <span m=\"1308360\">physical</span> <span m=\"1308810\">space,</span> <span m=\"\
  1309650\">we</span> <span m=\"1309890\">always</span> <span m=\"1314550\">use</span>\
  \ <span m=\"1315270\">the</span> <span m=\"1315390\">averaging</span> <span m=\"\
  1315960\">measure.</span> <span m=\"1319590\">Don't</span> <span m=\"1319780\">sum,</span>\
  \ <span m=\"1320140\">always</span> <span m=\"1320440\">average</span> <span m=\"\
  1321070\">in</span> <span m=\"1321160\">the</span> <span m=\"1321220\">physical</span>\
  \ <span m=\"1321640\">space.</span> <span m=\"1322660\">And</span> <span m=\"1322930\"\
  >in</span> <span m=\"1323050\">the</span> <span m=\"1323110\">frequency</span> <span\
  \ m=\"1323650\">space,</span> <span m=\"1327220\">always</span> <span m=\"1327580\"\
  >use</span> <span m=\"1327980\">sums,</span> <span m=\"1330040\">use</span> <span\
  \ m=\"1330220\">the</span> <span m=\"1330280\">counting</span> <span m=\"1330660\"\
  >measure.</span></p><p><span m=\"1332860\">Keep</span> <span m=\"1333100\">this</span>\
  \ <span m=\"1333280\">in</span> <span m=\"1333340\">mind.</span> <span m=\"1334630\"\
  >Any</span> <span m=\"1334810\">of</span> <span m=\"1334870\">these</span> <span\
  \ m=\"1335020\">questions</span> <span m=\"1335350\">about</span> <span m=\"1335500\"\
  >normalization,</span> <span m=\"1336250\">if</span> <span m=\"1336340\">you</span>\
  \ <span m=\"1336430\">stick</span> <span m=\"1336730\">with</span> <span m=\"1336850\"\
  >this</span> <span m=\"1337000\">convention,</span> <span m=\"1337480\">things</span>\
  \ <span m=\"1337690\">will</span> <span m=\"1337780\">become</span> <span m=\"1338080\"\
  >much</span> <span m=\"1338290\">easier.</span> <span m=\"1339590\">So</span> <span\
  \ m=\"1339790\">there</span> <span m=\"1339930\">won't</span> <span m=\"1340110\"\
  >be</span> <span m=\"1340590\">any</span> <span m=\"1340770\">of</span> <span m=\"\
  1340830\">these</span> <span m=\"1341010\">questions</span> <span m=\"1341340\"\
  >about</span> <span m=\"1341520\">when</span> <span m=\"1341670\">you</span> <span\
  \ m=\"1341760\">take</span> <span m=\"1341970\">the</span> <span m=\"1342090\">inverse</span>\
  \ <span m=\"1342480\">Fourier</span> <span m=\"1342750\">transform,</span> <span\
  \ m=\"1343390\">do</span> <span m=\"1343490\">I</span> <span m=\"1343590\">put</span>\
  \ <span m=\"1343650\">an</span> <span m=\"1343740\">extra</span> <span m=\"1344040\"\
  >factor</span> <span m=\"1344400\">in</span> <span m=\"1344970\">front</span> <span\
  \ m=\"1345270\">or</span> <span m=\"1345360\">not,</span> <span m=\"1345750\">if</span>\
  \ <span m=\"1345870\">you</span> <span m=\"1345960\">stick</span> <span m=\"1346260\"\
  >with</span> <span m=\"1346380\">this</span> <span m=\"1346530\">correct</span>\
  \ <span m=\"1346800\">convention.</span> <span m=\"1350520\">So</span> <span m=\"\
  1351210\">with</span> <span m=\"1351390\">that</span> <span m=\"1351510\">convention</span>\
  \ <span m=\"1351970\">in mind,</span> <span m=\"1352940\">what</span> <span m=\"\
  1353210\">the</span> <span m=\"1353280\">Fourier</span> <span m=\"1353580\">transform</span>\
  \ <span m=\"1354120\">really</span> <span m=\"1354560\">is</span> <span m=\"1355760\"\
  >is</span> <span m=\"1356500\">inner</span> <span m=\"1356730\">product</span> <span\
  \ m=\"1357360\">between</span> <span m=\"1357990\">F</span> <span m=\"1358920\"\
  >and</span> <span m=\"1359970\">a</span> <span m=\"1360060\">Fourier</span> <span\
  \ m=\"1360510\">character.</span></p><p><span m=\"1369810\">There</span> <span m=\"\
  1369960\">are</span> <span m=\"1369990\">some</span> <span m=\"1370770\">important</span>\
  \ <span m=\"1371190\">properties</span> <span m=\"1371670\">of</span> <span m=\"\
  1371730\">the</span> <span m=\"1371820\">Fourier</span> <span m=\"1372110\">transform.</span>\
  \ <span m=\"1372760\">So</span> <span m=\"1372780\">let</span> <span m=\"1372870\"\
  >me</span> <span m=\"1372990\">go</span> <span m=\"1373140\">through</span> <span\
  \ m=\"1373290\">a</span> <span m=\"1373350\">few</span> <span m=\"1373560\">of</span>\
  \ <span m=\"1373620\">the</span> <span m=\"1373710\">key</span> <span m=\"1373890\"\
  >properties</span> <span m=\"1374550\">that</span> <span m=\"1375110\">we'll</span>\
  \ <span m=\"1375270\">need.</span> <span m=\"1384940\">The</span> <span m=\"1385040\"\
  >first</span> <span m=\"1385170\">one</span> <span m=\"1385350\">is</span> <span\
  \ m=\"1385500\">pretty</span> <span m=\"1385710\">easy.</span> <span m=\"1387970\"\
  >What</span> <span m=\"1388050\">is</span> <span m=\"1388230\">the</span> <span\
  \ m=\"1388320\">meaning</span> <span m=\"1389010\">of</span> <span m=\"1390330\"\
  >the</span> <span m=\"1390700\">0-th</span> <span m=\"1391380\">Fourier</span> <span\
  \ m=\"1391740\">coefficient?</span> <span m=\"1394250\">You</span> <span m=\"1394340\"\
  >plug</span> <span m=\"1394580\">it</span> <span m=\"1394670\">in,</span> <span\
  \ m=\"1395410\">and</span> <span m=\"1395840\">you</span> <span m=\"1395940\">see</span>\
  \ <span m=\"1396110\">that</span> <span m=\"1396470\">it</span> <span m=\"1396620\"\
  >is</span> <span m=\"1396740\">just</span> <span m=\"1396950\">the</span> <span\
  \ m=\"1397040\">average</span> <span m=\"1397670\">of</span> <span m=\"1397850\"\
  >F.</span> <span m=\"1404020\">So</span> <span m=\"1404320\">0-th</span> <span m=\"\
  1404650\">coefficient</span> <span m=\"1405130\">is</span> <span m=\"1405250\">the</span>\
  \ <span m=\"1405370\">average</span> <span m=\"1405700\">of</span> <span m=\"1405860\"\
  >F.</span></p><p><span m=\"1407800\">The</span> <span m=\"1407920\">second</span>\
  \ <span m=\"1408910\">fact</span> <span m=\"1410350\">goes</span> <span m=\"1410710\"\
  >under</span> <span m=\"1410920\">one</span> <span m=\"1411160\">of</span> <span\
  \ m=\"1411280\">two names,</span> <span m=\"1412270\">and</span> <span m=\"1412510\"\
  >they're</span> <span m=\"1412720\">often</span> <span m=\"1413050\">used</span>\
  \ <span m=\"1413230\">interchangeably--</span> <span m=\"1414870\">Plancherel</span>\
  \ <span m=\"1415680\">or</span> <span m=\"1415840\">Parseval.</span> <span m=\"\
  1421340\">And</span> <span m=\"1421480\">it</span> <span m=\"1421550\">says</span>\
  \ <span m=\"1422350\">that</span> <span m=\"1423100\">if</span> <span m=\"1423340\"\
  >you</span> <span m=\"1425380\">look</span> <span m=\"1425620\">at</span> <span\
  \ m=\"1426370\">the</span> <span m=\"1426550\">inner</span> <span m=\"1426760\"\
  >product</span> <span m=\"1428560\">in</span> <span m=\"1428680\">the</span> <span\
  \ m=\"1428740\">physical</span> <span m=\"1429160\">space,</span> <span m=\"1434500\"\
  >then</span> <span m=\"1434710\">this</span> <span m=\"1435070\">product</span>\
  \ <span m=\"1437080\">is</span> <span m=\"1438250\">preserved,</span> <span m=\"\
  1439700\">if</span> <span m=\"1439750\">you</span> <span m=\"1439990\">take</span>\
  \ <span m=\"1440740\">the</span> <span m=\"1441040\">Fourier</span> <span m=\"1441190\"\
  >transform.</span> <span m=\"1445870\">But now,</span> <span m=\"1446230\">of</span>\
  \ <span m=\"1446320\">course,</span> <span m=\"1446510\">you're</span> <span m=\"\
  1446670\">in</span> <span m=\"1446770\">the</span> <span m=\"1446830\">frequency</span>\
  \ <span m=\"1447310\">space,</span> <span m=\"1447700\">so</span> <span m=\"1447850\"\
  >you</span> <span m=\"1447940\">should</span> <span m=\"1448070\">sum</span> <span\
  \ m=\"1448570\">instead</span> <span m=\"1448930\">of</span> <span m=\"1449080\"\
  >doing</span> <span m=\"1449380\">the</span> <span m=\"1449560\">inner</span> <span\
  \ m=\"1449710\">product.</span></p><p><span m=\"1455180\">So</span> <span m=\"1456110\"\
  >this</span> <span m=\"1457020\">identity</span> <span m=\"1457910\">can</span>\
  \ <span m=\"1458090\">be</span> <span m=\"1458470\">proved</span> <span m=\"1458810\"\
  >in</span> <span m=\"1458960\">a</span> <span m=\"1459020\">fairly</span> <span\
  \ m=\"1459320\">straightforward</span> <span m=\"1459890\">way</span> <span m=\"\
  1460490\">by</span> <span m=\"1460790\">plugging</span> <span m=\"1461450\">in</span>\
  \ <span m=\"1462780\">what</span> <span m=\"1462950\">the</span> <span m=\"1462990\"\
  >definition</span> <span m=\"1463530\">is</span> <span m=\"1463860\">for</span>\
  \ <span m=\"1464010\">the</span> <span m=\"1464200\">Fourier</span> <span m=\"1464360\"\
  >transform.</span> <span m=\"1465700\">This</span> <span m=\"1465810\">is</span>\
  \ <span m=\"1465900\">a</span> <span m=\"1465960\">straightforward</span> <span\
  \ m=\"1466410\">computation</span> <span m=\"1466960\">I'm</span> <span m=\"1467040\"\
  >not</span> <span m=\"1467190\">going</span> <span m=\"1467310\">to</span> <span\
  \ m=\"1467370\">do</span> <span m=\"1467450\">on</span> <span m=\"1467550\">the</span>\
  \ <span m=\"1467610\">board,</span> <span m=\"1467850\">but</span> <span m=\"1468000\"\
  >I</span> <span m=\"1468060\">highly</span> <span m=\"1468330\">encourage you</span>\
  \ <span m=\"1468780\">to</span> <span m=\"1468930\">actually</span> <span m=\"1469170\"\
  >do</span> <span m=\"1469320\">at</span> <span m=\"1469440\">home,</span> <span\
  \ m=\"1469970\">just</span> <span m=\"1470160\">to</span> <span m=\"1470310\">do</span>\
  \ <span m=\"1470490\">it</span> <span m=\"1470550\">once</span> <span m=\"1471120\"\
  >to</span> <span m=\"1471240\">make</span> <span m=\"1471390\">sure</span> <span\
  \ m=\"1471570\">you</span> <span m=\"1471690\">understand</span> <span m=\"1472080\"\
  >how</span> <span m=\"1472290\">it</span> <span m=\"1472380\">goes.</span></p><p><span\
  \ m=\"1473760\">But</span> <span m=\"1473810\">there</span> <span m=\"1473920\"\
  >is</span> <span m=\"1474050\">also</span> <span m=\"1474260\">a</span> <span m=\"\
  1474290\">more</span> <span m=\"1474500\">conceptual</span> <span m=\"1475100\"\
  >way</span> <span m=\"1475310\">to</span> <span m=\"1475490\">understand</span>\
  \ <span m=\"1475940\">this</span> <span m=\"1476120\">identity.</span> <span m=\"\
  1478410\">And</span> <span m=\"1478430\">that's</span> <span m=\"1478640\">because--</span>\
  \ <span m=\"1480020\">now,</span> <span m=\"1480380\">this</span> <span m=\"1480590\"\
  >is</span> <span m=\"1480680\">also</span> <span m=\"1481490\">important</span>\
  \ <span m=\"1481880\">to</span> <span m=\"1482630\">understand</span> <span m=\"\
  1483380\">what</span> <span m=\"1483540\">the</span> <span m=\"1483590\">Fourier</span>\
  \ <span m=\"1483950\">transform</span> <span m=\"1484430\">is.</span> <span m=\"\
  1484670\">It's</span> <span m=\"1484820\">not</span> <span m=\"1485030\">just</span>\
  \ <span m=\"1485180\">some</span> <span m=\"1485360\">magical</span> <span m=\"\
  1485810\">formula</span> <span m=\"1486210\">somebody</span> <span m=\"1486560\"\
  >wrote</span> <span m=\"1486740\">down,</span> <span m=\"1486980\">like</span> <span\
  \ m=\"1487160\">this</span> <span m=\"1487870\">is</span> <span m=\"1488000\">a</span>\
  \ <span m=\"1488030\">very</span> <span m=\"1488270\">natural</span> <span m=\"\
  1488750\">operation.</span> <span m=\"1490080\">It's</span> <span m=\"1490280\"\
  >because</span> <span m=\"1490820\">the</span> <span m=\"1492110\">characters,</span>\
  \ <span m=\"1494890\">the</span> <span m=\"1495050\">set</span> <span m=\"1495260\"\
  >of</span> <span m=\"1495350\">characters,</span> <span m=\"1499280\">is</span>\
  \ <span m=\"1500600\">an</span> <span m=\"1500780\">orthonormal</span> <span m=\"\
  1501410\">basis.</span> <span m=\"1502620\">So</span> <span m=\"1502700\">the</span>\
  \ <span m=\"1504820\">Fourier</span> <span m=\"1505370\">characters</span> <span\
  \ m=\"1506780\">form</span> <span m=\"1509690\">an</span> <span m=\"1510050\">orthonormal</span>\
  \ <span m=\"1510560\">basis.</span></p><p><span m=\"1515750\">As</span> <span m=\"\
  1515900\">a</span> <span m=\"1515960\">result,</span> <span m=\"1516920\">what</span>\
  \ <span m=\"1517280\">the</span> <span m=\"1517460\">Fourier</span> <span m=\"1517820\"\
  >transform</span> <span m=\"1518420\">is</span> <span m=\"1519380\">is</span> <span\
  \ m=\"1520100\">a</span> <span m=\"1520820\">unitary</span> <span m=\"1521420\"\
  >change</span> <span m=\"1521780\">of</span> <span m=\"1521870\">basis.</span> <span\
  \ m=\"1535510\">You</span> <span m=\"1535600\">can</span> <span m=\"1535750\">check.</span>\
  \ <span m=\"1536320\">It's</span> <span m=\"1536410\">very</span> <span m=\"1536620\"\
  >straightforward</span> <span m=\"1537070\">to</span> <span m=\"1537130\">check</span>\
  \ <span m=\"1537400\">that</span> <span m=\"1538090\">the</span> <span m=\"1538540\"\
  >Fourier</span> <span m=\"1538900\">characters,</span> <span m=\"1539350\">indeed,</span>\
  \ <span m=\"1539650\">form a</span> <span m=\"1539950\">orthonormal</span> <span\
  \ m=\"1540460\">basis,</span> <span m=\"1543360\">because--</span> <span m=\"1545210\"\
  >well,</span> <span m=\"1545550\">you</span> <span m=\"1545640\">can</span> <span\
  \ m=\"1546060\">evaluate</span> <span m=\"1546960\">the</span> <span m=\"1547830\"\
  >inner</span> <span m=\"1548010\">product</span> <span m=\"1548730\">between</span>\
  \ <span m=\"1551140\">two</span> <span m=\"1551350\">Fourier</span> <span m=\"1551650\"\
  >characters.</span> <span m=\"1553480\">So</span> <span m=\"1553690\">remember,</span>\
  \ <span m=\"1554500\">in</span> <span m=\"1554650\">the</span> <span m=\"1555010\"\
  >physical</span> <span m=\"1555430\">space,</span> <span m=\"1555730\">we're</span>\
  \ <span m=\"1555880\">always</span> <span m=\"1556240\">doing</span> <span m=\"\
  1556810\">averaging.</span></p><p><span m=\"1561050\">And</span> <span m=\"1561800\"\
  >so</span> <span m=\"1561950\">now,</span> <span m=\"1564855\">I'll</span> <span\
  \ m=\"1565160\">just</span> <span m=\"1565370\">write</span> <span m=\"1565580\"\
  >down</span> <span m=\"1565790\">first</span> <span m=\"1566240\">what</span> <span\
  \ m=\"1567170\">I</span> <span m=\"1567260\">mean</span> <span m=\"1567470\">by</span>\
  \ <span m=\"1567620\">the</span> <span m=\"1567710\">inner</span> <span m=\"1567920\"\
  >product.</span> <span m=\"1571100\">So</span> <span m=\"1571250\">that's</span>\
  \ <span m=\"1571440\">the</span> <span m=\"1571550\">inner</span> <span m=\"1571630\"\
  >product.</span> <span m=\"1572920\">And</span> <span m=\"1574380\">by</span> <span\
  \ m=\"1574690\">the</span> <span m=\"1574780\">definition</span> <span m=\"1575230\"\
  >of</span> <span m=\"1575290\">the</span> <span m=\"1575390\">Fourier</span> <span\
  \ m=\"1575680\">character,</span> <span m=\"1582090\">you</span> <span m=\"1582210\"\
  >have</span> <span m=\"1582360\">that.</span> <span m=\"1585410\">So</span> <span\
  \ m=\"1586010\">think</span> <span m=\"1586190\">about</span> <span m=\"1586340\"\
  >what</span> <span m=\"1586460\">this</span> <span m=\"1586610\">expectation</span>\
  \ <span m=\"1587210\">is--</span> <span m=\"1589010\">unless</span> <span m=\"1592310\"\
  >r</span> <span m=\"1592650\">equals</span> <span m=\"1593030\">to</span> <span\
  \ m=\"1593150\">s,</span> <span m=\"1593930\">in</span> <span m=\"1594050\">which</span>\
  \ <span m=\"1594230\">case,</span> <span m=\"1594500\">this</span> <span m=\"1595340\"\
  >expectation</span> <span m=\"1595970\">is</span> <span m=\"1596170\">1.</span>\
  \ <span m=\"1597470\">Unless</span> <span m=\"1597770\">that</span> <span m=\"1597920\"\
  >is</span> <span m=\"1598070\">the</span> <span m=\"1598160\">case,</span> <span\
  \ m=\"1598730\">you</span> <span m=\"1598880\">always</span> <span m=\"1599240\"\
  >have</span> <span m=\"1599660\">some</span> <span m=\"1601070\">coordinate</span>\
  \ <span m=\"1601550\">of</span> <span m=\"1601640\">x</span> <span m=\"1602270\"\
  >in</span> <span m=\"1602390\">the</span> <span m=\"1602480\">exponent.</span> <span\
  \ m=\"1603360\">So</span> <span m=\"1603440\">as</span> <span m=\"1603560\">you</span>\
  \ <span m=\"1603770\">average</span> <span m=\"1604250\">over</span> <span m=\"\
  1604510\">all</span> <span m=\"1604670\">possibilities,</span> <span m=\"1606230\"\
  >they</span> <span m=\"1606350\">average</span> <span m=\"1606680\">out</span> <span\
  \ m=\"1606790\">to</span> <span m=\"1606900\">0.</span></p><p><span m=\"1618020\"\
  >So</span> <span m=\"1618770\">this</span> <span m=\"1618980\">calculation</span>\
  \ <span m=\"1619520\">shows</span> <span m=\"1619820\">you</span> <span m=\"1619940\"\
  >that</span> <span m=\"1620270\">the</span> <span m=\"1620480\">Fourier</span> <span\
  \ m=\"1620600\">characters</span> <span m=\"1621050\">form</span> <span m=\"1621300\"\
  >a</span> <span m=\"1621420\">orthonormal</span> <span m=\"1622010\">basis.</span>\
  \ <span m=\"1622880\">And</span> <span m=\"1623030\">a</span> <span m=\"1623090\"\
  >basic</span> <span m=\"1623480\">fact</span> <span m=\"1623780\">you</span> <span\
  \ m=\"1623900\">know</span> <span m=\"1624230\">from</span> <span m=\"1624890\"\
  >linear</span> <span m=\"1625130\">algebra</span> <span m=\"1625910\">is</span>\
  \ <span m=\"1626060\">that</span> <span m=\"1626180\">if</span> <span m=\"1626300\"\
  >you</span> <span m=\"1626360\">do</span> <span m=\"1626510\">a</span> <span m=\"\
  1626570\">change</span> <span m=\"1626930\">of</span> <span m=\"1627020\">basis,</span>\
  \ <span m=\"1627470\">if</span> <span m=\"1627560\">you</span> <span m=\"1627620\"\
  >do</span> <span m=\"1627740\">a</span> <span m=\"1627890\">unitary</span> <span\
  \ m=\"1628370\">change</span> <span m=\"1628640\">of</span> <span m=\"1628730\"\
  >basis,</span> <span m=\"1630510\">then</span> <span m=\"1631590\">inner</span>\
  \ <span m=\"1631680\">product</span> <span m=\"1632040\">is</span> <span m=\"1632160\"\
  >preserved.</span> <span m=\"1633640\">It's</span> <span m=\"1633750\">like</span>\
  \ <span m=\"1633930\">a</span> <span m=\"1633990\">rotation.</span> <span m=\"1635430\"\
  >It's</span> <span m=\"1635520\">the</span> <span m=\"1635580\">same--</span> <span\
  \ m=\"1636330\">so</span> <span m=\"1636540\">you're</span> <span m=\"1636900\"\
  >not</span> <span m=\"1637080\">changing</span> <span m=\"1637480\">the</span> <span\
  \ m=\"1637560\">inner</span> <span m=\"1637770\">product.</span> <span m=\"1638150\"\
  >So the</span> <span m=\"1638260\">inner</span> <span m=\"1638430\">product</span>\
  \ <span m=\"1638790\">is</span> <span m=\"1638940\">preserved</span> <span m=\"\
  1639660\">under</span> <span m=\"1639870\">this</span> <span m=\"1640080\">change</span>\
  \ <span m=\"1640380\">of</span> <span m=\"1640470\">basis.</span> <span m=\"1641640\"\
  >And</span> <span m=\"1642930\">that's</span> <span m=\"1643200\">why</span> <span\
  \ m=\"1643440\">Plancherel</span> <span m=\"1643860\">is</span> <span m=\"1644150\"\
  >true.</span></p><p><span m=\"1647780\">Another</span> <span m=\"1648080\">important</span>\
  \ <span m=\"1648440\">thing</span> <span m=\"1649340\">is</span> <span m=\"1650630\"\
  >what's</span> <span m=\"1650870\">known</span> <span m=\"1651110\">as</span> <span\
  \ m=\"1651230\">the</span> <span m=\"1651290\">Fourier</span> <span m=\"1651710\"\
  >inversion</span> <span m=\"1652270\">formula.</span> <span m=\"1654684\">The</span>\
  \ <span m=\"1655180\">Fourier</span> <span m=\"1655520\">transform</span> <span\
  \ m=\"1656300\">tells</span> <span m=\"1656570\">you</span> <span m=\"1657050\"\
  >how</span> <span m=\"1657320\">to</span> <span m=\"1657560\">go</span> <span m=\"\
  1657860\">from</span> <span m=\"1658610\">a</span> <span m=\"1658700\">function</span>\
  \ <span m=\"1659720\">to</span> <span m=\"1661130\">the</span> <span m=\"1661460\"\
  >Fourier</span> <span m=\"1661550\">transform.</span> <span m=\"1662730\">Well,</span>\
  \ <span m=\"1663150\">now,</span> <span m=\"1663740\">if</span> <span m=\"1663920\"\
  >you</span> <span m=\"1664190\">are</span> <span m=\"1664310\">given</span> <span\
  \ m=\"1664790\">the</span> <span m=\"1665150\">Fourier</span> <span m=\"1665480\"\
  >transform,</span> <span m=\"1666020\">how</span> <span m=\"1666230\">do</span>\
  \ <span m=\"1666320\">you</span> <span m=\"1666440\">go</span> <span m=\"1666620\"\
  >back?</span></p><p><span m=\"1668090\">There's</span> <span m=\"1668270\">a</span>\
  \ <span m=\"1668300\">formula</span> <span m=\"1669390\">which</span> <span m=\"\
  1669500\">tells</span> <span m=\"1669770\">you</span> <span m=\"1670040\">that</span>\
  \ <span m=\"1670190\">you</span> <span m=\"1670280\">can</span> <span m=\"1670430\"\
  >go</span> <span m=\"1670580\">back</span> <span m=\"1671840\">by</span> <span m=\"\
  1673250\">the</span> <span m=\"1673700\">following</span> <span m=\"1678610\">formula</span>\
  \ <span m=\"1678940\">there.</span> <span m=\"1681350\">So</span> <span m=\"1681470\"\
  >that's</span> <span m=\"1681740\">the</span> <span m=\"1682130\">Fourier</span>\
  \ <span m=\"1683090\">inversion</span> <span m=\"1683540\">formula.</span> <span\
  \ m=\"1684370\">It</span> <span m=\"1684690\">allows</span> <span m=\"1684980\"\
  >you</span> <span m=\"1685310\">to</span> <span m=\"1686180\">do</span> <span m=\"\
  1686300\">this</span> <span m=\"1686510\">inversion.</span></p><p><span m=\"1687110\"\
  >And</span> <span m=\"1688010\">again,</span> <span m=\"1688440\">it's</span> <span\
  \ m=\"1688490\">one</span> <span m=\"1688640\">of</span> <span m=\"1688700\">these</span>\
  \ <span m=\"1688910\">formulas</span> <span m=\"1689330\">where</span> <span m=\"\
  1689540\">I</span> <span m=\"1689690\">encourage</span> <span m=\"1690110\">you</span>\
  \ <span m=\"1690230\">to</span> <span m=\"1691160\">try</span> <span m=\"1691460\"\
  >it</span> <span m=\"1691550\">out</span> <span m=\"1691670\">yourself</span> <span\
  \ m=\"1692360\">by</span> <span m=\"1692600\">plugging</span> <span m=\"1692990\"\
  >in</span> <span m=\"1694220\">the</span> <span m=\"1694550\">formula</span> <span\
  \ m=\"1694970\">and</span> <span m=\"1696170\">expanding.</span> <span m=\"1696770\"\
  >And</span> <span m=\"1696920\">it's</span> <span m=\"1697310\">pretty</span> <span\
  \ m=\"1697550\">easy</span> <span m=\"1697760\">to</span> <span m=\"1697880\">check.</span>\
  \ <span m=\"1699660\">It's</span> <span m=\"1699960\">much</span> <span m=\"1700290\"\
  >easier</span> <span m=\"1700670\">in</span> <span m=\"1700770\">the</span> <span\
  \ m=\"1700890\">finite</span> <span m=\"1701100\">field</span> <span m=\"1701400\"\
  >setting,</span> <span m=\"1701700\">by</span> <span m=\"1701820\">the</span> <span\
  \ m=\"1701910\">way.</span></p><p><span m=\"1702090\">So</span> <span m=\"1702780\"\
  >if</span> <span m=\"1702960\">you</span> <span m=\"1703140\">use</span> <span m=\"\
  1703440\">the</span> <span m=\"1703560\">usual</span> <span m=\"1704010\">Fourier</span>\
  \ <span m=\"1704340\">transform</span> <span m=\"1704840\">on</span> <span m=\"\
  1704910\">the</span> <span m=\"1704970\">real</span> <span m=\"1705240\">line,</span>\
  \ <span m=\"1705630\">there</span> <span m=\"1705780\">are</span> <span m=\"1705840\"\
  >some</span> <span m=\"1706020\">technicalities</span> <span m=\"1706860\">even</span>\
  \ <span m=\"1707070\">to</span> <span m=\"1707160\">prove</span> <span m=\"1707610\"\
  >the</span> <span m=\"1707700\">Fourier</span> <span m=\"1708040\">inversion.</span>\
  \ <span m=\"1708690\">But</span> <span m=\"1709110\">in</span> <span m=\"1709410\"\
  >finite</span> <span m=\"1709770\">groups,</span> <span m=\"1710190\">it's</span>\
  \ <span m=\"1710370\">almost</span> <span m=\"1710640\">trivial.</span> <span m=\"\
  1711070\">You</span> <span m=\"1711370\">expand,</span> <span m=\"1712120\">and</span>\
  \ <span m=\"1712440\">then</span> <span m=\"1712560\">you'll</span> <span m=\"1712700\"\
  >see.</span> <span m=\"1713170\">So</span> <span m=\"1713310\">it's</span> <span\
  \ m=\"1713430\">very</span> <span m=\"1713580\">easy</span> <span m=\"1713850\"\
  >to</span> <span m=\"1713940\">prove.</span></p><p><span m=\"1715250\">But you</span>\
  \ <span m=\"1715350\">can</span> <span m=\"1715500\">also</span> <span m=\"1715710\"\
  >see</span> <span m=\"1715920\">this</span> <span m=\"1716070\">Fourier</span> <span\
  \ m=\"1716340\">inversion</span> <span m=\"1716790\">formula</span> <span m=\"1717150\"\
  >more</span> <span m=\"1717330\">conceptually,</span> <span m=\"1718230\">because</span>\
  \ <span m=\"1718800\">you're</span> <span m=\"1719040\">in</span> <span m=\"1719160\"\
  >a</span> <span m=\"1719220\">unitary</span> <span m=\"1719690\">change</span> <span\
  \ m=\"1720000\">of</span> <span m=\"1720060\">basis.</span> <span m=\"1721550\"\
  >So</span> <span m=\"1721710\">to</span> <span m=\"1721820\">go</span> <span m=\"\
  1721970\">back,</span> <span m=\"1722580\">well,</span> <span m=\"1723200\">think</span>\
  \ <span m=\"1723410\">about</span> <span m=\"1723620\">what</span> <span m=\"1723920\"\
  >it</span> <span m=\"1724010\">means</span> <span m=\"1724250\">in</span> <span\
  \ m=\"1724310\">linear</span> <span m=\"1724550\">algebra</span> <span m=\"1725300\"\
  >to</span> <span m=\"1725510\">revert</span> <span m=\"1726200\">a</span> <span\
  \ m=\"1726380\">unitary</span> <span m=\"1727580\">transformation.</span> <span\
  \ m=\"1728990\">You</span> <span m=\"1729140\">simply</span> <span m=\"1730670\"\
  >multiply</span> <span m=\"1731600\">the</span> <span m=\"1731750\">coefficients</span>\
  \ <span m=\"1732530\">with</span> <span m=\"1732800\">the</span> <span m=\"1733280\"\
  >coordinates.</span> <span m=\"1736490\">Orthogonal,</span> <span m=\"1737070\"\
  >orthonormal</span> <span m=\"1737540\">change</span> <span m=\"1737810\">of</span>\
  \ <span m=\"1737870\">basis.</span></p><p><span m=\"1740335\">Finally,</span> <span\
  \ m=\"1745020\">Fourier</span> <span m=\"1745320\">transform</span> <span m=\"1745740\"\
  >behaves</span> <span m=\"1746130\">while</span> <span m=\"1746430\">under</span>\
  \ <span m=\"1746700\">convolution.</span> <span m=\"1747900\">So</span> <span m=\"\
  1748080\">by</span> <span m=\"1748230\">convolution,</span> <span m=\"1749190\"\
  >we</span> <span m=\"1749340\">define</span> <span m=\"1754660\">the</span> <span\
  \ m=\"1754770\">convolution</span> <span m=\"1755430\">of</span> <span m=\"1755520\"\
  >two</span> <span m=\"1755670\">functions,</span> <span m=\"1756370\">f</span> <span\
  \ m=\"1756420\">and</span> <span m=\"1756510\">g,</span> <span m=\"1758100\">using</span>\
  \ <span m=\"1758400\">the</span> <span m=\"1758460\">following</span> <span m=\"\
  1758850\">formula.</span> <span m=\"1767510\">And</span> <span m=\"1768330\">so</span>\
  \ <span m=\"1768490\">then</span> <span m=\"1768670\">the</span> <span m=\"1768760\"\
  >claim</span> <span m=\"1769270\">is</span> <span m=\"1769480\">that</span> <span\
  \ m=\"1773260\">the</span> <span m=\"1773620\">Fourier</span> <span m=\"1776350\"\
  >transform</span> <span m=\"1777010\">behaves</span> <span m=\"1778090\">very</span>\
  \ <span m=\"1778270\">well</span> <span m=\"1778480\">under</span> <span m=\"1778690\"\
  >convolution.</span> <span m=\"1779800\">It's</span> <span m=\"1781000\">basically</span>\
  \ <span m=\"1781330\">multiplicative</span> <span m=\"1782050\">under</span> <span\
  \ m=\"1782230\">convolution.</span></p><p><span m=\"1784250\">So</span> <span m=\"\
  1784270\">what</span> <span m=\"1784420\">this</span> <span m=\"1784570\">means</span>\
  \ <span m=\"1784810\">is,</span> <span m=\"1785080\">if</span> <span m=\"1785230\"\
  >I</span> <span m=\"1785380\">put</span> <span m=\"1785630\">in--</span> <span m=\"\
  1790490\">so</span> <span m=\"1790700\">it's</span> <span m=\"1791250\">pointwise</span>\
  \ <span m=\"1791960\">true</span> <span m=\"1792260\">everywhere.</span> <span m=\"\
  1794670\">Again,</span> <span m=\"1794910\">very</span> <span m=\"1795120\">easy</span>\
  \ <span m=\"1795390\">proof,</span> <span m=\"1796380\">because</span> <span m=\"\
  1797670\">I</span> <span m=\"1797790\">just</span> <span m=\"1798000\">evaluate</span>\
  \ <span m=\"1799230\">the</span> <span m=\"1799290\">left</span> <span m=\"1799470\"\
  >hand</span> <span m=\"1799590\">side,</span> <span m=\"1803320\">see</span> <span\
  \ m=\"1803620\">what--</span> <span m=\"1804850\">plug in</span> <span m=\"1805240\"\
  >the</span> <span m=\"1805330\">formula</span> <span m=\"1805750\">for</span> <span\
  \ m=\"1805870\">the</span> <span m=\"1806140\">Fourier</span> <span m=\"1806260\"\
  >transform.</span> <span m=\"1807730\">And</span> <span m=\"1807910\">I</span> <span\
  \ m=\"1808000\">find</span> <span m=\"1814300\">it's</span> <span m=\"1814640\"\
  >that.</span></p><p><span m=\"1816170\">And</span> <span m=\"1816260\">now,</span>\
  \ <span m=\"1816440\">I</span> <span m=\"1816530\">plug in</span> <span m=\"1816890\"\
  >the</span> <span m=\"1816950\">formula</span> <span m=\"1817370\">for</span> <span\
  \ m=\"1818090\">convolution.</span> <span m=\"1840450\">So</span> <span m=\"1840630\"\
  >now,</span> <span m=\"1843070\">you</span> <span m=\"1843190\">can</span> <span\
  \ m=\"1843370\">do</span> <span m=\"1843520\">a</span> <span m=\"1843580\">change</span>\
  \ <span m=\"1843910\">of</span> <span m=\"1843970\">variables.</span> <span m=\"\
  1845140\">And</span> <span m=\"1846920\">then</span> <span m=\"1847080\">you--</span>\
  \ <span m=\"1847650\">it's</span> <span m=\"1847810\">not</span> <span m=\"1848020\"\
  >hard</span> <span m=\"1848230\">to</span> <span m=\"1848290\">see.</span> <span\
  \ m=\"1848920\">You</span> <span m=\"1849040\">eventually</span> <span m=\"1849520\"\
  >end</span> <span m=\"1849700\">up</span> <span m=\"1849970\">at</span> <span m=\"\
  1850060\">the</span> <span m=\"1850120\">right</span> <span m=\"1850300\">hand</span>\
  \ <span m=\"1850480\">side.</span></p><p><span m=\"1855010\">So</span> <span m=\"\
  1855090\">these</span> <span m=\"1855270\">are</span> <span m=\"1855330\">some</span>\
  \ <span m=\"1855480\">of</span> <span m=\"1855540\">the</span> <span m=\"1855600\"\
  >properties.</span> <span m=\"1856260\">So</span> <span m=\"1856410\">there</span>\
  \ <span m=\"1856640\">are</span> <span m=\"1858000\">important</span> <span m=\"\
  1858330\">properties</span> <span m=\"1858750\">of</span> <span m=\"1858820\">the</span>\
  \ <span m=\"1858860\">Fourier</span> <span m=\"1859140\">transform.</span> <span\
  \ m=\"1859700\">So</span> <span m=\"1859890\">this</span> <span m=\"1860070\">is</span>\
  \ <span m=\"1860130\">something</span> <span m=\"1860430\">that,</span> <span m=\"\
  1861660\">whenever</span> <span m=\"1861960\">you</span> <span m=\"1862080\">learn</span>\
  \ <span m=\"1862290\">about</span> <span m=\"1862500\">Fourier</span> <span m=\"\
  1862740\">transform,</span> <span m=\"1863160\">you</span> <span m=\"1863280\">always</span>\
  \ <span m=\"1864200\">see</span> <span m=\"1864630\">these</span> <span m=\"1864780\"\
  >few</span> <span m=\"1865170\">properties.</span> <span m=\"1866720\">And</span>\
  \ <span m=\"1866880\">so</span> <span m=\"1866970\">we'll</span> <span m=\"1867120\"\
  >use</span> <span m=\"1867330\">them.</span> <span m=\"1868230\">But</span> <span\
  \ m=\"1868380\">we'll</span> <span m=\"1868500\">also</span> <span m=\"1868800\"\
  >need</span> <span m=\"1869520\">another</span> <span m=\"1870060\">property</span>\
  \ <span m=\"1870690\">that</span> <span m=\"1870870\">is</span> <span m=\"1870930\"\
  >specific</span> <span m=\"1871980\">to</span> <span m=\"1872430\">the</span> <span\
  \ m=\"1872550\">analysis</span> <span m=\"1873180\">of</span> <span m=\"1873330\"\
  >3-term</span> <span m=\"1873900\">arithmetic</span> <span m=\"1874440\">progressions.</span></p><p><span\
  \ m=\"1877990\">So</span> <span m=\"1878730\">what</span> <span m=\"1878960\">does</span>\
  \ <span m=\"1879090\">Fourier</span> <span m=\"1879300\">transform</span> <span\
  \ m=\"1879790\">have</span> <span m=\"1880080\">to</span> <span m=\"1880170\">do</span>\
  \ <span m=\"1880500\">with</span> <span m=\"1880980\">3-APs?</span> <span m=\"1882390\"\
  >So</span> <span m=\"1882480\">we</span> <span m=\"1882570\">want</span> <span m=\"\
  1882750\">to</span> <span m=\"1882810\">use</span> <span m=\"1883020\">it</span>\
  \ <span m=\"1883080\">to</span> <span m=\"1883170\">prove</span> <span m=\"1883480\"\
  >Roth's</span> <span m=\"1883760\">theorem.</span> <span m=\"1884040\">So</span>\
  \ <span m=\"1884220\">we</span> <span m=\"1884370\">better</span> <span m=\"1885570\"\
  >have</span> <span m=\"1885780\">some</span> <span m=\"1885960\">tool</span> <span\
  \ m=\"1886770\">that</span> <span m=\"1887010\">allows</span> <span m=\"1887400\"\
  >us</span> <span m=\"1887550\">to</span> <span m=\"1887640\">analyze</span> <span\
  \ m=\"1888090\">the</span> <span m=\"1888150\">number</span> <span m=\"1888430\"\
  >3-APs.</span> <span m=\"1889330\">And</span> <span m=\"1889530\">here is</span>\
  \ <span m=\"1889800\">a</span> <span m=\"1889890\">key</span> <span m=\"1890100\"\
  >identity</span> <span m=\"1892830\">relating</span> <span m=\"1895340\">Fourier</span>\
  \ <span m=\"1898830\">with</span> <span m=\"1902805\">3-APs.</span> <span m=\"1905250\"\
  >And</span> <span m=\"1907170\">it's</span> <span m=\"1907380\">that,</span> <span\
  \ m=\"1907830\">if</span> <span m=\"1910020\">you</span> <span m=\"1910170\">have</span>\
  \ <span m=\"1910530\">three</span> <span m=\"1910860\">functions,</span> <span m=\"\
  1916410\">then</span> <span m=\"1917160\">the</span> <span m=\"1917280\">following</span>\
  \ <span m=\"1917730\">quantity,</span> <span m=\"1919290\">which</span> <span m=\"\
  1920370\">relates</span> <span m=\"1921360\">the</span> <span m=\"1922140\">number</span>\
  \ <span m=\"1922920\">of</span> <span m=\"1926510\">3-APs--</span></p><p><span m=\"\
  1934880\">So</span> <span m=\"1935000\">this</span> <span m=\"1935180\">function</span>\
  \ <span m=\"1936320\">basically</span> <span m=\"1936860\">counts</span> <span m=\"\
  1937190\">the</span> <span m=\"1937250\">number</span> <span m=\"1937550\">3-APs,</span>\
  \ <span m=\"1938720\">if</span> <span m=\"1938960\">your</span> <span m=\"1939170\"\
  >f, g,</span> <span m=\"1939410\">and</span> <span m=\"1939710\">h</span> <span\
  \ m=\"1940010\">are</span> <span m=\"1940100\">indicator</span> <span m=\"1940700\"\
  >functions</span> <span m=\"1941120\">of</span> <span m=\"1941240\">a</span> <span\
  \ m=\"1941270\">set.</span> <span m=\"1944240\">I</span> <span m=\"1944300\">want</span>\
  \ <span m=\"1944480\">to</span> <span m=\"1944540\">express</span> <span m=\"1945770\"\
  >this</span> <span m=\"1946070\">formula</span> <span m=\"1947060\">in</span> <span\
  \ m=\"1947210\">terms</span> <span m=\"1947510\">of</span> <span m=\"1947570\">the</span>\
  \ <span m=\"1947660\">Fourier</span> <span m=\"1947960\">transforms</span> <span\
  \ m=\"1948620\">of</span> <span m=\"1948710\">these</span> <span m=\"1948890\">functions.</span>\
  \ <span m=\"1952550\">The</span> <span m=\"1952880\">formula</span> <span m=\"1953240\"\
  >turns</span> <span m=\"1953540\">out</span> <span m=\"1954080\">to</span> <span\
  \ m=\"1954170\">be</span> <span m=\"1954290\">fairly</span> <span m=\"1954650\"\
  >simple,</span> <span m=\"1955880\">that</span> <span m=\"1956330\">it</span> <span\
  \ m=\"1956450\">is</span> <span m=\"1956540\">simply</span> <span m=\"1965160\"\
  >that.</span> <span m=\"1965970\">So</span> <span m=\"1966470\">it's</span> <span\
  \ m=\"1966600\">a</span> <span m=\"1966660\">single</span> <span m=\"1967050\">sum</span>\
  \ <span m=\"1968100\">over</span> <span m=\"1968310\">the</span> <span m=\"1968430\"\
  >r's</span> <span m=\"1968730\">of</span> <span m=\"1969270\">f</span> <span m=\"\
  1969840\">hat</span> <span m=\"1970190\">of</span> <span m=\"1970440\">r,</span>\
  \ <span m=\"1970770\">g hat</span> <span m=\"1971220\">of</span> <span m=\"1971340\"\
  >minus</span> <span m=\"1971640\">2r,</span> <span m=\"1972030\">and</span> <span\
  \ m=\"1972270\">h</span> <span m=\"1972480\">hat</span> <span m=\"1972740\">of</span>\
  \ <span m=\"1972860\">r.</span></p><p><span m=\"1975240\">You</span> <span m=\"\
  1975330\">might</span> <span m=\"1975440\">wonder</span> <span m=\"1975660\">why</span>\
  \ <span m=\"1975870\">I</span> <span m=\"1975930\">put</span> <span m=\"1976140\"\
  >a</span> <span m=\"1976170\">minus</span> <span m=\"1976530\">2</span> <span m=\"\
  1976710\">here,</span> <span m=\"1977180\">because</span> <span m=\"1977310\">minus</span>\
  \ <span m=\"1977610\">2</span> <span m=\"1977880\">is</span> <span m=\"1978610\"\
  >r,</span> <span m=\"1978900\">and</span> <span m=\"1979050\">it</span> <span m=\"\
  1979110\">looks</span> <span m=\"1979590\">certainly</span> <span m=\"1979950\"\
  >much</span> <span m=\"1980130\">nicer</span> <span m=\"1980520\">with</span> <span\
  \ m=\"1980710\">just</span> <span m=\"1980970\">r in</span> <span m=\"1981240\"\
  >there.</span> <span m=\"1982212\">And</span> <span m=\"1982560\">that</span> <span\
  \ m=\"1982800\">is</span> <span m=\"1982920\">true.</span> <span m=\"1985080\">This</span>\
  \ <span m=\"1985380\">formula</span> <span m=\"1985740\">as</span> <span m=\"1985940\"\
  >written</span> <span m=\"1986280\">is</span> <span m=\"1986430\">true</span> <span\
  \ m=\"1986670\">for</span> <span m=\"1986850\">over</span> <span m=\"1987450\">any</span>\
  \ <span m=\"1987900\">group.</span> <span m=\"1993940\">And</span> <span m=\"1994140\"\
  >our</span> <span m=\"1994300\">proof</span> <span m=\"1994500\">will</span> <span\
  \ m=\"1994680\">show</span> <span m=\"1994850\">it.</span> <span m=\"1996340\">So</span>\
  \ <span m=\"1996520\">it's</span> <span m=\"1996640\">not</span> <span m=\"1996880\"\
  >really</span> <span m=\"1997090\">about</span> <span m=\"1997370\">F3</span> <span\
  \ m=\"1997690\">at</span> <span m=\"1997810\">all,</span> <span m=\"1997960\">but</span>\
  \ <span m=\"1998140\">any</span> <span m=\"1998320\">group.</span></p><p><span m=\"\
  2005300\">So</span> <span m=\"2005400\">let</span> <span m=\"2005490\">me</span>\
  \ <span m=\"2005610\">prove</span> <span m=\"2005850\">this</span> <span m=\"2006030\"\
  >for</span> <span m=\"2006180\">you</span> <span m=\"2006660\">in</span> <span m=\"\
  2006930\">a</span> <span m=\"2006990\">couple</span> <span m=\"2007240\">of</span>\
  \ <span m=\"2007290\">different</span> <span m=\"2007530\">ways.</span> <span m=\"\
  2009880\">So</span> <span m=\"2009930\">the</span> <span m=\"2010020\">first</span>\
  \ <span m=\"2010320\">proof</span> <span m=\"2015410\">is</span> <span m=\"2016250\"\
  >basically</span> <span m=\"2017390\">a</span> <span m=\"2017780\">straightforward</span>\
  \ <span m=\"2019280\">no</span> <span m=\"2019520\">thinking</span> <span m=\"2019910\"\
  >involved</span> <span m=\"2020360\">proof,</span> <span m=\"2021650\">as</span>\
  \ <span m=\"2021860\">in</span> <span m=\"2022280\">we</span> <span m=\"2023240\"\
  >apply</span> <span m=\"2024740\">these</span> <span m=\"2024950\">formula</span>\
  \ <span m=\"2026240\">for</span> <span m=\"2026840\">using</span> <span m=\"2027120\"\
  >either</span> <span m=\"2027380\">Fourier</span> <span m=\"2027590\">inversion</span>\
  \ <span m=\"2028250\">or</span> <span m=\"2029030\">the</span> <span m=\"2029120\"\
  >inverse</span> <span m=\"2030170\">Fourier</span> <span m=\"2030530\">transform,</span>\
  \ <span m=\"2032350\">and</span> <span m=\"2032860\">plug</span> <span m=\"2033220\"\
  >it</span> <span m=\"2033340\">in,</span> <span m=\"2033820\">and</span> <span m=\"\
  2034240\">expand,</span> <span m=\"2034920\">and</span> <span m=\"2035060\">check.</span>\
  \ <span m=\"2036830\">So</span> <span m=\"2036950\">it's</span> <span m=\"2037070\"\
  >worth</span> <span m=\"2037280\">doing</span> <span m=\"2037520\">at</span> <span\
  \ m=\"2037580\">least</span> <span m=\"2037760\">this</span> <span m=\"2037910\"\
  >once.</span> <span m=\"2038170\">So</span> <span m=\"2038510\">let's</span> <span\
  \ m=\"2039050\">do</span> <span m=\"2039200\">this</span> <span m=\"2039350\">together</span>\
  \ <span m=\"2039710\">at</span> <span m=\"2039770\">least</span> <span m=\"2039980\"\
  >once.</span> <span m=\"2041980\">But</span> <span m=\"2042210\">this</span> <span\
  \ m=\"2042380\">something</span> <span m=\"2042680\">that</span> <span m=\"2042830\"\
  >is</span> <span m=\"2043250\">a</span> <span m=\"2043310\">fairly</span> <span\
  \ m=\"2043640\">straightforward</span> <span m=\"2044420\">computation.</span></p><p><span\
  \ m=\"2045580\">The</span> <span m=\"2045680\">left</span> <span m=\"2045890\">hand</span>\
  \ <span m=\"2046040\">side</span> <span m=\"2048980\">can</span> <span m=\"2049190\"\
  >be</span> <span m=\"2049310\">expanded</span> <span m=\"2050900\">using</span>\
  \ <span m=\"2051350\">Fourier</span> <span m=\"2051560\">inversion.</span> <span\
  \ m=\"2054920\">so</span> <span m=\"2055150\">r1</span> <span m=\"2057219\">f</span>\
  \ <span m=\"2057400\">hat</span> <span m=\"2058310\">r1</span> <span m=\"2059110\"\
  >omega</span> <span m=\"2060010\">to</span> <span m=\"2060159\">the</span> <span\
  \ m=\"2060219\">minus</span> <span m=\"2060760\">r1</span> <span m=\"2061389\">dot</span>\
  \ <span m=\"2061900\">x,</span> <span m=\"2064560\">and</span> <span m=\"2065020\"\
  >sum</span> <span m=\"2065650\">over</span> <span m=\"2065929\">r2</span> <span\
  \ m=\"2067659\">g</span> <span m=\"2067974\">hat</span> <span m=\"2069489\">r2</span>\
  \ <span m=\"2070060\">omega</span> <span m=\"2070690\">to</span> <span m=\"2070810\"\
  >the</span> <span m=\"2070900\">minus</span> <span m=\"2071380\">r2</span> <span\
  \ m=\"2072280\">dot</span> <span m=\"2073239\">x</span> <span m=\"2073480\">plus</span>\
  \ <span m=\"2073780\">y,</span> <span m=\"2076384\">and</span> <span m=\"2076820\"\
  >then</span> <span m=\"2077060\">finally</span> <span m=\"2077870\">sum</span> <span\
  \ m=\"2078199\">over</span> <span m=\"2078380\">r3</span> <span m=\"2079770\">h</span>\
  \ <span m=\"2080030\">hat</span> <span m=\"2080610\">of</span> <span m=\"2080880\"\
  >r3</span> <span m=\"2083159\">omega</span> <span m=\"2083560\">to</span> <span\
  \ m=\"2083710\">the</span> <span m=\"2083860\">minus</span> <span m=\"2084669\"\
  >r3</span> <span m=\"2086080\">dot</span> <span m=\"2086440\">x</span> <span m=\"\
  2086679\">plus</span> <span m=\"2087159\">2y.</span> <span m=\"2090989\">So</span>\
  \ <span m=\"2091139\">I'm</span> <span m=\"2091260\">using</span> <span m=\"2091590\"\
  >Fourier</span> <span m=\"2091909\">inversion,</span> <span m=\"2092460\">replace</span>\
  \ <span m=\"2093210\">f,</span> <span m=\"2093420\">g,</span> <span m=\"2093840\"\
  >and</span> <span m=\"2094050\">h</span> <span m=\"2094770\">by</span> <span m=\"\
  2095389\">their</span> <span m=\"2098010\">Fourier</span> <span m=\"2098340\">transforms.</span>\
  \ <span m=\"2098800\">Oh,</span> <span m=\"2099210\">sorry,</span> <span m=\"2099380\"\
  >there</span> <span m=\"2099540\">should</span> <span m=\"2099690\">be--</span>\
  \ <span m=\"2102280\">yeah,</span> <span m=\"2102760\">so</span> <span m=\"2103110\"\
  >no</span> <span m=\"2103440\">minus.</span></p><p><span m=\"2106960\">So</span>\
  \ <span m=\"2107080\">now,</span> <span m=\"2107500\">we</span> <span m=\"2108250\"\
  >exchange</span> <span m=\"2109330\">sums</span> <span m=\"2109780\">and</span>\
  \ <span m=\"2109900\">expectations,</span> <span m=\"2110620\">do</span> <span m=\"\
  2110830\">a</span> <span m=\"2111730\">switch</span> <span m=\"2112760\">in</span>\
  \ <span m=\"2113140\">the</span> <span m=\"2113230\">order</span> <span m=\"2113560\"\
  >of</span> <span m=\"2113620\">summation,</span> <span m=\"2114605\">so</span> <span\
  \ m=\"2115020\">r1,</span> <span m=\"2115480\">r2,</span> <span m=\"2115840\">r3</span>\
  \ <span m=\"2116860\">and</span> <span m=\"2117800\">f</span> <span m=\"2118265\"\
  >hat</span> <span m=\"2118730\">of</span> <span m=\"2119190\">r1</span> <span m=\"\
  2121105\">g</span> <span m=\"2121520\">hat</span> <span m=\"2121850\">of</span>\
  \ <span m=\"2122000\">r2</span> <span m=\"2123710\">h</span> <span m=\"2124010\"\
  >hat of</span> <span m=\"2124350\">r3.</span> <span m=\"2127050\">And</span> <span\
  \ m=\"2128040\">you</span> <span m=\"2128160\">have</span> <span m=\"2128490\">this</span>\
  \ <span m=\"2129120\">expectation</span> <span m=\"2130380\">over</span> <span m=\"\
  2131370\">x</span> <span m=\"2131550\">and</span> <span m=\"2131670\">y</span> <span\
  \ m=\"2132810\">and</span> <span m=\"2133110\">omega</span> <span m=\"2133860\"\
  >of</span> <span m=\"2134550\">x</span> <span m=\"2135140\">dot</span> <span m=\"\
  2136000\">r1</span> <span m=\"2136680\">plus</span> <span m=\"2136980\">r2</span>\
  \ <span m=\"2137490\">plus</span> <span m=\"2137820\">r3.</span> <span m=\"2140610\"\
  >In fact,</span> <span m=\"2141450\">I</span> <span m=\"2141540\">can</span> <span\
  \ m=\"2141690\">even</span> <span m=\"2141930\">write</span> <span m=\"2142140\"\
  >the</span> <span m=\"2142260\">x</span> <span m=\"2142470\">and</span> <span m=\"\
  2142590\">y</span> <span m=\"2142800\">separately,</span> <span m=\"2145340\">y</span>\
  \ <span m=\"2146190\">omega</span> <span m=\"2147330\">to</span> <span m=\"2147620\"\
  >the</span> <span m=\"2150770\">y</span> <span m=\"2151270\">dot</span> <span m=\"\
  2152690\">r2</span> <span m=\"2153800\">plus</span> <span m=\"2154430\">2r3.</span>\
  \ <span m=\"2157180\">So</span> <span m=\"2157430\">just</span> <span m=\"2157670\"\
  >rearranging.</span></p><p><span m=\"2159540\">And</span> <span m=\"2159680\">now,</span>\
  \ <span m=\"2159980\">you</span> <span m=\"2160130\">see</span> <span m=\"2160400\"\
  >that</span> <span m=\"2160640\">as</span> <span m=\"2160970\">you</span> <span\
  \ m=\"2161330\">take</span> <span m=\"2161570\">expectation</span> <span m=\"2162320\"\
  >over</span> <span m=\"2162860\">x,</span> <span m=\"2165000\">this</span> <span\
  \ m=\"2165330\">expectation</span> <span m=\"2166320\">is</span> <span m=\"2166620\"\
  >equal</span> <span m=\"2166980\">to</span> <span m=\"2167870\">1,</span> <span\
  \ m=\"2169110\">if</span> <span m=\"2171090\">r1</span> <span m=\"2171600\">plus</span>\
  \ <span m=\"2172080\">r2</span> <span m=\"2173400\">plus</span> <span m=\"2173670\"\
  >r3</span> <span m=\"2174240\">is</span> <span m=\"2174390\">equal</span> <span\
  \ m=\"2174600\">to</span> <span m=\"2174720\">0,</span> <span m=\"2175500\">and</span>\
  \ <span m=\"2175650\">0</span> <span m=\"2176190\">otherwise.</span> <span m=\"\
  2179130\">And</span> <span m=\"2179230\">likewise,</span> <span m=\"2179580\">the</span>\
  \ <span m=\"2179670\">third</span> <span m=\"2180450\">expectation</span> <span\
  \ m=\"2181770\">is</span> <span m=\"2182340\">either</span> <span m=\"2182610\"\
  >1</span> <span m=\"2182940\">or</span> <span m=\"2183060\">0,</span> <span m=\"\
  2183930\">depending</span> <span m=\"2184440\">on</span> <span m=\"2184800\">the</span>\
  \ <span m=\"2184890\">sums</span> <span m=\"2186570\">of</span> <span m=\"2187740\"\
  >r2</span> <span m=\"2188140\">and</span> <span m=\"2188340\">r3.</span> <span m=\"\
  2193650\">So</span> <span m=\"2194040\">the</span> <span m=\"2194280\">only</span>\
  \ <span m=\"2194550\">terms</span> <span m=\"2194970\">that</span> <span m=\"2195060\"\
  >remain,</span> <span m=\"2195990\">after</span> <span m=\"2196260\">you</span>\
  \ <span m=\"2196380\">take</span> <span m=\"2196650\">out</span> <span m=\"2196760\"\
  >these</span> <span m=\"2196880\">0's,</span> <span m=\"2197970\">are</span> <span\
  \ m=\"2198180\">cases</span> <span m=\"2198810\">where</span> <span m=\"2199860\"\
  >both</span> <span m=\"2202870\">these</span> <span m=\"2203080\">two</span> <span\
  \ m=\"2203260\">equations</span> <span m=\"2203920\">are</span> <span m=\"2204070\"\
  >satisfied.</span></p><p><span m=\"2207350\">And</span> <span m=\"2207440\">then</span>\
  \ <span m=\"2207540\">you</span> <span m=\"2207660\">see</span> <span m=\"2208350\"\
  >that</span> <span m=\"2209640\">the</span> <span m=\"2209730\">only</span> <span\
  \ m=\"2210480\">remaining</span> <span m=\"2210900\">terms</span> <span m=\"2212990\"\
  >are</span> <span m=\"2214100\">basically</span> <span m=\"2215150\">the</span>\
  \ <span m=\"2215240\">ones</span> <span m=\"2215630\">given</span> <span m=\"2216590\"\
  >in</span> <span m=\"2220120\">the</span> <span m=\"2220220\">sum</span> <span m=\"\
  2221510\">on</span> <span m=\"2221660\">the</span> <span m=\"2221750\">right</span>\
  \ <span m=\"2221960\">hand</span> <span m=\"2222140\">side.</span> <span m=\"2225410\"\
  >OK?</span> <span m=\"2226000\">So</span> <span m=\"2226100\">that's</span> <span\
  \ m=\"2226260\">the</span> <span m=\"2226310\">proof.</span> <span m=\"2227930\"\
  >Pretty</span> <span m=\"2228170\">straightforward,</span> <span m=\"2228740\">you</span>\
  \ <span m=\"2228860\">plug in</span> <span m=\"2229190\">Fourier</span> <span m=\"\
  2229450\">inversion.</span></p><p><span m=\"2233540\">I</span> <span m=\"2233630\"\
  >want</span> <span m=\"2233810\">to</span> <span m=\"2233900\">show</span> <span\
  \ m=\"2234110\">you</span> <span m=\"2234680\">a</span> <span m=\"2235310\">different</span>\
  \ <span m=\"2235670\">proof</span> <span m=\"2236240\">that</span> <span m=\"2237080\"\
  >hopefully</span> <span m=\"2237470\">will</span> <span m=\"2237620\">be</span>\
  \ <span m=\"2237740\">more</span> <span m=\"2237890\">familiar</span> <span m=\"\
  2238370\">and</span> <span m=\"2238460\">more</span> <span m=\"2238610\">conceptual.</span>\
  \ <span m=\"2239240\">Now,</span> <span m=\"2239540\">it</span> <span m=\"2239630\"\
  >doesn't</span> <span m=\"2239840\">involve</span> <span m=\"2240200\">carrying</span>\
  \ <span m=\"2240560\">through</span> <span m=\"2240740\">this</span> <span m=\"\
  2240890\">calculation,</span> <span m=\"2241460\">even</span> <span m=\"2241700\"\
  >though</span> <span m=\"2241850\">this</span> <span m=\"2242030\">is</span> <span\
  \ m=\"2242780\">not</span> <span m=\"2243190\">at all</span> <span m=\"2243260\"\
  >hard</span> <span m=\"2243500\">calculation.</span> <span m=\"2246380\">But</span>\
  \ <span m=\"2246500\">first,</span> <span m=\"2246980\">let</span> <span m=\"2247130\"\
  >me</span> <span m=\"2248780\">rewrite</span> <span m=\"2249440\">the</span> <span\
  \ m=\"2249530\">formula</span> <span m=\"2250040\">up</span> <span m=\"2250220\"\
  >there.</span></p><p><span m=\"2251610\">So</span> <span m=\"2252220\">in</span>\
  \ <span m=\"2252420\">F3,</span> <span m=\"2253040\">it</span> <span m=\"2253370\"\
  >will</span> <span m=\"2253520\">be</span> <span m=\"2255890\">convenient,</span>\
  \ <span m=\"2256670\">and</span> <span m=\"2256790\">so the</span> <span m=\"2257210\"\
  >formula</span> <span m=\"2257600\">is</span> <span m=\"2257690\">actually</span>\
  \ <span m=\"2257870\">slightly</span> <span m=\"2258890\">easier</span> <span m=\"\
  2259190\">to</span> <span m=\"2259310\">interpreting</span> <span m=\"2259940\"\
  >F3,</span> <span m=\"2260705\">in</span> <span m=\"2260990\">F3,</span> <span m=\"\
  2261440\">the</span> <span m=\"2262250\">identity</span> <span m=\"2262700\">says</span>\
  \ <span m=\"2263030\">that,</span> <span m=\"2264770\">if</span> <span m=\"2264950\"\
  >you</span> <span m=\"2265040\">look</span> <span m=\"2265280\">at</span> <span\
  \ m=\"2265970\">the</span> <span m=\"2266060\">quantity--</span> <span m=\"2272460\"\
  >I</span> <span m=\"2272840\">need.</span> <span m=\"2278732\">So</span> <span m=\"\
  2279210\">let</span> <span m=\"2279310\">me</span> <span m=\"2279410\">give</span>\
  \ <span m=\"2279440\">you</span> <span m=\"2279530\">a</span> <span m=\"2279560\"\
  >second</span> <span m=\"2279890\">proof</span> <span m=\"2281300\">that</span>\
  \ <span m=\"2281630\">works</span> <span m=\"2283130\">just</span> <span m=\"2283370\"\
  >in</span> <span m=\"2283810\">F3,</span> <span m=\"2284300\">but</span> <span m=\"\
  2284420\">you</span> <span m=\"2284510\">can</span> <span m=\"2284630\">modify</span>\
  \ <span m=\"2284900\">it to</span> <span m=\"2285170\">work in</span> <span m=\"\
  2285530\">other</span> <span m=\"2285740\">groups.</span> <span m=\"2286210\">But</span>\
  \ <span m=\"2286340\">in F3,</span> <span m=\"2286540\">it's</span> <span m=\"2286850\"\
  >particularly</span> <span m=\"2287450\">nice.</span></p><p><span m=\"2288950\"\
  >The</span> <span m=\"2289040\">left</span> <span m=\"2289280\">hand</span> <span\
  \ m=\"2289520\">side,</span> <span m=\"2292190\">you</span> <span m=\"2292250\"\
  >see,</span> <span m=\"2293590\">the</span> <span m=\"2293710\">left</span> <span\
  \ m=\"2293880\">hand</span> <span m=\"2294000\">side,</span> <span m=\"2294240\"\
  >I</span> <span m=\"2294310\">can</span> <span m=\"2294470\">rewrite</span> <span\
  \ m=\"2295030\">it</span> <span m=\"2296200\">as</span> <span m=\"2300420\">the</span>\
  \ <span m=\"2300510\">following</span> <span m=\"2301110\">form,</span> <span m=\"\
  2301980\">where</span> <span m=\"2302640\">I</span> <span m=\"2302790\">sum</span>\
  \ <span m=\"2303390\">over--</span> <span m=\"2304840\">well,</span> <span m=\"\
  2305130\">I</span> <span m=\"2305190\">take</span> <span m=\"2305400\">expectation</span>\
  \ <span m=\"2306570\">over all</span> <span m=\"2306990\">triples</span> <span m=\"\
  2307740\">x, y,</span> <span m=\"2307950\">z</span> <span m=\"2309000\">that</span>\
  \ <span m=\"2309180\">sum</span> <span m=\"2309480\">to</span> <span m=\"2309600\"\
  >0.</span> <span m=\"2312600\">Because</span> <span m=\"2312870\">a</span> <span\
  \ m=\"2312930\">3-AP</span> <span m=\"2314520\">is</span> <span m=\"2314970\">the</span>\
  \ <span m=\"2315060\">same</span> <span m=\"2315480\">as</span> <span m=\"2315660\"\
  >three</span> <span m=\"2315900\">elements,</span> <span m=\"2316470\">three</span>\
  \ <span m=\"2316920\">points</span> <span m=\"2317310\">in</span> <span m=\"2317400\"\
  >the</span> <span m=\"2317460\">vector</span> <span m=\"2317730\">space</span> <span\
  \ m=\"2318000\">summing</span> <span m=\"2318270\">to</span> <span m=\"2318390\"\
  >0.</span> <span m=\"2321830\">But</span> <span m=\"2321950\">now,</span> <span\
  \ m=\"2322190\">you</span> <span m=\"2322310\">see</span> <span m=\"2322700\">that</span>\
  \ <span m=\"2324350\">this</span> <span m=\"2324890\">quantity</span> <span m=\"\
  2326000\">is</span> <span m=\"2327050\">the</span> <span m=\"2327140\">same</span>\
  \ <span m=\"2327740\">as</span> <span m=\"2330134\">the</span> <span m=\"2330620\"\
  >convolution</span> <span m=\"2332520\">evaluated</span> <span m=\"2333250\">at</span>\
  \ <span m=\"2333950\">0--</span> <span m=\"2337640\">so</span> <span m=\"2337810\"\
  >if</span> <span m=\"2337910\">you</span> <span m=\"2338030\">extend</span> <span\
  \ m=\"2338450\">the</span> <span m=\"2338510\">definition</span> <span m=\"2339020\"\
  >of</span> <span m=\"2339080\">convolution</span> <span m=\"2339650\">to</span>\
  \ <span m=\"2340070\">more</span> <span m=\"2340280\">than</span> <span m=\"2340430\"\
  >one</span> <span m=\"2340610\">func--</span> <span m=\"2340850\">more</span> <span\
  \ m=\"2341030\">than</span> <span m=\"2341150\">two</span> <span m=\"2341300\">functions.</span></p><p><span\
  \ m=\"2343630\">But</span> <span m=\"2343730\">now,</span> <span m=\"2344010\">we</span>\
  \ <span m=\"2344160\">apply</span> <span m=\"2344580\">Fourier</span> <span m=\"\
  2344850\">inversion.</span> <span m=\"2349650\">And</span> <span m=\"2349800\">we</span>\
  \ <span m=\"2349950\">find</span> <span m=\"2351150\">that--</span> <span m=\"2361780\"\
  >OK.</span> <span m=\"2362660\">So</span> <span m=\"2362790\">by</span> <span m=\"\
  2363110\">Fourier</span> <span m=\"2363260\">inversion,</span> <span m=\"2363860\"\
  >you</span> <span m=\"2364010\">have</span> <span m=\"2364680\">that.</span> <span\
  \ m=\"2366940\">But</span> <span m=\"2367360\">now,</span> <span m=\"2367910\">by</span>\
  \ <span m=\"2368330\">the</span> <span m=\"2368480\">identity</span> <span m=\"\
  2368870\">that</span> <span m=\"2369020\">relates</span> <span m=\"2369440\">the</span>\
  \ <span m=\"2369560\">Fourier</span> <span m=\"2369890\">transform</span> <span\
  \ m=\"2370700\">and</span> <span m=\"2371330\">inversion,</span> <span m=\"2378660\"\
  >you</span> <span m=\"2378780\">have</span> <span m=\"2378930\">that.</span> <span\
  \ m=\"2381560\">And</span> <span m=\"2381720\">that's</span> <span m=\"2382230\"\
  >the</span> <span m=\"2382290\">proof,</span> <span m=\"2383370\">because</span>\
  \ <span m=\"2384120\">minus</span> <span m=\"2384450\">2</span> <span m=\"2384620\"\
  >r</span> <span m=\"2384790\">is</span> <span m=\"2384830\">the</span> <span m=\"\
  2384880\">same</span> <span m=\"2385110\">as</span> <span m=\"2385230\">r.</span>\
  \ <span m=\"2388470\">So</span> <span m=\"2388620\">it's</span> <span m=\"2389160\"\
  >shorter,</span> <span m=\"2389760\">because</span> <span m=\"2390000\">we're</span>\
  \ <span m=\"2390390\">using</span> <span m=\"2390690\">some</span> <span m=\"2390900\"\
  >properties</span> <span m=\"2391410\">here</span> <span m=\"2392100\">about</span>\
  \ <span m=\"2392700\">convolution</span> <span m=\"2393670\">and--</span> <span\
  \ m=\"2394310\">yeah,</span> <span m=\"2394720\">so</span> <span m=\"2394990\">about</span>\
  \ <span m=\"2395100\">the</span> <span m=\"2395190\">convolution.</span></p><p><span\
  \ m=\"2403720\">That</span> <span m=\"2404230\">formula</span> <span m=\"2404590\"\
  >up</span> <span m=\"2404710\">there</span> <span m=\"2405110\">is,</span> <span\
  \ m=\"2405250\">of</span> <span m=\"2405310\">course,</span> <span m=\"2405580\"\
  >related</span> <span m=\"2406000\">to</span> <span m=\"2406270\">counting</span>\
  \ <span m=\"2406600\">3-APs.</span> <span m=\"2407530\">Because</span> <span m=\"\
  2408640\">if</span> <span m=\"2411230\">f, g,</span> <span m=\"2411545\">and</span>\
  \ <span m=\"2411860\">h</span> <span m=\"2413990\">are</span> <span m=\"2414110\"\
  >all</span> <span m=\"2415640\">indicators</span> <span m=\"2416510\">of</span>\
  \ <span m=\"2416960\">some</span> <span m=\"2417270\">set,</span> <span m=\"2422080\"\
  >then</span> <span m=\"2423580\">the</span> <span m=\"2423700\">left</span> <span\
  \ m=\"2423910\">hand</span> <span m=\"2424060\">side</span> <span m=\"2424900\"\
  >is</span> <span m=\"2425050\">the</span> <span m=\"2425110\">same</span> <span\
  \ m=\"2425710\">as</span> <span m=\"2427060\">basically</span> <span m=\"2427600\"\
  >the</span> <span m=\"2428200\">number</span> <span m=\"2428830\">of</span> <span\
  \ m=\"2431170\">triples</span> <span m=\"2434110\">of</span> <span m=\"2434260\"\
  >elements</span> <span m=\"2434650\">in</span> <span m=\"2434770\">A</span> <span\
  \ m=\"2435535\">whose</span> <span m=\"2436030\">sum</span> <span m=\"2437851\"\
  >is</span> <span m=\"2438310\">equal</span> <span m=\"2438520\">to</span> <span\
  \ m=\"2438580\">0.</span> <span m=\"2442210\">And</span> <span m=\"2442330\">the</span>\
  \ <span m=\"2442390\">right</span> <span m=\"2442570\">hand</span> <span m=\"2442750\"\
  >side</span> <span m=\"2444250\">is</span> <span m=\"2445330\">the</span> <span\
  \ m=\"2445480\">sum</span> <span m=\"2446680\">of</span> <span m=\"2446800\">the</span>\
  \ <span m=\"2447010\">third</span> <span m=\"2447430\">power</span> <span m=\"2450370\"\
  >of</span> <span m=\"2450610\">the</span> <span m=\"2450760\">Fourier</span> <span\
  \ m=\"2451090\">coefficients.</span></p><p><span m=\"2456360\">And</span> <span\
  \ m=\"2456460\">this</span> <span m=\"2456610\">formula</span> <span m=\"2456940\"\
  >should</span> <span m=\"2457120\">look</span> <span m=\"2457270\">somewhat</span>\
  \ <span m=\"2457600\">familiar,</span> <span m=\"2459980\">because</span> <span\
  \ m=\"2461060\">we</span> <span m=\"2462500\">also</span> <span m=\"2462740\">used</span>\
  \ <span m=\"2463040\">this</span> <span m=\"2463250\">kind</span> <span m=\"2463430\"\
  >of</span> <span m=\"2463490\">formula</span> <span m=\"2463940\">back</span> <span\
  \ m=\"2464270\">when</span> <span m=\"2464420\">we</span> <span m=\"2464510\">discussed</span>\
  \ <span m=\"2465500\">spectral</span> <span m=\"2465815\">graph</span> <span m=\"\
  2466130\">theory.</span> <span m=\"2467610\">And</span> <span m=\"2467660\">remember,</span>\
  \ <span m=\"2468290\">the</span> <span m=\"2468470\">third</span> <span m=\"2468920\"\
  >moment</span> <span m=\"2469670\">of the</span> <span m=\"2470060\">eigenvalues</span>\
  \ <span m=\"2471350\">is</span> <span m=\"2472520\">the</span> <span m=\"2472640\"\
  >trace</span> <span m=\"2473180\">of</span> <span m=\"2473780\">the</span> <span\
  \ m=\"2473870\">third</span> <span m=\"2474410\">power,</span> <span m=\"2475260\"\
  >which</span> <span m=\"2475370\">counts</span> <span m=\"2475760\">closed</span>\
  \ <span m=\"2476330\">walks</span> <span m=\"2477650\">in</span> <span m=\"2477740\"\
  >Cayley</span> <span m=\"2477800\">graph.</span> <span m=\"2478880\">So</span> <span\
  \ m=\"2479000\">this</span> <span m=\"2479120\">is</span> <span m=\"2479210\">actually</span>\
  \ <span m=\"2479450\">the</span> <span m=\"2479510\">same</span> <span m=\"2479780\"\
  >formula.</span> <span m=\"2481100\">So</span> <span m=\"2482120\">in</span> <span\
  \ m=\"2482270\">the</span> <span m=\"2482360\">case</span> <span m=\"2483740\">if</span>\
  \ <span m=\"2484850\">A</span> <span m=\"2485060\">is</span> <span m=\"2485420\"\
  >symmetric,</span> <span m=\"2486210\">let's</span> <span m=\"2486260\">say,</span>\
  \ <span m=\"2487640\">then</span> <span m=\"2487820\">this</span> <span m=\"2487980\"\
  >is</span> <span m=\"2488030\">the</span> <span m=\"2488120\">same</span> <span\
  \ m=\"2490190\">as</span> <span m=\"2490880\">the</span> <span m=\"2490970\">formula</span>\
  \ <span m=\"2494460\">that</span> <span m=\"2494680\">counts</span> <span m=\"2499180\"\
  >closed</span> <span m=\"2499600\">walks</span> <span m=\"2500020\">of</span> <span\
  \ m=\"2500140\">length</span> <span m=\"2500320\">three</span> <span m=\"2507530\"\
  >in</span> <span m=\"2507970\">the Cayley</span> <span m=\"2508320\">graph.</span></p><p><span\
  \ m=\"2514100\">The</span> <span m=\"2514200\">point</span> <span m=\"2514320\"\
  >of</span> <span m=\"2514410\">this</span> <span m=\"2514560\">comment</span> <span\
  \ m=\"2514950\">is</span> <span m=\"2515100\">just</span> <span m=\"2515340\">to</span>\
  \ <span m=\"2515430\">tell</span> <span m=\"2515670\">you</span> <span m=\"2515820\"\
  >that</span> <span m=\"2516310\">Fourier</span> <span m=\"2516590\">transform</span>\
  \ <span m=\"2516980\">is</span> <span m=\"2517110\">somehow</span> <span m=\"2517440\"\
  >it's</span> <span m=\"2517620\">not</span> <span m=\"2518460\">this</span> <span\
  \ m=\"2519570\">brand</span> <span m=\"2519930\">new</span> <span m=\"2520170\"\
  >concept</span> <span m=\"2520680\">that</span> <span m=\"2520800\">we've</span>\
  \ <span m=\"2520980\">never</span> <span m=\"2521220\">seen</span> <span m=\"2521430\"\
  >before.</span> <span m=\"2522160\">It</span> <span m=\"2522180\">is</span> <span\
  \ m=\"2522390\">intimately</span> <span m=\"2522870\">tied</span> <span m=\"2523230\"\
  >to</span> <span m=\"2523650\">many</span> <span m=\"2524010\">of</span> <span m=\"\
  2524070\">the</span> <span m=\"2524160\">things</span> <span m=\"2524400\">that</span>\
  \ <span m=\"2524490\">we</span> <span m=\"2524610\">have</span> <span m=\"2524820\"\
  >seen</span> <span m=\"2525330\">earlier</span> <span m=\"2525600\">in</span> <span\
  \ m=\"2525690\">this</span> <span m=\"2525870\">course</span> <span m=\"2526530\"\
  >but</span> <span m=\"2527280\">in</span> <span m=\"2527430\">disguise.</span> <span\
  \ m=\"2528866\">So</span> <span m=\"2529300\">it</span> <span m=\"2529390\">is</span>\
  \ <span m=\"2529510\">related</span> <span m=\"2529900\">to</span> <span m=\"2530020\"\
  >the</span> <span m=\"2530110\">spectral</span> <span m=\"2530530\">graph</span>\
  \ <span m=\"2530830\">theory</span> <span m=\"2531390\">that</span> <span m=\"2531520\"\
  >we</span> <span m=\"2531670\">discussed</span> <span m=\"2532150\">at</span> <span\
  \ m=\"2532240\">length</span> <span m=\"2532690\">earlier</span> <span m=\"2532990\"\
  >in</span> <span m=\"2533110\">this</span> <span m=\"2533290\">course.</span></p><p><span\
  \ m=\"2541290\">Now</span> <span m=\"2541400\">that</span> <span m=\"2541520\">we</span>\
  \ <span m=\"2541640\">have</span> <span m=\"2541790\">the</span> <span m=\"2541850\"\
  >Fourier</span> <span m=\"2542120\">transform,</span> <span m=\"2543080\">I</span>\
  \ <span m=\"2543140\">want</span> <span m=\"2543320\">to</span> <span m=\"2543380\"\
  >develop</span> <span m=\"2543890\">some</span> <span m=\"2544760\">machinery</span>\
  \ <span m=\"2545660\">to</span> <span m=\"2546800\">prove</span> <span m=\"2548420\"\
  >Roth's</span> <span m=\"2548750\">theorem</span> <span m=\"2549440\">following</span>\
  \ <span m=\"2550440\">the</span> <span m=\"2550520\">strategy</span> <span m=\"\
  2551620\">up</span> <span m=\"2551970\">there.</span> <span m=\"2552930\">So</span>\
  \ <span m=\"2553010\">let's</span> <span m=\"2553160\">take</span> <span m=\"2553310\"\
  >a</span> <span m=\"2553370\">quick</span> <span m=\"2553580\">break.</span> <span\
  \ m=\"2554100\">And</span> <span m=\"2554200\">then</span> <span m=\"2554300\">when</span>\
  \ <span m=\"2554420\">we</span> <span m=\"2554510\">come</span> <span m=\"2554690\"\
  >back,</span> <span m=\"2555000\">we'll</span> <span m=\"2555020\">prove</span>\
  \ <span m=\"2555260\">Roth's</span> <span m=\"2555710\">theorem.</span></p><p><span\
  \ m=\"2560570\">Any</span> <span m=\"2560750\">questions</span> <span m=\"2561110\"\
  >so</span> <span m=\"2561260\">far?</span></p><p><span m=\"2565204\">AUDIENCE:</span>\
  \ <span m=\"2565670\">So</span> <span m=\"2567080\">for</span> <span m=\"2567540\"\
  >this</span> <span m=\"2567810\">one,</span> <span m=\"2568740\">you</span> <span\
  \ m=\"2568890\">said--</span> <span m=\"2570596\">is it like</span> <span m=\"2571020\"\
  >we</span> <span m=\"2571250\">only</span> <span m=\"2571640\">used</span> <span\
  \ m=\"2571900\">the</span> <span m=\"2572316\">fact that</span> <span m=\"2572732\"\
  >it's</span> <span m=\"2573150\">F3</span> <span m=\"2573580\">to the n-th</span>\
  \ <span m=\"2574536\">at the</span> <span m=\"2575014\">end of the</span> <span\
  \ m=\"2575492\">proof,</span> <span m=\"2575970\">like in</span> <span m=\"2576448\"\
  >that last</span> <span m=\"2576926\">step?</span></p><p><span m=\"2577410\">YUFEI\
  \ ZHAO:</span> <span m=\"2577480\">OK.</span> <span m=\"2577880\">So</span> <span\
  \ m=\"2577940\">question</span> <span m=\"2578240\">is,</span> <span m=\"2578370\"\
  >where</span> <span m=\"2578610\">do</span> <span m=\"2578730\">we</span> <span\
  \ m=\"2578850\">use</span> <span m=\"2579120\">that</span> <span m=\"2579890\">in</span>\
  \ <span m=\"2580080\">F3</span> <span m=\"2580230\">to</span> <span m=\"2580350\"\
  >the</span> <span m=\"2580470\">n-th?</span> <span m=\"2581040\">This</span> <span\
  \ m=\"2581310\">formula</span> <span m=\"2581720\">here</span> <span m=\"2581940\"\
  >holds</span> <span m=\"2582240\">in</span> <span m=\"2582540\">every</span> <span\
  \ m=\"2583500\">finite</span> <span m=\"2583860\">abelian</span> <span m=\"2584190\"\
  >group,</span> <span m=\"2584970\">if</span> <span m=\"2585120\">you</span> <span\
  \ m=\"2585180\">use</span> <span m=\"2585420\">the</span> <span m=\"2585510\">correct</span>\
  \ <span m=\"2585840\">definition</span> <span m=\"2586410\">of</span> <span m=\"\
  2586680\">Fourier</span> <span m=\"2587190\">transform</span> <span m=\"2588060\"\
  >with</span> <span m=\"2588240\">the</span> <span m=\"2588330\">averaging</span>\
  \ <span m=\"2588690\">normalization.</span> <span m=\"2590240\">So</span> <span\
  \ m=\"2590460\">in</span> <span m=\"2590670\">the</span> <span m=\"2591450\">other</span>\
  \ <span m=\"2591690\">formula</span> <span m=\"2592140\">where</span> <span m=\"\
  2592340\">you</span> <span m=\"2592440\">replace</span> <span m=\"2593070\">minus</span>\
  \ <span m=\"2593460\">2</span> <span m=\"2594120\">by</span> <span m=\"2594420\"\
  >1,</span> <span m=\"2595020\">that</span> <span m=\"2595200\">requires</span> <span\
  \ m=\"2595730\">F3.</span></p><p><span m=\"2597890\">But</span> <span m=\"2598100\"\
  >you</span> <span m=\"2598220\">can--</span> <span m=\"2598850\">I</span> <span\
  \ m=\"2599150\">mean,</span> <span m=\"2600780\">you</span> <span m=\"2600870\"\
  >can</span> <span m=\"2600990\">follow</span> <span m=\"2601290\">the</span> <span\
  \ m=\"2601380\">proof</span> <span m=\"2601770\">and</span> <span m=\"2601890\"\
  >come</span> <span m=\"2602130\">up</span> <span m=\"2602280\">with</span> <span\
  \ m=\"2602430\">a</span> <span m=\"2602460\">similar</span> <span m=\"2602850\"\
  >formula</span> <span m=\"2603830\">for</span> <span m=\"2604020\">every</span>\
  \ <span m=\"2604260\">equation.</span> <span m=\"2607190\">So</span> <span m=\"\
  2607310\">there's</span> <span m=\"2607490\">a</span> <span m=\"2607520\">general</span>\
  \ <span m=\"2607790\">principle</span> <span m=\"2608210\">here,</span> <span m=\"\
  2608580\">which</span> <span m=\"2608720\">I'll</span> <span m=\"2609620\">discuss</span>\
  \ <span m=\"2610070\">more at</span> <span m=\"2610310\">length</span> <span m=\"\
  2610600\">in</span> <span m=\"2610690\">a</span> <span m=\"2610770\">bit,</span>\
  \ <span m=\"2612030\">that</span> <span m=\"2612500\">for</span> <span m=\"2613280\"\
  >patterns</span> <span m=\"2613880\">that</span> <span m=\"2614060\">are</span>\
  \ <span m=\"2614120\">governed</span> <span m=\"2614450\">by</span> <span m=\"2614630\"\
  >a</span> <span m=\"2614690\">single</span> <span m=\"2615170\">equation--</span>\
  \ <span m=\"2616760\">in</span> <span m=\"2616850\">this</span> <span m=\"2617000\"\
  >case,</span> <span m=\"2617450\">3-APs,</span> <span m=\"2618320\">x</span> <span\
  \ m=\"2618590\">minus</span> <span m=\"2618890\">2y</span> <span m=\"2619310\">plus</span>\
  \ <span m=\"2619565\">z</span> <span m=\"2619820\">equal</span> <span m=\"2620060\"\
  >to</span> <span m=\"2620150\">0--</span> <span m=\"2621260\">patterns</span> <span\
  \ m=\"2621710\">that</span> <span m=\"2621800\">can</span> <span m=\"2621920\">be</span>\
  \ <span m=\"2622010\">governed</span> <span m=\"2622340\">by</span> <span m=\"2622520\"\
  >a</span> <span m=\"2622580\">single</span> <span m=\"2622970\">equation</span>\
  \ <span m=\"2623900\">can</span> <span m=\"2624080\">be</span> <span m=\"2624170\"\
  >controlled</span> <span m=\"2624680\">by</span> <span m=\"2624840\">a</span> <span\
  \ m=\"2624860\">Fourier</span> <span m=\"2625250\">transform.</span></p><p><span\
  \ m=\"2629770\">So</span> <span m=\"2629920\">let's</span> <span m=\"2630130\">begin</span>\
  \ <span m=\"2630580\">our</span> <span m=\"2630820\">proof,</span> <span m=\"2631330\"\
  >the</span> <span m=\"2631790\">Fourier</span> <span m=\"2632270\">analytic</span>\
  \ <span m=\"2632710\">proof</span> <span m=\"2633210\">of</span> <span m=\"2633470\"\
  >Roth's</span> <span m=\"2633825\">theorem</span> <span m=\"2634180\">in</span>\
  \ <span m=\"2634510\">F3</span> <span m=\"2634720\">to the</span> <span m=\"2634870\"\
  >n-th.</span></p><p><span m=\"2635636\">AUDIENCE:</span> <span m=\"2636020\">So</span>\
  \ <span m=\"2636280\">at</span> <span m=\"2636775\">the end,</span> <span m=\"2637270\"\
  >you</span> <span m=\"2637360\">said</span> <span m=\"2638050\">it</span> <span\
  \ m=\"2638120\">was</span> <span m=\"2638260\">going to be</span> <span m=\"2638520\"\
  >connected</span> <span m=\"2638840\">with</span> <span m=\"2639260\">counting the</span>\
  \ <span m=\"2639630\">[INAUDIBLE]</span> <span m=\"2639945\">graph.</span> <span\
  \ m=\"2640260\">Does this</span> <span m=\"2640640\">mean</span> <span m=\"2641121\"\
  >that</span> <span m=\"2641602\">the</span> <span m=\"2642083\">Fourier</span> <span\
  \ m=\"2642564\">transform</span> <span m=\"2643045\">of</span> <span m=\"2643526\"\
  >the</span> <span m=\"2644010\">indicator</span> <span m=\"2644150\">of</span> <span\
  \ m=\"2644480\">A,</span> <span m=\"2644780\">those</span> <span m=\"2645190\">are</span>\
  \ <span m=\"2645600\">exactly the</span> <span m=\"2646020\">eigenvalues</span>\
  \ <span m=\"2646982\">of the</span> <span m=\"2647463\">Cayley</span> <span m=\"\
  2647944\">graph?</span> <span m=\"2648425\">Or is it like</span> <span m=\"2648906\"\
  >[INAUDIBLE]?</span></p><p><span m=\"2649387\">YUFEI ZHAO:</span> <span m=\"2649870\"\
  >OK,</span> <span m=\"2650190\">so</span> <span m=\"2650310\">you're</span> <span\
  \ m=\"2650430\">asking</span> <span m=\"2650700\">about</span> <span m=\"2650880\"\
  >the</span> <span m=\"2650970\">final</span> <span m=\"2651300\">step,</span> <span\
  \ m=\"2651590\">where</span> <span m=\"2652050\">we're</span> <span m=\"2652170\"\
  >talking</span> <span m=\"2652500\">about--</span> <span m=\"2653640\">so</span>\
  \ <span m=\"2653850\">I</span> <span m=\"2653940\">mentioned</span> <span m=\"2654390\"\
  >that</span> <span m=\"2654660\">there</span> <span m=\"2654800\">was</span> <span\
  \ m=\"2654880\">this</span> <span m=\"2654990\">connection</span> <span m=\"2655380\"\
  >between</span> <span m=\"2655650\">counting</span> <span m=\"2655980\">walks</span>\
  \ <span m=\"2656280\">in</span> <span m=\"2656370\">graphs</span> <span m=\"2656700\"\
  >and</span> <span m=\"2656880\">spectral</span> <span m=\"2657195\">graph</span>\
  \ <span m=\"2657510\">theory.</span> <span m=\"2658170\">So</span> <span m=\"2659190\"\
  >you</span> <span m=\"2659340\">can</span> <span m=\"2659490\">check</span> <span\
  \ m=\"2659850\">that,</span> <span m=\"2660150\">if</span> <span m=\"2660360\">you</span>\
  \ <span m=\"2660570\">have</span> <span m=\"2662460\">a</span> <span m=\"2664500\"\
  >subset</span> <span m=\"2665730\">A</span> <span m=\"2666180\">of</span> <span\
  \ m=\"2666720\">an</span> <span m=\"2666840\">abelian</span> <span m=\"2667230\"\
  >group,</span> <span m=\"2668520\">then</span> <span m=\"2669300\">the</span> <span\
  \ m=\"2669770\">Fourier</span> <span m=\"2669950\">transforms</span> <span m=\"\
  2670670\">of</span> <span m=\"2670850\">A</span> <span m=\"2671840\">are</span>\
  \ <span m=\"2672210\">exactly</span> <span m=\"2673380\">the</span> <span m=\"2673530\"\
  >eigenvalues</span> <span m=\"2676750\">of</span> <span m=\"2677890\">the</span>\
  \ <span m=\"2678640\">Cayley</span> <span m=\"2678970\">graph.</span></p><p><span\
  \ m=\"2684090\">AUDIENCE:</span> <span m=\"2684590\">So</span> <span m=\"2684740\"\
  >then</span> <span m=\"2684880\">I</span> <span m=\"2684940\">guess,</span> <span\
  \ m=\"2685950\">have</span> <span m=\"2686150\">we</span> <span m=\"2686350\">done</span>\
  \ <span m=\"2686530\">anything</span> <span m=\"2686950\">so</span> <span m=\"2687190\"\
  >far</span> <span m=\"2687490\">that</span> <span m=\"2688050\">could</span> <span\
  \ m=\"2688220\">have been</span> <span m=\"2688550\">done</span> <span m=\"2688810\"\
  >in</span> <span m=\"2689030\">a</span> <span m=\"2689310\">spectral</span> <span\
  \ m=\"2690260\">way</span> <span m=\"2690520\">yet?</span> <span m=\"2690950\">Well,</span>\
  \ <span m=\"2691210\">I</span> <span m=\"2691300\">guess,</span> <span m=\"2692260\"\
  >where</span> <span m=\"2692540\">is</span> <span m=\"2692650\">the</span> <span\
  \ m=\"2692800\">Fourier</span> <span m=\"2693220\">analysis</span> <span m=\"2693940\"\
  >better</span> <span m=\"2694190\">than the</span> <span m=\"2694645\">spectral</span>\
  \ <span m=\"2695100\">[INAUDIBLE]?</span></p><p><span m=\"2695555\">YUFEI ZHAO:</span>\
  \ <span m=\"2696010\">OK.</span> <span m=\"2696280\">Question,</span> <span m=\"\
  2696540\">where is</span> <span m=\"2696900\">the</span> <span m=\"2696960\">Fourier</span>\
  \ <span m=\"2697440\">analysis</span> <span m=\"2697950\">better</span> <span m=\"\
  2698190\">than</span> <span m=\"2698340\">the</span> <span m=\"2698400\">spectral</span>\
  \ <span m=\"2698790\">posts?</span> <span m=\"2699130\">Well,</span> <span m=\"\
  2699210\">let's</span> <span m=\"2699330\">see</span> <span m=\"2699480\">the</span>\
  \ <span m=\"2699570\">proof</span> <span m=\"2699810\">first.</span> <span m=\"\
  2700170\">And</span> <span m=\"2700440\">then</span> <span m=\"2700590\">you'll</span>\
  \ <span m=\"2700710\">see,</span> <span m=\"2700860\">yeah.</span> <span m=\"2701520\"\
  >So</span> <span m=\"2701880\">there's</span> <span m=\"2702120\">no</span> <span\
  \ m=\"2702270\">graphs</span> <span m=\"2702690\">anymore.</span> <span m=\"2703470\"\
  >So</span> <span m=\"2703590\">we're</span> <span m=\"2703680\">going</span> <span\
  \ m=\"2703760\">to</span> <span m=\"2703860\">work</span> <span m=\"2704070\">inside</span>\
  \ <span m=\"2704520\">F3</span> <span m=\"2704790\">to</span> <span m=\"2704880\"\
  >the</span> <span m=\"2705080\">n-th.</span></p><p><span m=\"2708270\">But</span>\
  \ <span m=\"2708480\">just</span> <span m=\"2708750\">like</span> <span m=\"2708960\"\
  >the</span> <span m=\"2709020\">proof</span> <span m=\"2709620\">of</span> <span\
  \ m=\"2709950\">regularity</span> <span m=\"2710610\">in</span> <span m=\"2710700\"\
  >counting,</span> <span m=\"2711020\">we're</span> <span m=\"2711110\">going to</span>\
  \ <span m=\"2711210\">have</span> <span m=\"2711340\">a</span> <span m=\"2711400\"\
  >counting</span> <span m=\"2711735\">lemma.</span> <span m=\"2712070\">So</span>\
  \ <span m=\"2712740\">all</span> <span m=\"2712890\">of</span> <span m=\"2712980\"\
  >these</span> <span m=\"2713160\">are</span> <span m=\"2713340\">analytic.</span>\
  \ <span m=\"2714240\">And</span> <span m=\"2715950\">at</span> <span m=\"2716040\"\
  >this</span> <span m=\"2716220\">point,</span> <span m=\"2717090\">they</span> <span\
  \ m=\"2717210\">should</span> <span m=\"2717360\">be</span> <span m=\"2717450\"\
  >very</span> <span m=\"2717660\">familiar</span> <span m=\"2718050\">to</span> <span\
  \ m=\"2718140\">you.</span> <span m=\"2719340\">They</span> <span m=\"2719460\"\
  >may</span> <span m=\"2719580\">come</span> <span m=\"2719850\">in</span> <span\
  \ m=\"2719950\">a</span> <span m=\"2719970\">different</span> <span m=\"2720270\"\
  >form.</span> <span m=\"2720660\">They</span> <span m=\"2720780\">may</span> <span\
  \ m=\"2720920\">be</span> <span m=\"2721130\">dressed</span> <span m=\"2721530\"\
  >in</span> <span m=\"2721620\">different</span> <span m=\"2721890\">clothing.</span>\
  \ <span m=\"2722790\">But</span> <span m=\"2723450\">it's</span> <span m=\"2723600\"\
  >still</span> <span m=\"2723850\">a counting</span> <span m=\"2724260\">lemma.</span>\
  \ <span m=\"2724930\">So</span> <span m=\"2724950\">let's</span> <span m=\"2725100\"\
  >see.</span></p><p><span m=\"2734360\">The</span> <span m=\"2734450\">counting</span>\
  \ <span m=\"2734750\">lemma,</span> <span m=\"2735410\">in</span> <span m=\"2735680\"\
  >this</span> <span m=\"2735860\">case,</span> <span m=\"2736190\">says</span> <span\
  \ m=\"2736550\">that</span> <span m=\"2736760\">if</span> <span m=\"2736970\">you</span>\
  \ <span m=\"2737150\">are</span> <span m=\"2737780\">in</span> <span m=\"2739440\"\
  >the</span> <span m=\"2739520\">setting</span> <span m=\"2739940\">of</span> <span\
  \ m=\"2741590\">A</span> <span m=\"2741980\">F3</span> <span m=\"2742250\">to</span>\
  \ <span m=\"2742370\">the</span> <span m=\"2742490\">n-th--</span> <span m=\"2744170\"\
  >and</span> <span m=\"2745010\">I'm</span> <span m=\"2745190\">going</span> <span\
  \ m=\"2745400\">to</span> <span m=\"2745550\">throughout</span> <span m=\"2746420\"\
  >write</span> <span m=\"2747470\">the</span> <span m=\"2747590\">density</span>\
  \ <span m=\"2748100\">of</span> <span m=\"2748280\">A</span> <span m=\"2748730\"\
  >as</span> <span m=\"2749750\">alpha,</span> <span m=\"2753640\">then</span> <span\
  \ m=\"2755290\">let</span> <span m=\"2755470\">me</span> <span m=\"2755590\">write,</span>\
  \ <span m=\"2756460\">let</span> <span m=\"2756580\">me</span> <span m=\"2756700\"\
  >define</span> <span m=\"2757420\">this</span> <span m=\"2758140\">lambda</span>\
  \ <span m=\"2758620\">3</span> <span m=\"2759430\">of</span> <span m=\"2759610\"\
  >A</span> <span m=\"2760924\">to</span> <span m=\"2761362\">be</span> <span m=\"\
  2762670\">the</span> <span m=\"2763210\">function</span> <span m=\"2764170\">which</span>\
  \ <span m=\"2766420\">basically</span> <span m=\"2769190\">counts</span> <span m=\"\
  2770000\">3-APs</span> <span m=\"2773930\">in</span> <span m=\"2774180\">A</span>\
  \ <span m=\"2775700\">but</span> <span m=\"2776210\">with</span> <span m=\"2776480\"\
  >the</span> <span m=\"2776660\">averaging</span> <span m=\"2777470\">normalization.</span>\
  \ <span m=\"2781660\">So</span> <span m=\"2781840\">this</span> <span m=\"2782020\"\
  >is--</span> <span m=\"2782890\">we</span> <span m=\"2783010\">saw</span> <span\
  \ m=\"2783190\">this</span> <span m=\"2783370\">earlier.</span></p><p><span m=\"\
  2786550\">So</span> <span m=\"2786580\">the</span> <span m=\"2786670\">counting</span>\
  \ <span m=\"2787030\">lemma</span> <span m=\"2787840\">says</span> <span m=\"2789430\"\
  >that</span> <span m=\"2792270\">this</span> <span m=\"2792450\">normalized</span>\
  \ <span m=\"2792920\">number</span> <span m=\"2793210\">of</span> <span m=\"2793310\"\
  >3-APs</span> <span m=\"2793550\">in</span> <span m=\"2794010\">A--</span> <span\
  \ m=\"2794900\">so</span> <span m=\"2795210\">including</span> <span m=\"2795690\"\
  >trivial</span> <span m=\"2796050\">3-APs;</span> <span m=\"2796270\">that's</span>\
  \ <span m=\"2796720\">why</span> <span m=\"2797130\">this</span> <span m=\"2797340\"\
  >is</span> <span m=\"2797490\">a</span> <span m=\"2797580\">nice</span> <span m=\"\
  2797970\">analytic</span> <span m=\"2798510\">expression--</span> <span m=\"2799650\"\
  >differs</span> <span m=\"2800610\">from</span> <span m=\"2801810\">what</span>\
  \ <span m=\"2802020\">you</span> <span m=\"2802140\">might</span> <span m=\"2802470\"\
  >guess</span> <span m=\"2802980\">based</span> <span m=\"2803340\">on</span> <span\
  \ m=\"2803520\">density</span> <span m=\"2804050\">alone.</span> <span m=\"2806490\"\
  >This</span> <span m=\"2806700\">difference</span> <span m=\"2807240\">should</span>\
  \ <span m=\"2807480\">be</span> <span m=\"2807600\">small</span> <span m=\"2808710\"\
  >if</span> <span m=\"2809370\">all</span> <span m=\"2809640\">the</span> <span m=\"\
  2809940\">nonzero</span> <span m=\"2810550\">Fourier</span> <span m=\"2810960\"\
  >coefficients</span> <span m=\"2812820\">of</span> <span m=\"2812940\">A</span>\
  \ <span m=\"2813210\">are</span> <span m=\"2813490\">small.</span></p><p><span m=\"\
  2824190\">So</span> <span m=\"2824350\">in</span> <span m=\"2824450\">this</span>\
  \ <span m=\"2824550\">strategy,</span> <span m=\"2825500\">I</span> <span m=\"2825560\"\
  >said</span> <span m=\"2825770\">that</span> <span m=\"2826250\">if--</span> <span\
  \ m=\"2826670\">so</span> <span m=\"2826910\">the</span> <span m=\"2827000\">counting</span>\
  \ <span m=\"2827330\">lemma</span> <span m=\"2827660\">tells</span> <span m=\"2827870\"\
  >you,</span> <span m=\"2828080\">if</span> <span m=\"2828440\">A</span> <span m=\"\
  2828620\">is</span> <span m=\"2828770\">Fourier</span> <span m=\"2829130\">uniform,</span>\
  \ <span m=\"2830330\">then</span> <span m=\"2830640\">it is</span> <span m=\"2830770\"\
  >pseudorandom.</span> <span m=\"2831550\">And</span> <span m=\"2831680\">this</span>\
  \ <span m=\"2831830\">is</span> <span m=\"2831950\">where</span> <span m=\"2832400\"\
  >it</span> <span m=\"2832460\">comes</span> <span m=\"2832730\">in.</span> <span\
  \ m=\"2833630\">If</span> <span m=\"2833840\">A</span> <span m=\"2834050\">has</span>\
  \ <span m=\"2834500\">all</span> <span m=\"2834710\">small</span> <span m=\"2835140\"\
  >Fourier</span> <span m=\"2835490\">coefficients,</span> <span m=\"2836940\">then</span>\
  \ <span m=\"2837080\">you</span> <span m=\"2837170\">have</span> <span m=\"2837320\"\
  >a</span> <span m=\"2837380\">counting</span> <span m=\"2837665\">lemma,</span>\
  \ <span m=\"2839020\">which</span> <span m=\"2839200\">tells</span> <span m=\"2839500\"\
  >you</span> <span m=\"2839890\">that</span> <span m=\"2840550\">the</span> <span\
  \ m=\"2840640\">counts</span> <span m=\"2840960\">of</span> <span m=\"2841070\"\
  >A</span> <span m=\"2841270\">should</span> <span m=\"2841480\">not</span> <span\
  \ m=\"2841660\">be</span> <span m=\"2841810\">so</span> <span m=\"2842050\">different</span>\
  \ <span m=\"2842500\">from</span> <span m=\"2844030\">the</span> <span m=\"2844120\"\
  >guess</span> <span m=\"2844750\">based</span> <span m=\"2845110\">on</span> <span\
  \ m=\"2845530\">density.</span></p><p><span m=\"2854290\">So</span> <span m=\"2854410\"\
  >the</span> <span m=\"2854500\">proof</span> <span m=\"2855460\">is</span> <span\
  \ m=\"2856170\">very</span> <span m=\"2856390\">short.</span> <span m=\"2856880\"\
  >It's</span> <span m=\"2856930\">based</span> <span m=\"2857290\">on</span> <span\
  \ m=\"2857500\">the</span> <span m=\"2857650\">identity</span> <span m=\"2858430\"\
  >that</span> <span m=\"2858640\">we</span> <span m=\"2858970\">saw</span> <span\
  \ m=\"2859420\">earlier.</span> <span m=\"2861310\">The</span> <span m=\"2862210\"\
  >3-AP</span> <span m=\"2862900\">count</span> <span m=\"2863440\">of</span> <span\
  \ m=\"2863620\">A</span> <span m=\"2865000\">by</span> <span m=\"2865270\">the</span>\
  \ <span m=\"2865450\">identity</span> <span m=\"2865960\">earlier</span> <span m=\"\
  2867040\">is</span> <span m=\"2867490\">simply</span> <span m=\"2868120\">the</span>\
  \ <span m=\"2868390\">third</span> <span m=\"2868810\">power</span> <span m=\"2869860\"\
  >of</span> <span m=\"2870210\">the</span> <span m=\"2870420\">Fourier</span> <span\
  \ m=\"2870790\">transforms.</span> <span m=\"2875180\">And</span> <span m=\"2876740\"\
  >all</span> <span m=\"2876890\">of</span> <span m=\"2876980\">these</span> <span\
  \ m=\"2877160\">calculations</span> <span m=\"2877770\">should</span> <span m=\"\
  2877960\">be</span> <span m=\"2878090\">reminiscent,</span> <span m=\"2878630\"\
  >because</span> <span m=\"2878930\">we've</span> <span m=\"2879170\">done</span>\
  \ <span m=\"2879440\">these</span> <span m=\"2879620\">kind</span> <span m=\"2879830\"\
  >of</span> <span m=\"2879890\">calculations</span> <span m=\"2880460\">in</span>\
  \ <span m=\"2880550\">some</span> <span m=\"2880820\">form</span> <span m=\"2881090\"\
  >or</span> <span m=\"2881150\">another</span> <span m=\"2881780\">earlier</span>\
  \ <span m=\"2882110\">in</span> <span m=\"2882200\">this</span> <span m=\"2882380\"\
  >course.</span> <span m=\"2883460\">So</span> <span m=\"2883730\">we're</span> <span\
  \ m=\"2883850\">going</span> <span m=\"2884000\">to</span> <span m=\"2884060\">separate</span>\
  \ <span m=\"2884660\">out</span> <span m=\"2885380\">the</span> <span m=\"2885500\"\
  >main</span> <span m=\"2885830\">term</span> <span m=\"2886370\">and</span> <span\
  \ m=\"2886490\">subsequent</span> <span m=\"2887030\">terms.</span></p><p><span\
  \ m=\"2887690\">So</span> <span m=\"2887960\">the</span> <span m=\"2888050\">main</span>\
  \ <span m=\"2888380\">term</span> <span m=\"2889250\">is</span> <span m=\"2890090\"\
  >the</span> <span m=\"2890180\">one</span> <span m=\"2890420\">corresponding</span>\
  \ <span m=\"2891050\">to</span> <span m=\"2892250\">r</span> <span m=\"2892430\"\
  >equals</span> <span m=\"2892730\">to</span> <span m=\"2892800\">0.</span> <span\
  \ m=\"2893750\">So</span> <span m=\"2893870\">that's</span> <span m=\"2894110\"\
  >the</span> <span m=\"2894200\">density.</span> <span m=\"2895970\">And</span> <span\
  \ m=\"2897170\">all</span> <span m=\"2897290\">the</span> <span m=\"2897410\">other</span>\
  \ <span m=\"2897620\">terms</span> <span m=\"2898200\">I'm</span> <span m=\"2898400\"\
  >going</span> <span m=\"2898640\">to</span> <span m=\"2899030\">lump</span> <span\
  \ m=\"2899300\">together</span> <span m=\"2900500\">into</span> <span m=\"2901250\"\
  >this</span> <span m=\"2901660\">sum.</span> <span m=\"2904310\">So</span> <span\
  \ m=\"2907390\">we</span> <span m=\"2907570\">now</span> <span m=\"2907870\">know</span>\
  \ <span m=\"2908770\">that</span> <span m=\"2913000\">the</span> <span m=\"2913190\"\
  >difference</span> <span m=\"2913610\">we're</span> <span m=\"2913730\">trying</span>\
  \ <span m=\"2914000\">to</span> <span m=\"2914090\">bound</span> <span m=\"2915020\"\
  >is</span> <span m=\"2915800\">upper</span> <span m=\"2916070\">bounded</span> <span\
  \ m=\"2916850\">by</span> <span m=\"2918770\">the</span> <span m=\"2919820\">third</span>\
  \ <span m=\"2920300\">moment</span> <span m=\"2921320\">of</span> <span m=\"2921410\"\
  >the</span> <span m=\"2921530\">absolute</span> <span m=\"2922010\">values</span>\
  \ <span m=\"2924250\">of</span> <span m=\"2926650\">the</span> <span m=\"2927040\"\
  >Fourier</span> <span m=\"2927850\">transform.</span> <span m=\"2930730\">And I\
  \ want to</span> <span m=\"2931030\">upper</span> <span m=\"2931240\">bound</span>\
  \ <span m=\"2931450\">this</span> <span m=\"2931600\">quantity</span> <span m=\"\
  2931970\">here,</span> <span m=\"2933040\">assuming</span> <span m=\"2933790\">that</span>\
  \ <span m=\"2934090\">all</span> <span m=\"2934240\">of</span> <span m=\"2934300\"\
  >these</span> <span m=\"2934510\">Fourier</span> <span m=\"2934810\">coefficients</span>\
  \ <span m=\"2935530\">are</span> <span m=\"2935680\">small.</span></p><p><span m=\"\
  2938320\">We've</span> <span m=\"2938440\">also</span> <span m=\"2938650\">done</span>\
  \ <span m=\"2938800\">this</span> <span m=\"2938890\">kind</span> <span m=\"2939070\"\
  >of</span> <span m=\"2939130\">calculations</span> <span m=\"2939640\">before.</span>\
  \ <span m=\"2940540\">So</span> <span m=\"2940690\">where</span> <span m=\"2940870\"\
  >have</span> <span m=\"2940990\">we</span> <span m=\"2941080\">seen</span> <span\
  \ m=\"2941260\">this</span> <span m=\"2941380\">before?</span> <span m=\"2946310\"\
  >We</span> <span m=\"2946460\">saw</span> <span m=\"2946700\">this</span> <span\
  \ m=\"2946850\">calculation</span> <span m=\"2947480\">earlier</span> <span m=\"\
  2947710\">in</span> <span m=\"2947840\">the</span> <span m=\"2947900\">class</span>\
  \ <span m=\"2948240\">with</span> <span m=\"2948360\">the</span> <span m=\"2948440\"\
  >3</span> <span m=\"2948740\">replaced</span> <span m=\"2949130\">by</span> <span\
  \ m=\"2949280\">a</span> <span m=\"2949340\">4.</span> <span m=\"2955640\">So</span>\
  \ <span m=\"2955820\">in</span> <span m=\"2955910\">counting</span> <span m=\"2956300\"\
  >four</span> <span m=\"2956540\">cycles</span> <span m=\"2957050\">in a</span> <span\
  \ m=\"2957140\">proof</span> <span m=\"2957560\">equivalent</span> <span m=\"2958160\"\
  >of</span> <span m=\"2958220\">quasirandomness,</span> <span m=\"2959470\">we</span>\
  \ <span m=\"2959600\">said</span> <span m=\"2959840\">that,</span> <span m=\"2960140\"\
  >if</span> <span m=\"2960500\">all</span> <span m=\"2960650\">the</span> <span m=\"\
  2961100\">eigenvalues</span> <span m=\"2961940\">other</span> <span m=\"2962090\"\
  >than</span> <span m=\"2962360\">the top one</span> <span m=\"2962810\">are</span>\
  \ <span m=\"2962900\">small,</span> <span m=\"2963720\">then</span> <span m=\"2964010\"\
  >you</span> <span m=\"2964310\">can</span> <span m=\"2964520\">count</span> <span\
  \ m=\"2965210\">four</span> <span m=\"2965510\">cycles.</span> <span m=\"2966980\"\
  >It's</span> <span m=\"2967070\">the</span> <span m=\"2967130\">same</span> <span\
  \ m=\"2967310\">proof.</span></p><p><span m=\"2968320\">And</span> <span m=\"2968480\"\
  >remember,</span> <span m=\"2969180\">in</span> <span m=\"2969320\">that</span>\
  \ <span m=\"2969470\">proof,</span> <span m=\"2970250\">there</span> <span m=\"\
  2970370\">was</span> <span m=\"2970550\">a</span> <span m=\"2971750\">important</span>\
  \ <span m=\"2972200\">trick,</span> <span m=\"2972530\">where</span> <span m=\"\
  2973190\">you</span> <span m=\"2973310\">do</span> <span m=\"2973460\">not</span>\
  \ <span m=\"2973820\">uniformly</span> <span m=\"2974510\">bound</span> <span m=\"\
  2975440\">each</span> <span m=\"2975680\">term</span> <span m=\"2976340\">by</span>\
  \ <span m=\"2976610\">the</span> <span m=\"2976700\">max,</span> <span m=\"2977470\"\
  >because</span> <span m=\"2977700\">then</span> <span m=\"2977870\">you</span> <span\
  \ m=\"2977960\">lose.</span> <span m=\"2978470\">You</span> <span m=\"2978590\"\
  >lose</span> <span m=\"2978830\">by</span> <span m=\"2978980\">an</span> <span m=\"\
  2979100\">extra</span> <span m=\"2979430\">factor</span> <span m=\"2979740\">of</span>\
  \ <span m=\"2979820\">n that</span> <span m=\"2980160\">you</span> <span m=\"2980240\"\
  >don't</span> <span m=\"2980420\">want.</span> <span m=\"2980900\">So</span> <span\
  \ m=\"2981110\">you</span> <span m=\"2981290\">only</span> <span m=\"2981530\">take</span>\
  \ <span m=\"2981860\">out</span> <span m=\"2982640\">one</span> <span m=\"2982910\"\
  >factor.</span></p><p><span m=\"2985100\">So</span> <span m=\"2985240\">you</span>\
  \ <span m=\"2985340\">take</span> <span m=\"2985640\">out</span> <span m=\"2986540\"\
  >one</span> <span m=\"2986780\">factor.</span> <span m=\"2993840\">And</span> <span\
  \ m=\"2994260\">you</span> <span m=\"2994410\">keep</span> <span m=\"2994740\">the</span>\
  \ <span m=\"2994860\">rest</span> <span m=\"2995440\">in there.</span> <span m=\"\
  2996900\">In fact,</span> <span m=\"2998260\">I</span> <span m=\"2998500\">can</span>\
  \ <span m=\"2998630\">be</span> <span m=\"2998750\">more</span> <span m=\"2998960\"\
  >generous</span> <span m=\"2999530\">and</span> <span m=\"2999680\">even</span>\
  \ <span m=\"2999980\">throw</span> <span m=\"3000310\">the</span> <span m=\"3001210\"\
  >r</span> <span m=\"3001390\">equal</span> <span m=\"3001660\">to</span> <span m=\"\
  3001750\">0</span> <span m=\"3002080\">term</span> <span m=\"3002560\">back</span>\
  \ <span m=\"3002650\">in.</span></p><p><span m=\"3006460\">And now,</span> <span\
  \ m=\"3007420\">by</span> <span m=\"3008440\">Plancherel--</span> <span m=\"3010950\"\
  >so by</span> <span m=\"3011390\">Plancherel/Parseval,</span> <span m=\"3014390\"\
  >this</span> <span m=\"3014780\">here</span> <span m=\"3015290\">is</span> <span\
  \ m=\"3015470\">equal</span> <span m=\"3015860\">to</span> <span m=\"3016670\">the</span>\
  \ <span m=\"3016850\">expectation</span> <span m=\"3018050\">of</span> <span m=\"\
  3022040\">the</span> <span m=\"3022230\">indicator</span> <span m=\"3022740\">function</span>\
  \ <span m=\"3023060\">of</span> <span m=\"3023180\">A</span> <span m=\"3023270\"\
  >squared.</span> <span m=\"3023910\">So</span> <span m=\"3024080\">you</span> <span\
  \ m=\"3024650\">take</span> <span m=\"3024890\">this--</span> <span m=\"3025775\"\
  >you</span> <span m=\"3026210\">go</span> <span m=\"3026390\">back</span> <span\
  \ m=\"3026570\">to</span> <span m=\"3026660\">physical</span> <span m=\"3027050\"\
  >space,</span> <span m=\"3027770\">and</span> <span m=\"3027890\">that's</span>\
  \ <span m=\"3028090\">simply</span> <span m=\"3028460\">the</span> <span m=\"3028550\"\
  >density.</span> <span m=\"3030170\">So</span> <span m=\"3030410\">then</span> <span\
  \ m=\"3030620\">that</span> <span m=\"3030740\">proves</span> <span m=\"3033320\"\
  >the</span> <span m=\"3033450\">theorem.</span></p><p><span m=\"3039300\">So</span>\
  \ <span m=\"3039420\">the</span> <span m=\"3039510\">moral</span> <span m=\"3039840\"\
  >of</span> <span m=\"3039930\">the</span> <span m=\"3039990\">counting</span> <span\
  \ m=\"3040330\">lemma</span> <span m=\"3040560\">is</span> <span m=\"3040650\">the</span>\
  \ <span m=\"3040740\">same</span> <span m=\"3041010\">as</span> <span m=\"3041130\"\
  >the</span> <span m=\"3041220\">one</span> <span m=\"3041550\">that</span> <span\
  \ m=\"3041700\">we've</span> <span m=\"3041880\">seen</span> <span m=\"3042090\"\
  >before when</span> <span m=\"3042550\">we</span> <span m=\"3042600\">discussed</span>\
  \ <span m=\"3043110\">graphs.</span> <span m=\"3043500\">If</span> <span m=\"3043650\"\
  >you're</span> <span m=\"3043830\">in</span> <span m=\"3043950\">pseudorandom,</span>\
  \ <span m=\"3044820\">then</span> <span m=\"3045180\">you</span> <span m=\"3045270\"\
  >have</span> <span m=\"3045420\">good</span> <span m=\"3045600\">counting.</span>\
  \ <span m=\"3046440\">And</span> <span m=\"3046610\">here,</span> <span m=\"3046860\"\
  >pseudorandom</span> <span m=\"3047730\">means</span> <span m=\"3048090\">having</span>\
  \ <span m=\"3048900\">small</span> <span m=\"3049500\">Fourier</span> <span m=\"\
  3049890\">coefficients,</span> <span m=\"3050760\">uniformly</span> <span m=\"3051300\"\
  >small</span> <span m=\"3051840\">Fourier</span> <span m=\"3052200\">coefficients.</span></p><p><span\
  \ m=\"3055040\">So</span> <span m=\"3055100\">now,</span> <span m=\"3055250\">let's</span>\
  \ <span m=\"3055400\">begin</span> <span m=\"3055660\">the</span> <span m=\"3055730\"\
  >proof</span> <span m=\"3055940\">of</span> <span m=\"3056000\">Roth's</span> <span\
  \ m=\"3056480\">theorem.</span> <span m=\"3057890\">The</span> <span m=\"3058020\"\
  >Roth's</span> <span m=\"3058450\">theorem</span> <span m=\"3058830\">proof</span>\
  \ <span m=\"3058940\">will</span> <span m=\"3059060\">have</span> <span m=\"3059330\"\
  >three</span> <span m=\"3059510\">steps.</span> <span m=\"3061858\">The</span> <span\
  \ m=\"3062340\">first</span> <span m=\"3062480\">step,</span> <span m=\"3066270\"\
  >we</span> <span m=\"3066390\">will</span> <span m=\"3067200\">observe</span> <span\
  \ m=\"3067680\">that</span> <span m=\"3068040\">if</span> <span m=\"3068310\">you're\
  \ in</span> <span m=\"3068600\">the</span> <span m=\"3068690\">3-AP-free</span>\
  \ <span m=\"3069640\">set,</span> <span m=\"3072020\">then</span> <span m=\"3072870\"\
  >there</span> <span m=\"3073020\">exists</span> <span m=\"3073560\">a</span> <span\
  \ m=\"3073680\">large</span> <span m=\"3074340\">Fourier</span> <span m=\"3074700\"\
  >coefficient.</span></p><p><span m=\"3086050\">Throughout,</span> <span m=\"3086650\"\
  >I'm</span> <span m=\"3086800\">going</span> <span m=\"3086910\">to</span> <span\
  \ m=\"3087010\">use</span> <span m=\"3087320\">uppercase</span> <span m=\"3087910\"\
  >N</span> <span m=\"3088240\">to</span> <span m=\"3088420\">denote</span> <span\
  \ m=\"3088990\">the</span> <span m=\"3089110\">size</span> <span m=\"3089680\">of</span>\
  \ <span m=\"3089860\">the</span> <span m=\"3090130\">ambient</span> <span m=\"3090550\"\
  >group.</span> <span m=\"3092620\">And</span> <span m=\"3092770\">specifically,</span>\
  \ <span m=\"3093400\">we</span> <span m=\"3093520\">will</span> <span m=\"3093670\"\
  >prove</span> <span m=\"3094000\">the</span> <span m=\"3094090\">following.</span>\
  \ <span m=\"3096560\">And</span> <span m=\"3096910\">also</span> <span m=\"3097210\"\
  >throughout,</span> <span m=\"3097990\">A</span> <span m=\"3098350\">is a</span>\
  \ <span m=\"3098680\">subset</span> <span m=\"3099280\">of</span> <span m=\"3100060\"\
  >F3</span> <span m=\"3100380\">to the</span> <span m=\"3100860\">n-th</span> <span\
  \ m=\"3101320\">and</span> <span m=\"3101830\">with</span> <span m=\"3102070\">density</span>\
  \ <span m=\"3104730\">alpha.</span> <span m=\"3105075\">So</span> <span m=\"3105420\"\
  >I'll</span> <span m=\"3105550\">keep</span> <span m=\"3105790\">this</span> <span\
  \ m=\"3106090\">convention</span> <span m=\"3106680\">throughout</span> <span m=\"\
  3107000\">this</span> <span m=\"3107190\">proof.</span></p><p><span m=\"3110380\"\
  >We</span> <span m=\"3110500\">will</span> <span m=\"3110620\">show</span> <span\
  \ m=\"3110860\">that</span> <span m=\"3111520\">if</span> <span m=\"3112420\">A</span>\
  \ <span m=\"3112690\">is</span> <span m=\"3113020\">3-AP-free</span> <span m=\"\
  3119830\">and</span> <span m=\"3122734\">N</span> <span m=\"3123540\">is</span>\
  \ <span m=\"3123880\">at</span> <span m=\"3123970\">least</span> <span m=\"3124900\"\
  >2</span> <span m=\"3125230\">to</span> <span m=\"3125380\">the</span> <span m=\"\
  3127210\">alpha</span> <span m=\"3127510\">to</span> <span m=\"3127630\">the</span>\
  \ <span m=\"3127990\">minus</span> <span m=\"3128290\">2--</span> <span m=\"3129030\"\
  >so</span> <span m=\"3129310\">N is</span> <span m=\"3129700\">at</span> <span m=\"\
  3129790\">least</span> <span m=\"3130480\">somewhat</span> <span m=\"3130810\">large--</span>\
  \ <span m=\"3131680\">then</span> <span m=\"3133030\">there</span> <span m=\"3133210\"\
  >exists</span> <span m=\"3133900\">a</span> <span m=\"3133990\">nonzero</span> <span\
  \ m=\"3134860\">r</span> <span m=\"3136360\">such</span> <span m=\"3136750\">that</span>\
  \ <span m=\"3137860\">the</span> <span m=\"3138100\">r-th</span> <span m=\"3138580\"\
  >Fourier</span> <span m=\"3139000\">coefficient</span> <span m=\"3141400\">is</span>\
  \ <span m=\"3141790\">at</span> <span m=\"3141910\">least</span> <span m=\"3142990\"\
  >alpha</span> <span m=\"3143230\">squared</span> <span m=\"3144040\">over</span>\
  \ <span m=\"3144280\">2.</span> <span m=\"3147450\">If</span> <span m=\"3147630\"\
  >you're</span> <span m=\"3147840\">3-AP-free,</span> <span m=\"3148770\">free</span>\
  \ <span m=\"3149400\">then</span> <span m=\"3150420\">provided</span> <span m=\"\
  3150900\">that</span> <span m=\"3151320\">you're</span> <span m=\"3151440\">working</span>\
  \ <span m=\"3151830\">in</span> <span m=\"3151920\">a</span> <span m=\"3151950\"\
  >large</span> <span m=\"3152250\">enough</span> <span m=\"3152970\">ambient</span>\
  \ <span m=\"3153330\">space,</span> <span m=\"3154290\">you</span> <span m=\"3154380\"\
  >always</span> <span m=\"3154740\">have</span> <span m=\"3155220\">some</span> <span\
  \ m=\"3155790\">large</span> <span m=\"3156300\">Fourier</span> <span m=\"3156720\"\
  >coefficient.</span></p><p><span m=\"3160601\">So</span> <span m=\"3161080\">the</span>\
  \ <span m=\"3161170\">proof</span> <span m=\"3162110\">is</span> <span m=\"3162310\"\
  >essentially--</span> <span m=\"3163450\">well,</span> <span m=\"3163720\">this</span>\
  \ <span m=\"3163900\">claim</span> <span m=\"3164200\">is</span> <span m=\"3164320\"\
  >essentially</span> <span m=\"3164710\">a</span> <span m=\"3164740\">corollary</span>\
  \ <span m=\"3165280\">of</span> <span m=\"3165370\">counting</span> <span m=\"3165750\"\
  >lemma,</span> <span m=\"3170230\">by</span> <span m=\"3170550\">the</span> <span\
  \ m=\"3170640\">counting</span> <span m=\"3170980\">lemma.</span> <span m=\"3174820\"\
  >And</span> <span m=\"3175990\">using</span> <span m=\"3176290\">the</span> <span\
  \ m=\"3176350\">fact</span> <span m=\"3176710\">that</span> <span m=\"3177040\"\
  >in</span> <span m=\"3177160\">a</span> <span m=\"3177220\">3-AP-free</span> <span\
  \ m=\"3177860\">set,</span> <span m=\"3178870\">what</span> <span m=\"3179050\"\
  >is</span> <span m=\"3179290\">the</span> <span m=\"3179500\">quantity</span> <span\
  \ m=\"3180100\">lambda</span> <span m=\"3180550\">3</span> <span m=\"3180910\">of</span>\
  \ <span m=\"3181030\">A?</span> <span m=\"3182611\">Up</span> <span m=\"3183050\"\
  >there,</span> <span m=\"3184150\">you</span> <span m=\"3184360\">only</span> <span\
  \ m=\"3184720\">have</span> <span m=\"3185620\">the</span> <span m=\"3185710\">trivial</span>\
  \ <span m=\"3186190\">3-APs</span> <span m=\"3186820\">present.</span> <span m=\"\
  3188170\">So</span> <span m=\"3189430\">this</span> <span m=\"3189610\">quantity</span>\
  \ <span m=\"3190030\">lambda</span> <span m=\"3190870\">must</span> <span m=\"3191230\"\
  >then</span> <span m=\"3191590\">be</span> <span m=\"3192330\">the</span> <span\
  \ m=\"3192460\">size</span> <span m=\"3193000\">of</span> <span m=\"3193120\">A</span>\
  \ <span m=\"3193600\">divided</span> <span m=\"3193990\">by</span> <span m=\"3194410\"\
  >N</span> <span m=\"3194560\">squared</span> <span m=\"3195600\">or</span> <span\
  \ m=\"3195730\">alpha</span> <span m=\"3196150\">over</span> <span m=\"3196420\"\
  >N,</span> <span m=\"3197510\">which</span> <span m=\"3197770\">are</span> <span\
  \ m=\"3198640\">precisely</span> <span m=\"3200260\">counting</span> <span m=\"\
  3200850\">the</span> <span m=\"3200920\">trivial</span> <span m=\"3201770\">3-APs.</span></p><p><span\
  \ m=\"3206040\">So</span> <span m=\"3206330\">by</span> <span m=\"3206450\">the</span>\
  \ <span m=\"3206570\">counting</span> <span m=\"3206890\">lemma,</span> <span m=\"\
  3207740\">then</span> <span m=\"3208010\">we</span> <span m=\"3208220\">have</span>\
  \ <span m=\"3208880\">that</span> <span m=\"3209720\">the</span> <span m=\"3210860\"\
  >upper</span> <span m=\"3211100\">bound</span> <span m=\"3212000\">on</span> <span\
  \ m=\"3212120\">the</span> <span m=\"3212180\">right</span> <span m=\"3212390\"\
  >hand</span> <span m=\"3212540\">side,</span> <span m=\"3213360\">which</span> <span\
  \ m=\"3213440\">we</span> <span m=\"3213490\">now</span> <span m=\"3213710\">write</span>\
  \ <span m=\"3214500\">alpha</span> <span m=\"3215180\">max</span> <span m=\"3217820\"\
  >over</span> <span m=\"3218060\">nonzero</span> <span m=\"3218660\">r's,</span>\
  \ <span m=\"3222580\">is</span> <span m=\"3223120\">at</span> <span m=\"3223240\"\
  >least</span> <span m=\"3225210\">alpha</span> <span m=\"3225460\">cubed</span>\
  \ <span m=\"3226090\">minus</span> <span m=\"3227290\">the</span> <span m=\"3228400\"\
  >lambda</span> <span m=\"3228790\">3</span> <span m=\"3229060\">term,</span> <span\
  \ m=\"3229660\">which</span> <span m=\"3229840\">should</span> <span m=\"3229990\"\
  >be</span> <span m=\"3231260\">alpha</span> <span m=\"3231880\">over</span> <span\
  \ m=\"3232150\">N.</span> <span m=\"3234760\">So</span> <span m=\"3234920\">provided</span>\
  \ <span m=\"3235370\">that</span> <span m=\"3235750\">N</span> <span m=\"3236090\"\
  >is</span> <span m=\"3236450\">large</span> <span m=\"3236810\">enough--</span>\
  \ <span m=\"3237380\">big</span> <span m=\"3237650\">N</span> <span m=\"3237830\"\
  >is</span> <span m=\"3237980\">large</span> <span m=\"3238220\">enough--</span>\
  \ <span m=\"3238890\">then</span> <span m=\"3239060\">the</span> <span m=\"3239180\"\
  >trivial</span> <span m=\"3239570\">3-APs</span> <span m=\"3240170\">should</span>\
  \ <span m=\"3240410\">not</span> <span m=\"3240680\">contribute</span> <span m=\"\
  3241280\">very</span> <span m=\"3241520\">much.</span> <span m=\"3242450\">So</span>\
  \ <span m=\"3242630\">I</span> <span m=\"3242720\">can</span> <span m=\"3242870\"\
  >lower</span> <span m=\"3243110\">bound</span> <span m=\"3243620\">the</span> <span\
  \ m=\"3243710\">right</span> <span m=\"3243890\">hand</span> <span m=\"3244070\"\
  >side</span> <span m=\"3244760\">by,</span> <span m=\"3246240\">let's</span> <span\
  \ m=\"3246500\">say,</span> <span m=\"3246770\">alpha</span> <span m=\"3247010\"\
  >3--</span> <span m=\"3247570\">alpha</span> <span m=\"3247870\">cubed</span> <span\
  \ m=\"3248270\">over</span> <span m=\"3248530\">2.</span> <span m=\"3250020\">So</span>\
  \ <span m=\"3250140\">then</span> <span m=\"3250260\">you</span> <span m=\"3250380\"\
  >deduce</span> <span m=\"3250740\">the</span> <span m=\"3250830\">conclusion.</span></p><p><span\
  \ m=\"3254160\">I</span> <span m=\"3254290\">want</span> <span m=\"3254440\">you</span>\
  \ <span m=\"3254520\">to</span> <span m=\"3254560\">think</span> <span m=\"3254720\"\
  >about</span> <span m=\"3254870\">how</span> <span m=\"3255140\">this</span> <span\
  \ m=\"3255320\">proof</span> <span m=\"3255560\">is</span> <span m=\"3255680\">related</span>\
  \ <span m=\"3256070\">to</span> <span m=\"3256430\">Szemer\xE9di's</span> <span\
  \ m=\"3257000\">graph</span> <span m=\"3257590\">regularity</span> <span m=\"3258200\"\
  >lemma.</span> <span m=\"3259310\">The</span> <span m=\"3259460\">analogy</span>\
  \ <span m=\"3259850\">will</span> <span m=\"3260000\">break</span> <span m=\"3260240\"\
  >down</span> <span m=\"3260450\">at</span> <span m=\"3260510\">some</span> <span\
  \ m=\"3260750\">point.</span> <span m=\"3261020\">But</span> <span m=\"3261740\"\
  >we've</span> <span m=\"3261920\">seen</span> <span m=\"3262130\">this</span> <span\
  \ m=\"3262250\">step</span> <span m=\"3262490\">before</span> <span m=\"3262790\"\
  >as</span> <span m=\"3262900\">well.</span> <span m=\"3263780\">From</span> <span\
  \ m=\"3265310\">lack</span> <span m=\"3265670\">of</span> <span m=\"3266240\">3-APs,</span>\
  \ <span m=\"3266900\">you</span> <span m=\"3267050\">extract</span> <span m=\"3267890\"\
  >some</span> <span m=\"3269060\">useful</span> <span m=\"3269480\">information</span>\
  \ <span m=\"3270050\">and</span> <span m=\"3270260\">from</span> <span m=\"3270440\"\
  >this</span> <span m=\"3270650\">will</span> <span m=\"3270920\">extract</span>\
  \ <span m=\"3271400\">some</span> <span m=\"3271670\">structure.</span></p><p><span\
  \ m=\"3272980\">And</span> <span m=\"3273100\">the</span> <span m=\"3273170\">structure</span>\
  \ <span m=\"3273560\">here--</span> <span m=\"3274430\">and</span> <span m=\"3274580\"\
  >this</span> <span m=\"3274730\">is</span> <span m=\"3274850\">where</span> <span\
  \ m=\"3275090\">the</span> <span m=\"3275180\">proof</span> <span m=\"3275480\"\
  >now</span> <span m=\"3275960\">diverges</span> <span m=\"3276590\">from</span>\
  \ <span m=\"3277220\">that</span> <span m=\"3277400\">of</span> <span m=\"3277550\"\
  >regularity--</span> <span m=\"3280190\">having</span> <span m=\"3280550\">a</span>\
  \ <span m=\"3280610\">large</span> <span m=\"3281460\">Fourier</span> <span m=\"\
  3281900\">coefficient</span> <span m=\"3286540\">will</span> <span m=\"3286660\"\
  >now</span> <span m=\"3286960\">imply</span> <span m=\"3288480\">a</span> <span\
  \ m=\"3288610\">density</span> <span m=\"3289150\">increment</span> <span m=\"3295260\"\
  >on</span> <span m=\"3296070\">a</span> <span m=\"3296160\">hyperplane.</span> <span\
  \ m=\"3304730\">Specifically,</span> <span m=\"3306110\">if</span> <span m=\"3306320\"\
  >you</span> <span m=\"3306470\">have--</span> <span m=\"3311390\">so</span> <span\
  \ m=\"3312200\">keeping</span> <span m=\"3312470\">the</span> <span m=\"3312560\"\
  >same</span> <span m=\"3312800\">convention</span> <span m=\"3313210\">as</span>\
  \ <span m=\"3313460\">before,</span> <span m=\"3315070\">if</span> <span m=\"3316660\"\
  >the</span> <span m=\"3317320\">Fourier</span> <span m=\"3317800\">coefficient</span>\
  \ <span m=\"3318430\">of</span> <span m=\"3318700\">A</span> <span m=\"3319910\"\
  >at</span> <span m=\"3320380\">r</span> <span m=\"3321100\">is</span> <span m=\"\
  3321460\">at</span> <span m=\"3321580\">least</span> <span m=\"3322240\">delta</span>\
  \ <span m=\"3323380\">for</span> <span m=\"3323530\">some</span> <span m=\"3327390\"\
  >nonzero</span> <span m=\"3327900\">r,</span> <span m=\"3329310\">then</span> <span\
  \ m=\"3332110\">A</span> <span m=\"3332440\">has</span> <span m=\"3332860\">density</span>\
  \ <span m=\"3337700\">at</span> <span m=\"3337840\">least</span> <span m=\"3338830\"\
  >alpha</span> <span m=\"3339190\">plus</span> <span m=\"3340510\">delta</span> <span\
  \ m=\"3340870\">over</span> <span m=\"3341170\">2</span> <span m=\"3342160\">when</span>\
  \ <span m=\"3342520\">restricted</span> <span m=\"3343120\">to</span> <span m=\"\
  3343300\">a</span> <span m=\"3343360\">hyperplane.</span></p><p><span m=\"3355280\"\
  >So</span> <span m=\"3355450\">if</span> <span m=\"3355630\">you</span> <span m=\"\
  3355750\">have</span> <span m=\"3355870\">a</span> <span m=\"3355930\">large</span>\
  \ <span m=\"3356230\">Fourier</span> <span m=\"3356560\">coefficient,</span> <span\
  \ m=\"3357640\">then</span> <span m=\"3357970\">I</span> <span m=\"3358090\">can</span>\
  \ <span m=\"3358240\">pass</span> <span m=\"3358660\">down</span> <span m=\"3358900\"\
  >to</span> <span m=\"3358990\">a</span> <span m=\"3359050\">smaller</span> <span\
  \ m=\"3359620\">part</span> <span m=\"3359860\">of</span> <span m=\"3359920\">the</span>\
  \ <span m=\"3360010\">space</span> <span m=\"3360730\">where</span> <span m=\"3360910\"\
  >the</span> <span m=\"3361030\">density</span> <span m=\"3361450\">of</span> <span\
  \ m=\"3361570\">A</span> <span m=\"3361770\">goes</span> <span m=\"3362110\">up</span>\
  \ <span m=\"3362260\">significantly.</span> <span m=\"3370210\">To</span> <span\
  \ m=\"3370300\">see</span> <span m=\"3370540\">why</span> <span m=\"3370780\">this</span>\
  \ <span m=\"3370960\">is</span> <span m=\"3371110\">true,</span> <span m=\"3371480\"\
  >let's</span> <span m=\"3371590\">go</span> <span m=\"3371740\">back</span> <span\
  \ m=\"3371980\">to</span> <span m=\"3372040\">the</span> <span m=\"3372130\">definition</span>\
  \ <span m=\"3372760\">of</span> <span m=\"3372850\">the</span> <span m=\"3372960\"\
  >Fourier</span> <span m=\"3373300\">coefficient,</span> <span m=\"3375255\">the</span>\
  \ <span m=\"3375520\">Fourier</span> <span m=\"3375910\">transform.</span> <span\
  \ m=\"3379120\">So</span> <span m=\"3379250\">recall</span> <span m=\"3380000\"\
  >that</span> <span m=\"3381510\">Fourier</span> <span m=\"3381830\">transform</span>\
  \ <span m=\"3382820\">is</span> <span m=\"3383270\">given</span> <span m=\"3383660\"\
  >by</span> <span m=\"3384560\">the</span> <span m=\"3384620\">following</span> <span\
  \ m=\"3385040\">formula,</span> <span m=\"3386670\">where</span> <span m=\"3387430\"\
  >I'm</span> <span m=\"3387740\">looking</span> <span m=\"3388670\">at</span> <span\
  \ m=\"3389900\">this</span> <span m=\"3390110\">expectation</span> <span m=\"3391310\"\
  >over</span> <span m=\"3391520\">points</span> <span m=\"3392030\">in</span> <span\
  \ m=\"3392210\">F3</span> <span m=\"3392480\">to</span> <span m=\"3392570\">the</span>\
  \ <span m=\"3392720\">n-th</span> <span m=\"3393830\">together</span> <span m=\"\
  3396840\">with</span> <span m=\"3397230\">indicator</span> <span m=\"3397860\">of</span>\
  \ <span m=\"3398250\">A</span> <span m=\"3399060\">multiplied</span> <span m=\"\
  3399610\">by</span> <span m=\"3399870\">this</span> <span m=\"3400770\">Fourier</span>\
  \ <span m=\"3401130\">character.</span></p><p><span m=\"3403840\">And</span> <span\
  \ m=\"3403960\">you</span> <span m=\"3404050\">see</span> <span m=\"3404290\">that</span>\
  \ <span m=\"3405850\">this</span> <span m=\"3406150\">function</span> <span m=\"\
  3406630\">here,</span> <span m=\"3409680\">it</span> <span m=\"3409840\">is</span>\
  \ <span m=\"3409990\">constant</span> <span m=\"3412110\">on</span> <span m=\"3414470\"\
  >cosets</span> <span m=\"3416170\">of</span> <span m=\"3416980\">the</span> <span\
  \ m=\"3417110\">hyperplane</span> <span m=\"3420580\">defined</span> <span m=\"\
  3421090\">by</span> <span m=\"3422230\">the</span> <span m=\"3424630\">orthogonal</span>\
  \ <span m=\"3425100\">complement</span> <span m=\"3426060\">of</span> <span m=\"\
  3426690\">r.</span> <span m=\"3430400\">So</span> <span m=\"3430610\">the</span>\
  \ <span m=\"3430700\">value</span> <span m=\"3431210\">of</span> <span m=\"3431330\"\
  >this</span> <span m=\"3431450\">dot</span> <span m=\"3431810\">product</span> <span\
  \ m=\"3433220\">is</span> <span m=\"3433720\">this</span> <span m=\"3433880\">constant</span>\
  \ <span m=\"3434550\">on</span> <span m=\"3434840\">the</span> <span m=\"3434960\"\
  >three</span> <span m=\"3435230\">hyperplanes.</span> <span m=\"3437780\">So</span>\
  \ <span m=\"3438650\">I</span> <span m=\"3438830\">can</span> <span m=\"3439100\"\
  >rewrite</span> <span m=\"3439820\">this</span> <span m=\"3440120\">expectation</span>\
  \ <span m=\"3441530\">simply</span> <span m=\"3442130\">as</span> <span m=\"3442910\"\
  >1/3</span> <span m=\"3444020\">of</span> <span m=\"3445070\">alpha</span> <span\
  \ m=\"3445320\">0</span> <span m=\"3445850\">plus</span> <span m=\"3446680\">alpha</span>\
  \ <span m=\"3446930\">1</span> <span m=\"3447180\">omega</span> <span m=\"3448010\"\
  >plus</span> <span m=\"3448420\">alpha</span> <span m=\"3448700\">2</span> <span\
  \ m=\"3449930\">omega</span> <span m=\"3450320\">squared,</span> <span m=\"3451550\"\
  >where</span> <span m=\"3454610\">alpha</span> <span m=\"3454850\">0,</span> <span\
  \ m=\"3455400\">alpha</span> <span m=\"3455840\">1,</span> <span m=\"3456320\">alpha</span>\
  \ <span m=\"3456560\">2</span> <span m=\"3457220\">are</span> <span m=\"3457310\"\
  >the</span> <span m=\"3457430\">densities</span> <span m=\"3460890\">of</span> <span\
  \ m=\"3461040\">A</span> <span m=\"3462330\">on</span> <span m=\"3462510\">the</span>\
  \ <span m=\"3462600\">three</span> <span m=\"3463740\">cosets</span> <span m=\"\
  3466500\">of</span> <span m=\"3467850\">r</span> <span m=\"3467990\">perp.</span>\
  \ <span m=\"3472139\">So</span> <span m=\"3472600\">group</span> <span m=\"3472900\"\
  >this</span> <span m=\"3473590\">expectation</span> <span m=\"3474400\">into</span>\
  \ <span m=\"3474700\">these</span> <span m=\"3474940\">three</span> <span m=\"3475660\"\
  >hyperplanes.</span></p><p><span m=\"3479320\">So</span> <span m=\"3479890\">now,</span>\
  \ <span m=\"3480310\">you</span> <span m=\"3480460\">see</span> <span m=\"3480760\"\
  >that</span> <span m=\"3481180\">if</span> <span m=\"3482230\">this</span> <span\
  \ m=\"3482450\">guy</span> <span m=\"3482710\">is</span> <span m=\"3482920\">large,</span>\
  \ <span m=\"3485300\">then</span> <span m=\"3487410\">you</span> <span m=\"3487770\"\
  >should</span> <span m=\"3488130\">expect</span> <span m=\"3489000\">that</span>\
  \ <span m=\"3489840\">alpha</span> <span m=\"3490140\">0,</span> <span m=\"3490740\"\
  >alpha</span> <span m=\"3490980\">1,</span> <span m=\"3491330\">and</span> <span\
  \ m=\"3491540\">alpha</span> <span m=\"3491760\">2</span> <span m=\"3492570\">are</span>\
  \ <span m=\"3492720\">not</span> <span m=\"3493140\">all</span> <span m=\"3493410\"\
  >too</span> <span m=\"3493770\">close</span> <span m=\"3494160\">to</span> <span\
  \ m=\"3494280\">each</span> <span m=\"3494520\">other.</span> <span m=\"3495550\"\
  >So</span> <span m=\"3495690\">if</span> <span m=\"3495960\">they</span> <span m=\"\
  3496140\">were</span> <span m=\"3496860\">all</span> <span m=\"3497010\">equal</span>\
  \ <span m=\"3497310\">to</span> <span m=\"3497430\">each</span> <span m=\"3497580\"\
  >other,</span> <span m=\"3497860\">you</span> <span m=\"3497960\">should</span>\
  \ <span m=\"3498060\">get</span> <span m=\"3498160\">0.</span> <span m=\"3499260\"\
  >But</span> <span m=\"3499380\">you</span> <span m=\"3499530\">should</span> <span\
  \ m=\"3499680\">not</span> <span m=\"3499920\">expect</span> <span m=\"3500340\"\
  >them</span> <span m=\"3500460\">to</span> <span m=\"3500550\">be</span> <span m=\"\
  3500700\">too</span> <span m=\"3500940\">close</span> <span m=\"3501300\">to</span>\
  \ <span m=\"3501420\">each</span> <span m=\"3501630\">other.</span></p><p><span\
  \ m=\"3502380\">In</span> <span m=\"3502470\">particular,</span> <span m=\"3503770\"\
  >we</span> <span m=\"3503820\">would</span> <span m=\"3504000\">want</span> <span\
  \ m=\"3504210\">to</span> <span m=\"3504270\">say</span> <span m=\"3504570\">that</span>\
  \ <span m=\"3505320\">one</span> <span m=\"3505590\">of</span> <span m=\"3505710\"\
  >them</span> <span m=\"3506160\">goes</span> <span m=\"3506520\">up--</span> <span\
  \ m=\"3507150\">is</span> <span m=\"3507480\">much</span> <span m=\"3507750\">bigger</span>\
  \ <span m=\"3508110\">than</span> <span m=\"3508350\">alpha.</span> <span m=\"3509520\"\
  >So</span> <span m=\"3509610\">one</span> <span m=\"3509820\">of</span> <span m=\"\
  3509880\">these,</span> <span m=\"3510630\">they</span> <span m=\"3510750\">must</span>\
  \ <span m=\"3510960\">be</span> <span m=\"3511290\">much</span> <span m=\"3511560\"\
  >bigger</span> <span m=\"3511830\">than</span> <span m=\"3512010\">alpha.</span>\
  \ <span m=\"3512730\">That's</span> <span m=\"3512940\">an</span> <span m=\"3513060\"\
  >elementary</span> <span m=\"3513930\">inequality.</span></p><p><span m=\"3514230\"\
  >This</span> <span m=\"3514530\">is</span> <span m=\"3514620\">something</span>\
  \ <span m=\"3514910\">that</span> <span m=\"3515000\">I'm</span> <span m=\"3515160\"\
  >sure</span> <span m=\"3515400\">I</span> <span m=\"3515460\">give</span> <span\
  \ m=\"3515670\">you</span> <span m=\"3515790\">five</span> <span m=\"3516000\">minutes</span>\
  \ <span m=\"3516300\">you</span> <span m=\"3516360\">can</span> <span m=\"3516510\"\
  >figure</span> <span m=\"3516800\">out.</span> <span m=\"3517320\">But</span> <span\
  \ m=\"3517410\">let</span> <span m=\"3517530\">me</span> <span m=\"3517620\">show</span>\
  \ <span m=\"3517860\">you</span> <span m=\"3518130\">a</span> <span m=\"3518250\"\
  >small</span> <span m=\"3518700\">trick</span> <span m=\"3519540\">to</span> <span\
  \ m=\"3519660\">show</span> <span m=\"3519960\">this.</span> <span m=\"3521170\"\
  >And</span> <span m=\"3521310\">the</span> <span m=\"3521370\">reason</span> <span\
  \ m=\"3521670\">for</span> <span m=\"3521820\">this</span> <span m=\"3522000\">trick</span>\
  \ <span m=\"3522600\">is</span> <span m=\"3523020\">because</span> <span m=\"3523900\"\
  >in</span> <span m=\"3524880\">next</span> <span m=\"3525270\">lecture,</span> <span\
  \ m=\"3526160\">when</span> <span m=\"3526200\">we</span> <span m=\"3526350\">look</span>\
  \ <span m=\"3526590\">at</span> <span m=\"3526770\">Roth's</span> <span m=\"3527160\"\
  >theorem</span> <span m=\"3527550\">over</span> <span m=\"3527790\">the</span> <span\
  \ m=\"3527910\">integers,</span> <span m=\"3528900\">we'll</span> <span m=\"3529110\"\
  >need</span> <span m=\"3529350\">this</span> <span m=\"3529560\">extra</span> <span\
  \ m=\"3529890\">trick.</span></p><p><span m=\"3535290\">And</span> <span m=\"3535410\"\
  >the</span> <span m=\"3535500\">trick</span> <span m=\"3535800\">here</span> <span\
  \ m=\"3536010\">is</span> <span m=\"3536160\">this.</span> <span m=\"3536850\">We</span>\
  \ <span m=\"3537000\">now</span> <span m=\"3537210\">know</span> <span m=\"3537540\"\
  >that</span> <span m=\"3538320\">because</span> <span m=\"3538920\">of</span> <span\
  \ m=\"3539070\">the</span> <span m=\"3539160\">hypothesis,</span> <span m=\"3541560\"\
  >3</span> <span m=\"3542040\">delta</span> <span m=\"3542880\">is</span> <span m=\"\
  3544410\">lower</span> <span m=\"3544740\">bound</span> <span m=\"3545430\">to</span>\
  \ <span m=\"3546180\">the</span> <span m=\"3546270\">absolute</span> <span m=\"\
  3546690\">value</span> <span m=\"3547140\">of</span> <span m=\"3547830\">alpha</span>\
  \ <span m=\"3548080\">0</span> <span m=\"3548430\">plus</span> <span m=\"3548900\"\
  >alpha</span> <span m=\"3549220\">1</span> <span m=\"3550020\">omega</span> <span\
  \ m=\"3550440\">plus</span> <span m=\"3550800\">alpha</span> <span m=\"3551010\"\
  >2</span> <span m=\"3551320\">omega</span> <span m=\"3551870\">squared.</span> <span\
  \ m=\"3556010\">OK,</span> <span m=\"3556430\">so</span> <span m=\"3556790\">note</span>\
  \ <span m=\"3557210\">here</span> <span m=\"3557780\">that</span> <span m=\"3558650\"\
  >the</span> <span m=\"3558800\">average</span> <span m=\"3559430\">of</span> <span\
  \ m=\"3559550\">the</span> <span m=\"3559640\">three</span> <span m=\"3560440\"\
  >alphas</span> <span m=\"3561680\">is</span> <span m=\"3561830\">equal</span> <span\
  \ m=\"3562190\">to</span> <span m=\"3563480\">the</span> <span m=\"3563600\">original</span>\
  \ <span m=\"3564110\">alpha</span> <span m=\"3565240\">by</span> <span m=\"3565400\"\
  >definition</span> <span m=\"3565930\">of</span> <span m=\"3566040\">density.</span></p><p><span\
  \ m=\"3568840\">So</span> <span m=\"3571080\">this</span> <span m=\"3571770\">inner</span>\
  \ <span m=\"3572070\">sum</span> <span m=\"3572730\">I</span> <span m=\"3572850\"\
  >can</span> <span m=\"3573060\">read</span> <span m=\"3573610\">write</span> <span\
  \ m=\"3574770\">like</span> <span m=\"3575170\">that.</span> <span m=\"3584620\"\
  >So</span> <span m=\"3584750\">the</span> <span m=\"3584870\">sum</span> <span m=\"\
  3585170\">of</span> <span m=\"3585230\">the</span> <span m=\"3585320\">three</span>\
  \ <span m=\"3585560\">groups</span> <span m=\"3585740\">of</span> <span m=\"3585830\"\
  >unity</span> <span m=\"3586130\">add</span> <span m=\"3586310\">up</span> <span\
  \ m=\"3586400\">to</span> <span m=\"3586490\">0.</span> <span m=\"3589410\">And</span>\
  \ <span m=\"3589560\">now,</span> <span m=\"3589800\">I</span> <span m=\"3589950\"\
  >apply</span> <span m=\"3590910\">triangle</span> <span m=\"3591540\">inequality</span>\
  \ <span m=\"3602260\">to</span> <span m=\"3603700\">extract</span> <span m=\"3604210\"\
  >the</span> <span m=\"3604270\">terms.</span></p><p><span m=\"3606220\">So</span>\
  \ <span m=\"3606410\">now,</span> <span m=\"3606680\">you</span> <span m=\"3606860\"\
  >should</span> <span m=\"3607070\">already</span> <span m=\"3607400\">deduce</span>\
  \ <span m=\"3607820\">that</span> <span m=\"3608780\">one</span> <span m=\"3609170\"\
  >of</span> <span m=\"3609290\">the</span> <span m=\"3609830\">alphas</span> <span\
  \ m=\"3610100\">i's</span> <span m=\"3610490\">has</span> <span m=\"3610700\">to</span>\
  \ <span m=\"3610790\">be</span> <span m=\"3611300\">significantly</span> <span m=\"\
  3612080\">larger</span> <span m=\"3612530\">than</span> <span m=\"3612710\">alpha.</span>\
  \ <span m=\"3614220\">And</span> <span m=\"3614510\">has</span> <span m=\"3614630\"\
  >to</span> <span m=\"3614720\">be</span> <span m=\"3614810\">significantly</span>\
  \ <span m=\"3615380\">different,</span> <span m=\"3615740\">but</span> <span m=\"\
  3615890\">there</span> <span m=\"3615950\">are</span> <span m=\"3616010\">only</span>\
  \ <span m=\"3616190\">three</span> <span m=\"3616400\">times.</span> <span m=\"\
  3616730\">One</span> <span m=\"3616890\">of</span> <span m=\"3616950\">them</span>\
  \ <span m=\"3617060\">has</span> <span m=\"3617240\">to</span> <span m=\"3617330\"\
  >be</span> <span m=\"3617420\">significantly</span> <span m=\"3617990\">larger.</span></p><p><span\
  \ m=\"3618620\">But</span> <span m=\"3618830\">let</span> <span m=\"3618950\">me</span>\
  \ <span m=\"3619490\">do</span> <span m=\"3619670\">this</span> <span m=\"3619850\"\
  >one</span> <span m=\"3620210\">extra</span> <span m=\"3620600\">trick,</span> <span\
  \ m=\"3621380\">which</span> <span m=\"3621590\">we'll</span> <span m=\"3621770\"\
  >need</span> <span m=\"3622280\">next</span> <span m=\"3622640\">time,</span> <span\
  \ m=\"3624050\">which</span> <span m=\"3624230\">is</span> <span m=\"3624350\">that</span>\
  \ <span m=\"3624620\">let</span> <span m=\"3624740\">me</span> <span m=\"3625010\"\
  >add</span> <span m=\"3625490\">an</span> <span m=\"3625880\">extra</span> <span\
  \ m=\"3630240\">term</span> <span m=\"3630780\">like</span> <span m=\"3630990\"\
  >that,</span> <span m=\"3631410\">which</span> <span m=\"3632310\">sums</span> <span\
  \ m=\"3632700\">out</span> <span m=\"3632800\">to</span> <span m=\"3632880\">0.</span>\
  \ <span m=\"3634850\">But</span> <span m=\"3634970\">now,</span> <span m=\"3635270\"\
  >you</span> <span m=\"3635420\">see</span> <span m=\"3635750\">that</span> <span\
  \ m=\"3636020\">each</span> <span m=\"3636230\">summand</span> <span m=\"3637400\"\
  >is</span> <span m=\"3637850\">always</span> <span m=\"3638940\">nonnegative.</span>\
  \ <span m=\"3645700\">So</span> <span m=\"3648370\">one</span> <span m=\"3648670\"\
  >of</span> <span m=\"3648820\">the--</span> <span m=\"3652050\">so</span> <span\
  \ m=\"3652260\">there</span> <span m=\"3652440\">exists</span> <span m=\"3652980\"\
  >some</span> <span m=\"3653340\">j</span> <span m=\"3654930\">such</span> <span\
  \ m=\"3655290\">that</span> <span m=\"3657270\">delta</span> <span m=\"3657780\"\
  >lower</span> <span m=\"3658030\">abounds</span> <span m=\"3658830\">the</span>\
  \ <span m=\"3659430\">j-th</span> <span m=\"3659820\">summand.</span></p><p><span\
  \ m=\"3661290\">And</span> <span m=\"3663420\">if</span> <span m=\"3663540\">you</span>\
  \ <span m=\"3663630\">look</span> <span m=\"3663810\">at</span> <span m=\"3663900\"\
  >what</span> <span m=\"3664080\">that</span> <span m=\"3664230\">means,</span> <span\
  \ m=\"3664980\">then</span> <span m=\"3666440\">alpha</span> <span m=\"3666720\"\
  >lower</span> <span m=\"3666960\">bounds</span> <span m=\"3667320\">the</span> <span\
  \ m=\"3667510\">j-th</span> <span m=\"3670190\">summand.</span> <span m=\"3671370\"\
  >So</span> <span m=\"3671720\">in</span> <span m=\"3671890\">particular,</span>\
  \ <span m=\"3672450\">this</span> <span m=\"3672610\">sum</span> <span m=\"3673300\"\
  >here</span> <span m=\"3673510\">should</span> <span m=\"3673690\">be</span> <span\
  \ m=\"3674430\">nonnegative.</span> <span m=\"3681480\">So</span> <span m=\"3681600\"\
  >you</span> <span m=\"3681690\">have</span> <span m=\"3681860\">that.</span> <span\
  \ m=\"3682640\">Good.</span> <span m=\"3686390\">So</span> <span m=\"3686550\">we</span>\
  \ <span m=\"3686910\">obtained</span> <span m=\"3687270\">a</span> <span m=\"3687370\"\
  >density</span> <span m=\"3687810\">increment</span> <span m=\"3688760\">of</span>\
  \ <span m=\"3689040\">this</span> <span m=\"3689460\">hyperplane.</span></p><p><span\
  \ m=\"3694760\">And</span> <span m=\"3694930\">finally,</span> <span m=\"3696940\"\
  >I</span> <span m=\"3697060\">want</span> <span m=\"3697280\">to</span> <span m=\"\
  3698440\">iterate</span> <span m=\"3699070\">this</span> <span m=\"3699400\">density</span>\
  \ <span m=\"3699730\">increment.</span> <span m=\"3702130\">So</span> <span m=\"\
  3702730\">I</span> <span m=\"3702790\">want</span> <span m=\"3703070\">to</span>\
  \ <span m=\"3703160\">iterate</span> <span m=\"3703330\">this</span> <span m=\"\
  3703480\">density</span> <span m=\"3703810\">increment--</span> <span m=\"3721400\"\
  >so</span> <span m=\"3722330\">summary</span> <span m=\"3722840\">so</span> <span\
  \ m=\"3723110\">far</span> <span m=\"3724820\">is</span> <span m=\"3725000\">that</span>\
  \ <span m=\"3725330\">we</span> <span m=\"3725660\">have--</span> <span m=\"3727520\"\
  >so</span> <span m=\"3727640\">if</span> <span m=\"3728560\">A</span> <span m=\"\
  3728920\">is</span> <span m=\"3729140\">3-AP-free</span> <span m=\"3734250\">with</span>\
  \ <span m=\"3734880\">density</span> <span m=\"3735350\">alpha</span> <span m=\"\
  3735480\">and</span> <span m=\"3737490\">N</span> <span m=\"3738420\">at</span>\
  \ <span m=\"3738570\">least</span> <span m=\"3739170\">2</span> <span m=\"3740520\"\
  >to</span> <span m=\"3740670\">the</span> <span m=\"3741060\">alpha</span> <span\
  \ m=\"3741780\">to</span> <span m=\"3741870\">the</span> <span m=\"3741960\">minus</span>\
  \ <span m=\"3742260\">2,</span> <span m=\"3743220\">then</span> <span m=\"3745890\"\
  >A</span> <span m=\"3746300\">has</span> <span m=\"3746970\">density</span> <span\
  \ m=\"3750300\">at</span> <span m=\"3750760\">least</span> <span m=\"3751440\">alpha</span>\
  \ <span m=\"3751910\">plus</span> <span m=\"3753150\">alpha</span> <span m=\"3753440\"\
  >squared</span> <span m=\"3754010\">over</span> <span m=\"3754280\">4</span> <span\
  \ m=\"3755510\">on</span> <span m=\"3755810\">some</span> <span m=\"3756110\">hyperplane.</span>\
  \ <span m=\"3760430\">So</span> <span m=\"3760570\">you</span> <span m=\"3760660\"\
  >combine</span> <span m=\"3761140\">step</span> <span m=\"3761440\">one</span> <span\
  \ m=\"3761560\">and</span> <span m=\"3761650\">step</span> <span m=\"3761920\">two,</span>\
  \ <span m=\"3763240\">we</span> <span m=\"3763360\">obtain</span> <span m=\"3763660\"\
  >this</span> <span m=\"3763840\">conclusion.</span></p><p><span m=\"3768340\">Well,</span>\
  \ <span m=\"3771370\">I</span> <span m=\"3771610\">can</span> <span m=\"3771790\"\
  >now</span> <span m=\"3772540\">repeat</span> <span m=\"3773230\">this</span> <span\
  \ m=\"3773440\">operation.</span> <span m=\"3774970\">So</span> <span m=\"3775150\"\
  >I</span> <span m=\"3775210\">can</span> <span m=\"3775390\">repeat</span> <span\
  \ m=\"3778450\">by</span> <span m=\"3780460\">restricting</span> <span m=\"3784160\"\
  >A</span> <span m=\"3785230\">to</span> <span m=\"3786342\">this</span> <span m=\"\
  3786700\">hyperplane.</span> <span m=\"3789890\">If</span> <span m=\"3790220\">A</span>\
  \ <span m=\"3790530\">is</span> <span m=\"3791040\">originally</span> <span m=\"\
  3791510\">3-AP-free,</span> <span m=\"3792290\">I</span> <span m=\"3792480\">restrict</span>\
  \ <span m=\"3792735\">it</span> <span m=\"3792990\">to a</span> <span m=\"3793120\"\
  >hyperplane,</span> <span m=\"3793590\">it's</span> <span m=\"3793670\">still</span>\
  \ <span m=\"3793950\">3-AP-free.</span> <span m=\"3795460\">So</span> <span m=\"\
  3795480\">I</span> <span m=\"3795510\">can</span> <span m=\"3795630\">keep</span>\
  \ <span m=\"3795810\">going.</span></p><p><span m=\"3797790\">I</span> <span m=\"\
  3797880\">can</span> <span m=\"3798030\">keep</span> <span m=\"3798240\">going</span>\
  \ <span m=\"3798770\">provided</span> <span m=\"3799330\">that</span> <span m=\"\
  3799460\">my</span> <span m=\"3799650\">space</span> <span m=\"3800100\">is</span>\
  \ <span m=\"3800160\">still</span> <span m=\"3800400\">large</span> <span m=\"3800730\"\
  >enough,</span> <span m=\"3801750\">because</span> <span m=\"3801990\">I</span>\
  \ <span m=\"3802110\">still</span> <span m=\"3802470\">need</span> <span m=\"3803610\"\
  >this</span> <span m=\"3806040\">lower</span> <span m=\"3806370\">bound</span> <span\
  \ m=\"3806700\">on</span> <span m=\"3806870\">F.</span> <span m=\"3807500\">So</span>\
  \ <span m=\"3807530\">don't</span> <span m=\"3807690\">forget</span> <span m=\"\
  3808020\">this</span> <span m=\"3808170\">one</span> <span m=\"3808350\">here.</span>\
  \ <span m=\"3809640\">So</span> <span m=\"3809910\">I</span> <span m=\"3810000\"\
  >can</span> <span m=\"3810180\">keep</span> <span m=\"3810420\">going</span> <span\
  \ m=\"3815410\">as long</span> <span m=\"3815760\">as</span> <span m=\"3819110\"\
  >N</span> <span m=\"3819980\">is--</span> <span m=\"3824960\">so I'm</span> <span\
  \ m=\"3825310\">using</span> <span m=\"3825760\">N</span> <span m=\"3825910\">sub\
  \ j</span> <span m=\"3826390\">to</span> <span m=\"3826510\">denote</span> <span\
  \ m=\"3826930\">what</span> <span m=\"3827110\">happens</span> <span m=\"3827830\"\
  >after</span> <span m=\"3828040\">the</span> <span m=\"3828180\">j-th</span> <span\
  \ m=\"3828460\">step.</span> <span m=\"3830240\">I</span> <span m=\"3830300\">can</span>\
  \ <span m=\"3830420\">keep</span> <span m=\"3830570\">going</span> <span m=\"3830930\"\
  >as</span> <span m=\"3831080\">long</span> <span m=\"3831350\">as</span> <span m=\"\
  3831920\">this</span> <span m=\"3832100\">is</span> <span m=\"3832160\">still</span>\
  \ <span m=\"3832400\">satisfied.</span></p><p><span m=\"3833840\">But</span> <span\
  \ m=\"3834080\">of</span> <span m=\"3834170\">course,</span> <span m=\"3834860\"\
  >you</span> <span m=\"3834980\">cannot</span> <span m=\"3835430\">keep</span> <span\
  \ m=\"3835670\">on</span> <span m=\"3835790\">going</span> <span m=\"3836030\">forever,</span>\
  \ <span m=\"3836540\">because</span> <span m=\"3837050\">the</span> <span m=\"3837140\"\
  >density</span> <span m=\"3837740\">is</span> <span m=\"3838550\">bounded.</span>\
  \ <span m=\"3840030\">So</span> <span m=\"3840050\">density</span> <span m=\"3840470\"\
  >cannot</span> <span m=\"3840800\">exceed</span> <span m=\"3841190\">1.</span> <span\
  \ m=\"3841970\">So</span> <span m=\"3842150\">these</span> <span m=\"3842390\">two</span>\
  \ <span m=\"3842600\">will</span> <span m=\"3842900\">give</span> <span m=\"3842990\"\
  >you</span> <span m=\"3843140\">a</span> <span m=\"3843200\">bound</span> <span\
  \ m=\"3843830\">on</span> <span m=\"3843950\">the</span> <span m=\"3844430\">total</span>\
  \ <span m=\"3844730\">dimension.</span> <span m=\"3846420\">So</span> <span m=\"\
  3846520\">let's</span> <span m=\"3846590\">work</span> <span m=\"3846770\">this</span>\
  \ <span m=\"3846980\">out.</span></p><p><span m=\"3848750\">So</span> <span m=\"\
  3848990\">let</span> <span m=\"3852410\">alpha</span> <span m=\"3853270\">i</span>\
  \ <span m=\"3854320\">denote</span> <span m=\"3854990\">the</span> <span m=\"3856580\"\
  >density</span> <span m=\"3858140\">after</span> <span m=\"3860300\">step</span>\
  \ <span m=\"3862590\">i</span> <span m=\"3863310\">in</span> <span m=\"3863540\"\
  >this</span> <span m=\"3863730\">iteration.</span> <span m=\"3865770\">And</span>\
  \ <span m=\"3866640\">we</span> <span m=\"3866820\">see</span> <span m=\"3867120\"\
  >from</span> <span m=\"3867840\">over</span> <span m=\"3868080\">here</span> <span\
  \ m=\"3868830\">that</span> <span m=\"3870750\">you</span> <span m=\"3870900\">start</span>\
  \ <span m=\"3871500\">with</span> <span m=\"3874050\">density</span> <span m=\"\
  3874950\">alpha,</span> <span m=\"3875910\">and</span> <span m=\"3876120\">each</span>\
  \ <span m=\"3876390\">step</span> <span m=\"3877530\">you</span> <span m=\"3877680\"\
  >go</span> <span m=\"3877950\">up</span> <span m=\"3880200\">by</span> <span m=\"\
  3880620\">an</span> <span m=\"3880950\">increment,</span> <span m=\"3882090\">which</span>\
  \ <span m=\"3882540\">is</span> <span m=\"3884490\">basically</span> <span m=\"\
  3884940\">what--</span> <span m=\"3886260\">so</span> <span m=\"3886470\">you</span>\
  \ <span m=\"3886830\">go</span> <span m=\"3887040\">up</span> <span m=\"3887170\"\
  >by</span> <span m=\"3887310\">some</span> <span m=\"3887520\">increment.</span>\
  \ <span m=\"3888720\">And</span> <span m=\"3888870\">you</span> <span m=\"3888960\"\
  >want</span> <span m=\"3889140\">to</span> <span m=\"3889200\">know,</span> <span\
  \ m=\"3889890\">if</span> <span m=\"3890040\">you</span> <span m=\"3890160\">start</span>\
  \ <span m=\"3890550\">with</span> <span m=\"3890760\">alpha,</span> <span m=\"3891570\"\
  >how</span> <span m=\"3891780\">many</span> <span m=\"3892050\">steps</span> <span\
  \ m=\"3893880\">at</span> <span m=\"3894030\">most</span> <span m=\"3894420\">can</span>\
  \ <span m=\"3894630\">you</span> <span m=\"3894750\">take</span> <span m=\"3895800\"\
  >before</span> <span m=\"3896160\">you</span> <span m=\"3896280\">blow</span> <span\
  \ m=\"3896550\">out</span> <span m=\"3897420\">1.</span></p><p><span m=\"3900440\"\
  >So</span> <span m=\"3901610\">can</span> <span m=\"3901780\">you</span> <span m=\"\
  3901840\">give</span> <span m=\"3901960\">me</span> <span m=\"3902080\">some</span>\
  \ <span m=\"3902280\">bound?</span> <span m=\"3906640\">So</span> <span m=\"3906800\"\
  >what's</span> <span m=\"3906980\">the</span> <span m=\"3907070\">maximum--</span>\
  \ <span m=\"3908160\">at</span> <span m=\"3908460\">most,</span> <span m=\"3908750\"\
  >how</span> <span m=\"3908900\">many</span> <span m=\"3909170\">steps?</span> <span\
  \ m=\"3917160\">So</span> <span m=\"3918060\">we</span> <span m=\"3918180\">know</span>\
  \ <span m=\"3918480\">that</span> <span m=\"3921100\">the</span> <span m=\"3921850\"\
  >density</span> <span m=\"3922210\">cannot</span> <span m=\"3922570\">exceed</span>\
  \ <span m=\"3922960\">1.</span></p><p><span m=\"3924184\">AUDIENCE:</span> <span\
  \ m=\"3924661\">4 by</span> <span m=\"3926569\">alpha</span> <span m=\"3927046\"\
  >squared.</span></p><p><span m=\"3927523\">YUFEI ZHAO:</span> <span m=\"3928000\"\
  >So</span> <span m=\"3929120\">you</span> <span m=\"3929460\">see</span> <span m=\"\
  3929700\">that</span> <span m=\"3930180\">you</span> <span m=\"3930360\">have</span>\
  \ <span m=\"3930680\">at</span> <span m=\"3930780\">most</span> <span m=\"3931380\"\
  >4</span> <span m=\"3931920\">over</span> <span m=\"3933170\">alpha</span> <span\
  \ m=\"3933630\">squared</span> <span m=\"3934200\">steps,</span> <span m=\"3937140\"\
  >because</span> <span m=\"3937440\">density</span> <span m=\"3937770\">is</span>\
  \ <span m=\"3937870\">at</span> <span m=\"3937940\">most</span> <span m=\"3938190\"\
  >1.</span> <span m=\"3938850\">And</span> <span m=\"3940540\">if</span> <span m=\"\
  3940690\">you</span> <span m=\"3940810\">plug</span> <span m=\"3941650\">this</span>\
  \ <span m=\"3941920\">in,</span> <span m=\"3943570\">you</span> <span m=\"3943810\"\
  >get</span> <span m=\"3944050\">something</span> <span m=\"3944500\">which</span>\
  \ <span m=\"3944710\">is</span> <span m=\"3944800\">not</span> <span m=\"3945100\"\
  >quite</span> <span m=\"3945520\">what</span> <span m=\"3945730\">I</span> <span\
  \ m=\"3945820\">stated.</span> <span m=\"3946810\">So</span> <span m=\"3947470\"\
  >it</span> <span m=\"3947530\">turns</span> <span m=\"3947830\">out</span> <span\
  \ m=\"3948670\">that</span> <span m=\"3948910\">if</span> <span m=\"3949030\">you</span>\
  \ <span m=\"3949180\">plug</span> <span m=\"3950020\">this</span> <span m=\"3950290\"\
  >in,</span> <span m=\"3950920\">you</span> <span m=\"3951040\">find</span> <span\
  \ m=\"3951400\">that</span> <span m=\"3951640\">alpha</span> <span m=\"3952540\"\
  >is--</span> <span m=\"3953620\">you</span> <span m=\"3953710\">find</span> <span\
  \ m=\"3953940\">that</span> <span m=\"3954010\">the</span> <span m=\"3954100\">size</span>\
  \ <span m=\"3954490\">of</span> <span m=\"3954610\">A</span> <span m=\"3955360\"\
  >is</span> <span m=\"3956010\">at</span> <span m=\"3956140\">most</span> <span m=\"\
  3957520\">3</span> <span m=\"3957730\">to</span> <span m=\"3957850\">the</span>\
  \ <span m=\"3957970\">n-th</span> <span m=\"3958480\">over</span> <span m=\"3958850\"\
  >square</span> <span m=\"3959410\">root</span> <span m=\"3959590\">n.</span></p><p><span\
  \ m=\"3963210\">So</span> <span m=\"3963370\">let</span> <span m=\"3963490\">me</span>\
  \ <span m=\"3963580\">do</span> <span m=\"3963790\">a</span> <span m=\"3963850\"\
  >little</span> <span m=\"3964060\">bit</span> <span m=\"3964180\">better,</span>\
  \ <span m=\"3964945\">so</span> <span m=\"3965410\">then</span> <span m=\"3966040\"\
  >simply</span> <span m=\"3966940\">seeing</span> <span m=\"3967390\">that</span>\
  \ <span m=\"3968500\">this</span> <span m=\"3968860\">term</span> <span m=\"3969130\"\
  >here</span> <span m=\"3969490\">is</span> <span m=\"3969730\">at</span> <span m=\"\
  3969820\">least</span> <span m=\"3970280\">alpha</span> <span m=\"3970630\">squared</span>\
  \ <span m=\"3971140\">over</span> <span m=\"3971420\">4.</span> <span m=\"3973260\"\
  >And</span> <span m=\"3973720\">the</span> <span m=\"3973810\">point</span> <span\
  \ m=\"3974050\">is</span> <span m=\"3974170\">that</span> <span m=\"3974260\">when</span>\
  \ <span m=\"3974470\">you</span> <span m=\"3975070\">increment,</span> <span m=\"\
  3975970\">you</span> <span m=\"3976180\">increment</span> <span m=\"3976600\">faster</span>\
  \ <span m=\"3977050\">and</span> <span m=\"3977140\">faster.</span> <span m=\"3979040\"\
  >So</span> <span m=\"3979190\">I</span> <span m=\"3979250\">can</span> <span m=\"\
  3979430\">use</span> <span m=\"3979640\">that</span> <span m=\"3979850\">to</span>\
  \ <span m=\"3981170\">give</span> <span m=\"3981410\">a</span> <span m=\"3981440\"\
  >better</span> <span m=\"3981680\">bound</span> <span m=\"3982040\">on</span> <span\
  \ m=\"3982160\">the</span> <span m=\"3982220\">number</span> <span m=\"3982520\"\
  >of</span> <span m=\"3982610\">steps.</span></p><p><span m=\"3984420\">And</span>\
  \ <span m=\"3984560\">here's</span> <span m=\"3985430\">the</span> <span m=\"3985520\"\
  >way</span> <span m=\"3985640\">to</span> <span m=\"3985730\">see</span> <span m=\"\
  3985910\">it.</span> <span m=\"3986840\">So</span> <span m=\"3987020\">let</span>\
  \ <span m=\"3987170\">me--</span> <span m=\"3988750\">we</span> <span m=\"3989240\"\
  >can</span> <span m=\"3989390\">do</span> <span m=\"3989540\">better.</span> <span\
  \ m=\"3993600\">So</span> <span m=\"3993750\">starting</span> <span m=\"3994440\"\
  >at</span> <span m=\"3996300\">alpha,</span> <span m=\"3996910\">I</span> <span\
  \ m=\"3997190\">then now</span> <span m=\"3997360\">ask,</span> <span m=\"3998100\"\
  >how</span> <span m=\"3998370\">many</span> <span m=\"3998610\">steps</span> <span\
  \ m=\"3999330\">do</span> <span m=\"3999420\">you</span> <span m=\"3999540\">need</span>\
  \ <span m=\"3999750\">to</span> <span m=\"3999840\">take</span> <span m=\"4000260\"\
  >before</span> <span m=\"4000650\">it</span> <span m=\"4000740\">doubles?</span></p><p><span\
  \ m=\"4002594\">AUDIENCE:</span> <span m=\"4002823\">[INAUDIBLE]</span></p><p><span\
  \ m=\"4004426\">YUFEI ZHAO:</span> <span m=\"4004890\">It</span> <span m=\"4005010\"\
  >goes</span> <span m=\"4005280\">up</span> <span m=\"4005670\">by</span> <span m=\"\
  4006470\">alpha</span> <span m=\"4006720\">squared</span> <span m=\"4007050\">over</span>\
  \ <span m=\"4007220\">4.</span> <span m=\"4008610\">So</span> <span m=\"4009690\"\
  >it</span> <span m=\"4009840\">doubles</span> <span m=\"4013140\">after</span> <span\
  \ m=\"4014961\">at</span> <span m=\"4015390\">most</span> <span m=\"4016050\">4</span>\
  \ <span m=\"4016440\">over</span> <span m=\"4016740\">alpha</span> <span m=\"4017220\"\
  >steps.</span> <span m=\"4021280\">And</span> <span m=\"4021600\">at</span> <span\
  \ m=\"4021850\">which</span> <span m=\"4022090\">point</span> <span m=\"4027810\"\
  >this</span> <span m=\"4028020\">alpha,</span> <span m=\"4028350\">new</span> <span\
  \ m=\"4028560\">alpha,</span> <span m=\"4028860\">becomes</span> <span m=\"4029280\"\
  >at</span> <span m=\"4029370\">least</span> <span m=\"4029640\">the</span> <span\
  \ m=\"4029790\">original--</span> <span m=\"4030930\">twice</span> <span m=\"4031290\"\
  >the</span> <span m=\"4031410\">original</span> <span m=\"4031830\">alpha?</span>\
  \ <span m=\"4033250\">But</span> <span m=\"4033480\">now,</span> <span m=\"4033690\"\
  >you</span> <span m=\"4034200\">keep</span> <span m=\"4034440\">going.</span> <span\
  \ m=\"4034740\">How</span> <span m=\"4034920\">many</span> <span m=\"4035130\">times</span>\
  \ <span m=\"4035760\">does</span> <span m=\"4035940\">it</span> <span m=\"4036000\"\
  >take</span> <span m=\"4036210\">to</span> <span m=\"4036390\">double</span> <span\
  \ m=\"4036720\">again?</span> <span m=\"4038560\">2</span> <span m=\"4038860\">over</span>\
  \ <span m=\"4039050\">alpha,</span> <span m=\"4039380\">because</span> <span m=\"\
  4039620\">the</span> <span m=\"4039680\">alpha</span> <span m=\"4039950\">became</span>\
  \ <span m=\"4040280\">twice</span> <span m=\"4040580\">as</span> <span m=\"4040700\"\
  >much.</span></p><p><span m=\"4046760\">So</span> <span m=\"4046770\">it</span>\
  \ <span m=\"4047000\">doubles</span> <span m=\"4047510\">again</span> <span m=\"\
  4049440\">after</span> <span m=\"4049920\">at</span> <span m=\"4050250\">most</span>\
  \ <span m=\"4050490\">2</span> <span m=\"4050700\">over</span> <span m=\"4050940\"\
  >alpha</span> <span m=\"4051240\">steps.</span> <span m=\"4053400\">And</span> <span\
  \ m=\"4053520\">then</span> <span m=\"4053880\">you</span> <span m=\"4054000\">keep</span>\
  \ <span m=\"4054210\">going.</span> <span m=\"4054670\">The</span> <span m=\"4054690\"\
  >next</span> <span m=\"4055290\">iteration</span> <span m=\"4055820\">is</span>\
  \ <span m=\"4055950\">1</span> <span m=\"4056160\">over</span> <span m=\"4056310\"\
  >alpha.</span> <span m=\"4058390\">So</span> <span m=\"4060990\">in</span> <span\
  \ m=\"4061170\">total--</span> <span m=\"4062280\">so</span> <span m=\"4062490\"\
  >you</span> <span m=\"4062640\">see</span> <span m=\"4062850\">that</span> <span\
  \ m=\"4063360\">we</span> <span m=\"4063510\">must</span> <span m=\"4063810\">stop</span>\
  \ <span m=\"4068680\">after</span> <span m=\"4070160\">at</span> <span m=\"4070600\"\
  >most</span> <span m=\"4072490\">8</span> <span m=\"4072700\">over</span> <span\
  \ m=\"4073150\">alpha</span> <span m=\"4075550\">steps.</span> <span m=\"4078570\"\
  >So the</span> <span m=\"4078640\">number</span> <span m=\"4079000\">of</span> <span\
  \ m=\"4079090\">times</span> <span m=\"4080250\">it</span> <span m=\"4080440\">doubles,</span>\
  \ <span m=\"4081250\">actually</span> <span m=\"4082105\">it</span> <span m=\"4082570\"\
  >decreases</span> <span m=\"4083110\">by</span> <span m=\"4083890\">at</span> <span\
  \ m=\"4083980\">least</span> <span m=\"4084160\">half</span> <span m=\"4084550\"\
  >each</span> <span m=\"4084760\">time.</span></p><p><span m=\"4091070\">So</span>\
  \ <span m=\"4091190\">now,</span> <span m=\"4091400\">we</span> <span m=\"4091520\"\
  >know</span> <span m=\"4091670\">that--</span> <span m=\"4094860\">we</span> <span\
  \ m=\"4095010\">see</span> <span m=\"4095430\">that</span> <span m=\"4096090\">the--</span>\
  \ <span m=\"4097500\">so</span> <span m=\"4098880\">you</span> <span m=\"4098970\"\
  >keep</span> <span m=\"4099180\">on</span> <span m=\"4099270\">going.</span> <span\
  \ m=\"4099609\">So</span> <span m=\"4099630\">you</span> <span m=\"4099750\">must</span>\
  \ <span m=\"4099990\">stop</span> <span m=\"4100439\">after</span> <span m=\"4100890\"\
  >at most</span> <span m=\"4101340\">8</span> <span m=\"4101490\">over</span> <span\
  \ m=\"4101700\">alpha</span> <span m=\"4101970\">steps.</span> <span m=\"4103170\"\
  >What</span> <span m=\"4103470\">is</span> <span m=\"4103649\">the</span> <span\
  \ m=\"4103920\">final</span> <span m=\"4105210\">density</span> <span m=\"4105840\"\
  >when</span> <span m=\"4106050\">you</span> <span m=\"4106170\">have</span> <span\
  \ m=\"4106410\">to</span> <span m=\"4106500\">stop,</span> <span m=\"4106859\">because</span>\
  \ <span m=\"4107050\">when</span> <span m=\"4107130\">are</span> <span m=\"4107340\"\
  >you</span> <span m=\"4107520\">forced</span> <span m=\"4107819\">to</span> <span\
  \ m=\"4107910\">stop?</span> <span m=\"4108430\">You</span> <span m=\"4108529\"\
  >are</span> <span m=\"4108600\">forced</span> <span m=\"4108960\">to</span> <span\
  \ m=\"4109020\">stop</span> <span m=\"4109590\">if</span> <span m=\"4109710\">you</span>\
  \ <span m=\"4109830\">run</span> <span m=\"4110069\">out</span> <span m=\"4110189\"\
  >of</span> <span m=\"4110279\">space.</span> <span m=\"4112399\">So</span> <span\
  \ m=\"4112609\">you're</span> <span m=\"4112700\">forced</span> <span m=\"4112970\"\
  >to</span> <span m=\"4113060\">stop</span> <span m=\"4113510\">when you</span> <span\
  \ m=\"4113810\">run</span> <span m=\"4113990\">out</span> <span m=\"4114080\">of</span>\
  \ <span m=\"4114140\">space.</span></p><p><span m=\"4114930\">So</span> <span m=\"\
  4115010\">if</span> <span m=\"4115580\">the</span> <span m=\"4115670\">process</span>\
  \ <span m=\"4118189\">terminates</span> <span m=\"4121040\">after</span> <span m=\"\
  4123210\">m</span> <span m=\"4123620\">steps--</span> <span m=\"4126290\">so</span>\
  \ <span m=\"4126470\">we're</span> <span m=\"4126700\">at</span> <span m=\"4127130\"\
  >density</span> <span m=\"4132850\">alpha</span> <span m=\"4133229\">m,</span> <span\
  \ m=\"4134540\">so</span> <span m=\"4134710\">then</span> <span m=\"4135040\">the</span>\
  \ <span m=\"4135160\">final</span> <span m=\"4141450\">subspace</span> <span m=\"\
  4144305\">has</span> <span m=\"4144740\">size</span> <span m=\"4147939\">less</span>\
  \ <span m=\"4148210\">than</span> <span m=\"4148870\">2</span> <span m=\"4149470\"\
  >to</span> <span m=\"4149620\">the</span> <span m=\"4149800\">alpha</span> <span\
  \ m=\"4152080\">m</span> <span m=\"4153970\">raised</span> <span m=\"4154240\">to</span>\
  \ <span m=\"4154359\">minus</span> <span m=\"4154689\">2,</span> <span m=\"4156100\"\
  >which</span> <span m=\"4156399\">is--</span> <span m=\"4159130\">So</span> <span\
  \ m=\"4159290\">now,</span> <span m=\"4159670\">I</span> <span m=\"4160069\">use</span>\
  \ <span m=\"4160290\">this</span> <span m=\"4160430\">bound</span> <span m=\"4162470\"\
  >alpha.</span> <span m=\"4165490\">So</span> <span m=\"4166870\">the</span> <span\
  \ m=\"4167050\">initial</span> <span m=\"4167680\">N</span> <span m=\"4168670\"\
  >is</span> <span m=\"4169460\">upper</span> <span m=\"4169800\">bounded</span> <span\
  \ m=\"4170680\">by</span> <span m=\"4171569\">what?</span> <span m=\"4172189\">So</span>\
  \ <span m=\"4172479\">how</span> <span m=\"4172720\">many</span> <span m=\"4172930\"\
  >steps</span> <span m=\"4173359\">did</span> <span m=\"4173439\">you</span> <span\
  \ m=\"4173529\">take?</span> <span m=\"4174250\">You</span> <span m=\"4174340\"\
  >took</span> <span m=\"4174550\">at</span> <span m=\"4174609\">most</span> <span\
  \ m=\"4175290\">8</span> <span m=\"4175460\">over</span> <span m=\"4175660\">alpha</span>\
  \ <span m=\"4175930\">steps.</span></p><p><span m=\"4176990\">Each</span> <span\
  \ m=\"4177069\">of</span> <span m=\"4177160\">those</span> <span m=\"4177340\">steps,</span>\
  \ <span m=\"4178939\">you</span> <span m=\"4179120\">pass</span> <span m=\"4179510\"\
  >down</span> <span m=\"4179779\">to</span> <span m=\"4180020\">codimension</span>\
  \ <span m=\"4180590\">what?</span> <span m=\"4181760\">You</span> <span m=\"4181850\"\
  >lose</span> <span m=\"4182060\">a</span> <span m=\"4182130\">dimension</span> <span\
  \ m=\"4182510\">for</span> <span m=\"4182689\">each</span> <span m=\"4182870\">step.</span>\
  \ <span m=\"4183979\">And</span> <span m=\"4184130\">the</span> <span m=\"4184189\"\
  >final</span> <span m=\"4184790\">subspace</span> <span m=\"4185510\">has</span>\
  \ <span m=\"4185840\">at</span> <span m=\"4185930\">least</span> <span m=\"4186380\"\
  >this--</span> <span m=\"4187050\">has</span> <span m=\"4187220\">at</span> <span\
  \ m=\"4187330\">most</span> <span m=\"4190130\">that</span> <span m=\"4190430\"\
  >much</span> <span m=\"4190760\">space.</span> <span m=\"4191490\">So</span> <span\
  \ m=\"4191630\">the</span> <span m=\"4191779\">final</span> <span m=\"4192170\"\
  >dimension</span> <span m=\"4196020\">is</span> <span m=\"4196530\">this,</span>\
  \ <span m=\"4197400\">basically</span> <span m=\"4197970\">log</span> <span m=\"\
  4198330\">1</span> <span m=\"4198530\">over</span> <span m=\"4198750\">alpha.</span>\
  \ <span m=\"4201300\">So</span> <span m=\"4201490\">put</span> <span m=\"4201670\"\
  >them</span> <span m=\"4201790\">together,</span> <span m=\"4202790\">we</span>\
  \ <span m=\"4202810\">see</span> <span m=\"4203050\">that</span> <span m=\"4205750\"\
  >the</span> <span m=\"4206530\">size</span> <span m=\"4206980\">of</span> <span\
  \ m=\"4207070\">the</span> <span m=\"4207160\">space</span> <span m=\"4207650\"\
  >originally</span> <span m=\"4208520\">is</span> <span m=\"4209200\">at</span> <span\
  \ m=\"4209290\">most</span> <span m=\"4209830\">1</span> <span m=\"4210040\">over</span>\
  \ <span m=\"4210160\">alpha.</span> <span m=\"4211368\">Yeah.</span></p><p><span\
  \ m=\"4211822\">AUDIENCE:</span> <span m=\"4211973\">Should</span> <span m=\"4212124\"\
  >this</span> <span m=\"4212276\">be a</span> <span m=\"4212730\">lower case</span>\
  \ <span m=\"4213184\">n?</span></p><p><span m=\"4214660\">YUFEI ZHAO:</span> <span\
  \ m=\"4214763\">Thank</span> <span m=\"4214866\">you.</span> <span m=\"4215383\"\
  >Yeah.</span> <span m=\"4216210\">This</span> <span m=\"4216320\">should</span>\
  \ <span m=\"4216440\">be</span> <span m=\"4216530\">a</span> <span m=\"4216590\"\
  >lower</span> <span m=\"4216840\">case</span> <span m=\"4217170\">n,</span> <span\
  \ m=\"4217490\">so</span> <span m=\"4217810\">the</span> <span m=\"4218200\">dimension.</span>\
  \ <span m=\"4219536\">Good.</span> <span m=\"4222780\">And</span> <span m=\"4223130\"\
  >OK, so</span> <span m=\"4223480\">then</span> <span m=\"4223630\">that's</span>\
  \ <span m=\"4223840\">the</span> <span m=\"4224050\">conclusion,</span> <span m=\"\
  4226406\">that</span> <span m=\"4229730\">the</span> <span m=\"4230110\">density</span>\
  \ <span m=\"4230540\">alpha</span> <span m=\"4231500\">is</span> <span m=\"4234800\"\
  >big</span> <span m=\"4235020\">O of</span> <span m=\"4235430\">1</span> <span m=\"\
  4235670\">over</span> <span m=\"4235870\">n.</span></p><p><span m=\"4241360\">That</span>\
  \ <span m=\"4241680\">proves</span> <span m=\"4243190\">the</span> <span m=\"4243280\"\
  >main</span> <span m=\"4243520\">theorem</span> <span m=\"4243910\">for</span> <span\
  \ m=\"4244060\">today,</span> <span m=\"4244990\">so</span> <span m=\"4245280\"\
  >Roth's</span> <span m=\"4245630\">theorem</span> <span m=\"4245980\">over</span>\
  \ <span m=\"4246490\">F3</span> <span m=\"4246910\">to</span> <span m=\"4247060\"\
  >the</span> <span m=\"4247180\">n-th.</span> <span m=\"4248940\">So</span> <span\
  \ m=\"4249030\">we</span> <span m=\"4249150\">went</span> <span m=\"4249300\">through</span>\
  \ <span m=\"4249390\">this</span> <span m=\"4249570\">Fourier</span> <span m=\"\
  4249810\">analytic</span> <span m=\"4250290\">proof.</span> <span m=\"4251540\"\
  >Next</span> <span m=\"4251910\">lecture,</span> <span m=\"4252360\">we</span> <span\
  \ m=\"4252480\">will</span> <span m=\"4252630\">see</span> <span m=\"4254170\">the</span>\
  \ <span m=\"4254290\">same</span> <span m=\"4254590\">proof</span> <span m=\"4254860\"\
  >again</span> <span m=\"4255940\">but</span> <span m=\"4256570\">done</span> <span\
  \ m=\"4257290\">in</span> <span m=\"4257440\">the</span> <span m=\"4257530\">integers</span>\
  \ <span m=\"4258400\">for</span> <span m=\"4258610\">interval.</span></p><p><span\
  \ m=\"4260800\">And</span> <span m=\"4262160\">there,</span> <span m=\"4262510\"\
  >there</span> <span m=\"4262860\">are</span> <span m=\"4262970\">some</span> <span\
  \ m=\"4264260\">difficulties</span> <span m=\"4265460\">that</span> <span m=\"4265670\"\
  >we</span> <span m=\"4265880\">don't</span> <span m=\"4266090\">see</span> <span\
  \ m=\"4266390\">over</span> <span m=\"4266630\">here.</span> <span m=\"4268340\"\
  >Because</span> <span m=\"4269990\">in</span> <span m=\"4270260\">the</span> <span\
  \ m=\"4270380\">finite</span> <span m=\"4270770\">field</span> <span m=\"4271190\"\
  >space,</span> <span m=\"4271940\">in</span> <span m=\"4272060\">the</span> <span\
  \ m=\"4272120\">finite</span> <span m=\"4272420\">field</span> <span m=\"4273440\"\
  >model,</span> <span m=\"4274940\">there's</span> <span m=\"4275120\">this</span>\
  \ <span m=\"4275330\">very</span> <span m=\"4275540\">nice</span> <span m=\"4275840\"\
  >idea</span> <span m=\"4276200\">of</span> <span m=\"4276320\">looking</span> <span\
  \ m=\"4276680\">at</span> <span m=\"4276830\">subspaces,</span> <span m=\"4278490\"\
  >so</span> <span m=\"4279170\">looking</span> <span m=\"4279500\">at</span> <span\
  \ m=\"4279650\">hyperplanes.</span> <span m=\"4281410\">Each</span> <span m=\"4281600\"\
  >Fourier</span> <span m=\"4281870\">coefficient</span> <span m=\"4282780\">gets</span>\
  \ <span m=\"4282980\">you</span> <span m=\"4283070\">down</span> <span m=\"4283430\"\
  >to</span> <span m=\"4283640\">one</span> <span m=\"4283910\">dimension</span> <span\
  \ m=\"4284330\">less.</span> <span m=\"4285820\">But</span> <span m=\"4286140\"\
  >when</span> <span m=\"4286290\">you're</span> <span m=\"4286440\">working</span>\
  \ <span m=\"4287400\">in</span> <span m=\"4287520\">the</span> <span m=\"4287640\"\
  >integers,</span> <span m=\"4289730\">there</span> <span m=\"4289880\">are</span>\
  \ <span m=\"4290000\">no</span> <span m=\"4290660\">subspaces</span> <span m=\"\
  4291680\">you</span> <span m=\"4291770\">can</span> <span m=\"4291950\">use.</span>\
  \ <span m=\"4294860\">So</span> <span m=\"4295040\">we'll</span> <span m=\"4295160\"\
  >be</span> <span m=\"4295280\">looking</span> <span m=\"4296210\">at</span> <span\
  \ m=\"4296630\">ways</span> <span m=\"4296990\">to</span> <span m=\"4297140\">get</span>\
  \ <span m=\"4297320\">around</span> <span m=\"4298040\">the</span> <span m=\"4298130\"\
  >lack</span> <span m=\"4298430\">of</span> <span m=\"4298520\">subspaces.</span></p><p><span\
  \ m=\"4299910\">And</span> <span m=\"4300080\">this</span> <span m=\"4300230\">is</span>\
  \ <span m=\"4300350\">why</span> <span m=\"4300530\">I</span> <span m=\"4300590\"\
  >said</span> <span m=\"4300760\">in</span> <span m=\"4300830\">the</span> <span\
  \ m=\"4300920\">beginning</span> <span m=\"4301310\">that</span> <span m=\"4301820\"\
  >the</span> <span m=\"4302210\">finite</span> <span m=\"4302660\">field</span> <span\
  \ m=\"4302980\">model</span> <span m=\"4303320\">is</span> <span m=\"4303470\">often</span>\
  \ <span m=\"4303790\">a</span> <span m=\"4303860\">very</span> <span m=\"4304250\"\
  >good</span> <span m=\"4304850\">playground</span> <span m=\"4306020\">for</span>\
  \ <span m=\"4309320\">additive</span> <span m=\"4309690\">combinatorics</span> <span\
  \ m=\"4310700\">type</span> <span m=\"4310940\">techniques,</span> <span m=\"4311490\"\
  >especially</span> <span m=\"4311900\">Fourier</span> <span m=\"4312290\">analytic</span>\
  \ <span m=\"4312770\">techniques.</span> <span m=\"4313940\">Because</span> <span\
  \ m=\"4314450\">in</span> <span m=\"4314660\">the</span> <span m=\"4314810\">additive--</span>\
  \ <span m=\"4315830\">in</span> <span m=\"4316010\">all</span> <span m=\"4316160\"\
  >of</span> <span m=\"4316220\">these</span> <span m=\"4316430\">techniques,</span>\
  \ <span m=\"4317120\">they</span> <span m=\"4317270\">just</span> <span m=\"4317450\"\
  >come</span> <span m=\"4317660\">out</span> <span m=\"4317780\">to</span> <span\
  \ m=\"4317840\">be</span> <span m=\"4317960\">much</span> <span m=\"4318200\">cleaner.</span>\
  \ <span m=\"4319050\">If</span> <span m=\"4319070\">you're</span> <span m=\"4319190\"\
  >working</span> <span m=\"4319610\">in</span> <span m=\"4319760\">a</span> <span\
  \ m=\"4319820\">finite</span> <span m=\"4320120\">field</span> <span m=\"4320780\"\
  >setting,</span> <span m=\"4321560\">you have</span> <span m=\"4321890\">nice</span>\
  \ <span m=\"4322130\">subspaces,</span> <span m=\"4322870\">you</span> <span m=\"\
  4323000\">have</span> <span m=\"4323180\">Fourier</span> <span m=\"4323480\">transform</span>\
  \ <span m=\"4323780\">in</span> <span m=\"4324080\">a</span> <span m=\"4324140\"\
  >very</span> <span m=\"4324320\">clean</span> <span m=\"4324620\">way.</span></p><p><span\
  \ m=\"4325160\">The</span> <span m=\"4325430\">Fourier</span> <span m=\"4325520\"\
  >transform</span> <span m=\"4326480\">always</span> <span m=\"4326840\">takes,</span>\
  \ <span m=\"4327530\">in</span> <span m=\"4327650\">this</span> <span m=\"4327800\"\
  >case,</span> <span m=\"4328130\">one</span> <span m=\"4328370\">of</span> <span\
  \ m=\"4328430\">three</span> <span m=\"4328700\">values.</span> <span m=\"4330260\"\
  >Everything's</span> <span m=\"4330680\">very</span> <span m=\"4330860\">clean.</span>\
  \ <span m=\"4331220\">Everything's</span> <span m=\"4331550\">very</span> <span\
  \ m=\"4331700\">simple.</span> <span m=\"4332300\">And</span> <span m=\"4332390\"\
  >you</span> <span m=\"4332480\">get</span> <span m=\"4332600\">to</span> <span m=\"\
  4332690\">see</span> <span m=\"4332900\">the</span> <span m=\"4333020\">idea here.</span>\
  \ <span m=\"4333490\">You</span> <span m=\"4333610\">get</span> <span m=\"4333740\"\
  >to</span> <span m=\"4333830\">see</span> <span m=\"4334010\">the</span> <span m=\"\
  4334090\">sense</span> <span m=\"4334300\">of</span> <span m=\"4334380\">the</span>\
  \ <span m=\"4334550\">increment</span> <span m=\"4334940\">argument.</span></p><p><span\
  \ m=\"4338210\">But</span> <span m=\"4339050\">once</span> <span m=\"4339290\">you</span>\
  \ <span m=\"4339590\">understand</span> <span m=\"4340100\">those</span> <span m=\"\
  4340310\">ideas</span> <span m=\"4341600\">and</span> <span m=\"4341690\">you're</span>\
  \ <span m=\"4341780\">willing</span> <span m=\"4342050\">to</span> <span m=\"4342140\"\
  >do</span> <span m=\"4342320\">more</span> <span m=\"4344250\">work,</span> <span\
  \ m=\"4345180\">then</span> <span m=\"4345520\">oftentimes,</span> <span m=\"4346320\"\
  >you</span> <span m=\"4346440\">can</span> <span m=\"4346620\">bring</span> <span\
  \ m=\"4346890\">those</span> <span m=\"4347130\">ideas</span> <span m=\"4347790\"\
  >to</span> <span m=\"4348780\">other</span> <span m=\"4349050\">settings,</span>\
  \ <span m=\"4349590\">to</span> <span m=\"4349860\">other</span> <span m=\"4350070\"\
  >abelian</span> <span m=\"4350460\">groups,</span> <span m=\"4351440\">to</span>\
  \ <span m=\"4352030\">the</span> <span m=\"4352200\">integers,</span> <span m=\"\
  4352830\">for</span> <span m=\"4353040\">instance,</span> <span m=\"4354360\">but</span>\
  \ <span m=\"4354480\">with</span> <span m=\"4354840\">more</span> <span m=\"4355140\"\
  >work</span> <span m=\"4355560\">in</span> <span m=\"4355740\">the--</span> <span\
  \ m=\"4357300\">there</span> <span m=\"4357600\">are</span> <span m=\"4357690\"\
  >some</span> <span m=\"4358500\">extra</span> <span m=\"4358770\">ingredients</span>\
  \ <span m=\"4359340\">that</span> <span m=\"4359460\">you</span> <span m=\"4359550\"\
  >need</span> <span m=\"4359670\">to</span> <span m=\"4359790\">use.</span></p><p><span\
  \ m=\"4361800\">I</span> <span m=\"4361860\">mentioned</span> <span m=\"4362670\"\
  >that</span> <span m=\"4362850\">there</span> <span m=\"4362940\">was</span> <span\
  \ m=\"4363120\">a</span> <span m=\"4364740\">bound--</span> <span m=\"4365260\"\
  >OK,</span> <span m=\"4365430\">so</span> <span m=\"4365670\">initially--</span>\
  \ <span m=\"4370160\">So</span> <span m=\"4370280\">next</span> <span m=\"4370490\"\
  >time,</span> <span m=\"4370610\">we'll</span> <span m=\"4370730\">see</span> <span\
  \ m=\"4370880\">that.</span> <span m=\"4371020\">Next</span> <span m=\"4371210\"\
  >time,</span> <span m=\"4371360\">we'll</span> <span m=\"4371510\">see</span> <span\
  \ m=\"4372410\">what</span> <span m=\"4372620\">happens</span> <span m=\"4373340\"\
  >over</span> <span m=\"4373550\">the</span> <span m=\"4373640\">integers.</span>\
  \ <span m=\"4376000\">Any</span> <span m=\"4376210\">questions?</span> <span m=\"\
  4378490\">Yes.</span></p><p><span m=\"4379187\">AUDIENCE:</span> <span m=\"4379415\"\
  >[INAUDIBLE]</span></p><p><span m=\"4383300\">YUFEI ZHAO:</span> <span m=\"4383760\"\
  >OK,</span> <span m=\"4384010\">great.</span> <span m=\"4384250\">So</span> <span\
  \ m=\"4384400\">question is</span> <span m=\"4384730\">why</span> <span m=\"4385240\"\
  >the</span> <span m=\"4385320\">process</span> <span m=\"4385690\">must</span> <span\
  \ m=\"4385930\">stop</span> <span m=\"4386770\">after</span> <span m=\"4387210\"\
  >at most</span> <span m=\"4387670\">8</span> <span m=\"4387850\">over</span> <span\
  \ m=\"4388060\">alpha</span> <span m=\"4388360\">steps?</span> <span m=\"4392430\"\
  >So</span> <span m=\"4393090\">you</span> <span m=\"4393210\">know</span> <span\
  \ m=\"4393330\">that</span> <span m=\"4393440\">the</span> <span m=\"4393540\">density</span>\
  \ <span m=\"4393990\">doubles</span> <span m=\"4394680\">after</span> <span m=\"\
  4394950\">this</span> <span m=\"4395100\">many</span> <span m=\"4395340\">steps,</span>\
  \ <span m=\"4395700\">doubles</span> <span m=\"4396000\">again</span> <span m=\"\
  4396270\">after</span> <span m=\"4396480\">that</span> <span m=\"4396600\">many</span>\
  \ <span m=\"4396780\">steps.</span> <span m=\"4397380\">So</span> <span m=\"4397830\"\
  >eventually,</span> <span m=\"4399670\">if</span> <span m=\"4399960\">it</span>\
  \ <span m=\"4400080\">keeps</span> <span m=\"4400380\">on</span> <span m=\"4400500\"\
  >doubling, it</span> <span m=\"4400920\">cannot</span> <span m=\"4401220\">keep</span>\
  \ <span m=\"4401460\">on</span> <span m=\"4401580\">doubling</span> <span m=\"4401970\"\
  >forever.</span></p><p><span m=\"4404360\">So</span> <span m=\"4404410\">this</span>\
  \ <span m=\"4404590\">process</span> <span m=\"4404950\">cannot</span> <span m=\"\
  4405250\">keep</span> <span m=\"4405430\">on</span> <span m=\"4405550\">doubling</span>\
  \ <span m=\"4405910\">forever.</span> <span m=\"4406570\">So</span> <span m=\"4406770\"\
  >it</span> <span m=\"4406860\">must</span> <span m=\"4407170\">stop--</span> <span\
  \ m=\"4408820\">so</span> <span m=\"4408970\">cannot</span> <span m=\"4411840\"\
  >double</span> <span m=\"4415150\">more</span> <span m=\"4415480\">than</span> <span\
  \ m=\"4417640\">log</span> <span m=\"4418020\">base</span> <span m=\"4418150\">2</span>\
  \ <span m=\"4418420\">of</span> <span m=\"4418540\">1</span> <span m=\"4418720\"\
  >over</span> <span m=\"4418960\">alpha</span> <span m=\"4419090\">times.</span>\
  \ <span m=\"4422980\">And</span> <span m=\"4423100\">that</span> <span m=\"4423220\"\
  >point,</span> <span m=\"4423460\">you</span> <span m=\"4424030\">have</span> <span\
  \ m=\"4424150\">to</span> <span m=\"4424240\">stop.</span> <span m=\"4425440\">So</span>\
  \ <span m=\"4425590\">how</span> <span m=\"4425740\">many</span> <span m=\"4425950\"\
  >steps</span> <span m=\"4426340\">have</span> <span m=\"4426430\">you</span> <span\
  \ m=\"4426550\">taken?</span> <span m=\"4427270\">Well,</span> <span m=\"4427450\"\
  >you</span> <span m=\"4427600\">sum</span> <span m=\"4428020\">this</span> <span\
  \ m=\"4428230\">geometric</span> <span m=\"4428800\">series.</span></p><p><span\
  \ m=\"4429420\">So</span> <span m=\"4429520\">this--</span> <span m=\"4430320\"\
  >and</span> <span m=\"4430420\">the</span> <span m=\"4430480\">next</span> <span\
  \ m=\"4430750\">thing</span> <span m=\"4431800\">is</span> <span m=\"4435385\">that</span>\
  \ <span m=\"4435830\">you</span> <span m=\"4435940\">sum</span> <span m=\"4436240\"\
  >this</span> <span m=\"4436390\">geometric</span> <span m=\"4436900\">series.</span>\
  \ <span m=\"4437840\">And</span> <span m=\"4437950\">that</span> <span m=\"4438160\"\
  >geometric</span> <span m=\"4438550\">series</span> <span m=\"4438910\">sums</span>\
  \ <span m=\"4439300\">to</span> <span m=\"4440710\">8</span> <span m=\"4440860\"\
  >over</span> <span m=\"4441070\">alpha.</span> <span m=\"4450470\">Great.</span>\
  \ <span m=\"4450730\">So</span> <span m=\"4451620\">let's</span> <span m=\"4451800\"\
  >finish</span> <span m=\"4452100\">here.</span> <span m=\"4452280\">So</span> <span\
  \ m=\"4452400\">next</span> <span m=\"4452640\">time,</span> <span m=\"4452850\"\
  >we'll</span> <span m=\"4452970\">see</span> <span m=\"4453810\">Roth's</span> <span\
  \ m=\"4454230\">proof</span> <span m=\"4454650\">of</span> <span m=\"4454800\">Roth's</span>\
  \ <span m=\"4455130\">theorem.</span></p>"
type: course
uid: b6005bf7bcb87c4ec8c8c0b1c9014989

---
None