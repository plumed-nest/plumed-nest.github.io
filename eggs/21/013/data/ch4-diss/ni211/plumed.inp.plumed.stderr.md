**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.XfrSK4/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az1947-163:65812] *** Process received signal ***
[fv-az1947-163:65812] Signal: Aborted (6)
[fv-az1947-163:65812] Signal code:  (-6)
[fv-az1947-163:65812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f21ed445330]
[fv-az1947-163:65812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f21ed49eb2c]
[fv-az1947-163:65812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f21ed44527e]
[fv-az1947-163:65812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f21ed4288ff]
[fv-az1947-163:65812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f21ed8a5ff5]
[fv-az1947-163:65812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f21ed8bb0da]
[fv-az1947-163:65812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f21ed8a5a55]
[fv-az1947-163:65812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f21ed8a5a6f]
[fv-az1947-163:65812] [ 8] plumed(+0x146dd)[0x56269dae36dd]
[fv-az1947-163:65812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f21ed42a1ca]
[fv-az1947-163:65812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f21ed42a28b]
[fv-az1947-163:65812] [11] plumed(+0x15365)[0x56269dae4365]
[fv-az1947-163:65812] *** End of error message ***
</pre>
{% endraw %}
