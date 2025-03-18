**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8640-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.arbLta/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az1267-279:63379] *** Process received signal ***
[fv-az1267-279:63379] Signal: Aborted (6)
[fv-az1267-279:63379] Signal code:  (-6)
[fv-az1267-279:63379] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f49f4245330]
[fv-az1267-279:63379] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f49f429eb2c]
[fv-az1267-279:63379] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f49f424527e]
[fv-az1267-279:63379] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f49f42288ff]
[fv-az1267-279:63379] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f49f46a5ff5]
[fv-az1267-279:63379] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f49f46bb0da]
[fv-az1267-279:63379] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f49f46a5a55]
[fv-az1267-279:63379] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f49f46a5a6f]
[fv-az1267-279:63379] [ 8] plumed(+0x146dd)[0x561dc95ac6dd]
[fv-az1267-279:63379] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f49f422a1ca]
[fv-az1267-279:63379] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f49f422a28b]
[fv-az1267-279:63379] [11] plumed(+0x15365)[0x561dc95ad365]
[fv-az1267-279:63379] *** End of error message ***
</pre>
{% endraw %}
