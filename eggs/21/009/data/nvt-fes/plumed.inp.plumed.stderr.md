**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.24IvJM/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.0.so ../codes/ReweightGeomFES.cpp

[runnervmkj6or:11485] *** Process received signal ***
[runnervmkj6or:11485] Signal: Aborted (6)
[runnervmkj6or:11485] Signal code:  (-6)
[runnervmkj6or:11485] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f75a4845330]
[runnervmkj6or:11485] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f75a489eb2c]
[runnervmkj6or:11485] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f75a484527e]
[runnervmkj6or:11485] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75a48288ff]
[runnervmkj6or:11485] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f75a4ca5ff5]
[runnervmkj6or:11485] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f75a4cbb0da]
[runnervmkj6or:11485] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f75a4ca5a55]
[runnervmkj6or:11485] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f75a4ca5a6f]
[runnervmkj6or:11485] [ 8] plumed(+0x146dd)[0x559db9a8e6dd]
[runnervmkj6or:11485] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f75a482a1ca]
[runnervmkj6or:11485] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f75a482a28b]
[runnervmkj6or:11485] [11] plumed(+0x15365)[0x559db9a8f365]
[runnervmkj6or:11485] *** End of error message ***
</pre>
{% endraw %}
