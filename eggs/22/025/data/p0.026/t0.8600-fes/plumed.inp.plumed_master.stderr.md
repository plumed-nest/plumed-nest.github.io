**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.b8Wvac/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1267-279:63143] *** Process received signal ***
[fv-az1267-279:63143] Signal: Aborted (6)
[fv-az1267-279:63143] Signal code:  (-6)
[fv-az1267-279:63143] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9bf9645330]
[fv-az1267-279:63143] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9bf969eb2c]
[fv-az1267-279:63143] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9bf964527e]
[fv-az1267-279:63143] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9bf96288ff]
[fv-az1267-279:63143] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9bf9aa5ff5]
[fv-az1267-279:63143] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9bf9abb0da]
[fv-az1267-279:63143] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9bf9aa5a55]
[fv-az1267-279:63143] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9bf9aa5a6f]
[fv-az1267-279:63143] [ 8] plumed_master(+0x146dd)[0x55c2d38106dd]
[fv-az1267-279:63143] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9bf962a1ca]
[fv-az1267-279:63143] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9bf962a28b]
[fv-az1267-279:63143] [11] plumed_master(+0x15365)[0x55c2d3811365]
[fv-az1267-279:63143] *** End of error message ***
</pre>
{% endraw %}
