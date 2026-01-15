**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.iehhbd/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmi13qx:38069] *** Process received signal ***
[runnervmi13qx:38069] Signal: Aborted (6)
[runnervmi13qx:38069] Signal code:  (-6)
[runnervmi13qx:38069] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa7fbe45330]
[runnervmi13qx:38069] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa7fbe9eb2c]
[runnervmi13qx:38069] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa7fbe4527e]
[runnervmi13qx:38069] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7fbe288ff]
[runnervmi13qx:38069] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7fc2a5ff5]
[runnervmi13qx:38069] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7fc2bb0da]
[runnervmi13qx:38069] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7fc2a5a55]
[runnervmi13qx:38069] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7fc2a5a6f]
[runnervmi13qx:38069] [ 8] plumed(+0x146dd)[0x562844b8e6dd]
[runnervmi13qx:38069] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa7fbe2a1ca]
[runnervmi13qx:38069] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa7fbe2a28b]
[runnervmi13qx:38069] [11] plumed(+0x15365)[0x562844b8f365]
[runnervmi13qx:38069] *** End of error message ***
</pre>
{% endraw %}
