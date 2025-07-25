**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.dII56J/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[pkrvmpptgkbjq6m:09374] *** Process received signal ***
[pkrvmpptgkbjq6m:09374] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09374] Signal code:  (-6)
[pkrvmpptgkbjq6m:09374] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f58bba45330]
[pkrvmpptgkbjq6m:09374] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f58bba9eb2c]
[pkrvmpptgkbjq6m:09374] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f58bba4527e]
[pkrvmpptgkbjq6m:09374] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f58bba288ff]
[pkrvmpptgkbjq6m:09374] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f58bbea5ff5]
[pkrvmpptgkbjq6m:09374] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f58bbebb0da]
[pkrvmpptgkbjq6m:09374] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f58bbea5a55]
[pkrvmpptgkbjq6m:09374] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f58bbea5a6f]
[pkrvmpptgkbjq6m:09374] [ 8] plumed(+0x146dd)[0x559c354896dd]
[pkrvmpptgkbjq6m:09374] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f58bba2a1ca]
[pkrvmpptgkbjq6m:09374] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f58bba2a28b]
[pkrvmpptgkbjq6m:09374] [11] plumed(+0x15365)[0x559c3548a365]
[pkrvmpptgkbjq6m:09374] *** End of error message ***
</pre>
{% endraw %}
