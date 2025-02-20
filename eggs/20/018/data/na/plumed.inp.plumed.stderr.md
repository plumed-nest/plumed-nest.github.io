**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.0emscR/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10b.so ../src/bias/ReweightGeomFES.cpp

[fv-az1372-996:12939] *** Process received signal ***
[fv-az1372-996:12939] Signal: Aborted (6)
[fv-az1372-996:12939] Signal code:  (-6)
[fv-az1372-996:12939] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa5f045330]
[fv-az1372-996:12939] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa5f09eb2c]
[fv-az1372-996:12939] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa5f04527e]
[fv-az1372-996:12939] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa5f0288ff]
[fv-az1372-996:12939] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa5f4a5ff5]
[fv-az1372-996:12939] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa5f4bb0da]
[fv-az1372-996:12939] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa5f4a5a55]
[fv-az1372-996:12939] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa5f4a5a6f]
[fv-az1372-996:12939] [ 8] plumed(+0x146dd)[0x5574f58316dd]
[fv-az1372-996:12939] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa5f02a1ca]
[fv-az1372-996:12939] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa5f02a28b]
[fv-az1372-996:12939] [11] plumed(+0x15365)[0x5574f5832365]
[fv-az1372-996:12939] *** End of error message ***
</pre>
{% endraw %}
