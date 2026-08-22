**Project ID:** [plumID:26.011]({{ '/' | absolute_url }}eggs/26/011/)  
Stderr for source:  biased/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
coordination_multi.waCPcX.cpp: In member function ‘void PLMD::NeighborList::update(const std::vector<PLMD::VectorGeneric<3> >&)’:
coordination_multi.waCPcX.cpp:253:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
253 |   for(unsigned int i=0; i<tot_size/2; i++) {
|                         ~^~~~~~~~~~~
In file included from /usr/include/x86_64-linux-gnu/c++/13/bits/c++allocator.h:33,
from /usr/include/c++/13/bits/allocator.h:46,
from /usr/include/c++/13/bits/stl_tree.h:64,
from /usr/include/c++/13/map:62,
from /usr/lib/x86_64-linux-gnu/openmpi/include/openmpi/ompi/mpi/cxx/mpicxx.h:42,
from /usr/lib/x86_64-linux-gnu/openmpi/include/mpi.h:2911,
from /home/runner/opt/include/plumed/tools/Communicator.h:25,
from coordination_multi.waCPcX.cpp:25:
/usr/include/c++/13/bits/new_allocator.h: In instantiation of ‘void std::__new_allocator<_Tp>::construct(_Up*, _Args&& ...) [with _Up = PLMD::SwitchingFunction; _Args = {const PLMD::SwitchingFunction&}; _Tp = PLMD::SwitchingFunction]’:
/usr/include/c++/13/bits/alloc_traits.h:538:17:   required from ‘static void std::allocator_traits<std::allocator<_Tp1> >::construct(allocator_type&, _Up*, _Args&& ...) [with _Up = PLMD::SwitchingFunction; _Args = {const PLMD::SwitchingFunction&}; _Tp = PLMD::SwitchingFunction; allocator_type = std::allocator<PLMD::SwitchingFunction>]’
/usr/include/c++/13/bits/stl_vector.h:1286:30:   required from ‘void std::vector<_Tp, _Alloc>::push_back(const value_type&) [with _Tp = PLMD::SwitchingFunction; _Alloc = std::allocator<PLMD::SwitchingFunction>; value_type = PLMD::SwitchingFunction]’
coordination_multi.waCPcX.cpp:455:34:   required from here
/usr/include/c++/13/bits/new_allocator.h:191:11: error: use of deleted function ‘PLMD::SwitchingFunction::SwitchingFunction(const PLMD::SwitchingFunction&)’
191 |         { ::new((void *)__p) _Up(std::forward<_Args>(__args)...); }
|           ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from coordination_multi.waCPcX.cpp:27:
/home/runner/opt/include/plumed/tools/SwitchingFunction.h:79:7: note: ‘PLMD::SwitchingFunction::SwitchingFunction(const PLMD::SwitchingFunction&)’ is implicitly deleted because the default definition would be ill-formed:
79 | class SwitchingFunction {
|       ^~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed/tools/SwitchingFunction.h:79:7: error: use of deleted function ‘std::unique_ptr<_Tp, _Dp>::unique_ptr(const std::unique_ptr<_Tp, _Dp>&) [with _Tp = PLMD::switchContainers::baseSwitch; _Dp = std::default_delete<PLMD::switchContainers::baseSwitch>]’
In file included from /usr/include/c++/13/memory:78,
from /home/runner/opt/include/plumed/tools/TypesafePtr.h:27,
from /home/runner/opt/include/plumed/tools/Communicator.h:29:
/usr/include/c++/13/bits/unique_ptr.h:522:7: note: declared here
522 |       unique_ptr(const unique_ptr&) = delete;
|       ^~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./coordination_multi.2.10.1.so coordination_multi.cpp

[runnervm76f27:04172] *** Process received signal ***
[runnervm76f27:04172] Signal: Aborted (6)
[runnervm76f27:04172] Signal code:  (-6)
[runnervm76f27:04172] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9607a45330]
[runnervm76f27:04172] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9607a9ec0c]
[runnervm76f27:04172] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9607a4527e]
[runnervm76f27:04172] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9607a288ff]
[runnervm76f27:04172] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9607ea5ff5]
[runnervm76f27:04172] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9607ebb0da]
[runnervm76f27:04172] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9607ea5a55]
[runnervm76f27:04172] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9607ea5a6f]
[runnervm76f27:04172] [ 8] plumed(+0x146dd)[0x55d942de56dd]
[runnervm76f27:04172] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9607a2a1ca]
[runnervm76f27:04172] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9607a2a28b]
[runnervm76f27:04172] [11] plumed(+0x15365)[0x55d942de6365]
[runnervm76f27:04172] *** End of error message ***
</pre>
{% endraw %}
