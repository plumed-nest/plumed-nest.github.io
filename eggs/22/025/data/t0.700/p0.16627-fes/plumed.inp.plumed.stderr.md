**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16627-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.JpfFmZ/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0.so ../../code/ReweightGeomFES.cpp

[runnervmmklqx:09299] *** Process received signal ***
[runnervmmklqx:09299] Signal: Aborted (6)
[runnervmmklqx:09299] Signal code:  (-6)
[runnervmmklqx:09299] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f485b645330]
[runnervmmklqx:09299] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f485b69eb2c]
[runnervmmklqx:09299] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f485b64527e]
[runnervmmklqx:09299] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f485b6288ff]
[runnervmmklqx:09299] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f485baa5ff5]
[runnervmmklqx:09299] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f485babb0da]
[runnervmmklqx:09299] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f485baa5a55]
[runnervmmklqx:09299] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f485baa5a6f]
[runnervmmklqx:09299] [ 8] plumed(+0x146dd)[0x555e824666dd]
[runnervmmklqx:09299] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f485b62a1ca]
[runnervmmklqx:09299] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f485b62a28b]
[runnervmmklqx:09299] [11] plumed(+0x15365)[0x555e82467365]
[runnervmmklqx:09299] *** End of error message ***
</pre>
{% endraw %}
