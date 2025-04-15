**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  da-wt/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.xPG5nV/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[fv-az1370-99:64939] *** Process received signal ***
[fv-az1370-99:64939] Signal: Aborted (6)
[fv-az1370-99:64939] Signal code:  (-6)
[fv-az1370-99:64939] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc23645330]
[fv-az1370-99:64939] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc2369eb2c]
[fv-az1370-99:64939] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc2364527e]
[fv-az1370-99:64939] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc236288ff]
[fv-az1370-99:64939] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc23aa5ff5]
[fv-az1370-99:64939] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc23abb0da]
[fv-az1370-99:64939] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc23aa5a55]
[fv-az1370-99:64939] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc23aa5a6f]
[fv-az1370-99:64939] [ 8] plumed(+0x146dd)[0x5558fc8456dd]
[fv-az1370-99:64939] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc2362a1ca]
[fv-az1370-99:64939] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc2362a28b]
[fv-az1370-99:64939] [11] plumed(+0x15365)[0x5558fc846365]
[fv-az1370-99:64939] *** End of error message ***
</pre>
{% endraw %}
