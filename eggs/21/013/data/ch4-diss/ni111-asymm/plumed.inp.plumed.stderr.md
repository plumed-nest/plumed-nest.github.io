**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Dwp7BX/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmmklqx:08831] *** Process received signal ***
[runnervmmklqx:08831] Signal: Aborted (6)
[runnervmmklqx:08831] Signal code:  (-6)
[runnervmmklqx:08831] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4a1c45330]
[runnervmmklqx:08831] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4a1c9eb2c]
[runnervmmklqx:08831] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4a1c4527e]
[runnervmmklqx:08831] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4a1c288ff]
[runnervmmklqx:08831] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4a20a5ff5]
[runnervmmklqx:08831] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4a20bb0da]
[runnervmmklqx:08831] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4a20a5a55]
[runnervmmklqx:08831] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4a20a5a6f]
[runnervmmklqx:08831] [ 8] plumed(+0x146dd)[0x5586980366dd]
[runnervmmklqx:08831] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4a1c2a1ca]
[runnervmmklqx:08831] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4a1c2a28b]
[runnervmmklqx:08831] [11] plumed(+0x15365)[0x558698037365]
[runnervmmklqx:08831] *** End of error message ***
</pre>
{% endraw %}
