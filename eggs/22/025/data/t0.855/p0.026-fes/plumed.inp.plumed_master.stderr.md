**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  t0.855/p0.026-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.IZg12t/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1771-923:06724] *** Process received signal ***
[fv-az1771-923:06724] Signal: Aborted (6)
[fv-az1771-923:06724] Signal code:  (-6)
[fv-az1771-923:06724] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdabf642520]
[fv-az1771-923:06724] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdabf6969fc]
[fv-az1771-923:06724] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdabf642476]
[fv-az1771-923:06724] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdabf6287f3]
[fv-az1771-923:06724] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdabfaa2b9e]
[fv-az1771-923:06724] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdabfaae20c]
[fv-az1771-923:06724] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdabfaae277]
[fv-az1771-923:06724] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdabfaae52b]
[fv-az1771-923:06724] [ 8] plumed_master(+0x14274)[0x557cc7592274]
[fv-az1771-923:06724] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdabf629d90]
[fv-az1771-923:06724] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdabf629e40]
[fv-az1771-923:06724] [11] plumed_master(+0x14ed5)[0x557cc7592ed5]
[fv-az1771-923:06724] *** End of error message ***
</pre>
{% endraw %}
