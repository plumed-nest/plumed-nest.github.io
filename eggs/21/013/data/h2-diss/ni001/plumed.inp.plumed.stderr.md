**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.FXEFFN/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az1110-827:63172] *** Process received signal ***
[fv-az1110-827:63172] Signal: Aborted (6)
[fv-az1110-827:63172] Signal code:  (-6)
[fv-az1110-827:63172] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc859045330]
[fv-az1110-827:63172] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc85909eb2c]
[fv-az1110-827:63172] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc85904527e]
[fv-az1110-827:63172] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8590288ff]
[fv-az1110-827:63172] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8594a5ff5]
[fv-az1110-827:63172] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8594bb0da]
[fv-az1110-827:63172] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8594a5a55]
[fv-az1110-827:63172] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8594a5a6f]
[fv-az1110-827:63172] [ 8] plumed(+0x146dd)[0x55f32f9716dd]
[fv-az1110-827:63172] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc85902a1ca]
[fv-az1110-827:63172] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc85902a28b]
[fv-az1110-827:63172] [11] plumed(+0x15365)[0x55f32f972365]
[fv-az1110-827:63172] *** End of error message ***
</pre>
{% endraw %}
