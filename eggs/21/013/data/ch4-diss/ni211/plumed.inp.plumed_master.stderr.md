**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.yBHkEk/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmgx7h7:09930] *** Process received signal ***
[runnervmgx7h7:09930] Signal: Aborted (6)
[runnervmgx7h7:09930] Signal code:  (-6)
[runnervmgx7h7:09930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1025645330]
[runnervmgx7h7:09930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f102569ec0c]
[runnervmgx7h7:09930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f102564527e]
[runnervmgx7h7:09930] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10256288ff]
[runnervmgx7h7:09930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1025aa5ff5]
[runnervmgx7h7:09930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1025abb0da]
[runnervmgx7h7:09930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1025aa5a55]
[runnervmgx7h7:09930] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1025aa5a6f]
[runnervmgx7h7:09930] [ 8] plumed_master(+0x146dd)[0x56394e8046dd]
[runnervmgx7h7:09930] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f102562a1ca]
[runnervmgx7h7:09930] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f102562a28b]
[runnervmgx7h7:09930] [11] plumed_master(+0x15365)[0x56394e805365]
[runnervmgx7h7:09930] *** End of error message ***
</pre>
{% endraw %}
