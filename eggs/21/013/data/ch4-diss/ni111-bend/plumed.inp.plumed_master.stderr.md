**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-bend/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.LIc9e9/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmi13qx:38995] *** Process received signal ***
[runnervmi13qx:38995] Signal: Aborted (6)
[runnervmi13qx:38995] Signal code:  (-6)
[runnervmi13qx:38995] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efdefc45330]
[runnervmi13qx:38995] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efdefc9eb2c]
[runnervmi13qx:38995] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efdefc4527e]
[runnervmi13qx:38995] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efdefc288ff]
[runnervmi13qx:38995] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efdf00a5ff5]
[runnervmi13qx:38995] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efdf00bb0da]
[runnervmi13qx:38995] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efdf00a5a55]
[runnervmi13qx:38995] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efdf00a5a6f]
[runnervmi13qx:38995] [ 8] plumed_master(+0x146dd)[0x557e4f8506dd]
[runnervmi13qx:38995] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efdefc2a1ca]
[runnervmi13qx:38995] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efdefc2a28b]
[runnervmi13qx:38995] [11] plumed_master(+0x15365)[0x557e4f851365]
[runnervmi13qx:38995] *** End of error message ***
</pre>
{% endraw %}
