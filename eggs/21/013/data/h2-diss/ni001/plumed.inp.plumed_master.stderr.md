**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Y5GMvu/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az787-589:64630] *** Process received signal ***
[fv-az787-589:64630] Signal: Aborted (6)
[fv-az787-589:64630] Signal code:  (-6)
[fv-az787-589:64630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fae83845330]
[fv-az787-589:64630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fae8389eb2c]
[fv-az787-589:64630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fae8384527e]
[fv-az787-589:64630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fae838288ff]
[fv-az787-589:64630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fae83ca5ff5]
[fv-az787-589:64630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fae83cbb0da]
[fv-az787-589:64630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fae83ca5a55]
[fv-az787-589:64630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fae83ca5a6f]
[fv-az787-589:64630] [ 8] plumed_master(+0x146dd)[0x558bf90ca6dd]
[fv-az787-589:64630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fae8382a1ca]
[fv-az787-589:64630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fae8382a28b]
[fv-az787-589:64630] [11] plumed_master(+0x15365)[0x558bf90cb365]
[fv-az787-589:64630] *** End of error message ***
</pre>
{% endraw %}
