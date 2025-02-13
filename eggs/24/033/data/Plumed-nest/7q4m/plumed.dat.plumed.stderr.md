**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az1046-619:05456] *** Process received signal ***
[fv-az1046-619:05456] Signal: Aborted (6)
[fv-az1046-619:05456] Signal code:  (-6)
[fv-az1046-619:05456] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd9ede45330]
[fv-az1046-619:05456] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd9ede9eb2c]
[fv-az1046-619:05456] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd9ede4527e]
[fv-az1046-619:05456] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9ede288ff]
[fv-az1046-619:05456] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9ee2a5ff5]
[fv-az1046-619:05456] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9ee2bb0da]
[fv-az1046-619:05456] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9ee2a5a55]
[fv-az1046-619:05456] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9ee2a5a6f]
[fv-az1046-619:05456] [ 8] plumed(+0x146dd)[0x55de8521d6dd]
[fv-az1046-619:05456] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd9ede2a1ca]
[fv-az1046-619:05456] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd9ede2a28b]
[fv-az1046-619:05456] [11] plumed(+0x15365)[0x55de8521e365]
[fv-az1046-619:05456] *** End of error message ***
</pre>
{% endraw %}
