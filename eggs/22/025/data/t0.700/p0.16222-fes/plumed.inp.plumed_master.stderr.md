**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.700/p0.16222-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.50XarM/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[runnervm76f27:09511] *** Process received signal ***
[runnervm76f27:09511] Signal: Aborted (6)
[runnervm76f27:09511] Signal code:  (-6)
[runnervm76f27:09511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9662645330]
[runnervm76f27:09511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f966269ec0c]
[runnervm76f27:09511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f966264527e]
[runnervm76f27:09511] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96626288ff]
[runnervm76f27:09511] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9662aa5ff5]
[runnervm76f27:09511] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9662abb0da]
[runnervm76f27:09511] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9662aa5a55]
[runnervm76f27:09511] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9662aa5a6f]
[runnervm76f27:09511] [ 8] plumed_master(+0x146dd)[0x55a791fe56dd]
[runnervm76f27:09511] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f966262a1ca]
[runnervm76f27:09511] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f966262a28b]
[runnervm76f27:09511] [11] plumed_master(+0x15365)[0x55a791fe6365]
[runnervm76f27:09511] *** End of error message ***
</pre>
{% endraw %}
