**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az1719-82:68578] *** Process received signal ***
[fv-az1719-82:68578] Signal: Aborted (6)
[fv-az1719-82:68578] Signal code:  (-6)
[fv-az1719-82:68578] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b39245330]
[fv-az1719-82:68578] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b3929eb2c]
[fv-az1719-82:68578] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b3924527e]
[fv-az1719-82:68578] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b392288ff]
[fv-az1719-82:68578] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b396a5ff5]
[fv-az1719-82:68578] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b396bb0da]
[fv-az1719-82:68578] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b396a5a55]
[fv-az1719-82:68578] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b396a5a6f]
[fv-az1719-82:68578] [ 8] plumed_master(+0x146dd)[0x55d49c4a76dd]
[fv-az1719-82:68578] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b3922a1ca]
[fv-az1719-82:68578] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b3922a28b]
[fv-az1719-82:68578] [11] plumed_master(+0x15365)[0x55d49c4a8365]
[fv-az1719-82:68578] *** End of error message ***
</pre>
{% endraw %}
