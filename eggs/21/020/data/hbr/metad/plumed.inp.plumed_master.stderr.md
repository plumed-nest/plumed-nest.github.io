**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1280-696:11795] *** Process received signal ***
[fv-az1280-696:11795] Signal: Aborted (6)
[fv-az1280-696:11795] Signal code:  (-6)
[fv-az1280-696:11795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f22845330]
[fv-az1280-696:11795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f2289eb2c]
[fv-az1280-696:11795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f2284527e]
[fv-az1280-696:11795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f228288ff]
[fv-az1280-696:11795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f22ca5ff5]
[fv-az1280-696:11795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f22cbb0da]
[fv-az1280-696:11795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f22ca5a55]
[fv-az1280-696:11795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f22ca5a6f]
[fv-az1280-696:11795] [ 8] plumed_master(+0x146dd)[0x562fc48766dd]
[fv-az1280-696:11795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f2282a1ca]
[fv-az1280-696:11795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f2282a28b]
[fv-az1280-696:11795] [11] plumed_master(+0x15365)[0x562fc4877365]
[fv-az1280-696:11795] *** End of error message ***
</pre>
{% endraw %}
