**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni211/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lSzCn4/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az790-36:65976] *** Process received signal ***
[fv-az790-36:65976] Signal: Aborted (6)
[fv-az790-36:65976] Signal code:  (-6)
[fv-az790-36:65976] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8009845330]
[fv-az790-36:65976] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f800989eb2c]
[fv-az790-36:65976] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f800984527e]
[fv-az790-36:65976] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80098288ff]
[fv-az790-36:65976] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8009ca5ff5]
[fv-az790-36:65976] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8009cbb0da]
[fv-az790-36:65976] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8009ca5a55]
[fv-az790-36:65976] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8009ca5a6f]
[fv-az790-36:65976] [ 8] plumed(+0x146dd)[0x561bca9d16dd]
[fv-az790-36:65976] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f800982a1ca]
[fv-az790-36:65976] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f800982a28b]
[fv-az790-36:65976] [11] plumed(+0x15365)[0x561bca9d2365]
[fv-az790-36:65976] *** End of error message ***
</pre>
{% endraw %}
