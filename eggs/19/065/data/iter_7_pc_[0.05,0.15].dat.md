**Project ID:** [plumID:19.065]({{ '/' | absolute_url }}eggs/19/065/)  
**Source:** iter_7_pc_[0.05,0.15].dat  
**Originally used with PLUMED version:** 2.5  
**Stable:** [raw zipped stdout](iter_7_pc_[0.05,0.15].dat.plumed.stdout.txt.zip) - [stderr](iter_7_pc_[0.05,0.15].dat.plumed.stderr)  
**Master:** [raw zipped stdout](iter_7_pc_[0.05,0.15].dat.plumed_master.stdout.txt.zip) - [stderr](iter_7_pc_[0.05,0.15].dat.plumed_master.stderr)  

{% raw %}<pre>
com_1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=2,5,7,9,15,17,19
p_com: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=com_1
p_0: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=2
p_1: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=5
p_2: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=7
p_3: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=9
p_4: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=15
p_5: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=17
p_6: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=19
l_0_out_0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_0.x,p_com.x
l_0_out_1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_0.y,p_com.y
l_0_out_2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_0.z,p_com.z
l_0_out_3: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_1.x,p_com.x
l_0_out_4: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_1.y,p_com.y
l_0_out_5: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_1.z,p_com.z
l_0_out_6: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_2.x,p_com.x
l_0_out_7: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_2.y,p_com.y
l_0_out_8: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_2.z,p_com.z
l_0_out_9: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_3.x,p_com.x
l_0_out_10: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_3.y,p_com.y
l_0_out_11: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_3.z,p_com.z
l_0_out_12: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_4.x,p_com.x
l_0_out_13: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_4.y,p_com.y
l_0_out_14: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_4.z,p_com.z
l_0_out_15: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_5.x,p_com.x
l_0_out_16: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_5.y,p_com.y
l_0_out_17: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_5.z,p_com.z
l_0_out_18: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_6.x,p_com.x
l_0_out_19: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_6.y,p_com.y
l_0_out_20: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> PERIODIC=NO COEFFICIENTS=2.000000,-2.000000 ARG=p_6.z,p_com.z
ann_force: <a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a> ARG=l_0_out_0,l_0_out_1,l_0_out_2,l_0_out_3,l_0_out_4,l_0_out_5,l_0_out_6,l_0_out_7,l_0_out_8,l_0_out_9,l_0_out_10,l_0_out_11,l_0_out_12,l_0_out_13,l_0_out_14,l_0_out_15,l_0_out_16,l_0_out_17,l_0_out_18,l_0_out_19,l_0_out_20 NUM_LAYERS=3 NUM_NODES=21,40,2 ACTIVATIONS=Tanh,Tanh  WEIGHTS0=-0.87190646,-0.35895786,0.6734935,-0.098617539,0.58977705,-1.7560576,-0.30386522,-0.80165708,1.0848917,1.1095463,-0.35254228,-0.20279369,0.44963095,0.13809972,0.50299871,-0.17153315,0.0505323,-0.74330133,-0.50989425,0.55473781,0.37219325,-0.37553853,-0.3427414,-0.23449679,0.1975265,0.077907383,0.16573068,-0.30443421,-0.1503022,-0.32445511,0.32689738,0.17485735,0.40054914,-0.54637015,-0.25923678,-0.54388577,0.88409442,0.5346815,1.1082554,-0.045663312,-0.0038172731,0.055509765,-0.18748185,0.32288462,-0.46864945,-0.072195314,-0.15959074,0.46920615,-0.47442245,0.22593582,-0.32674485,0.20719916,-0.48443758,0.3239305,-0.5364638,0.67186391,-0.77936113,0.36555919,-0.89535564,1.2932738,-0.20755383,0.039871227,0.18303925,0.39799026,0.10254072,-0.15130408,-0.36323583,0.12506182,0.28408203,0.44846249,-0.28776839,0.19125418,-0.33718386,0.034271318,0.22928827,-0.43623245,-0.052142624,-0.013432872,0.035640202,-0.018756021,0.14580581,-0.42891178,0.076430991,-0.29332843,-0.34469885,-0.30509126,-0.010469919,0.10327983,0.40357527,-0.33106098,0.15323016,-0.35418868,-0.10956552,-0.31042808,0.3027744,0.51386881,0.062461138,0.63669866,0.11132568,0.22506703,0.0297039,-0.22830535,0.035165008,-0.10976423,0.0048042596,-0.51349097,-0.22245894,0.13063104,0.068828315,0.18867876,-0.028261466,-0.3304536,-0.44724065,0.023943009,-0.013428614,0.50763994,-0.20016356,-0.65155351,-0.79663444,0.25276813,1.0474524,0.81566834,-0.57038617,-0.20817219,0.21636935,-0.01822588,-0.44512466,-0.95288861,-0.5662294,-0.71666044,0.74813765,0.90246964,0.50669968,-0.77351761,-0.28286681,0.96306181,0.59323323,0.59131658,0.32022148,0.05012225,0.14961715,-0.40245003,-0.046750676,-0.26690942,0.01317307,0.12424764,-0.5330736,-0.22134431,0.054783698,0.40253952,0.057357341,-0.11858512,0.28901431,0.28630149,0.58075988,-0.37819493,0.48605874,0.1912117,-0.028076051,-0.20306779,-0.15009768,-0.75262219,0.24606694,-0.38358468,0.068115197,-0.31823167,-0.10257821,0.47584617,-0.34904689,0.20898989,0.58147901,-0.14754817,-0.068642825,0.18200655,0.0024220359,-0.068592817,-0.085062623,-0.14660238,0.32388452,0.045377217,0.12297723,-0.43553817,0.074160956,-0.015552534,0.068233646,0.17843018,-0.36337066,-0.092738517,0.28497422,0.30670318,-0.18422402,0.25124481,-0.0033980538,0.027567279,0.38182691,0.19403292,0.010032619,0.18101594,-0.036751263,0.043363068,0.097792082,-0.08912956,0.11005507,-0.23153493,0.089410454,-0.048042249,0.15741339,-0.21298045,0.39330256,-0.3973206,-0.15519424,0.65569949,0.089132264,-0.072587766,-0.18756916,0.00052186189,-0.34849298,0.65279967,0.010484475,0.1294505,-0.43391132,0.19413583,-0.45687428,0.54211932,0.053499177,0.26038143,-1.4835744,0.13642761,-0.17224467,0.16572398,-0.04525568,-0.8668474,-0.52013659,-0.74104112,1.9226329,-0.027589995,0.62686199,-1.0000374,-0.10736405,-0.43189931,-0.14411415,0.13766964,1.1886227,-0.46619004,0.57043523,0.29487109,0.26349699,-0.21997993,0.074765764,-0.13438495,0.25611308,-0.74788821,0.62612408,0.25641415,0.71691716,-1.2026258,0.9731853,-0.52973324,0.46454036,-0.61229402,0.54001778,-0.69173568,-0.8479296,-0.32663679,0.18755201,-0.13377824,0.18770061,0.17745253,0.11922753,-0.39647114,0.45714906,0.34292498,-0.22847579,0.074631579,0.94742721,0.80674636,0.92021382,-0.95085979,-1.3765492,-0.23150755,0.63448715,1.1579987,-0.4178443,-0.65658462,-0.21097307,-0.72781026,0.19149226,-0.34017295,0.58828259,-0.24034806,0.027983941,-0.037756745,0.68238086,-0.12331192,0.67061913,-0.35581812,0.2189251,0.023059241,-0.040455222,0.20724759,0.36689061,-0.013371632,-0.13496278,-0.46835417,0.081597053,-0.065395057,0.83667463,-0.26037624,-0.052437056,-0.4937405,0.14082538,-0.031869844,-0.48380694,0.0966269,0.062322535,-0.50978911,0.92003679,-0.17021661,0.82502604,-1.2440196,-1.240762,-0.81866163,0.76564032,0.3884432,-0.33685538,-0.88262749,0.64201897,0.23414007,-0.14439154,0.016094858,0.22365959,-0.13425103,-0.35013062,0.50304341,0.57518476,0.08032617,-0.74074608,-0.39315301,0.69459563,0.81217575,1.7663578,-0.46657541,-0.51692134,-1.0427588,0.54986155,0.094762094,-0.3541227,-1.017193,-0.18503587,-0.92543477,0.14877872,0.65762526,0.17775156,0.31696633,0.11964813,0.0099153053,0.70376796,-0.82615465,-0.11297955,0.70193541,0.82548016,1.0292876,-0.53601962,-0.34920186,-0.38716757,0.4286404,0.4022359,-0.4585163,0.1658747,0.32218003,0.20744096,0.080288351,-0.20969293,0.15904887,-0.24602339,-0.20717628,-0.20112267,-0.44737211,0.11755884,0.31447679,-0.17108458,0.017629351,0.018861245,-0.015142393,-0.2155253,-0.030476943,-0.1690872,0.33438918,0.14482099,0.023152597,0.30487722,-0.0027344604,-0.21631536,0.20222089,-0.44298303,0.23005429,0.25268626,-4.2143583e-06,0.049901776,-0.28013238,0.23711057,-0.25289318,0.066663481,0.17246307,-0.0042734575,0.090394437,-0.13393714,0.030389834,0.30693582,-0.091076642,0.10436955,0.12956297,0.047047161,0.19815807,-0.2080593,-0.039983332,-0.18388852,0.2025966,0.34359065,0.30043751,0.14026317,-0.17468716,-0.51878321,-0.23082101,1.3449758,-0.13614023,0.049049065,-0.8941564,0.29086024,-0.94730526,-0.36964381,0.33946073,-0.060226955,-0.093031168,-0.17954183,0.10358064,-0.10318455,0.3848024,0.35608187,0.18960582,0.32115233,0.12768438,-0.028009122,-0.15621367,-0.018929681,0.1355051,0.035231523,0.29597142,-0.022308853,-0.042079188,-0.22837159,0.046595514,-0.21870525,-0.30851051,0.0436056,0.27108762,0.15448047,0.051830504,0.033109404,-0.08307261,0.25837994,-0.33586901,0.22157443,0.65853983,0.43180478,-0.55331576,-0.43479627,-2.0803616,0.33940938,0.36974123,0.99703407,0.63667822,-0.94511127,0.23094293,-0.17569824,-0.15343623,0.49909025,-0.12705633,-0.051815413,-0.44468671,-0.48644999,0.41159827,0.23218761,-0.56231678,-0.72099173,0.0090281377,0.40493384,0.89134467,-0.78334367,-0.46148595,-0.11875205,0.63768262,0.50733477,0.37949392,0.54382336,-0.21006759,-0.41715261,0.61433309,0.43319809,-0.035637937,0.0025205752,0.29020384,-0.72186053,-0.13276199,0.10659949,-0.20747183,-0.25652951,0.049847689,0.11877254,0.074770115,-0.10185882,0.17987143,0.088847078,0.14425816,-0.10210451,-0.062761925,-0.33897784,0.16113925,0.23704928,-0.2019449,-0.044402771,-0.13425364,0.31761342,-0.10853029,-0.40202922,-0.0016119562,0.98588473,-0.64638704,0.32061592,0.019125309,1.5235333,-0.59311718,0.32150325,-1.0275183,-0.54153621,-0.79888487,-0.076103382,-0.1237634,-0.35207063,-0.63651949,0.51255906,0.23457514,0.3390902,0.53344899,0.50230575,-0.34201497,0.93372315,-0.34891734,0.37332097,0.17755468,1.6213689,-0.39717427,0.10564311,-0.97522944,-0.29480344,-0.48480198,0.32613021,-0.85555047,-0.26537251,-0.80445278,-0.19466373,0.47971049,0.50640047,-0.026390623,0.16379941,-0.032665029,0.89719993,-0.83386153,-0.00040736247,0.25259796,-0.17417809,0.11798943,-0.35930452,0.260043,-0.1980965,-0.22258359,0.49908948,0.18948206,0.15377511,0.56089962,0.022690363,0.34864855,-0.042656004,0.017194981,0.13591796,-0.73503053,0.078944087,-0.24654816,-0.7131021,-0.014207372,0.60314608,0.47710249,-0.48409697,0.19237581,-0.078422792,-0.24949747,-0.46370679,-0.067179747,-0.3905803,-0.21147402,0.087271437,0.20761664,-0.45579314,0.28151214,-0.03948009,0.2579338,0.17992143,0.3565779,0.15363285,-0.59717751,0.20740679,-0.54237103,-0.52578723,-0.09294571,0.31651884,0.17270377,0.24940956,-0.46733585,0.16812946,-0.54901606,0.098522007,0.39464468,0.21522957,0.36194652,-0.083053507,-0.17807013,-0.07783331,-0.25852284,0.73090148,0.23350531,0.14302763,-0.36147967,0.20519273,-0.045686401,0.12125395,0.020764966,-0.25653073,0.037056088,0.11594804,0.25804144,-0.20154601,-0.17507632,0.058436081,-0.18709463,-0.25229374,0.091346398,0.18932098,-0.26299486,0.015384142,0.0035107858,0.34601942,0.43390027,0.24216458,-0.29626966,-0.33303252,0.051110789,-0.037590478,0.53699994,0.1318327,-0.12847432,0.28448543,0.36919785,-0.22804296,-0.338456,0.053694494,0.086477719,0.0952916,0.076853149,0.12574056,-0.2939586,0.011252576,0.42119765,0.036940079,0.97365922,0.26256001,-0.16754743,-0.18730079,0.20570597,-0.1117477,-0.24523483,-0.20678748,-0.15698093,-0.10818577,0.092522621,-0.076282702,0.097924858,-0.0804324,0.21620685,-0.13478059,0.17400938,-0.079389222,-0.65289015,0.0069932346,-0.04032727,-0.506661,-0.22070885,0.11782748,-0.29449114,0.070721403,0.090878256,0.30533659,0.27457181,-0.022346694,0.43347588,0.13356891,0.17207074,0.51752073,0.19522923,0.0010523925,0.089837343,-0.24586374,-0.03316164,-0.67000771,-0.14616421,-0.49346575,0.29740715,0.3184981,0.19422008,-0.3185797,-0.12736902,-0.50011057,0.18688117,0.49381393,0.36226112,0.048639718,-0.80079466,-0.72345626,0.72887975,0.74488276,1.0250039,-0.91858137,-0.77418071,-0.30760658,0.10520841,-0.12150225,-0.82354683,-0.0084075471,-0.41388434,1.5595106,0.96023828,-0.43286183,-0.66702873,-0.79278868,-0.3219834,0.39940614,-0.62159747,0.43264863,-0.29155797,-0.49899665,0.41477028,0.20313068,0.43645555,-0.088960238,-0.52772695,0.27389193,0.16576907,-0.034422684,0.28448132,-0.31245553,0.073977835,0.021771872,-0.39851052,-0.088513613,0.14653829,0.30102161,0.13993968,-0.39040691,0.75556862,-0.030382231,-0.47444099,0.34066358,0.023923485,0.071939312,-0.23079127,-0.092920206,0.12920903,-0.37805888,-0.46968707,-0.29125008,0.45019686,0.85214591,0.43372288,0.36168316,-0.12333729,-0.38159278,-0.20419726,0.44283742,-0.23093568,-0.47100621,-0.016783066,-0.62246758,-0.34163201,-0.21100649,0.3533079,0.17274664,-0.55841833,0.72427183,0.41945812,-0.3631061,0.27918091,0.25095794,0.12504527,0.23198816,0.42711729,0.071940526,0.19689746,0.052577514,0.21796986,-0.04649087,0.07979124,-0.069465801,0.33092621,-0.23305328,0.28080076,0.016266074,0.20194685,0.31297198,-0.18963157,-0.35399568,0.19022328,-0.58662075,0.5227977,-2.0479622,0.29788157,0.097558424,0.87820137,-0.19968428,0.039184537,-0.089003883,-0.17260669,-0.70111418,0.17990483,0.0087882755,-0.35211822,-0.4744789,0.1501738,0.34448746,0.17520067,0.51004863,0.10048845 WEIGHTS1=-1.4474005,1.1819946,-1.1216192,-0.78940159,0.74331534,-0.70094603,1.4844064,-0.68026286,-0.30956447,-0.57882565,-0.92185426,-1.4708488,-1.5033315,1.7666799,0.01495132,-1.3712292,-1.5344423,1.2697771,0.23869789,0.27679789,1.2686948,-0.25254104,1.5645528,1.3473588,-0.12887225,1.4751998,1.3410094,0.49554497,0.89936876,1.0525565,-0.065281205,-0.68517572,-0.9086746,-0.071358778,1.384454,-1.5543636,0.15621638,1.114916,-0.30061147,-1.2312047,-0.41492951,-1.4374379,1.1775233,-0.030663291,-0.16742989,1.4901097,0.45259544,-0.70822793,0.47922879,-0.27493277,0.71017331,-0.4213244,-0.44132277,0.66437048,-0.99834532,-0.39298326,-0.47902557,0.44100299,-0.24771006,-0.076476745,0.41081291,0.14500928,0.49235889,0.36851448,0.24893951,0.48711738,0.45509917,0.90099543,0.34356743,0.22818552,0.50050259,-0.28115118,-0.50365281,1.0348394,-1.3265117,-0.47053593,-0.8013888,0.36564624,-0.5284642,-0.42365542  BIASES0=0.013272726,0.75947374,-0.84004831,0.2054745,-0.34946805,-0.74981421,-0.012437688,-0.34459928,0.40734801,0.47119159,-0.78124416,-0.017262509,0.021960158,-0.056078315,0.81130099,0.019598454,-0.055766586,-0.090533003,0.064011835,-0.1710671,-0.11246064,0.21226649,0.068915062,0.066867948,0.18253617,0.070858479,-0.014372328,0.63218772,0.025760019,-0.070957676,0.29687637,0.46496901,0.68898129,0.62569374,0.83857441,0.034256008,-0.63991833,-0.011385996,0.39885962,0.099278286 BIASES1=-1.9012924,2.4299307
restraint: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_s_t_r_a_i_n_t.html">RESTRAINT</a> ARG=ann_force.node-0,ann_force.node-1 AT=0.05,0.15 KAPPA=3000,3000
</pre>{% endraw %}