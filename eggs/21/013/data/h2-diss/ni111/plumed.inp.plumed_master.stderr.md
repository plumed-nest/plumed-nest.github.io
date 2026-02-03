**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.zkRUwH/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervmkj6or:11412] *** Process received signal ***
[runnervmkj6or:11412] Signal: Aborted (6)
[runnervmkj6or:11412] Signal code:  (-6)
[runnervmkj6or:11412] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8df6e45330]
[runnervmkj6or:11412] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8df6e9eb2c]
[runnervmkj6or:11412] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8df6e4527e]
[runnervmkj6or:11412] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8df6e288ff]
[runnervmkj6or:11412] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8df72a5ff5]
[runnervmkj6or:11412] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8df72bb0da]
[runnervmkj6or:11412] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8df72a5a55]
[runnervmkj6or:11412] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8df72a5a6f]
[runnervmkj6or:11412] [ 8] plumed_master(+0x146dd)[0x5635b800a6dd]
[runnervmkj6or:11412] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8df6e2a1ca]
[runnervmkj6or:11412] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8df6e2a28b]
[runnervmkj6or:11412] [11] plumed_master(+0x15365)[0x5635b800b365]
[runnervmkj6or:11412] *** End of error message ***
</pre>
{% endraw %}
