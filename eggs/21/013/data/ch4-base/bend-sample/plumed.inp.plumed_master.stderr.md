**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[fv-az787-589:65051] *** Process received signal ***
[fv-az787-589:65051] Signal: Aborted (6)
[fv-az787-589:65051] Signal code:  (-6)
[fv-az787-589:65051] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f96d4e45330]
[fv-az787-589:65051] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f96d4e9eb2c]
[fv-az787-589:65051] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f96d4e4527e]
[fv-az787-589:65051] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f96d4e288ff]
[fv-az787-589:65051] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96d52a5ff5]
[fv-az787-589:65051] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96d52bb0da]
[fv-az787-589:65051] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96d52a5a55]
[fv-az787-589:65051] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96d52a5a6f]
[fv-az787-589:65051] [ 8] plumed_master(+0x146dd)[0x5570747156dd]
[fv-az787-589:65051] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f96d4e2a1ca]
[fv-az787-589:65051] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f96d4e2a28b]
[fv-az787-589:65051] [11] plumed_master(+0x15365)[0x557074716365]
[fv-az787-589:65051] *** End of error message ***
</pre>
{% endraw %}
