**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.lZwq97/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[fv-az585-767:08160] *** Process received signal ***
[fv-az585-767:08160] Signal: Aborted (6)
[fv-az585-767:08160] Signal code:  (-6)
[fv-az585-767:08160] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd012c42520]
[fv-az585-767:08160] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd012c969fc]
[fv-az585-767:08160] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd012c42476]
[fv-az585-767:08160] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd012c287f3]
[fv-az585-767:08160] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd0130a2b9e]
[fv-az585-767:08160] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd0130ae20c]
[fv-az585-767:08160] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd0130ae277]
[fv-az585-767:08160] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd0130ae52b]
[fv-az585-767:08160] [ 8] plumed(+0x14254)[0x556d484ab254]
[fv-az585-767:08160] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd012c29d90]
[fv-az585-767:08160] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd012c29e40]
[fv-az585-767:08160] [11] plumed(+0x14eb5)[0x556d484abeb5]
[fv-az585-767:08160] *** End of error message ***
</pre>
{% endraw %}
