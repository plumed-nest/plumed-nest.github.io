**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.FU3V9O/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.11.0-dev.so ../src/bias/ReweightGeomFES.cpp

[fv-az1279-218:65745] *** Process received signal ***
[fv-az1279-218:65745] Signal: Aborted (6)
[fv-az1279-218:65745] Signal code:  (-6)
[fv-az1279-218:65745] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f266d245330]
[fv-az1279-218:65745] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f266d29eb2c]
[fv-az1279-218:65745] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f266d24527e]
[fv-az1279-218:65745] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f266d2288ff]
[fv-az1279-218:65745] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f266d6a5ff5]
[fv-az1279-218:65745] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f266d6bb0da]
[fv-az1279-218:65745] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f266d6a5a55]
[fv-az1279-218:65745] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f266d6a5a6f]
[fv-az1279-218:65745] [ 8] plumed_master(+0x146dd)[0x561c6f3ee6dd]
[fv-az1279-218:65745] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f266d22a1ca]
[fv-az1279-218:65745] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f266d22a28b]
[fv-az1279-218:65745] [11] plumed_master(+0x15365)[0x561c6f3ef365]
[fv-az1279-218:65745] *** End of error message ***
</pre>
{% endraw %}
