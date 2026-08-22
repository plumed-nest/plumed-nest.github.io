**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.CWVT2w/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[runnervm76f27:10196] *** Process received signal ***
[runnervm76f27:10196] Signal: Aborted (6)
[runnervm76f27:10196] Signal code:  (-6)
[runnervm76f27:10196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d1ca45330]
[runnervm76f27:10196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d1ca9ec0c]
[runnervm76f27:10196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d1ca4527e]
[runnervm76f27:10196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d1ca288ff]
[runnervm76f27:10196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d1cea5ff5]
[runnervm76f27:10196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d1cebb0da]
[runnervm76f27:10196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d1cea5a55]
[runnervm76f27:10196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d1cea5a6f]
[runnervm76f27:10196] [ 8] plumed_master(+0x146dd)[0x55dcf69c86dd]
[runnervm76f27:10196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d1ca2a1ca]
[runnervm76f27:10196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d1ca2a28b]
[runnervm76f27:10196] [11] plumed_master(+0x15365)[0x55dcf69c9365]
[runnervm76f27:10196] *** End of error message ***
</pre>
{% endraw %}
