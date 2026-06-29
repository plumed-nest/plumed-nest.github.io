**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lDkJoQ/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmmklqx:09127] *** Process received signal ***
[runnervmmklqx:09127] Signal: Aborted (6)
[runnervmmklqx:09127] Signal code:  (-6)
[runnervmmklqx:09127] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f426be45330]
[runnervmmklqx:09127] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f426be9eb2c]
[runnervmmklqx:09127] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f426be4527e]
[runnervmmklqx:09127] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f426be288ff]
[runnervmmklqx:09127] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f426c2a5ff5]
[runnervmmklqx:09127] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f426c2bb0da]
[runnervmmklqx:09127] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f426c2a5a55]
[runnervmmklqx:09127] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f426c2a5a6f]
[runnervmmklqx:09127] [ 8] plumed_master(+0x146dd)[0x55d9b405d6dd]
[runnervmmklqx:09127] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f426be2a1ca]
[runnervmmklqx:09127] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f426be2a28b]
[runnervmmklqx:09127] [11] plumed_master(+0x15365)[0x55d9b405e365]
[runnervmmklqx:09127] *** End of error message ***
</pre>
{% endraw %}
