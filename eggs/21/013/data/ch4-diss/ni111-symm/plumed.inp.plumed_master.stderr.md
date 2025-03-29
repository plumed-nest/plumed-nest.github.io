**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.YESIDp/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1947-163:65497] *** Process received signal ***
[fv-az1947-163:65497] Signal: Aborted (6)
[fv-az1947-163:65497] Signal code:  (-6)
[fv-az1947-163:65497] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9be5845330]
[fv-az1947-163:65497] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9be589eb2c]
[fv-az1947-163:65497] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9be584527e]
[fv-az1947-163:65497] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9be58288ff]
[fv-az1947-163:65497] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9be5ca5ff5]
[fv-az1947-163:65497] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9be5cbb0da]
[fv-az1947-163:65497] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9be5ca5a55]
[fv-az1947-163:65497] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9be5ca5a6f]
[fv-az1947-163:65497] [ 8] plumed_master(+0x146dd)[0x55bb840db6dd]
[fv-az1947-163:65497] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9be582a1ca]
[fv-az1947-163:65497] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9be582a28b]
[fv-az1947-163:65497] [11] plumed_master(+0x15365)[0x55bb840dc365]
[fv-az1947-163:65497] *** End of error message ***
</pre>
{% endraw %}
