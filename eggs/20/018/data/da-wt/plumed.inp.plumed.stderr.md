**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.g6HT73/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[fv-az1983-395:66345] *** Process received signal ***
[fv-az1983-395:66345] Signal: Aborted (6)
[fv-az1983-395:66345] Signal code:  (-6)
[fv-az1983-395:66345] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe72ca45330]
[fv-az1983-395:66345] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe72ca9eb2c]
[fv-az1983-395:66345] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe72ca4527e]
[fv-az1983-395:66345] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe72ca288ff]
[fv-az1983-395:66345] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe72cea5ff5]
[fv-az1983-395:66345] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe72cebb0da]
[fv-az1983-395:66345] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe72cea5a55]
[fv-az1983-395:66345] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe72cea5a6f]
[fv-az1983-395:66345] [ 8] plumed(+0x146dd)[0x5559ef0df6dd]
[fv-az1983-395:66345] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe72ca2a1ca]
[fv-az1983-395:66345] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe72ca2a28b]
[fv-az1983-395:66345] [11] plumed(+0x15365)[0x5559ef0e0365]
[fv-az1983-395:66345] *** End of error message ***
</pre>
{% endraw %}
