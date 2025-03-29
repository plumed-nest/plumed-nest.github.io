**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.NnRGlJ/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1947-163:65410] *** Process received signal ***
[fv-az1947-163:65410] Signal: Aborted (6)
[fv-az1947-163:65410] Signal code:  (-6)
[fv-az1947-163:65410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f898a045330]
[fv-az1947-163:65410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f898a09eb2c]
[fv-az1947-163:65410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f898a04527e]
[fv-az1947-163:65410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f898a0288ff]
[fv-az1947-163:65410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f898a4a5ff5]
[fv-az1947-163:65410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f898a4bb0da]
[fv-az1947-163:65410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f898a4a5a55]
[fv-az1947-163:65410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f898a4a5a6f]
[fv-az1947-163:65410] [ 8] plumed_master(+0x146dd)[0x55969519a6dd]
[fv-az1947-163:65410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f898a02a1ca]
[fv-az1947-163:65410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f898a02a28b]
[fv-az1947-163:65410] [11] plumed_master(+0x15365)[0x55969519b365]
[fv-az1947-163:65410] *** End of error message ***
</pre>
{% endraw %}
