**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[fv-az1693-854:05640] *** Process received signal ***
[fv-az1693-854:05640] Signal: Aborted (6)
[fv-az1693-854:05640] Signal code:  (-6)
[fv-az1693-854:05640] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0216045330]
[fv-az1693-854:05640] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f021609eb2c]
[fv-az1693-854:05640] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f021604527e]
[fv-az1693-854:05640] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02160288ff]
[fv-az1693-854:05640] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02164a5ff5]
[fv-az1693-854:05640] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02164bb0da]
[fv-az1693-854:05640] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02164a5a55]
[fv-az1693-854:05640] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02164a5a6f]
[fv-az1693-854:05640] [ 8] plumed_master(+0x146dd)[0x558885d246dd]
[fv-az1693-854:05640] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f021602a1ca]
[fv-az1693-854:05640] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f021602a28b]
[fv-az1693-854:05640] [11] plumed_master(+0x15365)[0x558885d25365]
[fv-az1693-854:05640] *** End of error message ***
</pre>
{% endraw %}
