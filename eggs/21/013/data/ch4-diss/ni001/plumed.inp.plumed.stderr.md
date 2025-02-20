**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.rzCD1G/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az1691-811:10682] *** Process received signal ***
[fv-az1691-811:10682] Signal: Aborted (6)
[fv-az1691-811:10682] Signal code:  (-6)
[fv-az1691-811:10682] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2fcf645330]
[fv-az1691-811:10682] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2fcf69eb2c]
[fv-az1691-811:10682] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2fcf64527e]
[fv-az1691-811:10682] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2fcf6288ff]
[fv-az1691-811:10682] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2fcfaa5ff5]
[fv-az1691-811:10682] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2fcfabb0da]
[fv-az1691-811:10682] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2fcfaa5a55]
[fv-az1691-811:10682] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2fcfaa5a6f]
[fv-az1691-811:10682] [ 8] plumed(+0x146dd)[0x55ca540d86dd]
[fv-az1691-811:10682] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2fcf62a1ca]
[fv-az1691-811:10682] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2fcf62a28b]
[fv-az1691-811:10682] [11] plumed(+0x15365)[0x55ca540d9365]
[fv-az1691-811:10682] *** End of error message ***
</pre>
{% endraw %}
