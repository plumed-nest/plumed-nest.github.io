**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.yDPZWx/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmxyh4eaekms:09645] *** Process received signal ***
[pkrvmxyh4eaekms:09645] Signal: Aborted (6)
[pkrvmxyh4eaekms:09645] Signal code:  (-6)
[pkrvmxyh4eaekms:09645] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff267045330]
[pkrvmxyh4eaekms:09645] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff26709eb2c]
[pkrvmxyh4eaekms:09645] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff26704527e]
[pkrvmxyh4eaekms:09645] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2670288ff]
[pkrvmxyh4eaekms:09645] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2674a5ff5]
[pkrvmxyh4eaekms:09645] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2674bb0da]
[pkrvmxyh4eaekms:09645] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2674a5a55]
[pkrvmxyh4eaekms:09645] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2674a5a6f]
[pkrvmxyh4eaekms:09645] [ 8] plumed(+0x146dd)[0x55dd5a25d6dd]
[pkrvmxyh4eaekms:09645] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff26702a1ca]
[pkrvmxyh4eaekms:09645] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff26702a28b]
[pkrvmxyh4eaekms:09645] [11] plumed(+0x15365)[0x55dd5a25e365]
[pkrvmxyh4eaekms:09645] *** End of error message ***
</pre>
{% endraw %}
