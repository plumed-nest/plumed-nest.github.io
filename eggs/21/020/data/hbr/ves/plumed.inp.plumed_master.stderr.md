**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az2207-973:10036] *** Process received signal ***
[fv-az2207-973:10036] Signal: Aborted (6)
[fv-az2207-973:10036] Signal code:  (-6)
[fv-az2207-973:10036] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f37f5045330]
[fv-az2207-973:10036] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f37f509eb2c]
[fv-az2207-973:10036] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f37f504527e]
[fv-az2207-973:10036] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f37f50288ff]
[fv-az2207-973:10036] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37f54a5ff5]
[fv-az2207-973:10036] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37f54bb0da]
[fv-az2207-973:10036] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37f54a5a55]
[fv-az2207-973:10036] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37f54a5a6f]
[fv-az2207-973:10036] [ 8] plumed_master(+0x146dd)[0x55f65cdfd6dd]
[fv-az2207-973:10036] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f37f502a1ca]
[fv-az2207-973:10036] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f37f502a28b]
[fv-az2207-973:10036] [11] plumed_master(+0x15365)[0x55f65cdfe365]
[fv-az2207-973:10036] *** End of error message ***
</pre>
{% endraw %}
