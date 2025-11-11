**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.wBa0sU/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmw9dnm:08172] *** Process received signal ***
[runnervmw9dnm:08172] Signal: Aborted (6)
[runnervmw9dnm:08172] Signal code:  (-6)
[runnervmw9dnm:08172] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8affc45330]
[runnervmw9dnm:08172] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8affc9eb2c]
[runnervmw9dnm:08172] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8affc4527e]
[runnervmw9dnm:08172] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8affc288ff]
[runnervmw9dnm:08172] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b000a5ff5]
[runnervmw9dnm:08172] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b000bb0da]
[runnervmw9dnm:08172] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b000a5a55]
[runnervmw9dnm:08172] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b000a5a6f]
[runnervmw9dnm:08172] [ 8] plumed(+0x146dd)[0x557bd16ad6dd]
[runnervmw9dnm:08172] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8affc2a1ca]
[runnervmw9dnm:08172] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8affc2a28b]
[runnervmw9dnm:08172] [11] plumed(+0x15365)[0x557bd16ae365]
[runnervmw9dnm:08172] *** End of error message ***
</pre>
{% endraw %}
