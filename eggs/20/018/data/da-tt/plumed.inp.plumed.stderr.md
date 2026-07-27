**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.Hf31LN/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.1.so ../src/bias/ReweightGeomFES.cpp

[runnervmvrwv9:09425] *** Process received signal ***
[runnervmvrwv9:09425] Signal: Aborted (6)
[runnervmvrwv9:09425] Signal code:  (-6)
[runnervmvrwv9:09425] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8fed445330]
[runnervmvrwv9:09425] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8fed49eb2c]
[runnervmvrwv9:09425] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8fed44527e]
[runnervmvrwv9:09425] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8fed4288ff]
[runnervmvrwv9:09425] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8fed8a5ff5]
[runnervmvrwv9:09425] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8fed8bb0da]
[runnervmvrwv9:09425] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8fed8a5a55]
[runnervmvrwv9:09425] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8fed8a5a6f]
[runnervmvrwv9:09425] [ 8] plumed(+0x146dd)[0x5617822316dd]
[runnervmvrwv9:09425] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8fed42a1ca]
[runnervmvrwv9:09425] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8fed42a28b]
[runnervmvrwv9:09425] [11] plumed(+0x15365)[0x561782232365]
[runnervmvrwv9:09425] *** End of error message ***
</pre>
{% endraw %}
