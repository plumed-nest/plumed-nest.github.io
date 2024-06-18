**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  nvt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.OPUq15/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10.0-dev.so ../codes/ReweightGeomFES.cpp

[fv-az1272-851:09601] *** Process received signal ***
[fv-az1272-851:09601] Signal: Aborted (6)
[fv-az1272-851:09601] Signal code:  (-6)
[fv-az1272-851:09601] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7543842520]
[fv-az1272-851:09601] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f75438969fc]
[fv-az1272-851:09601] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7543842476]
[fv-az1272-851:09601] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f75438287f3]
[fv-az1272-851:09601] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7543ca2b9e]
[fv-az1272-851:09601] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7543cae20c]
[fv-az1272-851:09601] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7543cae277]
[fv-az1272-851:09601] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7543cae52b]
[fv-az1272-851:09601] [ 8] plumed_master(+0x14274)[0x5648fa5d4274]
[fv-az1272-851:09601] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7543829d90]
[fv-az1272-851:09601] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7543829e40]
[fv-az1272-851:09601] [11] plumed_master(+0x14ed5)[0x5648fa5d4ed5]
[fv-az1272-851:09601] *** End of error message ***
</pre>
{% endraw %}
