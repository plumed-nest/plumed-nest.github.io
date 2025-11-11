**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.dtWwpB/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmw9dnm:10958] *** Process received signal ***
[runnervmw9dnm:10958] Signal: Aborted (6)
[runnervmw9dnm:10958] Signal code:  (-6)
[runnervmw9dnm:10958] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcfa445330]
[runnervmw9dnm:10958] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcfa49eb2c]
[runnervmw9dnm:10958] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcfa44527e]
[runnervmw9dnm:10958] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcfa4288ff]
[runnervmw9dnm:10958] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcfa8a5ff5]
[runnervmw9dnm:10958] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcfa8bb0da]
[runnervmw9dnm:10958] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcfa8a5a55]
[runnervmw9dnm:10958] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcfa8a5a6f]
[runnervmw9dnm:10958] [ 8] plumed(+0x146dd)[0x558ddb3446dd]
[runnervmw9dnm:10958] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcfa42a1ca]
[runnervmw9dnm:10958] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcfa42a28b]
[runnervmw9dnm:10958] [11] plumed(+0x15365)[0x558ddb345365]
[runnervmw9dnm:10958] *** End of error message ***
</pre>
{% endraw %}
