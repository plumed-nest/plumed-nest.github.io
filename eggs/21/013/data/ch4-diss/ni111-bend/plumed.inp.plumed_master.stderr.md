**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-bend/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.jqV1Nx/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1530-541:08773] *** Process received signal ***
[fv-az1530-541:08773] Signal: Aborted (6)
[fv-az1530-541:08773] Signal code:  (-6)
[fv-az1530-541:08773] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fed26e42520]
[fv-az1530-541:08773] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fed26e969fc]
[fv-az1530-541:08773] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fed26e42476]
[fv-az1530-541:08773] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fed26e287f3]
[fv-az1530-541:08773] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fed272a2b9e]
[fv-az1530-541:08773] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fed272ae20c]
[fv-az1530-541:08773] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fed272ae277]
[fv-az1530-541:08773] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fed272ae52b]
[fv-az1530-541:08773] [ 8] plumed_master(+0x14274)[0x5557f3d0f274]
[fv-az1530-541:08773] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fed26e29d90]
[fv-az1530-541:08773] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fed26e29e40]
[fv-az1530-541:08773] [11] plumed_master(+0x14ed5)[0x5557f3d0fed5]
[fv-az1530-541:08773] *** End of error message ***
</pre>
{% endraw %}
