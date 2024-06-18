**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.TnEe0S/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1215-453:08746] *** Process received signal ***
[fv-az1215-453:08746] Signal: Aborted (6)
[fv-az1215-453:08746] Signal code:  (-6)
[fv-az1215-453:08746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2d03442520]
[fv-az1215-453:08746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2d034969fc]
[fv-az1215-453:08746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2d03442476]
[fv-az1215-453:08746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2d034287f3]
[fv-az1215-453:08746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2d038a2b9e]
[fv-az1215-453:08746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2d038ae20c]
[fv-az1215-453:08746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2d038ae277]
[fv-az1215-453:08746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2d038ae52b]
[fv-az1215-453:08746] [ 8] plumed_master(+0x14274)[0x5607e294d274]
[fv-az1215-453:08746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2d03429d90]
[fv-az1215-453:08746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2d03429e40]
[fv-az1215-453:08746] [11] plumed_master(+0x14ed5)[0x5607e294ded5]
[fv-az1215-453:08746] *** End of error message ***
</pre>
{% endraw %}
