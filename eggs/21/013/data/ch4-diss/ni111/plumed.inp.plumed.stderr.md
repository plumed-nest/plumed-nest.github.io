**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.sfdGRO/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmf6wy0o8zjz:40140] *** Process received signal ***
[pkrvmf6wy0o8zjz:40140] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40140] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a71045330]
[pkrvmf6wy0o8zjz:40140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a7109eb2c]
[pkrvmf6wy0o8zjz:40140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a7104527e]
[pkrvmf6wy0o8zjz:40140] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a710288ff]
[pkrvmf6wy0o8zjz:40140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a714a5ff5]
[pkrvmf6wy0o8zjz:40140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a714bb0da]
[pkrvmf6wy0o8zjz:40140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a714a5a55]
[pkrvmf6wy0o8zjz:40140] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a714a5a6f]
[pkrvmf6wy0o8zjz:40140] [ 8] plumed(+0x146dd)[0x55e8070c16dd]
[pkrvmf6wy0o8zjz:40140] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a7102a1ca]
[pkrvmf6wy0o8zjz:40140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a7102a28b]
[pkrvmf6wy0o8zjz:40140] [11] plumed(+0x15365)[0x55e8070c2365]
[pkrvmf6wy0o8zjz:40140] *** End of error message ***
</pre>
{% endraw %}
