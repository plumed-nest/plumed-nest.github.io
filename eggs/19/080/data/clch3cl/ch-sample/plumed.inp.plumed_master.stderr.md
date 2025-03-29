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
[fv-az789-879:65706] *** Process received signal ***
[fv-az789-879:65706] Signal: Aborted (6)
[fv-az789-879:65706] Signal code:  (-6)
[fv-az789-879:65706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbb7045330]
[fv-az789-879:65706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbb709eb2c]
[fv-az789-879:65706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbb704527e]
[fv-az789-879:65706] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbb70288ff]
[fv-az789-879:65706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbb74a5ff5]
[fv-az789-879:65706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbb74bb0da]
[fv-az789-879:65706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbb74a5a55]
[fv-az789-879:65706] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbb74a5a6f]
[fv-az789-879:65706] [ 8] plumed_master(+0x146dd)[0x55d4811a96dd]
[fv-az789-879:65706] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbb702a1ca]
[fv-az789-879:65706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbb702a28b]
[fv-az789-879:65706] [11] plumed_master(+0x15365)[0x55d4811aa365]
[fv-az789-879:65706] *** End of error message ***
</pre>
{% endraw %}
