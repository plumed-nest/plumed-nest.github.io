**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.nUW9IP/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10b.so ../codes/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:65851] *** Process received signal ***
[pkrvmbietmlfzoi:65851] Signal: Aborted (6)
[pkrvmbietmlfzoi:65851] Signal code:  (-6)
[pkrvmbietmlfzoi:65851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f44d2245330]
[pkrvmbietmlfzoi:65851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f44d229eb2c]
[pkrvmbietmlfzoi:65851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f44d224527e]
[pkrvmbietmlfzoi:65851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f44d22288ff]
[pkrvmbietmlfzoi:65851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44d26a5ff5]
[pkrvmbietmlfzoi:65851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44d26bb0da]
[pkrvmbietmlfzoi:65851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44d26a5a55]
[pkrvmbietmlfzoi:65851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44d26a5a6f]
[pkrvmbietmlfzoi:65851] [ 8] plumed(+0x146dd)[0x5594c05996dd]
[pkrvmbietmlfzoi:65851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f44d222a1ca]
[pkrvmbietmlfzoi:65851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f44d222a28b]
[pkrvmbietmlfzoi:65851] [11] plumed(+0x15365)[0x5594c059a365]
[pkrvmbietmlfzoi:65851] *** End of error message ***
</pre>
{% endraw %}
