**Project ID:** [plumID:22.039]({{ '/' | absolute_url }}eggs/22/039/)  
Stderr for source:  urea_plumed.dat   
Download: [zipped raw stdout](urea_plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](urea_plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
PairEntropy.M59N24.cpp: In member function ‘virtual void PLMD::colvar::PairEntropy::calculate()’:
PairEntropy.M59N24.cpp:264:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
264 |          if (minBin > (nhist-1)) minBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
PairEntropy.M59N24.cpp:266:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
266 |          if (maxBin > (nhist-1)) maxBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
ManyAngle.Ws9zZJ.cpp: In constructor ‘PLMD::colvar::ManyAngle::ManyAngle(const PLMD::ActionOptions&)’:
ManyAngle.Ws9zZJ.cpp:68:27: warning: ‘PLMD::colvar::ManyAngle::moment2’ will be initialized after [-Wreorder]
68 |   bool pbc, serial, mean, moment2;
|                           ^~~~~~~
ManyAngle.Ws9zZJ.cpp:68:13: warning:   ‘bool PLMD::colvar::ManyAngle::serial’ [-Wreorder]
68 |   bool pbc, serial, mean, moment2;
|             ^~~~~~
ManyAngle.Ws9zZJ.cpp:100:1: warning:   when initialized here [-Wreorder]
100 | ManyAngle::ManyAngle(const ActionOptions&ao):
| ^~~~~~~~~
ManyAngle.Ws9zZJ.cpp:124:3: warning: this ‘if’ clause does not guard... [-Wmisleading-indentation]
124 |   if(mean) addComponentWithDerivatives("mean"); componentIsNotPeriodic("mean"); moments[0]=getPntrToComponent("mean"); // (Z)
|   ^~
ManyAngle.Ws9zZJ.cpp:124:49: note: ...this statement, but the latter is misleadingly indented as if it were guarded by the ‘if’
124 |   if(mean) addComponentWithDerivatives("mean"); componentIsNotPeriodic("mean"); moments[0]=getPntrToComponent("mean"); // (Z)
|                                                 ^~~~~~~~~~~~~~~~~~~~~~
ManyAngle.Ws9zZJ.cpp:125:3: warning: this ‘if’ clause does not guard... [-Wmisleading-indentation]
125 |   if(moment2) addComponentWithDerivatives("moment2"); componentIsNotPeriodic("moment2"); moments[1]=getPntrToComponent("moment2"); // (Z)
|   ^~
ManyAngle.Ws9zZJ.cpp:125:55: note: ...this statement, but the latter is misleadingly indented as if it were guarded by the ‘if’
125 |   if(moment2) addComponentWithDerivatives("moment2"); componentIsNotPeriodic("moment2"); moments[1]=getPntrToComponent("moment2"); // (Z)
|                                                       ^~~~~~~~~~~~~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PAIRENTROPY LABEL=s ATOMS=C MAXR=0.6 SIGMA=0.05
Maybe a missing space or a typo?
[fv-az1153-362:68668] *** Process received signal ***
[fv-az1153-362:68668] Signal: Aborted (6)
[fv-az1153-362:68668] Signal code:  (-6)
[fv-az1153-362:68668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f03e0842520]
[fv-az1153-362:68668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f03e08969fc]
[fv-az1153-362:68668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f03e0842476]
[fv-az1153-362:68668] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f03e08287f3]
[fv-az1153-362:68668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f03e0ca4f26]
[fv-az1153-362:68668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f03e0cb6d9c]
[fv-az1153-362:68668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f03e0cb6e07]
[fv-az1153-362:68668] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f03e0cb70bb]
[fv-az1153-362:68668] [ 8] plumed_master(+0x12e7f)[0x560905fbce7f]
[fv-az1153-362:68668] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f03e0829d90]
[fv-az1153-362:68668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f03e0829e40]
[fv-az1153-362:68668] [11] plumed_master(+0x13115)[0x560905fbd115]
[fv-az1153-362:68668] *** End of error message ***
</pre>
{% endraw %}
