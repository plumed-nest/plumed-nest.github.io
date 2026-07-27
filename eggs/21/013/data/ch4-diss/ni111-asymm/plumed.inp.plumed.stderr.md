**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-asymm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.sAOGeK/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.1.so ../../data/ReweightGeomFES.cpp

[runnervmvrwv9:08563] *** Process received signal ***
[runnervmvrwv9:08563] Signal: Aborted (6)
[runnervmvrwv9:08563] Signal code:  (-6)
[runnervmvrwv9:08563] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f411a645330]
[runnervmvrwv9:08563] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f411a69eb2c]
[runnervmvrwv9:08563] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f411a64527e]
[runnervmvrwv9:08563] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f411a6288ff]
[runnervmvrwv9:08563] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f411aaa5ff5]
[runnervmvrwv9:08563] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f411aabb0da]
[runnervmvrwv9:08563] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f411aaa5a55]
[runnervmvrwv9:08563] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f411aaa5a6f]
[runnervmvrwv9:08563] [ 8] plumed(+0x146dd)[0x55742b3196dd]
[runnervmvrwv9:08563] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f411a62a1ca]
[runnervmvrwv9:08563] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f411a62a28b]
[runnervmvrwv9:08563] [11] plumed(+0x15365)[0x55742b31a365]
[runnervmvrwv9:08563] *** End of error message ***
</pre>
{% endraw %}
