**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.17Nr2B/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.1.so ../../code/ReweightGeomFES.cpp

[runnervmvrwv9:07492] *** Process received signal ***
[runnervmvrwv9:07492] Signal: Aborted (6)
[runnervmvrwv9:07492] Signal code:  (-6)
[runnervmvrwv9:07492] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0975845330]
[runnervmvrwv9:07492] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f097589eb2c]
[runnervmvrwv9:07492] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f097584527e]
[runnervmvrwv9:07492] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09758288ff]
[runnervmvrwv9:07492] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0975ca5ff5]
[runnervmvrwv9:07492] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0975cbb0da]
[runnervmvrwv9:07492] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0975ca5a55]
[runnervmvrwv9:07492] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0975ca5a6f]
[runnervmvrwv9:07492] [ 8] plumed(+0x146dd)[0x55a90199a6dd]
[runnervmvrwv9:07492] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f097582a1ca]
[runnervmvrwv9:07492] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f097582a28b]
[runnervmvrwv9:07492] [11] plumed(+0x15365)[0x55a90199b365]
[runnervmvrwv9:07492] *** End of error message ***
</pre>
{% endraw %}
