**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16222-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.aZcB46/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az805-507:10888] *** Process received signal ***
[fv-az805-507:10888] Signal: Aborted (6)
[fv-az805-507:10888] Signal code:  (-6)
[fv-az805-507:10888] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1dd0a45330]
[fv-az805-507:10888] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1dd0a9eb2c]
[fv-az805-507:10888] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1dd0a4527e]
[fv-az805-507:10888] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1dd0a288ff]
[fv-az805-507:10888] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1dd0ea5ff5]
[fv-az805-507:10888] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1dd0ebb0da]
[fv-az805-507:10888] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1dd0ea5a55]
[fv-az805-507:10888] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1dd0ea5a6f]
[fv-az805-507:10888] [ 8] plumed_master(+0x146dd)[0x55b0ac7526dd]
[fv-az805-507:10888] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1dd0a2a1ca]
[fv-az805-507:10888] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1dd0a2a28b]
[fv-az805-507:10888] [11] plumed_master(+0x15365)[0x55b0ac753365]
[fv-az805-507:10888] *** End of error message ***
</pre>
{% endraw %}
