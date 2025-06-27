**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.3wECUu/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[pkrvmbietmlfzoi:66222] *** Process received signal ***
[pkrvmbietmlfzoi:66222] Signal: Aborted (6)
[pkrvmbietmlfzoi:66222] Signal code:  (-6)
[pkrvmbietmlfzoi:66222] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f92b5645330]
[pkrvmbietmlfzoi:66222] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f92b569eb2c]
[pkrvmbietmlfzoi:66222] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f92b564527e]
[pkrvmbietmlfzoi:66222] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92b56288ff]
[pkrvmbietmlfzoi:66222] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92b5aa5ff5]
[pkrvmbietmlfzoi:66222] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92b5abb0da]
[pkrvmbietmlfzoi:66222] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92b5aa5a55]
[pkrvmbietmlfzoi:66222] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92b5aa5a6f]
[pkrvmbietmlfzoi:66222] [ 8] plumed(+0x146dd)[0x55f32a5546dd]
[pkrvmbietmlfzoi:66222] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f92b562a1ca]
[pkrvmbietmlfzoi:66222] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f92b562a28b]
[pkrvmbietmlfzoi:66222] [11] plumed(+0x15365)[0x55f32a555365]
[pkrvmbietmlfzoi:66222] *** End of error message ***
</pre>
{% endraw %}
