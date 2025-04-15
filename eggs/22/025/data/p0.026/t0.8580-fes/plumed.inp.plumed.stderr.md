**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8580-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.W0pVw7/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az1719-82:62589] *** Process received signal ***
[fv-az1719-82:62589] Signal: Aborted (6)
[fv-az1719-82:62589] Signal code:  (-6)
[fv-az1719-82:62589] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f14da245330]
[fv-az1719-82:62589] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f14da29eb2c]
[fv-az1719-82:62589] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f14da24527e]
[fv-az1719-82:62589] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f14da2288ff]
[fv-az1719-82:62589] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f14da6a5ff5]
[fv-az1719-82:62589] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f14da6bb0da]
[fv-az1719-82:62589] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f14da6a5a55]
[fv-az1719-82:62589] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f14da6a5a6f]
[fv-az1719-82:62589] [ 8] plumed(+0x146dd)[0x558f3467d6dd]
[fv-az1719-82:62589] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f14da22a1ca]
[fv-az1719-82:62589] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f14da22a28b]
[fv-az1719-82:62589] [11] plumed(+0x15365)[0x558f3467e365]
[fv-az1719-82:62589] *** End of error message ***
</pre>
{% endraw %}
