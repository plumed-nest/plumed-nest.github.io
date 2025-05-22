**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.PZCiar/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmf6wy0o8zjz:39423] *** Process received signal ***
[pkrvmf6wy0o8zjz:39423] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:39423] Signal code:  (-6)
[pkrvmf6wy0o8zjz:39423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f11ff045330]
[pkrvmf6wy0o8zjz:39423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f11ff09eb2c]
[pkrvmf6wy0o8zjz:39423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f11ff04527e]
[pkrvmf6wy0o8zjz:39423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f11ff0288ff]
[pkrvmf6wy0o8zjz:39423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f11ff4a5ff5]
[pkrvmf6wy0o8zjz:39423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f11ff4bb0da]
[pkrvmf6wy0o8zjz:39423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f11ff4a5a55]
[pkrvmf6wy0o8zjz:39423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f11ff4a5a6f]
[pkrvmf6wy0o8zjz:39423] [ 8] plumed(+0x146dd)[0x557109d5a6dd]
[pkrvmf6wy0o8zjz:39423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f11ff02a1ca]
[pkrvmf6wy0o8zjz:39423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f11ff02a28b]
[pkrvmf6wy0o8zjz:39423] [11] plumed(+0x15365)[0x557109d5b365]
[pkrvmf6wy0o8zjz:39423] *** End of error message ***
</pre>
{% endraw %}
