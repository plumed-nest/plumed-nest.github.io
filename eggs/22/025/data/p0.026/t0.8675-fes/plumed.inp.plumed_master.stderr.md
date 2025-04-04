**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.fN8njO/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az805-507:10202] *** Process received signal ***
[fv-az805-507:10202] Signal: Aborted (6)
[fv-az805-507:10202] Signal code:  (-6)
[fv-az805-507:10202] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4cff245330]
[fv-az805-507:10202] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4cff29eb2c]
[fv-az805-507:10202] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4cff24527e]
[fv-az805-507:10202] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4cff2288ff]
[fv-az805-507:10202] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4cff6a5ff5]
[fv-az805-507:10202] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4cff6bb0da]
[fv-az805-507:10202] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4cff6a5a55]
[fv-az805-507:10202] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4cff6a5a6f]
[fv-az805-507:10202] [ 8] plumed_master(+0x146dd)[0x56538e8926dd]
[fv-az805-507:10202] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4cff22a1ca]
[fv-az805-507:10202] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4cff22a28b]
[fv-az805-507:10202] [11] plumed_master(+0x15365)[0x56538e893365]
[fv-az805-507:10202] *** End of error message ***
</pre>
{% endraw %}
