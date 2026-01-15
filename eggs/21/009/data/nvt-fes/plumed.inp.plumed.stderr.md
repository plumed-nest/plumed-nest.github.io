**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.paZ0YO/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.0.so ../codes/ReweightGeomFES.cpp

[runnervmi13qx:35956] *** Process received signal ***
[runnervmi13qx:35956] Signal: Aborted (6)
[runnervmi13qx:35956] Signal code:  (-6)
[runnervmi13qx:35956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47c3a45330]
[runnervmi13qx:35956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47c3a9eb2c]
[runnervmi13qx:35956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47c3a4527e]
[runnervmi13qx:35956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47c3a288ff]
[runnervmi13qx:35956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47c3ea5ff5]
[runnervmi13qx:35956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47c3ebb0da]
[runnervmi13qx:35956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47c3ea5a55]
[runnervmi13qx:35956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47c3ea5a6f]
[runnervmi13qx:35956] [ 8] plumed(+0x146dd)[0x55ddbb9e16dd]
[runnervmi13qx:35956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47c3a2a1ca]
[runnervmi13qx:35956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47c3a2a28b]
[runnervmi13qx:35956] [11] plumed(+0x15365)[0x55ddbb9e2365]
[runnervmi13qx:35956] *** End of error message ***
</pre>
{% endraw %}
