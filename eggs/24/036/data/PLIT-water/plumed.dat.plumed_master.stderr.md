**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az1360-658:05681] *** Process received signal ***
[fv-az1360-658:05681] Signal: Aborted (6)
[fv-az1360-658:05681] Signal code:  (-6)
[fv-az1360-658:05681] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f59b2245330]
[fv-az1360-658:05681] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f59b229eb2c]
[fv-az1360-658:05681] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f59b224527e]
[fv-az1360-658:05681] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59b22288ff]
[fv-az1360-658:05681] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f59b26a5ff5]
[fv-az1360-658:05681] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f59b26bb0da]
[fv-az1360-658:05681] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f59b26a5a55]
[fv-az1360-658:05681] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f59b26a5a6f]
[fv-az1360-658:05681] [ 8] plumed_master(+0x146dd)[0x563828fc46dd]
[fv-az1360-658:05681] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f59b222a1ca]
[fv-az1360-658:05681] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f59b222a28b]
[fv-az1360-658:05681] [11] plumed_master(+0x15365)[0x563828fc5365]
[fv-az1360-658:05681] *** End of error message ***
</pre>
{% endraw %}
