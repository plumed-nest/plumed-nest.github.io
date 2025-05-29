**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.14000-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.4LF16N/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[pkrvmf6wy0o8zjz:63334] *** Process received signal ***
[pkrvmf6wy0o8zjz:63334] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63334] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4568045330]
[pkrvmf6wy0o8zjz:63334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f456809eb2c]
[pkrvmf6wy0o8zjz:63334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f456804527e]
[pkrvmf6wy0o8zjz:63334] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45680288ff]
[pkrvmf6wy0o8zjz:63334] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45684a5ff5]
[pkrvmf6wy0o8zjz:63334] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45684bb0da]
[pkrvmf6wy0o8zjz:63334] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45684a5a55]
[pkrvmf6wy0o8zjz:63334] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45684a5a6f]
[pkrvmf6wy0o8zjz:63334] [ 8] plumed(+0x146dd)[0x5638c3e846dd]
[pkrvmf6wy0o8zjz:63334] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f456802a1ca]
[pkrvmf6wy0o8zjz:63334] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f456802a28b]
[pkrvmf6wy0o8zjz:63334] [11] plumed(+0x15365)[0x5638c3e85365]
[pkrvmf6wy0o8zjz:63334] *** End of error message ***
</pre>
{% endraw %}
