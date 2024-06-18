**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.FpdyWi/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.10.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az1215-453:09104] *** Process received signal ***
[fv-az1215-453:09104] Signal: Aborted (6)
[fv-az1215-453:09104] Signal code:  (-6)
[fv-az1215-453:09104] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7ffe042520]
[fv-az1215-453:09104] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7ffe0969fc]
[fv-az1215-453:09104] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7ffe042476]
[fv-az1215-453:09104] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7ffe0287f3]
[fv-az1215-453:09104] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7ffe4a2b9e]
[fv-az1215-453:09104] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7ffe4ae20c]
[fv-az1215-453:09104] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7ffe4ae277]
[fv-az1215-453:09104] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7ffe4ae52b]
[fv-az1215-453:09104] [ 8] plumed_master(+0x14274)[0x557a886bc274]
[fv-az1215-453:09104] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7ffe029d90]
[fv-az1215-453:09104] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7ffe029e40]
[fv-az1215-453:09104] [11] plumed_master(+0x14ed5)[0x557a886bced5]
[fv-az1215-453:09104] *** End of error message ***
</pre>
{% endraw %}
