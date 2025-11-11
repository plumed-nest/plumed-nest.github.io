**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.kvpbCd/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.0.so ../src/bias/ReweightGeomFES.cpp

[runnervmw9dnm:12601] *** Process received signal ***
[runnervmw9dnm:12601] Signal: Aborted (6)
[runnervmw9dnm:12601] Signal code:  (-6)
[runnervmw9dnm:12601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8448c45330]
[runnervmw9dnm:12601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8448c9eb2c]
[runnervmw9dnm:12601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8448c4527e]
[runnervmw9dnm:12601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8448c288ff]
[runnervmw9dnm:12601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84490a5ff5]
[runnervmw9dnm:12601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84490bb0da]
[runnervmw9dnm:12601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84490a5a55]
[runnervmw9dnm:12601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84490a5a6f]
[runnervmw9dnm:12601] [ 8] plumed(+0x146dd)[0x563da187f6dd]
[runnervmw9dnm:12601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8448c2a1ca]
[runnervmw9dnm:12601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8448c2a28b]
[runnervmw9dnm:12601] [11] plumed(+0x15365)[0x563da1880365]
[runnervmw9dnm:12601] *** End of error message ***
</pre>
{% endraw %}
