**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.KcfQ92/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmkj6or:11780] *** Process received signal ***
[runnervmkj6or:11780] Signal: Aborted (6)
[runnervmkj6or:11780] Signal code:  (-6)
[runnervmkj6or:11780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2bbe45330]
[runnervmkj6or:11780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2bbe9eb2c]
[runnervmkj6or:11780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2bbe4527e]
[runnervmkj6or:11780] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2bbe288ff]
[runnervmkj6or:11780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2bc2a5ff5]
[runnervmkj6or:11780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2bc2bb0da]
[runnervmkj6or:11780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2bc2a5a55]
[runnervmkj6or:11780] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2bc2a5a6f]
[runnervmkj6or:11780] [ 8] plumed_master(+0x146dd)[0x5601b4b1e6dd]
[runnervmkj6or:11780] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2bbe2a1ca]
[runnervmkj6or:11780] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2bbe2a28b]
[runnervmkj6or:11780] [11] plumed_master(+0x15365)[0x5601b4b1f365]
[runnervmkj6or:11780] *** End of error message ***
</pre>
{% endraw %}
