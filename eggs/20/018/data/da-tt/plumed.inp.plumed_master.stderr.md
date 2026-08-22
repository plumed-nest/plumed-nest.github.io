**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.HIXdGA/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[runnervm76f27:09692] *** Process received signal ***
[runnervm76f27:09692] Signal: Aborted (6)
[runnervm76f27:09692] Signal code:  (-6)
[runnervm76f27:09692] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f915d645330]
[runnervm76f27:09692] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f915d69ec0c]
[runnervm76f27:09692] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f915d64527e]
[runnervm76f27:09692] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f915d6288ff]
[runnervm76f27:09692] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f915daa5ff5]
[runnervm76f27:09692] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f915dabb0da]
[runnervm76f27:09692] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f915daa5a55]
[runnervm76f27:09692] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f915daa5a6f]
[runnervm76f27:09692] [ 8] plumed_master(+0x146dd)[0x55d2c800a6dd]
[runnervm76f27:09692] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f915d62a1ca]
[runnervm76f27:09692] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f915d62a28b]
[runnervm76f27:09692] [11] plumed_master(+0x15365)[0x55d2c800b365]
[runnervm76f27:09692] *** End of error message ***
</pre>
{% endraw %}
