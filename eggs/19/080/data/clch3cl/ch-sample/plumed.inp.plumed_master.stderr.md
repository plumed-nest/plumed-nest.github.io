**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[fv-az2209-645:68081] *** Process received signal ***
[fv-az2209-645:68081] Signal: Aborted (6)
[fv-az2209-645:68081] Signal code:  (-6)
[fv-az2209-645:68081] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f161fe45330]
[fv-az2209-645:68081] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f161fe9eb2c]
[fv-az2209-645:68081] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f161fe4527e]
[fv-az2209-645:68081] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f161fe288ff]
[fv-az2209-645:68081] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f16202a5ff5]
[fv-az2209-645:68081] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f16202bb0da]
[fv-az2209-645:68081] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f16202a5a55]
[fv-az2209-645:68081] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f16202a5a6f]
[fv-az2209-645:68081] [ 8] plumed_master(+0x146dd)[0x55a17edfb6dd]
[fv-az2209-645:68081] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f161fe2a1ca]
[fv-az2209-645:68081] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f161fe2a28b]
[fv-az2209-645:68081] [11] plumed_master(+0x15365)[0x55a17edfc365]
[fv-az2209-645:68081] *** End of error message ***
</pre>
{% endraw %}
