**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.OJ1nbO/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.10b.so ../../code/ReweightGeomFES.cpp

[fv-az1719-82:62275] *** Process received signal ***
[fv-az1719-82:62275] Signal: Aborted (6)
[fv-az1719-82:62275] Signal code:  (-6)
[fv-az1719-82:62275] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34b5645330]
[fv-az1719-82:62275] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34b569eb2c]
[fv-az1719-82:62275] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34b564527e]
[fv-az1719-82:62275] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34b56288ff]
[fv-az1719-82:62275] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34b5aa5ff5]
[fv-az1719-82:62275] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34b5abb0da]
[fv-az1719-82:62275] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34b5aa5a55]
[fv-az1719-82:62275] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34b5aa5a6f]
[fv-az1719-82:62275] [ 8] plumed(+0x146dd)[0x55b235cdc6dd]
[fv-az1719-82:62275] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34b562a1ca]
[fv-az1719-82:62275] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34b562a28b]
[fv-az1719-82:62275] [11] plumed(+0x15365)[0x55b235cdd365]
[fv-az1719-82:62275] *** End of error message ***
</pre>
{% endraw %}
