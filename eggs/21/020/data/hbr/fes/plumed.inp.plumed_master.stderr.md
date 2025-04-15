**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1277-646:67085] *** Process received signal ***
[fv-az1277-646:67085] Signal: Aborted (6)
[fv-az1277-646:67085] Signal code:  (-6)
[fv-az1277-646:67085] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f46a45330]
[fv-az1277-646:67085] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f46a9eb2c]
[fv-az1277-646:67085] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f46a4527e]
[fv-az1277-646:67085] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f46a288ff]
[fv-az1277-646:67085] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f46ea5ff5]
[fv-az1277-646:67085] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f46ebb0da]
[fv-az1277-646:67085] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f46ea5a55]
[fv-az1277-646:67085] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f46ea5a6f]
[fv-az1277-646:67085] [ 8] plumed_master(+0x146dd)[0x55e7011486dd]
[fv-az1277-646:67085] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f46a2a1ca]
[fv-az1277-646:67085] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f46a2a28b]
[fv-az1277-646:67085] [11] plumed_master(+0x15365)[0x55e701149365]
[fv-az1277-646:67085] *** End of error message ***
</pre>
{% endraw %}
