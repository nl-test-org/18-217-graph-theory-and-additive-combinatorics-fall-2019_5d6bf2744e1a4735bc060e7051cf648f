---
about_this_resource_text: "<p><strong>Description:</strong> What can we say about\
  \ sets A of integers whose sumset A + A is small? Over the next several lectures,\
  \ Professor Zhao discusses Freiman&rsquo;s theorem, a foundational theorem in additive\
  \ combinatorics, that characterizes sets with small doubling.</p><p>This lecture\
  \ begins with a discussion and statement of Freiman&rsquo;s theorem, and then basic\
  \ tools including Ruzsa triangle inequality and Pl\xFCnnecke&ndash;Ruzsa inequality.</p>\
  \ <p><strong>Instructor:</strong> Yufei Zhao</p>"
course_id: 18-217-graph-theory-and-additive-combinatorics-fall-2019
embedded_media:
- id: Video-YouTube-Stream
  media_location: oLwZFBZylUw
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  title: Video-YouTube-Stream
  type: Video
  uid: 0712b276b59b3f4e08abd1fc63a494f2
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/oLwZFBZylUw/default.jpg
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7967b87c5a92febe8c9431ae54df445a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: oLwZFBZylUw
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c4967681c8672bf22ff0cafa5c19de3d
- id: oLwZFBZylUw.srt
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-21-structure-of-set-addition-i-introduction-to-freiman2019s-theorem/oLwZFBZylUw.srt
  title: 3play caption file
  type: null
  uid: 132df6eeb03996f773ee5ddea1c2a136
- id: oLwZFBZylUw.pdf
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-21-structure-of-set-addition-i-introduction-to-freiman2019s-theorem/oLwZFBZylUw.pdf
  title: 3play pdf file
  type: null
  uid: f011ee6769c3d95d2c5b90ee073bec44
- id: Caption-3Play YouTube id-SRT
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e41b31d785a883598575573caec7e78a
- id: Transcript-3Play YouTube id-PDF
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 986ece1e36795a7efd46aa780ad1c8c4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.217F19/MIT18_217F19_lec21_300k.mp4
  parent_uid: c4fbceccd2daf74551610e6adcd67b87
  title: Video-Internet Archive-MP4
  type: Video
  uid: c21fdd8e6d46e445ed73f0d8af5b4a60
inline_embed_id: 1537449lecture21structureofsetadditioniintroductiontofreimanstheorem70101734
layout: video
order_index: null
parent_uid: fa9006ef3a16a8b931aa8d93a378115e
related_resources_text: ''
short_url: lecture-21-structure-of-set-addition-i-introduction-to-freiman2019s-theorem
technical_location: https://ocw.mit.edu/courses/mathematics/18-217-graph-theory-and-additive-combinatorics-fall-2019/video-lectures/lecture-21-structure-of-set-addition-i-introduction-to-freiman2019s-theorem
template_type: Tabbed
title: "Lecture 21: Structure of Set Addition I: Introduction to Freiman\u2019s Theorem\
  \ \t"
transcript: "<p><span m=\"18600\">YUFEI ZHAO:</span> <span m=\"18645\">All</span>\
  \ <span m=\"18690\">right,</span> <span m=\"18960\">today</span> <span m=\"19260\"\
  >we're</span> <span m=\"19380\">going</span> <span m=\"19530\">to</span> <span m=\"\
  19620\">start</span> <span m=\"19950\">a</span> <span m=\"20340\">new</span> <span\
  \ m=\"20520\">topic</span> <span m=\"21000\">an</span> <span m=\"21140\">additive</span>\
  \ <span m=\"21540\">combinatorics.</span> <span m=\"22850\">And</span> <span m=\"\
  22980\">this</span> <span m=\"23130\">is</span> <span m=\"23220\">a</span> <span\
  \ m=\"23280\">fairly</span> <span m=\"23580\">central</span> <span m=\"24060\">topic</span>\
  \ <span m=\"25260\">having</span> <span m=\"25650\">to</span> <span m=\"25710\"\
  >do</span> <span m=\"26040\">with</span> <span m=\"26790\">the</span> <span m=\"\
  26910\">structure</span> <span m=\"27570\">of</span> <span m=\"27870\">set</span>\
  \ <span m=\"28320\">addition.</span> <span m=\"43810\">So</span> <span m=\"43930\"\
  >the</span> <span m=\"43990\">main</span> <span m=\"44200\">players</span> <span\
  \ m=\"44710\">that</span> <span m=\"44830\">we're</span> <span m=\"44920\">going</span>\
  \ <span m=\"44980\">to</span> <span m=\"45090\">be</span> <span m=\"45160\">seeing</span>\
  \ <span m=\"46060\">in</span> <span m=\"46330\">this</span> <span m=\"46570\">chapter</span>\
  \ <span m=\"47770\">have</span> <span m=\"47980\">to</span> <span m=\"48100\">do</span>\
  \ <span m=\"48310\">with,</span> <span m=\"49810\">if</span> <span m=\"49990\">you</span>\
  \ <span m=\"50140\">start</span> <span m=\"50590\">with</span> <span m=\"50800\"\
  >a</span> <span m=\"50860\">subset</span> <span m=\"51520\">of</span> <span m=\"\
  52270\">some</span> <span m=\"53320\">obedient</span> <span m=\"53740\">group</span>\
  \ <span m=\"56410\">under</span> <span m=\"57070\">addition--</span> <span m=\"\
  59980\">not</span> <span m=\"60130\">necessarily</span> <span m=\"60700\">finite.</span>\
  \ <span m=\"61150\">So</span> <span m=\"61900\">the</span> <span m=\"62020\">obedient</span>\
  \ <span m=\"62380\">group</span> <span m=\"62770\">that</span> <span m=\"63250\"\
  >I'm</span> <span m=\"63340\">going</span> <span m=\"63580\">to</span> <span m=\"\
  63670\">keep</span> <span m=\"63910\">in</span> <span m=\"63970\">mind,</span> <span\
  \ m=\"64959\">the</span> <span m=\"65050\">ones</span> <span m=\"65290\">that</span>\
  \ <span m=\"65379\">will</span> <span m=\"65500\">come</span> <span m=\"65770\"\
  >up</span> <span m=\"66160\">generally</span> <span m=\"66580\">are</span> <span\
  \ m=\"66730\">integers,</span> <span m=\"68220\">z mod</span> <span m=\"68640\"\
  >n</span> <span m=\"69940\">or</span> <span m=\"70090\">the</span> <span m=\"70220\"\
  >finite</span> <span m=\"70660\">field</span> <span m=\"71020\">model.</span></p><p><span\
  \ m=\"75260\">We're</span> <span m=\"75380\">going</span> <span m=\"75470\">to</span>\
  \ <span m=\"75570\">be</span> <span m=\"75680\">looking</span> <span m=\"76190\"\
  >at</span> <span m=\"77540\">objects</span> <span m=\"78140\">such</span> <span\
  \ m=\"78470\">as</span> <span m=\"78755\">a</span> <span m=\"79040\">sum</span>\
  \ <span m=\"79380\">set,</span> <span m=\"80480\">so</span> <span m=\"80750\">a</span>\
  \ <span m=\"81050\">plus</span> <span m=\"81500\">b,</span> <span m=\"82370\">meaning</span>\
  \ <span m=\"83180\">the</span> <span m=\"83300\">set</span> <span m=\"83660\">of</span>\
  \ <span m=\"84380\">elements</span> <span m=\"84830\">that</span> <span m=\"84950\"\
  >can</span> <span m=\"85100\">be</span> <span m=\"85220\">written</span> <span m=\"\
  86000\">as</span> <span m=\"86150\">a</span> <span m=\"86210\">sum,</span> <span\
  \ m=\"87680\">where</span> <span m=\"88100\">you</span> <span m=\"88220\">take</span>\
  \ <span m=\"88460\">one</span> <span m=\"88820\">element</span> <span m=\"89180\"\
  >from</span> <span m=\"89450\">a</span> <span m=\"89780\">and</span> <span m=\"\
  91100\">another</span> <span m=\"91610\">from</span> <span m=\"92000\">b.</span>\
  \ <span m=\"94510\">Likewise,</span> <span m=\"95230\">you</span> <span m=\"95350\"\
  >can</span> <span m=\"95530\">also</span> <span m=\"95800\">have</span> <span m=\"\
  96160\">a</span> <span m=\"96550\">minus</span> <span m=\"97030\">b</span> <span\
  \ m=\"97930\">defined</span> <span m=\"98410\">similarly,</span> <span m=\"99340\"\
  >now</span> <span m=\"99590\">taking</span> <span m=\"100060\">a</span> <span m=\"\
  100450\">minus</span> <span m=\"100900\">b.</span> <span m=\"105550\">We</span>\
  \ <span m=\"105700\">can</span> <span m=\"106390\">iterate</span> <span m=\"106930\"\
  >this</span> <span m=\"107200\">operation.</span> <span m=\"108430\">So</span> <span\
  \ m=\"110140\">kA,</span> <span m=\"110920\">so</span> <span m=\"111610\">2A,</span>\
  \ <span m=\"112270\">3A,</span> <span m=\"112630\">4A,</span> <span m=\"113450\"\
  >for</span> <span m=\"113860\">instance,</span> <span m=\"114760\">means</span>\
  \ <span m=\"115870\">I</span> <span m=\"116350\">add</span> <span m=\"116770\">A</span>\
  \ <span m=\"117010\">to</span> <span m=\"117250\">itself</span> <span m=\"119290\"\
  >k</span> <span m=\"119590\">times,</span> <span m=\"125340\">not</span> <span m=\"\
  125520\">to</span> <span m=\"125610\">be</span> <span m=\"125730\">confused</span>\
  \ <span m=\"126650\">with</span> <span m=\"126980\">a</span> <span m=\"127070\"\
  >dilation,</span> <span m=\"127800\">which</span> <span m=\"128009\">we'll</span>\
  \ <span m=\"128190\">denote</span> <span m=\"128520\">by</span> <span m=\"128729\"\
  >k</span> <span m=\"129400\">dot</span> <span m=\"129810\">A.</span> <span m=\"\
  131330\">So</span> <span m=\"131480\">this</span> <span m=\"132650\">is</span> <span\
  \ m=\"132830\">notation</span> <span m=\"133430\">for</span> <span m=\"134360\"\
  >multiplying</span> <span m=\"135290\">every</span> <span m=\"135560\">element</span>\
  \ <span m=\"135950\">of</span> <span m=\"136040\">A</span> <span m=\"136370\">by</span>\
  \ <span m=\"136670\">the</span> <span m=\"136760\">number</span> <span m=\"137240\"\
  >k.</span></p><p><span m=\"144360\">So</span> <span m=\"144490\">given</span> <span\
  \ m=\"145480\">a</span> <span m=\"145540\">subset</span> <span m=\"145990\">of</span>\
  \ <span m=\"146080\">integers</span> <span m=\"146890\">I</span> <span m=\"146980\"\
  >can</span> <span m=\"147130\">do</span> <span m=\"147280\">these</span> <span m=\"\
  147520\">operations</span> <span m=\"148120\">to</span> <span m=\"148240\">the</span>\
  \ <span m=\"148330\">set.</span> <span m=\"149200\">And</span> <span m=\"149390\"\
  >I</span> <span m=\"149440\">want</span> <span m=\"149620\">to</span> <span m=\"\
  149740\">ask,</span> <span m=\"150370\">how</span> <span m=\"150670\">does</span>\
  \ <span m=\"150910\">the</span> <span m=\"151030\">size</span> <span m=\"151630\"\
  >of</span> <span m=\"151750\">the</span> <span m=\"151840\">set</span> <span m=\"\
  152230\">change</span> <span m=\"153400\">when</span> <span m=\"154240\">I</span>\
  \ <span m=\"154390\">do</span> <span m=\"154540\">these</span> <span m=\"154720\"\
  >operations?</span> <span m=\"157750\">For</span> <span m=\"157930\">example,</span>\
  \ <span m=\"159100\">what</span> <span m=\"159280\">is</span> <span m=\"159400\"\
  >the</span> <span m=\"161170\">largest</span> <span m=\"162190\">or</span> <span\
  \ m=\"162310\">the</span> <span m=\"162400\">smallest?</span> <span m=\"163120\"\
  >So</span> <span m=\"163270\">how</span> <span m=\"163540\">large</span> <span m=\"\
  165160\">or</span> <span m=\"165310\">small</span> <span m=\"167700\">can</span>\
  \ <span m=\"169830\">A</span> <span m=\"170370\">plus</span> <span m=\"170940\"\
  >A</span> <span m=\"171330\">be</span> <span m=\"173000\">for</span> <span m=\"\
  174350\">a</span> <span m=\"174440\">given</span> <span m=\"176240\">set</span>\
  \ <span m=\"176570\">size,</span> <span m=\"178120\">A?</span></p><p><span m=\"\
  179590\">So</span> <span m=\"180530\">if I</span> <span m=\"180740\">allow</span>\
  \ <span m=\"181010\">you</span> <span m=\"181160\">to</span> <span m=\"181280\"\
  >use</span> <span m=\"182300\">10</span> <span m=\"182630\">elements,</span> <span\
  \ m=\"184070\">how</span> <span m=\"184250\">can</span> <span m=\"184430\">you</span>\
  \ <span m=\"184520\">make</span> <span m=\"184790\">A</span> <span m=\"184970\"\
  >plus A</span> <span m=\"185270\">as</span> <span m=\"185660\">big</span> <span\
  \ m=\"185900\">as</span> <span m=\"186020\">possible?</span> <span m=\"187290\"\
  >And</span> <span m=\"187390\">how</span> <span m=\"187460\">can</span> <span m=\"\
  187610\">you</span> <span m=\"187670\">make</span> <span m=\"187910\">it</span>\
  \ <span m=\"188000\">as</span> <span m=\"188120\">small</span> <span m=\"188510\"\
  >as</span> <span m=\"188660\">possible?</span> <span m=\"190160\">So</span> <span\
  \ m=\"190280\">this</span> <span m=\"190430\">is</span> <span m=\"190520\">not</span>\
  \ <span m=\"190730\">a</span> <span m=\"190760\">hard</span> <span m=\"191000\"\
  >question.</span> <span m=\"192500\">How</span> <span m=\"192650\">can</span> <span\
  \ m=\"192770\">you</span> <span m=\"192860\">make</span> <span m=\"193070\">it</span>\
  \ <span m=\"193220\">as</span> <span m=\"193430\">big</span> <span m=\"193670\"\
  >as</span> <span m=\"193820\">possible?</span> <span m=\"198700\">So</span> <span\
  \ m=\"198860\">what's</span> <span m=\"199100\">the</span> <span m=\"199190\">maximum</span>\
  \ <span m=\"199880\">size</span> <span m=\"200560\">A</span> <span m=\"200690\"\
  >plus A</span> <span m=\"201080\">can</span> <span m=\"201260\">be</span> <span\
  \ m=\"201870\">as</span> <span m=\"202010\">a</span> <span m=\"202070\">function</span>\
  \ <span m=\"202430\">of</span> <span m=\"202550\">A?</span></p><p><span m=\"204430\"\
  >Well,</span> <span m=\"204660\">I'm</span> <span m=\"204800\">looking</span> <span\
  \ m=\"205070\">at</span> <span m=\"205130\">pairwise</span> <span m=\"205620\">sums,</span>\
  \ <span m=\"207120\">so</span> <span m=\"207410\">if</span> <span m=\"207590\">there</span>\
  \ <span m=\"207710\">are</span> <span m=\"207800\">no</span> <span m=\"208130\"\
  >collisions</span> <span m=\"208790\">between</span> <span m=\"209300\">different</span>\
  \ <span m=\"209630\">pairwise</span> <span m=\"210020\">sums,</span> <span m=\"\
  210740\">this</span> <span m=\"210920\">is</span> <span m=\"211040\">as</span> <span\
  \ m=\"211220\">large</span> <span m=\"211520\">as</span> <span m=\"211640\">possible.</span>\
  \ <span m=\"212720\">And</span> <span m=\"213020\">then</span> <span m=\"213260\"\
  >it's</span> <span m=\"213470\">not</span> <span m=\"213710\">hard</span> <span\
  \ m=\"213920\">to</span> <span m=\"213980\">see</span> <span m=\"214250\">that</span>\
  \ <span m=\"214400\">the</span> <span m=\"214490\">maximum</span> <span m=\"215060\"\
  >possible</span> <span m=\"215600\">is</span> <span m=\"216200\">the</span> <span\
  \ m=\"216290\">size</span> <span m=\"216710\">of</span> <span m=\"216800\">A</span>\
  \ <span m=\"217040\">plus</span> <span m=\"217400\">1,</span> <span m=\"218150\"\
  >choose</span> <span m=\"218510\">2.</span> <span m=\"221370\">So</span> <span m=\"\
  221940\">since</span> <span m=\"223950\">at</span> <span m=\"224580\">most,</span>\
  \ <span m=\"226280\">this</span> <span m=\"226470\">many</span> <span m=\"226740\"\
  >pairs</span> <span m=\"232200\">and</span> <span m=\"232455\">space</span> <span\
  \ m=\"232980\">possible</span> <span m=\"234570\">if</span> <span m=\"234930\">all</span>\
  \ <span m=\"235590\">sums</span> <span m=\"236130\">are</span> <span m=\"236220\"\
  >distinct.</span> <span m=\"240610\">So</span> <span m=\"240790\">for</span> <span\
  \ m=\"240970\">example,</span> <span m=\"243040\">in</span> <span m=\"243430\">integers,</span>\
  \ <span m=\"244300\">you</span> <span m=\"244390\">can</span> <span m=\"244510\"\
  >take</span> <span m=\"244780\">1,</span> <span m=\"245280\">2,</span> <span m=\"\
  246340\">2</span> <span m=\"246580\">squared,</span> <span m=\"247300\">and</span>\
  \ <span m=\"247390\">so</span> <span m=\"247630\">on.</span> <span m=\"251126\"\
  >So</span> <span m=\"251610\">that</span> <span m=\"251800\">will</span> <span m=\"\
  251890\">give</span> <span m=\"252100\">you</span> <span m=\"252490\">the</span>\
  \ <span m=\"252610\">span.</span></p><p><span m=\"255040\">The</span> <span m=\"\
  255140\">minimum</span> <span m=\"255590\">possible</span> <span m=\"256350\">is</span>\
  \ <span m=\"256399\">also</span> <span m=\"256670\">not</span> <span m=\"256970\"\
  >too</span> <span m=\"257180\">hard.</span> <span m=\"260910\">We're</span> <span\
  \ m=\"261160\">allowed</span> <span m=\"261399\">to</span> <span m=\"261490\">work</span>\
  \ <span m=\"261730\">in</span> <span m=\"261820\">a</span> <span m=\"261880\">general</span>\
  \ <span m=\"262210\">obedient</span> <span m=\"262600\">group.</span> <span m=\"\
  263230\">So</span> <span m=\"264250\">in</span> <span m=\"264370\">that</span> <span\
  \ m=\"264490\">case,</span> <span m=\"265040\">the</span> <span m=\"265060\">minimum</span>\
  \ <span m=\"267430\">could</span> <span m=\"267580\">be</span> <span m=\"267670\"\
  >just</span> <span m=\"267910\">the</span> <span m=\"268000\">size</span> <span\
  \ m=\"268420\">of</span> <span m=\"268540\">A.</span> <span m=\"269770\">The</span>\
  \ <span m=\"269860\">size</span> <span m=\"270190\">is</span> <span m=\"270310\"\
  >always</span> <span m=\"270730\">at</span> <span m=\"270790\">least</span> <span\
  \ m=\"271180\">the</span> <span m=\"271270\">size</span> <span m=\"271600\">of</span>\
  \ <span m=\"271690\">A.</span> <span m=\"272860\">And</span> <span m=\"273340\"\
  >this</span> <span m=\"273520\">is</span> <span m=\"273640\">tight</span> <span\
  \ m=\"275620\">if</span> <span m=\"276010\">A</span> <span m=\"276220\">is</span>\
  \ <span m=\"276340\">a</span> <span m=\"276400\">subgroup.</span> <span m=\"279080\"\
  >If</span> <span m=\"279530\">you have</span> <span m=\"279650\">a</span> <span\
  \ m=\"279710\">subgroup,</span> <span m=\"280400\">then</span> <span m=\"280670\"\
  >it's</span> <span m=\"280790\">closed</span> <span m=\"281240\">under</span> <span\
  \ m=\"281540\">addition.</span> <span m=\"282780\">So</span> <span m=\"283040\"\
  >the</span> <span m=\"284060\">set</span> <span m=\"284420\">does</span> <span m=\"\
  284600\">not</span> <span m=\"284870\">expand</span> <span m=\"285620\">under</span>\
  \ <span m=\"285920\">addition.</span></p><p><span m=\"288030\">In</span> <span m=\"\
  288170\">the</span> <span m=\"288260\">integers,</span> <span m=\"289010\">you</span>\
  \ <span m=\"289100\">don't</span> <span m=\"289280\">have</span> <span m=\"289670\"\
  >any</span> <span m=\"290060\">finite</span> <span m=\"290420\">subgroups.</span>\
  \ <span m=\"292520\">So</span> <span m=\"292610\">if</span> <span m=\"292700\">I</span>\
  \ <span m=\"292760\">give</span> <span m=\"292970\">you</span> <span m=\"293120\"\
  >k</span> <span m=\"293600\">integers,</span> <span m=\"294960\">what's</span> <span\
  \ m=\"295070\">the</span> <span m=\"295160\">smallest,</span> <span m=\"295940\"\
  >the</span> <span m=\"296030\">sum</span> <span m=\"296330\">set</span> <span m=\"\
  296600\">can be?</span></p><p><span m=\"297564\">AUDIENCE:</span> <span m=\"297724\"\
  >2k</span> <span m=\"297884\">minus</span> <span m=\"298046\">1.</span></p><p><span\
  \ m=\"299010\">YUFEI ZHAO:</span> <span m=\"299070\">2k</span> <span m=\"299280\"\
  >minus</span> <span m=\"299550\">1, right?</span> <span m=\"299920\">So</span> <span\
  \ m=\"299970\">the</span> <span m=\"300060\">example</span> <span m=\"300570\">is</span>\
  \ <span m=\"300750\">when</span> <span m=\"300900\">you</span> <span m=\"300990\"\
  >have</span> <span m=\"301170\">an</span> <span m=\"301260\">arithmetic</span> <span\
  \ m=\"301740\">progression.</span> <span m=\"302628\">So</span> <span m=\"303852\"\
  >in</span> <span m=\"304260\">integers,</span> <span m=\"305360\">the</span> <span\
  \ m=\"305430\">minimum</span> <span m=\"305850\">is</span> <span m=\"306900\">2k</span>\
  \ <span m=\"307200\">minus</span> <span m=\"307520\">1.</span> <span m=\"310440\"\
  >And</span> <span m=\"310620\">it's</span> <span m=\"310740\">achieved</span> <span\
  \ m=\"314070\">for</span> <span m=\"316050\">an</span> <span m=\"316170\">arithmetic</span>\
  \ <span m=\"316860\">progression.</span></p><p><span m=\"318360\">So</span> <span\
  \ m=\"318510\">let</span> <span m=\"318600\">me</span> <span m=\"318690\">just</span>\
  \ <span m=\"318840\">give</span> <span m=\"318990\">you</span> <span m=\"319080\"\
  >the</span> <span m=\"319320\">one-line</span> <span m=\"319770\">proof</span> <span\
  \ m=\"320130\">why</span> <span m=\"321360\">you</span> <span m=\"321510\">always</span>\
  \ <span m=\"321810\">have</span> <span m=\"322050\">at</span> <span m=\"322140\"\
  >least</span> <span m=\"322560\">this</span> <span m=\"322800\">many</span> <span\
  \ m=\"323070\">elements,</span> <span m=\"324000\">is</span> <span m=\"324270\"\
  >if</span> <span m=\"326820\">A</span> <span m=\"327240\">has</span> <span m=\"\
  327510\">elements</span> <span m=\"329010\">sorted</span> <span m=\"329850\">like</span>\
  \ <span m=\"330090\">this,</span> <span m=\"331530\">then</span> <span m=\"332280\"\
  >the</span> <span m=\"332370\">following</span> <span m=\"334350\">elements</span>\
  \ <span m=\"334980\">are</span> <span m=\"335700\">distinct</span> <span m=\"336930\"\
  >in</span> <span m=\"337560\">the</span> <span m=\"337680\">sum</span> <span m=\"\
  337910\">set.</span> <span m=\"340020\">So</span> <span m=\"340200\">you</span>\
  \ <span m=\"340320\">start</span> <span m=\"340710\">with</span> <span m=\"341190\"\
  >A plus</span> <span m=\"341370\">A.</span> <span m=\"341800\">And</span> <span\
  \ m=\"341820\">then</span> <span m=\"341940\">you</span> <span m=\"342060\">move</span>\
  \ <span m=\"343790\">A1</span> <span m=\"344190\">plus</span> <span m=\"344400\"\
  >A2,</span> <span m=\"344910\">A1</span> <span m=\"345180\">plus A3,</span> <span\
  \ m=\"345720\">and</span> <span m=\"345810\">so</span> <span m=\"345960\">on,</span>\
  \ <span m=\"346400\">to</span> <span m=\"346530\">A1</span> <span m=\"346800\">plus</span>\
  \ <span m=\"346990\">Ak.</span> <span m=\"347850\">And</span> <span m=\"347940\"\
  >then</span> <span m=\"348060\">you</span> <span m=\"348150\">move</span> <span\
  \ m=\"348450\">the</span> <span m=\"348660\">first</span> <span m=\"348990\">element</span>\
  \ <span m=\"349560\">forward.</span> <span m=\"356310\">OK,</span> <span m=\"356630\"\
  >so</span> <span m=\"356750\">here</span> <span m=\"357020\">you</span> <span m=\"\
  357170\">already</span> <span m=\"357560\">see</span> <span m=\"358700\">2k</span>\
  \ <span m=\"359840\">minus</span> <span m=\"360230\">1</span> <span m=\"360580\"\
  >distinct</span> <span m=\"362870\">elements</span> <span m=\"364810\">in</span>\
  \ <span m=\"365090\">A</span> <span m=\"365240\">plus</span> <span m=\"365530\"\
  >A.</span></p><p><span m=\"370420\">OK,</span> <span m=\"370750\">so</span> <span\
  \ m=\"370870\">these</span> <span m=\"371080\">are</span> <span m=\"371590\">fairly</span>\
  \ <span m=\"371980\">simple</span> <span m=\"372520\">examples,</span> <span m=\"\
  373060\">fairly</span> <span m=\"373390\">simple</span> <span m=\"373720\">questions.</span>\
  \ <span m=\"374350\">So</span> <span m=\"374440\">now</span> <span m=\"374590\"\
  >let's</span> <span m=\"374800\">get</span> <span m=\"374950\">to</span> <span m=\"\
  375040\">some</span> <span m=\"375220\">more</span> <span m=\"375400\">interesting</span>\
  \ <span m=\"375880\">questions,</span> <span m=\"377960\">which</span> <span m=\"\
  378280\">is,</span> <span m=\"379390\">what</span> <span m=\"379660\">can</span>\
  \ <span m=\"379900\">you</span> <span m=\"380080\">say</span> <span m=\"380560\"\
  >about</span> <span m=\"380940\">a</span> <span m=\"381010\">set</span> <span m=\"\
  382090\">if</span> <span m=\"382300\">you</span> <span m=\"382450\">know</span>\
  \ <span m=\"382840\">that it</span> <span m=\"383080\">has</span> <span m=\"383350\"\
  >small</span> <span m=\"383980\">doubling?</span> <span m=\"385390\">If</span> <span\
  \ m=\"385600\">it</span> <span m=\"385720\">doesn't</span> <span m=\"386110\">expand</span>\
  \ <span m=\"386710\">by</span> <span m=\"386920\">very</span> <span m=\"387160\"\
  >much,</span> <span m=\"388030\">what</span> <span m=\"388180\">can</span> <span\
  \ m=\"388360\">you</span> <span m=\"388450\">tell</span> <span m=\"388660\">me</span>\
  \ <span m=\"388810\">about</span> <span m=\"389050\">the</span> <span m=\"389140\"\
  >set?</span> <span m=\"390510\">And</span> <span m=\"390850\">for</span> <span m=\"\
  390990\">that,</span> <span m=\"391250\">let</span> <span m=\"391350\">me</span>\
  \ <span m=\"391470\">define</span> <span m=\"391950\">the</span> <span m=\"392040\"\
  >notion</span> <span m=\"392400\">of</span> <span m=\"392510\">a</span> <span m=\"\
  392580\">doubling</span> <span m=\"393000\">constant.</span></p><p><span m=\"398960\"\
  >So</span> <span m=\"399110\">the</span> <span m=\"399200\">doubling</span> <span\
  \ m=\"399560\">constant</span> <span m=\"400430\">of</span> <span m=\"402460\">A</span>\
  \ <span m=\"403010\">is</span> <span m=\"403190\">defined</span> <span m=\"403670\"\
  >to</span> <span m=\"403790\">be</span> <span m=\"404000\">the</span> <span m=\"\
  404120\">number</span> <span m=\"405000\">which</span> <span m=\"405140\">we</span>\
  \ <span m=\"405320\">often</span> <span m=\"405620\">denote</span> <span m=\"405980\"\
  >by</span> <span m=\"406200\">k,</span> <span m=\"411330\">the</span> <span m=\"\
  411800\">number</span> <span m=\"412180\">obtained</span> <span m=\"412540\">by</span>\
  \ <span m=\"412840\">dividing</span> <span m=\"413440\">the</span> <span m=\"413530\"\
  >size</span> <span m=\"413860\">of</span> <span m=\"413980\">A</span> <span m=\"\
  414100\">plus A</span> <span m=\"414730\">by</span> <span m=\"415330\">the</span>\
  \ <span m=\"415390\">size</span> <span m=\"415690\">of</span> <span m=\"415780\"\
  >A.</span> <span m=\"416886\">And</span> <span m=\"417380\">we</span> <span m=\"\
  417500\">would</span> <span m=\"417740\">like</span> <span m=\"417920\">to</span>\
  \ <span m=\"418040\">understand--</span> <span m=\"419075\">and</span> <span m=\"\
  419420\">this</span> <span m=\"419570\">is</span> <span m=\"419660\">the</span>\
  \ <span m=\"419720\">main</span> <span m=\"419960\">question</span> <span m=\"421070\"\
  >that's</span> <span m=\"421340\">addressed</span> <span m=\"424250\">in</span>\
  \ <span m=\"424370\">the</span> <span m=\"424490\">upcoming</span> <span m=\"424880\"\
  >lectures</span> <span m=\"426290\">is,</span> <span m=\"427160\">what</span> <span\
  \ m=\"427370\">is</span> <span m=\"427550\">the</span> <span m=\"427880\">structure</span>\
  \ <span m=\"435360\">of</span> <span m=\"436090\">a</span> <span m=\"436170\">set</span>\
  \ <span m=\"438640\">with</span> <span m=\"439390\">bounded</span> <span m=\"441760\"\
  >doubling</span> <span m=\"442120\">constant?</span></p><p><span m=\"449960\">So</span>\
  \ <span m=\"450880\">for</span> <span m=\"451060\">instance,</span> <span m=\"451870\"\
  >think</span> <span m=\"452110\">of</span> <span m=\"452200\">k as</span> <span\
  \ m=\"452650\">fixed.</span> <span m=\"455960\">Let's</span> <span m=\"456200\"\
  >say</span> <span m=\"456410\">k is</span> <span m=\"456770\">100.</span> <span\
  \ m=\"457400\">If</span> <span m=\"457550\">you</span> <span m=\"457640\">know</span>\
  \ <span m=\"457850\">a</span> <span m=\"457910\">set</span> <span m=\"458210\">has</span>\
  \ <span m=\"458450\">doubling</span> <span m=\"458780\">constant,</span> <span m=\"\
  459230\">at</span> <span m=\"459380\">most,</span> <span m=\"459760\">100,</span>\
  \ <span m=\"461730\">what</span> <span m=\"461880\">can</span> <span m=\"462030\"\
  >you</span> <span m=\"462150\">tell</span> <span m=\"462360\">me</span> <span m=\"\
  462750\">about</span> <span m=\"462990\">the</span> <span m=\"463080\">structure</span>\
  \ <span m=\"463530\">of</span> <span m=\"463650\">the</span> <span m=\"463770\"\
  >set?</span> <span m=\"465570\">So</span> <span m=\"465690\">that's</span> <span\
  \ m=\"465900\">the</span> <span m=\"466020\">main</span> <span m=\"466200\">question.</span>\
  \ <span m=\"467310\">Let</span> <span m=\"467430\">me</span> <span m=\"467550\"\
  >show</span> <span m=\"467760\">you</span> <span m=\"467910\">in</span> <span m=\"\
  468000\">a</span> <span m=\"468060\">second</span> <span m=\"468360\">a</span> <span\
  \ m=\"468420\">few</span> <span m=\"468660\">examples</span> <span m=\"469850\"\
  >of</span> <span m=\"470060\">sets</span> <span m=\"470370\">the</span> <span m=\"\
  470490\">have</span> <span m=\"471030\">bounded</span> <span m=\"471480\">doubling</span>\
  \ <span m=\"471810\">constant.</span></p><p><span m=\"473600\">So</span> <span m=\"\
  473910\">that's</span> <span m=\"474180\">easy</span> <span m=\"474450\">to</span>\
  \ <span m=\"474540\">check</span> <span m=\"475110\">that</span> <span m=\"475260\"\
  >those</span> <span m=\"475470\">examples</span> <span m=\"475950\">indeed</span>\
  \ <span m=\"476280\">have</span> <span m=\"476490\">bounded</span> <span m=\"476910\"\
  >doubling</span> <span m=\"477240\">constant.</span> <span m=\"478570\">And</span>\
  \ <span m=\"478670\">what</span> <span m=\"478860\">this</span> <span m=\"479040\"\
  >question</span> <span m=\"479430\">amounts</span> <span m=\"479730\">to</span>\
  \ <span m=\"480330\">is</span> <span m=\"480960\">what</span> <span m=\"481110\"\
  >is</span> <span m=\"481230\">often</span> <span m=\"481440\">known</span> <span\
  \ m=\"481620\">as</span> <span m=\"481730\">an</span> <span m=\"481830\">inverse</span>\
  \ <span m=\"482340\">question.</span> <span m=\"484250\">So</span> <span m=\"484410\"\
  >it's</span> <span m=\"484530\">an</span> <span m=\"484650\">inverse</span> <span\
  \ m=\"485780\">problem</span> <span m=\"489620\">that</span> <span m=\"489780\"\
  >asks</span> <span m=\"490320\">you</span> <span m=\"490470\">to</span> <span m=\"\
  491100\">describe</span> <span m=\"492210\">in</span> <span m=\"492360\">reverse--</span>\
  \ <span m=\"493070\">so</span> <span m=\"493500\">it's</span> <span m=\"493770\"\
  >easy</span> <span m=\"494010\">to</span> <span m=\"494130\">check</span> <span\
  \ m=\"494580\">in</span> <span m=\"494700\">the</span> <span m=\"494820\">upcoming</span>\
  \ <span m=\"495210\">examples</span> <span m=\"495750\">that</span> <span m=\"495870\"\
  >all</span> <span m=\"496050\">of</span> <span m=\"496110\">those</span> <span m=\"\
  496350\">examples</span> <span m=\"497310\">have</span> <span m=\"498480\">bounded</span>\
  \ <span m=\"499140\">doubling</span> <span m=\"499500\">constant.</span> <span m=\"\
  500600\">And</span> <span m=\"500700\">what</span> <span m=\"500730\">we</span>\
  \ <span m=\"500850\">want</span> <span m=\"501030\">to</span> <span m=\"501090\"\
  >say</span> <span m=\"501390\">is,</span> <span m=\"501900\">in</span> <span m=\"\
  502020\">reverse,</span> <span m=\"502500\">that</span> <span m=\"502740\">if</span>\
  \ <span m=\"503040\">a</span> <span m=\"503130\">set</span> <span m=\"503460\">has</span>\
  \ <span m=\"503790\">bounded</span> <span m=\"504240\">doubling</span> <span m=\"\
  504600\">constant,</span> <span m=\"505740\">then</span> <span m=\"505980\">it</span>\
  \ <span m=\"506130\">must</span> <span m=\"507150\">in</span> <span m=\"507300\"\
  >some</span> <span m=\"507570\">sense</span> <span m=\"508410\">look</span> <span\
  \ m=\"508710\">like</span> <span m=\"509100\">one</span> <span m=\"509370\">of</span>\
  \ <span m=\"509520\">our</span> <span m=\"509640\">examples.</span> <span m=\"511160\"\
  >It's</span> <span m=\"511320\">the</span> <span m=\"511380\">harder</span> <span\
  \ m=\"511980\">inverse</span> <span m=\"512400\">question.</span></p><p><span m=\"\
  515530\">OK,</span> <span m=\"515830\">so</span> <span m=\"515980\">let</span> <span\
  \ m=\"516100\">me</span> <span m=\"516190\">give</span> <span m=\"516370\">you</span>\
  \ <span m=\"516429\">some</span> <span m=\"516640\">examples</span> <span m=\"517419\"\
  >of</span> <span m=\"517559\">sets</span> <span m=\"517929\">with</span> <span m=\"\
  518530\">small</span> <span m=\"519039\">doubling</span> <span m=\"519429\">constant.</span>\
  \ <span m=\"529650\">One</span> <span m=\"529860\">example</span> <span m=\"530430\"\
  >we</span> <span m=\"530550\">already</span> <span m=\"530880\">saw</span> <span\
  \ m=\"531120\">earlier</span> <span m=\"531900\">is</span> <span m=\"532080\">that</span>\
  \ <span m=\"532260\">if</span> <span m=\"532440\">you</span> <span m=\"532560\"\
  >have</span> <span m=\"532830\">an</span> <span m=\"532980\">arithmetic</span> <span\
  \ m=\"533640\">progression.</span> <span m=\"536600\">If</span> <span m=\"536750\"\
  >you</span> <span m=\"536840\">have</span> <span m=\"536960\">an</span> <span m=\"\
  537050\">arithmetic</span> <span m=\"537560\">progression,</span> <span m=\"538400\"\
  >then</span> <span m=\"538580\">the</span> <span m=\"538670\">size</span> <span\
  \ m=\"539180\">of</span> <span m=\"539540\">A</span> <span m=\"539690\">plus</span>\
  \ <span m=\"539900\">A</span> <span m=\"540530\">is</span> <span m=\"540680\">always</span>\
  \ <span m=\"541430\">2</span> <span m=\"542782\">times</span> <span m=\"543560\"\
  >the</span> <span m=\"543650\">size</span> <span m=\"544010\">of</span> <span m=\"\
  544130\">A</span> <span m=\"544520\">minus</span> <span m=\"544880\">1.</span></p><p><span\
  \ m=\"546085\">So</span> <span m=\"546410\">the</span> <span m=\"546710\">doubling</span>\
  \ <span m=\"547040\">constantly</span> <span m=\"547540\">is</span> <span m=\"547680\"\
  >always,</span> <span m=\"548640\">at</span> <span m=\"548890\">most,</span> <span\
  \ m=\"549170\">2.</span> <span m=\"551340\">That's</span> <span m=\"551520\">pretty</span>\
  \ <span m=\"551730\">small.</span> <span m=\"552460\">That's</span> <span m=\"553020\"\
  >as</span> <span m=\"553070\">small</span> <span m=\"553290\">as</span> <span m=\"\
  553380\">you</span> <span m=\"553440\">can</span> <span m=\"553590\">get</span>\
  \ <span m=\"554340\">in</span> <span m=\"554700\">arithmetic</span> <span m=\"555210\"\
  >progressions</span> <span m=\"556075\">is</span> <span m=\"556580\">in</span> <span\
  \ m=\"556800\">the</span> <span m=\"556890\">integers.</span></p><p><span m=\"560460\"\
  >But</span> <span m=\"560580\">if</span> <span m=\"560700\">you</span> <span m=\"\
  560760\">start</span> <span m=\"561090\">with</span> <span m=\"561240\">an</span>\
  \ <span m=\"561330\">arithmetic</span> <span m=\"561780\">progression</span> <span\
  \ m=\"563370\">and</span> <span m=\"564270\">now</span> <span m=\"564600\">I</span>\
  \ <span m=\"565380\">take</span> <span m=\"565890\">just</span> <span m=\"566160\"\
  >a</span> <span m=\"566220\">subset</span> <span m=\"566880\">of</span> <span m=\"\
  567000\">the</span> <span m=\"567120\">elements</span> <span m=\"567810\">of</span>\
  \ <span m=\"567990\">this</span> <span m=\"568170\">progression,</span> <span m=\"\
  570150\">so</span> <span m=\"570250\">if</span> <span m=\"570370\">I</span> <span\
  \ m=\"570490\">take</span> <span m=\"572350\">AP,</span> <span m=\"573580\">and</span>\
  \ <span m=\"574150\">if</span> <span m=\"574330\">I</span> <span m=\"575860\">cross</span>\
  \ <span m=\"576310\">out</span> <span m=\"576700\">a</span> <span m=\"576790\">few</span>\
  \ <span m=\"577090\">elements,</span> <span m=\"577930\">just</span> <span m=\"\
  578080\">a</span> <span m=\"578110\">small</span> <span m=\"578410\">number</span>\
  \ <span m=\"578650\">of</span> <span m=\"578710\">elements</span> <span m=\"579100\"\
  >from</span> <span m=\"579280\">this</span> <span m=\"579400\">progression,</span>\
  \ <span m=\"580840\">or</span> <span m=\"581050\">even</span> <span m=\"581350\"\
  >cross</span> <span m=\"581730\">out</span> <span m=\"582310\">most,</span> <span\
  \ m=\"582730\">but</span> <span m=\"582880\">keeping</span> <span m=\"583240\">a</span>\
  \ <span m=\"583330\">constant</span> <span m=\"583810\">fraction</span> <span m=\"\
  584320\">of</span> <span m=\"584440\">elements</span> <span m=\"584770\">still</span>\
  \ <span m=\"585070\">remaining,</span> <span m=\"588540\">I</span> <span m=\"588610\"\
  >claim</span> <span m=\"588850\">that's</span> <span m=\"589000\">still</span> <span\
  \ m=\"589270\">a</span> <span m=\"589330\">pretty</span> <span m=\"589600\">good</span>\
  \ <span m=\"589780\">set.</span> <span m=\"592200\">So</span> <span m=\"593070\"\
  >if</span> <span m=\"595050\">A</span> <span m=\"595530\">can</span> <span m=\"\
  595710\">be</span> <span m=\"595830\">embedded</span> <span m=\"596490\">inside</span>\
  \ <span m=\"596970\">an</span> <span m=\"597090\">AP</span> <span m=\"601290\">such</span>\
  \ <span m=\"601650\">that</span> <span m=\"603120\">the</span> <span m=\"603240\"\
  >AP</span> <span m=\"603810\">has</span> <span m=\"604150\">size</span> <span m=\"\
  604680\">no</span> <span m=\"604860\">more</span> <span m=\"605610\">a</span> <span\
  \ m=\"605730\">constant</span> <span m=\"606270\">factor</span> <span m=\"606690\"\
  >and</span> <span m=\"606770\">more</span> <span m=\"606990\">than</span> <span\
  \ m=\"607200\">that</span> <span m=\"607380\">of</span> <span m=\"607530\">A,</span>\
  \ <span m=\"609840\">then</span> <span m=\"611690\">the</span> <span m=\"611780\"\
  >size</span> <span m=\"612290\">of</span> <span m=\"613670\">A</span> <span m=\"\
  613790\">plus</span> <span m=\"614120\">A</span> <span m=\"615710\">is,</span> <span\
  \ m=\"615880\">at</span> <span m=\"615980\">most--</span> <span m=\"616700\">so</span>\
  \ <span m=\"616850\">we</span> <span m=\"616970\">bound</span> <span m=\"617240\"\
  >it</span> <span m=\"617510\">by</span> <span m=\"617720\">the</span> <span m=\"\
  617840\">size</span> <span m=\"618200\">of</span> <span m=\"618350\">P</span> <span\
  \ m=\"618590\">plus</span> <span m=\"618860\">P,</span> <span m=\"621260\">which</span>\
  \ <span m=\"621470\">is,</span> <span m=\"621590\">at</span> <span m=\"621750\"\
  >most,</span> <span m=\"622010\">2P.</span></p><p><span m=\"625160\">So</span> <span\
  \ m=\"625640\">the</span> <span m=\"625790\">doubling</span> <span m=\"626210\"\
  >constant</span> <span m=\"626870\">of</span> <span m=\"627050\">A</span> <span\
  \ m=\"627350\">is,</span> <span m=\"627530\">at</span> <span m=\"627620\">most,</span>\
  \ <span m=\"628250\">2C.</span> <span m=\"630250\">So</span> <span m=\"630410\"\
  >if</span> <span m=\"630560\">you</span> <span m=\"630740\">have</span> <span m=\"\
  630980\">a</span> <span m=\"631040\">set</span> <span m=\"631460\">which</span>\
  \ <span m=\"631700\">is</span> <span m=\"633050\">at</span> <span m=\"633110\">least</span>\
  \ <span m=\"633380\">1/10</span> <span m=\"634020\">fraction</span> <span m=\"634730\"\
  >of</span> <span m=\"634910\">an</span> <span m=\"635120\">AP,</span> <span m=\"\
  635960\">then</span> <span m=\"636140\">you</span> <span m=\"636190\">are</span>\
  \ <span m=\"636260\">doubling</span> <span m=\"636590\">constant</span> <span m=\"\
  637190\">at</span> <span m=\"637460\">most,</span> <span m=\"637840\">20,</span>\
  \ <span m=\"639410\">bounded.</span> <span m=\"640630\">So</span> <span m=\"640760\"\
  >this</span> <span m=\"640940\">is</span> <span m=\"641060\">another</span> <span\
  \ m=\"641420\">class</span> <span m=\"641780\">of</span> <span m=\"641900\">examples.</span>\
  \ <span m=\"642920\">So</span> <span m=\"643040\">it's</span> <span m=\"643130\"\
  >kind</span> <span m=\"643310\">of</span> <span m=\"643400\">a</span> <span m=\"\
  643460\">modification,</span> <span m=\"644510\">some</span> <span m=\"645290\"\
  >alteration</span> <span m=\"645950\">of</span> <span m=\"646670\">the</span> <span\
  \ m=\"647450\">arithmetic</span> <span m=\"647930\">progression.</span></p><p><span\
  \ m=\"652170\">Another</span> <span m=\"652800\">more</span> <span m=\"652950\"\
  >substantial</span> <span m=\"653700\">generalization</span> <span m=\"655350\"\
  >of</span> <span m=\"655680\">APs</span> <span m=\"656220\">is</span> <span m=\"\
  656610\">that</span> <span m=\"656970\">of</span> <span m=\"657060\">a</span> <span\
  \ m=\"657120\">two-dimensional</span> <span m=\"658740\">arithmetic</span> <span\
  \ m=\"659370\">progression.</span> <span m=\"661790\">So</span> <span m=\"661810\"\
  >you</span> <span m=\"661930\">think</span> <span m=\"662200\">of</span> <span m=\"\
  662290\">an</span> <span m=\"662410\">arithmetic</span> <span m=\"662860\">progression</span>\
  \ <span m=\"663600\">as</span> <span m=\"665410\">equally</span> <span m=\"665770\"\
  >spaced</span> <span m=\"666100\">points</span> <span m=\"666520\">on</span> <span\
  \ m=\"666650\">a</span> <span m=\"666700\">line.</span> <span m=\"668420\">But</span>\
  \ <span m=\"668590\">you</span> <span m=\"668710\">can</span> <span m=\"669490\"\
  >extend</span> <span m=\"670060\">this</span> <span m=\"670420\">in</span> <span\
  \ m=\"670570\">multiple</span> <span m=\"671050\">dimensions,</span> <span m=\"\
  676600\">so</span> <span m=\"677120\">like</span> <span m=\"677480\">a</span> <span\
  \ m=\"677540\">grid.</span></p><p><span m=\"678710\">So</span> <span m=\"678890\"\
  >this</span> <span m=\"679070\">is</span> <span m=\"679160\">a</span> <span m=\"\
  679220\">two-dimensional</span> <span m=\"679970\">arithmetic</span> <span m=\"\
  680480\">progression,</span> <span m=\"681560\">but</span> <span m=\"681770\">I</span>\
  \ <span m=\"681980\">still</span> <span m=\"682280\">want</span> <span m=\"682520\"\
  >to</span> <span m=\"682580\">work</span> <span m=\"682940\">inside</span> <span\
  \ m=\"683360\">the</span> <span m=\"683450\">integers.</span> <span m=\"684330\"\
  >So</span> <span m=\"684470\">what</span> <span m=\"684740\">we</span> <span m=\"\
  684890\">are</span> <span m=\"684980\">going</span> <span m=\"685220\">to</span>\
  \ <span m=\"685340\">do</span> <span m=\"685850\">is</span> <span m=\"686720\">project</span>\
  \ <span m=\"689030\">this</span> <span m=\"689210\">picture</span> <span m=\"690080\"\
  >onto</span> <span m=\"690650\">the</span> <span m=\"690770\">integers.</span> <span\
  \ m=\"693880\">So</span> <span m=\"694030\">that's</span> <span m=\"694300\">a</span>\
  \ <span m=\"694390\">two-dimensional</span> <span m=\"695320\">arithmetic</span>\
  \ <span m=\"695860\">progression.</span> <span m=\"696700\">And</span> <span m=\"\
  697540\">specifically,</span> <span m=\"698830\">we</span> <span m=\"701610\">have</span>\
  \ <span m=\"701820\">a</span> <span m=\"701880\">set</span> <span m=\"702510\">of</span>\
  \ <span m=\"702660\">the</span> <span m=\"702750\">form,</span> <span m=\"705240\"\
  >so</span> <span m=\"705460\">x0</span> <span m=\"706030\">is</span> <span m=\"\
  707955\">the</span> <span m=\"708440\">starting</span> <span m=\"708800\">point,</span>\
  \ <span m=\"709730\">plus</span> <span m=\"710460\">l1</span> <span m=\"711330\"\
  >of</span> <span m=\"711740\">x1--</span> <span m=\"712300\">l1</span> <span m=\"\
  712790\">times</span> <span m=\"713030\">x1,</span> <span m=\"713960\">and</span>\
  \ <span m=\"714080\">l2</span> <span m=\"714320\">2</span> <span m=\"714830\">times</span>\
  \ <span m=\"715400\">x2,</span> <span m=\"716930\">where</span> <span m=\"717830\"\
  >the</span> <span m=\"719300\">little</span> <span m=\"719930\">l's</span> <span\
  \ m=\"721040\">are</span> <span m=\"721310\">integers,</span> <span m=\"723510\"\
  >non-negative</span> <span m=\"724070\">integers</span> <span m=\"724580\">up</span>\
  \ <span m=\"724760\">to</span> <span m=\"725060\">big</span> <span m=\"725300\"\
  >L.</span></p><p><span m=\"739140\">So</span> <span m=\"739290\">that's</span> <span\
  \ m=\"740760\">a</span> <span m=\"740880\">two-dimensional</span> <span m=\"741630\"\
  >arithmetic</span> <span m=\"742200\">progression.</span> <span m=\"743110\">So</span>\
  \ <span m=\"743190\">the</span> <span m=\"743310\">picture</span> <span m=\"743760\"\
  >that</span> <span m=\"743910\">you</span> <span m=\"744030\">can</span> <span m=\"\
  744180\">have</span> <span m=\"744390\">in</span> <span m=\"744450\">mind</span>\
  \ <span m=\"745290\">is,</span> <span m=\"746250\">on</span> <span m=\"746560\"\
  >the</span> <span m=\"746610\">number</span> <span m=\"746910\">line,</span> <span\
  \ m=\"748740\">we</span> <span m=\"748860\">can</span> <span m=\"750270\">get,</span>\
  \ <span m=\"752400\">write</span> <span m=\"752700\">down</span> <span m=\"752910\"\
  >first</span> <span m=\"753450\">an</span> <span m=\"753630\">AP</span> <span m=\"\
  755470\">and</span> <span m=\"755620\">then</span> <span m=\"758470\">a</span> <span\
  \ m=\"758560\">few</span> <span m=\"758720\">more</span> <span m=\"758870\">points</span>\
  \ <span m=\"759470\">like</span> <span m=\"759620\">that</span> <span m=\"760310\"\
  >so</span> <span m=\"760490\">that</span> <span m=\"760640\">you</span> <span m=\"\
  760760\">can</span> <span m=\"760940\">have</span> <span m=\"761270\">a</span> <span\
  \ m=\"761390\">two-dimensional</span> <span m=\"762380\">arithmetic</span> <span\
  \ m=\"762980\">progression.</span> <span m=\"768630\">We</span> <span m=\"768780\"\
  >say</span> <span m=\"769050\">that</span> <span m=\"771240\">this</span> <span\
  \ m=\"771810\">set,</span> <span m=\"772380\">this</span> <span m=\"772740\">two-dimensional</span>\
  \ <span m=\"773430\">arithmetic</span> <span m=\"773910\">progression</span> <span\
  \ m=\"774960\">is</span> <span m=\"778030\">proper</span> <span m=\"781300\">if</span>\
  \ <span m=\"782860\">all</span> <span m=\"783280\">terms</span> <span m=\"785260\"\
  >are</span> <span m=\"785380\">distinct.</span></p><p><span m=\"792570\">And</span>\
  \ <span m=\"793290\">if</span> <span m=\"793440\">that's</span> <span m=\"793680\"\
  >the</span> <span m=\"793770\">case,</span> <span m=\"794500\">then</span> <span\
  \ m=\"794640\">I</span> <span m=\"794760\">can</span> <span m=\"794910\">write</span>\
  \ <span m=\"795990\">A</span> <span m=\"796140\">plus</span> <span m=\"796550\"\
  >A</span> <span m=\"797356\">in</span> <span m=\"797760\">a</span> <span m=\"797940\"\
  >very</span> <span m=\"798180\">similar</span> <span m=\"798630\">format.</span>\
  \ <span m=\"799290\">So</span> <span m=\"799440\">A</span> <span m=\"799560\">plus</span>\
  \ <span m=\"799890\">A</span> <span m=\"800460\">contains</span> <span m=\"800940\"\
  >elements</span> <span m=\"801780\">still</span> <span m=\"802170\">of</span> <span\
  \ m=\"802320\">the</span> <span m=\"802440\">same</span> <span m=\"802950\">form,</span>\
  \ <span m=\"806780\">but</span> <span m=\"806930\">now</span> <span m=\"808130\"\
  >the</span> <span m=\"808970\">indices</span> <span m=\"809660\">go</span> <span\
  \ m=\"810020\">up</span> <span m=\"810230\">to</span> <span m=\"811190\">2L</span>\
  \ <span m=\"811790\">minus</span> <span m=\"812180\">1.</span> <span m=\"819120\"\
  >So</span> <span m=\"819920\">you</span> <span m=\"820010\">see</span> <span m=\"\
  820280\">that</span> <span m=\"820550\">A</span> <span m=\"820700\">plus</span>\
  \ <span m=\"821060\">A</span> <span m=\"821250\">has</span> <span m=\"821450\">size,</span>\
  \ <span m=\"821900\">at</span> <span m=\"822000\">most,</span> <span m=\"822350\"\
  >4</span> <span m=\"822800\">times</span> <span m=\"823130\">the</span> <span m=\"\
  823250\">original</span> <span m=\"823670\">set, A.</span> <span m=\"825650\">Also</span>\
  \ <span m=\"825890\">easy</span> <span m=\"826130\">to</span> <span m=\"826220\"\
  >see</span> <span m=\"826490\">from</span> <span m=\"826760\">this</span> <span\
  \ m=\"826970\">blue</span> <span m=\"827210\">picture</span> <span m=\"827600\"\
  >up</span> <span m=\"827720\">there--</span> <span m=\"828360\">you</span> <span\
  \ m=\"828430\">expand</span> <span m=\"829010\">that</span> <span m=\"829130\">grid.</span>\
  \ <span m=\"829880\">It</span> <span m=\"830000\">goes</span> <span m=\"830240\"\
  >to,</span> <span m=\"830660\">at most,</span> <span m=\"830960\">4</span> <span\
  \ m=\"831170\">times</span> <span m=\"831500\">the</span> <span m=\"831590\">size.</span>\
  \ <span m=\"832300\">Yes?</span></p><p><span m=\"833055\">AUDIENCE:</span> <span\
  \ m=\"833302\">[INAUDIBLE]</span></p><p><span m=\"836520\">YUFEI ZHAO:</span> <span\
  \ m=\"836630\">So</span> <span m=\"837050\">the</span> <span m=\"837110\">question</span>\
  \ <span m=\"837410\">is,</span> <span m=\"837490\">should</span> <span m=\"837710\"\
  >it</span> <span m=\"837770\">be?</span></p><p><span m=\"838840\">AUDIENCE:</span>\
  \ <span m=\"839090\">[INAUDIBLE]</span></p><p><span m=\"844430\">YUFEI ZHAO:</span>\
  \ <span m=\"844625\">2x0?</span></p><p><span m=\"845600\">AUDIENCE:</span> <span\
  \ m=\"845840\">[INAUDIBLE]</span></p><p><span m=\"848480\">YUFEI ZHAO:</span> <span\
  \ m=\"848520\">What</span> <span m=\"848560\">do</span> <span m=\"848600\">you</span>\
  \ <span m=\"848660\">mean?</span></p><p><span m=\"849710\">AUDIENCE:</span> <span\
  \ m=\"849875\">2x0</span> <span m=\"850040\">plus</span> <span m=\"850250\">l1</span>\
  \ <span m=\"850740\">x0</span> <span m=\"851230\">plus 1?</span></p><p><span m=\"\
  851720\">YUFEI ZHAO:</span> <span m=\"851820\">Ah,</span> <span m=\"851920\">thank</span>\
  \ <span m=\"852100\">you,</span> <span m=\"852380\">so</span> <span m=\"852500\"\
  >2x0,</span> <span m=\"852950\">thank</span> <span m=\"853130\">you.</span> <span\
  \ m=\"853360\">Yeah,</span> <span m=\"853830\">2x0,</span> <span m=\"855020\">great.</span>\
  \ <span m=\"858070\">OK,</span> <span m=\"858690\">so</span> <span m=\"859240\"\
  >that's</span> <span m=\"859450\">the</span> <span m=\"859540\">size.</span> <span\
  \ m=\"861400\">And</span> <span m=\"861520\">of</span> <span m=\"861610\">course,</span>\
  \ <span m=\"861790\">you</span> <span m=\"861880\">can</span> <span m=\"862540\"\
  >generalize</span> <span m=\"863020\">this</span> <span m=\"863170\">example</span>\
  \ <span m=\"864130\">of</span> <span m=\"864310\">a</span> <span m=\"864370\">fairly</span>\
  \ <span m=\"864670\">straightforward</span> <span m=\"865120\">way</span> <span\
  \ m=\"865330\">to</span> <span m=\"865840\">d</span> <span m=\"866140\">dimensional</span>\
  \ <span m=\"866710\">arithmetic</span> <span m=\"867220\">progressions.</span> <span\
  \ m=\"868150\">And</span> <span m=\"868270\">we</span> <span m=\"868390\">call</span>\
  \ <span m=\"868610\">those</span> <span m=\"868840\">things</span> <span m=\"869270\"\
  >generalized</span> <span m=\"870010\">arithmetic</span> <span m=\"870520\">progressions.</span></p><p><span\
  \ m=\"873200\">So</span> <span m=\"874120\">a</span> <span m=\"874870\">Generalized</span>\
  \ <span m=\"878630\">Arithmetic</span> <span m=\"879170\">Progression,</span> <span\
  \ m=\"886270\">which</span> <span m=\"886410\">we</span> <span m=\"886560\">will</span>\
  \ <span m=\"886770\">abbreviate</span> <span m=\"887340\">by</span> <span m=\"887820\"\
  >the</span> <span m=\"887960\">letters</span> <span m=\"888240\">GAP,</span> <span\
  \ m=\"890250\">is</span> <span m=\"892950\">a</span> <span m=\"893010\">set</span>\
  \ <span m=\"893280\">of</span> <span m=\"893370\">numbers</span> <span m=\"893880\"\
  >of</span> <span m=\"894090\">the</span> <span m=\"894180\">form</span> <span m=\"\
  895630\">as</span> <span m=\"896010\">above,</span> <span m=\"896440\">except</span>\
  \ <span m=\"896670\">now</span> <span m=\"896880\">you</span> <span m=\"897030\"\
  >have</span> <span m=\"898610\">d</span> <span m=\"898830\">different</span> <span\
  \ m=\"899190\">directions</span> <span m=\"903550\">and</span> <span m=\"903880\"\
  >indices,</span> <span m=\"909720\">are</span> <span m=\"909930\">also</span> <span\
  \ m=\"910530\">straightforward</span> <span m=\"911280\">generalizations</span>\
  \ <span m=\"912270\">of</span> <span m=\"912650\">what</span> <span m=\"912770\"\
  >was</span> <span m=\"913260\">earlier.</span> <span m=\"914440\">So</span> <span\
  \ m=\"914490\">this</span> <span m=\"914820\">is</span> <span m=\"915180\">the</span>\
  \ <span m=\"915460\">notion</span> <span m=\"915810\">of</span> <span m=\"915930\"\
  >a</span> <span m=\"916020\">generalized</span> <span m=\"916830\">arithmetic</span>\
  \ <span m=\"917340\">progression.</span> <span m=\"918070\">So</span> <span m=\"\
  918360\">think</span> <span m=\"918540\">about</span> <span m=\"918660\">projection</span>\
  \ <span m=\"919140\">of</span> <span m=\"919230\">a</span> <span m=\"919290\">d</span>\
  \ <span m=\"919430\">dimensional</span> <span m=\"919830\">grid</span> <span m=\"\
  920220\">onto</span> <span m=\"920490\">the</span> <span m=\"920580\">integers.</span></p><p><span\
  \ m=\"923640\">And</span> <span m=\"923900\">for</span> <span m=\"924500\">GAPs,</span>\
  \ <span m=\"928040\">we</span> <span m=\"928160\">say</span> <span m=\"928370\"\
  >that</span> <span m=\"928510\">it's</span> <span m=\"928640\">proper</span> <span\
  \ m=\"930650\">if</span> <span m=\"930860\">all</span> <span m=\"931130\">the</span>\
  \ <span m=\"931250\">terms</span> <span m=\"931670\">are</span> <span m=\"931760\"\
  >distinct.</span> <span m=\"938940\">We</span> <span m=\"938990\">call</span> <span\
  \ m=\"939650\">d</span> <span m=\"940260\">the</span> <span m=\"940580\">dimension</span>\
  \ <span m=\"944830\">of</span> <span m=\"945010\">the</span> <span m=\"945100\"\
  >GAP.</span> <span m=\"947310\">And</span> <span m=\"948330\">for</span> <span m=\"\
  948610\">a</span> <span m=\"948690\">GAP,</span> <span m=\"949350\">whether</span>\
  \ <span m=\"949800\">it's</span> <span m=\"949950\">proper</span> <span m=\"950430\"\
  >or</span> <span m=\"950550\">not,</span> <span m=\"951150\">we</span> <span m=\"\
  951330\">call</span> <span m=\"951660\">the</span> <span m=\"951780\">size</span>\
  \ <span m=\"953730\">to</span> <span m=\"953880\">be</span> <span m=\"954250\">the</span>\
  \ <span m=\"954390\">product</span> <span m=\"955140\">of</span> <span m=\"955500\"\
  >the</span> <span m=\"956640\">lengths.</span></p><p><span m=\"961550\">And</span>\
  \ <span m=\"961730\">this</span> <span m=\"961910\">is</span> <span m=\"962840\"\
  >potentially</span> <span m=\"963440\">larger.</span> <span m=\"965290\">So</span>\
  \ <span m=\"965600\">this</span> <span m=\"965750\">is</span> <span m=\"965900\"\
  >larger</span> <span m=\"966380\">than</span> <span m=\"967400\">the</span> <span\
  \ m=\"967460\">number</span> <span m=\"967850\">of</span> <span m=\"967970\">distinct</span>\
  \ <span m=\"968390\">elements</span> <span m=\"972220\">if</span> <span m=\"973090\"\
  >it's</span> <span m=\"973300\">not</span> <span m=\"973570\">proper.</span> <span\
  \ m=\"975790\">So</span> <span m=\"975910\">when</span> <span m=\"976090\">I</span>\
  \ <span m=\"976180\">refer</span> <span m=\"976570\">to</span> <span m=\"976690\"\
  >the</span> <span m=\"976810\">size</span> <span m=\"977380\">of</span> <span m=\"\
  977470\">a</span> <span m=\"977530\">GAP--</span> <span m=\"978040\">so</span> <span\
  \ m=\"978190\">I</span> <span m=\"978310\">view</span> <span m=\"978490\">the</span>\
  \ <span m=\"978580\">GAP</span> <span m=\"979000\">more</span> <span m=\"979240\"\
  >than</span> <span m=\"979420\">just</span> <span m=\"979600\">as</span> <span m=\"\
  979720\">a</span> <span m=\"979780\">set,</span> <span m=\"980260\">but</span> <span\
  \ m=\"980470\">also</span> <span m=\"980740\">with</span> <span m=\"980980\">the</span>\
  \ <span m=\"981040\">data</span> <span m=\"981400\">of</span> <span m=\"981490\"\
  >the</span> <span m=\"981820\">initial</span> <span m=\"982150\">point</span> <span\
  \ m=\"982570\">and</span> <span m=\"982700\">the</span> <span m=\"982750\">directions.</span>\
  \ <span m=\"984050\">If</span> <span m=\"984070\">I</span> <span m=\"984160\">talk</span>\
  \ <span m=\"984370\">about</span> <span m=\"984580\">the</span> <span m=\"984670\"\
  >size,</span> <span m=\"985120\">I'm</span> <span m=\"985270\">always</span> <span\
  \ m=\"985570\">referring</span> <span m=\"986050\">to</span> <span m=\"986380\"\
  >this</span> <span m=\"986620\">quantity</span> <span m=\"987190\">over</span> <span\
  \ m=\"987430\">here.</span> <span m=\"992360\">Great.</span></p><p><span m=\"993790\"\
  >So</span> <span m=\"994240\">you</span> <span m=\"994360\">see,</span> <span m=\"\
  994810\">if</span> <span m=\"994960\">you</span> <span m=\"995050\">take</span>\
  \ <span m=\"995380\">a</span> <span m=\"995860\">GAP</span> <span m=\"997060\">or</span>\
  \ <span m=\"997630\">a</span> <span m=\"997720\">fraction</span> <span m=\"998290\"\
  >of</span> <span m=\"998440\">a</span> <span m=\"998470\">GAP,</span> <span m=\"\
  999460\">then,</span> <span m=\"999910\">as</span> <span m=\"1000150\">with</span>\
  \ <span m=\"1000360\">earlier</span> <span m=\"1000690\">examples,</span> <span\
  \ m=\"1001650\">you</span> <span m=\"1001860\">have</span> <span m=\"1002340\">small</span>\
  \ <span m=\"1003030\">doubling.</span> <span m=\"1005930\">So</span> <span m=\"\
  1006130\">if</span> <span m=\"1007270\">P</span> <span m=\"1008620\">is</span> <span\
  \ m=\"1009340\">a</span> <span m=\"1009460\">proper</span> <span m=\"1011500\">GAP,</span>\
  \ <span m=\"1016450\">of</span> <span m=\"1016640\">dimension</span> <span m=\"\
  1018320\">d,</span> <span m=\"1019310\">then</span> <span m=\"1019970\">P</span>\
  \ <span m=\"1020660\">plus</span> <span m=\"1021020\">P</span> <span m=\"1022010\"\
  >is,</span> <span m=\"1022480\">at</span> <span m=\"1022640\">most,</span> <span\
  \ m=\"1024920\">2</span> <span m=\"1025220\">raised to</span> <span m=\"1025520\"\
  >power</span> <span m=\"1025835\">d</span> <span m=\"1026150\">times</span> <span\
  \ m=\"1027560\">the</span> <span m=\"1027619\">size</span> <span m=\"1028010\">of</span>\
  \ <span m=\"1028069\">P.</span> <span m=\"1029480\">And</span> <span m=\"1029660\"\
  >furthermore,</span> <span m=\"1031400\">if</span> <span m=\"1032510\">A</span>\
  \ <span m=\"1032810\">is</span> <span m=\"1032990\">an</span> <span m=\"1033109\"\
  >arbitrary</span> <span m=\"1033650\">subset</span> <span m=\"1034130\">of</span>\
  \ <span m=\"1034280\">P</span> <span m=\"1035900\">and</span> <span m=\"1037250\"\
  >such</span> <span m=\"1037579\">that</span> <span m=\"1038329\">A</span> <span\
  \ m=\"1038630\">has</span> <span m=\"1040339\">size--</span> <span m=\"1042319\"\
  >such</span> <span m=\"1042550\">that</span> <span m=\"1042700\">the</span> <span\
  \ m=\"1044030\">GAP</span> <span m=\"1044370\">has</span> <span m=\"1044710\">size,</span>\
  \ <span m=\"1045040\">at</span> <span m=\"1045130\">most,</span> <span m=\"1045400\"\
  >a</span> <span m=\"1045430\">constant</span> <span m=\"1045849\">fraction</span>\
  \ <span m=\"1046270\">bigger</span> <span m=\"1046569\">than</span> <span m=\"1046720\"\
  >that</span> <span m=\"1046900\">of</span> <span m=\"1047020\">A,</span> <span m=\"\
  1048250\">then</span> <span m=\"1050730\">A</span> <span m=\"1050960\">has</span>\
  \ <span m=\"1051170\">small</span> <span m=\"1051580\">doubling</span> <span m=\"\
  1052080\">as</span> <span m=\"1052200\">well.</span></p><p><span m=\"1065120\">So</span>\
  \ <span m=\"1065440\">all</span> <span m=\"1065620\">of</span> <span m=\"1065680\"\
  >these</span> <span m=\"1065890\">are</span> <span m=\"1066010\">examples</span>\
  \ <span m=\"1066940\">of</span> <span m=\"1067030\">constructions</span> <span m=\"\
  1067600\">of</span> <span m=\"1067690\">sets</span> <span m=\"1067990\">where,</span>\
  \ <span m=\"1068590\">for</span> <span m=\"1068830\">some</span> <span m=\"1069310\"\
  >fixed</span> <span m=\"1070060\">constant,</span> <span m=\"1070770\">the</span>\
  \ <span m=\"1070900\">doubling</span> <span m=\"1071230\">constant,</span> <span\
  \ m=\"1072730\">we</span> <span m=\"1072910\">can</span> <span m=\"1073060\">find</span>\
  \ <span m=\"1074230\">a</span> <span m=\"1074290\">family</span> <span m=\"1075520\"\
  >of</span> <span m=\"1075850\">sets</span> <span m=\"1076900\">with</span> <span\
  \ m=\"1077140\">doubling</span> <span m=\"1077500\">constant</span> <span m=\"1078070\"\
  >bounded</span> <span m=\"1078700\">by</span> <span m=\"1079240\">that</span> <span\
  \ m=\"1079420\">number.</span> <span m=\"1082646\">And</span> <span m=\"1083130\"\
  >the</span> <span m=\"1083190\">natural</span> <span m=\"1083520\">question</span>\
  \ <span m=\"1083790\">though</span> <span m=\"1083970\">is,</span> <span m=\"1084420\"\
  >are</span> <span m=\"1084570\">these</span> <span m=\"1084930\">all</span> <span\
  \ m=\"1085140\">the</span> <span m=\"1085290\">examples?</span> <span m=\"1087150\"\
  >So</span> <span m=\"1087630\">have</span> <span m=\"1087900\">we</span> <span m=\"\
  1088590\">missed</span> <span m=\"1088980\">some</span> <span m=\"1089880\">important</span>\
  \ <span m=\"1090360\">family</span> <span m=\"1090810\">of</span> <span m=\"1090900\"\
  >constructions</span> <span m=\"1091620\">not</span> <span m=\"1091920\">covered</span>\
  \ <span m=\"1092340\">by</span> <span m=\"1093300\">any</span> <span m=\"1093540\"\
  >of</span> <span m=\"1093630\">these</span> <span m=\"1093900\">examples?</span></p><p><span\
  \ m=\"1094795\">And</span> <span m=\"1095120\">so</span> <span m=\"1095130\">that's</span>\
  \ <span m=\"1095280\">the</span> <span m=\"1095370\">kind</span> <span m=\"1095580\"\
  >of</span> <span m=\"1095670\">inverse</span> <span m=\"1096090\">question</span>\
  \ <span m=\"1096450\">I</span> <span m=\"1096540\">was</span> <span m=\"1096660\"\
  >referring</span> <span m=\"1097020\">to</span> <span m=\"1097110\">earlier.</span>\
  \ <span m=\"1097780\">So</span> <span m=\"1097860\">all</span> <span m=\"1098010\"\
  >of</span> <span m=\"1098100\">these</span> <span m=\"1098250\">examples,</span>\
  \ <span m=\"1098720\">easy</span> <span m=\"1098940\">to</span> <span m=\"1099030\"\
  >check</span> <span m=\"1099450\">that</span> <span m=\"1099630\">they</span> <span\
  \ m=\"1099750\">indeed</span> <span m=\"1100050\">have</span> <span m=\"1100260\"\
  >small</span> <span m=\"1100530\">doubling</span> <span m=\"1100830\">constant.</span>\
  \ <span m=\"1103680\">Can</span> <span m=\"1103830\">you</span> <span m=\"1103920\"\
  >go</span> <span m=\"1104100\">in</span> <span m=\"1104220\">reverse?</span> <span\
  \ m=\"1104990\">So</span> <span m=\"1105090\">can</span> <span m=\"1105240\">you</span>\
  \ <span m=\"1106260\">ask</span> <span m=\"1106500\">the</span> <span m=\"1106590\"\
  >inverse</span> <span m=\"1107040\">question,</span> <span m=\"1107880\">if</span>\
  \ <span m=\"1108210\">a</span> <span m=\"1108300\">set</span> <span m=\"1108540\"\
  >has</span> <span m=\"1108660\">small</span> <span m=\"1108930\">doubling</span>\
  \ <span m=\"1109230\">constant,</span> <span m=\"1110100\">must it</span> <span\
  \ m=\"1110540\">look</span> <span m=\"1110820\">like,</span> <span m=\"1111420\"\
  >in</span> <span m=\"1111540\">some</span> <span m=\"1111750\">sense,</span> <span\
  \ m=\"1112210\">one</span> <span m=\"1112320\">of</span> <span m=\"1112410\">these</span>\
  \ <span m=\"1112560\">sets?</span></p><p><span m=\"1114610\">It</span> <span m=\"\
  1115020\">turns</span> <span m=\"1115230\">out</span> <span m=\"1116070\">this</span>\
  \ <span m=\"1116250\">is</span> <span m=\"1116670\">not</span> <span m=\"1116970\"\
  >such</span> <span m=\"1117300\">an</span> <span m=\"1117390\">easy</span> <span\
  \ m=\"1117630\">problem.</span> <span m=\"1118770\">And</span> <span m=\"1120090\"\
  >there</span> <span m=\"1120330\">is</span> <span m=\"1120630\">a</span> <span m=\"\
  1122040\">central</span> <span m=\"1122520\">result</span> <span m=\"1122780\">in</span>\
  \ <span m=\"1123040\">additive</span> <span m=\"1123540\">combinatorics</span> <span\
  \ m=\"1124890\">known</span> <span m=\"1125130\">as</span> <span m=\"1125910\">Freiman's</span>\
  \ <span m=\"1126420\">theorem</span> <span m=\"1128760\">which</span> <span m=\"\
  1129180\">gives</span> <span m=\"1130050\">a</span> <span m=\"1130110\">positive</span>\
  \ <span m=\"1130650\">answer</span> <span m=\"1131310\">to</span> <span m=\"1131490\"\
  >that</span> <span m=\"1131700\">question.</span> <span m=\"1133850\">So</span>\
  \ <span m=\"1134890\">Freiman's</span> <span m=\"1135360\">theorem</span> <span\
  \ m=\"1136020\">is</span> <span m=\"1136170\">now</span> <span m=\"1136380\">considered</span>\
  \ <span m=\"1136830\">a</span> <span m=\"1136920\">central</span> <span m=\"1137880\"\
  >result</span> <span m=\"1138300\">in</span> <span m=\"1138480\">additive</span>\
  \ <span m=\"1138840\">combinatorics.</span> <span m=\"1140040\">And</span> <span\
  \ m=\"1140190\">it</span> <span m=\"1140250\">completely</span> <span m=\"1140640\"\
  >describes,</span> <span m=\"1141270\">in</span> <span m=\"1141360\">some</span>\
  \ <span m=\"1141570\">sense,</span> <span m=\"1142230\">the</span> <span m=\"1142620\"\
  >sets</span> <span m=\"1143400\">that</span> <span m=\"1143850\">have</span> <span\
  \ m=\"1144210\">small</span> <span m=\"1144570\">doubling.</span></p><p><span m=\"\
  1145380\">And</span> <span m=\"1145530\">let</span> <span m=\"1145620\">me</span>\
  \ <span m=\"1146460\">write</span> <span m=\"1146670\">down</span> <span m=\"1146850\"\
  >the</span> <span m=\"1146910\">statement.</span> <span m=\"1147730\">So</span>\
  \ <span m=\"1147870\">if</span> <span m=\"1148080\">A</span> <span m=\"1148350\"\
  >is</span> <span m=\"1148530\">a</span> <span m=\"1148590\">subset</span> <span\
  \ m=\"1149220\">of</span> <span m=\"1149850\">Z</span> <span m=\"1151350\">and</span>\
  \ <span m=\"1153480\">has</span> <span m=\"1154340\">bounded</span> <span m=\"1155010\"\
  >doubling,</span> <span m=\"1160500\">then</span> <span m=\"1162390\">A</span> <span\
  \ m=\"1162900\">is</span> <span m=\"1163190\">contained</span> <span m=\"1167420\"\
  >in</span> <span m=\"1168920\">a</span> <span m=\"1169100\">GAP</span> <span m=\"\
  1171440\">of</span> <span m=\"1172730\">bounded</span> <span m=\"1173420\">dimension</span>\
  \ <span m=\"1177850\">and</span> <span m=\"1179050\">size</span> <span m=\"1180310\"\
  >bounded</span> <span m=\"1181330\">by</span> <span m=\"1182800\">some</span> <span\
  \ m=\"1183070\">constant</span> <span m=\"1183910\">times</span> <span m=\"1185170\"\
  >the</span> <span m=\"1185260\">size</span> <span m=\"1185680\">of</span> <span\
  \ m=\"1185770\">the</span> <span m=\"1185860\">set.</span> <span m=\"1192900\">This</span>\
  \ <span m=\"1193080\">is</span> <span m=\"1193210\">a</span> <span m=\"1193260\"\
  >really</span> <span m=\"1193470\">important</span> <span m=\"1193860\">result in</span>\
  \ <span m=\"1194310\">additive</span> <span m=\"1194640\">combinatorics.</span>\
  \ <span m=\"1199170\">The</span> <span m=\"1199290\">title</span> <span m=\"1199710\"\
  >of</span> <span m=\"1199860\">this</span> <span m=\"1200070\">chapter,</span> <span\
  \ m=\"1200610\">&quot;Structure</span> <span m=\"1201120\">of</span> <span m=\"\
  1201210\">Set</span> <span m=\"1201480\">Addition,&quot;</span> <span m=\"1204480\"\
  >Freiman's</span> <span m=\"1204720\">theorem</span> <span m=\"1205110\">tells</span>\
  \ <span m=\"1205470\">us</span> <span m=\"1205740\">something</span> <span m=\"\
  1206130\">about</span> <span m=\"1206340\">the</span> <span m=\"1206460\">structure</span>\
  \ <span m=\"1206970\">of</span> <span m=\"1207090\">a</span> <span m=\"1207150\"\
  >set</span> <span m=\"1207750\">with</span> <span m=\"1207990\">small</span> <span\
  \ m=\"1208860\">doubling.</span></p><p><span m=\"1211740\">The</span> <span m=\"\
  1211830\">next</span> <span m=\"1212130\">few</span> <span m=\"1212280\">lecturers</span>\
  \ <span m=\"1212730\">are</span> <span m=\"1212820\">going</span> <span m=\"1213090\"\
  >to</span> <span m=\"1213390\">be</span> <span m=\"1213570\">occupied</span> <span\
  \ m=\"1214020\">with</span> <span m=\"1214410\">proving</span> <span m=\"1214950\"\
  >this</span> <span m=\"1215190\">theorem.</span> <span m=\"1215550\">So</span> <span\
  \ m=\"1215970\">this</span> <span m=\"1216300\">theorem</span> <span m=\"1216570\"\
  >will</span> <span m=\"1216960\">have--</span> <span m=\"1218090\">its</span> <span\
  \ m=\"1218220\">proof</span> <span m=\"1218520\">is</span> <span m=\"1218670\">involved</span>\
  \ <span m=\"1219180\">and</span> <span m=\"1219330\">probably</span> <span m=\"\
  1219600\">the</span> <span m=\"1219690\">most</span> <span m=\"1219930\">involved</span>\
  \ <span m=\"1220290\">proof</span> <span m=\"1220590\">that</span> <span m=\"1220710\"\
  >we</span> <span m=\"1220860\">have</span> <span m=\"1221160\">in</span> <span m=\"\
  1221310\">this</span> <span m=\"1221460\">course.</span> <span m=\"1222330\">And</span>\
  \ <span m=\"1222480\">the</span> <span m=\"1222540\">proof</span> <span m=\"1222720\"\
  >will</span> <span m=\"1222930\">take</span> <span m=\"1223800\">the</span> <span\
  \ m=\"1223890\">next</span> <span m=\"1224130\">several</span> <span m=\"1224370\"\
  >lectures.</span> <span m=\"1225570\">And</span> <span m=\"1226020\">we'll</span>\
  \ <span m=\"1226170\">see</span> <span m=\"1226380\">a</span> <span m=\"1226440\"\
  >lot</span> <span m=\"1226650\">of</span> <span m=\"1226710\">different</span> <span\
  \ m=\"1227040\">ingredients,</span> <span m=\"1227610\">a</span> <span m=\"1227630\"\
  >lot</span> <span m=\"1227820\">of</span> <span m=\"1227910\">really</span> <span\
  \ m=\"1228120\">nice</span> <span m=\"1228390\">tools.</span> <span m=\"1229460\"\
  >Fourier</span> <span m=\"1229790\">analysis</span> <span m=\"1230190\">will</span>\
  \ <span m=\"1230310\">come</span> <span m=\"1230520\">up</span> <span m=\"1230640\"\
  >at</span> <span m=\"1230700\">some</span> <span m=\"1230880\">point,</span> <span\
  \ m=\"1231210\">but</span> <span m=\"1231360\">also</span> <span m=\"1231600\">other</span>\
  \ <span m=\"1231840\">tools</span> <span m=\"1232170\">like</span> <span m=\"1232320\"\
  >the</span> <span m=\"1232380\">geometry</span> <span m=\"1232860\">of</span> <span\
  \ m=\"1232980\">numbers</span> <span m=\"1234180\">and</span> <span m=\"1234300\"\
  >also</span> <span m=\"1234630\">some</span> <span m=\"1234840\">more</span> <span\
  \ m=\"1234990\">classical</span> <span m=\"1235470\">additive</span> <span m=\"\
  1235770\">combinatorics</span> <span m=\"1236520\">ideas.</span></p><p><span m=\"\
  1238100\">But</span> <span m=\"1238200\">before</span> <span m=\"1238440\">starting</span>\
  \ <span m=\"1238800\">on</span> <span m=\"1238890\">a</span> <span m=\"1238950\"\
  >proof,</span> <span m=\"1239220\">I</span> <span m=\"1239310\">want</span> <span\
  \ m=\"1239490\">to</span> <span m=\"1239550\">offer</span> <span m=\"1239850\">a</span>\
  \ <span m=\"1239910\">few</span> <span m=\"1240630\">remarks</span> <span m=\"1241110\"\
  >and</span> <span m=\"1241320\">historical</span> <span m=\"1241800\">remarks</span>\
  \ <span m=\"1242560\">to</span> <span m=\"1242770\">just</span> <span m=\"1242940\"\
  >give</span> <span m=\"1243090\">you</span> <span m=\"1243270\">some</span> <span\
  \ m=\"1243450\">more</span> <span m=\"1243570\">context</span> <span m=\"1244200\"\
  >about</span> <span m=\"1244700\">Freiman's</span> <span m=\"1245100\">theorem,</span>\
  \ <span m=\"1246480\">but</span> <span m=\"1246570\">first,</span> <span m=\"1246870\"\
  >a</span> <span m=\"1246900\">few</span> <span m=\"1247050\">mathematical</span>\
  \ <span m=\"1247650\">comments.</span> <span m=\"1250980\">In</span> <span m=\"\
  1251190\">this</span> <span m=\"1251880\">conclusions</span> <span m=\"1252530\"\
  >of</span> <span m=\"1252610\">Freiman's</span> <span m=\"1252850\">theorem,</span>\
  \ <span m=\"1253290\">I</span> <span m=\"1253350\">didn't</span> <span m=\"1253620\"\
  >mention</span> <span m=\"1254010\">properness.</span> <span m=\"1255150\">And</span>\
  \ <span m=\"1255270\">that's</span> <span m=\"1255690\">mostly</span> <span m=\"\
  1256260\">a</span> <span m=\"1256320\">matter</span> <span m=\"1256590\">of</span>\
  \ <span m=\"1256650\">convenience.</span> <span m=\"1257220\">So</span> <span m=\"\
  1257340\">you</span> <span m=\"1257430\">can,</span> <span m=\"1257610\">in</span>\
  \ <span m=\"1257730\">fact,</span> <span m=\"1258130\">make</span> <span m=\"1259850\"\
  >the</span> <span m=\"1260010\">conclusion</span> <span m=\"1260640\">proper</span>\
  \ <span m=\"1261150\">as</span> <span m=\"1261320\">well</span> <span m=\"1261590\"\
  >at</span> <span m=\"1262020\">the</span> <span m=\"1262170\">cost</span> <span\
  \ m=\"1262590\">of</span> <span m=\"1262710\">increasing</span> <span m=\"1263460\"\
  >the</span> <span m=\"1264390\">number</span> <span m=\"1264780\">somewhat,</span>\
  \ <span m=\"1265200\">but</span> <span m=\"1265320\">still</span> <span m=\"1266460\"\
  >constants</span> <span m=\"1267000\">depending</span> <span m=\"1267450\">only</span>\
  \ <span m=\"1267690\">on</span> <span m=\"1267810\">k--</span> <span m=\"1271890\"\
  >can</span> <span m=\"1274710\">guarantee</span> <span m=\"1278390\">properness</span>\
  \ <span m=\"1280800\">as</span> <span m=\"1281260\">well.</span> <span m=\"1286130\"\
  >So</span> <span m=\"1286340\">there is</span> <span m=\"1286770\">an</span> <span\
  \ m=\"1286890\">extra</span> <span m=\"1287190\">step</span> <span m=\"1287460\"\
  >involved</span> <span m=\"1287910\">which</span> <span m=\"1288090\">we'll</span>\
  \ <span m=\"1288720\">not</span> <span m=\"1289020\">cover,</span> <span m=\"1291240\"\
  >because</span> <span m=\"1291620\">it's</span> <span m=\"1291740\">not</span> <span\
  \ m=\"1291890\">entirely</span> <span m=\"1292340\">trivial,</span> <span m=\"1292670\"\
  >but</span> <span m=\"1292790\">it's</span> <span m=\"1292970\">also</span> <span\
  \ m=\"1293210\">not</span> <span m=\"1293360\">too</span> <span m=\"1293540\">hard.</span></p><p><span\
  \ m=\"1297260\">Freiman's</span> <span m=\"1297960\">original</span> <span m=\"\
  1298370\">proof,</span> <span m=\"1299530\">so</span> <span m=\"1299740\">it's</span>\
  \ <span m=\"1300130\">named</span> <span m=\"1300380\">after</span> <span m=\"1300560\"\
  >Freiman.</span> <span m=\"1301160\">So</span> <span m=\"1301310\">he</span> <span\
  \ m=\"1301430\">proved</span> <span m=\"1301710\">that</span> <span m=\"1301820\"\
  >in</span> <span m=\"1301940\">the</span> <span m=\"1302000\">'60s.</span> <span\
  \ m=\"1303310\">But</span> <span m=\"1303450\">at</span> <span m=\"1303560\">that</span>\
  \ <span m=\"1303710\">time,</span> <span m=\"1304040\">the</span> <span m=\"1304160\"\
  >proof</span> <span m=\"1304460\">was</span> <span m=\"1304640\">considered</span>\
  \ <span m=\"1305060\">rather</span> <span m=\"1305360\">obscure.</span> <span m=\"\
  1306320\">It</span> <span m=\"1306440\">actually</span> <span m=\"1306890\">did</span>\
  \ <span m=\"1307040\">not</span> <span m=\"1307340\">get</span> <span m=\"1307520\"\
  >the</span> <span m=\"1307670\">attention</span> <span m=\"1308540\">and</span>\
  \ <span m=\"1308780\">the</span> <span m=\"1309680\">recognition</span> <span m=\"\
  1310220\">that it</span> <span m=\"1310430\">deserved</span> <span m=\"1311210\"\
  >until</span> <span m=\"1311600\">much</span> <span m=\"1311930\">later.</span>\
  \ <span m=\"1312740\">So</span> <span m=\"1312840\">this</span> <span m=\"1312890\"\
  >was</span> <span m=\"1313240\">kind</span> <span m=\"1313350\">of</span> <span\
  \ m=\"1313460\">a</span> <span m=\"1313490\">forgotten</span> <span m=\"1314030\"\
  >result,</span> <span m=\"1314690\">a</span> <span m=\"1314830\">forgotten</span>\
  \ <span m=\"1315230\">proof</span> <span m=\"1315530\">for</span> <span m=\"1315600\"\
  >a</span> <span m=\"1315620\">very</span> <span m=\"1315860\">long</span> <span\
  \ m=\"1316040\">time</span> <span m=\"1317420\">until</span> <span m=\"1318260\"\
  >quite</span> <span m=\"1318500\">a</span> <span m=\"1318530\">bit</span> <span\
  \ m=\"1318680\">later</span> <span m=\"1319070\">when</span> <span m=\"1319610\"\
  >Ruzsa--</span> <span m=\"1320700\">Ruzsa's</span> <span m=\"1321020\">name</span>\
  \ <span m=\"1321210\">will</span> <span m=\"1321290\">come</span> <span m=\"1321500\"\
  >up</span> <span m=\"1321620\">many</span> <span m=\"1321860\">times</span> <span\
  \ m=\"1322220\">in</span> <span m=\"1322310\">this</span> <span m=\"1322460\">chapter.</span></p><p><span\
  \ m=\"1323150\">Ruzsa</span> <span m=\"1323840\">came</span> <span m=\"1324140\"\
  >and</span> <span m=\"1324410\">gave</span> <span m=\"1324770\">a</span> <span m=\"\
  1324920\">different</span> <span m=\"1325280\">proof</span> <span m=\"1325740\"\
  >of</span> <span m=\"1325890\">Freiman's</span> <span m=\"1326100\">theorem,</span>\
  \ <span m=\"1326470\">and</span> <span m=\"1326580\">significantly</span> <span\
  \ m=\"1327230\">cleaned</span> <span m=\"1327560\">up</span> <span m=\"1327650\"\
  >the</span> <span m=\"1327740\">proof, and</span> <span m=\"1328090\">offered</span>\
  \ <span m=\"1328400\">many</span> <span m=\"1328640\">new</span> <span m=\"1328910\"\
  >ideas.</span> <span m=\"1329750\">So</span> <span m=\"1329990\">much</span> <span\
  \ m=\"1330290\">of</span> <span m=\"1330350\">what</span> <span m=\"1330470\">we'll</span>\
  \ <span m=\"1330620\">see</span> <span m=\"1330770\">today</span> <span m=\"1331430\"\
  >are</span> <span m=\"1331970\">results</span> <span m=\"1332390\">that</span> <span\
  \ m=\"1332540\">we</span> <span m=\"1332690\">now</span> <span m=\"1332880\">attribute</span>\
  \ <span m=\"1333290\">to</span> <span m=\"1333470\">Ruzsa.</span> <span m=\"1334190\"\
  >And</span> <span m=\"1335050\">theorem</span> <span m=\"1335510\">sometimes</span>\
  \ <span m=\"1335960\">is</span> <span m=\"1336080\">also</span> <span m=\"1336350\"\
  >called</span> <span m=\"1336570\">the</span> <span m=\"1336670\">Freiman-Ruzsa</span>\
  \ <span m=\"1337470\">theorem.</span></p><p><span m=\"1345650\">But</span> <span\
  \ m=\"1346080\">this</span> <span m=\"1346230\">result</span> <span m=\"1346470\"\
  >was</span> <span m=\"1346770\">really</span> <span m=\"1347100\">brought</span>\
  \ <span m=\"1347460\">into--</span> <span m=\"1350360\">brought</span> <span m=\"\
  1350870\">as</span> <span m=\"1351090\">a</span> <span m=\"1351150\">highlight</span>\
  \ <span m=\"1351630\">of</span> <span m=\"1352140\">additive</span> <span m=\"1352470\"\
  >combinatorics</span> <span m=\"1353520\">in</span> <span m=\"1353640\">the</span>\
  \ <span m=\"1353730\">work</span> <span m=\"1353970\">of</span> <span m=\"1354270\"\
  >Gowers</span> <span m=\"1355120\">when</span> <span m=\"1355320\">he</span> <span\
  \ m=\"1355500\">proved,</span> <span m=\"1356540\">that</span> <span m=\"1357040\"\
  >gave</span> <span m=\"1357290\">his</span> <span m=\"1357420\">new</span> <span\
  \ m=\"1357630\">proof</span> <span m=\"1358140\">of</span> <span m=\"1358380\">Szemer\xE9\
  di's</span> <span m=\"1358970\">theorem,</span> <span m=\"1360000\">giving</span>\
  \ <span m=\"1360270\">much</span> <span m=\"1360480\">better</span> <span m=\"1360720\"\
  >bounds.</span> <span m=\"1361620\">So</span> <span m=\"1361850\">he</span> <span\
  \ m=\"1362020\">had</span> <span m=\"1362150\">to</span> <span m=\"1362250\">use</span>\
  \ <span m=\"1362520\">quite</span> <span m=\"1362820\">a</span> <span m=\"1362880\"\
  >bit</span> <span m=\"1363090\">of</span> <span m=\"1364410\">serious</span> <span\
  \ m=\"1365010\">additive</span> <span m=\"1365370\">combinatorics.</span> <span\
  \ m=\"1366630\">And</span> <span m=\"1367710\">many</span> <span m=\"1368100\">of</span>\
  \ <span m=\"1368190\">the</span> <span m=\"1368310\">ideas</span> <span m=\"1368790\"\
  >that</span> <span m=\"1368910\">went</span> <span m=\"1369150\">into</span> <span\
  \ m=\"1369400\">Gowers'</span> <span m=\"1369870\">proof</span> <span m=\"1370410\"\
  >of</span> <span m=\"1370530\">Szemer\xE9di's</span> <span m=\"1371030\">theorem</span>\
  \ <span m=\"1371640\">came</span> <span m=\"1371940\">from</span> <span m=\"1372210\"\
  >this</span> <span m=\"1372450\">line</span> <span m=\"1372720\">of</span> <span\
  \ m=\"1372840\">work,</span> <span m=\"1373290\">Freiman</span> <span m=\"1373740\"\
  >and</span> <span m=\"1373830\">Ruzsa.</span> <span m=\"1375170\">So</span> <span\
  \ m=\"1375790\">and</span> <span m=\"1376440\">their</span> <span m=\"1376650\"\
  >work</span> <span m=\"1376890\">was,</span> <span m=\"1377130\">again,</span> <span\
  \ m=\"1377400\">brought</span> <span m=\"1377670\">into</span> <span m=\"1377880\"\
  >prominence</span> <span m=\"1378780\">as</span> <span m=\"1378930\">a</span> <span\
  \ m=\"1378990\">result</span> <span m=\"1379380\">of</span> <span m=\"1379900\"\
  >Gowers'</span> <span m=\"1380880\">Fields-Medal-winning</span> <span m=\"1381750\"\
  >work</span> <span m=\"1382050\">on</span> <span m=\"1382870\">Szemer\xE9di's</span>\
  \ <span m=\"1383250\">theorem.</span></p><p><span m=\"1386590\">So</span> <span\
  \ m=\"1386760\">this</span> <span m=\"1386970\">is</span> <span m=\"1387090\">some</span>\
  \ <span m=\"1388170\">of</span> <span m=\"1388230\">the</span> <span m=\"1388290\"\
  >history.</span> <span m=\"1388610\">And</span> <span m=\"1388680\">now</span> <span\
  \ m=\"1389550\">Freiman's</span> <span m=\"1389760\">theorem</span> <span m=\"1390180\"\
  >is</span> <span m=\"1390300\">considered</span> <span m=\"1390720\">a</span> <span\
  \ m=\"1390780\">central</span> <span m=\"1391200\">result</span> <span m=\"1391890\"\
  >in</span> <span m=\"1392010\">the</span> <span m=\"1392160\">area.</span> <span\
  \ m=\"1393130\">You</span> <span m=\"1393160\">can</span> <span m=\"1393300\">see,</span>\
  \ <span m=\"1393490\">it's</span> <span m=\"1393780\">a</span> <span m=\"1393810\"\
  >beautiful</span> <span m=\"1394230\">result.</span> <span m=\"1394660\">And</span>\
  \ <span m=\"1394770\">it's</span> <span m=\"1394890\">also</span> <span m=\"1395160\"\
  >quite</span> <span m=\"1395400\">a</span> <span m=\"1395460\">deep</span> <span\
  \ m=\"1395700\">result.</span></p><p><span m=\"1397730\">Let</span> <span m=\"1397750\"\
  >me</span> <span m=\"1397840\">mention</span> <span m=\"1398200\">a</span> <span\
  \ m=\"1398260\">few</span> <span m=\"1398590\">things</span> <span m=\"1398920\"\
  >about</span> <span m=\"1399190\">bounds.</span> <span m=\"1400060\">So</span> <span\
  \ m=\"1400180\">what</span> <span m=\"1400360\">do</span> <span m=\"1400420\">we</span>\
  \ <span m=\"1400540\">know</span> <span m=\"1400750\">about</span> <span m=\"1401890\"\
  >this</span> <span m=\"1402590\">d</span> <span m=\"1402790\">of</span> <span m=\"\
  1402880\">k</span> <span m=\"1403270\">and</span> <span m=\"1403480\">f</span> <span\
  \ m=\"1403650\">of</span> <span m=\"1403750\">k?</span> <span m=\"1405380\">But</span>\
  \ <span m=\"1405530\">first,</span> <span m=\"1406010\">an</span> <span m=\"1406160\"\
  >example--</span> <span m=\"1407400\">so</span> <span m=\"1407600\">if</span> <span\
  \ m=\"1408500\">the</span> <span m=\"1408560\">set</span> <span m=\"1408940\">A</span>\
  \ <span m=\"1409880\">is</span> <span m=\"1410590\">dissociated</span> <span m=\"\
  1411530\">in</span> <span m=\"1411650\">the</span> <span m=\"1411740\">sense</span>\
  \ <span m=\"1412010\">of</span> <span m=\"1412130\">having</span> <span m=\"1412460\"\
  >no</span> <span m=\"1414320\">arithmetic</span> <span m=\"1414860\">structure,</span>\
  \ <span m=\"1415610\">no</span> <span m=\"1416540\">coincidental</span> <span m=\"\
  1419950\">sums</span> <span m=\"1420460\">colliding,</span> <span m=\"1421690\"\
  >so</span> <span m=\"1421810\">for</span> <span m=\"1421930\">example,</span> <span\
  \ m=\"1422330\">if</span> <span m=\"1422380\">a</span> <span m=\"1422580\">of</span>\
  \ <span m=\"1423250\">this</span> <span m=\"1423440\">form,</span> <span m=\"1424960\"\
  >then</span> <span m=\"1426520\">you</span> <span m=\"1426640\">see</span> <span\
  \ m=\"1426850\">that--</span> <span m=\"1427360\">also</span> <span m=\"1427540\"\
  >and</span> <span m=\"1427690\">we</span> <span m=\"1427900\">saw</span> <span m=\"\
  1428260\">the</span> <span m=\"1428380\">size</span> <span m=\"1428680\">of</span>\
  \ <span m=\"1428770\">A</span> <span m=\"1428920\">plus</span> <span m=\"1429220\"\
  >A,</span> <span m=\"1429580\">so</span> <span m=\"1430150\">A</span> <span m=\"\
  1430570\">plus</span> <span m=\"1430810\">1</span> <span m=\"1431020\">choose</span>\
  \ <span m=\"1431290\">2.</span> <span m=\"1431800\">So</span> <span m=\"1431980\"\
  >in</span> <span m=\"1432070\">this</span> <span m=\"1432280\">case,</span> <span\
  \ m=\"1432550\">the</span> <span m=\"1432640\">doubling</span> <span m=\"1433000\"\
  >constant</span> <span m=\"1437790\">is</span> <span m=\"1439350\">the</span> <span\
  \ m=\"1439440\">size</span> <span m=\"1439830\">of</span> <span m=\"1439950\">A</span>\
  \ <span m=\"1440400\">plus</span> <span m=\"1440730\">1</span> <span m=\"1441510\"\
  >divided</span> <span m=\"1441840\">by</span> <span m=\"1441960\">2,</span> <span\
  \ m=\"1442500\">so</span> <span m=\"1442620\">roughly</span> <span m=\"1443385\"\
  >on</span> <span m=\"1443640\">the</span> <span m=\"1443700\">same</span> <span\
  \ m=\"1444060\">order</span> <span m=\"1444330\">as</span> <span m=\"1444480\">the</span>\
  \ <span m=\"1444570\">size</span> <span m=\"1444900\">of</span> <span m=\"1445020\"\
  >A.</span></p><p><span m=\"1447260\">But</span> <span m=\"1447480\">what</span>\
  \ <span m=\"1447870\">do</span> <span m=\"1447990\">you</span> <span m=\"1448920\"\
  >need</span> <span m=\"1449190\">to</span> <span m=\"1449280\">take</span> <span\
  \ m=\"1449940\">in</span> <span m=\"1450210\">Freiman's</span> <span m=\"1450540\"\
  >theorem</span> <span m=\"1451010\">for</span> <span m=\"1451390\">d</span> <span\
  \ m=\"1452100\">and</span> <span m=\"1452300\">for</span> <span m=\"1452760\">f?</span>\
  \ <span m=\"1453820\">So</span> <span m=\"1454140\">how</span> <span m=\"1454440\"\
  >can</span> <span m=\"1454620\">I</span> <span m=\"1454710\">embed</span> <span\
  \ m=\"1455100\">this</span> <span m=\"1455460\">A in</span> <span m=\"1455850\"\
  >generalized</span> <span m=\"1456600\">arithmetic</span> <span m=\"1457140\">progression?</span>\
  \ <span m=\"1459366\">See,</span> <span m=\"1461320\">there</span> <span m=\"1461700\"\
  >is</span> <span m=\"1461890\">not</span> <span m=\"1462310\">a</span> <span m=\"\
  1462370\">great</span> <span m=\"1462670\">way</span> <span m=\"1462820\">to</span>\
  \ <span m=\"1462910\">do</span> <span m=\"1463060\">it.</span> <span m=\"1463990\"\
  >So</span> <span m=\"1464140\">I</span> <span m=\"1464200\">want</span> <span m=\"\
  1464380\">to</span> <span m=\"1464440\">keep</span> <span m=\"1464740\">the</span>\
  \ <span m=\"1464860\">size</span> <span m=\"1465280\">small.</span> <span m=\"1466005\"\
  >There</span> <span m=\"1466280\">is</span> <span m=\"1466380\">not</span> <span\
  \ m=\"1466510\">a</span> <span m=\"1466540\">great</span> <span m=\"1466780\">way</span>\
  \ <span m=\"1466930\">to</span> <span m=\"1467050\">do</span> <span m=\"1467200\"\
  >it.</span></p><p><span m=\"1467660\">So</span> <span m=\"1468100\">one</span> <span\
  \ m=\"1468400\">way</span> <span m=\"1468520\">to</span> <span m=\"1468640\">do</span>\
  \ <span m=\"1468820\">it</span> <span m=\"1468940\">is</span> <span m=\"1469090\"\
  >to</span> <span m=\"1470020\">use</span> <span m=\"1470350\">one</span> <span m=\"\
  1471160\">direction</span> <span m=\"1471700\">for</span> <span m=\"1472180\">each</span>\
  \ <span m=\"1472510\">of</span> <span m=\"1472720\">these</span> <span m=\"1473230\"\
  >elements.</span> <span m=\"1475170\">So</span> <span m=\"1475690\">contained</span>\
  \ <span m=\"1478710\">in</span> <span m=\"1479070\">GAP--</span> <span m=\"1480410\"\
  >now</span> <span m=\"1480540\">of</span> <span m=\"1480630\">course,</span> <span\
  \ m=\"1480840\">there</span> <span m=\"1480950\">is</span> <span m=\"1481020\">always</span>\
  \ <span m=\"1481260\">a</span> <span m=\"1481340\">trade</span> <span m=\"1481440\"\
  >off</span> <span m=\"1481890\">between</span> <span m=\"1482580\">dimension</span>\
  \ <span m=\"1483030\">and</span> <span m=\"1483150\">size.</span> <span m=\"1483570\"\
  >But</span> <span m=\"1483690\">usually,</span> <span m=\"1484050\">not</span> <span\
  \ m=\"1484290\">a</span> <span m=\"1484320\">great-- I</span> <span m=\"1484740\"\
  >mean, it's</span> <span m=\"1485010\">not</span> <span m=\"1485400\">such</span>\
  \ <span m=\"1485640\">an</span> <span m=\"1485730\">important</span> <span m=\"\
  1486150\">trade off.</span> <span m=\"1486820\">So</span> <span m=\"1487170\">but</span>\
  \ <span m=\"1487830\">certainly</span> <span m=\"1488100\">it's</span> <span m=\"\
  1488220\">contained</span> <span m=\"1488570\">in</span> <span m=\"1488730\">the</span>\
  \ <span m=\"1488790\">GAP</span> <span m=\"1489780\">of</span> <span m=\"1490290\"\
  >dimension</span> <span m=\"1492060\">size</span> <span m=\"1492450\">of</span>\
  \ <span m=\"1492570\">A</span> <span m=\"1492690\">minus</span> <span m=\"1493110\"\
  >1</span> <span m=\"1493605\">and</span> <span m=\"1494100\">size</span> <span m=\"\
  1495180\">2</span> <span m=\"1495510\">to</span> <span m=\"1495660\">the</span>\
  \ <span m=\"1496200\">size</span> <span m=\"1496560\">of</span> <span m=\"1496680\"\
  >A</span> <span m=\"1497130\">minus</span> <span m=\"1497490\">1,</span> <span m=\"\
  1498120\">by</span> <span m=\"1498540\">thinking</span> <span m=\"1498870\">about</span>\
  \ <span m=\"1499170\">A</span> <span m=\"1499515\">as</span> <span m=\"1499860\"\
  >a</span> <span m=\"1500040\">cube.</span></p><p><span m=\"1503380\">And</span>\
  \ <span m=\"1504075\">so</span> <span m=\"1504440\">you</span> <span m=\"1504640\"\
  >convince</span> <span m=\"1504940\">yourself</span> <span m=\"1505270\">that</span>\
  \ <span m=\"1505390\">you</span> <span m=\"1505690\">basically</span> <span m=\"\
  1505990\">cannot</span> <span m=\"1506320\">do</span> <span m=\"1506440\">much</span>\
  \ <span m=\"1506620\">better.</span> <span m=\"1510400\">So</span> <span m=\"1510460\"\
  >the</span> <span m=\"1510550\">best</span> <span m=\"1510850\">possible</span>\
  \ <span m=\"1511300\">bound</span> <span m=\"1516930\">that</span> <span m=\"1517230\"\
  >we</span> <span m=\"1517350\">can</span> <span m=\"1517500\">hope</span> <span\
  \ m=\"1517740\">to</span> <span m=\"1517860\">prove</span> <span m=\"1524710\">is</span>\
  \ <span m=\"1525040\">of</span> <span m=\"1525160\">the</span> <span m=\"1525270\"\
  >form</span> <span m=\"1529320\">d</span> <span m=\"1529980\">being,</span> <span\
  \ m=\"1531150\">at</span> <span m=\"1531530\">most,</span> <span m=\"1531990\">linear</span>\
  \ <span m=\"1532380\">in</span> <span m=\"1532530\">k,</span> <span m=\"1533820\"\
  >and</span> <span m=\"1534540\">f</span> <span m=\"1535800\">being,</span> <span\
  \ m=\"1536680\">at</span> <span m=\"1536850\">most,</span> <span m=\"1537300\">exponential</span>\
  \ <span m=\"1537990\">in</span> <span m=\"1538190\">k.</span> <span m=\"1541680\"\
  >So</span> <span m=\"1541830\">you</span> <span m=\"1541920\">see</span> <span m=\"\
  1542130\">already,</span> <span m=\"1542430\">the</span> <span m=\"1542520\">bounds,</span>\
  \ <span m=\"1542960\">that</span> <span m=\"1543360\">you</span> <span m=\"1543510\"\
  >have</span> <span m=\"1543660\">to</span> <span m=\"1543750\">lose</span> <span\
  \ m=\"1543960\">some</span> <span m=\"1544150\">things.</span> <span m=\"1545130\"\
  >Yes?</span></p><p><span m=\"1545830\">AUDIENCE:</span> <span m=\"1545947\">Why</span>\
  \ <span m=\"1546064\">can't</span> <span m=\"1546181\">we</span> <span m=\"1546300\"\
  >just make</span> <span m=\"1546770\">the dimension</span> <span m=\"1547240\">1</span>\
  \ <span m=\"1547710\">and just</span> <span m=\"1548180\">let our</span> <span m=\"\
  1548650\">arithmetic</span> <span m=\"1549120\">progression be</span> <span m=\"\
  1549590\">1 through</span> <span m=\"1550060\">2 to</span> <span m=\"1550530\">the\
  \ sine of</span> <span m=\"1551000\">A minus 1?</span></p><p><span m=\"1551950\"\
  >YUFEI ZHAO:</span> <span m=\"1552070\">OK,</span> <span m=\"1552190\">great,</span>\
  \ <span m=\"1552850\">so</span> <span m=\"1553000\">that's</span> <span m=\"1553150\"\
  >a</span> <span m=\"1553180\">great</span> <span m=\"1553360\">question.</span>\
  \ <span m=\"1553730\">So</span> <span m=\"1553780\">why</span> <span m=\"1554110\"\
  >can't</span> <span m=\"1554320\">we</span> <span m=\"1554620\">just</span> <span\
  \ m=\"1555220\">make</span> <span m=\"1555400\">dimension</span> <span m=\"1555800\"\
  >1</span> <span m=\"1556600\">and</span> <span m=\"1556750\">have</span> <span m=\"\
  1557170\">the</span> <span m=\"1557290\">entire</span> <span m=\"1557860\">thing</span>\
  \ <span m=\"1558400\">be</span> <span m=\"1558580\">as</span> <span m=\"1558700\"\
  >part</span> <span m=\"1559000\">of</span> <span m=\"1559150\">a</span> <span m=\"\
  1559360\">single</span> <span m=\"1559720\">linear</span> <span m=\"1560020\">arithmetic</span>\
  \ <span m=\"1560410\">progression?</span> <span m=\"1561170\">So</span> <span m=\"\
  1561190\">you</span> <span m=\"1561280\">can</span> <span m=\"1561370\">do</span>\
  \ <span m=\"1561490\">that,</span> <span m=\"1562340\">but</span> <span m=\"1562810\"\
  >then</span> <span m=\"1563050\">I</span> <span m=\"1563140\">can</span> <span m=\"\
  1563290\">cook</span> <span m=\"1563560\">up</span> <span m=\"1563710\">other</span>\
  \ <span m=\"1563950\">examples</span> <span m=\"1564490\">where</span> <span m=\"\
  1564700\">I</span> <span m=\"1564820\">blow</span> <span m=\"1565300\">up</span>\
  \ <span m=\"1565540\">this</span> <span m=\"1565750\">cube.</span> <span m=\"1568110\"\
  >So</span> <span m=\"1568740\">I</span> <span m=\"1568840\">ask</span> <span m=\"\
  1569020\">you</span> <span m=\"1569080\">to</span> <span m=\"1569140\">think</span>\
  \ <span m=\"1569320\">about</span> <span m=\"1569470\">how</span> <span m=\"1569590\"\
  >to</span> <span m=\"1569680\">do</span> <span m=\"1569830\">that.</span> <span\
  \ m=\"1570080\">So</span> <span m=\"1570400\">you</span> <span m=\"1570490\">can</span>\
  \ <span m=\"1570640\">try</span> <span m=\"1570790\">to</span> <span m=\"1570880\"\
  >blow</span> <span m=\"1571210\">up</span> <span m=\"1571360\">this</span> <span\
  \ m=\"1571570\">cube</span> <span m=\"1572150\">so</span> <span m=\"1572330\">that</span>\
  \ <span m=\"1572470\">you</span> <span m=\"1572590\">really</span> <span m=\"1572830\"\
  >do</span> <span m=\"1573100\">need</span> <span m=\"1573970\">the</span> <span\
  \ m=\"1574330\">dimension</span> <span m=\"1574960\">to</span> <span m=\"1576130\"\
  >not</span> <span m=\"1576400\">be</span> <span m=\"1576520\">constant,</span> <span\
  \ m=\"1577792\">so</span> <span m=\"1578190\">exercise.</span></p><p><span m=\"\
  1581492\">So</span> <span m=\"1581970\">the</span> <span m=\"1582060\">best</span>\
  \ <span m=\"1582360\">result</span> <span m=\"1582780\">is</span> <span m=\"1583170\"\
  >not</span> <span m=\"1583350\">quite</span> <span m=\"1584130\">this</span> <span\
  \ m=\"1584400\">claim.</span> <span m=\"1584730\">So</span> <span m=\"1584850\"\
  >this</span> <span m=\"1585060\">is</span> <span m=\"1585180\">still</span> <span\
  \ m=\"1585480\">open.</span> <span m=\"1586080\">So</span> <span m=\"1586200\">the</span>\
  \ <span m=\"1586290\">best</span> <span m=\"1586620\">result</span> <span m=\"1587010\"\
  >so</span> <span m=\"1587220\">far</span> <span m=\"1589700\">is</span> <span m=\"\
  1589920\">due</span> <span m=\"1590100\">to</span> <span m=\"1590310\">Tom</span>\
  \ <span m=\"1590610\">Sanders,</span> <span m=\"1591630\">whose</span> <span m=\"\
  1591870\">name</span> <span m=\"1592110\">came</span> <span m=\"1592350\">up</span>\
  \ <span m=\"1592470\">earlier,</span> <span m=\"1592860\">as</span> <span m=\"1592950\"\
  >he</span> <span m=\"1593270\">has</span> <span m=\"1593790\">basically</span> <span\
  \ m=\"1594060\">the</span> <span m=\"1594150\">best</span> <span m=\"1594390\">bound</span>\
  \ <span m=\"1594720\">on</span> <span m=\"1594930\">Roth's</span> <span m=\"1595350\"\
  >theorem.</span> <span m=\"1595980\">And you</span> <span m=\"1596200\">know,</span>\
  \ <span m=\"1596340\">many</span> <span m=\"1596610\">of</span> <span m=\"1596700\"\
  >these</span> <span m=\"1596880\">results</span> <span m=\"1597210\">are</span>\
  \ <span m=\"1597270\">all</span> <span m=\"1597690\">related</span> <span m=\"1598050\"\
  >to</span> <span m=\"1598170\">each</span> <span m=\"1598380\">other.</span></p><p><span\
  \ m=\"1600160\">So</span> <span m=\"1600450\">Sanders</span> <span m=\"1601200\"\
  >has--</span> <span m=\"1603900\">so</span> <span m=\"1604080\">he</span> <span\
  \ m=\"1604230\">showed</span> <span m=\"1606850\">that</span> <span m=\"1607330\"\
  >Freiman's</span> <span m=\"1607900\">theorem</span> <span m=\"1611680\">is</span>\
  \ <span m=\"1611860\">true</span> <span m=\"1614620\">with</span> <span m=\"1617150\"\
  >d</span> <span m=\"1617750\">being,</span> <span m=\"1619070\">so</span> <span\
  \ m=\"1619220\">basically</span> <span m=\"1619850\">k, but</span> <span m=\"1620330\"\
  >you</span> <span m=\"1620480\">lose</span> <span m=\"1620900\">a</span> <span m=\"\
  1621020\">poly</span> <span m=\"1621410\">log</span> <span m=\"1621830\">factor.</span>\
  \ <span m=\"1624600\">I</span> <span m=\"1624700\">think</span> <span m=\"1624730\"\
  >the</span> <span m=\"1624820\">big O</span> <span m=\"1625030\">is</span> <span\
  \ m=\"1625330\">maybe</span> <span m=\"1625780\">3,</span> <span m=\"1626260\">or</span>\
  \ <span m=\"1626350\">4,</span> <span m=\"1627010\">something</span> <span m=\"\
  1627280\">like</span> <span m=\"1627430\">that,</span> <span m=\"1627610\">so</span>\
  \ <span m=\"1627940\">not</span> <span m=\"1628150\">substantial.</span> <span m=\"\
  1629390\">And</span> <span m=\"1629410\">then</span> <span m=\"1630070\">f</span>\
  \ <span m=\"1630280\">of</span> <span m=\"1630400\">k</span> <span m=\"1630730\"\
  >is</span> <span m=\"1631480\">also</span> <span m=\"1633520\">basically</span>\
  \ <span m=\"1633940\">exponential,</span> <span m=\"1634670\">but</span> <span m=\"\
  1634810\">you</span> <span m=\"1634930\">lose a</span> <span m=\"1635150\">poly</span>\
  \ <span m=\"1635200\">log</span> <span m=\"1635800\">factor</span> <span m=\"1636220\"\
  >in</span> <span m=\"1636430\">the</span> <span m=\"1636550\">exponent.</span></p><p><span\
  \ m=\"1641870\">Just</span> <span m=\"1642200\">a</span> <span m=\"1642740\">minor</span>\
  \ <span m=\"1643130\">note</span> <span m=\"1643370\">about</span> <span m=\"1643580\"\
  >how</span> <span m=\"1643790\">to</span> <span m=\"1643940\">read</span> <span\
  \ m=\"1644240\">this</span> <span m=\"1644420\">notation--</span> <span m=\"1645020\"\
  >so</span> <span m=\"1645620\">I</span> <span m=\"1645680\">mean,</span> <span m=\"\
  1645970\">it's</span> <span m=\"1646370\">written</span> <span m=\"1646640\">slightly</span>\
  \ <span m=\"1647060\">sloppily</span> <span m=\"1647720\">as</span> <span m=\"1647870\"\
  >log</span> <span m=\"1648140\">k</span> <span m=\"1648500\">raised</span> <span\
  \ m=\"1648830\">to</span> <span m=\"1649190\">big O</span> <span m=\"1649430\">of</span>\
  \ <span m=\"1649640\">1.</span> <span m=\"1649880\">You</span> <span m=\"1650120\"\
  >should</span> <span m=\"1650310\">think k</span> <span m=\"1650490\">as</span>\
  \ <span m=\"1651140\">constant,</span> <span m=\"1651710\">but</span> <span m=\"\
  1652250\">somewhat</span> <span m=\"1652760\">big,</span> <span m=\"1653750\">because</span>\
  \ <span m=\"1654170\">if</span> <span m=\"1654350\">k</span> <span m=\"1654830\"\
  >were</span> <span m=\"1655520\">2,</span> <span m=\"1656330\">this</span> <span\
  \ m=\"1656510\">notation</span> <span m=\"1656990\">actually</span> <span m=\"1657200\"\
  >doesn't</span> <span m=\"1657470\">make</span> <span m=\"1657620\">sense.</span>\
  \ <span m=\"1658560\">So</span> <span m=\"1658640\">just</span> <span m=\"1659510\"\
  >think</span> <span m=\"1659720\">of</span> <span m=\"1659810\">chaos,</span> <span\
  \ m=\"1660095\">as</span> <span m=\"1660380\">at</span> <span m=\"1660470\">least</span>\
  \ <span m=\"1661010\">3</span> <span m=\"1661910\">when</span> <span m=\"1662060\"\
  >you</span> <span m=\"1662150\">read</span> <span m=\"1662390\">that</span> <span\
  \ m=\"1662600\">notation.</span></p><p><span m=\"1665750\">All right,</span> <span\
  \ m=\"1666090\">so</span> <span m=\"1666240\">we</span> <span m=\"1666390\">will</span>\
  \ <span m=\"1666540\">prove</span> <span m=\"1667220\">Freiman's</span> <span m=\"\
  1667640\">theorem.</span> <span m=\"1669550\">So</span> <span m=\"1669750\">this</span>\
  \ <span m=\"1669930\">bound</span> <span m=\"1670200\">will</span> <span m=\"1670410\"\
  >show a</span> <span m=\"1670880\">worse</span> <span m=\"1671250\">bound.</span>\
  \ <span m=\"1671580\">It actually</span> <span m=\"1672240\">will</span> <span m=\"\
  1672570\">be</span> <span m=\"1672750\">basically</span> <span m=\"1673110\">exponentially</span>\
  \ <span m=\"1673770\">worse,</span> <span m=\"1674010\">but</span> <span m=\"1674130\"\
  >it</span> <span m=\"1674190\">will</span> <span m=\"1674280\">be</span> <span m=\"\
  1674370\">a</span> <span m=\"1674430\">constant.</span> <span m=\"1674820\">So</span>\
  \ <span m=\"1675000\">it will</span> <span m=\"1675090\">be</span> <span m=\"1675240\"\
  >just</span> <span m=\"1675720\">a</span> <span m=\"1675810\">function</span> <span\
  \ m=\"1676200\">of</span> <span m=\"1676290\">k.</span> <span m=\"1677370\">And</span>\
  \ <span m=\"1677900\">that</span> <span m=\"1678040\">will</span> <span m=\"1678150\"\
  >take</span> <span m=\"1678390\">us</span> <span m=\"1678510\">the</span> <span\
  \ m=\"1678600\">next</span> <span m=\"1678840\">several</span> <span m=\"1679080\"\
  >lectures.</span></p><p><span m=\"1680800\">So</span> <span m=\"1681010\">we'll</span>\
  \ <span m=\"1681190\">begin</span> <span m=\"1681880\">by</span> <span m=\"1683110\"\
  >developing</span> <span m=\"1683620\">some</span> <span m=\"1683830\">tools</span>\
  \ <span m=\"1684940\">that</span> <span m=\"1685090\">are, I</span> <span m=\"1685430\"\
  >think, of</span> <span m=\"1685800\">interest</span> <span m=\"1686410\">individually.</span>\
  \ <span m=\"1687070\">And</span> <span m=\"1687290\">they</span> <span m=\"1687460\"\
  >can</span> <span m=\"1687640\">all</span> <span m=\"1687760\">be</span> <span m=\"\
  1687910\">used</span> <span m=\"1688150\">for</span> <span m=\"1688300\">other</span>\
  \ <span m=\"1688480\">things.</span> <span m=\"1689480\">So</span> <span m=\"1689550\"\
  >we'll</span> <span m=\"1689690\">develop</span> <span m=\"1690040\">some</span>\
  \ <span m=\"1690220\">tools</span> <span m=\"1690610\">that</span> <span m=\"1690760\"\
  >will</span> <span m=\"1690850\">help</span> <span m=\"1691090\">us to</span> <span\
  \ m=\"1691390\">show,</span> <span m=\"1692500\">eventually</span> <span m=\"1692970\"\
  >lead</span> <span m=\"1693190\">us</span> <span m=\"1693340\">to</span> <span m=\"\
  1693430\">Freiman's</span> <span m=\"1693880\">theorem.</span></p><p><span m=\"\
  1695380\">And</span> <span m=\"1695650\">I'll</span> <span m=\"1696160\">try</span>\
  \ <span m=\"1696370\">to</span> <span m=\"1696490\">structure</span> <span m=\"\
  1696880\">this</span> <span m=\"1697060\">proof</span> <span m=\"1697540\">in</span>\
  \ <span m=\"1697660\">such</span> <span m=\"1697810\">a</span> <span m=\"1697870\"\
  >way</span> <span m=\"1698020\">that</span> <span m=\"1698170\">there</span> <span\
  \ m=\"1698290\">are</span> <span m=\"1698770\">several</span> <span m=\"1699750\"\
  >goal</span> <span m=\"1700130\">posts</span> <span m=\"1700930\">that</span> <span\
  \ m=\"1701110\">are</span> <span m=\"1701710\">also</span> <span m=\"1701950\">interesting.</span>\
  \ <span m=\"1702580\">So</span> <span m=\"1703180\">in</span> <span m=\"1703270\"\
  >particular,</span> <span m=\"1703810\">just</span> <span m=\"1704080\">as</span>\
  \ <span m=\"1704230\">what</span> <span m=\"1704350\">we</span> <span m=\"1704500\"\
  >did</span> <span m=\"1704770\">with</span> <span m=\"1705040\">Roth's</span> <span\
  \ m=\"1705355\">theorem,</span> <span m=\"1705960\">we'll</span> <span m=\"1706150\"\
  >begin</span> <span m=\"1706540\">by</span> <span m=\"1706720\">proving</span> <span\
  \ m=\"1707560\">a</span> <span m=\"1707710\">finite</span> <span m=\"1708200\">field</span>\
  \ <span m=\"1708640\">analog</span> <span m=\"1709870\">of</span> <span m=\"1710230\"\
  >Freiman's</span> <span m=\"1710630\">theorem.</span> <span m=\"1712270\">So</span>\
  \ <span m=\"1712420\">what</span> <span m=\"1713410\">would</span> <span m=\"1713560\"\
  >that</span> <span m=\"1713710\">mean,</span> <span m=\"1714205\">a</span> <span\
  \ m=\"1714520\">finite</span> <span m=\"1714880\">field</span> <span m=\"1715300\"\
  >analog?</span></p><p><span m=\"1716860\">So</span> <span m=\"1716980\">what</span>\
  \ <span m=\"1717190\">would</span> <span m=\"1717430\">a</span> <span m=\"1717550\"\
  >problem</span> <span m=\"1717880\">like</span> <span m=\"1718060\">this</span>\
  \ <span m=\"1718240\">mean</span> <span m=\"1718840\">in</span> <span m=\"1719250\"\
  >F2</span> <span m=\"1719470\">to</span> <span m=\"1719590\">the</span> <span m=\"\
  1719710\">n?</span> <span m=\"1732680\">So</span> <span m=\"1733030\">in</span>\
  \ <span m=\"1737160\">F2</span> <span m=\"1737500\">to</span> <span m=\"1737620\"\
  >the</span> <span m=\"1737750\">n,</span> <span m=\"1738130\">so</span> <span m=\"\
  1738280\">this</span> <span m=\"1738460\">is</span> <span m=\"1738580\">a</span>\
  \ <span m=\"1738640\">finite</span> <span m=\"1738940\">field</span> <span m=\"\
  1739200\">analog.</span> <span m=\"1740140\">If</span> <span m=\"1742540\">A</span>\
  \ <span m=\"1743020\">plus</span> <span m=\"1743500\">A</span> <span m=\"1743740\"\
  >is</span> <span m=\"1744610\">small--</span> <span m=\"1750005\">so</span> <span\
  \ m=\"1750420\">I'm</span> <span m=\"1750510\">not</span> <span m=\"1750610\">trying</span>\
  \ <span m=\"1750780\">to</span> <span m=\"1750840\">ask</span> <span m=\"1751080\"\
  >an</span> <span m=\"1751140\">inverse</span> <span m=\"1751530\">question.</span>\
  \ <span m=\"1753400\">But</span> <span m=\"1753660\">what</span> <span m=\"1754170\"\
  >are</span> <span m=\"1754350\">examples</span> <span m=\"1754950\">of</span> <span\
  \ m=\"1755100\">sets</span> <span m=\"1755910\">in</span> <span m=\"1756270\">F2</span>\
  \ <span m=\"1756420\">to</span> <span m=\"1756540\">the</span> <span m=\"1756660\"\
  >n</span> <span m=\"1756900\">that</span> <span m=\"1757050\">have</span> <span\
  \ m=\"1757320\">small</span> <span m=\"1757680\">doubling?</span></p><p><span m=\"\
  1760345\">AUDIENCE:</span> <span m=\"1760498\">2</span> <span m=\"1760651\">to</span>\
  \ <span m=\"1760806\">the n.</span></p><p><span m=\"1761728\">YUFEI ZHAO:</span>\
  \ <span m=\"1761959\">So</span> <span m=\"1762190\">2</span> <span m=\"1762550\"\
  >to</span> <span m=\"1762910\">the</span> <span m=\"1763010\">n,</span> <span m=\"\
  1763150\">so</span> <span m=\"1763280\">you</span> <span m=\"1763370\">can</span>\
  \ <span m=\"1763490\">take</span> <span m=\"1763640\">the</span> <span m=\"1763730\"\
  >entire</span> <span m=\"1764090\">space.</span> <span m=\"1765280\">Any</span>\
  \ <span m=\"1765470\">other</span> <span m=\"1765680\">examples</span> <span m=\"\
  1765940\">that</span> <span m=\"1766200\">have</span> <span m=\"1766340\">small</span>\
  \ <span m=\"1766670\">doubling?</span></p><p><span m=\"1773930\">AUDIENCE:</span>\
  \ <span m=\"1774177\">You can take a</span> <span m=\"1774425\">subspace.</span></p><p><span\
  \ m=\"1774920\">YUFEI ZHAO:</span> <span m=\"1775170\">Exactly,</span> <span m=\"\
  1775420\">I</span> <span m=\"1775690\">can</span> <span m=\"1775810\">take</span>\
  \ <span m=\"1775960\">a</span> <span m=\"1776020\">subspace.</span> <span m=\"1776620\"\
  >So a</span> <span m=\"1777100\">subspace,</span> <span m=\"1777850\">well,</span>\
  \ <span m=\"1778130\">it</span> <span m=\"1778240\">doesn't</span> <span m=\"1778480\"\
  >grow.</span> <span m=\"1778780\">So</span> <span m=\"1779130\">A</span> <span m=\"\
  1779270\">plus A</span> <span m=\"1779560\">is</span> <span m=\"1779820\">the</span>\
  \ <span m=\"1779900\">same</span> <span m=\"1780190\">as</span> <span m=\"1780310\"\
  >A.</span> <span m=\"1782380\">All</span> <span m=\"1782560\">right,</span> <span\
  \ m=\"1783140\">so</span> <span m=\"1783460\">and</span> <span m=\"1783570\">also,</span>\
  \ <span m=\"1783870\">as</span> <span m=\"1784020\">before,</span> <span m=\"1784320\"\
  >you</span> <span m=\"1784410\">can</span> <span m=\"1784560\">take</span> <span\
  \ m=\"1784710\">a</span> <span m=\"1784770\">subset</span> <span m=\"1785250\">of</span>\
  \ <span m=\"1785340\">a</span> <span m=\"1785400\">subspace.</span> <span m=\"1787960\"\
  >So</span> <span m=\"1788800\">then</span> <span m=\"1788980\">the</span> <span\
  \ m=\"1789090\">analog</span> <span m=\"1789540\">of</span> <span m=\"1789610\"\
  >Freiman's</span> <span m=\"1789850\">theorem</span> <span m=\"1790480\">will</span>\
  \ <span m=\"1790600\">say</span> <span m=\"1790900\">that</span> <span m=\"1793450\"\
  >A</span> <span m=\"1794260\">is</span> <span m=\"1794590\">contained</span> <span\
  \ m=\"1797730\">in</span> <span m=\"1799230\">a</span> <span m=\"1799860\">subspace</span>\
  \ <span m=\"1803520\">of</span> <span m=\"1803670\">size,</span> <span m=\"1805630\"\
  >at</span> <span m=\"1805830\">most,</span> <span m=\"1806950\">a</span> <span m=\"\
  1807300\">constant</span> <span m=\"1808830\">times</span> <span m=\"1809460\">the</span>\
  \ <span m=\"1809550\">size</span> <span m=\"1810180\">of</span> <span m=\"1810300\"\
  >A.</span></p><p><span m=\"1813930\">So</span> <span m=\"1814080\">this</span> <span\
  \ m=\"1814260\">is</span> <span m=\"1814380\">the</span> <span m=\"1814470\">analog</span>\
  \ <span m=\"1815310\">of</span> <span m=\"1816390\">Freiman's</span> <span m=\"\
  1816830\">theorem</span> <span m=\"1817770\">in</span> <span m=\"1818360\">F2.</span>\
  \ <span m=\"1818950\">And</span> <span m=\"1819300\">so</span> <span m=\"1819420\"\
  >we'll</span> <span m=\"1819600\">see,</span> <span m=\"1821340\">so</span> <span\
  \ m=\"1821490\">this</span> <span m=\"1821640\">will</span> <span m=\"1821760\"\
  >be</span> <span m=\"1821850\">much</span> <span m=\"1822060\">easier</span> <span\
  \ m=\"1822360\">than</span> <span m=\"1822530\">the</span> <span m=\"1822570\">general</span>\
  \ <span m=\"1822900\">result</span> <span m=\"1823270\">about</span> <span m=\"\
  1823450\">Freiman's</span> <span m=\"1823730\">theorem,</span> <span m=\"1824040\"\
  >but</span> <span m=\"1824080\">it</span> <span m=\"1824160\">will</span> <span\
  \ m=\"1824520\">involve</span> <span m=\"1825210\">a</span> <span m=\"1825240\"\
  >subset</span> <span m=\"1825810\">of</span> <span m=\"1825880\">F2.</span> <span\
  \ m=\"1826190\">And</span> <span m=\"1826380\">we'll</span> <span m=\"1826500\"\
  >see</span> <span m=\"1826710\">this</span> <span m=\"1826920\">theorem</span> <span\
  \ m=\"1827190\">first.</span> <span m=\"1828060\">So</span> <span m=\"1828120\"\
  >we'll</span> <span m=\"1828240\">prove</span> <span m=\"1828450\">that</span> <span\
  \ m=\"1828570\">next</span> <span m=\"1828840\">lecture.</span></p><p><span m=\"\
  1830760\">Of</span> <span m=\"1830820\">course,</span> <span m=\"1831370\">this\
  \ is</span> <span m=\"1832170\">much</span> <span m=\"1832390\">easier</span> <span\
  \ m=\"1832770\">in</span> <span m=\"1832860\">many</span> <span m=\"1833130\">ways,</span>\
  \ <span m=\"1833400\">because</span> <span m=\"1834090\">here,</span> <span m=\"\
  1834480\">unlike</span> <span m=\"1834780\">before,</span> <span m=\"1835050\">I</span>\
  \ <span m=\"1835140\">don't</span> <span m=\"1835320\">even</span> <span m=\"1835470\"\
  >have</span> <span m=\"1835620\">to</span> <span m=\"1835710\">think</span> <span\
  \ m=\"1835920\">about</span> <span m=\"1836130\">what</span> <span m=\"1836320\"\
  >subspace</span> <span m=\"1836880\">to</span> <span m=\"1836970\">take.</span>\
  \ <span m=\"1837700\">I</span> <span m=\"1837960\">can</span> <span m=\"1838110\"\
  >just</span> <span m=\"1838320\">take</span> <span m=\"1838560\">the</span> <span\
  \ m=\"1838620\">subspace</span> <span m=\"1839160\">generated</span> <span m=\"\
  1839730\">by</span> <span m=\"1840000\">the</span> <span m=\"1840120\">elements</span>\
  \ <span m=\"1840510\">of</span> <span m=\"1840620\">A.</span> <span m=\"1843900\"\
  >All right,</span> <span m=\"1845750\">Any</span> <span m=\"1846040\">questions</span>\
  \ <span m=\"1846470\">so</span> <span m=\"1846520\">far?</span> <span m=\"1849100\"\
  >Yes?</span></p><p><span m=\"1849584\">AUDIENCE:</span> <span m=\"1849745\">Is</span>\
  \ <span m=\"1849906\">the</span> <span m=\"1850068\">f of</span> <span m=\"1850552\"\
  >k here</span> <span m=\"1851036\">still</span> <span m=\"1851520\">exponential</span>\
  \ <span m=\"1852004\">in k?</span></p><p><span m=\"1852980\">YUFEI ZHAO:</span>\
  \ <span m=\"1853005\">OK,</span> <span m=\"1853370\">so</span> <span m=\"1853720\"\
  >the</span> <span m=\"1853940\">question,</span> <span m=\"1854230\">is</span> <span\
  \ m=\"1854390\">the</span> <span m=\"1854520\">f of k</span> <span m=\"1854770\"\
  >here</span> <span m=\"1855120\">still</span> <span m=\"1855320\">exponential</span>\
  \ <span m=\"1855920\">in</span> <span m=\"1856010\">k?</span> <span m=\"1856910\"\
  >So</span> <span m=\"1857180\">the</span> <span m=\"1857300\">answer</span> <span\
  \ m=\"1857680\">is,</span> <span m=\"1858140\">yes.</span> <span m=\"1858870\">And</span>\
  \ <span m=\"1859310\">the</span> <span m=\"1859430\">construction</span> <span m=\"\
  1860000\">is</span> <span m=\"1860150\">if</span> <span m=\"1860240\">you</span>\
  \ <span m=\"1860330\">take</span> <span m=\"1860570\">A</span> <span m=\"1860720\"\
  >to</span> <span m=\"1860870\">be</span> <span m=\"1861020\">a</span> <span m=\"\
  1861080\">basis.</span></p><p><span m=\"1865790\">OK,</span> <span m=\"1866270\"\
  >so</span> <span m=\"1866420\">let's</span> <span m=\"1866570\">start</span> <span\
  \ m=\"1866930\">with</span> <span m=\"1867290\">some</span> <span m=\"1868760\"\
  >techniques</span> <span m=\"1869270\">and</span> <span m=\"1869390\">some</span>\
  \ <span m=\"1869570\">proofs.</span> <span m=\"1883830\">So</span> <span m=\"1884720\"\
  >in</span> <span m=\"1884840\">this</span> <span m=\"1884990\">chapter,</span> <span\
  \ m=\"1885350\">many</span> <span m=\"1885650\">things</span> <span m=\"1886220\"\
  >are</span> <span m=\"1886430\">named</span> <span m=\"1886820\">after</span> <span\
  \ m=\"1887130\">Ruzsa.</span> <span m=\"1887900\">And</span> <span m=\"1888020\"\
  >at</span> <span m=\"1888080\">some</span> <span m=\"1888260\">point,</span> <span\
  \ m=\"1888470\">it</span> <span m=\"1888710\">becomes</span> <span m=\"1889820\"\
  >slightly</span> <span m=\"1890180\">confusing</span> <span m=\"1890960\">which</span>\
  \ <span m=\"1891170\">ones</span> <span m=\"1891380\">are</span> <span m=\"1891470\"\
  >not</span> <span m=\"1891710\">named</span> <span m=\"1891980\">after</span> <span\
  \ m=\"1892230\">Ruzsa.</span> <span m=\"1893750\">But</span> <span m=\"1893900\"\
  >the</span> <span m=\"1893960\">first</span> <span m=\"1894200\">thing</span> <span\
  \ m=\"1894320\">will</span> <span m=\"1894440\">be</span> <span m=\"1894560\">named</span>\
  \ <span m=\"1894800\">after</span> <span m=\"1895090\">Ruzsa.</span> <span m=\"\
  1895270\">So it's a</span> <span m=\"1895560\">Ruzsa</span> <span m=\"1895910\"\
  >Triangle</span> <span m=\"1896360\">Inequality.</span></p><p><span m=\"1905197\"\
  >All</span> <span m=\"1905700\">right,</span> <span m=\"1907120\">the</span> <span\
  \ m=\"1907230\">Ruzsa</span> <span m=\"1907470\">Triangle</span> <span m=\"1907830\"\
  >Inequality</span> <span m=\"1908520\">tells</span> <span m=\"1908820\">us</span>\
  \ <span m=\"1909330\">that,</span> <span m=\"1909720\">if</span> <span m=\"1911010\"\
  >A,</span> <span m=\"1911250\">B,</span> <span m=\"1911430\">and</span> <span m=\"\
  1911570\">C--</span> <span m=\"1912390\">so</span> <span m=\"1912840\">unless</span>\
  \ <span m=\"1913230\">otherwise</span> <span m=\"1913710\">I</span> <span m=\"1913800\"\
  >tell</span> <span m=\"1914010\">you</span> <span m=\"1914190\">so,</span> <span\
  \ m=\"1914500\">and</span> <span m=\"1914650\">I'll</span> <span m=\"1915300\">try</span>\
  \ <span m=\"1915450\">to</span> <span m=\"1915570\">remind</span> <span m=\"1915900\"\
  >you</span> <span m=\"1916020\">each</span> <span m=\"1916200\">time,</span> <span\
  \ m=\"1916620\">but</span> <span m=\"1916860\">basically,</span> <span m=\"1917310\"\
  >we're</span> <span m=\"1917460\">always</span> <span m=\"1917730\">going</span>\
  \ <span m=\"1917840\">to</span> <span m=\"1917930\">be</span> <span m=\"1918030\"\
  >looking</span> <span m=\"1918920\">finite</span> <span m=\"1919420\">sets</span>\
  \ <span m=\"1921240\">in</span> <span m=\"1921630\">an</span> <span m=\"1921750\"\
  >arbitrary</span> <span m=\"1922340\">obedient</span> <span m=\"1922710\">group</span>\
  \ <span m=\"1926500\">always</span> <span m=\"1926920\">with</span> <span m=\"1927100\"\
  >an</span> <span m=\"1927220\">under</span> <span m=\"1927660\">addition--</span>\
  \ <span m=\"1929940\">then</span> <span m=\"1930330\">one</span> <span m=\"1930630\"\
  >has</span> <span m=\"1930960\">the</span> <span m=\"1931080\">inequality</span>\
  \ <span m=\"1932160\">on</span> <span m=\"1932450\">their</span> <span m=\"1933720\"\
  >sizes</span> <span m=\"1934380\">of</span> <span m=\"1934700\">different</span>\
  \ <span m=\"1935340\">sets.</span> <span m=\"1942750\">The</span> <span m=\"1943040\"\
  >size</span> <span m=\"1943430\">of</span> <span m=\"1943520\">A</span> <span m=\"\
  1943700\">times</span> <span m=\"1944060\">the</span> <span m=\"1944120\">size</span>\
  \ <span m=\"1944420\">of</span> <span m=\"1944510\">B</span> <span m=\"1944660\"\
  >minus</span> <span m=\"1944930\">C</span> <span m=\"1945520\">is</span> <span m=\"\
  1945710\">upper</span> <span m=\"1945890\">bounded</span> <span m=\"1946250\">by</span>\
  \ <span m=\"1946400\">the</span> <span m=\"1946490\">size</span> <span m=\"1946730\"\
  >of</span> <span m=\"1946850\">A</span> <span m=\"1946970\">minus</span> <span m=\"\
  1947260\">B</span> <span m=\"1947930\">times</span> <span m=\"1948240\">the</span>\
  \ <span m=\"1948320\">size</span> <span m=\"1948590\">of</span> <span m=\"1948680\"\
  >A</span> <span m=\"1948800\">minus</span> <span m=\"1949070\">C.</span> <span m=\"\
  1951730\">So</span> <span m=\"1951850\">that's</span> <span m=\"1952090\">the</span>\
  \ <span m=\"1952270\">Ruzsa</span> <span m=\"1952780\">Triangle</span> <span m=\"\
  1953290\">Inequality.</span></p><p><span m=\"1956500\">Let</span> <span m=\"1956600\"\
  >me</span> <span m=\"1956610\">show</span> <span m=\"1956730\">you</span> <span\
  \ m=\"1956790\">the</span> <span m=\"1956880\">proof.</span> <span m=\"1959490\"\
  >We</span> <span m=\"1959670\">will</span> <span m=\"1959820\">construct</span>\
  \ <span m=\"1962068\">an</span> <span m=\"1962480\">injection</span> <span m=\"\
  1966170\">from</span> <span m=\"1967160\">A</span> <span m=\"1967940\">cross</span>\
  \ <span m=\"1969170\">B</span> <span m=\"1969320\">minus</span> <span m=\"1969620\"\
  >C</span> <span m=\"1971300\">to</span> <span m=\"1973520\">A</span> <span m=\"\
  1973670\">minus</span> <span m=\"1974090\">B</span> <span m=\"1974960\">cross</span>\
  \ <span m=\"1976190\">A</span> <span m=\"1976280\">minus</span> <span m=\"1976550\"\
  >C.</span> <span m=\"1977120\">Of</span> <span m=\"1977180\">course,</span> <span\
  \ m=\"1977420\">if</span> <span m=\"1977510\">you</span> <span m=\"1977630\">can</span>\
  \ <span m=\"1978020\">exhibit</span> <span m=\"1978410\">such</span> <span m=\"\
  1978710\">an</span> <span m=\"1978860\">injection,</span> <span m=\"1979620\">then</span>\
  \ <span m=\"1979700\">you</span> <span m=\"1979820\">prove</span> <span m=\"1980150\"\
  >the</span> <span m=\"1980270\">desired</span> <span m=\"1980810\">inequality.</span>\
  \ <span m=\"1983170\">To</span> <span m=\"1983350\">obtain</span> <span m=\"1983680\"\
  >this</span> <span m=\"1983860\">injection,</span> <span m=\"1985570\">we</span>\
  \ <span m=\"1985690\">start</span> <span m=\"1986170\">with</span> <span m=\"1987160\"\
  >an</span> <span m=\"1987280\">element</span> <span m=\"1989010\">a,</span> <span\
  \ m=\"1989130\">d.</span></p><p><span m=\"1991640\">And</span> <span m=\"1992750\"\
  >for</span> <span m=\"1993020\">this</span> <span m=\"1993290\">a,</span> <span\
  \ m=\"1993410\">d,</span> <span m=\"1994700\">so</span> <span m=\"1994850\">for</span>\
  \ <span m=\"1995000\">each</span> <span m=\"1995550\">d,</span> <span m=\"1996470\"\
  >let</span> <span m=\"1996650\">me</span> <span m=\"1996920\">pick--</span> <span\
  \ m=\"2000410\">so</span> <span m=\"2000550\">if</span> <span m=\"2002010\">d</span>\
  \ <span m=\"2002680\">is</span> <span m=\"2002860\">an</span> <span m=\"2002950\"\
  >element</span> <span m=\"2003270\">of</span> <span m=\"2003340\">B</span> <span\
  \ m=\"2003490\">minus</span> <span m=\"2003760\">C,</span> <span m=\"2004850\">let</span>\
  \ <span m=\"2005020\">us</span> <span m=\"2005920\">pick</span> <span m=\"2006790\"\
  >arbitrarily</span> <span m=\"2007990\">but</span> <span m=\"2008110\">stick</span>\
  \ <span m=\"2008440\">with</span> <span m=\"2008590\">those</span> <span m=\"2008830\"\
  >choices</span> <span m=\"2010450\">a</span> <span m=\"2013860\">b</span> <span\
  \ m=\"2014040\">of</span> <span m=\"2014540\">d</span> <span m=\"2015306\">in</span>\
  \ <span m=\"2015690\">the</span> <span m=\"2015760\">set</span> <span m=\"2016060\"\
  >B</span> <span m=\"2017110\">and</span> <span m=\"2018030\">a</span> <span m=\"\
  2018130\">c</span> <span m=\"2018460\">of</span> <span m=\"2018645\">d</span> <span\
  \ m=\"2019200\">in</span> <span m=\"2019320\">the</span> <span m=\"2019390\">set</span>\
  \ <span m=\"2019660\">C</span> <span m=\"2021190\">such</span> <span m=\"2021550\"\
  >that</span> <span m=\"2022270\">d</span> <span m=\"2022780\">equals</span> <span\
  \ m=\"2023230\">to</span> <span m=\"2024430\">b</span> <span m=\"2024610\">of</span>\
  \ <span m=\"2024730\">d</span> <span m=\"2025240\">minus</span> <span m=\"2026100\"\
  >c of</span> <span m=\"2026550\">d.</span> <span m=\"2027180\">So</span> <span m=\"\
  2028120\">because</span> <span m=\"2028510\">d</span> <span m=\"2028900\">is</span>\
  \ <span m=\"2029020\">the</span> <span m=\"2029080\">set</span> <span m=\"2029830\"\
  >B</span> <span m=\"2029980\">minus</span> <span m=\"2030280\">C,</span> <span m=\"\
  2031660\">it</span> <span m=\"2031900\">can</span> <span m=\"2032020\">be</span>\
  \ <span m=\"2032140\">represented</span> <span m=\"2032950\">as</span> <span m=\"\
  2033100\">a</span> <span m=\"2033130\">difference</span> <span m=\"2033790\">from</span>\
  \ <span m=\"2034150\">one</span> <span m=\"2034390\">element</span> <span m=\"2034720\"\
  >from each</span> <span m=\"2035040\">set.</span> <span m=\"2035340\">So</span>\
  \ <span m=\"2035700\">it</span> <span m=\"2036050\">may</span> <span m=\"2036250\"\
  >be</span> <span m=\"2036430\">represented</span> <span m=\"2036910\">in</span>\
  \ <span m=\"2037000\">many</span> <span m=\"2037300\">ways.</span></p><p><span m=\"\
  2038210\">But</span> <span m=\"2038500\">from</span> <span m=\"2038740\">the</span>\
  \ <span m=\"2038830\">start,</span> <span m=\"2039250\">you</span> <span m=\"2039370\"\
  >pick</span> <span m=\"2039790\">a</span> <span m=\"2039880\">way</span> <span m=\"\
  2040060\">to</span> <span m=\"2040210\">represent</span> <span m=\"2040630\">it.</span>\
  \ <span m=\"2040740\">And</span> <span m=\"2040870\">you</span> <span m=\"2040960\"\
  >stick</span> <span m=\"2041290\">with</span> <span m=\"2041440\">that</span> <span\
  \ m=\"2041590\">choice.</span> <span m=\"2042290\">And</span> <span m=\"2042390\"\
  >you</span> <span m=\"2042400\">label</span> <span m=\"2042700\">that</span> <span\
  \ m=\"2042940\">function</span> <span m=\"2043330\">b of</span> <span m=\"2043750\"\
  >d</span> <span m=\"2044515\">and</span> <span m=\"2044870\">c</span> <span m=\"\
  2044960\">of</span> <span m=\"2045160\">d.</span></p><p><span m=\"2048670\">Now</span>\
  \ <span m=\"2049150\">I</span> <span m=\"2049300\">map</span> <span m=\"2049989\"\
  >a,</span> <span m=\"2050139\">d</span> <span m=\"2052780\">to</span> <span m=\"\
  2053409\">the</span> <span m=\"2054100\">element</span> <span m=\"2055600\">a</span>\
  \ <span m=\"2056080\">minus</span> <span m=\"2057880\">b</span> <span m=\"2058090\"\
  >of</span> <span m=\"2058210\">d</span> <span m=\"2059170\">and</span> <span m=\"\
  2059440\">a</span> <span m=\"2059920\">minus</span> <span m=\"2061570\">c of</span>\
  \ <span m=\"2061870\">d.</span> <span m=\"2068070\">So</span> <span m=\"2068850\"\
  >this</span> <span m=\"2069030\">is</span> <span m=\"2069120\">a</span> <span m=\"\
  2069179\">map.</span> <span m=\"2070230\">I</span> <span m=\"2070320\">want</span>\
  \ <span m=\"2070500\">to</span> <span m=\"2070560\">show</span> <span m=\"2070739\"\
  >that</span> <span m=\"2070860\">it</span> <span m=\"2070949\">is</span> <span m=\"\
  2071100\">injective.</span> <span m=\"2075830\">Why</span> <span m=\"2076070\">is</span>\
  \ <span m=\"2076190\">it</span> <span m=\"2076250\">injective?</span> <span m=\"\
  2081760\">Well,</span> <span m=\"2081929\">to</span> <span m=\"2082040\">show</span>\
  \ <span m=\"2082230\">something</span> <span m=\"2082360\">is</span> <span m=\"\
  2082710\">injective,</span> <span m=\"2083650\">I</span> <span m=\"2083770\">just</span>\
  \ <span m=\"2083920\">need</span> <span m=\"2084040\">to</span> <span m=\"2084130\"\
  >show</span> <span m=\"2084370\">that</span> <span m=\"2084520\">I</span> <span\
  \ m=\"2084610\">can</span> <span m=\"2084790\">recover</span> <span m=\"2085540\"\
  >where</span> <span m=\"2085780\">I</span> <span m=\"2085840\">came</span> <span\
  \ m=\"2086080\">from</span> <span m=\"2086440\">if</span> <span m=\"2086560\">I</span>\
  \ <span m=\"2086710\">tell</span> <span m=\"2086949\">you</span> <span m=\"2087790\"\
  >the</span> <span m=\"2088360\">image.</span> <span m=\"2089810\">So</span> <span\
  \ m=\"2089860\">I</span> <span m=\"2089949\">can</span> <span m=\"2090100\">recover</span>\
  \ <span m=\"2090385\">a</span> <span m=\"2090670\">and</span> <span m=\"2090969\"\
  >d</span> <span m=\"2092230\">from</span> <span m=\"2092889\">these</span> <span\
  \ m=\"2093130\">two</span> <span m=\"2093370\">numbers.</span> <span m=\"2094850\"\
  >So</span> <span m=\"2095199\">if--</span> <span m=\"2097659\">sorry,</span> <span\
  \ m=\"2098097\">new</span> <span m=\"2098540\">board.</span></p><p><span m=\"2105040\"\
  >OK,</span> <span m=\"2105250\">so</span> <span m=\"2106410\">well</span> <span\
  \ m=\"2106720\">you</span> <span m=\"2106810\">basically</span> <span m=\"2107140\"\
  >can</span> <span m=\"2107260\">think</span> <span m=\"2107470\">about</span> <span\
  \ m=\"2108280\">how</span> <span m=\"2108520\">you</span> <span m=\"2108640\">can</span>\
  \ <span m=\"2108820\">recover</span> <span m=\"2109600\">a and</span> <span m=\"\
  2109900\">d</span> <span m=\"2110620\">from</span> <span m=\"2111160\">the</span>\
  \ <span m=\"2111340\">image</span> <span m=\"2111850\">elements.</span> <span m=\"\
  2121540\">So</span> <span m=\"2121770\">if</span> <span m=\"2122570\">the</span>\
  \ <span m=\"2123150\">image--</span> <span m=\"2124140\">so</span> <span m=\"2124360\"\
  >I</span> <span m=\"2124410\">label</span> <span m=\"2124710\">that</span> <span\
  \ m=\"2124860\">map</span> <span m=\"2125210\">phi.</span> <span m=\"2127440\">So</span>\
  \ <span m=\"2127560\">that's</span> <span m=\"2127740\">phi</span> <span m=\"2128040\"\
  >up</span> <span m=\"2128310\">there.</span> <span m=\"2128790\">So</span> <span\
  \ m=\"2129060\">if</span> <span m=\"2129660\">the</span> <span m=\"2129900\">image</span>\
  \ <span m=\"2130350\">is</span> <span m=\"2130560\">given,</span> <span m=\"2134730\"\
  >then</span> <span m=\"2135360\">I</span> <span m=\"2135450\">can</span> <span m=\"\
  2135630\">recover</span> <span m=\"2141920\">d.</span></p><p><span m=\"2142520\"\
  >So</span> <span m=\"2142640\">how</span> <span m=\"2142760\">can</span> <span m=\"\
  2142940\">we</span> <span m=\"2143060\">recover</span> <span m=\"2143540\">the</span>\
  \ <span m=\"2143690\">element</span> <span m=\"2144080\">d?</span> <span m=\"2150810\"\
  >So</span> <span m=\"2150930\">you</span> <span m=\"2151050\">subtract</span> <span\
  \ m=\"2151650\">these</span> <span m=\"2151890\">two</span> <span m=\"2152430\"\
  >numbers.</span> <span m=\"2153090\">So</span> <span m=\"2153180\">d</span> <span\
  \ m=\"2153450\">is</span> <span m=\"2154470\">minus</span> <span m=\"2154940\">x.</span>\
  \ <span m=\"2155860\">And</span> <span m=\"2156060\">once</span> <span m=\"2156330\"\
  >you</span> <span m=\"2156420\">recover</span> <span m=\"2156930\">d,</span> <span\
  \ m=\"2157900\">you can</span> <span m=\"2158220\">also</span> <span m=\"2158580\"\
  >then</span> <span m=\"2158760\">take</span> <span m=\"2158940\">a</span> <span\
  \ m=\"2159000\">look</span> <span m=\"2159180\">at</span> <span m=\"2159240\">the</span>\
  \ <span m=\"2159300\">first</span> <span m=\"2159630\">element.</span> <span m=\"\
  2160230\">And</span> <span m=\"2160320\">you</span> <span m=\"2160380\">can</span>\
  \ <span m=\"2160530\">recover</span> <span m=\"2161440\">a.</span> <span m=\"2166030\"\
  >So</span> <span m=\"2166230\">now</span> <span m=\"2166440\">you</span> <span m=\"\
  2166530\">know</span> <span m=\"2166680\">d.</span> <span m=\"2166980\">I</span>\
  \ <span m=\"2167040\">can</span> <span m=\"2167190\">now</span> <span m=\"2167370\"\
  >recover</span> <span m=\"2167860\">a.</span></p><p><span m=\"2170490\">OK,</span>\
  \ <span m=\"2170780\">so</span> <span m=\"2170900\">then</span> <span m=\"2171350\"\
  >this</span> <span m=\"2171560\">is--</span> <span m=\"2171790\">you</span> <span\
  \ m=\"2171870\">can</span> <span m=\"2171980\">check</span> <span m=\"2172270\"\
  >this</span> <span m=\"2172430\">is</span> <span m=\"2172520\">an</span> <span m=\"\
  2172610\">injection.</span> <span m=\"2173420\">And that</span> <span m=\"2173780\"\
  >proves</span> <span m=\"2175660\">the</span> <span m=\"2176410\">Ruzsa</span> <span\
  \ m=\"2176750\">Triangle</span> <span m=\"2177290\">Inequality.</span> <span m=\"\
  2179269\">OK,</span> <span m=\"2179762\">so</span> <span m=\"2182230\">it's</span>\
  \ <span m=\"2182420\">short,</span> <span m=\"2182900\">but</span> <span m=\"2183220\"\
  >it's</span> <span m=\"2183720\">tricky.</span> <span m=\"2184468\">It's tricky.</span></p><p><span\
  \ m=\"2186380\">OK, so</span> <span m=\"2186860\">why</span> <span m=\"2187130\"\
  >is</span> <span m=\"2187250\">this</span> <span m=\"2187430\">called</span> <span\
  \ m=\"2187790\">Ruzsa's</span> <span m=\"2188270\">Triangle</span> <span m=\"2188780\"\
  >Inequality?</span> <span m=\"2189320\">Where is</span> <span m=\"2189590\">the</span>\
  \ <span m=\"2189680\">triangle</span> <span m=\"2190170\">in</span> <span m=\"2190240\"\
  >this?</span> <span m=\"2191770\">The</span> <span m=\"2191840\">reason</span> <span\
  \ m=\"2192170\">that</span> <span m=\"2193020\">it's</span> <span m=\"2193190\"\
  >given</span> <span m=\"2193460\">that</span> <span m=\"2193580\">name</span> <span\
  \ m=\"2194060\">is</span> <span m=\"2194160\">that</span> <span m=\"2194330\">you</span>\
  \ <span m=\"2194450\">can</span> <span m=\"2194690\">write</span> <span m=\"2196090\"\
  >the</span> <span m=\"2196430\">inequality</span> <span m=\"2197030\">as</span>\
  \ <span m=\"2197180\">follows.</span> <span m=\"2198360\">Suppose</span> <span m=\"\
  2198650\">we</span> <span m=\"2199880\">use</span> <span m=\"2200270\">rho</span>\
  \ <span m=\"2201440\">A,</span> <span m=\"2201920\">B</span> <span m=\"2202580\"\
  >to</span> <span m=\"2202700\">denote</span> <span m=\"2203300\">this</span> <span\
  \ m=\"2203510\">quantity</span> <span m=\"2204660\">obtained</span> <span m=\"2205070\"\
  >by</span> <span m=\"2205310\">taking</span> <span m=\"2205650\">the</span> <span\
  \ m=\"2205730\">log</span> <span m=\"2206330\">of</span> <span m=\"2207140\">the</span>\
  \ <span m=\"2207200\">size</span> <span m=\"2207680\">of</span> <span m=\"2207800\"\
  >A</span> <span m=\"2208010\">minus</span> <span m=\"2208430\">B</span> <span m=\"\
  2209150\">divided</span> <span m=\"2209630\">by</span> <span m=\"2210380\">the</span>\
  \ <span m=\"2210500\">square</span> <span m=\"2210800\">root</span> <span m=\"2211670\"\
  >of</span> <span m=\"2211880\">the</span> <span m=\"2212000\">product</span> <span\
  \ m=\"2212510\">of</span> <span m=\"2212630\">their</span> <span m=\"2212810\">individual</span>\
  \ <span m=\"2213350\">sizes,</span> <span m=\"2214850\">then</span> <span m=\"2217130\"\
  >the</span> <span m=\"2217640\">inequality</span> <span m=\"2219470\">says</span>\
  \ <span m=\"2221060\">that</span> <span m=\"2221820\">the</span> <span m=\"2222080\"\
  >rho</span> <span m=\"2222530\">of</span> <span m=\"2223400\">B,</span> <span m=\"\
  2223980\">C</span> <span m=\"2224810\">is,</span> <span m=\"2224980\">at</span>\
  \ <span m=\"2225130\">most,</span> <span m=\"2225860\">rho</span> <span m=\"2226190\"\
  >of</span> <span m=\"2226370\">A,</span> <span m=\"2226850\">B</span> <span m=\"\
  2227660\">plus</span> <span m=\"2228500\">rho</span> <span m=\"2228800\">of</span>\
  \ <span m=\"2229040\">A,</span> <span m=\"2229550\">C,</span> <span m=\"2231690\"\
  >which</span> <span m=\"2231990\">looks</span> <span m=\"2232350\">like</span> <span\
  \ m=\"2232590\">a</span> <span m=\"2232650\">triangle</span> <span m=\"2233100\"\
  >inequality.</span></p><p><span m=\"2234590\">So</span> <span m=\"2234690\">that's</span>\
  \ <span m=\"2234840\">why</span> <span m=\"2235020\">it's</span> <span m=\"2235140\"\
  >called</span> <span m=\"2235350\">Ruzsa's</span> <span m=\"2235680\">Triangle</span>\
  \ <span m=\"2236040\">Inequality,</span> <span m=\"2236910\">because</span> <span\
  \ m=\"2237150\">this</span> <span m=\"2237360\">is--</span> <span m=\"2237720\"\
  >don't</span> <span m=\"2237930\">take</span> <span m=\"2238140\">it</span> <span\
  \ m=\"2238200\">too</span> <span m=\"2238410\">seriously,</span> <span m=\"2239280\"\
  >because</span> <span m=\"2239640\">this</span> <span m=\"2239820\">is</span> <span\
  \ m=\"2239910\">not</span> <span m=\"2240270\">a</span> <span m=\"2240360\">distance.</span>\
  \ <span m=\"2244960\">So</span> <span m=\"2245200\">rho</span> <span m=\"2245600\"\
  >of</span> <span m=\"2245790\">A,</span> <span m=\"2246390\">A</span> <span m=\"\
  2246690\">is</span> <span m=\"2247110\">not</span> <span m=\"2247440\">equal</span>\
  \ <span m=\"2247680\">to</span> <span m=\"2247800\">0.</span> <span m=\"2250560\"\
  >But it</span> <span m=\"2250920\">certainly</span> <span m=\"2251610\">has</span>\
  \ <span m=\"2251910\">the</span> <span m=\"2252000\">form</span> <span m=\"2252330\"\
  >of</span> <span m=\"2252420\">a</span> <span m=\"2252480\">triangle</span> <span\
  \ m=\"2252860\">inequality,</span> <span m=\"2253500\">hence</span> <span m=\"2253770\"\
  >the</span> <span m=\"2253860\">name.</span></p><p><span m=\"2257560\">How</span>\
  \ <span m=\"2257770\">should</span> <span m=\"2257980\">you</span> <span m=\"2258070\"\
  >think</span> <span m=\"2258340\">of</span> <span m=\"2258560\">Ruzsa's</span> <span\
  \ m=\"2258730\">triangle</span> <span m=\"2259280\">inequality?</span> <span m=\"\
  2259780\">So</span> <span m=\"2260020\">in</span> <span m=\"2260140\">this</span>\
  \ <span m=\"2260290\">chapter,</span> <span m=\"2260650\">there's</span> <span m=\"\
  2260800\">going</span> <span m=\"2260900\">to</span> <span m=\"2260980\">be</span>\
  \ <span m=\"2261070\">a</span> <span m=\"2261100\">lot</span> <span m=\"2261280\"\
  >of</span> <span m=\"2261370\">symbol</span> <span m=\"2261730\">pushing</span>\
  \ <span m=\"2262060\">around.</span> <span m=\"2262480\">And</span> <span m=\"2262630\"\
  >it's</span> <span m=\"2262780\">easy</span> <span m=\"2262960\">to</span> <span\
  \ m=\"2263050\">get</span> <span m=\"2263200\">lost</span> <span m=\"2263650\">and</span>\
  \ <span m=\"2263890\">buried</span> <span m=\"2264370\">in</span> <span m=\"2264520\"\
  >all</span> <span m=\"2264640\">of</span> <span m=\"2264700\">these</span> <span\
  \ m=\"2264820\">symbols.</span> <span m=\"2265310\">And</span> <span m=\"2265770\"\
  >I</span> <span m=\"2265840\">want</span> <span m=\"2266020\">to</span> <span m=\"\
  2267250\">tell</span> <span m=\"2267490\">you</span> <span m=\"2267550\">about</span>\
  \ <span m=\"2267670\">how</span> <span m=\"2268300\">you</span> <span m=\"2268390\"\
  >might</span> <span m=\"2268570\">think</span> <span m=\"2268840\">about</span>\
  \ <span m=\"2269620\">what's</span> <span m=\"2271430\">the</span> <span m=\"2271520\"\
  >point</span> <span m=\"2271790\">of</span> <span m=\"2271850\">Ruzsa's</span> <span\
  \ m=\"2272150\">Triangle</span> <span m=\"2272450\">Inequality.</span> <span m=\"\
  2272930\">How</span> <span m=\"2273200\">would</span> <span m=\"2273380\">you</span>\
  \ <span m=\"2273470\">use</span> <span m=\"2273680\">it?</span></p><p><span m=\"\
  2275120\">And</span> <span m=\"2275270\">the</span> <span m=\"2275390\">idea</span>\
  \ <span m=\"2275810\">is</span> <span m=\"2276050\">that</span> <span m=\"2276740\"\
  >if</span> <span m=\"2276950\">you</span> <span m=\"2277220\">have</span> <span\
  \ m=\"2277820\">a</span> <span m=\"2278080\">set</span> <span m=\"2279020\">with</span>\
  \ <span m=\"2279800\">small</span> <span m=\"2280460\">doubling,</span> <span m=\"\
  2282230\">we</span> <span m=\"2282410\">want</span> <span m=\"2282620\">to</span>\
  \ <span m=\"2282710\">use</span> <span m=\"2283370\">Ruzsa's</span> <span m=\"2283730\"\
  >triangle</span> <span m=\"2284090\">inequality</span> <span m=\"2284780\">and</span>\
  \ <span m=\"2284900\">other</span> <span m=\"2285140\">tools</span> <span m=\"2285980\"\
  >to</span> <span m=\"2286130\">control</span> <span m=\"2286730\">its</span> <span\
  \ m=\"2287510\">further</span> <span m=\"2287990\">doublings.</span> <span m=\"\
  2291810\">So</span> <span m=\"2292240\">in</span> <span m=\"2292330\">particular,</span>\
  \ <span m=\"2293710\">if--</span> <span m=\"2294760\">so</span> <span m=\"2296000\"\
  >I'll</span> <span m=\"2296370\">say,</span> <span m=\"2296740\">applications.</span></p><p><span\
  \ m=\"2299790\">So</span> <span m=\"2300120\">suppose</span> <span m=\"2300540\"\
  >you</span> <span m=\"2300660\">knew</span> <span m=\"2303150\">that</span> <span\
  \ m=\"2304010\">2A</span> <span m=\"2304740\">minus</span> <span m=\"2305100\">2A</span>\
  \ <span m=\"2307755\">is</span> <span m=\"2308190\">size,</span> <span m=\"2308670\"\
  >at</span> <span m=\"2308790\">most,</span> <span m=\"2309330\">k</span> <span m=\"\
  2309660\">times</span> <span m=\"2310040\">A.</span> <span m=\"2310440\">So</span>\
  \ <span m=\"2310620\">this</span> <span m=\"2310800\">is</span> <span m=\"2311040\"\
  >a</span> <span m=\"2311490\">stronger</span> <span m=\"2312000\">hypothesis</span>\
  \ <span m=\"2312720\">than</span> <span m=\"2312930\">just</span> <span m=\"2313170\"\
  >A has</span> <span m=\"2313440\">small</span> <span m=\"2313770\">doublings.</span>\
  \ <span m=\"2314790\">Even</span> <span m=\"2315050\">if</span> <span m=\"2315090\"\
  >you</span> <span m=\"2315380\">iterate it</span> <span m=\"2315750\">several</span>\
  \ <span m=\"2316080\">times,</span> <span m=\"2317400\">you</span> <span m=\"2317520\"\
  >still</span> <span m=\"2318900\">have</span> <span m=\"2319110\">size,</span> <span\
  \ m=\"2319590\">at</span> <span m=\"2319960\">most,</span> <span m=\"2320310\">constant</span>\
  \ <span m=\"2320760\">times</span> <span m=\"2321120\">A.</span></p><p><span m=\"\
  2322156\">I</span> <span m=\"2322610\">would</span> <span m=\"2322730\">like</span>\
  \ <span m=\"2322910\">to</span> <span m=\"2323300\">start</span> <span m=\"2323690\"\
  >from</span> <span m=\"2323960\">this</span> <span m=\"2324230\">hypothesis</span>\
  \ <span m=\"2325250\">and</span> <span m=\"2325370\">control</span> <span m=\"2326120\"\
  >further</span> <span m=\"2327260\">iterations,</span> <span m=\"2328130\">further</span>\
  \ <span m=\"2328560\">subsets</span> <span m=\"2329120\">of</span> <span m=\"2329290\"\
  >A.</span> <span m=\"2329815\">And</span> <span m=\"2330230\">Ruzsa's</span> <span\
  \ m=\"2330620\">Triangle</span> <span m=\"2331010\">Inequality</span> <span m=\"\
  2331700\">allows</span> <span m=\"2332090\">us</span> <span m=\"2332330\">to</span>\
  \ <span m=\"2332480\">do</span> <span m=\"2332660\">it,</span> <span m=\"2333472\"\
  >because</span> <span m=\"2333820\">by</span> <span m=\"2334640\">the</span> <span\
  \ m=\"2336590\">Ruzsa's</span> <span m=\"2340370\">Triangle</span> <span m=\"2340820\"\
  >Inequality,</span> <span m=\"2344110\">setting</span> <span m=\"2345100\">B</span>\
  \ <span m=\"2345850\">and</span> <span m=\"2346000\">C</span> <span m=\"2346600\"\
  >to</span> <span m=\"2346750\">be</span> <span m=\"2347560\">2A</span> <span m=\"\
  2348220\">minus</span> <span m=\"2348640\">A,</span> <span m=\"2349630\">we</span>\
  \ <span m=\"2349780\">find</span> <span m=\"2350170\">that</span> <span m=\"2350990\"\
  >3A</span> <span m=\"2351820\">minus</span> <span m=\"2352270\">3A</span> <span\
  \ m=\"2353470\">is,</span> <span m=\"2353620\">at</span> <span m=\"2353710\">most,</span>\
  \ <span m=\"2355090\">2A</span> <span m=\"2355510\">minus</span> <span m=\"2355870\"\
  >2A</span> <span m=\"2357070\">squared</span> <span m=\"2358330\">over</span> <span\
  \ m=\"2359700\">A,</span> <span m=\"2360160\">the</span> <span m=\"2360250\">size</span>\
  \ <span m=\"2360520\">of</span> <span m=\"2360610\">A.</span> <span m=\"2361520\"\
  >So</span> <span m=\"2361930\">plug</span> <span m=\"2362170\">it</span> <span m=\"\
  2362230\">in.</span> <span m=\"2362950\">This</span> <span m=\"2363100\">is</span>\
  \ <span m=\"2363220\">what</span> <span m=\"2363340\">you</span> <span m=\"2363430\"\
  >get.</span></p><p><span m=\"2365680\">So</span> <span m=\"2365980\">if</span> <span\
  \ m=\"2366180\">the</span> <span m=\"2366300\">size</span> <span m=\"2366750\">of</span>\
  \ <span m=\"2366840\">2A</span> <span m=\"2367260\">plus</span> <span m=\"2367500\"\
  >2A</span> <span m=\"2367710\">is,</span> <span m=\"2367920\">at</span> <span m=\"\
  2367990\">most,</span> <span m=\"2368250\">k</span> <span m=\"2368520\">times</span>\
  \ <span m=\"2368760\">the</span> <span m=\"2368820\">size</span> <span m=\"2369120\"\
  >of</span> <span m=\"2369240\">A,</span> <span m=\"2369810\">then</span> <span m=\"\
  2370570\">the</span> <span m=\"2370680\">size of</span> <span m=\"2370990\">3A</span>\
  \ <span m=\"2371430\">times</span> <span m=\"2371760\">3A</span> <span m=\"2372750\"\
  >is--</span> <span m=\"2375500\">blows</span> <span m=\"2375830\">up</span> <span\
  \ m=\"2375950\">by</span> <span m=\"2376040\">a</span> <span m=\"2376120\">factor,</span>\
  \ <span m=\"2376540\">at</span> <span m=\"2376660\">most,</span> <span m=\"2377320\"\
  >k</span> <span m=\"2377590\">squared.</span> <span m=\"2378550\">So it</span> <span\
  \ m=\"2378940\">controls</span> <span m=\"2379450\">further</span> <span m=\"2379840\"\
  >doublings.</span> <span m=\"2380650\">And</span> <span m=\"2380770\">of</span>\
  \ <span m=\"2380860\">course,</span> <span m=\"2381100\">we</span> <span m=\"2381220\"\
  >can</span> <span m=\"2381400\">iterate.</span></p><p><span m=\"2386220\">If</span>\
  \ <span m=\"2386380\">we</span> <span m=\"2386470\">know</span> <span m=\"2386710\"\
  >set</span> <span m=\"2389190\">B</span> <span m=\"2389370\">and</span> <span m=\"\
  2389490\">C to be</span> <span m=\"2390750\">3A</span> <span m=\"2391680\">minus</span>\
  \ <span m=\"2392070\">2A,</span> <span m=\"2393180\">then</span> <span m=\"2393420\"\
  >what</span> <span m=\"2393540\">we</span> <span m=\"2393660\">get</span> <span\
  \ m=\"2394020\">is</span> <span m=\"2394860\">5A</span> <span m=\"2395490\">minus</span>\
  \ <span m=\"2395880\">5A</span> <span m=\"2397380\">is,</span> <span m=\"2397530\"\
  >at</span> <span m=\"2397620\">most,</span> <span m=\"2397890\">a</span> <span m=\"\
  2397920\">size</span> <span m=\"2398250\">of</span> <span m=\"2398310\">3A</span>\
  \ <span m=\"2399120\">minus</span> <span m=\"2399480\">3A</span> <span m=\"2400260\"\
  >square</span> <span m=\"2400890\">divided</span> <span m=\"2401250\">by</span>\
  \ <span m=\"2401400\">the</span> <span m=\"2401490\">size</span> <span m=\"2401790\"\
  >of</span> <span m=\"2401880\">A.</span> <span m=\"2402930\">And</span> <span m=\"\
  2403260\">so</span> <span m=\"2403950\">now</span> <span m=\"2404220\">you</span>\
  \ <span m=\"2404370\">have</span> <span m=\"2404580\">a</span> <span m=\"2404610\"\
  >bound</span> <span m=\"2404940\">which</span> <span m=\"2405150\">is</span> <span\
  \ m=\"2405240\">k</span> <span m=\"2405515\">to</span> <span m=\"2405790\">the</span>\
  \ <span m=\"2405900\">4</span> <span m=\"2406920\">times</span> <span m=\"2407290\"\
  >A.</span> <span m=\"2408760\">And</span> <span m=\"2408890\">you</span> <span m=\"\
  2408980\">can</span> <span m=\"2409100\">continue.</span> <span m=\"2411464\">You\
  \ can continue.</span></p><p><span m=\"2415890\">OK,</span> <span m=\"2416110\"\
  >so</span> <span m=\"2416230\">this</span> <span m=\"2416410\">is</span> <span m=\"\
  2416530\">all</span> <span m=\"2416660\">a</span> <span m=\"2416690\">consequence</span>\
  \ <span m=\"2417190\">of</span> <span m=\"2417420\">Ruzsa's</span> <span m=\"2417490\"\
  >triangle.</span> <span m=\"2417880\">So</span> <span m=\"2418210\">starting</span>\
  \ <span m=\"2418600\">with</span> <span m=\"2418810\">this</span> <span m=\"2418990\"\
  >hypothesis,</span> <span m=\"2419920\">now</span> <span m=\"2420190\">I</span>\
  \ <span m=\"2420280\">get</span> <span m=\"2420460\">to</span> <span m=\"2420520\"\
  >control</span> <span m=\"2421660\">all</span> <span m=\"2421900\">the</span> <span\
  \ m=\"2422380\">further</span> <span m=\"2423190\">doublings,</span> <span m=\"\
  2425160\">the</span> <span m=\"2425440\">further</span> <span m=\"2425840\">subset</span>\
  \ <span m=\"2426250\">iterations.</span> <span m=\"2426850\">I</span> <span m=\"\
  2427210\">call them</span> <span m=\"2427480\">doublings,</span> <span m=\"2427900\"\
  >but</span> <span m=\"2428210\">they're</span> <span m=\"2428920\">no</span> <span\
  \ m=\"2429040\">longer</span> <span m=\"2429280\">doubles,</span> <span m=\"2429620\"\
  >but</span> <span m=\"2430060\">further</span> <span m=\"2430370\">subsets.</span>\
  \ <span m=\"2432580\">But</span> <span m=\"2432760\">this</span> <span m=\"2432940\"\
  >is</span> <span m=\"2433060\">a</span> <span m=\"2433120\">stronger</span> <span\
  \ m=\"2433600\">hypothesis</span> <span m=\"2434290\">than</span> <span m=\"2434380\"\
  >the</span> <span m=\"2434470\">one</span> <span m=\"2434650\">that</span> <span\
  \ m=\"2434770\">we</span> <span m=\"2435040\">start</span> <span m=\"2435370\">with</span>\
  \ <span m=\"2435610\">in</span> <span m=\"2436020\">Freiman's</span> <span m=\"\
  2436570\">theorem,</span> <span m=\"2437790\">because</span> <span m=\"2438610\"\
  >if</span> <span m=\"2438730\">you</span> <span m=\"2438850\">have</span> <span\
  \ m=\"2439000\">that,</span> <span m=\"2439290\">then</span> <span m=\"2440050\"\
  >this</span> <span m=\"2441410\">2A</span> <span m=\"2441710\">minus</span> <span\
  \ m=\"2441980\">2A</span> <span m=\"2442300\">is</span> <span m=\"2442490\">at</span>\
  \ <span m=\"2442670\">least</span> <span m=\"2442940\">as</span> <span m=\"2443090\"\
  >large</span> <span m=\"2443390\">as</span> <span m=\"2443510\">the</span> <span\
  \ m=\"2443570\">size</span> <span m=\"2443870\">of</span> <span m=\"2443960\">2A.</span>\
  \ <span m=\"2445640\">So</span> <span m=\"2446060\">can</span> <span m=\"2446390\"\
  >we</span> <span m=\"2446600\">start</span> <span m=\"2447080\">with</span> <span\
  \ m=\"2447350\">just</span> <span m=\"2448280\">doubling</span> <span m=\"2448670\"\
  >constant</span> <span m=\"2450350\">and</span> <span m=\"2450500\">then</span>\
  \ <span m=\"2450860\">obtain</span> <span m=\"2451520\">bounds</span> <span m=\"\
  2451980\">on</span> <span m=\"2452170\">the</span> <span m=\"2452300\">iterations?</span></p><p><span\
  \ m=\"2455410\">|</span> <span m=\"2455480\">it</span> <span m=\"2455710\">turns</span>\
  \ <span m=\"2455920\">out</span> <span m=\"2456010\">you</span> <span m=\"2456100\"\
  >can.</span> <span m=\"2456960\">It</span> <span m=\"2457430\">will</span> <span\
  \ m=\"2457570\">require</span> <span m=\"2459610\">another</span> <span m=\"2459910\"\
  >theorem.</span> <span m=\"2467130\">So</span> <span m=\"2467420\">this</span> <span\
  \ m=\"2467600\">theorem</span> <span m=\"2467900\">is</span> <span m=\"2468050\"\
  >called</span> <span m=\"2468825\">Plunnecke</span> <span m=\"2469730\">inequality.</span>\
  \ <span m=\"2474070\">But</span> <span m=\"2475060\">actually,</span> <span m=\"\
  2475930\">these</span> <span m=\"2476110\">days,</span> <span m=\"2476320\">in</span>\
  \ <span m=\"2476390\">literature,</span> <span m=\"2476790\">it's</span> <span m=\"\
  2476950\">often</span> <span m=\"2477220\">referred</span> <span m=\"2477490\">to</span>\
  \ <span m=\"2477610\">as</span> <span m=\"2477730\">Plunnecke-Ruzsa</span> <span\
  \ m=\"2478490\">inequality.</span> <span m=\"2481560\">So</span> <span m=\"2481787\"\
  >Plunnecke</span> <span m=\"2482470\">initially</span> <span m=\"2482860\">proved</span>\
  \ <span m=\"2483140\">it.</span> <span m=\"2483330\">But</span> <span m=\"2483730\"\
  >nobody</span> <span m=\"2484030\">understood</span> <span m=\"2484410\">his</span>\
  \ <span m=\"2484540\">proof.</span> <span m=\"2485130\">And</span> <span m=\"2485280\"\
  >Ruzsa</span> <span m=\"2485530\">gave</span> <span m=\"2485710\">a</span> <span\
  \ m=\"2485770\">better</span> <span m=\"2486010\">proof.</span> <span m=\"2486745\"\
  >And</span> <span m=\"2487180\">actually,</span> <span m=\"2487510\">recently,</span>\
  \ <span m=\"2487960\">there</span> <span m=\"2488080\">was</span> <span m=\"2488170\"\
  >an</span> <span m=\"2488260\">even</span> <span m=\"2488500\">better</span> <span\
  \ m=\"2488710\">proof.</span> <span m=\"2489010\">And</span> <span m=\"2489130\"\
  >that's</span> <span m=\"2489280\">the</span> <span m=\"2489370\">one</span> <span\
  \ m=\"2489550\">I</span> <span m=\"2489610\">will</span> <span m=\"2489730\">show</span>\
  \ <span m=\"2489910\">you.</span></p><p><span m=\"2491688\">So</span> <span m=\"\
  2492100\">Plunnecke-Ruzsa</span> <span m=\"2492700\">inequality</span> <span m=\"\
  2493780\">tells</span> <span m=\"2494050\">us</span> <span m=\"2494680\">that</span>\
  \ <span m=\"2496050\">if</span> <span m=\"2498000\">A</span> <span m=\"2498360\"\
  >is</span> <span m=\"2498690\">subset</span> <span m=\"2499470\">of</span> <span\
  \ m=\"2499620\">some</span> <span m=\"2499860\">obedient</span> <span m=\"2500280\"\
  >group,</span> <span m=\"2505680\">and</span> <span m=\"2507962\">has</span> <span\
  \ m=\"2508420\">doubling</span> <span m=\"2508920\">constant,</span> <span m=\"\
  2509460\">at</span> <span m=\"2509730\">most,</span> <span m=\"2511070\">k,</span>\
  \ <span m=\"2514340\">then</span> <span m=\"2516620\">for</span> <span m=\"2516860\"\
  >all</span> <span m=\"2517940\">non-negative</span> <span m=\"2518870\">integers</span>\
  \ <span m=\"2519470\">m</span> <span m=\"2520040\">and n,</span> <span m=\"2523930\"\
  >the</span> <span m=\"2524020\">size</span> <span m=\"2524470\">of</span> <span\
  \ m=\"2525030\">mA</span> <span m=\"2525850\">minus</span> <span m=\"2527520\">nA</span>\
  \ <span m=\"2528820\">is,</span> <span m=\"2529320\">at</span> <span m=\"2529450\"\
  >most,</span> <span m=\"2530440\">k</span> <span m=\"2530830\">to</span> <span m=\"\
  2531040\">the</span> <span m=\"2531490\">m</span> <span m=\"2531880\">plus</span>\
  \ <span m=\"2532240\">n</span> <span m=\"2532990\">times</span> <span m=\"2533530\"\
  >the</span> <span m=\"2533650\">size</span> <span m=\"2534140\">of</span> <span\
  \ m=\"2534400\">A.</span> <span m=\"2537230\">So</span> <span m=\"2537540\">if</span>\
  \ <span m=\"2537690\">you</span> <span m=\"2537810\">have</span> <span m=\"2539250\"\
  >bounded</span> <span m=\"2539710\">doubling,</span> <span m=\"2540710\">then the</span>\
  \ <span m=\"2541070\">further</span> <span m=\"2541610\">iterations,</span> <span\
  \ m=\"2542490\">the</span> <span m=\"2542600\">further</span> <span m=\"2543250\"\
  >subset</span> <span m=\"2543710\">iterations</span> <span m=\"2544730\">are</span>\
  \ <span m=\"2544820\">also</span> <span m=\"2545150\">controlling</span> <span m=\"\
  2545690\">size.</span> <span m=\"2547520\">I</span> <span m=\"2547640\">want</span>\
  \ <span m=\"2547820\">you</span> <span m=\"2547910\">to</span> <span m=\"2548060\"\
  >think</span> <span m=\"2548720\">of</span> <span m=\"2549140\">polynomial</span>\
  \ <span m=\"2549860\">transformations</span> <span m=\"2550820\">in</span> <span\
  \ m=\"2551000\">k</span> <span m=\"2551480\">as</span> <span m=\"2551750\">negligible.</span></p><p><span\
  \ m=\"2553320\">So</span> <span m=\"2553370\">don't</span> <span m=\"2553550\">worry</span>\
  \ <span m=\"2553790\">about</span> <span m=\"2554000\">that</span> <span m=\"2554310\"\
  >we're</span> <span m=\"2554390\">raising</span> <span m=\"2554840\">things</span>\
  \ <span m=\"2555490\">here.</span> <span m=\"2556340\">k</span> <span m=\"2556610\"\
  >is</span> <span m=\"2556700\">constant.</span> <span m=\"2557210\">You</span> <span\
  \ m=\"2557480\">should</span> <span m=\"2557630\">think</span> <span m=\"2557810\"\
  >of</span> <span m=\"2558080\">m and n</span> <span m=\"2558320\">as</span> <span\
  \ m=\"2558770\">constant.</span> <span m=\"2559640\">So</span> <span m=\"2559760\"\
  >I'm</span> <span m=\"2559850\">changing</span> <span m=\"2560210\">k</span> <span\
  \ m=\"2560510\">to</span> <span m=\"2560600\">some</span> <span m=\"2560780\">other</span>\
  \ <span m=\"2560930\">constant.</span> <span m=\"2562015\">And</span> <span m=\"\
  2562500\">in</span> <span m=\"2562600\">fact,</span> <span m=\"2562770\">I'm</span>\
  \ <span m=\"2562820\">only</span> <span m=\"2563000\">changing</span> <span m=\"\
  2563370\">it</span> <span m=\"2563410\">by</span> <span m=\"2563540\">a</span> <span\
  \ m=\"2563600\">polynomial.</span> <span m=\"2564210\">So</span> <span m=\"2564230\"\
  >this</span> <span m=\"2564410\">is,</span> <span m=\"2564640\">like,</span> <span\
  \ m=\"2565010\">almost</span> <span m=\"2565370\">no</span> <span m=\"2565550\"\
  >change</span> <span m=\"2565880\">at</span> <span m=\"2566000\">all.</span> <span\
  \ m=\"2570810\">So</span> <span m=\"2570860\">this</span> <span m=\"2571040\">is</span>\
  \ <span m=\"2571160\">tricky.</span> <span m=\"2572600\">So</span> <span m=\"2572670\"\
  >we'll</span> <span m=\"2572820\">do</span> <span m=\"2573000\">it</span> <span\
  \ m=\"2573960\">after</span> <span m=\"2574290\">a</span> <span m=\"2574320\">short</span>\
  \ <span m=\"2574530\">break.</span></p><p><span m=\"2576210\">All</span> <span m=\"\
  2576690\">right,</span> <span m=\"2577020\">let's</span> <span m=\"2577200\">prove</span>\
  \ <span m=\"2577690\">Plunnecke's</span> <span m=\"2578400\">inequality,</span>\
  \ <span m=\"2579150\">Plunnecke-Ruzsa</span> <span m=\"2579740\">inequality.</span>\
  \ <span m=\"2580290\">So</span> <span m=\"2580710\">the</span> <span m=\"2580800\"\
  >history</span> <span m=\"2581220\">of</span> <span m=\"2581370\">Plunnecke's</span>\
  \ <span m=\"2581730\">inequality</span> <span m=\"2585770\">has</span> <span m=\"\
  2586060\">some</span> <span m=\"2586280\">similarities</span> <span m=\"2587030\"\
  >with</span> <span m=\"2587360\">Freiman's</span> <span m=\"2587840\">theorem.</span>\
  \ <span m=\"2588160\">So</span> <span m=\"2588330\">Plunnecke</span> <span m=\"\
  2588770\">initially</span> <span m=\"2589220\">proved</span> <span m=\"2589470\"\
  >it,</span> <span m=\"2589760\">but</span> <span m=\"2589970\">his</span> <span\
  \ m=\"2590300\">proof</span> <span m=\"2590720\">was</span> <span m=\"2592370\"\
  >hard</span> <span m=\"2592610\">to</span> <span m=\"2592700\">understand</span>\
  \ <span m=\"2593390\">and</span> <span m=\"2593600\">was</span> <span m=\"2593860\"\
  >sort of</span> <span m=\"2594110\">left</span> <span m=\"2594980\">not</span> <span\
  \ m=\"2595220\">understood</span> <span m=\"2595670\">for</span> <span m=\"2595820\"\
  >a</span> <span m=\"2595850\">long</span> <span m=\"2596030\">time</span> <span\
  \ m=\"2596330\">until</span> <span m=\"2597780\">others</span> <span m=\"2598250\"\
  >like</span> <span m=\"2598640\">Plun</span> <span m=\"2599060\">and</span> <span\
  \ m=\"2599390\">Ruzsa</span> <span m=\"2599780\">came</span> <span m=\"2600050\"\
  >in</span> <span m=\"2600230\">and</span> <span m=\"2600380\">really</span> <span\
  \ m=\"2601040\">simplified</span> <span m=\"2601570\">the</span> <span m=\"2601650\"\
  >proof.</span></p><p><span m=\"2602690\">But</span> <span m=\"2602840\">even</span>\
  \ <span m=\"2603050\">then,</span> <span m=\"2603890\">the</span> <span m=\"2604070\"\
  >proof</span> <span m=\"2604370\">was</span> <span m=\"2605030\">not</span> <span\
  \ m=\"2605270\">so</span> <span m=\"2605450\">easy.</span> <span m=\"2606320\">And</span>\
  \ <span m=\"2607370\">if</span> <span m=\"2607520\">I</span> <span m=\"2607610\"\
  >were</span> <span m=\"2607730\">teaching</span> <span m=\"2608030\">this</span>\
  \ <span m=\"2608210\">course</span> <span m=\"2608630\">about</span> <span m=\"\
  2609380\">10</span> <span m=\"2609590\">years</span> <span m=\"2609770\">ago,</span>\
  \ <span m=\"2610260\">I</span> <span m=\"2610280\">would</span> <span m=\"2610410\"\
  >have</span> <span m=\"2610550\">just</span> <span m=\"2610970\">skipped</span>\
  \ <span m=\"2611300\">this</span> <span m=\"2611480\">proof,</span> <span m=\"2611910\"\
  >maybe</span> <span m=\"2612150\">sketched</span> <span m=\"2612440\">some</span>\
  \ <span m=\"2612620\">ideas,</span> <span m=\"2612980\">but</span> <span m=\"2613130\"\
  >I</span> <span m=\"2613190\">would</span> <span m=\"2613310\">have</span> <span\
  \ m=\"2613430\">skipped</span> <span m=\"2613720\">the</span> <span m=\"2613760\"\
  >proof.</span> <span m=\"2614330\">And</span> <span m=\"2614450\">the</span> <span\
  \ m=\"2614540\">proof,</span> <span m=\"2614810\">actually,</span> <span m=\"2615850\"\
  >it's</span> <span m=\"2616010\">a</span> <span m=\"2616040\">beautiful</span> <span\
  \ m=\"2616430\">proof, but</span> <span m=\"2616760\">it</span> <span m=\"2616850\"\
  >uses</span> <span m=\"2617090\">some</span> <span m=\"2618110\">serious</span>\
  \ <span m=\"2618560\">graph theory.</span> <span m=\"2618860\">It</span> <span m=\"\
  2619040\">uses</span> <span m=\"2619460\">Menger's</span> <span m=\"2619910\">theorem</span>\
  \ <span m=\"2620870\">about</span> <span m=\"2621150\">flows.</span> <span m=\"\
  2621700\">You</span> <span m=\"2621770\">construct</span> <span m=\"2622190\">some</span>\
  \ <span m=\"2622340\">graph.</span> <span m=\"2622700\">And</span> <span m=\"2622790\"\
  >then</span> <span m=\"2622940\">you</span> <span m=\"2623090\">try</span> <span\
  \ m=\"2623270\">to</span> <span m=\"2623330\">understand</span> <span m=\"2623730\"\
  >its</span> <span m=\"2623860\">flows.</span> <span m=\"2625240\">It's</span> <span\
  \ m=\"2625400\">very</span> <span m=\"2625550\">pretty</span> <span m=\"2625820\"\
  >stuff.</span> <span m=\"2626090\">And</span> <span m=\"2626210\">I</span> <span\
  \ m=\"2626720\">do</span> <span m=\"2626870\">encourage</span> <span m=\"2627230\"\
  >you</span> <span m=\"2627350\">to</span> <span m=\"2628310\">look</span> <span\
  \ m=\"2628490\">it</span> <span m=\"2628580\">up.</span></p><p><span m=\"2630170\"\
  >And</span> <span m=\"2630260\">then</span> <span m=\"2630680\">about</span> <span\
  \ m=\"2631610\">eight</span> <span m=\"2631760\">years</span> <span m=\"2631970\"\
  >ago,</span> <span m=\"2632630\">Petridis</span> <span m=\"2633560\">found</span>\
  \ <span m=\"2634190\">a</span> <span m=\"2634280\">proof,</span> <span m=\"2636260\"\
  >so a</span> <span m=\"2637250\">proof</span> <span m=\"2639340\">by</span> <span\
  \ m=\"2641230\">Petridis,</span> <span m=\"2643290\">who</span> <span m=\"2643550\"\
  >was</span> <span m=\"2643680\">a</span> <span m=\"2643930\">PhD</span> <span m=\"\
  2644410\">student</span> <span m=\"2644730\">that</span> <span m=\"2644810\">Tim</span>\
  \ <span m=\"2644980\">Gowers</span> <span m=\"2645370\">at</span> <span m=\"2645470\"\
  >the</span> <span m=\"2645520\">time.</span> <span m=\"2646450\">And</span> <span\
  \ m=\"2646780\">that</span> <span m=\"2646990\">was</span> <span m=\"2647860\">surprisingly</span>\
  \ <span m=\"2648850\">short,</span> <span m=\"2649630\">and</span> <span m=\"2649750\"\
  >beautiful,</span> <span m=\"2650200\">and</span> <span m=\"2650440\">kind</span>\
  \ <span m=\"2650650\">of</span> <span m=\"2650710\">surprised</span> <span m=\"\
  2651190\">everyone</span> <span m=\"2651580\">that</span> <span m=\"2652090\">such</span>\
  \ <span m=\"2652300\">a</span> <span m=\"2652360\">short</span> <span m=\"2652600\"\
  >proof</span> <span m=\"2652900\">exists,</span> <span m=\"2653650\">given</span>\
  \ <span m=\"2653950\">that</span> <span m=\"2654130\">this</span> <span m=\"2654660\"\
  >theorem</span> <span m=\"2655115\">sat</span> <span m=\"2655470\">in</span> <span\
  \ m=\"2655780\">that</span> <span m=\"2655920\">state</span> <span m=\"2656200\"\
  >for</span> <span m=\"2656320\">such</span> <span m=\"2656530\">a</span> <span m=\"\
  2656590\">long</span> <span m=\"2656800\">time.</span> <span m=\"2657450\">And</span>\
  \ <span m=\"2658500\">it's</span> <span m=\"2658630\">a</span> <span m=\"2658690\"\
  >pretty</span> <span m=\"2658930\">central</span> <span m=\"2659350\">step</span>\
  \ <span m=\"2659890\">in</span> <span m=\"2660020\">the</span> <span m=\"2660070\"\
  >proof</span> <span m=\"2660340\">of</span> <span m=\"2660400\">Freiman's</span>\
  \ <span m=\"2660860\">theorem.</span></p><p><span m=\"2663500\">We'll</span> <span\
  \ m=\"2663610\">prove</span> <span m=\"2664540\">Plunnecke-Ruzsa</span> <span m=\"\
  2665720\">via</span> <span m=\"2666030\">a</span> <span m=\"2666580\">slightly</span>\
  \ <span m=\"2667060\">more</span> <span m=\"2667210\">general</span> <span m=\"\
  2667600\">statement.</span> <span m=\"2668690\">So</span> <span m=\"2668830\">you</span>\
  \ <span m=\"2668920\">see,</span> <span m=\"2669130\">it</span> <span m=\"2669710\"\
  >generalizes</span> <span m=\"2670960\">the</span> <span m=\"2671080\">earlier</span>\
  \ <span m=\"2671410\">statement.</span> <span m=\"2672430\">Instead</span> <span\
  \ m=\"2672730\">of</span> <span m=\"2672820\">having</span> <span m=\"2673060\"\
  >one</span> <span m=\"2673330\">set,</span> <span m=\"2673630\">it</span> <span\
  \ m=\"2673720\">will</span> <span m=\"2673810\">be</span> <span m=\"2673930\">convenient</span>\
  \ <span m=\"2674710\">to</span> <span m=\"2674860\">have</span> <span m=\"2675460\"\
  >two</span> <span m=\"2675700\">different</span> <span m=\"2676060\">sets.</span>\
  \ <span m=\"2676930\">So</span> <span m=\"2677140\">let</span> <span m=\"2679030\"\
  >A</span> <span m=\"2679645\">and</span> <span m=\"2679900\">B</span> <span m=\"\
  2681070\">be</span> <span m=\"2681880\">subsets</span> <span m=\"2684730\">of</span>\
  \ <span m=\"2685000\">some</span> <span m=\"2685210\">obedient</span> <span m=\"\
  2685570\">group,</span> <span m=\"2685930\">as</span> <span m=\"2686080\">usual.</span></p><p><span\
  \ m=\"2690350\">If</span> <span m=\"2691600\">size</span> <span m=\"2692020\">of</span>\
  \ <span m=\"2692170\">A</span> <span m=\"2692590\">plus</span> <span m=\"2693010\"\
  >B</span> <span m=\"2693820\">is,</span> <span m=\"2693980\">at</span> <span m=\"\
  2694090\">most,</span> <span m=\"2696600\">k</span> <span m=\"2696900\">times</span>\
  \ <span m=\"2697200\">the</span> <span m=\"2697260\">size</span> <span m=\"2697590\"\
  >of</span> <span m=\"2697680\">A,</span> <span m=\"2699490\">then</span> <span m=\"\
  2702550\">mB</span> <span m=\"2704650\">minus</span> <span m=\"2706060\">nB</span>\
  \ <span m=\"2707180\">has</span> <span m=\"2707640\">size,</span> <span m=\"2708060\"\
  >at</span> <span m=\"2708160\">most,</span> <span m=\"2708490\">k</span> <span m=\"\
  2709330\">to</span> <span m=\"2709510\">the</span> <span m=\"2709900\">m</span>\
  \ <span m=\"2710140\">plus</span> <span m=\"2710530\">n</span> <span m=\"2712150\"\
  >times</span> <span m=\"2712570\">the</span> <span m=\"2712660\">size</span> <span\
  \ m=\"2713050\">of</span> <span m=\"2713140\">A</span> <span m=\"2713650\">for</span>\
  \ <span m=\"2713920\">all</span> <span m=\"2714670\">non-negative</span> <span m=\"\
  2715300\">integers</span> <span m=\"2716310\">m and</span> <span m=\"2716690\">n.</span>\
  \ <span m=\"2719040\">So</span> <span m=\"2719270\">instead</span> <span m=\"2719570\"\
  >of</span> <span m=\"2719630\">having</span> <span m=\"2719870\">one</span> <span\
  \ m=\"2720110\">set, so</span> <span m=\"2720470\">I</span> <span m=\"2720530\"\
  >have</span> <span m=\"2720710\">two</span> <span m=\"2720890\">sets, A</span> <span\
  \ m=\"2721250\">and</span> <span m=\"2721520\">B.</span> <span m=\"2721980\">Of</span>\
  \ <span m=\"2722260\">course,</span> <span m=\"2722510\">then</span> <span m=\"\
  2722660\">you</span> <span m=\"2723230\">derive</span> <span m=\"2723620\">the</span>\
  \ <span m=\"2723710\">earlier</span> <span m=\"2724040\">statement</span> <span\
  \ m=\"2724580\">setting</span> <span m=\"2725030\">A and</span> <span m=\"2725270\"\
  >B</span> <span m=\"2725450\">to</span> <span m=\"2725600\">equal.</span> <span\
  \ m=\"2727040\">So</span> <span m=\"2727260\">we'll</span> <span m=\"2727360\">prove</span>\
  \ <span m=\"2727600\">this</span> <span m=\"2727810\">more</span> <span m=\"2727990\"\
  >general</span> <span m=\"2728350\">statement.</span></p><p><span m=\"2734640\"\
  >The</span> <span m=\"2735150\">proof</span> <span m=\"2736180\">uses</span> <span\
  \ m=\"2736620\">a</span> <span m=\"2736770\">key</span> <span m=\"2737070\">lemma.</span>\
  \ <span m=\"2740390\">And</span> <span m=\"2740550\">the</span> <span m=\"2740640\"\
  >key</span> <span m=\"2740820\">lemma</span> <span m=\"2741100\">says</span> <span\
  \ m=\"2741990\">that</span> <span m=\"2743100\">if</span> <span m=\"2747480\">a</span>\
  \ <span m=\"2747540\">subset</span> <span m=\"2748230\">x</span> <span m=\"2748620\"\
  >of</span> <span m=\"2748770\">A</span> <span m=\"2749790\">is</span> <span m=\"\
  2750420\">non-empty</span> <span m=\"2754330\">and--</span> <span m=\"2755430\"\
  >so</span> <span m=\"2760150\">if</span> <span m=\"2760270\">x</span> <span m=\"\
  2760690\">is</span> <span m=\"2761170\">a</span> <span m=\"2761350\">non-empty</span>\
  \ <span m=\"2762100\">subset</span> <span m=\"2764850\">of</span> <span m=\"2765060\"\
  >A</span> <span m=\"2765720\">that</span> <span m=\"2766290\">minimizes</span> <span\
  \ m=\"2770810\">the</span> <span m=\"2770930\">ratio</span> <span m=\"2772730\"\
  >x</span> <span m=\"2773060\">plus</span> <span m=\"2773480\">B</span> <span m=\"\
  2774590\">divided</span> <span m=\"2775010\">by</span> <span m=\"2776900\">size</span>\
  \ <span m=\"2777230\">of</span> <span m=\"2777380\">x,</span> <span m=\"2781500\"\
  >and</span> <span m=\"2782810\">let</span> <span m=\"2783030\">k</span> <span m=\"\
  2783360\">prime</span> <span m=\"2784920\">be</span> <span m=\"2786120\">this</span>\
  \ <span m=\"2786360\">ratio,</span> <span m=\"2787700\">this</span> <span m=\"2787890\"\
  >minimum</span> <span m=\"2788700\">ratio,</span> <span m=\"2792160\">then</span>\
  \ <span m=\"2792440\">so</span> <span m=\"2792870\">the</span> <span m=\"2792930\"\
  >conclusion</span> <span m=\"2793440\">says</span> <span m=\"2793950\">that</span>\
  \ <span m=\"2796350\">x</span> <span m=\"2796980\">plus</span> <span m=\"2797730\"\
  >B</span> <span m=\"2798570\">plus</span> <span m=\"2799110\">C</span> <span m=\"\
  2800780\">has</span> <span m=\"2801200\">size,</span> <span m=\"2801720\">at</span>\
  \ <span m=\"2802020\">most,</span> <span m=\"2803160\">k</span> <span m=\"2803460\"\
  >prime</span> <span m=\"2805110\">times</span> <span m=\"2805530\">the</span> <span\
  \ m=\"2805620\">size</span> <span m=\"2806010\">of</span> <span m=\"2806220\">x</span>\
  \ <span m=\"2806520\">plus</span> <span m=\"2806820\">C</span> <span m=\"2807600\"\
  >for</span> <span m=\"2807840\">all</span> <span m=\"2808200\">sets</span> <span\
  \ m=\"2810480\">C.</span></p><p><span m=\"2813230\">So</span> <span m=\"2813720\"\
  >that's</span> <span m=\"2813940\">the</span> <span m=\"2814030\">statement.</span>\
  \ <span m=\"2814510\">I'll</span> <span m=\"2814660\">explain</span> <span m=\"\
  2815680\">how</span> <span m=\"2815920\">you</span> <span m=\"2816010\">should</span>\
  \ <span m=\"2816160\">think</span> <span m=\"2816370\">about</span> <span m=\"2816580\"\
  >the</span> <span m=\"2816700\">statement.</span> <span m=\"2820770\">These</span>\
  \ <span m=\"2821010\">ratios</span> <span m=\"2821730\">which</span> <span m=\"\
  2821970\">you</span> <span m=\"2822240\">see</span> <span m=\"2822720\">in</span>\
  \ <span m=\"2823650\">both</span> <span m=\"2823890\">hypotheses,</span> <span m=\"\
  2825420\">how</span> <span m=\"2825660\">you</span> <span m=\"2825740\">should</span>\
  \ <span m=\"2825900\">think</span> <span m=\"2826080\">about</span> <span m=\"2826320\"\
  >them</span> <span m=\"2826890\">is</span> <span m=\"2827100\">that</span> <span\
  \ m=\"2827640\">there</span> <span m=\"2827820\">is</span> <span m=\"2827940\">this</span>\
  \ <span m=\"2828150\">graph.</span></p><p><span m=\"2830210\">Let's</span> <span\
  \ m=\"2830400\">say it's</span> <span m=\"2831840\">the</span> <span m=\"2831960\"\
  >group</span> <span m=\"2832770\">bipartite</span> <span m=\"2833280\">graph</span>\
  \ <span m=\"2834420\">with</span> <span m=\"2834570\">the</span> <span m=\"2834630\"\
  >group</span> <span m=\"2834840\">elements</span> <span m=\"2835290\">on</span>\
  \ <span m=\"2835470\">both</span> <span m=\"2835710\">sides.</span> <span m=\"2837070\"\
  >And</span> <span m=\"2837210\">the</span> <span m=\"2837300\">graph</span> <span\
  \ m=\"2839370\">has</span> <span m=\"2840030\">edges,</span> <span m=\"2840460\"\
  >the</span> <span m=\"2840890\">bipartite</span> <span m=\"2841190\">graph,</span>\
  \ <span m=\"2842430\">where</span> <span m=\"2842580\">the</span> <span m=\"2842730\"\
  >edges</span> <span m=\"2844590\">are</span> <span m=\"2847110\">from</span> <span\
  \ m=\"2847410\">each</span> <span m=\"2847710\">vertex</span> <span m=\"2848670\"\
  >a</span> <span m=\"2849700\">drawn</span> <span m=\"2850180\">edge</span> <span\
  \ m=\"2850500\">for</span> <span m=\"2850740\">each</span> <span m=\"2851040\">element</span>\
  \ <span m=\"2851490\">of</span> <span m=\"2851610\">B.</span> <span m=\"2852180\"\
  >So</span> <span m=\"2852340\">I</span> <span m=\"2852450\">expand</span> <span\
  \ m=\"2853170\">by</span> <span m=\"2853460\">B.</span></p><p><span m=\"2855400\"\
  >So</span> <span m=\"2855550\">if</span> <span m=\"2855700\">you</span> <span m=\"\
  2855790\">have</span> <span m=\"2856030\">this</span> <span m=\"2856240\">graph</span>\
  \ <span m=\"2857650\">and</span> <span m=\"2857800\">you</span> <span m=\"2857920\"\
  >start</span> <span m=\"2858340\">with</span> <span m=\"2859090\">some</span> <span\
  \ m=\"2861380\">A</span> <span m=\"2862040\">on</span> <span m=\"2862160\">the</span>\
  \ <span m=\"2862250\">left,</span> <span m=\"2862940\">then</span> <span m=\"2863690\"\
  >its</span> <span m=\"2863900\">neighbors</span> <span m=\"2864620\">on</span> <span\
  \ m=\"2864770\">the</span> <span m=\"2864830\">right</span> <span m=\"2865280\"\
  >will</span> <span m=\"2865460\">be</span> <span m=\"2866150\">A</span> <span m=\"\
  2867200\">plus</span> <span m=\"2867590\">B.</span> <span m=\"2874075\">And</span>\
  \ <span m=\"2874810\">those</span> <span m=\"2875110\">ratios</span> <span m=\"\
  2875770\">up</span> <span m=\"2875950\">there</span> <span m=\"2876910\">are</span>\
  \ <span m=\"2877120\">the</span> <span m=\"2877330\">expansion</span> <span m=\"\
  2878080\">ratios.</span> <span m=\"2879790\">so</span> <span m=\"2880640\">quantities</span>\
  \ <span m=\"2881140\">like</span> <span m=\"2884150\">this,</span> <span m=\"2884660\"\
  >they</span> <span m=\"2884810\">are</span> <span m=\"2884930\">expansion</span>\
  \ <span m=\"2885650\">ratios.</span> <span m=\"2888520\">You</span> <span m=\"2888670\"\
  >start</span> <span m=\"2889030\">with</span> <span m=\"2889240\">some</span> <span\
  \ m=\"2889540\">set</span> <span m=\"2889870\">on</span> <span m=\"2890050\">the</span>\
  \ <span m=\"2890140\">left</span> <span m=\"2891070\">and</span> <span m=\"2891190\"\
  >see</span> <span m=\"2891460\">by</span> <span m=\"2891690\">a</span> <span m=\"\
  2891730\">what</span> <span m=\"2891940\">fraction</span> <span m=\"2892510\">does</span>\
  \ <span m=\"2892720\">it</span> <span m=\"2892810\">expand</span> <span m=\"2893650\"\
  >if</span> <span m=\"2893800\">you</span> <span m=\"2893890\">look</span> <span\
  \ m=\"2894070\">at</span> <span m=\"2894160\">the</span> <span m=\"2894250\">neighborhood.</span></p><p><span\
  \ m=\"2896730\">So</span> <span m=\"2896860\">let's</span> <span m=\"2897100\">read</span>\
  \ <span m=\"2897610\">the</span> <span m=\"2897730\">statement</span> <span m=\"\
  2898270\">of</span> <span m=\"2898390\">the</span> <span m=\"2898450\">key</span>\
  \ <span m=\"2898690\">lemma.</span> <span m=\"2900010\">It</span> <span m=\"2900100\"\
  >says,</span> <span m=\"2900340\">if</span> <span m=\"2900460\">you</span> <span\
  \ m=\"2900580\">have</span> <span m=\"2900820\">a</span> <span m=\"2900880\">set</span>\
  \ <span m=\"2901240\">x--</span> <span m=\"2903630\">I</span> <span m=\"2903830\"\
  >look,</span> <span m=\"2904110\">so</span> <span m=\"2904210\">I</span> <span m=\"\
  2904310\">have</span> <span m=\"2904410\">a</span> <span m=\"2904510\">set A.</span>\
  \ <span m=\"2904640\">And</span> <span m=\"2905300\">I'm</span> <span m=\"2905420\"\
  >choosing</span> <span m=\"2906230\">a</span> <span m=\"2906320\">subset</span>\
  \ <span m=\"2907400\">of</span> <span m=\"2908050\">A</span> <span m=\"2908870\"\
  >that</span> <span m=\"2909110\">minimizes</span> <span m=\"2910100\">the</span>\
  \ <span m=\"2910220\">expansion</span> <span m=\"2910910\">ratio,</span> <span m=\"\
  2911420\">so</span> <span m=\"2911840\">choose</span> <span m=\"2912200\">a</span>\
  \ <span m=\"2912270\">non-empty</span> <span m=\"2912800\">subset</span> <span m=\"\
  2913170\">that</span> <span m=\"2913260\">minimizes</span> <span m=\"2913970\">the</span>\
  \ <span m=\"2914090\">expansion</span> <span m=\"2914630\">ratio.</span> <span m=\"\
  2916080\">And if</span> <span m=\"2916550\">this</span> <span m=\"2916790\">minimum</span>\
  \ <span m=\"2917240\">expense</span> <span m=\"2917730\">ratio</span> <span m=\"\
  2918200\">is</span> <span m=\"2918380\">k</span> <span m=\"2918590\">prime,</span>\
  \ <span m=\"2920520\">then,</span> <span m=\"2921950\">so</span> <span m=\"2923670\"\
  >x</span> <span m=\"2925350\">minimizes</span> <span m=\"2926370\">expansion</span>\
  \ <span m=\"2927600\">ratio</span> <span m=\"2930790\">and</span> <span m=\"2931750\"\
  >expense</span> <span m=\"2932080\">ratios</span> <span m=\"2932460\">k</span> <span\
  \ m=\"2932660\">prime,</span> <span m=\"2933550\">then</span> <span m=\"2934600\"\
  >x</span> <span m=\"2935020\">plus</span> <span m=\"2935260\">C</span> <span m=\"\
  2935920\">also</span> <span m=\"2936250\">has</span> <span m=\"2939010\">expansion</span>\
  \ <span m=\"2939550\">ratio,</span> <span m=\"2942425\">at</span> <span m=\"2942900\"\
  >most,</span> <span m=\"2944190\">k</span> <span m=\"2944400\">prime</span> <span\
  \ m=\"2944910\">as</span> <span m=\"2945040\">well.</span></p><p><span m=\"2948560\"\
  >So</span> <span m=\"2948580\">that's</span> <span m=\"2948790\">the</span> <span\
  \ m=\"2948880\">statement.</span> <span m=\"2952480\">I</span> <span m=\"2952570\"\
  >mentioned</span> <span m=\"2952840\">earlier</span> <span m=\"2953110\">that</span>\
  \ <span m=\"2953260\">the</span> <span m=\"2953470\">previous</span> <span m=\"\
  2954040\">proofs</span> <span m=\"2954370\">of</span> <span m=\"2954460\">this</span>\
  \ <span m=\"2954640\">theorem</span> <span m=\"2955060\">went</span> <span m=\"\
  2955300\">through</span> <span m=\"2955480\">some</span> <span m=\"2955630\">graph</span>\
  \ <span m=\"2955960\">theory</span> <span m=\"2957220\">and</span> <span m=\"2958060\"\
  >Menger's</span> <span m=\"2958510\">theorem,</span> <span m=\"2958750\">that</span>\
  \ <span m=\"2958900\">type</span> <span m=\"2959080\">of</span> <span m=\"2959200\"\
  >graph</span> <span m=\"2959440\">theory.</span> <span m=\"2960530\">You</span>\
  \ <span m=\"2960740\">can</span> <span m=\"2961060\">kind</span> <span m=\"2961300\"\
  >of</span> <span m=\"2961390\">see</span> <span m=\"2961630\">where</span> <span\
  \ m=\"2962740\">it</span> <span m=\"2962830\">might</span> <span m=\"2963010\">come</span>\
  \ <span m=\"2963220\">in.</span></p><p><span m=\"2964110\">We're</span> <span m=\"\
  2964240\">not</span> <span m=\"2964340\">going</span> <span m=\"2964430\">to</span>\
  \ <span m=\"2964500\">do</span> <span m=\"2964600\">that.</span> <span m=\"2964820\"\
  >We're</span> <span m=\"2964920\">going</span> <span m=\"2965020\">to</span> <span\
  \ m=\"2965120\">stick</span> <span m=\"2965230\">with</span> <span m=\"2965380\"\
  >additive</span> <span m=\"2965790\">combinatorics.</span> <span m=\"2966100\">We're\
  \ going</span> <span m=\"2966180\">to</span> <span m=\"2966280\">stick</span> <span\
  \ m=\"2966550\">with</span> <span m=\"2967840\">playing</span> <span m=\"2968110\"\
  >with</span> <span m=\"2968290\">sums,</span> <span m=\"2968620\">playing</span>\
  \ <span m=\"2968950\">with</span> <span m=\"2969100\">additive</span> <span m=\"\
  2969430\">combinatorics.</span> <span m=\"2970870\">So</span> <span m=\"2971020\"\
  >let's</span> <span m=\"2971170\">see</span> <span m=\"2971380\">how</span> <span\
  \ m=\"2971620\">we</span> <span m=\"2971740\">can</span> <span m=\"2971920\">prove</span>\
  \ <span m=\"2972610\">the</span> <span m=\"2973270\">statement</span> <span m=\"\
  2973750\">up</span> <span m=\"2973900\">there,</span> <span m=\"2974390\">so</span>\
  \ <span m=\"2974740\">using</span> <span m=\"2975070\">the</span> <span m=\"2975160\"\
  >key</span> <span m=\"2975350\">lemma.</span></p><p><span m=\"2979960\">So</span>\
  \ <span m=\"2980530\">assuming</span> <span m=\"2981100\">key</span> <span m=\"\
  2981280\">lemma,</span> <span m=\"2985650\">so</span> <span m=\"2985800\">let's</span>\
  \ <span m=\"2986040\">prove</span> <span m=\"2986970\">the</span> <span m=\"2987120\"\
  >statement,</span> <span m=\"2990580\">the</span> <span m=\"2990890\">theorem</span>\
  \ <span m=\"2991340\">up</span> <span m=\"2991490\">there.</span> <span m=\"2992610\"\
  >So</span> <span m=\"2992710\">take</span> <span m=\"2994810\">a</span> <span m=\"\
  2994940\">non-empty</span> <span m=\"2998580\">subset</span> <span m=\"2999180\"\
  >x</span> <span m=\"2999720\">of</span> <span m=\"2999990\">A--</span> <span m=\"\
  3001520\">sorry, so</span> <span m=\"3001950\">x</span> <span m=\"3002810\">subset</span>\
  \ <span m=\"3003230\">of</span> <span m=\"3003320\">A</span> <span m=\"3005070\"\
  >that</span> <span m=\"3005450\">minimizes</span> <span m=\"3008480\">the</span>\
  \ <span m=\"3008610\">ratio</span> <span m=\"3010930\">x</span> <span m=\"3011470\"\
  >plus</span> <span m=\"3011890\">B</span> <span m=\"3012640\">divided</span> <span\
  \ m=\"3013090\">by</span> <span m=\"3014830\">x.</span> <span m=\"3016600\">And</span>\
  \ <span m=\"3017230\">let</span> <span m=\"3018040\">k</span> <span m=\"3018280\"\
  >prime</span> <span m=\"3018800\">be</span> <span m=\"3019030\">this</span> <span\
  \ m=\"3019270\">minimum</span> <span m=\"3019690\">ratio.</span></p><p><span m=\"\
  3025710\">Note</span> <span m=\"3026070\">that</span> <span m=\"3027180\">k</span>\
  \ <span m=\"3027390\">prime</span> <span m=\"3027930\">is,</span> <span m=\"3028530\"\
  >at</span> <span m=\"3028650\">most,</span> <span m=\"3028980\">k,</span> <span\
  \ m=\"3030390\">because if</span> <span m=\"3030810\">you</span> <span m=\"3031080\"\
  >plug in</span> <span m=\"3031770\">x</span> <span m=\"3032040\">equals</span> <span\
  \ m=\"3032390\">the</span> <span m=\"3032490\">k,</span> <span m=\"3032910\">you</span>\
  \ <span m=\"3033030\">get--</span> <span m=\"3033810\">if</span> <span m=\"3033930\"\
  >you</span> <span m=\"3034020\">plug in</span> <span m=\"3034410\">x</span> <span\
  \ m=\"3034680\">equals</span> <span m=\"3034950\">to</span> <span m=\"3035070\"\
  >A,</span> <span m=\"3035370\">you</span> <span m=\"3035710\">get</span> <span m=\"\
  3035820\">k.</span> <span m=\"3036980\">But</span> <span m=\"3037290\">I'm</span>\
  \ <span m=\"3037410\">choosing</span> <span m=\"3038460\">x</span> <span m=\"3038790\"\
  >to</span> <span m=\"3039030\">be</span> <span m=\"3039540\">possibly</span> <span\
  \ m=\"3040020\">even</span> <span m=\"3040290\">lower.</span> <span m=\"3040870\"\
  >So</span> <span m=\"3040950\">k</span> <span m=\"3041190\">prime</span> <span m=\"\
  3041620\">is,</span> <span m=\"3041730\">at</span> <span m=\"3041940\">most,</span>\
  \ <span m=\"3042240\">k.</span></p><p><span m=\"3050738\">Now,</span> <span m=\"\
  3052200\">applying</span> <span m=\"3052680\">the</span> <span m=\"3052800\">lemma,</span>\
  \ <span m=\"3055810\">so</span> <span m=\"3056080\">applying</span> <span m=\"3058190\"\
  >the</span> <span m=\"3058290\">key</span> <span m=\"3058530\">lemma</span> <span\
  \ m=\"3062670\">with</span> <span m=\"3062940\">C</span> <span m=\"3063980\">equals</span>\
  \ <span m=\"3064410\">to</span> <span m=\"3064530\">B,</span> <span m=\"3065610\"\
  >we</span> <span m=\"3065830\">find</span> <span m=\"3066660\">that</span> <span\
  \ m=\"3067020\">x</span> <span m=\"3068070\">plus</span> <span m=\"3068920\">2B,</span>\
  \ <span m=\"3071554\">so</span> <span m=\"3072050\">C,</span> <span m=\"3072500\"\
  >plug in</span> <span m=\"3073230\">B,</span> <span m=\"3074294\">x</span> <span\
  \ m=\"3075090\">plus</span> <span m=\"3075390\">2B</span> <span m=\"3076370\">has</span>\
  \ <span m=\"3076440\">size,</span> <span m=\"3076880\">at</span> <span m=\"3076970\"\
  >most,</span> <span m=\"3077700\">k</span> <span m=\"3078090\">times</span> <span\
  \ m=\"3079290\">size</span> <span m=\"3079680\">of</span> <span m=\"3079800\">x</span>\
  \ <span m=\"3080430\">plus</span> <span m=\"3080790\">B.</span> <span m=\"3083780\"\
  >But</span> <span m=\"3084020\">the</span> <span m=\"3084140\">size</span> <span\
  \ m=\"3084470\">of</span> <span m=\"3084590\">x</span> <span m=\"3084860\">plus</span>\
  \ <span m=\"3085190\">B</span> <span m=\"3085460\">is,</span> <span m=\"3085630\"\
  >at</span> <span m=\"3085700\">most,</span> <span m=\"3086630\">k</span> <span m=\"\
  3086910\">times</span> <span m=\"3087230\">the</span> <span m=\"3087290\">size</span>\
  \ <span m=\"3087590\">of</span> <span m=\"3087710\">A.</span> <span m=\"3088490\"\
  >So</span> <span m=\"3089420\">we</span> <span m=\"3089510\">get</span> <span m=\"\
  3089990\">k</span> <span m=\"3090260\">squared,</span> <span m=\"3092620\">so</span>\
  \ <span m=\"3093030\">k</span> <span m=\"3093390\">times the</span> <span m=\"3093810\"\
  >size</span> <span m=\"3094110\">of</span> <span m=\"3094210\">x,</span> <span m=\"\
  3094480\">at</span> <span m=\"3094890\">most,</span> <span m=\"3095160\">k</span>\
  \ <span m=\"3095430\">squared</span> <span m=\"3095790\">x.</span> <span m=\"3097860\"\
  >So</span> <span m=\"3098250\">we're</span> <span m=\"3098850\">already</span> <span\
  \ m=\"3099390\">in</span> <span m=\"3099660\">good</span> <span m=\"3099870\">shape.</span></p><p><span\
  \ m=\"3101430\">If</span> <span m=\"3101580\">you</span> <span m=\"3101970\">iterate</span>\
  \ <span m=\"3102990\">expansion</span> <span m=\"3103590\">twice--</span> <span\
  \ m=\"3104070\">so</span> <span m=\"3104220\">I</span> <span m=\"3104240\">imagine</span>\
  \ <span m=\"3104670\">there is</span> <span m=\"3105330\">several</span> <span m=\"\
  3105720\">chains</span> <span m=\"3106170\">of</span> <span m=\"3106290\">these</span>\
  \ <span m=\"3106460\">bipartite</span> <span m=\"3106850\">graphs.</span> <span\
  \ m=\"3107976\">If you</span> <span m=\"3108390\">iterate</span> <span m=\"3109140\"\
  >this</span> <span m=\"3109320\">expansion</span> <span m=\"3109800\">twice,</span>\
  \ <span m=\"3110250\">you</span> <span m=\"3110370\">still</span> <span m=\"3111000\"\
  >do</span> <span m=\"3111150\">not</span> <span m=\"3111330\">blow</span> <span\
  \ m=\"3111570\">up</span> <span m=\"3111750\">by</span> <span m=\"3111930\">too</span>\
  \ <span m=\"3112110\">much.</span> <span m=\"3114970\">So</span> <span m=\"3114990\"\
  >we</span> <span m=\"3115110\">can</span> <span m=\"3115260\">iterate</span> <span\
  \ m=\"3115650\">further,</span> <span m=\"3117150\">so</span> <span m=\"3117780\"\
  >apply</span> <span m=\"3118100\">the</span> <span m=\"3118420\">lemma with</span>\
  \ <span m=\"3118800\">C</span> <span m=\"3119190\">being</span> <span m=\"3119995\"\
  >now</span> <span m=\"3120410\">2B,</span> <span m=\"3121490\">and</span> <span\
  \ m=\"3121640\">then</span> <span m=\"3121700\">later</span> <span m=\"3122040\"\
  >3B,</span> <span m=\"3123300\">and</span> <span m=\"3123390\">so</span> <span m=\"\
  3123600\">on.</span> <span m=\"3125460\">So</span> <span m=\"3125610\">you</span>\
  \ <span m=\"3125730\">find</span> <span m=\"3126210\">that</span> <span m=\"3129620\"\
  >x</span> <span m=\"3129950\">plus</span> <span m=\"3130430\">nB</span> <span m=\"\
  3132290\">has</span> <span m=\"3132890\">size,</span> <span m=\"3133530\">at</span>\
  \ <span m=\"3133670\">most,</span> <span m=\"3134330\">k</span> <span m=\"3134930\"\
  >raised</span> <span m=\"3135290\">to</span> <span m=\"3135380\">power</span> <span\
  \ m=\"3135770\">n</span> <span m=\"3136560\">times</span> <span m=\"3136970\">the</span>\
  \ <span m=\"3137090\">size</span> <span m=\"3137480\">of</span> <span m=\"3137600\"\
  >x</span> <span m=\"3138320\">for</span> <span m=\"3138560\">all</span> <span m=\"\
  3139070\">non-negative</span> <span m=\"3139730\">integers,</span> <span m=\"3141072\"\
  >n.</span></p><p><span m=\"3150930\">What</span> <span m=\"3151080\">do</span> <span\
  \ m=\"3151140\">we</span> <span m=\"3151260\">want</span> <span m=\"3151410\">to</span>\
  \ <span m=\"3151470\">control?</span> <span m=\"3152600\">So</span> <span m=\"3152730\"\
  >we</span> <span m=\"3152850\">want</span> <span m=\"3153000\">to</span> <span m=\"\
  3153060\">prove</span> <span m=\"3153450\">a</span> <span m=\"3153920\">bound</span>\
  \ <span m=\"3154410\">on</span> <span m=\"3154530\">the</span> <span m=\"3154620\"\
  >size</span> <span m=\"3155010\">of</span> <span m=\"3155580\">mB</span> <span m=\"\
  3156330\">minus</span> <span m=\"3157310\">nB.</span> <span m=\"3159810\">Take</span>\
  \ <span m=\"3159990\">a</span> <span m=\"3160020\">look</span> <span m=\"3160230\"\
  >at</span> <span m=\"3160290\">the</span> <span m=\"3160680\">statement</span> <span\
  \ m=\"3161310\">of</span> <span m=\"3161850\">Ruzsa</span> <span m=\"3162210\">Triangle</span>\
  \ <span m=\"3162690\">Inequality.</span></p><p><span m=\"3170790\">Applying</span>\
  \ <span m=\"3171700\">Ruzsa</span> <span m=\"3171990\">Triangle</span> <span m=\"\
  3172380\">Inequality,</span> <span m=\"3173970\">we</span> <span m=\"3174090\">find</span>\
  \ <span m=\"3174570\">that</span> <span m=\"3176210\">if</span> <span m=\"3176350\"\
  >we</span> <span m=\"3176440\">want</span> <span m=\"3176620\">to</span> <span m=\"\
  3176680\">control</span> <span m=\"3178450\">mB</span> <span m=\"3179110\">minus</span>\
  \ <span m=\"3180430\">nB,</span> <span m=\"3182800\">we</span> <span m=\"3182890\"\
  >can</span> <span m=\"3183100\">upper</span> <span m=\"3183480\">bound it</span>\
  \ <span m=\"3184270\">by</span> <span m=\"3185530\">x</span> <span m=\"3185920\"\
  >plus</span> <span m=\"3188080\">mB</span> <span m=\"3189631\">x</span> <span m=\"\
  3190090\">plus</span> <span m=\"3191860\">nB</span> <span m=\"3192970\">divided</span>\
  \ <span m=\"3193390\">by</span> <span m=\"3193810\">the</span> <span m=\"3193900\"\
  >size</span> <span m=\"3194380\">of</span> <span m=\"3194980\">x.</span> <span m=\"\
  3198160\">Because</span> <span m=\"3199270\">each</span> <span m=\"3199600\">of</span>\
  \ <span m=\"3199810\">these</span> <span m=\"3200350\">two</span> <span m=\"3200770\"\
  >factors</span> <span m=\"3201340\">in</span> <span m=\"3201460\">the</span> <span\
  \ m=\"3201520\">numerator</span> <span m=\"3202630\">are</span> <span m=\"3203500\"\
  >small</span> <span m=\"3204100\">expansions</span> <span m=\"3204820\">of</span>\
  \ <span m=\"3205000\">x,</span> <span m=\"3205720\">now</span> <span m=\"3205930\"\
  >we</span> <span m=\"3206080\">can</span> <span m=\"3206260\">upper</span> <span\
  \ m=\"3206500\">bound</span> <span m=\"3206770\">the</span> <span m=\"3206860\"\
  >whole</span> <span m=\"3207070\">expression</span> <span m=\"3208300\">by</span>\
  \ <span m=\"3209500\">k</span> <span m=\"3209830\">to</span> <span m=\"3210010\"\
  >the</span> <span m=\"3210160\">m</span> <span m=\"3210430\">plus</span> <span m=\"\
  3210760\">n</span> <span m=\"3211810\">times</span> <span m=\"3212410\">the</span>\
  \ <span m=\"3212530\">size</span> <span m=\"3213160\">of</span> <span m=\"3213580\"\
  >x.</span> <span m=\"3215790\">And</span> <span m=\"3216120\">because</span> <span\
  \ m=\"3216600\">x</span> <span m=\"3216990\">is</span> <span m=\"3217110\">a</span>\
  \ <span m=\"3217170\">subset</span> <span m=\"3217770\">of</span> <span m=\"3218130\"\
  >A,</span> <span m=\"3220230\">we</span> <span m=\"3220380\">can</span> <span m=\"\
  3221730\">do</span> <span m=\"3221910\">one</span> <span m=\"3222120\">more</span>\
  \ <span m=\"3223040\">upper</span> <span m=\"3223230\">bound</span> <span m=\"3223950\"\
  >and</span> <span m=\"3224100\">obtain</span> <span m=\"3224730\">the</span> <span\
  \ m=\"3224850\">bound</span> <span m=\"3225420\">that</span> <span m=\"3225750\"\
  >we</span> <span m=\"3225900\">are</span> <span m=\"3225960\">looking</span> <span\
  \ m=\"3226230\">for.</span> <span m=\"3231400\">OK,</span> <span m=\"3231790\">so</span>\
  \ <span m=\"3232100\">that</span> <span m=\"3232250\">proves</span> <span m=\"3232490\"\
  >the</span> <span m=\"3232580\">key</span> <span m=\"3232760\">lemma.</span> <span\
  \ m=\"3236764\">It's</span> <span m=\"3237232\">OK?</span></p><p><span m=\"3237700\"\
  >AUDIENCE:</span> <span m=\"3237934\">[INAUDIBLE]</span></p><p><span m=\"3239580\"\
  >YUFEI ZHAO:</span> <span m=\"3239650\">Sorry,</span> <span m=\"3241350\">that</span>\
  \ <span m=\"3241480\">proves the</span> <span m=\"3241750\">theorem,</span> <span\
  \ m=\"3242170\">assuming</span> <span m=\"3242530\">the key</span> <span m=\"3242620\"\
  >lemma.</span> <span m=\"3243610\">Thank you,</span> <span m=\"3244440\">that's\
  \ what</span> <span m=\"3244630\">I</span> <span m=\"3244670\">meant</span> <span\
  \ m=\"3244820\">to</span> <span m=\"3244880\">say.</span> <span m=\"3245170\">Yeah,</span>\
  \ <span m=\"3245360\">so that</span> <span m=\"3246040\">proves</span> <span m=\"\
  3246250\">the</span> <span m=\"3246320\">theorem,</span> <span m=\"3246680\">assuming</span>\
  \ <span m=\"3246910\">the</span> <span m=\"3247000\">key lemma.</span> <span m=\"\
  3247360\">So</span> <span m=\"3247450\">now</span> <span m=\"3247600\">we</span>\
  \ <span m=\"3247720\">do</span> <span m=\"3247810\">prove</span> <span m=\"3247990\"\
  >the</span> <span m=\"3248080\">key lemma.</span></p><p><span m=\"3250170\">Great,</span>\
  \ <span m=\"3250690\">we</span> <span m=\"3250820\">need</span> <span m=\"3250920\"\
  >to</span> <span m=\"3250990\">prove</span> <span m=\"3251290\">the</span> <span\
  \ m=\"3251350\">key</span> <span m=\"3251650\">lemma.</span> <span m=\"3252010\"\
  >And</span> <span m=\"3252520\">so</span> <span m=\"3252750\">Petridis'</span> <span\
  \ m=\"3253270\">proof</span> <span m=\"3253540\">of</span> <span m=\"3253600\">the</span>\
  \ <span m=\"3253660\">key</span> <span m=\"3253960\">lemma,</span> <span m=\"3255000\"\
  >it's</span> <span m=\"3255190\">quite</span> <span m=\"3255820\">surprising,</span>\
  \ <span m=\"3256930\">in</span> <span m=\"3257050\">that</span> <span m=\"3257280\"\
  >it</span> <span m=\"3257350\">uses</span> <span m=\"3257740\">induction.</span>\
  \ <span m=\"3259300\">And</span> <span m=\"3259450\">basically,</span> <span m=\"\
  3259840\">we</span> <span m=\"3260020\">have</span> <span m=\"3260260\">not</span>\
  \ <span m=\"3260620\">used</span> <span m=\"3260920\">induction</span> <span m=\"\
  3261430\">in</span> <span m=\"3261550\">this</span> <span m=\"3261730\">course</span>\
  \ <span m=\"3262840\">ever</span> <span m=\"3263050\">since</span> <span m=\"3263320\"\
  >the</span> <span m=\"3263410\">first</span> <span m=\"3263980\">or</span> <span\
  \ m=\"3264280\">maybe</span> <span m=\"3264460\">the</span> <span m=\"3264550\"\
  >second</span> <span m=\"3265090\">lecture,</span> <span m=\"3266580\">and</span>\
  \ <span m=\"3266680\">for</span> <span m=\"3266830\">good</span> <span m=\"3266980\"\
  >reason.</span></p><p><span m=\"3267430\">So</span> <span m=\"3267580\">everything\
  \ in</span> <span m=\"3267940\">this</span> <span m=\"3268120\">course</span> <span\
  \ m=\"3268360\">is</span> <span m=\"3268480\">fairly</span> <span m=\"3268750\"\
  >analytic.</span> <span m=\"3269680\">You</span> <span m=\"3269740\">know,</span>\
  \ <span m=\"3269950\">you</span> <span m=\"3270040\">have</span> <span m=\"3270190\"\
  >these</span> <span m=\"3270370\">Roth</span> <span m=\"3270640\">bounds.</span>\
  \ <span m=\"3271060\">And</span> <span m=\"3271390\">putting</span> <span m=\"3272110\"\
  >one</span> <span m=\"3272380\">extra</span> <span m=\"3272650\">vertex</span> <span\
  \ m=\"3273130\">often</span> <span m=\"3273400\">doesn't</span> <span m=\"3273670\"\
  >really</span> <span m=\"3273880\">help.</span> <span m=\"3276010\">OK,</span> <span\
  \ m=\"3276250\">so</span> <span m=\"3276640\">here,</span> <span m=\"3276880\">we're</span>\
  \ <span m=\"3277060\">going</span> <span m=\"3277270\">to</span> <span m=\"3277390\"\
  >use</span> <span m=\"3278740\">induction</span> <span m=\"3279700\">on</span> <span\
  \ m=\"3279910\">the</span> <span m=\"3280030\">size</span> <span m=\"3280600\">of</span>\
  \ <span m=\"3281410\">C.</span> <span m=\"3294600\">OK,</span> <span m=\"3294760\"\
  >I</span> <span m=\"3294820\">just</span> <span m=\"3295000\">want</span> <span\
  \ m=\"3295070\">to</span> <span m=\"3295150\">emphasize</span> <span m=\"3295480\"\
  >again</span> <span m=\"3295670\">that</span> <span m=\"3295750\">the</span> <span\
  \ m=\"3295840\">use</span> <span m=\"3296080\">of</span> <span m=\"3296170\">induction</span>\
  \ <span m=\"3296590\">here</span> <span m=\"3296800\">was</span> <span m=\"3296980\"\
  >surprising.</span></p><p><span m=\"3299190\">So if</span> <span m=\"3299410\">the</span>\
  \ <span m=\"3299500\">base</span> <span m=\"3299770\">case--</span> <span m=\"3302320\"\
  >always</span> <span m=\"3302620\">check</span> <span m=\"3302860\">the</span> <span\
  \ m=\"3302950\">base</span> <span m=\"3303190\">case--</span> <span m=\"3305290\"\
  >when</span> <span m=\"3305560\">C</span> <span m=\"3305950\">is</span> <span m=\"\
  3306190\">1,</span> <span m=\"3306940\">then</span> <span m=\"3307510\">plus</span>\
  \ <span m=\"3307910\">C</span> <span m=\"3309550\">is</span> <span m=\"3310000\"\
  >a</span> <span m=\"3310060\">translation.</span> <span m=\"3315070\">So</span>\
  \ <span m=\"3315350\">this</span> <span m=\"3315630\">shifts</span> <span m=\"3316500\"\
  >the</span> <span m=\"3316620\">set</span> <span m=\"3317520\">over.</span> <span\
  \ m=\"3318630\">And</span> <span m=\"3322300\">so</span> <span m=\"3322570\">you</span>\
  \ <span m=\"3322900\">can</span> <span m=\"3323770\">see</span> <span m=\"3324130\"\
  >that</span> <span m=\"3324490\">if</span> <span m=\"3324670\">you</span> <span\
  \ m=\"3325840\">do</span> <span m=\"3325990\">plus</span> <span m=\"3326290\">C\
  \ and</span> <span m=\"3326620\">minus</span> <span m=\"3326950\">1,</span> <span\
  \ m=\"3327070\">you</span> <span m=\"3327190\">raise</span> <span m=\"3327430\"\
  >the</span> <span m=\"3327520\">plus</span> <span m=\"3327775\">C.</span> <span\
  \ m=\"3328690\">And</span> <span m=\"3329560\">the</span> <span m=\"3329650\">conclusion</span>\
  \ <span m=\"3332170\">follows</span> <span m=\"3332650\">basically</span> <span\
  \ m=\"3333040\">from</span> <span m=\"3333190\">the</span> <span m=\"3333280\">hypothesis.</span>\
  \ <span m=\"3335830\">So</span> <span m=\"3337390\">in</span> <span m=\"3337510\"\
  >this</span> <span m=\"3337660\">case,</span> <span m=\"3338020\">x</span> <span\
  \ m=\"3338290\">plus</span> <span m=\"3338650\">B</span> <span m=\"3339190\">plus</span>\
  \ <span m=\"3339490\">C</span> <span m=\"3340360\">is</span> <span m=\"3340840\"\
  >equal</span> <span m=\"3341230\">to</span> <span m=\"3342340\">x</span> <span m=\"\
  3342670\">plus</span> <span m=\"3343030\">B,</span> <span m=\"3344140\">which is,</span>\
  \ <span m=\"3344560\">at</span> <span m=\"3344740\">most,</span> <span m=\"3346000\"\
  >k</span> <span m=\"3346540\">prime</span> <span m=\"3347530\">times</span> <span\
  \ m=\"3348340\">the</span> <span m=\"3348400\">size</span> <span m=\"3348970\">x,</span>\
  \ <span m=\"3349990\">by</span> <span m=\"3350170\">definition</span> <span m=\"\
  3350770\">of--</span> <span m=\"3352990\">so</span> <span m=\"3353470\">this</span>\
  \ <span m=\"3353950\">actually</span> <span m=\"3354190\">is</span> <span m=\"3354550\"\
  >equal</span> <span m=\"3355960\">to</span> <span m=\"3356050\">the</span> <span\
  \ m=\"3356170\">size</span> <span m=\"3356470\">of</span> <span m=\"3356590\">k.</span>\
  \ <span m=\"3363030\">The</span> <span m=\"3363250\">base</span> <span m=\"3363490\"\
  >case</span> <span m=\"3363730\">is</span> <span m=\"3363850\">easy.</span></p><p><span\
  \ m=\"3366660\">Now</span> <span m=\"3366810\">we</span> <span m=\"3366960\">do</span>\
  \ <span m=\"3367080\">the</span> <span m=\"3367170\">induction</span> <span m=\"\
  3367630\">step.</span> <span m=\"3373660\">So</span> <span m=\"3373780\">let's</span>\
  \ <span m=\"3373990\">assume</span> <span m=\"3376210\">that</span> <span m=\"3377520\"\
  >the</span> <span m=\"3377590\">size</span> <span m=\"3378010\">of</span> <span\
  \ m=\"3378100\">C</span> <span m=\"3378460\">is</span> <span m=\"3378700\">bigger</span>\
  \ <span m=\"3378970\">than</span> <span m=\"3379120\">1</span> <span m=\"3380080\"\
  >and</span> <span m=\"3381070\">C</span> <span m=\"3381610\">is</span> <span m=\"\
  3381960\">C</span> <span m=\"3382330\">prime</span> <span m=\"3383380\">plus</span>\
  \ <span m=\"3383980\">an</span> <span m=\"3384130\">additional</span> <span m=\"\
  3384760\">element,</span> <span m=\"3385300\">which</span> <span m=\"3385510\">we'll</span>\
  \ <span m=\"3385660\">call</span> <span m=\"3385990\">gamma.</span> <span m=\"3389680\"\
  >So</span> <span m=\"3389890\">let's</span> <span m=\"3391030\">see</span> <span\
  \ m=\"3391420\">this</span> <span m=\"3391630\">expression,</span> <span m=\"3392480\"\
  >x</span> <span m=\"3392740\">plus</span> <span m=\"3393130\">B</span> <span m=\"\
  3393550\">plus</span> <span m=\"3394000\">C,</span> <span m=\"3395410\">by</span>\
  \ <span m=\"3395710\">separating</span> <span m=\"3396430\">it</span> <span m=\"\
  3397090\">according</span> <span m=\"3397450\">to</span> <span m=\"3398220\">if</span>\
  \ <span m=\"3398570\">its</span> <span m=\"3398740\">contribution</span> <span m=\"\
  3399340\">came</span> <span m=\"3399760\">from</span> <span m=\"3400570\">C</span>\
  \ <span m=\"3400840\">prime</span> <span m=\"3402040\">or</span> <span m=\"3402160\"\
  >not.</span></p><p><span m=\"3404870\">The</span> <span m=\"3405000\">contributions</span>\
  \ <span m=\"3405690\">that</span> <span m=\"3405840\">came</span> <span m=\"3406080\"\
  >from</span> <span m=\"3406320\">C</span> <span m=\"3406560\">prime,</span> <span\
  \ m=\"3407460\">I</span> <span m=\"3407550\">can</span> <span m=\"3407730\">write</span>\
  \ <span m=\"3408030\">it</span> <span m=\"3409320\">like</span> <span m=\"3409530\"\
  >that.</span> <span m=\"3413010\">And</span> <span m=\"3413110\">then</span> <span\
  \ m=\"3413150\">there</span> <span m=\"3413220\">are</span> <span m=\"3413360\"\
  >other</span> <span m=\"3413600\">contributions,</span> <span m=\"3414440\">namely</span>\
  \ <span m=\"3414890\">those</span> <span m=\"3415190\">that</span> <span m=\"3415370\"\
  >came</span> <span m=\"3415640\">from</span> <span m=\"3415910\">this</span> <span\
  \ m=\"3416150\">extra</span> <span m=\"3416510\">element.</span> <span m=\"3424480\"\
  >But</span> <span m=\"3424710\">I</span> <span m=\"3424830\">may</span> <span m=\"\
  3424950\">have</span> <span m=\"3425130\">some</span> <span m=\"3425310\">redundancies</span>\
  \ <span m=\"3426180\">in</span> <span m=\"3426300\">doing</span> <span m=\"3426510\"\
  >this.</span> <span m=\"3428960\">So</span> <span m=\"3429080\">I</span> <span m=\"\
  3429150\">may</span> <span m=\"3429270\">have</span> <span m=\"3429420\">some</span>\
  \ <span m=\"3429660\">redundancies</span> <span m=\"3430710\">coming</span> <span\
  \ m=\"3431040\">from</span> <span m=\"3431400\">the</span> <span m=\"3431490\">fact</span>\
  \ <span m=\"3431760\">that</span> <span m=\"3431940\">some</span> <span m=\"3432240\"\
  >of</span> <span m=\"3432330\">the</span> <span m=\"3432450\">elements</span> <span\
  \ m=\"3433470\">in</span> <span m=\"3433590\">this</span> <span m=\"3433770\">set</span>\
  \ <span m=\"3434430\">might</span> <span m=\"3434760\">have</span> <span m=\"3434970\"\
  >already</span> <span m=\"3435450\">appeared</span> <span m=\"3436480\">earlier.</span></p><p><span\
  \ m=\"3438100\">So</span> <span m=\"3438250\">let</span> <span m=\"3438370\">me</span>\
  \ <span m=\"3438520\">take</span> <span m=\"3438850\">out</span> <span m=\"3439360\"\
  >those</span> <span m=\"3440140\">elements</span> <span m=\"3447300\">by</span>\
  \ <span m=\"3447510\">taking</span> <span m=\"3447930\">out</span> <span m=\"3452490\"\
  >elements</span> <span m=\"3453870\">where</span> <span m=\"3455270\">it</span>\
  \ <span m=\"3455400\">already</span> <span m=\"3455760\">appeared</span> <span m=\"\
  3456360\">earlier.</span> <span m=\"3457230\">So</span> <span m=\"3457380\">this</span>\
  \ <span m=\"3457560\">means</span> <span m=\"3458490\">I'm</span> <span m=\"3458610\"\
  >looking</span> <span m=\"3458940\">at</span> <span m=\"3461250\">the</span> <span\
  \ m=\"3461340\">set</span> <span m=\"3461700\">z</span> <span m=\"3462330\">being</span>\
  \ <span m=\"3463380\">elements</span> <span m=\"3463800\">of</span> <span m=\"3464070\"\
  >x</span> <span m=\"3464910\">such</span> <span m=\"3465270\">that</span> <span\
  \ m=\"3466620\">x</span> <span m=\"3467550\">plus</span> <span m=\"3467940\">B</span>\
  \ <span m=\"3468870\">plus</span> <span m=\"3469260\">gamma</span> <span m=\"3470170\"\
  >is</span> <span m=\"3470730\">already</span> <span m=\"3471150\">a</span> <span\
  \ m=\"3471210\">subset</span> <span m=\"3472620\">of</span> <span m=\"3473370\"\
  >x</span> <span m=\"3474300\">plus</span> <span m=\"3474630\">B</span> <span m=\"\
  3475560\">plus</span> <span m=\"3476280\">C</span> <span m=\"3476580\">prime.</span>\
  \ <span m=\"3479570\">So</span> <span m=\"3479750\">the</span> <span m=\"3479870\"\
  >stuff</span> <span m=\"3480140\">in</span> <span m=\"3480410\">yellow,</span> <span\
  \ m=\"3481310\">I</span> <span m=\"3481400\">can</span> <span m=\"3481700\">safely</span>\
  \ <span m=\"3482120\">discard,</span> <span m=\"3482600\">because</span> <span m=\"\
  3482900\">it</span> <span m=\"3483110\">already</span> <span m=\"3483500\">appeared</span>\
  \ <span m=\"3483980\">earlier.</span></p><p><span m=\"3491490\">So</span> <span\
  \ m=\"3494120\">because</span> <span m=\"3494510\">of</span> <span m=\"3494570\"\
  >the</span> <span m=\"3494630\">definition</span> <span m=\"3495230\">of</span>\
  \ <span m=\"3495500\">z,</span> <span m=\"3496250\">we</span> <span m=\"3496400\"\
  >see</span> <span m=\"3496760\">that</span> <span m=\"3498260\">z</span> <span m=\"\
  3498980\">plus</span> <span m=\"3499580\">B</span> <span m=\"3500480\">plus</span>\
  \ <span m=\"3501560\">gamma</span> <span m=\"3503510\">appears</span> <span m=\"\
  3504020\">in</span> <span m=\"3504290\">x</span> <span m=\"3505250\">plus</span>\
  \ <span m=\"3505640\">B</span> <span m=\"3506330\">plus</span> <span m=\"3506630\"\
  >C</span> <span m=\"3506840\">prime.</span> <span m=\"3507950\">So</span> <span\
  \ m=\"3508700\">that</span> <span m=\"3508940\">union</span> <span m=\"3509300\"\
  >is</span> <span m=\"3509450\">valid.</span> <span m=\"3511940\">Now,</span> <span\
  \ m=\"3512890\">z</span> <span m=\"3513350\">is</span> <span m=\"3513500\">a</span>\
  \ <span m=\"3513560\">subset</span> <span m=\"3514190\">of</span> <span m=\"3514400\"\
  >x.</span> <span m=\"3519500\">So</span> <span m=\"3520520\">the</span> <span m=\"\
  3520700\">expansion</span> <span m=\"3521450\">ratio</span> <span m=\"3523610\"\
  >for</span> <span m=\"3523850\">z</span> <span m=\"3526040\">is</span> <span m=\"\
  3526430\">at</span> <span m=\"3526610\">least</span> <span m=\"3527390\">k</span>\
  \ <span m=\"3527660\">prime,</span> <span m=\"3528410\">because</span> <span m=\"\
  3528740\">we</span> <span m=\"3528890\">chose</span> <span m=\"3530060\">x</span>\
  \ <span m=\"3530450\">to</span> <span m=\"3530600\">minimize</span> <span m=\"3531410\"\
  >this</span> <span m=\"3531740\">expansion</span> <span m=\"3532430\">ratio.</span></p><p><span\
  \ m=\"3547530\">We</span> <span m=\"3547700\">would</span> <span m=\"3547790\">like</span>\
  \ <span m=\"3547950\">to</span> <span m=\"3548070\">understand</span> <span m=\"\
  3549480\">how</span> <span m=\"3550500\">big</span> <span m=\"3551700\">x</span>\
  \ <span m=\"3551970\">plus</span> <span m=\"3552300\">B</span> <span m=\"3552630\"\
  >plus</span> <span m=\"3552870\">C.</span> <span m=\"3553830\">So</span> <span m=\"\
  3553980\">let's</span> <span m=\"3554400\">evaluate</span> <span m=\"3555270\">the</span>\
  \ <span m=\"3555480\">cardinality</span> <span m=\"3556680\">of</span> <span m=\"\
  3556920\">that</span> <span m=\"3558570\">expression</span> <span m=\"3559310\"\
  >up</span> <span m=\"3559490\">there.</span> <span m=\"3561260\">The</span> <span\
  \ m=\"3561390\">cardinality</span> <span m=\"3562550\">I</span> <span m=\"3562960\"\
  >can</span> <span m=\"3563100\">upper</span> <span m=\"3563310\">bound</span> <span\
  \ m=\"3563790\">by</span> <span m=\"3564530\">the</span> <span m=\"3564810\">union</span>\
  \ <span m=\"3565230\">of</span> <span m=\"3565350\">these</span> <span m=\"3565920\"\
  >sum</span> <span m=\"3566280\">of</span> <span m=\"3566400\">the</span> <span m=\"\
  3566700\">sizes</span> <span m=\"3567120\">of</span> <span m=\"3567210\">the</span>\
  \ <span m=\"3567270\">components.</span></p><p><span m=\"3579420\">So up</span>\
  \ <span m=\"3579690\">there, so</span> <span m=\"3580050\">I</span> <span m=\"3581870\"\
  >just</span> <span m=\"3583010\">do</span> <span m=\"3583200\">a</span> <span m=\"\
  3583290\">union</span> <span m=\"3583590\">bound</span> <span m=\"3584280\">on</span>\
  \ <span m=\"3584520\">that</span> <span m=\"3584760\">expression</span> <span m=\"\
  3585270\">up</span> <span m=\"3585420\">there.</span> <span m=\"3590490\">And</span>\
  \ <span m=\"3590550\">now</span> <span m=\"3590730\">you</span> <span m=\"3590820\"\
  >see</span> <span m=\"3591150\">z</span> <span m=\"3591550\">is</span> <span m=\"\
  3591720\">a</span> <span m=\"3591780\">subset</span> <span m=\"3592410\">of</span>\
  \ <span m=\"3592840\">x.</span> <span m=\"3593310\">So</span> <span m=\"3593550\"\
  >I</span> <span m=\"3593640\">can</span> <span m=\"3593820\">split</span> <span\
  \ m=\"3594690\">this</span> <span m=\"3594900\">expression</span> <span m=\"3595440\"\
  >up</span> <span m=\"3595650\">even</span> <span m=\"3595950\">further.</span></p><p><span\
  \ m=\"3609657\">All right,</span> <span m=\"3613120\">now</span> <span m=\"3613320\"\
  >let's</span> <span m=\"3613560\">use</span> <span m=\"3613740\">the</span> <span\
  \ m=\"3613860\">induction</span> <span m=\"3614340\">hypothesis.</span> <span m=\"\
  3615930\">So</span> <span m=\"3616080\">we</span> <span m=\"3616230\">have</span>\
  \ <span m=\"3616380\">some</span> <span m=\"3616560\">expression</span> <span m=\"\
  3617160\">involving</span> <span m=\"3617700\">x</span> <span m=\"3618210\">plus</span>\
  \ <span m=\"3618570\">B</span> <span m=\"3619170\">plus</span> <span m=\"3619590\"\
  >C</span> <span m=\"3619980\">prime.</span> <span m=\"3621790\">So</span> <span\
  \ m=\"3621870\">now</span> <span m=\"3622080\">we</span> <span m=\"3622260\">apply</span>\
  \ <span m=\"3623130\">induction</span> <span m=\"3626550\">hypothesis</span> <span\
  \ m=\"3627720\">over</span> <span m=\"3627930\">here</span> <span m=\"3628170\"\
  >to</span> <span m=\"3628380\">this</span> <span m=\"3628590\">expression</span>\
  \ <span m=\"3629380\">that</span> <span m=\"3629580\">has</span> <span m=\"3630030\"\
  >plus</span> <span m=\"3630330\">C</span> <span m=\"3630510\">prime.</span></p><p><span\
  \ m=\"3632260\">And</span> <span m=\"3632380\">we</span> <span m=\"3632530\">obtain</span>\
  \ <span m=\"3633355\">an</span> <span m=\"3633700\">upper</span> <span m=\"3633910\"\
  >bound</span> <span m=\"3634460\">which</span> <span m=\"3634510\">is</span> <span\
  \ m=\"3634720\">k</span> <span m=\"3634960\">prime</span> <span m=\"3636850\">x</span>\
  \ <span m=\"3637540\">plus</span> <span m=\"3638020\">C</span> <span m=\"3638290\"\
  >prime.</span> <span m=\"3643370\">And</span> <span m=\"3643490\">the</span> <span\
  \ m=\"3643580\">two</span> <span m=\"3643910\">expressions</span> <span m=\"3644720\"\
  >on</span> <span m=\"3644900\">the</span> <span m=\"3644990\">right,</span> <span\
  \ m=\"3645510\">well,</span> <span m=\"3645710\">one</span> <span m=\"3645950\"\
  >of</span> <span m=\"3646040\">them</span> <span m=\"3646250\">here</span> <span\
  \ m=\"3647730\">is,</span> <span m=\"3648050\">by</span> <span m=\"3648230\">definition,</span>\
  \ <span m=\"3650850\">coming</span> <span m=\"3651150\">from</span> <span m=\"3651360\"\
  >the</span> <span m=\"3651450\">expansion</span> <span m=\"3652050\">ratio</span>\
  \ <span m=\"3652620\">of</span> <span m=\"3655010\">x.</span> <span m=\"3656610\"\
  >And</span> <span m=\"3656740\">then</span> <span m=\"3656920\">the</span> <span\
  \ m=\"3657070\">other,</span> <span m=\"3658180\">we</span> <span m=\"3658660\"\
  >gave</span> <span m=\"3658900\">a</span> <span m=\"3658960\">bound</span> <span\
  \ m=\"3659650\">just</span> <span m=\"3659980\">now.</span></p><p><span m=\"3672060\"\
  >OK,</span> <span m=\"3672330\">so</span> <span m=\"3672600\">we're</span> <span\
  \ m=\"3673110\">almost</span> <span m=\"3673440\">there.</span> <span m=\"3673770\"\
  >So</span> <span m=\"3673950\">we</span> <span m=\"3674070\">are</span> <span m=\"\
  3674160\">trying</span> <span m=\"3674460\">to</span> <span m=\"3674550\">upper</span>\
  \ <span m=\"3674770\">bound</span> <span m=\"3675240\">the</span> <span m=\"3675330\"\
  >size</span> <span m=\"3675750\">of</span> <span m=\"3675900\">this</span> <span\
  \ m=\"3676140\">quantity.</span> <span m=\"3677520\">So</span> <span m=\"3677965\"\
  >we</span> <span m=\"3678800\">decomposed</span> <span m=\"3679320\">it</span> <span\
  \ m=\"3679690\">into</span> <span m=\"3681010\">pieces</span> <span m=\"3681490\"\
  >according</span> <span m=\"3681880\">to</span> <span m=\"3682000\">its</span> <span\
  \ m=\"3682120\">contribution</span> <span m=\"3682690\">coming</span> <span m=\"\
  3682960\">from</span> <span m=\"3683140\">this</span> <span m=\"3683290\">extra</span>\
  \ <span m=\"3683590\">element.</span> <span m=\"3684240\">And</span> <span m=\"\
  3684520\">we</span> <span m=\"3684700\">analyzed</span> <span m=\"3685300\">these</span>\
  \ <span m=\"3685510\">pieces</span> <span m=\"3686020\">individually.</span></p><p><span\
  \ m=\"3688770\">But</span> <span m=\"3688910\">now</span> <span m=\"3689390\">I</span>\
  \ <span m=\"3689540\">want</span> <span m=\"3689780\">to</span> <span m=\"3689990\"\
  >understand</span> <span m=\"3690680\">the</span> <span m=\"3691040\">right-hand</span>\
  \ <span m=\"3691610\">side,</span> <span m=\"3692630\">so</span> <span m=\"3693140\"\
  >x</span> <span m=\"3693440\">plus</span> <span m=\"3693920\">C.</span> <span m=\"\
  3696040\">So</span> <span m=\"3696160\">let's</span> <span m=\"3696340\">try</span>\
  \ <span m=\"3696460\">to</span> <span m=\"3696550\">understand</span> <span m=\"\
  3696970\">the</span> <span m=\"3697030\">right-hand</span> <span m=\"3697420\">side.</span>\
  \ <span m=\"3701140\">See,</span> <span m=\"3701290\">the</span> <span m=\"3701470\"\
  >x</span> <span m=\"3701830\">plus</span> <span m=\"3702350\">C,</span> <span m=\"\
  3703570\">I</span> <span m=\"3703660\">can</span> <span m=\"3704590\">likewise</span>\
  \ <span m=\"3705160\">write</span> <span m=\"3705370\">it</span> <span m=\"3705720\"\
  >as</span> <span m=\"3705940\">earlier</span> <span m=\"3706510\">by</span> <span\
  \ m=\"3706690\">decomposing</span> <span m=\"3707380\">it</span> <span m=\"3707470\"\
  >into</span> <span m=\"3707800\">contributions</span> <span m=\"3709840\">from</span>\
  \ <span m=\"3711070\">C</span> <span m=\"3711370\">prime</span> <span m=\"3712510\"\
  >and</span> <span m=\"3712630\">those</span> <span m=\"3713020\">from</span> <span\
  \ m=\"3713350\">the</span> <span m=\"3713500\">extra</span> <span m=\"3713980\"\
  >element.</span></p><p><span m=\"3721490\">And</span> <span m=\"3721890\">as</span>\
  \ <span m=\"3722120\">earlier,</span> <span m=\"3722860\">we</span> <span m=\"3723010\"\
  >can</span> <span m=\"3723220\">take</span> <span m=\"3723580\">out</span> <span\
  \ m=\"3724030\">contributions</span> <span m=\"3725200\">that</span> <span m=\"\
  3725890\">were</span> <span m=\"3726130\">already</span> <span m=\"3726670\">appearing</span>\
  \ <span m=\"3727360\">earlier,</span> <span m=\"3730280\">which we</span> <span\
  \ m=\"3730510\">now</span> <span m=\"3730730\">recall</span> <span m=\"3731630\"\
  >W</span> <span m=\"3732020\">plus</span> <span m=\"3732410\">gamma,</span> <span\
  \ m=\"3733160\">where</span> <span m=\"3733820\">W</span> <span m=\"3737050\">is</span>\
  \ <span m=\"3737710\">the</span> <span m=\"3737800\">set</span> <span m=\"3738130\"\
  >of</span> <span m=\"3739090\">elements</span> <span m=\"3739570\">in</span> <span\
  \ m=\"3739900\">x,</span> <span m=\"3741100\">such</span> <span m=\"3741400\">that</span>\
  \ <span m=\"3741700\">x</span> <span m=\"3742240\">plus</span> <span m=\"3742660\"\
  >gamma</span> <span m=\"3744970\">is</span> <span m=\"3745180\">already</span> <span\
  \ m=\"3746050\">contained</span> <span m=\"3747310\">in</span> <span m=\"3747670\"\
  >x</span> <span m=\"3747910\">plus</span> <span m=\"3748510\">C</span> <span m=\"\
  3748810\">prime.</span> <span m=\"3750100\">So</span> <span m=\"3752170\">this</span>\
  \ <span m=\"3752500\">part</span> <span m=\"3752740\">was</span> <span m=\"3753010\"\
  >already</span> <span m=\"3753340\">included</span> <span m=\"3753760\">earlier.</span>\
  \ <span m=\"3754120\">We</span> <span m=\"3754300\">don't</span> <span m=\"3754440\"\
  >need</span> <span m=\"3754570\">to</span> <span m=\"3754660\">include</span> <span\
  \ m=\"3754990\">it</span> <span m=\"3755110\">any</span> <span m=\"3755300\">more.</span></p><p><span\
  \ m=\"3759234\">A</span> <span m=\"3759700\">couple</span> <span m=\"3760000\">of</span>\
  \ <span m=\"3760570\">observations</span> <span m=\"3761230\">that</span> <span\
  \ m=\"3761380\">were</span> <span m=\"3761560\">different</span> <span m=\"3762010\"\
  >from</span> <span m=\"3762250\">earlier--</span> <span m=\"3763480\">now</span>\
  \ <span m=\"3764110\">this</span> <span m=\"3764410\">union</span> <span m=\"3764890\"\
  >I</span> <span m=\"3764980\">claim</span> <span m=\"3765250\">and say</span> <span\
  \ m=\"3765880\">disjoined</span> <span m=\"3766510\">union.</span> <span m=\"3772518\"\
  >So</span> <span m=\"3772990\">this</span> <span m=\"3773200\">union</span> <span\
  \ m=\"3773500\">is a</span> <span m=\"3773690\">disjoined</span> <span m=\"3774190\"\
  >union.</span> <span m=\"3775250\">So</span> <span m=\"3775300\">there</span> <span\
  \ m=\"3775480\">is</span> <span m=\"3775570\">actually</span> <span m=\"3776800\"\
  >no</span> <span m=\"3777010\">more</span> <span m=\"3777970\">overlaps.</span>\
  \ <span m=\"3782780\">And</span> <span m=\"3782930\">furthermore,</span> <span m=\"\
  3783710\">W</span> <span m=\"3784820\">is</span> <span m=\"3785060\">contained</span>\
  \ <span m=\"3785870\">in</span> <span m=\"3786020\">the</span> <span m=\"3786110\"\
  >set</span> <span m=\"3786500\">z</span> <span m=\"3787100\">from</span> <span m=\"\
  3787370\">earlier.</span> <span m=\"3797410\">Any</span> <span m=\"3797910\">questions?</span></p><p><span\
  \ m=\"3804634\">All</span> <span m=\"3805130\">right,</span> <span m=\"3805790\"\
  >therefore,</span> <span m=\"3808640\">the</span> <span m=\"3808680\">size</span>\
  \ <span m=\"3809040\">of</span> <span m=\"3809160\">x</span> <span m=\"3809460\"\
  >plus</span> <span m=\"3809730\">C</span> <span m=\"3810990\">is</span> <span m=\"\
  3811140\">equal</span> <span m=\"3811890\">to,</span> <span m=\"3812740\">because</span>\
  \ <span m=\"3812970\">this</span> <span m=\"3813120\">is</span> <span m=\"3813240\"\
  >a</span> <span m=\"3813300\">disjoined</span> <span m=\"3813840\">union,</span>\
  \ <span m=\"3814980\">x</span> <span m=\"3815550\">plus</span> <span m=\"3816060\"\
  >C</span> <span m=\"3816360\">prime</span> <span m=\"3817260\">plus</span> <span\
  \ m=\"3817620\">the</span> <span m=\"3817710\">size</span> <span m=\"3818130\">of</span>\
  \ <span m=\"3818220\">x</span> <span m=\"3818880\">minus</span> <span m=\"3819390\"\
  >the</span> <span m=\"3819480\">size</span> <span m=\"3819900\">of</span> <span\
  \ m=\"3820310\">W,</span> <span m=\"3826590\">and</span> <span m=\"3829230\">which</span>\
  \ <span m=\"3830100\">is--</span> <span m=\"3831030\">so</span> <span m=\"3831350\"\
  >W,</span> <span m=\"3831900\">because</span> <span m=\"3832200\">W</span> <span\
  \ m=\"3832530\">is</span> <span m=\"3832620\">contained</span> <span m=\"3833370\"\
  >in</span> <span m=\"3833550\">z,</span> <span m=\"3834700\">is</span> <span m=\"\
  3835230\">x</span> <span m=\"3835980\">plus</span> <span m=\"3836400\">C</span>\
  \ <span m=\"3836700\">prime</span> <span m=\"3837930\">plus</span> <span m=\"3838590\"\
  >the</span> <span m=\"3838710\">size</span> <span m=\"3839070\">of</span> <span\
  \ m=\"3839190\">x</span> <span m=\"3839850\">minus</span> <span m=\"3840420\">the</span>\
  \ <span m=\"3840540\">size</span> <span m=\"3841050\">of</span> <span m=\"3841260\"\
  >z.</span> <span m=\"3847160\">Now</span> <span m=\"3847350\">you</span> <span m=\"\
  3847470\">compare</span> <span m=\"3848040\">these</span> <span m=\"3848280\">two</span>\
  \ <span m=\"3848490\">expressions.</span> <span m=\"3852660\">And</span> <span m=\"\
  3852790\">that</span> <span m=\"3852940\">proves</span> <span m=\"3853330\">the</span>\
  \ <span m=\"3853420\">key</span> <span m=\"3853620\">lemma.</span> <span m=\"3861255\"\
  >OK?</span> <span m=\"3863211\">That's</span> <span m=\"3863700\">it.</span> <span\
  \ m=\"3864678\">Yeah?</span></p><p><span m=\"3864800\">AUDIENCE:</span> <span m=\"\
  3864861\">Can</span> <span m=\"3864922\">you</span> <span m=\"3865044\">explain</span>\
  \ <span m=\"3865167\">one more</span> <span m=\"3865656\">time why it's</span> <span\
  \ m=\"3866145\">a disjoined</span> <span m=\"3866634\">union?</span></p><p><span\
  \ m=\"3867620\">YUFEI ZHAO:</span> <span m=\"3867740\">OK,</span> <span m=\"3867860\"\
  >great,</span> <span m=\"3868090\">so</span> <span m=\"3868220\">why</span> <span\
  \ m=\"3868520\">is</span> <span m=\"3868730\">this</span> <span m=\"3868940\">a</span>\
  \ <span m=\"3869030\">disjoined</span> <span m=\"3869600\">union?</span> <span m=\"\
  3870453\">Now,</span> <span m=\"3872920\">I</span> <span m=\"3873020\">have</span>\
  \ <span m=\"3873120\">the</span> <span m=\"3873160\">set</span> <span m=\"3873430\"\
  >here.</span> <span m=\"3874500\">So</span> <span m=\"3875390\">I'm</span> <span\
  \ m=\"3875570\">looking</span> <span m=\"3875930\">at</span> <span m=\"3877500\"\
  >this</span> <span m=\"3878730\">x</span> <span m=\"3879060\">plus</span> <span\
  \ m=\"3879780\">gamma.</span> <span m=\"3883760\">So</span> <span m=\"3884090\"\
  >think</span> <span m=\"3884330\">about,</span> <span m=\"3884910\">let's</span>\
  \ <span m=\"3884990\">say,</span> <span m=\"3885170\">gamma</span> <span m=\"3885630\"\
  >equals</span> <span m=\"3885880\">to</span> <span m=\"3885980\">0.</span> <span\
  \ m=\"3886790\">So</span> <span m=\"3887010\">we</span> <span m=\"3888200\">translate,</span>\
  \ <span m=\"3888620\">think</span> <span m=\"3888800\">about if</span> <span m=\"\
  3889110\">gamma</span> <span m=\"3889490\">equals</span> <span m=\"3889700\">to</span>\
  \ <span m=\"3889790\">0.</span></p><p><span m=\"3891910\">So</span> <span m=\"3892240\"\
  >I</span> <span m=\"3892990\">include</span> <span m=\"3893860\">x,</span> <span\
  \ m=\"3895190\">but</span> <span m=\"3896510\">if</span> <span m=\"3897110\">some</span>\
  \ <span m=\"3897650\">element</span> <span m=\"3898130\">of</span> <span m=\"3898640\"\
  >x</span> <span m=\"3899090\">was</span> <span m=\"3899360\">already</span> <span\
  \ m=\"3899840\">here,</span> <span m=\"3900890\">I</span> <span m=\"3901250\">take</span>\
  \ <span m=\"3901610\">it</span> <span m=\"3901730\">out.</span> <span m=\"3903340\"\
  >So</span> <span m=\"3903470\">here</span> <span m=\"3903950\">is</span> <span m=\"\
  3906460\">x</span> <span m=\"3906790\">plus</span> <span m=\"3907450\">C</span>\
  \ <span m=\"3908200\">prime.</span> <span m=\"3909400\">And</span> <span m=\"3909820\"\
  >let's</span> <span m=\"3910060\">say</span> <span m=\"3910270\">this</span> <span\
  \ m=\"3910570\">set is</span> <span m=\"3911050\">x.</span> <span m=\"3913270\"\
  >This</span> <span m=\"3913490\">W</span> <span m=\"3913910\">then</span> <span\
  \ m=\"3914240\">would</span> <span m=\"3914390\">there</span> <span m=\"3914570\"\
  >be</span> <span m=\"3914780\">their</span> <span m=\"3914930\">intersection.</span></p><p><span\
  \ m=\"3916850\">So</span> <span m=\"3917060\">now</span> <span m=\"3917870\">x</span>\
  \ <span m=\"3918170\">minus</span> <span m=\"3918590\">W</span> <span m=\"3918980\"\
  >is</span> <span m=\"3919190\">just</span> <span m=\"3919520\">this</span> <span\
  \ m=\"3919670\">set.</span> <span m=\"3920520\">So it's</span> <span m=\"3920980\"\
  >a</span> <span m=\"3921050\">disjoined</span> <span m=\"3921470\">union.</span>\
  \ <span m=\"3922516\">So the</span> <span m=\"3922930\">points</span> <span m=\"\
  3923170\">are,</span> <span m=\"3923230\">here,</span> <span m=\"3923310\">you're</span>\
  \ <span m=\"3923660\">adding</span> <span m=\"3923930\">single</span> <span m=\"\
  3924320\">elements,</span> <span m=\"3924740\">where there,</span> <span m=\"3925030\"\
  >you're</span> <span m=\"3925190\">adding</span> <span m=\"3925430\">some</span>\
  \ <span m=\"3925610\">sets.</span> <span m=\"3925930\">So</span> <span m=\"3926000\"\
  >you</span> <span m=\"3926060\">cannot</span> <span m=\"3926810\">necessarily</span>\
  \ <span m=\"3927290\">take</span> <span m=\"3927530\">a</span> <span m=\"3927680\"\
  >whole</span> <span m=\"3929210\">partition,</span> <span m=\"3929810\">necessarily.</span>\
  \ <span m=\"3930350\">But</span> <span m=\"3930785\">here</span> <span m=\"3931040\"\
  >it's</span> <span m=\"3931350\">OK.</span></p><p><span m=\"3936500\">It's</span>\
  \ <span m=\"3937850\">tricky.</span> <span m=\"3940410\">Yeah,</span> <span m=\"\
  3941130\">it's</span> <span m=\"3941280\">tricky. And</span> <span m=\"3941570\"\
  >you</span> <span m=\"3941650\">know,</span> <span m=\"3941850\">this</span> <span\
  \ m=\"3942060\">took</span> <span m=\"3942270\">a</span> <span m=\"3942330\">long</span>\
  \ <span m=\"3942540\">time</span> <span m=\"3942780\">for</span> <span m=\"3942900\"\
  >people</span> <span m=\"3943140\">to</span> <span m=\"3943230\">find.</span> <span\
  \ m=\"3943580\">It</span> <span m=\"3943740\">was</span> <span m=\"3944370\">found</span>\
  \ <span m=\"3945480\">about</span> <span m=\"3945780\">eight</span> <span m=\"3945960\"\
  >years</span> <span m=\"3946200\">ago.</span> <span m=\"3948090\">And</span> <span\
  \ m=\"3948760\">yeah,</span> <span m=\"3948960\">it</span> <span m=\"3949050\">was</span>\
  \ <span m=\"3949170\">surprising</span> <span m=\"3949800\">when</span> <span m=\"\
  3949920\">this</span> <span m=\"3950070\">proof</span> <span m=\"3950310\">was</span>\
  \ <span m=\"3950940\">discovered.</span> <span m=\"3951930\">People</span> <span\
  \ m=\"3952200\">did</span> <span m=\"3952320\">not</span> <span m=\"3952560\">expect</span>\
  \ <span m=\"3952880\">that</span> <span m=\"3953200\">this</span> <span m=\"3953400\"\
  >proof</span> <span m=\"3953640\">existed.</span></p><p><span m=\"3959270\">And</span>\
  \ <span m=\"3959480\">it's</span> <span m=\"3959630\">also</span> <span m=\"3959900\"\
  >tricky</span> <span m=\"3960260\">to</span> <span m=\"3960350\">get</span> <span\
  \ m=\"3960560\">right.</span> <span m=\"3960990\">So</span> <span m=\"3961190\"\
  >the</span> <span m=\"3961310\">details--</span> <span m=\"3961790\">I</span> <span\
  \ m=\"3962040\">do</span> <span m=\"3962270\">it</span> <span m=\"3962360\">slowly.</span>\
  \ <span m=\"3962900\">But</span> <span m=\"3963180\">the</span> <span m=\"3963860\"\
  >execution,</span> <span m=\"3964520\">like,</span> <span m=\"3964730\">the</span>\
  \ <span m=\"3964850\">order</span> <span m=\"3965060\">that</span> <span m=\"3965180\"\
  >you</span> <span m=\"3965300\">take</span> <span m=\"3965480\">the</span> <span\
  \ m=\"3965570\">minimalities</span> <span m=\"3966892\">is</span> <span m=\"3967330\"\
  >important.</span> <span m=\"3967850\">It's</span> <span m=\"3968000\">easy</span>\
  \ <span m=\"3968300\">to</span> <span m=\"3968390\">mess</span> <span m=\"3968660\"\
  >up</span> <span m=\"3968810\">this</span> <span m=\"3969010\">proof.</span> <span\
  \ m=\"3971760\">OK,</span> <span m=\"3972260\">any</span> <span m=\"3972500\">questions?</span></p><p><span\
  \ m=\"3975880\">Let</span> <span m=\"3976030\">me</span> <span m=\"3976150\">show</span>\
  \ <span m=\"3976450\">you,</span> <span m=\"3977860\">just</span> <span m=\"3978100\"\
  >as</span> <span m=\"3978280\">an</span> <span m=\"3978400\">aside,</span> <span\
  \ m=\"3979060\">an</span> <span m=\"3979210\">application</span> <span m=\"3980290\"\
  >of</span> <span m=\"3980850\">this</span> <span m=\"3981000\">key</span> <span\
  \ m=\"3981240\">lemma.</span> <span m=\"3983520\">So</span> <span m=\"3983850\"\
  >earlier</span> <span m=\"3984150\">we</span> <span m=\"3984270\">saw</span> <span\
  \ m=\"3984470\">Ruzsa's</span> <span m=\"3984840\">Triangle</span> <span m=\"3985200\"\
  >Inequality.</span> <span m=\"3986460\">And</span> <span m=\"3986580\">you</span>\
  \ <span m=\"3986670\">may</span> <span m=\"3986790\">wonder,</span> <span m=\"3987120\"\
  >what</span> <span m=\"3987300\">if</span> <span m=\"3987450\">you</span> <span\
  \ m=\"3988110\">replace</span> <span m=\"3988650\">the</span> <span m=\"3988770\"\
  >minus</span> <span m=\"3989310\">signs</span> <span m=\"3990000\">in</span> <span\
  \ m=\"3990150\">the</span> <span m=\"3990240\">theorem</span> <span m=\"3990630\"\
  >by</span> <span m=\"3990840\">plus</span> <span m=\"3991170\">signs?</span></p><p><span\
  \ m=\"3994530\">I</span> <span m=\"3994600\">mean,</span> <span m=\"3994780\">if</span>\
  \ <span m=\"3994900\">you</span> <span m=\"3995300\">replace</span> <span m=\"3995590\"\
  >the</span> <span m=\"3995650\">right-hand</span> <span m=\"3996130\">side,</span>\
  \ <span m=\"3996370\">the</span> <span m=\"3996430\">two</span> <span m=\"3996670\"\
  >pluses</span> <span m=\"3997200\">by</span> <span m=\"3997360\">minuses,</span>\
  \ <span m=\"3997840\">the</span> <span m=\"3997930\">same</span> <span m=\"3998200\"\
  >proof</span> <span m=\"3998440\">works.</span> <span m=\"4001340\">But</span> <span\
  \ m=\"4001410\">if</span> <span m=\"4001530\">you</span> <span m=\"4001620\">replace</span>\
  \ <span m=\"4002070\">all</span> <span m=\"4002250\">the</span> <span m=\"4002370\"\
  >minus</span> <span m=\"4002670\">signs</span> <span m=\"4003000\">by</span> <span\
  \ m=\"4003150\">plus</span> <span m=\"4003420\">signs,</span> <span m=\"4004180\"\
  >you</span> <span m=\"4004380\">see,</span> <span m=\"4004650\">the</span> <span\
  \ m=\"4004740\">proof</span> <span m=\"4005010\">doesn't</span> <span m=\"4005250\"\
  >work</span> <span m=\"4005430\">anymore.</span> <span m=\"4007860\">Just</span>\
  \ <span m=\"4008280\">give</span> <span m=\"4008470\">yourself</span> <span m=\"\
  4008860\">a</span> <span m=\"4008920\">moment</span> <span m=\"4009190\">to</span>\
  \ <span m=\"4009250\">convince</span> <span m=\"4009610\">yourself</span> <span\
  \ m=\"4009910\">that.</span> <span m=\"4010280\">If</span> <span m=\"4010460\">you</span>\
  \ <span m=\"4010570\">just</span> <span m=\"4010780\">replace</span> <span m=\"\
  4011320\">all</span> <span m=\"4011530\">the</span> <span m=\"4011650\">minus</span>\
  \ <span m=\"4012010\">signs</span> <span m=\"4012310\">by</span> <span m=\"4012460\"\
  >plus</span> <span m=\"4012730\">signs,</span> <span m=\"4013510\">it</span> <span\
  \ m=\"4013600\">doesn't</span> <span m=\"4013840\">work</span> <span m=\"4014050\"\
  >anymore,</span> <span m=\"4014410\">but</span> <span m=\"4014560\">it's</span>\
  \ <span m=\"4014710\">still</span> <span m=\"4014950\">true.</span></p><p><span\
  \ m=\"4019540\">So</span> <span m=\"4019600\">this</span> <span m=\"4019750\">is</span>\
  \ <span m=\"4019870\">more</span> <span m=\"4020050\">of</span> <span m=\"4020290\"\
  >an</span> <span m=\"4020540\">aside.</span> <span m=\"4021070\">We</span> <span\
  \ m=\"4021190\">will</span> <span m=\"4021340\">not</span> <span m=\"4021550\">use</span>\
  \ <span m=\"4021790\">it.</span> <span m=\"4022290\">But</span> <span m=\"4022910\"\
  >it's</span> <span m=\"4023050\">nice.</span> <span m=\"4023320\">It's</span> <span\
  \ m=\"4023470\">fun.</span> <span m=\"4024190\">So</span> <span m=\"4025710\">we</span>\
  \ <span m=\"4025860\">have</span> <span m=\"4026070\">the</span> <span m=\"4026160\"\
  >inequality</span> <span m=\"4026730\">A</span> <span m=\"4027840\">B</span> <span\
  \ m=\"4028080\">plus</span> <span m=\"4028380\">C</span> <span m=\"4029520\">bounded</span>\
  \ <span m=\"4030120\">by</span> <span m=\"4031320\">A</span> <span m=\"4031500\"\
  >plus</span> <span m=\"4031890\">B</span> <span m=\"4033122\">A</span> <span m=\"\
  4033610\">plus</span> <span m=\"4034040\">C.</span></p><p><span m=\"4037477\">So</span>\
  \ <span m=\"4037970\">hopefully</span> <span m=\"4038310\">you've</span> <span m=\"\
  4038480\">convince</span> <span m=\"4038840\">yourself</span> <span m=\"4039200\"\
  >that</span> <span m=\"4039320\">if</span> <span m=\"4039410\">you</span> <span\
  \ m=\"4039500\">follow</span> <span m=\"4039830\">our</span> <span m=\"4039950\"\
  >notes</span> <span m=\"4040280\">with</span> <span m=\"4040400\">the</span> <span\
  \ m=\"4040460\">previous</span> <span m=\"4041060\">proof,</span> <span m=\"4041540\"\
  >you</span> <span m=\"4041810\">are</span> <span m=\"4041990\">you're</span> <span\
  \ m=\"4042170\">not</span> <span m=\"4042350\">going</span> <span m=\"4042470\"\
  >to</span> <span m=\"4042560\">get it.</span> <span m=\"4043520\">You're</span>\
  \ <span m=\"4043670\">not</span> <span m=\"4043820\">going</span> <span m=\"4043940\"\
  >to</span> <span m=\"4044000\">prove</span> <span m=\"4044240\">this</span> <span\
  \ m=\"4045020\">this</span> <span m=\"4045230\">way.</span> <span m=\"4046340\"\
  >It's</span> <span m=\"4046460\">still</span> <span m=\"4046700\">true.</span> <span\
  \ m=\"4047010\">So</span> <span m=\"4047030\">how</span> <span m=\"4047180\">can</span>\
  \ <span m=\"4047330\">we</span> <span m=\"4047420\">prove</span> <span m=\"4047660\"\
  >it?</span> <span m=\"4048140\">So</span> <span m=\"4048440\">we</span> <span m=\"\
  4048740\">are</span> <span m=\"4048920\">going</span> <span m=\"4049060\">to</span>\
  \ <span m=\"4049190\">use</span> <span m=\"4049430\">the</span> <span m=\"4049550\"\
  >key</span> <span m=\"4049760\">lemma.</span> <span m=\"4051050\">So</span> <span\
  \ m=\"4053240\">first,</span> <span m=\"4053630\">the</span> <span m=\"4054620\"\
  >statement</span> <span m=\"4055100\">is</span> <span m=\"4055250\">trivial</span>\
  \ <span m=\"4056510\">if</span> <span m=\"4056960\">A</span> <span m=\"4057260\"\
  >is</span> <span m=\"4057650\">empty.</span> <span m=\"4059030\">So</span> <span\
  \ m=\"4059180\">let's</span> <span m=\"4059390\">assume</span> <span m=\"4059690\"\
  >that's</span> <span m=\"4059870\">not</span> <span m=\"4060050\">the</span> <span\
  \ m=\"4060140\">case.</span></p><p><span m=\"4063290\">Let</span> <span m=\"4064280\"\
  >x</span> <span m=\"4065060\">be</span> <span m=\"4065210\">a</span> <span m=\"\
  4065390\">subset</span> <span m=\"4065900\">of</span> <span m=\"4066050\">A</span>\
  \ <span m=\"4066950\">that</span> <span m=\"4067250\">minimizes</span> <span m=\"\
  4073870\">the</span> <span m=\"4073990\">expression</span> <span m=\"4074920\">or</span>\
  \ <span m=\"4075010\">the</span> <span m=\"4075100\">expansion</span> <span m=\"\
  4075670\">ratio</span> <span m=\"4078460\">x</span> <span m=\"4078970\">plus</span>\
  \ <span m=\"4080140\">B</span> <span m=\"4082330\">divided</span> <span m=\"4082660\"\
  >by</span> <span m=\"4082840\">x</span> <span m=\"4083860\">as</span> <span m=\"\
  4084360\">in</span> <span m=\"4084530\">the</span> <span m=\"4084610\">key</span>\
  \ <span m=\"4084820\">lemma.</span> <span m=\"4087490\">So</span> <span m=\"4087610\"\
  >let</span> <span m=\"4089380\">k</span> <span m=\"4090010\">denote</span> <span\
  \ m=\"4090570\">the</span> <span m=\"4090700\">quantity</span> <span m=\"4092350\"\
  >A</span> <span m=\"4092620\">plus</span> <span m=\"4093010\">B</span> <span m=\"\
  4094810\">over</span> <span m=\"4095050\">A,</span> <span m=\"4095220\">so</span>\
  \ <span m=\"4095380\">the</span> <span m=\"4095500\">expansion</span> <span m=\"\
  4096069\">ratio</span> <span m=\"4096520\">for</span> <span m=\"4096880\">A,</span>\
  \ <span m=\"4098054\">and</span> <span m=\"4100390\">k</span> <span m=\"4100630\"\
  >prime</span> <span m=\"4101680\">be</span> <span m=\"4101979\">the</span> <span\
  \ m=\"4102250\">expansion</span> <span m=\"4102880\">ratio</span> <span m=\"4103660\"\
  >for</span> <span m=\"4104170\">x.</span> <span m=\"4105720\">So</span> <span m=\"\
  4106120\">the</span> <span m=\"4106420\">quantities</span> <span m=\"4107109\">came</span>\
  \ <span m=\"4107380\">up</span> <span m=\"4107680\">earlier.</span> <span m=\"4109420\"\
  >k</span> <span m=\"4109630\">prime</span> <span m=\"4110170\">is,</span> <span\
  \ m=\"4111189\">at</span> <span m=\"4111370\">most,</span> <span m=\"4111790\">value\
  \ of</span> <span m=\"4112120\">k,</span> <span m=\"4112420\">because</span> <span\
  \ m=\"4112899\">of</span> <span m=\"4113050\">our</span> <span m=\"4113170\">choice</span>\
  \ <span m=\"4113620\">of</span> <span m=\"4113830\">x.</span></p><p><span m=\"4116560\"\
  >So</span> <span m=\"4119250\">the</span> <span m=\"4119350\">key</span> <span m=\"\
  4119569\">lemma</span> <span m=\"4120800\">gives</span> <span m=\"4125020\">x</span>\
  \ <span m=\"4126116\">B</span> <span m=\"4126490\">plus</span> <span m=\"4126729\"\
  >C--</span> <span m=\"4127069\">OK,</span> <span m=\"4127930\">and</span> <span\
  \ m=\"4128050\">this,</span> <span m=\"4128689\">it's</span> <span m=\"4128770\"\
  >really</span> <span m=\"4129069\">amazing</span> <span m=\"4129520\">what's</span>\
  \ <span m=\"4129700\">happening.</span> <span m=\"4130120\">It</span> <span m=\"\
  4130390\">seems</span> <span m=\"4130810\">like</span> <span m=\"4131380\">we're</span>\
  \ <span m=\"4131529\">just</span> <span m=\"4131680\">going</span> <span m=\"4131770\"\
  >to</span> <span m=\"4131890\">throw</span> <span m=\"4132310\">in</span> <span\
  \ m=\"4132490\">some</span> <span m=\"4132850\">extra</span> <span m=\"4133210\"\
  >stuff.</span> <span m=\"4135100\">So</span> <span m=\"4135590\">I'm</span> <span\
  \ m=\"4135740\">going</span> <span m=\"4135899\">to</span> <span m=\"4136240\">upper</span>\
  \ <span m=\"4136450\">bound it</span> <span m=\"4136779\">by</span> <span m=\"4137050\"\
  >x</span> <span m=\"4137350\">plus</span> <span m=\"4137680\">B</span> <span m=\"\
  4137890\">plus</span> <span m=\"4138220\">C.</span> <span m=\"4139105\">I'm</span>\
  \ <span m=\"4139479\">just</span> <span m=\"4139580\">going</span> <span m=\"4139670\"\
  >to</span> <span m=\"4139779\">throw</span> <span m=\"4140100\">in</span> <span\
  \ m=\"4140250\">some</span> <span m=\"4140490\">extra</span> <span m=\"4140850\"\
  >stuff.</span> <span m=\"4141870\">And</span> <span m=\"4141990\">then</span> <span\
  \ m=\"4143040\">by</span> <span m=\"4143689\">the</span> <span m=\"4143859\">lemma,</span>\
  \ <span m=\"4146069\">I</span> <span m=\"4146160\">can</span> <span m=\"4146370\"\
  >upper</span> <span m=\"4146580\">bound</span> <span m=\"4146819\">this</span> <span\
  \ m=\"4147000\">expression</span> <span m=\"4147540\">by</span> <span m=\"4147779\"\
  >k</span> <span m=\"4148649\">prime</span> <span m=\"4149819\">times</span> <span\
  \ m=\"4150730\">the</span> <span m=\"4151160\">size</span> <span m=\"4151560\">of</span>\
  \ <span m=\"4151710\">x</span> <span m=\"4152040\">plus</span> <span m=\"4152399\"\
  >C.</span> <span m=\"4155540\">So</span> <span m=\"4155819\">that's</span> <span\
  \ m=\"4156029\">what</span> <span m=\"4156149\">the</span> <span m=\"4156240\">lemma</span>\
  \ <span m=\"4156479\">gives</span> <span m=\"4156710\">you.</span></p><p><span m=\"\
  4158359\">And</span> <span m=\"4158930\">because</span> <span m=\"4159500\">x</span>\
  \ <span m=\"4159890\">is</span> <span m=\"4160040\">a</span> <span m=\"4160100\"\
  >subset</span> <span m=\"4160700\">of</span> <span m=\"4161060\">A,</span> <span\
  \ m=\"4162050\">we</span> <span m=\"4162200\">can</span> <span m=\"4162410\">upper</span>\
  \ <span m=\"4162649\">bound</span> <span m=\"4162919\">it</span> <span m=\"4163189\"\
  >by</span> <span m=\"4163370\">the</span> <span m=\"4163460\">size</span> <span\
  \ m=\"4163970\">of</span> <span m=\"4165470\">A</span> <span m=\"4165620\">plus</span>\
  \ <span m=\"4166010\">C.</span> <span m=\"4170050\">And</span> <span m=\"4170200\"\
  >now</span> <span m=\"4170470\">k</span> <span m=\"4170770\">prime</span> <span\
  \ m=\"4171220\">is,</span> <span m=\"4171370\">at</span> <span m=\"4171460\">most,</span>\
  \ <span m=\"4172200\">the</span> <span m=\"4172270\">size</span> <span m=\"4172750\"\
  >of</span> <span m=\"4172960\">k.</span> <span m=\"4174380\">k</span> <span m=\"\
  4174880\">prime is, at</span> <span m=\"4175330\">most,</span> <span m=\"4175600\"\
  >k.</span> <span m=\"4176520\">So you</span> <span m=\"4176859\">have</span> <span\
  \ m=\"4177170\">that.</span></p><p><span m=\"4178529\">But</span> <span m=\"4178800\"\
  >now</span> <span m=\"4178930\">look</span> <span m=\"4179109\">at</span> <span\
  \ m=\"4179200\">what</span> <span m=\"4179319\">the</span> <span m=\"4179410\">definition</span>\
  \ <span m=\"4179694\">of</span> <span m=\"4179979\">k</span> <span m=\"4180069\"\
  >is.</span> <span m=\"4188139\">And</span> <span m=\"4188383\">that's</span> <span\
  \ m=\"4188627\">it.</span> <span m=\"4195480\">So</span> <span m=\"4195720\">that's</span>\
  \ <span m=\"4196320\">how</span> <span m=\"4196440\">you</span> <span m=\"4196530\"\
  >can</span> <span m=\"4196680\">prove</span> <span m=\"4197100\">this</span> <span\
  \ m=\"4197850\">harder</span> <span m=\"4198300\">version</span> <span m=\"4198780\"\
  >of</span> <span m=\"4198900\">Ruzsa's</span> <span m=\"4199260\">Triangle</span>\
  \ <span m=\"4199710\">Inequality,</span> <span m=\"4201600\">Yes,</span> <span m=\"\
  4202020\">question?</span></p><p><span m=\"4203800\">AUDIENCE:</span> <span m=\"\
  4203963\">Are</span> <span m=\"4204126\">there</span> <span m=\"4204290\">equality</span>\
  \ <span m=\"4204780\">cases</span> <span m=\"4205270\">for this?</span></p><p><span\
  \ m=\"4206740\">YUFEI ZHAO:</span> <span m=\"4206903\">All</span> <span m=\"4207066\"\
  >right,</span> <span m=\"4207230\">question,</span> <span m=\"4207510\">are</span>\
  \ <span m=\"4207640\">there</span> <span m=\"4207860\">equality</span> <span m=\"\
  4208430\">cases</span> <span m=\"4208790\">for</span> <span m=\"4208940\">this?</span>\
  \ <span m=\"4209130\">Yes,</span> <span m=\"4209340\">so</span> <span m=\"4209600\"\
  >I</span> <span m=\"4209660\">mean,</span> <span m=\"4209750\">if</span> <span m=\"\
  4209840\">you're</span> <span m=\"4210020\">in</span> <span m=\"4210200\">a</span>\
  \ <span m=\"4210740\">subgroup,</span> <span m=\"4211640\">then</span> <span m=\"\
  4212060\">all</span> <span m=\"4212270\">things</span> <span m=\"4212780\">are</span>\
  \ <span m=\"4212900\">equal,</span> <span m=\"4214160\">although,</span> <span m=\"\
  4214850\">if</span> <span m=\"4215360\">A,</span> <span m=\"4215870\">B,</span>\
  \ <span m=\"4216170\">and</span> <span m=\"4216290\">C</span> <span m=\"4216650\"\
  >are</span> <span m=\"4216830\">all</span> <span m=\"4217070\">the</span> <span\
  \ m=\"4217160\">same</span> <span m=\"4217550\">subgroup</span> <span m=\"4218480\"\
  >of</span> <span m=\"4218720\">some</span> <span m=\"4219170\">finite</span> <span\
  \ m=\"4219680\">obedient</span> <span m=\"4220100\">group.</span></p><p><span m=\"\
  4220310\">AUDIENCE:</span> <span m=\"4220425\">What</span> <span m=\"4220540\">if</span>\
  \ <span m=\"4220655\">you're</span> <span m=\"4221232\">working in</span> <span\
  \ m=\"4221693\">the integers?</span></p><p><span m=\"4222615\">YUFEI ZHAO:</span>\
  \ <span m=\"4222847\">Great,</span> <span m=\"4223080\">yeah, so</span> <span m=\"\
  4223250\">the</span> <span m=\"4223340\">question</span> <span m=\"4223580\">is,</span>\
  \ <span m=\"4223670\">what</span> <span m=\"4223880\">if</span> <span m=\"4223970\"\
  >you're</span> <span m=\"4224090\">working</span> <span m=\"4224480\">in</span>\
  \ <span m=\"4224650\">integers?</span> <span m=\"4227980\">That's</span> <span m=\"\
  4228250\">a</span> <span m=\"4228340\">good</span> <span m=\"4228610\">question.</span>\
  \ <span m=\"4229010\">I mean,</span> <span m=\"4229120\">you</span> <span m=\"4229210\"\
  >can</span> <span m=\"4229390\">suddenly</span> <span m=\"4229690\">get</span> <span\
  \ m=\"4229840\">expansion</span> <span m=\"4230410\">ratio</span> <span m=\"4230830\"\
  >of</span> <span m=\"4230980\">two</span> <span m=\"4231550\">if</span> <span m=\"\
  4231790\">you</span> <span m=\"4232660\">have--</span> <span m=\"4233400\">no,</span>\
  \ <span m=\"4233700\">OK.</span></p><p><span m=\"4236650\">Right,</span> <span m=\"\
  4237050\">yeah,</span> <span m=\"4237200\">so</span> <span m=\"4237320\">that's</span>\
  \ <span m=\"4237590\">a</span> <span m=\"4237950\">good</span> <span m=\"4238280\"\
  >question.</span> <span m=\"4239090\">Can</span> <span m=\"4239300\">you</span>\
  \ <span m=\"4239450\">get</span> <span m=\"4240350\">equality</span> <span m=\"\
  4240920\">cases?</span> <span m=\"4241430\">If</span> <span m=\"4241640\">you</span>\
  \ <span m=\"4242390\">set</span> <span m=\"4242810\">A,</span> <span m=\"4243050\"\
  >B,</span> <span m=\"4243410\">and</span> <span m=\"4243560\">C</span> <span m=\"\
  4244100\">to</span> <span m=\"4244430\">be</span> <span m=\"4246110\">sets</span>\
  \ <span m=\"4247640\">of</span> <span m=\"4247970\">very</span> <span m=\"4248360\"\
  >different</span> <span m=\"4248870\">sizes,</span> <span m=\"4250310\">AP</span>\
  \ <span m=\"4250430\">is</span> <span m=\"4250730\">a</span> <span m=\"4250790\"\
  >very</span> <span m=\"4251060\">different</span> <span m=\"4251330\">set.</span>\
  \ <span m=\"4251600\">Yes?</span></p><p><span m=\"4251860\">AUDIENCE:</span> <span\
  \ m=\"4252104\">If you set B being</span> <span m=\"4252348\">true for</span> <span\
  \ m=\"4252836\">the single</span> <span m=\"4253324\">element</span> <span m=\"\
  4253812\">and B and C</span> <span m=\"4254300\">to just</span> <span m=\"4254790\"\
  >be</span> <span m=\"4256485\">sets that</span> <span m=\"4256940\">have full</span>\
  \ <span m=\"4257395\">extension</span> <span m=\"4258305\">so that B plus</span>\
  \ <span m=\"4258760\">C is not</span> <span m=\"4259215\">[? B. ?]</span></p><p><span\
  \ m=\"4259670\">YUFEI ZHAO:</span> <span m=\"4259760\">Great,</span> <span m=\"\
  4260105\">yeah,</span> <span m=\"4260560\">so</span> <span m=\"4260710\">you</span>\
  \ <span m=\"4260800\">take</span> <span m=\"4261280\">A</span> <span m=\"4261490\"\
  >to</span> <span m=\"4261610\">be</span> <span m=\"4261790\">a</span> <span m=\"\
  4261850\">single-element</span> <span m=\"4262570\">set,</span> <span m=\"4263680\"\
  >then</span> <span m=\"4264670\">it</span> <span m=\"4264760\">could</span> <span\
  \ m=\"4264940\">be</span> <span m=\"4265090\">that</span> <span m=\"4265180\">B</span>\
  \ <span m=\"4265420\">plus</span> <span m=\"4265840\">C</span> <span m=\"4266110\"\
  >is</span> <span m=\"4266260\">the</span> <span m=\"4266320\">same</span> <span\
  \ m=\"4266680\">as</span> <span m=\"4266800\">the</span> <span m=\"4266860\">size\
  \ of</span> <span m=\"4267200\">B</span> <span m=\"4267790\">times</span> <span\
  \ m=\"4268060\">the</span> <span m=\"4268120\">size</span> <span m=\"4268420\">of</span>\
  \ <span m=\"4268510\">C</span> <span m=\"4269160\">if</span> <span m=\"4269290\"\
  >B</span> <span m=\"4269500\">and</span> <span m=\"4269620\">C</span> <span m=\"\
  4269890\">have</span> <span m=\"4270100\">no</span> <span m=\"4270370\">additive</span>\
  \ <span m=\"4270790\">interactions.</span> <span m=\"4276603\">Yeah?</span></p><p><span\
  \ m=\"4277530\">AUDIENCE:</span> <span m=\"4277590\">Are</span> <span m=\"4277650\"\
  >there</span> <span m=\"4277890\">other</span> <span m=\"4278100\">known</span>\
  \ <span m=\"4278322\">proofs</span> <span m=\"4278545\">of</span> <span m=\"4278990\"\
  >this</span> <span m=\"4279435\">that are</span> <span m=\"4280325\">less</span>\
  \ <span m=\"4280770\">involved?</span></p><p><span m=\"4281630\">YUFEI ZHAO:</span>\
  \ <span m=\"4281775\">OK,</span> <span m=\"4281920\">are</span> <span m=\"4282030\"\
  >there</span> <span m=\"4282160\">other</span> <span m=\"4282340\">known</span>\
  \ <span m=\"4282610\">proofs</span> <span m=\"4282880\">of this?</span> <span m=\"\
  4283210\">I</span> <span m=\"4283540\">don't</span> <span m=\"4283750\">know.</span>\
  \ <span m=\"4284020\">I'm</span> <span m=\"4284170\">not</span> <span m=\"4284380\"\
  >aware</span> <span m=\"4284650\">of</span> <span m=\"4284740\">other</span> <span\
  \ m=\"4284950\">proofs.</span> <span m=\"4285625\">It</span> <span m=\"4285970\"\
  >would</span> <span m=\"4286090\">be</span> <span m=\"4286180\">nice</span> <span\
  \ m=\"4286390\">to</span> <span m=\"4286720\">find</span> <span m=\"4286990\">a</span>\
  \ <span m=\"4287050\">different</span> <span m=\"4287320\">proof.</span> <span m=\"\
  4291570\">More</span> <span m=\"4291800\">questions?</span> <span m=\"4293771\"\
  >Yeah?</span></p><p><span m=\"4294268\">AUDIENCE:</span> <span m=\"4294433\">How</span>\
  \ <span m=\"4294598\">did</span> <span m=\"4294765\">come up</span> <span m=\"4295013\"\
  >with this?</span></p><p><span m=\"4296260\">YUFEI ZHAO:</span> <span m=\"4296350\"\
  >How</span> <span m=\"4296440\">did</span> <span m=\"4296560\">he</span> <span m=\"\
  4296650\">come</span> <span m=\"4296860\">up</span> <span m=\"4296950\">with</span>\
  \ <span m=\"4297110\">this? You know,</span> <span m=\"4297310\">Petridis</span>\
  \ <span m=\"4297820\">did</span> <span m=\"4298000\">a</span> <span m=\"4298060\"\
  >very</span> <span m=\"4298360\">long</span> <span m=\"4298710\">PhD.</span> <span\
  \ m=\"4299680\">He</span> <span m=\"4300190\">spent,</span> <span m=\"4300670\"\
  >I</span> <span m=\"4300730\">think,</span> <span m=\"4300910\">seven</span> <span\
  \ m=\"4301240\">or</span> <span m=\"4301330\">eight</span> <span m=\"4301510\">years</span>\
  \ <span m=\"4301790\">in his</span> <span m=\"4301940\">PhD.</span> <span m=\"4302530\"\
  >And</span> <span m=\"4302680\">he</span> <span m=\"4302940\">eventually</span>\
  \ <span m=\"4303400\">came</span> <span m=\"4303640\">up</span> <span m=\"4303760\"\
  >with</span> <span m=\"4303890\">this</span> <span m=\"4304030\">proof.</span> <span\
  \ m=\"4306820\">So</span> <span m=\"4307090\">he</span> <span m=\"4307190\">must</span>\
  \ <span m=\"4307420\">have</span> <span m=\"4307530\">thought</span> <span m=\"\
  4307770\">a</span> <span m=\"4307800\">lot</span> <span m=\"4308010\">about</span>\
  \ <span m=\"4308190\">this</span> <span m=\"4308340\">problem.</span></p><p><span\
  \ m=\"4313470\">But</span> <span m=\"4313730\">the</span> <span m=\"4313890\">already</span>\
  \ <span m=\"4314130\">proofs</span> <span m=\"4314410\">are</span> <span m=\"4314490\"\
  >still</span> <span m=\"4314700\">nice.</span> <span m=\"4315000\">The</span> <span\
  \ m=\"4315090\">earlier</span> <span m=\"4315300\">proofs,</span> <span m=\"4315630\"\
  >I</span> <span m=\"4315690\">think</span> <span m=\"4315930\">they</span> <span\
  \ m=\"4316010\">are</span> <span m=\"4316350\">worth</span> <span m=\"4316590\"\
  >looking</span> <span m=\"4316890\">at.</span> <span m=\"4317280\">They</span> <span\
  \ m=\"4317460\">are</span> <span m=\"4317700\">looking</span> <span m=\"4318030\"\
  >at</span> <span m=\"4318120\">expansion</span> <span m=\"4318720\">ratios</span>\
  \ <span m=\"4319200\">in</span> <span m=\"4319380\">graphs.</span> <span m=\"4320700\"\
  >So</span> <span m=\"4320820\">you</span> <span m=\"4320910\">take</span> <span\
  \ m=\"4321120\">a</span> <span m=\"4321240\">sequence</span> <span m=\"4321870\"\
  >of</span> <span m=\"4322410\">graphs,</span> <span m=\"4322830\">multi-partite</span>\
  \ <span m=\"4323400\">graphs.</span> <span m=\"4323690\">And</span> <span m=\"4323760\"\
  >you</span> <span m=\"4323850\">think</span> <span m=\"4324030\">about</span> <span\
  \ m=\"4324630\">expansion.</span> <span m=\"4325310\">And</span> <span m=\"4325360\"\
  >you</span> <span m=\"4325440\">think</span> <span m=\"4325650\">about</span> <span\
  \ m=\"4325860\">flows.</span></p><p><span m=\"4326960\">It's,</span> <span m=\"\
  4327300\">again,</span> <span m=\"4328080\">not</span> <span m=\"4328830\">easy</span>\
  \ <span m=\"4329190\">at</span> <span m=\"4329370\">all,</span> <span m=\"4330090\"\
  >but</span> <span m=\"4331170\">maybe</span> <span m=\"4331500\">more</span> <span\
  \ m=\"4331710\">motivated</span> <span m=\"4332310\">if</span> <span m=\"4332400\"\
  >you're</span> <span m=\"4332520\">used</span> <span m=\"4332730\">to</span> <span\
  \ m=\"4332820\">think</span> <span m=\"4333030\">about</span> <span m=\"4333900\"\
  >expansions</span> <span m=\"4334500\">and</span> <span m=\"4334590\">flows</span>\
  \ <span m=\"4335100\">in</span> <span m=\"4335220\">graphs.</span> <span m=\"4336960\"\
  >And</span> <span m=\"4337180\">this</span> <span m=\"4337360\">one</span> <span\
  \ m=\"4337890\">really</span> <span m=\"4338110\">distills</span> <span m=\"4338740\"\
  >the</span> <span m=\"4338860\">core</span> <span m=\"4339220\">ideas</span> <span\
  \ m=\"4340030\">of</span> <span m=\"4340180\">that</span> <span m=\"4340330\">proof,</span>\
  \ <span m=\"4341440\">but</span> <span m=\"4341890\">looks</span> <span m=\"4342970\"\
  >something</span> <span m=\"4343330\">you</span> <span m=\"4343390\">can</span>\
  \ <span m=\"4343510\">teach</span> <span m=\"4343880\">in</span> <span m=\"4343990\"\
  >half</span> <span m=\"4344230\">a</span> <span m=\"4344260\">lecture,</span> <span\
  \ m=\"4345040\">whereas</span> <span m=\"4346720\">before</span> <span m=\"4347050\"\
  >this</span> <span m=\"4347260\">proof</span> <span m=\"4347500\">came</span> <span\
  \ m=\"4347740\">about,</span> <span m=\"4348475\">I</span> <span m=\"4348850\">could</span>\
  \ <span m=\"4349060\">have taught</span> <span m=\"4349220\">the</span> <span m=\"\
  4349420\">proof,</span> <span m=\"4349660\">but</span> <span m=\"4349750\">most</span>\
  \ <span m=\"4349960\">likely,</span> <span m=\"4350290\">I</span> <span m=\"4350350\"\
  >would</span> <span m=\"4350470\">have</span> <span m=\"4350610\">just</span> <span\
  \ m=\"4350740\">skipped it.</span></p><p><span m=\"4355830\">To</span> <span m=\"\
  4356160\">just</span> <span m=\"4356370\">give</span> <span m=\"4356580\">you</span>\
  \ <span m=\"4357420\">a</span> <span m=\"4358230\">sense</span> <span m=\"4358560\"\
  >of</span> <span m=\"4358680\">what's</span> <span m=\"4359070\">coming</span> <span\
  \ m=\"4359430\">up</span> <span m=\"4359550\">ahead,</span> <span m=\"4360000\"\
  >so</span> <span m=\"4360180\">going</span> <span m=\"4360480\">forward,</span>\
  \ <span m=\"4362290\">the</span> <span m=\"4362340\">first</span> <span m=\"4362610\"\
  >thing</span> <span m=\"4362790\">we'll</span> <span m=\"4363030\">do</span> <span\
  \ m=\"4363600\">in</span> <span m=\"4363840\">the</span> <span m=\"4364050\">next</span>\
  \ <span m=\"4364380\">lecture</span> <span m=\"4365070\">is</span> <span m=\"4365490\"\
  >we'll</span> <span m=\"4365730\">show--</span> <span m=\"4366240\">we'll</span>\
  \ <span m=\"4366420\">see</span> <span m=\"4366660\">the</span> <span m=\"4366810\"\
  >proof</span> <span m=\"4367590\">of</span> <span m=\"4369030\">the</span> <span\
  \ m=\"4369200\">Freiman's</span> <span m=\"4370200\">theorem</span> <span m=\"4370890\"\
  >in</span> <span m=\"4371100\">the</span> <span m=\"4371270\">finite</span> <span\
  \ m=\"4371580\">field</span> <span m=\"4371910\">setting,</span> <span m=\"4372620\"\
  >so in</span> <span m=\"4373000\">F2</span> <span m=\"4373370\">to</span> <span\
  \ m=\"4373500\">the</span> <span m=\"4373650\">n.</span> <span m=\"4375750\">There\
  \ is</span> <span m=\"4376020\">one</span> <span m=\"4376170\">more</span> <span\
  \ m=\"4376320\">thing,</span> <span m=\"4376500\">one</span> <span m=\"4376720\"\
  >more</span> <span m=\"4377280\">very</span> <span m=\"4377520\">quick</span> <span\
  \ m=\"4377870\">lemma</span> <span m=\"4378610\">called the</span> <span m=\"4378990\"\
  >covering</span> <span m=\"4379440\">lemma,</span> <span m=\"4379560\">Ruzsa</span>\
  \ <span m=\"4379980\">are</span> <span m=\"4380040\">Covering</span> <span m=\"\
  4380400\">Lemma,</span> <span m=\"4380520\">that</span> <span m=\"4380740\">I</span>\
  \ <span m=\"4380780\">will</span> <span m=\"4380880\">tell</span> <span m=\"4381060\"\
  >you.</span> <span m=\"4381830\">And</span> <span m=\"4381930\">then</span> <span\
  \ m=\"4382050\">once</span> <span m=\"4382290\">we</span> <span m=\"4382410\">have</span>\
  \ <span m=\"4382560\">that,</span> <span m=\"4382710\">then</span> <span m=\"4382890\"\
  >we</span> <span m=\"4382980\">can</span> <span m=\"4383100\">prove</span> <span\
  \ m=\"4383910\">Freiman's</span> <span m=\"4384330\">theorem</span> <span m=\"4384660\"\
  >in</span> <span m=\"4384750\">the</span> <span m=\"4384840\">finite</span> <span\
  \ m=\"4385110\">field</span> <span m=\"4385350\">setting.</span></p><p><span m=\"\
  4387620\">But</span> <span m=\"4387810\">then</span> <span m=\"4387900\">moving</span>\
  \ <span m=\"4388190\">on</span> <span m=\"4388270\">to</span> <span m=\"4388400\"\
  >the</span> <span m=\"4388490\">integers,</span> <span m=\"4389540\">we'll</span>\
  \ <span m=\"4389660\">need</span> <span m=\"4389810\">to</span> <span m=\"4389900\"\
  >understand</span> <span m=\"4390980\">how</span> <span m=\"4392240\">to</span>\
  \ <span m=\"4393020\">think</span> <span m=\"4393530\">about</span> <span m=\"4393830\"\
  >the</span> <span m=\"4394580\">integers.</span> <span m=\"4396330\">Well,</span>\
  \ <span m=\"4396410\">if</span> <span m=\"4396620\">you</span> <span m=\"4396800\"\
  >start</span> <span m=\"4397070\">with</span> <span m=\"4397190\">a</span> <span\
  \ m=\"4397220\">subset</span> <span m=\"4397580\">of</span> <span m=\"4397640\"\
  >integers,</span> <span m=\"4398300\">they</span> <span m=\"4398570\">could,</span>\
  \ <span m=\"4401150\">even</span> <span m=\"4401360\">if</span> <span m=\"4401480\"\
  >you</span> <span m=\"4401540\">have</span> <span m=\"4401660\">a</span> <span m=\"\
  4401720\">small</span> <span m=\"4401990\">number</span> <span m=\"4402230\">of</span>\
  \ <span m=\"4402320\">elements,</span> <span m=\"4403130\">they</span> <span m=\"\
  4403370\">could</span> <span m=\"4403670\">be</span> <span m=\"4403850\">spread</span>\
  \ <span m=\"4404240\">out,</span> <span m=\"4404450\">really,</span> <span m=\"\
  4404720\">all</span> <span m=\"4404870\">over</span> <span m=\"4405080\">the</span>\
  \ <span m=\"4405170\">place.</span> <span m=\"4405970\">But</span> <span m=\"4406100\"\
  >because</span> <span m=\"4406400\">you</span> <span m=\"4406580\">only</span> <span\
  \ m=\"4406850\">care</span> <span m=\"4407180\">about</span> <span m=\"4407360\"\
  >the</span> <span m=\"4407630\">additive</span> <span m=\"4408050\">structure</span>\
  \ <span m=\"4408950\">within</span> <span m=\"4409310\">the</span> <span m=\"4409400\"\
  >integers,</span> <span m=\"4410630\">you</span> <span m=\"4410720\">can</span>\
  \ <span m=\"4410840\">try</span> <span m=\"4411080\">to</span> <span m=\"4411200\"\
  >model</span> <span m=\"4412400\">that</span> <span m=\"4412610\">very</span> <span\
  \ m=\"4412880\">spread-out</span> <span m=\"4413440\">set</span> <span m=\"4413660\"\
  >of</span> <span m=\"4413750\">integers</span> <span m=\"4414650\">to</span> <span\
  \ m=\"4414890\">something</span> <span m=\"4415310\">that</span> <span m=\"4415490\"\
  >is</span> <span m=\"4415610\">very</span> <span m=\"4415850\">compact.</span> <span\
  \ m=\"4416960\">So</span> <span m=\"4417210\">there is</span> <span m=\"4417350\"\
  >something</span> <span m=\"4417590\">called</span> <span m=\"4417720\">the</span>\
  \ <span m=\"4417800\">modeling</span> <span m=\"4418430\">lemma,</span> <span m=\"\
  4419180\">Ruzsa's</span> <span m=\"4419540\">Modeling</span> <span m=\"4419960\"\
  >Lemma,</span> <span m=\"4421370\">that</span> <span m=\"4421550\">we'll</span>\
  \ <span m=\"4421700\">see</span> <span m=\"4421940\">next</span> <span m=\"4422210\"\
  >time.</span> <span m=\"4422900\">And</span> <span m=\"4423000\">that</span> <span\
  \ m=\"4423110\">will</span> <span m=\"4423260\">play</span> <span m=\"4423530\"\
  >a</span> <span m=\"4423590\">pretty</span> <span m=\"4423830\">important</span>\
  \ <span m=\"4424220\">role.</span></p><p><span m=\"4427760\">Before</span> <span\
  \ m=\"4428330\">finishing</span> <span m=\"4428750\">off,</span> <span m=\"4429270\"\
  >I</span> <span m=\"4429470\">also</span> <span m=\"4429740\">want</span> <span\
  \ m=\"4429920\">to</span> <span m=\"4429980\">mention</span> <span m=\"4430400\"\
  >that</span> <span m=\"4431150\">Freiman</span> <span m=\"4431680\">in</span> <span\
  \ m=\"4431780\">his</span> <span m=\"4431960\">work,</span> <span m=\"4432230\"\
  >so</span> <span m=\"4432350\">he</span> <span m=\"4433370\">had</span> <span m=\"\
  4433580\">this</span> <span m=\"4433760\">result.</span> <span m=\"4434150\">And</span>\
  \ <span m=\"4434360\">he</span> <span m=\"4434450\">also</span> <span m=\"4434660\"\
  >wrote</span> <span m=\"4434860\">a</span> <span m=\"4434900\">book</span> <span\
  \ m=\"4436052\">I think</span> <span m=\"4436480\">called</span> <span m=\"4436800\"\
  ><i>The</i></span> <span m=\"4437240\"><i>Structural</i></span> <span m=\"4437870\"\
  ><i>Theory</i></span> <span m=\"4438290\"><i>of</i></span> <span m=\"4438570\"><i>Set</i></span>\
  \ <span m=\"4438890\"><i>Addition,</i></span> <span m=\"4439460\">or</span> <span\
  \ m=\"4439910\">something</span> <span m=\"4440180\">like</span> <span m=\"4440300\"\
  >that,</span> <span m=\"4441050\">that</span> <span m=\"4441980\">emphasized</span>\
  \ <span m=\"4442760\">this</span> <span m=\"4442970\">connection.</span> <span m=\"\
  4444350\">He</span> <span m=\"4444530\">tried</span> <span m=\"4444740\">to</span>\
  \ <span m=\"4444830\">draw</span> <span m=\"4445040\">this</span> <span m=\"4445190\"\
  >analogy</span> <span m=\"4446180\">sort of</span> <span m=\"4446570\">comparing</span>\
  \ <span m=\"4447200\">additive</span> <span m=\"4447560\">combinatorics</span> <span\
  \ m=\"4448850\">to</span> <span m=\"4450530\">geometry</span> <span m=\"4451340\"\
  >in</span> <span m=\"4451430\">the</span> <span m=\"4451490\">sense</span> <span\
  \ m=\"4451760\">of</span> <span m=\"4451880\">cline,</span> <span m=\"4452390\"\
  >where</span> <span m=\"4453200\">in</span> <span m=\"4453320\">order</span> <span\
  \ m=\"4453560\">to</span> <span m=\"4453680\">understand</span> <span m=\"4454400\"\
  >sets,</span> <span m=\"4454820\">you</span> <span m=\"4454910\">don't</span> <span\
  \ m=\"4455090\">think</span> <span m=\"4455300\">about</span> <span m=\"4455590\"\
  >sets.</span></p><p><span m=\"4455750\">You</span> <span m=\"4455960\">think</span>\
  \ <span m=\"4456140\">about</span> <span m=\"4456320\">maps</span> <span m=\"4456830\"\
  >between</span> <span m=\"4457160\">sets,</span> <span m=\"4457910\">which</span>\
  \ <span m=\"4458090\">was</span> <span m=\"4458540\">kind</span> <span m=\"4458690\"\
  >of</span> <span m=\"4458780\">an</span> <span m=\"4458870\">obscure</span> <span\
  \ m=\"4459380\">idea</span> <span m=\"4459680\">at</span> <span m=\"4459750\">the</span>\
  \ <span m=\"4459800\">time.</span> <span m=\"4460940\">But</span> <span m=\"4461360\"\
  >we'll</span> <span m=\"4461570\">see</span> <span m=\"4461780\">next</span> <span\
  \ m=\"4462050\">lecture</span> <span m=\"4462410\">that</span> <span m=\"4462590\"\
  >this</span> <span m=\"4462830\">actually</span> <span m=\"4463120\">is</span> <span\
  \ m=\"4463250\">a</span> <span m=\"4463310\">very</span> <span m=\"4463520\">powerful,</span>\
  \ <span m=\"4463805\">it's a</span> <span m=\"4464090\">very</span> <span m=\"4464240\"\
  >influential</span> <span m=\"4464900\">idea</span> <span m=\"4465650\">to</span>\
  \ <span m=\"4466010\">really</span> <span m=\"4466250\">think</span> <span m=\"\
  4466550\">about</span> <span m=\"4466870\">a</span> <span m=\"4467120\">sets</span>\
  \ <span m=\"4467480\">of</span> <span m=\"4467570\">integers</span> <span m=\"4468620\"\
  >under</span> <span m=\"4468830\">transformations</span> <span m=\"4469610\">that</span>\
  \ <span m=\"4469730\">only</span> <span m=\"4469970\">preserve</span> <span m=\"\
  4470410\">their</span> <span m=\"4470570\">additive</span> <span m=\"4470990\">structure.</span>\
  \ <span m=\"4472800\">So</span> <span m=\"4472910\">we'll</span> <span m=\"4473090\"\
  >see</span> <span m=\"4473270\">this</span> <span m=\"4473420\">next</span> <span\
  \ m=\"4473660\">time.</span></p>"
type: course
uid: c4fbceccd2daf74551610e6adcd67b87

---
None