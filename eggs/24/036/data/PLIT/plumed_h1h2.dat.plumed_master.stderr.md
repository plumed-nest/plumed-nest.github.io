**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[fv-az1360-658:05571] *** Process received signal ***
[fv-az1360-658:05571] Signal: Aborted (6)
[fv-az1360-658:05571] Signal code:  (-6)
[fv-az1360-658:05571] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fae33845330]
[fv-az1360-658:05571] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fae3389eb2c]
[fv-az1360-658:05571] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fae3384527e]
[fv-az1360-658:05571] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fae338288ff]
[fv-az1360-658:05571] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fae33ca5ff5]
[fv-az1360-658:05571] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fae33cbb0da]
[fv-az1360-658:05571] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fae33ca5a55]
[fv-az1360-658:05571] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fae33ca5a6f]
[fv-az1360-658:05571] [ 8] plumed_master(+0x146dd)[0x56231a8e86dd]
[fv-az1360-658:05571] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fae3382a1ca]
[fv-az1360-658:05571] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fae3382a28b]
[fv-az1360-658:05571] [11] plumed_master(+0x15365)[0x56231a8e9365]
[fv-az1360-658:05571] *** End of error message ***
</pre>
{% endraw %}
