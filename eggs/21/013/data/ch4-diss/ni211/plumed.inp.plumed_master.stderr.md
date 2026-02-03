**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.9EGWfa/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmkj6or:12217] *** Process received signal ***
[runnervmkj6or:12217] Signal: Aborted (6)
[runnervmkj6or:12217] Signal code:  (-6)
[runnervmkj6or:12217] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c36845330]
[runnervmkj6or:12217] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c3689eb2c]
[runnervmkj6or:12217] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c3684527e]
[runnervmkj6or:12217] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c368288ff]
[runnervmkj6or:12217] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c36ca5ff5]
[runnervmkj6or:12217] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c36cbb0da]
[runnervmkj6or:12217] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c36ca5a55]
[runnervmkj6or:12217] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c36ca5a6f]
[runnervmkj6or:12217] [ 8] plumed_master(+0x146dd)[0x556456c816dd]
[runnervmkj6or:12217] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c3682a1ca]
[runnervmkj6or:12217] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c3682a28b]
[runnervmkj6or:12217] [11] plumed_master(+0x15365)[0x556456c82365]
[runnervmkj6or:12217] *** End of error message ***
</pre>
{% endraw %}
