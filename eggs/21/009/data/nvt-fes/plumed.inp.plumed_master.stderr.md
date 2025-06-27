**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
In file included from /home/runner/opt/include/plumed_master/bias/../core/../tools/Tools.h:27,
from /home/runner/opt/include/plumed_master/bias/../core/Action.h:28,
from /home/runner/opt/include/plumed_master/bias/../core/ActionWithValue.h:25,
from /home/runner/opt/include/plumed_master/bias/ReweightBase.h:25,
from ../codes/ReweightGeomFES.lyoXt5.cpp:22:
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:98: warning: ignoring ‘#pragma acc enter’ [-Wunknown-pragmas]
98 | #pragma acc enter data copyin(this[0:1], d, d[0:n*m-1])
|
/home/runner/opt/include/plumed_master/bias/../core/../tools/Tensor.h:102: warning: ignoring ‘#pragma acc exit’ [-Wunknown-pragmas]
102 | #pragma acc exit data delete( d[0:n*m-1], d, this[0:1])
|
In file included from ../codes/ReweightGeomFES.lyoXt5.cpp:24:
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
Fatal error: can't create plumed_mklib.kw9Uib/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.11.0-dev.so ../codes/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:66022] *** Process received signal ***
[pkrvmbietmlfzoi:66022] Signal: Aborted (6)
[pkrvmbietmlfzoi:66022] Signal code:  (-6)
[pkrvmbietmlfzoi:66022] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f06c7845330]
[pkrvmbietmlfzoi:66022] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f06c789eb2c]
[pkrvmbietmlfzoi:66022] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f06c784527e]
[pkrvmbietmlfzoi:66022] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06c78288ff]
[pkrvmbietmlfzoi:66022] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06c7ca5ff5]
[pkrvmbietmlfzoi:66022] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06c7cbb0da]
[pkrvmbietmlfzoi:66022] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06c7ca5a55]
[pkrvmbietmlfzoi:66022] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06c7ca5a6f]
[pkrvmbietmlfzoi:66022] [ 8] plumed_master(+0x146dd)[0x5603ad29c6dd]
[pkrvmbietmlfzoi:66022] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f06c782a1ca]
[pkrvmbietmlfzoi:66022] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f06c782a28b]
[pkrvmbietmlfzoi:66022] [11] plumed_master(+0x15365)[0x5603ad29d365]
[pkrvmbietmlfzoi:66022] *** End of error message ***
</pre>
{% endraw %}
