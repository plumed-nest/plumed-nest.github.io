**Project ID:** [plumID:23.024]({{ '/' | absolute_url }}eggs/23/024/)  
Stderr for source:  examples/driverTests/plumed_Ar13.dat   
Download: [zipped raw stdout](plumed_Ar13.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Ar13.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
../../src/pines/PINES.yk0ylS.cpp: In static member function ‘static void PLMD::PINES::PINES::registerKeywords(PLMD::Keywords&)’:
../../src/pines/PINES.yk0ylS.cpp:158:3: error: ‘componentsAreNotOptional’ was not declared in this scope
158 |   componentsAreNotOptional(keys);
|   ^~~~~~~~~~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp: In constructor ‘PLMD::PINES::PINES::PINES(const PLMD::ActionOptions&)’:
../../src/pines/PINES.yk0ylS.cpp:356:69: warning: ‘bool PLMD::PlumedMain::DeprecatedAtoms::usingNaturalUnits() const’ is deprecated: Use Action::usingNaturalUnits(). [-Wdeprecated-declarations]
356 |     mypdb.readFromFilepointer(fp,plumed.getAtoms().usingNaturalUnits(),0.1/atoms.getUnits().getLength());
|                                  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
In file included from ../../src/pines/PINES.yk0ylS.cpp:19:
/home/runner/opt/include/plumed/core/PlumedMain.h:109:10: note: declared here
109 |     bool usingNaturalUnits() const ;
|          ^~~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:356:76: error: ‘atoms’ was not declared in this scope; did you mean ‘Atoms’?
356 |     mypdb.readFromFilepointer(fp,plumed.getAtoms().usingNaturalUnits(),0.1/atoms.getUnits().getLength());
|                                                                            ^~~~~
|                                                                            Atoms
../../src/pines/PINES.yk0ylS.cpp:379:14: warning: comparison of integer expressions of different signedness: ‘int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<unsigned int>, unsigned int>::value_type’ {aka ‘unsigned int’} [-Wsign-compare]
379 |       if(rind==Presind[j]) {
../../src/pines/PINES.yk0ylS.cpp:416:11: warning: unused variable ‘rind’ [-Wunused-variable]
416 |       int rind=mypdb.getResidueNumber(anum);
|           ^~~~
../../src/pines/PINES.yk0ylS.cpp:1012:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<std::vector<PLMD::VectorGeneric<3> > >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
1012 |   for (int i = 0; i < ann_deriv.size(); i++) {
|                   ~~^~~~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp: In member function ‘virtual void PLMD::PINES::PINES::prepare()’:
../../src/pines/PINES.yk0ylS.cpp:1090:11: warning: unused variable ‘buffer’ [-Wunused-variable]
1090 |       int buffer=10;
|           ^~~~~~
../../src/pines/PINES.yk0ylS.cpp: In member function ‘virtual void PLMD::PINES::PINES::calculate()’:
../../src/pines/PINES.yk0ylS.cpp:1337:12: error: invalid use of incomplete type ‘class PLMD::Communicator’
1337 |     stride=comm.Get_size();
|            ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1338:10: error: invalid use of incomplete type ‘class PLMD::Communicator’
1338 |     rank=comm.Get_rank();
|          ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1512:27: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
1512 |               if(sb_count > max_solv_atoms) {
|                  ~~~~~~~~~^~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1567:34: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
1567 |           if(nl_small[j]->size() >= max_solv_atoms) {
|              ~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1575:44: warning: comparison of integer expressions of different signedness: ‘std::vector<int>::size_type’ {aka ‘long unsigned int’} and ‘int’ [-Wsign-compare]
1575 |                 if(sb_count - A0[i].size() < max_solv_atoms) {
|                    ~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1589:25: error: invalid use of incomplete type ‘class PLMD::Communicator’
1589 |         if(!doserial && comm.initialized()) {
|                         ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1620:11: error: invalid use of incomplete type ‘class PLMD::Communicator’
1620 |           comm.Barrier();
|           ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1625:11: error: invalid use of incomplete type ‘class PLMD::Communicator’
1625 |           comm.Allgather(&dim,1,&Vdim[0],1);
|           ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1640:11: error: invalid use of incomplete type ‘class PLMD::Communicator’
1640 |           comm.Allgather(&OrdVec[0],Nprec,&OrdVecAll[0],Nprec);
|           ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1642:11: error: invalid use of incomplete type ‘class PLMD::Communicator’
1642 |           comm.Allgatherv(&Atom0F[0],Atom0F.size(),&Atom0FAll[0],&Vdim[0],&Vpos[0]);
|           ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1643:11: error: invalid use of incomplete type ‘class PLMD::Communicator’
1643 |           comm.Allgatherv(&Atom1F[0],Atom1F.size(),&Atom1FAll[0],&Vdim[0],&Vpos[0]);
|           ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1656:34: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
1656 |               for(unsigned m=0; m<OrdVecAll[i+l*Nprec]; m++) {
../../src/pines/PINES.yk0ylS.cpp:1668:32: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} [-Wsign-compare]
1668 |             for(unsigned m=0; m<OrdVec[i]; m++) {
../../src/pines/PINES.yk0ylS.cpp:1723:18: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
1723 |         if(limit > max_solv_atoms) {
|            ~~~~~~^~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1704:10: warning: unused variable ‘dosorting’ [-Wunused-variable]
1704 |     bool dosorting=dosort[j];
|          ^~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1801:18: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
1801 |         if(limit > max_solv_atoms) {
|            ~~~~~~^~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1826:16: warning: unused variable ‘tPINES’ [-Wunused-variable]
1826 |         double tPINES = sfs[j].calculate(dm*Fvol, dfunc);
|                ^~~~~~
../../src/pines/PINES.yk0ylS.cpp:1848:20: error: invalid use of incomplete type ‘class PLMD::Communicator’
1848 |     if (!serial && comm.initialized() ) {
|                    ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1856:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
1856 |       comm.Barrier();
|       ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1860:11: error: invalid use of incomplete type ‘class PLMD::Communicator’
1860 |           comm.Sum(cPINES[j][k]);
|           ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1861:27: error: invalid use of incomplete type ‘class PLMD::Communicator’
1861 |           cPINES[j][k] /= comm.Get_size();
|                           ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1870:15: error: invalid use of incomplete type ‘class PLMD::Communicator’
1870 |               comm.Sum(ann_deriv[i][j][k]);
|               ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1871:37: error: invalid use of incomplete type ‘class PLMD::Communicator’
1871 |               ann_deriv[i][j][k] /= comm.Get_size();
|                                     ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1877:7: error: invalid use of incomplete type ‘class PLMD::Communicator’
1877 |       comm.Sum(&m_virial[0][0],9);
|       ^~~~
In file included from /home/runner/opt/include/plumed/colvar/../core/../tools/OFile.h:25,
from /home/runner/opt/include/plumed/colvar/../core/../tools/Log.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Action.h:30,
from /home/runner/opt/include/plumed/colvar/../core/ActionAtomistic.h:25,
from /home/runner/opt/include/plumed/colvar/../core/Colvar.h:25,
from /home/runner/opt/include/plumed/colvar/Colvar.h:24,
from ../../src/pines/PINES.yk0ylS.cpp:17:
/home/runner/opt/include/plumed/colvar/../core/../tools/FileBase.h:29:7: note: forward declaration of ‘class PLMD::Communicator’
29 | class Communicator;
|       ^~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1902:18: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
1902 |       if( (limit > max_solv_atoms) && (solv_blocks != 0) ){
|            ~~~~~~^~~~~~~~~~~~~~~~
../../src/pines/PINES.yk0ylS.cpp:1771:8: warning: unused variable ‘Nder’ [-Wunused-variable]
1771 |   bool Nder=CompDer;
|        ^~~~
../../src/pines/PINES.yk0ylS.cpp:1772:8: warning: unused variable ‘Scalevol’ [-Wunused-variable]
1772 |   bool Scalevol=Svol;
|        ^~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../src/pines/PINES.2.10b.so ../../src/pines/PINES.cpp

[fv-az585-767:04730] *** Process received signal ***
[fv-az585-767:04730] Signal: Aborted (6)
[fv-az585-767:04730] Signal code:  (-6)
[fv-az585-767:04730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb6ddc42520]
[fv-az585-767:04730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb6ddc969fc]
[fv-az585-767:04730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb6ddc42476]
[fv-az585-767:04730] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb6ddc287f3]
[fv-az585-767:04730] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb6de0a2b9e]
[fv-az585-767:04730] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb6de0ae20c]
[fv-az585-767:04730] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb6de0ae277]
[fv-az585-767:04730] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb6de0ae52b]
[fv-az585-767:04730] [ 8] plumed(+0x14254)[0x5606af111254]
[fv-az585-767:04730] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb6ddc29d90]
[fv-az585-767:04730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb6ddc29e40]
[fv-az585-767:04730] [11] plumed(+0x14eb5)[0x5606af111eb5]
[fv-az585-767:04730] *** End of error message ***
</pre>
{% endraw %}
