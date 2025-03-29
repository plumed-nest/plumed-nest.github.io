**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  dimer/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.qRTx04/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az1279-218:65654] *** Process received signal ***
[fv-az1279-218:65654] Signal: Aborted (6)
[fv-az1279-218:65654] Signal code:  (-6)
[fv-az1279-218:65654] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f32845330]
[fv-az1279-218:65654] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f3289eb2c]
[fv-az1279-218:65654] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f3284527e]
[fv-az1279-218:65654] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f328288ff]
[fv-az1279-218:65654] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f32ca5ff5]
[fv-az1279-218:65654] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f32cbb0da]
[fv-az1279-218:65654] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f32ca5a55]
[fv-az1279-218:65654] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f32ca5a6f]
[fv-az1279-218:65654] [ 8] plumed_master(+0x146dd)[0x5604436c86dd]
[fv-az1279-218:65654] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f3282a1ca]
[fv-az1279-218:65654] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f3282a28b]
[fv-az1279-218:65654] [11] plumed_master(+0x15365)[0x5604436c9365]
[fv-az1279-218:65654] *** End of error message ***
</pre>
{% endraw %}
