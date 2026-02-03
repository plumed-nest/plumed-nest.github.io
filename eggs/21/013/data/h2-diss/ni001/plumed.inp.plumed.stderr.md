**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.diNcCP/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmkj6or:11200] *** Process received signal ***
[runnervmkj6or:11200] Signal: Aborted (6)
[runnervmkj6or:11200] Signal code:  (-6)
[runnervmkj6or:11200] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2abe045330]
[runnervmkj6or:11200] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2abe09eb2c]
[runnervmkj6or:11200] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2abe04527e]
[runnervmkj6or:11200] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2abe0288ff]
[runnervmkj6or:11200] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2abe4a5ff5]
[runnervmkj6or:11200] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2abe4bb0da]
[runnervmkj6or:11200] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2abe4a5a55]
[runnervmkj6or:11200] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2abe4a5a6f]
[runnervmkj6or:11200] [ 8] plumed(+0x146dd)[0x557c09dd16dd]
[runnervmkj6or:11200] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2abe02a1ca]
[runnervmkj6or:11200] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2abe02a28b]
[runnervmkj6or:11200] [11] plumed(+0x15365)[0x557c09dd2365]
[runnervmkj6or:11200] *** End of error message ***
</pre>
{% endraw %}
