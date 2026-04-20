**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.QLZKu7/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmeorf1:08115] *** Process received signal ***
[runnervmeorf1:08115] Signal: Aborted (6)
[runnervmeorf1:08115] Signal code:  (-6)
[runnervmeorf1:08115] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d25645330]
[runnervmeorf1:08115] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d2569eb2c]
[runnervmeorf1:08115] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d2564527e]
[runnervmeorf1:08115] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d256288ff]
[runnervmeorf1:08115] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d25aa5ff5]
[runnervmeorf1:08115] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d25abb0da]
[runnervmeorf1:08115] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d25aa5a55]
[runnervmeorf1:08115] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d25aa5a6f]
[runnervmeorf1:08115] [ 8] plumed(+0x146dd)[0x5622a3ec26dd]
[runnervmeorf1:08115] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d2562a1ca]
[runnervmeorf1:08115] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d2562a28b]
[runnervmeorf1:08115] [11] plumed(+0x15365)[0x5622a3ec3365]
[runnervmeorf1:08115] *** End of error message ***
</pre>
{% endraw %}
