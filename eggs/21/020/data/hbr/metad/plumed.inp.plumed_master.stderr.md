**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1277-646:67175] *** Process received signal ***
[fv-az1277-646:67175] Signal: Aborted (6)
[fv-az1277-646:67175] Signal code:  (-6)
[fv-az1277-646:67175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd5ba445330]
[fv-az1277-646:67175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd5ba49eb2c]
[fv-az1277-646:67175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd5ba44527e]
[fv-az1277-646:67175] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd5ba4288ff]
[fv-az1277-646:67175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd5ba8a5ff5]
[fv-az1277-646:67175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd5ba8bb0da]
[fv-az1277-646:67175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd5ba8a5a55]
[fv-az1277-646:67175] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd5ba8a5a6f]
[fv-az1277-646:67175] [ 8] plumed_master(+0x146dd)[0x55af5725c6dd]
[fv-az1277-646:67175] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd5ba42a1ca]
[fv-az1277-646:67175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd5ba42a28b]
[fv-az1277-646:67175] [11] plumed_master(+0x15365)[0x55af5725d365]
[fv-az1277-646:67175] *** End of error message ***
</pre>
{% endraw %}
