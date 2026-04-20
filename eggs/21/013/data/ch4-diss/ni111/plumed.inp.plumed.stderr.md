**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.W8Fkg6/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmeorf1:08202] *** Process received signal ***
[runnervmeorf1:08202] Signal: Aborted (6)
[runnervmeorf1:08202] Signal code:  (-6)
[runnervmeorf1:08202] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efff9645330]
[runnervmeorf1:08202] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efff969eb2c]
[runnervmeorf1:08202] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efff964527e]
[runnervmeorf1:08202] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efff96288ff]
[runnervmeorf1:08202] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efff9aa5ff5]
[runnervmeorf1:08202] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efff9abb0da]
[runnervmeorf1:08202] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efff9aa5a55]
[runnervmeorf1:08202] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efff9aa5a6f]
[runnervmeorf1:08202] [ 8] plumed(+0x146dd)[0x5555d32826dd]
[runnervmeorf1:08202] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efff962a1ca]
[runnervmeorf1:08202] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efff962a28b]
[runnervmeorf1:08202] [11] plumed(+0x15365)[0x5555d3283365]
[runnervmeorf1:08202] *** End of error message ***
</pre>
{% endraw %}
