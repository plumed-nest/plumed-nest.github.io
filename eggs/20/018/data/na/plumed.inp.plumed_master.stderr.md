**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
PairEntropy.9xbrup.cpp: In constructor ‘PLMD::NeighborListParallel::NeighborListParallel(const std::vector<PLMD::AtomNumber>&, const std::vector<PLMD::AtomNumber>&, const bool&, const bool&, const PLMD::Pbc&, PLMD::Communicator&, PLMD::Log&, const double&, const bool&, const int&, const double&)’:
PairEntropy.9xbrup.cpp:65:8: warning: ‘PLMD::NeighborListParallel::mylog’ will be initialized after [-Wreorder]
65 |   Log& mylog;
|        ^~~~~
PairEntropy.9xbrup.cpp:54:21: warning:   ‘double PLMD::NeighborListParallel::skin_’ [-Wreorder]
54 |   double distance_, skin_;
|                     ^~~~~
PairEntropy.9xbrup.cpp:180:1: warning:   when initialized here [-Wreorder]
180 | NeighborListParallel::NeighborListParallel(const vector<AtomNumber>& list0, const vector<AtomNumber>& list1,
| ^~~~~~~~~~~~~~~~~~~~
PairEntropy.9xbrup.cpp:54:21: warning: ‘PLMD::NeighborListParallel::skin_’ will be initialized after [-Wreorder]
54 |   double distance_, skin_;
|                     ^~~~~
PairEntropy.9xbrup.cpp:42:8: warning:   ‘bool PLMD::NeighborListParallel::do_full_list_’ [-Wreorder]
42 |   bool do_full_list_;
|        ^~~~~~~~~~~~~
PairEntropy.9xbrup.cpp:180:1: warning:   when initialized here [-Wreorder]
180 | NeighborListParallel::NeighborListParallel(const vector<AtomNumber>& list0, const vector<AtomNumber>& list1,
| ^~~~~~~~~~~~~~~~~~~~
PairEntropy.9xbrup.cpp: In constructor ‘PLMD::NeighborListParallel::NeighborListParallel(const std::vector<PLMD::AtomNumber>&, const bool&, const PLMD::Pbc&, PLMD::Communicator&, PLMD::Log&, const double&, const bool&, const int&, const double&)’:
PairEntropy.9xbrup.cpp:65:8: warning: ‘PLMD::NeighborListParallel::mylog’ will be initialized after [-Wreorder]
65 |   Log& mylog;
|        ^~~~~
PairEntropy.9xbrup.cpp:54:21: warning:   ‘double PLMD::NeighborListParallel::skin_’ [-Wreorder]
54 |   double distance_, skin_;
|                     ^~~~~
PairEntropy.9xbrup.cpp:212:1: warning:   when initialized here [-Wreorder]
212 | NeighborListParallel::NeighborListParallel(const vector<AtomNumber>& list0, const bool& do_pbc,
| ^~~~~~~~~~~~~~~~~~~~
PairEntropy.9xbrup.cpp:54:21: warning: ‘PLMD::NeighborListParallel::skin_’ will be initialized after [-Wreorder]
54 |   double distance_, skin_;
|                     ^~~~~
PairEntropy.9xbrup.cpp:42:8: warning:   ‘bool PLMD::NeighborListParallel::do_full_list_’ [-Wreorder]
42 |   bool do_full_list_;
|        ^~~~~~~~~~~~~
PairEntropy.9xbrup.cpp:212:1: warning:   when initialized here [-Wreorder]
212 | NeighborListParallel::NeighborListParallel(const vector<AtomNumber>& list0, const bool& do_pbc,
| ^~~~~~~~~~~~~~~~~~~~
PairEntropy.9xbrup.cpp: In member function ‘void PLMD::NeighborListParallel::updateFullListWithLinkedList(const std::vector<PLMD::VectorGeneric<3> >&)’:
PairEntropy.9xbrup.cpp:313:47: warning: variable ‘atombin’ set but not used [-Wunused-but-set-variable]
313 |        unsigned atombinx, atombiny, atombinz, atombin;
|                                               ^~~~~~~
PairEntropy.9xbrup.cpp:337:47: warning: variable ‘atombin’ set but not used [-Wunused-but-set-variable]
337 |        unsigned atombinx, atombiny, atombinz, atombin;
|                                               ^~~~~~~
PairEntropy.9xbrup.cpp: In member function ‘void PLMD::NeighborListParallel::updateHalfListWithLinkedList(const std::vector<PLMD::VectorGeneric<3> >&)’:
PairEntropy.9xbrup.cpp:377:19: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
377 |              if (j>=i) continue;
|                  ~^~~
PairEntropy.9xbrup.cpp:371:47: warning: variable ‘atombin’ set but not used [-Wunused-but-set-variable]
371 |        unsigned atombinx, atombiny, atombinz, atombin;
|                                               ^~~~~~~
PairEntropy.9xbrup.cpp:395:47: warning: variable ‘atombin’ set but not used [-Wunused-but-set-variable]
395 |        unsigned atombinx, atombiny, atombinz, atombin;
|                                               ^~~~~~~
PairEntropy.9xbrup.cpp: In member function ‘void PLMD::NeighborListParallel::gatherStats(const std::vector<PLMD::VectorGeneric<3> >&)’:
PairEntropy.9xbrup.cpp:496:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
496 |   for(unsigned int i=0;i<mycomm.Get_size();i+=1) allNeighNum+=neighbors_ranks_[i];
|                        ~^~~~~~~~~~~~~~~~~~
PairEntropy.9xbrup.cpp: In member function ‘virtual void PLMD::colvar::PairEntropy::calculate()’:
PairEntropy.9xbrup.cpp:990:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
990 |            if (minBin > (nhist-1)) minBin=nhist-1;
|                ~~~~~~~^~~~~~~~~~~
PairEntropy.9xbrup.cpp:992:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
992 |            if (maxBin > (nhist-1)) maxBin=nhist-1;
|                ~~~~~~~^~~~~~~~~~~
PairEntropy.9xbrup.cpp:1032:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
1032 |            if (minBin > (nhist-1)) minBin=nhist-1;
|                ~~~~~~~^~~~~~~~~~~
PairEntropy.9xbrup.cpp:1034:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
1034 |            if (maxBin > (nhist-1)) maxBin=nhist-1;
|                ~~~~~~~^~~~~~~~~~~
PairEntropy.9xbrup.cpp:1062:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
1062 |            if (minBin > (nhist-1)) minBin=nhist-1;
|                ~~~~~~~^~~~~~~~~~~
PairEntropy.9xbrup.cpp:1064:23: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
1064 |            if (maxBin > (nhist-1)) maxBin=nhist-1;
|                ~~~~~~~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PAIRENTROPY ATOMS=1-250 MAXR=6.5 SIGMA=0.125 NHIST=130 LABEL=ss
Maybe a missing space or a typo?
[fv-az1200-632:72581] *** Process received signal ***
[fv-az1200-632:72581] Signal: Aborted (6)
[fv-az1200-632:72581] Signal code:  (-6)
[fv-az1200-632:72581] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbfd1642520]
[fv-az1200-632:72581] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbfd16969fc]
[fv-az1200-632:72581] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbfd1642476]
[fv-az1200-632:72581] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbfd16287f3]
[fv-az1200-632:72581] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fbfd1aa4f26]
[fv-az1200-632:72581] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fbfd1ab6d9c]
[fv-az1200-632:72581] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fbfd1ab6e07]
[fv-az1200-632:72581] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbfd1ab70bb]
[fv-az1200-632:72581] [ 8] plumed_master(+0x12e7f)[0x55aeff78ae7f]
[fv-az1200-632:72581] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbfd1629d90]
[fv-az1200-632:72581] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbfd1629e40]
[fv-az1200-632:72581] [11] plumed_master(+0x13115)[0x55aeff78b115]
[fv-az1200-632:72581] *** End of error message ***
</pre>
{% endraw %}
