**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.XTLG7x/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0.so ../../data/ReweightGeomFES.cpp

[runnervmmklqx:08377] *** Process received signal ***
[runnervmmklqx:08377] Signal: Aborted (6)
[runnervmmklqx:08377] Signal code:  (-6)
[runnervmmklqx:08377] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f14dfe45330]
[runnervmmklqx:08377] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f14dfe9eb2c]
[runnervmmklqx:08377] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f14dfe4527e]
[runnervmmklqx:08377] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f14dfe288ff]
[runnervmmklqx:08377] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f14e02a5ff5]
[runnervmmklqx:08377] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f14e02bb0da]
[runnervmmklqx:08377] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f14e02a5a55]
[runnervmmklqx:08377] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f14e02a5a6f]
[runnervmmklqx:08377] [ 8] plumed(+0x146dd)[0x55b51ac2e6dd]
[runnervmmklqx:08377] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f14dfe2a1ca]
[runnervmmklqx:08377] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f14dfe2a28b]
[runnervmmklqx:08377] [11] plumed(+0x15365)[0x55b51ac2f365]
[runnervmmklqx:08377] *** End of error message ***
</pre>
{% endraw %}
