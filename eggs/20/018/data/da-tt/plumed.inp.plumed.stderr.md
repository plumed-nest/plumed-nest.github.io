**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-tt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.p8KXef/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[fv-az1372-996:12674] *** Process received signal ***
[fv-az1372-996:12674] Signal: Aborted (6)
[fv-az1372-996:12674] Signal code:  (-6)
[fv-az1372-996:12674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7dbb645330]
[fv-az1372-996:12674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7dbb69eb2c]
[fv-az1372-996:12674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7dbb64527e]
[fv-az1372-996:12674] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7dbb6288ff]
[fv-az1372-996:12674] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7dbbaa5ff5]
[fv-az1372-996:12674] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7dbbabb0da]
[fv-az1372-996:12674] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7dbbaa5a55]
[fv-az1372-996:12674] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7dbbaa5a6f]
[fv-az1372-996:12674] [ 8] plumed(+0x146dd)[0x5618fda826dd]
[fv-az1372-996:12674] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7dbb62a1ca]
[fv-az1372-996:12674] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7dbb62a28b]
[fv-az1372-996:12674] [11] plumed(+0x15365)[0x5618fda83365]
[fv-az1372-996:12674] *** End of error message ***
</pre>
{% endraw %}
