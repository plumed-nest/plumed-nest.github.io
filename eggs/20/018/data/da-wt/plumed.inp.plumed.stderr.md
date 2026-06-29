**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.IjvVhT/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.0.so ../src/bias/ReweightGeomFES.cpp

[runnervmmklqx:11609] *** Process received signal ***
[runnervmmklqx:11609] Signal: Aborted (6)
[runnervmmklqx:11609] Signal code:  (-6)
[runnervmmklqx:11609] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7754445330]
[runnervmmklqx:11609] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f775449eb2c]
[runnervmmklqx:11609] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f775444527e]
[runnervmmklqx:11609] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77544288ff]
[runnervmmklqx:11609] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77548a5ff5]
[runnervmmklqx:11609] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77548bb0da]
[runnervmmklqx:11609] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77548a5a55]
[runnervmmklqx:11609] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77548a5a6f]
[runnervmmklqx:11609] [ 8] plumed(+0x146dd)[0x563a6681d6dd]
[runnervmmklqx:11609] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f775442a1ca]
[runnervmmklqx:11609] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f775442a28b]
[runnervmmklqx:11609] [11] plumed(+0x15365)[0x563a6681e365]
[runnervmmklqx:11609] *** End of error message ***
</pre>
{% endraw %}
