**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.zgZljz/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1490-855:05872] *** Process received signal ***
[fv-az1490-855:05872] Signal: Aborted (6)
[fv-az1490-855:05872] Signal code:  (-6)
[fv-az1490-855:05872] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3be3c42520]
[fv-az1490-855:05872] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3be3c969fc]
[fv-az1490-855:05872] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3be3c42476]
[fv-az1490-855:05872] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3be3c287f3]
[fv-az1490-855:05872] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3be40a2b9e]
[fv-az1490-855:05872] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3be40ae20c]
[fv-az1490-855:05872] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3be40ae277]
[fv-az1490-855:05872] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3be40ae52b]
[fv-az1490-855:05872] [ 8] plumed_master(+0x14274)[0x55ace4b7d274]
[fv-az1490-855:05872] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3be3c29d90]
[fv-az1490-855:05872] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3be3c29e40]
[fv-az1490-855:05872] [11] plumed_master(+0x14ed5)[0x55ace4b7ded5]
[fv-az1490-855:05872] *** End of error message ***
</pre>
{% endraw %}
