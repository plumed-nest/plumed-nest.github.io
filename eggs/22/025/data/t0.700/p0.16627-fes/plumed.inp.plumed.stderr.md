**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16627-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.67K6YS/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az805-507:10766] *** Process received signal ***
[fv-az805-507:10766] Signal: Aborted (6)
[fv-az805-507:10766] Signal code:  (-6)
[fv-az805-507:10766] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f369ac45330]
[fv-az805-507:10766] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f369ac9eb2c]
[fv-az805-507:10766] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f369ac4527e]
[fv-az805-507:10766] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f369ac288ff]
[fv-az805-507:10766] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f369b0a5ff5]
[fv-az805-507:10766] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f369b0bb0da]
[fv-az805-507:10766] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f369b0a5a55]
[fv-az805-507:10766] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f369b0a5a6f]
[fv-az805-507:10766] [ 8] plumed(+0x146dd)[0x5632e5edf6dd]
[fv-az805-507:10766] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f369ac2a1ca]
[fv-az805-507:10766] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f369ac2a28b]
[fv-az805-507:10766] [11] plumed(+0x15365)[0x5632e5ee0365]
[fv-az805-507:10766] *** End of error message ***
</pre>
{% endraw %}
