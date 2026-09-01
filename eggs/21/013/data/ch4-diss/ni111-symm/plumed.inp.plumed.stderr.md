**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.pd1jTR/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.1.so ../../data/ReweightGeomFES.cpp

[runnervmgx7h7:09542] *** Process received signal ***
[runnervmgx7h7:09542] Signal: Aborted (6)
[runnervmgx7h7:09542] Signal code:  (-6)
[runnervmgx7h7:09542] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d83045330]
[runnervmgx7h7:09542] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d8309ec0c]
[runnervmgx7h7:09542] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d8304527e]
[runnervmgx7h7:09542] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d830288ff]
[runnervmgx7h7:09542] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d834a5ff5]
[runnervmgx7h7:09542] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d834bb0da]
[runnervmgx7h7:09542] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d834a5a55]
[runnervmgx7h7:09542] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d834a5a6f]
[runnervmgx7h7:09542] [ 8] plumed(+0x146dd)[0x564f83ba06dd]
[runnervmgx7h7:09542] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d8302a1ca]
[runnervmgx7h7:09542] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d8302a28b]
[runnervmgx7h7:09542] [11] plumed(+0x15365)[0x564f83ba1365]
[runnervmgx7h7:09542] *** End of error message ***
</pre>
{% endraw %}
