**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.YnetBf/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmw9dnm:10608] *** Process received signal ***
[runnervmw9dnm:10608] Signal: Aborted (6)
[runnervmw9dnm:10608] Signal code:  (-6)
[runnervmw9dnm:10608] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a3fe45330]
[runnervmw9dnm:10608] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a3fe9eb2c]
[runnervmw9dnm:10608] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a3fe4527e]
[runnervmw9dnm:10608] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a3fe288ff]
[runnervmw9dnm:10608] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a402a5ff5]
[runnervmw9dnm:10608] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a402bb0da]
[runnervmw9dnm:10608] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a402a5a55]
[runnervmw9dnm:10608] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a402a5a6f]
[runnervmw9dnm:10608] [ 8] plumed(+0x146dd)[0x56167e3366dd]
[runnervmw9dnm:10608] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a3fe2a1ca]
[runnervmw9dnm:10608] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a3fe2a28b]
[runnervmw9dnm:10608] [11] plumed(+0x15365)[0x56167e337365]
[runnervmw9dnm:10608] *** End of error message ***
</pre>
{% endraw %}
