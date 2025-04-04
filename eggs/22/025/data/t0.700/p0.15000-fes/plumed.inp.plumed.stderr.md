**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.15000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.5aTm1X/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az805-507:11120] *** Process received signal ***
[fv-az805-507:11120] Signal: Aborted (6)
[fv-az805-507:11120] Signal code:  (-6)
[fv-az805-507:11120] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f269c845330]
[fv-az805-507:11120] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f269c89eb2c]
[fv-az805-507:11120] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f269c84527e]
[fv-az805-507:11120] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f269c8288ff]
[fv-az805-507:11120] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f269cca5ff5]
[fv-az805-507:11120] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f269ccbb0da]
[fv-az805-507:11120] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f269cca5a55]
[fv-az805-507:11120] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f269cca5a6f]
[fv-az805-507:11120] [ 8] plumed(+0x146dd)[0x556a94f5b6dd]
[fv-az805-507:11120] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f269c82a1ca]
[fv-az805-507:11120] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f269c82a28b]
[fv-az805-507:11120] [11] plumed(+0x15365)[0x556a94f5c365]
[fv-az805-507:11120] *** End of error message ***
</pre>
{% endraw %}
