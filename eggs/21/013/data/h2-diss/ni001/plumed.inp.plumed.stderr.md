**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.hVomk6/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmeorf1:07400] *** Process received signal ***
[runnervmeorf1:07400] Signal: Aborted (6)
[runnervmeorf1:07400] Signal code:  (-6)
[runnervmeorf1:07400] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f834ca45330]
[runnervmeorf1:07400] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f834ca9eb2c]
[runnervmeorf1:07400] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f834ca4527e]
[runnervmeorf1:07400] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f834ca288ff]
[runnervmeorf1:07400] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f834cea5ff5]
[runnervmeorf1:07400] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f834cebb0da]
[runnervmeorf1:07400] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f834cea5a55]
[runnervmeorf1:07400] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f834cea5a6f]
[runnervmeorf1:07400] [ 8] plumed(+0x146dd)[0x5652fccc36dd]
[runnervmeorf1:07400] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f834ca2a1ca]
[runnervmeorf1:07400] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f834ca2a28b]
[runnervmeorf1:07400] [11] plumed(+0x15365)[0x5652fccc4365]
[runnervmeorf1:07400] *** End of error message ***
</pre>
{% endraw %}
