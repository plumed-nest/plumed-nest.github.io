**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Noz4NR/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az1344-582:63682] *** Process received signal ***
[fv-az1344-582:63682] Signal: Aborted (6)
[fv-az1344-582:63682] Signal code:  (-6)
[fv-az1344-582:63682] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f717d245330]
[fv-az1344-582:63682] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f717d29eb2c]
[fv-az1344-582:63682] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f717d24527e]
[fv-az1344-582:63682] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f717d2288ff]
[fv-az1344-582:63682] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f717d6a5ff5]
[fv-az1344-582:63682] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f717d6bb0da]
[fv-az1344-582:63682] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f717d6a5a55]
[fv-az1344-582:63682] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f717d6a5a6f]
[fv-az1344-582:63682] [ 8] plumed(+0x146dd)[0x559ff0b4b6dd]
[fv-az1344-582:63682] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f717d22a1ca]
[fv-az1344-582:63682] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f717d22a28b]
[fv-az1344-582:63682] [11] plumed(+0x15365)[0x559ff0b4c365]
[fv-az1344-582:63682] *** End of error message ***
</pre>
{% endraw %}
