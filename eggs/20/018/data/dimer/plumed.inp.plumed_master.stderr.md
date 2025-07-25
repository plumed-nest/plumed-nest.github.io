**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
In file included from /home/runner/opt/include/plumed_master/bias/../core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/bias/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/bias/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/bias/ReweightBase.h:25,
from ../src/bias/ReweightGeomFES.gb7oOY.cpp:22:
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from ../src/bias/ReweightGeomFES.gb7oOY.cpp:24:
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
Fatal error: can't create plumed_mklib.eqc4JK/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[pkrvmpptgkbjq6m:10459] *** Process received signal ***
[pkrvmpptgkbjq6m:10459] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10459] Signal code:  (-6)
[pkrvmpptgkbjq6m:10459] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a62a45330]
[pkrvmpptgkbjq6m:10459] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a62a9eb2c]
[pkrvmpptgkbjq6m:10459] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a62a4527e]
[pkrvmpptgkbjq6m:10459] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a62a288ff]
[pkrvmpptgkbjq6m:10459] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a62ea5ff5]
[pkrvmpptgkbjq6m:10459] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a62ebb0da]
[pkrvmpptgkbjq6m:10459] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a62ea5a55]
[pkrvmpptgkbjq6m:10459] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a62ea5a6f]
[pkrvmpptgkbjq6m:10459] [ 8] plumed_master(+0x146dd)[0x55f9d2f046dd]
[pkrvmpptgkbjq6m:10459] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a62a2a1ca]
[pkrvmpptgkbjq6m:10459] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a62a2a28b]
[pkrvmpptgkbjq6m:10459] [11] plumed_master(+0x15365)[0x55f9d2f05365]
[pkrvmpptgkbjq6m:10459] *** End of error message ***
</pre>
{% endraw %}
