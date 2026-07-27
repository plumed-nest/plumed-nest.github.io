**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.AMKS85/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.1.so ../../data/ReweightGeomFES.cpp

[runnervmvrwv9:08650] *** Process received signal ***
[runnervmvrwv9:08650] Signal: Aborted (6)
[runnervmvrwv9:08650] Signal code:  (-6)
[runnervmvrwv9:08650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b17445330]
[runnervmvrwv9:08650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b1749eb2c]
[runnervmvrwv9:08650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b1744527e]
[runnervmvrwv9:08650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b174288ff]
[runnervmvrwv9:08650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b178a5ff5]
[runnervmvrwv9:08650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b178bb0da]
[runnervmvrwv9:08650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b178a5a55]
[runnervmvrwv9:08650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b178a5a6f]
[runnervmvrwv9:08650] [ 8] plumed(+0x146dd)[0x559cfc1496dd]
[runnervmvrwv9:08650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b1742a1ca]
[runnervmvrwv9:08650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b1742a28b]
[runnervmvrwv9:08650] [11] plumed(+0x15365)[0x559cfc14a365]
[runnervmvrwv9:08650] *** End of error message ***
</pre>
{% endraw %}
