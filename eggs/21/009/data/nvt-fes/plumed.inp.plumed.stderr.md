**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.BoKlws/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10b.so ../codes/ReweightGeomFES.cpp

[fv-az1947-163:66243] *** Process received signal ***
[fv-az1947-163:66243] Signal: Aborted (6)
[fv-az1947-163:66243] Signal code:  (-6)
[fv-az1947-163:66243] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5889c45330]
[fv-az1947-163:66243] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5889c9eb2c]
[fv-az1947-163:66243] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5889c4527e]
[fv-az1947-163:66243] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5889c288ff]
[fv-az1947-163:66243] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f588a0a5ff5]
[fv-az1947-163:66243] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f588a0bb0da]
[fv-az1947-163:66243] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f588a0a5a55]
[fv-az1947-163:66243] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f588a0a5a6f]
[fv-az1947-163:66243] [ 8] plumed(+0x146dd)[0x555f718786dd]
[fv-az1947-163:66243] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5889c2a1ca]
[fv-az1947-163:66243] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5889c2a28b]
[fv-az1947-163:66243] [11] plumed(+0x15365)[0x555f71879365]
[fv-az1947-163:66243] *** End of error message ***
</pre>
{% endraw %}
