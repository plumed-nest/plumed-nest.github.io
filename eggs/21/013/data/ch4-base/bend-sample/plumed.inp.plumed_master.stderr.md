**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[fv-az1360-658:08575] *** Process received signal ***
[fv-az1360-658:08575] Signal: Aborted (6)
[fv-az1360-658:08575] Signal code:  (-6)
[fv-az1360-658:08575] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f73a8245330]
[fv-az1360-658:08575] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f73a829eb2c]
[fv-az1360-658:08575] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f73a824527e]
[fv-az1360-658:08575] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f73a82288ff]
[fv-az1360-658:08575] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73a86a5ff5]
[fv-az1360-658:08575] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73a86bb0da]
[fv-az1360-658:08575] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73a86a5a55]
[fv-az1360-658:08575] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73a86a5a6f]
[fv-az1360-658:08575] [ 8] plumed_master(+0x146dd)[0x5598aeff86dd]
[fv-az1360-658:08575] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f73a822a1ca]
[fv-az1360-658:08575] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f73a822a28b]
[fv-az1360-658:08575] [11] plumed_master(+0x15365)[0x5598aeff9365]
[fv-az1360-658:08575] *** End of error message ***
</pre>
{% endraw %}
