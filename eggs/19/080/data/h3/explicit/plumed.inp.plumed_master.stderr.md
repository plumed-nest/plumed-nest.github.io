**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az789-879:65794] *** Process received signal ***
[fv-az789-879:65794] Signal: Aborted (6)
[fv-az789-879:65794] Signal code:  (-6)
[fv-az789-879:65794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ffe845330]
[fv-az789-879:65794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ffe89eb2c]
[fv-az789-879:65794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ffe84527e]
[fv-az789-879:65794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ffe8288ff]
[fv-az789-879:65794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ffeca5ff5]
[fv-az789-879:65794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ffecbb0da]
[fv-az789-879:65794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ffeca5a55]
[fv-az789-879:65794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ffeca5a6f]
[fv-az789-879:65794] [ 8] plumed_master(+0x146dd)[0x56114f7a86dd]
[fv-az789-879:65794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ffe82a1ca]
[fv-az789-879:65794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ffe82a28b]
[fv-az789-879:65794] [11] plumed_master(+0x15365)[0x56114f7a9365]
[fv-az789-879:65794] *** End of error message ***
</pre>
{% endraw %}
