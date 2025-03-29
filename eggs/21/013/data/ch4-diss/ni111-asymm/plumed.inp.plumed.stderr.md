**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.vWm6kE/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az1947-163:65376] *** Process received signal ***
[fv-az1947-163:65376] Signal: Aborted (6)
[fv-az1947-163:65376] Signal code:  (-6)
[fv-az1947-163:65376] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff504845330]
[fv-az1947-163:65376] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff50489eb2c]
[fv-az1947-163:65376] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff50484527e]
[fv-az1947-163:65376] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5048288ff]
[fv-az1947-163:65376] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff504ca5ff5]
[fv-az1947-163:65376] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff504cbb0da]
[fv-az1947-163:65376] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff504ca5a55]
[fv-az1947-163:65376] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff504ca5a6f]
[fv-az1947-163:65376] [ 8] plumed(+0x146dd)[0x5583696076dd]
[fv-az1947-163:65376] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff50482a1ca]
[fv-az1947-163:65376] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff50482a28b]
[fv-az1947-163:65376] [11] plumed(+0x15365)[0x558369608365]
[fv-az1947-163:65376] *** End of error message ***
</pre>
{% endraw %}
