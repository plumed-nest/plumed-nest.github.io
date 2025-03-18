**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.svwJed/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az790-36:65801] *** Process received signal ***
[fv-az790-36:65801] Signal: Aborted (6)
[fv-az790-36:65801] Signal code:  (-6)
[fv-az790-36:65801] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb575e45330]
[fv-az790-36:65801] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb575e9eb2c]
[fv-az790-36:65801] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb575e4527e]
[fv-az790-36:65801] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb575e288ff]
[fv-az790-36:65801] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb5762a5ff5]
[fv-az790-36:65801] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb5762bb0da]
[fv-az790-36:65801] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb5762a5a55]
[fv-az790-36:65801] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb5762a5a6f]
[fv-az790-36:65801] [ 8] plumed(+0x146dd)[0x558d8dd706dd]
[fv-az790-36:65801] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb575e2a1ca]
[fv-az790-36:65801] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb575e2a28b]
[fv-az790-36:65801] [11] plumed(+0x15365)[0x558d8dd71365]
[fv-az790-36:65801] *** End of error message ***
</pre>
{% endraw %}
