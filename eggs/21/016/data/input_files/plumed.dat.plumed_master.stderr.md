**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az1979-234:65399] *** Process received signal ***
[fv-az1979-234:65399] Signal: Aborted (6)
[fv-az1979-234:65399] Signal code:  (-6)
[fv-az1979-234:65399] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1eb5445330]
[fv-az1979-234:65399] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1eb549eb2c]
[fv-az1979-234:65399] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1eb544527e]
[fv-az1979-234:65399] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1eb54288ff]
[fv-az1979-234:65399] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1eb58a5ff5]
[fv-az1979-234:65399] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1eb58bb0da]
[fv-az1979-234:65399] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1eb58a5a55]
[fv-az1979-234:65399] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1eb58a5a6f]
[fv-az1979-234:65399] [ 8] plumed_master(+0x146dd)[0x55a2dc6a06dd]
[fv-az1979-234:65399] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1eb542a1ca]
[fv-az1979-234:65399] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1eb542a28b]
[fv-az1979-234:65399] [11] plumed_master(+0x15365)[0x55a2dc6a1365]
[fv-az1979-234:65399] *** End of error message ***
</pre>
{% endraw %}
