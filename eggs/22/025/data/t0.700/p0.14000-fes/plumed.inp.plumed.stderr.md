**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.gNfEI2/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az1267-279:63794] *** Process received signal ***
[fv-az1267-279:63794] Signal: Aborted (6)
[fv-az1267-279:63794] Signal code:  (-6)
[fv-az1267-279:63794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1312245330]
[fv-az1267-279:63794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f131229eb2c]
[fv-az1267-279:63794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f131224527e]
[fv-az1267-279:63794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13122288ff]
[fv-az1267-279:63794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f13126a5ff5]
[fv-az1267-279:63794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f13126bb0da]
[fv-az1267-279:63794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f13126a5a55]
[fv-az1267-279:63794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f13126a5a6f]
[fv-az1267-279:63794] [ 8] plumed(+0x146dd)[0x562514ace6dd]
[fv-az1267-279:63794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f131222a1ca]
[fv-az1267-279:63794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f131222a28b]
[fv-az1267-279:63794] [11] plumed(+0x15365)[0x562514acf365]
[fv-az1267-279:63794] *** End of error message ***
</pre>
{% endraw %}
