**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8640-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.K76QM4/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmw9dnm:08259] *** Process received signal ***
[runnervmw9dnm:08259] Signal: Aborted (6)
[runnervmw9dnm:08259] Signal code:  (-6)
[runnervmw9dnm:08259] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5801445330]
[runnervmw9dnm:08259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f580149eb2c]
[runnervmw9dnm:08259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f580144527e]
[runnervmw9dnm:08259] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58014288ff]
[runnervmw9dnm:08259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58018a5ff5]
[runnervmw9dnm:08259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58018bb0da]
[runnervmw9dnm:08259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58018a5a55]
[runnervmw9dnm:08259] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58018a5a6f]
[runnervmw9dnm:08259] [ 8] plumed(+0x146dd)[0x562483a486dd]
[runnervmw9dnm:08259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f580142a1ca]
[runnervmw9dnm:08259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f580142a28b]
[runnervmw9dnm:08259] [11] plumed(+0x15365)[0x562483a49365]
[runnervmw9dnm:08259] *** End of error message ***
</pre>
{% endraw %}
