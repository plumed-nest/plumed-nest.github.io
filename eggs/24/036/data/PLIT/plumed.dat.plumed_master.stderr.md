**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az1360-658:05531] *** Process received signal ***
[fv-az1360-658:05531] Signal: Aborted (6)
[fv-az1360-658:05531] Signal code:  (-6)
[fv-az1360-658:05531] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f022b245330]
[fv-az1360-658:05531] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f022b29eb2c]
[fv-az1360-658:05531] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f022b24527e]
[fv-az1360-658:05531] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f022b2288ff]
[fv-az1360-658:05531] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f022b6a5ff5]
[fv-az1360-658:05531] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f022b6bb0da]
[fv-az1360-658:05531] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f022b6a5a55]
[fv-az1360-658:05531] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f022b6a5a6f]
[fv-az1360-658:05531] [ 8] plumed_master(+0x146dd)[0x55bad78846dd]
[fv-az1360-658:05531] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f022b22a1ca]
[fv-az1360-658:05531] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f022b22a28b]
[fv-az1360-658:05531] [11] plumed_master(+0x15365)[0x55bad7885365]
[fv-az1360-658:05531] *** End of error message ***
</pre>
{% endraw %}
