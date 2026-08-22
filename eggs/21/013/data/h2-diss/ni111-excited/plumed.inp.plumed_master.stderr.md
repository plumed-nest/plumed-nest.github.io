**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni111-excited/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.MSmsEU/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervm76f27:09650] *** Process received signal ***
[runnervm76f27:09650] Signal: Aborted (6)
[runnervm76f27:09650] Signal code:  (-6)
[runnervm76f27:09650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ae9245330]
[runnervm76f27:09650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ae929ec0c]
[runnervm76f27:09650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ae924527e]
[runnervm76f27:09650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ae92288ff]
[runnervm76f27:09650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ae96a5ff5]
[runnervm76f27:09650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ae96bb0da]
[runnervm76f27:09650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ae96a5a55]
[runnervm76f27:09650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ae96a5a6f]
[runnervm76f27:09650] [ 8] plumed_master(+0x146dd)[0x55e5fe2446dd]
[runnervm76f27:09650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ae922a1ca]
[runnervm76f27:09650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ae922a28b]
[runnervm76f27:09650] [11] plumed_master(+0x15365)[0x55e5fe245365]
[runnervm76f27:09650] *** End of error message ***
</pre>
{% endraw %}
