**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.fTKMxe/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az1344-582:64037] *** Process received signal ***
[fv-az1344-582:64037] Signal: Aborted (6)
[fv-az1344-582:64037] Signal code:  (-6)
[fv-az1344-582:64037] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fada5a45330]
[fv-az1344-582:64037] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fada5a9eb2c]
[fv-az1344-582:64037] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fada5a4527e]
[fv-az1344-582:64037] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fada5a288ff]
[fv-az1344-582:64037] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fada5ea5ff5]
[fv-az1344-582:64037] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fada5ebb0da]
[fv-az1344-582:64037] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fada5ea5a55]
[fv-az1344-582:64037] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fada5ea5a6f]
[fv-az1344-582:64037] [ 8] plumed(+0x146dd)[0x55bf9eab16dd]
[fv-az1344-582:64037] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fada5a2a1ca]
[fv-az1344-582:64037] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fada5a2a28b]
[fv-az1344-582:64037] [11] plumed(+0x15365)[0x55bf9eab2365]
[fv-az1344-582:64037] *** End of error message ***
</pre>
{% endraw %}
