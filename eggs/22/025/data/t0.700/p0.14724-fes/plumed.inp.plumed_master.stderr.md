**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14724-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
In file included from /home/runner/opt/include/plumed_master/bias/../core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/bias/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/bias/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/bias/ReweightBase.h:25,
from ../../code/ReweightGeomFES.kwVaGD.cpp:22:
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from ../../code/ReweightGeomFES.kwVaGD.cpp:24:
/home/runner/opt/include/plumed_master/tools/Matrix.h:100: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
100 | #pragma acc enter data copyin(this[0:1],sz,data[0:sz])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:103: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
103 | #pragma acc exit data delete(data[0:sz],sz,this[0:1])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:117: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
117 | #pragma acc enter data copyin(this[0:1])
|
/home/runner/opt/include/plumed_master/tools/Matrix.h:123: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
123 | #pragma acc exit data delete( this[0:1])
|
Assembler messages:
Fatal error: can't create plumed_mklib.IBodYI/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[pkrvmpptgkbjq6m:09877] *** Process received signal ***
[pkrvmpptgkbjq6m:09877] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09877] Signal code:  (-6)
[pkrvmpptgkbjq6m:09877] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e9bc45330]
[pkrvmpptgkbjq6m:09877] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e9bc9eb2c]
[pkrvmpptgkbjq6m:09877] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e9bc4527e]
[pkrvmpptgkbjq6m:09877] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e9bc288ff]
[pkrvmpptgkbjq6m:09877] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e9c0a5ff5]
[pkrvmpptgkbjq6m:09877] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e9c0bb0da]
[pkrvmpptgkbjq6m:09877] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e9c0a5a55]
[pkrvmpptgkbjq6m:09877] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e9c0a5a6f]
[pkrvmpptgkbjq6m:09877] [ 8] plumed_master(+0x146dd)[0x55abcd2366dd]
[pkrvmpptgkbjq6m:09877] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e9bc2a1ca]
[pkrvmpptgkbjq6m:09877] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e9bc2a28b]
[pkrvmpptgkbjq6m:09877] [11] plumed_master(+0x15365)[0x55abcd237365]
[pkrvmpptgkbjq6m:09877] *** End of error message ***
</pre>
{% endraw %}
